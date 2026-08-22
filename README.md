# Lodgify (lodgify)

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

Lodgify is all-in-one vacation rental software for property owners and managers, providing a website builder, booking engine, channel manager, and property management system. The Lodgify Public API (v1 and v2) exposes a REST interface at https://api.lodgify.com for managing properties, availability, rates and quotes, bookings and reservations, guest messaging, and webhook subscriptions, authenticated with an X-ApiKey header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lodgify/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lodgify/refs/heads/main/apis.yml)

## Tags

- Vacation Rental
- Property Management
- Booking
- Channel Manager
- Travel

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Lodgify Properties API

Lists and retrieves vacation rental properties and their room types, including property details, per-property availability, statistics, and deleted properties.

- **Human URL:** [https://docs.lodgify.com/reference](https://docs.lodgify.com/reference)
- **Base URL:** `https://api.lodgify.com/v2`

#### Tags

- Properties
- Rooms
- Listings

#### Properties

- [Documentation](https://docs.lodgify.com/reference)
- [API Reference](https://docs.lodgify.com/reference/getallpropertiesasync)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lodgify Rates & Availability API

Reads the daily rates calendar and rate settings, creates and updates rates, and queries availability for users, properties, and room types for syncing and availability checks against connected channels.

- **Human URL:** [https://docs.lodgify.com/reference/ratescalendar](https://docs.lodgify.com/reference/ratescalendar)
- **Base URL:** `https://api.lodgify.com/v2`

#### Tags

- Rates
- Pricing
- Availability
- Calendar

#### Properties

- [Documentation](https://docs.lodgify.com/reference/ratescalendar)
- [API Reference](https://docs.lodgify.com/reference/ratescalendar)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lodgify Bookings & Reservations API

Full lifecycle management of bookings and reservations - create, read, update, and delete bookings, generate payment links, set key codes, list external bookings, and perform check-in and check-out.

- **Human URL:** [https://docs.lodgify.com/reference](https://docs.lodgify.com/reference)
- **Base URL:** `https://api.lodgify.com/v2`

#### Tags

- Bookings
- Reservations
- Payments

#### Properties

- [Documentation](https://docs.lodgify.com/reference)
- [API Reference](https://docs.lodgify.com/reference)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lodgify Quotes API

Generates a priced quote for a property given dates and guest counts, returning the breakdown of rates, fees, and taxes used to drive bookings and payment links.

- **Human URL:** [https://docs.lodgify.com/reference](https://docs.lodgify.com/reference)
- **Base URL:** `https://api.lodgify.com/v2`

#### Tags

- Quotes
- Pricing
- Stays

#### Properties

- [Documentation](https://docs.lodgify.com/reference)
- [API Reference](https://docs.lodgify.com/reference)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lodgify Messaging API

Retrieves a guest messaging thread by its thread GUID (found in booking data) to read the conversation between host and guest.

- **Human URL:** [https://docs.lodgify.com/reference/get_v2-messaging-threadguid](https://docs.lodgify.com/reference/get_v2-messaging-threadguid)
- **Base URL:** `https://api.lodgify.com/v2`

#### Tags

- Messaging
- Threads
- Guest Communication

#### Properties

- [Documentation](https://docs.lodgify.com/reference/get_v2-messaging-threadguid)
- [API Reference](https://docs.lodgify.com/reference/get_v2-messaging-threadguid)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lodgify Webhooks API

Subscribes and unsubscribes target URLs to platform events (such as booking and rate changes) and lists active webhook subscriptions for real-time notifications.

- **Human URL:** [https://docs.lodgify.com/reference/webhooks](https://docs.lodgify.com/reference/webhooks)
- **Base URL:** `https://api.lodgify.com/webhooks/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.lodgify.com/reference/webhooks)
- [API Reference](https://docs.lodgify.com/reference/post_webhooks-v1-subscribe)
- [OpenAPI](openapi/lodgify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lodgify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lodgify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lodgify)
- [LinkedIn](https://www.linkedin.com/company/lodgify)
- [Website](https://www.lodgify.com)
- [Documentation](https://docs.lodgify.com)
- [Plans](plans/lodgify-plans-pricing.yml)
- [Rate Limits](rate-limits/lodgify-rate-limits.yml)
- [Fin Ops](finops/lodgify-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
