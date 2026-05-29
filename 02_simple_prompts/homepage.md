# Course Homepage Editable Tags

Use the Canvas Design Agent skill. Transform the course homepage content below into a clear Canvas course page for students.

If you can create files or artifacts, create a downloadable `canvas-fragment.html` source file. If you cannot create a file, show the Canvas source in chat.

Do not show a rendered preview.

Copy and paste this entire file into a chat tool with the skill. The tag lines below are design instructions for the generated Canvas page. Use the tags to decide how each section should be displayed, but do not show the tag names or comment suggestions to students unless a tag is clearly meant to become a student-facing label.

Markdown comments in this file suggest other tags, colors, or elements to try. They are for workshop experimentation and should not appear in the final Canvas page.

**NOTE** All text below was generated for the sake of this workshop. I don't use generated text in my actual courses.

## Global Element Tags

Style Tag: S03 Warm Minimal
<!-- Try also: S01 Clean Modern, S06 Editorial, S07 Studio Light, or S04 High Contrast. -->

Page Container Element: L05 Centered Container
<!-- Try also: L06 Full-Width Section with Background, L04 CSS Grid for sidebar/main layout, or plain flow. -->

Header Element: V02 Color-Coded Header
<!-- Try also: V05 Gradient Header, V06 Dark Theme Section, or no banner for an S06 editorial title block. -->

Course Image Element: E03 Linked Image
<!-- Try also: E01 GitHub-Hosted Image if you want a plain image with caption and no link. -->

Quick Links Element: N02 Button-Styled Links
<!-- Try also: N01 Anchor Link Table of Contents, C03 Info Cards, or simple text links. -->

Key Dates Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C03 Info Cards, V01 Left-Border Accent Boxes, or C06 Ordered List Variants. -->

## How To Experiment

- Change one element ID at a time, then paste the whole file into a chat tool with the skill.
- Keep this page student-facing and practical rather than turning it into a full syllabus.
- Use comments as a menu of ideas, not as required content.
- Keep this week's work and major deadlines visible near the top.

## Page Goals

Section Handling Tag: generation-instructions
<!-- These goals should guide the output. Do not render this section as student-facing course content. -->

- Make the page feel like a practical course homepage, not a syllabus wall
- Keep this week's work and the major deadlines easy to find near the top
- Make quick links obvious and easy to scan
- Show the course image immediately below the title/header
- Put longer project details after the high-priority information

## Accessibility

Section Handling Tag: generation-instructions
<!-- Accessibility instructions should guide the generated HTML. Do not show this section as course content. -->

- Use one clear h1 and logical heading order
- Use descriptive link text
- Keep this week's key information visible near the top
- Use readable contrast throughout
- Provide descriptive alt text for images

## Course Info

Section Element: C04 Definition List
<!-- Try also: L03 Flexbox Row, C03 Info Card, C05 Styled Definition List with Border Accent, or D03 Column-Styled Table. -->

Header Metadata Element: V04 Status Badge
<!-- Try also: T02 Highlighted Text, plain text metadata, or no badge. -->

Course Code: CART 398
Course Title: Designing AI Agents: They Are Fun! and They Might Eat Us
Course Subtitle: A studio seminar on theory, tools, and experimental interactions for small screens
Term: Fall 2026
Meeting Time: Tuesdays, 1:00-3:45 PM
Room: EV 7.735 Studio Lab
Instructor: Oh Cadyu

## Course Image

Section Element: E03 Linked Image
<!-- Try also: E01 GitHub-Hosted Image for a plain image, L07 Float Wrap for image plus welcome text, or no image for a text-only page. -->

Image URL: https://dn721207.ca.archive.org/0/items/AILS_AC96-0191-4/AC96-0191-4.jpg
Full-size link URL: https://dn721207.ca.archive.org/0/items/AILS_AC96-0191-4/AC96-0191-4.jpg
Image Placement: Immediately below the course title/header, before course info cards or welcome text.
Image Crop: Display as a slightly cropped landscape image near the top of the page.
Crop Style: width: 100%; max-width: 100%; height: 520px; object-fit: cover; object-position: center 42%; display: block;
Alt Text: Dr Ross and Rei Cheng wearing 3D glasses while maneuvering a reconstructed skull and tissue model for facial reconstructive surgery.
Caption: Virtual Environment for facial reconstructive surgery, 1996. Public Domain. Internet Archive item AILS_AC96-0191-4.

## Welcome Message

Section Element: T06 Styled Blockquote
<!-- Try also: V01 Left-Border Accent Box, C03 Info Card, or plain paragraphs. -->

Tone Tag: studio-friendly
<!-- Try also: concise-direct, formal-academic, lightly-playful, or speculative. -->

Welcome to Designing AI Agents: They Are Fun! and They Might Eat Us. In this course, we will treat AI agents as strange little collaborators: sometimes helpful, sometimes overconfident, and always worth questioning carefully before handing them the keys to anything important.

This is a studio seminar about making, reading, and testing. We will read early AI theory, look closely at contemporary tools and open-source projects, and use agent-based coding workflows to build experimental interactions for phones. Your phone already knows how to steal your time and data. This course asks a better question: what else could it become if you used AI tools to design interactions that are playful, critical, useful, or delightfully unnecessary?

No one is expected to arrive as an expert programmer or AI researcher. You are expected to document your process, ask sharper questions over time, test your work with other people, and stay alert to the difference between an impressive demo and a thoughtful interaction.

## This Week

Section Element: V03 Alert / Callout Box
<!-- Try also: V01 Left-Border Accent Box, C03 Info Card, C07 Checklist, or D03 Column-Styled Table. -->

Priority Tag: high
<!-- Try also: normal, urgent, informational, or workshop-prep. -->

Week: 1
Date: Sep 8, 2026
Focus: What is an agent, and why do designers keep giving software jobs it may not deserve?
Reading: Alan Turing, "Computing Machinery and Intelligence" (1950), excerpts
In Class: Course introduction, agent vocabulary, first small-group scenario exercise, and project notebook setup
Due: Set up your documentation space and bring one example of an AI interaction you find either promising, confusing, or suspicious

## Quick Links

Section Element: N02 Button-Styled Links
<!-- Try also: N01 Anchor Link Table of Contents, C03 Info Cards, C09 Basic Unordered List, or simple text links. -->

- AI history reading archive: [link]
- Open-source AI coding tools list: [link]
- Mobile prototyping references: [link]
- Documentation template: [link]
- Accessibility contrast checker: [link]
- Consent and user testing guide: [link]

## Learning Units

Section Element: C03 Info Card
<!-- Try also: C01 Collapsible Section, L03 Flexbox Row with cards, C02 Nested Collapsibles, or C06 Ordered List Variants. -->

Unit 1: Foundations and Futures (Weeks 1-2)
We begin with early AI dreams, cybernetic feedback, and a short speculative workshop about what could happen next year.

Unit 2: Contemporary Tools and Impossible Things (Weeks 3-4)
We study recent art, design, and technical projects that use AI tools in ways that would have seemed unlikely a year ago, with special attention to open-source and shareable work.

Unit 3: Phone Experiments and Agent-Based Coding (Weeks 5-9)
We use AI coding tools to design and prototype experimental interactions for phones, then test version 1 with classmates.

Unit 4: Testing, Revision, and Presentation (Weeks 10-12)
We revise from feedback, run a second test session, and prepare final presentations that explain both the interaction and the process behind it.

## Key Dates

Section Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C03 Info Cards, V01 Left-Border Accent Boxes, or C06 Ordered List Variants. -->

- Sep 15, 2026: Workshop 1 due -- AI History and Future drawing plus 200-word response
- Sep 29, 2026: Workshop 2 due -- Contemporary tools research blog post with images
- Oct 20, 2026: Test Session 1 -- First user test of main project prototype
- Nov 3, 2026: Version 1 Presentation -- Short presentation of main project direction and prototype
- Nov 17, 2026: Test Session 2 -- Revised prototype test with documentation
- Nov 24, 2026: Final Presentation -- Final project presentation and process archive

## Projects and Deliverables

Section Element: C03 Info Card
<!-- Try also: L03 Flexbox Row, D01 Data Table, V01 Left-Border Accent Box, or C01 Collapsible Section for details. -->

Project Badge Element: V04 Status Badge
<!-- Try also: T02 Highlighted Text, plain bold labels, or no badges. -->

Workshop 1: AI History and Future
Due: Sep 15, 2026
Weight: 10%
Output: Drawing on paper plus 200 words

Workshop 2: Contemporary Tools Research
Due: Sep 29, 2026
Weight: 10%
Output: Blog post of approximately 500 words with images showing 2-3 examples

Main Project: Experimental Phone Interactions
Due: Developed across Weeks 5-12
Weight: Test Session 1 15%, Version 1 Presentation 25%, Test Session 2 15%, Final Presentation 25%
Output: Interactive phone prototype, testing documentation, process archive, and final presentation

## Instructor Note

Section Element: V01 Left-Border Accent Box
<!-- Try also: T06 Styled Blockquote, V03 Alert / Callout Box, or plain paragraph. -->

This course rewards careful experiments more than flawless demos. If your prototype fails in a way that teaches you something specific, document it. If an AI tool gives you code that works but you cannot explain, slow down and investigate. The goal is not to prove that agents are magical. The goal is to learn how to design with them without surrendering your judgment at the door.