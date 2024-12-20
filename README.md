# Rare Event Detection in Imbalanced Multi-Class Datasets Using an Optimal MIP-Based Ensemble Weighting Approach - Supplementary Material Section
This repository reproduces the experiments of this AAAI 2025 entitled "Rare Event Detection in Imbalanced Multi-Class Datasets Using an Optimal MIP-Based Ensemble Weighting Approach"

# Abstract
To address the challenges of imbalanced multi-class datasets typically used for rare event detection in critical cyber-physical systems, we propose an optimal, efficient, and adaptable mixed integer programming (MIP) ensemble weighting scheme. 
Our approach leverages the diverse capabilities of the classifier ensemble on a granular per class basis, while optimizing the weights of classifier-class pairs using elastic net regularization for improved robustness and generalization.
Additionally, it seamlessly and optimally selects a predefined number of classifiers from a given set.
We evaluate and compare our MIP-based method against six well-established weighting schemes, using representative datasets and suitable metrics, under various ensemble sizes.
The experimental results reveal that MIP outperforms all existing approaches, achieving an improvement in balanced accuracy ranging from 0.99% to 7.31%, with an overall average of 4.53% across all datasets and ensemble sizes. 
Furthermore, it attains an overall average increase of 4.63%, 4.60%, and 4.61% in macro-averaged precision, recall, and F1-score, respectively, while maintaining computational efficiency.

# Source Code Availability
The complete source code used in this research, including scripts for training and weight computation and inference, is available in this repository to ensures the reproducibility of our results, and provide a practical foundation for further research and development based on our work.

# Prerequisites
1. **Bash** **Shell**: Ensure you have a Bash-compatible shell to execute the script.
2. **Python 3.x:** The script calls several Python scripts. Ensure Python 3 is installed and accessible via python3.
3. **Python Dependencies:** Install any required libraries for the Python scripts. Common dependencies include:
   -> numpy
   -> pandas
   -> scikit-learn
   
# Datasets
1. **LeakDB**: https://zenodo.org/records/13985057
2. **NSL-KDD**: https://www.unb.ca/cic/datasets/nsl.html
3. **SG-MITM**: https://zenodo.org/records/8375657
4. **CIC-IDS2017**: https://www.unb.ca/cic/datasets/ids-2017.html
