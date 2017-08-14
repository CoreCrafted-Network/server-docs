# CoreCrafted Network Documentation


Welcome to the CoreCrafted Network Server Documentation source page.

Our documentation is made for providing static help and information about servers at our network , and probably teaches you everything you need to know for playing a particular server.

## Contributing
The documentation you see at our [official docs site](https://docs.corecrafted.net) is built from latest commit on master branch (If not the latest, it's just a few commits behind), and therefore should be accurate, complete and flawless.
However, nothing is perfect that there could be some minor mistakes we missed out and published anyway, or there are some missing pages of information you think they deserve to be in the docs, you can consider helping us to patch the page.

> Please keep in mind that every merge request is moderated , and will only be merged to master once we make sure everything is correct and accurate, so, if your modification/enhancement contains "facts" which we are unsure, please provide us with evidence so that your changes could be approved quicker

> Also, **NEVER** make lie and advertisements when modifying, or changing truths to something else maliciously (e.g. changing "Server Owner" to someone else)

### Branching
* **"master" branch**: The main production branch for English Official Version . If you want to clone this branch, use `https://github.com/CoreCrafted-Network/server-docs.git` in Git Bash
* **"master_zh-hk" branch**: *It is deleted an no longer exist* (If you want to contribute to the translation project, please get to @ItzJacky's Repository here at https://lab.corecrafted.net/ItzJacky/server-docs)



### Minor Mistakes / Improvements:
If you found out ***a few*** minor mistakes for example:
* spelling mistakes
* inappropriate wordings
* typing mistakes

and you are patient enough to wait for the docs author to update, you can consider making a post on our [forum](https://forum.corecrafted.net/c/feedback) or posting an issue post right at the [repository issue page](https://github.com/CoreCrafted-Network/server-docs/issues) about the issue.

Alternatively, if you prefer a more direct approach, you could fork the whole project repository to your account , make changes and commit them, then make a
merge request. There are links to tutorials and reference to editing and contributing in the next section


### Making new pages / Modiying a number of lines:
If you decide to do massive modifications for example,
* creating brand new page that hasn't on the docs before
* improve wordings on the whole documentation


**Useful Links**
* Tutorial on contributing: https://lab.corecrafted.net/ThisTNTSquid/server-docs/wikis/home *(This tutorial is intended to work on our server gitlab server, but the procedure is more like the same if you want to contribute on GitHub as well as these 2 are very similar thing)*
* Reference page for ReStructuredText: http://docutils.sourceforge.net/rst.html

## Translating
Some of you here might want to have a different language version of our official documentation. However, I'm really busy on developing plugins and servers, and thus wouldn't have any
extra time for me to sit down and translate the whole thing into another language. Therefore, if you wish to read our server documentation in another language, please consider forking
this project out and work on the translation with others that have extra time, then do a merge request on our project. Your hard work is always appreciated :smile:

## Building
If you like to have everything stored locally so that you don't need to visit our documentation site everytime you want to read it, you can consider cloning the source to your computer and building it locally.

Our documentation is built with [Sphinx](http://www.sphinx-doc.org/en/stable/), which is an awesome documentation generator that runs on Python

**Requirements**
* ~~Computer (or any devices that could run python)~~
* [Python](https://www.python.org/downloads/) (Python 3 recommended)
* [Sphinx](http://www.sphinx-doc.org/en/stable/tutorial.html)
* [Git](https://git-scm.com/)

**Procedure**
1. Download and install Git if your computer haven't installed it
1. Download and install Python if your computer doesn't have it
2. Setup Sphinx with executing `pip install Sphinx` in terminal (If you are unable to use this command on windows computers, please follow the quick fix [Here](https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation))
3. Now create a folder named whatever you like
4. Right click inside that folder then open "Git Bash Here"
5. Type in `https://github.com/CoreCrafted-Network/server-docs.git` in the terminal, and execute it
6. Rename the folder from "server-docs" to "source"
7. Now open powershell/cmd inside the workspace folder containing "source" folder (In case you don't know, it's Shift-right click -> "Open powershell Windows Here"/"Open Command Prompt Here")
8. Run `sphinx-build -a -b html source build`
9. The offline documentation is now sit in the "build" folder and you can now move the folder to somewhere else and rename it. The index page(The main page of documentation) is at `\index.html`. Open it with any web browser and the whole documentation should be working just fine as the one you see at our online site
