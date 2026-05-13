 $ cargo +nightly miri test
 Compiling proc-macro2 v1.0.103
   Compiling quote v1.0.42
   Compiling unicode-ident v1.0.22
   Compiling serde_core v1.0.228
   Compiling crossbeam-utils v0.8.21
   Compiling windows-link v0.2.1
   Compiling zerocopy v0.8.31
   Compiling serde v1.0.228
   Compiling autocfg v1.5.0
   Compiling rayon-core v1.13.0
   Compiling cfg-if v1.0.4
   Compiling serde_json v1.0.145
   Compiling windows-sys v0.61.2
   Compiling either v1.15.0
   Compiling itoa v1.0.15
   Compiling anstyle v1.0.13
   Compiling regex-syntax v0.8.8
   Compiling clap_lex v0.7.6
   Compiling ciborium-io v0.2.2
   Compiling plotters-backend v0.3.7
   Compiling num-traits v0.2.19
   Compiling winapi-util v0.1.11
   Compiling memchr v2.7.6
   Compiling ryu v1.0.20
   Compiling itertools v0.10.5
   Compiling clap_builder v4.5.53
   Compiling cast v0.3.0
   Compiling regex-automata v0.4.13
   Compiling same-file v1.0.6
   Compiling plotters-svg v0.3.7
   Compiling is-terminal v0.4.17
   Compiling walkdir v2.5.0
   Compiling crossbeam-epoch v0.9.18
   Compiling once_cell v1.21.3
   Compiling anes v0.1.6
   Compiling oorandom v11.1.5
warning[E0133]: dereference of raw pointer is unsafe and requires unsafe block
  --> src\lib.rs:60:15
   |
60 |     let val = *raw;
   |               ^^^^ dereference of raw pointer
   |
   = note: raw pointers may be null, dangling or unaligned; they can violate aliasing rules and cause data races: all of these are undefined behavior
note: an unsafe function restricts its caller, but its body is safe by default
  --> src\lib.rs:57:1
   |
57 | pub unsafe fn use_after_free() -> i32 {
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>
   = note: `#[warn(unsafe_op_in_unsafe_fn)]` (part of `#[warn(rust_2024_compatibility)]`) on by default

warning[E0133]: call to unsafe function `std::boxed::Box::<T>::from_raw` is unsafe and requires unsafe block
  --> src\lib.rs:61:10
   |
61 |     drop(Box::from_raw(raw));
   |          ^^^^^^^^^^^^^^^^^^ call to unsafe function
   |
   = note: consult the function's documentation for information on how to avoid undefined behavior
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>

warning[E0133]: dereference of raw pointer is unsafe and requires unsafe block
  --> src\lib.rs:62:11
   |
62 |     val + *raw
   |           ^^^^ dereference of raw pointer
   |
   = note: raw pointers may be null, dangling or unaligned; they can violate aliasing rules and cause data races: all of these are undefined behavior
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>

For more information about this error, try `rustc --explain E0133`.
warning: `broken-app` (lib) generated 3 warnings (run `cargo fix --lib -p broken-app` to apply 1 suggestion)
   Compiling crossbeam-deque v0.8.6
   Compiling syn v2.0.111
   Compiling criterion-plot v0.5.0
   Compiling rayon v1.11.0
   Compiling plotters v0.3.7
   Compiling regex v1.12.2
   Compiling clap v4.5.53
   Compiling zerocopy-derive v0.8.31
   Compiling serde_derive v1.0.228
   Compiling half v2.7.1
   Compiling ciborium-ll v0.2.2
   Compiling tinytemplate v1.2.1
   Compiling ciborium v0.2.2
   Compiling criterion v0.5.1
   Compiling broken-app v0.1.0 (D:\YPraktikum\Rust\module_5\broken-app)
    Finished `test` profile [unoptimized + debuginfo] target(s) in 10.68s
     Running unittests src\lib.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\broken_app-fc3f43343138b20b.exe)
warning[E0133]: dereference of raw pointer is unsafe and requires unsafe block
  --> src\lib.rs:60:15
   |
60 |     let val = *raw;
   |               ^^^^ dereference of raw pointer
   |
   = note: raw pointers may be null, dangling or unaligned; they can violate aliasing rules and cause data races: all of these are undefined behavior
note: an unsafe function restricts its caller, but its body is safe by default
  --> src\lib.rs:57:1
   |
57 | pub unsafe fn use_after_free() -> i32 {
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>
   = note: `#[warn(unsafe_op_in_unsafe_fn)]` (part of `#[warn(rust_2024_compatibility)]`) on by default

warning[E0133]: call to unsafe function `std::boxed::Box::<T>::from_raw` is unsafe and requires unsafe block
  --> src\lib.rs:61:10
   |
61 |     drop(Box::from_raw(raw));
   |          ^^^^^^^^^^^^^^^^^^ call to unsafe function
   |
   = note: consult the function's documentation for information on how to avoid undefined behavior
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>

warning[E0133]: dereference of raw pointer is unsafe and requires unsafe block
  --> src\lib.rs:62:11
   |
62 |     val + *raw
   |           ^^^^ dereference of raw pointer
   |
   = note: raw pointers may be null, dangling or unaligned; they can violate aliasing rules and cause data races: all of these are undefined behavior
   = note: for more information, see <https://doc.rust-lang.org/edition-guide/rust-2024/unsafe-op-in-unsafe-fn.html>


running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.04s

     Running unittests src\bin\demo.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\demo-ba5bca82202fe275.exe)

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.04s

     Running tests\integration.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\integration-8ff5439ad4f72509.exe)

running 6 tests
test averages_only_positive ... FAILED
test counts_non_zero_bytes ... ok
test dedup_preserves_uniques ... ok
test fib_small_numbers ... ok
test normalize_simple ... ok
test sums_even_numbers ... error: Undefined Behavior: `assume` called with `false`
  --> src\lib.rs:11:22
   |
11 |             let v = *values.get_unchecked(idx);
   |                      ^^^^^^^^^^^^^^^^^^^^^^^^^ Undefined Behavior occurred here
   |
   = help: this indicates a bug in the program: it performed an invalid operation, and caused Undefined Behavior
   = help: see https://doc.rust-lang.org/nightly/reference/behavior-considered-undefined.html for further information
   = note: this is on thread `sums_even_numbers`
   = note: stack backtrace:
           0: broken_app::sum_even
               at src\lib.rs:11:22: 11:47
           1: sums_even_numbers
               at tests\integration.rs:7:16: 7:31
           2: sums_even_numbers::{closure#0}
               at tests\integration.rs:4:23: 4:23

note: some details are omitted, run with `MIRIFLAGS=-Zmiri-backtrace=full` for a verbose backtrace

error: aborting due to 1 previous error

error: test failed, to rerun pass `--test integration`

Caused by:
  process didn't exit successfully: `C:\Users\dubov\.rustup\toolchains\nightly-x86_64-pc-windows-msvc\bin\cargo-miri.exe runner 'D:\YPraktikum\Rust\module_5\broken-app\target\miri\x86_64-pc-windows-msvc\debug\deps\integration-8ff5439ad4f72509.exe'` (exit code: 1)
note: test exited abnormally; to see the full output pass --no-capture to the harness.
