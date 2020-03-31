# TravlrBackend

#### Steps to deploy contracts
1. Deploy `Travlr` using acc[0]
2. Call assignGovernment(acc[1], ctry) in `Travlr`, get Govt Address in output
3. Deploy `Government` using Govt Address output from step 2
4. Call createEthPassport(acc[2]) in `Government`, get Eth Passport Address in output
5. Deploy `EthPassport` using Eth Passport Address output from step 4
6. Call assignHotel(acc[3]) in `Government`, get Hotel Address in output
7. Deploy `Hotel` using Hotel Address output from step 6
8. Call assignImmigration(acc[4]) in `Government`, get Immigration Address in output
9. Call other functions :)
