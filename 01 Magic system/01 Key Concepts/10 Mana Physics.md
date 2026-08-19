# Mana Physics

> This appendix provides a quantitative model of the behaviour described in [[02 Mana Dynamics|Mana Dynamics]]. Its constants are attribute-, material-, and condition-specific; it defines their relationships without assigning fixed values.

## Scope and State Model

Mana is a field of discrete particles. At any moment, each particle is in one of three states: **Primed**, **Attuned** to one attribute, or **Spent**. Attunement, Cross-Attunement, Expenditure, Detuning, and Priming change a particle's state while conserving the particle itself.

Each mana type `i` has a discrete **potentia level** `V_i` such that:

```text
V_primed > V_attribute > V_spent = 0

V_a != V_b for distinct attributes a and b
```

Ordinary transitions satisfy `V_initial > V_final`. Priming is the only established exception. The exact ordering and separation of the seven attribute levels have not been assigned.

For a downhill transition from type `i` to type `j`, the released particle potentia is:

```text
Delta V_i->j = V_i - V_j
```

Bound potentia, free mana-field potential, and physical energy are conserved across the combined system rather than within matter alone. For one transition:

```text
V_i = V_j + W + D

D = V_i - V_j - W
```

`W` is the signed operational potentia-equivalent transferred to a valid physical subject. Positive `W` adds energy or produces an equivalent physical change; negative `W` removes energy from the subject. `D` is the field potential discharged into the mana field. A non-operational permutation has `W = 0` and discharges the entire difference between its particle states.

The term **potentia-equivalent** recognises that some attributes alter momentum, continuity, physical patterns, or relations rather than producing heat directly. Their operation still consumes a finite amount of bound mana potentia and produces a corresponding field balance.

`Delta V_i->j` does not determine transition frequency by itself. Each transition also has an activation barrier `B_i->j`, which depends upon the source and destination types, local material and mana conditions, seed concentration, and imposed control. A large downhill drop can therefore remain rare when its activation barrier is high.

## Statistical Permutation

Attunement is a noise-like statistical process. Primed mana continually undergoes small random fluctuations towards possible Attuned states. Sub-threshold fluctuations return to their source state and are not completed permutations. Existing seeds, material affinities, and imposed confinement increase the probability that a matching fluctuation reaches a committed transition; they do not directly command its occurrence.

Once a fluctuation crosses the relevant activation barrier, it constitutes an attempted transition. For an attempted transition from type `i` to a lower intended type `j`, the intended outcome occurs with probability:

```text
P( output = M_j ) = 1 - w_i->j
```

The same attempt **quenches** into Spent mana with probability:

```text
P( output = M_spent ) = w_i->j
```

`w_i->j` is the **waste ratio** for that transition under the stated conditions. It may vary with the potentia difference, activation barrier, fluctuation rate, seed stability, local mana composition, confinement, material conditions, and throughput.

The two particle-scale branches are:

```text
success:  M_i -> M_j     + Phi(V_i - V_j)
quench:   M_i -> M_spent + Phi(V_i)
```

`Phi(D)` denotes a mana-field disruption carrying field potential `D`. For `N` statistically similar attempts:

```text
N_success = N * (1 - w_i->j)
N_waste   = N * w_i->j

D_expected =
    N * (1 - w_i->j) * (V_i - V_j)
    + N * w_i->j * V_i

D_expected = N * [(V_i - V_j) + w_i->j * V_j]
```

The failed particles are **Waste mana**. The released potentia becomes **permutation discharge**, not destroyed or missing capacity. These relationships apply to Attunement and Cross-Attunement and may be used for a specified Detuning destination. Expenditure already ends in Spent mana and instead follows the operational balance below.

## Expenditure and Signed Operation

For Expenditure of one particle of attribute `a`:

```text
M_a -> M_spent + Operation_a(W) + Phi(D)

D = V_a - W
-V_a <= W <= V_a
```

The lower bound caps energy drainage by one particle at an amount equal in magnitude and opposite in sign to that particle's initial potentia-equivalent. The upper bound prevents the same particle from adding more physical energy-equivalent than it carried. Consequently:

| Operation | `W` | `D` |
| --- | ---: | ---: |
| Maximum addition | `+V_a` | `0` |
| Partial addition | `0 < W < V_a` | `0 < D < V_a` |
| No useful operation | `0` | `V_a` |
| Cooling or drainage | `-V_a < W < 0` | `V_a < D < 2V_a` |
| Maximum drainage | `-V_a` | `2V_a` |

A cooling operation therefore transfers physical energy into the mana field in addition to discharging the particle's original potentia. Greater cooling requires proportionally more particles; selection, concentration, and throughput remain independent practical constraints.

An attributed operation may act only upon matter, a non-mana energy field, or a bounded region or relationship of space-time. `W` never represents direct attributed work upon a mana particle, construct scaffold, soul-form, or the mana field itself.

## Combined Potentia and Field-Potential Balance

A world-scale accounting may be represented by:

```text
E_total =
    E_physical
    + sum_i(N_i V_i)
    + integral_Omega(rho_phi dOmega)
    + R_singularity

dE_total/dt = 0
```

Where `rho_phi` is free field-potential density in the mana field and `R_singularity` is field potential retained at, or made available through, the Singularity. `E_physical` need not be constant within a bounded physical system:

```text
dE_physical/dt != 0
```

Local magical operations may therefore violate matter-only energy conservation while remaining balanced by particle potentia and the mana field. Approximate cancellation of additions and removals is an aggregate tendency across large regions and timescales, not a requirement that every local operation be immediately opposed.

## Background Attunement and Seed Stability

For each attribute, Primed mana has a small baseline chance of fluctuating towards a short-lived Attuned state. This **background fluctuation rate** is represented by `b_a`. A high `b_a` can contribute to natural availability, but availability also depends upon critical seed concentration, selective stabilisation, Detuning, and attainable retention yield; it is not a measure of operational complexity.

An isolated Attuned particle ordinarily Detunes into a lower-potentia type, disperses, or becomes Spent before it can establish a meaningful local bias. A concentration of matching particles, called an **attunement seed**, can instead stabilise matching fluctuations and make further attunement more likely. The seed becomes self-sustaining only after it reaches an attribute-specific critical concentration.

## Local Attunement Model

The following grouped equations describe the local concentration of one target attribute while keeping fluctuation generation distinct from selective retention:

```text
dC_a/dt = conversion_a - decay_a - competition_a

fluctuation_a = C_p * b_a

seed_feedback_a =
    ( C_a / C_star,a )^n
    / ( 1 + ( C_a / C_star,a )^n )

stabilisation_a =
    1 - exp[-(r_0,a + m_a M_a + i_a U + s_a seed_feedback_a)]

saturation_a = max[0, 1 - ( C_a / C_sat,a )]

attempt_a =
    fluctuation_a
    * stabilisation_a
    * saturation_a

conversion_a = attempt_a * (1 - w_a)

waste_a = attempt_a * w_a

attunement_discharge_a =
    conversion_a * (V_primed - V_a)
    + waste_a * V_primed

decay_a = d_a * C_a

competition_a = x_a * C_a * C_other
```

`fluctuation_a` is the rate at which random background noise approaches attribute `a`. Material affinity, confinement, and an existing seed act only through `stabilisation_a`: they increase the probability that a matching fluctuation persists long enough to cross the activation barrier and become `attempt_a`. The exponential form keeps this retention probability between `0` and `1`, while the bounded saturation term prevents a full region from producing negative conversion. Sub-threshold fluctuations not included in `attempt_a` return to their source state. A committed attempt then either becomes the intended attribute or quenches according to `w_a`. A more complete model may allow confinement to increase `C_p` or repeatedly circulate Primed particles past the same stabilising region, but it does not replace `b_a` with deterministic conversion.

Where:

| Variable | Description | Impact on local Attunement rate |
| --- | --- | --- |
| `C_a` | Local concentration of the target Attuned attribute. | **High and non-linear.** Increasing it strengthens seed-feedback until saturation; near or above `C_sat,a`, the conversion term falls while decay and competition losses continue to rise. |
| `C_p` | Local concentration of Primed mana. | **High and positive.** Increasing it raises the available feedstock and proportionally raises every conversion term, provided the seed and containment remain viable. |
| `C_other` | Sum of local concentrations of competing Attuned attributes. | **Negative.** Increasing it increases the competition loss term and reduces the target attribute's net accumulation. |
| `b_a` | Background fluctuation rate towards the target attribute. | **Low but positive.** Increasing it raises the number of fluctuations available for selective retention and possible committed transition. |
| `M_a` | Effective amount and selectivity of material or conditions that capture or stabilise the target attribute. | **Potentially high and positive.** Increasing it raises material-assisted accumulation until the material or local region reaches capacity. |
| `m_a` | Strength with which that material or condition assists the target attribute. | **Positive.** Increasing it makes a given `M_a` more effective at retaining matching fluctuations and supporting seed growth. |
| `U` | Imposed confinement and control, whether maintained by a soul-form or a mana construct. | **High and positive.** Increasing it retains favourable fluctuations and may keep more Primed mana within the active region; it does not directly select a particle's state. |
| `i_a` | Effectiveness of that imposed confinement. | **Positive.** Increasing it makes a given level of `U` more effective at preserving favourable fluctuations. |
| `r_0,a` | Baseline chance that a matching fluctuation persists under the stated environment. | **Low but positive.** Increasing it raises unmanaged Attunement yield without changing the fluctuation rate. |
| `s_a` | Strength of stabilisation supplied by a matching seed. | **Positive.** Increasing it makes existing Attuned mana more effective at retaining further matching fluctuations. |
| `w_a` | Waste ratio among fluctuations that cross the activation barrier. | **Negative for yield.** Increasing it causes more committed attempts to quench into Spent mana rather than reaching the target attribute. |
| `C_star,a` | Characteristic concentration at which seed-feedback becomes strong. | **Negative at a fixed `C_a`.** Increasing it delays seed-feedback and raises the practical difficulty of reaching critical concentration. |
| `n` | Sharpness with which seed-feedback emerges. A value greater than `1` produces a more distinct critical transition. | **Threshold-sharpening.** Increasing it weakens feedback below `C_star,a` and strengthens it above that value, making failure below the threshold and growth above it more abrupt. |
| `C_sat,a` | Local saturation limit imposed by repulsion, material capacity, and containment. | **Positive.** Increasing it delays saturation, allowing higher target concentration and conversion rate before the saturation term suppresses further growth. |
| `d_a` | Detuning, dispersion, and leakage rate. | **High and negative.** Increasing it removes target Attuned mana more quickly and raises the critical concentration required for self-maintenance. Detuned particles enter an admissible lower type rather than returning to Primed mana. |
| `x_a` | Strength of interference from competing attributes. | **Negative when `C_other` is present.** Increasing it magnifies the loss caused by competing Attuned mana. |

The conversion term is retained random fluctuation, not imposed transmutation. The final two terms are loss through decay, escape, and competition. The critical concentration is a positive value of `C_a` at which these conversion and loss terms are equal. Below that point, a seed usually dissipates; above it, seed-feedback can retain further fluctuations quickly enough to maintain local growth while sufficient Primed mana remains available.

This equation is a model rather than a universal law with fixed constants. A material may assist multiple attributes, an attribute may have several distinct stabilising conditions, and specific environments can alter any of the listed values.

The equation tracks only one target attribute. A multi-attribute model must add transition terms from higher attributes into `C_a` and from `C_a` into lower attributes. Such terms use their own activation barriers and do not imply that every pair of attributes permits direct Cross-Attunement.

## Mana-Field Transport and Priming

Let `Psi_m` represent the effective potential of the curved mana field and `rho_phi` the density of free disruption potential. Field disruption moves both by dispersal from local concentration and by directed descent towards the Singularity:

```text
partial(rho_phi)/partial(t) + div(J_phi)
    = S_discharge - S_priming

J_phi =
    -k_phi grad(rho_phi)
    -mu_phi rho_phi grad(Psi_m)
```

`S_discharge` collects permutation discharge and potentia-equivalent energy removed from physical subjects. `S_priming` is the field potential rebound into particles at the Singularity. The mana field is curved such that its ordinary inward or upward gradient terminates at the Singularity. Its relation to space-time curvature is opposed in effect but has not been assigned an exact inverse law.

Absent deliberate containment, every free disruption is therefore expected eventually to enter the Singularity's Priming region. Local gradients, matter, and mana currents may delay or disperse that return without providing another permanent sink.

Priming may be represented as:

```text
M_spent + V_primed(field reserve) -> M_primed

R_priming = k_priming * C_spent * rho_phi * S(x)
```

`S(x)` represents the exceptional coupling available at and around the Singularity. This expression is provisional: it states the need for Spent particles, returned field potential, and Singularity coupling without assigning the internal mechanism. Artificial Priming remains theoretical and unattested.

## Mana-Field Motion and Structural Interference

A coherent mana structure has no assigned ordinary rest mass, but responds to mana forces with measurable field inertia and therefore carries field momentum. A minimal kinematic model may therefore represent its motion as:

```text
I_i * dv/dt =
    chi(V_i) F_gravity
    + F_field
    + F_gradient
    + F_repulsion
    + F_material
    - Gamma_i(C_local, v)v
```

`I_i` is effective mana-field inertia rather than ordinary rest mass; for this model, `p_m = I_i v` is the corresponding field momentum. `chi(V_i)` is potentia-dependent gravitational coupling, while `F_field` follows the mana-field gradient towards the Singularity. The remaining terms represent concentration gradients, mana repulsion, material interaction, and the interference of surrounding mana. Material deflection has an equal and opposite but ordinarily negligible physical back-reaction; no hard-surface or excluded-volume term is present because mana structures remain permeable. An attributed operation is absent because mana structures are not valid subjects of attributed operation.

The qualitative gravitational ordering is:

```text
chi(V_primed) > chi(V_attuned) > chi(V_spent) approximately 0
```

Spent mana therefore experiences little outward gravitational force to oppose its inward mana-field motion. Primed mana experiences the strongest outward or downward coupling, while Attuned attributes occupy intermediate responses that need not be identical.

At terminal velocity:

```text
dv/dt = 0

F_drive = F_interference(v_terminal, C_local)
```

For approximately linear interference:

```text
v_terminal = F_drive / Gamma_i
```

The terminal velocity depends upon particle state, local mana concentration, relative flow, material conditions, and, for a coherent structure, topology and effective interaction cross-section. Even nearly inert Spent particles therefore do not accelerate without bound.

A coherent construct may be accelerated by Primed-mana repulsion, environmental mana flow, overlap with another structure's force field, or material interaction. Attributed operation may instead act upon a physical carrier or anchor, while Dimensional mana may alter the bounded space-time through which the construct moves.

Free particles ordinarily produce diffuse perturbations. Where two coherent structures overlap, their constrained geometries can instead produce strong **structural interference**. Its severity depends upon local Primed concentration, topological compatibility, relative motion, scaffold protection, and duration of overlap. Destructive interference may deform either scaffold without requiring an attributed operation.

Mana-field disruption from permutation enters these same local disturbance terms. It may trigger secondary downhill permutations, commonly described as **counterreactions**, by altering activation barriers. It can contribute to uphill Priming only after being carried to and rebound through the Singularity.

## Paired Resonant Transmission

A paired Resonant arrangement is prepared through local contact, common formation, or a continuous intermediary. Pairing gives the endpoints selective affinity; it does not make their states identical or permit instantaneous transmission.

A local Resonant operation couples a change in a physical sender into a propagating mana disturbance. Its paired receiver detects that disturbance selectively and couples the received information into a local physical response. The minimum arrival time is:

```text
t_arrival >= L_path / c_R
```

Where `L_path` is effective path length through the curved mana field and `c_R` is the local propagation speed. Received amplitude may be represented by:

```text
A_received =
    A_sent
    * K_pair
    * G(L_path)
    * exp[-integral_path(alpha_R dl)]
    + N_R
```

`K_pair` is paired selectivity, `G` represents geometric spreading, `alpha_R` is attenuation from local conditions, and `N_R` is background and competing mana disturbance. Transmission may therefore be delayed, weakened, distorted, screened, or interrupted. Pairing ordinarily offers less throughput and reliability than a maintained mana cord, but requires no continuous physical or construct conduit between the prepared endpoints.

Pair selectivity also decays under ordinary disturbance. A minimal maintenance model is:

```text
dK_pair/dt = -lambda_R K_pair + M_R

K_pair(t) = K_pair(0) * exp(-lambda_R t)    when M_R = 0
```

`lambda_R` is the condition-dependent loss of correlation and `M_R` is valid local maintenance performed at the prepared physical endpoints. Maintenance may slow decay, but any measurement or synchronisation exchanged between separated endpoints still travels through a cord or finite-speed Resonant disturbance.

## Material and Condition Parameters

The classifications, mechanisms, and individual profiles of material interaction are defined in [[13 Material Affinities|Material Affinities]]. In this model, the documented seed-supporting or selective properties of a material are represented by `M_a` and `m_a`; a documented decaying effect is represented by `d_a`.

Containment geometry, flow, pressure, temperature, nearby mana composition, and active regulation may behave like material conditions in this model. Their effects are represented by changes to the same constants rather than by additional mana states.

## Modes of Induced Attunement

**Induced Attunement** is the conventional practical term for bringing an attunement seed to its critical concentration by selectively retaining random fluctuations. It includes three overlapping modes:

| Mode                        | How it changes the model                                                                                                         | Limits                                                                                                                      |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Material Attunement**     | A selective medium increases `M_a`, `m_a`, or both, and may lower `d_a`.                                                            | It depends on available Primed mana, the material's selectivity and capacity, and sufficient time for fluctuations to accumulate. |
| **Unstructured Attunement** | A magus uses their soul-form to increase local `C_p` and `U` around a trace seed without a declared mana construct.                  | It is difficult to sustain, poorly regulated, and usually inefficient or impure.                                                 |
| **Structured Attunement**   | An Attuning component maintains suitable `C_p`, `U`, seed retention, separation, and Waste-mana handling.                           | It requires compatible materials, declared construct logic, preparation, and maintenance.                                        |

The modes describe how favourable fluctuations are cultivated, not different forms of mana permutation. A structured Attuner may rely on selective material, while an unstructured practitioner may use a prepared material core. Neither bypasses the random fluctuation represented by `b_a`.

**Unstructured Attunement** must not be confused with **Unstructured Casting**, which is the construct-free Expenditure of already Attuned mana.

## Use of the Model

The model can be used to compare candidate materials, describe natural attunement sites, design reservoirs and Attuners, or explain why a conversion fails. It does not by itself specify a spell, a reagent interaction, or an attributed operation. Those matters remain governed by [[05 Mana Constructs|Mana Constructs]], [[06 Spell Subjects|Spell Subjects]], and [[08 Mana Casting|Mana Casting]].
