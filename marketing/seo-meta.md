# SEO Metadata — Tri-State As-Built Pros

## Homepage

**Title tag (≤60 chars):**
As-Built Surveys & Drawings NY, NJ, CT | Tri-State As-Built Pros

**Meta description (≤155 chars):**
Fast, accurate as-built surveys & CAD drawings for NY, NJ & CT. Close out your permit the first time. Licensed surveyors. Free quotes.

**Suggested URL:** `/` (homepage)

---

## Services Landing Page

**Title tag:**
As-Built Survey & Drawing Services | Tri-State As-Built Pros

**Meta description:**
As-built surveys, CAD drafting, elevation certificates, foundation surveys & ALTA surveys across the tri-state area. Get a free quote today.

**Suggested URL:** `/services`

---

## Location Pages (create one per major service area for local SEO)

Template — replace {CITY} / {COUNTY}:

**Title tag:**
As-Built Surveys in {CITY}, {STATE} | Tri-State As-Built Pros

**Meta description:**
Licensed as-built surveyors serving {CITY} & {COUNTY}. Fast turnaround, permit-ready drawings. Call now for a free quote.

**Suggested URLs:**
- `/as-built-surveys-nyc`
- `/as-built-surveys-long-island`
- `/as-built-surveys-westchester`
- `/as-built-surveys-bergen-county-nj`
- `/as-built-surveys-fairfield-county-ct`

---

## Primary Keywords

- as-built survey [city/state]
- as-built drawings
- as-built survey near me
- elevation certificate NY / NJ / CT
- foundation survey
- permit close out survey
- ALTA survey tri-state
- land surveyor NYC / NJ / CT
- site plan for permit
- CAD drafting as-built

## Secondary / Long-Tail Keywords

- how long does an as-built survey take
- as-built survey for DOB approval
- as-built survey cost NYC
- foundation location survey before framing
- FEMA elevation certificate for flood insurance
- as-built survey for home addition permit

---

## Structured Data (Schema.org) — recommended

Add `LocalBusiness` (or more specifically `ProfessionalService`) JSON-LD to the homepage `<head>`:

```json
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Tri-State As-Built Pros",
  "description": "Licensed as-built surveys, CAD drawings, and permit close-out services across New York, New Jersey, and Connecticut.",
  "areaServed": ["New York", "New Jersey", "Connecticut"],
  "url": "https://tristate-asbuilt-pros.netlify.app/",
  "telephone": "+1-XXX-XXX-XXXX",
  "priceRange": "$$"
}
```

## Other On-Page SEO Checklist

- [ ] One H1 per page matching the primary keyword intent
- [ ] `sitemap.xml` submitted to Google Search Console
- [ ] `robots.txt` allowing crawl of all public pages
- [ ] Image `alt` text describing survey type + location
- [ ] Internal links from blog/service pages back to location pages
- [ ] Mobile page speed under 2.5s (Netlify + image compression should help)
- [ ] NAP (Name, Address, Phone) consistent across site, Google Business Profile, and directories
