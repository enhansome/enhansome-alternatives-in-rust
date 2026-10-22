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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,502 | 🐛 204 | 🌐 Go | 📅 2026-10-22

* [youki](https://github.com/youki-dev/youki) ⭐ 7,644 | 🐛 182 | 🌐 Rust | 📅 2026-10-22 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,507 | 🐛 0 | 🌐 C | 📅 2026-10-22

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,309 | 🐛 33 | 🌐 Rust | 📅 2026-10-22 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,048 | 🐛 59 | 🌐 C++ | 📅 2026-10-17

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 431 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,338 | 🐛 6,181 | 🌐 Java | 📅 2026-10-22

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,735 | 🐛 842 | 🌐 Rust | 📅 2026-10-22 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,573 | 🐛 982 | 🌐 Java | 📅 2026-10-01

* [drill](https://github.com/fcsonline/drill) ⭐ 2,311 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,245 | 🐛 168 | 🌐 Rust | 📅 2026-10-18 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,714 | 🐛 1,429 | 🌐 Rust | 📅 2026-10-22 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,658 | 🐛 60 | 🌐 Rust | 📅 2026-09-23 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 165 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,892 | 🐛 568 | 🌐 Rust | 📅 2026-10-20 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,615 | 🐛 29 | 🌐 Perl | 📅 2026-10-22

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,010 | 🐛 251 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,813 | 🐛 0 | 🌐 C | 📅 2026-10-22

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,801 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 929 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,287 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,557 | 🐛 491 | 🌐 Rust | 📅 2026-10-17 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,048 | 🐛 282 | 🌐 Rust | 📅 2026-10-16 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,693 | 🐛 78 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,534 | 🐛 16 | 🌐 Rust | 📅 2026-09-16 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,374 | 🐛 0 | 🌐 Rust | 📅 2026-10-17 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,837 | 🐛 216 | 🌐 Rust | 📅 2026-10-22 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 83,724 | 🐛 333 | 🌐 Go | 📅 2026-10-21

* [skim](https://github.com/skim-rs/skim) ⭐ 7,000 | 🐛 7 | 🌐 Rust | 📅 2026-10-20 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,333 | 🐛 16 | 🌐 C | 📅 2026-10-22

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,278 | 🐛 1,270 | 🌐 Rust | 📅 2026-10-22 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,297 | 🐛 41 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,670 | 🐛 355 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,141 | 🐛 39 | 🌐 Rust | 📅 2026-10-21 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,631 | 🐛 471 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,262 | 🐛 214 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,266 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,619 | 🐛 387 | 🌐 Shell | 📅 2026-10-10

* [mise](https://github.com/jdx/mise) ⭐ 35,270 | 🐛 28 | 🌐 Rust | 📅 2026-10-22 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,165 | 🐛 251 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,025 | 🐛 704 | 🌐 C | 📅 2026-10-22

* [broot](https://github.com/Canop/broot) ⭐ 13,090 | 🐛 106 | 🌐 Rust | 📅 2026-10-20 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,200 | 🐛 41 | 🌐 Rust | 📅 2026-10-20 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,741 | 🐛 17 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 656 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 600 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,735 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,397 | 🐛 85 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,045 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 134 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,472 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,139 | 🐛 62 | 🌐 Rust | 📅 2026-10-12 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,014 | 🐛 293 | 🌐 Markdown | 📅 2026-10-22

* [navi](https://github.com/denisidoro/navi) ⭐ 17,790 | 🐛 127 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,614 | 🐛 19 | 🌐 Rust | 📅 2026-08-25 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,298 | 🐛 5 | 🌐 Rust | 📅 2026-10-15 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,117 | 🐛 107 | 🌐 Rust | 📅 2026-10-04 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,065 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,792 | 🐛 212 | 🌐 Go | 📅 2026-10-19

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,041 | 🐛 209 | 🌐 Rust | 📅 2026-10-05 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,599 | 🐛 129 | 🌐 Shell | 📅 2026-10-21

* [starship](https://github.com/starship/starship) ⭐ 60,395 | 🐛 1,052 | 🌐 Rust | 📅 2026-10-22 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,020 | 🐛 344 | 🌐 Rust | 📅 2026-10-16 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,313 | 🐛 1,929 | 🌐 Rust | 📅 2026-10-19 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 49,965 | 🐛 38 | 🌐 C | 📅 2026-10-22

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,808 | 🐛 1,911 | 🌐 Rust | 📅 2026-10-22 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,662 | 🐛 1,748 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,129 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,352 | 🐛 221 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,934 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,907 | 🐛 418 | 🌐 C | 📅 2026-10-22

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,687 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,363 | 🐛 1,050 | 🌐 Go | 📅 2026-10-21

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,593 | 🐛 352 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 127 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,641 | 🐛 124 | 🌐 Rust | 📅 2026-10-22 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,199 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,396 | 🐛 172 | 🌐 Rust | 📅 2026-10-19 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,571 | 🐛 5,170 | 🌐 Go | 📅 2026-10-22

* [SWC](https://github.com/swc-project/swc) ⭐ 34,197 | 🐛 414 | 🌐 Rust | 📅 2026-10-22 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,569 | 🐛 127 | 🌐 JavaScript | 📅 2026-10-22

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,728 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,584 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,829 | 🐛 24 | 🌐 Python | 📅 2026-10-13

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 50,223 | 🐛 2,215 | 🌐 Rust | 📅 2026-10-22 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,371 | 🐛 1,453 | 🌐 JavaScript | 📅 2026-10-22

* [dprint](https://github.com/dprint/dprint) ⭐ 4,109 | 🐛 27 | 🌐 Rust | 📅 2026-10-22 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,217 | 🐛 1,083 | 🌐 Haskell | 📅 2026-10-19

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,808 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 122,552 | 🐛 1,263 | 🌐 JavaScript | 📅 2026-10-22

* [Deno](https://github.com/denoland/deno) ⭐ 108,724 | 🐛 1,637 | 🌐 Rust | 📅 2026-10-22 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,741 | 🐛 9,451 | 🌐 Python | 📅 2026-10-22

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,415 | 🐛 302 | 🌐 Rust | 📅 2026-10-22 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,279 | 🐛 57 | 🌐 JavaScript | 📅 2026-10-16

* [mrml](https://github.com/jdrouet/mrml) ⭐ 512 | 🐛 32 | 🌐 HTML | 📅 2026-10-19 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 104,977 | 🐛 17,718 | 🌐 Python | 📅 2026-10-22

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,505 | 🐛 276 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,643 | 🐛 922 | 🌐 Java | 📅 2026-10-22

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,528 | 🐛 9 | 🌐 Rust | 📅 2026-10-22 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,593 | 🐛 2,715 | 🌐 Java | 📅 2026-10-22

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,249 | 🐛 486 | 🌐 Rust | 📅 2026-10-22 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-22._
