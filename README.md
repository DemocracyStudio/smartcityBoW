# Thematic Bags-of-words (BoW) for Smart-City, CivicTech and Urban Studies topics.
This repo contains a notebook of the creation of Bag-of-words (BoW) from Smart-City and Civic Technology fields.

- smartcity (append smartgrid, iot, urban planning, urban development, innovation)
- civictech (append govtech, opendata, e-citizenship, empowerment)
- infrastructure (append transportation, mobility)
- sustainability (append environment, energy)
- governance (append democracy2.0 + law-related cross-field words)
- entrepreneurship (append economy + business-related cross-field words)

To make my BoW tighter to their topics, I considered many cross-field words, spread in different BoW, and merged them as :
- law => governance
- business => Entrepreneurship
- startup => Entrepreneurship
- technology => smartcity

Process :
1. Scraping tweets on specific hashtag
2. NLP process : Cleaning, Lemmatizing, Tokenizing
3. Creating BoWs of representative unique words in each topic

=> Resulting lexicons can be copy/pasted and used in your code in order to detect urban-science-related words in your text documents, tweets etc. 
