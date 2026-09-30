# HCD.4 — Architect a Balanced Human Capability Profile Across Simultaneous Work {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Human Capability Development Principles Framework* (28 September 2026 — twenty-nine-pattern edition), `Engineering DPF Suite/HUMAN-CAPABILITY-DEVELOPMENT-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Human Capability Development practitioner profile-and-choice pattern
> **Status:** Stable


## HCD.4:0 - Use This When {#use-this-when}

Use this pattern when one named person's later Work requires several contributions at once and a manager, practitioner, or the person needs to know what to preserve, investigate, defer, or make a development priority. Begin with a compatible HCD.1 demand account or equivalent qualified scope and compare the claims one by one; do not begin with a course sequence, mastery ladder, role level, platform score, or one total.

With compatible scope and claim-level evidence, the first useful result is a **condition-qualified human capability profile**: priority characteristics, explicit trade-offs, limiting gaps, and a recommendation or unresolved question for one named decision owner. If a bounded choice is also requested, apply the `C.11` requirements in §4.4. Missing choice inputs block that choice; keep any comparison and recommendation that the scope and evidence support. If required scope or profile evidence is missing, return `profile-decision-blocked` for the affected conclusion with the missing value and retry condition.

The practical gain is a profile that preserves strong contributions while exposing one consequential gap and its uncertainty. Use `HCD.1` when the demand frame is missing. Use `HCD.3` when the limiting cause or target is unresolved. A separate programme comparison (`HCD.2`) may use the profile; HCD.4 neither requires nor invents a programme.

Do not use this pattern to claim current mastery from an aggregate, prescribe curriculum or provider, assert a learning trajectory or transformation, perform ongoing-Work steering, decide employment, safety, legal, clinical, or release matters, or treat an assisting System as the chooser by label alone.

## HCD.4:0.1 - Working Terms {#working-terms}

| Name in this pattern | What it denotes |
| --- | --- |
| capability claim | One condition-qualified claim about a human contribution or interface needed in representative later Work. It is not a course outcome, trait label, or scalar coordinate by itself. |
| current profile | The set of supported current claim dispositions for one human holder, configuration, conditions, evidence window, and date. |
| target profile | The set of intended claim dispositions justified by representative later Work. It is not proof that the holder obtained them. |
| intermediate state | An optional description of a contribution and result boundary between the current and target profiles, under named conditions. Distinguish an intended intermediate target from an observed state. |
| profile difference | The claim-by-claim current-versus-target comparison, including preserved strengths, gaps, uncertainty, support dependence, critical errors, and trade-offs. |
| bounded profile decision | A lawful `C.11` choice over an already-available option set, supported by the profile comparison and kept separate from authorization, commitment, and later Work. |
| profile-decision-blocked | A substantive return naming a missing value required for the affected conclusion—scope, evidence, chooser, option, comparison, applicable inquiry input, participation or authority—and its retry condition. |
| simultaneous Work | Representative Work whose contributions or interfaces coexist, overlap, recur, or constrain one another; printed order does not make them a sequence or hierarchy. |

Current and target profiles describe supported and intended contributions. A profile difference compares those descriptions, and an optional aggregate summarizes selected claims. A curriculum plans instruction. Keep these descriptions, comparisons, and plans separate from the person's realized learning trajectory, the Work performed in learning, and any human transformation. Claims about what happened or changed need evidence of those occurrences.

## HCD.4:1 - Problem Frame {#problem-frame}

A person can be strong in three contributions and weak in a fourth. One contribution may be safe only with a specialist return; another may be independent of a tool; a third may fail only in unfamiliar variants. A single level or average can hide the critical asymmetry that should drive the next decision.

Visible source structures are seductive. A course order can look like a capability hierarchy, a Method decomposition can look like a development sequence, an organization chart can look like a profile, and a platform prediction can look like mastery. In simultaneous Work these structures need not line up one-for-one.

A profile must therefore preserve claim identity, conditions, evidence, support dependence, uncertainty, critical-error boundaries, and trade-offs. It may inform a choice, but choice requires a real chooser, current options and an adequate comparison basis. Inquiry values are needed when further inquiry is live under `C.11`, not as fields to complete for every choice.

## HCD.4:2 - Problem {#problem}

The common shortcut is to compress unlike claims into one score and then optimize the score. The resulting decision can trade away an already-reliable safety boundary, conceal unsupported transfer, or treat assisted performance as independent human capability.

The opposite shortcut records many dimensions but never closes a practical question. The practitioner needs a readable comparison that says what to preserve, what gap matters, what uncertainty is decision-changing, and whether to choose, probe, reroute, or stop—without fabricating a programme or authority.

## HCD.4:3 - Forces {#forces}

- A scalar is easy to compare, while claim identity, asymmetry, critical-error status, support dependence, and uncertainty may be decision-bearing.
- A staged course or Method hierarchy is easy to draw, while the way human contributions constrain one another in later Work need not follow that order or hierarchy.
- Target states guide development, while current evidence and actual transformation must not be inferred from the target.
- Assisted scores can predict performance, while platform or AI output is model- and condition-dependent evidence rather than mastery.
- Self-monitoring can improve, while self-report and confidence do not establish later-Work capability.
- A recommendation helps an owner act, while the profile does not create authority, options, budget, or commitment.
- Another probe can reduce uncertainty, while probing consumes time and may itself change the holder or Work.
- Preserving every strength is attractive, while real trade-offs may move time, workload, autonomy, support, or risk.
- Human participation matters, while manager, safety, release, clinical, and employment owners retain different decisions.

## HCD.4:4 - Solution {#solution}

Build the profile as a set of evidence-bound claim rows across simultaneous representative Work. Compare current and target dispositions without imposing a source sequence, expose trade-offs, and close only the decision that the current evidence and authority support.

### HCD.4:4.1 - Bind the Profile Use {#bind-the-profile-use}

Name:

1. the exact human holder and holder participation basis;
2. the HCD.1 demand account or equivalent qualified scope, including later-Work family, configuration, conditions, effective horizon, evidence window, and receiving decision;
3. the named profile decision owner and every direct owner whose authority or result remains external;
4. the representative cases and simultaneous contribution interfaces that can change the comparison; and
5. the protected consequences, critical errors, privacy or worker-governance conditions, and stop boundaries.

If the same-holder scope cannot be recovered, return `profile-decision-blocked` for the missing demand frame. Do not substitute a role profile, population average, course map, or imagined future person.

### HCD.4:4.2 - Build Claim Rows {#build-claim-rows}

For each selected capability claim, record:

| Claim field | Required content |
| --- | --- |
| contribution and interface | What the human contribution supports in representative later Work and which simultaneous contributions, tools, or specialist returns it interfaces with. |
| current disposition | Current evidence, conditions, support dependence, date, uncertainty, and any critical-error observation; `unsupported` is preferable to an invented level. |
| target disposition | The contribution and result boundary demanded by representative later Work, with its source and horizon. |
| intermediate disposition | The intermediate contribution, result boundary, and conditions, only when they help this decision. Keep a proposed next action separate from the state description. A threshold may define an intended result boundary, but a claim that it was reached needs observations. |
| discriminating evidence | Representative task, observation, work product, inference rule, and protected consequence that distinguish the claim. |
| trade-off and conflict | What time, workload, autonomy, support, evidence burden, or other claim could be harmed by prioritizing this one. |
| next change point | The nearest observation, source return, owner decision, or condition that can change the row. |

Use an aggregate only when the receiving decision does not need any claim identity, asymmetry, critical-error status, support dependence, or uncertainty that the aggregate removes. Keep the underlying rows available whenever an aggregate is used.

### HCD.4:4.3 - Compare Without Inventing Order {#compare-without-inventing-order}

Apply `C.32.MWA`'s guard against layout substitution. A course sequence, Method hierarchy, Work order, organization chart, or platform dashboard may be a source structure; none is the profile architecture merely because its rows line up with capability names.

Ask which contributions are simultaneous, which interfaces constrain each other, which supported claims must be preserved, which gaps are limiting, and where a local gain moves burden or risk. State the current profile, target profile, difference, priority characteristics, explicit trade-offs, and the recommendation or unresolved question before making a choice.

### HCD.4:4.4 - Make a Bounded Choice Under C.11 {#make-a-bounded-choice-under-c-11}

When a bounded choice is requested, obtain the inputs and conditions required by `C.11`:

| `C.11` input or condition | HCD.4 use |
| --- | --- |
| `DecisionSubject` and `DecisionSubjectGranularity` | The actual chooser and chooser-bearing level. Do not default to generic `Agent`; route unresolved agency to `A.13`. |
| `OptionSet` | Concrete options already on the table. HCD.4 does not generate a missing programme alternative. |
| `PreferenceOrder` or `EvaluativeMeasure` | The explicit comparison basis, including protected claims and unacceptable critical errors. |
| `BeliefState` | Current uncertainty, evidence limits, and live rivals shared across the options. |
| `OutcomeModel` | How the options and uncertainty map to the consequences that matter for this choice. |
| dependence layer | Evidential by default; causal, counterfactual, subjunctive, or other heavier dependence requires its own current support. |
| `ChoiceRule` | The condition under which `choose now`, `reject current set`, `probe again`, or `reroute` is lawful. |
| probe-worthiness | When inquiry is live under `C.11`—through a current proposal, consequential uncertainty or an applicable requirement that could change the choice or warranted use—obtain the relevant `ProbeActionSet`, `ProbeBudget`, `CostToProbe`, and value of information or computation. Otherwise these fields do not apply to finishing the supported choice. |
| governance | Holder participation and the chooser's applicable authority; authorization, commitment, and later execution remain separate. |

If a required input, condition, or necessary current/target evidence is absent, keep the profile comparison and recommendation if they are supported, then return `profile-decision-blocked` with the missing value, blocked choice, safe boundary, and retry condition.

With the required inputs and conditions established, the chooser applies the explicit `ChoiceRule` to the current comparison basis, dependence layer and any applicable inquiry values. Emit a `ChoiceResult` with the lawful disposition, its reason and the next question specified by `C.11`. The decision record documents this application, the inputs used and the emitted result.

Finish an already supported choice without creating a study, empty probe fields or a separate justification for omitting inquiry. Keep the profile, actual choice grounds and any short reason or limitation needed by this decision or a later recipient in that same result. A live feasible probe can still be selected when its attainable contribution justifies its whole burden. An evidence limit remains a limit when acquisition is not selected.

### HCD.4:4.5 - Recognition and Assurance {#recognition-and-assurance}

**Recognition.** Use HCD.4 when a conversation contains “well-rounded,” “level up,” “mastery score,” “skills matrix,” “promotion profile,” or a course pathway, while the actual decision depends on several different contributions to later Work.

**Assurance.** Stronger reliance requires holder- and condition-compatible task evidence for each decision-bearing claim; explicit current, target, and uncertainty positions; preservation of critical-error and support-dependence boundaries; an inspectable trade-off account; and, for a choice, all required current `C.11` inputs and conditions, application of the rule, and an inspectable result. High-stakes employment, clinical, safety, legal, or release uses need their direct owner and assurance in addition to this profile.

### HCD.4:4.6 - What Changes in Practice {#what-changes-in-practice}

A practitioner stops asking, “What level is this person?” and asks, “Which contributions are supported under which conditions, which must be preserved, which gap matters across simultaneous Work, and what uncertainty could still reverse the decision?” The profile returns a useful comparison even when no choice is yet lawful.

## HCD.4:7 - Conformance Checklist {#conformance-checklist}

- [ ] One exact human holder and a compatible HCD.1 demand account or equivalent qualified scope are recoverable.
- [ ] Later-Work family, configuration, conditions, horizon, evidence window, receiving decision, and representative simultaneous interfaces are explicit.
- [ ] Each claim row states contribution, current evidence, target, optional intermediate only when useful, conditions, support posture, observation date, uncertainty, discriminating task/evidence, critical-error boundary, trade-off, and next change point.
- [ ] Profile descriptions and their comparison or aggregate are distinguished from instructional plans, realized learning trajectory, performed learning Work, and human transformation; occurrence and change claims have corresponding evidence.
- [ ] Any source structure used for the profile is justified by the contributions and mutual constraints in representative Work.
- [ ] Supported claims to preserve are visible alongside gaps and trade-offs.
- [ ] An aggregate is used only when it removes no decision-bearing identity, asymmetry, critical-error, support, or uncertainty value.
- [ ] The profile first returns priority characteristics, trade-offs, limiting gaps, and a recommendation or unresolved question to one named owner.
- [ ] For any bounded choice, the chooser has applied the `ChoiceRule` to the required current `C.11` inputs; the record includes chooser granularity, pre-existing options, comparison basis, belief, outcome model, rule, applicable inquiry values, emitted result, participation and authority. Keep a reason or limit needed for this or a later use in the substantive result.
- [ ] A missing decision or evidence value required for the affected conclusion produces `profile-decision-blocked` with blocked choice, safe boundary, and exact retry condition.
- [ ] The result fabricates no HCD.2 programme and authorizes no curriculum, provider, employment, safety, legal, clinical, or release action.
- [ ] The receiver can identify claims to preserve, the consequential gap, what could reverse the recommendation, and who decides next.

## HCD.4:9 - Consequences {#consequences}

The result makes a profile usable without flattening it. Practitioners can preserve reliable contributions, expose one limiting gap, show the cost of prioritization, and distinguish a recommendation from a lawful choice. Missing required evidence or choice values become exact blockers instead of silently completed forms; an inapplicable inquiry field blocks nothing.

The cost is a larger evidence surface than one score. Claim rows can disagree, uncertainty can remain, and the lawful result may be `probe again` or reroute rather than a selected priority. A later programme, intervention, or employment decision still needs its own Method and authority.

## HCD.4:12 - Relations {#relations}

- **`HCD.1`:** supplies the same-holder scope and result frame. An equivalent qualified demand account may substitute; an incompatible population profile may not.
- **`HCD.3`:** may supply a qualified target and any still-plausible rival as evidence. HCD.4 does not inherit an intervention, programme, or transformation claim.
- **`C.32.MWA`:** prevents course sequence, Method hierarchy, Work order, organization chart, model, or platform layout from becoming the profile architecture by alignment alone.
- **[Winget and Persky’s review (2022)](https://doi.org/10.5688/ajpe8906) (`COG-06`):** supplies the local-threshold, correction, and retest contribution, not a universal mastery ladder.
- **[Gutierrez de Blume’s meta-analysis (2022)](https://doi.org/10.1037/edu0000674) (`COG-07`):** supplies self-monitoring accuracy as one bounded evidence source.
- **[Arieli-Attali and colleagues’ design framework (2019)](https://doi.org/10.3389/fpsyg.2019.00853) (`COG-08`):** supplies claim/task/evidence/inference traceability, not a causal intervention result.
- **[Abdelrahman and colleagues’ survey (2023)](https://doi.org/10.1145/3569576) (`COG-09`):** supplies model-prediction limits; a predicted state does not establish this person's mastery.
- **`C.11`:** governs one local choice over a current `OptionSet` and emits `choose now`, `reject current set`, `probe again`, or `reroute` under an explicit `ChoiceRule`.
- **`A.13`:** receives an unresolved agency claim when an assisting System, coupled arrangement, team, or organization is proposed as chooser.
- **`E.23.CAE` and `E.23.CDI`:** may supply differential or later development/transfer evidence under their own entry conditions; neither is implied by a profile.
- **Target-domain and specialist sources:** provide criteria and evidence for correctness, quality, criticality, safety, legal, clinical, and specialist-return questions in the claim rows. Qualified specialists supply professional judgements, and authorized actors make the corresponding decisions.
- **Programme comparison (`HCD.2`):** may receive priority characteristics and trade-offs as fit criteria for the same person, later Work, and decision. HCD.4 requires no programme-comparison result and does not fabricate programme alternatives.
- **Managers and direct decision owners:** retain allocation, assignment, employment, safety, legal, clinical, and release authority; the human holder's participation remains explicit.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-hcd/contract/HCD-1#root or equivalent qualified input; FPF spec://ai.lev/fpf-spec/contract/C-32-MWA#root, spec://ai.lev/fpf-spec/contract/C-11#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-hcd/contract/HCD-2#root, spec://ai.lev/fpf-eng-oce/contract/OCE-10#root @status:spec/done

#source spec://ai.lev/fpf-eng-hcd/source/HCD-4
