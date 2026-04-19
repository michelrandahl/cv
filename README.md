# Michel Bøje Randahl Nielsen

_Backend & Cloud_ | _Functional Programming_ | _Embedded Rust_

michelrandahl@proton.me / Addr.: Holte, Denmark / [GitHub](https://github.com/michelrandahl) / [Codeberg](https://codeberg.org/michelrandahl) / [LinkedIn](https://linkedin.com/in/michel-randahl) / This CV: [michelrandahl.github.io/cv](https://michelrandahl.github.io/cv/)

## Profile
Software Developer with 7+ years of professional experience across backend systems, cloud applications, and fullstack solutions, currently focused on embedded Rust and hardware development.

## Work Experience
### Independent Learning & Hardware Product Development _(Aug 2023 - Present)_
Career break to develop embedded systems and electronics expertise, working toward commercial eurorack modules and musical controllers. During this period I have:
- Contributed to [Embassy](https://embassy.dev/), an open source embedded Rust ecosystem ([my contributions](https://github.com/embassy-rs/embassy/pulls?q=author:michelrandahl))
- Designed and programmed bare-metal firmware in Rust for [STM32 microcontrollers](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html), using the Embassy HAL with firmware built on both the Embassy async runtime and the [RTIC](https://rtic.rs/2/book/en/) framework
- Learned end-to-end PCB development: schematic design and PCB layout in [KiCAD](https://www.kicad.org/), manufacturing (JLCPCB, Aisler, PCBWay), component sourcing (Mouser), hand assembly and soldering, verification and troubleshooting
- Designed, manufactured, and programmed a custom PCB with MCU for evaluating capacitive touch-sensing configurations
- Currently developing a modular prototyping platform: a shared mainboard and MCU with interchangeable expansion boards, enabling rapid iteration on multiple module designs from a common foundation
- Worked on PureScript application projects during the first part of my career break: standalone applications running on NodeJS, API consumption (including LLM APIs), and web frontends using the PureScript Halogen framework
- Explored practical security topics through [OverTheWire](https://overthewire.org/wargames/) wargames and related reading

**_Technologies:_** Rust, Embedded Rust, Embassy, RTIC, KiCAD, STM32, PureScript, Halogen<br>
**_Key competencies gained:_** Hardware prototyping, PCB design and manufacturing, embedded firmware development, open source contribution

### Software developer and DevOps @ [Criipto](https://idura.eu) (now Idura) _(Dec 2021 - Aug 2023)_
At Criipto, a broker for government and bank-issued digital identities, I:
- Contributed to [Stripe](https://stripe.com/en-dk) integration and billing systems
- Worked on audit logging systems for digital identity usage tracking
- Implemented ETL jobs and supported data warehouse operations
- Developed demo applications, prototypes, and worked on the customer account management platform
- Automated infrastructure using [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep) (Infrastructure as Code) and [GitHub Actions](https://docs.github.com/en/actions) for CI/CD

**_Technologies:_** F#, C#, NodeJS, React, TypeScript, Azure, Bicep, Stripe, GitHub Actions<br>
**_Key competencies gained:_** Security-focused development practices, payment systems integration, cloud infrastructure automation

### Software developer @ [Skatteministeriet / UFST (Udviklings og Forenklingsstyrelsen)](https://www.ufst.dk/) _(Jan 2017 - Nov 2021)_
Contributed to the work towards modernizing Danish property valuation and taxation systems:
- Worked on the event-sourcing backend, API design and implementations, audit logging, internal tooling
- Designed and implemented custom [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) pipelines and data processing applications for technical and non-technical staff
- Participated in DevOps practices: infrastructure management and vulnerability response coordination with security leads

**_Technologies:_** Clojure, ClojureScript, AWS, Serverless architecture, Event Sourcing, PostgreSQL, Cassandra, Terraform, Docker, Jenkins<br>
**_Key competencies gained:_** Large-scale government project experience, collaboration across technical and non-technical teams, code review and pair programming practices, cloud application development, security vulnerability management

### Intern and part time Software developer @ Noitso _(Feb 2013 - Aug 2014)_
Financial technology and custom software development company. Co-developed a CRM solution (application and database design) and provided user support for existing software systems.

**_Technologies:_** C#, Java, JavaScript, HTML5, MSSQL, ASP MVC<br>

## Education
### MSc Computer Science and Engineering @ DTU _(Feb 2014 - Oct 2016)_
Studied topics such as Fault Tolerant Systems, Data Mining, Stochastic Simulation, Model Checking and Formal Software Engineering.
- Teaching Assistant for [Formal Aspects of Software Engineering](https://kurser.dtu.dk/course/2016-2017/02263) course
- Exchange semester at [Tohoku University, Sendai, Japan](https://www.eng.tohoku.ac.jp/english/) - coursework and project work in the space robotics lab
- **_MSc Thesis:_** [Model Checking Safety Properties of Distributed Railway Control Systems](http://www2.imm.dtu.dk/pubdb/edoc/imm6955.pdf)

### BEng Information Technology @ DTU _(Sep 2009 - Jan 2014)_
BEng thesis on predictive home lighting control using artificial neural networks. Internship at Noitso.

## Technical Competences
### Programming languages
Extensive experience across multiple languages with particular focus on functional programming:
- **Proficient:** [Rust](https://www.rust-lang.org/), [Clojure](https://clojure.org/), [F#](https://dotnet.microsoft.com/en-us/languages/fsharp), [PureScript](https://www.purescript.org/)
- **Previous experience:** Python, JavaScript/NodeJS, TypeScript, C#, Java
- **Studied and explored:** [Idris](https://www.idris-lang.org/), Haskell, [Elixir](https://elixir-lang.org/), [Elm](https://elm-lang.org/)
- **Testing approaches:** Beyond traditional unit testing, I have used and explored [property-based testing](https://en.wikipedia.org/wiki/Software_testing#Property_testing) across multiple languages

### Databases
- **MSSQL, PostgreSQL, SQLite**
- **Cassandra:** Familiarity with NoSQL concepts and distributed databases

### Cloud & DevOps
- **CI/CD:** GitHub Actions, automated testing and deployment pipelines
- **AWS:** ECS, Fargate, Lambda, SNS/SQS
- **Azure:** Functions
- **Infrastructure as Code:** CloudFormation, Bicep, Terraform

### Security
Security-aware, with interest in practical security topics:
- Worked on security-critical systems at the Danish Tax Ministry (UFST) and Criipto: CVE analysis, patching and dependency updates, audit logging, and vulnerability response coordination with security leads
- Consult [OWASP Top Ten](https://owasp.org/www-project-top-ten/) and similar resources when developing web applications and APIs
- Explore practical security topics through [OverTheWire](https://overthewire.org/wargames/) exercises

### Development environment
- **Linux:** 10+ years daily use; [NixOS](https://nixos.org/) for the past few years, and Debian prior to that
- **Workflow:** Terminal-driven; comfortable in CLI-first environments
- **Version control:** Git across professional, open source, and personal projects

## Speaking and Writing
Native Danish and proficient in English

## Beyond Code
- **Music:** Eurorack modular systems, synthesizers, and samplers
- **DIY Electronics:** Soldering and assembling Eurorack modules; built a custom rack for my modular system
- **Outdoors:** Forest walks, running, kayaking and [tinywhoop FPV](https://en.everybodywiki.com/Tiny_Whoop) drone flying
