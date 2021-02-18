# unixtime

A small utility to print the current unix-time on STDOUT.

## Motivation

Somethimes I need the current unix-time for interacting with APIs and other stuff. But I never remember the correct command for it (is's `date +%s`). I mostly end up googling the current unix-time..

Late at night, I quickly built this tool. Maybe someone is having the same issue.

## Installation

Installation requires the Rust-Toolchain. Then install it from source by executing:
```bash
cargo install --git https://github.com/schoenenberg/unixtime --branch main
```
