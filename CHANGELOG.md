# Changelog

All notable changes to this project will be documented in this file.

## [v3.5.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.5.0) (2024-01-01)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.4.0...v3.5.0)

**Breaking changes:**

- Drop Ruby 2.5 support [\#351](https://github.com/voxpupuli/hiera-eyaml/pull/351) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Load configuration file from working directory [\#356](https://github.com/voxpupuli/hiera-eyaml/pull/356) ([micmax93](https://github.com/micmax93))
- Update gems and introduce rubocop [\#353](https://github.com/voxpupuli/hiera-eyaml/pull/353) ([bastelfreak](https://github.com/bastelfreak))

**Closed issues:**

- Remote Code Execution vulnerability in the hiera-eyaml tool [\#354](https://github.com/voxpupuli/hiera-eyaml/issues/354)

**Merged pull requests:**

- fix: upgrade to aruba-2/cucumber-8 [\#360](https://github.com/voxpupuli/hiera-eyaml/pull/360) ([robbat2](https://github.com/robbat2))
- Drop EoL Puppet 6 testing [\#358](https://github.com/voxpupuli/hiera-eyaml/pull/358) ([bastelfreak](https://github.com/bastelfreak))
- rubocop: autofix [\#357](https://github.com/voxpupuli/hiera-eyaml/pull/357) ([bastelfreak](https://github.com/bastelfreak))
- Bump actions/checkout from 3 to 4 [\#355](https://github.com/voxpupuli/hiera-eyaml/pull/355) ([dependabot[bot]](https://github.com/apps/dependabot))
- CI: Build gems with strictness and verbosity [\#348](https://github.com/voxpupuli/hiera-eyaml/pull/348) ([bastelfreak](https://github.com/bastelfreak))

## [v3.4.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.4.0) (2023-05-26)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.3.0...v3.4.0)

**Implemented enhancements:**

- Add Puppet 8 to CI matrix [\#349](https://github.com/voxpupuli/hiera-eyaml/pull/349) ([bastelfreak](https://github.com/bastelfreak))
- Add Ruby 3.2 support [\#340](https://github.com/voxpupuli/hiera-eyaml/pull/340) ([pschrammel](https://github.com/pschrammel))

**Fixed bugs:**

- Puppet 7: Ensure we test against 7.24 or newer [\#347](https://github.com/voxpupuli/hiera-eyaml/pull/347) ([bastelfreak](https://github.com/bastelfreak))
- Run puppet main branch on Ruby 3.1 and newer [\#346](https://github.com/voxpupuli/hiera-eyaml/pull/346) ([bastelfreak](https://github.com/bastelfreak))

**Closed issues:**

- Encrypt yaml file on my workstation and push to git [\#344](https://github.com/voxpupuli/hiera-eyaml/issues/344)
- hiera lookup arbitrary hierachy level [\#185](https://github.com/voxpupuli/hiera-eyaml/issues/185)

**Merged pull requests:**

- Apply Vox Pupuli CI best practices [\#345](https://github.com/voxpupuli/hiera-eyaml/pull/345) ([bastelfreak](https://github.com/bastelfreak))
- Bump actions/checkout from 2 to 3 [\#343](https://github.com/voxpupuli/hiera-eyaml/pull/343) ([dependabot[bot]](https://github.com/apps/dependabot))
- Add dependabot for gems and github actions [\#342](https://github.com/voxpupuli/hiera-eyaml/pull/342) ([bastelfreak](https://github.com/bastelfreak))
- CI: Ensure we use Puppet 6.29 or newer [\#341](https://github.com/voxpupuli/hiera-eyaml/pull/341) ([bastelfreak](https://github.com/bastelfreak))
- README: Add apt to installation methods [\#338](https://github.com/voxpupuli/hiera-eyaml/pull/338) ([AntoineSebert](https://github.com/AntoineSebert))

## [v3.3.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.3.0) (2022-05-20)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.2.2...v3.3.0)

**Implemented enhancements:**

- Build gem during CI [\#330](https://github.com/voxpupuli/hiera-eyaml/pull/330) ([bastelfreak](https://github.com/bastelfreak))
- Add more Ruby/Puppet versions to CI matrix [\#326](https://github.com/voxpupuli/hiera-eyaml/pull/326) ([bastelfreak](https://github.com/bastelfreak))

**Fixed bugs:**

- Repair ruby 3.1.x compability with backwards compability. Bumped vers… [\#329](https://github.com/voxpupuli/hiera-eyaml/pull/329) ([mmachner](https://github.com/mmachner))
- Fix an "undefined method" error with rubygems \>= 3.3.0 [\#327](https://github.com/voxpupuli/hiera-eyaml/pull/327) ([davidsansome](https://github.com/davidsansome))

## [v3.2.2](https://github.com/voxpupuli/hiera-eyaml/tree/v3.2.2) (2021-05-03)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.2.1...v3.2.2)

**Fixed bugs:**

- Using `3.2.1` for editing an eyaml created with `3.2.0` will mess up formatting [\#318](https://github.com/voxpupuli/hiera-eyaml/issues/318)
- Fix block formatting when editing [\#319](https://github.com/voxpupuli/hiera-eyaml/pull/319) ([kenyon](https://github.com/kenyon))

**Closed issues:**

- Concerns about the encrypted? method [\#316](https://github.com/voxpupuli/hiera-eyaml/issues/316)

## [v3.2.1](https://github.com/voxpupuli/hiera-eyaml/tree/v3.2.1) (2021-02-16)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.2.0...v3.2.1)

**Fixed bugs:**

- remove question mark from regex in encrypted? method [\#313](https://github.com/voxpupuli/hiera-eyaml/pull/313) ([mcka1n](https://github.com/mcka1n))
- Fix block folding [\#307](https://github.com/voxpupuli/hiera-eyaml/pull/307) ([kenyon](https://github.com/kenyon))
- add step-by-step how-to encrypting multiline values [\#304](https://github.com/voxpupuli/hiera-eyaml/pull/304) ([kBite](https://github.com/kBite))

**Closed issues:**

- eyaml edit should produce evenly folded blocks. [\#281](https://github.com/voxpupuli/hiera-eyaml/issues/281)
- Support version 4 hiera config [\#213](https://github.com/voxpupuli/hiera-eyaml/issues/213)

**Merged pull requests:**

- migrate CI to github actions [\#315](https://github.com/voxpupuli/hiera-eyaml/pull/315) ([bastelfreak](https://github.com/bastelfreak))
- gemspec: fix repo url / Drop Puppet 4/5 tests [\#311](https://github.com/voxpupuli/hiera-eyaml/pull/311) ([bastelfreak](https://github.com/bastelfreak))
- Unpin highline [\#310](https://github.com/voxpupuli/hiera-eyaml/pull/310) ([lucywyman](https://github.com/lucywyman))

## [v3.2.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.2.0) (2020-01-31)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.1.1...v3.2.0)

**Implemented enhancements:**

- Permit reading private key from environment variable [\#294](https://github.com/voxpupuli/hiera-eyaml/pull/294) ([nferch](https://github.com/nferch))

**Fixed bugs:**

- Version 3.1.0 does not clear the private/public key when options are changed [\#289](https://github.com/voxpupuli/hiera-eyaml/issues/289)

**Merged pull requests:**

- \(doc\) Correct order for config file precedence [\#295](https://github.com/voxpupuli/hiera-eyaml/pull/295) ([crayfishx](https://github.com/crayfishx))
- \(maint\) Update Gemfile and README for Ruby 2.5/2.4 [\#293](https://github.com/voxpupuli/hiera-eyaml/pull/293) ([glennsarti](https://github.com/glennsarti))

## [v3.1.1](https://github.com/voxpupuli/hiera-eyaml/tree/v3.1.1) (2019-11-12)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.1.0...v3.1.1)

**Merged pull requests:**

- Revert "Cache key strings." [\#290](https://github.com/voxpupuli/hiera-eyaml/pull/290) ([alexjfisher](https://github.com/alexjfisher))

## [v3.1.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.1.0) (2019-11-11)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v3.0.0...v3.1.0)

**Implemented enhancements:**

- Should be able to `edit` a new file [\#84](https://github.com/voxpupuli/hiera-eyaml/issues/84)
- Cache key strings. [\#191](https://github.com/voxpupuli/hiera-eyaml/pull/191) ([mkulke](https://github.com/mkulke))

**Closed issues:**

- Decryption errors should return error code. [\#282](https://github.com/voxpupuli/hiera-eyaml/issues/282)
- Release a new version [\#271](https://github.com/voxpupuli/hiera-eyaml/issues/271)

**Merged pull requests:**

- \(docs\) Update README with reference to hiera-eyaml-vault [\#287](https://github.com/voxpupuli/hiera-eyaml/pull/287) ([crayfishx](https://github.com/crayfishx))
- fix: don't handle cli exceptions early [\#283](https://github.com/voxpupuli/hiera-eyaml/pull/283) ([stuart-warren](https://github.com/stuart-warren))
- Adding doc for Google KMS plugin [\#279](https://github.com/voxpupuli/hiera-eyaml/pull/279) ([craigwatson](https://github.com/craigwatson))
- catch failed decryption and print a helpful message [\#144](https://github.com/voxpupuli/hiera-eyaml/pull/144) ([GeoffWilliams](https://github.com/GeoffWilliams))

## [v3.0.0](https://github.com/voxpupuli/hiera-eyaml/tree/v3.0.0) (2019-01-17)

[Full Changelog](https://github.com/voxpupuli/hiera-eyaml/compare/v2.1.0...v3.0.0)

This is the first release after this project was migrated to Vox Pupuli.

**Breaking changes:**

- Upgrading trollop to optimist to remove deprecation warnings [\#268](https://github.com/voxpupuli/hiera-eyaml/pull/268) ([chadlyon](https://github.com/chadlyon))

**Implemented enhancements:**

- Don't use SHA1 for the digest [\#257](https://github.com/voxpupuli/hiera-eyaml/issues/257)
- Update to make use of Backend.datasourcefiles\(\) [\#92](https://github.com/voxpupuli/hiera-eyaml/issues/92)
- allow setting an individual keysize [\#227](https://github.com/voxpupuli/hiera-eyaml/pull/227) ([tuxmea](https://github.com/tuxmea))

**Fixed bugs:**

- on OSX, eyaml isn't expanding `~` into /Users/$USER [\#170](https://github.com/voxpupuli/hiera-eyaml/issues/170)
- Performance bug: unnecessary double-decryption of blocks [\#182](https://github.com/voxpupuli/hiera-eyaml/pull/182) ([peculater](https://github.com/peculater))

**Closed issues:**

- PuppetDB gets base64 encoded string on exported ressources [\#273](https://github.com/voxpupuli/hiera-eyaml/issues/273)
- DEPRECATION - trollop gem is deprecated, need to switch to optimist [\#267](https://github.com/voxpupuli/hiera-eyaml/issues/267)
- Puppet can't find key on server [\#266](https://github.com/voxpupuli/hiera-eyaml/issues/266)
- Re-encryption is broken [\#258](https://github.com/voxpupuli/hiera-eyaml/issues/258)
- AWS KMS/IAM integration? [\#234](https://github.com/voxpupuli/hiera-eyaml/issues/234)
- Feature Request: Ability to use edit without the private key [\#231](https://github.com/voxpupuli/hiera-eyaml/issues/231)
- Not decrypting/working with puppetserver 2.7.2 \(Function lookup\(\) did not find a value for the name\) [\#228](https://github.com/voxpupuli/hiera-eyaml/issues/228)
- Allow stronger than 2048 bit keys [\#226](https://github.com/voxpupuli/hiera-eyaml/issues/226)
- failed: DataBinding 'hiera': No such file or directory - /var/lib/puppet/keys/private\_key.pkcs7.pem [\#225](https://github.com/voxpupuli/hiera-eyaml/issues/225)
- Migrate to Vox Pupuli [\#224](https://github.com/voxpupuli/hiera-eyaml/issues/224)
- Allow to `decrypt` while keeping the "DEC::..." [\#217](https://github.com/voxpupuli/hiera-eyaml/issues/217)
- secret in the logs [\#216](https://github.com/voxpupuli/hiera-eyaml/issues/216)
- eyaml produces base64 string for complex data [\#209](https://github.com/voxpupuli/hiera-eyaml/issues/209)
- Hiera-eyaml cannot decrypt with key, plain gpg works [\#206](https://github.com/voxpupuli/hiera-eyaml/issues/206)
- Unable to decrypt on remote nodes [\#202](https://github.com/voxpupuli/hiera-eyaml/issues/202)
- Backend not found in tests [\#200](https://github.com/voxpupuli/hiera-eyaml/issues/200)
- ArgumentError [\#193](https://github.com/voxpupuli/hiera-eyaml/issues/193)
- High CPU consumption  [\#192](https://github.com/voxpupuli/hiera-eyaml/issues/192)
- hiera call from manifeast not able to locate key [\#174](https://github.com/voxpupuli/hiera-eyaml/issues/174)
- PE 3.8  - sporadically failing to load eyaml backend. [\#173](https://github.com/voxpupuli/hiera-eyaml/issues/173)
- eyaml and templates [\#171](https://github.com/voxpupuli/hiera-eyaml/issues/171)
- cucumber failures with puppet 3.7.5 [\#154](https://github.com/voxpupuli/hiera-eyaml/issues/154)
- issue with jruby under PE 3.7 [\#150](https://github.com/voxpupuli/hiera-eyaml/issues/150)
- hiera eyaml does not work on PE 3.7.2 [\#126](https://github.com/voxpupuli/hiera-eyaml/issues/126)
- invalid byte sequence in UTF-8 on encrypted binary [\#124](https://github.com/voxpupuli/hiera-eyaml/issues/124)
- having an issue when loding hiera-eyaml [\#117](https://github.com/voxpupuli/hiera-eyaml/issues/117)
- Puppet hiera\(\): Cannot load backend eyaml: no such file to load [\#115](https://github.com/voxpupuli/hiera-eyaml/issues/115)
- Public/private keys undefined for Vagrant [\#101](https://github.com/voxpupuli/hiera-eyaml/issues/101)
- bug in hiera 1.3.2-1 vs rubygem-hiera 1.3.2-1 [\#85](https://github.com/voxpupuli/hiera-eyaml/issues/85)
- Errors of yaml and no eyaml files exist. Fine if just eyaml files exist. [\#82](https://github.com/voxpupuli/hiera-eyaml/issues/82)

**Merged pull requests:**

- Use UTF-8 as the encoding for plain text data [\#274](https://github.com/voxpupuli/hiera-eyaml/pull/274) ([jarretlavallee](https://github.com/jarretlavallee))
- Fix regem.sh shebang, it does not need bash [\#265](https://github.com/voxpupuli/hiera-eyaml/pull/265) ([AMDmi3](https://github.com/AMDmi3))
- Allow selection of digest, default to SHA256 [\#261](https://github.com/voxpupuli/hiera-eyaml/pull/261) ([juniorsysadmin](https://github.com/juniorsysadmin))
- expand README on whole-file encryption usage [\#260](https://github.com/voxpupuli/hiera-eyaml/pull/260) ([jflorian](https://github.com/jflorian))
- Add encrypt-only flag for 'edit' command. [\#256](https://github.com/voxpupuli/hiera-eyaml/pull/256) ([benjunmun](https://github.com/benjunmun))
- Test only with current Puppet and Ruby combination [\#254](https://github.com/voxpupuli/hiera-eyaml/pull/254) ([vinzent](https://github.com/vinzent))
- Update \#{self.prefix} to match yamllint rules [\#248](https://github.com/voxpupuli/hiera-eyaml/pull/248) ([jordanconway](https://github.com/jordanconway))
- Fix badge, link to AWS KMS/IAM integration [\#245](https://github.com/voxpupuli/hiera-eyaml/pull/245) ([rnelson0](https://github.com/rnelson0))
- Remove tildes that don't expand from configuration examples [\#242](https://github.com/voxpupuli/hiera-eyaml/pull/242) ([rnelson0](https://github.com/rnelson0))
- Disable deprecation warnings [\#241](https://github.com/voxpupuli/hiera-eyaml/pull/241) ([rnelson0](https://github.com/rnelson0))
- Add a cache for decrypted values [\#240](https://github.com/voxpupuli/hiera-eyaml/pull/240) ([stlava](https://github.com/stlava))
- Suppressing logging of configuration files on init [\#237](https://github.com/voxpupuli/hiera-eyaml/pull/237) ([sigv](https://github.com/sigv))
- Update the keys' example directory [\#236](https://github.com/voxpupuli/hiera-eyaml/pull/236) ([sigv](https://github.com/sigv))
- Modify edit command to not recrypt unchanged values [\#233](https://github.com/voxpupuli/hiera-eyaml/pull/233) ([ccojocar](https://github.com/ccojocar))
- Modify recrypt command to allow recrypting file with different encryp… [\#232](https://github.com/voxpupuli/hiera-eyaml/pull/232) ([ccojocar](https://github.com/ccojocar))
- \(docs\) Update README with instructions for using Hiera 5 [\#229](https://github.com/voxpupuli/hiera-eyaml/pull/229) ([nfagerlund](https://github.com/nfagerlund))
- Attempt to resolve Travis CI issues [\#220](https://github.com/voxpupuli/hiera-eyaml/pull/220) ([rnelson0](https://github.com/rnelson0))
- Make it clear that the ID and parens must be deleted, not just the ID [\#188](https://github.com/voxpupuli/hiera-eyaml/pull/188) ([sdotz](https://github.com/sdotz))
- Refactor highline import [\#187](https://github.com/voxpupuli/hiera-eyaml/pull/187) ([petems](https://github.com/petems))
- Adding hiera-eyaml-kms plugin to readme file [\#184](https://github.com/voxpupuli/hiera-eyaml/pull/184) ([adenot](https://github.com/adenot))
- Make output of `eyaml decrypt` valid yaml with multiline values. [\#183](https://github.com/voxpupuli/hiera-eyaml/pull/183) ([peculater](https://github.com/peculater))
- Add testing support for puppet 4 [\#181](https://github.com/voxpupuli/hiera-eyaml/pull/181) ([peculater](https://github.com/peculater))

## v2.1.0 (2016-03-02)

 - (#187) - Change the way third party highline library is imported to avoid memory leak when running under puppet server (@petems)
 - (#181) - Improve test suite to run against a variety of puppet versions (@peculater)

## v2.0.8 (2015-04-15)

 - (#149) - Fix to tempfile permissions and invalid editor scenario (@elyscape)

## v2.0.7 (2015-03-04)

 - (#142) - Fixed highline dependency to exclude newer versions that are not compatible with ruby 1.8.7 (@elyscape)
 - (#136) - \t and \r characters are now supported in encrypted blocks (@elyscape)
 - (#138) - Added missing tags and new tagging tool (@elyscape)

## v2.0.6 (2014-12-13)

 - (#131) - Fix another EDITOR bug (#130) that could erase command line flags to the specified editor (@elyscape)

## v2.0.5 (2014-12-11)

 - (#128) - Fix a bug (#127) that caused `eyaml edit` to break when `$EDITOR` was a command on PATH rather than a path to a command (@elyscape)

## v2.0.4 (2014-11-24)

 - Add change log
 - (#118) - Some initial support for spaces in filenames (primarily targeted at windows platforms) (@elyscape)
 - (#114) - Add new config file resolution so that a system wide /etc/eyaml/config.yaml is processed first (@gtmtech)
 - (#112) - Improve debugging options and colorise output (@gtmtech)
 - (#102) - Extension of temp files should be yaml to help editors provide syntax highlighting (@ColinHebert)
 - (#90), #121, #122 - Add preamble in edit mode to make it easier to remember how to edit (@sihil)
 - (#96), #111, #116 - Various updates to docs


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
