# .github Repository

This repository hosts shared GitHub resources for the organization. Use it to
standardize issue templates, pull request templates, workflow configurations,
and other reusable assets that improve consistency across projects.

## Repository Structure

| Path | Purpose |
| --- | --- |
| `workflows/` | Organization-wide GitHub Actions workflows. |
| `ISSUE_TEMPLATE/` | Markdown templates for common issue types. |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template shared across repos. |
| `CODEOWNERS` | Optional ownership rules for automated reviews. |
| `README.md` | You're reading it—describes how to use this repository. |

> ℹ️ If a directory or file listed above is missing, feel free to add it when
you introduce the corresponding resource.

## Getting Started

1. Clone the repository alongside the project that needs the shared assets:
   ```bash
   git clone https://github.com/<org>/.github.git
   ```
2. Add or update the desired configuration files (e.g., `ISSUE_TEMPLATE/`,
   `PULL_REQUEST_TEMPLATE.md`, or `workflows/`).
3. Commit your changes and open a pull request so that automation and templates
   stay version-controlled.

## Best Practices

- **Keep templates concise:** Focus on prompts that help contributors provide
  actionable information.
- **Document workflows:** When adding GitHub Actions, include comments in the
  YAML files to explain required secrets and expected behavior.
- **Test before merging:** Use draft pull requests to validate workflow changes
  so production repositories are not disrupted.

## Contributing

1. Create a new branch for your update.
2. Make your changes and include documentation when necessary.
3. Run any relevant checks (such as workflow linting) locally if possible.
4. Submit a pull request and request review from the DevOps team.

## Support

If you have questions about these shared assets or need help creating a new
workflow, open an issue in this repository or reach out to the DevOps team on
Slack.
