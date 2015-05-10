# Sample subset optimization techniques for imbalanced and ensemble learning problems #

News: a gui version of SSO can be downloaded from http://code.google.com/p/imbalanced-data-sampling/

## Summary ##
Random re-sampling is a popular approach for imbalanced and ensemble learning. However, it does not take into consideration of additional information, such as sample quality and usefulness.

Here we establish sample subset optimization (SSO) as a data driven approach for re-sampling. This approach was initially implemented for imbalanced medical data sampling using particle swarm optimization (PSO) `[1]` (source code and executable available from http://code.google.com/p/imbalanced-data-sampling/). Then, the framework was extended for classifying imbalanced data using an ensemble approach `[2]`. In our recent work `[3]`, we unifying and extending SSO as a generic approach for imbalanced data sampling and ensemble classification. The source code and the executable provided in this project implements the ensemble classification approach described in `[3]`.

## Testable Examples ##
  * Download and unzip `Example dataset.zip` from the [downloads](https://code.google.com/p/sample-subset-optimization/downloads/list)
  * To obtain the general information about the program, issue following command in command line without parameters:
```
    java -jar SSO.jar
```
  * To run SSO on example dataset:
```
    java -jar SSO.jar -t Diabetes_train.arff -e Diabetes_test.arff
```

## References ##
`[1]` P. Yang, L. Xu, BB. Zhou, Z. Zhang, AY. Zomaya, A particle swarm based hybrid system for imbalanced medical data sampling, <font color='blue'><i>BMC Genomics</i></font>, 10:S34, 2009.

`[2]` P. Yang, Z. Zhang, BB. Zhou, AY. Zomaya, Sample subsets optimization for classifying imbalanced biological data, In: <font color='green'><i>Proceedings of the 15th Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD)</i></font>, LNAI 6635, 333-344, 2011.

`[3]` Pengyi Yang, Paul D. Yoo, Juanita Fernando, Bing B. Zhou, Zili Zhang, and Albert Y. Zomaya, Sample subset optimization techniques for imbalanced and ensemble learning problems in bioinformatics applications, <font color='blue'><i>IEEE Transactions on Cybernetics</i></font>, accepted [[PDF](http://sydney.edu.au/engineering/it/~yangpy/publication/SSO%20for%20imbalanced%20and%20ensemble%20learning.pdf)].