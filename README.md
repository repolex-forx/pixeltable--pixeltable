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
│   │   ├── 0bd49ac3a30aea6e7e5c55f3fdab5917e1b80f21.nq.gz
│   │   ├── 1459dd6468d769866167871cf79da06d3a4e5fb5.nq.gz
│   │   ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2865df6dd7e64a8dfdaf25ae3f273875187f559c.nq.gz
│   │   ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│   │   ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 46558bbb6b2cf78eeeaa3ad2eb847f1e8f752808.nq.gz
│   │   ├── 497762988e677b442ea856be14440e420462a575.nq.gz
│   │   ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 5234584d48b1f29a60ca60c9165c60517cb339c7.nq.gz
│   │   ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 5811cb9d62d47c2e2e739c56bcb0e5bb604f8353.nq.gz
│   │   ├── 65da3ac39f7a00f0c748bae8a807adef41caffd8.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 708020cb2ce8b71368c7050462b911d369f77c11.nq.gz
│   │   ├── 741a7d4d72a763ae996ff7f12646e52fe1765850.nq.gz
│   │   ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│   │   ├── 8be3197c7aa8198eb4fd107002c5a2f54186d5ce.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── 9c84d61dab3cf5e4451e0728754f49405cba55ff.nq.gz
│   │   ├── a1e464de3d323610d8f992d03ba705e957f123ec.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a7b58ffcb74824b074bb27ce109243819c2db13c.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── bcb28ed1ed79e2a3e9069b239f4831d062183034.nq.gz
│   │   ├── beef27a301850e6f3b6473e26b3b28b7f518e5d7.nq.gz
│   │   ├── c2e5008dcec75f29b473e7c01b8ce59c8e10171a.nq.gz
│   │   ├── cae669fce14ebf12d069de809456a3d4915c50da.nq.gz
│   │   ├── ce7a5d0de17208767d3841cbd3f4da3a20e0b12c.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│   │   ├── db7c6edc845cadd0db43554943e46456f0f9c60f.nq.gz
│   │   ├── debc40460411730150058c45fdaadbed0d095396.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   ├── f5ea33b843198820f8a9bf8026b523cb8904304b.nq.gz
│   │   ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   │   └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
│   ├── lsp
│   │   ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│   │   ├── 0bd49ac3a30aea6e7e5c55f3fdab5917e1b80f21.nq.gz
│   │   ├── 1459dd6468d769866167871cf79da06d3a4e5fb5.nq.gz
│   │   ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│   │   ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│   │   ├── 2865df6dd7e64a8dfdaf25ae3f273875187f559c.nq.gz
│   │   ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│   │   ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│   │   ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│   │   ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│   │   ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│   │   ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│   │   ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│   │   ├── 46558bbb6b2cf78eeeaa3ad2eb847f1e8f752808.nq.gz
│   │   ├── 497762988e677b442ea856be14440e420462a575.nq.gz
│   │   ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│   │   ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│   │   ├── 5234584d48b1f29a60ca60c9165c60517cb339c7.nq.gz
│   │   ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│   │   ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│   │   ├── 5811cb9d62d47c2e2e739c56bcb0e5bb604f8353.nq.gz
│   │   ├── 65da3ac39f7a00f0c748bae8a807adef41caffd8.nq.gz
│   │   ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│   │   ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│   │   ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│   │   ├── 708020cb2ce8b71368c7050462b911d369f77c11.nq.gz
│   │   ├── 741a7d4d72a763ae996ff7f12646e52fe1765850.nq.gz
│   │   ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│   │   ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│   │   ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│   │   ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│   │   ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│   │   ├── 8be3197c7aa8198eb4fd107002c5a2f54186d5ce.nq.gz
│   │   ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│   │   ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│   │   ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   │   ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│   │   ├── 9c84d61dab3cf5e4451e0728754f49405cba55ff.nq.gz
│   │   ├── a1e464de3d323610d8f992d03ba705e957f123ec.nq.gz
│   │   ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│   │   ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│   │   ├── a7b58ffcb74824b074bb27ce109243819c2db13c.nq.gz
│   │   ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│   │   ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│   │   ├── bcb28ed1ed79e2a3e9069b239f4831d062183034.nq.gz
│   │   ├── beef27a301850e6f3b6473e26b3b28b7f518e5d7.nq.gz
│   │   ├── c2e5008dcec75f29b473e7c01b8ce59c8e10171a.nq.gz
│   │   ├── cae669fce14ebf12d069de809456a3d4915c50da.nq.gz
│   │   ├── ce7a5d0de17208767d3841cbd3f4da3a20e0b12c.nq.gz
│   │   ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│   │   ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│   │   ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│   │   ├── db7c6edc845cadd0db43554943e46456f0f9c60f.nq.gz
│   │   ├── debc40460411730150058c45fdaadbed0d095396.nq.gz
│   │   ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│   │   ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│   │   ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│   │   ├── f5ea33b843198820f8a9bf8026b523cb8904304b.nq.gz
│   │   ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│   │   └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
│   └── repolex
│       ├── 07e73e981ca77a520f1f15b8cd751f6aa7081ef1.nq.gz
│       ├── 0bd49ac3a30aea6e7e5c55f3fdab5917e1b80f21.nq.gz
│       ├── 1459dd6468d769866167871cf79da06d3a4e5fb5.nq.gz
│       ├── 16d5ca165322551a0b2e0e22a96b25a662d282d5.nq.gz
│       ├── 27f2f33cfee46a237c18bf671c83477c868d0946.nq.gz
│       ├── 2865df6dd7e64a8dfdaf25ae3f273875187f559c.nq.gz
│       ├── 2ccf87a549f24e3b531d4d10e0fa9525f305cfb8.nq.gz
│       ├── 2faabe919ccd40695d00608a3b453d88a963fb1b.nq.gz
│       ├── 30c7bb045b45d94999269c93272b351448962cf2.nq.gz
│       ├── 330065da251dbc193b559d561c255f1f31d2c73e.nq.gz
│       ├── 3511b87ce19f1fc85635a7c3f92150c1a3d582bd.nq.gz
│       ├── 39b822cf5019582a8b45cab2c52bfcbf00583dca.nq.gz
│       ├── 3f055c3bafc7946a8846b6a588f8ccf5cf0ba03b.nq.gz
│       ├── 46558bbb6b2cf78eeeaa3ad2eb847f1e8f752808.nq.gz
│       ├── 497762988e677b442ea856be14440e420462a575.nq.gz
│       ├── 4ced0d7ffaa88166207ece6cbae9e65e2be8e6de.nq.gz
│       ├── 5156928447daae5e0cb830dee1ca147fdf92cac6.nq.gz
│       ├── 5234584d48b1f29a60ca60c9165c60517cb339c7.nq.gz
│       ├── 555c6d8ba7897f05162fe9146b3f539016efb6f5.nq.gz
│       ├── 566ea71b45c93dddd636fd8e44b957568fdae587.nq.gz
│       ├── 5811cb9d62d47c2e2e739c56bcb0e5bb604f8353.nq.gz
│       ├── 65da3ac39f7a00f0c748bae8a807adef41caffd8.nq.gz
│       ├── 678484b84813553381036eed752673796755bd5f.nq.gz
│       ├── 68548d3afeb10b0d9f8479d2925b168fd9f4f140.nq.gz
│       ├── 6cdece3c3f6ecde147bacc0e443ef0293f6f5c55.nq.gz
│       ├── 708020cb2ce8b71368c7050462b911d369f77c11.nq.gz
│       ├── 741a7d4d72a763ae996ff7f12646e52fe1765850.nq.gz
│       ├── 75275ece7ee7b941d500fe75be8ca66d749a558d.nq.gz
│       ├── 772113a5a218e606d7f95844be70d4bc337bf657.nq.gz
│       ├── 7ca325567076f516ea2514e3510f5d7c03e32f34.nq.gz
│       ├── 8048cbe8c941f14f6da9d96c6622db7813b31f2d.nq.gz
│       ├── 8a01cbeccef1bbcba1d8a37582d462ec9a792663.nq.gz
│       ├── 8be3197c7aa8198eb4fd107002c5a2f54186d5ce.nq.gz
│       ├── 8c9eda17dad6bd902d9e13bc1092bbc6ef0cd0f1.nq.gz
│       ├── 8f267418faa8a3c0380f8d0d311bcb72aa0064eb.nq.gz
│       ├── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│       ├── 98258fb004ab51ea06bc27fb62f4cc9109c189c0.nq.gz
│       ├── 9c84d61dab3cf5e4451e0728754f49405cba55ff.nq.gz
│       ├── a1e464de3d323610d8f992d03ba705e957f123ec.nq.gz
│       ├── a420c077b3d10def9ba36a461375fe85c27f3ea8.nq.gz
│       ├── a6645e16ea13a333be916682b053ac45e857169f.nq.gz
│       ├── a7b58ffcb74824b074bb27ce109243819c2db13c.nq.gz
│       ├── a8d526053927a1cff790cf5ee16aceb6b518391a.nq.gz
│       ├── b0e06b29bb85f335731612f3e8190c68f689ecab.nq.gz
│       ├── bcb28ed1ed79e2a3e9069b239f4831d062183034.nq.gz
│       ├── beef27a301850e6f3b6473e26b3b28b7f518e5d7.nq.gz
│       ├── c2e5008dcec75f29b473e7c01b8ce59c8e10171a.nq.gz
│       ├── cae669fce14ebf12d069de809456a3d4915c50da.nq.gz
│       ├── ce7a5d0de17208767d3841cbd3f4da3a20e0b12c.nq.gz
│       ├── d195e6b909795b476dc649b262b89b08929ef5ee.nq.gz
│       ├── d1c3cd5483b89c73669fc542d71f0957a771a15f.nq.gz
│       ├── d51c73b58254b4f9cf0e046652f14583a29a7dba.nq.gz
│       ├── db7c6edc845cadd0db43554943e46456f0f9c60f.nq.gz
│       ├── debc40460411730150058c45fdaadbed0d095396.nq.gz
│       ├── e11199ccf22dfa2b4b0fe0ac90ad6b9481754de1.nq.gz
│       ├── e9366a37ea432829e4b2f6568d506dc7afc81059.nq.gz
│       ├── f54ba0cee9ad82efe5e514c51f3226ad9d38b400.nq.gz
│       ├── f5ea33b843198820f8a9bf8026b523cb8904304b.nq.gz
│       ├── f9246bba7a67faa74f331971faf97bf0fa6e04bf.nq.gz
│       └── f99b389b008fa10a2e226aa0a5c58692d5fdd871.nq.gz
└── blob
    ├── 00001bfd1808c32980ec7595434343e1f22a0b4f.nq.gz
    ├── 0013da44b8a5fc20109705a6377342c773cf49d6.nq.gz
    ├── 001d682302fc4e21c7a261c7fbf27efb2e542104.nq.gz
    ├── 00302794ef89f0a3a0f45c2e1381adea9716bd9b.nq.gz
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
    └── 00a6eb51169422cf0d01ddebb888a61a4abed6e4.nq.gz

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
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
