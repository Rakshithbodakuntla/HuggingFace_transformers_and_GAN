**Question 1**
Set up a QA system using Hugging Face’s transformers library.

Used a pre-trained model that can read a paragraph and answer questions about it.

🔧 Task Breakdown:
1. Basic Pipeline
Imported the pipeline from Hugging Face.

Gave it a paragraph about Charles Babbage.

Asked: “Who is the father of the computer?”

The model answered: "Charles Babbage", with a confidence score over 0.65.

2. Custom Model
Switched to a different model: deepset/roberta-base-squad2.

Got the same correct answer "Charles Babbage" but with even better confidence (above 0.70).

3. My Own Example
Wrote a short paragraph about Ada Lovelace.

Asked two questions:

“Who is the first programmer?”

“Who did Ada Lovelace work with?”

Got correct answers for both, with high confidence.





**Question 2**

Built a Conditional GAN that generates digits (0–9) from random noise + digit label.

Trained it on the MNIST digit dataset.

Generated one image per digit (0 to 9).
