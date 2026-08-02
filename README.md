# 4DReplay

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
