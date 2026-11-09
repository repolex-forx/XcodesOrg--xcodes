# Repolex Knowledge Graph of XcodesOrg/xcodes

RDF knowledge graph data for [XcodesOrg/xcodes](https://github.com/XcodesOrg/xcodes), parsed by [repolex](https://repolex.ai).

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
rlex download XcodesOrg/xcodes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a5b72c81a5b722f52aa97d179706df8d4d5540b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a5b72c81a5b722f52aa97d179706df8d4d5540b0
│           └── chunk-001.nq.gz
├── blob
│   ├── 031af12a517978e9a3aba9f1b57ac669878ecddb.nq.gz
│   ├── 165d010ca69e3c26bac64e821da41beb80446f0e.nq.gz
│   ├── 178da0767fe9d66621027076ad86ae286d106f6a.nq.gz
│   ├── 18b3580458e489b0ec54c8f3db42ae62a638620e.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 190aca5c81da341dd9aa199343a4fbb097c5e68a.nq.gz
│   ├── 217041c033f0f271f892617caf230ef74a9930cd.nq.gz
│   ├── 22a738ff1763b20765f323028c800456bd7a2677.nq.gz
│   ├── 27c4d0c4cd52733b16c1d1c8a09970473a8cb559.nq.gz
│   ├── 2eef55cb66833e8f4bd151955187572282ee2e85.nq.gz
│   ├── 3233eba5a6e1ab40a97c26dabb53e2fa8cb3827d.nq.gz
│   ├── 36ee7e5e5df4c7c34c3cb5dfe8a6d9f151b31d54.nq.gz
│   ├── 37e4e9663fa379c474b3a65320d471529140addc.nq.gz
│   ├── 3856bd12810023487150b151b08b2cb98e8ef572.nq.gz
│   ├── 3b5a637b26198eae8ad950a2ee68de461790e711.nq.gz
│   ├── 3bba8f7c6a0b5059883d6f280302a6535e777b66.nq.gz
│   ├── 3efd0fd3adbeb4b544009207e90ef871c0d1ee2c.nq.gz
│   ├── 3f729fb9b1cd528cd14880abd221e282e4f74e4f.nq.gz
│   ├── 404125aa3eecf282ac55f7d3c9c32afa9b538813.nq.gz
│   ├── 412d3a0a5089d25452a61bd8fd1934464cc02970.nq.gz
│   ├── 41804b6991628ccba23750994942059a9d7d78c4.nq.gz
│   ├── 42ae96c919b9bef7f86d2e3660a7a12081192cf9.nq.gz
│   ├── 46d8a235df7933707c6bb31fc5c4f5f591d2f5cb.nq.gz
│   ├── 48cdfbbaebfe979589d6265f16c23310ff5acdbb.nq.gz
│   ├── 4abf2c2de2ce6928ce4be49d2b65de3b7241bb8c.nq.gz
│   ├── 54b18668ee6dc0057a9c6d94cf5d212a3586db1c.nq.gz
│   ├── 55d354c680450f0b868e3bd87891d9a77c066db9.nq.gz
│   ├── 59283ea77c79b10a7e11d9c6ece0dfd5e4245f17.nq.gz
│   ├── 5d38145a64e8a56104a6deea7dabb82eaad78abb.nq.gz
│   ├── 5d9645d5af0b513fb96705ede97ccaa962583e81.nq.gz
│   ├── 5f586ac37f6a3b15b7045b7a1b67f09b597516ba.nq.gz
│   ├── 614aff1f0b2b549de6e398d3c4b467f797358d4e.nq.gz
│   ├── 6d80b1c54be4b274bc94b39a314192f7a47db69e.nq.gz
│   ├── 79aa13dfbb3e3f5266cb1a8038d32e1f2049f832.nq.gz
│   ├── 7a7166b15a5918b5eecdd043986d711ceb7c9c7a.nq.gz
│   ├── 7ac3fe8ab4d1f922a5e2718ce266de5b112e11ba.nq.gz
│   ├── 7d5515e8cf39d66bde9d7049e9f604ccec05e6db.nq.gz
│   ├── 7e0d0f71dcd4aac2f897b879685109a72c5fb769.nq.gz
│   ├── 7e4bda3fd21035d768372126ea60c7da47b2ee4b.nq.gz
│   ├── 8070792e2b62fd397efd7cdf0b4c0b5b8f9b5009.nq.gz
│   ├── 83387d6c1bc520bd37b1ae3dfdae83ddbae009c7.nq.gz
│   ├── 85ad3ac2b12144736829a1e8ec627b6557bae655.nq.gz
│   ├── 900e15edfb82e4c0f446e9a55fe4a3e7c86f7659.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 95e0d9a0e6f72cadcb258b98336978a4acdcf285.nq.gz
│   ├── 994d817a5695e4b145a0e91b71e35549c0a8ce16.nq.gz
│   ├── 9f3a8b433687b4d8f6222f3e07b55d75aabee9ca.nq.gz
│   ├── 9fe4d9eabbb119a238479d68cd048a098398cda8.nq.gz
│   ├── 9ffdc1ef2caca47b9e4fba54bc2b641b5ecd5090.nq.gz
│   ├── a0220dc1fff0bcdee0af86b81279a68e97a1f108.nq.gz
│   ├── ac9a0b24a289614566f8a174edbbb563d10b3a8c.nq.gz
│   ├── b3b59f4a62c00dbee6eed35e1de4d234a5ed3ab6.nq.gz
│   ├── b52c295b83b52966259df9df06331502508c23d5.nq.gz
│   ├── b5d2e76e46acfce1153c87ff0e0d7a2580a87071.nq.gz
│   ├── be2c8bd234d81559425eeb2eef0ce3ae3094e544.nq.gz
│   ├── c2c1d68ad2b59048c841b4f5a0932bc64b7ebbbf.nq.gz
│   ├── c3a0e12cc32635bbb43f2225c096d5437936e260.nq.gz
│   ├── c4c9b36e4e9b1d4c6d233bb699eed4a950b09cec.nq.gz
│   ├── c6b9b4dbd1187f0dab4b73d660909852ffa17f67.nq.gz
│   ├── cf22f96fd45682f497ceefc053076d6009f67b3a.nq.gz
│   ├── d346e2ab7f2109b12c9bf53299bbbf6e7527fe7f.nq.gz
│   ├── d8014744e057739e8b7db7c9134066d14a3c5c05.nq.gz
│   ├── d98eb967af22506bf71e2ee28b90366e6efd3696.nq.gz
│   ├── d9964596554f846ab186f70eabcb368b047069ac.nq.gz
│   ├── da88df455de5e32903a9c41f24a1705f5b6262a5.nq.gz
│   ├── e433ccfa7b0e64c019d7eea576f2a839136c6213.nq.gz
│   ├── e43b59aa2173b558b2ee9feb173ce6d550513400.nq.gz
│   ├── eb63e82c0b78c449184c10c338d5c1ffefd047be.nq.gz
│   ├── f1efcf42a04654184a31191fb7983e7dcd912ad3.nq.gz
│   ├── f7bf2cb774ca593a2e4a7a9f26ebfaee8f312383.nq.gz
│   ├── f7feed08ac0e003a7078ad9a8bdc76122d7b19e1.nq.gz
│   ├── f829d21931e0a4d98a3672eb402e0ebbbd3f099b.nq.gz
│   ├── f8edd8635bdb168144936c516f3e9f9258f3bc00.nq.gz
│   ├── f9097f1b51965d8b1fe0a9da07632e495241305b.nq.gz
│   └── fa438f0da5d4eae75027750763aa8e21e34eac20.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a5b72c81a5b722f52aa97d179706df8d4d5540b0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[XcodesOrg/xcodes](https://github.com/XcodesOrg/xcodes)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
