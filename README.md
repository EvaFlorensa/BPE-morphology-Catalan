# Byte pair encoding (BPE) and morphology in Catalan
In this project, I will use two BPE algorithms with the aim to study to which extent they align with the traditional notion of a morpheme in Catalan. In order to do that, I will use a text from the Universal Declaration of Human Rights (UDHR) corpus. I will base my code on the repository minbpe from A. Karpathy. With that, I will create and train the two different tokenizers: a basic one and one with regular expressions to split the words. As a result, I will extract the 20 first subwords obtained from the merges.

# Install
In order to run this code, you will need the following:
- urllib.request: to being able to get the text from the link
- regex: for working with regular expressions

# Author
Eva Florensa Villacampa
