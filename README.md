# Ullash Academic Programme — Teacher ID Verification

A small static verification page designed for GitHub Pages.

## Included
- `index.html` — responsive verification page
- `data/teachers.json` — public teacher records
- `assets/lablu-rahman.jpg` — portrait cropped from the ID-card image supplied in chat

## Important privacy notes
- GitHub Pages is public. Anyone can view the website and repository contents.
- This starter intentionally uses a public institutional ID `UAP-T-0001`.
- It does not publish the personal identification number, personal phone number, email address, or blood group shown on the sample card.
- The page verifies only whether a record exists and is marked active in this public JSON file. It is not a government identity verification service.
- To revoke an ID, change its `status` from `active` to `revoked` in `data/teachers.json` and commit the change.

## Publish on GitHub Pages
1. Create a **public** repository named `ullash-id-verification` under your GitHub account.
2. Upload all files and folders from this ZIP to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/(root)`, then Save.
6. After deployment, your URL will be:
   `https://YOUR-USERNAME.github.io/ullash-id-verification/`

## QR destination
After the site is live, create the QR code with this exact URL:
`https://YOUR-USERNAME.github.io/ullash-id-verification/?id=UAP-T-0001`

Replace `YOUR-USERNAME` with your GitHub username. Do not print the QR until the site URL is confirmed and tested.

## Add another teacher
Add another object to `data/teachers.json` using a unique public ID, for example `UAP-T-0002`.
