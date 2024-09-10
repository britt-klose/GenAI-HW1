# GenAI-HW1

**#Problem 1:** Extending the Model to Include a Third Category
Currently, the model we discussed in lecture classifies points as either "Land" or "Sea". Extend the model to include a third category, "Coastline", which represents points that are within a certain distance from any land point. The distance threshold for "Coastline" should be configurable.

- Modify the classify_point function to include the "Coastline" category.

- Use a distance threshold of 10 units for the "Coastline" category.

- Update the plotting function to visualize the new classification.

**#Steps to Complete the Exercise**
  **Modify the Classification Function:**

    Update the classify_point function to check if a point is within the distance threshold from any land point and classify it as "Coastline" if true.

    Use the existing distance calculation method to determine if a point is within the threshold.

**Update the Plotting Function:**

    Modify the plot_points function to include a new color and legend for "Coastline" points.

    Plot the test points with the updated classification.
  
**Test the Implementation:**

    Define a new set of test points that include points close to land masses.

    Print the classifications and visualize the results.
