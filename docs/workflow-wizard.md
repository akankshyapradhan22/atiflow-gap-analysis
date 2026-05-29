# 6. Workflow Wizard

<div class="section-meta">Accessed via <strong>Processing Area → Workflow tab → + New Workflow</strong>. 5-step wizard: Order Types → Basics → Material Order → Container Order → Review.</div>

## 6.1 Figma Workflow Section Overview

<div class="screenshot-frame">
  <img src="assets/figma/workflow_section.png" alt="Figma — full Workflow section strip">
  <div class="caption">Figma — full Workflow section (all wizard steps side by side)</div>
</div>

---

## 6.2 Step Indicator Bar

<div class="compare-grid">
<figure>
  <img src="assets/figma/workflow_section.png" alt="Figma — step indicator">
  <figcaption class="figma">Figma — step indicator strip</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.40.33 PM.png" alt="App — workflow wizard">
  <figcaption class="app">App — workflow wizard step indicator</figcaption>
</figure>
</div>

| Element | Figma | App | Status |
|---------|-------|-----|--------|
| Active step | Teal filled circle + number | Same | ✅ Match |
| Completed step | Teal circle + white checkmark | Same | ✅ Match |
| Future step | Grey outlined circle + number | Same | ✅ Match |
| Connecting line | Teal when passed, grey for future | Same | ✅ Match |
| Step labels below circles | ✅ | ✅ | ✅ Match |
| Step names | Order Types → Basics → Material Order → Container Order → Review | Same | ✅ Match |

---

## 6.3 Step 2 — Basics

<div class="compare-grid">
<figure>
  <img src="assets/figma/workflow_section.png" alt="Figma — Step 2 Basics">
  <figcaption class="figma">Figma — Step 2: Basics section</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.40.49 PM.png" alt="App — Step 2 Basics">
  <figcaption class="app">App — Step 2: Basics</figcaption>
</figure>
</div>

| Field | Figma | App | Status |
|-------|-------|-----|--------|
| Workflow Name input | ✅ | ✅ | ✅ Match |
| Auto Trip toggle | ✅ | ✅ | ✅ Match |
| Consumption Unit dropdown | ✅ | ✅ | ✅ Match |

---

## 6.4 Step 3 — Material Order / Station Configuration

<div class="compare-grid">
<figure>
  <img src="assets/figma/workflow_section.png" alt="Figma — Step 3 Station Config">
  <figcaption class="figma">Figma — Step 3: Station Configuration</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.40.58 PM.png" alt="App — Step 3 Static mode">
  <figcaption class="app">App — Step 3: Static mode</figcaption>
</figure>
</div>

<div class="compare-grid">
<figure>
  <img src="assets/figma/workflow_section.png" alt="Figma — Step 3 Mapping mode">
  <figcaption class="figma">Figma — Step 3: Mapping-based mode</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.41.06 PM.png" alt="App — Step 3 Mapping mode">
  <figcaption class="app">App — Step 3: Mapping-based mode</figcaption>
</figure>
</div>

| Element | Figma | App | Status |
|---------|-------|-----|--------|
| "Pickup" section header + vehicle icon | ✅ | ✅ | ✅ Match |
| Station Selection: Static → "Station Name *" | ✅ Dropdown | ✅ Dropdown | ✅ Match |
| Station Selection: Mapping-based → "Mapping ID *" | ✅ Dropdown | ✅ + **blue active border** | ⚠️ Active state not spec'd |
| Info tooltip ⓘ next to section headers | ✅ | ✅ | ✅ Match |
| Confirmation Mode table (Station Type / Mode) | ✅ | ✅ | ✅ Match |
| Auto / Manual toggle pill buttons (teal = active) | ✅ | ✅ | ✅ Match |
| Action Type radios (Pick, Auto-hitch, Manual) | ✅ | ✅ | ✅ Match |

!!! success "Best-implemented section"
    The Workflow wizard is the **most faithfully implemented section** — very close to Figma spec throughout.
