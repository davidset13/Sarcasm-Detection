# Sarcasm-Detection
This NLP model for the famous Kaggle Sarcasm Detection Dataset achieves 95.3% accuracy without utilizing BERT Transformer Embeddings, solely utilizing free online pretrained GloVe Embeddings.

This model uses the GloVe embeddings and layers an LSTM on top of it.

As far as my current research can gather, for a model that does not utilize BERT, this is the highest performing model of such nature that I can find.
This model utilizes an LSTM like other LLM models, but has key distinct features of its architecture that allow it to outperform similar models.

The extent of these changes can be observed in the architecture, and the simplified training model can be observed in the .ipynb model.
Aside from the hyperparameter tuning and cross-validation procedure, this code includes everything that should be needed for anyone improving on this model.

All code in this repository takes place in Python utilizng the PyTorch library and other imports at the top of the Jupyter Notebook.
Identical results should still be attainable in TensorFlow.

Thanks for reading, and I hope someone can find further ways to improve on this model.
