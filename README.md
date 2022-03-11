# prismcheck

## About

A simple terminal color checker adapted from [colortest](https://github.com/pablopunk/colortest)
and distributed with Deno.

## How it works

Embedded into the source code is a color display shell [script](https://tldp.org/HOWTO/Bash-Prompt-HOWTO/x329.html).
On your machine, it's simply piped into a Bash process and executed.

## Usage

### Run with [`land`](https://github.com/ije/land)

```console
land prismcheck
```

### Install and run

Install `prismcheck`:

```console
deno install --allow-run -f --import-map https://deno.land/x/prismcheck/import_map.json -n prismcheck https://deno.land/x/prismcheck/cli.ts
```

Run:

```console
prismcheck
```
