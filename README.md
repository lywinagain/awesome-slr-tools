# Awesome Systematic Literature Review (SLR) Tools

A comprehensive collection of tools, resources, and tutorials for conducting systematic literature reviews. Perfect for young researchers starting their SLR journey!

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> **💡 New to Systematic Literature Reviews?** Start with the [Quick Start Guide](#-quick-start-guide) below!

## Table of Contents

- [🚀 Quick Start Guide](#-quick-start-guide)
- [📊 Recommended Workflow](#-recommended-workflow)
- [What is Systematic Literature Review?](#what-is-systematic-literature-review)
- [Key Journals & Publications](#key-journals--publications)
- [Planning & Protocol](#planning--protocol)
- [Search & Discovery](#search--discovery)
  - [Search Strategy Development Tools](#search-strategy-development-tools)
  - [Grey Literature & Special Databases](#grey-literature--special-databases)
  - [Citation Discovery](#citation-discovery)
  - [API Resources](#api-resources)
- [Study Management](#study-management)
- [Screening & Selection](#screening--selection)
  - [AI-Powered Screening Tools](#ai-powered-screening-tools)
  - [Web-Based Screening Platforms](#web-based-screening-platforms)
- [Data Extraction](#data-extraction)
  - [AI-Powered Data Extraction](#ai-powered-data-extraction)
  - [PICO Extraction Systems](#pico-extraction-systems)
  - [Data Extraction Templates](#data-extraction-templates)
- [Quality Assessment](#quality-assessment)
  - [Study Design-Specific Tools](#study-design-specific-tools)
  - [Qualitative & Mixed Methods Tools](#qualitative--mixed-methods-tools)
  - [Visualization & Evidence Grading](#visualization--evidence-grading)
- [Analysis & Synthesis](#analysis--synthesis)
- [Visualization](#visualization)
- [Writing & Reporting](#writing--reporting)
- [Reference Management](#reference-management)
  - [Deduplication Tools](#deduplication-tools)
- [Collaboration Tools](#collaboration-tools)
- [AI-Powered Tools](#ai-powered-tools)
- [Open Source Tools & GitHub Repositories](#open-source-tools--github-repositories)
  - [Python Libraries & Tools](#python-libraries--tools)
  - [R Packages](#r-packages)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Learning Resources](#learning-resources)
  - [Comprehensive Methodology Guides](#comprehensive-methodology-guides)
  - [University Library Guides](#university-library-guides)
- [Specialized Review Types & Methodologies](#specialized-review-types--methodologies)
  - [Living Systematic Reviews](#living-systematic-reviews)
  - [Rapid Review Methodologies](#rapid-review-methodologies)
  - [Scoping Review Tools & Frameworks](#scoping-review-tools--frameworks)
  - [Umbrella Review Tools](#umbrella-review-tools)
  - [Realist Review Frameworks](#realist-review-frameworks)
  - [Protocol Registration Platforms](#protocol-registration-platforms)
  - [Qualitative Synthesis Methods](#qualitative-synthesis-methods)
- [⚠️ Common Challenges & How to Avoid Them](#%EF%B8%8F-common-challenges--how-to-avoid-them)
- [📝 Practical Examples & Templates](#-practical-examples--templates)
- [❓ FAQ for Young Researchers](#-faq-for-young-researchers)

---

## 🚀 Quick Start Guide

**Choose your path based on your needs:**

### For Beginners (Just Starting)
1. **Learn the basics**: Read [Systematic Literature Review: Easy Guide](https://www.languageonthemove.com/systematic-literature-review-easy-guide/)
2. **Follow standards**: Download [PRISMA 2020 Checklist](https://www.prisma-statement.org/)
3. **Start simple**: Use [Rayyan](https://www.rayyan.ai/) (free) or [Covidence](https://www.covidence.org/) (free trial)
4. **Manage references**: Install [Zotero](https://www.zotero.org/) (free, open-source)

### For Developers/Programmers
1. **Install Python tools**: `pip install asreview litstudy`
2. **Install R packages**: `install.packages(c("metafor", "bibliometrix", "PRISMA2020"))`
3. **Explore GitHub**: Browse [systematic-review topic](https://github.com/topics/systematic-review)
4. **Try notebooks**: Use [Jupyter Guide](https://github.com/jupyter-guide/jupyter-guide)

### For Health/Medical Researchers
1. **Search**: [PubMed](https://pubmed.ncbi.nlm.nih.gov/) + [Cochrane Library](https://www.cochranelibrary.com/)
2. **Screen**: [ASReview](https://asreview.nl/) or [Rayyan](https://www.rayyan.ai/)
3. **Quality**: [Cochrane RoB 2 Tool](https://www.riskofbias.info/)
4. **Analyze**: [RevMan](https://revman.cochrane.org/) (free Cochrane tool)

### For Engineering/CS Researchers
1. **Search**: [IEEE Xplore](https://ieeexplore.ieee.org/) + [ACM DL](https://dl.acm.org/) + [Scopus](https://www.scopus.com/)
2. **Visualize**: [VOSviewer](https://www.vosviewer.com/) for citation networks
3. **AI Help**: [Elicit](https://elicit.com/) or [Consensus](https://consensus.app/)
4. **Publish in**: [IEEE COMST](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9739) or [ACM CSUR](https://dl.acm.org/journal/csur)

---

## 📊 Recommended Workflow

**Step-by-step process with tool recommendations:**

| Phase | What to Do | Free Tools | Paid Tools |
|-------|------------|------------|------------|
| **1. Planning** | Define question (PICO), write protocol | [PRISMA-P](https://www.prisma-statement.org/protocols), [PROSPERO](https://www.crd.york.ac.uk/prospero/) | - |
| **2. Search** | Search multiple databases | [PubMed](https://pubmed.ncbi.nlm.nih.gov/), [Google Scholar](https://scholar.google.com/), [Semantic Scholar](https://www.semanticscholar.org/) | [Scopus](https://www.scopus.com/), [Web of Science](https://www.webofscience.com/) |
| **3. Deduplication** | Remove duplicate records | [ASySD](https://camarades.shinyapps.io/ASySD/), [Zotero](https://www.zotero.org/) | [EndNote](https://endnote.com/), [Covidence](https://www.covidence.org/) |
| **4. Screening** | Title/abstract screening | [ASReview](https://asreview.nl/), [Rayyan](https://www.rayyan.ai/) | [Covidence](https://www.covidence.org/), [DistillerSR](https://www.distillersr.com/) |
| **5. Full-text Review** | Read and select studies | [Rayyan](https://www.rayyan.ai/), [Zotero](https://www.zotero.org/) | [Covidence](https://www.covidence.org/) |
| **6. Data Extraction** | Extract study data | [Covidence](https://www.covidence.org/) (trial), Google Sheets | [DistillerSR](https://www.distillersr.com/), [NVivo](https://www.qsrinternational.com/) |
| **7. Quality Assessment** | Assess risk of bias | [JBI Tools](https://jbi.global/critical-appraisal-tools), [RoB 2](https://www.riskofbias.info/) | - |
| **8. Analysis** | Meta-analysis/synthesis | [RevMan](https://revman.cochrane.org/), [R metafor](https://www.metafor-project.org/) | [Comprehensive Meta-Analysis](https://www.meta-analysis.com/) |
| **9. Visualization** | Create figures | [PRISMA2020 R package](https://github.com/prisma-flowdiagram/PRISMA2020), [VOSviewer](https://www.vosviewer.com/) | [Tableau](https://www.tableau.com/) |
| **10. Writing** | Write manuscript | [Overleaf](https://www.overleaf.com/), [Google Docs](https://docs.google.com/) | [Microsoft Word](https://www.microsoft.com/microsoft-365/word) |

**💰 Budget-Friendly Full Workflow:**
- All steps: **Rayyan + Zotero + RevMan + R (metafor) + Overleaf** = $0
- Everything is free and open-source!

**🚀 Premium Workflow:**
- All steps: **Covidence + EndNote + Comprehensive Meta-Analysis + NVivo** ≈ $500-1500/year
- Professional features, support, and integrations

---

## What is Systematic Literature Review?

A **Systematic Literature Review (SLR)** is a rigorous and comprehensive method of reviewing existing research on a specific topic or question. It follows a clearly defined protocol and systematic methodology to identify, select, and critically appraise research.

### Key Characteristics:
- **Focused research question** using frameworks like PICO, PICOT, or SPIDER
- **Systematic and explicit methodology** that can be replicated
- **Comprehensive search** across multiple databases and grey literature
- **Critical appraisal** of study quality and risk of bias
- **Transparent reporting** following standards like PRISMA

### Essential Reading:

- **[Systematic Literature Review: Easy Guide](https://www.languageonthemove.com/systematic-literature-review-easy-guide/)** - Free cheat sheet for beginners
- **[How to Write a Systematic Review](https://pubmed.ncbi.nlm.nih.gov/29283007/)** - PubMed guide
- **[From Literature to Insights: Guidelines for Survey Writing](https://arxiv.org/abs/2509.25828)** - Recent methodological guidelines (2024)
- **[TU Berlin: SLR Method Description](https://www.tu.berlin/en/wm/bibliothek/research-teaching/systematic-literature-reviews/description-of-the-systematic-literature-review-method)**

---

## Key Journals & Publications

### Top Journals for Publishing SLRs:

1. **[IEEE Communications Surveys & Tutorials](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9739)**
   - Impact Factor: High-tier venue for comprehensive surveys
   - Scope: Communications, networking, and computing
   - [Author Guidelines](https://www.comsoc.org/publications/journals/ieee-comst/ieee-communications-surveys-tutorials-submit-manuscript)

2. **[ACM Computing Surveys (CSUR)](https://dl.acm.org/journal/csur)**
   - Impact Factor: 23.8 (2023)
   - Scope: Computer science and computing surveys
   - [Author Guidelines](https://dl.acm.org/journal/csur/author-guidelines)

3. **[Systematic Reviews](https://systematicreviewsjournal.biomedcentral.com/)**
   - Open access journal dedicated to systematic review methodology
   - Publishes protocols and completed reviews

---

## Planning & Protocol

### PRISMA Framework:

- **[PRISMA 2020 Statement](https://www.prisma-statement.org/)** - Official website with latest guidelines
  - 27-item checklist for systematic reviews
  - Flow diagram template
  - [PRISMA 2020 Explanation & Elaboration](https://pmc.ncbi.nlm.nih.gov/articles/PMC8005925/)

### PRISMA Extensions:
- **[PRISMA-P](https://www.prisma-statement.org/protocols)** - For protocols
- **PRISMA-S** - For searching (16-item checklist)
- **PRISMA-ScR** - For scoping reviews

### Protocol Development Tools:

- **[Covidence Protocol Guide](https://www.covidence.org/)** - Template and best practices
- **[PROSPERO](https://www.crd.york.ac.uk/prospero/)** - International registry of systematic review protocols

### Planning Frameworks:
- **PICO** - Population, Intervention, Comparison, Outcome
- **PICOT** - PICO + Time
- **SPIDER** - For qualitative research
- **PCC** - Population, Concept, Context

---

## Search & Discovery

### Academic Search Engines:

**General & Multidisciplinary:**
- **[Google Scholar](https://scholar.google.com/)** - Broad coverage, free access
- **[Semantic Scholar](https://www.semanticscholar.org/)** - AI-powered, 200M+ papers, identifies influential citations
- **[Dimensions](https://www.dimensions.ai/)** - Research analytics with patent/clinical trial links
- **[Lens.org](https://www.lens.org/)** - Free scholarly search with patent integration

**Health & Medicine:**
- **[PubMed](https://pubmed.ncbi.nlm.nih.gov/)** - Primary database for biomedical literature
- **[Cochrane Library](https://www.cochranelibrary.com/)** - Gold standard for health systematic reviews
- **[Embase](https://www.embase.com/)** - Biomedical and pharmacological database

**Engineering & Computer Science:**
- **[IEEE Xplore](https://ieeexplore.ieee.org/)** - Electrical engineering, computer science, electronics
- **[ACM Digital Library](https://dl.acm.org/)** - Computing and information technology
- **[Web of Science](https://www.webofscience.com/)** - Multidisciplinary citation database
- **[Scopus](https://www.scopus.com/)** - Abstract and citation database

**Social Sciences:**
- **[PsycINFO](https://www.apa.org/pubs/databases/psycinfo)** - Psychology and behavioral sciences
- **[ERIC](https://eric.ed.gov/)** - Education research
- **[ScienceDirect](https://www.sciencedirect.com/)** - Multidisciplinary scientific database

### Search Strategy Development Tools:

1. **[SR-Accelerator Polyglot Search Translator](https://sr-accelerator.com/#/polyglot)** ⭐ Essential
   [![GitHub stars](https://img.shields.io/github/stars/IEBH/sra-polyglot?style=social)](https://github.com/IEBH/sra-polyglot)
   - Cross-database search translation
   - Supports: PubMed, Ovid MEDLINE, Cochrane, Embase, Web of Science, Scopus, PsycInfo, ProQuest, SPORTDiscus, CINAHL
   - Web interface + npm package
   - Validation study: 32% time reduction without errors
   - `npm install sra-polyglot`
   - GitHub: https://github.com/IEBH/sra-polyglot

2. **[BOOL](https://scoperac.com/bool/)**
   - AI-powered Boolean search assistance
   - Plugs into Google, Bing, Google Scholar, Scopus
   - CSV import/export
   - Free web-based tool

3. **[PRESS 2015](https://www.cadth.ca/press-2015)** ⭐ Essential Validation
   - Peer Review of Electronic Search Strategies
   - Evidence-based checklists
   - Covers Boolean operators, subject headings, wildcards, field searching
   - Studies show 78-93% of reviews contain search errors
   - Official checklist: https://kib.ki.se/en/search-evaluate/systematic-reviews/press-2015-checklist-search-strategies

### Grey Literature & Special Databases:

**Grey Literature:**
- **[CADTH Grey Matters](https://www.cadth.ca/grey-matters)** - Practical toolkit for health grey literature
- **[OpenGrey](http://www.opengrey.eu/)** - European grey literature
- **[Overton](https://www.overton.io/)** - Policy documents, guidelines, think tank publications

**Trial Registries:**
- **[ClinicalTrials.gov](https://clinicaltrials.gov/)** - US clinical trials
- **[WHO ICTRP](https://trialsearch.who.int/)** - International trials
- **[ANZCTR](https://www.anzctr.org.au/)** - Australia/New Zealand trials
- **[EU Clinical Trials Register](https://www.clinicaltrialsregister.eu/)**
- **[ISRCTN Registry](https://www.isrctn.com/)**

**Preprint Servers:**
- **[medRxiv](https://www.medrxiv.org/)** - Medicine preprints
- **[bioRxiv](https://www.biorxiv.org/)** - Biology preprints
- **[arXiv](https://arxiv.org/)** - Multiple disciplines
- **[PsyArXiv](https://psyarxiv.com/)** - Psychology preprints

### Citation Discovery:

- **[Connected Papers](https://www.connectedpapers.com/)** - Visual citation network exploration
- **[ResearchRabbit](https://www.researchrabbit.ai/)** - "Spotify for research" - personalized recommendations
- **[CitNetExplorer](https://www.citnetexplorer.nl/)** - Citation network analysis
- **[Citation Gecko](https://citationgecko.com/)** ⭐ Free
  [![GitHub stars](https://img.shields.io/github/stars/CitationGecko/gecko-react?style=social)](https://github.com/CitationGecko/gecko-react)
  - Forward and backward citation chasing
  - BibTeX import, Zotero integration
  - Network visualization with timeline view
  - Iterative paper expansion
  - Uses OpenCitations, Crossref, Microsoft Academic
  - DOI: 10.5281/zenodo.7068284

- **[Local Citation Network](https://localcitationnetwork.github.io/)** ⭐ Free
  [![GitHub stars](https://img.shields.io/github/stars/LocalCitationNetwork/LocalCitationNetwork.github.io?style=social)](https://github.com/LocalCitationNetwork/LocalCitationNetwork.github.io)
  - Visualizes local citation networks from seed articles
  - "Top Cited" and "Top Citing" recommendations
  - Uses OpenAlex, Semantic Scholar, Crossref, OpenCitations
  - GPL-3 license, web-based

- **[Citation Graph Builder](https://github.com/FZJ-IEK3-VSA/citation-graph-builder)**
  [![GitHub stars](https://img.shields.io/github/stars/FZJ-IEK3-VSA/citation-graph-builder?style=social)](https://github.com/FZJ-IEK3-VSA/citation-graph-builder)
  - PDF parsing (GROBID) with bibliographic APIs
  - SVG export for publication-ready figures
  - MIT license
  - Install via conda

- **[Citograph](https://github.com/arsengit/citograph)**
  [![GitHub stars](https://img.shields.io/github/stars/arsengit/citograph?style=social)](https://github.com/arsengit/citograph)
  - Citation graphs from Semantic Scholar
  - JSON output for Excalidraw
  - Apache 2.0 license

### API Resources:

- **[OpenCitations](https://opencitations.net/)** - 2+ billion citation links (July 2024)
  [![GitHub stars](https://img.shields.io/github/stars/opencitations?style=social)](https://github.com/opencitations)
  - SPARQL endpoint, REST APIs, dataset dumps
  - CSV, N-Triples, Scholix formats
  - CC0 licensed data, ISC licensed software
  - Sources: Crossref, NIH-OCC, DataCite, OpenAIRE, JaLC

- **[OpenAlex API Tutorials](https://github.com/ourresearch/openalex-api-tutorials)**
  [![GitHub stars](https://img.shields.io/github/stars/ourresearch/openalex-api-tutorials?style=social)](https://github.com/ourresearch/openalex-api-tutorials)
  - Jupyter notebooks with bibliometric analysis
  - Python code snippets
  - No authentication required
  - 100k requests/day limit

### Systematic Review Toolbox:
- **[SR Toolbox](http://systematicreviewtools.com/)** - Directory of 235+ tools for literature reviews

---

## Study Management

> **🎯 Quick Pick:** Free users → [Rayyan](https://www.rayyan.ai/) | Budget available → [Covidence](https://www.covidence.org/)

### Comprehensive Platforms:

1. **[Covidence](https://www.covidence.org/)** ⭐ Recommended
   - Cochrane's official production platform
   - Full workflow support: screening, extraction, quality assessment
   - Subscription required (free trial available)

2. **[Rayyan](https://www.rayyan.ai/)** ⭐ Free
   - Free with unlimited collaborators
   - Excellent for screening and abstract management
   - AI-assisted screening

3. **[DistillerSR](https://www.distillersr.com/)**
   - Professional-grade systematic review software
   - Strong data extraction features
   - Commercial license required

4. **[EPPI-Reviewer](https://eppi.ioe.ac.uk/cms/Default.aspx?alias=eppi.ioe.ac.uk/cms/er4)**
   - All types of literature reviews
   - Meta-analysis capabilities
   - Academic and commercial licenses

5. **[Nested Knowledge](https://nested-knowledge.com/)**
   - Modern interface with AI features
   - Visual data extraction
   - Growing platform (87% feature coverage)

---

## Screening & Selection

> **🎯 Quick Comparison:**
>
> | Tool | Cost | Best Feature | Workload Reduction |
> |------|------|--------------|-------------------|
> | [ASReview](https://asreview.nl/) | Free | AI active learning | Up to 95% |
> | [Rayyan](https://www.rayyan.ai/) | Free | Collaborative screening | Good |
> | [Abstrackr](http://abstrackr.cebm.brown.edu/) | Free | Semi-automated | ~67% |
> | [Covidence](https://www.covidence.org/) | Paid | Full workflow | Good |

### AI-Powered Screening Tools:

1. **[ASReview](https://asreview.nl/)** ⭐ Free & Open Source
   - Active learning for efficient screening
   - Can reduce workload by up to 95%
   - Open source, published in Nature Machine Intelligence

2. **[Abstrackr](http://abstrackr.cebm.brown.edu/)** - Free
   - Semi-automated screening
   - Median workload savings: 67.2%
   - Web-based, no installation required

3. **[SWIFT Active Screener](https://www.sciome.com/swift-activescreener/)**
   - Machine learning-assisted screening
   - Supports all mandatory features

### Web-Based Screening Platforms:

4. **[Colandr](https://www.colandrcommunity.com/)** - Open Source
   - Machine learning-assisted screening
   - Full evidence synthesis workflows
   - PICO framework support
   - Customizable data extraction forms
   - MIT-licensed
   - Uses word2vec for ML
   - Free access

5. **[SRDR+](https://srdr.ahrq.gov/)** ⚠️ Retiring Nov 28, 2025
   - Machine learning-informed screening
   - FHIR-compliant data extraction
   - Free web-based platform
   - Customizable extraction forms
   - **Important**: Migrating to alternatives recommended
   - Website: https://srdr.ahrq.gov/

6. **[SRA2 (Systematic Review Accelerator)](https://github.com/CREBP/SRA2)**
   [![GitHub stars](https://img.shields.io/github/stars/CREBP/SRA2?style=social)](https://github.com/CREBP/SRA2)
   - Search optimization
   - Reference deduplication
   - Multi-researcher consolidation
   - Open-source PHP/MySQL tool
   - Successor to original SRA

7. **[SyRF (Systematic Review Facility)](https://syrf.org.uk/)**
   - Preclinical systematic reviews focus
   - Collaborative screening
   - Machine learning assistance
   - Risk of bias auto-detection
   - Living systematic reviews support
   - Free access
   - User guide: https://camaradesuk.github.io/syrf_userguide/

8. **[CADIMA](https://www.cadima.info/)**
   - Free open-access platform
   - Developed for agriculture and environmental sciences
   - Supports entire systematic review process
   - Protocol development
   - Statistical analysis integration with R
   - Export files for offline work

9. **[SysRev.com](https://sysrev.com/)**
   - Free collaborative data extraction
   - Boolean, categorical, and string labels
   - Multiple reviewers support
   - Abstract and full-text screening

### Manual Screening Support:

- **[Covidence](https://www.covidence.org/)** - Structured screening workflow
- **[Rayyan](https://www.rayyan.ai/)** - Collaborative blind screening
- **[RevMan](https://revman.cochrane.org/)** - Cochrane's review manager

---

## Data Extraction

### Structured Extraction:

- **[Covidence](https://www.covidence.org/)** - Customizable extraction forms
- **[DistillerSR](https://www.distillersr.com/)** - Advanced extraction features
- **[EPPI-Reviewer](https://eppi.ioe.ac.uk/cms/er4)** - Flexible coding framework

### Qualitative Data Analysis:

1. **[NVivo](https://www.qsrinternational.com/nvivo-qualitative-data-analysis-software/home)** ⭐
   - Industry standard for qualitative analysis
   - Supports text, audio, video, social media
   - AI-powered autocoding
   - Great for systematic reviews with qualitative data

2. **[MAXQDA](https://www.maxqda.com/)**
   - Mixed methods data analysis
   - AI-powered features
   - Automatic transcription

3. **[Atlas.ti](https://atlasti.com/)**
   - Qualitative and mixed methods analysis
   - Visual analysis tools

4. **[Dedoose](https://www.dedoose.com/)**
   - Web-based collaborative analysis
   - Mixed methods support

### Data Exchange:
- **REFI-QDA** - Standard format for exchanging data between NVivo, MAXQDA, and Atlas.ti

### AI-Powered Data Extraction:

**Automated Extraction from Clinical Trials:**

1. **[Trialstreamer](https://trialstreamer.robotreviewer.net/)** ⭐ Living Database
   - Living database of 700,000+ RCTs
   - Automatic RCT identification from PubMed
   - PICO extraction and MeSH mapping
   - Sample size extraction
   - Risk of bias prediction
   - Daily updates with free database download
   - Searches WHO ICTRP and PubMed
   - Structured query interface
   - Marshall et al. (2020) JAMIA

**PICO Extraction Systems:**

2. **BioBERT/BioELECTRA-PICO** (Hugging Face models)
   - Named Entity Recognition for PICO elements
   - BioELECTRA-PICO (110M parameters)
   - BioMobileBERT (compact, faster)
   - F1 scores 70-90% depending on element
   - Domain-adapted for biomedical text

3. **[EBM-NLP Dataset](https://github.com/bepnye/EBM-NLP)**
   - 5,000 annotated RCT abstracts
   - Gold standard for PICO extraction research
   - Publicly available corpus

4. **Section-Specific Learning Approach** (Hu et al., 2023 Bioinformatics)
   - >90% extraction accuracy from Methods sections
   - Two-step pipeline: sentence classification + NER
   - Focus on structured sections

5. **AlpaPICO**
   - LLM-based PICO extraction from clinical trials
   - Research code available

6. **OpenAI Batch API** - Large Scale
   - Parallel PICO extraction from 680,000+ abstracts
   - PostgreSQL database storage
   - <3 hours processing for 700,000 abstracts
   - For EU HTAR compliance

**LLM-Based Extraction:**

7. **ChatGPT/GPT-4** - API-based
   - ~80% accuracy for PICO elements in feasibility studies
   - Prompt engineering with JSON schemas
   - `pip install openai`
   - Commercial API costs ~$1.50/1000 pages
   - Limitations: hallucinations requiring validation

8. **Claude (Anthropic)**
   - 65-82% agreement across runs for binary outcomes
   - Kappa: 0.65-0.82 for consistency

9. **[ChatPDF](https://www.chatpdf.com/)**
   - LLM-powered PDF analysis
   - 70%+ correct responses for binary outcomes
   - Kappa: 0.78-0.96 for agreement

10. **[Mistral OCR](https://mistral.ai/news/mistral-ocr)**
    - Advanced document understanding via mistral-ocr-latest API
    - Handles complex elements (math, tables, images)
    - Thousands of scripts supported
    - 2000 pages/minute processing
    - $1/1000 pages pricing
    - Self-hosting option
    - Markdown output including images

**Specialized Tools:**

11. **[MedTrialExtractor](https://github.com/TakedaGME/MedTrialExtractor)**
    - Entity and relationship extraction
    - BiLSTM and BERT-based models
    - Designed for systematic reviews

12. **Supervised Distant Supervision (SDS)** (Wallace et al., 2016 PubMed)
    - Extracts PICO sentences from full-text
    - Uses Cochrane Database of Systematic Reviews (CDSR)

**Data Extraction Templates:**

13. **[Cochrane Data Extraction Templates](https://training.cochrane.org/handbook)**
    - Comprehensive forms for RCTs and non-RCTs
    - Haematological Malignancies Group template: https://training.cochrane.org/sites/training.cochrane.org/files/public/uploads/resources/downloadable_resources/English/Collecting%20data%20-%20form%20for%20RCTs%20only.doc

14. **PIECES Excel Workbook** (Texas A&M Libraries)
    - Developer: Margaret J. Foster
    - Advanced Excel with drop-down menus
    - Range checks, data validation
    - Prevents entry errors
    - Customizable workbooks

15. **[REDCap](https://www.project-redcap.org/)**
    - HIPAA-compliant survey and database creation
    - Custom forms builder
    - Data validation
    - Export to Excel/CSV/SPSS
    - Requires institutional license

16. **Epi Info + R Pipeline**
    - 10-step guideline: https://github.com/Afifistat/Data-extraction-guideline.git
    - Database design for data extraction
    - R scripts for data comparison
    - Open-source alternative for complex reviews
    - Systematic Reviews (2023) publication

---

## Quality Assessment

### Risk of Bias Tools:

1. **[Cochrane Risk of Bias Tool (RoB 2)](https://www.riskofbias.info/)**
   - Gold standard for RCTs
   - Domain-based approach
   - RoB 2.0 current version

2. **[JBI Critical Appraisal Tools](https://jbi.global/critical-appraisal-tools)** ⭐ Free
   - Updated 2023-2024
   - Multiple study designs
   - Adaptable framework
   - Free checklists

3. **[ROBINS-I](https://www.riskofbias.info/welcome/robins-i-tool)** - v2 Released Nov 2024
   - Risk of bias in non-randomized intervention studies
   - 7 bias domains with detailed guidance
   - Version 2: https://www.riskofbias.info/welcome/robins-i-v2
   - Improved algorithms and usability

### Study Design-Specific Tools:

4. **[Newcastle-Ottawa Scale (NOS)](https://www.ohri.ca/programs/clinical_epidemiology/oxford.asp)**
   - Star-based quality rating (0-9 stars)
   - For cohort and case-control studies
   - Assesses selection, comparability, outcome
   - Downloadable PDF: https://www.ohri.ca/programs/clinical_epidemiology/nosgen.pdf

5. **[QUADAS-2](https://www.bristol.ac.uk/population-health-sciences/projects/quadas/quadas-2/)** ⭐
   - Diagnostic accuracy studies
   - 4 domains: patient selection, index test, reference standard, flow/timing
   - Risk of bias and applicability concerns
   - Implementation manual available
   - NICE guidance: https://www.nice.org.uk/process/pmg6/resources/the-guidelines-manual-appendices-bi-2549703709/chapter/appendix-f-methodology-checklist-the-quadas-2-tool-for-studies-of-diagnostic-test-accuracy
   - QUADAS-AI version for AI diagnostic studies expected 2025

6. **[QUIPS](https://methods.cochrane.org/prognosis/tools)**
   - Assesses prognostic factor studies
   - 6 domains with three-grade risk of bias scale
   - Median 20 minutes per study
   - Inter-rater kappa 0.56-0.82
   - Recommended by Cochrane Prognosis Methods Group
   - Visualization supported by robvis

7. **[PROBAST](https://www.probast.org/)**
   - Evaluates prediction model studies
   - 4 domains: participants, predictors, outcome, analysis
   - 20 signaling questions
   - PDF: https://www.probast.org/wp-content/uploads/2020/02/PROBAST_20190515.pdf
   - Excel templates for systematic reviews

### Qualitative & Mixed Methods Tools:

8. **[MMAT (Mixed Methods Appraisal Tool)](https://www.mcgill.ca/familymed/research/resources/funding/mmat)** ⭐
   - Version 2018 current
   - Covers qualitative studies, RCTs, non-randomized quantitative, descriptive, mixed methods
   - 5 core criteria per category
   - Download: http://mixedmethodsappraisaltoolpublic.pbworks.com/
   - Developed through modified e-Delphi with 73 experts

9. **[COREQ](https://www.equator-network.org/reporting-guidelines/coreq/)**
   - 32-item checklist for interviews and focus groups
   - Covers research team reflexivity, study design, data analysis
   - Most frequently cited qualitative research reporting guideline

10. **[ENTREQ](https://pubmed.ncbi.nlm.nih.gov/22894893/)**
    - 21-item checklist for systematic reviews of qualitative research
    - 5 domains
    - Higher uptake in reviews (28%) than COREQ (17%)

### Systematic Review Quality Assessment:

11. **[AMSTAR 2](https://amstar.ca/)** ⭐ Essential
    - 16-item critical appraisal tool for systematic reviews
    - 7 critical domains
    - Overall ratings: high, moderate, low, critically low confidence
    - Published in BMJ 2017: https://pmc.ncbi.nlm.nih.gov/articles/PMC5833365/
    - Training videos and resources available
    - Used in ~80% of umbrella reviews

12. **[ROBIS (Risk Of Bias In Systematic reviews)](https://www.bristol.ac.uk/population-health-sciences/projects/robis/)**
    - Three-phase instrument focusing on bias
    - Complementary to AMSTAR 2
    - More sophisticated bias assessment

### Visualization & Evidence Grading:

13. **[robvis](https://github.com/mcguinlu/robvis)** ⭐ Essential (See R packages section)
    - Publication-quality risk of bias figures
    - Supports: RoB 2, ROBINS-I, ROBINS-E, QUADAS-2, QUIPS
    - Colorblind-friendly schemes
    - Over 1,500 academic citations
    - Web app: https://mcguinlu.shinyapps.io/robvis (no R required)

14. **[GRADEpro GDT](https://www.gradepro.org/)**
    - Creates Summary of Findings tables
    - Evidence Profiles with evidence-to-decision frameworks
    - Free web-based software: https://gdt.gradepro.org/app/
    - Over 100,000 users worldwide
    - Mobile/desktop compatibility

### Additional Quality Assessment Frameworks:

- **[CASP Checklists](https://casp-uk.net/casp-tools-checklists/)** ⭐ Free Downloads
  - 8 different checklists: systematic reviews, RCTs, qualitative, cohort, case control, diagnostic, economic evaluations, clinical prediction rules, cross-sectional
  - All free downloads under Creative Commons license

- **[NIH Quality Assessment Tools](https://www.nhlbi.nih.gov/health-topics/study-quality-assessment-tools)**
  - Multiple study designs
  - Developed by NHLBI

---

## Analysis & Synthesis

> **🎯 Quick Pick:** Free → [RevMan](https://revman.cochrane.org/) or [R metafor](https://www.metafor-project.org/) | Easy to use → [CMA](https://www.meta-analysis.com/) ($295/year)

### Meta-Analysis Software:

1. **[RevMan (Review Manager)](https://revman.cochrane.org/)** ⭐ Free
   - Cochrane's official software
   - Forest plots and meta-analysis
   - Free download

2. **[R with metafor package](https://www.metafor-project.org/)** ⭐ Free & Flexible
   - Most powerful and flexible
   - Free and open source
   - Steep learning curve
   - [Tutorial](https://www.metafor-project.org/doku.php/tips)

3. **[Comprehensive Meta-Analysis (CMA)](https://www.meta-analysis.com/)**
   - User-friendly interface
   - Highest usability scores
   - Academic: $295/year

4. **[OpenMeta[Analyst]](http://www.cebm.brown.edu/openmeta/)** - Free
   - Open source
   - Binary, continuous, diagnostic data
   - Developed at Brown University

### Additional Analysis Tools:

- **[Meta-Essentials](https://www.erim.eur.nl/research-support/meta-essentials/)** - Free Excel-based tool
- **[Stata](https://www.stata.com/)** - Statistical software with meta-analysis commands
- **[JASP](https://jasp-stats.org/)** - Free, user-friendly statistical software

---

## Visualization

### Bibliometric & Network Visualization:

1. **[VOSviewer](https://www.vosviewer.com/)** ⭐ Free
   - Citation network visualization
   - Co-authorship analysis
   - Keyword mapping
   - Easy to use, widely adopted

2. **[CiteSpace](http://cluster.cis.drexel.edu/~cchen/citespace/)** - Free
   - Temporal visualization of research trends
   - Burst detection for emerging topics
   - Java-based

3. **[Bibliometrix / Biblioshiny](https://www.bibliometrix.org/)** - Free
   - R package for bibliometric analysis
   - Web interface (Biblioshiny) available
   - Comprehensive metrics

### Data Visualization:

- **[R with ggplot2](https://ggplot2.tidyverse.org/)** - Publication-quality graphics
- **[Python matplotlib/seaborn](https://matplotlib.org/)** - Python visualization
- **[Tableau](https://www.tableau.com/)** - Interactive dashboards
- **[RAWGraphs](https://www.rawgraphs.io/)** - Free web-based visualization

### PRISMA Flow Diagrams:

- **[PRISMA Flow Diagram Generator](http://prisma.thetacollaborative.ca/)** - Free online tool
- **[SysRev PRISMA](https://sysrev.com/p/3144)** - Automated generation

---

## Writing & Reporting

### Collaborative Writing:

1. **[Overleaf](https://www.overleaf.com/)** ⭐ For LaTeX
   - Real-time collaborative LaTeX editor
   - [SLR Templates](https://www.overleaf.com/latex/templates/literature-systematic-review-lsr-template/wygxtxrgwjsj)
   - Free tier available
   - University licenses common

2. **[Google Docs](https://docs.google.com/)**
   - Real-time collaboration
   - Free, accessible
   - Good for drafting

3. **[Microsoft Word](https://www.microsoft.com/microsoft-365/word)** + OneDrive
   - Track changes
   - Comments and reviews
   - Familiar interface

### Academic Writing Tools:

- **[Grammarly](https://www.grammarly.com/)** - Grammar and style checking
- **[QuillBot](https://quillbot.com/)** - Paraphrasing and writing assistance
- **[Hemingway Editor](https://hemingwayapp.com/)** - Readability improvement

### Journal Templates:

- **[Overleaf Templates](https://www.overleaf.com/latex/templates/tagged/academic-journal)** - 1000+ journal templates
- Publisher templates (Elsevier, Springer, IEEE, ACM)

---

## Reference Management

> **🎯 Quick Pick:** Most users → [Zotero](https://www.zotero.org/) (free) | Large SLRs (5000+ refs) → [EndNote](https://endnote.com/)

### Top Reference Managers:

1. **[Zotero](https://www.zotero.org/)** ⭐ Free & Open Source
   - Best browser integration
   - Most accurate bibliographies
   - Free unlimited storage
   - Open source
   - **Best for**: Diverse content types

2. **[EndNote](https://endnote.com/)**
   - Best for large systematic reviews (5,000-10,000+ refs)
   - Superior deduplication
   - Most database search options
   - **Best for**: Large-scale SLRs
   - Commercial license required

3. **[Mendeley](https://www.mendeley.com/)** - Free
   - Strong community features
   - PDF annotation
   - Free cloud storage
   - Owned by Elsevier

### Deduplication Tools:

> **🎯 Performance Comparison:** Rayyan (highest sensitivity/specificity) → ASySD → Deduklick → EndNote/Mendeley

1. **[Rayyan](https://www.rayyan.ai/)** ⭐ Best Performance
   - Highest sensitivity (0.98) and specificity (0.96+)
   - Automatic deduplication with screening
   - Tagging and highlighting features
   - Free for up to 3 active reviews

2. **[ASySD (Automated Systematic Search Deduplicator)](https://camarades.shinyapps.io/ASySD/)** - Free
   - Rapid, open-source, interoperable
   - For biomedical systematic reviews
   - R package + Shiny app
   - Higher sensitivity than EndNote
   - GitHub: https://github.com/camaradesuk/ASySD
   - Published in BMC Biology (Hair et al. 2023)

3. **[Deduklick](https://pubmed.ncbi.nlm.nih.gov/35854436/)** - Novel Algorithm
   - Explainable automated deduplication
   - 99.51% mean recall
   - 100% precision
   - Published in Systematic Reviews (Borissov et al. 2022)

4. **[Systematic Review Accelerator Deduplicator](https://sr-accelerator.com/)**
   - Sorts by likelihood of duplication
   - XML file input (EndNote)
   - Higher sensitivity than EndNote
   - **Note**: Moving to TERA platform, paid after October 31, 2025

5. **[Mendeley](https://www.mendeley.com/)** - Free
   - Good balance: 0.93 sensitivity and 0.93 PPV
   - Freely available
   - Built-in deduplication

6. **EndNote, Zotero** - Built-in
   - EndNote: Best for large reviews (5,000-10,000+ refs)
   - Zotero: Free and open source

---

## Collaboration Tools

### Project Management:

1. **[Notion](https://www.notion.so/)**
   - All-in-one workspace
   - Documentation and knowledge base
   - Free for individuals

2. **[Miro](https://miro.com/)**
   - Visual collaboration whiteboard
   - Brainstorming and mapping
   - Integrates with Notion, GitHub, Slack

3. **[Trello](https://trello.com/)**
   - Simple project boards
   - Task tracking
   - Free tier available

### Research-Specific:

- **[OSF (Open Science Framework)](https://osf.io/)** - Research project management, free
- **[GitHub](https://github.com/)** - Version control for code and documents
- **[Slack](https://slack.com/)** / **[Discord](https://discord.com/)** - Team communication

---

## AI-Powered Tools

> **🎯 Quick Pick:** Start with [Elicit](https://elicit.com/) + [ResearchRabbit](https://www.researchrabbit.ai/) (both have free tiers)

### AI Research Assistants:

1. **[Elicit](https://elicit.com/)** ⭐ Highly Recommended
   - Systematic literature search and screening
   - 125M+ papers (Semantic Scholar)
   - AI-powered extraction to tables
   - Real-time collaboration
   - Free tier + paid plans

2. **[Consensus](https://consensus.app/)** ⭐
   - AI-powered literature consensus
   - Extracts key points from papers
   - Shows agreement/disagreement in literature
   - Free + Pro plans

3. **[Scite](https://scite.ai/)** ⭐
   - 1.2B citation statements analyzed
   - Shows if claims are supported/contradicted
   - Smart citations
   - Free tier + subscriptions

4. **[ResearchRabbit](https://www.researchrabbit.ai/)** - Free
   - "Spotify for research"
   - Personalized paper recommendations
   - Collection-based learning
   - Completely free

### Additional AI Tools:

- **[ChatPDF](https://www.chatpdf.com/)** - Chat with PDF papers
- **[Explainpaper](https://www.explainpaper.com/)** - Explain complex papers
- **[SciSpace](https://typeset.io/)** - AI copilot for research papers
- **[Lateral](https://www.lateral.io/)** - AI-powered research organization

### Important Notes:
- Don't use general ChatGPT for sensitive research data
- Combine tools for best results (e.g., Elicit + Scite + ResearchRabbit)
- Always verify AI-generated content

---

## Open Source Tools & GitHub Repositories

> **🎯 Quick Picks:**
> **Python:** `pip install asreview litstudy` → Screening + Analysis
> **R:** `install.packages(c("metafor", "bibliometrix"))` → Meta-analysis + Bibliometrics
> **PDF Extraction:** [GROBID](https://github.com/kermitt2/grobid) (3500+ stars)

This section highlights open-source tools and code repositories that you can use, modify, and contribute to. Perfect for developers and researchers who want programmatic access or customizable solutions.

### Python Libraries & Tools

#### Screening & Machine Learning

1. **[ASReview](https://github.com/asreview/asreview)** ⭐ Highly Recommended
   [![GitHub stars](https://img.shields.io/github/stars/asreview/asreview?style=social)](https://github.com/asreview/asreview)
   - Active learning for systematic reviews
   - Published in Nature Machine Intelligence
   - Reduces workload by up to 95%
   - Privacy-first, no data collection
   - `pip install asreview`
   - Language: Python

2. **[LatteReview](https://github.com/PouriaRouzrokh/LatteReview)**
   [![GitHub stars](https://img.shields.io/github/stars/PouriaRouzrokh/LatteReview?style=social)](https://github.com/PouriaRouzrokh/LatteReview)
   - Low-code AI-powered automation
   - Multi-agent review systems
   - Customizable agent roles
   - Supports multiple review rounds
   - Language: Python

3. **[systematic-reviewpy](https://github.com/chandraveshchaudhari/systematic-reviewpy)**
   [![GitHub stars](https://img.shields.io/github/stars/chandraveshchaudhari/systematic-reviewpy?style=social)](https://github.com/chandraveshchaudhari/systematic-reviewpy)
   - Automates PRISMA workflows with NLP
   - Generates analysis tables and workflow diagrams
   - Creates ASReview files
   - Provides stemming, lemmatization, paper sorting
   - `pip install systematic-reviewpy`
   - Language: Python

4. **[ProfOlaf](https://github.com/sr-lab/ProfOlaf)**
   [![GitHub stars](https://img.shields.io/github/stars/sr-lab/ProfOlaf?style=social)](https://github.com/sr-lab/ProfOlaf)
   - Iterative snowballing with LLM-assisted extraction
   - Human-in-the-loop filtering
   - Topic extraction and query answering
   - Citation network analysis for systematic reviews
   - Released 2024
   - Language: Python

5. **[LLAssist](https://github.com/cyharyanto/llassist)**
   [![GitHub stars](https://img.shields.io/github/stars/cyharyanto/llassist?style=social)](https://github.com/cyharyanto/llassist)
   - LLM-based literature screening
   - Automated relevance assessment
   - Key information extraction
   - Matches papers against research questions
   - Released 2024
   - Language: Python

6. **[RobotReviewer](https://github.com/ijmarshall/robotreviewer)**
   [![GitHub stars](https://img.shields.io/github/stars/ijmarshall/robotreviewer?style=social)](https://github.com/ijmarshall/robotreviewer)
   - Automatically extracts risk of bias from clinical trials
   - Identifies PICO elements
   - Machine learning for RCT identification
   - Web-based interface at https://www.robotreviewer.net/
   - `pip install robotreviewer`
   - Language: Python

#### Literature Analysis & Bibliometrics

7. **[LitStudy](https://github.com/NLeSC/litstudy)**
   [![GitHub stars](https://img.shields.io/github/stars/NLeSC/litstudy?style=social)](https://github.com/NLeSC/litstudy)
   - Automate literature analysis from Jupyter notebooks
   - Scientometrics and bibliometrics
   - Network analysis and visualization
   - Natural language processing
   - `pip install litstudy`
   - Language: Python

8. **[pyBibX](https://github.com/Valdecy/pybibx)**
   [![GitHub stars](https://img.shields.io/github/stars/Valdecy/pybibx?style=social)](https://github.com/Valdecy/pybibx)
   - Bibliometric and scientometric analysis
   - AI-powered features
   - Generates EDA reports
   - Creates document/author/institution IDs
   - `pip install pybibx`
   - Language: Python

9. **[metaknowledge](https://github.com/UWNETLAB/metaknowledge)**
   [![GitHub stars](https://img.shields.io/github/stars/UWNETLAB/metaknowledge?style=social)](https://github.com/UWNETLAB/metaknowledge)
   - Bibliometric research simplification
   - Reads meta-data from various sources
   - Network analysis capabilities
   - `pip install metaknowledge`
   - Language: Python

#### Meta-Analysis

10. **[PythonMeta](https://github.com/Lightbridge-KS/PythonMeta)**
    [![GitHub stars](https://img.shields.io/github/stars/Lightbridge-KS/PythonMeta?style=social)](https://github.com/Lightbridge-KS/PythonMeta)
    - Comprehensive meta-analysis with effect sizes
    - Supports OR, RR, RD for dichotomous data
    - MD, SMD for continuous data
    - Fixed/random effects models with MH/Peto/IV algorithms
    - Forest and funnel plots
    - `pip install PythonMeta`
    - Web interface: https://www.pymeta.com/
    - Language: Python

11. **[PyMARE](https://github.com/neurostuff/PyMARE)**
    [![GitHub stars](https://img.shields.io/github/stars/neurostuff/PyMARE?style=social)](https://github.com/neurostuff/PyMARE)
    - Mixed-effects meta-regression
    - Multiple variance estimation methods (ReML, ML, DL)
    - `pip install pymare`
    - Documentation: https://pymare.readthedocs.io/
    - Language: Python

12. **[NiMARE](https://github.com/neurostuff/NiMARE)**
    [![GitHub stars](https://img.shields.io/github/stars/neurostuff/NiMARE?style=social)](https://github.com/neurostuff/NiMARE)
    - Neuroimaging meta-analysis
    - Coordinate- and image-based methods
    - General meta-analysis tools included
    - `pip install nimare`
    - Language: Python

#### Citation Snowballing

13. **[snowballing](https://github.com/JoaoFelipe/snowballing)** ⭐
   [![GitHub stars](https://img.shields.io/github/stars/JoaoFelipe/snowballing?style=social)](https://github.com/JoaoFelipe/snowballing)
   - Literature snowballing tools
   - Chrome plugin for Google Scholar
   - Jupyter Notebook widgets
   - Citation graph visualization
   - Forward/backward snowballing
   - Documentation: https://joaofelipe.github.io/snowballing
   - Language: Python

#### Citation Network & API Access

14. **[semanticscholar](https://github.com/danielnsilva/semanticscholar)**
    [![GitHub stars](https://img.shields.io/github/stars/danielnsilva/semanticscholar?style=social)](https://github.com/danielnsilva/semanticscholar)
    - Unofficial Python client for Semantic Scholar API
    - Typed responses, paginated navigation
    - Async support
    - `pip install semanticscholar`
    - Language: Python

15. **[PyS2](https://github.com/mirandrom/PyS2)**
    [![GitHub stars](https://img.shields.io/github/stars/mirandrom/PyS2?style=social)](https://github.com/mirandrom/PyS2)
    - Typed pydantic objects for Semantic Scholar
    - Retries and rate limiting
    - `pip install pys2`
    - Language: Python

16. **[PyAlex](https://github.com/J535D165/pyalex)**
    [![GitHub stars](https://img.shields.io/github/stars/J535D165/pyalex?style=social)](https://github.com/J535D165/pyalex)
    - Comprehensive OpenAlex support (Works, Authors, Sources, etc.)
    - Polite pool access, retry mechanism
    - Abstract parsing, CC0 data license
    - Covers 200M+ works, free access
    - `pip install pyalex`
    - Language: Python

#### PDF Data Extraction

17. **[GROBID](https://github.com/kermitt2/grobid)** ⭐ Industry Standard
   [![GitHub stars](https://img.shields.io/github/stars/kermitt2/grobid?style=social)](https://github.com/kermitt2/grobid)
   - Machine learning for PDF extraction
   - Focus on scientific publications
   - Structured XML/TEI output
   - Extracts metadata + full text
   - 68 fine-grained structure labels
   - Language: Java/Python

18. **[PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit)**
   [![GitHub stars](https://img.shields.io/github/stars/opendatalab/PDF-Extract-Kit?style=social)](https://github.com/opendatalab/PDF-Extract-Kit)
   - High-quality content extraction
   - Layout detection, formula recognition
   - OCR for complex PDFs
   - Works on papers, textbooks, reports
   - Language: Python

19. **[MinerU](https://github.com/opendatalab/MinerU)**
    [![GitHub stars](https://img.shields.io/github/stars/opendatalab/MinerU?style=social)](https://github.com/opendatalab/MinerU)
    - Transforms PDFs to markdown/JSON
    - LLM-ready format
    - Machine-readable outputs
    - Language: Python

20. **[PDFDataExtractor](https://github.com/cat-lemonade/PDFDataExtractor)**
    [![GitHub stars](https://img.shields.io/github/stars/cat-lemonade/PDFDataExtractor?style=social)](https://github.com/cat-lemonade/PDFDataExtractor)
    - Semantic information extraction
    - Focused on scientific articles
    - Language: Python

21. **[Marker](https://github.com/VikParuchuri/marker)**
    [![GitHub stars](https://img.shields.io/github/stars/VikParuchuri/marker?style=social)](https://github.com/VikParuchuri/marker)
    - Converts PDF to Markdown using Surya OCR
    - Formula extraction (LaTeX)
    - Text detection and layout analysis
    - 90+ language support
    - Language: Python

22. **[Unstructured](https://github.com/Unstructured-IO/unstructured)**
    [![GitHub stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=social)](https://github.com/Unstructured-IO/unstructured)
    - ETL for ML tasks from PDFs
    - Document parsing library
    - Multiple format support
    - `pip install unstructured`
    - Language: Python

23. **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)**
    [![GitHub stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract?style=social)](https://github.com/tesseract-ocr/tesseract)
    - Open-source OCR from Google
    - Supports 100+ languages
    - `pip install pytesseract`
    - Language: C++/Python

24. **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)**
    [![GitHub stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR?style=social)](https://github.com/PaddlePaddle/PaddleOCR)
    - Handles 80+ languages
    - Table recognition
    - Excellent for Asian languages
    - `pip install paddleocr`
    - Language: Python

#### Text Mining & NLP

25. **[medaCy](https://github.com/NLPatVCU/medaCy)**
    [![GitHub stars](https://img.shields.io/github/stars/NLPatVCU/medaCy?style=social)](https://github.com/NLPatVCU/medaCy)
    - Medical text mining framework
    - Built on spaCy
    - Fast model prototyping
    - Highly predictive medical NLP
    - Language: Python

### R Packages

#### Search Strategy Development

1. **[litsearchr](https://github.com/elizagrames/litsearchr)** ⭐ Highly Recommended
   [![GitHub stars](https://img.shields.io/github/stars/elizagrames/litsearchr?style=social)](https://github.com/elizagrames/litsearchr)
   - Revolutionizes search strategy development
   - Quasi-automatic keyword extraction using text mining
   - Co-occurrence networks for term relationships
   - Interactive Shiny GUI available
   - `install.packages("litsearchr")`
   - Shiny app: https://elizagrames.shinyapps.io/litsearchr/
   - Language: R

2. **[searchAnalyzeR](https://cran.r-project.org/package=searchAnalyzeR)**
   - Validates search strategies
   - PRISMA-compliant reporting
   - Precision-recall analysis
   - Cross-database performance comparison
   - PubMed API integration
   - `install.packages("searchAnalyzeR")`
   - Language: R

#### Screening & Workflow Management

3. **[metagear](https://github.com/cran/metagear)**
   [![GitHub stars](https://img.shields.io/github/stars/cran/metagear?style=social)](https://github.com/cran/metagear)
   - GUI for abstract/title screening
   - Inter-reviewer reliability assessment
   - PDF downloading capabilities
   - PRISMA flow diagrams with multiple design layouts
   - Data extraction from scatter plots and bar plots
   - `install.packages("metagear")`
   - Language: R

4. **[revtools](https://revtools.net/)**
   - Article screening for evidence synthesis
   - Topic modeling for literature exploration
   - Visual screening methods
   - Document tagging
   - `install.packages("revtools")`
   - Website: https://revtools.net/
   - Language: R

#### Citation Tracking

5. **[citationchaser](https://github.com/nealhaddaway/citationchaser)**
   [![GitHub stars](https://img.shields.io/github/stars/nealhaddaway/citationchaser?style=social)](https://github.com/nealhaddaway/citationchaser)
   - Forward and backward citation chasing
   - Lens.org API integration
   - Automated reference discovery
   - RIS file output
   - `install.packages("citationchaser")`
   - Shiny app: https://estech.shinyapps.io/citationchaser/
   - Published in Research Synthesis Methods 13(4):533-545 (2022)
   - Language: R

6. **[semscholar](https://github.com/njahn82/semscholar)**
   [![GitHub stars](https://img.shields.io/github/stars/njahn82/semscholar?style=social)](https://github.com/njahn82/semscholar)
   - R interface to Semantic Scholar API
   - Author profiles and paper metadata
   - Citations and references
   - Zotero integration
   - `remotes::install_github("njahn82/semscholar")`
   - Language: R

7. **[semanticscholar](https://github.com/KTH-Library/semanticscholar)** (KTH Library)
   - Lightweight Semantic Scholar API access
   - Author metrics (h-index, citation count)
   - Paper metadata with TLDR
   - API key support (100 requests/sec)
   - `install.packages("semanticscholar")`
   - Language: R

8. **[openalexR](https://github.com/ropensci/openalexR)**
   [![GitHub stars](https://img.shields.io/github/stars/ropensci/openalexR?style=social)](https://github.com/ropensci/openalexR)
   - R interface to OpenAlex
   - Polite pool support
   - Premium API key compatibility
   - 200M+ works, CC0 licensed
   - `install.packages("openalexR")`
   - Language: R

#### Meta-Analysis

9. **[metafor](https://github.com/wviechtb/metafor)** ⭐ Gold Standard
   [![GitHub stars](https://img.shields.io/github/stars/wviechtb/metafor?style=social)](https://github.com/wviechtb/metafor)
   - Comprehensive meta-analysis package
   - Equal/fixed/random/mixed-effects models
   - Meta-regression analysis
   - Forest, funnel, radial plots
   - Extensive documentation
   - `install.packages("metafor")`
   - Website: https://wviechtb.github.io/metafor/

10. **[meta](https://github.com/guido-s/meta)**
    [![GitHub stars](https://img.shields.io/github/stars/guido-s/meta?style=social)](https://github.com/guido-s/meta)
    - Comprehensive meta-analysis package
    - metagen(), metabin(), metacont(), metainc() functions
    - Fixed/random effects, three-level meta-analysis
    - GLMM, Hartung-Knapp method, trim-and-fill
    - RevMan 5 imports
    - `install.packages("meta")`
    - Website: https://cran.r-project.org/package=meta

11. **[metaplus](https://cran.r-project.org/package=metaplus)**
    - Robust meta-analysis using t-distribution
    - Mixture of normals for random effects
    - Outlier detection via testOutliers() and outlierProbs()
    - `install.packages("metaplus")`
    - Language: R

#### Network Meta-Analysis

12. **[netmeta](https://github.com/guido-s/netmeta)** ⭐ Most Popular
    [![GitHub stars](https://img.shields.io/github/stars/guido-s/netmeta?style=social)](https://github.com/guido-s/netmeta)
    - Frequentist network meta-analysis
    - 3,645 monthly downloads
    - Graph-theoretic methods
    - Component network meta-analysis
    - Inconsistency assessment via netheat() and netsplit()
    - `install.packages("netmeta")`
    - Language: R

13. **[gemtc](https://cran.r-project.org/package=gemtc)**
    - Bayesian NMA via JAGS/OpenBUGS/WinBUGS
    - Consistency and inconsistency models
    - 1,781 monthly downloads
    - `install.packages("gemtc")`
    - Language: R

14. **[BUGSnet](https://github.com/audrey-b/BUGSnet)**
    [![GitHub stars](https://img.shields.io/github/stars/audrey-b/BUGSnet?style=social)](https://github.com/audrey-b/BUGSnet)
    - PRISMA/ISPOR/NICE-DSU compliant outputs
    - Bayesian NMA using JAGS
    - League tables via league.table()
    - SUCRA plots via sucra()
    - `install.packages("BUGSnet")`
    - Language: R

15. **[multinma](https://cran.r-project.org/package=multinma)**
    - Network meta-analysis and meta-regression
    - Individual patient data (IPD) and aggregate data
    - `install.packages("multinma")`
    - Language: R

16. **[pcnetmeta](https://cran.r-project.org/package=pcnetmeta)**
    - Arm-based network meta-analysis
    - Treatment-specific parameters
    - Bayesian framework
    - `install.packages("pcnetmeta")`
    - Language: R

17. **[bnma](https://cran.r-project.org/package=bnma)**
    - Bayesian network meta-analysis
    - Various model specifications
    - `install.packages("bnma")`
    - Language: R

18. **[crossnma](https://cran.r-project.org/package=crossnma)**
    - Cross-design and cross-format NMA
    - Handles different study designs
    - `install.packages("crossnma")`
    - Language: R

#### Bayesian Meta-Analysis

19. **[brms](https://github.com/paul-buerkner/brms)**
    [![GitHub stars](https://img.shields.io/github/stars/paul-buerkner/brms?style=social)](https://github.com/paul-buerkner/brms)
    - Highly flexible Bayesian multilevel models
    - Stan backend
    - Meta-analysis as special case of hierarchical models
    - Formula: y | se(se_y) ~ 1 + (1|study)
    - `install.packages("brms")`
    - Language: R

20. **[bayesmeta](https://cran.r-project.org/package=bayesmeta)**
    - Bayesian random-effects meta-analysis
    - No MCMC (faster, reproducible)
    - Shrinkage estimates and prediction intervals
    - Flexible priors
    - 919 monthly downloads
    - `install.packages("bayesmeta")`
    - Language: R

21. **[MetaStan](https://cran.r-project.org/package=MetaStan)**
    - Binomial-normal hierarchical models
    - Weakly informative priors
    - Using Stan
    - `install.packages("MetaStan")`
    - Language: R

22. **[baggr](https://cran.r-project.org/package=baggr)**
    - Bayesian meta-analysis using Stan
    - Hierarchical models
    - Graphical facilities
    - `install.packages("baggr")`
    - Language: R

23. **[metaBMA](https://cran.r-project.org/package=metaBMA)**
    - Bayesian model averaging
    - Variety of priors
    - Custom prior definition
    - `install.packages("metaBMA")`
    - Language: R

#### Specialized Meta-Analysis Packages

24. **[MAd](https://cran.r-project.org/package=MAd)**
    - Meta-analysis of standardized mean differences
    - Range of graphics
    - `install.packages("MAd")`
    - Language: R

25. **[psychmeta](https://cran.r-project.org/package=psychmeta)**
    - Hunter-Schmidt method for psychometric meta-analysis
    - Reliability corrections
    - `install.packages("psychmeta")`
    - Language: R

26. **[metap](https://cran.r-project.org/package=metap)**
    - Meta-analysis of significance values
    - Edgington, Fisher, Lancaster, Stouffer, Tippett, Wilkinson methods
    - `install.packages("metap")`
    - Language: R

27. **[robumeta](https://cran.r-project.org/package=robumeta)**
    - Robust variance estimation
    - For dependent effect sizes
    - `install.packages("robumeta")`
    - Language: R

28. **[POMADE](https://cran.r-project.org/package=POMADE)**
    - Power analysis for meta-analysis
    - Dependent effect sizes
    - `install.packages("POMADE")`
    - Language: R

29. **[metamisc](https://cran.r-project.org/package=metamisc)**
    - Diagnostic and prognostic studies
    - Bayesian methods with suggested priors
    - `install.packages("metamisc")`
    - Language: R

30. **[dosresmeta](https://cran.r-project.org/package=dosresmeta)**
    - Dose-response meta-analysis
    - `install.packages("dosresmeta")`
    - Language: R

31. **[metamedian](https://cran.r-project.org/package=metamedian)**
    - Meta-analyzes studies reporting medians
    - `install.packages("metamedian")`
    - Language: R

32. **[mixmeta](https://cran.r-project.org/package=mixmeta)**
    - Multivariate and multilevel meta-analysis
    - `install.packages("mixmeta")`
    - Language: R

33. **[mvmeta](https://cran.r-project.org/package=mvmeta)**
    - Multivariate meta-analysis
    - `install.packages("mvmeta")`
    - Language: R

#### Visualization Packages

34. **[robvis](https://github.com/mcguinlu/robvis)** ⭐ Essential
    [![GitHub stars](https://img.shields.io/github/stars/mcguinlu/robvis?style=social)](https://github.com/mcguinlu/robvis)
    - Risk-Of-Bias VISualization
    - Publication-quality figures for RoB 2, ROBINS-I, ROBINS-E, QUADAS-2, QUIPS
    - Colorblind-friendly schemes
    - Over 1,500 academic citations
    - `devtools::install_github("mcguinlu/robvis")`
    - Web app: https://mcguinlu.shinyapps.io/robvis (no R required)
    - Language: R

35. **[forestplot](https://cran.r-project.org/package=forestplot)**
    - Highly customizable forest plots
    - Publication-quality graphics
    - `install.packages("forestplot")`
    - Language: R

36. **[forestploter](https://cran.r-project.org/package=forestploter)**
    - Advanced forest plots
    - Flexible layouts
    - `install.packages("forestploter")`
    - Language: R

37. **[metaviz](https://cran.r-project.org/package=metaviz)**
    - Advanced visualization for meta-analysis
    - Influence plots and cumulative plots
    - `install.packages("metaviz")`
    - Language: R

38. **[viscomp](https://github.com/georgiosseitidis/viscomp)**
    [![GitHub stars](https://img.shields.io/github/stars/georgiosseitidis/viscomp?style=social)](https://github.com/georgiosseitidis/viscomp)
    - Visualizes multi-component interventions in NMA
    - Heat plots, violin plots, waterfall plots
    - Network graphs
    - Language: R

39. **[dmetar](https://dmetar.protectlab.org/)**
    - Companion to "Doing Meta-Analysis in R"
    - Utility functions for meta/metafor
    - Heterogeneity tests and utilities
    - `install.packages("dmetar")`
    - Language: R

40. **[metaDigitise](https://cran.r-project.org/package=metaDigitise)**
    - Extracts data from published figures
    - Graphical interface
    - `install.packages("metaDigitise")`
    - Language: R

#### Bibliometric Analysis

41. **[bibliometrix](https://github.com/massimoaria/bibliometrix)** ⭐
   [![GitHub stars](https://img.shields.io/github/stars/massimoaria/bibliometrix?style=social)](https://github.com/massimoaria/bibliometrix)
   - Comprehensive science mapping
   - Citation analysis, co-citation, coupling
   - Network analysis at multiple levels
   - Visualization capabilities
   - Web interface: Biblioshiny
   - `install.packages("bibliometrix")`
   - Website: https://www.bibliometrix.org/

#### PRISMA Flow Diagrams

42. **[PRISMA2020](https://github.com/prisma-flowdiagram/PRISMA2020)** ⭐ Official
   [![GitHub stars](https://img.shields.io/github/stars/prisma-flowdiagram/PRISMA2020?style=social)](https://github.com/prisma-flowdiagram/PRISMA2020)
   - PRISMA 2020-compliant diagrams
   - Interactive HTML output
   - Hover tooltips and hyperlinks
   - Shiny app available
   - `install.packages("PRISMA2020")`
   - Website: https://prisma-flowdiagram.github.io/PRISMA2020/

43. **[livingPRISMAflow](https://github.com/nealhaddaway/livingPRISMAflow)**
   [![GitHub stars](https://img.shields.io/github/stars/nealhaddaway/livingPRISMAflow?style=social)](https://github.com/nealhaddaway/livingPRISMAflow)
   - Living systematic review diagrams
   - PRISMA checklist conformance
   - Language: R

#### Deduplication

44. **[ASySD](https://github.com/camaradesuk/ASySD)** ⭐
   [![GitHub stars](https://img.shields.io/github/stars/camaradesuk/ASySD?style=social)](https://github.com/camaradesuk/ASySD)
   - Automated citation deduplication
   - R package + Shiny app
   - Fuzzy matching algorithms
   - Web app: https://camarades.shinyapps.io/ASySD/
   - `install.packages("ASySD")`
   - Language: R

### Automation & Workflow Tools

1. **[Systematic Review Accelerator (SRA)](https://github.com/IEBH/SRA2)**
   [![GitHub stars](https://img.shields.io/github/stars/IEBH/SRA2?style=social)](https://github.com/IEBH/SRA2)
   - Reference deduplication
   - Fuzzy matching for semi-identical refs
   - Merge multiple search sources
   - Developed at Bond University
   - Language: JavaScript/Node.js

2. **[Jupyter Guide for Reproducible Research](https://github.com/jupyter-guide/jupyter-guide)**
   [![GitHub stars](https://img.shields.io/github/stars/jupyter-guide/jupyter-guide?style=social)](https://github.com/jupyter-guide/jupyter-guide)
   - Crowdsourced guidelines
   - Ten Simple Rules companion
   - Reproducible SLR workflows
   - Language: Jupyter Notebooks

3. **[Ten Rules for Jupyter](https://github.com/jupyter-guide/ten-rules-jupyter)**
   [![GitHub stars](https://img.shields.io/github/stars/jupyter-guide/ten-rules-jupyter?style=social)](https://github.com/jupyter-guide/ten-rules-jupyter)
   - Best practices for notebooks
   - Sharing computational analyses
   - Reproducibility guidelines
   - Language: Jupyter Notebooks

### Text Mining Resources

- **[text_mining_resources](https://github.com/stepthom/text_mining_resources)**
  [![GitHub stars](https://img.shields.io/github/stars/stepthom/text_mining_resources?style=social)](https://github.com/stepthom/text_mining_resources)
  - Learning resources for text mining
  - NLP techniques and tools
  - Seven-step framework
  - Document clustering, entity extraction

### GitHub Topic Collections

Explore curated collections of repositories:

- **[systematic-review](https://github.com/topics/systematic-review)** - 50+ repositories
- **[systematic-reviews](https://github.com/topics/systematic-reviews)** - 40+ repositories
- **[literature-review](https://github.com/topics/literature-review)** - 100+ repositories
- **[bibliometrics](https://github.com/topics/bibliometrics)** - 112 repositories (37 R, 21 Python)
- **[meta-analysis](https://github.com/topics/meta-analysis)** - Various tools
- **[citation-analysis](https://github.com/topics/citation-analysis)** - Network tools
- **[reproducible-research](https://github.com/topics/reproducible-research)** - Workflow tools

### Key Datasets on GitHub

- **[SYNERGY Dataset](https://github.com/asreview/synergy-dataset)**
  [![GitHub stars](https://img.shields.io/github/stars/asreview/synergy-dataset?style=social)](https://github.com/asreview/synergy-dataset)
  - Open dataset for study selection
  - 169,288 academic works
  - 26 systematic reviews
  - Benchmarking ML models

### Installation Quick Start

**Python Environment:**
```bash
# Create virtual environment
python -m venv slr-env
source slr-env/bin/activate  # On Windows: slr-env\Scripts\activate

# Screening & AI-powered tools
pip install asreview lattereview systematic-reviewpy

# Bibliometrics & literature analysis
pip install litstudy pybibx metaknowledge

# Meta-analysis
pip install PythonMeta pymare nimare

# API access for citation tracking
pip install semanticscholar pys2 pyalex

# PDF extraction & OCR
pip install marker unstructured pytesseract paddleocr

# All-in-one installation
pip install asreview lattereview systematic-reviewpy litstudy pybibx metaknowledge PythonMeta pymare semanticscholar pyalex
```

**R Environment:**
```r
# Search strategy development
install.packages(c("litsearchr", "searchAnalyzeR"))

# Screening & workflow
install.packages(c("metagear", "revtools"))

# Citation tracking
install.packages(c("citationchaser", "openalexR"))

# Meta-analysis core
install.packages(c("metafor", "meta", "metaplus"))

# Network meta-analysis
install.packages(c("netmeta", "gemtc", "BUGSnet", "multinma", "pcnetmeta", "bnma", "crossnma"))

# Bayesian meta-analysis
install.packages(c("brms", "bayesmeta", "MetaStan", "baggr", "metaBMA"))

# Specialized meta-analysis
install.packages(c("MAd", "psychmeta", "metap", "robumeta", "POMADE", "metamisc",
                   "dosresmeta", "metamedian", "mixmeta", "mvmeta"))

# Visualization
devtools::install_github("mcguinlu/robvis")
install.packages(c("forestplot", "forestploter", "metaviz", "dmetar", "metaDigitise"))

# Bibliometrics & PRISMA
install.packages(c("bibliometrix", "PRISMA2020"))

# Deduplication
install.packages("ASySD")

# All-in-one installation (core packages)
install.packages(c("litsearchr", "metagear", "revtools", "citationchaser", "openalexR",
                   "metafor", "meta", "netmeta", "brms", "bibliometrix", "PRISMA2020",
                   "ASySD", "forestplot", "metaviz"))
```

**Node.js Tools:**
```bash
# Search translation
npm install sra-polyglot
```

### Contributing to Open Source

Many of these tools welcome contributions:
- 🐛 Report bugs and issues
- 📖 Improve documentation
- 💡 Suggest features
- 🔧 Submit pull requests
- ⭐ Star repositories you find useful

---

## Datasets & Benchmarks

### CLEF eHealth Datasets:

- **[CLEF eHealth Evaluation Lab](https://sites.google.com/site/clefehealth/datasets)** ⭐
  - Technology Assisted Reviews (TAR) datasets
  - 50+ Diagnostic Test Accuracy reviews
  - Freely available for research
  - TAR 2017-2019 benchmarks

### Standard Benchmarks:

- **20-Newsgroups** - Text classification
- **TREC Total Recall** - Information retrieval
- **[CLEF eHealth TAR 2019](https://sites.google.com/view/tar2019/home)** - Most widely used SLR benchmark

### Research Datasets:

- **[Dataset of Systematic Review Updates](https://dl.acm.org/doi/10.1145/3331184.3331358)** - ACM SIGIR 2019
- Cochrane Reviews Database - Available through Cochrane Library

---

## Learning Resources

### Comprehensive Methodology Guides:

1. **[Cochrane Handbook for Systematic Reviews of Interventions](https://training.cochrane.org/handbook)** ⭐ Gold Standard
   - Version 6.5 (current as of 2024)
   - Free online access
   - Key chapters:
     - Chapter 2: Determining scope and questions
     - Chapter 3: Defining eligibility criteria (PICO)
     - Chapter 9: Summarizing study characteristics
     - Chapter 17: Intervention complexity
   - Updated continuously with Technical Supplement

2. **[PRISMA 2020 Statement](https://www.prisma-statement.org/prisma-2020)** ⭐ Essential
   - Updated 27-item checklist
   - Flow diagram templates
   - Expanded guidance
   - Key paper (Page et al. 2021): https://pubmed.ncbi.nlm.nih.gov/33782057/
   - Explanation & Elaboration: https://pubmed.ncbi.nlm.nih.gov/33781993/

3. **PRISMA Extensions:**
   - **[PRISMA-P (Protocols)](https://www.prisma-statement.org/protocols)** - 17 items
     - Systematic Reviews journal: https://systematicreviewsjournal.biomedcentral.com/articles/10.1186/2046-4053-4-1
     - Item 6 guidance on eligibility criteria
     - PubMed: https://pmc.ncbi.nlm.nih.gov/articles/PMC4320440/
   - **[PRISMA-ScR (Scoping Reviews)](https://www.prisma-statement.org/scoping)** - 20 items
     - PubMed: https://pubmed.ncbi.nlm.nih.gov/30178033/
   - **[PRISMA-S (Search Reporting)](https://pubmed.ncbi.nlm.nih.gov/33499930/)** - 16 items

4. **[JBI Manual for Evidence Synthesis](https://jbi-global-wiki.refined.site/space/MANUAL)** ⭐ Comprehensive
   - Covers 10 review types:
     - Effectiveness reviews
     - Qualitative evidence synthesis
     - Mixed methods synthesis
     - Scoping reviews
     - Economic evaluations
     - Prevalence and incidence reviews
     - Diagnostic test accuracy
     - Etiology and risk reviews
     - Umbrella reviews
     - Text and opinion reviews
   - Editors: Aromataris & Jordan (2024)
   - DOI: 10.46658/JBIMES-24-01
   - Scoping review guidance: https://www.researchgate.net/publication/319713049_2017_Guidance_for_the_Conduct_of_JBI_Scoping_Reviews

5. **[Campbell Collaboration Standards](https://www.campbellcollaboration.org/methods/standards/)**
   - Based on MECCIR and PRISMA-2020
   - 35 items across 7 sections
   - Social sciences, education, criminal justice focus
   - Policies version 1.8: https://www.campbellcollaboration.org/wp-content/uploads/2024/11/Campbell-Policies-and-Guidelines-_May3-2022.docx.pdf
   - Author guidelines: https://onlinelibrary.wiley.com/page/journal/18911803/homepage/author-guidelines

6. **[Centre for Reviews and Dissemination (CRD) Guidance](https://www.york.ac.uk/media/crd/Systematic_Reviews.pdf)** ⭐ Comprehensive
   - 300+ page guide covering all stages
   - From protocol to dissemination
   - Includes: effectiveness, tests, qualitative research, economic evaluations
   - Homepage: https://www.york.ac.uk/crd/guidance/

### University Library Guides:

**Comprehensive Multi-Page Guides:**

1. **[Cornell University - Evidence Synthesis](https://guides.library.cornell.edu/evidence-synthesis)**
   - All 12 steps from protocol development through synthesis
   - Framework comparisons (PICO vs SPIDER vs PEO)
   - Reporting standards

2. **[UNC Chapel Hill - Systematic Reviews](https://guides.lib.unc.edu/systematic-reviews)**
   - Health Sciences Library
   - AI/automation tools
   - Predictive screening
   - Search strategies
   - PICO frameworks: https://guides.lib.unc.edu/pico/frameworks

3. **[University College London (UCL)](https://library-guides.ucl.ac.uk/systematic-reviews)**
   - Collaboration with EPPI-Centre
   - Formulating questions
   - Searching databases
   - Appraising studies
   - Synthesis methods

4. **[UCLA Library](https://guides.library.ucla.edu/systematicreviews)**
   - Methodology requirements
   - Decision trees
   - Primer resources

5. **[University of Cambridge](https://libguides.cam.ac.uk/systematic-reviews)**
   - Medical Library guide
   - Stages visualization
   - Timeline guidance
   - Critical appraisal

**Additional University Guides:**
- University of Michigan: https://guides.lib.umich.edu/sysreviews/
- Washington University: https://libguides.wustl.edu/brownschoollibrarysystematicreviews/guidelines
- University of Minnesota: https://www.lib.umn.edu/services/systematic-reviews
- University of Denver: https://libguides.du.edu/systematic/scoping
- NYU: https://guides.nyu.edu/c.php?g=277003&p=7844931
- Emory: https://guides.libraries.emory.edu/SRs/reporting_prisma
- University of Cincinnati: https://guides.libraries.uc.edu/ReviewAssistance

### Online Courses:

- **[Cochrane Interactive Learning](https://training.cochrane.org/interactivelearning)** - Free modules
- **[ICO Systematic Literature Review Course](https://ico-education.nl/education/the-ico-educational-programme/ico-courses-2024-2025/25-slr-systematic-literature-review/)** - For PhD candidates
- **[Coursera: Systematic Review Course](https://www.coursera.org/)** - Multiple options

### University Guides:

- **[Monash University SLR Guide](https://guides.lib.monash.edu/systematic-review)**
- **[Princeton SLR Guide](https://libguides.princeton.edu/systematicreviews)**
- **[Harvard Meta-Analysis Guide](https://guides.library.harvard.edu/meta-analysis)**
- **[UNC Chapel Hill SLR Guide](https://guides.lib.unc.edu/systematic-reviews)**

### Video Tutorials:

- **[How to do SLR GitBook](https://drshahizan.gitbook.io/slr/)** - Step-by-step guide
- YouTube channels: Cochrane, Evidence Synthesis Ireland

### Communities & Forums:

- **[Cochrane Community](https://community.cochrane.org/)**
- **[r/AskAcademia](https://www.reddit.com/r/AskAcademia/)**
- **[ResearchGate](https://www.researchgate.net/)** - Q&A on systematic reviews
- **[Zotero Forums](https://forums.zotero.org/)**

---

## Specialized Review Types & Methodologies

### Living Systematic Reviews

**What are Living Systematic Reviews?**
- Continuously updated systematic reviews
- Evidence updated as new studies emerge
- Daily or regular automated searches
- Critical for rapidly evolving fields

**Platforms & Tools:**

1. **[L·OVE (Living OVerview of Evidence)](https://iloveevidence.com/)** ⭐ Largest Platform
   - Maps and organizes ~300,000 systematic reviews
   - Epistemonikos database
   - AI algorithms and expert networks
   - Daily evidence updates
   - PICO format organization
   - Notifications for new evidence
   - Customized reports

2. **[LIvE (Living Interactive Evidence Synthesis)](https://adjrcc.living-evidence.com/)**
   - Living Interactive Systematic Reviews (LISRs)
   - 5 major components: automated search, scanner, extractor, analyzer, tabulator
   - Three pathways: conventional, semi-automated human-in-the-loop, AI-powered

3. **[Pitts.ai](https://pitts.ai/)**
   - Web application for living systematic reviews
   - Network meta-analysis support
   - AI-driven data extraction from full-text articles
   - Mission: living systematic reviews in every disease

4. **[Cochrane Living Evidence Network](https://community.cochrane.org/review-development/resources/living-systematic-reviews)**
   - Guidance documents
   - Tech enablers: Covidence, MAGICapp, Screen4Me, RCT-classifier, RevMan Replicant, Systematic Review Accelerator
   - Updated practical guidance (December 2019)

5. **[DistillerSR](https://www.distillersr.com/resources/systematic-literature-reviews/what-is-a-living-systematic-review)**
   - Supports living review methodology
   - Screening and data extraction tools
   - PRISMA checklist integration

**Key Guidance:**
- Elliott JH et al. "Living systematic review: 1. Introduction—the why, what, when, and how"
  - PubMed: https://pubmed.ncbi.nlm.nih.gov/28912002/
  - Full text: https://www.jclinepi.com/article/S0895-4356(17)30636-4/fulltext

### Rapid Review Methodologies

**What are Rapid Reviews?**
- Accelerated systematic reviews (weeks to months vs. 12-18 months)
- Balance timeliness with rigor
- Common shortcuts: limited databases, single screener, no quality assessment
- Used for time-sensitive policy decisions

**Resources & Guidance:**

1. **[NCCMT Rapid Review Guidebook](https://www.nccmt.ca/tools/rapid-review-guidebook)** ⭐ Essential
   - Comprehensive step-by-step guide
   - By Dobbins (2017)
   - PDF: https://www.nccmt.ca/uploads/media/media/0001/01/a816af720e4d587e13da6bb307df8c907a5dff9a.pdf
   - Covers all stages from protocol to reporting

2. **[Cochrane Rapid Reviews Interim Guidance](https://methods.cochrane.org/sites/methods.cochrane.org.rapidreviews/files/uploads/cochrane_rr_-_guidance-23mar2020-final.pdf)**
   - March 2020 guidance
   - Cochrane Rapid Reviews Methods Group
   - Specific methodological standards

3. **[WHO EMRO Training Package](https://www.emro.who.int/evidence-data-to-policy/training-package/rapid-reviews.html)**
   - Comprehensive training materials
   - Webinars available
   - Ottawa Hospital Research Institute experiences

**Methodological Papers:**
- "Paper 2: Performing rapid reviews" - https://systematicreviewsjournal.biomedcentral.com/articles/10.1186/s13643-022-02011-5
- "Rapid reviews methods series" - https://pmc.ncbi.nlm.nih.gov/articles/PMC10715469/

**University Guides:**
- VCU: https://guides.library.vcu.edu/rapidreview
- University of Melbourne: https://unimelb.libguides.com/whichreview/rapidreview
- James Cook University: https://libguides.jcu.edu.au/rapidreview
- University of Toronto: https://guides.library.utoronto.ca/c.php?g=713309&p=5083943

### Scoping Review Tools & Frameworks

**What are Scoping Reviews?**
- Map available evidence in a field
- Identify key concepts, gaps, and types of evidence
- Broader than systematic reviews
- Don't typically assess quality

**Frameworks:**

1. **[Arksey & O'Malley Framework (2005)](https://www.tandfonline.com/doi/full/10.1080/1364557032000119616)** - Original
   - Six-stage iterative process
   - Identifying research questions → identifying studies → study selection → charting data → collating/summarizing/reporting → optional consultation

2. **Enhanced Frameworks:**
   - Levac et al. (2010): https://implementationscience.biomedcentral.com/articles/10.1186/1748-5908-5-69
   - Pham et al. (2014): https://onlinelibrary.wiley.com/doi/10.1002/jrsm.1123

3. **[JBI Scoping Review Methodology](https://jbi-global-wiki.refined.site/space/MANUAL/355862497/10.+Scoping+reviews)** ⭐ Current Standard
   - Updated 2020 guidance (Peters et al.)
   - PubMed: https://pubmed.ncbi.nlm.nih.gov/33038124/
   - Network resources: https://jbi.global/scoping-review-network
   - Protocol template: https://jbi.global/sites/default/files/2024-04/JBI_Protocol_Template_Scoping_Reviews_2024.docx

4. **[PRISMA-ScR](https://www.prisma-statement.org/scoping)** - Reporting Standard
   - 20 essential + 2 optional items
   - EQUATOR: https://www.equator-network.org/reporting-guidelines/prisma-scr/
   - Developed by 24-member expert panel (Tricco et al., 2018)
   - PubMed: https://pubmed.ncbi.nlm.nih.gov/30178033/
   - Fillable checklist and flow diagram template

**University Guides:**
- University of South Australia: https://guides.library.unisa.edu.au/ScopingReviews/ReportSearchResults
- Knowledge Translation Program: https://knowledgetranslation.net/portfolios/the-prisma-scr-prisma-extension-for-scoping-reviews/

### Umbrella Review Tools

**What are Umbrella Reviews?**
- Reviews of systematic reviews
- Synthesize evidence from multiple systematic reviews
- High-level evidence synthesis
- Also called "overview of reviews" or "meta-reviews"

**Quality Assessment Tools:**

1. **[AMSTAR 2](https://amstar.ca/)** ⭐ Most Used (~80% of umbrella reviews)
   - 16-item critical appraisal tool
   - See Quality Assessment section above

2. **[ROBIS](https://www.bristol.ac.uk/population-health-sciences/projects/robis/)**
   - Risk Of Bias In Systematic reviews
   - Three-phase instrument
   - Focuses on bias (complementary to AMSTAR 2)

3. **JBI Critical Appraisal Checklist**
   - Systematic review checklist for umbrella reviews
   - Recommended by JBI (not validated)

**Guidance Documents:**
- "Umbrella reviews: a methodological guide" (European Journal of Cardiovascular Nursing, 2025)
  - https://academic.oup.com/eurjcn/article/24/6/996/7974731
- "A step-by-step guide for conducting an umbrella review" (Tropical Medicine and Health, 2025)
  - https://tropmedhealth.biomedcentral.com/articles/10.1186/s41182-025-00764-y
- Methodological approaches analyzing 99 umbrella reviews
  - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0269009

**Overlap Management:**
- **GROOVE** (Graphical representation of overlap for overviews)
- **CCA index** (Corrected covered area) for managing primary study overlap

### Realist Review Frameworks

**What are Realist Reviews?**
- Theory-driven synthesis
- Explains "what works, for whom, in what circumstances, and why"
- Uses Context-Mechanism-Outcome (CMO) configurations
- Based on Pawson and Tilley's realist evaluation

**RAMESES Standards:**

1. **[RAMESES Project](http://ramesesproject.org/)** ⭐ Gold Standard
   - Realist And Meta-narrative Evidence Syntheses – Evolving Standards
   - Funded by UK NIHR
   - Standards and training: https://www.ramesesproject.org/Standards_and_Training_materials.php

2. **[RAMESES I - Realist Syntheses](https://bmcmedicine.biomedcentral.com/articles/10.1186/1741-7015-11-21)**
   - 19 publication standards
   - BMC Medicine 2013
   - PubMed: https://pubmed.ncbi.nlm.nih.gov/23360677/
   - EQUATOR Network: https://www.equator-network.org/reporting-guidelines/rameses-publication-standards-realist-syntheses/
   - Developed through Delphi process (37-member panel, 90% response rate)

3. **[RAMESES II - Realist Evaluations](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-016-0643-1)**
   - Reporting standards for realist evaluations
   - BMC Medicine 2016
   - PubMed: https://pubmed.ncbi.nlm.nih.gov/27342217/
   - EQUATOR Network: https://www.equator-network.org/reporting-guidelines/rameses-ii-reporting-standards-for-realist-evaluations/
   - International Delphi panel with maximum variety expert sample

**Training & Resources:**
- Free training materials for researchers, evaluators, participants
- Patient and public involvement materials
- Full project reports:
  - RAMESES I: https://www.ncbi.nlm.nih.gov/books/NBK260013/
  - RAMESES II: https://pubmed.ncbi.nlm.nih.gov/29072890/
- JISCMail list: www.jiscmail.ac.uk/RAMESES

### Protocol Registration Platforms

**Why Register?**
- Transparency and reduces publication bias
- Prevents duplication of effort
- Some journals require pre-registration

**Platforms:**

1. **[OSF (Open Science Framework) Registries](https://osf.io/)** ⭐ Most Flexible
   - Free registration
   - Generalized Systematic Review Registration template: https://osf.io/by27q/
   - No formal editorial review
   - Version tracking, DOIs, immediate publication
   - Center for Open Science announcement: https://www.cos.io/blog/generalized-systematic-review-template-joins-osf-registries

2. **[INPLASY](https://inplasy.com/)** - Specialized SLR Registry
   - Launched March 2020
   - Accepts: systematic reviews, scoping reviews, meta-analyses, umbrella reviews, rapid reviews, methodological reviews, meta-research
   - INPLASY unique identifiers + DOIs
   - ORCID automatic updates
   - 94%+ protocols published within 24 hours
   - Over 4,658 protocols (as of March 2023)
   - Registration fee
   - Analysis: https://pubmed.ncbi.nlm.nih.gov/37588882/

3. **[protocols.io](https://www.protocols.io/)**
   - Generic protocol registration
   - Example: https://www.protocols.io/view/systematic-review-protocol-ha2sb2gef.html
   - Free of charge, no formal assessment
   - Version tracking, DOIs provided

4. **[Research Registry](https://www.researchregistry.com/)**
   - Systematic review/meta-analysis registry
   - Immediate visibility
   - Registration fee, DOIs provided

5. **[PROSPERO](https://www.crd.york.ac.uk/prospero/)** - Health Sciences
   - International registry (mentioned in Planning & Protocol section)
   - Required for many health journals
   - Free but can have long approval times

**Comparison Resource:**
- "Where to prospectively register a systematic review"
  - Systematic Reviews journal: https://systematicreviewsjournal.biomedcentral.com/articles/10.1186/s13643-021-01877-1
  - PubMed: https://pubmed.ncbi.nlm.nih.gov/34998432/
  - Compares PROSPERO, Research Registry, INPLASY, OSF Registries, protocols.io

### Qualitative Synthesis Methods

**Common Approaches:**

1. **Meta-ethnography (Noblit & Hare 1988)** - Most Common
   - 7-stage approach
   - Reciprocal translation and line-of-argument synthesis
   - Third-order interpretations beyond original studies
   - **Best for**: Developing analytical findings, lived experiences research

2. **Thematic synthesis (Thomas & Harden 2008)**
   - Combines meta-ethnography and grounded theory
   - Line-by-line coding → descriptive themes → analytical themes
   - **Best for**: Intervention need, appropriateness, acceptability questions

3. **Framework synthesis**
   - Uses a priori frameworks to structure synthesis
   - Data extraction into predetermined frameworks
   - Modified iteratively
   - **Best for**: Theory-driven reviews, policy questions with clear structure

4. **Meta-aggregation**
   - JBI approach
   - Assembling findings through categorization
   - Credibility ratings
   - **Best for**: Straightforward evidence aggregation

5. **Critical Interpretive Synthesis (CIS)**
   - Iterative approach problematizing literature
   - Elastic terminology, multi-disciplinary teams
   - **Best for**: Broad review questions, generating theory, cross-disciplinary topics

---

## ⚠️ Common Challenges & How to Avoid Them

Based on experienced researchers' insights, here are the most common pitfalls and how to avoid them:

### 1. Poor Search Strategy

**❌ Mistake:** Search too narrow (miss relevant papers) or too broad (overwhelmed with irrelevant results)

**✅ Solution:**
- Use PICO/PICOT frameworks to structure your question
- Combine synonyms with OR: `(machine learning OR deep learning OR neural network*)`
- Combine concepts with AND: `(machine learning) AND (healthcare) AND (diagnosis)`
- Test search strings on pilot searches (should find known key papers)
- Document all search strings and dates for reproducibility

**Example Search String:**
```
("systematic review" OR "literature review" OR "meta-analysis")
AND
("machine learning" OR "deep learning" OR "artificial intelligence" OR AI)
AND
(healthcare OR medical OR clinical)
```

### 2. Inadequate Protocol Planning

**❌ Mistake:** Starting without a clear protocol, leading to scope creep and inconsistent decisions

**✅ Solution:**
- Write protocol BEFORE searching (use PRISMA-P checklist)
- Register protocol on [PROSPERO](https://www.crd.york.ac.uk/prospero/) for transparency
- Define clear inclusion/exclusion criteria upfront
- Pre-specify all outcomes and analysis plans
- Get protocol peer-reviewed by colleagues

### 3. Poor Inter-Rater Reliability

**❌ Mistake:** Reviewers disagree on study selection, leading to bias

**✅ Solution:**
- Use at least 2 independent reviewers for screening
- Pilot screening on 50-100 abstracts to calibrate
- Measure agreement (Cohen's Kappa ≥ 0.6 is acceptable)
- Have clear decision rules for conflicts
- Use tools like [Rayyan](https://www.rayyan.ai/) or [Covidence](https://www.covidence.org/) for blind screening

### 4. Data Extraction Errors

**❌ Mistake:** Inconsistent or incorrect data extraction, transposition errors

**✅ Solution:**
- Create standardized extraction forms (pilot test on 5-10 papers)
- Use double data extraction (2 reviewers extract independently)
- Cross-check numerical data carefully
- Use tools: [Covidence](https://www.covidence.org/), [DistillerSR](https://www.distillersr.com/), or structured spreadsheets
- Keep extraction audit trail

### 5. Inadequate Documentation

**❌ Mistake:** Can't reproduce the review or explain decisions months later

**✅ Solution:**
- Document everything: search dates, databases, filters used
- Keep decision logs (why studies were excluded)
- Save all search results and versions
- Use version control (GitHub) for protocol and data
- Follow PRISMA 2020 reporting guidelines

### 6. Ignoring Grey Literature

**❌ Mistake:** Only searching academic databases, missing important studies

**✅ Solution:**
- Search conference proceedings, dissertations, preprints
- Check clinical trial registries (ClinicalTrials.gov)
- Contact key authors for unpublished work
- Search: Google Scholar, OpenGrey, ProQuest Dissertations

### 7. Poor Time Management

**❌ Mistake:** Underestimating time required (SLRs typically take 6-18 months!)

**✅ Solution:**
- Realistic timeline: Planning (1-2 months) → Searching (1 month) → Screening (2-4 months) → Extraction (2-3 months) → Analysis (1-2 months) → Writing (2-3 months)
- Use project management tools: [Notion](https://www.notion.so/), [Trello](https://trello.com/), or [OSF](https://osf.io/)
- Set weekly goals and track progress
- Build in buffer time for unexpected issues

### 8. Tool Overwhelm

**❌ Mistake:** Trying to learn too many tools at once

**✅ Solution:**
- Start with simple, free tools: [Rayyan](https://www.rayyan.ai/) + [Zotero](https://www.zotero.org/)
- Add complexity only when needed
- Use our [Quick Start Guide](#-quick-start-guide) based on your role
- Stick to one tool per task (don't switch mid-review)

### 9. Poor Quality Assessment

**❌ Mistake:** Skipping quality assessment or using wrong tools

**✅ Solution:**
- Choose appropriate tool for study type:
  - RCTs: [Cochrane RoB 2](https://www.riskofbias.info/)
  - Non-RCTs: [ROBINS-I](https://www.riskofbias.info/welcome/robins-i-tool)
  - Multiple designs: [JBI Tools](https://jbi.global/critical-appraisal-tools)
- Have 2 independent assessors
- Report quality scores in results
- Consider sensitivity analysis (excluding low-quality studies)

### 10. Publication Bias

**❌ Mistake:** Only including published studies (positive results bias)

**✅ Solution:**
- Search trial registries for unpublished trials
- Use funnel plots to detect publication bias
- Contact authors for unpublished data
- Report potential limitations in discussion

---

## 📝 Practical Examples & Templates

### Search String Examples

#### Example 1: Machine Learning in Healthcare
```
Title/Abstract/Keywords:
("machine learning" OR "deep learning" OR "neural network*" OR "artificial intelligence" OR AI)
AND
(diagnos* OR predict* OR classif* OR detect*)
AND
(medical OR clinical OR healthcare OR patient*)

Filters: English, 2015-2024, Peer-reviewed
```

#### Example 2: Software Engineering Education
```
("software engineering" OR "computer science" OR "programming")
AND
(education* OR teaching OR learning OR pedagog* OR curriculum)
AND
("systematic review" OR "literature review" OR survey OR "state of the art")
```

#### Example 3: Climate Change Adaptation
```
("climate change" OR "global warming" OR "climate crisis")
AND
(adapt* OR resilien* OR mitigation)
AND
(urban OR cit* OR "built environment")
AND
(policy OR policies OR governance OR planning)
```

### PICO/PICOT Framework Examples

#### Example: Clinical Question
- **P**opulation: Adults with Type 2 diabetes
- **I**ntervention: Continuous glucose monitoring
- **C**omparison: Standard blood glucose monitoring
- **O**utcome: HbA1c levels, hypoglycemic events
- **T**ime: At least 6 months follow-up

#### Example: Technology Question (PICO adaptation)
- **P**roblem: Software bug prediction
- **I**ntervention: Machine learning approaches
- **C**omparison: Traditional static analysis
- **O**utcome: Precision, recall, F1-score

### Downloadable Protocol Templates

1. **[PRISMA-P Template (Word)](https://www.prisma-statement.org/protocols)**
   - Official PRISMA protocol checklist
   - 17-item checklist
   - Free to use

2. **[Covidence Protocol Guide (PDF)](https://www.covidence.org/wp-content/uploads/2024/10/A_practical_guide_Protocol_Development_for_Systematic_Reviews.pdf)**
   - Practical guide with examples
   - Templates included
   - Real-world case studies

3. **[OSF Protocol Template](https://osf.io/jd4k2/)**
   - Preregistration template
   - For systematic reviews, scoping reviews, meta-analyses
   - Open access under CC license

4. **[York CRD Template (PDF)](https://www.crd.york.ac.uk/PROSPEROFILES/3611_STRATEGY_20130031.pdf)**
   - Systematic review protocol outline
   - Structured format
   - Widely used in health sciences

### Inclusion/Exclusion Criteria Examples

#### Example 1: Quantitative Studies
**Inclusion:**
- Peer-reviewed journal articles
- Published 2015-2024
- Randomized controlled trials (RCTs)
- Adults aged 18-65
- Intervention duration ≥ 12 weeks
- Reported outcomes: quantitative measures with statistics

**Exclusion:**
- Conference abstracts, posters
- Non-English language
- Animal studies
- Case reports, editorials, reviews
- Duplicate publications
- No full text available

#### Example 2: Mixed Methods
**Inclusion:**
- Empirical studies (qualitative, quantitative, mixed)
- Focus on software engineering practices
- Published in ACM, IEEE, or top-tier SE venues
- Full research papers (≥ 8 pages)

**Exclusion:**
- Opinion pieces, position papers
- Tool demos without evaluation
- Studies with <10 participants (qualitative)
- Pre-2010 (outdated technology)

### Data Extraction Form Template

| Field | Example Value | Notes |
|-------|---------------|-------|
| **Study ID** | Smith2024 | FirstAuthorYear |
| **Title** | ML for Medical Diagnosis | |
| **Authors** | Smith, J., Doe, A. | |
| **Year** | 2024 | |
| **Journal** | Nature Medicine | |
| **Study Design** | RCT | RCT/Cohort/Case-Control |
| **Sample Size** | n=500 | |
| **Population** | Type 2 Diabetes patients | |
| **Intervention** | CNN-based diagnosis | |
| **Comparison** | Traditional diagnosis | |
| **Outcome Measures** | Accuracy, Sensitivity, Specificity | |
| **Main Results** | Acc: 95%, Sens: 92%, Spec: 97% | |
| **Quality Score** | 8/10 (Cochrane RoB) | Low/Moderate/High |
| **Notes** | Large sample, well-designed | |

### PRISMA Flow Diagram Template

You can generate this automatically with:
- **R**: [PRISMA2020 package](https://github.com/prisma-flowdiagram/PRISMA2020) ✅ Free
- **Web App**: [PRISMA Flow Diagram Generator](http://prisma.thetacollaborative.ca/) ✅ Free
- **Shiny App**: [prisma.shinyapps.io/checklist](https://prisma.shinyapps.io/checklist/) ✅ Free

---

## ❓ FAQ for Young Researchers

### Getting Started

**Q: How long does a systematic review take?**
A: Typically 6-18 months depending on scope. Budget realistic time:
- Small review (50-200 papers): 6-9 months
- Medium review (200-500 papers): 9-12 months
- Large review (500+ papers): 12-18 months

**Q: Can I do a systematic review alone?**
A: Not recommended! You need at least 2 reviewers for:
- Independent screening (reduce bias)
- Data extraction validation
- Quality assessment
- Conflict resolution
However, you can be the lead with 1-2 collaborators.

**Q: Do I need to register my protocol?**
A: Strongly recommended (required for some journals):
- Health sciences: [PROSPERO](https://www.crd.york.ac.uk/prospero/) (required)
- Other fields: [OSF Registries](https://osf.io/registries) (recommended)
- Prevents duplication and selective reporting

**Q: How many databases should I search?**
A: Minimum 3-4 major databases for your field:
- Health: PubMed + Cochrane + Embase + Scopus
- Engineering/CS: IEEE Xplore + ACM + Scopus + Web of Science
- Social Sciences: PsycINFO + ERIC + Scopus + Web of Science

### Search Strategy

**Q: How do I know if my search string is good?**
A: Test it:
1. Should find 3-5 known key papers (seed papers)
2. Precision > 5% (not too broad)
3. Recall > 90% (not too narrow)
4. Validated by a librarian or search expert

**Q: Should I use MeSH terms or free text?**
A: BOTH! Use controlled vocabulary (MeSH, EMTREE) AND free text synonyms:
```
MeSH Terms: "Diabetes Mellitus, Type 2"[Mesh]
OR
Free Text: (diabetes OR diabetic*) AND (type 2 OR type II OR T2DM)
```

**Q: What if I get 10,000+ results?**
A: Refine your search:
1. Add more specific AND terms
2. Limit date range
3. Add publication type filters
4. Consult with search expert
5. Use AI tools like [ASReview](https://asreview.nl/) for efficient screening

### Tools & Software

**Q: What's the best free tool for beginners?**
A: Start with:
1. **Screening**: [Rayyan](https://www.rayyan.ai/) (free, unlimited collaborators)
2. **References**: [Zotero](https://www.zotero.org/) (free, open-source)
3. **Analysis**: [RevMan](https://revman.cochrane.org/) (free, from Cochrane)
4. **Writing**: [Overleaf](https://www.overleaf.com/) (free tier for LaTeX)

**Q: Is Excel okay for data extraction?**
A: Yes, for small reviews (<50 studies). For larger reviews:
- Use dedicated tools: [Covidence](https://www.covidence.org/), [DistillerSR](https://www.distillersr.com/)
- Or structured databases with version control
- Excel pros: familiar, flexible
- Excel cons: error-prone, no audit trail, hard to collaborate

**Q: Can I use ChatGPT for systematic reviews?**
A: ⚠️ Use with caution:
- ❌ DON'T use for: screening decisions, quality assessment, data extraction
- ✅ CAN use for: brainstorming search terms, paraphrasing text, organizing notes
- ✅ BETTER alternatives: [Elicit](https://elicit.com/), [Consensus](https://consensus.app/), [Scite](https://scite.ai/) (designed for research)
- ALWAYS verify AI outputs with original sources!

### Screening & Selection

**Q: How many reviewers do I need for screening?**
A: Minimum 2 independent reviewers:
- Title/abstract screening: 2 reviewers independently
- Full-text screening: 2 reviewers independently
- Conflicts: resolved by discussion or 3rd reviewer
- Pilot screening: ~10% of records to calibrate

**Q: What's an acceptable inter-rater agreement?**
A: Measured by Cohen's Kappa (κ):
- κ > 0.80: Excellent
- κ = 0.60-0.80: Good (acceptable)
- κ = 0.40-0.60: Moderate (needs improvement)
- κ < 0.40: Poor (recalibrate criteria)

**Q: Can I use AI to reduce screening workload?**
A: Yes! AI tools can reduce workload by 60-95%:
- [ASReview](https://asreview.nl/): 95% workload reduction
- [Abstrackr](http://abstrackr.cebm.brown.edu/): ~67% reduction
- Must still manually review AI suggestions
- Document AI tool use in methods

### Quality & Analysis

**Q: Do I have to assess study quality?**
A: YES! It's a core requirement of systematic reviews:
- Shows which studies are trustworthy
- Helps interpret conflicting results
- Allows sensitivity analyses
- Use appropriate tools: [Cochrane RoB 2](https://www.riskofbias.info/), [JBI Tools](https://jbi.global/critical-appraisal-tools)

**Q: When should I do meta-analysis vs narrative synthesis?**
A: Meta-analysis requirements:
- ✅ Studies measure same outcome
- ✅ Sufficient statistical data reported
- ✅ Studies are comparable (population, intervention)
- ✅ >3-5 studies available
- ❌ If not: do narrative synthesis
- Tools: [RevMan](https://revman.cochrane.org/), [R metafor](https://www.metafor-project.org/)

**Q: What if studies are too different (heterogeneous)?**
A: Options:
1. Use random-effects meta-analysis (accounts for heterogeneity)
2. Do subgroup analyses (by population, intervention type, etc.)
3. Perform meta-regression (explore sources of heterogeneity)
4. Resort to narrative synthesis
5. Report heterogeneity statistics (I², τ²)

### Writing & Reporting

**Q: What's the difference between systematic review and literature review?**
A:
| Feature | Literature Review | Systematic Review |
|---------|-------------------|-------------------|
| Research question | Broad | Focused, specific (PICO) |
| Search | Selective | Comprehensive, documented |
| Selection criteria | Implicit | Explicit, pre-defined |
| Quality assessment | Variable | Mandatory, standardized |
| Synthesis | Narrative | Systematic +/- meta-analysis |
| Protocol | Optional | Required (PRISMA-P) |
| Reproducible | No | Yes |

**Q: Do I have to follow PRISMA?**
A: Highly recommended:
- Many journals REQUIRE PRISMA compliance
- Improves transparency and reproducibility
- Makes writing easier (follows logical structure)
- Use [PRISMA 2020 Checklist](https://www.prisma-statement.org/prisma-2020-checklist)
- Generate flow diagram: [R package](https://github.com/prisma-flowdiagram/PRISMA2020) or [web tool](http://prisma.thetacollaborative.ca/)

**Q: Where should I publish my systematic review?**
A: Depends on field:
- **General**: [Systematic Reviews](https://systematicreviewsjournal.biomedcentral.com/) (open access)
- **CS/Engineering**: [ACM CSUR](https://dl.acm.org/journal/csur), [IEEE COMST](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9739)
- **Health**: Cochrane Library, medical specialty journals
- **Consider**: Impact factor, open access options, audience

### Common Issues

**Q: I found a paper after screening is done. What do I do?**
A: It happens! Options:
1. If before analysis: add to full-text screening
2. If after analysis: mention in limitations
3. For living reviews: add to next update
4. Document the paper and why it was missed

**Q: What if I can't access a full-text paper?**
A: Try:
1. University library access + interlibrary loan
2. Email corresponding author directly (surprisingly effective!)
3. ResearchGate request
4. Legal repositories: [PubMed Central](https://pmc.ncbi.nlm.nih.gov/), institutional repositories
5. Last resort: exclude and note in PRISMA diagram

**Q: Reviewers disagree - how do we resolve conflicts?**
A: Protocol should specify:
1. Discussion between reviewers (most common)
2. Third reviewer makes final decision
3. Pre-defined decision rules
4. Document all conflicts and resolutions
5. Report agreement statistics (Kappa)

### Time-Savers

**Q: Any tips to speed up the process?**
A:
1. **Screening**: Use [ASReview](https://asreview.nl/) (95% time savings)
2. **Deduplication**: [ASySD](https://camarades.shinyapps.io/ASySD/) R package
3. **Citation snowballing**: [ResearchRabbit](https://www.researchrabbit.ai/), [Connected Papers](https://www.connectedpapers.com/)
4. **PDF extraction**: [GROBID](https://github.com/kermitt2/grobid) for automated extraction
5. **AI assistance**: [Elicit](https://elicit.com/) for quick summaries
6. **Team collaboration**: [Covidence](https://www.covidence.org/) or [Rayyan](https://www.rayyan.ai/) for parallel work

**Q: Can I update an existing systematic review?**
A: Yes! Systematic Review Updates are valuable:
- Search from last review's end date
- Use same criteria (or justify changes)
- Cite original review
- Some journals specialize in updates
- Consider "living systematic reviews" for rapidly evolving fields

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Guidelines:
- Add new resources with clear descriptions
- Include links (verify they work!)
- Categorize appropriately
- Indicate if free/paid

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

---

## Acknowledgments

This resource was created to help young researchers navigate the complex world of systematic literature reviews. Special thanks to all the tool developers, open source communities, and institutions making research more accessible.

**Good luck with your systematic literature review! 🎓📚**

---

**Last Updated:** November 2024

**Maintainer:** Open to community contributions
