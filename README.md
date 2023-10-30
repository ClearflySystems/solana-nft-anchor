## Calyptus Solana Mint NFT exercise.

Note the data_v2 in `create_metadata_accounts_v3` uses a different struct with the same name.

Change:

```use mpl_token_metadata::state::DataV2 ```

to 

```use anchor_spl::metadata::mpl_token_metadata::types::DataV2```

---

### Minted transaction:

https://explorer.solana.com/tx/2dpmUQvXZ7cZJVwii6Fb5zeL4B2wBs6LWyDgVDLpAZfJUezUsmcbTtreh9n9EEWUwfuiEWsyC1jrWGLfWibs752r?cluster=devnet

Minted NFT:

https://explorer.solana.com/address/4D47GDz1yWkuZVRdvvLnukMTtEcQbBKAzoyS9pK7asmC?cluster=devnet