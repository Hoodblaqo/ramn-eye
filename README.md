# RAMN'S EYE

Mobile-first public-data OSINT dashboard. Static site; no backend or sleeping server.

## Features
- IP geolocation and ASN metadata via ipwho.is
- DNS record lookups via Cloudflare DNS-over-HTTPS
- Domain registration metadata via RDAP
- Browser-side HTTPS connectivity checks
- Dark tactical map and mobile navigation
- PWA manifest and service worker for home-screen use

## Deploy
Enable GitHub Pages in repository Settings → Pages → Deploy from branch → main → /(root).

## Notes
Lookups are manual and limited to public technical metadata. IP geolocation is approximate and does not identify a person's exact address. The app does not scan ports, exploit systems, access accounts, or track devices. Third-party public APIs and map tiles have their own availability and privacy policies.
