## Table of Contents
- [Installation](#installations)
- [Project Motivation](#project-motivation)
- [File Descriptions](#file-descriptions)
- [Resuçts](#results)
- [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)
  
## Installation
To run this project, you will need to have the following installed:
1. **Python 3.8+:** Download and install from [python.org](https://www.python.org/).

2. **Jupyter Notebook:** For running and executing the analysis.

3. **Required Libraries:** Install the dependencies listed below:
    - *pandas* for data manipulation
    - *numpy* for numerical computations
    - *matplotlib* and *seaborn* for data visualization
    - *scikit-learn* for machine learning
    - *scipy* for statistical tests

## Project Motivation
My main goal in this project was to analyze Airbnb accommodation data from Seattle and Boston to address key business questions, such as:

- What factors most influence the price of Airbnb accommodations?
- What are the most valued amenity combinations, considering average price and high demand?
- How do guest preferences for amenities differ between properties with high ratings and low ratings in Seattle and Boston?

## File Descriptions
The following files are available in the repository:

- **Project_Airbnb.ipynb:** A notebook containing the analyses conducted based on the CRISP-DM method to answer the business questions.
- **listings:** CSV files from both Boston and Seattle, containing detailed data about Airbnb listings, including accommodation features, host details, prices, and availability.
- **calendar and reviews:** These datasets were not used in the analysis but are provided here for reference.

## Results
This project provided valuable insights into the Airbnb data from Seattle and Boston. Key findings include:

- **Factors influencing price:** Variables such as accommodates, number of bedrooms and bathrooms, and room type were identified as significant drivers of price.
- **Valued amenity combinations:** Certain combinations of amenities, such as doorman, cats and suitable for events, were strongly associated with higher prices and demand.
- **Guest preferences:** High-rated properties tended to offer more essential amenities compared to low-rated ones. This suggests a potential alignment between the availability of these amenities and guest expectations, based on their ratings.

For a detailed discussion of the analysis and findings, please visit my blog post here.

## Licensing, Authors, Acknowledgements
This project is based on Airbnb data provided by Kaggle and Airbnb itself. More information about the data can be found at [Boston Data](https://www.kaggle.com/datasets/airbnb/boston) and [Seattle Data](https://www.kaggle.com/datasets/airbnb/seattle)
