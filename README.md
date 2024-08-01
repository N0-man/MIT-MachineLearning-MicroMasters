# Learning Notes from MITx 6.86x semister

Machine Learning with Python: from Linear Models to Deep Learning

**Disclaimer**: The following notes are a mesh of my own notes, forums, youtube, GPT, medium, some useful forum threads and various course materials (standford, MIT etc). There may be various error and that could very well be due to my own interpretation during learning. If you spot an error, want to specify something in a better way, add material or just have comments, you can clone, make your edits and make a pull request (preferred) or just open an issue.

### Running notebooks locally

- **install Poetry** : [from here](https://python-poetry.org/docs/basic-usage/) (I had better experience with brew on MacOS)
- **install dependencies** `poetry install`
- **setup poetry to use with vscode** a) `poetry shell` and then `code .` b) vscode would either ask you to select the Python interpreter OR manually select using Cmd+Shift+P+"Jupiter: select interpreter..." - choose the newly created venv

### Build Jupiter Book locally

Install ghp-import

```
pip install ghp-import
```

Build Jupiter Book

```
jb build .
```

> **Note**: as of July2024, jupiter-book wasnt cleanly able to convert base64 image attachments from notebook cells into external image to be used within html. The program [extract_base64_attachments.py](/extract_base64_attachments.py) runs as part of the pipeline scan each notebook cells and extract base64 images into external image files. Once the images are extracted, `sphinx` would take care of isolating all the image files into single image director as part of `jupiter-book build`

The GHA pipeline publishes the Jupiter Book at
https://N0-man.github.io/MIT-MachineLearning-MicroMasters/
