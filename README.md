Esperanto frequency list based on the 15000 most common words of Tekstaro (Esperanto corpus) ordered by frequency, eventually filtered using ESPDIC with or without English translation.

## Sources

Words are taken from:
- https://en.wiktionary.org/wiki/Wiktionary:Frequency_lists/Esperanto/Tekstaro_2023

ESPDIC is taken from:
- http://www.denisowski.org/Esperanto/ESPDIC/espdic_readme.html
- http://www.denisowski.org/Esperanto/ESPDIC/espdic.txt

## Transformations

1) `EO 15000 Tekstaro` contains the most common Esperanto words from the wiktionary page, in an easy to copy and compute format.
2) `EO 15000 Tekstaro filtered with ESPDIC` contains the same words, but only those who have an entry in ESPDIC. This is to further clean-up the list from proper names and to remove compound words that are overly represented in the corpus.
3) `EO 15000 Tekstaro filtered with ESPDIC with English translation` is the same as the previous document, but with English translations directly included. Format: `Esperanto word : English translation 1, English translation 2`

## License

Due to the licenses of the source materials, the frequency lists in this project are under CC BY-SA 4.0 https://creativecommons.org/licenses/by-sa/4.0/
