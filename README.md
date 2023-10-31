# Insurance-Fraud-detection-with-Income-Prediction

Problem Description :

The goal of this Research project is to build a machine-learning model that can detect auto insurance fraud. The main challenge behind fraudulent claim detection in machine learning is
that fraud claims are more common as compared to legit insurance claims. Building a machine learning model that can detect fraudulent insurance claims is quite complex, given the variety
of fraud patterns and a relatively small number of known frauds in a given sample. Insurance frauds cover a range of illegal actions which customers might commit to achieving monetary
sums from insurance providers by staging the incident, falsely representing the situation, including the actors. Many of these cases go unnoticed by insurance companies. Most Companies
in the USA use prediction analytics for price prediction, but there are more ways in which machine learning can help. Our research will make use of machine learning algorithms and help detect insurance frauds
and predict the income of customers independently. Through extensive research, we have found that many people have worked on insurance fraud detection, but no one has used more than five
different machine learning models. Notably, we have found one more interesting thing is that no one has used different encoding techniques to convert the numerical variable into a categorical
variable. From the literature review, We can see that only Mr. Pinak Patel has tried to use one -hot-encoding and managed to obtain good performance from the machine learning model.
After extensive research, we have seen that other researchers have only worked on insurance fraud detection but we are providing more advantages to insurance companies by predicting
the income of customers. Income prediction in the insurance industry is still uncommon. There are several ways we could have proceeded with the research, such as a mathematical
model or traditional OLS model, but we have decided to opt for python programming for developing a machine learning model. We also could have made use of R programming language
but using python is efficient for us as there are already predefined libraries that might be useful for us. We have assessed several research papers mentioned above to get an idea about project
implementation and project flow.


6.1 Requirements:

In the given research, we have decided to use the python programming language. We have used
Jupyter notebook as a code editor but it can be executable in google collaboratory as well. We
will load the data, and then it will split into training and testing datasets. We will train the
model using the training dataset and the results will be obtained by the performance of the
testing dataset. The following requirements are valid for both insurance fraud detection and
income prediction.
The final requirements of the proposed system are as follows :
• Dataset must be read in a single CSV file and converted into a format that can be used
by machine learning libraries.
Page 16
Auto insurance Fraud detection & Income prediction Aston University / 210268199
• Removal of any feature from the dataset should not be a problem at any given time
• After Data processing, the environment must be able to use the available data to train
the model and test its performance of it.
• Each machine learning model must be tested independently.
• Accuracy score of each machine learning model should be considered as a primary performance
metric.



7.1 Insurance Fraud detection
7.1.1 Data Collection
We have downloaded our insurance fraud detection dataset from the Kaggle website. Kaggle is
an online community platform for data scientists and machine learning enthusiasts. We have
added all the information about the missing values and unknown values in the data preparation
part which will be helpful to know the nature of the dataset.
• months as customer: It denotes the number of months for which the customer is associated
with the insurance company.
• age: continuous. It denotes the age of the person.
• policy number: The policy number.
• policy bind date: Start date of the policy.
• policy state: The state where the policy is registered.
• policy csl : combined single limits. How much of the bodily injury will be covered from
the total damage.
• policy deductible: The amount paid out of pocket by the policyholder before an insurance
provider will pay any expenses.
• policy annual premium: The yearly premium for the policy.
• umbrella limit: An umbrella insurance policy is extra liability insurance coverage that
goes beyond the limits of the insured’s homeowners, auto, or watercraft insurance. It
provides an additional layer of security to those who are at risk of being sued for damages
to other people’s property or injuries caused to others in an accident.
• insured zip: The zip code where the policy is registered.
• insured sex: It denotes the person’s gender.
• insured education level: The highest educational qualification of the policyholder.
• insured occupation: The occupation of the policyholder.
• insured hobbies: The hobbies of the policyholder.
• insured relationship: Dependents on the policy-holder.
• capital gain: It denotes the monitory gains by the person.
• capital loss: It denotes the monitory loss by the person.
• incident date: The date when the incident happened.
• incident type: The type of the incident. collision type: The type of collision that took
place.
• incident severity: The severity of the incident.
• authorities contacted: Which authority was contacted.
• incident state: The state in which the incident took place.
• incident city: The city in which the incident took place.
• incident location: The street in which the incident took place.
• incident hour of the day: The time of the day when the incident took place.
• property damage: If any property damage was done.
• bodily injuries: Number of bodily injuries.
• Witnesses: Number of witnesses present.
• police report available: Is the police report available?
• total claim amount: Total amount claimed by the customer.
• injury claim: Amount claimed for injury
• property claim: Amount claimed for property damage.
• vehicle claim: Amount claimed for vehicle damage.
• auto make: The manufacturer of the vehicle
• auto model: The model of the vehicle.
• auto year: The year of manufacture of the vehicle.
Our Target Column is Fraud Reported
• Fraud reported: Fraud detected Y or N.


Income Prediction
Some of the stages of Insurance fraud prediction methodology are similar to Income prediction
because in terms of our research project, income prediction is also a classification problem.
Therefore we will be using same machine learning models which are used in insurance fraud
detection.
7.2.1 Data Collection :
We have Usedthe Kaggle website to download this dataset. This dataset contains 10 columns
and 9000 rows.
Information about the features of dataset :
• Work: Explains the type of work such as private, self-employed etc.
• Marital Status : Explains if customer’s marital status.
• Hours Week: Number of hours customers work per week
• Country: Country of Citizenship of Customer.
• Above 50K: If its salary above 50k or not.
• Education: Education level of Customer.
• Gender: Gender of Customer.
• Occupation: Occupation of Customer.
• Age: Explains the Age of Customer.

