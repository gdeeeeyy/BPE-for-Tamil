## Bit Pair Encoding for Tamil Language
This project is to create a BPE code for the Tamil Language as the BPE algorithm for the western languages won't really fit the grammar rules of Asian languages.

For Tamil, it follows "Punarchi Vidhi" that allows the language to add two different words to make a completely different word, when combined.

For example, 

    நல்லன்=நன்மை+காற்று
    மூதூர்=முதுமை+ஊர்
    பைங்கொடி=பசுமை+கொடி

I should try to figure out a way to implement this Punarchi Vidhi as code. Implementation of this would help in training of Tamil Large Language models(both Masked and Causal Language Models) 
as this may allow us to properly create pair encodings and helps the transformer model to better understand the embeds of the words.

Maybe I can try making a dictionary of the words with how it looks after splitting the word.
