# Veronica Lange — Personal Website

Professional portfolio, coaching business, and YouTube channel hub.

## GitHub Pages Setup

1. Create a new GitHub repository named `veronicaalange.github.io`
   (or any name — see Custom Domain below)

2. Upload all files in this folder to the repository root

3. Go to **Settings → Pages** in your repository

4. Under **Source**, select **Deploy from a branch**

5. Select **main** branch and **/ (root)** folder

6. Click **Save** — your site will be live at:
   `https://veronicaalange.github.io`

## Custom Domain (Optional)

To use a custom domain like `veronicaalange.com`:

1. Purchase your domain from Namecheap, Google Domains, or similar

2. In GitHub Pages settings, enter your custom domain

3. Add these DNS records at your registrar:
   ```
   Type: A     Name: @    Value: 185.199.108.153
   Type: A     Name: @    Value: 185.199.109.153
   Type: A     Name: @    Value: 185.199.110.153
   Type: A     Name: @    Value: 185.199.111.153
   Type: CNAME Name: www  Value: veronicaalange.github.io
   ```

4. Check **Enforce HTTPS** in GitHub Pages settings

## Updating Content

All content is in `index.html`. Key sections to update:

- **Hero** — positioning statement, badges
- **Coaching offers** — update mailto links with your actual booking URLs (Cal.com or Calendly)
- **YouTube** — update episode links once channel is live
- **Contact** — email, phone, LinkedIn

## Booking Links

Replace the `mailto:` links in the coaching section with your actual
Cal.com or Calendly booking URLs once those are set up.
