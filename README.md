For this course, I evaluated the robustness of the Cell2Sentence model under two types of data perturbation:

Poisson Noise Injection — Poisson noise was applied to the expression data to simulate technical noise commonly found in single-cell RNA sequencing, testing how well the model maintains performance under realistic stochastic perturbations.

Block Shuffling — Gene expression values were shuffled within blocks of varying sizes. By increasing the block size, the local gene co-expression structure is progressively disrupted, gradually weakening the linear relationships present in the data. This allowed us to assess how sensitive model performance is to the degradation of structured biological signal.

Together, these experiments provide insight into the model's resilience to random technical noise.
