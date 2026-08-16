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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,402 | 🐛 343 | 🌐 Go | 📅 2026-08-14

* [youki](https://github.com/youki-dev/youki) ⭐ 7,544 | 🐛 144 | 🌐 Rust | 📅 2026-08-16 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,807 | 🐛 0 | 🌐 C | 📅 2026-08-15

* [pgrust](https://github.com/malisper/pgrust) ⭐ 4,443 | 🐛 12 | 🌐 Rust | 📅 2026-08-13 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 16,337 | 🐛 56 | 🌐 C++ | 📅 2026-08-10

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 432 | 🐛 11 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,834 | 🐛 6,067 | 🌐 Java | 📅 2026-08-16

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,496 | 🐛 800 | 🌐 Rust | 📅 2026-08-14 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,506 | 🐛 964 | 🌐 Java | 📅 2026-08-14

* [drill](https://github.com/fcsonline/drill) ⭐ 2,304 | 🐛 38 | 🌐 Rust | 📅 2026-07-29 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,673 | 🐛 136 | 🌐 Rust | 📅 2026-08-10 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,314 | 🐛 34 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,272 | 🐛 1,418 | 🌐 Rust | 📅 2026-08-15 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,656 | 🐛 60 | 🌐 Rust | 📅 2026-05-02 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 913 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 161 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,192 | 🐛 420 | 🌐 Rust | 📅 2026-08-11 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,437 | 🐛 26 | 🌐 Perl | 📅 2026-08-08

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,816 | 🐛 243 | 🌐 Rust | 📅 2026-05-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,768 | 🐛 0 | 🌐 C | 📅 2026-08-16

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,794 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 926 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,261 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 742 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 31,768 | 🐛 428 | 🌐 Rust | 📅 2026-08-02 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,780 | 🐛 296 | 🌐 Rust | 📅 2026-08-16 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,686 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,129 | 🐛 11 | 🌐 Rust | 📅 2026-08-16 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,140 | 🐛 31 | 🌐 Rust | 📅 2026-08-16 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,100 | 🐛 188 | 🌐 Rust | 📅 2026-08-11 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 82,548 | 🐛 326 | 🌐 Go | 📅 2026-08-14

* [skim](https://github.com/skim-rs/skim) ⭐ 6,924 | 🐛 5 | 🌐 Rust | 📅 2026-08-16 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,251 | 🐛 17 | 🌐 C | 📅 2026-08-16

* [coreutils](https://github.com/uutils/coreutils) ⭐ 23,947 | 🐛 1,159 | 🌐 Rust | 📅 2026-08-16 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,257 | 🐛 35 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,423 | 🐛 330 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,020 | 🐛 38 | 🌐 Rust | 📅 2026-08-16 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 22,950 | 🐛 425 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,172 | 🐛 207 | 🌐 Rust | 📅 2026-07-25 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,261 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 94,608 | 🐛 399 | 🌐 Shell | 📅 2026-07-24

* [mise](https://github.com/jdx/mise) ⭐ 32,545 | 🐛 69 | 🌐 Rust | 📅 2026-08-16 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 26,586 | 🐛 239 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 949 | 🐛 684 | 🌐 C | 📅 2026-08-16

* [broot](https://github.com/Canop/broot) ⭐ 12,894 | 🐛 242 | 🌐 Rust | 📅 2026-08-16 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,137 | 🐛 41 | 🌐 Rust | 📅 2026-08-10 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,732 | 🐛 15 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 592 | 🐛 12 | 🌐 Rust | 📅 2026-03-21 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,729 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,300 | 🐛 74 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,044 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,462 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,658 | 🐛 96 | 🌐 Rust | 📅 2026-04-30 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 63,411 | 🐛 301 | 🌐 Markdown | 📅 2026-08-16

* [navi](https://github.com/denisidoro/navi) ⭐ 17,441 | 🐛 110 | 🌐 Rust | 📅 2026-07-28 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,430 | 🐛 19 | 🌐 Rust | 📅 2026-08-14 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,271 | 🐛 5 | 🌐 Rust | 📅 2026-07-26 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,893 | 🐛 109 | 🌐 Rust | 📅 2026-08-15 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,044 | 🐛 40 | 🌐 Rust | 📅 2026-07-13 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 266 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 570 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,679 | 🐛 210 | 🌐 Go | 📅 2026-08-16

* [paru](https://github.com/Morganamilo/paru) ⭐ 8,939 | 🐛 203 | 🌐 Rust | 📅 2026-01-09 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,559 | 🐛 128 | 🌐 Shell | 📅 2026-08-05

* [starship](https://github.com/starship/starship) ⭐ 59,423 | 🐛 1,026 | 🌐 Rust | 📅 2026-08-16 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 65,393 | 🐛 341 | 🌐 Rust | 📅 2026-08-03 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 28,385 | 🐛 1,811 | 🌐 Rust | 📅 2026-08-15 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 48,655 | 🐛 50 | 🌐 C | 📅 2026-08-15

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 34,930 | 🐛 1,862 | 🌐 Rust | 📅 2026-08-13 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 45,837 | 🐛 1,610 | 🌐 Rust | 📅 2026-08-11 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,120 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,326 | 🐛 176 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,924 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,458 | 🐛 473 | 🌐 C | 📅 2026-08-12

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,673 | 🐛 2 | 🌐 Rust | 📅 2026-03-18 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,373 | 🐛 1,018 | 🌐 Go | 📅 2026-08-16

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,396 | 🐛 335 | 🌐 Rust | 📅 2026-08-04 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 395 | 🐛 7 | 🌐 Rust | 📅 2026-02-17 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,551 | 🐛 120 | 🌐 Rust | 📅 2026-08-12 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,198 | 🐛 197 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 35,312 | 🐛 168 | 🌐 Rust | 📅 2026-08-12 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 110,175 | 🐛 5,076 | 🌐 TypeScript | 📅 2026-08-14

* [SWC](https://github.com/swc-project/swc) ⭐ 34,178 | 🐛 409 | 🌐 Rust | 📅 2026-08-15 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,458 | 🐛 128 | 🌐 JavaScript | 📅 2026-08-16

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,731 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,585 | 🐛 167 | 🌐 Rust | 📅 2026-07-23 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,815 | 🐛 24 | 🌐 Python | 📅 2026-07-14

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,224 | 🐛 2,100 | 🌐 Rust | 📅 2026-08-16 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,204 | 🐛 1,425 | 🌐 JavaScript | 📅 2026-08-16

* [dprint](https://github.com/dprint/dprint) ⭐ 4,042 | 🐛 84 | 🌐 Rust | 📅 2026-08-16 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 39,881 | 🐛 1,136 | 🌐 Haskell | 📅 2026-08-04

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,796 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 118,950 | 🐛 1,472 | 🌐 JavaScript | 📅 2026-08-16

* [Deno](https://github.com/denoland/deno) ⭐ 108,259 | 🐛 1,501 | 🌐 Rust | 📅 2026-08-14 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 74,334 | 🐛 9,507 | 🌐 Python | 📅 2026-08-16

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,284 | 🐛 405 | 🌐 Rust | 📅 2026-08-16 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,199 | 🐛 67 | 🌐 JavaScript | 📅 2026-08-13

* [mrml](https://github.com/jdrouet/mrml) ⭐ 504 | 🐛 21 | 🌐 HTML | 📅 2026-08-11 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 102,401 | 🐛 17,331 | 🌐 Python | 📅 2026-08-16

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,474 | 🐛 244 | 🌐 Rust | 📅 2026-07-17 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,556 | 🐛 565 | 🌐 Java | 📅 2026-08-16

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,502 | 🐛 9 | 🌐 Rust | 📅 2026-08-16 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,538 | 🐛 2,645 | 🌐 Java | 📅 2026-08-14

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 15,700 | 🐛 441 | 🌐 Rust | 📅 2026-08-15 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
