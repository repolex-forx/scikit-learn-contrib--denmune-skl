# Repolex Knowledge Graph of scikit-learn-contrib/denmune-skl

RDF knowledge graph data for [scikit-learn-contrib/denmune-skl](https://github.com/scikit-learn-contrib/denmune-skl), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/denmune-skl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b06d026fb657e923fe31631d45252172e2b1b542
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b06d026fb657e923fe31631d45252172e2b1b542
│           └── chunk-001.nq.gz
├── blob
│   ├── 08019ea9e96e1bb4789e6bce2734b1c4e6df539a.nq.gz
│   ├── 1bdab5a797f86c20dfffaa806aa47beec725f4b9.nq.gz
│   ├── 2bab858cf3b554e592e7d2bde79c402c06abaccd.nq.gz
│   ├── 2d36622cb7e55bf87691be85e6cebfebd71b0272.nq.gz
│   ├── 2de3c0c8970807193df1a288c6b6e98c4ba80ba1.nq.gz
│   ├── 325367769a7f99b562ab53b4dd254c31804f2695.nq.gz
│   ├── 3939a35e4b1547beccf87227bf4290c7489e7c04.nq.gz
│   ├── 3d70980454c4c2348210b9a3d1927c1be8921a38.nq.gz
│   ├── 413ca866d13f2ef2ef10ce4604fce1f27281c697.nq.gz
│   ├── 46310f9f4d12b3ef392402409739eec503c56889.nq.gz
│   ├── 508376e44f20332a0a471b40ddf8c2484a99b015.nq.gz
│   ├── 51320964cdf5dc7709ae70a8c7b0195bc9c1b4cb.nq.gz
│   ├── 52e3f96493791e4da205dfc6647b73c7b3a8564d.nq.gz
│   ├── 53ba6559ac0fa2ab50c30188be7d9168d4a587dd.nq.gz
│   ├── 59369dde38eeca7c4e58570b4b0ee091d64542a2.nq.gz
│   ├── 62b416bb4c7d96ca4a302aaf7949d76604ddaccc.nq.gz
│   ├── 69f7ba1d2d114598b32a93552ac9bb89b3173d6d.nq.gz
│   ├── 6a1d992fabb5522cfcedb1f6cd13ae52310e8fae.nq.gz
│   ├── 6e05af9a41a1cbed04c0d77408771001952502dc.nq.gz
│   ├── 701aeb7648151a3b116f1e3644279a8aea8d3b3d.nq.gz
│   ├── 7806f2a6b2c4db05788fd9ccccaa767007354be7.nq.gz
│   ├── 79c1e1984b87bc0b5c10ae5cba2cc1a94a1051c3.nq.gz
│   ├── 7cf7ce1856aa9c8308f80421235dcfc3380a8ebb.nq.gz
│   ├── 8077a5f62c925fbb96e6e5055eb0586a849ad5ad.nq.gz
│   ├── 82318349effecdd5d318bf2e371cb5e214dc76fa.nq.gz
│   ├── 8ff1c866572d301eb0387491da18abba72a9e8f2.nq.gz
│   ├── 9a595917bf0f68b6448076b91511bb1dbf64e3d3.nq.gz
│   ├── 9b16b4d35cbb335bf749e39292bdd1d5584f5103.nq.gz
│   ├── b055862c0450cfde61983ec3dc74f6aaff001e19.nq.gz
│   ├── b3340cd2605b36a6888c4a97f04e729060706e33.nq.gz
│   ├── bd170535170a3b40235482d895678e5d939e32f9.nq.gz
│   ├── be595650c556b561400e2de515128a5b494c7b3f.nq.gz
│   ├── c1af3ba9ad97b5f5bc02d9530b02e0539288cd50.nq.gz
│   ├── d536b14ef201efe9cbfb698bb7858625aa747a1c.nq.gz
│   ├── d5559bbefd75a84851c05dfcf98405f4af209b20.nq.gz
│   ├── d87f56998175b91b21e7ee53ea806064fe0f78e1.nq.gz
│   ├── dc90cc86665f49d8bb9c7a2786d45b0bf3d6570a.nq.gz
│   ├── de3d902379383c8f30e4aafc91e9a8d933ae80b0.nq.gz
│   ├── e164557daa8f9eaaf701e3515b5460e9eb777357.nq.gz
│   ├── e74f38f362c6c6d6afed8cbe6ead03e66b1e9c18.nq.gz
│   ├── f7fcf005e99e1707a5b1a258117c9709139c22a0.nq.gz
│   └── fd6a35f7662b07dc9058a8ccc0a42e161ddbc6a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b06d026fb657e923fe31631d45252172e2b1b542.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 49 files
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

[scikit-learn-contrib/denmune-skl](https://github.com/scikit-learn-contrib/denmune-skl)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
