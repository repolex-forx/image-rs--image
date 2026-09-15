# Repolex Knowledge Graph of image-rs/image

RDF knowledge graph data for [image-rs/image](https://github.com/image-rs/image), parsed by [repolex](https://repolex.ai).

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
lexq download image-rs/image
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0307a47de2ea14eea8a497a859724e7ee005773c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1028cff98b00c9f20c6ab1e6098bbdf6da70132d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 317bc1692c134d750360ca9c8e108a08ff534d93
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ceb6af6c2b6671931a02fda955ce1676321711d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6edf8ae492c4bb1dacb41da88681ea74dab1bab3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 76e57184f22772dad1138e96954e57945406b15e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98b001da0ddcd91936a716696fba877df910b61d
│   │   │   └── chunk-001.nq.gz
│   │   ├── a24556bc87457086b10d02d685a2ccbe66f261ac
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7617037c8e05eb538c55799622855db37c26d3b
│   │   │   └── chunk-001.nq.gz
│   │   ├── d2986070139b729cd2e1305d49a91d8596ba64bc
│   │   │   └── chunk-001.nq.gz
│   │   └── f337e27aadaae8b86484429bc6020fef8a019c95
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 1028cff98b00c9f20c6ab1e6098bbdf6da70132d.nq.gz
│   │   └── d2986070139b729cd2e1305d49a91d8596ba64bc.nq.gz
│   └── repolex
│       └── d2986070139b729cd2e1305d49a91d8596ba64bc
│           └── chunk-001.nq.gz
└── blob
    ├── 0013be17dce540ed34a415f0204708588d83fb8c.nq.gz
    ├── 00209e7bdac624d14b38dde0efa3e10fa918e7ad.nq.gz
    ├── 003b4ab4a40ea3345c4aed59bb5a1bb9dacc58d0.nq.gz
    ├── 0075ed1c4fb9d0631ec4850c2b6c0df8b0a1f677.nq.gz
    ├── 0172c3a2f00a835e20e2b25d10a94e2fdd350fe2.nq.gz
    ├── 017ce58f64c3cc65097ce926787589fa1f2abc75.nq.gz
    ├── 01bbd3284dc25592342c5b93fba785071b20c6ad.nq.gz
    ├── 01c2c54b44d2b5f76c305d436c71c903c92b714f.nq.gz
    ├── 01f9f96d0d07f36a1365b5c5cb40814e91e2c358.nq.gz
    ├── 01ffe5f0500d40b1983f1f7163f6919f526f52bf.nq.gz
    ├── 028f98a70a19183c52fa78ba1d6a897da1bf6e35.nq.gz
    ├── 02eb0c7d8eebcc4f866646bc47f6c7d555735904.nq.gz
    ├── 035b02cb885f89de32c4eea080e1d98a285dc3dd.nq.gz
    ├── 03ea9ee9d8e938fe0f235d23543b33287b22106e.nq.gz
    ├── 03f16e7b004d5f0770fe89ba415cb8250289caa1.nq.gz
    ├── 03fc25f1228a349f1517364d5ce2b60843fd5de6.nq.gz
    ├── 04c7bd3f6b3dbc73f7ff88fe85b27b8a691e3d8d.nq.gz
    ├── 04cb06388833c65dba8e0c44b7bc9dec5d141abc.nq.gz
    ├── 04daab8e4676914553bb5fc152da92a75834c679.nq.gz
    ├── 04e43f666ae175cc05ea55f75782a091e3e21320.nq.gz
    ├── 051f0a7f001f8b7e24e598184e23d0b92fdd8c84.nq.gz
    ├── 0529609306b9061c812c32e71ca001b35b6a2d73.nq.gz
    ├── 055f8712ce217e3ed2320523836327c3d4a6bf0f.nq.gz
    ├── 05a4cdb3db706a84022cc781c07e1a1d9b5ee296.nq.gz
    ├── 05b845ea7468bf19bb181f2babf95552c75dcd36.nq.gz
    ├── 061062cfdcfac54d7c34796495ecbcf3263baf69.nq.gz
    ├── 06ce9401e4a7153d78c6d46bfb1c9dec7ed9f21b.nq.gz
    ├── 0719630083a99263f724ccdb2ad29dfc9bfd60cd.nq.gz
    ├── 074be924ee1d0e89198a087a30640cbd1b8b4512.nq.gz
    ├── 07863d0d92a3a899c68975c9b12cbd710589e670.nq.gz
    ├── 078d5359205508dd28ce9fbf09948b89e3e6598d.nq.gz
    ├── 07ee275f2110a5a258e21c9614284d69b8c1d7e9.nq.gz
    ├── 07f042e6b3be8ff611ea50bb993e6af2a3f90fce.nq.gz
    ├── 0822e327ef13449cbf1933f80c0ce1772c05e0a0.nq.gz
    ├── 08366ec82ec5598d07b23675ff81b499a1784c18.nq.gz
    ├── 08421597da0d565f13ce652d9517453d7aa5b037.nq.gz
    ├── 085e5f44b5c9dc5fa361bdc58bbce08f11b6d1eb.nq.gz
    ├── 08625f684086654f4920caf970f1a3e0c3177055.nq.gz
    ├── 0865ebdf80175cc88375d99d5fd83055c53002fd.nq.gz
    ├── 088b6d0b3e9a72fefab8cde2f03f4f67fb52cd9f.nq.gz
    ├── 08e87f0f561ea27bedab56cacd1be408ff58762c.nq.gz
    ├── 08f79ebe32eccc649687d58fc584ef8a4c543e03.nq.gz
    ├── 08f82475b91effa07d7dce61d50dcd808af17955.nq.gz
    ├── 08f8483d5f5e58e7c8101e0f7c02b1f67c9a61d7.nq.gz
    ├── 090ab30238098a3786197a493a3b0e5c97dbdf76.nq.gz
    ├── 091dc1e967d81de1d42335ed5c51d7696e549e5e.nq.gz
    ├── 091eea2700111028f0e712c5163228be0ae31d0a.nq.gz
    ├── 096d323f7dbcd2903e353058b9184b2315549653.nq.gz
    ├── 09dada98b3b5eb70ae736084c5f48ad071a8e5ff.nq.gz
    ├── 09ff3129133e9752a2ce21f797e3d48cd35f0712.nq.gz
    ├── 0ad4cf613d26138328047398a6e997b0c981f44c.nq.gz
    ├── 0b26dcc31357ba75dda3d1145c50af2a843b53a9.nq.gz
    ├── 0b95b657284b6f06431251b21f0175d9b8cb01ae.nq.gz
    ├── 0bf62d63cd0a4c9f65717414429234e26e10571d.nq.gz
    ├── 0c27ae3b0229f1dfd73bdde395ac7143f0e5c2b2.nq.gz
    ├── 0c944d8256a8e205456d42d4b88c15edf0e82e5a.nq.gz
    ├── 0ca398655a72f0ef7cd36121ef0973e8a8661290.nq.gz
    ├── 0ca4b2aaec5536275dc8825d0f60f628eaeca553.nq.gz
    ├── 0cacae9a55dd9f3d377eed5abe6641b0e3fa8f0b.nq.gz
    ├── 0cf1fe1b5495589113c98825687d11d9167ffb45.nq.gz
    ├── 0d35566270d2bb8db000c58fae4aa64cc9af058f.nq.gz
    ├── 0e1835f3f95f112dc6f222312c391b9a2549fe44.nq.gz
    ├── 0e6bf032075957f957c07483bf03a9ee04f4083b.nq.gz
    ├── 0e83924075ca7caa7c05db3da64e40e0d50ed3f1.nq.gz
    ├── 0eb8b2915eeccd50447354eb13c0eb861765daa5.nq.gz
    ├── 0ede3574db0fd51fa9266fb1cb91df3888dc8dbf.nq.gz
    ├── 0f74b5038ea2bcb9b8197bd9a439e41987652d5c.nq.gz
    ├── 0fe0405a84765efbfdee7384c5e4e94324169d5e.nq.gz
    ├── 0fe60157b3a4c7a9d916f504846256ce612df74c.nq.gz
    ├── 0fe79d77d3d46055cdbc04c8545377f5f5e55f1a.nq.gz
    ├── 0fff66f13fdbb1422013ec71e9b268ca2c059c39.nq.gz
    ├── 100e0f150ecacbb72f81d4b5fcfcacd14faece17.nq.gz
    ├── 101e0b49437ddcdfdf8d2c94d0644cd767d18d83.nq.gz
    ├── 1027611858337fff9b5a47637d751e7f3d3b404f.nq.gz
    ├── 103c07be505dfe5a6754f7b304f4b473744c6cbd.nq.gz
    ├── 103fd360d487c4938f140ab488b68ab587ae9147.nq.gz
    ├── 108f6e1a64078e8e0362c088ea5741b20f6c6710.nq.gz
    ├── 109470cbf8ffc34889b5161dea7f155586ed530a.nq.gz
    ├── 10950ce45b25d5d3e6cc28198ce9837d4364cadf.nq.gz
    ├── 109d00a58fb6e73583d9f553dcc0da00edab35f7.nq.gz
    ├── 10b161be37d3528c93cdcb7c36c6f722e72ce8f0.nq.gz
    ├── 10f547545d33e806a3867869e8120c2a370aa0e2.nq.gz
    ├── 110b9e715bf446d9e836e079cac017e327d5f577.nq.gz
    ├── 112082e495ad08f9e7d91ee36eec4f87e803a260.nq.gz
    ├── 11216254fe8b46d5f3372e2deeb28ffe3a2daf4b.nq.gz
    ├── 11493ac2200826ee9f6c8970def0befbf4af4ab3.nq.gz
    ├── 1182b458c65cc807acd0b36e1d9a1296da3248b4.nq.gz
    ├── 11c0cbfa00f631c2471971eb6fedad0b07b2254f.nq.gz
    ├── 12215b84c1757efde59a9ed1b886e2a309f30e39.nq.gz
    ├── 1224b5b6f22ac4d64dd3fca035144f89e1baa494.nq.gz
    ├── 12250559cfa2ec9682b8d36ae8db102f4fcc3f7d.nq.gz
    ├── 12a349e3bab29c59b6b18392476363075f0ef1ea.nq.gz
    ├── 12fa46e20da2b5ccdd43589c5a1c5c8103d3001f.nq.gz
    ├── 1375aa84e23dbefa81516937fa14d796e5e7aea7.nq.gz
    ├── 13a9bca3651acc77b13927512cebb164f7616d26.nq.gz
    ├── 13cbe87a50d153e7731e45c8b7a905d09f02bbeb.nq.gz
    ├── 144dcc4d3957c0ffe8f4f7f13f59e6006ceace18.nq.gz
    ├── 14866a512513c602deaa56dcab46a2de402f4378.nq.gz
    ├── 14bb091e4604ff5eae54dc61b1cb061ede11f212.nq.gz
    ├── 14c83905ca4427817f8e0502ab37a2d5b152a7be.nq.gz
    ├── 14f12d573200082a2f7dba8c78495ecef710e75f.nq.gz
    ├── 154ed08bed5bd4cf6bc6a3dac39456d0cd57be80.nq.gz
    ├── 1581c3795b4d66be19bf6c1a5612c2b1d9f80a4c.nq.gz
    ├── 15b2244b0958039c2fd00a5eb2ecc45564857356.nq.gz
    ├── 160bd5580d05fd5eccd8fd38bc56ccc696398a97.nq.gz
    ├── 16243cedf0cc5d15f44183361ab3561248872ac0.nq.gz
    ├── 1684dad414d4f5dfad70292ffa2f6b7b8446ec80.nq.gz
    ├── 175c5be8074f5fa67f9e6fbbe3ea92923b38b88d.nq.gz
    ├── 175efbb838f0c0b4287b5b7d10eff4b0d8a9c6cb.nq.gz
    ├── 17a7bed922109e44bffc9ea6970c5143aa0ae666.nq.gz
    ├── 17ecf8ecd3538f8c46ce111843a64a52aefd25ea.nq.gz
    ├── 1810ce8bd5959c2ddb44d0b4016495c1df03b041.nq.gz
    ├── 182268d156dc248ea696180ee804fdd52da20c59.nq.gz
    ├── 1851100b1e862632de7a20500a886d7c50adfed9.nq.gz
    ├── 1939dc12864dec673d42ced2af54b5d8674313d9.nq.gz
    ├── 197092d539b781544af842ff9a231276bb5b1287.nq.gz
    ├── 197d6690c3206903da8105aaed7642793303b004.nq.gz
    ├── 19fdd1855db22fe45a3c0d7125c757d8f62906fd.nq.gz
    ├── 1a1645317678a2e1a3abeb671f065a63cf3328f6.nq.gz
    ├── 1a564230e2d5ba16a90581ca111a1448ac2fa00f.nq.gz
    ├── 1a77ed8ecabfb963d6372b654561c0d07848a365.nq.gz
    ├── 1a79fdc8c03b332c715eca84b153a3151e4564a2.nq.gz
    ├── 1a8bb054312f74d73906a3f20eecffdec4110984.nq.gz
    ├── 1aed9bb327259e9fbb30f53fe9575b449e9eef2c.nq.gz
    ├── 1afe1e6dba10722b4768f7d174ee399313efc6f6.nq.gz
    ├── 1b1f7306b53dc4cfadcc881fcbace923031ef9ae.nq.gz
    ├── 1b35084a369ee5d40908a70e01ca47fccb144ce4.nq.gz
    ├── 1b512d341cf28192b6c185c095268384bf5b7b11.nq.gz
    ├── 1b655bf9cf241d4fea11ec3ebe7215bdbab7a689.nq.gz
    ├── 1bb9d24130b1e99525ea35a4dcf0b5f47c4e9729.nq.gz
    ├── 1bd12295ce41162239f21b357eac13a5b30baa59.nq.gz
    ├── 1c091f4aba0965747b3f6ea6be69adf2a59023f2.nq.gz
    ├── 1c1bfea1d31bae45f4861905490a19602b2a0927.nq.gz
    ├── 1c619c6fb1b8bd262d7966c59171cf4f1205aec0.nq.gz
    ├── 1ca01a9b523c0e0414607c4130e686f035078c43.nq.gz
    ├── 1cddac2c8bb1b38a199ad6587b1524bb01f0c363.nq.gz
    ├── 1d809d1d002cb3d6d4ae1efe0278941783f52d88.nq.gz
    ├── 1db72c3fba2ca6198c1fb122363c509750fa09c8.nq.gz
    ├── 1de417b5123cac58d1af1351c3572d86b9eab42d.nq.gz
    ├── 1de6d63462ac0684477200bb3c6cb2934fbdb755.nq.gz
    ├── 1e142c4165ee203c79c93e36364b91c49a0ff7c5.nq.gz
    ├── 1e7f324e930e3670f6cf6c7cc1b988c33856f62a.nq.gz
    ├── 1f0e650d6ef489d83e2317020e4f7a7bdf257ba8.nq.gz
    ├── 1f20191b928ac0d2c0849f144ba4aa58504db22b.nq.gz
    ├── 1f6ce53a77ff9a49d260411e89a79462b68dc3e2.nq.gz
    ├── 1f764fa4ada926029605ea4cef4f06e219439634.nq.gz
    ├── 1f8efc2cd9f4e00d8e4c025e128ef0800a6e3cfe.nq.gz
    ├── 1fccd26d5439fe927c807fc21edf7731006a1b07.nq.gz
    ├── 1fdc03ddea4fe2805e7ffb410972f7dc7fdaa02f.nq.gz
    ├── 2002a27f14121e61040d897967e8bf6528c4c8e9.nq.gz
    ├── 20632ff8d4faa48a59fb94a3bb2102a6ead55558.nq.gz
    ├── 2067b59c3ca10cd092e13126ff563b9e6d911a3d.nq.gz
    ├── 20a96887d5b5ef917cdb93cf94fccb814c207a1f.nq.gz
    ├── 20af7d733ba3fe8434ea3890531b257c27c8beaa.nq.gz
    ├── 20c0f8e4c302c82b1eb0b102af742a06a3b2f1e8.nq.gz
    ├── 20fa9a1326bccf03c925678e561183dd46586ad7.nq.gz
    ├── 214e99ba1ae8a28955b2fb39305c34f56f76725a.nq.gz
    ├── 2152063b730a17fc7eded28c9cc937a12bb07f2c.nq.gz
    ├── 219453dc8fc642f002dbb550030b33a98a3716c1.nq.gz
    ├── 21a909fda9ec586632f5cf3e22ea2f8d3c9f5948.nq.gz
    ├── 21e9dc7588431aed03926a380cdebb3d6837085f.nq.gz
    ├── 221a709b32fe23b342f6994edf7ed0114046af41.nq.gz
    ├── 245defd04575e0a36a2beccf1e53b2fce65a4193.nq.gz
    ├── 247e1ae3ece45ec01824e97ee2e6a54590f1fc08.nq.gz
    ├── 24dcd5e38cfad41bd509c20d13ed87fef8b3c709.nq.gz
    ├── 2509f94c8215fb2939dad92c08676a5df43c4384.nq.gz
    ├── 25668fac0d2d02a6602dc1c0a2603a5ab3db97a9.nq.gz
    ├── 259bd81100d79a8fc8b6d134e77c29f689af7cf3.nq.gz
    ├── 25bfe60dfe69a91e97eb539c631113822014d1f7.nq.gz
    ├── 26212f60a38aa989bda16f4536c0bd846111a3e1.nq.gz
    ├── 262ff38d6f09a11a712840ef1f68b66890562f6a.nq.gz
    ├── 263ac7d11b2ac3d5ec055010d7d0bf03bc7d3b63.nq.gz
    ├── 26598d54e98fba7306693438703beb6ed0943f34.nq.gz
    ├── 26687a70722a87e65dfd563114dd84d28c414762.nq.gz
    ├── 26740670e16c8287c293a379f35f9e43366daad6.nq.gz
    ├── 26d6cdebb9e479bca5a474d0212eee4b9ecf2238.nq.gz
    ├── 26e8d64ae33bfd382b8a6abbb837650782301120.nq.gz
    ├── 26efc3364eba8d9c96fce23893e56210be60a62c.nq.gz
    ├── 26f60123285ac3c56ab9515ef90e85141f5422cb.nq.gz
    ├── 26f704fdd53be8a1a99cb7c7ed83285888a0d7da.nq.gz
    ├── 2728f7f0669ad6a900feb916a454a6f1b8aa5d07.nq.gz
    ├── 2747afa799e0dabc7f5b13b8d3ad1e4d30e20711.nq.gz
    ├── 2786c5c3f4cf782455fbe8ce224fc37e2a00d9ff.nq.gz
    ├── 27a6b29ea0da979686dbf5eb6039679bfbdc10d7.nq.gz
    ├── 27dfa60ffe1d61b8a22096caed2af26e81bcde25.nq.gz
    └── 27fe7276bc7c58cbaf5e99f84f9adbe19ed707d2.nq.gz

18 directories, 200 files
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

[image-rs/image](https://github.com/image-rs/image)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
