# Repolex Knowledge Graph of PyCQA/pylint-pytest

RDF knowledge graph data for [PyCQA/pylint-pytest](https://github.com/PyCQA/pylint-pytest), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/pylint-pytest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b7a67d54340d14f8a04d73942003aa655b968e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b7a67d54340d14f8a04d73942003aa655b968e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0102b898b9d956e5bc0d0efbe715365090e00d4c.nq.gz
│   ├── 032863cc850d2eeee48848a6a26cf1742b0dd0ea.nq.gz
│   ├── 0965d19d4b9e1d92b90ebf5931ad1906ee8bb1d7.nq.gz
│   ├── 0efad862d8d48bcbbbdd44ac68a49af2d3ba65cd.nq.gz
│   ├── 16631bcafacea6a35c6e76d70fcb32db54a34024.nq.gz
│   ├── 1cfda6a047fa55e15db066e033e2329dacfb426f.nq.gz
│   ├── 239a9609f8e6684548bbb501e696d6e28ebb20f6.nq.gz
│   ├── 2854126b7337f32154703d863c365a48b756aa27.nq.gz
│   ├── 2a2ef5b413836f856995a421079013a54c6090d9.nq.gz
│   ├── 2cc9233eb0a534e531fb4b30ba68448e8c34ad8d.nq.gz
│   ├── 2de88b410ae00ff627c70acb44505823a17fe4a5.nq.gz
│   ├── 322dc08fba9da1472bf3d9bd2741f42cac0f20b4.nq.gz
│   ├── 3bc5debb7f94938983d8804b71ed995ef50bb39a.nq.gz
│   ├── 40f441dedc26a338519622593f0277485c1005aa.nq.gz
│   ├── 4293624833a739def405bcbd838406224093d9bb.nq.gz
│   ├── 49add62cc382449727346e884d76db576c395cd1.nq.gz
│   ├── 4c7bad79e7216a1bae9fda5be9a10a897494c5a8.nq.gz
│   ├── 543eb8e98294382906fd244b7ef863cbaceb8539.nq.gz
│   ├── 56694cc03cd3c387b101c53b354939bfa5681296.nq.gz
│   ├── 568e7e861cd278c67ca0f82f8d3e39355e6c89d7.nq.gz
│   ├── 573618309c13ccfe6af2997afa69026bc535017d.nq.gz
│   ├── 57a510bd1eea3d28b29a22609251e2e03e5e8517.nq.gz
│   ├── 58674d24f841ba0d006f753541aeeda176ea118d.nq.gz
│   ├── 59758b8581f539325ed5300b83e80d46fcf32b85.nq.gz
│   ├── 5c51cd5a4755d7761d68b7800c5d0852c9e52a87.nq.gz
│   ├── 6132fbd36fa245f24035d1b3d96334c26b2a75a5.nq.gz
│   ├── 6208d9f64b54927af70d85bbc7d2b03d8b02a2d3.nq.gz
│   ├── 7873b2ff4df7edd625751c50d00c28351e888562.nq.gz
│   ├── 7ab2747a9cea0ac82a6844320c6f24c818461593.nq.gz
│   ├── 7b1a8b39915bb9020e0d7c18bddca16485737c69.nq.gz
│   ├── 7dac65f71e160e998c11172f871a90b348fc4f5f.nq.gz
│   ├── 82187f08dcc381e8ff1c14260a7632d864e7a19b.nq.gz
│   ├── 828c27ad68d554236336afc17b6c9c2760c5dc9b.nq.gz
│   ├── 888e432a4f2f342bba55a0bcf272c5c7cd6e968f.nq.gz
│   ├── 8f5867d87b11ae30eab374b1a767ab963184229d.nq.gz
│   ├── 983d575594ba462b1145af13bd92dc5ef8a671b0.nq.gz
│   ├── 9b2ddc01a53b222c9242b81434c0c2046166bb45.nq.gz
│   ├── a0dbe55b7c611c69708fe3ead6d2d2f4ed4fcdcb.nq.gz
│   ├── a59d06e07eab023d56ce56ccb8eebd856ed9cf82.nq.gz
│   ├── a7cfb5db63522f33913e34caf97078d07e44abed.nq.gz
│   ├── ad62cc16fdc66c8f62c3e836bce4b78615d47a10.nq.gz
│   ├── ae9e8692bee7c6f094e17c464bae13596ce20e84.nq.gz
│   ├── aef5a323d4355ac71de085f32c594b67958cfb77.nq.gz
│   ├── b269f61a809c1afc23d56f30a06cf26f94f8da15.nq.gz
│   ├── b2ad9e60e1e932324220e67531bfe9fb4e72ab90.nq.gz
│   ├── b8344587c551a67678c79ece13c3ca0bdf513791.nq.gz
│   ├── be6dbfbdd64ed5f9b980edcebb01c4544a096ce6.nq.gz
│   ├── c1d7d36bc6aca1b5a820b15a78d32922c4751f13.nq.gz
│   ├── c2a00a0c6a0b23bd1bc06799ee5fdc2075e23851.nq.gz
│   ├── c931359d39f6564ead7705847d80449bc50510e7.nq.gz
│   ├── c96894025c9795a1d06d0b6d06495e72d216156d.nq.gz
│   ├── cf8c178ef48e5fe720f749dbf8fcf3c8fdc52d5c.nq.gz
│   ├── d08855f7b8b69545bff42fba3439ceab80c6853f.nq.gz
│   ├── d0fce9ba79fd6dbc850b5345fb3578a0235dc9e5.nq.gz
│   ├── da18ef0af787965ec59a8f02a1135cc73b008ae5.nq.gz
│   ├── daecf905cd0b04091cbf34f1103f503cb2e73941.nq.gz
│   ├── dcf91508c698ae453c21b86e9a78efbc7b8535b3.nq.gz
│   ├── e4355f17f887e3dadfebe28e24a356d02f69c5a9.nq.gz
│   ├── e46503010923bf21e2ecb2736c5312f551903448.nq.gz
│   ├── e99db73ea916374b95dde09c6b3c5ecfd2dbb9a2.nq.gz
│   └── f9b179a723dd678344b886bb555cc89c04c68b4a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b7a67d54340d14f8a04d73942003aa655b968e2.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 68 files
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

[PyCQA/pylint-pytest](https://github.com/PyCQA/pylint-pytest)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
