[![Commanders Act Logo](/Screenshots/CommandersAct.png)](https://www.commandersact.com/)
# Commanders Act | Server-side events (sGTM)
## Overview
This is a Google Tag Manager (GTM) **server-side** tag template using [Commanders Act](https://www.commandersact.com/) [reference specifications](https://doc.commandersact.com/developers/tracking-and-integrations/tracking/events-reference). It converts the events received by a GTM server container (usually through the GA4 client) to the Commanders Act event format and sends them to PlatformX through the HTTP tracking API.

For a web container, use the [Commanders Act | Serverside events bridge](https://github.com/CommandersAct/Serverside-events-bridge) template instead.

The full documentation is available here: [Google Tag Manager (sGTM) setup guide](https://doc.commandersact.com/features/sources/sources-catalog/server/http-tracking-api/google-tag-manager-sgtm).

> **Status:** beta (0.9.1-beta). Publication in the Google Community Template Gallery is planned after the beta.

## Permissions
The template can send HTTP requests to any URL because the collection domain is configurable (first-party collection). You can restrict this permission to your own collection domain.

## License
See the LICENSE file for details.