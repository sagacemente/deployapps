# Demo di Deploy di App su Hugging Face con Streamlit

LINK HF --> https://huggingface.co/sagax-sagacis
Questo repository contiene due demo per il deploy di applicazioni utilizzando Streamlit e modelli preaddestrati Hugging Face:

## Object Detection: 
Un'applicazione per il rilevamento degli oggetti che utilizza il modello Faster R-CNN di PyTorch per identificare oggetti in immagini.
Sentiment Analysis: Un'applicazione per l'analisi del sentiment che utilizza un modello di classificazione del sentiment preaddestrato per determinare se il testo inserito è positivo o negativo.
Il repository include anche un notebook per il fine-tuning di DistilBERT utilizzando il dataset IMDB per l'analisi sentimentale. Dopo il fine-tuning, il modello viene caricato su Hugging Face Model Hub per la condivisione con la comunità.

## Struttura del Repository
/object_detection: Contiene i file necessari per l'applicazione di rilevamento degli oggetti.
/sentiment_analysis: Contiene i file necessari per l'applicazione di analisi del sentiment.
/fine_tuning_notebook: Contiene il notebook per il fine-tuning di DistilBERT con il dataset IMDB.
/model: Directory contenente il modello fine-tuned di DistilBERT.
README.md: Questo file, che fornisce una panoramica del repository e delle sue funzionalità.

Requisiti
Prima di eseguire le demo o il notebook di fine-tuning, assicurarsi di aver installato i seguenti pacchetti:

Streamlit
PyTorch
Transformers
Istruzioni per l'utilizzo
Object Detection: Esegui streamlit run object_detection/app.py per avviare l'applicazione di rilevamento degli oggetti.
Sentiment Analysis: Esegui streamlit run sentiment_analysis/app.py per avviare l'applicazione di analisi del sentiment.
Fine-Tuning Notebook: Apri e esegui il notebook fine_tuning_notebook/Fine_Tuning_DistilBERT_IMDB.ipynb per eseguire il fine-tuning di DistilBERT con il dataset IMDB e caricare il modello su Hugging Face.
