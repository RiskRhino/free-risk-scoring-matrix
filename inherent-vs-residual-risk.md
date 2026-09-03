# Inherent vs. Residual Risk

Risk assessments often distinguish between **inherent risk** and **residual risk**.

Understanding the difference helps organizations evaluate both their initial exposure and the risk remaining after controls are considered.

## What Is Inherent Risk?

Inherent risk is the level of risk before considering existing controls or mitigation measures.

It represents the organization's exposure based on the underlying risk scenario.

### Example

A company processes sensitive customer information.

Before considering its security controls:

* Likelihood = 4
* Impact = 5

Inherent risk:

`4 × 5 = 20`

## What Is Residual Risk?

Residual risk is the level of risk remaining after controls and mitigation measures have been considered.

For example, the company may have:

* Multi-factor authentication
* Access reviews
* Security monitoring
* Endpoint protection
* Employee training
* Incident response procedures

After considering these controls, the assessment might be:

* Likelihood = 2
* Impact = 5

Residual risk:

`2 × 5 = 10`

## Comparison

|                      | Inherent Risk | Residual Risk |
| -------------------- | ------------: | ------------: |
| Likelihood           |             4 |             2 |
| Impact               |             5 |             5 |
| Score                |            20 |            10 |
| Controls considered? |            No |           Yes |

The example shows how controls may reduce the likelihood of a risk while the potential impact remains unchanged.

## Why Both Matter

Inherent risk helps an organization understand the underlying exposure.

Residual risk helps determine whether existing controls reduce the risk sufficiently.

Both can be useful when evaluating:

* Risk appetite
* Control effectiveness
* Treatment priorities
* Resource allocation
* Risk acceptance
* Management reporting

## Residual Risk and Risk Appetite

An organization may establish a risk appetite that determines how much risk it is willing to accept.

If residual risk exceeds the organization's acceptable level, additional treatment may be required.

For example:

```text
Inherent Risk
      ↓
Existing Controls
      ↓
Residual Risk
      ↓
Compare With Risk Appetite
      ↓
Accept / Treat / Escalate
```

## Controls Do Not Always Reduce Impact

Controls may reduce the likelihood of an event without changing its potential consequences.

For example, strong authentication may reduce the probability of unauthorized access, but if unauthorized access does occur, the underlying impact could remain significant.

Organizations should therefore assess likelihood and impact separately.

## Important Consideration

The calculation of residual risk should follow the organization's documented methodology.

Some organizations reduce likelihood, some reduce impact, and some use more sophisticated control-effectiveness models.

## Calculate Risk

**[Use the free RiskRhino Risk Score Matrix](https://riskrhino.com/risk-score-matrix)** to calculate and visualize risk scores.

## Related Resources

* [Risk Matrix](risk-matrix.md)
* [Risk Assessment Guide](risk-assessment-guide.md)
* [Risk Treatment](risk-treatment.md)
