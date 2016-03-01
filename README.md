# hudsonvalleyhelp


[![Build Status](https://travis-ci.org/brianjking/hudsonvalleyhelp.svg?branch=master)](https://travis-ci.org/brianjking/hudsonvalleyhelp)




#README

* [DockDogs Scheduling Site Documentation](http://smartsheet.bigairdogs.org). Generated with [MKDocs](http://mkdocs.org)

### Pre-requesites 

* [Git](http://github.com)
* [MkDocs](http://mkdocs.org) or check the [MkDocs Github Repository](https://github.com/mkdocs/mkdocs/)
* Python (for using MkDocs)
* Pip (for using/installing MkDocs)
* Text editor such as Atom, Notepad++, or SublimeText.
* Terminal/Powershell access (iTerm2, Terminal.app, etc.)
* Git Desktop client _(if you prefer a GUI instead of a shell prompt). Suggested applications would be Github Desktop Client, Sourcetree, or Tower (Mac OS X Only)_.

### Checkout Documentation for Editing

* If you've never obtained the documentation before you'll want to clone the repository. The default branch is `master`, this is where edits should take place.
    * `$ git clone git@github.com:DockDogs/dockdogs-scheduling.git`
* If you've already cloned the repository navigate to where this is in your computer using Terminal or Powershell. Once in this directory you'll be able to execute the following:
    * `$ git fetch && git checkout master`

### How to Edit

* Edit files in `docs` folder using a text editor such as Atom, SublimeText, or Notepad++. 
* Files are written in `Markdown` syntax. Learn more about `Markdown` syntax at at [DaringFireball](https://daringfireball.net/projects/markdown/) or [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Github also has an official [Markdown reference guide](https://help.github.com/articles/markdown-basics/).

### Deploying Edits to Production Environment

* `$ mkdocs build`
* `$ git commit -am "commit message documenting what you've changed"`
* `$ git push`
* Once pushed to `master` branch all files from `site` folder will be deployed via [Deploybot](http://deploybot.com), Git, and black magic.
* Confirm updates are live & accessible via accessing [http://smartsheet.bigairdogs.org](http://bigairdogs.org). _This may take a few minutes to fully deploy, please be patient._


#### Deployment Status 

[![Deployment status from DeployBot](https://dockdogs.deploybot.com/badge/77558059970570/58385.svg)](http://deploybot.com)

### Getting a Specific Release & Viewing All Releases

* [View Releases](https://github.com/DockDogs/dockdogs-scheduling/releases)

### Open Issues

* [Github Issues](https://github.com/brianjking/dockdogs-scheduling/issues)
