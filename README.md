# Pretraining GPT-2 with the Harry Potter Books

I performed pretraining using the Harry Potter book dataset to better understand the fundamental principles behind large language models (LLMs). This involved preparing the training data, defining a custom data loader and model architecture, training the model, and analyzing the results.

#### This image visualizes the probability distribution of possible next tokens predicted by the model for the input "Dobby is".

![image](https://github.com/user-attachments/assets/996e150e-a99b-4420-8a80-966509add051)

#### When "Dobby" is given as input, the model generates a 50-token sentence by predicting the next token at each step based on probability, choosing the most likely token at every point.

![Dobby](https://github.com/user-attachments/assets/d0712558-acc0-4dc3-969c-9d6e332bde71)

---

This example was referenced from the HongLabLLM.
