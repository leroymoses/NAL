# North American Logistics — Website

Single-file static site (`index.html`) — logo is embedded inline, so no other assets are needed.

## Deploy with GitHub Pages

1. Create a new repo on GitHub (e.g. `nal-website`).
2. Add this `index.html` to the root of the repo and push/commit it.
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, select the branch (usually `main`) and folder `/ (root)`, then Save.
5. GitHub will give you a live URL, typically:
   `https://<your-username>.github.io/nal-website/`
   (takes a minute or two to go live after the first deploy)

## Using a custom domain (optional)

In the same **Settings → Pages** section, enter your domain under "Custom domain" and follow GitHub's DNS instructions (a `CNAME` record pointing to your GitHub Pages URL).

## Local preview

Just open `index.html` directly in a browser — no build step, no server required.
