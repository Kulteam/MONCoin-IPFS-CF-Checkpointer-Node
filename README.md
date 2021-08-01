# MONCoin®: Checkpoints Updater

This project is designed to update blockchain checkpoints, PIN the resulting file hash in [IPFS](https://ipfs.io/) via [Pinata.cloud](https://pinata.cloud/), update a [DNSLink](https://docs.ipfs.io/guides/concepts/dnslink/) via [CloudFlare](https://www.cloudflare.com/) DNS, and leverage the [CloudFlare IPFS Gateway](https://cloudflare-ipfs.com) to serve the data.

## Prerequisites

- node >=8
- yarn
- A [Pinata.cloud](https://pinata.cloud/) account

## Install

```sh
git clone https://github.com/Kulteam/MONCoin-IPFS-CF-Checkpointer-Node.git
cd MONCoin-IPFS-CF-Checkpointer-Node
npm install -g yarn
yarn install
```

## Usage

1) Set your environment variables and start the script

```bash
export CHECKPOINT_FILE=checkpoints.csv
export PINATA_API_KEY=Your_Pinata_Key
export PINATA_SECRET_API_KEY=Your_Pinata_Secret_Key
export CLOUDFLARE_TOKEN=Your_Cloudflare_Token
export CLOUDFLARE_ZONE_ID=Your_Cloudflare_ZoneID
export CLOUDFLARE_SUBDOMAIN=Your_Cloudflare_Subdomain
yarn start
```

## Run tests

```sh
yarn test
```

## Author

👤 **Special Thanks to TurtleCoin Developers**

* Twitter: [@_turtlecoin](https://twitter.com/_turtlecoin)

## 📝 License

This project is [GPL-3.0](https://github.com/Kulteam/MONCoin-IPFS-CF-Checkpointer-Node/blob/master/LICENSE) licensed.
