# Mathematical Analysis of Voting Systems

An investigation into the vulnerabilities, fairness criteria, and strategic manipulation of key voting methods (Plurality, Runoff, Borda Count, and Condorcet) using mathematical frameworks and computational simulations.

## 🌟 Conference Presentation
This research was presented as a **Poster Presentation** at the **Science Undergraduate Research Conference (SURC 2024)** at Azim Premji University. 

📄 [View the full conference poster](./path/to/image_42e2fd.jpg)

---

## 🧠 Theoretical Framework
This project rigorously evaluates voting methods against critical impossibility theorems:
* **Arrow’s Impossibility Theorem:** Evaluating how voting systems reconcile criteria like universality, independence of irrelevant alternatives, and non-dictatorship.
* **Gibbard-Satterthwaite Theorem:** Investigating the vulnerability of electoral systems to strategic voting and manipulation.
* **Condorcet Criterion:** Testing if methods consistently select the candidate who wins all pairwise matchups.

## 💻 Computational Approach & Simulations
To analyze the probabilistic nature of these systems, I implemented:
* **Monte Carlo Simulations:** Generated random voter preference profiles across varied population sizes to simulate elections.
* **Data Analysis:** Evaluated outcomes based on the probability of selecting a Condorcet winner, the prevalence of paradoxes, and robustness to strategic manipulation.

## 📊 Key Results
* Plurality and runoff systems showed a significant failure rate in consistently identifying Condorcet winners.
* While Borda Count demonstrated better overall efficiency in ranking preferences, it exhibited higher vulnerability to strategic manipulation.
*(Tip: You can insert 1 or 2 of your key plot images here!)*

## 🛠️ How to Run the Simulations
```bash
git clone [https://github.com/yourusername/voting-systems-analysis.git](https://github.com/yourusername/voting-systems-analysis.git)
cd voting-systems-analysis
pip install -r requirements.txt
python main.py
```
---

## 3. Don't Forget the GitHub "About" Section
On the right-hand side of your GitHub repository page, fill out the **About** section using strong keywords so it pops up if someone searches for relevant terms:

*   **Description:** *Computational analysis and Monte Carlo simulations of voting system vulnerabilities using Arrow’s and Gibbard-Satterthwaite theorems. Presented at SURC 2024.*
*   **Topics/Tags:** `mathematical-modeling`, `monte-carlo-simulation`, `social-choice-theory`, `voting-systems`, `python`, `data-analysis`.

This turns a simple academic poster into a tangible, open-source project that proves your coding, data visualization, and analytical skills!
