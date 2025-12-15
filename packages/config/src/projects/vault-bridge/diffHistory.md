Generated with discovered.json: 0xc7e758ae58e547bbf3548ac73f475617b061a579

# Diff at Mon, 15 Dec 2025 16:22:48 GMT:

- author: Simon Dos (<sdosch@polygon.technology>)
- current timestamp: 1765815656

## Description

Discovery rerun on the same block number with only config-related changes.

## Initial discovery

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0x14Be6579A41342ca6B402ec85E7be538e6Ade951)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Yearn Strategist Multisig (eth:0x16388463d60FFE0661Cf7F1f31a7D658aC790ff7)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Safe (eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0x263b251D67BB154DD6b8352539466ACE7948ED56)
    +++ description: None
```

```diff
+   Status: CREATED
    contract vbWBTC (eth:0x2C24B57e2CCd1f273045Af6A5f632504C432374F)
    +++ description: This token contract uses a standard 'vault bridge token' implementation created by Agglayer CDK. It keeps deposited assets in a vault and issues an IOU token (Vault Bridge WBTC) which can be deposited to Agglayer. The underlying asset is generating yield, which does not accrue to the vbWBTC-IOU but is sent to eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50.
```

```diff
+   Status: CREATED
    contract VbETH (eth:0x2DC70fb75b88d2eB4715bc06E1595E6D97c34DFF)
    +++ description: This token contract uses a standard 'vault bridge token' implementation created by Agglayer CDK. It keeps deposited assets in a vault and issues an IOU token (Vault Bridge ETH) which can be deposited to Agglayer. The underlying asset is generating yield, which does not accrue to the vbETH-IOU but is sent to eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50.
```

```diff
+   Status: CREATED
    contract Katana vaultBridge Multisig 1 (eth:0x2De242e27386e224E5fbF110EA8406d5B70740ec)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0x377a9e5df2882DC1DF8A0bD162cbc640eA634010)
    +++ description: None
```

```diff
+   Status: CREATED
    contract vbUSDS (eth:0x3DD459dE96F9C28e3a343b831cbDC2B93c8C4855)
    +++ description: This token contract uses a standard 'vault bridge token' implementation created by Agglayer CDK. It keeps deposited assets in a vault and issues an IOU token (Vault Bridge USDS) which can be deposited to Agglayer. The underlying asset is generating yield, which does not accrue to the vbUSDS-IOU but is sent to eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50.
```

```diff
+   Status: CREATED
    contract Safe (eth:0x3e86A8bcAF0A96DD16Ec8160532DA13b2C0f6e21)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MigrationManager (eth:0x417d01B64Ea30C4E163873f3a1f77b727c689e02)
    +++ description: Helper contract for the vaultBridge tokens on Layer 2. If any vbTokens are minted 'natively' on Layer 2, this contract can receive the underlying assets and lock them in the Layer 1 vaults.
```

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0x420693B32113a0e00Eb9f3315D5D5ec3b32C2d69)
    +++ description: None
```

```diff
+   Status: CREATED
    contract vbUSDC (eth:0x53E82ABbb12638F09d9e624578ccB666217a765e)
    +++ description: This token contract uses a standard 'vault bridge token' implementation created by Agglayer CDK. It keeps deposited assets in a vault and issues an IOU token (Vault Bridge USDC) which can be deposited to Agglayer. The underlying asset is generating yield, which does not accrue to the vbUSDC-IOU but is sent to eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50.
```

```diff
+   Status: CREATED
    contract Katana yieldRecipient Mulsitig (eth:0x67C912fF560951526BffDff66dFbD4DF8AE23756)
    +++ description: None
```

```diff
+   Status: CREATED
    contract vbUSDT (eth:0x6d4f9f9f8f0155509ecd6Ac6c544fF27999845CC)
    +++ description: This token contract uses a standard 'vault bridge token' implementation created by Agglayer CDK. It keeps deposited assets in a vault and issues an IOU token (Vault Bridge USDT) which can be deposited to Agglayer. The underlying asset is generating yield, which does not accrue to the vbUSDT-IOU but is sent to eth:0x261a25ec6c396389B75B6b22BD4A8227070E3B50.
```

```diff
+   Status: CREATED
    contract Katana Steakhouse Financial / Morpho Multisig (eth:0x827e86072B06674a077f592A531dcE4590aDeCdB)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0x8970650CF3f1E57cA804C65B4DBcFf698789FE30)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Polygon Labs Engineering/Security Multisig (eth:0x9d851f8b8751c5FbC09b9E74E6e68E9950949052)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Katana vaultBridge Multisig 2 (eth:0xA8C31B2edd84c654d06d626383f4154D1E40C5Ff)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Polygon Multisig 2 (eth:0xd0673F989bc3BA9314d0AAF28BfC84e99B7898CC)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (eth:0xD1e389c046FB734D2a0c7C390312210c408ba832)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Katana vaultBridge Multisig 3 (eth:0xf4F2f5F6bAdBE05433C4604320ecC56BbECBC04E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Safe (eth:0xFA58659F64a393A6E1A548ABc70Ad2CfE1e8f9Cb)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GenericNativeConverter (katana:0x053FA9b934b83E1E0ffc7e98a41aAdc3640bB462)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Vault Bridge WBTC Token (katana:0x0913DA6Da4b42f538B445599b46Bb4622342Cf52)
    +++ description: None
```

```diff
+   Status: CREATED
    contract  (katana:0x0F99738B2Fc14D77308337f3e2596b63aE7BCC4A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (katana:0x10B6c57633Cc1fc20ACFEB3077EfB5C9bF680EfE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (katana:0x1393877F862DbF90Da55B8dd28DAAC34Fcb769b3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Vault Bridge USDC Token (katana:0x203A662b0BD271A6ed5a60EdFbd04bFce608FD36)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0x2134866886ce784fE2E0DE819118E4D32b4Be32C)
    +++ description: None
```

```diff
+   Status: CREATED
    contract BridgeL2SovereignChain (katana:0x2a3DD3EB832aF982ec71669E178424b10Dca2EDe)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Vault Bridge USDT Token (katana:0x2DCa96907fde857dd3D816880A0df407eeB2D2F2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract BytecodeStorer (katana:0x357e3fC9B1a802C12fB6Bf8203d8BDaa610C6E4D)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafeL2 (katana:0x4e981bAe8E3cd06Ca911ffFE5504B2653ac1C38a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Vault Bridge USDS Token (katana:0x62D6A123E8D19d06d68cf0d2294F9A3A0362c6b3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GenericNativeConverter (katana:0x639f13D5f30B47c792b6851238c05D0b623C77DE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (katana:0x659a517251b9148eD580832043dAE36B6f231Dfb)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0x815955d051C6262C16c720b19D735426254Bec5B)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GenericNativeConverter (katana:0x97a3500083348A147F419b8a65717909762c389f)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GlobalExitRootManagerL2SovereignChain (katana:0xa40D5f56745a118D0906a34E69aeC8C0Db1cB8fA)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WETHNativeConverter (katana:0xa6B0DB1293144Ebe9478B6a84F75dd651E45914a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GenericNativeConverter (katana:0xb00aa68b87256E2F22058fB2Ba3246EEc54A44fc)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0xB33e43A3F276e8e75792b941bccC996EcB2c0bBD)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0xd0dA4F796e183d398aF4797426dC25aA3A32f430)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Vault Bridge ETH Token (katana:0xEE7D8BCFb72bC1880D0Cf19822eB0A2e6577aB62)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0xf44e3BCB7A2461CC08185E127B324f2486a74E20)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (katana:0xF54e837B578deF7b1564Ea2B9ea07CE94DD19407)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (katana:0xF5f3A9687F45217df2E5FfF191fbD1B1aaF57E7E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenWrappedBridgeUpgradeable (katana:0xfd415D011FfaA8e6f17fa753CdB080d1dE266784)
    +++ description: None
```
