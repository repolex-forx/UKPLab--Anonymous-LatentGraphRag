# Repolex Knowledge Graph of UKPLab/Anonymous-LatentGraphRag

RDF knowledge graph data for [UKPLab/Anonymous-LatentGraphRag](https://github.com/UKPLab/Anonymous-LatentGraphRag), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/Anonymous-LatentGraphRag
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6d3fcb4eefc0c11421dd67a4d4a9aa44aa02f5d6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6d3fcb4eefc0c11421dd67a4d4a9aa44aa02f5d6
│           └── chunk-001.nq.gz
└── blob
    ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
    ├── 011199fbf4ce027d8508332aa2c982f709993dab.nq.gz
    ├── 011e02d1893ea6030122507fb4320930353deabc.nq.gz
    ├── 02257abadac854134861df8ffaf1852e425b6fb7.nq.gz
    ├── 0337df9ec6fd5559f7ed3c94ddcb04bfbb599adf.nq.gz
    ├── 046a908e360dc23939b467e5d79f13d12b8e1b23.nq.gz
    ├── 046b86cf5f46c42ec979ac757eb07afdff4bfe73.nq.gz
    ├── 04d503cc57ae0bbe955e21c26e04e462f40d54af.nq.gz
    ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
    ├── 0692def1c755335bca0e4c53031736398287ff40.nq.gz
    ├── 0a3e030c0f4379297b1be20005abba22ed202e30.nq.gz
    ├── 0b2b7e44c3036fe4ae9c7fb3cfea499c5d80ea1d.nq.gz
    ├── 0bc5eb4c08a56f464fc9e0a455544f75557ad8b8.nq.gz
    ├── 0bcca1b23700da8d9f4d9f5e8378c3f9df09f574.nq.gz
    ├── 0e0c383646f04db915b92216ec1e824ca0e1466c.nq.gz
    ├── 0e0e10d71cacecbadca6794755102e971f3f1d0b.nq.gz
    ├── 0e538a5fd5e671c439801f2b973dca6d72d28212.nq.gz
    ├── 107843f70299419e017504d398afc420583b28d7.nq.gz
    ├── 1124490666adecce9fd773c2e93d90f42f4cac96.nq.gz
    ├── 11c9b244eff7480d4713a5081cb05a21dd6dd5c8.nq.gz
    ├── 13511dc268f5ef2aabb44b7bc5fbc5c76ed065ed.nq.gz
    ├── 13df3f5250a3f1f7be19fbc9992679e4a396f371.nq.gz
    ├── 13f6d36d99acbb173d4a807c664ba4f15c850d99.nq.gz
    ├── 152d392811af1d8fee262e6418471b58438b5f55.nq.gz
    ├── 15f48dcb4692c573ed61106a36fcad0a209ba6a9.nq.gz
    ├── 185fd0653287bd9ceca630648e924ad4023e0eee.nq.gz
    ├── 19447e04c2696862d13e8811e69f533bd7129a63.nq.gz
    ├── 1a5e2fa3deee1745d6934b11ab8cd888530e9b7d.nq.gz
    ├── 1adebb48bb94e1faaf12d205739c7a1b16b249e6.nq.gz
    ├── 1b4aa24b0626206f143078571a5746f001c30312.nq.gz
    ├── 1b9c6395469aba2b50ed980d61d002a8c5c2f93d.nq.gz
    ├── 1e38c36c4fd9d84d5344cea176620627e8803f2b.nq.gz
    ├── 1f5d713df9793a18210ada2ac1896a246d31ef9d.nq.gz
    ├── 209856402c35d70e88414c02340cc83684971ab6.nq.gz
    ├── 213444a076dfdf436401e4b907ee47b8561e8671.nq.gz
    ├── 214d40e3e9345a924d72afa33a3050426e90920e.nq.gz
    ├── 22415de5a2f5e7ea3da46c6614f4d81937b41e07.nq.gz
    ├── 228f9432290e14578a9fa48509363bc0306891c2.nq.gz
    ├── 22d2b035bcbaf913eb575ce8734ba2b2efdbc1f7.nq.gz
    ├── 22f92caa78fa7ecafad9d1a7706f909d75bdcea9.nq.gz
    ├── 23cd54c42ac4c36a3f629f64369d79383a0dc9fb.nq.gz
    ├── 2601991fefa1def61349eaae8b26e9f39cc50864.nq.gz
    ├── 27122b0684a114d350e277b02f19e6a290dbc4b9.nq.gz
    ├── 277312d6f10c74574e768f55ebc36e1d7f652d94.nq.gz
    ├── 28bbe50477a69e9c3f04b601df496541881f3e01.nq.gz
    ├── 28f5ad96fd5868cae303b5430a9f4f3678c45c3d.nq.gz
    ├── 299f4ce5e8a3196690aae5d4cc346a9ea063e6e9.nq.gz
    ├── 29dd20f51912fa953d41ebf851e1d5c646492198.nq.gz
    ├── 2a739e2218b6202629f7c153496d0c8718e118fe.nq.gz
    ├── 2c8de49c435aec79ff2fa14235eb0ffac42c8d0a.nq.gz
    ├── 2e425b774420d1f8464df8218ea8ea568839538e.nq.gz
    ├── 303812041f7ce3e371a6aae60dfbf2dd1de5d28b.nq.gz
    ├── 314eb48aec1e91bb3e4204c26d6ac046ba19f837.nq.gz
    ├── 34f1c779a3fd813942e148ccaa6c946e6d2c2c23.nq.gz
    ├── 357ee27926b4b8e029ca5845143dc8556be1b0e8.nq.gz
    ├── 357ee53ecd47813a576d5f145933aa984cff2fb5.nq.gz
    ├── 364ec86376c6d0cb2ee462fee61b486341f20c8d.nq.gz
    ├── 389a52d6869b6f83ddadb75fd167ca6c2b73d956.nq.gz
    ├── 3b1e82c0bd6363d26a1deb01f4cd2f6a6f282a56.nq.gz
    ├── 3b401dffaca810e19232a65bbbacd8028151ef86.nq.gz
    ├── 3b708131f0062d0034bb9aff90aa3b7da72b3e52.nq.gz
    ├── 3be5c34d66cf1027bdc31577283fa3e3c37b6158.nq.gz
    ├── 3ddeb216e2460aa737716ce96f7e27ea741c8570.nq.gz
    ├── 3e7f281105938c0cf928f60e17de2104eaf5b96b.nq.gz
    ├── 3fb936827ae220712cb0fb8181e3b412c30f9be5.nq.gz
    ├── 40a06e648c23b14bb9374c63b3088a5e84440e13.nq.gz
    ├── 4240cfaa1bf7500b660036ed3b10b674341e42e4.nq.gz
    ├── 431bba33220b5f416cedf94b057dc37dda82040c.nq.gz
    ├── 43852bd95fad9f5a97385502ca123cd4e68eae50.nq.gz
    ├── 43dbda523a50cd1e9b61c8c57233b5e939647120.nq.gz
    ├── 44ee75ef663804f0945457ecc9763af18dde633f.nq.gz
    ├── 44f0266b39bdc7c8f39b41f4cce9ab7da6321e90.nq.gz
    ├── 44f35e6eb463fee24b52bc8c56065f46f8cdf98f.nq.gz
    ├── 460779c04582bef24cc55bd45930cdf64bc5eba6.nq.gz
    ├── 47b6969e2a78771b3f0c61faba3e468521afa19c.nq.gz
    ├── 48c5364c44c0561b97a02a8c63cb1d894504328b.nq.gz
    ├── 49a8a4213744dfb121f03a746dc9671c0ddab1fd.nq.gz
    ├── 4aa1daa0ffdb4d39e1db41b71e2e85ae7dfefd98.nq.gz
    ├── 4adde71a9fa50048b246a3090b83c9ffc16b812e.nq.gz
    ├── 4b58ee3da8a5aeadc3e3476957bd1c7e6263aaf3.nq.gz
    ├── 4bbd0479fcc9ae8a13175bbc9eefd6689cbf3b05.nq.gz
    ├── 4c0c640f65c9c2ece7e6bae6e5849952950f2e57.nq.gz
    ├── 4cb85c831cca283ce49d06e325661895239b32c5.nq.gz
    ├── 4e7a7cda726c0b0df4a84a9488c791a199d56077.nq.gz
    ├── 4f6be48ee486ffc70c1731433f603ae7e33b36ba.nq.gz
    ├── 4fa5c16a8ee12f428880808250f3ea9e571aede5.nq.gz
    ├── 4fc15d1f2063f9d57fa838a4b574b5bce2c5c543.nq.gz
    ├── 4fe6d779e0766d0b8d1115d3d22504ae28f051de.nq.gz
    ├── 503b41a61c95ae8b8065ffaa750833a7e6a30320.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 52259c688ca4aefed1225a5163f85650d102a490.nq.gz
    ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
    ├── 58d2f2f50f9f3d8e0becdca69f37b6cff5f8889b.nq.gz
    ├── 5b3ff592fd46c8736892a12864fdf3fed8775202.nq.gz
    ├── 5c1b5f4c1fdf258915a662176827e1dc989dbf0b.nq.gz
    ├── 5e9ef59a09ae576cef8b62c57b78a3663dae851e.nq.gz
    ├── 5f1a36fa48aabee97bf6d079d1233d41bfc5c0ea.nq.gz
    ├── 6165555d56442feeb869293583f5b38a0dad44a6.nq.gz
    ├── 61692761184ad8a58382a0f584ddb7b25f8b931f.nq.gz
    ├── 6176808b36e24373b05d35073a417cc452bdda5b.nq.gz
    ├── 61da72822267df00bf21609e017a9b03d3dc84e9.nq.gz
    ├── 61e36849cf7cfa9f1f71b4a3964a4953e3e243d3.nq.gz
    ├── 61f88bfbc8bf3a0b82118239f98fae1e6282a4a4.nq.gz
    ├── 626173d76611d45f12e558f1326dd57bf23b9c66.nq.gz
    ├── 6334639e47295ac69e638cc2789150ef7ed07b79.nq.gz
    ├── 635e237b0d37f6f507b4b9ce7bfe56dc9b47fde7.nq.gz
    ├── 6773b9dc01be468124bbfa47a658399c8efd16fe.nq.gz
    ├── 68002f4498aaeaa3bf598e7019204bea3c1052df.nq.gz
    ├── 6830d82681cc29ab611c6de3831105d67585d578.nq.gz
    ├── 6949bfa17fb1fd75ae99815e2176d8dcf1833f63.nq.gz
    ├── 6a8a4d7016e49c5a4d980f1d42146c349c851c51.nq.gz
    ├── 6b1079687615139c5b20a84bb52ac5764170feef.nq.gz
    ├── 6b2e085f67e8203f818727bda9367ef9791edd1e.nq.gz
    ├── 6c614090f007313fe90226a16d20743fa63da65c.nq.gz
    ├── 6caacd6a18b8b5f6d5e30b15b845da58ba782f9f.nq.gz
    ├── 718d6fea4835ec2d246af9800eddb7ffb276240c.nq.gz
    ├── 72295984ade7a220e82b7c870c93028336792570.nq.gz
    ├── 751a04d2f91922f3ef1510562505dcbb2a461521.nq.gz
    ├── 759a43aff3165cb6a73774d9478ac1edc102eedb.nq.gz
    ├── 76dc33e923b1a6082a0962b4b3a8f5e0f5e0c532.nq.gz
    ├── 77053960334e2e34dc584dea8019925c3b4ccca9.nq.gz
    ├── 777b7eabab4784614ef7a81912377acf514b11ee.nq.gz
    ├── 7a6267d0161c4f090c13136c001a6c014f67aaaa.nq.gz
    ├── 7ab581f7b347b642702d806e03391499013b6462.nq.gz
    ├── 7ac4f135d5328fe55304db086b5c8a3c2678c2d7.nq.gz
    ├── 7acaf9d4c772dd748106f8400ac14925a0a1ff98.nq.gz
    ├── 7dc65c551579258ba07cf772b496c431fe96f06d.nq.gz
    ├── 7e5084a182da4b84b7dda416c4e4d50c3531162a.nq.gz
    ├── 7efaed3466589cad5d553bd96003e4001cc78f94.nq.gz
    ├── 7fa060620ff9946df763bed3f20899f41831e749.nq.gz
    ├── 7ff39e854308ffa4b41b3c64dbc0edb4850c039d.nq.gz
    ├── 83fc4f059c1447c4a5e5ffabc9a1ebbc9a25ffc9.nq.gz
    ├── 8424a242d9f667278228f744b02e702bc8e51f08.nq.gz
    ├── 843fc987b5c43fdcfb8374c20bcafa34fd55a0c7.nq.gz
    ├── 855b690422392eb5dcba499499d199fd90f82d31.nq.gz
    ├── 8607845a836a729d068690c1c6db69ec3ef1e721.nq.gz
    ├── 86d0d6371f3ef82f5555d917bf5b5aca824729c5.nq.gz
    ├── 873f580e33dec394e6f16a87d07dc0000e50cb17.nq.gz
    ├── 8a1d3df6272a20ed445a030a88121222e5d78ba9.nq.gz
    ├── 8cd2a675cc0b889b4033d2ec6868bfd07b0d2da2.nq.gz
    ├── 8d65efbf2a503198c587a5fdef50fcc03124f38e.nq.gz
    ├── 8e4c0c166ebb2dd66d8e82240d59181bc3fcd263.nq.gz
    ├── 8f01e7630ba2f88ffa1acd90d69f67efb5bd3092.nq.gz
    ├── 90ce4de44beb1ec89c3c52b930e7eaf6fea511df.nq.gz
    ├── 9133516c0b38b05d2334bc16a8ce149e36c19f3e.nq.gz
    ├── 91c003ff0c175c021f34850a3f68e7216dc94593.nq.gz
    ├── 925bffd93b51279caf8f5f8d2f91171e5cbe9d03.nq.gz
    ├── 934f0b6e61cced2b53def898dc3fa9ebb3fca560.nq.gz
    ├── 97e02b21484d7758c9150273f1b97c4e2ffbe787.nq.gz
    ├── 9c6793ed2b521eeb0950357dd6010447a0e05755.nq.gz
    ├── 9cd9d0e2de39bbecb806d3e0b14b8f1e792daa97.nq.gz
    ├── 9d479530f8a847f81fec995b45b00e5d59409b55.nq.gz
    ├── 9da215d0ee00d696341d562847d12be70e4055a4.nq.gz
    ├── 9fa6f0ffda9919fd9b361adb7dc39d8b2d257735.nq.gz
    ├── a051b6987a8622d497ccae08824b0592972b04e7.nq.gz
    ├── a05f63487fea572886d2e0900455a3995c4f81e4.nq.gz
    ├── a1ddbfd76cea01d1441056ff280b67ddd2210ea2.nq.gz
    ├── a2f806e2801e2bc786370caa0e4adebc46781327.nq.gz
    ├── a3397259859ae1f39740d25bf6346c5cf6c65964.nq.gz
    ├── a5759657894f7a182f2dcb9873036a7010f4e63b.nq.gz
    ├── a691b0f7e1cf2bc9d54294aa38a74d509fd93df7.nq.gz
    ├── a7480cb36106e8b436186f01106645d163416773.nq.gz
    ├── a9e05dbe2fb19caec530c1e9afb370d16d582689.nq.gz
    ├── ab422b94a4fbe76275d31c0bf7ef334768b39cae.nq.gz
    ├── ad27b0c8187f5daa19dadb2d797299503af8f469.nq.gz
    ├── ada8733a234d9f19b7fd70b8a7cb485bd883bc5e.nq.gz
    ├── b252bd885542972c672a81f749ca543a904e2745.nq.gz
    ├── b2b2a44f6ebc70c450043c05a002e7a93ba5d651.nq.gz
    ├── b54e52b30918fd5daffdf1e9cea6c63ba4f5fad4.nq.gz
    ├── b8cacdb85d0241d921dd55fb50b7aa1ef0b4d3c2.nq.gz
    ├── ba84ce38a2e04ca19081ed746e00d886f8460eae.nq.gz
    ├── bb4aae1240c01ce960a127e021a4cb280608dcef.nq.gz
    ├── bbc587c3f0d741e6efded3f023b97ae54d72a42e.nq.gz
    ├── bc7bb21833309a2ea7bc3cb9af221290e16d5f92.nq.gz
    ├── bc94475844f7fba78e0c400177312ca5571a3050.nq.gz
    ├── bdc54d565f7b872894992334d789c7a0502f7c9f.nq.gz
    ├── be421169f14208a74119bca15608b988a15f8afe.nq.gz
    ├── c17a1d496ba677a09dd315a0048605a3b67a4ff8.nq.gz
    ├── c25bccbbdf1933f5f84d0f83b376bd5846ea6790.nq.gz
    ├── c30eb5781fd0d0061b53d0cd9b596054018aea3b.nq.gz
    ├── c31e990349927409d9050c426011e751ba6b0133.nq.gz
    ├── c4dde047fd58b9e7117abb8478bca96d614e005a.nq.gz
    ├── c504a7605346f69badac2fd18ca17c019ab0b9b9.nq.gz
    ├── c525162f8e13fb0fc7ac42c43e236b28139a91f4.nq.gz
    ├── c554c21afb9d8770d894dd7ddb8f4cf18e0d34bd.nq.gz
    ├── c5a50c86ecc42fda2468c7f16a37a59cffbaba31.nq.gz
    ├── c734a723e9c315d7446a2c409b8c6b429ca43d29.nq.gz
    ├── c7700cdf138beb733715d1183c3ee7e133e74b34.nq.gz
    ├── c812f68ec0151d05b5ed3dce1c9269f573bebb94.nq.gz
    ├── c9bea19701dbef9c637ff81fca935faaa16dd8c3.nq.gz
    ├── ca5f53288e93c71ebc81cebc64c1a033adedef78.nq.gz
    ├── ca97d04a5774a8f9f687f7832033ac93a23e8537.nq.gz
    ├── ce509b1e77dc45cb1625e08cedcd225907850144.nq.gz
    ├── ce96c87403d32a308316312aeb6bd1b3e9fef5d4.nq.gz
    ├── cf24126b086f12217076c4902c7c6d58e4f52c75.nq.gz
    ├── d1d98f507e04a104f37320d20134e36ce3c89e62.nq.gz
    ├── d38f03b51b3212a9e34685e18737b993c44284c6.nq.gz
    └── d4fd3195b499610f498480c3ff7b26617842dae1.nq.gz

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

[UKPLab/Anonymous-LatentGraphRag](https://github.com/UKPLab/Anonymous-LatentGraphRag)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
