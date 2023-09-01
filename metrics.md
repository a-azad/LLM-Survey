# Commonly used performance metrics in NLP

- **Classification**: Accuracy, precision, recall, F1-score, area under the ROC curve (AUC), and confusion matrix.
- **Sequence labeling**: Precision, recall, F1-score, and confusion matrix.
- **Language modeling**: Perplexity.
- **Machine translation**: BLEU, METEOR, TER, and ROUGE.
- **Question answering**: Accuracy, precision, recall, F1-score, and exact match.
- **Text summarization**: ROUGE, BLEU, and METEOR.
- **Dialog response generation**: Perplexity, F1-score, BLEU, METEOR, ROUGE, and human evaluation.
- **Named entity recognition**: Precision, recall, F1-score, and confusion matrix.
- **Dependency parsing**: UAS (Unlabeled Attachment Score), LAS (Labeled Attachment Score), and F1-score.
- **Sentiment analysis**: Accuracy, precision, recall, F1-score, and confusion matrix.
<br><br>

| Metric      | Brief Explanation |
| ----------- | ----------------- |
| Perplexity  | A metric used to evaluate the quality of language models. It measures how well the model can predict the next word in a sequence given the previous words. Lower perplexity indicates better performance. |
| BLEU        | A metric commonly used to evaluate the quality of machine translation. It measures the similarity between the machine-generated translation and one or more reference translations. Higher BLEU score indicates better performance. |
| METEOR      | A metric used to evaluate the quality of machine translation. It considers both the quality and diversity of the generated translations by measuring the overlap with reference translations and the fluency of the generated sentences. |
| TER         | A metric used to evaluate the quality of machine translation. It measures the edit distance (i.e., the number of insertions, deletions, and substitutions) between the machine-generated translation and one or more reference translations. Lower TER score indicates better performance. |
| ROUGE       | A metric commonly used to evaluate the quality of text summarization. It measures the similarity between the machine-generated summary and one or more reference summaries. Higher ROUGE score indicates better performance. |
| GLUE        | A benchmark for evaluating the performance of LLMs on a range of natural language understanding tasks, including sentiment analysis, textual entailment, and question answering. The overall score is calculated based on the average performance across all tasks. |
| UAS         | A metric used to evaluate the quality of dependency parsing. It measures the percentage of correct head dependencies predicted by the model without considering the type of the dependency label. Higher UAS score indicates better performance. |
| LAS         | A metric used to evaluate the quality of dependency parsing. It measures the percentage of correct head dependencies predicted by the model, considering both the head and the dependency label. Higher LAS score indicates better performance. |
| RACE        | A benchmark for evaluating the performance of LLMs on reading comprehension tasks, where the model must answer questions based on a given passage of text. |

<br> 

| Metric | Description |
|---|---|
| Perplexity | A measure of how well a language model predicts the next word in a sequence. |
| BLEU | A measure of how similar a machine-generated text is to a human-generated text. |
| METEOR | A measure of how similar a machine-generated text is to a human-generated text, taking into account word order and stemming. |
| TER | A measure of the number of edits required to transform a machine-generated text into a human-generated text. |
| ROUGE | A measure of the overlap between a machine-generated text and a human-generated text. |
| GLUE | A set of nine natural language understanding tasks used to evaluate the performance of a language model. |
| UAS | Unlabeled attachment score, a measure of the accuracy of a parser in attaching words to their correct syntactic constituents. |
| LAS | Labeled attachment score, a measure of the accuracy of a parser in attaching words to their correct syntactic constituents, taking into account the correct label for each constituent. |
| RACE | A reading comprehension dataset for evaluating the performance of a language model on social science questions. |
