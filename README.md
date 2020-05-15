# SeCoDa [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Repository for the Sense Complexity Dataset (SeCoDa)


# Paper

For more information on the SeCoDa, see the [paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.730.pdf).

Publications using this dataset must include a reference to the following publication:

<pre>
SeCoDa: Sense Complexity Dataset. David Strohmaier, Sian Gooding, Shiva Taslimipoor, Ekaterina Kochmar. Proceedings of the 12th Conference on Language Resources and Evaluation (LREC 2020), pages 5964–5969, Marseille, 11–16 May 2020
<\pre>

# Repository Content

Main data are found in SeCoDa.tsv. The columns are structured as follows.

1. Token to be disambiguated.
2. Offset start for token in context
3. Offset end for token in context
4. Context (sentence in which token occurs)
5. Selected sense
6. Comments (also contains MWE information)

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
