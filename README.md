# Umbrella issues

Bug reports, feature requests and questions for **Umbrella**, one MCP server for your Umbraco 17 site.

| Package | Where it runs |
|---|---|
| [`Umbraco.Community.Umbrella`](https://www.nuget.org/packages/Umbraco.Community.Umbrella) (NuGet) | In your Umbraco site: product detection, the **MCP** health checks and the **Umbrella** dashboard |
| [`umbrella-mcp`](https://www.npmjs.com/package/umbrella-mcp) (npm) | On your machine, started by your AI tool with `npx` |

This repository holds no code; it is only the public issue tracker. Setup and configuration are in the [NuGet package's readme](https://www.nuget.org/packages/Umbraco.Community.Umbrella).

## Reporting a problem

1. Run `get-mcp-health` in your AI tool, and look at Settings → **Umbrella** → **Overview** and the **MCP** health checks in the backoffice. They explain most problems.
2. Search the [open and closed issues](https://github.com/MarcusK00/Umbrella-Issues/issues?q=is%3Aissue) first.
3. [Open an issue](https://github.com/MarcusK00/Umbrella-Issues/issues/new/choose) and pick a form. Include the add-on and `umbrella-mcp` versions and the `get-mcp-health` output.

Issues are public. Before you post, remove client secrets, API keys, site URLs you don't want public, and any personal data (names, emails, member or form entry data).

**Security vulnerabilities:** don't open an issue. Report them privately, see [SECURITY.md](SECURITY.md).

## Labels

| Label | Meaning |
|---|---|
| `area: add-on` | The NuGet package: detection, capabilities endpoint, health checks |
| `area: dashboard` | The Umbrella dashboard in the backoffice (Overview, Tool Permissions) |
| `area: npm server` | `umbrella-mcp`: startup, filters, tool names, `get-mcp-health` |
| `product: cms`, `product: forms`, `product: automate`, `product: engage` | Tools of that product |
| `needs info` | Waiting for details from the reporter |

## Not an official Umbraco package

Umbrella is a community project, not an official Umbraco HQ package. Problems with Umbraco CMS, Forms, Automate or Engage themselves, or with their own MCP servers, belong in those products' channels. If you're not sure which it is, open an issue here and it will be passed on.
