# Simple Syllabus Editable Tags

Use the Canvas Design Agent skill. Transform the syllabus content below into a clear Canvas syllabus page for students.

If you can create files or artifacts, create a downloadable `canvas-fragment.html` source file. If you cannot create a file, show the Canvas source in chat.

Do not show a rendered preview.

Copy and paste this entire file into a chat tool with the skill. The tag lines below are design instructions for the generated Canvas page. Use the tags to decide how each section should be displayed, but do not show the tag names or comment suggestions to students unless a tag is clearly meant to become a student-facing label.

Markdown comments in this file suggest other tags, colors, or elements to try. They are for workshop experimentation and should not appear in the final Canvas page.

**NOTE** All text below was generated for the sake of this workshop. I don't use generated text in my actual courses.

## Global Element Tags

Style Tag: S02 Bold Academic
<!-- Try also: S01 Clean Modern, S06 Editorial, S04 High Contrast, or S03 Warm Minimal. -->

Font Tag: F02 Traditional Serif
<!-- Try also: F01 System Sans-Serif for a cleaner page or F04 Wide Sans-Serif for accessibility priority. -->

Palette Tag: Plum and Gold
<!-- Primary #4a148c, accent #ffc107, link #7b1fa2. Try Forest Greens, Ocean Blues, or a department color set. -->

Page Container Element: L05 Centered Container
<!-- Try also: L04 CSS Grid for a contents/sidebar layout, L06 Full-Width Section with Background, or plain flow. -->

Schedule Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C01 Collapsible Section, C03 Info Cards, or C06 Ordered List Variants. -->

Policies Element: C03 Info Card
<!-- Try also: C01 Collapsible Section for longer policies, V01 Left-Border Accent Box, or C09 Basic Unordered List. -->

## How To Experiment

- Change one element ID at a time, then paste the whole file into a chat tool with the skill.
- Try changing the global style before changing individual syllabus sections.
- Use comments as a menu of ideas, not as required content.
- Keep important policies visible; use collapsibles only for longer supplemental details.

## Page Goals

Section Handling Tag: generation-instructions
<!-- These goals should guide the output. Do not render this section as student-facing syllabus content. -->

- Create a readable single-page syllabus overview
- Keep course information, schedule, projects, grading, and norms easy to scan
- Use tables or structured lists where they make long information easier to read
- Keep important policies visible

## Accessibility

Section Handling Tag: generation-instructions
<!-- Accessibility instructions should guide the generated HTML. Do not show this section as course content. -->

- Use one clear h1 and logical heading order
- Use readable color contrast
- Use descriptive link text if links are added
- Keep important policies visible; use collapsibles only for longer supplemental details
- Use table headers with `scope="col"` if tables are generated

## Course Info

Section Element: C04 Definition List
<!-- Try also: L03 Flexbox Row, C03 Info Card, C05 Styled Definition List with Border Accent, or D03 Column-Styled Table. -->

Course Code: CART 398
Course Title: Designing AI Agents: They Are Fun! and They Might Eat Us
Course Subtitle: A studio seminar on theory, tools, and experimental interactions for small screens
Term: Fall 2026
Meeting Time: Tuesdays, 1:00-3:45 PM
Room: EV 7.735 Studio Lab
Instructor: Oh Cadyu

## About This Course

Section Element: T06 Styled Blockquote
<!-- Try also: V01 Left-Border Accent Box, C03 Info Card, or plain paragraphs. -->

This is a studio seminar about making, reading, and testing. We will read early AI theory, look closely at contemporary tools and open-source projects, and use agent-based coding workflows to build experimental interactions for phones.

No one is expected to arrive as an expert programmer or AI researcher. You are expected to document your process, ask sharper questions over time, test your work with other people, and stay alert to the difference between an impressive demo and a thoughtful interaction.

## Learning Goals

Section Element: C07 Checklist
<!-- Try also: C06 Ordered List Variants, C09 Basic Unordered List, C03 Info Card, or D01 Data Table. -->

- Describe major ideas from early AI history and connect them to current design questions
- Research contemporary AI tools and creative projects with attention to openness, shareability, and public documentation
- Use AI coding tools to prototype interactive systems while keeping human judgment in the loop
- Design and test experimental phone interactions that respond to real user behavior
- Document process clearly enough that another person can understand what changed, what failed, and what you learned
- Present speculative, technical, and ethical design decisions in concise critique language

## Weekly Schedule

Section Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C01 Collapsible Section, C03 Info Cards, or C06 Ordered List Variants. -->

Schedule Density Tag: compact
<!-- Try also: roomy, very-compact, expanded, or unit-grouped. -->

### Week 1 -- Sep 8, 2026: What is an agent?

- In class: Course introduction, agent vocabulary, examples of helpful and unhelpful automation, documentation setup
- Reading / research: Alan Turing, "Computing Machinery and Intelligence" (1950), excerpts
- Due: Set up documentation space; bring one AI interaction example

### Week 2 -- Sep 15, 2026: AI history and near futures

- In class: Discussion of early AI claims, speculative futures exercise, paper drawing workshop
- Reading / research: Norbert Wiener, Cybernetics (1948), excerpts; Joseph Weizenbaum, "ELIZA" (1966), excerpts
- Due: Workshop 1 due -- drawing on paper plus 200 words

### Week 3 -- Sep 22, 2026: Augmentation, conversation, and control

- In class: Demo day: agent workflows in coding tools; small experiments with prompts, constraints, and review
- Reading / research: J. C. R. Licklider, "Man-Computer Symbiosis" (1960); Douglas Engelbart, "Augmenting Human Intellect" (1962), excerpts
- Due: Research log -- three contemporary projects to investigate

### Week 4 -- Sep 29, 2026: Contemporary tools research

- In class: Share research examples, discuss open-source practice, compare impossible-seeming projects from the last 12 months
- Reading / research: Student-selected examples from art, design, and technical projects; prioritize open-source repositories and public process notes
- Due: Workshop 2 due -- 500-word blog post with 2-3 illustrated examples

### Week 5 -- Oct 6, 2026: Phones as sites for interaction

- In class: Main project launch, phone affordance mapping, interaction sketches, scope check
- Reading / research: Lucy Suchman, Plans and Situated Actions (1987), excerpts; mobile interaction case studies
- Due: Main project concept sketch and interaction statement

### Week 6 -- Oct 13, 2026: Agent-assisted prototyping

- In class: Studio build session, AI coding tool workflow demo, critique of generated code and interface decisions
- Reading / research: Don Norman, The Design of Everyday Things (2013), feedback and affordance excerpts
- Due: Prototype plan, feature list, and first technical test

### Week 7 -- Oct 20, 2026: Testing version 0.5

- In class: Test Session 1, observation notes, feedback synthesis, revision planning
- Reading / research: Read two classmates' documentation pages before class
- Due: Test Session 1 due -- working prototype test and notes

### Week 8 -- Oct 27, 2026: Interaction, behavior, and trust

- In class: Studio development, microinteraction critique, privacy and consent discussion for phone-based systems
- Reading / research: Donna Haraway, "A Cyborg Manifesto" (1985), excerpts; contemporary AI ethics short reading
- Due: Revised prototype and test plan for version 1

### Week 9 -- Nov 3, 2026: Version 1 presentations

- In class: Version 1 presentation day, peer questions, next-step planning
- Reading / research: Review presentation checklist and critique prompts
- Due: Version 1 Presentation due

### Week 10 -- Nov 10, 2026: Revision from evidence

- In class: Studio build sprint, debugging clinic, documentation review, accessibility pass
- Reading / research: N. Katherine Hayles, How We Became Posthuman (1999), excerpts; accessibility testing resource
- Due: Revision plan and documented change log

### Week 11 -- Nov 17, 2026: Second testing session

- In class: Test Session 2, structured feedback, final presentation storyboarding
- Reading / research: Student-selected reference connected to final project topic
- Due: Test Session 2 due -- revised prototype test and documentation

### Week 12 -- Nov 24, 2026: Final presentations

- In class: Final presentations, process archive review, course reflection
- Reading / research: No new reading; finalize documentation and prepare presentation
- Due: Final Presentation due -- prototype, process archive, and reflection

## Projects and Grading

Section Element: D07 Div-Based Progress Bar
<!-- Try also: D01 Data Table, C03 Info Card, C06 Ordered List Variants, or V04 percentage badges. -->

- Workshop 1: 10%
- Workshop 2: 10%
- Test Session 1: 15%
- Test Session 2: 15%
- Version 1 Presentation: 25%
- Final Presentation: 25%

## Important Dates

Section Element: D05 Schedule Grid
<!-- Try also: D01 Data Table, C03 Info Cards, V01 Left-Border Accent Boxes, or C06 Ordered List Variants. -->

- Sep 15, 2026: Workshop 1 due -- AI History and Future drawing plus 200-word response
- Sep 29, 2026: Workshop 2 due -- Contemporary tools research blog post with images
- Oct 20, 2026: Test Session 1 -- First user test of main project prototype
- Nov 3, 2026: Version 1 Presentation -- Short presentation of main project direction and prototype
- Nov 17, 2026: Test Session 2 -- Revised prototype test with documentation
- Nov 24, 2026: Final Presentation -- Final project presentation and process archive

## Workshop Norms

Section Element: C03 Info Card
<!-- Try also: C09 Basic Unordered List, C07 Checklist, V01 Left-Border Accent Box, or C01 Collapsible Section. -->

- Document prompts, code changes, design decisions, and tests as part of the work, not as an afterthought
- Treat AI-generated output as material to inspect, revise, and take responsibility for
- Share sources, references, and tool choices clearly enough that classmates can learn from them
- Make prototypes testable early, even when they are awkward
- Give critique that names what is happening, what it makes possible, and what question should be tested next
- Avoid collecting sensitive data from classmates unless the class has discussed and approved a safe testing plan