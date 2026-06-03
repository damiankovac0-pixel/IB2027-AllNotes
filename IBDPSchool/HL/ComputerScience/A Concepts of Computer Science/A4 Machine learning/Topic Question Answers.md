# A4 Machine Learning Topic Question Answers

This note marks the answers from `/Users/damiankovac/Downloads/answers.md` against the questions in [[Topic Review Questions]].

Marking note: questions with printed marks use those marks. The A4.3 practice questions do not show marks in the original question file, so their maximum marks are inferred from the command word and depth expected in IB-style answers.

## Overall Result

| Section | Mark |
| --- | --- |
| Topic Review, Exam-Style, and End-Of-Topic Questions | 86 / 134 |
| A4.3 Machine Learning Approaches Practice Questions | 101 / 147 |
| A4.4 Practice Questions | not answered |
| Case Study Questions | not answered |
| Total counted | 187 / 281 |

Percentage for counted answers: approximately 66.5%.

## Main Feedback

You often knew the correct topic and examples, especially for learning types, reinforcement learning, KNN/decision trees, clustering, genetic algorithms, and neural networks.

The main lost marks came from answers that were too brief, answers that listed ethical concerns without explaining impact, and some incorrect metric/model wording, especially regression accuracy, k in KNN vs k in k-means, and feature scaling.

For full IB marks, write in this pattern: definition, mechanism, consequence, and scenario-specific example.

## Topic Review

### 1. Guiding Question [6 marks]

Your answer: Use unbiased data, research the previous model when using transfer learning, protect privacy during collection/training/use, follow laws, consider environmental impact, take responsibility, and do not use stolen data.

Correct answer: Machine learning models should use suitable learning approaches for the problem, high-quality cleaned data, representative and unbiased training sets, careful preprocessing, feature selection, suitable evaluation metrics, and ethical safeguards. Ethical safeguards include privacy, consent, transparency, accountability, bias testing, legal compliance, and environmental awareness. Models should also be monitored after deployment because data and social conditions can change.

Mark: 4 / 6

Why: Strong ethics points, but accuracy principles were incomplete: preprocessing, evaluation metrics, validation, and model monitoring were missing.

## Exam-Style Questions

### 2a. Deep Learning [2 marks]

Your answer: Deep learning uses ANNs with multiple neurons, is suitable for large datasets and complex emerging patterns, is resource intensive, and often requires GPUs/TPUs and storage.

Correct answer: Deep learning uses multi-layer neural networks to learn complex patterns from large datasets. It is effective for images, speech, and natural language, but usually needs large data, high processing power, and specialized hardware.

Mark: 2 / 2

### 2b. Reinforcement Learning [2 marks]

Your answer: An agent navigates an environment, makes decisions to maximize cumulative rewards, uses exploration and exploitation, and is rewarded or punished according to training parameters.

Correct answer: Reinforcement learning trains an agent through interaction with an environment. The agent learns by receiving rewards or penalties and adjusts its behaviour to maximize cumulative reward.

Mark: 2 / 2

### 2c. Supervised Learning [2 marks]

Your answer: A model receives labelled training data as input-output pairs and learns patterns for future classification or regression tasks.

Correct answer: Supervised learning trains on labelled data where the correct output is known. It learns to predict outputs for new data, including classification and regression tasks.

Mark: 2 / 2

### 2d. Transfer Learning [2 marks]

Your answer: A previously trained general model is used as a base for a new specified model, reducing training time, monetary cost, resource cost, and improving performance.

Correct answer: Transfer learning reuses a model trained on one task as a starting point for a related task. It reduces data and training requirements and can improve performance when labelled data is limited.

Mark: 2 / 2

### 2e. Unsupervised Learning [2 marks]

Your answer: A model is fed unlabelled data and finds patterns or relationships by itself. It is useful when proper labels are unknown. You also said it determines future outputs as classification or regression.

Correct answer: Unsupervised learning uses unlabelled data to find hidden patterns, clusters, or associations. It is not mainly classification or regression because those are supervised learning tasks.

Mark: 1 / 2

Why: The first part was correct, but the classification/regression statement confused it with supervised learning.

### 3a. Deep Learning Application [2 marks]

Your answer: Object recognition using CNNs to detect and classify objects in images, given enough data and computation.

Correct answer: Deep learning can be used for object detection or medical image analysis. CNNs learn visual features from images and classify or detect objects, provided there is sufficient training data and computing power.

Mark: 2 / 2

### 3b. Reinforcement Learning Application [2 marks]

Your answer: A game-playing agent can navigate different scenarios, with goals and mistakes represented through rewards and punishments.

Correct answer: Reinforcement learning can be used for game-playing agents because the agent learns strategies by taking actions, receiving rewards or penalties, and improving over repeated attempts.

Mark: 2 / 2

### 3c. Supervised Learning Application [2 marks]

Your answer: Classifying emails as spam or not spam using emails labelled by appropriate personnel.

Correct answer: Supervised learning can classify spam emails by training on labelled examples of spam and non-spam messages, then predicting the label for new emails.

Mark: 2 / 2

### 3d. Transfer Learning Application [2 marks]

Your answer: A plant identification app uses a pre-trained object detection model to minimize training costs and specialize the model for plant identification.

Correct answer: Transfer learning can adapt a pre-trained image recognition model to classify plants, reducing training time and data requirements compared with training from scratch.

Mark: 2 / 2

### 3e. Unsupervised Learning Application [2 marks]

Your answer: Market basket analysis where the relationships are unknown and there is no clear labelled data.

Correct answer: Unsupervised learning can be used for market basket analysis or customer segmentation by finding associations or clusters in unlabelled purchasing data.

Mark: 2 / 2

### 4a. Principle Of Reinforcement Learning [4 marks]

Your answer: A model is rewarded or punished based on the agent's actions. The agent uses exploration and exploitation. Reward and punishment parameters are set, and the model tries to maximize cumulative reward and learn desired behaviour.

Correct answer: Reinforcement learning involves an agent interacting with an environment. The agent takes actions, receives rewards or penalties, and learns a policy that maximizes cumulative reward over time. Exploration tries new actions; exploitation uses known successful actions.

Mark: 4 / 4

### 4b. RL In Robotics Navigation [3 marks]

Your answer: A robot vacuum learns room layouts, which rooms have dirt, receives rewards for sucking up dirt, and penalties for aimless wandering or hitting walls.

Correct answer: In robotic navigation, the robot is the agent and the physical or simulated space is the environment. It is rewarded for reaching goals, cleaning efficiently, or avoiding obstacles, and penalized for collisions or inefficient movement. Through repeated trials it learns better navigation behaviour.

Mark: 3 / 3

### 5a. Hardware During Development And Testing [2 marks]

Your answer: It depends on the ML approach. Training may require discrete GPUs, TPU clusters, large storage, SSDs, fast internet for data collection, and large RAM.

Correct answer: Development and testing require enough CPU/GPU power, RAM, and storage to process data, train models, and run experiments. GPUs or TPUs may be needed for neural networks and large datasets.

Mark: 2 / 2

### 5b. Hardware During Large-Scale Deployment [2 marks]

Your answer: It should be optimized for edge devices or ASICs/FPGAs, requires less hardware than training, and models are optimized for deployment.

Correct answer: Large-scale deployment usually requires scalable servers or cloud infrastructure, reliable networking, fast inference, and enough processing and memory to serve many users. Specialized accelerators may be used depending on model complexity.

Mark: 1 / 2

Why: You described optimized inference, but focused too much on edge devices instead of large-scale server/cloud deployment.

### 5c. Hardware During Edge Computing [3 marks]

Your answer: Edge devices are small, need high speed, low latency and low power consumption, are heavily optimized, may include ASICs, and operate near the data source.

Correct answer: Edge computing uses local devices near the data source. Hardware must be small, energy-efficient, low-latency, and powerful enough for inference despite limited memory and battery. Models may need to be optimized or compressed.

Mark: 3 / 3

### 6a. Supervised Learning In Medical Imaging [3 marks]

Your answer: The model is given correctly labelled data by professionals, then given unlabelled data to label.

Correct answer: Supervised learning uses expert-labelled medical images, such as scans labelled as tumour/no tumour. The model learns patterns linking image features to diagnostic labels, then predicts labels for new images to support clinicians.

Mark: 2 / 3

Why: Correct core idea, but it needed more detail on medical images and diagnostic support.

### 6b. Deep Learning In Medical Imaging [3 marks]

Your answer: CNNs find complex emerging patterns that were previously unknown.

Correct answer: Deep learning, especially CNNs, can learn visual features from medical images. Lower layers detect simple features and deeper layers detect complex disease patterns. It can support diagnosis, but requires large, high-quality labelled datasets and careful validation.

Mark: 2 / 3

Why: CNN and complex patterns were correct, but the answer lacked layers, labelled scans, and validation.

### 6c. Transfer Learning In Medical Imaging [3 marks]

Your answer: A general object detection model is specialized to medical images in a specific field, leading to better results with less hardware/resource requirements and more accessibility.

Correct answer: Transfer learning adapts a model pre-trained on a large image dataset to a medical imaging task. It can reduce training data and resource requirements, but still needs fine-tuning and validation on expert-labelled medical images.

Mark: 2 / 3

Why: Correct idea, but overstated correctness and missed fine-tuning/validation.

## End-Of-Topic Questions

### 7. Data Cleaning [4 marks]

Your answer: Garbage in, garbage out; it reduces bias and improves correctness; a good algorithm trained on bad data produces a bad model; consolidates data.

Correct answer: Data cleaning removes or fixes missing, duplicated, inconsistent, incorrect, or biased data. It improves accuracy, generalization, and fairness because models learn from the data provided. Poor data can cause poor predictions even with a good algorithm.

Mark: 3 / 4

### 8a. Handling Outliers [3 marks]

Your answer: Fixes outliers by trimming, capping, or transforming.

Correct answer: Outliers should first be detected using statistical checks or visual methods. They can be removed if they are errors, capped if extreme but valid, transformed, or kept if they represent meaningful rare cases. The choice depends on context.

Mark: 2 / 3

### 8b. Removing Duplicate Data [3 marks]

Your answer: Remove or merge duplicate entries, or manually review them.

Correct answer: Duplicate records are identified by matching key fields or repeated rows. They can be removed, merged, or manually reviewed when duplicates contain conflicting information. This prevents repeated records from biasing training.

Mark: 2 / 3

### 8c. Missing Data [3 marks]

Your answer: Ignore the whole entry or enter null, mean, or median values.

Correct answer: Missing data can be handled by deleting affected records, imputing values using mean/median/mode or a predictive method, or marking missingness as a separate category. The method should match the data type and avoid bias.

Mark: 2 / 3

### 9. Normalization And Standardization [4 marks]

Your answer: Normalization is used when features have known min/max and few extreme outliers, scaling values into a range. Standardization puts values around mean 0 and standard deviation 1.

Correct answer: Normalization and standardization scale features so one large-range feature does not dominate learning. This is important for distance-based and gradient-based algorithms such as KNN and neural networks. Normalization rescales to a range; standardization centers around mean 0 and standard deviation 1.

Mark: 3 / 4

### 10a. Feature Selection [2 marks]

Your answer: Proper feature selection reduces dimensionality and keeps only features that matter to the output, helping create a better model.

Correct answer: Feature selection chooses relevant input variables and removes irrelevant or redundant ones. It can improve accuracy, reduce overfitting, reduce training time, and improve interpretability.

Mark: 2 / 2

### 10b. Feature Selection Strategies [6 marks]

Your answer: Embedded method is built into the training algorithm; filter method ranks features using statistics such as chi-squared or ANOVA; wrapper method compares subsets iteratively.

Correct answer: Filter methods use statistical tests before training; wrapper methods train and evaluate models using different feature subsets; embedded methods perform feature selection during model training. Each aims to keep useful features and remove irrelevant or redundant ones.

Mark: 5 / 6

### 11a. Dimensionality Reduction [1 mark]

Your answer: Reducing the amount of irrelevant and redundant features a model learns on.

Correct answer: Dimensionality reduction reduces the number of input features while preserving as much useful information as possible.

Mark: 1 / 1

### 11b. Importance Of Dimensionality Reduction [4 marks]

Your answer: It helps the model train and find important relationships rather than noise, prevents underfitting, and helps with computational resources.

Correct answer: Dimensionality reduction reduces computational cost, removes noise or redundant features, helps reduce overfitting, and combats the curse of dimensionality. It can also make data easier to visualize.

Mark: 3 / 4

Why: Strong points, but it should say helps prevent overfitting rather than underfitting.

### 12. Linear Regression For Continuous Outcomes [5 marks]

Your answer: No meaningful answer given.

Correct answer: Linear regression predicts a continuous value by modelling an approximately linear relationship between independent variables and a dependent variable. It learns a line or equation from training data, using slope(s) and intercept, then applies that equation to new inputs. It is suitable when the relationship is roughly linear and should be evaluated using error metrics or R squared.

Mark: 0 / 5

### 13. Slope And Intercept [4 marks]

Your answer: Slope is the weight; intercept is the bias.

Correct answer: The slope represents the rate of change in the predicted value for a one-unit change in the independent variable. The intercept is the predicted value when the independent variable is zero. Together they define the regression line.

Mark: 1 / 4

### 14. Regression Fit And R Squared [6 marks]

Your answer: No meaningful answer given.

Correct answer: R squared shows how much variation in the dependent variable is explained by the regression model. A value closer to 1 suggests a stronger fit, but it does not prove causation or guarantee good predictions on unseen data. Residuals, error metrics, and testing on unseen data should also be used.

Mark: 0 / 6

### 15. Linear Regression Compared With Another Continuous Model [5 marks]

Your answer: No answer given.

Correct answer: Linear regression is simple, interpretable, and suitable for approximately linear relationships. A neural network or other non-linear regression model can handle more complex patterns but needs more data and computation and is harder to interpret. The better choice depends on accuracy, interpretability, and data complexity.

Mark: 0 / 5

### 16. House Prices By Floor Area [5 marks]

Your answer: Predicting house prices from floor area is fairly suitable for linear regression, but it should include other features such as neighbourhood and age. The data should be fairly linear.

Correct answer: Linear regression is a reasonable baseline because larger floor area often correlates with higher price. However, price also depends on location, condition, age, rooms, and market factors, so floor area alone may be inaccurate. Outliers such as luxury properties can distort the line. It should be evaluated and possibly extended with multiple features.

Mark: 3 / 5

### 17. Ethical Implications [6 marks]

Your answer: Bias, privacy, transparency, environmental impact, security, and responsibility.

Correct answer: Machine learning raises concerns about biased decisions, privacy and consent, lack of transparency, unclear accountability, security risks, and environmental cost. These should be explained in context, with impacts on affected people and mitigation such as audits, representative data, privacy safeguards, and human oversight.

Mark: 3 / 6

Why: Correct issues, but they were listed rather than discussed.

### 18. Biases In Training Data [5 marks]

Your answer: Biased data gives biased output, can lead to unjust decisions, is hard to hold accountable, and hard to detect immediately.

Correct answer: Bias in training data can cause unfair or inaccurate predictions, especially for underrepresented groups. Historical bias may be reproduced, and proxy variables can hide discrimination. Bias must be tested for, mitigated through representative data and preprocessing, and monitored after deployment.

Mark: 3 / 5

### 19. ML In Online Communication [4 marks]

Your answer: Privacy, security, bias, and incorrect factual information.

Correct answer: ML in online communication can create privacy concerns, biased moderation or recommendations, misinformation amplification, filter bubbles, and unfair censorship or failure to detect harmful content. Security and accountability also matter.

Mark: 2 / 4

### 20. Reassessing Ethical Guidelines [5 marks]

Your answer: Technology changes all the time, so ethical guidelines must adapt to protect affected parties and prevent bias and misuse.

Correct answer: Ethical guidelines must be reassessed because new technologies create new risks, data use changes, models drift, social expectations change, and laws develop. Ongoing review supports fairness, privacy, accountability, and public trust.

Mark: 3 / 5

### 21. Emerging Technologies [6 marks]

Your answer: Quantum computing poses security risks, especially if one country has access and another does not. VR can replace human connection and raise security/privacy concerns. Pervasive AI can spread misinformation, be overused, and raise environmental concerns.

Correct answer: Quantum computing may transform optimization and science but threaten encryption. AR/VR may improve training, education, and collaboration but raise privacy, addiction, and access concerns. Pervasive AI may improve efficiency but increase surveillance, bias, dependency, misinformation, job disruption, and environmental impact. Society must balance benefits with regulation, security, fairness, and accessibility.

Mark: 4 / 6

### 22. Jefferson High Education ML Ethics [4 marks]

Your answer: Bias, confidence is not correctness, garbage output, academic integrity/learning, critical thinking, and data privacy.

Correct answer: ML in education must address bias against student groups, privacy of academic and personal data, transparency of recommendations or decisions, human oversight, and avoiding over-reliance on automated labels. It should support teachers and students rather than replace judgement.

Mark: 2 / 4

## A4.3 Machine Learning Approaches Practice Questions

### A4.3 1a. Linear Regression Assumption [inferred 1 mark]

Your answer: The independent variable is independent of the dependent variable, and customer spending is dependent on income for example.

Correct answer: Linear regression assumes an approximately linear relationship between the independent variable(s) and dependent variable, such as customer spending changing predictably with income or other inputs.

Mark: 0 / 1

### A4.3 1b. Outliers And Linear Regression [inferred 2 marks]

Your answer: Extreme outliers heavily distort the regression line, skewing results, so trimming, capping, or transforming may be needed.

Correct answer: Outliers can pull the regression line away from the main trend, distorting slope/intercept and reducing prediction accuracy. They should be investigated and handled appropriately.

Mark: 2 / 2

### A4.3 1c. Evaluating Accuracy [inferred 2 marks]

Your answer: Accuracy equals correct predictions divided by all predictions.

Correct answer: For linear regression, use regression metrics such as mean squared error, mean absolute error, R squared, or testing on a validation/test set. Accuracy is normally for classification, not continuous regression.

Mark: 0 / 2

### A4.3 2a. Multicollinearity [inferred 3 marks]

Your answer: If the model uses two similar features, such as number of rooms and floor area, it can struggle to find patterns; dimensionality reduction may help.

Correct answer: Multicollinearity occurs when input features are strongly correlated. It makes coefficient estimates unstable and makes it hard to interpret each feature's individual effect. Removing, combining, or reducing correlated variables can help.

Mark: 2 / 3

### A4.3 2b. Handling Multicollinearity [inferred 2 marks]

Your answer: Use dimensionality reduction to ensure each feature describes one thing and is not duplicate.

Correct answer: Identify correlated features using correlation analysis or VIF, then remove one feature, combine features, or use dimensionality reduction/regularization.

Mark: 1 / 2

### A4.3 3a. Assuming Linearity [inferred 2 marks]

Your answer: Otherwise linear regression would not be able to predict these values well.

Correct answer: Linear regression assumes the relationship is approximately linear. If student success follows a non-linear relationship, a linear model may underfit and make inaccurate predictions.

Mark: 1 / 2

### A4.3 3b. Predictive Accuracy Technique [inferred 3 marks]

Your answer: Accuracy, F1, precision, and recall formulas.

Correct answer: Use a validation/test set or cross-validation and a metric suitable for the task. If regression, use MSE/MAE/R squared; if classification, use accuracy, precision, recall, or F1. Explain that this tests generalization to unseen data.

Mark: 1 / 3

### A4.3 4a. Decision Tree Advantage [inferred 2 marks]

Your answer: Easy for humans to understand the structure behind the output.

Correct answer: Decision trees are interpretable because they show a clear sequence of feature-based decisions, useful in medical risk classification.

Mark: 2 / 2

### A4.3 4b. Decision Tree Disadvantage [inferred 2 marks]

Your answer: Heart disease may be too complex and based on a large database to be fully suitable for simplification by a decision tree.

Correct answer: A decision tree may overfit if too deep, or may oversimplify complex medical relationships. It can perform poorly on unseen patients if it learns noise.

Mark: 1 / 2

### A4.3 4c i. Critical Parameter [inferred 1 mark]

Your answer: Depth of data.

Correct answer: Maximum tree depth.

Mark: 1 / 1

### A4.3 4c ii. Role Of Parameter [inferred 2 marks]

Your answer: It controls output complexity and overfitting risk if depth is too large, but must be deep enough to produce useful answers.

Correct answer: Maximum depth limits how many levels of splits the tree can make. Lower depth can reduce overfitting; very high depth can learn noise.

Mark: 2 / 2

### A4.3 5a. k In KNN [inferred 2 marks]

Your answer: Too low k causes underfitting and too high k causes overfitting; incorrect k lowers accuracy.

Correct answer: Small k is sensitive to noise and can overfit; large k smooths predictions and can underfit by ignoring local patterns.

Mark: 1 / 2

### A4.3 5b. Optimal k [inferred 2 marks]

Your answer: Confusion matrix.

Correct answer: Test several k values using validation data or cross-validation and choose the value with the best performance metric.

Mark: 0 / 2

### A4.3 5c. Feature Scales In KNN [inferred 2 marks]

Your answer: More features worsen performance, fewer features improve performance until overfitting.

Correct answer: KNN uses distance, so features with larger numerical scales dominate the distance calculation. Normalization or standardization is needed so features contribute fairly.

Mark: 0 / 2

### A4.3 6a. Decision Trees Over KNN [inferred 4 marks]

Your answer: Decision trees give visual hierarchy, are easier to understand and justify, and selecting k in KNN may be difficult.

Correct answer: Decision trees are more interpretable, easier to justify to teachers/students, faster at prediction once trained, and less sensitive to feature scaling. KNN also requires choosing k and can be slower on large datasets.

Mark: 3 / 4

### A4.3 6b. KNN Over Decision Trees [inferred 4 marks]

Your answer: If there are many learning groups, decision trees might be ineffective while KNN works; KNN is harder to become biased.

Correct answer: KNN can classify based on similarity to nearby students, works with complex local patterns, can handle multi-class grouping, and makes fewer assumptions about decision boundaries. However, it is still affected by biased data.

Mark: 1 / 4

### A4.3 6c. Preventing Overfitting [inferred 2 marks]

Your answer: Use a proper amount of depth and features.

Correct answer: Limit maximum tree depth, prune the tree, require a minimum number of samples per split, or use validation to tune parameters.

Mark: 1 / 2

### A4.3 7a. Precision And Recall [inferred 2 marks]

Your answer: Precision = true positive failures / (true positive failures + false positives). Recall = true positive failures / (true positive failures + false negatives).

Correct answer: Correct.

Mark: 2 / 2

### A4.3 7b. F1 vs Accuracy [inferred 3 marks]

Your answer: Accuracy does not take false negatives into account properly, while F1 does.

Correct answer: Accuracy can be misleading when false negatives have high cost or when classes are imbalanced. F1 combines precision and recall, so it better reflects the tradeoff between missed failures and false alarms.

Mark: 2 / 3

### A4.3 7c. Confusion Matrix [inferred 3 marks]

Your answer: A confusion matrix shows TP, TN, FP, FN; correct predictions are on the diagonal, errors are off diagonal, and metrics can be derived.

Correct answer: Correct. A confusion matrix visually separates correct and incorrect classifications and shows the types of errors the model makes.

Mark: 3 / 3

### A4.3 8a. High Recall In Medical Classification [inferred 2 marks]

Your answer: High recall matters because false negatives are dangerous; missing a patient is worse than giving a false positive.

Correct answer: Correct. High recall reduces missed real disease cases, which is important where false negatives can harm patients.

Mark: 2 / 2

### A4.3 8b. Imbalanced Dataset [inferred 2 marks]

Your answer: It can skew precision and recall because of imbalance in false negatives and false positives.

Correct answer: Imbalanced data can make the model favour the majority class, giving high accuracy but poor recall or precision for the minority class.

Mark: 1 / 2

### A4.3 8c i. Threshold Adjustment [inferred 1 mark]

Your answer: Hyperparameter tuning, e.g. recall.

Correct answer: Adjust the classification probability threshold, such as lowering the threshold for the positive class.

Mark: 0 / 1

### A4.3 8c ii. F1 Impact [inferred 2 marks]

Your answer: F1 uses recall in its formula, but you were unsure.

Correct answer: Lowering the threshold may increase recall but reduce precision. F1 improves only if the balance between precision and recall improves.

Mark: 1 / 2

### A4.3 9a. k-Means Objective [inferred 2 marks]

Your answer: Group data into non-overlapping clusters based on distance to the centroid.

Correct answer: k-means partitions data into k clusters by assigning points to the nearest centroid and updating centroids to minimize within-cluster distance.

Mark: 2 / 2

### A4.3 9b. k-Means Challenge [inferred 2 marks]

Your answer: Customers can overlap, which is not possible in k-means.

Correct answer: k-means forces each point into one cluster, so overlapping or ambiguous customer behaviour can be hard to represent. Also, choosing k is difficult.

Mark: 1 / 2

### A4.3 9c. Choice Of k In k-Means [inferred 2 marks]

Your answer: You confused k-means with nearest neighbour range and reversed overfitting/underfitting.

Correct answer: A low k may merge different groups; a high k may split meaningful groups into too many small clusters. The chosen k changes the segmentation.

Mark: 0 / 2

### A4.3 10a. k-Means vs Spectral Clustering [inferred 3 marks]

Your answer: k-means struggles with non-spherical data because it uses centroid distance and non-overlapping clusters. Spectral clustering uses graph-based relationships and is better for complex data.

Correct answer: Correct. k-means works best with compact/spherical clusters, while spectral clustering can use similarity graphs to separate non-spherical structures.

Mark: 3 / 3

### A4.3 10b. Spectral Clustering Large Dataset Challenge [inferred 2 marks]

Your answer: Computationally expensive.

Correct answer: Spectral clustering can be computationally expensive on large datasets because similarity graphs/matrices are costly to build and process.

Mark: 2 / 2

### A4.3 10c. Customer Satisfaction [inferred 2 marks]

Your answer: It can find more complex classes and relationships to increase customer satisfaction.

Correct answer: More accurate customer clusters can lead to better recommendations, offers, and services, improving satisfaction.

Mark: 1 / 2

### A4.3 11a. Social Groups In A Network [inferred 1 mark]

Your answer: Spectral clustering.

Correct answer: Spectral clustering.

Mark: 1 / 1

### A4.3 11b. Diverse Data Challenge [inferred 2 marks]

Your answer: It may be computationally expensive and may overfit.

Correct answer: Diverse data can have different scales, formats, noise levels, and relevance. Combining it poorly can produce misleading clusters.

Mark: 1 / 2

### A4.3 11c. Number Of Clusters [inferred 2 marks]

Your answer: Too many clusters equals underfitting; too few clusters equals overfitting.

Correct answer: Too few clusters may merge distinct groups; too many clusters may fragment meaningful groups. Your labels of overfitting/underfitting were reversed, but the idea that cluster number affects results was present.

Mark: 1 / 2

### A4.3 12a. Traffic Sensor Algorithm [inferred 3 marks]

Your answer: DBSCAN because it handles noise based on density.

Correct answer: DBSCAN is suitable because it can find clusters of varying shapes and densities and identify noise/outliers, useful for irregular traffic sensor patterns.

Mark: 2 / 3

### A4.3 12b. Traffic Management Benefit [inferred 2 marks]

Your answer: Traffic clusters identify high-density choke points and show what to fix or optimize.

Correct answer: Correct. Clusters can reveal congestion hotspots and guide signal timing, road planning, public transport, and infrastructure investment.

Mark: 2 / 2

### A4.3 13a. Lift [inferred 2 marks]

Your answer: Lift means how likely it is for a relationship not to be random.

Correct answer: Lift compares how often items occur together against how often they would occur if independent. Lift greater than 1 indicates a positive association.

Mark: 1 / 2

### A4.3 13b. Support And Confidence Thresholds [inferred 3 marks]

Your answer: Confidence is how likely a consumer follows the predicted behaviour; support is how often an itemset appears in the dataset.

Correct answer: Support controls how frequent itemsets must be to be considered; confidence controls how reliable rules must be. Higher thresholds produce fewer stronger rules; lower thresholds produce more but weaker/noisier rules.

Mark: 2 / 3

### A4.3 13c. Buying Patterns Marketing [inferred 2 marks]

Your answer: Buying patterns help marketers push personalized offers or ads.

Correct answer: Correct. They can support targeted offers, bundles, recommendations, shelf placement, and promotions.

Mark: 2 / 2

### A4.3 14a. Confidence And Support [inferred 2 marks]

Your answer: Confidence shows how likely a borrower is to follow a predicted borrowing behaviour; support shows how often two books are borrowed together.

Correct answer: Correct. Support is frequency of the pattern; confidence is probability of the consequent given the antecedent.

Mark: 2 / 2

### A4.3 14b. Discover Borrowing Patterns [inferred 2 marks]

Your answer: Mine association rules from the library dataset.

Correct answer: Correct. Borrowing transactions can be analysed with association rule mining to find books or genres often borrowed together.

Mark: 2 / 2

### A4.3 14c. Association Rule Limitation [inferred 2 marks]

Your answer: Too little/diverse/individual data could lead to overfitting and low support, making the rules ineffective.

Correct answer: Correct. Association rules can be weak when support is low, and they show correlation rather than causation.

Mark: 2 / 2

### A4.3 15a. Crossover [inferred 2 marks]

Your answer: Two parent algorithms create an offspring with traits from both, increasing diversity and combining good traits.

Correct answer: Crossover combines parts of two parent solutions to create offspring, allowing useful traits to be inherited.

Mark: 2 / 2

### A4.3 15b. Mutation [inferred 2 marks]

Your answer: Mutation introduces random changes to increase diversity, reduce getting stuck, and possibly find better solutions.

Correct answer: Correct. Mutation adds random variation and helps avoid local optima.

Mark: 2 / 2

### A4.3 15c. GA Advantage [inferred 2 marks]

Your answer: GAs introduce natural selection and variety to find the most optimal solution.

Correct answer: Genetic algorithms can search very large complex solution spaces and find good approximate solutions without testing every possibility.

Mark: 1 / 2

Why: Correct direction, but "most optimal" overstates it; GAs do not guarantee the best solution.

### A4.3 16a. Selection [inferred 2 marks]

Your answer: Selection picks suitable algorithms for crossover and helps find the best timetable scheduling algorithm.

Correct answer: Selection chooses fitter candidate timetable solutions to become parents for the next generation.

Mark: 1 / 2

### A4.3 16b. Fitness Function [inferred 3 marks]

Your answer: A fitness function shows how good an algorithm is at its task, such as correctly picking the preferred schedule.

Correct answer: A fitness function scores each timetable solution, rewarding satisfied preferences and penalizing clashes, unavailable rooms, or constraint violations.

Mark: 2 / 3

### A4.3 16c. Population Size [inferred 2 marks]

Your answer: Greater population gives more diverse algorithms and should result in a better final algorithm.

Correct answer: Larger population increases diversity and chance of finding good solutions but requires more processing. Smaller population is faster but may converge prematurely.

Mark: 2 / 2

### A4.3 16d. GA Timetable Benefits [inferred 4 marks]

Your answer: Accurate, and creative solutions.

Correct answer: GAs can handle many constraints and search a large solution space efficiently. They can produce good approximate timetables where exact search is impractical.

Mark: 1 / 4

### A4.3 16e. GA Timetable Drawbacks [inferred 4 marks]

Your answer: Takes a lot of time and might not be meaningful enough.

Correct answer: GAs can be computationally expensive and do not guarantee an optimal solution. Results depend heavily on the fitness function, parameters, and population size.

Mark: 2 / 4

### A4.3 17a. Neural Network Layer [inferred 2 marks]

Your answer: Input layer, where the specific inputs enter a perceptron.

Correct answer: The input layer receives feature values and passes them into the network. Hidden layers process patterns; output layers produce predictions.

Mark: 2 / 2

### A4.3 17b. Neural Network Overfitting [inferred 2 marks]

Your answer: It might focus on the wrong pattern and waste training, resources, and effort, especially because neural networks are complex.

Correct answer: Neural networks can have many parameters and may memorize training data/noise rather than learning general patterns. This causes poor performance on unseen data.

Mark: 1 / 2

### A4.3 17c. Training To Minimize Error [inferred 3 marks]

Your answer: With enough consumer data, hidden layers, computing power, and clean selected data, it can find patterns for loan default risk.

Correct answer: The network predicts default risk, compares predictions with actual labels using a loss function, then updates weights through backpropagation and optimization to reduce error over repeated training.

Mark: 1 / 3

### A4.3 18a i. Electricity Demand Type [inferred 1 mark]

Your answer: Regression.

Correct answer: Regression.

Mark: 1 / 1

### A4.3 18a ii. Significance [inferred 2 marks]

Your answer: Because it is linear numerical continuous data.

Correct answer: Since demand is a continuous numerical value, the model should output a number and use regression loss/metrics rather than class labels.

Mark: 1 / 2

### A4.3 18b. Activation Function [inferred 2 marks]

Your answer: ReLU outputs 0 if the input is negative and otherwise outputs the value, introducing non-linearity.

Correct answer: Correct.

Mark: 2 / 2

### A4.3 18c. Output Activation [inferred 2 marks]

Your answer: Linear activation function because it outputs exact values, which are important in this case.

Correct answer: Correct. A linear output is suitable for continuous regression.

Mark: 2 / 2

### A4.3 18d. Deep Networks For Demand Forecasting [inferred 2 marks]

Your answer: Electricity demand forecasting may be complex with lots of nuance that shallow networks cannot capture.

Correct answer: Correct. Deep networks can learn complex interactions between variables such as time, weather, season, and human behaviour.

Mark: 2 / 2

### A4.3 18e. Backpropagation [inferred 3 marks]

Your answer: The model runs forward propagation, calculates error/loss, then goes backwards through the network adjusting weights and biases to reduce future errors.

Correct answer: Correct.

Mark: 3 / 3

### A4.3 18f. Training Deep Networks Challenges [inferred 2 marks]

Your answer: Resource intensive and requires a big dataset.

Correct answer: Correct. Other valid points include overfitting, tuning difficulty, and interpretability.

Mark: 2 / 2

### A4.3 19a. Model Selection [inferred 2 marks]

Your answer: Picking the appropriate model for the task.

Correct answer: Model selection is choosing the most suitable model based on task type, data, performance, interpretability, complexity, and constraints.

Mark: 2 / 2

### A4.3 19b. Metrics For User Engagement [inferred 2 marks]

Your answer: Computational resources available and dataset available.

Correct answer: Metrics could include accuracy/F1 for classification, or MSE/R squared for continuous engagement prediction.

Mark: 0 / 2

### A4.3 19c i. Cross-Validation [inferred 2 marks]

Your answer: Data is split into folds, and the model is trained and tested on different folds. The average score estimates generalization.

Correct answer: Correct.

Mark: 2 / 2

### A4.3 19c ii. Importance Of Cross-Validation [inferred 2 marks]

Your answer: It compares models using multiple validation splits, so the model is less likely to be overfitted to one particular split.

Correct answer: Correct.

Mark: 2 / 2

### A4.3 20a. Overfitting In Basketball Prediction [inferred 2 marks]

Your answer: Selecting a model that overfits on the specific data used for basketball outcome prediction.

Correct answer: Overfitting means the model learns noise or overly specific patterns from historical basketball data and performs poorly on future games.

Mark: 1 / 2

### A4.3 20b. Model Selection Factors [inferred 3 marks]

Your answer: Computational resources available, dataset available, and time available.

Correct answer: Valid factors include model performance on unseen data, data size/quality, computational resources, time constraints, interpretability, risk of overfitting, and task type.

Mark: 3 / 3

## A4.4 Practice Questions

No answers from this section were present in the submitted Excalidraw file, so this section was not marked.

## Case Study Questions

No answers from this section were present in the submitted Excalidraw file, so this section was not marked.
