# AI Clipper — Demo

A lightweight, mobile-first static demo of an AI short-form video clipping workflow. Built with plain HTML, CSS, and JavaScript; no dependencies, server, or API key required.

## Demo features

- Video-link input field (sample input only)
- 15-second or 30-second clip duration
- Vertical 9:16 (720 × 1280) or landscape 16:9 (1280 × 720) output setting
- Smart Hook overlay toggle
- Auto captions toggle
- Simulated analysis progress and illustrative clip candidates
- Simulated export selection

## Important limitations

This is a **UI simulation only**. It does not fetch or upload videos, analyze real footage, create captions from audio, or render/download MP4 files. Timestamps and hooks are example placeholders, not verified source timestamps. No API keys are used.

## Publish with GitHub Pages

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for the Pages deployment to finish. GitHub will show the published site URL in the Pages section.

The entry page is `index.html` in the repository root.

## Run locally

Open `index.html` in a modern browser. No build step is needed.
