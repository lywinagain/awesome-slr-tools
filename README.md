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
   - Python framework for automation
   - Customizable and open-source
   - Saves time without quality constraints
   - Language: Python

#### Literature Analysis & Bibliometrics

4. **[LitStudy](https://github.com/NLeSC/litstudy)**
   [![GitHub stars](https://img.shields.io/github/stars/NLeSC/litstudy?style=social)](https://github.com/NLeSC/litstudy)
   - Automate literature analysis from Jupyter notebooks
   - Scientometrics and bibliometrics
   - Network analysis and visualization
   - Natural language processing
   - `pip install litstudy`
   - Language: Python

5. **[pyBibX](https://github.com/Valdecy/pybibx)**
   [![GitHub stars](https://img.shields.io/github/stars/Valdecy/pybibx?style=social)](https://github.com/Valdecy/pybibx)
   - Bibliometric and scientometric analysis
   - AI-powered features
   - Generates EDA reports
   - Creates document/author/institution IDs
   - `pip install pybibx`
   - Language: Python

6. **[metaknowledge](https://github.com/UWNETLAB/metaknowledge)**
   [![GitHub stars](https://img.shields.io/github/stars/UWNETLAB/metaknowledge?style=social)](https://github.com/UWNETLAB/metaknowledge)
   - Bibliometric research simplification
   - Reads meta-data from various sources
   - Network analysis capabilities
   - `pip install metaknowledge`
   - Language: Python

#### Citation Snowballing

7. **[snowballing](https://github.com/JoaoFelipe/snowballing)** ⭐
   [![GitHub stars](https://img.shields.io/github/stars/JoaoFelipe/snowballing?style=social)](https://github.com/JoaoFelipe/snowballing)
   - Literature snowballing tools
   - Chrome plugin for Google Scholar
   - Jupyter Notebook widgets
   - Citation graph visualization
   - Forward/backward snowballing
   - Documentation: https://joaofelipe.github.io/snowballing
   - Language: Python

#### PDF Data Extraction

8. **[GROBID](https://github.com/kermitt2/grobid)** ⭐ Industry Standard
   [![GitHub stars](https://img.shields.io/github/stars/kermitt2/grobid?style=social)](https://github.com/kermitt2/grobid)
   - Machine learning for PDF extraction
   - Focus on scientific publications
   - Structured XML/TEI output
   - Extracts metadata + full text
   - 68 fine-grained structure labels
   - Language: Java/Python

9. **[PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit)**
   [![GitHub stars](https://img.shields.io/github/stars/opendatalab/PDF-Extract-Kit?style=social)](https://github.com/opendatalab/PDF-Extract-Kit)
   - High-quality content extraction
   - Layout detection, formula recognition
   - OCR for complex PDFs
   - Works on papers, textbooks, reports
   - Language: Python

10. **[MinerU](https://github.com/opendatalab/MinerU)**
    [![GitHub stars](https://img.shields.io/github/stars/opendatalab/MinerU?style=social)](https://github.com/opendatalab/MinerU)
    - Transforms PDFs to markdown/JSON
    - LLM-ready format
    - Machine-readable outputs
    - Language: Python

11. **[PDFDataExtractor](https://github.com/cat-lemonade/PDFDataExtractor)**
    [![GitHub stars](https://img.shields.io/github/stars/cat-lemonade/PDFDataExtractor?style=social)](https://github.com/cat-lemonade/PDFDataExtractor)
    - Semantic information extraction
    - Focused on scientific articles
    - Language: Python

#### Text Mining & NLP

12. **[medaCy](https://github.com/NLPatVCU/medaCy)**
    [![GitHub stars](https://img.shields.io/github/stars/NLPatVCU/medaCy?style=social)](https://github.com/NLPatVCU/medaCy)
    - Medical text mining framework
    - Built on spaCy
    - Fast model prototyping
    - Highly predictive medical NLP
    - Language: Python

### R Packages

#### Meta-Analysis

1. **[metafor](https://github.com/wviechtb/metafor)** ⭐ Gold Standard
   [![GitHub stars](https://img.shields.io/github/stars/wviechtb/metafor?style=social)](https://github.com/wviechtb/metafor)
   - Comprehensive meta-analysis package
   - Equal/fixed/random/mixed-effects models
   - Meta-regression analysis
   - Forest, funnel, radial plots
   - Extensive documentation
   - `install.packages("metafor")`
   - Website: https://wviechtb.github.io/metafor/

2. **[meta](https://github.com/guido-s/meta)**
   [![GitHub stars](https://img.shields.io/github/stars/guido-s/meta?style=social)](https://github.com/guido-s/meta)
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
   [![GitHub stars](https://img.shields.io/github/stars/massimoaria/bibliometrix?style=social)](https://github.com/massimoaria/bibliometrix)
   - Comprehensive science mapping
   - Citation analysis, co-citation, coupling
   - Network analysis at multiple levels
   - Visualization capabilities
   - Web interface: Biblioshiny
   - `install.packages("bibliometrix")`
   - Website: https://www.bibliometrix.org/

#### PRISMA Flow Diagrams

5. **[PRISMA2020](https://github.com/prisma-flowdiagram/PRISMA2020)** ⭐ Official
   [![GitHub stars](https://img.shields.io/github/stars/prisma-flowdiagram/PRISMA2020?style=social)](https://github.com/prisma-flowdiagram/PRISMA2020)
   - PRISMA 2020-compliant diagrams
   - Interactive HTML output
   - Hover tooltips and hyperlinks
   - Shiny app available
   - `install.packages("PRISMA2020")`
   - Website: https://prisma-flowdiagram.github.io/PRISMA2020/

6. **[livingPRISMAflow](https://github.com/nealhaddaway/livingPRISMAflow)**
   [![GitHub stars](https://img.shields.io/github/stars/nealhaddaway/livingPRISMAflow?style=social)](https://github.com/nealhaddaway/livingPRISMAflow)
   - Living systematic review diagrams
   - PRISMA checklist conformance
   - Language: R

#### Deduplication

7. **[ASySD](https://github.com/camaradesuk/ASySD)** ⭐
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
