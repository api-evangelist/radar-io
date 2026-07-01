# Radar (radar-io)

Radar is a geofencing and maps platform that gives developers a unified location infrastructure - forward and reverse geocoding, IP geocoding, address and place autocomplete, place and geofence search, routing (distance, matrix, directions, and route matching), geofence management, device tracking, events, trips, address verification, and map tiles - all under a single api.radar.io/v1 REST interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/radar-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/radar-io/refs/heads/main/apis.yml)

## Tags

- Location
- Geocoding
- Geofencing
- Maps
- Routing

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Radar Geocoding API

Forward geocoding (address to coordinates), reverse geocoding (coordinates to address), and IP geocoding (IP to city/state/country) over api.radar.io/v1/geocode.

- **Human URL:** [https://radar.com/documentation/api#geocoding](https://radar.com/documentation/api#geocoding)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Geocoding
- Reverse Geocoding
- IP Geocoding

#### Properties

- [Documentation](https://radar.com/documentation/api#geocoding)
- [API Reference](https://radar.com/documentation/api#forward-geocode)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Search & Autocomplete API

Address and place autocomplete, place search by chain/category near a location, and geofence search over api.radar.io/v1/search.

- **Human URL:** [https://radar.com/documentation/api#search](https://radar.com/documentation/api#search)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Autocomplete
- Search
- Places

#### Properties

- [Documentation](https://radar.com/documentation/api#search)
- [API Reference](https://radar.com/documentation/api#autocomplete)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Routing, Distance & Matrix API

Travel distance and duration, distance matrix across multiple origins and destinations, turn-by-turn directions, and GPS trace-to-road matching over api.radar.io/v1/route.

- **Human URL:** [https://radar.com/documentation/api#routing](https://radar.com/documentation/api#routing)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Routing
- Distance
- Matrix
- Directions

#### Properties

- [Documentation](https://radar.com/documentation/api#routing)
- [API Reference](https://radar.com/documentation/api#distance)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Geofences API

Create, read, update, and delete circle, polygon, and isochrone geofences keyed by tag and external ID over api.radar.io/v1/geofences.

- **Human URL:** [https://radar.com/documentation/api#geofences](https://radar.com/documentation/api#geofences)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Geofences
- Geofencing
- CRUD

#### Properties

- [Documentation](https://radar.com/documentation/api#geofences)
- [API Reference](https://radar.com/documentation/api#list-geofences)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Track & Users API

Server-side device tracking that generates geofence and place events, plus user (device) listing, retrieval, and deletion over api.radar.io/v1/track and /users.

- **Human URL:** [https://radar.com/documentation/api#track](https://radar.com/documentation/api#track)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Tracking
- Users
- Devices

#### Properties

- [Documentation](https://radar.com/documentation/api#track)
- [API Reference](https://radar.com/documentation/api#users)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Events API

List and retrieve geofence, place, and trip events (entered/exited, approaching, arrived) generated by tracking over api.radar.io/v1/events.

- **Human URL:** [https://radar.com/documentation/api#events](https://radar.com/documentation/api#events)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Events
- Geofence Events
- Webhooks

#### Properties

- [Documentation](https://radar.com/documentation/api#events)
- [API Reference](https://radar.com/documentation/api#list-events)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Trips API

Create, update, list, and retrieve trips for trip tracking with destination geofences, ETAs, and approaching/arrived events over api.radar.io/v1/trips.

- **Human URL:** [https://radar.com/documentation/api#trips](https://radar.com/documentation/api#trips)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Trips
- Trip Tracking
- ETA

#### Properties

- [Documentation](https://radar.com/documentation/api#trips)
- [API Reference](https://radar.com/documentation/api#upsert-trip)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Address Verification API

Validate and standardize postal addresses, returning a verification status and standardized components over api.radar.io/v1/addresses/validate.

- **Human URL:** [https://radar.com/documentation/api#address-validation](https://radar.com/documentation/api#address-validation)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Address Verification
- Address Validation
- Standardization

#### Properties

- [Documentation](https://radar.com/documentation/api#address-validation)
- [API Reference](https://radar.com/documentation/api#validate-an-address)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Radar Maps & Tiles API

Raster and vector map tiles across Radar map styles (default, light, dark) served by z/x/y over api.radar.io/v1/maps/tiles.

- **Human URL:** [https://radar.com/documentation/maps](https://radar.com/documentation/maps)
- **Base URL:** `https://api.radar.io/v1`

#### Tags

- Maps
- Tiles
- Raster

#### Properties

- [Documentation](https://radar.com/documentation/maps)
- [API Reference](https://radar.com/documentation/maps/tiles)
- [OpenAPI](openapi/radar-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radar-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radar-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/radarlabs)
- [LinkedIn](https://www.linkedin.com/company/radarlabs)
- [Website](https://radar.com/)
- [Documentation](https://radar.com/documentation)
- [Plans](plans/radar-io-plans-pricing.yml)
- [Rate Limits](rate-limits/radar-io-rate-limits.yml)
- [Fin Ops](finops/radar-io-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
