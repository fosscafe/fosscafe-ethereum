# fosscafe-ethereum
fosscafe ethereum setup, config and operations

install
npm install ethereumjs-testrpc -g
npm install truffle -g

start the in-memory blockchain
testrcp --verbose

run these commands

truffle compile
truffle migrate --reset

run the contract
truffle console

var hw = HelloWorld.deployed()
hw.then(a => console.log(a.balance().then(console.log)))

