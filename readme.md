ryantm@ ~/projects/rust/ecdsa/rust_ecdsa/test (master)$ ls
county.rs  farm.rs
ryantm@ryantm0j132 ~/projects/rust/ecdsa/rust_ecdsa/test (master)$ rustc --version
rustc 0.11-pre-nightly (168b2d1 2014-04-14 14:36:54 -0700)
host: x86_64-unknown-linux-gnu
ryantm@ ~/projects/rust/ecdsa/rust_ecdsa/test (master)$ uname -a
Linux ryantm0j132 3.14.1-1-ARCH #1 SMP PREEMPT Mon Apr 14 20:40:47 CEST 2014 x86_64 GNU/Linux
ryantm@ryantm0j132 ~/projects/rust/ecdsa/rust_ecdsa/test (master)$ rustc --version
rustc 0.11-pre-nightly (168b2d1 2014-04-14 14:36:54 -0700)
host: x86_64-unknown-linux-gnu
ryantm@ ~/projects/rust/ecdsa/rust_ecdsa/test (master)$ rustc county.rs 
county.rs:2:9: 2:13 error: file not found for module `farm`
county.rs:2     mod farm;
                    ^~~~
