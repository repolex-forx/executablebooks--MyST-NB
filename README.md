# Repolex Knowledge Graph of executablebooks/MyST-NB

RDF knowledge graph data for [executablebooks/MyST-NB](https://github.com/executablebooks/MyST-NB), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/MyST-NB
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 23b1747ff9b7e408244c62dd3981238ea193b25a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 23b1747ff9b7e408244c62dd3981238ea193b25a
│           └── chunk-001.nq.gz
├── blob
│   ├── 03769687d28c805a4696ff9bc27061cb6039e28e.nq.gz
│   ├── 06837614b03e3be16c3a045e1c8af0ad6c306147.nq.gz
│   ├── 0959bd67328966f9246aaff4bd072bf30cdd2d14.nq.gz
│   ├── 0b2802242c0d15e6b5dbf08563c808e08a344967.nq.gz
│   ├── 0ea97525384d4de61fc66926ca80253a4321c306.nq.gz
│   ├── 0ed540bfea4c2b4f831a0b0fbd2785f97bb3d192.nq.gz
│   ├── 109a9e48eab2c352338750233e38e46500db73ef.nq.gz
│   ├── 136559ded592716961ae8d4a5b1c26ac9689f7d4.nq.gz
│   ├── 13911b1a69482e331e477ebb1214fd1a49321f0b.nq.gz
│   ├── 18e7001a6e10b94e7c3e208056f4618eadf2e54a.nq.gz
│   ├── 1990b06728a82f830ff686dd6300bfc9d1bcd6f8.nq.gz
│   ├── 1a4528a9ee1fae15fdcc44e82ca3e643107c0b01.nq.gz
│   ├── 1afc97ec786204ba2695bb2bdbbaa43f9a21200c.nq.gz
│   ├── 1b773bae801e8aecfe37c35e2d94db577a941805.nq.gz
│   ├── 1bb52cfecdafd7633c69c6603bf1fe851e5e9ef9.nq.gz
│   ├── 1c1e83ea81e0420834b366b88eb6fe8ebdabead2.nq.gz
│   ├── 1da822fd3f6642502b8309b487cb17a85e972210.nq.gz
│   ├── 1e226162de1efc8e6830a8177c2b51306f49dbce.nq.gz
│   ├── 2451f181dd5ea3802eef144f33eeabd3fdaa4fa9.nq.gz
│   ├── 267bdb5391cc8cc23f3df55c4798a126c475a454.nq.gz
│   ├── 2ab5f899ce8852241afa4f722604874d57914b98.nq.gz
│   ├── 2b738e77a67f31bb7afd90e5b2409912d74ac5a8.nq.gz
│   ├── 2c3d087fa00ab499524ad36da2242a5c2735df4b.nq.gz
│   ├── 34d39dc9ec1cf21c526beceb3b31c6dc502237df.nq.gz
│   ├── 38935da12ee70c602a1674b0c8472a8619d158a3.nq.gz
│   ├── 3abece4106ba92c35ed5fef89bc87817f4082e46.nq.gz
│   ├── 3eccfbd034d7fdd14312e9c2195cda1b435a0635.nq.gz
│   ├── 41bfa6d1e8d20f98fb9df7a6c3e9592d738f58ba.nq.gz
│   ├── 4284f2d6ccc1894ea2e55c675c1c5a717d79da07.nq.gz
│   ├── 42a0d061785f077240d5d4870b42188845a86480.nq.gz
│   ├── 42a41b44a921656496d524b3df5a50b36864455d.nq.gz
│   ├── 473f759ea64035efc7a1d26a9a5965975cf1448b.nq.gz
│   ├── 48662c66310a7d0bf0ee4b1e2a49afe8273445c5.nq.gz
│   ├── 493dc2826a24888972aa00283265a425dc940bb5.nq.gz
│   ├── 495e5134c41bcab2ab42efd4f0cd6671ee5ed517.nq.gz
│   ├── 4a31aa02d3f56d9d795c5294b08bf48a7237d23f.nq.gz
│   ├── 4a3fbdae98f153c67fcf9f18786d8cb88da267cc.nq.gz
│   ├── 4a8597f6020040394ba13d1bcf8d7335d47dc4bb.nq.gz
│   ├── 4ae88e2b2547d20246802b50cffc3d01b217882f.nq.gz
│   ├── 4cd19273352029e3cab3d788b3367cba78be56a0.nq.gz
│   ├── 4d24361556ea6cad7f427217b7a04552bf929293.nq.gz
│   ├── 4f3c2575a66b913a129ccc78b06a902422f260d2.nq.gz
│   ├── 50cad6766354d27ab3e0c6f30438ae5e28e01304.nq.gz
│   ├── 50d0f36d65e240c7c82b27ef7c0ea11c1d840e9a.nq.gz
│   ├── 5140de477cf3e0c035ea5aad9feb4af3fc28496f.nq.gz
│   ├── 53aa85bfeb229a065a8798adebd1069136142e34.nq.gz
│   ├── 58b1f71a81049a1f6a8bc3a5c9ccb40d36911841.nq.gz
│   ├── 599a00b225343453785a83f3d2a67104284a4f51.nq.gz
│   ├── 5fa1c0544ed6e330462b0341dda0c973581e744a.nq.gz
│   ├── 61a455d03f2d7021cb9268041e85aab0d4a90102.nq.gz
│   ├── 633dd369338e06de264b1e0d2e8456b6d5d7f4de.nq.gz
│   ├── 65206737ebf65d8fc6e7bcde3a3f3f1313817c22.nq.gz
│   ├── 6795b2c9ce51aa7a794da306dea3d72ce7bf1785.nq.gz
│   ├── 685f11ba962bf866070d4ec8fe1f6dcbac9cfe88.nq.gz
│   ├── 6ab47e6e9c0b867e95a4bf6e1ec627400a750b2c.nq.gz
│   ├── 6c058db753a4814825abce4127ba48f1f03a7371.nq.gz
│   ├── 6d3e7ebf3040a9e5a2d9160363b82703ab4e11cc.nq.gz
│   ├── 6d8969f42728a433061d745ba7478edb8187ef15.nq.gz
│   ├── 6fded98b95c96e16c764a614e7a1c67ad3278b61.nq.gz
│   ├── 74b034b1f93d1d4ac6b29c41407648fda7c254b4.nq.gz
│   ├── 74f401291a1c28d002fc94b5aa7b08d758e70936.nq.gz
│   ├── 74ffcc85dfffbbf18be1999f737e007b6848f504.nq.gz
│   ├── 7575d2507bc80df2f842b0c7ed7015be8d8a366f.nq.gz
│   ├── 777fd2b0952cdb8a433328671c205614f80f1384.nq.gz
│   ├── 77c3d768a56c70f0c4b0664426691ee0755b04e4.nq.gz
│   ├── 798385a71be2d3500c01444b2a8ab6300a1a0282.nq.gz
│   ├── 7b2da3509ed76617d96312c779f2162c2382188f.nq.gz
│   ├── 7ba54c79fac5dcb6d8c6a72ca363485adf20801b.nq.gz
│   ├── 7beaacc9b999b976f23b204cf48ed812898832fe.nq.gz
│   ├── 7c7df80d068b3cce65f273dc2cfc9f1ce60234e7.nq.gz
│   ├── 80081d47557bb5894bfdae8642dd373759363b96.nq.gz
│   ├── 8152749c143a39a81991dd313293151e71f17563.nq.gz
│   ├── 84a6b35b21285dd0d8768c54195ffc42eaa93272.nq.gz
│   ├── 8a633929e4017a0615c686b4aa41473cffd45b32.nq.gz
│   ├── 8b6bd0b8bc71f8564ff9fa2e8941748a020b50b1.nq.gz
│   ├── 8b6f761b98c5e059c8e4ca213c1e1018405ee282.nq.gz
│   ├── 8c5705d534ed93152a415f87ceb829a8ab57b63c.nq.gz
│   ├── 8cbbca9c8b47dca28854746d4207f7c87c14756e.nq.gz
│   ├── 8f4d17cb43123d60c532e079147c2b1a2f6ccc91.nq.gz
│   ├── 917c00003d6a7b596a323eb736b039307404f51b.nq.gz
│   ├── 91d7352a1176cb6439729461955308fba1f8561c.nq.gz
│   ├── 9233786184d9fd2e7ae22cc45a0561c3b906758f.nq.gz
│   ├── 93e1203f4f63c47230e4dcf2d7c2fedf9e1acf00.nq.gz
│   ├── 960d5be67119b585df89308ccb32589ebf86ad87.nq.gz
│   ├── 961efc0305429a5dd1dcf5cc3b25d02addd9d29d.nq.gz
│   ├── 9a7b799664f1bfc6d9de3b1486343935b919e7cd.nq.gz
│   ├── 9a9e5adc47842713f1276f71a06e318ac84cfc7f.nq.gz
│   ├── 9b4775a35c36181302277a89e7d73ee73d36ad8e.nq.gz
│   ├── 9d56496a0e06e22f44c0eea578b1131cb2f5a5bc.nq.gz
│   ├── 9e0fde8e9b1406efb2db66c7b3f9d4ba7135f41c.nq.gz
│   ├── 9f3d7646bea55fa65e99c7bb69bf42e03ab3b97c.nq.gz
│   ├── a25fb40d1bfd0553f450a770a2137bfc23299f34.nq.gz
│   ├── a295d7467363153c194a999fa82e5ff05817ab16.nq.gz
│   ├── a2a3bf0c28f78de718bb9b57b6c013680323ebed.nq.gz
│   ├── a35d688c3ed27592076115061c80f7a6557bd668.nq.gz
│   ├── a495b71eea3a661880a3be2e45cbd89d6783bbf6.nq.gz
│   ├── a593c5bfcdb3e0492e2381172056604bf1eb94dd.nq.gz
│   ├── a5a38c80e4f2f6b338d1e6b3f38104d657785d9c.nq.gz
│   ├── a5d49cbde52a89125f189dd5f56861cbb770d880.nq.gz
│   ├── a8296d92d6466bfa286a51010e74220545ad5e4c.nq.gz
│   ├── a8a873121f1d32eb04c8c33ad41861bbf53f69b0.nq.gz
│   ├── a96f3438edf2fe324690c84185f92929b75663d5.nq.gz
│   ├── a9c2fd219097abd6250e8240213c9a8cd9ea97f3.nq.gz
│   ├── ab447279c278b458f9a5c9225662b45c4b574eea.nq.gz
│   ├── ac62502b42687e5914beba2d27812cc985dcd22e.nq.gz
│   ├── b003003db075db83a6fd82bc9c1963a0dbbb7f1a.nq.gz
│   ├── b07af311939dd6df0de5a6913b6d47431ae139ba.nq.gz
│   ├── b10f323a27c778a0aed7bcde41588d7d4fcacdec.nq.gz
│   ├── b12794e5c2b291aaaeb4e8d05c30e55f34986b74.nq.gz
│   ├── b44fc14699b506cda1617a71745fe6491e7e6b65.nq.gz
│   ├── b617f9cfe41b6a3519c86e0d08499fe0ee01c0b2.nq.gz
│   ├── ba973d7207660a523d7dfec5b09cca1b80a31097.nq.gz
│   ├── bcc7a38243fac9b14bc3cf925e5b1cb022c6fdf9.nq.gz
│   ├── be1e157aec6cec585ab23f061416614f35cfafdf.nq.gz
│   ├── be6e5204a82b29fdfe3577272350086f8b07e762.nq.gz
│   ├── bfd29e5157ff839992c7709987e19b69283949e5.nq.gz
│   ├── c0250080d6ec564b225c091a03eff4562a399280.nq.gz
│   ├── c06b11cf7272e799bf4ddea6eae615fba5d18104.nq.gz
│   ├── c31a015b5739f031347a3305d17d367d8ce4cebc.nq.gz
│   ├── c65676b56142c46a51b4c86aec705baa998a9ca8.nq.gz
│   ├── c6c03d3f2a07ef5ca0eb4e231be47b47151b5bcb.nq.gz
│   ├── c8a0c8e336a0e12c1d8cab0f9ccfbd395e97338e.nq.gz
│   ├── c9a49971ad34426c1fef48e4efd27fbf67527adc.nq.gz
│   ├── ca4ea4af86bcf944d68cde145ab5bc0b3d3c254a.nq.gz
│   ├── ceb0deef7a52229e4f0b0a36f694e13514ccfba4.nq.gz
│   ├── cf28904c41078e88f44e2ab61b287c294ea75e24.nq.gz
│   ├── cf494b454091a4dc75d14e1732e0e3167621d8b4.nq.gz
│   ├── d13481558caf30f7afd39b3e3441dc22889c6c9c.nq.gz
│   ├── d23398ac25053dee2387636f5186c617c727660e.nq.gz
│   ├── d30db534f09fe63147fb143390ac1c1003cffc8e.nq.gz
│   ├── d49aa3a50089f6254ba0637651adef3b977b8844.nq.gz
│   ├── d4e70ba77dd54659159ad4f4f502656893ad6803.nq.gz
│   ├── d54ffe8299f2ca326e223829998850fc4fe6f01e.nq.gz
│   ├── d75b926049be64841d1fa7f27147cdd20c2933d8.nq.gz
│   ├── dfab3618ce224cf831fe0862e7b04c3a169e4411.nq.gz
│   ├── e09e8249f45ae63fcb437445c08d69bb1137092e.nq.gz
│   ├── e133f9478c04214421d5f5f0a773fe7232237cba.nq.gz
│   ├── e244c7e5a6ae3273afb286d4368e22329ee721dd.nq.gz
│   ├── e247871d63c58df616d8cc19a04429416a76535d.nq.gz
│   ├── e36b6aebfd70cebfde9dc1509aea528863d11cde.nq.gz
│   ├── e4e9dd64d5039770bbc541bc5055c32c8dd24ef2.nq.gz
│   ├── e52477e4134cb1bf8f3dc065a96bfb4a325b3ee2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d02b57a954219435707d83c5a13897881025c9.nq.gz
│   ├── e7145895ef550d63718fa44ac1c4232d17322e4b.nq.gz
│   ├── e7817bab9270db5e0d924499ae13095a9af8f7fe.nq.gz
│   ├── e9f57e9fc8fd8b26d6409a9a1823dba7389b5bca.nq.gz
│   ├── ea0bcb943b503a3dd792d861a8f2a3b23e4c2227.nq.gz
│   ├── ea3b9ba0e6136d408e6e54fabd00cde3977e54ec.nq.gz
│   ├── eae2841f16145b8d0e2661b5a32e16b8c5161207.nq.gz
│   ├── edc04b01f8515cf3c88fd1ab5412cba19e58b96b.nq.gz
│   ├── edd1740435cdfcb36971001c863568dd2d0e9bb4.nq.gz
│   ├── efc9904d1c38da6e152df5062ade2716889675de.nq.gz
│   ├── f024eba3604d9bb6ce6adb10677997f5fd69a1af.nq.gz
│   ├── f0399b4f4c4c0fcf4390a0e11187b6d40036f2c8.nq.gz
│   ├── f0f718ebbf3889922eb5d2cce37583561c44e644.nq.gz
│   ├── f276f897b284481711a1ab44d69ecf8390e720b6.nq.gz
│   ├── f2bdb3b79fe7d14ba9411c17efc3883cd9c61365.nq.gz
│   ├── f772d9de7c0f693ad8f8ba947b4dc99e748705a9.nq.gz
│   ├── f7a46cc9d9372b74787a4b6ce0d7859cb5fcd607.nq.gz
│   ├── f7eeefac8d2f792a6da99bd6304c0b967a616761.nq.gz
│   ├── faf2ba763c74f4284476a8dbe1d7f2a91cc8e144.nq.gz
│   ├── fb6ab5fe2277426b330bf780959286370a9d11c3.nq.gz
│   ├── fd38128d57dec5a15bb8ff6bf94e7bad98212e1c.nq.gz
│   ├── fe18cdc5f118291032b7c4529d737e1b89483ee5.nq.gz
│   ├── fe82915b98ed1b0835595213bbe666154cb8eb5a.nq.gz
│   └── fec49687412b540a0a94dfd365121d7e8fed6dc4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 23b1747ff9b7e408244c62dd3981238ea193b25a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 175 files
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

[executablebooks/MyST-NB](https://github.com/executablebooks/MyST-NB)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
