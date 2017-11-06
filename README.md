# sexp2mdtbl
S-exp to markdown table format

## Example

### Processed file

```lisp
((me osx linux windows)
 (he linux)
 (she osx windows)
 (they windows linux))
```

### Result

#### Command

```shell
$ sexp2mdtbl < processed_file
```

#### Result in md

| `""` | `osx` | `linux` | `windows` |
|------|------|------|------|
| `me` | need | need | need |
| `he` |      | need |      |
| `she` | need |      | need |
| `they` |      | need | need |

## Installation

Roswell is recommended.

```shell
$ ros install windymelt/sexp2mdtbl
```
