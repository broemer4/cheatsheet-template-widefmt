# Cheatsheet / Notes Template

A minimal A4 landscape multi-column document template.

***

## Files

| Path | Description |
|------|-------------|
| `./src/_preamble.tex` | Packages, geometry, headers |
| `./src/index.tex` | Main content — edit this |
| `./src/postemble.tex` | Document closing |

## Build

Install [Tectonic](https://tectonic-typesetting.github.io/), then run:

```sh
tectonic -X build
```

Output is generated at `./build/default/default.pdf`.
