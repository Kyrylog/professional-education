Some additions to Favorities lab to fix errors

1. run 'yarn install'
   
2. After 'anchor build' in step 9
  go to /favorites/target/idl/favorites.json and copy Program Id in field "address": then paste it to lib.rs in declare_id!("address")

3. run 'anchor deploy'

4. Add to Anchor.toml section
[test.validator]
bind_address = "0.0.0.0"
url = "https://api.mainnet-beta.solana.com"
ledger = ".anchor/test-ledger"
rpc_port = 8899

5. run anchor test --skip-local-validator --skip-deploy  
