# Oilfield Service Ticket & Invoice Audit

Validate oilfield service invoices against signed field tickets, crew and equipment time, rate sheets, and job scope.

**Primary buyer:** Exploration and production operators. **Evidence:** master service agreements, wells, work orders, field tickets, crews, equipment, materials, rates, standby, mileage, invoices, and credits.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Master service agreement library
- Well job registry
- Work order ingestion
- Field ticket capture
- Crew hour validation
- Equipment hour validation
- Material quantity matching
- Rate sheet calculation
- Standby time audit
- Mobilization mileage
- Fuel surcharge control
- Invoice ticket matching
- Vendor dispute workflow
- Credit reconciliation
- Well vendor analytics

Run `./start.sh`, then open <http://127.0.0.1:4713>. API: `5713`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
