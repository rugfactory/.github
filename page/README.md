# RUGFACTORY PAGE

enabling the next generation of ruggers


rugfactory
<br/>
🐱 https://github.com/rugfactory
<br/>
𝕏 https://x.com/rugfactoryfun
<br/>
✈️ https://t.me/huggiesdotnear
<br/>
〇 https://rugfactory.near.social


copyright: 2025 by sleet.near, in partnership with huggies.near




---


web4 dist info


```sh
# web 4 contract
near deploy --wasmFile page/web4-min.wasm rugfactory.testnet

near deploy --wasmFile page/web4-min.wasm rugfactory.near

# html page
npx web4-deploy@0.7.2 page/web4 rugfactory.testnet --nearfs
npx web4-deploy@0.7.2 page/web4 rugfactory.near --nearfs

```

web3storage

Manage spaces:
```sh
# Create a new space
w3 space create rugfactory

# List all spaces
w3 space ls

# Switch to a different space
w3 space use rugfactory

# Delete a space
w3 space delete <name>
```

Upload files and directories:
```sh
w3 up page/web4
```

```sh

# For testnet
near call rugfactory.testnet web4_setStaticUrl '{"url": "ipfs://CID_HERE"}' --accountId rugfactory.testnet

# For mainnet
near call rugfactory.near web4_setStaticUrl '{"url": "ipfs://CID_HERE"}' --accountId rugfactory.near



---


copyright: 2025 by sleet.near, in partnership with huggies.near
