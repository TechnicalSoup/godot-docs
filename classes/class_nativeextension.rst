:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/NativeExtension.xml.

.. _class_NativeExtension:

NativeExtension
===============

**Inherits:** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

.. container:: contribute

	There is currently no description for this class. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

Methods
-------

+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                                 | :ref:`close_library<class_NativeExtension_method_close_library>` **(** **)**                                                                                      |
+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`InitializationLevel<enum_NativeExtension_InitializationLevel>` | :ref:`get_minimum_library_initialization_level<class_NativeExtension_method_get_minimum_library_initialization_level>` **(** **)** |const|                        |
+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                                 | :ref:`initialize_library<class_NativeExtension_method_initialize_library>` **(** :ref:`InitializationLevel<enum_NativeExtension_InitializationLevel>` level **)** |
+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                                              | :ref:`is_library_open<class_NativeExtension_method_is_library_open>` **(** **)** |const|                                                                          |
+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Error<enum_@GlobalScope_Error>`                                | :ref:`open_library<class_NativeExtension_method_open_library>` **(** :ref:`String<class_String>` path, :ref:`String<class_String>` entry_symbol **)**             |
+----------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Enumerations
------------

.. _enum_NativeExtension_InitializationLevel:

.. _class_NativeExtension_constant_INITIALIZATION_LEVEL_CORE:

.. _class_NativeExtension_constant_INITIALIZATION_LEVEL_SERVERS:

.. _class_NativeExtension_constant_INITIALIZATION_LEVEL_SCENE:

.. _class_NativeExtension_constant_INITIALIZATION_LEVEL_EDITOR:

enum **InitializationLevel**:

- **INITIALIZATION_LEVEL_CORE** = **0**

- **INITIALIZATION_LEVEL_SERVERS** = **1**

- **INITIALIZATION_LEVEL_SCENE** = **2**

- **INITIALIZATION_LEVEL_EDITOR** = **3**

Method Descriptions
-------------------

.. _class_NativeExtension_method_close_library:

- void **close_library** **(** **)**

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

----

.. _class_NativeExtension_method_get_minimum_library_initialization_level:

- :ref:`InitializationLevel<enum_NativeExtension_InitializationLevel>` **get_minimum_library_initialization_level** **(** **)** |const|

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

----

.. _class_NativeExtension_method_initialize_library:

- void **initialize_library** **(** :ref:`InitializationLevel<enum_NativeExtension_InitializationLevel>` level **)**

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

----

.. _class_NativeExtension_method_is_library_open:

- :ref:`bool<class_bool>` **is_library_open** **(** **)** |const|

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

----

.. _class_NativeExtension_method_open_library:

- :ref:`Error<enum_@GlobalScope_Error>` **open_library** **(** :ref:`String<class_String>` path, :ref:`String<class_String>` entry_symbol **)**

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
