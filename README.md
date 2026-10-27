> **Maintained fork.** The original [jcgoette/weight_gurus_homeassistant](https://github.com/jcgoette/weight_gurus_homeassistant) was archived in March 2026. I use this integration every day with an AccuCheck Verve 0412 scale and plan to keep it working with current Home Assistant releases. Issues and pull requests are welcome here.
>
> If you have the Bluetooth Weight Gurus 0376 scale, the original author's recommendation of [openScale](https://github.com/oliexdev/openScale) with [openScale-sync](https://github.com/oliexdev/openScale-sync) (local, no cloud) may suit you better. Wi-Fi models such as the 0412 sync only to the Weight Gurus cloud, which is what this integration reads.

# weight_gurus_homeassistant

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://hacs.xyz/docs/faq/custom_repositories/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)

This custom integration provides sensors for Weight Gurus API endpoints within [Home Assistant](https://github.com/home-assistant/core). Thanks to [@MarkWalters-pw](https://github.com/MarkWalters-pw) for the [heavy lifting of API documentation](https://gist.github.com/MarkWalters-pw/08ea0e8737e3e4d11f70427ef8fdc7df).

## Installation

### HACS (custom repository)

1. In HACS, open the three-dot menu and choose "Custom repositories".
1. Add `https://github.com/david-cd/weight_gurus_homeassistant` with type "Integration".
1. Search for "Weight Gurus" in HACS and click "Download".
1. Restart Home Assistant.

Switching from the archived original: remove the old repository from HACS, add this one, download, and restart. The integration domain is unchanged, so existing config entries and sensors carry over.

## Configuration

1. Go to "Configuration".
1. Click the "Integrations" button.
1. Click on the "ADD INTEGRATION" in the bottom right corner.
1. Search for "Weight Gurus".
1. Enter email and password and click "Submit".
