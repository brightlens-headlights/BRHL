# BrightLens Headlight Restoration website

Ready-to-publish static website for **BrightLens Headlight Restoration**, serving **Lincoln, Nebraska**.

## What's included

- `index.html` — complete mobile-friendly website
- `brightlens-logo.webp` and `favicon.png` — business logo
- `01-black-suv.webp` through `08-silver-sedan.webp` — all eight user-supplied before/after photos (converted to web-friendly WebP, with no crops or retouching)
- `.nojekyll` — instructs GitHub Pages to serve the website as-is

Everything is stored in the root directory, with no assets subfolder, so it is easy to upload.

## Upload to GitHub Pages

1. Download the ZIP and **extract/unzip it**. GitHub Pages needs the files, not the ZIP itself.
2. On GitHub, create/open your website repository (for example, `brightlens-website`).
3. Select **Add file → Upload files** and upload `index.html`, all `.webp` files, `favicon.png`, and `.nojekyll` from the unzipped folder. The README is optional.
4. Commit the changes.
5. In **Settings → Pages**, select **Deploy from a branch**, choose `main`, folder `/(root)`, and save.
6. Once GitHub builds the site, you can use its GitHub Pages address.

## Business email

The website uses the updated business address **brightlensrestoration26@gmail.com**. The email button is visible under Contact, and the footer links to the same address. No extra configuration is needed.

## Google Calendar booking

The website preserves the Google Calendar appointment booking URL previously provided and uses it in every **Book Appointment** button:

`https://calendar.google.com/calendar/appointments/schedules/AcZssZ0KezvT74o_PU4nR4_vKR1CnMdPHIwxzRiiocebhm-CGu9tRScfE4qdJhXAoZcxUjWcHRca6BRP?gv=true`

**Changing the website email does not transfer your Google Calendar appointment schedule to the new Gmail account.** If you create a new booking schedule under the business Gmail, replace every occurrence of the old URL in `index.html` with your new booking page link.

## Contact and social links

- Phone/text: (402) 413-8694
- Email: brightlensrestoration26@gmail.com
- Instagram: https://www.instagram.com/BRHEADLIGHT_RESTORATION/
- Facebook: https://www.facebook.com/share/1Yhdf8eZmS/

No web host, paid service, or build tool is required. Google fonts and Calendar booking require an internet connection.
