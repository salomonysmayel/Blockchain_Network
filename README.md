# Blockchain_homework

## Testnet Blockchain at ZBank

This project consist on the creation of a blockchain network, with which at the end a transaction between two accounts managed with MyCryto application is made. The following are the steps taken to achieve this process.

### Network Creation

The following image shows the creation of the network

The network created was named "zbanknet", then the genesis was configured from scratch, with proof of work, The two addresses 
used are:

account1_homework: 0x01BFD4508CC26797Af84Ce05287a3DeC0671DEb8 

account2_homework: 0x17F3593006632E03c41a930f99614dDb3e3263d7

The chain ID 988

The following image shows the set up of the network

![supply_chain](/Images/network_create.png)

### Nodes initialization and activation into mining 

![supply_chain](/Images/nodes_creation.png)

### Launching node 1 into mining mode

The enode code is used to launch the second node into mining mode

![supply_chain](/Images/node1act.png)

### Launching node 2 into mining mode

![supply_chain](/Images/node2_act.png)

### Setting transfer between the two accounts:

To send a transfer we launch MyCryto app and select the network created "zbanknet" and use "Private Key" option to log in to the account from which you want to send funds.

![supply_chain](/Images/mycryto_login.png)

Once loged in into your account, indicate the account to wich you want to send funds, select the amount to be send and the fee to be charged.

![supply_chain](/Images/set_transf.png)

### Confirming transfer between the two accounts:

![supply_chain](/Images/conf_transf.png)

### Confirmation of successful transaction between the two accounts:

![supply_chain](/Images/trans.png)

To use the zbanknet we can activate nodes and go to My Crypto to keep transferring between accounts 


