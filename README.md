# Mark-Guesser-Text-Semantic-Extraction-using-Gloves-and-seq2seq-with-attention

# Playground
This notebook is playground for text semantic extraction task and then guess the mark based on extracted semantic.
As input model have sentences with answer gived by person and as output model should guess the mark from 0 to 5 (continious) that evaluate that answer. For training data marks evaluated by experts.

Model is a modification to https://github.com/dongjun-Lee/text-summarization-tensorflow by https://github.com/dongjun-Lee and tutorial by https://github.com/theamrzaki
Model makes embeding using Gloves and then use seq2seq with attention for mark prediction
