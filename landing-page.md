# Make a landing page: a worked recipe

Status: manually authored synthetic example with tested browser behavior. Not a live model run or benchmark. Provider sources checked 2026-10-02. No guarantee that a specific model will produce the same result.

## 1. Write the brief before choosing a tool

Audience: parents of Class 10 students.
Offer: a fictional weekly after-school study group, Study Circle.
Goal: help visitors understand the format and find the next step.
Verified facts: none about a real business. All business content is explicitly fictional.
Unknowns: price, schedule, address, teachers and contact route. Do not fill these with guesses.
Constraints: mobile first; no accounts, dependencies, external scripts or private student data.

## 2. Draft the words with a text model, if useful

Suggested starting point: Google AI Studio where its current free tier fits. Check eligibility and current terms on the official pricing page. Free-tier content may improve Google products, so use this synthetic brief rather than private information.

Prompt:
> Write a short landing-page draft for this synthetic brief. Keep the fictional label visible. Do not invent prices, teachers, schedules, testimonials, guarantees or contact details. One heading, one short description, three format bullets and a next-step section. List missing facts separately.

Human quality gate: check that every claim follows the brief. A confident output is not proof.

## 3. Turn the checked draft into code

A text/code model can draft one self-contained HTML file. A local editor and browser are the tools for checking it. Do not add a second AI tool just to make the workflow look complex.

Prompt:
> Turn the checked copy below into accessible HTML/CSS. Use a viewport tag, semantic headings and native links. No external fonts, scripts, analytics or forms. Make the single CTA jump to the next-step section. Add a clear fictional-business label. Make it readable at 390px and 1280px. Do not add claims.

The included example was authored for this prototype. It illustrates an expected output, not actual output from a tested provider.

## 4. Verify before publication

- Render at phone and desktop widths. No horizontal overflow.
- Check title, one H1, viewport metadata and readable contrast.
- Keyboard-focus the CTA and activate it. Confirm it reaches the next-step section.
- Inspect every external resource and remove unneeded ones.
- Search source for keys, customer data, fabricated testimonials and claims.
- Confirm every real contact and payment destination separately before adding it.

This prototype includes functional tests for the guide's routing, privacy warnings, reset, download content and sample CTA. Visual inspection is recorded separately with screenshots. No sales uplift is claimed.

## 5. Publish only after review

Review the final words, code, repo name, description, license, topics and profile changes together. A launch does not authorize promotion messages or outside contributions.

## Limits

The chooser is rules based and does not interpret arbitrary tasks. All five task routes currently use a small text-model starting set, not a comprehensive specialist-tool comparison. The landing-page example is the first complete recipe; others are starter guides. Local models need capable hardware; sensitive work on a phone has no verified local model route here. Provider limits and availability must be rechecked before recommendation or execution.

## Official sources

- https://ai.google.dev/gemini-api/docs/pricing
- https://console.groq.com/docs/rate-limits
- https://docs.ollama.com/faq

GitHub Models is deliberately excluded: its official page states the service retired July 30, 2026.
https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models
