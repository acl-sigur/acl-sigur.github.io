---
layout: default
title: "Resource matrix"
category: resources
date: 2016-08-05 17:31:24
---

# Resource matrix

This matrix tries to capture state of the Uralic languages computational
resources using linkable, downloadable and usable resources as references
(rather than, expert judgment, as some other similar matrices do)

| ISO 639 | Language | (group) | Orth | Keyboard | Corpora | Speech | Morph | Treebank | MT |
| --- | --- | :-- | --- | --- | --- | --- | --- | --- | --- |
| fin | Finnish |     | ??? | ??? | ??? | ??? | [+][fin-morph-1][+][fin-morph-2][+][fin-morph-3][+][fin-morph-4] | [+][fin-treebank-1][+][fin-treebank-2] | [+][fin-any-1][-][fin-eng-1]  |
| hun | Hungarian |   | ?| ? | ?| ? | ?| ?| ?  |
| est | Estonian |    | ?| ? | ?| ? | ?| ?| ? |
| sme | Sámi | North | ??? | ??? | ??? | ? | ?? | ? | ? |
|  |       | Lule  | ? | ?| ? | ?| ?| ?| ? |
| sma |       | South | ? | ?| ? | ?| ?| ?| ? |
|  |     | Inari   | ? | ?| ? | ?| ?| ?| ? |
| sms |     | Skolt   | ? | ?| ? | ?| ?| ?| ? |
|  |     | Kildin  | ?| ? | ? | ?| ?| ?| ? |
| vro | Võro |        | ?| ? | ?| ?| ? | ?| ? |
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
| krl | Karelian |  | ? | ?| ? | | ?| ?| ? |
| izh |          | Ingrian | ? | ?| ? | | ?| ?| ? |
| olo |          | Olonets | ? | ?| ? | ? | ? | ?| ? |
| | Selkup |        | ? | ? | ?| ? | ? | ?| ? |

# References

We have tried to link all resources while avoiding spamming the list with
derivations and forks of the same resource.

## Finnish

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
2. [GF Finnish to any][fin-any-1]

[fin-morph-1]: https://github.com/flammie/omorfi
[fin-morph-2]: http://voikko.sf.net/
[fin-morph-3]: http://www.grammaticalframework.org/lib/src/finnish/
[fin-morph-4]: https://github.com/aalto-speech/morfessor
[fin-treebank-1]: http://universaldependencies.org/fi/overview/introduction.html
[fin-treebank-2]: http://www.ling.helsinki.fi/kieliteknologia/tutkimus/treebank/
[fin-eng-1]: https://github.com/flammie/apertium-fin-eng
[fin-deu-1]: https://github.com/flammie/apertium-fin-deu
[fin-olo-1]: https://github.com/flammie/apertium-fin-olo
