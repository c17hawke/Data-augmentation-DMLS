# Data-Augmentation

It is a family of techniques to increase the amount of training data

There are 3 kinds of data augmentation techniques as per the author -

1. Simple label-preserving transformation
2. Perturbation
3. Data synthesis

|  | Simple label-preserving transformation | Perturbation | Data synthesis |
| --- | --- | --- | --- |
| What? | Random modification of data while preserving the label. | Adding noise to the data while preserving the label. | Use GANs to generate synthetic data. Can use costly DALL-E-like services as well. |
| Examples in CV | Random flipping, Random rotation, etc. | Adding noise patches, or changing a single pixel values | Using CycleGAN to synthesize or generate new samples. |
| Examples in NLP | Replacing words in a sentence with its synonyms | Adding random symbols, or words in a sentence  | Using templating to generate new samples |
| Why? | Increase training sample per label/class | To improve model performance as well as evaluate model performance (i.e. How good is our model to adversarial attacks) | Increase training data using GAN techniques. |

---

## Example notebooks -

- Example notebooks for CV - [link](https://github.com/c17hawke/Data-augmentation-DMLS/tree/main/notebooks/CV)
- Example notebooks for NLP - [link](https://github.com/c17hawke/Data-augmentation-DMLS/tree/main/notebooks/NLP)

## References -

- [1] Huyen, C. (2022). Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications
