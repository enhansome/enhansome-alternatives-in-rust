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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,480 | 🐛 270 | 🌐 Go | 📅 2026-10-08

* [youki](https://github.com/youki-dev/youki) ⭐ 7,629 | 🐛 177 | 🌐 Rust | 📅 2026-10-07 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,314 | 🐛 0 | 🌐 C | 📅 2026-10-08

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,243 | 🐛 28 | 🌐 Rust | 📅 2026-09-18 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 16,857 | 🐛 44 | 🌐 C++ | 📅 2026-09-30

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 430 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,217 | 🐛 6,163 | 🌐 Java | 📅 2026-10-08

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,702 | 🐛 826 | 🌐 Rust | 📅 2026-10-08 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,554 | 🐛 978 | 🌐 Java | 📅 2026-10-01

* [drill](https://github.com/fcsonline/drill) ⭐ 2,311 | 🐛 39 | 🌐 Rust | 📅 2026-09-03 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 39,980 | 🐛 148 | 🌐 Rust | 📅 2026-10-03 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,317 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,637 | 🐛 1,472 | 🌐 Rust | 📅 2026-10-08 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,657 | 🐛 60 | 🌐 Rust | 📅 2026-09-23 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 917 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 165 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,709 | 🐛 543 | 🌐 Rust | 📅 2026-10-07 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,585 | 🐛 27 | 🌐 Perl | 📅 2026-09-20

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,986 | 🐛 251 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,804 | 🐛 0 | 🌐 C | 📅 2026-10-08

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,801 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 931 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,286 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,452 | 🐛 466 | 🌐 Rust | 📅 2026-10-08 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,987 | 🐛 287 | 🌐 Rust | 📅 2026-10-07 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,694 | 🐛 78 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,488 | 🐛 13 | 🌐 Rust | 📅 2026-09-16 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,339 | 🐛 0 | 🌐 Rust | 📅 2026-10-05 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,678 | 🐛 201 | 🌐 Rust | 📅 2026-10-07 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 83,454 | 🐛 333 | 🌐 Go | 📅 2026-10-08

* [skim](https://github.com/skim-rs/skim) ⭐ 6,986 | 🐛 7 | 🌐 Rust | 📅 2026-10-05 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,320 | 🐛 14 | 🌐 C | 📅 2026-10-08

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,225 | 🐛 1,198 | 🌐 Rust | 📅 2026-10-08 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,289 | 🐛 39 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,744 | 🐛 345 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,123 | 🐛 38 | 🌐 Rust | 📅 2026-09-05 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,508 | 🐛 464 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,256 | 🐛 211 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,265 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,283 | 🐛 388 | 🌐 Shell | 📅 2026-10-08

* [mise](https://github.com/jdx/mise) ⭐ 34,782 | 🐛 8 | 🌐 Rust | 📅 2026-10-08 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,061 | 🐛 247 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,011 | 🐛 701 | 🌐 C | 📅 2026-10-08

* [broot](https://github.com/Canop/broot) ⭐ 13,058 | 🐛 103 | 🌐 Rust | 📅 2026-10-04 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,195 | 🐛 39 | 🌐 Rust | 📅 2026-10-06 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,735 | 🐛 17 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 656 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 599 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,739 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,385 | 🐛 82 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,045 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 134 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,473 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,994 | 🐛 52 | 🌐 Rust | 📅 2026-10-07 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 63,852 | 🐛 259 | 🌐 Markdown | 📅 2026-10-08

* [navi](https://github.com/denisidoro/navi) ⭐ 17,745 | 🐛 115 | 🌐 Rust | 📅 2026-09-20 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,585 | 🐛 17 | 🌐 Rust | 📅 2026-08-25 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,297 | 🐛 6 | 🌐 Rust | 📅 2026-10-08 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,088 | 🐛 103 | 🌐 Rust | 📅 2026-10-04 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,061 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 265 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,779 | 🐛 209 | 🌐 Go | 📅 2026-10-08

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,016 | 🐛 207 | 🌐 Rust | 📅 2026-10-05 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,583 | 🐛 130 | 🌐 Shell | 📅 2026-09-02

* [starship](https://github.com/starship/starship) ⭐ 60,187 | 🐛 1,062 | 🌐 Rust | 📅 2026-10-08 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 65,916 | 🐛 341 | 🌐 Rust | 📅 2026-10-05 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,164 | 🐛 1,904 | 🌐 Rust | 📅 2026-10-05 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 49,845 | 🐛 32 | 🌐 C | 📅 2026-10-08

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,679 | 🐛 1,925 | 🌐 Rust | 📅 2026-10-08 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,516 | 🐛 1,721 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,130 | 🐛 95 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 68,934 | 🐛 202 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,930 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,766 | 🐛 420 | 🌐 C | 📅 2026-10-08

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,684 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,011 | 🐛 1,051 | 🌐 Go | 📅 2026-10-07

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,554 | 🐛 348 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,617 | 🐛 124 | 🌐 Rust | 📅 2026-10-08 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,200 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,168 | 🐛 173 | 🌐 Rust | 📅 2026-10-02 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,366 | 🐛 5,077 | 🌐 Go | 📅 2026-10-08

* [SWC](https://github.com/swc-project/swc) ⭐ 34,209 | 🐛 396 | 🌐 Rust | 📅 2026-10-08 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,627 | 🐛 126 | 🌐 JavaScript | 📅 2026-10-08

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,727 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,582 | 🐛 168 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,826 | 🐛 25 | 🌐 Python | 📅 2026-10-08

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,937 | 🐛 2,210 | 🌐 Rust | 📅 2026-10-08 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,414 | 🐛 1,475 | 🌐 JavaScript | 📅 2026-10-08

* [dprint](https://github.com/dprint/dprint) ⭐ 4,092 | 🐛 55 | 🌐 Rust | 📅 2026-10-08 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,152 | 🐛 1,095 | 🌐 Haskell | 📅 2026-10-08

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,809 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 122,253 | 🐛 1,185 | 🌐 JavaScript | 📅 2026-10-08

* [Deno](https://github.com/denoland/deno) ⭐ 108,697 | 🐛 1,675 | 🌐 Rust | 📅 2026-10-07 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,562 | 🐛 9,852 | 🌐 Python | 📅 2026-10-08

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,387 | 🐛 294 | 🌐 Rust | 📅 2026-10-08 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,255 | 🐛 49 | 🌐 JavaScript | 📅 2026-10-08

* [mrml](https://github.com/jdrouet/mrml) ⭐ 510 | 🐛 28 | 🌐 HTML | 📅 2026-09-29 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 103,904 | 🐛 17,700 | 🌐 Python | 📅 2026-10-08

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,498 | 🐛 248 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,632 | 🐛 773 | 🌐 Java | 📅 2026-10-08

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,525 | 🐛 44 | 🌐 Rust | 📅 2026-10-08 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,574 | 🐛 2,668 | 🌐 Java | 📅 2026-10-08

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,193 | 🐛 472 | 🌐 Rust | 📅 2026-10-08 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-08._
