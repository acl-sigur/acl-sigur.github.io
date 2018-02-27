---
layout: default
title: "CLDR Finnish (via LDML2markdown)"
---

## CLDR core data for Finnish


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
| one example | {0} päivä |
| other example | {0} päivää |
| Country Data and Default Content | fi_FI |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Finnish is already written in latin script |

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
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers

#### search

```
					[import und-u-co-search]
					# Below are the rules specific to fi.
					# Per Apple language group, V and W should match for search.
					[import fi-u-co-trad]

```

#### traditional

```
					&D<<ð<<<Ð<<đ<<<Đ
					&N<<ŋ<<<Ŋ
					&T<<þ/h<<<Þ/h
					&V<<w<<<W
					&Y<<ü<<<Ü<<ű<<<Ű
					&[before 1]ǀ<å<<<Å<ä<<<Ä<<æ<<<Æ<ö<<<Ö<<ø<<<Ø<<ő<<<Ő<<õ<<<Õ<<œ<<<Œ

```

#### standard

```
					# D and U+0335 COMBINING SHORT STROKE OVERLAY
					&D\u0335<<đ<<<Đ  # root order: d\u0335=đ
					# G and U+0335
					&G\u0335<<ǥ<<<Ǥ
					# N and U+0335
					&N\u0335<<ŋ<<<Ŋ
					# T and U+0335
					&T\u0335<<ŧ<<<Ŧ
					&Y<<ü<<<Ü
					# Z and U+0335
					&Z\u0335<<ʒ<<<Ʒ
					&[before 1]ǀ<å<<<Å<ä<<<Ä<<æ<<<Æ<ö<<<Ö<<ø<<<Ø

```

## CLDR minimal data for Finnish

**Needed soon after submitting new locale**.

### Required date-time formats


(44+ needed?)


#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | tammik. |
| month, 2, abbreviated, format | helmik. |
| month, 3, abbreviated, format | maalisk. |
| month, 4, abbreviated, format | huhtik. |
| month, 5, abbreviated, format | toukok. |
| month, 6, abbreviated, format | kesäk. |
| month, 7, abbreviated, format | heinäk. |
| month, 8, abbreviated, format | elok. |
| month, 9, abbreviated, format | syysk. |
| month, 10, abbreviated, format | lokak. |
| month, 11, abbreviated, format | marrask. |
| month, 12, abbreviated, format | jouluk. |
| month, 1, narrow, format | T |
| month, 2, narrow, format | H |
| month, 3, narrow, format | M |
| month, 4, narrow, format | H |
| month, 5, narrow, format | T |
| month, 6, narrow, format | K |
| month, 7, narrow, format | H |
| month, 8, narrow, format | E |
| month, 9, narrow, format | S |
| month, 10, narrow, format | L |
| month, 11, narrow, format | M |
| month, 12, narrow, format | J |
| month, 1, wide, format | tammikuuta |
| month, 2, wide, format | helmikuuta |
| month, 3, wide, format | maaliskuuta |
| month, 4, wide, format | huhtikuuta |
| month, 5, wide, format | toukokuuta |
| month, 6, wide, format | kesäkuuta |
| month, 7, wide, format | heinäkuuta |
| month, 8, wide, format | elokuuta |
| month, 9, wide, format | syyskuuta |
| month, 10, wide, format | lokakuuta |
| month, 11, wide, format | marraskuuta |
| month, 12, wide, format | joulukuuta |
| month, 1, abbreviated, stand-alone | tammi |
| month, 2, abbreviated, stand-alone | helmi |
| month, 3, abbreviated, stand-alone | maalis |
| month, 4, abbreviated, stand-alone | huhti |
| month, 5, abbreviated, stand-alone | touko |
| month, 6, abbreviated, stand-alone | kesä |
| month, 7, abbreviated, stand-alone | heinä |
| month, 8, abbreviated, stand-alone | elo |
| month, 9, abbreviated, stand-alone | syys |
| month, 10, abbreviated, stand-alone | loka |
| month, 11, abbreviated, stand-alone | marras |
| month, 12, abbreviated, stand-alone | joulu |
| month, 1, narrow, stand-alone | T |
| month, 2, narrow, stand-alone | H |
| month, 3, narrow, stand-alone | M |
| month, 4, narrow, stand-alone | H |
| month, 5, narrow, stand-alone | T |
| month, 6, narrow, stand-alone | K |
| month, 7, narrow, stand-alone | H |
| month, 8, narrow, stand-alone | E |
| month, 9, narrow, stand-alone | S |
| month, 10, narrow, stand-alone | L |
| month, 11, narrow, stand-alone | M |
| month, 12, narrow, stand-alone | J |
| month, 1, wide, stand-alone | tammikuu |
| month, 2, wide, stand-alone | helmikuu |
| month, 3, wide, stand-alone | maaliskuu |
| month, 4, wide, stand-alone | huhtikuu |
| month, 5, wide, stand-alone | toukokuu |
| month, 6, wide, stand-alone | kesäkuu |
| month, 7, wide, stand-alone | heinäkuu |
| month, 8, wide, stand-alone | elokuu |
| month, 9, wide, stand-alone | syyskuu |
| month, 10, wide, stand-alone | lokakuu |
| month, 11, wide, stand-alone | marraskuu |
| month, 12, wide, stand-alone | joulukuu |
| (week)day, sun, abbreviated, format | su |
| (week)day, mon, abbreviated, format | ma |
| (week)day, tue, abbreviated, format | ti |
| (week)day, wed, abbreviated, format | ke |
| (week)day, thu, abbreviated, format | to |
| (week)day, fri, abbreviated, format | pe |
| (week)day, sat, abbreviated, format | la |
| (week)day, sun, narrow, format | S |
| (week)day, mon, narrow, format | M |
| (week)day, tue, narrow, format | T |
| (week)day, wed, narrow, format | K |
| (week)day, thu, narrow, format | T |
| (week)day, fri, narrow, format | P |
| (week)day, sat, narrow, format | L |
| (week)day, sun, short, format | su |
| (week)day, mon, short, format | ma |
| (week)day, tue, short, format | ti |
| (week)day, wed, short, format | ke |
| (week)day, thu, short, format | to |
| (week)day, fri, short, format | pe |
| (week)day, sat, short, format | la |
| (week)day, sun, wide, format | sunnuntaina |
| (week)day, mon, wide, format | maanantaina |
| (week)day, tue, wide, format | tiistaina |
| (week)day, wed, wide, format | keskiviikkona |
| (week)day, thu, wide, format | torstaina |
| (week)day, fri, wide, format | perjantaina |
| (week)day, sat, wide, format | lauantaina |
| (week)day, sun, abbreviated, stand-alone | su |
| (week)day, mon, abbreviated, stand-alone | ma |
| (week)day, tue, abbreviated, stand-alone | ti |
| (week)day, wed, abbreviated, stand-alone | ke |
| (week)day, thu, abbreviated, stand-alone | to |
| (week)day, fri, abbreviated, stand-alone | pe |
| (week)day, sat, abbreviated, stand-alone | la |
| (week)day, sun, narrow, stand-alone | S |
| (week)day, mon, narrow, stand-alone | M |
| (week)day, tue, narrow, stand-alone | T |
| (week)day, wed, narrow, stand-alone | K |
| (week)day, thu, narrow, stand-alone | T |
| (week)day, fri, narrow, stand-alone | P |
| (week)day, sat, narrow, stand-alone | L |
| (week)day, sun, short, stand-alone | su |
| (week)day, mon, short, stand-alone | ma |
| (week)day, tue, short, stand-alone | ti |
| (week)day, wed, short, stand-alone | ke |
| (week)day, thu, short, stand-alone | to |
| (week)day, fri, short, stand-alone | pe |
| (week)day, sat, short, stand-alone | la |
| (week)day, sun, wide, stand-alone | sunnuntai |
| (week)day, mon, wide, stand-alone | maanantai |
| (week)day, tue, wide, stand-alone | tiistai |
| (week)day, wed, wide, stand-alone | keskiviikko |
| (week)day, thu, wide, stand-alone | torstai |
| (week)day, fri, wide, stand-alone | perjantai |
| (week)day, sat, wide, stand-alone | lauantai |
| quarter, 1, abbreviated, format | 1. nelj. |
| quarter, 2, abbreviated, format | 2. nelj. |
| quarter, 3, abbreviated, format | 3. nelj. |
| quarter, 4, abbreviated, format | 4. nelj. |
| quarter, 1, narrow, format | 1 |
| quarter, 2, narrow, format | 2 |
| quarter, 3, narrow, format | 3 |
| quarter, 4, narrow, format | 4 |
| quarter, 1, wide, format | 1. neljännes |
| quarter, 2, wide, format | 2. neljännes |
| quarter, 3, wide, format | 3. neljännes |
| quarter, 4, wide, format | 4. neljännes |
| quarter, 1, abbreviated, stand-alone | 1. nelj. |
| quarter, 2, abbreviated, stand-alone | 2. nelj. |
| quarter, 3, abbreviated, stand-alone | 3. nelj. |
| quarter, 4, abbreviated, stand-alone | 4. nelj. |
| quarter, 1, narrow, stand-alone | 1 |
| quarter, 2, narrow, stand-alone | 2 |
| quarter, 3, narrow, stand-alone | 3 |
| quarter, 4, narrow, stand-alone | 4 |
| quarter, 1, wide, stand-alone | 1. neljännes |
| quarter, 2, wide, stand-alone | 2. neljännes |
| quarter, 3, wide, stand-alone | 3. neljännes |
| quarter, 4, wide, stand-alone | 4. neljännes |
| period of day, midnight, abbreviated, format | keskiyöllä |
| period of day, am, abbreviated, format | ap. |
| period of day, noon, abbreviated, format | keskip. |
| period of day, pm, abbreviated, format | ip. |
| period of day, morning1, abbreviated, format | aamulla |
| period of day, morning2, abbreviated, format | aamup. |
| period of day, afternoon1, abbreviated, format | iltap. |
| period of day, evening1, abbreviated, format | illalla |
| period of day, night1, abbreviated, format | yöllä |
| period of day, midnight, narrow, format | ky. |
| period of day, am, narrow, format | ap. |
| period of day, noon, narrow, format | kp. |
| period of day, pm, narrow, format | ip. |
| period of day, morning1, narrow, format | aamulla |
| period of day, morning2, narrow, format | ap. |
| period of day, afternoon1, narrow, format | ip. |
| period of day, evening1, narrow, format | illalla |
| period of day, night1, narrow, format | yöllä |
| period of day, midnight, wide, format | keskiyöllä |
| period of day, am, wide, format | ap. |
| period of day, noon, wide, format | keskipäivällä |
| period of day, pm, wide, format | ip. |
| period of day, morning1, wide, format | aamulla |
| period of day, morning2, wide, format | aamupäivällä |
| period of day, afternoon1, wide, format | iltapäivällä |
| period of day, evening1, wide, format | illalla |
| period of day, night1, wide, format | yöllä |
| period of day, midnight, abbreviated, stand-alone | keskiyö |
| period of day, am, abbreviated, stand-alone | ap. |
| period of day, noon, abbreviated, stand-alone | keskip. |
| period of day, pm, abbreviated, stand-alone | ip. |
| period of day, morning1, abbreviated, stand-alone | aamu |
| period of day, morning2, abbreviated, stand-alone | aamup. |
| period of day, afternoon1, abbreviated, stand-alone | iltap. |
| period of day, evening1, abbreviated, stand-alone | ilta |
| period of day, night1, abbreviated, stand-alone | yö |
| period of day, midnight, narrow, stand-alone | ky. |
| period of day, am, narrow, stand-alone | ap. |
| period of day, noon, narrow, stand-alone | kp. |
| period of day, pm, narrow, stand-alone | ip. |
| period of day, morning1, narrow, stand-alone | aamu |
| period of day, morning2, narrow, stand-alone | ap. |
| period of day, afternoon1, narrow, stand-alone | ip. |
| period of day, evening1, narrow, stand-alone | ilta |
| period of day, night1, narrow, stand-alone | yö |
| period of day, midnight, wide, stand-alone | keskiyö |
| period of day, am, wide, stand-alone | ap. |
| period of day, noon, wide, stand-alone | keskipäivä |
| period of day, pm, wide, stand-alone | ip. |
| period of day, morning1, wide, stand-alone | aamu |
| period of day, morning2, wide, stand-alone | aamupäivä |
| period of day, afternoon1, wide, stand-alone | iltapäivä |
| period of day, evening1, wide, stand-alone | ilta |
| period of day, night1, wide, stand-alone | yö |
| era | ennen Kristuksen syntymää |
| era | ennen ajanlaskun alkua |
| era | jälkeen Kristuksen syntymän |
| era | jälkeen ajanlaskun alun |
| era | eKr. |
| era | eaa. |
| era | jKr. |
| era | jaa. |
| era | eKr |
| era | eaa |
| era | jKr |
| era | jaa |
| date format | ... |
| standard, full | `cccc d. MMMM y` |
| date format | ... |
| standard, long | `d. MMMM y` |
| date format | ... |
| standard, medium | `d.M.y` |
| date format | ... |
| standard, short | `d.M.y` |
| time format | ... |
| standard, full | `H.mm.ss zzzz` |
| time format | ... |
| standard, long | `H.mm.ss z` |
| time format | ... |
| standard, medium | `H.mm.ss` |
| time format | ... |
| standard, short | `H.mm` |
| datetime format | ... |
| standard, full | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, long | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, medium | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, short | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h.mm B` |
| date format `Bhms` | `h.mm.ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h.mm B` |
| date format `EBhms` | `E h.mm.ss B` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E H.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E H.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `hmsv` | `h.mm.ss a v` |
| date format `Hmsv` | `H.mm.ss v` |
| date format `hmv` | `h.mm a v` |
| date format `Hmv` | `H.mm v` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMW` | `LLLL'n' W. 'viikko'` |
| date format `MMMMW` | `LLLL'n' W. 'viikko'` |
| date format `ms` | `m.ss` |
| date format `y` | `y` |
| date format `yM` | `L.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E d.M.y` |
| date format `yMM` | `M.y` |
| date format `yMMM` | `LLL y` |
| date format `yMMMd` | `d. MMM y` |
| date format `yMMMEd` | `E d. MMM y` |
| date format `yMMMM` | `LLLL y` |
| date format `yMMMMccccd` | `cccc d. MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'vuoden' Y 'viikko' w` |
| date format `yw` | `'vuoden' Y 'viikko' w` |
| Timezone | {0} {1} |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d.–d.` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h.mm a – h.mm ah.mm–h.mm ah.mm–h.mm a` |
| interval format `Hm` | `H.mm–H.mmH.mm–H.mm` |
| interval format `hmv` | `h.mm a – h.mm a vh.mm–h.mm a vh.mm–h.mm a v` |
| interval format `Hmv` | `H.mm–H.mm vH.mm–H.mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `d.–d. MMMMd. MMMM – d. MMMM` |
| interval format `MMMEd` | `E d. – E d. MMMME d. MMMM – E d. MMMM` |
| interval format `MMMM` | `LLL–LLLL` |
| interval format `y` | `y–y` |
| interval format `yM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMd` | `d.–d.M.yd.M.–d.M.yd.M.y–d.M.y` |
| interval format `yMEd` | `E d.M.y – E d.M.yE d.M.y – E d.M.yE d.M.y – E d.M.y` |
| interval format `yMMM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMMMd` | `d.–d. MMMM yd. MMMM – d. MMMM yd. MMMM y – d. MMMM y` |
| interval format `yMMMEd` | `E d. – E d. MMMM yE d. MMMM – E d. MMMM yE d. MMMM y – E d. MMMM y` |
| interval format `yMMMM` | `LLL–LLLL yLLLL y – LLLL y` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | ... |
| standard, full | `cccc d. MMMM y G` |
| date format | ... |
| standard, long | `d. MMMM y G` |
| date format | ... |
| standard, medium | `d.M.y G` |
| date format | ... |
| standard, short | `d.M.y GGGGG` |
| datetime format | ... |
| standard, full | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, long | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, medium | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, short | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h.mm B` |
| date format `Bhms` | `h.mm.ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h.mm. B` |
| date format `EBhms` | `E h.mm.ss B` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E HH.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E HH.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMM` | `M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E d. MMM y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyMMMMccccd` | `cccc d. MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d.–d.` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h.mm a – h.mm ah.mm–h.mm ah.mm–h.mm a` |
| interval format `Hm` | `H.mm–H.mmH.mm–H.mm` |
| interval format `hmv` | `h.mm a – h.mm a vh.mm–h.mm a vh.mm–h.mm a v` |
| interval format `Hmv` | `H.mm–H.mm vH.mm–H.mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `d.–d. MMMMd. MMMM – d. MMMM` |
| interval format `MMMEd` | `E d. – E d. MMMME d. MMMM – E d. MMMM` |
| interval format `MMMM` | `LLL–LLLL` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `d.–d. MMMM y Gd. MMMM – d. MMMM y Gd. MMMM y – d. MMMM y G` |
| interval format `yMMMEd` | `E d. – E d. MMMM y GE d. MMMM – E d. MMMM y GE d. MMMM y – E d. MMMM y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |

### Important names in language


Language:

| `fi` | suomi |

Country or territory:

| `FI` | Suomi |

Currency:

| , EUR | euro |
| one, EUR | euro |
| other, EUR | euroa |
| , EUR symbol | € |
| narrow, EUR symbol | € |

### Datetime patterns


(1 needed)

| datetime format | ... |
| standard, full | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, long | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, medium | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, short | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h.mm B` |
| date format `Bhms` | `h.mm.ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h.mm. B` |
| date format `EBhms` | `E h.mm.ss B` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E HH.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E HH.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMM` | `M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E d. MMM y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyMMMMccccd` | `cccc d. MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d.–d.` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h.mm a – h.mm ah.mm–h.mm ah.mm–h.mm a` |
| interval format `Hm` | `H.mm–H.mmH.mm–H.mm` |
| interval format `hmv` | `h.mm a – h.mm a vh.mm–h.mm a vh.mm–h.mm a v` |
| interval format `Hmv` | `H.mm–H.mm vH.mm–H.mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `d.–d. MMMMd. MMMM – d. MMMM` |
| interval format `MMMEd` | `E d. – E d. MMMME d. MMMM – E d. MMMM` |
| interval format `MMMM` | `LLL–LLLL` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `d.–d. MMMM y Gd. MMMM – d. MMMM y Gd. MMMM y – d. MMMM y G` |
| interval format `yMMMEd` | `E d. – E d. MMMM y GE d. MMMM – E d. MMMM y GE d. MMMM y – E d. MMMM y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |

### Number formats


#### Symbols

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
| Not a number | epäluku |
| Time separator (Hours:Minutes) | . |

### Territories, cities  and timezone ID's in language area


Country or territory:

| `FI` | Suomi |
| `FI` | Suomi |
| `RU` | Venäjä |
| `HU` | Unkari |
| `EE` | Viro |

Timezone ID:

| Europe/Helsinki | Helsinki |
| Europe/Moscow | Moskova |
| Asia/Tomsk | Tomsk |
| Europe_Eastern | ... |
|  generic | Itä-Euroopan aika |
|  standard | Itä-Euroopan normaaliaika |
|  daylight savings | Itä-Euroopan kesäaika |
| Moscow | ... |
|  generic | Moskovan aika |
|  standard | Moskovan normaaliaika |
|  daylight savings | Moskovan kesäaika |
| Yekaterinburg | ... |
|  generic | Jekaterinburgin aika |
|  standard | Jekaterinburgin normaaliaika |
|  daylight savings | Jekaterinburgin kesäaika |

### Timezone patterns

| Hours from UTC | +H.mm;-H.mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional | aikavyöhyke: {0} |
| regional | {0} (kesäaika) |
| regional | {0} (normaaliaika) |
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
| `calendar` | kalenteri |
| `cf` | valuuttojen esitysmuoto |
| `colAlternate` | symbolien lajittelu |
| `colBackwards` | painomerkkien lajittelu |
| `colCaseFirst` | isojen ja pienten kirjainten järjestys |
| `colCaseLevel` | aakkoslajien lajittelu |
| `collation` | lajittelujärjestys |
| `colNormalization` | lajittelun normalisointi |
| `colNumeric` | numeroiden lajittelu |
| `colStrength` | lajittelun taso |
| `currency` | valuutta |
| `hc` | tuntijärjestelmä |
| `lb` | rivinvaihtotyyli |
| `ms` | mittajärjestelmä |
| `numbers` | numerot |
| `timezone` | aikavyöhyke |
| `va` | maavalinnan muunnelma |
| `x` | yksityiskäyttö |

### Some time intervals

???

## More (all) CLDR data for $language


While not strictly needed is all used by software and stuff:


identity:

```
$Revision: 13904 $fi
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
| `aa` | afar |
| `ab` | abhaasi |
| `ace` | atšeh |
| `ach` | atšoli |
| `ada` | adangme |
| `ady` | adyge |
| `ae` | avesta |
| `aeb` | tunisianarabia |
| `af` | afrikaans |
| `afh` | afrihili |
| `agq` | aghem |
| `ain` | ainu |
| `ak` | akan |
| `akk` | akkadi |
| `akz` | alabama |
| `ale` | aleutti |
| `aln` | gegi |
| `alt` | altai |
| `am` | amhara |
| `an` | aragonia |
| `ang` | muinaisenglanti |
| `anp` | angika |
| `ar` | arabia |
| `ar_001` | yleisarabia |
| `arc` | valtakunnanaramea |
| `arn` | mapudungun |
| `aro` | araona |
| `arp` | arapaho |
| `arq` | algerianarabia |
| `ars` | arabia – najd |
| `arw` | arawak |
| `ary` | marokonarabia |
| `arz` | egyptinarabia |
| `as` | assami |
| `asa` | asu |
| `ase` | amerikkalainen viittomakieli |
| `ast` | asturia |
| `av` | avaari |
| `avk` | kotava |
| `awa` | awadhi |
| `ay` | aimara |
| `az` | azeri |
| `az` | azeri |
| `ba` | baškiiri |
| `bal` | belutši |
| `ban` | bali |
| `bar` | baijeri |
| `bas` | basaa |
| `bax` | bamum |
| `bbc` | batak-toba |
| `bbj` | ghomala |
| `be` | valkovenäjä |
| `bej` | bedža |
| `bem` | bemba |
| `bew` | betawi |
| `bez` | bena |
| `bfd` | fut |
| `bfq` | badaga |
| `bg` | bulgaria |
| `bgn` | länsibelutši |
| `bho` | bhodžpuri |
| `bi` | bislama |
| `bik` | bikol |
| `bin` | bini |
| `bjn` | banjar |
| `bkm` | kom |
| `bla` | siksika |
| `bm` | bambara |
| `bn` | bengali |
| `bo` | tiibet |
| `bpy` | bišnupria |
| `bqi` | bahtiari |
| `br` | bretoni |
| `bra` | bradž |
| `brh` | brahui |
| `brx` | bodo |
| `bs` | bosnia |
| `bss` | koose |
| `bua` | burjaatti |
| `bug` | bugi |
| `bum` | bulu |
| `byn` | bilin |
| `byv` | medumba |
| `ca` | katalaani |
| `cad` | caddo |
| `car` | karibi |
| `cay` | cayuga |
| `cch` | atsam |
| `ce` | tšetšeeni |
| `ceb` | cebuano |
| `cgg` | kiga |
| `ch` | tšamorro |
| `chb` | tšibtša |
| `chg` | tšagatai |
| `chk` | chuuk |
| `chm` | mari |
| `chn` | chinook-jargon |
| `cho` | choctaw |
| `chp` | chipewyan |
| `chr` | cherokee |
| `chy` | cheyenne |
| `ckb` | sorani |
| `co` | korsika |
| `cop` | kopti |
| `cps` | capiznon |
| `cr` | cree |
| `crh` | krimintataari |
| `crh` | kriminturkki |
| `crs` | seychellienkreoli |
| `cs` | tšekki |
| `csb` | kašubi |
| `cu` | kirkkoslaavi |
| `cv` | tšuvassi |
| `cy` | kymri |
| `da` | tanska |
| `dak` | dakota |
| `dar` | dargi |
| `dav` | taita |
| `de` | saksa |
| `de_AT` | itävallansaksa |
| `de_CH` | sveitsinyläsaksa |
| `del` | delaware |
| `den` | slevi |
| `dgr` | dogrib |
| `din` | dinka |
| `dje` | djerma |
| `doi` | dogri |
| `dsb` | alasorbi |
| `dtp` | dusun |
| `dua` | duala |
| `dum` | keskihollanti |
| `dv` | divehi |
| `dyo` | jola-fonyi |
| `dyu` | djula |
| `dz` | dzongkha |
| `dzg` | dazaga |
| `ebu` | embu |
| `ee` | ewe |
| `efi` | efik |
| `egl` | emilia |
| `egy` | muinaisegypti |
| `eka` | ekajuk |
| `el` | kreikka |
| `elx` | elami |
| `en` | englanti |
| `en_AU` | australianenglanti |
| `en_CA` | kanadanenglanti |
| `en_GB` | britannianenglanti |
| `en_GB` | englanti (Britannia) |
| `en_US` | amerikanenglanti |
| `en_US` | englanti (USA) |
| `enm` | keskienglanti |
| `eo` | esperanto |
| `es` | espanja |
| `es_419` | amerikanespanja |
| `es_ES` | euroopanespanja |
| `es_MX` | meksikonespanja |
| `esu` | alaskanjupik |
| `et` | viro |
| `eu` | baski |
| `ewo` | ewondo |
| `ext` | extremadura |
| `fa` | persia |
| `fa` | persia |
| `fan` | fang |
| `fat` | fanti |
| `ff` | fulani |
| `fi` | suomi |
| `fil` | filipino |
| `fit` | meänkieli |
| `fj` | fidži |
| `fo` | fääri |
| `fon` | fon |
| `fr` | ranska |
| `fr_CA` | kanadanranska |
| `fr_CH` | sveitsinranska |
| `frc` | cajunranska |
| `frm` | keskiranska |
| `fro` | muinaisranska |
| `frp` | arpitaani |
| `frr` | pohjoisfriisi |
| `frs` | itäfriisi |
| `fur` | friuli |
| `fy` | länsifriisi |
| `ga` | iiri |
| `gaa` | ga |
| `gag` | gagauzi |
| `gan` | gan-kiina |
| `gay` | gajo |
| `gba` | gbaja |
| `gbz` | zoroastrialaisdari |
| `gd` | gaeli |
| `gez` | ge’ez |
| `gil` | kiribati |
| `gl` | galicia |
| `glk` | gilaki |
| `gmh` | keskiyläsaksa |
| `gn` | guarani |
| `goh` | muinaisyläsaksa |
| `gom` | goankonkani |
| `gon` | gondi |
| `gor` | gorontalo |
| `got` | gootti |
| `grb` | grebo |
| `grc` | muinaiskreikka |
| `gsw` | sveitsinsaksa |
| `gu` | gudžarati |
| `guc` | wayuu |
| `gur` | frafra |
| `guz` | gusii |
| `gv` | manksi |
| `gwi` | gwitšin |
| `ha` | hausa |
| `hai` | haida |
| `hak` | hakka-kiina |
| `haw` | havaiji |
| `he` | heprea |
| `hi` | hindi |
| `hif` | fidžinhindi |
| `hil` | hiligaino |
| `hit` | heetti |
| `hmn` | hmong |
| `ho` | hiri-motu |
| `hr` | kroatia |
| `hsb` | yläsorbi |
| `hsn` | xiang-kiina |
| `ht` | haiti |
| `hu` | unkari |
| `hup` | hupa |
| `hy` | armenia |
| `hz` | herero |
| `ia` | interlingua |
| `iba` | iban |
| `ibb` | ibibio |
| `id` | indonesia |
| `ie` | interlingue |
| `ig` | igbo |
| `ii` | sichuanin-yi |
| `ik` | inupiaq |
| `ilo` | iloko |
| `inh` | inguuši |
| `io` | ido |
| `is` | islanti |
| `it` | italia |
| `iu` | inuktitut |
| `izh` | inkeroinen |
| `ja` | japani |
| `jam` | jamaikankreolienglanti |
| `jbo` | lojban |
| `jgo` | ngomba |
| `jmc` | machame |
| `jpr` | juutalaispersia |
| `jrb` | juutalaisarabia |
| `jut` | juutti |
| `jv` | jaava |
| `ka` | georgia |
| `kaa` | karakalpakki |
| `kab` | kabyyli |
| `kac` | katšin |
| `kaj` | jju |
| `kam` | kamba |
| `kaw` | kavi |
| `kbd` | kabardi |
| `kbl` | kanembu |
| `kcg` | tyap |
| `kde` | makonde |
| `kea` | kapverdenkreoli |
| `ken` | kenyang |
| `kfo` | norsunluurannikonkoro |
| `kg` | kongo |
| `kgp` | kaingang |
| `kha` | khasi |
| `kho` | khotani |
| `khq` | koyra chiini |
| `khw` | khowar |
| `ki` | kikuju |
| `kiu` | kirmanjki |
| `kj` | kuanjama |
| `kk` | kazakki |
| `kkj` | kako |
| `kl` | kalaallisut |
| `kl` | grönlanti |
| `kln` | kalenjin |
| `km` | khmer |
| `kmb` | kimbundu |
| `kn` | kannada |
| `ko` | korea |
| `koi` | komipermjakki |
| `kok` | konkani |
| `kos` | kosrae |
| `kpe` | kpelle |
| `kr` | kanuri |
| `krc` | karatšai-balkaari |
| `kri` | krio |
| `krj` | kinaray-a |
| `krl` | karjala |
| `kru` | kurukh |
| `ks` | kašmiri |
| `ksb` | shambala |
| `ksf` | bafia |
| `ksh` | kölsch |
| `ku` | kurdi |
| `kum` | kumykki |
| `kut` | kutenai |
| `kv` | komi |
| `kw` | korni |
| `ky` | kirgiisi |
| `la` | latina |
| `lad` | ladino |
| `lad` | juutalaisespanja |
| `lag` | lango |
| `lah` | lahnda |
| `lam` | lamba |
| `lb` | luxemburg |
| `lez` | lezgi |
| `lfn` | lingua franca nova |
| `lg` | ganda |
| `li` | limburg |
| `lij` | liguuri |
| `liv` | liivi |
| `lkt` | lakota |
| `lmo` | lombardi |
| `ln` | lingala |
| `lo` | lao |
| `lol` | mongo |
| `lou` | louisianankreoli |
| `loz` | lozi |
| `lrc` | pohjoisluri |
| `lt` | liettua |
| `ltg` | latgalli |
| `lu` | katanganluba |
| `lua` | luluanluba |
| `lui` | luiseño |
| `lun` | lunda |
| `luo` | luo |
| `lus` | lusai |
| `luy` | luhya |
| `lv` | latvia |
| `lzh` | klassinen kiina |
| `lzz` | lazi |
| `mad` | madura |
| `maf` | mafa |
| `mag` | magahi |
| `mai` | maithili |
| `mak` | makassar |
| `man` | mandingo |
| `mas` | maasai |
| `mde` | maba |
| `mdf` | mokša |
| `mdr` | mandar |
| `men` | mende |
| `mer` | meru |
| `mfe` | morisyen |
| `mg` | malagassi |
| `mga` | keski-iiri |
| `mgh` | makua-meetto |
| `mgo` | meta’ |
| `mh` | marshall |
| `mi` | maori |
| `mic` | micmac |
| `min` | minangkabau |
| `mk` | makedonia |
| `ml` | malajalam |
| `mn` | mongoli |
| `mnc` | mantšu |
| `mni` | manipuri |
| `moh` | mohawk |
| `mos` | mossi |
| `mr` | marathi |
| `mrj` | vuorimari |
| `ms` | malaiji |
| `mt` | malta |
| `mua` | mundang |
| `mul` | useita kieliä |
| `mus` | creek |
| `mwl` | mirandeesi |
| `mwr` | marwari |
| `mwv` | mentawai |
| `my` | burma |
| `mye` | myene |
| `myv` | ersä |
| `mzn` | mazandarani |
| `na` | nauru |
| `nan` | min nan -kiina |
| `nap` | napoli |
| `naq` | nama |
| `nb` | norjan bokmål |
| `nd` | pohjois-ndebele |
| `nds` | alasaksa |
| `nds_NL` | alankomaidenalasaksa |
| `ne` | nepali |
| `new` | newari |
| `ng` | ndonga |
| `nia` | nias |
| `niu` | niue |
| `njo` | ao naga |
| `nl` | hollanti |
| `nl_BE` | flaami |
| `nmg` | kwasio |
| `nn` | norjan nynorsk |
| `nnh` | ngiemboon |
| `no` | norja |
| `nog` | nogai |
| `non` | muinaisnorja |
| `nov` | novial |
| `nqo` | n’ko |
| `nr` | etelä-ndebele |
| `nso` | pohjoissotho |
| `nus` | nuer |
| `nv` | navajo |
| `nwc` | klassinen newari |
| `ny` | njandža |
| `nym` | nyamwezi |
| `nyn` | nyankole |
| `nyo` | nyoro |
| `nzi` | nzima |
| `oc` | oksitaani |
| `oj` | odžibwa |
| `om` | oromo |
| `or` | orija |
| `os` | osseetti |
| `osa` | osage |
| `ota` | osmani |
| `pa` | pandžabi |
| `pag` | pangasinan |
| `pal` | pahlavi |
| `pam` | pampanga |
| `pap` | papiamentu |
| `pau` | palau |
| `pcd` | picardi |
| `pcm` | nigerianpidgin |
| `pdc` | pennsylvaniansaksa |
| `pdt` | plautdietsch |
| `peo` | muinaispersia |
| `pfl` | pfaltsi |
| `phn` | foinikia |
| `pi` | paali |
| `pl` | puola |
| `pms` | piemonte |
| `pnt` | pontoksenkreikka |
| `pon` | pohnpei |
| `prg` | muinaispreussi |
| `pro` | muinaisprovensaali |
| `ps` | paštu |
| `pt` | portugali |
| `pt_BR` | brasilianportugali |
| `pt_PT` | euroopanportugali |
| `qu` | ketšua |
| `quc` | kʼicheʼ |
| `qug` | chimborazonylänköketšua |
| `raj` | radžastani |
| `rap` | rapanui |
| `rar` | rarotonga |
| `rgn` | romagnoli |
| `rif` | tarifit |
| `rm` | retoromaani |
| `rn` | rundi |
| `ro` | romania |
| `ro_MD` | moldova |
| `rof` | rombo |
| `rom` | romani |
| `root` | juuri |
| `rtm` | rotuma |
| `ru` | venäjä |
| `rue` | ruteeni |
| `rug` | roviana |
| `rup` | aromania |
| `rw` | ruanda |
| `rwk` | rwa |
| `sa` | sanskrit |
| `sad` | sandawe |
| `sah` | jakuutti |
| `sam` | samarianaramea |
| `saq` | samburu |
| `sas` | sasak |
| `sat` | santali |
| `saz` | sauraštri |
| `sba` | ngambay |
| `sbp` | sangu |
| `sc` | sardi |
| `scn` | sisilia |
| `sco` | skotti |
| `sd` | sindhi |
| `sdc` | sassarinsardi |
| `sdh` | eteläkurdi |
| `se` | pohjoissaame |
| `see` | seneca |
| `seh` | sena |
| `sei` | seri |
| `sel` | selkuppi |
| `ses` | koyraboro senni |
| `sg` | sango |
| `sga` | muinaisiiri |
| `sgs` | samogiitti |
| `sh` | serbokroaatti |
| `shi` | tašelhit |
| `shn` | shan |
| `shu` | tšadinarabia |
| `si` | sinhala |
| `sid` | sidamo |
| `sk` | slovakki |
| `sl` | sloveeni |
| `sli` | sleesiansaksa |
| `sly` | selayar |
| `sm` | samoa |
| `sma` | eteläsaame |
| `smj` | luulajansaame |
| `smn` | inarinsaame |
| `sms` | koltansaame |
| `sn` | šona |
| `snk` | soninke |
| `so` | somali |
| `sog` | sogdi |
| `sq` | albania |
| `sr` | serbia |
| `srn` | sranan |
| `srr` | serer |
| `ss` | swazi |
| `ssy` | saho |
| `st` | eteläsotho |
| `stq` | saterlandinfriisi |
| `su` | sunda |
| `suk` | sukuma |
| `sus` | susu |
| `sux` | sumeri |
| `sv` | ruotsi |
| `sw` | swahili |
| `sw_CD` | kingwana |
| `swb` | komori |
| `syc` | muinaissyyria |
| `syr` | syyria |
| `szl` | sleesia |
| `ta` | tamili |
| `tcy` | tulu |
| `te` | telugu |
| `tem` | temne |
| `teo` | teso |
| `ter` | tereno |
| `tet` | tetum |
| `tg` | tadžikki |
| `th` | thai |
| `ti` | tigrinja |
| `tig` | tigre |
| `tiv` | tiv |
| `tk` | turkmeeni |
| `tkl` | tokelau |
| `tkr` | tsahuri |
| `tl` | tagalog |
| `tlh` | klingon |
| `tli` | tlingit |
| `tly` | tališi |
| `tmh` | tamašek |
| `tn` | tswana |
| `to` | tonga |
| `tog` | malawintonga |
| `tpi` | tok-pisin |
| `tr` | turkki |
| `tru` | turojo |
| `trv` | taroko |
| `ts` | tsonga |
| `tsd` | tsakonia |
| `tsi` | tsimši |
| `tt` | tataari |
| `ttt` | tati |
| `tum` | tumbuka |
| `tvl` | tuvalu |
| `tw` | twi |
| `twq` | tasawaq |
| `ty` | tahiti |
| `tyv` | tuva |
| `tzm` | keskiatlaksentamazight |
| `udm` | udmurtti |
| `ug` | uiguuri |
| `uga` | ugarit |
| `uk` | ukraina |
| `umb` | mbundu |
| `und` | tuntematon kieli |
| `ur` | urdu |
| `uz` | uzbekki |
| `vai` | vai |
| `ve` | venda |
| `vec` | venetsia |
| `vep` | vepsä |
| `vi` | vietnam |
| `vls` | länsiflaami |
| `vmf` | maininfrankki |
| `vo` | volapük |
| `vot` | vatja |
| `vro` | võro |
| `vun` | vunjo |
| `wa` | valloni |
| `wae` | walser |
| `wal` | wolaitta |
| `war` | waray |
| `was` | washo |
| `wbp` | warlpiri |
| `wo` | wolof |
| `wuu` | wu-kiina |
| `xal` | kalmukki |
| `xh` | xhosa |
| `xmf` | mingreli |
| `xog` | soga |
| `yao` | jao |
| `yap` | japi |
| `yav` | yangben |
| `ybb` | yemba |
| `yi` | jiddiš |
| `yo` | joruba |
| `yrl` | ñeengatú |
| `yue` | kantoninkiina |
| `za` | zhuang |
| `zap` | zapoteekki |
| `zbl` | blisskieli |
| `zea` | seelanti |
| `zen` | zenaga |
| `zgh` | vakioitu tamazight |
| `zh` | kiina |
| `zh_Hans` | yksinkertaistettu kiina |
| `zh_Hant` | perinteinen kiina |
| `zu` | zulu |
| `zun` | zuni |
| `zxx` | ei kielellistä sisältöä |
| `zza` | zaza |

### Script names


(Written in middle of sentence, selection list etc.)

| ISO code | Name |
| -------- | ---- |
| `Adlm` | fulanin adlam-aakkosto |
| `Afak` | afaka |
| `Aghb` | kaukasianalbanialainen |
| `Ahom` | ahom |
| `Arab` | arabialainen |
| `Arab` | persialaisarabialainen |
| `Armi` | valtakunnanaramealainen |
| `Armn` | armenialainen |
| `Avst` | avestalainen |
| `Bali` | balilainen |
| `Bamu` | bamum |
| `Bass` | bassa |
| `Batk` | batakilainen |
| `Beng` | bengalilainen |
| `Bhks` | sanskritin bhaiksuki-aakkosto |
| `Blis` | bliss-symbolit |
| `Bopo` | bopomofo |
| `Brah` | brahmi |
| `Brai` | braille-pistekirjoitus |
| `Bugi` | bugilainen |
| `Buhd` | buhidilainen |
| `Cakm` | chakmalainen |
| `Cans` | kanadalaisten alkuperäiskansojen yhtenäistetty tavukirjoitus |
| `Cari` | kaarialainen |
| `Cham` | tšamilainen |
| `Cher` | cherokeelainen |
| `Cirt` | cirth |
| `Copt` | koptilainen |
| `Cprt` | muinaiskyproslainen |
| `Cyrl` | kyrillinen |
| `Cyrs` | kyrillinen muinaiskirkkoslaavimuunnelma |
| `Deva` | devanagari |
| `Dsrt` | deseret |
| `Dupl` | Duployén pikakirjoitus |
| `Egyd` | egyptiläinen demoottinen |
| `Egyh` | egyptiläinen hieraattinen |
| `Egyp` | egyptiläiset hieroglyfit |
| `Elba` | elbasanilainen |
| `Ethi` | etiopialainen |
| `Ethi` | ge’ez |
| `Geok` | muinaisgeorgialainen |
| `Geok` | khutsuri |
| `Geor` | georgialainen |
| `Geor` | mkhedruli |
| `Glag` | glagoliittinen |
| `Gonm` | masaram-gondi |
| `Goth` | goottilainen |
| `Gran` | grantha |
| `Grek` | kreikkalainen |
| `Gujr` | gudžaratilainen |
| `Guru` | gurmukhi |
| `Hanb` | kiinan han ja bopomofo |
| `Hang` | hangul |
| `Hani` | kiinalainen han |
| `Hano` | hanunoolainen |
| `Hans` | yksinkertaistettu |
| `Hans` | yksinkertaistettu han |
| `Hant` | perinteinen |
| `Hant` | perinteinen han |
| `Hatr` | hatralainen |
| `Hebr` | heprealainen |
| `Hira` | hiragana |
| `Hluw` | anatolialaiset hieroglyfit |
| `Hmng` | pahawh hmong |
| `Hrkt` | japanin tavumerkistöt |
| `Hung` | muinaisunkarilainen |
| `Inds` | induslainen |
| `Ital` | muinaisitalialainen |
| `Jamo` | korean hangulin jamo-elementit |
| `Java` | jaavalainen |
| `Jpan` | japanilainen |
| `Jurc` | džurtšen |
| `Kali` | kayah li |
| `Kana` | katakana |
| `Khar` | kharosthi |
| `Khmr` | khmeriläinen |
| `Khoj` | khojki |
| `Knda` | kannadalainen |
| `Kore` | korealainen |
| `Kpel` | kpelle |
| `Kthi` | kaithi |
| `Lana` | lanna |
| `Laoo` | laolainen |
| `Latf` | latinalainen fraktuuramuunnelma |
| `Latg` | latinalainen gaelimuunnelma |
| `Latn` | latinalainen |
| `Lepc` | lepchalainen |
| `Limb` | limbulainen |
| `Lina` | lineaari-A |
| `Linb` | lineaari-B |
| `Lisu` | Fraserin aakkoset |
| `Loma` | loma |
| `Lyci` | lyykialainen |
| `Lydi` | lyydialainen |
| `Mahj` | mahajanilainen |
| `Mand` | mandealainen |
| `Mani` | manikealainen |
| `Marc` | tiibetiläinen marchan-kirjoitus |
| `Maya` | maya-hieroglyfit |
| `Mend` | mende |
| `Merc` | meroiittinen kursiivikirjoitus |
| `Mero` | meroiittinen |
| `Mlym` | malajalamilainen |
| `Modi` | modi-aakkoset |
| `Mong` | mongolilainen |
| `Moon` | moon-kohokirjoitus |
| `Mroo` | mro |
| `Mtei` | meitei |
| `Mtei` | meitei mayek |
| `Mult` | multanilainen |
| `Mymr` | burmalainen |
| `Narb` | muinaispohjoisarabialainen |
| `Nbat` | nabatealainen |
| `Newa` | newarin newa-tavukirjoitus |
| `Nkgb` | naxi geba |
| `Nkoo` | n’ko |
| `Nshu` | nüshu |
| `Ogam` | ogam |
| `Olck` | ol chiki |
| `Orkh` | orkhon |
| `Orya` | orijalainen |
| `Osge` | osagen aakkosto |
| `Osma` | osmanjalainen |
| `Palm` | palmyralainen |
| `Pauc` | zotuallai |
| `Perm` | muinaispermiläinen |
| `Phag` | phags-pa |
| `Phli` | piirtokirjoituspahlavilainen |
| `Phlp` | psalttaripahlavilainen |
| `Phlv` | kirjapahlavilainen |
| `Phnx` | foinikialainen |
| `Plrd` | Pollardin foneettinen |
| `Prti` | piirtokirjoitusparthialainen |
| `Rjng` | rejang |
| `Roro` | rongorongo |
| `Runr` | riimukirjoitus |
| `Samr` | samarianaramealainen |
| `Sara` | sarati |
| `Sarb` | muinaiseteläarabialainen |
| `Saur` | saurashtra |
| `Sgnw` | SignWriting |
| `Shaw` | shaw’lainen |
| `Shrd` | šarada |
| `Sidd` | siddham-tavukirjoitus |
| `Sind` | khudabadi |
| `Sinh` | sinhalilainen |
| `Sora` | sorang sompeng |
| `Soyo` | soyombo-kirjaimisto |
| `Sund` | sundalainen |
| `Sylo` | syloti nagri |
| `Syrc` | syyrialainen |
| `Syre` | syyrialainen estrangelo-muunnelma |
| `Syrj` | syyrialainen läntinen muunnelma |
| `Syrn` | syyrialainen itäinen muunnelma |
| `Tagb` | tagbanwalainen |
| `Takr` | takri |
| `Tale` | tailelainen |
| `Talu` | uusi tailuelainen |
| `Taml` | tamililainen |
| `Tang` | tangut |
| `Tavt` | tai viet |
| `Telu` | telugulainen |
| `Teng` | tengwar |
| `Tfng` | tifinagh |
| `Tglg` | tagalogilainen |
| `Thaa` | thaana |
| `Thai` | thailainen |
| `Tibt` | tiibetiläinen |
| `Tirh` | tirhuta |
| `Ugar` | ugaritilainen |
| `Vaii` | vailainen |
| `Visp` | näkyvä puhe |
| `Visp` | Visible Speech |
| `Wara` | varang kshiti |
| `Wole` | woleai |
| `Xpeo` | muinaispersialainen |
| `Xsux` | sumerilais-akkadilainen nuolenpääkirjoitus |
| `Yiii` | yiläinen |
| `Zanb` | zanabazar-neliökirjaimisto |
| `Zinh` | peritty |
| `Zmth` | matemaattinen |
| `Zsye` | emoji-symbolit |
| `Zsym` | symbolit |
| `Zxxx` | kirjoittamaton |
| `Zyyy` | määrittämätön |
| `Zzzz` | tuntematon kirjoitusjärjestelmä |

### Territory names


(Written in middle of sentence, selection list etc.)

| ISO code | Name |
| -------- | ---- |
| `001` | maailma |
| `002` | Afrikka |
| `003` | Pohjois-Amerikka |
| `005` | Etelä-Amerikka |
| `009` | Oseania |
| `011` | Länsi-Afrikka |
| `013` | Väli-Amerikka |
| `014` | Itä-Afrikka |
| `015` | Pohjois-Afrikka |
| `017` | Keski-Afrikka |
| `018` | eteläinen Afrikka |
| `019` | Amerikka |
| `021` | pohjoinen Amerikka |
| `029` | Karibia |
| `030` | Itä-Aasia |
| `034` | Etelä-Aasia |
| `035` | Kaakkois-Aasia |
| `039` | Etelä-Eurooppa |
| `053` | Australaasia |
| `054` | Melanesia |
| `057` | Mikronesia |
| `061` | Polynesia |
| `142` | Aasia |
| `143` | Keski-Aasia |
| `145` | Länsi-Aasia |
| `150` | Eurooppa |
| `151` | Itä-Eurooppa |
| `154` | Pohjois-Eurooppa |
| `155` | Länsi-Eurooppa |
| `202` | Saharan eteläpuolinen Afrikka |
| `419` | Latinalainen Amerikka |
| `AC` | Ascension-saari |
| `AD` | Andorra |
| `AE` | Arabiemiirikunnat |
| `AF` | Afganistan |
| `AG` | Antigua ja Barbuda |
| `AI` | Anguilla |
| `AL` | Albania |
| `AM` | Armenia |
| `AO` | Angola |
| `AQ` | Antarktis |
| `AR` | Argentiina |
| `AS` | Amerikan Samoa |
| `AT` | Itävalta |
| `AU` | Australia |
| `AW` | Aruba |
| `AX` | Ahvenanmaa |
| `AZ` | Azerbaidžan |
| `BA` | Bosnia ja Hertsegovina |
| `BB` | Barbados |
| `BD` | Bangladesh |
| `BE` | Belgia |
| `BF` | Burkina Faso |
| `BG` | Bulgaria |
| `BH` | Bahrain |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | Saint-Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Bolivia |
| `BQ` | Karibian Alankomaat |
| `BR` | Brasilia |
| `BS` | Bahama |
| `BT` | Bhutan |
| `BV` | Bouvet’nsaari |
| `BW` | Botswana |
| `BY` | Valko-Venäjä |
| `BZ` | Belize |
| `CA` | Kanada |
| `CC` | Kookossaaret (Keelingsaaret) |
| `CD` | Kongon demokraattinen tasavalta |
| `CD` | Kongo-Kinshasa |
| `CF` | Keski-Afrikan tasavalta |
| `CG` | Kongon tasavalta |
| `CG` | Kongo-Brazzaville |
| `CH` | Sveitsi |
| `CI` | Norsunluurannikko |
| `CI` | Côte d’Ivoire |
| `CK` | Cookinsaaret |
| `CL` | Chile |
| `CM` | Kamerun |
| `CN` | Kiina |
| `CO` | Kolumbia |
| `CP` | Clippertoninsaari |
| `CR` | Costa Rica |
| `CU` | Kuuba |
| `CV` | Kap Verde |
| `CW` | Curaçao |
| `CX` | Joulusaari |
| `CY` | Kypros |
| `CZ` | Tšekki |
| `CZ` | Tšekin tasavalta |
| `DE` | Saksa |
| `DG` | Diego Garcia |
| `DJ` | Djibouti |
| `DK` | Tanska |
| `DM` | Dominica |
| `DO` | Dominikaaninen tasavalta |
| `DZ` | Algeria |
| `EA` | Ceuta ja Melilla |
| `EC` | Ecuador |
| `EE` | Viro |
| `EG` | Egypti |
| `EH` | Länsi-Sahara |
| `ER` | Eritrea |
| `ES` | Espanja |
| `ET` | Etiopia |
| `EU` | Euroopan unioni |
| `EZ` | euroalue |
| `FI` | Suomi |
| `FJ` | Fidži |
| `FK` | Falklandinsaaret |
| `FK` | Falklandinsaaret (Malvinassaaret) |
| `FM` | Mikronesian liittovaltio |
| `FO` | Färsaaret |
| `FR` | Ranska |
| `GA` | Gabon |
| `GB` | Iso-Britannia |
| `GB` | Britannia |
| `GD` | Grenada |
| `GE` | Georgia |
| `GF` | Ranskan Guayana |
| `GG` | Guernsey |
| `GH` | Ghana |
| `GI` | Gibraltar |
| `GL` | Grönlanti |
| `GM` | Gambia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Päiväntasaajan Guinea |
| `GR` | Kreikka |
| `GS` | Etelä-Georgia ja Eteläiset Sandwichsaaret |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Guinea-Bissau |
| `GY` | Guyana |
| `HK` | Hongkong – Kiinan e.h.a. |
| `HK` | Hongkong |
| `HM` | Heard ja McDonaldinsaaret |
| `HN` | Honduras |
| `HR` | Kroatia |
| `HT` | Haiti |
| `HU` | Unkari |
| `IC` | Kanariansaaret |
| `ID` | Indonesia |
| `IE` | Irlanti |
| `IL` | Israel |
| `IM` | Mansaari |
| `IN` | Intia |
| `IO` | Brittiläinen Intian valtameren alue |
| `IQ` | Irak |
| `IR` | Iran |
| `IS` | Islanti |
| `IT` | Italia |
| `JE` | Jersey |
| `JM` | Jamaika |
| `JO` | Jordania |
| `JP` | Japani |
| `KE` | Kenia |
| `KG` | Kirgisia |
| `KH` | Kambodža |
| `KI` | Kiribati |
| `KM` | Komorit |
| `KN` | Saint Kitts ja Nevis |
| `KP` | Pohjois-Korea |
| `KR` | Etelä-Korea |
| `KW` | Kuwait |
| `KY` | Caymansaaret |
| `KZ` | Kazakstan |
| `LA` | Laos |
| `LB` | Libanon |
| `LC` | Saint Lucia |
| `LI` | Liechtenstein |
| `LK` | Sri Lanka |
| `LR` | Liberia |
| `LS` | Lesotho |
| `LT` | Liettua |
| `LU` | Luxemburg |
| `LV` | Latvia |
| `LY` | Libya |
| `MA` | Marokko |
| `MC` | Monaco |
| `MD` | Moldova |
| `ME` | Montenegro |
| `MF` | Saint-Martin |
| `MG` | Madagaskar |
| `MH` | Marshallinsaaret |
| `MK` | Makedonia |
| `MK` | EJT Makedonia |
| `ML` | Mali |
| `MM` | Myanmar (Burma) |
| `MN` | Mongolia |
| `MO` | Macao – Kiinan e.h.a. |
| `MO` | Macao |
| `MP` | Pohjois-Mariaanit |
| `MQ` | Martinique |
| `MR` | Mauritania |
| `MS` | Montserrat |
| `MT` | Malta |
| `MU` | Mauritius |
| `MV` | Malediivit |
| `MW` | Malawi |
| `MX` | Meksiko |
| `MY` | Malesia |
| `MZ` | Mosambik |
| `NA` | Namibia |
| `NC` | Uusi-Kaledonia |
| `NE` | Niger |
| `NF` | Norfolkinsaari |
| `NG` | Nigeria |
| `NI` | Nicaragua |
| `NL` | Alankomaat |
| `NO` | Norja |
| `NP` | Nepal |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | Uusi-Seelanti |
| `OM` | Oman |
| `PA` | Panama |
| `PE` | Peru |
| `PF` | Ranskan Polynesia |
| `PG` | Papua-Uusi-Guinea |
| `PH` | Filippiinit |
| `PK` | Pakistan |
| `PL` | Puola |
| `PM` | Saint-Pierre ja Miquelon |
| `PN` | Pitcairn |
| `PR` | Puerto Rico |
| `PS` | Palestiinalaisalueet |
| `PS` | Palestiina |
| `PT` | Portugali |
| `PW` | Palau |
| `PY` | Paraguay |
| `QA` | Qatar |
| `QO` | ulkomeri |
| `RE` | Réunion |
| `RO` | Romania |
| `RS` | Serbia |
| `RU` | Venäjä |
| `RW` | Ruanda |
| `SA` | Saudi-Arabia |
| `SB` | Salomonsaaret |
| `SC` | Seychellit |
| `SD` | Sudan |
| `SE` | Ruotsi |
| `SG` | Singapore |
| `SH` | Saint Helena |
| `SI` | Slovenia |
| `SJ` | Huippuvuoret ja Jan Mayen |
| `SK` | Slovakia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Senegal |
| `SO` | Somalia |
| `SR` | Suriname |
| `SS` | Etelä-Sudan |
| `ST` | São Tomé ja Príncipe |
| `SV` | El Salvador |
| `SX` | Sint Maarten |
| `SY` | Syyria |
| `SZ` | Swazimaa |
| `TA` | Tristan da Cunha |
| `TC` | Turks- ja Caicossaaret |
| `TD` | Tšad |
| `TF` | Ranskan eteläiset alueet |
| `TG` | Togo |
| `TH` | Thaimaa |
| `TJ` | Tadžikistan |
| `TK` | Tokelau |
| `TL` | Itä-Timor |
| `TL` | Timor-Leste |
| `TM` | Turkmenistan |
| `TN` | Tunisia |
| `TO` | Tonga |
| `TR` | Turkki |
| `TT` | Trinidad ja Tobago |
| `TV` | Tuvalu |
| `TW` | Taiwan |
| `TZ` | Tansania |
| `UA` | Ukraina |
| `UG` | Uganda |
| `UM` | Yhdysvaltain erillissaaret |
| `UN` | Yhdistyneet kansakunnat |
| `UN` | YK |
| `US` | Yhdysvallat |
| `US` | USA |
| `UY` | Uruguay |
| `UZ` | Uzbekistan |
| `VA` | Vatikaani |
| `VC` | Saint Vincent ja Grenadiinit |
| `VE` | Venezuela |
| `VG` | Brittiläiset Neitsytsaaret |
| `VI` | Yhdysvaltain Neitsytsaaret |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis ja Futuna |
| `WS` | Samoa |
| `XK` | Kosovo |
| `YE` | Jemen |
| `YT` | Mayotte |
| `ZA` | Etelä-Afrikka |
| `ZM` | Sambia |
| `ZW` | Zimbabwe |
| `ZZ` | tuntematon alue |

### Locale variant names


(Written in middle of sentence, selection list etc.)

| ISO code | Name |
| -------- | ---- |
| `1901` | saksan perinteinen oikeinkirjoitus |
| `1994` | sloveenin resian murteen yhdenmukaistettu oikeinkirjoitus |
| `1996` | saksan uusi oikeinkirjoitus |
| `1606NICT` | myöhäiskeskiranska |
| `1694ACAD` | varhaisnykyranska |
| `1959ACAD` | valkovenäjän virallinen oikeinkirjoitus |
| `ABL1943` | portugalin oikeinkirjoitus 1943 |
| `ALALC97` | amerikkalainen kirjastolatinaistus 1997 |
| `ALUKU` | alukun kreolimurre |
| `AO1990` | portugalin oikeinkirjoitussopimus 1990 |
| `AREVELA` | itäarmenialainen |
| `AREVMDA` | länsiarmenialainen |
| `BAKU1926` | yhtenäistetty turkkilainen latinalainen aakkosto |
| `BALANKA` | aniin balankalaismurre |
| `BARLA` | kapverdenkreolin barlaventolainen murreryhmä |
| `BASICENG` | Ogdenin perusenglanti |
| `BAUDDHA` | sanskriitin buddhalainen sekamuoto |
| `BISCAYAN` | baskin biskajalaismurre |
| `BISKE` | sloveenin resian San Giorgion/Bilan alamurre |
| `BOHORIC` | sloveenin Bohorič-aakkosto |
| `BOONT` | englannin boontling-murre |
| `COLB1945` | portugalin oikeinkirjoitus 1945 |
| `CORNU` | englannin cornu-murre |
| `DAJNKO` | sloveenin Dajnko-aakkosto |
| `EKAVSK` | serbian ekavialainen ääntämys |
| `EMODENG` | varhaisnykyenglanti |
| `FONIPA` | kansainvälinen foneettinen aakkosto IPA |
| `FONNAPA` | pohjoisamerikkalainen foneettinen aakkosto NAPA |
| `FONUPA` | uralilainen foneettinen aakkosto UPA |
| `FONUPA` | suomalais-ugrilainen tarkekirjoitus |
| `FONXSAMP` | foneettinen X-SAMPA-merkistö |
| `HEPBURN` | japanin Hepburn-latinaistus |
| `HOGNORSK` | norjan högnorsk |
| `HSISTEMO` | esperanton h-kirjoitus |
| `IJEKAVSK` | serbian ijekavialainen ääntämys |
| `ITIHASA` | sanskriitin eeppinen muoto |
| `JAUER` | retoromaanin jauer-murre |
| `JYUTPING` | kantoninkiinan jyutping-latinaistus |
| `KKCOR` | kornin yleiskirjoitus |
| `KOCIEWIE` | puolan kociewielainen murre |
| `KSCOR` | kornin Kernowek-ortografia |
| `LAUKIKA` | klassinen sanskriitti |
| `LIPAW` | sloveenin resian Lipovazin/Lipovecin alamurre |
| `LUNA1918` | venäjän ortografia 1918 |
| `METELKO` | sloveenin Metelko-aakkosto |
| `MONOTON` | monotoninen kreikka |
| `NDYUKA` | ndyukan kreolimurre |
| `NEDIS` | sloveenin natisonen murre |
| `NEWFOUND` | englannin newfoundlandilaismurre |
| `NJIVA` | sloveenin resian Gnivan/Njivan alamurre |
| `NULIK` | nykyvolapük |
| `OSOJS` | sloveenin resian Oseaccon/Osojanen alamurre |
| `OXENDICT` | englannin Oxfordin sanakirjan oikeinkirjoitus |
| `PAHAWH2` | pahawh-hmongin tavukirjoituksen toinen vaihe |
| `PAHAWH3` | pahawh-hmongin tavukirjoituksen kolmas vaihe |
| `PAHAWH4` | pahawh-hmongin tavukirjoituksen viimeinen vaihe |
| `PAMAKA` | pamakan kreolimurre |
| `PETR1708` | venäjän Pietarin siviiliaakkosto 1708 |
| `PINYIN` | kiinan pinyin-latinaistus |
| `POLYTON` | polytoninen kreikka |
| `POSIX` | tietokonemäärittely POSIX |
| `PUTER` | retoromaanin puter-muoto |
| `REVISED` | uudistettu oikeinkirjoitus |
| `RIGIK` | klassinen volapük |
| `ROZAJ` | sloveenin resian murre |
| `RUMGR` | retoromaanin rumantsch grischun -muoto |
| `SAAHO` | afarin saho-murre |
| `SCOTLAND` | skotlanninenglanti |
| `SCOUSE` | englannin scouse-murre |
| `SIMPLE` | yksinkertaistettu kielimuoto |
| `SOLBA` | sloveenin resian Stolvizzan/Solbican alamurre |
| `SOTAV` | kapverdenkreolin sotaventolainen murreryhmä |
| `SPANGLIS` | spanglish |
| `SURMIRAN` | retoromaanin surmiran-muoto |
| `SURSILV` | retoromaanin sursilvan-muoto |
| `SUTSILV` | retoromaanin sutsilvan-muoto |
| `TARASK` | valkovenäjän taraškevitsa-oikeinkirjoitus |
| `UCCOR` | kornin yhtenäiskirjoitus |
| `UCRCOR` | kornin uusittu yhtenäiskirjoitus |
| `ULSTER` | skotin ulster-murre |
| `UNIFON` | englannin foneeminen unifon-aakkosto |
| `VAIDIKA` | sanskriitin veda-murre |
| `VALENCIA` | katalaanin valencian murre |
| `VALLADER` | reoromaanin vallader-muoto |
| `WADEGILE` | kiinan Wade-Giles-latinaistus |
| `XSISTEMO` | esperanton x-kirjoitus |

#### Keys (system names)

| key | Name |
| -------- | ---- |
| `calendar` | kalenteri |
| `cf` | valuuttojen esitysmuoto |
| `colAlternate` | symbolien lajittelu |
| `colBackwards` | painomerkkien lajittelu |
| `colCaseFirst` | isojen ja pienten kirjainten järjestys |
| `colCaseLevel` | aakkoslajien lajittelu |
| `collation` | lajittelujärjestys |
| `colNormalization` | lajittelun normalisointi |
| `colNumeric` | numeroiden lajittelu |
| `colStrength` | lajittelun taso |
| `currency` | valuutta |
| `hc` | tuntijärjestelmä |
| `lb` | rivinvaihtotyyli |
| `ms` | mittajärjestelmä |
| `numbers` | numerot |
| `timezone` | aikavyöhyke |
| `va` | maavalinnan muunnelma |
| `x` | yksityiskäyttö |

### Types (of systems)

| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | buddhalainen kalenteri |
| `chinesecalendar` | kiinalainen kalenteri |
| `copticcalendar` | koptilainen kalenteri |
| `dangicalendar` | dangilainen kalenteri |
| `ethiopiccalendar` | etiopialainen kalenteri |
| `ethiopic-amete-alemcalendar` | etiopialainen amete alem -kalenteri |
| `gregoriancalendar` | gregoriaaninen kalenteri |
| `hebrewcalendar` | juutalainen kalenteri |
| `indiancalendar` | intialainen kalenteri |
| `islamiccalendar` | islamilainen kalenteri |
| `islamic-civilcalendar` | islamilainen siviilikalenteri, perjantai-epookki |
| `islamic-rgsacalendar` | islamilainen saudiarabialainen kalenteri |
| `islamic-tblacalendar` | islamilainen matemaattinen kalenteri, torstai-epookki |
| `islamic-umalquracalendar` | islamilainen Umm al-Qura -kalenteri |
| `iso8601calendar` | ISO 8601 -kalenteri |
| `japanesecalendar` | japanilainen kalenteri |
| `persiancalendar` | persialainen kalenteri |
| `roccalendar` | Kiinan tasavallan kalenteri |
| `accountcf` | valuuttojen laskentatoimen esitysmuoto |
| `standardcf` | valuuttojen vakioesitysmuoto |
| `non-ignorablecolAlternate` | symbolit huomioiva lajittelu |
| `shiftedcolAlternate` | symbolit ohittava lajittelu |
| `nocolBackwards` | painomerkkien normaali lajittelu |
| `yescolBackwards` | painomerkkien käänteinen lajittelu |
| `lowercolCaseFirst` | pienet kirjaimet edeltävät isoja |
| `nocolCaseFirst` | isojen ja pienten kirjainten normaalijärjestys |
| `uppercolCaseFirst` | isot kirjaimet edeltävät pieniä |
| `nocolCaseLevel` | isojen ja pienten kirjainten lajittelu yhdessä |
| `yescolCaseLevel` | isojen ja pienten kirjainten lajittelu erikseen |
| `big5hancollation` | perinteinen kiinalainen järjestys Big5 |
| `compatcollation` | aiempi lajittelujärjestys yhteensopivuutta varten |
| `dictionarycollation` | sanakirjajärjestys |
| `ducetcollation` | Unicoden oletusjärjestys |
| `emojicollation` | emojien lajittelujärjestys |
| `eorcollation` | yleiseurooppalainen lajittelujärjestys |
| `gb2312hancollation` | yksinkertaistettu kiinalainen järjestys GB2312 |
| `phonebookcollation` | puhelinluettelojärjestys |
| `phoneticcollation` | äänteellinen järjestys |
| `pinyincollation` | pinyin-järjestys |
| `reformedcollation` | uudistettu järjestys |
| `searchcollation` | yleishakujärjestys |
| `searchjlcollation` | haku hangul-alkukonsonantin mukaan |
| `standardcollation` | normaalijärjestys |
| `strokecollation` | piirtojärjestys |
| `traditionalcollation` | perinteinen järjestys |
| `unihancollation` | radikaali- ja piirtojärjestys |
| `zhuyincollation` | zhuyin-järjestys |
| `nocolNormalization` | lajittelu ilman normalisoinrtia |
| `yescolNormalization` | lajittelu Unicode-normalisoituna |
| `nocolNumeric` | numero-numerolta lajittelu |
| `yescolNumeric` | numeroden lajittelu lukuina |
| `identicalcolStrength` | kaikkien merkkien lajittelu |
| `primarycolStrength` | vain peruskirjainten lajittelu |
| `quaternarycolStrength` | painomerkit ja aakkoslajit tai merkkileveydet ja kana-merkit huomioiva lajittelu |
| `secondarycolStrength` | painomerkit huomioiva lajittelu |
| `tertiarycolStrength` | painomerkit ja aakkoslajit tai merkkileveydet huomioiva lajittelu |
| `fwidthd0` | ideogrammin levyinen |
| `hwidthd0` | ideogrammin puolikkaan levyinen |
| `npinyind0` | numeerinen muunnos |
| `h11hc` | 12 tunnin järjestelmä (0–11) |
| `h12hc` | 12 tunnin järjestelmä (1–12) |
| `h23hc` | 24 tunnin järjestelmä (0–23) |
| `h24hc` | 24 tunnin järjestelmä (1–24) |
| `looselb` | väljä rivinvaihto |
| `normallb` | normaali rivinvaihto |
| `strictlb` | tarkka rivinvaihto |
| `bgnm0` | BGN-latinaistus |
| `ungegnm0` | UNGEGN-latinaistus |
| `metricms` | metrijärjestelmä |
| `uksystemms` | brittiläinen mittajärjestelmä |
| `ussystemms` | yhdysvaltalainen mittajärjestelmä |
| `ahomnumbers` | ahom-numerot |
| `arabnumbers` | arabialaiset numerot |
| `arabextnumbers` | laajennetut arabialaiset numerot |
| `armnnumbers` | armenialaiset numerot |
| `armnlownumbers` | armenialaiset piennumerot |
| `balinumbers` | balilaiset numerot |
| `bengnumbers` | bengalilaiset numerot |
| `brahnumbers` | brahmilaiset numerot |
| `cakmnumbers` | chakmalaiset numerot |
| `chamnumbers` | cham-numerot |
| `cyrlnumbers` | kyrilliset numerot |
| `devanumbers` | devanagarinumerot |
| `ethinumbers` | etiopialaiset numerot |
| `financenumbers` | talousnumerot |
| `fullwidenumbers` | ideografin levyiset numerot |
| `geornumbers` | georgialaiset numerot |
| `greknumbers` | kreikkalaiset numerot |
| `greklownumbers` | kreikkalaiset piennumerot |
| `gujrnumbers` | gudžaratilaiset numerot |
| `gurunumbers` | gurmukhilaiset numerot |
| `hanidecnumbers` | kiinalaiset desimaalinumerot |
| `hansnumbers` | yksinkertaistetut kiinalaiset numerot |
| `hansfinnumbers` | yksinkertaistetut kiinalaiset talousnumerot |
| `hantnumbers` | perinteiset kiinalaiset numerot |
| `hantfinnumbers` | perinteiset kiinalaiset talousnumerot |
| `hebrnumbers` | heprealaiset numerot |
| `hmngnumbers` | pahawh hmong -numerot |
| `javanumbers` | jaavalaiset numerot |
| `jpannumbers` | japanilaiset numerot |
| `jpanfinnumbers` | japanilaiset talousnumerot |
| `kalinumbers` | kayah li -numerot |
| `khmrnumbers` | khmeriläiset numerot |
| `kndanumbers` | kannadalaiset numerot |
| `lananumbers` | taithamin hora-numerot |
| `lanathamnumbers` | taithamin tham-numerot |
| `laoonumbers` | laolaiset numerot |
| `latnnumbers` | länsimaiset numerot |
| `lepcnumbers` | lepchanumerot |
| `limbnumbers` | limbunumerot |
| `mathboldnumbers` | matemaattiset lihavoidut numerot |
| `mathdblnumbers` | matemaattiset kaksoislyöntinumerot |
| `mathmononumbers` | matemaattiset tasalevyiset numerot |
| `mathsanbnumbers` | matemaattiset pääteviivattomat lihavoidut numerot |
| `mathsansnumbers` | matemaattiset pääteviivattomat numerot |
| `mlymnumbers` | malajalamilaiset numerot |
| `modinumbers` | modi-numerot |
| `mongnumbers` | mongolialaiset numerot |
| `mroonumbers` | mro-numerot |
| `mteinumbers` | meetei mayek -numerot |
| `mymrnumbers` | burmalaiset numerot |
| `mymrshannumbers` | myanmarin shan-numerot |
| `mymrtlngnumbers` | myanmarin tai laing -numerot |
| `nativenumbers` | kielen omat numerot |
| `nkoonumbers` | n’ko-numerot |
| `olcknumbers` | ol chiki -numerot |
| `oryanumbers` | orijalaiset numerot |
| `osmanumbers` | osmanjalaiset numerot |
| `romannumbers` | roomalaiset numerot |
| `romanlownumbers` | roomalaiset piennumerot |
| `saurnumbers` | saurashtra-numerot |
| `shrdnumbers` | šarada-numerot |
| `sindnumbers` | khutabadi-numerot |
| `sinhnumbers` | sinhalan lith-numerot |
| `soranumbers` | sora sompeng -numerot |
| `sundnumbers` | sundalaiset numerot |
| `takrnumbers` | takri-numerot |
| `talunumbers` | uudet tai lue -numerot |
| `tamlnumbers` | perinteiset tamilinumerot |
| `tamldecnumbers` | tamilinumerot |
| `telunumbers` | telugulaiset numerot |
| `thainumbers` | thainumerot |
| `tibtnumbers` | tiibetiläiset numerot |
| `tirhnumbers` | tirhuta-numerot |
| `traditionalnumbers` | perinteiset numerot |
| `vaiinumbers` | vai-numerot |
| `waranumbers` | varang kshiti -numerot |
| `metric` | metrinen |
| `UK` | brittiläinen |
| `US` | amerikkalainen |

### Code patterns

| Label | Formatting |
| ----- | ---------- |
| `language` | kieli: {0} |
| `script` | kirjoitusjärjestelmä: {0} |
| `territory` | alue: {0} |

### Context transforms

| Context | Transformation |
| ------- | -------------- |
| `uiListOrMenu::languages` | `titlecase-firstword` |
| `stand-alone::relative` | `titlecase-firstword` |

### Character processing for computer systems

| Character set | Pattern |
| ------------- | ------- |
| main characters | `[a b c d e f g h i j k l m n o p q r s š t u v w x y z ž å ä ö]` |
| auxiliary characters | `[á à ă â ã ą ā ć č ċ ç ď ð đ é è ê ě ë ė ę ē ğ ǧ ģ ǥ ȟ ħ í î ï İ į ī ı ǩ ķ ĺ ľ ļ ł ń ň ñ ņ ŋ ó ò ô ő õ œ ŕ ř ś ŝ ş ș ß ť ţ ț ŧ ú ù û ů ű ų ū ý ÿ ü ź ż ʒ ǯ þ æ ø]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S T U V W X Y Z Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| final ellipsis | `{0}…` |
| initial ellipsis | `…{0}` |
| medial ellipsis | `{0}…{1}` |
| word-final ellipsis | `{0}…` |
| word-initial ellipsis | `…{0}` |
| word-medial ellipsis | `{0}…{1}` |
| More information | `?` |
| Lenient parse, date, `-` equivalents | `[\--/]` |
| Lenient parse, date, `:` equivalents | `[\:∶]` |
| Lenient parse, general, `.` equivalents | `[.․。︒﹒．｡]` |
| Lenient parse, general, `$` equivalents | `[\$﹩＄$]` |
| Lenient parse, general, `£` equivalents | `[£₤]` |
| Lenient parse, general, `₹` equivalents | `[₨₹{Rp}{Rs}]` |
| Lenient parse, number, `-` equivalents | `[\-‒⁻₋−➖﹣－]` |
| Lenient parse, number, `,` equivalents | `[,،٫、︐︑﹐﹑，､]` |
| Lenient parse, number, `+` equivalents | `[+⁺₊➕﬩﹢＋]` |
| Lenient parse, number, `,` equivalents | `[,٫︐﹐，]` |
| Lenient parse, number, `.` equivalents | `[.․﹒．｡]` |
| Quotation start character | ” |
| Quotation end character | ” |
| Secondary yquotation start character | ’ |
| Secondary quotation end character | ’ |

## Calendar data


#### buddhist calendar

| ID-stuff | values |
| -------- | ------ |
| era | buddhalainen aika |
| era | BE |
| era | BE |
| date format | ... |
| standard, full | `cccc d. MMMM y G` |
| date format | ... |
| standard, long | `d. MMMM y G` |
| date format | ... |
| standard, medium | `d.M.y G` |
| date format | ... |
| standard, short | `d.M.y GGGGG` |
| date format `d` | `d` |
| date format `Ed` | `E d.` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMM` | `M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E d. MMM y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyMMMMccccd` | `cccc d. MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |

#### chinese calendar

| ID-stuff | values |
| -------- | ------ |
| date format | ... |
| standard, full | `cccc d.M.y` |
| date format | ... |
| standard, long | `d.M.y` |
| date format | ... |
| standard, medium | `d.M.y` |
| date format | ... |
| standard, short | `d.M.y` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMMd` | `d.M.` |
| date format `MMMEd` | `E d.M.` |
| date format `ms` | `mm.ss` |
| date format `y` | `y` |
| date format `yyyy` | `y` |
| date format `yyyyMd` | `d.M.y` |
| date format `yyyyMEd` | `E d.M.y` |
| date format `yyyyMMMd` | `d.M.y` |
| date format `yyyyMMMEd` | `E d.M.y` |

#### coptic calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | thoutkuuta |
| month, 2, abbreviated, format | paopikuuta |
| month, 3, abbreviated, format | hathorkuuta |
| month, 4, abbreviated, format | koiakkuuta |
| month, 5, abbreviated, format | tobikuuta |
| month, 6, abbreviated, format | meshirkuuta |
| month, 7, abbreviated, format | paremhatkuuta |
| month, 8, abbreviated, format | paremoudekuuta |
| month, 9, abbreviated, format | pashonskuuta |
| month, 10, abbreviated, format | paonikuuta |
| month, 11, abbreviated, format | epipkuuta |
| month, 12, abbreviated, format | mesorikuuta |
| month, 13, abbreviated, format | pi-kogi-enavotkuuta |
| month, 1, wide, format | thoutkuuta |
| month, 2, wide, format | paopikuuta |
| month, 3, wide, format | hathorkuuta |
| month, 4, wide, format | koiakkuuta |
| month, 5, wide, format | tobikuuta |
| month, 6, wide, format | meshirkuuta |
| month, 7, wide, format | paremhatkuuta |
| month, 8, wide, format | paremoudekuuta |
| month, 9, wide, format | pashonskuuta |
| month, 10, wide, format | paonikuuta |
| month, 11, wide, format | epipkuuta |
| month, 12, wide, format | mesorikuuta |
| month, 13, wide, format | pi-kogi-enavotkuuta |
| month, 1, abbreviated, stand-alone | thout |
| month, 2, abbreviated, stand-alone | paopi |
| month, 3, abbreviated, stand-alone | hathor |
| month, 4, abbreviated, stand-alone | koiak |
| month, 5, abbreviated, stand-alone | toba |
| month, 6, abbreviated, stand-alone | meshir |
| month, 7, abbreviated, stand-alone | paremhat |
| month, 8, abbreviated, stand-alone | paremoude |
| month, 9, abbreviated, stand-alone | pashons |
| month, 10, abbreviated, stand-alone | paoni |
| month, 11, abbreviated, stand-alone | epip |
| month, 12, abbreviated, stand-alone | mesori |
| month, 13, abbreviated, stand-alone | pi kogi enavot |
| month, 1, wide, stand-alone | thoutkuu |
| month, 2, wide, stand-alone | paopikuu |
| month, 3, wide, stand-alone | hathorkuu |
| month, 4, wide, stand-alone | koiakkuu |
| month, 5, wide, stand-alone | tobikuu |
| month, 6, wide, stand-alone | meshirkuu |
| month, 7, wide, stand-alone | paremhatkuu |
| month, 8, wide, stand-alone | paremoudekuu |
| month, 9, wide, stand-alone | pashonskuu |
| month, 10, wide, stand-alone | paonikuu |
| month, 11, wide, stand-alone | epipkuu |
| month, 12, wide, stand-alone | mesorikuu |
| month, 13, wide, stand-alone | pi-kogi-enavotkuu |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |

#### ethiopic calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | mäskärämkuuta |
| month, 2, abbreviated, format | ṭəqəmtkuuta |
| month, 3, abbreviated, format | ḫədarkuuta |
| month, 4, abbreviated, format | taḫśaśkuuta |
| month, 5, abbreviated, format | ṭərrkuuta |
| month, 6, abbreviated, format | yäkatitkuuta |
| month, 7, abbreviated, format | mägabitkuuta |
| month, 8, abbreviated, format | miyazyakuuta |
| month, 9, abbreviated, format | gənbotkuuta |
| month, 10, abbreviated, format | sänekuuta |
| month, 11, abbreviated, format | ḥamlekuuta |
| month, 12, abbreviated, format | nähasekuuta |
| month, 13, abbreviated, format | ṗagumenkuuta |
| month, 1, wide, format | mäskärämkuuta |
| month, 2, wide, format | ṭəqəmtkuuta |
| month, 3, wide, format | ḫədarkuuta |
| month, 4, wide, format | taḫśaśkuuta |
| month, 5, wide, format | ṭərrkuuta |
| month, 6, wide, format | yäkatitkuuta |
| month, 7, wide, format | mägabitkuuta |
| month, 8, wide, format | miyazyakuuta |
| month, 9, wide, format | gənbotkuuta |
| month, 10, wide, format | sänekuuta |
| month, 11, wide, format | ḥamlekuuta |
| month, 12, wide, format | nähasekuuta |
| month, 13, wide, format | ṗagumenkuuta |
| month, 1, abbreviated, stand-alone | mäskärämkuu |
| month, 2, abbreviated, stand-alone | ṭəqəmtkuu |
| month, 3, abbreviated, stand-alone | ḫədarkuu |
| month, 4, abbreviated, stand-alone | taḫśaśkuu |
| month, 5, abbreviated, stand-alone | ṭərrkuu |
| month, 6, abbreviated, stand-alone | yäkatitkuu |
| month, 7, abbreviated, stand-alone | mägabitkuu |
| month, 8, abbreviated, stand-alone | miyazyakuu |
| month, 9, abbreviated, stand-alone | gənbotkuu |
| month, 10, abbreviated, stand-alone | sänekuu |
| month, 11, abbreviated, stand-alone | ḥamlekuu |
| month, 12, abbreviated, stand-alone | nähasekuu |
| month, 13, abbreviated, stand-alone | ṗagumenkuu |
| month, 1, wide, stand-alone | mäskärämkuu |
| month, 2, wide, stand-alone | ṭəqəmtkuu |
| month, 3, wide, stand-alone | ḫədarkuu |
| month, 4, wide, stand-alone | taḫśaśkuu |
| month, 5, wide, stand-alone | ṭərrkuu |
| month, 6, wide, stand-alone | yäkatitkuu |
| month, 7, wide, stand-alone | mägabitkuu |
| month, 8, wide, stand-alone | miyazyakuu |
| month, 9, wide, stand-alone | gənbotkuu |
| month, 10, wide, stand-alone | sänekuu |
| month, 11, wide, stand-alone | ḥamlekuu |
| month, 12, wide, stand-alone | nähasekuu |
| month, 13, wide, stand-alone | ṗagumenkuu |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | ... |
| standard, full | `cccc d. MMMM y G` |
| date format | ... |
| standard, long | `d. MMMM y G` |
| date format | ... |
| standard, medium | `d.M.y G` |
| date format | ... |
| standard, short | `d.M.y GGGGG` |
| datetime format | ... |
| standard, full | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, long | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, medium | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, short | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h.mm B` |
| date format `Bhms` | `h.mm.ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h.mm. B` |
| date format `EBhms` | `E h.mm.ss B` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E HH.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E HH.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMM` | `M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E d. MMM y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyMMMMccccd` | `cccc d. MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d.–d.` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h.mm a – h.mm ah.mm–h.mm ah.mm–h.mm a` |
| interval format `Hm` | `H.mm–H.mmH.mm–H.mm` |
| interval format `hmv` | `h.mm a – h.mm a vh.mm–h.mm a vh.mm–h.mm a v` |
| interval format `Hmv` | `H.mm–H.mm vH.mm–H.mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `d.–d. MMMMd. MMMM – d. MMMM` |
| interval format `MMMEd` | `E d. – E d. MMMME d. MMMM – E d. MMMM` |
| interval format `MMMM` | `LLL–LLLL` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `d.–d. MMMM y Gd. MMMM – d. MMMM y Gd. MMMM y – d. MMMM y G` |
| interval format `yMMMEd` | `E d. – E d. MMMM y GE d. MMMM – E d. MMMM y GE d. MMMM y – E d. MMMM y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | tammik. |
| month, 2, abbreviated, format | helmik. |
| month, 3, abbreviated, format | maalisk. |
| month, 4, abbreviated, format | huhtik. |
| month, 5, abbreviated, format | toukok. |
| month, 6, abbreviated, format | kesäk. |
| month, 7, abbreviated, format | heinäk. |
| month, 8, abbreviated, format | elok. |
| month, 9, abbreviated, format | syysk. |
| month, 10, abbreviated, format | lokak. |
| month, 11, abbreviated, format | marrask. |
| month, 12, abbreviated, format | jouluk. |
| month, 1, narrow, format | T |
| month, 2, narrow, format | H |
| month, 3, narrow, format | M |
| month, 4, narrow, format | H |
| month, 5, narrow, format | T |
| month, 6, narrow, format | K |
| month, 7, narrow, format | H |
| month, 8, narrow, format | E |
| month, 9, narrow, format | S |
| month, 10, narrow, format | L |
| month, 11, narrow, format | M |
| month, 12, narrow, format | J |
| month, 1, wide, format | tammikuuta |
| month, 2, wide, format | helmikuuta |
| month, 3, wide, format | maaliskuuta |
| month, 4, wide, format | huhtikuuta |
| month, 5, wide, format | toukokuuta |
| month, 6, wide, format | kesäkuuta |
| month, 7, wide, format | heinäkuuta |
| month, 8, wide, format | elokuuta |
| month, 9, wide, format | syyskuuta |
| month, 10, wide, format | lokakuuta |
| month, 11, wide, format | marraskuuta |
| month, 12, wide, format | joulukuuta |
| month, 1, abbreviated, stand-alone | tammi |
| month, 2, abbreviated, stand-alone | helmi |
| month, 3, abbreviated, stand-alone | maalis |
| month, 4, abbreviated, stand-alone | huhti |
| month, 5, abbreviated, stand-alone | touko |
| month, 6, abbreviated, stand-alone | kesä |
| month, 7, abbreviated, stand-alone | heinä |
| month, 8, abbreviated, stand-alone | elo |
| month, 9, abbreviated, stand-alone | syys |
| month, 10, abbreviated, stand-alone | loka |
| month, 11, abbreviated, stand-alone | marras |
| month, 12, abbreviated, stand-alone | joulu |
| month, 1, narrow, stand-alone | T |
| month, 2, narrow, stand-alone | H |
| month, 3, narrow, stand-alone | M |
| month, 4, narrow, stand-alone | H |
| month, 5, narrow, stand-alone | T |
| month, 6, narrow, stand-alone | K |
| month, 7, narrow, stand-alone | H |
| month, 8, narrow, stand-alone | E |
| month, 9, narrow, stand-alone | S |
| month, 10, narrow, stand-alone | L |
| month, 11, narrow, stand-alone | M |
| month, 12, narrow, stand-alone | J |
| month, 1, wide, stand-alone | tammikuu |
| month, 2, wide, stand-alone | helmikuu |
| month, 3, wide, stand-alone | maaliskuu |
| month, 4, wide, stand-alone | huhtikuu |
| month, 5, wide, stand-alone | toukokuu |
| month, 6, wide, stand-alone | kesäkuu |
| month, 7, wide, stand-alone | heinäkuu |
| month, 8, wide, stand-alone | elokuu |
| month, 9, wide, stand-alone | syyskuu |
| month, 10, wide, stand-alone | lokakuu |
| month, 11, wide, stand-alone | marraskuu |
| month, 12, wide, stand-alone | joulukuu |
| (week)day, sun, abbreviated, format | su |
| (week)day, mon, abbreviated, format | ma |
| (week)day, tue, abbreviated, format | ti |
| (week)day, wed, abbreviated, format | ke |
| (week)day, thu, abbreviated, format | to |
| (week)day, fri, abbreviated, format | pe |
| (week)day, sat, abbreviated, format | la |
| (week)day, sun, narrow, format | S |
| (week)day, mon, narrow, format | M |
| (week)day, tue, narrow, format | T |
| (week)day, wed, narrow, format | K |
| (week)day, thu, narrow, format | T |
| (week)day, fri, narrow, format | P |
| (week)day, sat, narrow, format | L |
| (week)day, sun, short, format | su |
| (week)day, mon, short, format | ma |
| (week)day, tue, short, format | ti |
| (week)day, wed, short, format | ke |
| (week)day, thu, short, format | to |
| (week)day, fri, short, format | pe |
| (week)day, sat, short, format | la |
| (week)day, sun, wide, format | sunnuntaina |
| (week)day, mon, wide, format | maanantaina |
| (week)day, tue, wide, format | tiistaina |
| (week)day, wed, wide, format | keskiviikkona |
| (week)day, thu, wide, format | torstaina |
| (week)day, fri, wide, format | perjantaina |
| (week)day, sat, wide, format | lauantaina |
| (week)day, sun, abbreviated, stand-alone | su |
| (week)day, mon, abbreviated, stand-alone | ma |
| (week)day, tue, abbreviated, stand-alone | ti |
| (week)day, wed, abbreviated, stand-alone | ke |
| (week)day, thu, abbreviated, stand-alone | to |
| (week)day, fri, abbreviated, stand-alone | pe |
| (week)day, sat, abbreviated, stand-alone | la |
| (week)day, sun, narrow, stand-alone | S |
| (week)day, mon, narrow, stand-alone | M |
| (week)day, tue, narrow, stand-alone | T |
| (week)day, wed, narrow, stand-alone | K |
| (week)day, thu, narrow, stand-alone | T |
| (week)day, fri, narrow, stand-alone | P |
| (week)day, sat, narrow, stand-alone | L |
| (week)day, sun, short, stand-alone | su |
| (week)day, mon, short, stand-alone | ma |
| (week)day, tue, short, stand-alone | ti |
| (week)day, wed, short, stand-alone | ke |
| (week)day, thu, short, stand-alone | to |
| (week)day, fri, short, stand-alone | pe |
| (week)day, sat, short, stand-alone | la |
| (week)day, sun, wide, stand-alone | sunnuntai |
| (week)day, mon, wide, stand-alone | maanantai |
| (week)day, tue, wide, stand-alone | tiistai |
| (week)day, wed, wide, stand-alone | keskiviikko |
| (week)day, thu, wide, stand-alone | torstai |
| (week)day, fri, wide, stand-alone | perjantai |
| (week)day, sat, wide, stand-alone | lauantai |
| quarter, 1, abbreviated, format | 1. nelj. |
| quarter, 2, abbreviated, format | 2. nelj. |
| quarter, 3, abbreviated, format | 3. nelj. |
| quarter, 4, abbreviated, format | 4. nelj. |
| quarter, 1, narrow, format | 1 |
| quarter, 2, narrow, format | 2 |
| quarter, 3, narrow, format | 3 |
| quarter, 4, narrow, format | 4 |
| quarter, 1, wide, format | 1. neljännes |
| quarter, 2, wide, format | 2. neljännes |
| quarter, 3, wide, format | 3. neljännes |
| quarter, 4, wide, format | 4. neljännes |
| quarter, 1, abbreviated, stand-alone | 1. nelj. |
| quarter, 2, abbreviated, stand-alone | 2. nelj. |
| quarter, 3, abbreviated, stand-alone | 3. nelj. |
| quarter, 4, abbreviated, stand-alone | 4. nelj. |
| quarter, 1, narrow, stand-alone | 1 |
| quarter, 2, narrow, stand-alone | 2 |
| quarter, 3, narrow, stand-alone | 3 |
| quarter, 4, narrow, stand-alone | 4 |
| quarter, 1, wide, stand-alone | 1. neljännes |
| quarter, 2, wide, stand-alone | 2. neljännes |
| quarter, 3, wide, stand-alone | 3. neljännes |
| quarter, 4, wide, stand-alone | 4. neljännes |
| period of day, midnight, abbreviated, format | keskiyöllä |
| period of day, am, abbreviated, format | ap. |
| period of day, noon, abbreviated, format | keskip. |
| period of day, pm, abbreviated, format | ip. |
| period of day, morning1, abbreviated, format | aamulla |
| period of day, morning2, abbreviated, format | aamup. |
| period of day, afternoon1, abbreviated, format | iltap. |
| period of day, evening1, abbreviated, format | illalla |
| period of day, night1, abbreviated, format | yöllä |
| period of day, midnight, narrow, format | ky. |
| period of day, am, narrow, format | ap. |
| period of day, noon, narrow, format | kp. |
| period of day, pm, narrow, format | ip. |
| period of day, morning1, narrow, format | aamulla |
| period of day, morning2, narrow, format | ap. |
| period of day, afternoon1, narrow, format | ip. |
| period of day, evening1, narrow, format | illalla |
| period of day, night1, narrow, format | yöllä |
| period of day, midnight, wide, format | keskiyöllä |
| period of day, am, wide, format | ap. |
| period of day, noon, wide, format | keskipäivällä |
| period of day, pm, wide, format | ip. |
| period of day, morning1, wide, format | aamulla |
| period of day, morning2, wide, format | aamupäivällä |
| period of day, afternoon1, wide, format | iltapäivällä |
| period of day, evening1, wide, format | illalla |
| period of day, night1, wide, format | yöllä |
| period of day, midnight, abbreviated, stand-alone | keskiyö |
| period of day, am, abbreviated, stand-alone | ap. |
| period of day, noon, abbreviated, stand-alone | keskip. |
| period of day, pm, abbreviated, stand-alone | ip. |
| period of day, morning1, abbreviated, stand-alone | aamu |
| period of day, morning2, abbreviated, stand-alone | aamup. |
| period of day, afternoon1, abbreviated, stand-alone | iltap. |
| period of day, evening1, abbreviated, stand-alone | ilta |
| period of day, night1, abbreviated, stand-alone | yö |
| period of day, midnight, narrow, stand-alone | ky. |
| period of day, am, narrow, stand-alone | ap. |
| period of day, noon, narrow, stand-alone | kp. |
| period of day, pm, narrow, stand-alone | ip. |
| period of day, morning1, narrow, stand-alone | aamu |
| period of day, morning2, narrow, stand-alone | ap. |
| period of day, afternoon1, narrow, stand-alone | ip. |
| period of day, evening1, narrow, stand-alone | ilta |
| period of day, night1, narrow, stand-alone | yö |
| period of day, midnight, wide, stand-alone | keskiyö |
| period of day, am, wide, stand-alone | ap. |
| period of day, noon, wide, stand-alone | keskipäivä |
| period of day, pm, wide, stand-alone | ip. |
| period of day, morning1, wide, stand-alone | aamu |
| period of day, morning2, wide, stand-alone | aamupäivä |
| period of day, afternoon1, wide, stand-alone | iltapäivä |
| period of day, evening1, wide, stand-alone | ilta |
| period of day, night1, wide, stand-alone | yö |
| era | ennen Kristuksen syntymää |
| era | ennen ajanlaskun alkua |
| era | jälkeen Kristuksen syntymän |
| era | jälkeen ajanlaskun alun |
| era | eKr. |
| era | eaa. |
| era | jKr. |
| era | jaa. |
| era | eKr |
| era | eaa |
| era | jKr |
| era | jaa |
| date format | ... |
| standard, full | `cccc d. MMMM y` |
| date format | ... |
| standard, long | `d. MMMM y` |
| date format | ... |
| standard, medium | `d.M.y` |
| date format | ... |
| standard, short | `d.M.y` |
| time format | ... |
| standard, full | `H.mm.ss zzzz` |
| time format | ... |
| standard, long | `H.mm.ss z` |
| time format | ... |
| standard, medium | `H.mm.ss` |
| time format | ... |
| standard, short | `H.mm` |
| datetime format | ... |
| standard, full | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, long | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, medium | `{1} 'klo' {0}` |
| datetime format | ... |
| standard, short | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h.mm B` |
| date format `Bhms` | `h.mm.ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h.mm B` |
| date format `EBhms` | `E h.mm.ss B` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E H.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E H.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E d. MMM y G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h.mm a` |
| date format `Hm` | `H.mm` |
| date format `hms` | `h.mm.ss a` |
| date format `Hms` | `H.mm.ss` |
| date format `hmsv` | `h.mm.ss a v` |
| date format `Hmsv` | `H.mm.ss v` |
| date format `hmv` | `h.mm a v` |
| date format `Hmv` | `H.mm v` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `ccc d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMW` | `LLLL'n' W. 'viikko'` |
| date format `MMMMW` | `LLLL'n' W. 'viikko'` |
| date format `ms` | `m.ss` |
| date format `y` | `y` |
| date format `yM` | `L.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E d.M.y` |
| date format `yMM` | `M.y` |
| date format `yMMM` | `LLL y` |
| date format `yMMMd` | `d. MMM y` |
| date format `yMMMEd` | `E d. MMM y` |
| date format `yMMMM` | `LLLL y` |
| date format `yMMMMccccd` | `cccc d. MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'vuoden' Y 'viikko' w` |
| date format `yw` | `'vuoden' Y 'viikko' w` |
| Timezone | {0} {1} |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d.–d.` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h.mm a – h.mm ah.mm–h.mm ah.mm–h.mm a` |
| interval format `Hm` | `H.mm–H.mmH.mm–H.mm` |
| interval format `hmv` | `h.mm a – h.mm a vh.mm–h.mm a vh.mm–h.mm a v` |
| interval format `Hmv` | `H.mm–H.mm vH.mm–H.mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `d.–d. MMMMd. MMMM – d. MMMM` |
| interval format `MMMEd` | `E d. – E d. MMMME d. MMMM – E d. MMMM` |
| interval format `MMMM` | `LLL–LLLL` |
| interval format `y` | `y–y` |
| interval format `yM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMd` | `d.–d.M.yd.M.–d.M.yd.M.y–d.M.y` |
| interval format `yMEd` | `E d.M.y – E d.M.yE d.M.y – E d.M.yE d.M.y – E d.M.y` |
| interval format `yMMM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMMMd` | `d.–d. MMMM yd. MMMM – d. MMMM yd. MMMM y – d. MMMM y` |
| interval format `yMMMEd` | `E d. – E d. MMMM yE d. MMMM – E d. MMMM yE d. MMMM y – E d. MMMM y` |
| interval format `yMMMM` | `LLL–LLLL yLLLL y – LLLL y` |

#### hebrew calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | tišrí |
| month, 2, abbreviated, format | hešván |
| month, 3, abbreviated, format | kislév |
| month, 4, abbreviated, format | tevét |
| month, 5, abbreviated, format | ševát |
| month, 6, abbreviated, format | adár I |
| month, 7, abbreviated, format | adár |
| month, 7, abbreviated, format | adár II |
| month, 8, abbreviated, format | nisán |
| month, 9, abbreviated, format | ijjár |
| month, 10, abbreviated, format | siván |
| month, 11, abbreviated, format | tammúz |
| month, 12, abbreviated, format | ab |
| month, 13, abbreviated, format | elúl |
| month, 1, wide, format | tišríkuuta |
| month, 2, wide, format | hešvánkuuta |
| month, 3, wide, format | kislévkuuta |
| month, 4, wide, format | tevétkuuta |
| month, 5, wide, format | ševátkuuta |
| month, 6, wide, format | adárkuuta I |
| month, 7, wide, format | adárkuuta |
| month, 7, wide, format | adárkuuta II |
| month, 8, wide, format | nisánkuuta |
| month, 9, wide, format | ijjárkuuta |
| month, 10, wide, format | sivánkuuta |
| month, 11, wide, format | tammúzkuuta |
| month, 12, wide, format | abkuuta |
| month, 13, wide, format | elúlkuuta |
| month, 1, abbreviated, stand-alone | tišrí |
| month, 2, abbreviated, stand-alone | hešván |
| month, 3, abbreviated, stand-alone | kislév |
| month, 4, abbreviated, stand-alone | tevét |
| month, 5, abbreviated, stand-alone | ševát |
| month, 6, abbreviated, stand-alone | adár I |
| month, 7, abbreviated, stand-alone | adár |
| month, 7, abbreviated, stand-alone | adár II |
| month, 8, abbreviated, stand-alone | nisán |
| month, 9, abbreviated, stand-alone | ijjár |
| month, 10, abbreviated, stand-alone | siván |
| month, 11, abbreviated, stand-alone | tammúz |
| month, 12, abbreviated, stand-alone | ab |
| month, 13, abbreviated, stand-alone | elúl |
| month, 1, narrow, stand-alone | T |
| month, 2, narrow, stand-alone | H |
| month, 3, narrow, stand-alone | K |
| month, 4, narrow, stand-alone | T |
| month, 5, narrow, stand-alone | S |
| month, 6, narrow, stand-alone | A |
| month, 7, narrow, stand-alone | A |
| month, 7, narrow, stand-alone | A |
| month, 8, narrow, stand-alone | N |
| month, 9, narrow, stand-alone | I |
| month, 10, narrow, stand-alone | S |
| month, 11, narrow, stand-alone | T |
| month, 12, narrow, stand-alone | A |
| month, 13, narrow, stand-alone | E |
| month, 1, wide, stand-alone | tišríkuu |
| month, 2, wide, stand-alone | hešvánkuu |
| month, 3, wide, stand-alone | kislévkuu |
| month, 4, wide, stand-alone | tevétkuu |
| month, 5, wide, stand-alone | ševátkuu |
| month, 6, wide, stand-alone | adárkuu I |
| month, 7, wide, stand-alone | adárkuu |
| month, 7, wide, stand-alone | adárkuu II |
| month, 8, wide, stand-alone | nisánkuu |
| month, 9, wide, stand-alone | ijjárkuu |
| month, 10, wide, stand-alone | sivánkuu |
| month, 11, wide, stand-alone | tammúzkuu |
| month, 12, wide, stand-alone | abkuu |
| month, 13, wide, stand-alone | elúlkuu |
| era | Anno Mundi |
| era | AM |
| era | AM |

#### indian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | chaitrakuuta |
| month, 2, abbreviated, format | vaisakhakuuta |
| month, 3, abbreviated, format | jyaisthakuuta |
| month, 4, abbreviated, format | asadhakuuta |
| month, 5, abbreviated, format | sravanakuuta |
| month, 6, abbreviated, format | bhadrakuuta |
| month, 7, abbreviated, format | asvinakuuta |
| month, 8, abbreviated, format | kartikakuuta |
| month, 9, abbreviated, format | agrahayanakuuta |
| month, 10, abbreviated, format | pausakuuta |
| month, 11, abbreviated, format | maghakuuta |
| month, 12, abbreviated, format | phalgunakuuta |
| month, 1, wide, format | chaitrakuuta |
| month, 2, wide, format | vaisakhakuuta |
| month, 3, wide, format | jyaisthakuuta |
| month, 4, wide, format | asadhakuuta |
| month, 5, wide, format | sravanakuuta |
| month, 6, wide, format | bhadrakuuta |
| month, 7, wide, format | asvinakuuta |
| month, 8, wide, format | kartikakuuta |
| month, 9, wide, format | agrahayanakuuta |
| month, 10, wide, format | pausakuuta |
| month, 11, wide, format | maghakuuta |
| month, 12, wide, format | phalgunakuuta |
| month, 1, abbreviated, stand-alone | chaitra |
| month, 2, abbreviated, stand-alone | vaisakha |
| month, 3, abbreviated, stand-alone | jyaistha |
| month, 4, abbreviated, stand-alone | asadha |
| month, 5, abbreviated, stand-alone | sravana |
| month, 6, abbreviated, stand-alone | bhadra |
| month, 7, abbreviated, stand-alone | asvina |
| month, 8, abbreviated, stand-alone | kartika |
| month, 9, abbreviated, stand-alone | agrahayana |
| month, 10, abbreviated, stand-alone | pausa |
| month, 11, abbreviated, stand-alone | magha |
| month, 12, abbreviated, stand-alone | phalguna |
| month, 1, wide, stand-alone | chaitrakuu |
| month, 2, wide, stand-alone | vaisakhakuu |
| month, 3, wide, stand-alone | jyaisthakuu |
| month, 4, wide, stand-alone | asadhakuu |
| month, 5, wide, stand-alone | sravanakuu |
| month, 6, wide, stand-alone | bhadrakuu |
| month, 7, wide, stand-alone | asvinakuu |
| month, 8, wide, stand-alone | kartikakuu |
| month, 9, wide, stand-alone | agrahayanakuu |
| month, 10, wide, stand-alone | pausakuu |
| month, 11, wide, stand-alone | maghakuu |
| month, 12, wide, stand-alone | phalgunakuu |
| era | Saka-ajanlaskua |
| era | Saka |
| era | Saka |

#### islamic calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, wide, format | muharram |
| month, 2, wide, format | safar |
| month, 3, wide, format | rabi’ al-awwal |
| month, 4, wide, format | rabi’ al-akhir |
| month, 5, wide, format | džumada-l-ula |
| month, 6, wide, format | džumada-l-akhira |
| month, 7, wide, format | radžab |
| month, 8, wide, format | ša’ban |
| month, 9, wide, format | ramadan |
| month, 10, wide, format | šawwal |
| month, 11, wide, format | dhu-l-qa’da |
| month, 12, wide, format | dhu-l-hiddža |
| month, 1, wide, stand-alone | muharram |
| month, 2, wide, stand-alone | safar |
| month, 3, wide, stand-alone | rabi’ al-awwal |
| month, 4, wide, stand-alone | rabi’ al-akhir |
| month, 5, wide, stand-alone | džumada-l-ula |
| month, 6, wide, stand-alone | džumada-l-akhira |
| month, 7, wide, stand-alone | radžab |
| month, 8, wide, stand-alone | ša’ban |
| month, 9, wide, stand-alone | ramadan |
| month, 10, wide, stand-alone | šawwal |
| month, 11, wide, stand-alone | dhu-l-qa’da |
| month, 12, wide, stand-alone | dhu-l-hiddža |
| era | hidžran jälkeen |
| era | AH |
| era | AH |

#### japanese calendar

| ID-stuff | values |
| -------- | ------ |
| date format | ... |
| standard, full | `cccc d. MMMM y G` |
| date format | ... |
| standard, long | `d. MMMM y G` |
| date format | ... |
| standard, medium | `d.M.y G` |
| date format | ... |
| standard, short | `d.M.y GGGGG` |

#### persian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | farvardinkuuta |
| month, 2, abbreviated, format | ordibeheštkuuta |
| month, 3, abbreviated, format | khordadkuuta |
| month, 4, abbreviated, format | tirkuuta |
| month, 5, abbreviated, format | mordadkuuta |
| month, 6, abbreviated, format | šahrivarkuuta |
| month, 7, abbreviated, format | mehrkuuta |
| month, 8, abbreviated, format | abankuuta |
| month, 9, abbreviated, format | azarkuuta |
| month, 10, abbreviated, format | deykuuta |
| month, 11, abbreviated, format | bahmankuuta |
| month, 12, abbreviated, format | esfandkuuta |
| month, 1, wide, format | farvardinkuuta |
| month, 2, wide, format | ordibeheštkuuta |
| month, 3, wide, format | khordadkuuta |
| month, 4, wide, format | tirkuuta |
| month, 5, wide, format | mordadkuuta |
| month, 6, wide, format | šahrivarkuuta |
| month, 7, wide, format | mehrkuuta |
| month, 8, wide, format | abankuuta |
| month, 9, wide, format | azarkuuta |
| month, 10, wide, format | deykuuta |
| month, 11, wide, format | bahmankuuta |
| month, 12, wide, format | esfandkuuta |
| month, 1, abbreviated, stand-alone | farvardin |
| month, 2, abbreviated, stand-alone | ordibehešt |
| month, 3, abbreviated, stand-alone | khordad |
| month, 4, abbreviated, stand-alone | tir |
| month, 5, abbreviated, stand-alone | mordad |
| month, 6, abbreviated, stand-alone | šahrivar |
| month, 7, abbreviated, stand-alone | mehr |
| month, 8, abbreviated, stand-alone | aban |
| month, 9, abbreviated, stand-alone | azar |
| month, 10, abbreviated, stand-alone | dey |
| month, 11, abbreviated, stand-alone | bahman |
| month, 12, abbreviated, stand-alone | esfand |
| month, 1, wide, stand-alone | farvardinkuu |
| month, 2, wide, stand-alone | ordibeheštkuu |
| month, 3, wide, stand-alone | khordadkuu |
| month, 4, wide, stand-alone | tirkuu |
| month, 5, wide, stand-alone | mordadkuu |
| month, 6, wide, stand-alone | šahrivarkuu |
| month, 7, wide, stand-alone | mehrkuu |
| month, 8, wide, stand-alone | abankuu |
| month, 9, wide, stand-alone | azarkuu |
| month, 10, wide, stand-alone | deykuu |
| month, 11, wide, stand-alone | bahmankuu |
| month, 12, wide, stand-alone | esfandkuu |
| era | Anno Persico |
| era | AP |
| era | AP |

#### roc calendar

| ID-stuff | values |
| -------- | ------ |
| era | ennen Kiinan tasavaltaa |
| era | Minguo |
| era | e. Kiinan tasav. |
| era | Minguo |
| era | e. Kiinan tasav. |
| era | Minguo |

### some more time stuff

| Stuff | Translation |
| ----- | ----------- |
| , era | aikakausi |
| , era-short | aikakausi |
| , era-narrow | aikakausi |
| , year | vuosi |
| -1year | viime vuonna |
| 0year | tänä vuonna |
| 1year | ensi vuonna |
| oneyearfuture | {0} vuoden päästä |
| otheryearfuture | {0} vuoden päästä |
| oneyearpast | {0} vuosi sitten |
| otheryearpast | {0} vuotta sitten |
| , year-short | v |
| -1year-short | viime v |
| 0year-short | tänä v |
| 1year-short | ensi v |
| oneyear-shortfuture | {0} v päästä |
| otheryear-shortfuture | {0} v päästä |
| oneyear-shortpast | {0} v sitten |
| otheryear-shortpast | {0} v sitten |
| , year-narrow | v |
| -1year-narrow | viime v |
| 0year-narrow | tänä v |
| 1year-narrow | ensi v |
| oneyear-narrowfuture | {0} v päästä |
| otheryear-narrowfuture | {0} v päästä |
| oneyear-narrowpast | {0} v sitten |
| otheryear-narrowpast | {0} v sitten |
| , quarter | neljännesvuosi |
| -1quarter | viime neljännesvuonna |
| 0quarter | tänä neljännesvuonna |
| 1quarter | ensi neljännesvuonna |
| onequarterfuture | {0} neljännesvuoden päästä |
| otherquarterfuture | {0} neljännesvuoden päästä |
| onequarterpast | {0} neljännesvuosi sitten |
| otherquarterpast | {0} neljännesvuotta sitten |
| , quarter-short | neljännes |
| -1quarter-short | viime neljänneksenä |
| 0quarter-short | tänä neljänneksenä |
| 1quarter-short | ensi neljänneksenä |
| onequarter-shortfuture | {0} neljänneksen päästä |
| otherquarter-shortfuture | {0} neljänneksen päästä |
| onequarter-shortpast | {0} neljännes sitten |
| otherquarter-shortpast | {0} neljännestä sitten |
| , quarter-narrow | nelj. |
| -1quarter-narrow | viime nelj. |
| 0quarter-narrow | tänä nelj. |
| 1quarter-narrow | ensi nelj. |
| onequarter-narrowfuture | {0} nelj. päästä |
| otherquarter-narrowfuture | {0} nelj. päästä |
| onequarter-narrowpast | {0} nelj. sitten |
| otherquarter-narrowpast | {0} nelj. sitten |
| , month | kuukausi |
| -1month | viime kuussa |
| 0month | tässä kuussa |
| 1month | ensi kuussa |
| onemonthfuture | {0} kuukauden päästä |
| othermonthfuture | {0} kuukauden päästä |
| onemonthpast | {0} kuukausi sitten |
| othermonthpast | {0} kuukautta sitten |
| , month-short | kk |
| -1month-short | viime kk |
| 0month-short | tässä kk |
| 1month-short | ensi kk |
| onemonth-shortfuture | {0} kk päästä |
| othermonth-shortfuture | {0} kk päästä |
| onemonth-shortpast | {0} kk sitten |
| othermonth-shortpast | {0} kk sitten |
| , month-narrow | kk |
| -1month-narrow | viime kk |
| 0month-narrow | tässä kk |
| 1month-narrow | ensi kk |
| onemonth-narrowfuture | {0} kk päästä |
| othermonth-narrowfuture | {0} kk päästä |
| onemonth-narrowpast | {0} kk sitten |
| othermonth-narrowpast | {0} kk sitten |
| , week | viikko |
| -1week | viime viikolla |
| 0week | tällä viikolla |
| 1week | ensi viikolla |
| oneweekfuture | {0} viikon päästä |
| otherweekfuture | {0} viikon päästä |
| oneweekpast | {0} viikko sitten |
| otherweekpast | {0} viikkoa sitten |
| week, relative period | päivän {0} viikolla |
| , week-short | vk |
| -1week-short | viime vk |
| 0week-short | tällä vk |
| 1week-short | ensi vk |
| oneweek-shortfuture | {0} vk päästä |
| otherweek-shortfuture | {0} vk päästä |
| oneweek-shortpast | {0} vk sitten |
| otherweek-shortpast | {0} vk sitten |
| week-short, relative period | päivän {0} viikolla |
| , week-narrow | vk |
| -1week-narrow | viime vk |
| 0week-narrow | tällä vk |
| 1week-narrow | ensi vk |
| oneweek-narrowfuture | {0} vk päästä |
| otherweek-narrowfuture | {0} vk päästä |
| oneweek-narrowpast | {0} vk sitten |
| otherweek-narrowpast | {0} vk sitten |
| week-narrow, relative period | päivän {0} viikolla |
| , weekOfMonth | kuukauden viikko |
| , weekOfMonth-short | kuukauden vk |
| , weekOfMonth-narrow | kuukauden vk |
| , day | päivä |
| -2day | toissa päivänä |
| -1day | eilen |
| 0day | tänään |
| 1day | huomenna |
| 2day | ylihuomenna |
| onedayfuture | {0} päivän päästä |
| otherdayfuture | {0} päivän päästä |
| onedaypast | {0} päivä sitten |
| otherdaypast | {0} päivää sitten |
| , day-short | pv |
| -2day-short | toissap. |
| -1day-short | eilen |
| 0day-short | tänään |
| 1day-short | huom. |
| 2day-short | ylihuom. |
| oneday-shortfuture | {0} pv päästä |
| otherday-shortfuture | {0} pv päästä |
| oneday-shortpast | {0} pv sitten |
| otherday-shortpast | {0} pv sitten |
| , day-narrow | pv |
| -2day-narrow | toissap. |
| -1day-narrow | eilen |
| 0day-narrow | tänään |
| 1day-narrow | huom. |
| 2day-narrow | ylihuom. |
| oneday-narrowfuture | {0} pv päästä |
| otherday-narrowfuture | {0} pv päästä |
| oneday-narrowpast | {0} pv sitten |
| otherday-narrowpast | {0} pv sitten |
| , dayOfYear | vuodenpäivä |
| , dayOfYear-short | vuodenpv |
| , dayOfYear-narrow | vuodenpv |
| , weekday | viikonpäivä |
| , weekday-short | viikonpäivä |
| , weekday-narrow | viikonpäivä |
| , weekdayOfMonth | kuukauden viikonpäivä |
| , weekdayOfMonth-short | kuukauden vk päivä |
| , weekdayOfMonth-narrow | kuukauden vk päivä |
| -1sun | viime sunnuntaina |
| 0sun | tänä sunnuntaina |
| 1sun | ensi sunnuntaina |
| onesunfuture | {0} sunnuntain päästä |
| othersunfuture | {0} sunnuntain päästä |
| onesunpast | {0} sunnuntai sitten |
| othersunpast | {0} sunnuntaita sitten |
| -1sun-short | viime su |
| 0sun-short | tänä su |
| 1sun-short | ensi su |
| onesun-shortfuture | {0} su päästä |
| othersun-shortfuture | {0} su päästä |
| onesun-shortpast | {0} su sitten |
| othersun-shortpast | {0} su sitten |
| -1sun-narrow | viime su |
| 0sun-narrow | tänä su |
| 1sun-narrow | ensi su |
| onesun-narrowfuture | {0} su päästä |
| othersun-narrowfuture | {0} su päästä |
| onesun-narrowpast | {0} su sitten |
| othersun-narrowpast | {0} su sitten |
| -1mon | viime maanantaina |
| 0mon | tänä maanantaina |
| 1mon | ensi maanantaina |
| onemonfuture | {0} maanantain päästä |
| othermonfuture | {0} maanantain päästä |
| onemonpast | {0} maanantai sitten |
| othermonpast | {0} maanantaita sitten |
| -1mon-short | viime ma |
| 0mon-short | tänä ma |
| 1mon-short | ensi ma |
| onemon-shortfuture | {0} ma päästä |
| othermon-shortfuture | {0} ma päästä |
| onemon-shortpast | {0} ma sitten |
| othermon-shortpast | {0} ma sitten |
| -1mon-narrow | viime ma |
| 0mon-narrow | tänä ma |
| 1mon-narrow | ensi ma |
| onemon-narrowfuture | {0} ma päästä |
| othermon-narrowfuture | {0} ma päästä |
| onemon-narrowpast | {0} ma sitten |
| othermon-narrowpast | {0} ma sitten |
| -1tue | viime tiistaina |
| 0tue | tänä tiistaina |
| 1tue | ensi tiistaina |
| onetuefuture | {0} tiistain päästä |
| othertuefuture | {0} tiistain päästä |
| onetuepast | {0} tiistai sitten |
| othertuepast | {0} tiistaita sitten |
| -1tue-short | viime ti |
| 0tue-short | tänä ti |
| 1tue-short | ensi ti |
| onetue-shortfuture | {0} ti päästä |
| othertue-shortfuture | {0} ti päästä |
| onetue-shortpast | {0} ti sitten |
| othertue-shortpast | {0} ti sitten |
| -1tue-narrow | viime ti |
| 0tue-narrow | tänä ti |
| 1tue-narrow | ensi ti |
| onetue-narrowfuture | {0} ti päästä |
| othertue-narrowfuture | {0} ti päästä |
| onetue-narrowpast | {0} ti sitten |
| othertue-narrowpast | {0} ti sitten |
| -1wed | viime keskiviikkona |
| 0wed | tänä keskiviikkona |
| 1wed | ensi keskiviikkona |
| onewedfuture | {0} keskiviikon päästä |
| otherwedfuture | {0} keskiviikon päästä |
| onewedpast | {0} keskiviikko sitten |
| otherwedpast | {0} keskiviikkoa sitten |
| -1wed-short | viime ke |
| 0wed-short | tänä ke |
| 1wed-short | ensi ke |
| onewed-shortfuture | {0} ke päästä |
| otherwed-shortfuture | {0} ke päästä |
| onewed-shortpast | {0} ke sitten |
| otherwed-shortpast | {0} ke sitten |
| -1wed-narrow | viime ke |
| 0wed-narrow | tänä ke |
| 1wed-narrow | ensi ke |
| onewed-narrowfuture | {0} ke päästä |
| otherwed-narrowfuture | {0} ke päästä |
| onewed-narrowpast | {0} ke sitten |
| otherwed-narrowpast | {0} ke sitten |
| -1thu | viime torstaina |
| 0thu | tänä torstaina |
| 1thu | ensi torstaina |
| onethufuture | {0} torstain päästä |
| otherthufuture | {0} torstain päästä |
| onethupast | {0} torstai sitten |
| otherthupast | {0} torstaita sitten |
| -1thu-short | viime to |
| 0thu-short | tänä to |
| 1thu-short | ensi to |
| onethu-shortfuture | {0} to päästä |
| otherthu-shortfuture | {0} to päästä |
| onethu-shortpast | {0} to sitten |
| otherthu-shortpast | {0} to sitten |
| -1thu-narrow | viime to |
| 0thu-narrow | tänä to |
| 1thu-narrow | ensi to |
| onethu-narrowfuture | {0} to päästä |
| otherthu-narrowfuture | {0} to päästä |
| onethu-narrowpast | {0} to sitten |
| otherthu-narrowpast | {0} to sitten |
| -1fri | viime perjantaina |
| 0fri | tänä perjantaina |
| 1fri | ensi perjantaina |
| onefrifuture | {0} perjantain päästä |
| otherfrifuture | {0} perjantain päästä |
| onefripast | {0} perjantai sitten |
| otherfripast | {0} perjantaita sitten |
| -1fri-short | viime pe |
| 0fri-short | tänä pe |
| 1fri-short | ensi pe |
| onefri-shortfuture | {0} pe päästä |
| otherfri-shortfuture | {0} pe päästä |
| onefri-shortpast | {0} pe sitten |
| otherfri-shortpast | {0} pe sitten |
| -1fri-narrow | viime pe |
| 0fri-narrow | tänä pe |
| 1fri-narrow | ensi pe |
| onefri-narrowfuture | {0} pe päästä |
| otherfri-narrowfuture | {0} pe päästä |
| onefri-narrowpast | {0} pe sitten |
| otherfri-narrowpast | {0} pe sitten |
| -1sat | viime lauantaina |
| 0sat | tänä lauantaina |
| 1sat | ensi lauantaina |
| onesatfuture | {0} lauantain päästä |
| othersatfuture | {0} lauantain päästä |
| onesatpast | {0} lauantai sitten |
| othersatpast | {0} lauantaita sitten |
| -1sat-short | viime la |
| 0sat-short | tänä la |
| 1sat-short | ensi la |
| onesat-shortfuture | {0} la päästä |
| othersat-shortfuture | {0} la päästä |
| onesat-shortpast | {0} la sitten |
| othersat-shortpast | {0} la sitten |
| -1sat-narrow | viime la |
| 0sat-narrow | tänä la |
| 1sat-narrow | ensi la |
| onesat-narrowfuture | {0} la päästä |
| othersat-narrowfuture | {0} la päästä |
| onesat-narrowpast | {0} la sitten |
| othersat-narrowpast | {0} la sitten |
| , dayperiod-short | vuorokaudenaika |
| , dayperiod | vuorokaudenaika |
| , dayperiod-narrow | vuorokaudenaika |
| , hour | tunti |
| 0hour | tämän tunnin aikana |
| onehourfuture | {0} tunnin päästä |
| otherhourfuture | {0} tunnin päästä |
| onehourpast | {0} tunti sitten |
| otherhourpast | {0} tuntia sitten |
| , hour-short | t |
| 0hour-short | tunnin sisällä |
| onehour-shortfuture | {0} t päästä |
| otherhour-shortfuture | {0} t päästä |
| onehour-shortpast | {0} t sitten |
| otherhour-shortpast | {0} t sitten |
| , hour-narrow | t |
| 0hour-narrow | tunnin sisällä |
| onehour-narrowfuture | {0} t päästä |
| otherhour-narrowfuture | {0} t päästä |
| onehour-narrowpast | {0} t sitten |
| otherhour-narrowpast | {0} t sitten |
| , minute | minuutti |
| 0minute | tämän minuutin aikana |
| oneminutefuture | {0} minuutin päästä |
| otherminutefuture | {0} minuutin päästä |
| oneminutepast | {0} minuutti sitten |
| otherminutepast | {0} minuuttia sitten |
| , minute-short | min |
| 0minute-short | minuutin sisällä |
| oneminute-shortfuture | {0} min päästä |
| otherminute-shortfuture | {0} min päästä |
| oneminute-shortpast | {0} min sitten |
| otherminute-shortpast | {0} min sitten |
| , minute-narrow | min |
| 0minute-narrow | minuutin sisällä |
| oneminute-narrowfuture | {0} min päästä |
| otherminute-narrowfuture | {0} min päästä |
| oneminute-narrowpast | {0} min sitten |
| otherminute-narrowpast | {0} min sitten |
| , second | sekunti |
| 0second | nyt |
| onesecondfuture | {0} sekunnin päästä |
| othersecondfuture | {0} sekunnin päästä |
| onesecondpast | {0} sekunti sitten |
| othersecondpast | {0} sekuntia sitten |
| , second-short | s |
| 0second-short | nyt |
| onesecond-shortfuture | {0} s päästä |
| othersecond-shortfuture | {0} s päästä |
| onesecond-shortpast | {0} s sitten |
| othersecond-shortpast | {0} s sitten |
| , second-narrow | s |
| 0second-narrow | nyt |
| onesecond-narrowfuture | {0} s päästä |
| othersecond-narrowfuture | {0} s päästä |
| onesecond-narrowpast | {0} s sitten |
| othersecond-narrowpast | {0} s sitten |
| , zone | aikavyöhyke |
| , zone-short | aikavyöhyke |
| , zone-narrow | aikavyöhyke |

#### time zones

| Format name | Format |
| ----------- | ------ |
| Hours from UTC | +H.mm;-H.mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional | aikavyöhyke: {0} |
| regional | {0} (kesäaika) |
| regional | {0} (normaaliaika) |
| fallback | {1} ({0}) |

| Zone | Name |
| ---- | ---- |
| America/Santa_Isabel | Santa Isabel |
| Pacific/Honolulu | Honolulu |
| Etc/UTC | UTC-yleisaika |
| Etc/Unknown | tuntematon |
| Europe/Andorra | Andorra |
| Asia/Dubai | Dubai |
| Asia/Kabul | Kabul |
| America/Antigua | Antigua |
| America/Anguilla | Anguilla |
| Europe/Tirane | Tirana |
| Asia/Yerevan | Jerevan |
| Africa/Luanda | Luanda |
| Antarctica/Rothera | Rothera |
| Antarctica/Palmer | Palmer |
| Antarctica/Troll | Troll |
| Antarctica/Syowa | Syowa |
| Antarctica/Mawson | Mawson |
| Antarctica/Davis | Davis |
| Antarctica/Vostok | Vostok |
| Antarctica/Casey | Casey |
| Antarctica/DumontDUrville | Dumont d’Urville |
| Antarctica/McMurdo | McMurdo |
| America/Argentina/Rio_Gallegos | Rio Gallegos |
| America/Mendoza | Mendoza |
| America/Argentina/San_Juan | San Juan |
| America/Argentina/Ushuaia | Ushuaia |
| America/Argentina/La_Rioja | La Rioja |
| America/Argentina/San_Luis | San Luis |
| America/Catamarca | Catamarca |
| America/Argentina/Salta | Salta |
| America/Jujuy | Jujuy |
| America/Argentina/Tucuman | Tucumán |
| America/Cordoba | Córdoba |
| America/Buenos_Aires | Buenos Aires |
| Pacific/Pago_Pago | Pago Pago |
| Europe/Vienna | Wien |
| Australia/Perth | Perth |
| Australia/Eucla | Eucla |
| Australia/Darwin | Darwin |
| Australia/Adelaide | Adelaide |
| Australia/Broken_Hill | Broken Hill |
| Australia/Currie | Currie |
| Australia/Melbourne | Melbourne |
| Australia/Hobart | Hobart |
| Australia/Lindeman | Lindeman |
| Australia/Sydney | Sydney |
| Australia/Brisbane | Brisbane |
| Antarctica/Macquarie | Macquariensaari |
| Australia/Lord_Howe | Lord Howe |
| America/Aruba | Aruba |
| Europe/Mariehamn | MaarianhaminaMariehamn |
| Asia/Baku | Baku |
| Europe/Sarajevo | Sarajevo |
| America/Barbados | Barbados |
| Asia/Dhaka | Dhaka |
| Europe/Brussels | Bryssel |
| Africa/Ouagadougou | Ouagadougou |
| Europe/Sofia | Sofia |
| Asia/Bahrain | Bahrain |
| Africa/Bujumbura | Bujumbura |
| Africa/Porto-Novo | Porto-Novo |
| America/St_Barthelemy | Saint-Barthélemy |
| Atlantic/Bermuda | Bermuda |
| Asia/Brunei | Brunei |
| America/La_Paz | La Paz |
| America/Kralendijk | Kralendijk |
| America/Eirunepe | Eirunepé |
| America/Rio_Branco | Rio Branco |
| America/Porto_Velho | Porto Velho |
| America/Boa_Vista | Boa Vista |
| America/Manaus | Manaus |
| America/Cuiaba | Cuiabá |
| America/Santarem | Santarém |
| America/Campo_Grande | Campo Grande |
| America/Belem | Belem |
| America/Araguaina | Araguaína |
| America/Sao_Paulo | São Paulo |
| America/Bahia | Bahia |
| America/Fortaleza | Fortaleza |
| America/Maceio | Maceió |
| America/Recife | Recife |
| America/Noronha | Noronha |
| America/Nassau | Nassau |
| Asia/Thimphu | Thimphu |
| Africa/Gaborone | Gaborone |
| Europe/Minsk | Minsk |
| America/Belize | Belize |
| America/Dawson | Dawson |
| America/Whitehorse | Whitehorse |
| America/Inuvik | Inuvik |
| America/Vancouver | Vancouver |
| America/Fort_Nelson | Fort Nelson |
| America/Dawson_Creek | Dawson Creek |
| America/Creston | Creston |
| America/Yellowknife | Yellowknife |
| America/Edmonton | Edmonton |
| America/Swift_Current | Swift Current |
| America/Cambridge_Bay | Cambridge Bay |
| America/Regina | Regina |
| America/Winnipeg | Winnipeg |
| America/Resolute | Resolute |
| America/Rainy_River | Rainy River |
| America/Rankin_Inlet | Rankin Inlet |
| America/Coral_Harbour | Atikokan |
| America/Thunder_Bay | Thunder Bay |
| America/Nipigon | Nipigon |
| America/Toronto | Toronto |
| America/Iqaluit | Iqaluit |
| America/Pangnirtung | Pangnirtung |
| America/Moncton | Moncton |
| America/Halifax | Halifax |
| America/Goose_Bay | Goose Bay |
| America/Glace_Bay | Glace Bay |
| America/Blanc-Sablon | Blanc-Sablon |
| America/St_Johns | St. John’s |
| Indian/Cocos | Kookossaaret |
| Africa/Kinshasa | Kinshasa |
| Africa/Lubumbashi | Lubumbashi |
| Africa/Bangui | Bangui |
| Africa/Brazzaville | Brazzaville |
| Europe/Zurich | Zürich |
| Africa/Abidjan | Abidjan |
| Pacific/Rarotonga | Rarotonga |
| Pacific/Easter | Pääsiäissaari |
| America/Punta_Arenas | Punta Arenas |
| America/Santiago | Santiago de Chile |
| Africa/Douala | Douala |
| Asia/Urumqi | Ürümqi |
| Asia/Shanghai | Shanghai |
| America/Bogota | Bogotá |
| America/Costa_Rica | Costa Rica |
| America/Havana | Havanna |
| Atlantic/Cape_Verde | Kap Verde |
| America/Curacao | Curaçao |
| Indian/Christmas | Joulusaari |
| Asia/Nicosia | Nikosia |
| Asia/Famagusta | Famagusta |
| Europe/Prague | Praha |
| Europe/Busingen | Büsingen |
| Europe/Berlin | Berliini |
| Africa/Djibouti | Djibouti |
| Europe/Copenhagen | Kööpenhamina |
| America/Dominica | Dominica |
| America/Santo_Domingo | Santo Domingo |
| Africa/Algiers | Alger |
| Pacific/Galapagos | Galapagos |
| America/Guayaquil | Guayaquil |
| Europe/Tallinn | Tallinna |
| Africa/Cairo | Kairo |
| Africa/El_Aaiun | El Aaiún |
| Africa/Asmera | Asmara |
| Atlantic/Canary | Kanariansaaret |
| Africa/Ceuta | Ceuta |
| Europe/Madrid | Madrid |
| Africa/Addis_Ababa | Addis Abeba |
| Europe/Helsinki | Helsinki |
| Pacific/Fiji | Fidži |
| Atlantic/Stanley | Stanley |
| Pacific/Truk | Chuuk |
| Pacific/Ponape | Pohnpei |
| Pacific/Kosrae | Kosrae |
| Atlantic/Faeroe | Färsaaret |
| Europe/Paris | Pariisi |
| Africa/Libreville | Libreville |
| Europe/London | Lontoo |
|  daylight savings | Britannian kesäaika |
| America/Grenada | Grenada |
| Asia/Tbilisi | Tbilisi |
| America/Cayenne | Cayenne |
| Europe/Guernsey | Guernsey |
| Africa/Accra | Accra |
| Europe/Gibraltar | Gibraltar |
| America/Thule | ThuleQaanaaq |
| America/Godthab | NuukGodthåb |
| America/Scoresbysund | IttoqqortoormiitScoresbysund |
| America/Danmarkshavn | Danmarkshavn |
| Africa/Banjul | Banjul |
| Africa/Conakry | Conakry |
| America/Guadeloupe | Guadeloupe |
| Africa/Malabo | Malabo |
| Europe/Athens | Ateena |
| Atlantic/South_Georgia | Etelä-Georgia |
| America/Guatemala | Guatemala |
| Pacific/Guam | Guam |
| Africa/Bissau | Bissau |
| America/Guyana | Guyana |
| Asia/Hong_Kong | Hongkong |
| America/Tegucigalpa | Tegucigalpa |
| Europe/Zagreb | Zagreb |
| America/Port-au-Prince | Port-au-Prince |
| Europe/Budapest | Budapest |
| Asia/Jakarta | Jakarta |
| Asia/Pontianak | Pontianak |
| Asia/Makassar | Makassar |
| Asia/Jayapura | Jayapura |
| Europe/Dublin | Dublin |
|  daylight savings | Irlannin kesäaika |
| Asia/Jerusalem | Jerusalem |
| Europe/Isle_of_Man | Mansaari |
| Asia/Calcutta | Kalkutta |
| Indian/Chagos | Chagos |
| Asia/Baghdad | Bagdad |
| Asia/Tehran | Teheran |
| Atlantic/Reykjavik | Reykjavík |
| Europe/Rome | Rooma |
| Europe/Jersey | Jersey |
| America/Jamaica | Jamaika |
| Asia/Amman | Amman |
| Asia/Tokyo | Tokio |
| Africa/Nairobi | Nairobi |
| Asia/Bishkek | Biškek |
| Asia/Phnom_Penh | Phnom Penh |
| Pacific/Enderbury | Enderbury |
| Pacific/Kiritimati | Kiritimati |
| Pacific/Tarawa | Tarawa |
| Indian/Comoro | Komorit |
| America/St_Kitts | Saint Kitts |
| Asia/Pyongyang | Pjongjang |
| Asia/Seoul | Soul |
| Asia/Kuwait | Kuwait |
| America/Cayman | Cayman |
| Asia/Aqtau | Aqtaw |
| Asia/Oral | Uralsk |
| Asia/Atyrau | Atıraw |
| Asia/Aqtobe | Aqtöbe |
| Asia/Qyzylorda | Qızılorda |
| Asia/Almaty | Almaty |
| Asia/Vientiane | Vientiane |
| Asia/Beirut | Beirut |
| America/St_Lucia | Saint Lucia |
| Europe/Vaduz | Vaduz |
| Asia/Colombo | Colombo |
| Africa/Monrovia | Monrovia |
| Africa/Maseru | Maseru |
| Europe/Vilnius | Vilna |
| Europe/Luxembourg | Luxemburg |
| Europe/Riga | Riika |
| Africa/Tripoli | Tripoli |
| Africa/Casablanca | Casablanca |
| Europe/Monaco | Monaco |
| Europe/Chisinau | Chişinău |
| Europe/Podgorica | Podgorica |
| America/Marigot | Marigot |
| Indian/Antananarivo | Antananarivo |
| Pacific/Kwajalein | Kwajalein |
| Pacific/Majuro | Majuro |
| Europe/Skopje | Skopje |
| Africa/Bamako | Bamako |
| Asia/Rangoon | Yangon |
| Asia/Hovd | Hovd |
| Asia/Ulaanbaatar | Ulan Bator |
| Asia/Choibalsan | Tšoibalsa |
| Asia/Macau | Macao |
| Pacific/Saipan | Saipan |
| America/Martinique | Martinique |
| Africa/Nouakchott | Nouakchott |
| America/Montserrat | Montserrat |
| Europe/Malta | Malta |
| Indian/Mauritius | Mauritius |
| Indian/Maldives | Malediivit |
| Africa/Blantyre | Blantyre |
| America/Tijuana | Tijuana |
| America/Hermosillo | Hermosillo |
| America/Mazatlan | Mazatlán |
| America/Chihuahua | Chihuahua |
| America/Bahia_Banderas | Bahía de Banderas |
| America/Ojinaga | Ojinaga |
| America/Monterrey | Monterrey |
| America/Mexico_City | Ciudad de México |
| America/Matamoros | Matamoros |
| America/Merida | Mérida |
| America/Cancun | Cancún |
| Asia/Kuala_Lumpur | Kuala Lumpur |
| Asia/Kuching | Kuching |
| Africa/Maputo | Maputo |
| Africa/Windhoek | Windhoek |
| Pacific/Noumea | Nouméa |
| Africa/Niamey | Niamey |
| Pacific/Norfolk | Norfolk |
| Africa/Lagos | Lagos |
| America/Managua | Managua |
| Europe/Amsterdam | Amsterdam |
| Europe/Oslo | Oslo |
| Asia/Katmandu | Kathmandu |
| Pacific/Nauru | Nauru |
| Pacific/Niue | Niue |
| Pacific/Chatham | Chathamsaaret |
| Pacific/Auckland | Auckland |
| Asia/Muscat | Masqat |
| America/Panama | Panama |
| America/Lima | Lima |
| Pacific/Tahiti | Tahiti |
| Pacific/Marquesas | Marquesassaaret |
| Pacific/Gambier | Gambiersaaret |
| Pacific/Port_Moresby | Port Moresby |
| Pacific/Bougainville | Bougainville |
| Asia/Manila | Manila |
| Asia/Karachi | Karachi |
| Europe/Warsaw | Varsova |
| America/Miquelon | Miquelon |
| Pacific/Pitcairn | Pitcairn |
| America/Puerto_Rico | Puerto Rico |
| Asia/Gaza | Gaza |
| Asia/Hebron | Hebron |
| Atlantic/Azores | Azorit |
| Atlantic/Madeira | Madeira |
| Europe/Lisbon | Lissabon |
| Pacific/Palau | Palau |
| America/Asuncion | Asunción |
| Asia/Qatar | Qatar |
| Indian/Reunion | Réunion |
| Europe/Bucharest | Bukarest |
| Europe/Belgrade | Belgrad |
| Europe/Kaliningrad | Kaliningrad |
| Europe/Simferopol | Simferopol |
| Europe/Moscow | Moskova |
| Europe/Volgograd | Volgograd |
| Europe/Saratov | Saratov |
| Europe/Astrakhan | Astrahan |
| Europe/Ulyanovsk | Uljanovsk |
| Europe/Kirov | Kirov |
| Europe/Samara | Samara |
| Asia/Yekaterinburg | Jekaterinburg |
| Asia/Omsk | Omsk |
| Asia/Novosibirsk | Novosibirsk |
| Asia/Barnaul | Barnaul |
| Asia/Tomsk | Tomsk |
| Asia/Novokuznetsk | Novokuznetsk |
| Asia/Krasnoyarsk | Krasnojarsk |
| Asia/Irkutsk | Irkutsk |
| Asia/Chita | Tšita |
| Asia/Yakutsk | Jakutsk |
| Asia/Vladivostok | Vladivostok |
| Asia/Khandyga | Handyga |
| Asia/Sakhalin | Sahalin |
| Asia/Ust-Nera | Ust-Nera |
| Asia/Magadan | Magadan |
| Asia/Srednekolymsk | Srednekolymsk |
| Asia/Kamchatka | Kamtšatka |
| Asia/Anadyr | Anadyr |
| Africa/Kigali | Kigali |
| Asia/Riyadh | Riad |
| Pacific/Guadalcanal | Guadalcanal |
| Indian/Mahe | Mahé |
| Africa/Khartoum | Khartum |
| Europe/Stockholm | Tukholma |
| Asia/Singapore | Singapore |
| Atlantic/St_Helena | Saint Helena |
| Europe/Ljubljana | Ljubljana |
| Arctic/Longyearbyen | Longyearbyen |
| Europe/Bratislava | Bratislava |
| Africa/Freetown | Freetown |
| Europe/San_Marino | San Marino |
| Africa/Dakar | Dakar |
| Africa/Mogadishu | Mogadishu |
| America/Paramaribo | Paramaribo |
| Africa/Juba | Juba |
| Africa/Sao_Tome | São Tomé |
| America/El_Salvador | El Salvador |
| America/Lower_Princes | Lower Prince’s Quarter |
| Asia/Damascus | Damaskos |
| Africa/Mbabane | Mbabane |
| America/Grand_Turk | Grand Turk |
| Africa/Ndjamena | N’Djamena |
| Indian/Kerguelen | Kerguelensaaret |
| Africa/Lome | Lomé |
| Asia/Bangkok | Bangkok |
| Asia/Dushanbe | Dušanbe |
| Pacific/Fakaofo | Fakaofo |
| Asia/Dili | Dili |
| Asia/Ashgabat | Ašgabat |
| Africa/Tunis | Tunis |
| Pacific/Tongatapu | Tongatapu |
| Europe/Istanbul | Istanbul |
| America/Port_of_Spain | Port of Spain |
| Pacific/Funafuti | Funafuti |
| Asia/Taipei | Taipei |
| Africa/Dar_es_Salaam | Dar es Salaam |
| Europe/Uzhgorod | Užgorod |
| Europe/Kiev | Kiova |
| Europe/Zaporozhye | Zaporižžja |
| Africa/Kampala | Kampala |
| Pacific/Midway | Midwaysaaret |
| Pacific/Wake | Wake |
| America/Adak | Adak |
| America/Nome | Nome |
| Pacific/Johnston | Johnston |
| America/Anchorage | Anchorage |
| America/Yakutat | Yakutat |
| America/Sitka | Sitka |
| America/Juneau | Juneau |
| America/Metlakatla | Metlakatla |
| America/Los_Angeles | Los Angeles |
| America/Boise | Boise |
| America/Phoenix | Phoenix |
| America/Denver | Denver |
| America/North_Dakota/Beulah | Beulah, Pohjois-Dakota |
| America/North_Dakota/New_Salem | New Salem, Pohjois-Dakota |
| America/North_Dakota/Center | Center, Pohjois-Dakota |
| America/Chicago | Chicago |
| America/Menominee | Menominee |
| America/Indiana/Vincennes | Vincennes, Indiana |
| America/Indiana/Petersburg | Petersburg, Indiana |
| America/Indiana/Tell_City | Tell City, Indiana |
| America/Indiana/Knox | Knox, Indiana |
| America/Indiana/Winamac | Winamac, Indiana |
| America/Indiana/Marengo | Marengo, Indiana |
| America/Indianapolis | Indianapolis |
| America/Louisville | Louisville |
| America/Indiana/Vevay | Vevay, Indiana |
| America/Kentucky/Monticello | Monticello, Kentucky |
| America/Detroit | Detroit |
| America/New_York | New York |
| America/Montevideo | Montevideo |
| Asia/Samarkand | Samarkand |
| Asia/Tashkent | Taškent |
| Europe/Vatican | Vatikaani |
| America/St_Vincent | Saint Vincent |
| America/Caracas | Caracas |
| America/Tortola | Tortola |
| America/St_Thomas | Saint Thomas |
| Asia/Saigon | Hồ Chí Minhin kaupunki |
| Pacific/Efate | Efate |
| Pacific/Wallis | Wallis |
| Pacific/Apia | Apia |
| Asia/Aden | Aden |
| Indian/Mayotte | Mayotte |
| Africa/Johannesburg | Johannesburg |
| Africa/Lusaka | Lusaka |
| Africa/Harare | Harare |
| Acre | ... |
|  generic | Acren aika |
|  standard | Acren normaaliaika |
|  daylight savings | Acren kesäaika |
| Afghanistan | ... |
|  standard | Afganistanin aika |
| Africa_Central | ... |
|  standard | Keski-Afrikan aika |
| Africa_Eastern | ... |
|  standard | Itä-Afrikan aika |
| Africa_Southern | ... |
|  standard | Etelä-Afrikan aika |
| Africa_Western | ... |
|  generic | Länsi-Afrikan aika |
|  standard | Länsi-Afrikan normaaliaika |
|  daylight savings | Länsi-Afrikan kesäaika |
| Alaska | ... |
|  generic | Alaskan aika |
|  standard | Alaskan normaaliaika |
|  daylight savings | Alaskan kesäaika |
| Almaty | ... |
|  generic | Almatyn aika |
|  standard | Almatyn normaaliaika |
|  daylight savings | Almatyn kesäaika |
| Amazon | ... |
|  generic | Amazonin aika |
|  standard | Amazonin normaaliaika |
|  daylight savings | Amazonin kesäaika |
| America_Central | ... |
|  generic | Yhdysvaltain keskinen aika |
|  standard | Yhdysvaltain keskinen normaaliaika |
|  daylight savings | Yhdysvaltain keskinen kesäaika |
| America_Eastern | ... |
|  generic | Yhdysvaltain itäinen aika |
|  standard | Yhdysvaltain itäinen normaaliaika |
|  daylight savings | Yhdysvaltain itäinen kesäaika |
| America_Mountain | ... |
|  generic | Kalliovuorten aika |
|  standard | Kalliovuorten normaaliaika |
|  daylight savings | Kalliovuorten kesäaika |
| America_Pacific | ... |
|  generic | Yhdysvaltain Tyynenmeren aika |
|  standard | Yhdysvaltain Tyynenmeren normaaliaika |
|  daylight savings | Yhdysvaltain Tyynenmeren kesäaika |
| Anadyr | ... |
|  generic | Anadyrin aika |
|  standard | Anadyrin normaaliaika |
|  daylight savings | Anadyrin kesäaika |
| Apia | ... |
|  generic | Apian aika |
|  standard | Apian normaaliaika |
|  daylight savings | Apian kesäaika |
| Aqtau | ... |
|  generic | Aqtaw’n aika |
|  standard | Aqtaw’n normaaliaika |
|  daylight savings | Aqtaw’n kesäaika |
| Aqtobe | ... |
|  generic | Aqtöben aika |
|  standard | Aqtöben normaaliaika |
|  daylight savings | Aqtöben kesäaika |
| Arabian | ... |
|  generic | Saudi-Arabian aika |
|  standard | Saudi-Arabian normaaliaika |
|  daylight savings | Saudi-Arabian kesäaika |
| Argentina | ... |
|  generic | Argentiinan aika |
|  standard | Argentiinan normaaliaika |
|  daylight savings | Argentiinan kesäaika |
| Argentina_Western | ... |
|  generic | Länsi-Argentiinan aika |
|  standard | Länsi-Argentiinan normaaliaika |
|  daylight savings | Länsi-Argentiinan kesäaika |
| Armenia | ... |
|  generic | Armenian aika |
|  standard | Armenian normaaliaika |
|  daylight savings | Armenian kesäaika |
| Atlantic | ... |
|  generic | Kanadan Atlantin aika |
|  standard | Kanadan Atlantin normaaliaika |
|  daylight savings | Kanadan Atlantin kesäaika |
| Australia_Central | ... |
|  generic | Keski-Australian aika |
|  standard | Keski-Australian normaaliaika |
|  daylight savings | Keski-Australian kesäaika |
| Australia_CentralWestern | ... |
|  generic | Läntisen Keski-Australian aika |
|  standard | Läntisen Keski-Australian normaaliaika |
|  daylight savings | Läntisen Keski-Australian kesäaika |
| Australia_Eastern | ... |
|  generic | Itä-Australian aika |
|  standard | Itä-Australian normaaliaika |
|  daylight savings | Itä-Australian kesäaika |
| Australia_Western | ... |
|  generic | Länsi-Australian aika |
|  standard | Länsi-Australian normaaliaika |
|  daylight savings | Länsi-Australian kesäaika |
| Azerbaijan | ... |
|  generic | Azerbaidžanin aika |
|  standard | Azerbaidžanin normaaliaika |
|  daylight savings | Azerbaidžanin kesäaika |
| Azores | ... |
|  generic | Azorien aika |
|  standard | Azorien normaaliaika |
|  daylight savings | Azorien kesäaika |
| Bangladesh | ... |
|  generic | Bangladeshin aika |
|  standard | Bangladeshin normaaliaika |
|  daylight savings | Bangladeshin kesäaika |
| Bhutan | ... |
|  standard | Bhutanin aika |
| Bolivia | ... |
|  standard | Bolivian aika |
| Brasilia | ... |
|  generic | Brasilian aika |
|  standard | Brasilian normaaliaika |
|  daylight savings | Brasilian kesäaika |
| Brunei | ... |
|  standard | Brunein aika |
| Cape_Verde | ... |
|  generic | Kap Verden aika |
|  standard | Kap Verden normaaliaika |
|  daylight savings | Kap Verden kesäaika |
| Casey | ... |
|  standard | Caseyn aika |
| Chamorro | ... |
|  standard | Tšamorron aika |
| Chatham | ... |
|  generic | Chathamin aika |
|  standard | Chathamin normaaliaika |
|  daylight savings | Chathamin kesäaika |
| Chile | ... |
|  generic | Chilen aika |
|  standard | Chilen normaaliaika |
|  daylight savings | Chilen kesäaika |
| China | ... |
|  generic | Kiinan aika |
|  standard | Kiinan normaaliaika |
|  daylight savings | Kiinan kesäaika |
| Choibalsan | ... |
|  generic | Tšoibalsan aika |
|  standard | Tšoibalsan normaaliaika |
|  daylight savings | Tšoibalsan kesäaika |
| Christmas | ... |
|  standard | Joulusaaren aika |
| Cocos | ... |
|  standard | Kookossaarten aika |
| Colombia | ... |
|  generic | Kolumbian aika |
|  standard | Kolumbian normaaliaika |
|  daylight savings | Kolumbian kesäaika |
| Cook | ... |
|  generic | Cookinsaarten aika |
|  standard | Cookinsaarten normaaliaika |
|  daylight savings | Cookinsaarten kesäaika |
| Cuba | ... |
|  generic | Kuuban aika |
|  standard | Kuuban normaaliaika |
|  daylight savings | Kuuban kesäaika |
| Davis | ... |
|  standard | Davisin aika |
| DumontDUrville | ... |
|  standard | Dumont d’Urvillen aika |
| East_Timor | ... |
|  standard | Itä-Timorin aika |
| Easter | ... |
|  generic | Pääsiäissaaren aika |
|  standard | Pääsiäissaaren normaaliaika |
|  daylight savings | Pääsiäissaaren kesäaika |
| Ecuador | ... |
|  standard | Ecuadorin aika |
| Europe_Central | ... |
|  generic | Keski-Euroopan aika |
|  standard | Keski-Euroopan normaaliaika |
|  daylight savings | Keski-Euroopan kesäaika |
| Europe_Eastern | ... |
|  generic | Itä-Euroopan aika |
|  standard | Itä-Euroopan normaaliaika |
|  daylight savings | Itä-Euroopan kesäaika |
| Europe_Further_Eastern | ... |
|  standard | Itäisemmän Euroopan aika |
| Europe_Western | ... |
|  generic | Länsi-Euroopan aika |
|  standard | Länsi-Euroopan normaaliaika |
|  daylight savings | Länsi-Euroopan kesäaika |
| Falkland | ... |
|  generic | Falklandinsaarten aika |
|  standard | Falklandinsaarten normaaliaika |
|  daylight savings | Falklandinsaarten kesäaika |
| Fiji | ... |
|  generic | Fidžin aika |
|  standard | Fidžin normaaliaika |
|  daylight savings | Fidžin kesäaika |
| French_Guiana | ... |
|  standard | Ranskan Guayanan aika |
| French_Southern | ... |
|  standard | Ranskan eteläisten ja antarktisten alueiden aika |
| Galapagos | ... |
|  standard | Galápagossaarten aika |
| Gambier | ... |
|  standard | Gambiersaarten aika |
| Georgia | ... |
|  generic | Georgian aika |
|  standard | Georgian normaaliaika |
|  daylight savings | Georgian kesäaika |
| Gilbert_Islands | ... |
|  standard | Gilbertsaarten aika |
| GMT | ... |
|  standard | Greenwichin normaaliaika |
| Greenland_Eastern | ... |
|  generic | Itä-Grönlannin aika |
|  standard | Itä-Grönlannin normaaliaika |
|  daylight savings | Itä-Grönlannin kesäaika |
| Greenland_Western | ... |
|  generic | Länsi-Grönlannin aika |
|  standard | Länsi-Grönlannin normaaliaika |
|  daylight savings | Länsi-Grönlannin kesäaika |
| Guam | ... |
|  standard | Guamin aika |
| Gulf | ... |
|  standard | Arabiemiirikuntien normaaliaika |
| Guyana | ... |
|  standard | Guyanan aika |
| Hawaii_Aleutian | ... |
|  generic | Havaijin-Aleuttien aika |
|  standard | Havaijin-Aleuttien normaaliaika |
|  daylight savings | Havaijin-Aleuttien kesäaika |
| Hong_Kong | ... |
|  generic | Hongkongin aika |
|  standard | Hongkongin normaaliaika |
|  daylight savings | Hongkongin kesäaika |
| Hovd | ... |
|  generic | Hovdin aika |
|  standard | Hovdin normaaliaika |
|  daylight savings | Hovdin kesäaika |
| India | ... |
|  standard | Intian aika |
| Indian_Ocean | ... |
|  standard | Intian valtameren aika |
| Indochina | ... |
|  standard | Indokiinan aika |
| Indonesia_Central | ... |
|  standard | Keski-Indonesian aika |
| Indonesia_Eastern | ... |
|  standard | Itä-Indonesian aika |
| Indonesia_Western | ... |
|  standard | Länsi-Indonesian aika |
| Iran | ... |
|  generic | Iranin aika |
|  standard | Iranin normaaliaika |
|  daylight savings | Iranin kesäaika |
| Irkutsk | ... |
|  generic | Irkutskin aika |
|  standard | Irkutskin normaaliaika |
|  daylight savings | Irkutskin kesäaika |
| Israel | ... |
|  generic | Israelin aika |
|  standard | Israelin normaaliaika |
|  daylight savings | Israelin kesäaika |
| Japan | ... |
|  generic | Japanin aika |
|  standard | Japanin normaaliaika |
|  daylight savings | Japanin kesäaika |
| Kamchatka | ... |
|  generic | Kamtšatkan aika |
|  standard | Kamtšatkan normaaliaika |
|  daylight savings | Kamtšatkan kesäaika |
| Kazakhstan_Eastern | ... |
|  standard | Itä-Kazakstanin aika |
| Kazakhstan_Western | ... |
|  standard | Länsi-Kazakstanin aika |
| Korea | ... |
|  generic | Korean aika |
|  standard | Korean normaaliaika |
|  daylight savings | Korean kesäaika |
| Kosrae | ... |
|  standard | Kosraen aika |
| Krasnoyarsk | ... |
|  generic | Krasnojarskin aika |
|  standard | Krasnojarskin normaaliaika |
|  daylight savings | Krasnojarskin kesäaika |
| Kyrgystan | ... |
|  standard | Kirgisian aika |
| Lanka | ... |
|  standard | Sri Lankan aika |
| Line_Islands | ... |
|  standard | Linesaarten aika |
| Lord_Howe | ... |
|  generic | Lord Howen aika |
|  standard | Lord Howen normaaliaika |
|  daylight savings | Lord Howen kesäaika |
| Macau | ... |
|  generic | Macaon aika |
|  standard | Macaon normaaliaika |
|  daylight savings | Macaon kesäaika |
| Macquarie | ... |
|  standard | Macquariensaaren aika |
| Magadan | ... |
|  generic | Magadanin aika |
|  standard | Magadanin normaaliaika |
|  daylight savings | Magadanin kesäaika |
| Malaysia | ... |
|  standard | Malesian aika |
| Maldives | ... |
|  standard | Malediivien aika |
| Marquesas | ... |
|  standard | Marquesassaarten aika |
| Marshall_Islands | ... |
|  standard | Marshallinsaarten aika |
| Mauritius | ... |
|  generic | Mauritiuksen aika |
|  standard | Mauritiuksen normaaliaika |
|  daylight savings | Mauritiuksen kesäaika |
| Mawson | ... |
|  standard | Mawsonin aika |
| Mexico_Northwest | ... |
|  generic | Luoteis-Meksikon aika |
|  standard | Luoteis-Meksikon normaaliaika |
|  daylight savings | Luoteis-Meksikon kesäaika |
| Mexico_Pacific | ... |
|  generic | Meksikon Tyynenmeren aika |
|  standard | Meksikon Tyynenmeren normaaliaika |
|  daylight savings | Meksikon Tyynenmeren kesäaika |
| Mongolia | ... |
|  generic | Ulan Batorin aika |
|  standard | Ulan Batorin normaaliaika |
|  daylight savings | Ulan Batorin kesäaika |
| Moscow | ... |
|  generic | Moskovan aika |
|  standard | Moskovan normaaliaika |
|  daylight savings | Moskovan kesäaika |
| Myanmar | ... |
|  standard | Myanmarin aika |
| Nauru | ... |
|  standard | Naurun aika |
| Nepal | ... |
|  standard | Nepalin aika |
| New_Caledonia | ... |
|  generic | Uuden-Kaledonian aika |
|  standard | Uuden-Kaledonian normaaliaika |
|  daylight savings | Uuden-Kaledonian kesäaika |
| New_Zealand | ... |
|  generic | Uuden-Seelannin aika |
|  standard | Uuden-Seelannin normaaliaika |
|  daylight savings | Uuden-Seelannin kesäaika |
| Newfoundland | ... |
|  generic | Newfoundlandin aika |
|  standard | Newfoundlandin normaaliaika |
|  daylight savings | Newfoundlandin kesäaika |
| Niue | ... |
|  standard | Niuen aika |
| Norfolk | ... |
|  standard | Norfolkinsaaren aika |
| Noronha | ... |
|  generic | Fernando de Noronhan aika |
|  standard | Fernando de Noronhan normaaliaika |
|  daylight savings | Fernando de Noronhan kesäaika |
| North_Mariana | ... |
|  standard | Pohjois-Mariaanien aika |
| Novosibirsk | ... |
|  generic | Novosibirskin aika |
|  standard | Novosibirskin normaaliaika |
|  daylight savings | Novosibirskin kesäaika |
| Omsk | ... |
|  generic | Omskin aika |
|  standard | Omskin normaaliaika |
|  daylight savings | Omskin kesäaika |
| Pakistan | ... |
|  generic | Pakistanin aika |
|  standard | Pakistanin normaaliaika |
|  daylight savings | Pakistanin kesäaika |
| Palau | ... |
|  standard | Palaun aika |
| Papua_New_Guinea | ... |
|  standard | Papua-Uuden-Guinean aika |
| Paraguay | ... |
|  generic | Paraguayn aika |
|  standard | Paraguayn normaaliaika |
|  daylight savings | Paraguayn kesäaika |
| Peru | ... |
|  generic | Perun aika |
|  standard | Perun normaaliaika |
|  daylight savings | Perun kesäaika |
| Philippines | ... |
|  generic | Filippiinien aika |
|  standard | Filippiinien normaaliaika |
|  daylight savings | Filippiinien kesäaika |
| Phoenix_Islands | ... |
|  standard | Phoenixsaarten aika |
| Pierre_Miquelon | ... |
|  generic | Saint-Pierren ja Miquelonin aika |
|  standard | Saint-Pierren ja Miquelonin normaaliaika |
|  daylight savings | Saint-Pierren ja Miquelonin kesäaika |
| Pitcairn | ... |
|  standard | Pitcairnin aika |
| Ponape | ... |
|  standard | Pohnpein aika |
| Pyongyang | ... |
|  standard | Pjongjangin aika |
| Qyzylorda | ... |
|  generic | Qızılordan aika |
|  standard | Qızılordan normaaliaika |
|  daylight savings | Qızılordan kesäaika |
| Reunion | ... |
|  standard | Réunionin aika |
| Rothera | ... |
|  standard | Rotheran aika |
| Sakhalin | ... |
|  generic | Sahalinin aika |
|  standard | Sahalinin normaaliaika |
|  daylight savings | Sahalinin kesäaika |
| Samara | ... |
|  generic | Samaran aika |
|  standard | Samaran normaaliaika |
|  daylight savings | Samaran kesäaika |
| Samoa | ... |
|  generic | Samoan aika |
|  standard | Samoan normaaliaika |
|  daylight savings | Samoan kesäaika |
| Seychelles | ... |
|  standard | Seychellien aika |
| Singapore | ... |
|  standard | Singaporen aika |
| Solomon | ... |
|  standard | Salomonsaarten aika |
| South_Georgia | ... |
|  standard | Etelä-Georgian aika |
| Suriname | ... |
|  standard | Surinamen aika |
| Syowa | ... |
|  standard | Syowan aika |
| Tahiti | ... |
|  standard | Tahitin aika |
| Taipei | ... |
|  generic | Taipein aika |
|  standard | Taipein normaaliaika |
|  daylight savings | Taipein kesäaika |
| Tajikistan | ... |
|  standard | Tadžikistanin aika |
| Tokelau | ... |
|  standard | Tokelaun aika |
| Tonga | ... |
|  generic | Tongan aika |
|  standard | Tongan normaaliaika |
|  daylight savings | Tongan kesäaika |
| Truk | ... |
|  standard | Chuukin aika |
| Turkmenistan | ... |
|  generic | Turkmenistanin aika |
|  standard | Turkmenistanin normaaliaika |
|  daylight savings | Turkmenistanin kesäaika |
| Tuvalu | ... |
|  standard | Tuvalun aika |
| Uruguay | ... |
|  generic | Uruguayn aika |
|  standard | Uruguayn normaaliaika |
|  daylight savings | Uruguayn kesäaika |
| Uzbekistan | ... |
|  generic | Uzbekistanin aika |
|  standard | Uzbekistanin normaaliaika |
|  daylight savings | Uzbekistanin kesäaika |
| Vanuatu | ... |
|  generic | Vanuatun aika |
|  standard | Vanuatun normaaliaika |
|  daylight savings | Vanuatun kesäaika |
| Venezuela | ... |
|  standard | Venezuelan aika |
| Vladivostok | ... |
|  generic | Vladivostokin aika |
|  standard | Vladivostokin normaaliaika |
|  daylight savings | Vladivostokin kesäaika |
| Volgograd | ... |
|  generic | Volgogradin aika |
|  standard | Volgogradin normaaliaika |
|  daylight savings | Volgogradin kesäaika |
| Vostok | ... |
|  standard | Vostokin aika |
| Wake | ... |
|  standard | Waken aika |
| Wallis | ... |
|  standard | Wallisin ja Futunan aika |
| Yakutsk | ... |
|  generic | Jakutskin aika |
|  standard | Jakutskin normaaliaika |
|  daylight savings | Jakutskin kesäaika |
| Yekaterinburg | ... |
|  generic | Jekaterinburgin aika |
|  standard | Jekaterinburgin normaaliaika |
|  daylight savings | Jekaterinburgin kesäaika |

## Numbers stuff

Using `latn` numbering by default.
Using `latn` numbering also.
`1` minimum grouping digits.

#### Symbols

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
| Not a number | epäluku |
| Time separator (Hours:Minutes) | . |

#### Decimal formatting

| Format name | Pattern |
| ----------- | ------- |
| standard,  | `#,##0.###` |
| one1000, long | `0 tuhat` |
| other1000, long | `0 tuhatta` |
| one10000, long | `00 tuhatta` |
| other10000, long | `00 tuhatta` |
| one100000, long | `000 tuhatta` |
| other100000, long | `000 tuhatta` |
| one1000000, long | `0 miljoona` |
| other1000000, long | `0 miljoonaa` |
| one10000000, long | `00 miljoonaa` |
| other10000000, long | `00 miljoonaa` |
| one100000000, long | `000 miljoonaa` |
| other100000000, long | `000 miljoonaa` |
| one1000000000, long | `0 miljardi` |
| other1000000000, long | `0 miljardia` |
| one10000000000, long | `00 miljardia` |
| other10000000000, long | `00 miljardia` |
| one100000000000, long | `000 miljardia` |
| other100000000000, long | `000 miljardia` |
| one1000000000000, long | `0 biljoona` |
| other1000000000000, long | `0 biljoonaa` |
| one10000000000000, long | `00 biljoonaa` |
| other10000000000000, long | `00 biljoonaa` |
| one100000000000000, long | `000 biljoonaa` |
| other100000000000000, long | `000 biljoonaa` |
| one1000, short | `0 t'.'` |
| other1000, short | `0 t'.'` |
| one10000, short | `00 t'.'` |
| other10000, short | `00 t'.'` |
| one100000, short | `000 t'.'` |
| other100000, short | `000 t'.'` |
| one1000000, short | `0 milj'.'` |
| other1000000, short | `0 milj'.'` |
| one10000000, short | `00 milj'.'` |
| other10000000, short | `00 milj'.'` |
| one100000000, short | `000 milj'.'` |
| other100000000, short | `000 milj'.'` |
| one1000000000, short | `0 mrd'.'` |
| other1000000000, short | `0 mrd'.'` |
| one10000000000, short | `00 mrd'.'` |
| other10000000000, short | `00 mrd'.'` |
| one100000000000, short | `000 mrd'.'` |
| other100000000000, short | `000 mrd'.'` |
| one1000000000000, short | `0 bilj'.'` |
| other1000000000000, short | `0 bilj'.'` |
| one10000000000000, short | `00 bilj'.'` |
| other10000000000000, short | `00 bilj'.'` |
| one100000000000000, short | `000 bilj'.'` |
| other100000000000000, short | `000 bilj'.'` |
| standard,  | `#E0` |
| standard,  | `#,##0 %` |
| standard,  | `#,##0.00 ¤` |
| standard,  | `#,##0.00 ¤` |
| one1000, short | `0 t'.' ¤` |
| other1000, short | `0 t'.' ¤` |
| one10000, short | `00 t'.' ¤` |
| other10000, short | `00 t'.' ¤` |
| one100000, short | `000 t'.' ¤` |
| other100000, short | `000 t'.' ¤` |
| one1000000, short | `0 milj'.' ¤` |
| other1000000, short | `0 milj'.' ¤` |
| one10000000, short | `00 milj'.' ¤` |
| other10000000, short | `00 milj'.' ¤` |
| one100000000, short | `000 milj'.' ¤` |
| other100000000, short | `000 milj'.' ¤` |
| one1000000000, short | `0 mrd'.' ¤` |
| other1000000000, short | `0 mrd'.' ¤` |
| one10000000000, short | `00 mrd'.' ¤` |
| other10000000000, short | `00 mrd'.' ¤` |
| one100000000000, short | `000 mrd'.' ¤` |
| other100000000000, short | `000 mrd'.' ¤` |
| one1000000000000, short | `0 bilj'.' ¤` |
| other1000000000000, short | `0 bilj'.' ¤` |
| one10000000000000, short | `00 bilj'.' ¤` |
| other10000000000000, short | `00 bilj'.' ¤` |
| one100000000000000, short | `000 bilj'.' ¤` |
| other100000000000000, short | `000 bilj'.' ¤` |
| one,  | {0} {1} |
| other,  | {0} {1} |

## Currency names

| Code | Name |
| ---- | ---- |
| , ADP | Andorran peseta |
| one, ADP | Andorran peseta |
| other, ADP | Andorran pesetaa |
| , ADP symbol | ADP |
| , AED | Arabiemiirikuntien dirhami |
| one, AED | Arabiemiirikuntien dirhami |
| other, AED | Arabiemiirikuntien dirhamia |
| , AED symbol | AED |
| , AFA | Afganistanin afgaani (1927–2002) |
| one, AFA | Afganistanin afgaani (1927–2002) |
| other, AFA | Afganistanin afgaania (1927–2002) |
| , AFA symbol | AFA |
| , AFN | Afganistanin afgaani |
| one, AFN | Afganistanin afgaani |
| other, AFN | Afganistanin afgaania |
| , AFN symbol | AFN |
| , ALK | Albanian lek (1946–1965) |
| one, ALK | Albanian lek (1946–1965) |
| other, ALK | Albanian lekiä (1946–1965) |
| , ALK symbol | ALK |
| , ALL | Albanian lek |
| one, ALL | Albanian lek |
| other, ALL | Albanian lekiä |
| , ALL symbol | ALL |
| , AMD | Armenian dram |
| one, AMD | Armenian dram |
| other, AMD | Armenian dramia |
| , AMD symbol | AMD |
| , ANG | Alankomaiden Antillien guldeni |
| one, ANG | Alankomaiden Antillien guldeni |
| other, ANG | Alankomaiden Antillien guldenia |
| , ANG symbol | ANG |
| , AOA | Angolan kwanza |
| one, AOA | Angolan kwanza |
| other, AOA | Angolan kwanzaa |
| , AOA symbol | AOA |
| narrow, AOA symbol | AOA |
| , AOK | Angolan kwanza (1977–1991) |
| one, AOK | Angolan kwanza (1977–1990) |
| other, AOK | Angolan kwanzaa (1977–1990) |
| , AOK symbol | AOK |
| , AON | Angolan uusi kwanza (1990–2000) |
| one, AON | Angolan uusi kwanza (1990–2000) |
| other, AON | Angolan uutta kwanzaa (1990–2000) |
| , AON symbol | AON |
| , AOR | Angolan kwanza reajustado (1995–1999) |
| one, AOR | Angolan kwanza reajustado (1995–1999) |
| other, AOR | Angolan kwanza reajustadoa (1995–1999) |
| , AOR symbol | AOR |
| , ARA | Argentiinan austral |
| one, ARA | Argentiinan austral |
| other, ARA | Argentiinan australia |
| , ARA symbol | ARA |
| , ARL | Argentiinan ley-peso (1970–1983) |
| one, ARL | Argentiinan ley-peso (1970–1983) |
| other, ARL | Argentiinan ley-pesoa (1970–1983) |
| , ARL symbol | ARL |
| , ARM | Argentiinan peso (1881–1970) |
| one, ARM | Argentiinan peso (1881–1970) |
| other, ARM | Argentiinan pesoa (1881–1970) |
| , ARM symbol | ARM |
| , ARP | Argentiinan peso (1983–1985) |
| one, ARP | Argentiinan peso (1983–1985) |
| other, ARP | Argentiinan pesoa (1983–1985) |
| , ARP symbol | ARP |
| , ARS | Argentiinan peso |
| one, ARS | Argentiinan peso |
| other, ARS | Argentiinan pesoa |
| , ARS symbol | ARS |
| narrow, ARS symbol | ARS |
| , ATS | Itävallan šillinki |
| one, ATS | Itävallan šillinki |
| other, ATS | Itävallan šillinkiä |
| , ATS symbol | ATS |
| , AUD | Australian dollari |
| one, AUD | Australian dollari |
| other, AUD | Australian dollaria |
| , AUD symbol | AUD |
| narrow, AUD symbol | AUD |
| , AWG | Aruban floriini |
| one, AWG | Aruban floriini |
| other, AWG | Aruban floriinia |
| , AWG symbol | AWG |
| , AZM | Azerbaidžanin manat (1993–2006) |
| one, AZM | Azerbaidžanin manat (1993–2006) |
| other, AZM | Azerbaidžanin manatia (1993–2006) |
| , AZM symbol | AZM |
| , AZN | Azerbaidžanin manat |
| one, AZN | Azerbaidžanin manat |
| other, AZN | Azerbaidžanin manatia |
| , AZN symbol | AZN |
| , BAD | Bosnia-Hertsegovinan dinaari (1992–1994) |
| one, BAD | Bosnia-Hertsegovinan dinaari (1992–1994) |
| other, BAD | Bosnia-Hertsegovinan dinaaria (1992–1994) |
| , BAD symbol | BAD |
| , BAM | Bosnia-Hertsegovinan vaihdettava markka |
| one, BAM | Bosnia-Hertsegovinan vaihdettava markka |
| other, BAM | Bosnia-Hertsegovinan vaihdettavaa markkaa |
| , BAM symbol | BAM |
| narrow, BAM symbol | BAM |
| , BAN | Bosnia-Hertsegovinan uusi dinaari (1994–1997) |
| one, BAN | Bosnia-Hertsegovinan uusi dinaari (1994–1997) |
| other, BAN | Bosnia-Hertsegovinan uutta dinaaria (1994–1997) |
| , BAN symbol | BAN |
| , BBD | Barbadosin dollari |
| one, BBD | Barbadosin dollari |
| other, BBD | Barbadosin dollaria |
| , BBD symbol | BBD |
| narrow, BBD symbol | BBD |
| , BDT | Bangladeshin taka |
| one, BDT | Bangladeshin taka |
| other, BDT | Bangladeshin takaa |
| , BDT symbol | BDT |
| narrow, BDT symbol | BDT |
| , BEC | Belgian vaihdettava frangi |
| one, BEC | Belgian vaihdettava frangi |
| other, BEC | Belgian vaihdettavaa frangia |
| , BEC symbol | BEC |
| , BEF | Belgian frangi |
| one, BEF | Belgian frangi |
| other, BEF | Belgian frangia |
| , BEF symbol | BEF |
| , BEL | Belgian rahoitusfrangi |
| one, BEL | Belgian rahoitusfrangi |
| other, BEL | Belgian rahoitusfrangia |
| , BEL symbol | BEL |
| , BGL | Bulgarian kova lev |
| one, BGL | Bulgarian kova lev |
| other, BGL | Bulgarian kovaa leviä |
| , BGL symbol | BGL |
| , BGM | Bulgarian sosialistinen lev |
| one, BGM | Bulgarian sosialistinen lev |
| other, BGM | Bulgarian sosialistista leviä |
| , BGM symbol | BGM |
| , BGN | Bulgarian lev |
| one, BGN | Bulgarian lev |
| other, BGN | Bulgarian leviä |
| , BGN symbol | BGN |
| , BGO | Bulgarian lev (1879–1952) |
| one, BGO | Bulgarian lev (1879–1952) |
| other, BGO | Bulgarian leviä (1879–1952) |
| , BGO symbol | BGO |
| , BHD | Bahrainin dinaari |
| one, BHD | Bahrainin dinaari |
| other, BHD | Bahrainin dinaaria |
| , BHD symbol | BHD |
| , BIF | Burundin frangi |
| one, BIF | Burundin frangi |
| other, BIF | Burundin frangia |
| , BIF symbol | BIF |
| , BMD | Bermudan dollari |
| one, BMD | Bermudan dollari |
| other, BMD | Bermudan dollaria |
| , BMD symbol | BMD |
| narrow, BMD symbol | BMD |
| , BND | Brunein dollari |
| one, BND | Brunein dollari |
| other, BND | Brunein dollaria |
| , BND symbol | BND |
| narrow, BND symbol | BND |
| , BOB | Bolivian boliviano |
| one, BOB | Bolivian boliviano |
| other, BOB | Bolivian bolivianoa |
| , BOB symbol | BOB |
| narrow, BOB symbol | BOB |
| , BOL | Bolivian boliviano (1863–1963) |
| one, BOL | Bolivian boliviano (1863–1963) |
| other, BOL | Bolivian bolivianoa (1863–1963) |
| , BOL symbol | BOL |
| , BOP | Bolivian peso |
| one, BOP | Bolivian peso |
| other, BOP | Bolivian pesoa |
| , BOP symbol | BOP |
| , BOV | Bolivian mvdol |
| one, BOV | Bolivian mvdol |
| other, BOV | Bolivian mvdol’ia |
| , BOV symbol | BOV |
| , BRB | Brasilian uusi cruzeiro (1967–1986) |
| one, BRB | Brasilian uusi cruzeiro (1967–1986) |
| other, BRB | Brasilian uutta cruzeiroa (1967–1986) |
| , BRB symbol | BRB |
| , BRC | Brasilian cruzado (1986–1989) |
| one, BRC | Brasilian cruzado (1986–1989) |
| other, BRC | Brasilian cruzadoa (1986–1989) |
| , BRC symbol | BRC |
| , BRE | Brasilian cruzeiro (1990–1993) |
| one, BRE | Brasilian cruzeiro (1990–1993) |
| other, BRE | Brasilian cruzeiroa (1990–1993) |
| , BRE symbol | BRE |
| , BRL | Brasilian real |
| one, BRL | Brasilian real |
| other, BRL | Brasilian realia |
| , BRL symbol | BRL |
| narrow, BRL symbol | BRL |
| , BRN | Brasilian uusi cruzado (1989–1990) |
| one, BRN | Brasilian uusi cruzado (1989–1990) |
| other, BRN | Brasilian uutta cruzadoa (1989–1990) |
| , BRN symbol | BRN |
| , BRR | Brasilian cruzeiro (1993–1994) |
| one, BRR | Brasilian cruzeiro (1993–1994) |
| other, BRR | Brasilian cruzeiroa (1993–1994) |
| , BRR symbol | BRR |
| , BRZ | Brasilian cruzeiro (1942–1967) |
| one, BRZ | Brasilian cruzeiro (1942–1967) |
| other, BRZ | Brasilian cruzeiroa (1942–1967) |
| , BRZ symbol | BRZ |
| , BSD | Bahaman dollari |
| one, BSD | Bahaman dollari |
| other, BSD | Bahaman dollaria |
| , BSD symbol | BSD |
| narrow, BSD symbol | BSD |
| , BTN | Bhutanin ngultrum |
| one, BTN | Bhutanin ngultrum |
| other, BTN | Bhutanin ngultrumia |
| , BTN symbol | BTN |
| , BUK | Burman kyat |
| one, BUK | Burman kyat |
| other, BUK | Burman kyatia |
| , BUK symbol | BUK |
| , BWP | Botswanan pula |
| one, BWP | Botswanan pula |
| other, BWP | Botswanan pulaa |
| , BWP symbol | BWP |
| narrow, BWP symbol | BWP |
| , BYB | Valko-Venäjän uusi rupla (1994–1999) |
| one, BYB | Valko-Venäjän uusi rupla (1994–1999) |
| other, BYB | Valko-Venäjän uutta ruplaa (1994–1999) |
| , BYB symbol | BYB |
| , BYN | Valko-Venäjän rupla |
| one, BYN | Valko-Venäjän rupla |
| other, BYN | Valko-Venäjän ruplaa |
| , BYN symbol | BYN |
| narrow, BYN symbol | BYN |
| , BYR | Valko-Venäjän rupla (2000–2016) |
| one, BYR | Valko-Venäjän rupla (2000–2016) |
| other, BYR | Valko-Venäjän ruplaa (2000–2016) |
| , BYR symbol | BYR |
| , BZD | Belizen dollari |
| one, BZD | Belizen dollari |
| other, BZD | Belizen dollaria |
| , BZD symbol | BZD |
| narrow, BZD symbol | BZD |
| , CAD | Kanadan dollari |
| one, CAD | Kanadan dollari |
| other, CAD | Kanadan dollaria |
| , CAD symbol | CAD |
| narrow, CAD symbol | CAD |
| , CDF | Kongon frangi |
| one, CDF | Kongon frangi |
| other, CDF | Kongon frangia |
| , CDF symbol | CDF |
| , CHE | Sveitsin WIR-euro |
| one, CHE | Sveitsin WIR-euro |
| other, CHE | Sveitsin WIR-euroa |
| , CHE symbol | CHE |
| , CHF | Sveitsin frangi |
| one, CHF | Sveitsin frangi |
| other, CHF | Sveitsin frangia |
| , CHF symbol | CHF |
| , CHW | Sveitsin WIR-frangi |
| one, CHW | Sveitsin WIR-frangi |
| other, CHW | Sveitsin WIR-frangia |
| , CHW symbol | CHW |
| , CLE | Chilen escudo |
| one, CLE | Chilen escudo |
| other, CLE | Chilen escudoa |
| , CLE symbol | CLE |
| , CLF | Chilen unidades de fomento |
| one, CLF | Chilen unidades de fomento |
| other, CLF | Chilen unidades de fomentoa |
| , CLF symbol | CLF |
| , CLP | Chilen peso |
| one, CLP | Chilen peso |
| other, CLP | Chilen pesoa |
| , CLP symbol | CLP |
| narrow, CLP symbol | CLP |
| , CNH | Kiinan juan (offshore) |
| one, CNH | Kiinan juan (offshore) |
| other, CNH | Kiinan juania (offshore) |
| , CNH symbol | CNH |
| , CNX | Kiinan kansanpankin dollari |
| one, CNX | Kiinan kansanpankin dollari |
| other, CNX | Kiinan kansanpankin dollaria |
| , CNX symbol | CNX |
| , CNY | Kiinan juan |
| one, CNY | Kiinan juan |
| other, CNY | Kiinan juania |
| , CNY symbol | CNY |
| narrow, CNY symbol | CNY |
| , COP | Kolumbian peso |
| one, COP | Kolumbian peso |
| other, COP | Kolumbian pesoa |
| , COP symbol | COP |
| narrow, COP symbol | COP |
| , COU | Kolumbian unidad de valor real |
| one, COU | Kolumbian unidad de valor real |
| other, COU | Kolumbian unidad de valor realia |
| , COU symbol | COU |
| , CRC | Costa Rican colón |
| one, CRC | Costa Rican colón |
| other, CRC | Costa Rican colónia |
| , CRC symbol | CRC |
| narrow, CRC symbol | CRC |
| , CSD | Serbian dinaari (2002–2006) |
| one, CSD | Serbian dinaari (2002–2006) |
| other, CSD | Serbian dinaaria (2002–2006) |
| , CSD symbol | CSD |
| , CSK | Tšekkoslovakian kova koruna |
| one, CSK | Tšekkoslovakian kova koruna |
| other, CSK | Tšekkoslovakian kovaa korunaa |
| , CSK symbol | CSK |
| , CUC | Kuuban vaihdettava peso |
| one, CUC | Kuuban vaihdettava peso |
| other, CUC | Kuuban vaihdettavaa pesoa |
| , CUC symbol | CUC |
| narrow, CUC symbol | CUC |
| , CUP | Kuuban peso |
| one, CUP | Kuuban peso |
| other, CUP | Kuuban pesoa |
| , CUP symbol | CUP |
| narrow, CUP symbol | CUP |
| , CVE | Kap Verden escudo |
| one, CVE | Kap Verden escudo |
| other, CVE | Kap Verden escudoa |
| , CVE symbol | CVE |
| , CYP | Kyproksen punta |
| one, CYP | Kyproksen punta |
| other, CYP | Kyproksen puntaa |
| , CYP symbol | CYP |
| , CZK | Tšekin koruna |
| one, CZK | Tšekin koruna |
| other, CZK | Tšekin korunaa |
| , CZK symbol | CZK |
| narrow, CZK symbol | CZK |
| , DDM | Itä-Saksan markka |
| one, DDM | Itä-Saksan markka |
| other, DDM | Itä-Saksan markkaa |
| , DDM symbol | DDM |
| , DEM | Saksan markka |
| one, DEM | Saksan markka |
| other, DEM | Saksan markkaa |
| , DEM symbol | DEM |
| , DJF | Djiboutin frangi |
| one, DJF | Djiboutin frangi |
| other, DJF | Djiboutin frangia |
| , DJF symbol | DJF |
| , DKK | Tanskan kruunu |
| one, DKK | Tanskan kruunu |
| other, DKK | Tanskan kruunua |
| , DKK symbol | DKK |
| narrow, DKK symbol | DKK |
| , DOP | Dominikaanisen tasavallan peso |
| one, DOP | Dominikaanisen tasavallan peso |
| other, DOP | Dominikaanisen tasavallan pesoa |
| , DOP symbol | DOP |
| narrow, DOP symbol | DOP |
| , DZD | Algerian dinaari |
| one, DZD | Algerian dinaari |
| other, DZD | Algerian dinaaria |
| , DZD symbol | DZD |
| , ECS | Ecuadorin sucre |
| one, ECS | Ecuadorin sucre |
| other, ECS | Ecuadorin sucrea |
| , ECS symbol | ECS |
| , ECV | Ecuadorin UVC |
| one, ECV | Ecuadorin UVC |
| other, ECV | Ecuadorin UVC’ta |
| , ECV symbol | ECV |
| , EEK | Viron kruunu |
| one, EEK | Viron kruunu |
| other, EEK | Viron kruunua |
| , EEK symbol | EEK |
| , EGP | Egyptin punta |
| one, EGP | Egyptin punta |
| other, EGP | Egyptin puntaa |
| , EGP symbol | EGP |
| narrow, EGP symbol | EGP |
| , ERN | Eritrean nakfa |
| one, ERN | Eritrean nakfa |
| other, ERN | Eritrean nakfaa |
| , ERN symbol | ERN |
| , ESA | Espanjan peseta (A-tili) |
| one, ESA | Espanjan peseta (A-tili) |
| other, ESA | Espanjan pesetaa (A-tili) |
| , ESA symbol | ESA |
| , ESB | Espanjan peseta (vaihdettava tili) |
| one, ESB | Espanjan peseta (vaihdettava tili) |
| other, ESB | Espanjan pesetaa (vaihdettava tili) |
| , ESB symbol | ESB |
| , ESP | Espanjan peseta |
| one, ESP | Espanjan peseta |
| other, ESP | Espanjan pesetaa |
| , ESP symbol | ESP |
| narrow, ESP symbol | ESP |
| , ETB | Etiopian birr |
| one, ETB | Etiopian birr |
| other, ETB | Etiopian birriä |
| , ETB symbol | ETB |
| , EUR | euro |
| one, EUR | euro |
| other, EUR | euroa |
| , EUR symbol | € |
| narrow, EUR symbol | € |
| , FIM | Suomen markka |
| one, FIM | Suomen markka |
| other, FIM | Suomen markkaa |
| , FIM symbol | mk |
| , FJD | Fidžin dollari |
| one, FJD | Fidžin dollari |
| other, FJD | Fidžin dollaria |
| , FJD symbol | FJD |
| narrow, FJD symbol | FJD |
| , FKP | Falklandinsaarten punta |
| one, FKP | Falklandinsaarten punta |
| other, FKP | Falklandinsaarten puntaa |
| , FKP symbol | FKP |
| narrow, FKP symbol | FKP |
| , FRF | Ranskan frangi |
| one, FRF | Ranskan frangi |
| other, FRF | Ranskan frangia |
| , FRF symbol | FRF |
| , GBP | Englannin punta |
| one, GBP | Englannin punta |
| other, GBP | Englannin puntaa |
| , GBP symbol | £ |
| narrow, GBP symbol | £ |
| , GEK | Georgian kuponkilari |
| one, GEK | Georgian kuponkilari |
| other, GEK | Georgian kuponkilaria |
| , GEK symbol | GEK |
| , GEL | Georgian lari |
| one, GEL | Georgian lari |
| other, GEL | Georgian laria |
| , GEL symbol | GEL |
| narrow, GEL symbol | GEL |
| , GHC | Ghanan cedi (1979–2007) |
| one, GHC | Ghanan cedi (1979–2007) |
| other, GHC | Ghanan cediä (1979–2007) |
| , GHC symbol | GHC |
| , GHS | Ghanan cedi |
| one, GHS | Ghanan cedi |
| other, GHS | Ghanan cediä |
| , GHS symbol | GHS |
| , GIP | Gibraltarin punta |
| one, GIP | Gibraltarin punta |
| other, GIP | Gibraltarin puntaa |
| , GIP symbol | GIP |
| narrow, GIP symbol | GIP |
| , GMD | Gambian dalasi |
| one, GMD | Gambian dalasi |
| other, GMD | Gambian dalasia |
| , GMD symbol | GMD |
| , GNF | Guinean frangi |
| one, GNF | Guinean frangi |
| other, GNF | Guinean frangia |
| , GNF symbol | GNF |
| narrow, GNF symbol | GNF |
| , GNS | Guinean syli |
| one, GNS | Guinean syli |
| other, GNS | Guinean syliä |
| , GNS symbol | GNS |
| , GQE | Päiväntasaajan Guinean ekwele |
| one, GQE | Päiväntasaajan Guinean ekwele |
| other, GQE | Päiväntasaajan Guinean ekweleä |
| , GQE symbol | GQE |
| , GRD | Kreikan drakma |
| one, GRD | Kreikan drakma |
| other, GRD | Kreikan drakmaa |
| , GRD symbol | GRD |
| , GTQ | Guatemalan quetzal |
| one, GTQ | Guatemalan quetzal |
| other, GTQ | Guatemalan quetzalia |
| , GTQ symbol | GTQ |
| narrow, GTQ symbol | GTQ |
| , GWE | Portugalin Guinean escudo |
| one, GWE | Portugalin Guinean escudo |
| other, GWE | Portugalin Guinean escudoa |
| , GWE symbol | GWE |
| , GWP | Guinea-Bissaun peso |
| one, GWP | Guinea-Bissaun peso |
| other, GWP | Guinea-Bissaun pesoa |
| , GWP symbol | GWP |
| , GYD | Guyanan dollari |
| one, GYD | Guyanan dollari |
| other, GYD | Guyanan dollaria |
| , GYD symbol | GYD |
| narrow, GYD symbol | GYD |
| , HKD | Hongkongin dollari |
| one, HKD | Hongkongin dollari |
| other, HKD | Hongkongin dollaria |
| , HKD symbol | HKD |
| narrow, HKD symbol | HKD |
| , HNL | Hondurasin lempira |
| one, HNL | Hondurasin lempira |
| other, HNL | Hondurasin lempiraa |
| , HNL symbol | HNL |
| narrow, HNL symbol | HNL |
| , HRD | Kroatian dinaari |
| one, HRD | Kroatian dinaari |
| other, HRD | Kroatian dinaaria |
| , HRD symbol | HRD |
| , HRK | Kroatian kuna |
| one, HRK | Kroatian kuna |
| other, HRK | Kroatian kunaa |
| , HRK symbol | HRK |
| narrow, HRK symbol | HRK |
| , HTG | Haitin gourde |
| one, HTG | Haitin gourde |
| other, HTG | Haitin gourdea |
| , HTG symbol | HTG |
| , HUF | Unkarin forintti |
| one, HUF | Unkarin forintti |
| other, HUF | Unkarin forinttia |
| , HUF symbol | HUF |
| narrow, HUF symbol | HUF |
| , IDR | Indonesian rupia |
| one, IDR | Indonesian rupia |
| other, IDR | Indonesian rupiaa |
| , IDR symbol | IDR |
| narrow, IDR symbol | IDR |
| , IEP | Irlannin punta |
| one, IEP | Irlannin punta |
| other, IEP | Irlannin puntaa |
| , IEP symbol | IEP |
| , ILP | Israelin punta |
| one, ILP | Israelin punta |
| other, ILP | Israelin puntaa |
| , ILP symbol | ILP |
| , ILR | Israelin sekeli (1980–1985) |
| one, ILR | Israelin sekeli (1980–1985) |
| other, ILR | Israelin sekeliä (1980–1985) |
| , ILR symbol | ILR |
| , ILS | Israelin uusi sekeli |
| one, ILS | Israelin uusi sekeli |
| other, ILS | Israelin uutta sekeliä |
| , ILS symbol | ILS |
| narrow, ILS symbol | ILS |
| , INR | Intian rupia |
| one, INR | Intian rupia |
| other, INR | Intian rupiaa |
| , INR symbol | INR |
| narrow, INR symbol | INR |
| , IQD | Irakin dinaari |
| one, IQD | Irakin dinaari |
| other, IQD | Irakin dinaaria |
| , IQD symbol | IQD |
| , IRR | Iranin rial |
| one, IRR | Iranin rial |
| other, IRR | Iranin rialia |
| , IRR symbol | IRR |
| , ISJ | Islannin kruunu (1918–1981) |
| one, ISJ | Islannin kruunu (1918–1981) |
| other, ISJ | Islannin kruunua (1918–1981) |
| , ISJ symbol | ISJ |
| , ISK | Islannin kruunu |
| one, ISK | Islannin kruunu |
| other, ISK | Islannin kruunua |
| , ISK symbol | ISK |
| narrow, ISK symbol | ISK |
| , ITL | Italian liira |
| one, ITL | Italian liira |
| other, ITL | Italian liiraa |
| , ITL symbol | ITL |
| , JMD | Jamaikan dollari |
| one, JMD | Jamaikan dollari |
| other, JMD | Jamaikan dollaria |
| , JMD symbol | JMD |
| narrow, JMD symbol | JMD |
| , JOD | Jordanian dinaari |
| one, JOD | Jordanian dinaari |
| other, JOD | Jordanian dinaaria |
| , JOD symbol | JOD |
| , JPY | Japanin jeni |
| one, JPY | Japanin jeni |
| other, JPY | Japanin jeniä |
| , JPY symbol | ¥ |
| narrow, JPY symbol | ¥ |
| , KES | Kenian šillinki |
| one, KES | Kenian šillinki |
| other, KES | Kenian šillinkiä |
| , KES symbol | KES |
| , KGS | Kirgisian som |
| one, KGS | Kirgisian som |
| other, KGS | Kirgisian somia |
| , KGS symbol | KGS |
| , KHR | Kambodžan riel |
| one, KHR | Kambodžan riel |
| other, KHR | Kambodžan rieliä |
| , KHR symbol | KHR |
| narrow, KHR symbol | KHR |
| , KMF | Komorien frangi |
| one, KMF | Komorien frangi |
| other, KMF | Komorien frangia |
| , KMF symbol | KMF |
| narrow, KMF symbol | KMF |
| , KPW | Pohjois-Korean won |
| one, KPW | Pohjois-Korean won |
| other, KPW | Pohjois-Korean wonia |
| , KPW symbol | KPW |
| narrow, KPW symbol | KPW |
| , KRH | Etelä-Korean hwan (1953–1962) |
| one, KRH | Etelä-Korean hwan (1953–1962) |
| other, KRH | Etelä-Korean hwania (1953–1962) |
| , KRH symbol | KRH |
| , KRO | Etelä-Korean won (1945–1953) |
| one, KRO | Etelä-Korean won (1945–1953) |
| other, KRO | Etelä-Korean wonia (1945–1953) |
| , KRO symbol | KRO |
| , KRW | Etelä-Korean won |
| one, KRW | Etelä-Korean won |
| other, KRW | Etelä-Korean wonia |
| , KRW symbol | KRW |
| narrow, KRW symbol | KRW |
| , KWD | Kuwaitin dinaari |
| one, KWD | Kuwaitin dinaari |
| other, KWD | Kuwaitin dinaaria |
| , KWD symbol | KWD |
| , KYD | Caymansaarten dollari |
| one, KYD | Caymansaarten dollari |
| other, KYD | Caymansaarten dollaria |
| , KYD symbol | KYD |
| narrow, KYD symbol | KYD |
| , KZT | Kazakstanin tenge |
| one, KZT | Kazakstanin tenge |
| other, KZT | Kazakstanin tengeä |
| , KZT symbol | KZT |
| narrow, KZT symbol | KZT |
| , LAK | Laosin kip |
| one, LAK | Laosin kip |
| other, LAK | Laosin kipiä |
| , LAK symbol | LAK |
| narrow, LAK symbol | LAK |
| , LBP | Libanonin punta |
| one, LBP | Libanonin punta |
| other, LBP | Libanonin puntaa |
| , LBP symbol | LBP |
| narrow, LBP symbol | LBP |
| , LKR | Sri Lankan rupia |
| one, LKR | Sri Lankan rupia |
| other, LKR | Sri Lankan rupiaa |
| , LKR symbol | LKR |
| narrow, LKR symbol | LKR |
| , LRD | Liberian dollari |
| one, LRD | Liberian dollari |
| other, LRD | Liberian dollaria |
| , LRD symbol | LRD |
| narrow, LRD symbol | LRD |
| , LSL | Lesothon loti |
| one, LSL | Lesothon loti |
| other, LSL | Lesothon lotia |
| , LSL symbol | LSL |
| , LTL | Liettuan liti |
| one, LTL | Liettuan liti |
| other, LTL | Liettuan litiä |
| , LTL symbol | LTL |
| narrow, LTL symbol | LTL |
| , LTT | Liettuan talonas |
| one, LTT | Liettuan talonas |
| other, LTT | Liettuan talonasia |
| , LTT symbol | LTT |
| , LUC | Luxemburgin vaihdettava frangi |
| one, LUC | Luxemburgin vaihdettava frangi |
| other, LUC | Luxemburgin vaihdettavaa frangia |
| , LUC symbol | LUC |
| , LUF | Luxemburgin frangi |
| one, LUF | Luxemburgin frangi |
| other, LUF | Luxemburgin frangia |
| , LUF symbol | LUF |
| , LUL | Luxemburgin rahoitusfrangi |
| one, LUL | Luxemburgin rahoitusfrangi |
| other, LUL | Luxemburgin rahoitusfrangia |
| , LUL symbol | LUL |
| , LVL | Latvian lati |
| one, LVL | Latvian lati |
| other, LVL | Latvian latia |
| , LVL symbol | LVL |
| narrow, LVL symbol | LVL |
| , LVR | Latvian rupla |
| one, LVR | Latvian rupla |
| other, LVR | Latvian ruplaa |
| , LVR symbol | LVR |
| , LYD | Libyan dinaari |
| one, LYD | Libyan dinaari |
| other, LYD | Libyan dinaaria |
| , LYD symbol | LYD |
| , MAD | Marokon dirhami |
| one, MAD | Marokon dirhami |
| other, MAD | Marokon dirhamia |
| , MAD symbol | MAD |
| , MAF | Marokon frangi |
| one, MAF | Marokon frangi |
| other, MAF | Marokon frangia |
| , MAF symbol | MAF |
| , MCF | Monacon frangi |
| one, MCF | Monacon frangi |
| other, MCF | Monacon frangia |
| , MCF symbol | MCF |
| , MDC | Moldovan kuponkileu |
| one, MDC | Moldovan kuponkileu |
| other, MDC | Moldovan kuponkileuta |
| , MDC symbol | MDC |
| , MDL | Moldovan leu |
| one, MDL | Moldovan leu |
| other, MDL | Moldovan leuta |
| , MDL symbol | MDL |
| , MGA | Madagaskarin ariary |
| one, MGA | Madagaskarin ariary |
| other, MGA | Madagaskarin ariarya |
| , MGA symbol | MGA |
| narrow, MGA symbol | MGA |
| , MGF | Madagaskarin frangi |
| one, MGF | Madagaskarin frangi |
| other, MGF | Madagaskarin frangia |
| , MGF symbol | MGF |
| , MKD | Makedonian denaari |
| one, MKD | Makedonian denaari |
| other, MKD | Makedonian denaaria |
| , MKD symbol | MKD |
| , MKN | Makedonian dinaari (1992–1993) |
| one, MKN | Makedonian dinaari (1992–1993) |
| other, MKN | Makedonian dinaaria (1992–1993) |
| , MKN symbol | MKN |
| , MLF | Malin frangi |
| one, MLF | Malin frangi |
| other, MLF | Malin frangia |
| , MLF symbol | MLF |
| , MMK | Myanmarin kyat |
| one, MMK | Myanmarin kyat |
| other, MMK | Myanmarin kyatia |
| , MMK symbol | MMK |
| narrow, MMK symbol | MMK |
| , MNT | Mongolian tugrik |
| one, MNT | Mongolian tugrik |
| other, MNT | Mongolian tugrikia |
| , MNT symbol | MNT |
| narrow, MNT symbol | MNT |
| , MOP | Macaon pataca |
| one, MOP | Macaon pataca |
| other, MOP | Macaon patacaa |
| , MOP symbol | MOP |
| , MRO | Mauritanian ouguiya |
| one, MRO | Mauritanian ouguiya |
| other, MRO | Mauritanian ouguiyaa |
| , MRO symbol | MRO |
| , MTL | Maltan liira |
| one, MTL | Maltan liira |
| other, MTL | Maltan liiraa |
| , MTL symbol | MTL |
| , MTP | Maltan punta |
| one, MTP | Maltan punta |
| other, MTP | Maltan puntaa |
| , MTP symbol | MTP |
| , MUR | Mauritiuksen rupia |
| one, MUR | Mauritiuksen rupia |
| other, MUR | Mauritiuksen rupiaa |
| , MUR symbol | MUR |
| narrow, MUR symbol | MUR |
| , MVP | Malediivien rupia (1947–1981) |
| one, MVP | Malediivien rupia (1947–1981) |
| other, MVP | Malediivien rupiaa (1947–1981) |
| , MVP symbol | MVP |
| , MVR | Malediivien rufiyaa |
| one, MVR | Malediivien rufiyaa |
| other, MVR | Malediivien rufiyaata |
| , MVR symbol | MVR |
| , MWK | Malawin kwacha |
| one, MWK | Malawin kwacha |
| other, MWK | Malawin kwachaa |
| , MWK symbol | MWK |
| , MXN | Meksikon peso |
| one, MXN | Meksikon peso |
| other, MXN | Meksikon pesoa |
| , MXN symbol | MXN |
| narrow, MXN symbol | MXN |
| , MXP | Meksikon hopeapeso (1861–1992) |
| one, MXP | Meksikon hopeapeso (1861–1992) |
| other, MXP | Meksikon hopeapesoa (1861–1992) |
| , MXP symbol | MXP |
| , MXV | Meksikon UDI |
| one, MXV | Meksikon UDI |
| other, MXV | Meksikon UDI’ta |
| , MXV symbol | MXV |
| , MYR | Malesian ringgit |
| one, MYR | Malesian ringgit |
| other, MYR | Malesian ringgitiä |
| , MYR symbol | MYR |
| narrow, MYR symbol | MYR |
| , MZE | Mosambikin escudo |
| one, MZE | Mosambikin escudo |
| other, MZE | Mosambikin escudoa |
| , MZE symbol | MZE |
| , MZM | Mosambikin metical (1980–2006) |
| one, MZM | Mosambikin metical (1980–2006) |
| other, MZM | Mosambikin meticalia (1980–2006) |
| , MZM symbol | MZM |
| , MZN | Mosambikin metical |
| one, MZN | Mosambikin metical |
| other, MZN | Mosambikin meticalia |
| , MZN symbol | MZN |
| , NAD | Namibian dollari |
| one, NAD | Namibian dollari |
| other, NAD | Namibian dollaria |
| , NAD symbol | NAD |
| narrow, NAD symbol | NAD |
| , NGN | Nigerian naira |
| one, NGN | Nigerian naira |
| other, NGN | Nigerian nairaa |
| , NGN symbol | NGN |
| narrow, NGN symbol | NGN |
| , NIC | Nicaraguan córdoba (1988–1991) |
| one, NIC | Nicaraguan córdoba (1988–1991) |
| other, NIC | Nicaraguan córdobaa (1988–1991) |
| , NIC symbol | NIC |
| , NIO | Nicaraguan córdoba |
| one, NIO | Nicaraguan córdoba |
| other, NIO | Nicaraguan córdobaa |
| , NIO symbol | NIO |
| narrow, NIO symbol | NIO |
| , NLG | Alankomaiden guldeni |
| one, NLG | Alankomaiden guldeni |
| other, NLG | Alankomaiden guldenia |
| , NLG symbol | NLG |
| , NOK | Norjan kruunu |
| one, NOK | Norjan kruunu |
| other, NOK | Norjan kruunua |
| , NOK symbol | NOK |
| narrow, NOK symbol | NOK |
| , NPR | Nepalin rupia |
| one, NPR | Nepalin rupia |
| other, NPR | Nepalin rupiaa |
| , NPR symbol | NPR |
| narrow, NPR symbol | NPR |
| , NZD | Uuden-Seelannin dollari |
| one, NZD | Uuden-Seelannin dollari |
| other, NZD | Uuden-Seelannin dollaria |
| , NZD symbol | NZD |
| narrow, NZD symbol | NZD |
| , OMR | Omanin rial |
| one, OMR | Omanin rial |
| other, OMR | Omanin rialia |
| , OMR symbol | OMR |
| , PAB | Panaman balboa |
| one, PAB | Panaman balboa |
| other, PAB | Panaman balboaa |
| , PAB symbol | PAB |
| , PEI | Perun inti |
| one, PEI | Perun inti |
| other, PEI | Perun intiä |
| , PEI symbol | PEI |
| , PEN | Perun sol |
| one, PEN | Perun sol |
| other, PEN | Perun solia |
| , PEN symbol | PEN |
| , PES | Perun sol (1863–1965) |
| one, PES | Perun sol (1863–1965) |
| other, PES | Perun solia (1863–1965) |
| , PES symbol | PES |
| , PGK | Papua-Uuden-Guinean kina |
| one, PGK | Papua-Uuden-Guinean kina |
| other, PGK | Papua-Uuden-Guinean kinaa |
| , PGK symbol | PGK |
| , PHP | Filippiinien peso |
| one, PHP | Filippiinien peso |
| other, PHP | Filippiinien pesoa |
| , PHP symbol | PHP |
| narrow, PHP symbol | PHP |
| , PKR | Pakistanin rupia |
| one, PKR | Pakistanin rupia |
| other, PKR | Pakistanin rupiaa |
| , PKR symbol | PKR |
| narrow, PKR symbol | PKR |
| , PLN | Puolan złoty |
| one, PLN | Puolan złoty |
| other, PLN | Puolan złotya |
| , PLN symbol | PLN |
| narrow, PLN symbol | PLN |
| , PLZ | Puolan złoty (1950–1995) |
| one, PLZ | Puolan złoty (1950–1995) |
| other, PLZ | Puolan złotya (1950–1995) |
| , PLZ symbol | PLZ |
| , PTE | Portugalin escudo |
| one, PTE | Portugalin escudo |
| other, PTE | Portugalin escudoa |
| , PTE symbol | PTE |
| , PYG | Paraguayn guarani |
| one, PYG | Paraguayn guarani |
| other, PYG | Paraguayn guarania |
| , PYG symbol | PYG |
| narrow, PYG symbol | PYG |
| , QAR | Qatarin rial |
| one, QAR | Qatarin rial |
| other, QAR | Qatarin rialia |
| , QAR symbol | QAR |
| , RHD | Rhodesian dollari |
| one, RHD | Rhodesian dollari |
| other, RHD | Rhodesian dollaria |
| , RHD symbol | RHD |
| , ROL | Romanian leu (1952–2006) |
| one, ROL | Romanian leu (1952–2006) |
| other, ROL | Romanian leuta (1952–2006) |
| , ROL symbol | ROL |
| , RON | Romanian leu |
| one, RON | Romanian leu |
| other, RON | Romanian leuta |
| , RON symbol | RON |
| narrow, RON symbol | RON |
| , RSD | Serbian dinaari |
| one, RSD | Serbian dinaari |
| other, RSD | Serbian dinaaria |
| , RSD symbol | RSD |
| , RUB | Venäjän rupla |
| one, RUB | Venäjän rupla |
| other, RUB | Venäjän ruplaa |
| , RUB symbol | RUB |
| narrow, RUB symbol | ₽ |
| , RUR | Venäjän rupla (1991–1998) |
| one, RUR | Venäjän rupla (1991–1998) |
| other, RUR | Venäjän ruplaa (1991–1998) |
| , RUR symbol | RUR |
| narrow, RUR symbol | RUR |
| , RWF | Ruandan frangi |
| one, RWF | Ruandan frangi |
| other, RWF | Ruandan frangia |
| , RWF symbol | RWF |
| narrow, RWF symbol | RWF |
| , SAR | Saudi-Arabian rial |
| one, SAR | Saudi-Arabian rial |
| other, SAR | Saudi-Arabian rialia |
| , SAR symbol | SAR |
| , SBD | Salomonsaarten dollari |
| one, SBD | Salomonsaarten dollari |
| other, SBD | Salomonsaarten dollaria |
| , SBD symbol | SBD |
| narrow, SBD symbol | SBD |
| , SCR | Seychellien rupia |
| one, SCR | Seychellien rupia |
| other, SCR | Seychellien rupiaa |
| , SCR symbol | SCR |
| , SDD | Sudanin dinaari (1992–2007) |
| one, SDD | Sudanin dinaari (1992–2007) |
| other, SDD | Sudanin dinaaria (1992–2007) |
| , SDD symbol | SDD |
| , SDG | Sudanin punta |
| one, SDG | Sudanin punta |
| other, SDG | Sudanin puntaa |
| , SDG symbol | SDG |
| , SDP | Sudanin punta (1957–1998) |
| one, SDP | Sudanin punta (1957–1998) |
| other, SDP | Sudanin puntaa (1957–1998) |
| , SDP symbol | SDP |
| , SEK | Ruotsin kruunu |
| one, SEK | Ruotsin kruunu |
| other, SEK | Ruotsin kruunua |
| , SEK symbol | SEK |
| narrow, SEK symbol | SEK |
| , SGD | Singaporen dollari |
| one, SGD | Singaporen dollari |
| other, SGD | Singaporen dollaria |
| , SGD symbol | SGD |
| narrow, SGD symbol | SGD |
| , SHP | Saint Helenan punta |
| one, SHP | Saint Helenan punta |
| other, SHP | Saint Helenan puntaa |
| , SHP symbol | SHP |
| narrow, SHP symbol | SHP |
| , SIT | Slovenian tolar |
| one, SIT | Slovenian tolar |
| other, SIT | Slovenian tolaria |
| , SIT symbol | SIT |
| , SKK | Slovakian koruna |
| one, SKK | Slovakian koruna |
| other, SKK | Slovakian korunaa |
| , SKK symbol | SKK |
| , SLL | Sierra Leonen leone |
| one, SLL | Sierra Leonen leone |
| other, SLL | Sierra Leonen leonea |
| , SLL symbol | SLL |
| , SOS | Somalian šillinki |
| one, SOS | Somalian šillinki |
| other, SOS | Somalian šillinkiä |
| , SOS symbol | SOS |
| , SRD | Surinamen dollari |
| one, SRD | Surinamen dollari |
| other, SRD | Surinamen dollaria |
| , SRD symbol | SRD |
| narrow, SRD symbol | SRD |
| , SRG | Surinamen guldeni |
| one, SRG | Surinamen guldeni |
| other, SRG | Surinamen guldeni |
| , SRG symbol | SRG |
| , SSP | Etelä-Sudanin punta |
| one, SSP | Etelä-Sudanin punta |
| other, SSP | Etelä-Sudanin puntaa |
| , SSP symbol | SSP |
| narrow, SSP symbol | SSP |
| , STD | São Tomén ja Príncipen dobra (1977–2017) |
| one, STD | São Tomén ja Príncipen dobra (1977–2017) |
| other, STD | São Tomén ja Príncipen dobraa (1977–2017) |
| , STD symbol | STD |
| , STN | São Tomén ja Príncipen dobra |
| one, STN | São Tomén ja Príncipen dobra |
| other, STN | São Tomén ja Príncipen dobraa |
| , STN symbol | STN |
| narrow, STN symbol | STD |
| , SUR | Neuvostoliiton rupla |
| one, SUR | Neuvostoliiton rupla |
| other, SUR | Neuvostoliiton ruplaa |
| , SUR symbol | SUR |
| , SVC | El Salvadorin colón |
| one, SVC | El Salvadorin colón |
| other, SVC | El Salvadorin colónia |
| , SVC symbol | SVC |
| , SYP | Syyrian punta |
| one, SYP | Syyrian punta |
| other, SYP | Syyrian puntaa |
| , SYP symbol | SYP |
| narrow, SYP symbol | SYP |
| , SZL | Swazimaan lilangeni |
| one, SZL | Swazimaan lilangeni |
| other, SZL | Swazimaan lilangenia |
| , SZL symbol | SZL |
| , THB | Thaimaan baht |
| one, THB | Thaimaan baht |
| other, THB | Thaimaan bahtia |
| , THB symbol | THB |
| narrow, THB symbol | THB |
| , TJR | Tadžikistanin rupla |
| one, TJR | Tadžikistanin rupla |
| other, TJR | Tadžikistanin ruplaa |
| , TJR symbol | TJR |
| , TJS | Tadžikistanin somoni |
| one, TJS | Tadžikistanin somoni |
| other, TJS | Tadžikistanin somonia |
| , TJS symbol | TJS |
| , TMM | Turkmenistanin manat (1993–2009) |
| one, TMM | Turkmenistanin manat (1993–2009) |
| other, TMM | Turkmenistanin manatia (1993–2009) |
| , TMM symbol | TMM |
| , TMT | Turkmenistanin manat |
| one, TMT | Turkmenistanin manat |
| other, TMT | Turkmenistanin manatia |
| , TMT symbol | TMT |
| , TND | Tunisian dinaari |
| one, TND | Tunisian dinaari |
| other, TND | Tunisian dinaaria |
| , TND symbol | TND |
| , TOP | Tongan pa’anga |
| one, TOP | Tongan pa’anga |
| other, TOP | Tongan pa’angaa |
| , TOP symbol | TOP |
| narrow, TOP symbol | TOP |
| , TPE | Timorin escudo |
| one, TPE | Timorin escudo |
| other, TPE | Timorin escudoa |
| , TPE symbol | TPE |
| , TRL | Turkin liira (1922–2005) |
| one, TRL | Turkin liira (1922–2005) |
| other, TRL | Turkin liiraa (1922–2005) |
| , TRL symbol | TRL |
| , TRY | Turkin liira |
| one, TRY | Turkin liira |
| other, TRY | Turkin liiraa |
| , TRY symbol | TRY |
| narrow, TRY symbol | TRY |
| variant, TRY symbol | TL |
| , TTD | Trinidadin ja Tobagon dollari |
| one, TTD | Trinidadin ja Tobagon dollari |
| other, TTD | Trinidadin ja Tobagon dollaria |
| , TTD symbol | TTD |
| narrow, TTD symbol | TTD |
| , TWD | Taiwanin uusi dollari |
| one, TWD | Taiwanin uusi dollari |
| other, TWD | Taiwanin uutta dollaria |
| , TWD symbol | TWD |
| narrow, TWD symbol | TWD |
| , TZS | Tansanian šillinki |
| one, TZS | Tansanian šillinki |
| other, TZS | Tansanian šillinkiä |
| , TZS symbol | TZS |
| , UAH | Ukrainan hryvnia |
| one, UAH | Ukrainan hryvnia |
| other, UAH | Ukrainan hryvniaa |
| , UAH symbol | UAH |
| narrow, UAH symbol | UAH |
| , UAK | Ukrainan karbovanetz |
| one, UAK | Ukrainan karbovanetz |
| other, UAK | Ukrainan karbovanetzia |
| , UAK symbol | UAK |
| , UGS | Ugandan šillinki (1966–1987) |
| one, UGS | Ugandan šillinki (1966–1987) |
| other, UGS | Ugandan šillinkiä (1966–1987) |
| , UGS symbol | UGS |
| , UGX | Ugandan šillinki |
| one, UGX | Ugandan šillinki |
| other, UGX | Ugandan šillinkiä |
| , UGX symbol | UGX |
| , USD | Yhdysvaltain dollari |
| one, USD | Yhdysvaltain dollari |
| other, USD | Yhdysvaltain dollaria |
| , USD symbol | $ |
| narrow, USD symbol | $ |
| , USN | Yhdysvaltain dollari (seuraava päivä) |
| one, USN | Yhdysvaltain dollari (seuraava päivä) |
| other, USN | Yhdysvaltain dollaria (seuraava päivä) |
| , USN symbol | USN |
| , USS | Yhdysvaltain dollari (sama päivä) |
| one, USS | Yhdysvaltain dollari (sama päivä) |
| other, USS | Yhdysvaltain dollaria (sama päivä) |
| , USS symbol | USS |
| , UYI | Uruguayn peso en unidades indexadas |
| one, UYI | Uruguayn peso en unidades indexadas |
| other, UYI | Uruguayn pesoa en unidades indexadas |
| , UYI symbol | UYI |
| , UYP | Uruguayn peso (1975–1993) |
| one, UYP | Uruguayn peso (1975–1993) |
| other, UYP | Uruguayn pesoa (1975–1993) |
| , UYP symbol | UYP |
| , UYU | Uruguayn peso |
| one, UYU | Uruguayn peso |
| other, UYU | Uruguayn pesoa |
| , UYU symbol | UYU |
| narrow, UYU symbol | UYU |
| , UZS | Uzbekistanin som |
| one, UZS | Uzbekistanin som |
| other, UZS | Uzbekistanin somia |
| , UZS symbol | UZS |
| , VEB | Venezuelan bolivar (1871–2008) |
| one, VEB | Venezuelan bolivar (1871–2008) |
| other, VEB | Venezuelan bolivaria (1871–2008) |
| , VEB symbol | VEB |
| , VEF | Venezuelan bolivar |
| one, VEF | Venezuelan bolivar |
| other, VEF | Venezuelan bolivaria |
| , VEF symbol | VEF |
| narrow, VEF symbol | VEF |
| , VND | Vietnamin dong |
| one, VND | Vietnamin dong |
| other, VND | Vietnamin dongia |
| , VND symbol | VND |
| narrow, VND symbol | VND |
| , VNN | Vietnamin dong (1978–1985) |
| one, VNN | Vietnamin dong (1978–1985) |
| other, VNN | Vietnamin dongia (1978–1985) |
| , VNN symbol | VNN |
| , VUV | Vanuatun vatu |
| one, VUV | Vanuatun vatu |
| other, VUV | Vanuatun vatua |
| , VUV symbol | VUV |
| , WST | Samoan tala |
| one, WST | Samoan tala |
| other, WST | Samoan talaa |
| , WST symbol | WST |
| , XAF | CFA-frangi BEAC |
| one, XAF | CFA-frangi BEAC |
| other, XAF | CFA-frangia BEAC |
| , XAF symbol | FCFA |
| , XAG | hopea |
| one, XAG | troy-unssi hopeaa |
| other, XAG | troy-unssia hopeaa |
| , XAG symbol | XAG |
| , XAU | kulta |
| one, XAU | troy-unssi kultaa |
| other, XAU | troy-unssia kultaa |
| , XAU symbol | XAU |
| , XBA | EURCO |
| one, XBA | EURCO |
| other, XBA | EURCO’a |
| , XBA symbol | XBA |
| , XBB | Euroopan rahayksikkö (EMU) |
| one, XBB | Euroopan rahayksikkö (EMU) |
| other, XBB | Euroopan rahayksikköä (EMU) |
| , XBB symbol | XBB |
| , XBC | EUA (XBC) |
| one, XBC | EUA (XBC) |
| other, XBC | EUA’ta (XBC) |
| , XBC symbol | XBC |
| , XBD | EUA (XBD) |
| one, XBD | EUA (XBD) |
| other, XBD | EUA’ta (XBD) |
| , XBD symbol | XBD |
| , XCD | Itä-Karibian dollari |
| one, XCD | Itä-Karibian dollari |
| other, XCD | Itä-Karibian dollaria |
| , XCD symbol | XCD |
| narrow, XCD symbol | XCD |
| , XDR | erityisnosto-oikeus (SDR) |
| one, XDR | erityisnosto-oikeus (SDR) |
| other, XDR | erityisnosto-oikeutta (SDR) |
| , XDR symbol | XDR |
| , XEU | Euroopan valuuttayksikkö (ECU) |
| one, XEU | Euroopan valuuttayksikkö (ECU) |
| other, XEU | Euroopan valuuttayksikköä (ECU) |
| , XEU symbol | XEU |
| , XFO | Ranskan kultafrangi |
| one, XFO | Ranskan kultafrangi |
| other, XFO | Ranskan kultafrangia |
| , XFO symbol | XFO |
| , XFU | Ranskan UIC-frangi |
| one, XFU | Ranskan UIC-frangi |
| other, XFU | Ranskan UIC-frangia |
| , XFU symbol | XFU |
| , XOF | CFA-frangi BCEAO |
| one, XOF | CFA-frangi BCEAO |
| other, XOF | CFA-frangia BCEAO |
| , XOF symbol | CFA |
| , XPD | palladium |
| one, XPD | troy-unssi palladiumia |
| other, XPD | troy-unssia palladiumia |
| , XPD symbol | XPD |
| , XPF | CFP-frangi |
| one, XPF | CFP-frangi |
| other, XPF | CFP-frangia |
| , XPF symbol | XPF |
| , XPT | platina |
| one, XPT | troy-unssi platinaa |
| other, XPT | troy-unssia platinaa |
| , XPT symbol | XPT |
| , XRE | RINET-rahastot |
| one, XRE | RINET-rahastoyksikkö |
| other, XRE | RINET-rahastoyksikköä |
| , XRE symbol | XRE |
| , XSU | etelä-amerikkalaisen ALBA:n laskentayksikkö sucre |
| one, XSU | sucre |
| other, XSU | sucrea |
| , XSU symbol | XSU |
| , XTS | testaustarkoitukseen varattu valuuttakoodi |
| one, XTS | testaustarkoitukseen varattu valuuttakoodi |
| other, XTS | testaustarkoitukseen varattua valuuttakoodia |
| , XTS symbol | XTS |
| , XUA | afrikkalainen AfDB-laskentayksikkö |
| one, XUA | AfDB-laskentayksikkö |
| other, XUA | AfDB-laskentayksikköä |
| , XUA symbol | XUA |
| , XXX | tuntematon rahayksikkö |
| one, XXX | tuntematon rahayksikkö |
| other, XXX | tuntematonta rahayksikköä |
| , XXX symbol | XXX |
| , YDD | Jemenin dinaari |
| one, YDD | Jemenin dinaari |
| other, YDD | Jemenin dinaaria |
| , YDD symbol | YDD |
| , YER | Jemenin rial |
| one, YER | Jemenin rial |
| other, YER | Jemenin rialia |
| , YER symbol | YER |
| , YUD | Jugoslavian kova dinaari (1966–1990) |
| one, YUD | Jugoslavian kova dinaari (1966–1990) |
| other, YUD | Jugoslavian kovaa dinaaria (1966–1990) |
| , YUD symbol | YUD |
| , YUM | Jugoslavian uusi dinaari (1994–2002) |
| one, YUM | Jugoslavian uusi dinaari (1994–2002) |
| other, YUM | Jugoslavian uutta dinaaria (1994–2002) |
| , YUM symbol | YUM |
| , YUN | Jugoslavian vaihdettava dinaari (1990–1992) |
| one, YUN | Jugoslavian vaihdettava dinaari (1990–1992) |
| other, YUN | Jugoslavian vaihdettavaa dinaaria (1990–1992) |
| , YUN symbol | YUN |
| , YUR | Jugoslavian uudistettu dinaari (1992–1993) |
| one, YUR | Jugoslavian uudistettu dinaari (1992–1993) |
| other, YUR | Jugoslavian uudistettua dinaaria (1992–1993) |
| , YUR symbol | YUR |
| , ZAL | Etelä-Afrikan rahoitusrandi |
| one, ZAL | Etelä-Afrikan rahoitusrandi |
| other, ZAL | Etelä-Afrikan rahoitusrandia |
| , ZAL symbol | ZAL |
| , ZAR | Etelä-Afrikan randi |
| one, ZAR | Etelä-Afrikan randi |
| other, ZAR | Etelä-Afrikan randia |
| , ZAR symbol | ZAR |
| narrow, ZAR symbol | ZAR |
| , ZMK | Sambian kwacha (1968–2012) |
| one, ZMK | Sambian kwacha (1968–2012) |
| other, ZMK | Sambian kwachaa (1968–2012) |
| , ZMK symbol | ZMK |
| , ZMW | Sambian kwacha |
| one, ZMW | Sambian kwacha |
| other, ZMW | Sambian kwachaa |
| , ZMW symbol | ZMW |
| narrow, ZMW symbol | ZMW |
| , ZRN | Zairen uusi zaire (1993–1998) |
| one, ZRN | Zairen uusi zaire (1993–1998) |
| other, ZRN | Zairen uutta zairea (1993–1998) |
| , ZRN symbol | ZRN |
| , ZRZ | Zairen zaire (1971–1993) |
| one, ZRZ | Zairen zaire (1971–1993) |
| other, ZRZ | Zairen zairea (1971–1993) |
| , ZRZ symbol | ZRZ |
| , ZWD | Zimbabwen dollari (1980–2008) |
| one, ZWD | Zimbabwen dollari (1980–2008) |
| other, ZWD | Zimbabwen dollaria (1980–2008) |
| , ZWD symbol | ZWD |
| , ZWL | Zimbabwen dollari (2009) |
| one, ZWL | Zimbabwen dollari (2009) |
| other, ZWL | Zimbabwen dollaria (2009) |
| , ZWL symbol | ZWL |
| , ZWR | Zimbabwen dollari (2008) |
| one, ZWR | Zimbabwen dollari (2008) |
| other, ZWR | Zimbabwen dollaria (2008) |
| , ZWR symbol | ZWR |

Other stuff:

| atLeast,  | `vähintään {0}` |
| range,  | `{0}–{1}` |

Examples:

| one example | {0} päivä |
| other example | {0} päivää |
Käänny {0}. risteyksestä oikealle.

## Units

| Code | Name |
| ---- | ---- |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
| , acceleration-g-force | G-voimat |
| one, acceleration-g-force | {0} G-voima |
| other, acceleration-g-force | {0} G-voimaa |
| acceleration-meter-per-second-squared | ... |
| , acceleration-meter-per-second-squared | metrit per sekunti toiseen |
| one, acceleration-meter-per-second-squared | {0} metri per sekunti toiseen |
| other, acceleration-meter-per-second-squared | {0} metriä per sekunti toiseen |
| angle-revolution | ... |
| , angle-revolution | kierros |
| one, angle-revolution | {0} kierros |
| other, angle-revolution | {0} kierrosta |
| angle-radian | ... |
| , angle-radian | radiaanit |
| one, angle-radian | {0} radiaani |
| other, angle-radian | {0} radiaania |
| angle-degree | ... |
| , angle-degree | asteet |
| one, angle-degree | {0} aste |
| other, angle-degree | {0} astetta |
| angle-arc-minute | ... |
| , angle-arc-minute | kulmaminuutit |
| one, angle-arc-minute | {0} kulmaminuutti |
| other, angle-arc-minute | {0} kulmaminuuttia |
| angle-arc-second | ... |
| , angle-arc-second | kulmasekunnit |
| one, angle-arc-second | {0} kulmasekunti |
| other, angle-arc-second | {0} kulmasekuntia |
| area-square-kilometer | ... |
| , area-square-kilometer | neliökilometrit |
| one, area-square-kilometer | {0} neliökilometri |
| other, area-square-kilometer | {0} neliökilometriä |
| per units of area-square-kilometer | {0} / neliökilometri |
| area-hectare | ... |
| , area-hectare | hehtaarit |
| one, area-hectare | {0} hehtaari |
| other, area-hectare | {0} hehtaaria |
| area-square-meter | ... |
| , area-square-meter | neliömetrit |
| one, area-square-meter | {0} neliömetri |
| other, area-square-meter | {0} neliömetriä |
| per units of area-square-meter | {0} / neliömetri |
| area-square-centimeter | ... |
| , area-square-centimeter | neliösenttimetrit |
| one, area-square-centimeter | {0} neliösenttimetri |
| other, area-square-centimeter | {0} neliösenttimetriä |
| per units of area-square-centimeter | {0} / neliösenttimetri |
| area-square-mile | ... |
| , area-square-mile | neliömailit |
| one, area-square-mile | {0} neliömaili |
| other, area-square-mile | {0} neliömailia |
| per units of area-square-mile | {0} / neliömaili |
| area-acre | ... |
| , area-acre | eekkerit |
| one, area-acre | {0} eekkeri |
| other, area-acre | {0} eekkeriä |
| area-square-yard | ... |
| , area-square-yard | neliöjaardit |
| one, area-square-yard | {0} neliöjaardi |
| other, area-square-yard | {0} neliöjaardia |
| area-square-foot | ... |
| , area-square-foot | neliöjalat |
| one, area-square-foot | {0} neliöjalka |
| other, area-square-foot | {0} neliöjalkaa |
| area-square-inch | ... |
| , area-square-inch | neliötuumat |
| one, area-square-inch | {0} neliötuuma |
| other, area-square-inch | {0} neliötuumaa |
| per units of area-square-inch | {0} / neliötuuma |
| concentr-karat | ... |
| , concentr-karat | karaatit |
| one, concentr-karat | {0} karaatti |
| other, concentr-karat | {0} karaattia |
| concentr-milligram-per-deciliter | ... |
| , concentr-milligram-per-deciliter | mg/dl |
| one, concentr-milligram-per-deciliter | {0} mg/dl |
| other, concentr-milligram-per-deciliter | {0} mg/dl |
| concentr-millimole-per-liter | ... |
| , concentr-millimole-per-liter | mmol/l |
| one, concentr-millimole-per-liter | {0} mmol/l |
| other, concentr-millimole-per-liter | {0} mmol/l |
| concentr-part-per-million | ... |
| , concentr-part-per-million | ppm |
| one, concentr-part-per-million | {0} ppm |
| other, concentr-part-per-million | {0} ppm |
| consumption-liter-per-kilometer | ... |
| , consumption-liter-per-kilometer | litrat / kilometri |
| one, consumption-liter-per-kilometer | {0} litra / kilometri |
| other, consumption-liter-per-kilometer | {0} litraa / kilometri |
| consumption-liter-per-100kilometers | ... |
| , consumption-liter-per-100kilometers | litrat / 100 kilometriä |
| one, consumption-liter-per-100kilometers | {0} litra / 100 km |
| other, consumption-liter-per-100kilometers | {0} litraa / 100 km |
| consumption-mile-per-gallon | ... |
| , consumption-mile-per-gallon | mailit / am. gallona |
| one, consumption-mile-per-gallon | {0} maili / am. gallona |
| other, consumption-mile-per-gallon | {0} mailia / am. gallona |
| consumption-mile-per-gallon-imperial | ... |
| , consumption-mile-per-gallon-imperial | mailit / br. gallona |
| one, consumption-mile-per-gallon-imperial | {0} maili / br. gallona |
| other, consumption-mile-per-gallon-imperial | {0} mailia / br. gallona |
| digital-terabyte | ... |
| , digital-terabyte | teratavut |
| one, digital-terabyte | {0} teratavu |
| other, digital-terabyte | {0} teratavua |
| digital-terabit | ... |
| , digital-terabit | terabitit |
| one, digital-terabit | {0} terabitti |
| other, digital-terabit | {0} terabittiä |
| digital-gigabyte | ... |
| , digital-gigabyte | gigatavut |
| one, digital-gigabyte | {0} gigatavu |
| other, digital-gigabyte | {0} gigatavua |
| digital-gigabit | ... |
| , digital-gigabit | gigabitit |
| one, digital-gigabit | {0} gigabitti |
| other, digital-gigabit | {0} gigabittiä |
| digital-megabyte | ... |
| , digital-megabyte | megatavut |
| one, digital-megabyte | {0} megatavu |
| other, digital-megabyte | {0} megatavua |
| digital-megabit | ... |
| , digital-megabit | megabitit |
| one, digital-megabit | {0} megabitti |
| other, digital-megabit | {0} megabittiä |
| digital-kilobyte | ... |
| , digital-kilobyte | kilotavut |
| one, digital-kilobyte | {0} kilotavu |
| other, digital-kilobyte | {0} kilotavua |
| digital-kilobit | ... |
| , digital-kilobit | kilobitit |
| one, digital-kilobit | {0} kilobitti |
| other, digital-kilobit | {0} kilobittiä |
| digital-byte | ... |
| , digital-byte | tavut |
| one, digital-byte | {0} tavu |
| other, digital-byte | {0} tavua |
| digital-bit | ... |
| , digital-bit | bitit |
| one, digital-bit | {0} bitti |
| other, digital-bit | {0} bittiä |
| duration-century | ... |
| , duration-century | vuosisadat |
| one, duration-century | {0} vuosisata |
| other, duration-century | {0} vuosisataa |
| duration-year | ... |
| , duration-year | vuodet |
| one, duration-year | {0} vuosi |
| other, duration-year | {0} vuotta |
| per units of duration-year | {0} / vuosi |
| duration-month | ... |
| , duration-month | kuukaudet |
| one, duration-month | {0} kuukausi |
| other, duration-month | {0} kuukautta |
| per units of duration-month | {0} / kuukausi |
| duration-week | ... |
| , duration-week | viikot |
| one, duration-week | {0} viikko |
| other, duration-week | {0} viikkoa |
| per units of duration-week | {0} / viikko |
| duration-day | ... |
| , duration-day | päivät |
| one, duration-day | {0} päivä |
| other, duration-day | {0} päivää |
| per units of duration-day | {0} / päivä |
| duration-hour | ... |
| , duration-hour | tunnit |
| one, duration-hour | {0} tunti |
| other, duration-hour | {0} tuntia |
| per units of duration-hour | {0} / tunti |
| duration-minute | ... |
| , duration-minute | minuutit |
| one, duration-minute | {0} minuutti |
| other, duration-minute | {0} minuuttia |
| per units of duration-minute | {0} / minuutti |
| duration-second | ... |
| , duration-second | sekunnit |
| one, duration-second | {0} sekunti |
| other, duration-second | {0} sekuntia |
| per units of duration-second | {0} / sekunti |
| duration-millisecond | ... |
| , duration-millisecond | millisekunnit |
| one, duration-millisecond | {0} millisekunti |
| other, duration-millisecond | {0} millisekuntia |
| duration-microsecond | ... |
| , duration-microsecond | mikrosekunnit |
| one, duration-microsecond | {0} mikrosekunti |
| other, duration-microsecond | {0} mikrosekuntia |
| duration-nanosecond | ... |
| , duration-nanosecond | nanosekunnit |
| one, duration-nanosecond | {0} nanosekunti |
| other, duration-nanosecond | {0} nanosekuntia |
| electric-ampere | ... |
| , electric-ampere | ampeerit |
| one, electric-ampere | {0} ampeeri |
| other, electric-ampere | {0} ampeeria |
| electric-milliampere | ... |
| , electric-milliampere | milliampeerit |
| one, electric-milliampere | {0} milliampeeri |
| other, electric-milliampere | {0} milliampeeria |
| electric-ohm | ... |
| , electric-ohm | ohmit |
| one, electric-ohm | {0} ohmi |
| other, electric-ohm | {0} ohmia |
| electric-volt | ... |
| , electric-volt | voltit |
| one, electric-volt | {0} voltti |
| other, electric-volt | {0} volttia |
| energy-kilocalorie | ... |
| , energy-kilocalorie | kilokalorit |
| one, energy-kilocalorie | {0} kilokalori |
| other, energy-kilocalorie | {0} kilokaloria |
| energy-calorie | ... |
| , energy-calorie | kalorit |
| one, energy-calorie | {0} kalori |
| other, energy-calorie | {0} kaloria |
| energy-foodcalorie | ... |
| , energy-foodcalorie | kilokalorit |
| one, energy-foodcalorie | {0} kilokalori |
| other, energy-foodcalorie | {0} kilokaloria |
| energy-kilojoule | ... |
| , energy-kilojoule | kilojoulet |
| one, energy-kilojoule | {0} kilojoule |
| other, energy-kilojoule | {0} kilojoulea |
| energy-joule | ... |
| , energy-joule | joulet |
| one, energy-joule | {0} joule |
| other, energy-joule | {0} joulea |
| energy-kilowatt-hour | ... |
| , energy-kilowatt-hour | kilowattitunnit |
| one, energy-kilowatt-hour | {0} kilowattitunti |
| other, energy-kilowatt-hour | {0} kilowattituntia |
| frequency-gigahertz | ... |
| , frequency-gigahertz | gigahertsit |
| one, frequency-gigahertz | {0} gigahertsi |
| other, frequency-gigahertz | {0} gigahertsiä |
| frequency-megahertz | ... |
| , frequency-megahertz | megahertsit |
| one, frequency-megahertz | {0} megahertsi |
| other, frequency-megahertz | {0} megahertsiä |
| frequency-kilohertz | ... |
| , frequency-kilohertz | kilohertsit |
| one, frequency-kilohertz | {0} kilohertsi |
| other, frequency-kilohertz | {0} kilohertsiä |
| frequency-hertz | ... |
| , frequency-hertz | hertsit |
| one, frequency-hertz | {0} hertsi |
| other, frequency-hertz | {0} hertsiä |
| length-kilometer | ... |
| , length-kilometer | kilometrit |
| one, length-kilometer | {0} kilometri |
| other, length-kilometer | {0} kilometriä |
| per units of length-kilometer | {0} / kilometri |
| length-meter | ... |
| , length-meter | metrit |
| one, length-meter | {0} metri |
| other, length-meter | {0} metriä |
| per units of length-meter | {0} / metri |
| length-decimeter | ... |
| , length-decimeter | desimetrit |
| one, length-decimeter | {0} desimetri |
| other, length-decimeter | {0} desimetriä |
| length-centimeter | ... |
| , length-centimeter | senttimetrit |
| one, length-centimeter | {0} senttimetri |
| other, length-centimeter | {0} senttimetriä |
| per units of length-centimeter | {0} / senttimetri |
| length-millimeter | ... |
| , length-millimeter | millimetrit |
| one, length-millimeter | {0} millimetri |
| other, length-millimeter | {0} millimetriä |
| length-micrometer | ... |
| , length-micrometer | mikrometrit |
| one, length-micrometer | {0} mikrometri |
| other, length-micrometer | {0} mikrometriä |
| length-nanometer | ... |
| , length-nanometer | nanometrit |
| one, length-nanometer | {0} nanometri |
| other, length-nanometer | {0} nanometriä |
| length-picometer | ... |
| , length-picometer | pikometrit |
| one, length-picometer | {0} pikometri |
| other, length-picometer | {0} pikometriä |
| length-mile | ... |
| , length-mile | mailit |
| one, length-mile | {0} maili |
| other, length-mile | {0} mailia |
| length-yard | ... |
| , length-yard | jaardit |
| one, length-yard | {0} jaardi |
| other, length-yard | {0} jaardia |
| length-foot | ... |
| , length-foot | jalat |
| one, length-foot | {0} jalka |
| other, length-foot | {0} jalkaa |
| per units of length-foot | {0} / jalka |
| length-inch | ... |
| , length-inch | tuumat |
| one, length-inch | {0} tuuma |
| other, length-inch | {0} tuumaa |
| per units of length-inch | {0} / tuuma |
| length-parsec | ... |
| , length-parsec | parsekit |
| one, length-parsec | {0} parsek |
| other, length-parsec | {0} parsekia |
| length-light-year | ... |
| , length-light-year | valovuodet |
| one, length-light-year | {0} valovuosi |
| other, length-light-year | {0} valovuotta |
| length-astronomical-unit | ... |
| , length-astronomical-unit | astronomiset yksiköt |
| one, length-astronomical-unit | {0} astronominen yksikkö |
| other, length-astronomical-unit | {0} astronomista yksikköä |
| length-furlong | ... |
| , length-furlong | furlongit |
| one, length-furlong | {0} furlong |
| other, length-furlong | {0} furlongia |
| length-fathom | ... |
| , length-fathom | sylet |
| one, length-fathom | {0} syli |
| other, length-fathom | {0} syltä |
| length-nautical-mile | ... |
| , length-nautical-mile | meripeninkulmat |
| one, length-nautical-mile | {0} meripeninkulma |
| other, length-nautical-mile | {0} meripeninkulmaa |
| length-mile-scandinavian | ... |
| , length-mile-scandinavian | peninkulmat |
| one, length-mile-scandinavian | {0} peninkulma |
| other, length-mile-scandinavian | {0} peninkulmaa |
| length-point | ... |
| , length-point | pt |
| one, length-point | {0} pt |
| other, length-point | {0} pt |
| light-lux | ... |
| , light-lux | luksit |
| one, light-lux | {0} luksi |
| other, light-lux | {0} luksia |
| mass-metric-ton | ... |
| , mass-metric-ton | tonnit |
| one, mass-metric-ton | {0} tonni |
| other, mass-metric-ton | {0} tonnia |
| mass-kilogram | ... |
| , mass-kilogram | kilogrammat |
| one, mass-kilogram | {0} kilogramma |
| other, mass-kilogram | {0} kilogrammaa |
| per units of mass-kilogram | {0} / kilogramma |
| mass-gram | ... |
| , mass-gram | grammat |
| one, mass-gram | {0} gramma |
| other, mass-gram | {0} grammaa |
| per units of mass-gram | {0} / gramma |
| mass-milligram | ... |
| , mass-milligram | milligrammat |
| one, mass-milligram | {0} milligramma |
| other, mass-milligram | {0} milligrammaa |
| mass-microgram | ... |
| , mass-microgram | mikrogrammat |
| one, mass-microgram | {0} mikrogramma |
| other, mass-microgram | {0} mikrogrammaa |
| mass-ton | ... |
| , mass-ton | am. tonnit |
| one, mass-ton | {0} am. tonni |
| other, mass-ton | {0} am. tonnia |
| mass-stone | ... |
| , mass-stone | stonet |
| one, mass-stone | {0} stone |
| other, mass-stone | {0} stonea |
| mass-pound | ... |
| , mass-pound | paunat |
| one, mass-pound | {0} pauna |
| other, mass-pound | {0} paunaa |
| per units of mass-pound | {0} / pauna |
| mass-ounce | ... |
| , mass-ounce | unssit |
| one, mass-ounce | {0} unssi |
| other, mass-ounce | {0} unssia |
| per units of mass-ounce | {0} / unssi |
| mass-ounce-troy | ... |
| , mass-ounce-troy | troy-unssit |
| one, mass-ounce-troy | {0} troy-unssi |
| other, mass-ounce-troy | {0} troy-unssia |
| mass-carat | ... |
| , mass-carat | karaatit |
| one, mass-carat | {0} karaatti |
| other, mass-carat | {0} karaattia |
| power-gigawatt | ... |
| , power-gigawatt | gigawatit |
| one, power-gigawatt | {0} gigawatti |
| other, power-gigawatt | {0} gigawattia |
| power-megawatt | ... |
| , power-megawatt | megawatit |
| one, power-megawatt | {0} megawatti |
| other, power-megawatt | {0} megawattia |
| power-kilowatt | ... |
| , power-kilowatt | kilowatit |
| one, power-kilowatt | {0} kilowatti |
| other, power-kilowatt | {0} kilowattia |
| power-watt | ... |
| , power-watt | watit |
| one, power-watt | {0} watti |
| other, power-watt | {0} wattia |
| power-milliwatt | ... |
| , power-milliwatt | milliwatit |
| one, power-milliwatt | {0} milliwatti |
| other, power-milliwatt | {0} milliwattia |
| power-horsepower | ... |
| , power-horsepower | hevosvoimat |
| one, power-horsepower | {0} hevosvoima |
| other, power-horsepower | {0} hevosvoimaa |
| pressure-hectopascal | ... |
| , pressure-hectopascal | hehtopascalit |
| one, pressure-hectopascal | {0} hehtopascal |
| other, pressure-hectopascal | {0} hehtopascalia |
| pressure-millimeter-of-mercury | ... |
| , pressure-millimeter-of-mercury | elohopeamillimetrit |
| one, pressure-millimeter-of-mercury | {0} millimetri elohopeaa |
| other, pressure-millimeter-of-mercury | {0} millimetriä elohopeaa |
| pressure-pound-per-square-inch | ... |
| , pressure-pound-per-square-inch | paunat / neliötuuma |
| one, pressure-pound-per-square-inch | {0} pauna / neliötuuma |
| other, pressure-pound-per-square-inch | {0} paunaa / neliötuuma |
| pressure-inch-hg | ... |
| , pressure-inch-hg | elohopeatuumat |
| one, pressure-inch-hg | {0} tuuma elohopeaa |
| other, pressure-inch-hg | {0} tuumaa elohopeaa |
| pressure-millibar | ... |
| , pressure-millibar | millibaarit |
| one, pressure-millibar | {0} millibaari |
| other, pressure-millibar | {0} millibaaria |
| speed-kilometer-per-hour | ... |
| , speed-kilometer-per-hour | kilometrit tunnissa |
| one, speed-kilometer-per-hour | {0} kilometri tunnissa |
| other, speed-kilometer-per-hour | {0} kilometriä tunnissa |
| speed-meter-per-second | ... |
| , speed-meter-per-second | metrit sekunnissa |
| one, speed-meter-per-second | {0} metri sekunnissa |
| other, speed-meter-per-second | {0} metriä sekunnissa |
| speed-mile-per-hour | ... |
| , speed-mile-per-hour | mailit tunnissa |
| one, speed-mile-per-hour | {0} maili tunnissa |
| other, speed-mile-per-hour | {0} mailia tunnissa |
| speed-knot | ... |
| , speed-knot | solmu |
| one, speed-knot | {0} solmu |
| other, speed-knot | {0} solmua |
| temperature-generic | ... |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ... |
| , temperature-celsius | celsiusasteet |
| one, temperature-celsius | {0} celsiusaste |
| other, temperature-celsius | {0} celsiusastetta |
| temperature-fahrenheit | ... |
| , temperature-fahrenheit | fahrenheitasteet |
| one, temperature-fahrenheit | {0} fahrenheitaste |
| other, temperature-fahrenheit | {0} fahrenheitastetta |
| temperature-kelvin | ... |
| , temperature-kelvin | kelvinit |
| one, temperature-kelvin | {0} kelvin |
| other, temperature-kelvin | {0} kelviniä |
| volume-cubic-kilometer | ... |
| , volume-cubic-kilometer | kuutiokilometrit |
| one, volume-cubic-kilometer | {0} kuutiokilometri |
| other, volume-cubic-kilometer | {0} kuutiokilometriä |
| volume-cubic-meter | ... |
| , volume-cubic-meter | kuutiometrit |
| one, volume-cubic-meter | {0} kuutiometri |
| other, volume-cubic-meter | {0} kuutiometriä |
| per units of volume-cubic-meter | {0} / kuutiometri |
| volume-cubic-centimeter | ... |
| , volume-cubic-centimeter | kuutiosenttimetrit |
| one, volume-cubic-centimeter | {0} kuutiosenttimetri |
| other, volume-cubic-centimeter | {0} kuutiosenttimetriä |
| per units of volume-cubic-centimeter | {0} / kuutiosenttimetri |
| volume-cubic-mile | ... |
| , volume-cubic-mile | kuutiomailit |
| one, volume-cubic-mile | {0} kuutiomaili |
| other, volume-cubic-mile | {0} kuutiomailia |
| volume-cubic-yard | ... |
| , volume-cubic-yard | kuutiojaardit |
| one, volume-cubic-yard | {0} kuutiojaardi |
| other, volume-cubic-yard | {0} kuutiojaardia |
| volume-cubic-foot | ... |
| , volume-cubic-foot | kuutiojalat |
| one, volume-cubic-foot | {0} kuutiojalka |
| other, volume-cubic-foot | {0} kuutiojalkaa |
| volume-cubic-inch | ... |
| , volume-cubic-inch | kuutiotuumat |
| one, volume-cubic-inch | {0} kuutiotuuma |
| other, volume-cubic-inch | {0} kuutiotuumaa |
| volume-megaliter | ... |
| , volume-megaliter | megalitrat |
| one, volume-megaliter | {0} megalitra |
| other, volume-megaliter | {0} megalitraa |
| volume-hectoliter | ... |
| , volume-hectoliter | hehtolitrat |
| one, volume-hectoliter | {0} hehtolitra |
| other, volume-hectoliter | {0} hehtolitraa |
| volume-liter | ... |
| , volume-liter | litrat |
| one, volume-liter | {0} litra |
| other, volume-liter | {0} litraa |
| per units of volume-liter | {0} / litra |
| volume-deciliter | ... |
| , volume-deciliter | desilitrat |
| one, volume-deciliter | {0} desilitra |
| other, volume-deciliter | {0} desilitraa |
| volume-centiliter | ... |
| , volume-centiliter | senttilitrat |
| one, volume-centiliter | {0} senttilitra |
| other, volume-centiliter | {0} senttilitraa |
| volume-milliliter | ... |
| , volume-milliliter | millilitrat |
| one, volume-milliliter | {0} millilitra |
| other, volume-milliliter | {0} millilitraa |
| volume-pint-metric | ... |
| , volume-pint-metric | tuopit |
| one, volume-pint-metric | {0} tuoppi |
| other, volume-pint-metric | {0} tuoppia |
| volume-cup-metric | ... |
| , volume-cup-metric | teekupit |
| one, volume-cup-metric | {0} teekuppi |
| other, volume-cup-metric | {0} teekuppia |
| volume-acre-foot | ... |
| , volume-acre-foot | eekkerijalat |
| one, volume-acre-foot | {0} eekkerijalka |
| other, volume-acre-foot | {0} eekkerijalkaa |
| volume-bushel | ... |
| , volume-bushel | bushelit |
| one, volume-bushel | {0} busheli |
| other, volume-bushel | {0} bushelia |
| volume-gallon | ... |
| , volume-gallon | am. gallonat |
| one, volume-gallon | {0} am. gallona |
| other, volume-gallon | {0} am. gallonaa |
| per units of volume-gallon | {0} / am. gallona |
| volume-gallon-imperial | ... |
| , volume-gallon-imperial | br. gallonat |
| one, volume-gallon-imperial | {0} br. gallona |
| other, volume-gallon-imperial | {0} br. gallonaa |
| per units of volume-gallon-imperial | {0} / br. gallona |
| volume-quart | ... |
| , volume-quart | neljännesgallonat |
| one, volume-quart | {0} neljännesgallona |
| other, volume-quart | {0} neljännesgallonaa |
| volume-pint | ... |
| , volume-pint | pintit |
| one, volume-pint | {0} pint |
| other, volume-pint | {0} pinttiä |
| volume-cup | ... |
| , volume-cup | kupit |
| one, volume-cup | {0} kuppi |
| other, volume-cup | {0} kuppia |
| volume-fluid-ounce | ... |
| , volume-fluid-ounce | nesteunssit |
| one, volume-fluid-ounce | {0} nesteunssi |
| other, volume-fluid-ounce | {0} nesteunssia |
| volume-tablespoon | ... |
| , volume-tablespoon | ruokalusikat |
| one, volume-tablespoon | {0} ruokalusikka |
| other, volume-tablespoon | {0} ruokalusikkaa |
| volume-teaspoon | ... |
| , volume-teaspoon | teelusikat |
| one, volume-teaspoon | {0} teelusikka |
| other, volume-teaspoon | {0} teelusikkaa |
{0}I{0}P{0}E{0}L
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
| , acceleration-g-force | G |
| one, acceleration-g-force | {0} G |
| other, acceleration-g-force | {0} G |
| acceleration-meter-per-second-squared | ... |
| , acceleration-meter-per-second-squared | m/s² |
| one, acceleration-meter-per-second-squared | {0} m/s² |
| other, acceleration-meter-per-second-squared | {0} m/s² |
| angle-revolution | ... |
| , angle-revolution | rev |
| one, angle-revolution | {0} rev |
| other, angle-revolution | {0} rev |
| angle-radian | ... |
| , angle-radian | rad |
| one, angle-radian | {0} rad |
| other, angle-radian | {0} rad |
| angle-degree | ... |
| , angle-degree | ° |
| one, angle-degree | {0}° |
| other, angle-degree | {0}° |
| angle-arc-minute | ... |
| , angle-arc-minute | ′ |
| one, angle-arc-minute | {0}′ |
| other, angle-arc-minute | {0}′ |
| angle-arc-second | ... |
| , angle-arc-second | ″ |
| one, angle-arc-second | {0}″ |
| other, angle-arc-second | {0}″ |
| area-square-kilometer | ... |
| , area-square-kilometer | km² |
| one, area-square-kilometer | {0} km² |
| other, area-square-kilometer | {0} km² |
| per units of area-square-kilometer | {0}/km² |
| area-hectare | ... |
| , area-hectare | ha |
| one, area-hectare | {0} ha |
| other, area-hectare | {0} ha |
| area-square-meter | ... |
| , area-square-meter | m² |
| one, area-square-meter | {0} m² |
| other, area-square-meter | {0} m² |
| per units of area-square-meter | {0}/m² |
| area-square-centimeter | ... |
| , area-square-centimeter | cm² |
| one, area-square-centimeter | {0} cm² |
| other, area-square-centimeter | {0} cm² |
| per units of area-square-centimeter | {0}/cm² |
| area-square-mile | ... |
| , area-square-mile | mi² |
| one, area-square-mile | {0} mi² |
| other, area-square-mile | {0} mi² |
| per units of area-square-mile | {0}/mi² |
| area-acre | ... |
| , area-acre | ac |
| one, area-acre | {0} ac |
| other, area-acre | {0} ac |
| area-square-yard | ... |
| , area-square-yard | yd² |
| one, area-square-yard | {0} yd² |
| other, area-square-yard | {0} yd² |
| area-square-foot | ... |
| , area-square-foot | ft² |
| one, area-square-foot | {0} ft² |
| other, area-square-foot | {0} ft² |
| area-square-inch | ... |
| , area-square-inch | in² |
| one, area-square-inch | {0} in² |
| other, area-square-inch | {0} in² |
| per units of area-square-inch | {0}/in² |
| concentr-karat | ... |
| , concentr-karat | ka |
| one, concentr-karat | {0} ka |
| other, concentr-karat | {0} ka |
| concentr-milligram-per-deciliter | ... |
| , concentr-milligram-per-deciliter | mg/dl |
| one, concentr-milligram-per-deciliter | {0} mg/dl |
| other, concentr-milligram-per-deciliter | {0} mg/dl |
| concentr-millimole-per-liter | ... |
| , concentr-millimole-per-liter | mmol/l |
| one, concentr-millimole-per-liter | {0} mmol/l |
| other, concentr-millimole-per-liter | {0} mmol/l |
| concentr-part-per-million | ... |
| , concentr-part-per-million | ppm |
| one, concentr-part-per-million | {0} ppm |
| other, concentr-part-per-million | {0} ppm |
| consumption-liter-per-kilometer | ... |
| , consumption-liter-per-kilometer | l/km |
| one, consumption-liter-per-kilometer | {0} l/km |
| other, consumption-liter-per-kilometer | {0} l/km |
| consumption-liter-per-100kilometers | ... |
| , consumption-liter-per-100kilometers | l/100 km |
| one, consumption-liter-per-100kilometers | {0} l/100 km |
| other, consumption-liter-per-100kilometers | {0} l/100 km |
| consumption-mile-per-gallon | ... |
| , consumption-mile-per-gallon | mpg-am |
| one, consumption-mile-per-gallon | {0} mpg-am |
| other, consumption-mile-per-gallon | {0} mpg-am |
| consumption-mile-per-gallon-imperial | ... |
| , consumption-mile-per-gallon-imperial | mpg-br |
| one, consumption-mile-per-gallon-imperial | {0} mpg-br |
| other, consumption-mile-per-gallon-imperial | {0} mpg-br |
| digital-terabyte | ... |
| , digital-terabyte | Tt |
| one, digital-terabyte | {0} Tt |
| other, digital-terabyte | {0} Tt |
| digital-terabit | ... |
| , digital-terabit | Tb |
| one, digital-terabit | {0} Tb |
| other, digital-terabit | {0} Tb |
| digital-gigabyte | ... |
| , digital-gigabyte | Gt |
| one, digital-gigabyte | {0} Gt |
| other, digital-gigabyte | {0} Gt |
| digital-gigabit | ... |
| , digital-gigabit | Gb |
| one, digital-gigabit | {0} Gb |
| other, digital-gigabit | {0} Gb |
| digital-megabyte | ... |
| , digital-megabyte | Mt |
| one, digital-megabyte | {0} Mt |
| other, digital-megabyte | {0} Mt |
| digital-megabit | ... |
| , digital-megabit | Mb |
| one, digital-megabit | {0} Mb |
| other, digital-megabit | {0} Mb |
| digital-kilobyte | ... |
| , digital-kilobyte | kt |
| one, digital-kilobyte | {0} kt |
| other, digital-kilobyte | {0} kt |
| digital-kilobit | ... |
| , digital-kilobit | kb |
| one, digital-kilobit | {0} kb |
| other, digital-kilobit | {0} kb |
| digital-byte | ... |
| , digital-byte | t |
| one, digital-byte | {0} t |
| other, digital-byte | {0} t |
| digital-bit | ... |
| , digital-bit | b |
| one, digital-bit | {0} b |
| other, digital-bit | {0} b |
| duration-century | ... |
| , duration-century | vs |
| one, duration-century | {0} vs |
| other, duration-century | {0} vs |
| duration-year | ... |
| , duration-year | v |
| one, duration-year | {0} v |
| other, duration-year | {0} v |
| per units of duration-year | {0}/v |
| duration-month | ... |
| , duration-month | kk |
| one, duration-month | {0} kk |
| other, duration-month | {0} kk |
| per units of duration-month | {0}/kk |
| duration-week | ... |
| , duration-week | vk |
| one, duration-week | {0} vk |
| other, duration-week | {0} vk |
| per units of duration-week | {0}/vk |
| duration-day | ... |
| , duration-day | pv |
| one, duration-day | {0} pv |
| other, duration-day | {0} pv |
| per units of duration-day | {0}/pv |
| duration-hour | ... |
| , duration-hour | t |
| one, duration-hour | {0} t |
| other, duration-hour | {0} t |
| per units of duration-hour | {0}/t |
| duration-minute | ... |
| , duration-minute | min |
| one, duration-minute | {0} min |
| other, duration-minute | {0} min |
| per units of duration-minute | {0}/min |
| duration-second | ... |
| , duration-second | sek |
| one, duration-second | {0} s |
| other, duration-second | {0} s |
| per units of duration-second | {0}/s |
| duration-millisecond | ... |
| , duration-millisecond | ms |
| one, duration-millisecond | {0} ms |
| other, duration-millisecond | {0} ms |
| duration-microsecond | ... |
| , duration-microsecond | μs |
| one, duration-microsecond | {0} μs |
| other, duration-microsecond | {0} μs |
| duration-nanosecond | ... |
| , duration-nanosecond | ns |
| one, duration-nanosecond | {0} ns |
| other, duration-nanosecond | {0} ns |
| electric-ampere | ... |
| , electric-ampere | A |
| one, electric-ampere | {0} A |
| other, electric-ampere | {0} A |
| electric-milliampere | ... |
| , electric-milliampere | mA |
| one, electric-milliampere | {0} mA |
| other, electric-milliampere | {0} mA |
| electric-ohm | ... |
| , electric-ohm | Ω |
| one, electric-ohm | {0} Ω |
| other, electric-ohm | {0} Ω |
| electric-volt | ... |
| , electric-volt | V |
| one, electric-volt | {0} V |
| other, electric-volt | {0} V |
| energy-kilocalorie | ... |
| , energy-kilocalorie | kcal |
| one, energy-kilocalorie | {0} kcal |
| other, energy-kilocalorie | {0} kcal |
| energy-calorie | ... |
| , energy-calorie | cal |
| one, energy-calorie | {0} cal |
| other, energy-calorie | {0} cal |
| energy-foodcalorie | ... |
| , energy-foodcalorie | kcal |
| one, energy-foodcalorie | {0} kcal |
| other, energy-foodcalorie | {0} kcal |
| energy-kilojoule | ... |
| , energy-kilojoule | kJ |
| one, energy-kilojoule | {0} kJ |
| other, energy-kilojoule | {0} kJ |
| energy-joule | ... |
| , energy-joule | J |
| one, energy-joule | {0} J |
| other, energy-joule | {0} J |
| energy-kilowatt-hour | ... |
| , energy-kilowatt-hour | kWh |
| one, energy-kilowatt-hour | {0} kWh |
| other, energy-kilowatt-hour | {0} kWh |
| frequency-gigahertz | ... |
| , frequency-gigahertz | GHz |
| one, frequency-gigahertz | {0} GHz |
| other, frequency-gigahertz | {0} GHz |
| frequency-megahertz | ... |
| , frequency-megahertz | MHz |
| one, frequency-megahertz | {0} MHz |
| other, frequency-megahertz | {0} MHz |
| frequency-kilohertz | ... |
| , frequency-kilohertz | kHz |
| one, frequency-kilohertz | {0} kHz |
| other, frequency-kilohertz | {0} kHz |
| frequency-hertz | ... |
| , frequency-hertz | Hz |
| one, frequency-hertz | {0} Hz |
| other, frequency-hertz | {0} Hz |
| length-kilometer | ... |
| , length-kilometer | km |
| one, length-kilometer | {0} km |
| other, length-kilometer | {0} km |
| per units of length-kilometer | {0}/km |
| length-meter | ... |
| , length-meter | m |
| one, length-meter | {0} m |
| other, length-meter | {0} m |
| per units of length-meter | {0}/m |
| length-decimeter | ... |
| , length-decimeter | dm |
| one, length-decimeter | {0} dm |
| other, length-decimeter | {0} dm |
| length-centimeter | ... |
| , length-centimeter | cm |
| one, length-centimeter | {0} cm |
| other, length-centimeter | {0} cm |
| per units of length-centimeter | {0}/cm |
| length-millimeter | ... |
| , length-millimeter | mm |
| one, length-millimeter | {0} mm |
| other, length-millimeter | {0} mm |
| length-micrometer | ... |
| , length-micrometer | µm |
| one, length-micrometer | {0} µm |
| other, length-micrometer | {0} µm |
| length-nanometer | ... |
| , length-nanometer | nm |
| one, length-nanometer | {0} nm |
| other, length-nanometer | {0} nm |
| length-picometer | ... |
| , length-picometer | pm |
| one, length-picometer | {0} pm |
| other, length-picometer | {0} pm |
| length-mile | ... |
| , length-mile | mi |
| one, length-mile | {0} mi |
| other, length-mile | {0} mi |
| length-yard | ... |
| , length-yard | yd |
| one, length-yard | {0} yd |
| other, length-yard | {0} yd |
| length-foot | ... |
| , length-foot | ft |
| one, length-foot | {0} ft |
| other, length-foot | {0} ft |
| per units of length-foot | {0}/ft |
| length-inch | ... |
| , length-inch | in |
| one, length-inch | {0} in |
| other, length-inch | {0} in |
| per units of length-inch | {0}/in |
| length-parsec | ... |
| , length-parsec | pc |
| one, length-parsec | {0} pc |
| other, length-parsec | {0} pc |
| length-light-year | ... |
| , length-light-year | vv |
| one, length-light-year | {0} vv |
| other, length-light-year | {0} vv |
| length-astronomical-unit | ... |
| , length-astronomical-unit | au |
| one, length-astronomical-unit | {0} au |
| other, length-astronomical-unit | {0} au |
| length-furlong | ... |
| , length-furlong | fur |
| one, length-furlong | {0} fur |
| other, length-furlong | {0} fur |
| length-fathom | ... |
| , length-fathom | fm |
| one, length-fathom | {0} fm |
| other, length-fathom | {0} fm |
| length-nautical-mile | ... |
| , length-nautical-mile | mpk |
| one, length-nautical-mile | {0} mpk |
| other, length-nautical-mile | {0} mpk |
| length-mile-scandinavian | ... |
| , length-mile-scandinavian | pnk |
| one, length-mile-scandinavian | {0} pnk |
| other, length-mile-scandinavian | {0} pnk |
| length-point | ... |
| , length-point | pt |
| one, length-point | {0} pt |
| other, length-point | {0} pt |
| light-lux | ... |
| , light-lux | lx |
| one, light-lux | {0} lx |
| other, light-lux | {0} lx |
| mass-metric-ton | ... |
| , mass-metric-ton | t |
| one, mass-metric-ton | {0} t |
| other, mass-metric-ton | {0} t |
| mass-kilogram | ... |
| , mass-kilogram | kg |
| one, mass-kilogram | {0} kg |
| other, mass-kilogram | {0} kg |
| per units of mass-kilogram | {0}/kg |
| mass-gram | ... |
| , mass-gram | g |
| one, mass-gram | {0} g |
| other, mass-gram | {0} g |
| per units of mass-gram | {0}/g |
| mass-milligram | ... |
| , mass-milligram | mg |
| one, mass-milligram | {0} mg |
| other, mass-milligram | {0} mg |
| mass-microgram | ... |
| , mass-microgram | µg |
| one, mass-microgram | {0} µg |
| other, mass-microgram | {0} µg |
| mass-ton | ... |
| , mass-ton | am. tn |
| one, mass-ton | {0} am. tn |
| other, mass-ton | {0} am. tn |
| mass-stone | ... |
| , mass-stone | st |
| one, mass-stone | {0} st |
| other, mass-stone | {0} st |
| mass-pound | ... |
| , mass-pound | lb |
| one, mass-pound | {0} lb |
| other, mass-pound | {0} lb |
| per units of mass-pound | {0}/lb |
| mass-ounce | ... |
| , mass-ounce | oz |
| one, mass-ounce | {0} oz |
| other, mass-ounce | {0} oz |
| per units of mass-ounce | {0}/oz |
| mass-ounce-troy | ... |
| , mass-ounce-troy | oz t |
| one, mass-ounce-troy | {0} oz t |
| other, mass-ounce-troy | {0} oz t |
| mass-carat | ... |
| , mass-carat | ka |
| one, mass-carat | {0} ka |
| other, mass-carat | {0} ka |
| power-gigawatt | ... |
| , power-gigawatt | GW |
| one, power-gigawatt | {0} GW |
| other, power-gigawatt | {0} GW |
| power-megawatt | ... |
| , power-megawatt | MW |
| one, power-megawatt | {0} MW |
| other, power-megawatt | {0} MW |
| power-kilowatt | ... |
| , power-kilowatt | kW |
| one, power-kilowatt | {0} kW |
| other, power-kilowatt | {0} kW |
| power-watt | ... |
| , power-watt | W |
| one, power-watt | {0} W |
| other, power-watt | {0} W |
| power-milliwatt | ... |
| , power-milliwatt | mW |
| one, power-milliwatt | {0} mW |
| other, power-milliwatt | {0} mW |
| power-horsepower | ... |
| , power-horsepower | hv |
| one, power-horsepower | {0} hv |
| other, power-horsepower | {0} hv |
| pressure-hectopascal | ... |
| , pressure-hectopascal | hPa |
| one, pressure-hectopascal | {0} hPa |
| other, pressure-hectopascal | {0} hPa |
| pressure-millimeter-of-mercury | ... |
| , pressure-millimeter-of-mercury | mm Hg |
| one, pressure-millimeter-of-mercury | {0} mm Hg |
| other, pressure-millimeter-of-mercury | {0} mm Hg |
| pressure-pound-per-square-inch | ... |
| , pressure-pound-per-square-inch | psi |
| one, pressure-pound-per-square-inch | {0} psi |
| other, pressure-pound-per-square-inch | {0} psi |
| pressure-inch-hg | ... |
| , pressure-inch-hg | inHg |
| one, pressure-inch-hg | {0} inHg |
| other, pressure-inch-hg | {0} inHg |
| pressure-millibar | ... |
| , pressure-millibar | mbar |
| one, pressure-millibar | {0} mbar |
| other, pressure-millibar | {0} mbar |
| speed-kilometer-per-hour | ... |
| , speed-kilometer-per-hour | km/h |
| one, speed-kilometer-per-hour | {0} km/h |
| other, speed-kilometer-per-hour | {0} km/h |
| speed-meter-per-second | ... |
| , speed-meter-per-second | m/s |
| one, speed-meter-per-second | {0} m/s |
| other, speed-meter-per-second | {0} m/s |
| speed-mile-per-hour | ... |
| , speed-mile-per-hour | mi/h |
| one, speed-mile-per-hour | {0} mi/h |
| other, speed-mile-per-hour | {0} mi/h |
| speed-knot | ... |
| , speed-knot | kn |
| one, speed-knot | {0} kn |
| other, speed-knot | {0} kn |
| temperature-generic | ... |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ... |
| , temperature-celsius | °C |
| one, temperature-celsius | {0} °C |
| other, temperature-celsius | {0} °C |
| temperature-fahrenheit | ... |
| , temperature-fahrenheit | °F |
| one, temperature-fahrenheit | {0} °F |
| other, temperature-fahrenheit | {0} °F |
| temperature-kelvin | ... |
| , temperature-kelvin | K |
| one, temperature-kelvin | {0} K |
| other, temperature-kelvin | {0} K |
| volume-cubic-kilometer | ... |
| , volume-cubic-kilometer | km³ |
| one, volume-cubic-kilometer | {0} km³ |
| other, volume-cubic-kilometer | {0} km³ |
| volume-cubic-meter | ... |
| , volume-cubic-meter | m³ |
| one, volume-cubic-meter | {0} m³ |
| other, volume-cubic-meter | {0} m³ |
| per units of volume-cubic-meter | {0}/m³ |
| volume-cubic-centimeter | ... |
| , volume-cubic-centimeter | cm³ |
| one, volume-cubic-centimeter | {0} cm³ |
| other, volume-cubic-centimeter | {0} cm³ |
| per units of volume-cubic-centimeter | {0}/cm³ |
| volume-cubic-mile | ... |
| , volume-cubic-mile | mi³ |
| one, volume-cubic-mile | {0} mi³ |
| other, volume-cubic-mile | {0} mi³ |
| volume-cubic-yard | ... |
| , volume-cubic-yard | yd³ |
| one, volume-cubic-yard | {0} yd³ |
| other, volume-cubic-yard | {0} yd³ |
| volume-cubic-foot | ... |
| , volume-cubic-foot | ft³ |
| one, volume-cubic-foot | {0} ft³ |
| other, volume-cubic-foot | {0} ft³ |
| volume-cubic-inch | ... |
| , volume-cubic-inch | in³ |
| one, volume-cubic-inch | {0} in³ |
| other, volume-cubic-inch | {0} in³ |
| volume-megaliter | ... |
| , volume-megaliter | Ml |
| one, volume-megaliter | {0} Ml |
| other, volume-megaliter | {0} Ml |
| volume-hectoliter | ... |
| , volume-hectoliter | hl |
| one, volume-hectoliter | {0} hl |
| other, volume-hectoliter | {0} hl |
| volume-liter | ... |
| , volume-liter | l |
| one, volume-liter | {0} l |
| other, volume-liter | {0} l |
| per units of volume-liter | {0}/l |
| volume-deciliter | ... |
| , volume-deciliter | dl |
| one, volume-deciliter | {0} dl |
| other, volume-deciliter | {0} dl |
| volume-centiliter | ... |
| , volume-centiliter | cl |
| one, volume-centiliter | {0} cl |
| other, volume-centiliter | {0} cl |
| volume-milliliter | ... |
| , volume-milliliter | ml |
| one, volume-milliliter | {0} ml |
| other, volume-milliliter | {0} ml |
| volume-pint-metric | ... |
| , volume-pint-metric | tp |
| one, volume-pint-metric | {0} tp |
| other, volume-pint-metric | {0} tp |
| volume-cup-metric | ... |
| , volume-cup-metric | tkp |
| one, volume-cup-metric | {0} tkp |
| other, volume-cup-metric | {0} tkp |
| volume-acre-foot | ... |
| , volume-acre-foot | ac ft |
| one, volume-acre-foot | {0} ac ft |
| other, volume-acre-foot | {0} ac ft |
| volume-bushel | ... |
| , volume-bushel | bu |
| one, volume-bushel | {0} bu |
| other, volume-bushel | {0} bu |
| volume-gallon | ... |
| , volume-gallon | am. gal |
| one, volume-gallon | {0} am. gal |
| other, volume-gallon | {0} am. gal |
| per units of volume-gallon | {0}/am. gal |
| volume-gallon-imperial | ... |
| , volume-gallon-imperial | br. gal |
| one, volume-gallon-imperial | {0} br. gal |
| other, volume-gallon-imperial | {0} br. gal |
| per units of volume-gallon-imperial | {0}/br. gal |
| volume-quart | ... |
| , volume-quart | qt |
| one, volume-quart | {0} qt |
| other, volume-quart | {0} qt |
| volume-pint | ... |
| , volume-pint | pt |
| one, volume-pint | {0} pt |
| other, volume-pint | {0} pt |
| volume-cup | ... |
| , volume-cup | kp |
| one, volume-cup | {0} kp |
| other, volume-cup | {0} kp |
| volume-fluid-ounce | ... |
| , volume-fluid-ounce | fl oz |
| one, volume-fluid-ounce | {0} fl oz |
| other, volume-fluid-ounce | {0} fl oz |
| volume-tablespoon | ... |
| , volume-tablespoon | rkl |
| one, volume-tablespoon | {0} rkl |
| other, volume-tablespoon | {0} rkl |
| volume-teaspoon | ... |
| , volume-teaspoon | tl |
| one, volume-teaspoon | {0} tl |
| other, volume-teaspoon | {0} tl |
{0}I{0}P{0}E{0}L
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
| , acceleration-g-force | G |
| one, acceleration-g-force | {0}G |
| other, acceleration-g-force | {0}G |
| acceleration-meter-per-second-squared | ... |
| , acceleration-meter-per-second-squared | m/s² |
| one, acceleration-meter-per-second-squared | {0}m/s² |
| other, acceleration-meter-per-second-squared | {0}m/s² |
| angle-revolution | ... |
| , angle-revolution | rev |
| one, angle-revolution | {0}rev |
| other, angle-revolution | {0}rev |
| angle-radian | ... |
| , angle-radian | rad |
| one, angle-radian | {0}rad |
| other, angle-radian | {0}rad |
| angle-degree | ... |
| , angle-degree | ° |
| one, angle-degree | {0}° |
| other, angle-degree | {0}° |
| angle-arc-minute | ... |
| , angle-arc-minute | ′ |
| one, angle-arc-minute | {0}′ |
| other, angle-arc-minute | {0}′ |
| angle-arc-second | ... |
| , angle-arc-second | ″ |
| one, angle-arc-second | {0}″ |
| other, angle-arc-second | {0}″ |
| area-square-kilometer | ... |
| , area-square-kilometer | km² |
| one, area-square-kilometer | {0}km² |
| other, area-square-kilometer | {0}km² |
| per units of area-square-kilometer | {0}/km² |
| area-hectare | ... |
| , area-hectare | ha |
| one, area-hectare | {0}ha |
| other, area-hectare | {0}ha |
| area-square-meter | ... |
| , area-square-meter | m² |
| one, area-square-meter | {0}m² |
| other, area-square-meter | {0}m² |
| per units of area-square-meter | {0}/m² |
| area-square-centimeter | ... |
| , area-square-centimeter | cm² |
| one, area-square-centimeter | {0}cm² |
| other, area-square-centimeter | {0}cm² |
| per units of area-square-centimeter | {0}/cm² |
| area-square-mile | ... |
| , area-square-mile | mi² |
| one, area-square-mile | {0}mi² |
| other, area-square-mile | {0}mi² |
| per units of area-square-mile | {0}/mi² |
| area-acre | ... |
| , area-acre | ac |
| one, area-acre | {0}ac |
| other, area-acre | {0}ac |
| area-square-yard | ... |
| , area-square-yard | yd² |
| one, area-square-yard | {0}yd² |
| other, area-square-yard | {0}yd² |
| area-square-foot | ... |
| , area-square-foot | ft² |
| one, area-square-foot | {0}ft² |
| other, area-square-foot | {0}ft² |
| area-square-inch | ... |
| , area-square-inch | in² |
| one, area-square-inch | {0}in² |
| other, area-square-inch | {0}in² |
| per units of area-square-inch | {0}/in² |
| concentr-karat | ... |
| , concentr-karat | ka |
| one, concentr-karat | {0}ka |
| other, concentr-karat | {0}ka |
| concentr-milligram-per-deciliter | ... |
| , concentr-milligram-per-deciliter | mg/dl |
| one, concentr-milligram-per-deciliter | {0}mg/dl |
| other, concentr-milligram-per-deciliter | {0}mg/dl |
| concentr-millimole-per-liter | ... |
| , concentr-millimole-per-liter | mmol/l |
| one, concentr-millimole-per-liter | {0}mmol/l |
| other, concentr-millimole-per-liter | {0}mmol/l |
| concentr-part-per-million | ... |
| , concentr-part-per-million | ppm |
| one, concentr-part-per-million | {0}ppm |
| other, concentr-part-per-million | {0}ppm |
| consumption-liter-per-kilometer | ... |
| , consumption-liter-per-kilometer | l/km |
| one, consumption-liter-per-kilometer | {0}l/km |
| other, consumption-liter-per-kilometer | {0}l/km |
| consumption-liter-per-100kilometers | ... |
| , consumption-liter-per-100kilometers | l/100km |
| one, consumption-liter-per-100kilometers | {0}l/100km |
| other, consumption-liter-per-100kilometers | {0}l/100km |
| consumption-mile-per-gallon | ... |
| , consumption-mile-per-gallon | mpg-am |
| one, consumption-mile-per-gallon | {0}mpg-am |
| other, consumption-mile-per-gallon | {0}mpg-am |
| consumption-mile-per-gallon-imperial | ... |
| , consumption-mile-per-gallon-imperial | mpg-br |
| one, consumption-mile-per-gallon-imperial | {0}mpg-br |
| other, consumption-mile-per-gallon-imperial | {0}mpg-br |
| digital-terabyte | ... |
| , digital-terabyte | Tt |
| one, digital-terabyte | {0}Tt |
| other, digital-terabyte | {0}Tt |
| digital-terabit | ... |
| , digital-terabit | Tb |
| one, digital-terabit | {0}Tb |
| other, digital-terabit | {0}Tb |
| digital-gigabyte | ... |
| , digital-gigabyte | Gt |
| one, digital-gigabyte | {0}Gt |
| other, digital-gigabyte | {0}Gt |
| digital-gigabit | ... |
| , digital-gigabit | Gb |
| one, digital-gigabit | {0}Gb |
| other, digital-gigabit | {0}Gb |
| digital-megabyte | ... |
| , digital-megabyte | Mt |
| one, digital-megabyte | {0}Mt |
| other, digital-megabyte | {0}Mt |
| digital-megabit | ... |
| , digital-megabit | Mb |
| one, digital-megabit | {0}Mb |
| other, digital-megabit | {0}Mb |
| digital-kilobyte | ... |
| , digital-kilobyte | kt |
| one, digital-kilobyte | {0}kt |
| other, digital-kilobyte | {0}kt |
| digital-kilobit | ... |
| , digital-kilobit | kb |
| one, digital-kilobit | {0}kb |
| other, digital-kilobit | {0}kb |
| digital-byte | ... |
| , digital-byte | t |
| one, digital-byte | {0}t |
| other, digital-byte | {0}t |
| digital-bit | ... |
| , digital-bit | b |
| one, digital-bit | {0}b |
| other, digital-bit | {0}b |
| duration-century | ... |
| , duration-century | vs |
| one, duration-century | {0} vs |
| other, duration-century | {0} vs |
| duration-year | ... |
| , duration-year | v |
| one, duration-year | {0}v |
| other, duration-year | {0}v |
| per units of duration-year | {0}/v |
| duration-month | ... |
| , duration-month | kk |
| one, duration-month | {0}kk |
| other, duration-month | {0}kk |
| per units of duration-month | {0}/kk |
| duration-week | ... |
| , duration-week | vk |
| one, duration-week | {0}vk |
| other, duration-week | {0}vk |
| per units of duration-week | {0}/vk |
| duration-day | ... |
| , duration-day | pv |
| one, duration-day | {0}pv |
| other, duration-day | {0}pv |
| per units of duration-day | {0}/pv |
| duration-hour | ... |
| , duration-hour | t |
| one, duration-hour | {0}t |
| other, duration-hour | {0}t |
| per units of duration-hour | {0}/t |
| duration-minute | ... |
| , duration-minute | min |
| one, duration-minute | {0}min |
| other, duration-minute | {0}min |
| per units of duration-minute | {0}/min |
| duration-second | ... |
| , duration-second | s |
| one, duration-second | {0}s |
| other, duration-second | {0}s |
| per units of duration-second | {0}/s |
| duration-millisecond | ... |
| , duration-millisecond | ms |
| one, duration-millisecond | {0}ms |
| other, duration-millisecond | {0}ms |
| duration-microsecond | ... |
| , duration-microsecond | μs |
| one, duration-microsecond | {0}μs |
| other, duration-microsecond | {0}μs |
| duration-nanosecond | ... |
| , duration-nanosecond | ns |
| one, duration-nanosecond | {0}ns |
| other, duration-nanosecond | {0}ns |
| electric-ampere | ... |
| , electric-ampere | A |
| one, electric-ampere | {0}A |
| other, electric-ampere | {0}A |
| electric-milliampere | ... |
| , electric-milliampere | mA |
| one, electric-milliampere | {0}mA |
| other, electric-milliampere | {0}mA |
| electric-ohm | ... |
| , electric-ohm | Ω |
| one, electric-ohm | {0}Ω |
| other, electric-ohm | {0}Ω |
| electric-volt | ... |
| , electric-volt | V |
| one, electric-volt | {0}V |
| other, electric-volt | {0}V |
| energy-kilocalorie | ... |
| , energy-kilocalorie | kcal |
| one, energy-kilocalorie | {0}kcal |
| other, energy-kilocalorie | {0}kcal |
| energy-calorie | ... |
| , energy-calorie | cal |
| one, energy-calorie | {0}cal |
| other, energy-calorie | {0}cal |
| energy-foodcalorie | ... |
| , energy-foodcalorie | kcal |
| one, energy-foodcalorie | {0}kcal |
| other, energy-foodcalorie | {0}kcal |
| energy-kilojoule | ... |
| , energy-kilojoule | kJ |
| one, energy-kilojoule | {0}kJ |
| other, energy-kilojoule | {0}kJ |
| energy-joule | ... |
| , energy-joule | J |
| one, energy-joule | {0}J |
| other, energy-joule | {0}J |
| energy-kilowatt-hour | ... |
| , energy-kilowatt-hour | kWh |
| one, energy-kilowatt-hour | {0}kWh |
| other, energy-kilowatt-hour | {0}kWh |
| frequency-gigahertz | ... |
| , frequency-gigahertz | GHz |
| one, frequency-gigahertz | {0}GHz |
| other, frequency-gigahertz | {0}GHz |
| frequency-megahertz | ... |
| , frequency-megahertz | MHz |
| one, frequency-megahertz | {0}MHz |
| other, frequency-megahertz | {0}MHz |
| frequency-kilohertz | ... |
| , frequency-kilohertz | kHz |
| one, frequency-kilohertz | {0}kHz |
| other, frequency-kilohertz | {0}kHz |
| frequency-hertz | ... |
| , frequency-hertz | Hz |
| one, frequency-hertz | {0}Hz |
| other, frequency-hertz | {0}Hz |
| length-kilometer | ... |
| , length-kilometer | km |
| one, length-kilometer | {0}km |
| other, length-kilometer | {0}km |
| per units of length-kilometer | {0}/km |
| length-meter | ... |
| , length-meter | m |
| one, length-meter | {0}m |
| other, length-meter | {0}m |
| per units of length-meter | {0}/m |
| length-decimeter | ... |
| , length-decimeter | dm |
| one, length-decimeter | {0}dm |
| other, length-decimeter | {0}dm |
| length-centimeter | ... |
| , length-centimeter | cm |
| one, length-centimeter | {0}cm |
| other, length-centimeter | {0}cm |
| per units of length-centimeter | {0}/cm |
| length-millimeter | ... |
| , length-millimeter | mm |
| one, length-millimeter | {0}mm |
| other, length-millimeter | {0}mm |
| length-micrometer | ... |
| , length-micrometer | µm |
| one, length-micrometer | {0}µm |
| other, length-micrometer | {0}µm |
| length-nanometer | ... |
| , length-nanometer | nm |
| one, length-nanometer | {0}nm |
| other, length-nanometer | {0}nm |
| length-picometer | ... |
| , length-picometer | pm |
| one, length-picometer | {0}pm |
| other, length-picometer | {0}pm |
| length-mile | ... |
| , length-mile | mi |
| one, length-mile | {0}mi |
| other, length-mile | {0}mi |
| length-yard | ... |
| , length-yard | yd |
| one, length-yard | {0}yd |
| other, length-yard | {0}yd |
| length-foot | ... |
| , length-foot | ft |
| one, length-foot | {0}′ |
| other, length-foot | {0}′ |
| per units of length-foot | {0}/′ |
| length-inch | ... |
| , length-inch | in |
| one, length-inch | {0}″ |
| other, length-inch | {0}″ |
| per units of length-inch | {0}/″ |
| length-parsec | ... |
| , length-parsec | pc |
| one, length-parsec | {0}pc |
| other, length-parsec | {0}pc |
| length-light-year | ... |
| , length-light-year | vv |
| one, length-light-year | {0}vv |
| other, length-light-year | {0}vv |
| length-astronomical-unit | ... |
| , length-astronomical-unit | au |
| one, length-astronomical-unit | {0}au |
| other, length-astronomical-unit | {0}au |
| length-furlong | ... |
| , length-furlong | fur |
| one, length-furlong | {0}fur |
| other, length-furlong | {0}fur |
| length-fathom | ... |
| , length-fathom | fm |
| one, length-fathom | {0}fm |
| other, length-fathom | {0}fm |
| length-nautical-mile | ... |
| , length-nautical-mile | mpk |
| one, length-nautical-mile | {0}mpk |
| other, length-nautical-mile | {0}mpk |
| length-mile-scandinavian | ... |
| , length-mile-scandinavian | pnk |
| one, length-mile-scandinavian | {0}pnk |
| other, length-mile-scandinavian | {0}pnk |
| light-lux | ... |
| , light-lux | lx |
| one, light-lux | {0}lx |
| other, light-lux | {0}lx |
| mass-metric-ton | ... |
| , mass-metric-ton | t |
| one, mass-metric-ton | {0}t |
| other, mass-metric-ton | {0}t |
| mass-kilogram | ... |
| , mass-kilogram | kg |
| one, mass-kilogram | {0}kg |
| other, mass-kilogram | {0}kg |
| per units of mass-kilogram | {0}/kg |
| mass-gram | ... |
| , mass-gram | g |
| one, mass-gram | {0}g |
| other, mass-gram | {0}g |
| per units of mass-gram | {0}/g |
| mass-milligram | ... |
| , mass-milligram | mg |
| one, mass-milligram | {0}mg |
| other, mass-milligram | {0}mg |
| mass-microgram | ... |
| , mass-microgram | µg |
| one, mass-microgram | {0}μg |
| other, mass-microgram | {0}μg |
| mass-ton | ... |
| , mass-ton | am.tn |
| one, mass-ton | {0}am.tn |
| other, mass-ton | {0}am.tn |
| mass-stone | ... |
| , mass-stone | st |
| one, mass-stone | {0}st |
| other, mass-stone | {0}st |
| mass-pound | ... |
| , mass-pound | lb |
| one, mass-pound | {0}lb |
| other, mass-pound | {0}lb |
| per units of mass-pound | {0}/lb |
| mass-ounce | ... |
| , mass-ounce | oz |
| one, mass-ounce | {0}oz |
| other, mass-ounce | {0}oz |
| per units of mass-ounce | {0}/oz |
| mass-ounce-troy | ... |
| , mass-ounce-troy | oz t |
| one, mass-ounce-troy | {0}oz t |
| other, mass-ounce-troy | {0}oz t |
| mass-carat | ... |
| , mass-carat | ka |
| one, mass-carat | {0}ka |
| other, mass-carat | {0}ka |
| power-gigawatt | ... |
| , power-gigawatt | GW |
| one, power-gigawatt | {0}GW |
| other, power-gigawatt | {0}GW |
| power-megawatt | ... |
| , power-megawatt | MW |
| one, power-megawatt | {0}MW |
| other, power-megawatt | {0} MW |
| power-kilowatt | ... |
| , power-kilowatt | kW |
| one, power-kilowatt | {0}kW |
| other, power-kilowatt | {0}kW |
| power-watt | ... |
| , power-watt | W |
| one, power-watt | {0}W |
| other, power-watt | {0}W |
| power-milliwatt | ... |
| , power-milliwatt | mW |
| one, power-milliwatt | {0}mW |
| other, power-milliwatt | {0}mW |
| power-horsepower | ... |
| , power-horsepower | hv |
| one, power-horsepower | {0}hv |
| other, power-horsepower | {0}hv |
| pressure-hectopascal | ... |
| , pressure-hectopascal | hPa |
| one, pressure-hectopascal | {0}hPa |
| other, pressure-hectopascal | {0}hPa |
| pressure-millimeter-of-mercury | ... |
| , pressure-millimeter-of-mercury | mmHg |
| one, pressure-millimeter-of-mercury | {0}mmHg |
| other, pressure-millimeter-of-mercury | {0}mmHg |
| pressure-pound-per-square-inch | ... |
| , pressure-pound-per-square-inch | psi |
| one, pressure-pound-per-square-inch | {0}psi |
| other, pressure-pound-per-square-inch | {0}psi |
| pressure-inch-hg | ... |
| , pressure-inch-hg | inHg |
| one, pressure-inch-hg | {0}″ Hg |
| other, pressure-inch-hg | {0}″ Hg |
| pressure-millibar | ... |
| , pressure-millibar | mbar |
| one, pressure-millibar | {0}mbar |
| other, pressure-millibar | {0}mbar |
| speed-kilometer-per-hour | ... |
| , speed-kilometer-per-hour | km/h |
| one, speed-kilometer-per-hour | {0}km/h |
| other, speed-kilometer-per-hour | {0}km/h |
| speed-meter-per-second | ... |
| , speed-meter-per-second | m/s |
| one, speed-meter-per-second | {0}m/s |
| other, speed-meter-per-second | {0}m/s |
| speed-mile-per-hour | ... |
| , speed-mile-per-hour | mi/h |
| one, speed-mile-per-hour | {0}mi/h |
| other, speed-mile-per-hour | {0}mi/h |
| speed-knot | ... |
| , speed-knot | kn |
| one, speed-knot | {0}kn |
| other, speed-knot | {0}kn |
| temperature-generic | ... |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ... |
| , temperature-celsius | °C |
| one, temperature-celsius | {0}° |
| other, temperature-celsius | {0}° |
| temperature-fahrenheit | ... |
| , temperature-fahrenheit | °F |
| one, temperature-fahrenheit | {0}°F |
| other, temperature-fahrenheit | {0}°F |
| temperature-kelvin | ... |
| , temperature-kelvin | K |
| one, temperature-kelvin | {0}K |
| other, temperature-kelvin | {0}K |
| volume-cubic-kilometer | ... |
| , volume-cubic-kilometer | km³ |
| one, volume-cubic-kilometer | {0}km³ |
| other, volume-cubic-kilometer | {0}km³ |
| volume-cubic-meter | ... |
| , volume-cubic-meter | m³ |
| one, volume-cubic-meter | {0}m³ |
| other, volume-cubic-meter | {0}m³ |
| per units of volume-cubic-meter | {0}/m³ |
| volume-cubic-centimeter | ... |
| , volume-cubic-centimeter | cm³ |
| one, volume-cubic-centimeter | {0}cm³ |
| other, volume-cubic-centimeter | {0}cm³ |
| per units of volume-cubic-centimeter | {0}/cm³ |
| volume-cubic-mile | ... |
| , volume-cubic-mile | mi³ |
| one, volume-cubic-mile | {0}mi³ |
| other, volume-cubic-mile | {0}mi³ |
| volume-cubic-yard | ... |
| , volume-cubic-yard | yd³ |
| one, volume-cubic-yard | {0}yd³ |
| other, volume-cubic-yard | {0}yd³ |
| volume-cubic-foot | ... |
| , volume-cubic-foot | ft³ |
| one, volume-cubic-foot | {0}ft³ |
| other, volume-cubic-foot | {0}ft³ |
| volume-cubic-inch | ... |
| , volume-cubic-inch | in³ |
| one, volume-cubic-inch | {0}in³ |
| other, volume-cubic-inch | {0}in³ |
| volume-megaliter | ... |
| , volume-megaliter | Ml |
| one, volume-megaliter | {0}Ml |
| other, volume-megaliter | {0}Ml |
| volume-hectoliter | ... |
| , volume-hectoliter | hl |
| one, volume-hectoliter | {0}hl |
| other, volume-hectoliter | {0}hl |
| volume-liter | ... |
| , volume-liter | l |
| one, volume-liter | {0}l |
| other, volume-liter | {0}l |
| per units of volume-liter | {0}/l |
| volume-deciliter | ... |
| , volume-deciliter | dl |
| one, volume-deciliter | {0}dl |
| other, volume-deciliter | {0}dl |
| volume-centiliter | ... |
| , volume-centiliter | cl |
| one, volume-centiliter | {0}cl |
| other, volume-centiliter | {0}cl |
| volume-milliliter | ... |
| , volume-milliliter | ml |
| one, volume-milliliter | {0}ml |
| other, volume-milliliter | {0}ml |
| volume-pint-metric | ... |
| , volume-pint-metric | tp |
| one, volume-pint-metric | {0}tp |
| other, volume-pint-metric | {0}tp |
| volume-cup-metric | ... |
| , volume-cup-metric | tkp |
| one, volume-cup-metric | {0}tkp |
| other, volume-cup-metric | {0}tkp |
| volume-acre-foot | ... |
| , volume-acre-foot | ac ft |
| one, volume-acre-foot | {0}ac ft |
| other, volume-acre-foot | {0}ac ft |
| volume-bushel | ... |
| , volume-bushel | bu |
| one, volume-bushel | {0}bu |
| other, volume-bushel | {0}bu |
| volume-gallon | ... |
| , volume-gallon | am.gal |
| one, volume-gallon | {0}am.gal |
| other, volume-gallon | {0}am.gal |
| per units of volume-gallon | {0}/am.gal |
| volume-gallon-imperial | ... |
| , volume-gallon-imperial | br.gal |
| one, volume-gallon-imperial | {0}br.gal |
| other, volume-gallon-imperial | {0}br.gal |
| per units of volume-gallon-imperial | {0}/br.gal |
| volume-quart | ... |
| , volume-quart | qt |
| one, volume-quart | {0}qt |
| other, volume-quart | {0}qt |
| volume-pint | ... |
| , volume-pint | pt |
| one, volume-pint | {0}pt |
| other, volume-pint | {0}pt |
| volume-cup | ... |
| , volume-cup | kp |
| one, volume-cup | {0}kp |
| other, volume-cup | {0}kp |
| volume-fluid-ounce | ... |
| , volume-fluid-ounce | fl oz |
| one, volume-fluid-ounce | {0}fl oz |
| other, volume-fluid-ounce | {0}fl oz |
| volume-tablespoon | ... |
| , volume-tablespoon | rkl |
| one, volume-tablespoon | {0}rkl |
| other, volume-tablespoon | {0}rkl |
| volume-teaspoon | ... |
| , volume-teaspoon | tl |
| one, volume-teaspoon | {0}tl |
| other, volume-teaspoon | {0}tl |
{0}I{0}P{0}E{0}Lh.mmh.mm.ssm.ss

## Lists

| List type | Patterns |
| --------- | -------- |
|  | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} ja {1} |
| 2 | {0} ja {1} |
| or | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} tai {1} |
| 2 | {0} tai {1} |
| standard-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} ja {1} |
| 2 | {0} ja {1} |
| unit | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} ja {1} |
| 2 | {0} ja {1} |
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

| Messages | Values |
| -------- | ------ |
| `yes` / affirmative | `kyllä:k` |
| `no` / negative | `ei:e` |

## Character sets

| Set | Name |
| --- | ---- |
| all | {0} – kaikki |
| category-list | {0}: {1} |
| compatibility | {0} – yhteensopivuus |
| enclosed | {0} – ympäröity |
| extended | {0} – laajennettu |
| historic | {0} – historiallinen |
| miscellaneous | {0} – sekalaiset |
| other | {0} – muut |
| scripts | kirjoitusjärjestelmät – {0} |
| onestrokes | {0} piirtoviiva |
| otherstrokes | {0} piirtoviivaa |
| activities | toiminta |
| african_scripts | afrikkalaiset kirjoitusjärjestelmät |
| american_scripts | amerikkalaiset kirjoitusjärjestelmät |
| animal | eläin |
| animals_nature | eläimet ja luonto |
| arrows | nuolet |
| body | keho |
| box_drawing | viivapiirrosmerkit |
| braille | pistekirjoitus |
| building | rakennus |
| bullets_stars | luettelomerkit ja tähdet |
| consonantal_jamo | jamo-konsonanttielementit |
| currency_symbols | valuuttamerkit |
| dash_connector | yhdysmerkit |
| digits | numerot |
| dingbats | ornamentit |
| divination_symbols | ennustussymbolit |
| downwards_arrows | alaspäin osoittavat nuolet |
| downwards_upwards_arrows | alas- ja ylöspäin osoittavat nuolet |
| east_asian_scripts | itäaasialaiset kirjoitusjärjestelmät |
| emoji | emojit |
| european_scripts | eurooppalaiset kirjoitusjärjestelmät |
| female | naissukupuolinen |
| flag | lippu |
| flags | liput |
| food_drink | ruoka ja juoma |
| format | muotoilu |
| format_whitespace | muotoilu ja tyhjämerkki |
| full_width_form_variant | ideografin levyiset muotovariantit |
| geometric_shapes | geometriset kuviot |
| half_width_form_variant | ideografin puolikkaan levyiset muotovariantit |
| han_characters | han-merkit |
| han_radicals | han-radikaalit |
| hanja | hanja |
| hanzi_simplified | hanzi (yksinkertaistettu) |
| hanzi_traditional | hanzi (perinteinen) |
| heart | sydän |
| historic_scripts | historialliset kirjoitusjärjestelmät |
| ideographic_desc_characters | ideogrammien kuvausmerkit |
| japanese_kana | japanilainen kana-kirjoitusjärjestelmä |
| kanbun | kanbun |
| kanji | kanji |
| keycap | näppäin |
| leftwards_arrows | vasemmalle osoittavat nuolet |
| leftwards_rightwards_arrows | vasemmalle ja oikealle osoittavat nuolet |
| letterlike_symbols | kirjainsymbolit |
| limited_use | rajoitettu käyttö |
| male | miessukupuolinen |
| math_symbols | matemaattiset symbolit |
| middle_eastern_scripts | Lähi-idän kirjoitusjärjestelmät |
| miscellaneous | sekalaiset |
| modern_scripts | nykyaikaiset kirjoitusjärjestelmät |
| modifier | tarkkeenomaiset merkit |
| musical_symbols | musiikkisymbolit |
| nature | luonto |
| nonspacing | omaa tilaa viemättömät merkit |
| numbers | numerot |
| objects | objektit |
| other | muut |
| paired | merkkiparit |
| person | henkilö |
| phonetic_alphabet | foneettiset aakkoset |
| pictographs | kuvakirjoitus |
| place | paikka |
| plant | kasvi |
| punctuation | välimerkit |
| rightwards_arrows | oikealle osoittavat nuolet |
| sign_standard_symbols | vakiosymboli |
| small_form_variant | vähäiset muotovariantit |
| smiley | hymiö |
| smileys_people | hymiöt ja ihmiset |
| south_asian_scripts | eteläaasialaiset kirjoitusjärjestelmät |
| southeast_asian_scripts | kaakkoisaasialaiset kirjoitusjärjestelmät |
| spacing | välistys |
| sport | urheilu |
| symbols | symbolit |
| technical_symbols | tekniset symbolit |
| tone_marks | toonimerkit |
| travel | matkustus |
| travel_places | matkustus ja paikat |
| upwards_arrows | ylöspäin osoittavat nuolet |
| variant_forms | varianttimuodot |
| vocalic_jamo | jamo-vokaalielementit |
| weather | sää |
| western_asian_scripts | länsiaasialaiset kirjoitusjärjestelmät |
| whitespace | tyhjämerkki |

## Font stuff

| Font feature | Name |
| ------------ | ---- |
| "axis" ital | kursivoitu |
| "axis" opsz | optinen koko |
| "axis" slnt | kallistus |
| "axis" wdth | leveys |
| "axis" wght | paksuus |
| "style" ital1 | kursiivi |
| "style" opsz18 | otsikko |
| "style" opsz72 | näyttö |
| "style" opsz144 | juliste |
| "style" slnt-12 | taaksepäin kallistettu |
| "style" slnt0 | pysty |
| "style" slnt12 | vino |
| "style" slnt24 | extravino |
| "style" wdth50 | ultrakapea |
| "style" wdth50 | ultratiivis |
| "style" wdth62.5 | extrakapea |
| "style" wdth62.5 | extratiivis |
| "style" wdth75 | kavennettu |
| "style" wdth75 | pakattu |
| "style" wdth75 | kapea |
| "style" wdth87.5 | semikapea |
| "style" wdth100 | normaali |
| "style" wdth112.5 | semilaaja |
| "style" wdth125 | laajennettu |
| "style" wdth125 | leveä |
| "style" wdth150 | extralaaja |
| "style" wdth150 | extraleveä |
| "style" wdth200 | ultralaaja |
| "style" wght100 | kapea |
| "style" wght200 | extraohut |
| "style" wght200 | ultraohut |
| "style" wght300 | ohut |
| "style" wght350 | semiohut |
| "style" wght380 | kirja |
| "style" wght400 | normaali |
| "style" wght500 | keskipaksu |
| "style" wght600 | semilihava |
| "style" wght600 | demilihava |
| "style" wght700 | lihavoitu |
| "style" wght800 | extralihava |
| "style" wght800 | ultralihava |
| "style" wght900 | musta |
| "style" wght900 | paksu |
| "style" wght950 | extramusta |
| "style" wght950 | ultrapaksu |
| "style" wght950 | ultramusta |
| "feature" afrc | pystysuuntaiset murtoluvut |
| "feature" cpsp | versaalivälistys |
| "feature" dlig | valinnaiset ligatuurit |
| "feature" frac | vinoviivaiset murtoluvut |
| "feature" lnum | otsikkonumerot |
| "feature" onum | gemenanumerot |
| "feature" ordn | järjestysluvut |
| "feature" pnum | suhteelliset numerot |
| "feature" smcp | kapiteelit |
| "feature" tnum | sarkautuvat numerot |
| "feature" zero | lävistetty nolla |
