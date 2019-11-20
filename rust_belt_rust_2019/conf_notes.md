# Rust Belt Rust 2019

## WASM plugin workshop 

* See code in ~/code/rust_experiments/rbr-plugins/ 
 * how to work with only numbers, and how to use strings in this manner 

* Never got the macro code to compile and he was doing things differently enough from 
    [his repo](https://github.com/FreeMasen/rbr-plugins) I just don't feel like getting it to work 


## Unicode in Rust - Illustrated by Kanji - Jenny Manning

* use `.chars().len()` for character count, not `.len()` unless you want the byte count 
* normalize strings before doing comparisons (`unicode-normalization`) 
 
## Tips for Writing a Web Server and Beyond - Apoorv Kothari

* Working code at their [repo](https://github.com/toidiu/fin-public) 
* `diesel` is ORM vs SQL
* `diesel` will actually check your queries at compile time (and type check them too!) 
* `slog` crate is a great crate for logging 
* on logging always make sure they are machine searchable, e.g. think in `key:value` 
* Logs should be contextual, always try to add a code path or a way to figure out where the code caused the problem 
* `tracing` is another crate, mainly used for distributed tracing. Good for async code as well 
* `lineError!` macro add the line in the file with the Error code 
* Good way to handle errors in the slides, find them 

## Are we *actually* IDE yet? A look on the Rust IDE Story - Igor Matuszewski

* @Xanewok 
* `racer` used the full `rustc` parser 
* Is the maintainer of the Rust Language Server (RLS) from Google Summer of Code 2017 
* Intellij Rust was actually written in pre-1.0 Kotlin in 2015
* Rust Analyzer 2018-> Using `salsa` and is a good IDE support 
* Separate from rustc so it isn't slowed by the compiler 
* WG RLS2.0 formed at Rust All-Hands 
* How to turn rustc into a library
* Bridge RLS and Rust Analyzer 
* So are we IDE yet? Not yet, but super close! 

## Polonius: Either Borrower or Lender Be, but Responsibly - Niko Matsakis

* Polonius: the dude who gets stabbed in Hamlet - "Neither borrow nor lender be; for loan oft loses both itself and friend" 
* Reimagination of the Rust Borrow Checker (as the end user you won't notice) 
* super great explanation of the borrow checker

## Lightening Talks 

### Organizing a workshop from across an ocean 

* I couldn't hear anything unfortunately they spoke in too high an octave 

### Creative Coding 

* Arts with computers (programming with a goal of artistic content) 

### Metamorphic Testing in Rust 

* start with an input, apply transformations, compute every possible combination of transformations, count results from original and transformed inputs, and then compare 
* 2**n-1 test cases if the order doesn't matter
* you know exactly what the inputs are 
* you don't need to know the expected output 
* `monarch` is the library he wrote 

### Oracle Bone Script

* explanation of bone script in the 1200BC era 
* where modern chines, japanese, and korean comes from 

### Genetic Programming in Rust 

* used rust code to automatically generate some program some brainfuck to loop for a \0 terminated program 

### Rust Program in 0x A presses 

* pretty cool, hope they put the code up on github

## Introducing Rust into a Legacy Embedded System - Steven Walter

* Embedded Rust at Lexmark 
* Scare bad C 
* picked small unimportant project to write in Rust 
* kept Rust in its own process(es) because of the bad C code
* uses bitbake 
* co-maintainer of [meta-rust](https://github.com/meta-rust/meta-rust/) which provides the bitbake recipes 
* Zephyr kernal 
* really small memory usage, https://github.com/tylerwhall/zephyr-rust 
* slides https://github.com/srwalter/rbr-legacy-code 

## Lightning Talks v2

### What Happens When You Give Blood

* Just overall general how to give blood and what happens 

### Everything that Sucks about windowing systems 

* @osspial 
* for windowing great to constantly poll for gaming you get and need all the attention
* but for desktop applications it will kill everything else 
* multiple windows -> multiple threads 

### How to Run RustBridge 

* everything is there to help you teach 
* [rustbridge](https://rustbridge.com)

### bitvec

## Type Theory for the Working Rustacean - Dan Pittman

* a:A (term:Type) 
* `x: u8` 
* shows good examples of when to use `where:` and why you would do that 

## The Death and Rebirth of Docs.rs - Quiet Misdreavus

* good overview on the infra of docs.rs and the infra team 
