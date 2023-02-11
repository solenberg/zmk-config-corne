# Corne Keyboard Layout

While I wanted a keyboard with fewer keys, I also juggle not wanting to chord too
often.  This layout is my first draft and I will try to update this as changes
get made.

## Keymap

### Base

For the most part, this is a standard qwerty layout. I am using tap for
space and return, and hold for shift on the innermost thumb keys.

[NAV](#Navigation) is a cursor navigation and media control layer  
[NUM](#Numbers) is a number layer and F# key layer  
[SYM](#Symbols) is a symbol layer accessed by holding both `NAV` and `NUM`

```text
+------------------------+     +-----------------------+
|ESC | Q | W | E | R | T |     | Y | U | I | O | P |DEL|
|TAB | A | S | D | F | G |     | H | J | K | L | ; | ' |
|CTRL| Z | X | C | V | B |     | N | M | , | . | / |GUI|
+------------|ALT|NUM|SHF|     |SHF|NAV|BKS|-----------+
                  || |ENT|     |SPC| ||
                  \\=======SYM=======//
```

### Navigation

I prefer cross keyboard modifiers, so Nav is accessed with the right thumb and 
keys are accessed with the left hand. This is a basic cursor navigation layer
 with music controls.

```text
+-------------------------+     +-----------------------+
|PRV|HME |BCK|UP |FWD|END |     |   |   |   |   |   |   |
|PP |PGUP|LFT|DN |RGT|PGDN|     |   |   |   |   |   |   |
|NXT|    |CUT|CPY|PST|    |     |   |   |   |   |   |   |
+------------|   |   |    |     |   |   |   |-----------+
```


### Numbers

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

### Symbols

I wanted to have a dedicated symbol row just in case.  I'm still testing this 
layout. This Layer also has a toggle to access the Bluetooth control layer.

```text
+------------------------+     +-----------------------+
|BLT |   |   |   |   |   |     |   |   |   |   |   |   |
| ~  | ! | @ | # | $ | % |     | ^ | & | * | ( | ) |"|"|
|CAPS|   |   |   |   |   |     |   |   |   |   |   |   |
+------------|   |   |   |     |   |   |   |-----------+
```

### Bluetooth

This layer is just to manage my BT devices. `BASE` will take you back to the base layer.

```text
+--------------------------+     +-----------------------+
|     |   |   |   |   |BASE|     |   |   |   |   |   |   |
|BTCLR|BT1|BT2|BT3|BT4|BT5 |     |   |   |   |   |   |   |
|     |   |   |   |   |    |     |   |   |   |   |   |   |
+-------------|   |   |    |     |   |   |   |-----------+
```