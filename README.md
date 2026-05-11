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
│   │   ├── 27ee29798f92742d4745f89276d8f1df94f57ac0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4f8e1d890eee73062eaf809b779ed1b276aa11d4
│   │   │   └── chunk-001.nq.gz
│   │   └── fbf58310c1f1d8de04c6c90ed8a68f6d7da5a880
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 4f8e1d890eee73062eaf809b779ed1b276aa11d4.nq.gz
│   │   └── fbf58310c1f1d8de04c6c90ed8a68f6d7da5a880.nq.gz
│   └── repolex
│       ├── 4f8e1d890eee73062eaf809b779ed1b276aa11d4
│       │   └── chunk-001.nq.gz
│       └── fbf58310c1f1d8de04c6c90ed8a68f6d7da5a880
│           └── chunk-001.nq.gz
└── blob
    ├── 00e97a979b2018a4052491a7754c540aab3e9f6f.nq.gz
    ├── 011567ae161d9ecd218187ba0d20aaceae7f16ae.nq.gz
    ├── 01ec0f2d5a25bdac05766c836ee58ef95d942aeb.nq.gz
    ├── 02e0718467a67b93ce49cfb10bd7263ff6e234ed.nq.gz
    ├── 02e7728e1b085d8ff935af5b7ea64d23b706b0b0.nq.gz
    ├── 03723e28ee8eff8bcf63172c1a60f5cb14abeee6.nq.gz
    ├── 039752e84d55c669775687264cf3d8a47212fd26.nq.gz
    ├── 03bab7b91e83a8a90a44e4e40b5957fe21641274.nq.gz
    ├── 048d12fe3126c178e5831a3eea35e234895f1890.nq.gz
    ├── 05c672def631edbe6c236cb9fb771b91486280ad.nq.gz
    ├── 05e7082931e2e670b61e86d3d1418ba2b64371f7.nq.gz
    ├── 068580c1f2cf483529e099717adc3cc426a8264d.nq.gz
    ├── 0698fd48633b5d6fb014ad5eeeef71feb4002caa.nq.gz
    ├── 07524c2cdfac65ea57efb0a1331f8a9c6ea637ba.nq.gz
    ├── 07a7c2ad7e36ca4bae2df61bb0643ba43b553bec.nq.gz
    ├── 08cf004a1e668ca909d59cd57e2aa722c096b849.nq.gz
    ├── 099ae76128416abc8ca6111391d29999c7f7ace7.nq.gz
    ├── 09d52581c2ebc0040781d5a0b80e1a897f1f7eaf.nq.gz
    ├── 0a13368fb268f4f3628e557576f2ef819b8cd9d2.nq.gz
    ├── 0a58b66161b64a40416048b6be68c6d02c29c1a9.nq.gz
    ├── 0a7ed56400831a42bed740ec5070d3726c6742ae.nq.gz
    ├── 0c14b7b64834f1ad900e04924c264d4fea692967.nq.gz
    ├── 0d1fb1fcf5a7169cad70cfc974c327d2a1276a85.nq.gz
    ├── 0e1c40a9aa9fb3a64a2e8c57fd6e2597385ade23.nq.gz
    ├── 0e75b7b7f7d683bfb58becbcdd921a4b3e76c09f.nq.gz
    ├── 0e7e5e95af8cd29bb7999da9ddcee313acf6cd47.nq.gz
    ├── 0e87bbe5b2bba1c6864840946453c570439c1597.nq.gz
    ├── 0fd648d1be13b68fee00f4ee07ff18c068fcae83.nq.gz
    ├── 1005494df2612c5b445c41d9e64bfaf2ee1d6dc4.nq.gz
    ├── 104a8631f4a8387db51d31d44ac271b6a04b151f.nq.gz
    ├── 105513465f4d82a016ba79efc9444017eefe171e.nq.gz
    ├── 107c3c1f7315be0de76028c77872b827c7a2160c.nq.gz
    ├── 1222f3d0250c235f356c170490677c781a86043b.nq.gz
    ├── 125dfccb4e3589c8e9910ba4a01031c433dc5488.nq.gz
    ├── 12e38b612d5de2a9da7311f6821111ddefdac5f7.nq.gz
    ├── 133717545aecfa4f1ba589165a058c04c7e2cbd8.nq.gz
    ├── 13805bfd45ffbf0ba2e2780e1c25bf00f60311d9.nq.gz
    ├── 13d3926aeb226e16f608bcf41f82d857c6ed55a3.nq.gz
    ├── 15b9cdbd66e743a76742ff7922f715cf15680e93.nq.gz
    ├── 1620cad2bae872c9b644d8cafd0bb0246d37f0d7.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 17279ffbb751bae0af323801c65a11d7b95ecb02.nq.gz
    ├── 173f98d192307437908c6d7a8b5e369b6342cd14.nq.gz
    ├── 185c89ff02044b664c19b6722558114ddc20770e.nq.gz
    ├── 18c10a669f22d889bf354b1bfa63c6c10d95d5e3.nq.gz
    ├── 190eb1f613accaf3b6b8b4c25a5452387d837175.nq.gz
    ├── 1aa600b7c1c01760312264ae0e595228d680265f.nq.gz
    ├── 1abf4e46f3c794dfdae7b339c7636b843441aaef.nq.gz
    ├── 1b865fc8d4a1cda03f633685dafff70f4875ea59.nq.gz
    ├── 1ba34808a7634a70922bda30a728fcdf38ce0918.nq.gz
    ├── 1c3291ccb50e89af6cbbdb71b17ec4728f8929c6.nq.gz
    ├── 1c441be2bc94ded9eac2f53d2211c1b57855c748.nq.gz
    ├── 1c748f17bd48c61b257b70d79e4202ffcf405808.nq.gz
    ├── 1cc68bda58ad8628f4ddd5c3bed22dc5fe7e24c7.nq.gz
    ├── 1d0cc18505ad7872538c57d078dc646ef5e0203d.nq.gz
    ├── 1e294cea2b4a5de51cf2d97ffdaf745650486323.nq.gz
    ├── 1e492d8621be5a3b4ef252ddccbba42d9192586e.nq.gz
    ├── 1f15072363c1d1a2d35d7c429ef6f5b9c47a8078.nq.gz
    ├── 1f59436b8403ae7cc1b83ffbfdc8f766af54ca0a.nq.gz
    ├── 1f94a53eb23fdaa0d68da4a595ca755b205e088c.nq.gz
    ├── 202817ab17b4da5b21c11f68c2382740da9a6da5.nq.gz
    ├── 20b7ebd0c8c5bae5710e59856e10bf2e449c2ee8.nq.gz
    ├── 217135e081dfe8b8de9033c62c62546be9c22d03.nq.gz
    ├── 2179274dad00e5d91e79b6a804f7dcfe0a912054.nq.gz
    ├── 2227c9ac35c1928b1b59a27b0830932e6245616b.nq.gz
    ├── 2296f7d68383099be42c459bb04ed1387742d6be.nq.gz
    ├── 23624131bb4a7afb7ae29b25b3f39a0010a4053a.nq.gz
    ├── 23a866d05bdf10c9edf55361930135b104ef9c61.nq.gz
    ├── 24e7337e338dd420ce75ad568022127a732e3243.nq.gz
    ├── 24faa1876a3ddf8380c03ac0dd643163bc816b00.nq.gz
    ├── 2555ff9cac24b3d1ca8aec92e38241766493a43e.nq.gz
    ├── 25a6b8c8a9634e7501c610a48a4a3ef5c1363899.nq.gz
    ├── 265ddffca516d27400900b9ed5aaf14f15329918.nq.gz
    ├── 27c316890d152e8e54e54f420dabb0e60a075717.nq.gz
    ├── 27dbf7a015482c5049ef0e7095efdeb3e6428dbc.nq.gz
    ├── 286142924040ad94eac25c846f5325e7f9153ec8.nq.gz
    ├── 2885effcbd354f9d50316d8f56544faa6197b4d9.nq.gz
    ├── 289a8e551d2ed25cba69572f43fbdeb90e81d462.nq.gz
    ├── 29c92751531a0e4fd699dffa671593e0b9933270.nq.gz
    ├── 29cd43ab303bde1b4018fe5ab493637ee26c256d.nq.gz
    ├── 2a2faef2faa19504a98c719bd65e11c33384e8d6.nq.gz
    ├── 2a569b60354767782b654e65401d77f3f7c354f8.nq.gz
    ├── 2ade3409cd44e0fb90f053f59298380a7da7119f.nq.gz
    ├── 2b14efb14a3de33d4c9953b0d592c670870af2ad.nq.gz
    ├── 2bf84674fe3142c1d239138c39df1d9678c1d733.nq.gz
    ├── 2c981e22750d97fe5ba4017e49f9239d601e1b66.nq.gz
    ├── 2e36e34e4f2ce347828d408c2e7749415cd8f2d1.nq.gz
    ├── 2e7ed1b1428cf753bae82f84d6ffdbbe6f371675.nq.gz
    ├── 2ee89f8093bc07d3b75b668e581648e155a78866.nq.gz
    ├── 2f873a580826b1cf27285dab332193986c8d2a87.nq.gz
    ├── 2ff9b4055d1735a55143796cb75074fb5ec949cf.nq.gz
    ├── 3108ddd26c0decd64d33a1a4268fb84089c2ce0b.nq.gz
    ├── 312cfa16ad629bb8b2c4c86fa1b8958613b36bbe.nq.gz
    ├── 3202e3e20099fab27a075b71841b68d228263720.nq.gz
    ├── 324f2ae294d337872900c2df90bc6f2349a6f888.nq.gz
    ├── 32600adaebfa8a0a7b00923ac330c13ce0a3ce44.nq.gz
    ├── 329b9033a47a56ee17970be15563ef011771c300.nq.gz
    ├── 32b3b35c381cab5e19c4856856196cc8c05adcfc.nq.gz
    ├── 3316858d3ca1fca55b813099b78ff7634326d1a3.nq.gz
    ├── 3407f40237f929cedfa49ab5a673d8491b872b81.nq.gz
    ├── 3471fcd8c893b32f393206258ffe0d251045ab4a.nq.gz
    ├── 34b9c22d27aa976edb2ac1209e0fb5db8610a7d5.nq.gz
    ├── 35b2d6f4ee7b2942fb82c0e84929dc63a95d98dc.nq.gz
    ├── 35bfa1a1385322072a1adf818d769eaf5e5c04be.nq.gz
    ├── 3760b66335f4eee7caeb303d097f9cc8fabcca6c.nq.gz
    ├── 37ea90ca62fdc6c544ae2dfd52a392ca865a7cfb.nq.gz
    ├── 38026c0d8a628b6b9a9164058edc9da21601f810.nq.gz
    ├── 38c761fd962d7db3311d83ac80487df7bcc1ac17.nq.gz
    ├── 3929c1528778e6d37f5d914ea0261e27973a9f59.nq.gz
    ├── 39b7a23a0757232acbf38ff30531a881c217f15c.nq.gz
    ├── 3a9fd05331db3b69080a0d1c567f8db6ea06a01b.nq.gz
    ├── 3ad605c41519afbe1f16612c891621fef84f0ad5.nq.gz
    ├── 3b515006da7036a9ec55e3f55d16088765a8a747.nq.gz
    ├── 3b7933e11a6295f8e54b5257af88dd97ba705920.nq.gz
    ├── 3bab996499514bdad5f483839c703ad8fc3c6f75.nq.gz
    ├── 3c4208ef6a10ff6599c68538773dc4c5337c9d2d.nq.gz
    ├── 3cc2136badea393f45a0e1bce229076b2d829dd0.nq.gz
    ├── 3d1a9ad482000bf3a04e991e67e3f892d4b35904.nq.gz
    ├── 3dc00ae3bab503ea0e9cabf6855024e478c3497f.nq.gz
    ├── 3dd3941525ad040824e4734b049cb2e6557e4020.nq.gz
    ├── 3e7058c4007b34d9812b82889c92123018124300.nq.gz
    ├── 3e81efbaaba5ab6d71cac4b5faedac911550ac6c.nq.gz
    ├── 3f869f7fe1a810d2258e1fa67ed0d5452037b3e0.nq.gz
    ├── 4137a8e160901976f45da5e86a5092c22057e77d.nq.gz
    ├── 414ae2ea707e11caa92568019fd3b8194a71aacb.nq.gz
    ├── 41f2dd0c82d7e4c9ffffb0c42d2235b311ac55eb.nq.gz
    ├── 4258026875d3c327ddb6fbeda5064a3815370a0c.nq.gz
    ├── 42a196d7022e1593455aaddad95e7cb595185876.nq.gz
    ├── 42d84087ac9f1091496ca6cb8f338f9200efe05e.nq.gz
    ├── 4310f137c65a511396cafd7ec0bcdbd4f514fe04.nq.gz
    ├── 432046187826774e7fb82554191d06a0ac3d3cc4.nq.gz
    ├── 434e93ebd51c5429f9e15c011c56d091decc625f.nq.gz
    ├── 4392b92b99b3e928da1bed7b1cfac5b6664b9cf5.nq.gz
    ├── 43ad4a6b30fc59fc1e66a76e75898012fa4bb5db.nq.gz
    ├── 43e62aadc914b6c9e0924295c9f466d04f1bd7ea.nq.gz
    ├── 4405857bab727bf6eb87f5bae8751881a4a04f56.nq.gz
    ├── 448915bbe85fdfc8017059916d2afb892e4b244d.nq.gz
    ├── 44b404021f9189fced620684d910c3ec1a0804bc.nq.gz
    ├── 44e9c32750a49853a21c84c3f0443760cac3490e.nq.gz
    ├── 4504e797479139af36b0eb33a7ff778d437e140c.nq.gz
    ├── 451f528a435bbe3468d948fb716d0e53c6c5ae24.nq.gz
    ├── 471821aeea25e1f078e56e42a5e498d8ce59e5ff.nq.gz
    ├── 48940f71e6828c228408c1c5f3574931feea0464.nq.gz
    ├── 48e39d8f75b903a97464b610a8369ff5b23f31cc.nq.gz
    ├── 48fd51eed563d7576b294e0573ef2c50ac0a95f7.nq.gz
    ├── 4a40f5e274394e4f869c504a81ac28639bdae1fc.nq.gz
    ├── 4a5c7691d680b94bc5fbb0161245e23175cc9ab9.nq.gz
    ├── 4b0e835438ce2348a5cbe87ea8ad713cfbdffc10.nq.gz
    ├── 4c15ecf2dfb55988cc59c23ccd1bee9cfee10a06.nq.gz
    ├── 4e01e3c4968829f267c53735d80ee8ca275bf524.nq.gz
    ├── 4e3bea6f64a6acb1d86cb011f84ae336a641c0c3.nq.gz
    ├── 4eb509c5e3e4905316bc6e5890080e0bce085979.nq.gz
    ├── 4f8b2645a87b6a9508728c0c79d41af7d2f52fce.nq.gz
    ├── 4fc78e23e72c0fd93b817856622707bb3f733bfc.nq.gz
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
    ├── 5636a358294f56b8cc31881d9bff8d3785d0f2b9.nq.gz
    ├── 5676776733c092aa13dc6c834d74053dc1d0e443.nq.gz
    ├── 57e8ddcd496ecd136b48e89061b46bcec05dc10b.nq.gz
    ├── 58c8a266db433e6e318c5f3b22cb8a596e32bc4d.nq.gz
    ├── 5adfc92fcbeb244246634c1bd7df789d953cf7f9.nq.gz
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
    ├── 61bb05c61d317a3ea24e7b699e8bbffa34938c36.nq.gz
    ├── 6201c2e1fa816561445f17a94a1b404cbccba00b.nq.gz
    ├── 626937615907e4a54f653ed53b089af2045ec9fe.nq.gz
    ├── 639e3f141cecda9a830cf861465637f5cec139f5.nq.gz
    ├── 63bfc926272c563d24602c36405da7b7af0a1e64.nq.gz
    ├── 648c4eab8df13cc1c76b3a160de4e69f8c16419e.nq.gz
    ├── 64eb3df57d479329bdb6290f615042b0639ab224.nq.gz
    ├── 651f3110a0d479c9394fd008091e088c46dd2108.nq.gz
    ├── 65494c5af88348d36194a7ff0858d633a295ca01.nq.gz
    ├── 6592b65f10023965f0e33651af069fde50ddfc31.nq.gz
    ├── 6597e1a29bcfcb35d09394aea1942f8325ac792d.nq.gz
    ├── 662a7099b11979d045e679310b025cd4bbd02700.nq.gz
    └── 665d15b420941e0cc25117325fd3e747996f30ce.nq.gz

11 directories, 200 files
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
*Parsed on 2026-05-11 by [repolex](https://repolex.ai)*
