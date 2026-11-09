# Repolex Knowledge Graph of BililiveRecorder/BililiveRecorder

RDF knowledge graph data for [BililiveRecorder/BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder), parsed by [repolex](https://repolex.ai).

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
rlex download BililiveRecorder/BililiveRecorder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2744d605b93fec44d00a7957de93ec3148e412fc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2744d605b93fec44d00a7957de93ec3148e412fc
│           └── chunk-001.nq.gz
└── blob
    ├── 00694e8d4c48694685a07f947a75f6e9fee4efe2.nq.gz
    ├── 01683c8a674d4947290fdbae01cc3eabd212c044.nq.gz
    ├── 01ed05d5b71b6529235f822a19eb8bebd3484668.nq.gz
    ├── 023fc4b808a71645377f1d46791d56ac9691aeb4.nq.gz
    ├── 02578132f1427d1cac31807537fb6f34ababb3df.nq.gz
    ├── 029a7ca87227c2c4a81b0081e96b6a3e2fe6d1c3.nq.gz
    ├── 02ad6b1c5900b740a6f7a52f374bff53bf5fc6b1.nq.gz
    ├── 03810feed4efced8e4b22cf657b849561e37259b.nq.gz
    ├── 03da0b749c6bd135f1146d55299af120e4463c68.nq.gz
    ├── 04852a995386b0de694d52cf17bf6fbddb679fc6.nq.gz
    ├── 04c6276943cac20329d11574cac1c744d56a4cfa.nq.gz
    ├── 06cccb281f308ee22e2e1985999dfcac0cc6b76a.nq.gz
    ├── 06f9d4f74cb4741aa7f257546424b01b1bff8f80.nq.gz
    ├── 075eb822d4ddb3b9aa837a59a330881f71e62d52.nq.gz
    ├── 0798dc26e2117679dbfc83e1b2f792dbbc89f898.nq.gz
    ├── 08d7af6739f63d2a3348b1f6de09f2130d322f8b.nq.gz
    ├── 09222ed4a421e1c5cee778ce9ccf138c84c300ec.nq.gz
    ├── 09de22934d97864118cad823ccfbba6089e4e89c.nq.gz
    ├── 0a121ca49699fe244a00cb2c8721f9fc86a32d66.nq.gz
    ├── 0a5f5a80a66ae42eef9f768dfd0a34d3a6003101.nq.gz
    ├── 0a699292c37c47904e7cd7a0364ad30c02123c4b.nq.gz
    ├── 0aa545293752359e5c89f1ca160bda7d0189ed2a.nq.gz
    ├── 0b0eb4b85c5d46749fef5f9cca6de428b6fa736c.nq.gz
    ├── 0b7fd23220c48f0a15b453c15c4dc892c17f10ff.nq.gz
    ├── 0becc73b8d79e5aa7c82c6d9cac327381c549289.nq.gz
    ├── 0cc29d4fdb53e4d44bfde0d5a0481528a05a6381.nq.gz
    ├── 0e5b810a04333a10ec327276c8226f49122bbe98.nq.gz
    ├── 0e6e30feadd440a3e7a9e94f6d08d81c57be4eae.nq.gz
    ├── 0ef8db7e382fddd3b3661636a9314345a0dc8d0b.nq.gz
    ├── 0f2f3349cc171c7e73a97ddb09eeded05b8960cf.nq.gz
    ├── 0f4b667a62e20729da572b2e09136c3afbd18b02.nq.gz
    ├── 0f65fe1f3c8d6d1cf527ec4206eabee3960e9dc4.nq.gz
    ├── 0f8b20718ce1e9befa0c735690719f1cf8dc774f.nq.gz
    ├── 10d14a34d13c79728ce7eb2356b920cbf966cc7b.nq.gz
    ├── 13105b2c7cf052f45cba9c7522cd92be37254152.nq.gz
    ├── 13301786bb8a6e4680f94ccd575d964e2cea7977.nq.gz
    ├── 1331092b2a9d60c17044dca5d661f7fc4c60b2c5.nq.gz
    ├── 13bc14bec900ea3db7f93b1389a06bdc8f3a696f.nq.gz
    ├── 140390f34fc768e9908616fb1fbfd1820a8cb3ea.nq.gz
    ├── 14278643faaff0f8a4e776dbfd3ca473aeb37037.nq.gz
    ├── 148718e5de406af02416e3a60e18bc3fa325e83e.nq.gz
    ├── 15afed0898f4e641c992fc69005e7ca4b0ab150c.nq.gz
    ├── 15ef73808d83bac4dc63514f85a9686800c86132.nq.gz
    ├── 162fc81c94462e1bf143bc5ad0aeff9b4d76fe15.nq.gz
    ├── 170399dd55d4beb0adf4f2370de3339cd98444f7.nq.gz
    ├── 176ba8450d69a7ac2c971887e172483e9fb2539b.nq.gz
    ├── 18a1a21f5817712c84294286d5e6abf363763bda.nq.gz
    ├── 18bd77bb0d01eb701bc0d160ee09723be4e02874.nq.gz
    ├── 196066f974812c90b2afcbbd51e5318ed061df4d.nq.gz
    ├── 1a4198e95ce8413878e49049099a65dec912e8db.nq.gz
    ├── 1a84ded71fa59ea28751174c2358f7c9e2e7d4a6.nq.gz
    ├── 1ae5d207c37923037a9cc2fa286a9f16456868a2.nq.gz
    ├── 1afebf8ec85f7ddb9417cc65c6fcaa3c9b4c8a92.nq.gz
    ├── 1b18d156e2bf36b0fc1c774f4a2036d042180cd0.nq.gz
    ├── 1b7afed094b74ce2c88f138b8d78ac7c9b880289.nq.gz
    ├── 1b8917a2d04bd7251e4532a4eb28305e44ea2e69.nq.gz
    ├── 1b8f2f8dd0e295a7e6f3d779cb62fb0d27899dd3.nq.gz
    ├── 1c76fbf25ad8342ec1b8734ed09d247912f973f8.nq.gz
    ├── 1cb446b50b714e86fe1ae6fa983da24b5076c265.nq.gz
    ├── 1cfde69d997fbaec40ebbe7d7a26a36ad8a6e445.nq.gz
    ├── 1d071de105a1bb7acff9f441c394dcdbc5ec25c6.nq.gz
    ├── 1d235cb2e319b10d42a036bdd96492c314b52bc2.nq.gz
    ├── 1df70d9c1fb05da1b32b57ff0bc8176d546f005c.nq.gz
    ├── 1e76b2cbd5ccd65b846b51410f66ebd403e9439e.nq.gz
    ├── 1ff0c423042b46cb1d617b81efb715defbe8054d.nq.gz
    ├── 21958eda0a535eab256dd5b01585865ee79e79c5.nq.gz
    ├── 21a45dd2a026ddaa3653abed1f62784d2ad5193e.nq.gz
    ├── 226ed27f13a05731f9cf407a91911c70ff3a3442.nq.gz
    ├── 22b7c0055b68922799d4f3ba4c534d24ea2ff6ae.nq.gz
    ├── 254137976fcd0e4b7898cda809d14ba445078b7f.nq.gz
    ├── 25532a54391d86729bff4a28c15c0e7300ccdaaa.nq.gz
    ├── 25b66361876d54e8fb3ce66d9bece58bf4fff6d1.nq.gz
    ├── 281fdd9a5b248fbccc30ef25e78aabe852011f52.nq.gz
    ├── 284523482858c899a1e914299b1bcb5beaa84655.nq.gz
    ├── 28729a44b7234ab6e9ee49c36524ef5b3e8d8c24.nq.gz
    ├── 2a23d004cbd91a4ab3fdd471ff5fc16bdfc8af65.nq.gz
    ├── 2a5759ce086c39e29f92d8efb544121693b00053.nq.gz
    ├── 2a5ecba555a0fcd1303c7c8845f00d8b84993f63.nq.gz
    ├── 2a72b4efa684718d4f3b47c0a153258f176f8297.nq.gz
    ├── 2b9b623762a2ccb16b17b9a0238ba53d32b3b50a.nq.gz
    ├── 2c714bfbf13afbd8778ebf35ffa80a8d6d1af905.nq.gz
    ├── 2c9779e2611f973cfc1777bb6a1c845479c7286d.nq.gz
    ├── 2d0bcacad4f7f967c0f7a35f1c632d9458a4d755.nq.gz
    ├── 2d7a58d84c67c808a764cce24c1c968bf615bffd.nq.gz
    ├── 2fdf94a378f21fbfea9fb59167270b17cba39f1e.nq.gz
    ├── 300d01479b3f4846000ada5d455b5f05f2460a12.nq.gz
    ├── 305215833b81bb8cd0ad3a54d0c74f684c0c8804.nq.gz
    ├── 30d8a163d1b0e87a4118cfa47c6c630ff48c011f.nq.gz
    ├── 317d5f3aa8af071c8cf7295fab23d620c029a624.nq.gz
    ├── 31eec9b8c456f4a8394ef0304d2804279fc9d14a.nq.gz
    ├── 3223b354bd079e5bd2b428b8a59911edd131fbef.nq.gz
    ├── 326a70bf7ca46215da8973a3c652a8f06bb1ad08.nq.gz
    ├── 333cdfc10af3bbcfbdea46b19f46b23ac7a39397.nq.gz
    ├── 33d1181af07ee4db5d30fef294cb664968a210f7.nq.gz
    ├── 33e8e97620788e6558718f8b605f8973962d334c.nq.gz
    ├── 34cda85030cd3d237f3715c18a7c674d3622c6f9.nq.gz
    ├── 3595c5e6b32fe0e8072dc02ae3494e816c323ebb.nq.gz
    ├── 36d5c2c13bd7c45c974367dc90c315fd49099243.nq.gz
    ├── 376c2ac60c1d36895abdfe366e044185f685ec1a.nq.gz
    ├── 377fb533e5c7ef3ec47a3d3be10fe4546bdc0344.nq.gz
    ├── 386a231b9481f9207446850612f1afb6fcce2e94.nq.gz
    ├── 38e38d2e9a87c78b9753be3e439d6c9cfab6f9ab.nq.gz
    ├── 3ab7ee7b3d1ca3803debd54fe62aa886e63a4afb.nq.gz
    ├── 3ad7fef982bb5aced334236008c34a32dbffa510.nq.gz
    ├── 3d1bd5a42408e27fa14456d9bb9f19dc1460ae54.nq.gz
    ├── 3d628d1f6b25615c5665127d05599090f862b42b.nq.gz
    ├── 3dc9a341e72a79c4c8246c632792e7b1c992c54f.nq.gz
    ├── 3e41007bae8d6850789c23678ac5f48f1047f7fe.nq.gz
    ├── 3e52905476245a5eae8b8e5111a6a7f1954a2210.nq.gz
    ├── 3f9095c311e8559dc85e7b881bb10cd3d073cfed.nq.gz
    ├── 4157078eb403fac5c1e96435cb753cf6185e9d4a.nq.gz
    ├── 41fee61af6cf12cf0564fe97d0f15abeaaafb195.nq.gz
    ├── 450b33895d5d023a7eda97e5316f9ccc8d76de2e.nq.gz
    ├── 45ecc28b862ee3d116f0c83ac473e4f6db1e3258.nq.gz
    ├── 45f3bd4274eae01b9fcb5fc6f7e832a6d20df030.nq.gz
    ├── 4635b66d1802bed62c72f4f3f74da77f8bd4e27a.nq.gz
    ├── 46baf3a6285b9e5b48d2f59d9c80cf1ce22e6621.nq.gz
    ├── 46d6608e8adfa65edd5d02cad2382747d7b9b9f9.nq.gz
    ├── 4739329e45450992cb5ee63ef26430535c4da4bf.nq.gz
    ├── 481fffe0f4e116ef386038aff4ef0d602002b121.nq.gz
    ├── 4821e7a07de35357f600217b0fdd9e5e70cf93bb.nq.gz
    ├── 4869e7e7c0b47260aae17cc2fb963ece79e1a73b.nq.gz
    ├── 489844947172bf16a4cfc273058d410a8fd25e5e.nq.gz
    ├── 48e97280ed84fb2a7aa365c331ba77ce9537034e.nq.gz
    ├── 4946919752c6e7445e6bb3fb2b1ac0d3e8304c5a.nq.gz
    ├── 496b47fc048de067e17eb08c02a87c21e751e998.nq.gz
    ├── 49f287022fdfd7e5ae9ac84314ed465baaaa1300.nq.gz
    ├── 4a4db2332de54518fa728d09c84aa05bea307f55.nq.gz
    ├── 4a5604d790c6d8e2503dc6cbb644ec821d5e398f.nq.gz
    ├── 4a98529469317308a203964dc5191b060a79b8e0.nq.gz
    ├── 4aaba8673edd24537063701687a5322111e1ff4b.nq.gz
    ├── 4aca231cf02cfdd22d8b6d59b39896741b31ced5.nq.gz
    ├── 4bf94c52dbbecbeb816222e4cc49041fcae721a1.nq.gz
    ├── 4d72f38cb357314fb8f7bb32d2ea170b6fb0425c.nq.gz
    ├── 4da8ebf753bd11732891d6ee114742e5882007b6.nq.gz
    ├── 4ebeb702b3e8c6861eb71fe5b5c9bf1301885ec1.nq.gz
    ├── 4edd6710620a90b0cbcce2ea99f049cc1ac9fe89.nq.gz
    ├── 4f34cca3a0c9531d85da0432bd82b1668068fcb6.nq.gz
    ├── 505644f465694ba451bd713bd9c96747b574ddd4.nq.gz
    ├── 5192c82e0eb03394d4b231708a43b1e8392afa98.nq.gz
    ├── 520320476d072cabb44527333ec9663d72d73216.nq.gz
    ├── 522fdb5525aae8962aa7cb993aa200a234e4dadf.nq.gz
    ├── 5534c2eaaeb1106d0df4dbf044e21e486c947b1e.nq.gz
    ├── 55d0fc34bba80760e86f154f99a7747ef66abcb4.nq.gz
    ├── 55f360f3da0e195f7813fa05c43f3e925403ab4e.nq.gz
    ├── 56d7715300de27d86f4205e6977e31da40cf24b7.nq.gz
    ├── 5767886486cb570c34afe783ec163fa95e8a58fc.nq.gz
    ├── 58ab98320b4b925632c546edfecf3374a7f811f1.nq.gz
    ├── 58f27aa3d70fcb540753843ba053a70c8de3fd6e.nq.gz
    ├── 59023c9e2b28edb58ca24c044a1577d7f6b4f748.nq.gz
    ├── 5928484b2d703ca1c380f5bb50a199c6d859ffae.nq.gz
    ├── 5935ce18ddb3178d014e13ea04ecc3ab7a9f842d.nq.gz
    ├── 5a091fa98710c88532a33cdfe6744618dac8ffef.nq.gz
    ├── 5b0aea15c27459b71868de8168f14f9ddeed67d3.nq.gz
    ├── 5b4b991fce45e912acacce0179b0959548f69ce6.nq.gz
    ├── 5c7e64d428a4249848a569aa89b5ad551f74c94f.nq.gz
    ├── 5d0692729ac42c1e5ed43e6292fb268c4be68569.nq.gz
    ├── 5d5c40ad590edbaf6b9628dad24838a68041bf6e.nq.gz
    ├── 5f3910715d6d16064a62380046654cf1bc05041a.nq.gz
    ├── 5ff4b53a76a25493fce46f9c48fb45d7a5d1c06c.nq.gz
    ├── 611be05a9099e31bff1ded35bdd6faa5343ae1ae.nq.gz
    ├── 6197c78bcf9c189ddbcd53311dd849b210a8f9a3.nq.gz
    ├── 61df8e679d61804c3e4d0c1c07f630741627fba2.nq.gz
    ├── 61e2b9a917245f1b281a85a08ece19b5e7785e90.nq.gz
    ├── 62376ae4e06259b664e73ea7e1a3ec643859c4b1.nq.gz
    ├── 6302f9f5d96cec6a212b68f143dfbab4a07f72e5.nq.gz
    ├── 650e718e9ab9de8f8656ba85c099c1ec3a899c73.nq.gz
    ├── 65911d4865ec363c75ac5bc9473ca931b6572486.nq.gz
    ├── 66672af560852e4c3d229c560c44ac30b9376c74.nq.gz
    ├── 6677e79b0a719889ef791b47bf13109b3c9a33af.nq.gz
    ├── 674cea0a85755754686117bc8acef45ca07a176e.nq.gz
    ├── 67a37810cbaf6dd3a9c4bbb709a5bdaa1a2c38d8.nq.gz
    ├── 69911a5677e280ef44bbf7b7a729b96706febe14.nq.gz
    ├── 6a1a9bc8ddaef9b81743d03aa41d4152f175bb26.nq.gz
    ├── 6ab6955648d4e39f9907cefe3cbe1d298d724632.nq.gz
    ├── 6ad96c54f50ecb89c90a40eda95ba86034c38d8e.nq.gz
    ├── 6b83cad533e46e4515aaaa72f37bd3b917f44f36.nq.gz
    ├── 6bec03f54c352c4e7a0cf1c8e5c7770787ce6e81.nq.gz
    ├── 6c064a3d4d121da730066bb40a5c613c551d27c8.nq.gz
    ├── 6c50ec8e863cd121429ed6d74a8a3cec05ccb32b.nq.gz
    ├── 6dd6fac39027f4fb63fe9d7c4661f388258cbdd0.nq.gz
    ├── 6e563943c32cf2a99ea3f0514555d1dbc83fb3ef.nq.gz
    ├── 6ec6a81edf22180be984c7948b1cca3ba28990e1.nq.gz
    ├── 6f31a807e1c1471b2e344b7c6c10b5874d736e25.nq.gz
    ├── 6ffe3496af664d6630e6f8f523b3160ef54567ed.nq.gz
    ├── 711179ed08510c0a6da724ba9300e403278264f2.nq.gz
    ├── 730e87566e2d7a4657a10bdd199f5a34aafbd113.nq.gz
    ├── 733123e8589cf3ecdcdc9e8d8f949c10c8eaa92a.nq.gz
    ├── 73a32cafcc72444e82e1aa178a7dc1cd05548457.nq.gz
    ├── 73f0d830d50932c6ef19d116197cbab5ac0cfc9e.nq.gz
    ├── 74127524d5f90a8124813186001b0deaaa11d710.nq.gz
    ├── 74c6db0fb4a1231e586c9027351cc59d47ce0022.nq.gz
    ├── 74d40e53e3fe290fcb186e6b0a175be6844ddc6b.nq.gz
    ├── 750251c8339f6609c0ea41285ef2510e5ac54cb4.nq.gz
    ├── 755a83639249e7847094c8174e34b2027e12d220.nq.gz
    ├── 76076661d9079d1135057c701e8e41a1dfadb1c1.nq.gz
    ├── 764422ca9409e5ca07697bd6ec816299e9601625.nq.gz
    └── 776b9d2b3d3d1297dba0246434db7634b046cf4c.nq.gz

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

[BililiveRecorder/BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
