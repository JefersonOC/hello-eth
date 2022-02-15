# hello-eth
Deploy a Smart Contract on Ethereum with Python, Truffle and web3py

# setup
```
sudo npm install -g truffle
pip3 install web3

truffle init
truffle compile
truffle develop

> migrate

Starting migrations...
======================
> Network name:    'develop'
> Network id:      5777
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x96de9ba9a2f4da7706ade88163c59fb9175982033fba29ab62a918a2bb75eea1
   > Blocks: 0            Seconds: 0
   > contract address:    0x8dCED6208954EAe3613b9aB81013c4a3137ec40f
   > block number:        1
   > block timestamp:     1644946433
   > account:             0x1197379f4131c0d0A4C95539b64260797b5C9994
   > balance:             99.99915577075
   > gas used:            250142 (0x3d11e)
   > gas price:           3.375 gwei
   > value sent:          0 ETH
   > total cost:          0.00084422925 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:       0.00084422925 ETH


2_deploy_contract.js
====================

   Deploying 'HelloWorld'
   ----------------------
   > transaction hash:    0x1d5633bb2d31dffeb4020c45e3af890dfe2f3da68b9ebdd1909edad8c9734752
   > Blocks: 0            Seconds: 0
   > contract address:    0x3D33f4a63343285376a2A78F25328bdeb6a9667A
   > block number:        3
   > block timestamp:     1644946434
   > account:             0x1197379f4131c0d0A4C95539b64260797b5C9994
   > balance:             99.998576170024866659
   > gas used:            135067 (0x20f9b)
   > gas price:           3.178365856 gwei
   > value sent:          0 ETH
   > total cost:          0.000429292341072352 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:     0.000429292341072352 ETH

Summary
=======
> Total deployments:   2
> Final cost:          0.001273521591072352 ETH
```
