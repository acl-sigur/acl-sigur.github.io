---
layout: default
title: "Resource matrix"
---

# Resource matrix

The special interest group for Uralic languages hosts an up-to-date list of
resource for Uralic languages.
This matrix tries to capture state of the Uralic languages computational
resources using linkable, downloadable and usable resources as references
(rather than, expert judgment, as some other similar matrices do). For a
full list of resources available, users are advised to turn to services,
such as [meta-share](http://meta-share.eu).

The columns are following: *ISO 639* is closest applicable standard language
code, *Language* is the name of the language, in case of related / similarly
named languages with separate language codes, *(group)* is used to add the
differentiating part of language name, *Orth* column describes the status of
standard orthography, *Keyboard* is freely available keyboard layouts for
commonly used operation systems, *Corpora* is freely available language data,
both spoken and written, annotated or not, carefully selected or not, *Speech*
is speech technology resources such as synthesised speakers, *Morph* is for
various text analysers; morpho-syntactic or otherwise, *Treebank* is for
different treebanks and parsebanks with over word-level annotations and
*MT* is for machine translators. The resources listed are ones that we have
verified free to use, at least for research purposes but usually free for all,
free as in no costs and free as in no restrictions for purposes of use, can
be copyleft. Also, systems must be usable, ideally used by us or researchers we
know.

| ISO 639 | Language | (group) | Orth | Keyboard | Corpora | Speech | Morph | Treebank | MT |
| --- | --- | :-- | --- | --- | --- | --- | --- | --- | --- |
| fin | Finnish |     | ??? | [+][fin-keyboard-1]+++ | ??? | ??? | [+][fin-morph-1][+][fin-morph-2][+][fin-morph-3][+][fin-morph-4] | [+][fin-treebank-1][+][fin-treebank-2] | [+][fin-any-1][-][fin-eng-1]  |
| fkv |  | Kven | ? | ? | ? | ? | ? | ? | ? |
| fit |  | Meänkieli | ? | ? | ? | ? | ? | ? | ? |
| hun | Hungarian |   | ?| ? | ?| ? | ?| ?| ?  |
| est | Estonian |    | ?| ? | ?| ? | ?| ?| [+][fin-est-1] |
| ekk | (Estonian) |  |  |   |  |   |  |  |   |
| vro | Võro |        | ?| ? | ?| ?| ? | ?| ? |
| sme | Sámi | North | ??? | [+][sme-keyboard-1] | ??? | ? | ?? | ? | ? |
|  |       | Lule  | ? | ?| ? | ?| ?| ?| ? |
| sma |       | South | ? | ?| ? | ?| ?| ?| ? |
|  |     | Inari   | ? | ?| ? | ?| ?| ?| ? |
| sms |     | Skolt   | ? | ?| ? | ?| ?| ?| ? |
|  |     | Kildin  | ?| ? | ? | ?| ?| ?| ? |
| kpv | Komi | Zyrian | ?| ? | ?| ?| ?| ? |
|     |      | Permyak | ?| ? | ?| ?| ?| ? |
| udm | Udmurt |      | ?| ?| ? | ?| ? | ?| ? |
| | Mari   | Hill | ?| ? | ?| ?| ?| ? |
| |        | Meadow | ?| ? | ?| ?| ?| ? |
| | Mordvin | Erzya | ?| ?| ? | ?| ?| ? |
| |         | Moksha | ?| ? | ?| ?|??| ? |
| | Mansi   |       | ?| ? | ?| ? | ?| ?| ? |
| kca | Khanty  |       | ?| ? | ?| ? | ?| ?| ? |
| nio | Nganasan |      | ?| ? | ?| ?| ? | ?| ? |
| | Enets | Tundra  | ?| ? | ?| ?| ?| ? |
| |       | Forest  | ?| ? | ?| ?| ?| ? |
| | Nenets | Tundra | ?| ? | ?| ?| ?| ? |
| |        | Forest | ?| ? | ?| ?| ?| ? |
| krl | Karelian | Varsinais- | ? | ?| ? | | ?| ?| ? |
| izh |          | Ingrian | ? | ?| ? | | ?| ?| ? |
| olo |          | Olonets | ? | ?| ? | ? | ? | ?| [-][fin-olo-1] |
| | Selkup |        | ? | ? | ?| ? | ? | ?| ? |

I have used a plus sign **+** for most resources, an occasional hyphen-minus
**-** is used to denote rather work-in-progress versions of data or software.

# References by language

We have tried to link all resources while avoiding spamming the list with
derivations and forks of the same resource.

## Finnish

### Finnish keyboard

1. [Kotoistus][fin-keyboard-1] keyboard layout, for national (SFS 5966)
   and international standards

Comes with all common OSes and systems: Microsoft’s, Linux, Apple’s and
Android-based.

### Finnish Morphology

1. [Omorfi][fin-morph-1] (see also: apertium-fin, giella-fin)
2. [Voikko][fin-morph-2] (also: suomi-malaga, vfst morphology)
3. [GF Finnish][fin-morph-3]
4. [Morfessor Finnish][fin-morph-4] (Finnish models available?)

### Finnish Treebanks

1. [Universal Depedencies Finnish][fin-treebank-1] (see also: Turku dependency treebank)
2. [Universal Dependencies Finnish FTB][fin-treebank-2] (see also: FinnTreeBanks)

### Finnish Machine Translation

1. [Apertium Finnish-English][fin-eng-1] (high coverage, low quality)
    * [Apertium Finnish-German][fin-deu-1]
    * [Apertium Finnish-Karelian Olonets][fin-olo-1]
    * [Apertium Finnish-Estonian][fin-est-1]
2. [GF Finnish to any][fin-any-1]

## North Saami

### North Saami keyboards

1. [Divvun’s North Saami keyboard][sme-keyboard-1]


[fin-keyboard-1]: http://kotoistus.fi/nappaimisto/
[fin-morph-1]: https://github.com/flammie/omorfi
[fin-morph-2]: http://voikko.sf.net/
[fin-morph-3]: http://www.grammaticalframework.org/lib/src/finnish/
[fin-morph-4]: https://github.com/aalto-speech/morfessor
[fin-treebank-1]: http://universaldependencies.org/fi/overview/introduction.html
[fin-treebank-2]: http://www.ling.helsinki.fi/kieliteknologia/tutkimus/treebank/
[fin-eng-1]: https://github.com/flammie/apertium-fin-eng
[fin-deu-1]: https://github.com/flammie/apertium-fin-deu
[fin-olo-1]: https://github.com/flammie/apertium-fin-olo
[fin-any-1]: http://www.grammaticalframework.org/
