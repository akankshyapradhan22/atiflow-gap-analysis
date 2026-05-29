# Summary: Prioritised Gaps

## 🔴 Critical — Design / Implementation Mismatch

These are cases where the Figma spec and app directly contradict each other.

| # | Screen | Figma | App | Impact |
|---|--------|-------|-----|--------|
| 1 | Requester Device table | "Username" + "UI Mode" columns | Replaced by "Bound Machines" | Column structure change — Figma needs update |
| 2 | Dispatcher Device modal | "Username" field present | Absent | Field removed — Figma shows ghost field |
| 3 | Supervisor Device Edit modal | "Visible Staging Areas" in both Add + Edit | Present only in Add modal | Edit UX incomplete vs Figma |
| 4 | Settings Connections | 3 cards: FM, AMR, **BOM API** | 2 cards: FM + AMR only | BOM API feature removed — Figma never updated |

---

## 🟠 Moderate — App Additions Not in Figma

These features exist in the live app but have **no Figma design**. They need to be back-ported into Figma for documentation and future iteration.

| # | Feature | Where | Notes |
|---|---------|-------|-------|
| 5 | "Processing Area" 7th tab | Per-area nav | Entire tab with Add New Area form |
| 6 | Cell B1 staging edit modal | Staging Area → Manage mode | Cell State + "Filled with" dropdowns |
| 7 | Required field `*` asterisks | All form modals | Red asterisk on every required field |
| 8 | "Requested" + "Total Qty" columns | WIP Inventory | 2 new columns not in Figma |
| 9 | "Process Name" auto-fill | Add New Material modal | Pre-filled with current area name |
| 10 | Refresh + "Updated just now" | WIP Inventory | Real-time refresh indicator |
| 11 | AMR "Schedule (s...)" field | Settings → Connections → AMR | Numeric polling interval field |
| 12 | Red uppercase CANCEL button | All modals | Colour treatment not specified in Figma |

---

## 🟡 Minor — Copy / Styling Differences

Small discrepancies that should be aligned in either design or implementation.

| # | Element | Figma | App |
|---|---------|-------|-----|
| 13 | WIP Inventory search | "Search SKU" | "Search by SKU, SKU Code" |
| 14 | Materials search | "Search Material" | "Search materials" |
| 15 | Mapping-based input border | Not specified | Blue active/focused border |
| 16 | Layout density | Tighter | More generous whitespace |

---

## 🔲 Unverified — Screenshots Not Captured

These screens exist in Figma but app screenshots were never taken. **Assign someone to capture and verify.**

| # | Screen | Figma node | Action |
|---|--------|------------|--------|
| 17 | Container Master (full CRUD) | `574:3179` variants | Capture Containers tab in app |
| 18 | Station Mapping (material + container mapping) | `574:14889` variants | Capture Station Mapping tab in app |
| 19 | MES tab (Event Mapping Name, Key-Value) | `figma_profile4` | Capture MES tab in app |
| 20 | WIP Inventory expanded row detail modal | `figma_wip_inventory2` | Capture expanded row in app |

---

## Counts at a Glance

| Category | Count |
|----------|-------|
| 🔴 Critical mismatches | 4 |
| 🟠 App additions not in Figma | 8 |
| 🟡 Minor differences | 4 |
| 🔲 Unverified | 4 |
| ✅ Confirmed matches | ~60+ |

---

*Report generated May 2026 — Figma version 2355537039279972312 vs app screenshots 2026-05-22.*
