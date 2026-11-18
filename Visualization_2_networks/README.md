# Visualization 2: Character networks

This folder holds the network notebooks for Visualization 2.

| Notebook | Who | What it shows |
|---|---|---|
| `Krish_Co-presence_Networks.ipynb` | Krish | **Part 1.** Who shares the stage (A. Co-presence) and Kim's (2024) "everyone on stage hears" rule (K. Kim's exchange): whole play, per act, court vs. household bridges, Viola vs. Cesario, and the letter scene (2.5). |
| `Myra_Speaking_Networks.ipynb` | Myra | **Part 2.** Who actually talks to whom (B1. Next speaker, B2. Addressed), on the same layout and colours. *(Myra: add your notebook to this folder.)* |

## Running
- Open a notebook from **inside this folder** and run all cells (Jupyter, VS Code or Colab).
- Needs the course environment plus `lxml` and `requests`.
- The play is in `data/Twelfth Night.xml` (Folger TEI XML, the copy from Kim's repository). If the file is missing, the notebook downloads it.
