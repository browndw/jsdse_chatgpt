# ChatGPT Project Data-Sharing

Code and data for "Developing Students' Statistical Expertise through Writing in
the Age of AI", by Laura S. DeLuca, Alex Reinhart, Gordon Weinberg, Michael
Laudenbach, Sydney Miller, and David West Brown.

Replication code is provided in `jsdse_chatgpt.qmd`, which can be run and
rendered by [Quarto](https://quarto.org/) to produce the figures and tables in
the paper. Raw data is provided in the `data/` directory:

- `all_intro_stats.tsv`: All introductions professional and ChatGPT-generated
  introductions. (Student introductions cannot be redistributed without the
  consent of the students.)
- `gpt-full-report.txt`: The raw text of the full data analysis report written
  by ChatGPT 4.
- `stats_biber.csv`: Each row is one document from the corpus of introductions;
  each column indicates the calculated Biber feature for that document.
- `stats_freq.csv`: Each row is one token (word). Columns give the absolute
  frequency (count) of the word in each of the three corpora (student,
  published, and ChatGPT), and the relative frequency per 10^5 words.
- `stats_nps.csv`: Each row is a noun phrase extracted from an introduction.
  Columns indicate which introduction, the content of the noun phrase, and the
  position of the start and end of the noun phrase in the introduction.
