Below is the authoritative guide on how the magic system should work.
This guide should be used to correct previously worked-on documents, including their usage of outdated nomenclature.

# Mana Flow

Mana is a field of discrete particles, each one being in one of **3 possible states** :

- **Primed** - charged with **unattuned potential**
- **Attuned** - charged with **attuned potential**, differentiated along multiple **mana attributes**
- **Spent** - uncharged, as its potential was consumed during permutation

Collectively, Primed, Spent, and the various Attuned mana attributes are known as **mana types**, and the process of converting from one of these to another is known as **mana permutation**. Permutation invariably follows one of these **3 permutation processes** :

| Permutation      | Process Formula                                                                   |
| ---------------- | --------------------------------------------------------------------------------- |
| **Attunement**\* | Primed => Attuned( attribute ) x ( 1 - Ratio ) + Spent x Ratio + Permutation Loss |
| **Expenditure**  | Attuned( attribute ) => Spent + Operation( attribute )                            |
| **Priming**\*\*  | Spent + Singularity => Primed                                                     |
*\*Attunement releases residual physical energy and disordered mana-field disturbances, collectively termed **permutation loss**.*

*\*\*Priming occurs exclusively around the singularity, which is the light source at the centre of the expanse.*

Mana particles are conserved through permutation, but their potential is not. Attunement always incurs some loss, while expenditure consumes the attuned potential required to perform an attributed operation.

Mana types interact with themselves and one another through repellent forces, pushing mana away from highly concentrated areas and towards less concentrated ones.

They are also affected by gravitational pull, with Spent mana being pulled upwards, where it eventually undergoes Priming, while the other states are pulled downwards at varying rates and pool in low-lying areas of the surface.

Different materials have distinct interactive properties with some or all mana types. Biological tissues, metals, crystals, and other materials may therefore attract, repel, channel, or retain mana to varying degrees.

Of all mana types, Primed mana is the most reactive with itself, other mana types, and mana-interactive matter, while Spent mana is the least reactive and is nearly inert. The properties of Attuned mana generally lie between these two extremes and vary by attribute.


**Flow Theory** is the study of mana movement under concentration gradients, repellent interactions, gravity, material affinity, and environmental conditions.

**Mana Hydrodynamics** is the applied study of large-scale mana currents, pooling, circulation, turbulence, and transport through natural or artificial channels.

# Mana Attunement

**Mana potential** is the capacity of a mana particle to perform an attributed operation. Physical energy may be created, redistributed, consumed, or conserved depending on the attribute involved.

**Attunement** is the process of converting Primed mana into Attuned mana. This process occurs naturally, at a rate dependent on the local concentration of the target Attuned mana relative to the concentrations of Primed mana and, to a lesser degree, Spent mana.

The greatest rates of **Background Attunement** are found in locales with high concentrations of Primed mana and low concentrations of Attuned and Spent mana. Existing Attuned mana biases nearby Primed mana towards the same attribute, making attunement partially self-propagating, though its rate diminishes as the local concentration of that attribute rises.

This conversion also generates an amount of Spent mana, called **Waste mana** in this context. The **Waste mana ratio**, which is the proportion of used Primed mana converted into Spent mana, depends on both the selected attribute and the attunement process. Faster processes are generally less efficient than slower ones.

Attunement can also be performed directly by a caster and is often one of the first exercises taught to novice magi. Doing so is rarely efficient in time, effort, or purity of results. As such, there exists a wide range of mana constructs dedicated to automating the attunement of Primed mana into specific attributes.

Already Attuned mana can be expended directly without first undergoing attunement, making it substantially more efficient and immediately useful than an equivalent supply of Primed mana. This advantage is offset by the difficulty of obtaining, separating, storing, transporting, and replenishing particular attributes, whose natural distributions are highly heterogeneous along the surface of the expanse.

Reservoirs of Attuned mana are therefore useful even without any associated executable spell assembly. A caster may draw directly from such a reservoir for Unstructured Casting, or supply it to a structured construct while omitting its usual Attuning components.

> *Reminder : Attunement refers to a permutation process, while an attribute refers to the differentiated potential produced by that process.*

Below are summary tables pertaining to the 11 known attuned **attributes** :

| Attribute      | Common Names                                | Operation Domain Description                                                                                                       |
| -------------- | ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Kinetic**    | Motion, Force, Heat, Explosion              | Change the momentum distribution of matter, whether uniformly or microscopically.                                                  |
| **Radiant**    | Light, Illusion, Cloaking, Optics           | Emit, absorb, redirect, or otherwise manipulate free photons.                                                                      |
| **Galvanic**   | Lightning, Magnetism                        | Change electric charges, currents, and quasi-static electromagnetic fields.                                                        |
| **Volumic**    | Pressure, Density, Compression, Expansion   | Modify the metric volume occupied by a bounded material system without directly changing its topology, mass, or internal momentum. |
| **Massic**     | Mass, Weight, Gravity                       | Modify an object's inertial and gravitational mass.                                                                                |
| **Cohesive**   | Structure, Shaping, Binding                 | Change which portions of matter are mechanically continuous without directly specifying their chemical composition.                |
| **Resonant**   | Linking, Observation, Divination            | Change the degree to which state changes in one system are detectable by, transmitted to, or correlated with another.              |
| **Mnemonic**   | Memory, Recording, Engraving, Scrying, Mind | Encode information into, and decode information from, the physical medium in which it is stored.                                   |
| **Temporal**\* | Acceleration, Preservation, Stasis          | Modify the local rate at which time progresses.                                                                                    |
| **Spatial**\*  | Portal, Dimension, Teleportation            | Modify the layout of space itself.                                                                                                 |
| ***Ontic***\*  | *Identity, Essence, Classification, Soul*   | *Modify what an object fundamentally is according to magical law.*                                                                 |

| Attribute      | Domain Type    | Reality Layer  | Operation Domain    | Waste Ratio | Persistence Mechanism                                              |
| -------------- | -------------- | -------------- | ------------------- | ----------- | ------------------------------------------------------------------ |
| **Kinetic**    | State          | Physical       | Momentum            | Low         | Imparted state                                                     |
| **Radiant**    | State          | Physical       | Photon field        | Low         | Active emission                                                    |
| **Galvanic**   | State          | Physical       | Electric field      | Low         | Usually active field; charge redistribution may persist            |
| **Volumic**    | State          | Emergent       | Volume, Pressure    | Medium      | Usually sustained unless natural structure supports the new volume |
| **Massic**     | State          | Physical       | Mass                | Medium      | Sustained                                                          |
| **Cohesive**   | Organisational | Emergent       | Connectivity        | High        | Structural                                                         |
| **Resonant**   | Relational     | Physical       | Coupling, Detection | High        | Anchored relationship                                              |
| **Mnemonic**   | Organisational | Emergent       | Information         | High        | Encoded state                                                      |
| **Temporal**\* | Organisational | Emergent       | Time rate           | Very High   | Sustained                                                          |
| **Spatial**\*  | Relational     | Emergent       | Spatial layout      | Very High   | Sustained                                                          |
| ***Ontic***\*  | *Ontological*  | *Metaphysical* | *Identity*          | *Extreme*   | *Metaphysical*                                                     |
*\*Little is known of these attributes, and what is known remains highly speculative and contested.*

Attuned mana used to power a spell and perform its attributed operation is converted into Spent mana through Expenditure.


**Attunement Theory** is the study of the processes by which Primed mana is converted into particular Attuned attributes, including their rates, efficiencies, waste ratios, and environmental dependencies.

**Attribute Theory** is the study of the operational and passive properties of individual mana attributes and their interactions with matter, fields, living systems, and other mana types.

**Permutation Thermaturgy** is the study of permutation loss, Waste mana, potential consumption, and the energetic or entropic consequences of mana permutation.

# Soul-Forms

A **soul-form** is a naturally occurring, self-organising mana structure produced through prolonged interaction between mana and an active biological nervous system, or another system exhibiting sufficiently similar organisation and activity.

Soul-forms are neither the source nor the container of consciousness. Thought, memory, personality, and subjective experience remain emergent properties of the physical nervous system. The soul-form instead develops around that system as a responsive magical structure, reflecting portions of its organisation and activity while providing the organism with a natural interface to mana.

Older traditions commonly refer to the soul-form as the **soul-shell**, based upon its protective function and apparent enclosure of the body. More recent scholarship generally considers this term incomplete, as the structure is neither a simple shell nor wholly external to the organism.

## Formation

Soul-forms arise when sustained patterns of neural activity repeatedly disturb and organise nearby mana.

The relationship is asymmetrical. Nervous activity shapes mana relatively quickly, while the resulting soul-form alters the nervous system only weakly and gradually. The soul-form therefore primarily reflects the organism that produced it rather than determining that organism's mind or identity.

Formation proceeds through cumulative interaction :

1. neural activity produces complex and recurrent electrical, chemical, and structural patterns
2. mana-interactive tissues weakly attract, repel, and redirect nearby mana
3. repeated activity causes mana to settle into partially stable configurations around neural pathways
4. those configurations become self-reinforcing through their continued interaction with the nervous system
5. the resulting structure gradually extends through the organism and develops a stable individual signature

A soul-form is not consciously designed, nor does it necessarily resemble a deliberately constructed scaffold. It is an **autogenic somatic construct** whose organisation emerges from sustained biological activity rather than formulaic declaration.

Newly formed soul-forms are weak, poorly differentiated, and highly dependent upon the nervous system that produces them. Their strength and complexity increase gradually with continued neural activity, development, and exposure to mana.

An organism entering a mana-rich environment without an existing soul-form may experience headaches, diffuse pressure, disorientation, disturbed sleep, transient sensory distortions, or unusual internal sensations as mana rapidly accumulates and begins organising around its nervous system.

As the initial formation period passes, acute symptoms generally diminish and are replaced by a less painful omnidirectional pressure-like awareness of nearby mana. The completed soul-form may remain weak for an extended period even after the organism begins perceiving mana.

**Animogenesis** is the study of the formation and maturation of soul-forms.

**Developmental Neurothaumaturgy** is the study of soul-form development across infancy, maturation, injury, and changing environments.

## Structure

A soul-form extends most strongly around the nervous system but gradually develops relationships with the rest of the body.

Its internal organisation reflects :

- the topology of the nervous system
- recurrent patterns of neural activity
- sensory and motor pathways
- autonomic regulation
- bodily boundaries
- long-established habits of neural activation
- persistent injuries or developmental irregularities

The soul-form does not contain a complete representation of the body or mind. It is a partial and continuously updated magical correlate of the organism's active neural organisation.

Its structure may be understood as containing several overlapping functional regions :

|Region|Function|
|---|---|
|**Neural core**|Closely follows the central and peripheral nervous systems and responds most strongly to neural activity|
|**Somatic lattice**|Extends through the body and helps distinguish the organism's own tissues from external matter|
|**Boundary field**|Resists foreign mana entering or directly operating upon protected tissues|
|**Sensorimotor fringe**|Interacts with nearby mana and permits limited perception and volitional manipulation|
|**Signature structure**|Encodes stable individual peculiarities produced by anatomy, development, and long-term neural activity|

These regions are descriptive rather than sharply separated anatomical parts.

Soul-forms are dynamic structures. Their precise organisation shifts continuously with activity, sleep, health, injury, emotional state, and magical exertion.

They are generally most active during waking consciousness and rapid-eye-movement sleep, when neural activity is complex and highly variable. They become calmer during ordinary sleep, anaesthesia, or unconsciousness, but do not disappear and continue to provide substantial magical resistance.

**Animic Morphology** is the study of soul-form structure and its relationship to anatomy and neural organisation.

## Individual Signature

Every mature soul-form develops a distinct **animic signature**.

This signature emerges from the unique physical structure and developmental history of the nervous system upon which it formed. Even highly similar organisms therefore possess distinguishable soul-forms.

An animic signature may reflect :

- broad species and anatomical traits
- individual neural topology
- long-standing sensorimotor habits
- persistent patterns of activity
- developmental history
- old injuries
- deeply ingrained behavioural dispositions
- the current physiological and cognitive state

The signature does not provide direct access to a person's complete thoughts or memories. It instead functions as a complex identifying pattern from which limited information may be inferred.

Animic signatures may be used for personal identification, authorised operator recognition, persistent Resonant links, ward configuration, diagnosis, or distinguishing an organism from an imitation.

Signatures change gradually over time but normally retain enough continuity for long-term recognition.

**Animic Signatury** is the study of soul-form identification, comparison, inheritance, and change.

**Forensic Animistics** is the applied study of soul-forms, animic signatures, remnants, injuries, and residues for the purpose of identifying individuals, reconstructing events, and resolving legal or investigative questions.

## Mana Perception and Manipulation

Soul-forms provide living organisms with a natural interface to mana.

Disturbances in nearby mana deform or excite the soul-form, and those changes weakly influence the nervous system. Through training, the organism learns to interpret these effects as **somatic mana sense**.

Conversely, deliberate neural and physiological activity alters the soul-form, allowing it to exert small forces upon nearby mana. Neural activity therefore deforms the soul-form, which in turn displaces, attracts, repels, condenses, or releases nearby mana.

The soul-form does not translate unrestricted thought into magical effects. It permits only low-level manipulations and the supply of bounded inputs to already defined construct interfaces.

Soul-forms differ greatly in sensitivity, range, precision, and coupling strength. These differences may arise from physiology, development, exposure, injury, or training.

The detailed use of soul-forms for conscious manipulation belongs to **Somaturgy** and **Casting Theory**.

## Animic Resistance

A soul-form protects its organism by resisting foreign magical intrusion. This protection is known as **animic resistance**.

The soul-form continuously associates the organism's tissues with one coherent internal system. Foreign mana attempting to enter, bind to, or operate directly upon those tissues must overcome the soul-form's accumulated mana, dynamic activity, and internal coherence.

Animic resistance impedes :

- direct Expenditure upon living tissue
- hostile reagent selection
- remote or indirect sensing
- forced anchoring
- unauthorised Resonant links
- alteration of internal bodily boundaries
- manipulation of neural or Mnemonic activity

This resistance is not absolute. It varies according to the strength and maturity of the soul-form, the concentration and type of attacking mana, the precision of the spell, the health and integrity of the target, existing Resonant relationships, and whether the target actively cooperates.

Consciousness and rapid-eye-movement sleep increase the soul-form's internal activity, making precise hostile manipulation more difficult. Unconsciousness reduces this activity but does not remove the soul-form's passive structure or accumulated mana and therefore does not leave the organism undefended.

## Primed-Mana Saturation

Animic resistance is reinforced by the accumulation of Primed mana within and around the soul-form.

Primed mana is highly reactive to other mana types. Dense Primed mana therefore disrupts incoming Attuned mana, interferes with controlled Expenditure, and makes foreign constructs more difficult to establish or maintain.

This effect may be reproduced artificially through **Primed-mana saturation**, in which an object, region, reservoir, or ward is deliberately flooded with Primed mana.

Primed-mana saturation may :

- raise the concentration required for Attuned mana to operate
- destabilise foreign mana flows
- increase permutation loss
- impede reagent binding
- obscure precise mana sensing
- disrupt construct formation
- provide passive resistance against Unstructured Casting

Soul-forms may therefore be understood partly as naturally maintained defensive reservoirs, though their organisation and responsiveness make them more effective than an equivalent quantity of unstructured Primed mana.

Excessive Primed-mana saturation can also interfere with allied spells, prevent beneficial magic, or produce uncontrolled local attunement if containment fails.

**Animic Defence Theory** is the study of soul-form resistance and its interaction with hostile or beneficial magic.

**Thaumaturgic Countermeasure Engineering** is the applied study of artificial mana saturation, resistant materials, wards, and other means of impeding magical operation.

## Neural and Neurological Analogues

Soul-forms are not restricted absolutely to biological nervous systems.

Any system capable of producing sufficiently complex, recurrent, integrated, and persistent patterns of activity may potentially attract and organise mana into a soul-like structure.

Such **neurological analogues** may include :

- artificial conductive lattices
- Galvanic signal networks
- recurrent Mnemonic systems
- living or semi-living tissues
- complex ward networks
- distributed sensor and control systems
- long-lived architectural assemblies
- symbiotic combinations of biological and artificial structures

Most such systems produce only weak or partial soul-forms.

The likelihood and complexity of formation appear to depend upon :

- density of internal signalling
- recurrence and feedback
- persistence over time
- integration between sensing and response
- internal differentiation
- a stable distinction between system and environment
- mana-attracting materials
- continued activity

A large and complex ward system surrounding a house may gradually develop a faint soul-form reflecting its boundaries, recurring signals, inhabitants, and maintenance history.

Such a structure would not necessarily be conscious or even behaviourally autonomous. It may nevertheless possess a recognisable signature, stronger internal cohesion, resistance to unfamiliar alterations, preferential response to familiar operators, persistent Resonant relationships, or rudimentary state retention.

These emergent structures are generally termed **proto-animic constructs** or **vestigial soul-forms**.

**Comparative Animistics** is the study of soul-form formation across biological, artificial, architectural, and distributed systems.

**Emergent Construct Theory** is the study of construct-like mana organisation arising without deliberate scaffold construction.

## Persistence, Remnants, and Decay

Soul-forms depend upon continued interaction with an active nervous system or neurological analogue.

When the underlying system becomes inactive, the soul-form loses the dynamic feedback that maintains its organisation. It does not normally vanish immediately, but begins a progressive process of simplification and decay.

The decaying structure left after the death or permanent inactivity of its source is known as a **soul-form remnant**.

The rate of decay depends upon :

- the maturity and strength of the soul-form
- ambient mana concentration
- surrounding mana types
- physical preservation of the nervous system
- Resonant anchors
- Mnemonic reinforcement
- containment within suitable materials or constructs
- the violence or suddenness of death

A soul-form remnant loses fine and recently maintained structures before its deepest and most stable patterns. It may temporarily retain an **animic echo** of the final activity of its source nervous system.

An animic echo is not a preserved consciousness. It is a degraded residue of neural organisation, recent state, habits, associations, and behavioural tendencies reflected within the soul-form at the time its biological support ceased.

A well-preserved remnant may contain fragmentary traces corresponding to the source's final hours or days. These traces may permit limited reconstruction of recent perceptions, repeated thoughts, emotional states, familiar persons or places, strong intentions, rehearsed behaviours, or final memories.

Recovering this information requires mapping the remnant onto a compatible active substrate. The result is necessarily approximate because the soul-form never contained a complete copy of the nervous system, decay removes and distorts information, and a new substrate interprets retained structure differently.

Attempting to preserve a deceased individual through a soul-form remnant is therefore more comparable to constructing a behavioural approximation from incomplete final records than to restoring the original mind.

**Thanatoanimistics** is the study of soul-form remnants and soul-form behaviour after biological death.

**Echo Reconstruction** is the study of extracting and interpreting residual information from soul-form remnants.

**Necromancy** is the applied use of deceased soul-forms, animic echoes, preserved nervous structures, and related constructs.

## Preservation and Transplantation

Soul-form preservation attempts to slow decay by replacing the stabilising influence once provided by the original nervous system.

Preservation may involve dense Primed-mana containment, Resonant anchoring, Mnemonic reinforcement, simulated recurrent activity, mana-attracting vessels, preserved neural tissue, or rapid attachment to another active substrate.

A soul-form may, under exceptional conditions, be detached from its original substrate and bound to a new one.

Successful transplantation requires :

- preservation of the soul-form during separation
- a sufficiently active receiving substrate
- correspondence between original and new sensory pathways
- correspondence between original and new motor outputs
- a coherent bodily boundary
- stable internal feedback
- gradual remapping of the soul-form to the new structure

Transplantation does not transfer the original mind. The receiving substrate produces its own cognition.

The transplanted soul-form may influence early development through inherited structure, signature, deeply ingrained tendencies, and residual echo, but the new substrate shapes the soul-form much more rapidly than the soul-form reshapes the substrate.

If a mature soul-form were transferred into a physically identical but neurologically fresh body, the result would therefore resemble a fresh developing mind more than a continuation or equal mixture of the original person.

A severe mismatch between soul-form and substrate may result in sensory confusion, motor dysfunction, unstable bodily boundaries, fragmented identity references, involuntary magical discharge, rapid degradation, or failure to bind.

**Animic Preservation** is the study of retaining soul-form structure after separation from its original substrate.

**Animic Transplantation** is the study of transferring soul-forms between biological or artificial substrates.

## Fragmentation and Derivation

A portion of a soul-form may be separated and encouraged to develop around a new substrate.

Such a **derived soul-form** begins largely as a clean slate. It does not contain a complete copy of the source and generally retains only coarse inherited characteristics, such as a related animic signature, broad mana affinities, deeply ingrained response tendencies, weak Resonant familiarity, or compatibility with wards keyed to the source signature.

Once attached to a new active substrate, the fragment develops primarily according to that substrate and its own experiences.

Derived soul-forms are often easier to stabilise than entirely artificial ones because they begin with an existing self-organising pattern. However, their inherited structure may impose limitations or biases that are difficult to remove.

Fragmentation may be performed destructively by removing part of an existing soul-form or more gradually by inducing a peripheral **animic bud** that can later be separated.

**Animic Derivation** is the study of fragmented, budded, copied, and otherwise source-derived soul-forms.

## Artificial Soul-Forms

A sufficiently complex neurological analogue may produce a soul-form without biological origin.

The substrate does not need to reproduce every property of a natural nervous system. It must, however, provide the organisational features required for sustained animic formation, including recurrent internal signalling, integrated sensory input, coordinated output pathways, internal feedback, persistent activity, adaptive relationships, differentiation between internal and external state, and a stable system boundary.

Simple feed-forward constructs and fixed spell routines generally fail to produce meaningful soul-forms. They may accumulate mana or develop stable signatures, but lack the recurrent integrated activity required for a developed animic structure.

Artificial soul-forms may be induced within golemic nervous analogues, Mnemonic lattices, Galvanic circuits, fluidic control networks, living hybrid tissues, distributed ward systems, or architectural control assemblies.

Creating a soul-form is not equivalent to creating consciousness.

A soul-form may provide sensorimotor integration, bodily identity, magical perception, and adaptive stability without the substrate being capable of sapience or subjective experience.

The production of a **sapience-capable substrate** would require a degree of complexity, integration, plasticity, and cognition that remains beyond known golemancy. No artificial system is universally accepted as having achieved genuine sapience.

**Synthetic Animistics** is the study of artificially induced soul-forms.

**Golemic Neurothaumaturgy** is the study of neurological analogues used to support soul-forms in artificial bodies.

## Soul-Form Injury

Soul-forms may be damaged through magical trauma, neurological injury, hostile Resonant interaction, excessive Primed-mana saturation, failed transplantation, or prolonged construct interference.

Possible consequences include :

- weakened magical resistance
- distorted mana perception
- involuntary mana attraction
- loss of fine manipulation
- phantom sensations
- altered animic signature
- unstable reagent boundaries
- susceptibility to foreign anchoring
- partial dissociation between body and soul-form
- persistent leakage or turbulence

Because the nervous system continually shapes the soul-form, minor damage may gradually repair itself. Severe or repeatedly reinforced damage may instead stabilise into **animic scarring**.

Soul-form injury does not necessarily imply psychological injury, though neurological and animic trauma often occur together because of their close interaction.

**Animic Medicine** is the study of soul-form health, injury, resistance, and its role in medical practice.

## Constraints

Soul-forms do not provide an unrestricted means of bypassing the broader magic system.

They cannot :

- generate mana
- perform attributed operations without Attuned mana
- encode arbitrary spell logic through desire alone
- preserve a complete mind after death
- restore destroyed neural information
- automatically heal complex tissue
- grant sapience to an inadequate substrate
- make a radically incompatible body easy to control
- replace construct interfaces, mana sourcing, or Expenditure
- perfectly reveal thoughts, memories, or identity

Soul-forms are natural mana interfaces, defensive structures, signatures, and substrates for limited retained organisation. Their usefulness derives from these specific functions rather than from being immaterial persons or universal metaphysical essences.

**Neurothaumaturgy** is the study of interactions between nervous activity and mana.

**Animic Theory** is the study of soul-form formation, structure, variation, persistence, and decay.

# Mana Constructs

Mana constructs are the building blocks of **structured spells**. They contain and direct mana, constrain its attributed operations, and allow those operations to respond to predefined conditions, enabling conditional or self-regulating behaviour.

Attuned mana may also be expended without a mana construct through **Unstructured Casting**. Constructs are therefore not required for an attribute to perform its primitive operation, but are required to make that operation precisely selected, bounded, directed, regulated, conditional, composable, repeatable, or safely automated.

There are **5 essential phases** to creating and triggering a functioning mana construct :

- **Construction** - **create** a stable **construct scaffold** out of Primed mana
- **Declaration** - **imbue** the construct with the desired **conditions** and **parameters**
- **Activation** - **seal** the construct and **enable** its future execution
- **Execution** - **enact** the construct's function according to its declaration
- **Termination** - gracefully **dissipate or deactivate** the construct without perturbing surrounding constructs

These phases may overlap, as with construction and declaration or execution and termination, but they are invariably present even when not readily visible.

| Magic Phase  | Computing Analogy                     |
| ------------ | ------------------------------------- |
| Construction | Allocate hardware/runtime environment |
| Declaration  | Define program and parameters         |
| Activation   | Compile, validate, seal, and arm       |
| Execution    | Run and supervise                     |
| Termination  | Deallocate, flush, and fail safely    |

**Construct Theory** is the general study of executable mana structures, their lifecycle, internal organisation, and capacity to constrain attributed operations.

Below is a more detailed breakdown of each phase :

### Construction

A mana construct must be contained within an insulating shell known as a **construct scaffold**. These scaffolds are built from Primed mana, which can form and maintain stable shapes when properly manipulated via **mana shaping**.

Similar shapes sometimes occur naturally in locations with high densities of Primed mana, but these occurrences generally lack the size, organisation, or internal structure required of proper construct scaffolds.

Primed mana incorporated into a scaffold is **geometrically constrained** and cannot readily undergo attunement. It retains its potential but is functionally isolated from ordinary flow. Scaffold damage releases this Primed mana, often causing uncontrolled local attunement or repulsive discharge.

Scaffolds are generally built as intricate patterns of lines connected at their ends. The simplest stable scaffolds correspond to the edges of the 5 Platonic solids, while larger or more capable constructs require increasingly elaborate geometries, often in the form of **fractal constructs**.

Scaffold topology is not merely representational. It constrains component capacity, structural stability, internal isolation, mana flow, concurrency, and fault containment. Its geometry therefore determines such properties as containment efficiency, the number of independent flow channels, maximum component density, feedback-loop stability, susceptibility to interference, dimensional embedding, and termination behaviour.

Within common scaffold models :
{ NOTE : VALIDATE }

- **vertices** serve as component junctions
- **edges** serve as mana and signal channels
- **faces** form isolation boundaries
- **enclosed volumes** provide buffering capacity
- **symmetry** distributes pressure and reduces drift
- **asymmetry** permits directional processing at the cost of stability


**Scaffold Engineering** is the study of scaffold topology, geometric stability, component capacity, isolation, flow channels, dimensional embedding, and methods of shaping Primed mana into functional structures.

**Construct Materials Science** is the study of physical materials used to attract, repel, channel, stabilise, shield, or host mana constructs.

### Declaration

An empty construct scaffold cannot enact a controlled magical effect. If improperly disassembled, it may do little more than release its Primed mana and disrupt nearby constructs. It must therefore be **imbued** with **construct components**, which embed specific functions into the scaffold and collectively define its behaviour during execution.

This imbuing process is known as **component declaration**. The declaration specifies which mana attributes may be expended operationally, which reagents may be selected, how inputs are processed, and under what conditions the construct may activate, regulate itself, or terminate.

A component's semantic role does not inherently require the correspondingly named mana attribute. A Timing component can measure ordinary elapsed time without Temporal mana, a Selection component can distinguish iron from wood without Ontic mana, and a Processing component can compare values without Mnemonic mana. Specialised attributes are required only when a component must exceed ordinary construct capabilities.

Mana used by a declared construct may therefore fulfil three broad roles :

- **Operational attributes** are expended to alter a reagent
- **Constructive mana** is constrained within the scaffold or its components to encode and stabilise declared behaviour
- **Auxiliary attributes** are expended by specialised components, such as Resonant mana used for remote or persistent sensing

Components may occur any number of times within a construct and are connected to one another and to the outside world according to both their internal interfaces and the scaffold's topology.

Commonly used components are described as **component archetypes**, which can be used to instantiate more specific **component variants**. This allows magi to reuse established designs rather than manually defining each component in every new construct.

Below is a list of the most commonly used component archetypes and their functions :

| Archetype       | Function                                                     |
| --------------- | ------------------------------------------------------------ |
| **Sourcing**    | Defines accepted mana sources and types                      |
| **Attuning**    | Defines the required attunement process, if any              |
| **Selection**   | Identifies eligible reagents                                 |
| **Bounding**    | Defines the affected region or quantity                      |
| **Anchoring**   | Determines what the construct follows or remains attached to |
| **Directing**   | Defines vectors, orientation, and propagation                |
| **Regulating**  | Defines magnitude and rate of operation                      |
| **Timing**      | Defines duration, delay, rhythm, or termination timing       |
| **Funnelling**  | Guides mana and signals within the construct                 |
| **Sensing**\*   | Inspects reagent or environmental properties                 |
| **Processing**  | Converts inspected properties into component behaviour       |
| **Warding**     | Detects, absorbs, or corrects disruptions                    |
| **Dissipating** | Handles excess mana and permutation loss                     |
| **Linking**     | Establishes declared interfaces between constructs           |
*\*A Sensing component may directly inspect properties of a reagent that relate to the construct's available mana attributes. Resonant mana is required for unrelated, indirect, remote, relational, or persistent inspection.*

Components exchange mana, values, references, and control signals through declared **interfaces**. Interfaces limit what may pass between components and constructs, preventing Linking components from acting as unrestricted channels. A component may expose one or more of the following interface categories :

{ NOTE : VALIDATE }

| Interface     | Carries                                                                    |
| ------------- | -------------------------------------------------------------------------- |
| **Flow**      | Mana of specified types and within specified throughput limits             |
| **Control**   | Activation, gating, synchronisation, and termination signals               |
| **Parameter** | Magnitudes, vectors, durations, rates, and other declared values           |
| **Reference** | Reagent, component, construct, or location references                      |
| **State**     | Sensed, processed, or retained information                                 |
| **Fault**     | Error conditions, warnings, and emergency termination signals             |

Interfaces may be directional or bidirectional and may be local, linked, or Resonantly extended. A connection is valid only when its categories, mana types, parameter dimensions, reference domains, and throughput tolerances are mutually compatible.

Information within and between constructs are carried and stored through **Primed mana packets**, which can travel along **Primed mana strands**. This information may take several forms :

- **constants**, fixed during declaration
- **inputs**, supplied during activation or execution
- **observations**, acquired by Sensing components
- **state**, retained between execution cycles
- **outputs**, transmitted to other components or constructs

Ordinary parameter values may be encoded through component configuration and scaffold geometry. Persistent or complex state generally requires a stable scaffold arrangement, a linked physical medium, or Mnemonic mana.


**Component Engineering** is the study of construct-component archetypes, variants, interfaces, combinations, and reusable component designs.

**Declarative Thaumaturgy** is the study of how conditions, parameters, references, state, and permitted behaviours are encoded into mana constructs.

**Thaumaturgic Informatics** is the study of information representation, transmission, storage, processing, and validation within constructs and spell assemblies.

### Activation

A properly built construct remains inert until it is **sealed**. Sealing fixes its declared components and interfaces, isolates its scaffold, and enables later execution. Modifying a sealed or active construct is possible only with great difficulty and risk, which makes sealing an important safeguard against accidental or hostile alteration.

Once sealed, the construct may be triggered by funnelling mana into it, supplying an activation signal, satisfying a declared condition, or receiving a command through a linked interface.

Constructs may be built for two primary lifecycle patterns :

- **Consumable constructs** execute once and dissipate during termination
- **Persistent constructs** return to a dormant sealed state after execution and remain available until damaged or deliberately disassembled

Persistent constructs may require periodic maintenance or replenishment to compensate for leakage, drift, and environmental interference.


**Activation Theory** is the study of sealing, arming, triggering, dormant states, and the transition between inert and executable constructs.

**Construct Security** is the study of preventing unauthorised activation, alteration, substitution, interference, or hostile access to sealed constructs.

### Execution

Execution is the **runtime behaviour** of an activated mana construct. A construct does not normally execute as one strictly linear sequence. Instead, its components form a reactive network of dependencies, flows, and conditions whose branches may operate once, repeatedly, continuously, concurrently, or only in response to faults.

Once execution begins :

- mana moves through available Flow interfaces;
- components activate when their prerequisites are satisfied;
- Sensing components update observations;
- Processing components derive state or control values;
- Regulating components alter throughput and output;
- operational components expend Attuned mana upon the selected reagent;
- termination conditions deactivate or dismantle the system.

The execution cycle can nevertheless be described through three broad stages :

{ NOTE LL : VALIDATE }
#### Initialisation

1. **Acquire** - Sourcing components draw or accept mana
2. **Validate** - The construct checks mana types, interface compatibility, reagent eligibility, and activation conditions
3. **Attune** - Primed mana is converted where required
4. **Address** - The reagent and affected region are resolved
5. **Parameterise** - Magnitude, direction, rate, duration, and other variable constraints are established

#### Active Operation

6. **Apply** - Attuned mana performs its primitive operation upon the reagent
7. **Observe** - Sensing components inspect relevant changes
8. **Process** - Processing components convert observations into state, parameters, or control signals
9. **Regulate** - Feedback modifies mana flow, parameters, or termination state
10. **Cycle** - Active branches repeat or remain sustained while their enabling conditions persist

#### Finalisation

11. **Discharge** - Expended mana becomes Spent mana, while excess mana and permutation loss are routed through Dissipating components
12. **Terminate** - Interfaces are released, active components are disabled, and the scaffold either dissipates or returns to dormancy

Not every construct performs every stage explicitly. Validation, Attunement, Observation, Processing, and Regulation may be absent from simple constructs, while persistent or adaptive constructs may perform parts of the active cycle continuously, at the cost of continuous mana expenditure.

**Repetition** is not normally declared as an instruction to repeat a procedure. Instead, it emerges from persistent flow paths, timed reactivation, feedback cycles, or external signals that continue until a termination condition is satisfied. This permits thermostatic spells, pulsed engines, periodic wards, tracking systems, and other self-regulating behaviour without requiring imperative execution.

**Independent branches** may execute concurrently. Scaffold topology determines whether branches have isolated mana supplies, compete for shared throughput, wait upon one another, or expend several attributes simultaneously.

Constructs may also be either :

- **stateless**, responding only to current inputs and conditions
- **stateful**, retaining prior observations, values, or activation history between cycles

Successful validation does not guarantee successful execution. Runtime conditions may change, reagents may leave their bounds, mana supplies may destabilise, feedback may diverge, or linked constructs may become unavailable. Such conditions must be routed into declared **Fault interfaces** and handled through **termination behaviour.**


**Execution Theory** is the study of runtime mana flow, component dependency, concurrency, feedback, state, and recurrent operation within active constructs.

**Thaumaturgic Control Theory** is the study of regulation, sensing, feedback stability, adaptive behaviour, oscillation, and fault-responsive control.

### Termination

A properly designed construct must account for all plausible **termination cases**, meaning the different ways execution may end either purposefully or accidentally. Failure to do so can collapse the scaffold, release contained mana, and propagate damage into surrounding constructs.

Proper termination is known as **graceful termination**, while improper termination is known as **erroneous termination**. Avoiding erroneous termination is one of the foremost concerns of spell design, as a malformed or uncontrolled spell may cause catastrophic damage, including loss of life.

Below is a list of frequent construct failure types that termination behaviour may need to handle :

| Failure Type             | Description                                                     |
| ------------------------ | --------------------------------------------------------------- |
| **Source starvation**    | Insufficient or interrupted mana supply                         |
| **Attribute mismatch**   | Supplied mana does not match component requirements             |
| **Interface mismatch**   | Connected inputs and outputs are mutually incompatible          |
| **Selection failure**    | A reagent cannot be resolved                                    |
| **Boundary leak**        | An operation escapes its declared region                        |
| **Regulation failure**   | Output exceeds declared or safe values                          |
| **Feedback oscillation** | Corrective loops repeatedly overcompensate                      |
| **Scaffold fracture**    | Construct topology loses containment                            |
| **Component deadlock**   | Components wait indefinitely upon one another                   |
| **Runaway execution**    | A termination condition becomes unreachable                     |
| **Dissipation overflow** | Waste or excess mana cannot be safely discharged                |
| **Link cascade**         | Failure propagates through linked constructs                    |
| **Semantic mismatch**    | A valid declaration does not perform the designer's intended task |

**Termination Theory** is the study of construct deactivation, scaffold dissipation, dormant return, fault containment, and safe disposal of excess mana.

**Thaumaturgic Safety Engineering** is the applied study of failure prevention, redundancy, emergency shutdown, fault isolation, and mitigation of magical accidents.

# Reagent Operations

A **reagent** is the physical or metaphysical system whose properties are directly operated upon by Attuned mana. Depending on the attribute and spell, a reagent may be an object, a bounded volume, several related objects, a field, a relationship, a process, a living organism, or another construct.

Spell design distinguishes between :

- the **selected reagent**, which is the system identified as eligible for an operation
- the **bounded reagent**, which is the exact portion or quantity upon which the operation is applied
- the **affected environment**, which changes only through the natural consequences of that operation

Mana performs **only the primitive operations** associated with its attributes. All unconstrained subsequent effects arise through ordinary physical, biological, or metaphysical processes.

For example, a Kinetic heating spell directly increases the disorganised microscopic momentum of a bounded reagent. Ignition, flame propagation, pressure changes, chemical reactions, and damage to nearby matter occur as natural consequences unless separately constrained by the spell.

This distinction prevents a spell from directly declaring a broad outcome such as _burn_, _heal_, or _destroy_. Instead, it must declare one or more primitive operations whose consequences produce the intended result.

## Expenditure Threshold

Attuned mana does not normally perform its primitive operation merely by being present near a compatible reagent. Expenditure begins only when the local concentration and coupling of one Attuned mana type exceed a **matter-specific expenditure threshold**.

These thresholds depend upon :

- the mana attribute
- the reagent's material composition and structure
- the area or volume across which mana is concentrated
- local Primed and competing Attuned mana concentrations
- the reagent's existing magical affinities
- the speed at which mana is condensed
- active wards, soul-forms, or other resistance

Natural concentrations rarely exceed these thresholds, preventing ordinary materials from spontaneously heating, compressing, fracturing, glowing, or otherwise undergoing attributed operations merely because mana is present.

A construct may lower, localise, or continuously maintain the effective threshold through precise sourcing, selection, bounding, and regulation. An Unstructured caster instead forces already Attuned mana above the threshold through direct condensation against a nearby reagent.

## Living Reagents

Living organisms are unusually difficult to affect directly because their soul-forms maintain coherent bodily boundaries and accumulate protective Primed mana.

This **animic resistance** raises expenditure thresholds within protected tissue, disrupts foreign mana concentration, and impedes hostile selection, binding, and sensing. It remains present during sleep or unconsciousness, though a highly active soul-form is somewhat harder to penetrate precisely.

Animic resistance can be imitated less efficiently through Primed-mana reservoirs, saturation wards, mana-attracting materials, or other systems that flood a protected volume with reactive Primed mana.

This makes crude internal attacks difficult. Heating a branch or shattering a stone through Unstructured Casting may be straightforward, while producing the same operation inside a living body requires vastly greater concentration, prolonged contact, a specialised structured spell, or prior disruption of the target's soul-form.

Cooperative targets may partially relax their resistance or accept a declared interface, but this does not make complex biological manipulation simple.

Cohesive mana can join or separate mechanically continuous matter, but cannot reconstruct the heterogeneous cellular organisation, vascular networks, biochemical gradients, immune function, or neural connectivity required for true healing. Practical magical medicine instead relies upon cauterisation, compression, immobilisation, temporary sealing, inert cohesive glues, removal of foreign matter, and support of natural recovery.

True restoration of complex tissue remains one of the foremost unsolved goals of magical medicine.


**Reagent Theory** is the study of reagent classification, selection, bounding, compatibility, susceptibility, and response to attributed operations.

**Consequential Thaumaturgy** is the study of how primitive magical operations propagate into larger physical, biological, and metaphysical results.

**Applied Attribute Dynamics** is the quantitative study of attributed operations within specific reagent classes and environmental conditions.

**Threshold Dynamics** is the study of the concentrations, couplings, and material conditions required to initiate and sustain Expenditure.

**Animic Medicine** is the study of soul-form health, injury, resistance, and its role in medical practice.

# Spell Composition

At their core, spells are **operationally unified systems** of one or more mana constructs, connected through declared interfaces and directed towards a shared process, effect, or termination condition. They are the defining products of Structured Casting and are distinct from the isolated attributed operations produced through Unstructured Casting.

A collection of nearby or interacting constructs does not necessarily constitute a single spell. Constructs form one spell when their activation, reagent bindings, execution dependencies, supervisory structure, or termination behaviour establish them as parts of one coherent operation.

While it is technically possible to accomplish any valid spell effect with a single sufficiently complex mana construct, such constructs rapidly become unwieldy and unstable. It is therefore preferable to **compose spells** by interconnecting more self-contained constructs, each with a dedicated purpose or task.

There are many ways to represent spells, but all rely upon **glyph systems**, abstract representations of construct components, scaffolds, interfaces, parameters, and other magical elements.

The only requirements of a valid glyph system are that its glyphs be reproducible, distinguishable from one another, and composable into **spell formulas**. Glyph systems need not be visual, as they may be expressed through symbols, text, speech, music, gesture, spatial arrangements, or other reproducible patterns.

Colloquially, the term _spell_ may refer to 5 distinct but interconnected concepts :

| Term                | Definition                                                                        |
| ------------------- | --------------------------------------------------------------------------------- |
| **Spell Formula**   | A specification of a spell encoded in a particular glyph system                  |
| **Spell Template**  | The notation-independent logical design represented by one or more formulas       |
| **Spell Assembly**  | The concrete network of mana constructs instantiated from a template              |
| **Spell Execution** | A particular activation and runtime instance of a spell assembly                  |
| **Spell Results**   | The attributed operations of an execution and their natural consequences          |

| Term      | Computing Analogy              |
| --------- | ------------------------------ |
| Formula   | Source representation          |
| Template  | Abstract program or design     |
| Assembly  | Instantiated runtime structure |
| Execution | Running process                |
| Results   | Output and side effects        |

**Spell Architecture** is the study of composing constructs into operationally unified assemblies through interfaces, shared reagents, dependencies, and supervisory structures.

**Compositional Thaumaturgy** is the study of how primitive operations and construct functions may be combined sequentially, concurrently, conditionally, or recurrently.

### Spell Interfaces

**Spell interfaces** are the declared boundaries through which components and constructs exchange mana, parameters, references, state, and control signals. They allow independently designed constructs to be composed without granting unrestricted access to one another's internal structure.

Spell interfaces use the same broad categories as component interfaces :

| Interface     | Typical Inputs and Outputs                                                 |
| ------------- | -------------------------------------------------------------------------- |
| **Flow**      | Primed, Attuned, or Spent mana; mana throughput; permutation loss          |
| **Control**   | Activation, gating, synchronisation, interruption, and termination signals |
| **Parameter** | Magnitudes, vectors, durations, rates, thresholds, and declared constants  |
| **Reference** | Reagents, locations, constructs, components, and bounded regions           |
| **State**     | Observations, processed values, retained state, and environmental conditions |
| **Fault**     | Warnings, error states, degraded operation, and emergency shutdown signals |

Interfaces may be required, optional, or conditional. They may expose fixed values, accept parameters supplied during activation, or transmit values produced during execution.

A connection is valid only when :

- the input and output interface categories match
- the transmitted mana types are accepted
- parameter dimensions and ranges are compatible
- reagent and construct references are meaningful to the receiver
- directionality is respected
- throughput remains within the tolerances of both interfaces

An invalid connection may prevent sealing, fail validation during activation, or produce erroneous execution if incompatibility emerges only at runtime.


**Interface Theory** is the study of compatible mana, parameter, control, reference, state, and fault connections between components and constructs.

**Thaumaturgic Systems Engineering** is the applied study of modular spell assemblies, subsystem integration, interface standards, verification, and whole-system behaviour.

### Spell Formulas

A **spell formula** is a reproducible **glyph-based encoding** of all or part of a spell template. It is a **representation of magical design** rather than a magic-bearing object in itself.

A formula may be written, engraved, spoken, sung, gestured, arranged spatially, or stored mechanically. Different glyph systems may encode the same spell template, and equivalent formulas may differ greatly in abstraction, precision, ordering, readability, ease of memorisation, suitability for enchanting, and resistance to transcription errors.

A complete formula may specify :

- scaffold topology
- construct count and organisation
- component archetypes and variants
- component parameters
- construct interfaces
- mana types, sources, and expected throughput
- reagent constraints
- activation conditions
- execution dependencies
- termination behaviour
- safety constraints

Not every formula is intended to encode a complete spell :

| Formula Type           | Description                                                               |
| ---------------------- | ------------------------------------------------------------------------- |
| **Complete**           | Contains enough information to instantiate the whole spell                |
| **Partial**            | Describes one construct, component group, or subsystem                    |
| **Parametric**         | Leaves declared values or references to be supplied during instantiation  |
| **Derived**            | Adapts or specialises an existing formula                                 |
| **Compressed**         | References recognised archetypes or sub-formulas rather than expanding them |
| **Diagnostic**         | Describes expected structure or behaviour for analysis and testing        |

A formula may be invalid in several different ways. It may be syntactically malformed within its glyph system, internally inconsistent, physically unrealisable, unsafe, dependent upon absent environmental conditions, or semantically valid while failing to perform its author's intended task.


**Glyphology** is the comparative study of glyph systems, their structures, semantics, notation conventions, and methods of representing magical designs.

**Formulaics** is the study of spell formulas, including their syntax, completeness, compression, derivation, transcription, interpretation, and validation.

**Thaumaturgic Philology** is the historical and comparative study of magical notation, terminology, formula transmission, and regional or linguistic variation.

### Spell Templates

A **spell template** is the notation-independent operational design shared by all equivalent formulas and assemblies that perform the same declared process.

A template defines :

- required constructs and their responsibilities
- component relationships
- required input mana types and permissible sources
- accepted reagent types
- parameters and their valid ranges
- required primitive operations
- inputs, outputs, and interface connections
- activation model
- execution dependencies and ordering constraints
- runtime behaviour
- output and completion conditions
- termination cases
- safety invariants

Templates may be fixed, parameterised, generic over a reagent class, generic over an attribute, or partially specialised.

For example :

> Transfer Kinetic momentum to a bounded object along a declared vector until a target velocity is reached.

This describes a spell template. A formula that fixes the reagent as a 2 kg iron sphere, the direction as northward, and the target velocity as 10 m/s describes a more specialised instantiation of that template.

Two spells may resemble one another without being equivalent in every respect :

- **Effect-equivalent spells** produce similar observable results.
- **Operation equivalent spells** perform the same primitive attributed operations.
- **Architecture equivalent spells** use the same construct organisation and interface graph.

For example, direct Kinetic excitation, Radiant absorption, and Volumic compression may all heat a reagent, but they are only effect-equivalent. Their primitive operations, reagent constraints, waste profiles, and risks remain distinct.

Templates may be **derived** by extending, constraining, or specialising an earlier design. A general Kinetic impulse template may therefore serve as the basis for projectile-launching, recoil-compensating, or self-correcting variants without requiring each design to be recreated from first principles.


**Template Theory** is the study of notation-independent spell designs, parameter schemas, genericity, specialisation, equivalence, and derivation.

**Formal Thaumaturgy** is the study of the logical validity, compatibility, completeness, and provable properties of spell templates and declarations.

### Spell Assemblies

A **spell assembly** is the concrete arrangement of one or more sealed mana constructs instantiated from a spell template.

An assembly includes :

- the location and topology of its constructs
- the links and interfaces between them
- active and dormant components
- contained and flowing mana
- reagent bindings
- runtime state
- scaffold and interface integrity
- anchoring, hosting, or ownership relationships

A spell assembly may exist without currently executing. An enchanted implement may contain a dormant assembly, a ward may contain a continuously active assembly, and a structured caster may build an ephemeral assembly immediately before activating it.

A memorised cantrip, by contrast, is a retained formula or template and does not become an assembly until instantiated.

An assembly retains its identity while its declared operational purpose and supervisory structure remain continuous, even if individual components or constructs are repaired, replaced, or reconfigured. Alterations that change its governing process or sever its shared execution structure produce a new assembly.

Assemblies may be classified by architecture :

| Assembly Type   | Description                                                                  |
| --------------- | ---------------------------------------------------------------------------- |
| **Monolithic**  | Consists of a single mana construct                                          |
| **Modular**     | Uses several specialised constructs with declared interfaces                 |
| **Distributed** | Separates its constructs across multiple locations                           |
| **Nested**      | Contains constructs that activate, host, or supervise subordinate assemblies |
| **Recursive\*** | Produces or reconstructs assemblies based upon its own template              |
*\*Recursive assemblies are theoretically possible but are difficult to constrain, highly susceptible to compounding error, and generally disused outside of formal research.*

Complex assemblies may be orchestrated through a central supervisory construct, distributed peer coordination, sequential dependencies, event-driven activation, or continuous shared feedback. Their orchestration is part of the spell template rather than an incidental consequence of physical proximity.


**Assembly Engineering** is the study of instantiated construct networks, their topology, anchoring, orchestration, integrity, repair, and persistent operation.

**Distributed Thaumaturgy** is the study of spatially separated constructs, Resonant links, synchronisation, propagation delays, partial failure, and distributed control.

### Spell Execution

A **spell execution** is a particular activation and runtime instance of a spell assembly.

While construct execution describes the behaviour of one scaffold and its components, spell execution describes the coordinated behaviour of the entire assembly. It determines when constructs activate, how they exchange inputs and outputs, how shared reagents and mana sources are resolved, and how local failures affect the wider spell.

A spell execution forms a directed graph of mana flows, parameter dependencies, state changes, and control signals. Its branches may occur sequentially, concurrently, recurrently, or conditionally. The graph may remain fixed throughout execution or change among predefined configurations in response to observations.

Spell execution is generally divided into :

- **Assembly initialisation**, during which shared sources, interfaces, parameters, and reagent bindings are validated;
- **Coordinated operation**, during which constructs perform and regulate their assigned tasks;
- **Assembly finalisation**, during which outputs are completed, faults are contained, and constructs terminate or return to dormancy in a safe order.

The failure of one construct does not necessarily terminate the entire spell. Fault interfaces may allow the assembly to isolate a damaged branch, substitute a redundant construct, degrade its output, or initiate graceful termination. Unhandled failures may instead cascade through shared mana sources, references, or control links.

Each activation of the same assembly constitutes a distinct execution, even when its formula, template, constructs, and nominal parameters remain unchanged. Environmental conditions, reagent state, and prior assembly wear may therefore cause repeated executions to produce slightly different results.


**Spell Dynamics** is the study of coordinated runtime behaviour across an entire spell assembly.

**Thaumaturgic Orchestration** is the study of activation ordering, shared state, supervisory control, redundancy, and fault propagation among linked constructs.

### Spell Types

Spell types are not exclusive natural categories. They are independent classifications describing different aspects of a spell's operation, architecture, reagent relationship, or use.

#### By Duration

| Type             | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| **Instantaneous** | Performs one bounded operation and terminates                   |
| **Sustained**     | Remains active while continuously supplied                      |
| **Persistent**    | Remains instantiated between executions                         |
| **Periodic**      | Executes at declared intervals                                  |
| **Latched**       | Enters and retains a state until explicitly reset or terminated |

#### By Control Behaviour

| Type            | Description                                                               |
| --------------- | ------------------------------------------------------------------------- |
| **Fixed**       | Performs one predefined operation                                         |
| **Conditional** | Executes only when declared conditions are satisfied                      |
| **Regulated**   | Uses feedback to maintain a target state                                  |
| **Adaptive**    | Selects among predefined behaviours according to observations             |
| **Stateful**    | Allows current behaviour to depend upon retained execution history         |

#### By Architecture

|Architecture Type|Description|
|---|---|
|**Monolithic**|The spell is contained within a single mana construct, with all sourcing, processing, regulation, and operational functions sharing one scaffold.|
|**Modular**|The spell is divided into several specialised constructs, each handling a distinct function and communicating through declared interfaces.|
|**Distributed**|The spell's constructs are physically separated across multiple locations while remaining part of the same operationally unified assembly.|
|**Hierarchical**|The spell is organised into supervisory layers, with higher-level constructs coordinating, activating, or regulating lower-level constructs.|
|**Networked**|The spell consists of multiple interconnected constructs or assemblies that exchange mana, state, references, or control signals without necessarily relying on a single central supervisor.|

#### By Reagent Relationship

| Type                 | Description                                                    |
| -------------------- | -------------------------------------------------------------- |
| **Directed**         | Acts upon a separately selected reagent                        |
| **Anchored**         | Acts upon what the spell or one of its constructs is attached to |
| **Volumetric**       | Acts throughout a bounded region                               |
| **Relational**       | Acts upon a link or relationship between reagents              |
| **Self-referential** | Acts upon the construct, assembly, instrument, or caster itself |

#### By Hosting Substrate

| Type              | Description                                                        |
| ----------------- | ------------------------------------------------------------------ |
| **Ephemeral**     | Exists only for one execution                                      |
| **Somatic**       | Hosted or continuously maintained by a living body                 |
| **Instrumental**  | Hosted within a portable or purpose-built artefact                 |
| **Architectural** | Embedded into a structure or fixed installation                    |
| **Environmental** | Anchored to terrain, ambient mana flows, or naturally occurring media |

Practical traditions also classify spells in **schools** by their intended results, such as offensive, defensive, sensory, transformative, transportive, communicative, or industrial magic. These are social and functional categories rather than divisions inherent to mana or construct theory.


**Thaumaturgic Taxonomy** is the study of spell classification according to duration, control behaviour, architecture, reagent relationship, hosting substrate, and practical use.

**Comparative Spellcraft** is the study of equivalent or competing spell designs across different attributes, architectures, traditions, and applications.

# Mana Casting

{ NOTE : VALIDATE }

**Mana casting** is the deliberate manipulation and Expenditure of mana to perform attributed operations upon one or more reagents.

Mana casting is divided into two broad methods :

- **Unstructured Casting** directly condenses already Attuned mana against a nearby reagent until its matter-specific expenditure threshold is exceeded
- **Structured Casting**, also called **spell casting**, instantiates or uses one or more mana constructs to select, constrain, coordinate, and regulate Expenditure

Unstructured Casting is comparable to entering individual low-level commands one at a time. Structured Casting is comparable to writing, compiling, and executing a script or program whose operations can be composed, parameterised, repeated, and supervised.

The distinction concerns the presence of executable construct logic rather than the skill or intention of the operator. Unstructured Casting may still require substantial training, while some structured spells can be activated by an untrained user through an instrument.

People capable of intentionally manipulating mana are most commonly called **magi** ( singular : **magus** ), though _mage_, _magician_, _wizard_, _witch_, _invocater_, and _caster_ are also used according to region, tradition, and profession.

## Casting Roles

A casting process may involve several functional roles. These roles need not correspond to separate physical objects, and a single caster, organ, instrument, or construct may fulfil several of them simultaneously.

|Casting Role|Function|
|---|---|
|**Source**|Provides Primed or Attuned mana to the spell assembly|
|**Reservoir**|Stores or buffers mana before or during execution|
|**Conduit**|Carries mana between sources, constructs, instruments, and reagents|
|**Attuner**|Permutes Primed mana into one or more required attributes|
|**Host**|Physically or somatically maintains a structured spell assembly|
|**Operator**|Manipulates mana directly or supplies parameters, references, activation, or supervision|
|**Reagent**|Receives the casting's attributed operations|
|**Sink**|Receives Spent mana, excess flow, or permutation loss|

These casting roles describe the participants and physical pathways involved in casting. They are distinct from **construct components**, which define the internal behaviour of an individual mana construct and are absent from purely Unstructured Casting.

For example, an Unstructured caster may simultaneously serve as operator and conduit while drawing from an external reservoir. A structured caster may additionally act as a temporary host, while an instrument acts as reservoir, attuner, and persistent host.

A living operator normally manipulates mana through their soul-form, whose sensorimotor fringe converts trained neural activity into low-level attraction, repulsion, condensation, release, and directional bias.

## Casting Dimensions

Structured casting methods are most rigorously described through three independent dimensions :

1. the **authoring source** from which the spell logic originates
2. the **execution substrate** upon which the assembly is hosted
3. the **supervision mode** by which execution is controlled

These dimensions may be combined freely where physically and logically compatible.

### By Authoring Source

|Authoring Source|Description|
|---|---|
|**Instinctive**|Spell logic is biologically encoded and instantiated through inherited anatomy, development, or instinctive behaviour.|
|**Reflexive**|A previously learned formula or template is reconstructed from procedural memory with little or no conscious alteration.|
|**Structured**|The spell is consciously assembled, modified, derived, or supervised by a caster who understands its internal logic.|
|**Inherited**|Spell logic is copied from an external specification, retained assembly, instrument, environment, or other pre-existing source.|

The authoring source describes where the executable design comes from, not where it is ultimately hosted. An inherited formula may be reconstructed somatically, while a structured caster may design a spell that is later hosted instrumentally.

### By Execution Substrate

| Execution Substrate | Description                                                                                                   |
| ------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Somatic**         | The spell assembly is generated, hosted, or continuously maintained by a living body or mind.                 |
| **Instrumental**    | The assembly is hosted within an artefact, implement, device, or other purpose-built object.                  |
| **Architectural**   | The assembly is embedded into a building, vessel, fortification, road, or fixed installation.                 |
| **Environmental**   | The assembly is anchored to terrain, ambient mana flows, naturally occurring structures, or local conditions. |
| **Distributed**     | The assembly is divided across several linked substrates or locations.                                        |

A distributed spell may combine several other substrates. For example, an architectural ward may use environmental anchors, instrumental reservoirs, and somatic supervision.

### By Supervision Mode

|Supervision Mode|Description|
|---|---|
|**Direct**|An operator continuously supplies parameters, regulation, or control during execution.|
|**Triggered**|An operator initiates the spell, after which its declared behaviour proceeds without continuous supervision.|
|**Conditional**|Execution begins, changes, or terminates when declared sensed conditions are satisfied.|
|**Continuous**|The assembly remains in an active regulatory state for as long as its required mana and conditions persist.|
|**Adaptive**|The assembly selects among predefined behaviours or parameters in response to observations and retained state.|
|**Autonomous**|The assembly performs its declared function without routine external intervention, including its own regulation and ordinary fault handling.|

Supervision does not grant a spell unrestricted intelligence. Conditional, Adaptive, and Autonomous spells remain limited to their declared observations, state, interfaces, and possible responses.

## Casting Archetypes

Every individual casting may be described through the preceding dimensions. Nevertheless, several recurring combinations are recognised as conventional **casting archetypes**.

| Casting Archetype        | Typical Classification           | Description                                                                                                                                         |
| ------------------------ | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Unstructured Casting** | Non-formulaic + Somatic          | An operator directly condenses available Attuned mana against a nearby reagent until its expenditure threshold is exceeded.                         |
| **Wild Casting**         | Instinctive + Somatic            | A living system biologically generates and executes a narrow spell assembly through specialised anatomy and instinctive mana control.               |
| **Reflexive Casting**    | Reflexive + Somatic              | A caster reconstructs and activates a memorised spell pattern through trained procedural memory and external helper cues.                         |
| **Structured Casting**   | Structured + Usually Somatic     | A caster consciously assembles, modifies, derives, or supervises a spell according to understood construct logic.                                   |
| **Instrumental Casting** | Usually Inherited + Instrumental | A pre-existing artefact hosts and executes most or all spell logic, while its user supplies only permitted inputs, mana, references, or activation. |

These archetypes are neither exhaustive nor mutually exclusive. A structured caster may work through an instrument, a wild-casting organism may incorporate mineral structures, and an instrumental assembly may require direct somatic supervision. Unstructured Casting sits partly outside the authoring-source taxonomy because it instantiates no formula or spell assembly.


**Casting Theory** is the study of how spell assemblies are instantiated, hosted, supplied, parameterised, activated, and supervised.

**Praxeothaumaturgy** is the applied study of practical casting technique, operator behaviour, efficiency, reliability, and performance under real conditions.

## Unstructured Casting

**Unstructured Casting** is the direct Expenditure of already Attuned mana without the use of a declared mana construct.

The caster uses their soul-form to gather and condense one mana attribute against a nearby reagent until its matter-specific expenditure threshold is exceeded. Once triggered, the Attuned mana performs its primitive operation according to its attribute and the local relationship between mana and reagent.

Unstructured Casting does not permit the caster to declare a broad desired result. The operator can only exert coarse control over :

- which nearby reagent is contacted
- the approximate point or surface of application
- how much Attuned mana is condensed
- whether the mana is added or withdrawn where the attribute permits it
- a crude directional bias where the operation naturally supports one
- when the caster stops supplying mana

Unstructured Casting is normally limited to touch or near-touch range. Direct somatic control weakens rapidly with distance, while the absence of Selection, Bounding, Directing, Regulating, and Sensing components makes remote application unreliable.

The method is easiest with abundant, stable, familiar attributes and simple reagents. Kinetic and Radiant mana are therefore the most common attributes used in this manner, while rare, unstable, or weakly understood attributes are seldom handled unstructured.

Typical Unstructured operations include :

| Attribute | Typical Unstructured Operations |
| --- | --- |
| **Kinetic** | Heat or cool a touched object, induce vibration, apply a crude point compression, crack brittle matter, or produce a short shove |
| **Radiant** | Make a touched object glow, dim a small illuminated surface, emit a flash, or crudely alter colour |
| **Galvanic** | Charge or discharge an object, create a spark, or weakly magnetise a compatible material |
| **Volumic** | Compress a soft material, expand a confined gas, or produce a local pressure pulse |
| **Massic** | Temporarily make a touched object heavier or lighter while mana remains concentrated |
| **Cohesive** | Widen an existing crack, weakly join compatible surfaces, or crudely separate brittle continuous matter |
| **Resonant** | Establish a weak short-lived coupling between touching or strongly familiar systems |

Mnemonic, Temporal, Spatial, Ontic, and other rare or unstable attributes are not normally suitable for Unstructured Casting. Even where direct Expenditure is theoretically possible, practitioners seldom possess sufficient access, familiarity, or control to exceed the relevant threshold safely.

Directional force is possible with Kinetic mana, but is significantly harder than heating, cooling, vibration, compression, or shattering. A shove can be produced by concentrating momentum transfer at one surface, but sustained telekinesis, controlled trajectories, levitation, and precise force distribution require structured Direction, Selection, Regulation, and feedback.

Unstructured Casting is often highly efficient for small immediate tasks when the correct Attuned mana is already available, as it incurs no scaffold or declaration cost. It becomes inefficient when the caster must first attune Primed mana manually, compensate for leakage, overcome resistance, or repeatedly reproduce a precise result.

Its primary limitations are :

- dependence upon locally available or stored Attuned mana
- touch or near-touch range
- poor reagent discrimination
- imprecise boundaries
- weak directional control
- no automatic feedback or termination
- inability to compose several operations reliably
- high danger when large concentrations are used
- strong interference from Primed-mana saturation and soul-forms

Unstructured Casting is widely treated as an ordinary practical skill rather than a spell tradition. Heating tinder, cooling a cup, making a walking stick glow, discharging static, or cracking a brittle object are often described simply as things a mana-sensitive person can learn to do.

Reservoirs greatly extend its usefulness. A container of pre-Attuned mana may function as a general-purpose supply even without containing a spell assembly, though each reservoir remains limited by its stored attribute, capacity, leakage, transport requirements, and need for replenishment.

**Unstructured Casting Theory** is the study of direct, construct-free Expenditure and its limits.

**Threshold Dynamics** is the study of the concentrations, couplings, and material conditions required to initiate and sustain Expenditure.

## Wild Casting

**Wild Casting**, also called **Instinctive Casting**, is the biological generation and execution of a spell assembly without conscious formulaic construction.

Wild-casting organisms possess anatomical, biochemical, crystalline, symbiotic, or otherwise biological structures capable of producing fixed scaffolds and declarations. These structures contain no necessary symbolic notation because their physical organisation and instinctive soul-form activity directly generate the required construct architecture.

Wild casting is most often observed in animals, though certain plants, fungi, colonies, bacteria, and composite or artificial organisms also display comparable phenomena. Some systems rely upon a single specialised organ, while others distribute casting functions across tissues, mineral inclusions, symbionts, developmental structures, or several cooperating organisms.

Wild casting assemblies are generally narrow, strongly constrained, and specific to particular reagents or environmental conditions. Within the circumstances for which they evolved, however, they may be extremely rapid, reliable, and mana-efficient.

Common biological adaptations include :

- organs that gradually accumulate a specific Attuned mana
- tissues that stabilise simple scaffold geometries
- reflexes that trigger a fixed discharge under threat
- structures that draw upon ambient mana flows
- distributed tissues that collectively perform sourcing, attunement, and regulation
- temporary organs that function only during particular life stages or seasons


**Magical Physiology** is the study of biological structures that attract, store, attune, shape, or expend mana.

**Evolutionary Thaumaturgy** is the study of how wild-casting traits arise, specialise, and interact with ecological pressures.

### Strengths

- extremely rapid activation
- reliable under stress
- integrated with ordinary anatomy and behaviour
- potentially efficient within its evolved function
- usable without sapient understanding

### Limitations

- narrow range of valid reagents and effects
- little or no conscious parameterisation
- poor composability
- difficult to alter through training
- often inefficient or unstable outside evolved conditions
- vulnerable to injury, disease, developmental defects, and environmental disruption

Reports of sapient children performing Wild Casting without identifiable specialised anatomy remain disputed. Proposed explanations include overlooked developmental structures, spontaneous reflexive reconstruction, symbiotic influence, or misidentified environmental spells.

## Reflexive Casting

**Reflexive Casting**, commonly called **Cantrip Casting**, is the reconstruction of a memorised spell template through trained procedural memory and the facultative use of external queues, such as grimoires, scrolls, or pseudoglyphs.

The caster does not preserve a continuously existing construct within the mind. Instead, training establishes a reproducible neural, soul-form, and sensorimotor pattern through which the necessary scaffold, declaration, interfaces, parameters, activation, and termination behaviour may be rapidly reinstantiated.

Reflexive casting is to structured casting what executing a rehearsed procedure is to designing or modifying that procedure.

Most reflexive spells are **cantrips** : standardised, overconstrained spell templates designed for safe and repeatable public use. Their accepted mana types, reagent classes, parameter ranges, throughput, and termination behaviour are deliberately limited.

A reflexive caster may normally adjust only the inputs exposed by the cantrip's template, such as :

- reagent selection
- direction
- magnitude within a safe range
- duration
- activation timing
- selection among a small number of predefined modes

Intent does not generate new spell logic. It acts only as a trained control signal used to supply these admissible inputs.

The practical number of cantrips a caster can retain depends upon their similarity, complexity, training, and frequency of use. Cantrips with closely related scaffold or activation patterns interfere more strongly than highly distinct ones.

Poorly practised cantrips may undergo **pattern drift**, in which the caster's reconstruction gradually diverges from the original template. This produces regional variants, folk adaptations, inefficient forms, incompatible traditions, and occasionally dangerous malformed executions.

Some authorities in the expanse restrict the use of magic to certified individuals, so as to combat dangerous drifting of cantrips and other easy-to-access, hard-to-master spells, to various degrees of success.

### Strengths

- comparatively fast
- reliable after sufficient practice
- accessible without advanced theory
- suitable for daily and professional routines
- safer than unconstrained structured casting
- easily standardised through education

### Limitations

- restricted parameter ranges
- little structural flexibility
- poor composability between separate cantrips
- mental and somatic fatigue
- interference between similar memorised patterns
- gradual drift without regular practice
- dependence upon inherited designs that the user may not understand

Knowing two cantrips does not normally permit their direct combination. A caster who knows separate Heating and Launch cantrips cannot simply merge them into a flying incendiary projectile unless the original templates expose compatible interfaces or the caster enters the domain of Structured Casting.


**Somaturgy** is the study of somatic and cognitive mana manipulation, including procedural reconstruction, casting fatigue, pattern interference, and trained reflexes.

**Thaumaturgic Pedagogy** is the study of teaching, memorisation, practice, correction, and safe transmission of casting patterns.

## Structured Casting

**Structured Casting** is the conscious construction, modification, derivation, or supervision of a spell assembly by a caster who understands its components, interfaces, parameters, and execution behaviour.

Structured casters may work from existing formulas, adapt inherited templates, combine recognised component variants, or design original constructs. Structured casting therefore encompasses a broad continuum of expertise rather than a single level of mastery.

Its common practices include :

| Practice             | Description                                                                           |
| -------------------- | ------------------------------------------------------------------------------------- |
| **Composition**      | Arranging established components and constructs into a compatible assembly            |
| **Parameterisation** | Safely modifying exposed constants, ranges, references, or thresholds                 |
| **Derivation**       | Adapting a known template to a new reagent, attribute, source, or operating condition |
| **Refactoring**      | Replacing or reorganising components while preserving the spell's declared operation  |
| **Original design**  | Producing a novel template or construct architecture                                  |
| **Live shaping**     | Modifying or redirecting a construct during activation or execution                   |
| **Diagnostics**      | Inspecting, testing, isolating, and repairing malformed or degraded constructs        |
| **Supervision**      | Continuously regulating a complex, unstable, or partially autonomous execution        |
| **Maintenance**      | Realigning an activated spell assembly towards its intended state                      |

A novice structured caster may be capable of adjusting a known reagent boundary or replacing a standard Sourcing component while remaining unable to design a stable regulator or original feedback system.

**Glyph systems** are the principal pedagogical and analytical tools of Structured Casting. They permit spell logic to be represented in a reproducible form suitable for inspection, communication, derivation, and criticism. Glyphs remain abstractions rather than sources of magical efficacy.

### Strengths

- highly flexible
- capable of composing several primitive operations
- capable of producing novel spells
- permits adaptation to unusual reagents and environments
- forms the basis of research, diagnostics, enchanting, and advanced invocation

### Limitations

- cognitively demanding
- slower than rehearsed or fixed methods
- sensitive to interruption and distraction
- dependent upon theoretical and practical education
- capable of subtle semantic errors
- dangerous when performed upon active or unstable constructs


**Constructive Thaumaturgy** is the practical discipline of designing, composing, modifying, and supervising spells through conscious construct manipulation.

**Spellcraft Methodology** is the study of derivation, refactoring, diagnostics, testing, and reproducible spell development.

## Instrumental Casting

**Instrumental Casting** is the use of an external artefact or installation to host and execute part or all of a spell assembly.

The user may provide mana, activation, reagent references, direction, magnitude, or a choice among predefined modes, while the instrument performs the construct operations assigned to it.

Instrumental Casting ranges from supportive tools that offload one component from a structured caster to autonomous engines that perform repeated regulated work without routine supervision.

Intent in Instrumental Casting is not an executable statement of desired outcome. It is a trained or mechanically interpreted control signal used to select among declared pathways and provide permitted parameters. Somatic instruments usually receive such signals through interfaces designed to couple with the user's soul-form. An instrument cannot infer an unspecified spell from what its user wishes to happen.

Not every mana instrument performs structured casting. Reservoirs, conduits, and attuners may instead provide pre-Attuned mana for Unstructured Casting without containing an executable spell assembly.

### Strengths

- repeatable
- usable by non-specialists
- easier to standardise and regulate
- capable of storing persistent assemblies
- scalable into warfare, transport, architecture, and industry
- less dependent upon the user's theoretical knowledge

### Limitations

- restricted to built-in interfaces and functions
- expensive to design and manufacture
- susceptible to physical damage, drift, and sabotage
- requires mana supplies, maintenance, and waste management
- often less adaptable than a structured caster
- may conceal faults from users unable to inspect its internal design


**Instrumental Thaumaturgy** is the study of artefacts and installations that host, assist, regulate, or execute spell assemblies.

**Enchantment Engineering** is the study of anchoring persistent or reconstructible constructs to physical hosts.

## Casting Practices

Casting archetypes describe how a spell is instantiated and supervised. **Casting practices** describe the practical activity being performed.

### Invocation

**Invocation** is the temporary instantiation and execution of a spell by a caster.

Invocations are commonly somatic and ephemeral, though they may employ focuses, reservoirs, catalysts, or other supporting instruments. Reflexive cantrips and most direct structured spells are forms of invocation.

An invocation normally ends when its assembly dissipates or its persistent constructs are deliberately released.

### Enchanting

**Enchanting** is the process of anchoring a spell formula, template, construct, or assembly to a durable physical host.

Traditional enchantments are often hardwired into their artefacts. Their scaffolds, component variants, interfaces, and parameters are fixed during manufacture, making them reliable but difficult to modify.

More advanced enchanting methods may permit :

- interchangeable component modules
- resettable parameters
- writable Mnemonic storage
- replaceable or repairable constructs
- standardised interfaces
- self-testing and fault reporting
- programmable or reconfigurable assemblies

Engraved glyphs are commonly used to guide construction, maintenance, and inspection, but the physical glyphs are not themselves the source of magical function.


**Enchantment Engineering** is the study of anchoring persistent or reconstructible spell logic to physical hosts.

### Instrumentation

**Instrumentation** is the design and use of artefacts that support, host, regulate, or perform magical operations.

Magical instruments may be classified independently by their function, form, and operational behaviour.


**Instrumental Thaumaturgy** is the study of artefacts and installations that host, assist, or execute spell assemblies.

#### By Function

| Instrument Function | Description                                                                                                                  |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Implement**       | Hosts and executes a narrow spell or set of closely related spells                                                           |
| **Reservoir**       | Stores and releases mana of accepted types for structured or Unstructured Casting                                             |
| **Attuner**         | Converts Primed mana into one or more specified attributes                                                                   |
| **Catalyst**        | Improves the rate, efficiency, purity, or stability of a permutation or construct process without supplying its primary mana |
| **Focus**           | Hosts reusable components or interfaces while leaving spell-specific decisions to a caster                                   |
| **Ward\***          | Detects, inhibits, redirects, absorbs, or responds to declared disruptions                                                   |
| **Engine**          | Performs repeated or sustained magical work through a persistent regulated assembly                                          |

*\*A ward is a functional classification rather than a particular physical form. A ward may be realised as an implement, architectural installation, environmental assembly, or distributed array.*

#### By Form

|Instrument Form|Description|
|---|---|
|**Handheld**|Designed to be held and directed by one user|
|**Worn**|Integrated into clothing, armour, jewellery, or the body|
|**Embedded**|Installed into another object, machine, or vehicle|
|**Architectural**|Integrated into a building or fixed installation|
|**Array**|Distributed across several linked hosts, surfaces, or locations|

#### By Operational Role

|Operational Role|Description|
|---|---|
|**Autonomous**|Executes its declared functions without routine operator control|
|**Supportive**|Offloads components or improves the casting of another operator|
|**Supervisory**|Coordinates or regulates subordinate constructs or instruments|
|**Protective**|Detects and responds to hazards or hostile interference|
|**Distributive**|Routes mana, parameters, references, or control signals across an assembly|

### Engine Casting

**Engine Casting** is the sustained or repeated operation of persistent instrumental assemblies to produce useful work.

A magical engine normally includes :

- a durable construct host
- a continuous or replenishable mana source
- stable Attuning and Sourcing components
- feedback regulation
- a defined work output
- fault detection
- a dissipation or waste-handling path
- scheduled inspection and maintenance

Engines differ from ordinary implements chiefly in operational duration, throughput, autonomy, and infrastructural integration.

### Ward Casting

**Ward Casting** is the construction or activation of spells whose primary purpose is detection, regulation, exclusion, containment, correction, or response.

Wards may detect crossings, mana flows, selected reagents, construct interference, or other declared conditions. Their response may include signalling, blocking, redirecting, dissipating, isolating, or activating another spell.

Because wards frequently remain dormant for extended periods before activation, their reliability depends heavily upon persistent scaffold stability, environmental tolerance, stable long term mana sourcing, maintenance frequency, and graceful handling of degraded components.

Wards may be keyed to animic signatures, allowing them to recognise authorised individuals, distinguish familiar inhabitants, or detect damaged and altered soul-forms. Primed-mana saturation wards may also imitate part of a soul-form's defensive function by making a protected volume resistant to foreign Expenditure and construct formation.

Large, recurrent, long-maintained ward networks may gradually accumulate vestigial soul-forms. Such proto-animic structures can develop distinctive signatures, preferential responses to familiar operators, and resistance to unfamiliar modification without necessarily possessing consciousness or general autonomy.

### Array Casting

**Array Casting** is the use of a distributed assembly whose constructs are anchored across several hosts or locations.

Arrays may be architectural, environmental, instrumental, or mixed. They are commonly used where one scaffold would be too large, where broad spatial coverage is required, or where mana sourcing and operation must be distributed.

Their principal difficulties include :

- synchronisation
- link stability
- propagation delay
- local environmental variation
- partial failure
- fault cascades
- maintaining a coherent shared reagent or boundary
