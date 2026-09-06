# Pullar Official Website

Minimalist landing website for **Pullar** ("Don't just watch—pull it"), showcasing high-speed video and audio downloaders for Windows and Android.

Built with [Astro](https://astro.build) and optimized for zero-configuration deployment on [Cloudflare Pages](https://pages.cloudflare.com).

---

## Color Palette

- Coffee Bean: `#1A110F`
- Light Apricot: `#FFEBC2`
- Toffee Brown: `#945E38`
- Maya Blue: `#7CC6FE`

---

## Local Development

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```

---

## Deploying to Cloudflare Pages

1. Log in to the [Cloudflare Dashboard](https://dash.cloudflare.com) and navigate to **Workers & Pages**.
2. Click **Create Application** > **Pages** > **Connect to Git**.
3. Select this repository: `1abdullahr1/pullar-website`.
4. In the build settings, configure:
   - **Framework preset**: `Astro`
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`
5. Click **Save and Deploy**. Cloudflare Pages will build and deploy the site worldwide across its global edge network.

---

## License

Released under the [MIT License](LICENSE).
