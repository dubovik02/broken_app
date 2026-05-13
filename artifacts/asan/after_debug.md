$ RUSTFLAGS="-Zsanitizer=address" cargo +nightly test --target x86_64-pc-windows-msvc --test integration
    Finished `test` profile [unoptimized + debuginfo] target(s) in 0.43s
     Running tests\integration.rs (target\x86_64-pc-windows-msvc\debug\deps\integration-56109bb89aa0e48a.exe)

running 6 tests
test averages_only_positive ... ok
test counts_non_zero_bytes ... ok
test dedup_preserves_uniques ... ok
test fib_small_numbers ... ok
test normalize_simple ... ok
test sums_even_numbers ... ok

test result: ok. 6 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.01s
