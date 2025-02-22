# BitcoinCashKit


```swift
let seed = Mnemonic.seed(mnemonic: [""], passphrase: "")!

let bitcoinCashKit = try BitcoinCashKit.Kit(
        seed: seed,
        walletId: "unique_wallet_id",
        syncMode: .full,
        networkType: .mainNet(coinType: .type145),
        confirmationsThreshold: 3,
        logger: nil
)
```
## Prerequisites

* Xcode 10.0+
* Swift 5+
* iOS 13+

## Installation

### Swift Package Manager

```swift
dependencies: [
    .package(url: "https://github.com/curdicu/BitcoinCashKit.git", .upToNextMajor(from: "1.0.0"))
]
```

