# Bert_Fine_Tuning
# Bert is a transformer Model which is very helpful to use for textual data for Sentimental Purpose, NER, Text Classfication text etc.

small pretrained model used in this case study 
model=TFDistilBertForSequenceClassification.from_pretrained('distilbert-base-uncased')
tokenizer=DistilBertTokenizer.from_pretrained('distilbert-base-uncased')
