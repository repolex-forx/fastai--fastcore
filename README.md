# Repolex Knowledge Graph of fastai/fastcore

RDF knowledge graph data for [fastai/fastcore](https://github.com/fastai/fastcore), parsed by [repolex](https://repolex.ai).

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
rlex download fastai/fastcore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d2e1395ca4c304189a62a54701ef6107d5988dd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9d2e1395ca4c304189a62a54701ef6107d5988dd
│           └── chunk-001.nq.gz
├── blob
│   ├── 03e12c0e9e2514665f91bd02cc84ac3161bb11f1.nq.gz
│   ├── 075b2542afb820ca0c990f02a196dfbb35c41a3a.nq.gz
│   ├── 08334bb33cff4c51fc28313800dc9dff7f3538a7.nq.gz
│   ├── 0bf79147c093d63294a0d51eab15f11b68a588d0.nq.gz
│   ├── 0c8c5488ab2b3c84a6e14bb905030b1c81162c18.nq.gz
│   ├── 0de8df163e4dfb29f3bd7ec3606e13c440dafe96.nq.gz
│   ├── 0f12aa85fd2299a6d9e4fab1b8e761f0bd693cf0.nq.gz
│   ├── 1308750575db9324a91569742eecebab0183c882.nq.gz
│   ├── 131dd2bf5c921c8ade64854ac0a7c1298ca73180.nq.gz
│   ├── 18dded389c0f0c544f3a2dd8d1bffc473063b5ff.nq.gz
│   ├── 1f3d89ac884a440b27d113fb0a457cde842cff69.nq.gz
│   ├── 21b870b1e8e65ce413c50db4f9a43cee970927dd.nq.gz
│   ├── 23d8ff46a2b3d852a8a198d206e00f834c9ebf17.nq.gz
│   ├── 247efc4e2da0dfebf2dddcfb1756e7d975affb92.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 343673867757676a66eea0b28851a36ad0ce28bb.nq.gz
│   ├── 3498008bcd890a25e1b9af8b998f0a7b305d8f9c.nq.gz
│   ├── 388da941aa17eca93662586f557b5e20a4f04e56.nq.gz
│   ├── 3acb7580bf075af031e761bcb566a156aa8c0c38.nq.gz
│   ├── 40e1e77d9c462b090793abc2191e608828021150.nq.gz
│   ├── 43613d1e9a827b23ee871f23c4f82622a3773d5a.nq.gz
│   ├── 44821105e8bc30669eca686bf9d8f7954292f56e.nq.gz
│   ├── 449deefcc38f0397f628508e354c2ad845fa633e.nq.gz
│   ├── 4689b8471095abb471fff9cc62b58881a77a60e6.nq.gz
│   ├── 48ddcf571568f79e46de7a60829de3d3b318cc80.nq.gz
│   ├── 546b027e8685d5500df4a7752f7631089c884fd0.nq.gz
│   ├── 57ee053c38c9cb0ddaaee86193e6030b1b3fa1de.nq.gz
│   ├── 5b553faaa3918686d97d1d1a2222fcb56b1cc1f0.nq.gz
│   ├── 5caf63f861b9316696c07b777767a49d1b4ceb97.nq.gz
│   ├── 64e49d8a9644c638274c17703bc261273d940019.nq.gz
│   ├── 64e853fe4c5ee1feb5583880bffd28e4ca82b75a.nq.gz
│   ├── 66e1582854b4d2d0775f165f34e2b622054b8ae4.nq.gz
│   ├── 6a6ca52be89f43cdd35ad862d90a97738a14685f.nq.gz
│   ├── 6af893d56c226bc61a4ffb0a0b1c1de3e8edd8d9.nq.gz
│   ├── 6bef9ce3ccc5335c65f945764477863f369fb5a8.nq.gz
│   ├── 6c11fc445667a12b8e8db655fb4cda67bea00e54.nq.gz
│   ├── 6ca21a6665288e4dfd3400058a8acc1d3463df11.nq.gz
│   ├── 6f7604eb1d90bf866b363cd3a6815ab3c9fad71b.nq.gz
│   ├── 725baade10ab3477fe087654bc6aa39fc2dfd6d4.nq.gz
│   ├── 732288f3a0ca3137ce43fdd09dce417d86d6ab4e.nq.gz
│   ├── 753b249880d57c22306cf155601bff986622b1a0.nq.gz
│   ├── 760f900c4ba9af6bd67968c79a07316ceaea9a4f.nq.gz
│   ├── 77603c3bbfb11343cb37a2056d3a8d1e9c535360.nq.gz
│   ├── 781ff50e63d496a387e5a80fb0e4bf1bacbdc43a.nq.gz
│   ├── 78e10b291a7f59631773a6281358d20ac3fb729b.nq.gz
│   ├── 7bd4593196e2d2a5b1c940526c3b1b7182fb7975.nq.gz
│   ├── 7cdaf9aa0a2bac1f47dbda50f05f2c357e2bf641.nq.gz
│   ├── 7d44d3f43f23d4c14d83efaaed0dc2fbf100b55a.nq.gz
│   ├── 888c94005ce1889efe7c4a60a75ca6c035424797.nq.gz
│   ├── 89bf8305287d337576c23c0d289b59cdac65ead4.nq.gz
│   ├── 8abda9dc57cff19563ca98db7be37a69281e2a1c.nq.gz
│   ├── 8bfa0e952eb318c5c74acaa26a0016c12e13418e.nq.gz
│   ├── 8c9f94a155997d359f8d5b263df219571338659d.nq.gz
│   ├── 8d57a898f1e3669769415b3767a6e3a7d3e297b4.nq.gz
│   ├── 8de4d8e94813e8ebaed536dec46b923677c25c72.nq.gz
│   ├── 8ed5601a5c5d34d2e9da6f5fa5400b73c5cebd7a.nq.gz
│   ├── 90c8c3ef91be13707ea6b6386ae559b657d61b71.nq.gz
│   ├── 915d05729cf07b9ea21743d8cb79b3b67343500c.nq.gz
│   ├── 96c5aa73cc93945c772e32d8c446ea7e4b5f253d.nq.gz
│   ├── 9c6e235bf1f3c88d7b0834dba38fdccd754bd7d2.nq.gz
│   ├── 9d1c0e6a74e3b6fcb355589bf98acadd0c5448ee.nq.gz
│   ├── a263dd28b1b63f34e3018e7fba4bd0944baea5f2.nq.gz
│   ├── a70d675de91b42098c0490a1f6580e855775ffba.nq.gz
│   ├── a76f58003aab736028e9d70848a2ebb71ee85a52.nq.gz
│   ├── a92a89cc347ff9f057b9eb07e4ee852456b9ebfc.nq.gz
│   ├── ae624a9a8f5f9b3bb9a009dae8f7947304fe583c.nq.gz
│   ├── b090f512fbd648dd99ef7d88d320832c80c5e87e.nq.gz
│   ├── b21a11b04e68a3c80aa4bd911eb47e50bd128597.nq.gz
│   ├── b46c2093407b6d1b296d0170a870e93ebc1e04ac.nq.gz
│   ├── baa55fe130619da3f39966e8cf00474c4e72471d.nq.gz
│   ├── be3d56f409ae9092ee674dc3d03b84342f108af3.nq.gz
│   ├── c1a5031bfc8d86107b47c1cbbfd79235270ce1fb.nq.gz
│   ├── c1efd1ebc8847b60be4fd65cce6225f48171ddc6.nq.gz
│   ├── c87a81b95d862971d3579d250df0631b1ea1354f.nq.gz
│   ├── ca021149687dd3649e71fc811d37569afdeffead.nq.gz
│   ├── cd9e0b344d155e7f1d23259432638a6bd78c3cbb.nq.gz
│   ├── d896a9b70e46992af323703cc1497967854113be.nq.gz
│   ├── d9bb41c6c51896d78af12fbc60c2c7a00deb21d1.nq.gz
│   ├── de857c985b555f4c933babe4ca98eec0f65af6e7.nq.gz
│   ├── e14a3b8b35dce29338a7f0c112e717784d6e12fe.nq.gz
│   ├── e16377ba76efd2d36502fab44021c88180a40aaf.nq.gz
│   ├── e51df7b4105dc6337ce0b0362c89d6698f669fc3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaa1d2572eb75cea7d43aabdc628ae2fe232c401.nq.gz
│   ├── ec0427b7140182e5af0ed05cbcec2bb9ed1f61c0.nq.gz
│   ├── f286e6a2c2541fff8e33f5ef2c6c31bc5980c21e.nq.gz
│   ├── f37038a26bc0b5ba5371f826af16e46ef6949df1.nq.gz
│   ├── f456fb8a377695eb8074779f849a1e078eb8477a.nq.gz
│   ├── f4f99bc6a648eee64935aab909f0f3aab32f33b6.nq.gz
│   ├── fa540d665b6763bb66883bf686c55654fad324a3.nq.gz
│   ├── fee292663b1c81820c348bd83c7dc0919f86d2f8.nq.gz
│   └── ff8131edce16c42d16fc1c0cad1c4a8de37855b5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9d2e1395ca4c304189a62a54701ef6107d5988dd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[fastai/fastcore](https://github.com/fastai/fastcore)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
