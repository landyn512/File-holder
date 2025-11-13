# Changelog

## 1.0.0 (2025-11-13)

Full Changelog: [v0.0.1...v1.0.0](https://github.com/landyn512/File-holder/compare/v0.0.1...v1.0.0)

### Features

* **mcp:** add docs search tool ([3225342](https://github.com/landyn512/File-holder/commit/32253424c05006fa9f671daffbe08b23632eaeeb))
* **mcp:** add option for including docs tools ([273c3c7](https://github.com/landyn512/File-holder/commit/273c3c76060d65dda46722e7d88a35731af98d6c))
* **mcp:** enable experimental docs search tool ([de4d48d](https://github.com/landyn512/File-holder/commit/de4d48dcf9d28150a26c558cfee782e0255a6122))
* **mcp:** enable optional code execution tool on http mcp servers ([c87acad](https://github.com/landyn512/File-holder/commit/c87acadda3c07429901c35101ae4c902b93a8d0b))


### Bug Fixes

* **ci:** set permissions for DXT publish action ([c3a35f4](https://github.com/landyn512/File-holder/commit/c3a35f41a7c29e9a7ec6ba60257d275c93981c23))
* **mcpb:** pin @anthropic-ai/mcpb version ([25c9958](https://github.com/landyn512/File-holder/commit/25c9958be3af648b39b036503630374606802084))
* **mcp:** fix cli argument parsing logic ([8a478e3](https://github.com/landyn512/File-holder/commit/8a478e31985280a249afc01f7cf19f3d8c94e86b))
* **mcp:** resolve a linting issue in server code ([98f2688](https://github.com/landyn512/File-holder/commit/98f26881de5fee366d88c8d6432c054d29863ec1))
* **mcp:** return tool execution error on jq failure ([1d7cb6b](https://github.com/landyn512/File-holder/commit/1d7cb6b4de888a079ae6a173fe189d620c4ce8ee))


### Performance Improvements

* faster formatting ([cb7ae36](https://github.com/landyn512/File-holder/commit/cb7ae3666544fe4dc1a1b93d5371bd9c162f6e99))


### Chores

* **codegen:** internal codegen update ([2e71c33](https://github.com/landyn512/File-holder/commit/2e71c3317827562a9ad85d2a751e62c935d872e7))
* configure new SDK language ([75e3728](https://github.com/landyn512/File-holder/commit/75e3728613ff19d2e9accf849e9a955991d06722))
* do not install brew dependencies in ./scripts/bootstrap by default ([a41e269](https://github.com/landyn512/File-holder/commit/a41e26907046aaccd9c15ed0cf067c97443f5f6b))
* extract some types in mcp docs ([5d74e93](https://github.com/landyn512/File-holder/commit/5d74e93ba6b22f2c0e6d99c38d901c9d37c24105))
* **internal:** codegen related update ([5c06115](https://github.com/landyn512/File-holder/commit/5c061157ee8b797f0952b4320f231756addc2578))
* **internal:** codegen related update ([2485e67](https://github.com/landyn512/File-holder/commit/2485e673d3fd01d60342b821b48d0d7b0c01ebd9))
* **internal:** codegen related update ([e6df082](https://github.com/landyn512/File-holder/commit/e6df0825643537ab6bfee7a41ceb8e4779ba656f))
* **internal:** fix incremental formatting in some cases ([34057ca](https://github.com/landyn512/File-holder/commit/34057ca1c6879fe37b694f1bf5e08a1530543c92))
* **internal:** gitignore .mcpb files ([231d9dc](https://github.com/landyn512/File-holder/commit/231d9dcfaaba1ea4fcefa5b09ecfd4da093c376b))
* **internal:** grammar fix (it's -&gt; its) ([e939583](https://github.com/landyn512/File-holder/commit/e939583a0b9d0a33717ca81fba2d58f0552a26c1))
* **internal:** ignore .eslintcache ([ba76474](https://github.com/landyn512/File-holder/commit/ba76474c803dd624d59058797d25492963cfa8e2))
* **internal:** remove .eslintcache ([b39315e](https://github.com/landyn512/File-holder/commit/b39315e79671ae2681b14d0104675ea45f98a58c))
* **internal:** remove deprecated `compilerOptions.baseUrl` from tsconfig.json ([508354b](https://github.com/landyn512/File-holder/commit/508354bedaeb278a87545f071fddb48d92ed425f))
* **internal:** use npm pack for build uploads ([c8893c1](https://github.com/landyn512/File-holder/commit/c8893c158fa30e28c4c66d31019097af07085c88))
* **jsdoc:** fix [@link](https://github.com/link) annotations to refer only to parts of the package‘s public interface ([17a7bc2](https://github.com/landyn512/File-holder/commit/17a7bc245e09f593e7c5ebe8623babedb1d108ff))
* mcp code tool explicit error message when missing a run function ([910d21e](https://github.com/landyn512/File-holder/commit/910d21e851d57e369787bb986be48209cc787db1))
* **mcp:** add friendlier MCP code tool errors on incorrect method invocations ([abe31ab](https://github.com/landyn512/File-holder/commit/abe31abe57acf57065d292aec34332430121e700))
* **mcp:** add line numbers to code tool errors ([18a588c](https://github.com/landyn512/File-holder/commit/18a588c70badfcea9501555d6858ad555513afb6))
* **mcp:** allow pointing `docs_search` tool at other URLs ([4793821](https://github.com/landyn512/File-holder/commit/479382160a5f9ad5650f6766e1f97c1f3ea75ca3))
* **mcp:** clarify http auth error ([9fde5d8](https://github.com/landyn512/File-holder/commit/9fde5d825fd633807f7528f20101f200cff441ea))
* **mcp:** rename dxt to mcpb ([c909b7f](https://github.com/landyn512/File-holder/commit/c909b7f7e0840f7d3dc6e001d0cb4b3de8f16e0f))
* **mcp:** upgrade jq-web ([26aa86b](https://github.com/landyn512/File-holder/commit/26aa86b4fb999aafe9f2d222b4061b239e342afb))
* update lockfile ([6872bb9](https://github.com/landyn512/File-holder/commit/6872bb9a804faba4fa641b2ca51193d467f1c85e))
* update SDK settings ([3437d2d](https://github.com/landyn512/File-holder/commit/3437d2df847c33385653bcef1b43af3039343b12))
* update SDK settings ([f058b89](https://github.com/landyn512/File-holder/commit/f058b8962a1fffa688b4ea3ff47a0f0a7b5fc44b))
* use structured error when code execution tool errors ([a80fb14](https://github.com/landyn512/File-holder/commit/a80fb149739b0c2a66b28fe13f455c3025113c99))


### Documentation

* **mcp:** add a README button for one-click add to Cursor ([9f69a22](https://github.com/landyn512/File-holder/commit/9f69a22339e48deaf328066ae1b160bb617e900c))
* **mcp:** add a README link to add server to VS Code or Claude Code ([392a6cd](https://github.com/landyn512/File-holder/commit/392a6cd42fd786cf98bd7eae70658bd316c6a75d))
