# Hello, folks! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

![](https://img.shields.io/badge/<CODE>-<Javascript>-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=B9BDC1)
![](https://img.shields.io/badge/<CODE>-<React>-informational?style=flat&logo=<LOGO_NAME>&logoColor=black&color=87CEEB)
![](https://img.shields.io/badge/<CODE>-<HTML>-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=B9BDC1)
![](https://img.shields.io/badge/<CODE>-<CSS>-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=87CEEB)

I’m currently working on a web based music player that can play Nft Music on an evm compatible blockchain.

- 🌱 I’m currently learning how to make Smart Contracts on Solidity that govern the behaviour of accounts within the Ethereum state, targeting the Ethereum Virtual Machine 
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: anthonyledesma12@yahoo.com
- ⚡ Fun fact: ...

name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ 67d945fb-dec5-4672-9946-3710bd0cf602 }}
