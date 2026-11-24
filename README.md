# Forge Nutrition (demo gym supplements store)

Single-file frontend: `index.html` (no build step, no dependencies).

## Run locally
Open `index.html` in a browser, or: `npx serve .`

## Deploy
1. Push to GitHub.
2. vercel.com > Add New > Project > import the repo.
3. Framework Preset: **Other**. Leave build command and output directory empty. Deploy.

## Customize
Edit the `CFG` block near the top of the `<script>` (FSSAI, GST, email, phone, WhatsApp number)
and the `P` array (products). Orders, OTP and payments are simulated in the browser.
