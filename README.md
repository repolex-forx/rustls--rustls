# Repolex Knowledge Graph of rustls/rustls

RDF knowledge graph data for [rustls/rustls](https://github.com/rustls/rustls), parsed by [repolex](https://repolex.ai).

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
rlex download rustls/rustls
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2976d90fd1c2db6b518700dd101b714069cfcb17
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2976d90fd1c2db6b518700dd101b714069cfcb17.nq.gz
│   └── repolex
│       └── 2976d90fd1c2db6b518700dd101b714069cfcb17
│           └── chunk-001.nq.gz
└── blob
    ├── 000f3ac8d2b087a90c6a2f958f4ea4547a94728d.nq.gz
    ├── 0023e6f4ccd2ee30abf33fe125ddd473360e1642.nq.gz
    ├── 003e85d440d5140dfee41114910dd97720815cb6.nq.gz
    ├── 00689912d74f3b61d88eee3885a480fbab220080.nq.gz
    ├── 007033225fa103d70d6d6e247eb3b4714c01ef65.nq.gz
    ├── 008136ee42bb517dfb7cc99a699e6fe2f934fcc1.nq.gz
    ├── 00f4c7096c2c0695b604617262c03916d9e3e102.nq.gz
    ├── 0184ff58862c896184e5a906fdbcc42cea03fc41.nq.gz
    ├── 01961abd318c74b7089ebfd2cd0a5a8e70daceb0.nq.gz
    ├── 01a05bb18b61a8987807385020123c94aabea3d3.nq.gz
    ├── 01cefed19ff4f7b215c20adbf47b324e24fef0a7.nq.gz
    ├── 01e0f3d52e2f7fd5b0e2069a06b0d4dc2a0f57b7.nq.gz
    ├── 020d00afe60717d0d007d84d0463a985dbff423c.nq.gz
    ├── 02541e91829e33108e8b1c2b6b1c448a32319367.nq.gz
    ├── 0266faebd7e8162abffc2dd14b933b117f05e442.nq.gz
    ├── 028c8bb9f0c8a0652d604b361c00ddd9a2ad2444.nq.gz
    ├── 0299ed6a8cf88b33af175cb4c22cc14fd5704cce.nq.gz
    ├── 0340e328251177168bead1a5c63cdb665764578f.nq.gz
    ├── 0341e6297f5c4aa8f4500d2584804c629e13c6c1.nq.gz
    ├── 0351088b32a8b057b7e26b686e9f57ad16d41cef.nq.gz
    ├── 03acf1bd2c44c9c10429d0ee4d05ee1e92f9e3f9.nq.gz
    ├── 047345f36461d20966acb4b8d80643a299f03578.nq.gz
    ├── 049fc3456bc7605b12a76b2846023b8551ae85f0.nq.gz
    ├── 04a2428dd1b241426110ecd5aa0d7ecc260f5cac.nq.gz
    ├── 05ef6bfd6a4d7fa59828d879850bd7a22066ff52.nq.gz
    ├── 060f0f77937bb71a6a628588f0625156d8f293ae.nq.gz
    ├── 06595dc9d7ef63c2fe7dcbc45ea57b7f670833fc.nq.gz
    ├── 06b1f07007960aadf264fa1b8ef2c69be3f10b44.nq.gz
    ├── 06bf2d43fb2735b39152735cf7488374836bc623.nq.gz
    ├── 07122e903e9fc89e6d399c53083185822a17f03a.nq.gz
    ├── 075ab08e53b0c81565be2dafc2d3ca2557a480f5.nq.gz
    ├── 078613e9f85ecf84557f64d1b170e9cbbebd4cc7.nq.gz
    ├── 0793d3084356bfc0377d89321e3b3184e1eb52af.nq.gz
    ├── 07b9f069a39d8f7855f06e6eb2d328d8f481b6cd.nq.gz
    ├── 07dc0dacf82054fef4007b7f824dec218264ef07.nq.gz
    ├── 07eb737729112d8caf1169fba55b17bdc8528d9f.nq.gz
    ├── 081c7c264ade9ceaf0da74a16d0df5cc53725522.nq.gz
    ├── 084515b1c61d3afebcccf6eff778d9376a0992be.nq.gz
    ├── 085c8f96cdbc1a78aa96ee52bd4f042e99e37d42.nq.gz
    ├── 0896bccf287bfb5052c63a9265a8bdf3cde3ccb2.nq.gz
    ├── 08a8cc3fbf004de8164bbef2d9c94deab0243151.nq.gz
    ├── 097f9cb399c1c9e2cbd26fac9d73c1c5c8a16615.nq.gz
    ├── 099e6eabd7fa998995b19240562deb63438a2c82.nq.gz
    ├── 0a2287aeb47b2c9cae95644bddf02540c2a0c108.nq.gz
    ├── 0ab1133e98814bc3286754d7aac241595e275d25.nq.gz
    ├── 0bd0018486fe750be5fe878f5093c8c7339d0916.nq.gz
    ├── 0c4a62ec6e08337c59e526afb49562b207cf78ef.nq.gz
    ├── 0d82e2d1e1c0a2088000cd0439590700d959e40a.nq.gz
    ├── 0d97cd2aed80f0dcf487deb08eb2d338eeb7b43b.nq.gz
    ├── 0df9fde3be36117fc387ab056c78b324747ee65c.nq.gz
    ├── 0e2bb7e0d8f5b5917134dbc34fa259c31dfa15a5.nq.gz
    ├── 0e4fddce1cb8a4eed45ca3d22ddf5910f529daeb.nq.gz
    ├── 0e77da4e48ebccabaa7288052511533330983cc8.nq.gz
    ├── 0ef650aaff82759f28e1155fb35a6ea90c87c1f0.nq.gz
    ├── 0ff3c900971bd451335e2d76058a47b3e6b37f2b.nq.gz
    ├── 0ffa6da3d277fe204bdd12e74bde41c96c24d66e.nq.gz
    ├── 0ffcccfea04f60970b2fe7f2312580483e004c78.nq.gz
    ├── 102c5308060c4b7ffb1a55d5e053dd64b330ca17.nq.gz
    ├── 10408cc0e59ffb923fbfb08550b52603912d6987.nq.gz
    ├── 1060d1302318891dd1de44fbd2c3e102a9794f92.nq.gz
    ├── 10b42c1054468b7eb4c3a8032f9208ab6d69625b.nq.gz
    ├── 11024af0a96087a75d78603d78afb1cfb5d1eb10.nq.gz
    ├── 11a9822ecec6ab58c797a72a2b481cdf8f1792ef.nq.gz
    ├── 11d310610384042b40fd8e10ab98779c156c6139.nq.gz
    ├── 11dd98990f48ea97f16c0bc64b03f1b5cc17f8a4.nq.gz
    ├── 1260f7c14c9ce518e5f8b9179b777a304d5ac029.nq.gz
    ├── 127bb76e66c42cc572c305e0dc4bd9f1a9addca6.nq.gz
    ├── 129a638da9b298388ca02a2a78b579d6a666d0a3.nq.gz
    ├── 133d7a65ee7b3303ca2a3474ef811c6e72a9ba4f.nq.gz
    ├── 1360f776986cae6d8d8fc40836537cf6c11975b5.nq.gz
    ├── 13d644021f1685de9fbed2bd344d7ae073516cef.nq.gz
    ├── 1440ea53fccf8238f0d19dbe437b46ac1f26cfc9.nq.gz
    ├── 147c02ae00f8cbc5f7d8538a6307d00fa494bf02.nq.gz
    ├── 148482f784ee17bba0ef5900056c07e8600e9e96.nq.gz
    ├── 151c8ebb008ffda1802e09f8473beb6167d606a3.nq.gz
    ├── 1559b6e0ab2eb9c750f03e3f97165f7c3e90a515.nq.gz
    ├── 156b26d35b6837769d998e54974d0e944998768e.nq.gz
    ├── 15704842a4d7540f2dd6fa5e274f5b40e1442d3a.nq.gz
    ├── 15a60bcbb978eb8f3f7273c714d8b272220803c3.nq.gz
    ├── 15bdc3f8013b94addeea66470bf7217fe2a114b5.nq.gz
    ├── 15c6f6cc4276880e81bc883b5052b4723de7dc05.nq.gz
    ├── 1623c3746b8e5bab75e55e353907291f2dae5b53.nq.gz
    ├── 16699e868499e46e9b4833f8c58734b423c77add.nq.gz
    ├── 16c1277d8adc31465790da215bf24787586fa110.nq.gz
    ├── 16f1592eb75e309a57b1a60471375439b33740af.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 17405e6ec30a42164d81d1016a6b6781f84b2995.nq.gz
    ├── 1760bdd4b3aca74e1dc7c219abcc52ae1ba6682a.nq.gz
    ├── 179c7578c3875d1a3a7597d9434fe306e592b9cf.nq.gz
    ├── 18860e710d84a5e84fc0bc9dcf773bf29b119a51.nq.gz
    ├── 18f40f75292fdf5fa37dc21b82a40f8327e61fcd.nq.gz
    ├── 18fb67ba8bafa58bbf94e7514cb8f619bc0a2b14.nq.gz
    ├── 18fef3f80041e5999ac47846514a3096e48dd1bb.nq.gz
    ├── 19187549671fcb899c2f946e62131c6266f88683.nq.gz
    ├── 1922091fb37aeb1afcdf357a81c62b2522f31c2e.nq.gz
    ├── 1938d51e3bb6842d9e6126615d5afab779e4fe91.nq.gz
    ├── 195cf3dadf0a90e5c4e8a6b4f532424ffd9cdc23.nq.gz
    ├── 19c633ea05e0eecae1a08ba435d3a0503e120571.nq.gz
    ├── 19d86367f03944e982ba99ac61ad51a3d520f3d1.nq.gz
    ├── 19e9b4cd1c86b008ba1095ea877810e51a43e688.nq.gz
    ├── 19f5a99b2334f2184e6f6cdb1cf4c16b1900e221.nq.gz
    ├── 1a3d4f9bb79dc189c9bf58baed1e5f34c6d955f8.nq.gz
    ├── 1a822a51a37798f4227f35e458d33da6954a731d.nq.gz
    ├── 1a9e713f963b052a1a99600ec0111fe95f23fbfd.nq.gz
    ├── 1af42730fa7cb82cb052c68e9d7027174d1e2d5a.nq.gz
    ├── 1b151609d20a8e9cff2c9cca9e890af34120ef3c.nq.gz
    ├── 1b5bd7580aa8846c883b1bd73b4ab6d0f04c4947.nq.gz
    ├── 1b7d3fac827068e8cf9a2fd831b757838294f52f.nq.gz
    ├── 1bac74b498a4f9b908ba0ef2de9eef349e45714f.nq.gz
    ├── 1bf0d8c7758e6fef35ec6bbca1b55badf24d9fce.nq.gz
    ├── 1bf0fb8b27e3c5f45709c196e61477a91a0d34f3.nq.gz
    ├── 1c6a7b98bd0f2cdff15f742d787a4b23e56bf2e6.nq.gz
    ├── 1c9c9649714c71cf8c95bc1987cccaa1b8f7bb62.nq.gz
    ├── 1ca30bee0d2ddb6e1c36f56d75d9a3e9f795614e.nq.gz
    ├── 1d6f910c9de8c20a648de6247930ca6aa8f7adb9.nq.gz
    ├── 1d72b7a4a6ab9d94e33022f7290dac1b22e156b7.nq.gz
    ├── 1da8f2bafcaecacf3582cfeb532802415e55fd2d.nq.gz
    ├── 1df384849366ae77798563c4a5c3522145edc91d.nq.gz
    ├── 1df456c5c4e31ac69d6190675579a85e5b19a467.nq.gz
    ├── 1dfb0e70faadbce1e2af09df6a528e061e25c471.nq.gz
    ├── 1e4c812bff4b40c0bc6de39ed880e6636d66b488.nq.gz
    ├── 1e927a7afe06c270670d6bc25c4d465db2e0a7e8.nq.gz
    ├── 1eb5f727af333a838cac2760d0defdfacfb04986.nq.gz
    ├── 1ebfaf2f3782789635b02eac0c529a0b61a12255.nq.gz
    ├── 1ec8caddae32f9ad482388f6b33c9f2711ca670e.nq.gz
    ├── 1f31dfefb55aabfc611ae70b2ae6bf0a429b6bc7.nq.gz
    ├── 1fd31f975b31498589b3ef43f05a5baf842cdbde.nq.gz
    ├── 205e391df97474b41617c5d00d79a228afe3d7b9.nq.gz
    ├── 20693e9b7b58deaddd87d98fff773a0c1ccf223b.nq.gz
    ├── 20997a0e63a581fa6a3b969261885357b30698c9.nq.gz
    ├── 20bac75319ae4b359a219e6cddb6dccf8e6e2aac.nq.gz
    ├── 21335e40dfa04bdbabac2300202bc90ec83e8006.nq.gz
    ├── 214dad4e0f89216a3b28ed1c166bb95523fa9fa4.nq.gz
    ├── 21c48a5a91f32362818ec0bcdd2585da561442ab.nq.gz
    ├── 220dc536395121b2738dd52fc1e38b615aaf1d1a.nq.gz
    ├── 2212b3c434343bf5b7462cd90e9a2367a34410dc.nq.gz
    ├── 22ae7b98a4484696cd68bd6980d8b3c0c5f24f71.nq.gz
    ├── 22b30abc5e8c823cfc7cbc6db9e831a40087e6e1.nq.gz
    ├── 22bcc84d0520c6b73fe3c7a3cb00a689ebc90ca6.nq.gz
    ├── 23593863d38327ace3ada31bde61df5a683969c3.nq.gz
    ├── 237578e008c664b02ded4a420e57c594ba249de5.nq.gz
    ├── 23a6491ac378e5f997221c1116cd6f149b1d4548.nq.gz
    ├── 23bde852ae62e49fe7ed345310cdec34177c7d64.nq.gz
    ├── 23dbebbb979ded8a277ebe8fa3624a8c754808fc.nq.gz
    ├── 23e385226c73aec61809b4b8d477d46857885c1c.nq.gz
    ├── 242455e764f61fbe9bbaa8b46191099a1cbb9d08.nq.gz
    ├── 242ea48f1d3919a92c94e8d9d65fcd5c511dd133.nq.gz
    ├── 246164fef3feba2837563ccfaf1dea942eb6e3bb.nq.gz
    ├── 2472270e1e506e3e983fe1a41972021d65a04a24.nq.gz
    ├── 25b46c315408ae99bb3f113d07cb3c8b583b3e72.nq.gz
    ├── 2620fe8a4cd8ae6340cb11cf7617d54f09fc72c8.nq.gz
    ├── 263156669cfad76dafde41ec63f9992460b613d6.nq.gz
    ├── 263e1735acb5e97b51d704275ff94224514ed4a2.nq.gz
    ├── 264dc1324ffca344a09002dcd21db2b16ea220da.nq.gz
    ├── 270c2dbcc721647405ce982564f7c6f09619df48.nq.gz
    ├── 281ce160562a7c6b5629b47a1399904433ff10da.nq.gz
    ├── 28832983cf2ca53d6bb75e94bb935d5fb25632b8.nq.gz
    ├── 2898141f47745f1abe425c3c380a44c5be37acbe.nq.gz
    ├── 2909eaceb35203344953c3bac59b1fae8ce00c2f.nq.gz
    ├── 293b1cda49df3bfd2154a4e3449736b0be1d3493.nq.gz
    ├── 296b447ccbd8dbcbaf45e358333ce4d0f9fe99db.nq.gz
    ├── 29efafda574cb1bce88baffd5b320453e2d27bd2.nq.gz
    ├── 2a097572908cc19096c67a5502700a2a282540fc.nq.gz
    ├── 2a61dd88232fdc47ae3dd494798138e357f5ca25.nq.gz
    ├── 2ae6793cadacbfca4ac472226748a9de722f51cb.nq.gz
    ├── 2af41f8e0f32e7d98232033b50caa162fc613f3d.nq.gz
    ├── 2bae399069f78577f5cdbdc66e0e781b55f2299e.nq.gz
    ├── 2c010ff1a70a22bad998409c4fdbab2f84980042.nq.gz
    ├── 2c2ae27749239c56d013fb4b48c6105b19ea5d51.nq.gz
    ├── 2c3fbaeac9495ae1e2ac80b6f54a5bd8485c8fcd.nq.gz
    ├── 2c6f1278c82dd00e9e59bee7a9c3cf7964258056.nq.gz
    ├── 2c7df63cde23bfa753c68d1e5faf9b610ce056fe.nq.gz
    ├── 2cfd8b82c4a48cbb7f510aef00580f9970e222e2.nq.gz
    ├── 2d337c793ef61f4035ed5c9b8c2ca654b5e40a9d.nq.gz
    ├── 2db1c7677c1e2da5a5beea2b7ba865ee669b566a.nq.gz
    ├── 2dccb8d99eae4ba9732e7e8a9aa5feca79240bb9.nq.gz
    ├── 2e4bff4cec53344b4c71f6c2b9b61cd848143e81.nq.gz
    ├── 2e5c3a5ece63d406878b2b3da627f6db9c1d05f6.nq.gz
    ├── 2e5f7110752f5915ea84b743c8e38ca454aed2f6.nq.gz
    ├── 2e7cc0f6f9d5f2a68058d3ba41d654feb445cff5.nq.gz
    ├── 2e9aca4c58377a35dc9eb88a1d4941e662a2df0e.nq.gz
    ├── 2fb8bbdd35ad4d279399d193c438f7aa6e698f47.nq.gz
    ├── 2fdb57e5232477307aa71ef69e4c81fd60c46582.nq.gz
    ├── 2fdd662ac597d490f4a9312eb9d7e82e3324e4f6.nq.gz
    ├── 3054c2ce0660f5bb377cd58af7fab1c2d1924bb4.nq.gz
    ├── 307a41b40fb5473d82019f0d881be95fe644d54f.nq.gz
    ├── 30a5600d5900e8ed5b6ee2cf454e0cf8db3fde1f.nq.gz
    ├── 312fc686b1d1b269bfe2306c7e2534bf10f709be.nq.gz
    ├── 316257c56a72db64b88cb1b7641de3c2f17154f3.nq.gz
    ├── 32250254c436ce9e4cc605ef32cbaa485ce52df5.nq.gz
    ├── 32785cdaed19ff2f021c73783e6c20a646ec53e7.nq.gz
    ├── 3283658f2b037bedfc4c123c090f74fe3fb0ab25.nq.gz
    ├── 3399bbeefeb18b3727117a087849ea393abd77a4.nq.gz
    ├── 340ca4713abc199113e51dc1ccdd8e096a29a748.nq.gz
    ├── 3474209d4ce23c4742224046bc33454567623dea.nq.gz
    ├── 34e0d1a34fbe9ca03380d218c3bb416434c66505.nq.gz
    └── 350bac45f8572a458b1b92a4d8b43f0486cd2729.nq.gz

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

[rustls/rustls](https://github.com/rustls/rustls)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
