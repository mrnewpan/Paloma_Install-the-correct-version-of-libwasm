## Paloma_Install-the-correct-version-of-libwasm
The current required version of libwasm is 1.4.0. If you're upgrading from a prior version it is recommended to remove the cache to avoid errors. If you're already have palomad running, you will need to stop it before doing these steps.
```
wget https://github.com/CosmWasm/wasmvm/releases/download/v1.4.0/libwasmvm.x86_64.so
sudo mv libwasmvm.x86_64.so /usr/lib/

rm -r ~/.paloma/data/wasm/cache
```
https://github.com/palomachain/paloma#install-the-correct-version-of-libwasm
