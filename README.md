# Raspberry Pico W Template


## Usage

```sh
cargo generate --git https://github.com/datenzauberer/picow-embassy-template \
    --define wifi_enabled=true
```

`wifi_enabled=true` creates a project with a wifi based tcp server.

`wifi_enabled=false` creates a project with a blinky.

## Preconditions

Install `cargo-generate` with

```sh
cargo install cargo-generate
```

