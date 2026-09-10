# Research — Accent Change (Dillon Ford)

Prepared for a webinar-funnel sample, brand **The Simulation Room**. English on every
page (US prospect). Sources at the bottom; unverifiable claims under **Unverified**.

---

## Identity

- **Brand:** Accent Change (accentchange.com). Promise: *"Finally Sound Like Yourself in
  American."* Sub: *"I help Successful Experts with strong foreign accents finally sound
  like themselves in American — with the same Hollywood Accent Techniques I used to
  successfully change my own accent within 18 months."*
- **Host:** Dillon Ford — accent-reduction coach, professionally trained actor, writer.
  Born in Munich, "half German, half Czech." Trained at the **William Esper Studio**,
  NYC (two years of accent-reduction + Voice & Speech classes; alumni named on his site:
  Sam Rockwell, Ebon Moss-Bachrach, Timothy Olyphant). Changed his own accent over
  "18 months of consistent action taking, discipline" and reports sounding "~97%
  American." Also: Jiu Jitsu purple belt, D&D player, fantasy novelist.
- **YouTube:** `@accentchange` ("Dillon Ford | American Accent Training"). Consent-walled
  from both WebFetch and the Browser pane (DE IP → GDPR redirect). No transcript mined —
  voice profile below is built from his written posts and two long-form interviews
  instead (see Voice profile → caveat).
- **Current funnel:** free **Accent Archetype Quiz** ("Find out YOUR Archetype +
  American Examples") → free **Skool community** (`skool.com/american`) → 1:1 coaching /
  "Accent Strategy Call". Also a self-paced course, **American Accent Fundamentals**
  (claimed on IG: "5 hours, 10 modules, 86 video lessons").
- **Named framework — the UDS Method** (his words, from accentchange.com):
  - **Understand** — "the easiest and fastest part… look up any American sound on
    YouTube right now." Theory ≠ skill.
  - **Drill** — "an incredibly important step where most people fall short… in an actual
    conversation there's too much going on at the same time for you to adequately catch
    the sounds. You need to build habits first."
  - **Simulate** — "where I use my acting training… 'roleplaying' in more advanced
    scenarios (scripted and improvised) to make sure that we truly pressure test the
    habits you built… you will fail a lot in this step. This is good."
  - "Think of a three legged stool. You remove one leg, it falls over."
- **Positioning line (his):** he fixes the **accent barrier**, not the language barrier —
  for people whose English is already fluent/expert-level.

### Proof points (claimed on his own site / profiles — carry as "claimed")

- Changed his own accent in **18 months**; "~97% American" now.
- "The same methods actors like **Daniel Day-Lewis and Christian Bale** use to prepare
  for movie roles."
- **5-star rated** across Google Business, Fiverr, Superprof, Trustpilot (Superprof
  listing: 18 reviews, $85/h).
- Works with **educational YouTube creators**, "some with 20K+ subscribers."
- Testimonials on the homepage (names + country + role, no outcome text given):
  Gleb (Russia, founder realcar.nyc) · Pei (China, project consultant) · Dominik
  (Slovakia, freelancer) · Aadi (India, content-agency owner) · Quan (Vietnam,
  financial advisor) · Alena (Belarus, researcher/student).

---

## Palette (extracted from accentchange.com computed styles)

White-ground brand. Painted-area tally: background `rgb(255,255,255)` dominant; dark
navies `rgb(34,38,57)` / `rgb(14,24,44)` / `rgb(0,3,33)`; primary blue `rgb(21,94,239)`
/ `rgb(24,139,246)`; a single **highlighter yellow** `rgb(255,229,0)`; muted text
`rgb(136,147,168)` and `rgb(85,108,121)`. Fonts: Lato (body), Montserrat + Inter
(headings). Sample keeps the template's local font stacks — no web fonts.

Mapping (light default — their site is a white ground):

| Token | Light (`:root`) | Dark (`[data-theme="dark"]`) |
|---|---|---|
| `--paper` | `#FFFFFF` | `#0B1120` |
| `--paper-2` | `#F3F6FC` | `#111A2E` |
| `--card` | `#FFFFFF` | `#152036` |
| `--ink` | `#0E182C` (their darkest navy) | `#EEF2FA` |
| `--ink-soft` | `#556C79` | `#A9B6C9` |
| `--ink-faint` | `#8893A8` | `#7E8BA3` |
| `--brand` / `--brand-2` | `#1D4ED8` / `#1A44BD` | `#2563EB` / `#1D4ED8` |
| `--on-brand` | `#FFFFFF` | `#FFFFFF` |
| `--brand-ink` | `#1149BE` (darkened, ≥4.5:1 on white) | `#7FB0FF` (lightened for dark ground) |
| `--btn-bg` | `#1D4ED8` | `#2563EB` |
| `--brand-tint` | `#E4ECFC` | `#17264A` |
| `--accent` | `#FFE500` (highlighter yellow — fills only: dot, alert bar, seat meter) | `#FFE500` |
| `--accent-ink` | `#7A5C00` (yellow darkened until it passes 4.5:1 for text uses) | `#F0D24A` |
| `--on-brand-tick` | `#FFFFFF` (theme-fixed — sits on the blue panel in both modes) | `#FFFFFF` |

Notes:
- Their raw primary `#155EEF` measured only ~3.7:1 with white — too low for the mono
  chips and pill labels the template sets in white on the brand ground. Deepened one
  notch to `#1D4ED8` (still clearly their blue; ~6.7:1 with white). Eyebrows / small
  text on white use `#1149BE` (`--brand-ink`).
- The yellow is `~1.1:1` on white as text — **never** set type in raw `--accent`. The
  OTO page hardcodes near-white on `var(--accent)` in a few spots (alert bar, pip,
  ticket flag); flip those to `--accent-ink` / `#0E182C` so text on yellow is dark.
- Run the contrast snippet from `palettes.md` after pasting.

---

## Voice profile

**Caveat:** no YouTube transcript (consent wall). Profile built from his Substack
("Dialect Work"), his site copy, and two long-form written Q&As (SHOUTOUT LA,
CanvasRebel — SHOUTOUT quotes captured verbatim; CanvasRebel bot-blocked, used only for
facts already corroborated elsewhere). Written voice is a strong signal here because his
posts *are* first-person and unedited-sounding; lean on structure over mimicry anyway.

- **Short declaratives, then a beat.** "Your foreign accent is NOT part of your identity.
  There. I said it." / "Speaking more doesn't fix your accent. You just keep making the
  same mistakes."
- **Direct address, second person.** Talks *to* the reader, not about the topic.
- **Concrete analogies.** Three-legged stool. Gym. "Solving a fun puzzle, not… a chore."
- **Reframes a fear, then disarms it.** identity → "changing my accent didn't make me
  any less German." / failure → "you will fail a lot in this step. This is good."
- **Anti-hype, anti-grind.** "I'm not a big believer in learning while stressed out."
  "I don't get mad when my students tell me they haven't had time to practice."
- **Actor's framing.** phonetics, sounds, drills, roleplay, "pressure test," "simulate,"
  systematic vs "willy nilly."
- Mild self-deprecation about the origin: with a German accent he only got cast as
  "Nazis and weirdos."

### Quote bank (verbatim, safe to echo in spirit)

- "Finally sound like yourself in American."
- "I fix the accent barrier — not the language barrier."
- "Theoretical knowledge is important but does not equate to actual skill."
- "Think of a three legged stool. You remove one leg, it falls over."
- "You will fail a lot in this step. This is good."
- "Speaking more doesn't fix your accent. You just keep making the same mistakes."
- "Changing my accent didn't make me any less German."
- "Approach it like you're solving a fun puzzle, not like you're forced to do a chore."
- "I'm not a big believer in learning while stressed out."
- "The difference… was that I had a systematic approach based on phonetics."

---

## Audience

Non-native professionals whose **English is already good** — the problem is delivery
under pressure, and how they're *perceived*. From forum/essay search (TeamBlind,
Substack essays, personal blogs — sourced below):

- **Fears**
  - Being judged less competent than they are because of the accent ("implicit biases
    label people with foreign accents as less competent").
  - "The squint" — watching a listener's eyes go slightly unfocused mid-sentence.
  - Being fine face-to-face but falling apart on phone screens / Zoom / recorded demos.
  - Losing themselves — that fixing the accent means erasing where they're from.
- **Desires**
  - Be heard for the expertise, not the accent. Stop repeating themselves.
  - Sound like themselves on their best day, on demand — not just when reading aloud
    alone.
  - Keep the fix under load: a sales call, a board update, a conference talk, a podcast.
- **Objections**
  - "I've already done the apps / a course / years of 'just speak more' — nothing stuck."
  - "I don't have time to practice daily."
  - "Isn't this just going to sound fake?"
  - "My accent isn't that bad" / "is it even fixable at my age?"
- **Buying triggers**
  - A specific upcoming high-stakes moment (fundraise, big client, promotion, launch).
  - One meeting that went badly because of a misheard word.
  - Realising theory hasn't converted to a single changed habit.

### Vocabulary (use this column; skip generic self-improvement words)

the accent barrier · sounds / the vowel / the R / the TH · drilling · reverting under
pressure · "sound like yourself" · the squint · asked to repeat · roleplay / simulate ·
pressure-test · habit, not knowledge · General American · "willy nilly" vs systematic ·
theory ≠ skill · fluent but not clear · familiarity = clarity

---

## The stuck moment (vocabulary test)

| The stuck moment | Their words |
|---|---|
| The new sounds hold when practising alone, then slip back the second a call gets real | reverting under pressure, the squint, "sorry — say that again?", theory that never became habit |

Write the whole funnel in that column. If a sentence would read the same for a generic
"public speaking" course, cut it.

---

## Offer shape (for the funnel — placeholder, design demo)

- **Free live event:** *The Simulation Room* — a 52-minute live workshop where Dillon
  runs real pressure-tests: the 3 sounds that give you away on a call, why drilling
  alone doesn't transfer, and live simulations with attendees. Positioned as the step
  **between the free Accent Archetype Quiz and a 1:1 Accent Strategy Call**.
- **One-time offer (OTO):** *The Simulation Vault* — ~20 scripted pressure-test
  scenarios (cold call, discovery call, investor pitch, standup, podcast interview, Q&A)
  with model General-American audio for each line, a self-recording workflow, and one
  live group drill session a month. Illustrative price **$47**.
- `CHECKOUT_URL` unset → offer button degrades to a toast.

---

## Competitors / anchors (light)

- The Accent Coach (theaccentcoach.com), Accent Advisor, Prestige Accents, Keri Safran —
  positioned around "accent reduction classes" and clarity. Gap Dillon already owns:
  **the actor's Simulate step** (pressure-testing under roleplay) and **"sound like
  yourself"** identity framing. Keep the sample on that ground.
- Superprof lists him at **$85/h**; self-paced course pricing not public. $47 OTO sits
  well under a single coaching hour — believable.

---

## Sources

- https://accentchange.com/ (home, about, method, FAQ — via Browser pane, verbatim)
- https://accentchange.com/ blog teasers: "Your Foreign Accent ≠ Your Identity",
  "Why Speaking More Won't Fix Your Accent" (Jul 2025)
- https://dialectwork.substack.com/archive + /p/can-anyone-change-their-accent,
  /p/what-is-accent-reduction (WebFetch — summarised, used for substance not verbatim)
- https://shoutoutla.com/meet-dillon-ford-writer-accent-reduction-coach-actor/ (verbatim Q&A)
- https://canvasrebel.com/meet-dillon-ford/ (403 / bot-blocked — facts only, cross-checked)
- https://www.linkedin.com/in/dillontheford/ · https://www.superprof.com/…accent-reduction… (ratings, rate)
- https://www.skool.com/american/about (free community)
- Audience: teamblind.com posts on accents in interviews; barbaraserra.substack.com;
  pavlinacerna.substack.com "leave my accent alone"; medium "too foreign here too local there"

## Unverified

- "~97% American", "18 months", "20K+ subscriber creators", the actor-method comparison,
  the 5-star-everywhere claim — all his own, carried as claimed, not independently checked.
- Testimonial outcomes: the homepage gives names/countries/roles but **no result text**.
  Any specific result in the funnel copy is invented for the demo — do not attach an
  invented outcome to the real first names; the sample uses generic labels instead.
- The entire offer (event + OTO + $47) is a design placeholder, not something Dillon sells.
