[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [<internal\>](../modules/internal_.md) / SendableMessage

# Interface: SendableMessage

[<internal>](../modules/internal_.md).SendableMessage

## Hierarchy

- **`SendableMessage`**

  ↳ [`Message`](internal_.Message.md)

## Table of contents

### Properties

- [callback](internal_.SendableMessage.md#callback)
- [command](internal_.SendableMessage.md#command)
- [from](internal_.SendableMessage.md#from)
- [message](internal_.SendableMessage.md#message)

## Properties

### callback

• `Optional` **callback**: [`MessageCallbackInfo`](internal_.MessageCallbackInfo.md)

Callback information. This is set when the source expects a response

#### Defined in

[types/index.d.ts:231](https://github.com/ioBroker/ioBroker.js-controller/blob/7dd079e8/packages/types/index.d.ts#L231)

___

### command

• **command**: `string`

The command to be executed

#### Defined in

[types/index.d.ts:225](https://github.com/ioBroker/ioBroker.js-controller/blob/7dd079e8/packages/types/index.d.ts#L225)

___

### from

• **from**: `string`

The source of this message

#### Defined in

[types/index.d.ts:229](https://github.com/ioBroker/ioBroker.js-controller/blob/7dd079e8/packages/types/index.d.ts#L229)

___

### message

• **message**: `any`

The message payload

#### Defined in

[types/index.d.ts:227](https://github.com/ioBroker/ioBroker.js-controller/blob/7dd079e8/packages/types/index.d.ts#L227)