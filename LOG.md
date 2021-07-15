 truffle migrate --network mainnet --reset

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



Migrations dry-run (simulation)
===============================
> Network name:    'mainnet-fork'
> Network id:      1
> Block gas limit: 14992150 (0xe4c316)


1_initial_migration.js
======================

   Replacing 'Migrations'
   ----------------------
   > block number:        12829428
   > block timestamp:     1626323752
   > account:             0x12a758632dA74281529648fC3a1d7B72AC746649
   > balance:             0.520622889
   > gas used:            176943 (0x2b32f)
   > gas price:           2 gwei
   > value sent:          0 ETH
   > total cost:          0.000353886 ETH

   -------------------------------------
   > Total cost:         0.000353886 ETH


2_deploy_flashloan.js
=====================

   Deploying 'Flashloan'
   ---------------------
   > block number:        12829430
   > block timestamp:     1626323760
   > account:             0x12a758632dA74281529648fC3a1d7B72AC746649
   > balance:             0.516211741
   > gas used:            2178236 (0x213cbc)
   > gas price:           2 gwei
   > value sent:          0 ETH
   > total cost:          0.004356472 ETH

   -------------------------------------
   > Total cost:         0.004356472 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.004710358 ETH





Starting migrations...
======================
> Network name:    'mainnet'
> Network id:      1
> Block gas limit: 15000000 (0xe4e1c0)


1_initial_migration.js
======================

   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0x2de33eb5b2aa040a677d12349024bcd9d2d4854d9572a3f35839c836cf450604
   > Blocks: 4            Seconds: 52
   > contract address:    0xf4a605aeF43FFe28E73a46F8133eCe645ed6A4Dd
   > block number:        12829435
   > block timestamp:     1626323950
   > account:             0x12a758632dA74281529648fC3a1d7B72AC746649
   > balance:             0.515565971
   > gas used:            193243 (0x2f2db)
   > gas price:           28 gwei
   > value sent:          0 ETH
   > total cost:          0.005410804 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:         0.005410804 ETH


2_deploy_flashloan.js
=====================

   Deploying 'Flashloan'
   ---------------------
   > transaction hash:    0x22af18b8a381c3ab62f782e1c0aecc3a922ded4775598e12b74da67b51f6cb0f
   > Blocks: 2            Seconds: 32
   > contract address:    0xEDea3ad1a7C6926497E5a2FA9904F70c47e35232
   > block number:        12829439
   > block timestamp:     1626323989
   > account:             0x12a758632dA74281529648fC3a1d7B72AC746649
   > balance:             0.453318172933268258
   > gas used:            2259736 (0x227b18)
   > gas price:           27 gwei
   > value sent:          0 ETH
   > total cost:          0.061012872 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:         0.061012872 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.066423676 ETH

