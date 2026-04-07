# Checklists
### Structured Prompts for Engineering Teams

Most architecture problems aren't caused by bad engineering.

They're caused by good engineers making reasonable decisions at the time — and nobody stepping back to ask whether those decisions still make sense as the system, the team, and the traffic have grown.

This is the first in a series of structured checklists — self-audit tools for engineering teams who'd rather find a problem themselves than be surprised by it later.

Each checklist covers patterns I've seen repeatedly across financial services, startups, enterprise and defence environments over 30 years of software architecture work.

They won't tell you anything you couldn't eventually figure out yourself. They will save you the time and pain of figuring it out during an incident.

---

## Checklists

| Title | Description |
|---|---|
| [Have You Outgrown Your AWS Setup?](aws-growth-audit-checklist.adoc) | A self-audit for growing engineering teams whose cloud architecture has evolved faster than it's been reviewed |
| [Is Your Microservice Architecture Actually Working?](microservices-health-check.adoc) | A health check for teams beyond the honeymoon phase of microservices adoption |
| [Technical Debt Triage](technical-debt-triage.adoc) | A structured framework for teams who know they have debt but don't know where to start |

---

## Who this is for

- Engineering teams whose systems have evolved organically and haven't been formally reviewed
- CTOs and Heads of Engineering who suspect their original architecture decisions may not have kept pace with growth
- Architects inheriting a system and looking for a structured starting point

## Who this is not for

Teams just getting started. These aren't beginner's guides — they're prompts for teams who consider themselves experienced but may have blind spots they haven't had cause to examine yet.

---

## Using these checklists

The questions are intentionally direct. Some will have comfortable answers. Others won't — and that's the point.

Work through them as a team if you can. The most useful conversations tend to happen when two people give different answers to the same question.

---

## Formats

The source is written in AsciiDoc. To generate your preferred format locally:

**PDF**
```bash
asciidoctor-pdf -a pdf-theme=professional -a pdf-themesdir=themes aws-growth-audit-checklist.adoc
```

**HTML**
```bash
asciidoctor aws-growth-audit-checklist.adoc
```

A pre-rendered PDF is available in this repo if you'd prefer not to install a toolchain.

---

## Want a structured review rather than a self-audit?

The checklist tells you what to look for. Sometimes it's useful to have an experienced eye look with you.

If you'd like to talk through your architecture — no sales pitch, just an honest conversation — you can reach me at **ian@englishteeth.com**

---

## Author

**Ian Robinson** — Software Architect and Consultant with 30+ years of experience across cloud architecture, financial services, defence, and startup environments.

[LinkedIn](https://www.linkedin.com/in/englishteeth/) &nbsp;|&nbsp; [ian@englishteeth.com](mailto:ian@englishteeth.com)

---

## Licence

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You're free to use, share, and adapt it — just attribute the source.
