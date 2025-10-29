# CRISIS #3: EXECUTIVE PRESSURE
## Detailed Framework Walkthrough for Facilitators

**Purpose:** This guide shows how to apply the **Crisis Response Framework (Diagnose → Decide → Communicate → Document)** to Crisis #3: Executive Pressure. This is a LEADERSHIP crisis—testing your ability to manage up, communicate constraints, and propose alternatives.

---

## THE SCENARIO (Quick Recap)

**Week 4 of Live Pilot:**
- Project is going well:
  - AI accuracy: 88%
  - Customer satisfaction: 82%
  - But cost savings only $15K (you projected $50K by now)
- CEO calls you in, frustrated
- CEO says: "I heard competitors scaled their AI to ALL customer service in 8 weeks. Why are we moving so slowly? I want to expand this to all query types and all customers. Do it in 4 weeks."
- You know expanding that fast will destroy the project
- But the CEO is your boss
- **Time to handle this:** 30 minutes

---

## KEY DIFFERENCE: LEADERSHIP CRISIS vs. TECHNICAL vs. PEOPLE

**Crisis #1 (Data Quality):**
- Problem = Technical (bad data)
- Solution = Fix the data
- Framework focus = Fast diagnosis + clear decision

**Crisis #2 (Team Resistance):**
- Problem = People don't trust/fear job loss
- Solution = Listen, engage, involve
- Framework focus = Deep listening + conversation

**Crisis #3 (Executive Pressure):**
- Problem = Leadership wants speed, you need quality
- Solution = Educate + propose alternatives
- Framework focus = Managing up with data + proposing middle path

**The big insight:** You're not refusing the CEO. You're *educating her on reality* and *proposing a better alternative*.

---

---

## FRAMEWORK APPLICATION: DIAGNOSE → DECIDE → COMMUNICATE → DOCUMENT

---

## STEP 1: DIAGNOSE (5-10 minutes)

**Goal:** Understand what's driving the CEO's demand and what the real constraints are.

---

### A. What's Driving This Demand?

**Ask the group:**
> "The CEO wants to expand to all query types in 4 weeks. What's making her say this?"

**Guide them to recognize multiple drivers:**

| Driver | What It Means |
|--------|---------------|
| **Competitive pressure** | "Competitors are doing it, so we look slow if we don't" |
| **Board pressure** | "The board is watching. The CEO wants to show progress." |
| **Cost pressure** | "We projected $50K savings by now; we're only at $15K. CEO needs ROI numbers." |
| **Impatience** | "We're 4 weeks in. CEO expected faster results." |
| **Misunderstanding** | "CEO thinks 'AI is AI'—doesn't understand the difference between pilot and scale" |

**Your role as facilitator:**
- "What's the REAL pressure behind the demand for 4 weeks?"
- "Is she demanding speed because she's unreasonable, or because the board is demanding it of her?"

**Key insight:** The CEO's demand isn't just ego. It's usually pressure from above or real business concerns. Understand that first.

---

### B. What Are the Real Constraints?

**Ask the group:**
> "The CEO wants to expand in 4 weeks. What would that actually require? What are the real constraints?"

**Guide them to identify:**

**Time constraint:**
- Current scope (30% of queries, 2 query types) took 6-8 weeks
- Full scope (100% of queries, all query types) = exponentially more complex
- 4 weeks = not enough time to design, build, test, train, deploy

**Data constraint:**
- Current model trained on order tracking + returns only
- Expanding to complaints, exceptions, product care = need new training data
- Data cleaning + training = 3-4 weeks minimum
- Testing = 1-2 weeks minimum
- 4 weeks = barely enough for testing alone

**Team constraint:**
- Current team just recovered from data quality crisis (Week 1)
- They're now building confidence in the AI
- Sudden expansion = asking team to learn new scope while supporting current system
- Team burnout risk = high

**Quality constraint:**
- Current accuracy 88% (good for routine queries)
- Expanding to complex queries (complaints, exceptions) = likely accuracy drops to 70-75%
- Shipping lower-quality system = new crisis

**Your role:**
- "What happens if we try to do this in 4 weeks and something breaks in production?"
- "Who bears the cost of that failure?"

**Key insight:** Every "constraint" is actually a hidden risk. Speed + quality + scope = pick 2. You can't have all 3.

---

### C. What's the Real Question?

**Ask the group:**
> "The CEO asked: 'Do it in 4 weeks.' But what is she REALLY asking?"

**Help them reframe:**

**Surface question:** "Can we expand in 4 weeks?"

**Real question:** "How fast can we show business value without breaking the project?"

**The reframe:** You're not refusing the CEO's question. You're *answering the real question*.

**Your role:**
- "The CEO doesn't want to break the project either. She wants results AND success."
- "Your job is to show her both are possible—just with a different timeline."

---

### D. What Do You Know and Not Know?

**Ask the group:**
> "What facts do you have to work with?"

**Known facts:**
- ✓ Current accuracy: 88%
- ✓ Current scope: 30% of queries (order tracking, returns)
- ✓ Timeline so far: 4 weeks, on track
- ✓ Team is engaged and recovering from crisis
- ✓ CEO needs to show business progress

**Unknown facts:**
- ? Actual cost savings (projected $50K, actual $15K—why?)
- ? What happens to accuracy when we expand to complaints/exceptions
- ? How much data is needed for new query types
- ? Board's actual expectations

**Your role:**
- "You have the tools to show the CEO the real constraints—data."
- "You don't have perfect information, but you have enough to make a recommendation."

**Key insight:** In a crisis, you rarely have perfect information. You work with what you have.

---

### E. Diagnose Summary

**Guide them to summarize:**
> "So what's our diagnosis? What's the real problem we're solving?"

**Expected answer:**
- **Surface problem:** CEO wants fast expansion (4 weeks)
- **Root cause:** Business pressure (board, competitors, ROI)
- **Real constraint:** Expanding too fast = risk of quality degradation
- **Key insight:** This isn't about refusing the CEO. It's about educating her on the trade-off and proposing a better path.

---

---

## STEP 2: DECIDE (5-15 minutes)

**Goal:** Choose between different approaches. This is NOT a simple yes/no decision.

**Critical insight:** You have MORE options than you think.

---

### A. What Are Your Options?

**Ask the group:**
> "The CEO wants 4 weeks. You know that's risky. What are your options?"

**Push them to brainstorm ALL approaches, including uncomfortable ones:**

---

**Option A: SAY NO** (Not Recommended)
- Tell the CEO: "4 weeks is impossible. It won't work."
- Hold the line on your 6-week timeline
- Let the CEO overrule you or accept the delay

**Trade-offs:**
- **Pro:** Protects the project quality
- **Con:** Signals you can't work with leadership. Damages relationship. Looks defensive and reactive.

**When to choose:** Only if the CEO's timeline is truly dangerous (which it is, but there's a better way).

---

**Option B: SAY YES & HOPE** (Not Recommended)
- Agree to the 4-week timeline
- Try to make it work
- Hope quality doesn't suffer and problems don't emerge

**Trade-offs:**
- **Pro:** Makes CEO happy short-term
- **Con:** Almost guarantees project failure. When it fails, you're blamed. Team is exhausted.

**When to choose:** Never, in this scenario.

---

**Option C: EDUCATE & PROPOSE COMPROMISE** (Recommended Staff Model)
- Don't say yes or no
- Show the CEO the data on what 4 weeks actually means
- Propose a hybrid: Expand faster than original plan, but not in 4 weeks
- Example: "Expand to returns policy in week 6 (faster), then full scale by week 14 (controlled)"
- This gives CEO a win (faster than 8 weeks) without killing the project

**Trade-offs:**
- **Pro:** Addresses CEO's urgency. Shows understanding of business pressure. Proposes middle path.
- **Con:** Takes time to prepare data. Requires confidence in your numbers.

**When to choose:** When you have data to support your position and the CEO is data-driven.

---

**Option D: ESCALATE THE DECISION** (Last Resort)
- Tell CEO: "This is your call. Here's what I recommend and why. If you want to overrule me, I need your decision in writing."
- Let CEO make the call
- Document that you warned them

**Trade-offs:**
- **Pro:** You've done your due diligence. Protects you professionally.
- **Con:** Project likely fails. You have to live with the consequences.

**When to choose:** Only if Option C doesn't work and CEO insists.

---

### B. Evaluate Each Option

**Create a decision matrix:**

| Option | Speed | Risk | Relationship | Long-Term Success |
|--------|-------|------|--------------|-------------------|
| **Say No** | Slow (8 weeks) | Low | Damaged | Medium (project safe, but CEO unhappy) |
| **Say Yes & Hope** | Fast (4 weeks) | VERY HIGH | Good (short-term) | Very Low (project fails in 8-12 weeks) |
| **Educate & Propose Compromise** | Medium (6 weeks) | Medium | Improved (CEO gets faster timeline) | High (project succeeds, CEO wins) |
| **Escalate** | Medium-Slow | Medium-High | Tense | Depends on CEO's choice |

**Your role as facilitator:**
- "Notice Option C gives you the best long-term outcome. Not the fastest, but the most sustainable."
- "Why would a good leader choose Option C over Option B?"

**Staff model:** "Because the CEO's actual goal is business success, not a 4-week deadline. If you show her a path to faster results WITHOUT killing the project, she'll take it."

---

### C. Make the Decision

**Ask the group:**
> "What's your recommendation? How are you going to respond to the CEO?"

**Staff Model Answer (Excellent Leadership):**

> "I'm going to choose **Educate & Propose Compromise**.
>
> Here's why:
> - The CEO's concern is legitimate. We need to show faster results.
> - But I can't just say yes to 4 weeks and hope it works.
> - Instead, I'm going to show her the data on what expansion requires.
> - Then I'm going to propose: Expand to 60% of queries by week 8 (faster than original plan), then full scale by week 14.
> - This gives her a win (6 weeks faster than original) without betting the project.
>
> The key is framing: I'm not saying 'no.' I'm saying 'yes, and here's how we do it right.'"

---

### D. Decision Summary

**Guide them to write down:**
> "Our decision: [OPTION]. Here's what we're going to tell the CEO and why."

**Example:**
> "Our decision: Educate & Propose Compromise. We're going to show the CEO the data on what 4 weeks requires (quality drop, team burn-out, timeline risks). Then we're going to propose: Expand to 60% of queries in 6 weeks, then full scale by week 14. This gives her faster progress without killing the project."

---

---

## STEP 3: COMMUNICATE (10-30 minutes)

**Goal:** Have the conversation with the CEO. This is THE critical step in managing up.

**Important:** How you frame this conversation determines whether CEO sees you as a problem-solver or a blocker.**

---

### A. BEFORE THE CONVERSATION: Prepare Your Data

**What you need ready:**

**Current performance data:**
- Accuracy: 88%
- Satisfaction: 82%
- Timeline: On track (4 weeks done, on schedule)
- Cost per ticket resolved: [calculated from financials]

**Expansion risk data:**
- What expanding to 100% of queries requires:
  - New query types = 4 weeks data + training
  - Testing for new scope = 2 weeks
  - Team training = 1 week
  - Total realistic timeline = 7-8 weeks (not 4)

**Cost of fast expansion:**
- What gets sacrificed if we rush 4 weeks:
  - Quality testing skipped = bugs in production
  - Team training skipped = support failures
  - Data validation skipped = accuracy issues
  - Cost of fixing mistakes = $200K+ (vs. $150K pilot budget)

**Alternative proposal:**
- Week 5-6: Expand to returns policy queries (already partially trained)
- Week 7-8: Expand to product care queries (new data, but not complaints)
- Week 9-14: Full expansion including complaints/exceptions
- By week 8: 60% of queries in AI (faster than original 30% only)
- By week 14: 100% of queries in AI (controlled growth)

**Your role:**
- "Go in with numbers, not opinions."
- "Show, don't tell."

---

### B. THE CONVERSATION WITH THE CEO

**Your opening (not defensive):**

> "I hear the urgency about expanding faster. I've been thinking about this since you brought it up. Let me walk you through what 4 weeks actually requires, then I want to propose something that gets you faster results without the risk."

**Key: You're not refusing. You're educating and proposing.**

---

**STEP 1: Acknowledge Her Concern**

> "I know the board is watching. I know competitors are expanding fast. That pressure is real. Here's what I want to do: Get you faster progress without betting the project."

**Why this works:**
- Shows you understand her position
- Not dismissive
- Frames yourself as ally, not blocker

---

**STEP 2: Show the Data**

> "We're 4 weeks in. 88% accuracy, 82% satisfaction. The current scope is working. Here's what expanding to 100% of queries in 4 weeks requires:
>
> - New query types need new training data (3-4 weeks)
> - Testing the new scope (2 weeks minimum)
> - Team training and support (1-2 weeks)
> - Total realistic timeline = 7-8 weeks
>
> If we compress to 4 weeks, we skip testing, training, or data validation. That's when things break."

**Why this works:**
- Concrete numbers, not vague concerns
- Shows you've thought it through
- Makes the constraint visible

---

**STEP 3: Share the Risk**

> "Here's what I've learned from other companies: When you scale too fast without proper testing, around week 12 you hit a wall. Errors start compounding. Now you've promised the board success and you're scrambling to fix bugs in production affecting thousands of customers. That's worse than a slower scale."

**Why this works:**
- Real-world comparison (not hypothetical)
- Shows long-term thinking
- CEO cares about not looking bad—this helps her not look bad

---

**STEP 4: Propose the Middle Path**

> "Here's what I'm proposing: Let's expand faster than the original plan, but not recklessly.
>
> - **Week 5-6:** Expand to returns policy queries (we know this works, needs minimal new training)
> - **Week 7-8:** Add product care queries (new data, manageable)
> - **Week 9-14:** Add complaints and exceptions
>
> By **week 8, you've expanded to 60% of queries in AI.** That's progress you can show the board. By week 14, you're fully scaled.
>
> This is **6 weeks faster than the original 8-week plan**, but without the risk of fast-track failure."

**Why this works:**
- Addresses her urgency (faster than original)
- Shows progress earlier (week 8, not week 14)
- Mitigates risk (controlled expansion)
- Gives her a win to show the board

---

**STEP 5: Reframe Success**

> "In 6 months, the board will either see 'controlled expansion that succeeded and saved $3M annually' or 'rushed expansion that failed, cost $500K, and we're rolling back.' I'm betting the board prefers option 1.
>
> And you'll be the leader who made the smart call, not the one who got pressured into a mistake."

**Why this works:**
- Long-term thinking (what CEO cares about)
- Makes HER look good (reframes risk as protection of her reputation)
- Clear choice

---

**STEP 6: Ask for Decision**

> "So here's what I'm asking: Can you buy into this plan? Expand faster than original, but controlled. It's more aggressive than my first plan, less aggressive than 4 weeks. It's the middle ground that works."

**Why this works:**
- Asks for a decision, not permission
- Acknowledges this is her call
- Makes her part of the solution

---

### C. If She Pushes Back

**If CEO says:** "But I told the board 4 weeks"

**Your response (respectful boundary):**
> "I understand. Here's what I recommend you tell the board: 'We've been testing different timelines. Our analysis shows 6 weeks of controlled expansion is safer than 4 weeks of risky expansion. Here's the data: [show accuracy drop, timeline reality]. We can show progress by week 8 and be fully scaled by week 14. This protects our investment and ensures success.'"

**Why this works:**
- Gives her language to explain to the board
- Makes HER the smart leader protecting the company
- Shows you're helping her manage up too

---

**If CEO says:** "Just make it work. I need 4 weeks."

**Your response (clear boundary, but respectful):**
> "CEO, I understand. I want to be clear: If we do this in 4 weeks and it fails in production, that's on me as PM. I'm not comfortable with that risk.
>
> What I AM comfortable with is [propose your middle path]. This is my professional recommendation based on the data.
>
> If you want to overrule this and go with 4 weeks, that's your call—but I need your decision documented and I'm going to need some support when things get complicated.
>
> What would you like to do?"

**Why this works:**
- You're not refusing. You're setting a professional boundary.
- Making her responsible for the decision (she can't blame you later)
- Still offering the compromise
- Respectful but firm

**Key insight:** Sometimes you have to be willing to walk away to maintain integrity. But offer the compromise first.

---

### D. Communication Summary

**Guide them to summarize:**

> "Who did we talk to, what did we say, and what was the outcome?"

**Answer:**
1. **CEO alone** → Educate on constraints + propose middle path
2. **If CEO agrees** → Great! Move forward with accelerated expansion
3. **If CEO overrules** → Document her decision, prepare for higher risk

---

---

## STEP 4: DOCUMENT (5-10 minutes)

**Goal:** Record the decision and reasoning so future projects don't repeat mistakes.

---

### A. What Happened?

**What to record:**
- **Date:** Week 4 of pilot
- **What CEO demanded:** Expansion to 100% of queries in 4 weeks
- **Why she demanded it:** Board pressure, competitive pressure, ROI expectations
- **Your recommendation:** Expansion to 60% by week 8, 100% by week 14
- **CEO's response:** Agreed / Overruled / Compromised

**Document template:**
```
EXECUTIVE PRESSURE INCIDENT

Date: Week 4 of Pilot
Demand: Expand to 100% of queries in 4 weeks
Driver: Board pressure, competitive pressure, ROI targets
Your Recommendation: Controlled expansion (60% by week 8, 100% by week 14)
CEO Response: [Agreed / Overruled / Compromised]
```

---

### B. Root Cause Analysis

**What to record:**
- **Why was there pressure?** Board expectations, competitive landscape, ROI timeline
- **Why did the CEO ask?** She's under pressure from above
- **Why didn't you anticipate this?** Didn't manage expectations proactively early in the pilot
- **What could have prevented this?** Weekly updates to CEO showing progress and realistic timelines

**Document template:**
```
ROOT CAUSE ANALYSIS:

Immediate Cause: CEO under board pressure to show AI results
Deeper Cause: We didn't manage CEO expectations proactively
Systemic Cause: Lack of regular communication with leadership during pilot

Prevention: For next projects, brief executive sponsor weekly with:
- Current metrics
- Progress toward milestones
- Risks and timeline realities
- When pressure comes, CEO is already prepared
```

---

### C. The Decision

**What to record:**
- **Decision:** Proposed middle path expansion (60% week 8, 100% week 14)
- **Why this option:** Balances urgency with quality
- **Trade-offs:** Slower than 4 weeks but faster than 8 weeks
- **CEO's response:** Approved / Rejected

**Document template:**
```
DECISION MADE:

Approach: Accelerated but Controlled Expansion
Timeline: Week 5-6 (returns), Week 7-8 (product care), Week 9-14 (exceptions/complaints)
By Week 8: 60% of queries in AI (faster progress for board)
By Week 14: 100% of queries in AI (controlled growth, quality preserved)

Rationale: Addresses CEO's urgency without sacrificing project quality
Trade-off: 6 weeks slower than CEO's demand, but 6 weeks faster than original plan
CEO Decision: Approved
```

---

### D. The Outcome (To Be Completed Later)

**What you'll document after the expansion:**
- **Did the accelerated timeline work?** Did we actually expand on schedule?
- **What surprised us?** Did accuracy drop? Did team handle it?
- **What was the board's reaction?** Did they accept the controlled expansion?
- **What would we do differently?** Should we have been faster or slower?

**Document template (to fill in after expansion):**
```
OUTCOME:

Timeline Achievement: Week 8 (60% in AI) - On Time / Delayed / Accelerated
Accuracy Impact: Maintained at 85%+ / Dropped to 75% / Other
Team Impact: Engaged / Stressed / Burned out
Board Satisfaction: Approved continued expansion / Demanded faster / Satisfied
```

---

### E. The Learning

**What to record for future projects:**

**Learning #1: Manage Expectations Proactively**
- Don't wait for pressure to appear
- Brief executives weekly with progress + realistic timelines
- When pressure comes, they're already informed

**Learning #2: Have Data Ready**
- When CEO asks for something risky, have numbers showing why
- "I don't have time" loses to "Here's the data"
- Data beats opinion every time

**Learning #3: Propose Alternatives, Not Refusals**
- Don't say "No, we can't do 4 weeks"
- Say "Yes, and here's how we do it right in 6 weeks"
- Give executives a win while protecting the project

**Learning #4: Managing Up = Understanding Their Pressure**
- CEO isn't asking for 4 weeks because she's unreasonable
- She's asking because she's under pressure from the board
- Your job is to help her succeed, not to refuse her

**Document template:**
```
LEARNING FOR FUTURE PROJECTS:

1. PROACTIVE COMMUNICATION
   - Brief executives weekly on progress
   - Share timelines and realities early
   - No surprises = no panic-driven demands

2. DATA-DRIVEN DECISIONS
   - Always have numbers to support your position
   - Show accuracy impact, timeline reality, team capacity
   - Opinions lose to data

3. ALTERNATIVE PROPOSALS
   - Never say "no" without saying "yes, and..."
   - Propose a middle path that addresses urgency
   - Make executives partners, not adversaries

4. UNDERSTAND THE PRESSURE
   - Recognize that leadership pressure comes from above
   - Your job is to help CEO succeed under that pressure
   - Position yourself as problem-solver, not blocker

PROCESS IMPROVEMENTS:
- Weekly executive briefings (not just monthly)
- Built-in timeline buffers (so you can accelerate if needed)
- Risk register shared with leadership (so they understand constraints early)
- Early discussion of scope, timeline, and quality trade-offs
```

---

---

## FACILITATION TIPS FOR GUIDING GROUP DISCUSSION

### During DIAGNOSE Phase:
- **Push on assumptions:** "The CEO wants 4 weeks. Do you think she REALLY wants 4 weeks, or does she want something else?"
- **Separate driver from demand:** "What's making her demand this? Is she unreasonable or is she under pressure?"
- **Make constraints visible:** "What happens if we try 4 weeks? Walk me through the timeline day by day."

### During DECIDE Phase:
- **Test their choice:** "You want to say no. What happens to your relationship with the CEO?"
- **Push on data:** "Do you have numbers to support your position, or are you just hoping it works?"
- **Explore middle ground:** "What's between 'yes, 4 weeks' and 'no, not possible'?"

### During COMMUNICATE Phase:
- **Check the frame:** "Are you refusing the CEO or proposing an alternative? What's the difference?"
- **Practice the conversation:** "Say it out loud. How do you start this conversation without sounding defensive?"
- **Test responses:** "If the CEO pushes back, what's your response? Do you hold the line or compromise?"

### During DOCUMENT Phase:
- **Make it real:** "You're leading another AI project in 2 years. What do you wish you'd documented from this crisis?"
- **Connect to prevention:** "How do you prevent this pressure from happening again?"

---

---

## EXPECTED GOOD vs. POOR RESPONSES

### GREEN FLAGS (Excellent Leadership)
✓ Recognized the CEO is under pressure from above (not just being difficult)
✓ Prepared data showing timeline reality and risks
✓ Proposed a middle path that addressed CEO's urgency
✓ Framed as "Yes, and here's how we do it right" (not "No")
✓ Made CEO a partner in the solution
✓ Set a clear boundary if CEO still insisted on 4 weeks
✓ Documented the decision and reasoning

### RED FLAGS (Poor Leadership)
❌ Just said "No, 4 weeks is impossible"
❌ Got defensive about the demand
❌ Had no data to support their position
❌ Proposed alternatives without understanding CEO's pressure
❌ Made it adversarial (leadership vs. team)
❌ Didn't document anything
❌ Gave in completely without setting boundaries

---

---

## DEBRIEF QUESTIONS TO ASK THE GROUP

After they present their decision, ask these follow-ups:

---

### Question 1: Understanding Pressure
> "Why did the CEO demand 4 weeks? Was she being unreasonable or was she under pressure from above?"

**Expected answer:** "She was under board pressure. Her job is on the line too."

**Why ask:** Testing whether they see the CEO as adversary or as someone with their own constraints.

---

### Question 2: The Frame
> "You chose to propose a middle path instead of saying 'no.' How did that change the conversation?"

**Expected answer:** "It made the CEO a partner instead of making her feel refused. She got a win (faster than 8 weeks) without the risk."

**Why ask:** Testing whether they understand the power of proposing alternatives vs. refusing.

---

### Question 3: The Boundary
> "If the CEO had insisted on 4 weeks despite your recommendation, what would you do?"

**Expected answer:** "Set a clear boundary: 'I'm not comfortable with that risk. If you want to overrule, I need it documented.' Then you follow through."

**Why ask:** Testing whether they understand when to hold firm vs. when to compromise.

---

### Question 4: Proactive Prevention
> "How do you prevent this crisis in the first place?"

**Expected answer:** "Weekly updates to the CEO showing progress, timeline, and realities. If she's informed early, she's less likely to suddenly demand change."

**Why ask:** Testing whether they see this as a one-off crisis or a pattern to prevent.

---

### Question 5: Managing Up
> "What's the difference between 'pushing back on the CEO' and 'managing up'?"

**Expected answer:** "Pushing back = defensive, says 'no.' Managing up = helpful, shows data, proposes alternatives, makes the CEO successful."

**Why ask:** Testing whether they understand their role as helping leadership succeed, not blocking decisions.

---

### Question 6: Comparison to Earlier Crises
> "In Crisis #1, you fixed the data. In Crisis #2, you listened to Sarah. In Crisis #3, you managed the CEO. What's different about each?"

**Expected answer:** "Crisis #1 was technical (fix it). Crisis #2 was people (listen). Crisis #3 was leadership (educate and propose)."

**Why ask:** Testing whether they see the pattern—different crises need different approaches.

---

---

## KEY INSIGHTS FOR CRISIS #3

**This is a LEADERSHIP CRISIS, not a TECHNICAL CRISIS**

The framework still applies (Diagnose → Decide → Communicate → Document), but how it plays out is very different:

| Aspect | Crisis #1 (Technical) | Crisis #2 (People) | Crisis #3 (Leadership) |
|--------|----------------------|-------------------|------------------------|
| **Problem** | System giving wrong answers | Team won't use the system | Executive demanding unrealistic timeline |
| **Root cause** | Bad data | Fear of job loss | Board pressure on CEO |
| **Solution** | Fix the data | Listen and engage | Educate and propose alternatives |
| **Diagnose** | Technical issue | Human fear | Leadership pressure |
| **Decide** | Technical fix | Engagement approach | Propose middle path |
| **Communicate** | Announce to stakeholders | Conversation with Sarah | Conversation with CEO |
| **Timeline** | Hours/days to fix | Weeks to rebuild trust | Days to propose alternative |
| **Success looks like** | System works correctly | Team voluntarily adopts | CEO agrees to accelerated but controlled timeline |

**The big lesson:** *Leadership crises aren't about saying yes or no. They're about understanding the pressure and proposing a path forward that works for everyone.*

---

---

## FOR YOUR FACILITATION

**During the simulation, watch for:**

**Good signs:**
- Group recognizes the CEO is under pressure (not just difficult)
- They gather data before responding
- They propose a middle path (not just refusing)
- They frame as "yes, and" instead of "no"
- They understand managing up ≠ blocking

**Red flags:**
- "We just tell the CEO no, it's not possible"
- "We don't have time to gather data"
- "We refuse unless she agrees to 8 weeks"
- Defensive or adversarial tone
- No understanding of CEO's own constraints

**If group gets stuck:**
- "The CEO isn't trying to break the project. What is she ACTUALLY trying to accomplish?"
- "You have data that shows 4 weeks is risky. How do you present that without sounding defensive?"
- "What would a middle path look like? What could you deliver faster than 8 weeks but slower than 4?"

**After their presentation, use the debrief questions to pull out learning about:**
- Understanding leadership pressure from above
- Proposing alternatives vs. refusing
- When to hold firm and when to compromise
- Preventing pressure through proactive communication
- The difference between managing up and blocking

---

