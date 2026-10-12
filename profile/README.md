<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://assets.botyard.io/logos/lockup/botyard-lockup-on-dark.svg">
  <img src="https://assets.botyard.io/logos/lockup/botyard-lockup-on-light.svg" alt="Botyard" height="48">
</picture>

### AI agents that belong to your company

[Website](https://botyard.io) · [Docs](https://docs.botyard.io) · [LinkedIn](https://www.linkedin.com/company/botyard)

</div>

---

Botyard is a platform for AI agents that belong to your company, not one employee's laptop. Each agent's memory, tools and credentials are owned and governed by the organization. Your team shares the same agent; it runs on schedules, hands decisions to the right person, and ships its work as live internal apps.

- **[Shared conversations](https://botyard.io/features/shared-conversations):** share an agent session with your team. Teammates work in the same agent thread with the same context, and every message shows who sent it.
- **[Runtime Vault](https://botyard.io/features/runtime-vault):** a credential vault for AI agents. Secrets are issued as short-lived, audited leases at runtime, so they never need to be pasted into chat.
- **[Governed MCP tools](https://botyard.io/features/mcp-security):** per-agent MCP permissions and credential management, with approvals and an audit trail.
- **[Workforces](https://botyard.io/features/workforces):** agents and people work from the same task board, with human review built into the workflow.
- **[Bot Pages](https://botyard.io/features/bot-pages):** agents publish their work as authenticated internal apps.

## Terraform

Manage Botyard as code with the official Terraform provider, published on the Terraform Registry as [`Botyard-AI/botyard`](https://registry.terraform.io/providers/Botyard-AI/botyard/latest). You can declare bots, skills, MCP servers, Runtime Vault secrets, and the tool, skill and credential assignments for each bot. Review them in a PR like any other infrastructure.

```hcl
terraform {
  required_providers {
    botyard = {
      source = "Botyard-AI/botyard"
    }
  }
}
```

- [Provider source code](https://github.com/Botyard-AI/terraform-provider-botyard)
- [Manage Botyard with Terraform](https://docs.botyard.io/docs/terraform) (guide)

The provider is early and in active development. New resources are added incrementally.

## Open source

Today, most of Botyard is a hosted platform. As the platform becomes more extensible, we want more of it to happen in the open: integrations, skills, tooling, and the provider above. Our aim is to grow our open-source contribution over time and build it together with the people who use it.

Issues and pull requests on our public repositories are welcome.

## Get started

- [Getting started guide](https://docs.botyard.io/docs/getting-started)
- [Secrets for AI agents with the Runtime Vault](https://docs.botyard.io/docs/runtime-vault)
- [Try Botyard](https://botyard.io)
