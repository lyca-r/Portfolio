HOW TO USE THIS PORTFOLIO SITE
================================

WHAT'S INCLUDED
----------------
- index.html          → the whole site (content, styling, and behavior in one file)
- certificates/        → folder where you put your certificate images/PDFs

There's no build process and no server needed — it's a plain static website.


1) EDIT YOUR CONTENT
----------------------
Open index.html in any text editor (Notepad, VS Code, TextEdit) and change:
- Your name, title, and summary near the top ("Alex Morgan", the <h1>, and the
  paragraph under it)
- The About section text and the stat list (location, focus, tools)
- The Experience timeline entries (dates, roles, companies, descriptions)
- The Projects section
- Your email / LinkedIn / GitHub links in Contact

Everything is plain HTML text — no code knowledge required to change wording,
dates, or links. Just don't delete the <tags> around each piece of text.


2) ADD YOUR CERTIFICATES
---------------------------
a. Save each certificate as an image (.png/.jpg) or a PDF.
b. Put the file inside the "certificates" folder next to index.html.
c. Open index.html, find the CREDENTIALS list near the bottom (search for
   "CREDENTIALS = ["), and add one entry per certificate, e.g.:

     {
       title: "AWS Certified Solutions Architect",
       issuer: "Amazon Web Services",
       date: "2025",
       file: "certificates/aws-solutions-architect.png",
       verifyUrl: ""   // optional link to verify the credential online
     }

d. Save the file. Refresh the page in your browser — the new certificate
   appears automatically as a card, and clicking it opens a larger preview.

If a filename doesn't match a real file, the card will show a small note
telling you which file is missing, instead of a broken image.


3) PREVIEW IT ON YOUR COMPUTER
---------------------------------
Just double-click index.html to open it in your browser. That's enough to
check your edits before publishing.


4) PUBLISH IT ONLINE (FREE) — pick one:

GitHub Pages
  1. Create a free GitHub account and a new repository, e.g. "portfolio".
  2. Upload index.html, the certificates/ folder, and resume.pdf to it.
  3. Repository Settings → Pages → set source to the main branch.
  4. Your site goes live at https://yourusername.github.io/portfolio

Netlify (drag-and-drop, no account setup needed for a quick preview)
  1. Go to netlify.com and sign up (free).
  2. Drag the whole "portfolio" folder onto the deploy page.
  3. You'll get a live link in seconds; you can add a custom domain later.

Either option gives you a clean, fast, professional URL — much better for a
job application than a raw script or app URL.


5) ADD YOUR RÉSUMÉ
---------------------
Put a file named "resume.pdf" in the same folder as index.html — the
"Download Résumé" buttons already link to it.


NOTES
------
- This is a static site: only you edit the content (by editing the file),
  visitors can't upload anything to it. That's normal and expected for a
  job-application portfolio — you're the only one who should be adding
  credentials.
- If you'd ever want a public-facing upload form (e.g., for a team, not a
  personal résumé site), that requires a small backend and is a different
  kind of project — ask if you'd like help setting one up.
