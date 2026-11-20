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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,569 | 🐛 176 | 🌐 Go | 📅 2026-11-17

* [youki](https://github.com/youki-dev/youki) ⭐ 7,708 | 🐛 169 | 🌐 Rust | 📅 2026-11-20 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,896 | 🐛 0 | 🌐 C | 📅 2026-11-20

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,969 | 🐛 67 | 🌐 Rust | 📅 2026-11-18 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,449 | 🐛 46 | 🌐 C++ | 📅 2026-11-20

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 432 | 🐛 12 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,685 | 🐛 6,673 | 🌐 Java | 📅 2026-11-20

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,807 | 🐛 857 | 🌐 Rust | 📅 2026-11-20 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,609 | 🐛 996 | 🌐 Java | 📅 2026-11-05

* [drill](https://github.com/fcsonline/drill) ⭐ 2,316 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,681 | 🐛 164 | 🌐 Rust | 📅 2026-11-18 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 41,043 | 🐛 701 | 🌐 Rust | 📅 2026-11-20 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,657 | 🐛 60 | 🌐 Rust | 📅 2026-11-03 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,333 | 🐛 572 | 🌐 Rust | 📅 2026-11-20 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,681 | 🐛 26 | 🌐 Perl | 📅 2026-11-18

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,093 | 🐛 259 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,836 | 🐛 0 | 🌐 C | 📅 2026-11-20

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,811 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 934 | 🐛 18 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,292 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,794 | 🐛 501 | 🌐 Rust | 📅 2026-11-20 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,215 | 🐛 289 | 🌐 Rust | 📅 2026-11-19 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,692 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,670 | 🐛 8 | 🌐 Rust | 📅 2026-11-19 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,459 | 🐛 1 | 🌐 Rust | 📅 2026-11-19 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 45,137 | 🐛 208 | 🌐 Rust | 📅 2026-11-18 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,315 | 🐛 336 | 🌐 Go | 📅 2026-11-19

* [skim](https://github.com/skim-rs/skim) ⭐ 7,014 | 🐛 8 | 🌐 Rust | 📅 2026-11-20 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,369 | 🐛 15 | 🌐 C | 📅 2026-11-20

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,402 | 🐛 1,404 | 🌐 Rust | 📅 2026-11-20 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,317 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,725 | 🐛 364 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,198 | 🐛 38 | 🌐 Rust | 📅 2026-11-06 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,981 | 🐛 491 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,296 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,264 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 96,262 | 🐛 357 | 🌐 Shell | 📅 2026-11-20

* [mise](https://github.com/jdx/mise) ⭐ 36,350 | 🐛 8 | 🌐 Rust | 📅 2026-11-20 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,463 | 🐛 259 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,056 | 🐛 714 | 🌐 C | 📅 2026-11-20

* [broot](https://github.com/Canop/broot) ⭐ 13,173 | 🐛 103 | 🌐 Rust | 📅 2026-11-12 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,239 | 🐛 44 | 🌐 Rust | 📅 2026-11-20 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,748 | 🐛 20 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 653 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 607 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,737 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,437 | 🐛 87 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,053 | 🐛 28 | 🌐 Rust | 📅 2026-11-15 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,309 | 🐛 80 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,261 | 🐛 319 | 🌐 Markdown | 📅 2026-11-20

* [navi](https://github.com/denisidoro/navi) ⭐ 17,885 | 🐛 130 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,680 | 🐛 20 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,311 | 🐛 5 | 🌐 Rust | 📅 2026-11-10 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,217 | 🐛 100 | 🌐 Rust | 📅 2026-11-20 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,075 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,844 | 🐛 230 | 🌐 Go | 📅 2026-11-16

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,103 | 🐛 128 | 🌐 Rust | 📅 2026-11-18 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,611 | 🐛 131 | 🌐 Shell | 📅 2026-11-09

* [starship](https://github.com/starship/starship) ⭐ 60,820 | 🐛 1,071 | 🌐 Rust | 📅 2026-11-20 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,247 | 🐛 346 | 🌐 Rust | 📅 2026-11-18 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,627 | 🐛 1,974 | 🌐 Rust | 📅 2026-11-20 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,579 | 🐛 54 | 🌐 C | 📅 2026-11-20

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 36,164 | 🐛 1,971 | 🌐 Rust | 📅 2026-11-20 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,949 | 🐛 1,758 | 🌐 Rust | 📅 2026-11-20 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,144 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 70,101 | 🐛 205 | 🌐 Rust | 📅 2026-11-20 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,939 | 🐛 16 | 🌐 Rust | 📅 2026-11-18 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,194 | 🐛 455 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,692 | 🐛 0 | 🌐 Rust | 📅 2026-11-15 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,978 | 🐛 1,080 | 🌐 Go | 📅 2026-11-18

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,675 | 🐛 361 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,684 | 🐛 124 | 🌐 Rust | 📅 2026-11-20 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,198 | 🐛 195 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,775 | 🐛 173 | 🌐 Rust | 📅 2026-11-15 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,868 | 🐛 5,265 | 🌐 Go | 📅 2026-11-20

* [SWC](https://github.com/swc-project/swc) ⭐ 34,222 | 🐛 385 | 🌐 Rust | 📅 2026-11-20 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,638 | 🐛 157 | 🌐 JavaScript | 📅 2026-11-20

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,723 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,585 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,836 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 51,328 | 🐛 2,311 | 🌐 Rust | 📅 2026-11-20 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,442 | 🐛 1,476 | 🌐 JavaScript | 📅 2026-11-20

* [dprint](https://github.com/dprint/dprint) ⭐ 4,144 | 🐛 30 | 🌐 Rust | 📅 2026-11-16 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,362 | 🐛 1,078 | 🌐 Haskell | 📅 2026-11-20

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,806 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,810 | 🐛 1,304 | 🌐 JavaScript | 📅 2026-11-20

* [Deno](https://github.com/denoland/deno) ⭐ 109,119 | 🐛 1,754 | 🌐 Rust | 📅 2026-11-17 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 78,439 | 🐛 9,336 | 🌐 Python | 📅 2026-11-20

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,498 | 🐛 340 | 🌐 Rust | 📅 2026-11-19 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,299 | 🐛 61 | 🌐 JavaScript | 📅 2026-11-20

* [mrml](https://github.com/jdrouet/mrml) ⭐ 517 | 🐛 20 | 🌐 HTML | 📅 2026-11-20 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,757 | 🐛 18,460 | 🌐 Python | 📅 2026-11-20

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,520 | 🐛 283 | 🌐 Rust | 📅 2026-11-10 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,658 | 🐛 733 | 🌐 Java | 📅 2026-11-18

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,548 | 🐛 15 | 🌐 Rust | 📅 2026-11-20 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,613 | 🐛 2,750 | 🌐 Java | 📅 2026-11-20

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,461 | 🐛 526 | 🌐 Rust | 📅 2026-11-18 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-20._
