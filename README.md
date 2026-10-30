# Awesome Alternatives in Rust with stars

[![github workflow status](https://img.shields.io/github/actions/workflow/status/TaKO8Ki/awesome-alternatives-in-rust/ci.yml?branch=main)](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/actions)

A curated list of replacements for existing software written in Rust.

If you want to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

I renamed the repository to "Awesome Alternatives in Rust". The original name was "Awesome Rewrite It In Rust". For more details, please refer to [this issue](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/issues/29).

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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,518 | 🐛 206 | 🌐 Go | 📅 2026-10-30

* [youki](https://github.com/youki-dev/youki) ⭐ 7,663 | 🐛 182 | 🌐 Rust | 📅 2026-10-29 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,638 | 🐛 0 | 🌐 C | 📅 2026-10-30

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,688 | 🐛 57 | 🌐 Rust | 📅 2026-10-26 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,172 | 🐛 57 | 🌐 C++ | 📅 2026-10-28

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 431 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,417 | 🐛 6,193 | 🌐 Java | 📅 2026-10-30

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,751 | 🐛 848 | 🌐 Rust | 📅 2026-10-30 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,580 | 🐛 991 | 🌐 Java | 📅 2026-10-30

* [drill](https://github.com/fcsonline/drill) ⭐ 2,312 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,370 | 🐛 159 | 🌐 Rust | 📅 2026-10-24 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,749 | 🐛 1,441 | 🌐 Rust | 📅 2026-10-30 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,659 | 🐛 60 | 🌐 Rust | 📅 2026-09-23 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,980 | 🐛 578 | 🌐 Rust | 📅 2026-10-29 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,636 | 🐛 26 | 🌐 Perl | 📅 2026-10-26

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,030 | 🐛 253 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,819 | 🐛 0 | 🌐 C | 📅 2026-10-30

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,805 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 932 | 🐛 17 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,291 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,611 | 🐛 496 | 🌐 Rust | 📅 2026-10-28 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,113 | 🐛 287 | 🌐 Rust | 📅 2026-10-30 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,692 | 🐛 78 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,564 | 🐛 9 | 🌐 Rust | 📅 2026-10-29 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,399 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,908 | 🐛 209 | 🌐 Rust | 📅 2026-10-30 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 83,867 | 🐛 337 | 🌐 Go | 📅 2026-10-29

* [skim](https://github.com/skim-rs/skim) ⭐ 7,001 | 🐛 6 | 🌐 Rust | 📅 2026-10-27 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,346 | 🐛 15 | 🌐 C | 📅 2026-10-30

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,313 | 🐛 1,450 | 🌐 Rust | 📅 2026-10-30 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,300 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,684 | 🐛 357 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,156 | 🐛 39 | 🌐 Rust | 📅 2026-10-29 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,716 | 🐛 476 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,285 | 🐛 217 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,266 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,713 | 🐛 389 | 🌐 Shell | 📅 2026-10-28

* [mise](https://github.com/jdx/mise) ⭐ 35,569 | 🐛 12 | 🌐 Rust | 📅 2026-10-30 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,247 | 🐛 256 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,033 | 🐛 709 | 🌐 C | 📅 2026-10-26

* [broot](https://github.com/Canop/broot) ⭐ 13,117 | 🐛 106 | 🌐 Rust | 📅 2026-10-20 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,214 | 🐛 43 | 🌐 Rust | 📅 2026-10-27 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,739 | 🐛 19 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 603 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,736 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,407 | 🐛 86 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,048 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,184 | 🐛 68 | 🌐 Rust | 📅 2026-10-12 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,087 | 🐛 293 | 🌐 Markdown | 📅 2026-10-30

* [navi](https://github.com/denisidoro/navi) ⭐ 17,812 | 🐛 130 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,636 | 🐛 17 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,302 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,142 | 🐛 105 | 🌐 Rust | 📅 2026-10-30 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,065 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,812 | 🐛 221 | 🌐 Go | 📅 2026-10-28

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,059 | 🐛 167 | 🌐 Rust | 📅 2026-10-28 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,601 | 🐛 131 | 🌐 Shell | 📅 2026-10-26

* [starship](https://github.com/starship/starship) ⭐ 60,518 | 🐛 1,061 | 🌐 Rust | 📅 2026-10-30 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,085 | 🐛 344 | 🌐 Rust | 📅 2026-10-26 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,400 | 🐛 1,942 | 🌐 Rust | 📅 2026-10-26 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,073 | 🐛 33 | 🌐 C | 📅 2026-10-30

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,897 | 🐛 1,933 | 🌐 Rust | 📅 2026-10-30 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,738 | 🐛 1,765 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,135 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,574 | 🐛 212 | 🌐 Rust | 📅 2026-10-27 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,934 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,984 | 🐛 421 | 🌐 C | 📅 2026-10-25

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,689 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,540 | 🐛 1,063 | 🌐 Go | 📅 2026-10-30

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,611 | 🐛 355 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,658 | 🐛 121 | 🌐 Rust | 📅 2026-10-30 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,198 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,489 | 🐛 173 | 🌐 Rust | 📅 2026-10-27 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,684 | 🐛 5,221 | 🌐 Go | 📅 2026-10-30

* [SWC](https://github.com/swc-project/swc) ⭐ 34,205 | 🐛 409 | 🌐 Rust | 📅 2026-10-30 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,601 | 🐛 126 | 🌐 JavaScript | 📅 2026-10-30

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,728 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,585 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,833 | 🐛 24 | 🌐 Python | 📅 2026-10-28

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 50,337 | 🐛 2,249 | 🌐 Rust | 📅 2026-10-30 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,381 | 🐛 1,471 | 🌐 JavaScript | 📅 2026-10-30

* [dprint](https://github.com/dprint/dprint) ⭐ 4,120 | 🐛 35 | 🌐 Rust | 📅 2026-10-30 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,261 | 🐛 1,089 | 🌐 Haskell | 📅 2026-10-26

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,807 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,115 | 🐛 1,293 | 🌐 JavaScript | 📅 2026-10-30

* [Deno](https://github.com/denoland/deno) ⭐ 108,773 | 🐛 1,661 | 🌐 Rust | 📅 2026-10-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,716 | 🐛 9,240 | 🌐 Python | 📅 2026-10-30

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,438 | 🐛 300 | 🌐 Rust | 📅 2026-10-30 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,283 | 🐛 54 | 🌐 JavaScript | 📅 2026-10-23

* [mrml](https://github.com/jdrouet/mrml) ⭐ 512 | 🐛 32 | 🌐 HTML | 📅 2026-10-30 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,023 | 🐛 17,857 | 🌐 Python | 📅 2026-10-30

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,513 | 🐛 280 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,648 | 🐛 909 | 🌐 Java | 📅 2026-10-27

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,535 | 🐛 14 | 🌐 Rust | 📅 2026-10-30 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,600 | 🐛 2,729 | 🌐 Java | 📅 2026-10-30

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,366 | 🐛 498 | 🌐 Rust | 📅 2026-10-30 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-30._
