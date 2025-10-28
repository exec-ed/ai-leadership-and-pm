# PILOT SCOPING EXERCISE
## Staff Answers & Debriefing Guide

**Activity Duration:** 30 min exercise + 15-20 min debrief
**Difficulty:** Medium
**Key Skill Being Tested:** Constraint thinking, success metrics, risk awareness

---

## STAFF ANSWER - MODEL SOLUTION

This is what an excellent pilot scope looks like. Use this as your standard for what "good" performance means.

### SECTION 1: Pilot Scope Decisions

**Primary Function (What the AI Actually Does):**
- ✓ **Automate responses to SPECIFIC query types only**
- ✓ **Assist human agents with AI-suggested responses**
- ✓ **Automatically triage and route queries**

**Chosen Approach (Hybrid):**

*"Phase 1: AI auto-responds to high-volume, low-complexity queries (order tracking, return policy questions). Phase 2: AI assists agents by suggesting responses they can review/edit before sending. Start with ~40% of current volume (1,000 queries/week)."*

**Rationale:**
- **Why limited scope?** 80% of queries fall into 2-3 categories; targeting these maximizes learning with contained risk
- **Why hybrid approach?** Builds team comfort + demonstrates value before full automation
- **Why 1,000 queries/week?** Large enough to get meaningful data; small enough to manage failures; 6-week sample covers seasonal variation

---

### SECTION 2: Success Metrics

| Metric | Current Baseline | Pilot Target | How We Measure |
|--------|-----------------|--------------|-----------------|
| Response time for tracked queries | 26 hours | 4 hours | Ticketing system logs |
| First contact resolution rate | 61% | 75% | Post-resolution surveys + escalation tracking |
| Customer satisfaction for AI-handled queries | Unknown | ≥80% | Brief 1-question survey after interaction |
| Agent time per query (assisted mode) | 8 min | 5 min | Time tracking in system |
| AI accuracy on routine queries | — | ≥90% | Weekly audits of 5% of AI responses |

**Primary Success Criterion:**

*"Customer satisfaction for AI-handled queries ≥80%. If customers hate it, it doesn't matter if it's fast—we won't scale it."*

---

### SECTION 3: Pilot Boundaries

**IN SCOPE:**
- Query types: Order tracking (35% volume), Return/Refund policy (25% volume)
- Volume: 1,000 queries/week (40% of normal 2,500 weekly volume)
- Duration: 8 weeks (6 weeks live + 2 weeks buffer)
- Team: Full customer service team sees AI; 2 agents volunteer for "assisted mode" testing
- Customers: All customers who query during pilot period (no segmentation by channel initially)

**OUT OF SCOPE:**
1. Product questions requiring detailed knowledge (deferred to Phase 2)
2. Technical support (app/website issues) - too complex for initial AI
3. Complaint escalations & refund exceptions - requires human judgment
4. Phone channel - start with chat/email only

**Why these boundaries?**

*"We need to prove competence before expanding. These two query types are high-volume, well-documented, and low-risk. Excludes scenarios requiring judgment, empathy, or exception handling."*

---

### SECTION 4: Risk Mitigation

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|-----------|
| AI gives incorrect info to customers | Medium | High | Phase 1: All AI responses flagged as "suggested" with human review before send. Weekly accuracy audits. |
| Customer service team resists AI | High | High | Involve team in design (test group volunteers). Frame as "helping you" not "replacing you." Monthly feedback sessions. |
| Customers hate interacting with AI | Medium | Medium | Clear handoff to human if customer requests. "Talk to agent" button always visible. Monitor satisfaction continuously. |
| Budget overrun | Low | High | Lock down vendor pricing upfront. Use open-source tools where possible. Allocate 15% contingency. |
| AI can't handle query complexity | Medium | Medium | Set accuracy threshold at 90%; anything below triggers escalation to human. Build feedback loop into training. |
| Data privacy/security issues | Low | High | Data anonymized in AI model. Queries encrypted in transit/at rest. No customer data leaves our servers. Weekly security review. |

**Top 3 Risks (Detailed Mitigation):**

**Risk #1: Team Resistance**
- Mitigation: Involve customer service manager & 2 volunteer agents from day 1. Position AI as "your research assistant"—handles the repetitive stuff so they focus on hard problems. Show them the time savings. Celebrate early wins visibly.

**Risk #2: AI Accuracy Issues (Bad Customer Experiences)**
- Mitigation: Phase 1 = 100% human review before customer sees response. Set hard floor at 90% accuracy; below that, we pause and retrain. Weekly sample of 50 responses reviewed by manager. Immediate feedback loop to data scientist.

**Risk #3: Executive Pressure to Expand Too Fast**
- Mitigation: Define clear "scale" criteria upfront with CEO. Show weekly progress. Document every escalation. After 4 weeks, present data: "We're at 87% satisfaction on routine queries, 94% on tracking. Ready to add return policy questions but NOT product support yet."

---

### SECTION 5: Resource Allocation

| Category | Allocation | Rationale |
|----------|-----------|-----------|
| AI platform/software | $35,000 | OpenAI API + GPT-4 for 6 months (lower cost than licensing) |
| Implementation/Integration | $40,000 | Consultant 2 days/week × 6 months to integrate with ticketing system & CRM |
| Data preparation | $15,000 | Cleaning 5 years of historical queries, building training set, labeling accuracy |
| Training & change management | $20,000 | 3 full-day workshops for team, monthly lunch-and-learns, 1:1 coaching for resistant agents |
| Testing & quality assurance | $25,000 | Dedicated QA person 0.5 FTE, weekly accuracy audits, customer satisfaction surveys |
| Contingency reserve | $15,000 | 10% buffer for unexpected costs or scope adjustments |
| **TOTAL** | **$150,000** | |

---

### SECTION 5B: Timeline & Milestones

| Month | Key Activities | Success Criteria | Deliverables |
|-------|----------------|-----------------|--------------|
| **Month 1** | Data audit & prep; vendor selection; team kickoff | Historical data clean & labeled; vendor contract signed; team trained on AI basics | Data audit report; vendor SLA; training completion sign-offs |
| **Month 2** | AI model training; integration build; team workshop | Model accuracy ≥85% on test set; integration working in staging; team comfortable with workflow | Model performance report; integration test results; team feedback |
| **Month 3** | Live pilot launch; daily monitoring; weekly reviews | 90% AI accuracy in production; zero critical customer complaints; team confidence growing | Week 1-4 dashboard with metrics; incident log; team survey |
| **Month 4** | Optimize based on real-world data; plan Phase 2 | Sustain 90%+ accuracy; customer satisfaction ≥75%; decision point for expansion | Optimization recommendations; Phase 2 scope document |
| **Month 5** | Phase 2 expansion (return policy queries); scale testing | Expand to 2 query types with same accuracy metrics; identify process improvements | Phase 2 launch report; expanded accuracy metrics |
| **Month 6** | Go/No-Go decision point; full analysis; recommendations | All success metrics met (or documented why not); clear recommendation for scale/pivot/kill | Final business case; scale-up plan or pivot strategy |

---

### SECTION 6: Go/No-Go Decision Criteria

*Evaluated at Month 3 & Month 6*

**✅ SCALE IT (Full Rollout Recommended)**

Criteria:
1. **Satisfaction & Accuracy:** AI customer satisfaction ≥80% AND accuracy ≥92% for handled query types
2. **Team Adoption:** 80%+ of team actively using suggested responses; zero formal grievances; voluntary use extending beyond pilot group
3. **Business Impact:** Cost per query reduced by 40%+ AND response time under 4 hours for 90%+ of queries AND zero escalations due to AI error
4. **Evidence:** 6+ weeks of clean data showing consistent performance; customer feedback predominantly positive; no emerging technical risks

*If all criteria met → Recommend scale to full customer base over 3-month rollout*

---

**🔄 PIVOT IT (Change Approach, Continue Initiative)**

Criteria:
1. **Partial Success:** Accuracy 85-92% OR satisfaction 75-80% (good but not great; suggests we're on right track but approach needs tweaking)
2. **Process Issues, Not Technology:** Problem is integration/workflow, not AI capability (solvable through better process design)
3. **Emerging Opportunity:** Real-world data reveals better use case than originally planned (e.g., "AI is actually better at complaint triage than we expected")

*If met → Pivot to new scope and extend pilot 8 more weeks*

---

**❌ KILL IT (Stop Project)**

Criteria:
1. **Fundamental Failure:** Accuracy stuck below 85% after 6 weeks of optimization attempts OR customer satisfaction below 70%
2. **Team Rejection:** >50% of team actively resists; escalations due to AI errors increase over time; safety concerns emerge
3. **Business Case Broken:** Cost savings don't materialize (>15% overrun) OR response time doesn't improve significantly

*If any criterion met → Stop pilot. Document learnings. Redirect budget to different approach*

---

### SECTION 7: Stakeholder Management

| Stakeholder | Their Main Concern | Your Engagement Strategy | Frequency |
|-------------|-------------------|-------------------------|-----------|
| **CEO** | Will this work? Will it hit the Q4 deadline? Is it worth the investment? | Monthly 15-min updates with 3 key metrics (satisfaction, accuracy, cost savings vs. plan). Frame as "learning fast, de-risking decision." | Monthly |
| **CFO** | Cost overrun? Will we get ROI? | Detailed budget tracker. Monthly cost updates. Show path to $500K annual savings once scaled. "Still within budget." | Monthly |
| **Customer Service Manager** | Will this replace my team? How does it affect morale? | Position as "your assistant, not your replacement." Involve in design. Highlight time savings. Show job security pathway. | Weekly |
| **Customer Service Team** | Am I being replaced? Will this make my job harder? | Training sessions. Celebrate early wins publicly. Share customer feedback. "You're the expert on hard problems; AI handles the tedious stuff." | Weekly lunch-and-learns |
| **IT/Security** | Will this create security/compliance issues? | Share security audit results. Demonstrate data handling protocols. Monthly security review. "No data leaves our servers." | As-needed, + monthly check-in |
| **Customers** | How is my data protected? Will I get bad service? | Transparent communication: "You may chat with AI for order tracking. You can always request a human." Emphasize speed benefit. Monitor feedback continuously. | Continuous (via satisfaction surveys) |

---

## DEBRIEFING STRATEGY FOR PILOT SCOPING

**TIMING:** After exercise, immediately begin 15-20 min debrief while groups finish presenting.

**FORMAT:**
1. **Gallery Walk** (5 min) - Groups post their responses on wall. Everyone reads other groups' answers.
2. **Group Share** (5 min) - 1-2 groups present their scope decisions. Highlight differences in approach.
3. **Facilitated Discussion** (10 min) - Use the debriefing questions below.

---

## KEY DEBRIEFING QUESTIONS

### Question 1: On Scope
**"Why did you choose to automate THESE specific query types? What would happen if you chose differently?"**

- *Purpose:* Tests thinking about risk/value trade-offs
- *Staff model answer:* "35% of volume, simple to handle, low risk of errors. If we chose product questions (20% volume), higher risk of errors. If we chose complaints (5% volume), we learn nothing at scale."
- *What you're listening for:* Do they have rationale beyond gut feeling? Do they understand risk-value trade-offs?

**"How big a pilot is 'big enough'? At what point do you have enough data to make a scale/kill decision?"**

- *Purpose:* Tests understanding of sample size and learning
- *Staff model answer:* "You need enough volume to hit edge cases (6-8 weeks minimum) but not so much that one failure cascades. 1,000 queries/week = good zone. 100 would be too small; 3,000 would be risky."
- *Red flag:* "As big as possible" (too ambitious) or "Very small, like 50 queries" (learn nothing)

---

### Question 2: On Trade-offs
**"You had $150K. What got cut, and why? What would you cut first if budget dropped to $75K?"**

- *Purpose:* Tests constraint thinking and priority-setting
- *Staff model answer:* "Cut contingency first, then testing budget. Must keep data prep and training. Those are foundation."
- *Note:* This leads into the Constraint Card exercise if you're doing that later

**"You set accuracy at 90%. Why not 95%? Why not 80%?"**

- *Purpose:* Tests thinking about realistic vs. aspirational targets
- *Staff model answer:* "90% is practical—catches most issues, allows some escalation. 95% might take 3x longer to achieve. 80% = unacceptable risk."
- *Red flag:* Arbitrary numbers without reasoning

---

### Question 3: On Uncertainty
**"What was your biggest assumption in this plan? What could prove you wrong?"**

- *Purpose:* Tests risk awareness
- *Staff model answer:* "Assumption: Team will embrace AI. Reality check: May face resistance. Mitigation: Involve volunteers, celebrate wins, frame as assistant."
- *What you're listening for:* Do they identify key assumptions? Do they think about how to test them?

**"If you had to bet your career on this plan, what would you change?"**

- *Purpose:* Forces them to surface what they're uncertain about
- *Staff model answer:* "I'd get the customer service manager more involved earlier. They know reality better than our documents."

---

### Question 4: On Go/No-Go
**"At what point would you kill this project? Be honest—when is it 'good enough' vs. 'a waste of money'?"**

- *Purpose:* Tests decision-making clarity
- *Staff model answer:* "Kill if accuracy stays below 85% after 6 weeks. We've learned the approach doesn't work. Sunk cost doesn't matter."
- *Red flag:* "We'd never kill it" (no discipline) or "We'd kill it immediately if anything goes wrong" (no resilience)

**"How would you communicate a kill decision to the CEO?"**

- *Purpose:* Tests stakeholder communication
- *Staff model answer:* "We learned the tech isn't ready for this use case. Better to discover now than after full rollout. Here's what we'll do instead [alternative plan]."

---

## KEY LEARNING POINTS TO EMPHASIZE

**Land these points during or after debrief:**

### 1. "Best pilots are 'Goldilocks'"
Not too ambitious (guaranteed failure), not too timid (learn nothing), but just right (prove value, manage risk).

### 2. "Scope is your most powerful tool"
Good project managers are great at boundary-setting. What you say NO to matters as much as what you say YES to.

### 3. "Success metrics predict outcomes"
If your metrics don't align with what matters to customers + stakeholders, you'll "succeed" on paper and fail in reality.

### 4. "Risk management is stakeholder management"
Your biggest risks aren't technical—they're people. Plan for resistance, budget constraints, and changing priorities.

### 5. "Go/No-Go criteria set you free"
Define these upfront so you can make a kill decision without guilt. You're not failing; you're learning.

### 6. "Scope creep kills more projects than technical issues"
Your scoping document is your shield against "just one more query type."

---

## WHAT TO WATCH FOR (As Facilitator)

### Red Flags During Exercise
- ❌ "Let's automate everything" → Too ambitious; they'll fail
- ❌ "Let's do 10% to be safe" → Too timid; they learn nothing
- ❌ "We'll figure out metrics during the project" → No clear success criteria
- ❌ "All these risks; we'll manage them somehow" → No concrete mitigation

### Green Flags (What Good Looks Like)
- ✓ "40% of queries, 2 query types, 8 weeks" → Good scope
- ✓ "Accuracy 90%, satisfaction 80%" → Good metrics
- ✓ "We'll pause if accuracy stays below 85%" → Clear go/no-go
- ✓ "Team resistance is our top risk; here's how we address it" → Risk awareness

---

## ASSESSMENT RUBRIC

### Strong Performance (9-10)
- Clear boundaries; specific query types; volume clearly defined; realistic timeline
- 3-5 specific, measurable metrics; clear baseline & target; realistic & achievable
- Identifies 6+ risks; realistic likelihood/impact; mitigation plans are specific & actionable
- Maps all key stakeholders; understands their concerns; engagement strategy clear for each

### Good Performance (7-8)
- Scope defined but somewhat vague; query types mentioned but trade-offs unclear
- 3-5 metrics but some are vague; baselines clear; targets maybe ambitious
- Identifies 4-5 key risks; mitigation plans exist but could be more detailed
- Maps 5+ stakeholders; understands concerns; strategy exists but could be more specific

### Needs Development (5-6)
- Scope covers multiple options without clear rationale; unclear volume targets
- <3 metrics or too many; hard to measure; targets unclear
- Identifies 2-3 risks; mitigation plans are generic
- Maps 3-4 stakeholders; limited stakeholder thinking; generic engagement

### Not Yet (< 5)
- Scope is too ambitious or too timid; no clear boundaries
- No clear metrics or unmeasurable goals
- Misses major risks; no real mitigation plans
- Ignores stakeholder management or naive approach

---

## QUICK DEBRIEF FLOW (If Short on Time)

**10-minute debrief version:**
1. Gallery walk (2 min)
2. Ask Question 1 + Question 3 (5 min) - Listen to 1-2 answers each
3. Land the learning: "Best pilots are Goldilocks. You just proved you can think like a PM." (3 min)

**20-minute debrief version:**
1. Gallery walk (3 min)
2. Ask all 4 questions with follow-ups (12 min)
3. Land the learning + transition (5 min)

---

## FACILITATOR TIPS

**Don't answer their questions directly:**
- ❌ Don't say: "That's the right scope size"
- ✓ Do ask back: "Why did you choose that size? What data supports it?"

**Celebrate good thinking:**
- "Notice what you just did: You limited scope, identified the real stakeholder concern, and made a clear decision. That's PM mastery."

**Notice differences between groups:**
- "Interesting—Group A chose 40% volume, Group B chose 60%. Both solid reasoning. What's the trade-off?"

**If a group is stuck:**
- "Start with risk. What's your #1 concern? Build the scope around managing that."
- "What would the CEO ask? Start there."

---

**Next Activity:** If doing Constraint Card exercise, refer back to their budget allocation and mention: "You're about to test whether your plan survives under pressure."
