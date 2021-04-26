# Text Summarization (Abstractive)
This part of the repo contains code for text summarization, the data was obtained [here](https://www.kaggle.com/sunnysai12345/news-summary).

This repo has tested the following frameworks for code:
- Transformers
- SimpleTransformers

The following metrics has been used to evaluate:
- Rogue1
- Rogue2
- Roguel

## TODO
- [x] Inference Script for simple transformers
- [ ] Write down model comparision
- [ ] Fix code for normal transformers to work training 
- [ ] Fix tqdm loader to add loss
- [ ] Fix metric evaluation when running evaluation loop
- [ ] Check and compare using bleu score as well