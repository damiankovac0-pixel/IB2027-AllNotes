# A4 Machine Learning Topic Question Answers

These are concise examiner-style model answers for the questions in [[Topic Review Questions]]. They are written to show the kind of points needed for full credit, not as long textbook explanations.

## Topic Review

### 1. Guiding Question [6 marks]

Machine learning models should use suitable learning approaches for the problem, such as supervised learning for labelled prediction tasks, unsupervised learning for finding patterns in unlabelled data, and reinforcement learning where an agent learns from rewards and penalties. Accurate results depend on high-quality data, so data should be cleaned, missing values and outliers handled, duplicates removed, and features selected carefully. Data should also be normalized or standardized where scale affects the algorithm, such as KNN or neural networks. Models should be evaluated using appropriate metrics, not just accuracy, especially where false positives or false negatives have different costs. Ethical accuracy also requires representative data to reduce bias, transparency where decisions affect people, privacy protection, and human accountability. Models should be monitored after deployment because data, society, and technology can change over time.

## Exam-Style Questions

### 2a. Deep Learning [2 marks]

Deep learning uses neural networks with many layers to learn complex patterns from large data sets. It is especially effective for unstructured data such as images, speech, and natural language, but usually needs significant processing power and training data.

### 2b. Reinforcement Learning [2 marks]

Reinforcement learning involves an agent interacting with an environment and learning through rewards and penalties. It is used when the system must learn a sequence of actions, such as navigation, game playing, or robot control.

### 2c. Supervised Learning [2 marks]

Supervised learning trains a model using labelled data where the correct output is known. It is used for prediction tasks such as classification and regression.

### 2d. Transfer Learning [2 marks]

Transfer learning reuses a model trained on one task as a starting point for a related task. It reduces training time and data requirements, especially when labelled data is limited.

### 2e. Unsupervised Learning [2 marks]

Unsupervised learning uses unlabelled data to discover hidden patterns or structures. Examples include clustering customers into groups or finding associations between products.

### 3a. Deep Learning Application [2 marks]

Deep learning is used in medical image analysis, where convolutional neural networks can detect patterns in X-rays, CT scans, or MRI images. The model can support diagnosis by identifying possible tumours, fractures, or disease indicators.

### 3b. Reinforcement Learning Application [2 marks]

Reinforcement learning can be used in robotics navigation. A robot receives rewards for moving toward a target or avoiding obstacles and penalties for collisions or inefficient movement.

### 3c. Supervised Learning Application [2 marks]

Supervised learning can be used for spam email classification. The model is trained on emails labelled as spam or not spam, then predicts the class of new emails.

### 3d. Transfer Learning Application [2 marks]

Transfer learning can be used in medical imaging by adapting a pre-trained image recognition model to detect a specific disease. This is useful when the hospital has limited labelled medical images.

### 3e. Unsupervised Learning Application [2 marks]

Unsupervised learning can be used for customer segmentation. Clustering algorithms group customers with similar purchasing behaviour without needing predefined labels.

### 4a. Principle Of Reinforcement Learning [4 marks]

Reinforcement learning involves an agent that takes actions within an environment. After each action, the agent receives feedback through rewards or penalties. Over time, the agent learns a policy that chooses actions likely to maximize cumulative reward. It is suitable for problems where the best action depends on trial, error, and long-term consequences.

### 4b. Reinforcement Learning In Robotics Navigation [3 marks]

In robotic navigation, the robot acts as the agent and the physical or simulated space is the environment. It receives rewards for reaching goals, following efficient paths, or avoiding obstacles, and penalties for collisions or unsafe actions. Through repeated attempts, it learns navigation strategies that improve movement and decision-making.

### 5a. Hardware During Development And Testing [2 marks]

Development and testing require enough CPU, RAM, and storage to prepare data, run experiments, and evaluate models. GPUs may be needed for neural networks or large data sets because they speed up parallel calculations.

### 5b. Hardware During Large-Scale Deployment [2 marks]

Large-scale deployment requires scalable servers or cloud infrastructure to handle many users and high data volumes. It may also require GPUs, high memory, fast storage, and reliable networking for low-latency predictions.

### 5c. Hardware During Edge Computing [3 marks]

Edge computing runs models close to the data source, such as on phones, sensors, or vehicles. Hardware must be energy-efficient, compact, and fast enough for local inference. Models may need to be optimized because edge devices have limited processing power, memory, and battery life.

### 6a. Supervised Learning In Medical Imaging [3 marks]

Supervised learning uses labelled medical images where experts have identified conditions such as tumours or fractures. The model learns to associate image features with diagnostic labels. It can then classify new images, supporting doctors by highlighting likely abnormalities.

### 6b. Deep Learning In Medical Imaging [3 marks]

Deep learning, especially CNNs, can learn complex visual features directly from medical scans. Lower layers may detect edges or textures, while deeper layers detect more complex disease patterns. This makes it effective for image-based diagnosis, but it needs large, high-quality data sets and careful validation.

### 6c. Transfer Learning In Medical Imaging [3 marks]

Transfer learning can adapt a model pre-trained on a large image data set to a medical imaging task. The earlier layers already detect useful visual features, so less medical training data may be needed. This can improve training efficiency while still requiring expert-labelled medical images for fine-tuning and validation.

## End-Of-Topic Questions

### 7. Significance Of Data Cleaning [4 marks]

Data cleaning prepares raw data so the model learns from reliable information. It removes or corrects missing, duplicated, inconsistent, or incorrect values. Clean data improves accuracy and generalization because the model is less likely to learn noise or errors. It also supports fairness because biased or incomplete data can lead to unfair predictions.

### 8a. Handling Outliers [3 marks]

Outliers can be detected using statistical methods such as range checks, z-scores, or boxplots. They may be removed if they are errors, capped if extreme but valid, or kept if they represent important real cases. The decision should depend on the context because removing valid rare cases can bias the model.

### 8b. Removing Duplicate Data [3 marks]

Duplicate records should be identified by comparing key fields or exact repeated rows. They can be removed so the same case does not influence the model more than once. This improves data quality and prevents biased training caused by repeated examples.

### 8c. Missing Data [3 marks]

Missing data can be handled by deleting records if few values are missing, imputing values using mean, median, mode, or prediction, or marking missingness as a separate category. The method should match the data type and avoid introducing bias.

### 9. Normalization And Standardization [4 marks]

Normalization and standardization scale numerical data so features are comparable. This is important for algorithms based on distance or gradient calculations, such as KNN and neural networks. Normalization often rescales values to a fixed range, while standardization centers values around a mean with standard deviation. Scaling prevents large-range features from dominating smaller-range but important features.

### 10a. Role Of Feature Selection [2 marks]

Feature selection chooses the most relevant input variables for the model. It can improve accuracy, reduce overfitting, speed up training, and make the model easier to interpret.

### 10b. Feature Selection Strategies [6 marks]

Filter methods select features using statistical measures before training, such as correlation with the target. Wrapper methods test different feature subsets by training and evaluating models, which can be accurate but computationally expensive. Embedded methods perform feature selection as part of model training, such as decision trees ranking feature importance. All three aim to remove irrelevant or redundant features while keeping useful predictors.

### 11a. Dimensionality Reduction [1 mark]

Dimensionality reduction reduces the number of input features while preserving as much useful information as possible.

### 11b. Importance Of Dimensionality Reduction [4 marks]

Dimensionality reduction can reduce training time and memory use. It helps address the curse of dimensionality, where many features make patterns harder to learn. It can reduce noise and overfitting by removing irrelevant variation. It can also make data easier to visualize and interpret.

### 12. Linear Regression For Continuous Outcomes [5 marks]

Linear regression predicts a continuous numerical value by modelling a linear relationship between independent variables and a dependent variable. The model learns a line or linear equation from training data. The slope shows how much the prediction changes when an input changes, while the intercept is the predicted value when inputs are zero. After training, the model uses the equation to estimate new outcomes. It is suitable when the relationship is approximately linear.

### 13. Slope And Intercept [4 marks]

The slope shows the rate of change between an independent variable and the predicted outcome. A positive slope means the prediction increases as the input increases, while a negative slope means it decreases. The intercept is the predicted value when the independent variable is zero. Together, slope and intercept define the regression line used for prediction.

### 14. Assessing Regression Fit With R Squared [6 marks]

R squared measures how much of the variation in the dependent variable is explained by the regression model. A value closer to 1 indicates a better fit, while a value near 0 means the model explains little variation. However, a high R squared does not prove causation or guarantee good predictions on unseen data. Residuals should also be checked to see whether errors are randomly distributed. Other metrics such as mean squared error can show the size of prediction errors. The model should be tested on unseen data to check generalization.

### 15. Linear Regression Compared With Another Continuous Model [5 marks]

Linear regression is simple, interpretable, and works well when the relationship between inputs and output is approximately linear. A neural network regression model can model more complex non-linear relationships. However, neural networks usually need more data, more computation, and are harder to interpret. Linear regression is better when transparency and simplicity matter, while neural networks may be better for complex patterns. Both should be evaluated on unseen data using suitable error metrics.

### 16. Linear Regression For House Prices By Floor Area [5 marks]

Linear regression can be useful because house price often increases as floor area increases, giving a simple and interpretable model. The slope can estimate how much price changes per unit of area. However, floor area alone may not explain price accurately because location, condition, age, and number of rooms also matter. Outliers such as luxury homes may distort the line. It is appropriate as a simple baseline model but should be evaluated and possibly extended with more features.

### 17. Ethical Implications Of ML [6 marks]

Machine learning can improve decisions and efficiency in areas such as healthcare, education, and transport. However, biased data can produce unfair outcomes for underrepresented groups. Privacy is a concern because models often use large amounts of personal data. Lack of transparency can make it hard for people to understand or appeal decisions. Accountability must be clear when a model causes harm. Ethical use requires representative data, testing for bias, privacy safeguards, explainability where possible, and human oversight.

### 18. Biases In Training Data [5 marks]

Bias in training data can cause the model to learn unfair or inaccurate patterns. If some groups are underrepresented, predictions may be less accurate for them. Historical bias can reproduce past discrimination, such as in recruitment or policing. Bias may be hidden in proxy features, such as postcode representing income or ethnicity. Bias should be reduced through representative data collection, preprocessing checks, fairness testing, and ongoing monitoring.

### 19. ML In Online Communication [4 marks]

Machine learning in online communication can moderate harmful content and recommend relevant information. Ethical concerns include censorship or unfair removal of legitimate speech through false positives. Biased moderation models may affect some languages, dialects, or groups more than others. Personalization can also create filter bubbles or amplify misinformation. Privacy is also a concern when user content is analysed.

### 20. Reassessing Ethical Guidelines [5 marks]

Ethical guidelines must be reassessed because technology, data use, and social expectations change. New systems such as pervasive AI or AR may create risks not covered by older rules. Models can behave differently after deployment as data changes. Regular reassessment helps detect bias, privacy risks, and unintended harms. It also supports accountability and keeps systems aligned with law, public trust, and human values.

### 21. Emerging Technologies And Society [6 marks]

Quantum computing could improve optimization and simulation but may threaten current encryption methods. Augmented and virtual reality can improve education, training, and collaboration but may create privacy, addiction, or access concerns. Pervasive AI can make services more efficient and personalized, but also increases surveillance, bias, and dependency on automated decisions. These technologies may create economic benefits while disrupting jobs and widening digital divides. Positive impact depends on regulation, accessibility, security, transparency, and ethical design. Society must balance innovation with rights, safety, and fairness.

### 22. Jefferson High Education ML Ethics [4 marks]

An education ML system must avoid bias against students from particular backgrounds or learning styles. Data privacy is important because academic, behavioural, or personal student data is sensitive. The system should be transparent enough for teachers, students, and parents to understand how recommendations or decisions are made. Human oversight is needed so the model supports educators rather than unfairly labelling or limiting students.

## A4.3 Machine Learning Approaches Practice Questions

### 1a. Linear Regression Assumption

It assumes an approximately linear relationship between the independent variables and the dependent variable, so changes in inputs such as income or visit frequency lead to proportional changes in predicted customer spending.

### 1b. Outliers In Linear Regression

Outliers can pull the regression line away from the main pattern, causing inaccurate slopes and poor predictions. They may increase error and reduce the model's ability to generalize.

### 1c. Evaluating Linear Regression Accuracy

Use a test data set and calculate a metric such as mean squared error or R squared. This shows how close predictions are to actual spending on unseen data.

### 2a. Multicollinearity Problem

Multicollinearity occurs when independent variables are strongly related to each other. In property-price prediction, this makes it difficult to identify each feature's individual effect, making coefficients unstable and interpretation unreliable.

### 2b. Handling Multicollinearity

Remove one of the highly correlated features or combine related features. Correlation analysis can identify variables that provide repeated information.

### 3a. Importance Of Linearity

Linearity is important because linear regression models predictions as a straight-line relationship. If student success depends on non-linear patterns, the model may underfit and make inaccurate predictions.

### 3b. Predictive Accuracy Technique

Use cross-validation to test the model on different splits of the data. This checks whether the model generalizes rather than only performing well on one training-test split.

### 4a. Decision Tree Advantage

Decision trees are easy to interpret because they show a sequence of feature-based decisions. This is useful in heart disease risk because doctors can understand why a classification was made.

### 4b. Decision Tree Disadvantage

Decision trees can overfit if they become too deep, learning noise in the training data rather than general patterns. This may reduce accuracy on new patients.

### 4c i. Decision Tree Parameter

Maximum tree depth.

### 4c ii. Role Of Maximum Depth

Maximum depth limits how many levels of decisions the tree can make. A lower depth can reduce overfitting, while a very high depth may fit training data too closely.

### 5a. Choice Of k In KNN

A small k is sensitive to noise and may overfit individual unusual reviews. A large k smooths predictions but may ignore local patterns and underfit.

### 5b. Finding Optimal k

Test different k values using validation data or cross-validation. Choose the k that gives the best performance on unseen data.

### 5c. Feature Scales In KNN

KNN uses distance, so features with larger numerical ranges can dominate the distance calculation. Normalization or standardization is needed so all features contribute fairly.

### 6a. Decision Trees Over KNN

Decision trees are more interpretable, so teachers can see why students are placed into groups. They are also faster for prediction once trained and less sensitive to feature scaling.

### 6b. KNN Over Decision Trees

KNN can be useful if similar students should be grouped based on closeness across features. It makes fewer assumptions about decision boundaries and can adapt naturally to local patterns.

### 6c. Preventing Decision Tree Overfitting

Limit the maximum depth or prune the tree. This prevents the model from creating overly specific rules that only fit the training data.

### 7a. Precision And Recall

Precision is the proportion of predicted equipment failures that are actually failures. Recall is the proportion of actual failures that the model successfully detects.

### 7b. F1 Score vs Accuracy

If false negatives are costly, accuracy can be misleading because the model may appear accurate while missing important failures. F1 combines precision and recall, so it better reflects performance when both missed failures and false alarms matter.

### 7c. Confusion Matrix

A confusion matrix shows true positives, false positives, true negatives, and false negatives. It visually shows where the model is correct and what types of errors it makes.

### 8a. High Recall In Medical Classification

High recall is important because missing a real disease case can be dangerous. It ensures most patients who actually have the condition are flagged for further investigation.

### 8b. Imbalanced Data Effects

An imbalanced data set can make the model favour the majority class. It may achieve high accuracy while having poor recall for the minority class, such as rare disease cases.

### 8c i. Threshold Adjustment Method

Lower the classification threshold for predicting the positive class.

### 8c ii. Threshold Impact On F1

Lowering the threshold usually increases recall but may reduce precision by creating more false positives. The F1 score improves only if the balance between precision and recall becomes better.

### 9a. Objective Of k-Means

k-means aims to divide data into k clusters so points within each cluster are similar and close to their cluster centroid.

### 9b. k-Means Challenge

Choosing the correct number of clusters is difficult. Poor choice of k can produce misleading customer segments.

### 9c. Choice Of k In k-Means

A small k may merge different customer groups, losing detail. A large k may split meaningful groups into too many small segments.

### 10a. k-Means vs Spectral Clustering

k-means works best with roughly spherical clusters because it uses distance to centroids. Spectral clustering can handle non-spherical clusters by using relationships or similarities between data points.

### 10b. Spectral Clustering Challenge

Spectral clustering can be computationally expensive for large data sets because it requires constructing and processing similarity information between data points.

### 10c. Spectral Clustering And Satisfaction

It can identify more accurate customer groups when behaviour patterns are complex. Better segmentation allows more relevant recommendations or services, improving customer satisfaction.

### 11a. Social Groups In A Network

Spectral clustering.

### 11b. Challenge With Diverse User Data

Different types of user data may have different scales, formats, or relevance. Combining them poorly can create misleading clusters.

### 11c. Number Of Clusters

Too few clusters may combine distinct social groups, while too many may fragment real communities. The chosen number affects interpretation and usefulness.

### 12a. Traffic Sensor Clustering

DBSCAN is suitable because it can find clusters of varying shapes and identify noise or outliers. This helps with traffic sensor data where congestion patterns may be irregular and densities vary by area.

### 12b. Benefit Of Traffic Clusters

Traffic clusters can reveal congestion hotspots and recurring movement patterns. Planners can use this to improve signal timing, route planning, public transport, and infrastructure investment.

### 13a. Lift

Lift measures how much more often two items occur together than expected if they were independent. A lift greater than 1 indicates a meaningful positive association useful for marketing.

### 13b. Support And Confidence

Minimum support controls how frequently an itemset must appear to be considered. Minimum confidence controls how reliable a rule must be. Higher thresholds produce fewer but stronger rules; lower thresholds produce more rules, including weaker or less useful ones.

### 13c. Buying Patterns And Marketing

Buying patterns can support targeted promotions, product placement, bundles, and recommendations. For example, products often bought together can be advertised together to increase sales.

### 14a. Confidence And Support

Support is how often a borrowing pattern appears in all transactions. Confidence is the probability that a second book is borrowed when a first book has been borrowed.

### 14b. Discovering Borrowing Patterns

The library can apply association rule mining to borrowing records to find books or genres frequently borrowed together. These rules can support recommendations or shelf organization.

### 14c. Limitation Of Association Rules

Association rules show correlation, not causation. A pattern may not explain why books are borrowed together and may become outdated as user interests change.

### 15a. Crossover In Genetic Algorithms

Crossover combines parts of two parent solutions to create offspring. It allows useful traits from different solutions to be inherited in the next generation.

### 15b. Mutation In Genetic Algorithms

Mutation randomly changes part of a solution. It introduces variation and helps the algorithm avoid becoming stuck in a local optimum.

### 15c. Genetic Algorithm Advantage

Genetic algorithms can search large and complex solution spaces where testing every possible design is impractical, such as optimizing vehicle shape, weight, and performance.

### 16a. Selection In Timetabling

Selection chooses better timetable solutions, usually those with higher fitness, to become parents for the next generation.

### 16b. Fitness Function

A fitness function scores how good a timetable is. For course scheduling, it may reward satisfying student preferences and penalize clashes, unavailable rooms, or overloaded teachers.

### 16c. Population Size

A larger population increases diversity and may find better solutions but requires more processing. A smaller population is faster but may converge too early on poor solutions.

### 16d. Timetable GA Benefits

Genetic algorithms can handle many constraints and search many possible timetables efficiently. They can also find good approximate solutions when an exact solution is too difficult.

### 16e. Timetable GA Drawbacks

They may require many generations and significant processing time. They also do not guarantee the absolute best solution and depend heavily on the fitness function and parameters.

### 17a. Neural Network Layer

A hidden layer processes weighted inputs and applies activation functions to learn internal patterns in the data.

### 17b. Neural Network Overfitting

Neural networks can have many parameters, so they may memorize training data instead of learning general patterns. This leads to poor performance on new loan applicants.

### 17c. Training To Minimize Error

The network predicts loan default risk, compares predictions with actual outcomes using a loss function, and adjusts weights through backpropagation and optimization. Repeated training reduces prediction error over many examples.

### 18a i. Electricity Demand Type

Regression.

### 18a ii. Significance Of Regression Choice

Electricity demand is a continuous numerical value, so the output layer should produce a number rather than a class label. Evaluation should use regression metrics such as error size.

### 18b. Activation Function

ReLU is an activation function often used in hidden layers. It introduces non-linearity and helps neural networks learn complex patterns.

### 18c. Output Activation

A linear activation is most suitable for the output layer because electricity demand is a continuous value and predictions should not be restricted to categories.

### 18d. Deep vs Shallow Networks

Deep networks can learn layered, complex relationships between factors such as time, weather, season, and human behaviour. This can improve forecasting where simple relationships are insufficient.

### 18e. Backpropagation

Backpropagation calculates how much each weight contributed to prediction error and updates weights to reduce that error. It is the main learning process used to train neural networks.

### 18f. Deep Network Challenges

Deep networks require large data sets and significant processing power. They can also overfit, be difficult to interpret, and require careful tuning.

### 19a. Model Selection

Model selection is the process of choosing the most suitable machine learning model for a task based on performance, data type, interpretability, complexity, and constraints.

### 19b. Metrics For User Engagement

Accuracy and F1 score, if predicting engagement categories; or mean squared error and R squared, if predicting a continuous engagement value.

### 19c i. Cross-Validation

Cross-validation splits data into several folds and trains/tests the model multiple times on different folds to estimate general performance.

### 19c ii. Importance Of Cross-Validation

It reduces dependence on one train-test split and gives a more reliable estimate of how well the model will perform on unseen data.

### 20a. Overfitting In Basketball Prediction

Overfitting occurs when a model learns specific patterns or noise from past basketball games rather than general factors affecting outcomes. It may perform well on training data but poorly on future games.

### 20b. Model Selection Factors

Consider predictive performance on unseen data, interpretability, computational cost, data size/quality, risk of overfitting, and suitability for regression or classification.

## A4.4 Ethical Considerations Practice Questions

### 1a. Facial Recognition Ethical Implications

Facial recognition in public spaces can reduce privacy because people may be identified without consent. It can enable mass surveillance and chilling effects on behaviour. It may also produce biased or inaccurate matches, leading to unfair treatment or false suspicion.

### 1b i. Facial Recognition Biases

Possible biases include lower accuracy for certain ethnic groups and lower accuracy for particular age or gender groups.

### 1b ii. Societal Impacts

Ethnic bias could lead to disproportionate false identification and policing of minority groups. Age or gender bias could cause unequal access or unfair suspicion for groups the system handles poorly.

### 1c. Measures For Facial Recognition Concerns

Use representative training data and test accuracy separately across demographic groups. Limit use through clear regulation, consent requirements, audits, and human review before serious decisions.

### 2a. Personalized Newsfeed Bias Issues

Algorithmic bias may amplify certain viewpoints and create filter bubbles. It may also unfairly promote or suppress content from particular groups, affecting public opinion and access to information.

### 2b. Ethical Personalization Strategies

Regularly audit recommendations for bias and misinformation. Give users transparency and control, such as explanation tools or options to adjust personalization settings.

### 2c i. Lack Of Transparency Implications

Users may not understand why they see certain content or why decisions are made about them. It also becomes harder to detect bias, manipulation, or accountability failures.

### 2c ii. Improving Transparency

Provide explanations for recommendations and publish clear information about major factors used by the algorithm. Independent audits can also check fairness and behaviour.

### 3a. AI Admissions Ethical Concerns

AI admissions may reproduce historical bias from past admissions data. Lack of transparency may make decisions hard to appeal. Over-reliance on automation could reduce human judgement of individual circumstances.

### 3b i. Admissions Biases

Bias may arise from socioeconomic background and school type, or from historical patterns favouring particular demographics.

### 3b ii. Impact On Students

Qualified students from underrepresented groups may be unfairly rejected. Students may also lose trust in the process if decisions cannot be explained or challenged.

### 3c. Measures For Admissions Ethics

Use representative data, remove or monitor proxy features, and test outcomes across groups. Provide human review, clear appeal processes, and transparent explanations of factors used.

## Case Study Questions

### 1 Health Monitoring App

#### 1a i. AI Or ML [1 mark]

Machine learning.

#### 1a ii. Reason [2 marks]

It learns patterns from health and lifestyle data to make predictions rather than only following fixed programmed rules.

#### 1b. GPUs In Mobile Deployment [2 marks]

GPUs or specialized mobile accelerators may be needed if the app runs complex models locally. They can speed up inference, but power and heat limits mean the model may need optimization.

#### 1c. Missing Lifestyle Data [2 marks]

Missing lifestyle data can reduce prediction accuracy or bias results if certain users have incomplete records. Cleaning may involve imputation, removing unusable records, or marking missing values consistently.

#### 1d. Feature Selection [2 marks]

Feature selection removes irrelevant health or lifestyle variables and keeps those most related to risk. This can improve accuracy, reduce overfitting, and make the model faster on mobile devices.

#### 1e. Suitable Algorithm [4 marks]

A classification algorithm is suitable because the task predicts a health category or risk class. A decision tree could be used because it is interpretable and can show which factors led to a risk classification. KNN could also classify based on similar patients, but it may be slower and sensitive to scaling. In a health context, interpretability and validation are important, so the chosen classifier must be tested carefully.

#### 1f. High k In KNN [2 marks]

A high k smooths predictions and reduces sensitivity to noise. However, it may ignore local patient differences and underfit, giving less personalized health predictions.

#### 1g. Privacy And Security Concerns [3 marks]

Health data is sensitive and could harm users if leaked. Users may not fully understand how their data is collected or shared. Unauthorized access or weak security could expose medical or lifestyle information.

#### 1h. Reducing Bias [2 marks]

Collect more representative data from underrepresented groups. Test model performance separately across demographic groups and adjust preprocessing or weighting if accuracy differs unfairly.

### 2 Autonomous Public Transport System

#### 2a i. Edge Computing [1 mark]

Edge computing processes data close to where it is generated rather than sending everything to a central server.

#### 2a ii. Relevance [2 marks]

Autonomous vehicles need fast decisions from sensor data. Edge processing reduces latency and allows the vehicle to react locally even if network connection is unreliable.

#### 2b. Deep Learning Effectiveness [2 marks]

Deep learning is likely more effective for complex environmental data such as images, traffic, weather, and sensor patterns. It can learn complex features, but requires more data and processing power.

#### 2c. Normalization [2 marks]

Normalization puts varied data types such as weather values and traffic density onto comparable scales. This prevents large-range features from dominating model learning.

#### 2d i. Data Quality Issue [1 mark]

Missing or noisy sensor readings.

#### 2d ii. Preprocessing Step [2 marks]

Missing readings can be imputed using nearby time values or sensor averages. Noisy readings can be smoothed or filtered before being used by the model.

#### 2e. RL For Bus Routes [2 marks]

Reinforcement learning can treat route choices as actions and use rewards such as reduced delay, fuel efficiency, or passenger waiting time. Over time, it learns route strategies that improve service.

#### 2f. Transfer Learning From Cities [2 marks]

Models trained on traffic patterns in other cities could provide a starting point. They must be fine-tuned with local data because roads, demand, and behaviour differ.

#### 2g. Surveillance Data Ethics [2 marks]

Surveillance data raises privacy and consent concerns because passengers or pedestrians may be tracked. Data should be anonymized, minimized, secured, and used only for a clear purpose.

#### 2h. Societal Impacts [2 marks]

Autonomous buses may improve safety, efficiency, and accessibility. However, they may reduce driving jobs and create public trust or accountability concerns after accidents.

### 3 AI-Powered Recruitment Tool

#### 3a. Classification Or Regression [2 marks]

It is classification if it predicts categories such as shortlisted/not shortlisted or suitable/not suitable. It is not regression unless it predicts a continuous numerical score.

#### 3b. Speed And Memory [2 marks]

Global deployment requires fast processing for many applicants and enough memory to handle large data sets or models. If requirements are too high, the system may be expensive or slow to scale.

#### 3c i. Training Bias [1 mark]

Historical hiring bias.

#### 3c ii. Bias Mitigation [2 marks]

Review and balance the training data, and remove or monitor biased proxy features. Test outcomes across demographic groups before deployment.

#### 3d. Feature Selection [2 marks]

Feature selection keeps job-relevant predictors and removes irrelevant or biased variables. This can improve accuracy and reduce unfair decisions based on unrelated factors.

#### 3e. Decision Tree Over Regression [3 marks]

A decision tree is suitable because recruitment screening is often a classification task. It can handle categorical and numerical features and produce interpretable decision paths. Regression is less suitable if the output is a category rather than a continuous value.

#### 3f. Ethical Concerns [2 marks]

The system may reproduce discrimination from historical data. It may also lack transparency, making it difficult for applicants to understand or challenge decisions.

#### 3g. Transparency And Accountability [2 marks]

Provide explanations of key factors influencing decisions and allow human review or appeal. Regular audits should check fairness and document responsibility for outcomes.

### 4 Retail Customer Segmentation

#### 4a. Supervised Or Unsupervised [4 marks]

Unsupervised learning is more appropriate when the retailer does not already know customer groups. Clustering can discover segments from purchasing behaviour without labels. Supervised learning would be more suitable only if existing labelled customer categories were available. Therefore, unsupervised clustering is usually best for exploratory segmentation.

#### 4b. Cloud Benefits [2 marks]

Cloud computing provides scalable storage and processing for large customer data sets. It can be more flexible than buying and maintaining in-house servers.

#### 4c. Outlier Detection [2 marks]

Outlier detection identifies unusual customers or transactions that may distort clusters. These may be removed, analysed separately, or checked for fraud or data errors.

#### 4d i. Suitable Algorithm [1 mark]

k-means, if dimensionality has been reduced and clusters are expected to be compact.

#### 4d ii. Reason [2 marks]

k-means is efficient and scalable for large data sets. However, preprocessing and careful choice of k are needed, especially with high-dimensional data.

#### 4e. Privacy Issues [3 marks]

Detailed segmentation can reveal sensitive habits, income level, health interests, or personal circumstances. Customers may not expect their purchases to be profiled so deeply. Data should be anonymized, secured, and used with clear consent and purpose limits.

#### 4f. Reducing Discriminatory Marketing [2 marks]

Audit segments for unfair outcomes and remove or adjust biased features. Use representative data and human review for campaigns that could exclude or exploit vulnerable groups.

### 5 Natural-Disaster Prediction And Management

#### 5a. Neural Networks [2 marks]

Neural networks can learn patterns from satellite images, weather data, seismic readings, river levels, and sensor data. They can predict risk levels or classify warning situations.

#### 5b. Real-Time Processing [2 marks]

Real-time data requires fast processing, reliable networks, and scalable infrastructure. Low latency is important because delayed predictions may reduce warning time.

#### 5c. Integration And Cleaning Challenges [2 marks]

Data sources may have different formats, resolutions, time intervals, and missing values. Cleaning must align formats, remove errors, and synchronize data before modelling.

#### 5d. Data Augmentation [2 marks]

Data augmentation creates additional training examples from limited historical data, such as modified images or simulated scenarios. This can improve generalization where disasters are rare.

#### 5e. Deep Learning Use [2 marks]

Deep learning can capture complex non-linear patterns in images and sensor streams better than simple models. It is useful when disaster signals depend on many interacting features.

#### 5f. Adapting To New Data [2 marks]

Models can be retrained or fine-tuned with new labelled disaster data. Continuous monitoring can detect when performance drops and update the model.

#### 5g. False Positives And Negatives [3 marks]

False positives may cause unnecessary panic, evacuation costs, and loss of trust. False negatives are more dangerous because people may not be warned before a disaster. Ethical design should consider the cost of each error and favour safety where lives are at risk.

#### 5h. Data Governance [2 marks]

Sensitive geographical or personal data should be encrypted, access-controlled, and used only for defined purposes. Governance should include anonymization, audit logs, retention limits, and compliance with relevant laws.

### 6 Automated Cyberbullying Detection System

#### 6a i. NLP [1 mark]

Natural language processing is the use of computing techniques to process and analyse human language.

#### 6a ii. NLP Relevance [2 marks]

Cyberbullying detection must analyse posts, messages, slang, and context. NLP helps identify harmful language, threats, insults, or abusive patterns.

#### 6b i. Computational Challenges [2 marks]

Large social-media platforms generate high volumes of text in real time. Processing this quickly requires efficient models, scalable infrastructure, and enough memory and processing power.

#### 6b ii. Hardware Solutions [2 marks]

Use cloud servers, GPUs or AI accelerators for model inference, and distributed processing to handle scale. Edge or regional servers may reduce latency.

#### 6c. Text Preprocessing [2 marks]

Preprocessing may include tokenization, lowercasing, removing irrelevant symbols, handling emojis, correcting spelling, and converting text into numerical features. It should also handle slang and repeated characters.

#### 6d. Sarcasm And Ambiguity [2 marks]

Sarcasm and ambiguity affect meaning because harmful intent may not be clear from individual words. If ignored, the model may create false positives or miss genuine bullying.

#### 6e. Rule-Based vs ML Models [2 marks]

Rule-based systems use fixed keyword or pattern rules and are transparent but inflexible. Machine learning models can learn more complex patterns from data but may be less interpretable and require labelled examples.

#### 6f. False Positives And Negatives [3 marks]

False positives may unfairly censor users or punish harmless messages. False negatives allow harmful cyberbullying to continue and may endanger victims. Ethical use requires human review for serious actions, appeal processes, and careful threshold tuning.

#### 6g. Privacy Implications

Analysing social-media content can expose private conversations, opinions, and relationships. Users may not expect automated monitoring of their messages. The system should minimize data collection, protect stored data, anonymize where possible, and clearly state how content is analysed.
