# Camera Lab by ICWT

An interactive, single-file camera simulator that shows how focal length, aperture, shutter speed, ISO, and focus work together to turn light into a photograph.

No build step, no server, and no external dependencies—just one self-contained HTML file powered by vanilla HTML, CSS, and Canvas.

## Quick Start

1. Open `final_code.html` in any modern desktop browser.
2. Adjust the sliders on the right, click anywhere in the live view to focus, or press `Space` to take a photo.

## Highlights

- **Live Viewfinder:** Full-frame 3:2 view with real-time depth of field, motion blur, exposure, vignetting, and sensor noise. Click any subject, tree, ground spot, or the sky to focus there.
- **Top-Down Scene Map:** Switch to the **Scene map** tab to see the field-of-view cone, sharp focus zone, and focus plane from above. Drag the person, sunflower, or car to restage the shot.
- **Inside the Camera:** A collapsible live schematic showing light rays through the lens and aperture, the shutter cycle, sensor light, and ISO gain—all driven by your current settings.
- **Instant Feedback:** Short **"What just happened?"** popups explain what changed after each adjustment, and hovering over any control displays a quick guide (including a live iris diagram for aperture).
- **Capture & A/B Compare:** Take clean, overlay-free PNG photographs, browse them in the session gallery, or tag two shots as **Shoot A** and **Shoot B** for a side-by-side comparison with automated explanations.

## Point & Shoot Presets

Quickly reset the scene to explore one concept at a time:

| Preset | What It Shows |
| --- | --- |
| **Everyday** | Balanced daylight exposure (default scene) |
| **Portrait** | Shallow depth of field at 85 mm and f/1.8 |
| **Motion Photography** | Moving car—compare fast shutters that freeze motion against slower speeds that blur it |
| **Low light** | Dusk lighting at high ISO, showing how amplification brings out shadow noise |

## Controls at a Glance

All exposure settings are fully manual so you can see cause and effect directly:

- **Lens & Focal Length:** 18 mm to 135 mm (zooms in/out without moving the camera)
- **Aperture:** f/1.4 to f/22 (controls light and depth of field)
- **Shutter Speed:** 1/2000 s to 1 s (controls light and motion blur)
- **ISO:** 100 to 6400 (amplifies brightness along with sensor noise)
- **Exposure Meter:** Read-only indicator showing whether the shot is balanced, bright, or dark
- **Focus Distance:** 0.5 m to infinity (or click directly on the live view)
- **Environment:** Adjust sunlight brightness (dusk to full sun) and car speed (0 to 120 km/h)

## Keyboard Shortcuts

- `Space` / `Enter` — Take a photograph (when the viewfinder is focused)
- `Escape` — Close the gallery or confirmation dialog

## Good to Know

- **Desktop-first:** Built for a two-column desktop layout (viewfinder and schematic on the left, controls on the right).
- **Session-only gallery:** Photos live in browser memory and clear on reload—use **Download PNG** in the gallery to save any shot.