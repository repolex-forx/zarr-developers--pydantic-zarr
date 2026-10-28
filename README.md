# Repolex Knowledge Graph of zarr-developers/pydantic-zarr

RDF knowledge graph data for [zarr-developers/pydantic-zarr](https://github.com/zarr-developers/pydantic-zarr), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/pydantic-zarr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d11289a9f1e21d12e329cf55f809b3e8ad631ab5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d11289a9f1e21d12e329cf55f809b3e8ad631ab5
│           └── chunk-001.nq.gz
├── blob
│   ├── 002fce463a99ec95909aeb8e9bb33ba155cc4f32.nq.gz
│   ├── 073b3dcbda337ec1b75aba0e627c6b0c36b10cde.nq.gz
│   ├── 0c78f1c07bb7990a57b2e456099ff53d54693291.nq.gz
│   ├── 0ccb495e8aa84eedf1cabc5f615dc7066e8f999a.nq.gz
│   ├── 0d37c512daee73ed69ac1530df3f891f24889368.nq.gz
│   ├── 0d73fa4c5a16a6848816fe6b747b449f73bea018.nq.gz
│   ├── 1dbaa5fbcbecc98d47002549cf9d1c3a461d23a8.nq.gz
│   ├── 1fc869547d99c2c45257f16b8fe4cec75166d6f8.nq.gz
│   ├── 23017294fb94f6c9d92c92d60e0d3a9c566dc211.nq.gz
│   ├── 25dc7f5e3e675899d65339b6333ffa65ae035178.nq.gz
│   ├── 2e092737f6e301a3f3cca7e52d3a71c189813961.nq.gz
│   ├── 2e0b70a0c1d4eaab68151cd7d0335fdad1a57979.nq.gz
│   ├── 2ffa3cb86a81d86372202e9cec48f73612e9ac41.nq.gz
│   ├── 345926945ae9a9840a6ab956cd055b843b2ceef7.nq.gz
│   ├── 348021310ba6dea6ee89e6776d75757c3848c23a.nq.gz
│   ├── 3763456ab37cfa370c0d756d166965d40cd04b1c.nq.gz
│   ├── 3b1a8aeeffe22da7b81500996acddc9a1aef27ca.nq.gz
│   ├── 3b5f3db01e912ebb6bf22d722fe435fb6aec02df.nq.gz
│   ├── 3c80b74c3d719eb9ef255bd8692883fa490bcd94.nq.gz
│   ├── 3caaa10d326b3b9673fddda16dbd186a26a56d89.nq.gz
│   ├── 45b8da7463287e568fa078eb9fd8f850f7a81e43.nq.gz
│   ├── 489da75973e4f6660a7cd855370946520b852d81.nq.gz
│   ├── 4934fa4cf9d4ec75ede5d2788df7fde8f677b0f3.nq.gz
│   ├── 4b6170651ed0e3974fdd2dd1e74cb03bac69c9d7.nq.gz
│   ├── 50567927d4be5874fdb3e951ffad5df8a0b15037.nq.gz
│   ├── 51f7b5a71320287569d8866bf560d7270f0f6145.nq.gz
│   ├── 52fd3db2bca450d88f49d4a97c33ee0a882f6370.nq.gz
│   ├── 571f2002aec665fd666d91e73d8946167b36e815.nq.gz
│   ├── 5866cf6bb6a00ce9fb71522f07784a9a79e282fe.nq.gz
│   ├── 5e9d806cfa7c5fc60d22cf65004adc8ac3d0213c.nq.gz
│   ├── 5edb17049ff3dbd3e482d5e6670d735cc4e9b59f.nq.gz
│   ├── 60a6b05f3fbd97fea34dcaa2001d18d2fc6afe64.nq.gz
│   ├── 62412aa21535a18d67d519b6921c2caa18d1cd9f.nq.gz
│   ├── 63ef8fbcb6bd9217d1645d4d63b3725c56d86a0d.nq.gz
│   ├── 6de803891e69e3ceaa6bada1d417e3b06438af14.nq.gz
│   ├── 6fbbe8270f6a61669103d67a355ae0cd641a62ce.nq.gz
│   ├── 722257247e51bd718425dbc9045ec7bc876f255b.nq.gz
│   ├── 7287ad0ccbdbc95ae9357d0cc4fc4b107bd6a01d.nq.gz
│   ├── 74d61095fa9525cb158e2621c3ad4b3b4e82fef5.nq.gz
│   ├── 7b67fc75eb625c627b0feed2ae6ee3f47af2e478.nq.gz
│   ├── 7cc72f34d905dd3acbb68abf9c10e6c441f1515c.nq.gz
│   ├── 7f09ed12237ffdeacacf480a1ad445ee0863a8ff.nq.gz
│   ├── 821b09de43673bbd9d95482b92a36985a9d44a58.nq.gz
│   ├── 82f81db866099c3241e8c5221a2084c4c5fc626d.nq.gz
│   ├── 836286d4cd7a40f65a20799ffdf1d818bb1c94f4.nq.gz
│   ├── 8632990dcd2e4ab9114be378434a0c6e97cbdbad.nq.gz
│   ├── 89179c37aee6a92fdeb79ac1dbdc46bbce6dcf13.nq.gz
│   ├── 897d4c117d6b554dfd5395599f32eafb3323138c.nq.gz
│   ├── 89b580b9dd63b1a7156e0b366ee07c083b728495.nq.gz
│   ├── 8fca125bbdae018ad5d8712736eefefb907241a1.nq.gz
│   ├── 9a9a97ed16d27c86d8a5fe6891268a44db663c35.nq.gz
│   ├── 9eb83639d59cb6e9a2b359bcc88a8325c1bd27ad.nq.gz
│   ├── a182f1feb47f414fb6a1a5b071c08e1c7549fb18.nq.gz
│   ├── a18a35717b6d3ca0f390f93238e7437e11b1bd2b.nq.gz
│   ├── a1eed5fb94812c0721e64744ac16b7d0edb443c7.nq.gz
│   ├── a4e4c0da5f618c86b20cd97a0956270f85e3733b.nq.gz
│   ├── b058d8bfc07f692b3b53b6e6829cf0b38afdd7d0.nq.gz
│   ├── b1467983917ac76cf46ac4abb7f9be6f46e7fd5c.nq.gz
│   ├── bb3c29e6b415150ac5114b5814ab227235b7c825.nq.gz
│   ├── bc2560c916d7f461fd007f500617e776e79e8fc0.nq.gz
│   ├── be5e95635587f67bffe1b51e824ae0d924ecb964.nq.gz
│   ├── bff8f871482de467c9324bfa1a34edfd713e1194.nq.gz
│   ├── c5ea42c5aeb000b8f070126f1333ce100bb190e3.nq.gz
│   ├── cc4d42070d4b03339d094a649c65f7bcf80ea51e.nq.gz
│   ├── cfbf1fb614558cb1533237c28ff095c4688da92d.nq.gz
│   ├── d1dd4d9e40338e53835b16e628d1066c6cd3a71a.nq.gz
│   ├── d8d2b302fc7129f489005ab20ae3aecfca573678.nq.gz
│   ├── d9d158554863e6150cb1981f7b8cb8e019fab06e.nq.gz
│   ├── da2700e32aa56ab8eccbc8e74582474ee608ac96.nq.gz
│   ├── e3af0bd7e8f78c4338c31144b45a2a1738dd5c51.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f16250f635ca74cdbfd5edd563b914bec62c6e84.nq.gz
│   ├── f9456ad51dee2047fb006f8ec9dbc97e8c8a5479.nq.gz
│   ├── fbafa8144c42515370e7e7e8debac7a3e34bee7f.nq.gz
│   ├── fe4ac63cc4f1a8609f8467168899faa7af92e2b4.nq.gz
│   └── ff91b6795833e328896b5d4083636bc4d0a3ba1e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d11289a9f1e21d12e329cf55f809b3e8ad631ab5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 84 files
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

[zarr-developers/pydantic-zarr](https://github.com/zarr-developers/pydantic-zarr)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
