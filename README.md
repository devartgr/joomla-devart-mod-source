# DevArt Source for Joomla

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![License](https://img.shields.io/badge/License-GPLv3-red)
![Version](https://img.shields.io/badge/Version-1.0.11-orange)

Lightweight Joomla 6 module for embedding trusted raw HTML, iframe, JavaScript and third-party source code directly inside module positions.

Designed for high-performance editorial, news and advanced Joomla websites using modern production workflows.

---

## Latest Release

**Version:** 1.0.11

### Highlights

- Joomla Extensions Directory compliance maintenance release
- Improved package and manifest compatibility
- Trusted administrator raw embed workflow
- iframe-only rendering mode
- GitHub-based Joomla update server
- PHP 8.2+ support
- Lightweight production-ready architecture

---

## Overview

DevArt Source is a lightweight Joomla module designed for trusted administrator use when raw source embedding is required.

It allows administrators to place trusted custom code directly in Joomla module positions without unnecessary frontend overhead.

Ideal for advanced integrations where normal content modules are too restrictive.

---

## Perfect For

- YouTube embeds
- Glomex players
- Google Ads
- Google Ad Manager
- Analytics snippets
- Third-party widgets
- iframe integrations
- Custom HTML blocks
- Tracking scripts
- Trusted JavaScript embeds
- External player integrations
- Advanced source code snippets

---

## Features

- Joomla 6 native module
- Trusted raw HTML rendering
- JavaScript embedding support
- iframe embedding support
- Optional iframe-only rendering mode
- Optional Joomla content plugin processing
- Lightweight frontend output
- Minimal performance overhead
- No unnecessary frontend libraries
- DevArt branded administrator interface
- Security guidance for administrators
- GitHub-based Joomla Update Server support
- GPL Open Source

---

## Use Cases

### Advertising

Embed:

- Google Ads
- Google Ad Manager
- affiliate widgets
- ad network scripts

---

### Media

Embed:

- YouTube
- Vimeo
- Glomex
- external players
- live stream widgets

---

### Analytics / Tracking

Insert trusted:

- analytics scripts
- conversion tracking
- remarketing tags
- custom measurement code

---

### Widgets

Embed:

- weather widgets
- stock widgets
- external feeds
- booking widgets
- custom HTML tools

---

## Installation

1. Download latest release ZIP
2. Open Joomla Administrator:

`System → Extensions → Install`

3. Upload:

`mod_devartsource_v1.0.11.zip`

4. Open:

`Content → Site Modules`

5. Create or edit:

`DevArt Source`

---

## Configuration

Main options include:

- Source Code
- Render Mode
- Optional content plugin preparation
- Joomla module assignment
- Access permissions
- Caching options

---

## Render Modes

### Raw Mode

Renders trusted administrator-provided code exactly as configured.

Suitable for:

- scripts
- widgets
- HTML blocks
- tracking code
- embeds

---

### iframe-only Mode

Extracts and renders iframe content only.

Useful when administrators want stricter embed behavior.

---

## Security Notes

DevArt Source is intentionally designed for **trusted administrator use only**.

This module renders administrator-configured source code exactly as provided.

Recommended only for trusted production environments where administrators intentionally embed:

- trusted scripts
- trusted widgets
- trusted iframe integrations
- trusted external code

This is not a frontend user content tool.

---

## Performance

Built for lightweight production use.

Features:

- minimal frontend overhead
- no CSS framework dependency
- no JavaScript framework dependency
- direct rendering workflow
- Joomla caching compatible
- CDN friendly
- Cloudflare friendly
- Gantry compatible
- RocketTheme compatible

---

## Requirements

- Joomla 6.x
- PHP 8.2+

---

## Joomla Native Updates

DevArt Source supports Joomla native updates via GitHub.

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-mod-source/main/update.xml`

After installation:

`System → Extensions → Update`

---

## Current Version

**1.0.11**

---

## Changelog 1.0.11

### Fixed

- Fixed Joomla Extensions Directory compliance metadata issues
- Fixed extension manifest naming for JED reserved naming rules
- Added missing author email metadata
- Added LICENSE.txt manifest reference

### Improved

- Improved XML manifest compatibility
- Improved release package consistency
- Retained Joomla native update compatibility

---

## Compatibility

Supported:

- Joomla 6.x
- PHP 8.2+
- Gantry
- RocketTheme
- CDN deployments
- Cloudflare environments

Not supported:

- Joomla 3
- Joomla 4
- Joomla 5
- legacy PHP versions

---

## Developer

**Stathopoulos Kostas – DevArt**  
https://devart.gr

GitHub Repository:

https://github.com/devartgr/joomla-devart-mod-source

---

## License

GNU General Public License v3 or later

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be held liable for any damages, data loss, downtime, security issues, or other problems resulting from the use or misuse of this software.

Users are responsible for testing the software in their own environment and maintaining proper backups before installation or upgrades.

Always test on a staging environment before using in production.
```
