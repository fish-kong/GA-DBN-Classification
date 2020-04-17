# GA-DBN-Classification
Using MATLAB and DeepBeliefNetworksToolbox to implement a GA-DBN for classification task,  Genetic algorithm（GA） is used to optimize the neuron's number of each hidden-layer
matlab代码。利用DBN实现数据分类，但是因为隐含层节点数不好选择，所以采用遗传算法进行优化选择,需要的加我qq 2919218574 禁止白嫖
1，DBN直接分类
![image](https://github.com/fish-kong/GA-DBN-Classification/blob/master/GA-DBN/dbn.png)
2,GA-DBN分类
2.1 适应度曲线
![image](https://github.com/fish-kong/GA-DBN-Classification/blob/master/GA-DBN/fitness.png)
这个曲线表示 随着GA算法的迭代进化，能够找到的隐含层节点数使得DBN的分类错误率越来越小
2.2 GA-DBN结果
![image](https://github.com/fish-kong/GA-DBN-Classification/blob/master/GA-DBN/ga-dbn.png)
