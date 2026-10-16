# Repolex Knowledge Graph of sknetwork-team/scikit-network

RDF knowledge graph data for [sknetwork-team/scikit-network](https://github.com/sknetwork-team/scikit-network), parsed by [repolex](https://repolex.ai).

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
rlex download sknetwork-team/scikit-network
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f8f9dfcde8339e6f4562c6553509bf6e01076865
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f8f9dfcde8339e6f4562c6553509bf6e01076865
│           └── chunk-001.nq.gz
└── blob
    ├── 005aad60a14b674ff3b3a4a921b3fa5e6449fed5.nq.gz
    ├── 0082dae4b7276805c21d12d9179d9c41c2671bc6.nq.gz
    ├── 00a3138cf2b3831d758476dadc1984eb367807d0.nq.gz
    ├── 019d42375935f8c448872ba0a7b88c90750c6f09.nq.gz
    ├── 01f25202baf971af390ccdaeaf79e01dadf11016.nq.gz
    ├── 039498d252a2dbe0159d373017c4d3ab3ecbc060.nq.gz
    ├── 067dece9f3acff124423ad1585dee77750f0e18e.nq.gz
    ├── 0834c2d1cfaad2aab3f280392d014b1e381509c1.nq.gz
    ├── 08b2850b38408a1f7fb8037ab3cde5e47eea6cb4.nq.gz
    ├── 09f727122891e845f8eb3425192bdd36893465b3.nq.gz
    ├── 0a989370e18944a14999b9a09e3cc2bde08b72ac.nq.gz
    ├── 0ac6e4d22eb1e85c2691f4804b64ed44a5fd074d.nq.gz
    ├── 0c632d8239330caec155683123ee153312e688db.nq.gz
    ├── 0cb7c90618e10f4536358b509f742c49e0873bac.nq.gz
    ├── 0d4be5ae92f0bd8c9cabec297ddcffe1f0598e71.nq.gz
    ├── 0d79797d718319d5ee4c9c6a0b270ddaf7676247.nq.gz
    ├── 0e919e3151e00f05c41d6e46c0940a17843f2bdf.nq.gz
    ├── 0ec618754ab6e4eb7f1d046c39efac4a6033572c.nq.gz
    ├── 1040b44df5e045c01f26a45a92b70866a774aac8.nq.gz
    ├── 1342da84283f759106e92d79931a758f2647fab8.nq.gz
    ├── 14d8d37d0d2123b53402bebfeebaba1b2e109bb4.nq.gz
    ├── 15b2676573aa6ce1ef405f01ba9b5f4503c20069.nq.gz
    ├── 15cc6b6c933258855bd847f57497f9ac73333d6e.nq.gz
    ├── 15dc02074ed200193ca85eba80d8418cf643c1d0.nq.gz
    ├── 15f420be0f16f4f0576792904a486c1317f5627a.nq.gz
    ├── 16326789f7a886bb171e1ffc12674a7fee504a49.nq.gz
    ├── 1642994e29f3e904d3ecbc1d5a5f8b86ff0e78a5.nq.gz
    ├── 166997c8cd23bc931b3493b407f86435c839d043.nq.gz
    ├── 16ca11361e3a6de79b0246b05f3b6a29149e3d56.nq.gz
    ├── 17149f33302e640ead382fb98b5b3777f69addb4.nq.gz
    ├── 19a4da5fa4b0e457943b2b7a8624bebbe7894b13.nq.gz
    ├── 1a4ab71c3ed9a7dde4f53f4839ae1a0e3e208cb8.nq.gz
    ├── 1a789cb851d2e5af43a9ab104ea777aefdf557e2.nq.gz
    ├── 1a7d5611cdb2716c33adfb6623b23515a50c9577.nq.gz
    ├── 1bad989df598535fb381ff0a7e322a1e9faae2dc.nq.gz
    ├── 1bd178017264230e54ee81c9316689e9a279b654.nq.gz
    ├── 1bfcabd93b729ec7f4f8e388782d1249acf09f58.nq.gz
    ├── 1cd3dd3b6e835557687b675c7a996f1369b8f43f.nq.gz
    ├── 1f345c6848cfd1b2dfbf6f26f82445cfb6af33b7.nq.gz
    ├── 1fdee4e3ff411c37108b52ef863012a4044348c6.nq.gz
    ├── 2088f03b507547ce4f1a8710b2e57486086edf30.nq.gz
    ├── 2155ca8902a8f7ea67589b1d587fc4a0267847d7.nq.gz
    ├── 21cf1008c07d74b6ee69ea4a6b589a58badfe169.nq.gz
    ├── 21fc9eb31b22e1919e99736de1a7430c20019f71.nq.gz
    ├── 22cd892af8ec84944c6243db601865ac31f36528.nq.gz
    ├── 231ff32d8637a3a0735e414d56616de405a6a86f.nq.gz
    ├── 2374268ce88dbcdbba320ecd8f70dc7e5e856305.nq.gz
    ├── 24661775b4f3db3f5b5f6bfe2ccdcb4e3cf67939.nq.gz
    ├── 24a74f74b59d4423b70c3adb1af0fedd56c9211c.nq.gz
    ├── 24da65a98d228ede46b9c149a94607484fb96128.nq.gz
    ├── 250649964bbc36f4bec2942f69238aa6f7c02c1a.nq.gz
    ├── 25ec6d3907fbeb02558a2f0862383998e10c208f.nq.gz
    ├── 284748ddafa16d2cc5f6e5e49a308b4055a6a5c0.nq.gz
    ├── 28e2a58d195d345d2dd933bc7c0fffa02664c300.nq.gz
    ├── 295b7a3b51a6e17f00d3126f1cbae4be37aa1c9f.nq.gz
    ├── 29844e97b884f5a2fb7ff88fba6dc2de7201f6b6.nq.gz
    ├── 2a4c6cb5fae3a92a7206ae961810c03fa74e41ac.nq.gz
    ├── 2b49c1e4d68642563604862e1e4b61de158a082a.nq.gz
    ├── 2b97a869c794fdfed4c954765ff153a3d83331ec.nq.gz
    ├── 2d196080fc87ce5d892c929fe769a5d735935d79.nq.gz
    ├── 30244ad50aac5c26790ccfa500a25d21f7da2fc9.nq.gz
    ├── 31ac04c0526ead258171ddce7b5dc615e4422f08.nq.gz
    ├── 31ade4524ca883867f847f511675ea630da3b272.nq.gz
    ├── 3247d8fc2ea62620a7ff62a309baad91a32886a7.nq.gz
    ├── 325afbd42763c502847048c7d798be5013ad2331.nq.gz
    ├── 33c428b7a2910a17f443c938408de6441d2ccd4e.nq.gz
    ├── 340b608229347f9ab29790b1234c6b6f90944964.nq.gz
    ├── 3447b35dc8bc648f8ae6b9884224c136c9216308.nq.gz
    ├── 35d63efff28829a1e409476b6c0b86121b838f9c.nq.gz
    ├── 36155582beec9a5eb1e7587788fbb59682a77b92.nq.gz
    ├── 37f3964704fee221bf53dc4836c63d8691fae1ab.nq.gz
    ├── 37f789a7d662d3afd38dc6fea89e3371774d5e86.nq.gz
    ├── 38ac0ad9b332e9d4bd49e2afabc2e13cd1b3fdd4.nq.gz
    ├── 392989b163037adbc093bd6f14dc707e3ed620bd.nq.gz
    ├── 39443c1f4f51cec6a2ac834370145d96b6a231c1.nq.gz
    ├── 399fde666bfac73c49e81858eaafa0f524ff6c06.nq.gz
    ├── 39a59e592b030d9b0a307cda1168641d336e56e7.nq.gz
    ├── 39ac379eb85cd365a56cf8f9977d68e256f11535.nq.gz
    ├── 3a8492687552cef6612f10e4858d117623ca13c6.nq.gz
    ├── 3b574413f9f288c3319e0e5728f49e2975492f73.nq.gz
    ├── 3c108211fd11c74c64dee1f3a03d86ff2e083949.nq.gz
    ├── 3c2866601fd0e1da3ed73c48206aecc5bf091af5.nq.gz
    ├── 3c9832b89f7f587db2aaaef8920e158c6bca1bfa.nq.gz
    ├── 3ce83bffdde50dbea7face4085c14e18cf645529.nq.gz
    ├── 3decd974356cf4cbee489e8d4658f0ac6a02763d.nq.gz
    ├── 3e5f157c86da52682fde56611d44c37ccaa94db0.nq.gz
    ├── 3e66e8e3e3ab279490765c0da437c5e128f928ce.nq.gz
    ├── 3e813da6846cdc69d767cef9b6041c7f879cf431.nq.gz
    ├── 4050aa637bb0a3bcba956595af4eb5f0ad063c32.nq.gz
    ├── 41c49d06f2dcbbfe53f7a674cb49a8d37b15084b.nq.gz
    ├── 424fa05ab43e2bbd1eb5415c99807816ad891eb7.nq.gz
    ├── 42ea27b62292a317fd30418bd071551bd05d7ff5.nq.gz
    ├── 4401e065af710083e33897e90416138aad8ee648.nq.gz
    ├── 442db05aeaa07c3247bb54de3bc06e1efec0034a.nq.gz
    ├── 44c8f242a529abe2a9283d980ac09f3ed6f1ea2e.nq.gz
    ├── 4571ad90529732e485f0dd267dd3f6b1b08dda58.nq.gz
    ├── 46af9596f949f99885873a7cdee24e45f5e1f349.nq.gz
    ├── 4717fe96da22999931baa155babd1dbe17c511ac.nq.gz
    ├── 472d02d8f7f1c92ae980959c4026e7ccfec558a8.nq.gz
    ├── 484f3aa8a6befd8f4f1e55a0bfbd3f512f308e55.nq.gz
    ├── 486fb489e26caf7f700ffd64e8c27633a9f3c75b.nq.gz
    ├── 4962bf847e79e1761b1bc8b8cb656a9d34372409.nq.gz
    ├── 49fad18638192aefca4bb45e1ffb62fb363fba64.nq.gz
    ├── 4a466612bedf4f6643d08a4d005afe6b41f6a8b2.nq.gz
    ├── 4bcafe67efbdabca30731a5e227343d9725007f7.nq.gz
    ├── 4c8a67dd1d490b61908e165a3ae2f584f46adb1c.nq.gz
    ├── 4c9f057e26250f88e4656ac581f0ab2f5256e41f.nq.gz
    ├── 4cb98a64c19224edeea2c5429f4d8b048664825b.nq.gz
    ├── 4dae33898c8b6f161006db0fff7b209995eafaff.nq.gz
    ├── 4f01e897760e88a18cf44085594e23546c1f9958.nq.gz
    ├── 502a9675059ccf6ec74d0e6dac163cd0e2b3b7a7.nq.gz
    ├── 5391325051f9a48a4c14df8e4420a6f52d2e462d.nq.gz
    ├── 543c6b13b473ff3c586d5d97ae418d267ee795c4.nq.gz
    ├── 559c191da25e19f0737c1d61c579ffc07ad7814c.nq.gz
    ├── 55f8383208545ac6aff32f18629f38e78860740b.nq.gz
    ├── 571f2e34ed8523c59f0a9fe565617eaa00a3a1bc.nq.gz
    ├── 572b9711a26af5fecfce0573fce6c1f4e6d0d27c.nq.gz
    ├── 5916b7909bbfa7d731d8d52434fa804f77c9ae04.nq.gz
    ├── 59efe1dffbdcab160bc9a89ded6e4c8471a1fa17.nq.gz
    ├── 5b54ff2e70d3f3febe0debd1711eaf15ebf9d9de.nq.gz
    ├── 5c5d45e6d516fb4f7eaea30faf79853a2624a946.nq.gz
    ├── 5d78367cc398e3b995e299d4c77d2fca0439dd28.nq.gz
    ├── 5f55f856e7e1a1b3ffa38dc26387a1635f8ff571.nq.gz
    ├── 5fe44db3e21eda7a363e06a4803af0d32e90c37d.nq.gz
    ├── 60dd107a79f55f0543632014cf5df591edddd86b.nq.gz
    ├── 61014092c2b80df17025ebe0f92385ece417f933.nq.gz
    ├── 610c82a751b116a2dae24630cd62927a213b71f8.nq.gz
    ├── 614e84377cc9b293da9b668fd1df9c918a0c6310.nq.gz
    ├── 615c2f2a4e7d8387638fcd82389e07cbde62190a.nq.gz
    ├── 61ef335c7a676f01399f7a91c6b214f001170a5c.nq.gz
    ├── 6271a08f0d3f535c94c67d87995f480adc3af273.nq.gz
    ├── 62c60f79d7b2640c80e43808655dd18a605f26de.nq.gz
    ├── 63571775b3ed7b13e827a6a0a73a24fd951f76bb.nq.gz
    ├── 67982a7c6c93329f433d6a4ffffc2f82c046f8fe.nq.gz
    ├── 6872fcadb90f46e3b17b39624497445c05ba4d83.nq.gz
    ├── 69025c5d7a55ec974f151bc25349bda57b625cae.nq.gz
    ├── 6927a42afa09ccec2fb4a2630cf96157eade02df.nq.gz
    ├── 699467406618c9291ad06f09b8a8a0c2c8bf33ee.nq.gz
    ├── 69d1acdf8000a0cd7bf9289561814b51253db2eb.nq.gz
    ├── 6b314921de27e3a1d30c735ce74503820a17726e.nq.gz
    ├── 6d06cabf1dd7403f8dde7fcaeadc41c5cd43a46a.nq.gz
    ├── 6f31387132b8f3c4d84781cd9a5de9e8df550fad.nq.gz
    ├── 7035c852b7455fce640db9bede957ae24384481c.nq.gz
    ├── 704c54180e376f38168d2f01da44defe694a1e93.nq.gz
    ├── 710c747a62312c81abba740cba8142f02d866a2e.nq.gz
    ├── 71fe617f42b7c055bedc36f00f4fa2d798727135.nq.gz
    ├── 7265c4a54f94a5006d22f3b7e99c5c7a381b70ec.nq.gz
    ├── 727dc29ad2082b77c864d8f87395f0c1e4330b3c.nq.gz
    ├── 7288410080af5c84c8ec25d495bfae9c19822921.nq.gz
    ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
    ├── 750681b64e7a164d5eae9af4219d6bbdff1d5e05.nq.gz
    ├── 75e91fd3d3b7b9d4494b11d44fe7085b32a1d174.nq.gz
    ├── 7645252d6ab33f28af7f4e8d7c1dd4d0df6ecb6b.nq.gz
    ├── 782655b5c57e211ea36d02b2d1f13787e1fb5537.nq.gz
    ├── 78ecd687a549e0a0833285a327fafade1db1ab2d.nq.gz
    ├── 78fb20197a7bc95ce2fcb739bd682bb08b761725.nq.gz
    ├── 7925c3b91e188f9fa6d030ffaa0fc5bb79657043.nq.gz
    ├── 7966d538021ef251faf5794d5970dfbf3e8873e2.nq.gz
    ├── 79b733302685981f79e5200bdf7329e4b901c4bf.nq.gz
    ├── 7a68b4a03121d8382502c518376291589a79b4e7.nq.gz
    ├── 7b09191fe4cf1614a75c4c557c4b23dace6ba409.nq.gz
    ├── 7b5b14b3c6acb9c2121f8777a96856ce3d81d565.nq.gz
    ├── 7c0e18cce825a51c0c59d13f4bf1b59d63345994.nq.gz
    ├── 7dc768146d0359485c2ff0293084f18b5dd1ae16.nq.gz
    ├── 7ea89319594f63cef1a6033d2a2a030bc5ab5bb2.nq.gz
    ├── 7fb710b36919a1c4596a8db01edf7433be22520b.nq.gz
    ├── 7fbbae4f9c58882c3754a89675312f3c1430ffd8.nq.gz
    ├── 7fe3797532e983d60593541fafa99ea24361fed5.nq.gz
    ├── 7fef8cad5556c92b67b52cbab30583bcb82452df.nq.gz
    ├── 801025564082ff119f2b21b24febd8ce7e927664.nq.gz
    ├── 80655d98c55d1625af9143f4127bacf2dcacf72a.nq.gz
    ├── 81239990a99a594771aec44677f5da9ddac8a65a.nq.gz
    ├── 81cb4d2d15ffe295a68e0a83b5df4dffe78cba03.nq.gz
    ├── 82e9988396e5a9dc0c1cdcff36bf73c25c30825b.nq.gz
    ├── 83ee6d7be9187ab1e7fa901ecc489370cde521d5.nq.gz
    ├── 8869bffb92ee6874dcd60a9b4a654f0e1e47fecb.nq.gz
    ├── 8931f33287f50f86c37ce8b5a3547c66b2ce834c.nq.gz
    ├── 8a9f7274eb07e09c53f94b00e42824eed467e399.nq.gz
    ├── 8b0b5d3ea0e6c027db5738f8dcddc30dde7afe5a.nq.gz
    ├── 8bcbed7ae8011dd132b302fc53d0db4058dea10a.nq.gz
    ├── 8c119230812daf2f3d79d2416fc6931a08d38e92.nq.gz
    ├── 8caa763fca2ed5a159f49ebc5ed17a148f90c288.nq.gz
    ├── 8ccb326eb7eb7afe6491343e273a0035251d2d4f.nq.gz
    ├── 8d1e9fa8a6570b3819a9eb4f231e5837670d5098.nq.gz
    ├── 8df4addf3f5fad6d6403a34d2365f4eff82a5bb6.nq.gz
    ├── 8f0b83c07ca194ecc4b9165d31d6305e2f49fbce.nq.gz
    ├── 94bd460830d4df0473a82cd60338ef7af4fb8735.nq.gz
    ├── 95a5eeb9d2e2ee73cc0fc12d37fcad82f2719364.nq.gz
    ├── 95bfb6ddb1fa70fd457f30052326ae04a05f01ef.nq.gz
    ├── 95e6ebfc64c8b9af367cc69590819e1a6037e50e.nq.gz
    ├── 9763a3e381a3e13a3075ea82f3e502188377d220.nq.gz
    ├── 97b15d4a666246a2cd723aacca3957439bd8c4f9.nq.gz
    ├── 97b3ceae452302a0af3290cb220b19369bdabff1.nq.gz
    ├── 981b3fe122402a23b320f2ac09961b4724e870b7.nq.gz
    ├── 9b5103a4510dc27a6659be5be10525b329a1afed.nq.gz
    ├── 9c21b6d3c1597fca36b1746d15dd3e64dd5c5130.nq.gz
    ├── 9d6745756e065dcdc91f778d24e6f9e2b6765700.nq.gz
    └── 9e21cd4322862472fb8c2f2411c0f10119634287.nq.gz

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

[sknetwork-team/scikit-network](https://github.com/sknetwork-team/scikit-network)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
