0.2.0
======
:release date: NOT RELEASED YET

New feature
------------
* Add *object_hook* and *list_hook* option to unpacker. It allows you to
  hook unpacing mapping type and array type.

* Add *default* option to packer. It allows you to pack unsupported types.

* unpacker accepts (old) buffer types.

Bugs fixed
----------
* Compilation error on win32.
