# Text Classification Challenge 
_[AI Tinkerers Ottawa](https://ottawa.aitinkerers.org/)_ 

## Introduction 
In this challenge, you’ll perform sentiment analysis of financial Tweets using open-source transformer models. 
This challenge is a great opportunity to explore fine-tuning AI models like BERT and collaborate with other AI Tinkerers in Ottawa. Top teams may be invited to speak at an upcoming AI Tinkerers event. 

Your goal is to classify Tweets from a dataset called [“zeroshot/twitter-financial-news-sentiment.”](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment)
This dataset is split into two portions, “train” and “validation.” You’ll use the train potion for your training data and the validation portion as the test data. 
You’ll be evaluated on the accuracy of your model on the test data.
You can see an example submission under [example_submission.ipynb](example_submission.ipynb).

## Deadlines
1. [Register](https://docs.google.com/forms/d/e/1FAIpQLSdmUfcGAymjV0IVbAFXIO3vwXviM-qa8jGbBxh4R3PV0TA1Qg/viewform) by April 15th 23:59 EDT.
2. [Submit](https://docs.google.com/forms/d/e/1FAIpQLSdynHFDkCf1BCADe557JsMTASv4UWuwD8OSo4HxqvqE7CyEFA/viewform) by May 1st 23:59 EDT.


## Eligibility 
1. You must be willing to attend some in-person AI Tinkerer’s [events](https://lu.ma/ai-tinkerers-ottawa) in Ottawa. 
2. Teams of up to two are allowed. 

## Rules
1. You must only use open-source code and models. No APIs. 
2. Your core text classification model must be a transformer model. Examples include BERT, RoBERTa, and GPT-J.
3. No starting with an already fine-tuned model ([example](https://huggingface.co/nickmuchi/finbert-tone-finetuned-fintwitter-classification)). You must use a foundational model instead like [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased). 
4. No fine-tuning the model with the test data. 
5. No using datasets other than [zeroshot/twitter-financial-news-sentiment](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment). 
6. You must not try multiple model variations on the test data to just select the best. Split the training data into an eval portion if you would like to determine the best model variation before the final test. 
7. In the case of a tie, the winner is whoever submitted first. 

## Submission 
1. Submit by filling out this [form](https://docs.google.com/forms/d/e/1FAIpQLSdynHFDkCf1BCADe557JsMTASv4UWuwD8OSo4HxqvqE7CyEFA/viewform).
2. Your final solution must be contained within a single Jupyter Notebook with all cells showing the process used to compute your final accuracy. All terminal commands and code required to reproduce your results must be present within this file. 
2. The notebook must be published publicly on GitHub. 
3. To ensure the integrity, we may run your notebook to reproduce your accuracy.
4. Your notebook must clearly display its accuracy on the test data along with how it was computed ([example](example_submission.ipynb)).

## Questions 
1. You can ask questions within our [Discord](https://discord.gg/QujqFBg9xZ). You can also find potential team members here. 

## Note
1. This is a casual challenge, and we may change the rules at any time. 

