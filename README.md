# Repolex Knowledge Graph of optuna/optuna-examples

RDF knowledge graph data for [optuna/optuna-examples](https://github.com/optuna/optuna-examples), parsed by [repolex](https://repolex.ai).

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
rlex download optuna/optuna-examples
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e96f65e01de1571b4f528e4cb8d91a306af4100f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e96f65e01de1571b4f528e4cb8d91a306af4100f
│           └── chunk-001.nq.gz
├── blob
│   ├── 023f710f1969a1963e9261f5583ebdd1d349a7bf.nq.gz
│   ├── 0393456acbe1b954b3f7b6ef17c6b38618d1a371.nq.gz
│   ├── 05f139b8edea8db431b7ad41aeff2251ecc601a6.nq.gz
│   ├── 08540a2e4fe8ba9038555f431ad92a60ac999462.nq.gz
│   ├── 0861010047afb4ed4e273412679c3657dd25195c.nq.gz
│   ├── 0bf60e4df4362e0889a6d1129d48a037857f8ff2.nq.gz
│   ├── 0e8a1d6fb60827599ac9147f3ebe712fe0288c49.nq.gz
│   ├── 0f04c49c584b244064a3ac911d1c15644d997f68.nq.gz
│   ├── 14ca67e954a713f031ba99fb312bc18490a32564.nq.gz
│   ├── 194ab411ab2b859ebe4c6e1487122b6641a81acb.nq.gz
│   ├── 1cb2dea240d50bd4fc2cdcb5859f11bb4637b715.nq.gz
│   ├── 1e632887a3833d6c018e5a51d0b013e806fb3cbe.nq.gz
│   ├── 216fd0a951b7778dde25f3653a3e3111066d2073.nq.gz
│   ├── 2232909a033a479544cee182e03a5136713de14b.nq.gz
│   ├── 22ad015ab36e71cffb2609bb801673aaf9a059f0.nq.gz
│   ├── 2481e1bb0c79edb2448507f4c5c470ac2d4764ec.nq.gz
│   ├── 249ed2b663f72c69ffca2116020707090edc9e89.nq.gz
│   ├── 2815229795c6fc96a58b4daa18a98767797eae87.nq.gz
│   ├── 28f8a91c4063d16333758c9dbde0ab0494b268c1.nq.gz
│   ├── 2a20fee7de72a5fb5cd8b8ef0a690e8272025067.nq.gz
│   ├── 2b0d0477582f9bce9c01d407098e4dd9989cc54d.nq.gz
│   ├── 2c37e1f087f8d97099338702c90d4c2b235c294d.nq.gz
│   ├── 2c3b2ddc5578d9fe2c64f63e31467d6e65a1de30.nq.gz
│   ├── 2ccfc436a049fd20aba7f10e3261d55cd7454e77.nq.gz
│   ├── 2d8602cb8682d596a26727981a0734fbcbcbe998.nq.gz
│   ├── 2ee3c75ae8053b213aee9c1b92c225420f419591.nq.gz
│   ├── 302d648a8653397c8a3f69fe611c8f79cc2dd49d.nq.gz
│   ├── 30354555839798886318788af204e0822006649b.nq.gz
│   ├── 3478585ee685d3501b66eb83fa64c781c60da891.nq.gz
│   ├── 34c21b69f7f447e89b155da552e76b0585a31620.nq.gz
│   ├── 34c9dc794d56e3f25cf98edec8ef0af975a906d5.nq.gz
│   ├── 34eaddf9ca30fa7ab1b014c02033c69f9f52ded9.nq.gz
│   ├── 3dbf51dcb02a9253c7cf3b3402f86523a8f77f34.nq.gz
│   ├── 43095f5dd5503c562c4e8ff9d87aa4315fc48f14.nq.gz
│   ├── 46ad5b8b3bb9a1011c319600cded3c0945490f8b.nq.gz
│   ├── 472976a97a58241c47a25c5c802169ba47ab422d.nq.gz
│   ├── 482ba30062d4c50f46aa3be4388b48c03d071a62.nq.gz
│   ├── 483b13a96f35f46efe4af7c53dc39e658185fa51.nq.gz
│   ├── 4dc05e1103d95ceabcc667024a5afaa499e2e6cf.nq.gz
│   ├── 4dfff33c5150369e0fdb02e90904e6c6c1cf74ed.nq.gz
│   ├── 4e0629719b9a268e19b44a5a68e78791dcd92b5c.nq.gz
│   ├── 4e3192067ff7ad60a04e1539e934b2dd99d1539c.nq.gz
│   ├── 4f4b7a04ae81ca916500ad98847f0f01547a5797.nq.gz
│   ├── 529b191d1838f7c68250b1b421e4654f351197b5.nq.gz
│   ├── 545378e31e644985a216239a38573212ae1c54c3.nq.gz
│   ├── 57048231815d2442f9e67472bdb5f6c528c8187c.nq.gz
│   ├── 590b85033ba176a767a5230a71c3e40f0eda0503.nq.gz
│   ├── 592117186ae62c8252f961c8e9a38fb181d8b80b.nq.gz
│   ├── 592e927146c6e352af23dbae64130d4fc0c8c96e.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 5b79e70c0d182d939b3e7827bdc8c30f48445b43.nq.gz
│   ├── 5d12726ccbd830fcfa7243996ef7fbb7b9d34a43.nq.gz
│   ├── 5dd922fe283984b3eed983f23a5d9caf445d9841.nq.gz
│   ├── 63339895fb3e536c76815d853ba34911a658a113.nq.gz
│   ├── 638dd375f786e1209593de7af872c538d48a1cf1.nq.gz
│   ├── 654c641ea7bfadc68c7136fe425f56f5de83d472.nq.gz
│   ├── 6613e3e7876b11f9b28b744640c66d13ec1f960a.nq.gz
│   ├── 663ea56520376b50ef0d0524c168c8a40b170cdd.nq.gz
│   ├── 69755cee61208e54bf905ae6459d233e800bc008.nq.gz
│   ├── 6a6cb95840490ec8f3f0582205e98b100f8c11c6.nq.gz
│   ├── 6bbc1aa30fa6b9da220988c696b0750bd475c5db.nq.gz
│   ├── 6cf72c6201a60419e013d6e9f45f4f65ac417594.nq.gz
│   ├── 6d8c6b35d2cb8fc076193b422223db3077cb471b.nq.gz
│   ├── 6e853b2c1fe0259af768a840286ed4cd580b2072.nq.gz
│   ├── 6ef8cb2e576cb3bad4070f001b9cd9215944b529.nq.gz
│   ├── 72429584d2f16670c297336f70b9f67286d0c933.nq.gz
│   ├── 73303eae95ed7464d1759613fb6e557d264663ea.nq.gz
│   ├── 7526235beba662e6f7eeda0f1ee194f9ae1c3b25.nq.gz
│   ├── 7553cdc47ca18ab54876870f58b7325fe2c61826.nq.gz
│   ├── 76ce3ff422c286625298cacebe5f3818b2e73ec1.nq.gz
│   ├── 78407325a0201aa3c175edeaffe01974fb5c1c32.nq.gz
│   ├── 78e6944afee08c1a980619bf1f159af2a19ef11b.nq.gz
│   ├── 794fb1fddde676bd2bde9f8de97e59c2d1b35f9a.nq.gz
│   ├── 79d764bca31e749dab455f03407bc8c59128f639.nq.gz
│   ├── 7a29cf74c492a1408479e546e4b77454f068438c.nq.gz
│   ├── 7a621e9efd19626d19e0144f23a6b64aeb7e4982.nq.gz
│   ├── 7eaef25bc80438add631e3e2e74307bb625f4788.nq.gz
│   ├── 816a35e824dc2dc3a0e182e2acd54629db756390.nq.gz
│   ├── 820089105b5ab20ef837d36e089f4ed5bf78f3be.nq.gz
│   ├── 82031326121f1298386979512fec9b91508f50b3.nq.gz
│   ├── 82606197da954c89a3d21a12cd7f543d698700d6.nq.gz
│   ├── 8372ddaf4366fe0b63f95824e9629bd0b8bb8ddc.nq.gz
│   ├── 83b6240ccc87537b828cb8c9b32b4dda9e2b8abd.nq.gz
│   ├── 84147f9675083d305be411a9157a1123d13a8080.nq.gz
│   ├── 8450217be7459af7db7aad6614bde509b6feeb03.nq.gz
│   ├── 845b46f01957a8e8d61560136759e78891dc95cd.nq.gz
│   ├── 8710b6b6e2ad9f4ae97ae2cd935fd971c7e4e037.nq.gz
│   ├── 877dbf2d228a3f02617244254e2c2cc70990ddb7.nq.gz
│   ├── 885675b99e0caf2d7c0017310232c2351389ab26.nq.gz
│   ├── 886b616aa749cbde6391a7d439dc8c4bb12ebeb0.nq.gz
│   ├── 8a359fde289497deabca156906dcfc71103452c6.nq.gz
│   ├── 8e53394e1d725fb8f8086a1814533c1bd378431b.nq.gz
│   ├── 914dcc7d99419701ea4f7afa58fd820feee23ffc.nq.gz
│   ├── 919e6380045a3cdfa8c95274f9bf30b397f5e45d.nq.gz
│   ├── 9568632f5632769432d0667dc8ca41a2ca664c95.nq.gz
│   ├── 956c4191fb4fd56695902d96583e7d5ca991db48.nq.gz
│   ├── 95e1cd5ee5afb4db95848c831af083a1599fdab2.nq.gz
│   ├── 98cffb57c3abf2ddf8f9003b32972a424a880098.nq.gz
│   ├── 9a635b910d93ff2d9b1c24b7bc7ce15600b65d31.nq.gz
│   ├── 9aa6586d6c3b0c64eb05e13dfa5b447f232e91c4.nq.gz
│   ├── 9be996e58286338d9646babfd4d80f39a962f6c0.nq.gz
│   ├── 9c599ff930c4a6e8e9ae9946782f689f13399f9c.nq.gz
│   ├── a058a6490bbe516de0fde59a1f05cce50e4251dd.nq.gz
│   ├── a0659a90739d3dcac798702907d6ec09df0c10b9.nq.gz
│   ├── a417dacd4e92fa8d53b881164ab81519db89f89a.nq.gz
│   ├── a42c46cdae099392af1ef4623caf7874a725345d.nq.gz
│   ├── a5b5bd880f7e3a23f33b4e971b066d090cf30bec.nq.gz
│   ├── a64631e976beb6f299e5b27948de66bddca854f8.nq.gz
│   ├── a6717e509f173a8992f0924c1c067cf5be8e4818.nq.gz
│   ├── aaf757abfa6659809e98b878146869273f1e4323.nq.gz
│   ├── ae10e02fd4a289bab0c7ab90bef2f574680df15a.nq.gz
│   ├── b0e784173651c0e00bc36184e4b77b472b2d8c73.nq.gz
│   ├── b2a11d8f25bf31c6b313231a3a29ca41a2528720.nq.gz
│   ├── b35d041462fe42ed11f85a20042d15174c3dad45.nq.gz
│   ├── b4afad97f23ed7fb4b86382e30891745106c1377.nq.gz
│   ├── b555b545b7bb21e8d304452afc613b83315c8b70.nq.gz
│   ├── b5c82bf2f83ba5b6cd9f7fa998497c62e0575e82.nq.gz
│   ├── b79d2e2a4718a200d2317b8113c408b50d5cda85.nq.gz
│   ├── b7a69217cadf88a7841175d3a7928db4a76b42c9.nq.gz
│   ├── bc9609a6edd6ddeaf6ef5ed0db159f6b588b88a2.nq.gz
│   ├── bf20cd834362bc25e0aefabd60321f91c019ae75.nq.gz
│   ├── c01033c614064cd09c3e062c62764499aa3269e9.nq.gz
│   ├── c1d37d980acd535b9cda9011a2f8d1f4c075423f.nq.gz
│   ├── c210090fea7bb22f08d2864692a878487af8fef3.nq.gz
│   ├── c89b3aaaad3217891f05a242eb525640337322b4.nq.gz
│   ├── ca1583e85d382f69e4c35f71d0be576c0100a9b5.nq.gz
│   ├── caac90cf988fb4da94601287a10cdde3a5b2e7cc.nq.gz
│   ├── caae9dd3c062402355c7029341034c9284c9341f.nq.gz
│   ├── cb8ca839fb6e9952ec95a17840cedef6287e8b68.nq.gz
│   ├── cd01b072be82062d374732f22f451b84519cbf3f.nq.gz
│   ├── cdadd893a8b841d4cb10cd166fb578a73cd29ba2.nq.gz
│   ├── d077cfabf18616baf88b6ed678f1aa53d4c4e218.nq.gz
│   ├── d3b6b01a6915d9e4d3b271209aaa98e32feb6a45.nq.gz
│   ├── d3f56fa99c6255b4e757f4b784a08e4f6bf84a70.nq.gz
│   ├── d443983e3eb98eeab64703f245bce93cb8c46b96.nq.gz
│   ├── d4f044d0917d2f17d007e1543507f3575a56f27f.nq.gz
│   ├── d6e6af3bc65c62075e10268210702ac4cb35e177.nq.gz
│   ├── d7b2903c7619da163f1d78fc87c09f1d668cde0b.nq.gz
│   ├── dcddf1e5eecdae74c787e74b1b158f7293fa3d8e.nq.gz
│   ├── dd3c984a8b826845e69151658fe81edebc2d0a38.nq.gz
│   ├── ddca0024ba93033f187df8ca2252c8be1f02f5c0.nq.gz
│   ├── ddf62235c51a2000dd1ca7c1f34deb1c71611e77.nq.gz
│   ├── de1cf868e97fe9221386a90065dbd8969d785dbb.nq.gz
│   ├── de559100c470e7a6eb5556f3cbdbe4203fb78372.nq.gz
│   ├── debe27f2764a478adc1bc1c575d45876e6063388.nq.gz
│   ├── e0287ad25f81baf2f404220c97d28b5f4e50ba89.nq.gz
│   ├── e39085e737156d04229ceb018addfaf6078fb412.nq.gz
│   ├── e42ef4b166dbd2c6a4194dfd36f840c0d5d312c6.nq.gz
│   ├── e4598c653741fe24209d8b5e712c9a53f8764581.nq.gz
│   ├── e5a13ffe5d6d2d024f698ea034ee529bfe0f4857.nq.gz
│   ├── e94baa49e7093b5fb823cdc85f66c0f96938d30b.nq.gz
│   ├── ea5217a3b567cee848821a859312ab36078ae913.nq.gz
│   ├── ea8bcd5d247886f9718af4bd4ccf82ac3c512284.nq.gz
│   ├── ecd6c7938dcfe512c6a7abda1ee41e9a226509f5.nq.gz
│   ├── ed317bf94b18a163a85686b1e0d2aba78e84a906.nq.gz
│   ├── ee91bef7b3f6fe4a79d77f321e0a6b8681f3c7bd.nq.gz
│   ├── ef41d7dc16c7c07ea55760ea606fe2d311ee7119.nq.gz
│   ├── f4bdb5514cb173835d4f320e129c16060f223960.nq.gz
│   ├── f6831bd05bd0755b3815bfca757faa5f76f8b7e7.nq.gz
│   ├── f7ebeca5886796d815a6ba2489aefd941f86e1ad.nq.gz
│   ├── f8cd699b913a2a4ff39dbb9190ec2d928cc9aa33.nq.gz
│   ├── fc76ad0245405815802630d9e592d7167b78fa4f.nq.gz
│   ├── fd6f7d190601140a5cfad237c9f4130b568e9073.nq.gz
│   ├── fdaa4b439741109d983202cc61ffc045c20a4aa2.nq.gz
│   ├── fe55e18f8904d7eae41cd4ddd926bf55429231a9.nq.gz
│   ├── fe7131881ed044e2001cc933ad9e629d918e8c41.nq.gz
│   ├── fee985a87c1b5b138794093db39ffb1364451e32.nq.gz
│   └── ff9396f37fbfae49024a58635e532600f5b3b9df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e96f65e01de1571b4f528e4cb8d91a306af4100f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[optuna/optuna-examples](https://github.com/optuna/optuna-examples)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
