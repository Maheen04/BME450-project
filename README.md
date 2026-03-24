# BME450-project
# Title
  MRI-Based Epilepsy Classification Using Convolutional Neural Networks
  
## Team Members
  Maheen Syed (GitHubUserA), Myra Khare (@myrakhare)
  
## Project Description 
Max 1/2 page, include:
- what dataset we plan to use
- goal of the project

- Add references

Epilepsy is a neurological disorder affecting over 50 million people worldwide, characterized by recurrent, unprovoked seizures. [1] Accurate and timely diagnosis is critical for effective treatment planning. However, current diagnostic methods rely heavily on expert interpretation of neuroimaging, specifically structural magnetic resonance imaging (MRI). [2] [3] This process is time-intensive, subjective, and often limited by the availability of trained neurologists, especially in low-resource settings. [3] 

Structural MRI scans can reveal anatomical abnormalities associated with epilepsy, such as cortical dysplasia, hippocampal sclerosis, or lesions.[2] [4] However, these features are often subtle and difficult to detect. [2] [5] As a result, there is a need for automated methods that can assist in identifying imaging biomarkers of epilepsy from MRI data. 

This project aims to develop a deep learning based approach using convolutional neural networks (CNNs) to automatically classify brain MRI scans as epileptic or non-epileptic, building on prior work showing that CNN-based models can discriminate temporal lobe epilepsy from other conditions using T1 weighted MRI. [3] 

By leveraging MRI datasets, the model will learn to extract relevant structural features and provide a probabilistic prediction of epilepsy presence. The goal of the project is to create a reliable and scalable tool that supports clinical decision making, reduces diagnostic variability, and improves access to neurological care through automated image analysis.

To train and evaluate this model, we will use the OpenNeuro ds004199 dataset, a publicly available collection of structural T1-weighted MRI scans from epilepsy patients and healthy controls stored in BIDS format. [6] If additional data is needed to improve model generalizability, we will supplement with MRI data from the ENIGMA Epilepsy Consortium, a large multicenter dataset comprising over 2,000 epilepsy patients across multiple seizure types. [7]

References 

[1] V. L. Feigin et al., “Global, regional, and National Burden of epilepsy, 1990–2021: a Systematic Analysis for the Global Burden of Disease Study 2021,” The Lancet Public Health, vol. 10, no. 3, Feb. 2025, doi: https://doi.org/10.1016/s2468-2667(24)00302-5 

[2] J. Pellinen, E. C. Foster, J. M. Wilmshurst, S. M. Zuberi, and J. French, “Improving Epilepsy Diagnosis across the lifespan: Approaches and Innovations,” The Lancet Neurology, vol. 23, no. 5, pp. 511–521, May 2024, doi: https://doi.org/10.1016/s1474-4422(24)00079-6 

[3] A. J. Chang et al., “MRI-based deep learning can discriminate between temporal lobe epilepsy, Alzheimer’s disease, and healthy controls,” Communications Medicine, vol. 3, no. 1, Feb. 2023, doi: https://doi.org/10.1038/s43856-023-00262-4  

[4] F. Cendes, W. H. Theodore, B. H. Brinkmann, V. Sulc, and G. D. Cascino, “Neuroimaging of Epilepsy,” Handbook of clinical neurology, vol. 136, pp. 985–1014, 2016, doi: https://doi.org/10.1016/B978-0-444-53486-6.00051-X. Available: https://www.ncbi.nlm.nih.gov/pubmed/27430454 

[5] H. Urbach, E. Kellner, N. Kremers, I. Blümcke, and T. Demerath, “MRI of Focal Cortical Dysplasia,” Neuroradiology, vol. 64, no. 3, pp. 443–452, Mar. 2022, doi: https://doi.org/10.1007/s00234-021-02865-x. Available: https://pubmed.ncbi.nlm.nih.gov/34839379/ 

[6] F. Schuch et al., "An open presurgery MRI dataset of people with epilepsy and focal cortical dysplasia type II," Scientific Data, vol. 10, no. 1, p. 475, Jul. 2023, doi: 10.1038/s41597-023-02379-8. [Online]. Available: https://openneuro.org/datasets/ds004199

[7] S. M. Sisodiya et al., "The ENIGMA-Epilepsy working group: Mapping disease from large data sets," Human Brain Mapping, vol. 43, no. 1, pp. 1–16, Jan. 2022, doi: 10.1002/hbm.25037.
