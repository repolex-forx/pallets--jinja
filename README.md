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
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   ├── lsp
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   └── repolex
│       ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│       ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│       ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│       ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│       ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│       ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│       ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│       └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
└── blob
    ├── 019d804f3d4c7f3e4e945feb4d83b883de43bab3.nq.gz
    ├── 01a7d0d787bec234c40fe1f541db234ab1a50348.nq.gz
    ├── 01e530dc89432237bfda5bbb204e5ac6d358ff54.nq.gz
    ├── 0469d04e432af8acdab390d9848817716baedd5d.nq.gz
    ├── 049ab3b2d6f00cbdaba7a5580c80e696cd2c2a70.nq.gz
    ├── 04ac784434fc1d2088c53625c424130be7f6bfcf.nq.gz
    ├── 0597b7a80b46f63c4067f6190c27fd1b3367e2ed.nq.gz
    ├── 05d1207d40722480f2e0d5341dd183ef5bd9652d.nq.gz
    ├── 060b19efee615b2ac57f3c08f8ecb3cfb6f38f6a.nq.gz
    ├── 06e799ec6ba345cc047411893d94762708a5913a.nq.gz
    ├── 0734a84f73d0ddb735a004c9e0416e018a7d50bd.nq.gz
    ├── 080e527cabf33b0422f6b8e5b172c17d7c039d39.nq.gz
    ├── 08c22f4f13371376c380d1a3223121aa7f0723cd.nq.gz
    ├── 0aa46ee2f864c218019156cf0cd7d98fb97be284.nq.gz
    ├── 0adc3d4dbcbb881910bfd90214534449fafddcb3.nq.gz
    ├── 0b6b6b3aaf239cd2f52c81035550b86388d6ea79.nq.gz
    ├── 0bc9ea4e8b4fd953035f89dac7a7c326b49bccd3.nq.gz
    ├── 0bf2003e30e2a24a54640359bb04f3e98b26e3f6.nq.gz
    ├── 0c262dc4b85bb6244c08370fb41465e44ff03bee.nq.gz
    ├── 0c307ecbc6662c200583ecbfedd4e5d3945babdb.nq.gz
    ├── 0c496317ca99f1addea3cf7ae1e47fe0661f6af6.nq.gz
    ├── 0c5b3657c8538e47be88b49daf91600a7936d9f6.nq.gz
    ├── 0c8e30ee8fad9ff979fd07b0e90d8e28b864b12a.nq.gz
    ├── 0c907ae3f12a64e21087a9a591b1407b780b1bb1.nq.gz
    ├── 0dae2173f22625a42d5443638377c90bb48d5717.nq.gz
    ├── 0eaf72149965d12be441f011c2e76c047a47adef.nq.gz
    ├── 0f30d5477f85f207e23628a30b97f53bd9e9e1a3.nq.gz
    ├── 0f5d2c6dbb031713d434dbf33d96d398ef5098de.nq.gz
    ├── 0f93f7b71febd8e794c5968c3263e3a5af1c14c0.nq.gz
    ├── 10145a264342b7888ec6accfedc4f2808fb67a0e.nq.gz
    ├── 107659b903b3586eee9ecc5ab10c445edfb1dad7.nq.gz
    ├── 109f4441f8e05b3bc6ddd32873b81abea868a460.nq.gz
    ├── 10c7e56e8371bbadd1c2c0d8fc18b5554e49d220.nq.gz
    ├── 11d9978f87e3bf5871091f8fefd200ab86a2f99f.nq.gz
    ├── 11efd1ed15832d51acef200d1ce93efc57297664.nq.gz
    ├── 1222d0250583096bdfbf8309d47f9b171ff0d53b.nq.gz
    ├── 12c589076b097bffa852571a9e041436731c3418.nq.gz
    ├── 154cf44c96df86d1e14f685e9f913025c9a0ebbc.nq.gz
    ├── 157720ff958bf00852a11774ba8b3fc76bb16b39.nq.gz
    ├── 15e13b6f2e6acf30ac115d942d4c377868d3ffbe.nq.gz
    ├── 162cc6d4d73fc4d92921e94054421db0d774a314.nq.gz
    ├── 17f06eea272d31229f9feca43e15eede8aaaff94.nq.gz
    ├── 1875711df49143b38b880111ef2cbb4ae01c979f.nq.gz
    ├── 194390a9e9756706acb79a3eb1e25da72442bf76.nq.gz
    ├── 1a08700b08124791b69ccc1e40f6e0a1499dfbd4.nq.gz
    ├── 1af7ac88a7c9aeea80b979982818addc5444612f.nq.gz
    ├── 1bde05694786aba2990c56a6d8678b8cc01eac4c.nq.gz
    ├── 1c0421878aa935f4b77fdc8f2fc753a0f6ded640.nq.gz
    ├── 1c4ad3e49631164bed1f0546b7e99d2254e5f0aa.nq.gz
    ├── 1d25a2b9852e8ef9ba3e10f2134c286e753f0716.nq.gz
    ├── 1d3be69a9656d4d3c90bd487dc4c59c53028a6ca.nq.gz
    ├── 1ddf05ee55a286c0990ff20d378467aa1400b7ee.nq.gz
    ├── 1df6bfedabc800baa804eed0afefadbd979d9d7a.nq.gz
    ├── 1e248d4d755d58f2853b3d2b9ffab262ba2580c9.nq.gz
    ├── 1ea7d495ef556a8c517c658b9a125fe005050fc2.nq.gz
    ├── 1ee6e2758a297bbe5fb026258299ef9980c2970f.nq.gz
    ├── 1f044954a02933bcec2277fcdd575821bc18a99a.nq.gz
    ├── 1fb8ee63bf284ba3adbba3788b359dd033bfc44f.nq.gz
    ├── 2042fccf5c10a8d719b557400bf74fd868b875b2.nq.gz
    ├── 20de3695b7faef5a60381c03b2594defa6a7cc62.nq.gz
    ├── 21244731f72e2d062f127f50aec320b9cd55036a.nq.gz
    ├── 218fe3339b3c747d3f7d208d34ad005095ff0ea3.nq.gz
    ├── 21deae6850f6747a8d9394b3b28266b85d55e7b6.nq.gz
    ├── 21eb77651bdcbc2327301d61a910d62477cda6a7.nq.gz
    ├── 224d5449d138e75f4f3c25d70cb8f1ea54ccd047.nq.gz
    ├── 22ae823ae9f9a64d31be644f70e18ad25858c72a.nq.gz
    ├── 2363fe29efff298bff1e68a1f52bab77fd4ec74c.nq.gz
    ├── 247007834a08672de65d7a3c91c871bd56da7bc3.nq.gz
    ├── 25dcb0b090ec59ebaf6c2515c95617fc135b0ac2.nq.gz
    ├── 267ddddaa03478ed77d640c011b8f2c0d6641d04.nq.gz
    ├── 26dd4da532aef0c2c6722113c557de70b72266dd.nq.gz
    ├── 2769e96ade5505d4fe01ed0802b497925a543e9b.nq.gz
    ├── 27bee23001e947b56c4b3d5a6346280cafac5fa9.nq.gz
    ├── 27bf519c1ba868c635eea3a42f47858f66107388.nq.gz
    ├── 285333fd5b89d4c1472249ad3dd63cd656734345.nq.gz
    ├── 28f32781d9e7c0149a7fd5b43edb3d44d528fb60.nq.gz
    ├── 29312d3e3d35dd391e3df78d410d0ec4fc3535db.nq.gz
    ├── 294fef1d66e2fe1af25e4719dde8291c10fe3e2c.nq.gz
    ├── 2970cb5c182a07b2695ece949e80c366b56c3eff.nq.gz
    ├── 29835e3d7c8699fd8fdff01c9c9f823096a3d2e3.nq.gz
    ├── 29b3974e3225cc718cfcbcf988b7d409b9825374.nq.gz
    ├── 2a870e8cbe804c2c20b5c62dc7f8b13527ca8f38.nq.gz
    ├── 2aa5b4e0ec16f70d222f1f76ec32cd3c62394136.nq.gz
    ├── 2afab2e9d7c1dcec73db0da7b3901d024f581c5d.nq.gz
    ├── 2b8d0661ed145baac8534976eb1292a2035a89e0.nq.gz
    ├── 2c57616ec11083b4b6b54b902d00a03c18dd190b.nq.gz
    ├── 2cfad55f9773f712c7fb82419c2d2d3a274bcc9c.nq.gz
    ├── 2d4ab9add849a874fe5b6620966848b563bacfc2.nq.gz
    ├── 2d74c58f248790e34e482eb07e20ec6c753c9d2d.nq.gz
    ├── 2dbd5693edd6d204110dd71ec131c41f2a1c6b3b.nq.gz
    ├── 2df94d41511775fdb5e48621ff7499c1c3b45e46.nq.gz
    ├── 2eac35d5c35531b2b63e3fbdcae4bfd02dd89240.nq.gz
    ├── 2ed3ac64651c860462dbe82f8cf4907c21dd45ad.nq.gz
    ├── 2f177473d2d04e836e0802fd19c28477376aa900.nq.gz
    ├── 2f1c3e725a0136791bb9ac9465c796c03d683dd3.nq.gz
    ├── 2fd5838a501a113032e00eb9c9db48ac4e6ab18e.nq.gz
    ├── 300e60d10f2a768ad2d9d216e0928b07d6c29bc6.nq.gz
    ├── 311ffb267a0839ccfab87b27ad816672ca864505.nq.gz
    ├── 3187890e853781f61aa6497741f01cf59477764d.nq.gz
    ├── 3291ba6fd186050e9b1b928ad3f524b47a945e92.nq.gz
    ├── 335876583e1e75a388af7f4f2949002d8527707e.nq.gz
    ├── 34b6f200deab22533911fb1ec800ff8770254792.nq.gz
    ├── 3510b37697b197c175a1e63ff49161c66de569de.nq.gz
    ├── 353f2654db767fcdbdc38bb3bf57b7bf8a049d31.nq.gz
    ├── 3663060be03cc954cb6d710a482953b6667b561b.nq.gz
    ├── 3795aace59da12815544dfcd5bb9973e196f7a43.nq.gz
    ├── 387cd465790be78c258304c67b24962e949ef73f.nq.gz
    ├── 38c09c624d3b8c7af799934408cd46dc6cb96147.nq.gz
    ├── 39be08d61c2b8eb8cedb4ca109f97cd778d0b374.nq.gz
    ├── 3a341a82fe48aa17cee5073c1272d19557d5c6bf.nq.gz
    ├── 3a4988b00d4fd0e1d44b4f56d47a42c8832436cb.nq.gz
    ├── 3b51e972248d96fd66f9dc188a859eb6bbce8631.nq.gz
    ├── 3b722835c9df54dc086282ca37e91d9910518fce.nq.gz
    ├── 3bd30e1191c9686f4416c6efbb8506f587272c0f.nq.gz
    ├── 3c12a8c97ad5f07804cfd0256f8e7724f2cee8b6.nq.gz
    ├── 3e24e7decb1d30644faac204b44bab76d857ed9a.nq.gz
    ├── 3e8a9cf480ccbe4a30911bdb7d78c0b80e767c81.nq.gz
    ├── 3ef69f6cb2b96e4f187d11efe5b6a0552f7156b9.nq.gz
    ├── 3f56e5ffd18b0fca5c94f1a0372e8bdec23a2583.nq.gz
    ├── 3f9cba40eb39f5bac143b069891be7242a966271.nq.gz
    ├── 4000a94b648975db2e186a749c79dd924a1b3ed6.nq.gz
    ├── 405622a9de0b940aa7f7f1d2883d783dc9a58ae3.nq.gz
    ├── 406eaebac303d695999f2dfcf4258839beca8656.nq.gz
    ├── 4132c4f5ea25cac64e9646afa9ae1c008939a809.nq.gz
    ├── 42595e8fd6cee1e6e0058a9b0c62db21bfa5abd7.nq.gz
    ├── 4273496d3e305fb29c4c5b83ce98405e23afe674.nq.gz
    ├── 4291ff7ac4a9ff480520ca174dae7dd87adc3508.nq.gz
    ├── 42aa763d571e5b01294941e30fc8fe5eabfd88e4.nq.gz
    ├── 43065df6c94286aaa62ec0925a81dcfb0021563b.nq.gz
    ├── 455b4c3c99cb843696c61fd43785ce74f486f6ea.nq.gz
    ├── 45be2c29fd4c020d16d45b0bc5f9f78b9d24d64f.nq.gz
    ├── 467d4cef400118a3c0e9aec2d5bb330befd04069.nq.gz
    ├── 46bf8f98af1bd0731c2ef4141002abd8a2256b79.nq.gz
    ├── 47bc9cc1c27f78db5777f6a378748c23c8ebe377.nq.gz
    ├── 4890904aa53735e21e083753e14665a6accac3d1.nq.gz
    ├── 48eb1503aad3cce89a7c8ff6f76d367a75ce147c.nq.gz
    ├── 491bfe083647c9d914b1641432000c3dcd625c22.nq.gz
    ├── 492c2527e98f7172c8475e8a33ecf5cba47d4a13.nq.gz
    ├── 496b484a66f1d9726f004e4b7b2072428438bf56.nq.gz
    ├── 49b1c752aa55a68d9a9ee100dfc203cc8b673705.nq.gz
    ├── 49c2efcfe2b36365cb9e1ba44a57418de5af6c67.nq.gz
    ├── 49c745b70e444ab10fd04225a48138a01ca8e1c6.nq.gz
    ├── 4a881bf8a87c1a0d826aefc3793612a05c294bc6.nq.gz
    ├── 4a9c9d102387bdb40e820c3a7b8c28310fe2dd73.nq.gz
    ├── 4aa6511ef2a57fe00d0822c77b56ec6bd6ff25ee.nq.gz
    ├── 4b94aa63dc5cad9a56669bc7165c741c95096931.nq.gz
    ├── 4c16cd00d6803598a4b0e5306336919e3ac329dd.nq.gz
    ├── 4c7979376065907d2adca51fbe76ff71079b8000.nq.gz
    ├── 4c79ee6c4718d2989821081de55e643f7deb72c4.nq.gz
    ├── 4cf0c72e29af1d7beb5fa5e3b1e01746cbfe1621.nq.gz
    ├── 4d33e220706e42a45175dbcba85b7e49ecd6938e.nq.gz
    ├── 4d9a01ad8bb2e7b0b63ed483e7c4c34ed0a22033.nq.gz
    ├── 4dbf6ea03977837619c3c3d9946062a8f4a40249.nq.gz
    ├── 4f61469801146835f824e9dfa9a28a5b24aca582.nq.gz
    ├── 4f85b49066fe0bc3c78c74d20ee20154584cb8cf.nq.gz
    ├── 502a311c08e549ac395a02650543e424a6d3e11c.nq.gz
    ├── 5074a342ecbd11dd492636762ea1ac3117b7856f.nq.gz
    ├── 507a9b3dee1f0bed8347729ea9d7baf7a910eca9.nq.gz
    ├── 50ad8ab11810b1319409b1e8268d5f40e794a3c0.nq.gz
    ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
    ├── 51c3700804c16b04448e5aeb38345eded1525847.nq.gz
    ├── 527d4b5e4bf280103b61c3a8edf9f2c9a58cff45.nq.gz
    ├── 52a8be2f187cd8a17af8de4cc971097148a2f8af.nq.gz
    ├── 52d78d9efe62717d529631ab25b56494389c520a.nq.gz
    ├── 53dac4d112309796952945e891a5e42e21343411.nq.gz
    ├── 549d9afab456b45032945fd47d5c2900e3797a1b.nq.gz
    ├── 54a80baaa2b5cc207008fe55be219087d82acf1b.nq.gz
    ├── 55f0526e4a560a62b5340ffb37438b1402de40d9.nq.gz
    ├── 566575e52d94764361c0c2b44ecbe999ec935225.nq.gz
    ├── 5708144fbcc5983f70f935f4de8402320efea680.nq.gz
    ├── 571bf38907c13ccf35076f18e6d8aaa3119b9473.nq.gz
    ├── 5813199813c8af957167a7b12baf275b5f87b9b9.nq.gz
    ├── 58165efbf09bc9e53bd5c391c5ce25cd7f31146b.nq.gz
    ├── 5a01037c0e104928e681145121f92c6a08872313.nq.gz
    ├── 5be982317bbf90944f2b15fe98e8c8c2b903a1c6.nq.gz
    └── 5bfca660d0158198b57c609be95f8472ce2a0208.nq.gz

6 directories, 200 files
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
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
