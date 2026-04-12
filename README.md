# Repolex Knowledge Graph of oxigraph/oxigraph

RDF knowledge graph data for [oxigraph/oxigraph](https://github.com/oxigraph/oxigraph), parsed by [repolex](https://repolex.ai).

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
lexq download oxigraph/oxigraph
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f8e1d890eee73062eaf809b779ed1b276aa11d4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4f8e1d890eee73062eaf809b779ed1b276aa11d4.nq.gz
│   └── repolex
│       └── 4f8e1d890eee73062eaf809b779ed1b276aa11d4
│           └── chunk-001.nq.gz
└── blob
    ├── 00e97a979b2018a4052491a7754c540aab3e9f6f.nq.gz
    ├── 02e0718467a67b93ce49cfb10bd7263ff6e234ed.nq.gz
    ├── 02e7728e1b085d8ff935af5b7ea64d23b706b0b0.nq.gz
    ├── 039752e84d55c669775687264cf3d8a47212fd26.nq.gz
    ├── 048d12fe3126c178e5831a3eea35e234895f1890.nq.gz
    ├── 05c672def631edbe6c236cb9fb771b91486280ad.nq.gz
    ├── 068580c1f2cf483529e099717adc3cc426a8264d.nq.gz
    ├── 0698fd48633b5d6fb014ad5eeeef71feb4002caa.nq.gz
    ├── 07524c2cdfac65ea57efb0a1331f8a9c6ea637ba.nq.gz
    ├── 09d52581c2ebc0040781d5a0b80e1a897f1f7eaf.nq.gz
    ├── 0a13368fb268f4f3628e557576f2ef819b8cd9d2.nq.gz
    ├── 0c14b7b64834f1ad900e04924c264d4fea692967.nq.gz
    ├── 0d1fb1fcf5a7169cad70cfc974c327d2a1276a85.nq.gz
    ├── 0e1c40a9aa9fb3a64a2e8c57fd6e2597385ade23.nq.gz
    ├── 0e75b7b7f7d683bfb58becbcdd921a4b3e76c09f.nq.gz
    ├── 105513465f4d82a016ba79efc9444017eefe171e.nq.gz
    ├── 107c3c1f7315be0de76028c77872b827c7a2160c.nq.gz
    ├── 125dfccb4e3589c8e9910ba4a01031c433dc5488.nq.gz
    ├── 12e38b612d5de2a9da7311f6821111ddefdac5f7.nq.gz
    ├── 13805bfd45ffbf0ba2e2780e1c25bf00f60311d9.nq.gz
    ├── 13d3926aeb226e16f608bcf41f82d857c6ed55a3.nq.gz
    ├── 15b9cdbd66e743a76742ff7922f715cf15680e93.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 190eb1f613accaf3b6b8b4c25a5452387d837175.nq.gz
    ├── 1aa600b7c1c01760312264ae0e595228d680265f.nq.gz
    ├── 1abf4e46f3c794dfdae7b339c7636b843441aaef.nq.gz
    ├── 1b865fc8d4a1cda03f633685dafff70f4875ea59.nq.gz
    ├── 1c441be2bc94ded9eac2f53d2211c1b57855c748.nq.gz
    ├── 1c748f17bd48c61b257b70d79e4202ffcf405808.nq.gz
    ├── 1cc68bda58ad8628f4ddd5c3bed22dc5fe7e24c7.nq.gz
    ├── 1d0cc18505ad7872538c57d078dc646ef5e0203d.nq.gz
    ├── 1e492d8621be5a3b4ef252ddccbba42d9192586e.nq.gz
    ├── 1f59436b8403ae7cc1b83ffbfdc8f766af54ca0a.nq.gz
    ├── 20b7ebd0c8c5bae5710e59856e10bf2e449c2ee8.nq.gz
    ├── 217135e081dfe8b8de9033c62c62546be9c22d03.nq.gz
    ├── 2179274dad00e5d91e79b6a804f7dcfe0a912054.nq.gz
    ├── 2227c9ac35c1928b1b59a27b0830932e6245616b.nq.gz
    ├── 2296f7d68383099be42c459bb04ed1387742d6be.nq.gz
    ├── 23624131bb4a7afb7ae29b25b3f39a0010a4053a.nq.gz
    ├── 24e7337e338dd420ce75ad568022127a732e3243.nq.gz
    ├── 24faa1876a3ddf8380c03ac0dd643163bc816b00.nq.gz
    ├── 265ddffca516d27400900b9ed5aaf14f15329918.nq.gz
    ├── 27c316890d152e8e54e54f420dabb0e60a075717.nq.gz
    ├── 27dbf7a015482c5049ef0e7095efdeb3e6428dbc.nq.gz
    ├── 29c92751531a0e4fd699dffa671593e0b9933270.nq.gz
    ├── 29cd43ab303bde1b4018fe5ab493637ee26c256d.nq.gz
    ├── 2a569b60354767782b654e65401d77f3f7c354f8.nq.gz
    ├── 2ade3409cd44e0fb90f053f59298380a7da7119f.nq.gz
    ├── 2e36e34e4f2ce347828d408c2e7749415cd8f2d1.nq.gz
    ├── 2e7ed1b1428cf753bae82f84d6ffdbbe6f371675.nq.gz
    ├── 2ee89f8093bc07d3b75b668e581648e155a78866.nq.gz
    ├── 2f873a580826b1cf27285dab332193986c8d2a87.nq.gz
    ├── 2ff9b4055d1735a55143796cb75074fb5ec949cf.nq.gz
    ├── 324f2ae294d337872900c2df90bc6f2349a6f888.nq.gz
    ├── 32600adaebfa8a0a7b00923ac330c13ce0a3ce44.nq.gz
    ├── 32b3b35c381cab5e19c4856856196cc8c05adcfc.nq.gz
    ├── 3471fcd8c893b32f393206258ffe0d251045ab4a.nq.gz
    ├── 35b2d6f4ee7b2942fb82c0e84929dc63a95d98dc.nq.gz
    ├── 35bfa1a1385322072a1adf818d769eaf5e5c04be.nq.gz
    ├── 3760b66335f4eee7caeb303d097f9cc8fabcca6c.nq.gz
    ├── 38c761fd962d7db3311d83ac80487df7bcc1ac17.nq.gz
    ├── 39b7a23a0757232acbf38ff30531a881c217f15c.nq.gz
    ├── 3a9fd05331db3b69080a0d1c567f8db6ea06a01b.nq.gz
    ├── 3ad605c41519afbe1f16612c891621fef84f0ad5.nq.gz
    ├── 3b515006da7036a9ec55e3f55d16088765a8a747.nq.gz
    ├── 3b7933e11a6295f8e54b5257af88dd97ba705920.nq.gz
    ├── 3bab996499514bdad5f483839c703ad8fc3c6f75.nq.gz
    ├── 3cc2136badea393f45a0e1bce229076b2d829dd0.nq.gz
    ├── 3d1a9ad482000bf3a04e991e67e3f892d4b35904.nq.gz
    ├── 3e7058c4007b34d9812b82889c92123018124300.nq.gz
    ├── 3e81efbaaba5ab6d71cac4b5faedac911550ac6c.nq.gz
    ├── 41f2dd0c82d7e4c9ffffb0c42d2235b311ac55eb.nq.gz
    ├── 42a196d7022e1593455aaddad95e7cb595185876.nq.gz
    ├── 42d84087ac9f1091496ca6cb8f338f9200efe05e.nq.gz
    ├── 4310f137c65a511396cafd7ec0bcdbd4f514fe04.nq.gz
    ├── 434e93ebd51c5429f9e15c011c56d091decc625f.nq.gz
    ├── 4392b92b99b3e928da1bed7b1cfac5b6664b9cf5.nq.gz
    ├── 43ad4a6b30fc59fc1e66a76e75898012fa4bb5db.nq.gz
    ├── 43e62aadc914b6c9e0924295c9f466d04f1bd7ea.nq.gz
    ├── 44b404021f9189fced620684d910c3ec1a0804bc.nq.gz
    ├── 451f528a435bbe3468d948fb716d0e53c6c5ae24.nq.gz
    ├── 471821aeea25e1f078e56e42a5e498d8ce59e5ff.nq.gz
    ├── 4a5c7691d680b94bc5fbb0161245e23175cc9ab9.nq.gz
    ├── 4b0e835438ce2348a5cbe87ea8ad713cfbdffc10.nq.gz
    ├── 4c15ecf2dfb55988cc59c23ccd1bee9cfee10a06.nq.gz
    ├── 4e01e3c4968829f267c53735d80ee8ca275bf524.nq.gz
    ├── 4f8b2645a87b6a9508728c0c79d41af7d2f52fce.nq.gz
    ├── 5051aa49530521562722f01f8d52bd5213d9fc51.nq.gz
    ├── 507639d08ed0c97acfa245ead074563a5a4818df.nq.gz
    ├── 518dd62796569f8e539d3845c7f39227df9cffa0.nq.gz
    ├── 52de196e62679c5ddd50bead948e77d64971636b.nq.gz
    ├── 52eb63bc9c56568ecd6bc059bcc53c022f22848a.nq.gz
    ├── 543935a37bfc4db46d198adb1da83cc4b3452732.nq.gz
    ├── 54a78b5e233410c91af87f794472ebec4c7f5614.nq.gz
    ├── 557447391dd0db3c1f46bda1f811a58cafcd85cc.nq.gz
    ├── 55cfbd6b2c58c48bc86e0f915f043e037d8b568d.nq.gz
    ├── 5605a40371dda10d007f79177bd7580c29869206.nq.gz
    ├── 58c8a266db433e6e318c5f3b22cb8a596e32bc4d.nq.gz
    ├── 5bbb4adb4fd13cace75268f220850cbd3fd76014.nq.gz
    ├── 5c153f041a198c2656da1fe93f7687c2e1762ab6.nq.gz
    ├── 5c32a5f1c6ca99d1a81a53920202261468cf988b.nq.gz
    ├── 5d14bcffe81c7aa725e8c42deffc8cd81f379f93.nq.gz
    ├── 5da8d868399ce07e134e2b7e0db7d5a24d82356c.nq.gz
    ├── 5e0e40a544c7a621df2d63d353ba7400eb50f426.nq.gz
    ├── 5eddbf93ecc5238eb245281d7dfd62c6d19f8fc5.nq.gz
    ├── 5ef0eec599e0d8ad0f01337d853acad98299f90b.nq.gz
    ├── 5f70c81eb2cfbef34fadcc76118a2ea077331ef0.nq.gz
    ├── 5fb71a6421f499b4ebffc685218275e2d7325439.nq.gz
    ├── 60bafc1073fd57a65209a2dbf7ff5ef574107196.nq.gz
    ├── 6201c2e1fa816561445f17a94a1b404cbccba00b.nq.gz
    ├── 626937615907e4a54f653ed53b089af2045ec9fe.nq.gz
    ├── 639e3f141cecda9a830cf861465637f5cec139f5.nq.gz
    ├── 63bfc926272c563d24602c36405da7b7af0a1e64.nq.gz
    ├── 64eb3df57d479329bdb6290f615042b0639ab224.nq.gz
    ├── 651f3110a0d479c9394fd008091e088c46dd2108.nq.gz
    ├── 6592b65f10023965f0e33651af069fde50ddfc31.nq.gz
    ├── 662a7099b11979d045e679310b025cd4bbd02700.nq.gz
    ├── 67661c2d561218dac007d79b8efd823f08770cb2.nq.gz
    ├── 67917e8a2be90d7bd40f667ea7f072be82881c76.nq.gz
    ├── 67d75ae15f8fbdb02aad65e1112741ab22ef62dd.nq.gz
    ├── 680b6ca04f069cb6d65850a0029222779fc6f1af.nq.gz
    ├── 68dee3bad280a4c1db4dd9bca40498ca34b4b6ff.nq.gz
    ├── 6915136d1499fd3bb05a08056d90f00f8783959a.nq.gz
    ├── 698c6e5e9d88f72960a8bf166e98931f8427069f.nq.gz
    ├── 6a0f90d84f5b6b56e5cf2132150d5eef19a4f01c.nq.gz
    ├── 6b01ada74730b37f82de34e37030cf2c6f3810b6.nq.gz
    ├── 6bfec7067ad87a735c5eb3304720d7ba268e2f83.nq.gz
    ├── 6e795f7f16ff7bb6198e357104f66ae1b30395eb.nq.gz
    ├── 6f969b8a155c38b305f6d56e890fbf70a50c131c.nq.gz
    ├── 7254d4bc9c12a5e49cea9f4797d13ecdb1872129.nq.gz
    ├── 74704b3ff0b498b5ae7be72b0c60b3138b88a915.nq.gz
    ├── 74b4d7c053bc8f3b6338274428142cac1ebc5985.nq.gz
    ├── 751c75daaa2d05e8e61ab18801046521b8017874.nq.gz
    ├── 7654a723d6efb9ba4cae6a193a3ee93b452d36e2.nq.gz
    ├── 76ec9f59e8e234dbcd600f35aef982b1082dd19d.nq.gz
    ├── 784bdbefc31a48e56772e38f352411a36897cb1d.nq.gz
    ├── 787efea5402b019baf5d4cf65244a4f354b5f34a.nq.gz
    ├── 789cf1cb035c4bc95673af87bdf67a5a5862a6a6.nq.gz
    ├── 7904ab06596efbc61b4c0cd97d69251fde8ed5f5.nq.gz
    ├── 791042dee8dbfcc70b728b80f45c38222119a897.nq.gz
    ├── 7952b9356e1c8a44e828a30b653b4e19bea25085.nq.gz
    ├── 7a188c473fdf2c8e15fdb8c6c32f714859a215a0.nq.gz
    ├── 7b6d89def8ca45d30db0dc1fedcda350ad36b6ab.nq.gz
    ├── 7b6f387a3b8a45e886104f61fab61ca78694898e.nq.gz
    ├── 7c85fb7b2f84647817016f99881274c01d85c4d0.nq.gz
    ├── 7ce155ca7749b87738ab0abd9549af92e0611afa.nq.gz
    ├── 7dca57163ff07e9c3ada681c309f496bf0f838db.nq.gz
    ├── 7e9239cbc5b887da16762fe070c378606323474f.nq.gz
    ├── 7ebebacc1d3ce83df3e8ef09c2062d8eb4cec51d.nq.gz
    ├── 7ef14b69c18de600d33a793f7fd9da1c13ff7f97.nq.gz
    ├── 7f912e8f210371b455989f3a81874e5c33b01f00.nq.gz
    ├── 7fcbc9e4e5827274e630caef616fd94ece84d43c.nq.gz
    ├── 808b823468c4d1eaaf2e91efab429d4d182d2858.nq.gz
    ├── 81726804311871cf838c48e599a5e7fcf3440ea1.nq.gz
    ├── 81b5367100fefe2c79e37ade893d1e5c894b121e.nq.gz
    ├── 8230fbda7023d2ff6d4f08f33678656fe670e53e.nq.gz
    ├── 824a42cb47baf909e2e39b9982994a6b6ba41efd.nq.gz
    ├── 828222cbd0504789fb7585bb12909a072c19470a.nq.gz
    ├── 85642bef117a2abe3888075e2998b064b6ba30d0.nq.gz
    ├── 85b988a1f8ae995983bdf6ebc27725860c00803e.nq.gz
    ├── 868a29a8e8428d177abb8306e75a2739f5670233.nq.gz
    ├── 8849d900c2442d3e16334ea9d637d547f3ecb288.nq.gz
    ├── 895693cff437c60bfaae4bff4b0068410239bdbf.nq.gz
    ├── 89c68ace0624a54041831516417bee36b516e92b.nq.gz
    ├── 89ff8fc09de2dd96bdb5eebd3ce6417c04983ad4.nq.gz
    ├── 8a2cb6b5a39d0153935161da89cb8b0014467f27.nq.gz
    ├── 8a2f3076f5a834807269d9ada5c40feb92b15287.nq.gz
    ├── 8c24c3d37f014e3b315588cfa4668e4465d0885a.nq.gz
    ├── 8d5070be30835c2237ab8b4d34901bad11cfeec4.nq.gz
    ├── 8d5544a91feb06740cfce062e88cf2a6cbda2e93.nq.gz
    ├── 8de6d6ab5996c3ac5ff357344f94af018d188854.nq.gz
    ├── 9014bc49f764260f2c34f77c0ae534e3282cc6aa.nq.gz
    ├── 90b9c51e0c9d9213baca698f62fb52dca4330abc.nq.gz
    ├── 90ea1a5f931b9cfe388ff3e477d36b25c0cd6283.nq.gz
    ├── 91bac5b7db95711ac78a07eab45f0468fa17abed.nq.gz
    ├── 922a0a792aae2d31b8aa3f9e4602f2b4ba5f1f47.nq.gz
    ├── 94356b96b02a36c1dc56fa2571c732f81a215c13.nq.gz
    ├── 94728840418678c81cf2ae4f31d2b5d79e6aaebe.nq.gz
    ├── 949609298344117f4ef441f4b15ae929d03bdc1f.nq.gz
    ├── 9503b061e5a0bdb450a243e1411b68284b0289e0.nq.gz
    ├── 9604e7308755b2cb00f824ce8aea77fee3a44a73.nq.gz
    ├── 96270cd96b5dd3ddfffca18ef14bc887d593211d.nq.gz
    ├── 96e233c2f906216b1affb403d820ea060eae5ba2.nq.gz
    ├── 96e2ed9cff2b3210761986e773aec9bd490355ee.nq.gz
    ├── 970399b8952787aa73b0b7b3ab3dabed573281d7.nq.gz
    ├── 978902d23bcec3fea1a544c046d00d59e915a7b3.nq.gz
    ├── 979258bae61819f6861b25445b0d88bb8dc5d4e6.nq.gz
    ├── 985f0c59078a28d2efcbcbf36a850b468f02530e.nq.gz
    ├── 99893190703a0bc7f5d455d923eaf4a40d6d7ae7.nq.gz
    ├── 9af653761370f2243506f45d4e10786e3aa6ef3a.nq.gz
    ├── 9bac239de6de5d475c54f56c17bb37c0a2ecd3a9.nq.gz
    ├── 9c03e1f3a099037a7852667ff180320328bd6b3c.nq.gz
    ├── 9c31080e834fbdfafebd0986593134a3a45fbca7.nq.gz
    ├── 9d6298f92acd802ce88b9149e70dc45d98a10327.nq.gz
    ├── 9d81beab36f96814d2e7af1f595fe3d06a6a0fe8.nq.gz
    ├── 9e5691a71b072f5b23326b1b373233140b47f3a7.nq.gz
    └── 9ebfef01518da4f2f99ef8ef532d80fc1cd74bf8.nq.gz

8 directories, 200 files
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

[oxigraph/oxigraph](https://github.com/oxigraph/oxigraph)

---
*Parsed on 2026-04-12 by [repolex](https://repolex.ai)*
