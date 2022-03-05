# Pi Build System

Yocto build system for Raspberry Pis


## Instructions for use

* Ensure all submodules are cloned

```bash
$ git submodule update --init --recursive
```

* In the base directory run

```bash
$ source poky/oe-init-build-env
```

* Build your desired image

```bash
$ bitbake core-image-base
```
