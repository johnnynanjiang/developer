# Deep Linking

## Usage 
### Open dapp browser for specific url and coin_id
```
trust://open_url?coin_id=61&url=https://compound.finance
https://link.trustwallet.com/open_url?coin_id=61&url=https://compound.finance
```
### Activate coin
```
trust://activate_coin?coin_id=60
https://link.trustwallet.com/activate_coin?coin_id=60
```

### Add custom token:
```
trust://add_token?token_id=0x514910771af9ca656af840dff83e8264ecf986ca
https://link.trustwallet.com/add_token?token_id=0x514910771af9ca656af840dff83e8264ecf986ca
```

## Definition

- `coin_id` is BIP44 [index](https://github.com/satoshilabs/slips/blob/master/slip-0044.md)

- `token_id` token identifier on the blockchain

#### Available domains links:

- `https://link.trustwallet.com`
- `trust://`
