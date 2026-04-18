## README.md

*To see the preview of this [README.md](http://README.md) file and to make it easier for you to read, on your keyboard, type: cmd+shift+v (mac users) or ctrl+shift+v (windows users)*

# What is Command Line?

| Prerequisite | Basic familiarity with your computer operating system, the basic software you will use to build a website, and file system |
| --- | --- |
| Learning Outcomes |   • Know what the command line is, what you can do with it
  • Know the basic keyboard shortcuts (e.g. tab, how to access previous commands)
  • Know basic commands (e.g. cd, ls, mkdir, touch, code .)
  • Command options/flags |
| Reference | | Reference | [MDN Command line crash course](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Environment_setup/Command_line#Basic_built-in_terminal_commands) ||

## Command Line

- Terminal commands are useful ways to navigate between your folders aka directories, quickly and easily.
- The terminal is a text interface for executing text-based programs. Check out my reference above to get a deeper dive!
- Your first assignment is to memorize and get really comfortable in using your Command Line. You will find that you would be using this regularly.

## Open your Terminal and try these out:

- We use ‘ls’ (ls stands for list) to list the contents of the current directory. Try it out yourself. Go to your Terminal and type ‘ls’ then click enter.
- We use ‘cd’ (cd stands for change directory) to change directories or file folders. Try it out yourself. On your terminal, type ‘cd Desktop’ to go to your Desktop. Then type ‘ls’ to see what you have on your Desktop.
- To move back up to the previous directory or file folder (or even to get out of said folder), we use ‘cd ..’ (note: terminals are case and space sensitive! So in this exercise, make sure it is all lowercase and there is a space between cd and the two periods that followed after it).
- To check our working directory, we use ‘pwd’. When we print the working directory (pwd stands for print working directory), it shows us the path. Try it out yourself! It should show along the lines (but not identical): /Users/john.smith/Desktop
- To create a new folder inside the Desktop directory, we navigate into the Desktop directory first (if you’re not there yet), by typing ‘cd Desktop’, then we use ‘mkdir sandbox’ (mkdir stands for: make directory) to create a new folder called: sandbox. We will be using this directory for your sandbox from now on.
- Now that we have a new folder, let’s go into that sandbox directory by typing ‘cd sandbox’. Then, we use ‘touch README.md’ to create a new file called: README.md.
- Now, type ‘ls’ again and you will see what is inside that new directory you have created. It should list: README.md
- Lastly, we’re going to open that new sandbox folder into your chosen code editor. I am using Visual Studio Code, but the command should be the same for you even if you aren’t using VS.
    - Firstly, make sure that you are in the sandbox directory by typing on your terminal again ‘pwd’. It should say along the lines: /Users/john.smith/Desktop/sandbox
    - Once you are in the sandbox directory (folder), you are going to type ‘code .’ (there is a space between code and the period). This will bring up your sandbox folder into your code editor. Again, we will be using this sandbox folder for your exercises from now on. 😉