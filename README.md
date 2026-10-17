# Repolex Knowledge Graph of huggingface/lerobot

RDF knowledge graph data for [huggingface/lerobot](https://github.com/huggingface/lerobot), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/lerobot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 146d8474932c8b566717eb2738ba459337ab71c4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 146d8474932c8b566717eb2738ba459337ab71c4
│           └── chunk-001.nq.gz
└── blob
    ├── 00845bb378cab6a1bf72972effdc22de4ade3552.nq.gz
    ├── 023759f94293c515ef3cc60966bb22fcbb967d05.nq.gz
    ├── 02a1b5c4987b27453199b45e83ab4e73a3a95c8e.nq.gz
    ├── 03e12ba7af7d6fecda0c44e9e1a02d16803b0934.nq.gz
    ├── 043dbb6600816bac5a58bbe92437999becba4ad3.nq.gz
    ├── 04602009852778a28be44647b6e7ba445dae3a95.nq.gz
    ├── 04d9691cc8e146e76af9637541345c5d3e9779b2.nq.gz
    ├── 04dbdb158a14f2b931bc62547004d84e9a4ac788.nq.gz
    ├── 04ea7185ce4287d3dc56fd2c8d7e0e5604afc898.nq.gz
    ├── 056f9f15b95a20c9f6374e6a21f701479b182a1b.nq.gz
    ├── 082a4fe655a7e3372a45fd09472622e9655bebee.nq.gz
    ├── 08746ec91a6dc58ff622cf4280a85b38a22d586d.nq.gz
    ├── 08756e81960dd2172cd98f99ea28602e1e2df84c.nq.gz
    ├── 099decf4f052cd9481512435a57c17405102adfd.nq.gz
    ├── 09b43fb92f9aade3e1071f9be30f05ff9dffc239.nq.gz
    ├── 0b2c83d0ceb5b376239674f1776d7b2232d40f28.nq.gz
    ├── 0bcaaeb3e9f98dcd08591015de8d71a053f08a48.nq.gz
    ├── 0be32b7174930f3238aa65839c07305decd8b6e9.nq.gz
    ├── 0caff6de7320032d103c6e761eccb9f3964d0e84.nq.gz
    ├── 0cd185e123243c4d39a7f2235ff88ee99fbb3551.nq.gz
    ├── 0dc087288e7adad4852f20f2de25cfce02815832.nq.gz
    ├── 0dd0a95c615466391bebd856230e0fd08125b583.nq.gz
    ├── 0e868d1047a4170c1f7107b0b01f77e6e2463295.nq.gz
    ├── 0f0eaf07fec48d242fa0d67650b1b7f4c1219f47.nq.gz
    ├── 0f42d7573a44a044acf22b15ee1e99fa1143ca42.nq.gz
    ├── 0fda728cfe6591c8184bf942ec70b834c84d0364.nq.gz
    ├── 104a05f965ba0b4e510cc60485bf4b1ec267df91.nq.gz
    ├── 10e2b6389f8e5997024050bcdd55a2ce7ceb1e16.nq.gz
    ├── 11112e7ec35da29d03bc16ee46547a714719d66f.nq.gz
    ├── 113e049ebcac0ce8e42985bddd3bae99ad8f4544.nq.gz
    ├── 128102caf346e57f5a5d8c7c5e0fa2d8c449a4a9.nq.gz
    ├── 13faddbab8614b52d816c7d78e43048a4b1a65b2.nq.gz
    ├── 1403fd20bb7c0b54e5e9137e89f71b4f868d77d3.nq.gz
    ├── 14368f7c72549e47e395325e9048370a300a8059.nq.gz
    ├── 1462697fa7b7ed2fd239f6cfa95c5ccb36c5ab2f.nq.gz
    ├── 148ec7e336277d83ab22b23fd03881a6521a9849.nq.gz
    ├── 1552e55b39a86dac7446603961c1e671e345aed3.nq.gz
    ├── 158717434edec9dabc3061dbf6ca724bee3d23a7.nq.gz
    ├── 159bde6d823d7733ee324188b1321dc3ea0b911e.nq.gz
    ├── 1618a8db29b660ddd05591771becbe32313d8e4c.nq.gz
    ├── 16dd1a0aac0cfaacc2ef2d4c2521f6b52352a687.nq.gz
    ├── 16ee6344a8d7320236cb444332dd9b3c7e507808.nq.gz
    ├── 16fd2c8ab899646a75aa479b3a52dfd55fa84a15.nq.gz
    ├── 1779a828eaac9181c7a01c1d9b4dab3346cb8c7a.nq.gz
    ├── 17b1130940710fc7dcd95509aa7c8411ecf54a25.nq.gz
    ├── 17fc22bbd8c32a953f9bcb6f7c9d2864bfda60da.nq.gz
    ├── 18359ef0575a4f560a65f21e2d6ddf534edc770f.nq.gz
    ├── 1a0af843e97bdaf5facfbfb3c381fd1b9ecf1647.nq.gz
    ├── 1a626533ffd055105419f46c1bf30dd04f5927c7.nq.gz
    ├── 1adfa30dae95c0554a29a8e6784e6facd1d7d2d2.nq.gz
    ├── 1c32a5621bc8c2cea8e3e9ad76cda3b183e73248.nq.gz
    ├── 1c8e3c91216020522171e329bd763e44a85bbd4a.nq.gz
    ├── 1d3ef89f83d0b2a21d737a67238f09ddc25966df.nq.gz
    ├── 1de25951f3475e7d096462a96f0f2e8c165046d5.nq.gz
    ├── 1e212340b09be56bfdc0e543645c3562d38b16f4.nq.gz
    ├── 1e373a358ca7b47c63f8c8a2eb7586b0939fbf37.nq.gz
    ├── 1ede0bfeb258d9d2b2de7895459ab0cb56d26282.nq.gz
    ├── 1eed89a713dc027802a14e57af8126926d20e764.nq.gz
    ├── 1ffad6854c2e5615c19578f6d85c823e66c33e75.nq.gz
    ├── 200e3fe53286b44b9e5c5ec82204b9787551945c.nq.gz
    ├── 20760fb18d9ebc7cf7104937e6a1687c12ed249c.nq.gz
    ├── 22d1624fae95bb98f1a8d587402ce44d1bf1bad7.nq.gz
    ├── 23a7a4a66d68334e972942d472ed0f5faeabbd3a.nq.gz
    ├── 23ccbbc130a664eaa1fc9d8d5c46e5a2b9544c5f.nq.gz
    ├── 2503b102c78036cd07f0fca24ffb20548abfa28f.nq.gz
    ├── 2537af3130216aaab8b6e60a0e7a9c43cf55ed6a.nq.gz
    ├── 2567d2de33b3246c6f47e3e76cf662e308318035.nq.gz
    ├── 277fd04f4e1a2d6e3c822c80545ec54bd3f57759.nq.gz
    ├── 27811a89ba5fbcbd49dadfde86e87100250dbbdf.nq.gz
    ├── 27a85e22034867a2ed92621a508881fdee3008c9.nq.gz
    ├── 287ad5dea1b32b4c6ccf6d171fd6040d3e802a0f.nq.gz
    ├── 287e0cb966fdcd5c65bf702090d2cea41fcda05d.nq.gz
    ├── 28d77dc83056cbc9df60d7b894212cec02ad5a5b.nq.gz
    ├── 2990e439e71fe0bee1d81d9385c565211e6cb766.nq.gz
    ├── 2a5d9dea7ffd6f5e24deb4d202bbd5cbb3e809de.nq.gz
    ├── 2b66a86acde17e2bc368e2510d594d3a64caf258.nq.gz
    ├── 2b8c83b96ac42020485f5b4d4507cac9f0275680.nq.gz
    ├── 2beba15e612375ae0ed7cec488df5581dd73b5fa.nq.gz
    ├── 2bfc83b4f3473db20d9a8274d72a30185772e268.nq.gz
    ├── 2c0a06301ea07a4f230aaeeebd84e8a513b3b24b.nq.gz
    ├── 2c59fd26b4d72fdb5e9ee17a029e09efa2333714.nq.gz
    ├── 2cea7f443240ac8513f43ef3c7efb13a1366026c.nq.gz
    ├── 2ceabe1851ee3248971a84fc19aec2882a8de8c5.nq.gz
    ├── 2db9cab74034abc944d209af83f558c97bf087a0.nq.gz
    ├── 2dc81f5450a9fe7bc2fa2fbea31b6f28646acfee.nq.gz
    ├── 2e71d15bba2fbb25b4ce4ce72dc36520b9b0866b.nq.gz
    ├── 2eaa150146a2854b26b0dd9b4bfc99de460671fd.nq.gz
    ├── 2f928c733fc7cce949aaf4be66b39078ab443bb3.nq.gz
    ├── 300c582ddd074eeb7152d4bf7da55b43794031af.nq.gz
    ├── 3081eed36674b641c2eddeb2cec30ef37d518b92.nq.gz
    ├── 3090b70511a3ab6d938dff86c70ec08f50938f0d.nq.gz
    ├── 3101458539d4bf976a70c29abcf700fe98ae2787.nq.gz
    ├── 31042596b8d2deb10bdef16ad0de182301904a76.nq.gz
    ├── 329d1c48a2d4f8d6445612b09a733dbe684a33fa.nq.gz
    ├── 32ac792ad1da71069e7b3745b99be3db3e1bf122.nq.gz
    ├── 32b344268d0e7d05ab787f1f1a2d0ef388a14e41.nq.gz
    ├── 32bfd0d7299ac62555a8b01a7e352c28b748db79.nq.gz
    ├── 332eecf4a00b882c134bb88659dc52b97335d9e1.nq.gz
    ├── 336abfe05e1632fb8965540f5d3a959fb8999c2c.nq.gz
    ├── 3405402904cf15ca18227b3a3fe006d7936f9d53.nq.gz
    ├── 37509e0a908ef8b69ca33fc8718f8052b63b0d79.nq.gz
    ├── 380d5f5ff0b5ec63ae02892572f89a2ff90fd469.nq.gz
    ├── 382e9b9537fb37b68fbc36dd034dba965bb07ff7.nq.gz
    ├── 394021e70ed2c3b09cf1a54f7d00f4f594633c05.nq.gz
    ├── 398c754a12b5837cdee8fb6bc044338b5c194fc4.nq.gz
    ├── 3aa058d958b65bcf1ca542ea9fe84a146eb94b5a.nq.gz
    ├── 3afd0e7f30eff510986d595b82a8410a0506d3ef.nq.gz
    ├── 3b08340e8838bdfe41621b3aaa246688bbb19944.nq.gz
    ├── 3b2f117e6b335dc65bd9bd279887c406df0b5233.nq.gz
    ├── 3ba0dde95a91b0c3cf67cba9005a842c10907cea.nq.gz
    ├── 3baa80ba74d87321545ceb31bdc01ef12659f5fd.nq.gz
    ├── 3bf94e6cb0b49b8125901c585a5f52bc5663fa28.nq.gz
    ├── 3bfa1bb775d3ac4109f856ad4aead4e8a5e2424b.nq.gz
    ├── 3cd6ebd8764e04a65171e59f4d54290cbca0293a.nq.gz
    ├── 3cfdf680b27da74d75c9d1b4f8c7f69182c28b02.nq.gz
    ├── 3e3eb8089f92b16284e47e67fc78fcaa49d4f8cb.nq.gz
    ├── 3f36fd805a15a2392d5e11690267dfb88a492f6f.nq.gz
    ├── 3f3e5b0ed8a521c73049f01812628c1563e6982c.nq.gz
    ├── 3fcfb3c8d1fd1a4daff6284d8c4a2e782924ed27.nq.gz
    ├── 403581132a1fbae34f4fe331a254f2aaf038ff93.nq.gz
    ├── 40df8d947adc9c83acfd27a0ff7e23fa3c0165ae.nq.gz
    ├── 4110657d57ccbcddcf54f3f8413d36672a3aa78c.nq.gz
    ├── 412fc64ce95ed74ba9758cdd2098b43893bbb45d.nq.gz
    ├── 413ea87b8aa47343500041a62de97e6241a8b6cf.nq.gz
    ├── 41a384d811d67d4e3f25b1458c5e891a4823a586.nq.gz
    ├── 41ca1fe205fdf5f6a932856c21612ab38f96b66a.nq.gz
    ├── 41d1a20029c4eb84332c4588bef5bdfa79399f69.nq.gz
    ├── 4267939b6f42cbcdf538bae74b79ddefebd69f14.nq.gz
    ├── 4436c9fda87f85a823c6670295a6a04e4bcfb72d.nq.gz
    ├── 44695eeaa13ac34036368bc8e9f25a394e8e6151.nq.gz
    ├── 4487636d06f957c753b1ebcc5536e47144066ba2.nq.gz
    ├── 44f15189f7908ef0f4aedab5b8b2b4dfab240a72.nq.gz
    ├── 460e97a880bb7e23e108cf2dfd1c960d9275b305.nq.gz
    ├── 46311db9c3d847b53db0e47143e9065be284c7c9.nq.gz
    ├── 4671ab9aee41602325d1e66d1e4f83d8dfde4ae8.nq.gz
    ├── 468280d1a8809a1b4c7dceac7310c31327b28788.nq.gz
    ├── 46851625663e9e9f3e38086e7091cd1b12146f60.nq.gz
    ├── 46a5bf0753b2953aa0f4e862a7f15b7c913ae765.nq.gz
    ├── 46d5e6aa3fce7d02706420820e56ef0255962561.nq.gz
    ├── 4717691e288c765237676be9f0e8ae78f36dbc19.nq.gz
    ├── 4729b3968c02c9857d7a7ea7f21ed36d2e8a82df.nq.gz
    ├── 476eb8dce871b56577ff92a86fb8c699699f51e1.nq.gz
    ├── 47c1680d014be09c6069280c49cdb53e5deaf709.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 48a033312856daf32d9ec847d02f2e7084dbcecb.nq.gz
    ├── 48ae5bf11e57950dc54c4cb792252766df002fbc.nq.gz
    ├── 48f07cd359eaf1b1f917e99050a664f45180cc90.nq.gz
    ├── 4a37ddeaf3916639e1ba9eac0c65840d777b3cb2.nq.gz
    ├── 4a4719f54e1d6cf427508e77230a6a318af997a0.nq.gz
    ├── 4a4a9a9f5ae193c020c7f75a9626054dcc583ced.nq.gz
    ├── 4a5593a46fadf76fb6ce4fddebf0c1b5328f8427.nq.gz
    ├── 4ab72c6c12d330dd28c3a3531ebdb6d7f7c7ed2e.nq.gz
    ├── 4b2e503d490fbff4915203ca261cb5450b0da9d6.nq.gz
    ├── 4bfb65ee1608a2dc861da2714725ef4c707d7e2c.nq.gz
    ├── 4c41078236ff42993edf21f0efd83dd233e031ae.nq.gz
    ├── 4c54098a5e06ccbb106775ce1eb5b55220e10f78.nq.gz
    ├── 4d12fc4aa5f91a2f3aba00d7554c081bf80c6219.nq.gz
    ├── 4d47c0bbfad45d85490da0eca664bad7acf5ab82.nq.gz
    ├── 4d7ba885fd555d2cd0f2e34d02cec003c1e47b3f.nq.gz
    ├── 4dce0cfc1496b1e3fbd292474972ee16b3ecbbea.nq.gz
    ├── 4e615d36328b17417b15bcb1c07f3b12c0665202.nq.gz
    ├── 4e6f9fb904eb250013885e39cdd2c9fa9b532fc9.nq.gz
    ├── 4ea29193177cf9862a1e6dc121291f2470c2ac06.nq.gz
    ├── 4ec8c0ca061da46a0502d2ec6e46292cc58a33d0.nq.gz
    ├── 4f0b787aac4d0f53a82d16c51ff20973260d2838.nq.gz
    ├── 52f4a8482a5310cc49e72d061efeca57accaa451.nq.gz
    ├── 541551ca33a59927183f3968995b5bad55d5de6b.nq.gz
    ├── 5584b8643114b69b2f3e9f3a314b671f231ac4b8.nq.gz
    ├── 5663e23c4b048ffe9f1d064b9942a8ed36512fc6.nq.gz
    ├── 56fbaa1a2166cc48c241e7b0dee597a97a6958c1.nq.gz
    ├── 57bffaa10b730d4cade0cf642e3b4135016200ac.nq.gz
    ├── 58048f018bbfc9c2484f86dc984ad7af5be17bac.nq.gz
    ├── 581b2b8245904ce9ff36d603db5b677fcbe7b35b.nq.gz
    ├── 581f00c3d0092d0ee2e0482aa3a244ecc2b7ddfe.nq.gz
    ├── 582eac9e652fbf0dbf515fd77b25e7993cb88bfe.nq.gz
    ├── 58c6f5f4b4a727dbaee48d5cb526a1c42d4eb178.nq.gz
    ├── 592ee199556783758e47ba3b6399a829ef4841eb.nq.gz
    ├── 59be0675922a88cfcb86906923c1d85968d2cbde.nq.gz
    ├── 5a98fa4d22cef7400a1744d65658f966a0b92d6e.nq.gz
    ├── 5af6882d36fcc5cd87adb96b3a52d7c63a7fbc53.nq.gz
    ├── 5b531b20330d9ce44c84e0cb72b06dbc9bf44643.nq.gz
    ├── 5c0b0f52435270f3614531ed42cf4d7f30a460da.nq.gz
    ├── 5c41cd2876ec704942c69a75e6764e0a3a526c4e.nq.gz
    ├── 5c94b06570cbe146cfca3277581545f74e813279.nq.gz
    ├── 5cca15923e4d28aafc4f45abd0c49fd9b2a1d448.nq.gz
    ├── 5ce44048f59f0f7367184a830092a8d33b0ee3fd.nq.gz
    ├── 5d4031a2a007327749abe98624ce680db306eae1.nq.gz
    ├── 5d668710257506ba9b3fcd24aa7f388271d8dab4.nq.gz
    ├── 5d8605286e3ea39dd093336ede45da4510983207.nq.gz
    ├── 5dcba75453b85a4468fa56d280748f0d49771cc1.nq.gz
    ├── 5e382f530f050cbcce57588d930247ae0b7d10b7.nq.gz
    ├── 5f106bd53f236d2d3ed200c2c27d98ab159b9392.nq.gz
    ├── 602892bd3eb6eba17a701efcce17fb0016741aa6.nq.gz
    ├── 60d327510aa69d434013669431bbc767abce344c.nq.gz
    ├── 611ebb000f96eaa772ab492088c23295e1979a39.nq.gz
    ├── 61c374d39b416bea0a1676c10795bcf28df3cf88.nq.gz
    ├── 61de0a3cb0990980bb9db97a660f69575c633cb6.nq.gz
    └── 61e26aed33b3a894bad72c6cbeb0aab310a91774.nq.gz

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

[huggingface/lerobot](https://github.com/huggingface/lerobot)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
