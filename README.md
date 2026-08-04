# what3words (what3words)

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

what3words has divided the world into a grid of three-metre squares and given each one a unique three-word address (e.g. ///filled.count.soap). The what3words Public API converts between three-word addresses and latitude / longitude coordinates, offers an AutoSuggest with autocorrect for voice/typing input, exposes supported languages and locale variants, and returns grid sections as GeoJSON. The API is HTTPS GET only, authenticated by API key in a query parameter or X-Api-Key header, and is wrapped by official SDKs for Swift, Android, Java, JavaScript, Python, PHP, and .NET, plus UI components for map and OCR experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/what3words/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/what3words/refs/heads/main/apis.yml)

## Tags

- Geocoding
- Addressing
- Location
- Three Word Address
- Maps

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### what3words Public API

REST API for converting between three-word addresses and latitude / longitude coordinates, with AutoSuggest, available-languages, and grid-section endpoints. JSON or GeoJSON response formats. Authenticated via the X-Api-Key header or a key query parameter.

- **Human URL:** [https://developer.what3words.com/public-api/docs](https://developer.what3words.com/public-api/docs)
- **Base URL:** `https://api.what3words.com/v3`

#### Tags

- REST API
- Geocoding
- Addressing

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs)
- [Repository](https://github.com/what3words/what3words-api-docs)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words convert-to-3wa Endpoint

Converts a latitude / longitude coordinate into a three-word address in a chosen language.

- **Human URL:** [https://developer.what3words.com/public-api/docs#convert-to-3wa](https://developer.what3words.com/public-api/docs#convert-to-3wa)
- **Base URL:** `https://api.what3words.com/v3/convert-to-3wa`

#### Tags

- Reverse Geocoding
- Endpoint

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs#convert-to-3wa)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words convert-to-coordinates Endpoint

Converts a three-word address into a latitude / longitude coordinate and a bounding square.

- **Human URL:** [https://developer.what3words.com/public-api/docs#convert-to-coordinates](https://developer.what3words.com/public-api/docs#convert-to-coordinates)
- **Base URL:** `https://api.what3words.com/v3/convert-to-coordinates`

#### Tags

- Forward Geocoding
- Endpoint

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs#convert-to-coordinates)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words AutoSuggest Endpoint

Validates and autocorrects partial or imperfect three-word input, returning ranked suggestions. Supports focus, clipping by polygon, country, bounding box or circle, and voice-input modes.

- **Human URL:** [https://developer.what3words.com/public-api/docs#autosuggest](https://developer.what3words.com/public-api/docs#autosuggest)
- **Base URL:** `https://api.what3words.com/v3/autosuggest`

#### Tags

- AutoSuggest
- Endpoint
- Voice

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs#autosuggest)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words available-languages Endpoint

Returns all supported what3words languages and locale variants.

- **Human URL:** [https://developer.what3words.com/public-api/docs#available-languages](https://developer.what3words.com/public-api/docs#available-languages)
- **Base URL:** `https://api.what3words.com/v3/available-languages`

#### Tags

- Languages
- Endpoint

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs#available-languages)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words grid-section Endpoint

Returns the what3words three-metre grid for a specified bounding box as JSON or GeoJSON, suitable for map overlays.

- **Human URL:** [https://developer.what3words.com/public-api/docs#grid-section](https://developer.what3words.com/public-api/docs#grid-section)
- **Base URL:** `https://api.what3words.com/v3/grid-section`

#### Tags

- Grid
- GeoJSON
- Endpoint

#### Properties

- [Documentation](https://developer.what3words.com/public-api/docs#grid-section)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words JavaScript SDK

Official JavaScript wrapper around the what3words Public API for browser and Node.js applications.

- **Human URL:** [https://github.com/what3words/w3w-node-wrapper](https://github.com/what3words/w3w-node-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-node-wrapper`

#### Tags

- SDK
- JavaScript

#### Properties

- [Repository](https://github.com/what3words/w3w-node-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words Python SDK

Official Python wrapper around the what3words Public API.

- **Human URL:** [https://github.com/what3words/w3w-python-wrapper](https://github.com/what3words/w3w-python-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-python-wrapper`

#### Tags

- SDK
- Python

#### Properties

- [Repository](https://github.com/what3words/w3w-python-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words Java SDK

Official Java wrapper around the what3words Public API for server-side JVM applications.

- **Human URL:** [https://github.com/what3words/w3w-java-wrapper](https://github.com/what3words/w3w-java-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-java-wrapper`

#### Tags

- SDK
- Java

#### Properties

- [Repository](https://github.com/what3words/w3w-java-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words PHP SDK

Official PHP wrapper around the what3words Public API.

- **Human URL:** [https://github.com/what3words/w3w-php-wrapper](https://github.com/what3words/w3w-php-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-php-wrapper`

#### Tags

- SDK
- PHP

#### Properties

- [Repository](https://github.com/what3words/w3w-php-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words Swift SDK

Official Swift wrapper around the what3words Public API for iOS, iPadOS, and macOS applications.

- **Human URL:** [https://github.com/what3words/w3w-swift-wrapper](https://github.com/what3words/w3w-swift-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-swift-wrapper`

#### Tags

- SDK
- Swift
- iOS

#### Properties

- [Repository](https://github.com/what3words/w3w-swift-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words Android SDK

Official Android wrapper around the what3words Public API for native Android applications.

- **Human URL:** [https://github.com/what3words/w3w-android-wrapper](https://github.com/what3words/w3w-android-wrapper)
- **Base URL:** `https://github.com/what3words/w3w-android-wrapper`

#### Tags

- SDK
- Android

#### Properties

- [Repository](https://github.com/what3words/w3w-android-wrapper)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words Swift Map Components

UI components for embedding what3words grids, markers, and AutoSuggest experiences in Apple Maps-based iOS and iPadOS applications.

- **Human URL:** [https://github.com/what3words/w3w-swift-components](https://github.com/what3words/w3w-swift-components)
- **Base URL:** `https://github.com/what3words/w3w-swift-components`

#### Tags

- Components
- Swift
- Map

#### Properties

- [Repository](https://github.com/what3words/w3w-swift-components)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words OCR Camera Component

UI component that uses the device camera to scan three-word addresses from signage, packaging, or printed materials.

- **Human URL:** [https://github.com/what3words](https://github.com/what3words)
- **Base URL:** `https://github.com/what3words`

#### Tags

- OCR
- Camera
- Component

#### Properties

- [Repository](https://github.com/what3words)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### what3words API Docs and OpenAPI Repository

Public repository hosting the OpenAPI specification, LLM files, and reference material for the what3words Public API.

- **Human URL:** [https://github.com/what3words/what3words-api-docs](https://github.com/what3words/what3words-api-docs)
- **Base URL:** `https://github.com/what3words/what3words-api-docs`

#### Tags

- OpenAPI
- Documentation
- Open Source

#### Properties

- [Repository](https://github.com/what3words/what3words-api-docs)
- [Postman Collection](collections/what3words.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/what3words.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/what3words)
- [Website](https://what3words.com/)
- [Documentation](https://developer.what3words.com/public-api/docs)
- [Git Hub](https://github.com/what3words)
- [Plans](plans/what3words-plans-pricing.yml)
- [Rate Limits](rate-limits/what3words-rate-limits.yml)
- [Fin Ops](finops/what3words-finops.yml)
- [Integrations](https://what3words.com/business/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
