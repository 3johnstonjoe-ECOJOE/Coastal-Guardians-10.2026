# Coastal Guardian — GitHub Pages Website Update

**Repository:** `3johnstonjoe-ECOJOE/Coastal_Guardian_Kiosk1`  
**Prepared:** October 2, 2026

This package upgrades the repository from a kiosk-only public page to a multi-page Coastal Guardian website.

## Included website pages

- `index.html` — new Coastal Guardian landing page
- `kiosk.html` — Kiosk Game
- `full-campaign.html` — Full Campaign v2.15.1
- `feedback.html` — public Supabase-backed feedback form
- `admin-feedback.html` — private/unlinked feedback inbox

## Expected GitHub Pages address

If GitHub Pages is configured to publish from the `main` branch and repository root, the expected public address is:

`https://3johnstonjoe-ECOJOE.github.io/Coastal_Guardian_Kiosk1/`

## Important QR note

The three embedded QR codes currently point to:

`https://coastal-guardians.ecojoe3.chatgpt.site/`

They were intentionally preserved because that was the previously selected public QR destination.

If you want the QR codes changed to the GitHub Pages address instead, update them before replacing the live repository files.

## Supabase

The feedback pages use the existing `Coastal_Guardians` Supabase project and browser-safe publishable key.

Do **not** add a Supabase service-role or secret key to this repository.

## GitHub Pages settings

In GitHub:

1. Open the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Save.

GitHub Pages should then serve `index.html` as the website home page.

## Disclaimer

Coastal Guardian is an educational coastal-restoration simulation. The illustrated map, costs, project effects, and scores are simplified educational representations and are not official GIS, engineering, permitting, or project-performance analyses.
