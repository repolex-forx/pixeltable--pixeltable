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
│   │   ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│   │   ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   │   └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
│   ├── lsp
│   │   ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│   │   ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│   │   ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   │   └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
│   └── repolex
│       ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│       ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│       ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│       ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│       ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│       ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│       ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│       ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│       ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│       ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│       ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│       ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│       ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│       ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│       ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│       ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│       ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│       ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│       ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│       ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│       ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│       ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│       ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│       ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│       ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│       ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│       ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│       ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│       ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│       ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│       ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│       ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│       ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│       ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│       ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│       ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│       ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│       └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
└── blob
    ├── 00001bfd1808c32980ec7595434343e1f22a0b4f.nq.gz
    ├── 001d682302fc4e21c7a261c7fbf27efb2e542104.nq.gz
    ├── 00309b7f303a0580582a3a4411db0e24200ce6cb.nq.gz
    ├── 0030b8be2a2209d196109232f2fafa63fd64544a.nq.gz
    ├── 0040bb276de524b02054cdf73ad1d21992c8955f.nq.gz
    ├── 00518e867d812e9e1f645eb08efd9ab738eab5f1.nq.gz
    ├── 00528850d3592c7c6a5a5334da9733d9dedac49b.nq.gz
    ├── 00621b5199662705e211e7838e215403e37986ff.nq.gz
    ├── 00626c343263372df21d8859e2e1b8aadb2e6501.nq.gz
    ├── 00627118d3a7b537afa5c567d9698ddae2d4599a.nq.gz
    ├── 0063cc853fd60e3b3be3e22df9f12d5a7a1b11cd.nq.gz
    ├── 00662441747c76644f53dafbb992446e5ecea2e5.nq.gz
    ├── 007a60c55c10f06af257cad0b88d0fa4d7c48fdf.nq.gz
    ├── 007bb651b29a37de8b39779753d3e331901cd07b.nq.gz
    ├── 008a0dd910d41625bc3a0c6c8ca09b330f38da66.nq.gz
    ├── 008a330a24988bde609140ebb58ae62c7cde6b18.nq.gz
    ├── 009774b262644c6af69021c3e786c8a984546272.nq.gz
    ├── 00a6eb51169422cf0d01ddebb888a61a4abed6e4.nq.gz
    ├── 00a7582c21f40404b1bd2e28ca07a736ce43fae1.nq.gz
    ├── 00bd0bcb0b7f45acf040f6d640757ad6fd61e504.nq.gz
    ├── 00cf914923f3cf3eb76743c543e4a618a7ea4d43.nq.gz
    ├── 00df6c825fc73276546b71f3d3ee5af5dc4815ab.nq.gz
    ├── 00eca8008d3fa5be2280f3d7fd4324597f0d9cdc.nq.gz
    ├── 00ee2705f087badce54a0f99eb45c9dad7d00501.nq.gz
    ├── 0107b02ede3ec8d688d58488e2058b13a5d70987.nq.gz
    ├── 010c46fc20eef07636c892ac8dfc85bada70affb.nq.gz
    ├── 010e1a39a47443e1c76baa8c263e2257d4de389a.nq.gz
    ├── 01385dcdaa32dad6fa4e370db9b2de00bd3de230.nq.gz
    ├── 014024777a83a631837d7aa38abe0cef7052da3b.nq.gz
    ├── 014e4c2019f880a4bd9cc730bcaa96a2548aafeb.nq.gz
    ├── 014e887c19095ebd1bb6e64dc4c52cae5290a523.nq.gz
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
    ├── 01b04440165a118800f7ed5440be2f4338c30520.nq.gz
    ├── 01bcd9fc78fa09cc3f3ff39e9bef53d31ec6dbbd.nq.gz
    ├── 01ccc73ef45a64ae2031bd4c2b3bcdaccd73b111.nq.gz
    ├── 01e27541cada3d677ab2610db2414be8b303fc2b.nq.gz
    ├── 01e8377d268304677b4a5d133fc3a218be9a78df.nq.gz
    ├── 01ed2893cd600945dd5bbbcc71d03dcb82134557.nq.gz
    ├── 01fb255928f28b3c4640c29117003de6ca501d5f.nq.gz
    ├── 020469747a1c09de6caf9ccff1d6bda48c5ea6a8.nq.gz
    ├── 021997af39ea24deca26c6173acdf9fd02670333.nq.gz
    ├── 02227f583d560f3726ea023f1dc968ed2e94cdee.nq.gz
    ├── 0262029758d2b758c3c215a31aebae986f9efe89.nq.gz
    ├── 0262b02440400e016fccb047ed5251ea53c0efc4.nq.gz
    ├── 0266e5758f76d7b078f01fa4e049c0edbffeb50c.nq.gz
    ├── 026aaf8c4400ce77c012d5f91c6d8ee6d7892549.nq.gz
    ├── 026c85655bf4ba6772e4fd425325b44b7707c23b.nq.gz
    ├── 028288d5c05c5d1fc6f02e01d45eacc235675d2a.nq.gz
    ├── 028821a8d04d80164c6f0d6b3a46476edec3f5d7.nq.gz
    ├── 028f4dc812b06b767f3fdfbc2f56f8977a296327.nq.gz
    ├── 02991e3eb970390cf07733c7c0d916ef0af4bcdb.nq.gz
    ├── 02a4bd7b73b6eb2bf4ec22d5483076fc89b6456e.nq.gz
    ├── 02ab29eb29b5f79fcd73ec85f19cba2b8e410d1a.nq.gz
    ├── 02ad1ec03fb2249db34ea89f870d197f097b5c2f.nq.gz
    ├── 02b16c4f862d93c9ac3fbe571340272ae771dea3.nq.gz
    ├── 02bdf9cff13ffdf7c7a1aa38490bfc023dc2ba9f.nq.gz
    ├── 02d449971065e8f111b34850deb067dfaaab7e6a.nq.gz
    ├── 02d7470e9e4878528981889500ab00a1f15eb225.nq.gz
    ├── 02e06348a39cf28708ca40c8cfd5b73b7e401451.nq.gz
    ├── 02e980ea4fd5ba1d2a8c41c74efe4dd92f56d734.nq.gz
    ├── 02ea095b53455ee0138753173fe4e68c5b19d2be.nq.gz
    ├── 02f1c468bca9d74cfbcd341064fbc40d244de782.nq.gz
    ├── 02fa6535d2b98f94fdf6cc0e654949ffa253d0dd.nq.gz
    ├── 03035fef0b2fcd16dd3c977bd9bbcb0f1e3e669f.nq.gz
    ├── 0306f9771336766cd97e0218860547020b27fe23.nq.gz
    ├── 0311cf3faf0d86046c94d745514fcce9b6b1bcc6.nq.gz
    ├── 0316d13f6f6fc3be1204f39c7c319b7fb4890e48.nq.gz
    ├── 0320331371eeb7194e17fb743b908c318b086328.nq.gz
    ├── 0334f7c581f082dcbbe5e8fc6d2fa184184c6eea.nq.gz
    ├── 033df5fb60d73b2e9b7a51436be920e2b6974960.nq.gz
    ├── 034040844716d0b66fb00fef1a835dfd46361b99.nq.gz
    ├── 036ec20d21f471ec8da7fa134c5acbcc6d322ed0.nq.gz
    ├── 039cd2d99758056cd8e5054d8dfdc773c54ad50a.nq.gz
    ├── 03a5b7444bb8e9ac6b34b87a942a141db5975dc1.nq.gz
    ├── 03b7f0367de70d9f5327dab90ac254992e2683da.nq.gz
    └── 03ba7f350774605e7c59bb8c6d02ca024c29f2a4.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
