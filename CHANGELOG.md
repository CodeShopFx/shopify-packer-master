## [2.4.4](https://github.com/hayes0724/shopify-packer/compare/v2.4.3...v2.4.4) (2022-03-09)


### Bug Fixes

* Build exit non zero on failure ([#153](https://github.com/hayes0724/shopify-packer/issues/153)) ([8b595f9](https://github.com/hayes0724/shopify-packer/commit/8b595f9cdb1a3e05082478f2f72adcaf0aaf6e1b))
* Environment vars: allow them to work ([#184](https://github.com/hayes0724/shopify-packer/issues/184)) ([009f704](https://github.com/hayes0724/shopify-packer/commit/009f70439b7888a50f70d6b392d7d065f570820b))
* handle {file}.css.liquid assets correctly ([0f8e0ce](https://github.com/hayes0724/shopify-packer/commit/0f8e0ce078066f9eb5454d56957c9e02078ffb2a)), closes [#144](https://github.com/hayes0724/shopify-packer/issues/144)
* ssl:make timing bug ([#180](https://github.com/hayes0724/shopify-packer/issues/180)) ([bec0e9e](https://github.com/hayes0724/shopify-packer/commit/bec0e9ed0361703a682113ca5300b22ed0cebed6))

## [2.4.3](https://github.com/hayes0724/shopify-packer/compare/v2.4.2...v2.4.3) (2022-02-20)


### Bug Fixes

* **deps:** update project dependencies  ([#171](https://github.com/hayes0724/shopify-packer/issues/171)) ([0a16958](https://github.com/hayes0724/shopify-packer/commit/0a1695870b2cf0061f2a498f1b0dab2bd52b746c))

## [2.4.2](https://github.com/hayes0724/shopify-packer/compare/v2.4.1...v2.4.2) (2022-02-20)


### Bug Fixes

* **deps:** pin copy webpack plugin to major version ([3a00d53](https://github.com/hayes0724/shopify-packer/commit/3a00d536ce9ef4595e374c91f65fbb56abd2bba4))

## [2.4.1](https://github.com/hayes0724/shopify-packer/compare/v2.4.0...v2.4.1) (2022-02-20)


### Bug Fixes

* **deps:** bump postcss from 8.2.10 to 8.2.13 ([2f75aac](https://github.com/hayes0724/shopify-packer/commit/2f75aacc9fe95479a59b2a6b163a7782a485ecd2))

# [2.4.0](https://github.com/hayes0724/shopify-packer/compare/v2.3.1...v2.4.0) (2022-02-19)


### Bug Fixes

* themekit updated to v1.1.9 to support themekit access app ([cbee44b](https://github.com/hayes0724/shopify-packer/commit/cbee44bab4d08b16cf528a58d3d48c4be227d462)), closes [#124](https://github.com/hayes0724/shopify-packer/issues/124)


### Features

* webpack dotenv support ([fd00413](https://github.com/hayes0724/shopify-packer/commit/fd0041317e84b788408209a806daa8c3460480bb))

## [2.3.2](https://github.com/hayes0724/shopify-packer/compare/v2.3.1...v2.3.2) (2022-02-19)


### Bug Fixes

* themekit updated to v1.1.9 to support themekit access app ([cbee44b](https://github.com/hayes0724/shopify-packer/commit/cbee44bab4d08b16cf528a58d3d48c4be227d462)), closes [#124](https://github.com/hayes0724/shopify-packer/issues/124)

## [2.3.1](https://github.com/hayes0724/shopify-packer/compare/v2.3.0...v2.3.1) (2022-02-19)


### Bug Fixes

* chalk v5 changed to v4.1.2 to support require ([04a8260](https://github.com/hayes0724/shopify-packer/commit/04a826016943ca52d70e8aed20a25bf7121ba362)), closes [#147](https://github.com/hayes0724/shopify-packer/issues/147)

# [2.3.0](https://github.com/hayes0724/shopify-packer/compare/v2.2.0...v2.3.0) (2022-02-19)


### Bug Fixes

* removed fibers from sass loader for node 16+ support ([7f2fc11](https://github.com/hayes0724/shopify-packer/commit/7f2fc114a4744eab7a365e87672956e5452744e8)), closes [#145](https://github.com/hayes0724/shopify-packer/issues/145)


### Features

* check for ssl and make ca + cert ([abb68e2](https://github.com/hayes0724/shopify-packer/commit/abb68e270ec5628fa624a95d1b8325a2c4ca9d47))

# [2.2.0](https://github.com/hayes0724/shopify-packer/compare/v2.1.11...v2.2.0) (2021-04-30)


### Features

* check for ssl and make ca + cert ([#89](https://github.com/hayes0724/shopify-packer/issues/89)) ([a773db6](https://github.com/hayes0724/shopify-packer/commit/a773db60d159f268643ce7468af4eca3370ee7d7))

## [2.1.11](https://github.com/hayes0724/shopify-packer/compare/v2.1.10...v2.1.11) (2021-04-28)


### Bug Fixes

* liquid styles file path incorrect ([e9163a1](https://github.com/hayes0724/shopify-packer/commit/e9163a1d996859095723b195deaa22b0c3f29092))

## [2.1.10](https://github.com/hayes0724/shopify-packer/compare/v2.1.9...v2.1.10) (2021-04-27)


### Bug Fixes

* exit if publish live prompt is no ([cd68128](https://github.com/hayes0724/shopify-packer/commit/cd68128ce4bb24efb832a882611b2b2f313d32a5))

## [2.1.9](https://github.com/hayes0724/shopify-packer/compare/v2.1.8...v2.1.9) (2021-04-27)


### Bug Fixes

* remove all assets before each build ([03a4683](https://github.com/hayes0724/shopify-packer/commit/03a46839ed20aa427c7c418ebfe77d72e155494b))

## [2.1.8](https://github.com/hayes0724/shopify-packer/compare/v2.1.7...v2.1.8) (2021-04-27)


### Bug Fixes

* continue if published theme prompt sets allowLive ([a1faf44](https://github.com/hayes0724/shopify-packer/commit/a1faf44fc76cc9764bb57e59685e4f03374652b6))

## [2.1.7](https://github.com/hayes0724/shopify-packer/compare/v2.1.6...v2.1.7) (2021-04-27)


### Bug Fixes

* --allowLive flag for start, deploy, and watch ([5c38cf0](https://github.com/hayes0724/shopify-packer/commit/5c38cf05949fb3542f99beb8d1bb0db3ad8d2a48)), closes [#75](https://github.com/hayes0724/shopify-packer/issues/75)

## [2.1.6](https://github.com/hayes0724/shopify-packer/compare/v2.1.5...v2.1.6) (2021-04-27)


### Bug Fixes

* escape css filenames in html webpack plugin ([7348095](https://github.com/hayes0724/shopify-packer/commit/73480959b44f956d4af4ab25782b19a1f694e8da))

## [2.1.5](https://github.com/hayes0724/shopify-packer/compare/2.1.4...2.1.5) (2021-04-13)


### :bug: Bug Fixes

* catch unhandled exception on deploy in progress ([2414e65](https://github.com/hayes0724/shopify-packer/commit/2414e654024f1859a8131695002508f0e833e0e9))


### :hammer: Code Refactoring

* changed shared bundles default to false ([9918a5f](https://github.com/hayes0724/shopify-packer/commit/9918a5fb91c02c941b84c425bee80eafa7448dc9))



## [2.1.4](https://github.com/hayes0724/shopify-packer/compare/2.1.3...2.1.4) (2021-04-07)


### :heavy_check_mark: Tests

* refactored init command for better testing ([09efd3d](https://github.com/hayes0724/shopify-packer/commit/09efd3da7cf2ae4abb85b41364ea84e73ef9f4fa))


### :sparkles: Features

* postcss updated to v8 ([d266c25](https://github.com/hayes0724/shopify-packer/commit/d266c256c0dc07e7b77bb3343f167b3e6324354d))


### :wrench: Continuous Integration

* dockerfiles for testing packer in node 10, 12, 14, and 15. ([f308dc4](https://github.com/hayes0724/shopify-packer/commit/f308dc47706b672b4aa3c8458938b966ec2c649a))
* removed node 15.x from matrix ([445f1e2](https://github.com/hayes0724/shopify-packer/commit/445f1e2264c953832570205cbf49e6808df9dc3f))



## [2.1.3](https://github.com/hayes0724/shopify-packer/compare/2.1.2...2.1.3) (2021-04-01)


### :sparkles: Features

* clean dist folder when dev server is first launched ([24b3d8c](https://github.com/hayes0724/shopify-packer/commit/24b3d8c83ab1989c91cae494b2bd395c7865e584))



## [2.1.2](https://github.com/hayes0724/shopify-packer/compare/2.1.1...2.1.2) (2021-03-31)


### :bug: Bug Fixes

* remove html encoding from html webpack filenames ([26ef677](https://github.com/hayes0724/shopify-packer/commit/26ef6770afc2cef22b1fc3ffcdae26137751ba15))


### chore

* removed html-webpack-tags-plugin from dev dependency ([ce8b83a](https://github.com/hayes0724/shopify-packer/commit/ce8b83a4e8791cadbd65088090da346e3fd0bdd7))



## [2.1.1](https://github.com/hayes0724/shopify-packer/compare/2.1.0...2.1.1) (2021-03-31)


### :hammer: Code Refactoring

* replaced liquid loader with copy plugin ([13160b3](https://github.com/hayes0724/shopify-packer/commit/13160b32d4cab733f5607470e1b2c47daf2583d7))



# [2.1.0](https://github.com/hayes0724/shopify-packer/compare/2.0.13...2.1.0) (2021-03-31)


### :rocket: Performance Improvements

* optimized assets handling, copying and cleaning ([a75ae4b](https://github.com/hayes0724/shopify-packer/commit/a75ae4badc81ae9c4b52f40c020fc6942d9ddc68))



## [2.0.13](https://github.com/hayes0724/shopify-packer/compare/2.0.12...2.0.13) (2021-03-30)


### :bug: Bug Fixes

* changed devtool to eval-source-map for hmr ([c8ebe24](https://github.com/hayes0724/shopify-packer/commit/c8ebe240efcb02dd701da76272f891e5bad16355))



## [2.0.12](https://github.com/hayes0724/shopify-packer/compare/2.0.11...2.0.12) (2021-03-29)


### :bug: Bug Fixes

* asset generator filename ([11dda8b](https://github.com/hayes0724/shopify-packer/commit/11dda8b9a5c0cfe0c82c125523238905d79ada04))



## [2.0.11](https://github.com/hayes0724/shopify-packer/compare/2.0.10...2.0.11) (2021-03-29)


### :bug: Bug Fixes

* updated development asset handling ([e6ccf99](https://github.com/hayes0724/shopify-packer/commit/e6ccf99005e5f7ec05c074c1e35c56b66c5daa5a))



## [2.0.10](https://github.com/hayes0724/shopify-packer/compare/2.0.9...2.0.10) (2021-03-28)


### :art: Styles

* removed unused variable and ran prettier ([a14dc67](https://github.com/hayes0724/shopify-packer/commit/a14dc67a536637a099f82a1e1548c7f6b05c2219))


### :bug: Bug Fixes

* dev server not detecting liquid file changes ([9301ce5](https://github.com/hayes0724/shopify-packer/commit/9301ce5b9c578c60ca3a2c08888ffd0622f25d51))


### :wrench: Continuous Integration

* Tests now run on macos and windows and linting added ([64166ef](https://github.com/hayes0724/shopify-packer/commit/64166efbda66c3c31768bf10b27fa8c997d41755))



## [2.0.8](https://github.com/hayes0724/shopify-packer/compare/2.0.7...2.0.8) (2021-03-28)


### :bug: Bug Fixes

* webpack 5 hot middleware ([5fcbe08](https://github.com/hayes0724/shopify-packer/commit/5fcbe0840fcaf430614d6046c5067c2e9c221a57))



## [2.0.7](https://github.com/hayes0724/shopify-packer/compare/2.0.6...2.0.7) (2021-03-26)


### :bug: Bug Fixes

* ssl check if folder exists before creating keys ([79b4223](https://github.com/hayes0724/shopify-packer/commit/79b4223ccbfa0ce33ebfa187b307828c2e07559b))


### :sparkles: Features

* dev settings asset loader for fonts and images ([467d081](https://github.com/hayes0724/shopify-packer/commit/467d0810d27857d0d0da7402d6a0ae6151121074))
* start/watch not detecting file changes ([3fa73a9](https://github.com/hayes0724/shopify-packer/commit/3fa73a9c8fade826301e5c5228cc8eb414154f86))



## [2.0.6](https://github.com/hayes0724/shopify-packer/compare/2.0.5...2.0.6) (2021-03-25)


### :bug: Bug Fixes

* init theme extraction issue ([0dae9b9](https://github.com/hayes0724/shopify-packer/commit/0dae9b9e782c94d971a1dcc9f4d99345b5a8f774))



## [2.0.5](https://github.com/hayes0724/shopify-packer/compare/2.0.4...2.0.5) (2021-03-25)


### :art: Styles

* eslint and prettier issues fixed ([7c81a7c](https://github.com/hayes0724/shopify-packer/commit/7c81a7c9e41371f2378fce4e1812cf7b6504872f))


### :bug: Bug Fixes

* replace all special charcters in script names ([ce3da66](https://github.com/hayes0724/shopify-packer/commit/ce3da66879da16e88636e437f95eeea90528e48c))


### :sparkles: Features

* added default cache group ([0810d9d](https://github.com/hayes0724/shopify-packer/commit/0810d9dee94943809b7af17dd8e7e8c258607b1b))
* added shared bundles configuration ([c082182](https://github.com/hayes0724/shopify-packer/commit/c08218264a5ac930eb98f8597838b02247f0b25b))


### chore

* eslint and prettier config for packer development ([797493a](https://github.com/hayes0724/shopify-packer/commit/797493a8ed8ecdafcdedaf10e83931e96ad21b39))



## [2.0.4](https://github.com/hayes0724/shopify-packer/compare/2.0.3...2.0.4) (2021-03-24)


### :bug: Bug Fixes

* packer init hanging during extraction ([ab7d65d](https://github.com/hayes0724/shopify-packer/commit/ab7d65dbc68a2522aecc5d6c663b84a38662972c)), closes [#67](https://github.com/hayes0724/shopify-packer/issues/67)



## [2.0.3](https://github.com/hayes0724/shopify-packer/compare/2.0.2...2.0.3) (2021-03-23)


### :bug: Bug Fixes

* added missing dependency eslint ([b424792](https://github.com/hayes0724/shopify-packer/commit/b4247924e3e35a639c7e827aa865d832b5b2e1a5))
* typo in config name for eslint and stylelint ([69310ac](https://github.com/hayes0724/shopify-packer/commit/69310ac9a2413c6cd37beb225113fcca50ee236e))


### :hammer: Code Refactoring

* added dart-sass and fibers to sass-loader ([536ab5a](https://github.com/hayes0724/shopify-packer/commit/536ab5ad43c988ff496e44d0a3009ab306abfead))
* changed stylelint and eslint messages ([8164129](https://github.com/hayes0724/shopify-packer/commit/816412987bb76997810b5c4f3615367a67e4ed2c))


### :wrench: Build System

* removed babel-preset-shopify and stylelint-selector-bem-pattern ([4d9c492](https://github.com/hayes0724/shopify-packer/commit/4d9c4923e1c375228b78b6787f81d77b7fb0f2e7))
* removed stylelint-config-shopify ([10f5918](https://github.com/hayes0724/shopify-packer/commit/10f5918a2856d07037fe75b0f1efa11965676cbf))
* removed stylelint-prettier ([c7dedff](https://github.com/hayes0724/shopify-packer/commit/c7dedffa718fa889a18ea7188cd9c82eb25a6708))



## [2.0.2](https://github.com/hayes0724/shopify-packer/compare/4.0.1...2.0.2) (2021-03-23)


### :wrench: Build System

* removed @babel/plugin-transform-async-to-generator ([68f27de](https://github.com/hayes0724/shopify-packer/commit/68f27de0ca9f3c53c94e45b98cf2468b8cd9c8e0))
* removed @babel/preset-env ([dcedb37](https://github.com/hayes0724/shopify-packer/commit/dcedb3740c8547b2aa510bc414ca3c3e725fca27))
* removed @babel/register ([ee853c1](https://github.com/hayes0724/shopify-packer/commit/ee853c14e5b4c857c32d5654d604d9cd01d7c916))
* removed @namics/stylelint-bem ([44d0678](https://github.com/hayes0724/shopify-packer/commit/44d0678ad4dd6e861bcfbfa7c050f6ad99a5a489))
* removed @shopify/babel-preset ([a22d493](https://github.com/hayes0724/shopify-packer/commit/a22d493e509ba25301026f6a38a9bc49585b4084))
* removed @shopify/theme-lint since it's not longer updated ([d46ef33](https://github.com/hayes0724/shopify-packer/commit/d46ef33fa6056a474ed4d2582b30fc60d8466617))
* removed autoprefixer ([c7d63ee](https://github.com/hayes0724/shopify-packer/commit/c7d63eeedb1ca96621c31fcb913fb1f3d736b665))
* removed cross-env ([d4b38c4](https://github.com/hayes0724/shopify-packer/commit/d4b38c4cf92fb4f2c4849b7d48aa6b8dda3674e7))
* removed cssnano ([94420ca](https://github.com/hayes0724/shopify-packer/commit/94420cadef974a10b671ea2fdeaf7ce7488c1e6d))
* removed edit-json-file ([8a2d722](https://github.com/hayes0724/shopify-packer/commit/8a2d72248ee95b996364ee57c74bb7bdbf16f405))
* removed eslint-plugin-shopify ([3106ded](https://github.com/hayes0724/shopify-packer/commit/3106dede9207f6e85562cf8af6b5fb25ebde3db2))
* removed expose-loader ([c4cdb68](https://github.com/hayes0724/shopify-packer/commit/c4cdb681ef59da16279c2078b5a7ae2b11c38ef0))
* removed extract-text-webpack-plugin ([e1b88fe](https://github.com/hayes0724/shopify-packer/commit/e1b88fe2cbbc5742b930fad44c2545c8b2fc21a8))
* removed glob ([b62d24a](https://github.com/hayes0724/shopify-packer/commit/b62d24af763b966b79380a3a82d68c58cd4c1d98))
* removed lodash ([25c4ec5](https://github.com/hayes0724/shopify-packer/commit/25c4ec556e3c4796cb53f7b4eb9637cf6c3131f9))
* removed postcss-preset-env ([67a5c40](https://github.com/hayes0724/shopify-packer/commit/67a5c40f49f7b37789d05d6233f16eade95f0e0c))
* removed raw-loader ([ab11469](https://github.com/hayes0724/shopify-packer/commit/ab11469cbc225c52c786d6f86216f957de6ff83d))
* removed read-yaml ([0719688](https://github.com/hayes0724/shopify-packer/commit/0719688d136941a881dcddadd717d0e9f1021e6d))
* removed stylelint-config-prettier ([881ebfa](https://github.com/hayes0724/shopify-packer/commit/881ebfa52508fc4f7bfc9415a703bd4f8143d5cb))
* removed stylelint-config-recommended-scss ([cb60324](https://github.com/hayes0724/shopify-packer/commit/cb60324a91b02633cc15765f597c7be7d2dbdcfb))



## [2.0.1](https://github.com/hayes0724/shopify-packer/compare/1.4.0...2.0.1) (2021-03-23)


### :bug: Bug Fixes

* --nodelete flag not checked before deploying ([b2aabe5](https://github.com/hayes0724/shopify-packer/commit/b2aabe5c45e0cc10219c38315be33bcd73fa772d)), closes [#60](https://github.com/hayes0724/shopify-packer/issues/60)


* Create FUNDING.yml ([0604700](https://github.com/hayes0724/shopify-packer/commit/0604700b21f0c6a53af51715aafc29578c6890ed))



# [2.0.0](https://github.com/hayes0724/shopify-packer/compare/1.3.8...2.0.0) (2021-03-22)


### :sparkles: Features

* webpack upgraded to v5 ([b5d68fd](https://github.com/hayes0724/shopify-packer/commit/b5d68fd6a301d1750fbfd920a55e09dc7e3aeac7))


### :wrench: Build System

* bumped fs-extra to ^9.1.0 ([873228f](https://github.com/hayes0724/shopify-packer/commit/873228fe4b1458686cc04e10a2e94604d5477835))



# [1.4.0](https://github.com/hayes0724/shopify-packer/compare/1.3.8...1.4.0) (2021-03-21)


### :sparkles: Features

* replace node sass with dart sass ([fff7650](https://github.com/hayes0724/shopify-packer/commit/fff7650fc377f4a3c7bcb9b8eb48fb9626ae1fd4))



## [1.3.8](https://github.com/hayes0724/shopify-packer/compare/1.3.7...1.3.8) (2021-03-21)


### :sparkles: Features

* Create self-signed ssl cert from Packer CLI ([98701e6](https://github.com/hayes0724/shopify-packer/commit/98701e637889794b688a7ee4a1b9193e55d10379))



## [1.3.7](https://github.com/hayes0724/shopify-packer/compare/1.3.6...1.3.7) (2021-03-20)


### :memo: Documentation

* Updated SSL docs ([097f30c](https://github.com/hayes0724/shopify-packer/commit/097f30c3963da932f98982a1e46b388987cbbf23))


### :sparkles: Features

* Check for certificate extensions instead of fixed filename ([71789a1](https://github.com/hayes0724/shopify-packer/commit/71789a13e46b4d0934dfeca8201efbb811e47255))


### chore

* Changed homepage in package.json ([44536a8](https://github.com/hayes0724/shopify-packer/commit/44536a836e1866203c67eb33ffdd810b1f1d15c9))


* Add docs for existing projects ([a44f9c6](https://github.com/hayes0724/shopify-packer/commit/a44f9c632d3f9f40ccc4fec543fba9c0db3f2e8d))



## [1.3.6](https://github.com/hayes0724/shopify-packer/compare/1.3.5...1.3.6) (2021-03-20)


### :memo: Documentation

* changed docusaurus.config.js ([4755789](https://github.com/hayes0724/shopify-packer/commit/4755789c12cd7359fcd832c54a01882d6172ea40))
* changed docusaurus.config.js again ([d6ba1ed](https://github.com/hayes0724/shopify-packer/commit/d6ba1edc116b63d0ceade781c7bcfab0c19c1e4d))
* documentation website ([b5ab20f](https://github.com/hayes0724/shopify-packer/commit/b5ab20fbdc758a42812ad03d216e9c39e87a9014))
* fixed broken links ([f6f4a9e](https://github.com/hayes0724/shopify-packer/commit/f6f4a9e15d81c4561f36310b0045d7bfce23b7d1))


### :sparkles: Features

* Added reload delay setting ([3ef3b40](https://github.com/hayes0724/shopify-packer/commit/3ef3b408c6e24ba244f811443d4a5e97c256b904))



## [1.3.5](https://github.com/hayes0724/shopify-packer/compare/1.3.4...1.3.5) (2021-01-13)


### :bug: Bug Fixes

* show error instead of exiting on deploy exception ([6d0107f](https://github.com/hayes0724/shopify-packer/commit/6d0107fc4b264db8de694610012e6e4e18780b63))


### :wrench: Build System

* **deps:** bump axios from 0.19.2 to 0.21.1 ([7334d5d](https://github.com/hayes0724/shopify-packer/commit/7334d5d403666574f8dec3bc8cc26ff29be60646))



## [1.3.4](https://github.com/hayes0724/shopify-packer/compare/1.3.2...1.3.4) (2021-01-13)


### :bug: Bug Fixes

* init command extract releases that use v in tag name ([76d4188](https://github.com/hayes0724/shopify-packer/commit/76d4188557f92746b15d108539bda5fd6b6a9b2f))


### :hammer: Code Refactoring

* **webpack-config:** removed img-loader and changed order of image loaders ([48966af](https://github.com/hayes0724/shopify-packer/commit/48966afb5d6ef7009e77317a6bc1e8271091e447))


### chore

* **webpack-config:** verbose output removed from clean webpack plugin ([4ae1f5c](https://github.com/hayes0724/shopify-packer/commit/4ae1f5c4e2077bfa3d462f1bc08b9919d2adea0d))



## [1.3.3](https://github.com/hayes0724/shopify-packer/compare/1.3.2...1.3.3) (2020-12-14)


### chore

* **webpack-config:** verbose output removed from clean webpack plugin ([50c7a34](https://github.com/hayes0724/shopify-packer/commit/50c7a3444b4d4f8a265cb26b932e2838b85ce39a))



## [1.3.2](https://github.com/hayes0724/shopify-packer/compare/1.3.1...1.3.2) (2020-12-10)


### :bug: Bug Fixes

* **packer-theme:** theme:download command typo in ignored files ([060d803](https://github.com/hayes0724/shopify-packer/commit/060d803e9faa2c7b37649617981c99af9522c117)), closes [#18](https://github.com/hayes0724/shopify-packer/issues/18)



## [1.3.1](https://github.com/hayes0724/shopify-packer/compare/1.3.0...1.3.1) (2020-12-10)


### :bug: Bug Fixes

* **packer-config:** env value live for allowing live theme deploy ([abd0d9f](https://github.com/hayes0724/shopify-packer/commit/abd0d9f5bc98a50eb8850e8785c5a34d50d1df72)), closes [#25](https://github.com/hayes0724/shopify-packer/issues/25)



# [1.3.0](https://github.com/hayes0724/shopify-packer/compare/1.2.1...1.3.0) (2020-12-10)


### :bug: Bug Fixes

* **html-webpack:** fixed style tag generator typo ([a23064a](https://github.com/hayes0724/shopify-packer/commit/a23064aebf70cfbb552b1470b70fedd7264e6db5))
* **packer-help:** Fixed help table rendering ([0656149](https://github.com/hayes0724/shopify-packer/commit/065614992bfc053630743ceb5f3e3acda96924b2))
* **webpack-config:** Clean webpack removes entire dist folder before build ([595597d](https://github.com/hayes0724/shopify-packer/commit/595597dbdbe643987f98947be33eb83baad7e7a6)), closes [#22](https://github.com/hayes0724/shopify-packer/issues/22)


### :memo: Documentation

* **packer-config:** updated readme with source configs ([857742c](https://github.com/hayes0724/shopify-packer/commit/857742c242375d544b480e4a082ba5a546c89213))


### :sparkles: Features

* **packer-theme:** Added id flag for `theme:remove` as an alternative to env values ([12b1fde](https://github.com/hayes0724/shopify-packer/commit/12b1fde8658779a356d63335a06bdc5937f41dc8))
* **webpack-config:** added ts file type to babel loader ([e7e1b3a](https://github.com/hayes0724/shopify-packer/commit/e7e1b3a049b68363f166566e40c63e428f262a59))


### :wrench: Build System

* CI workflow updated. NPM now uses `--access public` ([9cd64fd](https://github.com/hayes0724/shopify-packer/commit/9cd64fdbde23a3b9482e1de62f04cfb021c7bdac))



## [1.2.1](https://github.com/hayes0724/shopify-packer/compare/1.2.0...1.2.1) (2020-10-06)


* Update README.md ([3cc94ba](https://github.com/hayes0724/shopify-packer/commit/3cc94ba76a93e0cad193ffc2ced6e5763d511731))


### :bug: Bug Fixes

* **packer-config:** config keys set as strings ([42fc6e2](https://github.com/hayes0724/shopify-packer/commit/42fc6e2119fbf06b1c3e04dbeb2ab89dd302d99d))
* fixed issue with empty config files and webpack merge ([eba227c](https://github.com/hayes0724/shopify-packer/commit/eba227c64ae94ca9527851c459b30dc549d47f0d))


### :wrench: Build System

* .editorconfig added ([86a4f29](https://github.com/hayes0724/shopify-packer/commit/86a4f29d4c408f73643ccd1063b3c62f1d8cd1c7))



# [1.2.0](https://github.com/hayes0724/shopify-packer/compare/1.1.0...1.2.0) (2020-10-05)


### :art: Styles

* eslint fix on all javascript ([4f9c857](https://github.com/hayes0724/shopify-packer/commit/4f9c8576482d1a5619e6f4f2c39bfe21bdee6b4a))
* fixed eslint issues ([51a2a40](https://github.com/hayes0724/shopify-packer/commit/51a2a4040ed147b2886f648289bfb1412aecd604))


### :hammer: Code Refactoring

* all configurations files combined ([7648d05](https://github.com/hayes0724/shopify-packer/commit/7648d0539b5ce6cc778be9663c288e3a63bef785))


### :heavy_check_mark: Tests

* jest test for PackerConfig created ([ef8d13f](https://github.com/hayes0724/shopify-packer/commit/ef8d13fe2cb059654eb046c6de1780d346eb338a))


### :memo: Documentation

* readme updated with new settings config ([f12b66f](https://github.com/hayes0724/shopify-packer/commit/f12b66f71d22c6f99ef5b2728fedeb99defbe938))


### :wrench: Build System

* `lerna-changelog` added ([31ffece](https://github.com/hayes0724/shopify-packer/commit/31ffecef75ca753f618cd072e353e110928f8d08))
* development branch added to github workflow ([482066f](https://github.com/hayes0724/shopify-packer/commit/482066f57ccb8af89d5a6acb28ca480782d62eee))
* github workflow action added ([8afec77](https://github.com/hayes0724/shopify-packer/commit/8afec772c7a9ed82f31524f8673de44825d0956d))
* github workflow action added ([7886925](https://github.com/hayes0724/shopify-packer/commit/7886925961b03e8af024faed79b1edbe180e7f4e))


* test: ([8236d34](https://github.com/hayes0724/shopify-packer/commit/8236d34183d9951beaac80cb82ca37eb7d8cf422))
* Updated readme and added license ([7258e85](https://github.com/hayes0724/shopify-packer/commit/7258e85eee42fc028163356cf34c605c4ad49ccf))


### :boom: BREAKING CHANGES

* config is now located in `packer.config.js` and `packer.env.json`



# [1.1.0](https://github.com/hayes0724/shopify-packer/compare/1.0.7...1.1.0) (2020-10-01)


* Updated all packages to latest versions ([0d68d08](https://github.com/hayes0724/shopify-packer/commit/0d68d08aed480e7ebdb15e56faeae1b2998b215f))



## [1.0.7](https://github.com/hayes0724/shopify-packer/compare/1.0.6...1.0.7) (2020-09-27)


* bundle analyzer build command ([a8c3be6](https://github.com/hayes0724/shopify-packer/commit/a8c3be667eb569b70e3e40b1af6a2718e1c932b3))
* refactored dev build settings ([0536132](https://github.com/hayes0724/shopify-packer/commit/0536132fb7ad8ed52d720ae52ad8b7643ba1f9b3))
* fixed script tag creation ([97b7f02](https://github.com/hayes0724/shopify-packer/commit/97b7f022701340f6f3d2289a9802235bfae4b300))
* Update index.js ([1e57e4d](https://github.com/hayes0724/shopify-packer/commit/1e57e4daa48c96044b49ae91e74c588fbbdec1e9)), closes [#4](https://github.com/hayes0724/shopify-packer/issues/4)
* theme commands now use env argument ([1507e25](https://github.com/hayes0724/shopify-packer/commit/1507e252ec1eef1afe44b1d723314a7c2145f922))
* changed settings data prompt text ([886e731](https://github.com/hayes0724/shopify-packer/commit/886e731d88c057b9cb99151c3e559a6ccdc4cea5))



## [1.0.6](https://github.com/hayes0724/shopify-packer/compare/1.0.3...1.0.6) (2020-07-15)


* updated lodash version and removed jquery ([470b044](https://github.com/hayes0724/shopify-packer/commit/470b044b3fe17aec83a08d67dbcdab5bedad0cc1))
* Changed init to pull latest release and option for custom repo ([8832d7b](https://github.com/hayes0724/shopify-packer/commit/8832d7b941c446ea063ee243b949744c4f9e9566))
* check if webpack merge file exists before loading ([eb162be](https://github.com/hayes0724/shopify-packer/commit/eb162be8ca26dfe626014feb9cd8e45cbb9505f8))



## [1.0.3](https://github.com/hayes0724/shopify-packer/compare/1.0.1...1.0.3) (2020-07-01)


* merge and modify webpack config ([f318ded](https://github.com/hayes0724/shopify-packer/commit/f318dedc013319dc087703982b70594912bbdce7))
* start out put text changed ([0f425e5](https://github.com/hayes0724/shopify-packer/commit/0f425e5681dd5507c408b6242945cffcb6b7bb0f))
* updated readme with package name ([9077613](https://github.com/hayes0724/shopify-packer/commit/9077613ad2c9cbf44229ffcef5fc39adce0c01c6))
* added scope to packages.json ([e8dad23](https://github.com/hayes0724/shopify-packer/commit/e8dad23c715ad8257905703181fdad65ae242a3d))



## [1.0.1](https://github.com/hayes0724/shopify-packer/compare/1.0.0...1.0.1) (2020-06-19)


* updated package.json ([bc5378f](https://github.com/hayes0724/shopify-packer/commit/bc5378fd994cd7b6e49e3186a5c53d1b279b2ec9))
