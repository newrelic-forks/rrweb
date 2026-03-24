---
"@newrelic/rrweb-all": patch
"@newrelic/rrweb-packer": patch
"@newrelic/rrweb-record": patch
"@newrelic/rrweb-replay": patch
"@newrelic/rrdom": patch
"@newrelic/rrweb": patch
"@newrelic/rrweb-player": patch
"@newrelic/rrweb-snapshot": patch
"@newrelic/rrweb-types": patch
"@newrelic/rrweb-utils": patch
---

Provide a /umd/ output folder alongside the /dist/ one so that we can serve UMD (Universal Module Definition) files with a .js extension, without upsetting expectations set by package.json that all .js files in /dist/ are modules
