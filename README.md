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
│   │   ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│   │   ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   ├── lsp
│   │   ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│   │   ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│   │   ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│   │   ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│   │   ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│   │   ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│   │   ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│   │   ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│   │   ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│   │   ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│   │   ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│   │   ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│   │   ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│   │   ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│   │   └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
│   └── repolex
│       ├── 0fee409131d58d2912847450717b9312e0a9513d.nq.gz
│       ├── 56d01078055759936f9ae411c42471a3664dff9a.nq.gz
│       ├── 737a4cd41d09878e7e6c584a2062f5853dc30150.nq.gz
│       ├── 78d2f672149e5b9b7d539c575d2c1bfc12db67a9.nq.gz
│       ├── 9e6400e513c8795116e780f58709ffa65b2dc975.nq.gz
│       ├── 9ebc45718c2dbcd8296460f6780a3840e9ca575c.nq.gz
│       ├── a8ec0d9428f209790d2b34d0cfae4d8378055f19.nq.gz
│       ├── aa3d688a15aece0a0de0b59f94dda870c724bc87.nq.gz
│       ├── b85283e8464d56ef129fe8969f9abbb77be31be0.nq.gz
│       ├── bbdafe33ce9f47e3cbfb9415619e354349f11243.nq.gz
│       ├── bf943943e9eaef59826bc847aa2fd20e33c05ca0.nq.gz
│       ├── c4c4088945a2c12535f539be7f5453b9ca94666c.nq.gz
│       ├── c6a71f9545ad0de5e30eee759a31a187475bcb0f.nq.gz
│       ├── cf215390d4a4d6f0a4de27e2687eed176878f13d.nq.gz
│       └── f21e4448e07251f1b1a4fb0a66b9be5e87843b4b.nq.gz
└── blob
    ├── 00eab115e1c19a86bb1ec64b7cf626fbf413e126.nq.gz
    ├── 019d804f3d4c7f3e4e945feb4d83b883de43bab3.nq.gz
    ├── 01a7d0d787bec234c40fe1f541db234ab1a50348.nq.gz
    ├── 01e530dc89432237bfda5bbb204e5ac6d358ff54.nq.gz
    ├── 0469d04e432af8acdab390d9848817716baedd5d.nq.gz
    ├── 049ab3b2d6f00cbdaba7a5580c80e696cd2c2a70.nq.gz
    ├── 04ac784434fc1d2088c53625c424130be7f6bfcf.nq.gz
    ├── 0597b7a80b46f63c4067f6190c27fd1b3367e2ed.nq.gz
    ├── 05d1207d40722480f2e0d5341dd183ef5bd9652d.nq.gz
    ├── 060b19efee615b2ac57f3c08f8ecb3cfb6f38f6a.nq.gz
    ├── 06a339be54c9493acb737f82fbf9abb90aa271fd.nq.gz
    ├── 06e799ec6ba345cc047411893d94762708a5913a.nq.gz
    ├── 0734a84f73d0ddb735a004c9e0416e018a7d50bd.nq.gz
    ├── 080e527cabf33b0422f6b8e5b172c17d7c039d39.nq.gz
    ├── 08c22f4f13371376c380d1a3223121aa7f0723cd.nq.gz
    ├── 0aa46ee2f864c218019156cf0cd7d98fb97be284.nq.gz
    ├── 0adc3d4dbcbb881910bfd90214534449fafddcb3.nq.gz
    ├── 0b6b6b3aaf239cd2f52c81035550b86388d6ea79.nq.gz
    ├── 0ba46451d08473e83ff917c33a55666eb98e92da.nq.gz
    ├── 0ba86e768909a99798ceee69fbba9fb0d6d599e1.nq.gz
    ├── 0bc9ea4e8b4fd953035f89dac7a7c326b49bccd3.nq.gz
    ├── 0bf2003e30e2a24a54640359bb04f3e98b26e3f6.nq.gz
    ├── 0c262dc4b85bb6244c08370fb41465e44ff03bee.nq.gz
    ├── 0c307ecbc6662c200583ecbfedd4e5d3945babdb.nq.gz
    ├── 0c496317ca99f1addea3cf7ae1e47fe0661f6af6.nq.gz
    ├── 0c5b3657c8538e47be88b49daf91600a7936d9f6.nq.gz
    ├── 0c8e30ee8fad9ff979fd07b0e90d8e28b864b12a.nq.gz
    ├── 0c907ae3f12a64e21087a9a591b1407b780b1bb1.nq.gz
    ├── 0d5a68fef62166b14feb892020abba9dc626be6d.nq.gz
    ├── 0d608a36e7247935e731df425d6625f73304e5a0.nq.gz
    ├── 0dae2173f22625a42d5443638377c90bb48d5717.nq.gz
    ├── 0e3bf5a214a4be844bdfbe526cbeab183208125e.nq.gz
    ├── 0eaf72149965d12be441f011c2e76c047a47adef.nq.gz
    ├── 0f30d5477f85f207e23628a30b97f53bd9e9e1a3.nq.gz
    ├── 0f5d2c6dbb031713d434dbf33d96d398ef5098de.nq.gz
    ├── 0f93f7b71febd8e794c5968c3263e3a5af1c14c0.nq.gz
    ├── 0fa2de7f368e76fe362bab03f00c64dda81cc761.nq.gz
    ├── 0ff0d0471e46613573a98a76101b3f0bc997f382.nq.gz
    ├── 10145a264342b7888ec6accfedc4f2808fb67a0e.nq.gz
    ├── 107659b903b3586eee9ecc5ab10c445edfb1dad7.nq.gz
    ├── 109f4441f8e05b3bc6ddd32873b81abea868a460.nq.gz
    ├── 10c7e56e8371bbadd1c2c0d8fc18b5554e49d220.nq.gz
    ├── 1161b7f4a47d444963fdc77ae3c92187b3354430.nq.gz
    ├── 11d9978f87e3bf5871091f8fefd200ab86a2f99f.nq.gz
    ├── 11efd1ed15832d51acef200d1ce93efc57297664.nq.gz
    ├── 1222d0250583096bdfbf8309d47f9b171ff0d53b.nq.gz
    ├── 1229ba4275a0549e01dd6e7b10e1ccf17f17389f.nq.gz
    ├── 12c589076b097bffa852571a9e041436731c3418.nq.gz
    ├── 12e09fffaff3f4d0f9211b9efb246cb246ff5b50.nq.gz
    ├── 13e303b7131553a882decdbd026290084695c96d.nq.gz
    ├── 154810fc99a97b7f811bbb95a046fdb852a06c89.nq.gz
    ├── 154cf44c96df86d1e14f685e9f913025c9a0ebbc.nq.gz
    ├── 157720ff958bf00852a11774ba8b3fc76bb16b39.nq.gz
    ├── 15e13b6f2e6acf30ac115d942d4c377868d3ffbe.nq.gz
    ├── 162cc6d4d73fc4d92921e94054421db0d774a314.nq.gz
    ├── 17e6bf1d295f4b57cd20048af03bbbe912953809.nq.gz
    ├── 17f06eea272d31229f9feca43e15eede8aaaff94.nq.gz
    ├── 182c0619ddc8ce71358d237d179e1cb83414a5a4.nq.gz
    ├── 1831beb84b17591a12265bc605467401ff5d5420.nq.gz
    ├── 1875711df49143b38b880111ef2cbb4ae01c979f.nq.gz
    ├── 194390a9e9756706acb79a3eb1e25da72442bf76.nq.gz
    ├── 1961e9f12684a23a0cabd04ab08b18f5935bf819.nq.gz
    ├── 19902ff8583d2771cf6549855d2ee2df79488bc0.nq.gz
    ├── 1a08700b08124791b69ccc1e40f6e0a1499dfbd4.nq.gz
    ├── 1af7ac88a7c9aeea80b979982818addc5444612f.nq.gz
    ├── 1b12eb4dc17827060f2e70bac957b3510641fac7.nq.gz
    ├── 1bd96c41e98cfd2066c35707f711edd27fe87a9e.nq.gz
    ├── 1bde05694786aba2990c56a6d8678b8cc01eac4c.nq.gz
    ├── 1c0421878aa935f4b77fdc8f2fc753a0f6ded640.nq.gz
    ├── 1c4ad3e49631164bed1f0546b7e99d2254e5f0aa.nq.gz
    ├── 1d25a2b9852e8ef9ba3e10f2134c286e753f0716.nq.gz
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
    ├── 1fb8ee63bf284ba3adbba3788b359dd033bfc44f.nq.gz
    ├── 2042fccf5c10a8d719b557400bf74fd868b875b2.nq.gz
    ├── 20de3695b7faef5a60381c03b2594defa6a7cc62.nq.gz
    ├── 21244731f72e2d062f127f50aec320b9cd55036a.nq.gz
    ├── 218fbace16e64f7dc7cf055631d65539869995af.nq.gz
    ├── 218fe3339b3c747d3f7d208d34ad005095ff0ea3.nq.gz
    ├── 21deae6850f6747a8d9394b3b28266b85d55e7b6.nq.gz
    ├── 21eb77651bdcbc2327301d61a910d62477cda6a7.nq.gz
    ├── 224d5449d138e75f4f3c25d70cb8f1ea54ccd047.nq.gz
    ├── 22ae823ae9f9a64d31be644f70e18ad25858c72a.nq.gz
    ├── 23088a334033bb883414346051be05410db43153.nq.gz
    ├── 23128899f42bf4a4f61af6a4f22a56ab88f09017.nq.gz
    ├── 2363fe29efff298bff1e68a1f52bab77fd4ec74c.nq.gz
    ├── 247007834a08672de65d7a3c91c871bd56da7bc3.nq.gz
    ├── 25dcb0b090ec59ebaf6c2515c95617fc135b0ac2.nq.gz
    ├── 25dde8b7fd233eefe206a7a9b6e509e03d1ae44d.nq.gz
    ├── 26234e01d88943135327f41d6dd4c356c7e115ea.nq.gz
    ├── 267ddddaa03478ed77d640c011b8f2c0d6641d04.nq.gz
    ├── 269eff42b963cefc5d8457b6daca68aa3dfa826e.nq.gz
    ├── 26dd4da532aef0c2c6722113c557de70b72266dd.nq.gz
    ├── 2769e96ade5505d4fe01ed0802b497925a543e9b.nq.gz
    ├── 27bee23001e947b56c4b3d5a6346280cafac5fa9.nq.gz
    ├── 27bf519c1ba868c635eea3a42f47858f66107388.nq.gz
    ├── 284b9e91a5bd9516982316fadb387c2c58bddd24.nq.gz
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
    ├── 2b16facedd6f04efeb0820e98437a2c7bce84f0c.nq.gz
    ├── 2b8d0661ed145baac8534976eb1292a2035a89e0.nq.gz
    ├── 2b9974e35d9bfafaa22465ad03c86b34e575e686.nq.gz
    ├── 2c57616ec11083b4b6b54b902d00a03c18dd190b.nq.gz
    ├── 2cfad55f9773f712c7fb82419c2d2d3a274bcc9c.nq.gz
    ├── 2d4ab9add849a874fe5b6620966848b563bacfc2.nq.gz
    ├── 2d74c58f248790e34e482eb07e20ec6c753c9d2d.nq.gz
    ├── 2da3ebb04b823a2850fcc0d9860cdbd32dac514a.nq.gz
    ├── 2dbd5693edd6d204110dd71ec131c41f2a1c6b3b.nq.gz
    ├── 2df94d41511775fdb5e48621ff7499c1c3b45e46.nq.gz
    ├── 2e11d9ff845550bb5a950c30dc1eefae55278abc.nq.gz
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
    ├── 35b4cf624eb20c9ffe4a9190346314c3cfe1b2fd.nq.gz
    ├── 3663060be03cc954cb6d710a482953b6667b561b.nq.gz
    ├── 3795aace59da12815544dfcd5bb9973e196f7a43.nq.gz
    ├── 387cd465790be78c258304c67b24962e949ef73f.nq.gz
    ├── 388c346212ee1a5db15b8403c2afa278cb5690e0.nq.gz
    ├── 38c09c624d3b8c7af799934408cd46dc6cb96147.nq.gz
    ├── 39be08d61c2b8eb8cedb4ca109f97cd778d0b374.nq.gz
    ├── 3a341a82fe48aa17cee5073c1272d19557d5c6bf.nq.gz
    ├── 3a4988b00d4fd0e1d44b4f56d47a42c8832436cb.nq.gz
    ├── 3a779a5e9a81a6b59b0fa1685c63e62e38a70b9c.nq.gz
    ├── 3ad79686242d35b2ce587ac8267259621d4769e4.nq.gz
    ├── 3b2d71cfc33339d1723da1b1f0adbccfb382fff7.nq.gz
    ├── 3b51e972248d96fd66f9dc188a859eb6bbce8631.nq.gz
    ├── 3b722835c9df54dc086282ca37e91d9910518fce.nq.gz
    ├── 3bd30e1191c9686f4416c6efbb8506f587272c0f.nq.gz
    └── 3bf8a9423a6fd47e87857db6677c06dea494fccd.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
