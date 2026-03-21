# Repolex Knowledge Graph of pixeltable/pixeltable

RDF knowledge graph data for [pixeltable/pixeltable](https://github.com/pixeltable/pixeltable), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pixeltable/pixeltable
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   └── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   ├── lsp
│   │   ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   └── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   └── repolex
│       ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│       ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│       ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│       ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│       ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│       ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│       ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│       ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│       ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│       ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│       ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│       ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│       ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│       ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│       ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│       ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│       ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│       ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│       ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│       ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│       ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│       ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│       ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│       ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│       └── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
└── blob
    ├── 00001bfd1808c32980ec7595434343e1f22a0b4f.nq.gz
    ├── 0030b8be2a2209d196109232f2fafa63fd64544a.nq.gz
    ├── 0040bb276de524b02054cdf73ad1d21992c8955f.nq.gz
    ├── 00528850d3592c7c6a5a5334da9733d9dedac49b.nq.gz
    ├── 00621b5199662705e211e7838e215403e37986ff.nq.gz
    ├── 00626c343263372df21d8859e2e1b8aadb2e6501.nq.gz
    ├── 00627118d3a7b537afa5c567d9698ddae2d4599a.nq.gz
    ├── 0063cc853fd60e3b3be3e22df9f12d5a7a1b11cd.nq.gz
    ├── 00662441747c76644f53dafbb992446e5ecea2e5.nq.gz
    ├── 007a60c55c10f06af257cad0b88d0fa4d7c48fdf.nq.gz
    ├── 008a0dd910d41625bc3a0c6c8ca09b330f38da66.nq.gz
    ├── 008a330a24988bde609140ebb58ae62c7cde6b18.nq.gz
    ├── 009774b262644c6af69021c3e786c8a984546272.nq.gz
    ├── 00a6eb51169422cf0d01ddebb888a61a4abed6e4.nq.gz
    ├── 00a7582c21f40404b1bd2e28ca07a736ce43fae1.nq.gz
    ├── 00bd0bcb0b7f45acf040f6d640757ad6fd61e504.nq.gz
    ├── 00cf914923f3cf3eb76743c543e4a618a7ea4d43.nq.gz
    ├── 00df6c825fc73276546b71f3d3ee5af5dc4815ab.nq.gz
    ├── 00ee2705f087badce54a0f99eb45c9dad7d00501.nq.gz
    ├── 0107b02ede3ec8d688d58488e2058b13a5d70987.nq.gz
    ├── 01385dcdaa32dad6fa4e370db9b2de00bd3de230.nq.gz
    ├── 014feb69b4e9aab17fdbb73b49c9e9f0d162fcff.nq.gz
    ├── 01523484050c2d7a3f1ee6f9fcc2b291f3586781.nq.gz
    ├── 015748d18b48b7df8712f6f4f831826d84999581.nq.gz
    ├── 0157b29e203e320d3d5bc72f38e2101c9281d7d6.nq.gz
    ├── 01600739f73d2bffee0ea481faffd8688ca43c9f.nq.gz
    ├── 0163e9e6d0d5c3618cf53c75ed8405e3750a6fa5.nq.gz
    ├── 0188d770f778b12067dcd951603e78ca18461738.nq.gz
    ├── 0196dd14136a5a133ee0268f50c15bcb7bfa3495.nq.gz
    ├── 01994c2ef621aa0fdccc9029fb54c76d6e43d675.nq.gz
    ├── 01a043c63072f1b27a32ca2461b9393b9e95c9ff.nq.gz
    ├── 01a73575240804835d2d1fe54755d26592dfd177.nq.gz
    ├── 01bcd9fc78fa09cc3f3ff39e9bef53d31ec6dbbd.nq.gz
    ├── 01ccc73ef45a64ae2031bd4c2b3bcdaccd73b111.nq.gz
    ├── 01e8377d268304677b4a5d133fc3a218be9a78df.nq.gz
    ├── 01ed2893cd600945dd5bbbcc71d03dcb82134557.nq.gz
    ├── 020469747a1c09de6caf9ccff1d6bda48c5ea6a8.nq.gz
    ├── 021997af39ea24deca26c6173acdf9fd02670333.nq.gz
    ├── 02227f583d560f3726ea023f1dc968ed2e94cdee.nq.gz
    ├── 0262029758d2b758c3c215a31aebae986f9efe89.nq.gz
    ├── 0262b02440400e016fccb047ed5251ea53c0efc4.nq.gz
    ├── 0266e5758f76d7b078f01fa4e049c0edbffeb50c.nq.gz
    ├── 026aaf8c4400ce77c012d5f91c6d8ee6d7892549.nq.gz
    ├── 028288d5c05c5d1fc6f02e01d45eacc235675d2a.nq.gz
    ├── 028821a8d04d80164c6f0d6b3a46476edec3f5d7.nq.gz
    ├── 028f4dc812b06b767f3fdfbc2f56f8977a296327.nq.gz
    ├── 02991e3eb970390cf07733c7c0d916ef0af4bcdb.nq.gz
    ├── 02a4bd7b73b6eb2bf4ec22d5483076fc89b6456e.nq.gz
    ├── 02b16c4f862d93c9ac3fbe571340272ae771dea3.nq.gz
    ├── 02bdf9cff13ffdf7c7a1aa38490bfc023dc2ba9f.nq.gz
    ├── 02d449971065e8f111b34850deb067dfaaab7e6a.nq.gz
    ├── 02d7470e9e4878528981889500ab00a1f15eb225.nq.gz
    ├── 02e980ea4fd5ba1d2a8c41c74efe4dd92f56d734.nq.gz
    ├── 02ea095b53455ee0138753173fe4e68c5b19d2be.nq.gz
    ├── 02fa6535d2b98f94fdf6cc0e654949ffa253d0dd.nq.gz
    ├── 03035fef0b2fcd16dd3c977bd9bbcb0f1e3e669f.nq.gz
    ├── 0306f9771336766cd97e0218860547020b27fe23.nq.gz
    ├── 0316d13f6f6fc3be1204f39c7c319b7fb4890e48.nq.gz
    ├── 0320331371eeb7194e17fb743b908c318b086328.nq.gz
    ├── 0334f7c581f082dcbbe5e8fc6d2fa184184c6eea.nq.gz
    ├── 033df5fb60d73b2e9b7a51436be920e2b6974960.nq.gz
    ├── 034040844716d0b66fb00fef1a835dfd46361b99.nq.gz
    ├── 036ec20d21f471ec8da7fa134c5acbcc6d322ed0.nq.gz
    ├── 03a5b7444bb8e9ac6b34b87a942a141db5975dc1.nq.gz
    ├── 03b7f0367de70d9f5327dab90ac254992e2683da.nq.gz
    ├── 03ba7f350774605e7c59bb8c6d02ca024c29f2a4.nq.gz
    ├── 03bfd0f7a73120dca57e0df037193878cf6ff266.nq.gz
    ├── 03c4c40f6ce55c4c2068dcca11857c6e4cf6c300.nq.gz
    ├── 03c4f99ba9fdb8434065644f354c51254eacddd4.nq.gz
    ├── 03c941ee4a8bbfbf068da9ee24ad8e276d5e5059.nq.gz
    ├── 03dc35c683dc012ba922c080c65b97514ee244ad.nq.gz
    ├── 03e08cdcc812d40ebd1d7a179eb7957b612f9873.nq.gz
    ├── 03ecbf9d7d17fadf1fe8e4cc770b9e8441ee7715.nq.gz
    ├── 03f6b9adca136ac89501fb221b19153b28ab1af9.nq.gz
    ├── 04003381fd4e83ecc309ed531257f5918e0b3c33.nq.gz
    ├── 04045ba18eb66fd93488e47ef9ef90be1655ec8e.nq.gz
    ├── 0421632d20267d11a12f3e8464709351b279718d.nq.gz
    ├── 042d179157f8374ca9c77208cce4fdec0b040063.nq.gz
    ├── 043063dbb6ab488bfd6be70fa7a0758218e7f117.nq.gz
    ├── 04312e515b33b54bdef7b56761d8eab21dbd61f9.nq.gz
    ├── 044934ebf22610836d0c4bcadfb587235ae3193d.nq.gz
    ├── 046fceff270405d96e32a9ae8f92594c4215907f.nq.gz
    ├── 047da5dd2cca66038ee8c3fe3086ccf527b27016.nq.gz
    ├── 047fc042166c7ec3f84f2633a9622907afb7938a.nq.gz
    ├── 04823610b0e9c9830be7d03cc693b158cc9234dd.nq.gz
    ├── 04952b7214e56c2ebcf73dad456424c0b3211190.nq.gz
    ├── 049b80efc273612720764e0e2e34ea86d2e9a8e6.nq.gz
    ├── 04ba2f16444d0e896a3747fae5019be177457271.nq.gz
    ├── 04d6912e7c471a6a54ed0b5930877e8d764702a2.nq.gz
    ├── 0501b8314a0c64766475253acd05b7038b6e3609.nq.gz
    ├── 0519ecba6ea913e21689ec692e81e9e4973fbf73.nq.gz
    ├── 05734f3289d24b1d2cec63f65216fb9b1894e7b4.nq.gz
    ├── 058625c2c6626dc238113636a6f1158bec29c453.nq.gz
    ├── 05896ff1a80ac16941120bc2bf884a3ca732d03c.nq.gz
    ├── 05a078be77e08a91e965efd10bfaaf24121ef495.nq.gz
    ├── 05a118d05acabe401d425175f14b4ed0fb0c201b.nq.gz
    ├── 05b3555774907909e204e76253500d020b77670d.nq.gz
    ├── 05bb7c38aee33e07b44d7ec4de45d6ab65039bea.nq.gz
    ├── 05c32b2126c4eaf6f904f658291f2c56a4519c88.nq.gz
    ├── 0606637548f985916eaecdecb8a06e01a64c2ceb.nq.gz
    ├── 0608a35d5b5562508c939f68bb01647222026992.nq.gz
    ├── 061206dd4ce37dcba3e45ea556bd3e6177fe5589.nq.gz
    ├── 0617adbb0445bc257093697630e1bfae6c23b4d7.nq.gz
    ├── 062536e38b9ee72a90c04dd398997ba1022bb6d8.nq.gz
    ├── 062c78d8f1cf9cd545ff85ed498958931931aa0c.nq.gz
    ├── 063df18c4df38d0ed3cd52aa69c79336b9a8ca53.nq.gz
    ├── 06403d71d6e950fe2932090acb31c4bb3bf2b5af.nq.gz
    ├── 0649ce08fe86981359bb15717424e91a96e015c0.nq.gz
    ├── 06677ca33523806030d876587ca64a4581773865.nq.gz
    ├── 0672169e19485b64b09eee0fbc6b9b3da6bc73c0.nq.gz
    ├── 06a8c748fd4244d9b386e4cf5451331f7922b31c.nq.gz
    ├── 06ab20827d95a0dbfa00b09a1250da8b2be67ed9.nq.gz
    ├── 06b20d2b228ce80a788cecdba80eede22554908e.nq.gz
    ├── 06fac3be4213cea1d0a731099024136df5c65789.nq.gz
    ├── 06fb2e043efb7a9b3f9918a0ddde5f69ea2626ed.nq.gz
    ├── 06fd08b9be478d20cb9862b56887722954676d05.nq.gz
    ├── 071f56323e67e3e44374b19d374ba0c0b32a5f6d.nq.gz
    ├── 0722d00c311d4fd306ffe00c677cc720c52047b7.nq.gz
    ├── 0727f4fb9dce78a5746518ace4e165c8fda3f7d7.nq.gz
    ├── 072b1d1d08d945fdff5d474d948928292e45f95f.nq.gz
    ├── 076388c99e7447e0560599e0dfc2a4911b66881b.nq.gz
    ├── 07669d720fa8f1611fe14c0af4cad08bfa765ea9.nq.gz
    ├── 076e90fb02c3479983b245da766e17d2b56c271f.nq.gz
    ├── 0779fe264aaf123a1bb1d2f088ccd69c11728ff0.nq.gz
    └── 078c2c724692cc736b9d36443168c8df4e593610.nq.gz

6 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[pixeltable/pixeltable](https://github.com/pixeltable/pixeltable)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
