# fotobooth. — booking site

The public marketing and booking website for **fotobooth.**, a modern photo booth rental
serving Orange County and Southern California. Live at **https://fotobooth.biz**.

## What it is

A single-page site (`index.html`) with everything inline — no build step, no dependencies.
Visitors can browse the booth, see sample photo strips and reviews, compare packages, read
the FAQ, check open dates on a calendar, and send a booking inquiry.

## Sections

- **Home / hero** — intro video and headline
- **Strip gallery** — sample photo strips
- **Reviews** — customer review carousel
- **Showcase** — photos of the booth at events
- **Packages** — rental options
- **FAQ** — common questions
- **Booking** — calendar with available dates and time slots
- **Contact** — inquiry form (email, phone, Instagram)

## Files

- `index.html` — the entire site (HTML, CSS, and JS inline)
- `hero.mp4`, `hero-poster.jpg` — hero background video and its poster image
- `booth1–6.jpg` — showcase photos
- `strip1–6.jpg` — sample photo strips
- `og-preview.jpg` — social/link-share preview image (~1200×630)
- `robots.txt`, `sitemap.xml` — SEO
- `CNAME` — binds the site to `fotobooth.biz` on GitHub Pages

## Hosting

Hosted on **GitHub Pages** from the `main` branch, `/root` folder, with the custom domain
`fotobooth.biz` (set in **Settings → Pages**, backed by the `CNAME` file and the domain's
DNS records at Namecheap).

To update the site: edit or re-upload the files, commit to `main`, and GitHub Pages rebuilds
within about a minute.

## Contact

- Email: fotobooth.bidness@gmail.com
- Phone: (714) 902-9369

## Related

The event-day **receipt kiosk app** is a separate project, hosted independently at
`kiosk.fotobooth.biz` (repo: `fotobooth-receipt-kiosk`). It is not part of this site.
