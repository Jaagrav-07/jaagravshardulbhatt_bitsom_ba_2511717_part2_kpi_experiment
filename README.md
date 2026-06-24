# Part 2 – KPI Framework, Business Experiment Analysis & Decision Recommendation

## Business Context

A subscription-based digital product company launched a new onboarding and activation campaign to improve user conversion and early engagement.

Users were randomly assigned to:

* Control Group: Existing onboarding experience
* Treatment Group: New onboarding campaign

The objective was to determine whether the Treatment experience should be rolled out to all users.

---

## Business Problem Statement

The company must decide whether the new onboarding campaign should replace the existing onboarding experience.

This decision impacts:

* New users
* Product teams
* Marketing teams
* Revenue growth

The desired outcome is improved activation and conversion while maintaining a positive customer experience.

Before making a recommendation, evidence is required from experiment results, hypothesis testing, KPI performance, and guardrail metrics.

---

## Dataset Description

The dataset contains user-level experiment data including:

* Experiment group assignment
* Landing page visits
* Trial starts
* Onboarding completion
* Paid conversion
* Revenue
* Refund requests
* Support tickets
* Engagement scores
* Days to convert
* User segments such as region, device type, traffic source, and plan type

---

## North Star Metric

### Selected Metric

**Trial Start Rate**

### Why This Metric Was Selected

Trial Start Rate directly measures user activation and onboarding success.

It was selected because:

* It occurs early in the user journey
* It reflects onboarding effectiveness
* It is strongly connected to future conversions and revenue growth

### Supporting Metrics

Supporting metrics include:

* Landing Page Visit Rate
* Onboarding Completion Rate
* Paid Conversion Rate
* Average Revenue Per User
* Engagement Score

These metrics help explain performance but are not the primary success measure.

### Risks of Optimizing Only This Metric

Focusing only on Trial Start Rate may:

* Increase support requests
* Reduce revenue quality
* Increase refunds
* Create negative user experiences

---

## KPI Tree Summary

### North Star Metric

Trial Start Rate

### Primary Drivers

1. User Acquisition Quality
2. Onboarding Completion
3. User Engagement

### Sub-Drivers

#### User Acquisition Quality

* Landing Page Visit Rate
* Traffic Source Quality

#### Onboarding Completion

* Onboarding Completion Rate
* Days to Convert

#### User Engagement

* Engagement Score
* Paid Conversion Rate

### Guardrail Metrics

* Support Ticket Rate
* Refund Rate
* Revenue Quality
* Segment-Level Performance

---

## Experiment Analysis Approach

The following checks were performed:

* Missing value review
* Group count validation
* Duplicate user ID review
* Binary field validation
* Revenue outlier review
* Segment distribution comparison
* Control vs Treatment metric comparison

---

## Hypothesis Test Summary

### Null Hypothesis (H0)

Treatment Trial Start Rate = Control Trial Start Rate

### Alternative Hypothesis (H1)

Treatment Trial Start Rate > Control Trial Start Rate

### Significance Level

0.05

### Test Type

One-tailed hypothesis test

### Result

The Treatment group achieved a higher Trial Start Rate than the Control group.

The experiment provides evidence that the new onboarding experience improves activation performance.

---

## Guardrail Metrics Considered

The following guardrail metrics were evaluated:

* Support Ticket Rate
* Refund Rate
* Average Days to Convert
* Engagement Score

Treatment improved activation and engagement but increased support ticket volume.

This indicates that operational impact should be monitored after rollout.

---

## Final Recommendation

### Recommendation

**Launch with monitoring.**

### Reasons

* Improved Trial Start Rate
* Improved engagement
* Faster user activation
* Positive conversion impact

### Monitoring Required

* Support Ticket Rate
* Refund Rate
* Segment-level performance
* Long-term retention

---

## Assumptions and Limitations

* The experiment duration may not capture long-term retention.
* User behavior may change after rollout.
* Some segments may respond differently than others.
* Trial starts do not guarantee future revenue.

---

## Screenshots Included

* summary_metrics.png
* hypothesis_test_output.png
* kpi_tree_preview.png

---

## Repository Contents

### Data

* campaign_experiment_data.xlsx

### Analysis

* experiment_analysis.xlsx
* hypothesis_test_notes.md

### Outputs

* experiment_summary.xlsx
* recommendation_memo.md
* kpi_tree.png

### Screenshots

* summary_metrics.png
* hypothesis_test_output.png
* kpi_tree_preview.png
