# Case Study: Scaling Labeling Efficiency with Product-Led A/B Experiments

**Role Simulated**: Product Operation Specialist – Data Acquisition  
**Company Simulated**: TikTok Malaysia  
**Experience Level**: 1–3 years (Data & Ops Focused)

---

## 💡 Context

As TikTok scales globally, the need for **large volumes of high-quality labeled data** rises exponentially. However, traditional manual labeling methods are **costly** and **slow**. This case study simulates the role of a **Product Operation Specialist** responsible for:

- Onboarding internal labeling projects
- Diagnosing operational blockers
- Running template experiments
- Driving efficiency via data insights

---

## 💡 Goal

**Optimize labeling throughput and quality** by:

- Reducing blocker turnaround time
- Improving template adoption
- Enhancing labeler experience and accuracy via A/B tests

---

## 💡 Project Scope

| Category             | Details                                           |
|----------------------|---------------------------------------------------|
| Business Lines       | Ad moderation, Creator content labeling           |
| Data Sources         | Simulated queue logs, error rates                 |
| Tools Used           | SQL, Excel, Tableau, Notion                       |
| Key Metrics          | Labeling time/item, error rate, blocker resolution time |

---

## 💡 Process

### 1. 📚 Project Onboarding & Blocker Resolution

- Designed a standardized **onboarding form** capturing project details (priority, guidelines, volume).
- Created mock **queue assignment dashboards** to simulate labeling workflows.
- Diagnosed **3 common blockers**:
  - Unclear content categories
  - Labeling inconsistency due to new UI
  - Queue deadlocks from rule conflicts

**Actions Taken**:
- Suggested clearer documentation and escalation triggers.
- Proposed guideline simplification for ambiguous cases.
- Flagged logic bugs to Engineering via mock Jira workflow.

---

### 2. 📚 A/B Testing Labeling Templates

Ran controlled experiments between two labeling UI formats:

| Variant | Design Description                   | Avg Time | Accuracy | Ease-of-Use Score |
|---------|---------------------------------------|----------|----------|-------------------|
| A       | 3-tab layout (original)               | 24.5 sec | 92%      | 3.2/5             |
| B       | Single-page layout + shortcut hints   | 18.2 sec | 93%      | 4.4/5             |

✅ **Result**: Template B recommended → **25% projected cost savings**

---

### 3. 📚 Product Documentation & Feedback Loop

- Created **Self-Service Onboarding Guide**: platform setup, queue rules, FAQs
- Tested it with a new labeler cohort:
  - Training time reduced from 2 hrs → 45 mins
- Logged blocker types and fed them into a mock Jira triage system

---

## 💡 Outcome Summary

| KPI                         | Before       | After        | Change       |
|-----------------------------|--------------|--------------|--------------|
| Blocker resolution time     | 3 days       | 1 day        | -67%         |
| Labeling time per item      | 22 sec       | 18.2 sec     | +17% speed   |
| Labeler satisfaction score  | 3.1 / 5      | 4.4 / 5      | +42%         |
| Training duration           | 2 hours      | 45 mins      | -63%         |

---

## 💡 Strategic Insight

Rather than hiring more labelers, **scaling onboarding tools, UI experimentation, and blocker detection** created the highest leverage.  
A structured product operations approach led to measurable gains in **labeling speed, quality, and scalability**.

---

## 💡 Relevance to TikTok

This case directly mirrors the responsibilities of TikTok’s **Data Solutions Team**, especially:

- Product support for platform blockers
- Strategic optimization via A/B testing
- Ownership of onboarding and documentation
- Cross-functional alignment between Product, Engineering, and Ops

---

## 💡 Tools Used

- **Data Analysis**: SQL, Excel
- **Visualization**: Tableau Public
- **Documentation**: GitHub, Markdown
- **Workflow Simulation**: Phyton (mocked)

---

## 🚀 Summary

This case study demonstrates how **product ops + data thinking** can reduce costs and improve efficiency in a high-volume content labeling environment like TikTok’s. It reflects early-career readiness to contribute to a **global platform’s operational success** using data, process design, and stakeholder empathy.
