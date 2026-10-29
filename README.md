# AksharMitra — अक्षरमित्र

**Tagline:** अक्षरांपासून ज्ञानाकडे!

AksharMitra is a free, mobile-friendly Marathi–English learning starter for children in Maharashtra.

## Current prototype features
- Marathi vowel recognition with browser speech synthesis
- Marathi digits to English digit matching
- English number spelling practice (0–9)
- Five-question mini quiz
- Local progress and points saved in the browser
- Responsive desktop and mobile layout

## Run locally
Open `index.html` in a modern browser. No build step or secrets are required.

## Project direction
This is the first UI/learning prototype. Next milestones can add reviewed Marathi curriculum content, full barakhadi, writing practice, grade/lesson paths, accessibility and offline PWA support, teacher/admin workflows, and safe persistence if needed.

## Important
Educational content and pronunciations should be reviewed by Marathi and primary-school teachers before public release. Progress currently stays in the learner's browser; there is no backend, login, teacher dashboard, or cloud database yet.


## Touch-friendly tracing practice
- Trace uppercase English letters A–Z using a finger on mobile or a mouse on desktop.
- Practice Marathi vowels (स्वर) and consonants (व्यंजने), including क्ष and ज्ञ.
- Clear the drawing and move to the next letter; practice count stays in the browser.


## Tracing improvements
- Live, colorful ink follows finger or mouse movement on the tracing canvas.
- Capital English A–Z, lowercase English a–z, Marathi vowels and consonants.
- Small English words (cat, bat, dog, sun, pen, map, hen, cup, red, box) with left-to-right direction arrows.

## Publish with GitHub Pages
The repository includes `.github/workflows/deploy-pages.yml` to publish the root static site automatically. The first-time Pages site enablement requires repository Pages settings permission. Open Settings → Pages and select **GitHub Actions** as the build/deployment source; then the workflow can deploy on each push to `main`.
