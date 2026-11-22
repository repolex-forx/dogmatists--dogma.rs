# Repolex Knowledge Graph of dogmatists/dogma.rs

RDF knowledge graph data for [dogmatists/dogma.rs](https://github.com/dogmatists/dogma.rs), parsed by [repolex](https://repolex.ai).

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
rlex download dogmatists/dogma.rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 05158408aca889a5bcc4ede013c42603f4e1c3c8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 05158408aca889a5bcc4ede013c42603f4e1c3c8.nq.gz
│   └── repolex
│       └── 05158408aca889a5bcc4ede013c42603f4e1c3c8
│           └── chunk-001.nq.gz
├── blob
│   ├── 048196a6ce7c96b97e5c3185b0bbd321dd50297e.nq.gz
│   ├── 0caee2bdc79ab927030115e3e61abfcb2caa34f4.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 188b41b1dfeb32a8727322b6341bae05bbc10642.nq.gz
│   ├── 1d9639978ccacea46d165a306158a1df408f5529.nq.gz
│   ├── 20f49513e15fe8c9e59ec1b906021854bd91aea8.nq.gz
│   ├── 22388e5c0c8f2293ef1bcccab28d822be750ffbf.nq.gz
│   ├── 2601b3f4151f2ad62821425751ff1867283aa420.nq.gz
│   ├── 280fb8d04170d32ee9c5f1537fb204382a2602ff.nq.gz
│   ├── 325f037f2ea92a9393c489af7008233349f3bd73.nq.gz
│   ├── 363b1b480d46620bfcd0496e98006a26d15d8a90.nq.gz
│   ├── 3e5d6cd439aa1670f330295cb99a2c1fc59e8a21.nq.gz
│   ├── 404fb6af016db3ff7051ebddc819ae87f4cdc466.nq.gz
│   ├── 50a18fe8ee66b6caa436effd57c4c6fc3fe967ed.nq.gz
│   ├── 5213658b08518531ab0e458ac32e01f5a69069c7.nq.gz
│   ├── 5ad21b8604ae98b18295d4ced9f31128b13bb765.nq.gz
│   ├── 5ec0354212232148cf7d4d3b43b9ee7b8b3f4c75.nq.gz
│   ├── 61edbcafa2a60e77e26334f988e25e34f059853d.nq.gz
│   ├── 732b68fb485cc0e83c8aa0deba1375bc650f18e3.nq.gz
│   ├── 75e3b65f99b29f48ab230e3eab3de8d0b7a9229f.nq.gz
│   ├── 7f98217f3747df8a2762b22700ad90b375750550.nq.gz
│   ├── 8c660a5e9da34e8b4baf6aa481b4d37a0996be6c.nq.gz
│   ├── a2d26607843f8a002639a6c8bbc4820ff0731204.nq.gz
│   ├── a718674ce58c2cb835775828c8a323d259c0848c.nq.gz
│   ├── ac4c3dfd2524a8c0595823e19ca5616192290346.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── b4f8bb0a76ab41524e7c5229223a3af3a04cf7aa.nq.gz
│   ├── c40555a0e9d73b775c5df6fb25aeabec15a6a781.nq.gz
│   ├── c7504b17b600cacd0a72d17b05bb8dae214c4791.nq.gz
│   ├── cc4f9f1d54de20d1935c6cfd9e983a282ac66754.nq.gz
│   ├── d2d774d685a805fac62723c16262a6ba9ded7549.nq.gz
│   ├── dacbecb27c59ba295f8903c20a64d36953dbd7fd.nq.gz
│   ├── dc159d8eea284343e27a2104d04e80a5fc6a9444.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e5c8f963b37e3439f6d2e68d65861444df37f4eb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e94d007030c7f349ab7a49bf213a046e494b7efe.nq.gz
│   ├── ea5015b4a081108bc30f363b12e4b84bbab4136b.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   └── fba305b0dbf5fe218ee6c22331c97308942945ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 05158408aca889a5bcc4ede013c42603f4e1c3c8.nq.gz
├── filetree
│   └── 05158408aca889a5bcc4ede013c42603f4e1c3c8.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 49 files
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

[dogmatists/dogma.rs](https://github.com/dogmatists/dogma.rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
