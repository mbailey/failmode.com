# failmode.com

Minimal website for failmode.com

## Deployment

This site is designed to be deployed via GitHub Pages:

1. Create a new repository named `failmode.com` or `failmode-website`
2. Push this code to the repository
3. Enable GitHub Pages in Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. The site will be available at the custom domain failmode.com (CNAME file included)

## DNS Configuration

Ensure your domain has these DNS records:
- A record: `185.199.108.153`
- A record: `185.199.109.153`
- A record: `185.199.110.153`
- A record: `185.199.111.153`
- CNAME record for www: `mbailey.github.io`

## Local Development

Simply open `index.html` in a browser. No build process required.