# Repolex Knowledge Graph of requests/requests-oauthlib

RDF knowledge graph data for [requests/requests-oauthlib](https://github.com/requests/requests-oauthlib), parsed by [repolex](https://repolex.ai).

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
rlex download requests/requests-oauthlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f33dac32bd065b835b34e7f0a48025700aae1e31
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f33dac32bd065b835b34e7f0a48025700aae1e31
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b2fb3161573c30e232b9ccb7a3ea94cef3eeab5.nq.gz
│   ├── 0c055b85c0e612be587979d017ce53fc7e28aeb8.nq.gz
│   ├── 0d602659c646203a012f107e5651087762b93d37.nq.gz
│   ├── 11c80d0fc3415cfe76cd43698a93675b79f037b4.nq.gz
│   ├── 1581bb311c4d8d42169335a171d5b893110a87e9.nq.gz
│   ├── 23269c054dfae0a283699fa899ba7691bc8ad76e.nq.gz
│   ├── 2434b068b82c4ab74ce41f0210d25fb6616f362b.nq.gz
│   ├── 2abcdb9aebc95d8cce8be68a48a98ddd9238510a.nq.gz
│   ├── 2be3f345306a201280f55e4ec11846cad74ebb35.nq.gz
│   ├── 33f0c3a3d199d1a878424e7338b924c7f2b63419.nq.gz
│   ├── 3577332451f01f06d775b1ba403036f440899945.nq.gz
│   ├── 393d5c69912ca4d2e26fcd5bdbe618864a5310a8.nq.gz
│   ├── 4d2fe9d39a6982ceb35128a401a76ffe31c73575.nq.gz
│   ├── 562ceada790e448a6c1c5b388bfd648cefb056b6.nq.gz
│   ├── 60fc17926fbad6198dc9a4b7352b806f2e22890d.nq.gz
│   ├── 6830620ca28fcbbc20bbbd7d2b09991eab6ded8b.nq.gz
│   ├── 69ed6f6647a993f96e360663d1599488ca605595.nq.gz
│   ├── 6c7d40d0f131fc65a0c88ce19b1ac993a70db08c.nq.gz
│   ├── 6df39b9d57da48ee5c3d5d97b0af2638a925ed93.nq.gz
│   ├── 6ff09bc156c20f32aefcca4641c96a40a58a9cee.nq.gz
│   ├── 71dd733181d9bb5d81f8951860bdc64e112e84fa.nq.gz
│   ├── 7625c8084eecd402705e4bb76ea0604dcaa20560.nq.gz
│   ├── 7ae5d084d9389fef38eb63f537542eb118645ac8.nq.gz
│   ├── 7d5a2ad447eda3bbcefe65f417e1f9d82848c27e.nq.gz
│   ├── 7e3e63c57aec3b154086a7f1c69f345ae1e35302.nq.gz
│   ├── 812eac276aa65ae479d774b0869965131f661d31.nq.gz
│   ├── 859f0566a5be32fb1a8d2f013c8205800bb84e23.nq.gz
│   ├── 865d72fb768b4cac4912efd3afc62af2c774dbab.nq.gz
│   ├── 8815ea0b8eec8630d6cf957f91796df695e365bf.nq.gz
│   ├── 9095a470cd1ccb7783bd3129286310920c1e2b62.nq.gz
│   ├── 91374a4c0c37f6be4c167d6a0600f090aa2db6e7.nq.gz
│   ├── 93cc4d7bbd2af7e74e1c8d79a805d3d5540b1a5d.nq.gz
│   ├── 959529505e75ccd33eee102441ebc97c66b1b13a.nq.gz
│   ├── 97c16d759049f3b392cd7d01becc848a92d74019.nq.gz
│   ├── 9ad6d0995b33daf59a63c85e937947e2c6d9958b.nq.gz
│   ├── a516914e2b98dc32836538d842d517a57185f88e.nq.gz
│   ├── aacc68bfbb1b80be304d21a0f4d4a57cbb7db54b.nq.gz
│   ├── acb39835c991cfdc62a9b0dfe535cb299f9d6568.nq.gz
│   ├── adc333ac9fb47769455d2d9367e0f8ba9a6624ab.nq.gz
│   ├── afc3b2d024ff8e61c27313ed4e279096c04a7b3e.nq.gz
│   ├── afcafa6cae43cbd63fd9e5c19fc83153fe44b9bc.nq.gz
│   ├── b00d4f4796b5aded48db43aa035fbeac94afc457.nq.gz
│   ├── b08abf0fa1684d7f97aa6e4101ea4cc588e9bd6c.nq.gz
│   ├── b3c8c7048341f463aface45e2e856d271c5ca253.nq.gz
│   ├── c1e375fbd1c6ce95855324133aa94060a5c0aa25.nq.gz
│   ├── c1e99dd0e91163a8edf43204a3df19513ecc7fa0.nq.gz
│   ├── c732029e57e631097ec5de4c96f95aa9223bce0a.nq.gz
│   ├── c8b99c721e9bb09e3a0127bb90e09f53814d714c.nq.gz
│   ├── ca52a45be47223c0b3a2b47bfad179e849b34205.nq.gz
│   ├── ceb85e426808fc55ec252447f2c755f0c8ff8054.nq.gz
│   ├── d243b0e24b9765bd4643298e06f080018dbdde59.nq.gz
│   ├── d9f6a911266946d219f375a49d5eccc66eb1c50b.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── de09f408cec1f6d08308ea79fcff9e156468325c.nq.gz
│   ├── dea8fd7a9f203dc2be84f809687322eef98a03b0.nq.gz
│   ├── df3421847de4e1e3cd7638ebcf43ae3436099b76.nq.gz
│   ├── e1ac56c1454c0c0c777f9209cdeb634858ec8e9e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed8a958e0a8da154b0db9b1edca6e47e5dae146a.nq.gz
│   ├── edda9d3f774bf9851bc64f7d869dda29fb748a5e.nq.gz
│   ├── ef33f39101bd97ab2926b13289f8ff3886265fb1.nq.gz
│   ├── f1623fd6d768e5c5cdb91485f01a58c184040833.nq.gz
│   ├── f19f52ac900cd33c38500f184076c8422bcba81e.nq.gz
│   ├── f44558a83902a76022c38f2310a7eddb39cee150.nq.gz
│   ├── f8c0bd6e74e7caffb99874b62d363df92cd8f1a5.nq.gz
│   └── ff0f7320fd401c1036984189e8fdc5dece9a336c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f33dac32bd065b835b34e7f0a48025700aae1e31.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[requests/requests-oauthlib](https://github.com/requests/requests-oauthlib)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
