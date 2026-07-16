# OSS Bug Fixes / Reports

> Details for private reports will be disclosed after vendor confirmation, public advisory, or explicit permission from the vendor.  
> Entries are based on manual verification and vendor-visible artifacts.

Started from 4 May.  
Last updated: 2026-06-23.




## CVE

[CVE-2026-54010](https://github.com/open-webui/open-webui/security/advisories/GHSA-vrhc-3fr6-pc3c)

## Public / Verified

| Project | Count | Status |
|---|---|---|
| NGINX | 1 | [commit](https://github.com/nginx/nginx/commit/18a70a4d5806b5578d00460493954262ece55019) |
| Bun | 1 | [bun#30621](https://github.com/oven-sh/bun/issues/30621) |
| Chrome PDFium | 1 | Verified |
| OpenClaw | 1 | [GHSA](https://github.com/openclaw/openclaw/security/advisories/GHSA-fh8v-vgcv-pwh4) |
| DuckDB | 3 |[#22663](https://github.com/duckdb/duckdb/issues/22663) [#22660](https://github.com/duckdb/duckdb/issues/22660) [PR #23100](https://github.com/duckdb/duckdb/pull/23100)|
| VLC media | 1 | Verified; fix scheduled for 3.0.24 |
| openbao | 1| [#3235](https://github.com/openbao/openbao/issues/3235) |
| canonical-workshop | 1 | GHSA accepted [PR #929](https://github.com/canonical/workshop/commit/0a5252b713327eead41ec6f9df3716c195d20e59) |
| Protobuf | 1 | [commit](https://github.com/protocolbuffers/protobuf/commit/d944dd038764011730fec2c28e8d738dac2bd828); Google OSS VRP tracking |
| git | 1 | [PATCH](https://lore.kernel.org/git/20260624-pks-reftable-hardening-v1-0-66e4ce87c6b9@pks.im/T/#m84b44a2c7616caedbdc253a3e8172f21d6883d0f) |
| Linux Kernel | 1 | [commit](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf.git/commit/?id=a6f0643e4f63cfaa0d5d4a69de4f132eac4b8fe4) |
| SUM | 13 | |
## Pending Private Disclosure

| Vendor / Project | Count | Notes |
|---|---:|---|
| Bun | 5 | Several hardening fixes observed; credit/status unclear |
| ClickHouse | 3 | BugCrowd |
| cloudflare | 2 | HackerOne |
| Apple macOS | 3 | Submitted to Phrack 73 after Apple declined security classification |
| SUM |13 ||


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

## Not sure
| Project | Issue |
|---|---|
| llama.cpp | [ggml-org/llama.cpp#23108](https://github.com/ggml-org/llama.cpp/issues/23108) |
