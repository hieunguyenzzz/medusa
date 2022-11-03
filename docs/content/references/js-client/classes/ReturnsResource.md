# Class: ReturnsResource

## Hierarchy

- `default`

  ↳ **`ReturnsResource`**

## Methods

### create

▸ **create**(`payload`, `customHeaders?`): [`ResponsePromise`](../modules/internal.md#responsepromise)<[`StoreReturnsRes`](../modules/internal-44.md#storereturnsres)\>

Creates a return request

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `payload` | [`StorePostReturnsReq`](internal-44.StorePostReturnsReq.md) | details needed to create a return |
| `customHeaders` | `Record`<`string`, `any`\> |  |

#### Returns

[`ResponsePromise`](../modules/internal.md#responsepromise)<[`StoreReturnsRes`](../modules/internal-44.md#storereturnsres)\>

#### Defined in

[medusa-js/src/resources/returns.ts:12](https://github.com/hieunguyenzzz/medusa/blob/0b0d50b4/packages/medusa-js/src/resources/returns.ts#L12)
