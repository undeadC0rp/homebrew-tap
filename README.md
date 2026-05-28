# homebrew-tap

Homebrew tap for [The Yips](https://theyips.app) — a golf stats tracker focused on improvement through Strokes Gained methodology.

## Install

```sh
brew tap undeadC0rp/tap
brew install yips
```

## Tools

### `yips`

Terminal client for The Yips golf stats tracker. View rounds, analyze performance, and dig into club data — all from the command line.

```sh
yips rounds                        # list your rounds
yips round <id>                    # hole-by-hole scorecard with SG
yips hole <id> <hole>              # shot-by-shot Gantt chart
yips stats                         # aggregate stats across all rounds
yips clubs                         # distance & strokes gained per club
yips holes <course>                # club selection analysis by hole
yips clubs --json | claude "..."   # pipe to Claude for open-ended analysis
```

Source and full documentation: [undeadC0rp/theyips-cli](https://github.com/undeadC0rp/theyips-cli)
