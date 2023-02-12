![workflow](https://github.com/solenberg/zmk-firmware-corne/actions/workflows/build.yaml/badge.svg)

# Corne Keyboard Layout

The key map is subject to change as I discover my needs but I will try to keep 
this updated. 

### BASE

[NAV](#nav) is a cursor navigation and media control layer  
[NUM](#num) is a number and function key layer  
[SYM](#sym) is a symbol layer accessed by holding both `NAV` and `NUM`. It also 
has a toggle to go to [BLT](#blt) my Bluetooth control layer.

```
+----+---+---+---+---+---+     +---+---+---+---+---+---+
|ESC | Q | W | E | R | T |     | Y | U | I | O | P |DEL|
+----+---+---+---+---+---+     +---+---+---+---+---+---+
|TAB | A | S | D | F | G |     | H | J | K | L | ; | ' |
+----+---+---+---+---+---+     +---+---+---+---+---+---+
|CTRL| Z | X | C | V | B |     | N | M | , | . | / |GUI|
+----+---+---+---+---+---+     +---+---+---+---+---+---+
             |ALT|NUM|SHF|     |SHF|NAV|BKS|
             +---+---|ENT|     |SPC|---+---+ 
                   \\======SYM======//
```

### NAV

```
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|PRV|HME|BCK|UP |FWD|END|     |   |   |   |   |   |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|PP |PGU|LFT|DN |RGT|PGD|     |   |   |   |   |   |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|NXT|   |CUT|CPY|PST|   |     |   |   |   |   |   |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
            |   |   |   |     |   |   |   |
            +---+---+---+     +---+---+---+
```

### NUM

```
+---+---+---+---+---+---+     +---+---+---+---+---+---+
| ` |   |F7 |F8 |F9 |F10|     | ( | 7 | 8 | 9 | \ | ) |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|   |   |F4 |F5 |F6 |F11|     | [ | 4 | 5 | 6 | - | ] |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|   |   |F1 |F2 |F3 |F12|     | 0 | 1 | 2 | 3 | = |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
            |   |   |   |     |   |   |   |
            +---+---+---+     +---+---+---+
```

### SYM

```
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|   |   |   |   |   |BLT|     |   |   |   |   |   |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
| ~ | ! | @ | # | $ | % |     | ^ | & | * | ( | ) | | |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
|   |   |   |   |   |CAP|     |   |   |   |   |   |   |
+---+---+---+---+---+---+     +---+---+---+---+---+---+
            |   |   |   |     |   |   |   |
            +---+---+---+     +---+---+---+
```

### BLT

[BASE](#base) will take you back to the base layer.

```
+-----+---+---+---+---+----+     +---+---+---+---+---+---+
|     |   |   |   |   |BASE|     |   |   |   |   |   |   |
+-----+---+---+---+---+----+     +---+---+---+---+---+---+
|BTCLR|BT1|BT2|BT3|BT4|BT5 |     |   |   |   |   |   |   |
+-----+---+---+---+---+----+     +---+---+---+---+---+---+
|     |   |   |   |   |    |     |   |   |   |   |   |   |
+-----+---+---+---+---+----+     +---+---+---+---+---+---+
              |   |   |    |     |   |   |   |
              +---+---+----+     +---+---+---+