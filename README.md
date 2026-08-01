# Axiom Space

Axiom Space, Inc. is a privately funded American space infrastructure developer headquartered in Houston, Texas, founded in 2016 by Kam Ghaffarian and former NASA ISS Program Manager Michael Suffredini. It is building Axiom Station — the world's first commercial space station and planned successor to the ISS — has flown private astronaut missions Ax-1 through Ax-4 to the ISS, and develops the Axiom Extravehicular Mobility Unit (AxEMU) spacesuit for NASA's return to the lunar surface. Commercial lines include human spaceflight, microgravity research, in-space manufacturing, and Orbital Data Centers (in-orbit cloud compute).

- https://www.axiomspace.com/

## API surface

**None.** As of 2026-07-31 the API Evangelist contract-discovery pass found no OpenAPI/Swagger,
no GraphQL endpoint, no MCP server, no A2A agent card, no AsyncAPI or webhook catalog, no
SDKs or client packages, no CLI, no sandbox, and no developer portal, docs host, or API
reference. `api.axiomspace.com`, `developer.axiomspace.com` and `docs.axiomspace.com` do not
resolve in DNS, and every `/.well-known/` discovery path on the corporate site returns 404.
All offerings — including the Orbital Data Center product — are sold through direct
enterprise, agency, and government engagement.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `apis.yml` | APIs.json profile | searched |
| `security/axiom-space-domain-security.yml` | DomainSecurity | probed |
| `well-known/axiom-space-well-known.yml` | well-known probe index (all negative) | probed |
| `llms/axiom-space-llms.txt` | LLMsTxt | generated |

Secondary-market listing (harvest source): https://forgeglobal.com/axiom-space_stock/
