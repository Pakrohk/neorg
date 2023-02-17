# Changelog

## [3.0.0](https://github.com/nvim-neorg/neorg/compare/v2.0.1...v3.0.0) (2023-02-17)


### ⚠ BREAKING CHANGES

* **docgen:** wipe whole wiki on every reparse

### Features

* add `dirman.summary` module ([#750](https://github.com/nvim-neorg/neorg/issues/750)) ([93c40f2](https://github.com/nvim-neorg/neorg/commit/93c40f2e38a0770e9ce95787c8363320344a87c3))
* add `Home.md` generation capability ([6bdf557](https://github.com/nvim-neorg/neorg/commit/6bdf557ece33850f9733dddc343369d743a51564))
* cleanup, add document comments to all modules, add more error checks ([81284c1](https://github.com/nvim-neorg/neorg/commit/81284c1e2f6e441f6532678b76ff5378396dda2c))
* **dirman:** add new `use_popup` option for `dirman` ([#743](https://github.com/nvim-neorg/neorg/issues/743)) ([6350254](https://github.com/nvim-neorg/neorg/commit/63502544afde1c15d79ce097ad1928314cb8c7cd))
* **docgen:** add `module` page generator ([17496a8](https://github.com/nvim-neorg/neorg/commit/17496a8e975f1bd9d896d7cc78a6e61d1a131245))
* **docgen:** add basic rendering skeleton logic ([215719e](https://github.com/nvim-neorg/neorg/commit/215719ece560400592c2fef2ed75ab57430baf9b))
* **docgen:** add comment integrity checking logic ([799886f](https://github.com/nvim-neorg/neorg/commit/799886f7ba5a072a453d5a90708686109ce4fa21))
* **docgen:** allow strings as table keys ([4adf04e](https://github.com/nvim-neorg/neorg/commit/4adf04e05d98b6bcb6a3aac4cab60d64fd0d86f9))
* **docgen:** auto-open &lt;details&gt; tags that contain tables or lists ([1f2e0dc](https://github.com/nvim-neorg/neorg/commit/1f2e0dc23f6944bad660553ad4550847cf68e096))
* **docgen:** differentiate between lists and tables ([c0062e5](https://github.com/nvim-neorg/neorg/commit/c0062e5a75226f063b59eb5ee8250cb4da6ea202))
* **docgen:** differentiate empty and nonempty tables/lists ([0ab1a8d](https://github.com/nvim-neorg/neorg/commit/0ab1a8d469667d6b763e299c390a3e9bc7ea1a13))
* **docgen:** implement `Required By` field ([7033c4b](https://github.com/nvim-neorg/neorg/commit/7033c4bd2dc4633d0874b2da05b0ae67928b1117))
* **docgen:** implement `Required By` section ([15bf71b](https://github.com/nvim-neorg/neorg/commit/15bf71b15e07917e0f3a55de44e79fcdfbfc557d))
* **docgen:** implement configuration_options parsing logic ([b34658a](https://github.com/nvim-neorg/neorg/commit/b34658a21602fdd286889c2e57bf2d68d63d4472))
* **docgen:** implement function rendering, fix incorrect interpretation of function calls ([a023488](https://github.com/nvim-neorg/neorg/commit/a023488944473dfcd611308d5e21b7a9b2d7690d))
* **docgen:** implement table rendering ([9074328](https://github.com/nvim-neorg/neorg/commit/907432885e40a16f064d4406cd45efeb895f0962))
* **docgen:** indent nested table keys ([9cf679a](https://github.com/nvim-neorg/neorg/commit/9cf679a24f3bb9db145ae4dfbeb43878a49839e3))
* **docgen:** massive structure changes, implement proper table rendering ([42b8728](https://github.com/nvim-neorg/neorg/commit/42b8728f291072b9d8a11bdf9c7e205ef15fb94d))
* **docgen:** parse config tables ([93c41e1](https://github.com/nvim-neorg/neorg/commit/93c41e1f0aa290d0ad2e2590753312c71a782395))
* **docgen:** perform `[@module](https://github.com/module)` lookups, pasre complex data structures like tables ([19f2381](https://github.com/nvim-neorg/neorg/commit/19f23811ba0366fe3ec9423d26aec33d9d34fcc2))
* **docgen:** properly implement recursive table scanning ([33e06b8](https://github.com/nvim-neorg/neorg/commit/33e06b8d0fc2e7a9b386fc95e6bce4dfb714e56f))
* **docgen:** sort entries when rendering ([b420e70](https://github.com/nvim-neorg/neorg/commit/b420e70532766475bce0bf1d34129e711a31e21a))
* **docgen:** start generating true module pages ([5115d5c](https://github.com/nvim-neorg/neorg/commit/5115d5cd4bd1fefb11f82cb3e3da18b74d4e9b9e))
* **helpers:** add `ensure_nested` function ([2c4e8d0](https://github.com/nvim-neorg/neorg/commit/2c4e8d02feb7f1e6878307e7813a9f13ec000a73))
* implement _Sidebar generation ([733b74c](https://github.com/nvim-neorg/neorg/commit/733b74c92481bc955f1f46594e50fb4931ab3cf5))
* implement necessary APIs for complex data structure parsing ([b78f01c](https://github.com/nvim-neorg/neorg/commit/b78f01cd951b8ecfe7e842d31f609e6e4d5ac9db))
* implement new docgen featuring top-comment validation ([b77fbd5](https://github.com/nvim-neorg/neorg/commit/b77fbd52f96db049687901ac1f0a8aea7ab4bdfa))
* **makefile:** add `local-documentation` option ([ed20f79](https://github.com/nvim-neorg/neorg/commit/ed20f796f5bb337d230f5d33a3f6ba420a8d30a4))
* **qol.todo_items:** add new `create_todo_items` option ([d810aa4](https://github.com/nvim-neorg/neorg/commit/d810aa43c96301db35af351306eab54e35071d57))
* **qol.todo_items:** add new `create_todo_parents` option (false by default) ([6b6ef04](https://github.com/nvim-neorg/neorg/commit/6b6ef04e5fb0a5b1c3ff59699a9371afd659d9ff))
* **qol.todo_items:** when only done and uncertain items are present in ([1d6b0b0](https://github.com/nvim-neorg/neorg/commit/1d6b0b056b097e9f4bacf8877c49fdacbc445b2c))
* strip leading `--` from comments ([ecea630](https://github.com/nvim-neorg/neorg/commit/ecea6305a82007b6c8c509fd594f8b52c3331021))


### Bug Fixes

* `:Neorg journal today` would fail on alternative path separators ([#749](https://github.com/nvim-neorg/neorg/issues/749)) ([e7a5054](https://github.com/nvim-neorg/neorg/commit/e7a50542ad9921a8c7d652eeca6a9006cc024b79))
* **base.lua:** don't assign the `extension` flag to parent modules, only to the imports themselves ([fa5f561](https://github.com/nvim-neorg/neorg/commit/fa5f56163510eb00a0d75bec81d40d901c175d3b))
* **core.clipboard.code-blocks:** module would not work past version `1.0.0` ([ac88283](https://github.com/nvim-neorg/neorg/commit/ac8828369cb2a4b2e1e17e6b495645585ed2a37b))
* **core.itero:** preserve indentation on continued items ([92c31c4](https://github.com/nvim-neorg/neorg/commit/92c31c491caedd7d1a82b42d4ba6c2227c05d930))
* **core.norg.journal:** fixes [#736](https://github.com/nvim-neorg/neorg/issues/736) , now generates TOC correctly ([19c5558](https://github.com/nvim-neorg/neorg/commit/19c555836bc31f482e0ea42f08d150110754644f))
* **dirman:** corrected win width and height calculation ([9766bef](https://github.com/nvim-neorg/neorg/commit/9766bef893ec993af9408ea0d44a8f13adbd1e80))
* **docgen:** `&lt;h6&gt;` tags not being rendered properly ([d0a0da0](https://github.com/nvim-neorg/neorg/commit/d0a0da017135b48c5f4a325bfaedbcdf1ca79fe3))
* **docgen:** could not find module `neorg` ([b68a945](https://github.com/nvim-neorg/neorg/commit/b68a945d6b1a8c2f8c57e0c366f224a162f391e3))
* **docgen:** display listed modules in alphabetical order ([264b451](https://github.com/nvim-neorg/neorg/commit/264b451d74d3e4bc3f856d087070b9dac46f8e90))
* **docgen:** don't double-render numeric values ([35df191](https://github.com/nvim-neorg/neorg/commit/35df1918de321617972f10edd88d9c32cc8102a2))
* **docgen:** don't render description tags if no description is present ([64dc28d](https://github.com/nvim-neorg/neorg/commit/64dc28deea9a7f9c52c3ba5343f1ce3c754a566e))
* **docgen:** don't unnecessarily copy parsers ([46e7936](https://github.com/nvim-neorg/neorg/commit/46e79366775136592540fbe5f0532c001012daa5))
* **docgen:** incorrect wiki paths ([2dbead6](https://github.com/nvim-neorg/neorg/commit/2dbead687053610147161ecda1a908070720731f))
* **docgen:** internal modules that were part of `core.defaults` would not be displayed in the developer modules section ([c3099eb](https://github.com/nvim-neorg/neorg/commit/c3099ebd595d3ec491613c297f4199e316f85853))
* **docgen:** list items with no summary would break rendering ([b69ea57](https://github.com/nvim-neorg/neorg/commit/b69ea57029a2c62e72ea86c93d295102059c58ab))
* **docgen:** lists within lists would never be rendered ([06894bb](https://github.com/nvim-neorg/neorg/commit/06894bb090ad6deb52ba7b19f7e13bbb41385a63))
* **docgen:** make the spacing nicer to look at ([426ca24](https://github.com/nvim-neorg/neorg/commit/426ca246e310a212cef5f6bba367d7ebc84bf70b))
* **docgen:** remove debug log ([8ffcaed](https://github.com/nvim-neorg/neorg/commit/8ffcaed1095743b8474a16f25855b809cf4fe65d))
* **docgen:** this should work now i think (after 20 tries) ([72d3d49](https://github.com/nvim-neorg/neorg/commit/72d3d4981d85fd1114d3185e40cc135a7892a4a4))
* **docgen:** use minimal_init.vim instead of custom_init.vim ([a7cb7ab](https://github.com/nvim-neorg/neorg/commit/a7cb7ab443c24fbd1d9f696abddd91c16f05d842))
* **docgen:** wrong `require` order in `docgen.lua` ([7494b51](https://github.com/nvim-neorg/neorg/commit/7494b51a61cc31371514cb7b2e1ccdf4cef164e2))
* **qol.todo_item:** `&lt;C-space&gt;` would not create a new TODO item with ([fc45beb](https://github.com/nvim-neorg/neorg/commit/fc45bebde0fc9811ca4e770e2ba29c791035c885))
* **qol.todo_items:** `&lt;C-space&gt;` would not respect the `create_todo_items` option ([e764b92](https://github.com/nvim-neorg/neorg/commit/e764b92065ddd6bc206aaefd92837be8d0bd8419))
* **qol.todo_items:** TODO attributes would be erroneously assigned multiple times ([1303097](https://github.com/nvim-neorg/neorg/commit/13030974acee5a49dd02c51bedeac104b4f33cb7))


### Miscellaneous Chores

* **docgen:** wipe whole wiki on every reparse ([09cb3e6](https://github.com/nvim-neorg/neorg/commit/09cb3e62022ff0f93965800a728ed698db540240))

## [2.0.1](https://github.com/nvim-neorg/neorg/compare/v2.0.0...v2.0.1) (2023-02-02)


### Bug Fixes

* completion for TODO items ([#711](https://github.com/nvim-neorg/neorg/issues/711)) ([9184027](https://github.com/nvim-neorg/neorg/commit/91840274112f1286ff5f4063ac6f515683b6dc67))
* **core.norg.journal:** add proper error handling for `vim.loop.fs_scandir` ([4a9a5fe](https://github.com/nvim-neorg/neorg/commit/4a9a5fe13cd454692fc4db0b27783cd005e6be56))
* **treesitter:** don't constantly log errors about erroneous document syntax trees ([9f8b0a1](https://github.com/nvim-neorg/neorg/commit/9f8b0a1759d883fae901579ea83b3ffbfc81a53b))

## [2.0.0](https://github.com/nvim-neorg/neorg/compare/v1.1.1...v2.0.0) (2023-01-06)


### ⚠ BREAKING CHANGES

* **core.norg.qol.toc:** rewrite the table of contents implementation

### Features

* **core.export:** add `NeorgExportComplete` user autocommand ([8b10e61](https://github.com/nvim-neorg/neorg/commit/8b10e61d2f2c5e626849f9a6f8cb4399c28a1a47))
* **core.norg.qol.toc:** add multiple buffer handling logic ([467e311](https://github.com/nvim-neorg/neorg/commit/467e3113c32b8b9f1950a9425aa7b74c13cd88b8))
* **core.norg.qol.toc:** implement `qflist` generation option ([77c5149](https://github.com/nvim-neorg/neorg/commit/77c514970a9d4648b05b2334a060263666f588e2))
* **treesitter:** add `execute_query` function ([310ebaa](https://github.com/nvim-neorg/neorg/commit/310ebaaef538dfd41d02a2903663be05fd38834b))


### Bug Fixes

* **core.ui:** do not modify the user's `scrolloffset` ([bd2e58c](https://github.com/nvim-neorg/neorg/commit/bd2e58cf6f9d42527aa2b692fb187eafa82bd91e))


### Performance Improvements

* further optimize `toc` infirm tag grabber ([5e8d059](https://github.com/nvim-neorg/neorg/commit/5e8d05968e04f7945576d50a6b1576cc722f96fc))
* optimize the `toc` infirm tag grabber code ([a41bd4a](https://github.com/nvim-neorg/neorg/commit/a41bd4a92afefb7e2630b821b59f7707a054baac))


### ref

* **core.norg.qol.toc:** rewrite the table of contents implementation ([c0104fb](https://github.com/nvim-neorg/neorg/commit/c0104fb9faed3b3213e4e275a55a522a299a2d0e))

## [1.1.1](https://github.com/nvim-neorg/neorg/compare/v1.1.0...v1.1.1) (2023-01-05)


### Bug Fixes

* **core.export:** incorrect exporting of code blocks with no parameters ([#701](https://github.com/nvim-neorg/neorg/issues/701)) ([0922815](https://github.com/nvim-neorg/neorg/commit/0922815837a374bd0b2a3cf0477b54e6668e133d))

## [1.1.0](https://github.com/nvim-neorg/neorg/compare/v1.0.1...v1.1.0) (2023-01-05)


### Features

* keep checkboxes with `core.itero` ([#663](https://github.com/nvim-neorg/neorg/issues/663)) ([00532bd](https://github.com/nvim-neorg/neorg/commit/00532bd997d2aef0384ed8f11500d33d229a7e53))


### Bug Fixes

* **core.export.markdown:** incorrectly exported code blocks ([dd2750c](https://github.com/nvim-neorg/neorg/commit/dd2750c0e4d847b67a6ead79ff5043e671cac8bd))
* **folds:** correctly fold document metadata ([adc000a](https://github.com/nvim-neorg/neorg/commit/adc000aadd41e68e4de8a2d1bb90b2e910ffef1b))

## [1.0.1](https://github.com/nvim-neorg/neorg/compare/1.0.0...v1.0.1) (2022-12-23)


### Bug Fixes

* **core.looking-glass:** buffer being closed for no reason after leaving buffer ([828a37f](https://github.com/nvim-neorg/neorg/commit/828a37fe1f008dbfd70cd7fc0f7ba9d0bc75da2a))
* do not run tests for nightly/neorg-main, as GTD is no longer existent ([37f1f9a](https://github.com/nvim-neorg/neorg/commit/37f1f9a44ba65603b5992fc36761c61d921fab78))
