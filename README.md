# PASTEL Studio

**Pragmatic Applied Systems & Training Engineering Lab**

A small instructional design studio focused on technical workflow training for SaaS, fintech and enterprise learning and development teams. This repository is the studio's portfolio site.

Live site: https://leonildoalexandremorgado.github.io/PASTEL/

## What the site shows

- **A standard process.** Seven steps from defining the performance problem to evaluating results, each tied to named frameworks and a decision rule (`process.html`).
- **Three portfolio simulators.** Each one has a case file and a design review that compares version 1 with version 2.
- **Ask PASTEL.** A tree of topics that mirrors the process, case files and services, plus a search box for specific terms. It shows exact passages from the studio's own documents and names the source. It does not generate answers, and it says so when nothing relevant is found.

## Services offered

- **Technical Workflow Onboarding:** task analysis, role-based onboarding pathways, performance rubrics.
- **Custom Web-Native eLearning Engineering:** interactive modules in HTML5 and JavaScript, or in H5P when a client's platform calls for it, with xAPI statement design and SCORM and LRS integration scoped per project.
- **AI-Driven Training Scaffolding:** prompt design for practice and feedback, formative assessment drafts, and restructuring documentation so it can be searched.
- **Policy and Procedure Assistants:** source-cited search over an organization's own documents, designed to run inside the client's environment.

## Repository contents

| File | Purpose |
|---|---|
| `index.html` | The studio page, including Ask PASTEL |
| `process.html` | The standard process and the three case files |
| `invoice-simulator.html`, `api-simulator.html`, `compliance-simulator.html` | Version 2 of each portfolio simulator |
| `invoice-simulator-v1.html`, `api-simulator-v1.html`, `compliance-simulator-v1.html` | Archived version 1, kept for comparison with the design reviews |
| `pastel_knowledge_base.md` | The documents Ask PASTEL searches |

## Status and limits

- **The simulators use fictional data.** They are portfolio demonstrations and not client projects. The API, keys, secret and signing scheme in the API simulator are fictional, and the signing scheme is simplified, so do not copy it into production. The compliance policy is fictional and has not been reviewed by an AML professional.
- **No measured results.** The case files contain evaluation plans, not results. None of the simulators has been tested with real learners.
- **xAPI statements stay in the browser.** Each simulator builds xAPI-structured statements and offers them as a JSON download. Nothing is sent to a learning record store.
- **Accessibility is designed in but not audited.** The pages aim at WCAG 2.1 AA guidelines, and feedback is announced to screen readers. A full accessibility audit has not been run.
- **H5P, SCORM and LRS integration are offered capabilities.** None of the portfolio modules is built in H5P or delivered as a SCORM package.
- **Ask PASTEL uses keyword matching.** It can miss a relevant passage when a question is worded very differently from the documents. It only returns text from `pastel_knowledge_base.md`.

## Updating Ask PASTEL

Edit `pastel_knowledge_base.md` and commit. The page loads the file when it opens, so there is nothing to rebuild. GitHub Pages may take a few minutes to serve the change. Keep the structure the page expects:

- A `#` heading for each document.
- A `##` heading for each section.
- A blank line between passages.
- Lists written as lines that start with `- `.

Write each passage so it makes sense on its own, naming PASTEL explicitly instead of using pronouns.

The topic tree is built from the knowledge base headings, so a new `#` document or `##` section appears in the tree automatically. Documents whose names start with `Case File: ` appear under Case files. The process and case-file passages were generated from `process.html`, so when you change that page, update the matching passages in the knowledge base too.

## Running locally

Opening `index.html` directly from disk will not load the knowledge base, and the API simulator's signature check needs a secure context. Serve the folder instead:

```
python3 -m http.server
```

Then open http://localhost:8000.

## Technology

Plain HTML, CSS and JavaScript with no build step, hosted on GitHub Pages. The site loads fonts from Google Fonts, and the contact form posts to Formspree. Ask PASTEL's search runs entirely in the browser, and questions typed into it are not sent anywhere.
