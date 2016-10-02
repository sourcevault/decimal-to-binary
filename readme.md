
`@partially-applied/dec-to-bin`

Takes a decimal value and outputs the binary value as an array.

**Quick Guide in Code**

```livescript

dec-to-bin = require '@partially-appled/dec-to-bin'

console.log dec-to-bin 0 # [0]

console.log dec-to-bin 1 # [1]

console.log dec-to-bin 2 # [1,0]

console.log dec-to-bin 3 # [1,1]

```

`type-signature`

`
dec-to-bin :: Int -> [Bool,..Bool]
`


**Todo**

- reduce final `.reverse`
