# V3 Middle East Engineering Consultants — Company Context

This file gives Claude (and anyone else working in this repo) working context
about V3 so that question-bank content, reports, and other generated material
reflect what the company actually does, rather than generic industry filler.
Keep it updated — Claude reads repo files automatically every session, so
edits here take effect immediately with no integration work.

## Status of this file
Seeded from the divisions/disciplines already encoded in `index.html` (real,
verified data), plus real content pasted from v3international.com's
Expertise page. Still missing: Our Projects page content, Who We Are page
(history/team size), and the 5 individual service pages — paste those and
this file gets filled in further. Direct fetch of the live site is blocked
by this session's network egress policy.

## Company profile

- **Full legal name:** V3 Middle East Engineering Consultants (per site
  copyright footer)
- **Tagline:** "Expertise That Transforms" — "From concept to completion,
  our expert engineers guide your projects to success."
- **Stated values (from Expertise page):** "V3's long legacy has been built
  on our top priorities of unsurpassed quality, commitment to excellence,
  and focus on clients, while taking immense pride in our success and
  accomplishments that we attribute to our most valuable asset, our
  dedicated team."
- **Founded / history:** TO FILL IN (paste Who We Are page)
- **Head office / regional offices:** TO FILL IN
- **Sectors served:** TO FILL IN (paste Our Projects page)
- **Notable projects:** TO FILL IN (paste Our Projects page)
- **Team size:** TO FILL IN
- **Certifications / accreditations:** TO FILL IN

## Service lines (source: v3international.com/expertise/)

1. **Architecture and Engineering Design Consultancy** — maps to the
   "Design and AOR" division in the exam system
2. **Project Management and Construction Supervision** — maps to the
   "Construction Supervision" division in the exam system
3. **Fire and Life Safety** — maps to FLS / Fire Alarm / Fire Protection /
   Smoke Control Engineer disciplines under Design and AOR
4. **Municipal Consulting Services** — NOT currently reflected as its own
   discipline anywhere in `DISC_MAP`; may warrant its own question bank if
   V3 hires for it directly
5. **Survey and Mapping Services** — also NOT currently reflected as its
   own discipline in `DISC_MAP`; closest existing discipline is Civil/
   Infrastructure, but surveying is its own technical competency and may
   deserve its own bank rather than being folded into Civil

(Full detail on each service line lives on its own `/service/...` page —
paste those too if you want the question banks to reflect what each
service actually involves, beyond the one-line description on Expertise.)

## Divisions & Disciplines (source of truth: `DISC_MAP` in index.html)

### Construction Supervision
Architectural, Civil, Contracts, Document Controller, Electrical,
Environmental, HSE, Infrastructure, Landscape, Mechanical, Planning, QS,
Structural, Sustainability, Testing & Commissioning

### Design and AOR
Electrical, FLS, Fire Alarm, Fire Protection, Mechanical,
Smoke Control Engineer, Structural

### Administration
Business Development, Quality Department, Graphic Designer, IT, Logistics,
Marketing Specialist, Web Developer

(A fourth division icon, "BD & Contracts", exists in the UI but its
disciplines currently live under Administration/Construction Supervision —
confirm with the team whether this should be split into its own division.)

## Company profile — TO FILL IN
- **Full legal name:**
- **Founded / history:**
- **Head office / regional offices:**
- **Sectors served** (e.g. government, residential, infrastructure, giga-projects):
- **Notable projects:**
- **Mission / values:**
- **Team size:**
- **Certifications / accreditations:**

## How this file is used
When writing or revising exam question banks, use this context to:
- Weight question topics toward the project types V3 actually delivers
- Avoid generic industry content that doesn't reflect V3's real scope
- Calibrate entry vs. senior difficulty against the seniority V3 actually hires for

This file does not feed anything automatically — it is read by whoever
(human or Claude) is working in this repo. It is not synced from the live
website; update it by hand when company information changes.
