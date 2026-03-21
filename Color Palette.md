# 🎨 Color Palette — Agro-Sync

---

## Prompt (Gemini AI)

> **Prompt:**
> Give me colour pallet for "Agricultural mobile app, high contrast for outdoor sunlight use, earthy natural tones, must be WCAG AAA compliant"

---

### Answer:

## Suggestion

Designing for outdoor use in direct sunlight requires prioritizing intense contrast and reducing glare. When you combine that with WCAG AAA compliance (which requires a strict 7:1 contrast ratio for normal text) and an earthy aesthetic, the best approach is to use highly reflective, warm, light backgrounds paired with deeply saturated, dark, natural foregrounds.

Here is a curated color palette that meets all your requirements:

### The "High-Noon Harvest" Palette

This palette uses a bright, warm off-white to combat screen glare outdoors, paired with rich, grounded dark tones that comfortably exceed WCAG AAA standards.

| Color Role           | Color Name         | HEX Code      | RGB              | Usage Notes                                                                                                                                      |
|----------------------|--------------------|----------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **App Background**   | Sunbleached Canvas | **`#F8F6F2`** | `248, 246, 242`  | Use as the main app background. It provides high reflection for sunlight visibility without the harsh glare of pure white.                       |
| **Card/Surface**     | Dry Sand           | **`#EAE4D8`** | `234, 228, 216`  | Use for floating cards, input field backgrounds, or section dividers to create visual hierarchy.                                                  |
| **Primary Text**     | Rich Soil          | **`#1D1612`** | `29, 22, 18`     | Use for all main body text, headings, and crucial iconography. A very dark, warm brown that acts as a softer alternative to pure black.           |
| **Primary Action**   | Deep Crop Green    | **`#194D25`** | `25, 77, 37`     | Use for primary buttons, active states, text links, and positive confirmations (like a successful sync).                                         |
| **Warning/Alert**    | Fired Clay         | **`#732616`** | `115, 38, 22`    | Use for error messages, critical alerts (e.g., "Low Moisture Warning"), or destructive actions.                                                  |

---

### 📏 WCAG AAA Compliance Verification

To maintain AAA compliance, you must stick to these specific background/foreground pairings. All combinations below exceed the strict **7:1** ratio required for normal-sized text.

**Against App Background (`#F8F6F2`):**
- **Rich Soil (`#1D1612`) Text:** Contrast Ratio is **~17.3:1** (AAA Pass ✅)
- **Crop Green (`#194D25`) Text/Buttons:** Contrast Ratio is **~9.5:1** (AAA Pass ✅)
- **Fired Clay (`#732616`) Text/Alerts:** Contrast Ratio is **~9.1:1** (AAA Pass ✅)

**Against Card/Surface Background (`#EAE4D8`):**
- **Rich Soil (`#1D1612`) Text:** Contrast Ratio is **~14.4:1** (AAA Pass ✅)
- **Crop Green (`#194D25`) Text/Buttons:** Contrast Ratio is **~7.8:1** (AAA Pass ✅)
- **Fired Clay (`#732616`) Text/Alerts:** Contrast Ratio is **~7.6:1** (AAA Pass ✅)

> **Important UI Note for Sunlight:** Because you are using this in direct sunlight, avoid placing white or light text *inside* your colored buttons. A white text on the `Deep Crop Green` button only yields about a 6.7:1 contrast ratio (which fails AAA for normal text).
>
> **The Outdoor Solution:** Keep your buttons light (like the `Dry Sand` color or a transparent outline) with dark `Deep Crop Green` text/icons inside them, or make the buttons massive (large text only requires a 4.5:1 ratio for AAA).

---

## Final Selection

After testing, I kept these three colours for my UI:

| Color       | HEX Code      | Role              |
|-------------|----------------|--------------------|
| 🟡 Gold     | **`#D1AD5A`** | Accent / Highlight |
| 🟢 Green    | **`#194D25`** | Primary Action     |
| 🔴 Clay Red | **`#732616`** | Warning / Alert    |
