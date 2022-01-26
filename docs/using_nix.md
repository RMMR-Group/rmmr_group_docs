---
title: Using nix package manager
---

## What is `nix`?

Lots of Dylan's code (and maybe your code too!) uses the `nix` package manager to setup the environment. In theory, this "just works" across both MacOS and Linux systems, and provides complete isolation of your working environment.. You can find info on the `nix` package manager at its website:
[https://nixos.org](https://nixos.org)

## Using `nix` on MacOS
On a MacOS system, you can nust install the nix package manager using the installer on the nix website. In repos that include a `default.nix` file, you can then just run `nix-shell` in order to create a shell with the necessary dependencies.

## Using `nix` on Linux
On a Linux system you can also install the nix package manager. We don't have much experience with this, so happy to have it expanded upon.

## Using `nix` on AWS
You can create a virtual machine on AWS using nixos as it's base system (and thus nix as the package manager). This is somewhat esoteric, so we'll bother fleshing out the details if and when this workflow becomes more important to other folks.
