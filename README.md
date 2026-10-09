# CallPilot AI — early-stage MVP

This is a static, bilingual (Telugu/English) landing page with a browser-only scripted voice demo for real-estate enquiries.

## What works
- Responsive landing page and feature sections
- Type a question and receive a scripted demo response
- Browser speech recognition when supported by the browser
- Browser speech synthesis when a matching voice is available
- Contact form prepares an email draft only after you configure a real recipient

## Honest limitations
- This is a prototype, not a production AI agent.
- Answers are predefined; there is no LLM or live property database.
- It does not place or receive telephone calls.
- Speech recognition support and Telugu voice availability vary by browser/device.
- The contact form does not send or store information until you configure a real email recipient.
- Do not collect sensitive customer information in this demo.

## Preview locally
Open `index.html` in a current desktop browser. Microphone access may require localhost or HTTPS; if voice input does not work, test with the text input.

## Publish for free
1. Create a GitHub account if you do not already have one.
2. Create a public repository named `callpilot-ai-demo`.
3. Upload `index.html` and `README.md`.
4. In the repository, open Settings → Pages.
5. Choose deploy from branch, select `main` and `/ (root)`, then save.
6. Use the published URL as the initial demo URL. A custom domain is optional and usually costs money.

You can also use Netlify's manual deploy by dragging the folder into its deploy area.

## Before publishing
1. Search for `hello@YOURDOMAIN.com` in `index.html` and replace it with a real email address you control.
2. Replace any claims that do not match your actual product status.
3. Add a privacy notice before collecting real user data.
4. Do not claim live listings, CRM integrations, phone support, or customer results unless implemented and verified.
5. `CallPilot AI` is a working name only; check domain and trademark availability before committing to it.
