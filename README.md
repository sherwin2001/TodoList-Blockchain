# TodoList-Blockchain
This Todo List is a **Smart Contract** backed by **BlockChain Technology**. It makes use of **Solidity** for developing this Smart Contract.
For Front-End Client Side Server **HTML** is used and for connection between the Client Side Server and the Smart Contract, **web3.js** is used which is a special type of JavaScript Library.
Also using **metamask.io** and **Ganache** to create an Artificial Simulated BlockChain environment.

While **metamask.io** connects our browser to the blockchain, **web3.js** connects our client side application to the blockchain.
Ganache is an artificial ethereum wallet simulator used for setting up a personal Ethereum Blockchain for testing Smart contracts. 

***
### Working:
* For using this Todo List, the user simply needs to have a valid **ethereum** wallet in metamask which can be obtained using Ganache.
* The user creates **create a New Task** according to the needs.
* The user then strikes off the Task using CheckBox if the Task is completed Successfully.
* If the task is not Completed Successfully, the user can unstrike the Task by Unticking the CheckBox.

Everytime the user Checks / Unchecks or Creates a New Task, the Metamask Window prompts asking **Gas Fees** for executing the transaction which the User has to pay. Failing to pay will lead to
cancellation of execution.
