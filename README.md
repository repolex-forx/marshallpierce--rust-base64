# Repolex Knowledge Graph of marshallpierce/rust-base64

RDF knowledge graph data for [marshallpierce/rust-base64](https://github.com/marshallpierce/rust-base64), parsed by [repolex](https://repolex.ai).

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
rlex download marshallpierce/rust-base64
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e14400697453bcc85997119b874bc03d9601d0af
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e14400697453bcc85997119b874bc03d9601d0af.nq.gz
│   └── repolex
│       └── e14400697453bcc85997119b874bc03d9601d0af
│           └── chunk-001.nq.gz
├── blob
│   ├── 02aaf5141e1a41f74fee638b922e1725d67fbc1a.nq.gz
│   ├── 0c8aa3fe76c50fe7caafdec2cf164bc22f37c736.nq.gz
│   ├── 11d46a73f3328aac3c515fd06612be8d01148b7e.nq.gz
│   ├── 128c6b85df98380daad66296f5900dc2bdef46f8.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1c19bb42ab73a16ea866dee48ef6421a64e6f25d.nq.gz
│   ├── 1f1a1650a6b47dc6a2eb5fb0920183f7848abc4d.nq.gz
│   ├── 2a617db9de7b2ffb982d5222643b902f3d1c3529.nq.gz
│   ├── 2e9df598fde7d3079cc48dcfdb3539f042d79e51.nq.gz
│   ├── 339636bd0310c6ad9e418a28ae882a0e54521169.nq.gz
│   ├── 3cd260e7341bcb8abce0e8ee60430c0495b133c1.nq.gz
│   ├── 3e5988fee49580cbbf9584090931b1954dde493c.nq.gz
│   ├── 4d2576dc824a49bcc4ad9287bc8ad55edf41df0d.nq.gz
│   ├── 572e03bdf321b6cc3a99488183436905cefd086d.nq.gz
│   ├── 579a7225cb75ea51a1b15fa8d909d647736d30b6.nq.gz
│   ├── 6df8abad2ca202e00322b05c9ffec8504fb33b7e.nq.gz
│   ├── 6fe958097b287822f2ef5458da7c6d0c35347779.nq.gz
│   ├── 7083b5433fe2ef36d6ea3b628236fd45e54dbe62.nq.gz
│   ├── 72bbf4bb046d29851a4109aa3852f89863208693.nq.gz
│   ├── 781f6f880e5537e1b5136826a70e019d6a106fac.nq.gz
│   ├── 7bc10f80a0499ea61b9d7da04a0f84293c44de54.nq.gz
│   ├── 817b339f3b8151dc17d20322fa7484ce2c0d7f6e.nq.gz
│   ├── 856064481cba1745a30595e91ef1d5bfe85c52e7.nq.gz
│   ├── 8f041854e1085ada27702ecaac737159c3e09fc1.nq.gz
│   ├── 90e5c7a40b62eeb9eeda64b11f7c687feedca61a.nq.gz
│   ├── 91b68a6782095dfd3dbc9ad6f0c877ba66686d87.nq.gz
│   ├── 9c02bcde84fb4d97b62901d1352a479063755ab7.nq.gz
│   ├── 9d6944741aea4c0d3efcd4faa346f8421dae0a6a.nq.gz
│   ├── ae6d79074d71f933c3b207ccfc497639f67570cb.nq.gz
│   ├── af509bfa56b6a5a98cd50d56dca1a0632ddf618b.nq.gz
│   ├── b07bfdfe65823ad8da905cbaaef3841a0bb16587.nq.gz
│   ├── b35b2f3eb65ead6b9e45a88b0d7e1b3a78616fa9.nq.gz
│   ├── b55d3fc5c8f7e5c371a21b75e1b51f692b896e29.nq.gz
│   ├── df5fdb497c6ce6bf40a5685af151f37cdaf4c4f6.nq.gz
│   ├── e59a371083440dd22924933a431a92779a60b78c.nq.gz
│   ├── e9edb0445ea387bc24d52a0fc2acf27d861632e4.nq.gz
│   ├── ea2d4050388e30d6d49e24ef09fee6460fa50997.nq.gz
│   ├── eceff40d6a33bebac4782b7476d659bd29858456.nq.gz
│   ├── f2cc33f607c12ef651973335136cefda0bae5b0a.nq.gz
│   ├── f343145744815bac7af83700a457e3d75280c902.nq.gz
│   ├── f566756d51fa4968eac0472603852b39e8b20317.nq.gz
│   └── fc292f1b00a66a4c1c7408335ef9b4e828d85dc2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e14400697453bcc85997119b874bc03d9601d0af.nq.gz
├── filetree
│   └── e14400697453bcc85997119b874bc03d9601d0af.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[marshallpierce/rust-base64](https://github.com/marshallpierce/rust-base64)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
