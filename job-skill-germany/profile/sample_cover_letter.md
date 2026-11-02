# House style for cover letters / Anschreiben

This is the fallback voice the skill uses when the user hasn't supplied their own
sample. It is a **template-example**, not the user's real voice — always fill it
with the user's actual details from `base_cv`/`profile.md`, never the placeholders.
Goal: reads like a real person wrote it in ten focused minutes, not like AI.

## What makes it NOT sound AI-generated

1. **Open with something real, not a template.** Kill "I am writing to express my
   interest in the X position at your esteemed company." Open with a specific hook:
   a concrete thing about their product/stack, or what you already do that maps to
   the role.
2. **Specifics beat adjectives.** "I built the invoicing module two teams now use
   daily" > "results-driven engineer passionate about scalable solutions."
3. **Plain verbs.** built, shipped, fixed, migrated, broke, rewrote — not
   spearheaded, leveraged, orchestrated, utilized.
4. **Vary sentence length.** Short, then long. AI writes uniform medium sentences;
   humans don't.
5. **One honest reason you want *this* company.** Not "I admire your innovative
   culture." Name the domain, the stack, or a line from the JD.
6. **Don't restate the CV.** Pick 2–3 things and go deeper; connect them to the role.
7. **Concrete close.** Availability in plain terms: notice period, start date, that
   you're already here.
8. **Short.** Under ~300 words, one page. Germans especially value concise.
9. **Mild imperfection is human.** A contraction, a direct aside ("happy to show
   you the code"), one specific detail. Over-polish reads synthetic.

Mini before/after:
- ❌ "I am a results-driven engineer with a proven track record of delivering
  scalable, high-performance solutions."
- ✅ "For the last year I've been the person who ships the frontend and wires up
  the API behind it — most recently [concrete thing]."

## Layout: simple header + footer (use for every cover letter)

Keep it clean and minimal — no logos, no colored bars, no tables. A single
contact line under a thin rule at the top; the signature (and nothing else) at the
bottom. In DOCX, the top contact line goes in the page **header** and the sign-off
in a plain **footer**; for a one-page letter, inline is fine.

```
────────────────────────────────────────────────────────────
[Full Name] — [Headline, e.g. Full-Stack Developer]
[City, Country] · [email] · [phone] · [linkedin]
────────────────────────────────────────────────────────────

[Date]

[Company]
[Hiring person, or "Hiring Team"]

Application — [Role]

Dear [name / "Hiring Team"],

[Hook — one specific line about them/their mission, swapped per company.]

[One line on who you are + 2–3 real things you've built, tied to this role.]

[One line on how your stack overlaps their JD.]

[Logistics: where you're based, availability, languages.]

I'd be glad to talk about how I could fit in. Thanks for your time.

Warm regards,
[Full Name]
```

### Worked example (based on the 1KOMMA5° working-student role)

```
────────────────────────────────────────────────────────────
Muhammad Rahman — Full-Stack Developer
Bamberg, Germany · dev.rahman01@gmail.com · +49 157 56563397 · linkedin.com/in/dev-rahman
────────────────────────────────────────────────────────────

1 November 2026

1KOMMA5°
Hiring Team

Application — Working Student, Software Engineering

Dear Hiring Team,

What pulled me to apply is the mission itself — solar, heat pumps, and charging
tied into one platform. That's a problem I'd genuinely enjoy working on, and one
that actually matters, which I can't say about most software jobs.

I'm a full-stack developer with four years across Angular, React, Next.js,
Flutter, and Node/NestJS, currently finishing my Master's in Software Systems at
the University of Bamberg. At Alliance Tech I helped rebuild two mobile apps used
by 100,000+ people and moved the backend onto Node.js/Express to make it
maintainable; I also built HIPAA-compliant telehealth features with real-time
WebSocket sync, which taught me to build carefully when the data is sensitive.
Right now I'm a Werkstudent at Siemens Healthineers, where much of my work is
turning half-defined problems into something we can actually ship — close to what
this role asks for.

I already work with most of your stack — TypeScript, Node, NestJS, React,
Next.js — and I've built REST APIs before, so I wouldn't be starting from zero.

I'm enrolled at Bamberg for a while yet, based in Germany, and happy to work
remotely. My English is C1 and my German is coming along (A2).

I'd be glad to talk about how I could fit into the team. Thanks for your time.

Warm regards,
Muhammad Rahman
```

## German formal structure (for traditional/Mittelstand roles)

Same spirit, more formal register. Add the standard header and use "Sie".
- Header: your name + address (top), company address, place + date, subject line
  "Bewerbung als [Rolle] — [frühestmöglicher Eintritt]".
- Salutation: "Sehr geehrte Frau [X]" / "Sehr geehrter Herr [Y]"; only fall back to
  "Sehr geehrte Damen und Herren" if no name is findable.
- Body: same 3 beats (hook → what you've built → why them + availability), formal
  tone, no contractions, still specific — not "Hiermit bewerbe ich mich...".
- Close: "Mit freundlichen Grüßen", name.
