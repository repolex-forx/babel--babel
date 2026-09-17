# Repolex Knowledge Graph of babel/babel

RDF knowledge graph data for [babel/babel](https://github.com/babel/babel), parsed by [repolex](https://repolex.ai).

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
lexq download babel/babel
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2376757d7a42c6785b24091144ef7f00df7d436
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── b2376757d7a42c6785b24091144ef7f00df7d436.nq.gz
│   └── repolex
│       └── b2376757d7a42c6785b24091144ef7f00df7d436
│           └── chunk-001.nq.gz
└── blob
    ├── 0001d2c4547ca5d2273bf7553719f764439abfdf.nq.gz
    ├── 00045ae823dec5030216cc287edada81c6b00c39.nq.gz
    ├── 0006d5963410a955072d4e966863992c5a9de4ec.nq.gz
    ├── 000cbc8067c61702f876ecaeed8bd783d0fcaba8.nq.gz
    ├── 000d34966b47a0e2060d34f483791cbd2226ae4e.nq.gz
    ├── 000d60c741d3c4ebeb46c5354d493dd89ded6d4d.nq.gz
    ├── 000e99bcf250c23faddb1f69265c344e9bb465c4.nq.gz
    ├── 000ee41d24780a22562769e873f86b13413ba3d9.nq.gz
    ├── 000f2fbf3772dcdd29d7ef630b5a5abc5d45213a.nq.gz
    ├── 000fbd58f4d0273ace1b9f09278280a8311dbbbd.nq.gz
    ├── 0011015b1c26d80a720ecb58d89ef5d6f0b72116.nq.gz
    ├── 00121de2f8f462272f7e5e89efa1b3d93625681d.nq.gz
    ├── 001239c2838ae219e355bd061650acadf38acceb.nq.gz
    ├── 0013976f61bb4d73207005d472a24b41bae64477.nq.gz
    ├── 0014f490362792c4987d5661ad8269d06dd49c30.nq.gz
    ├── 0015000facc8aba220b3c88fb9bab06fdb6d77c7.nq.gz
    ├── 0017e9111b53954f1f8376078324253f8060e2ce.nq.gz
    ├── 00185a9e0b59a519770ec0be8d09911c3eaf3fe1.nq.gz
    ├── 0019ac9cdf1c20659f1e2a59030442aced88a2b1.nq.gz
    ├── 001ba9d365989ec7733c2049eb4e8275823c0768.nq.gz
    ├── 001c7217b72259d964f66ec518293c194f26ab42.nq.gz
    ├── 00206c855d82fc1c6cc21626bd2c6314088f68e9.nq.gz
    ├── 0020fd9e3d89ec2ad3896728eadadace4b073f3f.nq.gz
    ├── 00218c0e04b4217bc11b5543210ca5aa7f46063b.nq.gz
    ├── 0023e5109a7b951c3151f27845611a8cd9040bcf.nq.gz
    ├── 00243fe0d8028267fa02d8de8ba069ab566897a1.nq.gz
    ├── 002513eb8a1b4afc98cc3562c8934de78cf7ba49.nq.gz
    ├── 002801102404e159288b05f6a7387f4d6395c57d.nq.gz
    ├── 00280b3814f57c3b7515b815f97be50c1d500f15.nq.gz
    ├── 002b4aa0d58ec481a2688d3c0b66e9069e5d6adb.nq.gz
    ├── 002c642fdb270d56a73d228176db9ca6e429bf16.nq.gz
    ├── 002cf0afa663f2b3a292d2c7ed67980fce3b62e0.nq.gz
    ├── 002d71514e65493fd81ad7eaef67ef5402bc8b6c.nq.gz
    ├── 002dd1091c55db6a3829da751aa8dbf576111547.nq.gz
    ├── 002e11dc4f0c75aa9c744f7f35edfe078eec924d.nq.gz
    ├── 0031d64209aa12226920f5f617c92240a4903d62.nq.gz
    ├── 0033e2f7d117d3c8aa3c6b293a369dda248c0ad7.nq.gz
    ├── 0034e868cc278d1fb04e421e731ad2133b7a6e2f.nq.gz
    ├── 003667938889bba1db008744277ee09347c49db3.nq.gz
    ├── 003857f80294c3b90d3e6f79ac9f299a0b7124e5.nq.gz
    ├── 0038b79005e1d31e3b44e79a3d31818fb4bcd788.nq.gz
    ├── 0039194b113139ceba979b0e545cf3a6cdb22f92.nq.gz
    ├── 003b67cda8cb78916321cb755635deeb5c550161.nq.gz
    ├── 003bb1168d33a29371ace02fb03fab1b0314fd30.nq.gz
    ├── 003c94aa45515560201214ebb26e718a4c1153e6.nq.gz
    ├── 003d264c477aab6cff0027246a6974145dd45d59.nq.gz
    ├── 003d71f6aee0d8495f62dce444f07e358c70eab8.nq.gz
    ├── 00406be1c808e8ea83b04e65f05c466d1d76afe6.nq.gz
    ├── 004122f366e1aeaeb9edddb5288266f5193d4db0.nq.gz
    ├── 0043cff021581aa898cd85a0d519ec7c303d31df.nq.gz
    ├── 00440046c06ae176d9f29703a9fd4e5e4a1bf5ce.nq.gz
    ├── 0045e3f3d0ae0cc8563bbbf49cc2f502699be79a.nq.gz
    ├── 0048baa438b98404665989bb1f8c9fb29c535e09.nq.gz
    ├── 004925a9241052aab352b680c7b26398963fc359.nq.gz
    ├── 0049c235923c9cf467e04a5ad46a02c06258e689.nq.gz
    ├── 004a565a2f9e1252ebff36ad734a26e2152d5302.nq.gz
    ├── 004b86f7c591a37a0c84e01a6d4eaee84b8cfcd3.nq.gz
    ├── 004d2620b688a465bce8279d74ac4fcb8c09f514.nq.gz
    ├── 004d388a68aca317db9a9b3061fac66feb43e5d7.nq.gz
    ├── 00536f42839b83c81a2344a797fc4e5ab3a46fc5.nq.gz
    ├── 0054c4e8f4ffeabd9244a523b0c97881def46595.nq.gz
    ├── 0056c29b7ce692ba93100ac7d163c8006b9fe6ca.nq.gz
    ├── 005783bd2bb8f2b85c9b7298df36bbfac1668d6b.nq.gz
    ├── 0057b5dfaccb561bc6638cdd202d7b9f8d24a9de.nq.gz
    ├── 0057ceda7c2f34724df62b92aabcbbc7b8a8ada1.nq.gz
    ├── 0058fdfd1c637ddce50e87ebbcf715dac3296ddb.nq.gz
    ├── 005a931a5bfa68ef3b991033572c541153e0c53f.nq.gz
    ├── 005c453f8e2f709e0eba2a303bb0e0bd3beaee89.nq.gz
    ├── 005dee282cecf78c2fb4c10915d3798c73a51929.nq.gz
    ├── 005df4e1244ee61febd21474b3f350c668fbe605.nq.gz
    ├── 005e1dc68b1975a237a387f266e5abf2a57108ea.nq.gz
    ├── 005e2f9b8237d253cb93720a94177c39f0ba6e05.nq.gz
    ├── 0062a566b9dd57702caa0c09b917b8afd7d9afb4.nq.gz
    ├── 00635245b1fae51c858a98bbe4c3523f4e95e1a0.nq.gz
    ├── 006782bc3f9aad250f84e1d15b5846b69c8e9abc.nq.gz
    ├── 0068d7afd052ee31b2e270ff4dcc6cf3ad7063b6.nq.gz
    ├── 006937a303922256d83bf70478b6ddb13668d83b.nq.gz
    ├── 006976fc0e969d5c4fb24fc12919aea92fbd9be3.nq.gz
    ├── 006b36a2707f250e2c362cf5dfae65addd1d7d50.nq.gz
    ├── 006b6dbbe75dd281012a064de54bb37e01d9f4f4.nq.gz
    ├── 006cc18a3cddb66b8d8abe5b5a8669143b3c6c96.nq.gz
    ├── 006d88ac3f8bd9af46a8effb7393f85566fea8ce.nq.gz
    ├── 006e24cdb6dadef2847bc6e20922a2e46e9f226c.nq.gz
    ├── 00703912fe2a8a898049572614abb2d255a26505.nq.gz
    ├── 0071bd7a9bc537c20cfb2a0d2be959d3f333db6b.nq.gz
    ├── 0071c97792ff2a43e29d3410fddcadc5ecddfa7e.nq.gz
    ├── 0072c9dc6eee015ff42091f3e9c32fba26b738ce.nq.gz
    ├── 0074b0321a3b35c5cd3c149a2de972456e702ceb.nq.gz
    ├── 0078a25490685599bf3139d62ef15bfbbaa70865.nq.gz
    ├── 007971dfc41b7b29d725768fdda6e8dc34110260.nq.gz
    ├── 007a76d4d37586e2a0759e042ce56d145dc02790.nq.gz
    ├── 007ae280e2fc09f737bb973edad5e38b6feb547a.nq.gz
    ├── 007dc869bdabe65144381d93a82492f3a0e2cc9a.nq.gz
    ├── 008047ca62285de82a66e2aee85fdefd768706ab.nq.gz
    ├── 0082fd52b4423c24f24d521afc82de9f56d26dae.nq.gz
    ├── 0085c57dcafa628493c02b6264419dbd70f18253.nq.gz
    ├── 0086c2611c6e381524af94005b80ed47724db027.nq.gz
    ├── 0089014a62dd119db9e11e0a93db05a3ff6ffe48.nq.gz
    ├── 008af74cf78aa6347c840dcdd8ae5274b4ad85f2.nq.gz
    ├── 008f56a84bccc0f4ae181277b65f9a32d1eee04e.nq.gz
    ├── 008f85eda2a4df00be7a850c0b9b922bc299e5a4.nq.gz
    ├── 0091a95bcd6dc13c041f8ca5f5d473242e2a9301.nq.gz
    ├── 009433301e2c7264e7b59c0002949c8dbc08935b.nq.gz
    ├── 0094b9f040db3133f071a92a90c794b73f23eab8.nq.gz
    ├── 0096911c414ded55a7c29766c25d59fb0add7cf8.nq.gz
    ├── 0096fd72841fc621654a100f2070e6b879715884.nq.gz
    ├── 009749f7a4949f4ea2e9b85bf790be2e9650b289.nq.gz
    ├── 0098d5b57b49ce30137fad1877f3ff349ad2ee09.nq.gz
    ├── 0098e2b67a07f6d34a2f931df1fc2cfdc9331056.nq.gz
    ├── 0099cf0db61be914b69b15d916eb6a6915299402.nq.gz
    ├── 009b24e29203da67f0575a4828ba26c6c4fab06c.nq.gz
    ├── 009c01f8ac9c218d18d3c5ca0dfffadef435c748.nq.gz
    ├── 009c839453047017dc7bce2d879e8e01faccac86.nq.gz
    ├── 009e916dd701fe7964a6eb1a856a81d3cdd432df.nq.gz
    ├── 009f7cf089bc2bf7205cc527f7462d8d29684d2b.nq.gz
    ├── 00a25840087190c844abad32d4ae185260446822.nq.gz
    ├── 00a2dab45ce89eef5502f3be72280cad5b16efca.nq.gz
    ├── 00a3052e4e282eb239390ae6bf05e08e38b64685.nq.gz
    ├── 00a35d163ef1bdc229babdbc8bdb6fa35c3b4c45.nq.gz
    ├── 00a3d035df8c68cbc31498338e74c9eabc42fbd4.nq.gz
    ├── 00a5095947a5fb43f2afa5bd8e92c4485bdbe94e.nq.gz
    ├── 00a73cfe3736f80a8dea74f605ab805cd8e8b649.nq.gz
    ├── 00a7c78b9344c69d045f432a760132a9d25e0472.nq.gz
    ├── 00aa9148b536236e91a74774353b4f4005e427f7.nq.gz
    ├── 00ab717c3abf776344cab1d245b12269d87c617b.nq.gz
    ├── 00ab85047e4d3cb7c0280fc43d2e3acad55b260d.nq.gz
    ├── 00aca3089100dac4bbb2acf3bca187e591a2b52f.nq.gz
    ├── 00ae88a72e4d679815c52e644527d1d513c74ef1.nq.gz
    ├── 00afa7e28f5befdc870b6843433892009fe6e7b1.nq.gz
    ├── 00b068774cede368f7e5f3926bae71be3f2a7449.nq.gz
    ├── 00b7e44028a4087abf9ac1f485fbac60e78ad1f9.nq.gz
    ├── 00b816f4bea8a073d2ffd7a37ddad80d44c26d0a.nq.gz
    ├── 00bcc4bbbc24a30ae4639b9f17286e4e493bfea9.nq.gz
    ├── 00c067be3ffc02be94b36189a5da8dd6ac76612f.nq.gz
    ├── 00c1e1ae180de7b2b9421112ec512855c0b0e702.nq.gz
    ├── 00c3211a936d23ab79c699467550c1e06ab006b3.nq.gz
    ├── 00c410b2295c8668a8aa0ca20589e4f3077f3a03.nq.gz
    ├── 00c4bef4004dbb82e16f6c26fda934358d9b2621.nq.gz
    ├── 00c57bfe1045cd53b0a74ea538ee51cd0ed6b8b8.nq.gz
    ├── 00c5e76f0d7b2261ab0874cf1b5c6baa9dc04b65.nq.gz
    ├── 00c699469236bffc1cfe7e003ab1caffa24b0377.nq.gz
    ├── 00c80d5af72295a8f6545e4227167316ac3b6d53.nq.gz
    ├── 00c96adcd9ea96dd0126ea1a84aa3b77c27bbb55.nq.gz
    ├── 00cb9573c02468b655b9ba51daf416fdf342e8a5.nq.gz
    ├── 00cc14188bbe35b84e3151ca00c1a2ed8a32bf15.nq.gz
    ├── 00cc3b635df5e5b958fea4b4c193c505591aaabf.nq.gz
    ├── 00cf2ae322b4020ed4a44c9fe396aad2f2dc3bb3.nq.gz
    ├── 00cfb4b05ecaaeeaaad941a977a9d1ba9ec4c602.nq.gz
    ├── 00cffaecf3673144a19c95544ccbd8bfcd44b138.nq.gz
    ├── 00d047df1dad069683244f695e16a1403607507d.nq.gz
    ├── 00d16282a316128d96b28a1e99913607a5ed2506.nq.gz
    ├── 00d1c2320d2fe404b162664346b02cbd29ab71d8.nq.gz
    ├── 00d36e9a23c079f2ccaf48c8a0f8ea0c99cd0648.nq.gz
    ├── 00d50846e973391e7207de8615d34067b8de4494.nq.gz
    ├── 00d59b89a1ff2b8ccfc0cfcb35c9c06242c76c63.nq.gz
    ├── 00d6ffaddeb315c566002b20915667e68b1a52ec.nq.gz
    ├── 00d724403614ff78ad1e42a93e512a9f234a9d72.nq.gz
    ├── 00d819d9d446e9f085059d4202d8517391c15126.nq.gz
    ├── 00d93fb5d5093ba33cfd582b8887a10d8614f8b4.nq.gz
    ├── 00da0e054c4f58408aa959dcc10e3119d028aed8.nq.gz
    ├── 00dc7c8dfe3313bf9e953c5e77058e3232978919.nq.gz
    ├── 00df96e2b6444fd3d5e8b245b12cf3e8b081dc56.nq.gz
    ├── 00dfc30ac394eb61bfb727e73441d02e25eba4af.nq.gz
    ├── 00e123b656c503f9794600b6f700b5305d7600bf.nq.gz
    ├── 00e25f4094fc0ca6db69deee6185e4d49b9a6c3a.nq.gz
    ├── 00e4c4cd68bca1057d763f4d87ebcb10a87a2550.nq.gz
    ├── 00e676cb6cfd49f9e7f69772213058b21c9b9c46.nq.gz
    ├── 00eb198f49c38663de5fbc17940c1c8a0bc770d8.nq.gz
    ├── 00ec8f8098493de403928f7eeb4e8c45d70241e9.nq.gz
    ├── 00ed1c2cc1820e066fe9cce2e287b75c2287b9ef.nq.gz
    ├── 00eea498cbbc832058d6945ba50a16c258e0e3dc.nq.gz
    ├── 00ef26d6cb6bfbca5f5717749cad9eee54298324.nq.gz
    ├── 00f2c61d770d4ff43ffc9c2085e16e9023379d58.nq.gz
    ├── 00f849927e951cadbda86c7799a3203818a2bc56.nq.gz
    ├── 00f9dbfaa81dc60cb4d24af2d84a6ad9648bd357.nq.gz
    ├── 00fcd3fbd03494ff45ceb3959341c8dc8ddd8c0f.nq.gz
    ├── 00fea63b9da422a50836c1c3053f1f0f907400d9.nq.gz
    ├── 010019f81b887111100b668da6ba6de72f2f6ba6.nq.gz
    ├── 0100e137ff7f6a236cd714fbce03b55d04a252fc.nq.gz
    ├── 010117c937876249c84dea6dafbc9d912de7031f.nq.gz
    ├── 01031d38b1cbbe88aa1f83d2469407a683c562b8.nq.gz
    ├── 01032c9b064237a280942689a592dd934faf132b.nq.gz
    ├── 0103e2c92211d8a9fb512b5c8062eeb615c00def.nq.gz
    ├── 01069f36038a8454389e44957c3dc124f9d13c0c.nq.gz
    ├── 0107407855f2e53c2b518a4d1a1b44669015b27d.nq.gz
    ├── 0107b7623c2595c2b2aa53f622ca529715dd87bc.nq.gz
    ├── 0107e6652a621f656cd4382d626eb89d5f68d3bb.nq.gz
    ├── 01084aa6f6f42b8e9097dd33dfd5929031b3ec29.nq.gz
    ├── 0108538d3de16e75950f6efde34496dfb9758c49.nq.gz
    ├── 01086419eaffab966c8f2f31378207c860a8e41b.nq.gz
    ├── 010a989dfc1c7b593c04a476503673f29203dbd5.nq.gz
    ├── 010cc940efd882a837f59d014b9c78deec3ef3a0.nq.gz
    ├── 010e5bd09a6d44438458c9c6a0c53ef4b0443d62.nq.gz
    ├── 010f0790c7ed0d04a80183d0beaafe210cb77d5f.nq.gz
    ├── 010f1c5fb077fa36f345bb016108c5f355c8f632.nq.gz
    └── 0112cb64d90777c29694420f5bca864a46ddb065.nq.gz

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

## Source repository

[babel/babel](https://github.com/babel/babel)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
