
# Portfolio Project: Data Visualization Portfolio

**Total Points:** 35 + 5 bonus  
**Submission:** ZIP archive with index.html, relevant data sources + Video presentation (5-7 minutes)
Optionally: a website published on github pages (not graded)


---

## TL;DR - Quick Overview

**Portfolio with minimum 5 visualizations exploring a unified theme**

**Submit by Week 8:**
- ZIP file with `index.html`, datasets, and `VIDEO_LINK.txt`
- 5-7 minute video presentation

**Must demonstrate:**
- Clear analytical questions (data/task abstraction)
- Justified chart choices and visual encodings
- Professional documentation (titles, labels, legends, sources)
- Sophisticated techniques (interactivity OR layers OR multiple views)
- Coherent narrative connecting all visualizations

**Grade:** 35 points across 5 categories + optional 5-point live presentation bonus

**Tools:** Any visualization tool (Tableau, Vega-Lite, Python, R, D3.js, etc.)

**Data:** Use your own datasets or public data - NOT instructor-provided assignment datasets

**Key checklist:** Each visualization needs meaningful title, source citation, proper labels, appropriate color use, and at least one sophisticated element (interactive/layered/concatenated)

*📖 Read below for complete requirements, grading rubric, and submission details*

---
## Assignment Overview

Create a portfolio of data visualizations that demonstrates your mastery of the principles learned throughout this course. Your portfolio should showcase your ability to transform data into clear, effective visual communication.

**Core Philosophy:** We value well-crafted, sophisticated visualizations that clearly convey useful information. Quality and depth matter more than quantity.

---

## What You Need To Do

Create a portfolio containing **minimum 5 visualizations** that demonstrate your understanding of:

- Data and task abstraction (Munzner's framework from Week 2)
- Visual encoding principles
- Chart selection and design rationale
- Color theory and accessibility
- Technical implementation skills

**Submit:**

1. **ZIP archive** (`Portfolio_[LastName]_[FirstName].zip`) containing:
    
    - `index.html` (your portfolio - template provided)
    - All datasets referenced in your visualizations
    - AI usage documentation (if applicable - see policy below)

2. **Video presentation** (5-7 minutes):
    - Walkthrough of your portfolio
    - Highlight key visualizations and design decisions
    - Discuss what you learned
    - Upload to YouTube/Google Drive and **embed link in your index.html**

---

## Technical Requirements

### Dataset Requirements

**❌ Prohibited:**

- Instructor-provided datasets from assignments (Bikeshare, World Energy, OWID Population)
- Default tutorial datasets (vega-datasets, Tableau samples, Iris, Titanic, etc.)

**✅ Allowed:**

- Datasets YOU brought to previous assignments (reuse is fine)
- Makeover Monday datasets not used in class
- Your own research/work data
- Government open data portals
- Kaggle datasets (non-tutorial)
- Domain-specific professional datasets

**You may reuse your own previous assignment work IF you brought your own data.**

**All data sources must be cited with links where possible.**

### Tools & Technologies

**You have complete freedom** to use any visualization tool(s):

- Vega-Lite (learned in class)
- Tableau Public (learned in class)
- Python libraries (Altair, Matplotlib, Plotly, etc.)
- R (ggplot2, etc.)
- D3.js, Observable notebooks
- Any other professional visualization tools

**Tool choice does NOT affect grading.** Mastery of one tool is equally valid as using multiple tools. Use what works best for your visualizations.

**Critical requirement:** Source code must be available. For Tableau, visualizations must be published in YOUR Tableau Public account (not mine, not a classmate's).

### Refining Previous Work

You may include enhanced work from Assignments 2-4, IF:

- You brought your own dataset (not instructor-provided data)
- You've significantly improved it: new analytical question, different chart type, added interactivity/layers, substantially better documentation

Simply resubmitting assignment work with minor label changes will not earn full credit.

---

## Visualization Quality Checklist

**Every visualization must include (or explicitly explain why not applicable):**

✅ **Meaningful title** - Not "Chart 1" but "GDP Growth Rates in Eastern Europe, 2010-2020"

✅ **Source citation** - Where the data came from, with link if possible

✅ **Appropriate labels** - Axis labels, value labels where needed, units specified

✅ **Legends when necessary** - If using color/size/shape encoding, provide legend

✅ **Appropriate use of color** - Color is used meaningfully and corresponds to the data type (categorical / sequential / diverging / highlight)

✅ **At least ONE of these:**

- **Interactive elements** (filters, tooltips, brushing/linking)
- **Layered marks** (multiple mark types composed together)
- **Concatenated views** (small multiples, hconcat/vconcat, or dashboard composition)

**If any checklist item doesn't apply to your visualization, you must explain why in your documentation.**

Example: "No legend needed because color encodes the same information shown on the x-axis labels."

---

## Portfolio Structure

We've provided a template HTML file (see course materials). Your portfolio should include:

### Introduction Section (3-5 sentences)

Explain your portfolio theme - the common question or domain you're exploring. This is required for full points.

**A "theme" means:** A common question or domain explored through multiple visualizations.

**Good themes:**

- "Economic inequality in Ukraine" - 5 visualizations exploring different dimensions
- "My company's user behavior" - 5 visualizations answering related business questions
- "Climate change impacts" - 5 visualizations showing different evidence

**Not a theme:**

- 5 random visualizations on unrelated topics
- "Visualizations I made for class" without connecting narrative

### For EACH Visualization:

1. **Context & Question** (1-2 sentences)
    - What analytical question does this address?
    - Why is this question important?
2. **Design Decisions** (2-3 sentences)
    - Chart type selection and rationale
    - Visual encoding choices (position, color, size, etc.)
    - What alternatives did you consider and why did you choose this approach?
    - What are the strengths and tradeoffs of your choice?
3. **The Visualization Itself**
    - Must render and work properly
    - Must meet quality checklist (or explain exceptions)
4. **Key Insights** (2-3 sentences)
    - What patterns, trends, or outliers did you discover?
    - What should viewers take away from this visualization?
5. **Data Source Citation**
    - Where did the data come from?
    - Include links if possible

---

## Grading Rubric (35 points)

### Technical Execution (10 points)

**All visualizations render correctly, proper tool usage, source code available**

- **10 pts:** Perfect execution, no errors
- **8 pts:** Minor issues (one viz loads slowly, small formatting glitch)
- **6 pts:** Multiple problems affecting experience
- **<6 pts:** Significant technical failures

**Source code requirement:** For Tableau, visualizations must be in YOUR Tableau Public account. For code-based tools, include specifications in your HTML. (you can use LLMs  to aid if not sure about how to format code in HTML)

### Theoretical Understanding (10 points)

**Data/Task Abstraction (5 pts):** Clear analytical questions, appropriate data transformations

**Design Rationale (5 pts):** Justified chart selections, discussion of alternatives and tradeoffs, addresses "why this chart type?"

### Visual Communication (5 points)

**Clarity & professional documentation**

- Visualizations clearly convey useful information
- Proper titles, labels, legends (per checklist)
- All sources cited
- Clean, professional presentation

### Complexity & Polish (5 points)

**Majority of visualizations meet the quality checklist**

- **5 pts:** All 5+ visualizations meet checklist requirements
- **4 pts:** 4 visualizations meet full checklist
- **3 pts:** 3 visualizations meet full checklist
- **<3 pts:** Fewer than 3 meet requirements

### Coherent Portfolio Theme (5 points)

**Portfolio tells a unified story**

- **5 pts:** Clear theme, explicit connections between visualizations, coherent narrative in introduction
- **3-4 pts:** Weak theme or connections not clearly articulated
- **0-2 pts:** No discernible theme, random collection of visualizations

---

**Additional Deductions:**

- Video >7 minutes: -2 points
- Video <4 minutes: -2 points
- Missing or inaccessible video: -5 points
- Missing AI documentation (if AI was used): -5 points
- Fewer than 5 visualizations: Up to -10 points depending on severity

---

## Bonus: Live Portfolio Presentation (+5 points)

**Optional:** Present your portfolio live during Week 8 classes.

**Requirements:**

- 10-minute presentation + 5-minute Q&A
- Must opt-in by **end of Week 7** via Slack
- Present live (no pre-recorded videos)
- Demonstrate your portfolio and discuss design choices

**This is separate from the theme requirement.** The live presentation is a bonus opportunity for students who want to showcase their work and potentially recover points from earlier assignments.

**Limited slots available** - first come, first served after opt-in.

---

## Video Presentation Requirements

**Purpose:** The video serves as documentation of your work and ensures we can evaluate your portfolio even if technical rendering issues occur.
**Duration:** 5-7 minutes (videos under 4 minutes or over 7 minutes will be penalized)

**Content to cover:**

1. **Introduction** (30-60 seconds): Your portfolio theme and approach
2. **Visualization walkthrough** (3-5 minutes):
    - You may highlight 2-3 key visualizations in depth, OR
    - Briefly cover all 5+ visualizations
    - Focus on design decisions and key insights
3. **Reflection** (30-60 seconds): What you learned

**Technical:** Upload to YouTube or Google Drive storage and **include the link prominently in your index.html** (for example, in the Introduction section or create a dedicated "Video Presentation" section at the top). 
If uploading to Google Drive, **make sure to enable external access to your video!**


---

## Deployment to GitHub Pages (Optional)

We provide instructions for deploying your portfolio to GitHub Pages, making it publicly accessible. **This is completely optional and NOT graded** - I recognize this is a data visualization course, not a web development course.

Benefits of deploying:

- Shareable portfolio link for your CV/LinkedIn
- Professional online presence
- Easy to show potential employers

You can also run everything locally if you prefer. Deployment guide is provided separately in the repository.

---

## Submission Checklist

Before submitting, verify:

**Portfolio Content:**

- [ ] Minimum 5 visualizations included
- [ ] All visualizations render and work properly
- [ ] Each visualization meets quality checklist (or explains why not)
- [ ] Introduction section explains portfolio theme
- [ ] Each visualization includes: Context, Design Decisions, Insights, Data Source
- [ ] All data sources cited with links where possible

**Technical Files:**

- [ ] `index.html` file at root of archive
- [ ] All referenced datasets included in archive
- [ ] File named correctly: `Portfolio_[LastName]_[FirstName].zip`

**Video Presentation:**

- [ ] 5-7 minutes duration
- [ ] Covers portfolio theme, key visualizations, and learnings
- [ ] Link included in index.html

**Documentation:**

- [ ] AI usage documented if applicable (shared conversation links or PDFs)

**Optional:**

- [ ] Opted in for live presentation (by end of Week 7)
- [ ] Deployed to GitHub Pages

---

## Academic Integrity & AI Usage

### AI Tools Policy

**All AI usage must be documented:**

- Include links to shared LLM conversations, OR
- Attach PDF exports of your conversations
- Create a folder in your ZIP called `AI_Documentation` with these files

**Make it trivial for graders to access your AI usage history.**

**Remember:** AI can help with code syntax or brainstorming, but design decisions and analytical insights must reflect YOUR understanding of visualization principles.

### Originality

- Do not copy visualizations from online sources
- Do not submit someone else's work
- If reusing existing visualizations from previous assignments, document this clearly
- Your analysis and design decisions must be your own

---

## Final Reminder

**The goal isn't to impress with technical wizardry (though that's welcome).**

**The goal is to demonstrate that you can:**

- Transform data into clear, effective visual communication
- Apply systematic design principles
- Make justified choices about visual encodings
- Reveal insights that tell compelling stories with evidence

Your portfolio should show that you understand WHY certain visualizations work better than others, and that you can create professional-quality work that communicates effectively.

Good luck, and we look forward to seeing your portfolios!
