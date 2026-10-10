# Repolex Knowledge Graph of vllm-project/humming

RDF knowledge graph data for [vllm-project/humming](https://github.com/vllm-project/humming), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download vllm-project/humming
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f08e744fb1e7f11ee72413a4aebf1143e2d3512d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f08e744fb1e7f11ee72413a4aebf1143e2d3512d
│           └── chunk-001.nq.gz
└── blob
    ├── 00341c7dcef24a0c9505f0ffd7f2791b84854b41.nq.gz
    ├── 007ab71d6312c18d9fe34793633c9cb2a6e02166.nq.gz
    ├── 01505ce318e166bc882fad3af9de0ab36a404399.nq.gz
    ├── 01a90c3efd96c293f87c6f8bfa8d92eda22e83a5.nq.gz
    ├── 023978da3543d661e8fa7ea9e845c9beea0418d7.nq.gz
    ├── 026200109cf1d09db228379ee4324f3171f5c595.nq.gz
    ├── 02ad689bc633dd5e5fa16b6c9723c9edeb24cb51.nq.gz
    ├── 03c6bebdd4c93802502fb92f3c9d551c9fae9fcf.nq.gz
    ├── 049c9d4f26fee3a0561cf80510e646a7fd425f9f.nq.gz
    ├── 04ed8fab3bba652be7723d3ca4800ba5c58ac879.nq.gz
    ├── 04f95d53bd3c3f5e15cea612f792666fcbc079dd.nq.gz
    ├── 067ca68a346c0b43da4c47b3687f6afcafefec00.nq.gz
    ├── 068313ac3955f3125e6648eb5f0bc76500a678c8.nq.gz
    ├── 06bf0a47bfc964d10050916c25ea6fd722e2a4b2.nq.gz
    ├── 074333c400aced46e3c02aa2bc0ff6f4f09a6f85.nq.gz
    ├── 074761d3d8cf87d035ab6e89cc4eb345c56ee402.nq.gz
    ├── 08833aa54fffda1b40c41d5d3e245d5ccacbd28a.nq.gz
    ├── 08ea556fe039113aab7b0f04997e9777d821866e.nq.gz
    ├── 09d033f6411967dafee554c088d44aab6c81bab4.nq.gz
    ├── 0d22c7dc6012579af6e8eb52fa0577da9b483f0a.nq.gz
    ├── 0daf0a9edf2def62f5f44ba1ace15ae4b41e9fb6.nq.gz
    ├── 0e554b8b791e625be1f329377be1c79bb8cc848a.nq.gz
    ├── 0e5befa2ae3406a2445724b09139a0b6c2e3e171.nq.gz
    ├── 0e5c238ee63346bdeff96991f191d560b46779cc.nq.gz
    ├── 0f5d967887f822bc34f49909c6c193ee804ffefb.nq.gz
    ├── 0fe3d4c47a451ffc68bb94b47bff8c090aa5ac9b.nq.gz
    ├── 1049933c97535c2422ff9b879feb28ab006960b5.nq.gz
    ├── 116dd2188c9dfe5fc0e822a9bb4d3b5fda0070e8.nq.gz
    ├── 118ddb98bc47922ca51d1007e979107163803513.nq.gz
    ├── 11acae74e7e858d4602a729af1885c8c80c51ee2.nq.gz
    ├── 13d10643392165a0403dea83f4bdee7d1f76adbc.nq.gz
    ├── 148eea6b1cae8298fa7f5b50039a91fd52f18256.nq.gz
    ├── 14ce341d6386cadd3b5ee98766244397d92cb091.nq.gz
    ├── 163d18fd57bedf74af02cc1ef56d41f8a76966f7.nq.gz
    ├── 1688bd59cc0b98d1695eb1c636aed783c96c3af4.nq.gz
    ├── 17436d96eff50a108632088c2ab75e41cfbcb165.nq.gz
    ├── 17c5bd8b4b2a333d19b9aa3affd9ac5bb60b366f.nq.gz
    ├── 19b93008b2df560df5e79bc93ab1eeb741b57e97.nq.gz
    ├── 1a4fcc5a7bdb7d56e0166e758395c1cd9e384c85.nq.gz
    ├── 1b8057bb00e17c14d88802f6f309bd17a39f65ba.nq.gz
    ├── 1bf8404836578a35572807252a929bc602cbc0e2.nq.gz
    ├── 1c227f80dfccf7b402240d6a141e389a24a2faa2.nq.gz
    ├── 1dacc776a25fdc9a6ae4d00cb9c55b21bfe66e3a.nq.gz
    ├── 1e0119de8c24196bfe593557229a296cd5f0b896.nq.gz
    ├── 1e4ac7cb1a1e625639e3c1a247af6ef9b23cfc86.nq.gz
    ├── 1ed575b32b353b45beaf925cd0cec15921e302b6.nq.gz
    ├── 1ffdcf6cf4a2989992b0d3be40e95b304fe82f8c.nq.gz
    ├── 20731946f3c55a72af58b04e03304044bc6a970f.nq.gz
    ├── 21f8a3ba683d0749f20e122b23fce853431623fa.nq.gz
    ├── 22d87e7f0bc02db1ec52d0e6bb2795388dbd9ae5.nq.gz
    ├── 231e8082c6293e83c6cbf306bcd50742b7edd9eb.nq.gz
    ├── 23808f918f1ae0b7339865dbf1eab59fc91a42ca.nq.gz
    ├── 246a4b3954948f6e939ce9c4bea5570eab011bf0.nq.gz
    ├── 262e78813af7c36d94b50ad84332ad84bd7c9c56.nq.gz
    ├── 2642b049d9228545209b54f3be5963a64ee151a0.nq.gz
    ├── 274c6529a7cc8312d5ede4ce0c06eed5a07885e6.nq.gz
    ├── 27b62e9366b95e7505eb458af0c7b08753fed724.nq.gz
    ├── 28998f7536372b42de98ad72da7b215a264ab750.nq.gz
    ├── 28b0542a16a4f0f2088c886a2ef7a4e45a23e19f.nq.gz
    ├── 29a51b6d02583ebb77801a8d16292bf5742c3879.nq.gz
    ├── 29e888bfb31c8fba706651398e14b01a7b2dc9bc.nq.gz
    ├── 2aa43998e3bea1a364ad94e3158094de6c7a91ed.nq.gz
    ├── 2bd03ee68315df89ce3bef444d50629d554b8a26.nq.gz
    ├── 2bdd563eb1a0bdd1cdb78bc272d77554449eccd6.nq.gz
    ├── 2c0dd159d0bf41b7e72624ba1a720a79374980cd.nq.gz
    ├── 2c940243000f97f17a6d5ed37e210543b4d70f22.nq.gz
    ├── 2ce437948344761ffdc37eb8a88530f60104ffb5.nq.gz
    ├── 2e5054ab1b04df1034d2593f5ee5d09bccae02bc.nq.gz
    ├── 2f9050b201fee132085a6415805220fe7cd99b92.nq.gz
    ├── 2ffb2083469c083e46bc3a356d7f11e77770cee6.nq.gz
    ├── 30ec982b825518d99118c65579117c06ba7a3f19.nq.gz
    ├── 3113850319d4f4615fea2d4c112447e8b88bd4c7.nq.gz
    ├── 31539aec13345f357213b9c316a59fdd14ca7b01.nq.gz
    ├── 3211f315042fb9ca81eb0be16399246c6f960e04.nq.gz
    ├── 322490c6c7d109149e178ecc73c011a9202bbb8c.nq.gz
    ├── 32749e5c2c424ce82f664d8da7119c69a1f0fd7b.nq.gz
    ├── 3468c0f167907c0d9b3a9b1ba350153c77f4b167.nq.gz
    ├── 34a0dcb18794e864aa448369270281cff49f36df.nq.gz
    ├── 34fcd2b15ad8b76a89d6aaf0c06da5179b9316f0.nq.gz
    ├── 363674bdce0b21d197afcf7bc01ea89feae3955c.nq.gz
    ├── 375d83e77117193ccf6aa0a4cacbe13bffdf7a92.nq.gz
    ├── 395b095af6f550403b94d62d99d0aab90100b934.nq.gz
    ├── 39806f0c250d2be9b353856cf1bb3faed78c6df5.nq.gz
    ├── 3a2735bf513e2bca63f9a7abb9440dbc883022ba.nq.gz
    ├── 3b55a8d80e98aeece5e1ef24e3b22f78700ed683.nq.gz
    ├── 3d7b399182787e7ea64e05eb712831a487334e73.nq.gz
    ├── 3ec8516526e2ca90e7fe0a66a4e3787ecf8eeb77.nq.gz
    ├── 4039417fd39522b6d8acea4ecaaa38df71ba6d6b.nq.gz
    ├── 4173f51be68b81f9d209685142fd09e449d8b12e.nq.gz
    ├── 439887399814c48f95a14c3519aad150f4a7cf70.nq.gz
    ├── 44890e1f732b8ae34b09511bcf9052e7cb6d25dd.nq.gz
    ├── 4555b203049154050f28521328b4078554647d8f.nq.gz
    ├── 4585fb7fa8d0351d71f0ad25788a185b2b51969f.nq.gz
    ├── 45b37e0654dcbf1563c2fb3f483af8e3ba45982d.nq.gz
    ├── 46c678df03b05d4d48661e4485f53029ac0e466e.nq.gz
    ├── 48076a92de74b1457c8ae075d0aa360e308d886e.nq.gz
    ├── 49131f4eaec73b37ee65238e5a6163464b665f09.nq.gz
    ├── 4a6357389dc1da2e3f8a3c5884cbe60840574769.nq.gz
    ├── 4d7c5e4b0d2da25aec09a075af044b86c18b8b4b.nq.gz
    ├── 4f73a79e052941b55d39c88b5defd995f42ad517.nq.gz
    ├── 4fb5be0bf26fbb0ca5e1546f1a967e5f83c4e54f.nq.gz
    ├── 4ff1203d9b18e2857b2180f2d5f867919c674aaa.nq.gz
    ├── 548ab9ace5ba31bb861ac5656b597938c5e1a51e.nq.gz
    ├── 54befd0f50a25c28baab12178c575c111225fac1.nq.gz
    ├── 55172f10fb4c21ae8b0407eaac4a8c45f4195f4b.nq.gz
    ├── 554788c452df4a049c4bfa0f592cc261056fefb4.nq.gz
    ├── 5700074ea6ab1d50c40b9aaa47b61b20710742f2.nq.gz
    ├── 57bc88a15a0ee8266c259b2667e64608d3f7e292.nq.gz
    ├── 591d212c6b2cb4e237520c65382c83b06d8cf32b.nq.gz
    ├── 593bad16f1155dab54319a696e6ea9733e67f28a.nq.gz
    ├── 59802826a8e0616fee2b604ce3979e0e31975ac5.nq.gz
    ├── 59dcc7794832925693364396983afdc16843f88f.nq.gz
    ├── 5bab5c080512af7970c37937c57e4f2a3bc151cb.nq.gz
    ├── 5cddee909f44ab9bf35679e9218583a1cfb251fc.nq.gz
    ├── 5fb1f57987ff4669c18637fff879909ff64f388f.nq.gz
    ├── 5fdcc9276dacdd2a6e023b837d71f3a77223f64f.nq.gz
    ├── 60252100afd18fdd54e53e3a07fa4a01fe66d7bb.nq.gz
    ├── 61733ea39b8533081435754860b2707ece7a1ab1.nq.gz
    ├── 61a2c6aa23e97d51cda6e9ca9cfd3a010e0eab24.nq.gz
    ├── 62fe28851c2d9d9d8ff81b0d2dd8ec11711d888c.nq.gz
    ├── 642a481430879342ff6451ba18456cb8f6d367e7.nq.gz
    ├── 64471044cf771c0e9b8b65b6a18876945cbf39cb.nq.gz
    ├── 6471b1cac53c31554907b72337dec3a44fbf3100.nq.gz
    ├── 64780337101a8a797a374d366f0e1f8bedd9b4cb.nq.gz
    ├── 647eb88a3c6732f4fcf5e73cd3d0e63561930f7f.nq.gz
    ├── 662b317d34ddfd06d5d1c0316051c48df47293e3.nq.gz
    ├── 67ccf67771bf7070814ac49e93f9a90f784f67dc.nq.gz
    ├── 67d3e41dc3467be67711235c9c42e16402b216db.nq.gz
    ├── 68295d0377ee614bf13ddf87b94f3bd2db7e84ec.nq.gz
    ├── 6898f88d7f2e1f37b4ba863808a3e472c3fb6455.nq.gz
    ├── 69125d338079153025908baadd8a893ace8c3827.nq.gz
    ├── 69cdd454ec717a735fb58c710e54d6394438aa46.nq.gz
    ├── 6b35f4ec8aa56eafc6a0293bb91753281e934fd4.nq.gz
    ├── 6b470a7c71699de072ce07004b23d5cf2635895a.nq.gz
    ├── 6b579e6fe4c7d2528795f80cef8e7f233bd09b93.nq.gz
    ├── 6b8fd33371e7cb877a0d194633cf48707b597a75.nq.gz
    ├── 6ed158159adbf0a4095a3e8d1bba631d5fdbd5b9.nq.gz
    ├── 6f1fa4d51dba86081bfabe4647cc14f04fbd6a28.nq.gz
    ├── 6f7d88b811d34a46becbc34adbfd90d31cc7a539.nq.gz
    ├── 70357f8562d2c4c4c17fef2c882a6e8968510e08.nq.gz
    ├── 7183a00402cc6e3e573bbc6686f0408c9bb5a004.nq.gz
    ├── 726bd79892d35690e9dea5e9678164cf2bb49938.nq.gz
    ├── 728c9176b16b8904e7582709326d6254b8282e95.nq.gz
    ├── 7426f767a12dbc47ffc9479758f6f2e1abe82d1f.nq.gz
    ├── 75e820f3d416d16e6842bb1a93cd353f8b3c24bb.nq.gz
    ├── 76775ff6740f31257b60806db6b066296b0c9524.nq.gz
    ├── 7689ddc61bb75551a2257fc9f1ca89337d588108.nq.gz
    ├── 7a007244904a9562d9713205b3f28abd84eddb86.nq.gz
    ├── 7a128ac9f5c33a0d13c4fbc54a620d229bb2db97.nq.gz
    ├── 7addd113c9321d227b3a4ee03a23ccd36573bed8.nq.gz
    ├── 7cd63c8592ab2c6727547cca483b677a721a2d67.nq.gz
    ├── 7dd5d7c560aca0709c497c5507c8fad4e9c66d87.nq.gz
    ├── 7e2fa0d6f5086a3bc08310516c7e5dc85dd10f8c.nq.gz
    ├── 7fb800a9cc4080b820972b78e7c0da0d6b91e80b.nq.gz
    ├── 800eaecb7ea65ef29b03aaefd732db29dfb1d0af.nq.gz
    ├── 80a2436cee24e4be6b1e1a776b95c2e27c540416.nq.gz
    ├── 8107fb2da5156d81fcbe54902183208b0ca7204b.nq.gz
    ├── 818afbcd3188feeee02a61a05dd86c9848afd290.nq.gz
    ├── 81ad4cecaf23e2483ccb6fb221c951f520dab9e9.nq.gz
    ├── 838b2d69bcb36feab10841eadd79351f294d9cf8.nq.gz
    ├── 8486a10d1cbebf0327291943d79348f10d9775e1.nq.gz
    ├── 85da7d3c796f12bb48de1e52c3063590050a56ad.nq.gz
    ├── 862b407c6a178d9cb1ec7a675c919489a5c72800.nq.gz
    ├── 89baa753dd2217c04c65b51c41125233327d0a98.nq.gz
    ├── 8a8e33e2db5f8811dcc47b798f0bc0d96d07c426.nq.gz
    ├── 8ad7bc6cec6aba880dabefe631cf68fe2367a32c.nq.gz
    ├── 8ec74ab204e48240e38c11bd1f4867d71253684a.nq.gz
    ├── 8f722d867a822bc0066597139c05c1d65d10354f.nq.gz
    ├── 8f803098382279983ed82d8114e38a0dd2ad1e46.nq.gz
    ├── 8fb52f61505a7eb41426f8f2defe9cb909d8c9c2.nq.gz
    ├── 8fe514a5602e12d19ec0c2627f4d2843cc65d92c.nq.gz
    ├── 9083472abd232e1f60b413d128b164ca2205f6ff.nq.gz
    ├── 910bc03a51128aed0383cb8300883a5ae03d0c9b.nq.gz
    ├── 9499e5dc2eea74be9750be29389422cf5bc368bf.nq.gz
    ├── 952027d71a71ac586128822b08e7660a97c5a60b.nq.gz
    ├── 9586b462e34d2e8e51cefba236472f5da0145ee4.nq.gz
    ├── 973a7358b6ef841989651472852eb1e16c85cb32.nq.gz
    ├── 97b074d31037090a83a7a7a6270841dcc1f11baa.nq.gz
    ├── 9840364a246d3b6057e53e1c4b16c47b21fd3d8d.nq.gz
    ├── 99cba1ae94bf201670d531c33d82e066f8568751.nq.gz
    ├── 9b077e36a6aa28aa167a76485200e5e404c67072.nq.gz
    ├── 9dbd9accd3bde49e28922ad4c6c62bab8f521612.nq.gz
    ├── 9dcc72fa53e8fbe7814e3d9e23a61ee12ba9662b.nq.gz
    ├── 9e5b68e13519052ae9130b122a4514b74e46f7fe.nq.gz
    ├── 9e5de58e415536aa730b20821c6c14a5d413ef45.nq.gz
    ├── 9f886ba1ce14b9ca9f638657f1ca13f28e0992d5.nq.gz
    ├── a3058390c8dd4e04c9acf0d61764dab4c0c8f986.nq.gz
    ├── a3f8602df8f0491c8643b46f3ce7cc2789b50144.nq.gz
    ├── a418171dfbb14a5a7141271ea0d356210ea6770d.nq.gz
    ├── a4fe4808eb1ec7bd11971b62cbf1c0a996199156.nq.gz
    ├── a5fb8627b34d5445750f39e3e51cedca29cf657b.nq.gz
    ├── a70cdb5656835728bcdbb91170f19e5a86196a1b.nq.gz
    ├── a74b3293c20406bee00ba2f20d6df60ad0435c1b.nq.gz
    ├── a84cfc30e11bb96d827d7496e93c22f5c48c32e0.nq.gz
    ├── a8c24839414e04dfbd759e04533832df1658ea88.nq.gz
    ├── a96bbcfc16888d9d26751ba1c05f9c0ab4901032.nq.gz
    ├── a97b621c2457a4e64ebf779901c43f22693c1d82.nq.gz
    └── a985112b19685f6f581f12d272f89c745e350953.nq.gz

7 directories, 200 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[vllm-project/humming](https://github.com/vllm-project/humming)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
