# Widths

The inuitcss `widths` module is a simple file of helper classes to drop widths
onto elements such as grid systems.

Install using Bower:

    $ bower install --save inuit-widths

inuitcss’ widths classes are available in one of two formats. The default format
is fraction-like, e.g.: `<div class="1/2">`.

The other available format is spoken-word, e.g. `<div class="one-half">`. Enable
this by predefining the `$inuit-use-fractions` feature switch, e.g.:

    $inuit-use-fractions:    false;
    @import "path/to/trumps.widths";
