# Nerdgency add-on issues

This is where to report bugs and ask for features in **Nerdgency's ExpressionEngine add-ons**:

| Add-on | What it is | Docs | Issues |
| --- | --- | --- | --- |
| **[Formidable](https://nerdgency.ca/docs/formidable)** | Forms for ExpressionEngine | [Docs](https://nerdgency.ca/docs/formidable) | [Open issues](https://github.com/nerdgency/ee-addon-issues/issues?q=is%3Aissue+is%3Aopen+label%3Aformidable) |
| **[Autograph](https://nerdgency.ca/docs/autograph)** | Signatures for ExpressionEngine | [Docs](https://nerdgency.ca/docs/autograph) | [Open issues](https://github.com/nerdgency/ee-addon-issues/issues?q=is%3Aissue+is%3Aopen+label%3Aautograph) |

The add-ons' source isn't public. This repository holds only their issues. Each issue is labelled with the add-on it's about, so you can [choose a form](https://github.com/nerdgency/ee-addon-issues/issues/new/choose) for the right one, and filter by its label.

> [!CAUTION]
> **Found a security vulnerability? Don't open an issue.** Email **[security@nerdgency.ca](mailto:security@nerdgency.ca)** instead. See the [security policy](SECURITY.md).

## Before you open an issue

1. **Check the add-on's troubleshooting page:** [Formidable](https://nerdgency.ca/docs/formidable/getting-started/troubleshooting) · [Autograph](https://nerdgency.ca/docs/autograph/getting-started/troubleshooting).
2. **Update** to the add-on's latest release. Its changelog says what's been fixed: [Formidable](https://nerdgency.ca/docs/formidable/prologue/changelog) · [Autograph](https://nerdgency.ca/docs/autograph/prologue/changelog).
3. **Search the [open and closed issues](https://github.com/nerdgency/ee-addon-issues/issues?q=is%3Aissue).** If yours is already there, add a 👍 or a comment with your details instead of opening a new one. Upvotes help decide what gets done first.

> [!WARNING]
> Issues are public. Leave out submissions, visitors' answers, real signatures, API keys, credentials, passwords and your `config.php`. Use made-up values instead. If the problem only happens with real data, say so and we'll arrange a private way to look at it.

## Formidable

- **[Report a bug](https://github.com/nerdgency/ee-addon-issues/issues/new?template=formidable-bug-report.yml).** Include the Formidable, ExpressionEngine and PHP versions (Formidable's is at the bottom of its dashboard), the steps to reproduce it, what you expected and what happened instead, the template tag as written, and anything Formidable told you: what `debug="on"` said, any `<!-- formidable: … -->` comment in the page source, and anything in the Developer Log or the Workflow Log.
- **[Request a feature](https://github.com/nerdgency/ee-addon-issues/issues/new?template=formidable-feature-request.yml).** Describe the problem you're trying to solve, not only the solution: what the form is for, what you tried, and where Formidable got in the way.
- **[Request a fieldtype](https://github.com/nerdgency/ee-addon-issues/issues/new?template=formidable-fieldtype-request.yml).** What a visitor sees and does, what gets stored, any service it depends on, and an example. Want to build it yourself? See [Custom fieldtypes](https://nerdgency.ca/docs/formidable/extending/custom-fieldtypes).

## Autograph

- **[Report a bug](https://github.com/nerdgency/ee-addon-issues/issues/new?template=autograph-bug-report.yml).** Include the Autograph, ExpressionEngine and PHP versions (Autograph's is on the Add-Ons screen), where it happens (a Channel Form, a member form, the control panel, Grid or Fluid), the field's Storage Method, the steps to reproduce it, and anything in the browser's console or the Developer Log.
- **[Request a feature](https://github.com/nerdgency/ee-addon-issues/issues/new?template=autograph-feature-request.yml).** What you're collecting signatures for, and where Autograph gets in the way.

## Reporting a security vulnerability

If you think you've found a security problem in any of the add-ons, **email [security@nerdgency.ca](mailto:security@nerdgency.ca)**. Don't open a public issue or share it anywhere else until a fix is released. The [security policy](SECURITY.md) says what to include and what happens next.

## Labels

| Label | Meaning |
| --- | --- |
| `formidable`, `autograph` | The add-on an issue is about. Added by the issue forms. |
| `bug` | Something doesn't work as documented. |
| `enhancement` | A new feature, or a change to an existing one. |
| `fieldtype` | A request for a new Formidable fieldtype. |

## Formerly `ee-formidable-issues`

This repository used to be Formidable's alone. Old links to `github.com/nerdgency/ee-formidable-issues` redirect here, and Formidable's issues are all still here, labelled `formidable`.
