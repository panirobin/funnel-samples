# Research — Tim Noldin / Noldin Consulting

Working notes. Not linked publicly. Every deliverable in this folder was written from
this file.

---

## Identity

| | |
|---|---|
| Prospect | Tim Noldin — Führungspsychologe, M.Sc. |
| Company | Noldin Consulting (`noldin-consulting.com`) |
| Sells | Leadership consulting + team systems to Mittelstand owners and executives |
| Positioning (verbatim) | "Mache dein Unternehmen zu einem Umfeld – in dem alle Vollgas geben!" |
| Sub (verbatim) | "Wir zeigen dir, wie du durch **klare Systeme** und **souveräne Führung**, ein **leistungsstarkes Team** aufbaust, ohne im Tagesgeschäft unterzugehen." |
| Primary CTA | "JETZT ANALYSE-GESPRÄCH BUCHEN" |
| Named assets | Analysegespräch · Diagnose & Priorisierung · Leistungsrechner |
| Region | Austria/DACH — Austrian colloquialisms throughout his speech |

**Figures — all claimed on his own site** (`noldin-consulting.com`, fetched 2026-08-18):
+328 starke Teams · +20% Produktivität · €7.000–€10.000 monatliche Ersparnis (10-person
team) · +15 Stunden pro Woche · 12 Jahre Erfahrung.

**Named testimonials on site:** Philipp Huber (Gründer & GF, Huber Web Media GmbH) ·
Jakob Schuster (Gründer & CEO, Notarity) · Benedict Grabner (GF, Reinigung Rieser GmbH).

**Channels:** YouTube `@TimNoldin` (`UCx-y7QCF8EIt0V-7v95yCow`) · LinkedIn `tim-noldin` ·
Instagram `tim_noldin` · Facebook `tim.noldin`.

---

## Palette — extracted from the live site

| Colour | Hex | Role on their site |
|---|---|---|
| Lime | `#CFD92B` | the brand colour — CTA fills, accents (24 painted areas) |
| Deep navy | `#122635` | dominant body text (52 instances) |
| White | `#FFFFFF` | ground |
| Off-white | `#F7F7F7` | alternating band |
| Mid green | `#587A38` | supporting |
| Dark green | `#3D5427` | supporting |

**Measured contrast — this is the important part:**

| Pair | Ratio | Use |
|---|---|---|
| lime on white | **1.54** | ✗ never as text |
| navy on white | 15.51 | ✓ `--ink`, `--brand-ink` |
| **`#587A38` on white** | **4.93** | ✓ `--accent-ink` — their own colour, passes |
| lime on navy | 10.05 | ✓ `--on-brand-tick` |
| navy on lime | 10.05 | ✓ text on accent fills flips to navy |

Their lime is exactly the failure case documented in `palettes.md`. Their own darker
green solves it, so the whole palette stays in their real colours.

---

## Voice profile

Sourced from 3 videos on his own channel, ~15 min, `a-de` auto-captions
(cleaned — see `research.md` method notes in the skill).

**Address:** always `du`, never `Sie`. Informal throughout.

**Opening move:** a scene, in second person, before any teaching.
> "Du erklärst deinem Team eine Aufgabe und am Ende fragst du noch mal: 'Alles klar?'
> Alle nicken. Einer sagt sogar noch: 'Hey, wird gemacht, Chef.' Und dann vergehen zwei
> Wochen."

**Signature structure:** scene → the misdiagnosis everyone reaches for → the real
diagnosis → reframe → the exact words to say → CTA.

**The reframe pattern — "nicht X, sondern Y".** He runs this constantly and it is the
single most copyable thing about him:
> "Die sind nicht zu nett, die sind zu unklar."
> "Führung heißt nicht mehr zu machen. Führung heißt dafür zu sorgen, dass andere mehr schaffen."
> "Menschen folgen Klarheit und nicht Nettigkeit."
> "Führung ist kein Sprint, sondern ein System."
> "Wenn alles dringend ist, ist nichts wichtig."

**Names real clients, warmly:** "Erinnert mich an ein Gespräch mit'm Björn… Björn, wenn
du das siehst, Shoutout. Richtig richtig cooler Typ."

**Will be blunt for effect:** "Das Gegenteil von Nett sein ist Arschloch sein."

**Austrian register:** "mit'm", "Hei", "Na, hoffentlich bitte nicht", "richtig richtig".

**Uses "wir" for the firm:** "Was wir bei vielen Geschäftsführern beobachten…"

**Closes** with a calendar link or a free system, plus like/subscribe.

---

## Vocabulary

**Theirs — use these:** Klarheit · Rollen / Rollenkonflikt · Standards · Geschäftsführer ·
Führungskraft · Mittelstand · Verantwortung · eigenverantwortlich · konsequent ·
Tagesgeschäft · Umsetzung · praxisorientiert · Selbstüberlastung · Nettigkeitsfalle ·
Entscheidungschaos · Grenzenlosigkeit

**Avoid — outsider/consultant register:** Synergien · Change-Prozess · Empowerment ·
Transformation · Leadership-Journey · Stakeholder-Alignment

---

## The stuck moment

The task you delegated comes back to your desk. Not refused — just quietly not done,
and nobody says so until you ask two weeks later.

His own top-performing video is exactly this
(`Aufgaben so abgeben, dass du sie am Ende nicht doch selbst machst`, 398 views — his
best). The demand signal and the offer agree.

---

## Audience

**Who:** Mittelstand owners and newly-appointed Geschäftsführer, roughly 5–50 staff,
DACH. Often technically excellent and promoted into leading.

**Fears**
- That they are the bottleneck and the business cannot run without them.
  > *"Fast jeder Geschäftsführer hat das Gefühl, viel zu viel selbst machen zu müssen."* — lokaler-mittelstand.de
- That being clear will cost them the relationship — they know these people personally.
  Sourced from his own video: the Björn story is precisely this fear.
- That they are simply not cut out for it.
  > *"Das Unvermögen zu delegieren ist einer der häufigsten Gründe, warum gute Handwerker schlechte Unternehmer werden."* — mes-partner.de

**Desires**
- Tasks that stay delegated. Not more time in the abstract — *this* task, not returning.
- To stay the kind of boss people like, while still holding a line.
- A system rather than a personality change. He sells this directly: "Führung ist kein
  Sprint, sondern ein System."

**Objections** — sourced deliberately from critical material
- Coaching is empty phrases.
  > *"Der Mittelstand braucht keine leeren Floskeln oder unqualifizierten Ratgeber."* — mittelstand-nachrichten.de
- It only works under conditions nobody names.
  > *"Führungskräfte Coaching gilt oft als Allheilmittel … ansonsten bringt es nichts."* — zirbik-business-coaching.de
- Too expensive and too far from daily reality.
  > *"Executive Coaching hat lange den Ruf gehabt, teuer und exklusiv zu sein, weit entfernt vom unternehmerischen Alltag im Mittelstand."* — myconsult-unternehmensberatung.de
- The barrier is higher in Mittelstand than in corporates — asking for help reads as
  admitting failure.

**Buying triggers**
- Newly appointed GF, or the team just crossed ~10 people and informal coordination broke.
- A specific evening spent redoing work that was already delegated.
- A key person leaving, exposing how much only they knew.

**Where they are:** Mittelstand Cafe, KMU-Berater, LinkedIn DACH leadership circles,
regional Wirtschaftskammer/IHK events.

---

## Content signals

Ranked by views (his own channel only — two search hits were guest appearances on other
channels and were excluded):

| Views | Title | Mins |
|---|---|---|
| 398 | Aufgaben so abgeben, dass du sie am Ende nicht doch selbst machst | 6.3 |
| 142 | Wie du konsequent führst, ohne dich unbeliebt zu machen | 4.4 |
| 105 | So machst du Mitarbeitende eigenverantwortlich | 9.4 |
| 105 | Warum dein Team von dir abhängig wird (5 Führungsfehler) | 4.0 |
| 68 | Gesundes Wachstum als KMU sicherstellen | 7.3 |

Delegation and dependency dominate the top of the list. The 8 most recent uploads are
Shorts at 1–8 views and carry no signal.

---

## Competitors

Light pass. The DACH field splits between classical Führungskräfte-Coaching (individual,
expensive, slow) and systems/process consulting. His gap is the combination — a
psychologist selling *systems* with a measurable claim (+20% Produktivität,
Leistungsrechner) rather than personal growth. The funnel should lean on that: concrete
mechanism, not development.

---

## Sources

- `noldin-consulting.com` — positioning, figures, testimonials, socials
- YouTube RSS `UCx-y7QCF8EIt0V-7v95yCow` — 15 videos, titles/dates/views
- Transcripts: `DEgeW867cKk`, `j6yVlO6I9eI`, `e2y9VrhibqU`
- mes-partner.de · lokaler-mittelstand.de · mittelstandcafe.de — audience language
- zirbik-business-coaching.de · mittelstand-nachrichten.de · myconsult-unternehmensberatung.de — objections

## Unverified

- **All site figures** (+328 Teams, +20%, €7–10k, +15 h/Woche, 12 Jahre) are *his claims
  on his own site*, not independently checked. Usable if attributed to him; must not be
  restated as our finding.
- Video view counts are accurate but small in absolute terms — ranking signal only,
  never a proof number on a page.
- Auto-captions mishear occasionally ("dir fallt ein"). Fine for voice; do not quote
  verbatim as his words without checking the video.
- No subscriber count found on site or in search.
- Competitor pass was light — no pricing captured.
