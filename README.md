# IISc_DSP-Project_Recommendation-System

# Project Title 
## Book recommendation based on user interactions on it's purchases

## Team Members
 - Meenal Dhuria (meenaldhuria@iisc.ac.in)
 - Kshitiz Singh (kshitizsingh@iisc.ac.in)
 - Jyoti Pal (jyotipal@iisc.ac.in)
 - Rishav Kumar Goswami (rishavg@iisc.ac.in)

## Problem Statement
### Background:
  Recommending relevant products to customers is the key to improving user experience and sales. Analysing purchase history can reveal valuable insights into customer preferences.

### Importance: 
  Effective recommendations can increase customer retention and average order value, improving the overall shopping experience.
  
### Objectives:
  Build a recommendation system based on purchase history. Use machine learning to predict relevant products.

## How data science san help?
  Machine learning can detect patterns and suggest products based on similar users and products, enhancing personalization.


## Methods/Models:
  There are multiple methods available for solution of the recommendation problem like:
  - Collaborative Filtering: Recommend based on user-item interactions.
  - Content-Based Filtering: Use product attributes for recommendations.
  - Hybrid Methods: Combining both approaches for better accuracy.

## Justification:
  Collaborative filtering captures user preferences, while content-based filtering ensures relevant products.
  For our use case, we will be using “Model based Collaborative Filtering” and “Content-Based Filtering”
  Since, we have user and its interaction like `review` and `start rating` for their purchased products. 
  
## Future Work
   **Cold-Start Problem**: Implementing methods to handle new users and items.
   **Model Improvement**: Experiment with advanced models like collaborative filtering with matrix factorization, or deep neural networks.
   **Scalability**: Investigating how the model can scale to larger datasets.  

## Tools/Technologies:
   Python libraries like Pandas, NumPy, Scikit-learn, scipy, ipywidgets, IPython for recommendation algorithms.

## Conclusion
  This project successfully developed a recommendation system using collaborative filtering and content-based filtering. The results suggest that combining multiple approaches improves the 
  accuracy of recommendations. Future work will focus on handling cold-start problems and improving the scalability of the system.



