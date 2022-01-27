# Python
- OOP Lang.
## ananconda
- python.exe
- >>> opens !
## windows cmd
```console
dir py*.exe
python
```
## ide - anaconda navigator
- .net virtual machines ???
- > jupyter lab (browser)
- > notebook ?
- > spider 
  - run cell (partial exec)
  - variable explorer

- dynamically typed 
- type checking is done at runtime !
- guido van rossum => community group that is monty python
# Cpython
- parser uses source code to generate an abstract syntax tree 
- compiler turns it into bytecode (.pyc)
- interpreter will exec line by line
- easy to test and debug !
- free and open source
- portable 
- gui programming
- large library
- web2py ? numpy , pyramid , scikit
- (.pyd) win dll file ?
- (.pyo) file created with optimizations
- (.pyw) python script for windows
- (.pyz) python script archive
 
```py
c=10
print("So the value of c is {}".format(c))
```
# Questions / Notes
-  is __init__ the constructor ???
-  self is called this refeerence 
-  create a new_attribute of class ??? obj.new_attr = 5
-  you can delete obj / their attrib by "del" keyword !
-  file handling methods ??
-  
### Array
- extend() another list ? destructuring and then appending (... in js ?)
- insert() insert element at another index ?
- remove()
- pop(3)
- clear()
- index() first matched element 
- count() 
- sort()
- reverse()
- copy()
- ["a"] x 3 = ['a','a','a']
- [-3:-1] => will not print last element !
## file
- close()
- detach()
- readline() , readlines()
- seek()
### assert 
assert 5 > 5 => boolean output 
### try
try:
  x=9
  raise ZeroDivError
except Zero:
  print("div by 0")
finally:
  print("exec")

### global 
it is not a new var but the global variable
defines scope
### is 
True is True
### arrow functions ?
a = lambda x:x*2
a(i)
## nonlocal
- it's like get the variable just above the scope of this function ?
- that var is not global ye not local
- what if the nesting is thrice ????

## yield
- is it accumalating all the values ?
- returns an iterator 
- delays the exec until it is called again !?
- when it starts again it starts from where it left off ??


## tuple
- faster than a list
- can be used as key for dict 
- with list it is not possible
- write protected
- all() - if all are True
- any()
- enumerate() 
- max()
- sorted() returns new sorted list !!
- sum()
- tuple(['2','3'])
- common practice to use tuples for heterogeneous data
- can be reassigned !! not const but immutable

# Sets
- unordered collection of unique items 
- no duplicates
- immutable elements
- but set itself is mutable add / remove items from it 
- union , intersection , symm diff

## set methods
- add() 
- clear
- copy() shallow copy
- difference() return the diff of 2 or more sets as a new set
- difference_update() remove all ele of other set from this
- discard() remove an ele is it's a member
- intersection() _update()
- isdisjoint() true if 2 sets have a null inters
- issubset()


- issuperset() True if this set contains another
- pop() remove arbitrary ele , KeyError if set is empty()
- remove() ele, KeyError
- symmetric_difference() as a new set, _update()
- union()
- update() update a set with the union of itself and other

- all() - returns true if all ele are true
- any()
- enumerate()
- max()
- sorted() - new set !
- sum()

### set can't contain lists as ele !!! bcoz lists are immutable ;)
### we can make sets from a list
### we can make a list from a set

```py
my_set.add(77)
my_set.update([10,20,30],{10,20,30}) # list gets destructured & then gets added

my_set.remove(5) // will throe error
my_set.discard(5) // no error !!




```


# find the common factors of 2 numbers 
> Sets
- to find the factors of both the numbers -> 2 set (unique)
- intersection !!
> Math:  Common factors of 2 no.s are all the factors of their gcd 
- make a for loop from 1 to sqrt(n) 
- y sqrt(n) 
- fact : if a number has a factor in the range (1,sqrt(n)) another factor lies in (sqrt(N),N)
-   2 8*8 32    64
-   [1 , sqrt(n) ) => nf+=2
-   if(n== sqrt(n)*sqrt(n)) nf++;

generator



