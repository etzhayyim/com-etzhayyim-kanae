# kanae (鼎)

Standalone Etzhayyim actor for factual, aggregate-first government fiscal-flow
assembly and visualization. Kanae renders disclosed flows and never adjudicates.

EDN metadata and lexicons under `contracts/` are canonical. External AT Protocol,
DID, and fixture JSON is isolated under `wire/`. Implementations and tests live
under `src/kanae` and `test/kanae`; actor-owned history is under `data/identity`
and `docs/adr`.

Run `bb test` for the comprehensive standalone suite. Go, TinyGo, Rust/Cargo,
wasm binaries, shell runners, and the former JSON-LD manifest are prohibited.
