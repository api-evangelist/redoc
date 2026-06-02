---
title: '@redocly/portal-plugin-mock-server 0.18.0'
url: https://redocly.com/docs/realm/changelog#%40redocly%2Fportal-plugin-mock-server%400.18.0
date: '2026-05-14'
author: ''
feed_url: https://redocly.com/docs/changelog/feed.xml
---
New release: @redocly/portal-plugin-mock-server@0.18.0 · Date: 2026-05-14 · 6 features · 12 fixes

Features:
• Updated the icon displayed alongside hyperlinks in the project.
• Improved visibility and accessibility of Markdown links by adding an underline.
• Updated styles for page navigation buttons.
• Added support for callback URLs in `developerOnboarding`.
• Added `hreflang` alternate links for translated pages.
• Improved language picker accessibility by converting menu options to links.

Fixes:
• Fixed an issue in OpenAPI docs route resolution where lines not tied to an operation generated incorrect URLs by duplicating the base slug.
• Fixed an issue where selected request body examples were not properly synchronized between Redoc and the **Try it** overlay.
• Updated `@redocly/openapi-core` to version `2.30.5`.
• Fixed an issue in Replay where stale credentials persisted in the active environment across page reloads, and caused intermittent "JWT is expired" errors.
• Fixed an issue in Replay where the request body with invalid JSON input grew after restarts, leading to decreased performance.
• Fixed rendering of non-Latin characters by enforcing UTF-8 encoding.
• Fixed 404 error when opening login from locale-prefixed URLs.
• Fixed an issue where closing the search dialog modal locked page scrolling.
• Excluded buttons and links from heading content to improve accessibility.
• Fixed an issue where MCP connect actions were hidden for OpenAPI pages excluded from search (`openapi.excludeFromSearch`).
• Fixed an issue where the tooltips in API docs and Replay might partially render outside the viewport.
• Fixed an issue where navigating on a code walkthrough page prevented automatic scrolling to the active step.
