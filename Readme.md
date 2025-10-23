#  Simple NFT Marketplace on Sui: Operation Log

This document tracks the core object IDs and confirms successful operations performed on the **Simple NFT Marketplace** package deployed on the Sui network.

## Files here

* `simple_nft_marketplace`: The custom Move package built and deployed using the Sui CLI.
* `sui`: Sui CLI.

***

##  Core Deployment Identifiers

These IDs are crucial for interacting with the marketplace smart contract and its shared state.

| Component | Description | Identifier (ID) |
| :--- | :--- | :--- |
| **Package ID** | The address of the deployed smart contract code. | `0xdd0420d1074522b8121f656058dcaf31ed7464551400ff83b87e11fa6a882dca` |
| **Marketplace ID** | The shared object ID for the marketplace instance itself. | `0x82be626e2e767172a8086bf0911c7172f0ff33bcf5eb960d517873e1f323f20a` |

***

##  Confirmed Transaction History

The following digests confirm successful execution of various marketplace functions.

###  NFT Creation 

| Transaction Type | Transaction Digest (Hash) |
| :--- | :--- |
| Initial Mint | `ChyKf5zyJSwbbd5YAdFKQiGmhfJBp9N4LoaTVFj9iX6J` |
| Mint | `5eecczaC2kJBGGxJL9GQE3WcpRfzBJDq7tC5mrPcyud8` |
| Mint | `9F2nwQqskpfn1y3UPB27kmc4sFTx7dMjuotGJKPeS7pq` |
| **Latest Mint** (Burner NFT) | `D8whTy8j4zTqHV6jFYD9mPJhe4zWxQT6dmYMqJLNDURF` |

###  Marketplace Interactions

| Transaction Type | Transaction Digest (Hash) |
| :--- | :--- |
| **List NFT** | `GURd4vdK99hXQjuxRPZ9jNtdkTpsfeuUAdxV5DzDbm3q` |
| **List NFT** | `FXuRKwzVRsxf1o9VKrWZ7M2bM5AFKXBFsddPEqSpahuE` |
| **List NFT** | `54TkvKuTcRMrngRDzzY7ZTGuRegrn9h91xYEt3WfoJXu` |
| **Buy NFT** | `7hzmsGW3iD4wrk4PdtuvJtKUzUuaWkzfVpUguVCVtAVU` |
| **Cancel Listing** | `7Hoha2KpX6uUhjUTMgedVqe8vNaEksMhNbznpvCDMoRB` |

### 🛠️ NFT Maintenance

| Transaction Type | Transaction Digest (Hash) |
| :--- | :--- |
| **Edit Description**  | `BHhjKQnJTdH9YdgzyM4obqw1dYnwhqhRbbAGAALY6TPq` |
| **Transfer NFT** | `DjVWdkA35RNHWAuYXyXdtnrrNCNWP9zEYDELcPFL4qQV` |
| **Burn NFT** | `EAPypsgNgbaWvgQVMkp8d7fUQ2MymPRhZw8Jtzkv8fGD` |

***
