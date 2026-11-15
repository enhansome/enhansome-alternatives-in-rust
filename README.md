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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,559 | 🐛 187 | 🌐 Go | 📅 2026-11-13

* [youki](https://github.com/youki-dev/youki) ⭐ 7,692 | 🐛 173 | 🌐 Rust | 📅 2026-11-15 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,836 | 🐛 0 | 🌐 C | 📅 2026-11-14

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,810 | 🐛 60 | 🌐 Rust | 📅 2026-10-26 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,398 | 🐛 61 | 🌐 C++ | 📅 2026-11-15

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 432 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,692 | 🐛 6,565 | 🌐 Java | 📅 2026-11-15

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,796 | 🐛 857 | 🌐 Rust | 📅 2026-11-14 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,604 | 🐛 996 | 🌐 Java | 📅 2026-11-05

* [drill](https://github.com/fcsonline/drill) ⭐ 2,315 | 🐛 43 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,599 | 🐛 158 | 🌐 Rust | 📅 2026-11-08 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 41,018 | 🐛 817 | 🌐 Rust | 📅 2026-11-15 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,659 | 🐛 60 | 🌐 Rust | 📅 2026-11-03 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 919 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,267 | 🐛 565 | 🌐 Rust | 📅 2026-11-15 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,668 | 🐛 26 | 🌐 Perl | 📅 2026-11-14

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,070 | 🐛 259 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,835 | 🐛 0 | 🌐 C | 📅 2026-11-15

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,811 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 935 | 🐛 17 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,293 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 746 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,734 | 🐛 497 | 🌐 Rust | 📅 2026-11-15 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,187 | 🐛 287 | 🌐 Rust | 📅 2026-11-15 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,695 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,637 | 🐛 14 | 🌐 Rust | 📅 2026-11-01 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,443 | 🐛 0 | 🌐 Rust | 📅 2026-11-12 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 45,068 | 🐛 204 | 🌐 Rust | 📅 2026-11-14 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,212 | 🐛 333 | 🌐 Go | 📅 2026-11-12

* [skim](https://github.com/skim-rs/skim) ⭐ 7,015 | 🐛 7 | 🌐 Rust | 📅 2026-11-13 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,361 | 🐛 15 | 🌐 C | 📅 2026-11-15

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,372 | 🐛 1,421 | 🌐 Rust | 📅 2026-11-15 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,309 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,720 | 🐛 362 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,189 | 🐛 39 | 🌐 Rust | 📅 2026-11-06 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,920 | 🐛 484 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,290 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,265 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 96,119 | 🐛 379 | 🌐 Shell | 📅 2026-11-12

* [mise](https://github.com/jdx/mise) ⭐ 36,185 | 🐛 15 | 🌐 Rust | 📅 2026-11-15 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,412 | 🐛 259 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,051 | 🐛 711 | 🌐 C | 📅 2026-11-15

* [broot](https://github.com/Canop/broot) ⭐ 13,158 | 🐛 103 | 🌐 Rust | 📅 2026-11-12 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,224 | 🐛 44 | 🌐 Rust | 📅 2026-11-13 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,743 | 🐛 20 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 607 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,736 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,430 | 🐛 87 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,053 | 🐛 28 | 🌐 Rust | 📅 2026-11-15 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 134 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,473 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,282 | 🐛 79 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,214 | 🐛 304 | 🌐 Markdown | 📅 2026-11-15

* [navi](https://github.com/denisidoro/navi) ⭐ 17,861 | 🐛 130 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,671 | 🐛 19 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,309 | 🐛 5 | 🌐 Rust | 📅 2026-11-10 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,195 | 🐛 102 | 🌐 Rust | 📅 2026-11-15 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,070 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,838 | 🐛 233 | 🌐 Go | 📅 2026-11-13

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,086 | 🐛 123 | 🌐 Rust | 📅 2026-11-15 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,605 | 🐛 131 | 🌐 Shell | 📅 2026-11-09

* [starship](https://github.com/starship/starship) ⭐ 60,744 | 🐛 1,064 | 🌐 Rust | 📅 2026-11-15 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,193 | 🐛 347 | 🌐 Rust | 📅 2026-11-06 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,564 | 🐛 1,977 | 🌐 Rust | 📅 2026-11-14 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,326 | 🐛 46 | 🌐 C | 📅 2026-11-14

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 36,079 | 🐛 1,976 | 🌐 Rust | 📅 2026-11-13 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,899 | 🐛 1,780 | 🌐 Rust | 📅 2026-11-12 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,144 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,963 | 🐛 226 | 🌐 Rust | 📅 2026-11-09 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,938 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,137 | 🐛 438 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,691 | 🐛 1 | 🌐 Rust | 📅 2026-11-15 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,910 | 🐛 1,071 | 🌐 Go | 📅 2026-11-15

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,662 | 🐛 360 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,681 | 🐛 120 | 🌐 Rust | 📅 2026-11-13 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,201 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,712 | 🐛 172 | 🌐 Rust | 📅 2026-11-15 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,822 | 🐛 5,303 | 🌐 Go | 📅 2026-11-15

* [SWC](https://github.com/swc-project/swc) ⭐ 34,219 | 🐛 396 | 🌐 Rust | 📅 2026-11-15 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,619 | 🐛 157 | 🌐 JavaScript | 📅 2026-11-15

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,725 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,587 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,837 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 51,256 | 🐛 2,286 | 🌐 Rust | 📅 2026-11-15 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,415 | 🐛 1,466 | 🌐 JavaScript | 📅 2026-11-14

* [dprint](https://github.com/dprint/dprint) ⭐ 4,136 | 🐛 37 | 🌐 Rust | 📅 2026-11-14 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,347 | 🐛 1,075 | 🌐 Haskell | 📅 2026-11-09

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,804 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,741 | 🐛 1,321 | 🌐 JavaScript | 📅 2026-11-15

* [Deno](https://github.com/denoland/deno) ⭐ 108,899 | 🐛 1,736 | 🌐 Rust | 📅 2026-10-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 78,225 | 🐛 9,297 | 🌐 Python | 📅 2026-11-15

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,486 | 🐛 311 | 🌐 Rust | 📅 2026-11-15 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,294 | 🐛 61 | 🌐 JavaScript | 📅 2026-11-10

* [mrml](https://github.com/jdrouet/mrml) ⭐ 515 | 🐛 30 | 🌐 HTML | 📅 2026-11-08 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,522 | 🐛 18,303 | 🌐 Python | 📅 2026-11-15

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,520 | 🐛 282 | 🌐 Rust | 📅 2026-11-10 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,657 | 🐛 808 | 🌐 Java | 📅 2026-11-15

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,545 | 🐛 19 | 🌐 Rust | 📅 2026-11-15 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,612 | 🐛 2,746 | 🌐 Java | 📅 2026-11-15

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,441 | 🐛 523 | 🌐 Rust | 📅 2026-11-11 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-15._
