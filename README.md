# rulespec-us-ca

This repository is archived. Its canonical content now lives in
[`TheAxiomFoundation/rulespec-us`](https://github.com/TheAxiomFoundation/rulespec-us)
under `us-ca/`; keep all future RuleSpec work there.

California RuleSpec encodings and source registry metadata.

## Contents

- `statutes/`: California statute RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `regulations/`: California regulation RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `policies/`: California policy RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `sources/`: source registry or manifest metadata when needed.
- `.github/workflows/repository-checks.yml`: wrapper around the shared RuleSpec validation workflow.

## Conventions

Use RuleSpec YAML for encoded rules. Do not add singular rule roots, separate
parameter/test fixture files, or generated formula artifacts.

In the canonical monorepo, California-administered materials live under `us-ca/`; shared federal materials live at the country root.
