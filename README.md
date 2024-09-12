# A Multi-Level Framework for Anomalous Sound Detection via Feature Similarity and Difference
<img src="./overall.png">

## Introduction

Self-supervised classification methods have achieved promising performance in anomalous sound detection (ASD) by leveraging auxiliary classification tasks to learn embedding spaces.However, most of them primarily focus on the intrinsic characteristics of samples, overlooking the similarities and differences in features inter-tasks and inter-samples. In this paper, we propose a multi-level framework that takes into account both task-level and sample-level feature similarities and differences. At the task level, we propose a max divergence loss function $\mathcal{L}_{max}$ by maximize the distance between the feature maps of the section ID and attribute branches.At the sample level, we propose a covariance loss $\mathcal{L}_{cov}$ to reduce intra-class distances and increase inter-class distances.Experiments show that our proposed method has achieved a competitive performance on the development dataset of DCASE 2022 Challenge Task 2. 

