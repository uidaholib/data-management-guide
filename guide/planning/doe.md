---
title: DOE Data Management & Sharing Plans
parent: Data Management Plans & Planning
nav_order: 5
---

# DOE Data Management & Sharing Plans (DMSPs)
Last Updated: April 13, 2026

The U.S. Department of Energy requires data management and sharing plans as part of all funded research projects. The University of Idaho provides the following resources to help researchers understand DOE's requirements and develop compliant plans using university resources.

<p style="background-color: #ffe6e6; border-left: 4px solid #cc0000; padding: 0.75em 1em; border-radius: 4px;">
As of <b>October 1, 2025</b>, DOE replaced Data Management Plans (DMPs) with <b>Data Management and Sharing Plans (DMSPs)</b> in all new solicitations. The transition is formalized in <b><a href="https://www.energy.gov/management/fal-2026-01-data-management-and-sharing-plan-dmsp-requirements">FAL 2026-01</a></b> (December 2025). If you are responding to a solicitation released after October 1, 2025, you must submit a DMSP rather than a DMP. Older templates and guidance materials may not reflect this change — always check the solicitation for the most current requirements.
</p>

## General Information

- [**DOE Requirements and Guidance for Digital Research Data Management**](https://www.energy.gov/datamanagement/doe-requirements-and-guidance-digital-research-data-management) - the central hub for all DOE data management policy, including requirements, suggested elements, and FAQs

- [**Writing a Data Management and Sharing Plan**](https://www.energy.gov/datamanagement/writing-data-management-and-sharing-plan) - step-by-step guidance on developing a DMSP, including the five suggested elements (data types, sources, and standards; related tools, software, and code; data access and reuse considerations; data security, preservation, and sharing; oversight of data management and sharing)

- [**DMPTool**](https://dmptool.org) - a free online tool for generating a data management plan compliant with funding agency requirements, including DOE. *Use your @uidaho email address when logging in.* Note that some DOE templates in DMPTool may be flagged as outdated — look for the most recent DOE Generic template.

- [**DOE Data Management FAQs**](https://www.energy.gov/datamanagement/frequently-asked-questions) - answers to common questions about DMSP requirements, timelines, and implementation

## DOE Programs

Individual DOE programs may modify or add to the DOE-wide DMSP requirements. Researchers should always check for program-specific guidance in their solicitation.

Individual facilities within programs may also have unique requirements. Guidance can be found on the DOE's [**resources page**](https://science.osti.gov/Funding-Opportunities/Digital-Data-Management#resources).

### Biological and Environmental Research (BER)

- [**BER Digital Data Management**](https://science.osti.gov/ber/Funding-Opportunities/Digital-Data-Management)
- BER has specific recommended repositories depending on the research area:
  - [ESS-DIVE](https://ess-dive.lbl.gov/) for Environmental System Science projects
  - [ARM Data Archive](https://www.arm.gov/data) for Atmospheric System Research
  - [AmeriFlux Network](https://ameriflux.lbl.gov/) for carbon flux data
- Data must be publicly accessible at the time of publication, with a maximum **one-year exclusive use period** after data acquisition ends.

### Advanced Scientific Computing Research (ASCR)

- [**ASCR Digital Data Management**](https://science.osti.gov/ascr/Funding-Opportunities/Digital-Data-Management)
- ASCR treats **software as a data artifact** — DMSPs must address software-specific issues including open source licensing, distribution format, discoverability, and handling of proprietary third-party dependencies
- DMP's must breifly discuss the issues below, if applicable:
  - The Open Source License to be used;
  - If executable versions of the software will also be released, and if so what format will be used;
  - How software can be found and accessed and the length of time the software will be publicly available;
  - How any proprietary 3rd party software or libraries are used in the creation of this software.
  - How Personally Identifiable Information (PII) will be properly handled.

### Energy Efficiency and Renewable Energy (EERE)

- [**EERE Digital Data Management**](https://www.energy.gov/eere/funding/digital-data-management)
- [**Suggested Elements for an EERE DMP**](https://www.energy.gov/eere/funding/suggested-elements-eere-data-management-plan)
- EERE adds a **Rationale/Impact** section to the DMSP, asking researchers to describe the data's potential impact in the field and broader societal implications

### Other DOE Offices

ARPA-E, the Office of Fossil Energy and Carbon Management (FECM), and other DOE offices generally follow the DOE-wide DMSP requirements. Always check the specific solicitation for any additional guidance. Program managers can clarify office-specific expectations.

## Data Repositories and DOIs

- DOE does **not** mandate a specific centralized repository. Researchers choose a discipline-appropriate repository that meets [NSTC Desirable Characteristics](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf).
- [**DOE Data Explorer**](https://www.osti.gov/dataexplorer/) - DOE's discovery portal for publicly available datasets funded by DOE. All public datasets must be reported to OSTI as research products.
- [**OSTI Data ID Service**](https://www.osti.gov/pids/doi-services/doe-data-id-service) - OSTI provides **free DOIs** for datasets produced by DOE-funded researchers. University faculty on DOE grants qualify. Submit via E-Link or API; contact DOEDataID@osti.gov for assistance.
- The University of Idaho's [VERSO Data Portal](https://verso.uidaho.edu/) is a FAIR-compliant repository that automatically issues DOIs and may be appropriate for some DOE-funded datasets. Contact the Library for guidance.

## Other Resources

- [**DOE Public Access Plan (2023)**](https://www.energy.gov/sites/default/files/2023-06/doe-public-access-plan-2023.pdf) - the governing policy document for DOE's approach to open science and data sharing
- [**FAL 2026-01: DMSP Requirements**](https://www.energy.gov/management/fal-2026-01-data-management-and-sharing-plan-dmsp-requirements) - the current Financial Assistance Letter implementing DMSP requirements across all DOE programs
- [**SC PuRe Data Resources**](https://science.osti.gov/Initiatives/PuRe-Data) - Office of Science-designated authoritative data resources across mission areas, operating under elevated standards for data stewardship

## TODO: Locally Hosted Resources

The following PDF resources would complement the external links above, similar to the locally hosted PDFs on the [NIH DMSP page]({{ '/guide/planning/nih/' | relative_url }}):

- [ ] **DOE DMSP Overview** — a summary of the DOE policy, timeline, and how DMSPs are reviewed (analogous to `2023-NIH-DMSP-overview.pdf`)
- [ ] **Elements of a DOE DMSP** — a detailed guide to the five suggested DMSP sections with examples (analogous to `Elements_of_DMSP.pdf`)
- [ ] **DOE DMSP Checklist** — a list of prompts to address in each section of a DMSP (analogous to `DMSP_Checklist.pdf`)

## Questions?

For assistance, contact either:
  - Jeremy Kenyon, Library [(jkenyon@uidaho.edu)](mailto:jkenyon@uidaho.edu), or
  - Andrew Child, RCDS [(awchild@uidaho.edu)](mailto:awchild@uidaho.edu) for assistance.
