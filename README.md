# Lawhive

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
