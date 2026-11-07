# Repolex Knowledge Graph of plotly/dash-component-boilerplate

RDF knowledge graph data for [plotly/dash-component-boilerplate](https://github.com/plotly/dash-component-boilerplate), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-component-boilerplate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 78b6c964e411bd80aa15e4689ca6d2a976ed0c54
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 78b6c964e411bd80aa15e4689ca6d2a976ed0c54
│           └── chunk-001.nq.gz
├── blob
│   ├── 06a8ae6b8c743382261cdc7133799063e5bc3bff.nq.gz
│   ├── 09a1a7ae34e950c8d5c491c5709040b5386704ed.nq.gz
│   ├── 09c07c6b842c93c3dcaf27f3aeb6e5ffa39ae5a4.nq.gz
│   ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
│   ├── 19db65acf4b4c1687d0ad163d7b075808533bbd1.nq.gz
│   ├── 1a25d496d3421a37e1779b5357ea23e11b65e30d.nq.gz
│   ├── 1b318cc88f4bbae891e9220a7d51f9aba11ae460.nq.gz
│   ├── 208c8d7151ddf6e6f43493498c7d9e4caa64d671.nq.gz
│   ├── 27c5d0dee72bc0c3eb5d5e7a98d9646d1919908d.nq.gz
│   ├── 3296e4def6d63de0dd63a3146c73babccfb6d9c6.nq.gz
│   ├── 341d28510a9cb8ad8d2095ff82792b9bcd3dda0f.nq.gz
│   ├── 4419f9581f89be3b741bc17228c107b9238221b6.nq.gz
│   ├── 4474427c0e091554ec66877e3e2aeec9d9653082.nq.gz
│   ├── 49e9a9e683d24857bf59601ec28c0a949fe004c6.nq.gz
│   ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
│   ├── 561f9c2de03ef72203be647bb139d40c8c45b2d0.nq.gz
│   ├── 57c1297fc8b456b65143cd0d723cdd39762ae2de.nq.gz
│   ├── 588dd3e9a7c3f9dc175673d88918332897740120.nq.gz
│   ├── 5e38c09458420c18acb7b5ff5d31073bd7f60700.nq.gz
│   ├── 61e259f76d2f9c24e094a9386f7c90a1d2a47764.nq.gz
│   ├── 69227a1441391203ed75813a57d3ba2158eaf647.nq.gz
│   ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
│   ├── 7aad0dbb410ead5fe4c0470bae67ec6029923eac.nq.gz
│   ├── 7e4d35ef0ac27311c158b8f23fd3026409a3abb4.nq.gz
│   ├── 825c32f0d03d98995ebe3e6d797f14daf2df51d9.nq.gz
│   ├── 93e70a360efe716165ff194b6b02b55c2d3449eb.nq.gz
│   ├── a1eb70e73fb7bd3629bcb804fc899f626bfc09b8.nq.gz
│   ├── a86673d72564001cb4a122b0ee4b28dbc5c4ec7a.nq.gz
│   ├── aa6db38985c6d5e995529f2c8e18840c285b548d.nq.gz
│   ├── aba519b68f4ab4acd72f86f069eed6d5dc10b2b2.nq.gz
│   ├── b597a44232c2a3b77943c95857fa5c6075cf69d8.nq.gz
│   ├── b6302a609ca04e8b666ba4a70e4a516341363243.nq.gz
│   ├── c834fa224cc2ae47d8239b1cd73d51b83570ea34.nq.gz
│   ├── d5814114abd4dba46d19849c5c772870defc1c93.nq.gz
│   ├── e4ce941ae752b81d6e87bafd3aef41438c606a90.nq.gz
│   ├── e61dc979a5d724ec1cffd66f22fc87ff76ad71d1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9f14b969c9ee64de6729b79d4c7f01d031a399a.nq.gz
│   ├── eb2f603be8bea6758a268737279adbfb0523fa05.nq.gz
│   ├── eb81a49a94228fc85213e5bd9c8d45722b89887d.nq.gz
│   ├── eea45422a3499d810f07a0b82262b9a100eef918.nq.gz
│   ├── f367b2061580d80730c399d834eb703da68d98f8.nq.gz
│   ├── f6f6a602797ee73a414dac002f4b2db4ca3938e9.nq.gz
│   ├── f7ed3a178536ad72dc68e31cfc1a6b6d8c40d44a.nq.gz
│   └── fc390281b64949437b502f1d84f1a9a79851621e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 78b6c964e411bd80aa15e4689ca6d2a976ed0c54.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[plotly/dash-component-boilerplate](https://github.com/plotly/dash-component-boilerplate)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
