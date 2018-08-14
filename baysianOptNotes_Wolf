Baysian Optimization
====================
Created Sunday 08 July 2018

### Description
https://towardsdatascience.com/a-conceptual-explanation-of-bayesian-model-based-hyperparameter-optimization-for-machine-learning-b8172278050f
https://www.iro.umontreal.ca/%7Ebengioy/cifar/NCAP2014-summerschool/slides/Ryan_adams_140814_bayesopt_ncap.pdf

overview paper:
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7352306

Quote:
We will see that the careful choice of statistical model is often far more important than the choice of acquisition function heuristic.

X : trials / experiments
f(x) : the true function f, i.e. the repond surface, eg the true performance metric for a hyperpara setting x  
y: experiment outcome (noisy, ie. f(x) +  guass noise)
w: latent variable, model parameter

### List of libaries:
https://medium.com/@mikkokotila/a-comprehensive-list-of-hyperparameter-optimization-tuning-solutions-88e067f19d9

https://github.com/hawk31/pyGPGO

http://hyperopt.github.io/hyperopt/
https://papers.nips.cc/paper/4443-algorithms-for-hyper-parameter-optimization.pdf
Quote:
Hyperopt has been designed to accommodate Bayesian optimization algorithms based on Gaussian processes and regression trees, but these are not currently implemented.

### Components:

	— Surrogate model choice
	— Covariance function choice
	— Acquisition function behaviour
	— Hyperparameter treatment


#### Surrogate Model
aka Response Surface
— Guanssian Processes [Library: Spearmint and MOE]
— Random Forest Regression [Library: SMAC]
— Tree Parzen Estimation [Library: Hyperopt]

#### Covariance function choice
For Gaussian process, it is the kernal,
the related-ness of points, controls the smoothness of the surrogate function

#### Acquisition function
EI: Expected Improvement (per second)
PI: Prob of improvement
UCB: upper confidence bound (upper bound of uncertainty shade region
TS: thompson sampling (sample a line from the model then choose the best point)
ES: entropy sampling, choose a point that would reduce most entropy, ie. shaded area
./pasted_image.png

#### Hyperparameter treatment
Baysian optimization has its own hyperpara... (para in the model of the surrogate function)
So:
marginalize the hyper-para (eg by MCMC sampling)

Other Notes:
GP gausian process cannot yet deal with conditional search space (ie. para B is only relevent when para A takes certain value)
but Random forest and TPE (tree parzen estimator) can

GP assume stationary, i.e.
the kernel K(x,x') can be equivalently written as a function of x-x' . 
to deal with it, maybe apply a transform to the search space first e.g.
for learning rate, instead of linear 0->0.5->1 , search in log space 0.01->0.1->1

Tree Parzen Estimator TPE
estimate the p(x|y) i.e. given the score y, what region of hyper-para space will give such y?
GP uses p(y|x), at this hyper-para setting x, what is the prob. distribution of its score y?
TPE made 2 PDF : 
g(x) : region of hyper-para space that will give y Greater then some thres y*
l(x) : region of hyper-para space that will give y Less then some thres y*
Weakness: In the know obs (yn,xn), TPE don't care how much y is less then y*
it just grab all obs points with y<y* and build l(x) 

Notebooks
https://www.kaggle.com/eikedehling/tune-and-compare-xgb-lightgbm-rf-with-hyperopt

