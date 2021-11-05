# NLP
Natural Language Processing

A.1 Movie Reviews: A First Vectorized Representation

This first paper in Natural Language Processing (NLP) begins with the very basic idea of
identifying common terms, themes and ideas within a “corpus”, or collection of documents. It is
important that there is a common corpus vocabulary so that information and knowledge are
effectively communicated. With this goal in mind, we embark on analyzing a corpus (200
documents) of movie reviews that have been collected. Our end goal and final application of
analyzing this corpus, while not yet entirely clear, reveals some of the challenges and tools that
result. With the work described in this paper, we have taken the first step towards better NLP by
identifying terms which are good candidates for a useful corpus vocabulary.

A.2 Movie Reviews: Clustering, Topic Modeling, and Sentiment Analysis

Various clustering and topic modeling techniques are explored, with varying results. After recognizing a
distinct trend in the topic models produced across this 200 document corpus, I then turned
attention to developing a method of differentiating Action and Sci-Fi from other types of movie
reviews (Comedy and Horror). The final model developed is based upon a relatively simple
technique known as the Support Vector Machine (SVM), which identifies clear decision
boundaries in high dimensional spaces (Srinivasan, 2021). This SVM model has been shown to
achieve 100% Accuracy in identifying Action and Sci-Fi movie from a Test Set of 30 reviews.

A.3 Movie Reviews: 

This final paper in Natural Language Processing (NLP) focuses on creating ontologies
and identifying “context” via Knowledge Graphs in order to evoke relationships which may exist
between entities in the dataset of 200 movie reviews from our NLP course. The work focuses
specifically on the creation of Ontologies using Stanford’s Protege program, and on the creation
of Knowledge Graphs by using “SpaCy” (see https://spacy.io/), a free, open-source library for
NLP in Python.

Unfortunately, the results that are obtained from experiments conducted during the
course of my research are quite disappointing. The implementation of knowledge graphs, while
shown to be successful when deployed at extremely large scales such as Google’s Knowledge
Graph project, is challenged by the difficulties and subtleties of the written and spoken language
that is contained with corpora (Dery, 2016). So, while a few interesting results are presented in
this research, the overall result is that using knowledge graphs on corpora with many different
styles and approaches (such as appear to be present in our 200 movie reviews) is is not an effective 
means of evoking key concepts from corpora.
