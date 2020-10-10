# mkdir my-first-nuxtjs-prj
# cd my-first-nuxtjs-prj
# touch package.json

# npm install nuxt :
- 93.526s
- node_modules folder = 27.425 items, totalling 114,3 MB

# yarn add nuxt :
- 18.26s
- node_modules folder = 23.878 items, totalling 97,8 MB

# mkdir pages
# touch pages/index.vue

# npm run dev
✔ Client: Compiled successfully in 2.50s
✔ Server: Compiled successfully in 2.60s
ℹ Memory usage: 145 MB (RSS: 215 MB)

# yarn dev
✔ Client: Compiled successfully in 2.52s
✔ Server: Compiled successfully in 2.62s
ℹ Memory usage: 144 MB (RSS: 215 MB)

binhbdn@sun:~/Documents/github/learn-nuxt.js/01-install/my-first-nuxtjs-prj$ npm install nuxt
npm WARN deprecated @nuxt/static@1.0.0: this feature has been moved to the core. you can directly use nuxt generate
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.
npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.

> core-js@2.6.11 postinstall /home/binhbdn/Documents/github/learn-nuxt.js/01-install/my-first-nuxtjs-prj/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)


> ejs@2.7.4 postinstall /home/binhbdn/Documents/github/learn-nuxt.js/01-install/my-first-nuxtjs-prj/node_modules/ejs
> node ./postinstall.js

Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)


> nuxt@2.14.6 postinstall /home/binhbdn/Documents/github/learn-nuxt.js/01-install/my-first-nuxtjs-prj/node_modules/nuxt
> opencollective || exit 0

                                                                         
                                                 :-:                     
                                               .==-+:                    
                                              .==. :+- .-=-              
                                             .==.   :==++-+=.            
                                            :==.     -**: :+=.           
                                           :+-      :*+++. .++.          
                                          :+-      -*= .++: .=+.         
                                         -+:      =*-   .+*: .=+:        
                                        -+:     .=*-     .=*-  =+:       
                                      .==:     .+*:        -*-  -+-      
                                     .=+:.....:+*-.........:=*=..=*-     
                                     .-=------=++============++====:     
                                                     
                                     Thanks for installing nuxtjs 🙏
                             Please consider donating to our open collective
                                    to help us maintain this package.
                                                     
                                       Number of contributors: 229
                                          Number of backers: 377
                                          Annual budget: $67,637
                                         Current balance: $38,286
                                                     
                       👉  Donate: https://opencollective.com/nuxtjs/donate
                                                     
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN notsup Unsupported engine for watchpack-chokidar2@2.0.0: wanted: {"node":"<8.10.0"} (current: {"node":"12.18.4","npm":"6.14.6"})
npm WARN notsup Not compatible with your version of node/npm: watchpack-chokidar2@2.0.0
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@~2.1.2 (node_modules/chokidar/node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.1.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules/watchpack-chokidar2/node_modules/chokidar/node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})

+ nuxt@2.14.6
added 1219 packages from 593 contributors and audited 1221 packages in 93.526s

55 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

binhbdn@sun:~/Documents/github/learn-nuxt.js/01-install/my-first-nuxtjs-prj$ yarn add nuxt
yarn add v1.22.5
info No lockfile found.
warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
[1/4] Resolving packages...
warning nuxt > @nuxt/static@1.0.0: this feature has been moved to the core. you can directly use nuxt generate
warning nuxt > @nuxt/cli > @nuxt/static@1.0.0: this feature has been moved to the core. you can directly use nuxt generate
warning nuxt > @nuxt/webpack > @nuxt/babel-preset-app > core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
warning nuxt > @nuxt/webpack > webpack > watchpack > watchpack-chokidar2 > chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.
warning nuxt > @nuxt/webpack > webpack > watchpack > watchpack-chokidar2 > chokidar > fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
warning nuxt > @nuxt/webpack > webpack > micromatch > snapdragon > source-map-resolve > resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
warning nuxt > @nuxt/webpack > webpack > micromatch > snapdragon > source-map-resolve > urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
[2/4] Fetching packages...
info fsevents@2.1.3: The platform "linux" is incompatible with this module.
info "fsevents@2.1.3" is an optional dependency and failed compatibility check. Excluding it from installation.
info fsevents@1.2.13: The platform "linux" is incompatible with this module.
info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
[3/4] Linking dependencies...
[4/4] Building fresh packages...
success Saved lockfile.
success Saved 659 new dependencies.
info Direct dependencies
└─ nuxt@2.14.6
info All dependencies
├─ @babel/compat-data@7.11.0
├─ @babel/generator@7.11.6
├─ @babel/helper-builder-binary-assignment-operator-visitor@7.10.4
├─ @babel/helper-define-map@7.10.5
├─ @babel/helper-explode-assignable-expression@7.11.4
├─ @babel/helper-hoist-variables@7.10.4
├─ @babel/helper-member-expression-to-functions@7.11.0
├─ @babel/helper-wrap-function@7.10.4
├─ @babel/helpers@7.10.4
├─ @babel/highlight@7.10.4
├─ @babel/parser@7.11.5
├─ @babel/plugin-proposal-async-generator-functions@7.10.5
├─ @babel/plugin-proposal-decorators@7.10.5
├─ @babel/plugin-proposal-dynamic-import@7.10.4
├─ @babel/plugin-proposal-export-namespace-from@7.10.4
├─ @babel/plugin-proposal-json-strings@7.10.4
├─ @babel/plugin-proposal-logical-assignment-operators@7.11.0
├─ @babel/plugin-proposal-nullish-coalescing-operator@7.10.4
├─ @babel/plugin-proposal-numeric-separator@7.10.4
├─ @babel/plugin-proposal-object-rest-spread@7.11.0
├─ @babel/plugin-proposal-optional-catch-binding@7.10.4
├─ @babel/plugin-proposal-optional-chaining@7.11.0
├─ @babel/plugin-proposal-private-methods@7.10.4
├─ @babel/plugin-proposal-unicode-property-regex@7.10.4
├─ @babel/plugin-syntax-class-properties@7.10.4
├─ @babel/plugin-syntax-decorators@7.10.4
├─ @babel/plugin-syntax-top-level-await@7.10.4
├─ @babel/plugin-transform-arrow-functions@7.10.4
├─ @babel/plugin-transform-async-to-generator@7.10.4
├─ @babel/plugin-transform-block-scoped-functions@7.10.4
├─ @babel/plugin-transform-block-scoping@7.11.1
├─ @babel/plugin-transform-classes@7.10.4
├─ @babel/plugin-transform-computed-properties@7.10.4
├─ @babel/plugin-transform-destructuring@7.10.4
├─ @babel/plugin-transform-dotall-regex@7.10.4
├─ @babel/plugin-transform-duplicate-keys@7.10.4
├─ @babel/plugin-transform-exponentiation-operator@7.10.4
├─ @babel/plugin-transform-for-of@7.10.4
├─ @babel/plugin-transform-function-name@7.10.4
├─ @babel/plugin-transform-literals@7.10.4
├─ @babel/plugin-transform-member-expression-literals@7.10.4
├─ @babel/plugin-transform-modules-amd@7.10.5
├─ @babel/plugin-transform-modules-commonjs@7.10.4
├─ @babel/plugin-transform-modules-systemjs@7.10.5
├─ @babel/plugin-transform-modules-umd@7.10.4
├─ @babel/plugin-transform-named-capturing-groups-regex@7.10.4
├─ @babel/plugin-transform-new-target@7.10.4
├─ @babel/plugin-transform-object-super@7.10.4
├─ @babel/plugin-transform-property-literals@7.10.4
├─ @babel/plugin-transform-regenerator@7.10.4
├─ @babel/plugin-transform-reserved-words@7.10.4
├─ @babel/plugin-transform-runtime@7.11.5
├─ @babel/plugin-transform-shorthand-properties@7.10.4
├─ @babel/plugin-transform-spread@7.11.0
├─ @babel/plugin-transform-sticky-regex@7.10.4
├─ @babel/plugin-transform-template-literals@7.10.5
├─ @babel/plugin-transform-typeof-symbol@7.10.4
├─ @babel/plugin-transform-unicode-escapes@7.10.4
├─ @babel/plugin-transform-unicode-regex@7.10.4
├─ @babel/preset-env@7.11.5
├─ @babel/preset-modules@0.1.4
├─ @babel/runtime@7.11.2
├─ @nodelib/fs.scandir@2.1.3
├─ @nodelib/fs.stat@2.0.3
├─ @nodelib/fs.walk@1.2.4
├─ @nuxt/babel-preset-app@2.14.6
├─ @nuxt/builder@2.14.6
├─ @nuxt/cli@2.14.6
├─ @nuxt/components@1.1.0
├─ @nuxt/core@2.14.6
├─ @nuxt/friendly-errors-webpack-plugin@2.5.0
├─ @nuxt/generator@2.14.6
├─ @nuxt/loading-screen@2.0.2
├─ @nuxt/opencollective@0.3.0
├─ @nuxt/server@2.14.6
├─ @nuxt/telemetry@1.2.3
├─ @nuxt/vue-app@2.14.6
├─ @nuxtjs/youch@4.2.3
├─ @types/anymatch@1.3.1
├─ @types/html-minifier-terser@5.1.1
├─ @types/json-schema@7.0.6
├─ @types/q@1.5.4
├─ @types/source-list-map@0.1.2
├─ @types/tapable@1.0.6
├─ @types/uglify-js@3.11.0
├─ @types/webpack-sources@2.0.0
├─ @types/webpack@4.41.22
├─ @vue/babel-preset-jsx@1.1.2
├─ @vue/babel-sugar-functional-vue@1.1.2
├─ @vue/babel-sugar-inject-h@1.1.2
├─ @vue/babel-sugar-v-model@1.1.2
├─ @vue/babel-sugar-v-on@1.1.2
├─ @vue/component-compiler-utils@3.2.0
├─ @webassemblyjs/floating-point-hex-parser@1.9.0
├─ @webassemblyjs/helper-code-frame@1.9.0
├─ @webassemblyjs/helper-fsm@1.9.0
├─ @webassemblyjs/helper-wasm-section@1.9.0
├─ @webassemblyjs/wasm-edit@1.9.0
├─ @webassemblyjs/wasm-opt@1.9.0
├─ @xtuc/ieee754@1.2.0
├─ accepts@1.3.7
├─ acorn-walk@7.2.0
├─ acorn@6.4.2
├─ aggregate-error@3.1.0
├─ ajv-errors@1.0.1
├─ ajv-keywords@3.5.2
├─ ajv@6.12.5
├─ ansi-align@3.0.0
├─ ansi-colors@3.2.4
├─ ansi-html@0.0.7
├─ ansi-styles@4.3.0
├─ anymatch@3.1.1
├─ arg@4.1.3
├─ argparse@1.0.10
├─ arr-flatten@1.1.0
├─ array-filter@1.0.0
├─ array-flatten@1.1.1
├─ array-union@2.1.0
├─ asn1.js@5.4.1
├─ assert@1.5.0
├─ assign-symbols@1.0.0
├─ async-each@1.0.3
├─ async-limiter@1.0.1
├─ atob@2.1.2
├─ autoprefixer@9.8.6
├─ available-typed-arrays@1.0.2
├─ babel-loader@8.1.0
├─ base@0.11.2
├─ bfj@6.1.2
├─ binary-extensions@2.1.0
├─ bluebird@3.7.2
├─ body-parser@1.19.0
├─ boxen@4.2.0
├─ brace-expansion@1.1.11
├─ braces@2.3.2
├─ browserify-aes@1.2.0
├─ browserify-cipher@1.0.1
├─ browserify-des@1.0.2
├─ browserify-rsa@4.0.1
├─ browserify-sign@4.2.1
├─ browserify-zlib@0.2.0
├─ browserslist@4.14.5
├─ buffer-json@2.0.0
├─ buffer-xor@1.0.3
├─ buffer@5.6.0
├─ builtin-status-codes@3.0.0
├─ cacache@13.0.1
├─ cache-base@1.0.1
├─ cache-loader@4.1.0
├─ caller-callsite@2.0.0
├─ caller-path@2.0.0
├─ callsites@2.0.0
├─ camel-case@3.0.0
├─ caniuse-lite@1.0.30001146
├─ chardet@0.7.0
├─ check-types@8.0.3
├─ chokidar@3.4.2
├─ chownr@1.1.4
├─ chrome-trace-event@1.0.2
├─ ci-info@2.0.0
├─ cipher-base@1.0.4
├─ class-utils@0.3.6
├─ clean-css@4.2.3
├─ clean-stack@2.2.0
├─ cli-boxes@2.2.1
├─ cli-cursor@3.1.0
├─ cli-width@3.0.0
├─ coa@2.0.2
├─ collection-visit@1.0.0
├─ color-convert@1.9.3
├─ color-name@1.1.4
├─ color-string@1.5.4
├─ color@3.1.3
├─ colorette@1.2.1
├─ commander@2.20.3
├─ compressible@2.0.18
├─ concat-map@0.0.1
├─ concat-stream@1.6.2
├─ consola@2.15.0
├─ console-browserify@1.2.0
├─ consolidate@0.15.1
├─ constants-browserify@1.0.0
├─ content-disposition@0.5.3
├─ convert-source-map@1.7.0
├─ cookie-signature@1.0.6
├─ cookie@0.4.0
├─ copy-concurrently@1.0.5
├─ copy-descriptor@0.1.1
├─ core-js-compat@3.6.5
├─ core-js@2.6.11
├─ core-util-is@1.0.2
├─ create-ecdh@4.0.4
├─ create-hmac@1.1.7
├─ cross-spawn@7.0.3
├─ crypto-browserify@3.12.0
├─ css-blank-pseudo@0.1.4
├─ css-color-names@0.0.4
├─ css-declaration-sorter@4.0.1
├─ css-has-pseudo@0.10.0
├─ css-loader@3.6.0
├─ css-prefers-color-scheme@3.1.1
├─ css-select-base-adapter@0.1.1
├─ css-select@1.2.0
├─ css-tree@1.0.0-alpha.37
├─ css-what@2.1.3
├─ cssdb@4.4.0
├─ cssnano-preset-default@4.0.7
├─ cssnano-util-raw-cache@4.0.1
├─ cssnano-util-same-parent@4.0.1
├─ csso@4.0.3
├─ cuint@0.2.2
├─ cyclist@1.0.1
├─ de-indent@1.0.2
├─ debug@2.6.9
├─ decode-uri-component@0.2.0
├─ deepmerge@4.2.2
├─ des.js@1.0.1
├─ destroy@1.0.4
├─ detect-indent@5.0.0
├─ diffie-hellman@5.0.3
├─ dimport@1.0.0
├─ dir-glob@3.0.1
├─ dom-converter@0.2.0
├─ domain-browser@1.2.0
├─ domhandler@2.4.2
├─ domutils@1.7.0
├─ dot-case@3.0.3
├─ dot-prop@5.3.0
├─ duplexer@0.1.2
├─ duplexify@3.7.1
├─ ee-first@1.1.1
├─ ejs@2.7.4
├─ electron-to-chromium@1.3.578
├─ emoji-regex@8.0.0
├─ enhanced-resolve@4.3.0
├─ entities@2.0.3
├─ errno@0.1.7
├─ error-ex@1.3.2
├─ error-stack-parser@2.0.6
├─ es6-object-assign@1.1.0
├─ escalade@3.1.0
├─ eslint-scope@4.0.3
├─ esprima@4.0.1
├─ esrecurse@4.3.0
├─ estraverse@4.3.0
├─ esutils@2.0.3
├─ events@3.2.0
├─ eventsource-polyfill@0.9.6
├─ execa@3.4.0
├─ exit@0.1.2
├─ expand-brackets@2.1.4
├─ express@4.17.1
├─ external-editor@3.1.0
├─ extglob@2.0.4
├─ extract-css-chunks-webpack-plugin@4.7.5
├─ fast-deep-equal@3.1.3
├─ fast-glob@3.2.4
├─ fast-json-stable-stringify@2.1.0
├─ fastq@1.8.0
├─ file-loader@4.3.0
├─ filesize@3.6.1
├─ fill-range@4.0.0
├─ finalhandler@1.1.2
├─ flat@5.0.2
├─ flatten@1.0.3
├─ flush-write-stream@1.1.1
├─ for-in@1.0.2
├─ forwarded@0.1.2
├─ from2@2.3.0
├─ fs-memo@1.0.1
├─ fs-minipass@2.1.0
├─ fs.realpath@1.0.0
├─ gensync@1.0.0-beta.1
├─ get-port-please@1.0.0
├─ get-stream@5.2.0
├─ get-value@2.0.6
├─ git-config-path@2.0.0
├─ git-up@4.0.2
├─ git-url-parse@11.3.0
├─ glob-parent@5.1.1
├─ gzip-size@5.1.1
├─ hard-source-webpack-plugin@0.13.1
├─ has-ansi@2.0.0
├─ has-value@1.0.0
├─ hash.js@1.1.7
├─ hex-color-regex@1.1.0
├─ hmac-drbg@1.0.1
├─ hoopy@0.1.4
├─ hsl-regex@1.0.0
├─ hsla-regex@1.0.0
├─ html-comment-regex@1.1.2
├─ html-entities@1.3.1
├─ html-minifier-terser@5.1.1
├─ html-minifier@4.0.0
├─ html-webpack-plugin@4.5.0
├─ htmlparser2@3.10.1
├─ https-browserify@1.0.0
├─ human-signals@1.1.1
├─ ignore@5.1.8
├─ import-cwd@2.1.0
├─ import-fresh@2.0.0
├─ import-from@2.1.0
├─ indent-string@4.0.0
├─ infer-owner@1.0.4
├─ inflight@1.0.6
├─ ini@1.3.5
├─ inquirer@7.3.3
├─ ip@1.1.5
├─ ipaddr.js@1.9.1
├─ is-absolute-url@2.1.0
├─ is-accessor-descriptor@1.0.0
├─ is-arguments@1.0.4
├─ is-arrayish@0.2.1
├─ is-binary-path@2.1.0
├─ is-callable@1.2.2
├─ is-color-stop@1.1.0
├─ is-data-descriptor@1.0.0
├─ is-date-object@1.0.2
├─ is-descriptor@1.0.2
├─ is-directory@0.3.1
├─ is-docker@2.1.1
├─ is-extglob@2.1.1
├─ is-generator-function@1.0.7
├─ is-glob@4.0.1
├─ is-nan@1.3.0
├─ is-negative-zero@2.0.0
├─ is-obj@2.0.0
├─ is-plain-object@2.0.4
├─ is-promise@2.2.2
├─ is-resolvable@1.1.0
├─ is-stream@2.0.0
├─ is-svg@3.0.0
├─ is-symbol@1.0.3
├─ is-windows@1.0.2
├─ is-wsl@1.1.0
├─ isarray@1.0.0
├─ isexe@2.0.0
├─ jest-worker@25.5.0
├─ js-tokens@4.0.0
├─ jsesc@2.5.2
├─ json-parse-better-errors@1.0.2
├─ json-schema-traverse@0.4.1
├─ jsonfile@4.0.0
├─ kind-of@3.2.2
├─ last-call-webpack-plugin@3.0.0
├─ launch-editor-middleware@2.2.1
├─ launch-editor@2.2.1
├─ leven@3.1.0
├─ loader-runner@2.4.0
├─ loader-utils@1.4.0
├─ loadjs@4.2.0
├─ locate-path@3.0.0
├─ lodash.kebabcase@4.1.1
├─ lodash.memoize@4.1.2
├─ lodash.templatesettings@4.2.0
├─ loose-envify@1.4.0
├─ lower-case@1.1.4
├─ make-dir@2.1.0
├─ map-age-cleaner@0.1.3
├─ map-visit@1.0.0
├─ mdn-data@2.0.4
├─ media-typer@0.3.0
├─ mem@6.1.1
├─ merge-descriptors@1.0.1
├─ merge-source-map@1.1.0
├─ methods@1.1.2
├─ micromatch@3.1.10
├─ miller-rabin@4.0.1
├─ mime-db@1.44.0
├─ mimic-fn@2.1.0
├─ minimalistic-crypto-utils@1.0.1
├─ minimist@1.2.5
├─ minipass-collect@1.0.2
├─ minipass-flush@1.0.5
├─ minipass-pipeline@1.2.4
├─ minipass@3.1.3
├─ mississippi@3.0.0
├─ mixin-deep@1.3.2
├─ ms@2.0.0
├─ mustache@2.3.2
├─ mute-stream@0.0.8
├─ nanoid@3.1.12
├─ nanomatch@1.2.13
├─ negotiator@0.6.2
├─ neo-async@2.6.2
├─ node-fetch@2.6.1
├─ node-html-parser@1.3.1
├─ node-libs-browser@2.2.1
├─ node-object-hash@1.4.2
├─ node-releases@1.1.61
├─ node-res@5.0.1
├─ normalize-path@3.0.0
├─ normalize-range@0.1.2
├─ normalize-url@3.3.0
├─ npm-run-path@4.0.1
├─ nth-check@1.0.2
├─ num2fraction@1.2.2
├─ nuxt@2.14.6
├─ object-assign@4.1.1
├─ object-copy@0.1.0
├─ object-is@1.1.3
├─ object.assign@4.1.1
├─ object.getownpropertydescriptors@2.1.0
├─ object.values@1.1.1
├─ on-headers@1.0.2
├─ opener@1.5.2
├─ optimize-css-assets-webpack-plugin@5.0.4
├─ os-browserify@0.3.0
├─ os-tmpdir@1.0.2
├─ p-defer@1.0.0
├─ p-finally@2.0.1
├─ p-limit@2.3.0
├─ p-locate@3.0.0
├─ p-map@3.0.0
├─ p-try@2.2.0
├─ pako@1.0.11
├─ parallel-transform@1.2.0
├─ param-case@2.1.1
├─ parse-asn1@5.1.6
├─ parse-git-config@3.0.0
├─ parse-path@4.0.2
├─ parse-url@5.0.2
├─ pascal-case@3.1.1
├─ pascalcase@0.1.1
├─ path-browserify@0.0.1
├─ path-dirname@1.0.2
├─ path-exists@3.0.0
├─ path-is-absolute@1.0.1
├─ path-key@3.1.1
├─ path-parse@1.0.6
├─ path-to-regexp@0.1.7
├─ path-type@4.0.0
├─ picomatch@2.2.2
├─ pkg-up@3.1.0
├─ posix-character-classes@0.1.1
├─ postcss-attribute-case-insensitive@4.0.2
├─ postcss-calc@7.0.5
├─ postcss-color-functional-notation@2.0.1
├─ postcss-color-gray@5.0.0
├─ postcss-color-hex-alpha@5.0.3
├─ postcss-color-mod-function@3.0.3
├─ postcss-color-rebeccapurple@4.0.1
├─ postcss-colormin@4.0.3
├─ postcss-convert-values@4.0.1
├─ postcss-custom-media@7.0.8
├─ postcss-custom-properties@8.0.11
├─ postcss-custom-selectors@5.1.2
├─ postcss-dir-pseudo-class@5.0.0
├─ postcss-discard-comments@4.0.2
├─ postcss-discard-duplicates@4.0.2
├─ postcss-discard-empty@4.0.1
├─ postcss-discard-overridden@4.0.1
├─ postcss-double-position-gradients@1.0.0
├─ postcss-env-function@2.0.2
├─ postcss-focus-visible@4.0.0
├─ postcss-focus-within@3.0.0
├─ postcss-font-variant@4.0.0
├─ postcss-gap-properties@2.0.0
├─ postcss-image-set-function@3.0.1
├─ postcss-import-resolver@2.0.0
├─ postcss-import@12.0.1
├─ postcss-initial@3.0.2
├─ postcss-lab-function@2.0.1
├─ postcss-load-config@2.1.2
├─ postcss-loader@3.0.0
├─ postcss-logical@3.0.0
├─ postcss-media-minmax@4.0.0
├─ postcss-merge-longhand@4.0.11
├─ postcss-merge-rules@4.0.3
├─ postcss-minify-font-values@4.0.2
├─ postcss-minify-gradients@4.0.2
├─ postcss-minify-params@4.0.2
├─ postcss-minify-selectors@4.0.2
├─ postcss-modules-extract-imports@2.0.0
├─ postcss-modules-local-by-default@3.0.3
├─ postcss-modules-scope@2.2.0
├─ postcss-modules-values@3.0.0
├─ postcss-nesting@7.0.1
├─ postcss-normalize-charset@4.0.1
├─ postcss-normalize-display-values@4.0.2
├─ postcss-normalize-positions@4.0.2
├─ postcss-normalize-repeat-style@4.0.2
├─ postcss-normalize-string@4.0.2
├─ postcss-normalize-timing-functions@4.0.2
├─ postcss-normalize-unicode@4.0.1
├─ postcss-normalize-url@4.0.1
├─ postcss-normalize-whitespace@4.0.2
├─ postcss-ordered-values@4.1.2
├─ postcss-overflow-shorthand@2.0.0
├─ postcss-page-break@2.0.0
├─ postcss-place@4.0.1
├─ postcss-preset-env@6.7.0
├─ postcss-pseudo-class-any-link@6.0.0
├─ postcss-reduce-initial@4.0.3
├─ postcss-reduce-transforms@4.0.2
├─ postcss-replace-overflow-wrap@3.0.0
├─ postcss-selector-matches@4.0.0
├─ postcss-selector-not@4.0.0
├─ postcss-svgo@4.0.2
├─ postcss-unique-selectors@4.0.1
├─ postcss-url@8.0.0
├─ prepend-http@1.0.4
├─ prettier@1.19.1
├─ pretty-bytes@5.4.1
├─ pretty-error@2.1.1
├─ pretty-time@1.1.0
├─ process-nextick-args@2.0.1
├─ process@0.11.10
├─ proper-lockfile@4.1.1
├─ proxy-addr@2.0.6
├─ prr@1.0.1
├─ pseudomap@1.0.2
├─ public-encrypt@4.0.3
├─ pumpify@1.5.1
├─ punycode@2.1.1
├─ q@1.5.1
├─ query-string@4.3.4
├─ querystring-es3@0.2.1
├─ querystring@0.2.0
├─ randomfill@1.0.4
├─ raw-body@2.4.0
├─ read-cache@1.0.0
├─ readdirp@3.4.0
├─ regenerate-unicode-properties@8.2.0
├─ regenerator-runtime@0.13.7
├─ regenerator-transform@0.14.5
├─ regexpu-core@4.7.1
├─ regjsgen@0.5.2
├─ regjsparser@0.6.4
├─ remove-trailing-separator@1.1.0
├─ renderkid@2.0.3
├─ repeat-element@1.1.3
├─ resolve-url@0.2.1
├─ resolve@1.17.0
├─ restore-cursor@3.1.0
├─ ret@0.1.15
├─ retry@0.12.0
├─ reusify@1.0.4
├─ rewrite-imports@2.0.3
├─ rgb-regex@1.0.1
├─ rgba-regex@1.0.0
├─ run-async@2.4.1
├─ run-parallel@1.1.9
├─ run-queue@1.0.3
├─ rxjs@6.6.3
├─ safer-buffer@2.1.2
├─ sax@1.2.4
├─ serve-placeholder@1.2.2
├─ serve-static@1.14.1
├─ server-destroy@1.0.1
├─ set-value@2.0.1
├─ setimmediate@1.0.5
├─ shebang-command@2.0.0
├─ shebang-regex@3.0.0
├─ shell-quote@1.7.2
├─ simple-swizzle@0.2.2
├─ slash@3.0.0
├─ snapdragon-node@2.1.1
├─ snapdragon-util@3.0.1
├─ sort-keys@1.1.2
├─ source-list-map@2.0.1
├─ source-map-resolve@0.5.3
├─ source-map-support@0.5.19
├─ source-map-url@0.4.0
├─ split-string@3.1.0
├─ sprintf-js@1.0.3
├─ ssri@7.1.0
├─ stable@0.1.8
├─ stack-trace@0.0.10
├─ stackframe@1.2.0
├─ static-extend@0.1.2
├─ stream-browserify@2.0.2
├─ stream-each@1.2.3
├─ stream-http@2.8.3
├─ strict-uri-encode@1.1.0
├─ string_decoder@1.3.0
├─ strip-final-newline@2.0.0
├─ style-resources-loader@1.3.3
├─ stylehacks@4.0.3
├─ supports-color@7.2.0
├─ svgo@1.3.2
├─ tapable@1.1.3
├─ term-size@2.2.0
├─ terser-webpack-plugin@2.3.8
├─ terser@4.8.0
├─ text-table@0.2.0
├─ thread-loader@2.1.3
├─ through@2.3.8
├─ time-fix-plugin@2.0.7
├─ timers-browserify@2.0.11
├─ timsort@0.3.0
├─ tmp@0.0.33
├─ to-arraybuffer@1.0.1
├─ to-fast-properties@2.0.0
├─ to-object-path@0.3.0
├─ to-regex-range@2.1.1
├─ tryer@1.0.1
├─ tty-browserify@0.0.0
├─ type-fest@0.8.1
├─ type-is@1.6.18
├─ typedarray@0.0.6
├─ ua-parser-js@0.7.22
├─ uglify-js@3.11.1
├─ unfetch@4.2.0
├─ unicode-canonical-property-names-ecmascript@1.0.4
├─ unicode-match-property-ecmascript@1.0.4
├─ unicode-match-property-value-ecmascript@1.2.0
├─ unicode-property-aliases-ecmascript@1.1.0
├─ union-value@1.0.1
├─ unique-slug@2.0.2
├─ universalify@0.1.2
├─ unpipe@1.0.0
├─ unquote@1.1.1
├─ unset-value@1.0.0
├─ upath@1.2.0
├─ upper-case@1.1.3
├─ uri-js@4.4.0
├─ urix@0.1.0
├─ url-loader@2.3.0
├─ url@0.11.0
├─ use@3.1.1
├─ util-deprecate@1.0.2
├─ util.promisify@1.0.0
├─ util@0.11.1
├─ uuid@3.4.0
├─ vendors@1.0.4
├─ vm-browserify@1.1.2
├─ vue-client-only@2.0.0
├─ vue-hot-reload-api@2.3.4
├─ vue-loader@15.9.3
├─ vue-no-ssr@1.1.1
├─ vue-router@3.4.6
├─ vue-server-renderer@2.6.12
├─ vue-style-loader@4.1.2
├─ vue-template-compiler@2.6.12
├─ vue-template-es2015-compiler@1.9.1
├─ vuex@3.5.1
├─ watchpack-chokidar2@2.0.0
├─ watchpack@1.7.4
├─ webpack-bundle-analyzer@3.9.0
├─ webpack-dev-middleware@3.7.2
├─ webpack-external-import@2.2.4
├─ webpack-hot-middleware@2.25.0
├─ webpack-log@2.0.0
├─ webpack-node-externals@2.5.2
├─ webpack@4.44.2
├─ webpackbar@4.0.0
├─ which-typed-array@1.1.2
├─ which@2.0.2
├─ widest-line@3.1.0
├─ worker-farm@1.7.0
├─ wrap-ansi@6.2.0
├─ write-file-atomic@2.4.3
├─ write-json-file@2.3.0
├─ ws@6.2.1
├─ xtend@4.0.2
├─ xxhashjs@0.2.2
├─ y18n@4.0.0
└─ yallist@3.1.1
Done in 18.26s.