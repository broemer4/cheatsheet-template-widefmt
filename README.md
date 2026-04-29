# Cheatsheet / Notes Template

A minimal A4 landscape multi-column document template.

## Files

| Path | Description |
|------|-------------|
| `./src/_preamble.tex` | packages, geometry, headers |
| `./src/index.tex` | main content - edit this |
| `./src/postemble.tex` | document closing |

## Build

Install Tectonic [^fn1], then run:

```sh
tectonic -X build # --open if you want to directly open using the default reader
```

Output is generated at `./build/default/default.pdf`.

***

## References 

- [\[1\]: https://tectonic-typesetting.github.io/](https://tectonic-typesetting.github.io/)
