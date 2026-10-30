# BookLoop — ready-to-host static website

## Pages included
- Explore books (`#books`)
- Sell a book (`#sell`)
- Request a book (`#need-book`)
- Book requests (`#requests`)
- Selected books (`#cart`)

## Run locally
Open `index.html` in a browser, or serve this folder with any static web server.

## Deploy
### Netlify
1. Go to Netlify and choose **Add new site** / manual deploy.
2. Upload the `bookloop_site` folder (or deploy the ZIP contents).
3. Netlify will publish `index.html` as the home page.

### Vercel
1. Create a new project and upload/connect this folder.
2. Select **Other** as the framework preset.
3. Leave build command and output directory empty/default, then deploy.

### GitHub Pages
1. Put `index.html` at the repository root.
2. In repository **Settings → Pages**, deploy from the main branch and root folder.

## Important limitation
This is a static, front-end demo. Book listings, requests, and selected books are saved in the visitor's browser using `localStorage`; they are **not shared across users or devices**, and can be cleared by the browser. There is no login, database, image upload, messaging system, payment processing, or server-side API. For a real campus-wide marketplace, connect a backend/database and add authentication, moderation, privacy protections, and validation before collecting real contact details.

## Included files
- `index.html` — website
- `netlify.toml` — basic static hosting configuration
- `vercel.json` — static hosting configuration
