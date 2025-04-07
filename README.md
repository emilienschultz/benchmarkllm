# Evaluation of "Extracting Information from Text with Generative Large Language Models"

This repository contains all the scripts and data needed to reproduce the data presented in the article [From Codebooks to Promptbooks: Extracting Information from Text with Generative Large Language Models](https://osf.io/preprints/socarxiv/wjvfq_v1).

Input files are obtained with information extraction by different LLMs (in the `input` folder). The results are metrics evaluating the quality of information extraction compared to a ground truth (in the `output` folder). Human feedback is used to correct some variations (tables in the `feedback` folder).

The protocol is fully detailed in the Jupyter notebook `workflow.ipynb`. 

To use it, install the requirements with `pip install -r requirements.txt`.
