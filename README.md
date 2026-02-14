# Jon A. Chun

**Applied AI Researcher | Interdisciplinary Human-Centered AI Leader | Innovator**

Co-Founder with [Katherine Elkins](https://github.com/KatherineElkins) -- [Kenyon Human-Centered AI Colab](https://www.kenyon.edu/digital-humanities/)

[Google Scholar](https://scholar.google.com/citations?user=l-iUHQMAAAAJ&hl=en) | [Academia.edu](https://kenyon.academia.edu/jchun) | [LinkedIn](https://www.linkedin.com/in/jonchun2000/) | [Twitter/X](https://twitter.com/jonchun2000)

---

## Contents

- [Overview](#overview)
- [Current Research (2025--2026)](#current-research-20252026)
- [Published Research (2019--2024)](#published-research-20192024)
- [Open-Source Software](#open-source-software)
- [Grants & Affiliations](#grants--affiliations)
- [Education & Curriculum](#education--curriculum)
  - [Courses](#courses)
  - [Student Projects](#student-projects)
  - [DEI & Impact Metrics](#dei--impact-metrics)
  - [Program Timeline](#program-timeline)
- [Industry & Entrepreneurship](#industry--entrepreneurship)
- [Collaborations](#collaborations)
- [Organizations](#organizations)
- [Patents](#patents)

---

## Overview

Research scientist and AI leader specializing in interdisciplinary ML/AI applications across high-impact domains. Over the past decade, I've mentored over 300 original AI/ML projects spanning nearly every academic discipline -- from narrative and medicine to security and political science -- with work downloaded nearly 100k times by institutions including Stanford, MIT, Berkeley, Oxford, Amazon, and the Chinese Academy of Social Sciences.

I am currently serving as co-PI for the 25k-member Modern Language Assocation team in the NIST AI Consortium (former US AI Safety Institute) for LLM red/blue team testing. As of Jan 2026, I am also PI for one of 23 top AI research teams worldwide to have been awarded a Schmidt Sciences Humanity AI Virtual Instititue (HAVI) grant. As chief AI Architect, our interdisciplinary team from Columbia University, Berklee College of Music, and Louisiana State University is implementing a multilingual and multimodal archival digitial, restoration, and integrated graph database for early 1900s New Orlean Jazz collections. Previously, I lead research into tabular LLM recidivism prediction benchmarking for Notre Dame's Tech Ethics Lab on an IBM grant using multi-agent debates simluations of US bench trials. I have several papers for review at top-tier 2026 venues including ICML, FAccT, UAI, CogSci, TMLR, DMLR, JCP, and JAIR. Research focuses on AI safety and security, AI auditing and benchmarking, machine psychology/Theory of Mind, Affective AI, multi-agent workflow automation, and international AI policy and regulation.

Technical expertise spans LLM development and auditing, multimodal AI, automated agent frameworks, game theory simulations, and applying SOTA research to real-world problems in finance, healthcare, law, and narrative. I translate cutting-edge research into measurable products and services, having co-founded the world's first human-centered AI program bridging academia, research, and industry best practices.

Background includes Fortune 500 Director roles, Silicon Valley startup co-founder/CEO, and international experience across the US, Japan, and Latin America. Two US patents on network security. Published researcher with patents spanning gene therapy to AI policy.

**Languages:** English (native), Spanish (US Foreign Service Exam certified), Japanese (JLPT certified), French (professional working proficiency)

[Back to Top](#jon-a-chun)

---

## Current Research (2025--2026)

### Grants

**[Schmidt Sciences Humanities and AI Virtual Institute (HAVI)](https://www.schmidtsciences.org/humanities-and-ai-virtual-institute/)** (December 2025--Present)
*Principal Investigator and AI Architect -- 1 of 23 HAVI grants awarded to leading AI research teams worldwide (top 2-3%)*

"Archival Intelligence: Can AI Rescue Endangered Archives" -- Co-PI and AI Architect leading an interdisciplinary team of scholars in jazz studies, musicology and CS from Columbia University, Berklee College of Music, and Louisiana State University. A team of AI researchers, archival scientists, jazz historians, and New Orleans cultural experts racing to preserve endangered small community archives using only smartphone photos, with AI to recover portions lost to damage. This 18-month pilot tackles the hardest cases by focusing on voices systematically excluded from historical archives: multilingual newspapers documenting Creole and Cajun communities as well as early jazz materials.

---

### Papers Under Review / Submitted (2026)

#### ["The Paradox of Robustness: Decoupling Rule-Based Logic from Affective Noise in High-Stakes Decision-Making"](https://arxiv.org/abs/2601.09724)

*Pending*

While LLMs are widely documented to be sensitive to minor prompt perturbations, we uncover a striking "Paradox of Robustness": instruction-tuned LLMs exhibit 110--300x greater resistance to narrative manipulation than human subjects. Using a controlled perturbation framework across healthcare, law, and finance, we find a near-zero effect size (Cohen's h = 0.003) compared to substantial human biases (h = 0.3--0.8).

---

#### "When 'Should Not' Becomes 'Should': A Robustness Framework for Measuring Negation Fragility in LLM Decisions Across 23 Models"

*Submitted to ICML 2026*

Introduces Syntactic Framing Fragility (SFF), the first framework for quantifying decision consistency under logically equivalent syntactic transformations. SFF isolates syntactic effects via Logical Polarity Normalization (LPN) and provides the Syntactic Variation Index (SVI) as a CI/CD-ready robustness metric.

---

#### "Biased or Just Noisy? Why Aggregate AI Audits Miss Scenario-Specific Vulnerability"

*Submitted to FAccT 2026 (ACM Conference on Fairness, Accountability, and Transparency)*

Audits seven language models for narrative vulnerability -- the tendency to let emotionally compelling but policy-irrelevant content shift rule-bound decisions. Demonstrates how aggregate and scenario-level analyses can diverge in ways consequential for deployment.

---

#### "When Prohibitions Become Permissions: Auditing Negation Sensitivity in Language Models"

*Pending*

---

#### "Quantal Response Equilibrium as a Measure of Strategic Sophistication: Theory and Validation for LLM Evaluation"

*Submission for UAI 2026 (Conference on Uncertainty in Artificial Intelligence)*

Introduces a game-theoretic evaluation framework grounded in quantal response equilibrium (QRE). Theory of Mind benchmarks for LLMs typically produce aggregate scores without theoretical grounding; our approach offers three methodological advances addressing whether high performance reflects strategic reasoning or surface-level heuristics.

---

#### "Pragmatic Inefficiency in Language Models: Compositional Integration Failures Across Social Hierarchies"

*Submitted to CogSci 2026 (Cognitive Science Society)*

Uses large language model failures as a novel probe of pragmatic architecture. Compositional generalization tests reveal that models fail to bind features appropriately: accuracy drops 13--14% on novel context-utterance combinations, with 69% of predictions anchored to utterance patterns regardless of context.

---

#### "CEI: A Benchmark for Evaluating Pragmatic Reasoning in Language Models"

*Pending (Dataset Track)*

Presents the Contextual Emotional Inference (CEI) Benchmark: 300 human-validated scenarios for evaluating how well LLMs disambiguate pragmatically complex utterances. Each scenario pairs situational context and speaker-listener roles with explicit power relations against an ambiguous utterance.

---

#### "AgenticSimLaw: A Multi-Agent Courtroom Debate Framework for Explainable Recidivism Prediction from Tabular Data"

*Pending | Extended version of AAAI-26 LaMAS accepted paper | [IBM-Notre Dame Tech Ethics Lab Grant](https://techethicslab.nd.edu/call-for-proposals/)*

Role-structured, multi-agent debate framework providing transparent and controllable test-time reasoning for recidivism prediction from tabular data. Benchmarked across ~90 unique model-strategy combinations on the NLSY97 dataset.

---

#### "The Cyber Governance Trilemma: Comparative AI Regulation in the EU, China, and the United States"

*Pending*

---

#### "ESP-Ethical Audit: An Ethical Alignment Audit to Quantify Biased Decision-Making with Emotion and Syntactic Framing"

*(In Review)*

Tests whether LLM decision-making aligns with human values and whether that alignment reveals biases typical of human cognition. Measures confidence levels across moral scenarios while testing perturbations along syntactic framing and empathic backstory dimensions. Finds more performant models more closely mirror human biases, raising safety concerns about persuasion, manipulation, and deception.

---

### Published / Accepted (2025--2026)

#### ["Syntactic Framing Fragility: An Audit of Robustness in LLM Ethical Decisions"](https://arxiv.org/abs/2601.09724)

*ArXiv Preprint (December 2025)*

Auditing 23 SOTA models over 14 ethical scenarios and four controlled framings (39,975 decisions), we find widespread inconsistency: many models reverse ethical endorsements solely due to syntactic polarity, with open-source models exhibiting over twice the fragility of commercial counterparts. Chain-of-thought reasoning substantially reduces fragility.

---

#### ["AgenticSimLaw: A Juvenile Courtroom Multi-Agent Debate Simulation for Explainable High-Stakes Tabular Decision Making"](https://openreview.net/pdf?id=92kj14Wa8z)

*Accepted: AAAI-26 LaMAS (Singapore, January 2026) | [IBM-Notre Dame Tech Ethics Lab Grant](https://techethicslab.nd.edu/call-for-proposals/)*

Courtroom-style orchestration with explicit agent roles (prosecutor, defense, judge), 7-turn structured debate, and private reasoning strategies. Structured multi-agent debate provides more stable and generalizable performance compared to single-agent reasoning across ~90 model-strategy combinations.

[Back to Top](#jon-a-chun)

---

## Published Research (2019--2024)

### 2024

- ["Comparative Global AI Regulation: Policy Perspectives from the EU, China, and the US"](https://arxiv.org/abs/2410.21279) -- *SSRN and ArXiv*
- ["AIStorySimilarity: Quantifying Story Similarity Using Narrative for Search, IP Infringement, and Guided Creativity"](https://aclanthology.org/2024.conll-1.13/) -- *ACL EMNLP/CoNLL, Miami*
- ["MultiSentimentArcs: Affective AI and Multimodal Diachronic Sentiment Analysis"](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1444549/full) -- *Frontiers in Computer Science*
- ["In Search of a Translator: Using AI to Evaluate What's Lost in Translation"](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1444021/full) -- *Frontiers in Computer Science*
- ["Near to Mid-term Risks and Opportunities of Open-Source Generative AI"](https://arxiv.org/abs/2404.17047) -- *ICML 2024, Vienna* (with [long form version](https://arxiv.org/abs/2405.08597))
- ["Informed AI Regulation: Comparing the Ethical Frameworks of Leading LLM Chatbots"](https://arxiv.org/pdf/2402.01651) -- *ArXiv*

### 2023

- ["eXplainable AI with GPT4 for Story Analysis and Generation"](https://link.springer.com/article/10.1007/s42803-023-00069-8) -- *Springer International Journal of Digital Humanities* 5, 507--532
- ["The Crisis of Artificial Intelligence: A New Digital Humanities Curriculum for Human-Centred AI"](https://www.euppublishing.com/doi/abs/10.3366/ijhac.2023.0310?journalCode=ijhac) -- *International Journal of Humanities and Arts Computing* 17, 147--167

### 2019--2022

- ["What the Rise of AI Means for Narrative Studies"](https://muse.jhu.edu/article/846035) -- *Narrative* 30, no. 1 (2022): 104--113
- ["SentimentArcs: A Novel Method for Self-Supervised Sentiment Analysis of Time Series"](https://arxiv.org/abs/2110.09454) -- *ArXiv* (2021)
- [AI Improv DivaBot](https://www.youtube.com/watch?v=Ldb0vlCQXtQ&t=1s) -- World's first live Human-AI improvisation with GPT (2021)
- ["Can GPT-3 Pass a Writer's Turing Test?"](https://culturalanalytics.org/article/17212.pdf) -- *Journal of Cultural Analytics* 5, no. 2 (2020)
- [How Artificial Intelligence Tells Stories: NLG and Narrative](https://github.com/jon-chun/conference-narrative2020-GPT2-NLG) -- *Narrative 2020*, New Orleans
- ["Can Sentiment Analysis Reveal Structure in a Plotless Novel?"](https://arxiv.org/abs/1910.01441) -- *ArXiv* (2019)

### Medical Research & Informatics

- Lamping KG, Rios CD, **Chun JA** et al. "Intrapericardial Administration of Adenovirus for Gene Transfer." *Am J Physiol.* 1997. PMID: 9038951
- Flanagan JR, **Chun J**, Wagner JR. "Evolution of a Legacy System to a Web Patient Record Server." *Proc AMIA Annu Fall Symp.* 1996. PMID: 8947740

*SentimentArcs is the open-source code for [The Shapes of Stories](https://www.amazon.com/Stories-Elements-Digital-Literary-Studies/dp/1009270397) by Katherine Elkins (Cambridge UP, 2022)*

[Back to Top](#jon-a-chun)

---

## Open-Source Software

- **[SentimentArcs](https://github.com/jon-chun/sentimentarcs_notebooks)** -- Largest ensemble for diachronic sentiment analysis; basis for *The Shapes of Stories* (Cambridge UP, 2022)
- **[MultiSentimentArcs](https://github.com/jon-chun/multisentimentarcs)** -- First fully open-source diachronic multimodal sentiment analysis framework
- **[AIStorySimilarity](https://github.com/jon-chun/AIStorySimilarity)** -- Benchmark for long-text story similarity using narrative theory
- **[LLM Ethics Audit](https://github.com/jon-chun/llm-sota-chatbots-ethics-based-audit)** -- Ethics-based audit framework for leading LLM chatbots

![Block diagram showing SentimentArcs architecture](images/fig_sentimentarcs_blocks.png)
*Block Diagram for [SentimentArcs Notebooks](https://github.com/jon-chun/sentimentarcs_notebooks)*

[Back to Top](#jon-a-chun)

---

## Grants & Affiliations

| Grant / Affiliation | Role | Year |
|---|---|---|
| [Schmidt Sciences HAVI](https://www.schmidtsciences.org/humanities-and-ai-virtual-institute/) -- "Archival Intelligence" | Principal Investigator and AI Architect (1 of 23 worldwide) | 2025-- |
| [NIST AI Safety Institute Consortium](https://www.nist.gov/aisi/artificial-intelligence-safety-institute-consortium-aisic) (for [MLA](https://www.mla.org/)) | Lead AI Safety Researcher | 2024-- |
| [IBM-Notre Dame Tech Ethics Lab](https://techethicslab.nd.edu/call-for-proposals/) -- "How Well Can GenAI Predict Human Behavior?" | Co-PI | 2024 |
| Meta Global Scholars Research Group | Member | 2023-- |
| [AI Alliance Essential AI Competencies Guide](https://thealliance.ai/core-projects/guide-to-essential-competencies-for-ai) (Meta, IBM, Intel) | Contributor | 2024 |
| National Endowment for the Humanities (NEH) | Program Support | 2018 |

[Back to Top](#jon-a-chun)

---

## Education & Curriculum

I creatively apply industry best practices and state-of-the-art AI/ML techniques to high-impact interdisciplinary research. Our paper [The Crisis of Artificial Intelligence](https://www.euppublishing.com/doi/full/10.3366/ijhac.2023.0310?journalCode=ijhac), published in the *International Journal of Humanities and Computing*, outlines the challenges and opportunities AI presents to higher education, as well as the theory, structure, and goals of our human-centered AI approach.

Our human-centered curriculum is designed to be collaborative at multiple levels and interdisciplinary while maintaining academic rigor. Students from virtually every department across campus create a unique classroom learning and research environment. Research from our AI Colab has contributed to collaborative projects with institutions including Oxford, UC Berkeley, CMU, and Harvard Business School. We focus on productive collaborations to operationalize solutions to the "big questions" central to the Liberal Arts experience, including partnerships with industry leaders (Meta, IBM), government agencies (NIST AI Safety Institute), and non-profits (AI Alliance, MLA, US Chamber of Commerce, The Helix Center).

### Courses

| Course | Title | Introduced |
|---|---|---|
| [IPHS 200](https://digital.kenyon.edu/dh_iphs_prog/) | Programming Humanity | Fall 2017 |
| [IPHS 290](https://jon-chun.github.io/cultural-analytics/) | Cultural Analytics | Fall 2022 |
| [IPHS 300](https://digital.kenyon.edu/dh_iphs_ai/) | AI for the Humanities | 2019 |
| [IPHS 391](https://github.com/jon-chun/GenAI-Multi-Agent-Networks-and-Digital-Twins) | Frontiers in Generative AI: Autonomous Agent Networks | Fall 2024 |
| [IPHS 484](https://digital.kenyon.edu/dh_iphs_ss/) | Senior Seminar/Research | 2018 |
| Custom | [Industrial IoT Predictive Maintenance](https://github.com/jon-chun/iiot-time-series-prediction-system) | 2021 |

### Student Projects

**Sample projects using SentimentArcs:**
- Literature: [Sentiment Analysis and Nabokov's Pale Fire](https://digital.kenyon.edu/dh_iphs_ai/12/)
- Translations: [Cross-Linguistic Survey of Kafka's Trial](https://digital.kenyon.edu/dh_iphs_prog/55/)
- TV Scripts: [Storytelling and Sentiment Analysis in Shark Tank](https://digital.kenyon.edu/dh_iphs_ss/4/)
- Medical Narratives: [Five Stages of Grief in End-of-Life Memoirs](https://digital.kenyon.edu/dh_iphs_ss/20/)
- Social Media: [Sri Lankan Protestors and Political Change](https://digital.kenyon.edu/dh_iphs_prog/59/)
- Elections: [Quantifying Polarization around Election Denial](https://digital.kenyon.edu/dh_iphs_prog/66/)

**Sample projects from Frontiers in Generative AI (Fall 2024):**
- [AI-Powered MLB Roster Construction](https://digital.kenyon.edu/dh_iphs_391/1/)
- [AI-Powered Appointment Prioritization for Resource-Poor Settings](https://digital.kenyon.edu/dh_iphs_391/2/)
- [PitchAI: Streamlining Investment Banking Pitches Using LLMs](https://digital.kenyon.edu/dh_iphs_391/4/)
- [Ancient Greek Parsing with AI: Agentic System](https://digital.kenyon.edu/dh_iphs_391/7/)
- [AI Chatbot for College Disability Services Support](https://digital.kenyon.edu/dh_iphs_391/6/)
- [Agentic Framework for Data-Driven Cricket Player Scouting](https://digital.kenyon.edu/dh_iphs_391/5/)

**More projects:** [IPHS 200](https://digital.kenyon.edu/dh_iphs_prog/) | [IPHS 300](https://digital.kenyon.edu/dh_iphs_ai/) | [IPHS 391](https://digital.kenyon.edu/dh_iphs_391/) | [IPHS 484](https://digital.kenyon.edu/dh_iphs_ss/)

### DEI & Impact Metrics

![Blackboard showing Fall 2022 class photo](images/ascension_blackboard_2022fall.jpg)

| Metric | Value |
|---|---|
| **Research downloads** | 85k+ (as of Jan 2026) |
| **Institutions reached** | 2,700+ in 160+ countries |
| **Top visitors** | Stanford, Berkeley, CMU, NYU, Columbia, MIT, Princeton, Oxford, Cambridge |
| **Projects mentored** | 400+ since 2017 |
| **Female enrollment** | 61% (grew from 18% in 2017) |
| **Non-STEM majors** | >90% |
| **Black students** | 13% |
| **Latine students** | 11% |
| **Drop rate / Pass rate** | 0% / 100% |
| **Enrollment growth** | 20 to 120 students (2017--2022) |

![Gender diversity progress](images/iphs_ai_dh_gender.jpg)
*Progress on gender diversity since 2017 (61% female as of Spring 2022)*

![Non-STEM majors chart](images/iphs_ai_dh_stem.jpg)
*Over 90% non-STEM majors (Kenyon College Institutional Research)*

### Program Timeline

- **1992--99**: IPHS established a computer lab for DH scholarship under Director Michael Brint
- **July 2002**: Katherine Elkins joined Kenyon, mentoring computational projects in IPHS
- **May 2003**: Launched Symantec Clientless VPN appliance as Director of Development; relocated from Silicon Valley
- **March 2005**: Proposed human-centered AI curriculum with [Ewing Marion Kauffman Foundation](https://philanthropynewsdigest.org/news/morgan-kauffman-foundations-launch-liberal-arts-entrepreneurship-initiative) grant
- **August 2015**: Formulated detailed interdisciplinary AI curriculum
- **March 2017**: Led Kenyon Team at [HackOH5](https://hackoh5.ohio5.org/) Hackathon
- **August 2017**: First [Programming Humanity](https://digital.kenyon.edu/dh_iphs_prog/) course
- **August 2018**: First [AI for the Humanities](https://digital.kenyon.edu/dh_iphs_ai/) course; Katherine Elkins awarded [NEH Distinguished Professorship](https://www.kenyon.edu/offices-and-services/office-of-the-provost/recognition/neh-professorship/)
- **August 2022**: First [Cultural Analytics](https://jon-chun.github.io/cultural-analytics/) course; first [Industrial IoT](https://github.com/jon-chun/iiot-time-series-prediction-system) collaboration
- **2023**: Joined Meta Global Scholars Research Group
- **2024**: Co-PI for [NIST AI Safety Institute Consortium](https://www.nist.gov/aisi/artificial-intelligence-safety-institute-consortium-aisic-members); Co-PI for [IBM-Notre Dame Tech Ethics Grant](https://techethicslab.nd.edu/); first [Frontiers in Generative AI](https://github.com/jon-chun/GenAI-Multi-Agent-Networks-and-Digital-Twins) course
- **2026**: Co-PI for [Schmidt Sciences HAVI](https://www.schmidtsciences.org/humanities-and-ai-virtual-institute/) grant

[Back to Top](#jon-a-chun)

---

## Industry & Entrepreneurship

### Career Summary

| Role | Organization | Location | Years |
|---|---|---|---|
| Co-PI / Instructor | Kenyon College | Gambier, OH | 2017-- |
| AI Expert and Industry Analyst | BWG Strategy | New York, NY | 2023-- |
| Entrepreneur in Residence | UC Berkeley COE | Berkeley, CA | 2005--07 |
| Director, Development | Symantec Corp. | Redwood City, CA | 2003--04 |
| President & CEO | SafeWeb, Inc. | Emeryville, CA | 2000--03 |
| CTO | Latin eVentures | Irvine, CA / Sao Paulo | 1999--00 |
| Director of IT | Matrix Absence Mgmt (NYSE: DFG) | San Jose, CA | 1997--99 |
| Web/DB Consultant | Adecco, Stanford University | Palo Alto, CA | 1996--97 |
| AMA Research Fellow | U of Iowa Hospitals & Clinics | Iowa City, IA | 1995--96 |
| Japanese Localization Engineer | Dell (NYSE: DELL) | Austin, TX | 1995 |
| Japanese Technical Analyst | SEMATECH | Austin, TX | 1994 |
| Programmer Analyst | MMS Int'l / McGraw-Hill | Tokyo, Japan | 1990--91 |
| Research Programmer | Lawrence Berkeley Labs | Berkeley, CA | 1987--90 |
| Sales Engineer | Computer Associates (NYSE: CA) | Los Angeles, CA | 1984--85 |

### Key Highlights

- **SafeWeb** (Co-Founder/CEO): Built world's largest online privacy service (2B transactions in 8 months). Secured $11M from Wall Street funds + first security investment from In-Q-Tel (CIA). Pivoted to enterprise SSL VPN; drove $26M acquisition by Symantec at 35x revenue. ([Products](https://drive.google.com/drive/folders/1ZhQzKM5i6ZnHGmhTphs6Vq2uBTw4jchx?usp=sharing))
- **Symantec** (Director): Launched Clientless VPN Gateway in one quarter, under budget, with 2/3 team. 400K LOC release, zero attrition through acquisition integration.
- **Matrix Absence Management** (Director of IT): Architected B2B systems for 200+ high-tech clients (Intel, Dell, Cisco). Led $25M Unisys due diligence.
- **Latin eVentures** (CTO): Multi-million-dollar B2B portal-ERP across Latin America in 3 languages. Saved $500K in vendor renegotiations.

[Back to Top](#jon-a-chun)

---

## Collaborations

**Government & Policy**
- US White House AI Safety Policy / NIST AI Safety Institute (NIST, MLA)
- Comparative Global AI Regulation (SSRN, ArXiv, Journal of Cyber Policy)

**Industry & Research**
- Meta Global Scholars Research Group
- AI Alliance Essential AI Competencies Guide (Meta, IBM, Intel, US Chamber of Commerce)
- BWG Strategy -- Tech strategy and AI investing (NYC)
- IBM-Notre Dame Tech Ethics Lab

**Academic**
- Collaborative AI Safety and Open Source Policy (Oxford, Berkeley, UVa, Berklee/MIT)
- AI and the Future of Higher Education (Notre Dame, CMU, UC Berkeley, Harvard Business School)
- Computational Law, Ethics and XAI (ACM, Northwestern Law, IBM, Notre Dame)
- Multimodal Affective AI (Meta, NEH, EMNLP/CoNLL)
- Narrative and Affective AI (Yale, Harvard, Narrative Conferences)
- NLP and AI Research (ICML, ACL, ACM, CogSci, UAI, AAAI, FAccT)
- Theoretical Computer Science (McGill, UPitt, CMU)
- Psychology and Cognitive Science (Ohio State University)
- Literature, Language, Linguistics (MLA, Cambridge UP)
- Theatre and Film (Denison, NEH, LA Theatre)

**Other Domains**
- Medicine / FDA (AFDO/RAPS)
- Physics and Engineering Simulations (NAFEMS)
- IoT Predictive Maintenance (Kenyon AI Colab, Weyerhaeuser Paper)
- Computer and Network Security (USPTO, Symantec)
- Electronic Medical Records (U of Iowa, American Medical Informatics)
- Financial Information Systems (Bloomberg/McGraw-Hill Tokyo)
- Semiconductor Research (SEMATECH, Lawrence Berkeley Labs)

[Back to Top](#jon-a-chun)

---

## Organizations

### [US NIST AI Safety Institute Consortium](https://www.nist.gov/aisi/artificial-intelligence-safety-institute-consortium-aisic)

**Lead AI Safety Researcher** (2024--) for the [Modern Language Association](https://www.mla.org/) (25,000 members worldwide)

[Announcement](https://news.mla.hcommons.org/2024/04/16/mla-will-participate-in-department-of-commerce-consortium-dedicated-to-ai-safety/): The MLA is joining more than 200 of the nation's leading AI stakeholders in a US Department of Commerce initiative for trustworthy and safe AI. The MLA-sponsored team, led by Katherine Elkins and Jon Chun at Kenyon College, evaluates model capabilities with a special focus on linguistic edge cases and ethical frameworks.

### [Human Centered AI Lab.Org](https://humancenteredailab.org/portfolio/)

**Founder** (January 2024--)

A volunteer, wholly virtual non-profit facilitating interdisciplinary AI collaboration between researchers and domain experts on safety, bias, explainability, ethics, and policy.

### [The Helix Center](https://www.helixcenter.org/), New York, NY

**Executive Board Member** (November 2022--)

Interdisciplinary roundtables drawing together leaders from arts, humanities, sciences, and technology. ([Living in Difficult Times](https://www.helixcenter.org/participants/jon-chun/), November 2022)

### Kenyon AI Colab

![Kenyon AI Colab logo](images/logo_tilt5_kenyon_dh_colab.png)

- [Interdisciplinary AI/ML Projects](https://digital.kenyon.edu/dh/)
- [Kenyon Digital Colab](https://www.kenyon.edu/digital-humanities/kdh-colab/)
- [Kenyon Interdisciplinary Human-Centered AI Program](https://www.kenyon.edu/digital-humanities/)

![Top institutions reading research](images/screen_kenyon_dh_analytics0.png)
*Top 10 Institutions reading our AI DH Research -- [digital.kenyon.edu/dh](https://digital.kenyon.edu/dh/)*

![Map: Eurasian institutions](images/kenyon_dh_20230514_map_eurasia.png)
*Eurasian Institutions*

![Map: Americas institutions](images/kenyon_dh_20230514_map_americas.png)
*Institutions from The Americas*

[Back to Top](#jon-a-chun)

---

## Patents

1. **Chun, Jon A.**, Stephen Dao Hui Hsu, James Noshir Hormuzdiar; Symantec Corp. "Intelligent Secure Data Manipulation Apparatus and Method." US Patent 7,730,528 B2 (June 1, 2010). ([Patents folder](https://drive.google.com/drive/folders/15UPcgB-SfwiUBers10c3qpMAB_bF0BJL?usp=sharing))

2. Stephen Dao Hui Hsu, James Noshir Hormuzdiar, **Jon A. Chun**; Symantec Corp. "Method and Apparatus for Encrypted Communications to a Secure Server." US Patent 8,065,520 (November 22, 2011).

[Back to Top](#jon-a-chun)


