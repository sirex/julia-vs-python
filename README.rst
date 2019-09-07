This comparison is very subjective, from my point of view.

I started to use Python professionally since 2010. And I discovered Julia for
the first time in the beginning of 2019. So I have a lot of experience in
Python and no experience in Julia.

I thin Python is the best programming language ever created, but after looking
at Julia, I started to like it too.

To better understand which programming language is better, decided to do a
comparison Julia vs Python. All comparisons are subjective to my thinking. What
I'm trying to do is to decide for myself if Julia could be worth learning and
using in my new projects.

My background is mostly in web development, but in my free time I also like to
analize data using Jupyter and Pandas.

Even if this is a very subjective and personal comparison, I still decided to
share it with the internet, maybe some people will find it useful too.


Calculator
==========

.. code-block:: julia

   julia> π
   π = 3.1415926535897...


.. code-block:: python

   >>> π
   NameError: name 'π' is not defined

   >>> import math
   >>> π = math.pi

   >>> π
   3.141592653589793

I like to use Python as a calculator, but I find Julia as a better calculator
tool.

I like, that by default Julia REPL allows to enter `π` using TeX like syntax
`\\pi`. Python by default does not support that, but ipython has it too.

I like, that in Julia, greek letter `π`, by default gives ju π number, while in
Python, you have to import `pi` from `math` module.

Julia wins.


Functions
=========

.. code-block:: julia

   function f(a, b)
       a + b
   end


.. code-block:: python

   def f(a, b):
       return a + b

I think, that using indentation to separate code blocks is a very good idea.
Most programmers separate code blocks using indentation anyway, so why it
shouln't be part of code syntax?

Julia requires to put `end` at each code block, but `return` is optional. I'm
not sure about that. In some cases optional `return` improves readability, for
example, when you only need to return a multiline string block. But when you
need to return things in the middle of a function, then explicit `return` even
at the end of a function improves readability and consistency. So I'm not sure
about that.

Another thing `function` keyword is almost 3 times longer than `def`. Since
functions are very frequent thing in code, I definately like `def` more.

In this case Python is more on winning side, but probably having optional
`return` statement is a good thing.
