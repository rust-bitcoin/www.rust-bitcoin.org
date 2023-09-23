# Chapter 1

test me

```rust,noplayground
use std::str::FromStr;

use bitcoin::hashes::Hash;
use bitcoin::locktime::absolute;
use bitcoin::secp256k1::{rand, Message, Secp256k1, SecretKey, Signing};
use bitcoin::sighash::{EcdsaSighashType, SighashCache};
use bitcoin::{
    Address, Network, OutPoint, ScriptBuf, Sequence, Transaction, TxIn, TxOut, Txid, WPubkeyHash,
    Witness,
};
```
