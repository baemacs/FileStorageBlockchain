To use the system:
setup:
1. download node.js https://nodejs.org/en/ and ipfs
	- in the directory of the dstorage folder input in cmd these commands:
		"npm install"
		"npm install web3"
		"npm install truffle"
		"npm install ethers"
		"npm install react"
	- for ipfs:https://ipfs.io/ipfs/QmYxvrFbqasNV8jgT7TCzSnoG2Aa19tn7fFx1p59RTJ3ot/docs/install/
	  and put the downloaded folder to this folder

2. Download ganache blockchain https://trufflesuite.com/ganache/
	-run ganache, press quickstart and run ganache in the background

3. Add metamask to the browser extension

	-create an account on metamask
	-add a network named "Ganache" and add the RPC url seen at the ganache window
	-default chain id is 1337
	-add the private key to your account in metamask. The private key can be seen in the ganache window on a button shaped key on the right of each block. You should be ables to view how many eth u have.

Run:
	on the cmd run:
		"truffle migrate --reset"
		"npm start run"

