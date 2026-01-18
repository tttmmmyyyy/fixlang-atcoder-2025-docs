# Minilib.Math.Types

Defined in minilib-math@0.6.1

Type definitions for mathematical concepts, for example AdditiveGroup, Ring, Field.

## Values

### namespace Minilib.Math.Types::DivMod

#### divmod

Type: `[a : Minilib.Math.Types::DivMod] a -> a -> (a, a)`

`divmod(a, b)` returns `(a/b, a%b)`.

### namespace Minilib.Math.Types::MulScalar

#### mul_scalar

Type: `[a : Minilib.Math.Types::MulScalar] Minilib.Math.Types::MulScalar::ScalarType a -> a -> a`

### namespace Minilib.Math.Types::One

#### one

Type: `[a : Minilib.Math.Types::One] a`

## Types and aliases

## Traits and aliases

### namespace Minilib.Math.Types

#### trait `a : DivMod`

A trait for division-with-remainder.

##### method `divmod`

Type: `a -> a -> (a, a)`

`divmod(a, b)` returns `(a/b, a%b)`.

#### trait `a : MulScalar`

A trait that represents scalar multiplication.

##### type `ScalarType`

Defined as: `ScalarType a`

##### method `mul_scalar`

Type: `Minilib.Math.Types::MulScalar::ScalarType a -> a -> a`

#### trait `a : One`

A trait that represents a multiplicative unit.

##### method `one`

Type: `a`

## Trait implementations

### impl `Std::F32 : Minilib.Math.Types::One`

### impl `Std::F64 : Minilib.Math.Types::One`

### impl `Std::I64 : Minilib.Math.Types::DivMod`

### impl `Std::I64 : Minilib.Math.Types::One`

### impl `Std::U64 : Minilib.Math.Types::DivMod`