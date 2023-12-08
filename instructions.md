# How to use VSCode Terminal Capture

## Getting Started 

Because our extension is not published we will need to go through a few extra steps to install terminal capture.

To get started you need to clone the repository to your local machine by running the following in the terminal:
```{toggle}
https://github.com/introcompsys/vscode-better-terminal-capture.git
```

After you have cloned this repository to your machine you need to cd into the cloned repo.

In here you will run:
```{toggle}
npm install
```
This will install all the required modules.

Then you will run this:
```{toggle}
npm install -g @vscode/vsce
```

After that is finished running you will then need to run:
```{toggle}
vsce package
```

Then you will install the extension from the VSIX file:

![Instructions to install](https://route360.dev/static/98955dbe38c82bb15bfc98325f8a41e7/1cfc2/vscode01.en.png)

After you click install the extension will be updated in your vscode extensions.

## How to use

Using the Terminal capture is very simple to grasp and get started with. To start all you need is a terminal window within VSCode open and for there to be input in the terminal. 

Once you have input in the terminal you can decide whether to keep adding more input or to activate the terminal capture tool to create a text file with all of the input and output from the terminal inside it. **Activating the capture command** requires the user to open the command palette for VSCode and to enter 'Terminal: Capture'.

Once the user has triggered the command, the contents of the terminal goes into the text file and the terminal is cleared. During this time the user can go into the text file and make necessary adjustments, changes, and notes to the termial content.

After the user is done making their desired changes, they will need to adjust the line their curser is on. The reason that they **must** make this adjustment is so that when they run the 'Terminal: Capture' command again it does not append the new content of the terminal to somewhere unwanted.

Once the user runs the command again the same steps should be followed as before and when they would like to go back to writing in the open terminal they should make sure they adjust their curser to a line below their existing notes and terminal output.
