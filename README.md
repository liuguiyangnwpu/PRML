# PRML
## fpgrowth
* 在算法中使用了一种称为频繁模式树（Frequent Pattern Tree）的数据结构。FP-tree是一种特殊的前缀树，由频繁项头表和项前缀树构成。
* 主要思路是，利用1-item中的频繁模式，对数据中的每个记录中的模式进行排序，得到最有可能的模式，然后构造一棵FPtree和itemtable，通过列表和树可以找到以某个item为后缀的前缀组合，进行分析
* 使用方式直接运行 fpgrowth.py 文件即可，它所以来的数据在data中

## EM algorithm  
* create_config.py --> to use the json file to save the init EM parameter. include Mu and Sigma  
* datagen.py --> to create the datum which obey some distribution  
* EM.py --> acording the json file to estimate the parameter.
* gmm.py --> to create Gaussian distribution datum

## Percepion  
* single training data set  
* batch training data set  
* imply Ho-Kashyap algorithm to training data set  

## InfoGain  
* use information gain and entropy information to classification  
* draw the classification Tree  
* according the metrial about Machine Learning In Action  

## Simplex algorithm  
* you can use .py file to solve some simplex question  
* You can also install glpk or Octave to solve these Linear algorithm  
```
ubuntu install glpk  
sudo apt-get install glpk-some package  
use glpsol to run some question  
glpsol -m description file -o output file 
```
* please format your problem to standard format  

## BP neutral network  
* user can redefine the struct of the neutral network  
* train the test data, we can get follow run info  
```
error 10.33106
error 2.53433
error 2.67919
error 2.68346
error 2.38677
error 2.65445
error 2.38764
error 2.66426
error 2.53938
error 2.58303

Error Samples number is  3
[[array([ 1.2 ,  1.4 , -1.89]), 1, 0],
 [array([ 1.39,  3.16,  2.87]), 2, 0],
 [array([ 0.25,  0.68, -0.99]), 1, 2]]
```

