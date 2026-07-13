# Narcissistic Insanity — VFX Production Hub

A single-page VFX production hub for the feature **Narcissistic Insanity** (Script v2.8), built for **Levl Studio**.

**Live site:** https://borngifted.github.io/narcissistic-insanity-vfx/

## Tabs
- **VFX Shot Tracker** — priority-sorted shot breakdown (40 shots) seeded from the script, with search + filter by tier/effect type.
- **Scene Breakdown** — VFX load grouped by the show's recurring FX systems (AGI screens, deepfake/AI-avatar, mirrors/apparitions, CG alligators, gore, environment/hack FX).
- **AGI Character & Assets** — the AGI AI-companion character: ElevenLabs voice, all 39 audio cues, and the Higgsfield character-image plan.
- **Previs & Pipeline** — previs priorities and a live status board across bid → previs → layout → anim/FX → comp → final/QC.

## Editing
It's a static, self-contained `index.html` (no build step, no dependencies). Update the `SHOTS`, `CUES`, and `SEQS` arrays in the `<script>` block as production progresses, then push — GitHub Pages redeploys automatically.

Exported AGI audio can be dropped into `assets/audio/` to enable previews on the AGI tab.

_Living document — initial breakdown. Content derives from the shooting script for production-planning purposes._
