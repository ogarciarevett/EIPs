Please review [EIP-1](https://eips.ethereum.org/EIPS/eip-1) for EIP guidelines.

<!-- RATIONALE FOR THIS FILE: IT IS DISPLAYED WHEN YOU CREATE AN ISSUE OR MAKE A PR -->

## Contribution workflow and AI assistance

This section applies only to [ogarciarevett/EIPs](https://github.com/ogarciarevett/EIPs), an owner-controlled fork of [ethereum/EIPs](https://github.com/ethereum/EIPs). It does not change upstream policy or authorize an upstream PR. For this fork, it supersedes conflicting inherited wording only about the PR workflow, AI disclosure, and AI attribution trailers; substantive quality, review, CLA/DCO, license, security, and testing requirements remain in force.

All contributors and agents must work on a topic branch and submit changes by pull request to `master`. Only the human repository owner, after confirming exact GitHub account control, may choose direct changes to `main` or the default branch; existing protections still apply. Agents must never directly update those branches, even when authenticated with the owner's account. GitHub account authentication does not establish that a human is operating it.

AI assistance is welcome. In the PR description, disclose each tool, the model identifier when exposed, and the scope of its help. If the model is not exposed, say `unknown (not exposed)`; do not guess. This scoped disclosure is required even if an inherited instruction otherwise discourages tool attribution.

Example disclosure (replace the example with accurate details):

```text
AI assistance: tool = coding assistant; model = unknown (not exposed).
Scope: helped draft the change and tests.
Human responsibility: I reviewed and understand every submitted change.
Validation: list actual checks and results, or explain checks not run.
```

A named human must review and understand the complete change, verify its tests and claims, check security and privacy, and confirm the right to contribute all code and dependencies under the applicable licenses. AI assistance does not waive existing review, CLA/DCO, signing, coverage, or CI requirements. Follow the existing commit conventions, including Conventional Commits where required. No AI `Co-authored-by` trailer or one-line commit attribution is required; any required human credit or DCO sign-off still applies.

Do not include secrets, personal data, private prompts, conversation transcripts, or hidden reasoning in the disclosure. None is required. Provide only the tool/model, scope, human accountability, and actual validation evidence.
