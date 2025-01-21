# Pacman-dep-graph

[![License](https://img.shields.io/github/license/mal1kc/pacman-dep-graph)](./LICENSE)

this was forked from [here](https://github.com/vincillau/pacman-dep-graph)

`Pacman-dep-graph` can generate the dependency graph of installed pacman packages. When you run pacman-dep-graph, it will describe the dependency graph in `DOT language` and output it to `stdout`.

## Usage

```shell
git clone https://github.com/mal1kc/pacman-dep-graph.git
cd pacman-dep-graph
./pacman-dep-graph > pacman-dep-graph.dot
dot -Tpng pacman-dep-graph.dot -o pacman-dep-graph.png
```

For more infomation about `DOT language`, please visit [https://graphviz.org.](https://graphviz.org/)

## Maintainers

[@mal1kc.](https://github.com/mal1kc)
