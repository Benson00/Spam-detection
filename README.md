# Spam-detection

This project implements a spam detection system using Multinomial Naive Bayes. The system classifies emails as either spam or non-spam based on both their content and provenance.

The notebook contains three different spam detectors:

- The first detector works exclusively on the content of the emails.
- The second detector works on the content as well, but without considering stop words.
- The third detector uses both the content and provenance of the emails. The provenance is determined by clustering emails based on cosine similarity, which extracts a column representing the email's source.

Each detector is evaluated using a classification report and a confusion matrix.