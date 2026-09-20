# Repolex Knowledge Graph of cpburnz/python-pathspec

RDF knowledge graph data for [cpburnz/python-pathspec](https://github.com/cpburnz/python-pathspec), parsed by [repolex](https://repolex.ai).

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
lexq download cpburnz/python-pathspec
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0ff66291a073efa3daacb4ccace3ce60420923ba
│   │   │   └── chunk-001.nq.gz
│   │   ├── 37e289515fbae7e92077a2438996046e79cae5bf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 39f02a9bd9de3b9b99bba5f794d63d2087a50fec
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3a946678cbf0b634ee7a9b94447b315a7b69cddd
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5d358be3d2067d3bf2bb493c8f74745d812ba9ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6485791e1b5cf2ef4e756ae392fa80f2c5045d4c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6fd6bee628f5f2746ac46939b13fd127941a73f9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 75f4d0672305dfe3d0a6f182b870c3edec29f316
│   │   │   └── chunk-001.nq.gz
│   │   ├── 878be226c5324a4c5470c2ff86034d27c0734d70
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8a7c8fc5a51c81e4d226251405f3aebd669b8450
│   │   │   └── chunk-001.nq.gz
│   │   ├── a8ac2068508554077e9910eb82786cdfe89a9141
│   │   │   └── chunk-001.nq.gz
│   │   ├── a8ceca77caf5d1bfa0b251d4ad19462b01ea0921
│   │   │   └── chunk-001.nq.gz
│   │   └── db3f54e78f68824f641b186bf4a749d944e2153f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0ff66291a073efa3daacb4ccace3ce60420923ba.nq.gz
│   │   ├── 37e289515fbae7e92077a2438996046e79cae5bf.nq.gz
│   │   ├── 39f02a9bd9de3b9b99bba5f794d63d2087a50fec.nq.gz
│   │   ├── 3a946678cbf0b634ee7a9b94447b315a7b69cddd.nq.gz
│   │   ├── 5d358be3d2067d3bf2bb493c8f74745d812ba9ee.nq.gz
│   │   ├── 6485791e1b5cf2ef4e756ae392fa80f2c5045d4c.nq.gz
│   │   ├── 6fd6bee628f5f2746ac46939b13fd127941a73f9.nq.gz
│   │   ├── 75f4d0672305dfe3d0a6f182b870c3edec29f316.nq.gz
│   │   ├── 878be226c5324a4c5470c2ff86034d27c0734d70.nq.gz
│   │   ├── 8a7c8fc5a51c81e4d226251405f3aebd669b8450.nq.gz
│   │   ├── a8ac2068508554077e9910eb82786cdfe89a9141.nq.gz
│   │   ├── a8ceca77caf5d1bfa0b251d4ad19462b01ea0921.nq.gz
│   │   └── db3f54e78f68824f641b186bf4a749d944e2153f.nq.gz
│   └── repolex
│       ├── 0ff66291a073efa3daacb4ccace3ce60420923ba
│       │   └── chunk-001.nq.gz
│       ├── 37e289515fbae7e92077a2438996046e79cae5bf
│       │   └── chunk-001.nq.gz
│       ├── 39f02a9bd9de3b9b99bba5f794d63d2087a50fec
│       │   └── chunk-001.nq.gz
│       ├── 3a946678cbf0b634ee7a9b94447b315a7b69cddd
│       │   └── chunk-001.nq.gz
│       ├── 5d358be3d2067d3bf2bb493c8f74745d812ba9ee
│       │   └── chunk-001.nq.gz
│       ├── 6485791e1b5cf2ef4e756ae392fa80f2c5045d4c
│       │   └── chunk-001.nq.gz
│       ├── 6fd6bee628f5f2746ac46939b13fd127941a73f9
│       │   └── chunk-001.nq.gz
│       ├── 75f4d0672305dfe3d0a6f182b870c3edec29f316
│       │   └── chunk-001.nq.gz
│       ├── 878be226c5324a4c5470c2ff86034d27c0734d70
│       │   └── chunk-001.nq.gz
│       ├── 8a7c8fc5a51c81e4d226251405f3aebd669b8450
│       │   └── chunk-001.nq.gz
│       ├── a8ac2068508554077e9910eb82786cdfe89a9141
│       │   └── chunk-001.nq.gz
│       ├── a8ceca77caf5d1bfa0b251d4ad19462b01ea0921
│       │   └── chunk-001.nq.gz
│       └── db3f54e78f68824f641b186bf4a749d944e2153f
│           └── chunk-001.nq.gz
└── blob
    ├── 00e63a075028626695bc0e36e370d80e97843932.nq.gz
    ├── 013b9a618bd28616b1d87b143ba4012e0deb7e33.nq.gz
    ├── 01bf7d639a114da1b2b889f8101a1ce7ebf70915.nq.gz
    ├── 03b3709f74e38b2b1d79de7083eba7c6aaeec403.nq.gz
    ├── 045a08b7d61a49bc80659be0b0d8b785c8c0576c.nq.gz
    ├── 048741244732fb21a6013223ed2ece5561263008.nq.gz
    ├── 04902d25c835ea07606278fb3c86451cb455f09e.nq.gz
    ├── 049966c00747c3610c118dc3adb505cded173a65.nq.gz
    ├── 04dbc1c0302e90461c28d6c96342ab3e704c49e2.nq.gz
    ├── 081b8da86e0d217d7cacbc96a28e11ebfeedd21b.nq.gz
    ├── 0966c0d7c8c6e25732db7b03862c89acdf2a4b2a.nq.gz
    ├── 0981299d0a2449a9a0c0600f39b207d618a9c971.nq.gz
    ├── 09cabde861fce8d4658e7abd05bb1e2b868a325f.nq.gz
    ├── 09f83e9ba4dbea5901d5ef55370b3e52fe894d12.nq.gz
    ├── 0c3481c5d2798b1f8a546fd495a890276cda3408.nq.gz
    ├── 0cb0caf4363d3f5faf9b6edae9f69748d8e1143c.nq.gz
    ├── 0cf36af893144606015924f3f2214bda96aa3671.nq.gz
    ├── 0d2502d095641a85c845247265b79af6bcf411d9.nq.gz
    ├── 0d86f06375feac70800b94419d1c5ab6a2f904b5.nq.gz
    ├── 0e1dd3c2590b908d1dfa3f28635b7ef629722a6f.nq.gz
    ├── 0f3e76467dd6267f5993ba6678bd1a2ecfacae51.nq.gz
    ├── 0fb44b83a8537118b163c3a8b5eb8bbb7349f5d4.nq.gz
    ├── 103344aa6a5ecbacb12fe0f1cfdf19e306d3274a.nq.gz
    ├── 104117747dd22b64dc998e7404709a26595e9ad8.nq.gz
    ├── 114428eb04421381a7026b8376dfc73ab21280cd.nq.gz
    ├── 12f358d86986ddcde6d2749be1f8bc7bb7ff351f.nq.gz
    ├── 1385fe7065a2e56d8fba28c62b56bb7b6baa7541.nq.gz
    ├── 13ed2ad244c6ba127d244dbad8c4d2e823e24742.nq.gz
    ├── 14e2f777f6c395e7e04ab4aa306bbcc4b0c1120e.nq.gz
    ├── 17788aa21224e1ee25c89b302c988bfd3d30dc47.nq.gz
    ├── 1a0d55ec74d901a6d08460e729a3ea8c321a5cd7.nq.gz
    ├── 1a2be03007a29d20590a489eec270521856179f0.nq.gz
    ├── 1b900b0efb7bd75338b85ba3094cf8faf5deb086.nq.gz
    ├── 1d3561f9acaebc0e7a3f7f7b7e7cedd601e35313.nq.gz
    ├── 1d65322f6447af855ecb832931646cc51207850b.nq.gz
    ├── 212a6e598040500bb14171189dedc6dedd768c1c.nq.gz
    ├── 22157e2295819bd6bd02d20d646e63c3abbd6250.nq.gz
    ├── 23c334b7c7ab3648ea2e4968140a03438db1f21f.nq.gz
    ├── 2428b59122a2ea11a49331a130f8590c2b7ffe13.nq.gz
    ├── 24a84c313d07a2a71abe7121b2d48fddb5af6a01.nq.gz
    ├── 26ba14111fae1325a016a306f8e1f45869cd2179.nq.gz
    ├── 27067d1e3e275e5c2572c828050306a6a1f36a28.nq.gz
    ├── 2a9da7d0ec922ba9c6ec636725f4c6d03262278e.nq.gz
    ├── 2bbc2877c00d35ac8f5688bfbba2b2f24d5e41b4.nq.gz
    ├── 2c58b45d15034ae875f4ff7ad57031da2b3322b3.nq.gz
    ├── 2d99b977cbd0028699832323a72644d9613669ac.nq.gz
    ├── 2ded1be8b71a8d12ca13412cea7dc49cd2ac19b9.nq.gz
    ├── 2e7c8f04ff41c33fea90bea7a705824851a21127.nq.gz
    ├── 2efffb0d99c2498e9e505182d1758bf396e8e063.nq.gz
    ├── 2f71352a522ec5733b8d9f652d70a085ee752b7b.nq.gz
    ├── 301427b41af94a0fd416d5a688772259e3e87c81.nq.gz
    ├── 30426dcaff9a4c987a9fd31dc6ca24f40d21fae1.nq.gz
    ├── 307a064cf541628b753fbe7d17b3509270353d92.nq.gz
    ├── 32b90cc3281a776522e7cc9117b4c87e20407c67.nq.gz
    ├── 32e03f75f93fdb131bb6037b385fc3c87edd8afd.nq.gz
    ├── 347b9e561a78400d265e4b9f1228d26ea10c21db.nq.gz
    ├── 34abfd1ecc98ca363929d92a6833a7990ba28217.nq.gz
    ├── 359058e917767782b8bd4de4e4ecf1be68727e65.nq.gz
    ├── 3757dd4b8e26a4d9da694099664004029bbb70a4.nq.gz
    ├── 377f1598606e7dd2f2bba5deb8098f2bc2b687e3.nq.gz
    ├── 38cc9e22c2bb01b5ef1a39dee2ef40579faa45bc.nq.gz
    ├── 38cf6b64a9ab2f5991c233ca929c81ae9f85cf53.nq.gz
    ├── 3ca69d2f7b32245bbd9801aacf4492becec9e0c0.nq.gz
    ├── 3cc988a42cc748cba48eb7b5bff3328417a02044.nq.gz
    ├── 3ce4456e068e553ee7551dd9d3931ee7d9fb71a1.nq.gz
    ├── 3d272a45a0a2b6d50e531304c0ba280a2a3f301e.nq.gz
    ├── 3d7505e4f15def31015d39e4802cdbd2ce0b5bd5.nq.gz
    ├── 3e5ef468b80d8540926e60dadc26ab22e60f88d2.nq.gz
    ├── 3fa7e08664e72af24b67da43314f10df5946eec8.nq.gz
    ├── 40aafd3857eec7a8a6fd5a55593e8f22834ef119.nq.gz
    ├── 421d8fac24c82c2d8de29afb53d88a131037e306.nq.gz
    ├── 4315dd14ab591a6ca518fa9d8c0bee78c0175f91.nq.gz
    ├── 465b542bfbc2fedd448e0793d7d2806a9b59b246.nq.gz
    ├── 46d58cf75a3b50b39836b601a385276d4c905045.nq.gz
    ├── 4710dbcc7e414e97003d83b77dbc1f712ca16b3f.nq.gz
    ├── 479bd7564a4740124a78a35de8575b6aebff2cee.nq.gz
    ├── 48f3e2bf435a76d58ba8f83bca300a7f34c3bf40.nq.gz
    ├── 4946d7297cfd48e144a622199e170577017b96b3.nq.gz
    ├── 4c12d96cd12c29adf9e46ae02f6f3b3b1cd74ff0.nq.gz
    ├── 4c419fa3307d64b5413f8b439dca1089ca1bc1b8.nq.gz
    ├── 4c7a5199bbb584a2749d3f3a3b546ebcf8dbd12f.nq.gz
    ├── 4d2c74b3d03a1d3594b9ced74884f74707fb8bf4.nq.gz
    ├── 4d8c89d4467bbab7c4bb0907614e6f94857e6670.nq.gz
    ├── 4e4c78278af8ca335c20479bbedf0d49466cf383.nq.gz
    ├── 4e6ae9f8029ab29419ffb8ac0597294c25e6fbfa.nq.gz
    ├── 4fe45e847888c369c3ff9c0790a4a6f74d1cb4c4.nq.gz
    ├── 5222ec0899980236d1ce343e2c6b70e88d7239fc.nq.gz
    ├── 523012e588d945ff4e73ad2595777c45d5884604.nq.gz
    ├── 537212e4b2199a43c9f8166837d4db24700090ce.nq.gz
    ├── 559e09d37929a73a4db1db1f28fb754ba586eb7d.nq.gz
    ├── 56cf793f9a3716b95d6037528a5f5bb80dbb4d03.nq.gz
    ├── 58839511b848d3b9552901b3641818781398fe6f.nq.gz
    ├── 5a036a0d2dfed872f07ee768f52149ffaea7d15b.nq.gz
    ├── 5a9fc2b7860e366116e930032c8272eda1eb6c25.nq.gz
    ├── 5c00086916d0ac18c402688d7307c946114c8ec6.nq.gz
    ├── 5c0ebdf5e765297871861e7d4d922188acbcbb3d.nq.gz
    ├── 5cd9f6144ea91defa4fdc809d72289fe54c980ba.nq.gz
    ├── 5cf9d5f2b3ce10120af4fc2530930ed064855090.nq.gz
    ├── 5d039ae4a31d19f8571680e04b1e46ab0a473973.nq.gz
    ├── 5eca0da6ee019f543d3377618ebd8d76bcad3f72.nq.gz
    ├── 5f1730e0ae7e4dbf72d9e268b05a5d684fe1fcfb.nq.gz
    ├── 5f6dd39d354a0af98128476532a7c951efc44af8.nq.gz
    ├── 5fd89282c59dd68ff5d6fa25765ed9a24666531d.nq.gz
    ├── 61f7a75f71d53e16f2ed39d4b0a52f5f56ed7e3f.nq.gz
    ├── 63918ed987c6c66c5e4bddeb3ede1116b387a584.nq.gz
    ├── 6649eab554a035dd0c9da1ce4075ca82d0f88192.nq.gz
    ├── 67c9b41def10410b83fc804bb6eca7df5fef6b70.nq.gz
    ├── 688222e08cb70cf524b4385937f6bb71e40ea405.nq.gz
    ├── 6a3d6d5eb05a491eeb1ff3af8c4722d493d110ed.nq.gz
    ├── 6a64b0858df03a57240e1f1412e07e58eeb842c8.nq.gz
    ├── 6ab1ca1d0faabdf905450418b672ceccbfa6bf0f.nq.gz
    ├── 6b72375cefef3c9fe6668841ae34abd6a821d131.nq.gz
    ├── 6b805494813ff9111a357dafdf1da4ac143f7620.nq.gz
    ├── 6b990731334099d415e10cfb75c3507aa8d7517f.nq.gz
    ├── 6bd1ccfa230a36fc1f9c2a8107015caffd6c668b.nq.gz
    ├── 6c449002f996b76dcbaaa6b018aaf07bb50c764d.nq.gz
    ├── 6cba91d68f538a63e236874fa0d834a4ea5086de.nq.gz
    ├── 6e83c1039ddfcc03614727eb000c2e66e16d0971.nq.gz
    ├── 6f73571b7d65ecfed02586fb781c77c65a4ab779.nq.gz
    ├── 6fc994dd64f020df3dd2b7ab682fa50e89e6de9b.nq.gz
    ├── 7013f8dd888d0e935ff2ea0dbfc4fae33fb0a71f.nq.gz
    ├── 7212286cb5aa5430e42584e0f861022bb86d4b7c.nq.gz
    ├── 72235ab09215f67bd9c0720661c2dd02d3db1600.nq.gz
    ├── 72b611adcc52135d797c5b0c761628df4470e23e.nq.gz
    ├── 72c49490ddd0003d70f099278e02471bcfe976ef.nq.gz
    ├── 72f1740f9eb740dff48393eeb9bb060839455122.nq.gz
    ├── 7360e9c298534cf77986e01bf568dd1c77a866fa.nq.gz
    ├── 73c33c672a9605ff152793b6c2a647c283eb62f0.nq.gz
    ├── 747d6081df4cbe778cfa71caa3b99e6ae290f77a.nq.gz
    ├── 74d29d8810a08113ec41a5ee5724a5cbc7395bed.nq.gz
    ├── 75f1ed16d2b469d3d514a204f5ab07aed29bedde.nq.gz
    ├── 77c7cd97a79b5e57fdc058c2014bdc24d0a13d40.nq.gz
    ├── 79a72879dd1bfa2a5aaaa16db6cdd4e9a805939d.nq.gz
    ├── 79e447a19038066eb1b91a5cd3d35c60cb42c4e7.nq.gz
    ├── 7a7b10ccb3f82fd1d0033780777c04e88adde5f7.nq.gz
    ├── 7af08e74c5392641b90bbc4ab60c295b4323f8d7.nq.gz
    ├── 7b5dd02f244ffb9bcc16ce9aa4b8ff39eb05895d.nq.gz
    ├── 7cd15d2e240b4832574c297f5f15fc24e2d2f8bf.nq.gz
    ├── 7d261ecff3793217a7c31fd0184cf4cf9b3963b3.nq.gz
    ├── 7d7a17c7e38e26169711db41d247b45cab1f89c2.nq.gz
    ├── 7dccaee1ba994dde36608eb4e027109a049f64d0.nq.gz
    ├── 7e6ea6d4bead73e799c699a9e7394e8badb3cc8b.nq.gz
    ├── 80942a516082a4dc0ab04db8ec745813ead7bf1f.nq.gz
    ├── 809e703c78e6bd5fc74bab9c58d9470ccd1b974b.nq.gz
    ├── 80ca0e8e4501c03f0c443ace10d8f04521e1e74c.nq.gz
    ├── 817661cbffe82d5b340b2ad31756d8d538632fdf.nq.gz
    ├── 81ee2be50e7f5ec28c1c3e16a58d941680f52050.nq.gz
    ├── 824bc8bdd27aea676977f202d1e4c35b354f66a1.nq.gz
    ├── 82d3021168f7d588b630cf698b5a6e2b117ea44d.nq.gz
    ├── 8437becf4229130fbdc8863e315a1b1e1d45f1c9.nq.gz
    ├── 8483e71fc049197b30f08026d161ac7c6d209380.nq.gz
    ├── 8563d959f92d5f7e8d1e195bb7734ed987f1ffa6.nq.gz
    ├── 888b71b8bd16416a4fb3ba33aa08728c5e6276ad.nq.gz
    ├── 899edbf869538201a3437995c499d850fd3ee480.nq.gz
    ├── 8c13dc85994f4fe1b5f29db88d87a27ba03e945c.nq.gz
    ├── 8fe10f276c1f21209b8381901f11b6e87572d0ce.nq.gz
    ├── 908a9bd18db6d39a6feb05145e3672889f486dbf.nq.gz
    ├── 93c3d76a9cefec9b437fa35521f1beea1811a767.nq.gz
    ├── 93f06cee5d0f8558eb0621e3dc29351fdb924e21.nq.gz
    ├── 93f2f6098938537b827fd257e463cb7309944796.nq.gz
    └── 9453880a6f0c9790c0e4fe67d85f53d6a8991380.nq.gz

32 directories, 200 files
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

[cpburnz/python-pathspec](https://github.com/cpburnz/python-pathspec)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
