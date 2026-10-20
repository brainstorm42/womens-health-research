# Release checklist

Use this checklist for future changes or added results. The current public starter is an invitation and methods bundle, not a clinical evidence claim.

## Scope and audience

- [ ] The front page is understandable to a reader with basic women's-health knowledge.
- [ ] The project states what has started, what is being invited, and what remains uncertain.
- [ ] Proposals, reviewed static findings, and provisional numerical results use the labels in the status taxonomy.
- [ ] The no-clinical-advice boundary is visible and unambiguous.
- [ ] AI-assisted checks are explicitly separated from human expert review still sought.

## Privacy and security

- [ ] No private conversation, email, personal context, donor/patient image, raw record, or re-identification clue is present.
- [ ] No absolute local path, home-directory path, credential, token, API key, secret, or private URL is present.
- [ ] No hidden file, editor backup, OS metadata file, or generated cache is present.
- [ ] A secret-pattern scan was run on text and filenames, and the result was read by a human.

## Copyright and third-party material

- [ ] No library PDF or copied source article is included.
- [ ] No figure, table, long quotation, full report, or third-party code is included without verified reuse rights.
- [ ] Every external source has a stable citation/link and its rights or access uncertainty is stated.
- [ ] The repository license decision is recorded. If it is still pending, no license file or broad reuse promise is added.

## Evidence quality

- [ ] Each factual claim has a source locator or is clearly labelled as original project guidance.
- [ ] Abstract-only, full-text, and reproduced-computation evidence are not conflated.
- [ ] Denominators, missingness, sampling, and uncertainty are stated where relevant.
- [ ] “Not found,” “not extracted,” “not verified,” and “not established” are used precisely.
- [ ] Strong health-related claims have qualified human review or remain clearly held back; this review is not a prerequisite for the invitation starter.

## Accessibility and maintainability

- [ ] Headings are nested logically and links have descriptive labels.
- [ ] Tables are simple enough for screen readers and have clear column headings.
- [ ] Technical detail appears after a plain-language explanation.
- [ ] Relative links work from the repository root.
- [ ] The allowlist and scan evidence match the files actually intended for release.

## Final local checks

- [ ] `git status` and the file inventory were inspected.
- [ ] Only intended files are staged or committed.
- [ ] No remote was added or pushed without explicit authorization.
- [ ] The final reviewer read the front page, the source register, and the scan output together.
