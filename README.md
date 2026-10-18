# Repolex Knowledge Graph of Koed00/django-q

RDF knowledge graph data for [Koed00/django-q](https://github.com/Koed00/django-q), parsed by [repolex](https://repolex.ai).

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
rlex download Koed00/django-q
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 85baaccd2c3adfe0a414d4237465163e9ff6e5a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 85baaccd2c3adfe0a414d4237465163e9ff6e5a0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0197cfa7302fb4d8567fddfd219e47143bd003d2.nq.gz
│   ├── 02954a45d0c2c16ee3484c418d5c1eec5fae7ad1.nq.gz
│   ├── 03e83a4cddf6005b5c666d9a9ca813619497662c.nq.gz
│   ├── 062480aa664535e3a81adae2b6c4af4d0079dc64.nq.gz
│   ├── 0b6d14f9d768e5aea9191a833c7cd477d4243ce3.nq.gz
│   ├── 105c5d68f849602d99494b3c6595c0838f76caa8.nq.gz
│   ├── 1077fc36c23213c424046e248126139ce5459709.nq.gz
│   ├── 109b473b66a20126e48fb10a02453d6ad046b7cb.nq.gz
│   ├── 14dda2d0ac2b616437d725be0494753481ee2b46.nq.gz
│   ├── 1755932ec1ff126413d1bafd9654b886872e22e2.nq.gz
│   ├── 190827355e6768d03a3674cdd044f2c0f8fffd5e.nq.gz
│   ├── 1972bdce030276be6d18a92dd88fe8c367ece078.nq.gz
│   ├── 1a1ee88e3aa509913c7e35f211ab893f064f5a69.nq.gz
│   ├── 1a635410c462af75f5d113a4728a57cc18338863.nq.gz
│   ├── 1e8b655e328db751a6a61a114407611d80a61f93.nq.gz
│   ├── 29eb7af398ccdc1f11a9dea6b8cc7a48db8bacf7.nq.gz
│   ├── 2a2ec938cbdb56022d0a52782fad7b09ed2d3edf.nq.gz
│   ├── 2aa5279cdd014ab1b67e8a783033f313a978bdb2.nq.gz
│   ├── 2efe131bdf4c32b4cd156b8b0a192ee7807fddc4.nq.gz
│   ├── 30d03be4dad4a60485bdac8117aa815ae37786e0.nq.gz
│   ├── 345eff11142c3389898050505fc6a8ae97da09f0.nq.gz
│   ├── 347a8392b0bad5b6c5dcafb3a4f107caa35a2a93.nq.gz
│   ├── 3749d2ec41908dc8064fdb27a16341c4480eb873.nq.gz
│   ├── 397631f742b0837d277c7cb084394bad4d3e2d83.nq.gz
│   ├── 3a8f39829e077ebaf9d82ffac53718a3319c58de.nq.gz
│   ├── 3c89fab8e75d965bd15184f08a4157ff1559f498.nq.gz
│   ├── 3e2613acfbd728eac46391ab4a645a58f23f36e7.nq.gz
│   ├── 4308bf2c02fe53e06915babdbd5702f0caa5cbf0.nq.gz
│   ├── 455d4b8fc53fd8db3fc9c045088cbbc5fa2d1957.nq.gz
│   ├── 47684ce5bc39d2dfe7d17fcc5a54486ba14fe5b5.nq.gz
│   ├── 4958771a72a89ad8419febb91d0ac7592241fb57.nq.gz
│   ├── 5090848915457eb5d23b2f64b9450d8fcb68596e.nq.gz
│   ├── 53aaa16fcc00cb8823778dc8e5989f9a8ce1692d.nq.gz
│   ├── 57212dc6ee554fb6a05dec4d57b87c4f48dc1fc5.nq.gz
│   ├── 5ae4b0f7c4db1d96efd72e8d09d93260f573c073.nq.gz
│   ├── 5c74bb6cbaab80a82c4cdbed85d1b67d198507ac.nq.gz
│   ├── 5dd37e560aa02892c021532a490c456e0d96d5b0.nq.gz
│   ├── 63c0ec49f64452b2d52ca69bbb4c89ccfce9bd5c.nq.gz
│   ├── 66d97a2df88d153129782978cdd6aab7a821780d.nq.gz
│   ├── 6ca327bfc87f7f8602b06a4d9fe7e8e1fa0e9954.nq.gz
│   ├── 6d2037f9bda9b1d1d8424bebdf42d5fbebdcf143.nq.gz
│   ├── 6e6da73ca0030f7a597d576318854e7d13bd8f45.nq.gz
│   ├── 7204555771a6f73dbc77385b00230946d0e20b10.nq.gz
│   ├── 72238c1b6afc604d3677167206a027db0ce84167.nq.gz
│   ├── 7647c76b5739652a3008291c50ee2811d2a52953.nq.gz
│   ├── 7ac01ef96c8b53a2dee490e9921a95a915b401c9.nq.gz
│   ├── 7d270415d5c13b4897c0859afd5d3ac2f38d23a1.nq.gz
│   ├── 8384aae9616f3419e50363692ea4e4f231361a08.nq.gz
│   ├── 84b0cc00be08ce7b6cce96a1e67187e429bc2ac0.nq.gz
│   ├── 865d72880f04db341686451dcf5975fe43eabebd.nq.gz
│   ├── 886259e933d21f257dda09c388b9c25e076f7545.nq.gz
│   ├── 8be35eadf272eac5e78bbe66bd94be472bc397bd.nq.gz
│   ├── 8c62eee70aa49d8ac96af529e6035519893d25fb.nq.gz
│   ├── 9304eaaa48812b64ef8d18dd4c089f2cedffe69c.nq.gz
│   ├── 959e180b30b8af748b85b0f996bfd2928c2d59a7.nq.gz
│   ├── 97404187b5d9d4c1688f3f8cfba492c30d030da4.nq.gz
│   ├── 9740bc5a1770783120096b43807167208b24e80d.nq.gz
│   ├── 9a83e908f16440098ac7a76ce6e8091f0b561fab.nq.gz
│   ├── 9abb43b69d7a84614c021bb1254464e25670b5c1.nq.gz
│   ├── 9bce4f5ecfd191e63ab5d43bcf018ee233509494.nq.gz
│   ├── 9e8a29801ab00aa2801a57b027897acf793890c3.nq.gz
│   ├── 9f63e0769d1465b00152dc726efe7f4d50ff5b4e.nq.gz
│   ├── a2ce1093321ed093dc49d0c44ae7baf8b7e35ab1.nq.gz
│   ├── a6694e1648711e3361f6fe6f1658efb14962928c.nq.gz
│   ├── a774c4c31fa4f7734bbd5c6872a5cbb8c5ed9610.nq.gz
│   ├── a7a7980bb3e2cea3d79bb50917f370a3bc8b385f.nq.gz
│   ├── a8ad4e16f7b2f37589133d0101f8772688214089.nq.gz
│   ├── abfb0b2206fca250821505af49d0c32bc62eaacb.nq.gz
│   ├── ad480c654b9655a07cb2cc55826a6ce4543c3958.nq.gz
│   ├── b1e274af6b401b21604bb9567ed2b72d212aad36.nq.gz
│   ├── b372dca1287cc43fc3aa819bde2fefd47d3565c7.nq.gz
│   ├── b40c322f987be2c77a8eaca6cd4ad49574a0fd86.nq.gz
│   ├── b87e08a1dfee26646172c84d65a870d861977eea.nq.gz
│   ├── ca925a03d92d1e26d08a2a4bdaf7305c7a9e52a5.nq.gz
│   ├── d4775276953b8d0164b27a05b28f924f3acbd571.nq.gz
│   ├── d631cdc69010fac5c64f647ab1e4573f6d47cd7a.nq.gz
│   ├── d7b9b87ce77c60663980c124ae51971a58c410e5.nq.gz
│   ├── d83e039241a61fa8792b28e93ff47e98b36021b8.nq.gz
│   ├── d978d99c78e050291aeefa50f918a4ed634eb462.nq.gz
│   ├── dd91cd3aa0ba68b0d618344046c9a7bfbcbd17b4.nq.gz
│   ├── dd95eec586d3d5ad010adc6a4d1f43cbdb460273.nq.gz
│   ├── dfc4cd3a0662a88348bfed5d572b7fd1fcee6b92.nq.gz
│   ├── e21bb1d87104d20a5758c6498b72c9dfcee6ae00.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f84cebadd1b62514bcc47cfc0202ea657d2d36.nq.gz
│   ├── eafda41fc7f5c493dcf6b688a48659e45edd6fdc.nq.gz
│   ├── eb44d83ebd7514b6de2106711fd7df1ed2d2081a.nq.gz
│   ├── ebb737ab4225f67bdd86f73f348bbfd584d898c8.nq.gz
│   ├── ebe8e7a3ffb0b679c37159e3660a1860aaa84467.nq.gz
│   ├── ef3ea714a1947ed437cb0468dd49cb57ab8eaf1b.nq.gz
│   ├── ef42ac2e2ebdab78eca718c842f1fd40ff4d0325.nq.gz
│   ├── f2fb6305451886c919bd37befcb63b0bb04922f8.nq.gz
│   ├── f41d380a5d702562688d1ff3798126f9c7a18fa9.nq.gz
│   ├── f4997c393db3421774254aecaffb13f6dfefc4fa.nq.gz
│   ├── f59c13245561164fd26e6bdd30480a2e35125b68.nq.gz
│   ├── fb148d6ddc118b87c7e6a28bdeb45249294160a3.nq.gz
│   └── fefe54fadf019cf6ce1af68c94da4b50a25e0596.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 85baaccd2c3adfe0a414d4237465163e9ff6e5a0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[Koed00/django-q](https://github.com/Koed00/django-q)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
