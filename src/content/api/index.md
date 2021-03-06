---
title: Introduction
sort: 1
---

A variety of interfaces are available to customize the compilation process. Some features overlap between interfaces, e.g. a configuration option may be available via a CLI flag, while others exist only through a single interface. The following high-level information should get you started.


## CLI

The Command Line Interface (CLI) to configure and interact with your build. It is especially useful in the case of early prototyping and profiling. For the most part, the CLI is simply used to kick off the process using a configuration file and a few flags (e.g. `--env`).

[Learn more!](/api/cli)


## Module

When processing modules with webpack, it is important to understand the different module syntaxes -- specifically the [methods](/api/module-methods) and [variables](/api/module-variables) -- that are supported.

[Learn more!](/api/module-methods)


## Node

While most users can get away with just using the CLI along with a configuration file, more fine-grained control of the compilation can be achieved via the Node interface. This includes passing multiple configurations, programatically running or watching, and collecting stats.

[Learn more!](/api/node)


## Loaders

Loaders are transformations that are applied to the source code of a module. They are written as functions that accept source code as a parameter and return a new version of that code with tranformations applied.

[Learn more!](/api/loaders)


## Plugins

The plugin interface provided by webpack allows users to tap directly into the compilation process. Plugins can register handlers on lifecycle hooks that run at different points in the compilation process. When each hook is executed, the plugin will have full access to the current state of the compilation.

[Learn more!](/api/plugins)
