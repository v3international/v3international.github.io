# V3 Middle East Engineering Consultants — Company Context

This file gives Claude (and anyone else working in this repo) working context
about V3 so that question-bank content, reports, and other generated material
reflect what the company actually does, rather than generic industry filler.
Keep it updated — Claude reads repo files automatically every session, so
edits here take effect immediately with no integration work.

## Status of this file
Populated from V3's real 2026 Company Profile (48-page PDF, provided
directly) plus the Expertise page pasted earlier and the divisions/
disciplines already encoded in `index.html`. Direct fetch of
v3international.com is still blocked by this session's network egress
policy, but the PDF profile covers everything the website would have
(history, services, real project portfolio) — no further website access
needed for this purpose.

## Company profile

- **Full legal name:** V3 Middle East Engineering Consultants Company
- **Motto:** "Visio, Vertere, Virtute" — "The Vision to Transform with Excellence"
- **Classification:** Class 1 Architecture/Engineering Consultancy in Saudi Arabia (earned 2022) — the top licensing tier, qualifying the firm for large-scale, complex projects
- **Legal structure:** LLC (transitioned from a partnership in 2023)
- **Offices:** Jeddah (859-Unit No.24, Jeddah 22234-454) and Riyadh (Riyadh Avenue, Floor 4, Prince Faisal Bin Turki Bin). A Jubail (Eastern Province) branch opened in 2015 for industrial-sector work; not listed as a current office in the profile's office-location section — confirm with the team whether it's still active.
- **Values:** Committed to Excellence, Focused on Clients, Dedicated to Employees
- **Mission:** "Employee commitment, talent, and diversity together with strategic planning and implementation will enable us to continue to grow into a preferred provider of engineering solutions whose capabilities are unrestricted by project scope, market, or delivery system."

### History
- **1983** — V3 Companies founded in Woodridge, Illinois, USA (the origin of the "V3" name and the firm's US roots)
- **2001** — V3 Al-Esayi founded in Jeddah by Houssam Jabour (partnership with V3 Companies and Saeed Omar Alesayi Company) — start of KSA operations
- **2004** — V3 Al-Esayi expands to Riyadh
- **2008** — Abdullah Al Meheini Office for Civil Engineering and Project Management becomes V3's Middle East partner
- **2012** — Rebranded V3 Middle East Engineering Consultants Company; Aidroos Albar joins as partner
- **2015** — Jubail (Eastern Province) branch opens, targeting the industrial sector
- **2018** — Georges Hallak appointed CEO
- **2020** — Navigated COVID-19; restructured for efficiency
- **2022** — Earned Class 1 status
- **2023** — Fire and Life Safety consultancy services added; converted to LLC; Somou Al Mamlaka joins as third local partner

## Service lines

1. **Architecture and Engineering Design Consultancy** — Architectural, Structural, Civil, Mechanical (HVAC, Plumbing), Electrical (Power, ELV) design. Project types: Residential, Hospitality, Mixed-Use, Commercial/Office, Industrial, Educational/R&D, Healthcare, Parks & Recreational. → maps to the "Design and AOR" division
2. **Project Management and Construction Supervision** — Project Documentation, Change Orders/Pay Estimates, Construction Supervision, Material Testing Inspection, Statutory Relations, Record Drawings, Construction Layout, Measurement of Quantities, Cost Control, Schedule Prep & Analysis, Constructability Reviews, Cost Estimating, Claim Resolution, Owner's Representation → maps to the "Construction Supervision" division
3. **Fire and Life Safety Consultancy** — Life Safety Review, Fire Protection, Fire Alarm, Emergency Lighting, Smoke Control, Exit Signage, Generator systems (design side); Compartmentation, Egress, Fire Alarm Cause & Effect, detector/pump/sprinkler/riser pressure & flow testing (construction-supervision side). References SBC, IBC, IFC, NFPA and local Civil Defense requirements → maps to FLS/Fire Alarm/Fire Protection/Smoke Control Engineer disciplines
4. **Municipal Consulting Services** — Plan Review & Inspection, Transportation Analysis & Design, Roadway Design, Structural Design, Streetscape Design, Utility System Design, Traffic Services, Parking, Lighting Design, Survey & Mapping, GIS, Water Resources, Ecology & Wetland Services, Sustainable Design/Build. **Not currently reflected as its own discipline in `DISC_MAP`** — real, substantial work exists (see Dam & Well Survey, Misk Creative Hub street upgrade below) with no matching question bank
5. **Survey and Mapping Services** — Topographic Mapping, ALTA/ACSM Boundary Surveys, High-Definition Scanning, Hydrographic Mapping, Route Location Surveys, GPS Machine Control, As-Built Surveys, Control Network/Densification, Houseline Services. **Also not reflected as its own discipline** — same gap as above

## Regional & project-type context — READ BEFORE WRITING TECHNICAL CONTENT

This is the single most important section for calibrating question realism.
V3's real project portfolio (48 named projects in the 2026 profile) is
**heavily concentrated in Riyadh** — roughly two-thirds of showcased
projects — with a real but smaller share in Jeddah, a small Eastern
Province presence, and a handful of Red Sea coastal giga-projects.

### Riyadh (dominant — interior/desert conditions)
Solitaire Mall, Al Urubah Park, Misk Schools, Misk Creative Hub & Irqah
Street Upgrade, Wes Plot A Mall, Al Faisaliah Hotel & Spa, Al Faisaliah
Mall, Innovation Park, The 303, Saudi Olympic Training Center, Lulu
Hypermarket, Women's Spa by ESPA, Toki Restaurant, NCA Academy, Royal
Diriyah Golf Clubhouse, and the Diriyah heritage-district cluster (Diriyah
Gate Bulk Excavation, Bujairi Public Realm & Infrastructure, Bujairi
Parking P1, Samhan Parking P2).

**Groundwater is deep in Riyadh — a high-water-table dewatering scenario is
genuinely uncommon experience here**, which is exactly the feedback your
civil engineer gave. What IS a real, recurring Riyadh condition, backed
directly by these projects:
- **Very large, deep bulk excavations in desert/rock ground**: Diriyah Gate
  — 8,000,000 m³, 28 m deep, including a 26 m-deep Metro Station cut;
  Solitaire Mall — 947,200 m³, 16 m deep; Bujairi Parking P1 — 300,000 m³,
  16 m deep; Samhan Parking P2 — 400,000 m³, 16 m deep. Deep-excavation
  shoring/support is far more realistic Civil content for V3 than
  dewatering.
- **Heritage/UNESCO-sensitive construction**: the entire Diriyah district
  sits beside the UNESCO World Heritage At-Turaif site — construction
  adjacent to protected heritage assets is a recurring, real V3 condition
  (this validates keeping a heritage-sensitivity scenario, though the
  existing one is framed around tunnelling near a mosque — consider
  reframing around a Diriyah-style bulk-excavation-near-heritage-site
  scenario instead, which is literally what V3 does).
- **Wells and water infrastructure DO appear inland**, just differently
  framed: the Dam and Well Survey project (Irqa, Riyadh, for Diriyah
  Company) covered condition surveys of a detention dam and 274 wells —
  groundwater/well engineering is real Riyadh-area work, but as
  infrastructure assessment, not excavation dewatering.

### Jeddah (real, secondary — coastal Red Sea conditions)
Jeddah Waterfront (Corniche regeneration), Zahid Business Park, Crowne
Plaza Hotel renovation, Aramex BTS Facility (near Jeddah Islamic Port),
Light Industries Area in Asfan.

This is where a **high-water-table / dewatering scenario is genuinely
realistic** — coastal, reclaimed, and near-port land. If dewatering content
stays in the Civil bank, it should be explicitly scoped to a coastal/Jeddah
context (or Eastern Province — see below) rather than presented as
default/universal KSA experience.

### Eastern Province (real, smaller share — coastal Gulf conditions)
Jalmuda Central Park (Jubail, for Royal Commission of Yanbu & Jubail — 3
million m² coastal park/residential masterplan), King Salman Energy Park
"SPARK" (50 km² industrial city for Saudi Aramco).

Also coastal/high-water-table territory — same caveat as Jeddah.

### Red Sea giga-projects (niche but real — remote coastal/marine)
Shebara Hotel (Red Sea Global, Sheybarah Island — cantilevered over coral
reefs, LEED-Platinum), Bay La Sun Waterfront Mall & Hotel (Rabigh, King
Abdullah Economic City), Banyan Tree Al Ula (note: Al Ula itself is
interior/desert rock terrain, not coastal, despite being a luxury resort).

### What this means for question-writing going forward
- Don't default to generic "textbook" civil engineering scenarios — check
  them against this real geographic split first.
- Deep excavation/shoring in arid ground, heritage-adjacent construction,
  and large mixed-use/hospitality/institutional developments are the
  **safe, high-confidence default** for Civil content (matches the
  majority Riyadh-based work).
- Coastal/water-table content isn't wrong to include, but should be
  explicitly framed as a coastal-project scenario, not a universal one —
  and sized in the question mix to roughly reflect how much of V3's real
  work is coastal vs. interior (a minority share, not the default).
- Municipal Consulting and Survey & Mapping are real service lines with
  real delivered projects but no discipline/question bank at all yet —
  worth flagging to the team as a gap beyond the current Civil rework.

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

## How this file is used
When writing or revising exam question banks, use this context to:
- Weight question topics toward the project types V3 actually delivers
  (see Regional & project-type context above)
- Avoid generic industry content that doesn't reflect V3's real scope
- Calibrate entry vs. senior difficulty against the seniority V3 actually hires for

This file does not feed anything automatically — it is read by whoever
(human or Claude) is working in this repo. It is not synced from the live
website; update it by hand when company information changes.
