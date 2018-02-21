---
layout: default
title: "CLDR English (via LDML2markdown)"
---

## CLDR core data for English

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a b c d e f g h i j k l m n o p q r s t u v w x y z]` |
| auxiliary characters | `[á à ă â å ä ã ā æ ç é è ĕ ê ë ē í ì ĭ î ï ī ñ ó ò ŏ ô ö ø ō œ ú ù ŭ û ü ū ÿ]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S T U V W X Y Z]` |
| numbers characters | `[\- , . % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ’ " “ ” ( ) \[ \] § @ * / \& # † ‡ ′ ″]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} day |
| other example | {0} days |
| Country Data and Default Content | en_US |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | English is already written in latin script |

### Casing

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName | titlecase |
| currencyName_count | titlecase |
| day_format_except_narrow | titlecase |
| day_narrow | titlecase |
| day_standalone_except_narrow | titlecase |
| era_abbr | titlecase |
| era_name | titlecase |
| era_narrow | titlecase |
| key | titlecase |
| keyValue | titlecase |
| language | titlecase |
| metazone_long | titlecase |
| month_format_except_narrow | titlecase |
| month_narrow | titlecase |
| month_standalone_except_narrow | titlecase |
| quarter_abbreviated | titlecase |
| relative | lowercase |
| script | titlecase |
| territory | titlecase |
| variant | titlecase |
| zone_exemplarCity | titlecase |
| zone_long | titlecase |
| zone_short | titlecase |

### Collation

Alphabetical order,
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers

## CLDR minimal data for English

**Needed soon after submitting new locale**.

### Required date-time formats


#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | Jan |
| month 2 | Feb |
| month 3 | Mar |
| month 4 | Apr |
| month 5 | May |
| month 6 | Jun |
| month 7 | Jul |
| month 8 | Aug |
| month 9 | Sep |
| month 10 | Oct |
| month 11 | Nov |
| month 12 | Dec |
| month 1 | January |
| month 2 | February |
| month 3 | March |
| month 4 | April |
| month 5 | May |
| month 6 | June |
| month 7 | July |
| month 8 | August |
| month 9 | September |
| month 10 | October |
| month 11 | November |
| month 12 | December |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | A |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | S |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| (week)day sun | Sun |
| (week)day mon | Mon |
| (week)day tue | Tue |
| (week)day wed | Wed |
| (week)day thu | Thu |
| (week)day fri | Fri |
| (week)day sat | Sat |
| (week)day sun | Su |
| (week)day mon | Mo |
| (week)day tue | Tu |
| (week)day wed | We |
| (week)day thu | Th |
| (week)day fri | Fr |
| (week)day sat | Sa |
| (week)day sun | Sunday |
| (week)day mon | Monday |
| (week)day tue | Tuesday |
| (week)day wed | Wednesday |
| (week)day thu | Thursday |
| (week)day fri | Friday |
| (week)day sat | Saturday |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | W |
| (week)day thu | T |
| (week)day fri | F |
| (week)day sat | S |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1st quarter |
| quarter 2 | 2nd quarter |
| quarter 3 | 3rd quarter |
| quarter 4 | 4th quarter |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| period of day midnight | midnight |
| period of day am | AM |
| period of day am | am |
| period of day noon | noon |
| period of day pm | PM |
| period of day pm | pm |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | mi |
| period of day am | a |
| period of day noon | n |
| period of day pm | p |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day am | am |
| period of day noon | noon |
| period of day pm | PM |
| period of day pm | pm |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day noon | noon |
| period of day pm | PM |
| period of day morning1 | morning |
| period of day afternoon1 | afternoon |
| period of day evening1 | evening |
| period of day night1 | night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day noon | noon |
| period of day pm | PM |
| period of day morning1 | morning |
| period of day afternoon1 | afternoon |
| period of day evening1 | evening |
| period of day night1 | night |
| era | Before Christ |
| era | Before Common Era |
| era | Anno Domini |
| era | Common Era |
| era | BC |
| era | BCE |
| era | AD |
| era | CE |
| era | B |
| era | A |
| date format | `EEEE, MMMM d, y` |
| date format | `MMMM d, y` |
| date format | `MMM d, y` |
| date format | `M/d/yy` |
| time format | `h:mm:ss a zzzz` |
| time format | `h:mm:ss a z` |
| time format | `h:mm:ss a` |
| time format | `h:mm a` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `MMM d, y G` |
| date format `GyMMMEd` | `E, MMM d, y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `hmsv` | `h:mm:ss a v` |
| date format `Hmsv` | `HH:mm:ss v` |
| date format `hmv` | `h:mm a v` |
| date format `Hmv` | `HH:mm v` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `MMMMW` | `'week' W 'of' MMMM` |
| date format `MMMMW` | `'week' W 'of' MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `M/y` |
| date format `yMd` | `M/d/y` |
| date format `yMEd` | `E, M/d/y` |
| date format `yMMM` | `MMM y` |
| date format `yMMMd` | `MMM d, y` |
| date format `yMMMEd` | `E, MMM d, y` |
| date format `yMMMM` | `MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
| Day | {0} ({2}: {1}) |
| Day-Of-Week | {0} {1} |
| Era | {0} {1} |
| Hour | {0} ({2}: {1}) |
| Minute | {0} ({2}: {1}) |
| Month | {0} ({2}: {1}) |
| Quarter | {0} ({2}: {1}) |
| Second | {0} ({2}: {1}) |
| Timezone | {0} {1} |
| Week | {0} ({2}: {1}) |
| Year | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `y – y` |
| interval format `yM` | `M/y – M/yM/y – M/y` |
| interval format `yMd` | `M/d/y – M/d/yM/d/y – M/d/yM/d/y – M/d/y` |
| interval format `yMEd` | `E, M/d/y – E, M/d/yE, M/d/y – E, M/d/yE, M/d/y – E, M/d/y` |
| interval format `yMMM` | `MMM – MMM yMMM y – MMM y` |
| interval format `yMMMd` | `MMM d – d, yMMM d – MMM d, yMMM d, y – MMM d, y` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, yE, MMM d – E, MMM d, yE, MMM d, y – E, MMM d, y` |
| interval format `yMMMM` | `MMMM – MMMM yMMMM y – MMMM y` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, MMMM d, y G` |
| date format | `MMMM d, y G` |
| date format | `MMM d, y G` |
| date format | `M/d/y GGGGG` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `MMM d, y G` |
| date format `GyMMMEd` | `E, MMM d, y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `ms` | `mm:ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M/y GGGGG` |
| date format `yyyyMd` | `M/d/y GGGGG` |
| date format `yyyyMEd` | `E, M/d/y GGGGG` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `MMM d, y G` |
| date format `yyyyMMMEd` | `E, MMM d, y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| Day | {0} ({2}: {1}) |
| Day-Of-Week | {0} {1} |
| Era | {0} {1} |
| Hour | {0} ({2}: {1}) |
| Minute | {0} ({2}: {1}) |
| Month | {0} ({2}: {1}) |
| Quarter | {0} ({2}: {1}) |
| Second | {0} ({2}: {1}) |
| Timezone | {0} {1} |
| Week | {0} ({2}: {1}) |
| Year | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `y – y G` |
| interval format `yM` | `M/y – M/y GGGGGM/y – M/y GGGGG` |
| interval format `yMd` | `M/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGG` |
| interval format `yMEd` | `E, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGG` |
| interval format `yMMM` | `MMM – MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `MMM d – d, y GMMM d – MMM d, y GMMM d, y – MMM d, y G` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, y GE, MMM d – E, MMM d, y GE, MMM d, y – E, MMM d, y G` |
| interval format `yMMMM` | `MMMM – MMMM y GMMMM y – MMMM y G` |

### Important names in language

Language:

| `en` | English |

Country or territory:

| `US` | United States |
| `US` | US |

Currency:

|  | US Dollar |
| one | US dollar |
| other | US dollars |
|  symbol | $ |

### Datetime patterns

| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `MMM d, y G` |
| date format `GyMMMEd` | `E, MMM d, y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `ms` | `mm:ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M/y GGGGG` |
| date format `yyyyMd` | `M/d/y GGGGG` |
| date format `yyyyMEd` | `E, M/d/y GGGGG` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `MMM d, y G` |
| date format `yyyyMMMEd` | `E, MMM d, y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| Day | {0} ({2}: {1}) |
| Day-Of-Week | {0} {1} |
| Era | {0} {1} |
| Hour | {0} ({2}: {1}) |
| Minute | {0} ({2}: {1}) |
| Month | {0} ({2}: {1}) |
| Quarter | {0} ({2}: {1}) |
| Second | {0} ({2}: {1}) |
| Timezone | {0} {1} |
| Week | {0} ({2}: {1}) |
| Year | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `y – y G` |
| interval format `yM` | `M/y – M/y GGGGGM/y – M/y GGGGG` |
| interval format `yMd` | `M/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGG` |
| interval format `yMEd` | `E, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGG` |
| interval format `yMMM` | `MMM – MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `MMM d – d, y GMMM d – MMM d, y GMMM d, y – MMM d, y G` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, y GE, MMM d – E, MMM d, y GE, MMM d, y – E, MMM d, y G` |
| interval format `yMMMM` | `MMMM – MMMM y GMMMM y – MMMM y G` |

### Number formats

| Character name | Translated version |
| Decimal separator | . |
| "Thousands" separator | , |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | NaN |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| regional | {0} Time |
| regional | {0} Daylight Time |
| regional | {0} Standard Time |
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
| `calendar` | Calendar |
| `cf` | Currency Format |
| `colAlternate` | Ignore Symbols Sorting |
| `colBackwards` | Reversed Accent Sorting |
| `colCaseFirst` | Uppercase/Lowercase Ordering |
| `colCaseLevel` | Case Sensitive Sorting |
| `collation` | Sort Order |
| `colNormalization` | Normalized Sorting |
| `colNumeric` | Numeric Sorting |
| `colReorder` | Script/Block Reordering |
| `colStrength` | Sorting Strength |
| `currency` | Currency |
| `d0` | Transform Destination |
| `em` | Emoji Presentation Style |
| `fw` | First day of week |
| `h0` | Mixed-in Language |
| `hc` | Hour Cycle (12 vs 24) |
| `i0` | Input Method |
| `k0` | Keyboard |
| `kv` | Highest Ignored |
| `lb` | Line Break Style |
| `lw` | Line Breaks In Words Setting |
| `m0` | Transform Rules |
| `ms` | Measurement System |
| `numbers` | Numbers |
| `rg` | Region For Supplemental Data |
| `s0` | Transform Source |
| `sd` | Region Subdivision |
| `ss` | Sentence Break Suppressions Type |
| `t0` | Machine Translated |
| `timezone` | Time Zone |
| `va` | Locale Variant |
| `x` | Private-Use |
| `x0` | Private-Use Transform |

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13904 $en
```
#### Locale display patterns
| Things | Patterns |
| ------ | -------- |
| language, country | `{0} ({1})` |
| locale, another locale | `{0}, {1}` |
| label: locale | `{0}: {1}` |
### Language names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `aa` | Afar |
| `ab` | Abkhazian |
| `ace` | Achinese |
| `ach` | Acoli |
| `ada` | Adangme |
| `ady` | Adyghe |
| `ae` | Avestan |
| `aeb` | Tunisian Arabic |
| `af` | Afrikaans |
| `afh` | Afrihili |
| `agq` | Aghem |
| `ain` | Ainu |
| `ak` | Akan |
| `akk` | Akkadian |
| `akz` | Alabama |
| `ale` | Aleut |
| `aln` | Gheg Albanian |
| `alt` | Southern Altai |
| `am` | Amharic |
| `an` | Aragonese |
| `ang` | Old English |
| `anp` | Angika |
| `ar` | Arabic |
| `ar_001` | Modern Standard Arabic |
| `arc` | Aramaic |
| `arn` | Mapuche |
| `aro` | Araona |
| `arp` | Arapaho |
| `arq` | Algerian Arabic |
| `ars` | Najdi Arabic |
| `arw` | Arawak |
| `ary` | Moroccan Arabic |
| `arz` | Egyptian Arabic |
| `as` | Assamese |
| `asa` | Asu |
| `ase` | American Sign Language |
| `ast` | Asturian |
| `av` | Avaric |
| `avk` | Kotava |
| `awa` | Awadhi |
| `ay` | Aymara |
| `az` | Azerbaijani |
| `az` | Azeri |
| `ba` | Bashkir |
| `bal` | Baluchi |
| `ban` | Balinese |
| `bar` | Bavarian |
| `bas` | Basaa |
| `bax` | Bamun |
| `bbc` | Batak Toba |
| `bbj` | Ghomala |
| `be` | Belarusian |
| `bej` | Beja |
| `bem` | Bemba |
| `bew` | Betawi |
| `bez` | Bena |
| `bfd` | Bafut |
| `bfq` | Badaga |
| `bg` | Bulgarian |
| `bgn` | Western Balochi |
| `bho` | Bhojpuri |
| `bi` | Bislama |
| `bik` | Bikol |
| `bin` | Bini |
| `bjn` | Banjar |
| `bkm` | Kom |
| `bla` | Siksika |
| `bm` | Bambara |
| `bn` | Bangla |
| `bo` | Tibetan |
| `bpy` | Bishnupriya |
| `bqi` | Bakhtiari |
| `br` | Breton |
| `bra` | Braj |
| `brh` | Brahui |
| `brx` | Bodo |
| `bs` | Bosnian |
| `bss` | Akoose |
| `bua` | Buriat |
| `bug` | Buginese |
| `bum` | Bulu |
| `byn` | Blin |
| `byv` | Medumba |
| `ca` | Catalan |
| `cad` | Caddo |
| `car` | Carib |
| `cay` | Cayuga |
| `cch` | Atsam |
| `ccp` | Chakma |
| `ce` | Chechen |
| `ceb` | Cebuano |
| `cgg` | Chiga |
| `ch` | Chamorro |
| `chb` | Chibcha |
| `chg` | Chagatai |
| `chk` | Chuukese |
| `chm` | Mari |
| `chn` | Chinook Jargon |
| `cho` | Choctaw |
| `chp` | Chipewyan |
| `chr` | Cherokee |
| `chy` | Cheyenne |
| `ckb` | Central Kurdish |
| `co` | Corsican |
| `cop` | Coptic |
| `cps` | Capiznon |
| `cr` | Cree |
| `crh` | Crimean Turkish |
| `crs` | Seselwa Creole French |
| `cs` | Czech |
| `csb` | Kashubian |
| `cu` | Church Slavic |
| `cv` | Chuvash |
| `cy` | Welsh |
| `da` | Danish |
| `dak` | Dakota |
| `dar` | Dargwa |
| `dav` | Taita |
| `de` | German |
| `de_AT` | Austrian German |
| `de_CH` | Swiss High German |
| `del` | Delaware |
| `den` | Slave |
| `dgr` | Dogrib |
| `din` | Dinka |
| `dje` | Zarma |
| `doi` | Dogri |
| `dsb` | Lower Sorbian |
| `dtp` | Central Dusun |
| `dua` | Duala |
| `dum` | Middle Dutch |
| `dv` | Divehi |
| `dyo` | Jola-Fonyi |
| `dyu` | Dyula |
| `dz` | Dzongkha |
| `dzg` | Dazaga |
| `ebu` | Embu |
| `ee` | Ewe |
| `efi` | Efik |
| `egl` | Emilian |
| `egy` | Ancient Egyptian |
| `eka` | Ekajuk |
| `el` | Greek |
| `elx` | Elamite |
| `en` | English |
| `en_AU` | Australian English |
| `en_CA` | Canadian English |
| `en_GB` | British English |
| `en_GB` | UK English |
| `en_US` | American English |
| `en_US` | US English |
| `enm` | Middle English |
| `eo` | Esperanto |
| `es` | Spanish |
| `es_419` | Latin American Spanish |
| `es_ES` | European Spanish |
| `es_MX` | Mexican Spanish |
| `esu` | Central Yupik |
| `et` | Estonian |
| `eu` | Basque |
| `ewo` | Ewondo |
| `ext` | Extremaduran |
| `fa` | Persian |
| `fa_AF` | Dari |
| `fan` | Fang |
| `fat` | Fanti |
| `ff` | Fulah |
| `fi` | Finnish |
| `fil` | Filipino |
| `fit` | Tornedalen Finnish |
| `fj` | Fijian |
| `fo` | Faroese |
| `fon` | Fon |
| `fr` | French |
| `fr_CA` | Canadian French |
| `fr_CH` | Swiss French |
| `frc` | Cajun French |
| `frm` | Middle French |
| `fro` | Old French |
| `frp` | Arpitan |
| `frr` | Northern Frisian |
| `frs` | Eastern Frisian |
| `fur` | Friulian |
| `fy` | Western Frisian |
| `ga` | Irish |
| `gaa` | Ga |
| `gag` | Gagauz |
| `gan` | Gan Chinese |
| `gay` | Gayo |
| `gba` | Gbaya |
| `gbz` | Zoroastrian Dari |
| `gd` | Scottish Gaelic |
| `gez` | Geez |
| `gil` | Gilbertese |
| `gl` | Galician |
| `glk` | Gilaki |
| `gmh` | Middle High German |
| `gn` | Guarani |
| `goh` | Old High German |
| `gom` | Goan Konkani |
| `gon` | Gondi |
| `gor` | Gorontalo |
| `got` | Gothic |
| `grb` | Grebo |
| `grc` | Ancient Greek |
| `gsw` | Swiss German |
| `gu` | Gujarati |
| `guc` | Wayuu |
| `gur` | Frafra |
| `guz` | Gusii |
| `gv` | Manx |
| `gwi` | Gwichʼin |
| `ha` | Hausa |
| `hai` | Haida |
| `hak` | Hakka Chinese |
| `haw` | Hawaiian |
| `he` | Hebrew |
| `hi` | Hindi |
| `hif` | Fiji Hindi |
| `hil` | Hiligaynon |
| `hit` | Hittite |
| `hmn` | Hmong |
| `ho` | Hiri Motu |
| `hr` | Croatian |
| `hsb` | Upper Sorbian |
| `hsn` | Xiang Chinese |
| `ht` | Haitian Creole |
| `hu` | Hungarian |
| `hup` | Hupa |
| `hy` | Armenian |
| `hz` | Herero |
| `ia` | Interlingua |
| `iba` | Iban |
| `ibb` | Ibibio |
| `id` | Indonesian |
| `ie` | Interlingue |
| `ig` | Igbo |
| `ii` | Sichuan Yi |
| `ik` | Inupiaq |
| `ilo` | Iloko |
| `inh` | Ingush |
| `io` | Ido |
| `is` | Icelandic |
| `it` | Italian |
| `iu` | Inuktitut |
| `izh` | Ingrian |
| `ja` | Japanese |
| `jam` | Jamaican Creole English |
| `jbo` | Lojban |
| `jgo` | Ngomba |
| `jmc` | Machame |
| `jpr` | Judeo-Persian |
| `jrb` | Judeo-Arabic |
| `jut` | Jutish |
| `jv` | Javanese |
| `ka` | Georgian |
| `kaa` | Kara-Kalpak |
| `kab` | Kabyle |
| `kac` | Kachin |
| `kaj` | Jju |
| `kam` | Kamba |
| `kaw` | Kawi |
| `kbd` | Kabardian |
| `kbl` | Kanembu |
| `kcg` | Tyap |
| `kde` | Makonde |
| `kea` | Kabuverdianu |
| `ken` | Kenyang |
| `kfo` | Koro |
| `kg` | Kongo |
| `kgp` | Kaingang |
| `kha` | Khasi |
| `kho` | Khotanese |
| `khq` | Koyra Chiini |
| `khw` | Khowar |
| `ki` | Kikuyu |
| `kiu` | Kirmanjki |
| `kj` | Kuanyama |
| `kk` | Kazakh |
| `kkj` | Kako |
| `kl` | Kalaallisut |
| `kln` | Kalenjin |
| `km` | Khmer |
| `kmb` | Kimbundu |
| `kn` | Kannada |
| `ko` | Korean |
| `koi` | Komi-Permyak |
| `kok` | Konkani |
| `kos` | Kosraean |
| `kpe` | Kpelle |
| `kr` | Kanuri |
| `krc` | Karachay-Balkar |
| `kri` | Krio |
| `krj` | Kinaray-a |
| `krl` | Karelian |
| `kru` | Kurukh |
| `ks` | Kashmiri |
| `ksb` | Shambala |
| `ksf` | Bafia |
| `ksh` | Colognian |
| `ku` | Kurdish |
| `kum` | Kumyk |
| `kut` | Kutenai |
| `kv` | Komi |
| `kw` | Cornish |
| `ky` | Kyrgyz |
| `ky` | Kirghiz |
| `la` | Latin |
| `lad` | Ladino |
| `lag` | Langi |
| `lah` | Lahnda |
| `lam` | Lamba |
| `lb` | Luxembourgish |
| `lez` | Lezghian |
| `lfn` | Lingua Franca Nova |
| `lg` | Ganda |
| `li` | Limburgish |
| `lij` | Ligurian |
| `liv` | Livonian |
| `lkt` | Lakota |
| `lmo` | Lombard |
| `ln` | Lingala |
| `lo` | Lao |
| `lol` | Mongo |
| `lou` | Louisiana Creole |
| `loz` | Lozi |
| `lrc` | Northern Luri |
| `lt` | Lithuanian |
| `ltg` | Latgalian |
| `lu` | Luba-Katanga |
| `lua` | Luba-Lulua |
| `lui` | Luiseno |
| `lun` | Lunda |
| `luo` | Luo |
| `lus` | Mizo |
| `luy` | Luyia |
| `lv` | Latvian |
| `lzh` | Literary Chinese |
| `lzz` | Laz |
| `mad` | Madurese |
| `maf` | Mafa |
| `mag` | Magahi |
| `mai` | Maithili |
| `mak` | Makasar |
| `man` | Mandingo |
| `mas` | Masai |
| `mde` | Maba |
| `mdf` | Moksha |
| `mdr` | Mandar |
| `men` | Mende |
| `mer` | Meru |
| `mfe` | Morisyen |
| `mg` | Malagasy |
| `mga` | Middle Irish |
| `mgh` | Makhuwa-Meetto |
| `mgo` | Metaʼ |
| `mh` | Marshallese |
| `mi` | Maori |
| `mic` | Mi'kmaq |
| `min` | Minangkabau |
| `mk` | Macedonian |
| `ml` | Malayalam |
| `mn` | Mongolian |
| `mnc` | Manchu |
| `mni` | Manipuri |
| `moh` | Mohawk |
| `mos` | Mossi |
| `mr` | Marathi |
| `mrj` | Western Mari |
| `ms` | Malay |
| `mt` | Maltese |
| `mua` | Mundang |
| `mul` | Multiple languages |
| `mus` | Creek |
| `mwl` | Mirandese |
| `mwr` | Marwari |
| `mwv` | Mentawai |
| `my` | Burmese |
| `my` | Myanmar Language |
| `mye` | Myene |
| `myv` | Erzya |
| `mzn` | Mazanderani |
| `na` | Nauru |
| `nan` | Min Nan Chinese |
| `nap` | Neapolitan |
| `naq` | Nama |
| `nb` | Norwegian Bokmål |
| `nd` | North Ndebele |
| `nds` | Low German |
| `nds_NL` | Low Saxon |
| `ne` | Nepali |
| `new` | Newari |
| `ng` | Ndonga |
| `nia` | Nias |
| `niu` | Niuean |
| `njo` | Ao Naga |
| `nl` | Dutch |
| `nl_BE` | Flemish |
| `nmg` | Kwasio |
| `nn` | Norwegian Nynorsk |
| `nnh` | Ngiemboon |
| `no` | Norwegian |
| `nog` | Nogai |
| `non` | Old Norse |
| `nov` | Novial |
| `nqo` | N’Ko |
| `nr` | South Ndebele |
| `nso` | Northern Sotho |
| `nus` | Nuer |
| `nv` | Navajo |
| `nwc` | Classical Newari |
| `ny` | Nyanja |
| `nym` | Nyamwezi |
| `nyn` | Nyankole |
| `nyo` | Nyoro |
| `nzi` | Nzima |
| `oc` | Occitan |
| `oj` | Ojibwa |
| `om` | Oromo |
| `or` | Odia |
| `os` | Ossetic |
| `osa` | Osage |
| `ota` | Ottoman Turkish |
| `pa` | Punjabi |
| `pag` | Pangasinan |
| `pal` | Pahlavi |
| `pam` | Pampanga |
| `pap` | Papiamento |
| `pau` | Palauan |
| `pcd` | Picard |
| `pcm` | Nigerian Pidgin |
| `pdc` | Pennsylvania German |
| `pdt` | Plautdietsch |
| `peo` | Old Persian |
| `pfl` | Palatine German |
| `phn` | Phoenician |
| `pi` | Pali |
| `pl` | Polish |
| `pms` | Piedmontese |
| `pnt` | Pontic |
| `pon` | Pohnpeian |
| `prg` | Prussian |
| `pro` | Old Provençal |
| `ps` | Pashto |
| `ps` | Pushto |
| `pt` | Portuguese |
| `pt_BR` | Brazilian Portuguese |
| `pt_PT` | European Portuguese |
| `qu` | Quechua |
| `quc` | Kʼicheʼ |
| `qug` | Chimborazo Highland Quichua |
| `raj` | Rajasthani |
| `rap` | Rapanui |
| `rar` | Rarotongan |
| `rgn` | Romagnol |
| `rif` | Riffian |
| `rm` | Romansh |
| `rn` | Rundi |
| `ro` | Romanian |
| `ro_MD` | Moldavian |
| `rof` | Rombo |
| `rom` | Romany |
| `root` | Root |
| `rtm` | Rotuman |
| `ru` | Russian |
| `rue` | Rusyn |
| `rug` | Roviana |
| `rup` | Aromanian |
| `rw` | Kinyarwanda |
| `rwk` | Rwa |
| `sa` | Sanskrit |
| `sad` | Sandawe |
| `sah` | Sakha |
| `sam` | Samaritan Aramaic |
| `saq` | Samburu |
| `sas` | Sasak |
| `sat` | Santali |
| `saz` | Saurashtra |
| `sba` | Ngambay |
| `sbp` | Sangu |
| `sc` | Sardinian |
| `scn` | Sicilian |
| `sco` | Scots |
| `sd` | Sindhi |
| `sdc` | Sassarese Sardinian |
| `sdh` | Southern Kurdish |
| `se` | Northern Sami |
| `see` | Seneca |
| `seh` | Sena |
| `sei` | Seri |
| `sel` | Selkup |
| `ses` | Koyraboro Senni |
| `sg` | Sango |
| `sga` | Old Irish |
| `sgs` | Samogitian |
| `sh` | Serbo-Croatian |
| `shi` | Tachelhit |
| `shn` | Shan |
| `shu` | Chadian Arabic |
| `si` | Sinhala |
| `sid` | Sidamo |
| `sk` | Slovak |
| `sl` | Slovenian |
| `sli` | Lower Silesian |
| `sly` | Selayar |
| `sm` | Samoan |
| `sma` | Southern Sami |
| `smj` | Lule Sami |
| `smn` | Inari Sami |
| `sms` | Skolt Sami |
| `sn` | Shona |
| `snk` | Soninke |
| `so` | Somali |
| `sog` | Sogdien |
| `sq` | Albanian |
| `sr` | Serbian |
| `srn` | Sranan Tongo |
| `srr` | Serer |
| `ss` | Swati |
| `ssy` | Saho |
| `st` | Southern Sotho |
| `stq` | Saterland Frisian |
| `su` | Sundanese |
| `suk` | Sukuma |
| `sus` | Susu |
| `sux` | Sumerian |
| `sv` | Swedish |
| `sw` | Swahili |
| `sw_CD` | Congo Swahili |
| `swb` | Comorian |
| `syc` | Classical Syriac |
| `syr` | Syriac |
| `szl` | Silesian |
| `ta` | Tamil |
| `tcy` | Tulu |
| `te` | Telugu |
| `tem` | Timne |
| `teo` | Teso |
| `ter` | Tereno |
| `tet` | Tetum |
| `tg` | Tajik |
| `th` | Thai |
| `ti` | Tigrinya |
| `tig` | Tigre |
| `tiv` | Tiv |
| `tk` | Turkmen |
| `tkl` | Tokelau |
| `tkr` | Tsakhur |
| `tl` | Tagalog |
| `tlh` | Klingon |
| `tli` | Tlingit |
| `tly` | Talysh |
| `tmh` | Tamashek |
| `tn` | Tswana |
| `to` | Tongan |
| `tog` | Nyasa Tonga |
| `tpi` | Tok Pisin |
| `tr` | Turkish |
| `tru` | Turoyo |
| `trv` | Taroko |
| `ts` | Tsonga |
| `tsd` | Tsakonian |
| `tsi` | Tsimshian |
| `tt` | Tatar |
| `ttt` | Muslim Tat |
| `tum` | Tumbuka |
| `tvl` | Tuvalu |
| `tw` | Twi |
| `twq` | Tasawaq |
| `ty` | Tahitian |
| `tyv` | Tuvinian |
| `tzm` | Central Atlas Tamazight |
| `udm` | Udmurt |
| `ug` | Uyghur |
| `ug` | Uighur |
| `uga` | Ugaritic |
| `uk` | Ukrainian |
| `umb` | Umbundu |
| `und` | Unknown language |
| `ur` | Urdu |
| `uz` | Uzbek |
| `vai` | Vai |
| `ve` | Venda |
| `vec` | Venetian |
| `vep` | Veps |
| `vi` | Vietnamese |
| `vls` | West Flemish |
| `vmf` | Main-Franconian |
| `vo` | Volapük |
| `vot` | Votic |
| `vro` | Võro |
| `vun` | Vunjo |
| `wa` | Walloon |
| `wae` | Walser |
| `wal` | Wolaytta |
| `war` | Waray |
| `was` | Washo |
| `wbp` | Warlpiri |
| `wo` | Wolof |
| `wuu` | Wu Chinese |
| `xal` | Kalmyk |
| `xh` | Xhosa |
| `xmf` | Mingrelian |
| `xog` | Soga |
| `yao` | Yao |
| `yap` | Yapese |
| `yav` | Yangben |
| `ybb` | Yemba |
| `yi` | Yiddish |
| `yo` | Yoruba |
| `yrl` | Nheengatu |
| `yue` | Cantonese |
| `za` | Zhuang |
| `zap` | Zapotec |
| `zbl` | Blissymbols |
| `zea` | Zeelandic |
| `zen` | Zenaga |
| `zgh` | Standard Moroccan Tamazight |
| `zh` | Chinese |
| `zh` | Mandarin Chinese |
| `zh_Hans` | Simplified Chinese |
| `zh_Hant` | Traditional Chinese |
| `zu` | Zulu |
| `zun` | Zuni |
| `zxx` | No linguistic content |
| `zza` | Zaza |
### Script names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `Adlm` | Adlam |
| `Afak` | Afaka |
| `Aghb` | Caucasian Albanian |
| `Ahom` | Ahom |
| `Arab` | Arabic |
| `Arab` | Perso-Arabic |
| `Armi` | Imperial Aramaic |
| `Armn` | Armenian |
| `Avst` | Avestan |
| `Bali` | Balinese |
| `Bamu` | Bamum |
| `Bass` | Bassa Vah |
| `Batk` | Batak |
| `Beng` | Bangla |
| `Bhks` | Bhaiksuki |
| `Blis` | Blissymbols |
| `Bopo` | Bopomofo |
| `Brah` | Brahmi |
| `Brai` | Braille |
| `Bugi` | Buginese |
| `Buhd` | Buhid |
| `Cakm` | Chakma |
| `Cans` | Unified Canadian Aboriginal Syllabics |
| `Cans` | UCAS |
| `Cari` | Carian |
| `Cham` | Cham |
| `Cher` | Cherokee |
| `Cirt` | Cirth |
| `Copt` | Coptic |
| `Cprt` | Cypriot |
| `Cyrl` | Cyrillic |
| `Cyrs` | Old Church Slavonic Cyrillic |
| `Deva` | Devanagari |
| `Dsrt` | Deseret |
| `Dupl` | Duployan shorthand |
| `Egyd` | Egyptian demotic |
| `Egyh` | Egyptian hieratic |
| `Egyp` | Egyptian hieroglyphs |
| `Elba` | Elbasan |
| `Ethi` | Ethiopic |
| `Geok` | Georgian Khutsuri |
| `Geor` | Georgian |
| `Glag` | Glagolitic |
| `Gonm` | Masaram Gondi |
| `Goth` | Gothic |
| `Gran` | Grantha |
| `Grek` | Greek |
| `Gujr` | Gujarati |
| `Guru` | Gurmukhi |
| `Hanb` | Han with Bopomofo |
| `Hang` | Hangul |
| `Hani` | Han |
| `Hano` | Hanunoo |
| `Hans` | Simplified |
| `Hans` | Simplified Han |
| `Hant` | Traditional |
| `Hant` | Traditional Han |
| `Hatr` | Hatran |
| `Hebr` | Hebrew |
| `Hira` | Hiragana |
| `Hluw` | Anatolian Hieroglyphs |
| `Hmng` | Pahawh Hmong |
| `Hrkt` | Japanese syllabaries |
| `Hung` | Old Hungarian |
| `Inds` | Indus |
| `Ital` | Old Italic |
| `Jamo` | Jamo |
| `Java` | Javanese |
| `Jpan` | Japanese |
| `Jurc` | Jurchen |
| `Kali` | Kayah Li |
| `Kana` | Katakana |
| `Khar` | Kharoshthi |
| `Khmr` | Khmer |
| `Khoj` | Khojki |
| `Knda` | Kannada |
| `Kore` | Korean |
| `Kpel` | Kpelle |
| `Kthi` | Kaithi |
| `Lana` | Lanna |
| `Laoo` | Lao |
| `Latf` | Fraktur Latin |
| `Latg` | Gaelic Latin |
| `Latn` | Latin |
| `Lepc` | Lepcha |
| `Limb` | Limbu |
| `Lina` | Linear A |
| `Linb` | Linear B |
| `Lisu` | Fraser |
| `Loma` | Loma |
| `Lyci` | Lycian |
| `Lydi` | Lydian |
| `Mahj` | Mahajani |
| `Mand` | Mandaean |
| `Mani` | Manichaean |
| `Marc` | Marchen |
| `Maya` | Mayan hieroglyphs |
| `Mend` | Mende |
| `Merc` | Meroitic Cursive |
| `Mero` | Meroitic |
| `Mlym` | Malayalam |
| `Modi` | Modi |
| `Mong` | Mongolian |
| `Moon` | Moon |
| `Mroo` | Mro |
| `Mtei` | Meitei Mayek |
| `Mult` | Multani |
| `Mymr` | Myanmar |
| `Narb` | Old North Arabian |
| `Nbat` | Nabataean |
| `Newa` | Newa |
| `Nkgb` | Naxi Geba |
| `Nkoo` | N’Ko |
| `Nshu` | Nüshu |
| `Ogam` | Ogham |
| `Olck` | Ol Chiki |
| `Orkh` | Orkhon |
| `Orya` | Odia |
| `Osge` | Osage |
| `Osma` | Osmanya |
| `Palm` | Palmyrene |
| `Pauc` | Pau Cin Hau |
| `Perm` | Old Permic |
| `Phag` | Phags-pa |
| `Phli` | Inscriptional Pahlavi |
| `Phlp` | Psalter Pahlavi |
| `Phlv` | Book Pahlavi |
| `Phnx` | Phoenician |
| `Plrd` | Pollard Phonetic |
| `Prti` | Inscriptional Parthian |
| `Rjng` | Rejang |
| `Roro` | Rongorongo |
| `Runr` | Runic |
| `Samr` | Samaritan |
| `Sara` | Sarati |
| `Sarb` | Old South Arabian |
| `Saur` | Saurashtra |
| `Sgnw` | SignWriting |
| `Shaw` | Shavian |
| `Shrd` | Sharada |
| `Sidd` | Siddham |
| `Sind` | Khudawadi |
| `Sinh` | Sinhala |
| `Sora` | Sora Sompeng |
| `Soyo` | Soyombo |
| `Sund` | Sundanese |
| `Sylo` | Syloti Nagri |
| `Syrc` | Syriac |
| `Syre` | Estrangelo Syriac |
| `Syrj` | Western Syriac |
| `Syrn` | Eastern Syriac |
| `Tagb` | Tagbanwa |
| `Takr` | Takri |
| `Tale` | Tai Le |
| `Talu` | New Tai Lue |
| `Taml` | Tamil |
| `Tang` | Tangut |
| `Tavt` | Tai Viet |
| `Telu` | Telugu |
| `Teng` | Tengwar |
| `Tfng` | Tifinagh |
| `Tglg` | Tagalog |
| `Thaa` | Thaana |
| `Thai` | Thai |
| `Tibt` | Tibetan |
| `Tirh` | Tirhuta |
| `Ugar` | Ugaritic |
| `Vaii` | Vai |
| `Visp` | Visible Speech |
| `Wara` | Varang Kshiti |
| `Wole` | Woleai |
| `Xpeo` | Old Persian |
| `Xsux` | Sumero-Akkadian Cuneiform |
| `Xsux` | S-A Cuneiform |
| `Yiii` | Yi |
| `Zanb` | Zanabazar Square |
| `Zinh` | Inherited |
| `Zmth` | Mathematical Notation |
| `Zsye` | Emoji |
| `Zsym` | Symbols |
| `Zxxx` | Unwritten |
| `Zyyy` | Common |
| `Zzzz` | Unknown Script |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `001` | World |
| `002` | Africa |
| `003` | North America |
| `005` | South America |
| `009` | Oceania |
| `011` | Western Africa |
| `013` | Central America |
| `014` | Eastern Africa |
| `015` | Northern Africa |
| `017` | Middle Africa |
| `018` | Southern Africa |
| `019` | Americas |
| `021` | Northern America |
| `029` | Caribbean |
| `030` | Eastern Asia |
| `034` | Southern Asia |
| `035` | Southeast Asia |
| `039` | Southern Europe |
| `053` | Australasia |
| `054` | Melanesia |
| `057` | Micronesian Region |
| `061` | Polynesia |
| `142` | Asia |
| `143` | Central Asia |
| `145` | Western Asia |
| `150` | Europe |
| `151` | Eastern Europe |
| `154` | Northern Europe |
| `155` | Western Europe |
| `202` | Sub-Saharan Africa |
| `419` | Latin America |
| `AC` | Ascension Island |
| `AD` | Andorra |
| `AE` | United Arab Emirates |
| `AF` | Afghanistan |
| `AG` | Antigua & Barbuda |
| `AI` | Anguilla |
| `AL` | Albania |
| `AM` | Armenia |
| `AO` | Angola |
| `AQ` | Antarctica |
| `AR` | Argentina |
| `AS` | American Samoa |
| `AT` | Austria |
| `AU` | Australia |
| `AW` | Aruba |
| `AX` | Åland Islands |
| `AZ` | Azerbaijan |
| `BA` | Bosnia & Herzegovina |
| `BA` | Bosnia |
| `BB` | Barbados |
| `BD` | Bangladesh |
| `BE` | Belgium |
| `BF` | Burkina Faso |
| `BG` | Bulgaria |
| `BH` | Bahrain |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | St. Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Bolivia |
| `BQ` | Caribbean Netherlands |
| `BR` | Brazil |
| `BS` | Bahamas |
| `BT` | Bhutan |
| `BV` | Bouvet Island |
| `BW` | Botswana |
| `BY` | Belarus |
| `BZ` | Belize |
| `CA` | Canada |
| `CC` | Cocos (Keeling) Islands |
| `CD` | Congo - Kinshasa |
| `CD` | Congo (DRC) |
| `CF` | Central African Republic |
| `CG` | Congo - Brazzaville |
| `CG` | Congo (Republic) |
| `CH` | Switzerland |
| `CI` | Côte d’Ivoire |
| `CI` | Ivory Coast |
| `CK` | Cook Islands |
| `CL` | Chile |
| `CM` | Cameroon |
| `CN` | China |
| `CO` | Colombia |
| `CP` | Clipperton Island |
| `CR` | Costa Rica |
| `CU` | Cuba |
| `CV` | Cape Verde |
| `CW` | Curaçao |
| `CX` | Christmas Island |
| `CY` | Cyprus |
| `CZ` | Czechia |
| `CZ` | Czech Republic |
| `DE` | Germany |
| `DG` | Diego Garcia |
| `DJ` | Djibouti |
| `DK` | Denmark |
| `DM` | Dominica |
| `DO` | Dominican Republic |
| `DZ` | Algeria |
| `EA` | Ceuta & Melilla |
| `EC` | Ecuador |
| `EE` | Estonia |
| `EG` | Egypt |
| `EH` | Western Sahara |
| `ER` | Eritrea |
| `ES` | Spain |
| `ET` | Ethiopia |
| `EU` | European Union |
| `EZ` | Eurozone |
| `FI` | Finland |
| `FJ` | Fiji |
| `FK` | Falkland Islands |
| `FK` | Falkland Islands (Islas Malvinas) |
| `FM` | Micronesia |
| `FO` | Faroe Islands |
| `FR` | France |
| `GA` | Gabon |
| `GB` | United Kingdom |
| `GB` | UK |
| `GD` | Grenada |
| `GE` | Georgia |
| `GF` | French Guiana |
| `GG` | Guernsey |
| `GH` | Ghana |
| `GI` | Gibraltar |
| `GL` | Greenland |
| `GM` | Gambia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Equatorial Guinea |
| `GR` | Greece |
| `GS` | South Georgia & South Sandwich Islands |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Guinea-Bissau |
| `GY` | Guyana |
| `HK` | Hong Kong SAR China |
| `HK` | Hong Kong |
| `HM` | Heard & McDonald Islands |
| `HN` | Honduras |
| `HR` | Croatia |
| `HT` | Haiti |
| `HU` | Hungary |
| `IC` | Canary Islands |
| `ID` | Indonesia |
| `IE` | Ireland |
| `IL` | Israel |
| `IM` | Isle of Man |
| `IN` | India |
| `IO` | British Indian Ocean Territory |
| `IQ` | Iraq |
| `IR` | Iran |
| `IS` | Iceland |
| `IT` | Italy |
| `JE` | Jersey |
| `JM` | Jamaica |
| `JO` | Jordan |
| `JP` | Japan |
| `KE` | Kenya |
| `KG` | Kyrgyzstan |
| `KH` | Cambodia |
| `KI` | Kiribati |
| `KM` | Comoros |
| `KN` | St. Kitts & Nevis |
| `KP` | North Korea |
| `KR` | South Korea |
| `KW` | Kuwait |
| `KY` | Cayman Islands |
| `KZ` | Kazakhstan |
| `LA` | Laos |
| `LB` | Lebanon |
| `LC` | St. Lucia |
| `LI` | Liechtenstein |
| `LK` | Sri Lanka |
| `LR` | Liberia |
| `LS` | Lesotho |
| `LT` | Lithuania |
| `LU` | Luxembourg |
| `LV` | Latvia |
| `LY` | Libya |
| `MA` | Morocco |
| `MC` | Monaco |
| `MD` | Moldova |
| `ME` | Montenegro |
| `MF` | St. Martin |
| `MG` | Madagascar |
| `MH` | Marshall Islands |
| `MK` | Macedonia |
| `MK` | Macedonia (FYROM) |
| `ML` | Mali |
| `MM` | Myanmar (Burma) |
| `MM` | Myanmar |
| `MN` | Mongolia |
| `MO` | Macau SAR China |
| `MO` | Macau |
| `MP` | Northern Mariana Islands |
| `MQ` | Martinique |
| `MR` | Mauritania |
| `MS` | Montserrat |
| `MT` | Malta |
| `MU` | Mauritius |
| `MV` | Maldives |
| `MW` | Malawi |
| `MX` | Mexico |
| `MY` | Malaysia |
| `MZ` | Mozambique |
| `NA` | Namibia |
| `NC` | New Caledonia |
| `NE` | Niger |
| `NF` | Norfolk Island |
| `NG` | Nigeria |
| `NI` | Nicaragua |
| `NL` | Netherlands |
| `NO` | Norway |
| `NP` | Nepal |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | New Zealand |
| `OM` | Oman |
| `PA` | Panama |
| `PE` | Peru |
| `PF` | French Polynesia |
| `PG` | Papua New Guinea |
| `PH` | Philippines |
| `PK` | Pakistan |
| `PL` | Poland |
| `PM` | St. Pierre & Miquelon |
| `PN` | Pitcairn Islands |
| `PR` | Puerto Rico |
| `PS` | Palestinian Territories |
| `PS` | Palestine |
| `PT` | Portugal |
| `PW` | Palau |
| `PY` | Paraguay |
| `QA` | Qatar |
| `QO` | Outlying Oceania |
| `RE` | Réunion |
| `RO` | Romania |
| `RS` | Serbia |
| `RU` | Russia |
| `RW` | Rwanda |
| `SA` | Saudi Arabia |
| `SB` | Solomon Islands |
| `SC` | Seychelles |
| `SD` | Sudan |
| `SE` | Sweden |
| `SG` | Singapore |
| `SH` | St. Helena |
| `SI` | Slovenia |
| `SJ` | Svalbard & Jan Mayen |
| `SK` | Slovakia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Senegal |
| `SO` | Somalia |
| `SR` | Suriname |
| `SS` | South Sudan |
| `ST` | São Tomé & Príncipe |
| `SV` | El Salvador |
| `SX` | Sint Maarten |
| `SY` | Syria |
| `SZ` | Swaziland |
| `TA` | Tristan da Cunha |
| `TC` | Turks & Caicos Islands |
| `TD` | Chad |
| `TF` | French Southern Territories |
| `TG` | Togo |
| `TH` | Thailand |
| `TJ` | Tajikistan |
| `TK` | Tokelau |
| `TL` | Timor-Leste |
| `TL` | East Timor |
| `TM` | Turkmenistan |
| `TN` | Tunisia |
| `TO` | Tonga |
| `TR` | Turkey |
| `TT` | Trinidad & Tobago |
| `TV` | Tuvalu |
| `TW` | Taiwan |
| `TZ` | Tanzania |
| `UA` | Ukraine |
| `UG` | Uganda |
| `UM` | U.S. Outlying Islands |
| `UN` | United Nations |
| `UN` | UN |
| `US` | United States |
| `US` | US |
| `UY` | Uruguay |
| `UZ` | Uzbekistan |
| `VA` | Vatican City |
| `VC` | St. Vincent & Grenadines |
| `VE` | Venezuela |
| `VG` | British Virgin Islands |
| `VI` | U.S. Virgin Islands |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis & Futuna |
| `WS` | Samoa |
| `XK` | Kosovo |
| `YE` | Yemen |
| `YT` | Mayotte |
| `ZA` | South Africa |
| `ZM` | Zambia |
| `ZW` | Zimbabwe |
| `ZZ` | Unknown Region |
### Locale variant names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `1901` | Traditional German orthography |
| `1994` | Standardized Resian orthography |
| `1996` | German orthography of 1996 |
| `1606NICT` | Late Middle French to 1606 |
| `1694ACAD` | Early Modern French |
| `1959ACAD` | Academic |
| `ABL1943` | Orthographic formulation of 1943 |
| `ALALC97` | ALA-LC Romanization, 1997 edition |
| `ALUKU` | Aluku dialect |
| `AO1990` | Portuguese Language Orthographic Agreement of 1990 |
| `AREVELA` | Eastern Armenian |
| `AREVMDA` | Western Armenian |
| `BAKU1926` | Unified Turkic Latin Alphabet |
| `BALANKA` | Balanka dialect of Anii |
| `BARLA` | Barlavento dialect group of Kabuverdianu |
| `BISKE` | San Giorgio/Bila dialect |
| `BOHORIC` | Bohorič alphabet |
| `BOONT` | Boontling |
| `COLB1945` | Portuguese-Brazilian Orthographic Convention of 1945 |
| `DAJNKO` | Dajnko alphabet |
| `EKAVSK` | Serbian with Ekavian pronunciation |
| `EMODENG` | Early Modern English |
| `FONIPA` | IPA Phonetics |
| `FONUPA` | UPA Phonetics |
| `HEPBURN` | Hepburn romanization |
| `IJEKAVSK` | Serbian with Ijekavian pronunciation |
| `KKCOR` | Common Orthography |
| `KSCOR` | Standard Orthography |
| `LIPAW` | The Lipovaz dialect of Resian |
| `METELKO` | Metelko alphabet |
| `MONOTON` | Monotonic |
| `NDYUKA` | Ndyuka dialect |
| `NEDIS` | Natisone dialect |
| `NJIVA` | Gniva/Njiva dialect |
| `NULIK` | Modern Volapük |
| `OSOJS` | Oseacco/Osojane dialect |
| `OXENDICT` | Oxford English Dictionary spelling |
| `PAMAKA` | Pamaka dialect |
| `PINYIN` | Pinyin Romanization |
| `POLYTON` | Polytonic |
| `POSIX` | Computer |
| `REVISED` | Revised Orthography |
| `RIGIK` | Classic Volapük |
| `ROZAJ` | Resian |
| `SAAHO` | Saho |
| `SCOTLAND` | Scottish Standard English |
| `SCOUSE` | Scouse |
| `SOLBA` | Stolvizza/Solbica dialect |
| `SOTAV` | Sotavento dialect group of Kabuverdianu |
| `TARASK` | Taraskievica orthography |
| `UCCOR` | Unified Orthography |
| `UCRCOR` | Unified Revised Orthography |
| `UNIFON` | Unifon phonetic alphabet |
| `VALENCIA` | Valencian |
| `WADEGILE` | Wade-Giles Romanization |
#### Keys (system names)
| key | Name |
| -------- | ---- |
| `calendar` | Calendar |
| `cf` | Currency Format |
| `colAlternate` | Ignore Symbols Sorting |
| `colBackwards` | Reversed Accent Sorting |
| `colCaseFirst` | Uppercase/Lowercase Ordering |
| `colCaseLevel` | Case Sensitive Sorting |
| `collation` | Sort Order |
| `colNormalization` | Normalized Sorting |
| `colNumeric` | Numeric Sorting |
| `colReorder` | Script/Block Reordering |
| `colStrength` | Sorting Strength |
| `currency` | Currency |
| `d0` | Transform Destination |
| `em` | Emoji Presentation Style |
| `fw` | First day of week |
| `h0` | Mixed-in Language |
| `hc` | Hour Cycle (12 vs 24) |
| `i0` | Input Method |
| `k0` | Keyboard |
| `kv` | Highest Ignored |
| `lb` | Line Break Style |
| `lw` | Line Breaks In Words Setting |
| `m0` | Transform Rules |
| `ms` | Measurement System |
| `numbers` | Numbers |
| `rg` | Region For Supplemental Data |
| `s0` | Transform Source |
| `sd` | Region Subdivision |
| `ss` | Sentence Break Suppressions Type |
| `t0` | Machine Translated |
| `timezone` | Time Zone |
| `va` | Locale Variant |
| `x` | Private-Use |
| `x0` | Private-Use Transform |
### Types (of systems)
| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | Buddhist Calendar |
| `chinesecalendar` | Chinese Calendar |
| `copticcalendar` | Coptic Calendar |
| `dangicalendar` | Dangi Calendar |
| `ethiopiccalendar` | Ethiopic Calendar |
| `ethiopic-amete-alemcalendar` | Ethiopic Amete Alem Calendar |
| `gregoriancalendar` | Gregorian Calendar |
| `hebrewcalendar` | Hebrew Calendar |
| `indiancalendar` | Indian National Calendar |
| `islamiccalendar` | Islamic Calendar |
| `islamic-civilcalendar` | Islamic Calendar (tabular, civil epoch) |
| `islamic-rgsacalendar` | Islamic Calendar (Saudi Arabia, sighting) |
| `islamic-tblacalendar` | Islamic Calendar (tabular, astronomical epoch) |
| `islamic-umalquracalendar` | Islamic Calendar (Umm al-Qura) |
| `iso8601calendar` | ISO-8601 Calendar |
| `japanesecalendar` | Japanese Calendar |
| `persiancalendar` | Persian Calendar |
| `roccalendar` | Minguo Calendar |
| `accountcf` | Accounting Currency Format |
| `standardcf` | Standard Currency Format |
| `non-ignorablecolAlternate` | Sort Symbols |
| `shiftedcolAlternate` | Sort Ignoring Symbols |
| `nocolBackwards` | Sort Accents Normally |
| `yescolBackwards` | Sort Accents Reversed |
| `lowercolCaseFirst` | Sort Lowercase First |
| `nocolCaseFirst` | Sort Normal Case Order |
| `uppercolCaseFirst` | Sort Uppercase First |
| `nocolCaseLevel` | Sort Case Insensitive |
| `yescolCaseLevel` | Sort Case Sensitive |
| `big5hancollation` | Traditional Chinese Sort Order - Big5 |
| `compatcollation` | Previous Sort Order, for compatibility |
| `dictionarycollation` | Dictionary Sort Order |
| `ducetcollation` | Default Unicode Sort Order |
| `emojicollation` | Emoji Sort Order |
| `eorcollation` | European Ordering Rules |
| `gb2312hancollation` | Simplified Chinese Sort Order - GB2312 |
| `phonebookcollation` | Phonebook Sort Order |
| `phoneticcollation` | Phonetic Sort Order |
| `pinyincollation` | Pinyin Sort Order |
| `reformedcollation` | Reformed Sort Order |
| `searchcollation` | General-Purpose Search |
| `searchjlcollation` | Search By Hangul Initial Consonant |
| `standardcollation` | Standard Sort Order |
| `strokecollation` | Stroke Sort Order |
| `traditionalcollation` | Traditional Sort Order |
| `unihancollation` | Radical-Stroke Sort Order |
| `zhuyincollation` | Zhuyin Sort Order |
| `nocolNormalization` | Sort Without Normalization |
| `yescolNormalization` | Sort Unicode Normalized |
| `nocolNumeric` | Sort Digits Individually |
| `yescolNumeric` | Sort Digits Numerically |
| `identicalcolStrength` | Sort All |
| `primarycolStrength` | Sort Base Letters Only |
| `quaternarycolStrength` | Sort Accents/Case/Width/Kana |
| `secondarycolStrength` | Sort Accents |
| `tertiarycolStrength` | Sort Accents/Case/Width |
| `accentsd0` | To Accented Characters From ASCII Sequence |
| `asciid0` | To ASCII |
| `casefoldd0` | To Casefolded |
| `charnamed0` | To Unicode Character Names |
| `fccd0` | To Unicode FCC |
| `fcdd0` | To Unicode FCD |
| `fwidthd0` | To Fullwidth |
| `hexd0` | To Hexadecimal Codes |
| `hwidthd0` | To Halfwidth |
| `lowerd0` | To Lowercase |
| `nfcd0` | To Unicode NFC |
| `nfdd0` | To Unicode NFD |
| `nfkcd0` | To Unicode NFKC |
| `nfkdd0` | To Unicode NFKD |
| `npinyind0` | To Pinyin With Numeric Tones |
| `nulld0` | No Change |
| `publishd0` | To Publishing Characters From ASCII |
| `removed0` | To Empty String |
| `titled0` | To Titlecase |
| `upperd0` | To Uppercase |
| `defaultem` | Use Default Presentation For Emoji Characters |
| `emojiem` | Prefer Emoji Presentation For Emoji Characters |
| `textem` | Prefer Text Presentation For Emoji Characters |
| `frifw` | First Day of Week Is Friday |
| `monfw` | First Day of Week Is Monday |
| `satfw` | First Day of Week Is Saturday |
| `sunfw` | First Day of Week Is Sunday |
| `thufw` | First Day of Week Is Thursday |
| `tuefw` | First Day of Week Is Tuesday |
| `wedfw` | First Day of Week Is Wednesday |
| `hybridh0` | Hybrid Language |
| `h11hc` | 12 Hour System (0–11) |
| `h12hc` | 12 Hour System (1–12) |
| `h23hc` | 24 Hour System (0–23) |
| `h24hc` | 24 Hour System (1–24) |
| `handwriti0` | Handwriting Input Method |
| `pinyini0` | Pinyin Input Method |
| `undi0` | Unspecified Input Method |
| `wubii0` | Wubi Input Method |
| `101keyk0` | 101-Key Keyboard |
| `102keyk0` | 102-Key Keyboard |
| `600dpik0` | 600 dpi Keyboard |
| `768dpik0` | 768 dpi Keyboard |
| `androidk0` | Android Keyboard |
| `azertyk0` | AZERTY-Based Keyboard |
| `chromeosk0` | ChromeOS Keyboard |
| `colemakk0` | Colemak Keyboard |
| `dvorakk0` | Dvorak Keyboard |
| `dvoraklk0` | Dvorak Left-Handed Keyboard |
| `dvorakrk0` | Dvorak Right-Handed Keyboard |
| `el220k0` | Greek 220 Keyboard |
| `el319k0` | Greek 319 Keyboard |
| `extendedk0` | Keyboard With Many Extra Characters |
| `googlevkk0` | Google Virtual Keyboard |
| `isirik0` | Persian ISIRI Keyboard |
| `legacyk0` | Legacy Keyboard |
| `lt1205k0` | Lithuanian LST 1205 Keyboard |
| `lt1582k0` | Lithuanian LST 1582 Keyboard |
| `nutaaqk0` | Inuktitut Nutaaq Keyboard |
| `osxk0` | macOS Keyboard |
| `pattak0` | Thai Pattachote Keyboard |
| `qwertyk0` | QWERTY-Based Keyboard |
| `qwertzk0` | QWERTZ-Based Keyboard |
| `ta99k0` | Tamil 99 Keyboard |
| `undk0` | Unspecified Keyboard |
| `vark0` | Keyboard Variant |
| `viqrk0` | Vietnamese VIQR Keyboard |
| `windowsk0` | Windows Keyboard |
| `currencykr` | Currency |
| `digitkr` | Digits |
| `punctkr` | Punctuation |
| `spacekr` | Whitespace |
| `symbolkr` | Symbol |
| `currencykv` | Ignore Symbols affects spaces, punctuation, all symbols |
| `punctkv` | Ignore Symbols affects spaces and punctuation only |
| `spacekv` | Ignore Symbols affects spaces only |
| `symbolkv` | Ignore Symbols affects spaces, punctuation, non-currency symbols |
| `looselb` | Loose Line Break Style |
| `normallb` | Normal Line Break Style |
| `strictlb` | Strict Line Break Style |
| `breakalllw` | Allow Line Breaks In All Words |
| `keepalllw` | Prevent Line Breaks In All Words |
| `normallw` | Normal Line Breaks For Words |
| `alalocm0` | US ALA-LOC Transliteration |
| `bgnm0` | US BGN Transliteration |
| `buckwaltm0` | Buckwalter Arabic Transliteration |
| `dinm0` | German DIN Transliteration |
| `gostm0` | CIS GOST Transliteration |
| `isom0` | ISO Transliteration |
| `mcstm0` | Korean MCST Transliteration |
| `mnsm0` | Mongolian National Standard Transliteration |
| `prprnamem0` | Personal Name Transliteration Variant |
| `sattsm0` | Standard Arabic Technical Transliteration |
| `ungegnm0` | UN GEGN Transliteration |
| `metricms` | Metric System |
| `uksystemms` | Imperial Measurement System |
| `ussystemms` | US Measurement System |
| `adlmnumbers` | Adlam Digits |
| `ahomnumbers` | Ahom Digits |
| `arabnumbers` | Arabic-Indic Digits |
| `arabextnumbers` | Extended Arabic-Indic Digits |
| `arabextnumbers` | X Arabic-Indic Digits |
| `armnnumbers` | Armenian Numerals |
| `armnlownumbers` | Armenian Lowercase Numerals |
| `balinumbers` | Balinese Digits |
| `bengnumbers` | Bangla Digits |
| `bhksnumbers` | Bhaiksuki Digits |
| `brahnumbers` | Brahmi Digits |
| `cakmnumbers` | Chakma Digits |
| `chamnumbers` | Cham Digits |
| `cyrlnumbers` | Cyrillic Numerals |
| `devanumbers` | Devanagari Digits |
| `ethinumbers` | Ethiopic Numerals |
| `financenumbers` | Financial Numerals |
| `fullwidenumbers` | Full-Width Digits |
| `geornumbers` | Georgian Numerals |
| `gonmnumbers` | Masaram Gondi digits |
| `greknumbers` | Greek Numerals |
| `greklownumbers` | Greek Lowercase Numerals |
| `gujrnumbers` | Gujarati Digits |
| `gurunumbers` | Gurmukhi Digits |
| `hanidaysnumbers` | Chinese Calendar Day-of-Month Numerals |
| `hanidecnumbers` | Chinese Decimal Numerals |
| `hansnumbers` | Simplified Chinese Numerals |
| `hansfinnumbers` | Simplified Chinese Financial Numerals |
| `hantnumbers` | Traditional Chinese Numerals |
| `hantfinnumbers` | Traditional Chinese Financial Numerals |
| `hebrnumbers` | Hebrew Numerals |
| `hmngnumbers` | Pahawh Hmong Digits |
| `javanumbers` | Javanese Digits |
| `jpannumbers` | Japanese Numerals |
| `jpanfinnumbers` | Japanese Financial Numerals |
| `kalinumbers` | Kayah Li Digits |
| `khmrnumbers` | Khmer Digits |
| `kndanumbers` | Kannada Digits |
| `lananumbers` | Tai Tham Hora Digits |
| `lanathamnumbers` | Tai Tham Tham Digits |
| `laoonumbers` | Lao Digits |
| `latnnumbers` | Western Digits |
| `lepcnumbers` | Lepcha Digits |
| `limbnumbers` | Limbu Digits |
| `mathboldnumbers` | Mathematical Bold Digits |
| `mathdblnumbers` | Mathematical Double-Struck Digits |
| `mathmononumbers` | Mathematical Monospace Digits |
| `mathsanbnumbers` | Mathematical Sans-Serif Bold Digits |
| `mathsansnumbers` | Mathematical Sans-Serif Digits |
| `mlymnumbers` | Malayalam Digits |
| `modinumbers` | Modi Digits |
| `mongnumbers` | Mongolian Digits |
| `mroonumbers` | Mro Digits |
| `mteinumbers` | Meetei Mayek Digits |
| `mymrnumbers` | Myanmar Digits |
| `mymrshannumbers` | Myanmar Shan Digits |
| `mymrtlngnumbers` | Myanmar Tai Laing Digits |
| `nativenumbers` | Native Digits |
| `newanumbers` | Newa Digits |
| `nkoonumbers` | N’Ko Digits |
| `olcknumbers` | Ol Chiki Digits |
| `oryanumbers` | Odia Digits |
| `osmanumbers` | Osmanya Digits |
| `romannumbers` | Roman Numerals |
| `romanlownumbers` | Roman Lowercase Numerals |
| `saurnumbers` | Saurashtra Digits |
| `shrdnumbers` | Sharada Digits |
| `sindnumbers` | Khudawadi Digits |
| `sinhnumbers` | Sinhala Lith Digits |
| `soranumbers` | Sora Sompeng Digits |
| `sundnumbers` | Sundanese Digits |
| `takrnumbers` | Takri Digits |
| `talunumbers` | New Tai Lue Digits |
| `tamlnumbers` | Traditional Tamil Numerals |
| `tamldecnumbers` | Tamil Digits |
| `telunumbers` | Telugu Digits |
| `thainumbers` | Thai Digits |
| `tibtnumbers` | Tibetan Digits |
| `tirhnumbers` | Tirhuta Digits |
| `traditionalnumbers` | Traditional Numerals |
| `vaiinumbers` | Vai Digits |
| `waranumbers` | Warang Citi Digits |
| `accentss0` | From Accented Characters To ASCII Sequence |
| `asciis0` | From ASCII |
| `hexs0` | From Hexadecimal Codes |
| `npinyins0` | From Pinyin With Numeric Tones |
| `publishs0` | From Publishing Punctuation To ASCII |
| `zawgyis0` | From Zawgyi Myanmar Encoding |
| `noness` | Sentence Breaks Without Abbreviation Handling |
| `standardss` | Suppress Sentence Breaks After Standard Abbreviations |
| `undt0` | Unspecified Machine Translation |
| `posixva` | POSIX Compliant Locale |
| `metric` | Metric |
| `UK` | UK |
| `US` | US |
### Code patterns
Language: {0}Script: {0}Region: {0}
### Context transforms
```
titlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstword
```
### Character processing for computer systems
| main characters | `[a b c d e f g h i j k l m n o p q r s t u v w x y z]` |
| auxiliary characters | `[á à ă â å ä ã ā æ ç é è ĕ ê ë ē í ì ĭ î ï ī ñ ó ò ŏ ô ö ø ō œ ú ù ŭ û ü ū ÿ]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S T U V W X Y Z]` |
| numbers characters | `[\- , . % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ’ " “ ” ( ) \[ \] § @ * / \& # † ‡ ′ ″]` |
Delimiters:
Quotation start character: “
Quotation end character: ”
Secondary yquotation start character: ‘
Secondary quotation end character: ’
## Calendar data
#### buddhist calendar
| ID-stuff | values |
| -------- | ------ |
| era | BE |
#### chinese calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Mo1 |
| month 2 | Mo2 |
| month 3 | Mo3 |
| month 4 | Mo4 |
| month 5 | Mo5 |
| month 6 | Mo6 |
| month 7 | Mo7 |
| month 8 | Mo8 |
| month 9 | Mo9 |
| month 10 | Mo10 |
| month 11 | Mo11 |
| month 12 | Mo12 |
| month 1 | First Month |
| month 2 | Second Month |
| month 3 | Third Month |
| month 4 | Fourth Month |
| month 5 | Fifth Month |
| month 6 | Sixth Month |
| month 7 | Seventh Month |
| month 8 | Eighth Month |
| month 9 | Ninth Month |
| month 10 | Tenth Month |
| month 11 | Eleventh Month |
| month 12 | Twelfth Month |
RatOxTigerRabbitDragonSnakeHorseGoatMonkeyRoosterDogPig
| date format | `EEEE, MMMM d, r(U)` |
| date format | `MMMM d, r(U)` |
| date format | `MMM d, r` |
| date format | `M/d/r` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `r(U)` |
| date format `GyMMM` | `MMM r(U)` |
| date format `GyMMMd` | `MMM d, r` |
| date format `GyMMMEd` | `E, MMM d, r(U)` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `ms` | `mm:ss` |
| date format `UM` | `M/U` |
| date format `UMd` | `M/d/U` |
| date format `UMMM` | `MMM U` |
| date format `UMMMd` | `MMM d, U` |
| date format `y` | `r(U)` |
| date format `yMd` | `M/d/r` |
| date format `yyyy` | `r(U)` |
| date format `yyyyM` | `M/r` |
| date format `yyyyMd` | `M/d/r` |
| date format `yyyyMEd` | `E, M/d/r` |
| date format `yyyyMMM` | `MMM r(U)` |
| date format `yyyyMMMd` | `MMM d, r` |
| date format `yyyyMMMEd` | `E, MMM d, r(U)` |
| date format `yyyyMMMM` | `MMMM r(U)` |
| date format `yyyyQQQ` | `QQQ r(U)` |
| date format `yyyyQQQQ` | `QQQQ r(U)` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `U – U` |
| interval format `yM` | `M/y – M/yM/y – M/y` |
| interval format `yMd` | `M/d/y – M/d/yM/d/y – M/d/yM/d/y – M/d/y` |
| interval format `yMEd` | `E, M/d/y – E, M/d/yE, M/d/y – E, M/d/yE, M/d/y – E, M/d/y` |
| interval format `yMMM` | `MMM – MMM UMMM U – MMM U` |
| interval format `yMMMd` | `MMM d – d, UMMM d – MMM d, UMMM d, U – MMM d, U` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, UE, MMM d – E, MMM d, UE, MMM d, U – E, MMM d, U` |
| interval format `yMMMM` | `MMMM – MMMM UMMMM U – MMMM U` |
#### generic calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, MMMM d, y G` |
| date format | `MMMM d, y G` |
| date format | `MMM d, y G` |
| date format | `M/d/y GGGGG` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `MMM d, y G` |
| date format `GyMMMEd` | `E, MMM d, y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `ms` | `mm:ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M/y GGGGG` |
| date format `yyyyMd` | `M/d/y GGGGG` |
| date format `yyyyMEd` | `E, M/d/y GGGGG` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `MMM d, y G` |
| date format `yyyyMMMEd` | `E, MMM d, y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| Day | {0} ({2}: {1}) |
| Day-Of-Week | {0} {1} |
| Era | {0} {1} |
| Hour | {0} ({2}: {1}) |
| Minute | {0} ({2}: {1}) |
| Month | {0} ({2}: {1}) |
| Quarter | {0} ({2}: {1}) |
| Second | {0} ({2}: {1}) |
| Timezone | {0} {1} |
| Week | {0} ({2}: {1}) |
| Year | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `y – y G` |
| interval format `yM` | `M/y – M/y GGGGGM/y – M/y GGGGG` |
| interval format `yMd` | `M/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGGM/d/y – M/d/y GGGGG` |
| interval format `yMEd` | `E, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGGE, M/d/y – E, M/d/y GGGGG` |
| interval format `yMMM` | `MMM – MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `MMM d – d, y GMMM d – MMM d, y GMMM d, y – MMM d, y G` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, y GE, MMM d – E, MMM d, y GE, MMM d, y – E, MMM d, y G` |
| interval format `yMMMM` | `MMMM – MMMM y GMMMM y – MMMM y G` |
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Jan |
| month 2 | Feb |
| month 3 | Mar |
| month 4 | Apr |
| month 5 | May |
| month 6 | Jun |
| month 7 | Jul |
| month 8 | Aug |
| month 9 | Sep |
| month 10 | Oct |
| month 11 | Nov |
| month 12 | Dec |
| month 1 | January |
| month 2 | February |
| month 3 | March |
| month 4 | April |
| month 5 | May |
| month 6 | June |
| month 7 | July |
| month 8 | August |
| month 9 | September |
| month 10 | October |
| month 11 | November |
| month 12 | December |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | A |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | S |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| (week)day sun | Sun |
| (week)day mon | Mon |
| (week)day tue | Tue |
| (week)day wed | Wed |
| (week)day thu | Thu |
| (week)day fri | Fri |
| (week)day sat | Sat |
| (week)day sun | Su |
| (week)day mon | Mo |
| (week)day tue | Tu |
| (week)day wed | We |
| (week)day thu | Th |
| (week)day fri | Fr |
| (week)day sat | Sa |
| (week)day sun | Sunday |
| (week)day mon | Monday |
| (week)day tue | Tuesday |
| (week)day wed | Wednesday |
| (week)day thu | Thursday |
| (week)day fri | Friday |
| (week)day sat | Saturday |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | W |
| (week)day thu | T |
| (week)day fri | F |
| (week)day sat | S |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1st quarter |
| quarter 2 | 2nd quarter |
| quarter 3 | 3rd quarter |
| quarter 4 | 4th quarter |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| period of day midnight | midnight |
| period of day am | AM |
| period of day am | am |
| period of day noon | noon |
| period of day pm | PM |
| period of day pm | pm |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | mi |
| period of day am | a |
| period of day noon | n |
| period of day pm | p |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day am | am |
| period of day noon | noon |
| period of day pm | PM |
| period of day pm | pm |
| period of day morning1 | in the morning |
| period of day afternoon1 | in the afternoon |
| period of day evening1 | in the evening |
| period of day night1 | at night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day noon | noon |
| period of day pm | PM |
| period of day morning1 | morning |
| period of day afternoon1 | afternoon |
| period of day evening1 | evening |
| period of day night1 | night |
| period of day midnight | midnight |
| period of day am | AM |
| period of day noon | noon |
| period of day pm | PM |
| period of day morning1 | morning |
| period of day afternoon1 | afternoon |
| period of day evening1 | evening |
| period of day night1 | night |
| era | Before Christ |
| era | Before Common Era |
| era | Anno Domini |
| era | Common Era |
| era | BC |
| era | BCE |
| era | AD |
| era | CE |
| era | B |
| era | A |
| date format | `EEEE, MMMM d, y` |
| date format | `MMMM d, y` |
| date format | `MMM d, y` |
| date format | `M/d/yy` |
| time format | `h:mm:ss a zzzz` |
| time format | `h:mm:ss a z` |
| time format | `h:mm:ss a` |
| time format | `h:mm a` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1} 'at' {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `d E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `MMM d, y G` |
| date format `GyMMMEd` | `E, MMM d, y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `hmsv` | `h:mm:ss a v` |
| date format `Hmsv` | `HH:mm:ss v` |
| date format `hmv` | `h:mm a v` |
| date format `Hmv` | `HH:mm v` |
| date format `M` | `L` |
| date format `Md` | `M/d` |
| date format `MEd` | `E, M/d` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `E, MMM d` |
| date format `MMMMd` | `MMMM d` |
| date format `MMMMW` | `'week' W 'of' MMMM` |
| date format `MMMMW` | `'week' W 'of' MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `M/y` |
| date format `yMd` | `M/d/y` |
| date format `yMEd` | `E, M/d/y` |
| date format `yMMM` | `MMM y` |
| date format `yMMMd` | `MMM d, y` |
| date format `yMMMEd` | `E, MMM d, y` |
| date format `yMMMM` | `MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
| Day | {0} ({2}: {1}) |
| Day-Of-Week | {0} {1} |
| Era | {0} {1} |
| Hour | {0} ({2}: {1}) |
| Minute | {0} ({2}: {1}) |
| Month | {0} ({2}: {1}) |
| Quarter | {0} ({2}: {1}) |
| Second | {0} ({2}: {1}) |
| Timezone | {0} {1} |
| Week | {0} ({2}: {1}) |
| Year | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d – d` |
| interval format `h` | `h a – h ah – h a` |
| interval format `H` | `HH – HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm – h:mm ah:mm – h:mm a` |
| interval format `Hm` | `HH:mm – HH:mmHH:mm – HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm – h:mm a vh:mm – h:mm a v` |
| interval format `Hmv` | `HH:mm – HH:mm vHH:mm – HH:mm v` |
| interval format `hv` | `h a – h a vh – h a v` |
| interval format `Hv` | `HH – HH v` |
| interval format `M` | `M – M` |
| interval format `Md` | `M/d – M/dM/d – M/d` |
| interval format `MEd` | `E, M/d – E, M/dE, M/d – E, M/d` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `MMM d – dMMM d – MMM d` |
| interval format `MMMEd` | `E, MMM d – E, MMM dE, MMM d – E, MMM d` |
| interval format `y` | `y – y` |
| interval format `yM` | `M/y – M/yM/y – M/y` |
| interval format `yMd` | `M/d/y – M/d/yM/d/y – M/d/yM/d/y – M/d/y` |
| interval format `yMEd` | `E, M/d/y – E, M/d/yE, M/d/y – E, M/d/yE, M/d/y – E, M/d/y` |
| interval format `yMMM` | `MMM – MMM yMMM y – MMM y` |
| interval format `yMMMd` | `MMM d – d, yMMM d – MMM d, yMMM d, y – MMM d, y` |
| interval format `yMMMEd` | `E, MMM d – E, MMM d, yE, MMM d – E, MMM d, yE, MMM d, y – E, MMM d, y` |
| interval format `yMMMM` | `MMMM – MMMM yMMMM y – MMMM y` |
#### hebrew calendar
| ID-stuff | values |
| -------- | ------ |
| era | AM |
| date format | `EEEE, d MMMM y` |
| date format | `d MMMM y` |
| date format | `d MMM y` |
| date format | `d MMM y` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d MMM y G` |
| date format `GyMMMEd` | `E, d MMM y G` |
| date format `M` | `L` |
| date format `Md` | `d MMM` |
| date format `MEd` | `E, d MMM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `E, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `y` | `y` |
| date format `yM` | `MMM y` |
| date format `yMd` | `d MMM y` |
| date format `yMEd` | `E, d MMM y` |
| date format `yMMM` | `MMM y` |
| date format `yMMMd` | `d MMM y` |
| date format `yMMMEd` | `E, d MMM y` |
| date format `yMMMM` | `MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| interval format `M` | `MMM – MMM` |
| interval format `Md` | `d – d MMMd MMM – d MMM` |
| interval format `MEd` | `E, d MMM – E, d MMME, d MMM – E, d MMM` |
| interval format `MMM` | `MMM – MMM` |
| interval format `MMMd` | `d – d MMMd MMM – d MMM` |
| interval format `MMMEd` | `E, d MMM – E, d MMME, d MMM – E, d MMM` |
| interval format `y` | `y – y G` |
| interval format `yM` | `MMM – MMM yMMM y – MMM y` |
| interval format `yMd` | `d – d MMM yd MMM – d MMM yd MMM y – d MMM y` |
| interval format `yMEd` | `E, d MMM – E, d MMM yE, d MMM – E, d MMM yE, d MMM y – E, d MMM y` |
| interval format `yMMM` | `MMM – MMM yMMM y – MMM y` |
| interval format `yMMMd` | `d – d MMM yd MMM – d MMM yd MMM y – d MMM y` |
| interval format `yMMMEd` | `E, d MMM – E, d MMM yE, d MMM – E, d MMM yE, d MMM y – E, d MMM y` |
| interval format `yMMMM` | `MMMM – MMMM yMMMM y – MMMM y` |
#### islamic calendar
| ID-stuff | values |
| -------- | ------ |
| era | AH |
#### japanese calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, MMMM d, y G` |
| date format | `MMMM d, y G` |
| date format | `MMM d, y G` |
| date format | `M/d/y GGGGG` |
#### roc calendar
| ID-stuff | values |
| -------- | ------ |
| era | Before R.O.C. |
| era | Minguo |
### some more time stuff
|  | era |
|  | era |
|  | year |
last yearthis yearnext yearin {0} yearin {0} years{0} year ago{0} years ago
|  | yr. |
last yr.this yr.next yr.in {0} yr.in {0} yr.{0} yr. ago{0} yr. ago
|  | quarter |
last quarterthis quarternext quarterin {0} quarterin {0} quarters{0} quarter ago{0} quarters ago
|  | qtr. |
last qtr.this qtr.next qtr.in {0} qtr.in {0} qtrs.{0} qtr. ago{0} qtrs. ago
|  | month |
last monththis monthnext monthin {0} monthin {0} months{0} month ago{0} months ago
|  | mo. |
last mo.this mo.next mo.in {0} mo.in {0} mo.{0} mo. ago{0} mo. ago
|  | week |
last weekthis weeknext weekin {0} weekin {0} weeks{0} week ago{0} weeks agothe week of {0}
|  | wk. |
last wk.this wk.next wk.in {0} wk.in {0} wk.{0} wk. ago{0} wk. ago
|  | week of month |
|  | wk. of mo. |
|  | day |
yesterdaytodaytomorrowin {0} dayin {0} days{0} day ago{0} days ago
|  | day |
in {0} dayin {0} days{0} day ago{0} days ago
|  | day of year |
|  | day of yr. |
|  | day of the week |
|  | day of wk. |
|  | weekday of the month |
|  | wkday. of mo. |
last Sundaythis Sundaynext Sundayin {0} Sundayin {0} Sundays{0} Sunday ago{0} Sundays agolast Sun.this Sun.next Sun.in {0} Sun.in {0} Sun.{0} Sun. ago{0} Sun. agolast Suthis Sunext Suin {0} Suin {0} Su{0} Su ago{0} Su agolast Mondaythis Mondaynext Mondayin {0} Mondayin {0} Mondays{0} Monday ago{0} Mondays agolast Mon.this Mon.next Mon.in {0} Mon.in {0} Mon.{0} Mon. ago{0} Mon. agolast Mthis Mnext Min {0} Min {0} M{0} M ago{0} M agolast Tuesdaythis Tuesdaynext Tuesdayin {0} Tuesdayin {0} Tuesdays{0} Tuesday ago{0} Tuesdays agolast Tue.this Tue.next Tue.in {0} Tue.in {0} Tue.{0} Tue. ago{0} Tue. agolast Tuthis Tunext Tuin {0} Tuin {0} Tu{0} Tu ago{0} Tu agolast Wednesdaythis Wednesdaynext Wednesdayin {0} Wednesdayin {0} Wednesdays{0} Wednesday ago{0} Wednesdays agolast Wed.this Wed.next Wed.in {0} Wed.in {0} Wed.{0} Wed. ago{0} Wed. agolast Wthis Wnext Win {0} Win {0} W{0} W ago{0} W agolast Thursdaythis Thursdaynext Thursdayin {0} Thursdayin {0} Thursdays{0} Thursday ago{0} Thursdays agolast Thu.this Thu.next Thu.in {0} Thu.in {0} Thu.{0} Thu. ago{0} Thu. agolast Ththis Thnext Thin {0} Thin {0} Th{0} Th ago{0} Th agolast Fridaythis Fridaynext Fridayin {0} Fridayin {0} Fridays{0} Friday ago{0} Fridays agolast Fri.this Fri.next Fri.in {0} Fri.in {0} Fri.{0} Fri. ago{0} Fri. agolast Fthis Fnext Fin {0} Fin {0} F{0} F ago{0} F agolast Saturdaythis Saturdaynext Saturdayin {0} Saturdayin {0} Saturdays{0} Saturday ago{0} Saturdays agolast Sat.this Sat.next Sat.in {0} Sat.in {0} Sat.{0} Sat. ago{0} Sat. agolast Sathis Sanext Sain {0} Sain {0} Sa{0} Sa ago{0} Sa ago
|  | AM/PM |
|  | am/pm |
|  | AM/PM |
|  | am/pm |
|  | hour |
this hourin {0} hourin {0} hours{0} hour ago{0} hours ago
|  | hr. |
in {0} hr.in {0} hr.{0} hr. ago{0} hr. ago
|  | minute |
this minutein {0} minutein {0} minutes{0} minute ago{0} minutes ago
|  | min. |
in {0} min.in {0} min.{0} min. ago{0} min. ago
|  | second |
nowin {0} secondin {0} seconds{0} second ago{0} seconds ago
|  | sec. |
nowin {0} sec.in {0} sec.{0} sec. ago{0} sec. ago
|  | time zone |
|  | zone |
#### time zones
| Format name | Format |
| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| regional | {0} Time |
| regional | {0} Daylight Time |
| regional | {0} Standard Time |
| fallback | {1} ({0}) |
| Zone | Name |
| ---- | ---- |
| Pacific/Honolulu | HSTHSTHDT |
| Etc/UTC | Coordinated Universal Time |
| Etc/Unknown | Unknown City |
| Antarctica/DumontDUrville | Dumont d’Urville |
| America/St_Barthelemy | St. Barthélemy |
| America/Curacao | Curaçao |
| Europe/London | British Summer Time |
| Europe/Dublin | Irish Standard Time |
| America/Asuncion | Asunción |
| Indian/Reunion | Réunion |
| Africa/Sao_Tome | São Tomé |
| Europe/Uzhgorod | Uzhhorod |
| Asia/Saigon | Ho Chi Minh City |
| Acre | Acre TimeAcre Standard TimeAcre Summer Time |
| Afghanistan | Afghanistan Time |
| Africa_Central | Central Africa Time |
| Africa_Eastern | East Africa Time |
| Africa_Southern | South Africa Standard Time |
| Africa_Western | West Africa TimeWest Africa Standard TimeWest Africa Summer Time |
| Alaska | Alaska TimeAlaska Standard TimeAlaska Daylight TimeAKTAKSTAKDT |
| Almaty | Almaty TimeAlmaty Standard TimeAlmaty Summer Time |
| Amazon | Amazon TimeAmazon Standard TimeAmazon Summer Time |
| America_Central | Central TimeCentral Standard TimeCentral Daylight TimeCTCSTCDT |
| America_Eastern | Eastern TimeEastern Standard TimeEastern Daylight TimeETESTEDT |
| America_Mountain | Mountain TimeMountain Standard TimeMountain Daylight TimeMTMSTMDT |
| America_Pacific | Pacific TimePacific Standard TimePacific Daylight TimePTPSTPDT |
| Anadyr | Anadyr TimeAnadyr Standard TimeAnadyr Summer Time |
| Apia | Apia TimeApia Standard TimeApia Daylight Time |
| Aqtau | Aqtau TimeAqtau Standard TimeAqtau Summer Time |
| Aqtobe | Aqtobe TimeAqtobe Standard TimeAqtobe Summer Time |
| Arabian | Arabian TimeArabian Standard TimeArabian Daylight Time |
| Argentina | Argentina TimeArgentina Standard TimeArgentina Summer Time |
| Argentina_Western | Western Argentina TimeWestern Argentina Standard TimeWestern Argentina Summer Time |
| Armenia | Armenia TimeArmenia Standard TimeArmenia Summer Time |
| Atlantic | Atlantic TimeAtlantic Standard TimeAtlantic Daylight TimeATASTADT |
| Australia_Central | Central Australia TimeAustralian Central Standard TimeAustralian Central Daylight Time |
| Australia_CentralWestern | Australian Central Western TimeAustralian Central Western Standard TimeAustralian Central Western Daylight Time |
| Australia_Eastern | Eastern Australia TimeAustralian Eastern Standard TimeAustralian Eastern Daylight Time |
| Australia_Western | Western Australia TimeAustralian Western Standard TimeAustralian Western Daylight Time |
| Azerbaijan | Azerbaijan TimeAzerbaijan Standard TimeAzerbaijan Summer Time |
| Azores | Azores TimeAzores Standard TimeAzores Summer Time |
| Bangladesh | Bangladesh TimeBangladesh Standard TimeBangladesh Summer Time |
| Bhutan | Bhutan Time |
| Bolivia | Bolivia Time |
| Brasilia | Brasilia TimeBrasilia Standard TimeBrasilia Summer Time |
| Brunei | Brunei Darussalam Time |
| Cape_Verde | Cape Verde TimeCape Verde Standard TimeCape Verde Summer Time |
| Casey | Casey Time |
| Chamorro | Chamorro Standard Time |
| Chatham | Chatham TimeChatham Standard TimeChatham Daylight Time |
| Chile | Chile TimeChile Standard TimeChile Summer Time |
| China | China TimeChina Standard TimeChina Daylight Time |
| Choibalsan | Choibalsan TimeChoibalsan Standard TimeChoibalsan Summer Time |
| Christmas | Christmas Island Time |
| Cocos | Cocos Islands Time |
| Colombia | Colombia TimeColombia Standard TimeColombia Summer Time |
| Cook | Cook Islands TimeCook Islands Standard TimeCook Islands Half Summer Time |
| Cuba | Cuba TimeCuba Standard TimeCuba Daylight Time |
| Davis | Davis Time |
| DumontDUrville | Dumont-d’Urville Time |
| East_Timor | East Timor Time |
| Easter | Easter Island TimeEaster Island Standard TimeEaster Island Summer Time |
| Ecuador | Ecuador Time |
| Europe_Central | Central European TimeCentral European Standard TimeCentral European Summer Time |
| Europe_Eastern | Eastern European TimeEastern European Standard TimeEastern European Summer Time |
| Europe_Further_Eastern | Further-eastern European Time |
| Europe_Western | Western European TimeWestern European Standard TimeWestern European Summer Time |
| Falkland | Falkland Islands TimeFalkland Islands Standard TimeFalkland Islands Summer Time |
| Fiji | Fiji TimeFiji Standard TimeFiji Summer Time |
| French_Guiana | French Guiana Time |
| French_Southern | French Southern & Antarctic Time |
| Galapagos | Galapagos Time |
| Gambier | Gambier Time |
| Georgia | Georgia TimeGeorgia Standard TimeGeorgia Summer Time |
| Gilbert_Islands | Gilbert Islands Time |
| GMT | Greenwich Mean TimeGMT |
| Greenland_Eastern | East Greenland TimeEast Greenland Standard TimeEast Greenland Summer Time |
| Greenland_Western | West Greenland TimeWest Greenland Standard TimeWest Greenland Summer Time |
| Guam | Guam Standard Time |
| Gulf | Gulf Standard Time |
| Guyana | Guyana Time |
| Hawaii_Aleutian | Hawaii-Aleutian TimeHawaii-Aleutian Standard TimeHawaii-Aleutian Daylight TimeHATHASTHADT |
| Hong_Kong | Hong Kong TimeHong Kong Standard TimeHong Kong Summer Time |
| Hovd | Hovd TimeHovd Standard TimeHovd Summer Time |
| India | India Standard Time |
| Indian_Ocean | Indian Ocean Time |
| Indochina | Indochina Time |
| Indonesia_Central | Central Indonesia Time |
| Indonesia_Eastern | Eastern Indonesia Time |
| Indonesia_Western | Western Indonesia Time |
| Iran | Iran TimeIran Standard TimeIran Daylight Time |
| Irkutsk | Irkutsk TimeIrkutsk Standard TimeIrkutsk Summer Time |
| Israel | Israel TimeIsrael Standard TimeIsrael Daylight Time |
| Japan | Japan TimeJapan Standard TimeJapan Daylight Time |
| Kamchatka | Petropavlovsk-Kamchatski TimePetropavlovsk-Kamchatski Standard TimePetropavlovsk-Kamchatski Summer Time |
| Kazakhstan_Eastern | East Kazakhstan Time |
| Kazakhstan_Western | West Kazakhstan Time |
| Korea | Korean TimeKorean Standard TimeKorean Daylight Time |
| Kosrae | Kosrae Time |
| Krasnoyarsk | Krasnoyarsk TimeKrasnoyarsk Standard TimeKrasnoyarsk Summer Time |
| Kyrgystan | Kyrgyzstan Time |
| Lanka | Lanka Time |
| Line_Islands | Line Islands Time |
| Lord_Howe | Lord Howe TimeLord Howe Standard TimeLord Howe Daylight Time |
| Macau | Macau TimeMacau Standard TimeMacau Summer Time |
| Macquarie | Macquarie Island Time |
| Magadan | Magadan TimeMagadan Standard TimeMagadan Summer Time |
| Malaysia | Malaysia Time |
| Maldives | Maldives Time |
| Marquesas | Marquesas Time |
| Marshall_Islands | Marshall Islands Time |
| Mauritius | Mauritius TimeMauritius Standard TimeMauritius Summer Time |
| Mawson | Mawson Time |
| Mexico_Northwest | Northwest Mexico TimeNorthwest Mexico Standard TimeNorthwest Mexico Daylight Time |
| Mexico_Pacific | Mexican Pacific TimeMexican Pacific Standard TimeMexican Pacific Daylight Time |
| Mongolia | Ulaanbaatar TimeUlaanbaatar Standard TimeUlaanbaatar Summer Time |
| Moscow | Moscow TimeMoscow Standard TimeMoscow Summer Time |
| Myanmar | Myanmar Time |
| Nauru | Nauru Time |
| Nepal | Nepal Time |
| New_Caledonia | New Caledonia TimeNew Caledonia Standard TimeNew Caledonia Summer Time |
| New_Zealand | New Zealand TimeNew Zealand Standard TimeNew Zealand Daylight Time |
| Newfoundland | Newfoundland TimeNewfoundland Standard TimeNewfoundland Daylight Time |
| Niue | Niue Time |
| Norfolk | Norfolk Island Time |
| Noronha | Fernando de Noronha TimeFernando de Noronha Standard TimeFernando de Noronha Summer Time |
| North_Mariana | North Mariana Islands Time |
| Novosibirsk | Novosibirsk TimeNovosibirsk Standard TimeNovosibirsk Summer Time |
| Omsk | Omsk TimeOmsk Standard TimeOmsk Summer Time |
| Pakistan | Pakistan TimePakistan Standard TimePakistan Summer Time |
| Palau | Palau Time |
| Papua_New_Guinea | Papua New Guinea Time |
| Paraguay | Paraguay TimeParaguay Standard TimeParaguay Summer Time |
| Peru | Peru TimePeru Standard TimePeru Summer Time |
| Philippines | Philippine TimePhilippine Standard TimePhilippine Summer Time |
| Phoenix_Islands | Phoenix Islands Time |
| Pierre_Miquelon | St. Pierre & Miquelon TimeSt. Pierre & Miquelon Standard TimeSt. Pierre & Miquelon Daylight Time |
| Pitcairn | Pitcairn Time |
| Ponape | Ponape Time |
| Pyongyang | Pyongyang Time |
| Qyzylorda | Qyzylorda TimeQyzylorda Standard TimeQyzylorda Summer Time |
| Reunion | Reunion Time |
| Rothera | Rothera Time |
| Sakhalin | Sakhalin TimeSakhalin Standard TimeSakhalin Summer Time |
| Samara | Samara TimeSamara Standard TimeSamara Summer Time |
| Samoa | Samoa TimeSamoa Standard TimeSamoa Daylight Time |
| Seychelles | Seychelles Time |
| Singapore | Singapore Standard Time |
| Solomon | Solomon Islands Time |
| South_Georgia | South Georgia Time |
| Suriname | Suriname Time |
| Syowa | Syowa Time |
| Tahiti | Tahiti Time |
| Taipei | Taipei TimeTaipei Standard TimeTaipei Daylight Time |
| Tajikistan | Tajikistan Time |
| Tokelau | Tokelau Time |
| Tonga | Tonga TimeTonga Standard TimeTonga Summer Time |
| Truk | Chuuk Time |
| Turkmenistan | Turkmenistan TimeTurkmenistan Standard TimeTurkmenistan Summer Time |
| Tuvalu | Tuvalu Time |
| Uruguay | Uruguay TimeUruguay Standard TimeUruguay Summer Time |
| Uzbekistan | Uzbekistan TimeUzbekistan Standard TimeUzbekistan Summer Time |
| Vanuatu | Vanuatu TimeVanuatu Standard TimeVanuatu Summer Time |
| Venezuela | Venezuela Time |
| Vladivostok | Vladivostok TimeVladivostok Standard TimeVladivostok Summer Time |
| Volgograd | Volgograd TimeVolgograd Standard TimeVolgograd Summer Time |
| Vostok | Vostok Time |
| Wake | Wake Island Time |
| Wallis | Wallis & Futuna Time |
| Yakutsk | Yakutsk TimeYakutsk Standard TimeYakutsk Summer Time |
| Yekaterinburg | Yekaterinburg TimeYekaterinburg Standard TimeYekaterinburg Summer Time |
## Numbers stuff
| Character name | Translated version |
| Decimal separator | . |
| "Thousands" separator | , |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | NaN |
#,##0.###0 thousand0 thousand00 thousand00 thousand000 thousand000 thousand0 million0 million00 million00 million000 million000 million0 billion0 billion00 billion00 billion000 billion000 billion0 trillion0 trillion00 trillion00 trillion000 trillion000 trillion0K0K00K00K000K000K0M0M00M00M000M000M0B0B00B00B000B000B0T0T00T00T000T000T#E0#,##0%¤#,##0.00¤#,##0.00;(¤#,##0.00)¤0K¤0K¤00K¤00K¤000K¤000K¤0M¤0M¤00M¤00M¤000M¤000M¤0B¤0B¤00B¤00B¤000B¤000B¤0T¤0T¤00T¤00T¤000T¤000T
| one | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  | Andorran Peseta |
| one | Andorran peseta |
| other | Andorran pesetas |
|  | United Arab Emirates Dirham |
| one | UAE dirham |
| other | UAE dirhams |
|  | Afghan Afghani (1927–2002) |
| one | Afghan afghani (1927–2002) |
| other | Afghan afghanis (1927–2002) |
|  | Afghan Afghani |
| one | Afghan Afghani |
| other | Afghan Afghanis |
|  | Albanian Lek (1946–1965) |
| one | Albanian lek (1946–1965) |
| other | Albanian lekë (1946–1965) |
|  | Albanian Lek |
| one | Albanian lek |
| other | Albanian lekë |
|  | Armenian Dram |
| one | Armenian dram |
| other | Armenian drams |
|  | Netherlands Antillean Guilder |
| one | Netherlands Antillean guilder |
| other | Netherlands Antillean guilders |
|  | Angolan Kwanza |
| one | Angolan kwanza |
| other | Angolan kwanzas |
|  | Angolan Kwanza (1977–1991) |
| one | Angolan kwanza (1977–1991) |
| other | Angolan kwanzas (1977–1991) |
|  | Angolan New Kwanza (1990–2000) |
| one | Angolan new kwanza (1990–2000) |
| other | Angolan new kwanzas (1990–2000) |
|  | Angolan Readjusted Kwanza (1995–1999) |
| one | Angolan readjusted kwanza (1995–1999) |
| other | Angolan readjusted kwanzas (1995–1999) |
|  | Argentine Austral |
| one | Argentine austral |
| other | Argentine australs |
|  | Argentine Peso Ley (1970–1983) |
| one | Argentine peso ley (1970–1983) |
| other | Argentine pesos ley (1970–1983) |
|  | Argentine Peso (1881–1970) |
| one | Argentine peso (1881–1970) |
| other | Argentine pesos (1881–1970) |
|  | Argentine Peso (1983–1985) |
| one | Argentine peso (1983–1985) |
| other | Argentine pesos (1983–1985) |
|  | Argentine Peso |
| one | Argentine peso |
| other | Argentine pesos |
|  | Austrian Schilling |
| one | Austrian schilling |
| other | Austrian schillings |
|  | Australian Dollar |
| one | Australian dollar |
| other | Australian dollars |
|  | Aruban Florin |
| one | Aruban florin |
| other | Aruban florin |
|  | Azerbaijani Manat (1993–2006) |
| one | Azerbaijani manat (1993–2006) |
| other | Azerbaijani manats (1993–2006) |
|  | Azerbaijani Manat |
| one | Azerbaijani manat |
| other | Azerbaijani manats |
|  | Bosnia-Herzegovina Dinar (1992–1994) |
| one | Bosnia-Herzegovina dinar (1992–1994) |
| other | Bosnia-Herzegovina dinars (1992–1994) |
|  | Bosnia-Herzegovina Convertible Mark |
| one | Bosnia-Herzegovina convertible mark |
| other | Bosnia-Herzegovina convertible marks |
|  | Bosnia-Herzegovina New Dinar (1994–1997) |
| one | Bosnia-Herzegovina new dinar (1994–1997) |
| other | Bosnia-Herzegovina new dinars (1994–1997) |
|  | Barbadian Dollar |
| one | Barbadian dollar |
| other | Barbadian dollars |
|  | Bangladeshi Taka |
| one | Bangladeshi taka |
| other | Bangladeshi takas |
|  | Belgian Franc (convertible) |
| one | Belgian franc (convertible) |
| other | Belgian francs (convertible) |
|  | Belgian Franc |
| one | Belgian franc |
| other | Belgian francs |
|  | Belgian Franc (financial) |
| one | Belgian franc (financial) |
| other | Belgian francs (financial) |
|  | Bulgarian Hard Lev |
| one | Bulgarian hard lev |
| other | Bulgarian hard leva |
|  | Bulgarian Socialist Lev |
| one | Bulgarian socialist lev |
| other | Bulgarian socialist leva |
|  | Bulgarian Lev |
| one | Bulgarian lev |
| other | Bulgarian leva |
|  | Bulgarian Lev (1879–1952) |
| one | Bulgarian lev (1879–1952) |
| other | Bulgarian leva (1879–1952) |
|  | Bahraini Dinar |
| one | Bahraini dinar |
| other | Bahraini dinars |
|  | Burundian Franc |
| one | Burundian franc |
| other | Burundian francs |
|  | Bermudan Dollar |
| one | Bermudan dollar |
| other | Bermudan dollars |
|  | Brunei Dollar |
| one | Brunei dollar |
| other | Brunei dollars |
|  | Bolivian Boliviano |
| one | Bolivian boliviano |
| other | Bolivian bolivianos |
|  | Bolivian Boliviano (1863–1963) |
| one | Bolivian boliviano (1863–1963) |
| other | Bolivian bolivianos (1863–1963) |
|  | Bolivian Peso |
| one | Bolivian peso |
| other | Bolivian pesos |
|  | Bolivian Mvdol |
| one | Bolivian mvdol |
| other | Bolivian mvdols |
|  | Brazilian New Cruzeiro (1967–1986) |
| one | Brazilian new cruzeiro (1967–1986) |
| other | Brazilian new cruzeiros (1967–1986) |
|  | Brazilian Cruzado (1986–1989) |
| one | Brazilian cruzado (1986–1989) |
| other | Brazilian cruzados (1986–1989) |
|  | Brazilian Cruzeiro (1990–1993) |
| one | Brazilian cruzeiro (1990–1993) |
| other | Brazilian cruzeiros (1990–1993) |
|  | Brazilian Real |
| one | Brazilian real |
| other | Brazilian reals |
|  | Brazilian New Cruzado (1989–1990) |
| one | Brazilian new cruzado (1989–1990) |
| other | Brazilian new cruzados (1989–1990) |
|  | Brazilian Cruzeiro (1993–1994) |
| one | Brazilian cruzeiro (1993–1994) |
| other | Brazilian cruzeiros (1993–1994) |
|  | Brazilian Cruzeiro (1942–1967) |
| one | Brazilian cruzeiro (1942–1967) |
| other | Brazilian cruzeiros (1942–1967) |
|  | Bahamian Dollar |
| one | Bahamian dollar |
| other | Bahamian dollars |
|  | Bhutanese Ngultrum |
| one | Bhutanese ngultrum |
| other | Bhutanese ngultrums |
|  | Burmese Kyat |
| one | Burmese kyat |
| other | Burmese kyats |
|  | Botswanan Pula |
| one | Botswanan pula |
| other | Botswanan pulas |
|  | Belarusian Ruble (1994–1999) |
| one | Belarusian ruble (1994–1999) |
| other | Belarusian rubles (1994–1999) |
|  | Belarusian Ruble |
| one | Belarusian ruble |
| other | Belarusian rubles |
|  | Belarusian Ruble (2000–2016) |
| one | Belarusian ruble (2000–2016) |
| other | Belarusian rubles (2000–2016) |
|  | Belize Dollar |
| one | Belize dollar |
| other | Belize dollars |
|  | Canadian Dollar |
| one | Canadian dollar |
| other | Canadian dollars |
|  | Congolese Franc |
| one | Congolese franc |
| other | Congolese francs |
|  | WIR Euro |
| one | WIR euro |
| other | WIR euros |
|  | Swiss Franc |
| one | Swiss franc |
| other | Swiss francs |
|  | WIR Franc |
| one | WIR franc |
| other | WIR francs |
|  | Chilean Escudo |
| one | Chilean escudo |
| other | Chilean escudos |
|  | Chilean Unit of Account (UF) |
| one | Chilean unit of account (UF) |
| other | Chilean units of account (UF) |
|  | Chilean Peso |
| one | Chilean peso |
| other | Chilean pesos |
|  | Chinese Yuan (offshore) |
| one | Chinese yuan (offshore) |
| other | Chinese yuan (offshore) |
|  | Chinese People’s Bank Dollar |
| one | Chinese People’s Bank dollar |
| other | Chinese People’s Bank dollars |
|  | Chinese Yuan |
| one | Chinese yuan |
| other | Chinese yuan |
|  | Colombian Peso |
| one | Colombian peso |
| other | Colombian pesos |
|  | Colombian Real Value Unit |
| one | Colombian real value unit |
| other | Colombian real value units |
|  | Costa Rican Colón |
| one | Costa Rican colón |
| other | Costa Rican colóns |
|  | Serbian Dinar (2002–2006) |
| one | Serbian dinar (2002–2006) |
| other | Serbian dinars (2002–2006) |
|  | Czechoslovak Hard Koruna |
| one | Czechoslovak hard koruna |
| other | Czechoslovak hard korunas |
|  | Cuban Convertible Peso |
| one | Cuban convertible peso |
| other | Cuban convertible pesos |
|  | Cuban Peso |
| one | Cuban peso |
| other | Cuban pesos |
|  | Cape Verdean Escudo |
| one | Cape Verdean escudo |
| other | Cape Verdean escudos |
|  | Cypriot Pound |
| one | Cypriot pound |
| other | Cypriot pounds |
|  | Czech Koruna |
| one | Czech koruna |
| other | Czech korunas |
|  | East German Mark |
| one | East German mark |
| other | East German marks |
|  | German Mark |
| one | German mark |
| other | German marks |
|  | Djiboutian Franc |
| one | Djiboutian franc |
| other | Djiboutian francs |
|  | Danish Krone |
| one | Danish krone |
| other | Danish kroner |
|  | Dominican Peso |
| one | Dominican peso |
| other | Dominican pesos |
|  | Algerian Dinar |
| one | Algerian dinar |
| other | Algerian dinars |
|  | Ecuadorian Sucre |
| one | Ecuadorian sucre |
| other | Ecuadorian sucres |
|  | Ecuadorian Unit of Constant Value |
| one | Ecuadorian unit of constant value |
| other | Ecuadorian units of constant value |
|  | Estonian Kroon |
| one | Estonian kroon |
| other | Estonian kroons |
|  | Egyptian Pound |
| one | Egyptian pound |
| other | Egyptian pounds |
|  | Eritrean Nakfa |
| one | Eritrean nakfa |
| other | Eritrean nakfas |
|  | Spanish Peseta (A account) |
| one | Spanish peseta (A account) |
| other | Spanish pesetas (A account) |
|  | Spanish Peseta (convertible account) |
| one | Spanish peseta (convertible account) |
| other | Spanish pesetas (convertible account) |
|  | Spanish Peseta |
| one | Spanish peseta |
| other | Spanish pesetas |
|  | Ethiopian Birr |
| one | Ethiopian birr |
| other | Ethiopian birrs |
|  | Euro |
| one | euro |
| other | euros |
|  | Finnish Markka |
| one | Finnish markka |
| other | Finnish markkas |
|  | Fijian Dollar |
| one | Fijian dollar |
| other | Fijian dollars |
|  | Falkland Islands Pound |
| one | Falkland Islands pound |
| other | Falkland Islands pounds |
|  | French Franc |
| one | French franc |
| other | French francs |
|  | British Pound |
| one | British pound |
| other | British pounds |
|  | Georgian Kupon Larit |
| one | Georgian kupon larit |
| other | Georgian kupon larits |
|  | Georgian Lari |
| one | Georgian lari |
| other | Georgian laris |
|  | Ghanaian Cedi (1979–2007) |
| one | Ghanaian cedi (1979–2007) |
| other | Ghanaian cedis (1979–2007) |
|  | Ghanaian Cedi |
| one | Ghanaian cedi |
| other | Ghanaian cedis |
|  | Gibraltar Pound |
| one | Gibraltar pound |
| other | Gibraltar pounds |
|  | Gambian Dalasi |
| one | Gambian dalasi |
| other | Gambian dalasis |
|  | Guinean Franc |
| one | Guinean franc |
| other | Guinean francs |
|  | Guinean Syli |
| one | Guinean syli |
| other | Guinean sylis |
|  | Equatorial Guinean Ekwele |
| one | Equatorial Guinean ekwele |
| other | Equatorial Guinean ekwele |
|  | Greek Drachma |
| one | Greek drachma |
| other | Greek drachmas |
|  | Guatemalan Quetzal |
| one | Guatemalan quetzal |
| other | Guatemalan quetzals |
|  | Portuguese Guinea Escudo |
| one | Portuguese Guinea escudo |
| other | Portuguese Guinea escudos |
|  | Guinea-Bissau Peso |
| one | Guinea-Bissau peso |
| other | Guinea-Bissau pesos |
|  | Guyanaese Dollar |
| one | Guyanaese dollar |
| other | Guyanaese dollars |
|  | Hong Kong Dollar |
| one | Hong Kong dollar |
| other | Hong Kong dollars |
|  | Honduran Lempira |
| one | Honduran lempira |
| other | Honduran lempiras |
|  | Croatian Dinar |
| one | Croatian dinar |
| other | Croatian dinars |
|  | Croatian Kuna |
| one | Croatian kuna |
| other | Croatian kunas |
|  | Haitian Gourde |
| one | Haitian gourde |
| other | Haitian gourdes |
|  | Hungarian Forint |
| one | Hungarian forint |
| other | Hungarian forints |
|  | Indonesian Rupiah |
| one | Indonesian rupiah |
| other | Indonesian rupiahs |
|  | Irish Pound |
| one | Irish pound |
| other | Irish pounds |
|  | Israeli Pound |
| one | Israeli pound |
| other | Israeli pounds |
|  | Israeli Shekel (1980–1985) |
| one | Israeli shekel (1980–1985) |
| other | Israeli shekels (1980–1985) |
|  | Israeli New Shekel |
| one | Israeli new shekel |
| other | Israeli new shekels |
|  | Indian Rupee |
| one | Indian rupee |
| other | Indian rupees |
|  | Iraqi Dinar |
| one | Iraqi dinar |
| other | Iraqi dinars |
|  | Iranian Rial |
| one | Iranian rial |
| other | Iranian rials |
|  | Icelandic Króna (1918–1981) |
| one | Icelandic króna (1918–1981) |
| other | Icelandic krónur (1918–1981) |
|  | Icelandic Króna |
| one | Icelandic króna |
| other | Icelandic krónur |
|  | Italian Lira |
| one | Italian lira |
| other | Italian liras |
|  | Jamaican Dollar |
| one | Jamaican dollar |
| other | Jamaican dollars |
|  | Jordanian Dinar |
| one | Jordanian dinar |
| other | Jordanian dinars |
|  | Japanese Yen |
| one | Japanese yen |
| other | Japanese yen |
|  symbol | ¥ |
|  | Kenyan Shilling |
| one | Kenyan shilling |
| other | Kenyan shillings |
|  | Kyrgystani Som |
| one | Kyrgystani som |
| other | Kyrgystani soms |
|  | Cambodian Riel |
| one | Cambodian riel |
| other | Cambodian riels |
|  | Comorian Franc |
| one | Comorian franc |
| other | Comorian francs |
|  | North Korean Won |
| one | North Korean won |
| other | North Korean won |
|  | South Korean Hwan (1953–1962) |
| one | South Korean hwan (1953–1962) |
| other | South Korean hwan (1953–1962) |
|  | South Korean Won (1945–1953) |
| one | South Korean won (1945–1953) |
| other | South Korean won (1945–1953) |
|  | South Korean Won |
| one | South Korean won |
| other | South Korean won |
|  | Kuwaiti Dinar |
| one | Kuwaiti dinar |
| other | Kuwaiti dinars |
|  | Cayman Islands Dollar |
| one | Cayman Islands dollar |
| other | Cayman Islands dollars |
|  | Kazakhstani Tenge |
| one | Kazakhstani tenge |
| other | Kazakhstani tenges |
|  | Laotian Kip |
| one | Laotian kip |
| other | Laotian kips |
|  | Lebanese Pound |
| one | Lebanese pound |
| other | Lebanese pounds |
|  | Sri Lankan Rupee |
| one | Sri Lankan rupee |
| other | Sri Lankan rupees |
|  | Liberian Dollar |
| one | Liberian dollar |
| other | Liberian dollars |
|  | Lesotho Loti |
| one | Lesotho loti |
| other | Lesotho lotis |
|  | Lithuanian Litas |
| one | Lithuanian litas |
| other | Lithuanian litai |
|  | Lithuanian Talonas |
| one | Lithuanian talonas |
| other | Lithuanian talonases |
|  | Luxembourgian Convertible Franc |
| one | Luxembourgian convertible franc |
| other | Luxembourgian convertible francs |
|  | Luxembourgian Franc |
| one | Luxembourgian franc |
| other | Luxembourgian francs |
|  | Luxembourg Financial Franc |
| one | Luxembourg financial franc |
| other | Luxembourg financial francs |
|  | Latvian Lats |
| one | Latvian lats |
| other | Latvian lati |
|  | Latvian Ruble |
| one | Latvian ruble |
| other | Latvian rubles |
|  | Libyan Dinar |
| one | Libyan dinar |
| other | Libyan dinars |
|  | Moroccan Dirham |
| one | Moroccan dirham |
| other | Moroccan dirhams |
|  | Moroccan Franc |
| one | Moroccan franc |
| other | Moroccan francs |
|  | Monegasque Franc |
| one | Monegasque franc |
| other | Monegasque francs |
|  | Moldovan Cupon |
| one | Moldovan cupon |
| other | Moldovan cupon |
|  | Moldovan Leu |
| one | Moldovan leu |
| other | Moldovan lei |
|  | Malagasy Ariary |
| one | Malagasy ariary |
| other | Malagasy ariaries |
|  | Malagasy Franc |
| one | Malagasy franc |
| other | Malagasy francs |
|  | Macedonian Denar |
| one | Macedonian denar |
| other | Macedonian denari |
|  | Macedonian Denar (1992–1993) |
| one | Macedonian denar (1992–1993) |
| other | Macedonian denari (1992–1993) |
|  | Malian Franc |
| one | Malian franc |
| other | Malian francs |
|  | Myanmar Kyat |
| one | Myanmar kyat |
| other | Myanmar kyats |
|  | Mongolian Tugrik |
| one | Mongolian tugrik |
| other | Mongolian tugriks |
|  | Macanese Pataca |
| one | Macanese pataca |
| other | Macanese patacas |
|  | Mauritanian Ouguiya |
| one | Mauritanian ouguiya |
| other | Mauritanian ouguiyas |
|  | Maltese Lira |
| one | Maltese lira |
| other | Maltese lira |
|  | Maltese Pound |
| one | Maltese pound |
| other | Maltese pounds |
|  | Mauritian Rupee |
| one | Mauritian rupee |
| other | Mauritian rupees |
|  | Maldivian Rupee (1947–1981) |
| one | Maldivian rupee (1947–1981) |
| other | Maldivian rupees (1947–1981) |
|  | Maldivian Rufiyaa |
| one | Maldivian rufiyaa |
| other | Maldivian rufiyaas |
|  | Malawian Kwacha |
| one | Malawian kwacha |
| other | Malawian kwachas |
|  | Mexican Peso |
| one | Mexican peso |
| other | Mexican pesos |
|  | Mexican Silver Peso (1861–1992) |
| one | Mexican silver peso (1861–1992) |
| other | Mexican silver pesos (1861–1992) |
|  | Mexican Investment Unit |
| one | Mexican investment unit |
| other | Mexican investment units |
|  | Malaysian Ringgit |
| one | Malaysian ringgit |
| other | Malaysian ringgits |
|  | Mozambican Escudo |
| one | Mozambican escudo |
| other | Mozambican escudos |
|  | Mozambican Metical (1980–2006) |
| one | Mozambican metical (1980–2006) |
| other | Mozambican meticals (1980–2006) |
|  | Mozambican Metical |
| one | Mozambican metical |
| other | Mozambican meticals |
|  | Namibian Dollar |
| one | Namibian dollar |
| other | Namibian dollars |
|  | Nigerian Naira |
| one | Nigerian naira |
| other | Nigerian nairas |
|  | Nicaraguan Córdoba (1988–1991) |
| one | Nicaraguan córdoba (1988–1991) |
| other | Nicaraguan córdobas (1988–1991) |
|  | Nicaraguan Córdoba |
| one | Nicaraguan córdoba |
| other | Nicaraguan córdobas |
|  | Dutch Guilder |
| one | Dutch guilder |
| other | Dutch guilders |
|  | Norwegian Krone |
| one | Norwegian krone |
| other | Norwegian kroner |
|  | Nepalese Rupee |
| one | Nepalese rupee |
| other | Nepalese rupees |
|  | New Zealand Dollar |
| one | New Zealand dollar |
| other | New Zealand dollars |
|  | Omani Rial |
| one | Omani rial |
| other | Omani rials |
|  | Panamanian Balboa |
| one | Panamanian balboa |
| other | Panamanian balboas |
|  | Peruvian Inti |
| one | Peruvian inti |
| other | Peruvian intis |
|  | Peruvian Sol |
| one | Peruvian sol |
| other | Peruvian soles |
|  | Peruvian Sol (1863–1965) |
| one | Peruvian sol (1863–1965) |
| other | Peruvian soles (1863–1965) |
|  | Papua New Guinean Kina |
| one | Papua New Guinean kina |
| other | Papua New Guinean kina |
|  | Philippine Piso |
| one | Philippine piso |
| other | Philippine pisos |
|  | Pakistani Rupee |
| one | Pakistani rupee |
| other | Pakistani rupees |
|  | Polish Zloty |
| one | Polish zloty |
| other | Polish zlotys |
|  | Polish Zloty (1950–1995) |
| one | Polish zloty (PLZ) |
| other | Polish zlotys (PLZ) |
|  | Portuguese Escudo |
| one | Portuguese escudo |
| other | Portuguese escudos |
|  | Paraguayan Guarani |
| one | Paraguayan guarani |
| other | Paraguayan guaranis |
|  | Qatari Rial |
| one | Qatari rial |
| other | Qatari rials |
|  | Rhodesian Dollar |
| one | Rhodesian dollar |
| other | Rhodesian dollars |
|  | Romanian Leu (1952–2006) |
| one | Romanian leu (1952–2006) |
| other | Romanian Lei (1952–2006) |
|  | Romanian Leu |
| one | Romanian leu |
| other | Romanian lei |
|  | Serbian Dinar |
| one | Serbian dinar |
| other | Serbian dinars |
|  | Russian Ruble |
| one | Russian ruble |
| other | Russian rubles |
|  | Russian Ruble (1991–1998) |
| one | Russian ruble (1991–1998) |
| other | Russian rubles (1991–1998) |
|  | Rwandan Franc |
| one | Rwandan franc |
| other | Rwandan francs |
|  | Saudi Riyal |
| one | Saudi riyal |
| other | Saudi riyals |
|  | Solomon Islands Dollar |
| one | Solomon Islands dollar |
| other | Solomon Islands dollars |
|  | Seychellois Rupee |
| one | Seychellois rupee |
| other | Seychellois rupees |
|  | Sudanese Dinar (1992–2007) |
| one | Sudanese dinar (1992–2007) |
| other | Sudanese dinars (1992–2007) |
|  | Sudanese Pound |
| one | Sudanese pound |
| other | Sudanese pounds |
|  | Sudanese Pound (1957–1998) |
| one | Sudanese pound (1957–1998) |
| other | Sudanese pounds (1957–1998) |
|  | Swedish Krona |
| one | Swedish krona |
| other | Swedish kronor |
|  | Singapore Dollar |
| one | Singapore dollar |
| other | Singapore dollars |
|  | St. Helena Pound |
| one | St. Helena pound |
| other | St. Helena pounds |
|  | Slovenian Tolar |
| one | Slovenian tolar |
| other | Slovenian tolars |
|  | Slovak Koruna |
| one | Slovak koruna |
| other | Slovak korunas |
|  | Sierra Leonean Leone |
| one | Sierra Leonean leone |
| other | Sierra Leonean leones |
|  | Somali Shilling |
| one | Somali shilling |
| other | Somali shillings |
|  | Surinamese Dollar |
| one | Surinamese dollar |
| other | Surinamese dollars |
|  | Surinamese Guilder |
| one | Surinamese guilder |
| other | Surinamese guilders |
|  | South Sudanese Pound |
| one | South Sudanese pound |
| other | South Sudanese pounds |
|  | São Tomé & Príncipe Dobra (1977–2017) |
| one | São Tomé & Príncipe dobra (1977–2017) |
| other | São Tomé & Príncipe dobras (1977–2017) |
|  | São Tomé & Príncipe Dobra |
| one | São Tomé & Príncipe dobra |
| other | São Tomé & Príncipe dobras |
|  | Soviet Rouble |
| one | Soviet rouble |
| other | Soviet roubles |
|  | Salvadoran Colón |
| one | Salvadoran colón |
| other | Salvadoran colones |
|  | Syrian Pound |
| one | Syrian pound |
| other | Syrian pounds |
|  | Swazi Lilangeni |
| one | Swazi lilangeni |
| other | Swazi emalangeni |
|  | Thai Baht |
| one | Thai baht |
| other | Thai baht |
|  | Tajikistani Ruble |
| one | Tajikistani ruble |
| other | Tajikistani rubles |
|  | Tajikistani Somoni |
| one | Tajikistani somoni |
| other | Tajikistani somonis |
|  | Turkmenistani Manat (1993–2009) |
| one | Turkmenistani manat (1993–2009) |
| other | Turkmenistani manat (1993–2009) |
|  | Turkmenistani Manat |
| one | Turkmenistani manat |
| other | Turkmenistani manat |
|  | Tunisian Dinar |
| one | Tunisian dinar |
| other | Tunisian dinars |
|  | Tongan Paʻanga |
| one | Tongan paʻanga |
| other | Tongan paʻanga |
|  | Timorese Escudo |
| one | Timorese escudo |
| other | Timorese escudos |
|  | Turkish Lira (1922–2005) |
| one | Turkish lira (1922–2005) |
| other | Turkish Lira (1922–2005) |
|  | Turkish Lira |
| one | Turkish lira |
| other | Turkish Lira |
|  | Trinidad & Tobago Dollar |
| one | Trinidad & Tobago dollar |
| other | Trinidad & Tobago dollars |
|  | New Taiwan Dollar |
| one | New Taiwan dollar |
| other | New Taiwan dollars |
|  | Tanzanian Shilling |
| one | Tanzanian shilling |
| other | Tanzanian shillings |
|  | Ukrainian Hryvnia |
| one | Ukrainian hryvnia |
| other | Ukrainian hryvnias |
|  | Ukrainian Karbovanets |
| one | Ukrainian karbovanets |
| other | Ukrainian karbovantsiv |
|  | Ugandan Shilling (1966–1987) |
| one | Ugandan shilling (1966–1987) |
| other | Ugandan shillings (1966–1987) |
|  | Ugandan Shilling |
| one | Ugandan shilling |
| other | Ugandan shillings |
|  | US Dollar |
| one | US dollar |
| other | US dollars |
|  symbol | $ |
|  | US Dollar (Next day) |
| one | US dollar (next day) |
| other | US dollars (next day) |
|  | US Dollar (Same day) |
| one | US dollar (same day) |
| other | US dollars (same day) |
|  | Uruguayan Peso (Indexed Units) |
| one | Uruguayan peso (indexed units) |
| other | Uruguayan pesos (indexed units) |
|  | Uruguayan Peso (1975–1993) |
| one | Uruguayan peso (1975–1993) |
| other | Uruguayan pesos (1975–1993) |
|  | Uruguayan Peso |
| one | Uruguayan peso |
| other | Uruguayan pesos |
|  | Uzbekistani Som |
| one | Uzbekistani som |
| other | Uzbekistani som |
|  | Venezuelan Bolívar (1871–2008) |
| one | Venezuelan bolívar (1871–2008) |
| other | Venezuelan bolívars (1871–2008) |
|  | Venezuelan Bolívar |
| one | Venezuelan bolívar |
| other | Venezuelan bolívars |
|  | Vietnamese Dong |
| one | Vietnamese dong |
| other | Vietnamese dong |
|  | Vietnamese Dong (1978–1985) |
| one | Vietnamese dong (1978–1985) |
| other | Vietnamese dong (1978–1985) |
|  | Vanuatu Vatu |
| one | Vanuatu vatu |
| other | Vanuatu vatus |
|  | Samoan Tala |
| one | Samoan tala |
| other | Samoan tala |
|  | Central African CFA Franc |
| one | Central African CFA franc |
| other | Central African CFA francs |
|  | Silver |
| one | troy ounce of silver |
| other | troy ounces of silver |
|  | Gold |
| one | troy ounce of gold |
| other | troy ounces of gold |
|  | European Composite Unit |
| one | European composite unit |
| other | European composite units |
|  | European Monetary Unit |
| one | European monetary unit |
| other | European monetary units |
|  | European Unit of Account (XBC) |
| one | European unit of account (XBC) |
| other | European units of account (XBC) |
|  | European Unit of Account (XBD) |
| one | European unit of account (XBD) |
| other | European units of account (XBD) |
|  | East Caribbean Dollar |
| one | East Caribbean dollar |
| other | East Caribbean dollars |
|  | Special Drawing Rights |
| one | special drawing rights |
| other | special drawing rights |
|  | European Currency Unit |
| one | European currency unit |
| other | European currency units |
|  | French Gold Franc |
| one | French gold franc |
| other | French gold francs |
|  | French UIC-Franc |
| one | French UIC-franc |
| other | French UIC-francs |
|  | West African CFA Franc |
| one | West African CFA franc |
| other | West African CFA francs |
|  | Palladium |
| one | troy ounce of palladium |
| other | troy ounces of palladium |
|  | CFP Franc |
| one | CFP franc |
| other | CFP francs |
|  | Platinum |
| one | troy ounce of platinum |
| other | troy ounces of platinum |
|  | RINET Funds |
| one | RINET Funds unit |
| other | RINET Funds units |
|  | Sucre |
| one | Sucre |
| other | Sucres |
|  | Testing Currency Code |
| one | Testing Currency unit |
| other | Testing Currency units |
|  | ADB Unit of Account |
| one | ADB unit of account |
| other | ADB units of account |
|  | Unknown Currency |
| one | (unknown unit of currency) |
| other | (unknown currency) |
|  | Yemeni Dinar |
| one | Yemeni dinar |
| other | Yemeni dinars |
|  | Yemeni Rial |
| one | Yemeni rial |
| other | Yemeni rials |
|  | Yugoslavian Hard Dinar (1966–1990) |
| one | Yugoslavian hard dinar (1966–1990) |
| other | Yugoslavian hard dinars (1966–1990) |
|  | Yugoslavian New Dinar (1994–2002) |
| one | Yugoslavian new dinar (1994–2002) |
| other | Yugoslavian new dinars (1994–2002) |
|  | Yugoslavian Convertible Dinar (1990–1992) |
| one | Yugoslavian convertible dinar (1990–1992) |
| other | Yugoslavian convertible dinars (1990–1992) |
|  | Yugoslavian Reformed Dinar (1992–1993) |
| one | Yugoslavian reformed dinar (1992–1993) |
| other | Yugoslavian reformed dinars (1992–1993) |
|  | South African Rand (financial) |
| one | South African rand (financial) |
| other | South African rands (financial) |
|  | South African Rand |
| one | South African rand |
| other | South African rand |
|  | Zambian Kwacha (1968–2012) |
| one | Zambian kwacha (1968–2012) |
| other | Zambian kwachas (1968–2012) |
|  | Zambian Kwacha |
| one | Zambian kwacha |
| other | Zambian kwachas |
|  | Zairean New Zaire (1993–1998) |
| one | Zairean new zaire (1993–1998) |
| other | Zairean new zaires (1993–1998) |
|  | Zairean Zaire (1971–1993) |
| one | Zairean zaire (1971–1993) |
| other | Zairean zaires (1971–1993) |
|  | Zimbabwean Dollar (1980–2008) |
| one | Zimbabwean dollar (1980–2008) |
| other | Zimbabwean dollars (1980–2008) |
|  | Zimbabwean Dollar (2009) |
| one | Zimbabwean dollar (2009) |
| other | Zimbabwean dollars (2009) |
|  | Zimbabwean Dollar (2008) |
| one | Zimbabwean dollar (2008) |
| other | Zimbabwean dollars (2008) |
Other stuff:
{0}+
Examples:
| one example | {0} day |
| other example | {0} days |
Take the {0}rd right.Take the {0}st right.Take the {0}th right.Take the {0}nd right.
## Units
| Code | Name |
| ---- | ---- |
| Compound pattern  | {0} per {1} |
| acceleration-g-force | ... |
|  | g-force |
| one | {0} g-force |
| other | {0} g-force |
| acceleration-meter-per-second-squared | ... |
|  | meters per second squared |
| one | {0} meter per second squared |
| other | {0} meters per second squared |
| angle-revolution | ... |
|  | revolution |
| one | {0} revolution |
| other | {0} revolutions |
| angle-radian | ... |
|  | radians |
| one | {0} radian |
| other | {0} radians |
| angle-degree | ... |
|  | degrees |
| one | {0} degree |
| other | {0} degrees |
| angle-arc-minute | ... |
|  | arcminutes |
| one | {0} arcminute |
| other | {0} arcminutes |
| angle-arc-second | ... |
|  | arcseconds |
| one | {0} arcsecond |
| other | {0} arcseconds |
| area-square-kilometer | ... |
|  | square kilometers |
| one | {0} square kilometer |
| other | {0} square kilometers |
{0} per square kilometer
| area-hectare | ... |
|  | hectares |
| one | {0} hectare |
| other | {0} hectares |
| area-square-meter | ... |
|  | square meters |
| one | {0} square meter |
| other | {0} square meters |
{0} per square meter
| area-square-centimeter | ... |
|  | square centimeters |
| one | {0} square centimeter |
| other | {0} square centimeters |
{0} per square centimeter
| area-square-mile | ... |
|  | square miles |
| one | {0} square mile |
| other | {0} square miles |
{0} per square mile
| area-acre | ... |
|  | acres |
| one | {0} acre |
| other | {0} acres |
| area-square-yard | ... |
|  | square yards |
| one | {0} square yard |
| other | {0} square yards |
| area-square-foot | ... |
|  | square feet |
| one | {0} square foot |
| other | {0} square feet |
| area-square-inch | ... |
|  | square inches |
| one | {0} square inch |
| other | {0} square inches |
{0} per square inch
| concentr-karat | ... |
|  | karats |
| one | {0} karat |
| other | {0} karats |
| concentr-milligram-per-deciliter | ... |
|  | milligrams per deciliter |
| one | {0} milligram per deciliter |
| other | {0} milligrams per deciliter |
| concentr-millimole-per-liter | ... |
|  | millimoles per liter |
| one | {0} millimole per liter |
| other | {0} millimoles per liter |
| concentr-part-per-million | ... |
|  | parts per million |
| one | {0} part per million |
| other | {0} parts per million |
| consumption-liter-per-kilometer | ... |
|  | liters per kilometer |
| one | {0} liter per kilometer |
| other | {0} liters per kilometer |
| consumption-liter-per-100kilometers | ... |
|  | liters per 100 kilometers |
| one | {0} liter per 100 kilometers |
| other | {0} liters per 100 kilometers |
| consumption-mile-per-gallon | ... |
|  | miles per gallon |
| one | {0} mile per gallon |
| other | {0} miles per gallon |
| consumption-mile-per-gallon-imperial | ... |
|  | miles per Imp. gallon |
| one | {0} mile per Imp. gallon |
| other | {0} miles per Imp. gallon |
| digital-terabyte | ... |
|  | terabytes |
| one | {0} terabyte |
| other | {0} terabytes |
| digital-terabit | ... |
|  | terabits |
| one | {0} terabit |
| other | {0} terabits |
| digital-gigabyte | ... |
|  | gigabytes |
| one | {0} gigabyte |
| other | {0} gigabytes |
| digital-gigabit | ... |
|  | gigabits |
| one | {0} gigabit |
| other | {0} gigabits |
| digital-megabyte | ... |
|  | megabytes |
| one | {0} megabyte |
| other | {0} megabytes |
| digital-megabit | ... |
|  | megabits |
| one | {0} megabit |
| other | {0} megabits |
| digital-kilobyte | ... |
|  | kilobytes |
| one | {0} kilobyte |
| other | {0} kilobytes |
| digital-kilobit | ... |
|  | kilobits |
| one | {0} kilobit |
| other | {0} kilobits |
| digital-byte | ... |
|  | bytes |
| one | {0} byte |
| other | {0} bytes |
| digital-bit | ... |
|  | bits |
| one | {0} bit |
| other | {0} bits |
| duration-century | ... |
|  | centuries |
| one | {0} century |
| other | {0} centuries |
| duration-year | ... |
|  | years |
| one | {0} year |
| other | {0} years |
{0} per year
| duration-month | ... |
|  | months |
| one | {0} month |
| other | {0} months |
{0} per month
| duration-week | ... |
|  | weeks |
| one | {0} week |
| other | {0} weeks |
{0} per week
| duration-day | ... |
|  | days |
| one | {0} day |
| other | {0} days |
{0} per day
| duration-hour | ... |
|  | hours |
| one | {0} hour |
| other | {0} hours |
{0} per hour
| duration-minute | ... |
|  | minutes |
| one | {0} minute |
| other | {0} minutes |
{0} per minute
| duration-second | ... |
|  | seconds |
| one | {0} second |
| other | {0} seconds |
{0} per second
| duration-millisecond | ... |
|  | milliseconds |
| one | {0} millisecond |
| other | {0} milliseconds |
| duration-microsecond | ... |
|  | microseconds |
| one | {0} microsecond |
| other | {0} microseconds |
| duration-nanosecond | ... |
|  | nanoseconds |
| one | {0} nanosecond |
| other | {0} nanoseconds |
| electric-ampere | ... |
|  | amperes |
| one | {0} ampere |
| other | {0} amperes |
| electric-milliampere | ... |
|  | milliamperes |
| one | {0} milliampere |
| other | {0} milliamperes |
| electric-ohm | ... |
|  | ohms |
| one | {0} ohm |
| other | {0} ohms |
| electric-volt | ... |
|  | volts |
| one | {0} volt |
| other | {0} volts |
| energy-kilocalorie | ... |
|  | kilocalories |
| one | {0} kilocalorie |
| other | {0} kilocalories |
| energy-calorie | ... |
|  | calories |
| one | {0} calorie |
| other | {0} calories |
| energy-foodcalorie | ... |
|  | Calories |
| one | {0} Calorie |
| other | {0} Calories |
| energy-kilojoule | ... |
|  | kilojoules |
| one | {0} kilojoule |
| other | {0} kilojoules |
| energy-joule | ... |
|  | joules |
| one | {0} joule |
| other | {0} joules |
| energy-kilowatt-hour | ... |
|  | kilowatt-hours |
| one | {0} kilowatt hour |
| other | {0} kilowatt-hours |
| frequency-gigahertz | ... |
|  | gigahertz |
| one | {0} gigahertz |
| other | {0} gigahertz |
| frequency-megahertz | ... |
|  | megahertz |
| one | {0} megahertz |
| other | {0} megahertz |
| frequency-kilohertz | ... |
|  | kilohertz |
| one | {0} kilohertz |
| other | {0} kilohertz |
| frequency-hertz | ... |
|  | hertz |
| one | {0} hertz |
| other | {0} hertz |
| length-kilometer | ... |
|  | kilometers |
| one | {0} kilometer |
| other | {0} kilometers |
{0} per kilometer
| length-meter | ... |
|  | meters |
| one | {0} meter |
| other | {0} meters |
{0} per meter
| length-decimeter | ... |
|  | decimeters |
| one | {0} decimeter |
| other | {0} decimeters |
| length-centimeter | ... |
|  | centimeters |
| one | {0} centimeter |
| other | {0} centimeters |
{0} per centimeter
| length-millimeter | ... |
|  | millimeters |
| one | {0} millimeter |
| other | {0} millimeters |
| length-micrometer | ... |
|  | micrometers |
| one | {0} micrometer |
| other | {0} micrometers |
| length-nanometer | ... |
|  | nanometers |
| one | {0} nanometer |
| other | {0} nanometers |
| length-picometer | ... |
|  | picometers |
| one | {0} picometer |
| other | {0} picometers |
| length-mile | ... |
|  | miles |
| one | {0} mile |
| other | {0} miles |
| length-yard | ... |
|  | yards |
| one | {0} yard |
| other | {0} yards |
| length-foot | ... |
|  | feet |
| one | {0} foot |
| other | {0} feet |
{0} per foot
| length-inch | ... |
|  | inches |
| one | {0} inch |
| other | {0} inches |
{0} per inch
| length-parsec | ... |
|  | parsecs |
| one | {0} parsec |
| other | {0} parsecs |
| length-light-year | ... |
|  | light years |
| one | {0} light year |
| other | {0} light years |
| length-astronomical-unit | ... |
|  | astronomical units |
| one | {0} astronomical unit |
| other | {0} astronomical units |
| length-furlong | ... |
|  | furlongs |
| one | {0} furlong |
| other | {0} furlongs |
| length-fathom | ... |
|  | fathoms |
| one | {0} fathom |
| other | {0} fathoms |
| length-nautical-mile | ... |
|  | nautical miles |
| one | {0} nautical mile |
| other | {0} nautical miles |
| length-mile-scandinavian | ... |
|  | mile-scandinavian |
| one | {0} mile-scandinavian |
| other | {0} miles-scandinavian |
| length-point | ... |
|  | points |
| one | {0} point |
| other | {0} points |
| light-lux | ... |
|  | lux |
| one | {0} lux |
| other | {0} lux |
| mass-metric-ton | ... |
|  | metric tons |
| one | {0} metric ton |
| other | {0} metric tons |
| mass-kilogram | ... |
|  | kilograms |
| one | {0} kilogram |
| other | {0} kilograms |
{0} per kilogram
| mass-gram | ... |
|  | grams |
| one | {0} gram |
| other | {0} grams |
{0} per gram
| mass-milligram | ... |
|  | milligrams |
| one | {0} milligram |
| other | {0} milligrams |
| mass-microgram | ... |
|  | micrograms |
| one | {0} microgram |
| other | {0} micrograms |
| mass-ton | ... |
|  | tons |
| one | {0} ton |
| other | {0} tons |
| mass-stone | ... |
|  | stones |
| one | {0} stone |
| other | {0} stones |
| mass-pound | ... |
|  | pounds |
| one | {0} pound |
| other | {0} pounds |
{0} per pound
| mass-ounce | ... |
|  | ounces |
| one | {0} ounce |
| other | {0} ounces |
{0} per ounce
| mass-ounce-troy | ... |
|  | troy ounces |
| one | {0} troy ounce |
| other | {0} troy ounces |
| mass-carat | ... |
|  | carats |
| one | {0} carat |
| other | {0} carats |
| power-gigawatt | ... |
|  | gigawatts |
| one | {0} gigawatt |
| other | {0} gigawatts |
| power-megawatt | ... |
|  | megawatts |
| one | {0} megawatt |
| other | {0} megawatts |
| power-kilowatt | ... |
|  | kilowatts |
| one | {0} kilowatt |
| other | {0} kilowatts |
| power-watt | ... |
|  | watts |
| one | {0} watt |
| other | {0} watts |
| power-milliwatt | ... |
|  | milliwatts |
| one | {0} milliwatt |
| other | {0} milliwatts |
| power-horsepower | ... |
|  | horsepower |
| one | {0} horsepower |
| other | {0} horsepower |
| pressure-hectopascal | ... |
|  | hectopascals |
| one | {0} hectopascal |
| other | {0} hectopascals |
| pressure-millimeter-of-mercury | ... |
|  | millimeters of mercury |
| one | {0} millimeter of mercury |
| other | {0} millimeters of mercury |
| pressure-pound-per-square-inch | ... |
|  | pounds per square inch |
| one | {0} pound per square inch |
| other | {0} pounds per square inch |
| pressure-inch-hg | ... |
|  | inches of mercury |
| one | {0} inch of mercury |
| other | {0} inches of mercury |
| pressure-millibar | ... |
|  | millibars |
| one | {0} millibar |
| other | {0} millibars |
| speed-kilometer-per-hour | ... |
|  | kilometers per hour |
| one | {0} kilometer per hour |
| other | {0} kilometers per hour |
| speed-meter-per-second | ... |
|  | meters per second |
| one | {0} meter per second |
| other | {0} meters per second |
| speed-mile-per-hour | ... |
|  | miles per hour |
| one | {0} mile per hour |
| other | {0} miles per hour |
| speed-knot | ... |
|  | knots |
| one | {0} knot |
| other | {0} knots |
| temperature-celsius | ... |
|  | degrees Celsius |
| one | {0} degree Celsius |
| other | {0} degrees Celsius |
| temperature-fahrenheit | ... |
|  | degrees Fahrenheit |
| one | {0} degree Fahrenheit |
| other | {0} degrees Fahrenheit |
| temperature-kelvin | ... |
|  | kelvins |
| one | {0} kelvin |
| other | {0} kelvins |
| volume-cubic-kilometer | ... |
|  | cubic kilometers |
| one | {0} cubic kilometer |
| other | {0} cubic kilometers |
| volume-cubic-meter | ... |
|  | cubic meters |
| one | {0} cubic meter |
| other | {0} cubic meters |
{0} per cubic meter
| volume-cubic-centimeter | ... |
|  | cubic centimeters |
| one | {0} cubic centimeter |
| other | {0} cubic centimeters |
{0} per cubic centimeter
| volume-cubic-mile | ... |
|  | cubic miles |
| one | {0} cubic mile |
| other | {0} cubic miles |
| volume-cubic-yard | ... |
|  | cubic yards |
| one | {0} cubic yard |
| other | {0} cubic yards |
| volume-cubic-foot | ... |
|  | cubic feet |
| one | {0} cubic foot |
| other | {0} cubic feet |
| volume-cubic-inch | ... |
|  | cubic inches |
| one | {0} cubic inch |
| other | {0} cubic inches |
| volume-megaliter | ... |
|  | megaliters |
| one | {0} megaliter |
| other | {0} megaliters |
| volume-hectoliter | ... |
|  | hectoliters |
| one | {0} hectoliter |
| other | {0} hectoliters |
| volume-liter | ... |
|  | liters |
| one | {0} liter |
| other | {0} liters |
{0} per liter
| volume-deciliter | ... |
|  | deciliters |
| one | {0} deciliter |
| other | {0} deciliters |
| volume-centiliter | ... |
|  | centiliters |
| one | {0} centiliter |
| other | {0} centiliters |
| volume-milliliter | ... |
|  | milliliters |
| one | {0} milliliter |
| other | {0} milliliters |
| volume-pint-metric | ... |
|  | metric pints |
| one | {0} metric pint |
| other | {0} metric pints |
| volume-cup-metric | ... |
|  | metric cups |
| one | {0} metric cup |
| other | {0} metric cups |
| volume-acre-foot | ... |
|  | acre-feet |
| one | {0} acre-foot |
| other | {0} acre-feet |
| volume-bushel | ... |
|  | bushels |
| one | {0} bushel |
| other | {0} bushels |
| volume-gallon | ... |
|  | gallons |
| one | {0} gallon |
| other | {0} gallons |
{0} per gallon
| volume-gallon-imperial | ... |
|  | Imp. gallons |
| one | {0} Imp. gallon |
| other | {0} Imp. gallons |
{0} per Imp. gallon
| volume-quart | ... |
|  | quarts |
| one | {0} quart |
| other | {0} quarts |
| volume-pint | ... |
|  | pints |
| one | {0} pint |
| other | {0} pints |
| volume-cup | ... |
|  | cups |
| one | {0} cup |
| other | {0} cups |
| volume-fluid-ounce | ... |
|  | fluid ounces |
| one | {0} fluid ounce |
| other | {0} fluid ounces |
| volume-tablespoon | ... |
|  | tablespoons |
| one | {0} tablespoon |
| other | {0} tablespoons |
| volume-teaspoon | ... |
|  | teaspoons |
| one | {0} teaspoon |
| other | {0} teaspoons |
{0} east{0} north{0} south{0} west
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | g-force |
| one | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
|  | meters/sec² |
| one | {0} m/s² |
| other | {0} m/s² |
| angle-revolution | ... |
|  | rev |
| one | {0} rev |
| other | {0} rev |
| angle-radian | ... |
|  | radians |
| one | {0} rad |
| other | {0} rad |
| angle-degree | ... |
|  | degrees |
| one | {0} deg |
| other | {0} deg |
| angle-arc-minute | ... |
|  | arcmins |
| one | {0} arcmin |
| other | {0} arcmins |
| angle-arc-second | ... |
|  | arcsecs |
| one | {0} arcsec |
| other | {0} arcsecs |
| area-square-kilometer | ... |
|  | km² |
| one | {0} km² |
| other | {0} km² |
{0}/km²
| area-hectare | ... |
|  | hectares |
| one | {0} ha |
| other | {0} ha |
| area-square-meter | ... |
|  | meters² |
| one | {0} m² |
| other | {0} m² |
{0}/m²
| area-square-centimeter | ... |
|  | cm² |
| one | {0} cm² |
| other | {0} cm² |
{0}/cm²
| area-square-mile | ... |
|  | sq miles |
| one | {0} sq mi |
| other | {0} sq mi |
{0}/mi²
| area-acre | ... |
|  | acres |
| one | {0} ac |
| other | {0} ac |
| area-square-yard | ... |
|  | yards² |
| one | {0} yd² |
| other | {0} yd² |
| area-square-foot | ... |
|  | sq feet |
| one | {0} sq ft |
| other | {0} sq ft |
| area-square-inch | ... |
|  | inches² |
| one | {0} in² |
| other | {0} in² |
{0}/in²
| concentr-karat | ... |
|  | karats |
| one | {0} kt |
| other | {0} kt |
| concentr-milligram-per-deciliter | ... |
|  | mg/dL |
| one | {0} mg/dL |
| other | {0} mg/dL |
| concentr-millimole-per-liter | ... |
|  | millimol/liter |
| one | {0} mmol/L |
| other | {0} mmol/L |
| concentr-part-per-million | ... |
|  | parts/million |
| one | {0} ppm |
| other | {0} ppm |
| consumption-liter-per-kilometer | ... |
|  | liters/km |
| one | {0} L/km |
| other | {0} L/km |
| consumption-liter-per-100kilometers | ... |
|  | L/100 km |
| one | {0} L/100 km |
| other | {0} L/100 km |
| consumption-mile-per-gallon | ... |
|  | miles/gal |
| one | {0} mpg |
| other | {0} mpg |
| consumption-mile-per-gallon-imperial | ... |
|  | miles/gal Imp. |
| one | {0} mpg Imp. |
| other | {0} mpg Imp. |
| digital-terabyte | ... |
|  | TByte |
| one | {0} TB |
| other | {0} TB |
| digital-terabit | ... |
|  | Tbit |
| one | {0} Tb |
| other | {0} Tb |
| digital-gigabyte | ... |
|  | GByte |
| one | {0} GB |
| other | {0} GB |
| digital-gigabit | ... |
|  | Gbit |
| one | {0} Gb |
| other | {0} Gb |
| digital-megabyte | ... |
|  | MByte |
| one | {0} MB |
| other | {0} MB |
| digital-megabit | ... |
|  | Mbit |
| one | {0} Mb |
| other | {0} Mb |
| digital-kilobyte | ... |
|  | kByte |
| one | {0} kB |
| other | {0} kB |
| digital-kilobit | ... |
|  | kbit |
| one | {0} kb |
| other | {0} kb |
| digital-byte | ... |
|  | byte |
| one | {0} byte |
| other | {0} byte |
| digital-bit | ... |
|  | bit |
| one | {0} bit |
| other | {0} bit |
| duration-century | ... |
|  | c |
| one | {0} c |
| other | {0} c |
| duration-year | ... |
|  | years |
| one | {0} yr |
| other | {0} yrs |
{0}/y
| duration-month | ... |
|  | months |
| one | {0} mth |
| other | {0} mths |
{0}/m
| duration-week | ... |
|  | weeks |
| one | {0} wk |
| other | {0} wks |
{0}/w
| duration-day | ... |
|  | days |
| one | {0} day |
| other | {0} days |
{0}/d
| duration-hour | ... |
|  | hours |
| one | {0} hr |
| other | {0} hr |
{0}/h
| duration-minute | ... |
|  | mins |
| one | {0} min |
| other | {0} min |
{0}/min
| duration-second | ... |
|  | secs |
| one | {0} sec |
| other | {0} sec |
{0}/s
| duration-millisecond | ... |
|  | millisecs |
| one | {0} ms |
| other | {0} ms |
| duration-microsecond | ... |
|  | μsecs |
| one | {0} μs |
| other | {0} μs |
| duration-nanosecond | ... |
|  | nanosecs |
| one | {0} ns |
| other | {0} ns |
| electric-ampere | ... |
|  | amps |
| one | {0} A |
| other | {0} A |
| electric-milliampere | ... |
|  | milliamps |
| one | {0} mA |
| other | {0} mA |
| electric-ohm | ... |
|  | ohms |
| one | {0} Ω |
| other | {0} Ω |
| electric-volt | ... |
|  | volts |
| one | {0} V |
| other | {0} V |
| energy-kilocalorie | ... |
|  | kcal |
| one | {0} kcal |
| other | {0} kcal |
| energy-calorie | ... |
|  | cal |
| one | {0} cal |
| other | {0} cal |
| energy-foodcalorie | ... |
|  | Cal |
| one | {0} Cal |
| other | {0} Cal |
| energy-kilojoule | ... |
|  | kilojoule |
| one | {0} kJ |
| other | {0} kJ |
| energy-joule | ... |
|  | joules |
| one | {0} J |
| other | {0} J |
| energy-kilowatt-hour | ... |
|  | kW-hour |
| one | {0} kWh |
| other | {0} kWh |
| frequency-gigahertz | ... |
|  | GHz |
| one | {0} GHz |
| other | {0} GHz |
| frequency-megahertz | ... |
|  | MHz |
| one | {0} MHz |
| other | {0} MHz |
| frequency-kilohertz | ... |
|  | kHz |
| one | {0} kHz |
| other | {0} kHz |
| frequency-hertz | ... |
|  | Hz |
| one | {0} Hz |
| other | {0} Hz |
| length-kilometer | ... |
|  | km |
| one | {0} km |
| other | {0} km |
{0}/km
| length-meter | ... |
|  | m |
| one | {0} m |
| other | {0} m |
{0}/m
| length-decimeter | ... |
|  | dm |
| one | {0} dm |
| other | {0} dm |
| length-centimeter | ... |
|  | cm |
| one | {0} cm |
| other | {0} cm |
{0}/cm
| length-millimeter | ... |
|  | mm |
| one | {0} mm |
| other | {0} mm |
| length-micrometer | ... |
|  | µmeters |
| one | {0} µm |
| other | {0} µm |
| length-nanometer | ... |
|  | nm |
| one | {0} nm |
| other | {0} nm |
| length-picometer | ... |
|  | pm |
| one | {0} pm |
| other | {0} pm |
| length-mile | ... |
|  | miles |
| one | {0} mi |
| other | {0} mi |
| length-yard | ... |
|  | yards |
| one | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | feet |
| one | {0} ft |
| other | {0} ft |
{0}/ft
| length-inch | ... |
|  | inches |
| one | {0} in |
| other | {0} in |
{0}/in
| length-parsec | ... |
|  | parsecs |
| one | {0} pc |
| other | {0} pc |
| length-light-year | ... |
|  | light yrs |
| one | {0} ly |
| other | {0} ly |
| length-astronomical-unit | ... |
|  | au |
| one | {0} au |
| other | {0} au |
| length-furlong | ... |
|  | furlongs |
| one | {0} fur |
| other | {0} fur |
| length-fathom | ... |
|  | fathoms |
| one | {0} ftm |
| other | {0} ftm |
| length-nautical-mile | ... |
|  | nmi |
| one | {0} nmi |
| other | {0} nmi |
| length-mile-scandinavian | ... |
|  | smi |
| one | {0} smi |
| other | {0} smi |
| length-point | ... |
|  | points |
| one | {0} pt |
| other | {0} pt |
| light-lux | ... |
|  | lux |
| one | {0} lx |
| other | {0} lx |
| mass-metric-ton | ... |
|  | t |
| one | {0} t |
| other | {0} t |
| mass-kilogram | ... |
|  | kg |
| one | {0} kg |
| other | {0} kg |
{0}/kg
| mass-gram | ... |
|  | grams |
| one | {0} g |
| other | {0} g |
{0}/g
| mass-milligram | ... |
|  | mg |
| one | {0} mg |
| other | {0} mg |
| mass-microgram | ... |
|  | µg |
| one | {0} µg |
| other | {0} µg |
| mass-ton | ... |
|  | tons |
| one | {0} tn |
| other | {0} tn |
| mass-stone | ... |
|  | stones |
| one | {0} st |
| other | {0} st |
| mass-pound | ... |
|  | pounds |
| one | {0} lb |
| other | {0} lb |
{0}/lb
| mass-ounce | ... |
|  | oz |
| one | {0} oz |
| other | {0} oz |
{0}/oz
| mass-ounce-troy | ... |
|  | oz troy |
| one | {0} oz t |
| other | {0} oz t |
| mass-carat | ... |
|  | carats |
| one | {0} CD |
| other | {0} CD |
| power-gigawatt | ... |
|  | GW |
| one | {0} GW |
| other | {0} GW |
| power-megawatt | ... |
|  | MW |
| one | {0} MW |
| other | {0} MW |
| power-kilowatt | ... |
|  | kW |
| one | {0} kW |
| other | {0} kW |
| power-watt | ... |
|  | watts |
| one | {0} W |
| other | {0} W |
| power-milliwatt | ... |
|  | mW |
| one | {0} mW |
| other | {0} mW |
| power-horsepower | ... |
|  | hp |
| one | {0} hp |
| other | {0} hp |
| pressure-hectopascal | ... |
|  | hPa |
| one | {0} hPa |
| other | {0} hPa |
| pressure-millimeter-of-mercury | ... |
|  | mmHg |
| one | {0} mmHg |
| other | {0} mmHg |
| pressure-pound-per-square-inch | ... |
|  | psi |
| one | {0} psi |
| other | {0} psi |
| pressure-inch-hg | ... |
|  | inHg |
| one | {0} inHg |
| other | {0} inHg |
| pressure-millibar | ... |
|  | mbar |
| one | {0} mbar |
| other | {0} mbar |
| speed-kilometer-per-hour | ... |
|  | km/hour |
| one | {0} kph |
| other | {0} kph |
| speed-meter-per-second | ... |
|  | meters/sec |
| one | {0} m/s |
| other | {0} m/s |
| speed-mile-per-hour | ... |
|  | miles/hour |
| one | {0} mph |
| other | {0} mph |
| speed-knot | ... |
|  | kn |
| one | {0} kn |
| other | {0} kn |
| temperature-celsius | ... |
|  | deg. C |
| one | {0}°C |
| other | {0}°C |
| temperature-fahrenheit | ... |
|  | deg. F |
| one | {0}°F |
| other | {0}°F |
| temperature-kelvin | ... |
|  | K |
| one | {0} K |
| other | {0} K |
| volume-cubic-kilometer | ... |
|  | km³ |
| one | {0} km³ |
| other | {0} km³ |
| volume-cubic-meter | ... |
|  | m³ |
| one | {0} m³ |
| other | {0} m³ |
| volume-cubic-centimeter | ... |
|  | cm³ |
| one | {0} cm³ |
| other | {0} cm³ |
| volume-cubic-mile | ... |
|  | mi³ |
| one | {0} mi³ |
| other | {0} mi³ |
| volume-cubic-yard | ... |
|  | yards³ |
| one | {0} yd³ |
| other | {0} yd³ |
| volume-cubic-foot | ... |
|  | feet³ |
| one | {0} ft³ |
| other | {0} ft³ |
| volume-cubic-inch | ... |
|  | inches³ |
| one | {0} in³ |
| other | {0} in³ |
| volume-megaliter | ... |
|  | ML |
| one | {0} ML |
| other | {0} ML |
| volume-hectoliter | ... |
|  | hL |
| one | {0} hL |
| other | {0} hL |
| volume-liter | ... |
|  | liters |
| one | {0} L |
| other | {0} L |
{0}/L
| volume-deciliter | ... |
|  | dL |
| one | {0} dL |
| other | {0} dL |
| volume-centiliter | ... |
|  | cL |
| one | {0} cL |
| other | {0} cL |
| volume-milliliter | ... |
|  | mL |
| one | {0} mL |
| other | {0} mL |
| volume-pint-metric | ... |
|  | mpt |
| one | {0} mpt |
| other | {0} mpt |
| volume-cup-metric | ... |
|  | mcup |
| one | {0} mc |
| other | {0} mc |
| volume-acre-foot | ... |
|  | acre ft |
| one | {0} ac ft |
| other | {0} ac ft |
| volume-bushel | ... |
|  | bushels |
| one | {0} bu |
| other | {0} bu |
| volume-gallon | ... |
|  | gal |
| one | {0} gal |
| other | {0} gal |
| volume-gallon-imperial | ... |
|  | Imp. gal |
| one | {0} gal Imp. |
| other | {0} gal Imp. |
| volume-quart | ... |
|  | qts |
| one | {0} qt |
| other | {0} qt |
| volume-pint | ... |
|  | pints |
| one | {0} pt |
| other | {0} pt |
| volume-cup | ... |
|  | cups |
| one | {0} c |
| other | {0} c |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0} fl oz |
| other | {0} fl oz |
| volume-tablespoon | ... |
|  | tbsp |
| one | {0} tbsp |
| other | {0} tbsp |
| volume-teaspoon | ... |
|  | tsp |
| one | {0} tsp |
| other | {0} tsp |
{0} E{0} N{0} S{0} W
| acceleration-g-force | ... |
|  | g-force |
| one | {0}G |
| other | {0}Gs |
| acceleration-meter-per-second-squared | ... |
|  | m/s² |
| one | {0}m/s² |
| other | {0}m/s² |
| angle-revolution | ... |
|  | rev |
| one | {0}rev |
| other | {0}rev |
| angle-radian | ... |
|  | rad |
| one | {0}rad |
| other | {0}rad |
| angle-degree | ... |
|  | deg |
| one | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | arcmin |
| one | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | arcsec |
| one | {0}″ |
| other | {0}″ |
| area-hectare | ... |
|  | hectare |
| one | {0}ha |
| other | {0}ha |
| area-square-centimeter | ... |
|  | cm² |
| one | {0}cm² |
| other | {0}cm² |
| area-square-mile | ... |
|  | mi² |
| one | {0}mi² |
| other | {0}mi² |
{0}/mi²
| area-acre | ... |
|  | acre |
| one | {0}ac |
| other | {0}ac |
| area-square-yard | ... |
|  | yd² |
| one | {0}yd² |
| other | {0}yd² |
| area-square-foot | ... |
|  | ft² |
| one | {0}ft² |
| other | {0}ft² |
| area-square-inch | ... |
|  | in² |
| one | {0}in² |
| other | {0}in² |
| concentr-karat | ... |
|  | karat |
| one | {0}kt |
| other | {0}kt |
| concentr-milligram-per-deciliter | ... |
|  | mg/dL |
| one | {0}mg/dL |
| other | {0}mg/dL |
| concentr-millimole-per-liter | ... |
|  | mmol/L |
| one | {0}mmol/L |
| other | {0}mmol/L |
| concentr-part-per-million | ... |
|  | ppm |
| one | {0}ppm |
| other | {0}ppm |
| consumption-liter-per-kilometer | ... |
|  | L/km |
| one | {0}L/km |
| other | {0}L/km |
| consumption-liter-per-100kilometers | ... |
|  | L/100km |
| one | {0}L/100km |
| other | {0}L/100km |
| consumption-mile-per-gallon | ... |
|  | mpg |
| one | {0}mpg |
| other | {0}mpg |
| consumption-mile-per-gallon-imperial | ... |
|  | mpg UK |
| one | {0}m/gUK |
| other | {0}m/gUK |
| digital-terabyte | ... |
|  | TByte |
| one | {0}TB |
| other | {0}TB |
| digital-terabit | ... |
|  | Tbit |
| one | {0}Tb |
| other | {0}Tb |
| digital-gigabyte | ... |
|  | GByte |
| one | {0}GB |
| other | {0}GB |
| digital-gigabit | ... |
|  | Gbit |
| one | {0}Gb |
| other | {0}Gb |
| digital-megabyte | ... |
|  | MByte |
| one | {0}MB |
| other | {0}MB |
| digital-megabit | ... |
|  | Mbit |
| one | {0}Mb |
| other | {0}Mb |
| digital-kilobyte | ... |
|  | kByte |
| one | {0}kB |
| other | {0}kB |
| digital-kilobit | ... |
|  | kbit |
| one | {0}kb |
| other | {0}kb |
| digital-byte | ... |
|  | byte |
| one | {0}B |
| other | {0}B |
| digital-bit | ... |
|  | bit |
| one | {0}bit |
| other | {0}bit |
| duration-year | ... |
|  | yr |
| one | {0}y |
| other | {0}y |
| duration-month | ... |
|  | month |
| one | {0}m |
| other | {0}m |
| duration-week | ... |
|  | wk |
| one | {0}w |
| other | {0}w |
| duration-day | ... |
|  | day |
| one | {0}d |
| other | {0}d |
| duration-hour | ... |
|  | hour |
| one | {0}h |
| other | {0}h |
| duration-minute | ... |
|  | min |
| one | {0}m |
| other | {0}m |
| duration-second | ... |
|  | sec |
| one | {0}s |
| other | {0}s |
| duration-millisecond | ... |
|  | msec |
| one | {0}ms |
| other | {0}ms |
| duration-microsecond | ... |
|  | μsec |
| one | {0}μs |
| other | {0}μs |
| duration-nanosecond | ... |
|  | ns |
| one | {0}ns |
| other | {0}ns |
| electric-ampere | ... |
|  | amp |
| one | {0}A |
| other | {0}A |
| electric-milliampere | ... |
|  | mA |
| one | {0}mA |
| other | {0}mA |
| electric-ohm | ... |
|  | ohm |
| one | {0}Ω |
| other | {0}Ω |
| electric-volt | ... |
|  | volt |
| one | {0}V |
| other | {0}V |
| energy-kilocalorie | ... |
|  | kcal |
| one | {0}kcal |
| other | {0}kcal |
| energy-calorie | ... |
|  | cal |
| one | {0}cal |
| other | {0}cal |
| energy-foodcalorie | ... |
|  | Cal |
| one | {0}Cal |
| other | {0}Cal |
| energy-kilojoule | ... |
|  | kJ |
| one | {0}kJ |
| other | {0}kJ |
| energy-joule | ... |
|  | joule |
| one | {0}J |
| other | {0}J |
| energy-kilowatt-hour | ... |
|  | kWh |
| one | {0}kWh |
| other | {0}kWh |
| frequency-gigahertz | ... |
|  | GHz |
| one | {0}GHz |
| other | {0}GHz |
| frequency-megahertz | ... |
|  | MHz |
| one | {0}MHz |
| other | {0}MHz |
| frequency-kilohertz | ... |
|  | kHz |
| one | {0}kHz |
| other | {0}kHz |
| frequency-hertz | ... |
|  | Hz |
| one | {0}Hz |
| other | {0}Hz |
| length-kilometer | ... |
|  | km |
| one | {0}km |
| other | {0}km |
| length-meter | ... |
|  | m |
| one | {0}m |
| other | {0}m |
| length-decimeter | ... |
|  | dm |
| one | {0}dm |
| other | {0}dm |
| length-centimeter | ... |
|  | cm |
| one | {0}cm |
| other | {0}cm |
| length-millimeter | ... |
|  | mm |
| one | {0}mm |
| other | {0}mm |
| length-micrometer | ... |
|  | µm |
| one | {0}µm |
| other | {0}µm |
| length-nanometer | ... |
|  | nm |
| one | {0}nm |
| other | {0}nm |
| length-picometer | ... |
|  | pm |
| one | {0}pm |
| other | {0}pm |
| length-mile | ... |
|  | mi |
| one | {0}mi |
| other | {0}mi |
| length-yard | ... |
|  | yd |
| one | {0}yd |
| other | {0}yd |
| length-foot | ... |
|  | ft |
| one | {0}′ |
| other | {0}′ |
| length-inch | ... |
|  | in |
| one | {0}″ |
| other | {0}″ |
| length-parsec | ... |
|  | parsec |
| one | {0}pc |
| other | {0}pc |
| length-light-year | ... |
|  | ly |
| one | {0}ly |
| other | {0}ly |
| length-astronomical-unit | ... |
|  | au |
| one | {0}au |
| other | {0}au |
| length-furlong | ... |
|  | furlong |
| one | {0}fur |
| other | {0}fur |
| length-fathom | ... |
|  | fathom |
| one | {0}fm |
| other | {0}fm |
| length-nautical-mile | ... |
|  | nmi |
| one | {0}nmi |
| other | {0}nmi |
| length-mile-scandinavian | ... |
|  | smi |
| one | {0}smi |
| other | {0}smi |
| length-point | ... |
|  | pts |
| one | {0}pt |
| other | {0}pt |
| light-lux | ... |
|  | lux |
| one | {0}lx |
| other | {0}lx |
| mass-metric-ton | ... |
|  | t |
| one | {0}t |
| other | {0}t |
| mass-kilogram | ... |
|  | kg |
| one | {0}kg |
| other | {0}kg |
| mass-gram | ... |
|  | gram |
| one | {0}g |
| other | {0}g |
| mass-milligram | ... |
|  | mg |
| one | {0}mg |
| other | {0}mg |
| mass-microgram | ... |
|  | µg |
| one | {0}µg |
| other | {0}µg |
| mass-ton | ... |
|  | ton |
| one | {0}tn |
| other | {0}tn |
| mass-stone | ... |
|  | stone |
| one | {0}st |
| other | {0}st |
| mass-pound | ... |
|  | lb |
| one | {0}# |
| other | {0}# |
| mass-ounce | ... |
|  | oz |
| one | {0}oz |
| other | {0}oz |
| mass-ounce-troy | ... |
|  | oz t |
| one | {0}oz t |
| other | {0}oz t |
| mass-carat | ... |
|  | carat |
| one | {0}CD |
| other | {0}CD |
| power-gigawatt | ... |
|  | GW |
| one | {0}GW |
| other | {0}GW |
| power-megawatt | ... |
|  | MW |
| one | {0}MW |
| other | {0}MW |
| power-kilowatt | ... |
|  | kW |
| one | {0}kW |
| other | {0}kW |
| power-watt | ... |
|  | watt |
| one | {0}W |
| other | {0}W |
| power-milliwatt | ... |
|  | mW |
| one | {0}mW |
| other | {0}mW |
| power-horsepower | ... |
|  | hp |
| one | {0}hp |
| other | {0}hp |
| pressure-hectopascal | ... |
|  | hPa |
| one | {0}hPa |
| other | {0}hPa |
| pressure-millimeter-of-mercury | ... |
|  | mmHg |
| one | {0}mmHg |
| other | {0}mmHg |
| pressure-pound-per-square-inch | ... |
|  | psi |
| one | {0}psi |
| other | {0}psi |
| pressure-inch-hg | ... |
|  | ″ Hg |
| one | {0}″ Hg |
| other | {0}″ Hg |
| pressure-millibar | ... |
|  | mbar |
| one | {0}mb |
| other | {0}mb |
| speed-kilometer-per-hour | ... |
|  | km/hr |
| one | {0}kph |
| other | {0}kph |
| speed-meter-per-second | ... |
|  | m/s |
| one | {0}m/s |
| other | {0}m/s |
| speed-mile-per-hour | ... |
|  | mi/hr |
| one | {0}mph |
| other | {0}mph |
| speed-knot | ... |
|  | kn |
| one | {0}kn |
| other | {0}kn |
| temperature-celsius | ... |
|  | °C |
| one | {0}°C |
| other | {0}°C |
| temperature-fahrenheit | ... |
|  | °F |
| one | {0}° |
| other | {0}° |
| temperature-kelvin | ... |
|  | K |
| one | {0}K |
| other | {0}K |
| volume-cubic-kilometer | ... |
|  | km³ |
| one | {0}km³ |
| other | {0}km³ |
| volume-cubic-meter | ... |
|  | m³ |
| one | {0}m³ |
| other | {0}m³ |
{0}/m³
| volume-cubic-centimeter | ... |
|  | cm³ |
| one | {0}cm³ |
| other | {0}cm³ |
{0}/cm³
| volume-cubic-mile | ... |
|  | mi³ |
| one | {0}mi³ |
| other | {0}mi³ |
| volume-cubic-yard | ... |
|  | yd³ |
| one | {0}yd³ |
| other | {0}yd³ |
| volume-cubic-foot | ... |
|  | ft³ |
| one | {0}ft³ |
| other | {0}ft³ |
| volume-cubic-inch | ... |
|  | in³ |
| one | {0}in³ |
| other | {0}in³ |
| volume-megaliter | ... |
|  | ML |
| one | {0}ML |
| other | {0}ML |
| volume-hectoliter | ... |
|  | hL |
| one | {0}hL |
| other | {0}hL |
| volume-liter | ... |
|  | liter |
| one | {0}L |
| other | {0}L |
{0}/L
| volume-deciliter | ... |
|  | dL |
| one | {0}dL |
| other | {0}dL |
| volume-centiliter | ... |
|  | cL |
| one | {0}cL |
| other | {0}cL |
| volume-milliliter | ... |
|  | mL |
| one | {0}mL |
| other | {0}mL |
| volume-pint-metric | ... |
|  | pt |
| one | {0}mpt |
| other | {0}mpt |
| volume-cup-metric | ... |
|  | mcup |
| one | {0}mc |
| other | {0}mc |
| volume-acre-foot | ... |
|  | acre ft |
| one | {0}ac ft |
| other | {0}ac ft |
| volume-bushel | ... |
|  | bushel |
| one | {0}bu |
| other | {0}bu |
| volume-gallon | ... |
|  | gal |
| one | {0}gal |
| other | {0}gal |
{0}/gal
| volume-gallon-imperial | ... |
|  | Imp gal |
| one | {0}galIm |
| other | {0}galIm |
{0}/galIm
| volume-quart | ... |
|  | qt |
| one | {0}qt |
| other | {0}qt |
| volume-pint | ... |
|  | pt |
| one | {0}pt |
| other | {0}pt |
| volume-cup | ... |
|  | cup |
| one | {0}c |
| other | {0}c |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0}fl oz |
| other | {0}fl oz |
| volume-tablespoon | ... |
|  | tbsp |
| one | {0}tbsp |
| other | {0}tbsp |
| volume-teaspoon | ... |
|  | tsp |
| one | {0}tsp |
| other | {0}tsp |
{0}E{0}N{0}S{0}W
## Lists
| List type | Patterns |
|  | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0}, and {1} |
| 2 | {0} and {1} |
| or | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0}, or {1} |
| 2 | {0} or {1} |
| unit | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0}, {1} |
| 2 | {0}, {1} |
| unit-narrow | ... |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
| unit-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0}, {1} |
| 2 | {0}, {1} |
## POSIX
yes:yno:n
## Character sets
| Set | Name |
| --- | ---- |
| all | {0} — all |
| category-list | {0}: {1} |
| compatibility | {0} — compatibility |
| enclosed | {0} — enclosed |
| extended | {0} — extended |
| historic | {0} — historic |
| miscellaneous | {0} — miscellaneous |
| other | {0} — other |
| scripts | scripts — {0} |
| onestrokes | {0} stroke |
| otherstrokes | {0} strokes |
| activities | activity |
| african_scripts | African script |
| american_scripts | American script |
| animal | animal |
| animals_nature | animal or nature |
| arrows | arrow |
| body | body |
| box_drawing | box drawing |
| braille | braille |
| building | building |
| bullets_stars | bullet or star |
| consonantal_jamo | consonantal jamo |
| currency_symbols | currency symbol |
| dash_connector | dash or connector |
| digits | digit |
| dingbats | dingbat |
| divination_symbols | divination symbol |
| downwards_arrows | downwards arrow |
| downwards_upwards_arrows | downwards upwards arrow |
| east_asian_scripts | East Asian script |
| emoji | emoji |
| european_scripts | European script |
| female | female |
| flag | flag |
| flags | flags |
| food_drink | food & drink |
| format | format |
| format_whitespace | format & whitespace |
| full_width_form_variant | full-width variant |
| geometric_shapes | geometric shape |
| half_width_form_variant | half-width variant |
| han_characters | Han character |
| han_radicals | Han radical |
| hanja | hanja |
| hanzi_simplified | Hanzi (simplified) |
| hanzi_traditional | Hanzi (traditional) |
| heart | heart |
| historic_scripts | historic script |
| ideographic_desc_characters | ideographic desc. character |
| japanese_kana | Japanese kana |
| kanbun | kanbun |
| kanji | kanji |
| keycap | keycap |
| leftwards_arrows | leftwards arrow |
| leftwards_rightwards_arrows | leftwards rightwards arrow |
| letterlike_symbols | letterlike symbol |
| limited_use | limited-use |
| male | male |
| math_symbols | math symbol |
| middle_eastern_scripts | Middle Eastern script |
| miscellaneous | miscellaneous |
| modern_scripts | modern script |
| modifier | modifier |
| musical_symbols | musical symbol |
| nature | nature |
| nonspacing | nonspacing |
| numbers | numbers |
| objects | object |
| other | other |
| paired | paired |
| person | person |
| phonetic_alphabet | phonetic alphabet |
| pictographs | pictograph |
| place | place |
| plant | plant |
| punctuation | punctuation |
| rightwards_arrows | rightwards arrow |
| sign_standard_symbols | sign or symbol |
| small_form_variant | small variants |
| smiley | smiley |
| smileys_people | smiley or person |
| south_asian_scripts | South Asian script |
| southeast_asian_scripts | Southeast Asian script |
| spacing | spacing |
| sport | sport |
| symbols | symbol |
| technical_symbols | technical symbol |
| tone_marks | tone mark |
| travel | travel |
| travel_places | travel or place |
| upwards_arrows | upwards arrows |
| variant_forms | variant |
| vocalic_jamo | vocalic jamo |
| weather | weather |
| western_asian_scripts | Western Asian script |
| whitespace | whitespace |
## Font stuff
| Font feature | Name |
| "axis" ital | italic |
| "axis" opsz | optical size |
| "axis" slnt | slant |
| "axis" wdth | width |
| "axis" wght | weight |
| "style" ital1 | cursive |
| "style" opsz8 | caption |
| "style" opsz12 | text |
| "style" opsz18 | titling |
| "style" opsz72 | display |
| "style" opsz144 | poster |
| "style" slnt-12 | back slanted |
| "style" slnt0 | upright |
| "style" slnt12 | slanted |
| "style" slnt24 | extra slanted |
| "style" wdth50 | ultra condensed |
| "style" wdth62.5 | extra condensed |
| "style" wdth75 | condensed |
| "style" wdth87.5 | semi condensed |
| "style" wdth100 | normal |
| "style" wdth112.5 | semi expanded |
| "style" wdth125 | expanded |
| "style" wdth150 | extra expanded |
| "style" wdth200 | ultra expanded |
| "style" wght100 | thin |
| "style" wght200 | extra light |
| "style" wght300 | light |
| "style" wght350 | semi light |
| "style" wght380 | book |
| "style" wght400 | regular |
| "style" wght500 | medium |
| "style" wght600 | semi bold |
| "style" wght700 | bold |
| "style" wght800 | extra bold |
| "style" wght900 | black |
| "style" wght950 | extra black |
| "feature" afrc | vertical fractions |
| "feature" cpsp | capital spacing |
| "feature" dlig | optional ligatures |
| "feature" frac | diagonal fractions |
| "feature" lnum | lining numbers |
| "feature" onum | old-style figures |
| "feature" ordn | ordinals |
| "feature" pnum | proportional numbers |
| "feature" smcp | small capitals |
| "feature" tnum | tabular numbers |
| "feature" zero | slashed zero |
