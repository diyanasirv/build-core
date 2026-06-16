# BuildCore ERP Dashboard

BuildCore is a modern, high-performance Enterprise Resource Planning (ERP) web dashboard specifically engineered for the construction and infrastructure management sectors. Designed as a modular Single Page Application (SPA), it provides construction managers, administrative heads, and project coordinators with a single, consolidated platform to track site progress, optimize resource allocations, and audit real-time financial metrics.

By centralizing data streams from the field to the back office, BuildCore eliminates operational siloes, cuts out manual spreadsheet dependencies, and drives data-backed decision-making across all active construction sites.

---

## 🚀 Core Functional Modules

The platform is structured into core operational modules, easily navigated via the dynamic top management bar:

### 📊 Comprehensive Dashboard
*   **Real-Time Analytics Grid:** Aggregates multi-site metrics into high-level, glanceable statistical indicators (`dash-stats`).
*   **Activity Monitoring:** Features a "Recent Projects" feed paired with a "Quick Overview" panel to monitor milestones, sudden bottlenecks, and cross-project status shifts.

### 🏗️ Lifecycle Project Tracking
*   **Site Pipelines:** Tracks development phases from initial blueprint planning through excavation, core build structural steps, to client hand-off.
*   **Deadlines & Milestones:** Monitors schedule adherence across independent contract sectors to ensure timely delivery.

### 👷 Workforce & Personnel Management
*   **Workers & Labor Deployment:** Logs on-site attendance, tracks labor numbers across distinct sites, and monitors subcontractor rosters.
*   **Managers Hub:** Direct coordination space for structural site managers, facilitating clear accountability assignment for specific geographical zones.

### 🚜 Heavy Machinery & Asset Dispatch
*   **Logistics Scheduling:** Tracks location schedules for expensive operational equipment (e.g., excavators, cranes, mixers) to avoid bottleneck downtime.
*   **Maintenance Logs:** (Planned) Tracks service histories and machinery health checkups to protect capital equipment assets.

### 📦 Material & Inventory Supply Chain
*   **Stock Ledger:** Real-time stock counts for critical components like cement, steel rebar, and aggregate.
*   **Consumption Rates:** Monitored against incoming invoices to detect project leaks or supply waste early.

### 💰 Finance & Expenditure Auditing
*   **Cost Accounting:** Centralized space to log material invoices, labor payroll, equipment rental costs, and client cash flow milestones.
*   **Budgeting Integrity:** Compares real-time expenditures against projected project targets to flag overruns instantly.

---

## 🛠️ Architecture & Technical Stack

The architecture of BuildCore prioritizes lightweight parsing, extreme loading speeds, and strict modular design principles:

*   **Frontend Interface:** Optimized Single Page Application (SPA) system built using semantic HTML5 and vanilla layout components. View routing is handled dynamically in client memory via high-performance JavaScript render routers (`showPage`), bypassing heavy third-party framework overhead.
*   **Styling & UI Core:** Custom modern CSS stylesheet design incorporating advanced Flexbox alignment matrices and dynamic Grid layouts (`stats-grid`, `dash-grid`) for complete responsive flexibility across mobile, tablet, and desktop viewports.
*   **Data Tier Integration:** Specifically decoupled to interface with robust Cloud Backend-as-a-Service environments (such as **Supabase/PostgreSQL**) using explicit, async client SDK bindings for resilient CRUD operations.
*   **Session Security Layer:** Integrated state engines tracking live user session tokens (`user-email-display`), profile compilation steps, and secure programmatic logout handlers.

---
