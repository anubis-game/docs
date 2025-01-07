# Arbitrum Sepolia

<details>

<summary>Registry-USDC (v0.3.0)</summary>

[<mark style="color:purple;">**address**</mark>](https://sepolia.arbiscan.io/address/0x9632185d3851Fd06304C09BA6F1c1308189BE12b)

```
0x9632185d3851Fd06304C09BA6F1c1308189BE12b
```

<mark style="color:purple;">**deployment**</mark>

```
npx hardhat ignition deploy ./ignition/modules/testnet/Registry.ts --network arbitrum-sepolia
```

<mark style="color:purple;">**configuration**</mark>

```json
[
  "0xAD63B2262EB7D1591Ee8E6a85959a523dEce7983", // Owner Address (Arbitrum Deployer Wallet)
  "0x75faf114eafb1BDbe2F0316DF893fd58CE46AA4d", // Token Address (USDC on Arbitrum Sepolia)
  100000, //                                       Buyin Amount  (0.1 USDC with 6 decimals)
]
```

<mark style="color:purple;">**verification**</mark>

```
npx hardhat verify --network arbitrum-sepolia 0x9632185d3851Fd06304C09BA6F1c1308189BE12b "0xAD63B2262EB7D1591Ee8E6a85959a523dEce7983" "0x75faf114eafb1BDbe2F0316DF893fd58CE46AA4d" "100000"
```

[<mark style="color:purple;">**version**</mark>](https://github.com/anubis-game/contracts/tree/v0.3.0)

```
v0.3.0
```

</details>

<details>

<summary>Registry-USDC (v0.4.0)</summary>

[<mark style="color:purple;">**address**</mark>](https://sepolia.arbiscan.io/address/0x2fe8873afD3728C1cED0329b450d617FC235b4dB)

```
0x2fe8873afD3728C1cED0329b450d617FC235b4dB
```

<mark style="color:purple;">**deployment**</mark>

```
npx hardhat ignition deploy ./ignition/modules/testnet/Registry.ts --network arbitrum-sepolia
```

<mark style="color:purple;">**configuration**</mark>

```json
[
  "0xAD63B2262EB7D1591Ee8E6a85959a523dEce7983", // Owner Address (Arbitrum Deployer Wallet)
  "0x75faf114eafb1BDbe2F0316DF893fd58CE46AA4d", // Token Address (USDC on Arbitrum Sepolia)
  100000, //                                       Buyin Amount  (0.1 USDC with 6 decimals)
]
```

<mark style="color:purple;">**verification**</mark>

```
npx hardhat verify --network arbitrum-sepolia 0x2fe8873afD3728C1cED0329b450d617FC235b4dB "0xAD63B2262EB7D1591Ee8E6a85959a523dEce7983" "0x75faf114eafb1BDbe2F0316DF893fd58CE46AA4d" "100000"
```

[<mark style="color:purple;">**version**</mark>](https://github.com/anubis-game/contracts/releases/tag/v0.4.0)

```
v0.4.0
```

</details>

