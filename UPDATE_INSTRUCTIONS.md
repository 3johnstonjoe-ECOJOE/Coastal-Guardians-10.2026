# Update Instructions

These instructions assume you are updating:

`3johnstonjoe-ECOJOE/Coastal_Guardian_Kiosk1`

## Safest manual update

### 1. Download/backup the current repository
Before replacing anything, download the current repository ZIP from GitHub or keep the existing files in Git history.

### 2. Replace the root `index.html`
Replace the current kiosk-only `index.html` with the new `index.html` in this package.

### 3. Add these new root files
Upload these alongside `index.html`:

- `kiosk.html`
- `full-campaign.html`
- `feedback.html`
- `admin-feedback.html`

### 4. Replace `README.md`
You may replace the repository README with the included `README.md`, or merge its GitHub Pages/site information into your current README.

### 5. Commit
Suggested commit message:

`Add Coastal Guardian Kiosk + Full Campaign website`

### 6. Verify GitHub Pages
After GitHub finishes deploying, test:

- Home page loads
- Kiosk Game opens
- Full Campaign opens
- Feedback page opens
- `admin-feedback.html` is not linked publicly
- Instagram `@ecojoe33` link works
- Supabase feedback submissions work

## Current QR destination

The embedded QR codes in both games still resolve to:

`https://coastal-guardians.ecojoe3.chatgpt.site/`

If GitHub Pages becomes the new permanent public website, regenerate those QR codes to the GitHub Pages URL before distributing new QR materials.
