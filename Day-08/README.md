# Lists and Tuples

List in Python
List is a container that contains different types of objects. In it, the elements are separated by commas and stored within square brackets. Each element of a list has a unique position index, starting from 0.

Example
The following example shows how to create, display and modify a list in Python.

Open Compiler
```
# creating a list of characters
char_list = ['a', 'b', 'c', 'd', 'e']
print("Original list:", char_list)

# Modifying the list
char_list[0] = 10
char_list.append(5)
print("After modifying list:",char_list)
When you run this program, the following output will be displayed ?

Original list: ['a', 'b', 'c', 'd', 'e']
After modifying list: [10, 'b', 'c', 'd', 'e', 5]

```
Tuples in Python
Tuple is also similar to a list but it contains immutable objects and they are stored within parentheses. Those objects that cannot be modified by any means are called as immutable.

Example
In this example, we will create a tuple and try to modify it.

Open Compiler
```
# creating a tuple of characters
char_tuples = ('a', 'b', 'c', 'd', 'e')
print("Original tuple:", char_tuples)

# Modifying the tuple
char_tuples[0] = 10
print("After modifying tuple:",char_tuples)
```
On executing, the original tuple will be displayed along with an error message which specifies tuples elements could not be modified.
