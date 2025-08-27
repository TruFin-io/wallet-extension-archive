# Wallet Archive

We currently support three wallets(Petra, Meteor, and Solflare) without version control because their repositories are private. What this means for us is that we have no control over the version of wallet we download when running the end-to-end tests in CI. This will lead to high levels of uncertainty. Creating a private archive fixes this problem.

##  Supported wallets to archive

- Petra
- Meteor
- Solflare

> Please make sure to update the "WalletExtensionWithVersion" in the [Plawright Web3](https://github.com/TruFin-io/playwright-web3) repository to the corresponding version when publishing a new release
