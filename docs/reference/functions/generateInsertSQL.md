# Function generateInsertSQL

generate insert statement for informix database for given source data 


## Syntax

```js
dscopy.generateInsertSQL(x, y)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Unit &#124; Array &#124; Matrix | First value to add
`y` | number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Second value to add

### Returns

Type | Description
---- | -----------
number &#124; BigNumber &#124; Fraction &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Sum of `x` and `y`


## Examples

```js
dscopy.generateInsertSQL(x, y)              // returns insert into test (id,name) values (1,'test');

```


## See also

[generateUpdateSQL](generateUpdateSQL.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->