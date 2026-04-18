# Repolex Knowledge Graph of gruntjs/grunt-contrib-uglify

RDF knowledge graph data for [gruntjs/grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify), parsed by [repolex](https://repolex.ai).

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
lexq download gruntjs/grunt-contrib-uglify
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── a3f3f342331326b42a22a6003df4da305a72cfbd
│   │   │   └── chunk-001.nq.gz
│   │   └── e410511e11ad1307cee15bdc18682e569c63e2a0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── a3f3f342331326b42a22a6003df4da305a72cfbd.nq.gz
│   │   └── e410511e11ad1307cee15bdc18682e569c63e2a0.nq.gz
│   └── repolex
│       ├── a3f3f342331326b42a22a6003df4da305a72cfbd
│       │   └── chunk-001.nq.gz
│       └── e410511e11ad1307cee15bdc18682e569c63e2a0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bc9385f49123cc9a3ec71507ed600d255ec039.nq.gz
│   ├── 02b0908eeddc3b2c5e520c6a9d59e98b3f4dc579.nq.gz
│   ├── 045c41d4beb83badce0b5be82748c51a8ac7e4a6.nq.gz
│   ├── 06217c8d61f1611af7882750743d5e30230aa09c.nq.gz
│   ├── 06f2740ea24feffcf1487b339d84b80613c8cc67.nq.gz
│   ├── 0d19e51767e01ab1f1337ebe52d5d719e18cf306.nq.gz
│   ├── 102b1e367345c6111efc9ed3658e0637dfbdebb3.nq.gz
│   ├── 1073d15045c5cc10546bb5c91cfdeb84cc460772.nq.gz
│   ├── 113aa3453011c7d7646dee370c2df239ded59550.nq.gz
│   ├── 11d17880489ce194483e2fdbef29eb4eca4ce190.nq.gz
│   ├── 11e281b099d09cfa8954a64a62cb727ea75759ca.nq.gz
│   ├── 1bc1d2bb5af411ac5699f66e36cc0c89125e97d7.nq.gz
│   ├── 1f2f86feb54950846ae4796d5b950366ee5d5031.nq.gz
│   ├── 2121b684cffb9dd6951a38136cd484819babc459.nq.gz
│   ├── 21bdf578c525fc7845ff5d0ebf4c93fc70748ff6.nq.gz
│   ├── 2b4012c5bf5682e90c72cb98326feab66dcc3f7e.nq.gz
│   ├── 30ac5375234d366f5b11797f17192016a1bbd5c9.nq.gz
│   ├── 31fd083fa8b6eb0cfc2d1475b317f31410a82a28.nq.gz
│   ├── 32e5578f3fadb7b4d3e369017ecedc7a81158274.nq.gz
│   ├── 33c64a6501c3f861200eb6e0058c3d9b47e0d34a.nq.gz
│   ├── 3e7d5b94de9eaa93304ff3546464cfe0a0721d2e.nq.gz
│   ├── 3f5326fd0cbe30390ad38d2bff8588c80943130f.nq.gz
│   ├── 431be3be22f00992c63c7b8cc744e767c9804923.nq.gz
│   ├── 43c7a8eccffa17c22d01863f7720ee6e07b80446.nq.gz
│   ├── 473051f895be0db88b108927860ec0e937708fe9.nq.gz
│   ├── 4a3ee4d95923cb7c1bf33a9d7f188124b91a2e3b.nq.gz
│   ├── 4d0c6f6010158c0bcc32353173379cde048e6b97.nq.gz
│   ├── 507f91281ddb349f4b46006c67c28165b7690cf6.nq.gz
│   ├── 51750421927b1f89cff075eb34964233051364be.nq.gz
│   ├── 5285e4db4eed20210f0c67f6bb7428d9d4096f5b.nq.gz
│   ├── 57f277190bde4e1c7690803a9ed7a452a2b6c633.nq.gz
│   ├── 58fa93c5f4ee321347e3e9898c36c933d0e5ed2d.nq.gz
│   ├── 5902dda1dcb9284267f48a0fd3ff7e7ecf28d6a5.nq.gz
│   ├── 59290ba1bd5fc491900d821b459e94d8f2698220.nq.gz
│   ├── 597bd5d16c7aee0ad90f38a61d63f4239f9e8628.nq.gz
│   ├── 5a52dfb092ba5647862502277faca85331225e5b.nq.gz
│   ├── 5cf0e64532be2c506323a06257fa6e516f4f0ca8.nq.gz
│   ├── 627262c3ce9361cc506b204aabe387576221af5e.nq.gz
│   ├── 649c89d95ec1b9f09516e3f87111accf8e369550.nq.gz
│   ├── 6b77e9ac2316da6d60f5e03ab896e23697fddcfb.nq.gz
│   ├── 6eea0102b673ec4d5dac2f4a04bef23a6b371876.nq.gz
│   ├── 7095347a6d29abc84046b1393cca09a475072a8a.nq.gz
│   ├── 70ce11e5c14c5fe3cc9656f45f46e6cf84a24641.nq.gz
│   ├── 71c305a8036b4a0232dfe1e5440a5950ed89079c.nq.gz
│   ├── 737b4075dc3159136257761f753c38a1628be626.nq.gz
│   ├── 73ca2e464f0877323b31564143c9ac99d887d3a7.nq.gz
│   ├── 75c69d51ebf6936c1d0f2ce71528d3fdebd61a46.nq.gz
│   ├── 7843e6246b3f63cbc06fd516128a7b55f953b126.nq.gz
│   ├── 7b3c59395473b99484767fcc3110328738e56673.nq.gz
│   ├── 7eefd1c377cdf02c1a4ace16cbccf8f84ddf59de.nq.gz
│   ├── 817a4bfc87e0ac28cadfdd3ef662748c3150ef26.nq.gz
│   ├── 8486974c1c326058f9053f67256300f235d04790.nq.gz
│   ├── 8782025657c35e80010793dbd9a91c6ed4436419.nq.gz
│   ├── 8a6bb706a0eb3a021e3b0485d5200d0ff581bff9.nq.gz
│   ├── 8fbdfc1e69e1e0cc5e1ce33a84f2def0d0ef1eb7.nq.gz
│   ├── 92146d2a6ec533291d9722010828b99fb45fc4dc.nq.gz
│   ├── 96883353d0e397aa34cc1342b3594eb7bbbdde96.nq.gz
│   ├── 97a6604768bcce17b5b334753d58e133d34db8bf.nq.gz
│   ├── 985a89c129f3fe5cb235429bfc6618fe24cdddba.nq.gz
│   ├── 9cd2be3e8e54aaa3935ba89a3b660ffd4ff9f0f3.nq.gz
│   ├── 9e429828e38eeabdc5c4992de65c19df20d75f15.nq.gz
│   ├── a17bf38f43ce26bd1471b93b06b5dddab171a08b.nq.gz
│   ├── a390afd52386c961e83731c8111175b966ed16a2.nq.gz
│   ├── a74a4a40ce2fcb0816f88d7fb28c4250a516fc15.nq.gz
│   ├── a8ae2a31c9504db725cbc12db21d418d4e9a7511.nq.gz
│   ├── ae935c11d25282a1072de66ca59a9f8819315899.nq.gz
│   ├── afc6d0bc063298b6da45842e6d489139f0154166.nq.gz
│   ├── b08ab1161a41e79fe110b7fae9b5747c59efb903.nq.gz
│   ├── b09fc91c4050a9f22838e2ef587ac88a8f48b033.nq.gz
│   ├── b3f8b464a27b808be64aa833ff8e2544cac028c9.nq.gz
│   ├── b4e7f5fd216ffafbee5cb477f8e52ea2057af219.nq.gz
│   ├── b9128b27fb462bff50e5352d07a3cd31726848e7.nq.gz
│   ├── bae7d9f6644e9b930823deaa946e44438e84633e.nq.gz
│   ├── bd376574c2d2ad859a63623506b012fd7e4ce8d4.nq.gz
│   ├── be1f43e24e2e67dba2920e20be559768b9486c7f.nq.gz
│   ├── c103b6cbf2620d8b959dd5073a2583e247afd707.nq.gz
│   ├── ce5c9470251ebc429c6927268f6977a746cf3cb3.nq.gz
│   ├── ce858adef539149c3ffd31ccec91b4c8f1099ba0.nq.gz
│   ├── ceeb8555450a7a686361f8733bcecd1cca37ef0a.nq.gz
│   ├── d077038d7ded850397d09b352ff42e44fad9e2bb.nq.gz
│   ├── d0e5c023f005f52680fdb152e8ba1e0dc979cb33.nq.gz
│   ├── d2c91558561c3e66dd162cb103ac134000196ca4.nq.gz
│   ├── d2ef1323d23d8f53fbd683a929b8ef0bbdab6270.nq.gz
│   ├── d41cea0e3c4dcc7640a8d8d28b1537d685e22e1f.nq.gz
│   ├── d4e5147f8edd433046ab9180cf5108bc59e1d6e3.nq.gz
│   ├── da8c0b47f570d08342d033660cd5ad498cfcf8e4.nq.gz
│   ├── dc3f7248b736f616d878503489f7d74ff9e76903.nq.gz
│   ├── df6b5ff474d93fe475a2966be5db25f3aca58872.nq.gz
│   ├── df7f1fca90ab6ce67e8caffa515d4710ba68844e.nq.gz
│   ├── e6e9d1273497f8aade4d5856b2f07d69daed4af8.nq.gz
│   ├── e76446e9c0abd9d14f7d27cf120526e5c9991426.nq.gz
│   ├── e776b3c320cbb6ef3391a724b0d27c9341a126d1.nq.gz
│   ├── e79c3cf760012e5dc6d03f117fdf9952bb35b7bc.nq.gz
│   ├── ed8bfff892f0a673627a4fbb03ef1da5ed8b8eb8.nq.gz
│   ├── f0a7b643baf27f3b710a863bf42b01da41583a94.nq.gz
│   ├── f29ade854f0362d6920caa65308b9c5fed96ad91.nq.gz
│   ├── f2cb796a8e45aa5d650b77a184c66fc481fa4951.nq.gz
│   ├── f7e56fcfd7e0287e1d10585a375919d9127341ad.nq.gz
│   ├── fa590f63f90dabf1ff0f4b248d040078cedd9796.nq.gz
│   └── fd965a8917cba023dddd3f2a4a1fee71f477ff00.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── a3f3f342331326b42a22a6003df4da305a72cfbd.nq.gz
│   └── e410511e11ad1307cee15bdc18682e569c63e2a0.nq.gz
├── filetree
│   ├── a3f3f342331326b42a22a6003df4da305a72cfbd.nq.gz
│   └── e410511e11ad1307cee15bdc18682e569c63e2a0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 115 files
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

[gruntjs/grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
