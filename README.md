# Repolex Knowledge Graph of bottlepy/bottle

RDF knowledge graph data for [bottlepy/bottle](https://github.com/bottlepy/bottle), parsed by [repolex](https://repolex.ai).

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
rlex download bottlepy/bottle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ec5fe29420d14998c0d86885083983eaea8b839
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ec5fe29420d14998c0d86885083983eaea8b839
│           └── chunk-001.nq.gz
└── blob
    ├── 009267b231b213170484fa0f450759c384a37b8c.nq.gz
    ├── 02219b7fb98b40683059e92040b9f568769cdc8c.nq.gz
    ├── 03fad18514616091730454422b741a30407a4eae.nq.gz
    ├── 043653b3044ee80d290aa26c04314234a809bfb1.nq.gz
    ├── 0532420c31fd6cdc2dc568f11b75d16cf3b4c72c.nq.gz
    ├── 062851b5780789427b3f44bc7a64117270b77c0a.nq.gz
    ├── 07db52ca607d82ae8ade5d3b0d7bd69931aba87b.nq.gz
    ├── 0b1c452ad334f2900a37c311b97e8cb2b22be1b1.nq.gz
    ├── 0b4edb420061dbdb3864bbd92298c80d64da77a1.nq.gz
    ├── 0b85b4744caedaf4e81f5b1afad2a99b59fe425c.nq.gz
    ├── 0cbdc00f6aab0601c0587f6349c2c75bd47218b9.nq.gz
    ├── 0cd7f170c238e70fe6c52543169670bea4193bc6.nq.gz
    ├── 0ef9aa277c56b8cd1ed8481247d5ac7e991a5aca.nq.gz
    ├── 112b0b34f53d003cf28e9be66f46a5e580431487.nq.gz
    ├── 1310a4f078843612753a96b962cd48ce046713f7.nq.gz
    ├── 13adf2fe00ad721e27f9f85d8a20bd86750dec49.nq.gz
    ├── 141165593b8e74c3ee93b914a13859d0b18748f9.nq.gz
    ├── 14880d58a8c4bd058d74a4c888a693ff8d9f31f1.nq.gz
    ├── 15da64b8b1bb74d269c7d04acaa140a699335ae3.nq.gz
    ├── 173dd0f7d3753d6cf54abaa0ef41d190f3faf5d6.nq.gz
    ├── 18fac9a18a1a0491cc068925b21b2ea4e5bc0207.nq.gz
    ├── 1a40fdb8de4bdc41488a2151172b39365d6a87b9.nq.gz
    ├── 1cf8e522349844a267b935f49b69dd3463174fbe.nq.gz
    ├── 1db0ac9583b8788b963ffe70f80577bb7622a905.nq.gz
    ├── 1f581a74fa00b31907fd8e6534971b251128c8ea.nq.gz
    ├── 1f583db5f8533fd4f65ff56f8a68294ad0263a34.nq.gz
    ├── 20be7a1035ed26e23ddff9e77657739d1d0b4993.nq.gz
    ├── 211b0fba0b94a5ef3a3e132140f2bee6a3dc9e90.nq.gz
    ├── 2148997408c6f77462e297cfd6ca1190ace49330.nq.gz
    ├── 22dc44d4e53b54d42966ab63d56dc67db7c427f8.nq.gz
    ├── 2721c08cb41239e59d4dfd69cb904c46df7a0e8d.nq.gz
    ├── 27a1c281e2d211da13c6de86510d4f903a016e77.nq.gz
    ├── 2840edf4e2e719e64b669d93da0de77292085638.nq.gz
    ├── 2b8391f31acf206012a96021ca63a61aeb78ef4c.nq.gz
    ├── 2bafd37306df02a3f0b582769b8ef9fd9eb53192.nq.gz
    ├── 2d5a1d6b5f72c5b7b8d5df735bc58616eeb32841.nq.gz
    ├── 2e5bc4a87ede77b30c45e91790ec81f11fe6d535.nq.gz
    ├── 2e91d800ef397ba81566633b5ca905520cfc04a0.nq.gz
    ├── 2f3df0754dd52281cb05068c81c1e69949071572.nq.gz
    ├── 3087c6d54e209bca82ec6ffa7987c7a461e65ff6.nq.gz
    ├── 33958d206714a3fbdea88b1299bab5d45440dd1e.nq.gz
    ├── 34e6ed340d53b054f0e6c360fa090f3b2e776024.nq.gz
    ├── 35712d06dce4a1adb637dfd29cf9bbfcf3f34c22.nq.gz
    ├── 38f8e3b3e3571bc8fad4caae8ac1599307a57ce4.nq.gz
    ├── 3a6cac0a37a5275e3acb32266f2e4dc3dba34800.nq.gz
    ├── 3f8619bce3aa7787df2418b693298b5d8761d5f5.nq.gz
    ├── 3fa8b83b0764399cc8643493a6f8d333f66b0f26.nq.gz
    ├── 4572ba4a3585d2289fb0a22f41fef756cace7742.nq.gz
    ├── 45b9653afcf46b0c180537361bd91721d28084df.nq.gz
    ├── 460890748e4038697c33af5c8d5d30289f9d4b2e.nq.gz
    ├── 47952077c29800a3b018a1d6a0c9f455ac3f498c.nq.gz
    ├── 47abed3e11b1e801f09190bc2d6435b5db3d970c.nq.gz
    ├── 49c9cca96109c22004c76664a1397e755cf3e880.nq.gz
    ├── 4a9a7c1b1ea1c31422570a3afcbc7202ff39dc16.nq.gz
    ├── 4c48ce6afd504a5fb7a42708493b090ed5697f94.nq.gz
    ├── 4e32c68791b326c2837c4783c6af22e02d58a634.nq.gz
    ├── 4fa8dee8388a7d0ecf9253d6355f6748ac19450a.nq.gz
    ├── 5358ecba7fd0ed95d3ab701071e52507747df64b.nq.gz
    ├── 55c5d4c9c3b1fa6e2ce6707a3bf8fd8e2d91ce14.nq.gz
    ├── 560af4b5ff81aafaf7c06571c8d9850c24d7c15d.nq.gz
    ├── 58411095971eeec4360507baea854c9fdadcfe25.nq.gz
    ├── 58dd992e43efeb4038d9e91fdef4b5d0f2c04940.nq.gz
    ├── 5a552b4d641861d97cebe8f08b779e04828391b9.nq.gz
    ├── 5b80595be98f3517dfdced0deb23e97b8913daf1.nq.gz
    ├── 5d811397a7b0c48e7fb2f015d5c4792600266aa1.nq.gz
    ├── 5f2766ef176bfa4f01c65e767667b3384deb3323.nq.gz
    ├── 6047d01f8f103bfa34915591bb217ff7fe3d60b7.nq.gz
    ├── 63f6f23af3e452f8e942a6a5f2509f15a5af7e7b.nq.gz
    ├── 64f665868493464d2757434fe1c9dea0429a75d9.nq.gz
    ├── 67e00de2702cc8c982c8f0c28801bcbd7da80785.nq.gz
    ├── 6ce66f67cc7e7da9b25ccc642b03be06986f244a.nq.gz
    ├── 6d1b8aab3aa44029f1595fe28eed9ef9e26cd4c4.nq.gz
    ├── 6f3c1ea6cf0eaddeeb7444cf98a3bc18d80aad31.nq.gz
    ├── 702fd3cb76300f4f22ef62592c5310f4dd0a0723.nq.gz
    ├── 7090fc9518e353079fe0237f811d4f94e5a42985.nq.gz
    ├── 7152b4390b3d5292559a4242db630c286a11658d.nq.gz
    ├── 73e37ea0a598030af7f05a3ecd266914274d6509.nq.gz
    ├── 73f37d32034ca5230c6b6ab6c2be9a9fb5db23b0.nq.gz
    ├── 7460cf11239bca4481389e06348d84b0b1938813.nq.gz
    ├── 75ff7301d96023f37b09449740c1f82d991f7c41.nq.gz
    ├── 767546daad3537f0b4146929251dbfc2bf08b2f8.nq.gz
    ├── 789569a20474c461a5f9d9da746fd0dfc2d4d6af.nq.gz
    ├── 78fed38497ce0748bc5a3a0e2c8ea89e03105f8f.nq.gz
    ├── 7a64124f40c97fa41886436ba25aa089194b4cf0.nq.gz
    ├── 7c6dfce5fa8b4cb889495032021dc93ebae76675.nq.gz
    ├── 7cbc829376f0480a0b249fcb84fb88c2b148dbd9.nq.gz
    ├── 7df2850897ef789f4224ad7e0fa30e435d071567.nq.gz
    ├── 7ed519950c9f79cefaaf6093ba586efeddb6bc1a.nq.gz
    ├── 7efc38924ef7256845d07106cab15265bab0582f.nq.gz
    ├── 7f654d1e36b4e3e8d73955dc69dcc5ea602dec01.nq.gz
    ├── 81020b4bbc9d7921b4dd7f4d17783d240998b5b7.nq.gz
    ├── 8212c624e26cfc3802f201fa59b2fcc3322ed105.nq.gz
    ├── 829984a80603735d209e6ad8e634f95a7a3b0cd2.nq.gz
    ├── 82d4326f4ccfece0b26a0f2f7fe134dd7a8eafd9.nq.gz
    ├── 83b577623680526bf5ef3f3eddd87b24697aec28.nq.gz
    ├── 83e1669e0e4c251336880f7b3360d0a9ec24d3d7.nq.gz
    ├── 851a68b4aa1925f437b4fc034b90ea156f4c8d8f.nq.gz
    ├── 8754a3aad32ce5b77a2f650083ba6c4490b9cd58.nq.gz
    ├── 88ddea61c59c369093c96bd9552739fc2f78847c.nq.gz
    ├── 88e260b1fcaac53061b1e058e1dc0f4c8081ce96.nq.gz
    ├── 8adbc9dd82a8881bba25aaaae75b85d241e2248c.nq.gz
    ├── 8da5f66c21fcd7142265e5236f83354449e35edd.nq.gz
    ├── 8e410494568d49e910b7fda88f5c1e31525d7d56.nq.gz
    ├── 914a742322e3fae0906b52cfcf6f860bf480f34d.nq.gz
    ├── 935710117dea6ebac67131054af1b05d7abc44e8.nq.gz
    ├── 94990f2ee72b12d60fbecbe52550be5956cd2fcd.nq.gz
    ├── 95313acd76394a578bb77e42490ab84ca48344f2.nq.gz
    ├── 95fda3f5c290913a6762ecd59f7f7344a7cd134d.nq.gz
    ├── 9641e5bcea43da9edb549e3b4266c15a293ead81.nq.gz
    ├── 96527c22e748ebf3380fd3e9844aaf5ec8ae0402.nq.gz
    ├── 973748e43cf176ae7bf8f6619f4b2a1c06c4b86a.nq.gz
    ├── 9762b10b45984a7fba80c7718e6e32ad8b5540d9.nq.gz
    ├── 97c18da66170bfc493ac2aa601b19da8abffb35e.nq.gz
    ├── 99431ef19f3ebd591c22d07588e0fd620c1db949.nq.gz
    ├── 9e1fc9ace1214f515848a3b7b1d44f0d9ef5cc6f.nq.gz
    ├── 9edceafce9781e0bb35fb383779e4a7fbe5f3fb4.nq.gz
    ├── a080d2a82be392682e0f3a69ccce8ca721600c5f.nq.gz
    ├── a0dc626c0e905dd47e5318a128a5c8bcddc8770a.nq.gz
    ├── a1ecab1a10f07e4af1b8e071a1fc623a629ecaa0.nq.gz
    ├── a2a8701cbe0c6e5704720c7021e5947b99a04650.nq.gz
    ├── a3724abf0d29ea907bd5facc12985da2554e4ca6.nq.gz
    ├── a4730475d3b62d952a3d7d719b2ec3745e1947aa.nq.gz
    ├── a4f018bd189ffd07653b98c3daf8db5378d01fbf.nq.gz
    ├── a4fc7483e9a926e8c7d55fc100f4a23836a47766.nq.gz
    ├── a6a9d3ae651029fbd2db7fff1a7889b3353f84f9.nq.gz
    ├── a7729365bfd13546aa600dcc6c7c8e204932659f.nq.gz
    ├── ab49b4a586d26e9c97779dd03e5af11af86a839d.nq.gz
    ├── abfbe1f5062ffa00bfe7a8828533dd761ac5b8ee.nq.gz
    ├── ac148e80ce841e2baca3bb7121e90d9d423d61b3.nq.gz
    ├── ac418c1ab31d1a2e14fadf0b31b99991a1b12ad2.nq.gz
    ├── aceb42a6122171bba8a823aaedb2e2b5251efeb4.nq.gz
    ├── b10f28901d91fff590d6cb9a93ff0bd7482a014f.nq.gz
    ├── b1e0eef04f5c822507a7c8c31e249b9ee5737306.nq.gz
    ├── b1ffcbd57a52eed8b7a7ffdfb7058299148fa8bd.nq.gz
    ├── b2af7864d2eefb291069148a06e74d56eebeef5e.nq.gz
    ├── b3a3010e7f0cd38a038e8a7fb8ddece2e3e03fdd.nq.gz
    ├── b484cd558f5ef0dfc1ad4cacc6ea6f9ffbb12b31.nq.gz
    ├── b4b3c829dbebe61adec90f97fcff5db8c0e3091c.nq.gz
    ├── b603f966d18dc8ffcc0d4bc8ec835ceaa5f09d6c.nq.gz
    ├── b74b640405bacc8b5248d1454f8c1745ef699afc.nq.gz
    ├── b8154d5846d276945e8e10636a62034d8ded9af9.nq.gz
    ├── b82cef26ca3dd8970b68447584f9ed3eb57583f6.nq.gz
    ├── ba06f243700d7a64a2570545a226eb5a77542b54.nq.gz
    ├── ba9056a57724cfcd6f869fe6822870bb4e4e2228.nq.gz
    ├── bad88ac16bbdcaff371b9bb0f41d59e1cd488fa7.nq.gz
    ├── bb03b220c67c7cc7d9a443bca664f06d74958044.nq.gz
    ├── bee483bb35cce0da43beb08c8c69e8777c82ebd4.nq.gz
    ├── c02f793d4070a7df254c34947323666055924caf.nq.gz
    ├── c0ba7f5646e6af83c6c1e199a9fbe38845013d85.nq.gz
    ├── c167d89469a6d1d517532bde07e5c1e8d7b3f661.nq.gz
    ├── c1cf69f5403494c1800747390b046842dfeaf524.nq.gz
    ├── c4840b2721b1b0a7463a590dac814e0b44ef557e.nq.gz
    ├── c65e4acd66beccd80f9da2eb6123ff9197fc02d4.nq.gz
    ├── c80a8bebe0c9ff1280aca8c8c8f58c744581da43.nq.gz
    ├── c893663ce0c9a17f65964493e531df8e47d1607f.nq.gz
    ├── c8eacf79d7b9dda2d5a7ba5f7938728c66e5ada2.nq.gz
    ├── c9f2940ade3a3608a040a6a6b148cf0576c6a7ec.nq.gz
    ├── ca039803a39be9259c782cbe7d1c22ad967985bc.nq.gz
    ├── cb95c89bbc73c69faa799e55bf736687b885ae19.nq.gz
    ├── ccb9ccd5db8ba7d13cb522ec89ad55b1305814e3.nq.gz
    ├── cd1419027a0b1680de18325ca273e3c1cb2d2407.nq.gz
    ├── d1c782f405bd7b929ea02215250b5b3650dd94c1.nq.gz
    ├── d2dcce8880f1d4143c31bdc50fe47bb3a01fc77e.nq.gz
    ├── d3592f64868dbac870a1ede11221718b7e4473aa.nq.gz
    ├── d46bd94903987ae494afa6fc7ccfc0ab3d180132.nq.gz
    ├── d8c1397fc414c1234f303c8f64ebf174d9b0ec2e.nq.gz
    ├── d937d85b027934f5e477387c4738df90123ea5ce.nq.gz
    ├── da30114c3a0f1804e3d9fd2903c68a92c5f486dc.nq.gz
    ├── da3aa004dc36d682758136ff1c5255129910d144.nq.gz
    ├── db47187810c518141fde4d2bdff4c6a5044f15ca.nq.gz
    ├── dc660e26e67eca71a9fd08dce409aef839f0f689.nq.gz
    ├── dcfec60ef91551a4c67d9d42b0425963b474ae4b.nq.gz
    ├── dd0c92ac6d12a23889f4f66befaee715269cdba2.nq.gz
    ├── de5b1aaf92775d1549b40674ea2efacc5b570dec.nq.gz
    ├── df5dffeb6fc922e8fe6677e025ff891b20ba8526.nq.gz
    ├── dfa23260f39c22506dd9c5673168d6648257bd49.nq.gz
    ├── e0027679ba4402f97143082f0f21f4ad21a20ad7.nq.gz
    ├── e116cbfc2a3d7bd5bc265bbf1acb0ab8e20649ad.nq.gz
    ├── e12cf7b352070701a08ff2440cf3abacda6c6833.nq.gz
    ├── e21617a6debe1f2f284aa5063606ab1fef1d9696.nq.gz
    ├── e268ed07d3f975c28a86d28b41fb424197f2d7ad.nq.gz
    ├── e68418d2837c2a90a07dffacaa6f169744f54194.nq.gz
    ├── e8027e430270f5f47d87c5fd6930bd32302c5ab1.nq.gz
    ├── e8d348df7a960ff82c4a6545bd8218385a21f611.nq.gz
    ├── e8e2b924cea292de05c1c00989a509ba38cf73e4.nq.gz
    ├── e92d01a6eefcb1e669757961cff018690be7d6c7.nq.gz
    ├── eb68804e7c9c71c7779efbc8d1dc424d6731c704.nq.gz
    ├── ec25c717eb24ba38cc9cdf47ece8e15678aabc0e.nq.gz
    ├── ee6ac7baec2832b0990578e6896eb6a1d5a50873.nq.gz
    ├── ef192f37fd74af83da668a70bafb256d834ec088.nq.gz
    ├── f042c99f2a3781fd88a9a16e8716dc9d427158fc.nq.gz
    ├── f09b12e0a5876b9eafc780189d80af8a47e4f60d.nq.gz
    ├── f14172d473832174e9527f4ba88ad28f6abade07.nq.gz
    ├── f2493215b41fd973d481a2ded74d3fbad8ef9083.nq.gz
    ├── f29018a03eba2ebd89fbe26a12040880bed81465.nq.gz
    ├── f656706709a994b49bbaf2e8dac188ccdbb33d99.nq.gz
    ├── f83135473d1d7fb0699b41f4253616a4b0aa1289.nq.gz
    └── f9bd50127ed4a884b348cbe582772cb6ec812bc0.nq.gz

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

[bottlepy/bottle](https://github.com/bottlepy/bottle)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
