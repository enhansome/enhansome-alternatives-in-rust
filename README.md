# Awesome Alternatives in Rust with stars

[![github workflow status](https://img.shields.io/github/actions/workflow/status/TaKO8Ki/awesome-alternatives-in-rust/ci.yml?branch=main)](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/actions) ⭐ 4,104 | 🐛 34 | 🌐 Rust | 📅 2026-07-13

A curated list of replacements for existing software written in Rust.

If you want to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

I renamed the repository to "Awesome Alternatives in Rust". The original name was "Awesome Rewrite It In Rust". For more details, please refer to [this issue](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/issues/29) ⭐ 4,104 | 🐛 34 | 🌐 Rust | 📅 2026-07-13.

## Table of contents

* [Applications](#applications)
  * [Container](#container)
  * [Database](#database)
  * [Games](#games)
  * [Observability](#observability)
  * [Performance](#performance)
  * [System tools](#system-tools)
  * [Terminal](#terminal)
  * [Text editors](#text-editors)
  * [Text processing](#text-processing)
  * [Utilities](#utilities)
  * [Web](#web)
* [Development tools](#development-tools)
  * [Command runners](#command-runners)
  * [Compilers](#compilers)
  * [Linters](#linters)
  * [Runtimes](#runtimes)
* [Libraries](#libraries)
  * [Email](#email)
  * [Machine learning](#machine-learning)
  * [Message queues](#message-queues)
  * [Search](#search)

## Applications

### Container

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,399 | 🐛 344 | 🌐 Go | 📅 2026-08-11

* [youki](https://github.com/youki-dev/youki) ⭐ 7,534 | 🐛 143 | 🌐 Rust | 📅 2026-08-12 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,778 | 🐛 0 | 🌐 C | 📅 2026-08-12

* [pgrust](https://github.com/malisper/pgrust) ⭐ 4,366 | 🐛 12 | 🌐 Rust | 📅 2026-08-05 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 16,310 | 🐛 42 | 🌐 C++ | 📅 2026-08-10

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 432 | 🐛 11 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,842 | 🐛 5,988 | 🌐 Java | 📅 2026-08-13

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,491 | 🐛 793 | 🌐 Rust | 📅 2026-08-12 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,502 | 🐛 962 | 🌐 Java | 📅 2026-07-20

* [drill](https://github.com/fcsonline/drill) ⭐ 2,304 | 🐛 38 | 🌐 Rust | 📅 2026-07-29 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,628 | 🐛 135 | 🌐 Rust | 📅 2026-08-10 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,314 | 🐛 34 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,251 | 🐛 1,409 | 🌐 Rust | 📅 2026-08-12 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,656 | 🐛 60 | 🌐 Rust | 📅 2026-05-02 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 913 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 161 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,219 | 🐛 419 | 🌐 Rust | 📅 2026-08-11 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,427 | 🐛 26 | 🌐 Perl | 📅 2026-08-08

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,792 | 🐛 242 | 🌐 Rust | 📅 2026-05-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,765 | 🐛 0 | 🌐 C | 📅 2026-08-12

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,793 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 925 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,261 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 742 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 31,728 | 🐛 424 | 🌐 Rust | 📅 2026-08-02 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,760 | 🐛 289 | 🌐 Rust | 📅 2026-08-12 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,687 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,113 | 🐛 11 | 🌐 Rust | 📅 2026-08-10 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,123 | 🐛 29 | 🌐 Rust | 📅 2026-08-12 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,057 | 🐛 185 | 🌐 Rust | 📅 2026-08-11 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 82,535 | 🐛 327 | 🌐 Go | 📅 2026-08-11

* [skim](https://github.com/skim-rs/skim) ⭐ 6,919 | 🐛 4 | 🌐 Rust | 📅 2026-08-11 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,245 | 🐛 17 | 🌐 C | 📅 2026-08-12

* [coreutils](https://github.com/uutils/coreutils) ⭐ 23,921 | 🐛 1,170 | 🌐 Rust | 📅 2026-08-11 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,254 | 🐛 33 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,416 | 🐛 328 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,014 | 🐛 38 | 🌐 Rust | 📅 2026-07-26 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 22,914 | 🐛 422 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,165 | 🐛 203 | 🌐 Rust | 📅 2026-07-25 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,262 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 94,560 | 🐛 396 | 🌐 Shell | 📅 2026-07-24

* [mise](https://github.com/jdx/mise) ⭐ 32,336 | 🐛 65 | 🌐 Rust | 📅 2026-08-13 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 26,547 | 🐛 239 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 948 | 🐛 685 | 🌐 C | 📅 2026-08-01

* [broot](https://github.com/Canop/broot) ⭐ 12,889 | 🐛 251 | 🌐 Rust | 📅 2026-08-12 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,131 | 🐛 37 | 🌐 Rust | 📅 2026-08-10 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,731 | 🐛 15 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 594 | 🐛 12 | 🌐 Rust | 📅 2026-03-21 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,728 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,295 | 🐛 74 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,044 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,462 | 🐛 16 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,650 | 🐛 93 | 🌐 Rust | 📅 2026-04-30 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 63,391 | 🐛 320 | 🌐 Markdown | 📅 2026-08-12

* [navi](https://github.com/denisidoro/navi) ⭐ 17,423 | 🐛 108 | 🌐 Rust | 📅 2026-07-28 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,415 | 🐛 16 | 🌐 Rust | 📅 2026-08-12 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,271 | 🐛 5 | 🌐 Rust | 📅 2026-07-26 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,881 | 🐛 108 | 🌐 Rust | 📅 2026-08-13 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,044 | 🐛 41 | 🌐 Rust | 📅 2026-07-13 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 266 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 570 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,679 | 🐛 206 | 🌐 Go | 📅 2026-08-12

* [paru](https://github.com/Morganamilo/paru) ⭐ 8,938 | 🐛 202 | 🌐 Rust | 📅 2026-01-09 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,557 | 🐛 128 | 🌐 Shell | 📅 2026-08-05

* [starship](https://github.com/starship/starship) ⭐ 59,375 | 🐛 1,033 | 🌐 Rust | 📅 2026-08-12 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 65,341 | 🐛 338 | 🌐 Rust | 📅 2026-08-03 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 28,325 | 🐛 1,805 | 🌐 Rust | 📅 2026-08-12 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 48,581 | 🐛 44 | 🌐 C | 📅 2026-08-12

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 34,864 | 🐛 1,856 | 🌐 Rust | 📅 2026-08-12 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 45,808 | 🐛 1,605 | 🌐 Rust | 📅 2026-08-11 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,119 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,266 | 🐛 175 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,923 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,441 | 🐛 472 | 🌐 C | 📅 2026-08-12

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,674 | 🐛 2 | 🌐 Rust | 📅 2026-03-18 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,274 | 🐛 1,017 | 🌐 Go | 📅 2026-08-12

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,381 | 🐛 330 | 🌐 Rust | 📅 2026-08-04 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 396 | 🐛 6 | 🌐 Rust | 📅 2026-02-17 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,548 | 🐛 120 | 🌐 Rust | 📅 2026-08-12 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,202 | 🐛 197 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 35,276 | 🐛 168 | 🌐 Rust | 📅 2026-08-12 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 110,162 | 🐛 5,082 | 🌐 TypeScript | 📅 2026-08-13

* [SWC](https://github.com/swc-project/swc) ⭐ 34,180 | 🐛 416 | 🌐 Rust | 📅 2026-08-12 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,456 | 🐛 127 | 🌐 JavaScript | 📅 2026-08-12

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,731 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,585 | 🐛 167 | 🌐 Rust | 📅 2026-07-23 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,812 | 🐛 23 | 🌐 Python | 📅 2026-07-14

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,172 | 🐛 2,095 | 🌐 Rust | 📅 2026-08-13 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,195 | 🐛 1,441 | 🌐 JavaScript | 📅 2026-08-13

* [dprint](https://github.com/dprint/dprint) ⭐ 4,039 | 🐛 83 | 🌐 Rust | 📅 2026-08-06 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 39,858 | 🐛 1,135 | 🌐 Haskell | 📅 2026-08-04

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,797 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 118,908 | 🐛 1,498 | 🌐 JavaScript | 📅 2026-08-12

* [Deno](https://github.com/denoland/deno) ⭐ 108,250 | 🐛 1,482 | 🌐 Rust | 📅 2026-08-13 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 74,301 | 🐛 9,503 | 🌐 Python | 📅 2026-08-13

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,276 | 🐛 405 | 🌐 Rust | 📅 2026-08-12 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,197 | 🐛 67 | 🌐 JavaScript | 📅 2026-08-12

* [mrml](https://github.com/jdrouet/mrml) ⭐ 504 | 🐛 21 | 🌐 HTML | 📅 2026-08-11 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 102,352 | 🐛 17,143 | 🌐 Python | 📅 2026-08-13

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,473 | 🐛 245 | 🌐 Rust | 📅 2026-07-17 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,559 | 🐛 557 | 🌐 Java | 📅 2026-08-13

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,503 | 🐛 23 | 🌐 Rust | 📅 2026-08-13 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,539 | 🐛 2,644 | 🌐 Java | 📅 2026-08-12

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 15,682 | 🐛 440 | 🌐 Rust | 📅 2026-08-12 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
