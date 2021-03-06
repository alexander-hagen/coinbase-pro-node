**[coinbase-pro-node](../README.md)**

> [Globals](../globals.md) / ["order/OrderAPI"](../modules/_order_orderapi_.md) / LimitOrder

# Interface: LimitOrder

## Hierarchy

- { client*oid?: undefined \| string ; product_id: string ; side: OrderSide ; stop?: \"loss\" \| \"entry\" ; stop_price?: undefined \| string ; stp?: [SelfTradePrevention](../enums/\_order_orderapi*.selftradeprevention.md) }

  ↳ **LimitOrder**

  ↳↳ [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md)

  ↳↳ [PostOnlyLimitOrder](_order_orderapi_.postonlylimitorder.md)

## Index

### Properties

- [client_oid](_order_orderapi_.limitorder.md#client_oid)
- [price](_order_orderapi_.limitorder.md#price)
- [product_id](_order_orderapi_.limitorder.md#product_id)
- [side](_order_orderapi_.limitorder.md#side)
- [size](_order_orderapi_.limitorder.md#size)
- [stop](_order_orderapi_.limitorder.md#stop)
- [stop_price](_order_orderapi_.limitorder.md#stop_price)
- [stp](_order_orderapi_.limitorder.md#stp)
- [time_in_force](_order_orderapi_.limitorder.md#time_in_force)
- [type](_order_orderapi_.limitorder.md#type)

## Properties

### client_oid

• `Optional` **client_oid**: undefined \| string

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[client_oid](_order_orderapi_.autocancellimitorder.md#client_oid)_

_Defined in [src/order/OrderAPI.ts:31](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L31)_

---

### price

• **price**: string

_Defined in [src/order/OrderAPI.ts:69](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L69)_

---

### product_id

• **product_id**: string

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[product_id](_order_orderapi_.autocancellimitorder.md#product_id)_

_Defined in [src/order/OrderAPI.ts:32](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L32)_

---

### side

• **side**: OrderSide

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[side](_order_orderapi_.autocancellimitorder.md#side)_

_Defined in [src/order/OrderAPI.ts:33](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L33)_

---

### size

• **size**: string

_Defined in [src/order/OrderAPI.ts:70](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L70)_

---

### stop

• `Optional` **stop**: \"loss\" \| \"entry\"

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[stop](_order_orderapi_.autocancellimitorder.md#stop)_

_Defined in [src/order/OrderAPI.ts:34](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L34)_

---

### stop_price

• `Optional` **stop_price**: undefined \| string

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[stop_price](_order_orderapi_.autocancellimitorder.md#stop_price)_

_Defined in [src/order/OrderAPI.ts:35](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L35)_

---

### stp

• `Optional` **stp**: [SelfTradePrevention](../enums/_order_orderapi_.selftradeprevention.md)

_Inherited from [AutoCancelLimitOrder](_order_orderapi_.autocancellimitorder.md).[stp](_order_orderapi_.autocancellimitorder.md#stp)_

_Defined in [src/order/OrderAPI.ts:36](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L36)_

---

### time_in_force

• `Optional` **time_in_force**: [TimeInForce](../enums/_order_orderapi_.timeinforce.md)

_Defined in [src/order/OrderAPI.ts:72](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L72)_

Default is 'GTC'.

---

### type

• **type**: [LIMIT](../enums/_order_orderapi_.ordertype.md#limit)

_Defined in [src/order/OrderAPI.ts:73](https://github.com/bennycode/coinbase-pro-node/blob/a3ed45b/src/order/OrderAPI.ts#L73)_
