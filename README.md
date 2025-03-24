{
  "name": "Magic Mushroom #57",
  "description": "Hand drawing brings the NFT an artistic value, while various accessories and materials bring uniqueness and significance in our rapidly changing world.",
  "image": "https://s.getgems.io/nft/c/62695cb92d780b7496caea3a/nft/56/629b9349e034e8e582cf6448.png",
  "attributes": [
    {
      "trait_type": "Material",
      "value": "Wool fabric"
    },
    {
      "trait_type": "Hat",
      "value": "Top hat"
    },
    {
      "trait_type": "Glasses",
      "value": "None"
    },
    {
      "trait_type": "Item",
      "value": "None"
    },
    {
      "trait_type": "Background",
      "value": "Dark"
    }
  ]
}

# About

This repository contains Rust bindings for tonlibjson and services built on top of it.

## ton-grpc

```bash
docker pull ghcr.io/getgems-io/ton-grpc
docker run --rm -p 50052:50052 ghcr.io/getgems-io/ton-grpc
```

## ton-liteserver-client
### Installation
```toml
[dependencies]
ton-liteserver-client = { git = "https://github.com/getgems-io/ton-grpc.git" }
tokio = "1.37"
tower = "0.4"
```

### Usage
See `ton-liteserver-client/examples`