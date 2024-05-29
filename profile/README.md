This org hosts a stack of small Python packages related to client access to Ethereum network:

- [`compages`](https://github.com/fjarri-eth/compages) is a simple (de)structurer for typed data. 
- [`ethereum-rpc`](https://github.com/fjarri-eth/ethereum-rpc) contains types used in the Ethereum RPC and the JSON (de)serializer for them (using `compages`).
- [`alysis`](https://github.com/fjarri-eth/alysis) is an Ethereum testerchain currently backed by [`py-evm`](https://pypi.org/project/py-evm/). Its built-in RPC provider uses `ethereum-rpc` types.
- [`pons`](https://github.com/fjarri-eth/pons) is an async Ethereum client, providing also a more high-level access to the `alysis` testerchain and to the Solidity compiler (backed by [`py-solc-x`](https://pypi.org/project/py-solc-x/)). Uses `ethereum-rpc` types. 

In addition:
- [`pure-keccak`](https://github.com/fjarri-eth/pure-keccak) is a pure Python keccak implementation. Pretty slow.
