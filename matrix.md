---
layout: default
title: "Resource matrix"
---

# Introduction

The special interest group for Uralic languages hosts an up-to-date list of
resource for Uralic languages.
This matrix tries to capture state of the Uralic languages computational
resources using linkable, downloadable and usable resources as references
(rather than, expert judgment, as some other similar matrices do). For a
full list of resources available, users are advised to turn to services,
such as [meta-share](http://meta-share.eu).

**Please help us keep the list up-to-date**, send information of new resources
and fixes to current ones to [our ticket tracking system on
github](https://github.com/acl-sigur/acl-sigur.github.io/issues).

# The matrix

The columns are the following:

* **ISO 639:** closest applicable standard language code
* **Language:** the name of the language, in case of related / similarly named languages with separate language codes
* **(group):** is used to add the differentiating part of language name
* **Orth:** describes the status of standard orthography
* **Keyboard:** freely available keyboard layouts for commonly used operation systems available
* **Corpora:** freely available language data, both spoken and written, annotated or not, carefully selected or not
* **Speech:** speech technology resources such as synthesised speakers
* **Morph:** various text analysers; morpho-syntactic or otherwise
* **Treebank:** is for different treebanks and parsebanks with over word-level annotations
* **MT:** machine translators
* **CLDR:** resources available in the Common Language Data Repository

The resources listed are ones that we have
verified free to use, at least for research purposes but usually free for all,
free as in no costs and free as in no restrictions for purposes of use, can
be copyleft. Also, systems must be usable, ideally used by us or researchers we
know.


| ISO 639 | Language | (group) | Orth | Kbd | Corpora | Speech | Morph | Treebank | MT  | CLDR |
| ---     | ---      | :--     | ---  | ---      | ---     | ---    | ---   | ---      | --- | ---  | 
| fin | Finnish |     | ??? | [+][fin-keyboard-1]+++ | ??? | ??? | [+][fin-morph-1][+][fin-morph-2][+][fin-morph-3][+][fin-morph-4] | [+][fin-treebank-1][+][fin-treebank-2] | [+][fin-any-1][-][fin-eng-1]  | + | 
| fkv |  | Kven | ? | ? | ? | ? | ? | ? | ? |  | 
| fit |  | Meänkieli | ? | ? | ? | ? | ? | ? | ? |  | 
| hun | Hungarian |   | ?| ? | ?| ? | [+][hun-morph-1] | ? |? | + | 
| est | Estonian |    | ?| [+][est-keyboard-1] | ?| ? | [+][est-morph-1][+][est-morph-2][+][est-morph-3][+][est-morph-4] | ?| [+][fin-est-1] | + | 
| ekk | (Estonian) |  |  |   |  |   |  |  |   |  | 
| vro | Võro |        | ?| ? | ?| ?| ? | ?| ? |  | 
| sme | Sámi | North | + | [+][sme-keyboard-1][+][sme-keyboard-2] | + | ? | + | ? | + | + | 
| smj |      | Lule  | ? | ?| ? | ?| ?| ?| ? |  | 
| sma |      | South | ? | ?| ? | ?| ?| ?| ? |  | 
| smn |      | Inari   | ? | ?| ? | ?| ?| ?| ? | + | 
| sms |      | Skolt   | ? | ?| ? | ?| ?| ?| ? |  | 
| sjd |      | Kildin  | ?| ? | ? | ?| ?| ?| ? |  | 
| kpv | Komi | Zyrian | ?| ? | ?| ?| ?| ? |  | 
| koi |      | Permyak | ?| ? | ?| ?| ?| ? |  | 
| udm | Udmurt |      | ?| ?| ? | ?| ? | ?| ? |  | 
| mrj | Mari   | Hill | ?| ? | ?| ?| ?| ? |  | 
| mhr |        | Meadow | ?| ? | ?| ?| ?| ? |  | 
| myv | Mordvin | Erzya | ?| ?| ? | ?| ?| ? |  | 
| mdf |         | Moksha | ?| ? | ?| ?|??| ? |  | 
| mns | Mansi   |       | ?| ? | ?| ? | ?| ?| ? |  | 
| kca | Khanty  |       | ?| ? | ?| ? | ?| ?| ? |  | 
| nio | Nganasan |      | ?| ? | ?| ?| ? | ?| ? |  | 
| enh | Enets | Tundra  | ?| ? | ?| ?| ?| ? |  | 
| enf |       | Forest  | ?| ? | ?| ?| ?| ? |  | 
| yrk | Nenets   | Tundra | ?| ? | ?| ?| ?| ? |  | 
| yrk |          | Forest | ?| ? | ?| ?| ?| ? |  | 
| krl | Karelian | Varsinais- | ? | ?| ? | | ?| ?| ? |  | 
| izh |          | Ingrian | ? | ?| ? | | ?| ?| ? |  | 
| olo |          | Olonets | ? | ?| ? | ? | ? | ?| [-][fin-olo-1] |  | 
| sel | Selkup |        | ? | ? | ?| ? | ? | ?| ? |  | 
| vot | Votic |        | ? | ? | ?| ? | [+][vot-morph-1] | ?| ? |  | 

I have used a plus sign **+** for most resources, an occasional hyphen-minus
**-** is used to denote rather work-in-progress versions of data or software.

# References

We have tried to link all resources while avoiding spamming the list with
derivations and forks of the same resource.

## by Language

This is language-index:

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
4. [UralicNLP][fin-morph-4] (uses Omorfi)

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

1. [Official layout][sme-keyboard-1] keyboard layout, for national and international standards

Comes with all common OSes and systems: Microsoft’s, Linux, Apple’s and Android-based.

2. [Divvun’s North Saami keyboard][sme-keyboard-2]

## Hungarian

### Hungarian morphologies

1. [hunmorph][hun-morph-1]

## by Resource

This is resource-type index:

## Orthography

## Keyboards

## Corpora

## Speech technology

## Morphology

* [Omorfi][fin-morph-1] (see also: apertium-fin, giella-fin)
* [Voikko][fin-morph-2] (also: suomi-malaga, vfst morphology)
* [hunmorph][hun-morph-1]
* [GF][gf] (Available: Finnish, Hungarian...)
* [UralicNLP][fin-morph-4] (Available models/data: Finnish, North Saami...)

## Treebanks

## Machine Translation

# Other references

Larger collections:

* [Universal dependencies](http://universaldependencies.org), treebanks,
   dependency syntax conventions for Finnish, Estonian and Hungarian plus other
   world languages (includes [Uralic
   guidelines](http://universaldependencies.org/uralic)
* [Akusanat](https://www.akusanat.com/Main_Page) an online dictionary
* [UralicNLP resources](https://www.uralicnlp.com/) different resources for Uralic languages
* [OPUS open source parallel corpora](http://opus.lingfil.uu.se/) corpora for
   most of the world’s languages
* [Giellatekno](http://giellatekno.uit.no/) repository of uralic analysers and
   tools, most Uralic languages
* [Apertium](http://sf.net/p/apertium), machine translation dictionaries
   including some uralic languages
* [Grammatical Framework](http://grammaticalframework.com/)
   Haskell descriptions of linguistic data, including a few uralic languages
* [Korp at CSC](http://korp.csc.fi/), a corpus search interface
   for CSC.fi-managed corpora
* [Wanca corpora](http://suki.ling.helsinki.fi/wanca/) from SUKI project on
   harvesting internet for Uralic texts
* [Voikko](http://voikko.puimula.org/) spell-checking for many Uralic languages
* [Language bank of Finland](http://kielipankki.fi) a Finland’s central
   repository of language resources
* [Centre for Estonian Language Resources](http://keeleressursid.ee/)
* [Divvun](http://divvun.no) Writers' tools for Saami languages, and lots
  of others



<!-- links: -->

[est-keyboard-1]: http://www.eki.ee/itstandard/2000/keyboard.shtml
[est-morph-1]: http://portaal.eki.ee/tarkvara/
[est-morph-2]: https://github.com/Filosoft/vabamorf
[est-morph-3]: https://github.com/jjpp/plamk
[est-morph-4]: http://www.grammaticalframework.org/lib/src/estonian/
[fin-keyboard-1]: http://kotoistus.fi/nappaimisto/
[fin-morph-1]: https://github.com/flammie/omorfi
[fin-morph-2]: http://voikko.sf.net/
[fin-morph-3]: http://www.grammaticalframework.org/lib/src/finnish/
[fin-morph-4]: https://github.com/mikahama/uralicNLP
[fin-treebank-1]: http://universaldependencies.org/fi/overview/introduction.html
[fin-treebank-2]: http://www.ling.helsinki.fi/kieliteknologia/tutkimus/treebank/
[fin-eng-1]: https://github.com/flammie/apertium-fin-eng
[fin-deu-1]: https://github.com/flammie/apertium-fin-deu
[fin-olo-1]: https://github.com/flammie/apertium-fin-olo
[fin-any-1]: http://www.grammaticalframework.org/
[fin-est-1]: http://divvun.no/doc/lang/est/EstonianDocumentation.html
[hun-morph-1]: http://mokk.bme.hu/resources/hunmorph/
[gf]: http://grammaticalframework.org
[sme-keyboard-1]: http://divvun.no/doc/keyboards/kbdlangdocs/sme/doc/index.html
[sme-keyboard-2]: http://divvun.no/doc/keyboards/kbdlangdocs/sme/doc/index.html
[vot-morph-1]: https://github.com/keeleleek/GF-Votic

