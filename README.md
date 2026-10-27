# aptcomgh.com

Apt Communications' website. Plain HTML, no build step.

- `index.html`: the whole site (styles and script inline)
- `logo.png`, `favicon.png`, `apple-touch-icon.png`: brand images
- `netlify.toml`: hosting settings (headers, www redirect)

Deploys automatically on Netlify (project `aptcomgh`) whenever `main` is pushed.
DNS is at Namecheap: `@` A 75.2.60.5, `www` CNAME aptcomgh.netlify.app, `live` A 167.99.93.40 (the app platform; don't remove).
