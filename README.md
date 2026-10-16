# Repolex Knowledge Graph of sunpy/sunpy-sphinx-theme

RDF knowledge graph data for [sunpy/sunpy-sphinx-theme](https://github.com/sunpy/sunpy-sphinx-theme), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunpy-sphinx-theme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8578aae4bb1f5d8b14ed0fb13ac994339a722618
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8578aae4bb1f5d8b14ed0fb13ac994339a722618
│           └── chunk-001.nq.gz
├── blob
│   ├── 069be708dcd67ce266520c1ddb24b964fcbd6d40.nq.gz
│   ├── 088d5b4003115c02aa854b8cd9a3574260a8218c.nq.gz
│   ├── 0bacf2c7284fb8e39783e2136b597122ec2ee940.nq.gz
│   ├── 269c06aaaa2315683af253737aee4bf8f5315f5f.nq.gz
│   ├── 2efc2f95a998e5324ff84723a9e2d9009b9b7e85.nq.gz
│   ├── 302927cfc9e88675772087e9ace5f0ecd27c3103.nq.gz
│   ├── 33f0481e5459c6adb71dc2a192bac86ea96bd2bd.nq.gz
│   ├── 40f0e03f41adbea4bb95e9fbe0c1eef95008c598.nq.gz
│   ├── 45ddc6624c1a915d1a97e58f4c473223519def4c.nq.gz
│   ├── 48ce219b24f909fc96b1e466720b079c18c266dc.nq.gz
│   ├── 49c3e0bf997b145a49b09c6b0787f7dfb6830fce.nq.gz
│   ├── 4b2526a10ba298d22e9a7dde4912a3e14a245689.nq.gz
│   ├── 4cbee14aa71b6e35f767003ce7ce3bd579f34e83.nq.gz
│   ├── 4d8483744f5da850609ec12351e53405f293af69.nq.gz
│   ├── 4df80facb4cb008ca70fc145705ec50bc427d57f.nq.gz
│   ├── 4f23037d8800722918f92e47042e19b2ffff2c3f.nq.gz
│   ├── 502320f7ea7eb34871edfaf2c1b75e4005d616d0.nq.gz
│   ├── 50b33d74a569744a2fa486b335343f41612ed185.nq.gz
│   ├── 52e33b3a5be0a14c5cf45b53a4ab449ed436966e.nq.gz
│   ├── 541fd431e8fa1719f8058c9165c817d5438bddbc.nq.gz
│   ├── 56fbec8b9da9acceec7d606463efd8578761f89c.nq.gz
│   ├── 57cf667c065c739d1292332246deae44214637c9.nq.gz
│   ├── 58cf8095d665aa7fa4d07cd95048c30e31e09295.nq.gz
│   ├── 5a0a2541c001a8140d6ce0006157e4efce4cc22a.nq.gz
│   ├── 5da796080155af6a1eb095a9680a9d2b79d8fc45.nq.gz
│   ├── 5ed1b08053a918156c7ff1a646935280c35e339b.nq.gz
│   ├── 6084492e39ce617c1c7b36a429c4a0f34502524e.nq.gz
│   ├── 68de3658dffe5d4a9259caae2fc80505592a5c42.nq.gz
│   ├── 6c04fc550a5045b873997af861ad2a779569a257.nq.gz
│   ├── 74fd5e9b6ba1ec79f17086321be0846e1a61d4f1.nq.gz
│   ├── 782abf1e13ccc1a758d2abca460f0281fdac3203.nq.gz
│   ├── 7aa02f25bb847692f5215bcc0f2cf124609a3e5c.nq.gz
│   ├── 7bb240be6785e47cd78f9d3e69ac5e1a41ff6f6a.nq.gz
│   ├── 80e2d0ca9e373a822cf99d8bef58f9e37956b82f.nq.gz
│   ├── 81c1909eabc1d0e4da614e5ee928c0c5491aa805.nq.gz
│   ├── 81cde515ae2e6c490dc2a4293c2a98e603a416f2.nq.gz
│   ├── 82cb4703d2267076a1f942c58977e41d2319a4a7.nq.gz
│   ├── 8458481bb9b32e5d6fafdd7b131ee31e06ba4aab.nq.gz
│   ├── 8b2c2da39f4d9e6455b33c22b9975faf04b1c1b9.nq.gz
│   ├── 91bbb37cc621e8d7a7d03e0f088e35a3971be49a.nq.gz
│   ├── 97a592bbea78f04041941584fb2b4caf37f158f1.nq.gz
│   ├── a1ca9137d0e014d94a386920aa961635ffb75106.nq.gz
│   ├── a3223f457db1f858429c8b33a70768dcc0ec3fdc.nq.gz
│   ├── a761464cb02e1a57aa1594ecdcbca860be4aa619.nq.gz
│   ├── abb853d74afd056192be1acba5326848ea5fbdb3.nq.gz
│   ├── ae9dff48eee3fab055225ef037e98a2dbffeebb8.nq.gz
│   ├── b21e579f08ccf5fe30ca716a56da0372dd34a53e.nq.gz
│   ├── b22f2f87087554163b6b5f58baa2acbbd0be3426.nq.gz
│   ├── b618534ceac9552e2c1f8add053c5ec5c05c1194.nq.gz
│   ├── b9035f2750a3109ab4aaacf9aefdb82e6a37a88d.nq.gz
│   ├── bc18059ad8c8d584ec2e256900f0cf1d2bc2e4aa.nq.gz
│   ├── c8dfa1675f8a47c9b51a394d73cc798823d6aac4.nq.gz
│   ├── ccbb73e62e74630f06de4781e29ffc9ab4c15f2b.nq.gz
│   ├── ce97859de504f0dc4d325ebf17d4501ee1e1259e.nq.gz
│   ├── dc2bc284cfafb31d9f0c5f9e47b61535f92ea053.nq.gz
│   ├── dcfa5ef21f1472685557a40976a9bc8c19a88e22.nq.gz
│   ├── dfd0fd5464d5bc9929a16f2fecad3095edfcb43b.nq.gz
│   ├── e485152dc8748fc72d2c2c57dbcb2b3ab2002f6f.nq.gz
│   ├── ec937da355b95a722e79366391dca8df112a570a.nq.gz
│   ├── f21196c31b5933b688314df44cf562fa3007745b.nq.gz
│   ├── fb89b185885c93e2656dfb7a4dcb6f7daa4c0f62.nq.gz
│   └── fcc1183e9ecd4a3c85779b0e5ddf3d4fb30cb6aa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8578aae4bb1f5d8b14ed0fb13ac994339a722618.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[sunpy/sunpy-sphinx-theme](https://github.com/sunpy/sunpy-sphinx-theme)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
