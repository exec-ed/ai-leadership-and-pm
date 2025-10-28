---
title: "Why AI Projects Fail"
author: Michael Borck
format:
  html:
    embed-resources: true
---


## Executive Summary

AI projects face alarmingly high failure rates, with 70-80% failing to deliver business value according to multiple sources. This brief synthesises findings from Project Management Institute (PMI) and AIMultiple research to identify root causes and provide actionable recommendations for project success.

## Key Statistics

- **70-80% of AI projects fail** to deliver business value (PMI, 2024)
- **85% of AI project failures** are attributed to poor data quality issues (Dilmegani & Ermut, 2025)

*Note: The two primary articles also reference statistics from other sources including S&P Global Market Intelligence (42% abandonment rate), RAND Corporation (80% failure rate, double that of non-AI projects), Carnegie Mellon HCI Institute (90% failure rate), and Forbes (85% cite data quality issues), but these were secondary citations not independently verified for this brief.*

## Critical Failure Factors

### 1. Fundamental Misunderstanding of AI Project Nature

AI projects are fundamentally different from traditional software development. The core of AI lies not in complex coding, but in the data that powers it, requiring a data-centric approach rather than traditional agile methodologies (PMI, 2024).

**Key Issue:** Organizations attempt to run AI projects like application development projects, leading to predictable failures (PMI, 2024).

### 2. Unclear Business Objectives and ROI Misalignment

Companies must first determine and define business problems before deciding whether AI techniques and tools would help solve them, rather than starting from the solution for an indefinite business problem (Dilmegani & Ermut, 2025).

Projects often derail due to vague objectives or misaligned expectations regarding return on investment (ROI) (PMI, 2024). Without clearly defined problems and expected benefits, projects lack direction and measurable success criteria (PMI, 2024).

### 3. Poor Data Quality and Insufficient Data

Data quality emerges as the single most critical factor in AI success or failure (Dilmegani & Ermut, 2025). Working with outdated, insufficient, or biased data can lead to garbage-in-garbage-out situations, failure of the project, and wasting business resources (Dilmegani & Ermut, 2025).

#### Specific Data-Related Failures:

**Overfitting:** AI models become overly specialised in training data and fail to generalise to new inputs, particularly common in deep learning models used in financial fraud detection where the tool may only recognize past fraud patterns and miss emerging tactics (Dilmegani & Ermut, 2025).

**Data Bias:** A well-known example is healthcare AI models trained primarily on data from white patients, leading to inaccurate diagnoses for non-white patients (Dilmegani & Ermut, 2025).

**Data Drift:** AI tools assume data remains consistent over time, but real-world changes such as shifting customer behavior can lead to data drift, requiring AI models used in financial forecasting or legal research to be updated frequently to maintain accuracy (Dilmegani & Ermut, 2025).

**Edge-Case Neglect:** Edge cases, uncommon yet critical scenarios, often lead to AI systems making wrong decisions, such as in autonomous vehicles where an AI chatbot designed for navigation may fail to process unusual driving conditions (Dilmegani & Ermut, 2025).

### 4. Training Data vs. Real-World Data Gap

A common mistake in AI projects is assuming training data is reflective of real-world scenarios, leading to models that perform well in testing but fail in practical applications (PMI, 2024).

Proof of concept (POC) projects often fail to translate into successful real-world applications because the controlled environment of a POC can mask real-world challenges such as data variability and system integration issues (PMI, 2024).

### 5. Lack of Cross-Functional Collaboration

Building a successful AI project requires collaboration between data scientists, data engineers, IT professionals, designers, and line of business professionals (Dilmegani & Ermut, 2025). Having a data science team working in isolation is not a recipe for success (Dilmegani & Ermut, 2025).

Organizations need to ensure the AI project output will be well-integrated into their overall technological architecture and that learnings and best practices are shared across teams (Dilmegani & Ermut, 2025).

### 6. Talent and Skills Shortage

Due to skill shortage, creating a talented data science team can be costly and time-consuming, and without a team with proper training and business domain expertise, companies should not expect to accomplish much with their AI initiative (Dilmegani & Ermut, 2025).

### 7. Resource Underestimation

AI projects are resource-intensive, often requiring significant time and financial investment, with many projects faltering due to underestimating these requirements, particularly around data acquisition and preparation (PMI, 2024).

### 8. Neglecting Ongoing Maintenance

AI models are not static and require continuous updates and maintenance to stay relevant, with many organizations failing to plan for the ongoing iteration of AI models and data, leading to outdated models that no longer perform optimally (PMI, 2024).

## Real-World Failure Examples

### Apple Intelligence's Misleading News Summaries

The BBC lodged a complaint with Apple regarding inaccuracies in Apple's AI-generated news summaries, which erroneously attributed false information to the BBC, including a notification falsely stating that Luigi Mangione had committed suicide (Dilmegani & Ermut, 2025).

### Air Canada Chatbot Failure

Air Canada faced legal trouble after its AI chatbot misinformed a customer about bereavement fare refunds, wrongly stating he could apply for a refund within 90 days of booking, and a tribunal ruled that Air Canada was responsible for all information on its website (Dilmegani & Ermut, 2025).

### IBM Watson for Oncology

Internal IBM documents show that Watson frequently gave erroneous cancer treatment advice, such as prescribing bleeding drugs for a patient with severe bleeding, because Watson's training data contained a small number of hypothetical cancer patient data rather than real patient data, costing M.D. Anderson $62 million without achievement (Dilmegani & Ermut, 2025).

### Amazon's AI Recruiting Tool

Amazon's AI recruiting tool discriminated against women because it was trained on a dataset containing mostly resumes from male candidates, leading the tool to interpret that women candidates are less preferable (Dilmegani & Ermut, 2025).

### Facial Recognition Bias

AI researchers found that commercial facial recognition technologies from IBM, Microsoft, and Amazon performed poorly on dark-skinned females and well on light-skinned men (Dilmegani & Ermut, 2025).

## Recommendations for Success

### Strategic Approach

1. **Start with business problems, not AI capabilities** - Identify specific problems with measurable costs before considering AI solutions
2. **Define clear, measurable success criteria** - Establish KPIs aligned with business outcomes upfront
3. **Begin small and iterate** - Focus on solving one specific problem really well rather than ten problems sort of well

### Data Management

1. **Implement robust data governance** - Ensure availability, quality, integrity, and security of data
2. **Validate data representativeness** - Ensure training data reflects real-world scenarios and diverse populations
3. **Plan for data drift** - Establish processes for continuous monitoring and model updates
4. **Address edge cases** - Test for uncommon but critical scenarios

### Organizational Structure

1. **Foster cross-functional collaboration** - Implement DataOps and MLOps practices to bridge team gaps
2. **Establish AI Centers of Excellence** - Create federated structures where data scientists from different domains collaborate
3. **Invest in change management** - Prepare workflows and teams for AI integration
4. **Assess build vs. buy decisions** - Evaluate whether to create in-house teams or outsource based on scale and objectives

### Project Execution

1. **Test in real-world conditions early** - Move beyond POC environments quickly
2. **Allocate sufficient resources** - Budget adequately for data acquisition, preparation, and ongoing maintenance
3. **Plan for continuous iteration** - Treat AI as a living product requiring ongoing updates
4. **Maintain AI observability** - Monitor model performance and data quality continuously

## Conclusion

The high failure rate of AI projects is not primarily due to technological limitations but rather organizational readiness, data quality issues, and misaligned expectations. Success requires treating AI projects as fundamentally different from traditional IT projects, with emphasis on data quality, cross-functional collaboration, clear business objectives, and continuous iteration. Organizations that address these root causes systematically can significantly improve their chances of delivering real business value from AI investments.

---

## References

Dilmegani, C., & Ermut, S. (2025, July 24). AI fail: 4 root causes & real-life examples. AIMultiple. Retrieved October 20, 2025, from https://research.aimultiple.com/ai-fail/

Project Management Institute. (2024, December 12). Why most AI projects fail: 10 mistakes to avoid. PMI Blog. Retrieved October 20, 2025, from https://www.pmi.org/blog/why-most-ai-projects-fail