# Repolex Knowledge Graph of aio-libs/aioppspp

RDF knowledge graph data for [aio-libs/aioppspp](https://github.com/aio-libs/aioppspp), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aioppspp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08cda4c4b14d96771b7f485a8866fd2ddb5c97b6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08cda4c4b14d96771b7f485a8866fd2ddb5c97b6
│           └── chunk-001.nq.gz
├── blob
│   ├── 077852677062659f885c1dd4ab0060af4f87fd5e.nq.gz
│   ├── 18e86cebd220056292a1e2ea2fb1fd50b505b94f.nq.gz
│   ├── 1abc946ff544504bd38ae81674f53ff4e78aebb6.nq.gz
│   ├── 1af747afc377020f21f3423357966ba877bd4a5b.nq.gz
│   ├── 1e55c84260720d4406568d1ca79c2eebf388fc89.nq.gz
│   ├── 20e36816cf328dd63c00064011582ac83f58ed57.nq.gz
│   ├── 226209d81aee9ff8f6e799f8d5b0e788a3c73711.nq.gz
│   ├── 22e43423eea72b056b728aa36a04591083a2fca9.nq.gz
│   ├── 2c596e1c6c00b4291aef0e9440485d417f7976f5.nq.gz
│   ├── 358f8c2282cc4720ddaed0f8d84c5dcaae28cead.nq.gz
│   ├── 359ca4f48645aff40cda36741b2193f7ab6c41ef.nq.gz
│   ├── 37fa6047069ad454d7c373ccf3b559e482a27181.nq.gz
│   ├── 4533288e79edbc5b5cc93867ad9c8869368a9687.nq.gz
│   ├── 4b56f7eb2324f02d0d7d87caadce89f5674b77cf.nq.gz
│   ├── 4d0f654b9319babb9a61f8c95f9904331556845d.nq.gz
│   ├── 55c5e306f32b681332b1b5b60d892bba321d3f28.nq.gz
│   ├── 5b7b2b68d14498f3a612dc1fd768be35613074fd.nq.gz
│   ├── 5cf21b6dc7f1b4842b2aace8138503b1ce346d2e.nq.gz
│   ├── 646ca1b2087d0bcc6fb51c509d7d1adeb25f857e.nq.gz
│   ├── 66640926c2c1af59f204c9c91f3ecffef36fafb7.nq.gz
│   ├── 78371b99a7a884a14264da3c819893cefae057bc.nq.gz
│   ├── 823d77dfd6a912208b81dbaad31ff72cbf50aed1.nq.gz
│   ├── 83488d02daef5f15f6a0a290b772e247fa67ded8.nq.gz
│   ├── 8862c21b10e5c1a307d6622f16a9d755e4a976b1.nq.gz
│   ├── 89294bb09e6922a2a9d5dea810e68c60cc1df1ac.nq.gz
│   ├── 8c4366ad69ae0728f9cc8c166c0da3c7366313f3.nq.gz
│   ├── 8e1378500b6cd482c2882bb5f54f02eb92c91c09.nq.gz
│   ├── 92771f6af95d6cde1c10ecfcddfe7c415f4835c2.nq.gz
│   ├── 93c3b8ec458bced9022e6107a1630049229413f9.nq.gz
│   ├── a1631635b9775e0cc76610c3bfdc6c993979f399.nq.gz
│   ├── a2a404aef02e1bc9363759f078703a78edd4fec6.nq.gz
│   ├── a3911a12f103fe7638115ddf64ead60de98cb2ea.nq.gz
│   ├── aacfefc67feabfae482bb1e65053cf8abdd89fb3.nq.gz
│   ├── b09e926edaabce2c65e7cf67ed280b9fcc1237e1.nq.gz
│   ├── b31fbeaf74c83e5eb654c234590a16e81eac604a.nq.gz
│   ├── b5914971f6eb03c4d500d425728baa1361490529.nq.gz
│   ├── be79c427c681b590c5a33f171b0553e3b9d5ebe8.nq.gz
│   ├── be80ea610be7521ca3347a63f683ef1cf3854695.nq.gz
│   ├── c130000e249228fe78bb1f679c7a1f462a278fcf.nq.gz
│   ├── cdb84df83919d314cd1bd7d627187e5cc7091f23.nq.gz
│   ├── d9290ea93a80f2788f8895c969beaf0e4ac04a00.nq.gz
│   ├── dc425b605c43606c5f139d5ff58b20ccfbbc9a39.nq.gz
│   ├── dcf8d204a007e19b624810c8718e6a6a5b5843f0.nq.gz
│   ├── dea2a57282be3302c660df2f8b3f7afbf850cffc.nq.gz
│   ├── e660d38ee18c44b455af2626f8db186af70e2a6c.nq.gz
│   ├── e77c85dbf4e57a664173cbc68274707d29007710.nq.gz
│   ├── f0b917533bc69a31dffda6c0ec839393e157e037.nq.gz
│   ├── f5961e1a24bc5b7e60f4392a8d49fb0180e73bcc.nq.gz
│   └── fc81a0169051ce61fa29aa13f1744638e7f86fb6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 08cda4c4b14d96771b7f485a8866fd2ddb5c97b6.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[aio-libs/aioppspp](https://github.com/aio-libs/aioppspp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
