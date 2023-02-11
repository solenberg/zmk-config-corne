# Corne Keyboard Layout

## Keymap

> This is a first draft. The keymap is subject to change at random, but I will
> try to keep this updated as I go. 

I decided to go with a wireless build, so there aren't any LEDs on this board.
If I decide I like this, I may pick up a second and make a wired version for my 
desk.

### BASE

For the most part, this is a standard qwerty layout. I am using tap for
space and return, and hold for shift on the innermost thumb keys.

`NAV` is a cursor navigation and media control layer  
`NUM` is a number layer and F# key layer  
`SYM` is a symbol layer accessed by holding both `NAV` and `NUM`

```text
+------------------------+     +-----------------------+
|ESC | Q | W | E | R | T |     | Y | U | I | O | P |DEL|
|TAB | A | S | D | F | G |     | H | J | K | L | ; | ' |
|CTRL| Z | X | C | V | B |     | N | M | , | . | / |GUI|
+------------|ALT|NUM|SHF|     |SHF|NAV|BKS|-----------+
                  || |ENT|     |SPC| ||
                  \\=======SYM=======//
```

### NAV

I prefer cross keyboard modifiers, so the layer is accessed with the right thumb and
keys are accessed with the left hand. This is a basic cursor navigation layer
with music controls.

```text
+-------------------------+     +-----------------------+
|PRV|HME |BCK|UP |FWD|END |     |   |   |   |   |   |   |
|PP |PGUP|LFT|DN |RGT|PGDN|     |   |   |   |   |   |   |
|NXT|    |CUT|CPY|PST|    |     |   |   |   |   |   |   |
+------------|   |   |    |     |   |   |   |-----------+
```


### NUM

For the most part I try not to use layers on the same hand, but I don't access
my Function keys all that often so I'm testing out keeping the F# keys on the
left hand. The right half also has some of my commonly used symbols.

```text
+-----------------------+     +-----------------------+
|   |   |F7 |F8 |F9 |F10|     | ( | 7 | 8 | 9 | \ | ) |
|   |   |F4 |F5 |F6 |F11|     | [ | 4 | 5 | 6 | - | ] |
|   |   |F1 |F2 |F3 |F12|     | 0 | 1 | 2 | 3 | = | ` |
+-----------|   |   |   |     |   |   |   |-----------+
```

### SYM

I wanted to have a dedicated symbol row just in case. I'm still testing this
layout. This layer also has a toggle to access the Bluetooth control layer.

```text
+------------------------+     +-----------------------+
|BLT |   |   |   |   |   |     |   |   |   |   |   |   |
| ~  | ! | @ | # | $ | % |     | ^ | & | * | ( | ) |"|"|
|CAPS|   |   |   |   |   |     |   |   |   |   |   |   |
+------------|   |   |   |     |   |   |   |-----------+
```

### BLT

This layer is just to manage my BT connections. `BASE` will take you back to the
base layer.

```text
+--------------------------+     +-----------------------+
|     |   |   |   |   |BASE|     |   |   |   |   |   |   |
|BTCLR|BT1|BT2|BT3|BT4|BT5 |     |   |   |   |   |   |   |
|     |   |   |   |   |    |     |   |   |   |   |   |   |
+-------------|   |   |    |     |   |   |   |-----------+
```