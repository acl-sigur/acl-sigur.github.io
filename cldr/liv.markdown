---
layout: default
title: "CLDR Uralic Latin template"
---

## CLDR core data for $UralicLanguageX$


**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a b c d e f g h i j k l m n o p q r s š t u v w x y z ž å ä ö]` |
| auxiliary characters | `[á à ă â ã ą ā ć č ċ ç ď ð đ é è ê ě ë ė ę ē ğ ǧ ģ ǥ ȟ ħ í î ï İ į ī ı ǩ ķ ĺ ľ ļ ł ń ň ñ ņ ŋ ó ò ô ő õ œ ŕ ř ś ŝ ş ș ß ť ţ ț ŧ ú ù û ů ű ų ū ý ÿ ü ź ż ʒ ǯ þ æ ø]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S T U V W X Y Z Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| plural one example | **{0} $DAY$** |
| plural two example | **{0} $DAYS$** |
| plural other example | **{0} $DAYS$** |
| Country Data and Default Content | **Urj_RU** |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | **UralicLanguageX** is already written in latin script |

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

Like [Finnish](fi.html#Collation), add **X**, sort **Y** after **Z**


## CLDR minimal data for $UralicLanguageX$

**Needed soon after submitting new locale**.

### Required date-time formats


(44+ needed?)
**Check out details of formats from other languages, fill as many as you know
are commonly used.**

#### gregorian calendar

| ID-stuff | |
| -------- | |
| month, 1, wide, format | |
| month, 2, wide, format | |
| month, 3, wide, format | |
| month, 4, wide, format | |
| month, 5, wide, format | |
| month, 6, wide, format | |
| month, 7, wide, format | |
| month, 8, wide, format | |
| month, 9, wide, format | |
| month, 10, wide, format | |
| month, 11, wide, format | |
| month, 12, wide, format | |
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

| **Urj** | |

Country or territory:

| FI |  |
| ET |  |
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

(1 needed)

| datetime format | ... |

### Number formats


#### Symbols

| Character name | Translated version |
| -------------- | ------------------ |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | **FIXME** |
| Time separator (Hours:Minutes) | . |

### Territories, cities  and timezone ID's in language area


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

| Hours from UTC | +H:mm;-H:mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional | |
| regional | |
| regional | |
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

???

## More (all) CLDR data for $language


...

