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
- [Study Management](#study-management)
- [Screening & Selection](#screening--selection)
- [Data Extraction](#data-extraction)
- [Quality Assessment](#quality-assessment)
- [Analysis & Synthesis](#analysis--synthesis)
- [Visualization](#visualization)
- [Writing & Reporting](#writing--reporting)
- [Reference Management](#reference-management)
- [Collaboration Tools](#collaboration-tools)
- [AI-Powered Tools](#ai-powered-tools)
- [Open Source Tools & GitHub Repositories](#open-source-tools--github-repositories)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Learning Resources](#learning-resources)

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

### Citation Discovery:

- **[Connected Papers](https://www.connectedpapers.com/)** - Visual citation network exploration
- **[ResearchRabbit](https://www.researchrabbit.ai/)** - "Spotify for research" - personalized recommendations
- **[CitNetExplorer](https://www.citnetexplorer.nl/)** - Citation network analysis

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

3. **[ROBINS-I](https://www.riskofbias.info/welcome/robins-i-tool)**
   - Risk of bias in non-randomized studies
   - For intervention studies

### Quality Assessment Frameworks:

- **[AMSTAR 2](https://amstar.ca/)** - For systematic reviews of interventions
- **[CASP Checklists](https://casp-uk.net/casp-tools-checklists/)** - Critical Appraisal Skills Programme
- **[QUADAS-2](https://www.bristol.ac.uk/population-health-sciences/projects/quadas/)** - Diagnostic accuracy studies
- **[NIH Quality Assessment Tools](https://www.nhlbi.nih.gov/health-topics/study-quality-assessment-tools)**

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

- EndNote, Zotero, Mendeley (built-in)
- **[SRA De-duplicator](https://sr-accelerator.com/)** - Systematic Review Accelerator
- EPPI-Reviewer, DistillerSR (integrated)

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
   - Active learning for systematic reviews
   - Published in Nature Machine Intelligence
   - Reduces workload by up to 95%
   - Privacy-first, no data collection
   - `pip install asreview`
   - 📊 Stars: 700+ | Language: Python

2. **[LatteReview](https://github.com/PouriaRouzrokh/LatteReview)**
   - Low-code AI-powered automation
   - Multi-agent review systems
   - Customizable agent roles
   - Supports multiple review rounds
   - Language: Python

3. **[systematic-reviewpy](https://github.com/chandraveshchaudhari/systematic-reviewpy)**
   - Python framework for automation
   - Customizable and open-source
   - Saves time without quality constraints
   - Language: Python

#### Literature Analysis & Bibliometrics

4. **[LitStudy](https://github.com/NLeSC/litstudy)**
   - Automate literature analysis from Jupyter notebooks
   - Scientometrics and bibliometrics
   - Network analysis and visualization
   - Natural language processing
   - `pip install litstudy`
   - Language: Python

5. **[pyBibX](https://github.com/Valdecy/pybibx)**
   - Bibliometric and scientometric analysis
   - AI-powered features
   - Generates EDA reports
   - Creates document/author/institution IDs
   - `pip install pybibx`
   - Language: Python

6. **[metaknowledge](https://github.com/UWNETLAB/metaknowledge)**
   - Bibliometric research simplification
   - Reads meta-data from various sources
   - Network analysis capabilities
   - `pip install metaknowledge`
   - Language: Python

#### Citation Snowballing

7. **[snowballing](https://github.com/JoaoFelipe/snowballing)** ⭐
   - Literature snowballing tools
   - Chrome plugin for Google Scholar
   - Jupyter Notebook widgets
   - Citation graph visualization
   - Forward/backward snowballing
   - Documentation: https://joaofelipe.github.io/snowballing
   - Language: Python

#### PDF Data Extraction

8. **[GROBID](https://github.com/kermitt2/grobid)** ⭐ Industry Standard
   - Machine learning for PDF extraction
   - Focus on scientific publications
   - Structured XML/TEI output
   - Extracts metadata + full text
   - 68 fine-grained structure labels
   - 📊 Stars: 3,500+ | Language: Java/Python

9. **[PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit)**
   - High-quality content extraction
   - Layout detection, formula recognition
   - OCR for complex PDFs
   - Works on papers, textbooks, reports
   - Language: Python

10. **[MinerU](https://github.com/opendatalab/MinerU)**
    - Transforms PDFs to markdown/JSON
    - LLM-ready format
    - Machine-readable outputs
    - Language: Python

11. **[PDFDataExtractor](https://github.com/cat-lemonade/PDFDataExtractor)**
    - Semantic information extraction
    - Focused on scientific articles
    - Language: Python

#### Text Mining & NLP

12. **[medaCy](https://github.com/NLPatVCU/medaCy)**
    - Medical text mining framework
    - Built on spaCy
    - Fast model prototyping
    - Highly predictive medical NLP
    - Language: Python

### R Packages

#### Meta-Analysis

1. **[metafor](https://github.com/wviechtb/metafor)** ⭐ Gold Standard
   - Comprehensive meta-analysis package
   - Equal/fixed/random/mixed-effects models
   - Meta-regression analysis
   - Forest, funnel, radial plots
   - Extensive documentation
   - `install.packages("metafor")`
   - Website: https://wviechtb.github.io/metafor/

2. **[meta](https://github.com/guido-s/meta)**
   - User-friendly general package
   - Standard meta-analysis methods
   - Companion to "Meta-Analysis with R" book
   - `install.packages("meta")`

3. **[dmetar](https://dmetar.protectlab.org/)**
   - Companion to "Doing Meta-Analysis in R"
   - Utility functions for meta/metafor
   - Facilitates workflow
   - `install.packages("dmetar")`

#### Bibliometric Analysis

4. **[bibliometrix](https://github.com/massimoaria/bibliometrix)** ⭐
   - Comprehensive science mapping
   - Citation analysis, co-citation, coupling
   - Network analysis at multiple levels
   - Visualization capabilities
   - Web interface: Biblioshiny
   - `install.packages("bibliometrix")`
   - Website: https://www.bibliometrix.org/

#### PRISMA Flow Diagrams

5. **[PRISMA2020](https://github.com/prisma-flowdiagram/PRISMA2020)** ⭐ Official
   - PRISMA 2020-compliant diagrams
   - Interactive HTML output
   - Hover tooltips and hyperlinks
   - Shiny app available
   - `install.packages("PRISMA2020")`
   - Website: https://prisma-flowdiagram.github.io/PRISMA2020/

6. **[livingPRISMAflow](https://github.com/nealhaddaway/livingPRISMAflow)**
   - Living systematic review diagrams
   - PRISMA checklist conformance
   - Language: R

#### Deduplication

7. **[ASySD](https://github.com/camaradesuk/ASySD)** ⭐
   - Automated citation deduplication
   - R package + Shiny app
   - Fuzzy matching algorithms
   - Web app: https://camarades.shinyapps.io/ASySD/
   - `install.packages("ASySD")`
   - Language: R

### Automation & Workflow Tools

1. **[Systematic Review Accelerator (SRA)](https://github.com/IEBH/SRA2)**
   - Reference deduplication
   - Fuzzy matching for semi-identical refs
   - Merge multiple search sources
   - Developed at Bond University
   - Language: JavaScript/Node.js

2. **[Jupyter Guide for Reproducible Research](https://github.com/jupyter-guide/jupyter-guide)**
   - Crowdsourced guidelines
   - Ten Simple Rules companion
   - Reproducible SLR workflows
   - Language: Jupyter Notebooks

3. **[Ten Rules for Jupyter](https://github.com/jupyter-guide/ten-rules-jupyter)**
   - Best practices for notebooks
   - Sharing computational analyses
   - Reproducibility guidelines
   - Language: Jupyter Notebooks

### Text Mining Resources

- **[text_mining_resources](https://github.com/stepthom/text_mining_resources)**
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

# Install key tools
pip install asreview litstudy pybibx metaknowledge
```

**R Environment:**
```r
# Install key packages
install.packages(c("metafor", "meta", "bibliometrix", "PRISMA2020", "ASySD"))
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

### Comprehensive Guides:

1. **[Cochrane Handbook for Systematic Reviews](https://training.cochrane.org/handbook)** ⭐ Essential
   - Version 6.4 (2023)
   - Gold standard methodology
   - Free online access
   - Chapter-by-chapter guidance

2. **[PRISMA Resources](https://www.prisma-statement.org/)** ⭐ Essential
   - Checklists and flow diagrams
   - Examples and tutorials
   - All extensions documented

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
