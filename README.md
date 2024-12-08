# Group 1
* Jakob Wickham, Nick Brady, Noah Sturgeon

Group 1 project for DSCI445 @ CSU

### Contents of the repository:
* `create_paper.ipynb` - The notebook file to compile the paper
* `model_results.csv` - A CSV file containing the results of all models used in the project for easy access in the paper
* `paper.ipynb` - The paper in notebook format. Includes code cells for certain things
* `paper.pdf` - The compiled paper
* `presentation.ipynb` - The presentation in notebook format. Includes code cells for certain things
* `presentation.slides.html` - The compiled presentation
* `proj.ipynb` - The main notebook that our project resides in

### Installation process to get things running:
* Install Python if you haven't already: https://python.org (recommended version 3.9+)
    * Python should come with `pip` installed. If it somehow doesn't, install it
* Install Jupyter Notebook (JupyterLab, VSCode, Conda, etc.)
    * For our project, we programmed in VSCode using the Jupyter Notebook extension
    * If you don't use VSCode, install accordingly
* Install the packages necessary to run the code:
    * `pip install numpy pandas matplotlib imbalanced-learn scikit-learn seaborn xgboost kagglehub`
    * If you run into issues with installing these, append `--user` at the end of the command
* Install these things to compile the paper:
    * `pip install nbconvert pandoc`
    * LaTeX (https://www.latex-project.org/get/) (I prefer MiKTeX)
    * For more information, read here: https://nbconvert.readthedocs.io/en/latest/install.html

### The project
* Open the `proj.ipynb` file and run all code cells
* **NOTE**: This will take at least **3 hours** to fully run. You will need at least 16 GB of RAM to run. Run at your own risk.

### The paper:
* Open the `create_paper.ipynb` file and run the code cell to create the paper
* **NOTE**: Any numbers, graphs, and tables were taken from the project notebook. Since it takes a long time to compute, we copied the results over to easily make the paper.

### The presentation
* In the same directory as the project, run: `jupyter nbcovert presentation.ipynb --to slides`
* Open the `presentation.slides.html` file in a browser