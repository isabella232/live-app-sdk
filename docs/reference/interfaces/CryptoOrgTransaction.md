[@ledgerhq/live-app-sdk](../README.md) / [Exports](../modules.md) / CryptoOrgTransaction

# Interface: CryptoOrgTransaction

## Hierarchy

- [`TransactionCommon`](TransactionCommon.md)

  ↳ **`CryptoOrgTransaction`**

## Table of contents

### Properties

- [amount](CryptoOrgTransaction.md#amount)
- [family](CryptoOrgTransaction.md#family)
- [fees](CryptoOrgTransaction.md#fees)
- [mode](CryptoOrgTransaction.md#mode)
- [recipient](CryptoOrgTransaction.md#recipient)

## Properties

### amount

• **amount**: `BigNumber`

The amount of token to send in the transaction, denoted in the smallest cryptocurrency's magnitude
For example in BTC, a tx with an 'amount' field of 1 will correspond to a tx corresponding to 0.00000001 BTC

#### Inherited from

[TransactionCommon](TransactionCommon.md).[amount](TransactionCommon.md#amount)

#### Defined in

[types.ts:77](https://github.com/LedgerHQ/live-app-sdk/blob/1d8d8d5/src/types.ts#L77)

___

### family

• `Readonly` **family**: [`CRYPTO_ORG`](../enums/FAMILIES.md#crypto_org)

#### Defined in

[families/crypto_org/types.ts:9](https://github.com/LedgerHQ/live-app-sdk/blob/1d8d8d5/src/families/crypto_org/types.ts#L9)

___

### fees

• `Optional` **fees**: `BigNumber`

#### Defined in

[families/crypto_org/types.ts:11](https://github.com/LedgerHQ/live-app-sdk/blob/1d8d8d5/src/families/crypto_org/types.ts#L11)

___

### mode

• **mode**: `string`

#### Defined in

[families/crypto_org/types.ts:10](https://github.com/LedgerHQ/live-app-sdk/blob/1d8d8d5/src/families/crypto_org/types.ts#L10)

___

### recipient

• **recipient**: `string`

The address of the transaction's recipient

#### Inherited from

[TransactionCommon](TransactionCommon.md).[recipient](TransactionCommon.md#recipient)

#### Defined in

[types.ts:81](https://github.com/LedgerHQ/live-app-sdk/blob/1d8d8d5/src/types.ts#L81)
