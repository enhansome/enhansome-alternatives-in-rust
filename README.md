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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,537 | 🐛 193 | 🌐 Go | 📅 2026-11-05

* [youki](https://github.com/youki-dev/youki) ⭐ 7,669 | 🐛 175 | 🌐 Rust | 📅 2026-11-07 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,722 | 🐛 0 | 🌐 C | 📅 2026-11-07

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,769 | 🐛 58 | 🌐 Rust | 📅 2026-10-26 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,280 | 🐛 55 | 🌐 C++ | 📅 2026-11-06

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 430 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,523 | 🐛 6,412 | 🌐 Java | 📅 2026-11-07

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,776 | 🐛 858 | 🌐 Rust | 📅 2026-11-06 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,599 | 🐛 992 | 🌐 Java | 📅 2026-11-05

* [drill](https://github.com/fcsonline/drill) ⭐ 2,313 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,492 | 🐛 159 | 🌐 Rust | 📅 2026-11-07 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 41,058 | 🐛 1,458 | 🌐 Rust | 📅 2026-11-06 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,659 | 🐛 60 | 🌐 Rust | 📅 2026-11-03 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 917 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,218 | 🐛 563 | 🌐 Rust | 📅 2026-11-07 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,645 | 🐛 26 | 🌐 Perl | 📅 2026-10-26

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,046 | 🐛 256 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,826 | 🐛 0 | 🌐 C | 📅 2026-11-07

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,806 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 932 | 🐛 17 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,291 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,684 | 🐛 504 | 🌐 Rust | 📅 2026-10-28 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,159 | 🐛 285 | 🌐 Rust | 📅 2026-11-04 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,690 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,592 | 🐛 10 | 🌐 Rust | 📅 2026-11-01 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,420 | 🐛 0 | 🌐 Rust | 📅 2026-11-03 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 45,108 | 🐛 205 | 🌐 Rust | 📅 2026-11-07 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,056 | 🐛 333 | 🌐 Go | 📅 2026-11-07

* [skim](https://github.com/skim-rs/skim) ⭐ 7,005 | 🐛 9 | 🌐 Rust | 📅 2026-11-06 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,354 | 🐛 15 | 🌐 C | 📅 2026-11-07

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,342 | 🐛 1,381 | 🌐 Rust | 📅 2026-11-07 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,299 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,699 | 🐛 362 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,173 | 🐛 39 | 🌐 Rust | 📅 2026-11-06 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,815 | 🐛 479 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,281 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,266 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,767 | 🐛 374 | 🌐 Shell | 📅 2026-11-04

* [mise](https://github.com/jdx/mise) ⭐ 35,903 | 🐛 14 | 🌐 Rust | 📅 2026-11-07 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,331 | 🐛 257 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,036 | 🐛 707 | 🌐 C | 📅 2026-11-07

* [broot](https://github.com/Canop/broot) ⭐ 13,135 | 🐛 103 | 🌐 Rust | 📅 2026-11-01 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,217 | 🐛 43 | 🌐 Rust | 📅 2026-11-06 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,740 | 🐛 20 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 605 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,737 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,415 | 🐛 87 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,053 | 🐛 28 | 🌐 Rust | 📅 2026-11-02 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,223 | 🐛 76 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,161 | 🐛 292 | 🌐 Markdown | 📅 2026-11-07

* [navi](https://github.com/denisidoro/navi) ⭐ 17,841 | 🐛 130 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,652 | 🐛 21 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,303 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,166 | 🐛 103 | 🌐 Rust | 📅 2026-11-04 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,068 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,823 | 🐛 226 | 🌐 Go | 📅 2026-11-02

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,075 | 🐛 164 | 🌐 Rust | 📅 2026-11-04 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,603 | 🐛 131 | 🌐 Shell | 📅 2026-10-26

* [starship](https://github.com/starship/starship) ⭐ 60,636 | 🐛 1,066 | 🌐 Rust | 📅 2026-11-07 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,128 | 🐛 346 | 🌐 Rust | 📅 2026-11-06 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,481 | 🐛 1,953 | 🌐 Rust | 📅 2026-10-26 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,197 | 🐛 66 | 🌐 C | 📅 2026-11-06

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,970 | 🐛 1,932 | 🌐 Rust | 📅 2026-11-06 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,917 | 🐛 1,787 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,140 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,866 | 🐛 226 | 🌐 Rust | 📅 2026-10-27 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,934 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,056 | 🐛 429 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,691 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,713 | 🐛 1,067 | 🌐 Go | 📅 2026-11-07

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,633 | 🐛 358 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,670 | 🐛 120 | 🌐 Rust | 📅 2026-11-06 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,199 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,604 | 🐛 172 | 🌐 Rust | 📅 2026-11-02 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,861 | 🐛 5,267 | 🌐 Go | 📅 2026-11-07

* [SWC](https://github.com/swc-project/swc) ⭐ 34,209 | 🐛 396 | 🌐 Rust | 📅 2026-11-07 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,604 | 🐛 141 | 🌐 JavaScript | 📅 2026-11-07

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,727 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,586 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,834 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 50,915 | 🐛 2,280 | 🌐 Rust | 📅 2026-11-07 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,407 | 🐛 1,481 | 🌐 JavaScript | 📅 2026-11-06

* [dprint](https://github.com/dprint/dprint) ⭐ 4,129 | 🐛 35 | 🌐 Rust | 📅 2026-11-07 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,298 | 🐛 1,088 | 🌐 Haskell | 📅 2026-11-07

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,803 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,400 | 🐛 1,320 | 🌐 JavaScript | 📅 2026-11-07

* [Deno](https://github.com/denoland/deno) ⭐ 108,909 | 🐛 1,707 | 🌐 Rust | 📅 2026-10-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 78,074 | 🐛 9,274 | 🌐 Python | 📅 2026-11-07

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,460 | 🐛 313 | 🌐 Rust | 📅 2026-11-07 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,287 | 🐛 58 | 🌐 JavaScript | 📅 2026-11-06

* [mrml](https://github.com/jdrouet/mrml) ⭐ 513 | 🐛 34 | 🌐 HTML | 📅 2026-10-30 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,235 | 🐛 18,105 | 🌐 Python | 📅 2026-11-07

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,517 | 🐛 283 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,654 | 🐛 906 | 🌐 Java | 📅 2026-11-04

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,539 | 🐛 12 | 🌐 Rust | 📅 2026-11-07 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,608 | 🐛 2,747 | 🌐 Java | 📅 2026-11-06

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,406 | 🐛 514 | 🌐 Rust | 📅 2026-11-06 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-07._
