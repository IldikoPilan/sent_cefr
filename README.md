# sent_cefr
A small corpus of Swedish sentences with second language (L2) learning level annotations. The levels follow the scale of the Common European Framework of Reference for Languages ([CEFR] (https://www.coe.int/en/web/common-european-framework-reference-languages/level-descriptions)).

Sentences numbered 1-285 are corpus examples collected from Korp from generic Swedish corpora (e.g. newspaper texts and novels). The CEFR level annotations are derived from the user evaluation of a corpus example selection system, [HitEx] (https://spraakbanken.gu.se/larka/hitex), where L2 Swedish teachers evaluated the sentences and their atomatically assigned CEFR levels. For more information about the user evaluation see this [paper] (http://www.atala.org/content/candidate-sentence-selection-language-learning-exercises-comprehensive-framework-empirical). 

The sentences included in this dataset have been filtered for their well-formedness, independence from the rest of their textual context and some additional lexical and structural criteria (e.g. abbreviations, interrogative
form) using HitEx. From the original evaluation data only those sentences have been included that: (i) that were found overall
suitable (with an evaluation score >= 2.5 out of 4); and (ii) where a majority of teachers agreed with the CEFR level assigned automatically by our system.

Sentences 286-375 are individually occurring sentences collected from the [COCTAILL corpus] (https://spraakbanken.gu.se/eng/resource/coctaill) consisting of L2 Swedish coursebook texts.

Number of sentences per CEFR level in the resource:
⋅⋅* A1 8 + 90 (from COCTAILL)
⋅⋅* A2 81
⋅⋅* B1 59
⋅⋅* B2 92
⋅⋅* C1 45

The resource can be easily equipped with a wide variety of linguistic annotations using the [Sparv] (https://spraakbanken.gu.se/sparv/) pipeline (both via a GUI or an API).
