<div align="center"><h1>Machine-Learning-Computer-Science-Engineering</h1></div>
<div>
    <h1 align="center"><u>Introduction</u></h1>

<div>
    <h1 align="center"><u>Well posed learning problems</u></h1>
    <p>A computer program is said to learn from experience E in context to some task T and some performance measure P, if its performance on T, as was measured by P, upgrades with experience E.</p>
</div>

<div>
    <h2>Well posed learning problems - Examples</h2>
    <div>
        <ul>
            <div><li>
            <h3>To better filter emails as spam or not</h3>
            Task – Classifying emails as spam or not<br>
            Performance Measure – The fraction of emails accurately classified as spam or not spam<br>
            Experience – Observing you label emails as spam or not spam</li>
            </div>
            <div>
            <li>
            <h3>Handwriting Recognition Problem</h3>
            Task – Acknowledging handwritten words within portrayal<br>
            Performance Measure – percent of words accurately classified<br>
            Experience – a directory of handwritten words with given classifications</li>
            </div>
            <div>
            <li>
            <h3>Fruit Prediction Problem</h3>
            Task – forecasting different fruits for recognition<br>
            Performance Measure – able to predict maximum variety of fruits<br>
            Experience – training machine with the largest datasets of fruits images</li>
            </div>
            <div>
            <li>
            <h3>Face Recognition Problem</h3>
            Task – predicting different types of faces<br>
            Performance Measure – able to predict maximum types of faces<br>
            Experience – training machine with maximum amount of datasets of different face images</li>
            </div>
        </ul>
    </div>
    
</div>

<div>
    <h1 align="center"><u>Design a Learning System in Machine Learning</u></h1>
    <h2>Learning System Design</h2>
    <p>According to Arthur Samuel “Machine Learning enables a Machine to Automatically learn from Data, Improve performance from an Experience and predict things without explicitly programmed.”</p>
    <div>
        <ol>
            <div>
            <li>
                <h2>Supervised Learning</h2>
                <p>Supervised learning, as the name indicates, has the presence of a supervisor as a teacher. Basically supervised learning is when we teach or train the machine using data that is well labeled. Which means some data is already tagged with the correct answer.
                After that, the machine is provided with a new set of examples(data) so that the supervised learning algorithm analyses the training data(set of training examples) and produces a correct outcome from labeled data.</p>
                <h3>Supervised Learning Methods</h3>
                <ul>
                    <li>Regression</li>
                    <li>Logistic Regression</li>
                    <li>Naive Bayes Classifiers</li>
                    <li>K-NN (k nearest neighbors)</li>
                    <li>Decision Trees</li>
                    <li>Support Vector Machine</li>
                </ul>
            </li>
            </div>
            <div>
            <li>
                <h2>Unsupervised Learning</h2>
                <p>Unsupervised learning is the training of a machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance. Here the task of the machine is to group unsorted information according to similarities, patterns, and differences without any prior training of data.</p>
                <h3>Unsupervised Learning Methods</h3>
                <ul>
                    <li>Hierarchical clustering</li>
                    <li>K-means clusteringn</li>
                    <li>Principal Component Analysis</li>
                    <li>Singular Value Decomposition</li>
                    <li>Independent Component Analysis</li>
                </ul>
            </li>
            </div>
            <div>
            <li>
                <h2>Reinforcement learning</h2>
                <p>Reinforcement learning is an area of Machine Learning. It is about taking suitable action to maximize reward in a particular situation.
                    It is employed by various software and machines to find the best possible behavior or path it should take in a specific situation.
                    Reinforcement learning, there is no answer but the reinforcement agent decides what to do to perform the given task. In the absence of a training dataset, it is bound to learn from its experience.</p>
                <h3>Reinforcement learning methods</h3>
                <ul>
                    <li>State-Action-Reward-State-Action (SARSA)</li>
                    <li>Deep Deterministic Policy Gradient (DDPG)</li>
                </ul>
            </li>
            </div>
        </ol>
    </div>
    <div>
    <h2>Comparison</h2>
    <p>References :<br>
    <a href="https://www.geeksforgeeks.org/supervised- unsupervised-learning/">https://www.geeksforgeeks.org/supervised- unsupervised-learning/</a><br>
    <a href="https://www.aitude.com/supervised-vs- unsupervised-vs-reinforcement/">https://www.aitude.com/supervised-vs- unsupervised-vs-reinforcement/</a>
    </div>
    </p>
</div>



<div>
        <div><h1 align="center"><u>Data Pre-Processing</u></h1></div>
        <div>
            <h2>Data Preprocessing</h2>
            <p>Data preprocessing is the process of transforming raw data into an understandable format.The quality of the data should be checked before applying machine learning or data mining algorithms.</p>
        </div>
        <div>
            <h2>Methods of Data Pre-processing</h2>
            <div>
            <ul>
                <div>
                <li>Data Cleaning</li>
                <li>Data Integration</li>
                <li>Data transformation</li>
                <li>Data Reduction/Dimension Reduction</li>
                </div>
             </ul>
            </div>
            <div>
            <h3>Data Cleaning</h3>
            <ul>
                <li>Missing Values - Ignore/Fill Missing values</li>
                <li>Noisy Data - Binning (Mean/ Median/ Boundary Values) or Regression or Clustering</li>
            </ul>
            </div>
            <div>
                <h3>Data Integration</h3>
                <p>The process of combining multiple sources into a single dataset. The Data integration process is one of the main components in data management.                </p>
                <ul>
                    <li>Schema integration: Integrates metadata(a set of data that describes other data) from different sources.</li>
                    <li>Entity identification problem: Identifying entities from multiple databases.</li>
                    <li>Detecting and resolving data value concepts: The data taken from different databases while merging may differ from another database. For example, the date format may differ like “MM/DD/YYYY” or “DD/MM/YYYY”.</li>
                </ul>
            </div>
            <div>
                <h3>Data Transformation</h3>
                <p>The change made in the format or the structure of the data is called data transformation. This step can be simple or complex based on the requirements.</p>
                <ul>
                    <li>Normalization:
                        It is done in order to scale the data values in a specified range (-1.0 to 1.0 or 0.0 to 1.0)</li>
                    <li>Attribute Selection:
                        In this strategy, new attributes are constructed from the given set of attributes to help the mining process.</li>
                    <li>Discretization: The continuous data here is split into intervals. interval like (3 pm-5 pm, 6 pm-8 pm).</li>
                    <li>Concept Hierarchy Generation:
                        Here attributes are converted from lower level to higher level in hierarchy. For Example-The attribute “city” can be converted to “country”.</li>
                </ul>
            </div>
            <div>
                <h3>Data Reduction</h3>
                <p>This process helps in the reduction of the volume of the data which makes the analysis easier yet produces the same or almost the same result. This reduction also helps to reduce storage space.</p>
                <ul>
                    <li>Attribute Subset Selection:
                        The highly relevant attributes should be used, rest all can be discarded.</li>
                    <li>Numerosity Reduction:
                        This enable to store the model of data instead of whole data, for example: Regression Models.</li>
                    <li>Dimensionality Reduction:
                        This reduce the size of data by encoding mechanisms.It can be lossy or lossless.</li>
                </ul>
            </div>
        </div>
        <div>
            <h2>Data Preprocessing: Best practices</h2>
            <ol>
                <li>The first step in Data Preprocessing is to understand your data. Just looking at your dataset can give you an intuition of what things you need to focus on.</li>
                <li>Use statistical methods or pre-built libraries that help you visualize the dataset and give a clear image of how your data looks in terms of class distribution.</li>
                <li>Summarize your data in terms of the number of duplicates, missing values, and outliers present in the data.</li>
                <li>Drop the fields you think have no use for the modeling or are closely related to other attributes. Dimensionality reduction is one of the very important aspects of Data Preprocessing.</li>
                <li>Do some feature engineering and figure out which attributes contribute most towards model training.</li>
            </ol>
        </div>
        <div>
            <h2>Splitting dataset into Training and Testing set.</h2>
            <ul>
                <li><h3>Training Data</h3>
                    <p>The observations in the training set form the experience that the algorithm uses to learn. In supervised learning problems, each observation consists of an observed output variable and one or more observed input variables.</p></li>
                <li><h3>Test Data</h3>
                    <p>The test set is a set of observations used to evaluate the performance of the model using some performance metric. It is important that no observations from the training set are included in the test set.</p></li>
                </ul>
        </div>
        <div>
            <h2>Basics</h2>
            <ol>
                <li>Bias:<br> Assumptions made by a model to make a function easier to learn.</li>
                <li>Variance:<br> If you train your data on training data and obtain a very low error, upon changing the data and then training the same previous model you experience a high error, this is variance.</li>
            </ol>
        </div>
        <div>
            <h2>Under & Over Fitting</h2>
            <ol>
                <li>Underfitting:
                   <br>A statistical model or a machine learning algorithm is said to have underfitting when it cannot capture the underlying trend of the data.
                </li>
                <li>
                    Overfitting:
                    <br>A statistical model is said to be overfitted when we train it with a lot of data (just like fitting ourselves in oversized pants!).
                </li>
            </ol>
        </div>
        <div>
            <span>References :<span><br>
            <a href="https://www.geeksforgeeks.org/data- preprocessing-in-data-mining/">https://www.geeksforgeeks.org/data- preprocessing-in-data-mining/</a><br>
            <a href="https://www.analyticsvidhya.com/blog/2021/ 08/data-preprocessing-in-data-mining-a- hands-on-guide/">https://www.analyticsvidhya.com/blog/2021/ 08/data-preprocessing-in-data-mining-a- hands-on-guide/</a><br>
            <a href="https://www.v7labs.com/blog/data- preprocessing-guide">https://www.v7labs.com/blog/data- preprocessing-guide</a>
        </div>
    </div>
