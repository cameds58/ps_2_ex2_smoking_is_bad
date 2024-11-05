# Setup

To install the required packages, run the following command in the terminal (!You have to first
create the environment.yml!):

```bash
conda env create -f environment.yml
conda activate smoke
```

## Pre-commit

This repository uses pre-commit to run some checks before each commit. !You have to first create
the .pre-commit-config.yaml!

### Setting Up Pre-Commit Hooks
Run the following commands to set up pre-commit hooks:
```bash
pre-commit install

To run the checks manually, run:

```bash
pre-commit run --all-files
```

"We use nbstripout as a pre-commit hook to remove cell outputs from Jupyter notebooks before committing, which helps keep the repository lightweight and focuses on the code rather than output artifacts."

"The .gitattributes file helps control specific behaviors for different file types in Git, such as ensuring line endings are consistent across operating systems."



