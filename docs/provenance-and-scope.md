# Provenance and scope

## Purpose

This repository is a bounded public staging project for evidence work in women's health. It is intentionally separate from the private working source tree. The goal is to make small questions, source gaps, methods, and uncertainty inspectable without publishing private material or copyrighted source files.

## What is in scope

- original project guidance and plain-language explanations;
- bibliographic metadata and links to authoritative records;
- short, source-bounded evidence notes with locators;
- proposals for work using public or synthetic data;
- reproducibility and accessibility instructions;
- independent checks of transcription, provenance, scope, and wording.

## What is out of scope

- private conversations or planning exports;
- patient-level or donor-level records, images, or re-identification clues;
- emails, credentials, tokens, secrets, or local absolute paths;
- library PDFs, copied figures, full third-party reports, or code without verified reuse rights;
- clinical advice, diagnosis, treatment guidance, or claims of clinical validation;
- claims that a source, result, or structure does not exist merely because access was unsuccessful.

## Provenance rules

Every source-level statement should identify:

1. the exact paper, dataset, protocol, or official page;
2. a DOI, PMID, accession, stable URL, or other durable identifier;
3. the access level: metadata, abstract, full text, or reproduced computation;
4. the locator or method step that supports the statement;
5. what was not checked and what uncertainty remains;
6. whether an independent check was AI-assisted, human, or both.

An access route is not a reuse license. Public readability is not permission to redistribute an article, figure, table, dataset, or code. When rights are unclear, link to the source and retain only original summaries and metadata.

## Evidence and review boundary

AI tools can help locate records, compare structured claims, and catch inconsistencies. Those checks must be labelled as AI-assisted and must not be described as human expert review. Health-related claims still need qualified human review before strong public interpretation. A reviewer may confirm a source-level statement without confirming a broader biological or clinical conclusion.

The current data boundary is public or synthetic data only. Any future analysis should state the dataset version, transformations, exclusions, missingness, uncertainty, and independent reproduction status. A provisional numerical result is not a clinical result.

## Context for unmet research needs

The purpose includes helping women and making neglected questions and resource gaps visible. The public framing is deliberately qualitative. For readers who want the underlying context, see the [National Academies' A New Vision for Women's Health Research](https://www.nationalacademies.org/read/28586/chapter/6), the [NIH explanation of its updated women's-health research spending category](https://www.grants.nih.gov/news-events/nih-extramural-nexus-news/2025/06/new-fy-2024-nih-categorical-spending-data-available-including-an-updated-womens-health-research-category-to-improve-accuracy-and-consistency), and [Mirin's historical burden-normalized study](https://journals.sagepub.com/doi/10.1089/jwh.2020.8682). These are different scopes and methods: the NIH note warns that its category series changed, while Mirin's analysis is historical and not a current global estimate. None of them is used here to infer motive or to turn incomplete reporting into a funding claim.

## Source-tree separation

Only the bounded files listed in [the allowlist](../checks/allowlist.md) belong in this staging repository. The private working source tree remains the place for local PDFs, working notes, intermediate files, and material whose rights or privacy status has not been cleared. Do not recreate that tree here with renamed folders or copied binaries.

## Maintenance

Before a remote or public release, run the [release checklist](release-checklist.md), read the generated scan evidence, and confirm the license choice. If a source becomes available later, update the missing-sources register with the access route and rights status rather than silently replacing an earlier uncertainty note.
