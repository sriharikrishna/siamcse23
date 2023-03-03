# Integrating Scientific Simulations with Machine Learning Algorithms
https://www.siam.org/conferences/cm/program/minitutorials/cse23-minitutorials

**Organizers**: Ludger Paehler, Technical University of Munich; Sri Hari Krishna Narayanan and Jan Hueckelheim, Argonne National Laboratory

## Session 1: Friday, March 3, 9:20 a.m. - 11:00 p.m. CET
| Content      | Resources |
| ----------- | ----------- |
| Welcome & Introduction     | [Slides](https://github.com/sriharikrishna/siamcse23/blob/main/Intro.pdf)       |
| Demo & Hands on: Rosenbrock | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/rosenbrock_pytorch.ipynb)|
| Seed matrices   | [Slides](https://github.com/sriharikrishna/siamcse23/blob/main/Seeding.pdf)         |
| Demo & Hands on: PyTorch Seeding | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/pytorch_seeding.ipynb)|
| Demo & Hands on: Tapenade | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/tapenade.ipynb)|
| Demo & Hands on: Enzyme | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/EnzymeTutorial.ipynb)|
## Session 2: Friday, March 3, 11:30 a.m. - 13:10 p.m. CST
| Content      | Resources |
| ----------- | ----------- |
| Welcome      | [Slides](https://github.com/sriharikrishna/siamcse23/blob/main/Intro_Session2.pdf)       |
| Demo: Integrating Simulations into PyTorch | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/SimulationInML.ipynb)|
| Demo & Hands on: PINN with PyTorch and Tapenade | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/pinn_tapenade.ipynb)|
| Demo & Hands on: Integrating ML into Simulations | [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sriharikrishna/siamcse23/blob/main/MLintoSimulations.ipynb)|



## How to run the notebooks
### Option 1 (preferred): Using Google Colab. (You will need to login to your Google account)
1. Click on the [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)]() button for the session

### Option 2: Use Jupyter Notebook locally 
1. Clone this repository or download it
2. Install any prerequisites
```
pip install jupyterlab
```
3. Open the notebook
```
jupyter notebook rosenbrock_pytorch.ipynb
```
### Option 3: Use python version locally
1. Clone this repository or download it
2. Install any prerequisites
```
pip install pytorch
```
3. Run the python code
```
python rosenbrock.py
```
