# NTT Nutrition Results-Based Management (RBM) Dashboard

Web dashboard for results-based nutrition programme monitoring in East Nusa Tenggara, Indonesia.

**Programmes:** IMAM, MIYCN, FSCC, and SACA. **Reporting:** 3 consolidated outputs, 27 output indicators, WHO Six Building Blocks, and 9 MoH essential indicators.

The dashboard supports public read-only access and authenticated editing of indicators, supporting activities, quarterly results, and document evidence. Actual records remain in the database, not in this public source repository.

**Status:** Source preparation; production hosting is not activated until deployment and data security are approved.

## Deployment

The Render Blueprint in `render.yaml` provisions a Python web app and a PostgreSQL database. Before applying, review the paid service and database plans, configure `RBM_ADMIN_PASSWORD` as a secret, and use the authenticated import workflow to migrate a backup from the previous local HTML version.

**Prepared and maintained by:** Fandi Imran Pattisahusiwa, UNV Nutrition Officer, UNICEF Field Office Kupang.
