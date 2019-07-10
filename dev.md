Smart contract development:

- navigate to ledger repo and build it

Interpreter only:
```
./apps/etch/etch ../../etch-examples/02_erc20/contract.etch
```

Against ledger:
```
cd build/apps/constellation && rm -f *.db && ./constellation -port 8000 -block-interval 300 -standalone
```

deploy:

