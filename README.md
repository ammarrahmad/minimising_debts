# Minimizing Debts in a Group

This project focuses on solving the problem of minimizing the number of transactions required to settle debts within a group. Our work provides both theoretical and practical insights into the problem, showcasing its complexity and exploring approximation solutions.

---

## Highlights of Our Work

1. **Proving NP-Completeness**:
   - We rigorously proved that the debt minimization problem is NP-complete.
   - The proof is detailed in the research paper `Proof.pdf`, co-authored by Ammar Ahmad and Anand Kumar under the guidance of Dr. Arijit Mondal.

2. **Modeling as a Graph Problem**:
   - We modeled the problem as a graph, where nodes represent individuals and weighted edges represent debt relationships.
   - Graph visualization techniques were used to intuitively present the exchanges and their settlement paths.

3. **Interactive Demonstration**:
   - A Colab Notebook (`innovation_design.ipynb`) is provided to simulate and demonstrate the problem.
   - The notebook includes:
     - Random debt graph generation.
     - Graphical visualizations of debt relationships.
     - Execution of various approximation algorithms for debt minimization.

4. **Evaluating Approximation Solutions**:
   - We implemented and compared different approximation algorithms.
   - The results highlight which approaches offer decent approximations for the problem within practical constraints.

5. **Comprehensive Presentation**:
   - A video walkthrough of the project explains the theory, implementation, and results. You can access the video [here]([https://drive.google.com/file/d/your-video-link](https://drive.google.com/file/d/1rnxwr4caF9Bz_vF38rGbftq8Qh2tHPGO/view?usp=sharing)).
---

## Key Results
- **Theoretical Insight**: The debt minimization problem is NP-complete, as demonstrated by our proof.
- **Graphical Representation**: Debt relationships are effectively modeled and visualized as graphs.
- **Approximation Algorithms**: Various algorithms were implemented and evaluated, showcasing practical approaches for tackling the problem. We found out that the Maximum Pair Match is the most optimal approximation considering minimal transactions while considering time complexity constraints.

---

## Future Work
- **Scalability**: Extend the implementation to handle larger datasets and real-world scenarios.
- **Algorithmic Exploration**: Develop and test more heuristic or approximation algorithms.
- **User-Friendly Interface**: Create a web-based or standalone application for broader accessibility and ease of use.

---

## Credits
- **Ammar Ahmad**: Research, implementation, and visualization.
- **Anand Kumar**: Co-author of the research paper and implementation.
- **Dr. Arijit Mondal**: Project advisor.

---
### Additional References
- Verhoeff, Tom. "Settling multiple debts efficiently: An invitation to computing science." *Informatics in Education-An International Journal* 3.1 (2004): 105-126.
- Guillaume Fertin, Oscar Fontaine, Géraldine Jean, Stéphane Vialette. "The Maximum Zero-Sum Partition Problem." *25th International Computer Symposium, ICS 2022, Dec 2022, Taoyuan, Taiwan.* pp. 73-85, [10.1007/978-981-19-9582-8_7](https://doi.org/10.1007/978-981-19-9582-8_7).
- "Introduction to Algorithms, Third Edition" by Thomas H. Cormen and Charles E. Leiserson.

---
