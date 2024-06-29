# SaulGPT
A "from-scratch solution" to developing and deploying a GPT model

My goal is to create a GPT model from scratch, and deploy it to a web server. This project is a work in progress, and I will be updating it as I go along.

## Creating SaulGPT
I have followed Andrej Karpathy's [Build nanoGPT](https://www.youtube.com/watch?v=l8pRSuU81PU&ab_channel=AndrejKarpathy) tutorial to build a GPT model from scratch. The project has a repo located here: [build nanoGPT](https://github.com/karpathy/build-nanogpt).

The goal was to recreate GPT-2 from scratch, exactly as it was done in the original paper. For the first iteration, I followed the tutorial exactly, and make a first iteration, However, I think I want to improve the architecture to be more like the Llama2/3 architecture, which is a more effective way to train the model.

The model was trained on FineWeb-EDU, a dataset of educational text. The model was trained on a single GPU (RTX 4090) for 10,000 steps, so this is very much undertained. However, the model is able to generate text, and it is able to generate text that is coherent and relevant to the prompt.