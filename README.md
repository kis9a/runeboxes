# strbox

display pipe string in string char box

### usage

```
USAGE:
  strbox [options] <resource|data>

OPTIONS:
  -h: help
  -p: padding

EXAMPLE:
  echo string | strbox @
  echo string | strbox -p 3 \$
  cowsay -W 60 padding と runewidth に対応した。漢字、emoji:$(echo -e "\U1F4A9") | ./strbox -p 4 @
```

### inspired

- [GitHub - ascii-boxes/boxes: Command line ASCII boxes unlimited!](https://github.com/ascii-boxes/boxes)

### dev

linter: https://github.com/koalaman/shellcheck  
formatter: https://github.com/mvdan/sh
