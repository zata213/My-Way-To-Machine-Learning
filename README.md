---
#### :four_leaf_clover: I am studying *Data science*. In this repository, I am going to write about my experiences in studying *Machine learning*, with a step by step approach. :four_leaf_clover:
---

### :star: Anaconda
  - [Installation](https://docs.anaconda.com/anaconda/install/)
    - [Installing on Windows](https://docs.anaconda.com/anaconda/install/windows/)
      - I had an issue with Anaconda installation on windows 7, `Failed to create Anaconda menus`. With the help of an [answer](https://stackoverflow.com/a/57635204/12777699) from <a href="https://stackoverflow.com/questions/tagged/python"><img  src=https://upload.wikimedia.org/wikipedia/commons/f/f7/Stack_Overflow_logo.png width="90"/>
</a>, version 2019.03 of Anaconda (from [download archive](https://repo.continuum.io/archive/)) successfully installed.
  - [Conda (Starting and managing)](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html#getting-started-with-conda) 
   
    :one: `conda --version` (in a terminal command line) :arrow_right: Conda version number (if it is installed properly).
    
    :two: `conda update conda` and then `y` (if needed) :arrow_right: Update conda to the current version.

    - **Anaconda Prompt:** :one: Start menu :two: search for and open "Anaconda Prompt". 
    - **Windows Command Prompt:** :one: Start menu :two: search for and open "cmd". 
        - When I typed `conda --version` in the Command Prompt, I encountered `conda is not recognized as an internal or external command,
          operable program or batch file`. This issue was resolved by **Method 3** of this [page](https://appuals.com/fix-conda-is-not-recognized-as-an-internal-or-external-command-operable-program-or-batch-file/).
  - [Managing environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#managing-environments)
     - Some useful command lines:
     
       :one:`conda create --name envname` or `conda create -n envname` :arrow_right: Create the environment "envname".
              
     
       :two: `conda activate envname`:arrow_right: Activate the environment "envname".
     
       :three: `conda info --envs`:arrow_right: A list of all your environments (active environment with an asterisk (*)).
     
       :four: `conda deactivate` :arrow_right: Deactivate environment.
         
       :five: `conda list -n envname` or `conda list`:arrow_right: A list of all packages installed in the environment "envname". 
     
       :six: `conda list -n envname pkgname`:arrow_right: To see if the package "pkgname" is installed in "envname".
     
       :seven: `conda install --revision=0` or `conda install --rev 0`:arrow_right: Restore active environment to the default version.
    
       :eight: `conda remove --name envname --all`:arrow_right: Remove the environment "envname".

### :star: Git
   - [Installation](https://git-scm.com/downloads)
   - [Documentation](https://git-scm.com/doc)
   - [Git Handbook (10 minute read)](https://guides.github.com/introduction/git-handbook/)
   - [Git Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
   - [Videos (Persian): Git](https://parsclick.net/course/PL3Y-E4YSE4wYFlcomsBtJy1nCu3jclA8L) by Amir Azimi
   - Videos (English): GitHub Ultimate-Master Git and GitHub by Jason Taylor
   
### :star: Other useful links

   - GitHub: [Tools in Data Science](https://github.com/hhaji/Tools-in-Data-Science) by Hossein Hajiabolhassan
   - GitHub: [Applied Machine Learning](https://github.com/hhaji/Applied-Machine-Learning) by Hossein Hajiabolhassan
