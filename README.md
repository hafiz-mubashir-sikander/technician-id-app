# Technician ID

<p align="center"><img src="assets/app-logo.png" width="110" alt="Technician ID showcase logo"></p>

<p align="center"><strong>Technician ID — Client Mobile Application</strong><br>Offline-first technician workflows, built with Flutter.</p>

> **Company Project · VirtueNetz · Delivered to Client · Source Code Private**

## Overview

**Technician ID** is a client mobile application delivered through **VirtueNetz**. The app was delivered directly to the client and **was not published on Google Play or the Apple App Store because public distribution was not requested**.

This is a **documentation-only project showcase**, not the production repository or an open-source release.

## My Contribution

I independently owned the **Flutter mobile frontend**, including user interface implementation, frontend workflows, offline-first behavior, local persistence, application state, and integration of REST APIs supplied by the backend development team.

**Responsibility split:**

| Area | Ownership |
|---|---|
| Flutter UI and frontend workflows | My implementation |
| Offline-first behavior and local storage | My implementation |
| Client-side state, validation and error handling | My implementation |
| REST API consumption and data mapping | My implementation |
| Backend APIs and server implementation | Backend development team |
| Delivery | Completed for the client through VirtueNetz |

## Engineering Highlights

### Offline-first experience

- Designed mobile workflows to remain useful with locally available information during connectivity interruptions.
- Implemented local persistence and application-state handling.
- Integrated local and remote data flows to support reconnection and synchronization scenarios.
- Addressed loading, failure, and recovery states on the frontend.

### REST API integration

- Integrated backend-team-provided REST endpoints into Flutter screens and workflows.
- Handled API requests, response mapping, application state updates, and network errors.
- Connected remote services to locally managed application data.

### Mobile frontend

- Built screens, reusable interface components, forms, and user interactions.
- Implemented navigation, validation, and device-side behavior required by the application.
- Prepared and refined the client-facing mobile experience for delivery.

## Technology Overview

**Flutter · Dart · REST APIs · Offline-first architecture · Local storage · Mobile state management**

Specific internal dependencies, API contracts, storage schemas, and deployment configuration are intentionally not disclosed.

## Architecture at a Glance

```text
           Technician ID — Flutter App
                       |
        +--------------+--------------+
        |              |              |
     UI / UX       App State      Local Storage
        |              |              |
        +--------------+--------------+
                       |
              REST API Integration
                       |
             Backend Team APIs
```

The diagram is conceptual and does not disclose production infrastructure. See [Architecture](docs/ARCHITECTURE.md).

## Application Screenshots

Approved screenshots of the delivered application will be added to [`screenshots/`](screenshots/).

Only publicly approved screenshots without personal, client-confidential, or operational data should be included.

## Delivery Status

**Completed and delivered to the client.** No public app-store listing was required, so there are no Play Store or App Store links.

## Documentation

- [Project overview](docs/PROJECT.md)
- [High-level architecture](docs/ARCHITECTURE.md)
- [Showcase changelog](CHANGELOG.md)
- [Security and confidentiality](SECURITY.md)
- [Ownership and usage notice](NOTICE.md)

## Repository Scope

This repository includes public-facing documentation and a **temporary showcase logo placeholder**. The original client branding should be used only with permission.

**Not included:** production Flutter source code, backend implementation, private endpoints, credentials, signing assets, client records, configuration secrets, or internal company documentation.

---

**Project:** Technician ID  
**Company:** VirtueNetz  
**Role:** Flutter Developer — independent mobile frontend implementation  
**Delivery:** Completed · Client delivery · Not publicly listed
