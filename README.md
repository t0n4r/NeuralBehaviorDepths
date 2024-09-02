# Multidimensional Behavioral Influences on Brainwide Neural Activity
## Project Overview
This repository contains the analysis for our project "Investigating Multidimensional Behavioral Influences on Brainwide Neural Activity", completed as part of the NeuroMatch Academy's Summer Program on Computational Neuroscience.

## Project Description
We investigated how spontaneous behaviors such as running and changes in pupil area modulate neural activity within specific cortical depths, and which cortical layers are most significant in encoding these behaviors. Our analysis focused on the Stringer et al. (2019) dataset, exploring the relationship between neural activity and behavioral states.

## Repository Structure
```
.
├── README.md
├── neural_behavior_analysis.ipynb
└── presentation.pdf
```


## Key Findings
- Deeper cortical layers (-390 to -350 μm) are more effective in predicting pupil area
- Mid-deep layers (-270 to -230 μm) are more effective in predicting running speed
- Superficial cortical layers (-190 to -150 μm) have the lowest predictive power for both behaviors

## Usage

1. Clone this repository
2. Install the required packages:
```
pip install -r requirements.txt
```
3. Open and run NeuralBehaviorAnalysis.ipynb in Colab Notebook

## Data
This project uses the Stringer et al. (2019) dataset. Due to size constraints, the data is not included in this repository. Please download the dataset using the notebook.

### Team Members
- Murshed Al Amin
- Zaynab Soyokulova
- Aryan Mohanani
- Sampad Debnath

## Acknowledgements
We thank the NeuroMatch Academy for providing the opportunity to work on this project, and our TAs Amirreza Bahramani and Faezeh Shafiei for their guidance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
