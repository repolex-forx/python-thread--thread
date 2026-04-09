# Repolex Knowledge Graph of python-thread/thread

RDF knowledge graph data for [python-thread/thread](https://github.com/python-thread/thread), parsed by [repolex](https://repolex.ai).

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
lexq download python-thread/thread
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 669e025f3f72ab62b7abba82f8d394a28e1f0611
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 669e025f3f72ab62b7abba82f8d394a28e1f0611.nq.gz
│   └── repolex
│       └── 669e025f3f72ab62b7abba82f8d394a28e1f0611
│           └── chunk-001.nq.gz
├── blob
│   ├── 03f3266b7159b5429f4c528f2a6ebc0f84f7ccc3.nq.gz
│   ├── 0456172ae663d696828bb248cc8242cfd273b13c.nq.gz
│   ├── 0a3e7566a4b479ea31fdbeee4183d5bb4871045b.nq.gz
│   ├── 0ba50bdb35bacc0b1e6aaa4926931353b22e3eef.nq.gz
│   ├── 0bcc3b3061a0231ef4285e4c7ebcd28649af5e4e.nq.gz
│   ├── 0caf91356a6f45dcfbae1946cfc8da556a36a0a2.nq.gz
│   ├── 0e07b0bd3d7515c57ebe1257bc20d86acfc7ca2f.nq.gz
│   ├── 11a6ac5f33c404dee78cbb62297dba12a9386903.nq.gz
│   ├── 12a703d900da8159c30e75acbd2c4d87ae177f62.nq.gz
│   ├── 14983699258a13601dc05738f417f08ec9e45ec2.nq.gz
│   ├── 14fe3c3d29dc4ded5c0fb9eb9c574b7382ab1468.nq.gz
│   ├── 1a81a7b6006b7745fd8ec774e984f2334455b7c1.nq.gz
│   ├── 1ce8a812e7a364bc40b31c15edfb9fa89330bdcd.nq.gz
│   ├── 215b30a75ced3f109f6149df38971d3c9fb35c85.nq.gz
│   ├── 25d02e8d49c62c5a99ce517247987656b454da7e.nq.gz
│   ├── 2720a9cd0f7c72627f9c47bbcb31028f58c647ba.nq.gz
│   ├── 289706cd3578396663fd068fd1e49adf6b7a2d6c.nq.gz
│   ├── 28ab6cc365348b220118ee52453fd19479451fe8.nq.gz
│   ├── 2de98e22ccd3f4c936133730dd9b50d79f745d82.nq.gz
│   ├── 2e0399bd47b4a2fc0a21c9aaec8d431bfff98c2a.nq.gz
│   ├── 2e2a1a832eb6f4482ff4022c89d45a3877849d04.nq.gz
│   ├── 2f4cf0da77a0593a6d26e193b98960712d5823e2.nq.gz
│   ├── 31134023b45031244f2f8bf1c72ef8a2bde87377.nq.gz
│   ├── 330e906f82c348817d42e7167428bbcb47a5b4d9.nq.gz
│   ├── 3367e1b038edc8df04c922f22c1a1639e2f8c9a7.nq.gz
│   ├── 3379ac212b4a2a0722ece08ebd86dc184fb1de5f.nq.gz
│   ├── 346f38620d72df0e84cdd6ff285dcbd724796da1.nq.gz
│   ├── 37a905125da589c7503b82612770aa3395482a87.nq.gz
│   ├── 3a8c15de7cd812abfeba81880f5c0892ac3d0052.nq.gz
│   ├── 3aa0b7f9bcd7095de1bf7bcaaf28699aac833f95.nq.gz
│   ├── 3d060cdd3b5b2df6c48e8b9368fee262277c94f2.nq.gz
│   ├── 4149a8f6978d3d88ea7d50e1be48727d70468979.nq.gz
│   ├── 4617f8c0057afbd7f82b96445ff36ea8c9ec0271.nq.gz
│   ├── 4aa4ea21d441371c4d85a92f474dd4c7e09a4184.nq.gz
│   ├── 4e7685eff762388d3a92f5aef280ea69231aa0d2.nq.gz
│   ├── 4fe575f93b86b40ed6b0d67eddcc5e42933a3c40.nq.gz
│   ├── 536d88c8a6d8fc237bef1bdde42e82eeee2b45b9.nq.gz
│   ├── 58f3ace6c03d093337c9fa417ccbe8bc267b6c69.nq.gz
│   ├── 5d362288055cf801a84f15d16d4c63466d5b1046.nq.gz
│   ├── 5f7936abdd1fcc2d7ef59817b861213a275ab5cf.nq.gz
│   ├── 601b50d2b72826608a2a8956508be41c86bbe839.nq.gz
│   ├── 64b45070a187a9237b803c73889a0f9e1b7266e3.nq.gz
│   ├── 682e98b0cd589107946e6a7ad62fe8851307161d.nq.gz
│   ├── 6870223035bbbabc9eca4ace4c286f852a79c232.nq.gz
│   ├── 6be1b7402a32f151400a3d8fccc64523ee0a6630.nq.gz
│   ├── 6d6f63e04e6a8937ffb40df615e4c0f29d161db7.nq.gz
│   ├── 6deb73aadbeccb2bab69fe93699feb79add3f110.nq.gz
│   ├── 6f55c480e8e4e90f29b607032bc8793433d029eb.nq.gz
│   ├── 71a32ef1b8766ce4e91a523ac3d71e73d7a830c8.nq.gz
│   ├── 75ec243384563f77b51c5011ea41445c0927f693.nq.gz
│   ├── 76866a6a189a6b78660cb999629a8ee5e9cb5d38.nq.gz
│   ├── 777e932791d13139c151824ee8b6d3a7d7e1ec6b.nq.gz
│   ├── 78a524d87f74a2d7019cc70b86cae79342f28a29.nq.gz
│   ├── 794885f85e6a6109c126206e47c8d61d64d01800.nq.gz
│   ├── 79c1065c325404e07adc85c4abcd93500fa8e908.nq.gz
│   ├── 7a019c03947897fc38d799cdb8cb45922191adba.nq.gz
│   ├── 7eb7d144105bc68a7355cf1eea906e5a952737c0.nq.gz
│   ├── 8a766fa3a710c5a989c099a36db1ba7b7900c1e7.nq.gz
│   ├── 8aa7df7c1984848b80cc9c45ae8d478fede728f7.nq.gz
│   ├── 8dc7fc57fdf888323cc54eb8e6601d1b87f9c840.nq.gz
│   ├── 91a77b21fd73bde794177110551c00aa81b27d1f.nq.gz
│   ├── 968095dba69ba37693f7f68073cc9b0962a5426c.nq.gz
│   ├── 969f966ad79849ca72ee1fc3f4b5b283bd58a379.nq.gz
│   ├── 98261059ff175a215ab1b306615f2ba16df8b95c.nq.gz
│   ├── 99eb0b3daa77bb5247a980dbe73d42143396bef3.nq.gz
│   ├── 9c9aea010db2e5a299aeccde432a7371a6a59cef.nq.gz
│   ├── 9dd207c09b70cfc73d833250293185a1a9951bc0.nq.gz
│   ├── 9edb54fe62a863c43517f412676eee52a740fba8.nq.gz
│   ├── a1cc920687cbb5df715300ac5aa0da73bcebdfc3.nq.gz
│   ├── a2694411cf6aa6c6efdd4acd40f589c3c2660308.nq.gz
│   ├── a2a57fd1cdb36e22e9b164d7b24d9ea20367b94b.nq.gz
│   ├── ae0eac7da13bd4e3af74b826a4077ef8558ec2b2.nq.gz
│   ├── afae473baec67b8573e79f4c36cad7811236e921.nq.gz
│   ├── b05d98b4e491008ce0a2815e59983587f2ae243d.nq.gz
│   ├── b3029f20443cc1eef25b3bced04762e2ebcdc3cc.nq.gz
│   ├── b45327b289cfc3962ebf12989b352e2df3eb904c.nq.gz
│   ├── b4f6eba3ee22727e210a501e364ac184d3dfa15f.nq.gz
│   ├── b97e52fc9afaba6ed087f434dd3b93930c87a830.nq.gz
│   ├── bfa0b6f97403e8be4a823751f12ce8e893c7a7d9.nq.gz
│   ├── c2d13317b07d1b2502c20d0fe1f0caa7813f1034.nq.gz
│   ├── c481c46293fb8a6a893e05af3441624510fc85ab.nq.gz
│   ├── c682c13e6f804724bd65c70d930cab5346139fef.nq.gz
│   ├── c79857b06335578112ab57728f849ba50f4af89d.nq.gz
│   ├── c9decfc017c2c94ce40ce24e958844a566b2e02f.nq.gz
│   ├── d4d43ca1cfa1ae02a2161682b9f3b241bb09800e.nq.gz
│   ├── d6de7367757e6c46729dc1c4d4914b2e91c64e90.nq.gz
│   ├── d8d1a8c1c39f62c95b12f2235dbc59ac6e4a1984.nq.gz
│   ├── da50cfaf7cf8add833199d334ba8b7589a944f1d.nq.gz
│   ├── daa535ce18c7b6695d512d704ff7d7595d84b40c.nq.gz
│   ├── dc459bc78f487e13c76261de233922ae37b253e0.nq.gz
│   ├── dc9b8d26b5cc9a26d1b58e0880d0c5e2d6f50e51.nq.gz
│   ├── dda370c4014a116a5afba039b92ab4f2f46ecca5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cd7a50e9cd7c01dfb4b4a16aac6d2f3eafd2e3.nq.gz
│   ├── e76d20b2512c25d4cd9acb4437c0ff1cd7821959.nq.gz
│   ├── e85ba6f13020d5531799ff2573e6aa8f90a9b2a7.nq.gz
│   ├── e93702da9a4af87e528b5b9af2605c82a2cc8053.nq.gz
│   ├── ea196bc31f6d687ad822a484d5fbbe5297f01c52.nq.gz
│   ├── ea9bfeee68e63fa7270e27f2b0a4fb0f36ec9b36.nq.gz
│   ├── eaafd1ed61394825bfa3d23318b24c1ea0ee95ae.nq.gz
│   ├── ebd6b466b9bea76d64f14ea6b9c7559b2707452a.nq.gz
│   ├── f02849df617d0b376aaded518f4695b5d1f6dfe2.nq.gz
│   ├── f1563a23632fae289d00823c8347f6a57497e6e6.nq.gz
│   ├── f1803beb093a3b5b6e809feea546ef2db00a8ba9.nq.gz
│   ├── f23d68ba440889a69d56e3333d75e185eee7bb1b.nq.gz
│   ├── f3eb36fd2baa1fb681b09481e41a63e3b85c995b.nq.gz
│   ├── f851ad0016fd2eb282beeac90a29138515d2d7cc.nq.gz
│   ├── fa64f116f19ebf0f83c1479f3db9f39f5c827ad7.nq.gz
│   ├── faae3367c039eaa1798e280e16d6932948aa9276.nq.gz
│   ├── fb7295c548e78dee0c8b42ce4cfcb5a924ef2177.nq.gz
│   ├── fbabaf432952d31ed6045deda4b8f6f9acd980a3.nq.gz
│   ├── fc45fbffec055ec0613fd67c6704b00442832bae.nq.gz
│   └── fd38a182692d2ae63a936001bc5439780b891c76.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 669e025f3f72ab62b7abba82f8d394a28e1f0611.nq.gz
├── filetree
│   └── 669e025f3f72ab62b7abba82f8d394a28e1f0611.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 123 files
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

[python-thread/thread](https://github.com/python-thread/thread)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
