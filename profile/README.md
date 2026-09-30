<div align="center">

# Unconnected

**Connecting the unconnected: satellite internet for communities that need it most.**

[Website](https://unconnected.org) · [Portal](https://portal.unconnected.org)

</div>

---

## About us

Unconnected.org brings high-speed satellite connectivity to schools, health centers, NGOs, local governments and community ISPs in places where traditional infrastructure doesn't reach.

We operate and support a fleet of Starlink terminals across multiple countries. The software in this organization is what makes that possible at scale.

## What we build

### connectHub: Unconnected Portal

A multi-tenant web platform for managing a Starlink terminal fleet. It gives Unconnected's operations team, partner organizations and end sites one place to work, each with access scoped to their own kits.

| Capability | What it does |
| --- | --- |
| **Kit management** | Inventory, status, lifecycle and configuration of terminals |
| **Activation flow** | Request, review and activate service lines with progress tracking and bulk activation |
| **Telemetry & maps** | Real-time health, historical charts and geographic view of the fleet |
| **Data usage & plans** | Usage against plan allowances, add-ons, top-ups and overage handling |
| **Alerts & tickets** | Fleet alerts with helpdesk ticket automation |
| **Billing & payments** | Payment status, auto-renew tracking and enforcement tooling |
| **Multi-tenancy & RBAC** | Three organization levels and six roles, enforced at the API layer |
| **Multilingual UI** | Spanish, English, French, Portuguese and Filipino |

### Programs supported by the platform

- **connectIMPACT** for community and social-impact deployments
- **connectEMERGENCY** for rapid-response connectivity
- **connectEXTENSION** for add-on capacity
- **connect4GOOD** for mission-driven partner connectivity

## Tech stack

| Layer | Technology |
| --- | --- |
| Monorepo | Turborepo + pnpm workspaces |
| Frontend | Next.js (App Router) · React · Tailwind CSS · TanStack Query · Zustand |
| Backend | NestJS · Fastify · Prisma · PostgreSQL · Redis · BullMQ |
| Integrations | Starlink Public API v2 · Google Maps · Odoo Helpdesk · AWS |
| Infrastructure | Docker · GitHub Actions · GHCR · Cloudflare |

## Repositories

| Repository | Description |
| --- | --- |
| [`starlink-unconnected-portal`](https://github.com/Unconnected-org/starlink-unconnected-portal) | The connectHub monorepo: web app, API and shared types |

> Most repositories are private. If you'd like access or want to collaborate, reach out using the contact details below.

## Security

Please **do not** open a public issue for a security vulnerability. Email us instead and include enough detail to reproduce the problem. We'll respond as quickly as we can.

📧 **security@unconnected.org** *(replace with the correct address)*

## Contact

- 🌐 Website: [unconnected.org](https://unconnected.org)
- 📧 Email: **hello@unconnected.org** *(replace with the correct address)*

---

<div align="center">
<sub>© Unconnected.org. Starlink is a trademark of Space Exploration Technologies Corp. Unconnected.org is not affiliated with or endorsed by SpaceX.</sub>
</div>

