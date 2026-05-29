# What is the point of this? Why did you build it? What is wrong with you?
This tool came out of work I have been doing over the past few years to try and mitigate the issues we are all facing:
- Classes are larger
- Post-pandemic students have a different expectation toward Canvas and asynchronous engagement. What do we do when attendance isn't required etc

I decided to try and work with this via UX in Canvas for 2 main reasons
- I'm a design person who makes interactive things, so this is kind of the only way I know how to solve problems
- I found it difficult to teach students about the importance of UX and interaction principles via interfaces that were very non-visual

# How does this work ?
## Canvas is just (limited) html
Every page you have created in Canvas was done by generating html. The basic page editor lets you create things visually, but it is just generating html in the background. 
- Open any of your Canvas pages
- Press the </> button..

This also means that you can author pages directly as html. This has always been possible.

## What's the Catch
There were 2 things that made this a bit tricky
- Canvas limits what html elements can / can't be used. It removes standard coding practices of stylesheets, etc for security reasons. (Not that Canvas has any security concerns)

- The elements that can/can't be used were not documented anywhwere


## What is *it* ?
Over the past year, I managed to package up the workflows I have been using into a now generic format called a SKILL (hyperlink to the SKILL.md on the github repo). These are fancy text files that allow coding agents to work in specific ways. They are instructions that tell them to operate in a particular way. In this case it tells the agent to generate the code using these specific rules.

## A Few Examples
- Atelier 1
- Physical Computing
- DF Thesis


# What are we doing today?
- Getting Set up with some of the tools
- Learning the basic design process of working with textFiles -> html -> Canvas pages
- Experimenting with the tools based on a ficticious course I generated

# Caveats
- This tool is very much still in development. 
- Working with web-based chat is not ideal. Part 2 in the Fall will focus on developing locally with more advanced agent tools

# Feedback
- If you have any comments/questions just email me


