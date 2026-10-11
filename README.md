# Repolex Knowledge Graph of cherrypy/magicbus

RDF knowledge graph data for [cherrypy/magicbus](https://github.com/cherrypy/magicbus), parsed by [repolex](https://repolex.ai).

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
rlex download cherrypy/magicbus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 030c66688f4a65834047f4860f34e3db3df16166
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 030c66688f4a65834047f4860f34e3db3df16166
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cf5f6c73e0904decc0ebffe8080de194ec92f9.nq.gz
│   ├── 050272f686387c86e671365280449c48d13ad3f6.nq.gz
│   ├── 086d9c5000012856519c99dd53b4d362b55140b7.nq.gz
│   ├── 09a1ada835df6d6e8fcec1bb7cf9ba3793c79678.nq.gz
│   ├── 0a1906b8769e9476d6c3f9100138b3d28f9afc51.nq.gz
│   ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
│   ├── 32e88ac95b5746802028eed3e0e3de3fb4e91149.nq.gz
│   ├── 3c90dd00124b2eb09eaa1552fafdfb8f812c0082.nq.gz
│   ├── 3ea1f8d2acf3134164efa8993820de2df61b4a06.nq.gz
│   ├── 43437728db83069a3000aa1dfb3bdcd72c8aa81a.nq.gz
│   ├── 445f33aab30ed3e8a92b84471cfdeae9bf151a57.nq.gz
│   ├── 4a8fcdcd2b97513ce955b79e098c77ab39e08c27.nq.gz
│   ├── 4d52a0739270dde42a256c6915a39a6b0109d5d0.nq.gz
│   ├── 4db39ea08af0db5deaf8b149b31efe1d90825b29.nq.gz
│   ├── 50fb047fe02b3cb065a78f6e774166834bfc2afe.nq.gz
│   ├── 55e90ea5ba72d4edbf0d7d5243eeaac45da91964.nq.gz
│   ├── 5a6c7e3a4f33bae3fb798f9f218f92071ad52be7.nq.gz
│   ├── 5b97ba97250e07c83aca0c341f3b12c5430862dc.nq.gz
│   ├── 601fc08087017458c814c623d18cc2fed4546a21.nq.gz
│   ├── 6118b34634e6559b390bfeb536e7d309c9639b6b.nq.gz
│   ├── 6215252d4fa9b71e92cfedeed038ee479f726933.nq.gz
│   ├── 68bf02c49f131e9434b18175116f2a39e2d25059.nq.gz
│   ├── 6dbb5a0cab638ab6eae04636f75b7f134a7a8a46.nq.gz
│   ├── 6ef52ad7c232196d5ae4ecbc3f94e9f7373ff9e2.nq.gz
│   ├── 73683a1bd5e380c1f9c00de934fcecd14a2438ca.nq.gz
│   ├── 802e8a43d7d42c009e1d0f3a1cecab6adcc1336f.nq.gz
│   ├── 871e2d9d0708374b475825590a43bfe4b45c31b6.nq.gz
│   ├── 892f6f9337b56840983da1884adb9b5cf0efed0e.nq.gz
│   ├── 8d60f40b33a6800b6b7464f60bda0466d160a1d8.nq.gz
│   ├── 8e217503ba1a68826af8e1e9db4bd16ce7a21857.nq.gz
│   ├── 8e68935207d37e4396b3b26a61c03fc459dd578e.nq.gz
│   ├── 960e502130fa91d3e65932f24ada9c861cfb7991.nq.gz
│   ├── 9d9c5b5f09de98951bae80ab1ae775cded95b8f1.nq.gz
│   ├── b744ba55e64429e4881c66fe815935c2ce23cb78.nq.gz
│   ├── b8afcb528652d3db129150a429574fe40edf0fad.nq.gz
│   ├── bcf52465d3de6f6f7ac479f996432867c24e3172.nq.gz
│   ├── be5d1bdf7db12fefb012018ba01c802dc31c08f5.nq.gz
│   ├── cc3718fb164212efa610b9e4a8bf4c9dffb60fcf.nq.gz
│   ├── d0c04912f75c2b6cc8330142232db405222a65fc.nq.gz
│   ├── d623c512c1ab6d040f604f0bdc99548002808be0.nq.gz
│   ├── dfe6b4f0ef00d5ac1bd3bb00c82310dc054d354c.nq.gz
│   ├── eb92377f1c2c5dd8f8c09d21524fab21f5663569.nq.gz
│   ├── ed0d794a0660da32fc4997ef4f450d48974bba09.nq.gz
│   ├── edad554d4980be2a5e0563bdd299d29e77c102e1.nq.gz
│   ├── f2565ebfd5a77e99d6d1286b937678ceaa246fda.nq.gz
│   ├── f808fa6324d3da12ecba7bd84dd5dd40e8ca27f8.nq.gz
│   └── f86e49662b3514efe03253c7463bef5833a098a6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 030c66688f4a65834047f4860f34e3db3df16166.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[cherrypy/magicbus](https://github.com/cherrypy/magicbus)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
