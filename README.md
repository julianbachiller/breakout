# breakout

A clone of Breakout. This particular clone was originally written for the TI-Explorer Lisp Machine, and ported in this version to "modern" Common-Lisp using SDL bindings.

The original sources were taken from the [CMU AI Repository](http://www-cgi.cs.cmu.edu/afs/cs/project/ai-repository/ai/lang/lisp/code/impdep/explorer/).

I've used SBCL, so I have no clue if/how this will work on other Lisps. To run this you'll need quicklisp and lispbuilder-sdl.

If you don't have quicklisp you can find instructions here:<br/>
https://golems.github.io/motion-grammar-kit/install.html

or here:<br/>
https://lispcookbook.github.io/cl-cookbook/getting-started.html

Then once into the REPL:

```
* (load "~/quicklisp/setup.lisp")

T
* (ql:quickload :lispbuilder-sdl)
To load "lispbuilder-sdl":
  Load 1 ASDF system:
    lispbuilder-sdl
; Loading "lispbuilder-sdl"
......
(:LISPBUILDER-SDL)
* (load "breakout")

T
* (breakout)
```
