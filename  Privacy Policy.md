# Privacy Policy

**Last updated:** 11 October 2026

## 1. Introduction

This Privacy Policy describes how the Pinterest MCP Server (the "App", "we", "us") collects, uses, and protects information when you use our application to interact with Pinterest.

The App is a local Model Context Protocol (MCP) server that allows AI agents to create boards and publish pins on Pinterest on your behalf. We are committed to protecting your privacy and handling your data transparently.

## 2. Information We Collect

The App interacts with the Pinterest API to perform actions you request, such as:

- Creating boards (`create_board`, `bulk_create_pins`)
- Publishing pins (`create_pin`)
- Searching pins (`search_pins`)
- Listing boards (`list_boards`)
- Getting suggested keywords (`get_suggested_keywords`)

To perform these actions, the App may process:

- **Pinterest account identifiers** (user ID, username) returned by the Pinterest API.
- **Board and pin data** (titles, descriptions, images, URLs) that you explicitly provide or request.
- **Access tokens** issued by Pinterest after you authorize the App.

We do **not** collect, store, or transmit any of this data to our own servers. All data remains on your local machine or is sent directly to the Pinterest API.

## 3. How We Use Information

The information processed by the App is used solely to:

- Execute the actions you request through the MCP interface.
- Authenticate with the Pinterest API using OAuth 2.0.
- Display results back to you within your AI agent or local environment.

We do not use your data for advertising, profiling, or any other purpose.

## 4. Data Storage and Security

- **Access tokens** are stored locally on your device in a configuration file or environment variable. You are responsible for keeping this file secure.
- **No data is stored on external servers.** The App runs entirely on your local machine.
- We recommend using environment variables or a secure secret manager to store your Pinterest API credentials.

## 5. Third-Party Services

The App communicates with the **Pinterest API** (https://api.pinterest.com). Your use of Pinterest is governed by Pinterest's own Terms of Service and Privacy Policy. We encourage you to review them:

- Pinterest Terms of Service: https://policy.pinterest.com/en/terms-of-service
- Pinterest Privacy Policy: https://policy.pinterest.com/en/privacy-policy

We are not affiliated with Pinterest, Inc.

## 6. Your Rights

Since the App does not store your data on external servers, you have full control over your information at all times. You can:

- Revoke the App's access to your Pinterest account at any time via your Pinterest account settings.
- Delete any locally stored tokens or configuration files.
- Stop using the App at any time.

## 7. Children's Privacy

The App is not intended for use by children under the age of 13. We do not knowingly collect personal information from children.

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted in this repository with an updated "Last updated" date.

## 9. Contact

If you have any questions about this Privacy Policy, please contact:

**Email:** a326nv@gmail.com
**GitHub:** https://github.com/a326nv/aionui-downloader

---

*This App is an independent project and is not affiliated with, endorsed by, or sponsored by Pinterest, Inc.*