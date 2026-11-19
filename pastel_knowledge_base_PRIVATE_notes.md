<!--
KNOWLEDGE BASE CONVENTIONS (for the indexing script)
- "# " heading  = a document (becomes the "source" shown to the reader)
- "## " heading = a section (shown as the location inside the source)
- Each paragraph or bullet group under a section = one searchable passage.
- Every passage names PASTEL explicitly, so it still makes sense when shown on its own.
- HTML comments like this one are notes to the author and are stripped before indexing.
- Everything below was drafted ONLY from the text of the current PASTEL website.
  Gaps are marked "TODO" in comments. Nothing has been invented to fill them.
-->

# About PASTEL

## Who PASTEL is

PASTEL stands for Pragmatic Applied Systems & Training Engineering Lab. PASTEL is a boutique instructional engineering studio focused on technical workflow design, cognitive scaffolding, and applied systems training.

PASTEL designs training for complex systems. PASTEL turns dense software environments into intuitive training designed around measurable performance.

## What PASTEL focuses on

PASTEL's focus is technical workflow design. Its pedagogy is cognitive scaffolding and task-based learning. Its delivery is web-native HTML5 and xAPI, with H5P available on request. The intended outcome is applied operational fluency.

## Who PASTEL serves

PASTEL provides end-to-end applied systems training and instructional engineering for SaaS teams, fintech startups, and enterprise learning and development (L&D) organizations.

## Availability

PASTEL is available for select contract work. PASTEL is currently starting with smaller-scale projects in order to build its client base.

<!-- TODO: Add any limits on capacity or start dates if you want them stated. -->

# Philosophy and Methodology

## Why PASTEL's approach differs

Traditional corporate training relies on passive slide decks and bloated authoring tools. PASTEL builds interactive cognitive architectures rooted in psycholinguistic task analysis and rigorous learning engineering.

## Cognitive scaffolding

PASTEL applies applied linguistic frameworks to remove extraneous cognitive load. This turns complex fintech protocols and multi-step SaaS workflows into intuitive, digestible mental models.

## Task-based execution

PASTEL moves beyond rote memorization. Learners interact directly with sandboxed technical environments, building real skill through authentic, problem-centered simulation.

## Universal Design for Learning and accessibility

PASTEL designs to WCAG 2.1 AA guidelines from the start, with support for different learning modes and responsive layouts across common screen sizes. PASTEL's custom builds are mobile-first.

## Evaluating training with the Kirkpatrick model

PASTEL uses the Kirkpatrick Four Levels of Training Evaluation to plan how a training program will be judged. The four levels are Reaction, Learning, Behavior, and Results.

At Level 1 (Reaction), PASTEL looks at how learners respond to the training, including how engaging and relevant they find it. At Level 2 (Learning), PASTEL checks whether learners gain the intended knowledge and skills, using immediate corrective feedback inside simulations, formative assessments, and competency statements logged through xAPI to a learning record store.

At Level 3 (Behavior), PASTEL looks at whether people apply what they learned in their real work, supported by role-based onboarding pathways, job aids, and performance rubrics. At Level 4 (Results), PASTEL connects training to business outcomes such as shorter ramp time and faster time-to-proficiency. Levels 3 and 4 depend on data from the client's own workplace.

PASTEL plans for the higher levels at the start of a project, by working backward from the business result the client wants, to the on-the-job behaviors that produce it, and then to the learning activities that build those behaviors.

<!-- TODO: Confirm this reflects how you actually work. Level 1 (reaction surveys) and the "work backward" planning step are not on the current site, so edit or delete anything that overstates your practice. -->

## Why applied linguistics

PASTEL is built on the premise that mastering a complex fintech platform or enterprise software ecosystem is closely analogous to acquiring a specialized language. Traditional instructional designers rely on static templates. PASTEL approaches technical training through psycholinguistics, cognitive load theory, and communicative task design.

PASTEL replaces passive documentation with active task-based interaction, feedback loops, and input simplification. The goal is to reduce friction and design learning experiences aimed at measurable operational fluency.

# Portfolio Modules

## MOD_01: Enterprise Invoice Workflow Simulator

PASTEL's Enterprise Invoice Workflow Simulator demonstrates replacing a 60-page ERP manual with a sandboxed reconciliation environment. It uses progressive disclosure and immediate corrective feedback to reduce extraneous cognitive load during multi-currency audit training.

The simulator belongs to the FinOps portfolio area. It is built with HTML5, JavaScript and xAPI-structured statements generated in the browser. Version 2 has six invoice-matching cases, shuffled each time. Learners check quantities first, then price variance against a tolerance of 0.50% or less.

Launch it at: https://leonildoalexandremorgado.github.io/PASTEL/invoice-simulator.html

## MOD_02: Crypto API Onboarding Micro-Learning

PASTEL's Crypto API Onboarding Micro-Learning module teaches webhook onboarding for a fictional payments API in three steps with fading support. It keeps authentication, event types and signature verification in separate steps to limit split attention.

The module belongs to the developer relations (DevRel) area and is built with HTML5, JavaScript and a simulated API sandbox. Support fades across three steps: a worked example for authentication, a completion problem for event types, and an independent task in which the learner verifies three incoming webhooks by computing real HMAC signatures in the browser and checking timestamps.

Launch it at: https://leonildoalexandremorgado.github.io/PASTEL/api-simulator.html

## MOD_03: KYB / AML Compliance Decision Simulator

PASTEL's KYB / AML Compliance Decision Simulator asks learners to choose a proportionate response to fictional business customer files: approve, request information, approve with monitoring, or escalate to a compliance officer. Two of its four cases present a second decision when new information arrives. It is not timed, and its policy is fictional.

The module belongs to the risk and AML area. It is custom-built with HTML5, JavaScript and xAPI-structured statements generated in the browser. It is not an H5P or SCORM package.

Launch it at: https://leonildoalexandremorgado.github.io/PASTEL/compliance-simulator.html

## About the portfolio overall

PASTEL's portfolio modules are simulations built with fictional data to demonstrate how PASTEL designs training to reduce extraneous cognitive load in high-stakes software environments.

## Data used in the portfolio modules

All three portfolio modules use fictional data. They are portfolio demonstrations of PASTEL's design approach and technical instrumentation, and they are not client projects. They show how learning data can be captured (Kirkpatrick Level 2), and they do not report measured results from real learners or organizations. The xAPI statements are generated in the browser and are not sent to a learning record store. Each module has a case file with a design review comparing version 1 and version 2.

<!-- TODO: Consider adding a short "fictional data" note on the live module pages too, so visitors see it before they ask. -->

# Standard Process

## Overview

Every PASTEL project follows the same seven steps. The Invoice case file below shows the steps applied to a portfolio module, including what a design review found wrong with version 1 and what changed in version 2.

Read this first. The scenario is fictional and the module uses fictional data. The case file reconstructs the design reasoning behind a portfolio piece, and no real learners or organizations are involved. The evaluation section is a plan, not a set of results.

Read the full process at: https://leonildoalexandremorgado.github.io/PASTEL/process.html

## Step 1: Define the performance problem

What should people do differently, and is training the right fix? Compare desired and actual performance, then screen the causes: missing knowledge or skill, poor tools, weak incentives, or process barriers.

Frameworks: performance gap analysis (Mager & Pipe), Human Performance Technology, Action Mapping (Cathy Moore).

Decision rule: if the cause is tools, incentives or process, say so. Don’t build training for it.

## Step 2: Analyze the task

Break the job into the decisions people make and the cues they use to make them. Note where experts and novices differ, and where novices are likely to go wrong.

Frameworks: Cognitive Task Analysis.

Decision rule: design practice around decisions, not topics.

## Step 3: Profile the learners

Record prior knowledge, work context and available time. Support that helps beginners can slow experts down, so scaffolding has to fade as skill grows.

Frameworks: expertise reversal effect (Kalyuga), cognitive load theory.

Decision rule: state the assumed starting point, then test it with real learners.

## Step 4: Set objectives and assessment first

Write observable objectives, then the assessment items that would prove them, before drafting any content.

Frameworks: instructional alignment, criterion-referenced assessment (Dick & Carey tradition).

Decision rule: if an activity doesn’t serve an objective, cut it.

## Step 5: Design practice and scaffolds

Reduce wasted mental effort, for example by placing related information together. Use worked examples early and fade them. Keep the practice close to the real task.

Frameworks: cognitive load theory (Sweller), split-attention and worked-example effects, Merrill’s First Principles, Gagné’s events of instruction.

Decision rule: put the information next to where it’s used.

## Step 6: Build, instrument and test early

Prototype quickly and run formative evaluation: expert review, one-to-one tryouts, then a small group. Capture event data so later evaluation has something to use.

Frameworks: rapid prototyping, formative evaluation, xAPI.

Decision rule: test with a few real users before polishing anything.

## Step 7: Evaluate at four levels

Plan Reaction, Learning, Behavior and Results measures at the start. Levels 3 and 4 need workplace data, so the metric, the baseline and the data owner must be agreed before launch.

Frameworks: Kirkpatrick Four Levels, with confirmative follow-up months later.

Decision rule: name the metric, the baseline and the owner before launch.

# Case File: Enterprise Invoice 3-Way Match Simulator

## About this case file

Read this first. The scenario is fictional and the module uses fictional data. The case file reconstructs the design reasoning behind a portfolio piece, and no real learners or organizations are involved. The evaluation section is a plan, not a set of results.

Launch the Invoice simulator (version 2): https://leonildoalexandremorgado.github.io/PASTEL/invoice-simulator.html. Archived version 1: https://leonildoalexandremorgado.github.io/PASTEL/invoice-simulator-v1.html. This case file: https://leonildoalexandremorgado.github.io/PASTEL/process.html#invoice

## Performance problem (fictional scenario)

An accounts payable team relies on a 60-page ERP manual. New specialists are expected to apply three rules when matching an invoice to its purchase order and goods receipt, but the rules are buried in the manual. Desired performance: apply the rules the same way every time. Non-training causes to check first: whether the ERP displays variance clearly, and who owns the tolerance policy.

## Task analysis

Invoice simulator, task analysis:
- Step: 1. Compare quantities across PO, receipt and invoice
- Decision and cue: Does invoice quantity exceed receipt quantity?
- Predicted novice error: Trusting a matching invoice total and missing a receiving shortfall

Invoice simulator, task analysis:
- Step: 2. Work out the price or FX variance
- Decision and cue: Is the absolute variance within 0.50%?
- Predicted novice error: Misjudging values at or near the limit

Invoice simulator, task analysis:
- Step: 3. Choose a disposition
- Decision and cue: Approve, hold for Procurement, or reject
- Predicted novice error: Over-escalating small variances, or approving above tolerance

The errors are predicted from the task, not observed in real learners.

## Learner profile (assumed)

A new accounts payable specialist who knows basic accounting terms, works in an ERP system, and has not yet learned this company’s tolerance policy. These assumptions would be checked in one-to-one tryouts before any wider release.

## Objectives and assessment

Invoice simulator, objectives and assessment:
- Objective: O1. Spot a receiving shortfall even when the totals match
- Assessed by (v2 cases): INV-2026-892, INV-2026-921

Invoice simulator, objectives and assessment:
- Objective: O2. Judge a variance against the 0.50% tolerance, including values at the limit
- Assessed by (v2 cases): INV-2026-884, 889, 901, 907

Invoice simulator, objectives and assessment:
- Objective: O3. Choose the correct disposition and apply the checks in order
- Assessed by (v2 cases): All six cases

## Design decisions in v1

Invoice simulator, design decisions in v1:
- Decision: PO, receipt and invoice shown side by side
- Principle: Split-attention effect
- How it shows up: One ledger table, so learners don’t flip between documents

Invoice simulator, design decisions in v1:
- Decision: Rules shown beside the data
- Principle: Information at the point of use
- How it shows up: An embedded job aid instead of a manual lookup

Invoice simulator, design decisions in v1:
- Decision: One decision per case
- Principle: Chunking
- How it shows up: A queue of short cases

Invoice simulator, design decisions in v1:
- Decision: Specific feedback for each wrong choice
- Principle: Corrective feedback
- How it shows up: Each wrong option explains what was missed

## Build and instrument

HTML and JavaScript in a single page, with no server. v1 showed an activity log labeled as an xAPI stream. v2 builds real xAPI-structured statements in the browser and offers them as a JSON download.

## Evaluation plan (Kirkpatrick)

Invoice simulator, evaluation plan (kirkpatrick):
- Level: 1 Reaction
- Question: Was it clear and relevant?
- Instrument: Short rating survey after completion
- Data owner: Learner
- Suggested timing: Immediately

Invoice simulator, evaluation plan (kirkpatrick):
- Level: 2 Learning
- Question: Can they apply the rules to unseen cases?
- Instrument: First-attempt score on a fresh case set, compared before and after
- Data owner: L&D
- Suggested timing: Immediately and after two weeks

Invoice simulator, evaluation plan (kirkpatrick):
- Level: 3 Behavior
- Question: Do they apply the rules at work?
- Instrument: Supervisor checklist on a sample of real dispositions: quantities checked first, tolerance applied correctly
- Data owner: AP lead
- Suggested timing: 30 to 60 days

Invoice simulator, evaluation plan (kirkpatrick):
- Level: 4 Results
- Question: Did outcomes move?
- Instrument: Exception error rate, rework and escalation volume, late-payment incidents, each against a baseline set before launch
- Data owner: Finance operations
- Suggested timing: Quarterly

Because the scenario is fictional there are no baselines, so no results are shown.

## Design review: v1 to v2

Invoice simulator, design review: v1 to v2:
- Issue found in v1: Answer options described the rule that made them correct
- Why it matters: Learners could match wording instead of applying the rules
- Change in v2: Options describe the action only

Invoice simulator, design review: v1 to v2:
- Issue found in v1: Correct answers always came in the same order
- Why it matters: A pattern could be guessed
- Change in v2: Case order and option order are shuffled

Invoice simulator, design review: v1 to v2:
- Issue found in v1: Three cases, one per rule
- Why it matters: No value at the limit, and no case where two problems compete
- Change in v2: Six cases, including exactly 0.50%, just above it, and a combined shortfall and overage with a stated check order

Invoice simulator, design review: v1 to v2:
- Issue found in v1: “100% Audit Accuracy” logged at the end regardless of wrong attempts
- Why it matters: The record overstated performance
- Change in v2: First-attempt accuracy is scored and reported

Invoice simulator, design review: v1 to v2:
- Issue found in v1: Log labeled “LRS CONNECTED” with nothing sent anywhere
- Why it matters: The label claimed something that wasn’t true
- Change in v2: Labeled as generated locally, with xAPI-structured statements and a JSON download

Invoice simulator, design review: v1 to v2:
- Issue found in v1: Feedback not announced to screen readers
- Why it matters: Learners using assistive technology missed the result
- Change in v2: Feedback is announced through a live region, and smooth scrolling respects reduced-motion settings

Still not done: v2 has not been tested with real learners, and a full accessibility audit has not been run.

# Case File: KYB / AML Compliance Decision Simulator

## About this case file

The policy, the entities and the escalation rules in this module are fictional. Real AML procedures vary by institution and jurisdiction, and this is not compliance training for real use.

Launch the Compliance simulator (version 2): https://leonildoalexandremorgado.github.io/PASTEL/compliance-simulator.html. Archived version 1: https://leonildoalexandremorgado.github.io/PASTEL/compliance-simulator-v1.html. This case file: https://leonildoalexandremorgado.github.io/PASTEL/process.html#compliance

## Performance problem (fictional scenario)

New onboarding analysts at a fictional fintech are expected to match their response to the level of risk in a business customer’s file. Desired performance: approve clean files, ask for documents when an item can be explained, and escalate serious indicators without acting alone. Non-training causes to check first: whether the escalation policy is written down and findable, and whether the case system shows ownership and activity data together.

## Task analysis

Compliance simulator, task analysis:
- Step: 1. Check ownership transparency
- Decision and cue: Can the beneficial owner be identified?
- Predicted novice error: Accepting a registry entry without asking who actually controls the entity

Compliance simulator, task analysis:
- Step: 2. Compare activity with the expected profile
- Decision and cue: Does the volume and pattern match?
- Predicted novice error: Treating any mismatch as wrongdoing, or ignoring it

Compliance simulator, task analysis:
- Step: 3. Screen for PEP exposure
- Decision and cue: Is there a match, and is it explained?
- Predicted novice error: Reacting to any PEP link the same way, or missing opacity combined with a PEP link

Compliance simulator, task analysis:
- Step: 4. Choose a proportionate response
- Decision and cue: Approve, request information, monitor, or escalate
- Predicted novice error: Over-escalating clean files, or acting alone on serious indicators

Compliance simulator, task analysis:
- Step: 5. Decide again when new information arrives
- Decision and cue: Do the documents resolve the open items?
- Predicted novice error: Anchoring on the first impression

The errors are predicted from the task, not observed in real learners.

## Learner profile (assumed)

A new onboarding analyst who knows the basic terms (beneficial owner, PEP) but has not yet learned this firm’s escalation policy. These assumptions would be checked in one-to-one tryouts.

## Objectives and assessment

Compliance simulator, objectives and assessment:
- Objective: O1. Tell a clean profile from one with open items
- Assessed by (v2 cases): CASE-101, and the first decision in CASE-112

Compliance simulator, objectives and assessment:
- Objective: O2. Choose a proportionate first response
- Assessed by (v2 cases): The first decision in every case

Compliance simulator, objectives and assessment:
- Objective: O3. Decide again when new information arrives
- Assessed by (v2 cases): The second decision in CASE-104 and CASE-112

Compliance simulator, objectives and assessment:
- Objective: O4. Recognize patterns that call for immediate escalation without contacting the client
- Assessed by (v2 cases): CASE-109

## Design decisions in v1

Compliance simulator, design decisions in v1:
- Decision: Dossier beside the decision panel
- Principle: Split-attention effect
- How it shows up: Facts and choices on one screen

Compliance simulator, design decisions in v1:
- Decision: Three tiers of response
- Principle: Proportionality as the core concept
- How it shows up: Approve, enhanced due diligence, block

Compliance simulator, design decisions in v1:
- Decision: Short case queue
- Principle: Chunking
- How it shows up: One entity at a time

Compliance simulator, design decisions in v1:
- Decision: Feedback that names the consequence
- Principle: Corrective feedback
- How it shows up: Each wrong choice explains the risk

## Build and instrument

HTML and JavaScript in a single page. v1 showed an activity log labeled as an xAPI stream. v2 builds xAPI-structured statements for each decision in the browser, with a JSON download. Nothing is sent to a learning record store.

## Evaluation plan (Kirkpatrick)

Compliance simulator, evaluation plan (kirkpatrick):
- Level: 1 Reaction
- Question: Was it clear and relevant?
- Instrument: Short rating survey
- Data owner: Learner
- Suggested timing: Immediately

Compliance simulator, evaluation plan (kirkpatrick):
- Level: 2 Learning
- Question: Can they choose a proportionate response on unseen cases?
- Instrument: First-attempt score across decisions on a fresh case set
- Data owner: L&D
- Suggested timing: Immediately and after two weeks

Compliance simulator, evaluation plan (kirkpatrick):
- Level: 3 Behavior
- Question: Do real decisions follow the policy?
- Instrument: Quality review of a sample of real onboarding decisions: proportionality and timeliness of escalation
- Data owner: Compliance QA
- Suggested timing: 30 to 60 days

Compliance simulator, evaluation plan (kirkpatrick):
- Level: 4 Results
- Question: Did outcomes move?
- Instrument: Unnecessary escalations, time to decision, quality-review findings, each against a pre-launch baseline
- Data owner: Compliance operations
- Suggested timing: Quarterly

Because the scenario is fictional there are no baselines, so no results are shown.

## Design review: v1 to v2

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Each dossier carried a risk label such as “HIGH RISK” or “CRITICAL”
- Why it matters: Learners could read the label instead of weighing the evidence
- Change in v2: Labels removed; the learner reasons from the facts

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Described as branching, but it was three independent single choices
- Why it matters: The description promised more than the design delivered
- Change in v2: Described accurately; two cases now present a second decision when new information arrives

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Described as decided “under time constraints,” but nothing was timed
- Why it matters: The claim was untrue
- Change in v2: Claim removed. Speed pressure is a later fluency goal, and would add load for novices

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Option text stated the criteria (“illicit activity markers detected”)
- Why it matters: Learners could match wording instead of judging
- Change in v2: Option text describes the action only

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Answers always came in the same order
- Why it matters: A pattern could be guessed
- Change in v2: Case order and option order are shuffled

Compliance simulator, design review: v1 to v2:
- Issue found in v1: “Block account and file SAR” offered as an analyst action
- Why it matters: Analysts normally escalate, and the officer decides on reports and freezes
- Change in v2: Replaced with escalation to the compliance officer. A practitioner should review this rule

Compliance simulator, design review: v1 to v2:
- Issue found in v1: “100% Analytical Accuracy” and “LRS CONNECTED” labels
- Why it matters: The record and the label overstated what happened
- Change in v2: First-attempt scoring and statements labeled as generated locally

Compliance simulator, design review: v1 to v2:
- Issue found in v1: Feedback not announced to screen readers
- Why it matters: Learners using assistive technology missed the result
- Change in v2: Live region, and smooth scrolling respects reduced-motion settings

Still not done: v2 has not been tested with real learners, a full accessibility audit has not been run, and the policy has not been reviewed by an AML professional.

# Case File: Crypto Payment Webhook Onboarding

## About this case file

The API, keys, secret and signing scheme in this module are fictional. The signing scheme is a simplified teaching version, so real providers differ and nothing here should be copied into production.

Launch the API onboarding simulator (version 2): https://leonildoalexandremorgado.github.io/PASTEL/api-simulator.html. Archived version 1: https://leonildoalexandremorgado.github.io/PASTEL/api-simulator-v1.html. This case file: https://leonildoalexandremorgado.github.io/PASTEL/process.html#api

## Performance problem (fictional scenario)

A fictional payments company finds that some integrators ship webhook handlers that skip signature checks or accept old requests. Desired performance: integrators authenticate correctly, handle the right event types, and verify both the signature and the timestamp before crediting funds. Non-training causes to check first: whether the SDK offers a verification helper, whether the documentation buries the signing rules, and whether the sandbox ever sends a bad signature. If the SDK did the check by default, training would matter much less.

## Task analysis

API onboarding simulator, task analysis:
- Step: 1. Authenticate the request
- Decision and cue: Which header and scheme does the reference specify?
- Predicted novice error: Using a familiar scheme instead of reading the reference

API onboarding simulator, task analysis:
- Step: 2. Pick the event type
- Decision and cue: What state is the transfer in?
- Predicted novice error: Confusing pending and completed events

API onboarding simulator, task analysis:
- Step: 3. Verify the signature
- Decision and cue: Does the expected signature match the received one?
- Predicted novice error: Skipping the check, or comparing the wrong body

API onboarding simulator, task analysis:
- Step: 4. Check the timestamp
- Decision and cue: Is the request within 5 minutes of its timestamp?
- Predicted novice error: Treating a valid signature as proof the request is fresh

The errors are predicted from the task, not observed in real learners.

## Learner profile (assumed)

A developer who is comfortable with JSON and HTTP basics but new to this API and to webhook signature verification. These assumptions would be checked in one-to-one tryouts.

## Objectives and assessment

API onboarding simulator, objectives and assessment:
- Objective: O1. Build the authentication header the reference specifies
- Assessed by (v2): Step 1

API onboarding simulator, objectives and assessment:
- Objective: O2. Choose the event type that matches a scenario
- Assessed by (v2): Step 2

API onboarding simulator, objectives and assessment:
- Objective: O3. Detect a body altered after signing
- Assessed by (v2): Step 3, request with the changed amount

API onboarding simulator, objectives and assessment:
- Objective: O4. Reject a validly signed but stale request
- Assessed by (v2): Step 3, request that arrives 15 minutes late

API onboarding simulator, objectives and assessment:
- Objective: O5. Accept a valid, fresh request without over-rejecting
- Assessed by (v2): Step 3, the valid request

## Design decisions in v1

API onboarding simulator, design decisions in v1:
- Decision: Authentication taught before payloads
- Principle: Segmenting to limit split attention
- How it shows up: One concept per step

API onboarding simulator, design decisions in v1:
- Decision: Live request preview beside the task
- Principle: Immediate representation of consequences
- How it shows up: The inspector updates as the learner chooses

API onboarding simulator, design decisions in v1:
- Decision: Three steps with shrinking support
- Principle: Fading scaffolds
- How it shows up: Labeled worked example, faded prompt, then independent

API onboarding simulator, design decisions in v1:
- Decision: HTTP-style feedback
- Principle: Authentic context
- How it shows up: Status codes in the inspector

## Build and instrument

HTML and JavaScript in one page. v2 computes real HMAC-SHA256 signatures in the browser using the built-in Web Crypto API, and builds xAPI-structured statements for each decision, with a JSON download. Nothing is sent to a learning record store.

## Evaluation plan (Kirkpatrick)

API onboarding simulator, evaluation plan (kirkpatrick):
- Level: 1 Reaction
- Question: Was it clear and relevant?
- Instrument: Short rating survey
- Data owner: Learner
- Suggested timing: Immediately

API onboarding simulator, evaluation plan (kirkpatrick):
- Level: 2 Learning
- Question: Can they verify a webhook on unseen cases?
- Instrument: First-attempt score across decisions, with new request variations
- Data owner: Developer relations
- Suggested timing: Immediately and after two weeks

API onboarding simulator, evaluation plan (kirkpatrick):
- Level: 3 Behavior
- Question: Do their handlers verify signatures and timestamps?
- Instrument: Review of integrators’ sandbox traffic and code samples against a checklist
- Data owner: Integration support
- Suggested timing: 30 to 60 days

API onboarding simulator, evaluation plan (kirkpatrick):
- Level: 4 Results
- Question: Did outcomes move?
- Instrument: Rejected-forgery tests passed, integration support tickets, time to first successful integration, each against a pre-launch baseline
- Data owner: Developer relations
- Suggested timing: Quarterly

Because the scenario is fictional there are no baselines, so no results are shown.

## Design review: v1 to v2

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Step 1 was labeled a worked example, but no example was shown
- Why it matters: The label promised support that wasn’t there
- Change in v2: A solved example for another endpoint, then a matching problem

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Step 2 told learners the exact string to type
- Why it matters: It was a copy task, not a decision
- Change in v2: A scenario and an event-type reference; the learner finds the right value, with feedback for each common mistake

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Step 3 never verified a signature; it asked one policy question with an obvious wrong answer
- Why it matters: The skill named in the title was never practiced
- Change in v2: The learner computes the expected signature and judges three requests: valid, altered and stale

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: “Score: 100%” and “Mastery Achieved” were logged regardless of attempts
- Why it matters: The record overstated performance
- Change in v2: First-attempt accuracy across five decisions

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Feedback said API tokens “require” Bearer as an OAuth rule
- Why it matters: It stated a general rule that doesn’t apply to this API
- Change in v2: The rule is framed as this fictional API’s reference

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Answers were always in the same order
- Why it matters: A pattern could be guessed
- Change in v2: Options and the three requests are shuffled

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Log labeled “RECORDING STATEMENTS” with nothing recorded
- Why it matters: The label implied storage
- Change in v2: Labeled as generated locally, with a JSON download

API onboarding simulator, design review: v1 to v2:
- Issue found in v1: Feedback not announced to screen readers
- Why it matters: Learners using assistive technology missed the result
- Change in v2: Live region, and smooth scrolling respects reduced-motion settings

Still not done: v2 has not been tested with real learners, a full accessibility audit has not been run, and the signing scheme is simplified.

# Services

## Technical Workflow Onboarding

PASTEL's Technical Workflow Onboarding service provides diagnostic task analysis and structured curriculum architecture. It is designed to help reduce ramp time for complex B2B software products and internal tools.

It includes:
- Cognitive Task Analysis (CTA) and skill mapping
- Role-based onboarding pathways and job aids
- Performance rubrics and competency benchmarks

## Custom Web-Native eLearning Engineering

PASTEL's Custom Web-Native eLearning Engineering service builds lightweight, accessible interactive modules in HTML5 and JavaScript, or in H5P when a client's platform calls for it, without the lock-in of bloated proprietary authoring tools.

It includes:
- Interactive software UI simulations and sandboxes
- Mobile-first builds designed to WCAG 2.1 AA guidelines
- xAPI statement design, with SCORM and LRS integration scoped per project

## AI-Driven Training Scaffolding

PASTEL's AI-Driven Training Scaffolding service creates pedagogically grounded prompt architectures and adaptive practice environments designed to turn static documentation into active coaching loops.

It includes:
- LLM role-play and diagnostic feedback prompts
- Automated formative assessment generation
- Knowledge base restructuring for RAG (retrieval-augmented generation) readiness

## Policy and Procedure Assistants

PASTEL's Policy and Procedure Assistants service builds a search assistant that lets employees look up their organization's own policies and procedures. Every answer is the exact passage from the organization's documents, shown with the document and section named. The assistant does not write or generate answers, so it cannot invent text.

If the organization's documents contain nothing relevant, the assistant says so and points the employee to the right person instead of guessing.

The assistant is designed to run inside the client's own environment, so sensitive company documents are not processed by third-party servers.

It includes:
- Restructuring policy and procedure documents so they can be searched accurately
- A test set of real questions to check accuracy, including questions the assistant should decline to answer
- Guidance for staff on how to use the assistant, and when to confirm with the policy owner

A search can occasionally miss a relevant passage. For that reason the assistant always shows its sources, and staff are encouraged to confirm high-stakes decisions with the policy owner.

<!-- TODO: Confirm the scope above. It is drawn from our design discussion, not from the current site. Add it to the contact form's inquiry types if you keep it. -->

# Background and Credentials

## Education and experience

PASTEL is backed by an M.S.Ed. in Applied Linguistics / TESOL and over a decade of curriculum architecture experience.

<!-- Kept general on purpose. Add specifics later if you choose to. -->

## Academic foundation

PASTEL's academic foundation is an M.S.Ed. in Applied Linguistics / TESOL, covering psycholinguistics, cognitive scaffolding, and curriculum design.

## Core methodology

PASTEL's core methodology is Task-Based Learning and Cognitive Load Theory. PASTEL also works with ADDIE, Agile SAM, Universal Design for Learning (UDL), and the Kirkpatrick Four Levels of Training Evaluation.

## Authoring and web stack

PASTEL's authoring and web stack is HTML5, CSS3, JavaScript and xAPI, with Git and GitHub Pages, WCAG accessibility practices, and xAPI statements.

PASTEL offers H5P as a capability for clients whose platforms call for it. None of the portfolio modules is built in H5P. They are custom HTML5 and JavaScript.

# Working with PASTEL

## How to start

To start an engagement, send the details through the contact form on the PASTEL website. The form asks for full name, work email, the type of inquiry, and project context and objectives.

## Engagement types

PASTEL accepts inquiries in these categories:
- Technical Workflow Onboarding Architecture
- Custom Web-Native eLearning (HTML5 or H5P)
- AI-Driven Training Scaffolding and Prompt Design
- Policy and Procedure Assistants

## Response time

PASTEL's stated response time for inquiries is under 24 business hours.

## Project size, pricing and terms

PASTEL is starting with smaller-scale projects in order to build its client base. PASTEL has not published pricing or standard project terms. To discuss scope for a project, use the contact form on the PASTEL website.

<!-- TODO: Update as pricing, project length and scoping process get decided. Location, time zone and NDA handling are still unstated, so the tool will correctly say "not found" for those. -->

# About This Search Tool

## What it is

This tool answers questions about PASTEL by showing the exact passages from PASTEL's own documents, with the document and section named. It does not write or generate answers.

## Two ways to explore

Ask PASTEL offers a tree of topics that mirrors PASTEL's process, case files and services, and a search box for specific terms. The tree reads from the same knowledge base, so every result is an exact passage with its source named.

## Two ways to explore

Ask PASTEL offers a tree of topics that mirrors PASTEL's process, case files and services, and a search box for specific terms. The tree reads from the same knowledge base, so every result is an exact passage with its source named.

## What happens when there is no answer

If PASTEL's documents do not contain a relevant passage, the tool says so instead of guessing, and suggests rephrasing the question or contacting PASTEL directly.

## Limits

The search matches the words in a question to the words in PASTEL's documents. It can miss a relevant passage when the question uses very different wording, so rephrasing may help.

## Privacy

After the page loads, the search runs entirely in the visitor's browser. Questions are not sent to any server.

<!-- TODO: Confirm these three statements are still true after the tool is built and tested. -->
