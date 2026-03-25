---
"@newrelic/rrweb-record": minor
"@newrelic/rrweb-replay": minor
---

Note - this has been downgraded from a major change to a minor change to reflect this is not major version bump in newrelic forked repo at this time.

BREAKING CHANGE: Rename UMD global names from `rrweb` to `rrwebRecord` for the recorder and `rrwebReplay` for the replayer. This avoids conflicts when both are loaded on the same page.
