# Amazon Signer (amazon-signer)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS Signer is a fully managed code-signing service to ensure the trust and integrity of your code. It manages the code-signing certificate public and private keys and enables central management and deployment of code signing certificates for Lambda functions and IoT devices.

**URL:** [https://aws.amazon.com/signer/](https://aws.amazon.com/signer/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Code Signing, IoT, Lambda, Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Signer API

The AWS Signer API provides programmatic access to create and manage signing profiles, signing jobs, and signing platform permissions for code signing of Lambda functions and IoT device software.

**Human URL:** [https://aws.amazon.com/signer/](https://aws.amazon.com/signer/)

#### Tags:

 - Code Signing, Lambda, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/signer/latest/api/Welcome.html)
- [OpenAPI](openapi/amazon-signer.yaml)
- [GettingStarted](https://aws.amazon.com/signer/getting-started/)
- [Pricing](https://aws.amazon.com/signer/pricing/)
- [FAQ](https://aws.amazon.com/signer/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/signer/)
- [Documentation](https://docs.aws.amazon.com/signer/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/compute/tag/aws-signer/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/signer/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Centralized Code Signing | Security administrators define signing policies and which IAM roles can sign code. |
| Certificate Management | Automatically manages code-signing certificate public and private keys. |
| Lifecycle Management | Central management and deployment of code-signing certificates. |
| Compliance Tracking | Integration with AWS CloudTrail tracks who generates signatures for compliance. |
| Fully Managed | No infrastructure to maintain — fully managed code signing service. |
| Signature Revocation | Revoke signing profiles and individual signatures with effective timestamps. |

## Use Cases

| Name | Description |
|------|-------------|
| Lambda Code Signing | Sign Lambda deployment packages to ensure only trusted code is deployed. |
| IoT Firmware Signing | Sign firmware images for microcontrollers and OTA updates via Amazon FreeRTOS. |
| Container Image Signing | Sign container images using Notation CLI with Amazon ECR and verify at EKS deployment. |
| Audit and Compliance | Track all signing operations via CloudTrail for audit and compliance requirements. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Sign Lambda deployment packages; Lambda verifies signatures at deployment. |
| Amazon FreeRTOS | Sign firmware images for IoT microcontrollers and OTA updates. |
| Amazon ECR | Sign container images using Notation CLI stored in ECR registry. |
| Amazon EKS | Verify image ownership and integrity at Kubernetes deployment time. |
| AWS Certificate Manager | Create or import SSL/TLS certificates used for code signing. |
| AWS CloudTrail | Record and audit all API calls to AWS Signer for compliance. |
| AWS IoT Device Management | Sign code for IoT devices managed by AWS IoT Device Management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-signer.yaml](openapi/amazon-signer.yaml)

### JSON Schema

- [amazon-signer-add-profile-permission-request-schema.json](json-schema/amazon-signer-add-profile-permission-request-schema.json)
- [amazon-signer-add-profile-permission-response-schema.json](json-schema/amazon-signer-add-profile-permission-response-schema.json)
- [amazon-signer-cancel-signing-profile-request-schema.json](json-schema/amazon-signer-cancel-signing-profile-request-schema.json)
- [amazon-signer-category-schema.json](json-schema/amazon-signer-category-schema.json)
- [amazon-signer-describe-signing-job-request-schema.json](json-schema/amazon-signer-describe-signing-job-request-schema.json)
- ... and 60 more

### JSON Structure

- [amazon-signer-add-profile-permission-request-structure.json](json-structure/amazon-signer-add-profile-permission-request-structure.json)
- [amazon-signer-add-profile-permission-response-structure.json](json-structure/amazon-signer-add-profile-permission-response-structure.json)
- [amazon-signer-cancel-signing-profile-request-structure.json](json-structure/amazon-signer-cancel-signing-profile-request-structure.json)
- [amazon-signer-category-structure.json](json-structure/amazon-signer-category-structure.json)
- [amazon-signer-describe-signing-job-request-structure.json](json-structure/amazon-signer-describe-signing-job-request-structure.json)
- ... and 60 more

### JSON-LD

- [amazon-signer-context.jsonld](json-ld/amazon-signer-context.jsonld)

### Examples

- [amazon-signer-add-profile-permission-request-example.json](examples/amazon-signer-add-profile-permission-request-example.json)
- [amazon-signer-add-profile-permission-response-example.json](examples/amazon-signer-add-profile-permission-response-example.json)
- [amazon-signer-cancel-signing-profile-request-example.json](examples/amazon-signer-cancel-signing-profile-request-example.json)
- [amazon-signer-category-example.json](examples/amazon-signer-category-example.json)
- [amazon-signer-describe-signing-job-request-example.json](examples/amazon-signer-describe-signing-job-request-example.json)
- ... and 60 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-signer.yaml](capabilities/shared/amazon-signer.yaml) — AWS Signer operations for code signing management

## Vocabulary

- [Amazon Signer Vocabulary](vocabulary/amazon-signer-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 12 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Signer Spectral Rules](rules/amazon-signer-spectral-rules.yml) — 24 rules across 9 categories enforcing Amazon Signer API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
