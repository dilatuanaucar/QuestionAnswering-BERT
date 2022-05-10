# QuestionAnswering-BERT
 This repository contains basic deep learning project, Ouesting Answering for Turkish using BERT Model.


# Code
 question_answering_inference.py - This is a wrapper file which has supporting functions to process the input and outputs. In this file, we load the text from the file   path, clean the text (remove the stop words after converting all words to lowercase), convert the text into paragraphs and then pass it on to the answer_prediction function in the question_answering_main.py. The answer_prediction function returns the answers and their probabilities. Then, we filter the answers based on a probability threshold and then display the answers with their probability.

 question_answering_main.py - This file is the main file which has all the functions required to use the pre-trained model and tokenizer to predict the answer given the paragraphs and questions.

# Installation Instructions
 "bert-large-uncased-whole-word-masking-finetuned-squad-pytorch_model.bin" installation from "https://huggingface.co/bert-large-uncased-whole-word-masking-finetuned-squad/blob/main/pytorch_model.bin"
 
# Running Code
First you need to add the text you want to search in the "source.txt" file. Then you can do Question Answering by adding your question in the "question_answering_inference.py" file.
