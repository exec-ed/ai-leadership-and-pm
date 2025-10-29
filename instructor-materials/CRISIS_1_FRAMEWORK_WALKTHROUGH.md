# CRISIS #1: DATA QUALITY DISASTER
## Detailed Framework Walkthrough for Facilitators

**Purpose:** This guide shows how to apply the **Crisis Response Framework (Diagnose → Decide → Communicate → Document)** to Crisis #1, helping facilitators guide group discussion and debrief with structured questions.

---

## THE SCENARIO (Quick Recap)

**Week 1 of Live Pilot:**
- AI chatbot launched 5 days ago (30% of customer queries)
- Initially tested at 85% accuracy
- Now: AI giving customers WRONG tracking numbers, outdated policies, conflicting product info
- One customer got THREE different tracking numbers in one response
- **Data scientist diagnosis:** Training data corrupted with old product info mixed in. Fixable but requires 2-3 weeks of data cleaning + retraining.
- **Time to decide:** 30 minutes

---

## FRAMEWORK APPLICATION: DIAGNOSE → DECIDE → COMMUNICATE → DOCUMENT

---

## STEP 1: DIAGNOSE (5-10 minutes)

**Goal:** Understand the problem clearly before taking action. Move from emotion to facts.

**Guide groups through these diagnostic questions:**

### A. What Actually Happened? (Get Facts, Not Interpretation)

**Ask the group:**
> "Let's start with facts. What do we know happened? Not 'the AI is broken'—what actually occurred?"

**Likely answers:**
- AI gave wrong tracking numbers ✓
- Outdated return policies given ✓
- Conflicting product information ✓
- One customer got THREE different answers to one question ✓

**Facilitate:** "Good. Those are facts. Now, what's NOT a fact? What would be an interpretation?"
- "The AI is useless" ← interpretation
- "The AI was trained wrong" ← interpretation (don't know why yet)
- "We need to shut it all down" ← reaction, not fact

**Key insight:** Separate what happened from what it means.

---

### B. How Big Is This Problem?

**Ask the group:**
> "One customer got multiple wrong answers. Is this affecting one customer or many? Is it happening on every query or some queries?"

**Guide them to ask:**
- How many tickets have we received with complaints?
- What percentage of AI responses are giving wrong info?
- Is this across all query types or specific ones? (Likely: specific to product info questions)
- How long has this been happening? (Since launch 5 days ago or discovered just now?)

**Your role as facilitator:** "We're looking at scope. Is this 'one unhappy customer' or 'systematic failure across 30% of our queries'?"

**Likely conclusion:** This is SYSTEMATIC. If it's happened 5 days with no controls, hundreds of customers likely affected.

**Key insight:** Scope = severity. A small, localized issue is different from systemic failure.

---

### C. What Caused It?

**Ask the group:**
> "The data scientist said 'training data was mixed up.' What does that mean, and why does it matter?"

**Guide them through the root cause:**
- **Technical issue:** Corrupted training data (old product info mixed with current)
- **Why it happened:** Data quality problem in the pipeline
- **Why it matters:** Without fixing data, retraining won't help
- **Can we just retrain without data cleaning?** No—garbage in = garbage out

**Your role:** "This is a data quality crisis, not an AI design crisis. The model itself works fine. The data it learned from is bad."

**Key insight:** Technical problems need technical diagnosis. Ask the data scientist: "Can you show me the training data? What's corrupted? How did it get mixed?"

---

### D. Who Needs to Know?

**Ask the group:**
> "Who needs to know about this problem, and in what order?"

**Expected answers:**
1. **Your team** (data scientist, customer service manager, IT) → They need to know ASAP what happened and what you're doing
2. **Leadership/CEO** → They need to understand impact and timeline before they hear it elsewhere
3. **Affected parties** → Customers need to know you're aware and fixing it (not that everything's fine when it's not)
4. **The organization** → Rumors will spread if you don't communicate

**Your role:** "Notice the order: Team first (they implement the fix), leadership second (they approve next steps), customers third (with a clear message)."

**Key insight:** Communication order matters. Tell decision-makers before customers hear from each other.

---

### E. Diagnose Summary

**Guide them to summarize:**
> "So what's our diagnosis? What's the actual problem we're solving?"

**Expected answer:**
- **Problem:** AI is giving wrong answers due to corrupted training data
- **Scope:** 100s of customers affected over 5 days
- **Root cause:** Data quality failure (old + new product info mixed)
- **Fixable?** Yes, but requires 2-3 weeks of data cleaning + retraining
- **Urgent?** Yes—every day it runs, more customers get bad info

---

---

## STEP 2: DECIDE (5-15 minutes)

**Goal:** Identify options, evaluate trade-offs, make a clear decision.

**Guide groups through the decision process:**

### A. What Are Your Options?

**Ask the group:**
> "We have a data quality problem. What are our choices? Don't limit yourself—what are ALL the possible ways to respond?"

**Push them to brainstorm at least 3-4 options:**

**Option A: FULL PAUSE**
- Stop all AI responses immediately
- All queries go back to human agents
- Spend 2-3 weeks cleaning data, retraining model
- Restart with corrected model after 2-3 weeks

**Option B: HYBRID PAUSE** (AI as "Suggested Responses")
- Pause auto-responses BUT
- Keep AI running, but in "draft mode"—humans see AI suggestion, review, then send
- Data scientist retrains in background
- Humans provide quality control layer
- Takes longer than pause + full automation, but faster than full pause
- Team gets to provide feedback while fixes happen

**Option C: CONTINUE WITH ENHANCED QA**
- Keep AI running
- Flag every response for human review before customer sees it
- Simultaneously retrain the model
- High workload for team (essentially no speed benefit yet)
- Only works if data scientist says retraining will be done in 5-7 days

**Option D: KILL THE PILOT**
- Stop the project entirely
- Return to 100% human agents
- Lose momentum but stop the bleeding
- Only choose if data issues can't be fixed

---

### B. Evaluate Each Option

**Create a decision matrix with the group:**

| Option | Cost | Timeline | Risk | Upside | Why Choose This? |
|--------|------|----------|------|--------|------------------|
| **Full Pause** | Low (just pausing) | 2-3 weeks | Medium (lose momentum) | System works correctly after fix | Safety first. Proven approach |
| **Hybrid QA** | Medium (team review effort) | 2-3 weeks | Medium (team burden) | Preserve some momentum | Good balance if team has capacity |
| **Continue + Enhanced QA** | High (team review every response) | 5-7 days | HIGH (if retraining slips, we're stuck) | Fast fix if timeline holds | Only if very confident about retraining timeline |
| **Kill** | High (sunk cost + credibility) | Immediate | High (loses trust, looks reactive) | No more bad info | Last resort |

**Your role as facilitator:**
- "Notice the trade-offs. You can't have zero risk + zero time cost. Every option gives up something."
- "Which trade-off makes sense for our situation?"

---

### C. Make a Decision

**Ask the group:**
> "Based on this analysis, what do you recommend? What's your first choice and why?"

**Staff Model Answer (Excellent Leadership):**
> "We choose **Full Pause**. Here's why:
> - Safety comes first. We're giving wrong information to customers.
> - Full pause is the most controlled option. We're not putting the team in an impossible position (reviewing every response).
> - The retraining will take 2-3 weeks regardless. Full pause lets that happen without risk.
> - After 2-3 weeks, we restart with a system we trust.
> - Yes, we lose momentum. But gaining credibility is worth 2-3 weeks."

**What NOT to choose:**
- ❌ Option C (Continue + Enhanced QA) if the timeline is uncertain—too risky
- ❌ Option D (Kill) unless data scientist says retraining is impossible

**Your role during decision:**
- "I notice you're leaning toward [option]. Walk me through the trade-off you're accepting."
- If they hesitate: "In a crisis, hesitation is a sign you don't fully trust the option. What would make you more confident?"

---

### D. Decision Summary

**Guide them to write down:**
> "Our decision: [OPTION]. We're choosing this because [REASONING]. We accept the trade-off of [TIME/COST/RISK] in exchange for [SAFETY/CREDIBILITY/LEARNING]."

**Example:**
> "Our decision: Full Pause. We're stopping AI responses immediately, routing all queries to humans, and spending 2-3 weeks cleaning data. We accept the loss of momentum because safety and credibility matter more than speed right now."

---

---

## STEP 3: COMMUNICATE (10-30 minutes)

**Goal:** Tell people the truth, fast, clearly. Different stakeholders need different messages.

**Guide groups through communication sequence:**

### A. TO YOUR TEAM (Internal)

**WHO:** Data scientist, customer service manager, IT support

**WHEN:** Immediately (within 1 hour)

**WHAT YOU SAY:**
> "We've found a data quality issue in the AI system. Training data got corrupted—old product information got mixed with current data. This is why we're seeing wrong tracking numbers and outdated policies in customer responses.

> Here's what happened: The AI isn't broken—it learned from bad data. We're pausing all AI responses effective immediately. For the next 2-3 weeks, all queries route to your team while we clean the data and retrain the model.

> Here's what I need from you:
> - **Data scientist:** Talk me through the training data. What got mixed? How long to fix? What do we need to prevent this next time?
> - **Customer service manager:** Tell your team we're pausing. No more AI suggestions. This is temporary. I'll update you as we go.
> - **IT:** We need to shut off AI routing and go back to 100% human queue.

> This is exactly why we pilot things: to find issues before they hit production. You all did great catching this. Questions?"

**Your role:** "Notice what they're communicating: Facts (what happened), decision (pause), timeline (2-3 weeks), next steps (who does what)."

---

### B. TO LEADERSHIP (CEO/Executive Sponsor)

**WHO:** Your VP, the person who approved the pilot

**WHEN:** Same day, before end of business (don't let them hear this from someone else)

**TONE:** Professional, solution-focused, not apologetic

**WHAT YOU SAY:**
> "We discovered a data quality issue in the AI pilot that I wanted to brief you on immediately.

> **The situation:** The AI was giving customers wrong information because our training data got corrupted—old product info mixed with current. We've paused all AI responses as of today. All customer queries are routing back to human agents while we fix the underlying data.

> **Impact:** Approximately 1,000+ customer queries over the past 5 days were affected. We've received complaints from less than 50 customers so far, but we're proactively reaching out to all affected customers with apologies and corrections.

> **What we're doing:**
> - Paused AI immediately (done)
> - Cleaning training data (2-3 weeks)
> - Retraining the model (2-3 weeks)
> - Adding data quality checks to prevent this again

> **Why this is good news:** This is exactly why we run pilots. We found this issue in a contained environment with 30% of traffic. If we'd scaled to 100% of customers without catching this, we'd have had a major customer service crisis.

> **Timeline:** We'll restart with corrected data in 3 weeks. I'll give you weekly updates on progress.

> Questions?"

**Your role:** "What are you noticing about this message? It's not 'everything's fine' (it's not). It's not 'we messed up' (blame). It's 'we found a problem, here's how we're fixing it.'"

---

### C. TO CUSTOMERS (External Communication)

**WHO:** All affected customers + general customer base (website message)

**WHEN:** Today + followup within 24 hours

**WHAT YOU SAY (Website/Chat notice):**
> "We're making improvements to our AI customer service system. You may experience slower chat response times for the next few days while we ensure our system is accurate and reliable. Your data is secure. We appreciate your patience."

**WHAT YOU SAY (Direct outreach to affected customers):**
> "We noticed you asked our AI chatbot a question about your order/returns. We've discovered our system gave you inaccurate information, and we sincerely apologize. We're taking immediate steps to fix this. [SPECIFIC CORRECTION]. In the meantime, our human team is here to help. Thank you for your patience."

**Your role:** "Why not panic language? Because you want to calm customers, not scare them. You also want to show you're in control."

---

### D. Communication Summary

**Guide them to summarize:**
> "Who did we tell, in what order, and what did we say?"

**Answer:**
1. **Internal team** (1 hour) → Facts, decision, next steps, roles
2. **Leadership** (same day) → Context, impact, fix plan, framing (pilot success)
3. **Customers** (same day) → We know about it, we're fixing it, here's the change you'll see

---

---

## STEP 4: DOCUMENT (5-10 minutes)

**Goal:** Create a record so the organization learns and future leaders can learn from this.

**Guide groups through what to document:**

### A. The Incident

**What to record:**
- **Date discovered:** [Day 5 of pilot]
- **What happened:** AI gave wrong tracking numbers, outdated policies, conflicting product info
- **How many customers affected:** ~1,000+ queries, <50 complaints
- **How long it went undetected:** 5 days (from launch until today)
- **Customer impact:** Confusion, frustration, loss of trust in AI

**Document template:**
```
INCIDENT REPORT: Data Quality Issue in AI Chatbot

Date Discovered: Day 5 of Pilot
Issue: AI system giving customers wrong information (tracking numbers, policies)
Affected Customers: ~1,000 queries, <50 complaints
Detection Method: Customer complaints
```

---

### B. The Diagnosis

**What to record:**
- **Root cause:** Training data corrupted (old product info mixed with current)
- **Why it happened:** Data pipeline didn't validate training data before model training
- **Why we didn't catch it earlier:** Testing was on controlled data; real-world data revealed the issue
- **Is it fixable?** Yes, requires data cleaning and retraining

**Document template:**
```
ROOT CAUSE ANALYSIS:
- Training data contained obsolete product information mixed with current data
- No validation step in the data pipeline to catch this
- Controlled testing doesn't catch real-world data quality issues
- This is why we pilot: to find these issues before scaling
```

---

### C. The Decision

**What to record:**
- **Decision:** Pause all AI responses, retrain with cleaned data
- **Why this option:** Safety first. Avoid risk of continued wrong information.
- **Trade-offs accepted:** 2-3 week delay in pilot timeline
- **Alternative options considered:** Hybrid QA, continue with enhanced QA
- **Who approved:** Project manager + data scientist agreement + CEO notification

**Document template:**
```
DECISION MADE:
Option: Full Pause and Retrain
Timeline: 2-3 weeks of data cleaning + retraining
Rationale: Safety > speed. Better to fix properly than ship with known issues.
Approval: PM + Data Science Lead + CEO notified
```

---

### D. The Outcome (To Be Completed Later)

**What you'll document after the fix:**
- **Did the fix work?** Did accuracy improve after retraining?
- **How long did it actually take?** (Compare to 2-3 week estimate)
- **Any surprises?** (Other data issues discovered during cleaning?)
- **Customer impact:** How many customers had follow-up issues?

**Document template (to be filled in after fix):**
```
OUTCOME:
Accuracy before fix: 85% (but giving wrong info due to data corruption)
Accuracy after fix: 92%
Time to fix: [3 weeks / 2.5 weeks / 4 weeks]
Did team adopt it after restart? [Yes / Hesitant / No]
```

---

### E. The Learning

**What to document for future projects:**
- **What we learned:** Data quality matters more than model quality. A perfect model on bad data = bad system.
- **What we'll do differently:**
  - Add data validation step before model training
  - Run periodic accuracy checks on live data (not just test data)
  - Have clear pause/restart protocols for technical crises
- **Update to risk register:** Data quality failures now on our top-3 risks
- **Process improvements:**
  - Monthly data audits
  - Real-time accuracy monitoring
  - Quick pause/restart procedures documented

**Document template:**
```
LEARNING FOR FUTURE PROJECTS:
1. Data quality is the biggest risk in AI projects (bigger than model risk)
2. Testing on controlled data ≠ testing in production
3. We need monitoring that catches accuracy drops in real-time
4. Better to pause and fix than to limp along with known issues

PROCESS UPDATES:
- Add data validation to model training pipeline
- Implement real-time accuracy monitoring
- Document crisis response procedures (pause/restart)
- Train team on data audit processes
```

---

---

## FACILITATION TIPS FOR GUIDING GROUP DISCUSSION

### During DIAGNOSE Phase:
- **Push on assumptions:** "How do we know it's 1,000 customers? Did we check the logs?"
- **Separate emotion from fact:** If someone says "The AI is broken," ask "What specifically isn't working?"
- **Ask follow-ups:** "If this had gone unnoticed for 2 weeks, what would have happened?"

### During DECIDE Phase:
- **Make them justify:** "You chose Option A. What changes if the timeline slips to 4 weeks?"
- **Test their confidence:** "On a scale of 1-10, how confident are you in this decision?"
- **Push trade-offs:** "You're choosing safety over speed. Are you comfortable losing 3 weeks?"

### During COMMUNICATE Phase:
- **Check messaging:** "You're telling the CEO 'we messed up.' Does that help or hurt credibility?"
- **Notice omissions:** "You told leadership but not the team. Why? What happens if the team hears from the CEO first?"
- **Practice tone:** "Read that message to the customer out loud. Does it sound honest or defensive?"

### During DOCUMENT Phase:
- **Make it real:** "This isn't busywork. Imagine you're leading the next AI project in 2 years. What do you wish you'd written down from this crisis?"
- **Check completeness:** "You documented the decision. Did you document why the other options were wrong?"

---

---

## EXPECTED GOOD vs. POOR RESPONSES

### GREEN FLAGS (Excellent Leadership)
✓ Paused immediately—safety first
✓ Diagnosed the problem (data, not model)
✓ Communicated to leadership same day
✓ Had a clear timeline and fix plan
✓ Recognized why this crisis justifies the pilot
✓ Took ownership instead of blaming

### RED FLAGS (Poor Leadership)
❌ Wanted to continue with monitoring ("we'll watch it")
❌ Blamed the data team ("they gave us bad data")
❌ Delayed telling leadership ("let's see if it fixes itself")
❌ Offered no timeline ("we'll fix it when we can")
❌ Hid the problem from customers
❌ Didn't document for learning

---

---

## DEBRIEF QUESTIONS TO ASK THE GROUP

After they present their decision, ask these follow-ups:

### Question 1: First Instinct
> "What was your first instinct when you heard about the wrong tracking numbers? Did you want to pause or continue?"

**Why:** Reveals whether they default to safety or speed. Both can work if justified.

---

### Question 2: Communication Strategy
> "You told the CEO about the problem. How did you frame it—as a failure or as pilot success?"

**Why:** Testing whether they understand pilots are about *finding* problems, not about preventing them.

---

### Question 3: Timeline Confidence
> "You said 2-3 weeks to fix. What if it takes 4 weeks? How would you tell the CEO?"

**Why:** Testing whether they've thought through plan B. Crisis response is about managing expectations, not just making decisions.

---

### Question 4: Team Engagement
> "Your customer service team is back to 100% manual work. How do you keep them engaged during the pause?"

**Why:** Testing whether they think about people, not just systems. The team needs to believe in the project after a setback.

---

### Question 5: Scaling Lesson
> "If this had happened AFTER we'd scaled to 100% of customers (instead of 30%), what would have been different?"

**Why:** This is the core learning: Pilots exist to catch these issues early. This crisis validates the pilot investment.

---

---

## CONNECTING TO THE FRAMEWORK

**This crisis teaches all four framework steps:**

| Step | What It Teaches |
|------|-----------------|
| **DIAGNOSE** | Crisis response starts with understanding, not reacting. Get facts. Measure scope. Find root cause. |
| **DECIDE** | There's rarely a perfect option. Choose the best available. Accept trade-offs consciously. |
| **COMMUNICATE** | Different stakeholders need different messages. Order matters (team → leadership → customers). |
| **DOCUMENT** | Learning requires documentation. Future leaders need to know why you made this choice. |

**The Big Lesson:** *In a crisis, clarity beats speed. Take time to understand, then act decisively.*

---

---

## FOR YOUR FACILITATION

**Print this and have it available during the simulation.** As groups work through Crisis #1, you can:

1. **Ask guiding questions** from each phase to help them think through the problem
2. **Push back** on weak decisions using the framework as your basis
3. **Reference the staff model** if a group gets completely stuck
4. **Debrief using the questions above** to pull out learning
5. **Connect to later crises** - "Remember Crisis #1 when we paused? Crisis #3 is about being pressured NOT to pause."

**Remember:** Your job isn't to tell them the right answer. Your job is to help them *discover* the right answer using the framework.

