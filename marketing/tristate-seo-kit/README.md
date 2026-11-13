# TriState As-Built Pros: SEO kit (not live)

These files are ready to paste into the TriState site (tristate-asbuilt-pros.netlify.app).
This repo does not hold the site's own files, so nothing here changes the live site.
Someone has to copy them into the site and redeploy it on Netlify.

## What was found (Nov 13, 2026)
- The pages themselves are in good shape: every page has its own title, description, H1 and canonical.
- A web search for the site returned none of its pages, so it looks like Google has not indexed it yet.
- No business details (schema) for Google were found on the homepage.
- The 10 town and county pages are almost orphaned: the homepage links to none of them.
- Pages link to `/new-jersey` but the canonical tags and sitemap say `/new-jersey.html`.
- The quote email uses the subject "As-Built Quote Request", so its leads can't be told apart from other emails.
- The site is on a free netlify.app address. A real domain (for example tristateasbuiltpros.com) would be easier to trust, remember and rank.

## Changes, in order
1. **Quote tracking:** in every "Email for a Free Quote" link, change only the subject:
   `subject=As-Built Quote Request` → `subject=Quote%20request%20-%20TriState%20site`
   Keep the email address and body exactly as they are. Then every lead from this site arrives with the subject
   "Quote request - TriState site", and a Gmail search for that subject counts them.
2. **Homepage head:** replace the old title, description and og: tags with `head-homepage.html`.
3. **Footer links:** add `footer-area-links.html` to the footer of every page.
4. **Internal links:** change `/new-york`, `/new-jersey`, `/connecticut`, `/jersey-shore-nj`, `/monmouth-county-nj`,
   `/ocean-county-nj` to the same address with `.html`, so they match the canonical tags.
5. **Sitemap:** replace `sitemap.xml` on the site with this one (same pages, new dates).
6. **After it's live:** in Google Search Console (the site already has a verification tag), submit the sitemap and
   ask Google to index the homepage. This needs the owner's sign-in.
