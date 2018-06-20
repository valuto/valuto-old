Valuto (VLU) - The blockchain powered marketplace
===========
```

$$\    $$\  $$$$$$\  $$\      $$\   $$\ $$$$$$$$\  $$$$$$\
$$ |   $$ |$$  __$$\ $$ |     $$ |  $$ |\__$$  __|$$  __$$\ 
$$ |   $$ |$$ /  $$ |$$ |     $$ |  $$ |   $$ |   $$ /  $$ |
\$$\  $$  |$$$$$$$$ |$$ |     $$ |  $$ |   $$ |   $$ |  $$ |
 \$$\$$  / $$  __$$ |$$ |     $$ |  $$ |   $$ |   $$ |  $$ |
  \$$$  /  $$ |  $$ |$$ |     $$ |  $$ |   $$ |   $$ |  $$ |
   \$  /   $$ |  $$ |$$$$$$$$\\$$$$$$  |   $$ |    $$$$$$  |
    \_/    \__|  \__|\________|\______/    \__|    \______/ 
                                                            
```                                                 
#### Features ####

* Coinsupply: 133.000.007 VLU
* Block time: 30 Seconds
* Block reward: 
  
  First 5000 blocks: 500 VLU 
  5000-10000 blocks: 250 VLU
  10000-: 50 VLU / 2 every 840000 block ~ 291 days

* Premine: 500.000 VLU (Financing hosting, dev bounties, etc.)
* Homepage: www.valuto.io
* Port 40333 testnet 41333, rpcport 40332 testnet 41332

Before you start mining VLU
-------

You are welcome to mine VLU, even when the diff is low and reward is high. But remember, that VLU is what it is, until we launch VLU Market. 

VLU Market is going to be the biggest crypto powered marketplace on the vanilla web. Think Amazon (in functionality, not size), but with the added bonus of using a crypto currency and having 100 % safe escrow. 

Compiling binary for *nix
-------
In Ubuntu you need the following dependencies:

``` 
sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.3-dev libdb5.3++-dev libminiupnpc-dev libssl-dev
``` 

Clone source from this Git repository and change directory to the `src/` folder.

Start compiling using:

```
make -f makefile.unix
```

If you enjoy not spending time compiling, you can have a look at our [Docker container](https://github.com/valuto/docker-valutod) or our [binary releases](https://github.com/valuto/valuto/releases).


Where is the GUI?
-------

The GUI for valutod is currently under development in the form of ValutoPy. A beta version of ValutoPy is available from http://downloads.valuto.io/ValutoPy_Beta_Setup.exe.


Marketplace
-------

By using your VLU in the marketplace, you are building the worlds first marketplace using 100 % decentralized payment system.

Sign up on [VLUMarket.com](http://vlumarket.com) to receive a notification when VLU Market goes live.


Valutowallet
-------

An online wallet is available at https://valutowallet.com

The source code for the online wallet can be found at https://github.com/valuto/valutowallet


License
-------

Valuto is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


