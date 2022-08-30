[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [<internal\>](../modules/internal_.md) / ReadDirResult

# Interface: ReadDirResult

[<internal>](../modules/internal_.md).ReadDirResult

Contains the return values of readDir

## Table of contents

### Properties

- [acl](internal_.ReadDirResult.md#acl)
- [createdAt](internal_.ReadDirResult.md#createdat)
- [file](internal_.ReadDirResult.md#file)
- [isDir](internal_.ReadDirResult.md#isdir)
- [modifiedAt](internal_.ReadDirResult.md#modifiedat)
- [stats](internal_.ReadDirResult.md#stats)

## Properties

### acl

• `Optional` **acl**: [`EvaluatedFileACL`](internal_.EvaluatedFileACL.md)

Access rights

#### Defined in

node_modules/@types/iobroker/index.d.ts:1822

___

### createdAt

• `Optional` **createdAt**: `number`

Date of creation

#### Defined in

node_modules/@types/iobroker/index.d.ts:1826

___

### file

• **file**: `string`

Name of the file or directory

#### Defined in

node_modules/@types/iobroker/index.d.ts:1814

___

### isDir

• **isDir**: `boolean`

Whether this is a directory or a file

#### Defined in

node_modules/@types/iobroker/index.d.ts:1820

___

### modifiedAt

• `Optional` **modifiedAt**: `number`

Date of last modification

#### Defined in

node_modules/@types/iobroker/index.d.ts:1824

___

### stats

• **stats**: [`Stats`](../classes/internal_.Stats.md) \| [`Record`](../modules/internal_.md#record)<`string`, `never`\>

File system stats

#### Defined in

node_modules/@types/iobroker/index.d.ts:1818