Twine MathJax macros
====================

A couple of macros that let you use [MathJax](http://www.mathjax.org) to render LaTeX in a [Twine](http://twinery.org) story.

To use
------

In your **StoryIncludes** passage, add the line

```
mathjax.twee
```

and either make sure that that file is in the same directory as your story file, or use its full path.

For inline maths, use `<<math>>`.

For display maths, use `<<dmath>>`.

Example
-------

`<<math e^{i \pi} + 1 = 0 >`

There's an example story in `mathjax-demo.tws`


Licence
-------

Public domain or Apache 2.0. I don't care how you use this!
