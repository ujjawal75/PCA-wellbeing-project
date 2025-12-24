PCA-Based Dimensionality Reduction of
Community Well-Being Indicators
This project aims to simplify high-dimensional community well-being data using Principal
Component Analysis (PCA) and Sparse PCA. The goal is to enhance policy monitoring and
interpretability for multiple stakeholders such as governments, NGOs, and planners.
1. Introduction
Community well-being is measured using hundreds of heterogeneous indicators related to health,
education, economy, environment, safety, housing, and social inclusion. Analyzing such
high-dimensional data is challenging. This project proposes an unsupervised machine learning
framework to reduce complexity while preserving essential information.
2. Objectives
• Reduce dimensionality of large-scale well-being datasets • Discover latent well-being constructs •
Improve policy interpretability • Enable stakeholder-friendly visualization using Gradio
3. Dataset Description
A synthetic large-scale dataset containing 5,000 communities and 300 indicators was generated.
The indicators span six domains: Health, Education, Economy, Environment, Safety, and Housing.
Latent factors were used to simulate realistic correlations.
4. Methodology
The methodology consists of data preprocessing, PCA-based dimensionality reduction, and Sparse
PCA for interpretability. First, features are standardized. PCA reduces redundant features while
preserving variance. Sparse PCA enforces sparsity, making components interpretable.
5. Tools and Technologies Used
• Python • NumPy, Pandas • Scikit-learn • Matplotlib • Gradio • Google Colab
6. Results and Discussion
The proposed framework successfully reduced 300 indicators to 8 interpretable latent dimensions.
These dimensions represent core aspects of community well-being such as economic stability,
public health quality, and educational access.
7. Societal Impact
The project supports evidence-based governance, transparent policy monitoring, and improved
allocation of resources. It aligns with Sustainable Development Goals (SDGs).
8. Conclusion
This project demonstrates that PCA and Sparse PCA can effectively simplify complex community
well-being data. The integration of Gradio makes the system accessible to non-technical
stakeholders.
