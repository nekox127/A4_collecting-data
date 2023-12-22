# Donald Trump Rallies Speeches

# The corpus
The dataset contains the full speeches that Donald Trump gave at 35 of his rallies. Ideal for natural language processing and sentiment analysis.
# Target audience and the intended use of the corpus
Professionals studying political discourse and communication may find the dataset valuable for gaining insights into Donald Trump's rhetorical style, key themes, and sentiment during his rallies.
# Text selection criteria
Only speeches on rallies are chosen.
# The data collection process
The speeches are provided as txt files in full length in [Kaggle](https://www.kaggle.com/datasets/christianlillelund/donald-trumps-rallies).
# Annotations added and tools
spaCy is used as the tool to add these annotations:

·Doc

·Tokens

·Lemmas

·POS

·Proper_Nouns

·Named_Entities

# The description of the columns in the CSV file.

·Filename: The file name in the 'archive' folder

·Text: 

·Doc: This object stores not only the original text, but also all of the linguistic annotations obtained when spaCy processed the text.

·Tokens: Splitting text into pieces called tokens.

·Lemmas: Lemma is the form of a word as it appears in the dictionary.

·POS: Part of speech, is a category of words with similar grammatical properties.

·Proper_Nouns: The name of a particular person, place, organization, or thing in the files.

·Named_Entities: Real-world entities (location, person, time) mentioned in the text.

·NE_Words: text tagged with named entities.
