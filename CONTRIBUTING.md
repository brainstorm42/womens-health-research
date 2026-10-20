# Contributing

Thank you for taking a look. This project is meant to make women's health evidence easier to inspect and improve, one bounded task at a time. You do not need to be a clinician to help, and you should not present yourself as one unless that is your training.

## Four useful contribution roles

| Role | A good first contribution | What to record |
| --- | --- | --- |
| Source finding | Locate an exact paper, dataset, protocol, or public method page | Stable citation, DOI/PMID or URL, access date, lawful access route, and what remains unavailable |
| Claim checking | Compare one short claim with its cited source | Source locator, wording boundary, population/method limits, and unresolved uncertainty |
| Reproduction | Re-run a small public or synthetic-data analysis | Data and code provenance, environment, transformations, checks, and deviations |
| Accessibility | Improve headings, plain language, tables, link labels, or screen-reader flow | What changed, what was tested, and any remaining barrier |

## A safe, repeatable workflow

1. Choose one small question or one source. Open an issue first if the scope is unclear.
2. Use public sources, synthetic data, or data with a clearly documented lawful access path. Do not work around paywalls, login barriers, robots restrictions, or copyright controls.
3. Keep a provenance note: exact source, version or date, locator, transformation, and reviewer status.
4. State what the result does **not** show. A small sample, a reported subgroup, a marker, or a statistical association is not automatically a diagnosis, mechanism, treatment effect, or population estimate.
5. Ask for an independent check. An AI-assisted comparison can catch transcription or locator errors, but it does not replace a qualified human review for health claims.
6. Keep the change narrow and readable. Prefer a small pull request over a large unreviewed import.

## Plain-language expectations

Write for a reader with basic familiarity with women's health, not specialist shorthand. Define technical terms the first time. Put the short explanation first; link to the precise source and method underneath. Explain denominators, missingness, uncertainty, and whether a statement is a proposal, a static source finding, or a provisional numerical result.

## Privacy, safety, and rights

Do not add:

- patient or donor images, raw records, or re-identification clues;
- private conversations, email addresses, correspondence, or personal context;
- passwords, access tokens, API keys, credentials, or local absolute paths;
- library PDFs, copied figures, full third-party reports, or third-party code without verified reuse permission;
- allegations about identifiable authors or institutions that are not necessary and source-supported;
- clinical advice, diagnosis, treatment instructions, or claims of clinical validation.

Use aggregate, public, or synthetic examples. Remove local paths and private identifiers from notebooks, logs, screenshots, and error messages before sharing.

## Access and participation

Useful contributions can be made with public bibliographic records, open sources, synthetic data, careful reading, documentation, and accessibility review. No paid subscription or specialist access is required for these entry roles. If a source is not accessible, record the attempt and mark the claim pending; do not imply that the source is nonexistent and do not ask someone to bypass access controls.

## Review labels

Use the labels in [the status taxonomy](docs/status-taxonomy.md). In particular, keep these separate:

- **Proposal:** a question or planned test, not a result.
- **Reviewed static finding:** a source-level check with an explicit locator and boundary, not a new biological validation.
- **Provisional numerical result:** a reproducible calculation using public or synthetic data that still needs independent review.
- **Human expert review:** a named or otherwise documented qualified review, distinct from an AI check.

## License

The repository license is intentionally pending. Until the project owner records a choice, do not assume that original text, code, or future contributions are available for unrestricted reuse. Third-party material keeps its own terms.
