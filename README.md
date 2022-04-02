# jdll2022
Content for JdLL 2022 workshop

### Chain specifications
1. Network name: `jdll`.
2. Chain id: `202204` (2022-04), which is `315dc` in hex.
3. Block reward: `1 ETH`.
4. Block time: `5` seconds.


### Setup environment:
1. Install Openethereum: https://github.com/openethereum/openethereum/releases/tag/v3.3.0.

2. Edit chain specifications file `spec.json`.

3. Edit node configuration file `node.toml`.

3. Run
    ```
    ./openethereum --config=node.toml
    ```