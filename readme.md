age
=====

Calculate your age in command line.

install
-------

1. Run install script

```shell
wget -qO- https://raw.githubusercontent.com/dariubs/age/master/install.sh | bash
```

2. Append `age` to PATH. `~/.bashrc` for bash and `~/.zshrc` for zsh

```shell
export PATH="$HOME/.age:$PATH"
```


usage
-----

1. set your birthdate in `yyyymmdd` format

```shell
age -b 19930807
```

2. get your age

```shell
age
```

:)

