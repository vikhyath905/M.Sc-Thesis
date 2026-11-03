Last login: Tue Sep  1 21:13:14 on ttys000
vicky@Mac ~ % nano ~/Desktop/README_code.txt
UW PICO 5.09       File: /Users/vicky/Desktop/README_code.txt       Modified  



=== CODE GUIDE ===
Thesis: LLM Response Consistency in Hydrometeorological Disaster Response
Author: Vikhyath — SRH Leipzig, September 2026

Run notebooks in this order:

1. FORM_A_QB.ipynb
   Constructs the 100-item question bank from 396 survey responses.

2. QB1=HumAid.ipynb
   Validates the question bank semantically against the HumAID dataset
   using cosine similarity on sentence embeddings.

3. RQ1/RQ1.ipynb
   Main RQ1 analysis — metric divergence between SAS and ROUGE-L,
   consistency scores across models and question types.

4. RQ1/RQ1_Missing_Metrics.ipynb
   Supplementary metric computation for RQ1.

5. RQ2/RQ2_Paraphrase_Consistency.ipynb
   Cross-paraphrase consistency analysis across models.

6. RQ3/RQ3_Temperature_Sweep.ipynb
   Temperature sensitivity analysis for Llama 3.1-8B, Mistral 7B,
   and Llama 4 Scout (0.7 only).

7. LLM_as_Judge.ipynb
   Independent model-based validation of response quality.

=== REQUIREMENTS ===
pip install pandas numpy matplotlib seaborn scikit-learn
sentence-transformers rouge-score bert-score jupyter

   
   

^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Pg   ^K Cut Text  ^C Cur Pos   
^X Exit      ^J Justify   ^W Where is  ^V Next Pg   ^U UnCut Text^T To Spell  
