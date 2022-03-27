#  Decentralized Star Notary Service Project

## Dependencies

For this project, you will need to have:

1. **Truffle:** 5.0.2
2. **OpenZeppelin:** 2.3.0
3. **Node:** 10.24.1
4. **NPM:** 6.14.12
5. **Metamask:** 10.11.3


## Token information

**Token Name:** StarNotary

**Token Symbol:** SNT

**Token Address:** https://ropsten.etherscan.io/address/0x264051f3B3ca3AFe7ea265722103f1fd3C4E3F90

> N.B: The token was deployed to `ropsten` network rather than `rinkeby` due to migration errors on the rinkeby network.


### How to run the application

1. Clean the frontend 

    ```bash
    cd app

    # Remove the node_modules  
    # remove packages
    rm -rf node_modules

    # clean cache
    npm cache clean
    rm package-lock.json

    # initialize npm (you can accept defaults)
    npm init

    # install all modules listed as dependencies in package.json
    npm install
    ```


2. Start Truffle

    ```bash
    # For starting the development console
    truffle develop
    # truffle console

    # For compiling the contract, inside the development console, run:
    compile

    # For migrating the contract to the locally running Ethereum network, inside the development console
    migrate --reset

    # For running unit tests the contract, inside the development console, run:
    test
    ```

3. Frontend - Once you are ready to start your frontend, run the following from the app folder:


    ```bash
    cd app
    npm run dev
    ```

---

