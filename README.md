# Lendorse

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

Lendorse GmbH is a Berlin-based education-finance company that funds international master's students studying in Europe through Income Share Agreements (ISAs) instead of traditional credit-scored loans. Students receive between EUR 3,000 and EUR 20,000 toward tuition, visa deposits, relocation and living costs, then repay a fixed 6-12% share of gross monthly income for 12 to 60 months once they earn above a EUR 2,500 monthly salary floor, with total repayment capped at 2.3x the funded amount.

No collateral, co-signer, parental guarantor or credit check is required. Lendorse also provides mentorship, CV review, mock interviews and industry introductions, and covers universities in Austria, Belgium, France (HEC, INSEAD), Germany, Italy, Spain (ESADE), Sweden (SSE) and Switzerland (HSG).

Backed by: techstars — https://lendorse.com/

## API surface

Lendorse publishes **no public API, SDKs, developer portal or machine-readable specifications** as of 2026-07-19. There is no `/.well-known/` discovery surface, no `api.`/`docs.` host, and no public GitHub organization. This repository is a company profile, not an API profile.

## Artifacts

- `apis.yml` — APIs.json 0.20 company profile
- `security/lendorse-domain-security.yml` — TLS/HSTS/DNSSEC/CAA/SPF/DMARC probe
- `well-known/lendorse-well-known.yml` — recorded `/.well-known/` probe results (all 404)
- `llms/lendorse-llms.txt` — agent-readable company summary
