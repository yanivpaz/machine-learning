# Machine-learning
## Categories 
- regression ( supervised ) - predicting stock , looking for number 
- classification ( supervised ) - detect cat/dog
- clusters - multi classification  ( unsupervised ) - categorize people 

## Algorithms 
- decision tree
- neural networks ( deep learning )
- regression
- kmeans (clusters)
- bayesian 

## Typical flow
- prepare training  data 
  * select features (input to problem) 
- input 75% of data to chosen algorithem
- generate candidate model
- input 25% test data 
- compare target data with real vlaues in training data
- repeat 

application use the model by sending parameters 

## Supervised vs unsupervised 
 - supervised - label
 - unserupervised  - target
 
## Models 
 - custom local - R , Tensorflow ( support deep learning)
 - custom using cloud ( AWS services )
 - SAAS ( AWS lex, polly etc) 

## ML options on AWS 
1) managed and trained 
models already trained 
can tweak models

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
