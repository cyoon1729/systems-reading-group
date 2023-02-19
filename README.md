# systems-reading-group

## Programming Languages
**Runtimes**
- JVM
    - [JVM Anatomy Quarks](https://shipilev.net/jvm/anatomy-quarks/)
    - [JVM architecture blog posts from 2013](https://blog.jamesdbloom.com/JVMInternals.html)
    - [OReilly Optimizing Java](https://www.oreilly.com/library/view/optimizing-java/9781492039259/)
- Erlang/OTP Beam
    - [The Beam Book](https://blog.stenmans.org/theBeamBook/)

**Some Cool Concurrency stuff**
- [Coroutines](https://pl.cs.jhu.edu/fpse/lecture/coroutines.html), [a review? paper on coroutines](http://aleksandar-prokopec.com/resources/docs/coroutines-ecoop.pdf)
- [Structured Concurrency: A Review](https://dl.acm.org/doi/pdf/10.1145/3547276.3548519)
- [Rust](https://web.mit.edu/rust-lang_v1.25/arch/amd64_ubuntu1404/share/doc/rust/html/book/second-edition/index.html), [Swift](https://github.com/apple/swift-evolution/blob/main/proposals/0304-structured-concurrency.md), [Erlang](https://learnyousomeerlang.com/the-hitchhikers-guide-to-concurrency)
- [Ractor: Erlang-style actor framework for Rust](https://github.com/slawlor/ractor)
- (Haskell) STM?


## Virtualization, Containerization, and the Cloud
- A brief history of virtualization and containerization
- [What even is a container](https://jvns.ca/blog/2016/10/10/what-even-is-a-container/)
- [Implementing a container runtime](https://iximiuz.com/en/posts/conman-the-container-manager-inception/)
- [Docker](https://docs.docker.com/get-started/)
- [Amazon FireCracker](https://www.usenix.org/conference/nsdi20/presentation/agache)
- [Meta Owl](https://www.usenix.org/conference/osdi22/presentation/flinn)
- More stuff


## Databases and Storage Systems
**Distributed OLTP SQL**
- [ToyDB architecture](https://github.com/erikgrinaker/toydb/blob/master/docs/architecture.md)
- [RocksDB Architecture](https://github.com/facebook/rocksdb/wiki/RocksDB-Overview), [Paper](https://dl.acm.org/doi/pdf/10.1145/3483840) -> [TiKV](https://tikv.github.io/deep-dive-tikv/overview/introduction.html) 
- [CockroachDB design](https://github.com/cockroachdb/cockroach/blob/master/docs/design.md)
- Good to know: [{B, B+, Bw}-trees](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/bw-tree-icde2013-final.pdf)


**Database Potpourri** 
- Graph Databases ([GQL](https://arxiv.org/pdf/2112.06217.pdf), [ByteGraph](https://github.com/Aaronchangji/ByteGraph-Paper-Query-Set/blob/main/ByteGraph%20Paper.pdf), [Facebook Tao](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf))
- [DynamoDB](https://www.usenix.org/conference/atc22/presentation/elhemali)
- [Lucene](https://alibaba-cloud.medium.com/analysis-of-lucene-basic-concepts-5ff5d8b90a53)/[ElasticSearch](https://www.elastic.co/blog/found-elasticsearch-from-the-bottom-up)
- [More Lucene](https://stackoverflow.com/questions/2602253/how-does-lucene-index-documents)

**Storage-level Systems Engineering**
- [sled](https://sled.rs/)
- [Atomic commit in SQLite](https://sqlite.org/atomiccommit.html)


## Web Stuff
**Web Compiler Infrastructure** 
- [esbuild](https://esbuild.github.io/), [SWC](https://swc.rs/), [GLSLX](https://evanw.github.io/glslx/)

**WebAssembly**
- [what even is wasm](https://developer.mozilla.org/en-US/docs/WebAssembly/Concepts), [wasmtime](https://github.com/bytecodealliance/wasmtime), [Build your own wasm compiler](https://blog.scottlogic.com/2019/05/17/webassembly-compiler.html)

**Javascript Runtimes**
- [Node.js](https://nodejs.org/en/docs/guides/), [a blog post about it](https://patrickpassarella.com/blog/finally-understanding-node-internals), [Node.js in action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Deno](https://deno.land/)
    - [Architecture Docs](https://deno.land/manual@v1.30.3/references/contributing/architecture)
    - [Conference 1](https://www.youtube.com/watch?v=AOvg_GbnsbA&t=2113s)
    - [Conference](https://www.youtube.com/watch?v=1b7FoBwxc7E)
- [Bun](https://github.com/oven-sh/bun#developing-bun)


## Nix: Reproducible Builds
- [Nix Whitepaper](https://edolstra.github.io/pubs/nspfssd-lisa2004-final.pdf)
- [Nix Pills](https://nixos.org/guides/nix-pills/)
- [Nix Paper](https://edolstra.github.io/pubs/nixos-jfp-final.pdf)


## Networks Speedrun (topics, in no specific order)
- Ethernet, Switched Ethernet, Bluetooth, the Internet, BGP, IPv6
- UDP, TCP, Congestion Control, TLS, HTTP, QUIC
- multicast, webRTC, DNS
- [Computer Networks: A Systems Approach](https://book.systemsapproach.org/)
