# command-ops

> **gmodproj >= 0.4.0**

## Description

A simple library to handle the CLI of your application

## Documentation

Currently missing a more readable form of documentation, although everything under the `src` directory annotated.

## Installation

If wanting to use with a standard Lua platform, download the latest `command-ops.lua` build from [Releases](https://github.com/novacbn/command-ops/releases). And use it as you would any other library.

Alternatively, if using with `gmodproj`. Download the latest `.zip` or `.tar.gz` archive from the [Releases](https://github.com/novacbn/novautils/releases). Extract the contents of `src` directory into your project's `packages` directory under a `novacbn/command-ops` directory.

## Building

```bash
# Clone the repository
git clone https://github.com/novacbn/command-ops

# Move into the project and make the build directory
cd command-ops
mkdir ./dist

# Building the project will produce `./dist/command-ops.lua`
gmodproj build # Or gmodproj build production
```