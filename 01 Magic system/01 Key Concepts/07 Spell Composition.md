# Spell Composition

At their core, spells are **operationally unified systems** of one or more [[05 Mana Constructs|mana constructs]], connected through declared interfaces and directed towards a shared process, effect, or termination condition. They are the defining products of [[08 Mana Casting|Structured Casting]] and are distinct from the isolated attributed operations produced through Unstructured Casting.

A collection of nearby or interacting constructs does not necessarily constitute a single spell by themselves. Constructs form one spell when their activation, reagent bindings, execution dependencies, supervisory structure, or termination behaviour establish them as parts of one coherent operation. This is of course a somewhat blurry line, and as such, the terms spell and spell-combination sometimes overlap in their use.

While it is technically possible to accomplish any valid spell effect with a single sufficiently complex mana construct, such constructs rapidly become unwieldy and unstable. It is therefore preferable to **compose spells** by interconnecting more self-contained constructs, each with a dedicated purpose or task.

Wholly disjoint spells targeting the same reagent often interfere with each other's attributed operations onto said reagent, hence the need to compose spells, so as to make each mana construct aware of each other's action where necessary.

There are many ways to represent spells, but all rely upon **glyph systems**, which are abstract representations of construct components, scaffolds, interfaces, parameters, and other mana based elements.

The only requirements of a valid glyph system are that its glyphs be reproducible, distinguishable from one another, and composable into **spell formulas**. Glyph systems need not be visual, as they may be expressed through symbols, text, speech, music, gesture, spatial arrangements, or other reproducible patterns, but visual systems are most common across magical traditions.

Colloquially, the term _spell_ may refer to 5 distinct but interconnected concepts :

| Term                | Definition                                                                        |
| ------------------- | --------------------------------------------------------------------------------- |
| **Spell Formula**   | A specification of a spell encoded in a particular glyph system                  |
| **Spell Template**  | The notation-independent logical design represented by one or more formulas       |
| **Spell Assembly**  | The concrete network of mana constructs instantiated from a template              |
| **Spell Execution** | A particular activation and runtime instance of a spell assembly                  |
| **Spell Results**   | The attributed operations of an execution and their natural consequences          |

**Spell Architecture** is the study of composing constructs into operationally unified assemblies through interfaces, shared reagents, dependencies, and supervisory structures.

**Compositional Thaumaturgy** is the study of how primitive operations and construct functions may be combined sequentially, concurrently, conditionally, or recurrently.

### Spell Interfaces

**Spell interfaces** are [[05 Mana Constructs|construct]] interfaces exposed across construct boundaries within a spell assembly. They are not a wholly separate concept, as their categories, carried values, directionality, and compatibility requirements are those of the component-based interfaces defined in mana constructs.

A cross-construct connection begins at compatible declared interfaces. It is realised by a **Coupling component**, which establishes the declared relationship between the constructs without granting unrestricted access to either one's internal structure. A Coupling component may provide a local, linked, or Resonantly extended connection, and may regulate its activation, translation, supervision, or termination. It does not override the permissions or tolerances declared by the interfaces it couples.

At the assembly level, such connections may be required, optional, or conditional. They may expose fixed values, accept parameters supplied during activation, or transmit values produced during execution.

A connection is valid only when :

- the input and output interface categories match
- the transmitted mana types are accepted
- parameter dimensions and ranges are compatible
- reagent and construct references are meaningful to the receiver
- directionality is respected
- throughput remains within the tolerances of both interfaces

An invalid connection may prevent sealing, fail validation during assembly initialisation, or produce erroneous execution if incompatibility emerges only at runtime. A failing Coupling component may additionally isolate the connection, report a fault, or terminate it according to its declaration.


**Interface Theory** is the study of compatible mana, parameter, control, reference, state, and fault connections between components and constructs.

**Thaumaturgic Systems Engineering** is the applied study of modular spell assemblies, subsystem integration, interface standards, verification, and synergistic system behaviour.

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
- the couplings and interfaces between them
- active and dormant components
- contained and flowing mana
- reagent bindings
- runtime state
- scaffold and interface integrity
- anchoring, hosting, or ownership relationships

A spell assembly may exist without currently executing. An enchanted implement may contain a dormant assembly, a ward may contain a continuously active assembly, and a structured caster may build an ephemeral assembly immediately before activating it.

A memorised cantrip, by contrast, is a retained formula or template and does not become an assembly until instantiated.

**{ NOTE : VALIDATE }**
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

**Distributed Thaumaturgy** is the study of spatially separated constructs, Resonant couplings, synchronisation, propagation delays, partial failure, and distributed control.

### Spell Execution

A **spell execution** is a particular runtime instance of an activated spell assembly.

While construct execution describes the behaviour of one scaffold and its components, spell execution describes the coordinated behaviour of the entire assembly. It determines when constructs activate, how they exchange inputs and outputs, how shared reagents and mana sources are resolved, and how local failures affect the wider spell.

A spell execution forms a directed graph of mana flows, parameter dependencies, state changes, and control signals. Its branches may occur sequentially, concurrently, recurrently, or conditionally. The graph may remain fixed throughout execution or change among predefined configurations in response to observations.

Spell execution is generally divided into :

- **Assembly initialisation**, during which shared sources, interfaces, parameters, and reagent bindings are validated;
- **Coordinated operation**, during which constructs perform and regulate their assigned tasks;
- **Assembly finalisation**, during which outputs are completed, faults are contained, and constructs terminate or return to dormancy in a safe order.

The failure of one construct does not necessarily terminate the entire spell. Fault interfaces may allow the assembly to isolate a damaged branch, substitute a redundant construct, degrade its output, or initiate graceful termination. Unhandled failures may instead cascade through shared mana sources, references, or control couplings.

Each activation of the same assembly constitutes a distinct execution, even when its formula, template, constructs, and nominal parameters remain unchanged. Environmental conditions, reagent state, and prior assembly wear may therefore cause repeated executions to produce slightly different results.

A continuously executing spell, such as wards, may still be made up of **sub-executions**, which are discrete events, generally occurring inside one or multiple default stand-by state.


**Spell Dynamics** is the study of coordinated runtime behaviour across an entire spell assembly.

**Thaumaturgic Orchestration** is the study of activation ordering, shared state, supervisory control, redundancy, and fault propagation among linked constructs.

### Spell Types

Spell types are not exclusive natural categories. They are independent classifications describing different aspects of a spell's operation, architecture, reagent relationship, or use. As such, there are a multitude of axis along which spell can be broken into. Below are the most common ones :

#### By Duration

| Type              | Description                                                     |
| ----------------- | --------------------------------------------------------------- |
| **Instantaneous** | Performs one bounded operation and terminates                   |
| **Sustained**     | Remains active while continuously supplied                      |
| **Persistent**    | Remains instantiated between sub-executions                     |
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

| Type              | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| **Ephemeral**     | Exists only for one execution                                         |
| **Somatic**       | Hosted or continuously maintained by a living body                    |
| **Instrumental**  | Hosted within a portable or purpose-built artefact                    |
| **Architectural** | Embedded into a structure or fixed installation                       |
| **Environmental** | Anchored to terrain, ambient mana flows, or naturally occurring media |

Magical traditions also classify spells in **schools** based on various subjective classification systems. These are social and functional categories rather than divisions inherent to mana or construct theory, and as such, vary widely across the expanse, and are generally associated with a specific accompanying glyph tradition.

Prime examples of the school system would be the various widespread **Elemental Schools** and **Applicative Schools**, which each classify spells based on the elemental association and spell outcome respectively.


**Thaumaturgic Taxonomy** is the study of spell classification according to duration, control behaviour, architecture, reagent relationship, hosting substrate, practical use, or any other target attribute.

**Comparative Spellcraft** is the study of equivalent or competing spell designs across different attributes, architectures, traditions, and applications.


## META

| Term      | Computing Analogy              |
| --------- | ------------------------------ |
| Interface | Ports                          |
| Formula   | Source representation          |
| Template  | Abstract program or design     |
| Assembly  | Instantiated runtime structure |
| Execution | Running process                |
| Results   | Output and side effects        |
