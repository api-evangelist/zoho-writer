# Zoho Writer

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

Zoho Writer is an online word processor with a REST API for creating, editing, merging, converting, and signing documents, and automating document workflows within the Zoho ecosystem.

## API Capabilities

- **Document APIs** — Create, retrieve, update, download, and share documents
- **Meta APIs** — Retrieve document and template metadata
- **Combine APIs** — Merge multiple documents into one
- **Merge APIs** — Mail merge using templates with data sources; supports Merge and Email
- **Sign APIs** — Trigger electronic signature workflows via Zoho Sign integration
- **Webhooks** — Automate document generation from third-party application events

## Authentication

OAuth 2.0 with scopes such as `ZohoWriter.documentEditor.ALL` and `ZohoWriter.merge.ALL`. Access tokens are valid for one hour; refresh tokens have unlimited lifetime. Register applications at the [Zoho Developer Console](https://accounts.zoho.com/developerconsole).

## Data Centers

API base URLs are region-specific:

| Region | Base URL |
|---|---|
| United States | `https://writer.zoho.com/api/v1` |
| Europe | `https://writer.zoho.eu/api/v1` |
| India | `https://writer.zoho.in/api/v1` |
| Japan | `https://writer.zoho.jp/api/v1` |
| Australia | `https://writer.zoho.com.au/api/v1` |
| Canada | `https://writer.zoho.ca/api/v1` |

## Resources

- [Developer Portal](https://www.zoho.com/writer/developers.html)
- [API Documentation](https://www.zoho.com/writer/help/api/v1/)
- [OAuth 2.0 Guide](https://www.zoho.com/writer/help/api/v1/oauth-2.html)
- [Rate Limits](https://www.zoho.com/writer/help/api/v1/writer-apis-threshold-limits.html)
- [Pricing / Automation Credits](https://help.zoho.com/portal/en/kb/writer/writer-add-ons/pricing-faq/articles/how-can-i-purchase-the-writer-add-on)
- [Status Page](https://status.zoho.com)
- [What's New](https://www.zoho.com/writer/whats-new.html)
- [Blog](https://www.zoho.com/blog/writer/)
- [X / Twitter](https://x.com/ZohoWriter)
- [GitHub](https://github.com/zoho)
- [LinkedIn](https://www.linkedin.com/company/zoho)
