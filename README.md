# RPE Systems

Consolidated repo for RPE Flooring Operations Engine — dashboards, n8n workflow templates, client deployments, and deploy tooling.

## Structure

```
rpe-systems/
├── dashboard/          # Generic RPE dashboard (index.html, signoff.html)
├── workflows/          # Parameterized n8n workflow templates (v01–v12)
├── clients/
│   └── aj-flooring/    # AJ Flooring Solutions — client-specific dashboard
├── deploy/             # Deployment tooling and client deploy configs
├── clients.json        # Client manifest (searchable index)
└── README.md
```

## Clients

| Client | Folder | Contact | Status |
|--------|--------|---------|--------|
| AJ Flooring Solutions | `clients/aj-flooring/` | Carey Hunter | Active |

See `clients.json` for machine-readable client index.

## Workflows

12 parameterized n8n workflow templates in `workflows/`:
- v01: Margin Guardrail
- v02: Labor Cap Monitor
- v03: Field Validation
- v04: Job Completion
- v05: Material Order
- v06: Change Order Sync
- v07: Payout Gate
- v08: CO Paid Recalc
- v09: Dashboard Feed
- v10: Dashboard Feed (GHL)
- v11: Dashboard Live JSON
- v12: Signoff Receiver

## History

This repo consolidates the following former repos (now deleted):
- `rpe-dashboard` → `dashboard/`
- `aj-flooring-dashboard` → `clients/aj-flooring/`
- `rpe-workflow-templates` → `workflows/`
