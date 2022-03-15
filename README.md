# CWL Novice tutorial template

CWL Template for the [CWL Novice tutorial](https://carpentries-incubator.github.io/cwl-novice-tutorial/index.html).

This template contains some of the scripts used in the tutorial. 
It also contains instructions for installing the bio-cwl-tools library.

Before using these scripts you will need to install [VSCode](https://code.visualstudio.com/), [docker](https://www.docker.com/), and [cwltool](https://github.com/common-workflow-language/cwltool).
Instructions for installing these are available via their websites, and on the course [Setup page](https://carpentries-incubator.github.io/cwl-novice-tutorial/setup.html).

 
#### Usage

This template should be used to create a new git repository. The steps to do this are:

1. Click the `Use this template` button, and create a new repository on github as you would usually
   * Before the next step you can, if you wish, copy this repository to a different git service (such as [gitlab](https://gitlab.com/)).  
2. Clone the repository locally, using `git clone --recursive [template address]` (the `[template address]` can be got from the `Code` button at the top of the page)
   * Using the `--recursive` flag will automatically load the bio-cwl-tools library for you, using `git submodules`.


