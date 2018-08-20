# kdd18-RecognizingFilmEntitiesinPodcasts

We propose a Named Entity Recognition (NER) system
to identify film titles in podcast audio. Taking inspiration from NER
systems for noisy text in social media, we implement a two-stage
approach that is robust to computer transcription errors and does
not require significant computational expense to accommodate
new film titles/releases. Evaluating on a diverse set of podcasts,
we demonstrate more than a 20% increase in F1 score across three
baseline approaches when combining fuzzy-matching with a linear
model aware of film-specific metadata.
