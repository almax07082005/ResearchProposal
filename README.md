# Research Proposal

This project is for writing research proposal during EAP 4-th module.

I added .gitignore file, which (as you can see) ignores all files from ```output``` folder except ```main.pdf```. I did so to prevent problems with compilation. Also, to check for correctness of updated files.

## Additional settings for latex extension in vscode
![image](https://github.com/almax07082005/ResearchProposal/assets/64369296/746de3b0-a2e9-4762-a854-db014088e13c)

### So, please: do not change names of ```main.tex``` and ```main.pdf``` files.

If you do so, ```.gitignore``` will ignore this file when pushing, which will lead to rejecting a pull request.

### Hence, to work with this project you should do the following:

1) Execute the following command to clone the repo: ```git clone https://github.com/almax07082005/ResearchProposal.git```.
2) Two ways:
    - either compile ```main.tex``` file with your texlive compiler (which you may or may not install);
    - or move these files to any other external compiler (e.g. Overleaf), work there, then copy changed files to the local repo (do not forget about ```main.pdf```).
3) Make a pull request to commit changes:
    - create a new temporary branch and make all necessary commits there;
    - create a pull request;
    - when pull request will be approved, it will be automatically merged with main branch and your temporary branch will be removed.
4) Wait until approvance.

## Suggestions

I strongly recommend you use Github Desktop because it contains all necessary features to work with branches and pull requests, otherwise you will need to learn branch creation, stashes, and etc.
