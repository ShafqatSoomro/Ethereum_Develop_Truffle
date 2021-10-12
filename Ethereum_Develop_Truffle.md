
#	__"Ethereum Development Environment using Truffle".__


### Installing Git from command line (Ubuntu Terminal)
	sudo apt-get install git

### Installing Nodejs and NPM
	sudo apt install nodejs npm
	sudo ln -s /usr/bin/nodejs   /usr/bin/node

### Installing Solidity Compiler
	sudo npm install -g solc

### Installing Ethereum Client
	sudo apt-get install software-properties-common
	sudo add-apt-repository -y ppa:ethereum/ethereum

### Updating the Ubuntu
	sudo apt-get update

### Installing Ethereum
	sudo apt-get install ethereum

### Installing Truffle for gloabally
	sudo npm install -g truffle

### Making Directory/Folder for Truffle Deployment
	mkdir truffle-project

### Changing the directory
	cd truffle-project

### Initializing the truffle
	truffle init

### After initializing create truffle development and then migrate
	> truffle develop

	> migrate

### Exit from the console
	> .exit
