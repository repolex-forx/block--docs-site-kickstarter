# Repolex Knowledge Graph of block/docs-site-kickstarter

RDF knowledge graph data for [block/docs-site-kickstarter](https://github.com/block/docs-site-kickstarter), parsed by [repolex](https://repolex.ai).

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
rlex download block/docs-site-kickstarter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9ab73d6643d75a040344479969b53bd3841d675b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9ab73d6643d75a040344479969b53bd3841d675b.nq.gz
│   └── repolex
│       └── 9ab73d6643d75a040344479969b53bd3841d675b
│           └── chunk-001.nq.gz
└── blob
    ├── 0010cfdedac7422d5a61636b316a1172240569ba.nq.gz
    ├── 00b8df4eb6bae44277a4aa135b1871f5521e1b99.nq.gz
    ├── 014cf21113751e75a90078a7c539f1787f88f7a5.nq.gz
    ├── 01824f669576da7795c470860099f64f45b190bf.nq.gz
    ├── 028804b605518948bdb87921757fabcceb6d2b3e.nq.gz
    ├── 02e21c9bed607d40389e9b74e050da7c33632036.nq.gz
    ├── 04076edc86ce7185af947d53dd48365e709369a9.nq.gz
    ├── 04a3d8c52b645e8d9b30304483da83221a351bb7.nq.gz
    ├── 05c11650b40f5b23d5f9fc04ace02e91cc979080.nq.gz
    ├── 07d38fae6daae0b7334b09d78f25f978adc49c02.nq.gz
    ├── 0842510d384a87a2f2b5445d3f0db30f98131992.nq.gz
    ├── 09b8c7281d7aaf3fad60fa349c8b5cc374593087.nq.gz
    ├── 0a794388feac42cd67aaa45063669110218fdfcc.nq.gz
    ├── 0aa0fa81c87e084365a04a5a3f07599fadd1ea16.nq.gz
    ├── 0c5fa4599e78415b861afd0037658c7b08bece04.nq.gz
    ├── 0d61ead215a934e5ef21b74fdd2eb04ea93391c7.nq.gz
    ├── 0e15b3d986eb0267163885e007c1228d29541e2a.nq.gz
    ├── 10115bbb36f5b7cfcc97acb00cc43909bc480087.nq.gz
    ├── 132385f9e8bb33dd22ddd568f65679b4e577e042.nq.gz
    ├── 1475a5d750929dba5531362df8d7609bd0bfff43.nq.gz
    ├── 14de3817ffdbe41dff5262807d554b617e1ff233.nq.gz
    ├── 1610908289acc1b7ad8afcf28b6ded2eefede80b.nq.gz
    ├── 16fb4887ea5cf350fd3ce2f6146382f3d44be23a.nq.gz
    ├── 19841e6bef037a8e9cf763d0c831c2bc8285d8b0.nq.gz
    ├── 1988a29d18edd8b0ad725f7a11f05ca2795a28d7.nq.gz
    ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
    ├── 1d7a6c27245633f4976ba602e0f00beb602314c4.nq.gz
    ├── 202700f5ba68c19d1b3c88ba4e68f853a5a592fd.nq.gz
    ├── 225e1138e070cfd8a511b725b563343b9b59f07a.nq.gz
    ├── 22ddc4080126bc001ae5310996a9622c9f6bb65b.nq.gz
    ├── 241d08fac2ec5b5ab3bd1687285bd4334a6dc139.nq.gz
    ├── 25364c5591f48dc4739d62cc1efa6b11db9a8fd5.nq.gz
    ├── 259739d4edbb2f72faaf872a056f0b073a00bc30.nq.gz
    ├── 2ddea7208c9ee59ae083f83e5cd73200e4d2e16c.nq.gz
    ├── 2fea8ebf51301db08c7c6cc33ec4022d87559b59.nq.gz
    ├── 30301ceb5fe00afdfd7576301119b0dfbe7204a1.nq.gz
    ├── 30703f3cbc7e8807cb78f71927e5f258c8a45857.nq.gz
    ├── 3194767a45eb42707cb829999debf52bd15dd6a3.nq.gz
    ├── 31c29b5e3cf8ec27c88f4a087a0139a465afae53.nq.gz
    ├── 31c9f3fa75a46b387b7a88ed9ff574f45da0147e.nq.gz
    ├── 320652207095f823cfcdf9d4377e5bd167a00bce.nq.gz
    ├── 326af914c12df018e21e98af84c985b6a2ccae9b.nq.gz
    ├── 32d5a89e59f9d5231f9e905809e34a6ce1c548b5.nq.gz
    ├── 32eb7350dbf81b92425a875c7d582890200fd7b9.nq.gz
    ├── 3447494eb792773bd07a135a7754700268d57038.nq.gz
    ├── 34de3a82d9f38b4c22902491a52ac2725227c84b.nq.gz
    ├── 359b01a822d117456c0601e057abed9f670a7826.nq.gz
    ├── 366a8275dd69ca7d3da060a8ae499d0182d6a53a.nq.gz
    ├── 3754231a7799b4184e268de7096f0e524ff05868.nq.gz
    ├── 386a46370f4564aa3ccff7353fec6a405306138f.nq.gz
    ├── 38a27d488f2176d228a72c96d8d88cf1606573e4.nq.gz
    ├── 3b028208b0b099c07865bb71b80ecacffe3cda71.nq.gz
    ├── 3c617bfcfdf6e09f88b54056178856842c211cbc.nq.gz
    ├── 3d34afb7b86c22a39baab11c873d5a34d6b3156f.nq.gz
    ├── 3d9d99bdc7bd2b94f2280f7b20296aba39ad20d4.nq.gz
    ├── 3ec3cbb1764f2721804382f1ec90e474d1f20489.nq.gz
    ├── 407b61e05dc0abd2dcb5f80db55537a8380efa9b.nq.gz
    ├── 4082f41c297f2010d8acdee13816f8469add0afb.nq.gz
    ├── 41505e3be106d9f4929bcca2f0d1e31a5fd72738.nq.gz
    ├── 4199548784aafb1cbbf9b13438d0b77f90cf5152.nq.gz
    ├── 434ddb7c1ca4220e95556b4f3ab3d03fa58f1bf7.nq.gz
    ├── 454b28fcddaae053685072665c513f06bf27a93e.nq.gz
    ├── 4579c977e3216e1884d8b4ada1fec11531a67303.nq.gz
    ├── 45d5f5cef00b82dbcaba8e5f8aa0114e1e61cbc0.nq.gz
    ├── 46082fad265a1499a1b5d0d713107e0bf92c991c.nq.gz
    ├── 4675c2d61f29e35b010e66ca2e7d8b37b1ba55d0.nq.gz
    ├── 489c33aefcd17097314c7723674e61950305f81c.nq.gz
    ├── 4c812bd362ad1788c9d413f87383455f43310344.nq.gz
    ├── 4d25a1979ec2d2ea06ea7d45fbb84eab39fad777.nq.gz
    ├── 4e442967de68a64cb2e7cabd2719bb76cc8aa5ea.nq.gz
    ├── 4efa46838f4e3783d501f33eecead9076c07240a.nq.gz
    ├── 4f886dc94fe326de95baec95844fefe60175134b.nq.gz
    ├── 50155f403e6e956bb877c7f4c531083faa631191.nq.gz
    ├── 501580386d9dab5b344f94afa6adc9e9ec008ed8.nq.gz
    ├── 5058c84d2fe000fac97752078e4c4596a4069d32.nq.gz
    ├── 5148a282448b82abfca9bdf18236c55f8b3c89a6.nq.gz
    ├── 515f3e14df43f20d92e3dcb99f5cb1c47fad4aba.nq.gz
    ├── 546fe4067d5d40f1acf18b93f613f793745e8ca7.nq.gz
    ├── 55fb4dcf0124f51c0e520da47890626f0489e431.nq.gz
    ├── 56e156f687f01054c2a1ee0defda6e8387385417.nq.gz
    ├── 58a642204d1a2e1b9df178bd4ec09580a173ce84.nq.gz
    ├── 598411b7390ca6d5df4e0bae76cf318044b64152.nq.gz
    ├── 5a69ea68372b1169697cb12b943656dc4bbccc6a.nq.gz
    ├── 5b2b6061ada44f04358626091732e0119fe16e3a.nq.gz
    ├── 5b4350eba42aaa63172fe9d7ba9bd6f149d3e153.nq.gz
    ├── 5c29aad6ba16264e07f533be4114ff3498f12272.nq.gz
    ├── 5d19589ccd019912ed0a11957fbe57a1669be335.nq.gz
    ├── 5db5d6eec896b83769c2232d59deef927defb877.nq.gz
    ├── 5dcffda4591be5153edd99ca169c8f6edb2f5419.nq.gz
    ├── 5f15c7cb0c324f7fe5b21406b2373013e846ff22.nq.gz
    ├── 5f9ed90e8b92b5c9c3a2dd371370a26ca9287ba7.nq.gz
    ├── 625510b634619d2ef209ddd0dd48fa86cf5a680e.nq.gz
    ├── 630c862c1cfad25ccc50cb6893d3942b7bfda0d3.nq.gz
    ├── 633d69d91f8ad8939ca68cf5db5acc06910594e5.nq.gz
    ├── 63bdd82ad48b08ff2c0d9479553b015b276b3292.nq.gz
    ├── 65857c6f789cd49d6b635487581f4d6f49106ed6.nq.gz
    ├── 67627f66ae176869dee1d374b2fdf135f73f4a27.nq.gz
    ├── 69812626d8dbe40107ae342256e7edcdd932d325.nq.gz
    ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
    ├── 6cad0ba9c251ddde1a7314631b541fecae25015d.nq.gz
    ├── 6eb282c9e7c30fe1dcedf648d76e7551c4e23d6d.nq.gz
    ├── 6fc5559bc3b8fba9e5e59dcea400c108c0dab82a.nq.gz
    ├── 7229cbb429d6879a39ad4cdeb9da270fc7f4cc01.nq.gz
    ├── 72aee516313e441a328bd7257c738470ea518819.nq.gz
    ├── 73e617052472a1400a6abb851ca6f98141087361.nq.gz
    ├── 740d737704329b5b5dc0ac8dd534fed04733ec79.nq.gz
    ├── 74431dec68495931240723d5155808b515be662d.nq.gz
    ├── 768636d937e038bac8910385de563d1ac61b2a61.nq.gz
    ├── 7808a0344716ed877156cd326ad5ba2404523300.nq.gz
    ├── 78906f0580415bb4fb136c4d465b1275c8e260e1.nq.gz
    ├── 799a9a9dc9c33078af13f5e3fb35cd70ab82f7c4.nq.gz
    ├── 7cb1945e8fa5bb7025ef41c7335e0f48c10207fb.nq.gz
    ├── 7d2cee3c7ff91974aabd0390973bab98fe47e113.nq.gz
    ├── 7d53382340ef2ed5cafaf1de055ae9a663565442.nq.gz
    ├── 7ded6edeb7e56614c38ed5fe2fd7e61afbbdbebe.nq.gz
    ├── 7f74ace0cac25e3408df3c02de09562fca157946.nq.gz
    ├── 7fdb59dfc8621aa9767d94f1d7af69f0f6aa7d6b.nq.gz
    ├── 8405ae26f26cb991781c464239b7187b4cb40051.nq.gz
    ├── 84977e433bf761121ffc176579b597c358ac4788.nq.gz
    ├── 85d92205d22ec435edcc34e49b600351e34e3191.nq.gz
    ├── 860ad8f15f95a6e89a9a32451d9de54a96124f13.nq.gz
    ├── 860d69d4032ada54e2267935f2e72ff1d6a9d4c7.nq.gz
    ├── 8726006731ad32162e61eb6e50a31dc86e5d5066.nq.gz
    ├── 8858b76d0d066281a70552f5c0977fc13c296591.nq.gz
    ├── 8873b851de1cdc125f2e576a5cd578bac7956e26.nq.gz
    ├── 893522ce3a74212261a45f8324b13ebeb1c5d400.nq.gz
    ├── 89438ac4014818a322d350fbe6fba806bcc9191e.nq.gz
    ├── 8b973f9515c10feec7f6fc41639d8580df0764d1.nq.gz
    ├── 8c7b46dbcbb76e0f87776112a2a51a9ba4bdccc0.nq.gz
    ├── 8ca1cc76fbf737439297d782df6eea0f5e1e8a5e.nq.gz
    ├── 8d39bbc6ab85766b1fda107ccffda24b5fc4e0c9.nq.gz
    ├── 8f1d663c25c9e03df255172081715d63d0e3ba95.nq.gz
    ├── 91770a4d95bc55b9765cfef64b10b3ef0bc8b202.nq.gz
    ├── 9197db94fa665ccf1a8def237f5f26e807df08db.nq.gz
    ├── 93262542b585154ef06b2382361584c6f6c5e78a.nq.gz
    ├── 94d214f668b29d7f55ecf5c91b53cfd76ae4de65.nq.gz
    ├── 958ff6b557cfb93956a260568d4ab3e6938dc678.nq.gz
    ├── 95a24b5aa37edcac4a1b6c6b9e66909dded67ac8.nq.gz
    ├── 962e3837e7bc886ca887e89d4a2f9366a58b862b.nq.gz
    ├── 98242cd0d0318e7fbfd69107b6e8729ed5e4f338.nq.gz
    ├── 988f30998590e0d6ab954ef46f314fd570df7b71.nq.gz
    ├── 9a2e471e82682497f1131399beb3c39f522a3c0b.nq.gz
    ├── 9b972ad5c100f7f466ebe8dc5b43d7b351429529.nq.gz
    ├── 9ea3311fcde694d205471d7074bb581d6b06883c.nq.gz
    ├── 9fe44aaed099b5bd2c4a759dd038d4faf089e7ac.nq.gz
    ├── a0162a6bbe3f80903e230d96ed0aaec31d91901b.nq.gz
    ├── a07fdbbeabab709357ccf058d3a8fe9e27d79fb8.nq.gz
    ├── a15af74063ebec835b093aec2bc708315567f861.nq.gz
    ├── a23a06812bb4615ac28c4ca66e332ec976aa293c.nq.gz
    ├── a3600be0a2d6e36d5ed14232cf84800605696c22.nq.gz
    ├── a4864096d7fa2ff99cf671447196f2f5d12fb31f.nq.gz
    ├── a52d92c15f0e6e09454938c6982f08ae38c4f715.nq.gz
    ├── a945281814d99f613e05caa24230ed13f760d69c.nq.gz
    ├── aa7b5ecd8a464e08b843a3a020eb6941f57f0690.nq.gz
    ├── aab9a0a70aae4e12ff47401470775eb23c08be7b.nq.gz
    ├── af0a20f37efdbc9c879643e856f2b7781bfdda24.nq.gz
    ├── afb9ccf7edf9840173ace80bd6ad640cfaaf666b.nq.gz
    ├── afdf0ca4e6ead82c26862234deb18fa9b2e62f14.nq.gz
    ├── b05b5f91ea07355d7a58641d9723cd25bd876c92.nq.gz
    ├── b123d3aac6a5fabc1fd7a9dba258d14953707f53.nq.gz
    ├── b151f574be011d99c6968e7577c4902ccb76788e.nq.gz
    ├── b72e8995dd9e5a56f62f974d909c736f1e415307.nq.gz
    ├── b7c7233ce0b979a48ff7512bbc05264ebcd2010e.nq.gz
    ├── b81909e487c4949fedb3c9557f5a53b9421fd150.nq.gz
    ├── b8ba95e5862e973a43c23534b3f30f018cb845ed.nq.gz
    ├── b9b8bb256a2d5d4425a14ec6095165aaabccd7c6.nq.gz
    ├── bb80df3a8698af980809eb98aa009decee13f7ae.nq.gz
    ├── bc04bd7cdb9c276114928e73a9f594366b6c3487.nq.gz
    ├── bc77f073b557caa6ff9f077f6d5ff53a12ae2ba8.nq.gz
    ├── be124b7b01643a73eb0fc51582775790d46c1828.nq.gz
    ├── c04db18fc4c4fbefe6809bc1f96c4b62b8cdcf12.nq.gz
    ├── c14d5b662ba31395363cdb22711b49737de5d140.nq.gz
    ├── c28bc64cbc986267785ab335324901c6ed3e6627.nq.gz
    ├── c2ad38b85a89512a9c028ae4ff61481003390030.nq.gz
    ├── c546248b74d681a68c39a37cec4b0376147a514a.nq.gz
    ├── c56615eceaa68defa8df35b93c2939daf10e1673.nq.gz
    ├── c672a0a3bbf349fd821794b75595b6d1392c14a8.nq.gz
    ├── c7ab54078cbee863bc123931ec04bca196b59dd4.nq.gz
    ├── c8f9124cc0a9ca3250a33b51e2db73c19cf29da7.nq.gz
    ├── c9b15ecf3ea539bd657cb9c0004bfbeebc47c01e.nq.gz
    ├── ca8c1d20530eed0e1a82e7d1d700a09e2983c194.nq.gz
    ├── ca9752fb352855d338de791f38cc659415d18bcd.nq.gz
    ├── cb6b106dbfbe0985ef00daa0a6f71d9a020b4b24.nq.gz
    ├── cbfb3057823f480fe1431bb7200f95520f8cf894.nq.gz
    ├── cc92b81c97d861ad43274706e01d669afe194560.nq.gz
    ├── cdb5ca17c3d3721f34d5d02f3fcfd8e0331b0381.nq.gz
    ├── cdc511489324c66ea82d7a484a795c4c578a3d01.nq.gz
    ├── ced654547e4e194ee490f068a6f8aa366eac5805.nq.gz
    ├── cfede1ea5b0aba466f07539541c222f2f47b8439.nq.gz
    ├── d04b4cf6171dff674cd3ddfd9b12c71bcf9b5981.nq.gz
    ├── d0c558ea6c55a6474d8a3f1f1c5e70ffbb48c423.nq.gz
    ├── d29d1a0f3be704609f6c45ecdfbd2ac36697754b.nq.gz
    ├── d34894136da140d3ea1e361070a3bac7fd30e4d5.nq.gz
    ├── d5266b34f8296e89783aa7f15951d53f04917749.nq.gz
    ├── d64ad090f0eae04480a2d25db6fc183aafb5a33d.nq.gz
    ├── d6bbc8869324cc814f03b927ae27da72604dbfbd.nq.gz
    └── d7035c6826638f158ffe2dcd62e7d8311f56aaaf.nq.gz

8 directories, 200 files
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

[block/docs-site-kickstarter](https://github.com/block/docs-site-kickstarter)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
