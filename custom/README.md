# Sources
I'm just an amateur, so I'm sourcing a lot of the info used to create these languages from the internet. Here are my sources.

## Adûnaic

As articles will point out, this language was unfinished by Tolkien. I've reproduced a set of all available consonant combinations from dictionaries I could find. I did not implement grammar rules, partially because they're incomplete and partially because I'm not proficient enough with the tools yet. Note that wikipedia lists phonemical consonants that are not present in available dictionaries (or I just have no idea how to pronounce them, which is more likely) so I left them out. My goal was to create settings that would create a language that sounded like Adunaic and was more easily readable.

- [Ardûnaic Dictionary on RealElvish.net](https://realelvish.net/wordlists/adunaic/dictionary/)
- [IPA Charts on LotR Fandom Wiki](https://lotr.fandom.com/wiki/IPA_charts)
- [Wikipedia Entry on Ardûnaic](https://en.wikipedia.org/wiki/Ad%C3%BBnaic)
- [Long article on Ardûnaic from a site probably made in the 90s](https://folk.uib.no/hnohf/adunaic.htm)

## Ancient Greek

I didn't set this up to use Greek Orthography.

- [Wikipedia Entry on Ancient Greek](https://en.wikipedia.org/wiki/Ancient_Greek)
- [Wikipedia Entry on Ancient Greek Phonology](https://en.wikipedia.org/wiki/Ancient_Greek_phonology)
- [Greek Old Testament Dictionary](https://lexicon.katabiblon.com/index.php?letter=a)

## Atlantean

This language is based on the conlang created for the Disney Film _Atlantis: The Lost Empire_. Currently the phonetics are slightly wrong because there is no way in Vulgarlang to change sounds based on the stressed syllable; the vowel sounds change from `ɔ ɪ ʊ ɘ ɜ` to `o i u a e` on stressed syllables, respectively. The lexicon is minimal so the source is a fan dictionary which uses the movies and phonetical rules as a basis for expanding the available terms.

- [Wikipedia Entry on Atlantean](https://en.wikipedia.org/wiki/Atlantean_language)
- [Okrand's Atlantean Fanonical Dictionary](https://naviklingon.blogspot.com/2015/04/okrands-atlantean-fanonical-dictionary.html)

## Dothraki

This is a language that was included in the tool for a while but was removed after version 9.3.1. I have the original version in the default folder under the correct version but I'll be maintaining it in the current version to make sure it keeps working.

## Draconic

This is based on the D&D Draconic lexicon. Since it's not a conlang, the rules are just derived from the lexicon that's available, which comes from a single article in _Dragon_ magazine. A few rules were created from the content of the article. For some reason the output has a bunch of diphthong diacritics which I didn't include, those can be ignored.

- [Forgotten Realms Wiki Draconic Dictionary](https://forgottenrealms.fandom.com/wiki/Draconic_dictionary)
- [Forgotten Realms Wiki Draconic Language](https://forgottenrealms.fandom.com/wiki/Draconic_language)
- [Dragon Magazine 284 (see page 38-39)](https://archive.org/stream/DragonMagazine260_201801/DragonMagazine284#page/n37/mode/1up)

## Elvish

This is based on the D&D Elvish lexicon. Despite being a phonetic language, it seems to have some pretty dubious rules. I edited it to get to the point that looked somewhat correct. Some combinations, such as aa and ii, were omitted. Diacritics occurred so infrequently that I omitted them.

- [Elvish Dictionary](http://www.candlekeep.com/library/articles/diction_elf.htm)
- [A Treatise on Espruar (the Elvish script)](https://freepdfhosting.com/5f6a747504.pdf)

## Gaelic

This is a _very_ loose interpretation of Scottish Gaelic. The rules for the languge are very complex, and the main part that I deviated was from the different consonant classes (slender vs broad). These classes heavily dictate what the vowels look like, but they were very hard to implement.  I may come back to this later if I figure out the syntax.  I wrote the rules once and they weren't remotely close to working so I set them aside.

- [Wikipedia Entry on Scottish Gaelic Orthography and Phonology](https://en.wikipedia.org/wiki/Scottish_Gaelic_phonology_and_orthography)
- [Wikipedia Entry on Scottish Gaelic Orthography](https://en.wikipedia.org/wiki/Scottish_Gaelic_orthography)

## Giant

This is based on the D&D Giant lexicon. Borrows from Scandinavian language, so I tried to use Scandinavian vowel sounds where possible.

- [Giant Dictionary](https://forgottenrealms.fandom.com/wiki/Giant_dictionary)
- [Giant Language](https://forgottenrealms.fandom.com/wiki/Giant_language)

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

## Maori

Based on the language of the indigenous people of New Zealand.

- [Wikipedia Article on Maori Language](https://en.wikipedia.org/wiki/M%C4%81ori_language)
- [Wikipedia Article on Maori Phonology](https://en.wikipedia.org/wiki/M%C4%81ori_phonology)
- [A Thesis with some old Maori Words](https://ir.canterbury.ac.nz/bitstream/handle/10092/4865/duval_thesis_vol1.pdf)

## Na'Vi

This is based on the language from James Cameron's Avatar. There is a bug currently where the "syllabic consonant" diacritic is not loaded correctly, so you'll have to manually paste the fields into the tool.

- [Na'Vi Dictionary](https://eanaeltu.learnnavi.org/dicts/NaviDictionary.pdf)
- [Wikipedia Entry on Na'Vi](https://en.wikipedia.org/wiki/Na'vi_language)

## Norse

Based on Old Norse.

- [Wikipedia Entry on Old Norse](https://en.wikipedia.org/wiki/Old_Norse)
- [Small Norse Dictionary](http://ydalir.ca/norsedictionary/)
- [Large Norse Dictionary](https://www.vikingsofbjornstad.com/Old_Norse_Dictionary_N2E.shtm)

## Old English

- [Wikipedia Entry on Old English Orthography](https://en.wikipedia.org/wiki/Old_English#Orthography)
- [Wikipedia Entry on Old English Phonology](https://en.wikipedia.org/wiki/Old_English_phonology)
- [Wikipedia IPA Guide for Old English](https://en.wikipedia.org/wiki/Help:IPA/Old_English)
- [The Porety Foundation's Transcription of Beowulf in Old English](https://www.poetryfoundation.org/poems/43521/beowulf-old-english-version)
- [A worksheet from Harvard with some Old English Transliteration Exercises](https://sites.fas.harvard.edu/~eng101/workbook/old-eng/transcription/oe-babel-transcription.pdf)

## Phyrexian

This is the language of the Phyrexians of Magic the Gathering. This language is too incomplete at the moment. This is based on research by reddit users [/u/citrus_inferno](https://www.reddit.com/user/citrus_inferno) and [/u/GuruJ_](https://www.reddit.com/user/GuruJ_) off of a very small sample of phyrexian texts.

- [Consonant Chart for Phyrexian](https://www.reddit.com/r/magicTCG/comments/dfpigy/a_partial_parsing_of_the_phyrexian_alphabet/)
- [Recent Developments on Phyrxian from Jump Start](https://www.reddit.com/r/magicTCG/comments/he2dxn/partial_translation_of_the_phyrexian_swamp_lore/)
- [Guide to Phyrexian 06-25-2020](https://www.reddit.com/r/magicTCG/comments/hfdxtt/guide_to_phyrexian_version_0%CE%B1_20200625/)

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

## Valyrian

This is the language used in George RR Martin's _Song of Ice and Fire_ series. Phonemical consonants from loan words were excluded.

- [Wikipedia Entry on Valyrian](https://en.wikipedia.org/wiki/Valyrian_languages)
- [Partial Valyrian Dictionary](https://xdocs.net/preview/high-valyrian-dictionary-5c671a4702acb)
- [Word Counts for Valyrian](http://dothraki.com/2013/06/kastamiro-daomior/#comment-1854)
- [Swadesh List for Valyrian](https://dothraki.com/wp-content/uploads/2013/12/valyrian_swadesh.pdf)
