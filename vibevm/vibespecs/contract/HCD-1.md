# HCD.1 — Derive Human Capability Demand from Representative Later Work {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Human Capability Development Principles Framework* (28 September 2026 — twenty-nine-pattern edition), `Engineering DPF Suite/HUMAN-CAPABILITY-DEVELOPMENT-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Human Capability Development practitioner method pattern
> **Status:** Stable


## HCD.1:0 - Use This When {#use-this-when}

Use this pattern when someone asks what a named person must become able to contribute in later Work and the available request is still expressed as a job title, competency list, course request, platform score, MethodDescription, or technology rollout. Begin with the exact human holder and representative later Work, not with a learning product.

The first useful result is a **human capability-demand account** recording which contributions that person needs to make in the named Work family, configuration, conditions, and horizon for the receiving decision. When the future Work is well framed but current evidence is not yet available, return a **prospective demand hypothesis** and the observations to obtain. When the question belongs to a clinical, target-domain, authority, organization, assignment, access, tool, or nonhuman-capability owner, return it there. When a conclusion consumes evidence that is absent, name each missing value and its retry predicate instead of calling the gap a learning need.

The practical gain is a demand that can guide diagnosis or profile comparison without pretending that training has been selected or that capability has already been observed. Use `HCD.3` when the demand is known and the question is which changeable human limitation, if any, is supported. Use `HCD.4` when the demand is known and simultaneous capability claims must be compared. A separate programme comparison (`HCD.2`) may use the account; deriving demand does not select a programme.

Do not use HCD.1 to prescribe diagnosis, treatment, curriculum, provider, employment action, safety judgement, release decision, or target-domain correctness. Those decisions remain with their direct owners.

## HCD.1:0.1 - Working Terms {#working-terms}

| Name in this pattern | What it denotes |
| --- | --- |
| human holder | One identified human person whose capability demand is being considered. A role, cohort, roster, demographic category, or population is not that person. |
| later Work | A named family of future or recurring `U.Work` occurrences in which that person may contribute under stated conditions. |
| representative case | A case selected to examine a material variant of later Work, such as unfamiliar content, changed support, or a specialist interface. Its suitability depends on the conditions it represents and the conclusion for which it is used. |
| human capability demand | The contributions this person needs to be able to make under the named later-Work conditions. A demand account records those requirements; it does not establish the person's current capability. |
| demand claim | A statement that this person needs to be able to make a specified contribution under the named later-Work conditions, with the evidence for that requirement, uncertainty, and limits. |
| prospective demand hypothesis | A provisional account of future demand grounded in a supported future-Work frame. It states which demand claims remain provisional and which observations could qualify or revise them. |
| demand-evidence-blocked | A result that names each missing input, the conclusion it blocks, and the condition for retry. It also distinguishes available material from the missing input when that material could mislead the receiver. |
| outside-HCD return | A return of the current question and available evidence to the direct clinical, target-domain, authority, organization, assignment, access, tool, or other owner. |

The account records what later Work requires of the person. Evidence about present capability, causes, learning, or intervention effectiveness answers different questions and uses its own pattern.

## HCD.1:1 - Problem Frame {#problem-frame}

Human development is often commissioned from a visible carrier: a course catalogue, certification, role framework, AI platform, assessment dashboard, or manager's request. Those carriers can be useful, but none identifies by itself what a particular person must contribute in later Work.

Later Work is configured. The same named task can require different contributions when the product configuration, Method, information access, AI support, time, authority, specialist interface, or critical-error boundary changes. Assisted performance may also conceal which contribution belongs to the person and which belongs to a tool, another Agent, or an organization.

Demand therefore has to be recovered from representative Work and its intended result. Current observations are valuable, but future planning sometimes precedes an actual Work occurrence. The method must support honest prospective hypotheses without silently upgrading plans or demonstrations into current evidence.

## HCD.1:2 - Problem {#problem}

A role-first or course-first description bundles unlike things. It can call a missing Method, inaccessible source, broken tool, absent specialist result, poor assignment, unsafe workload, or organizational constraint a human skill gap. It can also average across a population and then assign the average to one person.

The reverse mistake is to refuse any demand account until the exact future Work has occurred. That discards useful architecture and delays the observations that would test it. The practitioner needs a result that distinguishes what can be framed now, what is qualified now, what belongs elsewhere, and exactly what evidence blocks the stronger conclusion.

## HCD.1:3 - Forces {#forces}

- A short role label is easy to communicate, while the consequential demand usually lives in case variants, interfaces, and error boundaries.
- A MethodDescription can make intended Work inspectable, while only enactment or qualified representative evidence supports claims about obtaining Work and its results.
- Current task success is visible, while later transfer and unfamiliar variants must be established rather than presumed.
- AI and other supports can improve the joint result, while assisted output is not automatically human capability.
- Population summaries help allocation, while a person-specific decision requires a person-specific holder and compatible evidence.
- Missing evidence should stop false certainty, while a useful prospective hypothesis may still guide observation.
- HCD can organize demand evidence, while target-domain correctness, specialist judgement, assignment, safety, release, and employment authority stay elsewhere.

## HCD.1:4 - Solution {#solution}

Derive demand claim by claim from representative later Work. Preserve the truth posture of every case and source, separate human contributions from surrounding conditions and other owners, and return the strongest conclusion that the evidence supports.

### HCD.1:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Fix the use boundary and holder.** Name the exact human person, receiving decision, later-Work family, subject configuration, effective horizon, and evidence window. If the question concerns a population, identify the separately observed members or representative accounts; do not manufacture one aggregate holder.
2. **Recover the later-Work basis.** For every case, distinguish what was observed from what is planned, stipulated, or assumed. Explain which later Work and material conditions the case represents, and why its evidence is suitable for the intended conclusion. Recover the intended result, quality and critical-error predicates, Work products, and stopping conditions.
3. **Recover Methods and direct-owner inputs.** Identify applicable target Methods or MethodDescriptions, specialist results, assignments, authority, access, environment, tools, and supports. A missing nonhuman value remains a missing nonhuman value; do not rename it a learning gap.
4. **Select representative cases.** Cover the variants that can change demand: familiar and unfamiliar situations, allowed and withdrawn assistance, time or workload limits, AI-output challenge, coordination interfaces, specialist-return conditions, and material quality or critical-error boundaries.
5. **Derive human demand claims.** For each case, state which contribution the named person must be able to make for the intended result under the protected conditions and why the evidence warrants that requirement. Contributions may include, for example, noticing a signal, handling an object, coordinating a specialist return, or justifying a decision. Record required tools and supports as conditions of the contribution. Keep each contribution distinct from the Method, task, tool output, team result, or personal trait.
6. **Bind evidence and uncertainty.** Relate each demand claim to the cases, observations, work products, inference rule, uncertainty, and remaining observation. Keep instruction events, learner events, learning outcomes, later transfer, and job performance distinct; one does not establish the next by label alone.
7. **Return a conclusion-specific disposition.** Emit `qualified current demand`, `prospective demand hypothesis`, `outside-HCD return`, or `demand-evidence-blocked`. Different questions may lawfully receive different dispositions in one use—for example, a prospective hypothesis for future framing and a blocker for qualified current demand.

### HCD.1:4.2 - Record the Result {#record-the-result}

A human capability-demand account contains these result positions:

| Result position | Required content |
| --- | --- |
| use boundary | Human holder, receiving decision, later-Work family, configuration, effective horizon, evidence window, and direct owners whose results or authority matter. |
| later-Work basis | Cases, what was observed or remains planned, stipulated, or assumed, and the later Work and conditions they represent; reasons the evidence is suitable for the conclusion; intended result, quality and critical-error predicates, Work products, and stop conditions. |
| protected conditions | Allowed or required tools, AI posture, information access, time, environment, assignment, authority, supports, and specialist interfaces. |
| demand claims | Statements of the human contributions required in the named later Work, including material interfaces among simultaneous contributions. Derive these requirements from the cases rather than assigning capability from job labels or traits. |
| evidence account | Evidence and inference for every demand claim, uncertainty, incompatible evidence, and the observation or case still needed. |
| external gaps | Missing Method, description, specialist return, assignment, authority, access, environment, or nonhuman capability kept under its own kind and owner. |
| disposition | One conclusion-specific `qualified current demand`, `prospective demand hypothesis`, `outside-HCD return`, or `demand-evidence-blocked`. |
| continuation | Compatible inputs that HCD.3, HCD.4, or a future programme comparison may consume, plus scope limits and reopen conditions. |

A `demand-evidence-blocked` result records one row per absent consumed value:

| Missing-value field | Required content |
| --- | --- |
| missing kind | For example `later-Work-occurrence-missing`, `later-Work-result-claim-missing`, `result-record-missing`, `representative-observation-evidence-missing`, or a named external supplier result. |
| blocked conclusion | The exact conclusion that cannot be supported without this value. |
| available non-substitute, when relevant | If available material could plausibly be mistaken for the missing input, name it and explain why it cannot fill this gap. Otherwise omit this field. |
| retry condition | The input that must become available or be confirmed before reconsidering the named conclusion. State its required connection to the person, Work, and conditions, using only qualifiers that affect that conclusion. |

Do not infer `result-record-missing` when qualified direct observations are sufficient for the conclusion. Conversely, an orphan record does not establish that Work occurred or produced the result described in the record.

### HCD.1:4.3 - Population and Reuse Boundary {#population-and-reuse-boundary}

A population use may return a distribution over separately identified member or representative demand accounts. It does not create one person's demand by averaging, and it does not turn the population into a capability holder. A population whole qualifies as a holder only through the independent-System condition of `E.23.CDI`, outside this one-human-holder pattern.

Any downstream use must preserve the same human holder, configuration, later-Work conditions, effective horizon, compatible evidence window, and receiving decision. HCD.3 may consume the account as evidence input; HCD.4 may consume it as a scope and result frame. Programme comparison (`HCD.2`) may use the same frame. Deriving demand requires no programme-comparison result.

### HCD.1:4.4 - What Changes in Practice {#what-changes-in-practice}

A practitioner stops asking, “Which course matches this role?” and first asks, “What must this person contribute in which later Work, under which conditions, and what evidence makes that demand current?” The answer either supports a bounded demand, makes a future hypothesis testable, returns the question to its owner, or exposes the exact missing evidence.

## HCD.1:7 - Conformance Checklist {#conformance-checklist}

- [ ] One exact human person is named as holder; any population use preserves member or representative accounts.
- [ ] The later-Work family, configuration, effective horizon, evidence window, and receiving decision are explicit.
- [ ] Each case distinguishes observed facts from plans, stipulations, and assumptions, and explains which later-Work conditions it represents and why its evidence is suitable for the conclusion.
- [ ] Intended results, quality and critical-error predicates, protected conditions, tools, supports, and specialist interfaces are recoverable.
- [ ] Each demand claim names a human contribution supported by representative Work rather than a job label, trait, task, MethodDescription, or course.
- [ ] Human, AI, tool, specialist, team, organization, assignment, authority, and environment contributions or gaps remain distinct.
- [ ] Each demand claim has evidence, an inference boundary, uncertainty, and any observation still needed.
- [ ] The result uses one conclusion-specific disposition and does not suppress a lawful prospective hypothesis merely because qualified current demand is blocked.
- [ ] Every blocker names the missing input, blocked conclusion, and retry condition; available material is distinguished from that input when it could mislead the receiver.
- [ ] Downstream reuse preserves holder, configuration, conditions, horizon, evidence window, and receiving decision.
- [ ] The first result selects no curriculum, provider, intervention, assessment programme, treatment, safety action, release action, or employment action.


## HCD.1:9 - Consequences {#consequences}

The organization gains an inspectable demand account that can support diagnosis, profile comparison, evidence collection, or later programme comparison without making those later decisions in advance. Prospective planning remains possible, and missing evidence becomes a substantive return rather than an administrative “TBD.”

The cost is more careful case selection and relation keeping. Demand may vary across configurations, supports, horizons, and holders; some visible requests will return outside HCD. Evidence collection may reveal that the main constraint is not human capability.

## HCD.1:12 - Relations {#relations}

- **`A.15.1` and current Work ontology:** keep Method, Work occurrence, performer, result, and result episteme distinct.
- **`E.23.CDI`:** governs whether a population whole is an independent System capable of holding capability; HCD.1 otherwise stays at one-human-holder granularity.
- **`E.23.CAE`:** supplies capability-evidence boundaries for downstream observations; evidence does not itself authorize intervention or employment action.
- **`COG-10`:** supplies the event-to-transfer distinction and the requirement to qualify workplace opportunity, support, and environment.
- **[Dell’Acqua and colleagues, Navigating the jagged technological frontier](https://doi.org/10.1287/orsc.2025.21838) (`AI-03`):** supplies the bounded independent-error-challenge cue where assisted Work makes that contribution material.
- **Target-domain Methods and results:** determine correctness, quality, criticality, and specialist boundaries. HCD.1 consumes them; it does not replace them.
- **`SYSE.21` / `XRI-21`:** an obtaining compatible cultural-continuation result may supply later-enactment observations, a bounded practice-change decision, retained alternatives, and evidence gaps. Its MethodDescription or constructed demonstration is not that supplier result.
- **`HCD.3`:** may consume a compatible HCD.1 account as evidence input for a limiting-capability or non-training disposition; no target is entailed.
- **`HCD.4`:** may consume a compatible HCD.1 account as the scope and result frame for a condition-qualified profile comparison; no mastery or choice is entailed.
- **Programme comparison (`HCD.2`):** may consume the compatible demand account and evidence needs. HCD.1 derives demand without selecting a programme or requiring a programme-comparison result.
- **Clinical, safety, legal, employment, specialist, organization, provider, and release owners:** retain their direct decisions and authority.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): FPF spec://ai.lev/fpf-spec/contract/A-15-1#root, spec://ai.lev/fpf-spec/contract/E-23-CDI#root; direct later-Work and target-domain evidence @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-hcd/contract/HCD-11#root, spec://ai.lev/fpf-eng-hcd/contract/HCD-2#root, spec://ai.lev/fpf-eng-hcd/contract/HCD-3#root, spec://ai.lev/fpf-eng-hcd/contract/HCD-4#root, spec://ai.lev/fpf-eng-oce/contract/OCE-10#root @status:spec/done

#source spec://ai.lev/fpf-eng-hcd/source/HCD-1
