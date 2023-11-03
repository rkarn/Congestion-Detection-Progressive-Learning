# Congestion-Detection-Progressive-Learning

This repository contains the source code to reproduce the outcome of following paper:
- `Karn, Rupesh Raj, Prabhakar Kudva, and Ibrahim M. Elfadel. "Criteria for learning without forgetting in artificial neural networks." In 2019 IEEE International Conference on Cognitive Computing (ICCC), pp. 90-97. IEEE, 2019.`
- `Karn, Rupesh Raj, Prabhakar Kudva, and Ibrahim M. Elfadel. "Learning without forgetting: A new framework for network cyber security threat detection." IEEE Access 9 (2021): 137042-137062.`

This work uses synaptic weight consolidation methodology implemented in 

    https://github.com/ganguli-lab/pathint
    
    Install the python libraries mentioned there.
    
    To run the congestion detection code, please perform following steps:
    1. git clone https://github.com/ganguli-lab/pathint
    2. cd pathint/fig_split_mnist/
    3. Copy all the three ipynb files in "pathint/fig_split_mnist/" directory.

UNSW-NB15 dataset can be downloaded from

    https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/

    Download the UNSW_NB15_training-set.csv and UNSW_NB15_testing-set.csv files.
    
AWID Dataset can be downloaded from 

    http://icsdweb.aegean.gr/awid/download.html 
    
    Download the AWID-ATK-R-Trn and AWID-ATK-R-Tst files. 
    
    Description links:     
    http://icsdweb.aegean.gr/awid/features.html 
    http://icsdweb.aegean.gr/awid/attributes.html
    http://icsdweb.aegean.gr/awid/draft-Intrusion-Detection-in-802-11-Networks-Empirical-Evaluation-of-Threats-and-a-Public-Dataset.pdf
    
NSL-KDD dataset can be downloaded from: 

    https://github.com/defcom17/NSL_KDD 
