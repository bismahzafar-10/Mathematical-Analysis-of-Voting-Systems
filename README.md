# Mathematical Analysis of Voting Systems

This repository contains the research, methodology, and conference poster for my project on the **Mathematical Analysis of Voting Systems**, which explores the application of mathematics to complex social choice issues. 

This work was officially accepted and presented as a **Poster Presentation** at the **Science Undergraduate Research Conference (SURC 2024)** at Azim Premji University.

---

## 📊 View the Poster
The complete, high-resolution research poster presented at the conference can be found here:
📁 [View Conference Poster (Mathematical Analysis of Voting Systems.png)](./Mathematical%20Analysis%20of%20Voting%20Systems.png)
---

## 🧠 Research Overview & Theoretical Framework
This study rigorously examines key voting methods—including Plurality, Runoff, Borda Count, and Condorcet—to evaluate their systemic strengths, structural weaknesses, and susceptibility to strategic manipulation. 

The analysis utilizes foundational mathematical frameworks in social choice theory:
* **Arrow’s Impossibility Theorem:** Used to evaluate the extent to which voting systems can simultaneously reconcile criteria like universality, independence of irrelevant alternatives, and non-dictatorship.
* **Gibbard-Satterthwaite Theorem:** Applied to investigate the inherent vulnerability of multi-candidate electoral systems to strategic voting and manipulation.
* **Condorcet Criterion:** Used to assess whether specific voting methods consistently select the candidate who can win all pairwise matchups.

## 💻 Methodology & Simulations
To evaluate the probabilistic nature of these systems, the project utilized:
1. **Monte Carlo Simulations:** Generated random voter preference profiles across varying population sizes to simulate elections under different voting rules.
2. **Data Analysis:** Performance metrics were computed to analyze the probability of selecting a Condorcet winner, the prevalence of voting paradoxes, and overall robustness to strategic manipulation.

## 📈 Key Findings & Discussion
* **Trade-offs in Design:** No single voting system fully overcomes the inherent trade-offs between fairness, efficiency, and manipulability.
* **Borda Count:** Demonstrated better overall efficiency in ranking collective preferences but exhibited a higher mathematical vulnerability to strategic manipulation.
* **Plurality & Runoff:** Frequently failed to consistently identify Condorcet winners, raising questions about their suitability in competitive, multi-candidate elections.
* **Future Work:** Explores the mathematical calibration of hybrid voting systems and the potential of blockchain to enhance democratic transparency.

Note: The original Monte Carlo simulation scripts were executed in a local environment and are currently being refactored for open-source distribution.
---

## 📚 References
1. Harrenstein, P., Lackner, M., & Lackner, M. (2020). *A Mathematical Analysis of an Election System Proposed by Gottlieb Frege.*
2. Shokil, T. (2023). *A Comparative Study of Electoral Systems.* University of Dhaka.
3. Hodge, J., & Klima, R. (2005). *The Mathematics of Voting and Elections: A Hands-On Approach.* American Mathematical Society.
4. Saari, D. G. (2001). *Decisions and Elections: Explaining the Unexpected.* Cambridge University Press.
