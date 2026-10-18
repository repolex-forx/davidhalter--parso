# Repolex Knowledge Graph of davidhalter/parso

RDF knowledge graph data for [davidhalter/parso](https://github.com/davidhalter/parso), parsed by [repolex](https://repolex.ai).

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
rlex download davidhalter/parso
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b26da16316da46e4770d589ed5f8d404531a22af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b26da16316da46e4770d589ed5f8d404531a22af
│           └── chunk-001.nq.gz
├── blob
│   ├── 0029fc8a514a38b21d7e2b22def5362195aedf14.nq.gz
│   ├── 01b52a5894560cd65d144d47bca2210355676f96.nq.gz
│   ├── 01df1ddd43c261b8a1920b496844cf996e073f67.nq.gz
│   ├── 04cd2d57fd21b422ff62327dd32b56f76c552f93.nq.gz
│   ├── 06416fce0b643ec4158d3c996586098904c319c4.nq.gz
│   ├── 06cffb4af982604d0360d88f1639675c575187c3.nq.gz
│   ├── 072d2e5e29539a155defcbb8cc4a09a37d3035b6.nq.gz
│   ├── 08c41db014ea40b0f01e9f5c56793b3c1d138aea.nq.gz
│   ├── 109dcd6c77deacde88c0c097b61a58d0fe5e3ebd.nq.gz
│   ├── 1295389f80f0d856fce408bea03e1e8d3ebfda8e.nq.gz
│   ├── 1348ee3635938a3b16d638be42bee4b768388bab.nq.gz
│   ├── 142a508a63e657bbdcd81b0b9467278cce931d55.nq.gz
│   ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
│   ├── 1d5657f2f06c335548b4b8970d2943a01039b6d7.nq.gz
│   ├── 222236e7e8902af4775e85b3b38f86aa7e374ac7.nq.gz
│   ├── 232be8623b4449de9c7043fd608882e2d6901b35.nq.gz
│   ├── 26697fed7359d67914480048bbd6795da1d5460a.nq.gz
│   ├── 2cba2569e181eff7bc084e0103c7525ee92a1be1.nq.gz
│   ├── 2d869e27bf1dbc0fe6c100f18eb3d35f170ae424.nq.gz
│   ├── 2e9ef9151d79632b5cbfdc5304e194584f98847d.nq.gz
│   ├── 300a54ebc20be1d2bb48de04564595dc987c787e.nq.gz
│   ├── 31e241cd44f826af5675560b7bfd2a1a69c4652b.nq.gz
│   ├── 37466435dd6a1d61de07cfaa77e621f9ddcef3d4.nq.gz
│   ├── 38d7a19043c5aa7b64970460526e595791607f7f.nq.gz
│   ├── 398e754a4161e13d27ca3b3e8374e66dd552de1d.nq.gz
│   ├── 39b93f21d57c817bc7340aaffffc108016d02458.nq.gz
│   ├── 3ea5f1653b0d284b9779318e71631fd69576a52c.nq.gz
│   ├── 44986fa963dccee4de79b2bf8c4df6cfba74f5cd.nq.gz
│   ├── 451918f2120bf2a52f365e65ec4d87456b837a3a.nq.gz
│   ├── 4774852a07aee2e89abcbfa6528c74da8dee0c04.nq.gz
│   ├── 47db445578f2ce821493568abcad65abc3786fad.nq.gz
│   ├── 47f1447a23dfde972be5cf980b6bbf0769dc8d30.nq.gz
│   ├── 4929496e5406c32c2e00e3187b3ede8afb6827fd.nq.gz
│   ├── 4a03a0f8356195f54c624bdce138dbe4b03e0efb.nq.gz
│   ├── 4b0c4c33626207fca90ce07cfe258db173c7a1c8.nq.gz
│   ├── 4cd9ebfdecaa90411ec59aaa50d6d6c36c93416e.nq.gz
│   ├── 5488ea40ebc0261b2ae123514cdf72b9ecbaadea.nq.gz
│   ├── 5592a9fdda088c93c86cacb6d530019ffab69f4e.nq.gz
│   ├── 566e90360a68005d1dbe0765e591539c084431b5.nq.gz
│   ├── 56795f21cc138be304e04a65f5b0f3235821e1f2.nq.gz
│   ├── 568ce9d48c5e74be7ea36b200cb19bd1296dd524.nq.gz
│   ├── 582efb43acef0caa81e8bddea8c4fb4e2c03ed62.nq.gz
│   ├── 58b186fc43b38c92e65feeedb85061cf7fdc62b9.nq.gz
│   ├── 58c1dcf98ff077326b4c6d70cda0488e2fc1bd48.nq.gz
│   ├── 5c3e47a6932a304d4c96cdfa5e4ebb8d77e9ed45.nq.gz
│   ├── 5d4b8651280e879c4b87996e3438f9aa23e15d81.nq.gz
│   ├── 5ddaae8af11644dc8796d8e0891ea11df59aa6f8.nq.gz
│   ├── 60a249b8f15a1948cdd6a388c6b815e6a17831f8.nq.gz
│   ├── 60a982db728e58165965cba14fb57aa88ea116a5.nq.gz
│   ├── 60aa841aa535806b5316bdfd6f405e54d3876af8.nq.gz
│   ├── 61cbba08122ae9e1e2af6f2e9ae91f0b40039cab.nq.gz
│   ├── 64610ddb1ba356cca74f7c164e36925237b199c7.nq.gz
│   ├── 67fd55833c746f6efc1cca55149ae527c6a3859f.nq.gz
│   ├── 6afd8e53321c632cc45ac69a30dde57f14f92c0b.nq.gz
│   ├── 6b8d59e69e37f971e7967585ed00c54735c6dc29.nq.gz
│   ├── 6eb20064a8909aebe04bc6ae7ff649db2672da82.nq.gz
│   ├── 6f332cfc547582eb5a96563fb431280357650f7b.nq.gz
│   ├── 7083dfeb46745cf8db04c30513f848d7f673e593.nq.gz
│   ├── 7288d556f9b4b09154e1e002630162a0e7d0cbe2.nq.gz
│   ├── 73ea9a2827027f5c5e3b892522bb4fef146d936b.nq.gz
│   ├── 77e2e9043a0e4285ce2325058e006751a45527e7.nq.gz
│   ├── 79ab47871b0be3e5919891e5a8cba4d5c9753c1e.nq.gz
│   ├── 79d25f85e657fb09fd176c653376e14f06a20305.nq.gz
│   ├── 7afcfaa487f168e0788530cb00e7d7e263855727.nq.gz
│   ├── 7ff342aeab40d7a9de938a10a4d1dd442e83d6be.nq.gz
│   ├── 82ff6a440a5dc42bd773ceec7353b02b1ddec67d.nq.gz
│   ├── 8328cfba9e7f6075b58f4a819b4e3cd2c6ac2fda.nq.gz
│   ├── 85ccacfb47660211610470d4e4d53fe5ddae6832.nq.gz
│   ├── 87efd4784a6091b7dfaf2e685860280d2b852256.nq.gz
│   ├── 8cf53147f784d5b63501878b2599b05b481870ad.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 8dc65a5a427e7dd14045ffbd513219e3823b3722.nq.gz
│   ├── 9149f0aa52601d30b16c823c9a8c38aa5c918c9d.nq.gz
│   ├── 93a2ccf386c537faaf7c5b8ec9b6986f32e2f64b.nq.gz
│   ├── 9b6f4c7c1985ccadf073a1bbf9e01ac906f49558.nq.gz
│   ├── 9b97f3980c4520ab0d78cdd30c28416022c2f0ff.nq.gz
│   ├── 9c065c9494ebe1b30ef60202c869fdde585e16cd.nq.gz
│   ├── 9cccf619cb6ed351efee1c7cc662d6dc115872d5.nq.gz
│   ├── a4811fb8d1a657e78700a2a143be670657ccc19d.nq.gz
│   ├── ae46033cf35962d2311f973c34cc3b743617a1a3.nq.gz
│   ├── af0c711a8c638b66ab95068ab9936d0f9c1afd14.nq.gz
│   ├── b11d4ce3b6c7ee909f871929f6f61eee0127dd7d.nq.gz
│   ├── b390db35c2473f6dc0d4d80a20f09593c69d6529.nq.gz
│   ├── b3c413000b160b31e1118a57350b0039d14c14ec.nq.gz
│   ├── b498af3b49e178ac60ddeb179bb8ba464eb46415.nq.gz
│   ├── b8821902e2e3478339d500abfb0ce68b1901fa7d.nq.gz
│   ├── b994b9bbb88d2d30c02d639be98249c9d30bdb60.nq.gz
│   ├── be11fb1def8e53dbe96aee5438f32fefc06a6d99.nq.gz
│   ├── bef857c84adcd6758fee0ec40ac5c2683fd12c51.nq.gz
│   ├── c0c005ccd2eea34ff84d877723c8af77b60ed0d0.nq.gz
│   ├── c2387ec540d9105f93a8da5dd5dbe387db874598.nq.gz
│   ├── c42963f0948b7d6ee3f1c9c06f843734d6144b85.nq.gz
│   ├── c6a23497e52415364da9e9946296d0572467158f.nq.gz
│   ├── c81d027a16308bf78f97edabe946e1548046c252.nq.gz
│   ├── cc2471987391ee036f9b0fa8469d4e5dbab47fdd.nq.gz
│   ├── cebbb7bba1a9e914bb1b29f8bb5fc889b955d71b.nq.gz
│   ├── d2d7259f7395790f2276d43024c2fb2307a5208a.nq.gz
│   ├── d3e33c0607297042e67610bb1f2809bee279cc08.nq.gz
│   ├── d4d9dcdc49983a06bc44c48fcbd6f9a097115b97.nq.gz
│   ├── d8a0fad169b53bae75282c14929cfcf40e3bf4a4.nq.gz
│   ├── d931ca390cad531d84b4497aa583f89dbdc3310b.nq.gz
│   ├── d99d792b93c052f3e8f1f32b8a7ea32c1c5689c7.nq.gz
│   ├── dc1b9d32f47d521e20364b6735d48593baf038b8.nq.gz
│   ├── e14a1e4b748de640fe869539d266fe7aac9f3212.nq.gz
│   ├── e54f3ea59452e8b4a1ddd9cc8b4466c6b12de9d5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e79620668d7283770a9604647ba5d2ee78d98a01.nq.gz
│   ├── e7c18e0ec02551cd850caca5c428ce65c19565d2.nq.gz
│   ├── e81a792a8ec494f94d562855cb5db6ee6b959e55.nq.gz
│   ├── ec50aaf0be97a4de709e15d36ee258eb57b23706.nq.gz
│   ├── eebc4563ddb60d158b78a6befb5af3cc015f0872.nq.gz
│   ├── f092050d881db65ec25e1cebbc34921500b60eca.nq.gz
│   ├── f4a929fe98fc36239a6c03cdf6a49715c1e9112f.nq.gz
│   ├── f65616e8ab785eb5bbe6be4380ea358255ea489d.nq.gz
│   ├── fa45e8b1530a433a8e8e529a5376b6ff2f5612e7.nq.gz
│   └── fc3b5f933985ca7f1605cc45eb311538a5d4719c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b26da16316da46e4770d589ed5f8d404531a22af.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[davidhalter/parso](https://github.com/davidhalter/parso)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
