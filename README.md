# RELand System: AI-Driven Landmine Risk Detection

## Project Overview
This project involves creating and demonstrating the RELand System, an advanced machine-learning platform designed for humanitarian demining. It employs state-of-the-art artificial intelligence methods to detect and prioritize landmine clearance in conflict-affected regions, enhancing both community safety and economic development.

### Section 1: Problem Statement
Landmines remain hidden threats long after conflicts end, restricting economic growth, threatening lives, and impeding recovery. Traditional landmine clearance methods are expensive, dangerous, and inefficient, often based on limited or incomplete information. Thus, there is a critical need for data-driven, precise, and cost-effective solutions to accurately estimate landmine risk and optimize demining efforts.

### Section 2: RELand White Paper Summary
The white paper titled "RELand: Risk Estimation of Landmines via Interpretable Invariant Risk Minimization" outlines an innovative system developed in partnership with Carnegie Mellon University and humanitarian organizations. The RELand system is structured around three main components:
Dataset Enhancement:
Combines geographic, historical, and socio-economic indicators into a rich, accurate dataset, enhancing prediction quality and robustness.
Risk Modeling:
Utilizes a custom-built, interpretable neural network employing Invariant Risk Minimization (IRM) and Sparse Feature Masking to reliably detect landmines across diverse geographic conditions and data distributions.
Interactive Interface:
Features a user-friendly web tool providing visualizations of predicted risk and recommended priority zones, significantly assisting demining organizations in making data-informed operational decisions.

### Section 3: Machine Learning & AI Techniques
The project involved detailed exploration and practical implementation of the following advanced ML/AI techniques:
Deep Tabular Neural Networks:
Multi-layer perceptron architecture with dense layers, batch normalization, dropout layers.
Captures complex relationships within structured tabular data efficiently.
Invariant Risk Minimization (IRM):
Robust training method that generalizes across different data environments.
Penalizes reliance on spurious correlations, resulting in models resilient to shifts in regional characteristics.
Sparse Feature Masking:
Selectively weights features, highlighting only the most predictive indicators (e.g., proximity to past mine events, terrain factors).
Improves interpretability and reduces noise in predictions.

### Section 4: Python Code Demonstration
A detailed and robust Python script was created to simulate RELand’s neural network methodology, covering:
Synthetic Data Generation:
Created a realistic dataset emulating geographic and historical risk indicators.
Neural Network Design & Training:
Custom Keras-based deep neural network implementing sparse feature masking and IRM.
Employed TensorFlow’s advanced training mechanisms and custom loss functions.
Evaluation and Validation:
Model performance assessed through accuracy metrics and comprehensive classification reports.
Demonstrated significant improvements over traditional methods, validating RELand's effectiveness.
This code demonstration offers a practical proof-of-concept, showcasing how RELand can accurately predict landmine risks with high robustness and interpretability.

### Section 5: Interactive HTML Website
The project included an interactive HTML website that visually demonstrates the RELand system capabilities:
Topographical Interactive Grid:
Emulates a real-world topographic map, displaying transparent, color-coded risk levels (low, medium, high).
Provides interactive sliders for threshold adjustments and a “randomize” button for simulated risk scenarios.
Interactive Risk Exploration:
Clickable grid cells open modal dialogs providing detailed explanations and feature contributions.
Enhances user understanding of AI-driven decision-making processes behind risk predictions.
Educational Value:
Highlights the interpretability and practical applicability of RELand's AI methodology, making complex concepts approachable for stakeholders.

### Section 6: Business and Economic Implications
Deploying the RELand system holds significant economic and societal value:
Accelerates Economic Recovery:
Rapidly cleared lands are returned to productive economic use—agriculture, real estate, infrastructure, and investment attraction.
Cost Savings and Efficiency:
Significant reductions in operational expenses by minimizing false positives and accurately prioritizing demining efforts.
Enhanced Community Development:
Increased community safety and economic opportunities boost local livelihoods, creating sustainable growth post-conflict.
Technological and Economic Innovation:
Encourages adoption of advanced AI solutions across broader humanitarian and risk management contexts, fostering innovation and business confidence.

### Section 7: Project Impact and Future Directions
The RELand project demonstrates how advanced AI techniques can directly contribute to humanitarian efforts:
Immediate Impact:
Successfully tested in pilot locations, identifying previously undetected landmines and streamlining resource allocation.
Long-term Benefits:
Scalable and adaptable framework, potentially applicable globally in diverse post-conflict scenarios.
Future Improvements:
Expanding dataset richness with additional geospatial and conflict data.
Enhancing real-time interactive dashboards for operational use.
Applying similar AI frameworks to related humanitarian and environmental challenges.

## Conclusion
This RELand project effectively showcases how AI can bridge technology with humanitarian goals, delivering reliable, interpretable, and scalable solutions for landmine risk detection. Through practical demonstrations—white papers, code implementations, and interactive tools—this project illustrates a powerful approach toward creating safer, economically vibrant communities in post-conflict environments.

### RELand AI Web Demo – Landmine Risk Prediction Website

** Live Demo: **  
[https://Brandon-Tirado.github.io/reland-demo-risk-map/](https://Brandon-Tirado.github.io/reland-demo-risk-map/)

** Prompt Used: **

> Please develop a website using HTML that demonstrates how the RELand model works for landmine detection using deep neural networks, machine learning and other AI techniques to produce probabilities of where landmines may be. It needs to work in the same way that the RELand system does using the variables such as distance from road, proximity to historical events, and also uses geospatial data/characteristics, and community variables i.e. past conflicts.

> Change the HTML code so I have the ability to insert a topographical map underneath the transparent grid squares that indicate low, medium, and high risk so that the user can see the topography of the indicated risk area.
