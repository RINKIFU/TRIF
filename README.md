## Pasang Paket Dasar
```sh
pkg update -y
pkg upgrade -y
pkg install git -y
pkg install git clang curl libffi libsodium openssl
pkg uninstall python -y
cd $HOME
git clone https://github.com/RINKIFU/TRIF

## Install Python Versi 3.10
```sh
Anda Harus Menggunakan Versi Python 3.10 Dikarenakan Versi Python 3.11 / Lebih Besar Tidak Support Pada Cython
pkg install tur-repo
pkg install python3.10
ln -s $PREFIX/bin/python3.10 $PREFIX/bin/python

