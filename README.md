# llm-playground
Generates hashtag recommendations for twitter posts

## Working with Google Collab Notebooks with Git Repo
1. Create or modify notebooks in a local IDE (e.g. vscode). Please note that Google Collab notebooks are read/run only (you cannot save your changes there), and all modifications need to be made locally. However, you can save a copy of the notebook with modification on Google collab, and copy & paste it back to local.
For more details, please refer to: https://saturncloud.io/blog/how-can-i-run-notebooks-of-a-github-project-in-google-colab/.
Other solutions:
- Historically, we could use collabcode package to open browser that's connected to vscode; however, seems that the solution is banned by Google. 
- Alternatively, we could potentially use ssh - we can explore that if the current approach creates any problem. 
2. To open and run an existing notebook in Google Collab: https://colab.research.google.com/, go to File -> Open notebook -> GitHub -> Check "Include private repos" -> search the link of this repo ("https://github.com/xtchen64/twitter-hashtag-generator") -> Select the repo and notebook from dropdown menu and open it.
3. [WIP] GPU setup: the plan is to use free quota for now, and upgrade to Collab Pro or Pro+ when needed.
