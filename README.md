# Awesome Alternatives in Rust with stars

[![github workflow status](https://img.shields.io/github/actions/workflow/status/TaKO8Ki/awesome-alternatives-in-rust/ci.yml?branch=main)](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/actions) ⭐ 4,119 | 🐛 38 | 🌐 Rust | 📅 2026-07-13

A curated list of replacements for existing software written in Rust.

If you want to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

I renamed the repository to "Awesome Alternatives in Rust". The original name was "Awesome Rewrite It In Rust". For more details, please refer to [this issue](https://github.com/TaKO8Ki/awesome-alternatives-in-rust/issues/29) ⭐ 4,119 | 🐛 38 | 🌐 Rust | 📅 2026-07-13.

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

#### [runc](https://github.com/opencontainers/runc) ⭐ 13,458 | 🐛 336 | 🌐 Go | 📅 2026-09-22

* [youki](https://github.com/youki-dev/youki) ⭐ 7,611 | 🐛 138 | 🌐 Rust | 📅 2026-09-22 - An experimental container runtime written in Rust

### Database

#### [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,178 | 🐛 0 | 🌐 C | 📅 2026-09-22

* [pgrust](https://github.com/malisper/pgrust) ⭐ 5,113 | 🐛 6 | 🌐 Rust | 📅 2026-09-18 - Postgres rewritten in Rust, now passing 100% of the Postgres regression tests

### Games

#### [Stockfish](https://github.com/official-stockfish/Stockfish/) ⭐ 16,698 | 🐛 38 | 🌐 C++ | 📅 2026-09-22

* [Pleco](https://github.com/pleco-rs/Pleco) ⭐ 432 | 🐛 11 | 🌐 Rust | 📅 2026-02-22 - A Rust-based re-write of the Stockfish Chess Engine

### Observability

#### [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,962 | 🐛 6,060 | 🌐 Java | 📅 2026-09-22

* [Quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,665 | 🐛 812 | 🌐 Rust | 📅 2026-09-22 - A cloud-native search engine for observability written in Rust

### Performance

#### [jMeter](https://github.com/apache/jmeter) ⭐ 9,542 | 🐛 980 | 🌐 Java | 📅 2026-09-12

* [drill](https://github.com/fcsonline/drill) ⭐ 2,311 | 🐛 39 | 🌐 Rust | 📅 2026-09-03 - A HTTP load testing application written in Rust

### System tools

#### autojump / z

* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 39,655 | 🐛 146 | 🌐 Rust | 📅 2026-09-21 - A smarter cd command for your terminal.

#### awk

* [frawk](https://github.com/ezrosent/frawk) ⭐ 1,317 | 🐛 35 | 🌐 Rust | 📅 2025-09-26 - an efficient awk-like language

#### bash/PowerShell/fish

* [nushell](https://github.com/nushell/nushell/) ⭐ 40,551 | 🐛 1,433 | 🌐 Rust | 📅 2026-09-22 - An attractive structured shell
* [ion](https://github.com/redox-os/ion) ⭐ 1,655 | 🐛 60 | 🌐 Rust | 📅 2026-09-19 - A modern shell developed for RedoxOS. But is still capable on \*nix platforms.

#### bc

* [eva](https://github.com/oppiliappan/eva) ⭐ 913 | 🐛 13 | 🌐 Rust | 📅 2025-07-31 - a calculator REPL, similar to bc(1)
* [cpc](https://github.com/probablykasper/cpc) ⭐ 162 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - Text calculator with support for units and conversion

#### cat

* [bat](https://github.com/sharkdp/bat) ⭐ 60,546 | 🐛 517 | 🌐 Rust | 📅 2026-09-22 - A cat(1) clone with wings.

#### [cloc](https://github.com/AlDanial/cloc) ⭐ 23,554 | 🐛 26 | 🌐 Perl | 📅 2026-09-20

* [tokei](https://github.com/XAMPPRocky/tokei) ⭐ 14,932 | 🐛 245 | 🌐 Rust | 📅 2026-09-06 - Count your code, quickly.

#### [coreboot](https://github.com/coreboot/coreboot) ⭐ 2,794 | 🐛 0 | 🌐 C | 📅 2026-09-22

* [oreboot](https://github.com/oreboot/oreboot) ⭐ 1,797 | 🐛 64 | 🌐 Rust | 📅 2026-07-13 - oreboot is a fork of coreboot, with C removed, written in Rust.

#### cp

* [xcp](https://github.com/tarka/xcp) ⭐ 929 | 🐛 18 | 🌐 Rust | 📅 2026-06-23 - An extended `cp`

#### cut

* [choose](https://github.com/theryangeary/choose) ⭐ 2,280 | 🐛 5 | 🌐 Rust | 📅 2026-06-11 - A human-friendly and fast alternative to cut and (sometimes) awk
* [hck](https://github.com/sstadick/hck) ⭐ 744 | 🐛 7 | 🌐 Rust | 📅 2026-06-15 - A sharp cut(1) clone

#### diff

* [delta](https://github.com/dandavison/delta) ⭐ 32,304 | 🐛 446 | 🌐 Rust | 📅 2026-09-19 - A viewer for git and diff output
* [difftastic](https://github.com/Wilfred/difftastic) ⭐ 25,921 | 🐛 286 | 🌐 Rust | 📅 2026-09-22 - A structural diff that understands syntax

#### dig

* [dog](https://github.com/ogham/dog) ⭐ 6,692 | 🐛 78 | 🌐 Rust | 📅 2024-05-29 - A command-line DNS client.

#### du

* [dust](https://github.com/bootandy/dust) ⭐ 12,290 | 🐛 9 | 🌐 Rust | 📅 2026-09-16 - A more intuitive version of du in rust
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,291 | 🐛 0 | 🌐 Rust | 📅 2026-09-22 - View disk space usage and delete unwanted data, fast.

#### find

* [fd](https://github.com/sharkdp/fd) ⭐ 44,519 | 🐛 199 | 🌐 Rust | 📅 2026-09-20 - A simple, fast and user-friendly alternative to 'find'

#### [fzf](https://github.com/junegunn/fzf) ⭐ 83,196 | 🐛 330 | 🌐 Go | 📅 2026-09-21

* [skim](https://github.com/skim-rs/skim) ⭐ 6,968 | 🐛 5 | 🌐 Rust | 📅 2026-09-21 - Fuzzy Finder in rust!

#### [GNU coreutils](https://github.com/coreutils/coreutils) ⭐ 5,300 | 🐛 15 | 🌐 C | 📅 2026-09-22

* [coreutils](https://github.com/uutils/coreutils) ⭐ 24,152 | 🐛 1,169 | 🌐 Rust | 📅 2026-09-22 - Cross-platform Rust rewrite of the GNU coreutils

#### hexdump

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,282 | 🐛 36 | 🌐 Rust | 📅 2026-04-30 - A command-line hex viewer

#### [httpie](https://github.com/httpie/cli) ⭐ 38,561 | 🐛 336 | 🌐 Python | 📅 2024-12-17

* [xh](https://github.com/ducaale/xh) ⭐ 8,088 | 🐛 37 | 🌐 Rust | 📅 2026-09-05 - Friendly and fast tool for sending HTTP requests

#### ls

* [eza](https://github.com/eza-community/eza) ⭐ 23,342 | 🐛 454 | 🌐 Rust | 📅 2026-08-06 - A replacement for 'ls'
* [lsd](https://github.com/lsd-rs/lsd) ⭐ 16,238 | 🐛 210 | 🌐 Rust | 📅 2026-08-17 - An ls with a lot of pretty colors and awesome icons
* [nat](https://github.com/willdoescode/nat) ⭐ 1,265 | 🐛 0 | 🌐 Rust | 📅 2021-05-28 - `ls` alternative with useful info and a splash of color 🎨

#### [nvm](https://github.com/nvm-sh/nvm) ⭐ 95,165 | 🐛 390 | 🌐 Shell | 📅 2026-09-21

* [mise](https://github.com/jdx/mise) ⭐ 34,197 | 🐛 68 | 🌐 Rust | 📅 2026-09-22 - dev tools, env vars, task runner
* [fnm](https://github.com/Schniz/fnm) ⭐ 26,924 | 🐛 248 | 🌐 Rust | 📅 2026-07-24 - 🚀 Fast and simple Node.js version manager, built in Rust

#### [Midnight Commander](https://github.com/MidnightCommander/mc) ⭐ 986 | 🐛 695 | 🌐 C | 📅 2026-09-16

* [broot](https://github.com/Canop/broot) ⭐ 12,956 | 🐛 100 | 🌐 Rust | 📅 2026-09-20 - A better way to navigate directories

#### ps

* [procs](https://github.com/dalance/procs) ⭐ 6,182 | 🐛 36 | 🌐 Rust | 📅 2026-09-16 - A modern replacement for ps written in Rust

#### [rbenv](https://github.com/rbenv/rbenv) ⭐ 16,733 | 🐛 17 | 🌐 Shell | 📅 2026-07-14

* [frum](https://github.com/TaKO8Ki/frum) ⭐ 655 | 🐛 36 | 🌐 Rust | 📅 2022-05-13 - A little bit fast and modern Ruby version manager written in Rust

#### rename

* [rnr](https://github.com/ismaelgv/rnr) ⭐ 597 | 🐛 12 | 🌐 Rust | 📅 2026-03-21 - A command-line tool to batch rename files and directories

#### rm

* [rip](https://github.com/nivekuil/rip) ⭐ 1,737 | 🐛 26 | 🌐 Rust | 📅 2024-04-08 - A safe and ergonomic alternative to rm

#### sed

* [sd](https://github.com/chmln/sd) ⭐ 7,360 | 🐛 79 | 🌐 Rust | 📅 2026-02-25 - Intuitive find & replace CLI (sed alternative)
* [sad](https://github.com/ms-jpq/sad) ⭐ 2,044 | 🐛 28 | 🌐 Rust | 📅 2026-05-11 - CLI search and replace | Space Age seD

#### strings

* [stringsext](https://github.com/getreu/stringsext) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-06-24 - Find multi-byte-encoded strings in binary data

#### sudo

* [please](https://gitlab.com/edneville/please) - `sudo` like program with regex support written in rust

#### sysctl

* [systeroid](https://github.com/orhun/systeroid) ⭐ 1,470 | 🐛 17 | 🌐 Rust | 📅 2026-07-30 - A more powerful alternative to `sysctl` with a terminal user interface

#### time

* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,893 | 🐛 100 | 🌐 Rust | 📅 2026-04-30 - A command-line benchmarking tool

#### [tldr](https://github.com/tldr-pages/tldr) ⭐ 63,717 | 🐛 303 | 🌐 Markdown | 📅 2026-09-22

* [navi](https://github.com/denisidoro/navi) ⭐ 17,611 | 🐛 110 | 🌐 Rust | 📅 2026-09-20 - An interactive cheatsheet tool for the command-line
* [tealdeer](https://github.com/tealdeer-rs/tealdeer) ⭐ 6,538 | 🐛 15 | 🌐 Rust | 📅 2026-08-25 - A very fast implementation of tldr in Rust.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,290 | 🐛 6 | 🌐 Rust | 📅 2026-07-26 - Like IntelliSense, but for shells

#### top

* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,041 | 🐛 104 | 🌐 Rust | 📅 2026-09-22 - Yet another cross-platform graphical process/system monitor.
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,054 | 🐛 40 | 🌐 Rust | 📅 2026-09-02 - A terminal system monitor with zoomable charts
* [ytop](https://github.com/cjbassi/ytop) ⚠️ Archived (no longer maintained) - A TUI system monitor written in Rust

#### uniq

* [huniq](https://github.com/koraa/huniq) ⭐ 265 | 🐛 10 | 🌐 Rust | 📅 2024-01-26 - Filter out duplicates on the command line.

#### xargs

* [rargs](https://github.com/lotabout/rargs) ⭐ 571 | 🐛 12 | 🌐 Rust | 📅 2023-07-30 - A kind of xargs + awk with pattern-matching support.

#### [yay](https://github.com/Jguer/yay) ⭐ 13,760 | 🐛 212 | 🌐 Go | 📅 2026-09-22

* [paru](https://github.com/Morganamilo/paru) ⭐ 8,993 | 🐛 205 | 🌐 Rust | 📅 2026-01-09 - Feature packed AUR helper

### Terminal

#### [Spaceship](https://github.com/spaceship-prompt/spaceship-prompt) ⭐ 20,574 | 🐛 131 | 🌐 Shell | 📅 2026-09-02

* [starship](https://github.com/starship/starship) ⭐ 59,996 | 🐛 1,055 | 🌐 Rust | 📅 2026-09-21 - ☄️🌌 The minimal, blazing-fast, and infinitely customizable prompt for any shell!

#### [termite](https://github.com/thestinger/termite) ⚠️ Archived

* [Alacritty](https://github.com/alacritty/alacritty) ⭐ 65,787 | 🐛 342 | 🌐 Rust | 📅 2026-08-31 - A cross-platform, OpenGL terminal emulator.
* [WezTerm](https://github.com/wezterm/wezterm) ⭐ 28,985 | 🐛 1,873 | 🌐 Rust | 📅 2026-09-21 - A GPU-accelerated cross-platform terminal emulator and multiplexer

#### [tmux](https://github.com/tmux/tmux) ⭐ 49,430 | 🐛 40 | 🌐 C | 📅 2026-09-22

* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,506 | 🐛 1,936 | 🌐 Rust | 📅 2026-09-22 - A terminal workspace with batteries included

### Text editors

#### Vim

* [Helix](https://github.com/helix-editor/helix) ⭐ 46,302 | 🐛 1,682 | 🌐 Rust | 📅 2026-09-15 - A post-modern modal text editor
* [Amp](https://github.com/jmacdonald/amp) ⭐ 4,127 | 🐛 95 | 🌐 Rust | 📅 2026-06-10 - A complete text editor for your terminal.

### Text processing

#### grep

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 68,507 | 🐛 200 | 🌐 Rust | 📅 2026-08-04 - ripgrep recursively searches directories for a regex pattern while respecting your gitignore

### Utilities

#### [codemod](https://github.com/facebookarchive/codemod) ⚠️ Archived

* [fastmod](https://github.com/facebookincubator/fastmod) ⭐ 1,927 | 🐛 16 | 🌐 Rust | 📅 2026-07-28 - A fast partial replacement for the codemod tool

#### [jq](https://github.com/jqlang/jq) ⭐ 35,665 | 🐛 450 | 🌐 C | 📅 2026-09-19

* [jql](https://github.com/yamafaktory/jql) ⭐ 1,682 | 🐛 0 | 🌐 Rust | 📅 2026-09-08 - A JSON Query Language CLI tool built with Rust 🦀

#### [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 82,579 | 🐛 1,051 | 🌐 Go | 📅 2026-09-22

* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,514 | 🐛 347 | 🌐 Rust | 📅 2026-08-04 - Blazing fast terminal-ui for git written in Rust 🦀

#### [Toggl Track](https://github.com/toggl/toggldesktop) ⭐ 126 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-30

* [Furtherance](https://github.com/unobserved-io/Furtherance) ⭐ 393 | 🐛 8 | 🌐 Rust | 📅 2026-02-17 - Time-tracking app written in Rust

### Web

#### Reddit

* [Lemmy](https://github.com/LemmyNet/lemmy) ⭐ 14,606 | 🐛 124 | 🌐 Rust | 📅 2026-09-22 - 🐀 Building a federated alternative to reddit in rust

#### [teddit](https://codeberg.org/teddit/teddit)

* [libreddit](https://github.com/libreddit/libreddit) ⭐ 5,200 | 🐛 196 | 🌐 Rust | 📅 2025-02-15 - Private front-end for Reddit written in Rust

## Development tools

### Command runners

#### make

* [just](https://github.com/casey/just) ⭐ 35,958 | 🐛 171 | 🌐 Rust | 📅 2026-09-22 - A command runner and partial replacement for `make`

### Compilers

#### [TypeScript Compiler](https://github.com/microsoft/TypeScript) ⭐ 111,163 | 🐛 5,005 | 🌐 Go | 📅 2026-09-22

* [SWC](https://github.com/swc-project/swc) ⭐ 34,206 | 🐛 441 | 🌐 Rust | 📅 2026-09-22 - A Rust-based platform for the web

### Linters

#### [ESLint](https://github.com/eslint/eslint) ⭐ 27,516 | 🐛 126 | 🌐 JavaScript | 📅 2026-09-22

* [RSLint](https://github.com/rslint/rslint) ⭐ 2,730 | 🐛 41 | 🌐 Rust | 📅 2023-03-05 - A (WIP) Extremely fast JavaScript and TypeScript linter and Rust crate
* [deno\_lint](https://github.com/denoland/deno_lint) ⭐ 1,583 | 🐛 166 | 🌐 Rust | 📅 2026-07-23 - Blazing fast linter for JavaScript and TypeScript written in Rust

#### [Flake8](https://github.com/PyCQA/flake8) ⭐ 3,823 | 🐛 23 | 🌐 Python | 📅 2026-08-17

* [Ruff](https://github.com/astral-sh/ruff) ⭐ 49,731 | 🐛 2,195 | 🌐 Rust | 📅 2026-09-22 - An extremely fast Python linter and code formatter written in Rust

#### [Prettier](https://github.com/prettier/prettier) ⭐ 52,295 | 🐛 1,444 | 🌐 JavaScript | 📅 2026-09-22

* [dprint](https://github.com/dprint/dprint) ⭐ 4,079 | 🐛 68 | 🌐 Rust | 📅 2026-09-15 - Pluggable and configurable code formatting platform written in Rust.

#### [ShellCheck](https://github.com/koalaman/shellcheck) ⭐ 40,068 | 🐛 1,134 | 🌐 Haskell | 📅 2026-09-21

* [Shellharden](https://github.com/anordal/shellharden) ⭐ 4,806 | 🐛 10 | 🌐 Rust | 📅 2026-07-09 - The corrective bash syntax highlighter

### Runtimes

#### [Node.js](https://github.com/nodejs/node) ⭐ 122,037 | 🐛 1,183 | 🌐 JavaScript | 📅 2026-09-22

* [Deno](https://github.com/denoland/deno) ⭐ 108,476 | 🐛 1,608 | 🌐 Rust | 📅 2026-09-22 - A modern runtime for JavaScript and TypeScript written in Rust

#### [Python](https://github.com/python/cpython) ⭐ 77,237 | 🐛 9,711 | 🌐 Python | 📅 2026-09-22

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,351 | 🐛 397 | 🌐 Rust | 📅 2026-09-22 - A Python interpreter written in Rust

## Libraries

### Email

#### [mjml](https://github.com/mjmlio/mjml) ⭐ 18,244 | 🐛 56 | 🌐 JavaScript | 📅 2026-09-10

* [mrml](https://github.com/jdrouet/mrml) ⭐ 507 | 🐛 26 | 🌐 HTML | 📅 2026-09-13 - Blazing fast reimplementation of mjml in Rust (\~200x faster)

### Machine learning

#### [PyTorch](https://github.com/pytorch/pytorch) ⭐ 103,177 | 🐛 17,584 | 🌐 Python | 📅 2026-09-22

* [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,490 | 🐛 248 | 🌐 Rust | 📅 2026-08-23 - Rust bindings for the C++ API of PyTorch

### Message queues

#### [Apache RocketMQ](https://github.com/apache/rocketmq) ⭐ 22,613 | 🐛 683 | 🌐 Java | 📅 2026-09-22

* [rocketmq-rust](https://github.com/mxsm/rocketmq-rust) ⭐ 1,521 | 🐛 23 | 🌐 Rust | 📅 2026-09-22 - An Apache RocketMQ implementation written in Rust

### Search

#### [Apache Lucene](https://github.com/apache/lucene) ⭐ 3,564 | 🐛 2,669 | 🌐 Java | 📅 2026-09-21

* [Tantivy](https://github.com/quickwit-oss/tantivy) ⭐ 16,126 | 🐛 458 | 🌐 Rust | 📅 2026-09-22 - A full-text search engine library inspired by Apache Lucene and written in Rust

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-22._
