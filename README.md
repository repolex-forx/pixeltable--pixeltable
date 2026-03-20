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
│   │   └── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   ├── lsp
│   │   └── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
│   └── repolex
│       └── 92fd27db8bd39edd5f19601ecd340ccde197fca0.nq.gz
└── blob
    ├── 00001bfd1808c32980ec7595434343e1f22a0b4f.nq.gz
    ├── 0040bb276de524b02054cdf73ad1d21992c8955f.nq.gz
    ├── 00528850d3592c7c6a5a5334da9733d9dedac49b.nq.gz
    ├── 00621b5199662705e211e7838e215403e37986ff.nq.gz
    ├── 00627118d3a7b537afa5c567d9698ddae2d4599a.nq.gz
    ├── 0063cc853fd60e3b3be3e22df9f12d5a7a1b11cd.nq.gz
    ├── 007a60c55c10f06af257cad0b88d0fa4d7c48fdf.nq.gz
    ├── 00bd0bcb0b7f45acf040f6d640757ad6fd61e504.nq.gz
    ├── 00df6c825fc73276546b71f3d3ee5af5dc4815ab.nq.gz
    ├── 0107b02ede3ec8d688d58488e2058b13a5d70987.nq.gz
    ├── 01385dcdaa32dad6fa4e370db9b2de00bd3de230.nq.gz
    ├── 014feb69b4e9aab17fdbb73b49c9e9f0d162fcff.nq.gz
    ├── 0163e9e6d0d5c3618cf53c75ed8405e3750a6fa5.nq.gz
    ├── 0188d770f778b12067dcd951603e78ca18461738.nq.gz
    ├── 0196dd14136a5a133ee0268f50c15bcb7bfa3495.nq.gz
    ├── 01a043c63072f1b27a32ca2461b9393b9e95c9ff.nq.gz
    ├── 01bcd9fc78fa09cc3f3ff39e9bef53d31ec6dbbd.nq.gz
    ├── 01e8377d268304677b4a5d133fc3a218be9a78df.nq.gz
    ├── 01ed2893cd600945dd5bbbcc71d03dcb82134557.nq.gz
    ├── 020469747a1c09de6caf9ccff1d6bda48c5ea6a8.nq.gz
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
    ├── 02e980ea4fd5ba1d2a8c41c74efe4dd92f56d734.nq.gz
    ├── 02fa6535d2b98f94fdf6cc0e654949ffa253d0dd.nq.gz
    ├── 03035fef0b2fcd16dd3c977bd9bbcb0f1e3e669f.nq.gz
    ├── 0320331371eeb7194e17fb743b908c318b086328.nq.gz
    ├── 0334f7c581f082dcbbe5e8fc6d2fa184184c6eea.nq.gz
    ├── 033df5fb60d73b2e9b7a51436be920e2b6974960.nq.gz
    ├── 034040844716d0b66fb00fef1a835dfd46361b99.nq.gz
    ├── 036ec20d21f471ec8da7fa134c5acbcc6d322ed0.nq.gz
    ├── 03a5b7444bb8e9ac6b34b87a942a141db5975dc1.nq.gz
    ├── 03bfd0f7a73120dca57e0df037193878cf6ff266.nq.gz
    ├── 03c4c40f6ce55c4c2068dcca11857c6e4cf6c300.nq.gz
    ├── 03dc35c683dc012ba922c080c65b97514ee244ad.nq.gz
    ├── 03e08cdcc812d40ebd1d7a179eb7957b612f9873.nq.gz
    ├── 03ecbf9d7d17fadf1fe8e4cc770b9e8441ee7715.nq.gz
    ├── 03f6b9adca136ac89501fb221b19153b28ab1af9.nq.gz
    ├── 04045ba18eb66fd93488e47ef9ef90be1655ec8e.nq.gz
    ├── 042d179157f8374ca9c77208cce4fdec0b040063.nq.gz
    ├── 04312e515b33b54bdef7b56761d8eab21dbd61f9.nq.gz
    ├── 044934ebf22610836d0c4bcadfb587235ae3193d.nq.gz
    ├── 046fceff270405d96e32a9ae8f92594c4215907f.nq.gz
    ├── 047fc042166c7ec3f84f2633a9622907afb7938a.nq.gz
    ├── 04952b7214e56c2ebcf73dad456424c0b3211190.nq.gz
    ├── 049b80efc273612720764e0e2e34ea86d2e9a8e6.nq.gz
    ├── 04ba2f16444d0e896a3747fae5019be177457271.nq.gz
    ├── 0501b8314a0c64766475253acd05b7038b6e3609.nq.gz
    ├── 0519ecba6ea913e21689ec692e81e9e4973fbf73.nq.gz
    ├── 05734f3289d24b1d2cec63f65216fb9b1894e7b4.nq.gz
    ├── 05896ff1a80ac16941120bc2bf884a3ca732d03c.nq.gz
    ├── 05a118d05acabe401d425175f14b4ed0fb0c201b.nq.gz
    ├── 05bb7c38aee33e07b44d7ec4de45d6ab65039bea.nq.gz
    ├── 05c32b2126c4eaf6f904f658291f2c56a4519c88.nq.gz
    ├── 0606637548f985916eaecdecb8a06e01a64c2ceb.nq.gz
    ├── 0608a35d5b5562508c939f68bb01647222026992.nq.gz
    ├── 061206dd4ce37dcba3e45ea556bd3e6177fe5589.nq.gz
    ├── 0617adbb0445bc257093697630e1bfae6c23b4d7.nq.gz
    ├── 062536e38b9ee72a90c04dd398997ba1022bb6d8.nq.gz
    ├── 063df18c4df38d0ed3cd52aa69c79336b9a8ca53.nq.gz
    ├── 06677ca33523806030d876587ca64a4581773865.nq.gz
    ├── 06ab20827d95a0dbfa00b09a1250da8b2be67ed9.nq.gz
    ├── 06b20d2b228ce80a788cecdba80eede22554908e.nq.gz
    ├── 06fac3be4213cea1d0a731099024136df5c65789.nq.gz
    ├── 06fb2e043efb7a9b3f9918a0ddde5f69ea2626ed.nq.gz
    ├── 06fd08b9be478d20cb9862b56887722954676d05.nq.gz
    ├── 0727f4fb9dce78a5746518ace4e165c8fda3f7d7.nq.gz
    ├── 072b1d1d08d945fdff5d474d948928292e45f95f.nq.gz
    ├── 07669d720fa8f1611fe14c0af4cad08bfa765ea9.nq.gz
    ├── 076e90fb02c3479983b245da766e17d2b56c271f.nq.gz
    ├── 0779fe264aaf123a1bb1d2f088ccd69c11728ff0.nq.gz
    ├── 078c2c724692cc736b9d36443168c8df4e593610.nq.gz
    ├── 0793979a41de99ea4a42cf7b98d942384a94940f.nq.gz
    ├── 07ba220bb765d81a9398eda706dd76243cf3626e.nq.gz
    ├── 07d454475120c53201ed0a5279cfee4568197f34.nq.gz
    ├── 07efe5c1a616f95c6715bc70b552870f68d52708.nq.gz
    ├── 07ff2605e4bb61b5d16f9959d895c5846df81882.nq.gz
    ├── 08031bc68c13e223ab0dfbc4369bd248313c86bd.nq.gz
    ├── 0815e0460e4e49f76637a4edcb17f7a08899eeec.nq.gz
    ├── 082d678223030fbd0ff142d42eb80f0e8e930d65.nq.gz
    ├── 0844add7de1a1675fda40aa1b598fbea158cd3fc.nq.gz
    ├── 08573cbcb3a6dff58ae6f7850dc0c0a9668a82bd.nq.gz
    ├── 0864cf48e597135b651fbc8ea91227953ab23e13.nq.gz
    ├── 087b52921ea167c699cf852448dacbb3f65a32c0.nq.gz
    ├── 08afe4b9ab5203cadf4970e077d25fb9c70fe8db.nq.gz
    ├── 08b774400804de1f8b2eb09daf4fff0a2ae68c8f.nq.gz
    ├── 08b8928634c00a99c35f1660a368e111616c3a29.nq.gz
    ├── 08c060655d7a2cf8d33cf6cfc66ad3c95b907ed1.nq.gz
    ├── 08dd042519ebfcc71551f817a1b9c1ad06048026.nq.gz
    ├── 091597f6dd6eaa9986b9bd6929613f5a231e8f37.nq.gz
    ├── 092490efd79834e0650de6d899f2dea9e3139361.nq.gz
    ├── 094a75d477c5a70bdd8942ec6d5e2898fff094d9.nq.gz
    ├── 095789ab57837214c8ead2a2d3fa18568cf53098.nq.gz
    ├── 09776741171426e20a3a3c57c7dac0c5ea07375a.nq.gz
    ├── 09b4b0809df8fee1774367529bd9e600f5a7820a.nq.gz
    ├── 09d9e03dff0e840dfa6a850cfb2de5a701348190.nq.gz
    ├── 09e266c73c605b63ed09aef74dd0970a9d10a149.nq.gz
    ├── 09f4f7ce66f6d019c9446065c00616dfe2ef58da.nq.gz
    ├── 0a01c457c28943087a646e07840089ac6031b03b.nq.gz
    ├── 0a1e69441dfe5125b5da8b482f409e09c1417316.nq.gz
    ├── 0a36a06a560e494ee43017f4e42b627d134ac328.nq.gz
    ├── 0a3d34a6e5e0e477199305ef5ff164838b59ef3a.nq.gz
    ├── 0a5ecc1e1e9bfae42161cae7d6ed78e776e596ce.nq.gz
    ├── 0a75f40b2a92bdef7f0325bad5e53611681db158.nq.gz
    ├── 0ac6110e099f2891d115975667ad334a174accc9.nq.gz
    ├── 0ac9d15e1d3622f394b07b253999e8865e87574a.nq.gz
    ├── 0ad45486d9c35308953d9ec6dd169ac20c31fd65.nq.gz
    ├── 0b3e49e9bd0e5ae246bf9b564acbe5397219afcc.nq.gz
    ├── 0b418dfc24fea3c8c3c50ac1937b18cd8208addf.nq.gz
    ├── 0b5eb246dc71cb13f98298e6417d5522e3d78da0.nq.gz
    ├── 0b665c803df5e95e9b006d59fe75c4c345de1a01.nq.gz
    ├── 0b8742d0fcf4c37d1e0d499dc00697cefb81aa3e.nq.gz
    ├── 0b9d27a412ccdddea3aa3b3117b14096d55c32fa.nq.gz
    ├── 0bc40f2681f0e47362eb21181d9223f2ba5105b2.nq.gz
    ├── 0bdf6a4bdead31af26df999827f5b3f3a3f7ad0e.nq.gz
    ├── 0bf2a4c08d54d329e2a37be6747768bac18f68ea.nq.gz
    ├── 0bf8852e62d508fd12bbc791ac2f3bd6b753d403.nq.gz
    ├── 0c21a73ca2f6c047e1b2d8c08b0a3aa0e0d41a5e.nq.gz
    ├── 0c4132b07875bcf927400547751306d1ee0791b5.nq.gz
    ├── 0c48df557f0ced59acf9a9c206992344ba9a3df9.nq.gz
    ├── 0c4de0fa3df768fbe01e8c7e11d63096ef861530.nq.gz
    ├── 0c50a31bece3cd5b03ddc74b723c353d924ee267.nq.gz
    ├── 0c6205ea0eeb8dc5fc8332a4c40bbac62e740362.nq.gz
    ├── 0c67e98b79777ff7983ed21fa84be716dd458dd5.nq.gz
    ├── 0c74d78f1f34168eb8f2d05b21bcec9cd5ae4bc8.nq.gz
    ├── 0c755f0b2a7d729482c0f4ee6c4e46a372ccf645.nq.gz
    ├── 0c81ece3525500ecf33ddb86498c82c4718d307a.nq.gz
    ├── 0c903079270a0f93f67c9e7b5a531aaecb3eea32.nq.gz
    ├── 0c99211e52c3de0ed90001e649032af808d6c54e.nq.gz
    ├── 0cb1d4da689032c8af61733fdfc55468d6cdf4c5.nq.gz
    ├── 0cca40a73d3c282558f0ace7b856c1eb67f9958a.nq.gz
    ├── 0cefb9e1c491c5381311e69f61a68f7d6e869176.nq.gz
    ├── 0cf0ead2884d63a016449dc99c4cc01e2854b0f2.nq.gz
    ├── 0d0230d2dc39294b60fec1df1e866b15e5507b50.nq.gz
    ├── 0d1520b33f5ba7b9056fdb2eca9bad91e0881e2c.nq.gz
    ├── 0d287afa7af5bc1bbf7da0574147dfa0e067a9bd.nq.gz
    ├── 0d3405a7e51fd56eecf02732b0f5c69ac8667dad.nq.gz
    ├── 0d3cb36be8a593f7e53db8dbbffa77f6ec5f7097.nq.gz
    ├── 0d4d2942705ca66407a5bbd82aecc82285faf56b.nq.gz
    ├── 0d58749e48eab97447f9035deb6851afbbd8ff7d.nq.gz
    ├── 0d612acd789f92be591dc525b44c70d8bc4c0f1f.nq.gz
    ├── 0d676b45f24f58a00e24cc7c0719e505fd2c010d.nq.gz
    ├── 0d7d5849da885332a6277518ec7b7fe8cbe1bd2b.nq.gz
    ├── 0d9ed64f928c95a28edb2ad587eef7211aa2698c.nq.gz
    ├── 0da93ce9c507b35579d055fd5874c3b3317fa3f0.nq.gz
    ├── 0daa5471cae63ed98ecda0febf94f54b30826cb4.nq.gz
    ├── 0e0f1b8fcc88f8c2257747ebccee4ba8eaedaee6.nq.gz
    ├── 0e154e7f50822148bf8f907f614fb08a53bbb80d.nq.gz
    ├── 0e52737089fd939df8be97d615e103b99d0bdd97.nq.gz
    ├── 0e700a0cafa30c6b44c7028e9279186b5884e523.nq.gz
    ├── 0e7c0bed31d35318bc934f025c09b442a2c5f396.nq.gz
    ├── 0e7f3cbad95197cbbbb4a1afb50d9dc119150253.nq.gz
    ├── 0e97f6a24165e3ce92b59a15a2ddd99b3c6a7dfd.nq.gz
    ├── 0eab5e5700501d9b2136f9f7cdcf39e37a8dbf5f.nq.gz
    ├── 0eba6eeccdcf60b9a0a9e3c98038789f32c9ed72.nq.gz
    ├── 0ec9a81a7b1027f3ceeabad10ac2088c390cc05c.nq.gz
    ├── 0ee6f6665a786a8bfe87ea3680606d909651c5a8.nq.gz
    ├── 0eed50087513ee3e64c01892119f9fe31ec5ffc4.nq.gz
    ├── 0ef7c33a73e0aa9150122fb724fe748535b75ec5.nq.gz
    ├── 0efb36cb020ad41db81732efdbf6de5b0394f624.nq.gz
    ├── 0f2451961c4a9f4d0ea3985b9c81e7dbfed01cf4.nq.gz
    ├── 0f25180184fe475f4b8e9abc8be0cb4ec70292a1.nq.gz
    ├── 0f52a20e0ac23893eed1ec3566cb7ce3dc9c92d7.nq.gz
    ├── 0f6469d8d79d0bf40b469ff184a5001b463b2304.nq.gz
    ├── 0f69b6b68c4c673089893e734fdf75202e45e93a.nq.gz
    ├── 0f6fbf0608df8cc0ab1f036673d7098dc4ce7fcf.nq.gz
    ├── 0f7ea05a888de85cc9e4f074c321a57cdbab2387.nq.gz
    ├── 0fab2ef4d6d40c5eb20a54b0582977ff0490730a.nq.gz
    ├── 0fecd20122ae04cda98633de59a0ac42d37da65e.nq.gz
    ├── 0ff9e4f954738d2e14f61e4805a61e44079fb264.nq.gz
    ├── 101c98afe79a77a9487736ccb574bce39daa30e3.nq.gz
    ├── 104791e2cdbd81b7bbaf6efbb9a746b57a4e1e41.nq.gz
    ├── 104f73711e8f8991fccde0dacae3e9a673c452ba.nq.gz
    ├── 105ce2da2d6447d11dfe32bfb846c3d5b199fc99.nq.gz
    ├── 10674f9d590e8741f2f83707ea48f4aa92bce5d1.nq.gz
    ├── 10849ace76c781043e169a67e0631eeb1c5009db.nq.gz
    ├── 109028fb6d41351ee474dd8dc0e6c7f54f8e4758.nq.gz
    ├── 109603975cb3c41fe340b7d55d9789c723e4607c.nq.gz
    ├── 1097b907b68211bd135a0bd8d1a0eda78f30ea53.nq.gz
    ├── 10a52c1f6b4dcc3e453d097f655b678885d02a7c.nq.gz
    ├── 10ba34333dce6bbea4a26bc3d25b4998d5ddeace.nq.gz
    ├── 10ce5c2739ef3dff0116da09b5d61941106448df.nq.gz
    ├── 10d4642ee254e9c1530837763eee65eb51567d37.nq.gz
    ├── 10e86a03d7c784aa9b66a5ce62034a3b6fdb10a1.nq.gz
    ├── 10f3e85b749db14a67d00b57f9bc2d7b793739b1.nq.gz
    ├── 1102da99fc5a566949b7fc60b2faa98dba78ba5f.nq.gz
    ├── 113d39f102130cb91bddf2da137f19bec5d1258d.nq.gz
    ├── 116c9b2f07885447e9616847b2fee607d87a43bf.nq.gz
    └── 1179afcc553dc0e0d7ba2c59b6079d02fd94501b.nq.gz

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
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
