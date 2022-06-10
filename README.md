# @

> instant alpine shells

@ (atsi, "at-sign") is a tool for instantly provisioning interactive Alpine
containers. Think of it a little like
[`nix-shell`](https://nixos.org/manual/nix/stable/command-ref/nix-shell.html)
for Alpine.

## Getting started

Run [`cargo make debug`](https://github.com/sagiegurari/cargo-make) to create
a debug build, or run `cargo make release` to create a release build. Builds
are emitted to `target/{debug,release}/@`.

You may need to run `cargo install cargo-make` first.

## Basic commands

- `@ run`: Get an Alpine container running. Check `@ run --help` for all
           options.
- `@ ps`: Show all currently-running Alpine containers.
