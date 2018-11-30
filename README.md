# Bas' dotfiles

Largely copied from [Mathias Bynens][1] and adjusted for my own needs.

## Use case

These settings are all optimized for use on Debian Stretch servers, which are 
always managed over SSH, usually with [PuTTY][2].

## Colored prompt in PuTTY

By default PuTTY will report `$TERM` as `xterm`, which results in a monochrome 
prompt. To activate the colored prompt, go to  _Connections_, _Data_ and set 
_Terminal-type string_ to [`putty-256color`][3]. Alternatively, you can try 
`xterm-256color`, but programs like `htop` are known to behave weirdly with
function keys with that value.

[1]: https://github.com/mathiasbynens/dotfiles
[2]: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
[3]: https://superuser.com/questions/436910/emulate-256-colors-in-putty-terminal/1069018
