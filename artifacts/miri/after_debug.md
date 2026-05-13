$ cargo +nightly miri test
   Compiling proc-macro2 v1.0.103
   Compiling unicode-ident v1.0.22
   Compiling quote v1.0.42
   Compiling windows-link v0.2.1
   Compiling stable_deref_trait v1.2.1
   Compiling cfg-if v1.0.4
   Compiling pin-project-lite v0.2.17
   Compiling bytes v1.11.1
   Compiling smallvec v1.15.1
   Compiling itoa v1.0.15
   Compiling memchr v2.7.6
   Compiling futures-core v0.3.32
   Compiling windows-sys v0.61.2
   Compiling shlex v1.3.0
   Compiling find-msvc-tools v0.1.9
   Compiling serde_core v1.0.228
   Compiling writeable v0.6.3
   Compiling litemap v0.8.2
   Compiling icu_normalizer_data v2.1.1
   Compiling once_cell v1.21.3
   Compiling icu_properties_data v2.1.2
   Compiling http v1.4.0
   Compiling percent-encoding v2.3.2
   Compiling serde v1.0.228
   Compiling crc32fast v1.5.0
   Compiling futures-io v0.3.32
   Compiling cc v1.2.61
   Compiling zeroize v1.8.2
   Compiling getrandom v0.2.17
   Compiling rustls-pki-types v1.14.1
   Compiling simd-adler32 v0.3.9
   Compiling adler2 v2.0.1
   Compiling syn v2.0.111
   Compiling untrusted v0.9.0
   Compiling http-body v1.0.1
   Compiling slab v0.4.12
   Compiling futures-task v0.3.32
   Compiling httparse v1.10.1
   Compiling miniz_oxide v0.8.9
   Compiling ryu v1.0.20
   Compiling try-lock v0.2.5
   Compiling rustls v0.23.40
   Compiling futures-util v0.3.32
   Compiling tower-service v0.3.3
   Compiling libc v0.2.186
   Compiling windows_x86_64_msvc v0.52.6
   Compiling want v0.3.1
   Compiling flate2 v1.1.9
   Compiling form_urlencoded v1.2.2
   Compiling tracing-core v0.1.36
   Compiling futures-channel v0.3.32
   Compiling windows-strings v0.5.1
   Compiling windows-result v0.4.1
   Compiling mio v1.2.0
   Compiling socket2 v0.6.3
   Compiling subtle v2.6.1
   Compiling atomic-waker v1.1.2
   Compiling utf8_iter v1.0.4
   Compiling tracing v0.1.44
   Compiling sync_wrapper v1.0.2
   Compiling ring v0.17.14
   Compiling thiserror v2.0.18
   Compiling tower-layer v0.3.3
   Compiling ipnet v2.12.0
   Compiling bitflags v2.11.1
   Compiling powerfmt v0.2.0
   Compiling base64 v0.22.1
   Compiling ref-cast v1.0.25
   Compiling tokio v1.52.2
   Compiling windows-targets v0.52.6
   Compiling webpki-roots v1.0.7
   Compiling crossbeam-utils v0.8.21
   Compiling deranged v0.5.8
   Compiling compression-core v0.4.32
   Compiling num-conv v0.2.1
   Compiling time-core v0.1.8
   Compiling option-ext v0.2.0
   Compiling futures-sink v0.3.32
   Compiling dirs-sys v0.5.0
   Compiling compression-codecs v0.4.38
   Compiling windows-sys v0.59.0
   Compiling synstructure v0.13.2
   Compiling http-body-util v0.1.3
   Compiling inplace-vec-builder v0.1.1
   Compiling windows-threading v0.2.1
   Compiling lzxd v0.2.6
   Compiling log v0.4.29
   Compiling zerocopy v0.8.31
   Compiling scroll v0.12.0
   Compiling twox-hash v2.1.2
   Compiling object v0.38.1
   Compiling uuid v1.23.1
   Compiling time v0.3.47
   Compiling binary-merge v0.1.2
   Compiling fallible-iterator v0.3.0
   Compiling byteorder v1.5.0
   Compiling fs4 v0.13.1
   Compiling ruzstd v0.8.2
   Compiling pdb2 v0.9.2
   Compiling dirs v6.0.0
   Compiling elsa v1.11.2
   Compiling scopeguard v1.2.0
   Compiling autocfg v1.5.0
   Compiling cab v0.6.0
   Compiling maybe-owned v0.3.4
   Compiling rustc-hash v2.1.2
   Compiling either v1.15.0
   Compiling serde_json v1.0.145
   Compiling rayon-core v1.13.0
   Compiling crossbeam-epoch v0.9.18
   Compiling winapi-util v0.1.11
   Compiling clap_lex v0.7.6
   Compiling regex-syntax v0.8.8
   Compiling crossbeam-deque v0.8.6
   Compiling anstyle v1.0.13
   Compiling ciborium-io v0.2.2
   Compiling num-traits v0.2.19
   Compiling plotters-backend v0.3.7
   Compiling same-file v1.0.6
   Compiling clap_builder v4.5.53
   Compiling itertools v0.10.5
   Compiling cast v0.3.0
   Compiling hyper v1.9.0
   Compiling tower v0.5.3
   Compiling tokio-util v0.7.18
   Compiling async-compression v0.4.42
   Compiling regex-automata v0.4.13
   Compiling plotters-svg v0.3.7
   Compiling rayon v1.11.0
   Compiling walkdir v2.5.0
   Compiling is-terminal v0.4.17
   Compiling hyper-util v0.1.20
   Compiling oorandom v11.1.5
   Compiling anes v0.1.6
   Compiling criterion-plot v0.5.0
   Compiling plotters v0.3.7
   Compiling zerofrom-derive v0.1.6
   Compiling yoke-derive v0.8.1
   Compiling zerovec-derive v0.11.2
   Compiling displaydoc v0.2.5
   Compiling serde_derive v1.0.228
   Compiling windows-interface v0.59.3
   Compiling windows-implement v0.60.2
   Compiling ref-cast-impl v1.0.25
   Compiling thiserror-impl v2.0.18
   Compiling zerocopy-derive v0.8.31
   Compiling rustls-webpki v0.103.13
   Compiling regex v1.12.2
   Compiling clap v4.5.53
   Compiling range-collections v0.4.6
   Compiling windows-core v0.62.2
   Compiling zerofrom v0.1.7
   Compiling windows-collections v0.3.2
   Compiling windows-future v0.3.2
   Compiling windows-numerics v0.3.1
   Compiling yoke v0.8.1
   Compiling pdb-addr2line v0.11.2
   Compiling zerovec v0.11.5
   Compiling zerotrie v0.2.3
   Compiling windows v0.62.2
   Compiling tinystr v0.8.2
   Compiling potential_utf v0.1.4
   Compiling icu_collections v2.1.1
   Compiling serde_urlencoded v0.7.1
   Compiling tinytemplate v1.2.1
   Compiling icu_locale_core v2.1.1
   Compiling half v2.7.1
   Compiling ciborium-ll v0.2.2
   Compiling ciborium v0.2.2
   Compiling criterion v0.5.1
   Compiling icu_provider v2.1.1
   Compiling tokio-rustls v0.26.4
   Compiling icu_normalizer v2.1.1
   Compiling icu_properties v2.1.2
   Compiling hyper-rustls v0.27.9
   Compiling idna_adapter v1.2.1
   Compiling idna v1.1.0
   Compiling url v2.5.8
   Compiling tower-http v0.6.9
   Compiling reqwest v0.12.28
   Compiling symsrv v0.5.6
   Compiling blondie v0.5.3
   Compiling broken-app v0.1.0 (D:\YPraktikum\Rust\broken_app)
    Finished `test` profile [unoptimized + debuginfo] target(s) in 23.12s
     Running unittests src\lib.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\broken_app-54b32805bae0ea5a.exe)

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.04s

     Running unittests src\main.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\broken_app-913d57b9dfb4dbaf.exe)

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.04s

     Running unittests src\bin\demo.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\demo-867ce32e44dbaabd.exe)

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.04s

     Running tests\integration.rs (target\miri\x86_64-pc-windows-msvc\debug\deps\integration-82a5531b4780607c.exe)

running 6 tests
test averages_only_positive ... ok
test counts_non_zero_bytes ... ok
test dedup_preserves_uniques ... ok
test fib_small_numbers ... ok
test normalize_simple ... ok
test sums_even_numbers ... ok

test result: ok. 6 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.82s

   Doc-tests broken_app

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s
