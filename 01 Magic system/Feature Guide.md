Below is the authoritative guide for how I want the magic system to work.
This guide should be used to correct the previously worked-on documents, including their use of outdated nomenclature.

## Mana Flow

Mana is a field of discrete particles, each one being in one of **3 possible states** :

- **Primed** ( charged with **unattuned potential** )
- **Attuned** ( charged with **attuned potential**, differentiated along multiple **mana attributes** )
- **Spent** ( uncharged, as the potential was consumed during permutation )

Collectively, Primed, Spent, and the various attuned mana attributes are known as **mana types**, and the process of converting from one of these to another is known as **mana permutation**. Permutation invariably follow one of these **3 permutation processes** : 

| Permutation     | Process Formula                                                                           |
| --------------- | ----------------------------------------------------------------------------------------- |
| **Attunement**  | Primed => Attuned( attribute ) x ( 1 - Ratio ) + Spent x Ratio + { *some kind of waste* } |
| **Expenditure** | Attuned( attribute ) => Spent + Operations( attribute )                                   |
| **Priming**\*   | Spent + Singularity => Primed                                                             |
\**Priming occurs solely around the central singularity ( the light source at the centre of the expense )*

These mana types all interact amongst themselves and each other through repellent forces, pushing mana away from highly concentrated areas towards less concentrated ones.

They are also all affected by gravitational pull, with Spent mana being pulled upwards ( where it eventually gets permuted back into Primed mana ), while the other states are all pulled downwards at varying rates, pooling in low-lying areas of the surface.

Different materials have various interactive properties with some or all of the mana types, resulting in many biological, metallic, crystalline matter attracting or repelling mana to various degrees.

Of all the mana types, Primed mana is the most reactive both with itself, other mana types, and mana-interactive matter, while Spent mana is the least, being almost completely inert. All other type's properties generally lie in between these two extremes.

**Flow Theory** is the field of study which pertains to the different ways mana is pushed and pulled with these various forces.

## Mana Attunement

**Mana potential** is the capacity of a mana particle to perform an attributed operation. Physical energy may be created, redistributed, consumed, or conserved depending on the attribute involved.

**Attunement** is the process of **converting Primed mana into** **Attuned Mana**. This process occurs naturally, at a rate dependent on the relative local concentration of the target Attuned mana compared to the local concentration of Primed mana and, to a lesser degree, Spent mana. The greatest rates of this **Background Attunement** are found in locales with high Primed mana concentration, and low Attuned and Spent mana concentrations.

This conversion process also generates an amount of Spent mana, called **Waste mana** in this context. The **Waste mana ratio** ( the proportion of used Primed mana which becomes Spent mana ) depends on both the specific attribute at play, as well as the attunement process itself, with faster processes generally being less efficient than slower ones.

Attuning attributes can also be done directly by a caster ( and is often one of the first exercises novice magi tend to be taught ), but doing so is rarely efficient in both time, effort, and purity of results. As such, There exists a wide range of mana construct dedicated to automating the attunement of Primed mana into the various attributes.

Below are summary tables pertaining to the 11 known attuned **attributes** :

| Attribute      | Common Names                                | Operation Domain Description                                                                                                         |
| -------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Kinetic**    | Motion, Force, Heat, Explosion              | Change the momentum distribution of matter (uniform or microscopic).                                                                 |
| **Radiant**    | Light, Illusion, Cloaking, optical          | Emit, absorb, redirect or otherwise manipulate free photons.                                                                         |
| **Galvanic**   | Lightning, Magnetism                        | Changes charges, currents, and quasi-static electromagnetic fields                                                                   |
| **Volumic**    | Pressure, Density, Compression, Expansion   | Modifies the metric volume occupied by a bounded material system without directly changing its topology, mass, or internal momentum. |
| **Massic**     | Mass, Weight, Gravity                       | Modify an object's inertial and gravitational mass.                                                                                  |
| **Cohesive**   | Structure, Shaping, Binding                 | Changes which portions of matter are mechanically continuous, without directly specifying their chemical composition.                |
| **Resonant**   | Linking, Observation, Divination            | Changes the degree to which state changes in one system are detectable by, transmitted to, or correlated with another.               |
| **Mnemonic**   | Memory, Recording, Engraving, Scrying, Mind | Encode and decode information to and from a physical medium in which it is stored.                                                   |
| **Temporal**\* | Acceleration, Preservation, Stasis          | Modify the local rate at which time progresses.                                                                                      |
| **Spatial**\*  | Portal, Dimension, Teleportation            | Modify the layout of space itself.                                                                                                   |
| **Ontic**\*    | Identity, Essence, Classification, Soul     | Modify what an object fundamentally _is_ according to magical law.                                                                   |

| Attribute      | Domain Type    | Reality Layer | Operation Domain    | Waste Ratio | Persistence mechanism                                              |     |
| -------------- | -------------- | ------------- | ------------------- | ----------- | ------------------------------------------------------------------ | --- |
| **Kinetic**    | State          | Physical      | Momentum            | Low         | Imparted state                                                     |     |
| **Radiant**    | State          | Physical      | Photon field        | Low         | Active emission                                                    |     |
| **Galvanic**   | State          | Physical      | Electron field      | Low         | Usually active field; charge redistribution may persist            |     |
| **Volumic**    | State          | Emergent      | Volume, Pressure    | Medium      | Usually sustained unless natural structure supports the new volume |     |
| **Massic**     | State          | Physical      | Mass                | Medium      | Sustained                                                          |     |
| **Cohesive**   | Organizational | Emergent      | Connectivity        | High        | Structural                                                         |     |
| **Resonant**   | Relational     | Physical      | Coupling, Detecting | High        | Anchored relationship                                              |     |
| **Mnemonic**   | Organizational | Emergent      | Information         | High        | Encoded state                                                      |     |
| **Temporal**\* | Organizational | Emergent      | Time rate           | Very High   | Sustained                                                          |     |
| **Spatial**\*  | Relational     | Emergent      | Spatial Layout      | Very High   | Sustained                                                          |     |
| **Ontic**\*    | Ontologic      | Metaphysical  | Identity            | Extreme     | Metaphysical                                                       |     |
*\*Little is known of these attributes, and what is is highly speculative and contested*

Attributed mana used to power a spell and impart its operational effect is converted into Spent mana in by the process.

**Attribute Theory** is the study of how each mana attribute interacts with the real world, both through their Operational effects on a chosen reagent, as well as their passive material interactions.

**Attunement Theory** is the study of the attunement process, the principles that affect its attunement rate and waste ratio, and the comparative properties of each individual attunement processes.

*PS : Make sure to properly distinguish **Attunement** ( the process of converting mana ) from **Attribute** ( the specific result of an attunement )*

## Mana Constructs

Mana constructs are building blocks of spells, as they allow for the conversion of Attuned mana into the specific desired effect, and can have said effect be nudged by predefined conditions, allowing for conditional or self-regulating spells.

There are **5 essential phases** to **creating and triggering** a functioning mana construct :

- **Construction** ( **create** a stable **construct scaffold** out of Primed mana )
- **Declaration** ( **imbue** the construct with the desired **conditions** and **parameters** )
- **Activation** ( **seal** the construct and **enable** its future execution )
- **Execution** ( **enact** the construct's function based on its declaration )
- **Termination** ( gracefully **dissipate** the construct without perturbing surrounding constructs )

Oftentimes, these phases can overlap ( for example, construction and declaration or execution and termination ), but they are invariably present, even if they are not always readily visible.

|Magic phase|Computing analogy|
|---|---|
|Construction|Allocate hardware/runtime environment|
|Declaration|Define program and parameters|
|Activation|Compile, validate, seal, arm|
|Execution|Run and supervise|
|Termination|Deallocate, flush, and fail safely|

Below is a more detailed breakdown of each phase :

### Construction

It is necessary for a mana construct to be contained within an insulating shell, known as a **construct scaffold**. This scaffold is built out of Primed mana, which has the ability to form and maintain certain shapes when properly manipulated. These shapes sometimes occur naturally in location with a high density of Primed mana, but these occurrences lack the size, organisation, or structure to be proper construct scaffolds. 

Construct scaffolds are generally built in intricate patterns of lines connected by their ends. The simplest of these patterns are the edges of all 5 platonic solids, but more complex mana constructs often require more complex shapes.

**Scaffold Theory** is the field of study which concerns itself with the shaping of construct scaffolds, the density and stability of their distinct configurations, and the ways to manipulate Primed mana into constructing them.


NOTES :

Construction could be highly nontrivial because scaffold topology appears to constrain:

- component capacity;
- stability;
- isolation;
- flow;
- concurrency;
- fault containment.

The topology could determine:

- containment efficiency;
- number of independent flow channels;
- maximum component count;
- feedback-loop stability;
- susceptibility to interference;
- dimensional embedding;
- termination behaviour.

For example:

- vertices are component junctions;
- edges are mana channels;
- faces are isolation boundaries;
- enclosed volume provides buffering;
- symmetry distributes pressure and reduces drift;
- asymmetry permits directional processing but causes instability.

### Declaration

Declaration, also known as **spell shaping**, is the most complex of the five phases, as the entirety of the mana construct's possible **behaviour** is defined here. This subject will be covered later on in more details, but below is a short summary.

Declaration is done via the **imbuing** of any number of custom **construct components** into the **construct scaffold**, the most frequent of which are presented below :

| Component       | Function                                                  |
| --------------- | --------------------------------------------------------- |
| **Sourcing**    | Defines accepted mana sources and types                   |
| **Attuning**    | Defines attunement process required, if any               |
| **Selection**   | Defines reagent and effect boundaries                     |
| **Bounding**    | Defines affected region or quantity                       |
| **Anchoring**   | Determines what construct follows or remains attached to  |
| **Directing**   | Defines vectors, orientation, and propagation             |
| **Regulating**  | Defines magnitude and rate of effect                      |
| **Timing**      | Defines duration, delay, rhythm, or termination of effect |
| **Funnelling**  | Guides mana flow inside the Construct                     |
| **Sensing**     | Observes parameterised conditions                         |
| **Processing**  | Processes observed conditions into component behaviour    |
| **Warding**     | Detects, absorbs, or corrects disruptions                 |
| **Dissipating** | Handles any excess mana                                   |
| **Linking**     | Connects constructs to one another                        |

Regarding sensing components : a construct may directly sense properties exposed by its operational attributes within its bounded reagent, but resonant mana is required for unrelated, indirect, remote, relational, or persistent detection.

**Component engineering** is the field of study relevant to the design, combinations, and interactions of various construct components within a single construct scaffold

### Activation

A properly built construct will be inert until it is **sealed**, as modifying the components of an active construct is extremely difficult, thus requiring this safeguard. Once sealed, the construct can have its execution triggered via funnelling mana into it, either actively or passively.

### Execution

TBA ( basically running '*sudo ./construct.sh*' without a care in the world )

The mana attribute used determines which primitive operation the construct can accomplish during its execution. The construct declares the reagent, region, magnitude, direction, duration, conditions, and permitted feedback behaviour of that operation.

### Termination

A properly designed construct will have a way to handle all likely **termination cases** (which is to say the different ways the execution can finish, either purposefully or accidentally ) so as to avoid collapse of the construct, which can lead to heavy collateral damages to surrounding constructs and the spell as a whole.

Proper termination is known as **graceful termination**, while improper termination is referred to as **erroneous termination**. Avoiding erroneous termination should be one of the top concerns of any spell designer, as a spell might otherwise cause catastrophic damage, including the loss of life.

Below is a list of frequent construct failure types termination would need to handle :

| Failure Type             | Description                                                     |
| ------------------------ | --------------------------------------------------------------- |
| **Source starvation**    | Insufficient or interrupted mana supply                         |
| **Attribute mismatch**   | Supplied mana does not match component requirements             |
| **Selection failure**    | Reagent cannot be resolved                                      |
| **Boundary leak**        | Effect escapes its declared region                              |
| **Regulation failure**   | Output exceeds declared or safe values                          |
| **Feedback oscillation** | Corrective loops repeatedly overcompensate                      |
| **Scaffold fracture**    | Construct topology loses containment                            |
| **Component deadlock**   | Components wait indefinitely on one another                     |
| **Runaway execution**    | Termination condition becomes unreachable                       |
| **Dissipation overflow** | Waste or excess mana cannot be safely discharged                |
| **Link cascade**         | Failure propagates through linked constructs                    |
| **Semantic mismatch**    | Declaration is valid but does not do what the designer intended |

## Spell casting

WIP
