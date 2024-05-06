# project-team-58
Repo for project team 58. CS 598 - Deep Learning for Healthcare, Spring 2024.

## Team Members
- Brian Betancourt
- John Lewis
- Robbie Li

## Proposal (requires invite)
https://docs.google.com/document/d/1sGE6xXncTIIqT5_l86JG-nd6DTWGr3Xtw51ogAczY_s/edit?usp=sharing

## Setup

### Environment

This requires Python 3.8.10. To create the environment, run the following command:

```bash
python3 -m venv cass && source cass/bin/activate && pip install -r requirements.txt
```

## Instructions to Run
1. Import DL4H_Team_58.ipynb into Google Colab.
2. Select the T4 High-RAM GPU in "connect to new runtime".
3. Step through the notebook, running each code cell. This will cover all necessary installs and imports, data import and preprocessing, and training and evaluation.
   NOTE that any code cells specific to the brain tumor dataset can be skipped as we ended up using medMnist for our final project.
   NOTE that checkpoint paths may need to be adjusted depending on location for the user.

## References
- https://github.com/yinchangchang/DG-RNN
- https://ieeexplore.ieee.org/document/8970777

---
