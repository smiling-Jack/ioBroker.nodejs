[**@iobroker/js-controller-adapter**](../../README.md) • **Docs**

***

[@iobroker/js-controller-adapter](../../globals.md) / [\<internal\>](../README.md) / AdapterObject

# Interface: AdapterObject

## Extends

- [`BaseObject`](BaseObject.md)

## Properties

### \_id

> **\_id**: [`Adapter`](../type-aliases/Adapter.md)

The ID of this object

#### Overrides

[`BaseObject`](BaseObject.md).[`_id`](BaseObject.md#_id)

#### Defined in

[types-dev/objects.d.ts:1115](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1115)

***

### acl?

> `optional` **acl**: [`ObjectACL`](ObjectACL.md)

#### Inherited from

[`BaseObject`](BaseObject.md).[`acl`](BaseObject.md#acl)

#### Defined in

[types-dev/objects.d.ts:917](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L917)

***

### common

> **common**: [`AdapterCommon`](AdapterCommon.md)

#### Overrides

[`BaseObject`](BaseObject.md).[`common`](BaseObject.md#common)

#### Defined in

[types-dev/objects.d.ts:1117](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1117)

***

### encryptedNative?

> `optional` **encryptedNative**: `string`[]

Like protectedNative, but the properties are also encrypted and decrypted automatically

#### Defined in

[types-dev/objects.d.ts:1121](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1121)

***

### enums?

> `optional` **enums**: `Record`\<`string`, `string` \| [`Translated`](../type-aliases/Translated.md)\>

#### Inherited from

[`BaseObject`](BaseObject.md).[`enums`](BaseObject.md#enums)

#### Defined in

[types-dev/objects.d.ts:916](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L916)

***

### from?

> `optional` **from**: `string`

#### Inherited from

[`BaseObject`](BaseObject.md).[`from`](BaseObject.md#from)

#### Defined in

[types-dev/objects.d.ts:918](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L918)

***

### instanceObjects

> **instanceObjects**: ([`StateObject`](StateObject.md) \| [`DeviceObject`](DeviceObject.md) \| [`ChannelObject`](ChannelObject.md) \| [`FolderObject`](FolderObject.md) \| [`MetaObject`](MetaObject.md))[]

Objects created for each instance, inside the namespace of this adapter

#### Defined in

[types-dev/objects.d.ts:1125](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1125)

***

### native

> **native**: `Record`\<`string`, `any`\>

#### Inherited from

[`BaseObject`](BaseObject.md).[`native`](BaseObject.md#native)

#### Defined in

[types-dev/objects.d.ts:914](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L914)

***

### nonEdit?

> `optional` **nonEdit**: [`NonEditable`](NonEditable.md)

These properties can only be edited if the correct password is provided

#### Inherited from

[`BaseObject`](BaseObject.md).[`nonEdit`](BaseObject.md#nonedit)

#### Defined in

[types-dev/objects.d.ts:923](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L923)

***

### notifications?

> `optional` **notifications**: [`Notification`](Notification.md)[]

Register notifications for the built-in notification system

#### Defined in

[types-dev/objects.d.ts:1123](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1123)

***

### objects

> **objects**: [`AnyObject`](../type-aliases/AnyObject.md)[]

Objects created for the adapter, anywhere in the global namespace

#### Defined in

[types-dev/objects.d.ts:1127](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1127)

***

### protectedNative?

> `optional` **protectedNative**: `string`[]

An array of `native` properties which cannot be accessed from outside the defining adapter

#### Defined in

[types-dev/objects.d.ts:1119](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1119)

***

### ts?

> `optional` **ts**: `number`

#### Inherited from

[`BaseObject`](BaseObject.md).[`ts`](BaseObject.md#ts)

#### Defined in

[types-dev/objects.d.ts:921](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L921)

***

### type

> **type**: `"adapter"`

#### Overrides

[`BaseObject`](BaseObject.md).[`type`](BaseObject.md#type)

#### Defined in

[types-dev/objects.d.ts:1116](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L1116)

***

### user?

> `optional` **user**: `string`

The user who created or updated this object

#### Inherited from

[`BaseObject`](BaseObject.md).[`user`](BaseObject.md#user)

#### Defined in

[types-dev/objects.d.ts:920](https://github.com/ioBroker/ioBroker.js-controller/blob/664d3c56250ad4e09c02e3cf6b90746a581d9f55/packages/types-dev/objects.d.ts#L920)