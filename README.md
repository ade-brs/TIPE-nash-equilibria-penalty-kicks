# Nash Equilibria in Penalty Kicks — Game Theory Analysis

##  Project Overview
This project explores the concept of **Nash equilibria** in the context of **penalty kicks in football**, using tools from **game theory**, **probability**, and **statistical analysis**.

The study was carried out as part of a two-year **TIPE (Travail d’Initiative Personnelle Encadré)** project, a national research-based examination required for entrance exams to French engineering schools.

The project focuses on how both the penalty taker and the goalkeeper can optimize their strategies to maximize success probabilities.

---

##  Research Question
**How can a penalty taker or a goalkeeper significantly increase their chances of scoring or stopping a penalty by using Nash equilibria and statistical analysis?**

---

##  Theoretical Framework
- Non-cooperative game theory
- Nash equilibrium (pure and mixed strategies)
- Zero-sum matrix games
- Expected payoff functions
- Optimization under probabilistic strategies

The theoretical foundations rely on **John Nash’s theorem**, which guarantees the existence of at least one Nash equilibrium in finite games. :contentReference[oaicite:1]{index=1}

---

##  Application: Penalty Kicks
- Players: penalty taker vs goalkeeper
- Strategies: left / center / right
- Payoff matrices constructed from real match data
- Mixed strategies derived analytically
- Identification of equilibrium strategies for both players

---

##  Statistical Study
- Manual data collection from video analysis (~5 hours)
- 214 penalty kicks analyzed (Lionel Messi dataset)
- Construction of empirical payoff matrices
- Success rate analysis based on player positioning

The statistical study allowed estimation of real-world probabilities used in the game-theoretic model. :contentReference[oaicite:2]{index=2}

---

##  Mathematical Results
- Construction of payoff matrices for both players
- Derivation of utility functions
- Analytical computation of Nash equilibrium using partial derivatives
- Proof of existence of a mixed-strategy equilibrium
- No pure-strategy equilibrium identified

The optimal mixed strategies were:
- **Penalty taker**: (0.483, 0.110, 0.407)
- **Goalkeeper**: (0.420, 0.203, 0.377)

:contentReference[oaicite:3]{index=3}

---

##  Python Simulations
Monte Carlo simulations were implemented in Python to validate the theoretical results.
Different strategy configurations were simulated over 10,000 penalty kicks:
- Random vs random strategies
- Optimal vs random strategies
- Optimal vs optimal strategies

Results showed an improvement of approximately **3–3.5%** in scoring probability when using optimal mixed strategies. :contentReference[oaicite:4]{index=4}

---

##  Tools & Technologies
- **Mathematics** (linear algebra, optimization, probability)
- **Python** (Monte Carlo simulations)
- **Statistical analysis**
- **Game theory**
- **Data collection from video analysis**

---

##  Academic Context & Team
This project was carried out as a **two-year team project** during preparatory classes (MPSI/MP),
as part of the **TIPE (Travail d’Initiative Personnelle Encadré)** examination required for
French engineering school entrance exams.

**Team members:**
- Adélaïde Broucas
- Thibaut Laheurte

---

##  Educational Value
This project illustrates how abstract mathematical concepts such as Nash equilibria
can be applied to real-world decision-making problems, particularly in sports analytics.

It demonstrates strong skills in:
- Mathematical modeling
- Analytical reasoning
- Statistical inference
- Computational simulation

