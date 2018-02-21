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
| month 1 | tammik. |
| month 2 | helmik. |
| month 3 | maalisk. |
| month 4 | huhtik. |
| month 5 | toukok. |
| month 6 | kesäk. |
| month 7 | heinäk. |
| month 8 | elok. |
| month 9 | syysk. |
| month 10 | lokak. |
| month 11 | marrask. |
| month 12 | jouluk. |
| month 1 | T |
| month 2 | H |
| month 3 | M |
| month 4 | H |
| month 5 | T |
| month 6 | K |
| month 7 | H |
| month 8 | E |
| month 9 | S |
| month 10 | L |
| month 11 | M |
| month 12 | J |
| month 1 | tammikuuta |
| month 2 | helmikuuta |
| month 3 | maaliskuuta |
| month 4 | huhtikuuta |
| month 5 | toukokuuta |
| month 6 | kesäkuuta |
| month 7 | heinäkuuta |
| month 8 | elokuuta |
| month 9 | syyskuuta |
| month 10 | lokakuuta |
| month 11 | marraskuuta |
| month 12 | joulukuuta |
| month 1 | tammi |
| month 2 | helmi |
| month 3 | maalis |
| month 4 | huhti |
| month 5 | touko |
| month 6 | kesä |
| month 7 | heinä |
| month 8 | elo |
| month 9 | syys |
| month 10 | loka |
| month 11 | marras |
| month 12 | joulu |
| month 1 | T |
| month 2 | H |
| month 3 | M |
| month 4 | H |
| month 5 | T |
| month 6 | K |
| month 7 | H |
| month 8 | E |
| month 9 | S |
| month 10 | L |
| month 11 | M |
| month 12 | J |
| month 1 | tammikuu |
| month 2 | helmikuu |
| month 3 | maaliskuu |
| month 4 | huhtikuu |
| month 5 | toukokuu |
| month 6 | kesäkuu |
| month 7 | heinäkuu |
| month 8 | elokuu |
| month 9 | syyskuu |
| month 10 | lokakuu |
| month 11 | marraskuu |
| month 12 | joulukuu |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | P |
| (week)day sat | L |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | sunnuntaina |
| (week)day mon | maanantaina |
| (week)day tue | tiistaina |
| (week)day wed | keskiviikkona |
| (week)day thu | torstaina |
| (week)day fri | perjantaina |
| (week)day sat | lauantaina |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | P |
| (week)day sat | L |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | sunnuntai |
| (week)day mon | maanantai |
| (week)day tue | tiistai |
| (week)day wed | keskiviikko |
| (week)day thu | torstai |
| (week)day fri | perjantai |
| (week)day sat | lauantai |
| quarter 1 | 1. nelj. |
| quarter 2 | 2. nelj. |
| quarter 3 | 3. nelj. |
| quarter 4 | 4. nelj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. neljännes |
| quarter 2 | 2. neljännes |
| quarter 3 | 3. neljännes |
| quarter 4 | 4. neljännes |
| quarter 1 | 1. nelj. |
| quarter 2 | 2. nelj. |
| quarter 3 | 3. nelj. |
| quarter 4 | 4. nelj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. neljännes |
| quarter 2 | 2. neljännes |
| quarter 3 | 3. neljännes |
| quarter 4 | 4. neljännes |
| period of day midnight | keskiyöllä |
| period of day am | ap. |
| period of day noon | keskip. |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | aamup. |
| period of day afternoon1 | iltap. |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | ky. |
| period of day am | ap. |
| period of day noon | kp. |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | ap. |
| period of day afternoon1 | ip. |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | keskiyöllä |
| period of day am | ap. |
| period of day noon | keskipäivällä |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | aamupäivällä |
| period of day afternoon1 | iltapäivällä |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | keskiyö |
| period of day am | ap. |
| period of day noon | keskip. |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | aamup. |
| period of day afternoon1 | iltap. |
| period of day evening1 | ilta |
| period of day night1 | yö |
| period of day midnight | ky. |
| period of day am | ap. |
| period of day noon | kp. |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | ap. |
| period of day afternoon1 | ip. |
| period of day evening1 | ilta |
| period of day night1 | yö |
| period of day midnight | keskiyö |
| period of day am | ap. |
| period of day noon | keskipäivä |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | aamupäivä |
| period of day afternoon1 | iltapäivä |
| period of day evening1 | ilta |
| period of day night1 | yö |
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
| date format | `cccc d. MMMM y` |
| date format | `d. MMMM y` |
| date format | `d.M.y` |
| date format | `d.M.y` |
| time format | `H.mm.ss zzzz` |
| time format | `H.mm.ss z` |
| time format | `H.mm.ss` |
| time format | `H.mm` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} {0}` |
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
| date format | `cccc d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} {0}` |
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

|  | euro |
| one | euro |
| other | euroa |
|  symbol | € |
| narrow symbol | € |

### Datetime patterns

(1 needed)

| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} {0}` |
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

| Europe/Helsinki | Helsinki |
| `FI` | Suomi |

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

kieli: {0}kirjoitusjärjestelmä: {0}alue: {0}

### Context transforms

```
titlecase-firstwordtitlecase-firstword
```

### Character processing for computer systems

| main characters | `[a b c d e f g h i j k l m n o p q r s š t u v w x y z ž å ä ö]` |
| auxiliary characters | `[á à ă â ã ą ā ć č ċ ç ď ð đ é è ê ě ë ė ę ē ğ ǧ ģ ǥ ȟ ħ í î ï İ į ī ı ǩ ķ ĺ ľ ļ ł ń ň ñ ņ ŋ ó ò ô ő õ œ ŕ ř ś ŝ ş ș ß ť ţ ț ŧ ú ù û ů ű ų ū ý ÿ ü ź ż ʒ ǯ þ æ ø]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S T U V W X Y Z Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
final ellipsis: `{0}…`
initial ellipsis: `…{0}`
medial ellipsis: `{0}…{1}`
word-final ellipsis: `{0}…`
word-initial ellipsis: `…{0}`
word-medial ellipsis: `{0}…{1}`
More information characters: `?`
Lenient parsing stuff: - is treated same as `[\--/]`
: is treated same as `[\:∶]`
Lenient parsing stuff: . is treated same as `[.․。︒﹒．｡]`
$ is treated same as `[\$﹩＄$]`
£ is treated same as `[£₤]`
₹ is treated same as `[₨₹{Rp}{Rs}]`
Lenient parsing stuff: - is treated same as `[\-‒⁻₋−➖﹣－]`
, is treated same as `[,،٫、︐︑﹐﹑，､]`
+ is treated same as `[+⁺₊➕﬩﹢＋]`
Lenient parsing stuff: , is treated same as `[,٫︐﹐，]`
. is treated same as `[.․﹒．｡]`
Delimiters:
Quotation start character: ”
Quotation end character: ”
Secondary yquotation start character: ’
Secondary quotation end character: ’

## Calendar data

#### buddhist calendar

| ID-stuff | values |
| -------- | ------ |
| era | buddhalainen aika |
| era | BE |
| era | BE |
| date format | `cccc d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |
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
| date format | `cccc d.M.y` |
| date format | `d.M.y` |
| date format | `d.M.y` |
| date format | `d.M.y` |
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
| month 1 | thoutkuuta |
| month 2 | paopikuuta |
| month 3 | hathorkuuta |
| month 4 | koiakkuuta |
| month 5 | tobikuuta |
| month 6 | meshirkuuta |
| month 7 | paremhatkuuta |
| month 8 | paremoudekuuta |
| month 9 | pashonskuuta |
| month 10 | paonikuuta |
| month 11 | epipkuuta |
| month 12 | mesorikuuta |
| month 13 | pi-kogi-enavotkuuta |
| month 1 | thoutkuuta |
| month 2 | paopikuuta |
| month 3 | hathorkuuta |
| month 4 | koiakkuuta |
| month 5 | tobikuuta |
| month 6 | meshirkuuta |
| month 7 | paremhatkuuta |
| month 8 | paremoudekuuta |
| month 9 | pashonskuuta |
| month 10 | paonikuuta |
| month 11 | epipkuuta |
| month 12 | mesorikuuta |
| month 13 | pi-kogi-enavotkuuta |
| month 1 | thout |
| month 2 | paopi |
| month 3 | hathor |
| month 4 | koiak |
| month 5 | toba |
| month 6 | meshir |
| month 7 | paremhat |
| month 8 | paremoude |
| month 9 | pashons |
| month 10 | paoni |
| month 11 | epip |
| month 12 | mesori |
| month 13 | pi kogi enavot |
| month 1 | thoutkuu |
| month 2 | paopikuu |
| month 3 | hathorkuu |
| month 4 | koiakkuu |
| month 5 | tobikuu |
| month 6 | meshirkuu |
| month 7 | paremhatkuu |
| month 8 | paremoudekuu |
| month 9 | pashonskuu |
| month 10 | paonikuu |
| month 11 | epipkuu |
| month 12 | mesorikuu |
| month 13 | pi-kogi-enavotkuu |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |

#### ethiopic calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | mäskärämkuuta |
| month 2 | ṭəqəmtkuuta |
| month 3 | ḫədarkuuta |
| month 4 | taḫśaśkuuta |
| month 5 | ṭərrkuuta |
| month 6 | yäkatitkuuta |
| month 7 | mägabitkuuta |
| month 8 | miyazyakuuta |
| month 9 | gənbotkuuta |
| month 10 | sänekuuta |
| month 11 | ḥamlekuuta |
| month 12 | nähasekuuta |
| month 13 | ṗagumenkuuta |
| month 1 | mäskärämkuuta |
| month 2 | ṭəqəmtkuuta |
| month 3 | ḫədarkuuta |
| month 4 | taḫśaśkuuta |
| month 5 | ṭərrkuuta |
| month 6 | yäkatitkuuta |
| month 7 | mägabitkuuta |
| month 8 | miyazyakuuta |
| month 9 | gənbotkuuta |
| month 10 | sänekuuta |
| month 11 | ḥamlekuuta |
| month 12 | nähasekuuta |
| month 13 | ṗagumenkuuta |
| month 1 | mäskärämkuu |
| month 2 | ṭəqəmtkuu |
| month 3 | ḫədarkuu |
| month 4 | taḫśaśkuu |
| month 5 | ṭərrkuu |
| month 6 | yäkatitkuu |
| month 7 | mägabitkuu |
| month 8 | miyazyakuu |
| month 9 | gənbotkuu |
| month 10 | sänekuu |
| month 11 | ḥamlekuu |
| month 12 | nähasekuu |
| month 13 | ṗagumenkuu |
| month 1 | mäskärämkuu |
| month 2 | ṭəqəmtkuu |
| month 3 | ḫədarkuu |
| month 4 | taḫśaśkuu |
| month 5 | ṭərrkuu |
| month 6 | yäkatitkuu |
| month 7 | mägabitkuu |
| month 8 | miyazyakuu |
| month 9 | gənbotkuu |
| month 10 | sänekuu |
| month 11 | ḥamlekuu |
| month 12 | nähasekuu |
| month 13 | ṗagumenkuu |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `cccc d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} {0}` |
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
| month 1 | tammik. |
| month 2 | helmik. |
| month 3 | maalisk. |
| month 4 | huhtik. |
| month 5 | toukok. |
| month 6 | kesäk. |
| month 7 | heinäk. |
| month 8 | elok. |
| month 9 | syysk. |
| month 10 | lokak. |
| month 11 | marrask. |
| month 12 | jouluk. |
| month 1 | T |
| month 2 | H |
| month 3 | M |
| month 4 | H |
| month 5 | T |
| month 6 | K |
| month 7 | H |
| month 8 | E |
| month 9 | S |
| month 10 | L |
| month 11 | M |
| month 12 | J |
| month 1 | tammikuuta |
| month 2 | helmikuuta |
| month 3 | maaliskuuta |
| month 4 | huhtikuuta |
| month 5 | toukokuuta |
| month 6 | kesäkuuta |
| month 7 | heinäkuuta |
| month 8 | elokuuta |
| month 9 | syyskuuta |
| month 10 | lokakuuta |
| month 11 | marraskuuta |
| month 12 | joulukuuta |
| month 1 | tammi |
| month 2 | helmi |
| month 3 | maalis |
| month 4 | huhti |
| month 5 | touko |
| month 6 | kesä |
| month 7 | heinä |
| month 8 | elo |
| month 9 | syys |
| month 10 | loka |
| month 11 | marras |
| month 12 | joulu |
| month 1 | T |
| month 2 | H |
| month 3 | M |
| month 4 | H |
| month 5 | T |
| month 6 | K |
| month 7 | H |
| month 8 | E |
| month 9 | S |
| month 10 | L |
| month 11 | M |
| month 12 | J |
| month 1 | tammikuu |
| month 2 | helmikuu |
| month 3 | maaliskuu |
| month 4 | huhtikuu |
| month 5 | toukokuu |
| month 6 | kesäkuu |
| month 7 | heinäkuu |
| month 8 | elokuu |
| month 9 | syyskuu |
| month 10 | lokakuu |
| month 11 | marraskuu |
| month 12 | joulukuu |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | P |
| (week)day sat | L |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | sunnuntaina |
| (week)day mon | maanantaina |
| (week)day tue | tiistaina |
| (week)day wed | keskiviikkona |
| (week)day thu | torstaina |
| (week)day fri | perjantaina |
| (week)day sat | lauantaina |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | P |
| (week)day sat | L |
| (week)day sun | su |
| (week)day mon | ma |
| (week)day tue | ti |
| (week)day wed | ke |
| (week)day thu | to |
| (week)day fri | pe |
| (week)day sat | la |
| (week)day sun | sunnuntai |
| (week)day mon | maanantai |
| (week)day tue | tiistai |
| (week)day wed | keskiviikko |
| (week)day thu | torstai |
| (week)day fri | perjantai |
| (week)day sat | lauantai |
| quarter 1 | 1. nelj. |
| quarter 2 | 2. nelj. |
| quarter 3 | 3. nelj. |
| quarter 4 | 4. nelj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. neljännes |
| quarter 2 | 2. neljännes |
| quarter 3 | 3. neljännes |
| quarter 4 | 4. neljännes |
| quarter 1 | 1. nelj. |
| quarter 2 | 2. nelj. |
| quarter 3 | 3. nelj. |
| quarter 4 | 4. nelj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. neljännes |
| quarter 2 | 2. neljännes |
| quarter 3 | 3. neljännes |
| quarter 4 | 4. neljännes |
| period of day midnight | keskiyöllä |
| period of day am | ap. |
| period of day noon | keskip. |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | aamup. |
| period of day afternoon1 | iltap. |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | ky. |
| period of day am | ap. |
| period of day noon | kp. |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | ap. |
| period of day afternoon1 | ip. |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | keskiyöllä |
| period of day am | ap. |
| period of day noon | keskipäivällä |
| period of day pm | ip. |
| period of day morning1 | aamulla |
| period of day morning2 | aamupäivällä |
| period of day afternoon1 | iltapäivällä |
| period of day evening1 | illalla |
| period of day night1 | yöllä |
| period of day midnight | keskiyö |
| period of day am | ap. |
| period of day noon | keskip. |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | aamup. |
| period of day afternoon1 | iltap. |
| period of day evening1 | ilta |
| period of day night1 | yö |
| period of day midnight | ky. |
| period of day am | ap. |
| period of day noon | kp. |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | ap. |
| period of day afternoon1 | ip. |
| period of day evening1 | ilta |
| period of day night1 | yö |
| period of day midnight | keskiyö |
| period of day am | ap. |
| period of day noon | keskipäivä |
| period of day pm | ip. |
| period of day morning1 | aamu |
| period of day morning2 | aamupäivä |
| period of day afternoon1 | iltapäivä |
| period of day evening1 | ilta |
| period of day night1 | yö |
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
| date format | `cccc d. MMMM y` |
| date format | `d. MMMM y` |
| date format | `d.M.y` |
| date format | `d.M.y` |
| time format | `H.mm.ss zzzz` |
| time format | `H.mm.ss z` |
| time format | `H.mm.ss` |
| time format | `H.mm` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} 'klo' {0}` |
| datetime format | `{1} {0}` |
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
| month 1 | tišrí |
| month 2 | hešván |
| month 3 | kislév |
| month 4 | tevét |
| month 5 | ševát |
| month 6 | adár I |
| month 7 | adár |
| month 7 | adár II |
| month 8 | nisán |
| month 9 | ijjár |
| month 10 | siván |
| month 11 | tammúz |
| month 12 | ab |
| month 13 | elúl |
| month 1 | tišríkuuta |
| month 2 | hešvánkuuta |
| month 3 | kislévkuuta |
| month 4 | tevétkuuta |
| month 5 | ševátkuuta |
| month 6 | adárkuuta I |
| month 7 | adárkuuta |
| month 7 | adárkuuta II |
| month 8 | nisánkuuta |
| month 9 | ijjárkuuta |
| month 10 | sivánkuuta |
| month 11 | tammúzkuuta |
| month 12 | abkuuta |
| month 13 | elúlkuuta |
| month 1 | tišrí |
| month 2 | hešván |
| month 3 | kislév |
| month 4 | tevét |
| month 5 | ševát |
| month 6 | adár I |
| month 7 | adár |
| month 7 | adár II |
| month 8 | nisán |
| month 9 | ijjár |
| month 10 | siván |
| month 11 | tammúz |
| month 12 | ab |
| month 13 | elúl |
| month 1 | T |
| month 2 | H |
| month 3 | K |
| month 4 | T |
| month 5 | S |
| month 6 | A |
| month 7 | A |
| month 7 | A |
| month 8 | N |
| month 9 | I |
| month 10 | S |
| month 11 | T |
| month 12 | A |
| month 13 | E |
| month 1 | tišríkuu |
| month 2 | hešvánkuu |
| month 3 | kislévkuu |
| month 4 | tevétkuu |
| month 5 | ševátkuu |
| month 6 | adárkuu I |
| month 7 | adárkuu |
| month 7 | adárkuu II |
| month 8 | nisánkuu |
| month 9 | ijjárkuu |
| month 10 | sivánkuu |
| month 11 | tammúzkuu |
| month 12 | abkuu |
| month 13 | elúlkuu |
| era | Anno Mundi |
| era | AM |
| era | AM |

#### indian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | chaitrakuuta |
| month 2 | vaisakhakuuta |
| month 3 | jyaisthakuuta |
| month 4 | asadhakuuta |
| month 5 | sravanakuuta |
| month 6 | bhadrakuuta |
| month 7 | asvinakuuta |
| month 8 | kartikakuuta |
| month 9 | agrahayanakuuta |
| month 10 | pausakuuta |
| month 11 | maghakuuta |
| month 12 | phalgunakuuta |
| month 1 | chaitrakuuta |
| month 2 | vaisakhakuuta |
| month 3 | jyaisthakuuta |
| month 4 | asadhakuuta |
| month 5 | sravanakuuta |
| month 6 | bhadrakuuta |
| month 7 | asvinakuuta |
| month 8 | kartikakuuta |
| month 9 | agrahayanakuuta |
| month 10 | pausakuuta |
| month 11 | maghakuuta |
| month 12 | phalgunakuuta |
| month 1 | chaitra |
| month 2 | vaisakha |
| month 3 | jyaistha |
| month 4 | asadha |
| month 5 | sravana |
| month 6 | bhadra |
| month 7 | asvina |
| month 8 | kartika |
| month 9 | agrahayana |
| month 10 | pausa |
| month 11 | magha |
| month 12 | phalguna |
| month 1 | chaitrakuu |
| month 2 | vaisakhakuu |
| month 3 | jyaisthakuu |
| month 4 | asadhakuu |
| month 5 | sravanakuu |
| month 6 | bhadrakuu |
| month 7 | asvinakuu |
| month 8 | kartikakuu |
| month 9 | agrahayanakuu |
| month 10 | pausakuu |
| month 11 | maghakuu |
| month 12 | phalgunakuu |
| era | Saka-ajanlaskua |
| era | Saka |
| era | Saka |

#### islamic calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | muharram |
| month 2 | safar |
| month 3 | rabi’ al-awwal |
| month 4 | rabi’ al-akhir |
| month 5 | džumada-l-ula |
| month 6 | džumada-l-akhira |
| month 7 | radžab |
| month 8 | ša’ban |
| month 9 | ramadan |
| month 10 | šawwal |
| month 11 | dhu-l-qa’da |
| month 12 | dhu-l-hiddža |
| month 1 | muharram |
| month 2 | safar |
| month 3 | rabi’ al-awwal |
| month 4 | rabi’ al-akhir |
| month 5 | džumada-l-ula |
| month 6 | džumada-l-akhira |
| month 7 | radžab |
| month 8 | ša’ban |
| month 9 | ramadan |
| month 10 | šawwal |
| month 11 | dhu-l-qa’da |
| month 12 | dhu-l-hiddža |
| era | hidžran jälkeen |
| era | AH |
| era | AH |

#### japanese calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `cccc d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |

#### persian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | farvardinkuuta |
| month 2 | ordibeheštkuuta |
| month 3 | khordadkuuta |
| month 4 | tirkuuta |
| month 5 | mordadkuuta |
| month 6 | šahrivarkuuta |
| month 7 | mehrkuuta |
| month 8 | abankuuta |
| month 9 | azarkuuta |
| month 10 | deykuuta |
| month 11 | bahmankuuta |
| month 12 | esfandkuuta |
| month 1 | farvardinkuuta |
| month 2 | ordibeheštkuuta |
| month 3 | khordadkuuta |
| month 4 | tirkuuta |
| month 5 | mordadkuuta |
| month 6 | šahrivarkuuta |
| month 7 | mehrkuuta |
| month 8 | abankuuta |
| month 9 | azarkuuta |
| month 10 | deykuuta |
| month 11 | bahmankuuta |
| month 12 | esfandkuuta |
| month 1 | farvardin |
| month 2 | ordibehešt |
| month 3 | khordad |
| month 4 | tir |
| month 5 | mordad |
| month 6 | šahrivar |
| month 7 | mehr |
| month 8 | aban |
| month 9 | azar |
| month 10 | dey |
| month 11 | bahman |
| month 12 | esfand |
| month 1 | farvardinkuu |
| month 2 | ordibeheštkuu |
| month 3 | khordadkuu |
| month 4 | tirkuu |
| month 5 | mordadkuu |
| month 6 | šahrivarkuu |
| month 7 | mehrkuu |
| month 8 | abankuu |
| month 9 | azarkuu |
| month 10 | deykuu |
| month 11 | bahmankuu |
| month 12 | esfandkuu |
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

|  | aikakausi |
|  | aikakausi |
|  | aikakausi |
|  | vuosi |
viime vuonnatänä vuonnaensi vuonna{0} vuoden päästä{0} vuoden päästä{0} vuosi sitten{0} vuotta sitten
|  | v |
viime vtänä vensi v{0} v päästä{0} v päästä{0} v sitten{0} v sitten
|  | v |
viime vtänä vensi v{0} v päästä{0} v päästä{0} v sitten{0} v sitten
|  | neljännesvuosi |
viime neljännesvuonnatänä neljännesvuonnaensi neljännesvuonna{0} neljännesvuoden päästä{0} neljännesvuoden päästä{0} neljännesvuosi sitten{0} neljännesvuotta sitten
|  | neljännes |
viime neljänneksenätänä neljänneksenäensi neljänneksenä{0} neljänneksen päästä{0} neljänneksen päästä{0} neljännes sitten{0} neljännestä sitten
|  | nelj. |
viime nelj.tänä nelj.ensi nelj.{0} nelj. päästä{0} nelj. päästä{0} nelj. sitten{0} nelj. sitten
|  | kuukausi |
viime kuussatässä kuussaensi kuussa{0} kuukauden päästä{0} kuukauden päästä{0} kuukausi sitten{0} kuukautta sitten
|  | kk |
viime kktässä kkensi kk{0} kk päästä{0} kk päästä{0} kk sitten{0} kk sitten
|  | kk |
viime kktässä kkensi kk{0} kk päästä{0} kk päästä{0} kk sitten{0} kk sitten
|  | viikko |
viime viikollatällä viikollaensi viikolla{0} viikon päästä{0} viikon päästä{0} viikko sitten{0} viikkoa sittenpäivän {0} viikolla
|  | vk |
viime vktällä vkensi vk{0} vk päästä{0} vk päästä{0} vk sitten{0} vk sittenpäivän {0} viikolla
|  | vk |
viime vktällä vkensi vk{0} vk päästä{0} vk päästä{0} vk sitten{0} vk sittenpäivän {0} viikolla
|  | kuukauden viikko |
|  | kuukauden vk |
|  | kuukauden vk |
|  | päivä |
toissa päivänäeilentänäänhuomennaylihuomenna{0} päivän päästä{0} päivän päästä{0} päivä sitten{0} päivää sitten
|  | pv |
toissap.eilentänäänhuom.ylihuom.{0} pv päästä{0} pv päästä{0} pv sitten{0} pv sitten
|  | pv |
toissap.eilentänäänhuom.ylihuom.{0} pv päästä{0} pv päästä{0} pv sitten{0} pv sitten
|  | vuodenpäivä |
|  | vuodenpv |
|  | vuodenpv |
|  | viikonpäivä |
|  | viikonpäivä |
|  | viikonpäivä |
|  | kuukauden viikonpäivä |
|  | kuukauden vk päivä |
|  | kuukauden vk päivä |
viime sunnuntainatänä sunnuntainaensi sunnuntaina{0} sunnuntain päästä{0} sunnuntain päästä{0} sunnuntai sitten{0} sunnuntaita sittenviime sutänä suensi su{0} su päästä{0} su päästä{0} su sitten{0} su sittenviime sutänä suensi su{0} su päästä{0} su päästä{0} su sitten{0} su sittenviime maanantainatänä maanantainaensi maanantaina{0} maanantain päästä{0} maanantain päästä{0} maanantai sitten{0} maanantaita sittenviime matänä maensi ma{0} ma päästä{0} ma päästä{0} ma sitten{0} ma sittenviime matänä maensi ma{0} ma päästä{0} ma päästä{0} ma sitten{0} ma sittenviime tiistainatänä tiistainaensi tiistaina{0} tiistain päästä{0} tiistain päästä{0} tiistai sitten{0} tiistaita sittenviime titänä tiensi ti{0} ti päästä{0} ti päästä{0} ti sitten{0} ti sittenviime titänä tiensi ti{0} ti päästä{0} ti päästä{0} ti sitten{0} ti sittenviime keskiviikkonatänä keskiviikkonaensi keskiviikkona{0} keskiviikon päästä{0} keskiviikon päästä{0} keskiviikko sitten{0} keskiviikkoa sittenviime ketänä keensi ke{0} ke päästä{0} ke päästä{0} ke sitten{0} ke sittenviime ketänä keensi ke{0} ke päästä{0} ke päästä{0} ke sitten{0} ke sittenviime torstainatänä torstainaensi torstaina{0} torstain päästä{0} torstain päästä{0} torstai sitten{0} torstaita sittenviime totänä toensi to{0} to päästä{0} to päästä{0} to sitten{0} to sittenviime totänä toensi to{0} to päästä{0} to päästä{0} to sitten{0} to sittenviime perjantainatänä perjantainaensi perjantaina{0} perjantain päästä{0} perjantain päästä{0} perjantai sitten{0} perjantaita sittenviime petänä peensi pe{0} pe päästä{0} pe päästä{0} pe sitten{0} pe sittenviime petänä peensi pe{0} pe päästä{0} pe päästä{0} pe sitten{0} pe sittenviime lauantainatänä lauantainaensi lauantaina{0} lauantain päästä{0} lauantain päästä{0} lauantai sitten{0} lauantaita sittenviime latänä laensi la{0} la päästä{0} la päästä{0} la sitten{0} la sittenviime latänä laensi la{0} la päästä{0} la päästä{0} la sitten{0} la sitten
|  | vuorokaudenaika |
|  | vuorokaudenaika |
|  | vuorokaudenaika |
|  | tunti |
tämän tunnin aikana{0} tunnin päästä{0} tunnin päästä{0} tunti sitten{0} tuntia sitten
|  | t |
tunnin sisällä{0} t päästä{0} t päästä{0} t sitten{0} t sitten
|  | t |
tunnin sisällä{0} t päästä{0} t päästä{0} t sitten{0} t sitten
|  | minuutti |
tämän minuutin aikana{0} minuutin päästä{0} minuutin päästä{0} minuutti sitten{0} minuuttia sitten
|  | min |
minuutin sisällä{0} min päästä{0} min päästä{0} min sitten{0} min sitten
|  | min |
minuutin sisällä{0} min päästä{0} min päästä{0} min sitten{0} min sitten
|  | sekunti |
nyt{0} sekunnin päästä{0} sekunnin päästä{0} sekunti sitten{0} sekuntia sitten
|  | s |
nyt{0} s päästä{0} s päästä{0} s sitten{0} s sitten
|  | s |
nyt{0} s päästä{0} s päästä{0} s sitten{0} s sitten
|  | aikavyöhyke |
|  | aikavyöhyke |
|  | aikavyöhyke |

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
| Europe/London | Britannian kesäaikaLontoo |
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
| Europe/Dublin | Irlannin kesäaikaDublin |
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
| Acre | Acren aikaAcren normaaliaikaAcren kesäaika |
| Afghanistan | Afganistanin aika |
| Africa_Central | Keski-Afrikan aika |
| Africa_Eastern | Itä-Afrikan aika |
| Africa_Southern | Etelä-Afrikan aika |
| Africa_Western | Länsi-Afrikan aikaLänsi-Afrikan normaaliaikaLänsi-Afrikan kesäaika |
| Alaska | Alaskan aikaAlaskan normaaliaikaAlaskan kesäaika |
| Almaty | Almatyn aikaAlmatyn normaaliaikaAlmatyn kesäaika |
| Amazon | Amazonin aikaAmazonin normaaliaikaAmazonin kesäaika |
| America_Central | Yhdysvaltain keskinen aikaYhdysvaltain keskinen normaaliaikaYhdysvaltain keskinen kesäaika |
| America_Eastern | Yhdysvaltain itäinen aikaYhdysvaltain itäinen normaaliaikaYhdysvaltain itäinen kesäaika |
| America_Mountain | Kalliovuorten aikaKalliovuorten normaaliaikaKalliovuorten kesäaika |
| America_Pacific | Yhdysvaltain Tyynenmeren aikaYhdysvaltain Tyynenmeren normaaliaikaYhdysvaltain Tyynenmeren kesäaika |
| Anadyr | Anadyrin aikaAnadyrin normaaliaikaAnadyrin kesäaika |
| Apia | Apian aikaApian normaaliaikaApian kesäaika |
| Aqtau | Aqtaw’n aikaAqtaw’n normaaliaikaAqtaw’n kesäaika |
| Aqtobe | Aqtöben aikaAqtöben normaaliaikaAqtöben kesäaika |
| Arabian | Saudi-Arabian aikaSaudi-Arabian normaaliaikaSaudi-Arabian kesäaika |
| Argentina | Argentiinan aikaArgentiinan normaaliaikaArgentiinan kesäaika |
| Argentina_Western | Länsi-Argentiinan aikaLänsi-Argentiinan normaaliaikaLänsi-Argentiinan kesäaika |
| Armenia | Armenian aikaArmenian normaaliaikaArmenian kesäaika |
| Atlantic | Kanadan Atlantin aikaKanadan Atlantin normaaliaikaKanadan Atlantin kesäaika |
| Australia_Central | Keski-Australian aikaKeski-Australian normaaliaikaKeski-Australian kesäaika |
| Australia_CentralWestern | Läntisen Keski-Australian aikaLäntisen Keski-Australian normaaliaikaLäntisen Keski-Australian kesäaika |
| Australia_Eastern | Itä-Australian aikaItä-Australian normaaliaikaItä-Australian kesäaika |
| Australia_Western | Länsi-Australian aikaLänsi-Australian normaaliaikaLänsi-Australian kesäaika |
| Azerbaijan | Azerbaidžanin aikaAzerbaidžanin normaaliaikaAzerbaidžanin kesäaika |
| Azores | Azorien aikaAzorien normaaliaikaAzorien kesäaika |
| Bangladesh | Bangladeshin aikaBangladeshin normaaliaikaBangladeshin kesäaika |
| Bhutan | Bhutanin aika |
| Bolivia | Bolivian aika |
| Brasilia | Brasilian aikaBrasilian normaaliaikaBrasilian kesäaika |
| Brunei | Brunein aika |
| Cape_Verde | Kap Verden aikaKap Verden normaaliaikaKap Verden kesäaika |
| Casey | Caseyn aika |
| Chamorro | Tšamorron aika |
| Chatham | Chathamin aikaChathamin normaaliaikaChathamin kesäaika |
| Chile | Chilen aikaChilen normaaliaikaChilen kesäaika |
| China | Kiinan aikaKiinan normaaliaikaKiinan kesäaika |
| Choibalsan | Tšoibalsan aikaTšoibalsan normaaliaikaTšoibalsan kesäaika |
| Christmas | Joulusaaren aika |
| Cocos | Kookossaarten aika |
| Colombia | Kolumbian aikaKolumbian normaaliaikaKolumbian kesäaika |
| Cook | Cookinsaarten aikaCookinsaarten normaaliaikaCookinsaarten kesäaika |
| Cuba | Kuuban aikaKuuban normaaliaikaKuuban kesäaika |
| Davis | Davisin aika |
| DumontDUrville | Dumont d’Urvillen aika |
| East_Timor | Itä-Timorin aika |
| Easter | Pääsiäissaaren aikaPääsiäissaaren normaaliaikaPääsiäissaaren kesäaika |
| Ecuador | Ecuadorin aika |
| Europe_Central | Keski-Euroopan aikaKeski-Euroopan normaaliaikaKeski-Euroopan kesäaika |
| Europe_Eastern | Itä-Euroopan aikaItä-Euroopan normaaliaikaItä-Euroopan kesäaika |
| Europe_Further_Eastern | Itäisemmän Euroopan aika |
| Europe_Western | Länsi-Euroopan aikaLänsi-Euroopan normaaliaikaLänsi-Euroopan kesäaika |
| Falkland | Falklandinsaarten aikaFalklandinsaarten normaaliaikaFalklandinsaarten kesäaika |
| Fiji | Fidžin aikaFidžin normaaliaikaFidžin kesäaika |
| French_Guiana | Ranskan Guayanan aika |
| French_Southern | Ranskan eteläisten ja antarktisten alueiden aika |
| Galapagos | Galápagossaarten aika |
| Gambier | Gambiersaarten aika |
| Georgia | Georgian aikaGeorgian normaaliaikaGeorgian kesäaika |
| Gilbert_Islands | Gilbertsaarten aika |
| GMT | Greenwichin normaaliaika |
| Greenland_Eastern | Itä-Grönlannin aikaItä-Grönlannin normaaliaikaItä-Grönlannin kesäaika |
| Greenland_Western | Länsi-Grönlannin aikaLänsi-Grönlannin normaaliaikaLänsi-Grönlannin kesäaika |
| Guam | Guamin aika |
| Gulf | Arabiemiirikuntien normaaliaika |
| Guyana | Guyanan aika |
| Hawaii_Aleutian | Havaijin-Aleuttien aikaHavaijin-Aleuttien normaaliaikaHavaijin-Aleuttien kesäaika |
| Hong_Kong | Hongkongin aikaHongkongin normaaliaikaHongkongin kesäaika |
| Hovd | Hovdin aikaHovdin normaaliaikaHovdin kesäaika |
| India | Intian aika |
| Indian_Ocean | Intian valtameren aika |
| Indochina | Indokiinan aika |
| Indonesia_Central | Keski-Indonesian aika |
| Indonesia_Eastern | Itä-Indonesian aika |
| Indonesia_Western | Länsi-Indonesian aika |
| Iran | Iranin aikaIranin normaaliaikaIranin kesäaika |
| Irkutsk | Irkutskin aikaIrkutskin normaaliaikaIrkutskin kesäaika |
| Israel | Israelin aikaIsraelin normaaliaikaIsraelin kesäaika |
| Japan | Japanin aikaJapanin normaaliaikaJapanin kesäaika |
| Kamchatka | Kamtšatkan aikaKamtšatkan normaaliaikaKamtšatkan kesäaika |
| Kazakhstan_Eastern | Itä-Kazakstanin aika |
| Kazakhstan_Western | Länsi-Kazakstanin aika |
| Korea | Korean aikaKorean normaaliaikaKorean kesäaika |
| Kosrae | Kosraen aika |
| Krasnoyarsk | Krasnojarskin aikaKrasnojarskin normaaliaikaKrasnojarskin kesäaika |
| Kyrgystan | Kirgisian aika |
| Lanka | Sri Lankan aika |
| Line_Islands | Linesaarten aika |
| Lord_Howe | Lord Howen aikaLord Howen normaaliaikaLord Howen kesäaika |
| Macau | Macaon aikaMacaon normaaliaikaMacaon kesäaika |
| Macquarie | Macquariensaaren aika |
| Magadan | Magadanin aikaMagadanin normaaliaikaMagadanin kesäaika |
| Malaysia | Malesian aika |
| Maldives | Malediivien aika |
| Marquesas | Marquesassaarten aika |
| Marshall_Islands | Marshallinsaarten aika |
| Mauritius | Mauritiuksen aikaMauritiuksen normaaliaikaMauritiuksen kesäaika |
| Mawson | Mawsonin aika |
| Mexico_Northwest | Luoteis-Meksikon aikaLuoteis-Meksikon normaaliaikaLuoteis-Meksikon kesäaika |
| Mexico_Pacific | Meksikon Tyynenmeren aikaMeksikon Tyynenmeren normaaliaikaMeksikon Tyynenmeren kesäaika |
| Mongolia | Ulan Batorin aikaUlan Batorin normaaliaikaUlan Batorin kesäaika |
| Moscow | Moskovan aikaMoskovan normaaliaikaMoskovan kesäaika |
| Myanmar | Myanmarin aika |
| Nauru | Naurun aika |
| Nepal | Nepalin aika |
| New_Caledonia | Uuden-Kaledonian aikaUuden-Kaledonian normaaliaikaUuden-Kaledonian kesäaika |
| New_Zealand | Uuden-Seelannin aikaUuden-Seelannin normaaliaikaUuden-Seelannin kesäaika |
| Newfoundland | Newfoundlandin aikaNewfoundlandin normaaliaikaNewfoundlandin kesäaika |
| Niue | Niuen aika |
| Norfolk | Norfolkinsaaren aika |
| Noronha | Fernando de Noronhan aikaFernando de Noronhan normaaliaikaFernando de Noronhan kesäaika |
| North_Mariana | Pohjois-Mariaanien aika |
| Novosibirsk | Novosibirskin aikaNovosibirskin normaaliaikaNovosibirskin kesäaika |
| Omsk | Omskin aikaOmskin normaaliaikaOmskin kesäaika |
| Pakistan | Pakistanin aikaPakistanin normaaliaikaPakistanin kesäaika |
| Palau | Palaun aika |
| Papua_New_Guinea | Papua-Uuden-Guinean aika |
| Paraguay | Paraguayn aikaParaguayn normaaliaikaParaguayn kesäaika |
| Peru | Perun aikaPerun normaaliaikaPerun kesäaika |
| Philippines | Filippiinien aikaFilippiinien normaaliaikaFilippiinien kesäaika |
| Phoenix_Islands | Phoenixsaarten aika |
| Pierre_Miquelon | Saint-Pierren ja Miquelonin aikaSaint-Pierren ja Miquelonin normaaliaikaSaint-Pierren ja Miquelonin kesäaika |
| Pitcairn | Pitcairnin aika |
| Ponape | Pohnpein aika |
| Pyongyang | Pjongjangin aika |
| Qyzylorda | Qızılordan aikaQızılordan normaaliaikaQızılordan kesäaika |
| Reunion | Réunionin aika |
| Rothera | Rotheran aika |
| Sakhalin | Sahalinin aikaSahalinin normaaliaikaSahalinin kesäaika |
| Samara | Samaran aikaSamaran normaaliaikaSamaran kesäaika |
| Samoa | Samoan aikaSamoan normaaliaikaSamoan kesäaika |
| Seychelles | Seychellien aika |
| Singapore | Singaporen aika |
| Solomon | Salomonsaarten aika |
| South_Georgia | Etelä-Georgian aika |
| Suriname | Surinamen aika |
| Syowa | Syowan aika |
| Tahiti | Tahitin aika |
| Taipei | Taipein aikaTaipein normaaliaikaTaipein kesäaika |
| Tajikistan | Tadžikistanin aika |
| Tokelau | Tokelaun aika |
| Tonga | Tongan aikaTongan normaaliaikaTongan kesäaika |
| Truk | Chuukin aika |
| Turkmenistan | Turkmenistanin aikaTurkmenistanin normaaliaikaTurkmenistanin kesäaika |
| Tuvalu | Tuvalun aika |
| Uruguay | Uruguayn aikaUruguayn normaaliaikaUruguayn kesäaika |
| Uzbekistan | Uzbekistanin aikaUzbekistanin normaaliaikaUzbekistanin kesäaika |
| Vanuatu | Vanuatun aikaVanuatun normaaliaikaVanuatun kesäaika |
| Venezuela | Venezuelan aika |
| Vladivostok | Vladivostokin aikaVladivostokin normaaliaikaVladivostokin kesäaika |
| Volgograd | Volgogradin aikaVolgogradin normaaliaikaVolgogradin kesäaika |
| Vostok | Vostokin aika |
| Wake | Waken aika |
| Wallis | Wallisin ja Futunan aika |
| Yakutsk | Jakutskin aikaJakutskin normaaliaikaJakutskin kesäaika |
| Yekaterinburg | Jekaterinburgin aikaJekaterinburgin normaaliaikaJekaterinburgin kesäaika |

## Numbers stuff

latnlatn1

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
#,##0.###0 tuhat0 tuhatta00 tuhatta00 tuhatta000 tuhatta000 tuhatta0 miljoona0 miljoonaa00 miljoonaa00 miljoonaa000 miljoonaa000 miljoonaa0 miljardi0 miljardia00 miljardia00 miljardia000 miljardia000 miljardia0 biljoona0 biljoonaa00 biljoonaa00 biljoonaa000 biljoonaa000 biljoonaa0 t'.'0 t'.'00 t'.'00 t'.'000 t'.'000 t'.'0 milj'.'0 milj'.'00 milj'.'00 milj'.'000 milj'.'000 milj'.'0 mrd'.'0 mrd'.'00 mrd'.'00 mrd'.'000 mrd'.'000 mrd'.'0 bilj'.'0 bilj'.'00 bilj'.'00 bilj'.'000 bilj'.'000 bilj'.'#E0#,##0 %#,##0.00 ¤#,##0.00 ¤0 t'.' ¤0 t'.' ¤00 t'.' ¤00 t'.' ¤000 t'.' ¤000 t'.' ¤0 milj'.' ¤0 milj'.' ¤00 milj'.' ¤00 milj'.' ¤000 milj'.' ¤000 milj'.' ¤0 mrd'.' ¤0 mrd'.' ¤00 mrd'.' ¤00 mrd'.' ¤000 mrd'.' ¤000 mrd'.' ¤0 bilj'.' ¤0 bilj'.' ¤00 bilj'.' ¤00 bilj'.' ¤000 bilj'.' ¤000 bilj'.' ¤
| one | {0} {1} |
| other | {0} {1} |

## Currency names

| Code | Name |
| ---- | ---- |
|  | Andorran peseta |
| one | Andorran peseta |
| other | Andorran pesetaa |
|  symbol | ADP |
|  | Arabiemiirikuntien dirhami |
| one | Arabiemiirikuntien dirhami |
| other | Arabiemiirikuntien dirhamia |
|  symbol | AED |
|  | Afganistanin afgaani (1927–2002) |
| one | Afganistanin afgaani (1927–2002) |
| other | Afganistanin afgaania (1927–2002) |
|  symbol | AFA |
|  | Afganistanin afgaani |
| one | Afganistanin afgaani |
| other | Afganistanin afgaania |
|  symbol | AFN |
|  | Albanian lek (1946–1965) |
| one | Albanian lek (1946–1965) |
| other | Albanian lekiä (1946–1965) |
|  symbol | ALK |
|  | Albanian lek |
| one | Albanian lek |
| other | Albanian lekiä |
|  symbol | ALL |
|  | Armenian dram |
| one | Armenian dram |
| other | Armenian dramia |
|  symbol | AMD |
|  | Alankomaiden Antillien guldeni |
| one | Alankomaiden Antillien guldeni |
| other | Alankomaiden Antillien guldenia |
|  symbol | ANG |
|  | Angolan kwanza |
| one | Angolan kwanza |
| other | Angolan kwanzaa |
|  symbol | AOA |
| narrow symbol | AOA |
|  | Angolan kwanza (1977–1991) |
| one | Angolan kwanza (1977–1990) |
| other | Angolan kwanzaa (1977–1990) |
|  symbol | AOK |
|  | Angolan uusi kwanza (1990–2000) |
| one | Angolan uusi kwanza (1990–2000) |
| other | Angolan uutta kwanzaa (1990–2000) |
|  symbol | AON |
|  | Angolan kwanza reajustado (1995–1999) |
| one | Angolan kwanza reajustado (1995–1999) |
| other | Angolan kwanza reajustadoa (1995–1999) |
|  symbol | AOR |
|  | Argentiinan austral |
| one | Argentiinan austral |
| other | Argentiinan australia |
|  symbol | ARA |
|  | Argentiinan ley-peso (1970–1983) |
| one | Argentiinan ley-peso (1970–1983) |
| other | Argentiinan ley-pesoa (1970–1983) |
|  symbol | ARL |
|  | Argentiinan peso (1881–1970) |
| one | Argentiinan peso (1881–1970) |
| other | Argentiinan pesoa (1881–1970) |
|  symbol | ARM |
|  | Argentiinan peso (1983–1985) |
| one | Argentiinan peso (1983–1985) |
| other | Argentiinan pesoa (1983–1985) |
|  symbol | ARP |
|  | Argentiinan peso |
| one | Argentiinan peso |
| other | Argentiinan pesoa |
|  symbol | ARS |
| narrow symbol | ARS |
|  | Itävallan šillinki |
| one | Itävallan šillinki |
| other | Itävallan šillinkiä |
|  symbol | ATS |
|  | Australian dollari |
| one | Australian dollari |
| other | Australian dollaria |
|  symbol | AUD |
| narrow symbol | AUD |
|  | Aruban floriini |
| one | Aruban floriini |
| other | Aruban floriinia |
|  symbol | AWG |
|  | Azerbaidžanin manat (1993–2006) |
| one | Azerbaidžanin manat (1993–2006) |
| other | Azerbaidžanin manatia (1993–2006) |
|  symbol | AZM |
|  | Azerbaidžanin manat |
| one | Azerbaidžanin manat |
| other | Azerbaidžanin manatia |
|  symbol | AZN |
|  | Bosnia-Hertsegovinan dinaari (1992–1994) |
| one | Bosnia-Hertsegovinan dinaari (1992–1994) |
| other | Bosnia-Hertsegovinan dinaaria (1992–1994) |
|  symbol | BAD |
|  | Bosnia-Hertsegovinan vaihdettava markka |
| one | Bosnia-Hertsegovinan vaihdettava markka |
| other | Bosnia-Hertsegovinan vaihdettavaa markkaa |
|  symbol | BAM |
| narrow symbol | BAM |
|  | Bosnia-Hertsegovinan uusi dinaari (1994–1997) |
| one | Bosnia-Hertsegovinan uusi dinaari (1994–1997) |
| other | Bosnia-Hertsegovinan uutta dinaaria (1994–1997) |
|  symbol | BAN |
|  | Barbadosin dollari |
| one | Barbadosin dollari |
| other | Barbadosin dollaria |
|  symbol | BBD |
| narrow symbol | BBD |
|  | Bangladeshin taka |
| one | Bangladeshin taka |
| other | Bangladeshin takaa |
|  symbol | BDT |
| narrow symbol | BDT |
|  | Belgian vaihdettava frangi |
| one | Belgian vaihdettava frangi |
| other | Belgian vaihdettavaa frangia |
|  symbol | BEC |
|  | Belgian frangi |
| one | Belgian frangi |
| other | Belgian frangia |
|  symbol | BEF |
|  | Belgian rahoitusfrangi |
| one | Belgian rahoitusfrangi |
| other | Belgian rahoitusfrangia |
|  symbol | BEL |
|  | Bulgarian kova lev |
| one | Bulgarian kova lev |
| other | Bulgarian kovaa leviä |
|  symbol | BGL |
|  | Bulgarian sosialistinen lev |
| one | Bulgarian sosialistinen lev |
| other | Bulgarian sosialistista leviä |
|  symbol | BGM |
|  | Bulgarian lev |
| one | Bulgarian lev |
| other | Bulgarian leviä |
|  symbol | BGN |
|  | Bulgarian lev (1879–1952) |
| one | Bulgarian lev (1879–1952) |
| other | Bulgarian leviä (1879–1952) |
|  symbol | BGO |
|  | Bahrainin dinaari |
| one | Bahrainin dinaari |
| other | Bahrainin dinaaria |
|  symbol | BHD |
|  | Burundin frangi |
| one | Burundin frangi |
| other | Burundin frangia |
|  symbol | BIF |
|  | Bermudan dollari |
| one | Bermudan dollari |
| other | Bermudan dollaria |
|  symbol | BMD |
| narrow symbol | BMD |
|  | Brunein dollari |
| one | Brunein dollari |
| other | Brunein dollaria |
|  symbol | BND |
| narrow symbol | BND |
|  | Bolivian boliviano |
| one | Bolivian boliviano |
| other | Bolivian bolivianoa |
|  symbol | BOB |
| narrow symbol | BOB |
|  | Bolivian boliviano (1863–1963) |
| one | Bolivian boliviano (1863–1963) |
| other | Bolivian bolivianoa (1863–1963) |
|  symbol | BOL |
|  | Bolivian peso |
| one | Bolivian peso |
| other | Bolivian pesoa |
|  symbol | BOP |
|  | Bolivian mvdol |
| one | Bolivian mvdol |
| other | Bolivian mvdol’ia |
|  symbol | BOV |
|  | Brasilian uusi cruzeiro (1967–1986) |
| one | Brasilian uusi cruzeiro (1967–1986) |
| other | Brasilian uutta cruzeiroa (1967–1986) |
|  symbol | BRB |
|  | Brasilian cruzado (1986–1989) |
| one | Brasilian cruzado (1986–1989) |
| other | Brasilian cruzadoa (1986–1989) |
|  symbol | BRC |
|  | Brasilian cruzeiro (1990–1993) |
| one | Brasilian cruzeiro (1990–1993) |
| other | Brasilian cruzeiroa (1990–1993) |
|  symbol | BRE |
|  | Brasilian real |
| one | Brasilian real |
| other | Brasilian realia |
|  symbol | BRL |
| narrow symbol | BRL |
|  | Brasilian uusi cruzado (1989–1990) |
| one | Brasilian uusi cruzado (1989–1990) |
| other | Brasilian uutta cruzadoa (1989–1990) |
|  symbol | BRN |
|  | Brasilian cruzeiro (1993–1994) |
| one | Brasilian cruzeiro (1993–1994) |
| other | Brasilian cruzeiroa (1993–1994) |
|  symbol | BRR |
|  | Brasilian cruzeiro (1942–1967) |
| one | Brasilian cruzeiro (1942–1967) |
| other | Brasilian cruzeiroa (1942–1967) |
|  symbol | BRZ |
|  | Bahaman dollari |
| one | Bahaman dollari |
| other | Bahaman dollaria |
|  symbol | BSD |
| narrow symbol | BSD |
|  | Bhutanin ngultrum |
| one | Bhutanin ngultrum |
| other | Bhutanin ngultrumia |
|  symbol | BTN |
|  | Burman kyat |
| one | Burman kyat |
| other | Burman kyatia |
|  symbol | BUK |
|  | Botswanan pula |
| one | Botswanan pula |
| other | Botswanan pulaa |
|  symbol | BWP |
| narrow symbol | BWP |
|  | Valko-Venäjän uusi rupla (1994–1999) |
| one | Valko-Venäjän uusi rupla (1994–1999) |
| other | Valko-Venäjän uutta ruplaa (1994–1999) |
|  symbol | BYB |
|  | Valko-Venäjän rupla |
| one | Valko-Venäjän rupla |
| other | Valko-Venäjän ruplaa |
|  symbol | BYN |
| narrow symbol | BYN |
|  | Valko-Venäjän rupla (2000–2016) |
| one | Valko-Venäjän rupla (2000–2016) |
| other | Valko-Venäjän ruplaa (2000–2016) |
|  symbol | BYR |
|  | Belizen dollari |
| one | Belizen dollari |
| other | Belizen dollaria |
|  symbol | BZD |
| narrow symbol | BZD |
|  | Kanadan dollari |
| one | Kanadan dollari |
| other | Kanadan dollaria |
|  symbol | CAD |
| narrow symbol | CAD |
|  | Kongon frangi |
| one | Kongon frangi |
| other | Kongon frangia |
|  symbol | CDF |
|  | Sveitsin WIR-euro |
| one | Sveitsin WIR-euro |
| other | Sveitsin WIR-euroa |
|  symbol | CHE |
|  | Sveitsin frangi |
| one | Sveitsin frangi |
| other | Sveitsin frangia |
|  symbol | CHF |
|  | Sveitsin WIR-frangi |
| one | Sveitsin WIR-frangi |
| other | Sveitsin WIR-frangia |
|  symbol | CHW |
|  | Chilen escudo |
| one | Chilen escudo |
| other | Chilen escudoa |
|  symbol | CLE |
|  | Chilen unidades de fomento |
| one | Chilen unidades de fomento |
| other | Chilen unidades de fomentoa |
|  symbol | CLF |
|  | Chilen peso |
| one | Chilen peso |
| other | Chilen pesoa |
|  symbol | CLP |
| narrow symbol | CLP |
|  | Kiinan juan (offshore) |
| one | Kiinan juan (offshore) |
| other | Kiinan juania (offshore) |
|  symbol | CNH |
|  | Kiinan kansanpankin dollari |
| one | Kiinan kansanpankin dollari |
| other | Kiinan kansanpankin dollaria |
|  symbol | CNX |
|  | Kiinan juan |
| one | Kiinan juan |
| other | Kiinan juania |
|  symbol | CNY |
| narrow symbol | CNY |
|  | Kolumbian peso |
| one | Kolumbian peso |
| other | Kolumbian pesoa |
|  symbol | COP |
| narrow symbol | COP |
|  | Kolumbian unidad de valor real |
| one | Kolumbian unidad de valor real |
| other | Kolumbian unidad de valor realia |
|  symbol | COU |
|  | Costa Rican colón |
| one | Costa Rican colón |
| other | Costa Rican colónia |
|  symbol | CRC |
| narrow symbol | CRC |
|  | Serbian dinaari (2002–2006) |
| one | Serbian dinaari (2002–2006) |
| other | Serbian dinaaria (2002–2006) |
|  symbol | CSD |
|  | Tšekkoslovakian kova koruna |
| one | Tšekkoslovakian kova koruna |
| other | Tšekkoslovakian kovaa korunaa |
|  symbol | CSK |
|  | Kuuban vaihdettava peso |
| one | Kuuban vaihdettava peso |
| other | Kuuban vaihdettavaa pesoa |
|  symbol | CUC |
| narrow symbol | CUC |
|  | Kuuban peso |
| one | Kuuban peso |
| other | Kuuban pesoa |
|  symbol | CUP |
| narrow symbol | CUP |
|  | Kap Verden escudo |
| one | Kap Verden escudo |
| other | Kap Verden escudoa |
|  symbol | CVE |
|  | Kyproksen punta |
| one | Kyproksen punta |
| other | Kyproksen puntaa |
|  symbol | CYP |
|  | Tšekin koruna |
| one | Tšekin koruna |
| other | Tšekin korunaa |
|  symbol | CZK |
| narrow symbol | CZK |
|  | Itä-Saksan markka |
| one | Itä-Saksan markka |
| other | Itä-Saksan markkaa |
|  symbol | DDM |
|  | Saksan markka |
| one | Saksan markka |
| other | Saksan markkaa |
|  symbol | DEM |
|  | Djiboutin frangi |
| one | Djiboutin frangi |
| other | Djiboutin frangia |
|  symbol | DJF |
|  | Tanskan kruunu |
| one | Tanskan kruunu |
| other | Tanskan kruunua |
|  symbol | DKK |
| narrow symbol | DKK |
|  | Dominikaanisen tasavallan peso |
| one | Dominikaanisen tasavallan peso |
| other | Dominikaanisen tasavallan pesoa |
|  symbol | DOP |
| narrow symbol | DOP |
|  | Algerian dinaari |
| one | Algerian dinaari |
| other | Algerian dinaaria |
|  symbol | DZD |
|  | Ecuadorin sucre |
| one | Ecuadorin sucre |
| other | Ecuadorin sucrea |
|  symbol | ECS |
|  | Ecuadorin UVC |
| one | Ecuadorin UVC |
| other | Ecuadorin UVC’ta |
|  symbol | ECV |
|  | Viron kruunu |
| one | Viron kruunu |
| other | Viron kruunua |
|  symbol | EEK |
|  | Egyptin punta |
| one | Egyptin punta |
| other | Egyptin puntaa |
|  symbol | EGP |
| narrow symbol | EGP |
|  | Eritrean nakfa |
| one | Eritrean nakfa |
| other | Eritrean nakfaa |
|  symbol | ERN |
|  | Espanjan peseta (A-tili) |
| one | Espanjan peseta (A-tili) |
| other | Espanjan pesetaa (A-tili) |
|  symbol | ESA |
|  | Espanjan peseta (vaihdettava tili) |
| one | Espanjan peseta (vaihdettava tili) |
| other | Espanjan pesetaa (vaihdettava tili) |
|  symbol | ESB |
|  | Espanjan peseta |
| one | Espanjan peseta |
| other | Espanjan pesetaa |
|  symbol | ESP |
| narrow symbol | ESP |
|  | Etiopian birr |
| one | Etiopian birr |
| other | Etiopian birriä |
|  symbol | ETB |
|  | euro |
| one | euro |
| other | euroa |
|  symbol | € |
| narrow symbol | € |
|  | Suomen markka |
| one | Suomen markka |
| other | Suomen markkaa |
|  symbol | mk |
|  | Fidžin dollari |
| one | Fidžin dollari |
| other | Fidžin dollaria |
|  symbol | FJD |
| narrow symbol | FJD |
|  | Falklandinsaarten punta |
| one | Falklandinsaarten punta |
| other | Falklandinsaarten puntaa |
|  symbol | FKP |
| narrow symbol | FKP |
|  | Ranskan frangi |
| one | Ranskan frangi |
| other | Ranskan frangia |
|  symbol | FRF |
|  | Englannin punta |
| one | Englannin punta |
| other | Englannin puntaa |
|  symbol | £ |
| narrow symbol | £ |
|  | Georgian kuponkilari |
| one | Georgian kuponkilari |
| other | Georgian kuponkilaria |
|  symbol | GEK |
|  | Georgian lari |
| one | Georgian lari |
| other | Georgian laria |
|  symbol | GEL |
| narrow symbol | GEL |
|  | Ghanan cedi (1979–2007) |
| one | Ghanan cedi (1979–2007) |
| other | Ghanan cediä (1979–2007) |
|  symbol | GHC |
|  | Ghanan cedi |
| one | Ghanan cedi |
| other | Ghanan cediä |
|  symbol | GHS |
|  | Gibraltarin punta |
| one | Gibraltarin punta |
| other | Gibraltarin puntaa |
|  symbol | GIP |
| narrow symbol | GIP |
|  | Gambian dalasi |
| one | Gambian dalasi |
| other | Gambian dalasia |
|  symbol | GMD |
|  | Guinean frangi |
| one | Guinean frangi |
| other | Guinean frangia |
|  symbol | GNF |
| narrow symbol | GNF |
|  | Guinean syli |
| one | Guinean syli |
| other | Guinean syliä |
|  symbol | GNS |
|  | Päiväntasaajan Guinean ekwele |
| one | Päiväntasaajan Guinean ekwele |
| other | Päiväntasaajan Guinean ekweleä |
|  symbol | GQE |
|  | Kreikan drakma |
| one | Kreikan drakma |
| other | Kreikan drakmaa |
|  symbol | GRD |
|  | Guatemalan quetzal |
| one | Guatemalan quetzal |
| other | Guatemalan quetzalia |
|  symbol | GTQ |
| narrow symbol | GTQ |
|  | Portugalin Guinean escudo |
| one | Portugalin Guinean escudo |
| other | Portugalin Guinean escudoa |
|  symbol | GWE |
|  | Guinea-Bissaun peso |
| one | Guinea-Bissaun peso |
| other | Guinea-Bissaun pesoa |
|  symbol | GWP |
|  | Guyanan dollari |
| one | Guyanan dollari |
| other | Guyanan dollaria |
|  symbol | GYD |
| narrow symbol | GYD |
|  | Hongkongin dollari |
| one | Hongkongin dollari |
| other | Hongkongin dollaria |
|  symbol | HKD |
| narrow symbol | HKD |
|  | Hondurasin lempira |
| one | Hondurasin lempira |
| other | Hondurasin lempiraa |
|  symbol | HNL |
| narrow symbol | HNL |
|  | Kroatian dinaari |
| one | Kroatian dinaari |
| other | Kroatian dinaaria |
|  symbol | HRD |
|  | Kroatian kuna |
| one | Kroatian kuna |
| other | Kroatian kunaa |
|  symbol | HRK |
| narrow symbol | HRK |
|  | Haitin gourde |
| one | Haitin gourde |
| other | Haitin gourdea |
|  symbol | HTG |
|  | Unkarin forintti |
| one | Unkarin forintti |
| other | Unkarin forinttia |
|  symbol | HUF |
| narrow symbol | HUF |
|  | Indonesian rupia |
| one | Indonesian rupia |
| other | Indonesian rupiaa |
|  symbol | IDR |
| narrow symbol | IDR |
|  | Irlannin punta |
| one | Irlannin punta |
| other | Irlannin puntaa |
|  symbol | IEP |
|  | Israelin punta |
| one | Israelin punta |
| other | Israelin puntaa |
|  symbol | ILP |
|  | Israelin sekeli (1980–1985) |
| one | Israelin sekeli (1980–1985) |
| other | Israelin sekeliä (1980–1985) |
|  symbol | ILR |
|  | Israelin uusi sekeli |
| one | Israelin uusi sekeli |
| other | Israelin uutta sekeliä |
|  symbol | ILS |
| narrow symbol | ILS |
|  | Intian rupia |
| one | Intian rupia |
| other | Intian rupiaa |
|  symbol | INR |
| narrow symbol | INR |
|  | Irakin dinaari |
| one | Irakin dinaari |
| other | Irakin dinaaria |
|  symbol | IQD |
|  | Iranin rial |
| one | Iranin rial |
| other | Iranin rialia |
|  symbol | IRR |
|  | Islannin kruunu (1918–1981) |
| one | Islannin kruunu (1918–1981) |
| other | Islannin kruunua (1918–1981) |
|  symbol | ISJ |
|  | Islannin kruunu |
| one | Islannin kruunu |
| other | Islannin kruunua |
|  symbol | ISK |
| narrow symbol | ISK |
|  | Italian liira |
| one | Italian liira |
| other | Italian liiraa |
|  symbol | ITL |
|  | Jamaikan dollari |
| one | Jamaikan dollari |
| other | Jamaikan dollaria |
|  symbol | JMD |
| narrow symbol | JMD |
|  | Jordanian dinaari |
| one | Jordanian dinaari |
| other | Jordanian dinaaria |
|  symbol | JOD |
|  | Japanin jeni |
| one | Japanin jeni |
| other | Japanin jeniä |
|  symbol | ¥ |
| narrow symbol | ¥ |
|  | Kenian šillinki |
| one | Kenian šillinki |
| other | Kenian šillinkiä |
|  symbol | KES |
|  | Kirgisian som |
| one | Kirgisian som |
| other | Kirgisian somia |
|  symbol | KGS |
|  | Kambodžan riel |
| one | Kambodžan riel |
| other | Kambodžan rieliä |
|  symbol | KHR |
| narrow symbol | KHR |
|  | Komorien frangi |
| one | Komorien frangi |
| other | Komorien frangia |
|  symbol | KMF |
| narrow symbol | KMF |
|  | Pohjois-Korean won |
| one | Pohjois-Korean won |
| other | Pohjois-Korean wonia |
|  symbol | KPW |
| narrow symbol | KPW |
|  | Etelä-Korean hwan (1953–1962) |
| one | Etelä-Korean hwan (1953–1962) |
| other | Etelä-Korean hwania (1953–1962) |
|  symbol | KRH |
|  | Etelä-Korean won (1945–1953) |
| one | Etelä-Korean won (1945–1953) |
| other | Etelä-Korean wonia (1945–1953) |
|  symbol | KRO |
|  | Etelä-Korean won |
| one | Etelä-Korean won |
| other | Etelä-Korean wonia |
|  symbol | KRW |
| narrow symbol | KRW |
|  | Kuwaitin dinaari |
| one | Kuwaitin dinaari |
| other | Kuwaitin dinaaria |
|  symbol | KWD |
|  | Caymansaarten dollari |
| one | Caymansaarten dollari |
| other | Caymansaarten dollaria |
|  symbol | KYD |
| narrow symbol | KYD |
|  | Kazakstanin tenge |
| one | Kazakstanin tenge |
| other | Kazakstanin tengeä |
|  symbol | KZT |
| narrow symbol | KZT |
|  | Laosin kip |
| one | Laosin kip |
| other | Laosin kipiä |
|  symbol | LAK |
| narrow symbol | LAK |
|  | Libanonin punta |
| one | Libanonin punta |
| other | Libanonin puntaa |
|  symbol | LBP |
| narrow symbol | LBP |
|  | Sri Lankan rupia |
| one | Sri Lankan rupia |
| other | Sri Lankan rupiaa |
|  symbol | LKR |
| narrow symbol | LKR |
|  | Liberian dollari |
| one | Liberian dollari |
| other | Liberian dollaria |
|  symbol | LRD |
| narrow symbol | LRD |
|  | Lesothon loti |
| one | Lesothon loti |
| other | Lesothon lotia |
|  symbol | LSL |
|  | Liettuan liti |
| one | Liettuan liti |
| other | Liettuan litiä |
|  symbol | LTL |
| narrow symbol | LTL |
|  | Liettuan talonas |
| one | Liettuan talonas |
| other | Liettuan talonasia |
|  symbol | LTT |
|  | Luxemburgin vaihdettava frangi |
| one | Luxemburgin vaihdettava frangi |
| other | Luxemburgin vaihdettavaa frangia |
|  symbol | LUC |
|  | Luxemburgin frangi |
| one | Luxemburgin frangi |
| other | Luxemburgin frangia |
|  symbol | LUF |
|  | Luxemburgin rahoitusfrangi |
| one | Luxemburgin rahoitusfrangi |
| other | Luxemburgin rahoitusfrangia |
|  symbol | LUL |
|  | Latvian lati |
| one | Latvian lati |
| other | Latvian latia |
|  symbol | LVL |
| narrow symbol | LVL |
|  | Latvian rupla |
| one | Latvian rupla |
| other | Latvian ruplaa |
|  symbol | LVR |
|  | Libyan dinaari |
| one | Libyan dinaari |
| other | Libyan dinaaria |
|  symbol | LYD |
|  | Marokon dirhami |
| one | Marokon dirhami |
| other | Marokon dirhamia |
|  symbol | MAD |
|  | Marokon frangi |
| one | Marokon frangi |
| other | Marokon frangia |
|  symbol | MAF |
|  | Monacon frangi |
| one | Monacon frangi |
| other | Monacon frangia |
|  symbol | MCF |
|  | Moldovan kuponkileu |
| one | Moldovan kuponkileu |
| other | Moldovan kuponkileuta |
|  symbol | MDC |
|  | Moldovan leu |
| one | Moldovan leu |
| other | Moldovan leuta |
|  symbol | MDL |
|  | Madagaskarin ariary |
| one | Madagaskarin ariary |
| other | Madagaskarin ariarya |
|  symbol | MGA |
| narrow symbol | MGA |
|  | Madagaskarin frangi |
| one | Madagaskarin frangi |
| other | Madagaskarin frangia |
|  symbol | MGF |
|  | Makedonian denaari |
| one | Makedonian denaari |
| other | Makedonian denaaria |
|  symbol | MKD |
|  | Makedonian dinaari (1992–1993) |
| one | Makedonian dinaari (1992–1993) |
| other | Makedonian dinaaria (1992–1993) |
|  symbol | MKN |
|  | Malin frangi |
| one | Malin frangi |
| other | Malin frangia |
|  symbol | MLF |
|  | Myanmarin kyat |
| one | Myanmarin kyat |
| other | Myanmarin kyatia |
|  symbol | MMK |
| narrow symbol | MMK |
|  | Mongolian tugrik |
| one | Mongolian tugrik |
| other | Mongolian tugrikia |
|  symbol | MNT |
| narrow symbol | MNT |
|  | Macaon pataca |
| one | Macaon pataca |
| other | Macaon patacaa |
|  symbol | MOP |
|  | Mauritanian ouguiya |
| one | Mauritanian ouguiya |
| other | Mauritanian ouguiyaa |
|  symbol | MRO |
|  | Maltan liira |
| one | Maltan liira |
| other | Maltan liiraa |
|  symbol | MTL |
|  | Maltan punta |
| one | Maltan punta |
| other | Maltan puntaa |
|  symbol | MTP |
|  | Mauritiuksen rupia |
| one | Mauritiuksen rupia |
| other | Mauritiuksen rupiaa |
|  symbol | MUR |
| narrow symbol | MUR |
|  | Malediivien rupia (1947–1981) |
| one | Malediivien rupia (1947–1981) |
| other | Malediivien rupiaa (1947–1981) |
|  symbol | MVP |
|  | Malediivien rufiyaa |
| one | Malediivien rufiyaa |
| other | Malediivien rufiyaata |
|  symbol | MVR |
|  | Malawin kwacha |
| one | Malawin kwacha |
| other | Malawin kwachaa |
|  symbol | MWK |
|  | Meksikon peso |
| one | Meksikon peso |
| other | Meksikon pesoa |
|  symbol | MXN |
| narrow symbol | MXN |
|  | Meksikon hopeapeso (1861–1992) |
| one | Meksikon hopeapeso (1861–1992) |
| other | Meksikon hopeapesoa (1861–1992) |
|  symbol | MXP |
|  | Meksikon UDI |
| one | Meksikon UDI |
| other | Meksikon UDI’ta |
|  symbol | MXV |
|  | Malesian ringgit |
| one | Malesian ringgit |
| other | Malesian ringgitiä |
|  symbol | MYR |
| narrow symbol | MYR |
|  | Mosambikin escudo |
| one | Mosambikin escudo |
| other | Mosambikin escudoa |
|  symbol | MZE |
|  | Mosambikin metical (1980–2006) |
| one | Mosambikin metical (1980–2006) |
| other | Mosambikin meticalia (1980–2006) |
|  symbol | MZM |
|  | Mosambikin metical |
| one | Mosambikin metical |
| other | Mosambikin meticalia |
|  symbol | MZN |
|  | Namibian dollari |
| one | Namibian dollari |
| other | Namibian dollaria |
|  symbol | NAD |
| narrow symbol | NAD |
|  | Nigerian naira |
| one | Nigerian naira |
| other | Nigerian nairaa |
|  symbol | NGN |
| narrow symbol | NGN |
|  | Nicaraguan córdoba (1988–1991) |
| one | Nicaraguan córdoba (1988–1991) |
| other | Nicaraguan córdobaa (1988–1991) |
|  symbol | NIC |
|  | Nicaraguan córdoba |
| one | Nicaraguan córdoba |
| other | Nicaraguan córdobaa |
|  symbol | NIO |
| narrow symbol | NIO |
|  | Alankomaiden guldeni |
| one | Alankomaiden guldeni |
| other | Alankomaiden guldenia |
|  symbol | NLG |
|  | Norjan kruunu |
| one | Norjan kruunu |
| other | Norjan kruunua |
|  symbol | NOK |
| narrow symbol | NOK |
|  | Nepalin rupia |
| one | Nepalin rupia |
| other | Nepalin rupiaa |
|  symbol | NPR |
| narrow symbol | NPR |
|  | Uuden-Seelannin dollari |
| one | Uuden-Seelannin dollari |
| other | Uuden-Seelannin dollaria |
|  symbol | NZD |
| narrow symbol | NZD |
|  | Omanin rial |
| one | Omanin rial |
| other | Omanin rialia |
|  symbol | OMR |
|  | Panaman balboa |
| one | Panaman balboa |
| other | Panaman balboaa |
|  symbol | PAB |
|  | Perun inti |
| one | Perun inti |
| other | Perun intiä |
|  symbol | PEI |
|  | Perun sol |
| one | Perun sol |
| other | Perun solia |
|  symbol | PEN |
|  | Perun sol (1863–1965) |
| one | Perun sol (1863–1965) |
| other | Perun solia (1863–1965) |
|  symbol | PES |
|  | Papua-Uuden-Guinean kina |
| one | Papua-Uuden-Guinean kina |
| other | Papua-Uuden-Guinean kinaa |
|  symbol | PGK |
|  | Filippiinien peso |
| one | Filippiinien peso |
| other | Filippiinien pesoa |
|  symbol | PHP |
| narrow symbol | PHP |
|  | Pakistanin rupia |
| one | Pakistanin rupia |
| other | Pakistanin rupiaa |
|  symbol | PKR |
| narrow symbol | PKR |
|  | Puolan złoty |
| one | Puolan złoty |
| other | Puolan złotya |
|  symbol | PLN |
| narrow symbol | PLN |
|  | Puolan złoty (1950–1995) |
| one | Puolan złoty (1950–1995) |
| other | Puolan złotya (1950–1995) |
|  symbol | PLZ |
|  | Portugalin escudo |
| one | Portugalin escudo |
| other | Portugalin escudoa |
|  symbol | PTE |
|  | Paraguayn guarani |
| one | Paraguayn guarani |
| other | Paraguayn guarania |
|  symbol | PYG |
| narrow symbol | PYG |
|  | Qatarin rial |
| one | Qatarin rial |
| other | Qatarin rialia |
|  symbol | QAR |
|  | Rhodesian dollari |
| one | Rhodesian dollari |
| other | Rhodesian dollaria |
|  symbol | RHD |
|  | Romanian leu (1952–2006) |
| one | Romanian leu (1952–2006) |
| other | Romanian leuta (1952–2006) |
|  symbol | ROL |
|  | Romanian leu |
| one | Romanian leu |
| other | Romanian leuta |
|  symbol | RON |
| narrow symbol | RON |
|  | Serbian dinaari |
| one | Serbian dinaari |
| other | Serbian dinaaria |
|  symbol | RSD |
|  | Venäjän rupla |
| one | Venäjän rupla |
| other | Venäjän ruplaa |
|  symbol | RUB |
| narrow symbol | ₽ |
|  | Venäjän rupla (1991–1998) |
| one | Venäjän rupla (1991–1998) |
| other | Venäjän ruplaa (1991–1998) |
|  symbol | RUR |
| narrow symbol | RUR |
|  | Ruandan frangi |
| one | Ruandan frangi |
| other | Ruandan frangia |
|  symbol | RWF |
| narrow symbol | RWF |
|  | Saudi-Arabian rial |
| one | Saudi-Arabian rial |
| other | Saudi-Arabian rialia |
|  symbol | SAR |
|  | Salomonsaarten dollari |
| one | Salomonsaarten dollari |
| other | Salomonsaarten dollaria |
|  symbol | SBD |
| narrow symbol | SBD |
|  | Seychellien rupia |
| one | Seychellien rupia |
| other | Seychellien rupiaa |
|  symbol | SCR |
|  | Sudanin dinaari (1992–2007) |
| one | Sudanin dinaari (1992–2007) |
| other | Sudanin dinaaria (1992–2007) |
|  symbol | SDD |
|  | Sudanin punta |
| one | Sudanin punta |
| other | Sudanin puntaa |
|  symbol | SDG |
|  | Sudanin punta (1957–1998) |
| one | Sudanin punta (1957–1998) |
| other | Sudanin puntaa (1957–1998) |
|  symbol | SDP |
|  | Ruotsin kruunu |
| one | Ruotsin kruunu |
| other | Ruotsin kruunua |
|  symbol | SEK |
| narrow symbol | SEK |
|  | Singaporen dollari |
| one | Singaporen dollari |
| other | Singaporen dollaria |
|  symbol | SGD |
| narrow symbol | SGD |
|  | Saint Helenan punta |
| one | Saint Helenan punta |
| other | Saint Helenan puntaa |
|  symbol | SHP |
| narrow symbol | SHP |
|  | Slovenian tolar |
| one | Slovenian tolar |
| other | Slovenian tolaria |
|  symbol | SIT |
|  | Slovakian koruna |
| one | Slovakian koruna |
| other | Slovakian korunaa |
|  symbol | SKK |
|  | Sierra Leonen leone |
| one | Sierra Leonen leone |
| other | Sierra Leonen leonea |
|  symbol | SLL |
|  | Somalian šillinki |
| one | Somalian šillinki |
| other | Somalian šillinkiä |
|  symbol | SOS |
|  | Surinamen dollari |
| one | Surinamen dollari |
| other | Surinamen dollaria |
|  symbol | SRD |
| narrow symbol | SRD |
|  | Surinamen guldeni |
| one | Surinamen guldeni |
| other | Surinamen guldeni |
|  symbol | SRG |
|  | Etelä-Sudanin punta |
| one | Etelä-Sudanin punta |
| other | Etelä-Sudanin puntaa |
|  symbol | SSP |
| narrow symbol | SSP |
|  | São Tomén ja Príncipen dobra (1977–2017) |
| one | São Tomén ja Príncipen dobra (1977–2017) |
| other | São Tomén ja Príncipen dobraa (1977–2017) |
|  symbol | STD |
|  | São Tomén ja Príncipen dobra |
| one | São Tomén ja Príncipen dobra |
| other | São Tomén ja Príncipen dobraa |
|  symbol | STN |
| narrow symbol | STD |
|  | Neuvostoliiton rupla |
| one | Neuvostoliiton rupla |
| other | Neuvostoliiton ruplaa |
|  symbol | SUR |
|  | El Salvadorin colón |
| one | El Salvadorin colón |
| other | El Salvadorin colónia |
|  symbol | SVC |
|  | Syyrian punta |
| one | Syyrian punta |
| other | Syyrian puntaa |
|  symbol | SYP |
| narrow symbol | SYP |
|  | Swazimaan lilangeni |
| one | Swazimaan lilangeni |
| other | Swazimaan lilangenia |
|  symbol | SZL |
|  | Thaimaan baht |
| one | Thaimaan baht |
| other | Thaimaan bahtia |
|  symbol | THB |
| narrow symbol | THB |
|  | Tadžikistanin rupla |
| one | Tadžikistanin rupla |
| other | Tadžikistanin ruplaa |
|  symbol | TJR |
|  | Tadžikistanin somoni |
| one | Tadžikistanin somoni |
| other | Tadžikistanin somonia |
|  symbol | TJS |
|  | Turkmenistanin manat (1993–2009) |
| one | Turkmenistanin manat (1993–2009) |
| other | Turkmenistanin manatia (1993–2009) |
|  symbol | TMM |
|  | Turkmenistanin manat |
| one | Turkmenistanin manat |
| other | Turkmenistanin manatia |
|  symbol | TMT |
|  | Tunisian dinaari |
| one | Tunisian dinaari |
| other | Tunisian dinaaria |
|  symbol | TND |
|  | Tongan pa’anga |
| one | Tongan pa’anga |
| other | Tongan pa’angaa |
|  symbol | TOP |
| narrow symbol | TOP |
|  | Timorin escudo |
| one | Timorin escudo |
| other | Timorin escudoa |
|  symbol | TPE |
|  | Turkin liira (1922–2005) |
| one | Turkin liira (1922–2005) |
| other | Turkin liiraa (1922–2005) |
|  symbol | TRL |
|  | Turkin liira |
| one | Turkin liira |
| other | Turkin liiraa |
|  symbol | TRY |
| narrow symbol | TRY |
| variant symbol | TL |
|  | Trinidadin ja Tobagon dollari |
| one | Trinidadin ja Tobagon dollari |
| other | Trinidadin ja Tobagon dollaria |
|  symbol | TTD |
| narrow symbol | TTD |
|  | Taiwanin uusi dollari |
| one | Taiwanin uusi dollari |
| other | Taiwanin uutta dollaria |
|  symbol | TWD |
| narrow symbol | TWD |
|  | Tansanian šillinki |
| one | Tansanian šillinki |
| other | Tansanian šillinkiä |
|  symbol | TZS |
|  | Ukrainan hryvnia |
| one | Ukrainan hryvnia |
| other | Ukrainan hryvniaa |
|  symbol | UAH |
| narrow symbol | UAH |
|  | Ukrainan karbovanetz |
| one | Ukrainan karbovanetz |
| other | Ukrainan karbovanetzia |
|  symbol | UAK |
|  | Ugandan šillinki (1966–1987) |
| one | Ugandan šillinki (1966–1987) |
| other | Ugandan šillinkiä (1966–1987) |
|  symbol | UGS |
|  | Ugandan šillinki |
| one | Ugandan šillinki |
| other | Ugandan šillinkiä |
|  symbol | UGX |
|  | Yhdysvaltain dollari |
| one | Yhdysvaltain dollari |
| other | Yhdysvaltain dollaria |
|  symbol | $ |
| narrow symbol | $ |
|  | Yhdysvaltain dollari (seuraava päivä) |
| one | Yhdysvaltain dollari (seuraava päivä) |
| other | Yhdysvaltain dollaria (seuraava päivä) |
|  symbol | USN |
|  | Yhdysvaltain dollari (sama päivä) |
| one | Yhdysvaltain dollari (sama päivä) |
| other | Yhdysvaltain dollaria (sama päivä) |
|  symbol | USS |
|  | Uruguayn peso en unidades indexadas |
| one | Uruguayn peso en unidades indexadas |
| other | Uruguayn pesoa en unidades indexadas |
|  symbol | UYI |
|  | Uruguayn peso (1975–1993) |
| one | Uruguayn peso (1975–1993) |
| other | Uruguayn pesoa (1975–1993) |
|  symbol | UYP |
|  | Uruguayn peso |
| one | Uruguayn peso |
| other | Uruguayn pesoa |
|  symbol | UYU |
| narrow symbol | UYU |
|  | Uzbekistanin som |
| one | Uzbekistanin som |
| other | Uzbekistanin somia |
|  symbol | UZS |
|  | Venezuelan bolivar (1871–2008) |
| one | Venezuelan bolivar (1871–2008) |
| other | Venezuelan bolivaria (1871–2008) |
|  symbol | VEB |
|  | Venezuelan bolivar |
| one | Venezuelan bolivar |
| other | Venezuelan bolivaria |
|  symbol | VEF |
| narrow symbol | VEF |
|  | Vietnamin dong |
| one | Vietnamin dong |
| other | Vietnamin dongia |
|  symbol | VND |
| narrow symbol | VND |
|  | Vietnamin dong (1978–1985) |
| one | Vietnamin dong (1978–1985) |
| other | Vietnamin dongia (1978–1985) |
|  symbol | VNN |
|  | Vanuatun vatu |
| one | Vanuatun vatu |
| other | Vanuatun vatua |
|  symbol | VUV |
|  | Samoan tala |
| one | Samoan tala |
| other | Samoan talaa |
|  symbol | WST |
|  | CFA-frangi BEAC |
| one | CFA-frangi BEAC |
| other | CFA-frangia BEAC |
|  symbol | FCFA |
|  | hopea |
| one | troy-unssi hopeaa |
| other | troy-unssia hopeaa |
|  symbol | XAG |
|  | kulta |
| one | troy-unssi kultaa |
| other | troy-unssia kultaa |
|  symbol | XAU |
|  | EURCO |
| one | EURCO |
| other | EURCO’a |
|  symbol | XBA |
|  | Euroopan rahayksikkö (EMU) |
| one | Euroopan rahayksikkö (EMU) |
| other | Euroopan rahayksikköä (EMU) |
|  symbol | XBB |
|  | EUA (XBC) |
| one | EUA (XBC) |
| other | EUA’ta (XBC) |
|  symbol | XBC |
|  | EUA (XBD) |
| one | EUA (XBD) |
| other | EUA’ta (XBD) |
|  symbol | XBD |
|  | Itä-Karibian dollari |
| one | Itä-Karibian dollari |
| other | Itä-Karibian dollaria |
|  symbol | XCD |
| narrow symbol | XCD |
|  | erityisnosto-oikeus (SDR) |
| one | erityisnosto-oikeus (SDR) |
| other | erityisnosto-oikeutta (SDR) |
|  symbol | XDR |
|  | Euroopan valuuttayksikkö (ECU) |
| one | Euroopan valuuttayksikkö (ECU) |
| other | Euroopan valuuttayksikköä (ECU) |
|  symbol | XEU |
|  | Ranskan kultafrangi |
| one | Ranskan kultafrangi |
| other | Ranskan kultafrangia |
|  symbol | XFO |
|  | Ranskan UIC-frangi |
| one | Ranskan UIC-frangi |
| other | Ranskan UIC-frangia |
|  symbol | XFU |
|  | CFA-frangi BCEAO |
| one | CFA-frangi BCEAO |
| other | CFA-frangia BCEAO |
|  symbol | CFA |
|  | palladium |
| one | troy-unssi palladiumia |
| other | troy-unssia palladiumia |
|  symbol | XPD |
|  | CFP-frangi |
| one | CFP-frangi |
| other | CFP-frangia |
|  symbol | XPF |
|  | platina |
| one | troy-unssi platinaa |
| other | troy-unssia platinaa |
|  symbol | XPT |
|  | RINET-rahastot |
| one | RINET-rahastoyksikkö |
| other | RINET-rahastoyksikköä |
|  symbol | XRE |
|  | etelä-amerikkalaisen ALBA:n laskentayksikkö sucre |
| one | sucre |
| other | sucrea |
|  symbol | XSU |
|  | testaustarkoitukseen varattu valuuttakoodi |
| one | testaustarkoitukseen varattu valuuttakoodi |
| other | testaustarkoitukseen varattua valuuttakoodia |
|  symbol | XTS |
|  | afrikkalainen AfDB-laskentayksikkö |
| one | AfDB-laskentayksikkö |
| other | AfDB-laskentayksikköä |
|  symbol | XUA |
|  | tuntematon rahayksikkö |
| one | tuntematon rahayksikkö |
| other | tuntematonta rahayksikköä |
|  symbol | XXX |
|  | Jemenin dinaari |
| one | Jemenin dinaari |
| other | Jemenin dinaaria |
|  symbol | YDD |
|  | Jemenin rial |
| one | Jemenin rial |
| other | Jemenin rialia |
|  symbol | YER |
|  | Jugoslavian kova dinaari (1966–1990) |
| one | Jugoslavian kova dinaari (1966–1990) |
| other | Jugoslavian kovaa dinaaria (1966–1990) |
|  symbol | YUD |
|  | Jugoslavian uusi dinaari (1994–2002) |
| one | Jugoslavian uusi dinaari (1994–2002) |
| other | Jugoslavian uutta dinaaria (1994–2002) |
|  symbol | YUM |
|  | Jugoslavian vaihdettava dinaari (1990–1992) |
| one | Jugoslavian vaihdettava dinaari (1990–1992) |
| other | Jugoslavian vaihdettavaa dinaaria (1990–1992) |
|  symbol | YUN |
|  | Jugoslavian uudistettu dinaari (1992–1993) |
| one | Jugoslavian uudistettu dinaari (1992–1993) |
| other | Jugoslavian uudistettua dinaaria (1992–1993) |
|  symbol | YUR |
|  | Etelä-Afrikan rahoitusrandi |
| one | Etelä-Afrikan rahoitusrandi |
| other | Etelä-Afrikan rahoitusrandia |
|  symbol | ZAL |
|  | Etelä-Afrikan randi |
| one | Etelä-Afrikan randi |
| other | Etelä-Afrikan randia |
|  symbol | ZAR |
| narrow symbol | ZAR |
|  | Sambian kwacha (1968–2012) |
| one | Sambian kwacha (1968–2012) |
| other | Sambian kwachaa (1968–2012) |
|  symbol | ZMK |
|  | Sambian kwacha |
| one | Sambian kwacha |
| other | Sambian kwachaa |
|  symbol | ZMW |
| narrow symbol | ZMW |
|  | Zairen uusi zaire (1993–1998) |
| one | Zairen uusi zaire (1993–1998) |
| other | Zairen uutta zairea (1993–1998) |
|  symbol | ZRN |
|  | Zairen zaire (1971–1993) |
| one | Zairen zaire (1971–1993) |
| other | Zairen zairea (1971–1993) |
|  symbol | ZRZ |
|  | Zimbabwen dollari (1980–2008) |
| one | Zimbabwen dollari (1980–2008) |
| other | Zimbabwen dollaria (1980–2008) |
|  symbol | ZWD |
|  | Zimbabwen dollari (2009) |
| one | Zimbabwen dollari (2009) |
| other | Zimbabwen dollaria (2009) |
|  symbol | ZWL |
|  | Zimbabwen dollari (2008) |
| one | Zimbabwen dollari (2008) |
| other | Zimbabwen dollaria (2008) |
|  symbol | ZWR |

Other stuff:
vähintään {0}{0}–{1}
Examples:
| one example | {0} päivä |
| other example | {0} päivää |
Käänny {0}. risteyksestä oikealle.

## Units

| Code | Name |
| ---- | ---- |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | G-voimat |
| one | {0} G-voima |
| other | {0} G-voimaa |
| acceleration-meter-per-second-squared | ... |
|  | metrit per sekunti toiseen |
| one | {0} metri per sekunti toiseen |
| other | {0} metriä per sekunti toiseen |
| angle-revolution | ... |
|  | kierros |
| one | {0} kierros |
| other | {0} kierrosta |
| angle-radian | ... |
|  | radiaanit |
| one | {0} radiaani |
| other | {0} radiaania |
| angle-degree | ... |
|  | asteet |
| one | {0} aste |
| other | {0} astetta |
| angle-arc-minute | ... |
|  | kulmaminuutit |
| one | {0} kulmaminuutti |
| other | {0} kulmaminuuttia |
| angle-arc-second | ... |
|  | kulmasekunnit |
| one | {0} kulmasekunti |
| other | {0} kulmasekuntia |
| area-square-kilometer | ... |
|  | neliökilometrit |
| one | {0} neliökilometri |
| other | {0} neliökilometriä |
{0} / neliökilometri
| area-hectare | ... |
|  | hehtaarit |
| one | {0} hehtaari |
| other | {0} hehtaaria |
| area-square-meter | ... |
|  | neliömetrit |
| one | {0} neliömetri |
| other | {0} neliömetriä |
{0} / neliömetri
| area-square-centimeter | ... |
|  | neliösenttimetrit |
| one | {0} neliösenttimetri |
| other | {0} neliösenttimetriä |
{0} / neliösenttimetri
| area-square-mile | ... |
|  | neliömailit |
| one | {0} neliömaili |
| other | {0} neliömailia |
{0} / neliömaili
| area-acre | ... |
|  | eekkerit |
| one | {0} eekkeri |
| other | {0} eekkeriä |
| area-square-yard | ... |
|  | neliöjaardit |
| one | {0} neliöjaardi |
| other | {0} neliöjaardia |
| area-square-foot | ... |
|  | neliöjalat |
| one | {0} neliöjalka |
| other | {0} neliöjalkaa |
| area-square-inch | ... |
|  | neliötuumat |
| one | {0} neliötuuma |
| other | {0} neliötuumaa |
{0} / neliötuuma
| concentr-karat | ... |
|  | karaatit |
| one | {0} karaatti |
| other | {0} karaattia |
| concentr-milligram-per-deciliter | ... |
|  | mg/dl |
| one | {0} mg/dl |
| other | {0} mg/dl |
| concentr-millimole-per-liter | ... |
|  | mmol/l |
| one | {0} mmol/l |
| other | {0} mmol/l |
| concentr-part-per-million | ... |
|  | ppm |
| one | {0} ppm |
| other | {0} ppm |
| consumption-liter-per-kilometer | ... |
|  | litrat / kilometri |
| one | {0} litra / kilometri |
| other | {0} litraa / kilometri |
| consumption-liter-per-100kilometers | ... |
|  | litrat / 100 kilometriä |
| one | {0} litra / 100 km |
| other | {0} litraa / 100 km |
| consumption-mile-per-gallon | ... |
|  | mailit / am. gallona |
| one | {0} maili / am. gallona |
| other | {0} mailia / am. gallona |
| consumption-mile-per-gallon-imperial | ... |
|  | mailit / br. gallona |
| one | {0} maili / br. gallona |
| other | {0} mailia / br. gallona |
| digital-terabyte | ... |
|  | teratavut |
| one | {0} teratavu |
| other | {0} teratavua |
| digital-terabit | ... |
|  | terabitit |
| one | {0} terabitti |
| other | {0} terabittiä |
| digital-gigabyte | ... |
|  | gigatavut |
| one | {0} gigatavu |
| other | {0} gigatavua |
| digital-gigabit | ... |
|  | gigabitit |
| one | {0} gigabitti |
| other | {0} gigabittiä |
| digital-megabyte | ... |
|  | megatavut |
| one | {0} megatavu |
| other | {0} megatavua |
| digital-megabit | ... |
|  | megabitit |
| one | {0} megabitti |
| other | {0} megabittiä |
| digital-kilobyte | ... |
|  | kilotavut |
| one | {0} kilotavu |
| other | {0} kilotavua |
| digital-kilobit | ... |
|  | kilobitit |
| one | {0} kilobitti |
| other | {0} kilobittiä |
| digital-byte | ... |
|  | tavut |
| one | {0} tavu |
| other | {0} tavua |
| digital-bit | ... |
|  | bitit |
| one | {0} bitti |
| other | {0} bittiä |
| duration-century | ... |
|  | vuosisadat |
| one | {0} vuosisata |
| other | {0} vuosisataa |
| duration-year | ... |
|  | vuodet |
| one | {0} vuosi |
| other | {0} vuotta |
{0} / vuosi
| duration-month | ... |
|  | kuukaudet |
| one | {0} kuukausi |
| other | {0} kuukautta |
{0} / kuukausi
| duration-week | ... |
|  | viikot |
| one | {0} viikko |
| other | {0} viikkoa |
{0} / viikko
| duration-day | ... |
|  | päivät |
| one | {0} päivä |
| other | {0} päivää |
{0} / päivä
| duration-hour | ... |
|  | tunnit |
| one | {0} tunti |
| other | {0} tuntia |
{0} / tunti
| duration-minute | ... |
|  | minuutit |
| one | {0} minuutti |
| other | {0} minuuttia |
{0} / minuutti
| duration-second | ... |
|  | sekunnit |
| one | {0} sekunti |
| other | {0} sekuntia |
{0} / sekunti
| duration-millisecond | ... |
|  | millisekunnit |
| one | {0} millisekunti |
| other | {0} millisekuntia |
| duration-microsecond | ... |
|  | mikrosekunnit |
| one | {0} mikrosekunti |
| other | {0} mikrosekuntia |
| duration-nanosecond | ... |
|  | nanosekunnit |
| one | {0} nanosekunti |
| other | {0} nanosekuntia |
| electric-ampere | ... |
|  | ampeerit |
| one | {0} ampeeri |
| other | {0} ampeeria |
| electric-milliampere | ... |
|  | milliampeerit |
| one | {0} milliampeeri |
| other | {0} milliampeeria |
| electric-ohm | ... |
|  | ohmit |
| one | {0} ohmi |
| other | {0} ohmia |
| electric-volt | ... |
|  | voltit |
| one | {0} voltti |
| other | {0} volttia |
| energy-kilocalorie | ... |
|  | kilokalorit |
| one | {0} kilokalori |
| other | {0} kilokaloria |
| energy-calorie | ... |
|  | kalorit |
| one | {0} kalori |
| other | {0} kaloria |
| energy-foodcalorie | ... |
|  | kilokalorit |
| one | {0} kilokalori |
| other | {0} kilokaloria |
| energy-kilojoule | ... |
|  | kilojoulet |
| one | {0} kilojoule |
| other | {0} kilojoulea |
| energy-joule | ... |
|  | joulet |
| one | {0} joule |
| other | {0} joulea |
| energy-kilowatt-hour | ... |
|  | kilowattitunnit |
| one | {0} kilowattitunti |
| other | {0} kilowattituntia |
| frequency-gigahertz | ... |
|  | gigahertsit |
| one | {0} gigahertsi |
| other | {0} gigahertsiä |
| frequency-megahertz | ... |
|  | megahertsit |
| one | {0} megahertsi |
| other | {0} megahertsiä |
| frequency-kilohertz | ... |
|  | kilohertsit |
| one | {0} kilohertsi |
| other | {0} kilohertsiä |
| frequency-hertz | ... |
|  | hertsit |
| one | {0} hertsi |
| other | {0} hertsiä |
| length-kilometer | ... |
|  | kilometrit |
| one | {0} kilometri |
| other | {0} kilometriä |
{0} / kilometri
| length-meter | ... |
|  | metrit |
| one | {0} metri |
| other | {0} metriä |
{0} / metri
| length-decimeter | ... |
|  | desimetrit |
| one | {0} desimetri |
| other | {0} desimetriä |
| length-centimeter | ... |
|  | senttimetrit |
| one | {0} senttimetri |
| other | {0} senttimetriä |
{0} / senttimetri
| length-millimeter | ... |
|  | millimetrit |
| one | {0} millimetri |
| other | {0} millimetriä |
| length-micrometer | ... |
|  | mikrometrit |
| one | {0} mikrometri |
| other | {0} mikrometriä |
| length-nanometer | ... |
|  | nanometrit |
| one | {0} nanometri |
| other | {0} nanometriä |
| length-picometer | ... |
|  | pikometrit |
| one | {0} pikometri |
| other | {0} pikometriä |
| length-mile | ... |
|  | mailit |
| one | {0} maili |
| other | {0} mailia |
| length-yard | ... |
|  | jaardit |
| one | {0} jaardi |
| other | {0} jaardia |
| length-foot | ... |
|  | jalat |
| one | {0} jalka |
| other | {0} jalkaa |
{0} / jalka
| length-inch | ... |
|  | tuumat |
| one | {0} tuuma |
| other | {0} tuumaa |
{0} / tuuma
| length-parsec | ... |
|  | parsekit |
| one | {0} parsek |
| other | {0} parsekia |
| length-light-year | ... |
|  | valovuodet |
| one | {0} valovuosi |
| other | {0} valovuotta |
| length-astronomical-unit | ... |
|  | astronomiset yksiköt |
| one | {0} astronominen yksikkö |
| other | {0} astronomista yksikköä |
| length-furlong | ... |
|  | furlongit |
| one | {0} furlong |
| other | {0} furlongia |
| length-fathom | ... |
|  | sylet |
| one | {0} syli |
| other | {0} syltä |
| length-nautical-mile | ... |
|  | meripeninkulmat |
| one | {0} meripeninkulma |
| other | {0} meripeninkulmaa |
| length-mile-scandinavian | ... |
|  | peninkulmat |
| one | {0} peninkulma |
| other | {0} peninkulmaa |
| length-point | ... |
|  | pt |
| one | {0} pt |
| other | {0} pt |
| light-lux | ... |
|  | luksit |
| one | {0} luksi |
| other | {0} luksia |
| mass-metric-ton | ... |
|  | tonnit |
| one | {0} tonni |
| other | {0} tonnia |
| mass-kilogram | ... |
|  | kilogrammat |
| one | {0} kilogramma |
| other | {0} kilogrammaa |
{0} / kilogramma
| mass-gram | ... |
|  | grammat |
| one | {0} gramma |
| other | {0} grammaa |
{0} / gramma
| mass-milligram | ... |
|  | milligrammat |
| one | {0} milligramma |
| other | {0} milligrammaa |
| mass-microgram | ... |
|  | mikrogrammat |
| one | {0} mikrogramma |
| other | {0} mikrogrammaa |
| mass-ton | ... |
|  | am. tonnit |
| one | {0} am. tonni |
| other | {0} am. tonnia |
| mass-stone | ... |
|  | stonet |
| one | {0} stone |
| other | {0} stonea |
| mass-pound | ... |
|  | paunat |
| one | {0} pauna |
| other | {0} paunaa |
{0} / pauna
| mass-ounce | ... |
|  | unssit |
| one | {0} unssi |
| other | {0} unssia |
{0} / unssi
| mass-ounce-troy | ... |
|  | troy-unssit |
| one | {0} troy-unssi |
| other | {0} troy-unssia |
| mass-carat | ... |
|  | karaatit |
| one | {0} karaatti |
| other | {0} karaattia |
| power-gigawatt | ... |
|  | gigawatit |
| one | {0} gigawatti |
| other | {0} gigawattia |
| power-megawatt | ... |
|  | megawatit |
| one | {0} megawatti |
| other | {0} megawattia |
| power-kilowatt | ... |
|  | kilowatit |
| one | {0} kilowatti |
| other | {0} kilowattia |
| power-watt | ... |
|  | watit |
| one | {0} watti |
| other | {0} wattia |
| power-milliwatt | ... |
|  | milliwatit |
| one | {0} milliwatti |
| other | {0} milliwattia |
| power-horsepower | ... |
|  | hevosvoimat |
| one | {0} hevosvoima |
| other | {0} hevosvoimaa |
| pressure-hectopascal | ... |
|  | hehtopascalit |
| one | {0} hehtopascal |
| other | {0} hehtopascalia |
| pressure-millimeter-of-mercury | ... |
|  | elohopeamillimetrit |
| one | {0} millimetri elohopeaa |
| other | {0} millimetriä elohopeaa |
| pressure-pound-per-square-inch | ... |
|  | paunat / neliötuuma |
| one | {0} pauna / neliötuuma |
| other | {0} paunaa / neliötuuma |
| pressure-inch-hg | ... |
|  | elohopeatuumat |
| one | {0} tuuma elohopeaa |
| other | {0} tuumaa elohopeaa |
| pressure-millibar | ... |
|  | millibaarit |
| one | {0} millibaari |
| other | {0} millibaaria |
| speed-kilometer-per-hour | ... |
|  | kilometrit tunnissa |
| one | {0} kilometri tunnissa |
| other | {0} kilometriä tunnissa |
| speed-meter-per-second | ... |
|  | metrit sekunnissa |
| one | {0} metri sekunnissa |
| other | {0} metriä sekunnissa |
| speed-mile-per-hour | ... |
|  | mailit tunnissa |
| one | {0} maili tunnissa |
| other | {0} mailia tunnissa |
| speed-knot | ... |
|  | solmu |
| one | {0} solmu |
| other | {0} solmua |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | celsiusasteet |
| one | {0} celsiusaste |
| other | {0} celsiusastetta |
| temperature-fahrenheit | ... |
|  | fahrenheitasteet |
| one | {0} fahrenheitaste |
| other | {0} fahrenheitastetta |
| temperature-kelvin | ... |
|  | kelvinit |
| one | {0} kelvin |
| other | {0} kelviniä |
| volume-cubic-kilometer | ... |
|  | kuutiokilometrit |
| one | {0} kuutiokilometri |
| other | {0} kuutiokilometriä |
| volume-cubic-meter | ... |
|  | kuutiometrit |
| one | {0} kuutiometri |
| other | {0} kuutiometriä |
{0} / kuutiometri
| volume-cubic-centimeter | ... |
|  | kuutiosenttimetrit |
| one | {0} kuutiosenttimetri |
| other | {0} kuutiosenttimetriä |
{0} / kuutiosenttimetri
| volume-cubic-mile | ... |
|  | kuutiomailit |
| one | {0} kuutiomaili |
| other | {0} kuutiomailia |
| volume-cubic-yard | ... |
|  | kuutiojaardit |
| one | {0} kuutiojaardi |
| other | {0} kuutiojaardia |
| volume-cubic-foot | ... |
|  | kuutiojalat |
| one | {0} kuutiojalka |
| other | {0} kuutiojalkaa |
| volume-cubic-inch | ... |
|  | kuutiotuumat |
| one | {0} kuutiotuuma |
| other | {0} kuutiotuumaa |
| volume-megaliter | ... |
|  | megalitrat |
| one | {0} megalitra |
| other | {0} megalitraa |
| volume-hectoliter | ... |
|  | hehtolitrat |
| one | {0} hehtolitra |
| other | {0} hehtolitraa |
| volume-liter | ... |
|  | litrat |
| one | {0} litra |
| other | {0} litraa |
{0} / litra
| volume-deciliter | ... |
|  | desilitrat |
| one | {0} desilitra |
| other | {0} desilitraa |
| volume-centiliter | ... |
|  | senttilitrat |
| one | {0} senttilitra |
| other | {0} senttilitraa |
| volume-milliliter | ... |
|  | millilitrat |
| one | {0} millilitra |
| other | {0} millilitraa |
| volume-pint-metric | ... |
|  | tuopit |
| one | {0} tuoppi |
| other | {0} tuoppia |
| volume-cup-metric | ... |
|  | teekupit |
| one | {0} teekuppi |
| other | {0} teekuppia |
| volume-acre-foot | ... |
|  | eekkerijalat |
| one | {0} eekkerijalka |
| other | {0} eekkerijalkaa |
| volume-bushel | ... |
|  | bushelit |
| one | {0} busheli |
| other | {0} bushelia |
| volume-gallon | ... |
|  | am. gallonat |
| one | {0} am. gallona |
| other | {0} am. gallonaa |
{0} / am. gallona
| volume-gallon-imperial | ... |
|  | br. gallonat |
| one | {0} br. gallona |
| other | {0} br. gallonaa |
{0} / br. gallona
| volume-quart | ... |
|  | neljännesgallonat |
| one | {0} neljännesgallona |
| other | {0} neljännesgallonaa |
| volume-pint | ... |
|  | pintit |
| one | {0} pint |
| other | {0} pinttiä |
| volume-cup | ... |
|  | kupit |
| one | {0} kuppi |
| other | {0} kuppia |
| volume-fluid-ounce | ... |
|  | nesteunssit |
| one | {0} nesteunssi |
| other | {0} nesteunssia |
| volume-tablespoon | ... |
|  | ruokalusikat |
| one | {0} ruokalusikka |
| other | {0} ruokalusikkaa |
| volume-teaspoon | ... |
|  | teelusikat |
| one | {0} teelusikka |
| other | {0} teelusikkaa |
{0}I{0}P{0}E{0}L
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | G |
| one | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
|  | m/s² |
| one | {0} m/s² |
| other | {0} m/s² |
| angle-revolution | ... |
|  | rev |
| one | {0} rev |
| other | {0} rev |
| angle-radian | ... |
|  | rad |
| one | {0} rad |
| other | {0} rad |
| angle-degree | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | ′ |
| one | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | ″ |
| one | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
|  | km² |
| one | {0} km² |
| other | {0} km² |
{0}/km²
| area-hectare | ... |
|  | ha |
| one | {0} ha |
| other | {0} ha |
| area-square-meter | ... |
|  | m² |
| one | {0} m² |
| other | {0} m² |
{0}/m²
| area-square-centimeter | ... |
|  | cm² |
| one | {0} cm² |
| other | {0} cm² |
{0}/cm²
| area-square-mile | ... |
|  | mi² |
| one | {0} mi² |
| other | {0} mi² |
{0}/mi²
| area-acre | ... |
|  | ac |
| one | {0} ac |
| other | {0} ac |
| area-square-yard | ... |
|  | yd² |
| one | {0} yd² |
| other | {0} yd² |
| area-square-foot | ... |
|  | ft² |
| one | {0} ft² |
| other | {0} ft² |
| area-square-inch | ... |
|  | in² |
| one | {0} in² |
| other | {0} in² |
{0}/in²
| concentr-karat | ... |
|  | ka |
| one | {0} ka |
| other | {0} ka |
| concentr-milligram-per-deciliter | ... |
|  | mg/dl |
| one | {0} mg/dl |
| other | {0} mg/dl |
| concentr-millimole-per-liter | ... |
|  | mmol/l |
| one | {0} mmol/l |
| other | {0} mmol/l |
| concentr-part-per-million | ... |
|  | ppm |
| one | {0} ppm |
| other | {0} ppm |
| consumption-liter-per-kilometer | ... |
|  | l/km |
| one | {0} l/km |
| other | {0} l/km |
| consumption-liter-per-100kilometers | ... |
|  | l/100 km |
| one | {0} l/100 km |
| other | {0} l/100 km |
| consumption-mile-per-gallon | ... |
|  | mpg-am |
| one | {0} mpg-am |
| other | {0} mpg-am |
| consumption-mile-per-gallon-imperial | ... |
|  | mpg-br |
| one | {0} mpg-br |
| other | {0} mpg-br |
| digital-terabyte | ... |
|  | Tt |
| one | {0} Tt |
| other | {0} Tt |
| digital-terabit | ... |
|  | Tb |
| one | {0} Tb |
| other | {0} Tb |
| digital-gigabyte | ... |
|  | Gt |
| one | {0} Gt |
| other | {0} Gt |
| digital-gigabit | ... |
|  | Gb |
| one | {0} Gb |
| other | {0} Gb |
| digital-megabyte | ... |
|  | Mt |
| one | {0} Mt |
| other | {0} Mt |
| digital-megabit | ... |
|  | Mb |
| one | {0} Mb |
| other | {0} Mb |
| digital-kilobyte | ... |
|  | kt |
| one | {0} kt |
| other | {0} kt |
| digital-kilobit | ... |
|  | kb |
| one | {0} kb |
| other | {0} kb |
| digital-byte | ... |
|  | t |
| one | {0} t |
| other | {0} t |
| digital-bit | ... |
|  | b |
| one | {0} b |
| other | {0} b |
| duration-century | ... |
|  | vs |
| one | {0} vs |
| other | {0} vs |
| duration-year | ... |
|  | v |
| one | {0} v |
| other | {0} v |
{0}/v
| duration-month | ... |
|  | kk |
| one | {0} kk |
| other | {0} kk |
{0}/kk
| duration-week | ... |
|  | vk |
| one | {0} vk |
| other | {0} vk |
{0}/vk
| duration-day | ... |
|  | pv |
| one | {0} pv |
| other | {0} pv |
{0}/pv
| duration-hour | ... |
|  | t |
| one | {0} t |
| other | {0} t |
{0}/t
| duration-minute | ... |
|  | min |
| one | {0} min |
| other | {0} min |
{0}/min
| duration-second | ... |
|  | sek |
| one | {0} s |
| other | {0} s |
{0}/s
| duration-millisecond | ... |
|  | ms |
| one | {0} ms |
| other | {0} ms |
| duration-microsecond | ... |
|  | μs |
| one | {0} μs |
| other | {0} μs |
| duration-nanosecond | ... |
|  | ns |
| one | {0} ns |
| other | {0} ns |
| electric-ampere | ... |
|  | A |
| one | {0} A |
| other | {0} A |
| electric-milliampere | ... |
|  | mA |
| one | {0} mA |
| other | {0} mA |
| electric-ohm | ... |
|  | Ω |
| one | {0} Ω |
| other | {0} Ω |
| electric-volt | ... |
|  | V |
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
|  | kcal |
| one | {0} kcal |
| other | {0} kcal |
| energy-kilojoule | ... |
|  | kJ |
| one | {0} kJ |
| other | {0} kJ |
| energy-joule | ... |
|  | J |
| one | {0} J |
| other | {0} J |
| energy-kilowatt-hour | ... |
|  | kWh |
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
|  | µm |
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
|  | mi |
| one | {0} mi |
| other | {0} mi |
| length-yard | ... |
|  | yd |
| one | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | ft |
| one | {0} ft |
| other | {0} ft |
{0}/ft
| length-inch | ... |
|  | in |
| one | {0} in |
| other | {0} in |
{0}/in
| length-parsec | ... |
|  | pc |
| one | {0} pc |
| other | {0} pc |
| length-light-year | ... |
|  | vv |
| one | {0} vv |
| other | {0} vv |
| length-astronomical-unit | ... |
|  | au |
| one | {0} au |
| other | {0} au |
| length-furlong | ... |
|  | fur |
| one | {0} fur |
| other | {0} fur |
| length-fathom | ... |
|  | fm |
| one | {0} fm |
| other | {0} fm |
| length-nautical-mile | ... |
|  | mpk |
| one | {0} mpk |
| other | {0} mpk |
| length-mile-scandinavian | ... |
|  | pnk |
| one | {0} pnk |
| other | {0} pnk |
| length-point | ... |
|  | pt |
| one | {0} pt |
| other | {0} pt |
| light-lux | ... |
|  | lx |
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
|  | g |
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
|  | am. tn |
| one | {0} am. tn |
| other | {0} am. tn |
| mass-stone | ... |
|  | st |
| one | {0} st |
| other | {0} st |
| mass-pound | ... |
|  | lb |
| one | {0} lb |
| other | {0} lb |
{0}/lb
| mass-ounce | ... |
|  | oz |
| one | {0} oz |
| other | {0} oz |
{0}/oz
| mass-ounce-troy | ... |
|  | oz t |
| one | {0} oz t |
| other | {0} oz t |
| mass-carat | ... |
|  | ka |
| one | {0} ka |
| other | {0} ka |
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
|  | W |
| one | {0} W |
| other | {0} W |
| power-milliwatt | ... |
|  | mW |
| one | {0} mW |
| other | {0} mW |
| power-horsepower | ... |
|  | hv |
| one | {0} hv |
| other | {0} hv |
| pressure-hectopascal | ... |
|  | hPa |
| one | {0} hPa |
| other | {0} hPa |
| pressure-millimeter-of-mercury | ... |
|  | mm Hg |
| one | {0} mm Hg |
| other | {0} mm Hg |
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
|  | km/h |
| one | {0} km/h |
| other | {0} km/h |
| speed-meter-per-second | ... |
|  | m/s |
| one | {0} m/s |
| other | {0} m/s |
| speed-mile-per-hour | ... |
|  | mi/h |
| one | {0} mi/h |
| other | {0} mi/h |
| speed-knot | ... |
|  | kn |
| one | {0} kn |
| other | {0} kn |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | °C |
| one | {0} °C |
| other | {0} °C |
| temperature-fahrenheit | ... |
|  | °F |
| one | {0} °F |
| other | {0} °F |
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
{0}/m³
| volume-cubic-centimeter | ... |
|  | cm³ |
| one | {0} cm³ |
| other | {0} cm³ |
{0}/cm³
| volume-cubic-mile | ... |
|  | mi³ |
| one | {0} mi³ |
| other | {0} mi³ |
| volume-cubic-yard | ... |
|  | yd³ |
| one | {0} yd³ |
| other | {0} yd³ |
| volume-cubic-foot | ... |
|  | ft³ |
| one | {0} ft³ |
| other | {0} ft³ |
| volume-cubic-inch | ... |
|  | in³ |
| one | {0} in³ |
| other | {0} in³ |
| volume-megaliter | ... |
|  | Ml |
| one | {0} Ml |
| other | {0} Ml |
| volume-hectoliter | ... |
|  | hl |
| one | {0} hl |
| other | {0} hl |
| volume-liter | ... |
|  | l |
| one | {0} l |
| other | {0} l |
{0}/l
| volume-deciliter | ... |
|  | dl |
| one | {0} dl |
| other | {0} dl |
| volume-centiliter | ... |
|  | cl |
| one | {0} cl |
| other | {0} cl |
| volume-milliliter | ... |
|  | ml |
| one | {0} ml |
| other | {0} ml |
| volume-pint-metric | ... |
|  | tp |
| one | {0} tp |
| other | {0} tp |
| volume-cup-metric | ... |
|  | tkp |
| one | {0} tkp |
| other | {0} tkp |
| volume-acre-foot | ... |
|  | ac ft |
| one | {0} ac ft |
| other | {0} ac ft |
| volume-bushel | ... |
|  | bu |
| one | {0} bu |
| other | {0} bu |
| volume-gallon | ... |
|  | am. gal |
| one | {0} am. gal |
| other | {0} am. gal |
{0}/am. gal
| volume-gallon-imperial | ... |
|  | br. gal |
| one | {0} br. gal |
| other | {0} br. gal |
{0}/br. gal
| volume-quart | ... |
|  | qt |
| one | {0} qt |
| other | {0} qt |
| volume-pint | ... |
|  | pt |
| one | {0} pt |
| other | {0} pt |
| volume-cup | ... |
|  | kp |
| one | {0} kp |
| other | {0} kp |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0} fl oz |
| other | {0} fl oz |
| volume-tablespoon | ... |
|  | rkl |
| one | {0} rkl |
| other | {0} rkl |
| volume-teaspoon | ... |
|  | tl |
| one | {0} tl |
| other | {0} tl |
{0}I{0}P{0}E{0}L
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | G |
| one | {0}G |
| other | {0}G |
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
|  | ° |
| one | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | ′ |
| one | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | ″ |
| one | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
|  | km² |
| one | {0}km² |
| other | {0}km² |
{0}/km²
| area-hectare | ... |
|  | ha |
| one | {0}ha |
| other | {0}ha |
| area-square-meter | ... |
|  | m² |
| one | {0}m² |
| other | {0}m² |
{0}/m²
| area-square-centimeter | ... |
|  | cm² |
| one | {0}cm² |
| other | {0}cm² |
{0}/cm²
| area-square-mile | ... |
|  | mi² |
| one | {0}mi² |
| other | {0}mi² |
{0}/mi²
| area-acre | ... |
|  | ac |
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
{0}/in²
| concentr-karat | ... |
|  | ka |
| one | {0}ka |
| other | {0}ka |
| concentr-milligram-per-deciliter | ... |
|  | mg/dl |
| one | {0}mg/dl |
| other | {0}mg/dl |
| concentr-millimole-per-liter | ... |
|  | mmol/l |
| one | {0}mmol/l |
| other | {0}mmol/l |
| concentr-part-per-million | ... |
|  | ppm |
| one | {0}ppm |
| other | {0}ppm |
| consumption-liter-per-kilometer | ... |
|  | l/km |
| one | {0}l/km |
| other | {0}l/km |
| consumption-liter-per-100kilometers | ... |
|  | l/100km |
| one | {0}l/100km |
| other | {0}l/100km |
| consumption-mile-per-gallon | ... |
|  | mpg-am |
| one | {0}mpg-am |
| other | {0}mpg-am |
| consumption-mile-per-gallon-imperial | ... |
|  | mpg-br |
| one | {0}mpg-br |
| other | {0}mpg-br |
| digital-terabyte | ... |
|  | Tt |
| one | {0}Tt |
| other | {0}Tt |
| digital-terabit | ... |
|  | Tb |
| one | {0}Tb |
| other | {0}Tb |
| digital-gigabyte | ... |
|  | Gt |
| one | {0}Gt |
| other | {0}Gt |
| digital-gigabit | ... |
|  | Gb |
| one | {0}Gb |
| other | {0}Gb |
| digital-megabyte | ... |
|  | Mt |
| one | {0}Mt |
| other | {0}Mt |
| digital-megabit | ... |
|  | Mb |
| one | {0}Mb |
| other | {0}Mb |
| digital-kilobyte | ... |
|  | kt |
| one | {0}kt |
| other | {0}kt |
| digital-kilobit | ... |
|  | kb |
| one | {0}kb |
| other | {0}kb |
| digital-byte | ... |
|  | t |
| one | {0}t |
| other | {0}t |
| digital-bit | ... |
|  | b |
| one | {0}b |
| other | {0}b |
| duration-century | ... |
|  | vs |
| one | {0} vs |
| other | {0} vs |
| duration-year | ... |
|  | v |
| one | {0}v |
| other | {0}v |
{0}/v
| duration-month | ... |
|  | kk |
| one | {0}kk |
| other | {0}kk |
{0}/kk
| duration-week | ... |
|  | vk |
| one | {0}vk |
| other | {0}vk |
{0}/vk
| duration-day | ... |
|  | pv |
| one | {0}pv |
| other | {0}pv |
{0}/pv
| duration-hour | ... |
|  | t |
| one | {0}t |
| other | {0}t |
{0}/t
| duration-minute | ... |
|  | min |
| one | {0}min |
| other | {0}min |
{0}/min
| duration-second | ... |
|  | s |
| one | {0}s |
| other | {0}s |
{0}/s
| duration-millisecond | ... |
|  | ms |
| one | {0}ms |
| other | {0}ms |
| duration-microsecond | ... |
|  | μs |
| one | {0}μs |
| other | {0}μs |
| duration-nanosecond | ... |
|  | ns |
| one | {0}ns |
| other | {0}ns |
| electric-ampere | ... |
|  | A |
| one | {0}A |
| other | {0}A |
| electric-milliampere | ... |
|  | mA |
| one | {0}mA |
| other | {0}mA |
| electric-ohm | ... |
|  | Ω |
| one | {0}Ω |
| other | {0}Ω |
| electric-volt | ... |
|  | V |
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
|  | kcal |
| one | {0}kcal |
| other | {0}kcal |
| energy-kilojoule | ... |
|  | kJ |
| one | {0}kJ |
| other | {0}kJ |
| energy-joule | ... |
|  | J |
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
{0}/km
| length-meter | ... |
|  | m |
| one | {0}m |
| other | {0}m |
{0}/m
| length-decimeter | ... |
|  | dm |
| one | {0}dm |
| other | {0}dm |
| length-centimeter | ... |
|  | cm |
| one | {0}cm |
| other | {0}cm |
{0}/cm
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
{0}/′
| length-inch | ... |
|  | in |
| one | {0}″ |
| other | {0}″ |
{0}/″
| length-parsec | ... |
|  | pc |
| one | {0}pc |
| other | {0}pc |
| length-light-year | ... |
|  | vv |
| one | {0}vv |
| other | {0}vv |
| length-astronomical-unit | ... |
|  | au |
| one | {0}au |
| other | {0}au |
| length-furlong | ... |
|  | fur |
| one | {0}fur |
| other | {0}fur |
| length-fathom | ... |
|  | fm |
| one | {0}fm |
| other | {0}fm |
| length-nautical-mile | ... |
|  | mpk |
| one | {0}mpk |
| other | {0}mpk |
| length-mile-scandinavian | ... |
|  | pnk |
| one | {0}pnk |
| other | {0}pnk |
| light-lux | ... |
|  | lx |
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
{0}/kg
| mass-gram | ... |
|  | g |
| one | {0}g |
| other | {0}g |
{0}/g
| mass-milligram | ... |
|  | mg |
| one | {0}mg |
| other | {0}mg |
| mass-microgram | ... |
|  | µg |
| one | {0}μg |
| other | {0}μg |
| mass-ton | ... |
|  | am.tn |
| one | {0}am.tn |
| other | {0}am.tn |
| mass-stone | ... |
|  | st |
| one | {0}st |
| other | {0}st |
| mass-pound | ... |
|  | lb |
| one | {0}lb |
| other | {0}lb |
{0}/lb
| mass-ounce | ... |
|  | oz |
| one | {0}oz |
| other | {0}oz |
{0}/oz
| mass-ounce-troy | ... |
|  | oz t |
| one | {0}oz t |
| other | {0}oz t |
| mass-carat | ... |
|  | ka |
| one | {0}ka |
| other | {0}ka |
| power-gigawatt | ... |
|  | GW |
| one | {0}GW |
| other | {0}GW |
| power-megawatt | ... |
|  | MW |
| one | {0}MW |
| other | {0} MW |
| power-kilowatt | ... |
|  | kW |
| one | {0}kW |
| other | {0}kW |
| power-watt | ... |
|  | W |
| one | {0}W |
| other | {0}W |
| power-milliwatt | ... |
|  | mW |
| one | {0}mW |
| other | {0}mW |
| power-horsepower | ... |
|  | hv |
| one | {0}hv |
| other | {0}hv |
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
|  | inHg |
| one | {0}″ Hg |
| other | {0}″ Hg |
| pressure-millibar | ... |
|  | mbar |
| one | {0}mbar |
| other | {0}mbar |
| speed-kilometer-per-hour | ... |
|  | km/h |
| one | {0}km/h |
| other | {0}km/h |
| speed-meter-per-second | ... |
|  | m/s |
| one | {0}m/s |
| other | {0}m/s |
| speed-mile-per-hour | ... |
|  | mi/h |
| one | {0}mi/h |
| other | {0}mi/h |
| speed-knot | ... |
|  | kn |
| one | {0}kn |
| other | {0}kn |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | °C |
| one | {0}° |
| other | {0}° |
| temperature-fahrenheit | ... |
|  | °F |
| one | {0}°F |
| other | {0}°F |
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
|  | Ml |
| one | {0}Ml |
| other | {0}Ml |
| volume-hectoliter | ... |
|  | hl |
| one | {0}hl |
| other | {0}hl |
| volume-liter | ... |
|  | l |
| one | {0}l |
| other | {0}l |
{0}/l
| volume-deciliter | ... |
|  | dl |
| one | {0}dl |
| other | {0}dl |
| volume-centiliter | ... |
|  | cl |
| one | {0}cl |
| other | {0}cl |
| volume-milliliter | ... |
|  | ml |
| one | {0}ml |
| other | {0}ml |
| volume-pint-metric | ... |
|  | tp |
| one | {0}tp |
| other | {0}tp |
| volume-cup-metric | ... |
|  | tkp |
| one | {0}tkp |
| other | {0}tkp |
| volume-acre-foot | ... |
|  | ac ft |
| one | {0}ac ft |
| other | {0}ac ft |
| volume-bushel | ... |
|  | bu |
| one | {0}bu |
| other | {0}bu |
| volume-gallon | ... |
|  | am.gal |
| one | {0}am.gal |
| other | {0}am.gal |
{0}/am.gal
| volume-gallon-imperial | ... |
|  | br.gal |
| one | {0}br.gal |
| other | {0}br.gal |
{0}/br.gal
| volume-quart | ... |
|  | qt |
| one | {0}qt |
| other | {0}qt |
| volume-pint | ... |
|  | pt |
| one | {0}pt |
| other | {0}pt |
| volume-cup | ... |
|  | kp |
| one | {0}kp |
| other | {0}kp |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0}fl oz |
| other | {0}fl oz |
| volume-tablespoon | ... |
|  | rkl |
| one | {0}rkl |
| other | {0}rkl |
| volume-teaspoon | ... |
|  | tl |
| one | {0}tl |
| other | {0}tl |
{0}I{0}P{0}E{0}Lh.mmh.mm.ssm.ss

## Lists

| List type | Patterns |
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

kyllä:k
ei:e

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
