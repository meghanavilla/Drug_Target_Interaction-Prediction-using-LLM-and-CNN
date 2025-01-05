# Drug_Target_Interaction-Prediction-using-LLM-and-CNN
This project aims to develop a hybrid model that integrates the strengths of LLMs and CNNs 
to predict drug-target interactions with greater accuracy. Specifically, we utilize ChemBERTa 
to encode SMILES representations of drug molecules, generating embeddings that capture 
molecular complexity. Concurrently, we employ a CNN architecture to process protein 
sequences, extracting features that represent biologically meaningful patterns. By combining 
these two representations, our model is designed to predict the likelihood of interaction 
between a given drug and protein, classifying each pair as interacting or non-interacting. 
