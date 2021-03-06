## 2018-08-25, Version 0.7.0
### Commits
- [[`c4c5986191`](https://github.com/datrs/hypercore/commits/c4c5986191ab9dc07443264c65d0f2edc6971439)] (cargo-release) version 0.7.0 (Yoshua Wuyts)
- [[`7d6bde061c`](https://github.com/datrs/hypercore/commits/7d6bde061c6724a216f59ecd90970722b0c0f118)] Storage: implement keypair read/write (#18)
- [[`d027f37ed8`](https://github.com/datrs/hypercore/commits/d027f37ed8aa5c9a487a7e0260fa1ca0cd089011)] Update sparse-bitfield requirement from 0.4.0 to 0.8.0 (#20)
- [[`5d9b05f029`](https://github.com/datrs/hypercore/commits/5d9b05f029f2e1427770c4169794ce1cccd70ec5)] Update memory-pager requirement from 0.4.5 to 0.7.0
- [[`73a3f28e26`](https://github.com/datrs/hypercore/commits/73a3f28e26957c627254ed024092df7ae057d277)] Update sleep-parser requirement from 0.4.0 to 0.6.0
- [[`566b7a1021`](https://github.com/datrs/hypercore/commits/566b7a1021a36e7dc82ca22091ee21df88870d57)] Upgrade to latest random-access-storage (#17)
- [[`e086e60942`](https://github.com/datrs/hypercore/commits/e086e609428d015bc831384ff3e16a8c9a295bc7)] Add rustfmt back to travis (#19)
- [[`eb5edfba43`](https://github.com/datrs/hypercore/commits/eb5edfba438f8617d076f3a3f95636dfd3cc29ad)] (cargo-release) start next development iteration 0.6.1-alpha.0 (Yoshua Wuyts)

### Stats
```diff
 .travis.yml         |  1 +-
 Cargo.toml          | 14 ++++++------
 src/bitfield/mod.rs |  9 +++-----
 src/feed.rs         | 49 +++++++++++++++++++++++++++++--------------
 src/feed_builder.rs |  3 ++-
 src/lib.rs          |  2 +-
 src/storage/mod.rs  | 62 +++++++++++++++++++++++++++++++++++++++++++++++++-----
 tests/compat.rs     |  7 +++---
 tests/feed.rs       | 32 ++++++++++++++++++++++++++++-
 tests/helpers.rs    |  2 +-
 tests/storage.rs    | 54 +++++++++++++++++++++++++++++++++++++++++++++++-
 11 files changed, 197 insertions(+), 38 deletions(-)
```
