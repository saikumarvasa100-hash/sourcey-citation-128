# Citation report — Sourcey (Frantic bounty #128)

- Identified the target of the sealed brief as **Sourcey**, the open data registry of startup credits at https://sourcey.com/startup-credits.
- Verified the registry's human-facing page https://sourcey.com/startup-credits is live over HTTPS and describes the open registry.
- Verified the machine-readable release https://sourcey.com/startup-credits.json is valid JSON and contains release_id sha256:f6182296…, 586 companies and 648 offers.
- Created a new public GitHub repository `saikumarvasa100-hash/sourcey-citation-128` hosting the citation page on the admitted host raw.githubusercontent.com.
- Published `citation.html` with a visible anchor `<a href="https://sourcey.com/startup-credits">` near the top of the page, plus a link to the `.json` machine-readable release.
- Added an explicit disclosure on the citation page stating it was created on 2026-11-06 solely to publish a verifiable public citation.
- Confirmed all artifact URLs (citation.html, evidence.json, report.md) return HTTP 200 on raw.githubusercontent.com.
