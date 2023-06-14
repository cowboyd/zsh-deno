zsh-emacs
===========

Useful [Deno][2] aliases and settings. This will set up your PATH
to have the ~/.deno/bin

Installation
------------

Once you have emacs already on your system, add the following to your
zsh plugin manaher. For example:

``` shell
# antigen
antigen bundle cowboyd/zsh-deno

#zim
zmodule cowboyd/zsh-deno
```

Aliases
-------

  * `e` edit a file or directory by connecting to an emacs server. If
    an emacs server is not started, it will be created for you.
  * `equick` start up emacs with absolutely no initialization
    customization whatsoever. Useful for digging yourself out of a
    hole if you managed to bork your init files.

[1]: https://github.com/zimfw/zimfw
[2]: https://deno.land
