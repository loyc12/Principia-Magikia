# Mana Dynamics

This reference describes mana's observable states, flow, conversion, storage, and practical behaviour. [[10 Mana Physics|Mana Physics]] provides an optional quantitative model of these processes; it is useful for calibration and theory, but is not required to understand the wider magic system.

## Mana Flow

Mana is a field of discrete particles, each one being in one of **3 possible states** :

- **Primed** - charged with **unattuned potential**
- **Attuned** - charged with **attuned potential**, differentiated along multiple **mana attributes**
- **Spent** - uncharged, as its potential was consumed during permutation

Collectively, Primed, Spent, and the various Attuned mana attributes are known as **mana types**, and the process of converting from one of these to another is known as **mana permutation**. Permutation follows three active processes and one passive process :

| Permutation        | Process Formula                                                                   |
| ------------------ | --------------------------------------------------------------------------------- |
| **Attunement**\*   | Primed => Attuned( attribute ) x ( 1 - Ratio ) + Spent x Ratio + Permutation Loss |
| **Expenditure**    | Attuned( attribute ) => Spent + Operation( attribute )                            |
| **Priming**\*\*    | Spent + [[The Singularity\|Singularity]] => Primed                                |
| **Detuning**\*\*\* | Attuned( attribute ) => Primed + Spent + Permutation Loss                         |

*\*Attunement releases residual physical energy and disordered mana-field disturbances, collectively termed **permutation losses**.*

*\*\*Priming occurs exclusively around the Singularity.*

*\*\*\*Detuning is the slow loss of an Attuned mana particle's differentiated attribute. It is not partial Priming: it does not restore Spent mana's potential and may occur far from the singularity.*

Mana particles are conserved through permutation, but their potential is not. Attunement always incurs some loss, while expenditure consumes the attuned potential required to perform an attributed operation.

Mana types interact with themselves and one another through repellent forces, pushing mana away from highly concentrated areas and towards less concentrated ones.

They are also affected by gravitational pull, with Spent mana being pulled upwards, where it eventually undergoes Priming, while the other states are pulled downwards at varying rates, pooling in low-lying areas of the surface.

Material interactions with Primed, Spent, and Attuned mana are defined in [[13 Material Affinities|Material Affinities]].

Of all mana types, Primed mana is the most reactive with itself, other mana types, and mana-interactive matter, while Spent mana is the least reactive, being nearly inert. The properties of Attuned mana generally lie between these two extremes and vary per attribute.

## Mana States in Practice

The three mana states are not interchangeable stores of the same immediately usable resource. Their different potential and behaviour determine how magi, instruments, and living systems can use them.

| State | Immediate Use | Characteristic Behaviour | Ordinary Handling |
| --- | --- | --- | --- |
| **Primed** | Feedstock for Attunement and the constructive medium of scaffolds, components, and natural mana structures | Highly reactive, easily disturbed, and strongly responsive to local mana and material conditions | Collected, contained, shaped, or passed through an Attuner before operational use |
| **Attuned** | Performs the primitive operation associated with its attribute when properly expended | Attribute-specific; less generally reactive than Primed mana but still subject to flow, affinity, and local concentration | Kept separated by attribute, stored in reservoirs, and supplied to a construct or direct operation |
| **Spent** | Residual product of Expenditure and Attunement | Nearly inert and drawn upward towards eventual Priming | Dissipated, removed from active systems, or allowed to re-enter the natural Priming cycle |

Primed mana is flexible because it has not yet been committed to one attribute, but this flexibility is not immediate magical power. It cannot by itself heat, move, bind, illuminate, or otherwise perform an attributed operation. Attuned mana is correspondingly less flexible but more immediately useful: it can be expended directly, provided its concentration and coupling exceed the relevant [[06 Spell Reagents|reagent's]] expenditure threshold.

### Primed Mana as a Constructive Medium

Primed mana is used to form the stable geometries of [[05 Mana Constructs|mana constructs]]. When shaped into a scaffold, it is geometrically constrained and functionally isolated from ordinary flow, allowing it to retain potential without immediately undergoing Attunement. Declared components then use this constrained mana to encode and stabilise construct behaviour.

Primed mana also carries information within constructs. Primed packets travel along constrained Primed strands as constants, inputs, control signals, references, retained state, and outputs. The packet or strand does not itself perform an attributed operation; it preserves and transmits the declared information by virtue of its configuration and route.

The early formation of a [[03 Soul-Forms|soul-form]] likewise depends upon Primed mana. Recurrent nervous activity organises nearby Primed mana into partially stable configurations, while the relevant material conditions are defined in [[13 Material Affinities|Material Affinities]]. These configurations become self-reinforcing through continued interaction with the active substrate. A mature soul-form remains a dynamic mana structure rather than a fixed Primed scaffold, but Primed mana within and around it continues to reinforce animic resistance.


**Flow Theory** is the study of mana movement under concentration gradients, repellent interactions, gravity, material affinity, and environmental conditions.

**Mana Hydrodynamics** is the applied study of large-scale mana currents, pooling, circulation, turbulence, and transport through natural or artificial channels.

## Mana Attunement

**Mana potential** is the capacity of a mana particle to perform an attributed operation. Physical energy may be created, redistributed, consumed, or conserved depending on the attribute involved.

**Attunement** is the process of converting Primed mana into Attuned mana. It occurs at a low **background rate** even without a caster or apparatus: Primed mana occasionally produces short-lived fluctuations of particular attributes. Simpler and more common attributes tend to appear more readily than rare, complex, or poorly understood ones.

An isolated Attuned particle does not normally possess enough stability bias or local concentration to remain Attuned. It usually Detunes, disperses, or is spent before it can influence neighbouring Primed mana. A background attunement event also has a variable chance of immediately producing Spent mana rather than the intended Attuned particle. This portion is **Waste mana**, while the accompanying residual energy and disordered mana-field disturbance are **permutation loss**. The resulting **waste ratio** depends upon the attribute, process, and conditions; faster or less controlled conversion is generally less efficient.

An **attunement seed** is a local concentration of one Attuned attribute that makes nearby fluctuations of that same attribute more likely to persist. Once a seed reaches its attribute-specific critical concentration, it can bias further nearby Primed mana towards that attribute quickly enough to maintain itself. This does not allow unlimited growth: Primed-mana supply, material capacity, repulsion, leakage, Waste mana, and competing attributes eventually limit the concentration or establish a local equilibrium.

Material conditions can create or support seeds. The classifications, mechanisms, and individual profiles for selective attunement and destabilising media are defined in [[13 Material Affinities|Material Affinities]].

Attunement can also be induced through direct mana casting. A caster uses the soul-form to gather Primed mana and restrain it around a seed of the desired attribute, bringing its local concentration to the critical point. A mana construct can perform the same task through its Attuning component, while adding declared sourcing, containment, regulation, separation, and waste handling. The mechanism is the same in both cases; the structured process is more stable, selective, and repeatable. Manual Attunement is often one of the first exercises taught to novice magi, but is rarely efficient in time, effort, or purity of results.

The quantitative relationships behind background, material-assisted, and induced Attunement are collected in [[10 Mana Physics|Mana Physics]].

### Modes of Induced Attunement

**Induced Attunement** is the broad practical field of establishing or maintaining an attunement seed long enough for it to reach critical concentration. Its modes are distinguished by the means used to create and control that seed:

| Mode                        | Means                                                                                                                | Ordinary use                                                                                |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Material Attunement**     | A selective attunement medium or favourable local condition captures and stabilises matching background fluctuations | Natural deposits, passive reservoirs, ecological adaptations, and simple Attuning apparatus |
| **Unstructured Attunement** | A magus directly manipulates local mana through the soul-form, without a declared mana construct                     | Training, small adjustments, emergency conversion, and improvised work                      |
| **Structured Attunement**   | A declared spell assembly or Attuning component sources, confines, regulates, and separates the conversion process   | Reliable supply, high purity, controlled throughput, and safe waste handling                |

These modes may be combined. A structured Attuner often uses selective materials, and an unstructured practitioner may use a material core to make manual induction possible. **Unstructured Attunement** is direct mana casting, not **Unstructured Casting**: the latter is the direct Expenditure of mana that is already Attuned.

Already Attuned mana can be expended directly without first undergoing attunement, making it substantially more efficient and immediately useful than an equivalent supply of Primed mana. This advantage is offset by the difficulty of obtaining, separating, storing, transporting, and replenishing particular attributes, whose natural distributions are highly heterogeneous along the surface of the Expanse.

Reservoirs of Attuned mana are therefore useful even without any associated executable spell assembly. A caster may draw directly from such a reservoir for Unstructured Casting, or manually supply it to a structured construct while omitting its usual Attuning components.

### Attunement Quality and Control

An attunement process is evaluated by more than whether it produces the intended attribute. Its practical quality depends upon :

- **rate**, the amount converted over a given period
- **yield**, the proportion of Primed mana becoming the intended Attuned attribute rather than Spent mana
- **purity**, the degree to which the output is concentrated in one intended attribute rather than mixed with unwanted Attuned mana
- **stability**, the extent to which the produced mana remains contained, separated, and usable before it disperses or causes further local Attunement
- **control**, the operator's ability to select the target attribute, throughput, and destination of the output

Unstructured Attunement is useful for training, small adjustments, and circumstances where no instrument is available. Structured Attuners are preferred where a reliable supply, high purity, controlled throughput, or safe waste handling is required. Neither is Unstructured Casting: that term refers only to the direct Expenditure of already Attuned mana.

### Distribution, Storage, and State Interactions

Primed mana is generally the easier state to gather from a mana-rich environment, but it is difficult to keep inert and precisely contained. Dense Primed concentrations react with nearby mana and mana-interactive matter, can interfere with controlled Expenditure, and may produce uncontrolled local Attunement if containment fails.

Attuned mana is more valuable as a working supply but less convenient as a general resource. Each attribute has its own natural distribution, affinity, storage needs, and demand. A reservoir therefore represents a specific logistical commitment rather than a universal mana store: it must preserve its accepted attribute, limit leakage and contamination, and be replenished from local sources or an Attuner.

Existing Attuned mana biases nearby Primed mana toward the same attribute, making local Attunement partly self-propagating. This permits reservoirs and dedicated Attuning installations to cultivate favourable conditions, but excessive concentration also increases the difficulty of separation, containment, and waste management.

Attuned mana does not normally perform its primitive operation merely by being stored beside a compatible reagent. Expenditure requires sufficient local concentration and coupling. Primed mana presents the opposite practical concern: its reactivity makes it useful for construction and conversion, but also makes saturation, interference, and uncontrolled permutation the central risks of handling it.

### Mana Purity and Contamination

**Mana purity** is the degree to which a stored or supplied mana stock conforms to its intended state, attribute, concentration, and permitted supporting materials. **Mana contamination** is the presence of mana outside that specification. It is an engineering and quality-control term, not a separate mana state or a mysterious universal reaction.

Common contamination includes :

- **Spent mana**, which reduces usable capacity while remaining largely inert
- **Primed mana**, which increases reactivity, local Attunement pressure, and containment risk
- **unintended Attuned attributes**, which make a supply unreliable for an operation expecting one specified attribute
- **foreign construct-state or flow**, which is more precisely termed signal corruption or construct interference when it affects information-bearing strands and interfaces

Contamination may result from leaky containment, conduit backflow, imperfect Attunement, Detuning, poorly separated sources, or damaged construct interfaces. Its ordinary effects are reduced purity, uncertain capacity, weaker Attunement biasing, and more difficult validation or filtering. It becomes directly dangerous only when unintended mana reaches an operational component or an expenditure threshold.

### Attunement Decay

**Attunement Decay**, commonly called **Detuning**, is the passive relaxation of Attuned mana back towards the Primed state. It probabilistically erases or spends attribute particle rather than directly restoring it to its prior condition: macroscopically, this results in some remaining potential being lost as Spent mana and permutation loss during the process.

Detuning is ordinarily slow enough that it does not determine the outcome of a short casting. It does, however, make Attuned mana a perishable working resource. Poorly contained supplies may noticeably lose purity or usable capacity over days or weeks, while well-designed reservoirs can preserve a stable attribute supply for far longer.

The rate of Detuning is measured as a half-life, and depends upon the attribute, local mana composition, material interaction, concentration, and containment. Dense reservoirs and active regulation can slow the process, while turbulence, Primed-mana saturation, leakage, and exposure to competing mana conditions accelerate it. The classifications and profiles of materials that retain or destabilise attributes are defined in [[13 Material Affinities|Material Affinities]].

The singularity's distant influence may bias Detuning without constituting Priming. Actual Priming remains exclusive to the singularity, while the wider field of the Expanse gradually favours the loss of unstable differentiation in poorly maintained Attuned mana.

Rare or poorly understood attributes are generally the hardest to preserve. Dimensional mana may Detune rapidly, irregularly, or under conditions not yet understood, contributing to its scarcity and the difficulty of experimental work involving it.

Soul-forms and other persistent active systems may locally stabilise their associated mana through continuing organisation and feedback. This does not prevent Detuning indefinitely, but helps explain why a living organism's mana environment is more coherent and resistant to disturbance than an equivalent inactive volume.

> *Reminder : Attunement refers to a permutation process, while an attribute refers to the differentiated potential produced by that process. An aspect is a recognised mode of applying an attribute, not a further mana type.*

## The Seven Mana Attributes

The seven known Attuned **attributes** are listed below. Their natural availability is classified by the conditions required for unmanaged seeds and practical reservoirs to form; it is not a measure of a caster's operational skill.

| Attribute         | Common Names                      | Availability | Operation Domain Description                                                                                         |
| ----------------- | --------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------- |
| **Kinetic**       | Motion, Force, Heat, Pressure     | Widespread   | Change the momentum distribution of matter, whether disordered, periodic, converging, diverging, or directional      |
| **Radiant**       | Light, Illusion, Cloaking, Optics | Widespread   | Emit, absorb, redirect, or otherwise manipulate free photons                                                         |
| **Galvanic**      | Lightning, Magnetism              | Localised    | Change electric charges, currents, and quasi-static electromagnetic fields                                           |
| **Cohesive**      | Structure, Cohesion, Binding      | Localised    | Change which portions of matter are mechanically continuous without directly specifying their chemical composition   |
| **Resonant**      | Linking, Observation, Divination  | Scarce       | Change the degree to which state changes in one system are detectable by, transmitted to, or correlated with another |
| **Signetic**      | Inscription, Recording, Decoding  | Scarce       | Establish, preserve, inspect, translate, or erase declared distinguishable patterns in a bounded physical medium     |
| **Dimensional**\* | Scale, Curvature, Gravity, Time   | Exceptional  | Modify proper distance, duration, and their gradients within a bounded region                                        |
*\*Dimensional mana is exceptionally difficult to find, retain, and control. Its reported operations remain restricted to carefully bounded, structured work.*

| Availability    | Natural-source criterion                                                                                |
| --------------- | ------------------------------------------------------------------------------------------------------- |
| **Widespread**  | Unmanaged seeds and practical deposits frequently form under ordinary conditions                        |
| **Localised**   | Common favourable media or particular environmental conditions or event  are required                   |
| **Scarce**      | Specialised media or unusual sites are required; practical reservoirs are limited                       |
| **Exceptional** | Active maintenance or extraordinary conditions are required; reliable natural reservoirs are negligible |

The availability grade summarises the combined effects of background fluctuation, critical seed concentration, selective media, Detuning, and attainable conversion yield. It does not replace those measurements, and it may differ sharply between regions.

Attuned mana used to power a spell and perform its attributed operation is converted into Spent mana through Expenditure.

Operation boundaries and aspect ladders are collected in [[12 Attribute Theory|Attribute Theory]]. Material interactions, including selective and decaying media, are collected in [[13 Material Affinities|Material Affinities]].


**Attunement Theory** is the study of the processes by which Primed mana is converted into particular Attuned attributes, including their rates, efficiencies, waste ratios, and environmental dependencies.

**Attribute Theory** is the study of the operational and passive properties of individual mana attributes and their interactions with matter, fields, living systems, and other mana types.

**Permutation Thermaturgy** is the study of permutation loss, Waste mana, potential consumption, and the energetic or entropic consequences of mana permutation.
