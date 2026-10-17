# Repolex Knowledge Graph of turboderp/exllama

RDF knowledge graph data for [turboderp/exllama](https://github.com/turboderp/exllama), parsed by [repolex](https://repolex.ai).

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
rlex download turboderp/exllama
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3b013cd53c7d413cf99ca04c7c28dd5c95117c0d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3b013cd53c7d413cf99ca04c7c28dd5c95117c0d
│           └── chunk-001.nq.gz
├── blob
│   ├── 09cf1ce11536459ac102782aa62d736c92f7de21.nq.gz
│   ├── 0c421c600c9a61973386c6dd5a1522ccfe08ac24.nq.gz
│   ├── 0d55e11eaa15a0142641a5a1335af26115a4c79e.nq.gz
│   ├── 1289f945270a554844a4d6fbed6254f71f1b2187.nq.gz
│   ├── 1301ca08042df046ea962517b5551bec3f78ef02.nq.gz
│   ├── 149fd68936fdcc07e8d7178f5b4ed32ab4254c94.nq.gz
│   ├── 182bafa5ba3f6021f111b723d590b205b6660b55.nq.gz
│   ├── 1a3bc99e2df4ffe4718d8849756e5889a68ef2cc.nq.gz
│   ├── 1bd91250f466b7accfeaed8156502434e2439c34.nq.gz
│   ├── 3179a2704746da6aee5832ec3fa5d3505ab44e7e.nq.gz
│   ├── 369b686424ba506b56bf0bb1169d21652144cbc2.nq.gz
│   ├── 3ab8b5a39491807eb8667dbd22bd63df10042ff6.nq.gz
│   ├── 3b85deb4463e1accf5cdb2ae2d1aecddaafeb653.nq.gz
│   ├── 3d6e0ca7dab8a383a0dc68825cd63fce9b058405.nq.gz
│   ├── 403b1626b569c47ee846a3c2afa8631bb4da11af.nq.gz
│   ├── 47eab0811ee1398e8dc826f19090b5c4f6b377ee.nq.gz
│   ├── 4ed599ee3c77d2a465c11d2e7a36ceab6501421e.nq.gz
│   ├── 4f63b484704d9b9fff3240cf497235b1b0b2fc67.nq.gz
│   ├── 50195e06b509acf17bb4dd75a229084357dd4e41.nq.gz
│   ├── 51961664251947db1599107925682668194a73e8.nq.gz
│   ├── 53bfa61e129c01360b7a75e559795bf30c420a5a.nq.gz
│   ├── 5b29db0f1eac5f5127d7bda3a6fc06b6fc1b6d02.nq.gz
│   ├── 5db19ade17f53f68927e53ca3bdd02db8c719607.nq.gz
│   ├── 5efd3d4ad7de85e2b8577d7d1b9fdafd6fe76b8e.nq.gz
│   ├── 669862676eee7edf4e4a0b5a4d5320e3b1442679.nq.gz
│   ├── 6802bc4b80c0f8df1413d55b16267c0969e352c9.nq.gz
│   ├── 6919db9e62c39209167a3e1a4587d10b9ba06d23.nq.gz
│   ├── 73dcba0b8135320b55eb279193895896e171aa0c.nq.gz
│   ├── 74d077f7addea41ad1695b98612f15abe5d73939.nq.gz
│   ├── 76ee1e43779c9d6e8d244455355f4463712410a6.nq.gz
│   ├── 7903f0eb4ecee9f585b11e9bfae1b7ff42bbea19.nq.gz
│   ├── 7dcc62ff72169e1eb66d3f790cb24de783addbbf.nq.gz
│   ├── 7ee85c255023715c665ab6a1f094eee13c5f2efc.nq.gz
│   ├── 804ff7f69216fc916d4b03174f5d1f624917b5ab.nq.gz
│   ├── 808e67d1470466e732ee6b47dae1503b85acc654.nq.gz
│   ├── 80c62053afcb66c5297df61f6fc9b5b90b824e06.nq.gz
│   ├── 829e9dadca703655221b62aedacd4c666fc2049b.nq.gz
│   ├── 8a693509203dcfa67cedd407eca7acfe8e1230e5.nq.gz
│   ├── 9405e08018f48bc49c5229a1ac9c1efb98dba94c.nq.gz
│   ├── 94a3127beae2d982c550fd78af7b3afd8fa3139a.nq.gz
│   ├── 9811db7f1f0246690f73cd9e1d095420ee4d5b98.nq.gz
│   ├── 991390b4e37ef45e53cfa19fb1aa0c167aec6885.nq.gz
│   ├── 9cc023bd80931d2384af6e8df3167f9fb256bea4.nq.gz
│   ├── 9d25ba56f846d575cc2d08f10c0851d9a4a79d8d.nq.gz
│   ├── 9d553947859672cb66592c8bc58fa668df6521b2.nq.gz
│   ├── a0ffd33f2d9c3117323044e0eba517cef3498617.nq.gz
│   ├── a1b7be70bc33efda86ae6b72e84e632700779a5e.nq.gz
│   ├── aa9b3a78177a4a84d80dc31f4a53610bf1213673.nq.gz
│   ├── ac21e0e2db8f5c761a4d44f4370a7a9a6809ee05.nq.gz
│   ├── b0d79d4a5053d85e4dcf719230d7f63a0addc99a.nq.gz
│   ├── b210a6320e787370df6093057024454df45d8534.nq.gz
│   ├── c34efddcecca4c20759984162a82faeca614ecb7.nq.gz
│   ├── c57f61fbe0e505679e1e1c84827e489c0eee0bb0.nq.gz
│   ├── c6b47899c93ef6250c5bef4cf9c3a91900066e21.nq.gz
│   ├── cb71be2ba899b09747933af336cce5f4f3d76193.nq.gz
│   ├── d1bf2563c300149ddd7362447e66a5d9e16dff61.nq.gz
│   ├── d5e511e0e1105e438df8a85707fb0f1325c9cc66.nq.gz
│   ├── daf00fa3421e3f37a00b2772a857565796776f71.nq.gz
│   ├── de5750b469bab9bba3ecd512dff676e53cd2a121.nq.gz
│   ├── e3a4c3478cc9bd68bcea2ae0e1a63fa7954b2d0f.nq.gz
│   ├── e8135d989b1685377594224a9d5ed6c03eb8aaef.nq.gz
│   ├── e83849add12c83d13c51089c3c84a78f1ad1bfda.nq.gz
│   ├── ec6a60be8eafbc71fc0d491dd0a65c4c6b2d078e.nq.gz
│   ├── ed51048e24886daf6937d1361de6cc6ff6d04fee.nq.gz
│   ├── ef1f307229bdc67699cf4a83c8f7071b394f393e.nq.gz
│   ├── f115db737d64e1c6d0e9740dc61a7ab6976db6f3.nq.gz
│   ├── f289522180a346c8c7df1fb38f3aaabaa3c1a72d.nq.gz
│   ├── f49ba4f9667cb95a7c793dc93891ffc99ac92e8f.nq.gz
│   ├── f4f2709097ab47c825c496ad2d7d6da779ef423a.nq.gz
│   └── f67434ef2de3beefcb3282d7f91329a46664a7ba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3b013cd53c7d413cf99ca04c7c28dd5c95117c0d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[turboderp/exllama](https://github.com/turboderp/exllama)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
