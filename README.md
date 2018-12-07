Meeting Agenda
==============

2018-12-07
=====

Sharing
------
- ECharts - a visualization tool by Baidu

2018-11-25
=========

Sharing
------
### Pong
- MLflow: An open source platform for the machine learning lifecycle
   - website: https://mlflow.org/
- Airflow: a platform to programmatically author, schedule, and monitor workflows
   - website: https://airflow.apache.org/



2018-10-28
=========

Sharing
------
### Kin
- 2018 DL & RL Summer School, Toronto
  Video: http://videolectures.net/DLRLsummerschool2018_toronto/

### Dominic
- Data Visualization Tool in web interface
  - https://vega.github.io/
- NLP Allen NLP - modular tools for many NLP problems
  - https://allennlp.org/

### Roy
- Kepler - Geo Visualization tool
  - http://kepler.gl/

### Anthony
- Google DataStudio
  - https://datastudio.google.com/u/0/navigation/reporting

2018-10-14
=========

Sharing
------
### Kin
- Google NLP Breakthrough - BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
  - https://arxiv.org/abs/1810.04805
  - https://www.jiqizhixin.com/articles/2018-10-12-13
- SHAP: sounds like an improvement of LIME (Model interpretation) - a unified approach to explain the output of any machine learning model. - https://github.com/slundberg/shap
- Google Facets: Interactive Visualization
  - https://pair-code.github.io/facets/
  - https://github.com/PAIR-code/facets
- Google Dataset search: https://toolbox.google.com/datasetsearch

### Pong
- dvc: data version control for data science projects
  - https://dvc.org/
- implicit: collaborative filtering faster than spark
  - https://github.com/benfred/implicit

### Victor
- ActiveQA
  - https://github.com/google/active-qa
- Google’s AI Bots
  - https://gizmodo.com/google-s-ai-bots-invent-ridiculous-new-legs-to-scamper-1829693108
  
  
### Solomon
- Home-Credit 2nd solution (machine learning pipeline)
  - https://github.com/neptune-ml/open-solution-home-credit
  
### Anthony
- Home-Credit sharing
  - https://www.meetup.com/Hong-Kong-Machine-Learning-Meetup

2018-09-30
=========

DeepRLBootcamp lab 1
--------------------

- Value Iteration
  - Value Function
  - Policy Function

- Reinforcement learning online syllabus: https://hollygrimm.com/syllabus_rl
- Featuretools
- an article about difficutlies of RL: https://bigdatafinance.tw/index.php/tech/data-processing/528-2018-02-27-04-31-42
- Google Dopamine: https://github.com/google/dopamine


2018-08-14
==========

Theoretical Review of Bayesian Optimization
-----------------------------------------
https://ieeexplore.ieee.org/document/7352306/

Misc
----
- Kappa
- point cloud
  
  
  
2018-08-05
==========

Attention is all you need [paper]
------------------------
- Paper - https://arxiv.org/abs/1706.03762
- Slide deck - https://nlp.stanford.edu/seminar/details/lkaiser.pdf

One Model to Learn them all [paper]
---------------------------
- paper - https://arxiv.org/pdf/1706.05137.pdf
- Chinese explanation - https://blog.csdn.net/shenxiaolu1984/article/details/73736259
- Three main neural net structures:
  1. Depthwise Separable Convolution
  2. Attention
  3. Mixture-of-experts layer
- Main achievements:
  1. Generalize to different tasks in a single model:
    - image
    - text
    - sound
    - classification (output)
  2. Even there are extra components, it won't hinder for other tasks accuracy
- Main concept:
  - use Modality Unit to transform any kind of input into universal representation 

Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer [paper]
--------------------------
- https://arxiv.org/abs/1701.06538
- https://medium.com/@thoszymkowiak/google-brains-new-super-fast-and-highly-accurate-ai-the-mixture-of-experts-layer-dd3972c25663

Tensor2Tensor [library from Google]
-------------
- short summary: https://towardsdatascience.com/tensor2tensor-and-one-model-to-learn-them-all-7ef3f9b61ba4


Misc
----
- R^2 - Coefficient of Determination
  - https://en.wikipedia.org/wiki/Coefficient_of_determination
  - Where 1 is the best score
  - 0 is the score as good/bad as the baseline with predicted value as expected value
  - (negative score is the score which is worse than the baseline (expected value)
  



2018-07-31
===========
- Rita Singh, from CMU, uses voice signal to analyze many things, profiling human from their voice, they even can construct the 3D facial structure from it.
  - https://www.youtube.com/watch?v=4HjcQjwKBWM
  - https://www.researchgate.net/scientific-contributions/9403190_Rita_Singh
- AWS Kinesis: AWS data streaming applications.
- Deep Mutual Learning
- Re-ranking Person Re-identification with k-reciprocal Encoding
  - Jaccard Similarity for finding k-reciprocal nearest neighbors
- Dist-GAN: An Improved GAN using Distance Constraints
  - http://closure11.com/%E5%AF%B9%E6%8A%97%E8%87%AA%E7%BC%96%E7%A0%81%E5%99%A8%EF%BC%9Aadversarial-autoencoders/
  - https://arxiv.org/abs/1803.08887
  - ...constrain the generator by an Autoencoder (AE). We propose a formulation to consider the reconstructed samples from AE as "real" samples for the discriminator. This couples the convergence of the AE with that of the discriminator, effectively slowing down the convergence of discriminator and reducing gradient vanishing. Importantly, we propose two novel distance constraints to improve the generator...

- keras library for reinforcement learning
  - https://github.com/keras-rl/keras-rl
  
- trading gym: openai gym environment for trading
  - https://github.com/Prediction-Machines/Trading-Gym

Tools:
-----
- TextBlob: NLP tool, based on NLTK
  - https://www.analyticsvidhya.com/blog/2018/02/natural-language-processing-for-beginners-using-textblob/
  - language translation and detection which is powered by Google Translate
  - Sentiment Analysis
- Sairen - OpenAI Gym Reinforcement Learning Environment for the Stock Market (real-time)
  - https://doctorj.gitlab.io/sairen/
- Quandl
- Numerai: data science competition in Finance
- NVIDIA DeepStream: https://developer.nvidia.com/deepstream-sdk
- NVIDIA Isaac: https://www.nvidia.com/en-us/deep-learning-ai/industries/robotics/


2018-07-15
==========

1. Debrief Kaggle Avito [1h, by Kin]
2. Start Kaggle Home Credit [2hr]

Topics
------
- improving CNN with Coord info 
https://www.youtube.com/watch?v=8yFQc6elePA

- ML blog
https://thegradient.pub

- **RL should not be trained form scratch** [Homework Reading, Kin]
https://thegradient.pub/how-to-fix-rl/
  

- Word embedding is soon obsolete? [Homework Reading, Roy]
https://thegradient.pub/nlp-imagenet/
