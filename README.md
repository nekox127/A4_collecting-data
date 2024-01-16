# Donald Trump Rallies Speeches

# The corpus
The dataset comprises a comprehensive collection of full speeches delivered by Donald Trump, the 45th President of the United States, during 35 of his political rallies in 2019 and 2020.  
A political rally is a public event where a political figure addresses a gathering of supporters to share their views, promote their agenda, and connect with the audience.  
In the context of Donald Trump's rally speeches, these events were pivotal moments in his political campaigns and presidency, characterized by passionate addresses, policy discussions, and engagement with the crowd. Analyzing these rally speeches provides insights into Trump's communication style, the issues he prioritized, and the sentiments he aimed to evoke among his supporters.
# Target audience and the intended use of the corpus
The target audience for the corpus includes political analysts, NLP researchers, journalists, political campaign strategists, public opinion researchers, educators, and students. The intended use spans political discourse analysis, NLP algorithm development, media coverage assessment, campaign strategy formulation, public opinion research, and educational purposes across various disciplines.  
# Text selection criteria
- Inclusion of Rally Speeches: Only speeches delivered during political rallies were considered, providing a concentrated focus on Trump's communication within the dynamic and charged atmosphere of campaign events.  
- Time Frame: The corpus comprises speeches delivered by Donald Trump during the years 2019 and 2020. This temporal restriction allows for a nuanced examination of his rhetoric during a critical period in his political career.
# The data collection process
The corpus of speeches used in this analysis was meticulously collected from [Kaggle](https://www.kaggle.com/datasets/christianlillelund/donald-trumps-rallies). 
The speeches, available in full length, are provided in TXT (text) file format. 
# Annotations added and tools
At first, Natural Language Processing (NLP) and Python is used to generate Tokenization (splitting text into words/sentences).  
- Lemmas: spaCy, Python  
- Part-of-Speech (POS) Tagging: spaCy, Python  
- Proper Nouns: spaCy, Python  
- Named Entity Recognition: spaCy, Python
- Sentiment Classification: spaCy, Python  
# The description of the columns in the CSV file.  
- Filename: The file name in the 'archive' folder.  
- Document: The original text exactly as it appears in the text file.  
- Text: Preprocessed text of this document.  
- Tokens: Splitting text into pieces called tokens.  
- Lemmas: Lemma is the form of a word as it appears in the dictionary.  
- Parts-of-speech: Part of speech, is a category of words with similar grammatical properties.  
- Proper_Nouns: The name of a particular person, place, organization, or thing in the files.  
- Named_Entities: Named entity labels, providing information about the type of each named entity.
- NE_Words: Real-world entities (location, person, time) mentioned in the text.
- Sentiment:
