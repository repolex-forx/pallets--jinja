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
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 15206881c006c79667fe5154fe80c01c65410679
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│   │   ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│   │   ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
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
│   │   ├── b08cd4bc64bb980df86ed2876978ae5735572280
│   │   │   └── chunk-001.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd4a8b5466d8790540c181590b14db4d4d889d57
│   │   │   └── chunk-001.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   ├── lsp
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 15206881c006c79667fe5154fe80c01c65410679.nq.gz
│   │   ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│   │   ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│   │   ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
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
│   │   ├── b08cd4bc64bb980df86ed2876978ae5735572280.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1.nq.gz
│   │   ├── dd4a8b5466d8790540c181590b14db4d4d889d57.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   └── repolex
│       ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│       ├── 15206881c006c79667fe5154fe80c01c65410679
│       │   └── chunk-001.nq.gz
│       ├── 2856c211fab4a1fb466345bae52e3373caed7fcf.nq.gz
│       ├── 30b39cd4d924dfed059a73960a45181752e0b5de.nq.gz
│       ├── 30c2d660dc1e6a80e8485ac7a410336148e24389.nq.gz
│       ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
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
│       ├── b08cd4bc64bb980df86ed2876978ae5735572280
│       │   └── chunk-001.nq.gz
│       ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│       ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│       ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│       ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│       ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│       ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│       ├── d9de4bb215fd1cc8092a410fb834c7c4060b1fc1
│       │   └── chunk-001.nq.gz
│       ├── dd4a8b5466d8790540c181590b14db4d4d889d57
│       │   └── chunk-001.nq.gz
│       └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
└── blob
    ├── 0057d6eabade5e964e6ef0e3ac8ed2dd67494b03.nq.gz
    ├── 00eab115e1c19a86bb1ec64b7cf626fbf413e126.nq.gz
    ├── 019d804f3d4c7f3e4e945feb4d83b883de43bab3.nq.gz
    ├── 01a7d0d787bec234c40fe1f541db234ab1a50348.nq.gz
    ├── 01e530dc89432237bfda5bbb204e5ac6d358ff54.nq.gz
    ├── 02c74a86b27d303419c1a308e1bcbaa63e19d61e.nq.gz
    ├── 0469d04e432af8acdab390d9848817716baedd5d.nq.gz
    ├── 049ab3b2d6f00cbdaba7a5580c80e696cd2c2a70.nq.gz
    ├── 04ac784434fc1d2088c53625c424130be7f6bfcf.nq.gz
    ├── 04c921d24745e63fc5019842004bbe7a9e7ad208.nq.gz
    ├── 056ca0d9479a9097a342b412e57f80407c7c0715.nq.gz
    ├── 0597b7a80b46f63c4067f6190c27fd1b3367e2ed.nq.gz
    ├── 05d1207d40722480f2e0d5341dd183ef5bd9652d.nq.gz
    ├── 060b19efee615b2ac57f3c08f8ecb3cfb6f38f6a.nq.gz
    ├── 06a339be54c9493acb737f82fbf9abb90aa271fd.nq.gz
    ├── 06d74148eccea79d1f5a0ca2fb76ecc246f87d62.nq.gz
    ├── 06e799ec6ba345cc047411893d94762708a5913a.nq.gz
    ├── 073277ba668aae883ced98465d93b0669bc843dc.nq.gz
    ├── 0734a84f73d0ddb735a004c9e0416e018a7d50bd.nq.gz
    ├── 080e527cabf33b0422f6b8e5b172c17d7c039d39.nq.gz
    ├── 082ebe8f221d4e7e980e4d321c0a0c5da033b124.nq.gz
    ├── 08a1785538e0a5c3c3c14fd9164be6d671b27d82.nq.gz
    ├── 08c22f4f13371376c380d1a3223121aa7f0723cd.nq.gz
    ├── 09119e2ae550e7001a64be0c7150837fb39af26d.nq.gz
    ├── 0a525e7ac97b74bdaa3f8e8d62f80f087b4a7fe0.nq.gz
    ├── 0a67388b40ffaacd87d17ccdd3bf92381368fbe0.nq.gz
    ├── 0a839517dfa084e8a21670750335e526ebfc1f66.nq.gz
    ├── 0aa46ee2f864c218019156cf0cd7d98fb97be284.nq.gz
    ├── 0adc3d4dbcbb881910bfd90214534449fafddcb3.nq.gz
    ├── 0b48ca2586949702859564a1133ab9be6f85b49d.nq.gz
    ├── 0b4fc12d3479772f15c20ad394aab575fd2a4975.nq.gz
    ├── 0b6b6b3aaf239cd2f52c81035550b86388d6ea79.nq.gz
    ├── 0ba46451d08473e83ff917c33a55666eb98e92da.nq.gz
    ├── 0ba86e768909a99798ceee69fbba9fb0d6d599e1.nq.gz
    ├── 0bc9ea4e8b4fd953035f89dac7a7c326b49bccd3.nq.gz
    ├── 0bf2003e30e2a24a54640359bb04f3e98b26e3f6.nq.gz
    ├── 0c20d4da7d3c29e36bf8c7fb36c747b069b6f6e5.nq.gz
    ├── 0c262dc4b85bb6244c08370fb41465e44ff03bee.nq.gz
    ├── 0c307ecbc6662c200583ecbfedd4e5d3945babdb.nq.gz
    ├── 0c496317ca99f1addea3cf7ae1e47fe0661f6af6.nq.gz
    ├── 0c5b3657c8538e47be88b49daf91600a7936d9f6.nq.gz
    ├── 0c8e30ee8fad9ff979fd07b0e90d8e28b864b12a.nq.gz
    ├── 0c907ae3f12a64e21087a9a591b1407b780b1bb1.nq.gz
    ├── 0d5a68fef62166b14feb892020abba9dc626be6d.nq.gz
    ├── 0d608a36e7247935e731df425d6625f73304e5a0.nq.gz
    ├── 0dae2173f22625a42d5443638377c90bb48d5717.nq.gz
    ├── 0db4653e9f8208136b819ef14548b97b7557c42d.nq.gz
    ├── 0e3bf5a214a4be844bdfbe526cbeab183208125e.nq.gz
    ├── 0e8dc5c0385d3baffffb100353e70d7183b482e9.nq.gz
    ├── 0eaf72149965d12be441f011c2e76c047a47adef.nq.gz
    ├── 0ec997fb4993ed6bf9564835f316a9cb7469089e.nq.gz
    ├── 0f30d5477f85f207e23628a30b97f53bd9e9e1a3.nq.gz
    ├── 0f5d2c6dbb031713d434dbf33d96d398ef5098de.nq.gz
    ├── 0f5fed5536599490295ad9200b4ef8267c3cbb8c.nq.gz
    ├── 0f93f7b71febd8e794c5968c3263e3a5af1c14c0.nq.gz
    ├── 0fa2de7f368e76fe362bab03f00c64dda81cc761.nq.gz
    ├── 0fc6e5be87ab8273f6056ddfede07e1be28f1495.nq.gz
    ├── 0ff0d0471e46613573a98a76101b3f0bc997f382.nq.gz
    ├── 10145a264342b7888ec6accfedc4f2808fb67a0e.nq.gz
    ├── 1062ebe444d9799bccd0af0f1931839635a0e1f3.nq.gz
    ├── 107659b903b3586eee9ecc5ab10c445edfb1dad7.nq.gz
    ├── 109f4441f8e05b3bc6ddd32873b81abea868a460.nq.gz
    ├── 10c7e56e8371bbadd1c2c0d8fc18b5554e49d220.nq.gz
    ├── 1161b7f4a47d444963fdc77ae3c92187b3354430.nq.gz
    ├── 11d9978f87e3bf5871091f8fefd200ab86a2f99f.nq.gz
    ├── 11efd1ed15832d51acef200d1ce93efc57297664.nq.gz
    ├── 120c6e76ad8fb07f1fa65a11da488ffeb811efd1.nq.gz
    ├── 1222d0250583096bdfbf8309d47f9b171ff0d53b.nq.gz
    ├── 1229ba4275a0549e01dd6e7b10e1ccf17f17389f.nq.gz
    ├── 12c589076b097bffa852571a9e041436731c3418.nq.gz
    ├── 12e09fffaff3f4d0f9211b9efb246cb246ff5b50.nq.gz
    ├── 1369081807950ed36239fe2ef2f8e28321cae0f2.nq.gz
    ├── 13e303b7131553a882decdbd026290084695c96d.nq.gz
    ├── 1483ce6e8bca3be0e7fcacfeba0d019c7ffa803a.nq.gz
    ├── 154810fc99a97b7f811bbb95a046fdb852a06c89.nq.gz
    ├── 154cf44c96df86d1e14f685e9f913025c9a0ebbc.nq.gz
    ├── 157720ff958bf00852a11774ba8b3fc76bb16b39.nq.gz
    ├── 15e13b6f2e6acf30ac115d942d4c377868d3ffbe.nq.gz
    ├── 162cc6d4d73fc4d92921e94054421db0d774a314.nq.gz
    ├── 17306fdd1ccaf584386de33c92c82cd324226893.nq.gz
    ├── 17c6aaba570742652f70bf1e7bf1a576c9d256ae.nq.gz
    ├── 17e6bf1d295f4b57cd20048af03bbbe912953809.nq.gz
    ├── 17f06eea272d31229f9feca43e15eede8aaaff94.nq.gz
    ├── 182c0619ddc8ce71358d237d179e1cb83414a5a4.nq.gz
    ├── 1831beb84b17591a12265bc605467401ff5d5420.nq.gz
    ├── 185d33246e395cc9a905bf7a05e5abdf1a1bbe5e.nq.gz
    ├── 1875711df49143b38b880111ef2cbb4ae01c979f.nq.gz
    ├── 18914a58fd3620b43ad98afd0fcb0a5758d764e9.nq.gz
    ├── 194390a9e9756706acb79a3eb1e25da72442bf76.nq.gz
    ├── 1961e9f12684a23a0cabd04ab08b18f5935bf819.nq.gz
    ├── 1978c64104a89072e1b936bb0a69a9d14fbc1251.nq.gz
    ├── 19902ff8583d2771cf6549855d2ee2df79488bc0.nq.gz
    ├── 1a08700b08124791b69ccc1e40f6e0a1499dfbd4.nq.gz
    ├── 1a423a3eac16ac550e8e4008d7f5d79401b50e0f.nq.gz
    ├── 1a4f3892cef1a53632476933f2ce2d86fc31b10a.nq.gz
    ├── 1a59e37032d51db5e8f75914334e6650f26ce4e9.nq.gz
    ├── 1af7ac88a7c9aeea80b979982818addc5444612f.nq.gz
    ├── 1b12eb4dc17827060f2e70bac957b3510641fac7.nq.gz
    ├── 1b163ff5a0f10ed890b62e275a8d4b6cfeb176b0.nq.gz
    ├── 1bd96c41e98cfd2066c35707f711edd27fe87a9e.nq.gz
    ├── 1bde05694786aba2990c56a6d8678b8cc01eac4c.nq.gz
    ├── 1c0421878aa935f4b77fdc8f2fc753a0f6ded640.nq.gz
    ├── 1c4ad3e49631164bed1f0546b7e99d2254e5f0aa.nq.gz
    ├── 1d25a2b9852e8ef9ba3e10f2134c286e753f0716.nq.gz
    ├── 1d3be0bed08d710f2a93079d62552d63fb09b627.nq.gz
    ├── 1d3be69a9656d4d3c90bd487dc4c59c53028a6ca.nq.gz
    ├── 1ddf05ee55a286c0990ff20d378467aa1400b7ee.nq.gz
    ├── 1df6bfedabc800baa804eed0afefadbd979d9d7a.nq.gz
    ├── 1e2236c3a5cead1b6c53c021ec35546d5184ca87.nq.gz
    ├── 1e248d4d755d58f2853b3d2b9ffab262ba2580c9.nq.gz
    ├── 1ea7d495ef556a8c517c658b9a125fe005050fc2.nq.gz
    ├── 1ee6e2758a297bbe5fb026258299ef9980c2970f.nq.gz
    ├── 1f044954a02933bcec2277fcdd575821bc18a99a.nq.gz
    ├── 1f10ef68141971c873c5a04a93cfc97b7a93b4ea.nq.gz
    ├── 1f5e12a721c71af9fd2b00e719ec04f89cf783b4.nq.gz
    ├── 1f97e37945ca3968644a6f4586836abd8aa0e7d8.nq.gz
    ├── 1fb8ee63bf284ba3adbba3788b359dd033bfc44f.nq.gz
    ├── 2042fccf5c10a8d719b557400bf74fd868b875b2.nq.gz
    ├── 20de3695b7faef5a60381c03b2594defa6a7cc62.nq.gz
    ├── 21244731f72e2d062f127f50aec320b9cd55036a.nq.gz
    ├── 2171d7c154504c7029e270473893b49bbacb6612.nq.gz
    └── 218fbace16e64f7dc7cf055631d65539869995af.nq.gz

20 directories, 200 files
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
