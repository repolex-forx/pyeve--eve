# Repolex Knowledge Graph of pyeve/eve

RDF knowledge graph data for [pyeve/eve](https://github.com/pyeve/eve), parsed by [repolex](https://repolex.ai).

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
rlex download pyeve/eve
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe7d9c919bf35fe149feb42e51ba9c5c337e3119
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fe7d9c919bf35fe149feb42e51ba9c5c337e3119
│           └── chunk-001.nq.gz
├── blob
│   ├── 070b35f422b4548ad2a07e9a5573f871616d0b40.nq.gz
│   ├── 07c558675bf7c9af1701ab943849621647d9cce8.nq.gz
│   ├── 0ccc7fcf1102d909364f55cb6d1138c2803fad8b.nq.gz
│   ├── 0e7b00b661f9e95248b275c900788115b3ee3f6d.nq.gz
│   ├── 103434533b9b152342139f23c836fd11dd546861.nq.gz
│   ├── 1049c544c092d0a220c4fa379956bd2b94a5cf19.nq.gz
│   ├── 12142bd6bd3d4208576f7e67eeb7e9d812fe34ac.nq.gz
│   ├── 183c1fc620d839518d3d7e9495c17a8df20e43c6.nq.gz
│   ├── 1963da290072522adfa9a5cbf46a6d3faee54d98.nq.gz
│   ├── 1a1803157894b5813bc9641f818f39518e814a3a.nq.gz
│   ├── 1d0d3cf8ae6e817340e38ef274892808d2ae84e3.nq.gz
│   ├── 2cc7db5306ea28b1fc6b236cb93ef985cc4bab59.nq.gz
│   ├── 2f4a14290fa0028cd233d404a4c9224913f2d446.nq.gz
│   ├── 30bd8d5b2bf5f27e1711b2686123850ec92478c9.nq.gz
│   ├── 3350c8a36f63788e8f4e31bd4da9fe8565e3b3eb.nq.gz
│   ├── 3933f99401dc7eb78a3e8c6c76dfb2de6ae52d74.nq.gz
│   ├── 3a3b1e107eec6a749b6333b4ab61958f5a19f77d.nq.gz
│   ├── 3a68697678b4e9d2c6bdb65e2423d157a409ef00.nq.gz
│   ├── 3c2e5204b5a860634d912192c75eb3ee92ee9db5.nq.gz
│   ├── 3cdff7f8b6c17c51cbc5e6b113d5a31cc640d7cf.nq.gz
│   ├── 3d2e1483cc83fbdd8380e4d83eaaffd5dc36ae6d.nq.gz
│   ├── 3d7338a71370b61d416f7076904c6931d5197907.nq.gz
│   ├── 3efa5ba633e64668e9b05fbdb7fa4e7d925b49bf.nq.gz
│   ├── 403e907ec72d5cb6b08a99c0da3e2a0a71a899ae.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 43ddd02b70e8a19c8fae1a8474dad5624f48f9a4.nq.gz
│   ├── 448c0a054a36028a2de10e56d978a7b26528c616.nq.gz
│   ├── 4506d2e7623f1f269bba2c09e828b524564b535e.nq.gz
│   ├── 462818222b531ec0c2569ba4cac22bef11bacc88.nq.gz
│   ├── 49c8afe9c755c48d5a2b296c9e59ed53da978465.nq.gz
│   ├── 4c4a66d220edd0e6707980552f15e969fb85aa76.nq.gz
│   ├── 4f8ebe36e5368e98c9cc8ebe3eb9e8f261b8894c.nq.gz
│   ├── 510cd6c459ed8a7871cf8dd3307a7e5aab4c834e.nq.gz
│   ├── 52715e5dfafe3cdf2d7eb7992f4161b9fb3a0af9.nq.gz
│   ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
│   ├── 58328934452bb5b9028b3a816398c9a4e3f5e8b9.nq.gz
│   ├── 5a060157a8b1caf4575934862c6fc92624d0a883.nq.gz
│   ├── 5cdfd27e396de701ff590422b6445b760f9432a6.nq.gz
│   ├── 5d3933909d8345bcbaaa363ce132838cfc425ae1.nq.gz
│   ├── 5ffb71086b2f98b4536aa3dfbee6f29fc960a80e.nq.gz
│   ├── 60a49bc660c3aa5bb1e083feac512c25939026cc.nq.gz
│   ├── 627f94e89ba50d4e844b17cb6ce40e33a53b7af0.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 66c162511bd197640b06e496c92dec0cf4cc7df3.nq.gz
│   ├── 6831765d73be54e731aee07d708823305de1f61f.nq.gz
│   ├── 6a07f9d687a45677683c4bf17b7ae64fc9e60ba3.nq.gz
│   ├── 6febe010c9fbd1373153ee30d1d55bbc160d57b6.nq.gz
│   ├── 71961a272308549a00a2c2dd5ecaa8faa0b1f100.nq.gz
│   ├── 73641e9ec150fa111822abfde672e06d6c906ca7.nq.gz
│   ├── 750e3c4cb78a74a16e4b1d7dd4a24bb162c4856f.nq.gz
│   ├── 76ba7cee80175b182cd5479046e9f63cf54bd6ae.nq.gz
│   ├── 77101e63df169442e4b5b64f4391ca3368ec4c34.nq.gz
│   ├── 77fc977c4fef9ebd534545eed074209d4287b62d.nq.gz
│   ├── 7806c1c00594a3c15814e990555536592bc665ad.nq.gz
│   ├── 7bba0f2f14c2fe025563a6f29b4fd3077b6a0b89.nq.gz
│   ├── 7d072e3b88edb8e4a6c870c7a04d3c8ca0d11248.nq.gz
│   ├── 80366fcccd0fd4e0dd9071a472a1fa7ef384d4e3.nq.gz
│   ├── 83727714ae9ebcd378310356332fc3f0dcdd2dc6.nq.gz
│   ├── 8423cae76c171963f767df212d6e6313822d4d56.nq.gz
│   ├── 8adee363ffac6e409708776ba46bed8a75a4a862.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 8e7857746ebf1512954e9088f0a0b4dae7efe32e.nq.gz
│   ├── 917da2e39f2f2f7ab60913a92274ff5d816d3491.nq.gz
│   ├── 924958f11725ffe6506785899cbbad2d50fea65f.nq.gz
│   ├── 9397b398a84ad2c4193e470cd186433bedf93684.nq.gz
│   ├── 9592736d7d978bebaa06d3b6418353de41bbbd64.nq.gz
│   ├── 9601ad40748d2b4c48f37688306ac07949883e6f.nq.gz
│   ├── 980210e8f48b4c88ca2d76eafdcf40652da28de6.nq.gz
│   ├── 9a2f3b6f211a4b3fc4414d1c03db9c1540a282ee.nq.gz
│   ├── 9b3ae1c8e7f3618e64f52259e13179f79d69b9da.nq.gz
│   ├── 9b5cdbe8b9478f36219d3953cfcc275d95a39389.nq.gz
│   ├── 9c03291c6952d41c3c9ce4e96794d816aa706822.nq.gz
│   ├── 9c76b217a9d44ad2e45832af98fec44c3b9e0ec4.nq.gz
│   ├── 9e598ba6f89cea3cbb183b5ba9e51a4ec0ffd09c.nq.gz
│   ├── a146e95193ecb4293c3e059b2cb012434c54bfb8.nq.gz
│   ├── a595d7d631133a1f2333470a03fce1961ddbc221.nq.gz
│   ├── a5e1c028c51783c30647e4ad3202f9ff3601fd35.nq.gz
│   ├── a655902c9b55865a06e70dd421910beff470415b.nq.gz
│   ├── a86c7887dff141c827c208a2081cc89f70c86ed8.nq.gz
│   ├── aabae5b0948d53c3ef50d616c4bee44fcce4621d.nq.gz
│   ├── ab44ff8020ee4da2b33058d1ea2138313c762e68.nq.gz
│   ├── aeb074a55e842d20d6efaf58f4045511cd4fba88.nq.gz
│   ├── b0a0e249d6b8ca3bc54c7bf6c573b83b1d477b2f.nq.gz
│   ├── b26a1530eb18a77439e5be780dca34f4aae90674.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b3ff26e9001a289deec7f7e89854a4916c32716b.nq.gz
│   ├── b72f232e86841953869452718a3224a3e40a2d95.nq.gz
│   ├── b799a8bef06bfd523fddffcd134a20af21e56e25.nq.gz
│   ├── b7c511d44399eeeb152d862c48be487bbf8628a0.nq.gz
│   ├── b81522b56bf02cab52cd8128308c01b4bc312a7f.nq.gz
│   ├── b86067ff7ea54335e696a1b73ef5d2ed2ac13dbd.nq.gz
│   ├── ba37a83f842f9c63fcaa1bcbfee316799cc83cba.nq.gz
│   ├── bc8563b6909074e26604cd81fac134e25c688a2c.nq.gz
│   ├── bd3d46b935cc057c9a04e18c2cf0381583dcef32.nq.gz
│   ├── c2a4bf83bf90eceaebaa041a0ebb3cb711a96589.nq.gz
│   ├── c2e8e16ed176e85e98e139c66c971a69875a27c3.nq.gz
│   ├── c34787e03b75fb608bd7201ba8cacfda9647f85b.nq.gz
│   ├── c431f6e91c2284176d8086857e99283ef633aff2.nq.gz
│   ├── c5d37081a863877073874807fd1ac07987de0e4f.nq.gz
│   ├── c7a66d091d721d80b1b44756b0e6921f03578d0a.nq.gz
│   ├── c9906ca4fdba5a63a6ad5958abb944c7368a10f1.nq.gz
│   ├── cd01dab322cd4aec2e535c4a4ea9792322aec244.nq.gz
│   ├── d356c1760d3666f5c09d4a3c666c81b4e8354f89.nq.gz
│   ├── d75835f0d315889da391326f76e9ff94c5f36688.nq.gz
│   ├── d963757fa6b229138d3bbbe421f5d7705727d065.nq.gz
│   ├── dc06bc1bb6b8820991da634f387743438eaf2110.nq.gz
│   ├── dcfc0027fbf1b3509a424cfdf9e8b400274e6e21.nq.gz
│   ├── ddcecf98f8aef64e2586e33cab5e1a1f81fa5ded.nq.gz
│   ├── ddfcec6bf6174170fd945f68c45f7abfba9bbb01.nq.gz
│   ├── deee78a32c4f553d47c40a1377d9a7d79e42f434.nq.gz
│   ├── df8383e95f2601e71d581efe6a0c37f509211938.nq.gz
│   ├── e7237e4aa965dc8b33de871c6d3f977a7bdd7053.nq.gz
│   ├── e7b3a2a69fb3aa856f8832b3abff0c69ef4d043a.nq.gz
│   ├── eaf7a9cb19b0ce8806b0d7903017032efb4a4c8e.nq.gz
│   ├── ec1adfde26ba1bd77923f70f29be11cc91ac3ce4.nq.gz
│   ├── ec1c0dd2d9cba1402b8e208680bec6eb760e4db6.nq.gz
│   ├── ec5644fd3db7653952b809013894eb5f3ae7afc7.nq.gz
│   ├── ed0add9c6c93580cc4f914000c44be27fb80dcde.nq.gz
│   ├── edf684356ab14b7db31b4afa86a5fe23db922b2e.nq.gz
│   ├── ee85e8e84af0ab056aad3d2f0e46835fee5c1ee6.nq.gz
│   ├── f064db7c7dfd600d6527aaa21f61a49dee1ba58c.nq.gz
│   ├── f2616c72b392b9d5c0dc250df4a2c0e707909d75.nq.gz
│   ├── f455850230d17224d2bc5d4313653ea17d9f8f21.nq.gz
│   ├── f5f5312ee5004a01ee9e4dc4fe57012e2ea8a4b7.nq.gz
│   ├── f6a352994fc8e15857b07220ed1b098bdbc0b212.nq.gz
│   ├── f77b277c43e04066cfaa9fc2e5e9b3d40ec44ba3.nq.gz
│   ├── f97f0b956b3a127afa1871c4876553f6a4fffa25.nq.gz
│   ├── f9b6cf595aae3bf170211470f52f61f1a37707a7.nq.gz
│   ├── faa937c95997a04a6af29d0594ebaec6ea755dbd.nq.gz
│   ├── fad0d82f31a0df49c416317353a12fd1bbbeb4d9.nq.gz
│   ├── fb1e14fb9f0b836fe694abc886d06cc4b9ce502a.nq.gz
│   └── fba0e6beae5b7ce8a67e30afa8b048ce97399b7b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fe7d9c919bf35fe149feb42e51ba9c5c337e3119.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[pyeve/eve](https://github.com/pyeve/eve)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
