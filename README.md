# Repolex Knowledge Graph of mne-tools/mne-bids

RDF knowledge graph data for [mne-tools/mne-bids](https://github.com/mne-tools/mne-bids), parsed by [repolex](https://repolex.ai).

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
rlex download mne-tools/mne-bids
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 085e309b9f3a2b66e3cd668db9f2a234da9156d0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 085e309b9f3a2b66e3cd668db9f2a234da9156d0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 055731ca3e23be7bae75a3d63e9436dd5838f507.nq.gz
│   ├── 057aeaea10da7a276303d847ac978a7da5f2221d.nq.gz
│   ├── 082efa55e7ca3fcf3c7faaf8835e9c9ce5f39594.nq.gz
│   ├── 0a0368246f6fb3ecda83493b0d1c05251cc2a86f.nq.gz
│   ├── 0ba25e0a533f189e4ec965e0b458d42ed2f657e7.nq.gz
│   ├── 0c3b9b110b3563d289c7d0a1816777774d9376c1.nq.gz
│   ├── 0e532a4c7f827a5f18870b986a60614e7717311b.nq.gz
│   ├── 0ea3d54851e98623a04b9ba99213c3c9a21e2f74.nq.gz
│   ├── 118c0a63d806b6748fa7a01af1988c77aa90b6dd.nq.gz
│   ├── 14b762d4664435153467346c493e5af58cb274dd.nq.gz
│   ├── 167092587ae1ca6e1c708f833052a7a5c4070c45.nq.gz
│   ├── 170330b8f8dccc1a552d8398f8baf8ae1bd26419.nq.gz
│   ├── 17e565cbb88dfebfede96ff97bb1d529b058e0c6.nq.gz
│   ├── 18156b1c1cc337aed3e19cdb6bd1a0f6a914f5d9.nq.gz
│   ├── 18518a352e305a6fdb541f1351d3c47e1e0f306b.nq.gz
│   ├── 18a9a0f74227504e7cd7f89ea283846db1766ed6.nq.gz
│   ├── 18f57cd4768f9c2ac37913721bdb9c8cbcc37538.nq.gz
│   ├── 1939d1bc12fb4102c5c73bb7b934f17fd8c063c0.nq.gz
│   ├── 19d316d0e1438862f612e710d3e6ed32c9d36942.nq.gz
│   ├── 1cbaf18695f85ce46bded27c7392862ac2851b55.nq.gz
│   ├── 22932a8548e6ac57a9ad194ab69e269f6636c3ae.nq.gz
│   ├── 238fc12f7c033bb4e1f0b416b1cd0c31c3191708.nq.gz
│   ├── 243294ae5dec28783afd585889ddbfa751b06ddd.nq.gz
│   ├── 24eb8f93f50b38f2248eee17588d259a95c3a5ef.nq.gz
│   ├── 25ac50cd26d5ca98cbe31c469128844f4a16aea2.nq.gz
│   ├── 26220d2f718ad088d1a2fd635c32e8e1a2f20c5f.nq.gz
│   ├── 264ad65a0d8a6f8f9d640ae2a90d963afaf38e4a.nq.gz
│   ├── 2762494eea629f855f490acd2bbcc357e839514b.nq.gz
│   ├── 2aa25981112e0ee99a4e41eeb78eab1be0eb1fac.nq.gz
│   ├── 2af504129f7b1f071831f343e5b9a62f0f5f1466.nq.gz
│   ├── 2c172289f3cbe25bc8747a64def49ba6186f4f11.nq.gz
│   ├── 2da6aae614cd22d140cc32142613ca8fdffc6cb1.nq.gz
│   ├── 2e6f140242a5b338b834f13ef45332401c373fab.nq.gz
│   ├── 33b4ed5bf00f27441f2a61395f101755d5759c54.nq.gz
│   ├── 3589751808793374f32afd6d3f1001924759dba9.nq.gz
│   ├── 35c3945de0e4e53dda91f0b29d4188cc4ed41c66.nq.gz
│   ├── 37d201ed8ba4c916c505c3e0cc434f753bb25072.nq.gz
│   ├── 391cccb58939b6f2d804b492f963c21efde0f35d.nq.gz
│   ├── 3b5a10ea397a6cb1f873728af04a2e63782d9131.nq.gz
│   ├── 3bfe3b5afd80d33d7ff22d525860c8f022cd70fe.nq.gz
│   ├── 3db48f74f33d0e137a93c5008508748f3b2c6fe7.nq.gz
│   ├── 3dd7bed6688b4163ac8d76c82daad8ffde89b28b.nq.gz
│   ├── 3dddf5bccde136d56ea231aaaa770cf17a5df644.nq.gz
│   ├── 408f379cd31b55b4717ea896e0c8eb5bf1f2496d.nq.gz
│   ├── 44a25108456e176c154f89c164021960cfb546ad.nq.gz
│   ├── 44e25ac43bc989ac531e9bb10383de9c9ffeb407.nq.gz
│   ├── 45cb0b4a855b2bce116199ada22eb2dbdaa8da08.nq.gz
│   ├── 47fdef1cf6978f256ba29ab9b3267403c01fdcde.nq.gz
│   ├── 4dcc8e1587462fdd148b6709fcf1b5221b2ba755.nq.gz
│   ├── 4dd416512ccd554feb6ba2456ba0b9d48e08e407.nq.gz
│   ├── 4eeb9af06a19be93e7612ea9e23ea738d8b23acc.nq.gz
│   ├── 4f0bd2e989fec02cfde5acbd1eec8fc8d39673c2.nq.gz
│   ├── 4fb1b9c67d838dd91142823f03251fdfce300edd.nq.gz
│   ├── 4fff658da866496c17270e1c9ef50a6013664958.nq.gz
│   ├── 50cc2a5588a0e2e370b6a1fb9e142202683b1bbe.nq.gz
│   ├── 50dbe4684999eccafa37ce758e58290c8f26bae4.nq.gz
│   ├── 510bf28cc133ad07e3628af6b1635b9c12aadba7.nq.gz
│   ├── 51dd0afd1ad827bdcb81374bf363fea5863c9284.nq.gz
│   ├── 55576f92410055ef779416cc4e09e43f83f70724.nq.gz
│   ├── 558a9cc342a577fb57344900d8619838bcea37ec.nq.gz
│   ├── 5a51997876e148bc033ad72edc5df2942f699344.nq.gz
│   ├── 5b69b00af07e3348eec1f0452bdab6926067da7f.nq.gz
│   ├── 608e830e33723bae58bfda645b3c0ef1e5e246c8.nq.gz
│   ├── 60b9ba10fdd1c38cebd85beec1d18305b8851eb9.nq.gz
│   ├── 6152c513626f00ddb5a0c992413d07eb6989a1fb.nq.gz
│   ├── 62633ae3444edc5ce0222e0ba13f4572c232ccd8.nq.gz
│   ├── 673671d648e5073a0af9d2ae14572f8ebcc4c439.nq.gz
│   ├── 673b6a57152a51a579dcaaa2a4048cfc67637845.nq.gz
│   ├── 6a683f716342b32e246f3f534c88f61408bfc12d.nq.gz
│   ├── 6acfa03a12301663e3c272c530cee1508b89035a.nq.gz
│   ├── 6d027dbdd05f068b06a37e69531b74453172483c.nq.gz
│   ├── 6e257b749344d0edb1d408870fce88c4e469b935.nq.gz
│   ├── 703a181a4e1bdba4c65445bf53cc0209b0f660b2.nq.gz
│   ├── 7074e00d78749416e5b361c75fa3b86eadac41ff.nq.gz
│   ├── 70c86012a315b6398d2a3141e7ad6d695a4ed06b.nq.gz
│   ├── 71cf7303fc36496713940c66fd97c0b319720e6a.nq.gz
│   ├── 727d57182de9f786ee5989d531902ed19d95ad79.nq.gz
│   ├── 7405fbfade07947fb5eb6cf059e07051bd0afc53.nq.gz
│   ├── 753e4f81e9a49cd7fbf45b9e52c865926b48a9c6.nq.gz
│   ├── 769179529d6d0a735d86a766dab8b38c147df6da.nq.gz
│   ├── 76b615bf24592cc5a8cef29dbdee92ef255a8ce3.nq.gz
│   ├── 77fd1cd00eab7893581c6c3dbe9054ab499ea666.nq.gz
│   ├── 789e673f46c9a7b70b76c87c86967c548cee1bbe.nq.gz
│   ├── 79b9e7bcff1c0bb0bbaf58c208b7f0590c08eda2.nq.gz
│   ├── 7ab2f55e6e3a8c2352ed8cd8ef7a18ef638a8a5f.nq.gz
│   ├── 7b0787fefceb7ee99f10bfcb2871434dc979ae8b.nq.gz
│   ├── 7b356500ea9f3cd1a011cffc8c084e693d0b50e4.nq.gz
│   ├── 7b3dbfc1be2aa6e419f14f0f7c131a0fe1b4ad0d.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 7c67eba788887bc642784659f00293280f8bacc5.nq.gz
│   ├── 7fa52f625f570a90c30fa3bafaa8ea1fd1310cfb.nq.gz
│   ├── 7fafd6d15f4ca375aaf8c7a0b5edda12e6bbffbe.nq.gz
│   ├── 817ffec540aed24e544d21f95275b68e11c44e48.nq.gz
│   ├── 81aa68d23e013efac9780b78dc75beea39e73cae.nq.gz
│   ├── 8456cf64eafd3c1e7eccba264d91b8abfe475444.nq.gz
│   ├── 84a5d39422522cfbee91f28bff2fc71c43f11a00.nq.gz
│   ├── 84e94a29ef9342ec3dcfab86da66dbe16bcced42.nq.gz
│   ├── 87ee7fae45e33703e5664988a93868d0acf6b919.nq.gz
│   ├── 8818870216f00e2fa982dda9140e7c1f8d0f0815.nq.gz
│   ├── 8a4798fdaa4b4997843a6130e65c95b64fec2290.nq.gz
│   ├── 8c7829d87bdbd69a2d1eef6fbace1490901ab616.nq.gz
│   ├── 901eb9f0b0776791b5ae537f9ac0764bf23b7dd9.nq.gz
│   ├── 9204208ff65fd27c1a7986dd86508bd60b927495.nq.gz
│   ├── 926d79c270e29dc47bacc5d1eadbfa5a98bccbb6.nq.gz
│   ├── 929d0f14d9f8c33376079e8af9c9d6cf93715109.nq.gz
│   ├── 934304eec0954b1ea13f18cd3a42e0af95b6d60a.nq.gz
│   ├── 9422d6fef2368212227ad3f864d0316ab7b23614.nq.gz
│   ├── 94f8ba4aedcb34796727116af9a05f2c39299660.nq.gz
│   ├── 95e5edbaa232a48ea077c7018cc844606447540b.nq.gz
│   ├── 9778fd6b434295245fd400d6688b19aed43b5e50.nq.gz
│   ├── 9a37d6dc08a1d0a4a681d51035297d0b3ee5e5de.nq.gz
│   ├── 9b3127f1f138e93c8898f57f114a71c6e2732300.nq.gz
│   ├── 9bd4f7a80982e0d54370c3274293067661e093f7.nq.gz
│   ├── 9f3b271be9c2d66a082d331ce200c15a717b35d9.nq.gz
│   ├── a020c350e8154775c4998ee5d908e87d59700d59.nq.gz
│   ├── a1a5400dd217d95e5e37f1f0ed2e722e29a1b781.nq.gz
│   ├── a1f0aff6609073ecb1a28bda08963752b483826d.nq.gz
│   ├── a3496a5ff72e9634598c3421fe38fad89aa322fc.nq.gz
│   ├── a3d4fe5a8689951783da1364c881b914473e182c.nq.gz
│   ├── a4fb5d7504d0998aa311e26822d7726cbd394d5d.nq.gz
│   ├── a517cc78fc43b81033c07505dfc6e09ca088e645.nq.gz
│   ├── a55bfbd0cbae9423f9420390b3bc721ab1e47b34.nq.gz
│   ├── a94c6fa3c93f45ad1d7d0f52c3b72fcd4b5c0449.nq.gz
│   ├── a9e5eba1455de1c2dcc225a28ee434d5cf70266c.nq.gz
│   ├── aada6dfd987a687f7af6db3fadb01d6fd04d7499.nq.gz
│   ├── ab2b7490f45adda41e2496e576e3c4d366024f4c.nq.gz
│   ├── ac3926142382cf90a2385a3d732810d061dea043.nq.gz
│   ├── ad2c1920f83321c6833a1e54a8629fbd71c8fdb6.nq.gz
│   ├── ade7cfb1c0afd7e67482ab1c8af10963ed7b5612.nq.gz
│   ├── aec37b0f881ffdc2776c1bbde92108b8efc0266d.nq.gz
│   ├── aeed07b38a253b9aabaed8b7f4bfd24172936b10.nq.gz
│   ├── af4bffe4665364f53c5b2e08e1cc619ba6b70374.nq.gz
│   ├── b1836a0da03297eaee0a25bff27ec930010f9772.nq.gz
│   ├── b25f8696a3c2618ac558e017c788b07b51c2df35.nq.gz
│   ├── b2bd237328e81a6f0002938998a5fe4018121a5c.nq.gz
│   ├── b3f9d4245d1fa7750d141da0cc344da70719cb73.nq.gz
│   ├── b44ece06dcb34f71a3a9b3b7aea888aa7a0e30aa.nq.gz
│   ├── b465f32d5e4843d2594998f0fae7931aae7de783.nq.gz
│   ├── b4c984e71e3e167693db10299643c58b3ae2ccb3.nq.gz
│   ├── b76e97fe77ab0cd8b049cf3cc1986dd87edb99e6.nq.gz
│   ├── b902d6fc783ab02eee4b24cfa5d997421e5e61f1.nq.gz
│   ├── b907962edbaa33af6ce04f3b22cc89ec78519d28.nq.gz
│   ├── baa0b1dcf4ffc78a83310039c015f34e64204829.nq.gz
│   ├── bb51cb451fb56ee2781aeb2aa6c8af00ad21c55e.nq.gz
│   ├── bb5e347db4e890064488f49da163dee74ed418fa.nq.gz
│   ├── bcb8571bdd3ebe1c0d2d39f50ee86d38fbb101ee.nq.gz
│   ├── bd4370ef2c4f49da1449b40d789c99bdac2c5a1f.nq.gz
│   ├── bd447905052e75da4788477b3bffa7fdb746e8d9.nq.gz
│   ├── be9ded60327a327486ba463c061261078595e413.nq.gz
│   ├── c037381fb537de353fd033369831931bc4ac215c.nq.gz
│   ├── c3165847f44132ca8d2839ce8a98a7a4da7e3b1c.nq.gz
│   ├── c359dba10578f8688d3de98787f3b3482e804473.nq.gz
│   ├── c387c90379ee207eaeb202b253e16f9548787151.nq.gz
│   ├── c4049968bd01024d540742fab1b2959ba54a9b76.nq.gz
│   ├── c489b3b48d98f1a7e6fb7a4abd1555223b4657ba.nq.gz
│   ├── c89c782f3b9466f8b6a1db9850b9a5aa8a444b8f.nq.gz
│   ├── c91168d8e5a059ff2fbfffdcd6f44cbd458ab6f6.nq.gz
│   ├── caa5c5f7024a65f97d1591f23d2355b40e6288e2.nq.gz
│   ├── cb64e007152c37462979b13602fdc17e7e3c8f25.nq.gz
│   ├── cb76ebe0a52d04e9a4b0b9d16bfedf09bc7f58c5.nq.gz
│   ├── cb8144442f177322a68c5c2844dc749fb3d498b0.nq.gz
│   ├── ccd8ae3d690516f4b618da28062796e9c83a7455.nq.gz
│   ├── cd4563ab8af315d903309b48ecceeaaafe5fbea7.nq.gz
│   ├── ceb4b1f667de9310c1b758e9350d82fbc92eda3e.nq.gz
│   ├── d0be9df22c8329554d7e2dd9a3e7a6ebe7f747fa.nq.gz
│   ├── d53fe201721cab81a7157eebb07b14c9ccc17f9c.nq.gz
│   ├── d71ad03f827b31ce0d2fff49f332d525f1d39fbc.nq.gz
│   ├── d71fa650bfaec13983819266958195b5a686bf60.nq.gz
│   ├── dc357b2db72b1ed74e87f043021aa10a99c87b4c.nq.gz
│   ├── dc42ae0672b255342a73a34018e9f49d65b4703d.nq.gz
│   ├── ddf4b51570c3552eb0a99cf2787884faa412479d.nq.gz
│   ├── de1642226da7f3cd253c39ca5ec8562a52973613.nq.gz
│   ├── de4b301c17eb56634c5320e2577c0a192a498f85.nq.gz
│   ├── deecbf860519a8fe2c164bd1a42bffa21e7acfa1.nq.gz
│   ├── e1e102bbf1d1b137ae1bb80203d713bd50d061cd.nq.gz
│   ├── e74f983de75916fb4186f30c2787ecf5bcac5d0f.nq.gz
│   ├── e93e5fa7b8d754f9d4e1f7148f53385616114a80.nq.gz
│   ├── ea19506eaaf7ec5a8f3e7e7f9f45a7ee957acb06.nq.gz
│   ├── ed09e3804492468d9037618576db9c812e831080.nq.gz
│   ├── ef056b5c0c5da5554cf629790897219bcf43833e.nq.gz
│   ├── f0e52fd1aefab4a40c79e33412c28ee2d3abb1cf.nq.gz
│   ├── f1ee8e21464733a0bb6333d53bac5341944a9985.nq.gz
│   ├── f369bbe06abec8be41e61d011e1c91dc22802a8e.nq.gz
│   ├── f3d4a84fc914a32426b2ea2fc034e829038ca6ab.nq.gz
│   ├── f518bd877282b1ac8fcd1c466b231fa39eabd014.nq.gz
│   ├── f94a070cf980a8a08abab9598836dbe1d7622c1b.nq.gz
│   ├── fb5bdfe16a5b87b872f757b935818665c7ae809b.nq.gz
│   ├── fc263347cceb167498721993f6b4daf77a96acd2.nq.gz
│   ├── fd35d11f53cbeefef1c0f1365e8d279a01dad7d8.nq.gz
│   ├── fdf63c335d38651724e1effc523f2dc1a868b938.nq.gz
│   ├── fec19411b5e170b438ae16ce5758dcfe86700c37.nq.gz
│   └── fecf14577bd2460712f3bf8e607752c811b5a57d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 085e309b9f3a2b66e3cd668db9f2a234da9156d0.nq.gz
├── issue
│   └── issue.nq.gz
└── pr
    └── pr.nq.gz

12 directories, 200 files
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

[mne-tools/mne-bids](https://github.com/mne-tools/mne-bids)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
