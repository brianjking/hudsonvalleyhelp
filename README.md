# Hudson Valley DockDogs Website Help


[![Build Status](https://travis-ci.org/brianjking/hudsonvalleyhelp.svg?branch=master)](https://travis-ci.org/brianjking/hudsonvalleyhelp)


* [Hudson Valley DockDogs Website Help](http://help.hudsonvalleydockdogs.com). Generated with [MKDocs](http://mkdocs.org)

### Pre-requesites 

* [Git](http://github.com)
* [MkDocs](http://mkdocs.org) or check the [MkDocs Github Repository](https://github.com/mkdocs/mkdocs/)
* Python (for using MkDocs)
* Pip (for using/installing `MkDocs` and other dependencies)
* Text editor such as Atom, Notepad++, or SublimeText.
* Terminal/Powershell access (iTerm2, Terminal.app, etc.)
* Git Desktop client _(if you prefer a GUI instead of a shell prompt). Suggested applications would be Github Desktop Client, Sourcetree, or Tower (Mac OS X Only)_.

### Checkout Documentation for Editing

* If you've never obtained the documentation before you'll want to clone the repository. The default branch is `master`, this is where edits should take place.
    * $ ` git clone git@github.com:brianjking/hudsonvalleyhelp.git`
* If you've already cloned the repository navigate to where this is in your computer using Terminal or Powershell. Once in this directory you'll be able to execute the following:
    * $ ` git fetch && git checkout master`

### How to Edit Documentation

* Edit files in `docs` folder using a text editor such as Atom, SublimeText, or Notepad++. 
* Files are written in `Markdown` syntax. Learn more about `Markdown` syntax at at [DaringFireball](https://daringfireball.net/projects/markdown/) or [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Github also has an official [Markdown reference guide](https://help.github.com/articles/markdown-basics/).

### Deploying Edits to Production Environment

* `$ git commit -am "commit message documenting what you've changed"`
* `$ git push`
* Once pushed to `master` branch `Travis-CI` will run tests to confirm all builds correctly.
* On successful build `Travis-CI` will push to the `gh-pages` branch and deploy the documentation.
* Confirm updates are live & accessible via accessing [http://help.hudsonvalleydockdogs.com](http://help.hudsonvalleydockdogs.com). _This may take a few minutes to fully test & deploy, please be patient._


#### Build & Deployment Status 

[![Build Status](https://travis-ci.org/brianjking/hudsonvalleyhelp.svg?branch=master)](https://travis-ci.org/brianjking/hudsonvalleyhelp)


