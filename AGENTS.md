# Homelab HA Alerting Agent Guide

## Scope

This repo holds alerting-specific Home Assistant content and related documentation.

## Operating Rules

- Keep alerting logic explicit, readable, and easy to troubleshoot.
- Prefer stable naming for automations, notifications, and helper entities.
- Do not add secrets or tokens to tracked files.
- Keep this repo aligned with the active Home Assistant implementation, not legacy NAS notes.

## Maintenance Expectations

- Update documentation when alert routing, notification channels, or operating assumptions change.
- Keep operational guidance concise and specific to the homelab.
- If shared runtime ownership belongs elsewhere, document it here and update the owning repo instead of duplicating logic.

## Change Standard

- Favor simple, debuggable alert flows.
- Avoid unnecessary abstraction for homelab-scale automation.