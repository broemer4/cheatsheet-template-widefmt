# Cheatsheet / Notes Template

A minimal A4 landscape multi-column document template.

## Files

| Path | Description |
|------|-------------|
| `./src/_preamble.tex` | Packages, geometry, headers |
| `./src/index.tex` | Main content — edit this |
| `./src/postemble.tex` | Document closing |

## Build

Install Tectonic [1], then run:

```sh
tectonic -X build # --open if you want to directly open using the default reader
```

Output is generated at `./build/default/default.pdf`.

***

- [1: https://tectonic-typesetting.github.io/](https://tectonic-typesetting.github.io/)
