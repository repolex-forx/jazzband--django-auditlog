# Repolex Knowledge Graph of jazzband/django-auditlog

RDF knowledge graph data for [jazzband/django-auditlog](https://github.com/jazzband/django-auditlog), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-auditlog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 607000d8145c31eb7677cce63ca58ab76c5190a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 607000d8145c31eb7677cce63ca58ab76c5190a6
│           └── chunk-001.nq.gz
├── blob
│   ├── 033ec96a1a55a5c329cb36322b0e18d7a3d8baf2.nq.gz
│   ├── 0346ccf6d5a17b0cf52bf788312341214d52e5a9.nq.gz
│   ├── 045d643cff0f65292749d5ff5e08f09b767056ec.nq.gz
│   ├── 0dc55d3939dea725a442f38e61e14531a744bd6a.nq.gz
│   ├── 0ee78525e6beb7ec32f427cd5aa5f1b1f6ca6620.nq.gz
│   ├── 123080f71ecfa61aa8e7f902332f027ffbc461ec.nq.gz
│   ├── 12a931cea61a6eb2a9be40d8f096be8f81e32143.nq.gz
│   ├── 14013dbf7446b26ad7ceec117072bb4104ec32ce.nq.gz
│   ├── 14cb88929512941d995c2277d813dc9585a41aac.nq.gz
│   ├── 14fc84706a860635c3caef9f4a8bf27e3089075f.nq.gz
│   ├── 152119d47f96ad4467399733900c99d4415a7420.nq.gz
│   ├── 184bc261a9d80bc9766059da4dc30026143692f8.nq.gz
│   ├── 18a4c86be83663b342801d1ab40cd3f897ad3feb.nq.gz
│   ├── 19410252d64a3b42be85572917d82d992496808f.nq.gz
│   ├── 19ad9d9fcd2be7b2c4ab2bac51a5e6cc7242d64e.nq.gz
│   ├── 1fca926e53424e546d043312f37f18b26878f38b.nq.gz
│   ├── 230f53a97d77e9c77bbf05983bcee2b44c6c422c.nq.gz
│   ├── 240d6093f04eae30845c79a1f0c69f97cb136220.nq.gz
│   ├── 251d4639b29eacf9d14548acfb1efe9a8651b325.nq.gz
│   ├── 28a5c6c26d6061e04871fd732d5019b51cdfc3c0.nq.gz
│   ├── 2a35dcea1bcf327af613ebfcbd52832bd477cd55.nq.gz
│   ├── 2a50bda3ad082a7fe49034d177318982c8c61897.nq.gz
│   ├── 2c827c29b6bdc4f0351e5ac201b256e3d270be60.nq.gz
│   ├── 2eb305825f8fa037978843df6b1d585268d14cf9.nq.gz
│   ├── 2ed96bdefea9361e109a1e7d917142fe133b2edf.nq.gz
│   ├── 2ef50ff0afbb93c495d1384635dcd5b8a5b996b0.nq.gz
│   ├── 32d1930e45c2600688bafc948dcc7f6be43ea241.nq.gz
│   ├── 32ec84b193c005ba6655e1e548483c50e8c1ff75.nq.gz
│   ├── 34c1cd535a3431658008aea0ba0131d1cbd82e1d.nq.gz
│   ├── 370303f6eb0f6c2e0aab687ceec2efcfb7fafdaa.nq.gz
│   ├── 3c289fb9463e903478b5d6c0116a3c25dfc878fc.nq.gz
│   ├── 3e2b78fc3ece84eb35a30fe04e59305ef92945b2.nq.gz
│   ├── 3fcd41e6f327a0d3f879f5721f693b68bb67b779.nq.gz
│   ├── 42c502075ddb68fac41c8cef493fc22f6a6161d1.nq.gz
│   ├── 4c68d5f66674c2a658a138662a975ffe109eb6e9.nq.gz
│   ├── 4ef243d4aa5614fcaae8b7f04da0c53831ebc41e.nq.gz
│   ├── 597ec2a7a34a52521f2d44e87fb176910f0667cf.nq.gz
│   ├── 5ab56893694cdf3e099d851995cf418b3114c192.nq.gz
│   ├── 687f0f65a5d962b5ddbd0bd55795c467c47b9cb5.nq.gz
│   ├── 6a57ad9500b406bca987260ae88a192369e83d72.nq.gz
│   ├── 6afee246294a25c780ebe1bb7f781adf022515f5.nq.gz
│   ├── 6c761bf0cd157c709f97423d28d3b392252a1db2.nq.gz
│   ├── 726a32a8c52d93fdda2e1728a4c972b436bfe017.nq.gz
│   ├── 754328b4eaa8e006ff61624b8941714ab445e7ae.nq.gz
│   ├── 761b5dfbb8852990ca9a7d4e951d20a0a737470b.nq.gz
│   ├── 7a973f8034d5544bba412a37de3d75cd2d0f21db.nq.gz
│   ├── 7ac432fbae8d38114e6c9e26c5acf36678a60eeb.nq.gz
│   ├── 805d15aaa984c30dd873c899a499dfeb903bb11c.nq.gz
│   ├── 81a7c314dc192e29a3c9556cc8cc1934e5f64539.nq.gz
│   ├── 8583f379621121077a7a687900f8c7575281b195.nq.gz
│   ├── 858596e3251d7e50b9eee7c11fffde3fed7a261f.nq.gz
│   ├── 8597650c4ff2cc4a30af1da59fadb78d46c346ca.nq.gz
│   ├── 8788de02fba1ede43f238ce1a93fe57e561add1a.nq.gz
│   ├── 8ae203c3a7bfe9265257d58a76364df8ab6caaed.nq.gz
│   ├── 8ba23c99c2b529f1145d9972d4e55eb80a03c7f9.nq.gz
│   ├── 8bbbdd6e665734f80b2ee48e9b121cb9ffbfcacc.nq.gz
│   ├── 8dedb1ef77eb618c53373fe243734dfa8baa5f63.nq.gz
│   ├── 92dd33a1a44470e1405a20c617694fd174086fcc.nq.gz
│   ├── 97dc78123f7e95367f80b9fdd9e4db3fca0c5ba9.nq.gz
│   ├── 97def0692a27f5d03f44ea80e56bd97dd394a68f.nq.gz
│   ├── 9c869c12e0c7ce16e13b47cb2c6c3bddd1ba177d.nq.gz
│   ├── 9de0f6016ce50aec4d810c67bc51a76292426499.nq.gz
│   ├── 9deec0ecaae546f9bf18fa5938a44a8df37195a1.nq.gz
│   ├── a5c47b3595058334beb6fa84f18b8b00fceaa93e.nq.gz
│   ├── a8935966b431e862173d5ab2661ecb16b43f3188.nq.gz
│   ├── a8e70454a246bcc0b6280cd49c2bcbf3f53a3027.nq.gz
│   ├── aaae2768fffc0b85aecb3bb3bb3cc3afe2ebca76.nq.gz
│   ├── ac09cf8e344163832c6fd7e572b01b34933d2235.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── b66bcd8a4b02de908c0c7d03ceb8ef4694ce7e7b.nq.gz
│   ├── bae9600cb58df653b5b7f361ae58c565bf47744e.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── beb0d2bb610d00acee8ad5485b901e0e48baa61d.nq.gz
│   ├── c0f61bb11fbe088d78ecd5691fbfee7c50627d1c.nq.gz
│   ├── c27f4857f8bbdce19286f2cd9c827d0ebca61d14.nq.gz
│   ├── d0a144b4a13bb9e3b8e467b0ed1d93b7ec806581.nq.gz
│   ├── d0f65c493f7899e787714bc1aac7effaff6587c5.nq.gz
│   ├── d18bf4848f4ef4b54348e96f4466aa332cd30f7b.nq.gz
│   ├── d49b198ebdbe60e6339c4134206f187e92813206.nq.gz
│   ├── d4f1a4690ac92b565525fb67b2630e08f2164419.nq.gz
│   ├── d948e0438eacf161ae9e015ce6b58057a080cd7b.nq.gz
│   ├── d980d895f6282c56c5c46953c394dd2b8cf481e2.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e23888f1c6fa3363ac1f3120abc59faeefd4e225.nq.gz
│   ├── e2c5de60e0b3811996145e2351b8e6928a223c27.nq.gz
│   ├── e3a23b3e6652aed41b26048b39d4435f60ea1ef2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb019311e813de7f19c4c9201d66330cb1989d16.nq.gz
│   ├── eb6c0bf0c60b086fed5fdcd44022887464423f04.nq.gz
│   ├── f0629304ed43c6cc8996829081b8373267f288c2.nq.gz
│   ├── f083970958eb0daa3fa0d745e3277068ea46a7f3.nq.gz
│   └── f1029bd829caa38dbcb27b1cfc05a8fdfcd0cf73.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 607000d8145c31eb7677cce63ca58ab76c5190a6.nq.gz
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

[jazzband/django-auditlog](https://github.com/jazzband/django-auditlog)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
