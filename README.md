# Diamonds EDA
#### Diamonds features exploration data analysis and visualization.
![Image](https://media.tiffany.com/is/image/tiffanydm/GuideToDiamonds_LP_Hero_Desktop_v2-2?$tile$&wid=2992)
### IRONHACK Data Analysis - Project II

This repository correspond to the data exploration project performed at IRONHACK Data Analysis Bootcamp.

The original dataset can be found at [Kaggle](https://www.kaggle.com/shivam2503/diamonds).


---
#### **Purpose**

The project scope is to practice exploration, analysis and visualization of a unknown dataset about diamonds and its features,
 in order to find key features and relationships.

It is split in three parts:
   * Dataset analysis performed on Jupyter Notebook.
   * A/B hypothesis testing performed on Jupyter Notebook.
   * Tableau interactive dashboard hosted in [this](https://public.tableau.com/profile/pablo5039#!/vizhome/Diamonds_15959547286880/Diamonddashboard) 
   Tableau Public repository.

The parameters included in the dataset are:

* **Carat**:   diamond weight
* **Cut**:     cut quality
* **Color**:   color
* **Clarity**: diamond clarity and inclusions
* **Depth**:   relationship between z, x and y: z/mean(x+y). Depth refers to the distance between the culet and the table when the diamond is viewed from the side.
* **Table**:   top horizontal facet, expressed as the relationship with the average girdle diameter. Excellent quality -> 52-62% 
* **Price**  
* **X**:       diamond length
* **Y**:       diamond width
* **Z**:       diamond height

Since this analysis will be used later to train a machine learning algorithm able to predict a diamond price,
Price is the kye feature that guides the data exploration.

#### **A/B Testing & conclusion**
When talking about diamonds the rarest and hardest to find, the higher the price. 
After carat weight, cut is the most important feature to set the price, followed by clarity and color; not every diamond can get a good cut because the inclusions or imperfections and they tend to be smaller. Also a good cut makes a diamond looks bigger and more shinning.

When we talk about low quality diamonds, prices tend to be more similar and the most important feature is its carat weight, followed by the cut.

Top diamonds are super rare to find and usually, a lot of material is wasted to avoid inclusions and imperfections while cutting the stone, therefore the diamonds with better features are very rare are their price increases easily, especially when the carat weight increases.


### **Tech stack**

- Analysis performed on Jupyter Notebook.
- Used libraries:
    - numpy
    - scipy
    - pandas
    - matplotlib
    - seaborn
    - plotly
      