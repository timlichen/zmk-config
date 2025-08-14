# Rae Dux QWERTY Keymap

34-key split keyboard QWERTY layout with ZMK firmware. Windows-optimized with 4-layer system.

## Layers

### Layer 0: Base QWERTY
```
╭─────────────────────────╮ ╭─────────────────────────╮
│  Q    W    E    R    T  │ │  Y    U    I    O    P  │
│  A    S    D    F    G  │ │  H    J    K    L    ;  │
│  Z    X    C    V    B  │ │  N    M    ,    .    /  │
╰──────╮ Tab  Spc  Esc    │ │  Del  Bsp  Ret   ╭──────╯
       ╰──────────────────╯ ╰──────────────────╯
```

**Home Row Mods:** A(Alt) S(Win) D(Shift) F(Ctrl) | J(Ctrl) K(Shift) L(Win) ;(Alt)

**Thumb Keys:** 
- Tab/Nav | Space/Sym | Esc/Num | Del/Num | Bsp/Sym | Enter/Nav

### Layer 1: Symbols
```
╭─────────────────────────╮ ╭─────────────────────────╮
│  !    @    #    $    %  │ │  ^    &    *    (    )  │
│  `    -    =    [    ]  │ │  \    '    "    {    }  │
│  ~    _    +    <    >  │ │  |    :    ?    ,    .  │
╰──────╮ Tab  ███  Esc    │ │  Del  ███  Ret  ╭───────╯
       ╰──────────────────╯ ╰─────────────────╯
```

### Layer 2: Numbers & Functions
```
╭─────────────────────────╮ ╭─────────────────────────╮
│  F1   F2   F3   F4   F5 │ │  F6   F7   F8   F9  F10 │
│  1    2    3    4    5  │ │  6    7    8    9    0  │
│ F11  F12   ▓    ▓    ▓  │ │  -    =    [    ]    \  │
╰──────╮ Tab  Spc  ███    │ │  ███  Bsp  Ret   ╭──────╯
       ╰──────────────────╯ ╰──────────────────╯
```

### Layer 3: Navigation & Bluetooth
```
╭─────────────────────────╮ ╭──────────────────────────╮
│  ▓    ▓    ▓    ▓  BTCLR│ │ BTPRV BTNXT  ▓    ▓    ▓ │
│ Alt  Win  Shft Ctrl  ▓  │ │  ▓    ←    ↓    ↑    →   │
│  ▓   Cut  Copy Paste ▓  │ │  ▓   Home PgDn PgUp  End │
╰──────╮ ███  Spc  Esc    │ │  Del  Bsp     ███ ╭──────╯
       ╰──────────────────╯ ╰───────────────────╯
```

## Combos

| Keys | Output | Keys | Output |
|------|--------|------|--------|
| W+E | ` | U+I | ; |
| X+C | = | ,+. | ' |
| F+G | Caps Word | J+K | Caps Word |
| Spc+Bsp | - | Esc+Del | _ |

## Key Features

**Home Row Mods:** Hold letter keys for modifiers (200ms timing)
**Positional Hold-Tap:** Prevents accidental mods on same hand
**Sticky Keys:** On nav layer - tap to stick modifier for next key
**Caps Word:** Auto-capitalize until space/punctuation
**Windows Clipboard:** Cut(Ctrl+X), Copy(Ctrl+C), Paste(Ctrl+V)

## Bluetooth

- **BTCLR:** Clear all pairings
- **BTPRV/BTNXT:** Switch between 5 paired devices

## Technical

**Key Positions:**
```
╭────────────────────╮ ╭────────────────────╮
│  0   1   2   3   4 │ │  5   6   7   8   9 │
│ 10  11  12  13  14 │ │ 15  16  17  18  19 │
│ 20  21  22  23  24 │ │ 25  26  27  28  29 │
╰───────╮ 30  31  32 │ │ 33  34  35 ╭───────╯
        ╰────────────╯ ╰────────────╯
```

**Timing:** 200ms hold-tap, 200ms quick-tap, 60ms combo timeout
