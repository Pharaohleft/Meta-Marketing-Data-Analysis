

# Meta Ads Performance Analysis — Facebook vs Instagram Funnel Optimization

---

## Executive Summary (Marketing-Focused)

- Evaluated paid advertising performance across Facebook and Instagram to assess reach, engagement quality, and conversion efficiency.
- Found strong top-of-funnel performance (CTR ~12%, Engagement Rate ~13%) but significant drop-off at the purchase stage (Purchase Rate <1%).
- Identified audience, creative, timing, and channel-level optimization opportunities to improve ROI without increasing spend.

---

## Business Context (This Is Key for Marketing Roles)

Marketing teams need to decide where to allocate budget across Meta platforms.

The goal is not just engagement, but efficient customer acquisition.

This analysis supports decisions on:

- Platform prioritization
- Audience targeting
- Creative format selection
- Campaign timing

(We will explicitly reference the BRD intent here.)

---

## Data & Modeling (Signals You’re a Real Analyst)

- Event-level ad interaction data (impressions → clicks → purchases)
- Star schema with:
  - **Fact table:** `ad_events`
  - **Dimensions:** ads, campaigns, users

Enables:

- Funnel KPIs (CTR, Conversion Rate, Purchase Rate)
- Audience segmentation (gender, age, geography)
- Creative and platform comparison

This shows you understand marketing data, not just visualize it.

---

## Key KPIs (Marketing-Relevant)

We’ll keep this concise and sharp:

- **CTR** → Creative effectiveness
- **Engagement Rate** → Message resonance
- **Conversion Rate** → Post-click efficiency
- **Purchase Rate** → True ROI proxy
- **Spend** → Budget context













## Facebook — Core Performance Signals

---

### 1. Funnel Health: Strong Top & Mid, Weak Bottom

- CTR (~11.8%) and Engagement Rate (~13.6%) are strong, indicating effective creative and targeting at the awareness and consideration stages.
- Conversion Rate (5.21%) is reasonable, but Purchase Rate (0.61%) is materially low relative to upstream performance.
- This suggests drop-off occurs post-click, not during ad exposure.

**Interpretation:**  
Facebook ads are good at driving interest, but the downstream purchase experience (landing page, offer, or intent quality) is the bottleneck.

---

### 2. Audience Skew: Consistent but Narrow

- Female users dominate impressions, clicks, engagements, and purchases across all views.
- Male contribution is consistently ~20–22% across the funnel and never meaningfully catches up.
- Age distribution peaks in the early-to-mid 20s, with a steep decline after ~35.

**Interpretation:**  
Facebook delivery is optimized toward a young, female-heavy audience, either by design (targeting) or algorithmic learning. This concentration creates efficiency but increases dependency risk.

---

### 3. Temporal Stability with Mild Fatigue Signals

- Weekly trends are stable across impressions, clicks, engagements, shares, comments, and purchases.
- Hourly trends show predictable oscillations (morning and evening bumps), but no sustained growth pattern.
- No metric shows a clear upward trajectory over time.

**Interpretation:**  
Campaigns appear to be in a steady-state optimization loop — performing consistently but not improving. This often indicates creative saturation or budget caps limiting incremental gains.

---

### 4. Geography: Performance Is Broad, Not Deep

- Activity is spread across major markets (US, Canada, Europe, India, Australia).
- No single country visually dominates conversions disproportionately.
- This suggests horizontal reach rather than deep market penetration.

**Interpretation:**  
Facebook spend is diversified geographically, but likely lacks localized optimization (country-specific creatives or offers).

---

### 5. Ad Type Analysis: Incremental, Not Transformational Differences

- Stories slightly outperform other formats on CTR and conversion rate.
- Carousel, Image, and Video are tightly clustered in performance.
- No ad type materially changes purchase efficiency.

**Interpretation:**  
Format choice is not the primary lever for improving outcomes. Gains must come from messaging, offer, or post-click optimization.

---

### 6. Social Signals ≠ Commercial Impact

- Shares and comments exist but do not translate proportionally into purchases.
- High engagement does not correlate with high purchase lift.

**Interpretation:**  
Facebook engagement here is likely lightweight or social, not purchase-driven. Optimizing for engagement alone would inflate vanity metrics without revenue impact.

## Key Insights (This Is Where You Shine)

We will not copy the PDF verbatim. Instead, we’ll elevate it:

---

### 1. Funnel imbalance

- High CTR + ER but low Purchase Rate → classic conversion bottleneck
- Indicates friction after click (landing page, offer, intent mismatch)

---

### 2. Platform roles

- Facebook drives scale and consistency
- Instagram adds reach but does not improve conversion efficiency
- Channel choice is not the primary lever — funnel optimization is

---

### 3. Audience concentration

- Strong skew toward females aged 18–30
- Efficient but risky if over-relied upon
- Opportunity to test adjacent segments

---

### 4. Creative & format

- Video and Stories outperform static formats
- Gains are incremental → creative alone won’t fix conversion drop-off

---

### 5. Timing

- Afternoon and evening consistently outperform
- Indicates opportunity for day-parting optimization

---

## Areas of Concern (Very Important for Senior Signal)

- Heavy reliance on engagement metrics without corresponding revenue lift
- Underutilization of retargeting and post-click optimization
- Budget spread across geographies without localized conversion tuning
## Actionable Recommendations (Marketing-Grade)

Concrete, realistic actions:

- Shift optimization focus from CTR to Purchase Rate / ROAS
- Introduce retargeting campaigns for high-engagement users
- Optimize landing pages and offers for mobile-first Meta traffic
- Reallocate spend toward Video & Stories + high-performing regions
- Apply day-parting to concentrate spend during peak hours

---

## Tools & Skills Demonstrated (ATS-Friendly)

- **Power BI** (DAX, parameters, interactive dashboards)
- **Marketing KPI design** (CTR, CR, Purchase Rate)
- Funnel analysis
- Audience segmentation
- Campaign performance analysis
## Financial Risk & Opportunity Assessment

---
<img width="1253" height="707" alt="1" src="https://github.com/user-attachments/assets/b31ef4dc-1fc4-4d5d-b25e-a1a11460f46b" />

### 1. Revenue Leakage at Scale (Primary Risk)

Despite strong performance in awareness and engagement, only ~0.6% of impressions convert into purchases. At a total spend of $2.5M, this implies that the majority of advertising investment is not translating into direct revenue outcomes.

**Business risk:**  
If this conversion gap persists, incremental budget increases will primarily inflate vanity metrics (clicks, engagement) rather than profitable growth, leading to diminishing returns on ad spend.

**Opportunity:**  
Even a modest lift in purchase rate (e.g., +0.3–0.5 percentage points) would yield a disproportionately large revenue gain without increasing budget, making funnel optimization far more cost-effective than scaling spend.

---

### 2. Misalignment Between Optimization Metrics and Business Goals

Current performance suggests campaigns are optimized for CTR and engagement, both of which are strong. However, these metrics do not correlate proportionally with purchases.

**Business risk:**  
Optimizing toward upper-funnel KPIs creates a false sense of success while masking poor revenue efficiency. This increases the likelihood of over-investing in campaigns that look strong but underperform financially.

**Opportunity:**  
Reorienting optimization toward purchase rate, conversion rate, or ROAS would immediately improve capital efficiency and align marketing performance with revenue outcomes.

---

### 3. Audience Concentration Risk

The majority of engagement and purchases come from a narrow demographic segment (females aged ~18–30) across both platforms.

**Business risk:**  
Over-reliance on a single audience cohort increases exposure to:
- Audience saturation
- Rising CPMs
- Performance volatility if preferences shift

**Opportunity:**  
Expanding controlled tests into adjacent age or gender segments could unlock incremental demand while reducing dependency risk — especially if paired with retargeting strategies.

---

### 4. Platform Efficiency vs Scale Tradeoff

Facebook delivers greater volume and stability, while Instagram provides incremental reach but no meaningful improvement in conversion efficiency.

**Business implication:**  
This indicates that platform selection is not the limiting factor in performance. Simply reallocating budget between Facebook and Instagram is unlikely to materially improve ROI.

**Opportunity:**  
The constraint lies downstream — landing pages, offers, and retargeting — suggesting higher returns from post-click optimization than channel-level budget shifts.

---

### 5. Creative & Timing Are Secondary Levers

Video and Stories marginally outperform other formats, and performance peaks during afternoon and evening hours.

**Business interpretation:**  
These factors offer incremental gains, but they will not resolve the core efficiency problem alone.

**Opportunity:**  
Once funnel efficiency improves, these levers can be layered on to compound gains — but addressing them first would yield limited financial upside.

---

## Strategic Implications for the Business

- The organization is paying efficiently for attention, but overpaying for conversions.
- Growth is currently constrained by conversion mechanics, not reach or creative appeal.
- The fastest path to improved ROI is conversion optimization, not budget expansion.

---
<img width="1247" height="714" alt="2" src="https://github.com/user-attachments/assets/f3792ee2-c91d-49ab-99ec-8b8f306707c7" />

## Executive Recommendations (Revenue-Focused)

- Shift success metrics from CTR to Purchase Rate / ROAS to prevent inefficient spend.
- Invest in landing page and offer optimization to reduce post-click drop-off.
- Deploy retargeting campaigns for high-intent users already engaging with ads.
- Use Video & Stories as primary formats, but only after conversion fixes.
- Expand audience testing cautiously to reduce concentration risk.
