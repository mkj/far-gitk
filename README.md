# far-gitk

Runs [gitk](https://git-scm.com/docs/gitk) on a remote host over SSH.

## Installation

```
git clone https://github.com/mkj/far-gitk  ~/programs/far-gitk
ln -s ~/programs/far-gitk ~/bin/far-gitk
```

(`far-gitk` puts the shell script `git` wrapper in a new `$PATH`, so
needs its own directory).

## TODO

Maybe give `gitk` its own `--git` argument, make `far-gitk` obselete.

## License

Zero-Clause BSD
