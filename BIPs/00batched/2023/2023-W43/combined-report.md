
## Mainnet DAO Multisig
[Tenderly](https://dashboard.tenderly.co/public/safe/safe-apps/simulator/67d1be78-f4b3-4cec-9743-3ff0342e6d91)

[Sign Nonce 225](https://app.safe.global/transactions/queue?safe=eth:0x10A19e7eE7d7F8a52822f6817de8ea18204F2e4f)
```
+--------------------------+--------------------------------------------------------------------+------------------+------+--------------------------------------------+--------+--------+--------------+---------+------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| function                 | pool_id                                                            | symbol           | a    | gauge_address                              | fee    | cap    | style        | bip     |   tx_index | tokens                                                                                                                                                                                                               |
+==========================+====================================================================+==================+======+============================================+========+========+==============+=========+============+======================================================================================================================================================================================================================+
| AAEntrypoint/killGauge() | 0x2086f52651837600180de173b09470f54ef7491000000000000000000000004f | staBAL3          | 1500 | 0x5a6fb12d15021649dda459e8585812142Aa6b968 | 0.005% | 100.0% | L0 sidechain | BIP-447 |          0 | ['staBAL3(0x2086f52651837600180dE173B09470F54EF74910)', 'USDT(0x4ECaBa5870353805a9F068101A40E0f32ed605C6)', 'USDC(0xDDAfbb505ad214D7b80b1f830fcCc89B60fb7A83)', 'WXDAI(0xe91D153E0b41518A2Ce8Dd3D7944Fa863463a97d)'] |
+--------------------------+--------------------------------------------------------------------+------------------+------+--------------------------------------------+--------+--------+--------------+---------+------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| AAEntrypoint/killGauge() | 0x0c1b9ce6bf6c01f587c2ee98b0ef4b20c6648753000000000000000000000050 | EURe/staBAL3     | 20   | 0x399A750516c14C80480AED2Bb597092b9118Caa9 | 0.05%  | 2.0%   | L0 sidechain | BIP-447 |          1 | ['EURe/staBAL3(0x0C1B9CE6Bf6C01f587C2ee98b0ef4B20C6648753)', 'staBAL3(0x2086f52651837600180dE173B09470F54EF74910)', 'EURe(0xcB444e90D8198415266c6a2724b7900fb12FC56E)']                                              |
+--------------------------+--------------------------------------------------------------------+------------------+------+--------------------------------------------+--------+--------+--------------+---------+------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| AAEntrypoint/killGauge() | 0xeb30c85cc528537f5350cf5684ce6a4538e13394000200000000000000000059 | B-50USD-50wstETH | N/A  | 0xf0d3268d36Adf812Fa69756500D72A899D4c2420 | 0.3%   | 100.0% | L0 sidechain | BIP-447 |          2 | ['staBAL3(0x2086f52651837600180dE173B09470F54EF74910)', 'wstETH(0x6C76971f98945AE98dD7d4DFcA8711ebea946eA6)']                                                                                                        |
+--------------------------+--------------------------------------------------------------------+------------------+------+--------------------------------------------+--------+--------+--------------+---------+------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| AAEntrypoint/killGauge() | 0x5c78d05b8ecf97507d1cf70646082c54faa4da95000000000000000000000030 | bb-agEUR-EURe    | 100  | 0x7F75ecd3cFd8cE8bf45f9639A226121ca8bBe4ff | 0.01%  | 100.0% | L0 sidechain | BIP-447 |          3 | ['agEUR(0x4b1E2c2762667331Bc91648052F646d1b0d35984)', 'bb-agEUR-EURe(0x5C78d05b8ECF97507d1cf70646082c54FaA4dA95)', 'EURe(0xcB444e90D8198415266c6a2724b7900fb12FC56E)']                                               |
+--------------------------+--------------------------------------------------------------------+------------------+------+--------------------------------------------+--------+--------+--------------+---------+------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
```
```
+------------+-------------------------------------------------+----------------------------------------------------------------------+--------------------------+---------+------------+
| function   | token_symbol                                    | recipient                                                            | amount                   | bip     |   tx_index |
+============+=================================================+======================================================================+==========================+=========+============+
| transfer   | USDC:0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 | payees/karpatkey_payments:0x58e6c7ab55Aa9012eAccA16d1ED4c15795669E1C | 5032.0 (RAW: 5032000000) | BIP-103 |          4 |
+------------+-------------------------------------------------+----------------------------------------------------------------------+--------------------------+---------+------------+
```
```
+-----------------------+---------------+--------------------------------------------+-----------------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+------------+
| function              | caller_name   | caller_address                             | fx_paths                                                                                      | action_ids                                                         | bip     |   tx_index |
+=======================+===============+============================================+===============================================================================================+====================================================================+=========+============+
| Authorizer/grantRole  | multisigs/dao | 0x10A19e7eE7d7F8a52822f6817de8ea18204F2e4f | 20230215-single-recipient-gauge-factory-v2/SingleRecipientGauge/setRelativeWeightCap(uint256) | 0xae60dce27f51ce5815357b9f6b40f200557867f8222262a1646c005d09b7dfba | BIP-458 |          5 |
|                       |               |                                            | 20230529-avalanche-root-gauge-factory/AvalancheRootGauge/setRelativeWeightCap(uint256)        |                                                                    |         |            |
|                       |               |                                            | 20230217-gnosis-root-gauge-factory/GnosisRootGauge/setRelativeWeightCap(uint256)              |                                                                    |         |            |
|                       |               |                                            | 20220823-optimism-root-gauge-factory-v2/OptimismRootGauge/setRelativeWeightCap(uint256)       |                                                                    |         |            |
|                       |               |                                            | 20220823-arbitrum-root-gauge-factory-v2/ArbitrumRootGauge/setRelativeWeightCap(uint256)       |                                                                    |         |            |
|                       |               |                                            | 20230911-base-root-gauge-factory/BaseRootGauge/setRelativeWeightCap(uint256)                  |                                                                    |         |            |
|                       |               |                                            | 20230811-avalanche-root-gauge-factory-v2/AvalancheRootGauge/setRelativeWeightCap(uint256)     |                                                                    |         |            |
|                       |               |                                            | 20220822-mainnet-gauge-factory-v2/LiquidityGaugeV5/setRelativeWeightCap(uint256)              |                                                                    |         |            |
|                       |               |                                            | 20220823-polygon-root-gauge-factory-v2/PolygonRootGauge/setRelativeWeightCap(uint256)         |                                                                    |         |            |
|                       |               |                                            | 20230526-zkevm-root-gauge-factory/PolygonZkEVMRootGauge/setRelativeWeightCap(uint256)         |                                                                    |         |            |
+-----------------------+---------------+--------------------------------------------+-----------------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+------------+
| Authorizer/revokeRole | multisigs/dao | 0x10A19e7eE7d7F8a52822f6817de8ea18204F2e4f | 20230215-single-recipient-gauge-factory-v2/SingleRecipientGauge/setRelativeWeightCap(uint256) | 0xae60dce27f51ce5815357b9f6b40f200557867f8222262a1646c005d09b7dfba | BIP-458 |          7 |
|                       |               |                                            | 20230529-avalanche-root-gauge-factory/AvalancheRootGauge/setRelativeWeightCap(uint256)        |                                                                    |         |            |
|                       |               |                                            | 20230217-gnosis-root-gauge-factory/GnosisRootGauge/setRelativeWeightCap(uint256)              |                                                                    |         |            |
|                       |               |                                            | 20220823-optimism-root-gauge-factory-v2/OptimismRootGauge/setRelativeWeightCap(uint256)       |                                                                    |         |            |
|                       |               |                                            | 20220823-arbitrum-root-gauge-factory-v2/ArbitrumRootGauge/setRelativeWeightCap(uint256)       |                                                                    |         |            |
|                       |               |                                            | 20230911-base-root-gauge-factory/BaseRootGauge/setRelativeWeightCap(uint256)                  |                                                                    |         |            |
|                       |               |                                            | 20230811-avalanche-root-gauge-factory-v2/AvalancheRootGauge/setRelativeWeightCap(uint256)     |                                                                    |         |            |
|                       |               |                                            | 20220822-mainnet-gauge-factory-v2/LiquidityGaugeV5/setRelativeWeightCap(uint256)              |                                                                    |         |            |
|                       |               |                                            | 20220823-polygon-root-gauge-factory-v2/PolygonRootGauge/setRelativeWeightCap(uint256)         |                                                                    |         |            |
|                       |               |                                            | 20230526-zkevm-root-gauge-factory/PolygonZkEVMRootGauge/setRelativeWeightCap(uint256)         |                                                                    |         |            |
+-----------------------+---------------+--------------------------------------------+-----------------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+------------+
```
```
+---------------+-----------------------------------------------------------------------------------------------------------------+---------+----------------------------------------------------------------------------------------+--------------+------------+
| fx_name       | to                                                                                                              |   value | inputs                                                                                 | bip_number   | tx_index   |
+===============+=================================================================================================================+=========+========================================================================================+==============+============+
| performAction | 0xf5dECDB1f3d1ee384908Fbe16D2F0348AE43a9eA (20221124-authorizer-adaptor-entrypoint/AuthorizerAdaptorEntrypoint) |       0 | {                                                                                      | BIP-458      | N/A        |
|               |                                                                                                                 |         |   "target": [                                                                          |              |            |
|               |                                                                                                                 |         |     "0xed0bb13496ce24EFFF8f9734A9707D092d4Be10c (N/A) "                                |              |            |
|               |                                                                                                                 |         |   ],                                                                                   |              |            |
|               |                                                                                                                 |         |   "data": "0x10d3eb0400000000000000000000000000000000000000000000000000b1a2bc2ec50000" |              |            |
|               |                                                                                                                 |         | }                                                                                      |              |            |
+---------------+-----------------------------------------------------------------------------------------------------------------+---------+----------------------------------------------------------------------------------------+--------------+------------+
```