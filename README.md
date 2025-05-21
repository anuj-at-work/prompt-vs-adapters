This project compares two efficient fine-tuning strategies for low-resource NER: adapter tuning and prompt-based tuning (prefix-tuning), using the Odia language NER dataset from the Sankalp Bahad NER initiative.

#Aim-
Evaluate which method — adapter tuning or prompt tuning — achieves better performance on Odia NER under constrained training conditions.

#Dataset used- 
- Sankalp Bahad Odia NER, BIO tagged
- 15k samples
- Source: https://github.com/SankalpBahad/IL-NER

#Methodology
-Base: XLM-R
-Adapter tuning (adapters), Prefix-tuning (peft)

