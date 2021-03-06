[fluent-iterable - v0.2.4](../README.md) / IterableClassDecorator

# Interface: IterableClassDecorator<TDecoratorArgs\>

## Type parameters

Name | Type |
:------ | :------ |
`TDecoratorArgs` | Args |

## Hierarchy

* [*IterableDecorator*](iterabledecorator.md)<[*ClassDecoratorItem*](classdecoratoritem.md)<TDecoratorArgs\>\>

  ↳ **IterableClassDecorator**

## Callable

▸ **IterableClassDecorator**(...`args`: TDecoratorArgs): ClassDecorator

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | TDecoratorArgs |

**Returns:** ClassDecorator

## Table of contents

### Methods

- [[Symbol.iterator]](iterableclassdecorator.md#[symbol.iterator])
- [clear](iterableclassdecorator.md#clear)

## Methods

### [Symbol.iterator]

▸ **[Symbol.iterator]**(): *Iterator*<[*ClassDecoratorItem*](classdecoratoritem.md)<TDecoratorArgs, Function\>, any, undefined\>

**Returns:** *Iterator*<[*ClassDecoratorItem*](classdecoratoritem.md)<TDecoratorArgs, Function\>, any, undefined\>

Inherited from: [IterableDecorator](iterabledecorator.md)

___

### clear

▸ **clear**(): *void*

**Returns:** *void*

Inherited from: [IterableDecorator](iterabledecorator.md)
