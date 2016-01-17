# Awesome Vorpal.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of delightful [Vorpal.js](https://github.com/dthree/vorpal)-based projects and extensions. Vorpal is Node's first framework for building immersive CLI applications. 

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

### Projects built with Vorpal

- [wat](https://github.com/dthree/wat) - Community-built syntax cheat-sheets for every language, platform and library.
- [vantage.js](https://github.com/dthree/vantage) - Vorpal with wings: `CLI` + `SSH` + `REPL` for your live Node app.
- [metronome](https://github.com/AljoschaMeyer/metronome-cli) - Turns your CLI into a metronome, adjustable on the fly.
- [itunes remote](https://github.com/mischah/itunes-remote/) - Control iTunes via the CLI.
- [fastack](https://github.com/fastack/cli) - A zero-configuration development tool that makes developing client-side-only apps easy

### Community / Tutorials

- [Tutorial by Brian Rinaldi] (http://developer.telerik.com/featured/creating-node-js-command-line-utilities-improve-workflow/)

### Vorpal extensions

Vorpal supports community extensions, which add to the functionality of Vorpal programmatically or on the fly.

##### POSIX implementations

- [less](https://github.com/vorpaljs/vorpal-less) - Implementation of the `less` command.
- [grep](https://github.com/vorpaljs/vorpal-grep) - Implementation of the `grep` command.

##### REPL

- [repl](https://github.com/vorpaljs/vorpal-repl) - Drops your CLI into a REPL within your app's context.

##### Realtime

- [use](https://github.com/vorpaljs/vorpal-use) - Import Vorpal extensions live: while your app is running.

##### Misc

- [tour](https://github.com/vorpaljs/vorpal-tour) - Build an interactive tour for your Vorpal app.
- [hacker-news](https://github.com/vorpaljs/vorpal-hacker-news) - Pulls the top trending items from Hacker News.

##### Vorpal development tools
- [watch](https://github.com/vorpaljs/vorpal-watch) - Updates your live Vorpal extensions in realtime.
- [setorprint](https://github.com/AljoschaMeyer/vorpal-setorprint) - Quickly generate commands which either set or print a parameter. Think instant getters/setters for the console.
- [log](https://github.com/AljoschaMeyer/vorpal-log) - Logging utility for Vorpal - comes with logging levels, formatters, and is extensible.

### Vantage-only extensions

[Vantage.js](https://github.com/dthree/vantage) extends Vorpal, giving it client / server functionality. While Vantage supports all Vorpal extensions, the following extensions are only applicable to Vantage.

- [Basic Authentication](https://github.com/vantagejs/vantage-auth-basic) - Basic authentication packaged with Vantage. Mirrors SSH authentication, however with credentials declared in the Node instance as opposed to PAM authentication.

### Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

### License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [David Caccavella](https://github.com/dthree) has waived all copyright and related or neighboring rights to this work.
