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

# Process and Case Files

## The standard process

PASTEL follows seven steps: define the performance problem, analyze the task, profile the learners, set objectives and assessment first, design practice and scaffolds, build, instrument and test early, and evaluate at four levels. Each step has a decision rule. For example, if the cause of a performance gap is tools, incentives or process, PASTEL says so and does not build training for it.

Read the full process at: https://leonildoalexandremorgado.github.io/PASTEL/process.html

## Case files

PASTEL publishes a case file for each portfolio module: the Invoice simulator, the Compliance simulator and the API onboarding simulator. Each covers the performance problem, task analysis, learner profile, objectives and assessment, design decisions, an evaluation plan at each Kirkpatrick level, and a design review. The scenarios are fictional, and the evaluation sections are plans, not results.

## Design review of version 1

Each case file lists what was wrong with version 1 of the module and what changed in version 2. Examples of issues found include labels that promised more than the module did, answer options that revealed the rule, answers in a predictable order, and scores that overstated performance. Version 1 of each module is archived for comparison.

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

## What happens when there is no answer

If PASTEL's documents do not contain a relevant passage, the tool says so instead of guessing, and suggests rephrasing the question or contacting PASTEL directly.

## Limits

The search matches the words in a question to the words in PASTEL's documents. It can miss a relevant passage when the question uses very different wording, so rephrasing may help.

## Privacy

After the page loads, the search runs entirely in the visitor's browser. Questions are not sent to any server.

<!-- TODO: Confirm these three statements are still true after the tool is built and tested. -->
