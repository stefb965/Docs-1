﻿
# COM
* [Creating Objects](#com_create)
* [Finding Objects](#com_find)
* [Releasing Objects](#com_release)
	


## com
The ``com`` library can be used to create and access COM instances on Windows.

The ``com`` is accessed by the global ``luacom`` variable.

For a complete reference, see refer to the [LuaCOM User Manual](http://www.tecgraf.puc-rio.br/~rcerq/luacom/pub/1.3/luacom-htmldoc/).



### Creating Objects
Creates an instance of the object with the specified id.

	obj = luacom.CreateObject("PowerPoint.Application");




### Finding Objects
Finds a running instance of the object with the specified id.

	obj = luacom.GetObject("PowerPoint.Application");




### Releasing Objects
It is very important to release all COM objects when they are no longer in use.

	obj = nil;
	collectgarbage();

