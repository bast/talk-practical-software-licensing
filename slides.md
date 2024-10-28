class: center, middle, gray-background

# Practical software licensing

## Radovan Bast

### UiT The Arctic University of Norway

<img src="img/coderefinery.png" style="height: 140px;"/>
&nbsp;
<img src="img/rse-logo.png" style="height: 180px;"/>

Text: CC-BY 4.0

Slides: https://doi.org/10.5281/zenodo.11554000

---

.left-column30[
## About me

<img src="img/avatar.jpeg" style="width: 80%;"/>
]

.right-column70[
- Theoretical chemist turned research software engineer.

- I write research software and teach programming to researchers and lead the
  [CodeRefinery project](https://coderefinery.org).

- I lead the [high-performance computing group](https://hpc.uit.no) and the
  [research software engineering group](https://research-software.uit.no) at UiT.

- Drafted a [Research software licensing guide](https://research-software.uit.no/blog/2023-software-licensing-guide/)

.quote[I am not a lawyer. This is not a legal advice ...]
]

---

.left-column70[
## Copyright and derivative work: Sampling/remixing

- Copyright controls whether and how we can distribute
  the original work or the .emph[derivative work]
- In the **context of software** it is more about
  being able to change and .emph[distribute changes]
- Changing and distributing software is similar to changing and distributing
  music
- You can do almost anything if you don't distribute it

**Often we don't have the choice**:
- We are expected to publish software
- Sharing can be good insurance against being locked out

**Can we distribute our changes** with the research community or our future selves?
]

.right-column20[
<img src="img/ai/record-player.png"
     alt="Generated image of a monk operating a record player"
     style="height: 220px;" />

<img src="img/ai/turntable.png"
     alt="Generated image of a monk operating two record players"
     style="height: 220px;" />

.cite[Midjourney, CC-BY-NC 4.0]
]

---

# Why software licenses matter

You find some great code that you want to reuse for your own publication.

- This is good for the original author - you will cite them. Maybe other people who cite you will cite them.

- You modify and remix the code.

- Two years later ... &#8987;

- Time to publish: You realize **there is no license to the original work** &#128561;

---

# Now we have a problem

### &#128556; "Best" case: You manage to publish the paper without the software/data

Others cannot build on your software and data.

### &#128561; Worst case: You cannot publish it at all

Journal requires that papers should come with data and software so that they are reproducible.

---

.left-column70[
# Derivative work?

- Download some code from a website and add on to it:
  .quote[[x] yes [ ] no]
- Download some code and use one of the functions in your code:
  .quote[[x] yes [ ] no]
- Rewriting code you got from somewhere to a different language:
  .quote[[x] yes [ ] no]
- Linking to libraries (static or dynamic), plug-ins, and drivers:
  .quote[[ ] yes [x] no]
- You read a paper, understand algorithm, write own code:
  .quote[[ ] yes [x] no]
- Clean room design (somebody explains you the code but you have never seen it):
  .quote[[ ] yes [x] no]
]

.right-column30[
<img src="img/ai/modular.png"
     alt="Generated image of a modular synthesizer"
     style="height: 250px;" />

<img src="img/ai/clean-room.png"
     alt="Generated image of a clean room"
     style="height: 250px;" />

.cite[Midjourney, CC-BY-NC 4.0]
]

---

# Software license types (metaphor: cake)

.left-column50[
<img src="img/cake-1.svg" alt="cake emoji" style="width: 100px;"/>

## Your recipe (code)

- Imagine you (.emph[original author]) compose a recipe for a really tasty cake.
- In regular intervals you distribute cakes (release binaries).
- You share it on GitHub under the OpenCake organization.

]

.right-column50[
<img src="img/cake-2.svg" alt="cake emoji" style="width: 100px;"/>

## Famous restaurant ...

- Finds your cake recipe on GitHub
- The chef suggests improvements (.emph[derivative work]).
- They wish to put it on their menu (.emph[distribution]).
]

.cite[Images: [EmojiOne](https://www.emojione.com), CC-BY-SA 4.0]

---

## Possible outcomes 1/4: custom/proprietary

### No license or custom license

- No restaurant chef will touch it: too much hassle to employ a lawyer to be sure
  that the cake can be served to customers.
- But maybe they will bake it and eat it and not distribute it and that is OK
  ("fair use" provision permits the making of copies for own use).

<!--- The restaurant industry is infamous for copying recipes and there are
very few published court cases. Let's skim over this fact and stay in the
fictitious example though. -->

---

## Possible outcomes 2/4: permissive

### License: MIT or Apache or BSD-2

- It is OK to use the recipe and sell the cake.
- It is OK to not share the improved recipe.
- They have to .emph[indicate where the original recipe came from (preserve copyright notice)]
  and possibly summarize their modifications.
- If somebody becomes sick, it is not the fault of the OpenCake organization (limit of liability).
- You may not get the improvements back to use yourself.

### License: BSD-3

- In addition to the above it is understood that the updated recipe are not endorsed by the OpenCake organization.

---

## Possible outcomes 3/4: share-alike, weak copyleft

### License: GNU Lesser GPL (LGPL)

- The restaurant has to share only the improved cake recipe .emph[but can keep other recipes closed].
- .emph[You can use their improved recipe] and improve it further:

<img src="img/cake-2.svg" alt="cake emoji" style="width: 100px;"/>
<img src="img/cake-3.svg" alt="cake emoji" style="width: 100px;"/>

- The restaurant guests have to be able to exchange the cake from the menu by improved cakes from other restaurants (dynamic relinking).

### License: Mozilla Public License v2.0

- Like LGPL but do not require that the modified cake can be exchanged by the restaurant guest.

---

## Possible outcomes 4/4: strong copyleft

### License: GNU GPL or GNU Affero GPL

- If the cake is a part of the menu, the famous restaurant has to
  .emph[share the recipes of the entire menu].

---

<img src="img/license-models.png"
     alt="license models"
     style="height: 530px;"/>

.cite[European Commission, Directorate-General for Informatics, Schmitz, P., European Union Public Licence (EUPL): guidelines July 2021, Publications Office, 2021, https://data.europa.eu/doi/10.2799/77160]

---

.left-column50[
### Beginning of a project

<img src="img/ai/field.png"
     alt="Generated image of an empty field"
     style="height: 250px;" />

.cite[Midjourney, CC-BY-NC 4.0]

- License does not seem important
- Easy to change (*)
- **Start with a LICENSE file**
]

.right-column50[
### Later in the project

<img src="img/hundertwasserhaus.jpg"
     alt="Photo of Hunderwasserhaus in Vienna"
     style="height: 250px;" />

.cite[C.Stadler/Bwag, CC-BY-SA 4.0]

- Can be important
- Especially when combining codes or organizations
- Difficult to change
- Authors change affiliation
]

---

## If your work is not derivative work - you started from scratch

Clarify:
- Does your work contract, grant, or collaboration agreement dictate a
  specific license?
- Is there an intent to commercialize the code?
- When there is unknown or mixed ownership: If there are multiple persons or
  organizations as owners of the code, all must agree to the license.

Do not invent your own license. Choose one of the standard licenses, otherwise
compatibility is not clear:
  - [Joinup Licensing Assistant - Find and compare software licenses](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses)
  - [Joinup Licensing Assistant - Compatibility Checker](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-compatibility-checker)

If no overriding guidelines exist, we recommend:
- **European Union Public Licence, Version 1.2 or later (EUPL)**
- **MIT License**

---

## If your work is derivative work

**Check the license of the
original code**. Depending on the license, your choices might be limited:
- [Joinup Licensing Assistant - Find and compare software licenses](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses)
- [Joinup Licensing Assistant - Compatibility Checker](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-compatibility-checker)

If the original code does not have a license, you may not be able to distribute your
derivative code.
- Try to contact the authors and ask them to clarify
  the license of their code.

---

## Receiving contributions

- Keep track of where things come from. Clarify their license.

- **Work as if the project is public even though it is still private**:
  This is to avoid surprises about code in the history with incompatible
  license years later when we decide to open the project.

---

## Slides: https://doi.org/10.5281/zenodo.11554000

- [More about licenses](https://coderefinery.github.io/social-coding/software-licensing/#great-resources)

- [More about software citation](https://coderefinery.github.io/social-coding/software-citation/)

- [Research software licensing guide](https://research-software.uit.no/blog/2023-software-licensing-guide/)

.left-column50[
<img src="img/coderefinery.png" style="height: 140px;"/>

https://coderefinery.org
]

.right-column50[
<img src="img/rse-logo.png" style="height: 140px;"/>

https://research-software.uit.no
]
