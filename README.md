<h1>Chichewa Word-embeddings</h1>


<h2>Description</h2>
This project is part of the my ongoing PhD work.The primary objective of this work was to generate word embeddings for the Chichewa language that can be used in various NLP applications, including part of speech tagging, named entity recognition, and TTS systems.I intent to use the word emmebdings for fine-tuning SpeechT5 model for Chichewa text systhesis. Since Chichewa has complex morphology, meaning words change form depending on tense, aspect, and subject,Pretrained embeddings (like Word2Vec, FastText, or BERT) for Chichewa may be limited or non-existent, making it necessary to train custom embeddings from scratch.Custom embeddings can better capture linguistic features, improving pronunciation and intonation in TTS output.We used the FastText model to train word embedding on 1,884,405 Chichewa words from scratch.Th courpus used in this project is avaialble upon request, and will be made publicly availble after the thesis is defended.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Fasttex library</b>
  
<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
The model can be accessed on hugging face spaces with gradio intercafe: [here] (https://huggingface.co/spaces/Chithekitale/Chichewa_embeddings) <br/>
<br />




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
