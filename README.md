# Architecture Decision Records (ADRs) [![TechRadar Quadrant: Technique][badge-tech-radar-techniques]](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)

> <img alt="Repository" src="https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/repo.svg" height="60" width="60" align="left" valign="top"> Capture important architectural and design decisions—along with their context and consequences—for the benefit of future team members, as well as and external oversight.

[![The MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/v/architecture-decision-records.svg?style=flat-square)](https://www.npmjs.org/commonality/architecture-decision-records)
<br>
[![David](https://img.shields.io/david/commonality/architecture-decision-records.svg?style=flat-square)](https://david-dm.org/commonality/architecture-decision-records)
[![David](https://img.shields.io/david/dev/commonality/commonality/architecture-decision-records.svg?style=flat-square)](https://david-dm.org/commonality/commonality/architecture-decision-records?type=dev)<br>
[![Travis CI](https://img.shields.io/travis/commonality/commonality/architecture-decision-records.svg?style=flat-square&logo=travis)](https://travis-ci.org/commonality/commonality/architecture-decision-records)
[![AppVeyor](https://img.shields.io/appveyor/ci/commonality/architecture-decision-records.svg?style=flat-square&logo=appveyor)]()
[![Codecov](https://img.shields.io/codecov/c/github/commonality/architecture-decision-records.svg?style=flat-square&logo=codecov)]()
[![Codacy](https://img.shields.io/codacy/id.svg?style=flat-square&logo=Codacy)]()<br>
[![GitHub](https://img.shields.io/github/issues/commonality/architecture-decision-records.svg?style=flat-square&logo=github)](https://github.com/commonality/architecture-decision-records/issues)

---

## Index of ADRs

There aren't any ADRs, yet.

## Propose an architecture decision

- [![TechRadar Quadrant: Languages and Frameworks][badge-tech-radar-langs]][tw-tr-languages-frameworks]

   > **Programming Languages** are what people use to write software.<br>
   > **Frameworks** provide structure and support software is written.

   [Propose a **Language or Framework** decision][pr-lang-nygard]

- [![TechRadar Quadrant: Platforms][badge-tech-radar-platforms]][tw-tr-platforms]

   > **Platforms** host or execute software, and refer to things like operating systems, VMs, and hybrid clouds.

   [Propose a **Platforms** decision]()

- [![TechRadar Quadrant: Techniques][badge-tech-radar-techniques]][tw-tr-techniques]

   > **Techniques** include processes and methodologies concerned with managing and organizing software developers, as well as behaviors encouraged by design thinking.

   [Propose a **Techniques** decision]()

- [![TechRadar Quadrant: Tools][badge-tech-radar-tools]][tw-tr-tools]

   > **Tools** are computer programs that software engineers use to create, repair, maintain, and support other software. Tools may also refer to hardware that perform the same functions.
   >

   [Propose a **Tools** decision]()

<!-- ⛔️ LINK REFERENCES(Begin) ⛔️  -->

[adr-madr-languages-frameworks]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(languages-frameworks):%20add%20MADR%20template&template=adr_template_madr.md
[adr-madr-platforms]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(platforms):%20add%20MADR%20template&template=adr_template_madr.md
[adr-madr-techniques]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(techniques):%20add%20MADR%20template&template=adr_template_madr.md
[adr-madr-tools]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(tools):%20add%20MADR%20template&template=adr_template_madr.md

[adr-nygard-languages-frameworks]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(languages-frameworks):%20add%20MADR%20template&template=adr-nygard-template.md
[adr-nygard-platforms]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(platforms):%20add%20MADR%20template&template=adr-nygard-template.md
[adr-nygard-techniques]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(techniques):%20add%20MADR%20template&template=adr-nygard-template.md
[adr-nygard-tools]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?expand=1&title=adr(tools):%20add%20MADR%20template&template=adr-nygard-template.md
[badge-tech-radar-langs]: https://img.shields.io/badge/Tech--Radar-Languages%20%26%20Frameworks-b32059.svg?style=for-the-badge
[badge-tech-radar-platforms]: https://img.shields.io/badge/Tech--Radar-Platforms-f38a3e.svg?style=for-the-badge
[badge-tech-radar-techniques]: https://img.shields.io/badge/Tech--Radar-Techniques-1ebccd.svg?style=for-the-badge
<!-- [badge-tech-radar-tools]: https://img.shields.io/badge/TechRadar-Tools-86b782.svg?style=flat-square -->
[badge-tech-radar-tools]: https://img.shields.io/badge/Tech--Radar-Tools-86b782.svg?longCache=true&style=for-the-badge

[icon-octicon-link-external]: https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/link-external.svg
[icon-octicon-file-text]: https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/file-text.svg
[icon-octicon-info]: https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/info.svg
[icon-octicon-thumbsup]: https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/thumbsup.svg

<!-- QUADRANT: Languages and Frameworks -->
[label-langs-frameworks-img]: https://fakeimg.pl/200x40/b32059/FFF/?text=Languages+%26+Frameworks&font_size=24
[label-tech-radar-langs-frameworks-img]: https://fakeimg.pl/200x80/b32059/FFF/?text=TechRadar:%0ALanguages+%26+Frameworks&font_size=24
[menu-quad-languages-img]: docs/img/readme/menu_quadrant_languages.png
<!-- RINGS: Languages and Frameworks -->
[label-tech-radar-langs-frameworks-adopt-img]: https://fakeimg.pl/80x40/b32059/FFF/?text=Adopt&font_size=18
[label-tech-radar-langs-frameworks-trial-img]: https://fakeimg.pl/80x40/b32059/FFF/?text=Trial&font_size=18
[label-tech-radar-langs-frameworks-assess-img]: https://fakeimg.pl/80x40/b32059/FFF/?text=Assess&font_size=18
[label-tech-radar-langs-frameworks-hold-img]: https://fakeimg.pl/80x40/b32059/FFF/?text=Hold&font_size=18
<!-- QUADRANT: Platforms -->
[label-platforms-img]: https://fakeimg.pl/200x40/f38a3e/FFF/?text=Platforms&font_size=24
[label-tech-radar-platforms-img]: https://fakeimg.pl/200x80/f38a3e/FFF/?text=TechRadar:+Platforms&font_size=24
<!-- RINGS: Platforms -->
[label-tech-radar-platforms-adopt-img]: https://fakeimg.pl/80x40/f38a3e/FFF/?text=Adopt&font_size=18
[label-tech-radar-platforms-trial-img]: https://fakeimg.pl/80x40/f38a3e/FFF/?text=Trial&font_size=18
[label-tech-radar-platforms-assess-img]: https://fakeimg.pl/80x40/f38a3e/FFF/?text=Assess&font_size=18
[label-tech-radar-platforms-hold-img]: https://fakeimg.pl/80x40/f38a3e/FFF/?text=Hold&font_size=18
<!-- QUADRANT: Techniques -->
[label-techniques-img]: https://fakeimg.pl/200x40/1ebccd/FFF/?text=Techniques&font_size=24
[label-tech-radar-techniques-img]: https://fakeimg.pl/200x80/1ebccd/FFF/?text=TechRadar:+Techniques&font_size=24
<!-- RINGS: Techniques -->
[label-tech-radar-techniques-adopt-img]: https://fakeimg.pl/80x40/1ebccd/FFF/?text=Adopt&font_size=18
[label-tech-radar-techniques-trial-img]: https://fakeimg.pl/80x40/1ebccd/FFF/?text=Trial&font_size=18
[label-tech-radar-techniques-assess-img]: https://fakeimg.pl/80x40/1ebccd/FFF/?text=Assess&font_size=18
[label-tech-radar-techniques-hold-img]: https://fakeimg.pl/80x40/1ebccd/FFF/?text=Hold&font_size=18
<!-- QUADRANT: Tools -->
[label-tools-img]: https://fakeimg.pl/200x40/86b782/FFF/?text=Tools&font_size=24
[label-tech-radar-tools-img]: https://fakeimg.pl/200x80/86b782/FFF/?text=TechRadar:+Tools&font_size=24
<!-- RINGS: Tools -->
[label-tech-radar-tools-adopt-img]: https://fakeimg.pl/80x40/86b782/FFF/?text=Adopt&font_size=18
[label-tech-radar-tools-trial-img]: https://fakeimg.pl/80x40/86b782/FFF/?text=Trial&font_size=18
[label-tech-radar-tools-assess-img]: https://fakeimg.pl/80x40/86b782/FFF/?text=Assess&font_size=18
[label-tech-radar-tools-hold-img]: https://fakeimg.pl/80x40/86b782/FFF/?text=Hold&font_size=18
[icon-octicon-question]: https://cdnjs.cloudflare.com/ajax/libs/octicons/4.4.0/svg/question.svg
[tw-tr-languages-frameworks]: https://thoughtworks.com/radar/languages-and-frameworks
[tw-tr-platforms]: https://thoughtworks.com/radar/platforms
[tw-tr-techniques]: https://thoughtworks.com/radar/techniques
[tw-tr-tools]: https://thoughtworks.com/radar/tools
[tw-tech-radar-faq-url]: https://www.thoughtworks.com/radar/a-z
[img-logo-commonality]: ./docs/img/logo-commonalaxy.png

[pr-lang-nygard]: https://github.com/commonality/architecture-decision-records/compare/adr-0001?quick_pull=1&title=adr(languages-frameworks):%20add%20MADR%20template&template=adr-nygard-template.md

<!-- ⛔️ LINK REFERENCES(End) ⛔️ -->
