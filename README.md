# GPT model from scratch

**Author**: Gabriel Pišvejc
**Contact**: GabrielPisvejc@Protonmail.com, [LinkedIn](https://www.linkedin.com/in/gabrielpisvejc/?profileId=ACoAADo5FU0BnBPkBj5SmMESVBJ633BazdnsESU)

In this small showcase, I built a small clone of the GPT-2 model by OpenAI using basic PyTorch. See my implementation [here](https://github.com/GabrielZelva/GPT-from-scratch/blob/main/GPT_from_scratch.ipynb). My Deep Learning classes at the [NLP Master's at EHU/UPV](https://www.ehu.eus/en/web/master/master-language-analysis-processing)were a heavy source of knowledge for this exercise. 

## Features

**Full manual implementation of**

- Layer normalisation
- Multi-Headed Self Attention (MHSA) using 4D tensors
- Feed Forward layers
- Transformer blocks
- Decoder-Transformer architecture and usage functions
- Training loop

**Network architecture**

- 124 million parameters
- 50257 tokens in the vocabulary
- Context window of 256 tokens
- 768 dimensional embeddings 
- 12 attention heads
- 12 transformer blocks
