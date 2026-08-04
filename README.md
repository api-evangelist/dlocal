# dLocal

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

dLocal is an emerging markets payment platform that enables global merchants to accept and disburse local payment methods and currencies through a single REST API. The platform covers 60+ countries across Africa, Asia, and Latin America, supporting 1,000+ local payment methods including cards, cash, bank transfers, mobile money, and eWallets, with $41 billion in payments processed in 2025.

## APIs

- **Payins API** — Accept payments using local payment methods including cards, bank transfers, cash, mobile money, eWallets, and Pix. Supports 3D Secure, installments, recurring payments, and authorization/capture flows.
- **Payouts API** — Distribute funds globally with multi-currency support and local compliance. Includes balance checking, FX quote generation, and payout lifecycle management.
- **Platforms API** — Complete marketplace solution with automated account onboarding, KYC, bank account management, and transfer operations.
- **Verification API** — Identity verification and document management for compliance workflows.

## Authentication

All API requests use HMAC-SHA256 signature-based authentication. Requests require X-Login, X-Trans-Key, X-Date, and Authorization headers. Credentials are obtained from the dLocal Merchant Dashboard.

## Resources

- [Developer Documentation](https://docs.dlocal.com/)
- [API Reference](https://docs.dlocal.com/reference/api)
- [Get Started](https://docs.dlocal.com/docs/get-started)
- [Postman Workspace](https://www.postman.com/dlocal-dev)
- [GitHub Organization](https://github.com/dlocal)
- [Status Page](https://dlocal.statuspage.io/)
- [Blog](https://www.dlocal.com/blog/)

## Links

- [Website](https://www.dlocal.com/)
- [LinkedIn](https://www.linkedin.com/company/dlocal)
- [X / Twitter](https://twitter.com/dLocalPayments)
