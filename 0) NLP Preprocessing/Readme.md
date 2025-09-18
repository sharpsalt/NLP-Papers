# NLP Preprocessing

Natural Language Processing (NLP) me raw text ko machine-learning ke liye taiyaar karne ke process ko Preprocessing kehte hain.
Is step ka main goal hai ki text ko clean, structured aur numerical format me convert kiya jaaye jisse algorithms easily use kar saken.

# Steps in NLP Preprocessing
## 1. Text Cleaning

-Raw text me unwanted cheezein hoti hain.
-Lowercasing: "Hello World" → "hello world"
-Remove punctuation: "hello, world!" → "hello world"
-Remove numbers: "I have 2 dogs" → "i have dogs"
-Remove extra spaces: "hello world" → "hello world"

## 2. Tokenization

Text ko chhote-chhote shabdon (tokens) me todna.
"I love NLP" → ["I", "love", "NLP"]

## 3. Stopword Removal

Stopwords = common words jo zyada meaning nahi rakhte (like the, is, at).
"I am learning NLP" → ["learning", "NLP"]

## 4. Normalization (Stemming & Lemmatization)

Stemming → word ko chhota karke root form banata hai
"playing", "played" → "play"
Lemmatization → proper dictionary root form deta hai
"better" → "good"
"running" → "run"

## 5. Text to Numbers (Vectorization)

Computer ko sirf numbers samajh aate hain → text ko convert karna padta hai:
Bag of Words (BoW)
TF-IDF (Term Frequency–Inverse Document Frequency)
Word2Vec / GloVe embeddings
Transformers (BERT, GPT embeddings)

## 6. Task-Specific Preprocessing

Kabhi-kabhi extra steps ki zaroorat hoti hai:
NER (Named Entity Recognition) → proper nouns detect karna (e.g. "India" = country)
Spell correction → "goood" → "good"
Emoji/Slang handling → 🙂 → "smile"
Class imbalance handling (text classification tasks ke liye)
