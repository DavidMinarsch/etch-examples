How can you get a contract's address?
- Ethereum: Address(this)

How can you access the value attached to a msg (in FET)?
- Ethereum: msg.value

How can you access the value attached to a contract (in FET)?

Why can the sender address not be always available and by default signed?
- Ethereum: self.sender

How can I instantiate another contract in a contract?
- e.g.: open_ERC20_contract = ERC20(open_contract_address);

This (^) is needed for contract to contract calls:
- e.g.: open_ERC20_contract.transfer(...)

How can a contract self-destruct at the end of its lifetime?
- e.g.: selfdestruct(some_address) where some_address receives remaining funds 

How can a contract send some of its funds?
- e.g.: send(some_address, some_amount)