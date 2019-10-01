
### Filter
##### Inspiration
* http://www.ecma-international.org/ecma-262/10.0/index.html#sec-array.prototype.filter
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
* https://docs.microsoft.com/en-us/office/vba/language/reference/user-interface-help/filter-function

##### Description
The `Filter()` method filters and returns the current array based on the specified filter criteria. 

##### Note
Provides ability to filter on variant arrays (not just with strings unlike the VBA version).

##### Arguments
###### `match` (Variant)
The value to compare against
###### *Optional* `exclude` (Boolean)
Boolean value indicating whether to return values that include or exclude `match`. If include is True, `Filter` returns the subset of the array that contains `match`. If include is False, `Filter` returns the subset of the array that does not contain `match`.
##### Returns
##### (Variant)
The modified array.