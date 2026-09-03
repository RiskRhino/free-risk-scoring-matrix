# Risk Register

A risk register is a structured record of identified risks and the information needed to monitor and manage them.

A risk register is often used together with a risk scoring matrix.

## What Does a Risk Register Contain?

A risk register can include:

* Risk ID
* Risk title
* Risk description
* Category
* Cause
* Consequence
* Risk owner
* Likelihood
* Impact
* Risk score
* Existing controls
* Treatment strategy
* Treatment actions
* Residual likelihood
* Residual impact
* Residual score
* Due date
* Status

## Example Risk Register

| ID    | Risk                     | Category      | Likelihood | Impact | Score | Treatment | Owner           | Status      |
| ----- | ------------------------ | ------------- | ---------: | -----: | ----: | --------- | --------------- | ----------- |
| R-001 | Unauthorized data access | Cybersecurity |          4 |      5 |    20 | Reduce    | Security        | Open        |
| R-002 | Supplier disruption      | Operational   |          3 |      4 |    12 | Reduce    | Operations      | Monitoring  |
| R-003 | Regulatory change        | Compliance    |          2 |      5 |    10 | Monitor   | Compliance      | Open        |
| R-004 | Project delay            | Project       |          4 |      3 |    12 | Reduce    | Project Manager | In Progress |

## Risk Description

A useful risk description should explain the relationship between cause, event, and consequence.

Example:

> Inadequate access controls could allow unauthorized users to access sensitive information, potentially resulting in financial, regulatory, and reputational consequences.

## Risk Owner

The risk owner is accountable for ensuring that the risk is understood, monitored, and appropriately managed.

The risk owner does not necessarily need to perform every treatment action personally.

## Risk Score

A simple risk score can be calculated as:

**Likelihood × Impact**

For example:

`4 × 5 = 20`

Organizations should define their own risk-rating thresholds.

## Controls

Document the controls already in place.

Examples:

* Policies
* Procedures
* Technical controls
* Monitoring
* Training
* Contracts
* Reviews
* Testing

## Treatment

Record the selected treatment strategy and actions.

Examples:

* Avoid
* Reduce
* Transfer
* Accept

## Status

A risk register can use statuses such as:

* Open
* Under Assessment
* Treatment Planned
* In Progress
* Monitoring
* Accepted
* Closed

## Review Frequency

Risk reviews may occur:

* Monthly
* Quarterly
* Semi-annually
* Annually
* After significant changes
* After incidents

The appropriate frequency depends on the organization's risk profile.

## Risk Register Template

A CSV template is available in:

`templates/risk-register.csv`

A Markdown assessment template is available in:

`templates/risk-assessment-template.md`

## Calculate Risk Scores

**[Use the free RiskRhino Risk Score Matrix](https://riskrhino.com/risk-score-matrix)** to calculate and visualize risk scores for your assessments.

## Related Resources

* [Risk Matrix](risk-matrix.md)
* [Risk Assessment Guide](risk-assessment-guide.md)
* [Risk Treatment](risk-treatment.md)
* [Risk Examples](examples.md)
