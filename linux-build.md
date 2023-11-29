Building (Linux)

# Build Dependencies
curl https://sh.rustup.rs -sSf | sh
sudo apt-get install perl
sudo apt-get install yasm
sudo apt-get install git

# Build
git clone https://github.com/apmcoin/apm-reward-chain
cd apm-reward-chain/openethereum-core/

cargo build --release --features final