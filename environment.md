# Environment setup

## Github Desktop

For syncing local files with GitHub.

### Installation

1. Download application from [here](https://desktop.github.com/)
2. Open GitHub Desktop, navigate to ```File > Clone repository...```
3. Search for "Social Analytics", otherwise, search by url and paste the repository url: https://github.com/terenceneo/Social-Analytics
4. Choose the Local path (folder) you want to download the repository to.

### Workflow to make an update to Git repo

1. ```Fetch origin```
2. If your copy is not up to date, you will be able to ```Pull from origin```
3. Make your changes
4. You will be able to view your files changed and lines changed in each file. Select the appropraite files, give the commmit a name and ```Commit to master```.
    - The purpose of commit names are for revision history purposes
    - In commit names, use present tense words such as Create (file), Add (feature), Remove, Update, Fix, etc
    - In addition, I have created automations with the Kanban board with Fix and Close. So if you Fix #1: commit description, Issue #1 will be shifted to the completed board
5. ```Push to origin``` to upload your changes

## Jupyter lab

Allows you add more extensions to Jupyter, will be needed for the installation of the Jupyter lab-git extension. Should be installed by default with Anaconda

### Installation

Run the following command in Anaconda prompt

```shell
conda install -c conda-forge jupyterlab
```

### Run

To open jupyter lab, navigate into the folder you want to open and run

```shell
jupyter lab
```

Alternatively, because JupyterLab is a server extension of the classic Jupyter Notebook server, you can launch JupyterLab by calling jupyter notebook and visiting the /lab URL.

## Jupyter lab-git extension

An intuitive and visual way (GUI) to collaborate on JupyterLab. You can use the Git extension to create and switch branches, stage and commit code changes, send push and pull requests to shared repositories, see the version history in detail, and revert to previous versions when needed.

Allows preview of changes made in python notebooks.

![](https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2018/11/27/sagemaker-git-13.gif)

```shell
pip install --upgrade jupyterlab-git
jupyter lab build
```

### References

- Jupyter lab: https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
- Jupyter lab-git extension: https://github.com/jupyterlab/jupyterlab-git