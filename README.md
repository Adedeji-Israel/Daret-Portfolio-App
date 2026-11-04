<<<<<<< HEAD
# Daret Digitals website

Portfolio site for Obadare Olabiyi, CRM & Business Automation Specialist.

The site is a single static page (`index.html`) with no build step. It uses plain HTML, CSS, and JavaScript, so it can be hosted anywhere.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole website, including content data, styles, and scripts |
| `robots.txt` | Crawler rules |
| `sitemap.xml` | Sitemap for search engines |

## Run it locally

Open `index.html` in a browser, or run `python3 -m http.server 8080` in this folder and visit http://localhost:8080.

## What you must fill in

Search `index.html` for `YOUR-DOMAIN.com` and replace it with your real website address. It appears in the canonical link, the Open Graph tags, `robots.txt`, and `sitemap.xml`.

Add an `og-image.png` (1200 x 630) next to `index.html` so shared links show a preview.

## Edit content

All content sits in the `<script>` block at the bottom of `index.html`, inside clearly commented data blocks.

| To change | Edit |
| --- | --- |
| Email, WhatsApp number and message | `CONFIG` |
| Logo | Set `CONFIG.logoSrc` to your logo file, or edit the inline SVG in the header |
| Profile photo | Replace `images/obadare-olabiyi.jpg` (or change `CONFIG.photoSrc`) |
| LinkedIn and other social links | `CONFIG.social` (empty ones stay hidden) |
| Services | `SERVICES` |
| CRM and tool list | `PLATFORMS` (keep only tools you can genuinely support) |
| Portfolio projects | `PROJECTS` (each has a `label`, `media`, and `outcomes`) |
| Portfolio screenshots | `MEDIA` (embedded images) or any file path in a project's `media` list |
| Email & popup design gallery | `DESIGN` (title, brand, description, `img` key from `MEDIA`) |
| Portfolio videos | Put an .mp4 in `videos/` and add it to a project's `media` list |
| Process steps, "Why work with me", FAQs | `PROCESS`, `WHY`, `FAQS` |
| Testimonials | `TESTIMONIALS` (the section stays hidden until you add real ones) |
| Colors | The `:root` variables at the top of the `<style>` block |
| Page title and description | The `<head>` tags in `index.html` |

### Replacing sample projects with real work

The six projects are labeled Concept Project, Demo Project, or Sample Workflow. When you have real, approved work:

1. Change `label` (for example to `"Client Project"`).
2. Fill `outcomes` with results you can verify. Leave it empty if you have none.
3. Set `image` to a screenshot path, for example `"images/project-1.png"`.

Before publishing any screenshot, remove or blur client names, emails, phone numbers, deal values, and any other private data. Do not publish client work without permission.

## Make the contact form deliver messages

A static page cannot send email by itself. Until you connect a form service, the form validates the visitor's input, then shows their message with buttons to send it by WhatsApp or email. It never claims a message was sent.

To receive submissions directly:

1. Create a free form endpoint with a service such as Formspree, Basin, or Web3Forms, and point it to oolabiyi5114@gmail.com.
2. Paste its URL into `CONFIG.formEndpoint`.
3. In the service's dashboard, turn on its spam protection (CAPTCHA or Turnstile) and add your domain to its allowed list.

Private keys must never go in the page. A form endpoint URL is designed to be public. If a service gives you a secret token, use a server-side function (for example a Netlify or Cloudflare function) and store the token as an environment variable there.

The form already includes a hidden honeypot field that catches basic bots.

## Deploy

Any of these work, and all have free plans:

- **Netlify:** drag this folder onto https://app.netlify.com/drop.
- **Cloudflare Pages / Vercel:** create a project, upload the folder, and leave the build command empty.
- **GitHub Pages:** push the folder to a repository and enable Pages in its settings.

Then connect your domain, replace `YOUR-DOMAIN.com`, and submit `sitemap.xml` in Google Search Console.

## Before you go live checklist

- [ ] Replace `YOUR-DOMAIN.com` everywhere
- [ ] Add your photo and logo (optional)
- [ ] Remove tools from `PLATFORMS` that you cannot support
- [ ] Connect `CONFIG.formEndpoint`
- [ ] Review the Privacy Policy text with a qualified adviser
- [ ] Add social links if you want them shown

## Notes

- The Privacy Policy is a plain template. It is not legal advice.
- Product names are trademarks of their owners. The site states that no partnership is implied.
- The pipeline and workflow visuals in the hero are illustrations with sample names, not real client data.

## Portfolio media

- Videos live in the `videos/` folder. Extract the zip before opening `index.html`, otherwise the videos cannot load (the thumbnails and screenshots are built into the page and always show).
- Client names, emails, phone numbers, deal names, and customer data were blurred, cropped, or cut from every screenshot and video. The recordings have no sound. Check any new material the same way before publishing.
- The monday.com board and Zoho Campaigns report are labeled Sample Board and Sample Report because they look like those vendors' own demo material. Replace them with your own work when you have it.
=======
# Daret-Portfolio-Website
>>>>>>> 73b264e50bfe85101a09baa0302db9b61b713422
