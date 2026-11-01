# Project Scope and Methodology

[Back to the project](../README.md)

This document summarizes the **proposed research method** in the 2024/1 application. It does not certify completed development, deployment or evaluation. The project was accepted under TÜBİTAK 2209-B; official closure approval remains pending as of 31 October 2026, according to the participant's update based on communication with the project lead.

## User needs and scope

The proposal focuses on everyday communication between people with special communication needs and their parents or caregivers. Familiar visual content, personalization and simple interaction are central to the proposed approach.

| Area | Proposed behavior | Boundary of available evidence |
| --- | --- | --- |
| Individual Mode | Select and arrange visual cards or familiar content to express needs and choices | Exact navigation, interaction details and implemented screens are unverified |
| Parent/Caregiver Mode | Upload and manage content personalized to the individual | No account, authorization or storage implementation is documented here |
| Speech output | Speak text associated with selected visual content through TTS | No selected engine, package or verified language coverage is available |
| Caregiver notifications | Notify the caregiver about interactions with content | Delivery conditions, latency and reliability are unmeasured |
| User experience | Refine both modes through usability/accessibility review and feedback | No completed study, participant count or outcome dataset is available here |

Flutter, Firebase, Google Cloud and TTS are named in the application. Digital PECS describes the intended visual communication approach. Specific cloud products, data schemas, package versions and deployment arrangements are not established by the available source.

## Proposed work plan

The application defines five work packages over **12 relative project months**. The 2024/1 call label is not a confirmed project start date; these intervals must not be converted into calendar dates without further records.

| Package | Planned months | Intended work | Assigned team members |
| --- | --- | --- | --- |
| WP1 | 1-4 | Establish the application foundation and integrate TTS | Eren Malkoç; Ferhat Baydır |
| WP2 | 5-7 | Functional tests, evaluation of user feedback and issue resolution | Devran Deniz Akgül |
| WP3 | 8-9 | Improve interfaces for Individual and Parent modes | Eren Malkoç |
| WP4 | 10-11 | Add notifications and personalized content upload | Ferhat Baydır; Devran Deniz Akgül |
| WP5 | 12 | End-user tests and final adjustments | Eren Malkoç; Ferhat Baydır; Devran Deniz Akgül |

This table records planned responsibilities, not verified completion of individual work packages. Separately, Devran Deniz Akgül reports collaborating with project lead Eren Malkoç on basic Flutter code modifications and incremental improvements. These contributions do not establish independent implementation of complete features or ownership of the application's codebase.

## Proposed evaluation and iteration

The proposal combines application development with functional tests and user-centered evaluation. It envisages a pilot with intended users and families, feedback on the two modes, and subsequent improvements. It also calls for usability and accessibility testing.

The supplied materials do not establish the pilot's execution, participant recruitment, consent arrangements, instruments, device matrix or analysis protocol. The [testing approach](testing-approach.md) translates selected objectives into illustrative review scenarios prepared for this portfolio, not historical test records.

## Risks identified in the proposal

| Risk area | Planned response described in the application |
| --- | --- |
| Compatibility problems and software defects | Regular testing and consultation of technical documentation |
| Feedback requiring substantial changes | Manage changes within the project plan and allow time for refinement |
| Server interruption or delayed responses | Backup and recovery arrangements |
| Protection of user data | Secure storage and encrypted backups |
| Unusable interfaces or difficulty finding help | UI/UX testing, feedback review and a proposed help panel |

These are planned mitigations. They do not demonstrate implemented security controls, successful recovery tests or verified accessibility compliance.

## Expected outputs

The proposal aims to produce a personalized communication application and inform further work on accessible mobile experiences. It also anticipates academic dissemination and broader educational or social use.

These remain **expected outputs in the application**. This portfolio makes no claim of a completed release, publication, presentation, patent, commercial outcome or measured user benefit. Quantitative proposal targets are not reported as achieved results.

## Source Basis

This documentation is based on the original TÜBİTAK 2209-B research proposal:

- Pages 2–5: Project objectives and methodology
- Page 6: Work packages and team responsibilities
- Page 7: Risk management
- Page 8: Expected outcomes and impact

The original research proposal is not publicly distributed in this repository.
