<p align="center">
  <h1> Task Fair Token</h1>
  <img src="./logo.png">
</p>


* _Standart_        : ERC20
* _Name_            : TaskFairToken
* _Ticket_          : TFT
* _Decimals_        : 18
* _Emission_        : Mintable
* _Crowdsales_      : 2
* _Fiat dependency_ : No
* _Tokens locked_   : Yes

## Smart-contracts description

Contract mint bounty, advisors and founders tokens after each stage finished. 
Crowdsale contracts have special function to retrieve transferred in errors tokens.

### Contracts contains
1. _TaskFairToken_ 
2. _PreTGE_
3. _TGE_

### How to manage contract
To start working with contract you should follow next steps:
1. Compile it in Remix with enamble optimization flag and compiler 0.4.18
2. Deploy bytecode with MyEtherWallet. 

After crowdsale contract manager must call finishMinting. 

### How to invest
To purchase tokens investor should send ETH (more than minimum 0.1 EHT) to corresponding crowdsale contract.
Recommended GAS: 200 000 , GAS PRICE - 60 Gwei.

### Wallets with ERC20 support
1. MyEtherWallet - https://www.myetherwallet.com/
2. Parity 
3. Mist/Ethereum wallet

EXODUS not support ERC20, but have way to export key into MyEtherWallet - http://support.exodus.io/article/128-how-do-i-receive-unsupported-erc20-tokens

Investor must not use other wallets, coinmarkets or stocks. Can lose money.

## Main network configuration

* _Base price_                 : 4000 TFT per ETH

#### Links
* _Token_ - https://etherscan.io/token/0xf9cb429a0a56d1bdf6b4dc4b4d729c1208726674
* _PreTGE_ - https://etherscan.io/address/0xc87b7887f62c6674a19103fc35c749474d78ff40
* _TGE_ - https://etherscan.io/address/0x6b5f8cb3f5bd108d8004a38b54dc6d19a11e6a82

#### Pre Token General Event
* _Minimal insvested limit_    : 1 ETH
* _Softcap_                    : 40 ETH
* _Hardcap_                    : 4540 ETH
* _Developers tokens percent_  : 3% of total tokens
* _Founders tokens percent_    : 5% of total tokens
* _Bounty tokens percent_      : 5% of total tokens
* _Growth fund tokens percent_ : 30% of total tokens
* _Advisors tokens percent_    : 2% of total tokens
* _Security tokens percent_    : 0.5% of total tokens
* _Developers ETH percent_     : 2% of eth
* _Security ETH percent_       : 1% of eth
* _Start_                      : Sun, 10 Dec 2017 1:00:00 EST
* _Contract manager_           : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447
* _Direct mint agent_          : 
* _ETH Wallet_                 : 0x73598a82559f3566Ecf93aab415323668124191C 
* _Developers tokens wallet_   : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447
* _Founders tokens wallet_     : 0xd63c6c4977B80a2042aA71bEd548e32A856e9481
* _Bounty tokens wallet_       : 0x1C59BD0658DA5f357926D38083286A7E25Cd6f97
* _Growth fund tokens wallet_  : 0x9518ea93647DC3B198d3B04AD229977d8485fA1A
* _Advisors tokens wallet_     : 0x17D34009D6e16Ae35dCfF3840d9eeC832d75FeA6
* _Security tokens wallet_     : 0xe3B9E00c0b0E676A9105E7BbF984667d12e06d51
* _Security wallet_            : 0xe3B9E00c0b0E676A9105E7BbF984667d12e06d51
* _Developers ETH wallet_      : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447


_Milestones_

1. 1 week or up to  570 ETH    : discount 40%
2. 1 week or up to 1400 ETH    : discount 30%
3. 1 week or up to 2570 ETH    : discount 20%

#### Token General Event
* _Minimal insvested limit_    : 0.1 ETH
* _Hardcap_                    : 26330 ETH
* _Developers tokens percent_  : 3% of total tokens
* _Founders tokens percent_    : 5% of total tokens
* _Bounty tokens percent_      : 5% of total tokens
* _Growth fund tokens percent_ : 30% of total tokens
* _Advisors tokens percent_    : 2% of total tokens
* _Security tokens percent_    : 0.5% of total tokens
* _Developers ETH percent_     : 2% of eth
* _Security ETH percent_       : 1% of eth
* _Start_                      : Wed, 3 Jan 2018 1:00:00 GMT
* _Contract manager_           : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447
* _Direct mint agent_          :  
* _ETH Wallet_                 : 0x570241a4953c71f92B794F77dd4e7cA295E79bb1
* _Developers tokens wallet_   : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447
* _Founders tokens wallet_     : 0xFEED17c1db96B62C18642A675a6561F3A395Bc10
* _Bounty tokens wallet_       : 0xb2C6f32c444C105F168a9Dc9F5cfCCC616041c8a
* _Growth fund tokens wallet_  : 0xEc3E7D403E9fD34E83F00182421092d44f9543b2
* _Advisors tokens wallet_     : 0x7C737C97004F1C9156faaf2A4D04911e970aC554
* _Security tokens wallet_     : 0xe3B9E00c0b0E676A9105E7BbF984667d12e06d51
* _Security wallet_            : 0xe3B9E00c0b0E676A9105E7BbF984667d12e06d51
* _Developers ETH wallet_      : 0xad3Df84A21d508Ad1E782956badeBE8725a9A447

_Milestones_
1. 1 week or up to  2850 ETH   : discount 20%
2. 1 week or up to  5700 ETH   : discount 10%
3. 1 week or up to 18280 ETH   : no discount


## Kovan network configuration 1 old test

* _Base price_                 : 325 TFT per ETH

#### Links
* _Token_ - https://kovan.etherscan.io/token/0xe14d93851224ab1d171d6f19342b71f2dce87bbc
* _PreTGE_ - https://kovan.etherscan.io/address/0xe389aa4990d54193cd47296a040ff09645575fde
* _TGE_ - https://kovan.etherscan.io/address/0x6473b4e65285fd3f4394c5d159209634db9df8de

#### PreTGE
* _Minimal insvested limit_    : 1 ETH
* _Softcap_                    : 4 ETH
* _Hardcap_                    : 10000 ETH
* _Developers tokens percent_  : 3% of total tokens
* _Founders tokens percent_    : 5% of total tokens
* _Bounty tokens percent_      : 5% of total tokens
* _Growth fund tokens percent_ : 30% of total tokens
* _Advisors tokens percent_    : 2% of total tokens
* _Developers ETH percent_     : 2% of eth
* _Start_                      : Wed, 15 Nov 2017 00:00:00 GMT
* _End_                        : Fri, 17 Nov 2017 00:00:00 GMT
* _Contract manager_           : 0xb8600b335332724Df5108Fc0595002409c2ADbC6
* _Direct mint agent_          : 0xc56b0d5BBc2bF9b760ebD797DAcD3A683Cb8498F
* _ETH Wallet_                 : 0xb8600b335332724Df5108Fc0595002409c2ADbC6
* _Developers tokens wallet_   : 0x54a67F1507dEb1BFc58ba3ffa94B59fC50EB74BC
* _Founders tokens wallet_     : 0xE619BCD3c4609AE269B5eBE5bf0cb7D1Dc70C210
* _Bounty tokens wallet_       : 0x66fF3b89e15ACB0B5e69179a2e54c494b89bdB1B
* _Growth fund tokens wallet_  : 0x39eCC9E56979c884B28D8c791890E279AB1Ec5F4
* _Advisors tokens wallet_     : 0xD1BC33B2c89C93E65b0D476B8b50BFee82594847
* _Developers ETH wallet_      : 0x54a67F1507dEb1BFc58ba3ffa94B59fC50EB74BC


_Milestones_

1. 1 day                       : +40%
2. 2 days                      : +30%

#### TGE
* _Minimal insvested limit_    : 0.1 ETH
* _Hardcap_                    : 20769 ETH
* _Developers tokens percent_  : 3% of total tokens
* _Founders tokens percent_    : 5% of total tokens
* _Bounty tokens percent_      : 5% of total tokens
* _Growth fund tokens percent_ : 30% of total tokens
* _Advisors tokens percent_    : 2% of total tokens
* _Developers ETH percent_     : 2% of eth
* _Start_                      : Sat, 18 Nov 2017 00:00:00 GMT
* _End_                        : Tue, 21 Nov 2017 00:00:00 GMT
* _Contract manager_           : 0xb8600b335332724Df5108Fc0595002409c2ADbC6
* _Direct mint agent_          : 0xc56b0d5BBc2bF9b760ebD797DAcD3A683Cb8498F
* _ETH Wallet_                 : 0x67d78DE2f2819dcBd47426A1ac6a23B9e9C9d300
* _Developers tokens wallet_   : 0x87f2f8a94986D9049147590E12a64fFaa9f946A8
* _Founders tokens wallet_     : 0x39eCC9E56979c884B28D8c791890E279AB1Ec5F4
* _Bounty tokens wallet_       : 0x772215cCF488031991f7DCC65e80A7C1FD497E75
* _Growth fund tokens wallet_  : 0x39eCC9E56979c884B28D8c791890E279AB1Ec5F4
* _Advisors tokens wallet_     : 0x6Bb6dBc29f8adb3a7627eA65372FE471509b7698
* _Developers ETH wallet_      : 0xc56b0d5BBc2bF9b760ebD797DAcD3A683Cb8498F

_Milestones_
1. 1 day                       : +20%
2. 1 day                       : +10%

### Test audit

#### Investors

##### PreTGE
* https://kovan.etherscan.io/tx/0x33836049436a84d8803fbee0377fde7d93ea6a0455b267dca1747cdede197fde

##### TGE

##### Service operations

#### Transfer tokens transactions

