# Repolex Knowledge Graph of anysphere/gpt-4-for-code

RDF knowledge graph data for [anysphere/gpt-4-for-code](https://github.com/anysphere/gpt-4-for-code), parsed by [repolex](https://repolex.ai).

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
rlex download anysphere/gpt-4-for-code
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 44a2b9718117b7c35646ed67d6493db2c1a38019
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 44a2b9718117b7c35646ed67d6493db2c1a38019.nq.gz
│   └── repolex
│       └── 44a2b9718117b7c35646ed67d6493db2c1a38019
│           └── chunk-001.nq.gz
├── blob
│   ├── 022fd9f1748df316e646df0320ec8b13b9a4c989.nq.gz
│   ├── 037712bf87de0aaf1f966ac353cc78991cbe800a.nq.gz
│   ├── 07591b2d9624039aa6ddc4c49ada25cdd3e47785.nq.gz
│   ├── 0c336bd05349ed224a45e56c6dfb23c4f35ee079.nq.gz
│   ├── 13e82719a6f944a404f59fe690d96c9aa04de161.nq.gz
│   ├── 153b0cec99552923dd4b9652303997294cc9e5a7.nq.gz
│   ├── 1b01e05217359c4949125cd22cee6fc840d01ce5.nq.gz
│   ├── 206caceee2ee63dd8817bc6a71e5fbfa9aa2e99c.nq.gz
│   ├── 23cde333ebb3514fdb63bc3506cb9551c550cc94.nq.gz
│   ├── 28d1718311133c835c329f963b62d4b7816a504b.nq.gz
│   ├── 2a1579cbe3e8eac5273cba161ce2b192a40e39d8.nq.gz
│   ├── 2a23f6f04ecd61cbc39238efc9413372818545bf.nq.gz
│   ├── 2a97ba52bc8b33a95cbabbec60cecfa4b0ab6a92.nq.gz
│   ├── 2abf15bb07a0bc96f33732ccf2f5660f682fb203.nq.gz
│   ├── 33040687af63350dba6c72bc16552099e4c14c35.nq.gz
│   ├── 3c73ad076b4a351daa346d7e8692b1e8e32f501d.nq.gz
│   ├── 3f724e06674d539b204a521266a6765d4eeb8a93.nq.gz
│   ├── 4631cc078b781ed01692798410dc3ecc942515df.nq.gz
│   ├── 4a27eb7cd3d88e6e9e6c43d588bae5922192cd69.nq.gz
│   ├── 54842dcbc7860c620a089494f93a1326c348457e.nq.gz
│   ├── 58461f25420fa09ee4a525651a0c54efa1b11af7.nq.gz
│   ├── 5ba652ebe69f9fc72dc2c8f6778f883753b94153.nq.gz
│   ├── 5c3ae248a4f6661a945b192adb85ddbc71531df7.nq.gz
│   ├── 6c4a6f6221a46c22e3bf4aad211ff0b8e0a91257.nq.gz
│   ├── 6d8ad95fa60324ffb53a432fe19b0be9b752adc9.nq.gz
│   ├── 71262599271bc09c50c03f4d08c4c1db1cdf224c.nq.gz
│   ├── 74a204a03ccfce126ae871c4a54974103dfb4127.nq.gz
│   ├── 7e31b2dd9bb649184f2417f281e1c3bed01bf163.nq.gz
│   ├── 7f3afbdc7a120e59f27601542f1f82d249f038f3.nq.gz
│   ├── 881c99ac94aba5814dadd9a1c48853f3c34a1a78.nq.gz
│   ├── 93d3c72ff28cb495554ebaf1b4356e2152f24ca5.nq.gz
│   ├── 958e965bb543df3fecb1be727810cf3ad3bd9f35.nq.gz
│   ├── 9706e010bb55e36bbf6130d60e04a6118be7b87d.nq.gz
│   ├── 977788fb4c2c025723f10104d3f112a89ea1c36b.nq.gz
│   ├── a1164661606e9ba1dcd16172231e9c096b7b4928.nq.gz
│   ├── a5400de4eb6cc1e5fb072491e8b1af573985f633.nq.gz
│   ├── a829281ee2f5938249070f2a7d16cc8eab086a89.nq.gz
│   ├── ab06fd0a9afba5536faf5f217b65cb2c57a155cb.nq.gz
│   ├── b4c831fcaa75de87972392caf8ebb111b9c1458c.nq.gz
│   ├── b5de7d79174b0e5f92208c8eee07fa55a3144d30.nq.gz
│   ├── c585e6908c202fa947df45f1b4d38194a5c4549c.nq.gz
│   ├── c7b910ace6258b5a78526bd1935b53e6e078d193.nq.gz
│   ├── cdb7db0e5689ba9e22cae157118470a9d1f87d0c.nq.gz
│   ├── d4707b04a365b63a95fcc4fdaeb4f55e68ef8884.nq.gz
│   ├── d5eb3e157172e0250d29066517049a283d74b372.nq.gz
│   ├── d8b0d10a950cc63b6a12ed55a0df8688f99d80f0.nq.gz
│   ├── e05fc3db7a0b94d467211ea3efd4c6b8ae7e0a06.nq.gz
│   ├── e43b0f988953ae3a84b00331d0ccf5f7d51cb3cf.nq.gz
│   ├── e61099fe1c951506dbfffe44fd410c572b3104a3.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   └── ffd91f0c628a325a8116da29b63b1860c8c7d4e8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 44a2b9718117b7c35646ed67d6493db2c1a38019.nq.gz
├── filetree
│   └── 44a2b9718117b7c35646ed67d6493db2c1a38019.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[anysphere/gpt-4-for-code](https://github.com/anysphere/gpt-4-for-code)

---
*Parsed on 2026-10-05 by [repolex](https://repolex.ai)*
