## **Hypothesis Test Notes** 

## **Business Objective** 

The company launched a new onboarding and activation campaign to improve user conversion and engagement. The objective is to determine whether the Treatment experience performs significantly better than the existing onboarding process and should be rolled out to all users. 

## **Primary Metric Selected** 

## **Trial Start Rate** 

Formula: 

Trial Start Rate = Users Who Started Trial / Total Users 

Reason for Selection: 

- Trial start is the first major activation event. 

- It occurs earlier than paid conversion, allowing faster experiment evaluation. 

- It directly reflects onboarding effectiveness. 

- Improvements in trial starts typically increase downstream conversion opportunities. 

## **Null Hypothesis (H0)** 

There is no statistically significant difference in Trial Start Rate between the Control group and the Treatment group. 

H0: 

Treatment Trial Start Rate = Control Trial Start Rate 

## **Alternative Hypothesis (H1)** 

The Treatment group has a higher Trial Start Rate than the Control group. 

H1: 

Treatment Trial Start Rate > Control Trial Start Rate 

1 

## **Test Type** 

One-Tailed A/B Test 

Reason: 

The business objective is to determine whether the Treatment improves performance compared to Control. Only improvement is relevant for the launch decision. 

## **Significance Level** 

Alpha = 0.05 

Decision Rule: 

- If p-value < 0.05, reject the null hypothesis. 

- If p-value ≥ 0.05, fail to reject the null hypothesis. 

## **Test Inputs** 

Control Group Users: 693 

Treatment Group Users: 715 

Control Trial Start Rate: 25.1% 

Treatment Trial Start Rate: 29.1% 

Observed Improvement: 

Approximately +4 percentage points 

## **Statistical Evidence** 

The Treatment group demonstrated a higher Trial Start Rate than the Control group. 

The statistical test was conducted to determine whether the observed difference is likely due to the campaign rather than random variation. 

Test output and calculations are included in: 

screenshots/hypothesis_test_output.png 

2 

## **Business Interpretation** 

The Treatment onboarding experience increases the proportion of users who start a trial compared with the existing onboarding experience. 

This suggests that the campaign improves early-stage activation and user engagement. 

However, the decision should not rely solely on Trial Start Rate. 

Guardrail metrics including: 

- Support Ticket Rate 

- Refund Rate 

- Engagement Score 

- Days to Convert 

must also be reviewed before launch. 

## **Risks and Limitations** 

- Trial starts do not guarantee paid conversion. 

- Increased support requests may create operational costs. 

- Long-term retention is not measured in this experiment. 

- Results may vary across regions, device types, and traffic sources. 

## **Final Testing Conclusion** 

The Treatment group shows evidence of improved onboarding performance and should be considered for rollout only after guardrail metrics are reviewed and business risks are assessed. 

3 

