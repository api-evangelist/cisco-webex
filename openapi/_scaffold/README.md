# Quarantined scaffold — not published by Cisco

The OpenAPI documents in this directory were **written by API Evangelist**, modelled from Cisco's
public Webex documentation. They were never published by Cisco and must not be presented as Cisco
artifacts, cited as evidence of what Cisco ships, or credited in a Kin Score.

They were moved here on **2026-07-31**.

## Why they were quarantined

Cisco *does* publish Webex OpenAPI, from a Cisco-owned GitHub organization:

> https://github.com/webex/webex-openapi-specs — `public-spec/`

Nine OpenAPI 3.0.0 documents, **1,382 paths / 2,053 operations / 4,498 schemas**, last pushed
2026-07-29. Those are now harvested into `../_original/` and are the only contracts this provider
should be scored on.

The 19 documents here totalled **92 operations** — about **4.5%** of what Cisco actually publishes.
Because they carried no `x-generated-from` / `x-provenance` marker, the rubric 0.6 provenance grader
read them as first-party and credited them in full, which inflated this provider to a **75.4
"exemplar"** composite earned largely on specifications API Evangelist wrote.

See `[[scaffold-fabrication-sweep]]` and `[[kin-score-provenance-gap]]` for the general failure mode.

## Contents

19 hand-modelled documents, one per Webex resource area (`messaging`, `meetings`, `rooms`, `teams`,
`people`, `webhooks`, `devices`, …), plus 21 per-tag files that `refine-openapis` split out of them.
Everything in here is downstream of the hand-modelled set.

## Do not

- Restore these to `_original/`.
- Re-run `refine-openapis` against them.
- Point `apis.yml` at them.
