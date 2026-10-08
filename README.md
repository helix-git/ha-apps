# Helix Home Assistant Apps

[![Add repository to Home Assistant](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fhelix-git%2Fha-apps)

Apps (add-ons) for Home Assistant. Each app brings its own integration and installs it by itself.
No HACS needed.

## Apps

| App | Description | Built on | Note | License | Version | Tests |
|---|---|---|---|---|---|---|
| [Leapmotor Gateway](https://github.com/helix-git/ha-leapmotor-gateway) | Connects Home Assistant to the Leapmotor cloud. Every remote command passes an allowlist. Critical commands need approval on your phone or are blocked. Trip computer and dashboard included. | [leapmotor-api](https://github.com/markoceri/leapmotor-api), [leapmotor-ha](https://github.com/kerniger/leapmotor-ha) | Not affiliated with Leapmotor. Uses an undocumented cloud interface that may change at any time. Remote commands act on a real car. | [![AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-blue)](https://github.com/helix-git/ha-leapmotor-gateway/blob/main/LICENSE) | ![Version](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhelix-git%2Fha-leapmotor-gateway%2Fmain%2Faddon%2Fconfig.yaml&query=%24.version&label=version) ![aarch64](https://img.shields.io/badge/aarch64-yes-green) ![amd64](https://img.shields.io/badge/amd64-yes-green) | [![Tests](https://github.com/helix-git/ha-leapmotor-gateway/actions/workflows/tests.yml/badge.svg)](https://github.com/helix-git/ha-leapmotor-gateway/actions/workflows/tests.yml) |

## Installation

1. Use the button above, or open **Settings > Apps > App store**, menu **Repositories**, and add
   `https://github.com/helix-git/ha-apps`.
2. Install the app you want and follow its documentation.
3. Restart Home Assistant once when the app asks for it, so its integration is loaded.

## Disclaimer

Hobby projects, provided as is, without warranty. Support on a best effort basis. Use at your own
risk. Notes for each app are in the table above and in its documentation.

These projects were developed with AI assistance.
