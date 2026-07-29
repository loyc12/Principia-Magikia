# Mana Physics

> This appendix provides a quantitative model of the behaviour described in [[02 Mana Dynamics|Mana Dynamics]]. Its constants are attribute-, material-, and condition-specific; it defines their relationships without assigning fixed values.

## Scope and State Model

Mana is a field of discrete particles. At any moment, each particle is in one of three states: **Primed**, **Attuned** to one attribute, or **Spent**. The processes of Attunement, Expenditure, Priming, and Detuning change a particle's state while conserving the particle itself. Mana potential is not conserved.

Attunement is probabilistic. For a target attribute `a`, an attunement attempt produces its Attuned particle with probability:

```text
P( output = Attuned(a) ) = 1 - w_a
```

The same attempt immediately produces a Spent particle with probability:

```text
P( output = Spent ) = w_a
```

`w_a` is the **waste ratio** for that particular attunement process. It may vary with the attribute, conversion rate, local mana composition, containment, materials, and control. Both outcomes may release physical energy and disordered mana-field disturbances as permutation loss. This model concerns the state of the mana particle; permutation loss does not imply that the particle itself has been destroyed.

## Background Attunement and Seed Stability

For each attribute, Primed mana has a small baseline chance of forming a short-lived Attuned fluctuation. This **background attunement rate** is represented by `b_a`. A high `b_a` can contribute to natural availability, but availability also depends upon critical seed concentration, selective media, Detuning, and attainable conversion yield; it is not a measure of operational complexity.

An isolated Attuned particle ordinarily Detunes, disperses, or is spent before it can establish a meaningful local bias. A concentration of matching particles, called an **attunement seed**, can instead stabilise matching fluctuations and make further attunement more likely. The seed becomes self-sustaining only after it reaches an attribute-specific critical concentration.

## Local Attunement Model

The following equivalent grouped equations describe the local concentration of one target attribute. They separate conversion from the two forms of loss:

```text
dC_a/dt = conversion_a - decay_a - competition_a

conversion_a =
    C_p
    * ( b_a + m_a * M_a + i_a * U * seed_feedback_a )
    * saturation_a

seed_feedback_a =
    ( C_a / C_star,a )^n
    / ( 1 + ( C_a / C_star,a )^n )

saturation_a = 1 - ( C_a / C_sat,a )

decay_a = d_a * C_a

competition_a = x_a * C_a * C_other
```

Where:

| Variable | Description | Impact on local Attunement rate |
| --- | --- | --- |
| `C_a` | Local concentration of the target Attuned attribute. | **High and non-linear.** Increasing it strengthens seed-feedback until saturation; near or above `C_sat,a`, the conversion term falls while decay and competition losses continue to rise. |
| `C_p` | Local concentration of Primed mana. | **High and positive.** Increasing it raises the available feedstock and proportionally raises every conversion term, provided the seed and containment remain viable. |
| `C_other` | Sum of local concentrations of competing Attuned attributes. | **Negative.** Increasing it increases the competition loss term and reduces the target attribute's net accumulation. |
| `b_a` | Background attunement rate for the target attribute. | **Low but positive.** Increasing it raises spontaneous production and makes seed formation more likely, especially before a critical concentration exists. |
| `M_a` | Effective amount and selectivity of material or conditions that capture or stabilise the target attribute. | **Potentially high and positive.** Increasing it raises material-assisted accumulation until the material or local region reaches capacity. |
| `m_a` | Strength with which that material or condition assists the target attribute. | **Positive.** Increasing it makes a given `M_a` more effective at retaining matching fluctuations and supporting seed growth. |
| `U` | Imposed confinement and control, whether maintained by a soul-form or a mana construct. | **High and positive.** Increasing it strengthens artificial induction, provided the confinement does not cause instability, leakage, or material saturation. |
| `i_a` | Effectiveness of that imposed induction. | **Positive.** Increasing it makes a given level of `U` produce more target-attribute conversion. |
| `C_star,a` | Characteristic concentration at which seed-feedback becomes strong. | **Negative at a fixed `C_a`.** Increasing it delays seed-feedback and raises the practical difficulty of reaching critical concentration. |
| `n` | Sharpness with which seed-feedback emerges. A value greater than `1` produces a more distinct critical transition. | **Threshold-sharpening.** Increasing it weakens feedback below `C_star,a` and strengthens it above that value, making failure below the threshold and growth above it more abrupt. |
| `C_sat,a` | Local saturation limit imposed by repulsion, material capacity, and containment. | **Positive.** Increasing it delays saturation, allowing higher target concentration and conversion rate before the saturation term suppresses further growth. |
| `d_a` | Detuning, dispersion, and leakage rate. | **High and negative.** Increasing it removes target Attuned mana more quickly and raises the critical concentration required for self-maintenance. |
| `x_a` | Strength of interference from competing attributes. | **Negative when `C_other` is present.** Increasing it magnifies the loss caused by competing Attuned mana. |

The first group of terms is conversion into the target attribute. The final two terms are loss through decay, escape, and competition. The critical concentration is a positive value of `C_a` at which these conversion and loss terms are equal. Below that point, a seed usually dissipates; above it, seed-feedback can maintain further attunement while sufficient Primed mana remains available.

This equation is a model rather than a universal law with fixed constants. A material may assist multiple attributes, an attribute may have several distinct stabilising conditions, and specific environments can alter any of the listed values.

## Material and Condition Parameters

The classifications, mechanisms, and individual profiles of material interaction are defined in [[13 Material Affinities|Material Affinities]]. In this model, the documented seed-supporting or selective properties of a material are represented by `M_a` and `m_a`; a documented decaying effect is represented by `d_a`.

Containment geometry, flow, pressure, temperature, nearby mana composition, and active regulation may behave like material conditions in this model. Their effects are represented by changes to the same constants rather than by additional mana states.

## Modes of Induced Attunement

**Induced Attunement** is the practical field concerned with bringing an attunement seed to its critical concentration and maintaining the conditions under which it converts Primed mana. It includes three overlapping modes:

| Mode                        | How it changes the model                                                                                                         | Limits                                                                                                                      |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Material Attunement**     | A selective medium increases `M_a`, `m_a`, or both, and may lower `d_a`.                                                         | It depends on available Primed mana, the material's selectivity and capacity, and sufficient time for a seed to accumulate. |
| **Unstructured Attunement** | A magus uses their soul-form to increase local `C_p`, `C_a`, and `U` without a declared mana construct.                          | It is difficult to sustain, poorly regulated, and usually inefficient or impure.                                            |
| **Structured Attunement**   | An Attuning component and its supporting assembly maintain suitable values of `C_p`, `C_a`, `U`, separation, and waste handling. | It requires compatible materials, declared construct logic, preparation, and maintenance.                                   |

The modes describe how induced Attunement is achieved, not different forms of mana permutation. A structured Attuner may rely on selective material, while an unstructured practitioner may use a prepared material core.

**Unstructured Attunement** must not be confused with **Unstructured Casting**, which is the construct-free Expenditure of already Attuned mana.

## Use of the Model

The model can be used to compare candidate materials, describe natural attunement sites, design reservoirs and Attuners, or explain why a conversion fails. It does not by itself specify a spell, a reagent interaction, or an attributed operation. Those matters remain governed by [[05 Mana Constructs|Mana Constructs]], [[06 Spell Subjects|Spell Subjects]], and [[08 Mana Casting|Mana Casting]].
