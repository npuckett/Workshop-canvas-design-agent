# Step by step guide for generating your first pages
this page should guide people step by step for working with the markdown files in 
01_getting_started folder. 

# Before starting
Ensure you have gone through the Setup and basic workflow sections of the website
We will be referencing the workflow outlined in basic workflow. If a step isn't clear, check there for more details

# Understanding the markdown files
In the example files look in the foler 01_getting_started
There are 3 files:
01_getting_started/00-no-style-class-page.md
01_getting_started/01-single-style-class-page.md
01_getting_started/02-section-style-class-page.md

The markdown files are where you
- Input course content
- Input basic page structure
- Tag different sections of the text to use visual styles from the Elements Catalog (link to Elements page)

01_getting_started/00-no-style-class-page.md
This is a base file with no specific html styling

01_getting_started/01-single-style-class-page.md
This file inputs 1 style input at the top : Style: S01 Clean Modern
This can be changed to one of the others listed below in the comment

01_getting_started/02-section-style-class-page.md
This inputs multiple styling tags to the same base file. It allows more specific control

# Your first generated Canvas page
*link to basic Workflow page*
- Open a new Copilot Chat session and make sure the correct model is selected
- Upload Skill.md to the chat
- Open 01_getting_started/01-single-style-class-page.md in VS Code
- Copy / paste the contents of the file into the chat and hit enter
- Download the generated code to a new file in VSCode
- Create a new canvas page and paste it in to see the results

## Next Steps
- Change the basic style in the markdown
- Repeat the same steps to see the results

# A Few more controls
- Open 01_getting_started/02-section-style-class-page.md
- Follow the same steps as before to generate, download, and copy/paste the html
- Consult the element catalog to see what other styles can be applied to the text
- See how different you can make it look without changing the content

# Important Note
Once you have the Skill.md file uploaded to the chat, you can ask the Agent questions about the skill and how to use it. Ask it for help!


Also include a menu item at the end called theAnswers
Copy the html from the corresponding 01_getting_started/theAnswers folder into the docs that shows the outcome of the prompts