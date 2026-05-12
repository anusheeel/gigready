# GigReady Website

Static landing, support, and privacy site for GigReady Setlist Planner.

## Local Preview

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Vercel

Import this folder as the Vercel project root.

- Framework preset: Other
- Build command: leave blank or use `npm run build`
- Output directory: leave blank

After deploy, add `gigready.xyz` in Vercel Project Settings → Domains.

Use these App Store Connect URLs:

- Marketing URL: `https://gigready.xyz`
- Support URL: `https://gigready.xyz/support`
- Privacy Policy URL: `https://gigready.xyz/privacy`
