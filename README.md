# FraudVision AI

**Pause. Check. Stay safe.**

FraudVision AI is a browser-based tool that checks SMS, WhatsApp, and email
messages for scam patterns. Paste text directly or upload a screenshot —
the app uses OCR to read the image locally and scores the message as
Safe, Suspicious, or High Risk, with reasons and advice for each flag.

## Features
- Paste-to-check or screenshot upload (with OCR via Tesseract.js)
- Risk scoring with flagged-word highlighting and plain-language reasons
- Example messages (prize scam, bank KYC scam, genuine OTP) to try instantly
- Sign-up / sign-in with a per-user scan history
- Admin dashboard (source breakdown, verdict counts, CSV export)
- Multi-language interface (English, Hindi, Tamil)
- Light/dark theme

## Tech
Single self-contained HTML file — HTML, CSS, and vanilla JavaScript, with
[Tesseract.js](https://github.com/naptha/tesseract.js) loaded from a CDN
for OCR. No build step, no backend: accounts and scan history are kept in
the browser's local storage.

## Running it
Just open `index.html` in a browser, or serve the folder with any static
host (see Deployment below).

## Deployment
Deployed on Vercel as a static site: https://vercel.com

## Disclaimer
This is a student project and an early-warning tool, not a guarantee.
It is not a substitute for verifying with your bank or the relevant
service directly.

## License
MIT — see [LICENSE](LICENSE).
