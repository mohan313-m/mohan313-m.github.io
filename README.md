# Mohan Shrestha — Personal Website

## Files
- `index.html`: Complete responsive website (HTML, CSS, JavaScript in one file).
- `CNAME`: Custom domain for GitHub Pages.

## Before publishing
1. Open `index.html` and replace `YOUR_EMAIL@example.com` with your real public contact email.
2. Update education, experience, research, and publication details for accuracy.
3. Add your LinkedIn/GitHub profile URLs if desired.
4. Preview by double-clicking `index.html` in your browser.

## Free deployment using GitHub Pages
1. Create/sign in to GitHub.
2. Create a **public repository** named exactly `YOUR-GITHUB-USERNAME.github.io` (replace with your GitHub username).
3. Upload `index.html`, `CNAME`, and optionally this README to the repository root.
4. In repository **Settings → Pages**, choose publishing from the `main` branch and `/ (root)`, then Save.
5. In **Settings → Pages → Custom domain**, enter `mohanshrestha07.com.np` and Save.
6. At the company/portal where you manage the domain DNS, add these records:
   - A | Host/Name `@` | `185.199.108.153`
   - A | Host/Name `@` | `185.199.109.153`
   - A | Host/Name `@` | `185.199.110.153`
   - A | Host/Name `@` | `185.199.111.153`
   - CNAME | Host/Name `www` | `YOUR-GITHUB-USERNAME.github.io`
7. If DNS allows, verify the domain with GitHub first. Do not delete existing mail-related MX/TXT records. Remove conflicting A/AAAA/CNAME records only if you know they conflict with the website setup.
8. Wait for DNS propagation (sometimes up to 24 hours). Return to Settings → Pages and enable **Enforce HTTPS** when it becomes available.

The exact DNS interface varies by registrar. This is a static site: it does not include a database, server-side login, or a working contact form. GitHub Pages public repositories make the source code public.
