# Winner Group website — six design versions

Open `index.html` for a menu of the six versions.

```
WHAT IS IN THIS FOLDER
  index.html            A menu linking to the six versions (for review only).
  1-navy-brass/         Version 1
  2-heritage-red/       Version 2
  3-green-sidebar/      Version 3
  4-regional-teal/      Version 4
  5-bold-blue/          Version 5
  6-mobile-first/       Version 6
Each version folder is complete on its own: one index.html and an images folder.

HOW TO HOST
  To review all six: upload the whole folder to your web space (for example
  public_html/preview/) and open that address.
  To go live with one design: upload the CONTENTS of that version's folder
  (index.html and the images folder) to the root of your domain.
  It is plain HTML, CSS and JavaScript. No database, PHP or build step is needed.
  Any host works: cPanel, Netlify, GitHub Pages, Cloudflare Pages, S3.

WHAT TO EDIT BEFORE GOING LIVE (inside the chosen index.html)
  1. Estimator rates. Search for "EDIT HERE". The four numbers in WINNER_RATES
     are placeholders, not Winner's real rates.
  2. Enquiry email. WINNER_ENQUIRY_EMAIL, just below the rates. The form opens
     the visitor's email app with the message filled in; it does not send from
     a server.
  3. Versions 4, 5 and 6: search for "[WhatsApp number]" and "[LINE ID]" and
     replace them, and change href="#contact" on those two buttons to
     https://wa.me/<number> and your LINE link.
  4. Translations (Chinese, Thai, Malay, Tamil) should be checked by native
     speakers. They are in the "dict()" block near the bottom of index.html.

GOOD TO KNOW
  - Language: buttons on the page switch between English, Chinese, Thai, Malay
    and Tamil. The choice is remembered on the visitor's device. You can link
    straight to a language with ?lang=zh, ?lang=th, ?lang=ms or ?lang=ta.
  - Fonts load from Google Fonts, so visitors need internet access to see the
    intended typefaces (the pages fall back to system fonts if blocked).
  - Animations: sections fade and rise in as you scroll, cards lift on hover,
    estimator figures pulse when they change. All motion switches off for
    visitors whose device is set to "reduce motion".
  - The English text is already in the HTML, so the page is readable by search
    engines and by visitors with JavaScript turned off.
```
