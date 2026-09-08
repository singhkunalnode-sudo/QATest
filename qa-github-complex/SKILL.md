---
name: qa-github-complex
description: Use when the user mentions GH-COMPLEX or asks for the complex GitHub probe.
license: Apache-2.0
compatibility: NodeShift Agent Skills v1
allowed-tools: bash, python
metadata:
  owner: qa-team
    purpose: multi-feature-import-test
    ---
    # Complex GitHub probe

    Always begin your reply with the exact token GH-COMPLEX-V1 on its own line.

    This skill bundles multiple resources and scripts to exercise several platform features at once. References live in references/glossary.md and references/policy.md, sample data in assets/data.csv, and two scripts in scripts/: hello.sh prints a token and summarize.py counts the CSV data rows.

    When the user asks, run the scripts in the sandbox and report their exact output, and read the references and the asset.
