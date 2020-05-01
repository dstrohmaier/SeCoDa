# SeCoDa [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Repository for the SeCoDa dataset

Main data are found in SeCoDa.tsv. The file is structured as follows.

First column: token to be disambiguated.
Second column: offset start for token in context
Third column: offset end for token in context
Fourth column: context (sentence in which token occurs)
Fifth column: selected sense
Sixth column: comments (also contains MWE information)

Example:

| target  | offset_start | offset_end | context            | sense            | comments |
| ------- |:------------:| ----------:| ------------------:| ----------------:| --------:|
| abroad  | 39           | 45         | As we emerge...    | OTHER COUNTRY... | -        |
| abroad  | 39           | 45         | As we emerge...    | OTHER COUNTRY... | -        |
| abroad  | 73           | 79         | #1-8 The speech... | OTHER COUNTRY... | -        |


The senses are drawn from the [Cambridge Advanced Learner's Dictionary](https://dictionary.cambridge.org).

This work is licensed under a [Creative Commons Attribution-NonCommerial-ShareAlike 4.0
International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
