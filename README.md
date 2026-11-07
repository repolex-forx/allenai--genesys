# Repolex Knowledge Graph of allenai/genesys

RDF knowledge graph data for [allenai/genesys](https://github.com/allenai/genesys), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/genesys
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a38edfd0099fc08389e93594bb71f393ba5d18f0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a38edfd0099fc08389e93594bb71f393ba5d18f0
│           └── chunk-001.nq.gz
└── blob
    ├── 006b2c5da509c1baf6257b7dcffb26b991277654.nq.gz
    ├── 00980a12b3a4d1c4d836d16ba8b147becfca32b2.nq.gz
    ├── 00a23b581713f66802f360e63f359db5c4b9f587.nq.gz
    ├── 0124fb7d85dcea9bf06ad210df681a58d34d1e5e.nq.gz
    ├── 01c6bda9bc0b214b2d93e94fcd20ff191ab240e6.nq.gz
    ├── 01f0b947650c6da81c2a0476e76056edb0574cb2.nq.gz
    ├── 023571569e29a0fa988fba2b702f255c78bcfd72.nq.gz
    ├── 023a57cc9b7bf49ab8499aab5dcd38c52295797a.nq.gz
    ├── 030501ce3163502155c9bf5e5bc6f631626a1334.nq.gz
    ├── 03182b7fcbf49529bb70921e27e5e8286905aa51.nq.gz
    ├── 03289ba94932b02449160a7eb2c55bb6c6d56e3e.nq.gz
    ├── 03ad3f3aedd1b9a2fa9bcc0008f5af4694d5bcf0.nq.gz
    ├── 051d8ebc678b20b97857d2a0e81fdf775a7e6822.nq.gz
    ├── 05de26fe007ab181ddd11ec940314fb4a494bee8.nq.gz
    ├── 06377930a022f3172e86979f5d8725ff29a7e994.nq.gz
    ├── 06c2670a9d8a22991284893f1a4b221b4660b9b8.nq.gz
    ├── 074e074150286b4fc78d68c06beeff09b1c1e61e.nq.gz
    ├── 07a67b13ef75f213aa1598a5227e77e50cfc4d2c.nq.gz
    ├── 08a329dff90b2225b66879f0135afb69351adb22.nq.gz
    ├── 0910eb3d489a959b50ce588145fef22f281ae20f.nq.gz
    ├── 0966384bcd8d1096adcb7daf903d107e9b1e9d49.nq.gz
    ├── 09ca471ec30857267ea7cc50b0c458e3dffc7631.nq.gz
    ├── 09cd622f94cca5f47b88627b7223394cfbfea4e2.nq.gz
    ├── 0a51b49ee87ac964966e7f6a1fb60abaf19205af.nq.gz
    ├── 0ad034963fb0287016c71b49be1e1c0600dbae97.nq.gz
    ├── 0c230c7dfb4b2e913798a10e24603aeff362dae7.nq.gz
    ├── 0c23f327a91c5c434a0a9cdf09cf53a2a811c9c2.nq.gz
    ├── 0cea950ba5b74e612410898fbc7b60772fbe3395.nq.gz
    ├── 0d7555acddbd260636d1d14d5bd6324f6af0056a.nq.gz
    ├── 0daf8e7c6de0d6474dfb24f22f2f8ee33bbb0416.nq.gz
    ├── 0e5af7dceef2993544f39a606806240bd92bdc98.nq.gz
    ├── 0f2ed050e165834827461830cd80887f4c9a178b.nq.gz
    ├── 0fa6e8f8a8a4781cd997ec9f579cb94db892e8ea.nq.gz
    ├── 0fd08cbf23bb7441323862a945cda946f2a5726b.nq.gz
    ├── 0fd5b9d54a7427a509a1fae9687390e589ee105d.nq.gz
    ├── 111021b4904c8f116b317b276b91616009502a92.nq.gz
    ├── 1130b4b9771bc88a5874aad7b1e4e91882179623.nq.gz
    ├── 11aebb1f6be6390e5ca8fe71b5918722227c442e.nq.gz
    ├── 11e065a2c3715d6e7b29f789ac62c29808468520.nq.gz
    ├── 1293d65d2d6afa92ab263b8dcf3d2675ad77dc9f.nq.gz
    ├── 12a9f76f4c54704d09a7ec767b2b3de13d25824f.nq.gz
    ├── 12d85bbb970f502d7d7cf96d693343d5be6f29e3.nq.gz
    ├── 13a6581a92159b3ecb4601de4098b3c296bf34ab.nq.gz
    ├── 150ffec86358585e6b149c6d1815f4222f96b7fe.nq.gz
    ├── 15536bfdb8843c68fdfc40b60859a41092c4f9a9.nq.gz
    ├── 15c006d9ac599d55235b4a3fef4c6926b3c0e29b.nq.gz
    ├── 16db223a0367c1ec25b735987686496518596782.nq.gz
    ├── 1775b9a0e83a1ea4618f9706f62be12ea6fe233b.nq.gz
    ├── 185abb4e141109697724f2ca4e6f668d732094a9.nq.gz
    ├── 186240f5958e5311b69a04499b08a981be5968a4.nq.gz
    ├── 18a48d086aca45f6367a97048f693d3e6f6c2096.nq.gz
    ├── 1931b81553f56d56799a8690b3c1da7cd3f3af55.nq.gz
    ├── 194ce91b16fb72bcce1affed284ac9baf7e16ff0.nq.gz
    ├── 19ba0d24af3c617ff2757d03e8ee479642f77f5d.nq.gz
    ├── 1a624856268c003549e8db7a3e0964b9defbd66e.nq.gz
    ├── 1a8ed0cd9ba566dbeeb3984e143efb1c9b17eb22.nq.gz
    ├── 1bc0588bc18baae6a925ff6fe5bf9015b7d0601d.nq.gz
    ├── 1c30b1f8e33e51d8b72c48d4aadff8514417245b.nq.gz
    ├── 1c63db74ee256b1b84b072aea736847d257d4d9d.nq.gz
    ├── 1cade6a4dd94129fa26af40ef639732f259d4bd9.nq.gz
    ├── 1cbb798fa1cdb95e7624c06a28e8dfd5b110c1cb.nq.gz
    ├── 1dacdb89182e788181b824f0e1ace0dd843f7905.nq.gz
    ├── 1e1522963ca93618445d6ecc5c1dc2f5367caea7.nq.gz
    ├── 1ea4978be7b0ae48b3f2b82e953aa34c8939680b.nq.gz
    ├── 1eaf73243f88402ec20f32f4afa5e969a1fb378f.nq.gz
    ├── 1f1b9243d42334aef23aa75db7da603c33c87fa3.nq.gz
    ├── 1f2d0c138218aad4f2cc5d37f26f31b4a0546d40.nq.gz
    ├── 208d5396cbb3c7e91cc7a5e64d97c72685e82176.nq.gz
    ├── 2131e22f4a20c2468d41316bb5ce5d927f1f099d.nq.gz
    ├── 21496f86d1058b5b812851a16af010f9e7957c5d.nq.gz
    ├── 21a8d1f38d3c8bf749bb1447ead8943f413e87bd.nq.gz
    ├── 23ec993ba430183f09b244e561f4308f6bd25d61.nq.gz
    ├── 24fbce0399b0b2cdcb4d0191fb7d91bb962e248c.nq.gz
    ├── 25425277a63f8ae6bb56914df63b62ea62326690.nq.gz
    ├── 2550a3d7e7d9fb8c8add6455296b4e7a3b142390.nq.gz
    ├── 25a2d92c16207c7f0984f87067239a175a6adb1f.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 274364a972ee5aa87392d666b20d9a9a0697e7aa.nq.gz
    ├── 281fb2e12fe5c6af4fccce103737e4b6360c63aa.nq.gz
    ├── 2923e8ae1628ba8e936fb9afe2d1778955781d7e.nq.gz
    ├── 29ace993835d855e7db667cff184d2339d701f0b.nq.gz
    ├── 29e6161c7b23eeb4134f3401fadeb95d3ed96e46.nq.gz
    ├── 2af4a11f45a8f1d79ede3c680c4317b701dde540.nq.gz
    ├── 2bbe09383510339f50496ecafa52e944c01634c5.nq.gz
    ├── 2ce2e032a9366248b7fa9f502eb6398780d1885c.nq.gz
    ├── 2d11235a4c0386dfb9978fbd3baa69afb108b31a.nq.gz
    ├── 2eba5b6632589d33e4c964ff8420a133e45deb0f.nq.gz
    ├── 2ef3e18f1965c350d480f3e9e079953341017649.nq.gz
    ├── 2f304d4344574d6cf1e4bbdc7f87158bfa2cce11.nq.gz
    ├── 308c3ca9401b664e91d109687d0e4665308ee165.nq.gz
    ├── 308e20ec6ac5f01a8062011ed24e094664a38e2d.nq.gz
    ├── 30aa1304719a06c839de477c9e7a79a61c2f7cd9.nq.gz
    ├── 31116a52d40b4c064e10f45685e868a441379b65.nq.gz
    ├── 314d196f5b35e2c40b3bc0d2c783c0311d2103fa.nq.gz
    ├── 31f5d2c772416bdbc2bc03b0c27ae3a8c43bd2c7.nq.gz
    ├── 337713ae622deb6bbb8a99bb6618a965120bc24d.nq.gz
    ├── 33a01fd3749d4d3363f27f94de02b9d8bd904a54.nq.gz
    ├── 340a170c4ab1ecf5f19a8ba1e8fa9f114c156a1a.nq.gz
    ├── 34ea92ed0ed9ced078d3d82e060f29714e6b395d.nq.gz
    ├── 36cf7da1f216b13014193ccd28be10efd522dc64.nq.gz
    ├── 36e46e0ba004ca5b5a8d41c9ff5802e87d516b29.nq.gz
    ├── 385bbf8c9e86e6ab84dfc613b36e26ed8247249e.nq.gz
    ├── 3a2b1bd87cc5bc4a5cbc611376b555720a02e5f0.nq.gz
    ├── 3b481df1dd1549b785dd1c5de69517aa7222b1bf.nq.gz
    ├── 3b817d0d3430607ebff5613fe248d0c516f2de39.nq.gz
    ├── 3d40aac0e33d9b75712e1e549a77b07a38ca2d5a.nq.gz
    ├── 3e1fd6555f0846d9ef42855dad73026410513a0d.nq.gz
    ├── 3ea874cebbd3a695ab114d85eb9d52c7fc327291.nq.gz
    ├── 3f34b5c5a32fc6f6b4698c4a52ccd611e1b86a12.nq.gz
    ├── 3fa3f518c7b876990173f14723220278e1aefed1.nq.gz
    ├── 410ffbb523db53406f0ad6246567ffa924eaf14f.nq.gz
    ├── 42696738d111606041c1286fb02e7d413af9e0db.nq.gz
    ├── 42a532dba8e1512ffa9f965d982b7a329adf1efe.nq.gz
    ├── 430d89896f541435258e17d82221d2406053cec2.nq.gz
    ├── 44095231b6866953628c2bfe1b2e30b98782b7a0.nq.gz
    ├── 441da1f1eaede11f3799f55bec5b1ae9ca86d02d.nq.gz
    ├── 45f4af4d6215e816383d6404d5972d4ab283d278.nq.gz
    ├── 46222ead0a5ac75cf53edc37084f6c66d394596d.nq.gz
    ├── 48270e0c000fad00b67ec83f2b753c6ac6d726d4.nq.gz
    ├── 48fd4f063e7796ceea772c21956b7bbdcbf1d196.nq.gz
    ├── 49542f609222b906e284e2af58ce8e11f6bbfa63.nq.gz
    ├── 49fc5a7b2b586200440db04e1f1a0a0e6309a8d4.nq.gz
    ├── 4a86cdb3ab033822c053cb4eb7e253ba2ad1c14b.nq.gz
    ├── 4aec67515a3701e7f53d4877ea7a973f6d7ac1a9.nq.gz
    ├── 4b8968c51186c0802555af314d0cea919e2f223e.nq.gz
    ├── 4cd43a6538cb4b6800c1bc10eb9dfa338d59620b.nq.gz
    ├── 4d1400513f2302aca3c0fc3159d1ff4b57acabcf.nq.gz
    ├── 4d4b151e6484d7b3a49662d9ab85c6392dd3a2fc.nq.gz
    ├── 4d4c645cc4df11caa29115455ecad7d689699d6f.nq.gz
    ├── 4d81df4936663ae300d7ded2b143f705c647df00.nq.gz
    ├── 4db9c91db3ec25911c9b6ee2d13f7331c3dbae68.nq.gz
    ├── 4dc1b364b33fe6929b8c6e5135c53277c420832b.nq.gz
    ├── 4dca11e86f19a50be84b51d8e65ad083fe352f6b.nq.gz
    ├── 4ea7906a2415d991e376d587b59b58088fe8f731.nq.gz
    ├── 5064bcd49fd4aeda16d2b6cbe0aa290ab76930c6.nq.gz
    ├── 50dc190c344fbf0702a5f7e027d78afbec3a053a.nq.gz
    ├── 511bb5c86157292c1e67c715c8521734ff21a8ca.nq.gz
    ├── 5180a809f0bf8b33ac33cc5b6098dcb3fd2bf593.nq.gz
    ├── 52c4a87f5f4b84024e622e85092369abcb498d4c.nq.gz
    ├── 534337a74af65a8570d0ecaabf94f871bbfdb170.nq.gz
    ├── 54eb0eef7a8800917d8312d0f45b230d8d98bf0e.nq.gz
    ├── 5576c6a0e06c99d99c7c49399ac39e2498bc2ca9.nq.gz
    ├── 5589a1c60410b2d8775cb576458ad48c28cd6242.nq.gz
    ├── 55b81475ac73d4d3ef8f97adaa1670690c1a308d.nq.gz
    ├── 55e90de45de4365119878afbd2ad471528664e39.nq.gz
    ├── 56cd35934f507211e4447b673bc57d7e6ee3eeab.nq.gz
    ├── 571d5d1467c6c4377a41fc3678ad8d1a0be27555.nq.gz
    ├── 577b6dbe970530d449896faa08729257a34ea07e.nq.gz
    ├── 57ee01a698038282051cee3be13e35ef358c645f.nq.gz
    ├── 580470d5616594e8182f8056a536e2993f8665e8.nq.gz
    ├── 597e98649dc5e837c3970edea5381f5ff335dae2.nq.gz
    ├── 5b9f42b405ff81df849a577c7b2be8ccdce797b1.nq.gz
    ├── 5bdef79b3447c22502c4f45248d180b95ca20982.nq.gz
    ├── 5c4b8283b4a78bee517a502564b5df839d4683c7.nq.gz
    ├── 5ca05bd2219341855c8edf1f42f98d5e0cadc968.nq.gz
    ├── 5d68e3e959a623be235d00b76611b13f701a3a93.nq.gz
    ├── 5ea8e465dc832b242771d2029a1f72faca542ce2.nq.gz
    ├── 5f1481c2e76f63f021038531630ec8082b795289.nq.gz
    ├── 60681787e2f04c5285bbe8886e2317ff359eae1f.nq.gz
    ├── 617fb072a57eb04943bf3841620a356e58306cea.nq.gz
    ├── 6369051711421f20b94d39685cb98a7325df9414.nq.gz
    ├── 636ba8a98fdf86e6fa948c0365de448766b3eaff.nq.gz
    ├── 63863b8236e1c091741c9faeb6f4a41376fc5b42.nq.gz
    ├── 63a741177e262d49b0ed7cfe7d472a521b8e0578.nq.gz
    ├── 63ba2493a71602f0c897910dd06df88bd122cd5d.nq.gz
    ├── 647d01e48d8ed57ac6eda72ed5ebecd9d0d42e20.nq.gz
    ├── 64ff442b43c4889313be0de9e4735feaace171fe.nq.gz
    ├── 655707f461a0d858210d129130341bdde966634d.nq.gz
    ├── 65a9baee93f9985227cda17ee07ef098972ae243.nq.gz
    ├── 66c1b8b8758792b8955ce0659d284586b4256194.nq.gz
    ├── 670201315dc83490d4cea719a7bc42bbefbabb08.nq.gz
    ├── 67b63e3690a529048cc2e19aa69371f486ac5c20.nq.gz
    ├── 67e4ec20395f832171f10c522cdc8e865411bee1.nq.gz
    ├── 692fa6c4c719bfa6568d5503dc2c1e0d59b3b93a.nq.gz
    ├── 69a832554fa01f790c842a62ab6caf3754469fab.nq.gz
    ├── 6a0d17fd04122b4dba19ad6a140d67c2376250f0.nq.gz
    ├── 6c8c383591567335bdf5c207e4cb6fedd59f850f.nq.gz
    ├── 6d47dc33442464e99e497369b7c0dfe191081fbf.nq.gz
    ├── 6df4f0c31fc9aaa86a0120bdb9c9aa899c78f2a5.nq.gz
    ├── 6e53a182193d937877befb7d721f8a6925b4d1cf.nq.gz
    ├── 6eb6021ecd875fce00e44f173c5fc1ff9b400eb2.nq.gz
    ├── 6ed3a254c813e26057d79d27f8d22206ed3f8d24.nq.gz
    ├── 6f799a1c4152bc68f12994a38633ad7eb19f8ece.nq.gz
    ├── 6fb8950b656f902109d34e5457889bc3e1ae3d42.nq.gz
    ├── 722e8b44e3fd4e2d62802c2e185e2ad3d9bb852a.nq.gz
    ├── 724c858f8b01ef56a52250231ebb4749bccac020.nq.gz
    ├── 7255ea2418be2755a24e1d5700c24147cb720bbd.nq.gz
    ├── 73c5955eadf5629452771a1751a10b938449179b.nq.gz
    ├── 73f4ce3c91154ee37469d207bda2704b5f6fac02.nq.gz
    ├── 74f6b65726f5f685f4fb9589e352b8c3cefa6f61.nq.gz
    ├── 751b99afc8dd92b665760c4aa1c845298ebd56f0.nq.gz
    ├── 751d9d0075816b3e26119cc3bb63f2033523f378.nq.gz
    ├── 7572cc735fbb5c40a703f9e0dae44b7697352413.nq.gz
    ├── 75d58cb4faa3d143b979a1d6c139c4329216c55c.nq.gz
    ├── 763582e0b5b564c631f556d32ec25fa2d2e506b2.nq.gz
    ├── 767224378c6a1444db86b84afd2b14a5d1df2446.nq.gz
    ├── 773b633ce284913b674d13044248797503c7f09f.nq.gz
    └── 7772b4575892e3409e3a729ff0ef8f443380fe81.nq.gz

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

[allenai/genesys](https://github.com/allenai/genesys)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
