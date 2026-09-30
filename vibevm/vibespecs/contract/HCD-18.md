# HCD.18 - Select or Construct a Characterization and Evaluation Specification for Instructional Material {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Human Capability Development Principles Framework* (28 September 2026 — twenty-nine-pattern edition), `Engineering DPF Suite/HUMAN-CAPABILITY-DEVELOPMENT-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Human Capability Development practitioner evaluation-specification construction pattern
> **Status:** Stable

## HCD.18:0 - Use This When {#use-this-when}

Use this pattern when you must decide what to repair, select, or rely on in instructional material, but the available evaluation cannot distinguish the material's useful contribution from an attractive presentation, a correct answer supplied by an expert, or help supplied by a teacher.

An editor preparing a worksheet, a teacher choosing a worked explanation, and a designer evaluating a connected course route face the same first question: **what work should this material help this audience do, with what support?** Write that promise and one task that would expose a consequential failure. Then check whether an existing specification already answers it.

The first useful result is either a compatible specification ready for evaluation, or a new specification that tells an evaluator what to inspect, how to interpret observations, and what decision each difference can change. The specification concerns the instructional material in its declared use. Wider human capability development remains outside this construction task.

If a compatible specification is already available, use it directly through HCD.19. If the question is one person's performance, transfer, or retention, use HCD.11, HCD.12, or HCD.13. A professional reference used to make a decision is evaluated for that reference use; it acquires a learning-task requirement only when it promises instruction.

## HCD.18:0.1 - Working Terms {#working-terms}

| Term | Meaning in this pattern |
| --- | --- |
| Instructional material | The explanations, examples, tasks, representations, and usable returns offered to support specified learning work. A worksheet, book, or guided interface may carry this content. |
| Declared use | The audience, tasks, prerequisites, ordinary assistance, and decision for which the evaluation is intended. |
| Task denominator | The work and consequential variations the material promises to support, recovered from that work and its subject requirements rather than counted from the material's headings. |
| Characteristic | A property whose possible values can change use, repair, evidence collection, or protection of another property. |
| Evaluation specification | The defined object and use, selected characteristics and scales, evidence requirements, result meanings, and conditions under which an evaluator may draw a conclusion. |
| Material value | A qualified judgement about a selected property of the material. The evidence supporting the judgement and the material's fit to the specification remain separately interpretable. |

These are working terms, not new artifact types. A short written agreement can carry the specification when it supplies the required meaning.

## HCD.18:1 - Problem Frame {#problem-frame}

A time-accounting handout tells a learner to count from a task's first start to handoff. Its example contains no interruption, so the intended active effort and the elapsed turnaround have the same value. The example looks correct. A prepared reader later separates the quantities without help, while another reader may follow the handout's wrong general rule.

Counting correct answers alone would miss the defective explanation. Counting headings would find an explanation, an example, and a task and miss it again. A useful evaluation must make the distinction matter: introduce an interruption, ask for both quantities, inspect the explanation that supports them, and preserve what the reader supplied from prior knowledge.

The evaluator also needs to know what the material promises. A handout used with a teacher's corrective question has a different support arrangement from a self-study unit. The question can legitimately enable correction without proving that the first explanation enabled independent recognition.

A specification fixes these distinctions before observations are interpreted. It keeps subject truth, audience support, the task's validity, and the strength of the resulting inference connected without turning them into one score.

## HCD.18:2 - Problem {#problem}

How can a designer construct a small but complete evaluation specification that distinguishes action-changing material defects, supports defensible values and repairs, and exposes the evidence still needed for the declared use?

## HCD.18:3 - Forces {#forces}

- A reusable profile saves effort, but a fixed quality list can miss a task absent from the material itself.
- Shared observations can support several properties, while those properties require different repairs.
- A correct first answer can come from the material, prior expertise, or an available helper; the evaluation must distinguish those contributions when they change reliance.
- More detail can clarify a distinction or obstruct the next action. The property concerns support for the use, not volume.
- A usable ordinal judgement can guide repair without pretending to measure equal intervals or predict learning.
- A demanding task can reveal useful learning work or a missing prerequisite. Immediate ease cannot decide between them.

## HCD.18:4 - Solution {#solution}

Construct the specification from the intended work to the evidence and resulting decision. A.19.ECS supplies the general construction requirements; this pattern supplies their instructional-material application. The [instructional-material evaluation profile](spec://ai.lev/fpf-eng-hcd/pub/cross-pattern-application#instructional-material-evaluation-profile) offers selectable property families and an optional repair/use scale.

### HCD.18:4.1 - Recover the promise and stop if an existing specification fits {#recover-the-promise-and-stop-if-an-existing-specification-fits}

Name the material edition and the portion to be judged. Distinguish its content from a particular export when font size, navigation, image resolution, or interaction changes access. Identify the intended audience and prerequisites at the level that changes the tasks: “can add time intervals” is useful in the worked case; an invented demographic persona is not.

State the ordinary material, tools, source returns, teacher help, and peer or AI assistance. Separate what is promised from what is available and what later proves to be used. For an intended future audience, these are design conditions, not observations about already identified people.

Name the decision: for example, select between two explanations for a supervised exercise, repair a course's planning task, or authorize a specified self-study use. Say what a wrong positive conclusion would cost. This selects the evaluation grain and evidence burden.

Compare an existing specification by value: object kind, audience, task denominator, support arrangement, relied-on subject state, properties, value meanings, evidence, and consuming decision. A matching title or the same 0–5 labels do not establish compatibility. If the existing specification fits, stop construction and use it. If only one requirement changed, retain the compatible parts and repair the affected specification content.

### HCD.18:4.2 - Derive the tasks and contrast cases outside the present table of contents {#derive-the-tasks-and-contrast-cases-outside-the-present-table}

Start from the work the audience should be able to perform or practise. Recover its required distinctions, prerequisite operations, acceptable variants, and consequential errors from the problem and a qualified subject basis. A material's claim of coverage does not define its own denominator.

For each promised task, ask what a successful contribution would contain and which plausible wrong contribution an apparently adequate explanation might also produce. Choose a case on which the alternatives differ. In the time example, an uninterrupted interval cannot distinguish active effort from elapsed turnaround; an interruption can.

Compare this task-derived need with the actual explanations, examples, practice, and accessible returns. A precise external return can supply a contribution if it is usable by this audience at this point. A title that promises the contribution cannot.

Prepare three kinds of contrast:

- an in-scope material that supplies the needed contribution;
- an in-scope material with a consequential deficiency;
- a nearby object or use for which this specification would answer the wrong question.

These contrasts test fit as well as quality. A personal capability judgement is outside a material specification even when the same learner task appears in both.

Distinguish the subject basis from manufacturing history. An existing directly authored book can be evaluated without knowing how its author wrote it. If fidelity to a transcript, prescribed edition, or earlier rendering was promised, evaluate that source-to-material relation on its own evidence.

### HCD.18:4.3 - Select properties by the decisions their values change {#select-properties-by-the-decisions-their-values-change}

Use the profile's property families as a search aid. Keep a characteristic when its values can change the use decision, identify a distinct repair, call for different evidence, or protect a contribution that another repair might damage.

For each proposed characteristic, try two possible material conditions. If both would receive the same practical response and evidence requirement, refine the distinction or remove the redundant coordinate. Split a compound coordinate when its parts can fail independently with different repairs. Subject accuracy and currentness may share a passage but require different evidence; explanatory sufficiency and criterion validity can diverge when a correct explanation is followed by a key that rejects a valid answer.

Declare the characteristic's bearer and grain. A false arrow in one diagram, a missing operation across an explanation–exercise chain, and a whole-route omission have different reach. A local defect does not inherit the whole book's grain merely because the evaluator opened the whole book.

When the decision depends on how much selected structure a reader can extract, select [`C.2.8 U.ExtractableStructuralInformation`](spec://ai.lev/fpf-spec/contract/C-2-8#root). Identify the material episteme, its expressing publication form and the reader or observer; fix the selected relations and correctness basis, usable preparation, operations, help, access and budget only as precisely as this comparison needs. These conditions qualify the three bearers. A material reference may identify the account and expression without new paperwork. Explanatory sufficiency and overall material adequacy remain different questions.

Make the selected set complete for the declared decision. A short diagnostic can legitimately borrow two profile questions, but then its conclusion is a bounded diagnosis, not a complete material evaluation. Do not call an omitted required property “not applicable” merely because it is inconvenient to observe.

### HCD.18:4.4 - Bind values, evidence, and decisions without collapsing them {#bind-values-evidence-and-decisions-without-collapsing-them}

For each selected characteristic, define its value domain, scale type, polarity, anchors, and conditions of applicability. A numerical scale needs an interpretation: a count, a measured duration, and an ordinal repair judgement support different operations.

For structural amount, a qualitative account of additional and missing relations can suffice. A count or fraction needs fixed semantic units and a nonempty selected set; another scale needs the interpretation required by C.2.8. Keep the observed recovery, conditional design estimate or mapped formal estimate identifiable. A missing denominator or criterion is a gap, not zero. Define any required-relation use condition separately from amount; more unrelated structure cannot compensate for a missing necessary relation.

The profile's optional 0–5 rendering is ordinal. Its anchors distinguish absence of usable support, limited support, connected central repair, bounded repair, adequacy, and additional useful resilience. They describe material use and repair, not a structural amount, and do not license averages, equal-step differences, or a universal floor. Choose a floor only when the consuming decision needs one, and explain why that decision can rely on it. State any non-compensable condition at its actual grain.

Make adjacent values distinguishable in the domain. For explanatory sufficiency, distinguish rebuilding the central explanation–task chain from repairing one missing transition. Distinguish adequacy for the selected cases from an evidenced advantage across consequential variations. A value of 5 requires the latter advantage over 4, not more pages or a history of having been repaired.

Attach evidence requirements to each value. Source inspection can establish a false unit relation. It cannot establish how an unobserved learner experienced the passage. Where adequacy for the audience requires reader work, say what contribution must be observed and under which assistance conditions. Keep a missing observation explicit; lack of evidence is not the material value 0.

Define what a result returns for each selected coordinate: value or lawful missingness, evidence basis, limiting case, grounds against adjacent alternatives, implication for use, and smallest worthwhile repair. Shared evidence may be cited by several rows without being counted as independent observations.

Resolve differences at their cause. If two evaluators disagree between 2 and 3, trace whether the repair crosses a central connected chain or remains bounded. Do not average the judgements. If the disputed distinction repeatedly fails to change action, repair the scale rather than demand stronger agreement with an arbitrary label.

### HCD.18:4.5 - Make the specification usable by another evaluator {#make-the-specification-usable-by-another-evaluator}

The following content completes an A.19.ECS specification. A table is optional; the values are not.

| Specification content | What the evaluator must be able to recover |
| --- | --- |
| Object, use, and qualification | Exact material or material family, evaluation grain, audience prerequisites, tasks, assistance, subject/source state, consuming decision, and window in which the basis remains valid. |
| Fit and contrasts | In-scope adequate and deficient examples, outside-kind or outside-use example, entry decision, and the disposition of a forced invocation on an incompatible object. |
| Characteristics and scales | Selected properties, their applicability, value domains and scale types, polarity, anchors, any floor or exceptional-value condition, and protected trade-offs. |
| Evidence and calibration | Coordinate-specific evidence minima, qualified subject criteria, actual tasks and competing answers, admissible inference, missingness, known contrasts, and the needed reader or evaluator calibration. |
| Result and evidence payload | Every selected coordinate with value or missingness; material locus, task/observation, available and actual help, adjacent-value grounds, limiting example, repair, and claim limits. Preserve the task, criterion, first answer, and later assistance when they carry the inference. |
| Decisions and continuation | Supported-use, repair-needed, insufficient-evidence, disputed-criterion, and fit-defect meanings as needed; stop, reopen, and next-evidence conditions; the starting result for E.23 if improvement is needed. |
| Neighbouring claims and comparisons | Exact exits for human performance, transfer, retention, source fidelity, or production history. If selection among alternatives is live, the common comparison basis and E.22 use, including incomparable cases. |

A complete specification need not already have every observation that its later use requires. It must state the missing observations and prevent a stronger result from being claimed without them. Conversely, a calibrated illustration does not make every future application adequate.

An incompatible object normally stops before invocation. If an invocation is nevertheless required, return an explicit fit defect and the blocked conclusion. If a selected coordinate becomes unevaluable during an in-scope application, return its evidence or criterion defect in the complete result. Neither case authorizes silently dropping that coordinate.

### HCD.18:4.6 - Try the specification on contrasts and establish its continuation {#try-the-specification-on-contrasts-and-establish-its}

Have an evaluator use the same specification on its adequate, deficient, and outside-use contrasts. Examine the resulting decisions and repairs, not merely agreement on labels. Check whether a known central defect can pass because an example is ambiguous, whether a correct alternative is rejected, and whether a missing observation is mistakenly converted to a low material score.

Where an AI reader or evaluator is used, test the contribution it is actually able to make. Subject-grounded counterexamples can calibrate defect diagnosis; simulated novice behaviour cannot establish human learning. A fresh reader is useful when private knowledge of the intended defect or answer would defeat the selected inference.

Stop construction when another evaluator can identify the object and tasks, collect the specified evidence, return all selected coordinates with their limits, and decide the declared next move. An unresolved criterion or discriminating-evidence gap is a legitimate returned result.

Name the specification version when results will be compared later. A changed value meaning, task denominator, or support arrangement may invalidate numeric comparison with earlier results. Preserve earlier results under their original meanings; establish a justified comparison of meanings or decline equivalence. Reopen only the affected specification content when a new task, audience, source premise, assistance change, or recurrent calibration disagreement changes it.

## HCD.18:7 - Conformance Checklist {#conformance-checklist}

This is assurance guidance for a constructed specification; the working method is in sections 4 and 5.

- **HCD18-CC1.** The specification SHALL identify the material, grain, audience, tasks, prerequisites, assistance, subject basis, consuming decision, and qualification conditions.
- **HCD18-CC2.** The constructor SHALL check compatibility with an existing specification and derive the task denominator from the promised work rather than the present headings alone.
- **HCD18-CC3.** The specification SHALL provide adequate, deficient, and outside-use contrasts and preserve the distinction between fit, material value, and evidence.
- **HCD18-CC4.** Each selected characteristic SHALL have an action-changing purpose, applicability, scale binding, anchors, evidence requirements, and an explicit result or missingness disposition.
- **HCD18-CC5.** An ordinal numeric rendering SHALL NOT be treated as equal intervals or silently averaged. Any floor, exceptional value, comparison, or non-compensable condition SHALL be justified for the consuming use.
- **HCD18-CC6.** The result requirements SHALL preserve the evidence and adjacent-value grounds needed to recover the judgement, including first response and actual assistance when they change the inference.
- **HCD18-CC7.** Calibration SHALL test discriminating contrasts and preserve criterion or evidence disagreements. Constructed cases SHALL be distinguished from observed reader work.
- **HCD18-CC8.** The specification SHALL state supported conclusions, stops, reopens, neighbouring-claim exits, and the E.23 starting result when repair is needed.

## HCD.18:9 - Consequences {#consequences}

A constructed specification makes the next evaluation executable: the evaluator knows what work matters, what a defect would change, what evidence to obtain, and which stronger conclusion remains unavailable. Repairs can target a criterion, example, explanation, return, or assistance arrangement instead of expanding the material indiscriminately.

The cost is up-front task and contrast design. That cost is worthwhile when an intuitive score could drive consequential selection or repair. A compatible existing specification avoids repeating it. New audiences or purposes can require a changed specification; preserving the original result meanings makes that change inspectable.

## HCD.18:12 - Relations {#relations}

- **A.19.ECS** defines the general content of an evaluation specification and its fit, evidence, comparison, and continuation requirements. **A.17, A.18, and C.16** retain the general characteristic and scale meanings used by its bindings.
- **HCD.19** applies a compatible specification to instructional material and representative reader work. **E.22** supplies comparison when selection is live; **E.23** supplies improvement from the resulting defect and protected trade-offs.
- **HCD.3 and HCD.6** can supply the target contribution and representative task design. HCD.18 can also use qualified task and audience inputs obtained elsewhere; those patterns are not mandatory preliminary stages.
- **HCD.11, HCD.12, and HCD.13** govern evidence about human performance, transfer, and retention. A material judgement contributes to those questions without replacing their evidence.
- **NSTD.6 and NSTD.8** contribute current narrative-product adequacy, attachment, and progressive reconstruction when the selected material's narrative use makes those properties live.
- **E.4.DPF.DA** governs the adequacy of a DPF package used as a framework. An instructional-material profile applies additionally only for an instructional promise; it does not turn every reference framework into a course.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-spec/contract/A-19-ECS#root; instructional-material profile; qualified task, subject and assistance conditions @status:spec/done

#source spec://ai.lev/fpf-eng-hcd/source/HCD-18
