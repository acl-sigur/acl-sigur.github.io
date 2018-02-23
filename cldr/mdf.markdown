---
layout: default
title: "CLDR Moksha"
---

## CLDR core data for Moksha

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[ԗ ԙ ԕ є ѕ і ў џ ѣ ѡ ѳ ѵ ѷ җ ҥ ä ə]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ъ Ы Ь Э Ю Я]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} ула
| other example | {0} улотне |
| Country Data and Default Content | mdf_RU |
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

Alphabetical order,
Just like Russian, with "е" followed by "ё"

## CLDR minimal data for Finnish

**Needed soon after submitting new locale**.

### Required date-time formats

(44+ needed?)

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | кельмеков |
| month 2 | уфайков |
| month 3 | марайков|
| month 4 | шудиков |
| month 5 | панжиков |
| month 6 | лямбеков |
| month 7 | псиков |
| month 8 | сёроньков |
| month 9 | тюжягов |
| month 10 | кельмазаков |
| month 11 | эйндамков |
| month 12 | кучкаков |
| (week)day sun | |
| (week)day mon | |
| (week)day tue | |
| (week)day wed | |
| (week)day thu | |
| (week)day fri | |
| (week)day sat | |
| quarter 1 |  |
| quarter 2 |  |
| quarter 3 |  |
| quarter 4 | . |
| period of day midnight | |
| period of day am |  |
| period of day noon |  |
| period of day pm |  |
| period of day morning1 | |
| period of day morning2 |  |
| period of day afternoon1  |
| period of day evening1 |  |
| period of day night1 |  |
| period of day midnight |  |
| era BC | ennen Kristuksen syntymää |
| era BCE | ennen ajanlaskun alkua |
| era AD | jälkeen Kristuksen syntymän |
| era ACE | jälkeen ajanlaskun alun |
| date format | `cccc d. MMMM y` |
| time format | `H.mm.ss zzzz` |
| datetime format | `{1} 'klo' {0}` |
| Timezone | {0} {1} |
| interval format fallback | `{0}–{1}` |


### Important names in language

Language:

| `mdf` | мокша |
| `myv` | эрзя |
| `ru` | руз |

Country or territory:

| `RU` | Рузмастор |

Currency:

|  |  |
| one |  |
| other |  |
|  symbol |  |
| narrow symbol |  |

### Datetime patterns

(1 needed)


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
| Time separator (Hours:Minutes) | . |

### Territories and cities in language area

The place names to translate must be in the lists here: XXX

| Asia/Moscow |  |
| `RU` |  |

### Timezone patterns

| Hours from UTC |  |
| GMT |  |
| Time at Greenwich |  |
| regional |  |
| regional |  |
| regional |  |
| fallback |  |

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
| `calendar` | ковгярькс |
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

???

## More (all) CLDR data for Moksha

While not strictly needed is all used by software and stuff:
identity:

