# Oil Is Not Food

A static HTML and CSS guide to vegetable oils, food labels and home cooking.

## Local preview

From the repository root, run `python3 -m http.server 8000 --bind 127.0.0.1` and open `http://127.0.0.1:8000/`.

## GitHub Pages

Review the repository's existing commit metadata before publishing. Once the site files are on the publishing branch, open **Settings → Pages**, select **Deploy from a branch** and choose that branch and **/ (root)**.

The repository's `CNAME` file declares `oil-is-not.food`. Verify the domain in GitHub, set it as the custom domain in Pages settings, and configure apex DNS with your DNS provider using [GitHub's current apex-domain instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain). Enable **Enforce HTTPS** once GitHub has provisioned the certificate.
