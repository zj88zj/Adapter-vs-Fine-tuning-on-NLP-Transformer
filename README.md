# Adapter vs Fine-tuning on NLP Transformer
<p>Comparing to domain-adaptive pretraining in BERT transformer, this fine-tuning is replaced with Adapter using AdapterHub API. Our experiment will across four domains and eight classification tasks as the table shown below:</p>
<img width="342" alt="Screen Shot 2021-12-06 at 5 48 29 PM" src="https://user-images.githubusercontent.com/32077985/144969779-48eef733-d9e1-4be5-bc9c-62e0f4bde332.png">

<p>Structure:</p>
<p>This repo contains separated training/prediction codes and traning results for each target tasks. There are also subfolders with tuning codes and outputs under each results forlder for CHEMPROT and SCIERC. Visual is an additional part for visualizations. </p>

<p>Partial Reference:</p>
<ol>Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks. Suchin Gururangan</ol>
<ol>AdapterHub: A Framework for Adapting Transformers. Jonas Pfeiffer</ol>
<ol>Parameter-Efficient Transfer Learning for NLP. Neil Houlsby</ol>
