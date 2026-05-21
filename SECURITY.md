# Security Policy 

## Versions

Due to the nature of our project - being open source - we have decided to patch only the latest major release (currently v1.x) for security vulnerabilities.

## How to disclose

Please use [our website](https://flarum.org/foundation/contact) for security issues that affect our project. If you believe you have found a vulnerability, please disclose it via our website. You can also disclose security issues by mailing security@flarum.org.

## What we do

Any submitted security issue will be checked thoroughly by our development team. A fix for the issue and a transparent information on GitHub about the issue existing will be released. You can view any previously identified issues on our [GitHub Security Page](https://github.com/flarum/.github/security). New major versions of Flarum will also receive a security audit to verify our efforts on providing a secure application.

## Respecting maintainer time
Flarum’s security team are volunteers. Please be mindful and respectful of their time when submitting reports. Your initial report should give the team enough to make a triage decision, no more. It should include:

- A brief description of the issue and where in Flarum it occurs.
- A minimal, working proof of concept (code snippet or reproduction steps).
- The versions of Flarum you tested against.
- Optionally, a minimal patch with the mitigation for the issue.

Please do not include severity scores (CVSS or otherwise), lengthy background sections, multiple headers, or a determination of whether the issue constitutes a vulnerability. The security team will make those assessments. Extensive upfront analysis makes triage slower, not faster. If the team confirms the issue is a valid vulnerability, they will follow up and welcome further detail at that stage.

If you have identified multiple potential issues, please wait for a triage result on your initial report before submitting further ones. Exceptions can be made for issues that are clearly and directly related to an already reported finding. Feedback on an initial report is often relevant to subsequent ones, and taking the time to read and incorporate it leads to better reports overall.

The security team is not able to process large volumes of reports submitted in a short period of time, and reports submitted in bulk may be put on hold.

## AI-Assisted Reports
Following the widespread availability of large language models (LLMs), the Flarum Security Team has received a growing number of security reports generated partially or entirely using such tools. Many of these contain inaccurate, misleading, or fictitious content. While AI tools can help draft or analyze reports, they must not replace human understanding and review.

If you use AI tools to help prepare a report, you must:

- Disclose which AI tools were used and specify what they were used for (analysis, writing the description, writing the exploit, etc).
- Verify that the issue describes a real, reproducible vulnerability that otherwise meets these reporting guidelines.
- Avoid fabricated code, placeholder text, or references to non-existent Flarum features.
- Reports that appear to be unverified AI output will be closed without response. Repeated low-quality submissions may result in a ban from future reporting.

We align with similar policies adopted by other major open-source projects, which have described the flood of unverified AI-generated reports as disruptive, counterproductive, and a drain on limited security team resources.

Flarum’s security process depends on accurate and responsible reports. Please support the project by ensuring that any AI-assisted submissions meet a high standard of clarity and technical accuracy.
