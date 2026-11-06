# Repolex Knowledge Graph of mpkocher/pydantic-cli

RDF knowledge graph data for [mpkocher/pydantic-cli](https://github.com/mpkocher/pydantic-cli), parsed by [repolex](https://repolex.ai).

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
rlex download mpkocher/pydantic-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c319c2cdbc602a4cb98f3f92c9c898c713cc166d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c319c2cdbc602a4cb98f3f92c9c898c713cc166d
│           └── chunk-001.nq.gz
├── blob
│   ├── 1652043ca60cc7f47582b5e371d1e9d19d88f318.nq.gz
│   ├── 1833a6a551af9b6ffbe4419e8f6de5f2cc6400b3.nq.gz
│   ├── 1a84e0bb335ca555f13a2aae7f9521a3df9f7a13.nq.gz
│   ├── 1c7d27eb69f45d82724b7801d950c4d888660961.nq.gz
│   ├── 261103bd30a267a6b3edf59118fe44cda8b2ea37.nq.gz
│   ├── 27e38fa2cbfce6e797e484dad3aa4596a2c8fb84.nq.gz
│   ├── 2993e0d8efaf0efeabd6d752d97bba16b6fd1e8b.nq.gz
│   ├── 2dfa1181e0dd23b73645920af7514b82d7e6bb9d.nq.gz
│   ├── 308ccac2b98691ccee24eab24ece57698bf8dfb0.nq.gz
│   ├── 397f26fcccb553303abebbdcecd274d8ef080ab4.nq.gz
│   ├── 3f0e5f84863f006940d49e579964f47c61a3dfb6.nq.gz
│   ├── 4b973d1ea379ac0a0aee0f3a7543f9dbea60c8e6.nq.gz
│   ├── 4fd99257c8fd906e6cdabb6471f3e24d7478eb96.nq.gz
│   ├── 509141de65ad13512da45e896e11d10e4bc2546f.nq.gz
│   ├── 580b7ef640c792c62e5be545689b5048ec5f847d.nq.gz
│   ├── 60bc89abe2e11801097914df4f61ce43404e4905.nq.gz
│   ├── 62a1f25231b445870fdeed0ea4fb1a1c4ee430ae.nq.gz
│   ├── 63fca2179e7d03aebf5251e053ccaa44920f70ee.nq.gz
│   ├── 70cf60db41a896f919742bec32295140830284c5.nq.gz
│   ├── 775c172dea312e9d8ec4562cfdf542fc815b93e6.nq.gz
│   ├── 780fc877a2732659f8d3390e1b11b0fbc013b9c1.nq.gz
│   ├── 811f2666943d0cb5360fc98c3e243cbbbc1076ff.nq.gz
│   ├── 83d84bf5d1cd0a90919ed8798465e48b03b9eb5b.nq.gz
│   ├── 8f5ca5a122b9a49cd2e09bc211bc37501f49797a.nq.gz
│   ├── 906b3ba0ab3fe5b00e737f81636b93c2a4ff7917.nq.gz
│   ├── 9158871f97a117795e0c447fb008e6852bf0bbd3.nq.gz
│   ├── 9ac0cd54bd30337ac685d33068b7283f2559dc20.nq.gz
│   ├── 9af45ab2d9c48c58f9a69370690dd80256ac9ea5.nq.gz
│   ├── a347026dc8d652f7fb1ec89ab6d27c9c8c6d5ca3.nq.gz
│   ├── ac3bae70156bc1cf10a234580a893a1e4697beb1.nq.gz
│   ├── adeb8e219ee5084af142b0dc81d895c1cb86b4dd.nq.gz
│   ├── b06950c745fbed52648f606492645319c293f775.nq.gz
│   ├── b1e42b513ab06db7dea1c23a9d55837daad94f88.nq.gz
│   ├── b348a0de1593dd63a554e68ff23e55e36a040f1a.nq.gz
│   ├── b919816c83d1ac4944adfe693a3586957d794d1c.nq.gz
│   ├── c167e99f7fae8db7c0a26f534ff98c59f497b38a.nq.gz
│   ├── c68180dc8f55dc84efba6fbb3351fa03b12a25a2.nq.gz
│   ├── c97327236c6dce2e6642600eb4ad178af795adad.nq.gz
│   ├── ca907346eb4158f594f77f1c0a4c6850c62d17c4.nq.gz
│   ├── cb3ddc86ae1abda9774309b0e380ed1e9265fb19.nq.gz
│   ├── d9580be8409952da9d144fd920e7a239be879676.nq.gz
│   ├── dee21ba7fd3e8ac586dff96cba4dbb0260f953f1.nq.gz
│   ├── df29681c6088bacf4d0deec8e0eb40040bb6f1dc.nq.gz
│   ├── e30967bfb24a50f96da372afc5f2659004972a02.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5454aea8f86d509e4a2aa0d71f2643e551ac12.nq.gz
│   ├── ec674f4f0a64e2c4a2fd226def9d7bb7fcd5ce28.nq.gz
│   ├── f95635cdec94fa2b655cec608aca75a84bf8e390.nq.gz
│   └── fe638ae91f5d6882733efa5f2e14618c3a6cb9a2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c319c2cdbc602a4cb98f3f92c9c898c713cc166d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[mpkocher/pydantic-cli](https://github.com/mpkocher/pydantic-cli)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
