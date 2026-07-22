# Mana Constructs

Mana constructs are the building blocks of [[07 Spell Composition|structured spells]]. They contain and direct mana, constrain its attributed operations, and allow those operations to respond to predefined conditions, enabling conditional or self-regulating behaviour.

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
