# Signature Generators (Markgrid + Two99)

Static email signature tools for **Markgrid** and **Two99**. Logos are hosted in this repo and referenced with absolute URLs so they keep working after you paste the signature into Gmail.

## Live site

After you connect this repo to Vercel, open the deployment URL:

- `/` — choose Markgrid or Two99
- `/markgrid/` — Markgrid signature generator
- `/two99/` — Two99 signature generator (pick one of 4 square logo styles)

## How to use (Gmail)

1. Open the generator for your brand.
2. Fill in name, title, phone, and LinkedIn (Two99) or the Markgrid fields.
3. Click **Generate Signature**.
4. In the popup window: **Select All** (`Cmd+A` / `Ctrl+A`) → **Copy** (`Cmd+C` / `Ctrl+C`).
5. Gmail → **Settings** → **See all settings** → **General** → **Signature**.
6. Paste (`Cmd+V` / `Ctrl+V`) → **Save Changes**.

## Deploy on Vercel

1. Log in to [Vercel](https://vercel.com) (e.g. `security@two99.org`).
2. **Add New… → Project** → **Import Git Repository**.
3. Connect GitHub if prompted, then select `kunaltomartwo99/Markgrid-Signatures-1-`.
4. Framework preset: **Other** (static). No build command needed. Output directory: leave empty / `.`
5. Deploy. Use the new `*.vercel.app` URL going forward.

Images are public files under `markgrid/images/` and `two99/images/`. Do **not** host signature logos on Google Drive.

## Local preview

Serve the repo root with any static server, for example:

```bash
npx --yes serve .
```

Then open `http://localhost:3000/` (or the port shown).
