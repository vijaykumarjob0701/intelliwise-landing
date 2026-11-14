# The Intelliwise landing page

Plain coming-soon page for **https://theintelliwise.com**.

The technical blog lives at **https://blogs.theintelliwise.com**
(repo: [vijaykumarjob0701/theintelliwise](https://github.com/vijaykumarjob0701/theintelliwise)).

## Important

Do not enable GitHub Pages, and do not attach the custom domain
`theintelliwise.com`, until the blog repo has already switched its Pages
domain to `blogs.theintelliwise.com`. Enabling this domain too early
would take the live blog offline.

`CNAME` is already set to `theintelliwise.com` so the cutover is a
Pages setting change, not a file edit.

Old paths such as `/posts/<slug>/` are handled by `404.html`, which
sends the browser to the same path on `https://blogs.theintelliwise.com`.

## After DNS and the blog domain are ready

1. Settings → Pages → Deploy from a branch → `main` / root.
2. Custom domain: `theintelliwise.com`.
3. Wait for the HTTPS certificate, then enforce HTTPS.
4. Confirm the home page shows this landing page, and a post URL such as
   `https://theintelliwise.com/posts/vector-index-myths/` redirects to
   the blog subdomain.
