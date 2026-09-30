# HCD.6 - Design Representative Practice Tasks: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Human Capability Development Principles Framework* (28 September 2026 — twenty-nine-pattern edition), `Engineering DPF Suite/HUMAN-CAPABILITY-DEVELOPMENT-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## HCD.6:5 - Archetypal Grounding {#archetypal-grounding}

### HCD.6:5.1 - Pump Explanation and a Pressure Change {#pump-explanation-and-a-pressure-change}

The stipulated demonstration begins with a pump delivering 100 m³/h at 400 kPa and 20 kW. After a controller change, measured flow remains 100 m³/h and power becomes 22.4 kW, while comparable pressure data are absent. The worked explanation calculates the 12% rise in energy per volume and keeps resistance, regulation efficiency, and measurement error as rivals.

The task supplies the domain comparison: at the same flow and previous efficiency, increased pressure requires greater power; reduced regulation efficiency can also increase electrical demand. A pressure value near 448 kPa would support increased resistance under those conditions, while a value near 400 kPa would direct attention toward regulation efficiency. Neither value establishes a unique cause by itself.

The controller log and four specialist-hours are available. The supplied complete measurement contributions cost one hour for independent power, one and a half for flow, and one and a half for pressure; they include safe preparation, measurement and result return. A day-long shutdown is outside the allowed arrangement. The learner has ninety minutes to justify the observations and next decision, including explanation and comparison. For the selected pressure branch, changing the receiving engineer's next diagnostic question warrants the remaining specialist contribution and the learner's effort, including displaced work. Selection does not supply a pressure result.

The first attempt receives independent measurements of 22.3 kW and 99.5 m³/h, with uncertainties of 0.2 kW and 1 m³/h respectively. Ask the person to compare like quantities and use both uncertainty bounds. Even the lowest new ratio, 22.1/100.5, exceeds the stipulated baseline 20/100; this weakens the measurement-error explanation under the supplied conditions. After the power and flow contributions, one and a half specialist-hours remain for pressure. The learner can select that observation and explain how its possible values change the resistance/efficiency comparison while keeping the cause unresolved.

The target action is conditional explanation and a present response suited to the available basis, not arithmetic alone. In a later variant without a worthwhile obtainable observation, the learner can finish the qualified explanation with its live rivals and return that account while leaving a resistance-specific remedy unselected. A unique cause remains unproved. A renamed machine with the same numbers would add no useful variation; neither does a generic request to collect more data.

### HCD.6:5.2 - Ticket Load after Duplicate Removal {#ticket-load-after-duplicate-removal}

Four people each have six active-processing hours per day. Incoming records rise from 50 to 80 and each distinct request takes 18 minutes. The initial worked case shows that 50 and 80 distinct requests require 15 and 24 person-hours; the observed queue alone does not establish lower individual productivity.

In a stipulated variation, the 80 records include 20 duplicate messages attached to existing requests, leaving 60 distinct requests. The target action is to recognize that the unit of account changed before calculating 18 person-hours of active processing.

Now leave the duplicate count unknown and ask whether the day's requests fit the stated active-processing capacity. There can be no more than 80 distinct requests: at 18 minutes each, they require **at most 24 person-hours**, equal to the four people's supplied capacity. Return that sufficient upper bound and keep the exact count unknown. The answer concerns active effort under the stipulated processing assumptions; it establishes no queue-clearance, response-time or safety guarantee. Obtaining the count is unnecessary for this answer.

Change the receiving use to an allocation that needs the exact active-processing load of these requests. The upper bound no longer supplies that quantity. Stipulate an authorized existing request view and five minutes of available coordinator time to open it, resolve the duplicate labels and check the total. Correcting the allocation warrants that obtainable burden. Obtain the count for this use; until it is available, retain the upper bound with the exact allocation unresolved. If the view supplies 60 distinct requests, the processing load is 18 person-hours. The five minutes of coordination are an additional cost, not request-processing time or free work.

These cases distinguish a changed unit, a sufficient bound and a receiving use that needs another quantity. Merely replacing the support team with a warehouse would not test those distinctions.

### HCD.6:5.3 - FW7 Refusal and FW8 Continuation {#fw7-refusal-and-fw8-continuation}

The first engineering case supplies a vendor report for FW7 while the intended release configuration requires HW3/FW8/SCHED2. The correct action is to identify the mismatch and withhold that use; a correct financial calculation cannot repair incompatible evidence.

The varied case supplies a report for HW3/FW8/SCHED2, confirms mandatory checks, and leaves 24 test hours. Ten changes in three homogeneous batches require 23 hours. The person should propose the bounded ten-change use and preserve the continuing queue when demand is twelve. Repeating the earlier refusal is now wrong because compatible evidence is present. When available time falls to 22 hours, promising ten changes becomes unsupported again.

This task family makes evidence applicability and the resource calculation jointly visible. It tests a warranted refusal, a supported continuation, and a changed constraint rather than rewarding universal caution.

### HCD.6:5.4 - AI-Supported Practice without Attribution Drift {#ai-supported-practice-without-attribution-drift}

AI may propose sources, calculations, alternatives, or draft wording in a practice task. The task description states which actions the person still performs: checking decisive references, configuration, assumptions and calculations; selecting the Method; explaining the result; and returning unsupported claims. A later attempt may remove AI for a narrow independent contribution while retaining supplied tables and a calculator. The supported and changed-support attempts remain separate in the practice history; neither is silently upgraded to transfer or retention evidence.

### HCD.6:5.5 - Correct the Same Action before Adding a New Condition {#correct-the-same-action-before-adding-a-new-condition}

A trainee must enter a measurement and its unit in an inspection record. The teaching data give **2.4 mV**; the criterion is to preserve both the number and unit. Design the first task with a worked row available if the trainee needs it. If the trainee writes **2.4 V**, feedback points to the unit on the supplied reading and asks the trainee to correct the entry. The same reading is suitable for this correction: changing it would add a different demand before the present action has been repaired.

That corrected entry is a useful supported practice result. When the later question is whether the trainee independently preserves units on a new reading, supply another reading and withhold the answer-bearing worked row. If later work also requires unit conversion, a separate variant can ask for **0.0024 V** to be entered in a column marked **mV**, whose correct value is **2.4**. Select that variant only for the conversion target. Each task keeps its own help and conclusion; the design alone establishes no learner performance.

## HCD.6:6 - Bias-Annotation {#bias-annotation}

Lenses: **Gov**, **Arch**, **Onto/Epist**, **Prag**, **Did**. Scope: representative practice-task design for a named human contribution or an explicitly conditional future-audience branch.

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| surface-realism bias | A workplace story or visual detail is treated as representation. | Preserve the relations and conditions that elicit and discriminate the target action. |
| difficulty bias | More complexity is assumed to create more learning. | Remove irrelevant burden and vary only what changes the Method, action, or interpretation. |
| cue blindness | Method names, intermediate prompts, or AI output supply the answer being tested. | Declare permitted help; remove the answer-bearing cue when the attempt must elicit that contribution independently. |
| tool-removal bias | All references and tools are removed in the name of independence. | Retain legitimate later-Work supports and isolate only the human contribution the current task targets. |
| caution bias | Refusal is accepted in every uncertain case. | Include sufficient-evidence cases that require bounded action as well as genuine missing-evidence stops. |
| answer-key bias | The final answer is checked while the reasoning, source applicability, or critical error remains hidden. | Require the decision-bearing intermediate action and use domain criteria. |
| production-copy bias | A real case is copied without controlling risk, access, or confounding contributions. | Build a sufficiently whole bounded task and return professional facts to qualified owners. |
| assessment leakage | A supported or corrected practice attempt is reported as independent capability. | State each task's evidence purpose and preserve help and contamination history. |

## HCD.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Why it fails | Repair |
| --- | --- | --- |
| “Change the pump to a ticket queue” | New nouns can preserve the same cue and answer. | Change a relation or condition that alters the warranted Method or result. |
| “Use a real project” | Production realism can add uncontrolled risk, access limits, and other human or specialist contributions. | Bound the task around the target action and obtain qualified domain and safety inputs. |
| “Repeating the shown answer demonstrates adaptation” | The repeated answer may depend on memory of that case. | Keep its legitimate practice use; test adaptation through a changed condition without supplying the answer being judged. |
| “No help means independent” | Removing legitimate references or tools can test a different contribution from later Work. | Specify the exact human contribution and retain compatible support conditions. |
| “Always refuse if evidence is uncertain” | Generic caution fails when sufficient compatible evidence supports bounded action. | Pair missing-evidence and sufficient-evidence variants with explicit criteria. |
| “The learner got it after feedback” | Corrected practice is contaminated by the feedback event. | Record help and test the affected action on a changed task before stronger inference. |
| “Harder is more representative” | Difficulty without target relevance raises burden and obscures the result. | Scale complexity to current knowledge and the action being elicited. |
| “The answer key defines professional truth” | An invented key can encode unsafe or wrong domain guidance. | Obtain a qualified domain source or label stipulated teaching facts and their limits. |

## HCD.6:10 - Rationale {#rationale}

A practice task is representative relative to the target contribution and intended evidence claim. It preserves the relations needed for that contribution and use, not every detail of the workplace. This permits bounded safe practice while protecting domain truth.

Supported acquisition and correction can use the same task; a changed-condition attempt answers a different question when recognition or adaptation is required. Separating those uses keeps the learning contribution of help visible while preserving the limits of the resulting evidence. Designing both refusal and continuation cases prevents a safety-oriented boundary from becoming inert caution. The resulting work products give HCD.9 a focused practice object and HCD.11 an interpretable attempt without making their later conclusions in advance.

## HCD.6:11 - SoTA-Echoing {#sota-echoing}

The working question is: **How should a practitioner design practice tasks that elicit a target human contribution and support meaningful correction and variation without mistaking surface realism for representation?**

The selected best-known line combines sufficiently whole complex tasks, expertise-sensitive worked support, and decision-bearing variation. The maintained [4C/ID model](https://www.4cid.org/about/) and its [fourth-edition presentation](https://www.4cid.org/readings/books/) supply the serious whole-task design candidate: learning tasks, support for non-routine reasoning, timely procedural information, and additional practice for recurrent parts. Paas and van Merriënboer's 2020 review ([`COG-05`](https://doi.org/10.1177/0963721420922183)) supports worked examples and integrated information for novices while warning that unchanged guidance can become redundant as task knowledge grows. HCD.6 adapts these contributions into §§4.2–4.3 and the separation of whole-task and focused-part practice. The amount of help and the use of a repeated or varied task follow the learning purpose and starting capability; the sources do not prescribe a changed condition for every correction.

The serious ordinary alternative is a topic exercise or surface-isomorphic scenario: present the rule, vary the nouns and numbers, and score the final answer. It is cheaper to produce, but it can preserve answer-bearing cues, omit the later-Work purpose and interfaces, and reward either calculation without judgement or generic caution. HCD.6 rejects surface change as representation and adds the decision-bearing variation, human/support allocation, domain criteria, and correction task in §§4.1–4.6.

Brunmair and Richter's 2019 meta-analysis ([`COG-03`](https://doi.org/10.1037/bul0000209)) supplies limit evidence that interleaving varies by material and similarity; it does not prescribe one mixed task set. Czyż, Wójcik, and Solarská's 2024 motor-learning review ([`COG-04`](https://doi.org/10.3389/fpsyg.2024.1377122)) supports testing delayed transfer while its applied estimate and cross-domain reach remain weak. Bastani and colleagues' 2025 school-mathematics trial ([`AI-04`](https://doi.org/10.1073/pnas.2422633122)) supports separating assisted practice from a later unassisted attempt; it does not supply an adult engineering effect or a universal AI ban. These sources change the task contrasts and evidence-purpose boundary rather than selecting one universal schedule.

The selected line costs more domain and case-design effort than renaming exercises, but it preserves action interpretability, legitimate support, critical errors, and the opportunity to learn from a changed result. Reopen it when stronger sources alter the whole-task, worked-support, variation, AI-help, or transfer boundary, or when representative use shows a lower-effort task design that preserves the same decision-bearing relations and evidence value.


## HCD.6:End {#end}
