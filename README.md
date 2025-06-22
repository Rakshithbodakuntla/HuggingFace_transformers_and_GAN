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



**Question 3**

How is a Conditional GAN different from a normal GAN?
A normal GAN just makes random stuff.
A Conditional GAN lets you control what it makes by giving it a label (like “make a 5”).

Real Example: Generating specific clothes by type: "Make a red jacket".


**Question 4**

What does the Discriminator do in image-to-image GANs? Why is matching important?
It checks if the output image matches the input (e.g., a map to a satellite image).
Matching is important because the model must not only make a real-looking image, but it must match the input condition.
