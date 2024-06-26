# dlg's layout

Inspired heavily by [my tada68 layout](https://github.com/qmk/qmk_firmware/tree/master/keyboards/tada68/keymaps/dlg).

Notable deviation from the default keymap includes correctly placing `KC_BSLS` and moving `KC_BSPC` up to the top row where it belongs. The additional key on the top-row is a NOOP while I think of something fun.  I also swapped `Esc` and `~` as in my tada68 layout.


### Base Layer

```
,---------------------------------------------------------------.
|~` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = |Bks|Bks|Esc|
|---------------------------------------------------------------|
|Tab  | Q | W | E | R | T | Y | U | I | O | P | [ | ] |  \  |Del|
|---------------------------------------------------------------|
|Ctrl  | A | S | D | F | G | H | J | K | L | ; | ' | Enter  |PUp|
|---------------------------------------------------------------|
|Shift   | Z | X | C | V | B | N | M | , | . | / |Shift |Up |PDn|
|---------------------------------------------------------------|
|Ctrl|Opt |Cmd |        Space            |Cmd |Fn  ||Lt |Dn |Rt |
`--------------------------------------------------''-----------'
```


### Fn Layer

```
,---------------------------------------------------------------.
|   |F1 |F2 |F3 |F4 |F5 |F6 |F7 |F8 |F9 |F10|F11|F12|Del|RST|   |
|---------------------------------------------------------------|
|     |   |   |   |   |   |   |   |mac|   |PSc|Br-|Br+|     |Ins|
|---------------------------------------------------------------|
|      |   |   |   |   |   |Lt |Dn |Up |Rt |   |   |        |Hme|
|---------------------------------------------------------------|
|        |   |   |   |   |   |   |MUT|V- |V+ |   |      |PUp|End|
|---------------------------------------------------------------|
|    |    |    |                         |    |    ||Hme|PDn|End|
`--------------------------------------------------''-----------'
```

### PC Layer

```
,---------------------------------------------------------------.
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
|---------------------------------------------------------------|
|     |   |   |   |   |   |   |   |   |   |   |   |   |     |   |
|---------------------------------------------------------------|
|      |   |   |   |   |   |   |   |   |   |   |   |        |   |
|---------------------------------------------------------------|
|        |   |   |   |   |   |   |   |   |   |   |      |   |   |
|---------------------------------------------------------------|
|Ctrl|Win |Alt |                         |Alt |    ||   |   |   |
`--------------------------------------------------''-----------'
```

### `LALT` Layer

Left Alt Layer - LALT-4 maps to LALT-F4 so I can quit apps

```
,---------------------------------------------------------------.
|   |   |   |   |F4 |   |   |   |   |   |   |   |   |   |   |   |
|---------------------------------------------------------------|
|     |   |   |   |   |   |   |   |   |   |   |   |   |     |   |
|---------------------------------------------------------------|
|      |   |   |   |   |   |   |   |   |   |   |   |        |   |
|---------------------------------------------------------------|
|        |   |   |   |   |   |   |   |   |   |   |      |   |   |
|---------------------------------------------------------------|
|    |    |    |                         |    |    ||   |   |   |
`--------------------------------------------------''-----------'
```
