![](afbeelding/vodw1a.png)

> **Auteur**: Tim Kleinloog
> **Laatst geweizigd**: 29 mei 2017

Om ons werk zo efficient mogelijk uit te voeren kwam het idee naar voren voor het gebruik van Git bij onder andere Peer Coding.
Deze pagina gaat stap voor stap iets dieper in op hoe Git(Hub/-Lab) werkt en hoe het gebruikt dient te worden. Onder de verschillende kopjes staat een beknopte toelichting met daaronder links naar de desbetreffende handleidingen op de GitHub en GitLab homepage.

Veel plezier!

# Git
Om GitHub te begrijpen is het belangrijk ook de basics van Git te snappen.

Wat Git het beste versie controle systeem (VCS) maakt wordt het beste verklaard door de volgende twee plaatjes.
Standaard slaat een VCS veranderingen op de volgende manier op:


![Standaard "way of thinking" voor version control systems (VCSs)](https://git-scm.com/book/en/v2/book/01-introduction/images/deltas.png)

De Git "way of thinking" is anders. Het maakt snapshots van het project op en slaat een bestand niet op als het niet is veranderd:

![Git "way of thinking" voor version control systems (VCSs)](https://git-scm.com/book/en/v2/book/01-introduction/images/snapshots.png)

**De kern van Git zijn de drie stages waar een bestand zich in kan bevinden.**

  * Comitted
    * Het bestand is veilig opgeslagen op de locale server
  * Modified
    * Het originele bestand is aangepast, maar niet "committed" naar de locale server
  * Staged
    * Een aangepast bestand is is goedgekeurd om meegenomen te worden in de volgende "commit snapshot"

![Area's GIt](https://git-scm.com/book/en/v2/book/01-introduction/images/areas.png)

De resulterende Git workfow die volgt uit de bovenstaande afbeelding is als volgt:

  1. Pas een betand aan in je eigen working directory
  2. "stage" het bestand
  3. "commit" het bestand. Het nieuwe snapshot wordt nu gebruikt in de Git directory.

Een uitgebeidere uitleg over Git vind je [hier](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics).
Wanneer je GitHub gebruikt zal ook Git gebruikt worden. De eerste keer dat he GitHub en dus ook Git gebruikt is het goed [deze](https://help.github.com/articles/set-up-git/) stappen te volgen om Git te configureren. Voor GitLab gaat het vergelijkbaar.

# De Git(Hub/-Lab) Workflow

Je zult merken dat de Git "way of thinking" de basis is van GitHub en GitLab. Bovendien maakt GitHub het mogelijk om op een gemakkelijke manier en vanaf verschillende locaties samen te werken aan projecten waarbij Git de versiecontrole voor zijn rekening neemt. De remote repository van GitHub of GitLab dienen als centrale punt welke het samenwerken makkelijker maakt. Omdat Git en distributed version control system is staat de gehele geschiedenis van alle veranderingen niet alleen op deze remote, maar ook op de locale computer van elke contrinbutor.

Een uitgebriede uitleg over de workflow die Git gebruikt vind je [hier](https://www.atlassian.com/git/tutorials/what-is-version-control), voor GitHub [hier](https://guides.github.com/introduction/flow/), voor GitLab [hier](https://docs.gitlab.com/ee/workflow/gitlab_flow.html)

# Goede resources voor het leren van Git, GitHub en GitLab

## Using Git
* [Using Git](https://www.atlassian.com/git/tutorials/what-is-version-control)

## Using GitHub
* [Setting up GitHub](https://help.github.com/articles/set-up-git/)
* [Oefening om een idee te krijgen hoe GitHub werkt](https://guides.github.com/activities/hello-world/)
* [Een project op GitHub? Zo werkt het](https://guides.github.com/introduction/getting-your-project-on-github/)
* [Het gebruik van "Issues" voor het tracken van fouten](https://guides.github.com/features/issues/)

## Using GitLab
[The Gitlab workflow](https://docs.gitlab.com/ee/workflow/gitlab_flow.html)

# Glossary
Verward door al de hippe termen die gebruikt worden in versiebeheer? Hieronder vind je alles in een overzichtelijk overzicht terug.

* [Github Glossary](https://help.github.com/articles/github-glossary/)
* [Official Git Glossary](https://www.kernel.org/pub/software/scm/git/docs/gitglossary.html)

# Cheat sheets

* [Git commando's door Atlassian](atlassian-git-cheatsheet.pdf)
* [Git commando's door GitHub](github-git-cheat-sheet.pdf)


# Optional
#### Connecting R and GitHub (vergelijkbaar voor GitLab)
[Automatisch werken in GitHub vanuit R studio](http://www.r-bloggers.com/rstudio-and-github/)

#### Social component Git(Hub/-Lab)

* [Gitter](https://gitter.im/VODW-DS)
* [Be social](https://help.github.com/articles/be-social/)

#### Inspiratie
Een video ter inspiratie. Het laat zien hoe MailChimp GitHub integreert in hun dagelijkse werkzaamheden.

[![GitHub Inspiration](http://img.youtube.com/vi/OeBZUW-9i0M/0.jpg)](https://www.youtube.com/watch?v=OeBZUW-9i0M-Y "GitHub Inspiration")


![vodw](afbeelding/vodw2.png)
