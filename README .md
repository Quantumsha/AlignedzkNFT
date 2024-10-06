# Aligned-layer-Testnet 3

Use CodeSpace or Gitpod

https://github.com/codespaces

## 1. Install Rust

```
wget https://raw.githubusercontent.com/Hitasyurekk/aligned-layer-phase3/main/rust.sh && chmod +x rust.sh && ./rust.sh
```

## 2. Install Foundry
```
curl -L https://foundry.paradigm.xyz | bash

```

```
source /home/codespace/.bashrc
```
```
foundryup
```

## 3. Update Config 
```
sudo apt update && sudo apt install pkg-config libssl-dev
```

## 4. Add Aligned CLI & Import new wallet private key 
```
npm install -g cast-cli
```
```
source ~/.bashrc
```
```
[ -d ~/.aligned_keystore ] && rm -rf ~/.aligned_keystore && echo "Deleted existing directory ~/.aligned_keystore." ; mkdir -p ~/.aligned_keystore && cast wallet import ~/.aligned_keystore/keystore0 --interactive
```

## 5. Adım Aligned 
```
[ -d aligned_layer ] && rm -rf aligned_layer && echo "Deleted existing aligned_layer directory." ; git clone https://github.com/yetanotherco/aligned_layer.git && cd aligned_layer/examples/zkquiz
```
```
make answer_quiz KEYSTORE_PATH=~/.aligned_keystore/keystore0
```

## 6. Reply the Following answers

y , c , c , a , y



