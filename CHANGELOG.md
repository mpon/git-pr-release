# git-pr-release

## v1.6.0 (2021-05-15)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.5.0...v1.6.0)

* (#63) Sort merged_pull_request_numbers numerically by default (@yutailang0119)

## v1.5.0 (2021-04-02)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.4.0...v1.5.0)

* (#60, #61) Get issue number from GitHub API for squashed PR (@yuuan)
* (#58) Make stable test (@kachick)
* (#55) Suppress warning for ERB (@ohbarye)
* (#50) support `GIT_PR_RELEASE_MENTION` environment variable (@dabutvin)
* (#49) Transfer repository to x-motemen organization (@onk)

## v1.4.0 (2020-02-22)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.3.0...v1.4.0)

* (#48) List PR API needs head user or head organization and branch name (@sasasin)

## v1.3.0 (2020-02-19)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.2.0...v1.3.0)

* (#47) Fix Errno::ENOENT when finding the specified template (@onk)
* (#45) Fix "warning: instance variable @xxx not initialized" (@onk)

## v1.2.0 (2020-02-07)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.1.0...v1.2.0)

* (#44) Use API option when detecting existing release PR (@onk)
* (#41, #42) Refactor (@onk)
  - Some local variables are removed. This will break if you have customized the template ERB.

## v1.1.0 (2020-01-02)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.0.1...v1.1.0)

* (#38) Fetch changed files as many as possible (@shibayu36)

## v1.0.1 (2019-12-17)

[full changelog](https://github.com/x-motemen/git-pr-release/compare/v1.0.0...v1.0.1)

* (#37) Fix NameError (@onk)

## v1.0.0 (2019-12-14)

* (#35) Do not define classes and methods at the top level (@onk)
* (#30) Extract logic from bin/git-pr-release (@banyan)

...

## v0.0.1 (2014-01-21)

Initial Release
