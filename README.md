# rust-dxr

[DXR](https://github.com/mozilla/dxr) is a static analysis tool for indexing and
cross-referencing programs. [Rust](https://github.com/rust-lang/rust) is a
programming language. This repository is for tracking the implementation of
Rust indexing in DXR. The current status is that there is no particular
support. Rust programs are syntax highlighted and searchable. There was in the
past a fairly complete implementation, but that is out of date. I (@nick29581)
have been porting that to the new DXR plugin API. See issues for more details.

Note that there will not be a lot of code in this repo, it is mainly to have one
place for issue tracking. The code is in two places - in DXR, and in the Rust
compiler. The old version of the DXR stuff can be found
[here](https://github.com/nick29581/dxr/tree/rust2/dxr/plugins/rust) (note that
that is fairly out of date). The compiler stuff can be found (mostly) in
[librustc_trans/save](https://github.com/rust-lang/rust/tree/master/src/librustc_trans/save).
