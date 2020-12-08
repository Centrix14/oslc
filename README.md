# oslc
## this repository contains a lisp calculator with a length of one line and a volume of 76 bytes!
here is its code:

```lisp
(print (eval (read-from-string (concatenate 'string "(" (read-line) ")"))))
```

in addition the calculator can execute lisp programs!
