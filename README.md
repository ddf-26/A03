# Tutorial and Definitions
### Tutorial for GIT, Github, and WebStorm
1. Download WebStorm [here](https://www.jetbrains.com/student/).
2. Download GIT [here](https://git-scm.com/downloads).
3. Set up a Github account [here](https://github.com/join).
4. Connect Github with WebStorm by going into system preferences->Version Control->Git and enter the path to git.
5. Set up Github repository: click the '+' sign and choose "Create New Repository."
6. Enter a reposittory name and write a short description in their respective boxes.
7. Select the "Add a README file" and click "Create Repository."
8. 


### Part 2 Glossary
* **Branch**: a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
* **Clone**: a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
* **Commit**: an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
* **Fetch**: When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.
* **GIT**: an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
* **Github**: provides a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.
* **Merge**: takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
* **Merge Conflict**: a difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
* **Push**: to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
* **Pull**: refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
* **Remote**: this is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
* **Repository**: contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

### References
1. GitHub (2022) GitHub Guides Tutorial. Retrieved from https://docs.github.com/en/get-started/quickstart/hello-world
2. GitHub (2022) GitHub Glossary. Retrieved from https://docs.github.com/en/get-started/quickstart/github-glossary
