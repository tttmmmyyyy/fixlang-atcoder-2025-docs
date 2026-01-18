# Hash

Defined in hash@1.1.0

Provides the `Hash` trait and related traits, and basic hashing functions.

## Values

### namespace Hash

#### combine_hash

Type: `Std::U64 -> Std::U64 -> Std::U64`

Combines two hashes.

Using method described in https://stackoverflow.com/questions/5889238/why-is-xor-the-default-way-to-combine-hashes.

### namespace Hash::Hash

#### hash

Type: `[a : Hash::Hash] a -> Std::U64`

## Types and aliases

## Traits and aliases

### namespace Hash

#### trait `a : Hash`

Hashable types.

##### method `hash`

Type: `a -> Std::U64`

## Trait implementations

### impl `[a : Hash::Hash, b : Hash::Hash] (a, b) : Hash::Hash`

### impl `[a : Hash::Hash] Std::Array a : Hash::Hash`

### impl `Std::I16 : Hash::Hash`

### impl `Std::I32 : Hash::Hash`

### impl `Std::I64 : Hash::Hash`

### impl `Std::I8 : Hash::Hash`

### impl `Std::String : Hash::Hash`

### impl `Std::U16 : Hash::Hash`

### impl `Std::U32 : Hash::Hash`

### impl `Std::U64 : Hash::Hash`

### impl `Std::U8 : Hash::Hash`