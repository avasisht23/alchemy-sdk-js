[alchemy-sdk](../README.md) / [Exports](../modules.md) / GetMintedNftsOptions

# Interface: GetMintedNftsOptions

Optional parameters object for the [NftNamespace.getMintedNfts](../classes/NftNamespace.md#getmintednfts) method.

## Table of contents

### Properties

- [contractAddresses](GetMintedNftsOptions.md#contractaddresses)
- [pageKey](GetMintedNftsOptions.md#pagekey)
- [tokenType](GetMintedNftsOptions.md#tokentype)

## Properties

### contractAddresses

• `Optional` **contractAddresses**: `string`[]

List of NFT contract addresses to filter mints by. If omitted, defaults to
all contract addresses.

#### Defined in

[src/types/nft-types.ts:633](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5cfa150/src/types/nft-types.ts#L633)

___

### pageKey

• `Optional` **pageKey**: `string`

Optional page key from an existing [TransfersNftResponse](TransfersNftResponse.md) to use for
pagination.

#### Defined in

[src/types/nft-types.ts:645](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5cfa150/src/types/nft-types.ts#L645)

___

### tokenType

• `Optional` **tokenType**: [`ERC721`](../enums/NftTokenType.md#erc721) \| [`ERC1155`](../enums/NftTokenType.md#erc1155)

Filter mints by ERC721 vs ERC1155 contracts. If omitted, defaults to all
NFTs.

#### Defined in

[src/types/nft-types.ts:639](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5cfa150/src/types/nft-types.ts#L639)
