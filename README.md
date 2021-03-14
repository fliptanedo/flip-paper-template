# flip-paper-template
A LaTeX paper template that I use for papers and notes.

**Note**: This version is now no longer updated. Please refer to the [new repository](https://github.com/fliptanedo/flip-paper-template-2021).

By Flip Tanedo (flip.tanedo@ucr.edu)

Uses Jacques Distler's `utcaps.bst` and AAS TeX's `aas_macros.sty`, included in this repository. Place figures in the `\figures` directory. 

## How to use this

For those, like me, are less competent with `git` and GitHub than we really aught to be.

1. Go to repo's [page](https://github.com/fliptanedo/flip-paper-template) on GitHub.

2. Click on the green `Code` button just to the top-right of the list of files. 

3. Copy the URL that pops up. It should be: `https://github.com/fliptanedo/flip-paper-template.git`

4. Locally (on your system) go to the parent directory of where you'd like to start a new LaTeX project and open a Terminal (command prompt) window there. Assuming you have `git` set up, you can simply type in `git clone https://github.com/fliptanedo/flip-paper-template.git` and press enter.

5. This should create a new folder `flip-paper-template`. Go ahead and rename it right away. `mv flip-paper-template new-folder-name`.

6. Go ahead and start your new project.

7. If you'd like to put this new project on GitHub, just start a new GitHub repository through the web interface. Do not initialize with a `README.md` file. Follow the steps to push and existing repository. This should be a `git remote add origin` command followed by a `git push -u origin master` command. **Except**: there's one problem. Your copy of `flip-paper-tempalte` (now renamed) is *already* connected to the paper template GitHub repository. So if you follow the GitHub directions you'll get an error: `fatal: remote origin already exists.`. Instead, the first line should be `git remote set-url origin [https://github.com/....git]`. 

That should do it.
