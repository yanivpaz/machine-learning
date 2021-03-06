# Machine-learning

## Supervised vs unsupervised 
 - supervised - label ( the trainer who set the label can be machine or person ) 
   input/output relation is known 
 - unserupervised  - target
   input/output relation is unknown 
 https://datascience.stackexchange.com/questions/44108/difference-between-a-target-and-a-label-in-machine-learning
 
## Categories 
- regression ( supervised ) - predicting stock , looking for number 
- classification ( supervised ) - detect cat/dog
- clustering  - ( unsupervised ) - categorize people 

## Algorithms 
* supervised : 
- regression
- decision tree
- K neareast neighbour
- neural networks ( deep learning )
  - CNN - image processing 

* unsupervised :
- kmeans (clusters)
- anomlay detecation 
- neural networks ( deep learning )

* reinforcement ( based on feedback , ie pacman - the reward is being changed and influence the next movemnt )
- q learning 
- SARSA

## Typical flow
- prepare training  data ( feature and lables ) 
  * remove noisy data points for accurate results 
  * select features (input to the problem) 
  * 10 times data points as features ( 5 features need 50 data points)
  * imputation - the assignment of a value to something by inference from the value of the products or processes to which it contributes
- input 75% of data to chosen algorithem
- generate candidate model
- input 25% test data (only include features)
- compare target data with real vlaues in training data
- repeat 

application use the model by sending parameters 

## Terminology
- label + feature = data points = obervations 
- multiple observations = dataset 

## Visualizations
- histograms 
- scatter plots - relationshipts between features and labels 

## ML options on AWS 
1) SAAS managed and trained 
models already trained 
can tweak models
( AWS lex, polly etc) 

2) managed  - sagemaker 
can create model
no control on the infrastructure 

3) self managed 
full control on everything
special pre configured AMIS with support to relevant platforms like pytorch , Tensorflow ,Keras 

### AWS DLAMI
Deep learning AMI

- DLAMI with Conda - all frameworks are installed 
- Base AMI ( advanced )

for learning use p2.xlarge ( c4.xlarge as alternative) 
for adcance use case use other GPU instnace / FPGA/ AWS inferentia 

eia1.large eia1.meduim - accelarator for elastic inference
