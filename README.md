# Repolex Knowledge Graph of argilla-io/synthetic-data-generator

RDF knowledge graph data for [argilla-io/synthetic-data-generator](https://github.com/argilla-io/synthetic-data-generator), parsed by [repolex](https://repolex.ai).

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
rlex download argilla-io/synthetic-data-generator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 771d5d7885a7d38c6983ed8d68396a4937658583
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 771d5d7885a7d38c6983ed8d68396a4937658583
│           └── chunk-001.nq.gz
├── blob
│   ├── 0114458ca1a6e405d396269c8df5d2b8e0a0c753.nq.gz
│   ├── 043fa99a266646d779e44e5f5a4effd7872e0ce3.nq.gz
│   ├── 05ddf6b0dff6718b255d03f567ac46e3e4edba36.nq.gz
│   ├── 0602900377e7be63a0a6e5e02a6f225966c4680e.nq.gz
│   ├── 0acf8d281110ca5eb3c0aeb0a534329256622a36.nq.gz
│   ├── 0bff180f3ce54a2a088627917fc2ae356fed0601.nq.gz
│   ├── 0c726db15b6d7da081b57c56227576d8354780f4.nq.gz
│   ├── 15f6a51cbff6603c1d8c3d80135eb9c9f469afdb.nq.gz
│   ├── 160e19fd84fda56b7d90edfb06c5178d3fd15f5c.nq.gz
│   ├── 1738b7de0b11b4b6af68c79b749b80704de31f3e.nq.gz
│   ├── 1869414fed2c34e292f8321ee080f2ce5d41b3e8.nq.gz
│   ├── 20b3a1070ef24406c9aca72e49cc2fb14bb278f3.nq.gz
│   ├── 28d06db099d2aac6923affc7eebe5958813b3765.nq.gz
│   ├── 306fcf8abd9a46de57bd0f3d70e39a4444e52514.nq.gz
│   ├── 31fe90b91703bfaa3da38c6bef3a9c46a4431e1c.nq.gz
│   ├── 33897ad0502cea19ecfbd9ddcae3cec473a78b8c.nq.gz
│   ├── 3884c21db18968dc992202de1be59b7ed73ecf95.nq.gz
│   ├── 3d66c36c19a0831524bec96b2d7474dbee426ebd.nq.gz
│   ├── 40cf883ad9f96207c612fd0cf200342f45bebfcf.nq.gz
│   ├── 457addb286f4cf157f6ad9855a5c6baf7c6ac451.nq.gz
│   ├── 4d83eae097e27147284f4738ff3b1def8c90c3c5.nq.gz
│   ├── 4dcfcfeca16e22dd8d62d11094a6fe3eead40a4c.nq.gz
│   ├── 4efb9919b1052d14e53a06832a112d6f521a33bb.nq.gz
│   ├── 50b670b8d4b279be66e1d0125caf5e5885a10c46.nq.gz
│   ├── 534e2e1687504d69a92f751e608983f74342deac.nq.gz
│   ├── 56d92ed0183eeb224729c29c75d8da6c575be599.nq.gz
│   ├── 64f69798c7ddde6aebb4981f388996f5491061e4.nq.gz
│   ├── 662e03acb1b07c340e689ee54fc06ff3362974b0.nq.gz
│   ├── 788b4c6d02e20870ccfd15277693ba7893914ba1.nq.gz
│   ├── 7bf05222762180939af3eb8076264894f7357b7d.nq.gz
│   ├── 830ecbc42e52af277d203a7b70391c750a9b2d1b.nq.gz
│   ├── 86d513b8efcd172826806ffa4b6b2ea9ef038036.nq.gz
│   ├── 8bd0aa778b44255c14b66924e883ef79d313abb9.nq.gz
│   ├── 8c9ea6bbfe136925cecc3d811ccfb03d524df690.nq.gz
│   ├── 8ff89df6d5a5b657ffbfde07919c82c2926911ed.nq.gz
│   ├── a3a1bf8d2db1b3adc221b1f9d679dffe660d9f87.nq.gz
│   ├── a3b7654a08c5cd4720e36f655a4b049366a8805d.nq.gz
│   ├── a4740d4e8bea29e2de1fdda25e1ce5d3c5e0d9a8.nq.gz
│   ├── ad969f7fb96e6c248cd6614c54e27c4bd119defa.nq.gz
│   ├── b2e4958afe1e71d8c68da8172b2beb54c45a98f2.nq.gz
│   ├── b7ffb7c2daf53c81e0af136b1ba72857ee55fdaa.nq.gz
│   ├── b9625204b6a9382965bf1bdecfcc73c4be20a7d3.nq.gz
│   ├── ba21e58da821e5533e1af324794e5afa7b9f19b9.nq.gz
│   ├── ba7550d3a4005543bec3092c4838b9cb77a09197.nq.gz
│   ├── bd32be1ee3abfe4148c138727276bbf3ad9f22d4.nq.gz
│   ├── bdaee631706ec7b0555c8d0e0eff0c8fb297b64b.nq.gz
│   ├── c31381e084b217c1dbaa0b3f8278bdc5217e9815.nq.gz
│   ├── c4545f73266c214f52f9b3a679efa4bdc6c4deb4.nq.gz
│   ├── cf89c8bb4cf72e46a33e90df6d8196af9226788a.nq.gz
│   ├── e334019794ea05e05fa922c88ea0ca81bbe3ada3.nq.gz
│   ├── e4c7097235ac6437497a08983bc0856c88ae7b6c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee4a2a895055b0780f689805c435b3564c60d971.nq.gz
│   ├── f123cf1b804a818feb86a7560315474800b8dbc0.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   ├── f57624fccee44c3e79cf141d898a1e6ff231653a.nq.gz
│   ├── f8328c2672c18350985a181d0e17c8705a6ab698.nq.gz
│   ├── fe3a975c1f682dddd2e365f9ef188bc6becfb100.nq.gz
│   └── fee3f0cc0aea7891b7d2e2572d496d0653c9daa6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 771d5d7885a7d38c6983ed8d68396a4937658583.nq.gz
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

[argilla-io/synthetic-data-generator](https://github.com/argilla-io/synthetic-data-generator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
