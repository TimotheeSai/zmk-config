# Keymap

[Generator](https://nickcoutsos.github.io/keymap-editor/)

# Debug

## Display

- Ensure external power is on: `EP_ON`
- Press reset button

# Local

## Setup

https://zmk.dev/docs/development/setup

## Build

```sh
west build -b nice_nano -- -DSHIELD=lily58_left -DZMK_CONFIG="$HOME/Code/zmk-config"
west build -b nice_nano -- -DSHIELD=lily58_right -DZMK_CONFIG="$HOME/Code/zmk-config"
```
