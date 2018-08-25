## Proof Of Existence

### What Good It Does?

This project lets users to upload files to create proofs of existences. Upload time is stored in the smart contract and records are immutable.

Along with the file, user can optionally provide some tags describing the content.

Users can see their records and search for other records by providing the ID of the record.

### Tech Stack

Files are stored on **IPFS**. Identity management is handled using **uPort**. And user interface built with **React**. Contract deployed to the **Rinkeby** network at: [**`0x8624f7187ad1e4fe36a403af63165c08c27114a2`**](https://etherscan.io/address/0x8624f7187ad1e4fe36a403af63165c08c27114a2)

-----


Install dependencies: 
```yarn install```

Compile contracts:
```truffle compile```

Run tests:
```truffle test```

Run the app:
```yarn start```

To be able to login, you need to install uPort.

