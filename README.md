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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,587 | 🐛 177 | 🌐 Go | 📅 2026-11-25

* [youki](https://github.com/youki-dev/youki) ⭐ 7,716 | 🐛 181 | 🌐 Rust | 📅 2026-11-25 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,960 | 🐛 0 | 🌐 C | 📅 2026-11-26

* [pgrust](https://github.com/malisper/pgrust) ⭐ 6,095 | 🐛 70 | 🌐 Rust | 📅 2026-11-18 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,506 | 🐛 37 | 🌐 C++ | 📅 2026-11-26

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 433 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,841 | 🐛 6,686 | 🌐 Java | 📅 2026-11-26

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,816 | 🐛 848 | 🌐 Rust | 📅 2026-11-26 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,615 | 🐛 997 | 🌐 Java | 📅 2026-11-25

* [drill](https://github.com/fcsonline/drill) ⭐ 2,315 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,777 | 🐛 162 | 🌐 Rust | 📅 2026-11-25 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 41,123 | 🐛 686 | 🌐 Rust | 📅 2026-11-26 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,657 | 🐛 60 | 🌐 Rust | 📅 2026-11-23 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,529 | 🐛 569 | 🌐 Rust | 📅 2026-11-26 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,690 | 🐛 26 | 🌐 Perl | 📅 2026-11-18

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,133 | 🐛 260 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,842 | 🐛 0 | 🌐 C | 📅 2026-11-26

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,812 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 935 | 🐛 18 | 🌐 Rust | 📅 2026-11-22 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,293 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 746 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,857 | 🐛 506 | 🌐 Rust | 📅 2026-11-25 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,274 | 🐛 291 | 🌐 Rust | 📅 2026-11-19 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,694 | 🐛 80 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,736 | 🐛 8 | 🌐 Rust | 📅 2026-11-25 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,498 | 🐛 2 | 🌐 Rust | 📅 2026-11-24 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 45,219 | 🐛 206 | 🌐 Rust | 📅 2026-11-25 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,511 | 🐛 341 | 🌐 Go | 📅 2026-11-24

* [skim](https://github.com/skim-rs/skim) ⭐ 7,023 | 🐛 9 | 🌐 Rust | 📅 2026-11-25 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,373 | 🐛 16 | 🌐 C | 📅 2026-11-26

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,448 | 🐛 1,437 | 🌐 Rust | 📅 2026-11-26 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,345 | 🐛 44 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,746 | 🐛 365 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,241 | 🐛 38 | 🌐 Rust | 📅 2026-11-06 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 24,064 | 🐛 494 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,331 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,264 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 96,335 | 🐛 359 | 🌐 Shell | 📅 2026-11-25

* [mise](https://github.com/jdx/mise) ⭐ 36,552 | 🐛 57 | 🌐 Rust | 📅 2026-11-26 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,521 | 🐛 262 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,058 | 🐛 717 | 🌐 C | 📅 2026-11-26

* [broot](https://github.com/Canop/broot) ⭐ 13,212 | 🐛 103 | 🌐 Rust | 📅 2026-11-12 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,266 | 🐛 41 | 🌐 Rust | 📅 2026-11-26 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,751 | 🐛 21 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 654 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 607 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,738 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,478 | 🐛 88 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,056 | 🐛 28 | 🌐 Rust | 📅 2026-11-15 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 18 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,374 | 🐛 83 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,325 | 🐛 316 | 🌐 Markdown | 📅 2026-11-26

* [navi](https://github.com/denisidoro/navi) ⭐ 17,903 | 🐛 131 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,694 | 🐛 21 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,310 | 🐛 5 | 🌐 Rust | 📅 2026-11-10 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,297 | 🐛 96 | 🌐 Rust | 📅 2026-11-26 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,077 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 265 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,857 | 🐛 223 | 🌐 Go | 📅 2026-11-26

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,127 | 🐛 128 | 🌐 Rust | 📅 2026-11-25 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,616 | 🐛 130 | 🌐 Shell | 📅 2026-11-25

* [starship](https://github.com/starship/starship) ⭐ 60,946 | 🐛 1,065 | 🌐 Rust | 📅 2026-11-26 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,317 | 🐛 346 | 🌐 Rust | 📅 2026-11-18 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,709 | 🐛 1,984 | 🌐 Rust | 📅 2026-11-26 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,604 | 🐛 34 | 🌐 C | 📅 2026-11-26

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 36,281 | 🐛 1,999 | 🌐 Rust | 📅 2026-11-24 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 47,036 | 🐛 1,770 | 🌐 Rust | 📅 2026-11-20 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,144 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 70,390 | 🐛 81 | 🌐 Rust | 📅 2026-11-24 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,940 | 🐛 16 | 🌐 Rust | 📅 2026-11-20 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,360 | 🐛 465 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,693 | 🐛 0 | 🌐 Rust | 📅 2026-11-15 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 84,116 | 🐛 1,083 | 🌐 Go | 📅 2026-11-23

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,693 | 🐛 364 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 395 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,691 | 🐛 129 | 🌐 Rust | 📅 2026-11-26 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,198 | 🐛 195 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,864 | 🐛 176 | 🌐 Rust | 📅 2026-11-15 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,917 | 🐛 5,310 | 🌐 Go | 📅 2026-11-26

* [SWC](https://github.com/swc-project/swc) ⭐ 34,223 | 🐛 381 | 🌐 Rust | 📅 2026-11-26 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,651 | 🐛 157 | 🌐 JavaScript | 📅 2026-11-26

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,723 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,584 | 🐛 170 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,836 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 51,571 | 🐛 2,321 | 🌐 Rust | 📅 2026-11-26 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,456 | 🐛 1,498 | 🌐 JavaScript | 📅 2026-11-26

* [dprint](https://github.com/dprint/dprint) ⭐ 4,149 | 🐛 32 | 🌐 Rust | 📅 2026-11-25 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,388 | 🐛 1,061 | 🌐 Haskell | 📅 2026-11-26

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,808 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 124,036 | 🐛 1,270 | 🌐 JavaScript | 📅 2026-11-26

* [Deno](https://github.com/denoland/deno) ⭐ 109,034 | 🐛 1,758 | 🌐 Rust | 📅 2026-11-17 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 78,474 | 🐛 9,366 | 🌐 Python | 📅 2026-11-26

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,509 | 🐛 329 | 🌐 Rust | 📅 2026-11-26 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,305 | 🐛 59 | 🌐 JavaScript | 📅 2026-11-26

* [mrml](https://github.com/jdrouet/mrml) ⭐ 521 | 🐛 21 | 🌐 HTML | 📅 2026-11-26 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,786 | 🐛 18,662 | 🌐 Python | 📅 2026-11-26

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,522 | 🐛 256 | 🌐 Rust | 📅 2026-11-10 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,667 | 🐛 724 | 🌐 Java | 📅 2026-11-26

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,552 | 🐛 10 | 🌐 Rust | 📅 2026-11-26 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,618 | 🐛 2,748 | 🌐 Java | 📅 2026-11-26

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,487 | 🐛 538 | 🌐 Rust | 📅 2026-11-26 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-26._
