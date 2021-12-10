# petal_beethoven_diabelli-variations
data sets for performance analyses of Ludwig van Beethoven’s 'Diabelli Variations' (1823)

This repository introduces the data sets created during research on recorded performances of Ludwig van Beethoven’s 'Diabelli Variations' (1823). It complements the following article:

Glaser, Thomas. 2021. “Formgestaltung aus aufführungspraktischer Perspektive. Zur Interpretationsgeschichte von Beethovens 33 Veränderungen über einen Walzer von A. Diabelli op. 120.” *Zeitschrift der Gesellschaft für Musiktheorie* 18. Special Issue: *Musikalische Interpretation als Analyse. Historische, empirische und analytische Annäherungen an Aufführungsstrategien musikalischer Zyklen*: 253–285. https://doi.org/10.31751/1128

**main content**

The data discussed in Glaser 2021 refer to 66 different recordings of Beethoven's 'Diabelli Variations' as detailed in the article's discography (https://storage.gmth.de/zgmth/media/1128/Glaser_Diabelli_Tab07.pdf).

**(1) raw data (66 recordings)**

The Excel sheet "Diabelli Variations_raw data_tpo-dur_66 rec" (https://github.com/petal2020/petal_beethoven_diabelli-variations/blob/main/Diabelli%20Variations_raw%20data_tpo-dur_66%20rec.xlsx) contains duration measurements and tempo values of 66 recordings in separate worksheets. For each pianist, there are two worksheets containing (1) the durations of the theme and the 33 variations as well as the total duration of a recording and (2) the initial tempi within formal units that range between 4 and 12 bars (see Glaser 2021, Tab. 3a).

**(2) durations, percentage values, initial tempo values, repeats (66 recordings)**

The tsv-files provide detailed data on each pianist and recording (file names indicate specific data content):

"_dur": absolute durations (theme and 33 variations; full durations);

"_%val" : percentage values of the theme and each variation of the full duration of the respective recording;

"_tpo": initial tempo values.

Minimum and maximum values of each of the aforementioned data category are included in separate files ("_min-max") as well as an overview of the repeats composed by Beethoven and the pianists's choices of these repeats ("_repeats"). Four recordings (Anda 1961, Lefébure 1975, Rangell 1977, Varsano 1980) with idiosyncratic readings of the score in terms of textual fidelity to the repeats are included according to their "real" and "virtual" durations and percentage values (see also Glaser 2021, Fig. 1 and 2).
