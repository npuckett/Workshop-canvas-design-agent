# 1 Get a text editor
It is possible to use any text editor, but for this workshop it will be easiest if everyone is usign VS Code. A free, open source editor
https://code.visualstudio.com/download

- Download it
- Install it
- Open it

# 2 Download the example files
Download the zip file that contains the Skill file and the examples we will use:
https://npuckett.github.io/canvas-design-agent/docs/Workshop-canvas-design-agent.zip

- Unzip the folder to somewhere on your computer 

If you are familiar with Github you can also clone the repo from here: https://github.com/npuckett/Workshop-canvas-design-agent


# 3 Open the Example file in VS Code
- Open VS Code
- Go to File -> Open Folder
- Select the folder wherever you unzipped it
- Choose the File icon on the top left and you should now see the examples


If you are working with Web-based tools, Microsoft Copilot, ChatGpt, ect You are ready to go.

# Optional

## If you are using Github Copilot in VS Code

Use these steps if you have already cloned the repo locally.

- Open VS Code
- Go to File -> Open Folder
- Select the cloned `Workshop-canvas-design-agent` folder
- Make sure the GitHub Copilot extension is installed and you are signed in
- Open Copilot Chat in VS Code
- Ask Copilot to use the files in this repo to help generate Canvas-ready HTML
- The repo includes `.github/copilot-instructions.md`, so Copilot should automatically use the Canvas Design Agent instructions while you work in this folder

## Claude Code

Use these steps if you have already cloned the repo locally.

- Open Terminal
- Move into the cloned repo folder: `cd path/to/Workshop-canvas-design-agent`
- Start Claude Code from that folder
- Tell Claude to use `SKILL.md` as the Canvas Design Agent instruction file
- Open or reference one of the prompt files in `02_simple_prompts` or `03_homepage_schedule`
- Ask Claude to create Canvas-ready HTML from the prompt
- If Claude can create files, ask it to save the output as `canvas-fragment.html`; otherwise, ask it to show the Canvas HTML source in chat