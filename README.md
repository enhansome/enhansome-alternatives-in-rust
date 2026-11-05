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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,529 | 🐛 196 | 🌐 Go | 📅 2026-11-05

* [youki](https://github.com/youki-dev/youki) ⭐ 7,665 | 🐛 177 | 🌐 Rust | 📅 2026-11-05 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,718 | 🐛 0 | 🌐 C | 📅 2026-11-05

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,757 | 🐛 58 | 🌐 Rust | 📅 2026-10-26 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,257 | 🐛 64 | 🌐 C++ | 📅 2026-10-28

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 430 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,504 | 🐛 6,347 | 🌐 Java | 📅 2026-11-05

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,769 | 🐛 861 | 🌐 Rust | 📅 2026-11-05 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,593 | 🐛 992 | 🌐 Java | 📅 2026-11-05

* [drill](https://github.com/fcsonline/drill) ⭐ 2,313 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,466 | 🐛 163 | 🌐 Rust | 📅 2026-11-01 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,788 | 🐛 1,462 | 🌐 Rust | 📅 2026-11-05 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,659 | 🐛 60 | 🌐 Rust | 📅 2026-11-03 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,111 | 🐛 564 | 🌐 Rust | 📅 2026-11-05 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,645 | 🐛 26 | 🌐 Perl | 📅 2026-10-26

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,045 | 🐛 256 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,824 | 🐛 0 | 🌐 C | 📅 2026-11-03

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,805 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 932 | 🐛 17 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,290 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,667 | 🐛 503 | 🌐 Rust | 📅 2026-10-28 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,159 | 🐛 285 | 🌐 Rust | 📅 2026-11-04 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,692 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,582 | 🐛 10 | 🌐 Rust | 📅 2026-11-01 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,416 | 🐛 0 | 🌐 Rust | 📅 2026-11-03 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,988 | 🐛 210 | 🌐 Rust | 📅 2026-11-04 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,044 | 🐛 336 | 🌐 Go | 📅 2026-11-05

* [skim](https://github.com/skim-rs/skim) ⭐ 7,004 | 🐛 9 | 🌐 Rust | 📅 2026-11-05 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,355 | 🐛 15 | 🌐 C | 📅 2026-11-05

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,332 | 🐛 1,415 | 🌐 Rust | 📅 2026-11-05 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,301 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,695 | 🐛 362 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,170 | 🐛 41 | 🌐 Rust | 📅 2026-10-29 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,793 | 🐛 478 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,283 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,266 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,765 | 🐛 373 | 🌐 Shell | 📅 2026-11-04

* [mise](https://github.com/jdx/mise) ⭐ 35,816 | 🐛 18 | 🌐 Rust | 📅 2026-11-05 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,306 | 🐛 257 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,035 | 🐛 708 | 🌐 C | 📅 2026-11-04

* [broot](https://github.com/Canop/broot) ⭐ 13,134 | 🐛 103 | 🌐 Rust | 📅 2026-11-01 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,218 | 🐛 43 | 🌐 Rust | 📅 2026-11-02 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,740 | 🐛 20 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 605 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,737 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,414 | 🐛 87 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,052 | 🐛 28 | 🌐 Rust | 📅 2026-11-02 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,212 | 🐛 76 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,135 | 🐛 288 | 🌐 Markdown | 📅 2026-11-05

* [navi](https://github.com/denisidoro/navi) ⭐ 17,837 | 🐛 129 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,642 | 🐛 21 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,303 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,163 | 🐛 103 | 🌐 Rust | 📅 2026-11-04 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,068 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,818 | 🐛 225 | 🌐 Go | 📅 2026-11-02

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,074 | 🐛 165 | 🌐 Rust | 📅 2026-11-04 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,602 | 🐛 131 | 🌐 Shell | 📅 2026-10-26

* [starship](https://github.com/starship/starship) ⭐ 60,614 | 🐛 1,064 | 🌐 Rust | 📅 2026-11-04 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,121 | 🐛 346 | 🌐 Rust | 📅 2026-11-02 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,458 | 🐛 1,956 | 🌐 Rust | 📅 2026-10-26 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,163 | 🐛 49 | 🌐 C | 📅 2026-11-03

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,947 | 🐛 1,931 | 🌐 Rust | 📅 2026-11-05 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,816 | 🐛 1,784 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,137 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,736 | 🐛 221 | 🌐 Rust | 📅 2026-10-27 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,934 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,051 | 🐛 427 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,691 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,673 | 🐛 1,067 | 🌐 Go | 📅 2026-11-04

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,622 | 🐛 358 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,666 | 🐛 120 | 🌐 Rust | 📅 2026-11-05 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,199 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,580 | 🐛 173 | 🌐 Rust | 📅 2026-11-02 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,764 | 🐛 5,248 | 🌐 Go | 📅 2026-11-05

* [SWC](https://github.com/swc-project/swc) ⭐ 34,208 | 🐛 420 | 🌐 Rust | 📅 2026-11-05 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,606 | 🐛 139 | 🌐 JavaScript | 📅 2026-11-05

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,727 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,586 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,832 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 50,462 | 🐛 2,240 | 🌐 Rust | 📅 2026-11-05 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,407 | 🐛 1,479 | 🌐 JavaScript | 📅 2026-11-05

* [dprint](https://github.com/dprint/dprint) ⭐ 4,128 | 🐛 35 | 🌐 Rust | 📅 2026-11-05 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,287 | 🐛 1,090 | 🌐 Haskell | 📅 2026-11-05

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,805 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,268 | 🐛 1,322 | 🌐 JavaScript | 📅 2026-11-05

* [Deno](https://github.com/denoland/deno) ⭐ 108,842 | 🐛 1,687 | 🌐 Rust | 📅 2026-10-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,920 | 🐛 9,245 | 🌐 Python | 📅 2026-11-05

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,454 | 🐛 365 | 🌐 Rust | 📅 2026-11-05 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,285 | 🐛 57 | 🌐 JavaScript | 📅 2026-11-05

* [mrml](https://github.com/jdrouet/mrml) ⭐ 513 | 🐛 34 | 🌐 HTML | 📅 2026-10-30 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,165 | 🐛 17,996 | 🌐 Python | 📅 2026-11-05

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,516 | 🐛 283 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,652 | 🐛 906 | 🌐 Java | 📅 2026-11-04

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,537 | 🐛 5 | 🌐 Rust | 📅 2026-11-05 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,606 | 🐛 2,732 | 🌐 Java | 📅 2026-11-05

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,402 | 🐛 511 | 🌐 Rust | 📅 2026-11-05 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-05._
