# Lawhive

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

Lawhive is a UK consumer legal-services marketplace that connects individuals and small businesses with regulated solicitors online at fixed, transparent prices. Clients answer intake questions on the site, receive a quote or a callback, and are matched with a vetted consultant lawyer who runs the matter through the Lawhive platform — conveyancing, divorce and family, employment, immigration, landlord and tenant, and property.

Lawhive Ltd is not a law firm and does not itself give legal advice; regulated legal work is delivered by its network, including affiliate firm Lawhive Legal Ltd, authorised and regulated by the Solicitors Regulation Authority (SRA ID 8003766). Backed by Balderton Capital and GV.

- Website: https://lawhive.co.uk/
- Platform sign-in: https://platform.lawhive.co.uk/sign-in
- GitHub: https://github.com/Lawhive

## API surface

Lawhive publishes **no public developer API** — no API documentation, developer portal, OpenAPI, AsyncAPI, webhook catalog, MCP server, CLI, or sandbox. Its GitHub org holds hiring exercises and internal tooling, and its `@lawhive` npm scope holds code-style configs rather than API client SDKs.

Note for future enrichment runs: lawhive.co.uk is a Next.js app whose catch-all route returns HTTP **200 with the marketing HTML shell for any unmatched path**. Status codes alone are not a reliable existence test — compare the page title against the homepage. See `well-known/lawhive-well-known.yml`.

## Artifacts

| Artifact | File |
|---|---|
| Conformance (SRA / ICO / UK GDPR) | `conformance/lawhive-conformance.yml` |
| Domain security (probed) | `security/lawhive-domain-security.yml` |
| Packages (first-party npm) | `packages/lawhive-packages.yml` |
| Well-known probe results | `well-known/lawhive-well-known.yml` |
| llms.txt | `llms/lawhive-llms.txt` |
