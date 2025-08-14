# Proud Of My Town — Static Site (GitHub Pages)

This folder contains a single `index.html` you can upload to a GitHub repository and publish for free with GitHub Pages.

## Quick publish (no code tools required)
1. Create a GitHub account at https://github.com (free).
2. Click **New repository** → name it e.g. `proudofmytown` → keep it **Public** → **Create**.
3. Click **Add file → Upload files**, drag in `index.html`, and **Commit**.
4. Go to **Settings → Pages** → Build & deployment: **Deploy from a branch**.  
   Choose **Branch: `main`** and **Folder: `/ (root)`** → **Save**.
5. Your site will appear at `https://<your-username>.github.io/<repo-name>/` within a minute.

## Editing products & stories
Open `index.html` and find the `PRODUCTS` array. For each product set:
- `title`, `price`, `image` (URL), `buyUrl` (Stripe/Gumroad/Shopify link)
- `story` (short paragraph the shopper reads in the modal)
- `igSeq` (Instagram sequence number; 1 = newest post)

Use the **Instagram order / Newest first** toggle on the page to test ordering.

## Connect checkout (lowest-cost)
- **Stripe Checkout**: create a payment link in Stripe and paste into `buyUrl`.
- **Gumroad**: paste the product URL into `buyUrl`.
- **Shopify Starter** ($5/month): paste the Buy Button URL into `buyUrl`.

## Custom domain (optional)
Add a CNAME in GitHub Pages and point your DNS CNAME to `<your-username>.github.io`.

