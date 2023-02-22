# unsupervisedLearning_KPrototype_UfoSightings
Personal Unsupervised Learning Project (Python): extensive data cleaning (used encoders and KNN imputation), in-depth exploratory data analysis, and K-Prototype algorithm used

## Data Source 
National UFO Reporting Center: "Dedicated to the collection and dissemination of objective UFO data"
Anonymous sources can file UFO Sightings through an Online Report Form

## Data Limitations: 
The data source is varied, anonymous, and random. The data collection is not validated and does not have a consistent process.
Proceed anyways since this project is for fun!

## EDA Graphs:

### Total UFO Sightings in the USA Map Visualization:
<img width="806" alt="Screenshot 2023-02-22 at 4 47 27 PM" src="https://user-images.githubusercontent.com/105748980/220777709-f37519ff-b913-474b-ae83-f954e3dadcd5.png">

### Correlation Matrix:
<img width="507" alt="Screenshot 2023-02-22 at 4 50 09 PM" src="https://user-images.githubusercontent.com/105748980/220778165-0b42da52-c4eb-42cc-a48b-52805e71a71b.png">

### Numerical Variable Histogram:
<img width="502" alt="Screenshot 2023-02-22 at 4 44 30 PM" src="https://user-images.githubusercontent.com/105748980/220777235-fba114fc-da57-488b-bed3-c07a19352175.png">

### Number of UFO Sightings in Each Year Histogram:
<img width="477" alt="Screenshot 2023-02-22 at 4 45 09 PM" src="https://user-images.githubusercontent.com/105748980/220777328-4f103459-9a0e-4554-bf0c-f67f08309220.png">

### UFO Shape Frequency Bar Graph:
<img width="493" alt="Screenshot 2023-02-22 at 4 45 47 PM" src="https://user-images.githubusercontent.com/105748980/220777439-581ee129-c5f1-4531-baea-57455479afd8.png">

### UFO Sighting Duration Frequency BoxPlot:
<img width="465" alt="Screenshot 2023-02-22 at 4 45 59 PM" src="https://user-images.githubusercontent.com/105748980/220777476-3f351025-247c-4be1-9b76-5113caf012fa.png">

### UFO Sighting Country Frequency Bar Graph:
<img width="490" alt="Screenshot 2023-02-22 at 4 46 42 PM" src="https://user-images.githubusercontent.com/105748980/220777579-80099231-008f-4b67-a8f3-09fb05016064.png">

## K-Prototype (Unsupervised Algorithm) Use
For this dataset, I used K-Prototype, which is a clustering technique that combines K-Means and K-Mode. K-Prototype is suitable for mixed data (data with categorical and continuous variables), which is why I chose the algorithm.

## K-Prototype Results
After implementing K-Prototype, I found the above 2 clusters. There is something off with these clusters since the first segment has 113058 data points and the second only has 2.

The second segment was clustered separately probably due to the high duration of the points' UFO sightings. These are considered true outliers; they are extreme but represent the dataset.

## Explanation + Conclusion
A likely reason the clustering technique did not work is due to the high variation in the dataset and the lack of clear or true clustering patterns in the dataset. This is understandable as UFO sightings, in general, are not backed by any scientific research and are unnatural, random phenomenons. Furthermore, the data collection was done randomly and not validated and did not have a consistent process since they are sightings inputted by random people across the world.

For better clustering results, we need more consistent and validated data. However, that is difficult to achieve since no one knows when the UFOs will come. :)

<img width="390" alt="Screenshot 2023-02-22 at 4 48 47 PM" src="https://user-images.githubusercontent.com/105748980/220777927-ee7e15b2-a518-4145-af38-57bf3ff0897b.png">
