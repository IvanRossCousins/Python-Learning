# Datatypes

Datatypes describe the different ways python can store data in variables, these can be used in combination and normally several datatypes can be used to accommodate a specific set of data.

You can check the type of an object with `type()` fucntion.

### Basic Datatypes

- **int** -> Whole nnumber integers between the values of -2147483648 and 2147483647.
- **float** -> A float stores a decimal number.
- **str** -> A string contains a string of characters and is a text type.
- **bool** -> A bool stores a `True` or `False` value and only requires a single bit.
- **bytes** -> Bytes store raw binary to be able to perform binary operations.


### Collection Datatypes

- **list** -> Lists hold, as implied, lists of data, these lists are ordered and can contain duplicates. `list_name = ["apple", "banana", "cherry"]`
- **tuple** -> Tuples hold multiple items in an ordered list, they can conmtain duplicated but are unchangeable. `tuple_name = ("apple", "banana", "cherry")`
- **range** -> Contains a range of numbers. `range_name = range(5)`
- **dict** -> Dictionaries are lists of `key`-`value` pairs. This allows for keys to be assigned to each entry. `dict_name = {"name" : "Lufter", "age" : 18}`
- **set** -> Like lists there are ordered sets of iems that are changeable, but they cannot contain duplicates. `set_name = {"apple", "banana", "cherry"}`