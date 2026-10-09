# Repolex Knowledge Graph of NousResearch/local_generative_agents

RDF knowledge graph data for [NousResearch/local_generative_agents](https://github.com/NousResearch/local_generative_agents), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/local_generative_agents
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d66508143a2e0bed9b8e32b7a9a2ab6435b7e2d1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d66508143a2e0bed9b8e32b7a9a2ab6435b7e2d1
│           └── chunk-001.nq.gz
└── blob
    ├── 010dfdd59a08086d741bd6de1708d0dc7dd9a570.nq.gz
    ├── 011a4c15c30c61b2e6323d400e6161cc05f55cf7.nq.gz
    ├── 01e01a28e3497398603af3350b65bc554484e539.nq.gz
    ├── 02ffc4ae5cf6f498fe8a86b31cadd94b3b0c5717.nq.gz
    ├── 031c0bc2eba240ad3e942730103ae75560403eb3.nq.gz
    ├── 036462edbe930c53f71e812d33aa81a0a6d53cce.nq.gz
    ├── 040ecce44d669a3a706c23d5bdbe0606b17d946a.nq.gz
    ├── 041470d256b9715d97ff34b83cb030bfc4a7c8ae.nq.gz
    ├── 04e679144f8d3c114cb640c55a9996b951a11479.nq.gz
    ├── 0505f450f6ed8892b0a75881993ade9253085ed3.nq.gz
    ├── 05c2c1e5fe07be11999254b3460c2914f8ed2d00.nq.gz
    ├── 0638627474a3c749c9dbaaa1b5b574174b4fadec.nq.gz
    ├── 067bbe8db64aa533541d33628ac755a18ebc9970.nq.gz
    ├── 06a87485a814d554a34efd1c5b53e681fa01a128.nq.gz
    ├── 06ed9551f72feab43b118c2dde351f50e73878cc.nq.gz
    ├── 07390a096e79f6ad1ccbf69dc80fdf114c0188b4.nq.gz
    ├── 0740f2717ca8d58fe2942fdc75c05890703be3d6.nq.gz
    ├── 07705907d8ece8ccc89c19e4ca7a2b249deb5ebf.nq.gz
    ├── 08053e6519cb27e385b65d36358020ac77df44a0.nq.gz
    ├── 08be204f5ede872437cb91ac69053840bea8dfcb.nq.gz
    ├── 09ea8d9a72225a615ecd228e7383149a4613b382.nq.gz
    ├── 0a32bb3a10d79f375c26126c850884306d34193f.nq.gz
    ├── 0ae4c622db139f6f807a405c70d478e479ee92dd.nq.gz
    ├── 0b8ea00ee95bdc96932b55e7bb068c89651a13fb.nq.gz
    ├── 0bafa8817b99a12de5519dcf9164a2f042212f4d.nq.gz
    ├── 0c2c924b6a56c6c3f104adfcc4df6b823a56bbad.nq.gz
    ├── 0c72f4cca67d48991025f3a44f4f660371fc81ce.nq.gz
    ├── 0cccf7cec93737b60fdea30c983c582bcaa7ac47.nq.gz
    ├── 0dbef4e4d26b67e6f27bde102427f0d8cf8cb686.nq.gz
    ├── 0e3e532078fc72bd7490fd8cb2b1f0aced0f638f.nq.gz
    ├── 0e514acbeea8b325fd422e3a11f6dc982f1047f3.nq.gz
    ├── 0f33d0569e651391f65725f617da7faa546323be.nq.gz
    ├── 0f8816ea66ba574055d92b77fb242224aae533e9.nq.gz
    ├── 0fda003361749e95a6a409037759207b558ba71e.nq.gz
    ├── 10b292c07e99fba05bf4e0d953c4b3a09138f06b.nq.gz
    ├── 113f5954cd797e4191217821aba70f1ac5453855.nq.gz
    ├── 125f236ae5b25f3d640335e09f35c17a9745d60e.nq.gz
    ├── 1267ecc5338724404fcb1c06187ed869a8ca2b8c.nq.gz
    ├── 12eb287988fc275d9a5af1a97dfc666b1fabbcd3.nq.gz
    ├── 1407743435caa277bf76e16e116e63eb2990f86c.nq.gz
    ├── 145df00f050de062a62c53574f6400634fef906c.nq.gz
    ├── 1469dc81fd04fd4ee21295919ec49a593998e00a.nq.gz
    ├── 147ff20ffab22c57b1154f3032251cb5dbb91992.nq.gz
    ├── 149671c310512449a5e294fe75856eee0a18edd7.nq.gz
    ├── 153e8bef0af4dba3224da70b548ce91a99f22d67.nq.gz
    ├── 1594ffb9437804b944e39a0683dbe6ba6c3ce1ea.nq.gz
    ├── 15adc92c176fca48c6e3fde946f1da366f6c66d0.nq.gz
    ├── 16d9f7be0b1764f97f1be93b6ef2931b7ac5b12a.nq.gz
    ├── 16dac23b5366976c024484c9a875b4e8432654c7.nq.gz
    ├── 16fc81634e774f705af5c78f8fe9a17eae4db12e.nq.gz
    ├── 17350fedf97cd4f0bc9ebc0a6ab437796263c09a.nq.gz
    ├── 17441eb5ff755912ad7f39ba0f1a23ce69502043.nq.gz
    ├── 17d1528c464f6398e1689af50ef6c463fcf63e8e.nq.gz
    ├── 180f25921210cfc36d000111e5fc6c1edb933379.nq.gz
    ├── 184f77477c4e908fadf664ea0e199d937774fb79.nq.gz
    ├── 1904f98b7f6467689b13790687000fbff94ae4f4.nq.gz
    ├── 19b03c9fa91372003b96ae4f90dce04e095eb3ff.nq.gz
    ├── 1a1c8eb81b66570a824a929c832d7003ea5eca21.nq.gz
    ├── 1a28550e800a5bba7c3d94680ca5b0a1546201b1.nq.gz
    ├── 1a312befba23d6fd227607869cbb4bf8504bcc36.nq.gz
    ├── 1b307f8e7e3c0dacc294cca8203e3207fcc2c8d0.nq.gz
    ├── 1b7fcd1675bd7b0c8426fa8e9ec1b506f9d299f3.nq.gz
    ├── 1c83b59c9a107ba6d2de947d240ff3717e369530.nq.gz
    ├── 1f53cf032c1198596b887d50183af5e9d3629350.nq.gz
    ├── 1f5c8187595ea1b0ca7cafe3078ddda8aada311c.nq.gz
    ├── 1f61d98923094f95d6e9f885a547345402614eb0.nq.gz
    ├── 20a9452c1869366bdd282926444e8779fb2f6e52.nq.gz
    ├── 20b7c595a63c939006a965a1dc33ce213b8d4d4d.nq.gz
    ├── 220d38d274f8ecaead42a56da2219fd8723e1a81.nq.gz
    ├── 229f13ac6e7ddbb87f5eba090947ee15c99a93a2.nq.gz
    ├── 2305954d58a681430f3da8a73a4b85e5e3ddcc1e.nq.gz
    ├── 238d4c80cb921862f0245694eb7d66decbd467c4.nq.gz
    ├── 24dd6138ce963d2ce230b79c9d38b840ff89c9e8.nq.gz
    ├── 250b4db26ab7b91b8e9e1074f1a37f8e91f7071a.nq.gz
    ├── 253d332f28f80b64f3bc0cc044109c0b95f40f71.nq.gz
    ├── 2549a95092fcb6c5e6050fa5f81a003a2a0bbec5.nq.gz
    ├── 273c9a0c8d4f5744ec103cce2be2214befe66d82.nq.gz
    ├── 2766a108303a6388da268495ed3078871bd9b99e.nq.gz
    ├── 278711c1f0460d0e8892b0a114654c7e8958c380.nq.gz
    ├── 286774db38c51c634a180d86db50649c9657689e.nq.gz
    ├── 28af3a91e066bd56f44a313a62bc7360b21c7149.nq.gz
    ├── 2b6a074b18e2174e032c4ee3c253ee1194aacb1e.nq.gz
    ├── 2b70dcbb576140c509a5f19d8d09c1824ce7dc6b.nq.gz
    ├── 2d0836d028a01964353e3eab30979bc286eda71d.nq.gz
    ├── 2d658569a61f7067d0268514ab4ac3ee183c8ce6.nq.gz
    ├── 2d65864ab23e138b828ad1a54dfe587f1cdd21ed.nq.gz
    ├── 2f0629698dd37b770d40132977b3d74c2e3feaf4.nq.gz
    ├── 2f6e5e22ef8e871c4e74622388583bda0cdfa77a.nq.gz
    ├── 2fcad9ad17f5ab2fd8c6aa426731e1bf294bce5c.nq.gz
    ├── 3028288d0a974839f91fa0e1d0a603d91407d63d.nq.gz
    ├── 30c068177f19ad86dd7597c7080e656b96b09ce2.nq.gz
    ├── 322a1fd3dc9b7333063a2dbbba547996aa714cd3.nq.gz
    ├── 3276882e05009005551c2cc2013d12ca804a40f9.nq.gz
    ├── 3372c5e62beaf59e188deebf7bc05e683e13fc82.nq.gz
    ├── 3414bf0abb29a1b8298376b423441d81a2ea17b5.nq.gz
    ├── 34dc2e4952262a981ef0f4e04f45ec0936168250.nq.gz
    ├── 350afa83a5b2f1a6d777e6eaad41fb13202d91eb.nq.gz
    ├── 3535b9f088df45b97525be69e6aec187ff7a244d.nq.gz
    ├── 357ae9acd083f3ef360c6f50e87827992bad7fe0.nq.gz
    ├── 3581fec268fafbe6e49a4d230ab4ed409f42a8cc.nq.gz
    ├── 35e87112e49b0f5e77fc79c44934aa8c6cec91a8.nq.gz
    ├── 3631f6d5c263f7038ae6b3d07f72d81d3ef541fc.nq.gz
    ├── 3689edd68beacba2752454f56b932f2caad060d1.nq.gz
    ├── 36a323787113f107dafac0c45feb113297044d43.nq.gz
    ├── 370704c36b9e84df8b7949aaefcc7a2a0baf5a6d.nq.gz
    ├── 37d06133d847caf9880065967758c8cdd8dcf8b6.nq.gz
    ├── 38d5190057ffd7526a2625a71e96fc2980329bed.nq.gz
    ├── 391cd8c44ce9839372c7184ced0c41e3dacfea2b.nq.gz
    ├── 3928ab52a5188285a867e786ec7387f4d9c1f66a.nq.gz
    ├── 39376ed147a02a43a28d15d43f1915ea4052d4c9.nq.gz
    ├── 39a1530846228dc661a038b12d871a7a6af72ba9.nq.gz
    ├── 39aa974ba6120846df0f16b7fcaa42e5f2f968fd.nq.gz
    ├── 3a640f14f213976cc5d2bceef51bc447a27bda9d.nq.gz
    ├── 3af4687bef42fff1c18e579f98294a70aee73088.nq.gz
    ├── 3b6bfe9dd82c8cf15a56685b30cdde26e1096be6.nq.gz
    ├── 3be6b43c97377329f7a55b6ee4876f33b6ef8c77.nq.gz
    ├── 3bee0d1afcbc6ae93c8ca8fd98d0b83d20f625a9.nq.gz
    ├── 3c59b48f0bc7ea5757836c6f266cecea1f802042.nq.gz
    ├── 3c9fd1d6ee30aeda5bcdcbb739425944974c9934.nq.gz
    ├── 3e51662647680a5281a4e0f1bce7de7bc1c605d7.nq.gz
    ├── 3f0bc66ce9658456ca1dd95af6ef78e9c91721b5.nq.gz
    ├── 4025af300a022560357434a1aa607db698457aac.nq.gz
    ├── 402ccbda2765209c008e3b12f076835f55d312e9.nq.gz
    ├── 41500e52170bb5b933692bc7bcbb197a6a3fbe03.nq.gz
    ├── 41e9e6be208ecaf5be5569ee948c22603a0e2445.nq.gz
    ├── 420964798d3484394cf223bf47aed129899463d5.nq.gz
    ├── 42357683b9e09e75a9ae30e2941c272499c7650b.nq.gz
    ├── 42542b54b47590458a83bde600389251f8ddd1c1.nq.gz
    ├── 4368a93fd16784b902f6d5ec6315f8d6ff96c781.nq.gz
    ├── 43745a3014f5b45c0d504ad1ffb8df03bf962218.nq.gz
    ├── 43daff8bd4f34065eb3987e66e5c4a5ed7a18f18.nq.gz
    ├── 444390d7768718502f8e340baaf1c61fcde3b725.nq.gz
    ├── 459f4a37314113f8706860299dd1ac197155d9fc.nq.gz
    ├── 45c65a04c35e099378d84cf0882fc9f425ec8868.nq.gz
    ├── 45e3f5582f3b1d6d7089c7b92868c4dfd57259b5.nq.gz
    ├── 46037dd722d3c9166466d3ac88a328d9c249d1fb.nq.gz
    ├── 466d41bf34a87d6068da847daccbe622041ef398.nq.gz
    ├── 46e31e0b939d257be2053955317dfe1b7656de29.nq.gz
    ├── 474dd474c965e00fa27bce50d9ee2aa900d7ab37.nq.gz
    ├── 485e5fd9762a6d0f86102358dcac853d794a8345.nq.gz
    ├── 48d348162598b19ede8d48a99906ce5b08c3f047.nq.gz
    ├── 49a8a6a7e2bc9e6a25ab4be8c390b38f62da38ae.nq.gz
    ├── 49c347e4682393bc6136c02a11c035f698cfa862.nq.gz
    ├── 4a34693411e594227267a56c699655f9898ff80d.nq.gz
    ├── 4b80f2fa6e63125373ee42f030c5fd70ad7acb4a.nq.gz
    ├── 4cb4a7f4b48cb75796e3d60e71daa8b58be041f5.nq.gz
    ├── 4d5580eaa49f5412e52fa7742126aa5b114cb2d3.nq.gz
    ├── 4dda45b28f97a93ca78f15287dd59933132d2ecc.nq.gz
    ├── 4e554a0797b607cfa5082c2fe2ff18e68cd9b864.nq.gz
    ├── 4ef429d187719741d650d5842aa009801a8652a8.nq.gz
    ├── 50a1369fb4eea469cadb70664ffd90357b1eb49f.nq.gz
    ├── 50a1a61b96545b1797a6119e9fcc62b0774921d4.nq.gz
    ├── 50beab99e7e462e428c3d15d9e664f753ac9d992.nq.gz
    ├── 50c81ee3788e798e09de4f75169a9b22f6fe8165.nq.gz
    ├── 50d00a356e858173686308409de877d9457338a7.nq.gz
    ├── 51bd94a931505b8792b3eabc571b97a74ef7e1b7.nq.gz
    ├── 52641812711078d4471cab89ce1a724bde6ec749.nq.gz
    ├── 529d220d86e98ee2f46068cd3e7524ebe99a6900.nq.gz
    ├── 52d0d1767a0998213ba76cf71093e10c7b96dc6c.nq.gz
    ├── 533d125fcef5875df72d4d5db8a07ea9a59dfdd3.nq.gz
    ├── 53e58ca7d4694f654b73aec1298b977eb394390a.nq.gz
    ├── 54dc10856cafaf3719f53a00e92f0d205bc526b4.nq.gz
    ├── 55ba09f8d7c7937cf9431134f5a7d5134a2b1950.nq.gz
    ├── 560f32e829d9add1eed93777f5915ba2d790df95.nq.gz
    ├── 56fdef626c0ff06cc75c367cef4f29fb8f773f62.nq.gz
    ├── 579c401717d488cd83be80b81f0e56757b8c4ba2.nq.gz
    ├── 57cfe8c848e198fafe644d1d42cb096bd64946ac.nq.gz
    ├── 5a225c349057fbb8c9c54f79b31208c471033a99.nq.gz
    ├── 5ba7945f0ba2973aecea347447a066967198ec03.nq.gz
    ├── 5c687b1c5d61780e3d8017a57f71427f8286d4ba.nq.gz
    ├── 5c79710f43ccb602343170da888e084b4029fdcb.nq.gz
    ├── 5c94fd917b2f198859fedbd01aac165b3e0e9eb7.nq.gz
    ├── 5d840ff0c62fc9decef920ba347120542089343b.nq.gz
    ├── 5ddb44236d3ff369a27701aca2df8cdb53d383a3.nq.gz
    ├── 5de45a44ecca5e48c8afae6428d431429729f6e4.nq.gz
    ├── 5df0c366facd119a08f24ecb3dcddbe3b1985a7c.nq.gz
    ├── 5eb853413cc033e2a4f03bc407bbe935bba692a6.nq.gz
    ├── 5f4697eff4fb34179a4ed02638ca915ec76e4f28.nq.gz
    ├── 6046e84098991f8a7836affc558187cac0fcc330.nq.gz
    ├── 60afc23f5640b2085787ca3013c2a88674d358d1.nq.gz
    ├── 60f0a9a3edeb1d3cb2122313208c6a372ded1a44.nq.gz
    ├── 61ae02f54998ec9d3400947e525fd88fec3390d3.nq.gz
    ├── 61dca5d53e36e61a0c41773841c6c1ad338d72fb.nq.gz
    ├── 61e5f88de6136e5e634dbc899d9ff5ceaabbd3a6.nq.gz
    ├── 6252153f4045eef6371966cfa3e8493c6a63f054.nq.gz
    ├── 626b0b8c3c5d1899356716a50b1e0181839f78c4.nq.gz
    ├── 62ac6943befe4e702133ed4f53adb1e3eaacaeb7.nq.gz
    ├── 62af78f188c209ee57cec766a5fa06bfd952400f.nq.gz
    ├── 633173c787f79095580844ba883c7cca790542a4.nq.gz
    ├── 63a2a59ea700ad74170efa13f010f2b4fa5c0e77.nq.gz
    ├── 63b75af8ddbede4b260698ee8fad3f4a779a7f76.nq.gz
    ├── 655e27e7071edce40c8db6b0e5f8db1488073588.nq.gz
    ├── 667155ebbae367ed60f0bca3a664ef6b93a95d6a.nq.gz
    ├── 6703d8f11958753e46556570f20b4927550e2f68.nq.gz
    ├── 68576d527c318398e1a66e02b58dfde65dae68da.nq.gz
    ├── 685e5fbc36af6ed5af226c19d1d0859af64db5b8.nq.gz
    ├── 68f02e44ed90af77206784d07efb3ba3e7810b14.nq.gz
    └── 693de7de0cae95b5094703700266093ec8f0a857.nq.gz

7 directories, 200 files
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

[NousResearch/local_generative_agents](https://github.com/NousResearch/local_generative_agents)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
