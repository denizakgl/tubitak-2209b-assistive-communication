# Illustrative Testing Approach

[Back to the project](../README.md)

**Prepared for this portfolio on 31 October 2026. These scenarios have not been executed or verified as part of this documentation work. They are not historical test results or evidence that Devran Deniz Akgül performed the proposed tests.**

## Connection to the research plan

The proposal calls for functional tests, usability/accessibility evaluation, user-feedback review and final user testing. This document provides a small set of original example scenarios derived from that scope. Detailed steps and expected observations below are portfolio suggestions, not a recovered project test specification.

An authorized application build, agreed requirements, selected target devices and appropriate test data would be needed before execution. Use synthetic text and self-created or properly licensed images; no real participant photos, health information or user records are included here.

## Illustrative scenarios

| ID | Focus | Example procedure | Observation to evaluate | Status |
| --- | --- | --- | --- | --- |
| TA-01 | Personalized content | In Parent/Caregiver Mode, create an item with a synthetic image and a short label; open the corresponding Individual Mode view | The intended item and associated label are available to the intended individual | Not executed |
| TA-02 | Speech association | Select two different synthetic items and request their speech output, using the build's actual interaction | The spoken content corresponds to the selected item's associated text | Not executed |
| TA-03 | Content updates | Change a synthetic item's label or image through the caregiver workflow; revisit the individual view | The relevant view reflects the change according to the agreed synchronization behavior | Not executed |
| TA-04 | Caregiver notification | With authorized test accounts and configured permissions, trigger an interaction designated to generate a notification | The intended caregiver receives the expected event without information belonging to another test account | Not executed |
| TA-05 | Connection interruption | Interrupt connectivity during a synthetic content operation, then restore it | Observe error feedback, saved state and recovery behavior; acceptance criteria would need agreement first | Not executed |
| TA-06 | Interface review | Review both modes on agreed devices for clear labels, readable content and understandable feedback | Record usability/accessibility concerns without treating a review as compliance certification or user validation | Not executed |
| TA-07 | Regression after a change | After an authorized team change, repeat the affected scenario and related content, speech and notification checks | Determine whether the reported issue recurs and whether related behavior has changed | Not executed |

TA-01 to TA-04 address proposed features. TA-05 to TA-07 extend the proposal's general testing and risk themes into suggested checks. Their precise behavior, scope and acceptance criteria require agreement with the implementation team.

## Suggested execution record

For a future authorized run, record the scenario ID, application build, device/OS, preconditions, synthetic test data, steps, expected behavior, actual behavior, result and any sanitized defect reference. Keep an unexecuted scenario separate from a passing or failing result.

If a concern is found, document reproducible behavior for the implementation team. Rechecking a developer's fix is distinct from writing that fix; any future contribution description should retain that distinction.

## Feedback and end-user evaluation

Actual end-user studies would require a suitable protocol, agreed consent and data-handling arrangements, and project-team oversight. This document contains no participant records, consent claims or evidence of a completed study. Interface inspection with synthetic content cannot establish improved communication outcomes for real users.

## Evidence limits

No application build or source code was available for this portfolio review. Consequently, this repository reports no executed test count, pass rate, defect-reduction percentage, accessibility score or validated user outcome. Program acceptance and pending closure are tracked separately in the [project status](../README.md#project-status).
