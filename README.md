# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-django

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-django](https://github.com/sphinx-doc/sphinxcontrib-django), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxcontrib-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0c06ad2379d1056148699095943c8a463e81bf79
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0c06ad2379d1056148699095943c8a463e81bf79
│           └── chunk-001.nq.gz
├── blob
│   ├── 040b4ed81fb3d2e1087603e5eb5b141271591ce8.nq.gz
│   ├── 0fbcf503804086371795e3a49353f37f5e1e49bc.nq.gz
│   ├── 111a009e91f13448eb57d9648ddb0dce2c64c334.nq.gz
│   ├── 1167d98e439b44daff807bbebe03fbc14de39899.nq.gz
│   ├── 142df9b0d00569b629823a1c51fd7b77c6d84db8.nq.gz
│   ├── 145ced041edb345a52637d3fdac5217def10e350.nq.gz
│   ├── 180f0453c7e8ac10032d1144baa6b640d6a0956e.nq.gz
│   ├── 1b8e741909dbfd3af0ff73f174028ec525f8c729.nq.gz
│   ├── 1f3d725a0a303e178ad51b1b157ed931d24ded46.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2732a37c7bda189adfd05f55daf135f17fd7ddc5.nq.gz
│   ├── 2b5ee5089cf439f2c79df6aa00669c474cf13c15.nq.gz
│   ├── 32633271a8ec8f9ac6f7d388b098d35669278910.nq.gz
│   ├── 32940dc51e6598df0d12bcfd6ef2ce464969418a.nq.gz
│   ├── 343269a6098dffc1a444e0d814fc3babbd19d2c2.nq.gz
│   ├── 39f2bdd9ce29d83e5a956e98f46492f3ee4b16ac.nq.gz
│   ├── 3a769a971d0fbbdadcae8fa07e58828f0d34faa0.nq.gz
│   ├── 401a6c974085151f4324d071fe65e6ae92c9eb74.nq.gz
│   ├── 4a50162a4efda45ae983f6413ac42bc8cc09dd51.nq.gz
│   ├── 4df95b48498b11b0fc090ff089c38500f6bc5c8f.nq.gz
│   ├── 4fa69a141768996ac8846663c54c556cd0f7afc8.nq.gz
│   ├── 4fbc0801b3efb390a25701b6ee4f690ffa361489.nq.gz
│   ├── 5187ccb03caa9163a339d8931d115a26dbdfb265.nq.gz
│   ├── 544a0414c009ae4ff96c2b01ee7039c1beae8dc1.nq.gz
│   ├── 576be098bb6cd08942a9ac3c743420e126490bbb.nq.gz
│   ├── 5b88894b76ee51cc16831e7b47dcc1ad72e866e4.nq.gz
│   ├── 5f7565442bc45dfbc25402acdb705de38dff8894.nq.gz
│   ├── 607b0d9840e1e617a69d23aa4aef0a665f31910e.nq.gz
│   ├── 69c9f25ac706b3313085d9cfeee4c5bb001c975b.nq.gz
│   ├── 6b2b3ec68c627e4cbbf773eb34269d5b8b703cd5.nq.gz
│   ├── 6c8db51e006ae27b454948a4ed69e8aa44a37007.nq.gz
│   ├── 77e2e2adc1ac07e4772186bcca182e1afe838d58.nq.gz
│   ├── 7f0f9c46482ec46d4f32c7b7bc4f2614e6ad0ee3.nq.gz
│   ├── 81ed3675840f5f21b9b7462854e29ec11eda1023.nq.gz
│   ├── 88f50097be5a8696f5d85e9ebc87f11e6a57ac3b.nq.gz
│   ├── 8f4cf7c32af99d6366e3ad670fe6f943e5d62eef.nq.gz
│   ├── 96849eacf63763704864363ba7629d40b8495908.nq.gz
│   ├── 9797093704ec3fdc18e5e0fab0f22be40bcf4dbc.nq.gz
│   ├── 9f6329bc6f7bdba83ab3a6ea08b4189f712d79bc.nq.gz
│   ├── a07011f7c34900c6cd7984ac9e0a8057d3b4f1c2.nq.gz
│   ├── a6bf5e4031f3559aa46d8e8c7391244fc5e8fb4e.nq.gz
│   ├── b0cc71fc2047ff5ffdb29d24bb8ee9b6c9b935d2.nq.gz
│   ├── b25842464554fe8413dd240b7a4ee6b8e9424e32.nq.gz
│   ├── b4260dcdfcc787940bedeac8ed751506aa3106c5.nq.gz
│   ├── b8b0d8671d4fd7f7f0df798ca1c72260bbe3a1ac.nq.gz
│   ├── bdb4b46d3960d7a47ac8c1dc43a1b88bb042eba4.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c3e1acd35e2ddbc45bbfb9a2cd95fb2c55082ab4.nq.gz
│   ├── c58723594254f6e62eb35eabc6db2e6fda0565b5.nq.gz
│   ├── c768ba2b911381fca99f0596fdfab4f9f1fa3e52.nq.gz
│   ├── d4758afa1571bad6716305abf29c001dbd10cfe5.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d5256345c98b579524e1c0388baa2f470fdd7f41.nq.gz
│   ├── d638d22ee87dd7859a0f7f95555fdf3c7c6d9ad0.nq.gz
│   ├── d83429fa69bdd37affb848b91f330669f9ceb9bf.nq.gz
│   ├── db251d36b6914f33c9cf62a5c44b644e5ec7d8f7.nq.gz
│   ├── e178c3655aaf95d46ef9ec9b7bf5de535c46798f.nq.gz
│   ├── e9215e499a75bcc433ecc9a966a9f5e216df61cd.nq.gz
│   ├── ea8c8383a2a4b0eeba53ea6857c6d96f62dde55f.nq.gz
│   ├── f20bd15660a64dd898ec0e790e92e6f4b3fe6306.nq.gz
│   ├── f82a862cfb621794fbf30ed8fcad392c18438c0a.nq.gz
│   ├── fb839ac8cc5d0136884fe2f6f6c27562c5e0f61d.nq.gz
│   └── fe5117882b934f7bcee6e39e703f863dcf0d39f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0c06ad2379d1056148699095943c8a463e81bf79.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[sphinx-doc/sphinxcontrib-django](https://github.com/sphinx-doc/sphinxcontrib-django)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
