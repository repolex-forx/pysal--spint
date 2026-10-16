# Repolex Knowledge Graph of pysal/spint

RDF knowledge graph data for [pysal/spint](https://github.com/pysal/spint), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/spint
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5f88ceda2c63b90f9b50118e4a4750380922c9c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5f88ceda2c63b90f9b50118e4a4750380922c9c
│           └── chunk-001.nq.gz
├── blob
│   ├── 03d8ead20011a62ca611208a830a08d3120b9173.nq.gz
│   ├── 059189472d7ffc1b1400e869d7741308d104a16f.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0c677709e546ecfaa5c9f61e9d3afc85a7a8d440.nq.gz
│   ├── 0eb927eabfde87cae49e99da582e2d4091ca449f.nq.gz
│   ├── 0edb77fb0f2a9352fd255e324ebdc04494a0dbd2.nq.gz
│   ├── 0f37088cbf167520ce4623102d7a9fb5cb84bc2d.nq.gz
│   ├── 0f85dab3f69380171521b62f58d7ea4043ca863d.nq.gz
│   ├── 10d87835a8d3a339f8ec34fd649f2600e03413ad.nq.gz
│   ├── 16aaf7de76c61ee1ecc80202f315adc39897eb70.nq.gz
│   ├── 24f267dcb9bf4fd8f0d94446a7d5b318455d960f.nq.gz
│   ├── 2ba7b2c3300ec21207ca5105d598d6fc3f706789.nq.gz
│   ├── 2ce205bf4cad6535d100149eabde69f4df6e93ac.nq.gz
│   ├── 2f27598da1da2716331135f1aeb7083777cdfeff.nq.gz
│   ├── 32da8171d2134f7eaf468895c11f83916178a87a.nq.gz
│   ├── 338bc235bd47cb7ae4f81c1cad35b09ee8b31569.nq.gz
│   ├── 3533a4241f549ab81da79f52a4edd2c9366d3c26.nq.gz
│   ├── 3ba11e3a8df9e320821e09e41f87ae6d95123b7a.nq.gz
│   ├── 3ba83909ada41c53622b169195ccb0ac258b6f90.nq.gz
│   ├── 3e9ded20cce810c1ff78c4b834d897f66d1f6911.nq.gz
│   ├── 3ff18c02092ae34aa22c6d2c0f6d412a97650463.nq.gz
│   ├── 48a1ed2455b1ef5c8178176167b73aad32918b23.nq.gz
│   ├── 4ac1c230aacb16bc69b119091ac6e2a05aa24be6.nq.gz
│   ├── 4b8c7b7f74ebb97e05dcc99154431a1e95840a48.nq.gz
│   ├── 4c7da6f2f41589a84a764c16ec9dc760b0237ed6.nq.gz
│   ├── 585bfae34999bd7caf42d1d47f358020cee996e1.nq.gz
│   ├── 5fd30c71e0f8d6354d371f5bdfcf67abf97b55a4.nq.gz
│   ├── 60fc63205095907a698264408e4bcd3781e554b9.nq.gz
│   ├── 64d0f101e00df1c24278b93f3be602445634d1b7.nq.gz
│   ├── 65d90633be2c3c56781701e4cdc90fb43d4d4a16.nq.gz
│   ├── 6633c2a58c8f6bd311bc2cea32d1ec4fee8ad856.nq.gz
│   ├── 6b98522ee4e4bec37bd1b3c704a13d6ed8c1cb42.nq.gz
│   ├── 716b249af86d232e3bcf42f9f4b0a49445dd0578.nq.gz
│   ├── 7444fe2de9be4c04ddde039ec33fb5f4cbff9528.nq.gz
│   ├── 7465e248a16558af50fa452c2e639f21e39f5512.nq.gz
│   ├── 756afbbbf37c1cdd00965142694feb0acf14b4ec.nq.gz
│   ├── 75dd8422a09a0ef616fdc2c59e40f44a44ee2151.nq.gz
│   ├── 767dc21761bf7017571daed7269545ab1e7d2361.nq.gz
│   ├── 76e21feddb97fc96b2c1ffcd3802fc2f9f928f04.nq.gz
│   ├── 7892984fcb30f33c93fe2367b9ac167439fb441f.nq.gz
│   ├── 7a49d1c1d942b4f3ce167df9f10c10f169f66bab.nq.gz
│   ├── 7b98156c85f021943195181ea465dc895616a556.nq.gz
│   ├── 7b9821f28da17b03e1225aa73da915e725b18c98.nq.gz
│   ├── 831b012152288d4826a8aa886534e9320f5f0151.nq.gz
│   ├── 84f05e98ef4f50454598c973d34e6ee4d8024770.nq.gz
│   ├── 90323dbf58126fd573708a8ed7920935aeb727bc.nq.gz
│   ├── 9988dce6d9249d773d7e1b0c0ed8aeb03a8b2f0f.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a08f512ec1824d5b90017561789ad6d47261fb55.nq.gz
│   ├── a4568ee44b43fe43c29e805b8d669d9b822a7822.nq.gz
│   ├── adf74f5f77351ae09d70f26f6c4c5df1a79537c5.nq.gz
│   ├── ae0f9e5f672e0b2971968bf92f11a65c9b237a8e.nq.gz
│   ├── b2028df9585dab1e5ceab4bc4b6cbb14fff90e6c.nq.gz
│   ├── b478611642666c0eeb081df2e5c48a3936223627.nq.gz
│   ├── b7b579d2a2aa6444b668b4b6d13fa8b52fe509da.nq.gz
│   ├── b904c91325b8a1c0afc1efcee5d1053fa44a3bc5.nq.gz
│   ├── c10d084e0369b69e29bd013a34d4d79867702895.nq.gz
│   ├── ca0b0e85d7d29622355798168a81abeba72eb620.nq.gz
│   ├── cda50f0ae2dd36b6e0271f6789aaff4b54c4870e.nq.gz
│   ├── cdabfd01f8d14c6606f4f14a17be091f94676adb.nq.gz
│   ├── dd1d2ac030c58c19e8f2a274f5d0f1729f7290f1.nq.gz
│   ├── de5a4050e4de0f88fd916248b5d9ed3f17744d16.nq.gz
│   ├── e13d3b56c80a3276313bf19949869ce153c9110b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec02886cda5526e7603735d29b31a970e17023d9.nq.gz
│   ├── ec1a02b8dc59a3fe349bbfe886c7d452b9bf9785.nq.gz
│   ├── ec3fe932b22c92c2df355eee6bef63b98dca03fc.nq.gz
│   ├── f027dadfce8e5616976cf509ac0f30c9e19c174b.nq.gz
│   ├── f13f55d91e0ebb766080a323e2672bb0deeda08c.nq.gz
│   ├── f1a784b9bcdb0793daaa04c587d9f1b141175e46.nq.gz
│   ├── f78e84a52f6fb3957fe6f5fff0b0387c5c514106.nq.gz
│   ├── f93501acd2b7237e9603910b2e421259559a6d30.nq.gz
│   └── f96306c103b08e3dfbcdd8b598e63defad5c35e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5f88ceda2c63b90f9b50118e4a4750380922c9c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[pysal/spint](https://github.com/pysal/spint)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
