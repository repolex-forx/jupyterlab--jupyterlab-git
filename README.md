# Repolex Knowledge Graph of jupyterlab/jupyterlab-git

RDF knowledge graph data for [jupyterlab/jupyterlab-git](https://github.com/jupyterlab/jupyterlab-git), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterlab/jupyterlab-git
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b62a87b719cd151a2c60eaaa6a70a6755784c4ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b62a87b719cd151a2c60eaaa6a70a6755784c4ef
│           └── chunk-001.nq.gz
└── blob
    ├── 02581f9400a915c0454981cd1d453533f4dc92f1.nq.gz
    ├── 02dd8ba36e16a400762ef030a80f2e0361d0d150.nq.gz
    ├── 031b50a64d1c4b2689da5ffe93bbc61d9d104439.nq.gz
    ├── 0428badddd51dca37b9599487c5f1d4d6e9d3bfc.nq.gz
    ├── 043499c9e5a0ce1edfa44c636f02fc624aedd31f.nq.gz
    ├── 0465ad79fd349bcdece4db3b891014e353b21c9b.nq.gz
    ├── 06d3e83ffc0bdd3701b9ee62204e6492be7ea87c.nq.gz
    ├── 070b01af8614eb3895afaafb25fbc1b5d6e12d5f.nq.gz
    ├── 07e4ba42c4fc75d0436f02eaa4d46cdd32b7f081.nq.gz
    ├── 088644b4602c8b30bcedbc7b8803897af816936d.nq.gz
    ├── 0a305a8c05f1be9d8f1df978b3f6feca81dd4746.nq.gz
    ├── 0a6074214c466a69b5a8f5927ff2d6df4cb5e9a4.nq.gz
    ├── 0af7070a3763bb2580072fa248a2af945b3c5817.nq.gz
    ├── 0e3c45e9148b09efb0dd75c33bd4b365fd172f57.nq.gz
    ├── 114fca2f140ebfd9a30a3a71b04c62fe91528eed.nq.gz
    ├── 13494660f8fb4960dddf5d96560293fe40d98a61.nq.gz
    ├── 14ef4c5d88cc6792e1e2a5ba25da4889ef6aa24d.nq.gz
    ├── 14fca3f32b91186fa257f08aa29d5391ec610fe1.nq.gz
    ├── 16f36a54b3de287d588382f6fe264f81e34eb049.nq.gz
    ├── 18746659c2f3451e88f8e777140ced57f0163723.nq.gz
    ├── 1a4b73024240e518f0b1f9a7c98b3c1850643d55.nq.gz
    ├── 1ac3b38bd1bf0f03f4051dc8c8e9ee4bd6241a11.nq.gz
    ├── 1b86d24b132302bbcb1a389feba98e1b18e38daf.nq.gz
    ├── 1ee6c9cc947fe7ce86b6e66390bc4c8d7b2d3c3b.nq.gz
    ├── 1f7d067b0b788d08fd9bd02b9c225b7caf6df4af.nq.gz
    ├── 1fcece2b442c29149a6cb5ad311f500571387916.nq.gz
    ├── 211219b84a219e58aad44440e52583e9deca4a1b.nq.gz
    ├── 215c1ce5a00adde7051358b4b58f21bee68a504b.nq.gz
    ├── 2629e2a77938a0128bd65d10235e8865db0caf8a.nq.gz
    ├── 2632f417d14051a25d3a51221c0fa471410d98a4.nq.gz
    ├── 26a2519c89d5ad7f1720bb2d95844cb3309ac8a7.nq.gz
    ├── 28c4bdcaf2d45e216aaa429a961e4161847ad684.nq.gz
    ├── 290867cb3420b0b8b40e0d89d974e58d7a40515b.nq.gz
    ├── 290fb2bcf6900223be44e889e435075133a57e98.nq.gz
    ├── 2cf75aed3d02f973821e873fb47694f0a2ad81be.nq.gz
    ├── 2fe919dd4c18e71d81cb5e5a27e679351f90741f.nq.gz
    ├── 30c076b056586ca3310ee5aed2f4c35020570d5d.nq.gz
    ├── 31311051a970cd51ec0b758fabea8544e88f723b.nq.gz
    ├── 3167e85dd8621e1501411090db50c785c915c1c7.nq.gz
    ├── 3186f3f0795ab612d5508593672dc9ad94bccca0.nq.gz
    ├── 32cf334485ca902aa5388161d3f8eb83099d14cf.nq.gz
    ├── 32fde5709447b80c66c1d838eac62d61811f3e28.nq.gz
    ├── 364d1d0de88fcb30e763a0d14fecfd184ed07aa1.nq.gz
    ├── 375f3178031472e029c8b0fd5486c7cc9c32f75d.nq.gz
    ├── 39032be60384b5b5f6e529966bd94fde974eb994.nq.gz
    ├── 3918e91dff85e65ddbdb7edfb817145517a75a04.nq.gz
    ├── 394725a90d6e3563b202d661ecc180fd5f77c335.nq.gz
    ├── 394a40300ad3af97b036f6efd6848f50a2dfe87e.nq.gz
    ├── 3957deb0db836c68eb9cbe1de12439162f33336e.nq.gz
    ├── 40225f6473bd3636182dbe70878a3cc0ede2c254.nq.gz
    ├── 4146aca1264a5bd9908916e068be97d9b0f37883.nq.gz
    ├── 41adb28e2f5f85a03f48c5ba32eac467c0bc54cd.nq.gz
    ├── 423f96f51ddbdc0c0f504f56192b2cf466bc7217.nq.gz
    ├── 429d1efc14fa5ff4344740e555a9daa84144e7cb.nq.gz
    ├── 4304a9cd79920cccf31567a45a74833c04cff6c9.nq.gz
    ├── 484330abad38fcf13d5cdbcbeba5ec470228fe4a.nq.gz
    ├── 48ec1ddf8e721dcdc25f85544ec688280df44142.nq.gz
    ├── 49816037a93c0913bc622564e9441120dd1402d9.nq.gz
    ├── 49c3e6c952ee12236074e330d99fa0abba50e69a.nq.gz
    ├── 4a11f7f3348f65f80c051a48b215356f3b9566dc.nq.gz
    ├── 4a2ac196bc22df671d15226c07085c43e3f11678.nq.gz
    ├── 4b8a6ac3bba0a63c9a0737ffeec3a74718b50662.nq.gz
    ├── 4d19e0d6259f30afdf2b7836c9a4d90a1d8b4c15.nq.gz
    ├── 4e39d1c1fcd3fbc9cad5e75f13962fb2776fdd3d.nq.gz
    ├── 4fe031d4803a7e48f3c2bc2dea875c5dc08cf8bd.nq.gz
    ├── 4fe40153f53a3057a55b9b3b6be258b9bb081056.nq.gz
    ├── 5086b4410df1a6e84dd596e5526756d001828087.nq.gz
    ├── 51024a7bd0a7df7f60be207092c0883362368241.nq.gz
    ├── 51ca28adcee4b738afceacbf00f97bc1fe10417b.nq.gz
    ├── 5248bc26db6377a42140de7fc81f7be493f5e8ac.nq.gz
    ├── 530f98ac2d7dfdff4e147809784595b13226b0cc.nq.gz
    ├── 54b4af43453c1fec81a2b5f933ebf7327384a4dc.nq.gz
    ├── 54bad92cc8236cc6fc6f75d525e2154f30e56b5e.nq.gz
    ├── 576ea253a438100b51fa0b118e3445fa62d0381b.nq.gz
    ├── 5856cc84ad4f5327281401fe566c909036d4b2de.nq.gz
    ├── 5a74bf0be1cb551c59d6ab099895e01193b4c9f5.nq.gz
    ├── 5b681a1e5cb8214542478c905c6738740689ee01.nq.gz
    ├── 5b7a487a26bf12557796b40ec0d8e197c627d53c.nq.gz
    ├── 5bd49512d3ff419f94a093756d54c64e45c6af77.nq.gz
    ├── 5cd8b46850d7ec303f5677987015c080051dd3e4.nq.gz
    ├── 5e3db64c6ebf3e5dc39ed024ec2cc5d61a2c435a.nq.gz
    ├── 5f6040c909af24d79eaa01a980d090f6f0b06bec.nq.gz
    ├── 605d902abc80c0c8cf19f2cdf7451f9d88961b55.nq.gz
    ├── 62410dd710b6b11c8fecf248aad5c358d3f3f4a7.nq.gz
    ├── 635611c7703efd63bb6591db66354900a94bb2f2.nq.gz
    ├── 639b835ed14cedeca8a71d2441d5b34dc5b66e29.nq.gz
    ├── 66b334f7a6c34572b9d9a78cf51344d125532fd8.nq.gz
    ├── 672997d01515d824236504ae32acc893ba4512d8.nq.gz
    ├── 67ecd988641591ea0ab8cda684d8ff78e9157810.nq.gz
    ├── 69e1ecbc3060da9dff26f8f91098449ec76098ea.nq.gz
    ├── 6a55bc2c4cbf24262aaece00c7eb3457494de723.nq.gz
    ├── 6a8411fb7dd89da46218344cb6fc85b7b5a5ca96.nq.gz
    ├── 6dd528a7ac312ad1f7733178406b6351b645b88c.nq.gz
    ├── 6e8ed10358b7a952f1d5996d3cb838ff630beb48.nq.gz
    ├── 6eacde90af41356c36286cedf1af9ee2548bd74d.nq.gz
    ├── 70400859c0a03a11d30a1bd04df284fe4bc77037.nq.gz
    ├── 71104126a2b05857709810e4fe80607f66079f65.nq.gz
    ├── 714405d182435315359e709acb30a309e7dd09f9.nq.gz
    ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
    ├── 72a520cfcb6d560b2c833953940939b2b79c8915.nq.gz
    ├── 72fb4a4a961cc5c56961eb0f7c5c234201130111.nq.gz
    ├── 73ac50ad35a20c6daf911b7f4dbd88647d67ab8c.nq.gz
    ├── 76dd066a2dd3bb1bca205d6dfeeeb59205cdc0f7.nq.gz
    ├── 775ec437fb3478e15fc68a8f59cc656ed19f0c0f.nq.gz
    ├── 786d80ec06e1b941754d67a0300c783ac241f46c.nq.gz
    ├── 793884fcecf640b04fc847b1dbf358bef17aad71.nq.gz
    ├── 79e6c32289e98312c0449b8f150b06f40063bac6.nq.gz
    ├── 7b73d975e5d55495f616f737ac0f942a6aa0432d.nq.gz
    ├── 7ce55c9f8c359eba55522877f610f8753713f336.nq.gz
    ├── 7d4e842c43c4404236a7acbd17dc3ef245eecf57.nq.gz
    ├── 7e59934df038d051f9c196f40d97b6eea3d68922.nq.gz
    ├── 80dcc0a8a51ce69e6e194ee0ee090bb9691a0b7d.nq.gz
    ├── 8438b60571ea97d75eed41496d71b7cbb31028e4.nq.gz
    ├── 85e2c267b4ab0f8e842b54d7ac0fef0608558949.nq.gz
    ├── 85e87d5fcbd5498b8b5d42a2cace68960051f8e2.nq.gz
    ├── 86aef60100089667a1c9cf7ff6790ca3d5f5b1ad.nq.gz
    ├── 87099271ef170f8df77b435d17da56c40cd71bed.nq.gz
    ├── 877e44f0721c6983e9f696f98837826e67f0701b.nq.gz
    ├── 878b400eedc4320b819278291e02ab97cf7d7a64.nq.gz
    ├── 878ff125bdc21c568180be88472373d7300fc774.nq.gz
    ├── 87d3c20ad2e2a08df082ebc04c3f6bbe31fde683.nq.gz
    ├── 87e9cd29b58fdb1d83807bac61659dbaf58e1370.nq.gz
    ├── 88023f02e541b6b76aba1a31ff7fa99477b943cd.nq.gz
    ├── 88c7660326883d93cf36866d77f81e8d747e7b05.nq.gz
    ├── 88e4e96b1f099ba938b7ccafc4045a049ed545e9.nq.gz
    ├── 89a13ba41346c7092682ec858781858ede25f48f.nq.gz
    ├── 8ace65ea29a810277aa9c451a3208feb36bf1d1d.nq.gz
    ├── 8b3c961626b056e06f9c25c746ad701ad038d576.nq.gz
    ├── 8b5c76420c6070a63b2beaaa99d96ed45aa3d30e.nq.gz
    ├── 8c19cd1cb805102994c1c83d89c159ae1b9f5f92.nq.gz
    ├── 8c80fd91df15a68e4086fc50c5397fdb198660a9.nq.gz
    ├── 8cdaaa495e7dcb15a89358de24b1820f688671f7.nq.gz
    ├── 8d04ade9955cb6ec16cf18d79fe99ce8c64dd771.nq.gz
    ├── 8ddbe3d4ba14150e8fb6f42a1da80ff2bc1a04bb.nq.gz
    ├── 8e47cf29baaa2e7de56200145d9f73c0f9d4e17a.nq.gz
    ├── 9059e01b41dc1c7504f8ddd09ce9b456c00d92a2.nq.gz
    ├── 942fe4143178b5e9af40197872e179489d2096cf.nq.gz
    ├── 94a57c1bb91dab21fbc1c9276fe28237d015a936.nq.gz
    ├── 971ad6eb5c799c5b04d3b766d82c49a52c0365f7.nq.gz
    ├── 97f3490e43c6dc2b5bb1668522f471a2721f17ab.nq.gz
    ├── 9820d7aaf0f6ef2f64464323a96c8d672453919b.nq.gz
    ├── 98524d4820bd16f06c583166d99bb6491b3e0635.nq.gz
    ├── 988d59014ddbff5de1877c41d1082708a061af0a.nq.gz
    ├── 98e15c0f0c6c49babb7400d243115b339c2c44b7.nq.gz
    ├── 9a03ea4081127053418b2206a5d83e1db2950922.nq.gz
    ├── 9bb58a2925c0bce9bdb29d960c52a7fe868ae50c.nq.gz
    ├── 9d1b45d643f31138adf1228ad52383932b67edb5.nq.gz
    ├── 9d33a9660c15504d13d78064170d60c9a10a3ab4.nq.gz
    ├── 9ece6fa1106d1ac93f9b405274fd36e00355ecc1.nq.gz
    ├── 9efc0d37a4529d3e1a6c254a9ba580ebe60d9682.nq.gz
    ├── 9f17f810e643b8192f088bde635c964066028cb2.nq.gz
    ├── a028a76408bf46181259249b2e15e14a9bbdf7f1.nq.gz
    ├── a1b8004333d40202c3948e50746603e6ba14069f.nq.gz
    ├── a1ebdb295633debde6d15a95df98798d5154b997.nq.gz
    ├── a3f6a0cb9af33011474369575f917ea6029d2b77.nq.gz
    ├── a46860636bfac2fb572af8c818f509799bd5d9ec.nq.gz
    ├── a4acd917250d6939cbd43b8cae2ea64bc5d68a1c.nq.gz
    ├── a4ee2bd531d6f75fde34976e0e187dc5fbea088a.nq.gz
    ├── a51954b5e6d43421c0c824918688029507bd2030.nq.gz
    ├── a5d552a732b879e20ecc060a3d1f2ee8a3fe1261.nq.gz
    ├── a7d80cde593c9c0156201b5c728359e87e8c701c.nq.gz
    ├── a7f29ec1a55ed18ec57a088c0cfbd3f399032ba1.nq.gz
    ├── a83cb2b75b8c0bf4d1782ceabbfd7e851bc35e6c.nq.gz
    ├── a8480584d3616af15c63ffea79939ff76c2741c1.nq.gz
    ├── ac041986063f838ff0557dd8a05f69f9a3edb688.nq.gz
    ├── acd050e083b0c582e994c16c55822e2d64523a7c.nq.gz
    ├── ae1d24aa50bac1ff23555b693faae8c29f8c2dd5.nq.gz
    ├── ae2d8095206138f20e4c20444e796e7a6507cfb4.nq.gz
    ├── afb077d7588ca5cbb769777811dce4106b884934.nq.gz
    ├── b119c629a3cc1d840d8b91fb12a594559903cd69.nq.gz
    ├── b14ec163f5cde3594239113b381e6fe40a0af3fd.nq.gz
    ├── b365082fcf224f9028a7f9248028aaba1bf0461f.nq.gz
    ├── b6027ec09d6e1f5c64539a7c510443bf5816aa90.nq.gz
    ├── b71c8ff8b5bde16dffe0ca63a876f177aab173bb.nq.gz
    ├── b803d4b133ef0cd835cf07f9f99122cc63530563.nq.gz
    ├── b831827d818fa92f6b55c2781e9e117fe842df1f.nq.gz
    ├── b89f07394cc587090cb6bfa56ef1f0a185ae8e8e.nq.gz
    ├── b8ed115023664baa607ccbe42123f9d8a07592d6.nq.gz
    ├── bb2cdfb03af615b335b1d872ba6d4fd613a2adf2.nq.gz
    ├── bb917da38fc6dd21b0a03d48a668aae9f87b1570.nq.gz
    ├── bbce4c8fdb4a8c4cd11df556064c4fff329be6d9.nq.gz
    ├── bc05994edfcb42c813513429337c777bab026d98.nq.gz
    ├── bd45e2311a407ddb1bf7c25e9a3abb026708ec1c.nq.gz
    ├── bd8c463403b6a814a8405d2ee8aefad5a4870f6d.nq.gz
    ├── be4db4668723da329e52247a81d5b9ebafde10e7.nq.gz
    ├── c106462bf29a0179109b10224291eb97296fac78.nq.gz
    ├── c162239e6b079b586961f83486c43cb06646df11.nq.gz
    ├── c1881060de286b6e65824cf42d336f09ad37ce7e.nq.gz
    ├── c32a8f7d7d7dbda06a8b17851bc45c43518a7d0f.nq.gz
    ├── c4b99dd8ce8a40eb4dd3caba110561c507f8fc37.nq.gz
    ├── c4e38666a411e57703ff7acea241a01bdd4d80d5.nq.gz
    ├── c51596222dad56eeffdd36cc18e617f4166d7ef8.nq.gz
    ├── c7adcce5a7167116c988fdf7102862a3a1548c22.nq.gz
    ├── c96e64d34131647319f461e3273c6091636bd700.nq.gz
    ├── ca241b5603642386f6efb0376c183dfc67cdf690.nq.gz
    ├── ca32a46970976440c590a452bdace6d232ef1396.nq.gz
    ├── ca6ec35c00ff0e9c506234913d93681ef90438de.nq.gz
    └── cb823a3b8c39e03570e3819354c1e9aded67d829.nq.gz

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

[jupyterlab/jupyterlab-git](https://github.com/jupyterlab/jupyterlab-git)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
