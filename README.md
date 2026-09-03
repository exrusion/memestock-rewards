# Memestock Rewards

Automatic Solana fee-to-holder rewards bot. No holder wallet connection or claim flow.

## Run
`npm install && npm start`

## Production setup

Set `ADMIN_TOKEN`, `SOLANA_RPC_URL`, `FEE_WALLET`, `TREASURY_KEYPAIR_JSON`, and `AUTO_DISTRIBUTE=true` in Railway. Configure the token mint through the protected admin API. Keep the signing key only in Railway and use a dedicated fee wallet.
