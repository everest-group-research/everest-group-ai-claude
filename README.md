# Everest Group AI for Claude

Everest Group AI brings Everest Group's research library into Claude as one plugin. It combines the secure Everest Group MCP connector with instructions that keep responses grounded in the research returned for the signed-in user.

## What is included

- Entitlement-aware research search and answers
- Recent, topical, and author-based publication discovery
- Upcoming research discovery where the user's membership permits it
- Analyst-style instructions for scope, grounding, tone, and research planning

## Authentication

The plugin connects to `https://mcp.everestgrp.com/mcp`. Claude will ask the user to sign in with their Everest Group account when the connector is first used. Access to research is determined by that account's membership and permissions.

## What the plugin sends

The plugin contains no code that runs on your device. When you ask an Everest Group research question, Claude sends your question and relevant context from the conversation to the Everest Group MCP server at `https://mcp.everestgrp.com/mcp` to retrieve research. Your sign-in establishes your identity so the server can apply your membership entitlements. The plugin sends data to no other destination.

## Data and support

- [Everest Group privacy notice](https://www.everestgrp.com/privacy-notice/)
- [Everest Group terms of use](https://www.everestgrp.com/terms-of-use/)
- [Contact Everest Group](https://www.everestgrp.com/contact-us/)

Everest Group AI does not bypass membership restrictions. If a source is not available to the signed-in user, Claude must not claim or reconstruct access to it.
