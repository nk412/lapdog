# 🐕 lapdog

A loyal little CLI stopwatch. Sits. Stays. Times.

## Run

```
./lapdog
```

## Keys

| key     | does              |
| ------- | ----------------- |
| `space` | start / pause     |
| `l`     | record lap        |
| `r`     | reset             |
| `s`     | next digit style  |
| `q`     | quit              |

Cycling styles with `s` doesn't touch the clock — lapdog keeps running.

## Styles

Press `s` to cycle. Four flavors of big chunky digits:

### `block` — tmux clock vibes

```
█████     █       █████ █████       █   █ █████
█   █     █   █       █     █   █   █   █ █
█   █     █       █████ █████       █████ █████
█   █     █   █   █         █   █       █     █
█████     █       █████ █████           █ █████
```

### `rounded` — softer corners, friendlier dog

```
╭───╮     │       ╭───╮ ╭───╮       │   │ ╭───╴
│   │     │   •       │     │   •   │   │ │
│   │     │       ╭───╯ ╶───┤       ╰───┤ ╰───╮
│   │     │   •   │         │   •       │     │
╰───╯     │       ╰───╴ ╰───╯           │ ╰───╯
```

### `double` — double-line, very serious business

```
╔═══╗     ║       ╔═══╗ ╔═══╗       ║   ║ ╔═══╗
║   ║     ║   ◆       ║     ║   ◆   ║   ║ ║
║   ║     ║       ╔═══╝  ═══╣       ╚═══╣ ╚═══╗
║   ║     ║   ◆   ║         ║   ◆       ║     ║
╚═══╝     ║       ╚═══╝ ╚═══╝           ║ ╚═══╝
```

### `dots` — LED dot-matrix, airport departures board energy

```
●●●●● ····● ····· ●●●●● ●●●●● ····· ●···● ●●●●●
●···● ····● ··●·· ····● ····● ··●·· ●···● ●····
●···● ····● ····· ●●●●● ●●●●● ····· ●●●●● ●●●●●
●···● ····● ··●·· ●···· ····● ··●·· ····● ····●
●●●●● ····● ····· ●●●●● ●●●●● ····· ····● ●●●●●
```

## Requirements

Python 3. A terminal. A dog (optional).
