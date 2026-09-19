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
├── aggregate
│   ├── ast
│   │   ├── 09f8b2b2d1cfca7e5b231cf3773bef2a952b6312
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 1164cc361778a501317529aafa67b1180a4a15cd
│   │   │   └── chunk-001.nq.gz
│   │   ├── 15206881c006c79667fe5154fe80c01c65410679
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│   │   ├── 2a48dd898d72f1a119ee923996e70aa43da04ea4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│   │   ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│   │   ├── 3b3e16fc18fca4de0bd5fa714374767e8d124c27
│   │   │   └── chunk-001.nq.gz
│   │   ├── 417f822196f66155e8c121e5229cc12a6b02ce14
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│   │   ├── 5962edeb271d93687eb93f32d53ffe53f86871e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 70c2d7976bcd277d26c8d901e9d72db7a1796844
│   │   │   └── chunk-001.nq.gz
│   │   ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── 7f66a58a967ec11b56c76d37782990d9e72353ab
│   │   │   └── chunk-001.nq.gz
│   │   ├── 800ac7f623a21e7549c7afd6aa7c340c0713eb3f.nq.gz
│   │   ├── 84c0e2cf4e58655032930aeb200b979e3c6f5f32
│   │   │   └── chunk-001.nq.gz
│   │   ├── 877f6e51be8e1765b06d911cfaa9033775f051d1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│   │   ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│   │   ├── ac8d8d69fe3e0eb81251867218c67193a086e427
│   │   │   └── chunk-001.nq.gz
│   │   ├── b08cd4bc64bb980df86ed2876978ae5735572280
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7d12b6b1597ea5d38de8dac2013749be266edd0
│   │   │   └── chunk-001.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   ├── d77a91b1cba05d9dc78d4b03d312fcff3ca91ebb
│   │   │   └── chunk-001.nq.gz
│   │   ├── d78a1b079cd985eea7d636f79124ab4fc44cb538
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd4a8b5466d8790540c181590b14db4d4d889d57
│   │   │   └── chunk-001.nq.gz
│   │   ├── df8296af7eb07d56353de95146370a3c6614110e
│   │   │   └── chunk-001.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   ├── lsp
│   │   ├── 09f8b2b2d1cfca7e5b231cf3773bef2a952b6312.nq.gz
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 1164cc361778a501317529aafa67b1180a4a15cd.nq.gz
│   │   ├── 15206881c006c79667fe5154fe80c01c65410679.nq.gz
│   │   ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│   │   ├── 2a48dd898d72f1a119ee923996e70aa43da04ea4.nq.gz
│   │   ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│   │   ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│   │   ├── 3b3e16fc18fca4de0bd5fa714374767e8d124c27.nq.gz
│   │   ├── 417f822196f66155e8c121e5229cc12a6b02ce14.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│   │   ├── 5962edeb271d93687eb93f32d53ffe53f86871e0.nq.gz
│   │   ├── 70c2d7976bcd277d26c8d901e9d72db7a1796844.nq.gz
│   │   ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── 7f66a58a967ec11b56c76d37782990d9e72353ab.nq.gz
│   │   ├── 800ac7f623a21e7549c7afd6aa7c340c0713eb3f.nq.gz
│   │   ├── 84c0e2cf4e58655032930aeb200b979e3c6f5f32.nq.gz
│   │   ├── 877f6e51be8e1765b06d911cfaa9033775f051d1.nq.gz
│   │   ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│   │   ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│   │   ├── ac8d8d69fe3e0eb81251867218c67193a086e427.nq.gz
│   │   ├── b08cd4bc64bb980df86ed2876978ae5735572280.nq.gz
│   │   ├── b7d12b6b1597ea5d38de8dac2013749be266edd0.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   ├── d77a91b1cba05d9dc78d4b03d312fcff3ca91ebb.nq.gz
│   │   ├── d78a1b079cd985eea7d636f79124ab4fc44cb538.nq.gz
│   │   ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1.nq.gz
│   │   ├── dd4a8b5466d8790540c181590b14db4d4d889d57.nq.gz
│   │   ├── df8296af7eb07d56353de95146370a3c6614110e.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   └── repolex
│       ├── 09f8b2b2d1cfca7e5b231cf3773bef2a952b6312
│       │   └── chunk-001.nq.gz
│       ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│       ├── 1164cc361778a501317529aafa67b1180a4a15cd
│       │   └── chunk-001.nq.gz
│       ├── 15206881c006c79667fe5154fe80c01c65410679
│       │   └── chunk-001.nq.gz
│       ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│       ├── 2a48dd898d72f1a119ee923996e70aa43da04ea4
│       │   └── chunk-001.nq.gz
│       ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│       ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│       ├── 3b3e16fc18fca4de0bd5fa714374767e8d124c27
│       │   └── chunk-001.nq.gz
│       ├── 417f822196f66155e8c121e5229cc12a6b02ce14
│       │   └── chunk-001.nq.gz
│       ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│       ├── 5962edeb271d93687eb93f32d53ffe53f86871e0
│       │   └── chunk-001.nq.gz
│       ├── 70c2d7976bcd277d26c8d901e9d72db7a1796844
│       │   └── chunk-001.nq.gz
│       ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│       ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│       ├── 7f66a58a967ec11b56c76d37782990d9e72353ab
│       │   └── chunk-001.nq.gz
│       ├── 800ac7f623a21e7549c7afd6aa7c340c0713eb3f.nq.gz
│       ├── 84c0e2cf4e58655032930aeb200b979e3c6f5f32
│       │   └── chunk-001.nq.gz
│       ├── 877f6e51be8e1765b06d911cfaa9033775f051d1
│       │   └── chunk-001.nq.gz
│       ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│       ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│       ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│       ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│       ├── ac8d8d69fe3e0eb81251867218c67193a086e427
│       │   └── chunk-001.nq.gz
│       ├── b08cd4bc64bb980df86ed2876978ae5735572280
│       │   └── chunk-001.nq.gz
│       ├── b7d12b6b1597ea5d38de8dac2013749be266edd0
│       │   └── chunk-001.nq.gz
│       ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│       ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│       ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│       ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│       ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│       ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│       ├── d77a91b1cba05d9dc78d4b03d312fcff3ca91ebb
│       │   └── chunk-001.nq.gz
│       ├── d78a1b079cd985eea7d636f79124ab4fc44cb538
│       │   └── chunk-001.nq.gz
│       ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1
│       │   └── chunk-001.nq.gz
│       ├── dd4a8b5466d8790540c181590b14db4d4d889d57
│       │   └── chunk-001.nq.gz
│       ├── df8296af7eb07d56353de95146370a3c6614110e
│       │   └── chunk-001.nq.gz
│       └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
└── blob
    ├── 0057d6eabade5e964e6ef0e3ac8ed2dd67494b03.nq.gz
    ├── 00656b38d31972b7e8806e3f96bfab8f166e91c3.nq.gz
    ├── 007f92916b1b9e6f466b0684c6839885d0eb413d.nq.gz
    ├── 00d5f03ca610252a176872f7b1b0cbd431f0609e.nq.gz
    ├── 00eab115e1c19a86bb1ec64b7cf626fbf413e126.nq.gz
    ├── 00f1f59f645f22fd2b24ca11fb8cd5f2c2ae7356.nq.gz
    ├── 019d804f3d4c7f3e4e945feb4d83b883de43bab3.nq.gz
    ├── 01a7d0d787bec234c40fe1f541db234ab1a50348.nq.gz
    ├── 01e530dc89432237bfda5bbb204e5ac6d358ff54.nq.gz
    ├── 027538579199e3a0986ce3398e4608bcf998891c.nq.gz
    ├── 02c74a86b27d303419c1a308e1bcbaa63e19d61e.nq.gz
    ├── 02dd8e85ef404148e34587f1fab748ca31085713.nq.gz
    ├── 02de4ee71b36035c8c4055b00ff36ad6dd2e43d5.nq.gz
    ├── 03402f043c0e4114d4c810726903d1ad30b7fb71.nq.gz
    ├── 03e303f14401e470971d2891ba06133a3ca96314.nq.gz
    ├── 045a3a88dca30be63aeb97042a3f2d8e09521786.nq.gz
    ├── 0469d04e432af8acdab390d9848817716baedd5d.nq.gz
    ├── 049ab3b2d6f00cbdaba7a5580c80e696cd2c2a70.nq.gz
    ├── 04ac784434fc1d2088c53625c424130be7f6bfcf.nq.gz
    ├── 04c921d24745e63fc5019842004bbe7a9e7ad208.nq.gz
    ├── 054c9010480dab6d4a0fe068bbd11f892a8e3d8b.nq.gz
    ├── 056ca0d9479a9097a342b412e57f80407c7c0715.nq.gz
    ├── 0597b7a80b46f63c4067f6190c27fd1b3367e2ed.nq.gz
    ├── 05d1207d40722480f2e0d5341dd183ef5bd9652d.nq.gz
    ├── 060b19efee615b2ac57f3c08f8ecb3cfb6f38f6a.nq.gz
    ├── 06a339be54c9493acb737f82fbf9abb90aa271fd.nq.gz
    ├── 06d74148eccea79d1f5a0ca2fb76ecc246f87d62.nq.gz
    ├── 06e799ec6ba345cc047411893d94762708a5913a.nq.gz
    ├── 0730e3ac05313104e9aa0b5e577ade61b9656682.nq.gz
    ├── 073277ba668aae883ced98465d93b0669bc843dc.nq.gz
    ├── 0734a84f73d0ddb735a004c9e0416e018a7d50bd.nq.gz
    ├── 075bcc6a86dc7c511a82880d3da8dd2f6c5e1d96.nq.gz
    ├── 0762e4d87c30e6ded054a429b5892e3771881a0c.nq.gz
    ├── 07c21f1a8bd26a99f234e1221e4603c1035439f2.nq.gz
    ├── 07cfba26499e36864d833f78a867c869ac6c95ee.nq.gz
    ├── 07f849204a2ce51d265d5f96075a6fa87714eabc.nq.gz
    ├── 080e527cabf33b0422f6b8e5b172c17d7c039d39.nq.gz
    ├── 082ebe8f221d4e7e980e4d321c0a0c5da033b124.nq.gz
    ├── 08a1785538e0a5c3c3c14fd9164be6d671b27d82.nq.gz
    ├── 08aaf4b5e92a15f404338e38574a92ba809265da.nq.gz
    ├── 08c22f4f13371376c380d1a3223121aa7f0723cd.nq.gz
    ├── 09119e2ae550e7001a64be0c7150837fb39af26d.nq.gz
    ├── 0a525e7ac97b74bdaa3f8e8d62f80f087b4a7fe0.nq.gz
    ├── 0a67388b40ffaacd87d17ccdd3bf92381368fbe0.nq.gz
    ├── 0a839517dfa084e8a21670750335e526ebfc1f66.nq.gz
    ├── 0aa46ee2f864c218019156cf0cd7d98fb97be284.nq.gz
    ├── 0aad12c81860e9fe73e876b84431ddd833cd24b6.nq.gz
    ├── 0ad95383bfb7f21bf034224b0fd81d72e85280b8.nq.gz
    ├── 0adc3d4dbcbb881910bfd90214534449fafddcb3.nq.gz
    ├── 0aec78ae48f54a8f8c274df20fd7a2a337ea6cc1.nq.gz
    ├── 0b48ca2586949702859564a1133ab9be6f85b49d.nq.gz
    ├── 0b4fc12d3479772f15c20ad394aab575fd2a4975.nq.gz
    ├── 0b529a191b4f75ca9a695095fddf063f260190b5.nq.gz
    ├── 0b6b6b3aaf239cd2f52c81035550b86388d6ea79.nq.gz
    ├── 0ba46451d08473e83ff917c33a55666eb98e92da.nq.gz
    ├── 0ba86e768909a99798ceee69fbba9fb0d6d599e1.nq.gz
    ├── 0bc9ea4e8b4fd953035f89dac7a7c326b49bccd3.nq.gz
    ├── 0bf2003e30e2a24a54640359bb04f3e98b26e3f6.nq.gz
    ├── 0bf74c9459be00c325b12be338f4925bb6bfcfe2.nq.gz
    ├── 0c20d4da7d3c29e36bf8c7fb36c747b069b6f6e5.nq.gz
    ├── 0c262dc4b85bb6244c08370fb41465e44ff03bee.nq.gz
    ├── 0c307ecbc6662c200583ecbfedd4e5d3945babdb.nq.gz
    ├── 0c363636f68da8d2b2a28a0fded9c59066f1ed00.nq.gz
    ├── 0c496317ca99f1addea3cf7ae1e47fe0661f6af6.nq.gz
    ├── 0c5b3657c8538e47be88b49daf91600a7936d9f6.nq.gz
    ├── 0c8e30ee8fad9ff979fd07b0e90d8e28b864b12a.nq.gz
    ├── 0c907ae3f12a64e21087a9a591b1407b780b1bb1.nq.gz
    ├── 0cade7a3503d10c563f90e084e2b701c4fb1b8bc.nq.gz
    ├── 0ce916df497fd2605dd3ceef81839c07a2c19e02.nq.gz
    ├── 0d5a68fef62166b14feb892020abba9dc626be6d.nq.gz
    ├── 0d608a36e7247935e731df425d6625f73304e5a0.nq.gz
    ├── 0d6db7c5edce27d278652270d9af54904bf151a0.nq.gz
    ├── 0dae2173f22625a42d5443638377c90bb48d5717.nq.gz
    ├── 0db4653e9f8208136b819ef14548b97b7557c42d.nq.gz
    ├── 0dbc2bc86082435c86f26ce85fe36451fc642416.nq.gz
    ├── 0dead3bfadba27d77a82645046dd47a09126a08f.nq.gz
    ├── 0e342aaad86334e020eef4705122495bc8d60f5b.nq.gz
    ├── 0e3bf5a214a4be844bdfbe526cbeab183208125e.nq.gz
    ├── 0e8dc5c0385d3baffffb100353e70d7183b482e9.nq.gz
    ├── 0eaf72149965d12be441f011c2e76c047a47adef.nq.gz
    ├── 0ec997fb4993ed6bf9564835f316a9cb7469089e.nq.gz
    ├── 0f30d5477f85f207e23628a30b97f53bd9e9e1a3.nq.gz
    ├── 0f5d2c6dbb031713d434dbf33d96d398ef5098de.nq.gz
    ├── 0f5fed5536599490295ad9200b4ef8267c3cbb8c.nq.gz
    ├── 0f93f7b71febd8e794c5968c3263e3a5af1c14c0.nq.gz
    └── 0fa2de7f368e76fe362bab03f00c64dda81cc761.nq.gz

44 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
