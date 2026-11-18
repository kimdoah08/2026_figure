# Lesson 4: Novel Methods in Mass Spectrometry Analysis
---
## Objectives
- Visualize mass spectrometry data with UMAP
- Use linear regression to find predictors of disease state in mass spectrometry data
- Learn the basics of cross validation
---
### Updating the Repository
As with last week, we'll get started today by updating our local repository using the instructions from [lesson 1](../lesson_1/intro_to_stats.md).

---
### Visualizing Mass Spectrometry Data
As you can probably guess after getting a look at mass spectrometry data in lesson 3, visualizing data with that many variables and dimensions is quite difficult if we want to try and see clear trends in our data before diving into an analysis. Thus we turn to [dimensionality reduction](https://en.wikipedia.org/wiki/Dimensionality_reduction). As we covered in lesson 2, dimensionality reduction works by capturing aspects of relationships between data in its full complexity and then simplifying said complexity until we can view it on a standard graph.


For today, we'll once again be applying [UMAP](https://en.wikipedia.org/wiki/Nonlinear_dimensionality_reduction#Uniform_manifold_approximation_and_projection) for this purpose, though you could reasonably use t-SNE as an alternative method.


1. To get started, open the `mass_spectrometry_analysis_part_2.ipynb` file in the `lesson_4` subdirectory of your local repository using Visual Studio Code.
2. Follow the instructions provided in the notebook until you reach the "Linear Regression" section, and then return here.

---
