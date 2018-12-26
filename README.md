# BlockChainApp

This project is a step by step application development using ethereum Blockchain. It will consist of two basic element: A `Smart contract` and a `Web insterface`. Our smart contract will allow customization access to the blockchain where we can store our data.
The goal is to develop a simple Dapp that will allow us to deposit Ether and send it from one address to another and check the balance that's being stored, see who the approver is and enable the approver to approve the transaction. Each part of the developmet will require some knowledge of javascript for the client side, Solidiy and more on the Ethereum side.


What we really need to be install is the `Truffle` test server and Ganache(optional).
To begin we will install npm and nodeJs on your Linux distribution. For this project I chose to use ubuntu 16.04. After the installation done. We'll install truffle which we will be used to compile and migrate our smart contrat on our test network.
Ganache on the other hand will allow us to interact and see transaction performed on our network.

# nodejs npm installation
```
$ sudo apt-get update
$ curl -sL https://deb.nodesource.com/setup_8.x | sudo bash -
$ sudo apt-get install -y nodejs
```

# truffle installation
```
$ sudo npm cache clean -f (optional only if you get error while proceeding with the installation)
$ sudo npm install -g truffle
```

# Ganache installation
To download Ganache, visit http://truffleframework.com/ganache/ and click on Download.
Under Linux, you will download an AppImage package. To run it, navigate to your Download folder and change its modus and finally execute it.

```
$ cd ~/Downloads
$ chmod a+x ganache-1.1.0-x86_64.AppImage
$ ./ganache-1.1.0-x86_64.AppImage
```

It will prompt a window and ask you whether you want to integrate Ganache with your system. Click Yes and the programm is ready to use.


