# Important Links
## Workshop Canvas Page
You should have received an invitation to join this page today. Check your OCAD email
Canvas Page Link (https://canvascloud.ocadu.ca/courses/14047)
Create course pages to test out the code you generate.
## Copilot Chat
There are roughly 25 million different Copilots in the Microsoft suite, but we will be focussing on Copilot chat to generate our website code. If you have another chat tool you prefer Claude, ChatGPT, etc feel free to use that
- Sign into your OCAD account
- Go to https://m365.cloud.microsoft/chat
*Note* If it says you need a subscription, you need to sign into your OCAD account in the bottom left corner of the page
## Markdown
Markdown is an open data format created in 2004 as a simple text format that allows establishing hierarchy and simple styling through basic symbols. It has become an important tool when working with agent based AI as it lets you provide more complex instruction sets to an Agent working on a task.

We will be using the Markdown format to create the instructions for creating the canvas pages.

Markdown Syntax Guide https://www.markdownguide.org/cheat-sheet/



## Example Files
In case you missed it in the install step, these are all the files you will need.
Example files (link to come)

# Basic Workflow with Web-based Chat
## Set Copilot to use the correct Model
By default Copilot will want to leave the model choice set to *Auto*. Unfortunately, this makes the output type less predictable
In the Top Left Corner, press the + sign 
Select the newest GPT model that has **Quick Response**

In this workflow having the model overthink tends to lead to worse results and it trying to render the webpage instead of just generating the raw code.
docs/assets/modelPick.png

## Upload the Canvas Skill as Context
A **Skill** is a platform agnostic set of tools and instructions used by AI agents to tailor the work toward specific outcomes. Like most things with AI agents, it is just a text file with particular formatting. You can find SKILL.md in the example files for today

## Use the Markdown text as the Chat prompt
**This is a workaround for today's session**. Typically we would have the agents operate on our file directly in VSCode, but this method will be fine for today. These markdown files are designed to work either way and have the prompt info included at the top.

- Copy the text of the markdown file you want to use to generate the Canvas page
- Paste the entire text as a prompt into the chat
- Press enter to generate the code

## Copy the generated HTML
**Hopefully** it will generate a block that looks like this:
docs/assets/codeOutput.png
- Click the Clipboard icon to copy the code
- Create a new Blank File in VS Code File -> New Text File 
- Give it a name you can remember
- Paste it into the Blank file 
*It is important to keep local copies of your files for organization*

### Option 2 - it generates a download link for canvas-fragment.html
- Download the file
- Copy it into the folder with the other example files
- Select the file in VS Code. This should show you the raw html code
- Copy it

## Use the generated code in Canvas
Now you can use the generated html to create a page in Canvas
- Go to https://canvascloud.ocadu.ca/courses/14047/pages
- Create a new page by pressing + Page
- Toggle to the Html editor by pressing the </> icon
docs/assets/01_ToggleToCode.png
- When you toggle to the Html editor, there will be numbered lines and a grey bar on the left
docs/assets/02_CodeEditor.png
- Copy your generated html and paste it into the box
docs/assets/03_PasteHtml.png
- Toggle back to the rendered view by pressing the </> icon again
docs/assets/04_ToggleBack.png
You should now see the styled page!
- Save/Publish it
- You can also go back and edit the page directly as you typically would in the Canvas editor

# Problems 
## How Do I Know if it worked correctly?
In the example fileset each section has a folder called 'theAnswers' with pre-generated html. You can also view these pages from that section on this website

## It gave me the rendered Html, not the code
Tell the robot to fix it! In the chat tell it to 'provide the output as downloadable html'

## Something else is wrong with the code/output
Try and explain what is wrong in the chat and tell it to fix it