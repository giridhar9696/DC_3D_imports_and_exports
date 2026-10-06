# DC Imports and Exports

Marketing website for DC Imports and Exports, a freight forwarding and logistics business serving international supply chains.

## Highlights

- Freight forwarding, customs brokerage, transport, warehousing, and integrated logistics content
- Responsive static pages for services, industries, company information, contact, policies, and insights
- Green DC branding with custom favicon and animated particle wordmark
- Contact form routed to WhatsApp for quick enquiries

## Run locally

Serve this folder with any static web server. For example:

```powershell
cd united-carriers-master
python -m http.server 8000
```

Then open <http://localhost:8000/>.

## Project structure

- `index.html` — homepage
- `contact.html` — contact form and office details
- `services.html` — logistics services
- `industries.html` — industry capabilities
- `about.html`, `careers.html`, `qhse.html` — company pages
- `assets/`, `css/`, and `js/` — site media, styles, and scripts

## Deployment

This is a static site. Publish the contents of this directory to a static hosting provider or web server; no build step is required.
