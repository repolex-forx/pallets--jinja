# Repolex Knowledge Graph of pallets/jinja

RDF knowledge graph data for [pallets/jinja](https://github.com/pallets/jinja), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets/jinja
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 019d804f3d4c7f3e4e945feb4d83b883de43bab3.nq.gz
│   ├── 049ab3b2d6f00cbdaba7a5580c80e696cd2c2a70.nq.gz
│   ├── 0597b7a80b46f63c4067f6190c27fd1b3367e2ed.nq.gz
│   ├── 06e799ec6ba345cc047411893d94762708a5913a.nq.gz
│   ├── 0aa46ee2f864c218019156cf0cd7d98fb97be284.nq.gz
│   ├── 0bc9ea4e8b4fd953035f89dac7a7c326b49bccd3.nq.gz
│   ├── 0c5b3657c8538e47be88b49daf91600a7936d9f6.nq.gz
│   ├── 0f30d5477f85f207e23628a30b97f53bd9e9e1a3.nq.gz
│   ├── 154cf44c96df86d1e14f685e9f913025c9a0ebbc.nq.gz
│   ├── 17f06eea272d31229f9feca43e15eede8aaaff94.nq.gz
│   ├── 1875711df49143b38b880111ef2cbb4ae01c979f.nq.gz
│   ├── 194390a9e9756706acb79a3eb1e25da72442bf76.nq.gz
│   ├── 1bde05694786aba2990c56a6d8678b8cc01eac4c.nq.gz
│   ├── 1c0421878aa935f4b77fdc8f2fc753a0f6ded640.nq.gz
│   ├── 1d25a2b9852e8ef9ba3e10f2134c286e753f0716.nq.gz
│   ├── 1d3be69a9656d4d3c90bd487dc4c59c53028a6ca.nq.gz
│   ├── 1e248d4d755d58f2853b3d2b9ffab262ba2580c9.nq.gz
│   ├── 1ea7d495ef556a8c517c658b9a125fe005050fc2.nq.gz
│   ├── 1ee6e2758a297bbe5fb026258299ef9980c2970f.nq.gz
│   ├── 2042fccf5c10a8d719b557400bf74fd868b875b2.nq.gz
│   ├── 20de3695b7faef5a60381c03b2594defa6a7cc62.nq.gz
│   ├── 21244731f72e2d062f127f50aec320b9cd55036a.nq.gz
│   ├── 21deae6850f6747a8d9394b3b28266b85d55e7b6.nq.gz
│   ├── 2363fe29efff298bff1e68a1f52bab77fd4ec74c.nq.gz
│   ├── 247007834a08672de65d7a3c91c871bd56da7bc3.nq.gz
│   ├── 27bee23001e947b56c4b3d5a6346280cafac5fa9.nq.gz
│   ├── 29835e3d7c8699fd8fdff01c9c9f823096a3d2e3.nq.gz
│   ├── 29b3974e3225cc718cfcbcf988b7d409b9825374.nq.gz
│   ├── 2a870e8cbe804c2c20b5c62dc7f8b13527ca8f38.nq.gz
│   ├── 2aa5b4e0ec16f70d222f1f76ec32cd3c62394136.nq.gz
│   ├── 2afab2e9d7c1dcec73db0da7b3901d024f581c5d.nq.gz
│   ├── 2d74c58f248790e34e482eb07e20ec6c753c9d2d.nq.gz
│   ├── 311ffb267a0839ccfab87b27ad816672ca864505.nq.gz
│   ├── 335876583e1e75a388af7f4f2949002d8527707e.nq.gz
│   ├── 3b722835c9df54dc086282ca37e91d9910518fce.nq.gz
│   ├── 3bd30e1191c9686f4416c6efbb8506f587272c0f.nq.gz
│   ├── 3ef69f6cb2b96e4f187d11efe5b6a0552f7156b9.nq.gz
│   ├── 3f9cba40eb39f5bac143b069891be7242a966271.nq.gz
│   ├── 4000a94b648975db2e186a749c79dd924a1b3ed6.nq.gz
│   ├── 43065df6c94286aaa62ec0925a81dcfb0021563b.nq.gz
│   ├── 496b484a66f1d9726f004e4b7b2072428438bf56.nq.gz
│   ├── 49c2efcfe2b36365cb9e1ba44a57418de5af6c67.nq.gz
│   ├── 4f85b49066fe0bc3c78c74d20ee20154584cb8cf.nq.gz
│   ├── 50ad8ab11810b1319409b1e8268d5f40e794a3c0.nq.gz
│   ├── 52a8be2f187cd8a17af8de4cc971097148a2f8af.nq.gz
│   ├── 566575e52d94764361c0c2b44ecbe999ec935225.nq.gz
│   ├── 571bf38907c13ccf35076f18e6d8aaa3119b9473.nq.gz
│   ├── 5be982317bbf90944f2b15fe98e8c8c2b903a1c6.nq.gz
│   ├── 5e24ec12ec99ec3d4cc907f2b2fa5049cfcbc3ba.nq.gz
│   ├── 609bcf244a2c3a1c3082e410fb510ad41d3a8001.nq.gz
│   ├── 620bb43256ef9c6a1599ba5588a98be5d0f81859.nq.gz
│   ├── 6343d2e696e11c832fc3d9e4676c38a3d03e5fd2.nq.gz
│   ├── 6873b5a8f5fc0de9a59c004a4096b6abaaac9231.nq.gz
│   ├── 6e514be8eee941e31c0f188792b2fedcbc1160e6.nq.gz
│   ├── 6e9b3f730792dc732be3bddc9aa052025e0f17f7.nq.gz
│   ├── 709105ba986f01f03ce00a29219ec5d7fa801082.nq.gz
│   ├── 73dd6325eb8064a5887935b32b80cafc385846c3.nq.gz
│   ├── 79d8e7d50640d8b41714ac583f65e514260fa41f.nq.gz
│   ├── 7aa757579be3d38edb9b06fd22c43ccb58708ac8.nq.gz
│   ├── 7c812c0942e357beccce07763e96d8cbacd9139a.nq.gz
│   ├── 7c81eaba5d550b9bb7534a1ca1440ea0d7fdff9d.nq.gz
│   ├── 7cc09715dc5a22cb76f83ffc01676b549c974f93.nq.gz
│   ├── 7dc9baf762afce234a0612d9f21892a1c7b56cf6.nq.gz
│   ├── 804906f3c2e4dad44a980aad019fada30373a27e.nq.gz
│   ├── 80ac497883dd7a5d0b349d3fd6b48656b13702d5.nq.gz
│   ├── 817cb1ef87a6ba2c49a0630565cf25f5b32c3ea6.nq.gz
│   ├── 859db46b2ffc6c2587938d0591cff1df660c477f.nq.gz
│   ├── 8696be06c1c1980f24817d5c199f6bc4a8879ec1.nq.gz
│   ├── 8884b9f7ca997cfe0add3fd3ec76ae6c2aef3a96.nq.gz
│   ├── 8faf987b03ea7ab8d6c81a604ba057f7b5a17edd.nq.gz
│   ├── 919954b6d9eff8838b8d5b58f43c5634ea13a5f6.nq.gz
│   ├── 9209054848d2f1cba4673b825f5adb75e3717777.nq.gz
│   ├── 97166f131933d6808f8098ba09075c4f973dbe6c.nq.gz
│   ├── 9cd3e50b52bf5e12627a4fbb7a6ac45fddf04cc9.nq.gz
│   ├── 9f2fa42749fa5f5c3eb03786afb4b1d40e50948e.nq.gz
│   ├── a0b4a6366b14ab950f61e01e86b3b65dee45f0db.nq.gz
│   ├── a154404c259a1e95ac6d6b4fc95d51723c739dcc.nq.gz
│   ├── a95193680f0f5a59a3d03e0e13328801b960a982.nq.gz
│   ├── aa687c898a1378e341bd38c93ed60e9e41915f79.nq.gz
│   ├── ad111088954bd5bb4bd875de988814502144e7d4.nq.gz
│   ├── b1c20b699159d0fc377926577f381632b9f700f9.nq.gz
│   ├── b2d4340abdb2f8574589b3ce07632671e220cd6e.nq.gz
│   ├── b425e18d32dc112c3d5520f654b54bf7fc427f24.nq.gz
│   ├── b62c84fb5ed40a743f24dd6c9461c727dddac1bd.nq.gz
│   ├── ba3cfb1ff4f1c2aa34cceffb41107b54503c4c52.nq.gz
│   ├── bb0ca9fce9ce5a8081eea7a121cbd8aae9531b72.nq.gz
│   ├── bff9e8306f196034b5cd6018e4a4017ad5fb6844.nq.gz
│   ├── c02d0b3299f77908c94c98f82ddc52bd6c5f055e.nq.gz
│   ├── c484da657379b381102a7485ae23862a329493b8.nq.gz
│   ├── c488ee983f14126431c251cfe32cffd24f19971c.nq.gz
│   ├── c53505a398ccb59a048970062fc8ea02ca25085e.nq.gz
│   ├── c5943dd0e4e292dcd5b884e95858ad159af104d2.nq.gz
│   ├── c9e8f956972609454c8ec7789e01f7d0760441ca.nq.gz
│   ├── cb1e2dc16c6a2a869af7717df44e689a3efd5bf0.nq.gz
│   ├── cce9dfbbcccf456c91ad0572b259c2f50e92e81a.nq.gz
│   ├── d365d4c0d18acdd8298a76fb5e59f40656e1c795.nq.gz
│   ├── d791ea00fabf6921ac61aeb1587720c02b3ec071.nq.gz
│   ├── d7ed8449bbd3830b6f9cd53409041521cc832209.nq.gz
│   ├── ddb29a0ec92fb996505ac2f15744c73f43fe605b.nq.gz
│   ├── e11951521bc05c9e84cb959f6979250b7a497265.nq.gz
│   ├── e6238d5e24d33507a4a03987237b8af0b02c43f3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e94b92f88cf2db23028cf8f2edc4a03dd7f04e03.nq.gz
│   ├── e964fdcf7964092480d19fc85bfc4427c9b3723e.nq.gz
│   ├── ec0067bb2b2958452cd097bb2b116fd1e45c3471.nq.gz
│   ├── ec1fff4b2c2b945d8463752d8f506473367b8496.nq.gz
│   ├── ee6c35321d5ada8f39387791a2f69829a1d3cb6c.nq.gz
│   ├── effa6d4adad454bff547d033dd9cbcb55e2ea587.nq.gz
│   ├── f0544bb2a8bd836152d1681017f699a5d1f69553.nq.gz
│   ├── f1e182b2fff54f6e5566931a7c32a24ab8cfceaf.nq.gz
│   ├── f3981f09dab5fbb825ebbf606b7ac6aa31f673e0.nq.gz
│   ├── f4f7348e72507b12347f4edf21dba967444c8c83.nq.gz
│   ├── f7e4d68307094e2e9096ff0d0d2c55d320833e4f.nq.gz
│   ├── fa60acd1da3dd8c2babda59a45d276b3e01b39f5.nq.gz
│   └── fb633d879c1d2ed02fa24e45109f03ac5a901662.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 121 files
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

## Source repository

[pallets/jinja](https://github.com/pallets/jinja)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
