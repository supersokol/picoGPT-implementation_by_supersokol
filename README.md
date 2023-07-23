# Supersokol's PicoGPT Implementation Notebook
Based on [this blog post](https://jaykmody.com/blog/gpt-from-scratch/)
Welcome to my PicoGPT Implementation Notebook! 
This repository serves as a demonstration of my understanding of the GPT-2 language model through its implementation. 
By creating this implementation, I aim to showcase my comprehension of the underlying concepts and techniques employed in building language models like GPT.
What is PicoGPT?
[PicoGPT](https://github.com/jaymody/picoGPT) is a scaled-down version of the popular GPT (Generative Pre-trained Transformer) model developed by OpenAI, designed to be more accessible for educational purposes and small-scale projects. While it lacks the vast scale of its big brother, PicoGPT retains many of the essential elements that make GPT so impressive. It operates on the transformer architecture, utilizing attention mechanisms and pre-training on large text corpora to achieve state-of-the-art results in various natural language processing (NLP) tasks. 

The primary objectives of this implementation project are as follows:

* Gain a deeper understanding of the transformer architecture and attention mechanisms.
* Implement PicoGPT and analyze its performance on simple NLP tasks.
* Showcase my coding skills and ability to comprehend ML concepts.

A quick breakdown of each of the files:

* `encoder.py` contains the code for OpenAI's BPE Tokenizer, taken straight from their [gpt-2 repo](https://github.com/openai/gpt-2/blob/master/src/encoder.py).
* `utils.py` contains the code to download and load the GPT-2 model weights, tokenizer, and hyper-parameters. (copied [from](https://github.com/jaymody/picoGPT/blob/main/utils.py))
* `picogpt_implementation_notebook.ipynb` contains the actual GPT model and generation code in blocks which we can easily run.


#### Dependencies 
```bash
pip install -r requirements.txt
```
Tested on `Python 3.7.9`.
