---
layout: default
title: "CLDR Uralic Cyrillic template"
---

## CLDR core data for Komi-Zyrian

Check / fill-in.

**Needed for requesting new locale**:


| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[а б в г д е ё ж з и і й к л м н о ӧ п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[ԁ ԃ ј ԉ ԋ ԅ ԇ ԍ ԏ ҵ ӓ ә]` |
| index characters | `[А Б В Г Д Е Ё Ж З И І Й К Л М Н О Ӧ П Р С Т У Ф Х Ц Ч Ш Щ Ъ Ы Ь Э Ю Я]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| plural one example | из {0} книги за {0} день |
| plural few example | из {0} книг за {0} дня |
| plural many example | из {0} книг за {0} дней |
| plural other example | из {0} книги за {0} дня |
| Country Data and Default Content | XXX_RU |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | а:a б:b в:v г:g д:d е:je ё:jo ж:ž з:z и:i й:j к:k л:l м:m н:n о:o п:p р:r с:s т:t у:u ф:f х:h ц:c ч:č ш:š щ:šč ъ:ъ ы:y ь:ь э:e ю:ju я:ja |

### Casing

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName | titlecase |
| currencyName_count | titlecase |
| day_format_except_narrow | lowercase |
| day_narrow | titlecase |
| day_standalone_except_narrow | lowercase |
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
| relative | lowercase |
| script | lowercase |
| territory | titlecase |
| variant | lowercase |
| zone_exemplarCity | titlecase |
| zone_long | titlecase |

### Collation

Like [Russian](ru.html#Collation), add **X**, sort **Y** after **Z**.


## CLDR minimal data for Komi-Zyrian

**Needed soon after submitting new locale**.

### Required date-time formats

**If the calendar used is not gregorian, check other languages for referneces.**

#### gregorian calendar

**Check out detials of these formats from other languages and fill as many as
you know are in common use.**

| ID-stuff | values |
| -------- | ------ |
# These are for month day ordering
| month, 1, wide, format | тӧвшӧр тӧлысь |
| month, 2, wide, format | урасьӧм тӧлысь |
| month, 3, wide, format | рака тӧлысь |
| month, 4, wide, format | косму тӧлысь |
| month, 5, wide, format | ода-кора тӧлысь |
| month, 6, wide, format | лӧдза-номъя тӧлысь |
| month, 7, wide, format | сора тӧлысь |
| month, 8, wide, format | моз тӧлысь |
| month, 9, wide, format | кӧч тӧлысь |
| month, 10, wide, format | йирым тӧлысь |
| month, 11, wide, format | вӧльгым тӧлысь |
| month, 12, wide, format | ӧшым тӧлысь |
| month, 1, abbreviated, stand-alone | твт |
| month, 2, abbreviated, stand-alone | урт |
| month, 3, abbreviated, stand-alone | ркт|
| month, 4, abbreviated, stand-alone | кст |
| month, 5, abbreviated, stand-alone | одт |
| month, 6, abbreviated, stand-alone | лнт |
| month, 7, abbreviated, stand-alone | срт |
| month, 8, abbreviated, stand-alone | мзт |
| month, 9, abbreviated, stand-alone | кчт |
| month, 10, abbreviated, stand-alone | йрт |
| month, 11, abbreviated, stand-alone | влт |
| month, 12, abbreviated, stand-alone | ӧшт |
| (week)day, sun, wide, format | |
| (week)day, mon, wide, format | |
| (week)day, tue, wide, format | |
| (week)day, wed, wide, format | |
| (week)day, thu, wide, format | |
| (week)day, fri, wide, format | |
| (week)day, sat, wide, format | |
| quarter, 1, wide, format | |
| quarter, 2, wide, format | |
| quarter, 3, wide, format | |
| quarter, 4, wide, format | |
| period of day, midnight, wide, format | |
| period of day, am, wide, format | |
| period of day, noon, wide, format | |
| period of day, pm, wide, format | |
| period of day, morning1, wide, format | |
| period of day, morning2, wide, format | |
| period of day, afternoon1, wide, format | |
| period of day, evening1, wide, format | |
| period of day, night1, wide, format | |
| era | |
| date format | |
| time format | |
| datetime format | |
| Timezone | |
| interval format fallback | `{0}–{1}` |


### Important names in language


Language:

| `kpv` |  |

Country or territory (include translations of all main countries language
is spoken):

| FI |  |
| EE |  |
| HU |  |
| RU |  |

Currency:

| , EUR |  |
| one, EUR |  |
| two, EUR |  |
| other, EUR |  |
| , EUR symbol | € |
| narrow, EUR symbol | € |
| , RUB |  |
| one, RUB |  |
| two, RUB |  |
| other, RUB |  |
| , RUB symbol | ₽  |
| narrow, RUB symbol | ₽  |

### Datetime patterns

| datetime format | ... |

### Number formats

| Character name | Translated version |
| -------------- | ------------------ |
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
| Not a number | **FIXME** |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

Country or territory:

| `FI` |  |
| `RU` |  |
| `HU` |  |
| `EE` |  |

Timezone ID:

| Europe/Helsinki | |
| Europe/Moscow | |
| Asia/Tomsk | |
| Europe_Eastern | |
|  generic | |
|  standard | |
|  daylight savings | |
| Moscow | |
|  generic | |
|  standard | |
|  daylight savings | |
| Yekaterinburg | |
|  generic | |
|  standard | |
|  daylight savings | |


### Timezone patterns

| Message | formatting |
| ------- | ---------- |
| Hours from UTC | +H:mm;-H:mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional |  |
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
| `calendar` |  |
| `cf` |  |
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

???

## More (all) CLDR data for $language

TODO
