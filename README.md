# Nubit Light Node
A Nubit Light Node is a resource-efficient way to participate in the Nubit blockchain network





![image](https://github.com/user-attachments/assets/b888a11d-f812-451f-b092-6b61ab2a1f1e)


# Nubit is a data availability layer designed to enhance the scalability and efficiency of the Bitcoin ecosystem .It leverages Bitcoin's economic security to create a highly secure and scalable solution for data storage and retrieval.Nubit is a scalable, cost-effective data availability layer secured by Bitcoin. The project is in its early stages but has already raised $12 million from reputable funds.

![image](https://github.com/user-attachments/assets/afecf3bd-f3af-463b-ab1e-d97c344b7e85)


# we can engage with the project in several ways:
*Being active on the project’s Discord


*Participating in the testnet


*Installing a node

# In this guide, we will focus on the last option and detail how to install a node for this project. According to the official documentation,
https://docs.nubit.org/nubit-da/introduction, we can install one of three types of nodes: Validator, Light Node, Full Node. Each type has its own server requirements.

# Installing the Nubit Node
We will be installing the simplest option, the Light Node, which will help us record our activity within the project and potentially qualify for a drop in the future.

# To install the node, we need a virtual server with:
![image](https://github.com/user-attachments/assets/c825d7ef-98a7-422c-ab7f-d6d0dda05866)


Once the server is ready, we can proceed with the node installation. To do this, open the application you will use to access the server (I use Termius) and start entering the following commands:

## Installation

# Update

```bash
 sudo apt-get update && sudo apt-get upgrade -y
```
![image](https://github.com/user-attachments/assets/172b70da-ff9d-4a4d-b2e2-14e60de65f78)


# Install Screen 
```bash
 apt-get install screen -y 
```
# Screen 
```bash
screen -S nubit
```
# Deploy Your Node
```bash
curl -sL1 https://nubit.sh | bash
```
![image](https://github.com/user-attachments/assets/984d0ec9-3fb4-4a54-80f3-efd17343a022)


![image](https://github.com/user-attachments/assets/89d6f78a-b8a1-4eeb-bbad-9dc7f50f4ef4)


# Key Export : 
```bash
cat $HOME/nubit-node/mnemonic.txt  
```
# PUBKEY :
 Each time you start light node, PUBKEY will be print out : 
```bash
curl -sL1 https://nubit.sh | bash

```
![image](https://github.com/user-attachments/assets/3bbb4127-7b67-446c-be1a-1a0495149fcf)


# Wallet Import
```bash
/root/nubit-node/bin/nkey add my_nubit_key --recover --p2p.network nubit-alphatestnet-1 --node.type light  
```
# If you want to check the node’s operation, you will need to enter the following command on the server:
```bash
 screen -r nubit 
```
That’s it! The node installation is successfully completed!

In addition, today within the project, you can also complete tasks within the testnet, which is highly likely to be rewarded.
# x 
https://x.com/Nubit_org
# wab
https://www.nubit.org/
