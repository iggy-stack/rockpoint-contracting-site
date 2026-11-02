# Rockpoint Contracting – one-page site (preview)
Static `index.html`, no build step. Deployed to Vercel as a preview URL only; rockpointcontracting.com.au NOT attached, DNS untouched.

## To replace before going live
- **Photos:** the 6 grey striped blocks in "Our Work" are placeholders ("PHOTO TO BE REPLACED"). Swap for real Rockpoint job photos.
- **Logo:** the round badge is a simple placeholder SVG, not the real logo. Replace with the official logo file.
- **Form backend:** the contact form only opens the visitor's email app (mailto to iggy@rockpointcontracting.com.au). Hook up a real backend (e.g. Formspree/Resend/Vercel function) to receive submissions.
- **Areas list:** generic Sydney regions; adjust if needed.
- **Domain:** attach rockpointcontracting.com.au in Vercel + update DNS at the registrar when approved.

## Gallery
Real job photos live in `images/` (resized to max 1600px, JPEG q80, lazy-loaded with width/height and alt text). Captions only; no client names or locations.
