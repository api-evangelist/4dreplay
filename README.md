# 4DReplay

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

4DReplay is a media technology company that builds multi-camera, time-slice ("bullet-time")
video capture and replay systems for live sports, entertainment and events. Arrays of roughly
50 to 120 synchronized cameras — locked to within 1/10,000 of a second — are processed in real
time to produce any-angle replay highlights within seconds of a play and deliver them to
broadcast, mobile and OTT audiences.

Founded in 2012 by Hongsu Jung; headquartered in San Mateo, California, with offices in Seoul
and Tokyo. Work has appeared with ESPN, NBC, CBS, FOX Sports, the NBA, MLB, NHL, the PGA
Championship and the Olympics.

## Products

- **4DReplay** — premium broadcast instant replay, frame-accurate multi-camera capture.
- **4DReplay+ / 4DLive** — broadcast replay with live speed/angle/tracking overlays and
  5G-based interactive multi-view live streaming.
- **4Dist** (<https://4dist.com/>) — browser-based interactive OTT platform with automated
  AI motion and swing analysis for academies, coaches and players.

## API status

As of 2026-08-02, 4DReplay publishes **no public developer API**. Probes of `4dreplay.com`,
`4dist.com`, `www.4dist.com` and `api.4dist.com` found no OpenAPI/Swagger, GraphQL, AsyncAPI,
MCP server, A2A agent card, `/.well-known/` document, SDK, CLI, Postman collection, developer
portal, sandbox, status page or changelog. Integration is a commercial/broadcast engagement
via <https://4dist.com/contact.html>.

`*.4dist.com` is a **wildcard host** — `api.4dist.com`, `status.4dist.com` and `mcp.4dist.com`
all return the 4Dist landing page and must not be recorded as an API host, status page or MCP
server.

4dist.com does serve a first-party JSON API under `/api/` that backs its own web app, but it is
`Disallow`'d in robots.txt, undocumented, and deliberately **not** registered as an API here.

## AI and crawler policy

4DReplay publishes a Cloudflare Content Signals Policy at <https://4dreplay.com/robots.txt> —
`Content-Signal: search=yes, ai-train=no, use=reference` — and disallows CCBot, ClaudeBot,
Google-Extended, GPTBot and meta-externalagent. Captured verbatim at
`well-known/4dreplay-content-signals-robots.txt`.

## Artifacts

| Path | What |
|---|---|
| `apis.yml` | APIs.json catalog record |
| `well-known/4dreplay-well-known.yml` | Full `/.well-known/` + spec-discovery probe record |
| `well-known/4dreplay-content-signals-robots.txt` | Verbatim robots.txt with the Content Signals Policy |
| `security/4dreplay-domain-security.yml` | TLS / HSTS / DNSSEC / CAA / SPF / DMARC probe |
| `conformance/4dreplay-conformance.yml` | Standards conformance, derived from probes |
| `llms/4dreplay-llms.txt` | Generated llms.txt (provider publishes none) |

- <https://4dreplay.com/>
- <https://4dist.com/>
- Secondary-market listing: <https://forgeglobal.com/4dreplay_stock/>
