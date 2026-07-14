Hey, 
I build platforms, lakehouse, streaming, data analytics.

Contributions to the [Polars](https://github.com/pola-rs/polars) query engine (Rust), mostly optimizer, IO, and reliability:

- [#28017](https://github.com/pola-rs/polars/pull/28017) feat: Optimize joins with redundant equi-join keys
- [#27727](https://github.com/pola-rs/polars/pull/27727) / [#28002](https://github.com/pola-rs/polars/pull/28002) feat: Optimize `len` and `null_count` comparisons
- [#27590](https://github.com/pola-rs/polars/pull/27590) feat: Add Rust backend for `Expr.has_nulls`
- [#28157](https://github.com/pola-rs/polars/pull/28157) fix: Avoid slice pushdown panic on shared cache inputs
- [#28225](https://github.com/pola-rs/polars/pull/28225) fix: Classify S3 region request failures as IO errors
- [#28066](https://github.com/pola-rs/polars/pull/28066) fix(python): Close ResourceWarning leaks in database tests

All merged PRs: [`author:0guban0v is:merged`](https://github.com/pola-rs/polars/pulls?q=is%3Apr+author%3A0guban0v+is%3Amerged) · reported issues: [`author:0guban0v`](https://github.com/pola-rs/polars/issues?q=is%3Aissue+author%3A0guban0v)

## Projects

- [bayesian-llm-judge-reliability](https://github.com/0guban0v/bayesian-llm-judge-reliability): Bayesian IRT analysis of LLM-as-judge reliability on JudgeBench. Main finding: judge rankings are not stable across item populations.
