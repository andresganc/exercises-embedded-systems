
# INSTALL RUST

## INSTALL - LINUX UBUNTU 22.10

- 

    $ sudo apt update && sudo apt upgrade

    $ sudo apt install curl build-essential gcc make -y


    $ curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh

    or

    $ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh


    $ source ~/.profile
    $ source ~/.cargo/env

    $ rustc -V
