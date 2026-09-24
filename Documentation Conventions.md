# Documentation Conventions

**Type: Authorial guide**

**Status: Active**

This is the author-facing guide to organizing, writing, and maintaining the vault. Read the relevant sections when creating, editing, moving, or auditing documentation. It establishes no setting canon.

## Corpus Boundary

Agents and LLMs must not directly write, rewrite, or otherwise edit corpus prose, including drafts and equivalent creative text stored elsewhere, as those are meant to be fully user generated and maintained. However, they may read and discuss that material only when requested, providing critique or suggestions without modifying the source.

## Find the Right Home

| Location | Owns |
| --- | --- |
| `Start Here.md` | Reading routes, topical references, and working tools. |
| `00 Core` | Premise, durable axioms, story intent, and themes. |
| `01 World` | Cosmology, environments, populations, and places. |
| `10 Magic System/01 Key Concepts` | Magical mechanisms, constraints, terminology, and training. |
| `10 Magic System/02 Additional Disciplines` | Specialized disciplines that draw on the foundational references. |
| `11 Society` | Institutions, culture, economy, politics, knowledge, and everyday life. |
| `80 Narrative` | Author-facing characters, relationships, arcs, location planning, and planning boards. |
| `90 Corpus` | User-written prose, creative drafts, fragments, and fictional documents. |
| `97 Assets` | Obsidian attachments and supporting assets. |
| `98 Temp` | Incidental Obsidian files, including notes generated from broken links. |
| `99 Workshop` | Development method, current work context, unresolved alternatives, and historical feedback. |

Keep the fixed Core and World roles first, the project-specific domains together next, and the supporting folders last. Folders identify purpose, not approval.

Do not store valuable work in Temp. Review its contents before removal because a temporary location does not make a file disposable. Asset and Temp folder roles do not authorize editor-setting changes.

A World note owns a place's established environment and infrastructure. Society owns general institutions and social mechanisms. Narrative owns that place's intended story function and encounter planning. Keep a short note together until independent retrieval makes a split useful.

## Ownership and Navigation

- One document owns the detailed answer to a subject. Dependent notes give the context needed to remain readable and link to that owner.
- Put a usable baseline or operational summary first, then mechanics, constraints, consequences, and open questions as needed. Do not force every small note into a large template.
- Landing pages provide short context and descriptive links. A topic overview may own a genuinely broad baseline, but should not repeat each linked reference.
- Use descriptive filenames. Avoid catch-all `General Ideas` files and unqualified `Overview` names. Create a new folder when existing material needs grouping, not as an empty promise of future work.
- Numbering expresses a deliberate reading or browsing order. Preserve or deliberately repair it when moving files. It is not a record of creation order.
- Split sections when readers seek them independently or they have different owners or uses. Merge when they repeatedly answer the same question together. File length alone is not a reason to split. Related equipment may remain together.
- Exact technical vocabulary belongs with its mechanism. If a shared glossary becomes useful, let it define ambiguous shared terms and link to specialized vocabulary.

## Status and Approval

Begin ordinary documents with **Type** and **Status** labels. Use **Scope** when approval applies only at a particular level, **Approval** when canonization explicitly requires it, and **Development** for explicit deferrals. Keep each field on its own paragraph so it remains readable in both Markdown and preview.

Use these status values consistently:

- **Current foundation:** existing core, terminology, or reference material whose original document had no explicit approval label. This records continuity, not a new blanket canon approval. Open questions and candidate sections remain unselected.
- **Approved baseline** or **Selected baseline:** retain the author's existing approval wording and state its scope. Neither label settles explicitly open details.
- **Exploring** or **Provisional:** retain the existing distinction between alternatives under development and a provisional working proposal. Preserve any explicit approval requirement.
- **Current direction:** revisable narrative preferences.
- **Unassessed:** inherited feedback or other evidence whose current applicability has not been established.
- **Active:** a navigation page, guide, or queue in current use. This is not a canon status.

Kanban boards retain their native frontmatter and settings instead of receiving prose labels or a new heading. Document type and status labels apply to ordinary notes, not as extra cards on a board.

Keep these dimensions distinct:

| Dimension | Examples | Meaning |
| --- | --- | --- |
| Authorial approval | Approved baseline, selected high-level baseline, provisional, exploring, rejected | Whether the author has selected the material and at what level. |
| Narrative planning | Current narrative direction, candidate scene or character | Story preferences do not automatically settle broader canon. |
| In-setting availability | Routine, exceptional, undeployed research, theoretical-only | Whether people in the setting can use a capability, separate from authorial approval. |
| Development state | Active, explicitly deferred, superseded | Whether work should proceed now. |

Preserve existing status and approval labels. Do not infer approval from a file's folder, a confident sentence, a catalogue entry, or its presence in a reference. Moving or consolidating text never canonizes it.

An active topical working reference may contain approved constraints and exploratory details if their boundaries are explicit. Use section-level labels when a single file-level label would misrepresent mixed material. Keep incompatible alternatives distinguishable. Preserve provenance, conflicting figures, names, and mechanisms until the author resolves them.

Keep detailed open questions with their topic. [[99 Workshop/00 Current Work Context|Current Work Context]] owns their work order, continuation plans, loose ends, and explicit deferrals, linking to the detailed questions. Completed decisions belong in their owners, not repeated at length in the queue or a workbook.

## Writing and Knowledge Layers

Follow [[Writing Style|Writing Style]] for Canadian English, the -ize and -ization house preference, clear prose, and restrained punctuation.

Topical magic and cosmology references use precise, setting-compatible scholarly prose. Preserve the soft historical-fantasy tone and established vocabulary, including mana states, Attunement, Expenditure, constructs, reagents, and soul-forms. Explain mechanisms, constraints, consequences, and uncertainty without mystical hand-waving. The reference writer may take an omniscient view while speaking in the setting's register.

This is an author-facing reference style. It does not authorize agents to create fictional corpus documents. Avoid conspicuously modern industrial, corporate, or computing comparisons in scholarly reference prose. When necessary, put external analogies or design commentary in a final `## META` section. Use direct authorial language for methods, queues, development questions, and narrative planning.

Distinguish objective reality, institutional knowledge, common practice, common belief, and narrative revelation using [[99 Workshop/01 Development Method and Order|Development Method and Order]]. Reference completeness does not establish universal knowledge within the setting.

Record source details and limitations when they affect a claim. Historical draft feedback retains its provenance and uncertainty. It is not a current assessment unless the author requests a new review of the identified source.

## Links and Markdown

- Use concise Obsidian links at the first useful occurrence of a concept. Avoid linking every repetition. Prefer explicit vault-relative targets for cross-folder links and plain-language display labels.
- Link directly to the relevant section when the reader needs a specific answer. Update the link if that heading changes.
- Outside tables use `[[File Name|display text]]`. Inside tables escape the internal pipe exactly once: `[[File Name\|display text]]` or `![[Image.png\|200]]`. Keep ordinary table separators unescaped. Adjust escaping when moving text into or out of tables. Never double-escape links or put alignment spaces inside targets or labels.
- Use one descriptive document title and a coherent heading hierarchy. Check affected tables, code fences, and mathematical blocks when restructuring them.
- Keep Kanban board frontmatter, settings, and card syntax intact when moving boards.

In Markdown tables, escape every pipe belonging to a cell’s content with exactly one backslash: `\|`. This includes ordinary text, inline code, wikilink aliases, and embed options. Backticks do not protect a pipe from splitting a cell. Keep structural column separators unescaped, and never double-escape content pipes. After editing a table, check that its rows retain their intended cell counts.

## Editing and Handoff

When changing a foundational concept, trace direct and likely second- or third-order effects through affected references. Remove, revise, or explicitly defer dependencies on superseded assumptions. Surface substantive contradictions instead of inventing a resolution.

`VALIDATE` markers are author-maintained review prompts, not instructions to delete text automatically. Keep review proportionate to the affected concepts.

Treat Legacy folders as obsolete and leave them alone unless the task explicitly needs them. Do not modify source guides, inherited material, or empty idea files unless the task calls for it. Preserve useful source provenance and unresolved alternatives when consolidating notes.

For moves and merges, update inbound links, section targets, navigation lists, and ownership statements in editable author-facing documentation together. Exclude corpus text from automated rewriting, including link repair. Report known affected corpus references for the author to update. Remove a superseded wrapper only after its useful material has a destination. Keep summaries short enough that they do not become competing versions of the answer.

Before handoff, apply the validation scope below and verify affected approval, provenance, and deferral boundaries. Check new files as well as existing edits. Report checks and limitations accurately. `git diff --check` checks whitespace only. File comparisons can verify changes without using Git.

## Work Context Maintenance

[Current Work Context](99%20Workshop/00%20Current%20Work%20Context.md) owns work order, next steps and their rationale, short stopping points, loose ends, parked threads, and explicit deferrals. Detailed questions, evidence, calculations, and selected answers remain in their topical notes. Save substantial unfinished reasoning in an existing working note, or a dedicated Workshop note when it needs its own home, and link it from Current Work Context.

1. When starting or resuming project work, read the context page and then only the notes relevant to the chosen thread. The user's current request takes precedence over recorded priorities
2. During authorised edits, save useful findings and consequential reasoning at meaningful milestones, especially before switching topics. Record rejected approaches or dead ends only when they would prevent worthwhile repeated work
3. Before pausing, switching threads, or handing off, update only the affected thread: next steps and why, unresolved loose ends, and enough progress context and links to resume. Preserve an interrupted thread's plan when taking a tangent
4. When work is resolved, retain useful results, decision rationale, and actual approval state in their owners. Remove the resolved entry or replace it with a brief result link. Carry remaining loose ends forward
5. For discussion-only or no-edit work, offer a short proposed checkpoint in the response if useful. Do not write files against that boundary

Use **Open Threads**, **Later and Parked**, and **Explicit Deferrals**. Keep a simple task to one line and use a short thread note when preparation warrants it. Priorities need not identify the last active thread. Distinguish documented plans from suggested next actions, and state when current focus or a stopping point is unknown. Do not infer authorial intent from modification dates.

A parked thread is unfinished work, not automatically an author-imposed restriction. Preserve the actual scope of explicit deferrals. Listing a task authorises neither its execution nor its possible setting outcomes. Keep proposals, selected decisions, and unresolved alternatives distinguishable.

Keep this a current working page. Dates, IDs, estimates, session logs, exhaustive backlogs, and recurring reviews are not required. Add a date only when it helps interpret a checkpoint. Do not promote every unanswered setting question into a task or refresh untouched entries merely for tidiness. A near-empty page is valid when nothing remains planned.

## Validation Scope and Stopping Rule

Validate changed material and dependencies that the change could affect. Do not revalidate unrelated content by default. Review the relevant diff or before/after comparison, including new files, for unintended changes and information loss.

| Change | Check |
| --- | --- |
| Ordinary prose correction | Review the edited prose. Skip link checks if targets, headings, paths, and link syntax are unchanged. |
| Link added or target changed | Resolve that link and any heading target. |
| Display label changed | Check syntax and escaping. Recheck the destination only if its target or resolution context changed. |
| Heading renamed or removed | Find and check references to that heading. |
| File moved, renamed, or deleted | Find inbound references and check affected relative links, embeds, navigation, and stale path mentions. |
| Table or structural Markdown edited | Check the affected table's cell counts and pipe escaping, or the affected headings, fences, and surrounding structure. |
| Numerical or foundational content changed | Check the affected values, interpretations, and dependent references within the authorized scope. |

An affected link may be in an otherwise unchanged file. Use a targeted search across editable documentation to find inbound references when needed. This is not a reason to validate every unrelated link. Corpus protection still applies, including during dependency searches.

Batch related edits before checking them. Once a relevant check passes, stop. Repeat only checks whose inputs or dependencies changed, checks needed to investigate an unresolved failure, or checks justified by new evidence or an explicit request. One successful check can satisfy several workflow steps. Do not repeat it merely to produce another handoff summary or report a larger check count.

Broaden validation only when requested or when the actual change or evidence warrants it, such as widespread path changes or failures suggesting a systemic problem. State the reason and limit the scope accordingly. A bootstrap checks the new starter and its local dependencies, not neighbouring projects.

Check portability when guidance is first adopted or when paths, dependencies, or instruction routing change. Inspect the affected guidance and local dependencies first. Use a temporary isolated copy only when it would resolve a concrete uncertainty about external dependencies or when explicitly requested. Ordinary wording edits do not require an isolated copy.

Report the checks actually performed and any relevant limits. Do not maintain validation logs, version fields, or recurring audit dates solely to support this rule.
