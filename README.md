# Repolex Knowledge Graph of scverse/scirpy

RDF knowledge graph data for [scverse/scirpy](https://github.com/scverse/scirpy), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scirpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8496483d777ee439d02290ec5ad9210944f3f1f0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8496483d777ee439d02290ec5ad9210944f3f1f0
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a55641585fa2a25ffc42e651137a15daf728b7.nq.gz
│   ├── 03f202983296c3aef86aa2b3b3b06d5c4e0ac74a.nq.gz
│   ├── 0783b3c2a3ac5e3be82f80ba004e1150da6f42a7.nq.gz
│   ├── 08045e922b3d51781fd41dbba55ace59d485e541.nq.gz
│   ├── 0aafe61a87063740461ba62844615bcd37e24889.nq.gz
│   ├── 0afe3df06d4795e775ff828300f4ec3fa0658891.nq.gz
│   ├── 0fe0c344cdec266d9e6ccbc604f7c0bcc9a9d05d.nq.gz
│   ├── 12a50852969da56780283b21c4ae4fd372f90585.nq.gz
│   ├── 12cbe933d63631ddce7a2acb96549777b2d508e9.nq.gz
│   ├── 12f37b39ca22eee25dfbf9e963b276968aaba121.nq.gz
│   ├── 156e4174a9a288b5519bd15c98f53b7227b46948.nq.gz
│   ├── 15e1c95cc0fa5c56125c12c2eeee8f43bf9eb4a8.nq.gz
│   ├── 1acb0e901056e17a1c8f928ea782f4854e71500f.nq.gz
│   ├── 1bf3c3df939b79ec8ea3d25462e111d2392c0c88.nq.gz
│   ├── 1cd8296f29d397e11da2efc9aa4a0c6175894448.nq.gz
│   ├── 1d065f859126f1c05c033303d61da586a591dd26.nq.gz
│   ├── 1effd44093db461b0848f21a1db758f8122d38aa.nq.gz
│   ├── 1f9b5f95eefd3782d9709e80f95adeab10f2a73c.nq.gz
│   ├── 1feac45ff1a09de4d5c8db3faa3b72c95f9293c3.nq.gz
│   ├── 206dde8e9cc15e3fedbbe654d755afe4b2bf919e.nq.gz
│   ├── 2754592f4d7d61d4aa8190d84767636ba61a0f04.nq.gz
│   ├── 292e5570be8ac7460c4600ed8e6296be1c7c53b9.nq.gz
│   ├── 29928d5352c916939e184595ea3349006338abef.nq.gz
│   ├── 2b57d197da44fc9206980aa9e973ec6742ece196.nq.gz
│   ├── 2bdc61e1af0c055f1c4dc1a86dde85f04f456fd5.nq.gz
│   ├── 32e7c35d7ec89aba4b2255d0d829ffc7948ed8ea.nq.gz
│   ├── 32f478254c80ecc6715175ec842ec650d8636d62.nq.gz
│   ├── 384266aef21de0846a5ccc87d84c930f698a00b9.nq.gz
│   ├── 38bd40f523f888df8e2c8964b561f143e888f45a.nq.gz
│   ├── 38c7a84a3f77e425adf8a4044a66f48b6c83cbb3.nq.gz
│   ├── 3941737f8527d204b412a498572317d0c8f0ca1a.nq.gz
│   ├── 3b07c269fb778c7390e21fcb640685c03a8fc4a4.nq.gz
│   ├── 3b800bf263f9d32315016181e3798dbef7c232e8.nq.gz
│   ├── 3c8f605da6c691f7e97162a8429f67c022d8de49.nq.gz
│   ├── 3d349445668346042b2fd6452890ac463d677cb7.nq.gz
│   ├── 3e44eb859aa4565eecc57367be92c2fc0bacf71e.nq.gz
│   ├── 433609251879b18ea1b3df70c44a85b4a11c8bed.nq.gz
│   ├── 439f4b8181ca5789878e5b1d6152307924a5f5ad.nq.gz
│   ├── 43d5888662a032ed976fc061d1e416e29b89e7a8.nq.gz
│   ├── 46ce969ce1833ed8834472b605c5578d96d6895a.nq.gz
│   ├── 483d4c51f9917d2167f470792e3a8961a9a4dff6.nq.gz
│   ├── 487b2a507ad69b1c3375904695da99a01d8c973e.nq.gz
│   ├── 48c2b18c4ca8d7b64ee2b1967fec6c6b800e860a.nq.gz
│   ├── 517aded61069d2cebe12b2180739ab80ce51e245.nq.gz
│   ├── 51ab54a0bc919374263cbe8773445b8d4ea0eb78.nq.gz
│   ├── 531fe02328734ec1d4e4633949014d66db21afc4.nq.gz
│   ├── 54997289e2f41bde1c90377d7b58110d0882a761.nq.gz
│   ├── 54f4a4f9eb1c73f0614312dd4de83e5755d0eb80.nq.gz
│   ├── 56b19cd122f5d7627811d8324dd3374b481ce681.nq.gz
│   ├── 59ac38e9d2a30ce9f2bfb96f350cc005eb3476f4.nq.gz
│   ├── 5ae2c66b458a8d10beaf2d5e65a0603153ceb96b.nq.gz
│   ├── 5d5c75a46abd48e06058875a63ddb09ededfb788.nq.gz
│   ├── 5dfdcdeea895406f07eab2859039abc0e57b6bd9.nq.gz
│   ├── 5e492e72614966b12f5f92464be63abe6460fe9e.nq.gz
│   ├── 5e730e8986d4962fab8e8ddb7155398e3e11bd5f.nq.gz
│   ├── 5e91b80b0b2650621dcc92d8cbe2cf7b16f9c350.nq.gz
│   ├── 5fc4166dae7c289e51e91adb49eba1aa8a76a3b5.nq.gz
│   ├── 5fcd7825574746c58c469d88697685142d56985f.nq.gz
│   ├── 60dbf6d378a3e99da65304921223b375a01d594c.nq.gz
│   ├── 60f8fd96da504cab383db8e5ee56f43172629fd1.nq.gz
│   ├── 6104b9e6f4ae97e25a2fd85f24bc2370b23bab6a.nq.gz
│   ├── 61a07b7cb30dd368a482e7b553b2951a8f045ceb.nq.gz
│   ├── 66088a8a20259a3ce7d01bfb8e41062b09ce805a.nq.gz
│   ├── 66eb0b61bcac68a649bb1761b2d113a6c3e23043.nq.gz
│   ├── 678d0b6660391db632927d7f3acd496197c8166b.nq.gz
│   ├── 67a84eccfc16e5dd16e2248638389d84f027c617.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 6a181420ff63c05f44a0f2554246a35b6deda968.nq.gz
│   ├── 6af0701a11fbd0f49c25283c4df7153f22b52cb6.nq.gz
│   ├── 6ceadf87d69c69669c0d097b95d0e5d97f3084a9.nq.gz
│   ├── 6d5b84f458da94d4f1add6402866c41cbc930d1c.nq.gz
│   ├── 6d624cd4d1c2a198fe6e57ca11db9cc8b7726082.nq.gz
│   ├── 6e8551550b39fc4bf922af355953018929bd0914.nq.gz
│   ├── 6e8fa77b89eb81ab21c396c3cee8cf0fe7c360a7.nq.gz
│   ├── 6f267ad891ec0eea6e71d6fba0deb59f1e41bb8b.nq.gz
│   ├── 71c9260628076cc40ff1388be85f1cc30900f0e4.nq.gz
│   ├── 7253f9c7e2bd802e1bf9c5698b1d22311b47916f.nq.gz
│   ├── 72d8af1c3168b287a45f69a111b5f522a0a9f60d.nq.gz
│   ├── 72e84d5d8fbd0b3bf08b1aedbc9170f1a6a1cdf5.nq.gz
│   ├── 73547d21bb4263af220addd95bbc526aadda2640.nq.gz
│   ├── 73ed6f5ad37e3d75f74fe4fdd6c6d3f30870d6ca.nq.gz
│   ├── 7405b10c2f2958c2be32af81a90865d81426d101.nq.gz
│   ├── 7407b097f3f20487de36619322507b7d98ff66e1.nq.gz
│   ├── 756e2cba784105c5a0851390e944ca6631c4d5d9.nq.gz
│   ├── 75c88cc10ca3f06cb6d6014ccd5eefd805efaac6.nq.gz
│   ├── 763e941f1a88f5c458f6a09160217226fa61f2f1.nq.gz
│   ├── 7b3fe1fcd6709242ba519180f8031ab53d6087e0.nq.gz
│   ├── 7cc64280b9d90c9382d552f992ccc755c53a76d9.nq.gz
│   ├── 7dfae719c5dbbfd3afe89fb5fa3a1c9a258f55a9.nq.gz
│   ├── 7f58ba23166441763cab6c8c48d563c8aebe12da.nq.gz
│   ├── 7fa0c3e7745ec8d2a779494d39a60291cf5c4bca.nq.gz
│   ├── 7fc123af43e003134b261ee8f506933319086336.nq.gz
│   ├── 80404ad35f518f84e272a94a17ba32ca236ea59c.nq.gz
│   ├── 8104795d126a67e500d3044c24b10046bd2e9d6c.nq.gz
│   ├── 824f07eda0b43568f6122ea846fc06e82fa9b548.nq.gz
│   ├── 82854e8ad2e96bf4dd1070fe3c999ad96ae9f091.nq.gz
│   ├── 82938d4b231b87b886410b054b084bdeb5e8fee4.nq.gz
│   ├── 82b813c5f3d5798c2ffeed95f3b73197e8360507.nq.gz
│   ├── 82ef0e3883e639b061db4e4178c13b3c6586530d.nq.gz
│   ├── 82fcf4224f7f7d7f07cc99dafcb1cdf9ce8ec021.nq.gz
│   ├── 8366d03970dacd10ef10c414885a362a4913be32.nq.gz
│   ├── 84a21a2e1bda18c03201183ad756f57482b939a6.nq.gz
│   ├── 852a090582681b3746a85105f0079619d9666fc2.nq.gz
│   ├── 85d83cbec88419b326bfa8003e606c4c9a1a4598.nq.gz
│   ├── 884b60fbdab8f1e4b3e2bdc9e62cb3c102119a3d.nq.gz
│   ├── 890dca5cd4e7ec6bf99fbc5f3211b1c762ccd0f7.nq.gz
│   ├── 8aa7ef92d121a71bb204c840bc5e7d61062912a6.nq.gz
│   ├── 8b28335c521471b71b285542775ac1c201b1b12d.nq.gz
│   ├── 8b7290223d003c5c921f40f19e91248e56efdde6.nq.gz
│   ├── 8c175d4d0babe4a51fe13e2e3e64dca1006c9e56.nq.gz
│   ├── 8e8ed317240cc9ebc2c7b8a7f6108dafc392c453.nq.gz
│   ├── 8f08e08ea97e867c27d28ea226bb18291f1260c1.nq.gz
│   ├── 914ad69d5046bebb8743ad4f7a9f003284d56925.nq.gz
│   ├── 91f3b47677d21a4825b2b50b7e6926d59c39ef04.nq.gz
│   ├── 92f22331853fac029b987f8a040bd28729fd26f6.nq.gz
│   ├── 92fe74edb60c2fb20d673b680db5026416f8124f.nq.gz
│   ├── 9524424757e4b79a840d9ce8a0b86061cc5644d6.nq.gz
│   ├── 9577d5ccaa32d4c6fc95dc0f8385f108606cae6b.nq.gz
│   ├── 96580981f283b006d3fbb4589cac22e7a0168117.nq.gz
│   ├── 97b06fea2f2f0d29c2a762969fe0701c7c6fcbbd.nq.gz
│   ├── 997c507330e1c522a543ccd7feeb3dfeb0517b41.nq.gz
│   ├── 9b9db5b2415a6af74c8fcf9a45e699cee6d03409.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── 9fe8951c251426e0297971b85a0e38ed28f19fa3.nq.gz
│   ├── a1d50655bfde82f937b3a1e4d097de205f5b84ff.nq.gz
│   ├── a1f0329792e41aeb9da63c0ed9b6c2cd0bf1bed4.nq.gz
│   ├── a22845e4385d75628a8b772cfe1d3388da046500.nq.gz
│   ├── a382489457e102cbddfc3cf65da81d47ae0fb287.nq.gz
│   ├── a5924af1a7d90632c8117aaf54a87ee92ad5e1bb.nq.gz
│   ├── a59be4b9d95c42c03b8e423f557a70f36634bbc1.nq.gz
│   ├── a633dbf8c288a91babaf362c71a1b56d3dc3b886.nq.gz
│   ├── a6cbf767ab4d8545d24926bb3dd27f41ebddb758.nq.gz
│   ├── a776acf9e651487242eba4e748ebb144ca75e13d.nq.gz
│   ├── abeded67fb4b7bab5cbe26c87139187ba9dac7b4.nq.gz
│   ├── ad754482e9d1c468cd64e86d8eab82ae5073c58e.nq.gz
│   ├── aea45d3a8057931cb4deb79933bf5e2298a6c35c.nq.gz
│   ├── afb5b5952100e9d89509e5c92f9813be0bd9563a.nq.gz
│   ├── b13fc25304f286d2694abbc095e094007b0366f0.nq.gz
│   ├── b1cea2b7d70d0fc66be9890d628c3726b255e81d.nq.gz
│   ├── b21b7e8222bd10494ed84ae164edb9bf8cb964eb.nq.gz
│   ├── b23b6f4b6071ead71dc08e439fbec68d454da3b5.nq.gz
│   ├── b2dfa5d5535714823b91636a7644a0889edc201a.nq.gz
│   ├── b4595142ffaa6984fe9d48079834f41eb56faf09.nq.gz
│   ├── b472e8c4305fb52ba21f380002a7ca8e697811c1.nq.gz
│   ├── b4b8af117f25bb08718fa6865e11a07878c3b587.nq.gz
│   ├── b4e7b9453aa857123ce0afa3add18af80b2a67f2.nq.gz
│   ├── b567644d7181186f1f123c2542911b51760e42c2.nq.gz
│   ├── b7add4f53d363be11ddeaca84ea083c3fdd224a0.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── befbe4c01bbe8de0e170962fa7dbb74fe7a415c2.nq.gz
│   ├── bf8621089bc4a9c024ac8a41402ce66bddf12e50.nq.gz
│   ├── c0d81b216178f75156e6fa5b81216bb9422b3f00.nq.gz
│   ├── c41e7000b1f0c7a2383fd8b498399eae416ac920.nq.gz
│   ├── c8f9e9f735311957dc57a30f4aa80faddc4b65bc.nq.gz
│   ├── d08f6a76bd9f4b7e5021bcd6626704a130f7d919.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d1a2575532ea53fa694509b4896bc83880ac4ac0.nq.gz
│   ├── d65c9599f99ef2cef2bc6af13640e410e882b88f.nq.gz
│   ├── d82a9ffd70d052dc08423df1511a4af9ccbae1e5.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── db7bf2d15739d68aacbe86eaa02ed27516b50426.nq.gz
│   ├── dbacdc7f263d1d5bcaf2ea6e4c6373e6742fbee8.nq.gz
│   ├── dbd7882e8dbbc081eee056ec3b5af4a2b2a65a09.nq.gz
│   ├── dc027f3f27673e44584f6342744531e2613ae91c.nq.gz
│   ├── de5c962b4ced8dbbc9751360dc6267c50079862a.nq.gz
│   ├── df4bab5b442a354bfa94f17c6c351a9f027192e7.nq.gz
│   ├── e245a13ab78ab2814cd0e65932789cf9cdd5bb53.nq.gz
│   ├── e43e4fe4f6a1c66980b6a7b73ea19f3159961329.nq.gz
│   ├── e5c735cf3a4844a4d034605e94fd2417d43b83f3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7135fa4df3d14a0772542bedafa95ce67748192.nq.gz
│   ├── e7c4906725926fc036e2a3e847b5863d798389b0.nq.gz
│   ├── eaaa09d15ef3f1d3bb43804f73859fe014065bc1.nq.gz
│   ├── f051a08eef035256f01401cfe41b1f6ab4b4b825.nq.gz
│   ├── f20f6f7f6ce816131d73d194b8967a3bb3912ddf.nq.gz
│   ├── f5072dc8cb36420d2ada640686c0e65c7c8f97a1.nq.gz
│   ├── f50fa3800e8c6df9c5991cbf7fd164adbb09d3b3.nq.gz
│   ├── f58b75cfcaebee3ac0e750c41c1dc2b7d01b6568.nq.gz
│   ├── f5a9e4f7e7262e8e8ff3c16d58846bd791f9f06b.nq.gz
│   ├── f9157ce092e06fd936e398b2c3e1f496f9b7951f.nq.gz
│   ├── f943fe5e68fe8c11f5e1e4c54705c71e84122426.nq.gz
│   ├── f94513e11692859b34d640df132ec4a48acf1358.nq.gz
│   ├── fa41fa05dd198315bb44d74df718712778094da6.nq.gz
│   ├── fa86e2faedce6d77ca2e6add2818ba2c11d6de0d.nq.gz
│   └── fb3f7451fa12bc1d1367faabb6566f37554296a7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8496483d777ee439d02290ec5ad9210944f3f1f0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 193 files
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

[scverse/scirpy](https://github.com/scverse/scirpy)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
