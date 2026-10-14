# Al Sakyf Azad Portfolio

A responsive static portfolio built with HTML, CSS, and JavaScript. All website files are in `dist/`. No package installation or backend is required.

## Publish through GitHub and Cloudflare Pages

1. Create a GitHub repository named `al-sakyf-azad-portfolio` and upload this folder's contents, preserving the `dist/` folder.
2. In Cloudflare, open **Workers & Pages**, create a **Pages** application, and connect the GitHub repository. If prompted, grant access only to this repository.
3. Set the production branch to `main`, framework preset to **None**, build command to `exit 0`, and build output directory to `dist`. Leave the root directory at its default.
4. Save and deploy. Cloudflare returns a free `pages.dev` address. The requested project name is `al-sakyf-azad-portfolio`; the exact address depends on availability.
5. Future pushes to `main` deploy automatically.

Cloudflare setup reference: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/

## Content updates

- `dist/index.html`: biography, experience, publications, and contact details.
- `dist/style.css`: appearance and responsive layout.
- `dist/script.js`: project overviews, filters, navigation, and email copying.
- `dist/assets/portrait.jpg`: profile photo.
- `dist/assets/Al-Sakyf-Azad-CV.docx`: downloadable CV.

The published website includes the contact information and CV provided by the portfolio owner. Google Fonts is used with system-font fallbacks.
