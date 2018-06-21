## Docker for run EOS jungle testnet

Jungle is a public test net for EOS blockchain (http://jungle.cryptolions.io/)

### Setup

1. Open `config.ini`, change following:
  * `SERVER_ADDRESS` to your ip
  * `signature-provider = PUBKEY=KEY:PRIVKEY` use your keys
  * `PRODUCER_NAME` use your name.

2. Check p2p list in http://jungle.cryptolions.io/#p2p, replace at the end of `config.ini`

3. `docker-compose up -d`
