# AngularJSApps
Sample Apps and getting started

## To Get Started , need to to install angular js CLI on your machine.

using command

npm install -g @angular/cli

https://angular.io/cli

Output of this installation would be like as followings

# Output

npm install -g @angular/cli
/usr/local/bin/ng -> /usr/local/lib/node_modules/@angular/cli/bin/ng

> @angular/cli@8.3.13 postinstall /usr/local/lib/node_modules/@angular/cli
> node ./bin/postinstall/script.js

/usr/local/lib
└─┬ @angular/cli@8.3.13 
  ├─┬ @angular-devkit/architect@0.803.13 
  │ └─┬ rxjs@6.4.0 
  │   └── tslib@1.10.0 
  ├─┬ @angular-devkit/core@8.3.13 
  │ ├─┬ ajv@6.10.2 
  │ │ ├── fast-deep-equal@2.0.1 
  │ │ ├── json-schema-traverse@0.4.1 
  │ │ └─┬ uri-js@4.2.2 
  │ │   └── punycode@2.1.1 
  │ ├── fast-json-stable-stringify@2.0.0 
  │ ├─┬ magic-string@0.25.3 
  │ │ └── sourcemap-codec@1.4.6 
  │ └── source-map@0.7.3 
  ├── @angular-devkit/schematics@8.3.13 
  ├── @schematics/angular@8.3.13 
  ├─┬ @schematics/update@0.803.13 
  │ └─┬ semver-intersect@1.4.0 
  │   └── semver@5.7.1 
  ├── @yarnpkg/lockfile@1.1.0 
  ├── ansi-colors@4.1.1 
  ├─┬ debug@4.1.1 
  │ └── ms@2.1.2 
  ├── ini@1.3.5 
  ├─┬ inquirer@6.5.1 
  │ ├─┬ ansi-escapes@4.2.1 
  │ │ └── type-fest@0.5.2 
  │ ├─┬ chalk@2.4.2 
  │ │ ├─┬ ansi-styles@3.2.1 
  │ │ │ └─┬ color-convert@1.9.3 
  │ │ │   └── color-name@1.1.3 
  │ │ ├── escape-string-regexp@1.0.5 
  │ │ └─┬ supports-color@5.5.0 
  │ │   └── has-flag@3.0.0 
  │ ├─┬ cli-cursor@3.1.0 
  │ │ └─┬ restore-cursor@3.1.0 
  │ │   ├─┬ onetime@5.1.0 
  │ │   │ └── mimic-fn@2.1.0 
  │ │   └── signal-exit@3.0.2 
  │ ├── cli-width@2.2.0 
  │ ├─┬ external-editor@3.1.0 
  │ │ ├── chardet@0.7.0 
  │ │ ├─┬ iconv-lite@0.4.24 
  │ │ │ └── safer-buffer@2.1.2 
  │ │ └── tmp@0.0.33 
  │ ├── figures@3.1.0 
  │ ├── lodash@4.17.15 
  │ ├── mute-stream@0.0.8 
  │ ├─┬ run-async@2.3.0 
  │ │ └── is-promise@2.1.0 
  │ ├─┬ string-width@4.1.0 
  │ │ ├── emoji-regex@8.0.0 
  │ │ └── is-fullwidth-code-point@3.0.0 
  │ ├─┬ strip-ansi@5.2.0 
  │ │ └── ansi-regex@4.1.0 
  │ └── through@2.3.8 
  ├─┬ npm-package-arg@6.1.0 
  │ ├── hosted-git-info@2.8.5 
  │ ├─┬ osenv@0.1.5 
  │ │ ├── os-homedir@1.0.2 
  │ │ └── os-tmpdir@1.0.2 
  │ ├── semver@5.7.1 
  │ └─┬ validate-npm-package-name@3.0.0 
  │   └── builtins@1.0.3 
  ├─┬ npm-pick-manifest@3.0.2 
  │ ├── figgy-pudding@3.5.1 
  │ └── semver@5.7.1 
  ├─┬ open@6.4.0 
  │ └── is-wsl@1.1.0 
  ├─┬ pacote@9.5.5 
  │ ├── bluebird@3.7.1 
  │ ├─┬ cacache@12.0.3 
  │ │ ├── chownr@1.1.3 
  │ │ ├── graceful-fs@4.2.2 
  │ │ ├─┬ move-concurrently@1.0.1 
  │ │ │ ├── aproba@1.2.0 
  │ │ │ ├─┬ copy-concurrently@1.0.5 
  │ │ │ │ ├── iferr@0.1.5 
  │ │ │ │ └── rimraf@2.7.1 
  │ │ │ ├── fs-write-stream-atomic@1.0.10 
  │ │ │ ├── rimraf@2.7.1 
  │ │ │ └── run-queue@1.0.3 
  │ │ ├── rimraf@2.7.1 
  │ │ └── y18n@4.0.0 
  │ ├─┬ get-stream@4.1.0 
  │ │ └── pump@3.0.0 
  │ ├─┬ glob@7.1.5 
  │ │ ├── fs.realpath@1.0.0 
  │ │ ├─┬ inflight@1.0.6 
  │ │ │ └── wrappy@1.0.2 
  │ │ ├── inherits@2.0.4 
  │ │ ├── once@1.4.0 
  │ │ └── path-is-absolute@1.0.1 
  │ ├── infer-owner@1.0.4 
  │ ├─┬ lru-cache@5.1.1 
  │ │ └── yallist@3.1.1 
  │ ├─┬ make-fetch-happen@5.0.1 
  │ │ ├─┬ agentkeepalive@3.5.2 
  │ │ │ └── humanize-ms@1.2.1 
  │ │ ├── http-cache-semantics@3.8.1 
  │ │ ├─┬ http-proxy-agent@2.1.0 
  │ │ │ ├─┬ agent-base@4.3.0 
  │ │ │ │ └─┬ es6-promisify@5.0.0 
  │ │ │ │   └── es6-promise@4.2.8 
  │ │ │ └─┬ debug@3.1.0 
  │ │ │   └── ms@2.0.0 
  │ │ ├─┬ https-proxy-agent@2.2.3 
  │ │ │ └── debug@3.2.6 
  │ │ ├─┬ node-fetch-npm@2.0.2 
  │ │ │ └── encoding@0.1.12 
  │ │ └─┬ socks-proxy-agent@4.0.2 
  │ │   ├── agent-base@4.2.1 
  │ │   └─┬ socks@2.3.2 
  │ │     ├── ip@1.1.5 
  │ │     └── smart-buffer@4.0.2 
  │ ├─┬ minimatch@3.0.4 
  │ │ └─┬ brace-expansion@1.1.11 
  │ │   ├── balanced-match@1.0.0 
  │ │   └── concat-map@0.0.1 
  │ ├── minipass@2.9.0 
  │ ├─┬ mississippi@3.0.0 
  │ │ ├─┬ concat-stream@1.6.2 
  │ │ │ ├── buffer-from@1.1.1 
  │ │ │ ├─┬ readable-stream@2.3.6 
  │ │ │ │ ├── core-util-is@1.0.2 
  │ │ │ │ ├── isarray@1.0.0 
  │ │ │ │ ├── process-nextick-args@2.0.1 
  │ │ │ │ ├── safe-buffer@5.1.2 
  │ │ │ │ ├─┬ string_decoder@1.1.1 
  │ │ │ │ │ └── safe-buffer@5.1.2 
  │ │ │ │ └── util-deprecate@1.0.2 
  │ │ │ └── typedarray@0.0.6 
  │ │ ├─┬ duplexify@3.7.1 
  │ │ │ └── stream-shift@1.0.0 
  │ │ ├── end-of-stream@1.4.4 
  │ │ ├── flush-write-stream@1.1.1 
  │ │ ├── from2@2.3.0 
  │ │ ├─┬ parallel-transform@1.2.0 
  │ │ │ └── cyclist@1.0.1 
  │ │ ├─┬ pumpify@1.5.1 
  │ │ │ └── pump@2.0.1 
  │ │ ├── stream-each@1.2.3 
  │ │ └─┬ through2@2.0.5 
  │ │   └── xtend@4.0.2 
  │ ├─┬ mkdirp@0.5.1 
  │ │ └── minimist@0.0.8 
  │ ├─┬ normalize-package-data@2.5.0 
  │ │ ├─┬ resolve@1.12.0 
  │ │ │ └── path-parse@1.0.6 
  │ │ ├── semver@5.7.1 
  │ │ └─┬ validate-npm-package-license@3.0.4 
  │ │   ├─┬ spdx-correct@3.1.0 
  │ │   │ └── spdx-license-ids@3.0.5 
  │ │   └─┬ spdx-expression-parse@3.0.0 
  │ │     └── spdx-exceptions@2.2.0 
  │ ├─┬ npm-packlist@1.4.6 
  │ │ ├── ignore-walk@3.0.3 
  │ │ └── npm-bundled@1.0.6 
  │ ├── npm-pick-manifest@2.2.3 
  │ ├─┬ npm-registry-fetch@4.0.2 
  │ │ └─┬ JSONStream@1.3.5 
  │ │   └── jsonparse@1.3.1 
  │ ├── promise-inflight@1.0.1 
  │ ├─┬ promise-retry@1.1.1 
  │ │ ├── err-code@1.1.2 
  │ │ └── retry@0.10.1 
  │ ├─┬ protoduck@5.0.1 
  │ │ └── genfun@5.0.0 
  │ ├── rimraf@2.7.1 
  │ ├── safe-buffer@5.2.0 
  │ ├── semver@5.7.1 
  │ ├── ssri@6.0.1 
  │ ├─┬ tar@4.4.13 
  │ │ ├── fs-minipass@1.2.7 
  │ │ └── minizlib@1.3.3 
  │ ├─┬ unique-filename@1.1.1 
  │ │ └─┬ unique-slug@2.0.2 
  │ │   └── imurmurhash@0.1.4 
  │ └─┬ which@1.3.1 
  │   └── isexe@2.0.0 
  ├─┬ read-package-tree@5.3.1 
  │ ├─┬ read-package-json@2.1.0 
  │ │ ├── json-parse-better-errors@1.0.2 
  │ │ └── slash@1.0.0 
  │ ├─┬ readdir-scoped-modules@1.1.0 
  │ │ ├── debuglog@1.0.1 
  │ │ └─┬ dezalgo@1.0.3 
  │ │   └── asap@2.0.6 
  │ └─┬ util-promisify@2.1.0 
  │   └─┬ object.getownpropertydescriptors@2.0.3 
  │     ├─┬ define-properties@1.1.3 
  │     │ └── object-keys@1.1.1 
  │     └─┬ es-abstract@1.16.0 
  │       ├─┬ es-to-primitive@1.2.0 
  │       │ ├── is-date-object@1.0.1 
  │       │ └── is-symbol@1.0.2 
  │       ├── function-bind@1.1.1 
  │       ├── has@1.0.3 
  │       ├── has-symbols@1.0.0 
  │       ├── is-callable@1.1.4 
  │       ├── is-regex@1.0.4 
  │       ├── object-inspect@1.6.0 
  │       ├── string.prototype.trimleft@2.1.0 
  │       └── string.prototype.trimright@2.1.0 
  ├── rimraf@3.0.0 
  ├── semver@6.3.0 
  ├── symbol-observable@1.2.0 
  ├─┬ universal-analytics@0.4.20 
  │ ├── debug@3.2.6 
  │ └─┬ request@2.88.0 
  │   ├── aws-sign2@0.7.0 
  │   ├── aws4@1.8.0 
  │   ├── caseless@0.12.0 
  │   ├─┬ combined-stream@1.0.8 
  │   │ └── delayed-stream@1.0.0 
  │   ├── extend@3.0.2 
  │   ├── forever-agent@0.6.1 
  │   ├─┬ form-data@2.3.3 
  │   │ └── asynckit@0.4.0 
  │   ├─┬ har-validator@5.1.3 
  │   │ └── har-schema@2.0.0 
  │   ├─┬ http-signature@1.2.0 
  │   │ ├── assert-plus@1.0.0 
  │   │ ├─┬ jsprim@1.4.1 
  │   │ │ ├── extsprintf@1.3.0 
  │   │ │ ├── json-schema@0.2.3 
  │   │ │ └── verror@1.10.0 
  │   │ └─┬ sshpk@1.16.1 
  │   │   ├── asn1@0.2.4 
  │   │   ├── bcrypt-pbkdf@1.0.2 
  │   │   ├── dashdash@1.14.1 
  │   │   ├── ecc-jsbn@0.1.2 
  │   │   ├── getpass@0.1.7 
  │   │   ├── jsbn@0.1.1 
  │   │   └── tweetnacl@0.14.5 
  │   ├── is-typedarray@1.0.0 
  │   ├── isstream@0.1.2 
  │   ├── json-stringify-safe@5.0.1 
  │   ├─┬ mime-types@2.1.24 
  │   │ └── mime-db@1.40.0 
  │   ├── oauth-sign@0.9.0 
  │   ├── performance-now@2.1.0 
  │   ├── qs@6.5.2 
  │   ├─┬ tough-cookie@2.4.3 
  │   │ ├── psl@1.4.0 
  │   │ └── punycode@1.4.1 
  │   └── tunnel-agent@0.6.0 
  └── uuid@3.3.3 
