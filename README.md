# ML Models

## What are types of models models?

- ***Deterministic model:***  A statistical model that determines boundaries in the observed data and uses these boundaries to make decisions or predictions.
- ***Generative model:*** Describes how a dataset is generated in terms of probablistc model and sampling from the model allows to generate new data that did not exist.

---

## Generative Learning Trilemma

It is when we want a generative model to cover 3 aspects/requests
1. ***High Quality Samples:*** The genertive model should be able to generate data as similar as to the realistic dataset
2. ***Fast Sampling:*** The generation process should be of less computation cmplexity - enables real-time applications
3. ***Diversity or Mode Coverage:*** The generation model should be able to capture the range and details of input data well

***The Generative Adveserial Networks fail on Diversity or Mode Coverage*** : [More about GANs](https://github.com/NiketGirdhar22/GAN)

---

## Why is  Diversity Coverage important?

- It is important to the training stage that the generated data represents the original data successfullt
- There may me a chance that the rare samples [which form the long tail of the input distribution] in the dataset be more important than the majority samples.

[Note: It is very difficult for a generative model to maintain all the 3 points in the trilemma]
For generating data that produces high quality samples along with mode covergae, we have diffusion models.

Denoising Diffusion Probablistic Models / Diffusion Models - [Diffusion Model Fundamentals](diffusion_models_overview.md)