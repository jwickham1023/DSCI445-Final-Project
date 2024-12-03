# Group 1
* Jakob Wickham, Nick Brady, Noah Sturgeon

Group 1 project for DSCI445 @ CSU

### Installation process to get things running:
* Install Python if you haven't already: https://python.org (recommended version 3.9+)
    * Python should come with `pip` installed. If it somehow doesn't, install it.
* Install the packages necessary to run the code:
    * `pip install numpy pandas matplotlib imblearn sklearn seaborn xgboost kagglehub`
    * If you run into issues with installing these, append `--user` at the end of the command
* Install these things to compile the paper:
    * `pip install nbconvert pandoc`
    * LaTeX (https://www.latex-project.org/get/) (I prefer MiKTeX)
    * For more information, read here: https://nbconvert.readthedocs.io/en/latest/install.html

### The paper:
* Open the `create_paper.ipynb` file and run the code cell to create the paper

### The presentation
* In the same directory as the project, run: `jupyter nbcovert presentation.ipynb --to slides`
* Open the `presentation.slides.html` file