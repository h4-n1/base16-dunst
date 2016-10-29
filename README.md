# base16-dunst

This repository is meant to work with
[chriskempson/base16](https://github.com/chriskempson/base16).
It provides a simple template that can be used with the base16 color schemes to
generate a functional config file for
[knopwob/dunst](https://github.com/knopwob/dunst),
a lightweight and customizable notification daemon.

To use, you can copy one of the config files in themes/ or use curl:

```
mkdir -p ~/.config/dunst
curl https://raw.githubusercontent.com/khamer/base16-dunst/master/themes/base16-default-dark.dunstrc >> ~/.config/dunst/dunstrc
```

We used `msg_urgency` configuration instead of `urgency_low`, `urgency_normal`,
`urgency_critical` to allow for additional configuration to these earlier in
`dunstrc`.
