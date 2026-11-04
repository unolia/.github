<p align="center">
  <a href="https://unolia.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png">
      <img src="logo-light.png" alt="Unolia" width="280">
    </picture>
  </a>
</p>

<h3 align="center">You manage too many websites to keep working like this.</h3>

<p align="center">
  <a href="https://unolia.com">Website</a> ·
  <a href="https://unolia.com/docs/general/getting-started">Docs</a> ·
  <a href="https://unolia.com/docs/api-reference">API</a> ·
  <a href="https://unolia.com/blog/changelog">Changelog</a> ·
  <a href="https://unolia.com/pricing">Pricing</a>
</p>

---

Unolia groups every client project with everything it runs on: domains, DNS, websites, servers,
repositories, deployments, monitoring, email senders and costs, plus the issues worth fixing. Your
team reads one project view instead of opening ten provider dashboards.

It started inside a web agency that maintains more than 200 sites across many hosts and
registrars. Most of what you find here is what we needed to keep that running.

### Open source

**[unolia-cli](https://github.com/unolia/unolia-cli)** is the command line for Unolia. Deploy a site
and follow it, edit DNS and watch it propagate, list what is broken and what can be fixed. At a
terminal it prompts and draws tables; in a pipe, in CI or in an agent it never prompts, answers JSON
and exits with a code that says what happened.

```bash
composer global require unolia/unolia-cli
unolia login
unolia issue list --fixable
```

### Providers

Cloudflare, Amazon Route 53, OVH, Gandi, GoDaddy, IONOS, Namecheap, Porkbun, bunny.net,
DigitalOcean, Vultr, Laravel Forge, Laravel Cloud, Ploi, GitHub, GitLab, Oh Dear, Mailgun, Bento
and endoflife.date. [See them all](https://unolia.com/docs/providers).

### AI agents

Connect Claude, ChatGPT, Cursor or any MCP client to your team through the
[Unolia MCP server](https://unolia.com/docs/agent-mcp). Agents get project briefs, environment maps,
costs, incidents and DNS audits, without a single provider credential in the prompt.

---

<p align="center">
  Questions? <a href="mailto:support@unolia.com">support@unolia.com</a>
</p>
