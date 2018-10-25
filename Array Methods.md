## Array Methods
 
### 1.concat() Method:
The concat() method is used to merge two or more arrays. This method does not change the existing arrays, but instead returns a new array.

#### Syntax:
array1.concat(array2, array3, ..., arrayX)

### 2.copyWithin() Method:
The copyWithin() method copies array elements within the array, to and from specified positions.

#### Syntax:
arr.copyWithin(target)
arr.copyWithin(target, start)
arr.copyWithin(target, start, end)

### Array entries() Method:
The entries() method returns a new Array Iterator object that contains the key/value pairs for each index in the array.

#### Syntax
array.entries()

### Array every() Method:
1. The every() method checks if all elements in an array pass a test (provided as a function).
2. The every() method executes the function once for each element present in the array.
3. If it finds an array element where the function returns a false value, every() returns false (and does not check the remaining values)
4. If no false occur, every() returns true.

#### Syntax:
array.every(function(currentValue, index, arr), thisValue).

### Array fill() Method:
The fill() method fills all the elements of an array from a start index to an end index with a static value. The end index is not included.

#### Syntax
array.fill(value, start, end)

### Array filter() Method:
The filter() method creates an array filled with all array elements that pass a test (provided as a function).

#### Syntax
array.filter(function(currentValue, index, arr), thisValue).

### Array find() Method:
1. The find() method returns the value of the first element in an array that pass a test (provided as a function).
2. The find() method executes the function once for each element present in the array.
3. If it finds an array element where the function returns a true value, find() returns the value of that array element (and does not check the remaining values)
Otherwise it returns undefined.

#### Syntax
array.find(function(currentValue, index, arr),thisValue).

### Array findIndex() Method:
1.The findIndex() method returns the index of the first element in the array that satisfies the provided testing function.
2.The findIndex() method executes the function once for each element present in the array:
3.If it finds an array element where the function returns a true value, findIndex() returns the index of that array element (and does not check the remaining values)
Otherwise it returns -1.

#### Syntax:
array.findIndex(function(currentValue, index, arr), thisValue).

### Array forEach() Method:
The forEach() method executes a provided function once for each array element.

#### Syntax
array.forEach(function(currentValue, index, arr), thisValue).

### Array from() Method:
The Array.from() method returns an Array object from any object with a length property or an iterable object.

#### Syntax
Array.from(object, mapFunction, thisValue)

### Array includes() Method:
1.The includes() method determines whether an array contains a specified element.
2.This method returns true if the array contains the  element, and false if not.

#### Syntax:
array.includes(element, start).

### Array indexOf() Method:
1.The indexOf() method searches the array for the specified item, and returns its position.
2.The search will start at the specified position, or at the beginning if no start position is specified, and end the search at the end of the array.
3.Returns -1 if the item is not found.
4.If the item is present more than once, the indexOf method returns the position of the first occurence.

#### Syntax
array.indexOf(item, start);

### Array isArray() Method:
The Array.isArray() method determines whether the passed value is an Array.

#### Syntax
Array.isArray(obj).

### Join() Method:
1. The join() method joins the elements of an array into a string, and returns the string.
2. The elements will be separated by a specified separator. The default separator is comma (,).

#### Syntax
array.join(separator).

### Array keys() Method:
The keys() method returns a new Array Iterator object that contains the keys for each index in the array.

#### Syntax
array.keys()

### Array lastIndexOf() Method:
1. The lastIndexOf() method returns the last index at which a given element can be found in the array, or -1 if it is not present. 
2. The array is searched backwards, starting at fromIndex.