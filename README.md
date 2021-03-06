# SimpleLibrary
A P2P Book Sharing/Virtual Library DApp that allows users to lend books to each other.
![UI Preview](https://i.imgur.com/IGn02f7.png)
The UI is a modified version of the [Pet Shop example](https://www.trufflesuite.com/tutorials/pet-shop).

## Run A Local Development Server
1. Clone the repo. Install `truffle` and `ganache-cli`.
2. In the root of the directory, compile using `truffle compile`.
3. Run `ganache-cli` from another terminal window. The project uses port 8545 for all intents and purposes.
3. Migrate the contracts `truffle migrate`.
4. Run `npm run dev` to start the `lite-server`.
5. Connect with MetaMask or provider of your preference to perform transactions, and import the keys generated by ganache-cli after setting RPC server to `127.0.0.1:8545`.
6. The DApp would be accessible at `://localhost:3000`.


### Core Files
- Contract: `SimpleLibrary.sol` in `Contracts` folder.
- Tests: `simple_library.test.js` in `Tests` folder.
- Migrations are located in `Migrations`.
- UI files are present in the `src` folder.

### Rinkeby Deployment
- Contract: [0x7cd3cb57c0bca9316969493e9de0106c453cf0a9](https://rinkeby.etherscan.io/address/0x7cd3cb57c0bca9316969493e9de0106c453cf0a9#code)

### Additional Requirements
- avoiding_common_attacks.md
- design_pattern_decisions.md
- deployed_addresses.txt

### Walk-through Video
- [Youtube](https://www.youtube.com/watch?v=ok6_7_ll0BY)

### Security Assessment
- The contract was tested with MythX and no high level vulnerabilities were found.
