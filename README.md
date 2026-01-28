# Art Direction as Data  
## Cultural Analytics of Pedagogical Discourse

This repository presents an exploratory research project that examines a full semester of the course *Art Direction I* by transforming recorded classroom lectures into **cultural data**.

The project is framed within the **Cultural Analytics** approach proposed by **Lev Manovich**, understanding pedagogical discourse as an object that can be explored through computational analysis at scale.

The visualizations produced do not aim to represent the educational phenomenon in its entirety. Instead, they seek to make visible **patterns, variations, and recurrences** that operate as **indexical traces of pedagogical discourse**.

In this context, the word cloud is conceived as a **data-driven cultural image of the classroom**, allowing the observation of aspects of academic discourse that are not always easily detectable through traditional close reading.

---

## Corpus Composition

- Recorded classes from the full semester of *Art Direction I*  
- Audio and video formats (`.wav`, `.mp4`)

---

## Methodology / Workflow

The project follows a two-step pipeline:

1. **Corpus Construction**  
   - Audio and video recordings are transcribed using automatic speech recognition (AssemblyAI).  
   - Speaker labels are preserved to maintain dialogue structure.  
   - All transcriptions are consolidated into a single text corpus.

2. **Exploratory Analysis and Visualization**  
   - Text is tokenized and normalized, removing stopwords and non-alphabetic characters.  
   - Lexical frequencies are calculated and exported as a `.csv` for further analysis.  
   - Word clouds are generated to visualize dominant concepts and patterns in the classroom discourse.

---





