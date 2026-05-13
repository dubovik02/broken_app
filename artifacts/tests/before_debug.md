Running unittests src\bin\demo.rs (target\debug\deps\demo-c6d4128acf3f4490.exe)

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s

     Running tests\integration.rs (target\debug\deps\integration-992c4c6f76592797.exe)

running 6 tests
test counts_non_zero_bytes ...
thread 'sums_even_numbers' (16068) panicked at src\lib.rs:11:29:
unsafe precondition(s) violated: slice::get_unchecked requires that the index is within the slice

This indicates a bug in the program. This Undefined Behavior check is optional, and cannot be relied on for safety.
thread caused non-unwinding panic. aborting.
error: test failed, to rerun pass `--test integration`

Caused by:
  process didn't exit successfully: `D:\YPraktikum\Rust\module_5\broken-app\target\debug\deps\integration-992c4c6f76592797.exe` (exit code: 0xc0000409, STATUS_STACK_BUFFER_OVERRUN)
note: test exited abnormally; to see the full output pass --no-capture to the harness.

