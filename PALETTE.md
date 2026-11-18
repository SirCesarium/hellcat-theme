# Palette

Hellcat uses one token vocabulary across its three variants. Values come from the theme files in `themes/`.

- Surfaces stay near-black and carry the variant's hue. Four steps run from `bg.crust` to `bg.overlay`, with raised surfaces getting lighter.
- `accent` covers focus rings, active borders, badges, keywords, and tags. `accent.bright` is for the cursor and language variables.
- Text contrast holds steady across variants: body text sits at about 15:1 against its background, muted text and accents at about 5:1.

## Hellcat

| Token | Hex | Role |
| --- | --- | --- |
| `bg.crust` | `#0d0a09` | Editor and title bar background |
| `bg.base` | `#12100e` | Sidebar, panel, and status bar |
| `bg.surface` | `#171412` | Active tab, menus, notifications |
| `bg.overlay` | `#1a1614` | Inputs and inlay hints |
| `border` | `#241e1b` | Panel, tab, and sidebar borders |
| `selection` | `#583f19` | Editor selection |
| `text` | `#e8e0d8` | Body text and variables |
| `text.secondary` | `#c4bab2` | Activity bar and status bar labels |
| `text.muted` | `#8b7f78` | Inactive tabs and punctuation |
| `text.comment` | `#8a7d78` | Comments |
| `text.gutter` | `#4f4641` | Line numbers |
| `accent` | `#d9564a` | Focus rings, active borders, badges |
| `accent.bright` | `#ff7a5c` | Cursor and language variables |
| `status.error` | `#ff5f56` | Errors and deleted content |
| `status.warning` | `#e2b07a` | Warnings and modified content |
| `status.info` | `#7f9eb0` | Info markers and icons |
| `status.success` | `#8faa6a` | Added and inserted content |
| `syntax.keyword` | `#d9564a` | Keywords and storage, bold |
| `syntax.function` | `#e2b07a` | Functions and methods |
| `syntax.string` | `#d6b98c` | Strings |
| `syntax.number` | `#e39a5c` | Numbers and constants |
| `syntax.type` | `#c4b3a6` | Types, classes, namespaces |
| `syntax.property` | `#e6c9a8` | Properties and object keys |
| `syntax.operator` | `#c98a72` | Operators and macros |
| `syntax.parameter` | `#dcbf9a` | Parameters |
| `syntax.decorator` | `#c9a27a` | Decorators and attributes, italic |
| `ansi.black` | `#3c332e` | Terminal ANSI black |
| `ansi.red` | `#d9564a` | Terminal ANSI red |
| `ansi.green` | `#8faa6a` | Terminal ANSI green |
| `ansi.yellow` | `#e2b07a` | Terminal ANSI yellow |
| `ansi.blue` | `#7f9eb0` | Terminal ANSI blue |
| `ansi.magenta` | `#c0839b` | Terminal ANSI magenta |
| `ansi.cyan` | `#7fa8a0` | Terminal ANSI cyan |
| `ansi.white` | `#d6cfc8` | Terminal ANSI white |
| `ansi.brightBlack` | `#6f6460` | Terminal ANSI bright black |
| `ansi.brightRed` | `#ff7a5c` | Terminal ANSI bright red |
| `ansi.brightGreen` | `#a9c482` | Terminal ANSI bright green |
| `ansi.brightYellow` | `#f0c78e` | Terminal ANSI bright yellow |
| `ansi.brightBlue` | `#9db8c9` | Terminal ANSI bright blue |
| `ansi.brightMagenta` | `#d9a0b4` | Terminal ANSI bright magenta |
| `ansi.brightCyan` | `#9cc4bb` | Terminal ANSI bright cyan |
| `ansi.brightWhite` | `#f2ece4` | Terminal ANSI bright white |

## Hellcat Oxide

| Token | Hex | Role |
| --- | --- | --- |
| `bg.crust` | `#090c0a` | Editor and title bar background |
| `bg.base` | `#0e1210` | Sidebar, panel, and status bar |
| `bg.surface` | `#131714` | Active tab, menus, notifications |
| `bg.overlay` | `#171b17` | Inputs and inlay hints |
| `border` | `#19231e` | Panel, tab, and sidebar borders |
| `selection` | `#1f4b41` | Editor selection |
| `text` | `#dfe4d9` | Body text and variables |
| `text.secondary` | `#b6bfb5` | Activity bar and status bar labels |
| `text.muted` | `#79857a` | Inactive tabs and punctuation |
| `text.comment` | `#768679` | Comments |
| `text.gutter` | `#3f4b42` | Line numbers |
| `accent` | `#cc633d` | Focus rings, active borders, badges |
| `accent.bright` | `#e48c66` | Cursor and language variables |
| `status.error` | `#e37761` | Errors and deleted content |
| `status.warning` | `#dfb09b` | Warnings and modified content |
| `status.info` | `#84a09b` | Info markers and icons |
| `status.success` | `#82ab8f` | Added and inserted content |
| `syntax.keyword` | `#cc633d` | Keywords and storage, bold |
| `syntax.function` | `#dfb09b` | Functions and methods |
| `syntax.string` | `#d9ba7b` | Strings |
| `syntax.number` | `#d1a26c` | Numbers and constants |
| `syntax.type` | `#8bc1b6` | Types, classes, namespaces |
| `syntax.property` | `#ddccb0` | Properties and object keys |
| `syntax.operator` | `#b7936e` | Operators and macros |
| `syntax.parameter` | `#d4c2a9` | Parameters |
| `syntax.decorator` | `#c8a471` | Decorators and attributes, italic |
| `ansi.black` | `#2f382f` | Terminal ANSI black |
| `ansi.red` | `#cc633d` | Terminal ANSI red |
| `ansi.green` | `#7dac8d` | Terminal ANSI green |
| `ansi.yellow` | `#d5b76f` | Terminal ANSI yellow |
| `ansi.blue` | `#79a29c` | Terminal ANSI blue |
| `ansi.magenta` | `#b78c79` | Terminal ANSI magenta |
| `ansi.cyan` | `#79aaa0` | Terminal ANSI cyan |
| `ansi.white` | `#cbd3ca` | Terminal ANSI white |
| `ansi.brightBlack` | `#5e6a60` | Terminal ANSI bright black |
| `ansi.brightRed` | `#e48c66` | Terminal ANSI bright red |
| `ansi.brightGreen` | `#99c6a8` | Terminal ANSI bright green |
| `ansi.brightYellow` | `#e2cc99` | Terminal ANSI bright yellow |
| `ansi.brightBlue` | `#92bdb7` | Terminal ANSI bright blue |
| `ansi.brightMagenta` | `#cea898` | Terminal ANSI bright magenta |
| `ansi.brightCyan` | `#99c5bd` | Terminal ANSI bright cyan |
| `ansi.brightWhite` | `#eaefe5` | Terminal ANSI bright white |

## Hellcat Crimson

| Token | Hex | Role |
| --- | --- | --- |
| `bg.crust` | `#0c0709` | Editor and title bar background |
| `bg.base` | `#120b0e` | Sidebar, panel, and status bar |
| `bg.surface` | `#171014` | Active tab, menus, notifications |
| `bg.overlay` | `#1b1218` | Inputs and inlay hints |
| `border` | `#241820` | Panel, tab, and sidebar borders |
| `selection` | `#702c40` | Editor selection |
| `text` | `#eadeda` | Body text and variables |
| `text.secondary` | `#c5b7bc` | Activity bar and status bar labels |
| `text.muted` | `#8b7d84` | Inactive tabs and punctuation |
| `text.comment` | `#8e797f` | Comments |
| `text.gutter` | `#50444b` | Line numbers |
| `accent` | `#db4d70` | Focus rings, active borders, badges |
| `accent.bright` | `#e98296` | Cursor and language variables |
| `status.error` | `#e3745f` | Errors and deleted content |
| `status.warning` | `#e3aaae` | Warnings and modified content |
| `status.info` | `#899ab6` | Info markers and icons |
| `status.success` | `#84a98a` | Added and inserted content |
| `syntax.keyword` | `#db4d70` | Keywords and storage, bold |
| `syntax.function` | `#e3aaae` | Functions and methods |
| `syntax.string` | `#dcb592` | Strings |
| `syntax.number` | `#d89b8b` | Numbers and constants |
| `syntax.type` | `#c5afbf` | Types, classes, namespaces |
| `syntax.property` | `#dec8be` | Properties and object keys |
| `syntax.operator` | `#bf899b` | Operators and macros |
| `syntax.parameter` | `#d7bcbe` | Parameters |
| `syntax.decorator` | `#c5a279` | Decorators and attributes, italic |
| `ansi.black` | `#442d3c` | Terminal ANSI black |
| `ansi.red` | `#db4d70` | Terminal ANSI red |
| `ansi.green` | `#84a98a` | Terminal ANSI green |
| `ansi.yellow` | `#d2b579` | Terminal ANSI yellow |
| `ansi.blue` | `#9298b3` | Terminal ANSI blue |
| `ansi.magenta` | `#c87e9c` | Terminal ANSI magenta |
| `ansi.cyan` | `#7fa6a6` | Terminal ANSI cyan |
| `ansi.white` | `#d8cccf` | Terminal ANSI white |
| `ansi.brightBlack` | `#736166` | Terminal ANSI bright black |
| `ansi.brightRed` | `#e98296` | Terminal ANSI bright red |
| `ansi.brightGreen` | `#9dc3a3` | Terminal ANSI bright green |
| `ansi.brightYellow` | `#dfca9f` | Terminal ANSI bright yellow |
| `ansi.brightBlue` | `#adb2cc` | Terminal ANSI bright blue |
| `ansi.brightMagenta` | `#da9eb7` | Terminal ANSI bright magenta |
| `ansi.brightCyan` | `#9fc2c2` | Terminal ANSI bright cyan |
| `ansi.brightWhite` | `#f4eae6` | Terminal ANSI bright white |

[Back to README](README.md)
