# Repolex Knowledge Graph of google/zerocopy

RDF knowledge graph data for [google/zerocopy](https://github.com/google/zerocopy), parsed by [repolex](https://repolex.ai).

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
rlex download google/zerocopy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7217b5f43d522ab6fbd4919c1583cf51e414ba4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e7217b5f43d522ab6fbd4919c1583cf51e414ba4.nq.gz
│   └── repolex
│       └── e7217b5f43d522ab6fbd4919c1583cf51e414ba4
│           └── chunk-001.nq.gz
└── blob
    ├── 0000eb0bab17092570e7b629f75ef87ebaafb072.nq.gz
    ├── 003907559670c9e903bc693c4b6ed1a995cf2f61.nq.gz
    ├── 0086f2a962dc843e4e7c3b21e41efc22592f8554.nq.gz
    ├── 038682724ff34b4ed99aaae648c63fa9dbe86440.nq.gz
    ├── 03afed0604b7e737d4dcf91c964fcaa66b312ad4.nq.gz
    ├── 03dc9f646ee93353645ecd8a3a32b5c1df53bcf4.nq.gz
    ├── 04204b952203d1e3cd5e87677be4c32dff04299b.nq.gz
    ├── 0432ed446d473ebd616b88909b0b7fc023519a2f.nq.gz
    ├── 0482a59d4da03f8dd01f4bc54687d5c57d4b8909.nq.gz
    ├── 04d8b8f54675a0d7ee34684ee8f2d20441d6d230.nq.gz
    ├── 05b416a55f39ee26e231fb414d56741a5528b40d.nq.gz
    ├── 05cb6f51c21c7fea23c5bc177fe109f5079ecdab.nq.gz
    ├── 05cca6b17ddd60b116644d7c3aa80c4b245e02ac.nq.gz
    ├── 0658bccf1512a56f18ec855738ad2f0c1e677b94.nq.gz
    ├── 0691557aa1b524dfe790cc92abaaad3810577db9.nq.gz
    ├── 06ec48d72a99d0122b3ea28ddd612318063d8622.nq.gz
    ├── 072f2064cbebd5d1bf39e51b2a8770f7085a5f4b.nq.gz
    ├── 076dcf54acc212ce8ba23684ce101c2b3f570619.nq.gz
    ├── 07d0188e441223f985affc1418893648aab390a0.nq.gz
    ├── 08088d0db6d3ffd2dffab630df7ded4f37f5af95.nq.gz
    ├── 08c7216b1eacf4eea9a6a9a9ee70f01f798a0449.nq.gz
    ├── 08d4c75c6085132fdc997cc87579f1984e1749d5.nq.gz
    ├── 0905dc6d5ff996da9966e61021dd969dfab74da3.nq.gz
    ├── 0906ff449a353bc52ffdf56c9bad5447d084350b.nq.gz
    ├── 09aa9068b9f4fee8770485719bb8f95c4e81b587.nq.gz
    ├── 09bb2f7399531a8e9d2b09b51a8d4f1d6b414369.nq.gz
    ├── 0a8ecb46487f79f775879faaa585e21d26804eb8.nq.gz
    ├── 0f06fd425c22a6aba2f1123fa839277381054776.nq.gz
    ├── 0f10c6ed048a60b40ea9bd4834189adf4338f9d8.nq.gz
    ├── 0f4aeec9e2455bbb10f258b7fc6ac73daaf0aaef.nq.gz
    ├── 0f4ce002144c170d92eccac1397fd5a161be9398.nq.gz
    ├── 0fc6f984b3eab329c8aaae57ac4a07b5f5c2d666.nq.gz
    ├── 100b0ded12e5861f04a62d467006c983ba5d94ea.nq.gz
    ├── 109bab179b7ee9330ebe754e0753bba8a846feee.nq.gz
    ├── 10dc0d18f373fd36c9f6e36dffdff50c9be8a74b.nq.gz
    ├── 114e917b54497759d0c70742b5b792b857c6233d.nq.gz
    ├── 118d6ddf1f0d46bb0952c2b3afd372e271aa9e1a.nq.gz
    ├── 11e6ffcfdb2f4aca39c1c95a461a93264c8a9330.nq.gz
    ├── 12379b6eb3c39e8083af50f76c67d03f814298f0.nq.gz
    ├── 12ad69147759baf789edf82edb866b79d89a63ea.nq.gz
    ├── 12e10eee78ddfa6cafef528d258dc59ac98c0874.nq.gz
    ├── 13d4b64ddbd35f2111d4bb92a3b41a24b5f1253d.nq.gz
    ├── 13d68fce49fe1c509033ddfcc7ca36495141867e.nq.gz
    ├── 141929e1154a3c716c37f5af4a5fbc5ed8dac98b.nq.gz
    ├── 141a74e74cea57d2ed8babdd2bb3c09e38f18be8.nq.gz
    ├── 1427c7b0e918033602a52d69e57c99ef94981498.nq.gz
    ├── 147b04cf1ffac9220308f76ae5185966024d6292.nq.gz
    ├── 14caab4b657a69807129b9ff8c903abc861e8982.nq.gz
    ├── 14e72b4ddccd72d5c67d18c71bd6b59297979ce9.nq.gz
    ├── 1533eb9efddd9087f17dcd53247427fabfb69f12.nq.gz
    ├── 15561e68b2ddfcb4fabc5e1cf3908056ec3d5832.nq.gz
    ├── 16e985cde564c824b6cc2109ae479a6658741042.nq.gz
    ├── 18ca8a20ff87eb696f884135e8d475cbfc08110d.nq.gz
    ├── 18ecbbdd74b33d807ee18a5c17457bc60899da63.nq.gz
    ├── 19726a2134c5aa99b1aac0cc7a88bc3b87c0db5a.nq.gz
    ├── 1987bf15b227911cb2312d8a5afeb0a93fb1aeb7.nq.gz
    ├── 198866d8f8c2407f541069f166a07836d69db17d.nq.gz
    ├── 19c211b2c022621ac3bcb948c5a4c01cccde289c.nq.gz
    ├── 19f18bbcd78b9d491bd79d88a610ceec956609d7.nq.gz
    ├── 19fd0ce4962eaed6eeb65a4fb498f61e008101fd.nq.gz
    ├── 1a6a58127a69e57cbef656b5305186242c9d1d11.nq.gz
    ├── 1b1bed31f3f157818ccbd53c4fc93d1920df7f8f.nq.gz
    ├── 1bebcf2d68702f521544440a7f8bf67140f69d5d.nq.gz
    ├── 1cfc584099be4e92802d78b4b45800479d2b3b32.nq.gz
    ├── 1cff579d973eab460d1466b0b2b4e37b3814d958.nq.gz
    ├── 1d1f58951a9ddf91aec5bd1410a3813adc8cb54d.nq.gz
    ├── 1d66a54ef72d69715e756ca3634bbc7066dce341.nq.gz
    ├── 1d87f69028ed3746427422695269fc4709620018.nq.gz
    ├── 1da794871f49c7945e865f200318cace7c5e980d.nq.gz
    ├── 1db5b9c6e733c8c06aea6ea268aed6773e7a52fd.nq.gz
    ├── 1eccb5159bd0920f85fb6b50a283a7dff956c038.nq.gz
    ├── 1ef34feb7f07366452893b6460685de24fe67965.nq.gz
    ├── 1f1f31f0b8aaa569a9122d31a7c6e2b1030c8d45.nq.gz
    ├── 1f706233d145a94feb06adc0bcaa424088085a62.nq.gz
    ├── 209f4b25a6e63dd502929ed484fe81d8faa10add.nq.gz
    ├── 2222e924aa7d3e9520c487cb35111599d4b6d2be.nq.gz
    ├── 22b86002493debecd253a410dc2a136b0731103f.nq.gz
    ├── 22ca8bc43889be0241a5bcd6c99bce66fbb6a323.nq.gz
    ├── 22d379ada7a916101f9ec4375ed9ad399a82b095.nq.gz
    ├── 239991357dafbae2681a2da6d3821e2b03ef8762.nq.gz
    ├── 239c69f696b2826aa9363cb00897dca59105a0b3.nq.gz
    ├── 239d3c18de67de2166e218d36b39f9ab59fb5336.nq.gz
    ├── 241128d0d0c1da1be35c2603e312857851c49830.nq.gz
    ├── 24d3ce4cd826037f3c314e5adeb2e2f2ae407133.nq.gz
    ├── 2509defb7b31a89380961393709b05a5ffc75818.nq.gz
    ├── 251e58c5d1030e8d17f2777b791edf8d4209fd60.nq.gz
    ├── 2538c9deb463633605a3ba0976cce1fe5525078b.nq.gz
    ├── 255653ded58d7a5b48485e57385a288b6d1ea17a.nq.gz
    ├── 25697a99383872059a4f97d254368f0a9725ee25.nq.gz
    ├── 257f61c332c7108298824c4ec2b2b9cee9784c10.nq.gz
    ├── 25ab0325019ba475ab4325cb2a81134d7af33de6.nq.gz
    ├── 2696d4043e3e356e2523a80dc2d93e8511f0f8be.nq.gz
    ├── 26b185639dbe76aa598d8b1b57674e0b019af151.nq.gz
    ├── 26e15216cd727a960953f4cfab99c16acd7eaf3f.nq.gz
    ├── 272d11f416c0e76a74c5cfb43cede9299383f679.nq.gz
    ├── 27cf93ae6874707254c578dee9b0cc13d525c9ae.nq.gz
    ├── 280f05d41038b155b08e06445582d4dff745da65.nq.gz
    ├── 28438632a28ee0f340d9829d8ed4b75019b3a244.nq.gz
    ├── 28edcf15eb65091ceb5188d99d05a51e16ebdb1e.nq.gz
    ├── 29e98d64ce250fd734df3664bf65160f6f1105d3.nq.gz
    ├── 2a8bbd93d7704c290685bec172b3344cfa04c789.nq.gz
    ├── 2aec95ae6c11486e4d41f5914b1384b165bfcdca.nq.gz
    ├── 2b02f27c9079925f591989600ade7be5b51aef82.nq.gz
    ├── 2b5ed44b08bc61295dc0a01fccf70ffd95c50b92.nq.gz
    ├── 2d8f510f986d1a8f7dedcf11e196d7d4a59d5117.nq.gz
    ├── 2dc22c12fa9c6ef93d7e9319ded0df3fc055aec5.nq.gz
    ├── 2e306c25baea39c611884924cc495e13174bf55c.nq.gz
    ├── 2fd87ed86bbf4973239c41c1b436df31415e9b3f.nq.gz
    ├── 30fabe5a663c26bb35636d88580dc86b010a5b54.nq.gz
    ├── 312da091a1b692755d226d2713788d7e657e9206.nq.gz
    ├── 31d3ba39e400633451d362706c3fade001e5a58f.nq.gz
    ├── 322f6340e299fd4ae10f8224b209621a9fee3bc1.nq.gz
    ├── 32377e5ea3434a49a104ee4fb1675ff1a1aae207.nq.gz
    ├── 3262b014aa260e9a00c29cfcfccab7a94f18e7f0.nq.gz
    ├── 327abca3fb2ad44865ad6ddfbbf5a922e65ada10.nq.gz
    ├── 3361707c11a670884b782ca48cf67dcaa8b6d0f2.nq.gz
    ├── 33a9ecd9559dc4dd6d9fa1bdb60803b66107a6b1.nq.gz
    ├── 33f9cf2ee77961701aadef5af902e17a0a9cd741.nq.gz
    ├── 343d517d5b017f8593bbab1d8d9fd3cc51baf266.nq.gz
    ├── 34bf863a56cedef1ff14163b944d67ee8b4702f5.nq.gz
    ├── 34e3307388bd6b4319f9ad33962fc52349ff4553.nq.gz
    ├── 3510954a82149ed6cd14cfa1ae5b11ed0ed67419.nq.gz
    ├── 358a4a6a7ede4ccd81f15240665b5d97b87c769a.nq.gz
    ├── 35dc780eaed5facd957e76189b3038264916308b.nq.gz
    ├── 374a1b393c5ed1880911c75d0e6742c703f1463a.nq.gz
    ├── 3752cf747e181d19175a0ecee5f308370e92c497.nq.gz
    ├── 382f8bb755a4e899715d5d466df2fb92598bdc4a.nq.gz
    ├── 3877619cabca2416f7fa97f1643261cad95304e1.nq.gz
    ├── 38b76d0067e87e8954ad7c3507e445341c6fbaaa.nq.gz
    ├── 38dd5901ebcb0da27763a3bd8dc6a5af760e2cf9.nq.gz
    ├── 3928a1cb2a0e36396adfba1ff33231ce1ac9a711.nq.gz
    ├── 3949f96753bd92f0188ada9e5cd88c832aa976ae.nq.gz
    ├── 3a1c79d804a711a5f36b6a2ce795bccdf9117186.nq.gz
    ├── 3a55b4c6126850d8ee266816e38d0621d77ccacd.nq.gz
    ├── 3a6bdf78a61cec3013de78b58beb20714cb2b8bb.nq.gz
    ├── 3b79ffbeeb8defc63cc5eee6f1c212fc1534e9b6.nq.gz
    ├── 3d6765cc3a19b25975e8e68a50e6db5b8853f381.nq.gz
    ├── 3eb5ad50874055bcabb27e196769db3c4371cb29.nq.gz
    ├── 3f569ac9711367554ccdfab137fb77995348c9f7.nq.gz
    ├── 400b0a81668c49e1b002bb7ee9e33bc02258e0ed.nq.gz
    ├── 40c69f63c43a832a30baef22f4f114c67ab36f56.nq.gz
    ├── 413dd68d89b937c0441759ad686ee2b5548e5347.nq.gz
    ├── 414407279c0719c2e0fd331c78d5b53ba2441e71.nq.gz
    ├── 415d2f3278617093c15f9944dd206e459a13e68f.nq.gz
    ├── 41fc51f767dd2b2aa5468cbfee4901e195f944e1.nq.gz
    ├── 41fd8c533f7920f20893da27f1444c5c7e6e9ed8.nq.gz
    ├── 44b7e66233957bc6293eb7882d43c08225af8271.nq.gz
    ├── 44c06e55254722232e5cdce851655d3ddb76796c.nq.gz
    ├── 46070fe91432e5f5577618c9bfcd041ced4bb63b.nq.gz
    ├── 460880f7e152649de48d4f8d816b10e1686fef8b.nq.gz
    ├── 46e7083a27d13a3d6d5ce8a687fe09acc84b6327.nq.gz
    ├── 47372b1be4b5eb317c429c733e24e3da397ca8b7.nq.gz
    ├── 4875f63bea1328626d5a31c9146f0444314379e3.nq.gz
    ├── 49aaa9a076f574f11251931ccf180143f405b518.nq.gz
    ├── 49fa697e20373a984a66abaf0ab508aea661eb24.nq.gz
    ├── 4a9160125cfd6cb1ffff67b892b0940599393870.nq.gz
    ├── 4b5262257343d058dab09e7a85aea02dedb76caf.nq.gz
    ├── 4b64f94ffb55c90fe27780503e3dd0ec6c719e15.nq.gz
    ├── 4b71af1d6de26c6bc66a8f7729e158bd915cb34a.nq.gz
    ├── 4bbabf0cc7d74510b084f39a6a9e29e994fc4212.nq.gz
    ├── 4c5e4981c8b2c09ce1058f68179e82cc92ceadd6.nq.gz
    ├── 4c94d501c2388a273f2364d22ca60a0fe3db1a7e.nq.gz
    ├── 4eb38159ca96c1615ce9ef87504fd09e8a1317c1.nq.gz
    ├── 4ef9f1a6641067dc2d683b7b04a086c7cbb23c2d.nq.gz
    ├── 4f5b8e17be7b7f188f4498c1032d35a42a399409.nq.gz
    ├── 4fc50b9f2eaf713c95507fe29a2ea17b5e0620c7.nq.gz
    ├── 50cf0e7cb838afaca42abfff7aaec2e3ae2f0c8f.nq.gz
    ├── 518402df91f9b9c5a820cf50acf80fd1c82af0ec.nq.gz
    ├── 524fdb8d4dcc3be05468ba7612ca6afb8e13d588.nq.gz
    ├── 53e3eb9b0aa59db355673e1d96e9086e7db4e6bb.nq.gz
    ├── 53f4fd7ea805e98ac8fc513f98a4964f58031d89.nq.gz
    ├── 54fcc46fdc99af11180545dd63c3349341772508.nq.gz
    ├── 560bc8694dd3bccc736776e8639ba9c81f05975d.nq.gz
    ├── 567b6733f7eb2b6adaa63932cd7efe22e55d83e1.nq.gz
    ├── 57a5cb7cf0be28bfc76a6c8c4e0e44209c0812f9.nq.gz
    ├── 58a88a01312c145e500f62c8fb4b5809bcfd76e4.nq.gz
    ├── 5914621d1c937ac0a51903eebe1f7bd0f0ea9623.nq.gz
    ├── 5990caeb8316f2d297501ebc2e3c462bb2214e33.nq.gz
    ├── 5aa341aab581eb97cb3b676df2b518d8b23bb6dc.nq.gz
    ├── 5aa9d70695fa7eb6b674d809113a3ac3fa3faad9.nq.gz
    ├── 5af88593323e11eed0fdfe9b749d6a7bea2b354c.nq.gz
    ├── 5c9559b16048a85abfa1b51df6fa3ea9c74b3aa4.nq.gz
    ├── 5cc4bee82b4274cc2c7c870fc0db6b3bb3ff4757.nq.gz
    ├── 5d73ee0d5d7f125210775723b39f2a991e8a7423.nq.gz
    ├── 5edbabc47dcb7c54483fa3462e3258d9556c691b.nq.gz
    ├── 5f03e217f4164e554b4a073275ddf9f25e67e5a1.nq.gz
    ├── 5ff7145966fe520ca49d3debcc3194890e72aa62.nq.gz
    ├── 603e06914e8b97f4a4296cf656627c79ad763c64.nq.gz
    ├── 614c30600c8bc6289e190b855956134dadad5bd6.nq.gz
    ├── 61abd7fea3c661426f3a7de5b8edb7b1c2364f3e.nq.gz
    ├── 6245785bd7618f62a399b27d205de3c1a02c7ecf.nq.gz
    ├── 625f1fac0758d1c6dfe9bee03fad99927cdf0d62.nq.gz
    ├── 62d774f344246ce947434cedf6c326fc00986faf.nq.gz
    ├── 64aa798f9d10aab40ba5920e1852907d09c9df44.nq.gz
    ├── 65414b51fa2c04996d91c672c542f4bf944708bf.nq.gz
    ├── 6602ca352de56bb84997fa858e68f62492d61a14.nq.gz
    └── 6623ce25e40cda008c77003e8344648bf10d5cb8.nq.gz

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

[google/zerocopy](https://github.com/google/zerocopy)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
