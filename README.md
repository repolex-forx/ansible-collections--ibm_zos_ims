# Repolex Knowledge Graph of ansible-collections/ibm_zos_ims

RDF knowledge graph data for [ansible-collections/ibm_zos_ims](https://github.com/ansible-collections/ibm_zos_ims), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm_zos_ims
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3d1dc911062580fd6f7cbe8fdd592fef021c89b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3d1dc911062580fd6f7cbe8fdd592fef021c89b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ca77c450d1c718735e88133d1d269ddb403560.nq.gz
│   ├── 00cb473a5b6c66f5e89ab6d0909a8a09b2d24142.nq.gz
│   ├── 01ba62ca5adecdd685846aef89f6178f06c0ead8.nq.gz
│   ├── 0560cfbb99e7e07bf363687fb30e96f55091d04c.nq.gz
│   ├── 05f684de06a603a66a39a8e6773bdec4f1ff2e3a.nq.gz
│   ├── 08b7f5e710e6c171bff630046b29ab36d36341a9.nq.gz
│   ├── 08e7393975187dc52d2a11db4ba2fea5586da8ec.nq.gz
│   ├── 0a69e3b0380d35aefa69bfde22a9453c2f7ef83a.nq.gz
│   ├── 0bff38c03377701545743e35aca1bb9a5cfd9f0b.nq.gz
│   ├── 0e7b69bca419e7de0283fc8dd3b0247530c40ce5.nq.gz
│   ├── 11744a057e2b8d9939969beafd114e1ccaf74479.nq.gz
│   ├── 1453f5dd7dbaf4ceada7a689c186adc58056cda9.nq.gz
│   ├── 1708d26332f79b5e8774d8224661ab61407a92e9.nq.gz
│   ├── 1a396c816f4011375a399a673a7b03016d35944a.nq.gz
│   ├── 1b47ee6c829edec50e16a2589cb62fb92ffcdb83.nq.gz
│   ├── 1c1e2d32e42a370736a1a55ad3451144b9cc7f82.nq.gz
│   ├── 1ebd7ee649bfa3148862acb4a75ebb725cc692bf.nq.gz
│   ├── 23b53ea5df730982d01be14312925ae58b03fc77.nq.gz
│   ├── 258c6d2fa65bc91d32e2ab2dece8d89b0b51d810.nq.gz
│   ├── 29e3b72068336016110f16161165496f655f21b1.nq.gz
│   ├── 29ff0cf98cb564a6b5b7527b1bb431559cf42c85.nq.gz
│   ├── 2a5aec3b3ccd7e186539ac970043a4eb2268aefd.nq.gz
│   ├── 2b61b56bdbc38dc34a15026599731ff8092d1e05.nq.gz
│   ├── 2bcba9a485cbd778658f322e200c6163d4804124.nq.gz
│   ├── 2c3ba9c29d866aaf4073ef12b528e571fb187f20.nq.gz
│   ├── 2e16eed1d070b2fb9a80534348f92966d49f6ef1.nq.gz
│   ├── 2f2ad8d559c164e020d477b7adbb7962662b4bf4.nq.gz
│   ├── 321dd4c365f073aea08016df42d7159b92729784.nq.gz
│   ├── 357649c5b6341eb6a51c137d138c6a6f5d29449a.nq.gz
│   ├── 3c8235a4c2b76658c77340734c0f67f68ab74b2f.nq.gz
│   ├── 3c92cd7456801743df507511b7457c0008067be4.nq.gz
│   ├── 3fcb8ec30beaf5b839fa566d612edee6b2986dfb.nq.gz
│   ├── 455126f1cbeffe8787667a3799bacda81f618598.nq.gz
│   ├── 456fddf8ebd408d4711cf59f9ff5bea51601eedb.nq.gz
│   ├── 492239e50ee5f5e03d4fa91b4c83d4d619ee96ea.nq.gz
│   ├── 4c5f59157aa1d9fc79fdd4cda72a061e8fa0efeb.nq.gz
│   ├── 4e9cbf078f5e9608aef0bb654365e827448445f8.nq.gz
│   ├── 4fd2a4dd3122f2f52dd6a8d03cb19d69399e59fc.nq.gz
│   ├── 5041564ef2e55e28625145769d7cd1a291ccbdb1.nq.gz
│   ├── 5374cc2b3a5cb5d77a43863dfbdc52019f6499a6.nq.gz
│   ├── 56a539b92ed3fefdbaba59a3fcfb22af29b2d404.nq.gz
│   ├── 58f1b8e6b9aba9dc11d1c1ff20403f4db6dc4111.nq.gz
│   ├── 590477678e17fdf288ff68403d5d3af23e0e2c9d.nq.gz
│   ├── 5c639b70862528183cfe7f66bf9a07a6bb6d7cb1.nq.gz
│   ├── 5e7446bfc6364b0c621e2ca8ed64001c219ffb9d.nq.gz
│   ├── 5ef5b1dc64782594ece877e60deb97a4b4923574.nq.gz
│   ├── 5f412c51055b0dd0ea299caeedeb45476090d738.nq.gz
│   ├── 61f5d7414d29e730e88f5f714369dd28cc9d0845.nq.gz
│   ├── 6422c4b8a265db37004b2a41383d09c00bb839ba.nq.gz
│   ├── 659dd223e8bfe96d6bfb5a027e29b73196a40544.nq.gz
│   ├── 6742e459418cb9ceac33da006b81e1bf3bfa1ded.nq.gz
│   ├── 6b2b8d2d5518dd3c2702949d128f6919c2198650.nq.gz
│   ├── 6c9e91aa82af22a9312f633c4202821eb8489d81.nq.gz
│   ├── 6cc532cf1deaa5bcaaa425b0392838d050b02b07.nq.gz
│   ├── 6e5911e526dc4d19ec60335cc8f13e95a7ff7140.nq.gz
│   ├── 6e78e0336aeb9411a9a2f7522b498e2609b80fbf.nq.gz
│   ├── 72480ce74f68fc64cd528ad1cc57cb4c3c65a7ee.nq.gz
│   ├── 7288bd930c06c44c0907320b80bb550612b330f7.nq.gz
│   ├── 73175ec355e4a37f13e8f9fa8fd1da36dd0cbf98.nq.gz
│   ├── 74252b12752c9ecab41ab896904eed15396f8393.nq.gz
│   ├── 76cbc6b856315db1f6048d7d6abe0fd8a1406cc3.nq.gz
│   ├── 7728c2ae2232b3b7d37d2f2b1c89c9e0616b9a8f.nq.gz
│   ├── 78f6121e8eb4fc929f67709d8c44af03533759e7.nq.gz
│   ├── 7a1d81ca492b0b2c01cf92a2ec80fcdc9a18d939.nq.gz
│   ├── 7c753ea4f45a30b1b0d2636f655b0dc1dc20bd0b.nq.gz
│   ├── 7ec112f18d4c97bdb56ba68c29c1334164168eb2.nq.gz
│   ├── 7ecff6e8b0e04f86d52024fa009a05be09e3d51a.nq.gz
│   ├── 7f31b536dc462a30eca3c16230149fa5a7196d41.nq.gz
│   ├── 7f8de3c743e092bab5604a9d42cdb359051d92e0.nq.gz
│   ├── 7fe81515efa5cb273786652245cf7b47e88e73e2.nq.gz
│   ├── 8731cb96a62d35ad6459393391dce7caf4ed7556.nq.gz
│   ├── 8bc81125305ca688f49089707a3a1a95f827d334.nq.gz
│   ├── 8c70cb77689f8c3952fe83fe81f19603fd549eea.nq.gz
│   ├── 8cf6bbea1c31c906ccd9ae0f1c7ac5156d644fc9.nq.gz
│   ├── 8e1ac2cfc31257126fd85cfcb6b74a787ad691c2.nq.gz
│   ├── 8e959152754ca64c18a8a355726ff87829845103.nq.gz
│   ├── 8fa2dee1285c734d3b8f128d750c5722dc621469.nq.gz
│   ├── 9112f888a47222e9617e59e4d40b7888d4a8de1c.nq.gz
│   ├── 92ac24e7e0bcf050e3528b493142433d9b037d79.nq.gz
│   ├── 96dff59e58e13762da1b69ddf98710ae8e1b4298.nq.gz
│   ├── 9899bf49ed002bf4b4966436e6dc4ede69002cbc.nq.gz
│   ├── 98d5966f2d8366f03a1c3da5e0f01d27d20e6da3.nq.gz
│   ├── 994e371877cd286fc9414aa22d58fb68fbb39c27.nq.gz
│   ├── 9dc68ffcd068ae74ac8f47f0ad9433eebb1abba5.nq.gz
│   ├── a1aa7ddc06f3899db243dba6370bdc4cebd24237.nq.gz
│   ├── a28681a6ab7f079737d9912a853f42be58b5a40f.nq.gz
│   ├── a69aa44ae8ae7ca1bb1e3c1a3a0e5120a15307ef.nq.gz
│   ├── a8005b4a755517709b1cbc05337423bbc0336103.nq.gz
│   ├── aa913b3b7597d3c0d7b195781099e1c792881542.nq.gz
│   ├── accca8c3e592ea169dcb5520693985c5f81b00ed.nq.gz
│   ├── ae57d3c90cbd34a6914a229a418f1b049e620fd5.nq.gz
│   ├── af026d9a59b977e81430461c3145359abcbb14bc.nq.gz
│   ├── b5f71acf7ecad674060ffa7a254a467e1ed7d636.nq.gz
│   ├── b5fcd4405debdc1d756e1118ffc5ff3d1baa5eca.nq.gz
│   ├── b6f10a84c368f64aa2da4b6bb74743f74f081e70.nq.gz
│   ├── b7fde045f3b5500f8cdae58b1df95c08ac6347af.nq.gz
│   ├── b82c5d1244af63e10907e601775720574d6e460f.nq.gz
│   ├── b88c0a81b485942e39880e51119ef5dd696770d9.nq.gz
│   ├── ba0d68b15aba0b8bfe039bf7d03b2f809d7aae8a.nq.gz
│   ├── ba740b52cd706b9289267d2eecf5c2988c098d9f.nq.gz
│   ├── bb2b7ebaef2dd2c54e45171d951d8ba7b55e3c76.nq.gz
│   ├── bb6e6efd94d8f077cee553601dd28da8d604a825.nq.gz
│   ├── bbbf9ad78d9d8b37da7b153880c3713cb9ae8ceb.nq.gz
│   ├── bdef6c57fc446b908f191d210ba74785c8e01b8c.nq.gz
│   ├── be6f72d9f2dfd8ae5ebc5078a4847a1fbc45fd3d.nq.gz
│   ├── bf74fac60edc168427b75866650b6a48bb18c5d1.nq.gz
│   ├── c14cbcac16fbb845bd02fca20507fd301a9bb44f.nq.gz
│   ├── c3a0c1898c2c09a671fad7f27ec559ff3065234e.nq.gz
│   ├── c791245e9ef050b04e797fa9984c7f8d9a90a368.nq.gz
│   ├── c9e7e7e1ba026748c0e1a116b53fda815151bd5a.nq.gz
│   ├── ca35775d9ed0b938dba72b178c1bef5d000145b5.nq.gz
│   ├── cbea90b2a7a3bf9aa69497c7c312818d37fa9a0e.nq.gz
│   ├── cc20f650fde816131c61a4ce2fa3628b113a3343.nq.gz
│   ├── ce0ec009b3b54ab369ecb50328ec564aada66413.nq.gz
│   ├── cec4d22af88d0dea758a6c4a9556e457b5c942ac.nq.gz
│   ├── cf0a4a77348693a92138e6d9ff0b80c1576a3fd4.nq.gz
│   ├── cf7b500d206268b9b7d2793ad8f1fa16be3ae127.nq.gz
│   ├── d254a6e53aff174aa0dacd35d2183cf25f2f6b52.nq.gz
│   ├── d473438a480de4c684feea7718eeb0e32c865dbd.nq.gz
│   ├── d60f474698cfa6f36e54d78f7cf589d7ea191e32.nq.gz
│   ├── de5ad8e589111f652149c6d47089af8e07144f3b.nq.gz
│   ├── dee2e241d2c54a5aae0852bb799b2256156ec876.nq.gz
│   ├── dff9a44674f7dd59bbaec6507b985037bf06490d.nq.gz
│   ├── e0381afe6413db2b08002beb598c2a226168ae11.nq.gz
│   ├── e1edb3f12b739cf826f6470d09921d1a2ec0489f.nq.gz
│   ├── e25f88e5d858e86bb7c4d2c98654599e65404624.nq.gz
│   ├── e2f4d362cd3d4a391e6ff18368e5507d667f9f40.nq.gz
│   ├── e4dc2d7f02e270d130d41bfe813c3add7113b10c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fdcb0394ab2d8107104262465dafee2853eeb3.nq.gz
│   ├── e91d368ab45d255fe8f3d48d5bd879559e9ad63e.nq.gz
│   ├── edce020bc96a5b0a6db700438501926dc81fe664.nq.gz
│   ├── eea4b5cd9524391c65283f96f3392c273f29a497.nq.gz
│   ├── ef03c5c93ac2dd4dd3d57ba13d5513f6f9e8ac67.nq.gz
│   ├── f354b261e3ce5dfa69c5d60781f8233ac63059ec.nq.gz
│   ├── f4d7a03e68df3bce3cec2e62c18beb59972aa29f.nq.gz
│   ├── f775bdab8aacee5a514c9622fdc676f510a95763.nq.gz
│   ├── f88ea864e5be259392bb48d8307de98a2119e3f1.nq.gz
│   ├── fa006824c6dbf1410dc76d351433c3502ae15355.nq.gz
│   ├── fb03cf5d1cd11662d9b7584aa018c0d6a67a8e99.nq.gz
│   └── fdc5bf3fbd7d1225eb32fe41f48f1c5ecd949557.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a3d1dc911062580fd6f7cbe8fdd592fef021c89b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 149 files
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

[ansible-collections/ibm_zos_ims](https://github.com/ansible-collections/ibm_zos_ims)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
