# PROJECT STRUCTURE GUIDE
## AI Leadership & Project Management Masterclass

This document explains the organization of the masterclass materials.

---

## Folder Organization Philosophy

The project is organized by **WHO uses the files** and **WHEN they use them**:

- **`/activities/materials/`** → Materials students USE during activities (cards, cases)
- **`/instructor-materials/`** → Guides for instructors to FACILITATE activities (organized by activity)
- **`/handouts/`** → Reference materials students TAKE HOME (frameworks, templates)
- **`/docs/`** → Rendered outputs for the website (generated, don't edit)
- **`/retailflow-site/`** → Company simulation website for immersive case study

---

## Directory Structure

```
ai-leadership-and-pm/
│
├── SOURCE FILES (Edit these)
│   │
│   ├── activities/materials/          ← Materials USED IN activities
│   │   ├── case-briefs/              ← Scenario descriptions
│   │   │   ├── pilot_scoping_case.qmd
│   │   │   └── crisis_sim_overview.qmd
│   │   │
│   │   ├── constraint-cards/         ← Planning constraints (Activity 1)
│   │   │   ├── budget-cut.qmd
│   │   │   ├── scope-creep.qmd
│   │   │   ├── timeline-acceleration.qmd
│   │   │   └── vendor-lock-in.qmd
│   │   │
│   │   ├── crisis-cards/             ← Crisis scenarios (Activity 3)
│   │   │   ├── data-quality.qmd
│   │   │   ├── team-resistance.qmd
│   │   │   ├── executive-pressure.qmd
│   │   │   └── ethical-dilemma.qmd
│   │   │
│   │   ├── pilot-data/               ← Pilot metrics for Activity 4
│   │   │   └── pilot-data-dashboard.qmd
│   │   │
│   │   └── role-cards/               ← Stakeholder perspectives (Activity 2)
│   │       ├── 1-data-scientist-ai-engineer.qmd
│   │       ├── 2-operations-manager.qmd
│   │       ├── 3-end-user-store-manager.qmd
│   │       ├── 4-it-security-manager.qmd
│   │       ├── 5-finance-cfo.qmd
│   │       └── 6-executive-sponsor.qmd
│   │
│   ├── instructor-materials/         ← FACILITATION guides (organized by activity)
│   │   ├── README.qmd               ← Master instructor guide
│   │   ├── facilitator-quick-reference.qmd  ← Day-of cheat sheet
│   │   │
│   │   ├── activity-1-pilot-scoping/
│   │   │   ├── facilitation-guide.qmd
│   │   │   └── constraint-cards-interactive.qmd
│   │   │
│   │   ├── activity-2-speed-dating/
│   │   │   ├── facilitation-guide.qmd
│   │   │   └── stakeholder-cards-interactive.qmd
│   │   │
│   │   ├── activity-3-crisis-management/
│   │   │   ├── facilitation-guide.qmd
│   │   │   ├── framework-walkthrough-crisis-1.qmd
│   │   │   ├── framework-walkthrough-crisis-2.qmd
│   │   │   ├── framework-walkthrough-crisis-3.qmd
│   │   │   └── crisis-walkthroughs/
│   │   │       ├── data-quality.md
│   │   │       ├── team-resistance.md
│   │   │       └── executive-pressure.md
│   │   │
│   │   ├── activity-4-scale-pivot-kill/
│   │   │   ├── facilitation-guide.qmd
│   │   │   ├── facilitation-guide-detailed.qmd
│   │   │   ├── debrief-outline.qmd
│   │   │   ├── decision-framework-reference.qmd
│   │   │   └── case-studies-summary.md
│   │   │
│   │   └── feedback/
│   │       ├── summary.md
│   │       ├── response.md
│   │       └── AI in Leadership and PM - Feedback Report.xlsx
│   │
│   ├── handouts/                     ← Student TAKE-HOME materials
│   │   ├── frameworks-simple/        ← Simplified framework summaries
│   │   │   ├── crisis-response-simple.qmd
│   │   │   ├── scale-pivot-kill-simple.qmd
│   │   │   └── project-scoping-simple.qmd
│   │   │
│   │   ├── company-overview.qmd      ← RetailFlow background
│   │   ├── references.qmd            ← Key resources
│   │   ├── scale-pivot-kill-matrix.qmd
│   │   └── stakeholder-mapping-template.qmd
│   │
│   ├── content/                      ← Slides and presentations
│   │   └── slides-deck.qmd
│   │
│   ├── pre-readings/                 ← Pre-course materials
│   │   ├── what-is-ai.qmd
│   │   └── what-are-llms.qmd
│   │
│   ├── retailflow-site/              ← Company simulation website
│   │   ├── index.html               ← RetailFlow homepage
│   │   ├── about.html               ← Company info
│   │   ├── shop.html                ← Product catalog
│   │   ├── customer-service.html    ← Support page
│   │   ├── staff.html               ← Leadership team
│   │   └── internal.html            ← Password-protected pilot dashboard
│   │
│   └── scripts/                      ← Build and utility scripts
│       └── render-all.sh            ← Renders all .qmd to HTML/PDF
│
├── RENDERED OUTPUT (Generated - don't edit directly)
│   └── docs/                         ← Website files (GitHub Pages)
│       ├── index.html               ← Main companion site
│       ├── instructor.html          ← Password-protected instructor portal
│       ├── activities/              ← Rendered cards, cases (HTML/PDF)
│       ├── handouts/                ← Rendered frameworks, templates
│       ├── content/                 ← Slides (HTML/PDF/PPTX)
│       ├── pre-readings/            ← Pre-course reading pages
│       └── instructor/              ← Rendered instructor materials
│           ├── facilitator-quick-reference.html
│           ├── activity-1-facilitation-guide.html
│           ├── activity-2-facilitation-guide.html
│           ├── activity-3-facilitation-guide.html
│           └── activity-4-facilitation-guide.html
│
└── DOCUMENTATION
    ├── README.md                     ← Project overview & quick start
    └── PROJECT_STRUCTURE.md          ← This file
```

---

## Detailed Folder Descriptions

### `/activities/materials/` - Materials Used IN Activities

**Purpose:** The "props" students use during exercises

**Who uses it:** Students (during class)

**What's in it:**
- **case-briefs/** - Scenario descriptions that set up each activity
- **constraint-cards/** - Planning challenge cards for Activity 1 (Pilot Scoping)
- **crisis-cards/** - Crisis scenario cards for Activity 3 (Crisis Management)
- **role-cards/** - Stakeholder perspective cards for Activity 2 (Speed Dating)
- **pilot-data/** - Pilot metrics dashboard for Activity 4 (Scale/Pivot/Kill)

**When it's used:**
- Activity 1: Pilot scoping → case-briefs, constraint-cards
- Activity 2: Speed dating → role-cards
- Activity 3: Crisis management → crisis-cards
- Activity 4: Scale/Pivot/Kill → pilot-data

**Example flow:**
```
Activity 1: Pilot Scoping
├── Case brief: pilot_scoping_case.qmd
├── Constraint card: budget-cut.qmd (random card dealt to group)
└── Output: Pilot plan with success criteria
```

---

### `/instructor-materials/` - Facilitation Guides (Organized by Activity)

**Purpose:** Detailed teaching notes on HOW to run activities

**Who uses it:** Instructors only (not shared with students)

**What's in it:**

**Root level:**
- `README.qmd` - Master instructor guide with prep checklist
- `facilitator-quick-reference.qmd` - Day-of cheat sheet (PRINT THIS!)
- `feedback/` - Pilot delivery feedback and improvements

**Activity folders:**
- **activity-1-pilot-scoping/**
  - facilitation-guide.qmd - Staff answers, debrief strategy
  - constraint-cards-interactive.qmd - How to use constraint cards

- **activity-2-speed-dating/**
  - facilitation-guide.qmd - Stakeholder role breakdowns
  - stakeholder-cards-interactive.qmd - Role cards with notes

- **activity-3-crisis-management/**
  - facilitation-guide.qmd - Master guide for all crises
  - framework-walkthrough-crisis-1/2/3.qmd - Step-by-step DDCD application
  - crisis-walkthroughs/ - Alternative format teaching notes

- **activity-4-scale-pivot-kill/**
  - facilitation-guide.qmd - Core guide
  - facilitation-guide-detailed.qmd - Extended version
  - debrief-outline.qmd - Quick reference for key questions
  - decision-framework-reference.qmd - Verbose version (instructor only)
  - case-studies-summary.md - Real-world examples

**When it's used:** During activity preparation and live facilitation

**Example usage:**
```
Before Activity 3:
→ Read: activity-3-crisis-management/facilitation-guide.qmd
→ Review: framework-walkthrough-crisis-1.qmd
→ Prepare guiding questions
→ Know expected answers

During Activity 3:
→ Reference facilitation guide on tablet
→ Use guiding questions when groups stuck
→ Check sample answers for quality benchmarks
```

**Access methods:**
1. **Via files:** Navigate to `/instructor-materials/` folder
2. **Via website:** Click "🔐 Instructor" in companion site (password: `instructor2025`)

---

### `/handouts/` - Student Take-Home Materials

**Purpose:** Reference materials students keep after the course

**Who uses it:** Students (before, during, and after class)

**What's in it:**
- **frameworks-simple/** - One-page framework summaries
- **Templates** - Worksheets they fill out (stakeholder mapping, decision matrices)
- **References** - Key resources to explore post-course
- **Company overview** - RetailFlow background (context for exercises)

**When it's used:**
- Before class: Pre-reading materials
- During class: Quick reference during activities
- After class: Apply frameworks to real projects

**Key principle:** Handouts are CONCISE (1-2 pages)
- Detailed versions stay in instructor-materials/
- Students get simplified, actionable versions

**Example:**
```
Student version (1 page):
  handouts/frameworks-simple/crisis-response-simple.qmd

Instructor version (detailed, 50+ pages):
  instructor-materials/activity-3-crisis-management/facilitation-guide.qmd
```

---

### `/docs/` - Rendered Website Files

**Purpose:** Generated HTML/PDF files for GitHub Pages website

**Who uses it:** Students and instructors (accessing via website)

**What's in it:** Rendered versions of all source files

**IMPORTANT RULES:**
1. **Never edit files in docs/ directly** - they're auto-generated
2. **Edit source files** (in activities/, handouts/, content/, instructor-materials/)
3. **Run render script** to regenerate docs/
4. **All files in docs/ are outputs** from the build process

**How it works:**
```
Source file:                     Rendered output:
handouts/references.qmd    →     docs/handouts/references.html
                           →     docs/handouts/references.pdf

instructor-materials/
  activity-1-pilot-scoping/
    facilitation-guide.qmd →     docs/instructor/
                                 activity-1-facilitation-guide.html
```

**Build command:**
```bash
./scripts/render-all.sh
```

This script:
1. Finds all .qmd files in source folders
2. Renders them to HTML + PDF
3. Moves outputs to correct location in docs/
4. Organizes by type (activities/, handouts/, content/, instructor/)

**Website structure:**
- `index.html` - Main companion site with navigation
- `instructor.html` - Password-protected instructor portal
- `activities/` - Student materials (cards, cases)
- `handouts/` - Frameworks and templates
- `content/` - Lecture slides
- `pre-readings/` - Pre-course materials
- `instructor/` - All rendered instructor materials

---

### `/content/` - Slides & Presentations

**Purpose:** Lecture slides and presentation materials

**What's in it:**
- slides-deck.qmd - Main presentation

**Rendered to:**
- docs/content/slides-deck.html
- docs/content/slides-deck.pdf
- docs/content/slides-deck.pptx

**Access:** Via companion site Resources → Slides

---

### `/pre-readings/` - Pre-Course Materials

**Purpose:** Articles and resources students read before class

**What's in it:**
- what-is-ai.qmd
- what-are-llms.qmd

**Rendered to:** docs/pre-readings/

**Access:** Via companion site Resources → Pre-Readings

---

### `/retailflow-site/` - Company Simulation Website

**Purpose:** Standalone website for RetailFlow (the fictional company)

**What's in it:**
- `index.html` - Company homepage
- `about.html` - Company history and mission
- `shop.html` - Product catalog
- `customer-service.html` - Support page (shows AI chatbot)
- `staff.html` - Leadership team bios
- `internal.html` - Password-protected pilot dashboard (password: `pilot2024`)

**Hosted separately** (linked from main companion site)

**Why separate:** Provides immersive context - students can "visit" the company, see the team, explore products, and access internal pilot data

**Key feature:** Internal portal password gate creates realistic scenario where students must "log in" to access pilot data for Activity 4

---

### `/scripts/` - Build and Utility Scripts

**Purpose:** Automation scripts for rendering and deployment

**What's in it:**
- `render-all.sh` - Main build script that renders all .qmd files

**Usage:**
```bash
./scripts/render-all.sh
```

**What it renders:**
1. Role cards → docs/activities/
2. Constraint cards → docs/activities/
3. Crisis cards → docs/activities/
4. Case briefs → docs/activities/
5. Handouts → docs/handouts/
6. Frameworks → docs/frameworks/ (deprecated, moved to handouts)
7. Activities → docs/activities/
8. Pilot data → docs/handouts/
9. Pre-readings → docs/pre-readings/
10. Content/slides → docs/content/
11. **Instructor materials** → docs/instructor/ (NEW!)

---

## Activity Delivery Map

This shows which materials are used in each activity:

### **Activity 1: Pilot Scoping** (50 min total: 30 min work + 20 min debrief)

**Materials:**
- `/activities/materials/case-briefs/pilot_scoping_case.qmd`
- `/activities/materials/constraint-cards/` (deal random card to each group)
  - budget-cut.qmd
  - scope-creep.qmd
  - timeline-acceleration.qmd
  - vendor-lock-in.qmd

**Instructor guide:**
- `/instructor-materials/activity-1-pilot-scoping/facilitation-guide.qmd`
- `/instructor-materials/activity-1-pilot-scoping/constraint-cards-interactive.qmd`

**Student handouts:**
- `/handouts/frameworks-simple/project-scoping-simple.qmd`
- `/handouts/company-overview.qmd`

---

### **Activity 2: Speed-Dating with Stakeholders** (40 min)

**Materials:**
- `/activities/materials/role-cards/` (all 6 stakeholder cards)
  - 1-data-scientist-ai-engineer.qmd
  - 2-operations-manager.qmd
  - 3-end-user-store-manager.qmd
  - 4-it-security-manager.qmd
  - 5-finance-cfo.qmd
  - 6-executive-sponsor.qmd

**Instructor guide:**
- `/instructor-materials/activity-2-speed-dating/facilitation-guide.qmd`
- `/instructor-materials/activity-2-speed-dating/stakeholder-cards-interactive.qmd`

**Student handouts:**
- `/handouts/stakeholder-mapping-template.qmd`

---

### **Activity 3: Crisis Management** (90 min: 75 min work + 15 min debrief)

**Materials:**
- `/activities/materials/case-briefs/crisis_sim_overview.qmd`
- `/activities/materials/crisis-cards/` (present 3-4 crises)
  - data-quality.qmd
  - team-resistance.qmd
  - executive-pressure.qmd
  - ethical-dilemma.qmd (optional 4th)

**Instructor guide:**
- `/instructor-materials/activity-3-crisis-management/facilitation-guide.qmd`
- `/instructor-materials/activity-3-crisis-management/framework-walkthrough-crisis-1.qmd`
- `/instructor-materials/activity-3-crisis-management/framework-walkthrough-crisis-2.qmd`
- `/instructor-materials/activity-3-crisis-management/framework-walkthrough-crisis-3.qmd`

**Alternative instructor materials:**
- `/instructor-materials/activity-3-crisis-management/crisis-walkthroughs/` (markdown versions)

**Student handouts:**
- `/handouts/frameworks-simple/crisis-response-simple.qmd`

---

### **Activity 4: Scale, Pivot, or Kill?** (45 min)

**Materials:**
- Pilot data dashboard (accessed via RetailFlow internal portal)
  - URL: retailflow.serveur.au/internal
  - Password: `pilot2024`
- Groups' original success criteria from Activity 1

**Instructor guide:**
- `/instructor-materials/activity-4-scale-pivot-kill/facilitation-guide.qmd`
- `/instructor-materials/activity-4-scale-pivot-kill/facilitation-guide-detailed.qmd`
- `/instructor-materials/activity-4-scale-pivot-kill/debrief-outline.qmd`
- `/instructor-materials/activity-4-scale-pivot-kill/decision-framework-reference.qmd`
- `/instructor-materials/activity-4-scale-pivot-kill/case-studies-summary.md`

**Student handouts:**
- `/handouts/frameworks-simple/scale-pivot-kill-simple.qmd`
- `/handouts/scale-pivot-kill-matrix.qmd`

---

## File Naming Conventions

### Activity Materials (in `/activities/materials/`)

**Constraint cards:**
- Format: `[description].qmd` (lowercase, descriptive)
- Examples: `budget-cut.qmd`, `scope-creep.qmd`, `timeline-acceleration.qmd`

**Crisis cards:**
- Format: `[description].qmd` (lowercase, descriptive)
- Examples: `data-quality.qmd`, `team-resistance.qmd`, `executive-pressure.qmd`

**Role cards:**
- Format: `[NUMBER]-[role-name].qmd`
- Examples: `1-data-scientist-ai-engineer.qmd`, `2-operations-manager.qmd`

**Case briefs:**
- Descriptive names: `pilot_scoping_case.qmd`, `crisis_sim_overview.qmd`

### Instructor Materials (in `/instructor-materials/`)

**Activity folders:**
- Format: `activity-[NUMBER]-[name]/`
- Examples: `activity-1-pilot-scoping/`, `activity-3-crisis-management/`

**Facilitation guides:**
- Standard name: `facilitation-guide.qmd` (in each activity folder)

**Framework walkthroughs:**
- Format: `framework-walkthrough-crisis-[NUMBER].qmd`
- Examples: `framework-walkthrough-crisis-1.qmd`

**Supporting materials:**
- Descriptive names: `debrief-outline.qmd`, `decision-framework-reference.qmd`

### Handouts (in `/handouts/`)

**Frameworks:**
- Kept in `/handouts/frameworks-simple/` subfolder
- Format: `[framework-name]-simple.qmd`
- Examples: `crisis-response-simple.qmd`, `scale-pivot-kill-simple.qmd`

**Templates:**
- Descriptive names: `stakeholder-mapping-template.qmd`, `scale-pivot-kill-matrix.qmd`

---

## Source Files vs Output Files

### Rule: **If it's in `/docs/`, it's generated. Don't edit it.**

**Source files** (edit these):
- Anything in `/activities/`, `/handouts/`, `/content/`, `/instructor-materials/`, `/pre-readings/`
- File types: `.qmd`, `.md` (in source folders)

**Output files** (generated by render script):
- Everything in `/docs/`
- File types: `.html`, `.pdf`, `.pptx`, `.docx`

**Workflow:**
1. Edit source file: `handouts/references.qmd`
2. Run render script: `./scripts/render-all.sh`
3. Output appears: `docs/handouts/references.html` and `.pdf`
4. Commit both source and output to git

---

## How to Build the Site

### Quick Build
```bash
cd /Users/michael/Projects/ai-leadership-and-pm
./scripts/render-all.sh
```

### What the render script does:
1. Renders all .qmd files in:
   - activities/materials/role-cards/
   - activities/materials/constraint-cards/
   - activities/materials/crisis-cards/
   - activities/materials/case-briefs/
   - activities/materials/pilot-data/
   - handouts/
   - handouts/frameworks-simple/
   - content/
   - pre-readings/
   - **instructor-materials/** (all activity folders)

2. Moves outputs to:
   - docs/activities/
   - docs/handouts/
   - docs/frameworks/
   - docs/content/
   - docs/pre-readings/
   - **docs/instructor/**

3. Creates organized structure in docs/ folder

### Test the website locally:
```bash
open docs/index.html
```

---

## Website Structure

### Main Companion Site (`docs/index.html`)

**Navigation:**
- Home
- Activities
- Resources ▼
  - Pre-Readings
  - Frameworks
  - Reference Materials
  - Slides
- RetailFlow → (external link)
- 🔐 Instructor (password-protected)

**Sections:**
- Pre-Readings - Pre-course materials
- Activities - Exercise worksheets
- Frameworks - Decision-making tools
- Resources - Reference materials and company overview
- Slides - Lecture presentation

### Instructor Portal (`docs/instructor.html`)

**Password:** `instructor2025`

**Contents:**
- Facilitator Quick Reference (PRINT THIS!)
- Activity 1: Pilot Scoping materials
- Activity 2: Speed-Dating materials
- Activity 3: Crisis Management materials
- Activity 4: Scale/Pivot/Kill materials
- Feedback from previous deliveries

**Access:** Click "🔐 Instructor" in main site navigation

### RetailFlow Website (`retailflow-site/`)

**Main pages:**
- index.html - Homepage
- about.html - Company info
- shop.html - Products
- customer-service.html - Support
- staff.html - Leadership team

**Internal Portal (`internal.html`):**
- Password: `pilot2024`
- Contains: Week 6 pilot data dashboard
- Used in: Activity 4 (Scale/Pivot/Kill decision)

---

## Common Tasks

### Adding a new constraint card
1. Create: `activities/materials/constraint-cards/new-constraint.qmd`
2. Add Quarto YAML header
3. Run: `./scripts/render-all.sh`
4. Check: `docs/activities/new-constraint.html` exists
5. Update: `docs/index.html` to link to it (if needed)

### Adding a new crisis card
1. Create: `activities/materials/crisis-cards/new-crisis.qmd`
2. Add Quarto YAML header
3. Run: `./scripts/render-all.sh`
4. Check: `docs/activities/new-crisis.html` exists
5. Update: `docs/index.html` to link to it (if needed)

### Adding a new handout
1. Create: `handouts/new-template.qmd`
2. Add Quarto YAML header
3. Run: `./scripts/render-all.sh`
4. Check: `docs/handouts/new-template.html` exists
5. Update: `docs/index.html` to link to it (if needed)

### Updating a framework
1. Edit: `handouts/frameworks-simple/crisis-response-simple.qmd`
2. Run: `./scripts/render-all.sh`
3. Check: Output appears in `docs/handouts/`

### Updating slides
1. Edit: `content/slides-deck.qmd`
2. Run: `./scripts/render-all.sh`
3. Check: `docs/content/slides-deck.html`, `.pdf`, `.pptx` updated

### Adding new instructor materials
1. Create file in appropriate activity folder: `instructor-materials/activity-X-name/new-guide.qmd`
2. Run: `./scripts/render-all.sh`
3. Check: Output appears in `docs/instructor/`
4. Update: `docs/instructor.html` to link to it (if it's a new type of material)

---

## Key Principles

1. **Separation of Concerns**
   - Activities = materials used during exercises
   - Instructor materials = how to facilitate (organized by activity)
   - Handouts = what students take home

2. **Student vs Instructor Content**
   - Students get concise (1-2 page) versions
   - Instructors get detailed (10+ page) versions
   - Same content, different detail levels

3. **Source vs Output**
   - Source lives in project root folders
   - Output lives in docs/
   - Never edit docs/ directly

4. **Render Everything**
   - Use `./scripts/render-all.sh` for consistency
   - Don't manually render individual files
   - Ensures all outputs are up-to-date

5. **Password Protection**
   - Instructor portal: `instructor2025`
   - RetailFlow internal: `pilot2024`
   - Client-side only (for convenience, not security)

---

## Questions?

- **"Where do I put a new activity?"** → Instructor guide in `/instructor-materials/activity-X-name/`, materials in `/activities/materials/`
- **"Where do I put a new framework?"** → Simplified version in `/handouts/frameworks-simple/`, detailed in `/instructor-materials/`
- **"Where do I put a new template?"** → `/handouts/`
- **"Can I edit files in docs/?"** → No, they're auto-generated. Edit source files and re-render.
- **"How do I access instructor materials?"** → Via website (click "🔐 Instructor") or via `/instructor-materials/` folder
- **"What's the difference between constraint and crisis cards?"** → Constraints are planning challenges (before pilot), crises are emergencies (during pilot)

---

**Last updated:** October 30, 2024
