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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,527 | 🐛 203 | 📅 2026-11-04

* [youki](https://github.com/youki-dev/youki) ⭐ 7,668 | 🐛 177 | 🌐 Rust | 📅 2026-11-04 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,708 | 🐛 0 | 🌐 C | 📅 2026-11-04

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,749 | 🐛 58 | 🌐 Rust | 📅 2026-10-26 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 17,239 | 🐛 63 | 🌐 C++ | 📅 2026-10-28

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 430 | 🐛 10 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,487 | 🐛 6,347 | 🌐 Java | 📅 2026-11-04

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,765 | 🐛 857 | 🌐 Rust | 📅 2026-11-04 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,590 | 🐛 992 | 🌐 Java | 📅 2026-11-04

* [drill](https://github.com/fcsonline/drill) ⭐ 2,313 | 🐛 42 | 🌐 Rust | 📅 2026-10-13 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 40,455 | 🐛 162 | 🌐 Rust | 📅 2026-11-01 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,318 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,769 | 🐛 1,443 | 🌐 Rust | 📅 2026-11-04 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,659 | 🐛 60 | 🌐 Rust | 📅 2026-11-03 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 918 | 🐛 14 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 166 | 🐛 0 | 🌐 Rust | 📅 2026-10-06 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 61,066 | 🐛 565 | 🌐 Rust | 📅 2026-11-04 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,646 | 🐛 26 | 🌐 Perl | 📅 2026-10-26

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 15,041 | 🐛 255 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,825 | 🐛 0 | 🌐 C | 📅 2026-11-03

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,805 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 932 | 🐛 17 | 🌐 Rust | 📅 2026-10-27 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,290 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 745 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,660 | 🐛 502 | 🌐 Rust | 📅 2026-10-28 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 26,152 | 🐛 285 | 🌐 Rust | 📅 2026-11-04 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,691 | 🐛 79 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,576 | 🐛 10 | 🌐 Rust | 📅 2026-11-01 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,410 | 🐛 0 | 🌐 Rust | 📅 2026-11-03 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,947 | 🐛 209 | 🌐 Rust | 📅 2026-11-04 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 84,017 | 🐛 336 | 🌐 Go | 📅 2026-11-04

* [skim](https://github.com/skim-rs/skim) ⭐ 7,004 | 🐛 9 | 🌐 Rust | 📅 2026-11-02 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,354 | 🐛 15 | 🌐 C | 📅 2026-11-04

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,329 | 🐛 1,419 | 🌐 Rust | 📅 2026-11-04 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,301 | 🐛 43 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,695 | 🐛 362 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,170 | 🐛 41 | 🌐 Rust | 📅 2026-10-29 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,781 | 🐛 478 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,283 | 🐛 218 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,266 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,756 | 🐛 372 | 🌐 Shell | 📅 2026-11-04

* [mise](https://github.com/jdx/mise) ⭐ 35,771 | 🐛 43 | 🌐 Rust | 📅 2026-11-04 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 27,295 | 🐛 257 | 🌐 Rust | 📅 2026-10-26 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 1,036 | 🐛 708 | 🌐 C | 📅 2026-11-04

* [broot](https://github.com/Canop/broot) ⭐ 13,130 | 🐛 103 | 🌐 Rust | 📅 2026-11-01 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,216 | 🐛 43 | 🌐 Rust | 📅 2026-11-02 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,739 | 🐛 20 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 604 | 🐛 12 | 🌐 Rust | 📅 2026-10-05 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,736 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,409 | 🐛 87 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,050 | 🐛 28 | 🌐 Rust | 📅 2026-11-02 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,474 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 29,205 | 🐛 76 | 🌐 Rust | 📅 2026-11-01 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 64,122 | 🐛 284 | 🌐 Markdown | 📅 2026-11-04

* [navi](https://github.com/denisidoro/navi) ⭐ 17,835 | 🐛 130 | 🌐 Rust | 📅 2026-10-16 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,641 | 🐛 20 | 🌐 Rust | 📅 2026-10-24 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,303 | 🐛 5 | 🌐 Rust | 📅 2026-10-28 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,157 | 🐛 103 | 🌐 Rust | 📅 2026-11-04 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,068 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 264 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 573 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,819 | 🐛 223 | 🌐 Go | 📅 2026-11-02

* [paru](https://github.com/Morganamilo/paru) ⭐ 9,075 | 🐛 165 | 🌐 Rust | 📅 2026-11-04 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,602 | 🐛 131 | 🌐 Shell | 📅 2026-10-26

* [starship](https://github.com/starship/starship) ⭐ 60,603 | 🐛 1,063 | 🌐 Rust | 📅 2026-11-04 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 66,113 | 🐛 345 | 🌐 Rust | 📅 2026-11-02 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 29,448 | 🐛 1,954 | 🌐 Rust | 📅 2026-10-26 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 50,152 | 🐛 47 | 🌐 C | 📅 2026-11-03

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,940 | 🐛 1,929 | 🌐 Rust | 📅 2026-11-04 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,784 | 🐛 1,781 | 🌐 Rust | 📅 2026-09-29 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,136 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 69,698 | 🐛 218 | 🌐 Rust | 📅 2026-10-27 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,934 | 🐛 17 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 36,036 | 🐛 424 | 🌐 C | 📅 2026-11-02

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,691 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 83,651 | 🐛 1,066 | 🌐 Go | 📅 2026-11-04

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,618 | 🐛 358 | 🌐 Rust | 📅 2026-10-06 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 394 | 🐛 6 | 🌐 Rust | 📅 2026-09-29 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,665 | 🐛 117 | 🌐 Rust | 📅 2026-11-04 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,199 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 36,568 | 🐛 173 | 🌐 Rust | 📅 2026-11-02 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,730 | 🐛 5,248 | 🌐 Go | 📅 2026-11-04

* [SWC](https://github.com/swc-project/swc) ⭐ 34,209 | 🐛 418 | 🌐 Rust | 📅 2026-11-04 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,604 | 🐛 137 | 🌐 JavaScript | 📅 2026-11-04

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,727 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,586 | 🐛 169 | 🌐 Rust | 📅 2026-09-25 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,831 | 🐛 24 | 🌐 Python | 📅 2026-11-04

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 50,432 | 🐛 2,290 | 🌐 Rust | 📅 2026-11-04 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,402 | 🐛 1,481 | 🌐 JavaScript | 📅 2026-11-04

* [dprint](https://github.com/dprint/dprint) ⭐ 4,126 | 🐛 35 | 🌐 Rust | 📅 2026-11-04 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,282 | 🐛 1,091 | 🌐 Haskell | 📅 2026-10-26

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,806 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 123,232 | 🐛 1,313 | 🌐 JavaScript | 📅 2026-11-04

* [Deno](https://github.com/denoland/deno) ⭐ 108,806 | 🐛 1,686 | 🌐 Rust | 📅 2026-10-29 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,875 | 🐛 9,250 | 🌐 Python | 📅 2026-11-04

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,453 | 🐛 406 | 🌐 Rust | 📅 2026-11-04 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,282 | 🐛 56 | 🌐 JavaScript | 📅 2026-11-03

* [mrml](https://github.com/jdrouet/mrml) ⭐ 513 | 🐛 34 | 🌐 HTML | 📅 2026-10-30 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 105,133 | 🐛 17,947 | 🌐 Python | 📅 2026-11-04

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,515 | 🐛 281 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,650 | 🐛 906 | 🌐 Java | 📅 2026-11-04

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,536 | 🐛 13 | 🌐 Rust | 📅 2026-11-04 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,606 | 🐛 2,735 | 🌐 Java | 📅 2026-11-04

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,400 | 🐛 508 | 🌐 Rust | 📅 2026-11-02 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-04._
