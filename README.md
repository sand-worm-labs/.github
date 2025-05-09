

# 🐛 Sandworm

**Sandworm** is a no-bullshit suite of tools, protocols, and frameworks for tearing through blockchain data like it's tissue paper. We're building bleeding-edge infrastructure for indexing, querying, analyzing, and abusing decentralized systems in ways they were never meant to be used.

---

## 💣 What the Hell is This?

A collection of hardcore, low-level tech meant for people who don't want to wait 5 seconds for a query to return or write 10 different scripts just to get a single transaction. We're here to strip blockchain data down to the bone and give developers the raw power they need.

**Projects include:**

* `wql`: SQL-like DSL for querying blockchains (EVM, Sui, more).
* `sui-adapter`: High-speed adapter for scraping and querying Sui blockchain data.
* `evm-adapter`: Ethereum-compatible adapter for block/tx/log access.
* `sandworm-indexer`: Custom indexer stack using PostgreSQL, TiDB, and raw speed.
* `sandworm-core`: Core traits, abstractions, and query runtime.
* `cli`: Command-line interface to run queries locally or remotely.
* More unhinged stuff coming...

---

## 🚀 Philosophy

* **Performance > Everything**: If it's not fast, it's dead to us.
* **Minimalism**: No fluff, no hand-holding, just raw functionality.
* **Hackability**: Easy to fork, script, extend, or completely bastardize.

---

## 🧠 Who Is This For?

Developers who:

* Want direct access to blockchain data without third-party bullshit
* Are tired of GraphQL, rate limits, or slow APIs
* Love building their own tooling and want real flexibility
* Aren’t afraid to read source code when the docs run out

---

## 🛠️ Stack

* Rust (because speed)
* PostgreSQL / TiDB
* Pest for DSL parsing
* Alloy (EVM), Sui SDK
* GlueSQL (for dumb-fast SQL over JSON/Parquet/etc)

---

## 🧨 Status

This is alpha. Expect breaking changes, occasional rage commits
