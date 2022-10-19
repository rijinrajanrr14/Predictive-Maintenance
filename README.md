# Predictive-Maintenance
Predictive maintenance techniques are designed to help determine the condition of in-service equipment in order to estimate when maintenance should be performed.This approach promises cost savings over routine or time-based preventive maintenance. Machine Learning models have been used to predict the maintenance condition of the machines.
Maintenance is an important process from an industrial point of view. The emerging technological advancements such as Internet of Things (IoT) ,Industry 4.0 and the wide use of sensors have led to a significant disruption of industries. In these contexts, predictive maintenance is increasingly gaining a crucial role in cost reduction and business performance improvement since it utilizes heterogeneous data sources for detecting abnormal behaviours of equipment (diagnosis), predicting future failure modes (prognosis) and supporting decisions ahead of time (proactive decision making). In order to decrease misclassification and boost prediction, this study introduces a straight forward ensemble model that integrates eight different machine learning models. This model has the benefit of being computationally inexpensive, and the performance of the model can be improved by choosing other base models.


## Dataset Description:
The dataset consist of 10,000 rows and 10 columns and the total number of elements present in the dataset is 1,40,000.As mentioned,there are 10 columns out of which one is the target column.Here the target column is Target which shows the machine failure. The Target column consist of two integer values 1 and 0 where 1 represents the failure and 0 stands for no failure.There are no missing values in the dataset. The dataset consist of the following columns:

UDI: Unique identifiers for different machines
Product ID: Shows the different product ID
Type:  Shows the different product types
Air temperature [K]:  Consist of the air temperature expressed in Kelvin
Process temperature [K]:  Provide details about the working temperature of the machine
Rotational speed [rpm]:  The rotational speed of the machine in RPM
Torque [Nm]:  Provides the values of the torque during machining
Tool wear [min]:  Shows the tool damage observed during machining operation
Target:  Show whether there is failure or not
Failure:  Type Give the details about the type of failure
