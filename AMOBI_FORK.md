# Amobi SQLite core source fork

- Upstream: <https://github.com/powersync-ja/powersync-sqlite-core>
- Baseline: `v0.5.3`, commit `2ba6b280975c546ed913a73e634aec016e21bb8d`
- Annotated upstream tag object: `77a2ddb6c216250746a325529c3b9e959a65f36d`
- Source archive SHA-256: `e0304170d0adaf6bee192a86b9e7268547f269da80609ee6368bbbadd37a287c`
- License: Apache-2.0; upstream LICENSE and NOTICE retained.
- Amobi patches: none yet; source/API unchanged.

This is the shared Rust-based SQLite extension source used by multiple SDKs. The
forked source does not yet provide Amobi-hosted release binaries; Kotlin, Swift
and existing Flutter packages still consume upstream-published native artifacts.
