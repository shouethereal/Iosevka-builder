### Build Log
- Build Time: 2025-12-25 22:55:22 UTC
- Source Commit: 6c9c4e2b49ffb353f2e64e8a22905d194bb2f522
- Build Target: contents

### private-build-plans.toml
```toml
[buildPlans.IosevkaCustom]
family = "Iosevka Custom"
spacing = "fontconfig-mono"
serifs = "slab"
noCvSs = true
exportGlyphNames = false

  [buildPlans.IosevkaCustom.ligations]
  inherits = "dlig"

[buildPlans.IosevkaCustom.weights.Regular]
shape = 400
menu = 400
css = 400

[buildPlans.IosevkaCustom.weights.Light]
shape = 300
menu = 300
css = 300

[buildPlans.IosevkaCustom.widths.Normal]
shape = 548
menu = 5
css = "normal"

[buildPlans.IosevkaCustom.slopes.Upright]
angle = 0
shape = "upright"
menu = "upright"
css = "normal"

[buildPlans.IosevkaCustom.slopes.Italic]
angle = 9.4
shape = "italic"
menu = "italic"
css = "italic"
```
