
# Projects

Code from my research, data-science training and AI tooling. Every project is open on [GitHub](https://github.com/dhruvadityasrivastava).

## AI tools for researchers
*   **[hallucination-check](https://github.com/dhruvadityasrivastava/hallucination-check)** · Claude skill · 2026
    *   Checks whether an AI answer can be trusted. It pulls out the facts that can be tested (numbers, citations, names, computed results), checks them against your own data first, then runs one targeted search, and reports a hallucination score with just the claims that failed. Capped at eight claims so the check stays cheap.
*   **[analysis-brief](https://github.com/dhruvadityasrivastava/analysis-brief)** · Claude skill and plugin · 2026
    *   Turns pasted tables, logs and long chat threads into a one-page brief: the data reduced to its schema, plus the decisions, failed attempts and finish line. Paste the brief into a fresh chat and carry on without re-sending the data.

## Machine learning in R
*   **[SVM recursive feature elimination](https://github.com/dhruvadityasrivastava/Support-Vector-Machine-Recursive-Feature-Elimination)** · R · caret · ggplot2 · 2026
    *   Finds the smallest set of variables that still predicts well: a linear SVM ranks features, drops the weakest and retrains, with 5-fold cross-validation at each step.
*   **[SVM feature ablation](https://github.com/dhruvadityasrivastava/svm-feature-ablation)** · R · caret · ggplot2 · 2026
    *   The reverse test: removes the most important features in steps and retrains, measuring how fast accuracy falls on unseen data.

## Deep learning and data science in Python
*   **[Plant seedling classification](https://github.com/dhruvadityasrivastava/plant-seedling-classification)** · Python · TensorFlow/Keras · OpenCV
    *   A convolutional neural network that identifies 12 plant-seedling species from images, a building block for automated weed and crop monitoring (~80% accuracy on held-out images).
*   **[FoodHub business insights](https://github.com/dhruvadityasrivastava/FoodHub-Business-Insights)** · Python · pandas · seaborn
    *   Exploratory analysis of a food-delivery order dataset, leading to recommendations on customer retention and weekday promotions.

## Bioinformatics
*   **[iDEP (fork)](https://github.com/dhruvadityasrivastava/idepGolem)** · R · Shiny · RNA-seq
    *   My fork of iDEP, the open-source platform from South Dakota State University for RNA-seq differential expression and pathway analysis, kept as my RNA-seq analysis workflow.

*The two Python projects come from the Post Graduate Program in AI and Machine Learning (UT Austin with Great Learning).*

[back](./)
