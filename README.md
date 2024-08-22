# Learning Notes from MITx 6.86x semister

[Machine Learning with Python: from Linear Models to Deep Learning](https://www.edx.org/learn/machine-learning/massachusetts-institute-of-technology-machine-learning-with-python-from-linear-models-to-deep-learning)

[MIT MicroMasters® Program Calendar](https://micromasters.mit.edu/ds/upcoming-dates/)

**Disclaimer**: The following notes are a mesh of my own notes, forums, youtube, GPT, medium, some useful forum threads and various course materials (standford, MIT etc). There may be various error and that could very well be due to my own interpretation during learning. If you spot an error, want to specify something in a better way, add material or just have comments, you can clone, make your edits and make a pull request (preferred) or just open an issue.

---

**Note:** As a prerequisite, I had to brush up some basic math important for machine learning. Here are my Jupiter notes published as [Digital Book 📚](https://N0-man.github.io/math-for-machine-learning/)

---

### Running notebooks locally

- **install Poetry** : [from here](https://python-poetry.org/docs/basic-usage/) (I had better experience with brew on MacOS)
- **install dependencies** `poetry install`
- **setup poetry to use with vscode** a) `poetry shell` and then `code .` b) vscode would either ask you to select the Python interpreter OR manually select using Cmd+Shift+P+"Jupiter: select interpreter..." - choose the newly created venv

---

### Rendering base64 image attachments in JupiterBook

> **Note**: as of July2024, jupiter-book wasnt cleanly able to convert base64 image attachments from notebook cells into external image to be used within html. The program [extract_base64_attachments.py](/extract_base64_attachments.py) runs as part of the pipeline scan each notebook cells and extract base64 images into external image files. Once the images are extracted, `sphinx` would take care of isolating all the image files into single image director as part of `jupiter-book build`

---

### 📚 Jupiter Book Link

All my notes in jupiter notebooks are published as a [digital book 📚](https://N0-man.github.io/MIT-MachineLearning-MicroMasters/)
