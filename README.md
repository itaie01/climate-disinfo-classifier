# Climate Disinformation Classifier

This is a classifier made for the [QuotaClimate](https://huggingface.co/datasets/QuotaClimat/frugalaichallenge-text-train) in cooperation with the AI Action Summit in Paris in January 2025. 

Keeping in the spirit of the competition in mind in creating the least costly model, I used `distilroberta-base` for Sequence Classification and fine tuned it on the dataset. In an earlier version, I used a model based on `distilbert-base-uncased`.

In a later iteraiton, I will use codecarbon to track training outputs and also train for longer in an attempt to increase accuracy across all metrics.