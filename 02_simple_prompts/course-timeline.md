# Course Timeline Editable Tags

Use the Canvas Design Agent skill. Transform the course timeline content below into a clear Canvas schedule page for students.

If you can create files or artifacts, create a downloadable `canvas-fragment.html` source file. If you cannot create a file, show the Canvas source in chat.

Do not show a rendered preview.

Copy and paste this entire file into a chat tool with the skill. The tag lines below are design instructions for the generated Canvas page. Use the tags to decide how each section should be displayed, but do not show the tag names or comment suggestions to students unless a tag is clearly meant to become a student-facing label.

Markdown comments in this file suggest other tags, colors, or elements to try. They are for workshop experimentation and should not appear in the final Canvas page.

**NOTE** All text below was generated for the sake of this workshop. I don't use generated text in my actual courses.

## Global Element Tags

Style Tag: S01 Clean Modern
<!-- Try also: S04 High Contrast for schedule readability, S06 Editorial for a typographic timeline, or S07 Studio Light for a creative light treatment. -->

Primary Color Tag: #2d6a4f
<!-- Try also: #1b5e20, #0055aa, #333333, or a course-specific department color with strong contrast. -->

Accent Color Tag: #40916c
<!-- This custom green intentionally overrides the standard Forest Greens palette. Try #52b788 or #0066cc for comparison. -->

Page Container Element: L05 Centered Container
<!-- Try also: L06 Full-Width Section with Background, L04 CSS Grid for a sidebar timeline, or plain flow. -->

Header Element: V05 Gradient Header
<!-- Try also: V02 Color-Coded Header, V06 Dark Theme Section, or an S06-style plain title block. -->

Navigation Element: N01 Anchor Link Table of Contents
<!-- Try also: no navigation, N02 button links to each unit, or a compact text list. -->

Schedule Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C01 Collapsible Section, C03 Info Cards, or C06 Ordered List Variants. -->

## How To Experiment

- Change one element ID at a time, then paste the whole file into a chat tool with the skill.
- Try changing the schedule element before changing the course data.
- Use comments as a menu of display options, not as required content.
- Keep due dates visible and include text labels in addition to color.

## Page Goals

Section Handling Tag: generation-instructions
<!-- These goals should guide the output. Do not render this section as student-facing course content. -->

- Make the semester sequence easy to scan
- Keep major deadlines near the top
- Group weeks by learning unit
- Make due dates visible without relying only on color
- Keep the schedule readable on narrow screens

## Accessibility

Section Handling Tag: generation-instructions
<!-- Accessibility instructions should guide the generated HTML. Do not show this section as course content. -->

- Use one clear h1 and logical heading order
- Use table headers with `scope="col"` if a table is generated
- Do not rely on color alone for due dates; include text labels
- Keep the schedule readable on narrow screens
- Use readable contrast throughout

## Header

Section Element: V05 Gradient Header
<!-- Try also: V02 Color-Coded Header, V01 Left-Border Accent Box, or plain title text with T01 unit headings. -->

Course: CART 398 -- Designing AI Agents: They Are Fun! and They Might Eat Us
Page Title: Fall 2026 -- Course Timeline
Meeting: Tuesdays, 1:00-3:45 PM -- EV 7.735 Studio Lab

## Key Dates

Section Element: V01 Left-Border Accent Box
<!-- Try also: D05 Schedule Grid, D01 Data Table, C03 Info Cards, or C06 Ordered List Variants. -->

Deadline Emphasis Element: T02 Highlighted Text
<!-- Try also: V04 Status Badge, bold date labels, V03 Alert / Callout Box, or plain text. -->

- Workshop 1 due: Sep 15, 2026
- Workshop 2 due: Sep 29, 2026
- Test Session 1: Oct 20, 2026
- Version 1 Presentation: Nov 3, 2026
- Test Session 2: Nov 17, 2026
- Final Presentation: Nov 24, 2026

## Semester Progress

Section Element: D07 Div-Based Progress Bar
<!-- Try also: V04 Status Badge, C03 Info Card, or plain text summary. -->

Progress Label: Week 1 of 12
Progress Value: 8%

## Unit 1: Foundations and Futures

Section Element: D05 Schedule Grid
<!-- Try also: C01 Collapsible Section, C03 Info Cards, C06 Ordered List Variants, or C09 Basic Unordered List. -->

Unit Heading Element: T01 Styled Heading
<!-- Try also: V01 Left-Border Accent Box or V04 Status Badge for week ranges. -->

Week 1 -- Sep 8: What is an agent? | Due: Set up documentation space; bring one AI interaction example
Week 2 -- Sep 15: AI history and near futures | Due: Workshop 1 due -- drawing on paper plus 200 words

## Unit 2: Contemporary Tools and Impossible Things

Section Element: D05 Schedule Grid
<!-- Try also: C01 Collapsible Section, C03 Info Cards, C06 Ordered List Variants, or compact text rows. -->

Week 3 -- Sep 22: Augmentation, conversation, and control | Due: Research log -- three contemporary projects to investigate
Week 4 -- Sep 29: Contemporary tools research | Due: Workshop 2 due -- 500-word blog post with 2-3 illustrated examples

## Unit 3: Phone Experiments and Agent-Based Coding

Section Element: D05 Schedule Grid
<!-- Try also: C01 Collapsible Section, C03 Info Cards, C06 Ordered List Variants, or compact text rows. -->

Week 5 -- Oct 6: Phones as sites for interaction | Due: Main project concept sketch and interaction statement
Week 6 -- Oct 13: Agent-assisted prototyping | Due: Prototype plan, feature list, and first technical test
Week 7 -- Oct 20: Testing version 0.5 | Due: Test Session 1 due -- working prototype test and notes
Week 8 -- Oct 27: Interaction, behavior, and trust | Due: Revised prototype and test plan for version 1
Week 9 -- Nov 3: Version 1 presentations | Due: Version 1 Presentation due

## Unit 4: Testing, Revision, and Presentation

Section Element: D05 Schedule Grid
<!-- Try also: C01 Collapsible Section, C03 Info Cards, C06 Ordered List Variants, or compact text rows. -->

Week 10 -- Nov 10: Revision from evidence | Due: Revision plan and documented change log
Week 11 -- Nov 17: Second testing session | Due: Test Session 2 due -- revised prototype test and documentation
Week 12 -- Nov 24: Final presentations | Due: Final Presentation due -- prototype, process archive, and reflection

## Grading Breakdown

Section Element: D07 Div-Based Progress Bar
<!-- Try also: D01 Data Table, C03 Info Card, C06 Ordered List Variants, or V04 percentage badges. -->

- Workshop 1: 10%
- Workshop 2: 10%
- Test Session 1: 15%
- Test Session 2: 15%
- Version 1 Presentation: 25%
- Final Presentation: 25%