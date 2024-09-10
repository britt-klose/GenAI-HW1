# GenAI-HW1

# Problem 1: Extending the Model to Include a Third Category
Given a model that classifies points as either "Land" or "Sea". Extend the model to include a third category, "Coastline", which represents points that are within a certain distance from any land point. The distance threshold for "Coastline" should be configurable.

**Complete the following todos:**

  - Modify the classify_point function to include the "Coastline" category.
  
  - Use a distance threshold of 10 units for the "Coastline" category.
  
  - Update the plotting function to visualize the new classification.

**Steps to Complete the Exercise**
  **Modify the Classification Function:**

      - Update the classify_point function to check if a point is within the distance threshold from any land point and classify it as "Coastline" if true.
      - Use the existing distance calculation method to determine if a point is within the threshold.

**Update the Plotting Function:**

      - Modify the plot_points function to include a new color and legend for "Coastline" points.
      - Plot the test points with the updated classification.
  
**Test the Implementation:**

       -  Define a new set of test points that include points close to land masses.
       -  Print the classifications and visualize the results.


# Problem 2: Likelihood-Based Classification
Modify the classification method to use likelihoods calculated based on distances to land points instead of a simple bounding box. Classify points as "Land" if the likelihood of being land is greater than a certain threshold, and as "Sea" otherwise.

  - Define a likelihood threshold for classification (e.g., 0.5).
  
  - Modify the classify_point function to use the likelihoods calculated in the calculate_likelihoods function.
  
  - Update the main execution block to use the new classification method and visualize the results.

**Steps to Complete the Exercise**

  **Calculate Likelihoods:**

      - Ensure the calculate_likelihoods function is correctly computing the likelihoods for all grid points.

  **Modify the Classification Function:**
  
      - Update the classify_point function to classify points based on their likelihood of being land.
      - Use a threshold value to determine the classification.

  **Update the Plotting Function:**

      - Ensure the plot_points function can handle and visualize the new classification method.

  **Test the Implementation:**
  
      - Define a set of test points with varying distances to land masses.
      - Print the classifications and visualize the results.
