INSTRUCTIONS — How to install these favicon files
==================================================

STEP 1 — UPLOAD ALL FILES TO YOUR GITHUB REPO
---------------------------------------------
Upload every file below to the ROOT of your bethelyouthunited repo
(same folder as index.html). REPLACE any existing files with the same name.

Files to upload:
  ✓ favicon.ico                        (replaces existing)
  ✓ favicon-16x16.png                  (replaces existing)
  ✓ favicon-32x32.png                  (replaces existing)
  ✓ favicon-48x48.png                  (NEW)
  ✓ favicon-96x96.png                  (NEW)
  ✓ favicon-192x192.png                (NEW)
  ✓ favicon-512x512.png                (NEW)
  ✓ apple-touch-icon.png               (replaces existing)
  ✓ android-chrome-192x192.png         (NEW)
  ✓ android-chrome-512x512.png         (NEW)
  ✓ logo.png                           (NEW — for Google structured data)
  ✓ logo.jpg                           (optimized replacement for existing)
  ✓ site.webmanifest                   (NEW)


STEP 2 — UPDATE YOUR index.html
-------------------------------
Open index.html in GitHub. Find the favicon block in the <head>
(it currently has several <link rel="icon"...> lines).

REPLACE the whole block with the contents of HEAD_SNIPPET_to_paste.html

Also change this line in your JSON-LD structured data:
    "logo": "https://bethelyouthunited.com/logo.jpg"
to:
    "logo": "https://bethelyouthunited.com/logo.png"

And change:
    "image": "https://bethelyouthunited.com/logo.jpg"
to:
    "image": "https://bethelyouthunited.com/logo.png"


STEP 3 — COMMIT AND PUSH
------------------------
Commit all the changes. GitHub Pages will redeploy in 1-2 minutes.


STEP 4 — VERIFY THE FILES ARE LIVE
----------------------------------
Open each of these URLs in your browser. Each should show the BETHEL logo:

  https://bethelyouthunited.com/favicon.ico
  https://bethelyouthunited.com/favicon-32x32.png
  https://bethelyouthunited.com/favicon-192x192.png
  https://bethelyouthunited.com/apple-touch-icon.png
  https://bethelyouthunited.com/logo.png

If any gives a 404, re-upload that file.


STEP 5 — FORCE-REFRESH YOUR BROWSER TAB FAVICON
-----------------------------------------------
Open https://bethelyouthunited.com/ in an INCOGNITO/PRIVATE window.
Look at the browser tab — you should now see your BETHEL logo there.
If yes, you're done with the technical side.


STEP 6 — ASK GOOGLE TO RE-CRAWL
-------------------------------
1. Go to https://search.google.com/search-console
2. URL Inspection → paste: https://bethelyouthunited.com/
3. Click "Request Indexing"

Google will re-crawl within a few days. The favicon will appear in
search results within a few days to a couple weeks AFTER that.


WHY THE LOGO WASN'T SHOWING BEFORE
----------------------------------
Your previous favicon files were likely generic/blank (not generated
from your actual logo). Even if Google re-crawled, it would have
rendered whatever was in those files. These new files are ALL
generated directly from your BETHEL YOUTH UNITED logo at correct
sizes with 1:1 aspect ratio — which Google requires.

Also note: your Google search result shows "http://bethelyouthunited.com"
(not https). This is just how Google displays it — the actual site
redirects to HTTPS. Not a problem for favicons.
