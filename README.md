# Repolex Knowledge Graph of ansible-collections/azure

RDF knowledge graph data for [ansible-collections/azure](https://github.com/ansible-collections/azure), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/azure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7de0d8a6f0f30f11f28386c6117d8aed382db8c4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7de0d8a6f0f30f11f28386c6117d8aed382db8c4
│           └── chunk-001.nq.gz
└── blob
    ├── 011cc7c1608e9ee8f96f7b6e5df03587f72b28b9.nq.gz
    ├── 019e8163843f0030a1be66a1f8845dc0541c90d2.nq.gz
    ├── 01b53a07786a5dda46746db9b49527f9abd47b21.nq.gz
    ├── 01b5d4e1ac8a21f4121304a9404d38c7c8e29b5f.nq.gz
    ├── 01dda868ea42a517878b3a1eca5bbbec2163c6cf.nq.gz
    ├── 0238020c0b8123d9fc5aaf6efd48b98c2fc5a17a.nq.gz
    ├── 02ab1ed4089c6abf6bea5d6a0e3a00f6d95254bb.nq.gz
    ├── 0324b65ff60ba6eaa102e68a10f62083985d22d5.nq.gz
    ├── 07342ca8abe5a7af875b20518f4a337ccb693917.nq.gz
    ├── 07e18deac781af0626b21aae8c35c93f03b3a5b1.nq.gz
    ├── 08154fb21c0f0c15afe57f64affb60908083c30a.nq.gz
    ├── 09543d2327bc2aa83cf6ff1086ca344cf177e773.nq.gz
    ├── 095e5ec34795129b5bffc77bf01249baf8881713.nq.gz
    ├── 0a7d5f08515c47b30494f56648b0d1179bd50c0f.nq.gz
    ├── 0ab070c45d42ce57d2030a99860ed973aa1cb479.nq.gz
    ├── 0afc7e2aaead0dcda71ef83e3585fd4f56a55142.nq.gz
    ├── 0cacd9de925f841acb46d3bd2ea9c0c1e4b601d2.nq.gz
    ├── 0cc5135d0b9a1ff5904df42fcacf4182b8bcb31b.nq.gz
    ├── 0d494579f5954cd8eaed17e94c2ad335620ccae4.nq.gz
    ├── 0dbbfcebabe67ca4152bbf1237dc08cc2a41998d.nq.gz
    ├── 0dfa133e9c2fba6b1c145b877445680da8326884.nq.gz
    ├── 0fc3c1f9e7fd29a52449a9043c36a8b7d5f6632d.nq.gz
    ├── 10756bc989b75810b00d20104d640e9d541b5042.nq.gz
    ├── 10aee79ded520baa1d20d571bbcc264e33eafedf.nq.gz
    ├── 112023b42d5a19a05126538f8cb8730087631b7e.nq.gz
    ├── 112d3d3d4c741d5e78717b3be861c491478c574c.nq.gz
    ├── 116ae96ab0af12250a3c9dc4c6fd1135bf89a2b5.nq.gz
    ├── 1191ed2b2f191a3df439c9edd22696cd872b4dff.nq.gz
    ├── 120bd927d14654b5241d128dbee936bb0807c79c.nq.gz
    ├── 1321533fcfad76c4d811126c67026d9b65171369.nq.gz
    ├── 132201187f3d285a2bda25990ecdf332525eaf64.nq.gz
    ├── 13a299dbe5488d0911127d2b8a60142347179374.nq.gz
    ├── 147b3cbdce563a597a189b1286330b9fed46101d.nq.gz
    ├── 14eb029b4785aa12d1a668953e806980dc016cb1.nq.gz
    ├── 155c9bfc2a1278026c38bc7d5cf0782d6d4785a0.nq.gz
    ├── 15e3b67f69700d99ddbc2a4c3efcb5b5d5abfc0a.nq.gz
    ├── 164c752cfea3440e9d0c720f58aa1f0e98d97ab9.nq.gz
    ├── 1680c50b43f0e0f62c87d17be6e60606cac6ce4e.nq.gz
    ├── 17456633d2433c968a8ac4aecca1150da8505a42.nq.gz
    ├── 18b09824024ab1b21266c76aedc22cf0c3b3247b.nq.gz
    ├── 1904bc7824467bfbec0378140ceeb2a78fb00d96.nq.gz
    ├── 1907794c83a593f80f9dc9ad95fe05214840647c.nq.gz
    ├── 19486524fb8d58301e1f2d44382f0f7ee868d0d8.nq.gz
    ├── 196212901a945d9e9db5d9e5f69bc7acac0a93f9.nq.gz
    ├── 19ae4418f958e6419d04e908baf71e6f304ee7a9.nq.gz
    ├── 1b48f4f2254e9be801b079aca5e504fdeffd9361.nq.gz
    ├── 1ba334eba9e92aca7b0c30703123191fd3fa7938.nq.gz
    ├── 1bc77071923ed09cb02e39fc89305c267def5db7.nq.gz
    ├── 1bfee8cd691357cea23a8bfa95fc20e670d892ea.nq.gz
    ├── 1c7a473b8f93cdbd3b4eee75c1208abb8e3ca619.nq.gz
    ├── 1d0312e01be3500293ae1a234eca0988bedbadaa.nq.gz
    ├── 1da29e3b8e1a5b3beb9075b4034dbe2fe68021fa.nq.gz
    ├── 1e464ced2b53da598de89b315c4a35d9332d77d4.nq.gz
    ├── 1ed3d0e14fff71646ac08955b7ad23c203a1238b.nq.gz
    ├── 2195a4d0957e013db98d03e51697e2315816cce2.nq.gz
    ├── 21a922c3b2b49fe84747823f009aa054bc8158d4.nq.gz
    ├── 221e7c1a1b04951e3a23909ff56fcfcf208eb7ec.nq.gz
    ├── 2277848008e205628d3110e8d990a5dbbaccf8cf.nq.gz
    ├── 2339b9ec9df359da3b28767978edd69927dfcc53.nq.gz
    ├── 235728b6462fa900778c14f3fe3520f834652b5b.nq.gz
    ├── 2368950e2fe438a5f22bbbf34bacf6bc130e7f1d.nq.gz
    ├── 23967e89baca772d5de1da9db24f75c45c0189d1.nq.gz
    ├── 247fd96a0f70c69df5a4207fd119158dfe237015.nq.gz
    ├── 24c1a108db6bd3c39f9ac8e3f1698e20d1da936d.nq.gz
    ├── 25cb580c0063fae85fafb9f8726506f248f99fa3.nq.gz
    ├── 260cb7ffdfdde4d2c6d6c1906110d3ce8d20f79e.nq.gz
    ├── 26fcd0677ec2dad7d1702376575cd0e474b1939e.nq.gz
    ├── 27271303a38a31989362d5abac22d5aca2f386a1.nq.gz
    ├── 2759b0fecc202f4c99c23ebbcc95518de8fdf5ca.nq.gz
    ├── 283dbe334d6e63d5f23bfe35cea546b9bff370f5.nq.gz
    ├── 29369a463d6b73e427e69ddc0b92cbf88920a2df.nq.gz
    ├── 2983b040632b76d775d56e4f76fa8a31b2702bae.nq.gz
    ├── 2a6efb6982bc0678688664bea651beb65186d7da.nq.gz
    ├── 2aac083855642c6e30e1b463b6dc201583028ac6.nq.gz
    ├── 2baec70290ce1da8c61c657ad5a824c848026891.nq.gz
    ├── 2ccf0d7997662707b839c1359b3b64d0989b58c5.nq.gz
    ├── 2d637cae962f6ac2e8f232d531b3122343cf557e.nq.gz
    ├── 2dad7af5d89e1adf88a2b696cec04ecc0a953b9d.nq.gz
    ├── 2ec3a7f358d6723f73a35074f28f5ed494f6488f.nq.gz
    ├── 301e5a1df277a1c0e4dfec53581251291194a3d0.nq.gz
    ├── 30da6cb0f40464b1ecf72e9d2ecc7c89aaceed4c.nq.gz
    ├── 3117262c1d35ac6593c353e4fcc15542ee291fdd.nq.gz
    ├── 321a35c488e0af80a306f510e3e5ac8b0557f0fa.nq.gz
    ├── 341edc3d96d60de7451ca15c198063e6fc234c48.nq.gz
    ├── 344947ba72e53e048511f3404331d8b1b7d978f4.nq.gz
    ├── 349ec52f580efd5f768db7576c986643cf03b2ae.nq.gz
    ├── 36c46425c8bf9e276ce092b239a9328be05de886.nq.gz
    ├── 36c69120afd9627ff36b10cd9bb43644ca92680e.nq.gz
    ├── 36fb4b2681bc0cc8a84979a24e6f80a3a56f61f3.nq.gz
    ├── 37bac79bc6f002d965f363e0b20514904504a4d9.nq.gz
    ├── 37d5f408375c5e36115182b82ca04b0edc56843e.nq.gz
    ├── 37eaa9df2337299a18d8331f5f19ba8d024318ca.nq.gz
    ├── 37fd9c7a8dd572466abc5365db3d5cd38e8dcff5.nq.gz
    ├── 38ad8b5b097ad2abe18862f8d085f6c908a457e7.nq.gz
    ├── 38d334a44ee058b3f2a586dbf7aec9c1d54df9f2.nq.gz
    ├── 396b5554d519c499cfadf5c7f11bee1f9e53f168.nq.gz
    ├── 3a66f7e7fae3c62600fe6349a5f3435617caa1e2.nq.gz
    ├── 3a806d2b695ac2fb732ba8cf3f0d94b5a6fe8786.nq.gz
    ├── 3a84f2e74228738aa345c722a5679ae04ba1f950.nq.gz
    ├── 3a9bed0b050549dfdcc6866a1fdf68d39dc17093.nq.gz
    ├── 3ab882edcb2ad5d187a5cde4a22bd17857edac1b.nq.gz
    ├── 3c63edec5777f20f67b5603f7546b73bc81ba400.nq.gz
    ├── 3ce9f8f9e67e1a84dc24e6438c44b4f187ab0f26.nq.gz
    ├── 3d6f03b078f48573050172e57923e881076a56f7.nq.gz
    ├── 3e0ceb56c41147f1194190bdf4f36b1bb5ffbf4f.nq.gz
    ├── 3ea2533314febaab7a01a9ccdce872ea0bd487fd.nq.gz
    ├── 3f52d6c3c08aaff33a6888f83b51e9bd110928ca.nq.gz
    ├── 3f539486cda3027ed024ab121033bd8ce7435aef.nq.gz
    ├── 3f6ce2321edb3d90a32fc1277ac421497881b0e1.nq.gz
    ├── 3f72e0ce46fabbae049e3eccf2f84e2e71e27979.nq.gz
    ├── 40ba3ffce79db460a4d50217e24c851e66f2061c.nq.gz
    ├── 40c6236e77212675e7dcc12435e7747f3d861679.nq.gz
    ├── 4151a11d9dea2064f1afb076928beb623ae165e7.nq.gz
    ├── 41a003a3b1ba3a769a4597082a58ef11c0590cd3.nq.gz
    ├── 41f2902b59a870832f6df05421d338d6f47526fc.nq.gz
    ├── 421b8f5c0cb6f53cb53c3ada175d23077bd9c25c.nq.gz
    ├── 422f06f0cf34d5c8ec83fc221ea1ba69ad3f0bd8.nq.gz
    ├── 42d97e7d272c49302e97bab6f87e3d876c8a1a14.nq.gz
    ├── 4353a9ee749b3dbc467b0cf74d3e5c41dfa372d6.nq.gz
    ├── 43881d4cff408e1d4a95b3d535d1a593e128afac.nq.gz
    ├── 43deab594e6af3bc87824ae244a2a88a22679f23.nq.gz
    ├── 4435be5232c8202a6816dfc6368ba6e1486924b5.nq.gz
    ├── 445c2a237ba90a72124a2bff1719a26984aff00f.nq.gz
    ├── 452f8b0b3aa066d48de6bab56205b65823394e6b.nq.gz
    ├── 45854fd7a973381d83b12b35fd3e61baefc32d3f.nq.gz
    ├── 45fd38bc69b3a18cee50e546e3afafce51389af0.nq.gz
    ├── 4600f5473304dbd3d4074879901fe684ad1105bf.nq.gz
    ├── 4676bc0d5a92542e4e6d6af01fc701fa1f7de8d8.nq.gz
    ├── 46c2617f06ee982c4ec970899d8f4ec1c5061eb5.nq.gz
    ├── 46c379ff5c9481f751bbfa96f961b8530c25b9c8.nq.gz
    ├── 46ffa7132e84e5fe3546b209f5896b00c0afa37d.nq.gz
    ├── 470cbe553a6c328dd6cab643b478f9629d957131.nq.gz
    ├── 477c393bb9aa3faf33a4e1e0e94a8b52e1aa132c.nq.gz
    ├── 480b727db79ab3133a192821854803d5e07b2b33.nq.gz
    ├── 4824dc3b65f53800d82b43213a8b89891c559218.nq.gz
    ├── 488304e921275de5ceb5061b261d05cabaa19054.nq.gz
    ├── 489c562f361beca24abaf17b30d51afac76a85cb.nq.gz
    ├── 493ebc7238fe1125a8c90c9328480f847c0ee082.nq.gz
    ├── 496dc7497d9819be85d0f460ae26673f36ef54a8.nq.gz
    ├── 49acfee76c9085b6b0c68a4344db7fbfbf08f1fc.nq.gz
    ├── 4a52cbfbc5a9c199e55c01457532d61ed72775b1.nq.gz
    ├── 4a8333775ce138b5bd8bf2f6aa2832ca8ffc1b21.nq.gz
    ├── 4b4fa386b6f934d1d41e2e8383f2ff7739470141.nq.gz
    ├── 4ba794ef5357b9c6d973ce59af2989f85b3d01c9.nq.gz
    ├── 4bd0c8c592f870d566aa622835d3d2e96a621b42.nq.gz
    ├── 4be014f609c65b4a7854c0cb8fdcb8866ef38227.nq.gz
    ├── 4c9047b5910886e7a6190cc7d124643752cf249b.nq.gz
    ├── 4ceedc4eb1ced7517ba68001ad6e0bd07c3b9936.nq.gz
    ├── 4d89f0eac84068c5861386b2f841479a75a86391.nq.gz
    ├── 4dc7c7053d4b815b8b651246e47b62412fd2a10e.nq.gz
    ├── 4dd882f5b6db8e4f79479e2dfd8cc3a118a0ff14.nq.gz
    ├── 4e0057d76ffb858f69ce852b58a1c7213a5ae9c5.nq.gz
    ├── 5052c82c7f594419e4d83149b5b4177e03dd276b.nq.gz
    ├── 50d8a26263846be4b46532069fd990877ff6f2db.nq.gz
    ├── 51b7da15ec7ea0420b5b441564ddc95a9447b93c.nq.gz
    ├── 534b41bc5d0bcf8a55b411dd5bce189cab0a90ca.nq.gz
    ├── 534eb80e53196d251b8f1e9efe539c026ab37073.nq.gz
    ├── 53a971654c2237bdba7ce45f2a966f653b770edc.nq.gz
    ├── 54542bce2e69f8a7019f8bdd0988e5a4e40c1958.nq.gz
    ├── 550e9603395362dbedbbc3e377748d8d77c7fd28.nq.gz
    ├── 556c5395e94c7ed66ceb034165039f52f160556f.nq.gz
    ├── 570cfb6df65b5c44ba73274740916563a965c670.nq.gz
    ├── 58c46abffb8e449fc8fa3978cfeae36313ce1466.nq.gz
    ├── 5a088c51740aaf44c7c6b018b5229cc93dae1ab7.nq.gz
    ├── 5a40b03d1ff32f7eee361ecd9b7316b2f07b7625.nq.gz
    ├── 5a87f9619d0c4f4af7fcc07772e16fc39e0a5245.nq.gz
    ├── 5a9c148281e2617f0f72ad21441e9c5170b4b50f.nq.gz
    ├── 5ad5083fd9fb7df9462f97d8e13ab9f3dcf5c207.nq.gz
    ├── 5b0e5cccd502fdfe67a65e17b681d8cfe1926b27.nq.gz
    ├── 5b56606e84e8ef940328de22fb47fc009cb18c2b.nq.gz
    ├── 5ba9ce9a6f2a68f5ab0ee6e5d5af536aaf27ea64.nq.gz
    ├── 5bec11dd53c38375231dfefacfdb75c464baffce.nq.gz
    ├── 5c7767f7defc14348bec2e9f37e835fd72951d9f.nq.gz
    ├── 5c8a56d330a4cd7751865a62a100aa002d5b51e5.nq.gz
    ├── 5cf25760d31d06b0e7ffc073adf412814c5f9dc8.nq.gz
    ├── 5d29c6c4daef769c4f11b4c07b9640ae59e06bf9.nq.gz
    ├── 5d686c98d2dc1da1b8229e36d5b575bc7d0a783c.nq.gz
    ├── 5df60958b52ed57a37b0087cd5b24d912ccbd621.nq.gz
    ├── 5e35d8e6dc576d83bd89dd7e90674fbf8f025f93.nq.gz
    ├── 5e48028bc21542ba298719631fc49f5ec02eafd0.nq.gz
    ├── 5e8abfb1d1bcfdf31b7a1c72d196a3bae3262446.nq.gz
    ├── 5f3a664a6bc7e5ab578f3515de4fda819d88a66e.nq.gz
    ├── 5f45e53036cc7aa132279ff993076d2ba8312abc.nq.gz
    ├── 5f6d48767e75f3d7fbda8df4a7948650a6574bd4.nq.gz
    ├── 5fffd463077d1644db5bd56c9d787172e279dc4e.nq.gz
    ├── 60070b1d3e05d0d7d6d8b5f842fa11fd1a476706.nq.gz
    ├── 6166f9737f4edc5a8a47192d72734b2214667a1e.nq.gz
    ├── 617ce5050be7c7f771382bf78fe451091ad76b2a.nq.gz
    ├── 61c2c6f507b373511fd99d8d9f11374e261e6f83.nq.gz
    ├── 6216880939d68244021b909a3aa014462618e83f.nq.gz
    ├── 6253d9f4af24ce3f1da2ccccf6b4c1615f91bef8.nq.gz
    ├── 62c92d841c4a3eb24a099aa4c544270d6086854a.nq.gz
    ├── 634773af7295935e4d2c14ef8743506306982556.nq.gz
    ├── 63860eda3ca08a03997422f85bad2158c8d397a8.nq.gz
    ├── 64568a67fa9346877a048bfc4e82cd8cdb4c6be6.nq.gz
    ├── 64e47d504a7fc13e03537bfe8ee01c854ad5a092.nq.gz
    ├── 663c45d962aeb5b75ead7cf3def106f8e35c7a0b.nq.gz
    └── 66439ec2f1b4c3d94433313088bc5bdbb7cecade.nq.gz

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

[ansible-collections/azure](https://github.com/ansible-collections/azure)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
