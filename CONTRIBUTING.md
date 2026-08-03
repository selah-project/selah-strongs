# Contributing to Selah Strong's renderings

Thank you for helping make these lexical renderings accurate and natural in
each target language. Reports from native speakers and careful lexicon users
are especially valuable.

## Choose an issue or a pull request

- Open an **issue** when the meaning or wording needs discussion.
- Open a **pull request** when the exact correction is clear.
- Report application defects and private security or account matters through
  [Selah support](https://selahproject.com/support), not a public issue.

## What to include

Identify the Strong's number, language, current text, proposed text, and reason
for the change. Include a lexical source or explain the target-language problem.
State whether you are a native speaker of the target language.

## Editing a record

Files follow `<language>/<bucket>/H####.edn`.

- For an ordinary translation correction, edit the target-language `:text`.
- Preserve `:strongs`, `:hebrew`, `:lang`, the English source `:gloss`, and
  provenance fields unless the report specifically concerns one of them.
- Preserve valid EDN syntax and the established divine-name and Hebrew-script
  conventions.
- Keep each pull request narrow; avoid bulk rephrasing without prior discussion.

Strong's is a historical lexicon. If its inherited English definition is
obsolete, incomplete, or disputed, do not silently replace the source witness
through a target-language edit. Open an issue so the inherited source and a
modern clarification can remain distinguishable.

## AI-assisted work

Disclose material use of a language model or automated translation tool,
including the human review performed. Unreviewed bulk output is not accepted.

## License and attribution

Contribute only wording you have the right to submit. By submitting, you agree
that accepted material will be distributed under this repository's
[CC BY-SA 4.0 license](LICENSE.md). Git history preserves the public correction
record and contributor attribution.

## Review

Maintainers weigh the source definition, Hebrew headword, target-language
usage, repository conventions, and evidence supplied. A proposal may be
accepted, revised, held for more evidence, or declined with an explanation.
Please critique the text rather than the person proposing it.
