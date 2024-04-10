# Melange for React Developers

A simple project template using [Melange](https://github.com/melange-re/melange)
with [opam](https://opam.ocaml.org/).

## Quick Start

```shell
npm run init

# In separate terminals:
npm run watch
npm run serve
```

### React

React support is provided by
[`reason-react`](https://github.com/reasonml/reason-react/). The entry
point of the sample React app is [`Index.re`](Index.re).

## Commands

All the build commands are defined in the `scripts` field of `package.json`.
This is completely optional, and other tools like `make` could be used.

You can see all available commands by running `npm run`. There are explanations
of each command in the `scriptsComments` field of the `package.json` file. Here
are a few of the most useful ones:

- `npm run init`: set up opam local switch and download OCaml, Melange and
JavaScript dependencies
- `npm run install:npm-opam`: install JavaScript, OCaml, and Melange
  dependencies
- `npm run watch`: watch the filesystem and have Melange rebuild on every
change
- `npm run serve`: serve the application with a local HTTP server
