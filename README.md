==========
GOACTIVATE
==========

Script to set PATH, GOPATH and shell prompt for your project. Drop this script in your PATH. To activate environment, go in the root directory of the project and type:

```shell
source goactivate
```

This will set PATH to:

```shell
/project/home/bin:$PATH
```

And it will also set GOPATH to:

```shell
/project/home
```

So that dependencies will be installed in your project home directory. Furthermore, the shell prompt is modified so that it will show activated project between brackets.

To deactivate the environment, type:

```shell
deactivate
```

This will restore your previous PATH, GOPATH and shell prompt.

