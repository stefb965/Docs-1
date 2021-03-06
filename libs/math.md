﻿
# Math
* [math](#math-1)
* [extensions](#extensions)
* [round](#math-round-x-)


## math
The ``math`` library is a standard Lua library. It is a global library and does not need to be imported.

````lua
print(math.abs(-123));  -- 123
````

Refer to the [official Lua documentation](http://www.lua.org/manual/5.1/) for more details.



## extensions

The ``math`` library has been extended with some additional functions.



### math.round( x )
Rounds the value ``x`` to the nearest integer (rounds 0.5 up).

````lua
print(math.round(1.25));  -- 1
print(math.round(1.5));	  -- 2
print(math.round(1.75));  -- 2
````

