# kanae repository guidance

This is an independent west-managed actor repository. Keep EDN canonical and
JSON under `wire/` only. Preserve non-adjudication, provenance, aggregate-first,
and Murakumo-only gates. Do not restore former root paths, Cargo/wasm, Go/TinyGo,
or shell test runners. Verify with `bb test` plus EDN/JSON and artifact audits.
