# dbank-app

Truffle Commands:-

* truffle migrate
* truffle console

* const token = await Token.deployed()
* token.name()
* token.symbol()
* token.totalSupply()

* const acs=await web3.eth.getAccounts()
* const ac=acs[0]
* const bal=await web3.eth.getBalance(ac)

* token.mint(ac,web3.utils.toWei('100'))
* tokenbal=await token.balanceOf(ac)
*web3.utils.fromWei(tokenbal)
