# Project Brief Editable Tags

Use the Canvas Design Agent skill. Transform the project brief content below into a clear Canvas project page for students.

If you can create files or artifacts, create a downloadable `canvas-fragment.html` source file. If you cannot create a file, show the Canvas source in chat.

Do not show a rendered preview.

Copy and paste this entire file into a chat tool with the skill. The tag lines below are design instructions for the generated Canvas page. Use the tags to decide how each section should be displayed, but do not show the tag names or comment suggestions to students unless a tag is clearly meant to become a student-facing label.

Markdown comments in this file suggest other tags, colors, or elements to try. They are for workshop experimentation and should not appear in the final Canvas page.

**NOTE** All text below was generated for the sake of this workshop. I don't use generated text in my actual courses.

## Global Element Tags

Style Tag: S02 Bold Academic
<!-- Try also: S01 Clean Modern, S06 Editorial, S03 Warm Minimal, or S04 High Contrast. -->

Accent Color Tag: #e67e22
<!-- This overrides the default S02 crimson accent. Try #b71c1c, #2e7d32, #0055aa, or #ffc107. -->

Page Layout Element: L04 CSS Grid
<!-- Try also: L05 Centered Container, L03 Flexbox Row for card sections, or L06 Full-Width Section with Background. -->

Header Element: V05 Gradient Header
<!-- Try also: V02 Color-Coded Header, V06 Dark Theme Section, or plain title text with T01 section headings. -->

Milestones Element: D01 Data Table
<!-- Try also: D05 Schedule Grid, C03 Info Cards, C01 Collapsible Section, or C06 Ordered List Variants. -->

Submission Element: V06 Dark Theme Section
<!-- Try also: V03 Alert / Callout Box, V01 Left-Border Accent Box, or C03 Info Card. -->

## How To Experiment

- Change one element ID at a time, then paste the whole file into a chat tool with the skill.
- Try switching the project layout from L04 to L05 before changing individual sections.
- Use comments as design options, not as text students should see.
- Keep due dates, weights, and submission instructions visible.

## Page Goals

Section Handling Tag: generation-instructions
<!-- These goals should guide the output. Do not render this section as student-facing project content. -->

- Make the main project feel substantial but still navigable
- Put quick facts and milestone dates where students can find them quickly
- Separate project description, objectives, milestones, deliverables, testing norms, and submission instructions
- Make evaluation weights visible
- Keep technical requirements concrete and testable

## Accessibility

Section Handling Tag: generation-instructions
<!-- Accessibility instructions should guide the generated HTML. Do not show this section as course content. -->

- Use one clear h1 and logical heading order
- Keep due dates, weights, and submission instructions visible
- Use table headers with `scope="col"` for milestone or rubric tables
- Use descriptive button/link text
- Use readable contrast throughout

## Header

Section Element: V05 Gradient Header
<!-- Try also: V02 Color-Coded Header, V06 Dark Theme Section, or plain title text. -->

Course: CART 398 -- Designing AI Agents: They Are Fun! and They Might Eat Us
Project Title: Main Project: Experimental Phone Interactions
Timeline: Developed across Weeks 5-12
Weight: 80% of final grade across test sessions and presentations

## Quick Facts

Section Element: L04 CSS Grid
<!-- Try also: C04 Definition List, C03 Info Card, D03 Column-Styled Table, or L03 Flexbox Row. -->

Placement Tag: sidebar
<!-- Try also: top-summary, right-column, card-row, or inline-list. -->

- Format: Interactive phone prototype, testing documentation, process archive, and final presentation
- Project launch: Oct 6, 2026
- Test Session 1: Oct 20, 2026 -- 15%
- Version 1 Presentation: Nov 3, 2026 -- 25%
- Test Session 2: Nov 17, 2026 -- 15%
- Final Presentation: Nov 24, 2026 -- 25%

## Project Description

Section Element: T01 Styled Heading
<!-- Try also: C03 Info Card, V01 Left-Border Accent Box, T06 Styled Blockquote, or plain paragraphs. -->

Use AI coding tools to create an experimental new interaction for phones. The project can be useful, poetic, inconvenient in an interesting way, or built around a highly specific behavior.

The phone should not only display content; it should respond to touch, movement, time, location, sound, camera input, notifications, or another interaction pattern you can test with people.

Your prototype does not need to become a polished app store product. It does need to be testable, documented, and specific enough that someone can understand what kind of relationship it proposes between a person, a phone, and an AI-assisted design process.

## Learning Objectives

Section Element: C06 Ordered List Variants
<!-- Try also: C07 Checklist, C09 Basic Unordered List, C03 Info Card, or D01 Data Table. -->

1. Use AI coding tools to prototype interactive systems while keeping human judgment in the loop
2. Design and test experimental phone interactions that respond to real user behavior
3. Document process clearly enough that another person can understand what changed, what failed, and what you learned
4. Present speculative, technical, and ethical design decisions in concise critique language
5. Share sources, references, and tool choices clearly enough that classmates can learn from them

## Milestones

Section Element: D01 Data Table
<!-- Try also: D05 Schedule Grid, C03 Info Cards, C01 Collapsible Section, or C06 Ordered List Variants. -->

Milestone Badge Element: V04 Status Badge
<!-- Try also: T02 Highlighted Text, V01 Left-Border Accent Box, or plain bold labels. -->

M1 -- Concept Sketch and Interaction Statement (due Oct 6)
Main project concept sketch and interaction statement

M2 -- Prototype Plan and First Technical Test (due Oct 13)
Prototype plan, feature list, and first technical test

M3 -- Test Session 1 (due Oct 20, 15%)
Working prototype test and notes

M4 -- Version 1 Presentation (due Nov 3, 25%)
Short presentation of main project direction and prototype

M5 -- Test Session 2 (due Nov 17, 15%)
Revised prototype test and documentation

M6 -- Final Presentation (due Nov 24, 25%)
Prototype, process archive, and reflection

## Deliverables

Section Element: L03 Flexbox Row
<!-- Try also: C03 Info Cards, D01 Data Table, V01 Left-Border Accent Boxes, or C01 Collapsible Section. -->

Card Element: C03 Info Card
<!-- Try also: V04 REQUIRED badges, T02 Highlighted Text labels, or plain headings. -->

### Interactive Phone Prototype

- A testable phone-based interaction
- A response to touch, movement, time, location, sound, camera input, notifications, or another testable behavior
- Evidence that the prototype changed through testing

### Testing Documentation

- Test Session 1 notes
- Feedback synthesis and revision plan
- Test Session 2 notes
- A documented change log

### Process Archive and Presentation

- Prompts, code changes, and design decisions
- Sources, references, and tool choices
- Final presentation materials
- Concise reflection on how AI coding tools shaped the project

## Testing Norms

Section Element: V03 Alert / Callout Box
<!-- Try also: V01 Left-Border Accent Box, C03 Info Card, T06 Styled Blockquote, or plain paragraph. -->

Make prototypes testable early, even when they are awkward. Observe what users actually do, not only what you hoped they would do. Avoid collecting sensitive data from classmates unless the class has discussed and approved a safe testing plan.

## Evaluation Criteria

Section Element: D07 Div-Based Progress Bar
<!-- Try also: D01 Data Table, C03 Info Card, C06 Ordered List Variants, or V04 percentage badges. -->

- Test Session 1: 15%
- Version 1 Presentation: 25%
- Test Session 2: 15%
- Final Presentation: 25%

## Detailed Rubric

Section Element: C01 Collapsible Section
<!-- Try also: D01 Data Table, C03 Info Cards, C05 Styled Definition List with Border Accent, or plain headings. -->

### Prototype Specificity

Excellent: The interaction is specific, testable, and meaningfully connected to phone behavior.
Needs improvement: The interaction remains vague, mostly visual, or difficult for another person to test.

### AI-Assisted Design Process

Excellent: Prompts, code changes, tool choices, and human decisions are documented clearly.
Needs improvement: AI-generated material is used without explanation or review.

### Testing and Revision

Excellent: User testing produces specific evidence, and revisions respond to that evidence.
Needs improvement: Testing is minimal, undocumented, or not connected to design changes.

### Presentation and Reflection

Excellent: The final presentation explains the prototype, process archive, and ethical or technical decisions in concise critique language.
Needs improvement: The presentation is unclear, missing process evidence, or unable to explain major decisions.

## Technical Requirements and Resources

Section Element: C01 Collapsible Section
<!-- Try also: C03 Info Card, V01 Left-Border Accent Box, D01 Data Table, or plain visible section. -->

### Consent and Safety Note

Section Element: V01 Left-Border Accent Box
<!-- Try also: V03 Alert / Callout Box, T02 Highlighted Text, or plain paragraph. -->

Avoid collecting sensitive data from classmates unless the class has discussed and approved a safe testing plan.

### Minimum Requirements

- Must be testable by another person
- Must involve phone behavior beyond only displaying static content
- Must include documentation of prompts, code changes, design decisions, and tests
- Must include a process archive and final reflection

### Links

Section Element: N02 Button-Styled Links
<!-- Try also: simple text links, N01 Anchor Link Table of Contents, or C09 Basic Unordered List. -->

- Mobile Prototyping References: [link]
- Documentation Template: [link]
- Accessibility Contrast Checker: [link]
- Consent and User Testing Guide: [link]

## Submission

Section Element: V06 Dark Theme Section
<!-- Try also: V03 Alert / Callout Box, V01 Left-Border Accent Box, C03 Info Card, or plain visible paragraph. -->

Button Element: N02 Button-Styled Links
<!-- Try also: simple text links, Canvas assignment links X01, or no buttons if links are not available. -->

Submit each milestone through Canvas. The final submission must include the prototype, process archive, and reflection.

Buttons: Submit Test Session 1 Notes, Submit Version 1 Presentation, Submit Test Session 2 Documentation, Submit Final Presentation