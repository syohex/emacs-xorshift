# xorshift.el

xorshift implementationn in Emacs Lisp

## Interface

#### `(xorshift-builder &optional seed)`

Return an anonymous function which calculates xorshift32.

#### `(xorshift96-builder &optional seed1 seed2 seed3)`

Return an anonymous function which calculates xorshift96.

#### `(xorshift128-builder &optional seed1 seed2 seed3)`

Return an anonymous function which calculates xorshift128.

## See also

- https://en.wikipedia.org/wiki/Xorshift
