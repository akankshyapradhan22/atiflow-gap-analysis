# 8. Staging Area

<div class="section-meta">Accessed via <strong>Processing Area → Staging Area tab</strong>. Shows a visual grid of staging cells with state colour-coding.</div>

## 8.1 Grid View

<div class="compare-grid">
<figure>
  <img src="assets/figma/staging_area.png" alt="Figma — Staging Area grid">
  <figcaption class="figma">Figma — Staging Area grid (large)</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.37.16 PM.png" alt="App — Staging Area grid">
  <figcaption class="app">App — Staging Area grid (staging_map, 3×2)</figcaption>
</figure>
</div>

| Element | Figma | App | Status |
|---------|-------|-----|--------|
| Grid size | Large (~10×5 cells) | Smaller (3×2 in screenshots) | ⚠️ Config-dependent |
| Available — teal square icon | ✅ | ✅ | ✅ Match |
| Reserved — yellow diamond icon | ✅ | ✅ | ✅ Match |
| Blocked — coral circle icon | ✅ | ✅ | ✅ Match |
| Filled — light blue square | ✅ | ✅ | ✅ Match |
| Legend (all 4 states) | ✅ | ✅ | ✅ Match |
| View / Manage toggle buttons | ✅ | ✅ | ✅ Match |
| Breadcrumb navigation | ✅ | ✅ | ✅ Match |

---

## 8.2 Staging Area — Manage Mode

<div class="compare-grid">
<figure>
  <img src="assets/figma/staging_area2.png" alt="Figma — Staging Area manage mode">
  <figcaption class="figma">Figma — Staging Area (manage mode)</figcaption>
</figure>
<figure>
  <img src="assets/app/Screenshot_2026-05-22_at_1.37.58 PM.png" alt="App — Cell B1 modal">
  <figcaption class="app">App — Cell B1 edit modal</figcaption>
</figure>
</div>

| Element | Figma | App | Status |
|---------|-------|-----|--------|
| Cell B1 / cell management modal | ❌ **Not designed** | ✅ Cell State + "Filled with" dropdowns | ➕ Entirely added in app |

!!! warning "Missing from Figma"
    The cell edit modal (Cell State dropdown: Available / Reserved / Blocked / Filled + "Filled with" dropdown) is a complete feature with no Figma design counterpart.
