This project centers on the captivating field of wearable computing, specifically working with data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone. The main objective is to retrieve, process, and clean the data, culminating in the creation of a well-organized and coherent data set suitable for future analyses.

The source data set originates from the Human Activity Recognition Using Smartphones Data Set, wherein a diverse group of 30 volunteers, aged 19-48, performed six activities while wearing the smartphone on their waist. The smartphone's embedded accelerometer and gyroscope captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The data was manually labeled through video recordings.

To construct the final data set, the training and test data were merged, and measurements related to mean and standard deviation were extracted. Descriptive activity names were used to label the data set, and the variables were appropriately named to enhance clarity.

Furthermore, a second, independent tidy data set was generated, summarizing the average of each variable for every activity and subject. The entire process was carried out using the R script "run_analysis.R," and the resultant tidy_data.txt file represents the culmination of this effort.
