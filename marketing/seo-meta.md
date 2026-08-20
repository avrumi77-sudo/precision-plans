# SEO Metadata — Tri-State As-Built Pros

## Homepage

**Title tag (≤60 chars):**
As-Built Surveys for Architects, Designers & Contractors

**Meta description (≤155 chars):**
As-built surveys & CAD drawings for architects, designers & contractors in Lakewood, Toms River, Jackson & Brooklyn. Free quotes, fast turnaround.

**Suggested URL:** `/` (homepage)

---

## Services Landing Page

**Title tag:**
As-Built Survey & Drawing Services | Tri-State As-Built Pros

**Meta description:**
As-built surveys, CAD drafting, elevation certificates, foundation surveys & ALTA surveys in Ocean County, NJ & Brooklyn, NY. Get a free quote today.

**Suggested URL:** `/services`

---

## Location Pages (create one per major service area for local SEO)

Template — replace {CITY} / {COUNTY}:

**Title tag:**
As-Built Surveys in {CITY}, {STATE} | Tri-State As-Built Pros

**Meta description:**
Licensed as-built surveyors serving {CITY} & {COUNTY}. Fast turnaround, permit-ready drawings. Call now for a free quote.

**Suggested URLs:**
- `/as-built-surveys-lakewood-nj`
- `/as-built-surveys-toms-river-nj`
- `/as-built-surveys-jackson-nj`
- `/as-built-surveys-brooklyn-ny`

---

## Primary Keywords

- as-built survey Lakewood NJ
- as-built survey Toms River
- as-built survey Jackson NJ
- as-built survey Brooklyn
- as-built drawings
- as-built survey near me
- elevation certificate Ocean County NJ
- foundation survey
- permit close out survey
- ALTA survey Ocean County
- land surveyor Lakewood / Toms River / Brooklyn
- site plan for permit
- CAD drafting as-built
- as-built survey for architects
- as-built drawings for designers
- as-built survey for contractors

## Secondary / Long-Tail Keywords

- how long does an as-built survey take
- as-built survey for township permit approval
- as-built survey cost Ocean County NJ
- foundation location survey before framing
- FEMA elevation certificate for flood insurance
- as-built survey for home addition permit Jackson NJ
- as-built survey Brooklyn DOB approval

---

## Structured Data (Schema.org) — recommended

Add `LocalBusiness` (or more specifically `ProfessionalService`) JSON-LD to the homepage `<head>`:

```json
{
  "@context": "https://schema.org",
  "@type": "ProfessionalService",
  "name": "Tri-State As-Built Pros",
  "description": "As-built surveys and CAD drawings for architects, designers, and contractors in Lakewood, Toms River, Jackson & Brooklyn.",
  "areaServed": ["Lakewood, NJ", "Toms River, NJ", "Jackson, NJ", "Brooklyn, NY"],
  "url": "https://tristate-asbuilt-pros.netlify.app/",
  "telephone": "+1-845-907-5025",
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
