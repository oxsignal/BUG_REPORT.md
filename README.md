# OSS Bug Fixes / Reports

> Details for private reports will be disclosed after vendor confirmation, public advisory, or explicit permission from the vendor.  
> Entries are based on manual verification and vendor-visible artifacts.

Started from 4 May.  
Last updated: 2026-06-23.
|||
|---|---|
|Tried| 50|
|CVE|1|
|Accepted| 12|
|Pending| 13|
|N_A| 18|
|N_R| 5|


## CVE

[CVE-2026-54010](https://github.com/open-webui/open-webui/security/advisories/GHSA-vrhc-3fr6-pc3c)

## Public / Verified

| Project | Count | Status |
|---|---|---|
| NGINX | 1 | [commit](https://github.com/nginx/nginx/commit/18a70a4d5806b5578d00460493954262ece55019) |
| Bun | 1 | [bun#30621](https://github.com/oven-sh/bun/issues/30621) |
| Chrome PDFium | 1 | Verified |
| OpenClaw | 1 | [PR #83741](https://github.com/openclaw/openclaw/pull/83741) |
| DuckDB | 1 |[#22663](https://github.com/duckdb/duckdb/issues/22663) [#22660](https://github.com/duckdb/duckdb/issues/22660)
| VLC media | 1 | Verified; fix scheduled for 3.0.24 |
| openbao | 1| [#3235](https://github.com/openbao/openbao/issues/3235) |
| canonical-workshop | 1 | GHSA accepted |
| Protobuf | 1 | [commit](https://github.com/protocolbuffers/protobuf/commit/d944dd038764011730fec2c28e8d738dac2bd828); Google OSS VRP tracking |
| git | 1 | verified |
| DuckDB | 1 |[PR #23100](https://github.com/duckdb/duckdb/pull/23100) |
| Linux Kernel | 1 | verified |
| SUM | 12 | |
## Pending Private Disclosure

| Vendor / Project | Count | Notes |
|---|---:|---|
| Bun | 5 | Several hardening fixes observed; credit/status unclear |
| ClickHouse | 3 | BugCrowd |
| cloudflare | 2 | HackerOne |
| Apple macOS | 3 | Submitted to Phrack 73 after Apple declined security classification |
| SUM |13 ||
## Public Issues / Not Yet Verified by Maintainer

| Project | Issue |
|---|---|
| llama.cpp | [ggml-org/llama.cpp#23108](https://github.com/ggml-org/llama.cpp/issues/23108) |

## Duplicate / Not Accepted

| Project | Count | Notes |
|---|---:|---|
| canonical-workshop | 1 | out of scope |
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
| SUM |18 ||
## Not Reported

| Project | Count |
|---|---:|
| Apple lipo | 2 |
| Safari crash | 2 |
| Cloudflare | 1 |
| SUM |5 ||
