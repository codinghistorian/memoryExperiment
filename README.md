# memoryExperiment
would initializing uint128 variable cheaper than uint125 in memory?

Answer: No difference

Proofs:

In case of using uint64
![uint64 fn call](./testUint64.png?raw=true "Uint64")


In case of using uint128
![uint128 fn call](./testUint128.png?raw=true "Uint128")


In case of usint uint256
![uint256 fn call](./testUint256.png?raw=true "Uint256")

