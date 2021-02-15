# Anoma ledger prototype

Handy commands:

```shell
# Build
make

# Build and link the executables
make install

# Run Anoma daemon (this will also initialize and run Tendermint node)
make run

# Reset the state (resets Tendermint too)
anoma reset

# Submit a transaction to the Tendermint node
anoma transfer -c 1
```