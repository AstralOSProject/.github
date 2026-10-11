### Display & UI

| Feature | Description |
| --- | --- |
| **Animation speed** | Control how fast system animations play. |
| **Lockscreen clock color** | Pick the colour of the lockscreen clock. |
| **Extra dim** | An additional dimming step for lower brightness than stock. |
| **Clock font** | Choose the typeface used for the lockscreen clock. |
| **Glass styling** | Astral glass aesthetic throughout SystemUI — 36dp quick-settings tile radius and 80dp notification-shade blur. |

### Gestures

| Gesture | Action |
| --- | --- |
| **Three-finger swipe** | Take a screenshot. |
| **Shake** | Toggle the flashlight. |

### Status bar

| Feature | Description |
| --- | --- |
| **4G for LTE** | Force the `4G` icon instead of `LTE` on networks that report LTE. |
| **Battery style** | Adds a **Hide** option to the existing *Portrait icon / Circle / Text* styles. |

### Launcher — Trebuchet

- Drawer **labels hidden by default** for a cleaner app list.
- **Icon size increased by ~14%**.

### Browser — Jelly

- **Look Lock** enabled by default.
- **Do Not Track** enabled by default.

### Branding

- **LineageParts rebranded** to AstralOS (Trust, statistics and Easter egg strings).
- **Updater rebranded** — OTA server, changelog and headers across all locales.
- Custom **AstralOS launcher icon**.
- **"About AstralOS" page removed** from Settings.
- Translations for **23 locales**.

### Performance — frameworks/native

- SurfaceFlinger **HWC backpressure disabled**.
- **gpuservice disabled**.
- **Dalvik heap limits raised** (start 16m, growth 256m, target 0.75, maxfree 32m) for smoother app switching.
- **Blur-region optimisations** — clip blur regions to layer bounds, cap the number of blurred layers, and submit each blur region as a separate request.
- **RPC Binder** crash and error-handling fixes.
