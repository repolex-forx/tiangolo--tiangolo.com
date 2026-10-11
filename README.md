# Repolex Knowledge Graph of tiangolo/tiangolo.com

RDF knowledge graph data for [tiangolo/tiangolo.com](https://github.com/tiangolo/tiangolo.com), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/tiangolo.com
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e61748bd410ee51b2823c446a13fc1f04eef9bf3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e61748bd410ee51b2823c446a13fc1f04eef9bf3
│           └── chunk-001.nq.gz
├── blob
│   ├── 09c4fae679551276fd37d8f169dd127fff8a2e04.nq.gz
│   ├── 0bfb2d46f6caa4ba90b974203c8abd5344b192e3.nq.gz
│   ├── 0e55d05f1eca183de18f49df66add97f4b999b27.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 16b9f6359eb4415765532e7468f67561e5b95e64.nq.gz
│   ├── 1a8c6dc2e0c4a8c79f0934945f9807ac266361ad.nq.gz
│   ├── 1f1fc7d2b8b63c8f9102a8462bd17ec2c6e5d245.nq.gz
│   ├── 2bf869e2206375898cc54be38a69e2c032238af7.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 34b82a058d7145caacba0236d7db946bcf3035eb.nq.gz
│   ├── 3794058ef2b85d7c915f094e7cbe28b5489e8865.nq.gz
│   ├── 545d30a18cec93495328868463868efc1fccb7d8.nq.gz
│   ├── 6dd15f38002b202ddea7a0bdeaecc424b5eb8414.nq.gz
│   ├── 6f2e7ec30c3615fc3266cde9e3e4d8b8f67321eb.nq.gz
│   ├── 707972c622d8175fd71105c8f33d41b7c9947e33.nq.gz
│   ├── 7619333bc2e9fa101da45e9418a7eca5cd012c35.nq.gz
│   ├── 77d0e6c5aa917cf5fd5edba06c299be7a7b120a8.nq.gz
│   ├── 814f7946cf8e844680dc80f9448a52c00b779add.nq.gz
│   ├── 8dc0d292b49e255de90f2078799a5aceb9a7955d.nq.gz
│   ├── 8e9ddbc311a3e93e585f3d586bc7a0a82aaa609a.nq.gz
│   ├── 8f113aba0dc1d962e87a6228f485d2eb053851d7.nq.gz
│   ├── 9435ea5d8ec8e15a6c4e91b65881b8cc9264a7de.nq.gz
│   ├── 94ab212d2a9e01f5c3f8fdc8b386f836669a19fc.nq.gz
│   ├── 950a70a7d00d174a07c9108dee6afe05a5a261cb.nq.gz
│   ├── 9aba52bb0cd57ccc6860b4922e7b0cccac350a0d.nq.gz
│   ├── aba1e31fe9a4711e397d6e124a049f9b90bea00b.nq.gz
│   ├── ae0b0d708daeaea074c9529a23eeab08beea3776.nq.gz
│   ├── b00cd21d70fe4118e2087e58fe67e9cea2e6c3dd.nq.gz
│   ├── b072693361ef469e9194f2607e72f290b10995ca.nq.gz
│   ├── b6bf1f62da6628a896b22a9dd35e5dcdb5a66f61.nq.gz
│   ├── b98b0b6c0b14e39277fa9edfd834df20bbb04c64.nq.gz
│   ├── bafcf081e1279ae81a5433de0ed27faf3a56852c.nq.gz
│   ├── bd8ef458c58280faa4c9dc97557b51d1e2d0f6bf.nq.gz
│   ├── ca09433b2ef20538fec35213200daafdb83c8c09.nq.gz
│   ├── cbe89a2b470cd3fc2a6ad4019d48fc116115fbdb.nq.gz
│   ├── cdeb10e3081b4265eaf5f2ae287d2702f2ede550.nq.gz
│   ├── daa6038a0a8a386d6315b541c501a9a2abddc650.nq.gz
│   ├── de4d8d1442e93d761007e4be0c28dcf6b157d8da.nq.gz
│   ├── e5d05e5e249e8b2a3ab05e3158f279b28c02d96e.nq.gz
│   ├── ed25f9be128fde05aad98074995a3d4b59df08c8.nq.gz
│   ├── f000ec015fa45ba33a72deb957ab06534b5bdd6a.nq.gz
│   ├── f9cbfca4c62dc5ec9cc94d64e203f5629d3b03ca.nq.gz
│   └── fad2c24c836f601b43a7eacde34e5355a30b27e7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e61748bd410ee51b2823c446a13fc1f04eef9bf3.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 50 files
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

[tiangolo/tiangolo.com](https://github.com/tiangolo/tiangolo.com)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
