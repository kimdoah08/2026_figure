# Lesson 4: Novel Methods in Mass Spectrometry Analysis
---
## Objectives
- Visualize mass spectrometry data with UMAP
- Use linear regression to find predictors of disease state in mass spectrometry data
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
### Linear Regression with Mass Spectrometry
Now that we've taken a look at our data, we'll next try to fit a predictive model to it that can determine if a given sample is from the schizophrenia or control groups. As we covered in lesson 2, by assigning our labels of choice a numerical value, we can then fit a linear regression to those labels and our ion intensities. In theory, we could then provide the ion intensity data of a new patient to this model in order to predict if they were likely to have schizophrenia or not.

1. Return to the Jupyter notebook and follow its instructions until you reach the "Challenges" section, and then return here.

---
## Challenges
These are extra activities which shouldn't take you all that long, but will help reinforce some of the things we've practiced today. We'll discuss them during our next lesson, so don't worry if you aren't able to figure something out.
1. Split our dataset by if each entry is from layers 1-3 of the prefrontal cortex or layers 4-6, then create a new UMAP and linear classifier to try and determine if each sample is from a control individual or an individual with schizophrenia.
2. Commit the changes you've made to GitHub.
