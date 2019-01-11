# DSND_Blog_Post

## Data Science Nanodegree Blog Post README

### Dataset used
 * [Kaggle Google Play Dataset](https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore.csv)

### Schema of Dataset
 * App (String - Application Name)
 * Category (String - Category the app belongs to)
 * Rating (Integer - Overall user rating of the app)
 * Reviews (Integer - Number of user reviews for the app)
 * Size (String - Size of the app)
 * Installs (String - Number of user downloads/installs for the app)
 * Type (String - Paid or Free)
 * Price (String - Price of the App)
 * Content Rating (String - Age group the app is targeted at - Children/ Mature 21+/ Adult)
 * Genres (String - Multiple genres app belongs to apart from main category)
 * Last Updated (Date - Date app was last updated on Play Store)
 * Current Ver (String - Current version of the app available on the Play Store)
 * Android Ver (String - Min required Android version)

### Libraries Used
 * The typical libraries that are bundled with Anaconda Python
    * pandas
    * numpy
    * matplotlib
    * seaborn
    * string
    * re
    * warnings
         
### Motivation of Project
 * The motivation for studying this datatset was to create an analysis to help inform the decision points that app developers will encounter when choosing which business model to decide between and which category of apps to focus on the development of
 
### Files Available in Repository
 * Nanodegree Blog_files - Upload of images for .htm file references
 * Nanodegree Blog.htm - Blog post of Google Play Store dataset
 * Play Store App Data Discovery.html - .html version of Jupyter Notebook analysis
 * Play Store App Data Discovery.ipynb - Jupyter Notebook of Play Store App Analysis
 * README.md - This file
 * googleplaystore.csv - The dataset as taken from Kaggle
 
### Summary of Results

Analysed the following questions:
1. How do paid vs free apps differentiate in number of installs?
2. How do paid vs free apps differentiate in app rating?
3. How does the app category potentially impact the rating the app receives?

Conclusion of analysis:
The first two analyses suggest a very interesting dynamic for free vs paid apps in the app store for the number of installs and rating that the apps receive. The data shows that free apps have a significantly higher install base (and much higher variance) while paid apps remain relatively low.

Conversely, the opposite is true for ratings which demonstrate that paid apps have a higher rating on average to free apps! The difference is almost negligible at a mean of 4.18 for free apps and 4.26 for paid apps, but there does exist a higher sense of app satisfaction with paying directly for an app.

Leading on to the third analysis of app categories and their ratings suggests that for developers looking to create apps in less crowded (and higher rated) categories could potentially go down the avenue of creating apps for the events, education and art and design categories as these only account for ~2.5% of this dataset while having the highest average rating.

While it also showed that dating,tools, and maps and navigation apps should be avoided as this area is more crowded (~10% of this dataset) and lower rated on average within this sample.

### Acknowledgements
 * The following kernals on Kaggle were used for inspiration in the analysis:
    * Dataset taken from https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore.csv
    * https://www.kaggle.com/lava18/all-that-you-need-to-know-about-the-android-market
    * https://www.kaggle.com/tekdogan/visualizing-google-play-store-apps-via-seaborn
