# OSS Bug Fixes / Reports

> Details for private reports will be disclosed after vendor confirmation, public advisory, or explicit permission from the vendor.  
> Entries are based on manual verification and vendor-visible artifacts.

Started from 4 May.  
Last updated: 2026-06-23.

## CVE

[CVE-2026-54010](https://github.com/open-webui/open-webui/security/advisories/GHSA-vrhc-3fr6-pc3c)

## Public / Verified

| Project | Report | Status |
|---|---|---|
| NGINX | [commit](https://github.com/nginx/nginx/commit/18a70a4d5806b5578d00460493954262ece55019) | Merged |
| Bun | [bun#30621](https://github.com/oven-sh/bun/issues/30621) | Verified |
| Chrome PDFium | PDFium crash bug | Verified |
| OpenClaw | [PR #83741](https://github.com/openclaw/openclaw/pull/83741) | Merged |
| DuckDB | [#22663](https://github.com/duckdb/duckdb/issues/22663) [#22660](https://github.com/duckdb/duckdb/issues/22660) | Patched |
| VLC media | 1 | Verified; fix scheduled for 3.0.24 |
| openbao | [#3235](https://github.com/openbao/openbao/issues/3235) | Hardening issue |
| canonical-workshop | 1 | GHSA accepted |
| Protobuf | 1 | Upstream acknowledged; Google OSS VRP tracking |
| git | 1 | Maintainer reproduced; public fix planned with reporter credit |

## Pending Private Disclosure

| Vendor / Project | Count | Notes |
|---|---:|---|
| Bun | 5 | Several hardening fixes observed; credit/status unclear |
| DuckDB | 1 | Waiting for GHSA/vendor follow-up |
| ClickHouse | 3 | BugCrowd |
| canonical-workshop | 1 | Follow-up / private fork patch path |
| cloudflare | 2 | HackerOne |
| Apple macOS | 3 | Submitted to Phrack 73 after Apple declined security classification |

## Public Issues / Not Yet Verified by Maintainer

| Project | Issue |
|---|---|
| llama.cpp | [ggml-org/llama.cpp#23108](https://github.com/ggml-org/llama.cpp/issues/23108) |

## Duplicate / Not Accepted

| Project | Count | Notes |
|---|---:|---|
| vercel | 1 | Not security issue |
| Flowise | 1 | Dup |
| Chrome | 1 | Dup |
| Open WebUI | 1 | Dup |
| Codex CLI | 1 | Obsolete |
| Codex Windows | 1 | Patched during triage |
| ClickHouse | 2 | Dup |
| Apple macOS | 2 | Not security issue |
| VLC media | 1 | Dup |
| MongoDB | 1 | Dup |
| vercel | 3 | Dup |
| filament | 1 | Dup / not eligible for Google OSS VRP |
| PostgreSQL | 1 | Not security issue under PostgreSQL threat model; WAL storage considered trusted |

## Not Reported

| Project | Count |
|---|---:|
| Apple lipo | 2 |
| Safari crash | 2 |
| Cloudflare | 1 |
