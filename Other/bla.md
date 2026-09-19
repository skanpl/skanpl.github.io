[Home](/) | [GitHub](https://github.com/skanpl) | [_](https://skanpl.github.io/Other/bla)

I'm bored so here are some stuff i wrote because why not.

## Crash course on emacs keybindings

Before anything, let's keep in mind that `M` stands for `meta` which is the `alt` button and `C` stands for `ctrl`.\
The reading of `C-x` is *first press (and hold it) ctrl then press x then release your fingers* and similarily with say `M-x` etc.\
It takes some time to get used to this "finger acrobatics" but after a while you can get used to it. 

Now, here are some useful bindings to keep in mind.

- buffer management:\
`C-x <left>`: previous buffer\
`C-x <right>`: next buffer\
`C-x k`: kill current buffer\
`C-x o`: switch windows\
`C-x 2`: split buffer horizontally [—]\
`C-x 3`: split buffer vertically [|]\
`C-x +`: zoom in\
`C-x -`: zoom out\
`C-g`: cancel
- mode management: \ 
`M-x shell`: open the shell within emacs\
`M-x package-list-packages`: list all available packages\
`M-x package-install`: install a package\
`M-x load-file`: load an elisp file (e.g. your `.emacs`)\
`M-x eval-expression`: runs an elisp expression\
`M-x tetris`: play a meh version of tetris

- some specific stuff:
You can write math unicode with `M-x set-input-method RET tex`, e.g. typing `\forall` would then render as `∀`. To revert back the input method, just press `C-\`.\
When using proofgeneral for Rocq development, proofgeneral might not align itself with the current Rocq version you use (it might be because you have multiple opam switches) and to solve the issue you can do `M-x tuareg-opam-update-env` this will align proofgeneral's Rocq version with the one of your current opam switch.\
You can of course automate things in a way that the commands you like will be run each time you start emacs by putting the desired command in your `.emacs` file which should be located on the root of your linux file system.


## Emacs vs Vim
The great text editor war!\
Which one is the best ?!?!\
Idk and i'm not into this debate, just try them both and pick the one you like the most.

