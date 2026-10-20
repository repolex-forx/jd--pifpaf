# Repolex Knowledge Graph of jd/pifpaf

RDF knowledge graph data for [jd/pifpaf](https://github.com/jd/pifpaf), parsed by [repolex](https://repolex.ai).

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
rlex download jd/pifpaf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b9c3364b293c50223a84d7505634a8f848580c39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b9c3364b293c50223a84d7505634a8f848580c39
│           └── chunk-001.nq.gz
├── blob
│   ├── 0970172c879833b006d860a118f71ba596a6c1e2.nq.gz
│   ├── 0edd1d2dd7ed3d21732e589a0bd5ecb90d2da86b.nq.gz
│   ├── 18e9033644c22f8713e38aeb5fd02b9db7bf9913.nq.gz
│   ├── 1d2d58341a4e0bfcf06342bea4968541360be1ba.nq.gz
│   ├── 1d855bfa983bd4d41a749417ab769b27a60f1f7c.nq.gz
│   ├── 260ac111aa26f32f7e123e23f8b0957547ceb83f.nq.gz
│   ├── 263a4a5d3e69c85d72434f05fab8c636a91475c3.nq.gz
│   ├── 2a96f0907fa41745a591ed4acc353437e972d086.nq.gz
│   ├── 2e3de58afb27c92ee04323967d5d68bdea39a3ca.nq.gz
│   ├── 2ef4049f58c3773ef0a37f41df250f1a899b0649.nq.gz
│   ├── 3444d21a7cf56c75085e97d3d8b2d165e0b80e35.nq.gz
│   ├── 4177da57270711696501eda1eaae81fc9b061497.nq.gz
│   ├── 435d9eee8a777d0bb445820609aa5ccec570c74e.nq.gz
│   ├── 449d384e23f9dc596c74f8304e376686c50c4b55.nq.gz
│   ├── 486197f518c5d449584c46e6c6cb007ab7e62c16.nq.gz
│   ├── 4ec92c82a270ea4119f612b836c1f98730b59bd0.nq.gz
│   ├── 4f561552e8fbb9020ae1beb4b11b730829ef1f60.nq.gz
│   ├── 50b51ae92dd99b5b259d755468256ebe7c794ad7.nq.gz
│   ├── 54f9564e4f63068a3893917233ac921302d9443f.nq.gz
│   ├── 57c3e5d9427ae3030e3991525b1d6b67157320e5.nq.gz
│   ├── 63a5eb6f57aeb446864865a30700c501ba60efd7.nq.gz
│   ├── 642e54f6ef4ef46c264b2f72284ae21f852e399d.nq.gz
│   ├── 656b8e8e055d70b800ffd76d7bfefaa4bc7e516f.nq.gz
│   ├── 67fff1bce5c74e9c4e0ffc17db7a71b21a769080.nq.gz
│   ├── 6839b60a27b00547c827df8a41bec35f167fbe21.nq.gz
│   ├── 68c771a099958211169377d766a7389422f5573d.nq.gz
│   ├── 73417ca255a77903e4281cca1f330a02bf7c7476.nq.gz
│   ├── 744ffd5f8b6c460dda699bd63e5d7d7c16ad83d9.nq.gz
│   ├── 74ed2fdb8bfbbba11e440802cbe482599b1cd863.nq.gz
│   ├── 771ebea420e7a61ce39af6e84a641cdb09177f4e.nq.gz
│   ├── 77890869fd0f8fe7f50d897e84de93d40fd6038b.nq.gz
│   ├── 79da33048bfa22dce256ab1f7bd2224c31de0f2e.nq.gz
│   ├── 817fe01cfc49718defc4ca9f2d3919076f313651.nq.gz
│   ├── 83d4ab241bccc80a530eed36866260e279936780.nq.gz
│   ├── 8728788aa2ff0d1f385060d643a1b9ee64c50a98.nq.gz
│   ├── 8bfcb21d6a0c49dcb21df1f52b6f26c53992bf3f.nq.gz
│   ├── 982581c26fc4ddb44b04ba506f5c24b992ee190d.nq.gz
│   ├── a51bef1f4b43ceaa2f9610b05f2473fdca7efa44.nq.gz
│   ├── aa3240773f67f93e3ad2ae41d57ccbcb0ade2519.nq.gz
│   ├── ab532c806dca55a45a11b89865457af30460e5c3.nq.gz
│   ├── b534e2c2dbd770bd69ec29ab30623d671285f09b.nq.gz
│   ├── b9f3e37accf6257537b70fde9c1554cbf6a31891.nq.gz
│   ├── bc53c4ea172e63c1be2db6ca0e43a30aa2b9f114.nq.gz
│   ├── bdeae35f0d7a56be3c64ea24745b4a0f0228fea3.nq.gz
│   ├── c1e53eae16e6f0ca44f84761bdcf5781b83d33ce.nq.gz
│   ├── c2408a43410b70e712dcb8b64af5321b9caee17d.nq.gz
│   ├── c78e7dc8df0d3d1c0ecc0c4cb7e8b83e6c812a89.nq.gz
│   ├── c8c8d1f681c3103c68f2d6723db0678604f82f64.nq.gz
│   ├── ccb93b2f4913196c7184c34d87b11a1e8dfb2765.nq.gz
│   ├── d4ea9bd54ff040025388f30e2d470fa9190e9654.nq.gz
│   ├── d961dfab474a3c584db3a37136392eda5b639bb1.nq.gz
│   ├── d973d3cd1a4026d5ecf79999cf61fb2a8d870b70.nq.gz
│   ├── db2dd7be077cb4b172789cc7749d2abc00e3c13b.nq.gz
│   ├── de558da7e81c52ac8b112a40b0a27b1634c7e77d.nq.gz
│   ├── df139f5185496c13cb6efff0389c30e1d995ad98.nq.gz
│   ├── e20280377098ce0dd80359edf2411dad0e493a74.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9cee1f659647e546c1ceca8670b07c7195f3798.nq.gz
│   └── fa26e208482f329c34846d2a56f538097def3116.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b9c3364b293c50223a84d7505634a8f848580c39.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[jd/pifpaf](https://github.com/jd/pifpaf)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
