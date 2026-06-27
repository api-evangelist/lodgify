# Lodgify (lodgify)

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
