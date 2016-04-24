# Awesome Rust

A curated list of Rust code and resources, inspired by other awesome lists.
The goal is to have only projects that are mostly stable and useful to users.

If you want to contribute, please read [this](CONTRIBUTING.md).

- [Awesome Rust](#awesome-rust)
  - [Applications written in Rust](#applications-written-in-rust)
    - [Games](#games)
    - [Operating systems](#operating-systems)
    - [System tools](#system-tools)
  - [Development Tools](#development-tools)
    - [Debugging](#debugging)
    - [Embedded](#embedded)
    - [FFI](#ffi)
    - [IDEs](#ides)
    - [Profiling](#profiling)
    - [Testing](#testing)
  - [Libraries](#libraries)
    - [Astronomy](#astronomy)
    - [Asynchronous](#asynchronous)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Bioinformatics](#bioinformatics)
    - [Build system](#build-system)
    - [Caching](#caching)
    - [Cloud](#cloud)
    - [Command-line argument parsing](#command-line-argument-parsing)
    - [Command-line interface](#command-line-interface)
    - [Compression](#compression)
    - [Computation](#computation)
    - [Concurrency](#concurrency)
    - [Cryptography](#cryptography)
    - [Database](#database)
    - [Data structures](#data-structures)
    - [Date and time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Encoding](#encoding)
    - [Game development](#game-development)
    - [Games](#games)
    - [Geospatial](#geospatial)
    - [GUI](#gui)
    - [Image processing](#image-processing)
    - [Machine learning](#machine-learning)
    - [Markup language](#markup-language)
    - [Mobile](#mobile)
    - [Network programming](#network-programming)
    - [Parser](#parser)
    - [Platform specific](#platform-specific)
    - [Template engine](#template-engine)
    - [Text processing](#text-processing)
    - [Virtualization](#virtualization)
    - [Web programming](#web-programming)
  - [Resources](#resources)
  - [License](#license)

## Applications written in Rust

* [azerupi/mdBook](https://github.com/azerupi/mdBook) — a command line utility to create books from markdown files [<img src="https://travis-ci.org/azerupi/mdBook.svg?branch=master">](https://travis-ci.org/azerupi/mdBook)
* [bluejekyll/trust-dns](https://github.com/bluejekyll/trust-dns) — a DNS-server [<img src="https://travis-ci.org/bluejekyll/trust-dns.svg?branch=master">](https://travis-ci.org/bluejekyll/trust-dns)
* [BurntSushi/xsv](https://github.com/BurntSushi/xsv) — a fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.) [<img src="https://travis-ci.org/BurntSushi/xsv.svg?branch=master">](https://travis-ci.org/BurntSushi/xsv)
* Emulators
  * [simias/rustation](https://github.com/simias/rustation) — a Playstation emulator [<img src="https://travis-ci.org/simias/rustation.svg?branch=master">](https://travis-ci.org/simias/rustation)
* [gchp/iota](https://github.com/gchp/iota) — a simple text editor [<img src="https://travis-ci.org/gchp/iota.svg?branch=master">](https://travis-ci.org/gchp/iota)
* [dlecan/generic-dns-update](https://github.com/dlecan/generic-dns-update) — a tool to update DNS zonefiles with your IP address [<img src="https://travis-ci.org/dlecan/generic-dns-update.svg?branch=master">](https://travis-ci.org/dlecan/generic-dns-update)
* [Factotum](https://github.com/snowplow/factotum) - [A system to programmatically run data pipelines](http://snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [<img src="https://travis-ci.org/snowplow/factotum.svg?branch=master">](https://travis-ci.org/snowplow/factotum)
* [Fractalide](https://github.com/fractalide/fractalide) — Flow-based Programming environment.
* [imjacobclark/Herd](https://github.com/imjacobclark/Herd) — an experimental HTTP load testing application
* [jedisct1/flowgger](https://github.com/jedisct1/flowgger) — a fast, simple and lightweight data collector
* [kbknapp/docli](https://github.com/kbknapp/docli-rs) — a command line utility for managing DigitalOcean infrastructure [<img src="https://travis-ci.org/kbknapp/docli-rs.svg?branch=master">](https://travis-ci.org/kbknapp/docli-rs)
* [MaidSafe](http://maidsafe.net/) — a decentralized platform.
* [qmx/limonite](https://github.com/qmx/limonite) — static blog/website generator [<img src="https://travis-ci.org/qmx/limonite.svg?branch=master">](https://travis-ci.org/qmx/limonite)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — a Redis reimplementation [<img src="https://travis-ci.org/seppo0010/rsedis.svg?branch=master">](https://travis-ci.org/seppo0010/rsedis)
* [Servo](https://github.com/servo/servo) — a prototype web browser engine
* Virtualization
  * [tailhook/vagga](https://github.com/tailhook/vagga) — a containerization tool without daemons [<img src="https://travis-ci.org/tailhook/vagga.svg?branch=master">](https://travis-ci.org/tailhook/vagga)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) — a configurable watcher inspired in [entr](http://entrproject.org/) [<img src="https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master">](https://travis-ci.org/cristianoliveira/funzzy)

### Games

See also [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — a minimalistic music video game which supports the BMS format [<img src="https://travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master">](https://travis-ci.org/lifthrasiir/angolmois-rust)
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — a Sokoban implementation
* [Zone of Control](https://github.com/ozkriff/zoc) — a turn-based hexagonal strategy game [<img src="https://travis-ci.org/ozkriff/zoc.svg?branch=master">](https://travis-ci.org/ozkriff/zoc)
* [rhex](https://github.com/dpc/rhex) — hexagonal ascii roguelike

### Operating systems

[A comparison of operating systems written in Rust](https://github.com/flosse/rust-os-comparison)

* [redox-os/redox](https://github.com/redox-os/redox) — [<img src="https://travis-ci.org/redox-os/redox.svg?branch=master">](https://travis-ci.org/redox-os/redox)
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) — [<img src="https://travis-ci.org/thepowersgang/rust_os.svg?branch=master">](https://travis-ci.org/thepowersgang/rust_os)

### System tools

* [Aaronepower/tokei](https://github.com/Aaronepower/tokei) — counts the lines of code [<img src="https://img.shields.io/travis/Aaronepower/tokei.svg">](https://travis-ci.org/Aaronepower/tokei)
* [buster/rrun](https://github.com/buster/rrun) — a command launcher for Linux, similar to gmrun  [<img src="https://travis-ci.org/buster/rrun.svg?branch=master">](https://travis-ci.org/buster/rrun)
* [ogham/exa](https://github.com/ogham/exa) — a replacement for 'ls' written in Rust [<img src="https://travis-ci.org/ogham/exa.svg?branch=master">](https://travis-ci.org/ogham/exa)
* [mmstick/systemd-manager](https://github.com/mmstick/systemd-manager) -- a systemd service manager written in Rust using GTK-rs.
* [uutils/coreutils](https://github.com/uutils/coreutils) — a cross-platform Rust rewrite of the GNU coreutils [<img src="https://travis-ci.org/uutils/coreutils.svg?branch=master">](https://travis-ci.org/uutils/coreutils)


## Development tools

* [Clippy](https://github.com/Manishearth/rust-clippy) — Rust lints [<img src="https://travis-ci.org/Manishearth/rust-clippy.svg?branch=master">](https://travis-ci.org/Manishearth/rust-clippy)
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) — generates a changelog from git metadata ([conventional changelog](http://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [<img src="https://travis-ci.org/clog-tool/clog-cli.svg?branch=master">](https://travis-ci.org/clog-tool/clog-cli)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — create ctags/etags for a cargo project and all of its dependencies [<img src="https://travis-ci.org/dan-t/rusty-tags.svg?branch=master">](https://travis-ci.org/dan-t/rusty-tags)
* [frewsxcv/crate-deps](https://github.com/frewsxcv/crate-deps) — generates images of dependency graphs for crates hosted on crates.io
* Multirust — manage multiple Rust installations
  * [brson/multirust](https://github.com/brson/multirust) — the original multirust as shell scripts [<img src="https://travis-ci.org/brson/multirust.svg?branch=master">](https://travis-ci.org/brson/multirust)
  * [Diggsey/multirust-rs](https://github.com/Diggsey/multirust-rs) — multirust reimplementation in Rust [<img src="https://travis-ci.org/Diggsey/multirust-rs.svg?branch=master">](https://travis-ci.org/Diggsey/multirust-rs)
* [Racer](https://github.com/phildawes/racer) — code completion for Rust [<img src="https://travis-ci.org/phildawes/racer.svg?branch=master">](https://travis-ci.org/phildawes/racer)
* [rustfmt](https://github.com/rust-lang-nursery/rustfmt) — a Rust code formatter [<img src="https://travis-ci.org/rust-lang-nursery/rustfmt.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/rustfmt)

### Debugging

* GDB
  * [rust-gdb](https://github.com/rust-lang/rust/blob/master/src/etc/rust-gdb)
* LLDB
  * [lldb_batchmode.py](https://github.com/rust-lang/rust/blob/master/src/etc/lldb_batchmode.py) — allows to use LLDB in a way similar to GDB's batch mode.


### Embedded

* Cross compiling
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) — everything you need to know about cross compiling Rust programs [<img src="https://travis-ci.org/japaric/rust-cross.svg?branch=master">](https://travis-ci.org/japaric/rust-cross)
* Raspberry Pi
  * [Ogeon/rust-on-raspberry-pi](https://github.com/Ogeon/rust-on-raspberry-pi) — instructions for how to cross compile Rust projects for the Raspberry Pi .


### FFI

See also [Foreign Function Interface](https://doc.rust-lang.org/book/ffi.html), [Rust Inside Other Languages](https://doc.rust-lang.org/book/rust-inside-other-languages.html) and [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages).

* C
  * [crabtw/rust-bindgen](https://github.com/crabtw/rust-bindgen) — a Rust bindings generator [<img src="https://travis-ci.org/crabtw/rust-bindgen.svg?branch=master">](https://travis-ci.org/crabtw/rust-bindgen)
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files [<img src="https://travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master">](https://travis-ci.org/Sean1708/rusty-cheddar)
* Erlang
  * [hansihe/Rustler](https://github.com/hansihe/Rustler) - Safe Rust bridge for creating Erlang NIF functions [<img src="https://travis-ci.org/hansihe/Rustler.svg?branch=master">](https://travis-ci.org/hansihe/Rustler)
* Java
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — use Rust from Java [<img src="https://travis-ci.org/drrb/java-rust-example.svg?branch=master">](https://travis-ci.org/drrb/java-rust-example)
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) - mruby safe bindings for Rust [<img src="https://travis-ci.org/anima-engine/mrusty.svg?branch=master">](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [rustbridge/neon](https://github.com/rustbridge/neon) — use Rust from Node.js [<img src="https://travis-ci.org/rustbridge/neon.svg?branch=master">](https://travis-ci.org/rustbridge/neon)
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python bindings [<img src="https://travis-ci.org/dgrunwald/rust-cpython.svg?branch=master">](https://travis-ci.org/dgrunwald/rust-cpython)
  * [lukemetz/rustpy](https://github.com/lukemetz/rustpy) — Python bindings [<img src="https://travis-ci.org/lukemetz/rustpy.svg?branch=master">](https://travis-ci.org/lukemetz/rustpy)
* R
  * [rustr/rustr](https://github.com/rustr/rustr) — use Rust from R, and use R in Rust [<img src="https://travis-ci.org/rustr/rustr.svg?branch=master">](https://travis-ci.org/rustr/rustr)

### IDEs

See also [http://areweideyet.com/](http://areweideyet.com/) and [Rust and IDEs](https://www.rust-lang.org/ides.html).

  * [intellij-rust](https://github.com/intellij-rust/intellij-rust) — an [IntelliJ](https://www.jetbrains.com/idea/)-based IDE for Rust [<img src="https://travis-ci.org/intellij-rust/intellij-rust.svg?branch=master">](https://travis-ci.org/intellij-rust/intellij-rust)
  * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) — a Visual Studio extension for Rust [<img src="https://travis-ci.org/PistonDevelopers/VisualRust.svg?branch=master">](https://travis-ci.org/PistonDevelopers/VisualRust)
  * [Ride](https://github.com/madeso/ride) — [<img src="https://travis-ci.org/madeso/ride.svg?branch=master">](https://travis-ci.org/madeso/ride)
  * [RustDT](https://github.com/RustDT/RustDT) — an [Eclipse](https://eclipse.org/)-based IDE for Rust [<img src="https://travis-ci.org/RustDT/RustDT.svg?branch=master">](https://travis-ci.org/RustDT/RustDT)
  * [SolidOak](https://github.com/oakes/SolidOak) — a simple IDE for Rust, based on GTK+ and [Neovim](https://github.com/neovim/neovim)
  * [Visual Studio Code](https://code.visualstudio.com/)

### Profiling

* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — a stopwatch library [<img src="https://travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master">](https://travis-ci.org/ellisonch/rust-stopwatch)
* [mrhooray/torch](https://github.com/mrhooray/torch) — generates FlameGraphs based on DWARF Debug Info

### Testing

* [BurntSushi/quickcheck](https://github.com/BurntSushi/quickcheck) — a Rust implementation of [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) [<img src="https://travis-ci.org/BurntSushi/quickcheck.svg?branch=master">](https://travis-ci.org/BurntSushi/quickcheck)
* [farcaller/shiny](https://github.com/farcaller/shiny) — a fancy syntax similar to Ruby's Rspec or Objective-C' kiwi [<img src="https://travis-ci.org/farcaller/shiny.svg?branch=master">](https://travis-ci.org/farcaller/shiny)
* [frewsxcv/afl.rs](https://github.com/frewsxcv/afl.rs) — a Rust fuzzer, using [AFL](http://lcamtuf.coredump.cx/afl/) [<img src="https://api.travis-ci.org/frewsxcv/afl.rs.svg?branch=master">](https://travis-ci.org/frewsxcv/afl.rs)

## Libraries

### Astronomy
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — astronomy for Rust [<img src="https://travis-ci.org/saurvs/astro-rust.svg?branch=master">](https://travis-ci.org/saurvs/astro-rust)

### Asynchronous

* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — a coroutine I/O library with a working-stealing scheduler [<img src="https://travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)
* [thehydroimpulse/tangle](https://github.com/thehydroimpulse/tangle) — a scala-inspired futures library [<img src="https://travis-ci.org/thehydroimpulse/tangle.svg?branch=master">](https://travis-ci.org/thehydroimpulse/tangle)

### Audio

* [GuillaumeGomez/rust-fmod](https://github.com/GuillaumeGomez/rust-fmod) — [FMOD](http://www.fmod.org/) bindings [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
* [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — [PortAudio](http://www.portaudio.com/) bindings [<img src="https://travis-ci.org/RustAudio/rust-portaudio.svg?branch=master">](https://travis-ci.org/RustAudio/rust-portaudio)
* [jhasse/ears](https://github.com/jhasse/ears) — a simple library to play Sounds and Musics, on top of OpenAL and libsndfile [<img src="https://travis-ci.org/jhasse/ears.svg?branch=master">](https://travis-ci.org/jhasse/ears)
* [jpernst/openal-rs](https://github.com/jpernst/openal-rs) — [OpenAL 1.1](http://www.openal.org/) bindings [<img src="https://travis-ci.org/jpernst/openal-rs.svg?branch=master">](https://travis-ci.org/jpernst/openal-rs)
* [RustAudio](https://github.com/RustAudio)
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) bindings [<img src="https://travis-ci.org/musitdev/portmidi-rs.svg?branch=master">](https://travis-ci.org/musitdev/portmidi-rs)

### Authentication

* [keats/rust-jwt](https://github.com/keats/rust-jwt) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust  [![Build Status](https://api.travis-ci.org/Keats/rust-jwt.svg?branch=master)](https://travis-ci.org/Keats/rust-jwt)


### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) — bioinformatics libraries in Rust.


### Build system

* [Cargo](https://crates.io/) — the Rust package manager
  * [rsolomo/cargo-check](https://github.com/rsolomo/cargo-check) — a wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks [<img src="https://travis-ci.org/rsolomo/cargo-check.svg?branch=master">](https://travis-ci.org/rsolomo/cargo-check)
  * [kbknapp/cargo-count](https://github.com/kbknapp/cargo-count) — lists source code counts and details about cargo projects, including unsafe statistics [<img src="https://travis-ci.org/kbknapp/cargo-count.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-count)
  * [pwoolcoc/cargo-do](https://github.com/pwoolcoc/cargo-do) — run multiple cargo commands in a row
  * [maxsnew/cargo-dot](https://github.com/maxsnew/cargo-dot) — generate graphs of a Cargo project's dependencies [<img src="https://travis-ci.org/maxsnew/cargo-dot.svg?branch=master">](https://travis-ci.org/maxsnew/cargo-dot)
  * [killercup/cargo-edit](https://github.com/killercup/cargo-edit) — allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line [<img src="https://travis-ci.org/killercup/cargo-edit.svg?branch=master">](https://travis-ci.org/killercup/cargo-edit)
  * [kbknapp/cargo-graph](https://github.com/kbknapp/cargo-graph) — updated fork of `cargo-dot` with additional features [<img src="https://travis-ci.org/kbknapp/cargo-graph.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-graph)
  * [kbknapp/cargo-outdated](https://github.com/kbknapp/cargo-outdated) — displays when newer versions of Rust dependencies are available, or out of date [<img src="https://travis-ci.org/kbknapp/cargo-outdated.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-outdated)
  * [imp/cargo-multi](https://github.com/imp/cargo-multi) [[cargo-multi](https://crates.io/crates/cargo-multi/)] — runs specified cargo command on multiple crates [<img src="https://travis-ci.org/imp/cargo-multi.svg?branch=master">](https://travis-ci.org/imp/cargo-multi)
  * [DanielKeep/cargo-script](https://github.com/DanielKeep/cargo-script) — lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem
  * [passcod/cargo-watch](https://github.com/passcod/cargo-watch) — utility for cargo to compile projects when sources change [<img src="https://travis-ci.org/passcod/cargo-watch.svg?branch=master">](https://travis-ci.org/passcod/cargo-watch)
* CMake
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — an example project showing usage of CMake with Rust [<img src="https://travis-ci.org/SiegeLord/RustCMake.svg?branch=master">](https://travis-ci.org/SiegeLord/RustCMake)

### Caching

* [jaysonsantos/bmemcached-rs](https://github.com/jaysonsantos/bmemcached-rs) - Memcached library written in pure rust [<img src="https://travis-ci.org/jaysonsantos/bmemcached-rs.svg?branch=master">](https://travis-ci.org/jaysonsantos/bmemcached-rs)

### Concurrency

* [aturon/crossbeam](https://github.com/aturon/crossbeam) – Support for parallelism and low-level concurrency in Rust [<img src="https://travis-ci.org/aturon/crossbeam.svg?branch=master">](https://travis-ci.org/aturon/crossbeam)
* [nikomatsakis/rayon](https://github.com/nikomatsakis/rayon) – A data parallelism library for Rust [<img src="https://travis-ci.org/nikomatsakis/rayon.svg?branch=master">](https://travis-ci.org/nikomatsakis/rayon)

### Cloud

* AWS
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) — [<img src="https://travis-ci.org/rusoto/rusoto.svg?branch=master">](https://travis-ci.org/rusoto/rusoto)
  * [thommay/aws-rs](https://github.com/thommay/aws-rs) — [<img src="https://travis-ci.org/thommay/aws-rs.svg?branch=master">](https://travis-ci.org/thommay/aws-rs)
* DigitalOcean
  * [kbknapp/doapi](https://github.com/kbknapp/doapi-rs) — DigitalOcean v2 API bindings [<img src="https://travis-ci.org/kbknapp/doapi-rs.svg?branch=master">](https://travis-ci.org/kbknapp/doapi-rs)

### Command-line argument parsing

* [docopt/docopt.rs](https://github.com/docopt/docopt.rs) — a Rust implementation of [DocOpt](http://docopt.org) [<img src="https://travis-ci.org/docopt/docopt.rs.svg?branch=master">](https://travis-ci.org/docopt/docopt.rs)
* [kbknapp/clap-rs](https://github.com/kbknapp/clap-rs) — a simple to use, full featured command-line argument parser [<img src="https://travis-ci.org/kbknapp/clap-rs.svg?branch=master">](https://travis-ci.org/kbknapp/clap-rs)

### Command-line interface

* [kkawakam/rustyline](https://github.com/kkawakam/rustyline) - Readline Implementation in Rust [![Build Status](https://travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
* [srijs/rust-copperline](https://github.com/srijs/rust-copperline) - Pure-Rust Command Line Editing Library

### Compression

* [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](http://www.bzip.org) bindings [<img src="https://travis-ci.org/alexcrichton/bzip2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/bzip2-rs)
* [alexcrichton/flate2-rs](https://github.com/alexcrichton/flate2-rs) — [miniz](https://code.google.com/p/miniz/) bindings [<img src="https://travis-ci.org/alexcrichton/flate2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/flate2-rs)
* [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — tar archive reading/writing in Rust [<img src="https://travis-ci.org/alexcrichton/tar-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/tar-rs)
* [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — implementation of [Brotli](http://google-opensource.blogspot.co.uk/2015/09/introducing-brotli-new-compression.html) compression
* [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [snappy](https://github.com/google/snappy) bindings [<img src="https://travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master">](https://travis-ci.org/JeffBelgum/rust-snappy)
* [slackito/zip](https://github.com/slackito/zip) — read and write ZIP archives [<img src="https://travis-ci.org/slackito/zip.svg?branch=master">](https://travis-ci.org/slackito/zip)

### Computation

* BLAS [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) bindings
  * [stainless-steel/blas](https://github.com/stainless-steel/blas) — [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) bindings [<img src="https://travis-ci.org/stainless-steel/blas.svg?branch=master">](https://travis-ci.org/stainless-steel/blas)
* GMP
  * [thestinger/rust-gmp](https://github.com/thestinger/rust-gmp) — [libgmp](https://gmplib.org/) bindings [<img src="https://travis-ci.org/thestinger/rust-gmp.svg?branch=master">](https://travis-ci.org/thestinger/rust-gmp)
* GSL
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez) — [GSL](http://www.gnu.org/software/gsl/) bindings [<img src="https://travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master">](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* LAPACK
  * [stainless-steel/lapack](https://github.com/stainless-steel/lapack) — [LAPACK](https://en.wikipedia.org/wiki/LAPACK) bindings [<img src="https://travis-ci.org/stainless-steel/lapack.svg?branch=master">](https://travis-ci.org/stainless-steel/lapack)
* OpenCL
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](http://arrayfire.com) bindings
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) bindings [<img src="https://travis-ci.org/luqmana/rust-opencl.svg?branch=master">](https://travis-ci.org/luqmana/rust-opencl)
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) — scientific computing library in Rust [![Build Status](https://travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)   


### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [briansmith/ring](https://github.com/briansmith/ring) — Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives. [<img src="https://travis-ci.org/briansmith/ring.svg?branch=master">](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki](https://github.com/briansmith/webpki) — Web PKI TLS X.509 certificate validation in Rust. [<img src="https://travis-ci.org/briansmith/webpki.svg?branch=master">](https://travis-ci.org/briansmith/webpki)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — cryptographic algorithms in Rust [<img src="https://travis-ci.org/DaGenix/rust-crypto.svg?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* [dnaq/sodiumoxide](https://github.com/dnaq/sodiumoxide) — [libsodium](https://github.com/jedisct1/libsodium) bindings [<img src="https://travis-ci.org/dnaq/sodiumoxide.svg?branch=master">](https://travis-ci.org/dnaq/sodiumoxide)
* [klutzy/suruga](https://github.com/klutzy/suruga) — a Rust implementation of [TLS 1.2](http://tools.ietf.org/html/rfc5246)
* [libOctavo/octavo](https://github.com/libOctavo/octavo) — Modular hash and crypto library in Rust [<img src="https://api.travis-ci.org/libOctavo/octavo.svg?branch=master">](https://travis-ci.org/libOctavo/octavo)
* [seb-m/common.rs](https://github.com/seb-m/common.rs) — Common Rust crypto utilities [<img src="https://travis-ci.org/seb-m/common.rs.svg?branch=master">](https://travis-ci.org/seb-m/common.rs)
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) bindings [<img src="https://travis-ci.org/sfackler/rust-openssl.svg?branch=master">](https://travis-ci.org/sfackler/rust-openssl)


### Database

[[database](https://crates.io/keywords/database)]

* [pingcap/tikv](https://github.com/pingcap/tikv) — TiKV is a distributed KV database powered by Rust [<img src="https://travis-ci.org/pingcap/tikv.svg?branch=master">](https://travis-ci.org/pingcap/tikv)
* [sfackler/r2d2](https://github.com/sfackler/r2d2) — generic connection pool [<img src="https://travis-ci.org/sfackler/r2d2.svg?branch=master">](https://travis-ci.org/sfackler/r2d2)
* NoSQL [[nosql](https://crates.io/keywords/nosql)]
  * Cassandra [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [tupshin/cassandra-rust](https://github.com/tupshin/cassandra-rs) — [Cassandra](http://cassandra.apache.org) bindings
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [couchdb-rs/couchdb](https://github.com/couchdb-rs/couchdb) [[couchdb](https://crates.io/crates/couchdb/)] — a Rust client for the CouchDB REST API [<img src="https://travis-ci.org/couchdb-rs/couchdb.svg?branch=master">](https://travis-ci.org/couchdb-rs/couchdb)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es/)] — a Rust client for the [Elastic](https://www.elastic.co/) REST API [<img src="https://travis-ci.org/benashford/rs-es.svg?branch=master">](https://travis-ci.org/benashford/rs-es)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd/)] — A client library for CoreOS's etcd. [<img src="https://travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master">](https://travis-ci.org/jimmycuadra/rust-etcd)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [ForestDB](https://github.com/couchbase/forestdb) bindings [<img src="https://travis-ci.org/vhbit/sherwood.svg?branch=master">](https://travis-ci.org/vhbit/sherwood)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs/)] — [LMDB](http://symas.com/mdb/) bindings [<img src="https://travis-ci.org/vhbit/lmdb-rs.svg?branch=master">](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb-labs/mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) [[mongodb](https://crates.io/crates/mongodb/)] — [MongoDB](https://www.mongodb.org/) bindings [<img src="https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype.svg">](https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype)
  * Neo4j [[cypher](https://crates.io/keywords/cypher), [neo4j](https://crates.io/keywords/neo4j)]
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [mitsuhiko/redis-rs](https://github.com/mitsuhiko/redis-rs) — [Redis](http://redis.io) library in Rust [<img src="https://travis-ci.org/mitsuhiko/redis-rs.svg?branch=master">](https://travis-ci.org/mitsuhiko/redis-rs)
* SQL [[sql](https://crates.io/keywords/sql)]
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] — a native MySql client [<img src="https://travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
 * ORM [[orm](https://crates.io/keywords/orm)]
    * [deuterium-orm/deuterium-orm](https://github.com/deuterium-orm/deuterium) — an SQL query builder for Rust  [![Build Status](https://travis-ci.org/deuterium-orm/deuterium.svg?branch=master)](https://travis-ci.org/deuterium-orm/deuterium)
    * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — an ORM for Rust [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg)](https://travis-ci.org/ivanceras/rustorm)
    * [phonkee/treasure](https://github.com/phonkee/treasure) — an ORM for Rust
    * [sgrif/diesel](https://github.com/sgrif/diesel) — an ORM and Query builder for Rust [![Build Status](https://api.travis-ci.org/sgrif/diesel.svg)](https://travis-ci.org/sgrif/diesel)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres/)] — a native [PostgreSQL](http://www.postgresql.org) client [<img src="https://travis-ci.org/sfackler/rust-postgres.svg?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [dckc/rust-sqlite3](https://github.com/dckc/rust-sqlite3) — [Sqlite3](http://www.sqlite.org/) bindings [<img src="https://travis-ci.org/dckc/rust-sqlite3.svg?branch=master">](https://travis-ci.org/dckc/rust-sqlite3)
    * [jgallagher/rusqlite](https://github.com/jgallagher/rusqlite) — [Sqlite3](http://www.sqlite.org/) bindings [<img src="https://travis-ci.org/jgallagher/rusqlite.svg?branch=master">](https://travis-ci.org/jgallagher/rusqlite)
    * [linuxfood/rustsqlite](https://github.com/linuxfood/rustsqlite) — [Sqlite3](http://www.sqlite.org/) bindings [<img src="https://travis-ci.org/linuxfood/rustsqlite.svg?branch=master">](https://travis-ci.org/linuxfood/rustsqlite)


### Data structures

* [bluss/rust-itertools](https://github.com/bluss/rust-itertools) — [<img src="https://travis-ci.org/bluss/rust-itertools.svg?branch=master">](https://travis-ci.org/bluss/rust-itertools)
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) – a hack to allow for arrays sized by typenums [<img src="https://travis-ci.org/fizyk20/generic-array.svg?branch=master">](https://travis-ci.org/fizyk20/generic-array)
* [Nemo157/roaring-rs](https://github.com/Nemo157/roaring-rs) – Roaring Bitmaps in Rust [<img src="https://travis-ci.org/Nemo157/roaring-rs.svg?branch=master">](https://travis-ci.org/Nemo157/roaring-rs)
* [reem/rust-typemap](https://github.com/reem/rust-typemap) — [<img src="https://travis-ci.org/reem/rust-typemap.svg?branch=master">](https://travis-ci.org/reem/rust-typemap)
* [serde-rs/serde](https://github.com/serde-rs/serde) — a framework to generically serialize Rust data structures [<img src="https://api.travis-ci.org/serde-rs/serde.svg?branch=master">](https://travis-ci.org/serde-rs/serde)


### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [lifthrasiir/rust-chrono](https://github.com/lifthrasiir/rust-chrono) — [<img src="https://travis-ci.org/lifthrasiir/rust-chrono.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-chrono)
* [rust-lang-deprecated/time](https://github.com/rust-lang-deprecated/time) — [<img src="https://travis-ci.org/rust-lang-deprecated/time.svg?branch=master">](https://travis-ci.org/rust-lang-deprecated/time)


### Distributed Systems

* Apache Kafka
  * [spicavigo/kafka-rust](https://github.com/spicavigo/kafka-rust) — [<img src="https://travis-ci.org/spicavigo/kafka-rust.svg?branch=master">](https://travis-ci.org/spicavigo/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd](https://github.com/kr/beanstalkd) bindings [<img src="https://travis-ci.org/schickling/rust-beanstalkd.svg?branch=master">](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) — libhdfs bindings [<img src="https://travis-ci.org/hyunsik/hdfs-rs.svg?branch=master">](https://travis-ci.org/hyunsik/hdfs-rs)


### Email

[[email](https://crates.io/keywords/email)]

* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) — unofficial Rust library for SendGrid API [<img src="https://travis-ci.org/gsquire/sendgrid-rs.svg?branch=master">](https://travis-ci.org/gsquire/sendgrid-rs)
* [lettre/lettre](https://github.com/lettre/lettre) — an SMTP-library for Rust [<img src="https://travis-ci.org/lettre/lettre.svg?branch=master">](https://travis-ci.org/lettre/lettre)


### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — a Rust ASN.1 (DER) serializer [<img src="https://travis-ci.org/alex/rust-asn1.svg?branch=master">](https://travis-ci.org/alex/rust-asn1)
* Bencode
  * [arjantop/rust-bencode](https://github.com/arjantop/rust-bencode) — [Bencode](https://en.wikipedia.org/wiki/Bencode) implementation in Rust [<img src="https://travis-ci.org/arjantop/rust-bencode.svg?branch=master">](https://travis-ci.org/arjantop/rust-bencode)
* Binary
  * [arcnmx/nue](https://github.com/arcnmx/nue) — I/O and binary data encoding for Rust [<img src="https://travis-ci.org/arcnmx/nue.svg?branch=master">](https://travis-ci.org/arcnmx/nue)
  * [TyOverby/bincode](https://github.com/TyOverby/bincode) — a binary encoder/decoder in Rust [<img src="https://travis-ci.org/TyOverby/bincode.svg?branch=master">](https://travis-ci.org/TyOverby/bincode)
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — Supports big-endian, little-endian and native byte orders [<img src="https://travis-ci.org/BurntSushi/byteorder.svg?branch=master">](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  * [dwrensha/capnproto-rust](https://github.com/dwrensha/capnproto-rust) — [<img src="https://travis-ci.org/dwrensha/capnproto-rust.svg?branch=master">](https://travis-ci.org/dwrensha/capnproto-rust)
* CBOR
  * [BurntSushi/rust-cbor](https://github.com/BurntSushi/rust-cbor) — Supports JSON conversion and type-based encoding/decoding [<img src="https://travis-ci.org/BurntSushi/rust-cbor.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-cbor)
* Character Encoding
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [<img src="https://travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) — [<img src="https://travis-ci.org/mrhooray/crc-rs.svg?branch=master">](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — [<img src="https://travis-ci.org/BurntSushi/rust-csv.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-csv)
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — High-performance browser-grade HTML5 parser [<img src="https://travis-ci.org/servo/html5ever.svg?branch=master">](https://travis-ci.org/servo/html5ever)
* JSON
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json/)] — JSON support for [Serde](https://github.com/serde-rs/serde) framework [<img src="https://travis-ci.org/serde-rs/json.svg?branch=master">](https://travis-ci.org/serde-rs/json)
* Jsonnet
  * [Qihoo360/rust-jsonnet](https://github.com/Qihoo360/rust-jsonnet) —  [<img src="https://travis-ci.org/Qihoo360/rust-jsonnet.svg?branch=master">](https://travis-ci.org/Qihoo360/rust-jsonnet)
* MsgPack
  * [mneumann/rust-msgpack](https://github.com/mneumann/rust-msgpack) — [<img src="https://travis-ci.org/mneumann/rust-msgpack.svg?branch=master">](https://travis-ci.org/mneumann/rust-msgpack)
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — a pure Rust low/high level MessagePack implementation [<img src="https://travis-ci.org/3Hren/msgpack-rust.svg?branch=master">](https://travis-ci.org/3Hren/msgpack-rust)
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [<img src="https://travis-ci.org/stepancheg/rust-protobuf.svg?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
* RON (Rusty Object Notation)
  * [kvark/ron](https://github.com/kvark/ron) — [<img src="https://travis-ci.org/kvark/ron.svg?branch=master">](https://travis-ci.org/kvark/ron)
* Tnetstring
  * [erickt/rust-tnetstring](https://github.com/erickt/rust-tnetstring) — [<img src="https://travis-ci.org/erickt/rust-tnetstring.svg?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
* TOML
  * [alexcrichton/toml-rs](https://github.com/alexcrichton/toml-rs) — [<img src="https://travis-ci.org/alexcrichton/toml-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/toml-rs)
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — an XML parser written in Rust [<img src="https://travis-ci.org/Florob/RustyXML.svg?branch=master">](https://travis-ci.org/Florob/RustyXML)
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — An XML library in Rust [<img src="https://travis-ci.org/shepmaster/sxd-document.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — An XPath library in Rust [<img src="https://travis-ci.org/shepmaster/sxd-xpath.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-xpath)
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) — a streaming XML library [<img src="https://travis-ci.org/netvl/xml-rs.svg?branch=master">](https://travis-ci.org/netvl/xml-rs)
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — The missing YAML 1.2 implementation for Rust. [<img src="https://travis-ci.org/chyh1990/yaml-rust.svg?branch=master">](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml/)] — YAML support for [Serde](https://github.com/serde-rs/serde) framework [<img src="https://travis-ci.org/dtolnay/serde-yaml.svg?branch=master">](https://travis-ci.org/dtolnay/serde-yaml)
  * [kimhyunkang/libyaml-rust](https://github.com/kimhyunkang/libyaml-rust) — [libyaml](http://pyyaml.org/wiki/LibYAML) bindings [<img src="https://travis-ci.org/kimhyunkang/libyaml-rust.svg?branch=master">](https://travis-ci.org/kimhyunkang/libyaml-rust)

### Game development

* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](http://liballeg.org/) bindings [<img src="https://travis-ci.org/SiegeLord/RustAllegro.svg?branch=master">](https://travis-ci.org/SiegeLord/RustAllegro)
* Amethyst
  * [ebkalderon/amethyst](https://github.com/ebkalderon/amethyst) — data-oriented game engine [<img src="https://travis-ci.org/ebkalderon/amethyst.svg?branch=master">](https://travis-ci.org/ebkalderon/amethyst)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange) bindings
* Piston
  * [Piston](http://www.piston.rs) — [<img src="https://travis-ci.org/PistonDevelopers/piston.svg?branch=master">](https://travis-ci.org/PistonDevelopers/piston)
* SDL [[sdl](https://crates.io/keywords/sdl)]
  * [AngryLawyer/rust-sdl2](https://github.com/AngryLawyer/rust-sdl2) — [SDL2](http://www.libsdl.org/) bindings [<img src="https://travis-ci.org/AngryLawyer/rust-sdl2.svg?branch=master">](https://travis-ci.org/AngryLawyer/rust-sdl2)
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — [SDL1](http://www.libsdl.org/) bindings [<img src="https://travis-ci.org/brson/rust-sdl.svg?branch=master">](https://travis-ci.org/brson/rust-sdl)
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — [SFML](http://www.sfml-dev.org/) bindings [<img src="https://travis-ci.org/jeremyletang/rust-sfml.svg?branch=master">](https://travis-ci.org/jeremyletang/rust-sfml)
* Voxlap
  * [bbodi/rust-voxlap](https://github.com/bbodi/rust-voxlap) — [Voxlap](http://advsys.net/ken/voxlap.htm) bindings

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [Georust](https://github.com/georust) — geospatial tools and libraries written in Rust


### GUI

[[gui](https://crates.io/keywords/gui)]

* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — An easy-to-use, immediate-mode, 2D GUI library written entirely in Rust [<img src="https://travis-ci.org/PistonDevelopers/conrod.svg?branch=master">](https://travis-ci.org/PistonDevelopers/conrod)
* [pravic/rust-sciter](https://github.com/pravic/rust-sciter) — Rust bindings for the Sciter, embeddable HTML/CSS/script engine (cross-platform desktop GUI toolkit). [<img src="https://ci.appveyor.com/api/projects/status/github/pravic/rust-sciter?svg=true">](https://ci.appveyor.com/project/pravic/rust-sciter)
* Cocoa
  * [servo/rust-cocoa](https://github.com/servo/cocoa-rs)
* IUP
  * [dcampbell24/iup-rust](https://github.com/dcampbell24/iup-rust) — [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) bindings [<img src="https://travis-ci.org/dcampbell24/iup-rust.svg?branch=master">](https://travis-ci.org/dcampbell24/iup-rust)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — a simple UI framework built on IUP [![Build Status](https://travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* GTK+ [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk](https://github.com/gtk-rs/gtk) — [GTK+](http://www.gtk.org) bindings [<img src="https://travis-ci.org/gtk-rs/gtk.svg?branch=master">](https://travis-ci.org/gtk-rs/gtk)
* ncurses [[ncurses](https://crates.io/keywords/ncurses)]
  * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) — [ncurses](http://www.gnu.org/software/ncurses/) bindings [<img src="https://travis-ci.org/jeaye/ncurses-rs.svg?branch=master">](https://travis-ci.org/jeaye/ncurses-rs)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [bjz/gl-rs](https://github.com/bjz/gl-rs) — [<img src="https://travis-ci.org/bjz/gl-rs.svg?branch=master">](https://travis-ci.org/bjz/gl-rs)
  * [bjz/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) — [<img src="https://travis-ci.org/bjz/glfw-rs.svg?branch=master">](https://travis-ci.org/bjz/glfw-rs)
  * [tomaka/glium](https://github.com/tomaka/glium) — safe OpenGL wrapper for the Rust language. [<img src="https://travis-ci.org/tomaka/glium.svg?branch=master">](https://travis-ci.org/tomaka/glium)
  * [tomaka/glutin](https://github.com/tomaka/glutin) — Rust alternative to [GLFW](http://www.glfw.org/) [<img src="https://travis-ci.org/tomaka/glutin.svg?branch=master">](https://travis-ci.org/tomaka/glutin)
* Qt
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — [QtQuick](http://doc.qt.io) bindings [<img src="https://travis-ci.org/cyndis/qmlrs.svg?branch=master">](https://travis-ci.org/cyndis/qmlrs)
* Termbox
  * [gchp/rustbox](https://github.com/gchp/rustbox) — a Rust implementation of [termbox](https://github.com/nsf/termbox) [<img src="https://travis-ci.org/gchp/rustbox.svg?branch=master">](https://travis-ci.org/gchp/rustbox)


### Image processing

* [chyh1990/imageproc](https://github.com/chyh1990/imageproc) — An advanced image processing library for Rust. [![Build Status](https://travis-ci.org/chyh1990/imageproc.svg?branch=master)](https://travis-ci.org/chyh1990/imageproc)
* [cybergeek94/img-hash](https://github.com/cybergeek94/img_hash) — Perceptual image hashing and comparison for equality and similarity.
* [PistonDevelopers/image](https://github.com/PistonDevelopers/image) — Basic imaging processing functions and methods for converting to and from image formats [<img src="https://travis-ci.org/PistonDevelopers/image.svg?branch=master">](https://travis-ci.org/PistonDevelopers/image)


### Machine learning

* [autumnai/leaf](https://github.com/autumnai/leaf) — Open Machine Intelligence framework. [![Build Status](https://travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — Machine learning crate for Rust. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://circleci.com/gh/maciejkula/rustlearn)


### Markup language

* CommonMark
  * [google/pulldown-cmark](https://github.com/google/pulldown-cmark) — [CommonMark](http://commonmark.org/) parser in Rust


### Mobile

* Android
  * [tomaka/android-rs-glue](https://github.com/tomaka/android-rs-glue) — glue between Rust and Android [<img src="https://travis-ci.org/tomaka/android-rs-glue.svg?branch=master">](https://travis-ci.org/tomaka/android-rs-glue)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — a cargo lipo subcommand which automatically creates a universal library for use with your iOS application. [<img src="https://travis-ci.org/TimNN/cargo-lipo.svg?branch=master">](https://travis-ci.org/TimNN/cargo-lipo)
  * [vhbit/ObjCrust](https://github.com/vhbit/ObjCrust) — using Rust to create an iOS static library [<img src="https://travis-ci.org/vhbit/ObjCrust.svg?branch=master">](https://travis-ci.org/vhbit/ObjCrust)
* Pebble
  * [andars/pebble.rs](https://github.com/andars/pebble.rs) — a crate that allows Rust to be used to develop Pebble applications.


### Network programming

* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — an [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-ftp)
* Low level
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — a cross-platform, low level networking [<img src="https://travis-ci.org/libpnet/libpnet.svg?branch=master">](https://travis-ci.org/libpnet/libpnet)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](http://nanomsg.org/) bindings [<img src="https://travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master">](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) — an [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-nntp)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) — a [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-pop3)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [libssh2](http://www.libssh2.org/) bindings [<img src="https://travis-ci.org/alexcrichton/ssh2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — a [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation in Rust [<img src="https://travis-ci.org/zslayton/stomp-rs.svg?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
* uTP
  * [meqif/rust-utp](https://github.com/meqif/rust-utp) — a [uTP](http://www.bittorrent.org/beps/bep_0029.html) (Micro Transport Protocol) library for Rust. [<img src="https://travis-ci.org/meqif/rust-utp.svg?branch=master">](https://travis-ci.org/meqif/rust-utp)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — [ZeroMQ](http://zeromq.org/) bindings [<img src="https://travis-ci.org/erickt/rust-zmq.svg?branch=master">](https://travis-ci.org/erickt/rust-zmq)


### Parser

  * [Geal/nom](https://github.com/Geal/nom) — parser combinator library [<img src="https://travis-ci.org/Geal/nom.svg?branch=master">](https://travis-ci.org/Geal/nom)
  * [ivanceras/inquerest](https://github.com/ivanceras/inquerest) — an URL parameter parser for rest filter inquiry [![Build Status](https://travis-ci.org/ivanceras/inquerest.svg?branch=master)](https://travis-ci.org/ivanceras/inquerest)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — Parsing Expression Grammar (PEG) parser generator
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) – A fast monadic-style parser combinator [<img src="https://travis-ci.org/m4rw3r/chomp.svg?branch=master">](https://travis-ci.org/m4rw3r/chomp)
  * [Marwes/combine](https://github.com/Marwes/combine) — parser combinator library [<img src="https://travis-ci.org/Marwes/combine.svg?branch=master">](https://travis-ci.org/Marwes/combine)
  * [nikomatsakis/lalrpop](https://github.com/nikomatsakis/lalrpop) - LR(1) parser generator for Rust [![Build status](https://travis-ci.org/nikomatsakis/lalrpop.svg?branch=master)](https://travis-ci.org/nikomatsakis/lalrpop)
  * [ptal/oak](https://github.com/ptal/oak) — a typed PEG parser generator (compiler plugin)
  * [rustless/queryst](https://github.com/rustless/queryst) — a query string parsing library for Rust inspired by https://github.com/ljharb/qs [![Build Status](https://travis-ci.org/rustless/queryst.svg?branch=master)](https://travis-ci.org/rustless/queryst)


### Platform specific

* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) — [inotify](https://en.wikipedia.org/wiki/Inotify) bindings [<img src="https://travis-ci.org/hannobraun/inotify-rs.svg?branch=master">](https://travis-ci.org/hannobraun/inotify-rs)
* Unix-like
  * [carllerche/nix-rust](https://github.com/carllerche/nix-rust) — Unix-like API bindings [<img src="https://travis-ci.org/carllerche/nix-rust.svg?branch=master">](https://travis-ci.org/carllerche/nix-rust)
  * [zargony/rust-fuse](https://github.com/zargony/rust-fuse) — [FUSE](https://github.com/libfuse/libfuse) bindings <img src="https://travis-ci.org/zargony/rust-fuse.svg?branch=master">
* Windows
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) — Windows API bindings [<img src="https://travis-ci.org/retep998/winapi-rs.svg?branch=master">](https://travis-ci.org/retep998/winapi-rs)


### Template engine

* Handlebars
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — Handlebars template engine with inheritance, custom helper support. [<img src="https://travis-ci.org/sunng87/handlebars-rust.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  * [lfairy/maud](https://github.com/lfairy/maud) — compile-time HTML templates [<img src="https://travis-ci.org/lfairy/maud.svg?branch=master">](https://travis-ci.org/lfairy/maud)
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — compile-time HTML templates [<img src="https://travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master">](https://travis-ci.org/Stebalien/horrorshow-rs)
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) — [<img src="https://travis-ci.org/rustache/rustache.svg?branch=master">](https://travis-ci.org/rustache/rustache)
* [tailhook/marafet](https://github.com/tailhook/marafet) — Compiler for Jade-like template language to cito.js-based virtual dom

### Text processing

* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — Linear time suffix array construction (with Unicode support) [<img src="https://travis-ci.org/BurntSushi/suffix.svg?branch=master">](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — Elastic tab stops (i.e., text column alignment) [<img src="https://travis-ci.org/BurntSushi/tabwriter.svg?branch=master">](https://travis-ci.org/BurntSushi/tabwriter)
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) — Construct [n-grams](https://en.wikipedia.org/wiki/N-gram) from arbitrary iterators [<img src="https://travis-ci.org/pwoolcoc/ngrams.svg?branch=master">](https://travis-ci.org/pwoolcoc/ngrams)
* [rust-lang-nursery/regex](https://github.com/rust-lang-nursery/regex) — Regular expressions (RE2 style) [<img src="https://travis-ci.org/rust-lang-nursery/regex.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/regex)

### Virtualization

* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — Hardware-accelerated virtualization on OS X

### Web programming

See also [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* HTTP Client
  * [carllerche/curl-rust](https://github.com/carllerche/curl-rust) — [libcurl](http://curl.haxx.se/libcurl/) bindings [<img src="https://travis-ci.org/carllerche/curl-rust.svg?branch=master">](https://travis-ci.org/carllerche/curl-rust)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — an HTTP implementation [<img src="https://travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [vhbit/curl-rs](https://github.com/vhbit/curl-rs) — [libcurl](http://curl.haxx.se/libcurl/) bindings [<img src="https://travis-ci.org/vhbit/curl-rs.svg?branch=master">](https://travis-ci.org/vhbit/curl-rs)
* HTTP Server
  * [fengsp/pencil](https://github.com/fengsp/pencil) — [<img src="https://travis-ci.org/fengsp/pencil.svg?branch=master">](https://travis-ci.org/fengsp/pencil)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — an HTTP implementation [<img src="https://travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [Iron](https://github.com/iron/iron) — a middleware-based server framework [<img src="https://travis-ci.org/iron/iron.svg?branch=master">](https://travis-ci.org/iron/iron)
    * [sunng87/handlebars-iron](https://github.com/sunng87/handlebars-iron) — [Handlebars-rust](https://github.com/sunng87/handlebars-rust) as an Iron web framework middleware. [<img src="https://travis-ci.org/sunng87/handlebars-iron.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-iron)
  * [Nickel](https://github.com/nickel-org/nickel.rs/) — inspired by [Express](http://expressjs.com/) [<img src="https://travis-ci.org/nickel-org/nickel.rs.svg?branch=master">](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) — a RESTful web framework for Rust  [<img src="https://travis-ci.org/Ogeon/rustful.svg?branch=master">](https://travis-ci.org/Ogeon/rustful)
  * [Rustless](https://github.com/rustless/rustless) — a REST-like API micro-framework inspired by [Grape](https://github.com/ruby-grape/grape) and [Hyper](https://github.com/hyperium/hyper) [<img src="https://travis-ci.org/rustless/rustless.svg?branch=master">](https://travis-ci.org/rustless/rustless)
  * [tiny-http](https://github.com/frewsxcv/tiny-http) — Low level HTTP server library [<img src="https://travis-ci.org/frewsxcv/tiny-http.svg?branch=master">](https://travis-ci.org/frewsxcv/tiny-http)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [cyderize/rust-websocket](https://github.com/cyderize/rust-websocket) — a framework for dealing with WebSocket connections (both clients and servers) [<img src="https://travis-ci.org/cyderize/rust-websocket.svg?branch=master">](https://travis-ci.org/cyderize/rust-websocket)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — lightweight, event-driven WebSockets for Rust [<img src="https://travis-ci.org/housleyjk/ws-rs.svg?branch=stable">](https://travis-ci.org/housleyjk/ws-rs)


## Resources

* Benchmarks
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) — Rust implementations for the [The Computer Language Benchmarks Game](http://benchmarksgame.alioth.debian.org/) [<img src="https://travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master">](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* Podcasts
  * [New Rustacean](http://www.newrustacean.com) — a podcast about learning Rust
  * [Rusty Radio](http://rustyrad.io) — covering the rust ecosystem
* [Rust by Example](http://rustbyexample.com/)
* [RustCamp 2015 Talks](http://confreaks.tv/events/rustcamp2015)
* [Rust Design Patterns](https://github.com/nrc/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [rust-learning](https://github.com/ctjhoa/rust-learning) — a collection of useful resources to learn Rust
* [Rustlings](https://github.com/carols10cents/rustlings) — small exercises to get you used to reading and writing Rust code


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
