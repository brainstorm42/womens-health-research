# Staging allowlist and scan limits

This file defines the bounded public staging set. It is a review aid, not a complete security guarantee.

## Allowed files

The intended starter set is:

- `.gitignore`
- `README.md`
- `CONTRIBUTING.md`
- `docs/missing-sources.md`
- `docs/provenance-and-scope.md`
- `docs/status-taxonomy.md`
- `docs/release-checklist.md`
- `checks/allowlist.md`
- `checks/staging-scan.txt`

No PDFs, Office files, images, datasets, notebooks, archives, credentials, or source-code imports are allowed in this starter.

## Text patterns to reject or review

Review the complete text and filenames for:

- absolute local paths, home-directory paths, file URIs, or editor/project-private locations;
- private conversation markers, email addresses, phone numbers, donor/patient identifiers, or unredacted correspondence;
- personal-access-token, API-key, cloud-key, OAuth/bearer-token, private-key, password, or secret-assignment patterns;
- full third-party reports, source PDFs, copied figures/tables, long quotations, or code whose reuse rights are not verified;
- claims framed as clinical advice, diagnosis, treatment instructions, or proof of clinical validation;
- claims that a paper, structure, or result “does not exist” based only on a failed search or access attempt.

## Allowed content types

- original plain-language guidance;
- short bibliographic metadata and links to authoritative records;
- short source-bounded summaries with explicit locators and uncertainty;
- proposals and methods using public or synthetic data;
- accessibility, reproducibility, and review instructions.

## Explicit limits

These checks cannot prove that a secret, private fact, copyrighted passage, or personal identifier is absent from every possible encoding or derivative. They do not verify external licenses, the scientific truth of a claim, the identity or expertise of a contributor, or the safety of a clinical decision. Human review is required before any public release.
