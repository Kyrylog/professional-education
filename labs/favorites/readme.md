Some additions to Favorities lab to fix errors

1. yarn install
   
2. After 'anchor build' in step 9
  go to /favorites/target/idl/favorites.json and copy Program Id in field "address": then paste it to lib.rs in declare_id!("address")

3. solana-test-validator
   
4. anchor deploy

5. run anchor test --skip-local-validator --skip-deploy  
