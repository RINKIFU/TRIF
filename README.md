## Pasang Paket Dasar
```sh
pkg update -y
pkg upgrade -y
pkg install git -y
pkg install git clang curl libffi libsodium openssl
pkg uninstall python -y
cd $HOME
git clone https://github.com/RINKIFU/TRIF
