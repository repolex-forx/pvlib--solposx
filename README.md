# Repolex Knowledge Graph of pvlib/solposx

RDF knowledge graph data for [pvlib/solposx](https://github.com/pvlib/solposx), parsed by [repolex](https://repolex.ai).

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
rlex download pvlib/solposx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 498c7cc10b3b7275d3f7683ef27b40d7665b84f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 498c7cc10b3b7275d3f7683ef27b40d7665b84f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c03ec7c2396f8fabb93a74347354342c27a2b2.nq.gz
│   ├── 03a84d5eb91ae7d21c008a98a4df878ba1416c99.nq.gz
│   ├── 061f32f91b96f05f8fa2b52b2edcdcc19aa33d50.nq.gz
│   ├── 07eb5d1f79ee3964d637ff5615c1c89e62631666.nq.gz
│   ├── 0882256b56bb7c0bd6750c52cf2e4d5ff3043110.nq.gz
│   ├── 15d84df86ad411d68f4bb74dbbb1eb5281cda3bc.nq.gz
│   ├── 1d3ffe610614c3c4a1c4ea28479da610a9ab88f4.nq.gz
│   ├── 2690721cbc4be5f6b9f79242ade5c1a333176e25.nq.gz
│   ├── 2b06f4433a7e96b33092ce81f59261fb0539802a.nq.gz
│   ├── 2bc14f62f4ebc00e7666536ddebb072252b88e00.nq.gz
│   ├── 325ecff7388e526e6f39a1339cceef14dd46bf3a.nq.gz
│   ├── 3958429d90797c2d941e98706aae763ebc4e1bb8.nq.gz
│   ├── 3acc32bd8ac55bc68c71804b7c335a904dab0f79.nq.gz
│   ├── 3fe84cb9e669318670bee58397cccaa271bdda26.nq.gz
│   ├── 40f5717697896995570a47db3e5f1d5e437bb2a1.nq.gz
│   ├── 415dc43841d80e9af0a9a3ea8837ecc2ebd055b3.nq.gz
│   ├── 4bbe1826fc59d16f758d286718a784a14fb24b42.nq.gz
│   ├── 552deceef81cbad2273a5311dd58726b5d3238f0.nq.gz
│   ├── 562e12e188409e09676c6cd67504b0bd385b6212.nq.gz
│   ├── 5d4226160bc66c9eb60ff5f9a155618b2eb147fe.nq.gz
│   ├── 6072672f95cf9e4498976d166353a8f144f08b92.nq.gz
│   ├── 60f602feabeeba85f1ea137a173ebb967ba765d9.nq.gz
│   ├── 6180acf92b54aec91aff6e851dd2ebe38b70ba00.nq.gz
│   ├── 630a94c2d96e21695afc9a4b03dbdf31271eeb0d.nq.gz
│   ├── 644b12d1244c745d02b8a6cdcbf5cb5f5235b004.nq.gz
│   ├── 67695a4fe8e86a203c03805b3634fee853131d59.nq.gz
│   ├── 6d6129f03b84b66bf3823c9b4ce8ee85814f0732.nq.gz
│   ├── 70ac25074a2e86c9d42193fa656acb02c7a93cb0.nq.gz
│   ├── 72a03c8cae2cee066a40e65eaa415ae4fe90a7b2.nq.gz
│   ├── 80dd57b42ba3385569f8e991ee174ef0d9a921ce.nq.gz
│   ├── 821e8406f55a85c9df9cdf7efc5025c73cd4a28c.nq.gz
│   ├── 8717762b12b55a87cf1f4f3efd7318c2bd777d25.nq.gz
│   ├── 8b4dee55c8e10ba63a24088c5fc37c755003bc43.nq.gz
│   ├── 90094d19cf1e5a3a0c4554ae9a3ace088eec1e6d.nq.gz
│   ├── 92aadedeadfa1b76844e743a17961ae995e95a30.nq.gz
│   ├── 9c2d5fa596808157933c9d196dd25918290d3cc5.nq.gz
│   ├── 9d5f1163ba1567e868246994175bc9c24344625f.nq.gz
│   ├── a0273ae796a2a35a7947fb387fbd0539adf58402.nq.gz
│   ├── c1546cefaea6806d30e53e40072c53b216d689e0.nq.gz
│   ├── c8c7d6b1e1156748a51b388fa0851cf26fc1f07b.nq.gz
│   ├── c9f8507cf1834e2f2b6c3d477bf1c8c06f2cde68.nq.gz
│   ├── ce53213a2298da0a096e8339bd25fb01a4949f65.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d2b0eaca5ead3570d62bf84eeb28e25787a20170.nq.gz
│   ├── d2c7eeb3d049356e74deb5c4271ae8cb0a34ca58.nq.gz
│   ├── d3f85352feb62965f10f4b185652e067e9c72c37.nq.gz
│   ├── dccf38f350a17c1f08966a4489d275af9e35f498.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f2e1d8dadd82cc7495b00ff7729ba5329806594e.nq.gz
│   ├── f83c8ef3f537b69cd73242f05ba00a773fbb0436.nq.gz
│   ├── f88abf2c6cbd4b0cbd57c34860c3741a2dfd246c.nq.gz
│   └── fb205cc453bdf02a4827d2e010331e39e13b5493.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 498c7cc10b3b7275d3f7683ef27b40d7665b84f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[pvlib/solposx](https://github.com/pvlib/solposx)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
