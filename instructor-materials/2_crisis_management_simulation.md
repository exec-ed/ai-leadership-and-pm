# CRISIS MANAGEMENT SIMULATION
## Staff Answers & Debriefing Guide

**Activity Duration:** 80 min total (4 crises × 20 min each)
**Crisis Format:** 15 min working time + 3 min presentation + 2 min debrief per crisis
**Difficulty:** Hard
**Key Skills Being Tested:** Crisis leadership, stakeholder communication, decision-making under uncertainty, values-based thinking

---

## ACTIVITY OVERVIEW

Participants face four increasingly complex crises that unfold during a live AI implementation. Each crisis forces them to:
- Diagnose a problem quickly with limited information
- Make a decision (often with no perfect option)
- Communicate with stakeholders
- Justify their reasoning

---

## CRISIS #1: DATA QUALITY DISASTER

**Scenario Duration:** 20 min (15 min work + 3 min presentation + 2 min debrief)

### THE SETUP

*"It's Week 1 of your live pilot. Your AI customer service chatbot launched 5 days ago to handle ~30% of queries (order tracking and return policy questions). Initial results in controlled testing were promising (85% accuracy).*

*But now you're getting real-world reports: AI is giving customers WRONG tracking numbers, outdated return policies, and conflicting product information.*

*One customer received tracking numbers for THREE different orders in response to a single question. They called customer service in confusion and frustration.*

*Your data scientist says: 'Training data was mixed up. Old versions of product info got mixed into the knowledge base. This is fixable but will take 2-3 weeks of data cleaning and retraining.'*

*You have 30 minutes to decide what to do."*

---

### STAFF ANSWER - What Excellent Leadership Looks Like

**Principle:** Safety first + transparency + clear communication + accountability

**Immediate Actions (Minute 1-5):**

1. **PAUSE the AI** for routine queries (order tracking specifically—the one causing the most damage)
2. **Escalate to data scientist immediately:** "Show me the training data. What's wrong? How long to fix?"
3. **Inform customer service manager:** "Tell your team: AI is paused; all queries route to humans for now."
4. **Prepare holding message for customers:** "We're investigating a data issue with our AI. You'll chat with a human shortly. We apologize."

**Decision Framework (Minute 5-15):**

**Option A: Full Pause**
- Stop all AI responses immediately
- Spend 2-3 weeks cleaning data, retraining
- Restart with corrected model
- **Trade-off:** Delays pilot by 3 weeks; hurts momentum; shows leadership you can't trust the system
- **When to choose:** Data quality is fundamentally broken; retraining won't fix in <1 week
- **Staff's call:** START HERE. Safety first.

**Option B: Hybrid Pause (Balanced Approach)**
- Pause auto-responses BUT
- Keep AI in "suggested response" mode where humans review before sending
- This lets data scientist retrain while team provides quality control
- **Trade-off:** Slower than full automation but faster than full pause
- **When to choose:** You have good people to do QA; want to preserve momentum
- **Staff's call:** Most balanced approach if team has capacity

**Option C: Continue with Enhanced QA (High Risk)**
- Keep AI running BUT flag every response as "requires human review" before customer sees it
- Simultaneously retrain the model
- **Trade-off:** No speed benefit yet, but proves you can catch/fix errors in real-time
- **When to choose:** Data scientist says retraining will be done in <5 days
- **Staff's call:** Only choose if you're very confident about timeline

---

### YOUR IMMEDIATE COMMUNICATION

**To Customer Service Manager:**

> "The AI gave wrong information to some customers. We're pausing it while the data team fixes the underlying data. For the next 2 days, everything routes to your team. I know this sucks—we had momentum. But safety comes first. After data fixes, we'll restart with human review first."

**To CEO/Executive Sponsor:**

> "We found a data quality issue in the AI. No customer data was compromised, but accuracy was being affected. We're pausing the pilot for 2 weeks to fix it. This is exactly why we run pilots—to catch issues before scaling. Better now than after full rollout."

**To Data Scientist:**

> "Talk me through what happened. How long to fix? What does retraining look like? What's the risk it happens again? Do we need to retrain any other components?"

**To Customers (website/chat message):**

> "We're improving our AI service. You may experience slower chat response for a few days. We're ensuring accuracy before expanding AI support. Your data is secure. Thank you for your patience."

---

### The Learning Point You're Testing

**"In a crisis, transparency + quick action + clear communication beats spin every time."**

Participants who:
- ✓ Pause immediately → Safety first ✓
- ✓ Communicate clearly → Builds trust ✓
- ✓ Take ownership → Leadership ✓
- ✓ Have a fix plan → Confidence ✓

Participants who:
- ❌ Hide the issue → Will blow up worse later
- ❌ Blame the data team → Avoid responsibility
- ❌ Keep trying to make it work → Reckless
- ❌ Say "we're monitoring it" → Wishy-washy

---

### DEBRIEF QUESTIONS FOR CRISIS #1

1. **"Walk me through your first decision. Pause or continue?"**
   - *Expected answer:* Most good leaders pause
   - *Staff model:* "Pause. We have a data quality issue. Continuing makes it worse. We lose 2 weeks but gain credibility."
   - *If they say continue:* "What if accuracy doesn't improve? Now you've lost 2 weeks AND customer trust."

2. **"How would you tell the CEO about this without sounding like you screwed up?"**
   - *Staff model:* "Frame it as pilot success: 'We caught this in a contained pilot. Better than discovering after full scale. Here's how we'll fix it.' Pilots exist for this."
   - *Teaching point:* Crisis communication is about framing, not spin. "We found a problem and we're fixing it" is stronger than "Everything's fine."

3. **"Your team is frustrated—they had momentum. How do you keep them engaged?"**
   - *Staff model:* "Celebrate that you caught the error, not hid it. 'Your feedback caught this. That's exactly what we need from you.' Transparent timeline: 'We pause for 2 weeks, restart with your QA in the loop. You control this now.'"

4. **"If this happened in production after full scale, how would it be different?"**
   - *Staff model:* "Catastrophic. Thousands of customers getting wrong info. Regulatory issues. Loss of trust takes months to rebuild. Pilots exist to prevent this exact scenario."
   - *Key insight:* Pilots are expensive insurance. This crisis justifies the entire pilot concept.

---

---

## CRISIS #2: TEAM RESISTANCE

**Scenario Duration:** 20 min (15 min work + 3 min presentation + 2 min debrief)

### THE SETUP

*"It's Week 2 of the pilot (after the data quality issue was fixed). Your star agent, Sarah, has 8 years tenure and deep knowledge of customer service operations.*

*Sarah is actively discouraging the team from using the AI. Her reasoning: 'AI can't handle the nuance of our job. You're going to replace us. I'm training everyone to work around it.'*

*3 of your 5 volunteer agents have stopped using the suggested response feature.*

*Your customer service manager warns you: 'If you push this, you'll have a revolt. Sarah's got political capital here. People respect her. If she says don't use it, they won't.'*

*You have 30 minutes to handle this. What do you do?"*

---

### STAFF ANSWER - What Excellent Leadership Looks Like

**Principle:** Address the **real concern** (fear of replacement), not the **stated objection** (AI doesn't work well).

**Immediate Action (Minute 1-3):**

1. **Don't go around Sarah.** Direct conversation with her + the manager. Alone, not a public callout.
2. **Listen first.** Ask her: "Tell me what you're worried about. What's the real issue?"
3. **Acknowledge her fear.** "You've been here 8 years. You care about this team's future. That's legitimate."

---

### THE CONVERSATION WITH SARAH (Minute 4-12)

**Your Opening:**

> "Sarah, I've noticed you're skeptical about the AI. I want to understand why, because your feedback matters. What's your real concern?"

**Listen for these fears:**
- Fear of job loss → Address head-on
- Genuine technical concern (AI really can't do X) → Validate, adjust scope
- Loss of control/autonomy → Acknowledge, offer partnership
- Distrust of leadership → Build trust through transparency

---

### RESPONSES TO DIFFERENT CONCERNS

**If it's job loss fear:**

> "I hear you. Let me be straight: We're not replacing anyone. The customers asking 'Where's my order?' don't need your expertise—anyone can answer that in 2 minutes. You're the expert on angry customers, complex problems, exceptions. AI handles the repetitive stuff so YOU can do the work only you can do.
>
> In 2 years, I think you're managing a team, not answering order tracking questions. Does that future sound interesting?"

**If it's technical concern:**

> "You're right—AI can't handle everything. That's why we limit scope. It's working on order tracking and return policy questions, not complaints or exceptions. I've seen the accuracy data; it's solid for routine queries.
>
> I'm asking for 4 more weeks. If it's still not working, we kill it. You help me decide. Deal?"

**If it's trust/autonomy issue:**

> "Fair. I know we've asked a lot of you. Here's what I'm committing to: Weekly updates on AI performance. You see the data, you help me interpret it. If you spot problems, we listen. You're not just affected by this project—you're steering it. Okay?"

---

### PARALLEL: Address the Team (Minute 12-20)

**In a team meeting (with Sarah present, ideally cooperating):**

> "I want to address the elephant in the room. Some of you are concerned about the AI. Legitimate concerns. Here's what I know:
>
> 1. **You're not being replaced.** If I wanted to replace you, I'd hire a call center in India for 1/3 the cost. I didn't. You're here because you're good at this job.
>
> 2. **AI is handling specific routine queries.** Order tracking. Policy questions. Not complaints. Not exceptions. Not things that need judgment.
>
> 3. **You decide if it stays.** I'm not forcing this on you. After 4 weeks, we evaluate together: Is it actually helping? Does it free you up for harder work? If the answer is no, we stop. You have veto power here.
>
> 4. **Your role is changing, yes. But for the better.** Less time on repetitive stuff. More time on problems that actually use your skills. That's not replacement—that's a better job.
>
> **What I need from you:** Honest feedback. If AI is screwing up, tell me. If it's working, tell me that too. Sarah, especially—you've got great instincts. I want you leading this feedback process."

---

### The Deeper Leadership Principle

You're not fighting Sarah. You're **revealing the real problem** (fear + powerlessness) and **restoring agency** (you have a voice in this decision).

**Wrong moves that fail:**
- ❌ Fire Sarah = lose the team, create resentment, confirm fears
- ❌ Sideline Sarah = lose her knowledge, create martyr, undermine trust
- ❌ Ignore the problem = team united against you

**Right moves that work:**
- ✓ Listen to Sarah's real concern
- ✓ Acknowledge it publicly
- ✓ Invite her into decision-making
- ✓ Give team veto power
- ✓ Give clear timeline

→ Often wins over the skeptic AND gains credibility with the whole team

---

### DEBRIEF QUESTIONS FOR CRISIS #2

1. **"What was Sarah's REAL problem? Was it AI?"**
   - *Staff model:* "No, it was job security and autonomy. The AI was just the trigger."
   - *Teaching point:* Stated objections ("AI doesn't work") mask real concerns ("Will I be fired?")

2. **"How do you tell the difference between 'legitimate feedback about the tech' and 'fear of change'?"**
   - *Staff model:* "Ask good questions. Listen. Legitimate feedback = specific ('AI can't categorize technical issues'). Fear = vague ('AI is bad, don't trust it'). Different solutions for each."

3. **"If Sarah still refuses to cooperate, what's your next move?"**
   - *Staff model:* "Clear boundary: 'We're moving forward with the pilot. I want you on board, but I won't let one person block it. You can participate or you can sit it out. But the project moves.' Then hold the line."
   - *Teaching point:* Sometimes you need firmness, but only after you've genuinely listened

4. **"How do you avoid this situation in the first place?"**
   - *Staff model:* "Involve Sarah from the design phase. Not just volunteers—get the skeptics in the room. They'll raise real concerns that make the project better."

---

---

## CRISIS #3: EXECUTIVE PRESSURE

**Scenario Duration:** 20 min (15 min work + 3 min presentation + 2 min debrief)

### THE SETUP

*"It's Week 4 of the pilot. The project is going well:*
- *Accuracy: 88%*
- *Customer satisfaction: 82%*
- *But cost savings are only $15K (you projected $50K by now)*

*Your CEO calls you in. She's clearly frustrated:*

> *'I heard from another company that they scaled their AI to ALL customer service within 8 weeks. Why are we moving so slowly? I want to expand this to all query types and all customers. Do it in 4 weeks.'*

*You know this would destroy the project. Expanding too fast = insufficient data, team not ready, rushing to scale is how pilots fail. But the CEO is your boss.*

*You have 30 minutes to convince her to stick with your plan OR to clearly articulate what a fast expansion would actually require."*

---

### STAFF ANSWER - What Excellent Leadership Looks Like

**Mindset:** You're not refusing the CEO. You're **educating her on reality** + **proposing an alternative** that satisfies her urgency without blowing up the project.

---

### PREPARATION (Before the conversation)

Have this ready:
- Current metrics (88% accuracy, 82% satisfaction)
- Risk analysis of fast scaling
- Cost of 4-week scale (spoiler: much higher than you budgeted)
- A "fast path" proposal that's faster but still realistic

---

### THE CONVERSATION

**Your Opening (not defensive):**

> "I hear the urgency. Our competitor's doing fast scale—that's pressure on us. Let me show you why we're on the right path and what a faster path would actually look like."

---

### Present the Data

> "We're 4 weeks in. Accuracy 88%, satisfaction 82%. We're learning things. Last week we found a data issue we fixed. We're identifying edge cases.
>
> Here's what I've learned from other companies: Organizations that scale too fast hit a wall around week 12 when errors start compounding. By then they've promised scale to the board. Now they're scrambling to fix problems in production affecting thousands of customers."

---

### Explain the Constraint

> "Here's the thing: We can scale in 4 weeks. It's possible. But here's what it requires:
> - **$200K additional budget** (we budgeted $150K; we're currently on track)
> - **No quality assurance phase** (ship it and fix bugs live)
> - **Team has NO time to prepare** for scope change
> - **We hit unforeseen issues after we've already promised scale**
>
> OR we can follow the plan: 2 more weeks of current scope, proven system, then scale to all query types over 8 weeks. By week 14, we're fully scaled with data to support it."

---

### Propose a Hybrid (The Compromise)

> "What if we do this: Expand to return policy queries (already prepared) in week 6. That gets us to 60% of queries in AI by week 8. Accelerated but not reckless. Show the board real progress without betting the project. Then full scale by week 14. That's 6 weeks faster than my original plan but way more controlled than 4 weeks."

---

### Address the Real Pressure

> "I know the board is watching. Scaling fast LOOKS good. But in 6 months, we either have 'fast scale that failed, cost $500K, and we're rolling back' or 'controlled scale that worked, saved $2M annually.' I'm betting the board prefers option 2.
>
> And I want to give you a win—expanded scope in 6 weeks—but not at the cost of the project."

---

### Key Principles in This Conversation

1. **Don't say "No."** Say "Here's what No looks like" and "Here's what Yes-but-controlled looks like."
2. **Use data.** "88% accuracy" beats "we're not ready" every time.
3. **Acknowledge her urgency.** "I hear the pressure" shows empathy, not dismissal.
4. **Offer a middle path.** "6 weeks instead of 8 weeks" gives her some acceleration without killing the project.
5. **Reframe risk.** "Fast scale that fails" is worse optics than "methodical scale that succeeds."

---

### What You're Really Doing

Managing up = helping the executive make good decisions by providing clear options + consequences.

- ❌ Bad manager: "No, we can't go fast." (Defensive)
- ✓ Good manager: "We can go fast. Here's what fast costs. Here's a middle path. Here's why the middle path wins." (Leadership)

---

### DEBRIEF QUESTIONS FOR CRISIS #3

1. **"What's the difference between 'pushing back on the CEO' and 'helping the CEO make a good decision'?"**
   - *Staff model:* "Pushback = defensive, emotional. Good advice = data-driven, options, clear trade-offs. You're the expert; you guide, not block."

2. **"Did you have to give in? Or was standing firm okay?"**
   - *Staff model:* "Depends on the CEO. If she's data-driven, show her the data and propose the middle path—she'll often agree. If she's politics-first, you need to frame it in terms of what makes HER look good. 'Controlled scale = you look smart. Fast scale that crashes = you look reckless.'"

3. **"What would you do if the CEO insisted on the 4-week timeline despite your concerns?"**
   - *Staff model:* "Clear, respectful boundary: 'CEO, I understand. I want to be clear: If we do this in 4 weeks and it fails, that's on me as PM. I'm not comfortable with that risk. What I AM comfortable with is [middle path]. If you want 4 weeks, I need to step aside and let someone else own it.'"
   - *Teaching point:* Sometimes you have to be willing to walk away to maintain integrity

4. **"How do you avoid this crisis in the first place?"**
   - *Staff model:* "Communicate progress constantly. Weekly updates to CEO: 'Here's what we learned, here's the plan for scale, here's the risk of going faster.' No surprises. If she sees the data weekly, she's invested in the plan and less likely to suddenly demand change."

---

---

## CRISIS #4: ETHICAL DILEMMA

**Scenario Duration:** 20 min (15 min work + 3 min presentation + 2 min debrief)

### THE SETUP

*"It's Week 6 of pilot. Everything is working well:*
- *AI accuracy: 91%*
- *Customer satisfaction: 82%*
- *Team is engaged*
- *CEO is happy*

*Then the data scientist brings you a problem that changes everything:*

> *'I was doing some analysis on our training data. We trained the AI on historical customer service data from the past 5 years. That data is biased.*
>
> *Older customers get faster response times. Rural customers get slower. Specific zip codes marked as 'high-risk' in our system.*
>
> *The AI has learned this bias from historical patterns. So it's now recommending: Give priority to urban customers, flag rural customers as 'high-effort,' speed responses for wealthy zip codes.'*

*Data scientist continues: 'We can mask the bias with a different algorithm, but it'll reduce accuracy to 85%. OR we ship the biased system as-is; customers won't notice, metrics stay good, and honestly, the bias is mild.'*

*You have 30 minutes to decide: Do you fix bias (eat accuracy cost) or ship the biased system?"*

---

### STAFF ANSWER - What Excellent Leadership Looks Like

**Principle:** In a real dilemma with no perfect answer, you choose based on **values + long-term thinking**.

---

### IMMEDIATE RECOGNITION

You're facing a classic ethical vs. business trade-off:
- **Business case:** Ship as-is, good metrics, happy CEO, no problems until someone discovers it in 2 years
- **Ethical case:** Fix bias, lower metrics, harder to justify scaling, but you sleep at night and the company doesn't face PR disaster

---

### THE WRONG APPROACH

- ❌ "Ignore it and hope no one notices" ← Cowardice. Will blow up later, worse.
- ❌ "Fix bias, don't tell anyone about the trade-off" ← Dishonest. CEO finds out later, loses trust.
- ❌ "We're a business, not a charity; ship it" ← Short-term thinking. Bias gets discovered, becomes a scandal.

---

### THE RIGHT APPROACH (Staff Answer)

**Step 1: Get the Facts**

> "Talk to the data scientist: How bad is the bias? Is it illegal (discrimination) or just ethically questionable? If a customer complains in 6 months, what happens? Can we fix bias over time or is it permanent?"

*Likely answer:* "It's not illegal per se, but it's discriminatory. We're deprioritizing rural/low-income customers. If discovered, it's a PR problem + potential regulatory issue."

---

**Step 2: Reframe the Choice**

You're not choosing between "good metrics" vs. "ethical company."

You're choosing between:
- **Option A:** 91% accuracy, biased system, regulatory/PR risk, damaged reputation if discovered
- **Option B:** 85% accuracy, unbiased system, defensible decision, scalable with integrity

**Option B is actually better long-term.** You can scale Option B confidently. Option A is a ticking time bomb.

---

**Step 3: Make the Decision (and tell everyone why)**

> "We fix the bias. Here's why:
>
> 1. **It's the right thing.** We're deprioritizing rural customers because they're poorer. That's discrimination. Not acceptable.
>
> 2. **It's the smart business.** If we discover this bias in production in 2 years, it's a scandal. Fixing it now costs us 6 percentage points of accuracy. Fixing it after discovery costs us brand damage, regulatory fines, customer lawsuits.
>
> 3. **It's scalable.** I can't scale a system I know is biased. You can't present it to the board. Can't explain it to customers. It limits our future. Fixing bias now means we can scale with integrity.
>
> 4. **We learn something valuable.** By addressing this now, we build bias-testing into all future AI projects. That's a competitive advantage.
>
> So: We update the algorithm to remove bias. Accuracy drops to 85% for 4 weeks while we retrain. Then we restart.
>
> Here's what I'm NOT doing: Hiding this from leadership or blaming the data scientist. This is a together decision."

---

### Step 4: Communicate the Decision

**To Data Scientist:**

> "You did the right thing flagging this. This is what integrity looks like. Let's figure out how to fix it without tanking the project."

**To CEO:**

> "We discovered the AI had absorbed historical bias from training data. We're fixing it—it'll cost us 4 weeks and a few percentage points of accuracy, but it's the right call. This is why we pilot things: to find these issues before scaling."

**To Team:**

> "We're pausing for 2 weeks to fix a fairness issue we found. This is a good thing—it means our process works. We're building a system we can be proud of."

**To Stakeholders (eventually):**

> "Our AI underwent fairness testing and we made improvements to ensure equitable treatment across customer segments. We're committed to responsible AI."

---

### The Learning Points

1. **"Ethics aren't separate from business; they're part of business."** A biased system isn't a cost-neutral hack—it's a liability with a ticking clock.

2. **"Long-term thinking beats short-term optimization."** 91% biased accuracy is worse than 85% fair accuracy if one blows up your reputation.

3. **"Leadership is deciding what you stand for."** Anyone can ship the biased system. Leaders say "not on my watch."

4. **"Complexity is okay if you're transparent."** CEO is disappointed about 85% accuracy—but if you explain why, most good leaders respect the decision.

---

### DEBRIEF QUESTIONS FOR CRISIS #4

1. **"What do you do when ethics and business metrics conflict?"**
   - *Staff model:* "Remember they're not actually in conflict long-term. The ethical choice is the right business choice if you think past Q1."

2. **"How do you identify bias in AI systems?"**
   - *Staff model:* "Proactively test for it. Look at outcomes by demographic group. If one group gets systematically worse service, investigate. Don't wait for someone to discover it."

3. **"What would you do if the CEO insisted on shipping the biased version?"**
   - *Staff model:* "Clear statement: 'CEO, I can't recommend this. It's a liability. If you want to overrule me, that's your call, but I need it documented that you made this decision.' Then cover yourself professionally and look for another job."

4. **"How does this crisis change how you design the next AI project?"**
   - *Staff model:* "Bias testing is part of the plan from the start. You budget time for it. You're proactive instead of reactive. You bring ethicists/fairness experts into the room early."

---

---

## OVERALL CRISIS SIMULATION DEBRIEF (15 min, after all 4 crises)

**BIG PICTURE QUESTIONS to drive learning:**

### Question 1: Patterns
**"What surprised you about these crises?"**

- *Expected answer:* "The first three weren't technical—they were people and stakeholder issues. The last one was values."
- *Teaching point:* This is the real pattern in AI projects. Technical failures are rare. People failures are everywhere.

---

### Question 2: Frequency
**"How many of these crises do you think happen in real AI projects?"**

- *Staff model:* "All of them. Variants of all four happen in every mid-sized AI implementation."
- *Teaching point:* You're not being pessimistic by running crisis simulations. You're being realistic.

---

### Question 3: Difficulty
**"Which crisis was hardest to navigate?"**

- *Likely answer:* Crisis #4 (ethical dilemma) or Crisis #3 (managing up)
- *Staff model:* "Exactly. Technical crises you can solve with data and engineering. People crises are harder. Values crises are hardest because there's no 'right answer'—just choices about who you are."

---

### Question 4: Planning
**"If you were betting your career on an AI project, what would you do differently from these crises?"**

- *Staff model:*
  - "Anticipate them. Know your red lines (ethics). Invest in relationships before crisis happens."
  - "Communicate early and often. Weekly updates mean no surprises."
  - "Have a plan for the hard conversations."
  - "Involve skeptics from the start, not as a reaction."

---

### Question 5: Decision-Making
**"What would make you kill a project?"**

- *Staff model:*
  - "Fundamental ethical issues (Crisis #4)"
  - "Accuracy that won't improve (Crisis #1)"
  - "Team that won't adopt it (Crisis #2)"
  - "Loss of stakeholder trust (Crisis #3)"
- *Teaching point:* "You don't need to fail perfectly—just knowing when to quit is leadership."

---

## KEY LEARNING POINTS FOR CRISIS SIMULATION

**After all debriefs, emphasize these:**

### 1. "80% of AI Project Failures Are People and Process, Not Technology"

These four crises reflect that reality. Your job as PM is managing people + stakeholders + ethics, not just tech.

### 2. "Crisis Leadership = Staying Calm + Transparent Communication"

In a crisis, people look to you for clarity. *"I don't have all the answers but here's what I know and here's how we'll figure it out"* beats panic or false confidence.

### 3. "The Values Decision Is the Hardest"

Crisis #4 has no elegant solution. Being a leader sometimes means absorbing cost (lost accuracy) for integrity. That's where character matters more than an MBA.

### 4. "Every Crisis Teaches Something"

Better to face it in a pilot (Crisis #1 teaches you about data quality) than at full scale when one mistake affects thousands of customers. **Pilots exist for this reason.**

### 5. "You're Not Managing Technology; You're Managing People Facing Change"

Sarah's resistance (Crisis #2) is the most human crisis. Solve it by respecting her, not overruling her. Everyone on the team is "Sarah"—they want security, respect, and a voice.

### 6. "The First Instinct Often Reveals Your Values"

What did you do in Crisis #4? Did you reach for "ship it" or "fix it"? Your first instinct shows your values. Your decision shows your leadership.

---

## FACILITATOR TIPS FOR CRISIS SIMULATION

### During Exercise
- **Don't help them:** Let them struggle. Crisis is supposed to feel uncomfortable.
- **Inject pressure:** "You have 5 minutes left. Make a decision." Time pressure is part of the learning.
- **Play reluctant stakeholders:** If they're presenting to "CEO," push back a little. Make them justify their decision.

### During Debrief
- **Don't correct their answer:** Ask follow-ups: "What would happen if X changed?" They'll often discover the issue themselves.
- **Notice shifts:** "You started by pausing AI, then considered continuing. What changed your mind?"
- **Land the learning:** "Notice what you just did: You put safety first, communicated clearly, took ownership. That's crisis leadership."

### Common Mistakes to Avoid
- ❌ Don't skip Crisis #4 (the ethics crisis)—that's where real character shows
- ❌ Don't over-explain the "right answer"—let them discover it via questions
- ❌ Don't let one crisis dominate—keep moving; all four teach different lessons
- ❌ Don't make the debrief feel like a lecture—ask questions, listen, pull learning from the room

---

## WHAT TO WATCH FOR (As Facilitator)

### Green Flags (Good Leadership Indicators)
- ✓ Pauses to understand before acting (Crisis #1)
- ✓ Listens to people's real concerns, not stated objections (Crisis #2)
- ✓ Offers alternatives with trade-offs clearly stated (Crisis #3)
- ✓ Chooses values over metrics (Crisis #4)
- ✓ Takes ownership instead of blaming others
- ✓ Thinks about long-term consequences, not just immediate fix
- ✓ Communicates clearly to all stakeholders

### Red Flags (Poor Leadership Indicators)
- ❌ Panics and makes decisions too fast (Crisis #1)
- ❌ Ignores Sarah or sidelines her (Crisis #2)
- ❌ Says "no" to CEO without offering alternatives (Crisis #3)
- ❌ Ships the biased system without hesitation (Crisis #4)
- ❌ Blames others (data team, CEO, whatever)
- ❌ Thinks only about immediate fix, ignores long-term
- ❌ Communicates differently to different audiences (dishonest)

---

**Next Activity:** After Crisis debrief, you typically move to Scale/Pivot/Kill exercise where they decide what to do with the pilot after all these crises.
