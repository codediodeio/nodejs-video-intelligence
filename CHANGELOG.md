# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/@google-cloud/video-intelligence?activeTab=versions

### [2.2.2](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.2.1...v2.2.2) (2019-08-05)


### Bug Fixes

* allow calls with no request, add JSON proto ([8fb7221](https://www.github.com/googleapis/nodejs-video-intelligence/commit/8fb7221))

### [2.2.1](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.2.0...v2.2.1) (2019-06-26)


### Bug Fixes

* **docs:** link to reference docs section on googleapis.dev ([#266](https://www.github.com/googleapis/nodejs-video-intelligence/issues/266)) ([f992de6](https://www.github.com/googleapis/nodejs-video-intelligence/commit/f992de6))

## [2.2.0](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.1.2...v2.2.0) (2019-06-20)


### Features

* support streaming automl configs ([#261](https://www.github.com/googleapis/nodejs-video-intelligence/issues/261)) ([ca3e0d3](https://www.github.com/googleapis/nodejs-video-intelligence/commit/ca3e0d3))

### [2.1.2](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.1.1...v2.1.2) (2019-06-13)


### Bug Fixes

* **docs:** move to new client docs URL ([#257](https://www.github.com/googleapis/nodejs-video-intelligence/issues/257)) ([fccfb8d](https://www.github.com/googleapis/nodejs-video-intelligence/commit/fccfb8d))

### [2.1.1](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.1.0...v2.1.1) (2019-06-10)


### Bug Fixes

* Update example commands to use cloud-storage-samples bucket ([#253](https://www.github.com/googleapis/nodejs-video-intelligence/issues/253)) ([3a80413](https://www.github.com/googleapis/nodejs-video-intelligence/commit/3a80413))

## [2.1.0](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.0.1...v2.1.0) (2019-06-05)


### Features

* add ObjectTrackingConfig and support apiEndpoint ([#249](https://www.github.com/googleapis/nodejs-video-intelligence/issues/249)) ([bac9326](https://www.github.com/googleapis/nodejs-video-intelligence/commit/bac9326))

### [2.0.1](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v2.0.0...v2.0.1) (2019-05-20)


### Bug Fixes

* update min dependencies and use repo-tools to generate README ([#236](https://www.github.com/googleapis/nodejs-video-intelligence/issues/236)) ([81dfa09](https://www.github.com/googleapis/nodejs-video-intelligence/commit/81dfa09))

## [2.0.0](https://www.github.com/googleapis/nodejs-video-intelligence/compare/v1.6.0...v2.0.0) (2019-05-13)


### Bug Fixes

* DEADLINE_EXCEEDED retry code is idempotent ([#234](https://www.github.com/googleapis/nodejs-video-intelligence/issues/234)) ([7a98ca6](https://www.github.com/googleapis/nodejs-video-intelligence/commit/7a98ca6))
* **deps:** update dependency google-gax to v1 ([#233](https://www.github.com/googleapis/nodejs-video-intelligence/issues/233)) ([0ad08b2](https://www.github.com/googleapis/nodejs-video-intelligence/commit/0ad08b2))
* DEADLINE_EXCEEDED no longer treated as idempotent and retried  ([#228](https://www.github.com/googleapis/nodejs-video-intelligence/issues/228)) ([c25517e](https://www.github.com/googleapis/nodejs-video-intelligence/commit/c25517e))
* **deps:** update dependency google-gax to ^0.26.0 ([#222](https://www.github.com/googleapis/nodejs-video-intelligence/issues/222)) ([22de82b](https://www.github.com/googleapis/nodejs-video-intelligence/commit/22de82b))


### Build System

* upgrade engines field to >=8.10.0 ([#223](https://www.github.com/googleapis/nodejs-video-intelligence/issues/223)) ([966eef9](https://www.github.com/googleapis/nodejs-video-intelligence/commit/966eef9))


### BREAKING CHANGES

* upgrade engines field to >=8.10.0 (#223)

## v1.6.0

02-21-2019 13:46 PST

### Implementation Changes
- fix: throw on invalid credentials

### New Features
- feat: generate v1p3beta1 with streaming support ([#198](https://github.com/googleapis/nodejs-video-intelligence/pull/198))
- feat: add text detection and object mapping support ([#197](https://github.com/googleapis/nodejs-video-intelligence/pull/197))

### Dependencies
- chore(deps): update dependency mocha to v6
- fix(deps): update dependency yargs to v13 ([#192](https://github.com/googleapis/nodejs-video-intelligence/pull/192))

### Documentation
- docs: update links in contrib guide ([#195](https://github.com/googleapis/nodejs-video-intelligence/pull/195))
- build: create docs test npm scripts ([#191](https://github.com/googleapis/nodejs-video-intelligence/pull/191))
- docs: update contributing path in README ([#189](https://github.com/googleapis/nodejs-video-intelligence/pull/189))

### Internal / Testing Changes
- build: use linkinator for docs test ([#194](https://github.com/googleapis/nodejs-video-intelligence/pull/194))
- build: test using @grpc/grpc-js in CI ([#190](https://github.com/googleapis/nodejs-video-intelligence/pull/190))
- chore: move CONTRIBUTING.md to root ([#188](https://github.com/googleapis/nodejs-video-intelligence/pull/188))

## v1.5.1

02-05-2019 15:05 PST

### Fixes
- fix: increase gRPC timeout window ([#139](https://github.com/googleapis/nodejs-video-intelligence/pull/139))

### Dependencies
- fix(deps): update dependency google-gax to ^0.25.0 ([#183](https://github.com/googleapis/nodejs-video-intelligence/pull/183))
- refactor: remove unused deps and fix lint ([#141](https://github.com/googleapis/nodejs-video-intelligence/pull/141))

### Documentation
- docs: add lint/fix example to contributing guide ([#185](https://github.com/googleapis/nodejs-video-intelligence/pull/185))
- docs: remove unused long running operation message typesed  to pick up changes in the API or client library generator. ([#176](https://github.com/googleapis/nodejs-video-intelligence/pull/176))
- docs: fix filepath of example command in README ([#160](https://github.com/googleapis/nodejs-video-intelligence/pull/160))
- docs: fix typo in samples/analyze.js ([#159](https://github.com/googleapis/nodejs-video-intelligence/pull/159))
- docs: update readme badges ([#156](https://github.com/googleapis/nodejs-video-intelligence/pull/156))
- docs(samples): update samples to use GA APIs ([#153](https://github.com/googleapis/nodejs-video-intelligence/pull/153))
- docs(samples): updated samples code to use async await ([#151](https://github.com/googleapis/nodejs-video-intelligence/pull/151))

## v1.5.0

### New features
- feat: add speech transcription

### Documentation
- docs(samples): video beta samples ([#123](https://github.com/googleapis/nodejs-video-intelligence/pull/123))

### Internal / Testing Changes
- chore: update issue templates ([#128](https://github.com/googleapis/nodejs-video-intelligence/pull/128))
- chore: remove old issue template ([#124](https://github.com/googleapis/nodejs-video-intelligence/pull/124))
- build: run tests on node11 ([#122](https://github.com/googleapis/nodejs-video-intelligence/pull/122))
- chores(build): do not collect sponge.xml from windows builds ([#121](https://github.com/googleapis/nodejs-video-intelligence/pull/121))
- chores(build): run codecov on continuous builds ([#120](https://github.com/googleapis/nodejs-video-intelligence/pull/120))
- chore: update new issue template ([#119](https://github.com/googleapis/nodejs-video-intelligence/pull/119))

## v1.4.1

### Implementation Changes
- chore: minor generator changes ([#110](https://github.com/googleapis/nodejs-video-intelligence/pull/110))

### Internal / Testing Changes
- build: fix codecov uploading on Kokoro ([#112](https://github.com/googleapis/nodejs-video-intelligence/pull/112))
- Update kokoro config ([#109](https://github.com/googleapis/nodejs-video-intelligence/pull/109))
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#108](https://github.com/googleapis/nodejs-video-intelligence/pull/108))
- Update CI config ([#105](https://github.com/googleapis/nodejs-video-intelligence/pull/105))
- test: remove appveyor config ([#106](https://github.com/googleapis/nodejs-video-intelligence/pull/106))
- Enable prefer-const in the eslint config ([#102](https://github.com/googleapis/nodejs-video-intelligence/pull/102))
- Enable no-var in eslint ([#101](https://github.com/googleapis/nodejs-video-intelligence/pull/101))

## v1.4.0

### New Features
- feat: release v1p2beta1 client (Object tracking and Text detecting beta) ([#98](https://github.com/googleapis/nodejs-video-intelligence/pull/98))

### Dependencies
- fix(deps): update dependency google-gax to ^0.20.0 ([#96](https://github.com/googleapis/nodejs-video-intelligence/pull/96))

### Internal / Testing Changes
- Switch to let/const ([#97](https://github.com/googleapis/nodejs-video-intelligence/pull/97))
- test: throw on deprecation ([#72](https://github.com/googleapis/nodejs-video-intelligence/pull/72))
- Update CI config ([#95](https://github.com/googleapis/nodejs-video-intelligence/pull/95))
- Retry npm install in CI ([#93](https://github.com/googleapis/nodejs-video-intelligence/pull/93))
- add templates to synth.py ([#91](https://github.com/googleapis/nodejs-video-intelligence/pull/91))
