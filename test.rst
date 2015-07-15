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

An example::
 
 19  from onceaweek.tools import jsend
 20
 21  # to generate jsend formatted dictionary
 22  jsend.success({'key':'value'})
 23  # output = {'status':'success', 'data':{'key':'value'}
 24
 25  jsend.fail({'json':'object'})
 26  jsend.error('message')
 27
 28  jsend.is_success(json_string)
 29  jsend.is_fail(json_string)
 30  jsend.is_error(json_string)
 
