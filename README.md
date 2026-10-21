# Plumtree Plants Elizabethton

Website for the Elizabethton seasonal location. Custom domain: **plumtreeplantstn.garden**.

## Publish through GitHub
1. Open https://github.com/muncyman/plumtree-plants-elizabethton
2. Choose **Add file → Upload files** and upload `index.html`, `CNAME`, and `README.md` from this package (not the containing folder). Commit to `main`.
3. Under **Settings → Pages**, choose **Deploy from a branch**, **main**, **/(root)** and Save.
4. In GitHub Pages, set **Custom domain** to `plumtreeplantstn.garden` and Save (if not already populated).
5. At your domain registrar, configure the A records for the root `@` pointing to GitHub Pages IPv4 addresses:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
   Remove conflicting root A/AAAA/CNAME records. For `www`, add CNAME pointing to `muncyman.github.io` (without a repo path).
6. After DNS propagates and the certificate is ready, enable **Enforce HTTPS** in Pages settings.

Before sharing the live URL: confirm that the owner approved publication and the business links/hours are accurate. Christmas opening date remains TBA. These are stated lot hours when seasonally operating: Mon–Sat 9am–6pm; Sun 10am–5pm.

Do not use GitHub's default Pages URL as customer-facing advertising; use the custom domain.
