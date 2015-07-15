rst-test
========

*italic* **bold**

An example::

    Whitespace, newlines, blank lines, and all kinds of markup
      (like *this* or \this) is preserved by literal blocks.
  Lookie here, I've dropped an indentation level
  (but not far enough)

python code::
 
 from woorizm.tools import jsend
 
 jsend.success({'jsend':'value'})
 jsend.fail({'jsend':'value'})
 jsend.error({'jsend':'value'})

 
Usage
-----
success example::

 >>> from onceaweek.tools import jsend
 >>> jsend.*success*({'key':'value'})
 {'status':'success', 'data':{'key':'value'}}
 
----
Test
----
