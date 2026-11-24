# Twelfth Night: Dialogue & Character Interaction Analysis

A collaborative computational text analysis project

We are studying William Shakespeare's *Twelfth Night* using Python and network graphs to examine character dialogue, relationships, and structural shifts across the play's 5 acts.

---

##  Data Source & Citation

The play text is sourced directly from the **Folger Shakespeare Library Digital Edition**:

* **Corpus File:** `Twelfth_night_full_text.txt` (5 Acts, 18 Scenes)
* **Source:** [Folger Shakespeare Library — Twelfth Night](https://www.folger.edu/explore/shakespeares-works/twelfth-night/)


### Citation
> Shakespeare, William. *Twelfth Night*. Edited by Barbara A. Mowat, Paul Werstine, Michael Poston, and Rebecca Niles, Folger Shakespeare Library, 31 July 2015, https://www.folger.edu/explore/shakespeares-works/twelfth-night/.

---

##  Research Questions

1. **RQ1.** How do conversations change from Act 1 to Act 5? Do they get more chaotic and then settle?
2. **RQ2.** How separate are Orsino's court and Olivia's household? Who connects them?
3. **RQ3.** What changes if Viola and Cesario are treated as two people? What did the disguise let her do?

---

##  What is in this repository

| File | What it does |
|---|---|
| `data_cleaning.ipynb` | Turns the play into a table: one row per speech (926 speeches, 2,634 lines), stage directions in their own table, a cleaned version of each speech, and a `persona` column that marks when Viola is disguised as Cesario |
| `data/` | The cleaned tables made by `data_cleaning.ipynb` |
| `Character_line_visualization_1.ipynb` | Visualization 1: who speaks the most, overall and by act |
| `Visualization_2_networks/` | Visualization 2: character networks from the Folger XML (who shares the stage, and who hears whom) |
| `word_frequency.ipynb` | Visualization 3: word frequency, court vs household and Viola/Cesario |
| `figures/` | Saved charts |

---

Clone the repository

```bash
git clone https://github.com/SoumyA4348/twelfth-night-dialogue-analysis.git
```



## 👥 Group Members
* Soumya Patel
* Krish Shah
* Mason Helman
* Myra Thomas
* Abbey Altieri
