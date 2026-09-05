# Google Ngrams Time-Series Analysis

A Fall 2021 AMS 586 group project analyzing the annual frequency of the word **“peace”** in the English Google Books Ngram corpus.

## Project overview

The analysis retrieves unsmoothed annual data for 1533–2019 and treats the normalized word frequency as a 487-observation time series. It explores:

- stationarity with augmented Dickey–Fuller tests;
- autocorrelation and partial autocorrelation;
- structural change with Bai–Perron breakpoint methods;
- a two-regime Markov-switching model; and
- regime-specific ARIMA models and forecasts.

The work is an exploratory analysis of a corpus-derived frequency series. Changes in word frequency should not be interpreted directly as changes in public opinion, historical conflict, or a causal social process.

## Repository contents

- `PeaceProject.Rmd` — complete R Markdown analysis
- `presentation.pdf` — final presentation

## Contributors

Robert Matsibekker, Kai Li, Cruz Sanchez Hugo, and Thomas Green.
