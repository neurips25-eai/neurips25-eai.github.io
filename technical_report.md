---
layout: default
---

# 📝 Technical Report Instructions

Welcome to the Embodied Agent Interface (EAI) Challenge! This document contains the official instructions for your technical report submission. All teams participating in the Final Evaluation Phase must submit a technical report describing their approach, experiments, and results. This template provides a structured format following NeurIPS 2025 conference style guidelines.

**Important:** The LaTeX template provides a suggested structure to guide your writing. Teams are allowed and encouraged to modify the structure, add additional sections, or reorganize content as needed to best present their work. The key requirement is to meet the formatting guidelines and cover all essential content areas.

---

- [Overview](#overview)
  - [Eligibility and Registration](#eligibility-and-registration)
  - [Public Submissions](#public-submissions)
- [Files Included](#files-included)
- [Requirements](#requirements)
  - [Page Limit](#page-limit)
  - [Formatting Requirements](#formatting-requirements)
- [Report Structure Overview](#report-structure-overview)
  - [Excluded from Page Limit](#excluded-from-page-limit)
  - [Optional Sections](#optional-sections)
- [How to Use This Template](#how-to-use-this-template)
  - [Step 1: Setup LaTeX Environment](#step-1-setup-latex-environment)
  - [Step 2: Download Template Files](#step-2-download-template-files)
  - [Step 3: Fill in the Template](#step-3-fill-in-the-template)
  - [Step 4: Compile Your Document](#step-4-compile-your-document)
- [Submission Guidelines](#submission-guidelines)
  - [Deadline](#deadline)
  - [Where to Submit](#where-to-submit)
  - [What to Submit](#what-to-submit)
  - [Important: OpenReview Account Creation](#important-openreview-account-creation)
- [Writing Tips](#writing-tips)
  - [Aim for High Quality](#aim-for-high-quality)
  - [Be Clear and Specific](#be-clear-and-specific)
  - [Conduct Thorough Analysis](#conduct-thorough-analysis)
  - [Ensure Reproducibility](#ensure-reproducibility)
- [Evaluation Criteria](#evaluation-criteria)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Citation](#citation)

---


## Overview

### Eligibility and Registration

**All teams are welcome to participate in the Final Evaluation Phase**, even if you missed the Development Phase. Teams who join during the Final Evaluation Phase are still eligible for prizes.

**Required Action**: All participating teams must fill out the registration form:
- **Registration Form**: [https://forms.gle/eZri9Sj9RGDwJYzt6](https://forms.gle/eZri9Sj9RGDwJYzt6)

This form collects essential information including your EvalAI team name, team members, and affiliation.

### Public Submissions

**All technical reports will be made public** on OpenReview, similar to ICLR conference submissions. This provides several valuable opportunities:

- **Professional Development**: Practice writing high-quality research papers in a conference-style format
- **Portfolio Building**: Add a publicly accessible technical report to your resume and academic portfolio
- **Community Contribution**: Share your insights and approaches with the broader embodied AI research community
- **Visibility**: Showcase your work to potential collaborators, advisors, and employers

Given the public nature of these submissions, **teams should strive for the highest quality** in their technical reports. This is an excellent opportunity to demonstrate your research and technical writing skills to a wide audience.

## Files Included

The `eai_starter_kit/latex_template/` directory contains:

- `technical_report_template.tex` - Main LaTeX template file with detailed instructions
- `neurips_2025.sty` - NeurIPS 2025 style file (required for compilation)
- `references.bib` - Bibliography file you can use to cite your sources

This document provides comprehensive submission instructions and guidelines.

## Requirements

### Page Limit
- **Main content**: 8 pages maximum (including figures and tables)
- **Biography section**: Does not count toward page limit (included in appendix)
- **References**: Unlimited (does not count toward page limit)
- **Appendix**: Optional, unlimited pages (does not count toward page limit)

### Formatting Requirements
- Use the provided NeurIPS 2025 style file
- Font: Times Roman, 10pt for main text
- Do not modify margins or spacing
- Papers violating formatting requirements may be rejected

## Report Structure Overview

The technical report follows a standard academic paper structure with specific requirements for the EAI Challenge. Your technical report must include the following content areas. **Note:** The section structure below is suggested but not mandatory. Feel free to organize your report differently to best present your work, as long as you cover all essential content.

1. **Title and Authors**: Team name, all team members, affiliations, and corresponding author contact
2. **Abstract**: Concise summary covering:
   - Overall methodology and key innovations
   - Main results across all four tasks
   - Key findings, insights, and limitations
3. **Introduction**: 
   - Background and motivation
   - Problem statement and relation to challenge objectives
   - Key contributions of your work
4. **Related Work**: Discussion of relevant prior work in embodied AI, task planning, and language models for robotics
5. **Method**: Detailed technical description with subsections for:
   - **Goal Interpretation**: Input representation, model architecture/prompting strategy, handling ambiguity, task-specific innovations
   - **Subgoal Decomposition**: Decomposition strategy, hierarchical planning, granularity determination, temporal dependencies
   - **Action Sequencing**: Sequence generation methodology, constraint handling, optimization strategies, executability
   - **Transition Modeling**: State prediction mechanism, model-based vs. learning-based approaches, object interactions, uncertainty handling
   - **Environment-Specific Adaptations**: Differences between BEHAVIOR and VirtualHome, adaptation strategies
6. **Implementation Details**: 
   - Models experimented with (including unsuccessful attempts)
   - Inference parameters (temperature, top-p, max tokens, etc.)
   - Preprocessing and post-processing steps
   - Computational resources and runtime
   - Software frameworks and versions
7. **Evaluation Results**: 
   - Comprehensive quantitative results for all four tasks
   - Performance on both BEHAVIOR and VirtualHome environments
   - Tables and figures visualizing comparisons
   - Ablation studies and comparative analyses
8. **Analysis and Discussion**: In-depth analysis including:
   - **Error Analysis**: Common failure modes, systematic biases, error categorization with examples
   - **Task-Specific Analysis**: Detailed analysis for each of the four tasks
   - **Cross-Environment Comparison**: Performance differences between BEHAVIOR and VirtualHome
   - **Insights and Lessons Learned**: Key takeaways and recommendations for future participants
   - **Case Studies**: Representative success cases, failure cases, and edge cases
9. **Conclusion**: Summary of results, limitations, future improvements, and research directions
10. **Reproducibility Statement**: Code availability, model checkpoints, hyperparameters, computational requirements, random seeds
11. **References**: All relevant citations (unlimited pages)
12. **Appendix**: 
    - **Biography**: Team name and short biography of all team members (required, does not count toward page limit)
    - Additional results, extended ablations, full prompts (optional)

### Optional Sections
- **Ethics Statement**: Discussion of potential impacts and responsible AI considerations (recommended)
- **Acknowledgments**: External funding, computational resources, helpful discussions, and any other relevant information.
- **Extended Appendix**: Additional results, full prompts, extended ablations, supplementary figures


### Excluded from Page Limit

- **Reproducibility Statement**: Detailed information for reproducing your results
- **Acknowledgments** (optional): Funding sources, computational resources, collaborators
- **References**: All citations (unlimited)
- **Appendix**:
  - Biography section with team name and member bios (required)
  - Extended results, full prompts, additional ablations (optional)

## How to Use This Template

### Step 1: Setup LaTeX Environment

Ensure you have a LaTeX distribution installed:
- **Online**(Recommended): Overleaf (https://www.overleaf.com/)
- **Linux**: TeX Live (`sudo apt-get install texlive-full`)
- **macOS**: MacTeX (https://www.tug.org/mactex/)
- **Windows**: MiKTeX (https://miktex.org/)

### Step 2: Download Template Files

Download all three files from [eai_starter_kit/latex_template/](https://drive.google.com/file/d/1d-SfGfp109NjRVhY8tFWrNu_KyWpLJbB/view?usp=sharing) to your working directory:
- `technical_report_template.tex` (main template)
- `neurips_2025.sty` (style file)
- `references.bib` (bibliography with EAI citation)

All files must be in the same directory for successful compilation.

### Step 3: Fill in the Template

The template includes extensive inline instructions and placeholder text to guide you. Follow these steps:

1. **Update Title and Authors**: 
   - Modify the title to include your team name and approach
   - List all team members with affiliations
   - Mark the corresponding author with contact email
   
2. **Fill in Each Section**:
   - Replace placeholder text with your actual content
   - The template provides suggested structure and guidance
   - Feel free to modify sections, add new subsections, or reorganize as needed
   - The key is to cover all essential content while best showcasing your work
   
3. **Add Your Content**:
   - Include figures using `\includegraphics{}` (place image files in same directory)
   - Create tables using the `booktabs` package for professional formatting
   - Add citations using `\cite{key}` and add new entries to `references.bib`
   
4. **Complete the Biography Section**:
   - In the Appendix, add your team name and short bios for all members
   - This section does not count toward the 8-page limit
   
5. **Review and Polish**:
   - Ensure all sections are complete and meet the requirements
   - Check that all figures/tables have descriptive captions
   - Verify all citations are properly formatted

### Step 4: Compile Your Document

Compile the LaTeX document into a PDF using your preferred LaTeX editor (e.g. Overleaf).

## Submission Guidelines

### Deadline
- **Technical Report Submission**: 12/01/2025 12:00AM UTC-0
- Grace period may be granted for exceptional cases
- **Important**: Create OpenReview accounts with institutional emails well before the deadline to avoid moderation delays

### Where to Submit
- **Submission Portal**: [OpenReview - NeurIPS 2025 Workshop FMEA](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/FMEA)
- Follow the OpenReview submission instructions on the portal

### What to Submit

All submissions must be made through OpenReview. You will need to upload:

**PDF of technical report**:
   - Must include both the main paper and appendix (if applicable) in a single PDF file
   - Follow the naming convention: `EAI2025_TeamName_TechnicalReport.pdf`
   - Ensure all content (main body + biography section + any additional appendices) is in one document

### Important: OpenReview Account Creation

**Before the submission deadline**, ensure all team members create OpenReview accounts:

- **Recommended**: Use an institutional email address (e.g., .edu, .ac.uk, etc.)
  - Profiles created with institutional emails are **activated automatically**
  - You can submit immediately after account creation
  
- **Not Recommended**: Personal email addresses (gmail, outlook, etc.)
  - New profiles created without institutional emails go through a **moderation process**
  - Moderation can take **up to two weeks**
  - This may cause you to miss the submission deadline

**Action Required**: Create your OpenReview account well in advance using your institutional email to avoid delays. All team members should be listed as co-authors during submission.

## Writing Tips

### Aim for High Quality

Since all submissions will be made public on OpenReview, treat this as an opportunity to produce a polished, professional research paper:
- Write clearly and professionally—this will be part of your public academic portfolio
- Ensure thorough proofreading and editing before submission
- Use high-quality figures and well-formatted tables
- Follow academic writing best practices
- Consider this as practice for future conference submissions

### Be Clear and Specific
- Describe your method in enough detail for reproducibility
- Use figures and diagrams to illustrate your approach
- Include concrete examples where helpful

### Conduct Thorough Analysis
- Provide error analysis with qualitative examples categorized by failure type
- Analyze performance on each task individually
- Compare results across BEHAVIOR and VirtualHome environments
- Present case studies with success cases, failure cases, and edge cases
- Discuss what worked and what didn't
- Share insights that could help future participants

### Ensure Reproducibility
- Specify all models, versions, and hyperparameters (including both successful and unsuccessful attempts)
- Document all inference parameters (temperature, top-p, max tokens, etc.)
- Describe preprocessing and post-processing steps in detail
- Report computational requirements (GPU/TPU types, memory, runtime)
- Provide links to code repositories and model checkpoints if available
- Include random seeds and complete experimental setup
- Specify software framework versions (Python, CUDA, PyTorch/TensorFlow, etc.)

## Evaluation Criteria

Technical reports will be evaluated based on:

1. **Technical Quality** 
   - Soundness of methodology
   - Novelty and creativity of approach
   - Depth of technical content

2. **Effort and Completeness**
   - Number of approaches explored
   - Number of traditional autoregressive LLMs experimented with(e.g. Qwen3 series, Llama4 series, etc.)
   - Number of diffusion LLMs experimented with(e.g. RND1.)

3. **Experimental Rigor** 
   - Comprehensive evaluation across all tasks
   - Appropriate ablation studies
   - Thorough analysis and error analysis

4. **Clarity and Presentation** 
   - Clear writing and organization
   - Effective use of figures and tables
   - Reproducibility of results

5. **Results and Impact** 
   - Performance on challenge benchmarks
   - Insights and contributions to the field


## Frequently Asked Questions

### Q: Can I participate in the Final Evaluation Phase if I missed the Development Phase?
**A**: Yes! All teams are welcome to participate in the Final Evaluation Phase, even if you missed the Development Phase. You are still eligible for prizes. Make sure to fill out the registration form at [https://forms.gle/eZri9Sj9RGDwJYzt6](https://forms.gle/eZri9Sj9RGDwJYzt6).

### Q: Do I need to fill out the registration form?
**A**: Yes, all participating teams must complete the registration form. This helps us collect essential information including your EvalAI team name, team members, and affiliation. Register at [https://forms.gle/eZri9Sj9RGDwJYzt6](https://forms.gle/eZri9Sj9RGDwJYzt6).

### Q: Can we submit a report if we didn't achieve top performance?
**A**: Yes! All teams that participated in the challenge are encouraged to submit. We value thorough analysis and insights regardless of leaderboard position.

### Q: Can we include results from additional experiments beyond the challenge?
**A**: Yes, additional experiments and analysis are welcome, especially if they provide insights into the tasks.

### Q: Is the ethics statement required?
**A**: It's recommended but not strictly required. We encourage discussion of potential impacts and responsible AI considerations.

### Q: Will the reports be published?
**A**: Yes, all technical reports will be made public on OpenReview, following the ICLR conference model. This is an excellent opportunity to build your portfolio and contribute to the research community. Selected reports may also be featured on the challenge website.

### Q: Can we publish this work elsewhere?
**A**: Yes, you retain full rights to your work. You may submit to other venues following their respective guidelines.

### Q: What should be included in the biography section?
**A**: Include your team name as used in the challenge, and a short biography (2-3 sentences) for each team member covering their affiliation, research interests, and relevant background. This section is required but does not count toward the 8-page limit.

### Q: Do we need to report results for models that didn't work well?
**A**: Yes, documenting unsuccessful attempts in the Implementation Details section is valuable for reproducibility and provides insights to the community. You don't need to analyze them in depth, but mentioning what you tried helps others avoid similar paths.

### Q: Must we follow the exact template structure?
**A**: No, the LaTeX template provides a suggested structure, but you are allowed and encouraged to modify it as needed. You can add sections, reorganize content, or adjust subsections to best present your work. The key requirements are: (1) use the NeurIPS 2025 style file, (2) stay within the 8-page limit for main content, and (3) cover all essential content areas.

### Q: How do I submit to OpenReview?
**A**: Visit the [OpenReview submission portal](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/FMEA), create an account if needed (strongly recommended to use institutional email for immediate activation), and follow the submission instructions. Upload your complete PDF (including appendix) and add all team members as co-authors. You can also upload supplementary materials if needed.

### Q: Why should I use an institutional email for OpenReview?
**A**: OpenReview automatically activates accounts created with institutional email addresses (.edu, .ac.uk, etc.), allowing you to submit immediately. Accounts created with personal emails (gmail, outlook, etc.) require manual moderation that can take up to two weeks, which may cause you to miss the submission deadline. Create your account early with an institutional email to avoid delays.

### Q: Should the appendix be in a separate PDF?
**A**: No, the appendix must be included in the same PDF as the main paper. Your submission should be a single PDF file containing: (1) main content (up to 8 pages), (2) reproducibility statement, (3) references, (4) biography section (required), and (5) any additional appendices. Do not submit the appendix as a separate file.

## Citation

If you use the EAI benchmark or participate in the challenge, please cite:

```bibtex
@article{li2024embodied,
  title={Embodied agent interface: Benchmarking llms for embodied decision making},
  author={Li, Manling and Zhao, Shiyu and Wang, Qineng and Wang, Kangrui and Zhou, Yu and Srivastava, Sanjana and Gokmen, Cem and Lee, Tony and Li, Erran Li and Zhang, Ruohan and others},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={100428--100534},
  year={2024}
}
```

