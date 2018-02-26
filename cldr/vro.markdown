---
layout: default
title: "CLDR Võro"
---

## CLDR core data for Uralic

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a b b́ c ć d d́ e f f́ g ǵ h h́ i j k ḱ l ĺ m ḿ n ń o p ṕ q r ŕ s ś š z ź ž t t́ u v v́ w õ ä ö ü x y]` |
| auxiliary characters | `[ʼ á à â å ā æ ç é è ê ë ē í ì î ï ī ñ ó ò ŏ ô ø ō œ ú ù û ū]` |
| index characters | `[A B B́ C Ć D D́ E F F́ G Ǵ H H́ I J K Ḱ L Ĺ M Ḿ N Ń O P Ṕ Q R Ŕ S Ś Š Z Ź Ž T T́ U V V́ Õ Ä Ö Ü X Y]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- , ; \: ! ? . “ „ ( ) \[ \] \{ \} @]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} üüpäiv |
| other example | {0} üüpääväd |XXX
| Country Data and Default Content | vro_EE |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Võro is already written in Latin script |

### Casing

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName | titlecase |
| currencyName_count | titlecase |
| day_narrow | titlecase |
| era_abbr | lowercase |
| era_name | lowercase |
| era_narrow | lowercase |
| key | lowercase |
| keyValue | lowercase |
| language | lowercase |
| metazone_long | titlecase |
| month_format_except_narrow | lowercase |
| month_narrow | titlecase |
| month_standalone_except_narrow | lowercase |
| quarter_abbreviated | titlecase |
| relative | lowercase |
| script | lowercase |
| territory | titlecase |
| zone_exemplarCity | titlecase |
| zone_long | titlecase |

### Collation

Alphabetical order,
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers
Like Estonian, except for nearly every consonant there is also a palatalized consonant immediately following it, i.e.,
.. b b́ c ć d d́ ... f f́ g ǵ h h́ ... k ḱ l ĺ m ḿ n ń ... p ṕ ... r ŕ s ś ... z ź ... t t́ ... v v́ ...

## CLDR minimal data for Uralic

**Needed soon after submitting new locale**.

### Required date-time formats


#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | vahtsõaastakuu |
| month 2 | radokuu |
| month 3 | urbõkuu |
| month 4 | mahlakuu |
| month 5 | lehekuu |
| month 6 | piimäkuu |
| month 7 | hainakuu |
| month 8 | põimukuu |
| month 9 | süküskuu |
| month 10 | rehekuu |
| month 11 | märtekuu |
| month 12 | joulukuu |
| (week)day sun | pühäpäiv |
| (week)day mon | iispäiv |
| (week)day tue | tõõsõpäiv |
| (week)day wed | kolmapäiv |
| (week)day thu | neĺäpäiv |
| (week)day fri | riidi |
| (week)day sat | puulpäiv |
| (week)day sun | pühäpäiv |
| quarter 1 |  |
| quarter 2 |  |
| quarter 3 |  |
| quarter 4 |  |
| period of day midnight |  |
| period of day am |  |
| period of day noon |  |
| period of day pm |  |
| period of day morning1 | |
| period of day morning2 |  |
| period of day afternoon1 |  |
| period of day evening1 |  |
| period of day night1 |  |
| period of day midnight |  |
| period of day am |  |
| period of day noon |  |
| period of day pm |  |
| period of day morning1 | |
| period of day morning2 |  |
| period of day afternoon1 |  |
| period of day evening1 |  |
| period of day night1 | |
| era | |
| era |  |
| era |  |
| era |  |

### Important names in language

Language:

| `vro` | võro |

Country or territory:

| `EE` | Eesti |

Currency:

|  | euro |
| one | euro |
| other | eurot |
|  symbol | € |
| narrow symbol | € |

### Datetime patterns


### Number formats

| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | epäluku |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

TODO

| EE | Eesti |
| | Võro |
| | Obinitsa |
| | Tarto |

### Timezone patterns

| Hours from UTC | +H:mm;-H:mm |
| GMT | GMT {0} |
| Time at Greenwich | GMT |
| regional | ({0}) |
| regional | {0} (+1) |
| regional | {0} (+0) |
| fallback | {1} ({0}) |

### Locale pattern

(how software should display languages)

#### Locale display patterns

| Things | Patterns |
| ------ | -------- |
| language, country | `{0} ({1})` |
| locale, another locale | `{0}, {1}` |
| label: locale | `{0}: {1}` |

### some important words to translate
#### Keys (system names)

| key | Name |
| -------- | ---- |
| `calendar` | |
| `cf` | |
| `colAlternate` | |
| `colBackwards` | |
| `colCaseFirst` | |
| `colCaseLevel` | |
| `collation` | |
| `colNormalization` | |
| `colNumeric` | |
| `colStrength` | |
| `currency` | |
| `hc` | |
| `lb` | |
| `ms` | |
| `numbers` | |
| `timezone` | |
| `va` | |
| `x` | |

### Some time intervals

TODO

## More (all) CLDR data for $language
