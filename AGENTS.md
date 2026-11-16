# AGENTS.md

Org defaults for PeleOs Technologies LLC, a US medical device company in orthopedic rehabilitation and sports medicine. `profile/README.md` is the public org page; the root `README.md` describes this repo.

## Layout

- `profile/README.md`: the public profile. Contact is info@peleos.tech.
- `SECURITY.md`: org-wide security reporting policy.
- `.github/workflows/`: CodeQL, dependency review, OpenSSF Scorecard. `.github/dependabot.yml` for the actions.
- `.gate.toml`: one gate, `doc-audit` in strict mode. `lefthook.yml` and `.gitleaks.toml` run the secret scan.

## Verify

`gate` runs doc-audit (and nothing else; there is no code). Run `gitleaks git --redact --no-banner` before a commit.

## Invariants

- Public repo. No device data, clinical claims, trial results, regulatory status or customer names; those are NOMAD's call and stay out of the profile unless he supplies the wording.
- Private internal guidance goes in `PeleOs-LLC/.github-private`, never here.
- Actions are pinned to a full commit SHA.
