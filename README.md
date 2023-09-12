# RESPONSIBLE AI INVESTING and SAFETY (RAIS) Framework

## Introduction
The RAIS framework provides guidance for venture capitalists looking at early-stage companies developing and deploying AI. This is a living framework that will evolve over time. We encourage firms to promote the benefits and mitigate the risks arising from AI as a powerful, general-purpose technology and to cultivate a collective sense of responisbility. 

## Table of Contents
- Usage
- Roadmap
- FAQ
- Contact

**## Usage**
The framework is intended as a guide for early-stage venture capital investors assessing early-stage companies creating and using AI as a meaningful aspect of their product. 

There are three main sections to the framework looking at different risk areas: social and ethical, industry-specific and regulatory, and technical.
![RAIS Screenshot 1](https://github.com/radicalventures/RAIS-Framework/assets/143823006/f4fbc646-fdc9-46d1-a976-1789709fea83)

**Vulnerability/Threats:** In each risk area, there are recommendations for the types of vulnerabilities and threats that could be listed. These are not prescriptive and should be adapted to the investor's responsible investment principles.  

**Risk**
Risk is calculated as a product of likelihood and impact. 
<img width="1074" alt="Screenshot 2023-09-12 at 12 52 58 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/0723581d-1425-46b0-95f1-eca81b85e61c">

**Initial Risk:** Assessing the initial risk against the likelihood and the impact on stakeholders and/or assets and the company if nothing is changed in the business or product. 

_Likelihood:_
Likelihood is a subjective measure ranging from 0 to 7 with 7 being 100% likely (i.e., guaranteed). The scale is intentionally odd in number to avoid selecting a number that represents a 50% likelihood – which should be viewed as a random chance of the vulnerability occurring (neither likely nor unlikely). All likelihoods should be assessed as either more or less likely to happen than a random occurrence. 
<img width="582" alt="Screenshot 2023-09-12 at 12 28 29 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/b5ad2b76-48c6-4e38-9418-eef5b19fcb4f">

_Impact:_
A guide has also been provided for assessing impact which is subject to adaptation for specific uses. 
<img width="321" alt="Screenshot 2023-09-12 at 12 32 48 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/d227c742-b370-4edd-a097-bc32a99ce9ae">

**Remaining Risk:** After assessing the initial risk of the vulnerability strategies to mitigate either the likelihood or the impact of the vulnerability should be considered. Given these are implemented the likelihood and impact should be reassessed resulting in a calculation of the remaining risk. 
<img width="616" alt="Screenshot 2023-09-12 at 12 30 13 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/986919fd-3653-4a75-9c95-0671737e9db8">

**Risk:** The risk-level is colour-coded based on 10-point intervals.  

<img width="618" alt="Screenshot 2023-09-12 at 12 44 08 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/7188d623-8357-4027-8898-1a99d95f32d5">

In the vulnerability rows, each vulnerability is given an initial and remaining risk reflected as a product of the likelihood and the impact scores. These are coloured with conditional formatting in Excel to match the risk-level matrix. 
<img width="560" alt="Screenshot 2023-09-12 at 12 49 30 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/81011382-dacb-4df9-9c86-ad304a4fe182">

Rows are averaged using a standard average if the risk is greater than 0 to produce an average initial risk and an average remaining risk. 
 <img width="1073" alt="Screenshot 2023-09-12 at 12 52 05 PM" src="https://github.com/radicalventures/RAIS-Framework/assets/143823006/0ec8fee4-4dc6-4893-b29e-5a96c2cc8c36">

**Note on the Regulatory Risk Area**: Likelihood in this risk area assesses the likelihood that the vulnerability would lead to non-compliance with relevant regulations dependent on industry and location. The impact is dependent on assessing the consequences of non-compliance.  

**Date of Last Update:** If any of the entries are changed across the columns a new date should be entered. 

**Format:** The framework is derived from the internal audit literature for AI systems (see [Raji & Smart, et al., 2020]([url](https://edwinwenink.github.io/ai-ethics-tool-landscape/tools/smactr/))). The framework leverages the ethical risk heat map format suggested for the testing phase of the internal audit. By partaking in the testing process, investors are doing diligence as enablers of the product development stages. 

It is recommended that as part of due diligence investors also ask for other relevant artefacts that may include AI principles, stakeholder maps, design history files for past product versions, or datasheets and model cards. Early companies should also create ethical principles, standards and AI principles, as well as a Product Requirements Document (PRD) or something similar for project planning. Recognizing that the RAIS Framework is intended for early-stage investors, this tool can effectively pinpoint areas requiring further analysis and the development of crucial internal audit documentation. The due diligence process for investment can take place even before a product has materialized, offering valuable insights to guide the creation of necessary artefacts as the company progresses beyond the ideation phase.

**Streamlining and Adaptation:**
This is a working draft open for iteration amongst the investment and AI builders community. Mitigation strategies should refer to best practices and tools documented in critical algorithm studies and the broader harm reduction community in the field of AI. Vulnerabilities and threats should focus limit focus as much as possible on the company's initial product and beachhead market or pilot to limit the extensive nature of this excerise.   

**The framework is intended as a guide and does not guarantee compliance with any applicable regulation. Use of the framework does not guarantee that a system is safe and that risks are adequately mitigated.** 

## Roadmap
 - [ ] Contribution instructions
 - [ ] Add license information
 - [ ] Add RAIS framework technical categories based on feedback from industry and AI research institutions 
 - [ ] Add case studies to usage
 - [ ] Release v.2 based on feedback
 - [ ] Add framework variations focused on particular technologies, applications, or other specifications. 

## FAQ 
**Q: How is Artificial Intelligence defined in the framework?**
**A:** The framework aims to assess companies developing and deploying across the toolchain including companies developing Foundation Models, as well as those leveraging model APIs. The framework should also include AI solutions and services including SaaS and AI-embedded functions, AI data pipeline companies, AI software modules, AI/ML lifecycle management platforms and tools, and AI-related infrastructure companies (often referred to as MLOps). 

**Q: Why is a venture capital fund creating a Responsible AI and Safety Framework?**
**A** Venture capital has become an essential driver of economic value. In 2020, venture capital-backed companies accounted for 41% of total US market capitalization and 62% of US public companies’ R&D spending. Among the public companies founded within the last fifty years, venture-funded companies account for half in number, three-quarters by value, and more than 92% of R&D spending and patent value. The fact that only approximately 0.5% of companies receive venture financing in the US demonstrates the disproportionate role that venture capital plays in the economy.

In 2022, there were 32 significant industry-produced machine learning models compared to just 3 produced by academia. Many of these companies received their first capital from venture investors. Building state-of-the-art AI systems increasingly requires large amounts of data, compute, and thus money. In addition to addressing nonprofit and academic access to these resources, it is important that investors have the appropriate tools and information to assess the technologies that gain access to funding.

Venture investors should use this as an early brainstorming tool. Investors at the earliest stages are helping to launch initial products and should be part of the ideation for product development and deployment. Additionally, understanding the required mitigation can inform the investment to ensure these tools and processes are adequately funded to reduce risk. 

**Q: Who is Radical Ventures?**
**A:** Radical Ventures is an AI-focused venture capital fund investing in world-leading entrepreneurs developing and applying AI to invent the future. Currently, Radical manages close to $1 billion of commitments under four funds. The portfolio is currently made up of approximately 50 investments across industries from healthcare to space. Globally, Radical Ventures has relationships with leading AI experts, research institutes, and early corporate adopters. In addition to its offices in Toronto, Canada, and Palo Alto, California, Radical Ventures recently added two partners based in London, United Kingdom. 

Radical Ventures is committed to developing AI technologies and applications that improve the future for all. The Investment Framework for Responsible AI is the first step in a larger strategy to put responsible AI in practice. 

## Contact
Leah Morris - Radical Ventures - [SafeAI@radical.vc](mailto:leah@radical.vc)
