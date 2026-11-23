# putplain-uk-wordlists

Ukrainian word lists used by the Putplain app.

## Files

- `uk-targets.txt`: `word<TAB>band`, about 1800 words in frequency order (band 1 to 3).
- `uk-accept.txt`: one word per line, the larger list of accepted words.

## Source

Adapted from [FrequencyWords](https://github.com/hermitdave/FrequencyWords) by Hermit Dave, Copyright (c) 2016 Hermit Dave
(commit `525f9b560de45753a5ea01069454e72e9aa541c6`, files `content/2018/uk/uk_50k.txt` and `content/2018/uk/uk_full.txt`).
FrequencyWords is built from the OpenSubtitles2018 corpus ([OPUS](https://opus.nlpl.eu/OpenSubtitles-v2018.php)),
with subtitles from [opensubtitles.org](http://www.opensubtitles.org/).

## Licence

[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
The full legal code is in `LICENSE`. Provided as-is, without warranties (licence Section 5).

## Changes made

The source files were modified: only lowercase Ukrainian words (no apostrophe), 3 to 8 letters and seen at least
5 times were kept; offensive words, names and likely inflected forms were removed from `uk-targets.txt`; words far
more frequent in the Russian list of the same source were removed from `uk-targets.txt`; counts were replaced with
ranks (bands).
