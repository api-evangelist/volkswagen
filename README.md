# Volkswagen (volkswagen)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Volkswagen is a German automotive company and the parent of the VW Group, manufacturing vehicles under brands including Volkswagen, Audi, SEAT, Skoda, CUPRA, Porsche, Lamborghini, and Bentley. The OKAPI (Open Konfigurator API) provides programmatic access to VW AG product data for vehicle catalog browsing, interactive configuration, buildability validation, WLTP emissions data, configuration images, and order/pricing information across global markets.

**APIs.json:** [https://productdata.volkswagenag.com/](https://productdata.volkswagenag.com/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automobiles
- Cars
- Vehicles
- Automotive
- Vehicle Configuration

## Timestamps

- **Created:** 2025-02-25
- **Modified:** 2026-05-19

## APIs

### Volkswagen OKAPI - Open Konfigurator API

The VW OKAPI API provides access to Volkswagen AG product data and vehicle configuration services across global markets. Catalog endpoints (GET) browse countries, brands, models, types, and options. Operation endpoints (POST) handle buildability checking, configuration recovery, interactive configuration, resolution, WLTP emissions data, vehicle images, and order information with pricing.

- **Human URL:** [https://productdata.volkswagenag.com/](https://productdata.volkswagenag.com/)
- **Base URL:** `https://productdata.volkswagenag.com/v3`

#### Tags

- Automobiles
- Vehicle Configuration
- Konfigurator
- Product Data

#### Properties

- [Documentation](https://productdata.volkswagenag.com/swagger-doc.html)
- [Getting Started](https://productdata.volkswagenag.com/tutorial.html)
- [OpenAPI](openapi/volkswagen-okapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/volkswagen-okapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/volkswagen-okapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/volkswagen-vehicle-config-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [GitHub Organization](https://github.com/volkswagen)
- [LinkedIn](https://www.linkedin.com/company/volkswagen)
- [Whats New](https://productdata.volkswagenag.com/whats-new.html)
- [Guide](https://productdata.volkswagenag.com/introduction.html)
- [Support](https://productdata.volkswagenag.com/support.html)
- [Terms of Service](https://productdata.volkswagenag.com/condition-of-use.html)
- [Portal](https://okapi-ddp.productdata.volkswagenag.com/dev-portal/)
- [OpenAPI](openapi/volkswagen-okapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/volkswagen-vehicle-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/volkswagen-vehicle-config-structure.json)
- [JSON-LD](json-ld/volkswagen-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/volkswagen-vocabulary.yml)
- [Spectral Rules](rules/volkswagen-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
