class: center, middle, gray-background

# Practical software licensing at UiT

### [Radovan Bast](https://bast.fr/) (UiT The Arctic University of Norway)

<img src="img/coderefinery.png"
     alt="CodeRefinery logo"
     style="height: 140px;"/>
&nbsp;
<img src="img/uit-rse-logo.png"
     alt="UiT RSE logo"
     style="height: 180px;"/>

<a href="https://creativecommons.org/licenses/by/4.0/" target="_blank">
  <img src="img/cc-by-icon.svg"
       alt="CC-BY icon"
       style="height: 30px;"/>
</a>

---

## Outline of this short talk

- Lack of guidelines

- Comparing licenses for data and software

- What do other universities recommend?

- What should we recommend?

- Suggestion for a way forward

---

## Problem

- Open science without software licensing is not useful: reuse is then not possible or unclear at best

- UiT seems to lack guidelines about software licensing

- The existing guidelines are not easy to find
  - https://en.uit.no/research/innovation/art?p_document_id=754152
  - Title: "Employees: innovation and commercialization"

- Guidelines are not clear about ownership/copyright

- No recommendation for choosing software licenses

- No practical recommendations for what to do when license has been chosen either

---

<img src="img/license-models.png"
     alt="license models"
     style="height: 530px;"/>

.cite[European Commission, Directorate-General for Informatics, Schmitz, P., European Union Public Licence (EUPL): guidelines July 2021, Publications Office, 2021, https://data.europa.eu/doi/10.2799/77160]

---

## Guidelines/recommendations from various universities

- [Aalto university](https://www.aalto.fi/en/open-science-and-research/opening-your-software-at-aalto-university)
    - Summary: yes, you can open software and data and you need to ask only
      minimal permission (confirm your supervisor agrees).
- [UiT](https://en.uit.no/research/innovation/art?p_document_id=754152)
    - "Work results of a copyright nature belong to the author"
- [NTNU](https://i.ntnu.no/wiki/-/wiki/English/Guidelines+for+policy+for+Open+Science)
    - "Where no overriding guidelines exist, NTNU-produced software must be
      licensed under the European Union Public Licence."
- [UiB](https://www.uib.no/en/ub/106619/copyright-own-scientific-work)
    - "As a rule authors have copyright to their own work"
    - Encourage the use of CC-BY
- [UiO](https://www.uio.no/english/for-employees/support/research/funding/units/hf/imv/data-ethics/ipr.html)
    - "If the University chooses not to take steps to secure copyright
      protection and exploit the findings, the employees must be entitled to
      have these rights reassigned to them."

---

## NTNU [Guidelines for policy for Open Science](https://i.ntnu.no/wiki/-/wiki/English/Guidelines+for+policy+for+Open+Science)

[...]

"For software production, it is desirable to provide access through a
licence that permits reuse and further modification, has broad legal recognition and is certified by the Open Source Initiative (OSI).
.emph[Where no overriding guidelines exist], NTNU-produced software must be licensed under the
.emph[European Union Public Licence]. For software projects in disciplines with
special requirements or licensing practices specific to a field of use, it may
be possible to use other licences that satisfy the OSI requirements for
open source code (for example the MIT licence, the Apache licence, or GNU
GPLv3)."

[...]

---

## What license(s) should we recommend?

[Comparison of licenses](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses)


### MIT

- permissive
- short
- very popular (probably the most used worldwide)


### European Union Public Licence

- interoperable (no restrictions on linking)
- reciprocal
- compatible with GPL/AGPL, LGPL, MPL
- license text available in 23 EU languages
- part of European law
- free legal support
- good documentation

---

## Suggestion for a way forward

- We provide a clear recommendation
  (like [NTNU](https://i.ntnu.no/wiki/-/wiki/English/Guidelines+for+policy+for+Open+Science))
  but also keep it really practical
  (like [Aalto university](https://www.aalto.fi/en/open-science-and-research/opening-your-software-at-aalto-university))
- Ownership: ?
- License: MIT or Apache 2.0 (patent clause) or EUPL, unless derivative code dictates otherwise
- We give guidelines on what to do if this is a derivative code
- Provide practical recommendations
  - License your code very early in the project
  - Follow https://reuse.software/tutorial/
  - From day 1 anticipate open sourcing in future
- Get approval: ?
- We summarize these in a website and link from our websites and advertise in blog posts and events
