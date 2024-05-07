Instalar Nodo*****************

mkdir xelis && cd xelis

wget [https://github.com/argenminers/xelis-blockchain/releases/download/V1.9.5/x86_64-unknown-linux-gnu.tar](https://github.com/argenminers/xelis-blockchain/releases/download/v1.10.0-Mainnet/x86_64-unknown-linux-gnu.tar)

tar -xf x86_64-unknown-linux-gnu.tar && rm x86_64-unknown-linux-gnu.tar

Iniciar Nodo******************
cd x86_64-unknown-linux-gnu
screen -S node-xelis ./xelis_daemon



Wallet***************

https://github.com/xelis-project/xelis-genesix-wallet/releases/download/0.0.2/genesix_windows.zip


Hoja de Vuelo ***************
custom miner: Install Url:
https://private.viporlab.net/files/xelis-taxminer-0.8.1.tar.gz

pool:
ws://192.168.0.144:8080

User Config: --host 192.168.0.44:8080 --wallet xel: --worker Xelis-Rig1
