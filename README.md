Stanford University, CS251 Project 4: Building a DEX
Authors: Simon Tao (BS'22, MS'23), Mathew Hogan (BS'22), under the guidance of Professor Dan Boneh.

Start local node 

```
npx hardhat code 
```

Deploy the token contract. Save token_abi and token_address

```
npx hardhat run --network localhost scripts/deploy_token.js
```

Deploy the exchange contract. Save exchange_abi and exchange_address

```
npx hardhat run --network localhost scripts/deploy_exchange.js
```
Update token_abi and token_address, exchange_abi and exchange_address in exchange.js. 
Update tokenAddr in exchange.sol
Can find abi in artifacts/contracts/ folder

Run app web_app/index.html
