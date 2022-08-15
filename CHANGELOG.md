## 0.15.1 (2022-08-15)

### Bug Fixes

- benchmarks and add to gh action
  ([e1650e7](https://github.com/NuggetsLtd/node-bbs-signatures/commit/e1650e7e4cbfd6b2ad2a1894939548f08b1a4812))
- ci for release, reset package version
  ([0986725](https://github.com/NuggetsLtd/node-bbs-signatures/commit/09867254b91b6434d260bb2437ddc923132420a4))
- create proof with invalid message set ([#81](https://github.com/NuggetsLtd/node-bbs-signatures/issues/81))
  ([bf6453f](https://github.com/NuggetsLtd/node-bbs-signatures/commit/bf6453fe35369a837b47dadd4b484670bcd9f214))
- dev dependencies, update readme ([#1](https://github.com/NuggetsLtd/node-bbs-signatures/issues/1))
  ([6d418b5](https://github.com/NuggetsLtd/node-bbs-signatures/commit/6d418b569a86478ec8395a4cf2e11d2dec8dca0b))
- linting issues
  ([e70a9d6](https://github.com/NuggetsLtd/node-bbs-signatures/commit/e70a9d63c8f2a1168f941bf4951652dc05f701f0))
- linting issues, added in pre-pr script ([#13](https://github.com/NuggetsLtd/node-bbs-signatures/issues/13))
  ([4d5c127](https://github.com/NuggetsLtd/node-bbs-signatures/commit/4d5c1276b3d5bb73f0a5c4041d2c420e1de4c02b))
- native node module resolution ([#131](https://github.com/NuggetsLtd/node-bbs-signatures/issues/131))
  ([4cb57b7](https://github.com/NuggetsLtd/node-bbs-signatures/commit/4cb57b72b22243eb74394b74d1362ec06f509875))
- remove yarn error log ([#2](https://github.com/NuggetsLtd/node-bbs-signatures/issues/2))
  ([bb6a640](https://github.com/NuggetsLtd/node-bbs-signatures/commit/bb6a6407486f1149960c4b2f178278549e9d7b6e))
- strict check for given messages count and originally revealed
  ([#175](https://github.com/NuggetsLtd/node-bbs-signatures/issues/175))
  ([b9679d4](https://github.com/NuggetsLtd/node-bbs-signatures/commit/b9679d448d7250c13468b9441e99a4010a6958f3))
- ts-config ([#4](https://github.com/NuggetsLtd/node-bbs-signatures/issues/4))
  ([7fc7dc0](https://github.com/NuggetsLtd/node-bbs-signatures/commit/7fc7dc0930f8985da6be5fcbc26d2272608ff3ac))
- ts-config issue ([#3](https://github.com/NuggetsLtd/node-bbs-signatures/issues/3))
  ([a5e6125](https://github.com/NuggetsLtd/node-bbs-signatures/commit/a5e6125e725ceca1ea24528eedac5d52093ad1ca))
- tweaks to rust
  ([eeaad0b](https://github.com/NuggetsLtd/node-bbs-signatures/commit/eeaad0b48bf7f20d22bcaaa83a57cea9f66097cb))
- update bbs to 0.4.1 and run cargo update
  ([3ac291a](https://github.com/NuggetsLtd/node-bbs-signatures/commit/3ac291a557443c93ff061a188fdbdf267ef98d98))
- verify proof rust wrapper ([#71](https://github.com/NuggetsLtd/node-bbs-signatures/issues/71))
  ([b948144](https://github.com/NuggetsLtd/node-bbs-signatures/commit/b9481443d438eeb6449cb8fb25787269af46a111))

### Features

- add blinded bls12-381 key generation ([#130](https://github.com/NuggetsLtd/node-bbs-signatures/issues/130))
  ([9b2646e](https://github.com/NuggetsLtd/node-bbs-signatures/commit/9b2646e3eb41b0fb4a46448c137b715e319dcc30))
- add bls12-381 g1 key generation support ([#127](https://github.com/NuggetsLtd/node-bbs-signatures/issues/127))
  ([85e89a0](https://github.com/NuggetsLtd/node-bbs-signatures/commit/85e89a02e6649d4c31b1c07d252267d48f9b9c73))
- add create proof api ([#16](https://github.com/NuggetsLtd/node-bbs-signatures/issues/16))
  ([7dd5137](https://github.com/NuggetsLtd/node-bbs-signatures/commit/7dd513788eefc628ca38b6e211f3459dcf6e3329))
- add key length constants ([#26](https://github.com/NuggetsLtd/node-bbs-signatures/issues/26))
  ([5ae266c](https://github.com/NuggetsLtd/node-bbs-signatures/commit/5ae266c18f46af9a2871673061486caf1e1da126))
- add license header to files ([#61](https://github.com/NuggetsLtd/node-bbs-signatures/issues/61))
  ([7170cf6](https://github.com/NuggetsLtd/node-bbs-signatures/commit/7170cf63f0216392ccc538e2cacfd8161b475450))
- add proof create and verify benchmarks ([#62](https://github.com/NuggetsLtd/node-bbs-signatures/issues/62))
  ([e85a5ed](https://github.com/NuggetsLtd/node-bbs-signatures/commit/e85a5ed8b3510f4963348390d59163b8a9973e6e))
- add simple runnable sample ([#94](https://github.com/NuggetsLtd/node-bbs-signatures/issues/94))
  ([5b7acd4](https://github.com/NuggetsLtd/node-bbs-signatures/commit/5b7acd4092fec1e3cd459297fb74b11f7fa05079))
- adding github actions to backup repository to s3
  ([#188](https://github.com/NuggetsLtd/node-bbs-signatures/issues/188))
  ([93f5f41](https://github.com/NuggetsLtd/node-bbs-signatures/commit/93f5f41aa3921c3cf78ef001272d7eaad1b3c6fc))
- change to async based api ([#136](https://github.com/NuggetsLtd/node-bbs-signatures/issues/136))
  ([92450c3](https://github.com/NuggetsLtd/node-bbs-signatures/commit/92450c34714f8039d222feb2106cc63701b4d42a))
- expose create and verify proof ([#52](https://github.com/NuggetsLtd/node-bbs-signatures/issues/52))
  ([170f65f](https://github.com/NuggetsLtd/node-bbs-signatures/commit/170f65f8bf9d8ca18b5e9783087a3e143f667d52))
- remove challenge validation from bbs blind sign ([#12](https://github.com/NuggetsLtd/node-bbs-signatures/issues/12))
  ([a91b17e](https://github.com/NuggetsLtd/node-bbs-signatures/commit/a91b17e700430e59f8f44cd574f1f3ccc1b17218))
- sign and verify bbs+ signature support ([#11](https://github.com/NuggetsLtd/node-bbs-signatures/issues/11))
  ([5992833](https://github.com/NuggetsLtd/node-bbs-signatures/commit/5992833b9606f5b146012233149ae6f43771b575))
- support building for node 13 and 14 ([#118](https://github.com/NuggetsLtd/node-bbs-signatures/issues/118))
  ([19be9e1](https://github.com/NuggetsLtd/node-bbs-signatures/commit/19be9e1d945c03fbd85830a969b370f222bf5203))
- update benchmarks ([#47](https://github.com/NuggetsLtd/node-bbs-signatures/issues/47))
  ([2d8650b](https://github.com/NuggetsLtd/node-bbs-signatures/commit/2d8650b88e086bbbb7a21bbe387eb52c549a7bc7))
- update rust wrapper for bbs ([#46](https://github.com/NuggetsLtd/node-bbs-signatures/issues/46))
  ([ebbf895](https://github.com/NuggetsLtd/node-bbs-signatures/commit/ebbf895a329e4bc81054694afcbf55ed2f70d405))
- update sample ([#112](https://github.com/NuggetsLtd/node-bbs-signatures/issues/112))
  ([3ff8c0f](https://github.com/NuggetsLtd/node-bbs-signatures/commit/3ff8c0f333e041a18c008799a064046535aebba5))
- update to bbs 0.3.0 crate
  ([c6f635e](https://github.com/NuggetsLtd/node-bbs-signatures/commit/c6f635e5c2734ee76d7a36ef3f7b26ba48d51d16))
- update to bbs 0.4.0 crate ([#109](https://github.com/NuggetsLtd/node-bbs-signatures/issues/109))
  ([c5f3a9c](https://github.com/NuggetsLtd/node-bbs-signatures/commit/c5f3a9c961beeb3165dbfb1982b4f5bb20fd18f9))

### BREAKING CHANGES

- All API's now return a promise instead of the raw result
- generateBls12381KeyPair has been changed to generateBls12381G2KeyPair

# [0.15.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.14.0...0.15.0) (2022-07-11)

### Bug Fixes

- update bbs to 0.4.1 and run cargo update
  ([3ac291a](https://github.com/mattrglobal/node-bbs-signatures/commit/3ac291a557443c93ff061a188fdbdf267ef98d98))

# [0.14.0](https://github.com/mattrglobal/node-bbs-signatures/compare/v0.13.0...v0.14.0) (2022-06-23)

### Features

- upgrade dependencies
- adding github actions to backup repository to s3
  ([#188](https://github.com/mattrglobal/node-bbs-signatures/issues/188))
  ([93f5f41](https://github.com/mattrglobal/node-bbs-signatures/commit/93f5f41aa3921c3cf78ef001272d7eaad1b3c6fc))

# [0.13.0](https://github.com/mattrglobal/node-bbs-signatures/compare/v0.12.0...v0.13.0) (2021-11-30)

### Bug Fixes

- strict check for given messages count and originally revealed
  ([#175](https://github.com/mattrglobal/node-bbs-signatures/issues/175))
  ([b9679d4](https://github.com/mattrglobal/node-bbs-signatures/commit/b9679d448d7250c13468b9441e99a4010a6958f3))

# [0.12.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.11.0...0.12.0) (2021-05-21)

Add NodeJS version 15 and 16 support

### Bug Fixes

- benchmarks and add to gh action
  ([e1650e7](https://github.com/mattrglobal/node-bbs-signatures/commit/e1650e7e4cbfd6b2ad2a1894939548f08b1a4812))

# [0.11.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.10.0...0.11.0) (2020-11-23)

### Features

- change to async based api ([#136](https://github.com/mattrglobal/node-bbs-signatures/issues/136))
  ([92450c3](https://github.com/mattrglobal/node-bbs-signatures/commit/92450c34714f8039d222feb2106cc63701b4d42a))

### BREAKING CHANGES

- All API's now return a promise instead of the raw result

# [0.10.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.9.0...0.10.0) (2020-08-27)

### Bug Fixes

- native node module resolution ([#131](https://github.com/mattrglobal/node-bbs-signatures/issues/131))
  ([4cb57b7](https://github.com/mattrglobal/node-bbs-signatures/commit/4cb57b72b22243eb74394b74d1362ec06f509875))

### Features

- add blinded bls12-381 key generation ([#130](https://github.com/mattrglobal/node-bbs-signatures/issues/130))
  ([9b2646e](https://github.com/mattrglobal/node-bbs-signatures/commit/9b2646e3eb41b0fb4a46448c137b715e319dcc30))
- add bls12-381 g1 key generation support ([#127](https://github.com/mattrglobal/node-bbs-signatures/issues/127))
  ([85e89a0](https://github.com/mattrglobal/node-bbs-signatures/commit/85e89a02e6649d4c31b1c07d252267d48f9b9c73))

### BREAKING CHANGES

- generateBls12381KeyPair has been changed to generateBls12381G2KeyPair
- All operations involving messages and nonces are now in terms of Uint8Array's rather than strings

# [0.9.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.8.0...0.9.0) (2020-06-18)

### Features

- support building for node 13 and 14 ([#118](https://github.com/mattrglobal/node-bbs-signatures/issues/118))
  ([19be9e1](https://github.com/mattrglobal/node-bbs-signatures/commit/19be9e1d945c03fbd85830a969b370f222bf5203))
- update sample ([#112](https://github.com/mattrglobal/node-bbs-signatures/issues/112))
  ([3ff8c0f](https://github.com/mattrglobal/node-bbs-signatures/commit/3ff8c0f333e041a18c008799a064046535aebba5))

# [0.8.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.7.0...0.8.0) (2020-05-19)

### Features

- update to bbs 0.4.0 crate ([#109](https://github.com/mattrglobal/node-bbs-signatures/issues/109))
  ([c5f3a9c](https://github.com/mattrglobal/node-bbs-signatures/commit/c5f3a9c961beeb3165dbfb1982b4f5bb20fd18f9))

# [0.7.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.6.0...0.7.0) (2020-05-04)

- add support for publishing Node 11 and Node 12 binaries
  ([#100](https://github.com/mattrglobal/node-bbs-signatures/issues/100))
  ([eb9a667](https://github.com/mattrglobal/node-bbs-signatures/pull/104/commits/eb9a667e98a9bade59d874a5f91bcc862f130a32))
  ([f1af7ee](https://github.com/mattrglobal/node-bbs-signatures/pull/105/commits/f1af7eebc8561b43cea286426e744dbb8758a450))

# [0.6.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.5.0...0.6.0) (2020-05-03)

### Features

- add simple runnable sample ([#94](https://github.com/mattrglobal/node-bbs-signatures/issues/94))
  ([5b7acd4](https://github.com/mattrglobal/node-bbs-signatures/commit/5b7acd4092fec1e3cd459297fb74b11f7fa05079))
- update to bbs 0.3.0 crate
  ([c6f635e](https://github.com/mattrglobal/node-bbs-signatures/commit/c6f635e5c2734ee76d7a36ef3f7b26ba48d51d16))

# [0.5.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.3.0...0.5.0) (2020-04-28)

Updates to package release configuration

# [0.4.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.3.0...0.4.0) (2020-04-28)

Updates to package release configuration

# [0.3.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.1.0...0.3.0) (2020-04-28)

Version bump due to NPM package publishing issue caused by prior delete 0.2.0 release

# [0.2.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.1.0...0.2.0) (2020-04-28)

### Bug Fixes

- create proof with invalid message set ([#81](https://github.com/mattrglobal/node-bbs-signatures/issues/81))
  ([bf6453f](https://github.com/mattrglobal/node-bbs-signatures/commit/bf6453fe35369a837b47dadd4b484670bcd9f214))

# [0.1.0](https://github.com/mattrglobal/node-bbs-signatures/compare/0.2.0...0.1.0) (2020-04-26)

Initial release
