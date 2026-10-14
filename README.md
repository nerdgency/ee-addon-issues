# Formidable issues

This is where to report bugs and ask for features in **[Formidable](https://nerdgency.ca/docs/formidable)**, the forms add-on for ExpressionEngine. New fieldtypes are welcome as requests too.

Formidable's source isn't public. This repository holds only its issues.

> [!CAUTION]
> **Found a security vulnerability? Don't open an issue.** Email **[security@nerdgency.ca](mailto:security@nerdgency.ca)** instead. See [Reporting a security vulnerability](#reporting-a-security-vulnerability).

## Before you open an issue

1. **Check [Troubleshooting](https://nerdgency.ca/docs/formidable/getting-started/troubleshooting).** Adding `debug="on"` to the form tag usually says what's wrong.
2. **Update** to the latest Formidable 1.x release. The [release notes](https://nerdgency.ca/docs/formidable/prologue/release-notes) say what's been fixed.
3. **Search the [open and closed issues](https://github.com/nerdgency/ee-formidable-issues/issues?q=is%3Aissue).** If yours is already there, add a 👍 or a comment with your details instead of opening a new one. Upvotes help decide what gets done first.

## Reporting a bug

[Open a bug report](https://github.com/nerdgency/ee-formidable-issues/issues/new?template=bug_report.yml) and include:

1. **Versions:** Formidable, ExpressionEngine and PHP. Formidable's version is at the bottom of its dashboard.
2. **What you did,** step by step, so the problem can be reproduced.
3. **What you expected,** and **what happened instead.**
4. **The template tag as written,** with every parameter, if the problem is on the front end.
5. **Anything Formidable told you:** what `debug="on"` said, any `<!-- formidable: … -->` comment in the page source, and anything in the Developer Log or the Workflow Log.
6. **Screenshots,** if they help.

> [!WARNING]
> Issues are public. Leave out submissions, visitors' answers, API keys, Connection credentials, passwords and your `config.php`. Use made-up values instead. If the problem only happens with real data, say so and we'll arrange a private way to look at it.

## Requesting a feature

[Open a feature request](https://github.com/nerdgency/ee-formidable-issues/issues/new?template=feature_request.yml). Describe **the problem you're trying to solve**, not only the solution you have in mind: what the form is for, what you tried, and where Formidable got in the way.

## Requesting a fieldtype

[Open a fieldtype request](https://github.com/nerdgency/ee-formidable-issues/issues/new?template=fieldtype_request.yml) and tell us:

- **What a visitor sees and does:** the control, and what they pick, type or upload.
- **What gets stored,** and how it should look in the control panel, exports, emails and the API.
- **Any service it depends on,** such as an address lookup or a payment provider.
- **An example** of the field on another site, if you have one.

Want to build it yourself? See [Custom fieldtypes](https://nerdgency.ca/docs/formidable/extending/custom-fieldtypes).

## Reporting a security vulnerability

If you think you've found a security problem in Formidable, such as a way to bypass validation or spam protection, read submissions you shouldn't, run code, or reach the API without permission, **email [security@nerdgency.ca](mailto:security@nerdgency.ca)**. Don't open a public issue or share it anywhere else until a fix is released.

Include what the problem is and what an attacker could do with it, the steps to reproduce it, the Formidable, ExpressionEngine and PHP versions you tested, and anything that limits it (a setting that has to be on, a permission the attacker needs).

We'll confirm we've received it, keep you updated, and release a fix as soon as we can. We're glad to credit you in the release notes, or to leave your name out if you prefer.

Please test only against your own installations, never against a site you don't own or have permission to test.

## Links

- [Documentation](https://nerdgency.ca/docs/formidable)
- [Getting help](https://nerdgency.ca/docs/formidable/getting-started/support)
- [Release notes](https://nerdgency.ca/docs/formidable/prologue/release-notes)
