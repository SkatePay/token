
# $RABOTA-token
$RABOTA is the utility token of the ProRobot ecosystem, used for transaction validation and token holder governance.

![PROROBOT](rabotaToken.png)

## [Create Solana Token](https://solana.com/developers/guides/getstarted/how-to-create-a-token)
    mkdir rabota-token
    cd rabota-token
    solana config get
    solana config set -ut

    # treasurer
    solana-keygen grind --starts-with key:1
    solana config set --keypair key[PRESS_TAB]

    # mint
    solana-keygen grind --starts-with rab:1

    solana airdrop 2

    spl-token create-token --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb --enable-metadata rab[PRESS_TAB]

    spl-token initialize-metadata rabpv2nxTLxdVv2SqzoevxXmSD2zaAmZGE79htseeeq 'RABOTA Token' 'RABOTA' https://bafybeihetbvgte3kpwl5urwki6y3pgcro6ekc3whvtb7rzgh7d7ovmczgq.ipfs.w3s.link/metadata.json

    spl-token create-account rabpv2nxTLxdVv2SqzoevxXmSD2zaAmZGE79htseeeq

    spl-token mint rabpv2nxTLxdVv2SqzoevxXmSD2zaAmZGE79htseeeq 100

    spl-token transfer rabpv2nxTLxdVv2SqzoevxXmSD2zaAmZGE79htseeeq 10 (recipient wallet address) --fund-recipient


## Mint Addresses
[.testnet](https://solana.fm/address/rabpv2nxTLxdVv2SqzoevxXmSD2zaAmZGE79htseeeq/tokens?cluster=testnet-solana)
