# [2.5.0-beta.1](https://github.com/vitejs/vite/compare/v2.5.0-beta.0...v2.5.0-beta.1) (2021-08-04)


### Bug Fixes

* change the preview default mode from `development` to `production` ([#4483](https://github.com/vitejs/vite/issues/4483)) ([77933ba](https://github.com/vitejs/vite/commit/77933ba86e7b15cb32ba80c27ae707db2a598cec))
* close vite dev server before creating new one ([#4374](https://github.com/vitejs/vite/issues/4374)) ([9e4572e](https://github.com/vitejs/vite/commit/9e4572edf5a21db9ed2d5ffa9c1a54dbea3687b3))
* register files added by addWatchFile() as current module's dependency ([db4ba56](https://github.com/vitejs/vite/commit/db4ba56e38a2ce7fa4a4ecf52d9eb0f375073560)), closes [#3216](https://github.com/vitejs/vite/issues/3216)


### Features

* add `logger.hasErrorLogged(error)` method ([#3957](https://github.com/vitejs/vite/issues/3957)) ([fb406ce](https://github.com/vitejs/vite/commit/fb406ce4c0fe6da3333c9d1c00477b2880d46352))



# [2.5.0-beta.0](https://github.com/vitejs/vite/compare/v2.4.4...v2.5.0-beta.0) (2021-08-03)


### Bug Fixes

* mixed match result of importMetaUrl ([#4482](https://github.com/vitejs/vite/issues/4482)) ([86f673a](https://github.com/vitejs/vite/commit/86f673abf4af38ab7a1e408f96e3447fdfcc5396))
* **build:** respect rollup output.assetFileNames, fix [#2944](https://github.com/vitejs/vite/issues/2944) ([#4352](https://github.com/vitejs/vite/issues/4352)) ([cbd0458](https://github.com/vitejs/vite/commit/cbd04588a2fe62e689fc5f7bb0b71610b88f2a3e))
* **deps:** update all non-major dependencies ([#4468](https://github.com/vitejs/vite/issues/4468)) ([cd54a22](https://github.com/vitejs/vite/commit/cd54a22b8d5048f5d25a9954697f49b6d65dcc1f))
* **html:** cover more cases in bodyPrependInjectRE ([#4474](https://github.com/vitejs/vite/issues/4474)) ([40c51e1](https://github.com/vitejs/vite/commit/40c51e16802d39fef03d145bfc3a5089867dd8cb))
* **server:** keep port when modifying the config file ([#4460](https://github.com/vitejs/vite/issues/4460)) ([056b17e](https://github.com/vitejs/vite/commit/056b17eb82becd08217346dddb47f8ecbf55fe3f))
* config port timing, fix [#4094](https://github.com/vitejs/vite/issues/4094) ([#4104](https://github.com/vitejs/vite/issues/4104)) ([6b98fdd](https://github.com/vitejs/vite/commit/6b98fddd84545a8500ac7767c514c6ce3bf3bf96))
* overwrite configEnv.mode if the user explicitly set mode option (fix [#4441](https://github.com/vitejs/vite/issues/4441)) ([#4437](https://github.com/vitejs/vite/issues/4437)) ([7d340a6](https://github.com/vitejs/vite/commit/7d340a6339cb5497ef54d3684697c4660ab97302))
* update dependency @rollup/plugin-commonjs to v20, fix [#2623](https://github.com/vitejs/vite/issues/2623) ([#4469](https://github.com/vitejs/vite/issues/4469)) ([f9e5d63](https://github.com/vitejs/vite/commit/f9e5d638431dc27619d0cafdd7ea0dd8543133d3))
* **scan:** improve import regex and allow multiline comments ([#4088](https://github.com/vitejs/vite/issues/4088)) ([76dbef6](https://github.com/vitejs/vite/commit/76dbef62741d4a53be1e6e8a0e04d3727759cc93))
* @vite/client http request is 404 not found ([#4187](https://github.com/vitejs/vite/issues/4187)) ([21ecdac](https://github.com/vitejs/vite/commit/21ecdacb40ba4fd1b8d248e1a1c99c21257f238d))
* import sass file even if not listed in package.json ([#3627](https://github.com/vitejs/vite/issues/3627)) ([a5b2b4f](https://github.com/vitejs/vite/commit/a5b2b4f11c5335828fd8179721aee73191df46e9))
* the return value of resolve by adding a namespace when processing a '@' in filter ([#3534](https://github.com/vitejs/vite/issues/3534)) ([d4e979f](https://github.com/vitejs/vite/commit/d4e979fbe70e2e7ab03407bd601b813e1671c144))
* **build:** fix define plugin spread operations ([#4397](https://github.com/vitejs/vite/issues/4397)) ([bd7c148](https://github.com/vitejs/vite/commit/bd7c1481cecf5eecc87a69ff8e8f54fa4bf4bfed))
* preserve base in HMR for CSS referenced in link tags ([#4407](https://github.com/vitejs/vite/issues/4407)) ([a06b26b](https://github.com/vitejs/vite/commit/a06b26b461dd05451c6c1ca20fce3b0e392c086e))


### Features

* **ssr:** tolerate circular imports ([#3950](https://github.com/vitejs/vite/issues/3950)) ([69f91a1](https://github.com/vitejs/vite/commit/69f91a1c03a129ab324c20fddfd2a07e729add96))
* implement custom logger ([#2521](https://github.com/vitejs/vite/issues/2521)) ([59841f0](https://github.com/vitejs/vite/commit/59841f0b65a2e554db964e530b18dcdc9b3b9586))
* **css:** support css module compose/from path resolution ([#4378](https://github.com/vitejs/vite/issues/4378)) ([690b35e](https://github.com/vitejs/vite/commit/690b35e857cea833ed4f1782e5c87b2b7064d072))
* minify css with esbuild, deprecate build.cleanCssOptions ([#4371](https://github.com/vitejs/vite/issues/4371)) ([4454688](https://github.com/vitejs/vite/commit/4454688bd8eda0217ec3c7397038bf3ece39b5b0))
* modulepreload polyfill ([#4058](https://github.com/vitejs/vite/issues/4058)) ([cb75dbd](https://github.com/vitejs/vite/commit/cb75dbd4a2b1c56e2a7aeaf1625818a4d1865f00))
* respect tsconfig options that affects compilation results ([#4279](https://github.com/vitejs/vite/issues/4279)) ([2986f6e](https://github.com/vitejs/vite/commit/2986f6ec78818910675b7d4f81b3dbd6ca51143a))



## [2.4.4](https://github.com/vitejs/vite/compare/v2.4.3...v2.4.4) (2021-07-27)


### Bug Fixes

* **deps:** update all non-major dependencies ([#4387](https://github.com/vitejs/vite/issues/4387)) ([2f900ba](https://github.com/vitejs/vite/commit/2f900ba4d4ad8061e0046898e8d1de3129e7f784))
* --https get ignored in preview ([#4318](https://github.com/vitejs/vite/issues/4318)) ([a870584](https://github.com/vitejs/vite/commit/a8705846f7f604263a64aece67deb7593c498dcd))
* don't interact with res if refresh has happened ([#4370](https://github.com/vitejs/vite/issues/4370)) ([c90b7d9](https://github.com/vitejs/vite/commit/c90b7d9d89a803b51d56f2885e5e61bbcf1c1c43))
* fix pre-bundling executes multiple times ([#3640](https://github.com/vitejs/vite/issues/3640)) ([41a00df](https://github.com/vitejs/vite/commit/41a00dff62ee2ae60099953b1d3cc91f7bad0d7d))
* handle imports from dot directories ([#3739](https://github.com/vitejs/vite/issues/3739)) ([f4f0100](https://github.com/vitejs/vite/commit/f4f0100649220453d961b6c66531c58026885680))
* ignore ENOENT in `injectSourcesContent` ([#2904](https://github.com/vitejs/vite/issues/2904)) ([0693d03](https://github.com/vitejs/vite/commit/0693d038e096dd4db3140507269c6aaeefd2186e))
* provide build load fallback for arbitrary request with queries ([f097aa1](https://github.com/vitejs/vite/commit/f097aa10c17faf0b73b239a34ca72934d38188d7))
* **css:** cachedPostcssConfig reused for multiple builds ([#3906](https://github.com/vitejs/vite/issues/3906)) ([3a97644](https://github.com/vitejs/vite/commit/3a9764403722a32b8d51222025e6516ef557e178))


### Features

* support ?inline css query to avoid css insertion ([e1de8a8](https://github.com/vitejs/vite/commit/e1de8a888ea9adb9dc415cf74aec43dfa83aa526))



## [2.4.3](https://github.com/vitejs/vite/compare/v2.4.2...v2.4.3) (2021-07-20)


### Bug Fixes

* call createFileOnlyEntry() only for CSS deps, fix [#4150](https://github.com/vitejs/vite/issues/4150) ([#4267](https://github.com/vitejs/vite/issues/4267)) ([89e3160](https://github.com/vitejs/vite/commit/89e3160d86bc8c27d6d33b82adec7c44016c3fc3))
* **dev:** only rewrite SSR stacktrace when possible ([#4248](https://github.com/vitejs/vite/issues/4248)) ([887c247](https://github.com/vitejs/vite/commit/887c247984abc0f80d8b19a1d681855944f6d01a))
* **util:** copyDir may cause an infinite loop ([#4310](https://github.com/vitejs/vite/issues/4310)) ([da64197](https://github.com/vitejs/vite/commit/da64197bc8bcd8f848aef3ae7a87a2d0d56ebd55))
* correctly ignore optional deps when bundling vite deps ([#4223](https://github.com/vitejs/vite/issues/4223)) ([b5ab77d](https://github.com/vitejs/vite/commit/b5ab77d878d7bdc5c68dbbf144395f2a590f7d99)), closes [#3977](https://github.com/vitejs/vite/issues/3977) [#3850](https://github.com/vitejs/vite/issues/3850)
* do not end process in middleware mode, fix [#4196](https://github.com/vitejs/vite/issues/4196) ([#4232](https://github.com/vitejs/vite/issues/4232)) ([1c994f8](https://github.com/vitejs/vite/commit/1c994f840e707e1085ee1e1aed0986bb92e39422))
* improve indent of built html file ([#4227](https://github.com/vitejs/vite/issues/4227)) ([0316f14](https://github.com/vitejs/vite/commit/0316f14eddb6854321ed0c1bbeb29c2668c6f08c))
* nested dependencies from sub node_modules, fix [#3254](https://github.com/vitejs/vite/issues/3254) ([#4091](https://github.com/vitejs/vite/issues/4091)) ([b465d3e](https://github.com/vitejs/vite/commit/b465d3eb87d415b2f484dae77daab57adc3415bf))


### Features

* `vite preview` port is used automatically `+1` ([#4219](https://github.com/vitejs/vite/issues/4219)) ([179a057](https://github.com/vitejs/vite/commit/179a0576b2b8da4fc0c32a574b8ae487b8b5265a))
* enable usage of function as library fileName, close [#3585](https://github.com/vitejs/vite/issues/3585) ([#3625](https://github.com/vitejs/vite/issues/3625)) ([772b2f7](https://github.com/vitejs/vite/commit/772b2f73b0da08181a7cc29e0eb50073ff3cc464))
* extract `config.base` in `importAnalysisBuild.ts` ([#4096](https://github.com/vitejs/vite/issues/4096)) ([ab59598](https://github.com/vitejs/vite/commit/ab59598f4e07a466d8319e6d81047f75517085db))
* library mode does not include preload ([#4097](https://github.com/vitejs/vite/issues/4097)) ([decc7d8](https://github.com/vitejs/vite/commit/decc7d885d108a3e96ffc82abcb4057f54aa6db5))



## [2.4.2](https://github.com/vitejs/vite/compare/v2.4.1...v2.4.2) (2021-07-12)


### Bug Fixes

* __VITE_PRELOAD__ replacement error ([#4163](https://github.com/vitejs/vite/issues/4163)) ([d377aae](https://github.com/vitejs/vite/commit/d377aae05f73779869ba84c91e050fe0a9f50dce)), closes [#3051](https://github.com/vitejs/vite/issues/3051)
* shutdown process after closing server ([#4082](https://github.com/vitejs/vite/issues/4082)) ([eac779c](https://github.com/vitejs/vite/commit/eac779c3d7c306288b01a35239e9eaaa2273c1a5))
* **build:** resolve license files correctly ([#4149](https://github.com/vitejs/vite/issues/4149)) ([bf32b41](https://github.com/vitejs/vite/commit/bf32b41bc4ac89e1fd39c27fb22c3bfa0a150152))
* **utils:** add dot-all flag to match all characters, fix [#3761](https://github.com/vitejs/vite/issues/3761) ([#3780](https://github.com/vitejs/vite/issues/3780)) ([b9cdfbe](https://github.com/vitejs/vite/commit/b9cdfbeedcd74d33c30cab9d38b1a9ca6d1cd8c2))


### Features

* cache certificate ([#3642](https://github.com/vitejs/vite/issues/3642)) ([5dd670f](https://github.com/vitejs/vite/commit/5dd670f06dc2b0928771d571ce6ca5164b0db8e9))



## [2.4.1](https://github.com/vitejs/vite/compare/v2.4.0...v2.4.1) (2021-07-06)


### Bug Fixes

* **hmr:** html registered as a PostCSS dependency, fix [#3716](https://github.com/vitejs/vite/issues/3716) ([#4127](https://github.com/vitejs/vite/issues/4127)) ([09c6c94](https://github.com/vitejs/vite/commit/09c6c94690ea3fc8b66bb6781995b3e15faedf8f))
* specify full filepath to importMeta.d.ts, fix [#4125](https://github.com/vitejs/vite/issues/4125) ([#4138](https://github.com/vitejs/vite/issues/4138)) ([3bc1d78](https://github.com/vitejs/vite/commit/3bc1d78843d970d367e235f6c30fd7996cf7335a))



# [2.4.0](https://github.com/vitejs/vite/compare/v2.4.0-beta.3...v2.4.0) (2021-07-05)



# [2.4.0-beta.3](https://github.com/vitejs/vite/compare/v2.4.0-beta.2...v2.4.0-beta.3) (2021-07-02)


### Bug Fixes

* **ssr:** Transform named default exports without altering scope ([#4053](https://github.com/vitejs/vite/issues/4053)) ([5211aaf](https://github.com/vitejs/vite/commit/5211aaf9b71022a1153dd3ccdef540fd51be72c0))
* add `type: "module"` hint to cache directory ([#4063](https://github.com/vitejs/vite/issues/4063)) ([58a29b2](https://github.com/vitejs/vite/commit/58a29b241662f77dbf971967b913f4e75f91fe26))
* allow preprocessor to be installed outside of the root directory ([#3988](https://github.com/vitejs/vite/issues/3988)) ([a0a80f8](https://github.com/vitejs/vite/commit/a0a80f8e992393f01b4b7377e7dc53059ddf1fe1))
* Avoid importing in source that __vitePreload has declared (close [#4016](https://github.com/vitejs/vite/issues/4016)) ([#4041](https://github.com/vitejs/vite/issues/4041)) ([bd34203](https://github.com/vitejs/vite/commit/bd34203bc40d6a406dfac3ab6cb41f5dfed63a77))
* ensure that esbuild uses the same working directory as Vite ([#4001](https://github.com/vitejs/vite/issues/4001)) ([19abafe](https://github.com/vitejs/vite/commit/19abafeedda8008f4cc9eeda4cf8cb46e57de8b9))
* fix esbuild break when importRe matches multiline import ([#4054](https://github.com/vitejs/vite/issues/4054)) ([eb2e41b](https://github.com/vitejs/vite/commit/eb2e41b098fb3d5f367c1f4fdfcad12f7538ac16))
* skip redirect and error fallback on middleware mode ([#4057](https://github.com/vitejs/vite/issues/4057)) ([d156a9f](https://github.com/vitejs/vite/commit/d156a9f364dddcfc41338f83e39db38a00a2ceb0))
* the current main branch code build the vite project error ([#4059](https://github.com/vitejs/vite/issues/4059)) ([4adc970](https://github.com/vitejs/vite/commit/4adc9706874581d2d5048fb48c135154591360cf))
* use `.mjs` extension for injected client modules ([#4061](https://github.com/vitejs/vite/issues/4061)) ([cca92c4](https://github.com/vitejs/vite/commit/cca92c47d54e0f96b56964f13fbe0b2d050c5ed9))
* use path type import, fix [#4028](https://github.com/vitejs/vite/issues/4028) ([#4031](https://github.com/vitejs/vite/issues/4031)) ([e092e89](https://github.com/vitejs/vite/commit/e092e899dad28f50aaa004419e9da50cf31db72d))



# [2.4.0-beta.2](https://github.com/vitejs/vite/compare/v2.4.0-beta.1...v2.4.0-beta.2) (2021-06-29)


### Bug Fixes

* revert resolve nested dependencies [#3753](https://github.com/vitejs/vite/issues/3753) ([#4019](https://github.com/vitejs/vite/issues/4019)) ([b6f4293](https://github.com/vitejs/vite/commit/b6f4293435bf90c9a64476d8bfbb022f4f2af9a9)), closes [#4005](https://github.com/vitejs/vite/issues/4005)
* **commonjs:** `ignoreDynamicRequires` should default to `false` ([#4015](https://github.com/vitejs/vite/issues/4015)) ([c08069c](https://github.com/vitejs/vite/commit/c08069cb3bdf7e7aa16d9cfaef4c1aea3a29cfa2)), closes [/github.com/vitejs/vite/pull/3353#issuecomment-851520683](https://github.com//github.com/vitejs/vite/pull/3353/issues/issuecomment-851520683) [#3426](https://github.com/vitejs/vite/issues/3426) [#3997](https://github.com/vitejs/vite/issues/3997)
* **css:** skip comma when matching css url ([#4004](https://github.com/vitejs/vite/issues/4004)) ([7d0bc26](https://github.com/vitejs/vite/commit/7d0bc2691f0291c3a9b0df992554f18bf85c8892))



# [2.4.0-beta.1](https://github.com/vitejs/vite/compare/v2.4.0-beta.0...v2.4.0-beta.1) (2021-06-29)


### Bug Fixes

* **hmr:** entry mod's importers contains css mod invalidate hmr ([#3929](https://github.com/vitejs/vite/issues/3929)) ([d97b33a](https://github.com/vitejs/vite/commit/d97b33a8cb9a72ed64244f239900a9a862b6ba68))
* **types:** correct import of types ([#4003](https://github.com/vitejs/vite/issues/4003)) ([4954636](https://github.com/vitejs/vite/commit/4954636c859fbfce76d02aea7881e59435fa3211))


### Features

* allow passing options to rollupjs dynamic import vars plugin ([#3047](https://github.com/vitejs/vite/issues/3047)) ([5507b4c](https://github.com/vitejs/vite/commit/5507b4c912d2e0e36e63488f5db8e9d1bb0a80f6))



# [2.4.0-beta.0](https://github.com/vitejs/vite/compare/v2.3.8...v2.4.0-beta.0) (2021-06-27)

### BREAKING CHANGES

- **server:** `server.fsServe` renamed to `server.fs` ([#3965](https://github.com/vitejs/vite/pull/3965))
- **server:** `server.fs.root` deprecated in favor of `server.fs.allow` ([#3968](https://github.com/vitejs/vite/pull/3968))

### Security

We have improved the file serving boundaries detection with ([#3784](https://github.com/vitejs/vite/issues/3784)). While it's still experimental and **disabled by default**, you can opt-in it by

```js
// vite.config.js
export default {
  server: {
    fs: {
      strict: true
    }
  }
}
```

It should smartly serve the files related to your project (directly imported, linked deps, etc.) while denying the rest. If you find any false-negative, please [open an issue](https://github.com/vitejs/vite/issues/new?assignees=&labels=pending+triage&template=bug_report.yml) with reproduction to report.

### Bug Fixes

* **build:** bundle non-inlined workers with rollup ([#2494](https://github.com/vitejs/vite/issues/2494)) ([18a2208](https://github.com/vitejs/vite/commit/18a22089df34c32daddf3b280c58f25cae73f722))
* resolve nested dependencies ([#3254](https://github.com/vitejs/vite/issues/3254)) ([#3753](https://github.com/vitejs/vite/issues/3753)) ([8467f64](https://github.com/vitejs/vite/commit/8467f64aee218dcb3135bb832ccaed36d647052f))
* **css:** file or contents missing error in build watch ([#3742](https://github.com/vitejs/vite/issues/3742)) ([#3747](https://github.com/vitejs/vite/issues/3747)) ([26b1b99](https://github.com/vitejs/vite/commit/26b1b9988db1ab980ca816d1914b26d6d3424502))
* **deps:** update all non-major dependencies ([#3878](https://github.com/vitejs/vite/issues/3878)) ([a66a805](https://github.com/vitejs/vite/commit/a66a8053e9520d20bcf95fce870570c5195bcc91))
* **scan:** 'for await' support in script setup for dev server ([#3889](https://github.com/vitejs/vite/issues/3889)) ([dd46cd1](https://github.com/vitejs/vite/commit/dd46cd1d030dcfffcbb2f20aff2b388cd18700f4))
* **scan:** avoid breaking html comment regex inside script of scanned html-like files ([bb095db](https://github.com/vitejs/vite/commit/bb095db11db5c7a12db6dcee866694f1f68d1e15))
* **ssr:** fix binding overwrite at nested function, fix [#3856](https://github.com/vitejs/vite/issues/3856) ([#3869](https://github.com/vitejs/vite/issues/3869)) ([85f51c1](https://github.com/vitejs/vite/commit/85f51c191d4d3317c5796e6c614ade6f7c21dddf))
* **ssr:** normalize manifest filenames ([#3706](https://github.com/vitejs/vite/issues/3706)) ([aa8ca3f](https://github.com/vitejs/vite/commit/aa8ca3f35218c9fb48f87d3f6f4681d379ee45ca)), closes [#3303](https://github.com/vitejs/vite/issues/3303)
* **ssr:** not flatten export * as (fix [#3934](https://github.com/vitejs/vite/issues/3934)) ([#3954](https://github.com/vitejs/vite/issues/3954)) ([7381d27](https://github.com/vitejs/vite/commit/7381d27564045a05cffbe4229d71d64b5a791042))
* **ssr:** not importing browser exports, fix [#3772](https://github.com/vitejs/vite/issues/3772) ([#3933](https://github.com/vitejs/vite/issues/3933)) ([f623ba3](https://github.com/vitejs/vite/commit/f623ba37dbc517656a7ffb10bc1b3cb221a4bc72))
* do not end server process in CI ([#3659](https://github.com/vitejs/vite/issues/3659)) ([5999444](https://github.com/vitejs/vite/commit/5999444496b6309460687b0769afad018aa21859))
* missing styles with build watch ([#3742](https://github.com/vitejs/vite/issues/3742)) ([#3887](https://github.com/vitejs/vite/issues/3887)) ([c9a6efe](https://github.com/vitejs/vite/commit/c9a6efe17108a899e1d1f4cb490973486223da99))
* multiple css url separation (fix [#3922](https://github.com/vitejs/vite/issues/3922)) ([#3926](https://github.com/vitejs/vite/issues/3926)) ([2d01e62](https://github.com/vitejs/vite/commit/2d01e62a70e534694ee1d87f4a328e796ae4c8fe))
* only downgrade target to es2019 when actually using terser ([bd8723e](https://github.com/vitejs/vite/commit/bd8723eb36be368b4a45240e1f0159fbd40a81a4))


### Features

* add client events to import.meta.hot.on ([#3638](https://github.com/vitejs/vite/issues/3638)) ([de1ddd4](https://github.com/vitejs/vite/commit/de1ddd401802784a74f5106c5173945e760d3f03))
* fs-serve import graph awareness ([#3784](https://github.com/vitejs/vite/issues/3784)) ([c45a02f](https://github.com/vitejs/vite/commit/c45a02f0279103be922a2d24b8cd05141e0ff165))
* generate inline sourcemaps for bundled vite.config.js files ([#3949](https://github.com/vitejs/vite/issues/3949)) ([cff2fcd](https://github.com/vitejs/vite/commit/cff2fcd8db98bb1c046816fd2e01dcbffbe86629))
* support for regex for ssr.noExternal ([#3819](https://github.com/vitejs/vite/issues/3819)) ([330c94c](https://github.com/vitejs/vite/commit/330c94c4355e4f091e6e4f46c6a47dbfba410e40))
* support new URL(url, import.meta.url) usage ([4cbb40d](https://github.com/vitejs/vite/commit/4cbb40d2f1a4050c9944e7e1d9e0f5b204b7e37b))



## [2.3.8](https://github.com/vitejs/vite/compare/v2.3.7...v2.3.8) (2021-06-19)


### Bug Fixes

* **css:** filter out function name suffixes with url ([#3752](https://github.com/vitejs/vite/issues/3752)) ([9aa255a](https://github.com/vitejs/vite/commit/9aa255a0abcb9f5b23c34607b2188f796f4b6c94))
* **deps:** update all non-major dependencies ([#3791](https://github.com/vitejs/vite/issues/3791)) ([74d409e](https://github.com/vitejs/vite/commit/74d409eafca8d74ec4a6ece621ea2895bc1f2a32))
* **hmr:** always invalidate all affected modules ([e048114](https://github.com/vitejs/vite/commit/e048114d3657fc8e2fec645eba3f5f2fe230ceb7))
* **hmr:** avoid css propagation infinite loop ([7362e6e](https://github.com/vitejs/vite/commit/7362e6e9a7a0f0177b467f1cf80552acf22c46a0))
* **hmr:** avoid duplicated modules for css dependency ([385ced9](https://github.com/vitejs/vite/commit/385ced9c2e9b5f06e9c06669fe19a0a98cc82c8b))
* **hmr/css:** check CSS importers for hmr boundaries - fix Tailwind 2.2 compat ([6eaec3a](https://github.com/vitejs/vite/commit/6eaec3ab74d126310d93f8a93f8577bed1c3f474))
* **hmr/css:** fix infinite recursion on hmr ([#3865](https://github.com/vitejs/vite/issues/3865)) ([0d5726f](https://github.com/vitejs/vite/commit/0d5726fff2fe724ffec3c0621e3dcd6775b0fe8b))
* ?import with trailing = added by some servers ([#3805](https://github.com/vitejs/vite/issues/3805)) ([460d1cd](https://github.com/vitejs/vite/commit/460d1cda317e4c4d03434f2b3d8de9152620005b))
* don't replace `process.env` if `process` not global variable ([#3703](https://github.com/vitejs/vite/issues/3703)) ([5aeadb7](https://github.com/vitejs/vite/commit/5aeadb719944152be7ed9f9472aa2238ea3557c0))
* upgrade esbuild for esm compatibility ([#3718](https://github.com/vitejs/vite/issues/3718)) ([dbb5eab](https://github.com/vitejs/vite/commit/dbb5eabe246747abab187a6c8d90cd418856e048)), closes [#3399](https://github.com/vitejs/vite/issues/3399) [#3413](https://github.com/vitejs/vite/issues/3413)


### Features

* allow 'hidden' sourcemap to remove //# sourceMappingURL from generated maps ([#3684](https://github.com/vitejs/vite/issues/3684)) ([19e479b](https://github.com/vitejs/vite/commit/19e479ba0dd1da4d1de075bdf11edabe00af6cb6))



## [2.3.7](https://github.com/vitejs/vite/compare/v2.3.6...v2.3.7) (2021-06-08)


### Bug Fixes

* Include src files in vite npm bundle (for sourcemaps) ([#3656](https://github.com/vitejs/vite/issues/3656)) ([294d8b4](https://github.com/vitejs/vite/commit/294d8b472ca5d5079d8fe35ecb1b0bf6cf7720db))
* show error message above the stack when HMR overlay is disabled ([#3677](https://github.com/vitejs/vite/issues/3677)) ([6b4c355](https://github.com/vitejs/vite/commit/6b4c3550f673253ca175a1e2ca2efb8d1ec85b3b))
* tolerant fs error in formatError ([#3665](https://github.com/vitejs/vite/issues/3665)) ([5146cc5](https://github.com/vitejs/vite/commit/5146cc5eb2bfe4317e3a7c8590963cbebaa5b3e9))
* update `sirv` to decode url in preview ([#3680](https://github.com/vitejs/vite/issues/3680)) ([0430127](https://github.com/vitejs/vite/commit/0430127b7b7216d92a351fcb9c80753563a318e6))


### Features

* **css:** support postcss dir-dependency message type ([#3707](https://github.com/vitejs/vite/issues/3707)) ([665d438](https://github.com/vitejs/vite/commit/665d43872914c7a79a5a79aa4b6349961e68a10d))



## [2.3.6](https://github.com/vitejs/vite/compare/v2.3.5...v2.3.6) (2021-06-02)


### Bug Fixes

* revert avoid css leaking into emitted javascript ([#3402](https://github.com/vitejs/vite/issues/3402)) ([#3630](https://github.com/vitejs/vite/issues/3630)) ([91eb2a6](https://github.com/vitejs/vite/commit/91eb2a6bc30103569cce05f6da1acdd72d5f71f0))
* **types:** add '*?.sharedworker' typing ([#3618](https://github.com/vitejs/vite/issues/3618)) ([690ff99](https://github.com/vitejs/vite/commit/690ff999cdebf390a84506c5b62a17e6e8f47c17))



## [2.3.5](https://github.com/vitejs/vite/compare/v2.3.4...v2.3.5) (2021-06-01)


### Bug Fixes

* cannot recognize JS url correctly([#3568](https://github.com/vitejs/vite/issues/3568)) ([#3572](https://github.com/vitejs/vite/issues/3572)) ([ab08652](https://github.com/vitejs/vite/commit/ab0865223f2fd8c460ee9b5108dbe67b9ad534a1))
* **tests:** fix tests run fail in the Chinese directory ([#3586](https://github.com/vitejs/vite/issues/3586)) ([3cab2c2](https://github.com/vitejs/vite/commit/3cab2c2202c2c7188b4f76d872c94a9f6acaf122))
* update esbuild to 0.12 ([#3570](https://github.com/vitejs/vite/issues/3570)) ([421c530](https://github.com/vitejs/vite/commit/421c530eae668f0ddadd9b4ef6d366a58d74febc))


### Features

* **config:** add `envDir` option ([#3407](https://github.com/vitejs/vite/issues/3407)) ([472ba5d](https://github.com/vitejs/vite/commit/472ba5d7198e5db631ddafc1fd2adf78ce26003e))
* **plugins/worker:** support SharedWorker (resolve [#2093](https://github.com/vitejs/vite/issues/2093)) ([#2505](https://github.com/vitejs/vite/issues/2505)) ([d78191c](https://github.com/vitejs/vite/commit/d78191c5ce5f9c0e5a2329c7b113fc25b27535b9))
* **ssr:** include non-CSS assets in the manifest ([#3556](https://github.com/vitejs/vite/issues/3556)) ([adc7170](https://github.com/vitejs/vite/commit/adc7170dac0b08f3cffd49fa4844a6fa871067dc))
* added clientPort to HmrOptions ([#3578](https://github.com/vitejs/vite/issues/3578)) ([7db69a3](https://github.com/vitejs/vite/commit/7db69a3c284d58ebb51f91c5f44da9890d056b19))



## [2.3.4](https://github.com/vitejs/vite/compare/v2.3.3...v2.3.4) (2021-05-25)


### Bug Fixes

* allow passing an array as sass / scss importer ([#3529](https://github.com/vitejs/vite/issues/3529)) ([e344cdd](https://github.com/vitejs/vite/commit/e344cdd28425e08b2481b1a6289b820764f25928))
* avoid css leaking into emitted javascript ([#3402](https://github.com/vitejs/vite/issues/3402)) ([65d333d](https://github.com/vitejs/vite/commit/65d333d8eb95ea3ab3d611d9c21d05de9657f134))
* clean manifest plugin state at build start ([#3530](https://github.com/vitejs/vite/issues/3530)) ([c9da635](https://github.com/vitejs/vite/commit/c9da635841cc20e65df6a51c3f0b7a7fb79a814f))
* data-uri plugin cache reset at buildStart ([#3537](https://github.com/vitejs/vite/issues/3537)) ([9d97b6d](https://github.com/vitejs/vite/commit/9d97b6d0084a543b6e692890d8a095e4bee5dfac))
* do not cache module while the file contains import.meta.glob ([#3005](https://github.com/vitejs/vite/issues/3005)) ([e7b8f41](https://github.com/vitejs/vite/commit/e7b8f41c45ea95cfd12801dfd22fa9be99de8ac8))
* ensure new assets cache at build start, fix [#3271](https://github.com/vitejs/vite/issues/3271) ([#3512](https://github.com/vitejs/vite/issues/3512)) ([9484c0f](https://github.com/vitejs/vite/commit/9484c0f392407d71efad64b585b8656202c9b411))
* ensure new CSS modules cache at build start ([#3516](https://github.com/vitejs/vite/issues/3516)) ([07ad2b4](https://github.com/vitejs/vite/commit/07ad2b494b14701f54376afe6ce49bf24a3e7cd9))
* **preview:** [#3487](https://github.com/vitejs/vite/issues/3487) preview should serve latest content by default ([#3488](https://github.com/vitejs/vite/issues/3488)) ([9a4183d](https://github.com/vitejs/vite/commit/9a4183dbc0d4dcf278ac829b96230b3d2b24bd5e))
* **preview:** allow to disable HTTPS ([#3514](https://github.com/vitejs/vite/issues/3514)) ([cf1632e](https://github.com/vitejs/vite/commit/cf1632ea525b4e3230afaee908ef42f0e7321fe8))
* **preview:** support custom hostname ([#3506](https://github.com/vitejs/vite/issues/3506)) ([5979d0e](https://github.com/vitejs/vite/commit/5979d0e3b2c071ee15408aa67974af04f7bb1c3d))
* **types:** add .module.pcss typings, fix [#3518](https://github.com/vitejs/vite/issues/3518) ([#3519](https://github.com/vitejs/vite/issues/3519)) ([3475351](https://github.com/vitejs/vite/commit/3475351a371df2e17689a99968fdee827b0b2d16))
* handle HMR for files with more than one glob import ([#3497](https://github.com/vitejs/vite/issues/3497)) ([05bd96e](https://github.com/vitejs/vite/commit/05bd96e21ced682251378c4ad7ae0dee59195eae))
* inline webworker safari support ([#3468](https://github.com/vitejs/vite/issues/3468)) ([2671546](https://github.com/vitejs/vite/commit/26715465f7430e6fd9a0cf2ae9e49fb099cced3a))
* invalidate import globs upon new/removed files (fix [#3499](https://github.com/vitejs/vite/issues/3499)) ([#3500](https://github.com/vitejs/vite/issues/3500)) ([b31604e](https://github.com/vitejs/vite/commit/b31604e08c4333bed5a3c4cc6876d1eb337a100b))
* track deps for css [@import](https://github.com/import) in build watch mode, fix [#3387](https://github.com/vitejs/vite/issues/3387) ([#3478](https://github.com/vitejs/vite/issues/3478)) ([13bda33](https://github.com/vitejs/vite/commit/13bda3368e73ade311f1c113894c2dcb329cef8d))


### Features

* support serving `index.html` in middleware mode ([#2871](https://github.com/vitejs/vite/issues/2871)) ([b1598ce](https://github.com/vitejs/vite/commit/b1598cec7ee185f796d8679f0a97d36b80fe1949))



## [2.3.3](https://github.com/vitejs/vite/compare/v2.3.2...v2.3.3) (2021-05-17)


### Bug Fixes

* ignore ids that start with \0 in plugin asset, fix [#3424](https://github.com/vitejs/vite/issues/3424) ([#3436](https://github.com/vitejs/vite/issues/3436)) ([f6cfe30](https://github.com/vitejs/vite/commit/f6cfe30abfc5179262aea807173d7591fd4dc876))
* restore dynamic-import-polyfill ([#3434](https://github.com/vitejs/vite/issues/3434)) ([4112c5d](https://github.com/vitejs/vite/commit/4112c5d103673b83c50d446096086617dfaac5a3))
* sass importer can't be undefined (fix: [#3390](https://github.com/vitejs/vite/issues/3390)) ([#3395](https://github.com/vitejs/vite/issues/3395)) ([30ff5a2](https://github.com/vitejs/vite/commit/30ff5a235d2a832cb45a761a03c5947460417b40))
* skip fs fallback for out of root urls, fix [#3364](https://github.com/vitejs/vite/issues/3364) ([#3431](https://github.com/vitejs/vite/issues/3431)) ([19dae99](https://github.com/vitejs/vite/commit/19dae997f91607424af2d0e159ae2570463bbcb3))
* warn about dynamic import polyfill only during build ([#3446](https://github.com/vitejs/vite/issues/3446)) ([5fe0550](https://github.com/vitejs/vite/commit/5fe05507dd28bbd863469628bc61b45a04f938bd))



## [2.3.2](https://github.com/vitejs/vite/compare/v2.3.1...v2.3.2) (2021-05-12)


### Bug Fixes

* **css:** fix sass importer error ([#3368](https://github.com/vitejs/vite/issues/3368)) ([3f04abf](https://github.com/vitejs/vite/commit/3f04abf0ff21c7b2969902c3d8d87f4b1b93740f))
* **server:** hostname defaults to localhost, fix [#3355](https://github.com/vitejs/vite/issues/3355) ([#3383](https://github.com/vitejs/vite/issues/3383)) ([8b5a6a8](https://github.com/vitejs/vite/commit/8b5a6a855091e6f744cc7b886cf927d14dc74d50))



## [2.3.1](https://github.com/vitejs/vite/compare/v2.3.0...v2.3.1) (2021-05-12)

### Notable Changes

We introduced a security fix in v2.3.0 to restrict file access outside of the workspace root. We received reports of issues with symlinks and monorepo setups, so we are marking this feature as experimental and disabling it by default to avoid disruption in the ecosystem.

A new experimental option `server.fsServe.strict` was added defaulting to `false`. This **disables the restrictions by default**. The `fsServe` restrictions are going to be enabled by default in a future version, once the issues are been resolved and the logic becomes more robust. You can opt-in to this security change using (experimental)

```js
// vite.config.js
export default {
  server: {
    fsServe: {
      strict: true
    }
  }
}
```

### Bug Fixes

* bump @rollup/plugin-commonjs to v19, fix [#3312](https://github.com/vitejs/vite/issues/3312) ([#3353](https://github.com/vitejs/vite/issues/3353)) ([c6ef6d0](https://github.com/vitejs/vite/commit/c6ef6d084c2368f6c73e03cc18bcab05aea9cfa6))
* disable fsServe restrictions by default ([#3377](https://github.com/vitejs/vite/issues/3377)) ([5433a65](https://github.com/vitejs/vite/commit/5433a655534cd4c716c2eba2f89f20bfa328e812))
* normalize url in `ensureServingAccess` ([#3350](https://github.com/vitejs/vite/issues/3350)) ([deb465b](https://github.com/vitejs/vite/commit/deb465ba412312ccae2d5b767de327d6f8562e7e))
* use the closest package.json as root when workspace not found fo… ([#3374](https://github.com/vitejs/vite/issues/3374)) ([42b35ac](https://github.com/vitejs/vite/commit/42b35ac567b02b8142a7a51df320d7deb2ec4ac1))



# [2.3.0](https://github.com/vitejs/vite/compare/v2.2.4...v2.3.0) (2021-05-11)

## BREAKING CHANGES

- Browser default targets changed (PR [#2976](https://github.com/vitejs/vite/pull/2976))
    - Default browser support range has changed. The minimum requirement is now [native dynamic import support](https://caniuse.com/es6-module-dynamic-import). Most notably, this means support for legacy Microsoft Edge (16-18) has been dropped.
    - `vite/dynamic-import-polyfill` removed and no longer required in custom entries

### Why are there breaking changes in a minor?

- **Limited impact:** The affected target browsers are ones that natively support [ES6 modules](https://caniuse.com/es6-module) (92.83% of global usage) but do not support [native dynamic imports](https://caniuse.com/es6-module-dynamic-import) (92.34% of global usage). So this is a small range affecting only 0.49% of global usage.

    This number should continue to decrease in the future as most modern browsers are evergreen. You are also not affected if you are already targeting legacy browsers using `@vitejs/plugin-legacy`.

- **Easy migration:** if you do intend to support browsers that fall into this category, you can use [dynamic-import-polyfill](https://github.com/GoogleChromeLabs/dynamic-import-polyfill).

    To make the polyfill work, you will also need to use a plugin with [`renderDynamicImport`](https://rollupjs.org/guide/en/#renderdynamicimport) to change the import calls to `__import__`. You can follow the installation guide in [this example](https://github.com/antfu/vite-dynamic-import-polyfill-example).

- **Required for bug fixes:** This change is required for upgrading esbuild from v0.9 to [v0.11](https://github.com/evanw/esbuild/releases/tag/v0.11.0), which includes a lot of bug fixes and improvements. And it also allows us to remove the complexity of the dynamic import polyfill.

## Security Fixes

- Dev server only listens to localhost by default now (PR [#2977](https://github.com/vitejs/vite/pull/2977))
    - Pass `--host 0.0.0.0` to change back to the previous behavior.
- Dev server only serves files under workspace root by defualt (PR [#2850](https://github.com/vitejs/vite/pull/2850), [#3321](https://github.com/vitejs/vite/pull/3321))
    - Accessing files outside of workspace root will result in a 403 response.
    - Vite will try to search up for workspace root defined in `package.json` or `pnpm-workspace.yaml`
    - To set the workspace root explicitly, see [configurations](https://vitejs.dev/config/#server-fsserve-root)

### Bug Fixes

* **dev:** rewrite importee path at html files at spa fallback ([#3239](https://github.com/vitejs/vite/issues/3239)) ([13d41d8](https://github.com/vitejs/vite/commit/13d41d864219bcc0e952f42f69adb97147e15520))
* **hmr:** respect server https options when running as middleware ([#1992](https://github.com/vitejs/vite/issues/1992)) ([24178b0](https://github.com/vitejs/vite/commit/24178b05825245b9f36b5a8e4730996184cc7e8e))
* **serve:** prevent serving unrestricted files ([#3321](https://github.com/vitejs/vite/issues/3321)) ([7231b5a](https://github.com/vitejs/vite/commit/7231b5a882a2db8dd2d9cb88a0f446edb5e2cf43))
* only provide npm package names to resolveSSRExternal ([#2717](https://github.com/vitejs/vite/issues/2717)) ([6dde32a](https://github.com/vitejs/vite/commit/6dde32a1641e91470da73315272f14e62369b65b))
* prevent serving unrestricted files (fix [#2820](https://github.com/vitejs/vite/issues/2820)) ([#2850](https://github.com/vitejs/vite/issues/2850)) ([792a6e1](https://github.com/vitejs/vite/commit/792a6e1ee8fa288ce8e641f7fa378fe8d76e52d4))
* type error by [#3151](https://github.com/vitejs/vite/issues/3151) ([#3292](https://github.com/vitejs/vite/issues/3292)) ([fd4146b](https://github.com/vitejs/vite/commit/fd4146b8624100a609ae43b2d73681d260dfe131))
* upgrade to esbuild@0.11.19 ([#3282](https://github.com/vitejs/vite/issues/3282)) ([b0dd69d](https://github.com/vitejs/vite/commit/b0dd69d305c268b2ea326ec4f344da7f7b989e69))
* warning for vite/dynamic-import-polyfill ([#3328](https://github.com/vitejs/vite/issues/3328)) ([8b80512](https://github.com/vitejs/vite/commit/8b80512c03bc053e101b1047bfd142260a15e2ac))
* **ci:** fix ci lint step ([#2988](https://github.com/vitejs/vite/issues/2988)) ([4e8ffd8](https://github.com/vitejs/vite/commit/4e8ffd8865e6303d19b5a5ea4501fc54bff4e180))
* **resolve:** normalize node_modules and bare imports, fix [#2503](https://github.com/vitejs/vite/issues/2503) ([#2848](https://github.com/vitejs/vite/issues/2848)) ([0c97412](https://github.com/vitejs/vite/commit/0c9741222532b9fa7818e0a2ce9c918bda03c6a0))
* **server:** Listen only to 127.0.0.1 by default ([#2977](https://github.com/vitejs/vite/issues/2977)) ([1e604d5](https://github.com/vitejs/vite/commit/1e604d5b60900098f201f90394445fea55642e74))
* **ssr:** resolve dynamic import vars modules ([#3177](https://github.com/vitejs/vite/issues/3177)) ([b1e7395](https://github.com/vitejs/vite/commit/b1e73951ed402a64882fb771bf433938ad171e19))


### Features

* add optimizeDeps.esbuildOptions ([#2991](https://github.com/vitejs/vite/issues/2991)) ([77a882a](https://github.com/vitejs/vite/commit/77a882a385147957b3100b3ec21de7cb212887bf))
* set publicDir to false to disable copied static assets to build dist dir ([#3152](https://github.com/vitejs/vite/issues/3152)) ([f4ab90a](https://github.com/vitejs/vite/commit/f4ab90a79f3ff56647631fa8891dc665081b45a2))
* webworker ssr target ([#3151](https://github.com/vitejs/vite/issues/3151)) ([1c59ef1](https://github.com/vitejs/vite/commit/1c59ef14dec3b60c67e70800af9d88a2255a54ae))



## [2.2.4](https://github.com/vitejs/vite/compare/v2.2.3...v2.2.4) (2021-05-03)


### Bug Fixes

* **dev:** strip utf-8 bom ([#3162](https://github.com/vitejs/vite/issues/3162)) ([#3171](https://github.com/vitejs/vite/issues/3171)) ([19a2869](https://github.com/vitejs/vite/commit/19a28692209564202ce7303a5664696cfbf3ef28))
* call `buildStart` hook in middleware mode ([#3080](https://github.com/vitejs/vite/issues/3080)) ([c374a54](https://github.com/vitejs/vite/commit/c374a5405050a6ed9013082027774fa275c2d324))
* **scan:** improve script regular matching (fixes [#2942](https://github.com/vitejs/vite/issues/2942)) ([#2961](https://github.com/vitejs/vite/issues/2961)) ([1e785d1](https://github.com/vitejs/vite/commit/1e785d1af54ae5e305dd1bef9af513f2c3a91ad3))
* dependencies are analyzed multiple times ([#3154](https://github.com/vitejs/vite/issues/3154)) ([28a67ad](https://github.com/vitejs/vite/commit/28a67ad023fd7e43e3024d1a698c49a0f7156b59))
* **emptyOutDir:** never remove .git ([#3043](https://github.com/vitejs/vite/issues/3043)) ([82dc588](https://github.com/vitejs/vite/commit/82dc5880c97daca2b7b8d55c27c30a6d810849a1))


### Features

* Allow overwrite `TerserOptions.safari10` from `UserConfig` ([#3113](https://github.com/vitejs/vite/issues/3113)) ([7cd8d78](https://github.com/vitejs/vite/commit/7cd8d7832e12e2facf7dfc163320a8798e19c6fd))



## [2.2.3](https://github.com/vitejs/vite/compare/v2.2.2...v2.2.3) (2021-04-25)


### Bug Fixes

* revert [#2541](https://github.com/vitejs/vite/issues/2541), fix [#3084](https://github.com/vitejs/vite/issues/3084) [#3101](https://github.com/vitejs/vite/issues/3101) ([#3144](https://github.com/vitejs/vite/issues/3144)) ([f4e7918](https://github.com/vitejs/vite/commit/f4e7918d0784d4f20f7f9a5575cd7e4a9cfd69fb))
* **build:** vendor chunk strategy uses static imports, fix [#2672](https://github.com/vitejs/vite/issues/2672) ([#2934](https://github.com/vitejs/vite/issues/2934)) ([949b818](https://github.com/vitejs/vite/commit/949b8184310ac073faf7f5271301ad0d9a884487))
* add .svelte to list of known js src files ([#3128](https://github.com/vitejs/vite/issues/3128)) ([0f09eaf](https://github.com/vitejs/vite/commit/0f09eaff374065a866c0f23db1217704eeb637a6))
* await bundle close in worker plugin ([#2997](https://github.com/vitejs/vite/issues/2997)) ([0e7125a](https://github.com/vitejs/vite/commit/0e7125a0480d2a50cd1d88c7a8d046af75be3a75))
* dymamic import polyfill path when base is a URL ([#3132](https://github.com/vitejs/vite/issues/3132)) ([02ba4ba](https://github.com/vitejs/vite/commit/02ba4ba32cd40f1cc3943781022c05f9df3b57e6))
* handle null/empty sources in source maps ([#3074](https://github.com/vitejs/vite/issues/3074)) ([3e9f128](https://github.com/vitejs/vite/commit/3e9f128d15f154a2e140fa65c5f617824f0c4916))
* support postcss .pcss extension ([#3130](https://github.com/vitejs/vite/issues/3130)) ([6d602a0](https://github.com/vitejs/vite/commit/6d602a0a4d2c1e77ded1344d59733eb93d4009c3))



## [2.2.2](https://github.com/vitejs/vite/compare/v2.2.1...v2.2.2) (2021-04-24)


### Bug Fixes

* **ssr:** skip resolving browser field for SSR build, fix [#3036](https://github.com/vitejs/vite/issues/3036) ([#3039](https://github.com/vitejs/vite/issues/3039)) ([61ea320](https://github.com/vitejs/vite/commit/61ea32056048e902ca69d88e1b0a2d21660dae2a))


### Features

* add marko file extensions ([#3073](https://github.com/vitejs/vite/issues/3073)) ([d34fd88](https://github.com/vitejs/vite/commit/d34fd88e46cdcbbfbc266f431f47af285b1e8702))



## [2.2.1](https://github.com/vitejs/vite/compare/v2.2.0...v2.2.1) (2021-04-19)


### Bug Fixes

* **optimizer:** depScan resolve with flatIdDeps ([#3053](https://github.com/vitejs/vite/issues/3053)) ([cb441ef](https://github.com/vitejs/vite/commit/cb441ef0f5c4a21117ea42d3fcee110a62371196))



# [2.2.0](https://github.com/vitejs/vite/compare/v2.1.5...v2.2.0) (2021-04-19)


### Bug Fixes

* require.resolve to correct sub node_modules ([#3003](https://github.com/vitejs/vite/issues/3003)) ([da11d43](https://github.com/vitejs/vite/commit/da11d43d9a246b0e721d6c33cd6a47a0675843cf))
* **optimizer:** ensure consistency with replace define ([#2929](https://github.com/vitejs/vite/issues/2929)) ([ddb7a91](https://github.com/vitejs/vite/commit/ddb7a91f0085f832d438f9523397c8a55f3d0764)), closes [#2893](https://github.com/vitejs/vite/issues/2893)
* A static and dynamically imported module is loaded twice ([#2935](https://github.com/vitejs/vite/issues/2935)) ([266fb55](https://github.com/vitejs/vite/commit/266fb55adc1e3580bab86d30fcd1dfd1d80748a9))
* avoid endless loop in resolveSSRExternal (fix [#2635](https://github.com/vitejs/vite/issues/2635)) ([#2636](https://github.com/vitejs/vite/issues/2636)) ([59871ef](https://github.com/vitejs/vite/commit/59871ef16142412d78ec79fe5ed06390d86c49e6))
* don't resolve import using browser during SSR (fix [#2995](https://github.com/vitejs/vite/issues/2995)) ([#2996](https://github.com/vitejs/vite/issues/2996)) ([fd1c9ba](https://github.com/vitejs/vite/commit/fd1c9ba11bff634c10e23a9cad2e5d639145ccf6))
* filter out empty srcset, fix [#2863](https://github.com/vitejs/vite/issues/2863) ([#2888](https://github.com/vitejs/vite/issues/2888)) ([0d4f803](https://github.com/vitejs/vite/commit/0d4f803d6edc51f31a5e20a161aa77688823b689))
* **build:** avoid import duplicate chunks, fix [#2906](https://github.com/vitejs/vite/issues/2906) ([#2940](https://github.com/vitejs/vite/issues/2940)) ([8b02abf](https://github.com/vitejs/vite/commit/8b02abf537cb731fcfe84cf8e93ba3e923e83114))
* **build:** properly handle alias key in config merge ([#2847](https://github.com/vitejs/vite/issues/2847)) ([41261c7](https://github.com/vitejs/vite/commit/41261c70e6d65ddf1dca52a6e94e5aa555539581))
* **build:** support `cssCodeSplit` for cjs format, fix [#2575](https://github.com/vitejs/vite/issues/2575) ([#2621](https://github.com/vitejs/vite/issues/2621)) ([2a89c57](https://github.com/vitejs/vite/commit/2a89c57d3fb2dedbe595c4d49c454f3d138e6414))
* **css:** properly pass options to stylus compiler, fix [#2587](https://github.com/vitejs/vite/issues/2587) ([#2860](https://github.com/vitejs/vite/issues/2860)) ([8dbebee](https://github.com/vitejs/vite/commit/8dbebeed4c1dd13e13aa7201ad6922d4d4c20368))
* **define:** ensure the normal use of NODE_ENV, fix [#2759](https://github.com/vitejs/vite/issues/2759) ([#2764](https://github.com/vitejs/vite/issues/2764)) ([fa85749](https://github.com/vitejs/vite/commit/fa8574921195dd03b539c150a2ae5f97121a0aea))
* **scan:** avoid crawling type only import ([#2810](https://github.com/vitejs/vite/issues/2810)) ([daf7838](https://github.com/vitejs/vite/commit/daf783866b744c09e2b10234ced853c6f9a84dff))
* **ssr:** fix ssrTransform catch clause error (fix [#2667](https://github.com/vitejs/vite/issues/2667)) ([#2966](https://github.com/vitejs/vite/issues/2966)) ([c9e0bcf](https://github.com/vitejs/vite/commit/c9e0bcf5653c31ffa00819083a9ce58a24e0bd17))
* **types:** clean-css types ([#2971](https://github.com/vitejs/vite/issues/2971)) ([9be7449](https://github.com/vitejs/vite/commit/9be7449544b078d572b93e7df463a0c4756a84f5))
* chunks are analysed multiple times ([#2541](https://github.com/vitejs/vite/issues/2541)) ([1451b78](https://github.com/vitejs/vite/commit/1451b78e7b1a34b89e2768315832087c686fb5aa))
* serve .js, .jsx, .ts, .tsx as application/javascript, fix [#2642](https://github.com/vitejs/vite/issues/2642) ([#2769](https://github.com/vitejs/vite/issues/2769)) ([b08e973](https://github.com/vitejs/vite/commit/b08e973da0477481970cdf6d49532bb6129aaa24))


### Features

* **createLogger:** allow custom prefix for logger ([#2019](https://github.com/vitejs/vite/issues/2019)) ([344d77e](https://github.com/vitejs/vite/commit/344d77e9735bc907b9383ad729afb0a8daa2af5f))
* add async support for vite config file ([#2758](https://github.com/vitejs/vite/issues/2758)) ([aee8b37](https://github.com/vitejs/vite/commit/aee8b3770cd081632fefb327b38ab704b97aa860))
* add inlineConfig.envFile option ([#2475](https://github.com/vitejs/vite/issues/2475)) ([81b80c6](https://github.com/vitejs/vite/commit/81b80c69d6bb00f54aae0481ea78f869db35725d))
* export manifest types ([#2901](https://github.com/vitejs/vite/issues/2901)) ([ffcb7ce](https://github.com/vitejs/vite/commit/ffcb7ce0ac4fe61fbd02da05090d48835a0dd1e4))
* parameter settings when packaging the library ([#2750](https://github.com/vitejs/vite/issues/2750)) ([f17e19a](https://github.com/vitejs/vite/commit/f17e19a80ced16401d00fef266493dd11fc69f2f))
* support cacheDir ([#2899](https://github.com/vitejs/vite/issues/2899)) ([57980d2](https://github.com/vitejs/vite/commit/57980d27ee10f1f92e532a0975d4ab39ce27d3ed))
* watch the dependencies of config file ([#3031](https://github.com/vitejs/vite/issues/3031)) ([bb419cb](https://github.com/vitejs/vite/commit/bb419cb969fec2a752dc45ab43b34351fe771f3a))
* **cli:** build watch mode, fix [#1434](https://github.com/vitejs/vite/issues/1434) ([#1449](https://github.com/vitejs/vite/issues/1449)) ([0dc6e37](https://github.com/vitejs/vite/commit/0dc6e37298e2e3efda74a1042f37bd70e3f5d3a5))
* **plugin:** plugin config hook supports return promise ([#2800](https://github.com/vitejs/vite/issues/2800)) ([5dfd0e8](https://github.com/vitejs/vite/commit/5dfd0e85978f77c8d12f7b83f25a383ae9c2f7e9))
* **plugin-api:** support async configResolved hooks (fixes [#2949](https://github.com/vitejs/vite/issues/2949)) ([#2951](https://github.com/vitejs/vite/issues/2951)) ([8b38168](https://github.com/vitejs/vite/commit/8b38168f7bc5be1d3417f3115ac723baec736ed6))
* support globbing from dependencies ([#2519](https://github.com/vitejs/vite/issues/2519)) ([7121553](https://github.com/vitejs/vite/commit/71215533ac60e8ff566dc3467feabfc2c71a01e2)), closes [#2390](https://github.com/vitejs/vite/issues/2390)



## [2.1.5](https://github.com/vitejs/vite/compare/v2.1.4...v2.1.5) (2021-03-31)


### Bug Fixes

* do not inject ?import query to external urls ([be3a4f5](https://github.com/vitejs/vite/commit/be3a4f5beb39a83bb62aef19f9e18177047618fa))
* replace __dirname and __filename in config file, fix [#2728](https://github.com/vitejs/vite/issues/2728) ([#2780](https://github.com/vitejs/vite/issues/2780)) ([eb57ac6](https://github.com/vitejs/vite/commit/eb57ac6ab1aa1256cadcea2bf8d31881023a568c))



## [2.1.4](https://github.com/vitejs/vite/compare/v2.1.3...v2.1.4) (2021-03-30)


### Bug Fixes

* **scan:** properly crawl imports in lang=ts blocks in vue/svelte files ([8f527fd](https://github.com/vitejs/vite/commit/8f527fd09c494fd23121aded0b836ff60a62835c))
* invalidate module cache on unlinked ([#2629](https://github.com/vitejs/vite/issues/2629)), fix [#2630](https://github.com/vitejs/vite/issues/2630) ([57f2a69](https://github.com/vitejs/vite/commit/57f2a698dcce47e11510bbff4c4716aac49a202b))
* reload only once on socket reconnect ([#2340](https://github.com/vitejs/vite/issues/2340)) ([d73c1fa](https://github.com/vitejs/vite/commit/d73c1fa6824397515adaf42ec29732013c8c54de))
* **client:** don't inject queries for data URLs ([#2703](https://github.com/vitejs/vite/issues/2703)), fix [#2658](https://github.com/vitejs/vite/issues/2658) ([86753d6](https://github.com/vitejs/vite/commit/86753d6e3d2be88f2f885c27fef8245c5d4b3b1b))
* **resolve:** fix resolver not following node resolve algorithm ([#2718](https://github.com/vitejs/vite/issues/2718)), fix [#2695](https://github.com/vitejs/vite/issues/2695) ([669c591](https://github.com/vitejs/vite/commit/669c591696788df844e7b26e600df86ffc70792c))
* **resolve:** improve browser filed substitutions ([#2701](https://github.com/vitejs/vite/issues/2701)), fix [#2598](https://github.com/vitejs/vite/issues/2598) ([cc213c6](https://github.com/vitejs/vite/commit/cc213c68d54db338ce0e6cf8fafe1b05a414fa6a))
* fix types errors ([#2726](https://github.com/vitejs/vite/issues/2726)) ([9716582](https://github.com/vitejs/vite/commit/97165828ecbcea867e927c62033002359d83a0db))


### Features

* **dev:** support keepNames option for optimizeDependencies config ([#2742](https://github.com/vitejs/vite/issues/2742)) ([130bf5a](https://github.com/vitejs/vite/commit/130bf5a03af2733dff9a34ef74450740d7cdb991))



## [2.1.3](https://github.com/vitejs/vite/compare/v2.1.2...v2.1.3) (2021-03-25)


### Bug Fixes

* add a timeout to the res.sep when discovering dependencies, fix [#2525](https://github.com/vitejs/vite/issues/2525) ([#2548](https://github.com/vitejs/vite/issues/2548)) ([31d10cb](https://github.com/vitejs/vite/commit/31d10cbacf292cbd1064f847673281745c977b0d))
* handle paths with special characters in injectQuery (fix [#2585](https://github.com/vitejs/vite/issues/2585)) ([#2614](https://github.com/vitejs/vite/issues/2614)) ([ed321ba](https://github.com/vitejs/vite/commit/ed321ba3f3364c0d93097d0ecfeb22aee3daa909))
* **css:** alias for background url in sass/less link error (fix [#2316](https://github.com/vitejs/vite/issues/2316)) ([#2323](https://github.com/vitejs/vite/issues/2323)) ([9499d26](https://github.com/vitejs/vite/commit/9499d26ead3214cebeab43cfb6f91adad69ae2a9))
* **dev:** remove process listeners on server close ([#2619](https://github.com/vitejs/vite/issues/2619)) ([74b360b](https://github.com/vitejs/vite/commit/74b360b6c53149c04ab5472aac7e327793a8a493))
* json should be bundled ([#2573](https://github.com/vitejs/vite/issues/2573)) ([2eb7682](https://github.com/vitejs/vite/commit/2eb76827a364f015727da521e55ec5fa54202a71)), closes [#2543](https://github.com/vitejs/vite/issues/2543)


### Features

* let `plugins` array contain falsy values ([#1649](https://github.com/vitejs/vite/issues/1649)) ([be76a30](https://github.com/vitejs/vite/commit/be76a304aacb52ac5e333552d30024be34a8a6a9))



## [2.1.2](https://github.com/vitejs/vite/compare/v2.1.1...v2.1.2) (2021-03-17)


### Bug Fixes

* update esbuild target to allow destructuring ([#2566](https://github.com/vitejs/vite/issues/2566)) ([da49782](https://github.com/vitejs/vite/commit/da497823e249aaf4d3a7da80e2211501f6159e1e))
* **manifest:** do not fail when using rollupOtions.external ([#2532](https://github.com/vitejs/vite/issues/2532)) ([e44cc11](https://github.com/vitejs/vite/commit/e44cc11bcf265d0bc4eaf5679c3b84d4b31d10ad))



## [2.1.1](https://github.com/vitejs/vite/compare/v2.1.0...v2.1.1) (2021-03-16)


### Bug Fixes

* decode path before reading sourcemap source content ([73b80d5](https://github.com/vitejs/vite/commit/73b80d5da99bbf35afe95c588d30c5b38655e225)), closes [#2524](https://github.com/vitejs/vite/issues/2524)
* **scan:** handle await replacement edge case ([cbfc3e9](https://github.com/vitejs/vite/commit/cbfc3e9dbabc4b4863a7f659b59d2e5115a81481)), closes [#2528](https://github.com/vitejs/vite/issues/2528)
* enable latest syntax when parsing for ssr ([407ce3b](https://github.com/vitejs/vite/commit/407ce3b7c5c07a51b5e20e97bc2fff2f173c74c0)), closes [#2526](https://github.com/vitejs/vite/issues/2526)



# [2.1.0](https://github.com/vitejs/vite/compare/v2.0.5...v2.1.0) (2021-03-15)


### Bug Fixes

* **json:** support importing json with ?url and ?raw queries ([fd0a0d9](https://github.com/vitejs/vite/commit/fd0a0d9bcaf0fd9098c5eb1a0c53226575fdcccb)), closes [#2455](https://github.com/vitejs/vite/issues/2455)
* **ssr:** fix mistakenly overwriting destructure variables as import bindings ([#2417](https://github.com/vitejs/vite/issues/2417)) ([24c866f](https://github.com/vitejs/vite/commit/24c866f0de4fddec45fd6aa757185d5e74d0e7f3)), closes [#2409](https://github.com/vitejs/vite/issues/2409)
* correctly handle explicit ts config file ([#2515](https://github.com/vitejs/vite/issues/2515)) ([e8f3c78](https://github.com/vitejs/vite/commit/e8f3c784b338a87a274dce44c73230d621cecb62))
* **hmr:** never invalidate an accepting importer ([#2457](https://github.com/vitejs/vite/issues/2457)) ([63bd250](https://github.com/vitejs/vite/commit/63bd2502781b87a2c04a375d9e7b770f63d8857c))
* **ssr:** handle empty sourcemaps (fix [#2391](https://github.com/vitejs/vite/issues/2391)) ([#2441](https://github.com/vitejs/vite/issues/2441)) ([103dec9](https://github.com/vitejs/vite/commit/103dec9fe80c333e1e8daec53fb08ab597f1120b))
* fix early logger definiton in resolveConfig ([#2425](https://github.com/vitejs/vite/issues/2425)) ([96ea9f4](https://github.com/vitejs/vite/commit/96ea9f4ad4522548248a951ed0cded46413b6193))
* Improve how [@fs](https://github.com/fs) urls are printed ([#2362](https://github.com/vitejs/vite/issues/2362)) ([5d4e82d](https://github.com/vitejs/vite/commit/5d4e82d90238b0d52ded1eea6359947eefc5e054))
* Improve injectQuery path handling ([#2435](https://github.com/vitejs/vite/issues/2435)) ([a5412f8](https://github.com/vitejs/vite/commit/a5412f86be80fa55cf41ac286b0a9675098c6ab8)), closes [#2422](https://github.com/vitejs/vite/issues/2422)
* keep process running when fail to load config in restarting server ([#2510](https://github.com/vitejs/vite/issues/2510)) ([b18af15](https://github.com/vitejs/vite/commit/b18af15fe83d1fcea7800fab9b550018476f740f)), closes [#2496](https://github.com/vitejs/vite/issues/2496)
* make import resolution failures easier to track down ([#2450](https://github.com/vitejs/vite/issues/2450)) ([f6ac860](https://github.com/vitejs/vite/commit/f6ac8600d944a5ce92df92c0cbef162a165c6b94))
* respect cors and proxy options in preview command ([f7d85ae](https://github.com/vitejs/vite/commit/f7d85ae4c25e7f9481261d691696554113c2d58b)), closes [#2279](https://github.com/vitejs/vite/issues/2279)
* url linked to wmr rollup-plugin-container.js found 404 ([#2368](https://github.com/vitejs/vite/issues/2368)) ([209232c](https://github.com/vitejs/vite/commit/209232cc0417f46ea73458650efa5bf6d9306e65))
* **build:** respect rollupOtions.external  at generate manifest([#2353](https://github.com/vitejs/vite/issues/2353)) ([b05a567](https://github.com/vitejs/vite/commit/b05a5676eb4c46852c0833cc5ff264533d8053ef))


### Features

* allow custom websocket server ([#2338](https://github.com/vitejs/vite/issues/2338)) ([9243cc9](https://github.com/vitejs/vite/commit/9243cc9e8ea6271eb5d548ff459eb7cc5f260598))
* bundle vite config file with esbuild instead of rollup ([#2517](https://github.com/vitejs/vite/issues/2517)) ([e034ee2](https://github.com/vitejs/vite/commit/e034ee2d9c7ef1497d1c9248ef05cdd8e0efb6ad))
* **dev:** support keepNames for dependencies ([#2376](https://github.com/vitejs/vite/issues/2376)) ([b5cd8c8](https://github.com/vitejs/vite/commit/b5cd8c8dc33e920a301ef03c097147d841d08200))



## [2.0.5](https://github.com/vitejs/vite/compare/v2.0.4...v2.0.5) (2021-03-02)


### Bug Fixes

* serving static files from root ([#2309](https://github.com/vitejs/vite/issues/2309)) ([4f942be](https://github.com/vitejs/vite/commit/4f942bef3ee2dc496a3a6854de9ea7b208829ff6))
* **scan:** handle race condition for tempDir removal ([#2299](https://github.com/vitejs/vite/issues/2299)) ([67e56e4](https://github.com/vitejs/vite/commit/67e56e48dac7875a2916845614bfb970722744a0))
* await bundle close ([#2313](https://github.com/vitejs/vite/issues/2313)) ([c988574](https://github.com/vitejs/vite/commit/c988574c3253ff133c2395c1d3884945e67641aa))



## [2.0.4](https://github.com/vitejs/vite/compare/v2.0.3...v2.0.4) (2021-02-26)


### Bug Fixes

* **build:** css tags injection priority ([#2272](https://github.com/vitejs/vite/issues/2272)) ([55ad23e](https://github.com/vitejs/vite/commit/55ad23ed44af35cb34c81881bdb12bff844c913e))
* **css:** ignore css commonjs-proxy modules ([#2160](https://github.com/vitejs/vite/issues/2160)) ([de33d32](https://github.com/vitejs/vite/commit/de33d3233708088a94217045069b4a1d9d38d1a7))
* **optimizer:** detect re-exports in dep entries ([a3abf99](https://github.com/vitejs/vite/commit/a3abf99a19e117fc71e6ea8596c6cda68a6a85ad)), closes [#2219](https://github.com/vitejs/vite/issues/2219)
* **sourcemap:** avoid cjs import interop line offset messing up sourcemap ([4ce972d](https://github.com/vitejs/vite/commit/4ce972df23dfe68543bd960ecf95091a6ffc4fdb)), closes [#2280](https://github.com/vitejs/vite/issues/2280)
* **sourcemap:** inject `sourcesContent` for .map requests ([#2283](https://github.com/vitejs/vite/issues/2283)) ([8d50b18](https://github.com/vitejs/vite/commit/8d50b18f64e3a342b2f1c4f79f306f0fb2b86f69))
* **ssr:** allow ssr module export overwrites ([#2228](https://github.com/vitejs/vite/issues/2228)) ([6fae0b7](https://github.com/vitejs/vite/commit/6fae0b7d119cf97904ae276176f8bb4374aee300))
* add source and sourcesContent to transformed SSR modules ([#2285](https://github.com/vitejs/vite/issues/2285)) ([72be67b](https://github.com/vitejs/vite/commit/72be67b70867fbbb2df63ce5484f56e6c95e2759)), closes [#2284](https://github.com/vitejs/vite/issues/2284)
* **optimizer:** fix deps aliased to cdns that are imported by optimized deps ([06d3244](https://github.com/vitejs/vite/commit/06d32447b465c045604d9f111d6fa46a98f7a7ea)), closes [#2268](https://github.com/vitejs/vite/issues/2268)
* **ssr:** handle imported binding being used as super class ([167a9c3](https://github.com/vitejs/vite/commit/167a9c31b9709f3c9627149fa5b6da378f8e09ad)), closes [#2221](https://github.com/vitejs/vite/issues/2221)
* **ssr:** handle ssrLoadModule failures in post pending ([#2253](https://github.com/vitejs/vite/issues/2253)) ([ea323cc](https://github.com/vitejs/vite/commit/ea323ccdfb5a2aef2128dd3ebd09a261d371a897)), closes [#2252](https://github.com/vitejs/vite/issues/2252)
* **ssr:** ssr transform method definition ([#2223](https://github.com/vitejs/vite/issues/2223)) ([8e0c0fa](https://github.com/vitejs/vite/commit/8e0c0fa8db5247fb1be94d5b8d3def2c4bc27923))
* decode url before serving static files ([#2201](https://github.com/vitejs/vite/issues/2201)) ([1342108](https://github.com/vitejs/vite/commit/1342108a04f7e9068301ecd04a5b391c1ed8e15d)), closes [#2195](https://github.com/vitejs/vite/issues/2195)
* determine anonymous function wrapper offset at runtime ([#2266](https://github.com/vitejs/vite/issues/2266)) ([a2ee885](https://github.com/vitejs/vite/commit/a2ee885e52547703f66367fec589f372d2b9e8a8)), closes [#2265](https://github.com/vitejs/vite/issues/2265)



## [2.0.3](https://github.com/vitejs/vite/compare/v2.0.2...v2.0.3) (2021-02-24)


### Bug Fixes

* **resolve:** compat for babel 7.13 helper resolution ([39820b9](https://github.com/vitejs/vite/commit/39820b96cec2c672e849e160b92b42c979b85285))
* **ssr:** fix ssr external check for mjs entries ([5095e04](https://github.com/vitejs/vite/commit/5095e041deaced2db8fc3c3af504367bc57bb93f)), closes [#2161](https://github.com/vitejs/vite/issues/2161)
* do not prepend base to double slash urls during dev ([#2143](https://github.com/vitejs/vite/issues/2143)) ([7a1b5c6](https://github.com/vitejs/vite/commit/7a1b5c670e2088a65f9866ecfe1b98f041980683))
* handle escape sequences in import specifiers ([#2162](https://github.com/vitejs/vite/issues/2162)) ([bbda31e](https://github.com/vitejs/vite/commit/bbda31ef695d3f9b89160435f73fcb948c3b07f1)), closes [#2083](https://github.com/vitejs/vite/issues/2083)
* should transform the img tag's srcset arrtibute and css' image-set property ([#2188](https://github.com/vitejs/vite/issues/2188)) ([0f17a74](https://github.com/vitejs/vite/commit/0f17a74c64a6664c68f23c92d572c22d1a4de059)), closes [#2177](https://github.com/vitejs/vite/issues/2177)
* treat the watcher path as literal name ([#2211](https://github.com/vitejs/vite/issues/2211)) ([58bed16](https://github.com/vitejs/vite/commit/58bed165e996cf8131ba3439ef6d8bf8d33598af)), closes [#2179](https://github.com/vitejs/vite/issues/2179)
* use proper esbuild loader for .cjs and .mjs files ([#2215](https://github.com/vitejs/vite/issues/2215)) ([a0d922e](https://github.com/vitejs/vite/commit/a0d922e7d9790f998c246f8122bc339717b6088f))
* **optimizer:** let esbuild resolve transitive deps ([0138ef3](https://github.com/vitejs/vite/commit/0138ef3eeec4bda73204ae68d5d068175335f38c)), closes [#2199](https://github.com/vitejs/vite/issues/2199)
* **scan:** avoid replacing await in import specifiers ([94e5b9a](https://github.com/vitejs/vite/commit/94e5b9a06f764d576eeeb7f35cae6bdc03b878be)), closes [#2210](https://github.com/vitejs/vite/issues/2210)



## [2.0.2](https://github.com/vitejs/vite/compare/v2.0.1...v2.0.2) (2021-02-22)


### Bug Fixes

* **build:** do not handle asset url when its url is "#" ([#2097](https://github.com/vitejs/vite/issues/2097)) ([0092a35](https://github.com/vitejs/vite/commit/0092a35632d31590409530639e33fc90274d6488)), closes [#2096](https://github.com/vitejs/vite/issues/2096)
* **cli:** fix short flags being ignored ([#2131](https://github.com/vitejs/vite/issues/2131)) ([cbb3eff](https://github.com/vitejs/vite/commit/cbb3eff96f54ed76c6ed7ca793d50914c96a67da))
* **optimizer:** do not optimize deps w/ jsx entrypoints ([1857652](https://github.com/vitejs/vite/commit/1857652f6153f1cfd7d171e75d567dd05731c711)), closes [#2107](https://github.com/vitejs/vite/issues/2107)
* **optimizer:** externalize jsx/tsx files in dependencies ([37a103f](https://github.com/vitejs/vite/commit/37a103fd2aadd42b0cda0bdfa81e0624a64b1a09))
* **optimizer:** fix .styl externalization ([87cfd9e](https://github.com/vitejs/vite/commit/87cfd9e556a0e633694805ae2497a656722d3abb)), closes [#2168](https://github.com/vitejs/vite/issues/2168)
* **resolve:** fix browser mapping fallback ([de58967](https://github.com/vitejs/vite/commit/de58967c570822e7a345bb63b81ca113ed8a8127)), closes [#2115](https://github.com/vitejs/vite/issues/2115)
* **scan:** set namespace when resolving to html ([#2174](https://github.com/vitejs/vite/issues/2174)) ([3be4fac](https://github.com/vitejs/vite/commit/3be4facebd383ea74db6274fc53848fb0149b902)), closes [#2163](https://github.com/vitejs/vite/issues/2163)
* **ssr:** avoid duplicate ssr module instantiation on shared imports ([a763ffd](https://github.com/vitejs/vite/commit/a763ffd5135fbd34bc1bdebe349e80b51884e1d4)), closes [#2060](https://github.com/vitejs/vite/issues/2060)
* **ssr:** fix ssr export * from ([8ed67cf](https://github.com/vitejs/vite/commit/8ed67cf6782bec72f8fbb4237fadfb415f86129d)), closes [#2158](https://github.com/vitejs/vite/issues/2158)
* typo ([#2149](https://github.com/vitejs/vite/issues/2149)) ([2b19e3c](https://github.com/vitejs/vite/commit/2b19e3c2d36f87e84d8bf34982a06f573a56c008))
* **ssr:** reject ssrLoadModule promises if evaluation fails ([#2079](https://github.com/vitejs/vite/issues/2079)) ([e303c4e](https://github.com/vitejs/vite/commit/e303c4e9395e6770b1f00104f28dee03e37c26ac)), closes [#2078](https://github.com/vitejs/vite/issues/2078)
* stricter html fallback check in transformRequest ([d0eac2f](https://github.com/vitejs/vite/commit/d0eac2fca9bc16caca7b9043b9c614c7044fb9fa)), closes [#2051](https://github.com/vitejs/vite/issues/2051)



## [2.0.1](https://github.com/vitejs/vite/compare/v2.0.0...v2.0.1) (2021-02-17)


### Bug Fixes

* allow custom process.env.VAR defines ([#2055](https://github.com/vitejs/vite/issues/2055)) ([7def49a](https://github.com/vitejs/vite/commit/7def49a49c83539b6a65c895c276fa83f7c89349))
* do not error on failed load for SPA html requests ([44a30d5](https://github.com/vitejs/vite/commit/44a30d5df8257bed9c59360b9751bf63151880b4)), closes [#2051](https://github.com/vitejs/vite/issues/2051)
* more inclusive config syntax error hanlding for Node 12.x ([27785f7](https://github.com/vitejs/vite/commit/27785f7fcc5b45987b5f0bf308137ddbdd9f79ea)), closes [#2050](https://github.com/vitejs/vite/issues/2050)



# [2.0.0](https://github.com/vitejs/vite/compare/v2.0.0-beta.70...v2.0.0) (2021-02-16)


### Bug Fixes

* **css/assets:** respect alias in css url() paths ([ad50060](https://github.com/vitejs/vite/commit/ad50060ed43c8d84c22a5c60592404a4e1180e2d)), closes [#2043](https://github.com/vitejs/vite/issues/2043)
* **resolve:** handle hash fragment in fs resolve ([34064c8](https://github.com/vitejs/vite/commit/34064c89aba3690667e4f5fedcbc564f6d759153))
* **scan:** fix top level await handling in script setup ([24ed098](https://github.com/vitejs/vite/commit/24ed098eedf9e90da69c328bb4d2749fec957fb3)), closes [#2044](https://github.com/vitejs/vite/issues/2044)
* **scan:** ignore virtual entries during scan ([6dc2d56](https://github.com/vitejs/vite/commit/6dc2d561cf2d8e0ea5806764314582a6f434c1d6)), closes [#2047](https://github.com/vitejs/vite/issues/2047)
* always transform applicable requests ([#2041](https://github.com/vitejs/vite/issues/2041)) ([4fd61ab](https://github.com/vitejs/vite/commit/4fd61abc05c686088b9f0ece421138311a8428c8))



# [2.0.0-beta.70](https://github.com/vitejs/vite/compare/v2.0.0-beta.69...v2.0.0-beta.70) (2021-02-15)


### Bug Fixes

* respect host option when listening ([f05ae32](https://github.com/vitejs/vite/commit/f05ae32156211d3bbf82ccfaea6d4f2fc137e609)), closes [#2032](https://github.com/vitejs/vite/issues/2032)
* **css:** resolve pre-processors from project root ([ddfcbce](https://github.com/vitejs/vite/commit/ddfcbce05753da3e525c1bb9bdf449a322e997f4)), closes [#2030](https://github.com/vitejs/vite/issues/2030)
* reject preload promise if link fails to load ([#2027](https://github.com/vitejs/vite/issues/2027)) ([f74d65d](https://github.com/vitejs/vite/commit/f74d65d41d898982839abb13787ed310555c7980)), closes [#2009](https://github.com/vitejs/vite/issues/2009)
* **ssr:** ignore base when normalizing urls for ssr ([26d409b](https://github.com/vitejs/vite/commit/26d409bbfb9bf661a19cc6619242b382f7181d05)), closes [#1995](https://github.com/vitejs/vite/issues/1995)


### Code Refactoring

* make define option perform direct replacement instead ([059070e](https://github.com/vitejs/vite/commit/059070e10aaee27a03ec5fd52e77fa04effe4c8f))


### Features

* **css:** allow async additionalData function for css pre-processors ([20f609d](https://github.com/vitejs/vite/commit/20f609dcc4f588da89b4f81eb64fb59c16fd7e07)), closes [#2002](https://github.com/vitejs/vite/issues/2002)
* allow `getJSON` option on `css.modules` ([#2025](https://github.com/vitejs/vite/issues/2025)) ([e324e36](https://github.com/vitejs/vite/commit/e324e36e04ba76e2c5203126306f1cb5ac09df8d))


### BREAKING CHANGES

* `define` option no longer calls `JSON.stringify` on
string values. This means string define values will be now treated as
raw expressions. To define a string constant, explicit quotes are now
required.



# [2.0.0-beta.69](https://github.com/vitejs/vite/compare/v2.0.0-beta.68...v2.0.0-beta.69) (2021-02-11)


### Bug Fixes

* fix out of root static file serving on windows ([4d34a73](https://github.com/vitejs/vite/commit/4d34a7362e57ba8b04e8fee0e0f2f74ce05f13eb)), closes [#1982](https://github.com/vitejs/vite/issues/1982)
* Remove negative count in stdout with 0 rows ([#1983](https://github.com/vitejs/vite/issues/1983)) ([09b13ed](https://github.com/vitejs/vite/commit/09b13eddd98810fef82858bab7997ea895ab3289)), closes [#1981](https://github.com/vitejs/vite/issues/1981)
* **ssr:** handle virtual modules during ssr ([108be94](https://github.com/vitejs/vite/commit/108be949cd814ec8fc6214c6cdfa440c0dfd7e13)), closes [#1980](https://github.com/vitejs/vite/issues/1980)
* prevent crash on malformed URI ([#1977](https://github.com/vitejs/vite/issues/1977)) ([f1b0bc9](https://github.com/vitejs/vite/commit/f1b0bc9b9bf25d206e3db93c242d5a25af0c15d6))
* user define on import.meta.env should apply during dev ([603d57e](https://github.com/vitejs/vite/commit/603d57ebc61970902ed9a275dd2e74a6c3eabe65))


### Features

* pass config env to plugin config hook ([19f3503](https://github.com/vitejs/vite/commit/19f35033045582b05c50ecad10bf2b75a0425383))



# [2.0.0-beta.68](https://github.com/vitejs/vite/compare/v2.0.0-beta.67...v2.0.0-beta.68) (2021-02-11)


### Bug Fixes

* **css/assets:** properly replace multiple css asset urls on the same line ([1d805a6](https://github.com/vitejs/vite/commit/1d805a6beb212f1812b1b13460c910c848ca3772)), closes [#1975](https://github.com/vitejs/vite/issues/1975)
* **scan:** handle lang=jsx in sfcs ([2f9549c](https://github.com/vitejs/vite/commit/2f9549c910b954b0ed4257a7a3a2e0ae6004c701)), closes [#1972](https://github.com/vitejs/vite/issues/1972)
* fix path normalization for windows paths w/ non ascii chars ([03b323d](https://github.com/vitejs/vite/commit/03b323d39cafe2baabef74e6051a9640add82590)), closes [#1384](https://github.com/vitejs/vite/issues/1384)


### Features

* support --open for `vite preview` command ([#1968](https://github.com/vitejs/vite/issues/1968)) ([446b815](https://github.com/vitejs/vite/commit/446b815d8911440f178f7b36aadc9a5a3cf46fe0))
* **resolve:** expose full resolve options via config ([0318c64](https://github.com/vitejs/vite/commit/0318c64cc3efe970a5cd3ef6624fe3625af06012)), closes [#1951](https://github.com/vitejs/vite/issues/1951)


### Performance Improvements

* ignore node_modules when globbing import.meta.glob ([8b3d0ea](https://github.com/vitejs/vite/commit/8b3d0ea41265870b9b0741bde3a31bde81078277)), closes [#1974](https://github.com/vitejs/vite/issues/1974)



# [2.0.0-beta.67](https://github.com/vitejs/vite/compare/v2.0.0-beta.66...v2.0.0-beta.67) (2021-02-09)


### Bug Fixes

* **html:** avoid duplicate preload link injection ([6e71596](https://github.com/vitejs/vite/commit/6e7159675c55f46bcc030f9c6fd35dee9a92cfca)), closes [#1957](https://github.com/vitejs/vite/issues/1957)
* **ssr:** fix ssr node require for virtual modules ([fa2d7d6](https://github.com/vitejs/vite/commit/fa2d7d66c16c2156354b6888a2f0bd4b47262ca2))
* do not open browser when restarting server ([#1952](https://github.com/vitejs/vite/issues/1952)) ([9af1517](https://github.com/vitejs/vite/commit/9af1517e47f66bb793447d998cf1a4d2fa3ef758))



# [2.0.0-beta.66](https://github.com/vitejs/vite/compare/v2.0.0-beta.65...v2.0.0-beta.66) (2021-02-08)


### Bug Fixes

* **import-analysis:** fix literal dynamic id false positive ([6a6508e](https://github.com/vitejs/vite/commit/6a6508edb9b31a4ea8bbc54b841f5227ba2b562a)), closes [#1902](https://github.com/vitejs/vite/issues/1902)
* **resolve:** avoid race condition in resolve skip check ([85f1e7b](https://github.com/vitejs/vite/commit/85f1e7bdcb9d454bd17b96ef98e2dc0cad58776b)), closes [#1937](https://github.com/vitejs/vite/issues/1937)
* **resolve:** pass down resolve skip via context ([9066f27](https://github.com/vitejs/vite/commit/9066f27c591b356107239e9cef36c1cad73864c0)), closes [#1937](https://github.com/vitejs/vite/issues/1937)
* **scan:** only scan supported entry file types ([a93e61d](https://github.com/vitejs/vite/commit/a93e61d02405728278ac905a9539450927dc7364))
* use dedicated endpoint for hmr reconnect ping ([b433607](https://github.com/vitejs/vite/commit/b433607aca0986c6e1592c3f64adb2ef30689c5e)), closes [#1904](https://github.com/vitejs/vite/issues/1904)
* **ssr:** ssr external should take scannd imports into account ([92934d4](https://github.com/vitejs/vite/commit/92934d4c18329cc51879aca5016a408b467c1fa0)), closes [#1916](https://github.com/vitejs/vite/issues/1916)
* brotli skipped is printed when build.brotliSize is false ([#1912](https://github.com/vitejs/vite/issues/1912)) ([db3c324](https://github.com/vitejs/vite/commit/db3c324134db2bf371700cc4d838a49ac6148045))



# [2.0.0-beta.65](https://github.com/vitejs/vite/compare/v2.0.0-beta.64...v2.0.0-beta.65) (2021-02-05)


### Bug Fixes

* **build:** ignore html asset urls that do not exist on disk ([02653f0](https://github.com/vitejs/vite/commit/02653f0b93cacd0f1b3464204d24c0d57f407aa0)), closes [#1885](https://github.com/vitejs/vite/issues/1885)
* better dependency non-js type file handling ([1fdc710](https://github.com/vitejs/vite/commit/1fdc710a391b968f85f6a150dc06e51e53742b02))
* **dev:** check wasClean in onclose event ([#1872](https://github.com/vitejs/vite/issues/1872)) ([5d3107a](https://github.com/vitejs/vite/commit/5d3107a4a787929810fbfaef37bf3002aa0bcc17))
* **resolve:** prioritize file over dir with same name for resolve ([c741872](https://github.com/vitejs/vite/commit/c741872e6ca975f507ec89581b742a1da19a0cb0)), closes [#1871](https://github.com/vitejs/vite/issues/1871)
* **ssr:** respect user defines for ssr ([3fad3ba](https://github.com/vitejs/vite/commit/3fad3ba861fb56edd22941db645f2d73b02bf7b1))
* do not include vite in ssr externals ([578c591](https://github.com/vitejs/vite/commit/578c591ffe7b7c1ffa68e711a7df043afe013daa)), closes [#1865](https://github.com/vitejs/vite/issues/1865)


### Code Refactoring

* **css:** use default CSS modules localsConvention settings ([fee7393](https://github.com/vitejs/vite/commit/fee739325fd4dbf7f6d842c205608e39271db513))


### Features

* **cli:** make --ssr flag value optional ([3c7b652](https://github.com/vitejs/vite/commit/3c7b652f24fdb5e67c5f56db3cea0769bcd9263b)), closes [#1877](https://github.com/vitejs/vite/issues/1877)
* **proxy:** support conditional options for proxy request ([#1888](https://github.com/vitejs/vite/issues/1888)) ([e81a118](https://github.com/vitejs/vite/commit/e81a118735045a40f0ab93c1bedef5b7d674f2f0))
* support absolute glob patterns ([159cc79](https://github.com/vitejs/vite/commit/159cc799f19482da3626f906cde45accdf780823)), closes [#1875](https://github.com/vitejs/vite/issues/1875)
* support resolving style/sass entries in css [@import](https://github.com/import) ([f90a85c](https://github.com/vitejs/vite/commit/f90a85c2ba8c9ba215fe75c49035a7e38fa81a7d)), closes [#1874](https://github.com/vitejs/vite/issues/1874)


### Performance Improvements

* improve resolve cache ([6a793d3](https://github.com/vitejs/vite/commit/6a793d319cf7adab061b056692c331a9d66fdac5))


### BREAKING CHANGES

* **css:** CSS modules now defaults to export class names as-is.
To get camelCase exports like before, explictly set
`css.modules.localsConvention` via config.



# [2.0.0-beta.64](https://github.com/vitejs/vite/compare/v2.0.0-beta.63...v2.0.0-beta.64) (2021-02-03)


### Bug Fixes

* **ssr:** do not resolve to optimized deps during ssr ([d021506](https://github.com/vitejs/vite/commit/d0215060e87c9464c97549cdbb008184796d0f8f)), closes [#1860](https://github.com/vitejs/vite/issues/1860)
* **ssr:** fix externalized cjs deps that exports compiled esmodule ([8ec2d6f](https://github.com/vitejs/vite/commit/8ec2d6f77eb04e015156769f4f004a4792077770))



# [2.0.0-beta.63](https://github.com/vitejs/vite/compare/v2.0.0-beta.62...v2.0.0-beta.63) (2021-02-03)


### Bug Fixes

* **css:** hoist external [@import](https://github.com/import) in concatenated css ([000ee62](https://github.com/vitejs/vite/commit/000ee62ef41e4964d1002ab7862303cec0419c47)), closes [#1845](https://github.com/vitejs/vite/issues/1845)
* **css:** respect sass partial import convention ([cb7b6be](https://github.com/vitejs/vite/commit/cb7b6becd0a566c58aca6cc47ae785ac2c4b4482))
* **vite:** close server and exit if stdin ends ([#1857](https://github.com/vitejs/vite/issues/1857)) ([b065ede](https://github.com/vitejs/vite/commit/b065ede3cca3bc72d3bb3e6f9cd945d1b36ccb42))
* consistently use mode for NODE_ENV in deps ([cd13ef0](https://github.com/vitejs/vite/commit/cd13ef009abd23d2676dda470638c81895034a91))
* do not shim process with actual object ([8ad7ecd](https://github.com/vitejs/vite/commit/8ad7ecd1029bdc0b47e55877db10ac630829c7e5))
* make ssr external behavior consistent between dev/build ([e089eff](https://github.com/vitejs/vite/commit/e089eff8f8108fa5463e2e42e16244f7edfd5a1e))
* only close if http server has listened ([94a8042](https://github.com/vitejs/vite/commit/94a804233682581c0f920ed5c0d42aa85ea3f163)), closes [#1855](https://github.com/vitejs/vite/issues/1855)
* **scan:** handle import glob in jsx/tsx files ([24695fe](https://github.com/vitejs/vite/commit/24695fe47727b7b4e3ac85bb389477f673c57c18))
* **ssr:** improve ssr external heuristics ([928fc33](https://github.com/vitejs/vite/commit/928fc33b6fffb3bb22c2daa4b478ead7715a2c5f)), closes [#1854](https://github.com/vitejs/vite/issues/1854)
* respect config.build.brotliSize in reporter ([1d5437d](https://github.com/vitejs/vite/commit/1d5437d56bb0974c21561c1cdf5ad1588baefea3))


### Features

* **ssr:** graduate ssr method types ([0fe2634](https://github.com/vitejs/vite/commit/0fe2634756b6311f0489613460eeadc6c8280192))



# [2.0.0-beta.62](https://github.com/vitejs/vite/compare/v2.0.0-beta.61...v2.0.0-beta.62) (2021-02-02)


### Bug Fixes

* properly cascade asset hash change ([f8e4eeb](https://github.com/vitejs/vite/commit/f8e4eebcc48ad5e98e52d12ce6595da014a43276))
* **optimizer:** fix cjs interop check on entries with identical ending ([338d17a](https://github.com/vitejs/vite/commit/338d17a197c9835fbce79919b58b8c4e094f4bb9)), closes [#1847](https://github.com/vitejs/vite/issues/1847)
* **scan:** handle tsx lang in SFCs during dep scan ([#1837](https://github.com/vitejs/vite/issues/1837)) ([be9bc3f](https://github.com/vitejs/vite/commit/be9bc3ff6eb72386876af17b61ccabae1ee249db))


### Features

* **dev:** inject env for webworker ([#1846](https://github.com/vitejs/vite/issues/1846)) ([5735692](https://github.com/vitejs/vite/commit/5735692b571ad193c04f236325df97bca7ef92bc)), closes [#1838](https://github.com/vitejs/vite/issues/1838)
* better build output + options for brotli / chunk size warning ([da1b06f](https://github.com/vitejs/vite/commit/da1b06f3771371b72c8ba68f3428c48ebf2082ad))



# [2.0.0-beta.61](https://github.com/vitejs/vite/compare/v2.0.0-beta.60...v2.0.0-beta.61) (2021-02-01)


### Bug Fixes

* **less:** fix less [@import](https://github.com/import) url rebasing ([41783fa](https://github.com/vitejs/vite/commit/41783fade0604adb98e468d4a4f8b50c9624899a)), closes [#1834](https://github.com/vitejs/vite/issues/1834)
* **manifest:** include assets referenced via CSS in manifest entries ([34894a2](https://github.com/vitejs/vite/commit/34894a2c41871a08a86fb9a1852563bc698d9c00)), closes [#1827](https://github.com/vitejs/vite/issues/1827)
* yarn pnp resolveDir ([9c6edef](https://github.com/vitejs/vite/commit/9c6edefd45634becbd51c1bf25b735770aeb752a))
* **optimizer:** fix cjs export interop for webpacked output ([4b6ebc3](https://github.com/vitejs/vite/commit/4b6ebc3f3b117cbe45aff55746dd5f588dfe1587)), closes [#1830](https://github.com/vitejs/vite/issues/1830)
* **ssr:** do not inject hmr timestamp when transforming for ssr ([#1825](https://github.com/vitejs/vite/issues/1825)) ([8ace645](https://github.com/vitejs/vite/commit/8ace6456b682a9ae7d550225817f3270524d96a3))



# [2.0.0-beta.60](https://github.com/vitejs/vite/compare/v2.0.0-beta.59...v2.0.0-beta.60) (2021-01-31)


### Bug Fixes

* **hmr:** do not update on file unlink when there are no affected modules ([#1818](https://github.com/vitejs/vite/issues/1818)) ([59fe913](https://github.com/vitejs/vite/commit/59fe913f122696ed94ac3f78655576fe7eef98d6))
* **optimizer:** entry resolving for yarn pnp ([febff7b](https://github.com/vitejs/vite/commit/febff7b837a09eec64bfe8a7cf380dd8001bba67)), closes [#1813](https://github.com/vitejs/vite/issues/1813)
* **optimizer:** fix cjs interop for packages that cannot be ([3b85296](https://github.com/vitejs/vite/commit/3b852964344e4b7e3b45b3af30f27baa89660261)), closes [#1821](https://github.com/vitejs/vite/issues/1821)
* **scan:** skip non-absolute resolved paths during scan ([f635971](https://github.com/vitejs/vite/commit/f6359716ae9f3b206cca1e63b6c1240d3bbc74fa))


### Features

* support ?url special query ([0006e89](https://github.com/vitejs/vite/commit/0006e89af419472a3c4c3f0f5328242aade2939a))



# [2.0.0-beta.59](https://github.com/vitejs/vite/compare/v2.0.0-beta.58...v2.0.0-beta.59) (2021-01-30)


### Bug Fixes

* **optimizer:** exclude should apply to deep imports ([3c22f84](https://github.com/vitejs/vite/commit/3c22f8404ecd8504448ffbe05763145887d05928))
* **optimizer:** separate dep entry proxy modules from actual modules ([8e1d3d8](https://github.com/vitejs/vite/commit/8e1d3d82f6d3ba9e48adb60a1b016c35f0aab627))



# [2.0.0-beta.58](https://github.com/vitejs/vite/compare/v2.0.0-beta.57...v2.0.0-beta.58) (2021-01-29)


### Bug Fixes

* **optimizer:** handle rollup plugin virtual ids ([a748896](https://github.com/vitejs/vite/commit/a748896b2058b0bbc2a45ef9cf84969f5681b49e)), closes [#1804](https://github.com/vitejs/vite/issues/1804)
* do not generate import specifier if not needed ([e438802](https://github.com/vitejs/vite/commit/e438802803d11acf99918690e4010b601fd7e40d))


### Features

* add ViteDevServer.transformIndexHtml method for ssr ([dbe1f4a](https://github.com/vitejs/vite/commit/dbe1f4aeadfb9f927f8cd0eec95a32aeee9c3601)), closes [#1745](https://github.com/vitejs/vite/issues/1745)
* support configuring publicDir via config ([470ceb8](https://github.com/vitejs/vite/commit/470ceb827629ab6cccf76cec3249caee08db247a)), closes [#1799](https://github.com/vitejs/vite/issues/1799)



# [2.0.0-beta.57](https://github.com/vitejs/vite/compare/v2.0.0-beta.56...v2.0.0-beta.57) (2021-01-29)


### Bug Fixes

* **optimizer:** fix entry cross imports ([a9ca3da](https://github.com/vitejs/vite/commit/a9ca3da4f1d2c584499bbbf2f16bdbf60d4f12e9)), closes [#1801](https://github.com/vitejs/vite/issues/1801)
* **optimizer:** respect ids that resolve to external urls during scan ([328b6b9](https://github.com/vitejs/vite/commit/328b6b9f7049ec9661cf42f4f43d0ea92fe9b9d0)), closes [#1798](https://github.com/vitejs/vite/issues/1798)
* still account for plugins in optimizer hash ([82dce90](https://github.com/vitejs/vite/commit/82dce90e9d5d3ad1ea516a2a66635960766afb65))
* **optimizer:** check qualified deps length after accounting for include ([6a03813](https://github.com/vitejs/vite/commit/6a0381311b173b133772efe8d5f174e9bdf989cd))
* **optimizer:** exclude ?worker and ?raw from runtime dep discovery ([d216da0](https://github.com/vitejs/vite/commit/d216da0e59bd5ab05a8eac38e99e9b6dd9461478))
* **optimizer:** properly externalize unknown types ([c3b81a8](https://github.com/vitejs/vite/commit/c3b81a8f6a3c8b2199dd42c09f5a722121891334)), closes [#1793](https://github.com/vitejs/vite/issues/1793)



# [2.0.0-beta.56](https://github.com/vitejs/vite/compare/v2.0.0-beta.55...v2.0.0-beta.56) (2021-01-29)


### Bug Fixes

* **optimizer:** handle alias to optimized entries ([81eb7a0](https://github.com/vitejs/vite/commit/81eb7a09ddb0042ec94561052e961c1ee7463bb3)), closes [#1780](https://github.com/vitejs/vite/issues/1780)


### Performance Improvements

* use esbuild service mode during pre-bundling ([b24b07c](https://github.com/vitejs/vite/commit/b24b07ce689df721d63b68e2647cc0609e58df32))



# [2.0.0-beta.55](https://github.com/vitejs/vite/compare/v2.0.0-beta.54...v2.0.0-beta.55) (2021-01-28)


### Bug Fixes

* **optimizer:** use js loader for resolved mjs files in esbuild ([0f2c2ce](https://github.com/vitejs/vite/commit/0f2c2ce4875c3ed87264c4904b047f06ee1c5d2d))



# [2.0.0-beta.54](https://github.com/vitejs/vite/compare/v2.0.0-beta.53...v2.0.0-beta.54) (2021-01-28)


### Bug Fixes

* **optimizer:** map entries to their file paths when passed as importer ([32ba8fb](https://github.com/vitejs/vite/commit/32ba8fb2b63b43dd4018dbbe5b6b431375e1c3d0))



# [2.0.0-beta.53](https://github.com/vitejs/vite/compare/v2.0.0-beta.52...v2.0.0-beta.53) (2021-01-28)


### Bug Fixes

* **css:** pure css chunk removal + manifest entry with multiple css files ([cadf38c](https://github.com/vitejs/vite/commit/cadf38cdedf5d47c63e8476b16bb74434df35878)), closes [#1776](https://github.com/vitejs/vite/issues/1776)
* **optimizer:** add separate hash for invalidating optimized deps ([216ae8e](https://github.com/vitejs/vite/commit/216ae8e95cc43dca47da4607086d2948d538fc53))
* **optimizer:** externalize json ([c3e52f2](https://github.com/vitejs/vite/commit/c3e52f2b204cdcfcab46e4b5e4992a6cefecba6a))
* **optimizer:** invalidate all modules on deps rebundle ([02053a2](https://github.com/vitejs/vite/commit/02053a2bfc2db82f277625fdf0563b257ef9c221))
* **optimizer:** use vite resolver for yarn 2 fallback ([475aae4](https://github.com/vitejs/vite/commit/475aae4ee29f9951f715d0ea98746202cfb586d4)), closes [#1778](https://github.com/vitejs/vite/issues/1778)
* fix pure css chunk removal ([d69d49d](https://github.com/vitejs/vite/commit/d69d49d4ae89b3f8ed37e1cf4345197634514546))
* **optimizer:** use all inputs for optimized entry matching ([9ecf52b](https://github.com/vitejs/vite/commit/9ecf52b27a3bdd0ce487e142fb45578eea76a3b6)), closes [#1769](https://github.com/vitejs/vite/issues/1769)
* dependency scan with esbuild when using non-HTML entrypoints ([#1772](https://github.com/vitejs/vite/issues/1772)) ([ca862a2](https://github.com/vitejs/vite/commit/ca862a2ea12853876e38100e8894fa22d9dbbc6e)), closes [#1763](https://github.com/vitejs/vite/issues/1763)
* hold missing dep requests while re-bundling ([8e28803](https://github.com/vitejs/vite/commit/8e288039a871b56803a7a5b66cc3766b6c2267db))
* more stable request hold ([be0e698](https://github.com/vitejs/vite/commit/be0e6981f764cb653d107966a755c8daa18d20c9))


### Reverts

* Revert "chore: remove unused logic" ([6b154f0](https://github.com/vitejs/vite/commit/6b154f0df3bd73cc3d3bdd91a999a7a4268e6c6b))


### BREAKING CHANGES

* **css:** the "css" property of build manifest entries is now an
array because it is possible for an entry to link to multiple generated
css files.



# [2.0.0-beta.52](https://github.com/vitejs/vite/compare/v2.0.0-beta.51...v2.0.0-beta.52) (2021-01-28)


### Bug Fixes

* **optimizer:** fix ?raw import and import with queries in pre-bundling ([2f1efa3](https://github.com/vitejs/vite/commit/2f1efa383f5f5e07618101898ce99ccbcbfc2654)), closes [#1759](https://github.com/vitejs/vite/issues/1759)
* always normalize fs prefix slashes ([99e4edd](https://github.com/vitejs/vite/commit/99e4edd468c5e27f66fd276b2ebf22d1c3424c31))
* **optimizer:** fix optimizer updates on new dep discovery ([b2110af](https://github.com/vitejs/vite/commit/b2110af04564f184bac9308926116138b9ab7aeb)), closes [#1755](https://github.com/vitejs/vite/issues/1755)



# [2.0.0-beta.51](https://github.com/vitejs/vite/compare/v2.0.0-beta.50...v2.0.0-beta.51) (2021-01-27)


### Bug Fixes

* avoid removing double slash in fileToUrl ([f6db155](https://github.com/vitejs/vite/commit/f6db155aa7a06e687d2982069db3d1619495afec))
* **build:** ensure lib mode file name is correctly inferred for scoped packages ([#1754](https://github.com/vitejs/vite/issues/1754)) ([c2e8806](https://github.com/vitejs/vite/commit/c2e88060624d73b544c31f92e5fee5d84503f6a4))
* **hmr:** fix hmr for [@fs](https://github.com/fs) urls ([b5987c1](https://github.com/vitejs/vite/commit/b5987c1f603f628ce6c075bbc83e37cafb5ea923)), closes [#1749](https://github.com/vitejs/vite/issues/1749)
* **optimizer:** attempt resolve node builtin first before externalizing ([74b55b8](https://github.com/vitejs/vite/commit/74b55b854200c3847cf13e7e036c0dc299820c64)), closes [#1746](https://github.com/vitejs/vite/issues/1746)
* allow ssr css preloads in preload-helper ([#1734](https://github.com/vitejs/vite/issues/1734)) ([1dfda16](https://github.com/vitejs/vite/commit/1dfda1618801b904b721fbd81d52a874b057ac65))
* handle vite client path with dollar signs ([#1732](https://github.com/vitejs/vite/issues/1732)) ([20bacf7](https://github.com/vitejs/vite/commit/20bacf7cacb7a0a180a9f38b18b306177a59b40d)), closes [#1423](https://github.com/vitejs/vite/issues/1423)
* scan on windows ([5f7698b](https://github.com/vitejs/vite/commit/5f7698b1f22545584e533bd0cd9abbb49c54d2b8))
* **optimizer:** entry matching for .mjs entries ([ebe71c4](https://github.com/vitejs/vite/commit/ebe71c42a481c140bbb1999f3bfa37dc15699170)), closes [#1739](https://github.com/vitejs/vite/issues/1739)
* css [@import](https://github.com/import) alias for windows ([71fcfdf](https://github.com/vitejs/vite/commit/71fcfdf219c0dd2aab6612e6b5ba89af1f63cd85))
* don't override resolver options ([#1740](https://github.com/vitejs/vite/issues/1740)) ([73196e5](https://github.com/vitejs/vite/commit/73196e517643af88a790ab5222d3e6b68dbbf987))
* resolve css [@import](https://github.com/import) relative imports without leading dot ([78eb32c](https://github.com/vitejs/vite/commit/78eb32c17998a96aff0f787cf4629b2683c6cd09)), closes [#1737](https://github.com/vitejs/vite/issues/1737)
* **optimizer:** do not perform treeshaking for pre-bundling ([6b619c4](https://github.com/vitejs/vite/commit/6b619c4be210dbab0164f42ee4b358c3ac34a896))


### Code Refactoring

* adjust optimizeDeps options ([fd5e7c0](https://github.com/vitejs/vite/commit/fd5e7c01bae67f7dfc3e631aa87a8d08429b819a))


### Features

* auto re-run dep optimization on discovery of new imports ([470b4e4](https://github.com/vitejs/vite/commit/470b4e4a8cb040ec368b3702d82f8caa145b6698))
* dep optimizer entry option ([64ba807](https://github.com/vitejs/vite/commit/64ba807f25df82e51eeacbc11d525df75cf84235))
* import resolving + url rebasing for less ([f266bb7](https://github.com/vitejs/vite/commit/f266bb7417167e752bbbbd64fe3c82dceb13794b))
* new manifest format ([51bc1ec](https://github.com/vitejs/vite/commit/51bc1ecc1c130eba7eabdbaf1e5693d1c9967628))
* proper css resolving + sass import url rebase ([477f174](https://github.com/vitejs/vite/commit/477f1749d938d5ce95df3093de7154b749fe3667))
* use esbuild to scan imports ([d0f8b12](https://github.com/vitejs/vite/commit/d0f8b1248890c1eea0b81b1d6f61a81d3dc6e44a))
* **css:** support alias in css [@imports](https://github.com/imports) ([82d87d9](https://github.com/vitejs/vite/commit/82d87d91048b90282c4cae079ee142deb2a782d5)), closes [#650](https://github.com/vitejs/vite/issues/650)


### BREAKING CHANGES

* `optimizeDeps` options have been adjusted.
    - Dependencies are now automatically scanned from source code. There
      is no longer the need to specify deep imports.
    - `optimizeDeps.include` and `optimizeDeps.exclude` now expect type `string[]`.
    - `optimizeDpes.link` and `optimizeDeps.auto` are removed.
* the build manifest format has changed. See
https://vitejs.dev/guide/backend-integration.html for more details.



# [2.0.0-beta.50](https://github.com/vitejs/vite/compare/v2.0.0-beta.49...v2.0.0-beta.50) (2021-01-26)


### Bug Fixes

* json plugin error report line regex ([#1719](https://github.com/vitejs/vite/issues/1719)) ([35e1f52](https://github.com/vitejs/vite/commit/35e1f520c99581248f8241b82a1d568518e72d3f))
* **optimizer:** externalize cross-package imported css ([0599908](https://github.com/vitejs/vite/commit/0599908dcd233dd5108069ea501a651043c28d5c)), closes [#1722](https://github.com/vitejs/vite/issues/1722)
* **optimizer:** fix entry analysis fs read on case-sensitive systems ([1a9b321](https://github.com/vitejs/vite/commit/1a9b321c744b830fe8eb3275c4150eb763d9ba76)), closes [#1720](https://github.com/vitejs/vite/issues/1720)
* **optimizer:** fix entry matching edge case ([c5fe45f](https://github.com/vitejs/vite/commit/c5fe45fdd2c90436e2ee00754aedde2a32325ac6)), closes [#1661](https://github.com/vitejs/vite/issues/1661)
* **optimizer:** handle special case where esm entry gets converted to cjs by esbuild ([32413ce](https://github.com/vitejs/vite/commit/32413cec52ab12a835d3b3ec7a1e294946d11505)), closes [#1724](https://github.com/vitejs/vite/issues/1724)
* **optimizer:** pnp compat to match relative paths ([#1714](https://github.com/vitejs/vite/issues/1714)) ([8fb74f5](https://github.com/vitejs/vite/commit/8fb74f5d0983237a95aab683d800d3546b31729f))
* **sourcemap:** empty source map chain on nullified sourcemap ([52c9416](https://github.com/vitejs/vite/commit/52c94161b5c0f5eb0ad7e676a7b30a2de4a23116)), closes [#1726](https://github.com/vitejs/vite/issues/1726)
* properly handle base + path in hmr config ([1e67d66](https://github.com/vitejs/vite/commit/1e67d669318fac320c61ea00e0e01e972183fa27))


### Features

* allow speicfying ssr entry directly via build.ssr option ([45d8bf4](https://github.com/vitejs/vite/commit/45d8bf4da234f73badcf47e574e1e3ee3dc55b6c))



# [2.0.0-beta.49](https://github.com/vitejs/vite/compare/v2.0.0-beta.48...v2.0.0-beta.49) (2021-01-25)


### Bug Fixes

* **config:** fix native esm config loading on windows ([33d3cca](https://github.com/vitejs/vite/commit/33d3cca78607e14e4d0b13e7012d065a94d184b1))
* **optimizer:** entry matching on windows ([e6120d5](https://github.com/vitejs/vite/commit/e6120d582051f3535951698df40dc9b6fc485ae0))
* **optimizer:** fix output to entry matching logic ([6c96883](https://github.com/vitejs/vite/commit/6c96883d794d3396e890907df6b799d79a027420)), closes [#1704](https://github.com/vitejs/vite/issues/1704)
* **ssr:** generate same asset url links for ssr build ([68960f7](https://github.com/vitejs/vite/commit/68960f7867be13cfdce9ea49a8cc05448dff5e60)), closes [#1711](https://github.com/vitejs/vite/issues/1711)
* **watcher:** ensure only add normalized file paths ([a19c456](https://github.com/vitejs/vite/commit/a19c4565542c2c3575ab47642f80737a3bf26f3a))
* **watcher:** watch fs specific root paths ([64d2c17](https://github.com/vitejs/vite/commit/64d2c1772a57b024373e33015740c11c172dba85))
* do not move css modules to vendor chunk ([3d55e83](https://github.com/vitejs/vite/commit/3d55e8304e0faa71aec49326901048c46d196210)), closes [#1703](https://github.com/vitejs/vite/issues/1703)
* fix hmr.path option normalization ([cbeb9ba](https://github.com/vitejs/vite/commit/cbeb9ba7c7a192e61279fb00b543b81843663bc1)), closes [#1705](https://github.com/vitejs/vite/issues/1705)



# [2.0.0-beta.48](https://github.com/vitejs/vite/compare/v2.0.0-beta.47...v2.0.0-beta.48) (2021-01-25)


### Bug Fixes

* externalize known css types during dep-prebundling ([02a0324](https://github.com/vitejs/vite/commit/02a0324a56fcc3659ace4b62f96b2a8b10979f4c)), closes [#1695](https://github.com/vitejs/vite/issues/1695)
* fallback to static middleware on unfound source maps ([2096309](https://github.com/vitejs/vite/commit/2096309bee0f4ad838cde2a9dd9114b819e462c4))
* preload marker incorrect replacement ([7f83deb](https://github.com/vitejs/vite/commit/7f83deb7fe5add6117f8f715fc3165511761d07b))
* remove preload markers in all cases ([6cd2d35](https://github.com/vitejs/vite/commit/6cd2d35d791311de953b7a832a877b1c98e2b2ed)), closes [#1694](https://github.com/vitejs/vite/issues/1694)
* resolve library entry ([3240db1](https://github.com/vitejs/vite/commit/3240db19d33f0816e3c52a5042161a94753879d9))


### Features

* resolved ids rollup compat for win32 ([#1693](https://github.com/vitejs/vite/issues/1693)) ([e2137b7](https://github.com/vitejs/vite/commit/e2137b71a5a82580b2cf45e84ead136052014ac7)), closes [#1522](https://github.com/vitejs/vite/issues/1522)



# [2.0.0-beta.47](https://github.com/vitejs/vite/compare/v2.0.0-beta.46...v2.0.0-beta.47) (2021-01-24)


### Bug Fixes

* do not apply json plugin to commonjs proxy ([a92f430](https://github.com/vitejs/vite/commit/a92f4303253c9423093bedad6b06744d66dd1d39)), closes [#1679](https://github.com/vitejs/vite/issues/1679)
* esbuild optimizer yarn 2 pnp compat ([028c3bb](https://github.com/vitejs/vite/commit/028c3bb1a6c5f56eaa7f8f122200d6262a1a8683)), closes [#1688](https://github.com/vitejs/vite/issues/1688)
* fix incorrect preload placeholder regex ([5ca43ef](https://github.com/vitejs/vite/commit/5ca43ef6e91e41f09e06d92adef79953a3df9782)), closes [#1686](https://github.com/vitejs/vite/issues/1686)
* fix server.watch option ignore overwriting defaults ([#1680](https://github.com/vitejs/vite/issues/1680)) ([33cffa3](https://github.com/vitejs/vite/commit/33cffa3910600c5adfb10f2cab07029f1ff8f35f))


### Performance Improvements

* **build:** improve performance of default vendor chunk splitting ([#1690](https://github.com/vitejs/vite/issues/1690)) ([0bed9c4](https://github.com/vitejs/vite/commit/0bed9c44b2c89ad4fb7439907959f78d946b42cd))



# [2.0.0-beta.46](https://github.com/vitejs/vite/compare/v2.0.0-beta.45...v2.0.0-beta.46) (2021-01-24)


### Bug Fixes

* **css:** fix extract concurrency issue when disabling cssCodeSplit ([4ac7e7e](https://github.com/vitejs/vite/commit/4ac7e7ec9915bd044454f90a6a3d5a9676b3615c))



# [2.0.0-beta.45](https://github.com/vitejs/vite/compare/v2.0.0-beta.44...v2.0.0-beta.45) (2021-01-24)


### Bug Fixes

* **hmr:** fix nested hmr accept calls with base ([2950c3c](https://github.com/vitejs/vite/commit/2950c3c278e20174184e44c194393b098c0d4305))
* **hmr:** preserve host when updating link CSS ([60f9782](https://github.com/vitejs/vite/commit/60f9782a8481a4ce4d4c90ca246f5de44065d314)), closes [#1665](https://github.com/vitejs/vite/issues/1665)
* **html:** ensure quote in rebased asset urls in html ([7306610](https://github.com/vitejs/vite/commit/73066105727e669fe15d926fbe07d1788a469844)), closes [#1668](https://github.com/vitejs/vite/issues/1668)
* **import-anaysis:** markPos out-of-range  for overwrite ([#1671](https://github.com/vitejs/vite/issues/1671)) ([226e984](https://github.com/vitejs/vite/commit/226e9849253677770f11f8a26e6ec205067dc902))
* **optimizer:** repsect alias in pre-bundling ([2824d06](https://github.com/vitejs/vite/commit/2824d067d5239b506f93dc9c073c21d7e059bbe3)), closes [#1674](https://github.com/vitejs/vite/issues/1674)
* **resolve:** handle paths starting with slash in entry fields ([13da32e](https://github.com/vitejs/vite/commit/13da32e9ce22b1916a1b98bba7ad83bd145563c1)), closes [#1676](https://github.com/vitejs/vite/issues/1676)
* import analysis dynamic import check ([d4909b9](https://github.com/vitejs/vite/commit/d4909b936994d4fec37dfbafd27cd24494de8d14))
* revert trailing slash handling + improve dev base usage ([01e9ac0](https://github.com/vitejs/vite/commit/01e9ac0222dcc36c075c25e3fe8f7e8881867e9c)), closes [#1664](https://github.com/vitejs/vite/issues/1664)
* support empty, relative and external base values ([00bc446](https://github.com/vitejs/vite/commit/00bc4466567bd5613d67abd1bdf46d9c9cb23a80)), closes [#1669](https://github.com/vitejs/vite/issues/1669)


### Features

* default vendor chunk splitting ([f6b58a0](https://github.com/vitejs/vite/commit/f6b58a0f535b1c26f9c1dfda74c28c685402c3c9))
* disable prompts and clearScreen on CI ([63dd1a2](https://github.com/vitejs/vite/commit/63dd1a2829ea0764c12e11f2f3510bc1c096febf)), closes [#1673](https://github.com/vitejs/vite/issues/1673)
* source map for optimized deps ([972b13e](https://github.com/vitejs/vite/commit/972b13e09f9f0d43de9b7fb1d7bd706b4a10984b))
* support stringifying json ([98c321b](https://github.com/vitejs/vite/commit/98c321b3694dc77dd66e8064f14467e909832171)), closes [#1672](https://github.com/vitejs/vite/issues/1672)
* vite preview command for previewing build output ([a198990](https://github.com/vitejs/vite/commit/a198990efe4f96c2155928ac23264437d393d54e)), closes [#1627](https://github.com/vitejs/vite/issues/1627)



# [2.0.0-beta.44](https://github.com/vitejs/vite/compare/v2.0.0-beta.43...v2.0.0-beta.44) (2021-01-23)


### Bug Fixes

* esbuild dep resolving on windows ([62e4d72](https://github.com/vitejs/vite/commit/62e4d724a8a008cb6bd6f2122753880ec3568192))



# [2.0.0-beta.43](https://github.com/vitejs/vite/compare/v2.0.0-beta.42...v2.0.0-beta.43) (2021-01-23)


### Bug Fixes

* **optimizer:** force vite resolver for esbuild pre-bundle ([4c4d629](https://github.com/vitejs/vite/commit/4c4d629c391415351c797cf9b9c54d22be6244fe))



# [2.0.0-beta.42](https://github.com/vitejs/vite/compare/v2.0.0-beta.41...v2.0.0-beta.42) (2021-01-23)


### Bug Fixes

* **optimizer:** ensure esbuild use vite-resolved entries ([bdb9b3c](https://github.com/vitejs/vite/commit/bdb9b3c5a5c8da83d8b8082e936cb3cc16eeb1e0))



# [2.0.0-beta.41](https://github.com/vitejs/vite/compare/v2.0.0-beta.40...v2.0.0-beta.41) (2021-01-23)


### Bug Fixes

* lower .mjs resolve priority ([b15e90e](https://github.com/vitejs/vite/commit/b15e90e6893582d04f9506ef56cc9d03c9c6d775)), closes [#1660](https://github.com/vitejs/vite/issues/1660)



# [2.0.0-beta.40](https://github.com/vitejs/vite/compare/v2.0.0-beta.39...v2.0.0-beta.40) (2021-01-23)


### Bug Fixes

* **optimizer:** compiled esmdoule interop ([6826624](https://github.com/vitejs/vite/commit/68266245338d4f1c27d9552d5d54eff3420af8b6)), closes [#1659](https://github.com/vitejs/vite/issues/1659)



# [2.0.0-beta.39](https://github.com/vitejs/vite/compare/v2.0.0-beta.38...v2.0.0-beta.39) (2021-01-23)


### Bug Fixes

* **optimizer:** fix es interop heuristics for entry with only export * from ([ef1a7e3](https://github.com/vitejs/vite/commit/ef1a7e33cc19bac7893bca85b6df14adeb847516))
* **ssr:** do not inject ?import query for ssr transforms ([7d26119](https://github.com/vitejs/vite/commit/7d261191e5ebf0c2fede0c6fc82137999d58cc5c)), closes [#1655](https://github.com/vitejs/vite/issues/1655)
* hmr port fallback in middlewareMode ([36a9456](https://github.com/vitejs/vite/commit/36a94560399e03cdbdbdbdb16913c05deb87ab9b))
* **ssr:** avoid resolving externals to mjs ([3955fe3](https://github.com/vitejs/vite/commit/3955fe37fe4498e6c7df122376a942d63afe6acb))
* file dir resolve should prioritize package.json ([ce2d49a](https://github.com/vitejs/vite/commit/ce2d49ab396aa7b4ed582650e569d7f2f6d3ef9f))
* **ssr:** remove import query in ssrLoadModule ([80473c1](https://github.com/vitejs/vite/commit/80473c1423209824d143df77b38f1bdb8723f47b))



# [2.0.0-beta.38](https://github.com/vitejs/vite/compare/v2.0.0-beta.37...v2.0.0-beta.38) (2021-01-23)


### Bug Fixes

* **dev:** remove comment for sourcemap reference at debug ([#1658](https://github.com/vitejs/vite/issues/1658)) ([16248c0](https://github.com/vitejs/vite/commit/16248c02844c5447eeb7c441cc4b051becef2346))
* **optimizer:** improve exports analysis ([406cbea](https://github.com/vitejs/vite/commit/406cbeaa4f52472ce356980840f1a2a824eaa497))
* **ssr:** fix ssr transform edge cases ([f22ddbd](https://github.com/vitejs/vite/commit/f22ddbdb52d4579a5756215c320a13cd674a38a0)), closes [#1646](https://github.com/vitejs/vite/issues/1646)
* exclude spa-fallback middleware in middlewareMode ([#1645](https://github.com/vitejs/vite/issues/1645)) ([843c879](https://github.com/vitejs/vite/commit/843c87915082b36f7d1ffeb81515b45d5d65aabb))


### Code Refactoring

* remove optimizeDeps.plugins ([38524f6](https://github.com/vitejs/vite/commit/38524f6c6e864f9805dd0083da1dfa8ce20fa816))


### Features

* esbuild based dep pre-bundling ([6e7f652](https://github.com/vitejs/vite/commit/6e7f652d89dde43806a2323560486c9b4b771a35))
* support `base` option during dev, deprecate `build.base` ([#1556](https://github.com/vitejs/vite/issues/1556)) ([809d4bd](https://github.com/vitejs/vite/commit/809d4bd3bf62d3bc6b35f182178922d2ab2175f1))


### BREAKING CHANGES

* `optimizeDeps.plugins` has been removed. The dep
optimizer is now using `esbuild`, and all non-js files are automatically
externalized to be processed by Vite's transform pipeline when imported.



# [2.0.0-beta.37](https://github.com/vitejs/vite/compare/v2.0.0-beta.35...v2.0.0-beta.37) (2021-01-22)


### Bug Fixes

* **css:** fix url rewriting in [@imported](https://github.com/imported) css ([52ae44f](https://github.com/vitejs/vite/commit/52ae44fe97b53ce82633268030bb46594f385860)), closes [#1629](https://github.com/vitejs/vite/issues/1629)
* **manifest:** avoid chunks with same name overwriting one another ([cf81aa3](https://github.com/vitejs/vite/commit/cf81aa399b2df1ee8441a1b8922908f4e36358d6)), closes [#1632](https://github.com/vitejs/vite/issues/1632)
* **ssr:** do not inject inlined css in ssr build ([5d77665](https://github.com/vitejs/vite/commit/5d77665def42ffafc699a0006e4527536dfd1114)), closes [#1643](https://github.com/vitejs/vite/issues/1643)
* always reload when html is edited in middleware mode ([85c89be](https://github.com/vitejs/vite/commit/85c89bea9807090d928942a72b972183ebf8483a))
* handle esm config syntax error in Node 12 ([20cf718](https://github.com/vitejs/vite/commit/20cf718ac77abfce5656ee9836f8c06ddbbc440d)), closes [#1635](https://github.com/vitejs/vite/issues/1635)
* normalize paths for cjs optimized deps on windows ([#1631](https://github.com/vitejs/vite/issues/1631)) ([b462e33](https://github.com/vitejs/vite/commit/b462e33ce3d31df49ada436324a9c32cd5c9053a))
* still resolve jsnext fields ([4e0cd73](https://github.com/vitejs/vite/commit/4e0cd7384e850e4b7f23b68e5b591bb717650b79))


### Features

* allow inline postcss config ([6bd2140](https://github.com/vitejs/vite/commit/6bd21402a9e5955433656024f5548f12b12ea2fa)), closes [#1061](https://github.com/vitejs/vite/issues/1061)
* hmr for glob import ([edd2fd9](https://github.com/vitejs/vite/commit/edd2fd9de904a194f25e18136dfe298c7bcbbd8d))



# [2.0.0-beta.36](https://github.com/vitejs/vite/compare/v2.0.0-beta.35...v2.0.0-beta.36) (2021-01-21)


### Bug Fixes

* always reload when html is edited in middleware mode ([85c89be](https://github.com/vitejs/vite/commit/85c89bea9807090d928942a72b972183ebf8483a))
* still resolve jsnext fields ([6e06108](https://github.com/vitejs/vite/commit/6e061089c62898086c07fad7154b178446a18da5))


### Features

* allow inline postcss config ([6bd2140](https://github.com/vitejs/vite/commit/6bd21402a9e5955433656024f5548f12b12ea2fa)), closes [#1061](https://github.com/vitejs/vite/issues/1061)
* hmr for glob import ([edd2fd9](https://github.com/vitejs/vite/commit/edd2fd9de904a194f25e18136dfe298c7bcbbd8d))



# [2.0.0-beta.35](https://github.com/vitejs/vite/compare/v2.0.0-beta.34...v2.0.0-beta.35) (2021-01-20)


### Bug Fixes

* allow direct inspection of static file via browser ([a3c334f](https://github.com/vitejs/vite/commit/a3c334f66dbe1e5c49c4e5d77381aa0098c4a8a9)), closes [#1612](https://github.com/vitejs/vite/issues/1612)
* also resolve for module condition ([3a3029e](https://github.com/vitejs/vite/commit/3a3029effa0b83775f02fbd9469ef104eb6adb33)), closes [#1583](https://github.com/vitejs/vite/issues/1583)
* do not apply jsxInject on ts files ([a72a59c](https://github.com/vitejs/vite/commit/a72a59c55355a2a247b84178e63ce8c7cc1d7564))
* inline async css for legacy builds ([940d483](https://github.com/vitejs/vite/commit/940d48333f6572314576da9312f36018fd70bdc8))
* manually test global regex codeframeRE index ([#1608](https://github.com/vitejs/vite/issues/1608)) ([20d6c0f](https://github.com/vitejs/vite/commit/20d6c0fae160e25ab6cb76484baf910388dccdc6))
* properly format css pre-processor errors from [@imported](https://github.com/imported) files ([ec18bde](https://github.com/vitejs/vite/commit/ec18bde7ee4045a47362240a6f5ff4997657c7ba)), closes [#1600](https://github.com/vitejs/vite/issues/1600) [#1601](https://github.com/vitejs/vite/issues/1601)
* **asset:** use stricter asset url marker and regex ([e6c8478](https://github.com/vitejs/vite/commit/e6c8478dd765e63f56e2c4559daf03f976f60b4c)), closes [#1602](https://github.com/vitejs/vite/issues/1602)
* **plugin-dynamic-import:** include assetDir in dynamic import polyfill module path ([#1610](https://github.com/vitejs/vite/issues/1610)) ([47ff0f4](https://github.com/vitejs/vite/commit/47ff0f4307da6a90db2fc43fcf0aaffdb9e36643))
* **resolve:** get pkg  from importer for relative id ([#1599](https://github.com/vitejs/vite/issues/1599)) ([c821f09](https://github.com/vitejs/vite/commit/c821f094c25a7acde87b868dced265aa6e792a57))


### Features

* **manifest:** include dynamic entries and dynamic imports ([#1609](https://github.com/vitejs/vite/issues/1609)) ([9ed4908](https://github.com/vitejs/vite/commit/9ed49085ae860fb96d51ac50845f96ceb9fa649f))
* detect and warn against imports to transitively optimized deps ([3841e70](https://github.com/vitejs/vite/commit/3841e702213efac178aa90ab01825a813d3b4819)), closes [#1543](https://github.com/vitejs/vite/issues/1543)



# [2.0.0-beta.34](https://github.com/vitejs/vite/compare/v2.0.0-beta.33...v2.0.0-beta.34) (2021-01-20)


### Bug Fixes

* default changeOrigin to true in proxy option shorthand ([b008bd5](https://github.com/vitejs/vite/commit/b008bd59674c6d46ca41108b1c9d5076374bd1b8)), closes [#1577](https://github.com/vitejs/vite/issues/1577)
* emit css only once when there are multiple outputs ([6bce108](https://github.com/vitejs/vite/commit/6bce1081991501f3779bff1a81e5dd1e63e5d38e)), closes [#1590](https://github.com/vitejs/vite/issues/1590)
* **optimizer:** handle commonjs require css ([#1568](https://github.com/vitejs/vite/issues/1568)) ([3d09b50](https://github.com/vitejs/vite/commit/3d09b50b8774cf85a8c1dee24b3e379cbd3e9eb5)), closes [#1566](https://github.com/vitejs/vite/issues/1566)
* handle legacy chunks in manifest ([123b6f6](https://github.com/vitejs/vite/commit/123b6f67f7e159d098109d5c65a74dc0d17bd495)), closes [#1551](https://github.com/vitejs/vite/issues/1551)
* use safe dynamic import rewrite ([5cb02ce](https://github.com/vitejs/vite/commit/5cb02ce0b24ff167b7da3e2de9b0237186d9e95a)), closes [#1563](https://github.com/vitejs/vite/issues/1563)
* **hmr:** fix hmr invalidation on circular deps ([ca8442c](https://github.com/vitejs/vite/commit/ca8442c19e51526e2fa75f0c4976941a2b9089e6)), closes [#1477](https://github.com/vitejs/vite/issues/1477)
* **resolve:** node resolve from virtual modules ([c6d5ed8](https://github.com/vitejs/vite/commit/c6d5ed833befafaaea14fbd2fb62a7ed8d58c409))



# [2.0.0-beta.33](https://github.com/vitejs/vite/compare/v2.0.0-beta.32...v2.0.0-beta.33) (2021-01-19)


### Bug Fixes

* fix ssr module invalidation infinite loop ([30885d1](https://github.com/vitejs/vite/commit/30885d1673a282a12e0c7471fc80236b72ebeb16)), closes [#1591](https://github.com/vitejs/vite/issues/1591)



# [2.0.0-beta.32](https://github.com/vitejs/vite/compare/v2.0.0-beta.31...v2.0.0-beta.32) (2021-01-19)


### Bug Fixes

* avoid preloading owner chunk ([61969d7](https://github.com/vitejs/vite/commit/61969d787200ab0b03179ecf2855c5b4aff3baa6))
* ssr transform check valid inMap ([bf4b3e9](https://github.com/vitejs/vite/commit/bf4b3e9b416bb0f2a8ee8bfce969d452429a8282))
* support resolving .json ext to be consistent with Node ([a1d1dde](https://github.com/vitejs/vite/commit/a1d1dde70c4626ab603ed07234fe296ef8d5a65f))


### Code Refactoring

* rename ViteDevServer.app -> ViteDevServer.middlewares ([394390a](https://github.com/vitejs/vite/commit/394390a983deccd8cbca101066db93f60577b810))


### Features

* import.meta.env.SSR ([fe7396d](https://github.com/vitejs/vite/commit/fe7396d3896d04db17f73ea265eebe0397414e65))
* ssr manifest for preload inference ([107e79e](https://github.com/vitejs/vite/commit/107e79e7b7d422f0d1dbe8b7b435636df7c6281c))
* **ssr:** isolated mode ([e954ed2](https://github.com/vitejs/vite/commit/e954ed25099d9217d30a5a4d38e5dfee5acee0fd))
* ssr sourcemap + stacktrace fix ([6cb04fa](https://github.com/vitejs/vite/commit/6cb04fa3b3a7a4ac4676a7b1c41d9d5068fae5de))


### BREAKING CHANGES

* `ViteDevServer.app` is now `ViteDevServer.middlewares`.
In addition, Vite no longer serves `index.html` in middleware mode. The
server using Vite as middleware is responsible for serving HTML with
`/@vite/client` injected.



# [2.0.0-beta.31](https://github.com/vitejs/vite/compare/v2.0.0-beta.30...v2.0.0-beta.31) (2021-01-18)


### Bug Fixes

* workaround for ts config + native esm w/ imports ([4a7d2eb](https://github.com/vitejs/vite/commit/4a7d2ebca1719d83c22d7dce5214e61f7906a772)), closes [#1560](https://github.com/vitejs/vite/issues/1560)
* **resolve:** also respect browser mapping of dependencies ([12b706d](https://github.com/vitejs/vite/commit/12b706d6ecd99c98f326deae53f9aa79cd8a81f4)), closes [#1547](https://github.com/vitejs/vite/issues/1547)



# [2.0.0-beta.30](https://github.com/vitejs/vite/compare/v2.0.0-beta.29...v2.0.0-beta.30) (2021-01-15)


### Bug Fixes

* **config:** delete cache correctly when restarting server ([#1541](https://github.com/vitejs/vite/issues/1541)) ([bd3b1bf](https://github.com/vitejs/vite/commit/bd3b1bfd83488b05a188a9d1c7093e3003721d91))
* **config:** load native esm ts config string with base64 encoding ([55b05db](https://github.com/vitejs/vite/commit/55b05dba3d157da72eaf9c445b0bb5084b9858d0)), closes [#1548](https://github.com/vitejs/vite/issues/1548)



# [2.0.0-beta.29](https://github.com/vitejs/vite/compare/v2.0.0-beta.28...v2.0.0-beta.29) (2021-01-14)


### Bug Fixes

* **optimizer:** fix empty exclude filter ([4579c38](https://github.com/vitejs/vite/commit/4579c382d4a1b0385510bb708f74305c87c4a68a))
* fix graceful shutdown on sigint ([fe7238c](https://github.com/vitejs/vite/commit/fe7238c530533d7ea7bff20ce97485669c7dfb46))
* warn failed source map load instead of erroring ([7a1261b](https://github.com/vitejs/vite/commit/7a1261b51695cbe7d41da6835c360b9bb26d189e))



# [2.0.0-beta.28](https://github.com/vitejs/vite/compare/v2.0.0-beta.27...v2.0.0-beta.28) (2021-01-14)


### Bug Fixes

* alias should work for optimized deps ([54dab71](https://github.com/vitejs/vite/commit/54dab71e41cdd9f516460d153b024d0c0cc05097))
* serve out of root static file on windows ([#1537](https://github.com/vitejs/vite/issues/1537)) ([506bf2d](https://github.com/vitejs/vite/commit/506bf2d542a27ee19a1b1b2d05aad845f4387cf6))
* **dev:** correct responce for html qurey ([#1526](https://github.com/vitejs/vite/issues/1526)) ([49d294d](https://github.com/vitejs/vite/commit/49d294d36d0f32d00a025a03017c9049d3f48ebd)), closes [#1524](https://github.com/vitejs/vite/issues/1524)
* **optimizer:** should respect rollup external during pre-bundling ([db97317](https://github.com/vitejs/vite/commit/db9731753abf36563172b02961ded54be23dd215)), closes [#1528](https://github.com/vitejs/vite/issues/1528)


### Features

* add clearScreen option ([c5c3298](https://github.com/vitejs/vite/commit/c5c32982f207055229b6bce61ce205d8d20db023))
* close server on sigint/sigterm ([4338d7d](https://github.com/vitejs/vite/commit/4338d7d6f32c8e0e67ff58f0cb8c1a9120294756)), closes [#1525](https://github.com/vitejs/vite/issues/1525)
* support specifying URL path via server.open option ([#1514](https://github.com/vitejs/vite/issues/1514)) ([25e9c44](https://github.com/vitejs/vite/commit/25e9c44992c8b868cec97dbdeddd3a4837d5bb07))
* support using vite as a middleware ([960b420](https://github.com/vitejs/vite/commit/960b42068579dddc2c216720a7f16d8d189e8225))



# [2.0.0-beta.27](https://github.com/vitejs/vite/compare/v2.0.0-beta.26...v2.0.0-beta.27) (2021-01-13)


### Bug Fixes

* transform import.meta.url in config files ([98e57de](https://github.com/vitejs/vite/commit/98e57deb9d16b23b7ae0c382cca49a9420443b47)), closes [#1511](https://github.com/vitejs/vite/issues/1511)


### Features

* **vite:** support RegExp strings as server.proxy keys ([#1510](https://github.com/vitejs/vite/issues/1510)) ([f39a2aa](https://github.com/vitejs/vite/commit/f39a2aafd35a70effc298d53b0b7539fbac79e89))
* warn unintended dependency during pre-bundling ([ae6cc27](https://github.com/vitejs/vite/commit/ae6cc27349e66945a0964635e6ad64933fe33960))



# [2.0.0-beta.26](https://github.com/vitejs/vite/compare/v2.0.0-beta.25...v2.0.0-beta.26) (2021-01-13)


### Bug Fixes

* properly externalize resolved external urls ([6cda88d](https://github.com/vitejs/vite/commit/6cda88d882ffcd5b3fdaa005296bfe1f0991925c))



# [2.0.0-beta.25](https://github.com/vitejs/vite/compare/v2.0.0-beta.24...v2.0.0-beta.25) (2021-01-12)


### Bug Fixes

* Revert "feat: allow browser new window view source ([#1496](https://github.com/vitejs/vite/issues/1496))" ([64fde38](https://github.com/vitejs/vite/commit/64fde3883e07f66fee6f6234f84ad35288a24b62)), closes [#1507](https://github.com/vitejs/vite/issues/1507)


### Features

* support aliasing to external url ([abf7844](https://github.com/vitejs/vite/commit/abf784403e1d9e36653ee4fd167c4cf341fd343f))



# [2.0.0-beta.24](https://github.com/vitejs/vite/compare/v2.0.0-beta.23...v2.0.0-beta.24) (2021-01-12)


### Bug Fixes

* **hmr:** watch file changes even when HMR is disabled ([#1504](https://github.com/vitejs/vite/issues/1504)) ([cc5fa6e](https://github.com/vitejs/vite/commit/cc5fa6efb3448e2f83b5d6d428e79803c8993657))
* always replace preload marker with value ([2d6f524](https://github.com/vitejs/vite/commit/2d6f5243e16f7debd7ba0de4bf22706df35ccf73))
* more consistent outDir formatting ([50bff79](https://github.com/vitejs/vite/commit/50bff797c536b08661791a833cfbb9179ff54422)), closes [#1497](https://github.com/vitejs/vite/issues/1497)
* show target build mode in logs ([#1498](https://github.com/vitejs/vite/issues/1498)) ([ae2e14b](https://github.com/vitejs/vite/commit/ae2e14baf1771c2ccdeece8bbc2b9bd11b279490))
* support import.meta.url in ts esm config file ([cf5f3ab](https://github.com/vitejs/vite/commit/cf5f3ab2c33aca6ab6bff8d600854f93586adcf0)), closes [#1499](https://github.com/vitejs/vite/issues/1499)


### Features

* allow browser new window view source ([#1496](https://github.com/vitejs/vite/issues/1496)) ([1629c54](https://github.com/vitejs/vite/commit/1629c546158253f155afecb55846771013f90ec0))
* require explicit option to empty outDir when it is out of root ([730d2f0](https://github.com/vitejs/vite/commit/730d2f0d8081e11c88b1151086d99b23e0c58823)), closes [#1501](https://github.com/vitejs/vite/issues/1501)



# [2.0.0-beta.23](https://github.com/vitejs/vite/compare/v2.0.0-beta.22...v2.0.0-beta.23) (2021-01-12)


### Bug Fixes

* fix ts config loading on windows ([ec370d2](https://github.com/vitejs/vite/commit/ec370d22db875cca0b2319073d9025b05e7ffc54)), closes [#1493](https://github.com/vitejs/vite/issues/1493)



# [2.0.0-beta.22](https://github.com/vitejs/vite/compare/v2.0.0-beta.21...v2.0.0-beta.22) (2021-01-11)


### Bug Fixes

* handle http proxy error ([4ca20f2](https://github.com/vitejs/vite/commit/4ca20f2e16c1bba0dc330c7e5879ca322b2ab21c)), closes [#1485](https://github.com/vitejs/vite/issues/1485)
* optimizer hash should take inline mode into account ([0aed0e8](https://github.com/vitejs/vite/commit/0aed0e89f84aff26cfdf57879925a76fa696331d)), closes [#1490](https://github.com/vitejs/vite/issues/1490)
* support resolved Ids that start with null bytes ([7074414](https://github.com/vitejs/vite/commit/70744143cd09863412a59aad14de888067bd8531)), closes [#1471](https://github.com/vitejs/vite/issues/1471)
* **config:** support native esm config on windows + support TS config in native esm projects ([803f6da](https://github.com/vitejs/vite/commit/803f6da2ad04846c3ae2622e15b5a18f0691204e)), closes [#1487](https://github.com/vitejs/vite/issues/1487)


### Features

* **resolve:** support subpath patterns + production/development conditinals in exports field ([62cbd53](https://github.com/vitejs/vite/commit/62cbd53f25411ddfc7cfd5446c2f487a260da191))
* **server:** add strict-port option ([#1453](https://github.com/vitejs/vite/issues/1453)) ([0501084](https://github.com/vitejs/vite/commit/05010846cb266f540039f13e280b486c97803f03))



# [2.0.0-beta.21](https://github.com/vitejs/vite/compare/v2.0.0-beta.20...v2.0.0-beta.21) (2021-01-11)


### Bug Fixes

* properly remove dynamic import args for full dynamic imports ([d9c3fdb](https://github.com/vitejs/vite/commit/d9c3fdb4073d49d427d825007154e873d8aa3d9a))



# [2.0.0-beta.20](https://github.com/vitejs/vite/compare/v2.0.0-beta.19...v2.0.0-beta.20) (2021-01-11)


### Bug Fixes

* **optimizer:** exclude should not be resolve ([#1469](https://github.com/vitejs/vite/issues/1469)) ([f8c34ee](https://github.com/vitejs/vite/commit/f8c34eeb89e327f484293f3156119ba6d14f6aee))
* **resolve:** heuristics for browser vs. module field ([1865e6e](https://github.com/vitejs/vite/commit/1865e6ee4c3e07c0f4a199c1ba7e1c1c4f68862f)), closes [#1467](https://github.com/vitejs/vite/issues/1467)


### Features

* allow passing options to rollup commonjs plugin via build.commonjsOptions ([6ed8e28](https://github.com/vitejs/vite/commit/6ed8e286f149f9474e0fc624110de5f787551d62)), closes [#1460](https://github.com/vitejs/vite/issues/1460)
* async chunk loading optimizations ([e6f7fba](https://github.com/vitejs/vite/commit/e6f7fbad75c1b406b9a95060c5d2a42d3a8994a8))



# [2.0.0-beta.19](https://github.com/vitejs/vite/compare/v2.0.0-beta.18...v2.0.0-beta.19) (2021-01-10)


### Bug Fixes

* transform json in deep import ([#1459](https://github.com/vitejs/vite/issues/1459)) ([cf8342b](https://github.com/vitejs/vite/commit/cf8342bef45bebb05d020d4f220b12d2bf526256)), closes [#1458](https://github.com/vitejs/vite/issues/1458)



# [2.0.0-beta.18](https://github.com/vitejs/vite/compare/v2.0.0-beta.17...v2.0.0-beta.18) (2021-01-10)


### Bug Fixes

* fix dynamic import with parent relative paths ([bbfe06c](https://github.com/vitejs/vite/commit/bbfe06ce1af8f89490032e609377c6516f7da773)), closes [#1461](https://github.com/vitejs/vite/issues/1461)
* **optimizer:** properly externalize css/asset imports in optimized deps ([5d180db](https://github.com/vitejs/vite/commit/5d180db4bd19e26de20bb816d594226b4d492804)), closes [#1443](https://github.com/vitejs/vite/issues/1443)


### Features

* **optimizer:** support specifying plugins for the optimizer ([1ea0168](https://github.com/vitejs/vite/commit/1ea016823975f3d0e37bf7b65614eded213e0869))



# [2.0.0-beta.17](https://github.com/vitejs/vite/compare/v2.0.0-beta.16...v2.0.0-beta.17) (2021-01-10)


### Code Refactoring

* support glob import under `import.meta.glob` ([23d0f2b](https://github.com/vitejs/vite/commit/23d0f2b85d8eb8677e30456342000cabed8e684e))


### BREAKING CHANGES

* Glob import syntax has changed. The feature is now
exposed under `import.meta.glob` (lazy, exposes dynamic import functions)
and `import.meta.globEager` (eager, exposes already imported modules).



# [2.0.0-beta.16](https://github.com/vitejs/vite/compare/v2.0.0-beta.15...v2.0.0-beta.16) (2021-01-09)


### Bug Fixes

* inject css link when cssCodeSplit is disabled ([51a02ff](https://github.com/vitejs/vite/commit/51a02ff902c3afa4dff76b43f75b9221768cd7f8)), closes [#1141](https://github.com/vitejs/vite/issues/1141)
* set NODE_ENV for build ([d7ceabe](https://github.com/vitejs/vite/commit/d7ceabe92efe1c523ee05a6941e3f5042733b2bf)), closes [#1445](https://github.com/vitejs/vite/issues/1445) [#1452](https://github.com/vitejs/vite/issues/1452)


### Features

* allow tag injection after body open (body-prepend) ([#1435](https://github.com/vitejs/vite/issues/1435)) ([432487e](https://github.com/vitejs/vite/commit/432487e24cb8688c86502e3b4e284e25c81b7dd8))



# [2.0.0-beta.15](https://github.com/vitejs/vite/compare/v2.0.0-beta.14...v2.0.0-beta.15) (2021-01-09)


### Bug Fixes

* **hmr:** ensure all modules are fetched as import ([98bc767](https://github.com/vitejs/vite/commit/98bc7675a0f515ec6a908c6f18b2947a4a117836))



# [2.0.0-beta.14](https://github.com/vitejs/vite/compare/v2.0.0-beta.13...v2.0.0-beta.14) (2021-01-09)


### Features

* support ../ paths in glob import ([7f399e1](https://github.com/vitejs/vite/commit/7f399e1a628240fdcd866cddc45c5522b07fd7f6))



# [2.0.0-beta.13](https://github.com/vitejs/vite/compare/v2.0.0-beta.12...v2.0.0-beta.13) (2021-01-09)


### Bug Fixes

* always rebase path against root ([d704b7c](https://github.com/vitejs/vite/commit/d704b7c55fcbf347b5277a1d92dee4cc9583bab5)), closes [#1413](https://github.com/vitejs/vite/issues/1413)
* handle potential imports that has no correspodning chunks ([d47e10c](https://github.com/vitejs/vite/commit/d47e10c77d642b0446cb6ea1d5fd5a33346e9391))
* raw fetch requests should not be transformed ([0356c3c](https://github.com/vitejs/vite/commit/0356c3c5193a5aeb8586e5588c8c873df7a1a427)), closes [#1433](https://github.com/vitejs/vite/issues/1433)
* skip cjs rewrite for export * declarations ([cca015b](https://github.com/vitejs/vite/commit/cca015b1c46fff41e047a92430937f31df5e6dfb)), closes [#1439](https://github.com/vitejs/vite/issues/1439)
* **cli:** fix help for --root ([#1429](https://github.com/vitejs/vite/issues/1429)) ([7a55c5b](https://github.com/vitejs/vite/commit/7a55c5be36a6d04a5a1e434147f4208c4a64c492))
* **dev:** decode url before `sirv` resolve ([#1432](https://github.com/vitejs/vite/issues/1432)) ([7cc3cf1](https://github.com/vitejs/vite/commit/7cc3cf1044594297320ed62e1b38b27883f3f6c0)), closes [#1426](https://github.com/vitejs/vite/issues/1426)


### Features

* allow user define to overwrite default process.env. defines ([351ad4e](https://github.com/vitejs/vite/commit/351ad4ee56d46eb8837b6a90af19ef953e3fe28b))
* build support for data uri import ([4fd0b86](https://github.com/vitejs/vite/commit/4fd0b8615ef5ecff704ed44cadece613368cf18b))
* support import "glob:./*" ([8d8e2cc](https://github.com/vitejs/vite/commit/8d8e2cc9ea0e1cc8f620c0a9d143294c1efb37b0))



# [2.0.0-beta.12](https://github.com/vitejs/vite/compare/v2.0.0-beta.11...v2.0.0-beta.12) (2021-01-07)


### Bug Fixes

* **plugin-legacy:** avoid esbuild transform on legacy chunks ([7734105](https://github.com/vitejs/vite/commit/7734105093c6dabf64da6bfc11486aa9ac62efea))



# [2.0.0-beta.11](https://github.com/vitejs/vite/compare/v2.0.0-beta.10...v2.0.0-beta.11) (2021-01-07)


### Bug Fixes

* preserve html comments during dev ([b295400](https://github.com/vitejs/vite/commit/b2954009f48da0a0d3202eee802e51eb7a1fb6c5)), closes [#1420](https://github.com/vitejs/vite/issues/1420)
* **resolve:** respect exports env key order ([b58c860](https://github.com/vitejs/vite/commit/b58c860f1771deecb78e126dfe8b6f663bd5e7c9)), closes [#1418](https://github.com/vitejs/vite/issues/1418)
* avoid excessive quote in css public urls ([1437129](https://github.com/vitejs/vite/commit/1437129541b36c0453fcecb1f1d44b574cc3326f)), closes [#1399](https://github.com/vitejs/vite/issues/1399)
* do not rewrite dynamic import if format is not native es ([eb35bd5](https://github.com/vitejs/vite/commit/eb35bd546333f4edea94607d05581b887b2ce9b6))
* esbuild transform should filter id with and wihtout query ([4cda5be](https://github.com/vitejs/vite/commit/4cda5beb9f62c766dc8a8ab5d7b17704355348fc))
* fix cache invalidation for non-optimized deps with cross imports ([11c407a](https://github.com/vitejs/vite/commit/11c407a085e9facd810914a5d4256946c11a1ca9)), closes [#1401](https://github.com/vitejs/vite/issues/1401)
* html transform should not render boolean attr with false value ([a59ffef](https://github.com/vitejs/vite/commit/a59ffefe1087a45cc4c13ab9e15e1d43ccac114a))
* remove vue from optimize ignore list ([9eab790](https://github.com/vitejs/vite/commit/9eab79088079e95fb32f458a4bf573af7618bec6)), closes [#1408](https://github.com/vitejs/vite/issues/1408)
* support serving extension-less files in /public ([a7bca9c](https://github.com/vitejs/vite/commit/a7bca9c324db280ad3fa8255a36dee838a29255b)), closes [#1364](https://github.com/vitejs/vite/issues/1364)
* **build:** inline quotes css url to base64 ([#1412](https://github.com/vitejs/vite/issues/1412)) ([9b5b352](https://github.com/vitejs/vite/commit/9b5b3526de3288fc5d0e0a40fd80378db24674a1)), closes [#1409](https://github.com/vitejs/vite/issues/1409) [#1413](https://github.com/vitejs/vite/issues/1413)


### Code Refactoring

* pass `configFile` via inline config instead of extra arg in most ([24b3b5a](https://github.com/vitejs/vite/commit/24b3b5a4e4402543d45bd8e3e4ff9ff26c09d7cb))


### Features

* support specifying mode in user config ([396bbf8](https://github.com/vitejs/vite/commit/396bbf8c869b23360a39bc4d99b760e25645c84b)), closes [#1380](https://github.com/vitejs/vite/issues/1380)
* **plugin-legacy:** @vitejs/plugin-legacy ([8c34870](https://github.com/vitejs/vite/commit/8c34870040f8c2f4be7d00245a3683f9e64d894e))
* **proxy:** add rewrite support for ws ([#1407](https://github.com/vitejs/vite/issues/1407)) ([fa3bc34](https://github.com/vitejs/vite/commit/fa3bc34e23e757d57ca42e66c41dc8e712ae5547))
* also expose correspodning chunk in build html transform ([b2f4836](https://github.com/vitejs/vite/commit/b2f4836ea83d7ba86c2ef3a082773d5045f2e7d9))
* expose loadConfigFromFile API ([#1403](https://github.com/vitejs/vite/issues/1403)) ([9582171](https://github.com/vitejs/vite/commit/958217177c3173b7e5dec7f29048a2e83168649b))


### BREAKING CHANGES

* the following JavaScript APIs now expect `configFile`
as a property of the config object passed in instead of an argument:

    - `createServer`
    - `build`
    - `resolveConfig`



# [2.0.0-beta.10](https://github.com/vitejs/vite/compare/v2.0.0-beta.9...v2.0.0-beta.10) (2021-01-06)


### Bug Fixes

* **alias:** normalize alias behavior when there is ending slash ([c4739a3](https://github.com/vitejs/vite/commit/c4739a3f6d341db220cc5732857cf194c7cecc0d)), closes [#1363](https://github.com/vitejs/vite/issues/1363)
* **build:** Pass `allowNodeBuiltins` to rollup instead of empty array (Fixes [#1392](https://github.com/vitejs/vite/issues/1392)) ([#1393](https://github.com/vitejs/vite/issues/1393)) ([f209ad9](https://github.com/vitejs/vite/commit/f209ad9c858235ea317db6beb3bf2ab5ec26c153))
* avoid replacing process.env member expression ([c8f4bb9](https://github.com/vitejs/vite/commit/c8f4bb92337c8882f238ea395f169af96a59d2ae)), closes [#930](https://github.com/vitejs/vite/issues/930)



# [2.0.0-beta.9](https://github.com/vitejs/vite/compare/v2.0.0-beta.8...v2.0.0-beta.9) (2021-01-06)


### Bug Fixes

* properly handle browser: false resolving ([da09320](https://github.com/vitejs/vite/commit/da09320e3671dbf08a5f8c4a78bd273f75fdcd7d)), closes [#1386](https://github.com/vitejs/vite/issues/1386)
* properly handle ts worker source ([eea1224](https://github.com/vitejs/vite/commit/eea122434740a60d353df54cb4dc108e29d4ef87)), closes [#1385](https://github.com/vitejs/vite/issues/1385)


### Features

* **env:** also expose VITE_ variables from actual env ([956cd2c](https://github.com/vitejs/vite/commit/956cd2c76e69ba046f51a36af8e44ae9fb3a67ab))



# [2.0.0-beta.8](https://github.com/vitejs/vite/compare/v2.0.0-beta.7...v2.0.0-beta.8) (2021-01-05)


### Bug Fixes

* **resolve:** handle exports field w/ mapped directory ([724aa8a](https://github.com/vitejs/vite/commit/724aa8a5fcb0ccaea283b3bf065d29ebf2cdf5a2))


### Features

* **build:** default build target to 'modules' with dynamic import polyfill ([756e90f](https://github.com/vitejs/vite/commit/756e90ff9b7d0b838ac3a2d7a20c36c801f72d8c))
* allow boolean attr values in html transform tag descriptors ([#1381](https://github.com/vitejs/vite/issues/1381)) ([0fad96e](https://github.com/vitejs/vite/commit/0fad96e5cbff48efd3a13bb27580de894e1ec728))



# [2.0.0-beta.7](https://github.com/vitejs/vite/compare/v2.0.0-beta.6...v2.0.0-beta.7) (2021-01-05)


### Code Refactoring

* update client type usage ([245303c](https://github.com/vitejs/vite/commit/245303ca35ff2a40eca49e102b4f82cb1210f597))


### BREAKING CHANGES

* client types are now exposed under `vite/client.d.ts`.
It can now be included via the following `tsconfig.json`:

    ```ts
    {
      "compilerOptions": {
        "types": ["vite/client"]
      }
    }
    ```



# [2.0.0-beta.6](https://github.com/vitejs/vite/compare/v2.0.0-beta.5...v2.0.0-beta.6) (2021-01-05)


### Bug Fixes

* **css:** ensure options for .styl ([b3237ff](https://github.com/vitejs/vite/commit/b3237fff697b4b8b0e10adc9e0041f64c33fbc2d)), closes [#1351](https://github.com/vitejs/vite/issues/1351)
* **error-handling:** avoid serilaizing unnecessary error properties when seinding to client ([61aec65](https://github.com/vitejs/vite/commit/61aec651b470d5b97f2340a1b692b82cfe0c8ba5)), closes [#1373](https://github.com/vitejs/vite/issues/1373)
* **optimizer:** optimizer should not be affected by config rollup options ([ba08310](https://github.com/vitejs/vite/commit/ba08310b9e82668670af8a95e889e7cb68388e84)), closes [#1372](https://github.com/vitejs/vite/issues/1372)
* support aliases in html references ([68eac64](https://github.com/vitejs/vite/commit/68eac643f907fb4d57bd25925a342692441b1d97)), closes [#1363](https://github.com/vitejs/vite/issues/1363)
* **optimizer:** resolve linked dep from relative root ([#1375](https://github.com/vitejs/vite/issues/1375)) ([034bbcd](https://github.com/vitejs/vite/commit/034bbcd1738426d89e6c942f27dd1ccc8ede3990))


### Code Refactoring

* remove the need for specifying `transformInclude` ([99522d0](https://github.com/vitejs/vite/commit/99522d0edf06da4b8519c209f5f928cdf2951105))


### Features

* exclude vue from optimization ([1046fe0](https://github.com/vitejs/vite/commit/1046fe008b3288633bf8b38efdc2401a5ad2bf47))
* improve import analysis fail warning ([2b39fce](https://github.com/vitejs/vite/commit/2b39fce9450dc0d8bc99b06a6d757f4e48193001)), closes [#1368](https://github.com/vitejs/vite/issues/1368)


### BREAKING CHANGES

* `transformInclude` option has been removed and is no
longer necessary. This allows full dynamic imports to custom file types
to automatically qualify for the transform pipeline.

    - All requests that accept `*/*` AND is not declared an asset type
    will now qualify for the transform pipeline.

    - To exclude an asset type from being transformed when requested
    directly, declare it as asset via `config.assetsInclude`.



# [2.0.0-beta.5](https://github.com/vitejs/vite/compare/v2.0.0-beta.4...v2.0.0-beta.5) (2021-01-05)


### Bug Fixes

* only append dep version query for known types ([42cd8b2](https://github.com/vitejs/vite/commit/42cd8b217de6afb53163eef69e96514c75de4443))
* **css:** fix css comment removal ([7b9dee0](https://github.com/vitejs/vite/commit/7b9dee020785022acaa8e6989dcb2cc7ec03c3f2)), closes [#1359](https://github.com/vitejs/vite/issues/1359)
* **css:** inline css in all non-entry split chunks ([e90ff76](https://github.com/vitejs/vite/commit/e90ff76d1c6d5ad1d079c953ba4fbfc84be73185)), closes [#1356](https://github.com/vitejs/vite/issues/1356)
* do not bundle resolve for yarn 2 compat ([3524e96](https://github.com/vitejs/vite/commit/3524e96da0de59e5dddf2210dc78e2a1de3f07e0)), closes [#1353](https://github.com/vitejs/vite/issues/1353)
* do not error on unresolved commonjs externals ([60a4708](https://github.com/vitejs/vite/commit/60a470880034fcd7e54c15b4cf92f738b973a3df)), closes [#1339](https://github.com/vitejs/vite/issues/1339)
* only allow built-ins as externals if building for ssr ([804c9a3](https://github.com/vitejs/vite/commit/804c9a30e673386c419a0582d0da11f805c285c4))
* run mutiple output builds sequantially ([ab80522](https://github.com/vitejs/vite/commit/ab805228e55bd79275b6ac67b0408419a8ab5c70))


### Features

* **types:** separate client type shims from main types ([0cddbbc](https://github.com/vitejs/vite/commit/0cddbbc4bfc8e85329ba710117b9aec1d67d318d))
* default clean-css level to 1 + expose options ([ef100d0](https://github.com/vitejs/vite/commit/ef100d09cbd1c6745108afc2877396fe69b08bdd)), closes [#936](https://github.com/vitejs/vite/issues/936)
* support plugin.apply ([d914b54](https://github.com/vitejs/vite/commit/d914b542450cd7b4bbeb057a0fee8f79efd2bb9d))



# [2.0.0-beta.4](https://github.com/vitejs/vite/compare/v2.0.0-beta.3...v2.0.0-beta.4) (2021-01-04)


### Bug Fixes

* stop service in build esbuild plugin as well ([1a90b4e](https://github.com/vitejs/vite/commit/1a90b4e50250c4011a058e9e121b7b80caff888e))
* **build:** rollup import resolving message ([#1336](https://github.com/vitejs/vite/issues/1336)) [skip ci] ([87d55f4](https://github.com/vitejs/vite/commit/87d55f43e90edb36c2f0d49d71ffadd20f82e97a))
* **resolve:** always prioritize browser field ([409988f](https://github.com/vitejs/vite/commit/409988fbbb5d854ccbbae0dd81f757eb42e24c40))
* [@fs](https://github.com/fs) paths resolving for win32 ([#1317](https://github.com/vitejs/vite/issues/1317)) ([0a94c88](https://github.com/vitejs/vite/commit/0a94c88238f265a14c116c2f1306d3be74b182e6))
* do not error on css deep imports ([25adf1e](https://github.com/vitejs/vite/commit/25adf1eefaf6817f9443365f5ee3fcf0d63ffd6f))
* ensure consistent module entry urls by removing import query ([2b82e84](https://github.com/vitejs/vite/commit/2b82e84a272db2a4269d742dd7b9a8a1ad8351dd)), closes [#1321](https://github.com/vitejs/vite/issues/1321)
* load source map from sourceMappingURL comment ([#1327](https://github.com/vitejs/vite/issues/1327)) ([1f89b0e](https://github.com/vitejs/vite/commit/1f89b0e704d4315246836d2cd7faf3cdcdf89dd9))
* sourcemap path mangled by browser ([#1326](https://github.com/vitejs/vite/issues/1326)) ([1da12ba](https://github.com/vitejs/vite/commit/1da12baf00ab8e7c3366f9c0e088c09cce903934)), closes [#1323](https://github.com/vitejs/vite/issues/1323)
* **dev:** display localetime correctly ([#1310](https://github.com/vitejs/vite/issues/1310)) ([06663a7](https://github.com/vitejs/vite/commit/06663a7e7825bedd61593d299f00110f6ac40916))


### Features

* esbuild.(include|exclude|jsxInject) ([b5b1496](https://github.com/vitejs/vite/commit/b5b14962b53d8dcbae850b9eb6abf2ca5820b3db))
* **wasm:** use `instantiateStreaming` when available ([#1330](https://github.com/vitejs/vite/issues/1330)) ([2286f62](https://github.com/vitejs/vite/commit/2286f629ab6d96fb0b90c9825582962bf8f0f2a5)), closes [#1143](https://github.com/vitejs/vite/issues/1143)
* export normalizePath helper ([#1313](https://github.com/vitejs/vite/issues/1313)) ([37d1a5d](https://github.com/vitejs/vite/commit/37d1a5de019cfd5db397f5c8e0365222950c1dff))



# [2.0.0-beta.3](https://github.com/vitejs/vite/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2021-01-03)


### Bug Fixes

* **build:** fix import-fresh shim ([b57d74c](https://github.com/vitejs/vite/commit/b57d74c2b72498aee251ed7ed45ff046a98d5499)), closes [#1306](https://github.com/vitejs/vite/issues/1306)
* decode incoming URL ([f52db58](https://github.com/vitejs/vite/commit/f52db5898dfb1eecb4b3427a73ffd7ecd2ac15d6)), closes [#1308](https://github.com/vitejs/vite/issues/1308)
* keep `this` defined in `configureServer` hook ([#1304](https://github.com/vitejs/vite/issues/1304)) ([b665b92](https://github.com/vitejs/vite/commit/b665b92323521475a568f8c5204a83c0e80a6b75))
* **resolve:** prioritize module + avoid mutating path when ([6ce6d5c](https://github.com/vitejs/vite/commit/6ce6d5c2908c20b8308725a5f91f5a618aa09d8a)), closes [#1299](https://github.com/vitejs/vite/issues/1299)


### Features

* dedupe option ([7858e62](https://github.com/vitejs/vite/commit/7858e629273269ca2aedf9891d560521a4bd0c8d)), closes [#1302](https://github.com/vitejs/vite/issues/1302)
* export `resolvePackageData` and `resolvePackageEntry` helpers ([#1307](https://github.com/vitejs/vite/issues/1307)) ([38b9613](https://github.com/vitejs/vite/commit/38b9613832d1af569ca5aba4226895f0bd7897a0))
* expose `loadEnv` in public api ([#1300](https://github.com/vitejs/vite/issues/1300)) ([9d0a8e7](https://github.com/vitejs/vite/commit/9d0a8e74d1553c8c9108caeaf0c22cd938a502c7))



# [2.0.0-beta.2](https://github.com/vitejs/vite/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2021-01-02)


### Bug Fixes

* do not attempt to transform html requests ([a7a5c5b](https://github.com/vitejs/vite/commit/a7a5c5bbd9d26e46fb3a175c80bd898cdfce5572))
* fix spa fallback on paths ending with slash ([60fe476](https://github.com/vitejs/vite/commit/60fe476638930702fb94f906afcf6d1dc4dfab7b))
* **resolve:** prioritize browser field ([dfef3de](https://github.com/vitejs/vite/commit/dfef3de9a5875c238d9a795a461e47634db9809f)), closes [#1154](https://github.com/vitejs/vite/issues/1154)
* **resolve:** resolve inline package ([e27fe30](https://github.com/vitejs/vite/commit/e27fe30e7920d22f4ad786e5bfb14415d73cc2cc)), closes [#1291](https://github.com/vitejs/vite/issues/1291)
* dynamic load postcss plugin ([#1292](https://github.com/vitejs/vite/issues/1292)) ([00c7370](https://github.com/vitejs/vite/commit/00c737024a72ab3e2c5c17f74b2bf28c5b0d158f)), closes [#1287](https://github.com/vitejs/vite/issues/1287)
* fix transform result check for empty result ([2adfa8b](https://github.com/vitejs/vite/commit/2adfa8b1bdc01297a030f8cb3066df7f7a753d3c)), closes [#1278](https://github.com/vitejs/vite/issues/1278)


### Code Refactoring

* **hmr:** pass context object to `handleHotUpdate` plugin hook ([b314771](https://github.com/vitejs/vite/commit/b3147710e96a8f88ab81b2e45dbf7e7174ad976c))


### Reverts

* Revert "types: worker types" (#1295) ([806ef96](https://github.com/vitejs/vite/commit/806ef9697069db581eaa2c1721db5d3e08707a7d)), closes [#1295](https://github.com/vitejs/vite/issues/1295)


### BREAKING CHANGES

* **hmr:** `handleHotUpdate` plugin hook now receives a single
`HmrContext` argument instead of multiple args.



# [2.0.0-beta.1](https://github.com/vitejs/vite/compare/v2.0.0-alpha.5...v2.0.0-beta.1) (2021-01-02)


### Bug Fixes

* --open and --filter arguments ([#1259](https://github.com/vitejs/vite/issues/1259)) ([0c0bc4a](https://github.com/vitejs/vite/commit/0c0bc4a33c99da22be96214af872344f930732d4))
* handle hmr errors ([ff2b3ce](https://github.com/vitejs/vite/commit/ff2b3cef01750c3cb33d39dc726317cbd832568b))
* overlay z-index ([6b3278e](https://github.com/vitejs/vite/commit/6b3278eff8702c45bd8dbace35baca337fb89682))
* **css:** respect minify option for chunk css ([6a287a1](https://github.com/vitejs/vite/commit/6a287a176dd4be6e290d3be0490e39b92916a0d0))


### Features

* also call buildEnd on container close ([94a8def](https://github.com/vitejs/vite/commit/94a8def3bcc673c00ff56f9d19b9933c6426c605))
* provide default typing for supported file types ([a9c7eac](https://github.com/vitejs/vite/commit/a9c7eaca1cf8ab0f590bb605da49fd4daa766244))
* support resolveId returning arbitrary value ([b782af4](https://github.com/vitejs/vite/commit/b782af44cc968cc4f18ef0722302991406fa82de))



# [2.0.0-alpha.5](https://github.com/vitejs/vite/compare/v2.0.0-alpha.4...v2.0.0-alpha.5) (2020-12-30)


### Bug Fixes

* **css:** properly prevent css from being tree-shaken ([7f08835](https://github.com/vitejs/vite/commit/7f088352894f3fcc06e6936917de4bb70b5763dc))



# [2.0.0-alpha.4](https://github.com/vitejs/vite/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2020-12-30)


### Bug Fixes

* **css:** fix cssCodeSplit: false ([9a02203](https://github.com/vitejs/vite/commit/9a0220304bd6bc655078b7705b95f3cfd1059e36))
* disable cssCodeSplit by default in lib mode ([e64509a](https://github.com/vitejs/vite/commit/e64509a680fdb01ff25393f9c65f34ac87eb799a))
* fix terser worker thread when vite is linked ([a28419b](https://github.com/vitejs/vite/commit/a28419bafc649192cdb6eca3f6014e3b823d1c0a))
* inline assets in lib mode ([c976d10](https://github.com/vitejs/vite/commit/c976d10ac1e40f0c59bcb02c1016ed6f39563ca0))



# [2.0.0-alpha.3](https://github.com/vitejs/vite/compare/v2.0.0-alpha.2...v2.0.0-alpha.3) (2020-12-30)



# [2.0.0-alpha.2](https://github.com/vitejs/vite/compare/v2.0.0-alpha.1...v2.0.0-alpha.2) (2020-12-29)


### Bug Fixes

* **plugin-vue:** avoid throwing on never requested file ([48a24c1](https://github.com/vitejs/vite/commit/48a24c1fa1f64e89ca853635580911859ef5881b))



# [2.0.0-alpha.1](https://github.com/vitejs/vite/compare/v1.0.0-rc.13...v2.0.0-alpha.1) (2020-12-29)

- [x] new universal plugin format
- [x] framework agnostic core
- [x] smaller and faster install
- [x] improved JS API
- [x] improved alias and resolving
- [x] improved page reload performance (strong caching of npm deps)
- [x] error overlay
- [x] better vue perf (single request in most cases)
- [x] multi entry mode
- [x] lib mode
