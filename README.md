# Pre-train, Prompt, Predict


[**Typology**](https://github.com/pfliu-nlp/NLPedia-Pretrain/blob/main/README.md#typology-of-prompting-methods) | 
[**Prompt Paper**](https://github.com/pfliu-nlp/NLPedia-Pretrain/tree/main/prompt_paper) |
[**Interactive Paperlist**](http://explainaboard.nlpedia.ai/leaderboard/prompting/) |
[**Pretrained LM Family**](https://github.com/pfliu-nlp/NLPedia-Pretrain/tree/main/pretrain) |
[**Survey and Website**](http://pretrain.nlpedia.ai/) |
[**Copyright**](https://github.com/pfliu-nlp/NLPedia-Pretrain/blob/main/README.md#copyright-and-acknowledgement)

> Feel free to let us know the missing papers (```issue``` or ```pull request```)

> We highly recommend using the [interactive paperlist]((http://explainaboard.nlpedia.ai/leaderboard/prompting/)) for prompt-based learning.
 
  <img src="./fig/bg.png" width="600" class="center">
 
 


 
## Typology of Prompting Methods


* ### Pre-trained Models ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/plm.pdf))
  * *Left-to-right Language Model*: [\[2\]]() [\[17\]]()
  * *Masked Language Model*: [\[60\]]() [\[2\]]()
  * *Prefix Language Model*: [\[1\]]() [\[2\]]()
  * *Encoder-Decoder*: [\[15\]]() [\[2\]]()
* ### Prompt Engineering ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/template.pdf))
  * *Shape*
    * *Cloze prompt*: [\[7\]]() [\[53\]]()
    * *Prefix prompt*: [\[17\]]() [\[26\]]()
  * *Human Effort*
    * *Hand-crated*
    * *Automated*
        - *Discrete*: [\[24\]]() [\[27\]]()
        - *Continuous*: [\[29\]]() [\[59\]]()
* ### Answer Engineering ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/answer.pdf))
  * *Shape*
    * *Token*: [\[53\]]() [\[7\]]()
    * *Span*: [\[19\]]() [\[22\]]()
    * *Sentence*: [\[17\]]() [\[29\]]()
  * Human Effort
    * *Hand-crated*: [\[1\]]() [\[2\]]()
    * *Automated*
        - *Discrete*: [\[1\]]() [\[2\]]()
        - *Continuous*: [\[1\]]() [\[2\]]()
    
* ### Multi-Prompt Learning ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/multi-prompt.pdf))
  * *Prompt Ensemble*: [\[1\]]() [\[2\]]()
  * *Prompt Augmentation*: [\[1\]]() [\[2\]]()
  * *Prompt Composition*: [\[1\]]() [\[2\]]()
  * *Prompt Decomposition*: [\[1\]]() [\[2\]]()
  * *Prompt Sharing*: [\[1\]]() [\[2\]]()
    
* ### Prompt-based Training Strategies ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/learning.pdf))
  * Parameter Updating
    * *Promptless Fine-tuning*: [\[1\]]() [\[2\]]()
    * *Tuning-free Prompting*: [\[1\]]() [\[2\]]()
    * *Fixed-LM Prompt Tuning*: [\[1\]]() [\[2\]]()
    * *Fixed-prompt LM Tuning*: [\[1\]]() [\[2\]]()
    * *Prompt+LM Tuning*: [\[1\]]() [\[2\]]()
  * Training Sample Size
    * *Zero-shot*: [\[1\]]() [\[2\]]()
    * *Few-shot*: [\[1\]]() [\[2\]]()
    * *Full-data*: [\[1\]]() [\[2\]]()
 
## Copyright and Acknowledgement
* If you aim to use the picture from our github repo or survey, please state the source of these pictures.
* These pictures are drawn by Weizhe and co-designed by Pengfei.
