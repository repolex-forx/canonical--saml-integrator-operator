# Repolex Knowledge Graph of canonical/saml-integrator-operator

RDF knowledge graph data for [canonical/saml-integrator-operator](https://github.com/canonical/saml-integrator-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/saml-integrator-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 651358e895478907d47497815f7a98a349365dab
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 651358e895478907d47497815f7a98a349365dab
│           └── chunk-001.nq.gz
├── blob
│   ├── 0706aba9004a74cd470e095528d5e831471a30eb.nq.gz
│   ├── 073ccfceb10f2f5102059fff3aa22166c88f668d.nq.gz
│   ├── 1125a20ebd60779042b564b777e34d280742c1f7.nq.gz
│   ├── 12652bcae178119f67a17a55ca440a7d18ffad57.nq.gz
│   ├── 13b36134fea6b920526ca317a3f8b11172143f54.nq.gz
│   ├── 176ec5dd25221bbb00eb8cfe84eb07ec594777c6.nq.gz
│   ├── 17759d8801c554bc458a8046b2320e7b6c06fe83.nq.gz
│   ├── 1b273041f5184392e1bea3a9d84559f3b4c74cec.nq.gz
│   ├── 1cf761f454f60b7b6b7c8550b498b73515dd6a3a.nq.gz
│   ├── 212b059b78e400b9a440d39a28e419bc451aefaa.nq.gz
│   ├── 213ec01d15a4e63159e610b387073bf3c6028137.nq.gz
│   ├── 22cd8c774329a7fc34bdcd95171ab3120c5caa2b.nq.gz
│   ├── 23ec5a287017098340899a1b9175d829575164cd.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 2717a39bd5f317a277d098aab8d89e9854b9fd72.nq.gz
│   ├── 28b808c88154e25c9bd10ea556f7a373dddeff53.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 2a220ee7476c9461cec28e8ac45da83fd9ce82e7.nq.gz
│   ├── 2db23224d6a293c9995d35f5da3f623cc6c44141.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 34cc905bf423ab06209db66a64e4d7f823b05d93.nq.gz
│   ├── 350d969edb9e532c464817dc76bc145c2e282a05.nq.gz
│   ├── 37d059bfb238b79eac8c195b5dc61633d8fdc54b.nq.gz
│   ├── 4ca38f53ca42a70c3be8fec3efde6bf15be1a134.nq.gz
│   ├── 544993d1c032e6ee9732285739e594d1eab3cadc.nq.gz
│   ├── 58e038a73e18ca7e1bca16a2d31305f3b707e535.nq.gz
│   ├── 5c07e72228c0b51336daa8dce7899ca07c6c51b3.nq.gz
│   ├── 5fc52f6f5199cbb1ca205077e657d4dae551722b.nq.gz
│   ├── 60ca37c0feadd96930eec1213d74c5dc04f1f23a.nq.gz
│   ├── 65f4410270649b54a4c1a652b651d51175f64783.nq.gz
│   ├── 66d81bdcff1097cca169685330ced51786139b85.nq.gz
│   ├── 6a51a854e7059d672c58aa6d98a20a6cb55043ac.nq.gz
│   ├── 6a5b27da0bf06f86f993f30d4e1c906a910952e4.nq.gz
│   ├── 73b8786523b39278249356d7e21ca3b604d4881c.nq.gz
│   ├── 74246a6bcde0bbce9d4f44342e136660408bb041.nq.gz
│   ├── 76a5fbfc4b7425ee577ab2a34d09daa10fd1e585.nq.gz
│   ├── 79d54264aaff7d380e5c1148dd55482b9e125414.nq.gz
│   ├── 8061dec0adbce2dbae786d5d042c8f73aaa79fa2.nq.gz
│   ├── 84c995a715d3ab917b5710273022b245a0224e31.nq.gz
│   ├── 8a61e8be93e8d72c867cd32ca6793c5cbb742e05.nq.gz
│   ├── 8cc661bece751b13e65f97101d406ffe1ad5e95d.nq.gz
│   ├── 8cd8b2614c028d856a3fffa0f2ffa86d7206c255.nq.gz
│   ├── 930d2e600da574f4765393b5ddc4542a678f82e6.nq.gz
│   ├── 9599a5c57d33555d6d58517da6c3adcf83ad4c62.nq.gz
│   ├── 97328c49eaa27f1dfd863a76b9d5157eaada2823.nq.gz
│   ├── 9a9cc62fa4ef70e8336158e24b5375411edcd826.nq.gz
│   ├── 9cd3b99003d1810cffd154af5bedfd631f0226d1.nq.gz
│   ├── 9da7dba3845ed8bbc0747546c41f56cabcb9c9bf.nq.gz
│   ├── 9e81600625cedf74bc592aec28c74bde37d1c062.nq.gz
│   ├── a6da61f6cf0cf6c8773e58938af089b4c59e5046.nq.gz
│   ├── abdfd61183129b7dd006f17ccd5b7156a6cddf80.nq.gz
│   ├── aef1db20970de9f21f422d594b6d759a1a1cfb9b.nq.gz
│   ├── b2d2f84e0f8960fa1618098e198f191c6a1a46ab.nq.gz
│   ├── b51cc0b4a3ddd6fe8b7bfe46dcdac79543819cbc.nq.gz
│   ├── b699873418c35f6ab140f82166208eecd310675e.nq.gz
│   ├── b94315333ab80d2cf7efa17a4cdf411d406aba6d.nq.gz
│   ├── ba6a6a74cbbd2fafbecc69c74eb1ff05cd7cf6f0.nq.gz
│   ├── bb221d559fc37029b6f44234fad6a84f5b4eddc8.nq.gz
│   ├── bbf9af1d88b02ad98188606e19067d2848ea1a3f.nq.gz
│   ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
│   ├── cbf21ae293a19be727eebea1b5c0305f50732818.nq.gz
│   ├── cde693d3a757860350e1484896da866451a21525.nq.gz
│   ├── cf37d8910f43c86e0a56c28f1ee0cc4adaef3749.nq.gz
│   ├── cf7af82eee1210754c4b686fe439ffc85c358860.nq.gz
│   ├── d215dc3890e95d3eefad7c502025179b54876dab.nq.gz
│   ├── da1e2049eb420c5e26c46849af0ee747a58fabcb.nq.gz
│   ├── da21f4360905816b8e7a7c0761867cbb27fdb9aa.nq.gz
│   ├── dddb292a2c1698851f1fe7d4eae27a5c284b55e2.nq.gz
│   ├── de6e0dbfaf18615b8930d706251660b56f9fd902.nq.gz
│   ├── df25a1d06f89f9474301e29e3fdd86cb4766aa42.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e44ecd9e18bea79b9e6718901827a96a3a949fca.nq.gz
│   ├── e4697f1f8d76135f5172104e300338f66577c3f8.nq.gz
│   ├── e47694ddb02e7f0bdbae764d09d168d1d1219bbf.nq.gz
│   ├── f1dd113d89adf0aac009f8e963a89c6e81e46f11.nq.gz
│   ├── f3c96a1f81252d65108421e40b556af3c34e2230.nq.gz
│   ├── f4e30c56a97efe41bb7baa39ac822b3e4b4d694c.nq.gz
│   ├── f8bb3b865bf7d09c542e8af486f430bd41535ae2.nq.gz
│   ├── fb7169b99797e4312242a4e7d6e09bf7b2215da3.nq.gz
│   ├── fe00675303f0c05ea45423a82ee7837834649b88.nq.gz
│   ├── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
│   └── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 651358e895478907d47497815f7a98a349365dab.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[canonical/saml-integrator-operator](https://github.com/canonical/saml-integrator-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
