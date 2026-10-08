<p align="center">
  <img src="assets/logo.svg" alt="G2X" width="72" height="72">
</p>

<h1 align="center">GovCon for Cursor</h1>

<p align="center">Research federal opportunities, companies, and markets in your editor.</p>

<p align="center">
  <a href="https://g2x.com/docs/connect">Connection guide</a> ·
  <a href="https://g2x.com/pricing">Plans</a> ·
  <a href="https://govcon.sh">CLI</a>
</p>

---

Connect Cursor to **GovCon MCP** and add a skill for finding and using the tools available to your G2X account.

## Start with a question

- “Find federal opportunities for cybersecurity services.”
- “Research a company and link to its records.”
- “Summarize the results and cite the sources.”

Sign in with your G2X account. Available tools and data depend on your plan and permissions.

## Connect

The plugin connects to `https://mcp.g2x.com/mcp`. Sign in through the OAuth flow in Cursor; no client ID, client secret, or API key is needed. See the [connection guide](https://g2x.com/docs/connect) for setup and [support](https://g2x.com/support) for help.

<details>
<summary><strong>Install from this repository</strong></summary>

1. Copy the plugin files into `~/.cursor/plugins/local/g2x/`.
2. Restart Cursor or run **Developer: Reload Window**.
3. In **Customize**, find the `govcon-mcp` skill and **G2X** MCP server, then complete sign-in.
4. Confirm that tools are listed and try a research question.

Your organization must allow local plugins.

</details>

## Prefer the terminal?

The [GovCon CLI](https://govcon.sh) provides terminal access to G2X. Once installed, run `govcon login` to sign in and `govcon --help` for commands. The skill can use it when you request terminal access. Install the CLI separately.

## License

The files distributed in this plugin are licensed under MIT; see [LICENSE](LICENSE). This repository contains the client configuration and usage guidance for the hosted G2X service.
