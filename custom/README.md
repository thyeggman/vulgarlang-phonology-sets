# Sources
I'm just an amateur, so I'm sourcing a lot of the info used to create these languages from the internet. Here are my sources.

## Adûnaic

As articles will point out, this language was unfinished by Tolkien. I've reproduced a set of all available consonant combinations from dictionaries I could find. I did not implement grammar rules, partially because they're incomplete and partially because I'm not proficient enough with the tools yet. Note that wikipedia lists phonemical consonants that are not present in available dictionaries (or I just have no idea how to pronounce them, which is more likely) so I left them out. My goal was to create settings that would create a language that sounded like Adunaic and was more easily readable.

- [Ardûnaic Dictionary on RealElvish.net](https://realelvish.net/wordlists/adunaic/dictionary/)
- [IPA Charts on LotR Fandom Wiki](https://lotr.fandom.com/wiki/IPA_charts)
- [Wikipedia Entry on Ardûnaic](https://en.wikipedia.org/wiki/Ad%C3%BBnaic)
- [Long article on Ardûnaic from a site probably made in the 90s](https://folk.uib.no/hnohf/adunaic.htm)

## Inuktitut

This is the native Inuit language. Many dialects exist but I tried to exclude alternate phonemes present in dialects. This language may also be written using a hat (^) in place of double letters (aa, ii, uu).

- [Wikipedia Entry on Inuktitut](https://en.wikipedia.org/wiki/Inuktitut)
- [Wikipedia Entry on Inuit Grammar](https://en.wikipedia.org/wiki/Inuit_grammar)
- [Wikipedia Entry on Inuit Phonology](https://en.wikipedia.org/wiki/Inuit_phonology)
- [Labrador Virtual Museum Inuktitut-English Dictionary](http://www.labradorvirtualmuseum.ca/inuttut-english.htm)

## Khuzdul

This is the language Tolkien used for dwarves. This language is very similar to Adûnaic but was more well-documented. There are a few sounds Tolkien specifies exist in the language but have no known examples, so to keep to available examples I've left them out.

- [Wikipedia Entry on Khuzdul](https://en.wikipedia.org/wiki/Khuzdul)
- [NYU's Khuzdul Dictionary](http://pages.stern.nyu.edu/~adamodar/ryan/Linguistics/Dictionaries/Dwarvish%20Dictionary.htm)
- [LotRO Wiki Entry on Khuzdul](https://lotro-wiki.com/index.php/Khuzdul)
- [IPA Charts on LotR Fandom Wiki](https://lotr.fandom.com/wiki/IPA_charts)

## Klingon

Klingon is a pretty well fleshed-out language with very complex rules that I don't really understand. I focused on getting the correct consonant sounds in the correct places and on disallowing illegal combinations. Unfortunately, Vulgarlang doesn't like it when you try to restrict vowels at the beginnings of words, so those words should be ignored in whatever output you get, because Klingon words never begin or end with vowels. Setting the "vowel probabilities" to 0 each mitigates the problem but the output still includes some. The syllable patterns are also a bit off. I would suggest just using the words you like and regenerating the language to get more options.

- [Wikipedia Entry on the Klingon Language](https://en.wikipedia.org/wiki/Klingon_language)
- [The Original Klingon Dictionary](https://startrekestonia.ucoz.ru/_fr/0/The-Klingon-Dic.pdf)
- [The Klingon Wiki's Entry on Pronunciation](http://klingon.wiki/En/Pronunciation)

## Old English

- [Wikipedia Entry on Old English Orthography](https://en.wikipedia.org/wiki/Old_English#Orthography)
- [Wikipedia Entry on Old English Phonology](https://en.wikipedia.org/wiki/Old_English_phonology)
- [Wikipedia IPA Guide for Old English](https://en.wikipedia.org/wiki/Help:IPA/Old_English)
- [The Porety Foundation's Transcription of Beowulf in Old English](https://www.poetryfoundation.org/poems/43521/beowulf-old-english-version)
- [A worksheet from Harvard with some Old English Transliteration Exercises](https://sites.fas.harvard.edu/~eng101/workbook/old-eng/transcription/oe-babel-transcription.pdf)

## Phyrexian

This is the language of the Phyrexians of Magic the Gathering. This language is too incomplete at the moment, I don't even have a real vowel set. This is based on research by reddit user [/u/citrus_inferno](https://www.reddit.com/user/citrus_inferno) off of a very small sample of phyrexian texts.

- [Consonant Chart for Phyrexian](https://www.reddit.com/r/magicTCG/comments/dfpigy/a_partial_parsing_of_the_phyrexian_alphabet/)
- [Recent Developments on Phyrxian from Jump Start](https://www.reddit.com/r/magicTCG/comments/he2dxn/partial_translation_of_the_phyrexian_swamp_lore/)

## Quenya

This one was pretty difficult. I tried to stick to the most recent revision of the language. A lot of the spelling rules and illegal combinations are just there to make words "look" right and not for transliteration purposes. I may come back to this with a less exacting approach and just type in the transliterated consonant combinations. Again I left out legal combinations where they do not appear in the available lexicon.

- [Wikipedia Entry on Quenya](https://en.wikipedia.org/wiki/Quenya)
- [Quenya Dictionary from amgar-elderon.com](https://ambar-eldaron.com/telechargements/quenya-engl-A4.pdf)
- [Notes on Quenyan Diacritics](https://middleearthreflections.com/2019/12/05/dots-and-curls-on-the-diacritics-in-quenya-and-sindarin/)
- [IPA Charts on LotR Fandom Wiki](https://lotr.fandom.com/wiki/IPA_charts)

## Sindarin

The language as represented here has a higher rate of acute accent diacritics than the Sindarin lexicon. Another common rule not reflected is the use of the ^ diacritic on vowels in single-syllable words. I couldn't figure out how to enforce that rule.

- [Wikipedia Entry on Sindarin](https://en.wikipedia.org/wiki/Sindarin)
- [Sindarin Dictionary from amgar-eldaron.com](https://www.ambar-eldaron.com/english/downloads/sindarin-english.pdf)
- [IPA Charts on LotR Fandom Wiki](https://lotr.fandom.com/wiki/IPA_charts)