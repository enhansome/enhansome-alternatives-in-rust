# Awesome Alternatives in Rust with stars

[![github workflow status](https://img.shields.io/github/actions/workflow/status/TaKO8Ki/awesome-alternatives-in-rust/ci.yml?branch=main)](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/actions) ⭐ 4,107 | 🐛 35 | 🌐 Rust | 📅 2026-07-13

A curated list of replacements for existing software written in Rust.

If you want to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

I renamed the repository to "Awesome Alternatives in Rust". The original name was "Awesome Rewrite It In Rust". For more details, please refer to [this issue](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/issues/29) ⭐ 4,107 | 🐛 35 | 🌐 Rust | 📅 2026-07-13.

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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,422 | 🐛 349 | 🌐 Go | 📅 2026-08-28

* [youki](https://github.com/youki-dev/youki) ⭐ 7,573 | 🐛 150 | 🌐 Rust | 📅 2026-08-30 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,945 | 🐛 0 | 🌐 C | 📅 2026-08-30

* [pgrust](https://github.com/malisper/pgrust) ⭐ 4,769 | 🐛 15 | 🌐 Rust | 📅 2026-08-29 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 16,437 | 🐛 40 | 🌐 C++ | 📅 2026-08-29

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 431 | 🐛 11 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,882 | 🐛 6,016 | 🌐 Java | 📅 2026-08-30

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,557 | 🐛 804 | 🌐 Rust | 📅 2026-08-28 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,522 | 🐛 976 | 🌐 Java | 📅 2026-08-27

* [drill](https://github.com/fcsonline/drill) ⭐ 2,308 | 🐛 38 | 🌐 Rust | 📅 2026-07-29 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 39,039 | 🐛 139 | 🌐 Rust | 📅 2026-08-28 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,315 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,374 | 🐛 1,438 | 🌐 Rust | 📅 2026-08-30 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,656 | 🐛 60 | 🌐 Rust | 📅 2026-05-02 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 915 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 161 | 🐛 0 | 🌐 Rust | 📅 2026-08-02 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,305 | 🐛 421 | 🌐 Rust | 📅 2026-08-11 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,483 | 🐛 27 | 🌐 Perl | 📅 2026-08-08

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,859 | 🐛 243 | 🌐 Rust | 📅 2026-05-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,778 | 🐛 0 | 🌐 C | 📅 2026-08-30

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,794 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 930 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,267 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 744 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,010 | 🐛 432 | 🌐 Rust | 📅 2026-08-02 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,841 | 🐛 296 | 🌐 Rust | 📅 2026-08-28 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,691 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,196 | 🐛 8 | 🌐 Rust | 📅 2026-08-19 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,189 | 🐛 1 | 🌐 Rust | 📅 2026-08-30 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,248 | 🐛 197 | 🌐 Rust | 📅 2026-08-28 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 82,732 | 🐛 327 | 🌐 Go | 📅 2026-08-26

* [skim](https://github.com/skim-rs/skim) ⭐ 6,939 | 🐛 4 | 🌐 Rust | 📅 2026-08-22 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,275 | 🐛 15 | 🌐 C | 📅 2026-08-29

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,003 | 🐛 1,145 | 🌐 Rust | 📅 2026-08-30 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,263 | 🐛 34 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,470 | 🐛 336 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,042 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,088 | 🐛 441 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,203 | 🐛 205 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,263 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 94,786 | 🐛 397 | 🌐 Shell | 📅 2026-08-18

* [mise](https://github.com/jdx/mise) ⭐ 33,236 | 🐛 62 | 🌐 Rust | 📅 2026-08-30 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 26,733 | 🐛 241 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 963 | 🐛 686 | 🌐 C | 📅 2026-08-30

* [broot](https://github.com/Canop/broot) ⭐ 12,924 | 🐛 231 | 🌐 Rust | 📅 2026-08-30 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,150 | 🐛 42 | 🌐 Rust | 📅 2026-08-17 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,730 | 🐛 15 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 656 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 594 | 🐛 12 | 🌐 Rust | 📅 2026-03-21 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,730 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,336 | 🐛 77 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,045 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,466 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,765 | 🐛 96 | 🌐 Rust | 📅 2026-04-30 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 63,531 | 🐛 305 | 🌐 Markdown | 📅 2026-08-30

* [navi](https://github.com/denisidoro/navi) ⭐ 17,496 | 🐛 112 | 🌐 Rust | 📅 2026-07-28 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,473 | 🐛 14 | 🌐 Rust | 📅 2026-08-25 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,280 | 🐛 6 | 🌐 Rust | 📅 2026-07-26 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,951 | 🐛 107 | 🌐 Rust | 📅 2026-08-30 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,045 | 🐛 40 | 🌐 Rust | 📅 2026-08-25 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 265 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 570 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,716 | 🐛 210 | 🌐 Go | 📅 2026-08-22

* [paru](https://github.com/Morganamilo/paru) ⭐ 8,966 | 🐛 204 | 🌐 Rust | 📅 2026-01-09 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,568 | 🐛 130 | 🌐 Shell | 📅 2026-08-05

* [starship](https://github.com/starship/starship) ⭐ 59,670 | 🐛 1,043 | 🌐 Rust | 📅 2026-08-30 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 65,558 | 🐛 338 | 🌐 Rust | 📅 2026-08-26 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 28,641 | 🐛 1,830 | 🌐 Rust | 📅 2026-08-29 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 48,920 | 🐛 40 | 🌐 C | 📅 2026-08-30

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,194 | 🐛 1,881 | 🌐 Rust | 📅 2026-08-28 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,021 | 🐛 1,633 | 🌐 Rust | 📅 2026-08-25 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,126 | 🐛 95 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,716 | 🐛 183 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,925 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,519 | 🐛 473 | 🌐 C | 📅 2026-08-23

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,674 | 🐛 2 | 🌐 Rust | 📅 2026-03-18 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,775 | 🐛 1,026 | 🌐 Go | 📅 2026-08-30

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,449 | 🐛 343 | 🌐 Rust | 📅 2026-08-04 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 395 | 🐛 7 | 🌐 Rust | 📅 2026-02-17 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,573 | 🐛 128 | 🌐 Rust | 📅 2026-08-18 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,201 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 35,550 | 🐛 171 | 🌐 Rust | 📅 2026-08-20 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 110,786 | 🐛 5,174 | 🌐 Go | 📅 2026-08-29

* [SWC](https://github.com/swc-project/swc) ⭐ 34,190 | 🐛 413 | 🌐 Rust | 📅 2026-08-28 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,492 | 🐛 138 | 🌐 JavaScript | 📅 2026-08-29

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,730 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,584 | 🐛 166 | 🌐 Rust | 📅 2026-07-23 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,823 | 🐛 23 | 🌐 Python | 📅 2026-08-17

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,397 | 🐛 2,161 | 🌐 Rust | 📅 2026-08-30 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,222 | 🐛 1,418 | 🌐 JavaScript | 📅 2026-08-30

* [dprint](https://github.com/dprint/dprint) ⭐ 4,061 | 🐛 75 | 🌐 Rust | 📅 2026-08-30 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 39,962 | 🐛 1,138 | 🌐 Haskell | 📅 2026-08-04

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,800 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 119,959 | 🐛 1,199 | 🌐 JavaScript | 📅 2026-08-30

* [Deno](https://github.com/denoland/deno) ⭐ 108,345 | 🐛 1,546 | 🌐 Rust | 📅 2026-08-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 75,289 | 🐛 9,606 | 🌐 Python | 📅 2026-08-30

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,316 | 🐛 398 | 🌐 Rust | 📅 2026-08-30 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,214 | 🐛 69 | 🌐 JavaScript | 📅 2026-08-28

* [mrml](https://github.com/jdrouet/mrml) ⭐ 503 | 🐛 22 | 🌐 HTML | 📅 2026-08-11 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 102,680 | 🐛 17,472 | 🌐 Python | 📅 2026-08-30

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,481 | 🐛 248 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,573 | 🐛 586 | 🌐 Java | 📅 2026-08-26

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,507 | 🐛 45 | 🌐 Rust | 📅 2026-08-30 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,550 | 🐛 2,656 | 🌐 Java | 📅 2026-08-27

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,014 | 🐛 444 | 🌐 Rust | 📅 2026-08-28 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
