# Repolex Knowledge Graph of langchain-ai/paid-media-agent

RDF knowledge graph data for [langchain-ai/paid-media-agent](https://github.com/langchain-ai/paid-media-agent), parsed by [repolex](https://repolex.ai).

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
rlex download langchain-ai/paid-media-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3cd7a0e0c82cfd120d82360e7dada003ba1c262f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3cd7a0e0c82cfd120d82360e7dada003ba1c262f
│           └── chunk-001.nq.gz
└── blob
    ├── 02baf8f416c6004fc6c890911e8346a7bd59717a.nq.gz
    ├── 02e737f57a9ad343bd197f759d767133b28c79c9.nq.gz
    ├── 0315b1dfd79ff12f45b517e80404c7a661d4a4a2.nq.gz
    ├── 035f3e82e45e25029691fd2c1dfc62e7736ccea7.nq.gz
    ├── 054fa59b339d18c072773ee923823f7f507448c3.nq.gz
    ├── 07f2f13081008e29e031695b2476104ca896fe83.nq.gz
    ├── 087c53787e7d8f4effe7239b985dde34be576402.nq.gz
    ├── 08b0b0110c3e3c578147bda089ab420a196d2a59.nq.gz
    ├── 0c11e74486a83186bee05676084fbc6bf3a57ca2.nq.gz
    ├── 0ece1b801d70f763723c828f1d986755424ea4bc.nq.gz
    ├── 12329eb864c6c7ad32af6aabf0f2c759335f9714.nq.gz
    ├── 1396b13624be580a070b79ee3322cce55047ac5a.nq.gz
    ├── 1470ce7103cbf9cef4881b6c85aedf503f004768.nq.gz
    ├── 150af6fec72a88b62b253bd40b2f42b7f6a8d1a7.nq.gz
    ├── 1523d2d3436a0056adeaa716073982d4d803b718.nq.gz
    ├── 1698b3771497b79291979b5172cf3576e3b4730d.nq.gz
    ├── 1898aa0b371d50caf6c13a1e6983e57409cf2490.nq.gz
    ├── 18c9ef916461a8be0fb073f1bf697743044b3ace.nq.gz
    ├── 1907aaceb202b946d96f6c37a0b857c0fb04ee50.nq.gz
    ├── 1a73f97eab8f9069525f9784b81a04aad522ac58.nq.gz
    ├── 1a789abdecef360e1287cdf821cd9262aa0d2644.nq.gz
    ├── 1ad0951c39715fa43f24f751cda457b03c30dd2e.nq.gz
    ├── 1b2824277ec44db954978a985861472c322b7f93.nq.gz
    ├── 1b2d7f5cb54916089fbd94c4c972f0ab0ca2bafb.nq.gz
    ├── 1b9f6edb2f8148fa02cb30ee7e05ad9179b1ca5d.nq.gz
    ├── 1ca66ad52cd5f09287ffb4c7670eecc9049e4ecb.nq.gz
    ├── 1d4e675fcd8f2622c6fd081260b9d8fccaf27cb3.nq.gz
    ├── 1d643877b588c648ba5f00c7bd14b62659f7252b.nq.gz
    ├── 1d8105be1e96ab3a7878665febb5ea6a8adcf4d1.nq.gz
    ├── 1db1acf8b797e571a483c3e730d90a3130165feb.nq.gz
    ├── 219d6dad225036d4ed0902bd898e024afc40315d.nq.gz
    ├── 22296f8f67ce596f426ac242280079ebe20ff8e4.nq.gz
    ├── 226c8f49d3a5fd71227588fe9f02419667b40e34.nq.gz
    ├── 24f0ed70a0316a3163fa164c3e247261d6744b7e.nq.gz
    ├── 26b7bfac2c17239837d101941ee0d4ba29284392.nq.gz
    ├── 26d7b344f07a525f2b3589b13f402fa5b98dd04f.nq.gz
    ├── 2a2deacfc56ba89076eed5fd8fbe33872c1ed120.nq.gz
    ├── 2a4ed8cf1d95459e5c8eb066e3b0448201a1166f.nq.gz
    ├── 2b5a652889b94e554e1fcf55b8b24256f0ff07ee.nq.gz
    ├── 2b7a412b8fa0fb7e985b0793321bd4e698f2b6cd.nq.gz
    ├── 2c48766e06c80e397fe5337a76716cd16a483208.nq.gz
    ├── 2d4e1ff5cb174fe8805cf855db3d9d9e38eded65.nq.gz
    ├── 2eb89f37300059cfce461b47c6df6e71a81768a5.nq.gz
    ├── 2f12c6b499aa43c4b8dad409779c85bdb14cfc21.nq.gz
    ├── 2f480cea957829c5e73e8f6311a9ae4df6b325db.nq.gz
    ├── 30b92fd06e11d24e8c3e62ce256d1472a909cecf.nq.gz
    ├── 314ff7a8105926a20a29cd2b2930d2d14096a6eb.nq.gz
    ├── 3322ebeba1818ba70f6c7394a14c39b3fcfca3ab.nq.gz
    ├── 33699eba8f35831017741e4530a7ad1ad7831bc3.nq.gz
    ├── 37c8287c7c1cd9a5bc4c2ae97bfc1fe7c71aac40.nq.gz
    ├── 38363bcad11435ab1889be2996716b2aad7b2b08.nq.gz
    ├── 39235a7003c40ff6aaa1caac1fff5893125bd723.nq.gz
    ├── 3a33ef2e33404d8b409aa8ed485450ce56f7013f.nq.gz
    ├── 3c96a8b764dad6d20f7615fcb16013226cd57fc5.nq.gz
    ├── 3cff89b37fb006ed392af19bda7adcb71151e1ed.nq.gz
    ├── 3d536f29cbe196ed42ac347b461163cd2a455d64.nq.gz
    ├── 3db2bbd34a4fc18a62c70d683153bc6fd96bdb03.nq.gz
    ├── 43b488932c09602f6d4de0a833ea54613a77aaaa.nq.gz
    ├── 43c558e4b4e3cb78cce6c31c55fc198e985974c3.nq.gz
    ├── 43e83339d7434987948f22677d4c96c6ab8f5d6e.nq.gz
    ├── 4440bc344839cf517d62b6b06457d6672f067ea1.nq.gz
    ├── 46afbcec539de4735676b07c455470a9f6bc6c7b.nq.gz
    ├── 478c2c932065f0666c854e629a368a6cb6af3891.nq.gz
    ├── 4a17190bda4b672947b2dbb7d25e9743eb9e57a0.nq.gz
    ├── 4a42b8c0a457efdf1238e29fecac6a5ca437b6f9.nq.gz
    ├── 4b1a92dad8ac73cbf9afd077b8b78897bb6bceb8.nq.gz
    ├── 4cafc9929585aa9e80b24c08f4fa836c8a18bdb3.nq.gz
    ├── 4d0677ab0550d9fba87fa106c6830b854584eabc.nq.gz
    ├── 4da1f63522236ed62c01d2c5e5cbd6b3cd6312d6.nq.gz
    ├── 4e08547cb1702bccdf4620c26ba76b7e5102e758.nq.gz
    ├── 4e1f0ad7888598ff177e86c40c5c3fdc0ae00db7.nq.gz
    ├── 4ec6922e7427948b928e66e752918c9af1c3cd50.nq.gz
    ├── 4f5232f12e56a8d316e7b85b1e1b9b1b3bba662b.nq.gz
    ├── 51607d3f7a10713d143106331a864d60eab2ee31.nq.gz
    ├── 5189e4dd21159cc0b460befb4b1bb0116e51df94.nq.gz
    ├── 52dff75c026d34502afef11afb49eadeab6f7019.nq.gz
    ├── 532253011b4872ef263cd4f1f52203a709ff0c57.nq.gz
    ├── 543d848c24519368d7a627e3a3b368cc42eb5291.nq.gz
    ├── 5448c5a9f6ebfb359a4d039d4c92ec45a372f592.nq.gz
    ├── 56e684cd07a0dfb8e798f6796d9c7b16dd51651e.nq.gz
    ├── 5737c553c7a2ad8197b98a6bdd68bc181c77152d.nq.gz
    ├── 573d612cdcdbec678ef085775b85c9923b158aca.nq.gz
    ├── 57adf96c8c7263a88e658934fbe4647d7c792f4c.nq.gz
    ├── 57f7bd952617a88e62de5c2657be04a9f0773cc7.nq.gz
    ├── 58de445e6ada073adaf484357d1e1f3d0fe2b3a6.nq.gz
    ├── 5919c3b4de14bf79deaff66e5c26fccd8a2f6457.nq.gz
    ├── 5920aa5a90ec8697609329f7787eeb93467a9191.nq.gz
    ├── 5ae20bb069b7567855e0accccca22e5aba4caa47.nq.gz
    ├── 5e22f2c4f9e6afaffb9eb940ee244b6d2aac5f8e.nq.gz
    ├── 5e6dd0c385d146235aecf0245d20fe831635340f.nq.gz
    ├── 5eabaad4a092efff8fb8763746579e8b848c587e.nq.gz
    ├── 5f05a494724ae6c8eda392a783c13271b14653ee.nq.gz
    ├── 5f8dcde19e0df3a94ee69e078027bb33993532d6.nq.gz
    ├── 5ff4ea7864cd792e937388f1930fd0b0f62050bb.nq.gz
    ├── 632bfff10206cab127862b28496123fd275c9e14.nq.gz
    ├── 645b9ed939d45eae531b5e604f3d4f1127c39db5.nq.gz
    ├── 653b21a8cc497c6586fd2073220ecf65e0d04ae2.nq.gz
    ├── 66dafb37b2c9504073a17e82d6538a62d6f10810.nq.gz
    ├── 67bdd41fa6e5f08ebe51f2c412cb806a66016b7a.nq.gz
    ├── 68ebbae48fd8f5d848ada3061e06a0bbcf7a1613.nq.gz
    ├── 6c06e2317787b4a5b9a8849e905ec41b5ae6f112.nq.gz
    ├── 6c1beb041de18ca2330b3d312036183d80147881.nq.gz
    ├── 6c1f3d749ed8b5d5d364fe303cdc6637a71d9715.nq.gz
    ├── 6df14867f9a9afe568d12e91da22db9e0b3bbf79.nq.gz
    ├── 6df776669d1d7acd1fd923b3f01a474d88bfdddb.nq.gz
    ├── 70985490647a1c52fe091fd46b93d7046feca132.nq.gz
    ├── 70af40773bcbc0bd4e0e9fa61b5127ae2b742173.nq.gz
    ├── 70c3becd53e2f151a497a53a8750ad5c42c17da7.nq.gz
    ├── 710d04d80ecf23f34c6b3a0e536c380a38370944.nq.gz
    ├── 71647371bf81bc84bbd9c4745a30797446bdea9f.nq.gz
    ├── 71b68eb5b4a24894371711033ef02e1d3ce873ac.nq.gz
    ├── 7208b330e0c92a87532f1b4cfcbd510bca805a6e.nq.gz
    ├── 72838c6c1c3e71eb96a72cdb8a73822d596c7fde.nq.gz
    ├── 72d3635585e1b6226b0d2b2433a2ee38eb5a6ddf.nq.gz
    ├── 73fab0d200f4f598341c549c357bcea00d48fd30.nq.gz
    ├── 7416ca76d327736181866bbafa115522948c72ab.nq.gz
    ├── 74dadfbe9885182239f7ae6294098dd1d8482ae0.nq.gz
    ├── 75885fa39e0b20f5851a662b18337a17039f133b.nq.gz
    ├── 770ae1084fa226d94296322b144f781f480923c9.nq.gz
    ├── 7a5d6f63fabdb396430102b8035146fa2fe07a67.nq.gz
    ├── 7a71c1ddc08b90f2c95c4b230b3e7253a20e95ff.nq.gz
    ├── 7c3f12a106ee48f2c50daca74b667946b489e36d.nq.gz
    ├── 7c4b9e2420f78ad6181205f6ee6c32ce3581af85.nq.gz
    ├── 7da5f4e2c4dfa287622a9efdd75bfe21917ef980.nq.gz
    ├── 7e3208e8d53811d140f40f8a070eff780cd18208.nq.gz
    ├── 7ea8136d838ef4ec297e3acd469acc52052c07d9.nq.gz
    ├── 7fa5a33c006309a968205abc48b6283d7892e799.nq.gz
    ├── 875ec548562f7043bddc7c9689192bf88b8c27c0.nq.gz
    ├── 8a3ec0872b6d34d45682b5c48061ba077475c5af.nq.gz
    ├── 8a45743d11d8238a5d80512e8b284e4749b8a750.nq.gz
    ├── 8c801b1815626557b4bc1e99093ec92a43de51a6.nq.gz
    ├── 8d0cf1d10cbc2b6717f8bbd3ea6a644d345c6392.nq.gz
    ├── 8e8d99de89db4f4753e197da87a96c69ab8cf9fe.nq.gz
    ├── 8fa38321974f8b3393ad86b5b12a28366947b20a.nq.gz
    ├── 90243f5dcb3ef65486c8320baacd6687d30007cd.nq.gz
    ├── 910c4ba6414e8131ee0809c6611ec525c6b4bbf2.nq.gz
    ├── 94290d30f4d38ffcd2defebf4f36fa183fc0b058.nq.gz
    ├── 94569974678fb25339030c5f984db7811ebb9592.nq.gz
    ├── 9868ec936a7ca9d85a614b526f84fc95ac8ff33d.nq.gz
    ├── 9a6196ffc8e201fa1d0bbba56ea2f2d7ac93ce1a.nq.gz
    ├── 9a681cc342b301ac832a56ad6ad52880717bc8d4.nq.gz
    ├── 9ae2b5bddd3f79680fda3a13e1b1b3ace873ebaf.nq.gz
    ├── 9b45a87725f697d461865236030a7b5b034f0cba.nq.gz
    ├── 9b8a5b57ec79aac4551e68b0a8dbdd52977a5253.nq.gz
    ├── 9deaffcdd007f5bcb6dacb56517e560b61218a48.nq.gz
    ├── 9e1099ff31d58254d712c1d6e11d5ebb52adb66e.nq.gz
    ├── 9f0dad881e815d74073513899b7faa7ad9d3e324.nq.gz
    ├── 9f1bac4bf3ddfc09210f35c3da243d77605ded94.nq.gz
    ├── a0ee3618ce318e342bf6b44eee63dbd6552cd6fd.nq.gz
    ├── a462d6af4203df97eaa41f38dd61f968e7c1cd24.nq.gz
    ├── a51e36e893ce1720cc83f9b98ad08f9d80efff5d.nq.gz
    ├── a5aa86193bbc95d7142a9d5ff84b890d5c112ba1.nq.gz
    ├── a5d3f23f5caadd64dd0e5bbdda307608a30bdcb2.nq.gz
    ├── a71dbc87f81882f98d4609aba799d95bf998e057.nq.gz
    ├── a88cf071c6220a3f145fbe64d3dd2baacc538f6f.nq.gz
    ├── a96e6abdb45ab882945e4f5f0c464c19961a8b68.nq.gz
    ├── aa31252440625b8845fb39f43282eab2beb695b4.nq.gz
    ├── aa507cea002dba7f9d54c888c102c0db5fd72e04.nq.gz
    ├── ab692351c2d5b9c7ad3e2cb5f4b183cde9bdcc4f.nq.gz
    ├── ab76899a2d10aa1419c518dad24db52b01afec8c.nq.gz
    ├── b020c2123e88c373e509b81c706c515a721f7124.nq.gz
    ├── b0278507cb6f854b0c6af097dfc5b339698d3972.nq.gz
    ├── b0ee5835b20c7fbdea835e22a71cdf39bf43e9dc.nq.gz
    ├── b10763f57c11f6c198f28d1e68ede2eab8c76217.nq.gz
    ├── b183ac3214bf2072c65ec4f45a937d35d64c893b.nq.gz
    ├── b28f538b6721a28ae7a18c1acef770a56116fb1f.nq.gz
    ├── b2b8067848df6dbf0f02a70449dfd88a87baf995.nq.gz
    ├── b46ea9573651c8b4ec9540eb1381d8f08ca50ffd.nq.gz
    ├── b48b7a10a9b21134071618416c69594f33374c7d.nq.gz
    ├── b4bd7d4fe4e5882292fe63398fa4c0dc92ea1955.nq.gz
    ├── b60e822ae9700b86a91fc78010e23a2fa6e74c69.nq.gz
    ├── b672d5973bdb5b1aa9b215662991260db9b0282d.nq.gz
    ├── b6ccf72581d15a020b06d27ae06a3c3275a1921a.nq.gz
    ├── b788487f08d53ee36a5633541daaf0cd2e906413.nq.gz
    ├── b94494cf61751f70d63cbcef34409f3fe7ba7528.nq.gz
    ├── ba40978195052f56266cbc01b62b9be50bf1eecb.nq.gz
    ├── bc3dbb2f703ae25490df9ca988cd9f6238825d69.nq.gz
    ├── be8386a485ec1060a44cf8e0ad0cb57566615076.nq.gz
    ├── c24cfff576bb4523816087029f3c86362dad6ab7.nq.gz
    ├── c394553d60b18c1473697ce89bc6cc3b866aa2e2.nq.gz
    ├── c5fe47ae7d0500d9adb2a2c8fa03d7d25660f857.nq.gz
    ├── c68151f3a8b92e629e40857a4798da2c407804be.nq.gz
    ├── c6b443b0dfa1acae46a228ceac15fb290ece3df6.nq.gz
    ├── c7a11145929a7525270903e60f3593009202ea9f.nq.gz
    ├── c82e7f6f74a73d97c38b8709522e99084c6e3a29.nq.gz
    ├── c845e05e0e612e1b92003ba42b366eb66a94f7fa.nq.gz
    ├── ca0a5784cdc5d4fd203170a00fee0285b2c59d2d.nq.gz
    ├── ca1cfcf51a471a8d83a0a0023319af567f88db4c.nq.gz
    ├── ca4068dec3d61af044727ed7f4fb3f188fd26c19.nq.gz
    ├── cbb56624736b5f022fccbbc3c7fd8eb10debac64.nq.gz
    ├── cd329a76c2aeabe535ae519dd6a1cf3ca92b9141.nq.gz
    ├── cdbc7af95e8aa1f159a466fbb2e8135e074604bf.nq.gz
    ├── ce96af8c194f44c81180ac5714af9f50b587dd30.nq.gz
    ├── d109ccce97f61ff422a519c38b8ed5e0fe5f9e3f.nq.gz
    ├── d1e2ab464586cb8d84b9b1aad036d363b4a05b04.nq.gz
    ├── d219bb96fc00361f34cfc2b43e3e01fe45227233.nq.gz
    ├── d31c3c4b7690beb0d45be6f81b3ddb205f0c633b.nq.gz
    └── d47ee7fb4f745df34f0dc2616b7722a54d18c5f8.nq.gz

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

[langchain-ai/paid-media-agent](https://github.com/langchain-ai/paid-media-agent)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
