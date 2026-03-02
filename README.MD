# Awesome Digital Public Infrastructure [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Digital Public Infrastructure (DPI) and Digital Public Goods (DPG) resources, tools, frameworks, and implementations.

**Digital Public Infrastructure** refers to shared digital systems — identity, payments, data exchange — that are open, interoperable, and reusable by both government and the private sector. **Digital Public Goods** are open-source software, data, AI models, and content standards that contribute to sustainable development.

*Maintained with field experience from UNICEF, UNDP, and real implementations in countries like Timor-Leste.*

---

## Contents

- [Frameworks & Standards](#frameworks--standards)
- [Certified DPGs by Domain](#certified-dpgs-by-domain)
  - [Health](#health)
  - [Identity & Civil Registration](#identity--civil-registration)
  - [Payments & Financial Inclusion](#payments--financial-inclusion)
  - [Education](#education)
  - [Climate & Environment](#climate--environment)
  - [Data Exchange & Interoperability](#data-exchange--interoperability)
  - [Child Protection & Social Protection](#child-protection--social-protection)
- [Country DPI Stacks](#country-dpi-stacks)
- [Toolkits & Assessment Frameworks](#toolkits--assessment-frameworks)
- [Organizations & Communities](#organizations--communities)
- [Research & Reports](#research--reports)
- [Courses & Learning](#courses--learning)
- [Jobs & Opportunities](#jobs--opportunities)
- [Field Notes](#field-notes)
- [Contributing](#contributing)

---

## Frameworks & Standards

> Authoritative frameworks that define and guide DPI/DPG development.

- [UNDP Digital Public Goods Standard](https://digitalpublicgoods.net/standard/) — Nine-indicator standard for certifying a solution as a Digital Public Good.
- [GovStack Reference Architecture](https://www.govstack.global/our-work/technical-specifications/) — Building-block approach to assembling government digital services.
- [ITU Digital Transformation Framework](https://www.itu.int/en/ITU-D/Pages/default.aspx) — ITU guidelines and metrics for national digital transformation.
- [OECD Digital Government Policy Framework](https://www.oecd.org/governance/digital-government/oecd-digital-government-policy-framework.htm) — Six dimensions for assessing digital government maturity.
- [World Bank DPI Framework](https://www.worldbank.org/en/topic/digitaldevelopment) — Policy and investment guidance for national digital infrastructure.
- [Co-Develop DPI Framework](https://www.co-develop.net/) — Practical guidance for countries designing sovereign DPI.
- [Principles for Digital Development](https://digitalprinciples.org/) — Nine principles for technology in development contexts.

---

## Certified DPGs by Domain

> Software certified by the [Digital Public Goods Alliance](https://digitalpublicgoods.net/) as Digital Public Goods. Only open-source, openly licensed solutions are listed.

### Health

| Solution | Description | License |
|----------|-------------|---------|
| [DHIS2](https://dhis2.org/) | Health information management system used in 100+ countries | BSD |
| [OpenMRS](https://openmrs.org/) | Open medical record system for resource-constrained environments | MPL 2.0 |
| [OpenHIM](http://openhim.org/) | Health interoperability middleware — openHIE reference implementation | MPL 2.0 |
| [iHRIS](https://www.ihris.org/) | Health workforce management system | GPL 3.0 |
| [Bahmni](https://www.bahmni.org/) | Hospital information system for low-resource settings | AGPL 3.0 |
| [OpenELIS](https://openelis-global.org/) | Laboratory information system | MPL 2.0 |

### Identity & Civil Registration

| Solution | Description | License |
|----------|-------------|---------|
| [MOSIP](https://mosip.io/) | Modular Open Source Identity Platform — national foundational ID | MPL 2.0 |
| [OpenCRVS](https://www.opencrvs.org/) | Civil registration and vital statistics system | MPL 2.0 |
| [OpenSPP](https://openspp.org/) | Social protection platform built on DPI principles | LGPL 3.0 |
| [OpenG2P](https://openg2p.org/) | Government-to-person benefit delivery infrastructure | MPL 2.0 |

### Payments & Financial Inclusion

| Solution | Description | License |
|----------|-------------|---------|
| [Mojaloop](https://mojaloop.io/) | Open-source payment platform for financial inclusion | Apache 2.0 |
| [OpenG2P](https://openg2p.org/) | G2P payment infrastructure — vouchers, cash transfers, benefits | MPL 2.0 |
| [Mifos X](https://mifos.org/) | Core banking platform for microfinance | MPL 2.0 |
| [Apache Fineract](https://fineract.apache.org/) | Open core banking platform for financial services | Apache 2.0 |

### Education

| Solution | Description | License |
|----------|-------------|---------|
| [Moodle](https://moodle.org/) | Learning management system used by 300M+ learners | GPL 3.0 |
| [H5P](https://h5p.org/) | Interactive HTML5 content and applications | MIT |
| [Kolibri](https://learningequality.org/kolibri/) | Offline-capable education platform for underserved communities | MIT |
| [OpenEDX](https://openedx.org/) | Open-source platform powering edX and 100+ national deployments | AGPL 3.0 |
| [Sunbird](https://sunbird.org/) | National digital infrastructure for learning (India's DIKSHA) | MIT |

### Climate & Environment

| Solution | Description | License |
|----------|-------------|---------|
| [OpenClimate](https://openclimate.network/) | Open data infrastructure for climate action transparency | Apache 2.0 |
| [SEPAL](https://sepal.io/) | FAO platform for geospatial analysis and forest monitoring | MIT |
| [ODK / OpenDataKit](https://getodk.org/) | Mobile data collection for field monitoring and reporting | Apache 2.0 |

### Data Exchange & Interoperability

| Solution | Description | License |
|----------|-------------|---------|
| [X-Road](https://x-road.global/) | Data exchange layer — backbone of Estonia's e-government | MIT |
| [OpenHIE](https://ohie.org/) | Health information exchange architecture and community | — |
| [FHIR](https://hl7.org/fhir/) | HL7 standard for healthcare data exchange | — |
| [KoboToolbox](https://www.kobotoolbox.org/) | Data collection for humanitarian and development contexts | GPL |
| [CommCare](https://www.dimagi.com/commcare/) | Mobile data collection for frontline health and social workers | Apache 2.0 |

### Child Protection & Social Protection

| Solution | Description | License |
|----------|-------------|---------|
| [Primero](https://www.primero.org/) | Child protection case management (UNICEF, UNHCR, IRC) | AGPL 3.0 |
| [RapidPro](https://app.rapidpro.io/) | Messaging platform for humanitarian and development programs | AGPL 3.0 |
| [CPIMS+](https://www.cpimsglobal.org/) | Child protection information management system | AGPL 3.0 |
| [OpenSRP](https://smartregister.org/) | Smart register platform for community health workers | Apache 2.0 |

---

## Country DPI Stacks

> Real-world national implementations. Each profile covers: DPI components deployed, key challenges, lessons learned, and open-source tools used.

| Country | DPI Highlights | Profile |
|---------|----------------|---------|
| 🇮🇳 India | Aadhaar ID, UPI Payments, ONDC Commerce, DigiLocker | [India Stack](docs/country-profiles/india.md) |
| 🇪🇪 Estonia | X-Road, e-Residency, KSI Blockchain, i-Voting | [Estonia](docs/country-profiles/estonia.md) |
| 🇧🇷 Brazil | PIX payments, GOV.BR identity, Open Finance | [Brazil](docs/country-profiles/brazil.md) |
| 🇹🇱 Timor-Leste | CPMIS, e-SISCA health, RDTL digital services | [Timor-Leste](docs/country-profiles/timor-leste.md) |
| 🇰🇪 Kenya | Huduma Namba, M-Pesa integration, eCitizen | *(coming soon)* |
| 🇷🇼 Rwanda | Irembo portal, National ID, Mobile money ecosystem | *(coming soon)* |
| 🇸🇳 Senegal | Wari, Orange Money, DER digital inclusion programs | *(coming soon)* |

---

## Toolkits & Assessment Frameworks

> Practical tools for planning, assessing, and implementing DPI/DPG.

### Digital Readiness & Assessment
- [ITU ICT Development Index](https://www.itu.int/en/ITU-D/Statistics/Pages/publications/mis/methodology.aspx) — Global benchmark for digital readiness across 167 countries.
- [OECD Digital Government Index](https://www.oecd.org/governance/digital-government/digital-government-index.htm) — Maturity model across 6 dimensions.
- [WEF Global Technology Governance Report](https://www.weforum.org/reports/global-technology-governance-report-2021/) — Framework for responsible digital infrastructure deployment.
- [DIAL Digital Investment Framework](https://digitalimpactalliance.org/research/digital-investment-framework/) — How to assess and prioritize DPG investments.

### Interoperability
- [GovStack Building Blocks](https://govstack.gitbook.io/specification/) — Technical specifications for interoperable government services.
- [OpenHIE Architecture](https://ohie.org/framework/) — Health information exchange reference architecture.
- [IHE Integration Profiles](https://www.ihe.net/resources/profiles/) — Integration profiles for healthcare interoperability.

### Procurement & Policy
- [UNICEF Venture Fund Guidance](https://www.unicef.org/innovation/venturefund) — How to fund and scale DPGs in development contexts.
- [Digital Square Global Goods Maturity Model](https://digitalsquare.org/global-goods-maturity-model) — Maturity model for health digital tools.
- [Open Source Policy Guide](https://github.com/OpenSourcePolicyCenter/toolkit) — Policy frameworks for government open source adoption.

---

## Organizations & Communities

> Key actors in the DPI/DPG ecosystem.

### UN System & Multilaterals
- [Digital Public Goods Alliance (DPGA)](https://digitalpublicgoods.net/) — Multi-stakeholder body defining and certifying DPGs.
- [UNICEF Office of Innovation](https://www.unicef.org/innovation/) — DPG investment and frontier technology for children.
- [UNDP Digital](https://www.undp.org/digital) — Digital transformation support for 170+ country offices.
- [ITU](https://www.itu.int/) — UN agency for information and communication technologies.
- [World Bank Digital Development](https://www.worldbank.org/en/topic/digitaldevelopment) — Financing and technical assistance for digital infrastructure.

### Foundations & Alliances
- [Digital Impact Alliance (DIAL)](https://digitalimpactalliance.org/) — Research and convening on digital development.
- [Digital Square](https://digitalsquare.org/) — Pathfinder Fund for global digital health goods.
- [Co-Develop Fund](https://www.co-develop.net/) — Philanthropic funding for DPI in low-income countries.
- [Gates Foundation Digital Financial Services](https://www.gatesfoundation.org/our-work/programs/global-growth-and-opportunity/financial-services-for-the-poor) — Financial inclusion through DPI.
- [Omidyar Network](https://omidyar.com/) — Investment in digital public infrastructure and open internet.

### Technical Communities
- [GovStack Community](https://www.govstack.global/) — Technical community for reusable government building blocks.
- [OpenHIE Community](https://ohie.org/) — Health information exchange implementers.
- [Digital Development Forum](https://www.digitaldevelopment.org/) — Community of practice for ICT4D practitioners.

---

## Research & Reports

> Foundational papers, impact studies, and policy briefs.

### Foundational Papers
- [The Case for a New Digital Bretton Woods](https://www.bu.edu/gdp/files/2022/05/GDP_PB_032_FIN.pdf) — Boston University Global Development Policy Center.
- [DPI: A Moonshot for Equitable Growth](https://www.co-develop.net/dpi-moonshot) — Co-Develop Fund, 2022.
- [Rethinking Digital Public Infrastructure](https://www3.weforum.org/docs/WEF_Rethinking_Digital_Public_Infrastructure.pdf) — World Economic Forum.

### Impact Studies
- [DHIS2 Impact](https://dhis2.org/impact/) — 30 years of health information infrastructure impact.
- [MOSIP Country Implementations](https://mosip.io/country.php) — National ID deployments across Africa and Asia.
- [Mojaloop Impact](https://mojaloop.io/impact/) — Financial inclusion through open payment infrastructure.

### Policy Briefs
- [OECD Going Digital Policy Notes](https://www.oecd.org/going-digital/policy-notes.htm) — Country-specific digital transformation notes.
- [AfDB Digital Transformation Strategy](https://www.afdb.org/en/topics-and-sectors/topics/digital-transformation) — Africa digital infrastructure priorities.

---

## Courses & Learning

> MOOCs, certifications, and structured learning paths.

### Free Online Courses
- [UNDP Digital for Development Academy](https://www.undp.org/digital/academy) — DPI, AI governance, and digital transformation.
- [ITU Academy](https://academy.itu.int/) — ICT policy, cybersecurity, and digital inclusion courses.
- [DHIS2 Academy](https://dhis2.org/academy/) — Free courses on health information systems.
- [ODK Documentation & Community](https://docs.getodk.org/) — Data collection infrastructure training.
- [GovStack Learning Path](https://www.govstack.global/learning/) — Technical training for government digital services.
- [DIAL Digital Principles e-Learning](https://digitalprinciples.org/learn/) — Best practices for technology in development.

### Certifications
- [ISACA CGEIT](https://www.isaca.org/credentialing/cgeit) — Governance of Enterprise IT.
- [Google Digital Futures](https://grow.google/) — Digital skills for public sector professionals.

---

## Jobs & Opportunities

> Where to find roles at the intersection of technology and development.

### Job Boards
- [DevNetJobs](https://www.devnetjobs.org/) — International development sector jobs, including tech roles.
- [ReliefWeb Jobs](https://reliefweb.int/jobs) — Humanitarian and development positions worldwide.
- [UN Careers](https://careers.un.org/) — Official UN Secretariat and agency job portal.
- [UNICEF Careers](https://www.unicef.org/careers/) — Including ICT and innovation roles.
- [ICTworks Job Board](https://www.ictworks.org/category/jobs/) — Jobs in ICT for development.

### Fellowships & Funding
- [DIAL Fellowship](https://digitalimpactalliance.org/get-involved/) — Digital development fellowships.
- [UNICEF Venture Fund](https://www.unicef.org/innovation/venturefund) — Equity-free funding for DPG startups.
- [Digital Square Open Calls](https://digitalsquare.org/opencalls) — Grants for global digital health goods.

---

## Field Notes

> Practical insights from real DPI implementations. *Contributed by practitioners with field experience.*

### From the Ground: Timor-Leste
- **Data collection before full infrastructure:** In fragile states, lightweight tools like KoboToolbox work better than complex HMIS until network and capacity are established.
- **Ministry buy-in is the hard part:** Technical implementation takes weeks; stakeholder alignment takes months.
- **Enforce consistent period identifiers early:** Cross-system reporting requires uniform cycle IDs (e.g., `MSSI_2026_q1`) from the data collection layer — retrofitting later is expensive.
- **Design for PDF too:** Even with digital infrastructure, email + PDF remains the fallback for senior government officials. Always design for both channels.

### Common DPI Pitfalls
- **Vendor lock-in disguised as DPI:** Verify true openness — check for open APIs, exportable data, and absence of proprietary dependencies before procuring.
- **"Digital first" without analog inclusion:** 30–40% of populations in many countries lack smartphones. DPI must support USSD, IVR, and in-person fallback channels.
- **Sustainability gaps:** Many donor-funded DPG deployments lack a post-project sustainability plan. Budget for operations from day one.
- **Interoperability as afterthought:** Connecting systems is 10x harder than building them. Start with the integration architecture, not the features.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To suggest a new resource: [open an issue](../../issues/new/choose) using the **Add Resource** template.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
