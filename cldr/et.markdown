---
layout: default
title: "CLDR Estonian (via LDML2markdown)"
---

## CLDR core data for Estonian

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a b c d e f g h i j k l m n o p q r s š z ž t u v w õ ä ö ü x y]` |
| auxiliary characters | `[á à â å ā æ ç é è ê ë ē í ì î ï ī ñ ó ò ŏ ô ø ō œ ú ù û ū]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S Š Z Ž T U V Õ Ä Ö Ü X Y]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- , ; \: ! ? . “ „ ( ) \[ \] \{ \} @]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} ööpäev |
| other example | {0} ööpäeva |
| Country Data and Default Content | et_EE |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Estonian is already written in latin script |

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

#### standard
```
					&[before 1]T<š<<<Š<z<<<Z<ž<<<Ž
					&[before 1]X<õ<<<Õ<ä<<<Ä<ö<<<Ö<ü<<<Ü

```

## CLDR minimal data for Estonian

**Needed soon after submitting new locale**.

### Required date-time formats


#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | jaan |
| month 2 | veebr |
| month 3 | märts |
| month 4 | apr |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | aug |
| month 9 | sept |
| month 10 | okt |
| month 11 | nov |
| month 12 | dets |
| month 1 | J |
| month 2 | V |
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
| month 1 | jaanuar |
| month 2 | veebruar |
| month 3 | märts |
| month 4 | aprill |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | august |
| month 9 | september |
| month 10 | oktoober |
| month 11 | november |
| month 12 | detsember |
| month 1 | jaan |
| month 2 | veebr |
| month 3 | märts |
| month 4 | apr |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | aug |
| month 9 | sept |
| month 10 | okt |
| month 11 | nov |
| month 12 | dets |
| month 1 | J |
| month 2 | V |
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
| month 1 | jaanuar |
| month 2 | veebruar |
| month 3 | märts |
| month 4 | aprill |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | august |
| month 9 | september |
| month 10 | oktoober |
| month 11 | november |
| month 12 | detsember |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | pühapäev |
| (week)day mon | esmaspäev |
| (week)day tue | teisipäev |
| (week)day wed | kolmapäev |
| (week)day thu | neljapäev |
| (week)day fri | reede |
| (week)day sat | laupäev |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | pühapäev |
| (week)day mon | esmaspäev |
| (week)day tue | teisipäev |
| (week)day wed | kolmapäev |
| (week)day thu | neljapäev |
| (week)day fri | reede |
| (week)day sat | laupäev |
| quarter 1 | K1 |
| quarter 2 | K2 |
| quarter 3 | K3 |
| quarter 4 | K4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. kvartal |
| quarter 2 | 2. kvartal |
| quarter 3 | 3. kvartal |
| quarter 4 | 4. kvartal |
| quarter 1 | K1 |
| quarter 2 | K2 |
| quarter 3 | K3 |
| quarter 4 | K4 |
| quarter 1 | 1. |
| quarter 2 | 2. |
| quarter 3 | 3. |
| quarter 4 | 4. |
| quarter 1 | 1. kvartal |
| quarter 2 | 2. kvartal |
| quarter 3 | 3. kvartal |
| quarter 4 | 4. kvartal |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| era | enne Kristust |
| era | enne meie ajaarvamist |
| era | pärast Kristust |
| era | meie ajaarvamise järgi |
| era | eKr |
| era | e.m.a |
| era | pKr |
| era | m.a.j |
| era | eKr |
| era | e.m.a |
| era | pKr |
| era | m.a.j |
| date format | `EEEE, d. MMMM y` |
| date format | `d. MMMM y` |
| date format | `d. MMM y` |
| date format | `dd.MM.yy` |
| time format | `HH:mm:ss zzzz` |
| time format | `HH:mm:ss z` |
| time format | `HH:mm:ss` |
| time format | `HH:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E, d. MMMM y G` |
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
| date format `M` | `M` |
| date format `Md` | `d.M` |
| date format `MEd` | `E, d.M` |
| date format `MMM` | `MMMM` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `E, d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMEd` | `E, d. MMMM` |
| date format `MMMMW` | `MMM (W. 'nädal')` |
| date format `MMMMW` | `MMM (W. 'nädal')` |
| date format `mmss` | `mm:ss` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `M.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E, d.M.y` |
| date format `yMMM` | `MMM y` |
| date format `yMMMd` | `d. MMM y` |
| date format `yMMMEd` | `E, d. MMMM y` |
| date format `yMMMM` | `MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `w. 'nädal' (Y)` |
| date format `yw` | `w. 'nädal' (Y)` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `HH–HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `HH:mm–HH:mmHH:mm–HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `HH:mm–HH:mm vHH:mm–HH:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `HH–HH v` |
| interval format `M` | `MM–MM` |
| interval format `Md` | `dd.MM–dd.MMdd.MM–dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `d.–d. MMMd. MMM – d. MMM` |
| interval format `MMMEd` | `E, d. MMM – E, d. MMME, d. MMM – E, d. MMM` |
| interval format `y` | `y–y` |
| interval format `yM` | `MM.y–MM.yMM.y–MM.y` |
| interval format `yMd` | `dd.MM.y–dd.MM.ydd.MM.y–dd.MM.ydd.MM.y–dd.MM.y` |
| interval format `yMEd` | `E, dd.MM.y – E, dd.MM.yE, dd.MM.y – E, dd.MM.yE, dd.MM.y – E, dd.MM.y` |
| interval format `yMMM` | `MMM–MMM yMMM y – MMM y` |
| interval format `yMMMd` | `d.–d. MMM yd. MMM – d. MMM yd. MMM y – d. MMM y` |
| interval format `yMMMEd` | `E, d. MMM – E, d. MMM yE, d. MMM – E, d. MMM yE, d. MMM y – E, d. MMM y` |
| interval format `yMMMM` | `MMMM–MMMM yMMMM y – MMMM y` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `dd.MM.y G` |
| date format | `dd.MM.y GGGGG` |
| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E, d. MMMM y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm.ss a` |
| date format `Hms` | `H:mm.ss` |
| date format `M` | `M` |
| date format `Md` | `d.M` |
| date format `MEd` | `E, d.M` |
| date format `MMM` | `MMMM` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `E, d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMEd` | `E, d. MMMM` |
| date format `mmss` | `mm.ss` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E, d.M y G` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E, d. MMMM y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `HH–HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `HH:mm–HH:mmHH:mm–HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `HH:mm–HH:mm vHH:mm–HH:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `HH–HH v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM–dd.MMdd.MM–dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `d.–d. MMMd. MMM – d. MMM` |
| interval format `MMMEd` | `E, d. MMM – E, d. MMME, d. MMM – E, d. MMM` |
| interval format `y` | `y–y G` |
| interval format `yM` | `MM.y–MM.y GMM.y–MM.y G` |
| interval format `yMd` | `dd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y G` |
| interval format `yMEd` | `E, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y G` |
| interval format `yMMM` | `MMM–MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `d.–d. MMM y Gd. MMM – d. MMM y Gd. MMM y – d. MMM y G` |
| interval format `yMMMEd` | `E, d. MMM – E, d. MMM y GE, d. MMM – E, d. MMM y GE, d. MMM y – E, d. MMM y G` |
| interval format `yMMMM` | `MMMM–MMMM y GMMMM y – MMMM y G` |

### Important names in language

Language:

| `et` | eesti |

Country or territory:

| `EE` | Eesti |

Currency:

|  | euro |
| one | euro |
| other | eurot |
|  symbol | € |
| narrow symbol | € |

### Datetime patterns

| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E, d. MMMM y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm.ss a` |
| date format `Hms` | `H:mm.ss` |
| date format `M` | `M` |
| date format `Md` | `d.M` |
| date format `MEd` | `E, d.M` |
| date format `MMM` | `MMMM` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `E, d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMEd` | `E, d. MMMM` |
| date format `mmss` | `mm.ss` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E, d.M y G` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E, d. MMMM y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `HH–HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `HH:mm–HH:mmHH:mm–HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `HH:mm–HH:mm vHH:mm–HH:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `HH–HH v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM–dd.MMdd.MM–dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `d.–d. MMMd. MMM – d. MMM` |
| interval format `MMMEd` | `E, d. MMM – E, d. MMME, d. MMM – E, d. MMM` |
| interval format `y` | `y–y G` |
| interval format `yM` | `MM.y–MM.y GMM.y–MM.y G` |
| interval format `yMd` | `dd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y G` |
| interval format `yMEd` | `E, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y G` |
| interval format `yMMM` | `MMM–MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `d.–d. MMM y Gd. MMM – d. MMM y Gd. MMM y – d. MMM y G` |
| interval format `yMMMEd` | `E, d. MMM – E, d. MMM y GE, d. MMM – E, d. MMM y GE, d. MMM y – E, d. MMM y G` |
| interval format `yMMMM` | `MMMM–MMMM y GMMMM y – MMMM y G` |

### Number formats

| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | ×10^ |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | NaN |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

| Hours from UTC | +HH:mm;−HH:mm |
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
| `calendar` | kalender |
| `cf` | rahavorming |
| `colAlternate` | sümbolite eiramine järjestuses |
| `colBackwards` | diakriitikute pöördjärjestus |
| `colCaseFirst` | suur- ja väiketähe järjestus |
| `colCaseLevel` | järjestuse tõstutundlikkus |
| `collation` | sortimisjärjestus |
| `colNormalization` | normaliseeritud järjestus |
| `colNumeric` | numbrite järjestus |
| `colStrength` | järjestuskaalud |
| `currency` | vääring |
| `hc` | 12 või 24 tunni süsteem |
| `lb` | reavahetuse laad |
| `ms` | mõõdustik |
| `numbers` | numbrid |
| `timezone` | ajavöönd |
| `va` | lokaadi variant |
| `x` | erakasutus |

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13904 $et
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
| `aa` | afari |
| `ab` | abhaasi |
| `ace` | atšehi |
| `ach` | atšoli |
| `ada` | adangme |
| `ady` | adõgee |
| `ae` | avesta |
| `aeb` | Tuneesia araabia |
| `af` | afrikaani |
| `afh` | afrihili |
| `agq` | aghemi |
| `ain` | ainu |
| `ak` | akani |
| `akk` | akadi |
| `akz` | alabama |
| `ale` | aleuudi |
| `aln` | geegi |
| `alt` | altai |
| `am` | amhara |
| `an` | aragoni |
| `ang` | vanainglise |
| `anp` | angika |
| `ar` | araabia |
| `ar_001` | araabia (tänapäevane) |
| `arc` | aramea |
| `arn` | mapudunguni |
| `aro` | araona |
| `arp` | arapaho |
| `arq` | Alžeeria araabia |
| `arw` | aravaki |
| `ary` | Maroko araabia |
| `arz` | Egiptuse araabia |
| `as` | assami |
| `asa` | asu |
| `ase` | Ameerika viipekeel |
| `ast` | astuuria |
| `av` | avaari |
| `awa` | avadhi |
| `ay` | aimara |
| `az` | aserbaidžaani |
| `az` | aseri |
| `ba` | baškiiri |
| `bal` | belutši |
| `ban` | bali |
| `bar` | baieri |
| `bas` | basaa |
| `bax` | bamuni |
| `bbc` | bataki |
| `bbj` | ghomala |
| `be` | valgevene |
| `bej` | bedža |
| `bem` | bemba |
| `bew` | betavi |
| `bez` | bena |
| `bfd` | bafuti |
| `bfq` | badaga |
| `bg` | bulgaaria |
| `bgn` | läänebelutši |
| `bho` | bhodžpuri |
| `bi` | bislama |
| `bik` | bikoli |
| `bin` | edo |
| `bjn` | bandžari |
| `bkm` | komi (Aafrika) |
| `bla` | mustjalaindiaani |
| `bm` | bambara |
| `bn` | bengali |
| `bo` | tiibeti |
| `bpy` | bišnuprija |
| `bqi` | bahtiari |
| `br` | bretooni |
| `bra` | bradži |
| `brh` | brahui |
| `brx` | bodo |
| `bs` | bosnia |
| `bss` | akoose |
| `bua` | burjaadi |
| `bug` | bugi |
| `bum` | bulu |
| `byn` | bilini |
| `byv` | medumba |
| `ca` | katalaani |
| `cad` | kado |
| `car` | kariibi |
| `cay` | kajuka |
| `cch` | aitšami |
| `ce` | tšetšeeni |
| `ceb` | sebu |
| `cgg` | tšiga |
| `ch` | tšamorro |
| `chb` | tšibtša |
| `chg` | tšagatai |
| `chk` | tšuugi |
| `chm` | mari |
| `chn` | tšinuki žargoon |
| `cho` | tšokto |
| `chp` | tšipevai |
| `chr` | tšerokii |
| `chy` | šaieeni |
| `ckb` | sorani |
| `co` | korsika |
| `cop` | kopti |
| `cps` | kapisnoni |
| `cr` | krii |
| `crh` | krimmitatari |
| `crs` | seišelli |
| `cs` | tšehhi |
| `csb` | kašuubi |
| `cu` | kirikuslaavi |
| `cv` | tšuvaši |
| `cy` | kõmri |
| `da` | taani |
| `dak` | siuu |
| `dar` | dargi |
| `dav` | davida |
| `de` | saksa |
| `de_AT` | Austria saksa |
| `de_CH` | Šveitsi ülemsaksa |
| `del` | delavari |
| `den` | sleivi |
| `dgr` | dogribi |
| `din` | dinka |
| `dje` | zarma |
| `doi` | dogri |
| `dsb` | alamsorbi |
| `dtp` | keskdusuni |
| `dua` | duala |
| `dum` | keskhollandi |
| `dv` | maldiivi |
| `dyo` | fonji |
| `dyu` | djula |
| `dz` | dzongkha |
| `dzg` | daza |
| `ebu` | embu |
| `ee` | eve |
| `efi` | efiki |
| `egl` | emiilia |
| `egy` | egiptuse |
| `eka` | ekadžuki |
| `el` | kreeka |
| `elx` | eelami |
| `en` | inglise |
| `en_AU` | Austraalia inglise |
| `en_CA` | Kanada inglise |
| `en_GB` | Briti inglise |
| `en_GB` | Briti inglise |
| `en_US` | Ameerika inglise |
| `en_US` | USA inglise |
| `enm` | keskinglise |
| `eo` | esperanto |
| `es` | hispaania |
| `es_419` | Ladina-Ameerika hispaania |
| `es_ES` | Euroopa hispaania |
| `es_MX` | Mehhiko hispaania |
| `esu` | keskjupiki |
| `et` | eesti |
| `eu` | baski |
| `ewo` | evondo |
| `ext` | estremenju |
| `fa` | pärsia |
| `fan` | fangi |
| `fat` | fanti |
| `ff` | fula |
| `fi` | soome |
| `fil` | filipiini |
| `fit` | meä |
| `fj` | fidži |
| `fo` | fääri |
| `fon` | foni |
| `fr` | prantsuse |
| `fr_CA` | Kanada prantsuse |
| `fr_CH` | Šveitsi prantsuse |
| `frc` | cajun’i |
| `frm` | keskprantsuse |
| `fro` | vanaprantsuse |
| `frp` | frankoprovansi |
| `frr` | põhjafriisi |
| `frs` | idafriisi |
| `fur` | friuuli |
| `fy` | läänefriisi |
| `ga` | iiri |
| `gaa` | gaa |
| `gag` | gagauusi |
| `gan` | kani |
| `gay` | gajo |
| `gba` | gbaja |
| `gd` | gaeli |
| `gez` | etioopia |
| `gil` | kiribati |
| `gl` | galeegi |
| `glk` | gilaki |
| `gmh` | keskülemsaksa |
| `gn` | guaranii |
| `goh` | vanaülemsaksa |
| `gon` | gondi |
| `gor` | gorontalo |
| `got` | gooti |
| `grb` | grebo |
| `grc` | vanakreeka |
| `gsw` | šveitsisaksa |
| `gu` | gudžarati |
| `guc` | vajuu |
| `gur` | farefare |
| `guz` | gusii |
| `gv` | mänksi |
| `gwi` | gvitšini |
| `ha` | hausa |
| `hai` | haida |
| `hak` | hakka |
| `haw` | havai |
| `he` | heebrea |
| `hi` | hindi |
| `hif` | Fidži hindi |
| `hil` | hiligainoni |
| `hit` | heti |
| `hmn` | hmongi |
| `ho` | hirimotu |
| `hr` | horvaadi |
| `hsb` | ülemsorbi |
| `hsn` | sjangi |
| `ht` | haiti |
| `hu` | ungari |
| `hup` | hupa |
| `hy` | armeenia |
| `hz` | herero |
| `ia` | interlingua |
| `iba` | ibani |
| `ibb` | ibibio |
| `id` | indoneesia |
| `ie` | interlingue |
| `ig` | ibo |
| `ii` | Sichuani jii |
| `ik` | injupiaki |
| `ilo` | iloko |
| `inh` | inguši |
| `io` | ido |
| `is` | islandi |
| `it` | itaalia |
| `iu` | inuktituti |
| `izh` | isuri |
| `ja` | jaapani |
| `jam` | Jamaica kreoolkeel |
| `jbo` | ložban |
| `jgo` | ngomba |
| `jmc` | matšame |
| `jpr` | juudipärsia |
| `jrb` | juudiaraabia |
| `jut` | jüüti |
| `jv` | jaava |
| `ka` | gruusia |
| `kaa` | karakalpaki |
| `kab` | kabiili |
| `kac` | katšini |
| `kaj` | jju |
| `kam` | kamba |
| `kaw` | kaavi |
| `kbd` | kabardi-tšerkessi |
| `kbl` | kanembu |
| `kcg` | tjapi |
| `kde` | makonde |
| `kea` | kabuverdianu |
| `kfo` | koro |
| `kg` | kongo |
| `kgp` | kaingangi |
| `kha` | khasi |
| `kho` | saka |
| `khq` | koyra chiini |
| `khw` | khovari |
| `ki` | kikuju |
| `kiu` | kõrmandžki |
| `kj` | kvanjama |
| `kk` | kasahhi |
| `kkj` | kako |
| `kl` | grööni |
| `kln` | kalendžini |
| `km` | khmeeri |
| `kmb` | mbundu |
| `kn` | kannada |
| `ko` | korea |
| `koi` | permikomi |
| `kok` | konkani |
| `kos` | kosrae |
| `kpe` | kpelle |
| `kr` | kanuri |
| `krc` | karatšai-balkaari |
| `kri` | krio |
| `krj` | kinaraia |
| `krl` | karjala |
| `kru` | kuruhhi |
| `ks` | kašmiiri |
| `ksb` | šambala |
| `ksf` | bafia |
| `ksh` | kölni |
| `ku` | kurdi |
| `kum` | kumõki |
| `kut` | kutenai |
| `kv` | komi |
| `kw` | korni |
| `ky` | kirgiisi |
| `la` | ladina |
| `lad` | ladiino |
| `lag` | langi |
| `lah` | lahnda |
| `lam` | lamba |
| `lb` | letseburgi |
| `lez` | lesgi |
| `lg` | ganda |
| `li` | limburgi |
| `lij` | liguuri |
| `liv` | liivi |
| `lkt` | lakota |
| `lmo` | lombardi |
| `ln` | lingala |
| `lo` | lao |
| `lol` | mongo |
| `lou` | Louisiana kreoolkeel |
| `loz` | lozi |
| `lrc` | põhjaluri |
| `lt` | leedu |
| `ltg` | latgali |
| `lu` | luba |
| `lua` | lulua |
| `lui` | luisenjo |
| `lun` | lunda |
| `luo` | luo |
| `lus` | lušei |
| `luy` | luhja |
| `lv` | läti |
| `lzh` | klassikaline hiina |
| `lzz` | lazi |
| `mad` | madura |
| `maf` | mafa |
| `mag` | magahi |
| `mai` | maithili |
| `mak` | makassari |
| `man` | malinke |
| `mas` | masai |
| `mde` | maba |
| `mdf` | mokša |
| `mdr` | mandari |
| `men` | mende |
| `mer` | meru |
| `mfe` | Mauritiuse kreoolkeel |
| `mg` | malagassi |
| `mga` | keskiiri |
| `mgh` | makhuwa-meetto |
| `mgo` | meta |
| `mh` | maršalli |
| `mi` | maoori |
| `mic` | mikmaki |
| `min` | minangkabau |
| `mk` | makedoonia |
| `ml` | malajalami |
| `mn` | mongoli |
| `mnc` | mandžu |
| `mni` | manipuri |
| `moh` | mohoogi |
| `mos` | more |
| `mr` | marathi |
| `mrj` | mäemari |
| `ms` | malai |
| `mt` | malta |
| `mua` | mundangi |
| `mul` | mitu keelt |
| `mus` | maskogi |
| `mwl` | miranda |
| `mwr` | marvari |
| `mwv` | mentavei |
| `my` | birma |
| `mye` | mjene |
| `myv` | ersa |
| `mzn` | mazandaraani |
| `na` | nauru |
| `nan` | lõunamini |
| `nap` | napoli |
| `naq` | nama |
| `nb` | norra bokmål |
| `nd` | põhjandebele |
| `nds` | alamsaksa |
| `nds_NL` | Hollandi alamsaksa |
| `ne` | nepali |
| `new` | nevari |
| `ng` | ndonga |
| `nia` | niasi |
| `niu` | niue |
| `njo` | ao |
| `nl` | hollandi |
| `nl_BE` | flaami |
| `nmg` | kwasio |
| `nn` | uusnorra |
| `nnh` | ngiembooni |
| `no` | norra |
| `nog` | nogai |
| `non` | vanapõhjala |
| `nov` | noviaal |
| `nqo` | nkoo |
| `nr` | lõunandebele |
| `nso` | põhjasotho |
| `nus` | nueri |
| `nv` | navaho |
| `nwc` | vananevari |
| `ny` | njandža |
| `nym` | njamvesi |
| `nyn` | nkole |
| `nyo` | njoro |
| `nzi` | nzima |
| `oc` | oksitaani |
| `oj` | odžibvei |
| `om` | oromo |
| `or` | oria |
| `os` | osseedi |
| `osa` | oseidži |
| `ota` | osmanitürgi |
| `pa` | pandžabi |
| `pag` | pangasinani |
| `pal` | pahlavi |
| `pam` | pampanga |
| `pap` | papiamento |
| `pau` | belau |
| `pcd` | pikardi |
| `pcm` | Nigeeria pidžinkeel |
| `pdc` | Pennsylvania saksa |
| `pdt` | mennoniidisaksa |
| `peo` | vanapärsia |
| `pfl` | Pfalzi |
| `phn` | foiniikia |
| `pi` | paali |
| `pl` | poola |
| `pms` | piemonte |
| `pnt` | pontose |
| `pon` | poonpei |
| `prg` | preisi |
| `pro` | vanaprovansi |
| `ps` | puštu |
| `pt` | portugali |
| `pt_BR` | Brasiilia portugali |
| `pt_PT` | Euroopa portugali |
| `qu` | ketšua |
| `quc` | kitše |
| `raj` | radžastani |
| `rap` | rapanui |
| `rar` | rarotonga |
| `rgn` | romanja |
| `rif` | riifi |
| `rm` | romanši |
| `rn` | rundi |
| `ro` | rumeenia |
| `ro_MD` | moldova |
| `rof` | rombo |
| `rom` | mustlaskeel |
| `root` | root |
| `rtm` | rotuma |
| `ru` | vene |
| `rue` | russiini |
| `rug` | roviana |
| `rup` | aromuuni |
| `rw` | ruanda |
| `rwk` | rvaa |
| `sa` | sanskriti |
| `sad` | sandave |
| `sah` | jakuudi |
| `sam` | Samaaria aramea |
| `saq` | samburu |
| `sas` | sasaki |
| `sat` | santali |
| `saz` | sauraštra |
| `sba` | ngambai |
| `sbp` | sangu |
| `sc` | sardi |
| `scn` | sitsiilia |
| `sco` | šoti |
| `sd` | sindhi |
| `sdh` | lõunakurdi |
| `se` | põhjasaami |
| `see` | seneka |
| `seh` | sena |
| `sei` | seri |
| `sel` | sölkupi |
| `ses` | koyraboro senni |
| `sg` | sango |
| `sga` | vanaiiri |
| `sgs` | žemaidi |
| `sh` | serbia-horvaadi |
| `shi` | šilha |
| `shn` | šani |
| `shu` | Tšaadi araabia |
| `si` | singali |
| `sid` | sidamo |
| `sk` | slovaki |
| `sl` | sloveeni |
| `sli` | alamsileesia |
| `sly` | selajari |
| `sm` | samoa |
| `sma` | lõunasaami |
| `smj` | Lule saami |
| `smn` | Inari saami |
| `sms` | koltasaami |
| `sn` | šona |
| `snk` | soninke |
| `so` | somaali |
| `sog` | sogdi |
| `sq` | albaania |
| `sr` | serbia |
| `srn` | sranani |
| `srr` | sereri |
| `ss` | svaasi |
| `ssy` | saho |
| `st` | lõunasotho |
| `stq` | saterfriisi |
| `su` | sunda |
| `suk` | sukuma |
| `sus` | susu |
| `sux` | sumeri |
| `sv` | rootsi |
| `sw` | suahiili |
| `sw_CD` | Kongo suahiili |
| `swb` | komoori |
| `syc` | vanasüüria |
| `syr` | süüria |
| `szl` | sileesia |
| `ta` | tamili |
| `tcy` | tulu |
| `te` | telugu |
| `tem` | temne |
| `teo` | teso |
| `ter` | tereno |
| `tet` | tetumi |
| `tg` | tadžiki |
| `th` | tai |
| `ti` | tigrinja |
| `tig` | tigree |
| `tiv` | tivi |
| `tk` | türkmeeni |
| `tkl` | tokelau |
| `tkr` | tsahhi |
| `tl` | tagalogi |
| `tlh` | klingoni |
| `tli` | tlingiti |
| `tly` | talõši |
| `tmh` | tamašeki |
| `tn` | tsvana |
| `to` | tonga |
| `tog` | tšitonga |
| `tpi` | uusmelaneesia |
| `tr` | türgi |
| `tru` | turojo |
| `trv` | taroko |
| `ts` | tsonga |
| `tsd` | tsakoonia |
| `tsi` | tšimši |
| `tt` | tatari |
| `ttt` | lõunataadi |
| `tum` | tumbuka |
| `tvl` | tuvalu |
| `tw` | tvii |
| `twq` | taswaqi |
| `ty` | tahiti |
| `tyv` | tõva |
| `tzm` | tamasikti |
| `udm` | udmurdi |
| `ug` | uiguuri |
| `uga` | ugariti |
| `uk` | ukraina |
| `umb` | umbundu |
| `und` | määramata keel |
| `ur` | urdu |
| `uz` | usbeki |
| `vai` | vai |
| `ve` | venda |
| `vec` | veneti |
| `vep` | vepsa |
| `vi` | vietnami |
| `vls` | lääneflaami |
| `vmf` | Maini frangi |
| `vo` | volapüki |
| `vot` | vadja |
| `vro` | võru |
| `vun` | vundžo |
| `wa` | vallooni |
| `wae` | walseri |
| `wal` | volaita |
| `war` | varai |
| `was` | vašo |
| `wbp` | varlpiri |
| `wo` | volofi |
| `wuu` | uu |
| `xal` | kalmõki |
| `xh` | koosa |
| `xmf` | megreli |
| `xog` | soga |
| `yao` | jao |
| `yap` | japi |
| `yav` | yangbeni |
| `ybb` | jemba |
| `yi` | jidiši |
| `yo` | joruba |
| `yrl` | njengatu |
| `yue` | kantoni |
| `za` | tšuangi |
| `zap` | sapoteegi |
| `zbl` | Blissi sümbolid |
| `zea` | zeelandi |
| `zen` | zenaga |
| `zgh` | tamasikti (Maroko) |
| `zh` | hiina |
| `zh_Hans` | lihtsustatud hiina |
| `zh_Hant` | traditsiooniline hiina |
| `zu` | suulu |
| `zun` | sunji |
| `zxx` | mittekeeleline |
| `zza` | zaza |
### Script names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `Afak` | afaka |
| `Aghb` | albaani |
| `Ahom` | ahomi |
| `Arab` | araabia |
| `Arab` | pärsia-araabia |
| `Armi` | vanaaramea |
| `Armn` | armeenia |
| `Avst` | avesta |
| `Bali` | bali |
| `Bamu` | bamumi |
| `Bass` | bassa |
| `Batk` | bataki |
| `Beng` | bengali |
| `Blis` | Blissi sümbolid |
| `Bopo` | bopomofo |
| `Brah` | braahmi |
| `Brai` | punktkiri |
| `Bugi` | bugi |
| `Buhd` | buhidi |
| `Cakm` | tšaakma |
| `Cans` | Kanada põlisrahvaste ühtlustatud silpkiri |
| `Cari` | kaaria |
| `Cham` | tšaami |
| `Cher` | tšerokii |
| `Cirt` | Cirthi |
| `Copt` | kopti |
| `Cprt` | Küprose silpkiri |
| `Cyrl` | kirillitsa |
| `Cyrs` | kürilliline kirikuslaavi |
| `Deva` | devanaagari |
| `Dsrt` | desereti |
| `Dupl` | Duployé kiirkiri |
| `Egyd` | egiptuse demootiline |
| `Egyh` | egiptuse hieraatiline |
| `Egyp` | egiptuse hieroglüüfkiri |
| `Elba` | Elbasani |
| `Ethi` | etioopia |
| `Geok` | hutsuri |
| `Geor` | gruusia |
| `Glag` | glagoolitsa |
| `Gonm` | Masarami gondi |
| `Goth` | gooti |
| `Gran` | grantha |
| `Grek` | kreeka |
| `Gujr` | gudžarati |
| `Guru` | gurmukhi |
| `Hanb` | hanbi |
| `Hang` | korea |
| `Hani` | hani |
| `Hano` | hanunoo |
| `Hans` | lihtsustatud |
| `Hans` | lihtsustatud hani |
| `Hant` | traditsiooniline |
| `Hant` | traditsiooniline hani |
| `Hatr` | Hatra |
| `Hebr` | heebrea |
| `Hira` | hiragana |
| `Hluw` | Anatoolia hieroglüüfkiri |
| `Hmng` | phahau-hmongi kiri |
| `Hrkt` | jaapani silpkirjad |
| `Hung` | vanaungari |
| `Inds` | Induse |
| `Ital` | vanaitali |
| `Jamo` | jamo |
| `Java` | jaava |
| `Jpan` | jaapani |
| `Jurc` | tšurtšeni |
| `Kali` | kaja-lii |
| `Kana` | katakana |
| `Khar` | kharoshthi |
| `Khmr` | khmeeri |
| `Khoj` | hodžki |
| `Knda` | kannada |
| `Kore` | korea segakiri |
| `Kpel` | kpelle |
| `Kthi` | kaithi |
| `Lana` | tai-thami |
| `Laoo` | lao |
| `Latf` | ladina fraktuurkiri |
| `Latg` | ladina gaeli |
| `Latn` | ladina |
| `Lepc` | leptša |
| `Limb` | limbu |
| `Lina` | lineaarkiri A |
| `Linb` | lineaarkiri B |
| `Lisu` | lisu |
| `Loma` | loma |
| `Lyci` | lüükia |
| `Lydi` | lüüdia |
| `Mahj` | mahaadžani |
| `Mand` | mandea |
| `Mani` | mani |
| `Maya` | maaja hieroglüüfkiri |
| `Mend` | mende |
| `Merc` | meroe kursiivkiri |
| `Mero` | meroe |
| `Mlym` | malajalami |
| `Modi` | modi |
| `Mong` | mongoli |
| `Moon` | Mooni |
| `Mroo` | mruu |
| `Mtei` | meitei |
| `Mult` | Multani |
| `Mymr` | birma |
| `Narb` | Põhja-Araabia |
| `Nbat` | Nabatea |
| `Newa` | nevari |
| `Nkgb` | nasi |
| `Nkoo` | nkoo |
| `Nshu` | nüšu |
| `Ogam` | ogam |
| `Olck` | santali |
| `Orkh` | Orhoni |
| `Orya` | oria |
| `Osge` | oseidži |
| `Osma` | osmani |
| `Palm` | Palmyra |
| `Perm` | vanapermi |
| `Phag` | phakpa |
| `Phli` | pahlavi raidkiri |
| `Phlp` | pahlavi psalmikiri |
| `Phlv` | pahlavi raamatukiri |
| `Phnx` | foiniikia |
| `Plrd` | Pollardi miao |
| `Prti` | partia raidkiri |
| `Rjng` | redžangi |
| `Roro` | rongorongo |
| `Runr` | ruunikiri |
| `Samr` | Samaaria |
| `Sara` | sarati |
| `Sarb` | Lõuna-Araabia |
| `Saur` | sauraštra |
| `Sgnw` | viipekiri |
| `Shaw` | Shaw’ kiri |
| `Shrd` | šaarada |
| `Sidd` | siddhami |
| `Sind` | hudavadi |
| `Sinh` | singali |
| `Sora` | sora |
| `Soyo` | sojombo |
| `Sund` | sunda |
| `Sylo` | siloti |
| `Syrc` | süüria |
| `Syre` | süüria estrangelo |
| `Syrj` | läänesüüria |
| `Syrn` | idasüüria |
| `Tagb` | tagbanva |
| `Takr` | taakri |
| `Tale` | tai-löö |
| `Talu` | uus tai-lõõ |
| `Taml` | tamili |
| `Tang` | tanguudi |
| `Tavt` | tai-vieti |
| `Telu` | telugu |
| `Teng` | Tengwari |
| `Tfng` | tifinagi |
| `Tglg` | tagalogi |
| `Thaa` | taana |
| `Thai` | tai |
| `Tibt` | tiibeti |
| `Tirh` | tirhuta |
| `Ugar` | ugariti |
| `Vaii` | vai |
| `Visp` | nähtava kõne |
| `Wara` | hoo |
| `Wole` | voleai |
| `Xpeo` | vanapärsia |
| `Xsux` | sumeri-akadi kiilkiri |
| `Yiii` | jii |
| `Zanb` | Dzanabadzari ruutkiri |
| `Zinh` | päritud |
| `Zmth` | matemaatiline tähistus |
| `Zsye` | emoji |
| `Zsym` | sümbolid |
| `Zxxx` | kirjakeeleta |
| `Zyyy` | üldine |
| `Zzzz` | määramata kiri |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `001` | maailm |
| `002` | Aafrika |
| `003` | Põhja-Ameerika |
| `005` | Lõuna-Ameerika |
| `009` | Okeaania |
| `011` | Lääne-Aafrika |
| `013` | Kesk-Ameerika |
| `014` | Ida-Aafrika |
| `015` | Põhja-Aafrika |
| `017` | Kesk-Aafrika |
| `018` | Lõuna-Aafrika |
| `019` | Ameerika |
| `021` | Ameerika põhjaosa |
| `029` | Kariibi piirkond |
| `030` | Ida-Aasia |
| `034` | Lõuna-Aasia |
| `035` | Kagu-Aasia |
| `039` | Lõuna-Euroopa |
| `053` | Australaasia |
| `054` | Melaneesia |
| `057` | Mikroneesia (piirkond) |
| `061` | Polüneesia |
| `142` | Aasia |
| `143` | Kesk-Aasia |
| `145` | Lääne-Aasia |
| `150` | Euroopa |
| `151` | Ida-Euroopa |
| `154` | Põhja-Euroopa |
| `155` | Lääne-Euroopa |
| `202` | Sahara-tagune Aafrika |
| `419` | Ladina-Ameerika |
| `AC` | Ascensioni saar |
| `AD` | Andorra |
| `AE` | Araabia Ühendemiraadid |
| `AF` | Afganistan |
| `AG` | Antigua ja Barbuda |
| `AI` | Anguilla |
| `AL` | Albaania |
| `AM` | Armeenia |
| `AO` | Angola |
| `AQ` | Antarktika |
| `AR` | Argentina |
| `AS` | Ameerika Samoa |
| `AT` | Austria |
| `AU` | Austraalia |
| `AW` | Aruba |
| `AX` | Ahvenamaa |
| `AZ` | Aserbaidžaan |
| `BA` | Bosnia ja Hertsegoviina |
| `BB` | Barbados |
| `BD` | Bangladesh |
| `BE` | Belgia |
| `BF` | Burkina Faso |
| `BG` | Bulgaaria |
| `BH` | Bahrein |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | Saint-Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Boliivia |
| `BQ` | Hollandi Kariibi mere saared |
| `BR` | Brasiilia |
| `BS` | Bahama |
| `BT` | Bhutan |
| `BV` | Bouvet’ saar |
| `BW` | Botswana |
| `BY` | Valgevene |
| `BZ` | Belize |
| `CA` | Kanada |
| `CC` | Kookossaared |
| `CD` | Kongo DV |
| `CD` | Kongo-Kinshasa |
| `CF` | Kesk-Aafrika Vabariik |
| `CG` | Kongo Vabariik |
| `CG` | Kongo-Brazzaville |
| `CH` | Šveits |
| `CI` | Côte d’Ivoire |
| `CI` | Elevandiluurannik |
| `CK` | Cooki saared |
| `CL` | Tšiili |
| `CM` | Kamerun |
| `CN` | Hiina |
| `CO` | Colombia |
| `CP` | Clippertoni saar |
| `CR` | Costa Rica |
| `CU` | Kuuba |
| `CV` | Roheneemesaared |
| `CW` | Curaçao |
| `CX` | Jõulusaar |
| `CY` | Küpros |
| `CZ` | Tšehhi |
| `CZ` | Tšehhia |
| `DE` | Saksamaa |
| `DG` | Diego Garcia |
| `DJ` | Djibouti |
| `DK` | Taani |
| `DM` | Dominica |
| `DO` | Dominikaani Vabariik |
| `DZ` | Alžeeria |
| `EA` | Ceuta ja Melilla |
| `EC` | Ecuador |
| `EE` | Eesti |
| `EG` | Egiptus |
| `EH` | Lääne-Sahara |
| `ER` | Eritrea |
| `ES` | Hispaania |
| `ET` | Etioopia |
| `EU` | Euroopa Liit |
| `EZ` | euroala |
| `FI` | Soome |
| `FJ` | Fidži |
| `FK` | Falklandi saared |
| `FK` | Malviini saared |
| `FM` | Mikroneesia |
| `FO` | Fääri saared |
| `FR` | Prantsusmaa |
| `GA` | Gabon |
| `GB` | Suurbritannia |
| `GB` | ÜK |
| `GD` | Grenada |
| `GE` | Gruusia |
| `GF` | Prantsuse Guajaana |
| `GG` | Guernsey |
| `GH` | Ghana |
| `GI` | Gibraltar |
| `GL` | Gröönimaa |
| `GM` | Gambia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Ekvatoriaal-Guinea |
| `GR` | Kreeka |
| `GS` | Lõuna-Georgia ja Lõuna-Sandwichi saared |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Guinea-Bissau |
| `GY` | Guyana |
| `HK` | Hongkongi erihalduspiirkond |
| `HK` | Hongkong |
| `HM` | Heardi ja McDonaldi saared |
| `HN` | Honduras |
| `HR` | Horvaatia |
| `HT` | Haiti |
| `HU` | Ungari |
| `IC` | Kanaari saared |
| `ID` | Indoneesia |
| `IE` | Iirimaa |
| `IL` | Iisrael |
| `IM` | Mani saar |
| `IN` | India |
| `IO` | Briti India ookeani ala |
| `IQ` | Iraak |
| `IR` | Iraan |
| `IS` | Island |
| `IT` | Itaalia |
| `JE` | Jersey |
| `JM` | Jamaica |
| `JO` | Jordaania |
| `JP` | Jaapan |
| `KE` | Keenia |
| `KG` | Kõrgõzstan |
| `KH` | Kambodža |
| `KI` | Kiribati |
| `KM` | Komoorid |
| `KN` | Saint Kitts ja Nevis |
| `KP` | Põhja-Korea |
| `KR` | Lõuna-Korea |
| `KW` | Kuveit |
| `KY` | Kaimanisaared |
| `KZ` | Kasahstan |
| `LA` | Laos |
| `LB` | Liibanon |
| `LC` | Saint Lucia |
| `LI` | Liechtenstein |
| `LK` | Sri Lanka |
| `LR` | Libeeria |
| `LS` | Lesotho |
| `LT` | Leedu |
| `LU` | Luksemburg |
| `LV` | Läti |
| `LY` | Liibüa |
| `MA` | Maroko |
| `MC` | Monaco |
| `MD` | Moldova |
| `ME` | Montenegro |
| `MF` | Saint-Martin |
| `MG` | Madagaskar |
| `MH` | Marshalli Saared |
| `MK` | Makedoonia |
| `MK` | Makedoonia Vabariik |
| `ML` | Mali |
| `MM` | Myanmar (Birma) |
| `MN` | Mongoolia |
| `MO` | Macau erihalduspiirkond |
| `MO` | Macau |
| `MP` | Põhja-Mariaanid |
| `MQ` | Martinique |
| `MR` | Mauritaania |
| `MS` | Montserrat |
| `MT` | Malta |
| `MU` | Mauritius |
| `MV` | Maldiivid |
| `MW` | Malawi |
| `MX` | Mehhiko |
| `MY` | Malaisia |
| `MZ` | Mosambiik |
| `NA` | Namiibia |
| `NC` | Uus-Kaledoonia |
| `NE` | Niger |
| `NF` | Norfolk |
| `NG` | Nigeeria |
| `NI` | Nicaragua |
| `NL` | Holland |
| `NO` | Norra |
| `NP` | Nepal |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | Uus-Meremaa |
| `OM` | Omaan |
| `PA` | Panama |
| `PE` | Peruu |
| `PF` | Prantsuse Polüneesia |
| `PG` | Paapua Uus-Guinea |
| `PH` | Filipiinid |
| `PK` | Pakistan |
| `PL` | Poola |
| `PM` | Saint-Pierre ja Miquelon |
| `PN` | Pitcairni saared |
| `PR` | Puerto Rico |
| `PS` | Palestiina alad |
| `PS` | Palestiina |
| `PT` | Portugal |
| `PW` | Belau |
| `PY` | Paraguay |
| `QA` | Katar |
| `QO` | Okeaania hajasaared |
| `RE` | Réunion |
| `RO` | Rumeenia |
| `RS` | Serbia |
| `RU` | Venemaa |
| `RW` | Rwanda |
| `SA` | Saudi Araabia |
| `SB` | Saalomoni Saared |
| `SC` | Seišellid |
| `SD` | Sudaan |
| `SE` | Rootsi |
| `SG` | Singapur |
| `SH` | Saint Helena |
| `SI` | Sloveenia |
| `SJ` | Svalbard ja Jan Mayen |
| `SK` | Slovakkia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Senegal |
| `SO` | Somaalia |
| `SR` | Suriname |
| `SS` | Lõuna-Sudaan |
| `ST` | São Tomé ja Príncipe |
| `SV` | El Salvador |
| `SX` | Sint Maarten |
| `SY` | Süüria |
| `SZ` | Svaasimaa |
| `TA` | Tristan da Cunha |
| `TC` | Turks ja Caicos |
| `TD` | Tšaad |
| `TF` | Prantsuse Lõunaalad |
| `TG` | Togo |
| `TH` | Tai |
| `TJ` | Tadžikistan |
| `TK` | Tokelau |
| `TL` | Ida-Timor |
| `TL` | Timor-Leste |
| `TM` | Türkmenistan |
| `TN` | Tuneesia |
| `TO` | Tonga |
| `TR` | Türgi |
| `TT` | Trinidad ja Tobago |
| `TV` | Tuvalu |
| `TW` | Taiwan |
| `TZ` | Tansaania |
| `UA` | Ukraina |
| `UG` | Uganda |
| `UM` | Ühendriikide hajasaared |
| `UN` | Ühendatud Rahvaste Organisatsioon |
| `UN` | ÜRO |
| `US` | Ameerika Ühendriigid |
| `US` | USA |
| `UY` | Uruguay |
| `UZ` | Usbekistan |
| `VA` | Vatikan |
| `VC` | Saint Vincent ja Grenadiinid |
| `VE` | Venezuela |
| `VG` | Briti Neitsisaared |
| `VI` | USA Neitsisaared |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis ja Futuna |
| `WS` | Samoa |
| `XK` | Kosovo |
| `YE` | Jeemen |
| `YT` | Mayotte |
| `ZA` | Lõuna-Aafrika Vabariik |
| `ZM` | Sambia |
| `ZW` | Zimbabwe |
| `ZZ` | Tundmatu piirkond |
### Locale variant names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `1901` | saksa traditsiooniline kirjaviis |
| `1994` | normitud Resia kirjaviis |
| `1996` | saksa reformitud kirjaviis |
| `1606NICT` | hiliskeskprantsuse (kuni 1606) |
| `1694ACAD` | varajane moodne prantsuse |
| `1959ACAD` | akadeemiline |
| `ALALC97` | ALA-LC latinisatsioon (1997) |
| `AREVELA` | idaarmeenia |
| `AREVMDA` | läänearmeenia |
| `BAKU1926` | ühtlustatud türgi-ladina tähestik |
| `BISKE` | San Giorgio/Bila murre |
| `BOONT` | boontlingi |
| `EKAVSK` | štokavi e-line murrak |
| `FONIPA` | IPA foneetika |
| `FONUPA` | UPA foneetika |
| `HEPBURN` | Hepburni latinisatsioon |
| `IJEKAVSK` | štokavi ije-line murrak |
| `KKCOR` | üldlevinud kirjaviis |
| `KSCOR` | normitud kirjaviis |
| `LIPAW` | Resia Lipovaz’i murre |
| `MONOTON` | monotoonne |
| `NEDIS` | Natisone murre |
| `NJIVA` | Gniva/Njiva murre |
| `OSOJS` | Oseacco/Osojane murre |
| `PINYIN` | pinyin |
| `POLYTON` | polütooniline |
| `POSIX` | arvuti |
| `REVISED` | uus kirjaviis |
| `ROZAJ` | Resia murre |
| `SAAHO` | saho murre |
| `SCOTLAND` | šoti tavainglise |
| `SCOUSE` | scouse |
| `SOLBA` | Stolvizza/Solbica murre |
| `TARASK` | Taraskievica ortograafia |
| `UCCOR` | ühtlustatud ortograafia |
| `UCRCOR` | ühtlustatud redigeeritud ortograafia |
| `VALENCIA` | valentsia |
| `WADEGILE` | Wade’i-Gilesi latinisatsioon |
#### Keys (system names)
| key | Name |
| -------- | ---- |
| `calendar` | kalender |
| `cf` | rahavorming |
| `colAlternate` | sümbolite eiramine järjestuses |
| `colBackwards` | diakriitikute pöördjärjestus |
| `colCaseFirst` | suur- ja väiketähe järjestus |
| `colCaseLevel` | järjestuse tõstutundlikkus |
| `collation` | sortimisjärjestus |
| `colNormalization` | normaliseeritud järjestus |
| `colNumeric` | numbrite järjestus |
| `colStrength` | järjestuskaalud |
| `currency` | vääring |
| `hc` | 12 või 24 tunni süsteem |
| `lb` | reavahetuse laad |
| `ms` | mõõdustik |
| `numbers` | numbrid |
| `timezone` | ajavöönd |
| `va` | lokaadi variant |
| `x` | erakasutus |
### Types (of systems)
| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | budistlik kalender |
| `chinesecalendar` | Hiina kalender |
| `copticcalendar` | kopti kalender |
| `dangicalendar` | dangi kalender |
| `ethiopiccalendar` | Etioopia kalender |
| `ethiopic-amete-alemcalendar` | Etioopia amete alemi kalender |
| `gregoriancalendar` | Gregoriuse kalender |
| `hebrewcalendar` | juudi kalender |
| `indiancalendar` | India rahvuslik kalender |
| `islamiccalendar` | islamikalender |
| `islamic-civilcalendar` | islami ilmalik kalender |
| `islamic-rgsacalendar` | islamikalender (Saudi Araabia, vaatluspõhine) |
| `islamic-tblacalendar` | islamikalender (tabulaarne, astronoomiline ajastu) |
| `islamic-umalquracalendar` | islamikalender (Umm al-Qura) |
| `iso8601calendar` | ISO-8601 kalender |
| `japanesecalendar` | Jaapani kalender |
| `persiancalendar` | Pärsia kalender |
| `roccalendar` | Hiina Vabariigi kalender |
| `accountcf` | arvelduse rahavorming |
| `standardcf` | standardne rahavorming |
| `non-ignorablecolAlternate` | järjesta sümbolid |
| `shiftedcolAlternate` | eira järjestuses sümboleid |
| `nocolBackwards` | diakriitikud tavajärjestuses |
| `yescolBackwards` | diakriitikud pöördjärjestuses |
| `lowercolCaseFirst` | väiketäht järjestuses eespool |
| `nocolCaseFirst` | harilik järjestus |
| `uppercolCaseFirst` | suurtäht järjestuses eespool |
| `nocolCaseLevel` | tõstutundetu järjestus |
| `yescolCaseLevel` | tõstutundlik järjestus |
| `big5hancollation` | hiina traditsiooniline sortimisjärjestus (Big5) |
| `compatcollation` | varasem sortimisjärjestus (ühilduvuse jaoks) |
| `dictionarycollation` | sõnastiku sortimisjärjestus |
| `ducetcollation` | Unicode’i sortimise vaikejärjestus |
| `emojicollation` | emoji sortimisjärjestus |
| `eorcollation` | Euroopa järjestusreeglid |
| `gb2312hancollation` | hiina lihtsustatud sortimisjärjestus (GB2312) |
| `phonebookcollation` | telefoniraamatu sortimisjärjestus |
| `phoneticcollation` | foneetiline sortimisjärjestus |
| `pinyincollation` | pinyin’i sortimisjärjestus |
| `reformedcollation` | reformitud sortimisjärjestus |
| `searchcollation` | üldeesmärgiline otsing |
| `searchjlcollation` | otsing korea alguskonsonandi järgi |
| `standardcollation` | standardne sortimisjärjestus |
| `strokecollation` | kriipsude sortimisjärjestus |
| `traditionalcollation` | traditsiooniline sortimisjärjestus |
| `unihancollation` | võtmete-kriipsude sortimisjärjestus |
| `zhuyincollation` | zhuyin’i sortimisjärjestus |
| `nocolNormalization` | järjesta normaliseerimata |
| `yescolNormalization` | järjesta Unicode’i normaliseerimisega |
| `nocolNumeric` | järjesta numbrid eraldi |
| `yescolNumeric` | järjesta numbrid arvuliselt |
| `identicalcolStrength` | järjesta kõik |
| `primarycolStrength` | järjesta ainult alustähed |
| `quaternarycolStrength` | järjesta diakriitikud, algustähed, laius ja kana kiri |
| `secondarycolStrength` | järjesta diakriitikud |
| `tertiarycolStrength` | järjesta diakriitikud, algustähed ja laius |
| `fwidthd0` | täislaius |
| `hwidthd0` | poollaius |
| `npinyind0` | Numbriline |
| `h11hc` | 12-tunnine süsteem (0–11) |
| `h12hc` | 12-tunnine süsteem (1–12) |
| `h23hc` | 24-tunnine süsteem (0–23) |
| `h24hc` | 24-tunnine süsteem (1–24) |
| `looselb` | paindlik reavahetuse laad |
| `normallb` | harilik reavahetuse laad |
| `strictlb` | jäik reavahetuse laad |
| `bgnm0` | transkriptsioon (BGN) |
| `ungegnm0` | transkriptsioon (UNGEGN) |
| `metricms` | meetermõõdustik |
| `uksystemms` | inglise mõõdustik |
| `ussystemms` | USA mõõdustik |
| `ahomnumbers` | ahomi numbrid |
| `arabnumbers` | idaaraabia numbrid |
| `arabextnumbers` | laiendatud idaaraabia numbrid |
| `armnnumbers` | armeenia numbrid |
| `armnlownumbers` | väiketähelised armeenia numbrid |
| `balinumbers` | bali numbrid |
| `bengnumbers` | bengali numbrid |
| `brahnumbers` | braahmi numbrid |
| `cakmnumbers` | tšaakma numbrid |
| `chamnumbers` | tšaami numbrid |
| `cyrlnumbers` | kirillitsa numbrid |
| `devanumbers` | devanaagari numbrid |
| `ethinumbers` | etioopia numbrid |
| `financenumbers` | finantsnumbrid |
| `fullwidenumbers` | täislaiusega numbrid |
| `geornumbers` | gruusia numbrid |
| `gonmnumbers` | masaram gondi numbrid |
| `greknumbers` | kreeka numbrid |
| `greklownumbers` | väiketähelised kreeka numbrid |
| `gujrnumbers` | gudžarati numbrid |
| `gurunumbers` | gurmukhi numbrid |
| `hanidecnumbers` | hiina kümnendnumbrid |
| `hansnumbers` | lihtsustatud hiina keele numbrid |
| `hansfinnumbers` | lihtsustatud hiina keele finantsnumbrid |
| `hantnumbers` | traditsioonilise hiina keele numbrid |
| `hantfinnumbers` | traditsioonilise hiina keele finantsnumbrid |
| `hebrnumbers` | heebrea numbrid |
| `hmngnumbers` | phahau-hmongi numbrid |
| `javanumbers` | jaava numbrid |
| `jpannumbers` | jaapani numbrid |
| `jpanfinnumbers` | jaapani finantsnumbrid |
| `kalinumbers` | kaja-lii numbrid |
| `khmrnumbers` | khmeeri numbrid |
| `kndanumbers` | kannada numbrid |
| `lananumbers` | tai tham hora numbrid |
| `lanathamnumbers` | tai tham tham numbrid |
| `laoonumbers` | lao numbrid |
| `latnnumbers` | araabia numbrid |
| `lepcnumbers` | leptša numbrid |
| `limbnumbers` | limbu numbrid |
| `mlymnumbers` | malajalami numbrid |
| `modinumbers` | modi numbrid |
| `mongnumbers` | mongoli numbrid |
| `mroonumbers` | mruu numbrid |
| `mteinumbers` | meitei numbrid |
| `mymrnumbers` | birma numbrid |
| `mymrshannumbers` | myanmari shan numbrid |
| `mymrtlngnumbers` | myanmari tai laing numbrid |
| `nativenumbers` | kohalikud numbrid |
| `nkoonumbers` | nkoo numbrid |
| `olcknumbers` | santali numbrid |
| `oryanumbers` | oria numbrid |
| `osmanumbers` | osmani numbrid |
| `romannumbers` | Rooma numbrid |
| `romanlownumbers` | väiketähelised Rooma numbrid |
| `saurnumbers` | sauraštra numbrid |
| `shrdnumbers` | šaarada numbrid |
| `sindnumbers` | hudavadi numbrid |
| `sinhnumbers` | sinhala lithi numbrid |
| `soranumbers` | sora numbrid |
| `sundnumbers` | sunda numbrid |
| `takrnumbers` | taakri numbrid |
| `talunumbers` | uue tai-lõõ numbrid |
| `tamlnumbers` | traditsioonilised tamili numbrid |
| `tamldecnumbers` | tamili numbrid |
| `telunumbers` | telugu numbrid |
| `thainumbers` | tai numbrid |
| `tibtnumbers` | tiibeti numbrid |
| `tirhnumbers` | tirhuta numbrid |
| `traditionalnumbers` | traditsioonilised numbrid |
| `vaiinumbers` | vai numbrid |
| `waranumbers` | hoo numbrid |
| `metric` | meetermõõdustik |
| `UK` | inglise mõõdustik |
| `US` | USA mõõdustik |
### Code patterns
Keel: {0}Kiri: {0}Piirkond: {0}
### Character processing for computer systems
| main characters | `[a b c d e f g h i j k l m n o p q r s š z ž t u v w õ ä ö ü x y]` |
| auxiliary characters | `[á à â å ā æ ç é è ê ë ē í ì î ï ī ñ ó ò ŏ ô ø ō œ ú ù û ū]` |
| index characters | `[A B C D E F G H I J K L M N O P Q R S Š Z Ž T U V Õ Ä Ö Ü X Y]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- , ; \: ! ? . “ „ ( ) \[ \] \{ \} @]` |
final ellipsis: `{0}…`
initial ellipsis: `…{0}`
medial ellipsis: `{0} … {1}`
word-final ellipsis: `{0} …`
word-initial ellipsis: `… {0}`
word-medial ellipsis: `{0} … {1}`
More information characters: `?`
Delimiters:
Quotation start character: „
Quotation end character: “
Secondary yquotation start character: ‚
Secondary quotation end character: ‘
## Calendar data
#### buddhist calendar
| ID-stuff | values |
| -------- | ------ |
| era | BK |
| era | BK |
| era | BK |
#### chinese calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | esimene kuu |
| month 2 | teine kuu |
| month 3 | kolmas kuu |
| month 4 | neljas kuu |
| month 5 | viies kuu |
| month 6 | kuues kuu |
| month 7 | seitsmes kuu |
| month 8 | kaheksas kuu |
| month 9 | üheksas kuu |
| month 10 | kümnes kuu |
| month 11 | üheteistkümnes kuu |
| month 12 | kaheteistkümnes kuu |
rotthärgtiigerküülikdraakonmaduhobunelammasahvkukkkoersigarotthärgtiigerküülikdraakonmaduhobunelammasahvkukkkoersiga
#### generic calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, d. MMMM y G` |
| date format | `d. MMMM y G` |
| date format | `dd.MM.y G` |
| date format | `dd.MM.y GGGGG` |
| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1}, 'kell' {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E, d. MMMM y G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm.ss a` |
| date format `Hms` | `H:mm.ss` |
| date format `M` | `M` |
| date format `Md` | `d.M` |
| date format `MEd` | `E, d.M` |
| date format `MMM` | `MMMM` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `E, d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMEd` | `E, d. MMMM` |
| date format `mmss` | `mm.ss` |
| date format `ms` | `mm.ss` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `M.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E, d.M y G` |
| date format `yyyyMMM` | `MMM y G` |
| date format `yyyyMMMd` | `d. MMM y G` |
| date format `yyyyMMMEd` | `E, d. MMMM y G` |
| date format `yyyyMMMM` | `MMMM y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0}–{1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `HH–HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `HH:mm–HH:mmHH:mm–HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `HH:mm–HH:mm vHH:mm–HH:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `HH–HH v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM–dd.MMdd.MM–dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `d.–d. MMMd. MMM – d. MMM` |
| interval format `MMMEd` | `E, d. MMM – E, d. MMME, d. MMM – E, d. MMM` |
| interval format `y` | `y–y G` |
| interval format `yM` | `MM.y–MM.y GMM.y–MM.y G` |
| interval format `yMd` | `dd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y Gdd.MM.y–dd.MM.y G` |
| interval format `yMEd` | `E, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y GE, dd.MM.y – E, dd.MM.y G` |
| interval format `yMMM` | `MMM–MMM y GMMM y – MMM y G` |
| interval format `yMMMd` | `d.–d. MMM y Gd. MMM – d. MMM y Gd. MMM y – d. MMM y G` |
| interval format `yMMMEd` | `E, d. MMM – E, d. MMM y GE, d. MMM – E, d. MMM y GE, d. MMM y – E, d. MMM y G` |
| interval format `yMMMM` | `MMMM–MMMM y GMMMM y – MMMM y G` |
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | jaan |
| month 2 | veebr |
| month 3 | märts |
| month 4 | apr |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | aug |
| month 9 | sept |
| month 10 | okt |
| month 11 | nov |
| month 12 | dets |
| month 1 | J |
| month 2 | V |
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
| month 1 | jaanuar |
| month 2 | veebruar |
| month 3 | märts |
| month 4 | aprill |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | august |
| month 9 | september |
| month 10 | oktoober |
| month 11 | november |
| month 12 | detsember |
| month 1 | jaan |
| month 2 | veebr |
| month 3 | märts |
| month 4 | apr |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | aug |
| month 9 | sept |
| month 10 | okt |
| month 11 | nov |
| month 12 | dets |
| month 1 | J |
| month 2 | V |
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
| month 1 | jaanuar |
| month 2 | veebruar |
| month 3 | märts |
| month 4 | aprill |
| month 5 | mai |
| month 6 | juuni |
| month 7 | juuli |
| month 8 | august |
| month 9 | september |
| month 10 | oktoober |
| month 11 | november |
| month 12 | detsember |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | pühapäev |
| (week)day mon | esmaspäev |
| (week)day tue | teisipäev |
| (week)day wed | kolmapäev |
| (week)day thu | neljapäev |
| (week)day fri | reede |
| (week)day sat | laupäev |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | P |
| (week)day mon | E |
| (week)day tue | T |
| (week)day wed | K |
| (week)day thu | N |
| (week)day fri | R |
| (week)day sat | L |
| (week)day sun | pühapäev |
| (week)day mon | esmaspäev |
| (week)day tue | teisipäev |
| (week)day wed | kolmapäev |
| (week)day thu | neljapäev |
| (week)day fri | reede |
| (week)day sat | laupäev |
| quarter 1 | K1 |
| quarter 2 | K2 |
| quarter 3 | K3 |
| quarter 4 | K4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. kvartal |
| quarter 2 | 2. kvartal |
| quarter 3 | 3. kvartal |
| quarter 4 | 4. kvartal |
| quarter 1 | K1 |
| quarter 2 | K2 |
| quarter 3 | K3 |
| quarter 4 | K4 |
| quarter 1 | 1. |
| quarter 2 | 2. |
| quarter 3 | 3. |
| quarter 4 | 4. |
| quarter 1 | 1. kvartal |
| quarter 2 | 2. kvartal |
| quarter 3 | 3. kvartal |
| quarter 4 | 4. kvartal |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | keskööl |
| period of day am | AM |
| period of day noon | keskpäeval |
| period of day pm | PM |
| period of day morning1 | hommikul |
| period of day afternoon1 | pärastlõunal |
| period of day evening1 | õhtul |
| period of day night1 | öösel |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| period of day midnight | kesköö |
| period of day am | AM |
| period of day noon | keskpäev |
| period of day pm | PM |
| period of day morning1 | hommik |
| period of day afternoon1 | pärastlõuna |
| period of day evening1 | õhtu |
| period of day night1 | öö |
| era | enne Kristust |
| era | enne meie ajaarvamist |
| era | pärast Kristust |
| era | meie ajaarvamise järgi |
| era | eKr |
| era | e.m.a |
| era | pKr |
| era | m.a.j |
| era | eKr |
| era | e.m.a |
| era | pKr |
| era | m.a.j |
| date format | `EEEE, d. MMMM y` |
| date format | `d. MMMM y` |
| date format | `d. MMM y` |
| date format | `dd.MM.yy` |
| time format | `HH:mm:ss zzzz` |
| time format | `HH:mm:ss z` |
| time format | `HH:mm:ss` |
| time format | `HH:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm B` |
| date format `EBhms` | `E h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `MMM y G` |
| date format `GyMMMd` | `d. MMM y G` |
| date format `GyMMMEd` | `E, d. MMMM y G` |
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
| date format `M` | `M` |
| date format `Md` | `d.M` |
| date format `MEd` | `E, d.M` |
| date format `MMM` | `MMMM` |
| date format `MMMd` | `d. MMM` |
| date format `MMMEd` | `E, d. MMM` |
| date format `MMMMd` | `d. MMMM` |
| date format `MMMMEd` | `E, d. MMMM` |
| date format `MMMMW` | `MMM (W. 'nädal')` |
| date format `MMMMW` | `MMM (W. 'nädal')` |
| date format `mmss` | `mm:ss` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `M.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E, d.M.y` |
| date format `yMMM` | `MMM y` |
| date format `yMMMd` | `d. MMM y` |
| date format `yMMMEd` | `E, d. MMMM y` |
| date format `yMMMM` | `MMMM y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `w. 'nädal' (Y)` |
| date format `yw` | `w. 'nädal' (Y)` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `HH–HH` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `HH:mm–HH:mmHH:mm–HH:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `HH:mm–HH:mm vHH:mm–HH:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `HH–HH v` |
| interval format `M` | `MM–MM` |
| interval format `Md` | `dd.MM–dd.MMdd.MM–dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `d.–d. MMMd. MMM – d. MMM` |
| interval format `MMMEd` | `E, d. MMM – E, d. MMME, d. MMM – E, d. MMM` |
| interval format `y` | `y–y` |
| interval format `yM` | `MM.y–MM.yMM.y–MM.y` |
| interval format `yMd` | `dd.MM.y–dd.MM.ydd.MM.y–dd.MM.ydd.MM.y–dd.MM.y` |
| interval format `yMEd` | `E, dd.MM.y – E, dd.MM.yE, dd.MM.y – E, dd.MM.yE, dd.MM.y – E, dd.MM.y` |
| interval format `yMMM` | `MMM–MMM yMMM y – MMM y` |
| interval format `yMMMd` | `d.–d. MMM yd. MMM – d. MMM yd. MMM y – d. MMM y` |
| interval format `yMMMEd` | `E, d. MMM – E, d. MMM yE, d. MMM – E, d. MMM yE, d. MMM y – E, d. MMM y` |
| interval format `yMMMM` | `MMMM–MMMM yMMMM y – MMMM y` |
#### hebrew calendar
| ID-stuff | values |
| -------- | ------ |
| era | AM |
| era | AM |
| era | AM |
#### islamic calendar
| ID-stuff | values |
| -------- | ------ |
| era | AH |
| era | AH |
| era | AH |
### some more time stuff
|  | ajastu |
|  | ajastu |
|  | ajastu |
|  | aasta |
eelmine aastakäesolev aastajärgmine aasta{0} aasta pärast{0} aasta pärast{0} aasta eest{0} aasta eest
|  | a |
{0} a pärast{0} a pärast{0} a eest{0} a eest
|  | a |
{0} a pärast{0} a pärast{0} a eest{0} a eest
|  | kvartal |
eelmine kvartalkäesolev kvartaljärgmine kvartal{0} kvartali pärast{0} kvartali pärast{0} kvartali eest{0} kvartali eest
|  | kv |
eelmine kvkäesolev kvjärgmine kv{0} kv pärast{0} kv pärast{0} kv eest{0} kv eest
|  | kv |
eelmine kvkäesolev kvjärgmine kv{0} kv pärast{0} kv pärast{0} kv eest{0} kv eest
|  | kuu |
eelmine kuukäesolev kuujärgmine kuu{0} kuu pärast{0} kuu pärast{0} kuu eest{0} kuu eest
|  | k |
{0} kuu pärast{0} kuu pärast{0} kuu eest{0} kuu eest
|  | k |
{0} k pärast{0} k pärast{0} k eest{0} k eest
|  | nädal |
eelmine nädalkäesolev nädaljärgmine nädal{0} nädala pärast{0} nädala pärast{0} nädala eest{0} nädala eest{0} nädal
|  | näd |
{0} näd pärast{0} näd pärast{0} näd eest{0} näd eest{0} näd
|  | näd |
{0} näd pärast{0} näd pärast{0} näd eest{0} näd eest{0} nädal
|  | kuu nädal |
|  | kuu näd |
|  | kuu näd |
|  | päev |
üleeileeiletänahommeülehomme{0} päeva pärast{0} päeva pärast{0} päeva eest{0} päeva eest
|  | p |
{0} p pärast{0} p pärast{0} p eest{0} p eest
|  | p |
{0} p pärast{0} p pärast{0} p eest{0} p eest
|  | aasta päev |
|  | aasta p |
|  | aasta p |
|  | nädalapäev |
|  | nädalap. |
|  | nädalap. |
|  | kuu nädalapäev |
|  | kuu nädalap. |
|  | kuu nädalap. |
eelmine pühapäevkäesolev pühapäevjärgmine pühapäev{0} pühapäeva pärast{0} pühapäeva pärast{0} pühapäeva eest{0} pühapäeva eesteelmine pühapkäesolev pühapjärgmine pühap{0} pühap pärast{0} pühap pärast{0} pühap eest{0} pühap pärasteelmine Pkäesolev Pjärgmine P{0} P pärast{0} P pärast{0} P eest{0} P eesteelmine esmaspäevkäesolev esmaspäevjärgmine esmaspäev{0} esmaspäeva pärast{0} esmaspäeva pärast{0} esmaspäeva eest{0} esmaspäeva eesteelmine esmaspkäesolev esmaspjärgmine esmasp{0} esmasp pärast{0} esmasp pärast{0} esmasp eest{0} esmasp eesteelmine Ekäesolev Ejärgmine E{0} E pärast{0} E pärast{0} E eest{0} E eesteelmine teisipäevkäesolev teisipäevjärgmine teisipäev{0} teisipäeva pärast{0} teisipäeva pärast{0} teisipäeva eest{0} teisipäeva eesteelmine teisipkäesolev teisipjärgmine teisip{0} teisip pärast{0} teisip pärast{0} teisip eest{0} teisip eesteelmine Tkäesolev Tjärgmine T{0} T pärast{0} T pärast{0} T eest{0} T eesteelmine kolmapäevkäesolev kolmapäevjärgmine kolmapäev{0} kolmapäeva pärast{0} kolmapäeva pärast{0} kolmapäeva eest{0} kolmapäeva eesteelmine kolmapkäesolev kolmapjärgmine kolmap{0} kolmap pärast{0} kolmap pärast{0} kolmap eest{0} kolmap eesteelmine Kkäesolev Kjärgmine K{0} K pärast{0} K pärast{0} K eest{0} K eesteelmine neljapäevkäesolev neljapäevjärgmine neljapäev{0} neljapäeva pärast{0} neljapäeva pärast{0} neljapäeva eest{0} neljapäeva eesteelmine neljapkäesolev neljapjärgmine neljap{0} neljap pärast{0} neljap pärast{0} neljap eest{0} neljap eesteelmine Nkäesolev Njärgmine N{0} N pärast{0} N pärast{0} N eest{0} N eesteelmine reedekäesolev reedejärgmine reede{0} reede pärast{0} reede pärast{0} reede eest{0} reede eesteelmine reedekäesolev reedejärgmine reede{0} reede pärast{0} reede pärast{0} reede eest{0} reede eesteelmine Rkäesolev Rjärgmine R{0} R pärast{0} R pärast{0} R eest{0} R eesteelmine laupäevkäesolev laupäevjärgmine laupäev{0} laupäeva pärast{0} laupäeva pärast{0} laupäeva eest{0} laupäeva eesteelmine laupkäesolev laupjärgmine laup{0} laup pärast{0} laup pärast{0} laup eest{0} laup eesteelmine Lkäesolev Ljärgmine L{0} L pärast{0} L pärast{0} L eest{0} L eest
|  | enne/pärast lõunat |
|  | enne/pärast lõunat |
|  | enne/pärast lõunat |
|  | tund |
praegusel tunnil{0} tunni pärast{0} tunni pärast{0} tunni eest{0} tunni eest
|  | t |
{0} t pärast{0} t pärast{0} t eest{0} t eest
|  | t |
{0} t pärast{0} t pärast{0} t eest{0} t eest
|  | minut |
praegusel minutil{0} minuti pärast{0} minuti pärast{0} minuti eest{0} minuti eest
|  | min |
{0} min pärast{0} min pärast{0} min eest{0} min eest
|  | min |
{0} min pärast{0} min pärast{0} min eest{0} min eest
|  | sekund |
nüüd{0} sekundi pärast{0} sekundi pärast{0} sekundi eest{0} sekundi eest
|  | sek |
{0} sek pärast{0} sek pärast{0} sek eest{0} sek eest
|  | s |
{0} s pärast{0} s pärast{0} s eest{0} s eest
|  | ajavöönd |
|  | vöönd |
|  | vöönd |
#### time zones
| Format name | Format |
| Hours from UTC | +HH:mm;−HH:mm |
| GMT | GMT {0} |
| Time at Greenwich | GMT |
| regional | ({0}) |
| regional | {0} (+1) |
| regional | {0} (+0) |
| fallback | {1} ({0}) |
| Zone | Name |
| ---- | ---- |
| America/Santa_Isabel | Santa Isabel |
| Pacific/Honolulu | Honolulu |
| Etc/UTC | Koordineeritud maailmaaeg |
| Etc/Unknown | määramata linn |
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
| America/Argentina/Rio_Gallegos | Río Gallegos |
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
| Europe/Vienna | Viin |
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
| Antarctica/Macquarie | Macquarie |
| Australia/Lord_Howe | Lord Howe |
| America/Aruba | Aruba |
| Europe/Mariehamn | Maarianhamina |
| Asia/Baku | Bakuu |
| Europe/Sarajevo | Sarajevo |
| America/Barbados | Barbados |
| Asia/Dhaka | Dhaka |
| Europe/Brussels | Brüssel |
| Africa/Ouagadougou | Ouagadougou |
| Europe/Sofia | Sofia |
| Asia/Bahrain | Bahrein |
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
| America/Belem | Belém |
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
| America/St_Johns | Saint John’s |
| Indian/Cocos | Kookossaared |
| Africa/Kinshasa | Kinshasa |
| Africa/Lubumbashi | Lubumbashi |
| Africa/Bangui | Bangui |
| Africa/Brazzaville | Brazzaville |
| Europe/Zurich | Zürich |
| Africa/Abidjan | Abidjan |
| Pacific/Rarotonga | Rarotonga |
| Pacific/Easter | Lihavõttesaar |
| America/Punta_Arenas | Punta Arenas |
| America/Santiago | Santiago |
| Africa/Douala | Douala |
| Asia/Urumqi | Ürümqi |
| Asia/Shanghai | Shanghai |
| America/Bogota | Bogotá |
| America/Costa_Rica | Costa Rica |
| America/Havana | Havanna |
| Atlantic/Cape_Verde | Roheneemesaared |
| America/Curacao | Curaçao |
| Indian/Christmas | Jõulusaar |
| Asia/Nicosia | Nikosia |
| Asia/Famagusta | Famagusta |
| Europe/Prague | Praha |
| Europe/Busingen | Büsingen |
| Europe/Berlin | Berliin |
| Africa/Djibouti | Djibouti |
| Europe/Copenhagen | Kopenhaagen |
| America/Dominica | Dominica |
| America/Santo_Domingo | Santo Domingo |
| Africa/Algiers | Alžiir |
| Pacific/Galapagos | Galápagos |
| America/Guayaquil | Guayaquil |
| Europe/Tallinn | Tallinn |
| Africa/Cairo | Kairo |
| Africa/El_Aaiun | El Aaiun |
| Africa/Asmera | Asmara |
| Atlantic/Canary | Kanaari saared |
| Africa/Ceuta | Ceuta |
| Europe/Madrid | Madrid |
| Africa/Addis_Ababa | Addis Abeba |
| Europe/Helsinki | Helsingi |
| Pacific/Fiji | Fidži |
| Atlantic/Stanley | Stanley |
| Pacific/Truk | Chuuk |
| Pacific/Ponape | Pohnpei |
| Pacific/Kosrae | Kosrae |
| Atlantic/Faeroe | Fääri saared |
| Europe/Paris | Pariis |
| Africa/Libreville | Libreville |
| Europe/London | Briti suveaegLondon |
| America/Grenada | Grenada |
| Asia/Tbilisi | Thbilisi |
| America/Cayenne | Cayenne |
| Europe/Guernsey | Guernsey |
| Africa/Accra | Accra |
| Europe/Gibraltar | Gibraltar |
| America/Thule | Thule |
| America/Godthab | Nuuk |
| America/Scoresbysund | Ittoqqortoormiit |
| America/Danmarkshavn | Danmarkshavn |
| Africa/Banjul | Banjul |
| Africa/Conakry | Conakry |
| America/Guadeloupe | Guadeloupe |
| Africa/Malabo | Malabo |
| Europe/Athens | Ateena |
| Atlantic/South_Georgia | Lõuna-Georgia |
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
| Europe/Dublin | Iiri suveaegDublin |
| Asia/Jerusalem | Jeruusalemm |
| Europe/Isle_of_Man | Mani saar |
| Asia/Calcutta | Kolkata |
| Indian/Chagos | Chagos |
| Asia/Baghdad | Bagdad |
| Asia/Tehran | Teheran |
| Atlantic/Reykjavik | Reykjavík |
| Europe/Rome | Rooma |
| Europe/Jersey | Jersey |
| America/Jamaica | Jamaica |
| Asia/Amman | Amman |
| Asia/Tokyo | Tōkyō |
| Africa/Nairobi | Nairobi |
| Asia/Bishkek | Biškek |
| Asia/Phnom_Penh | Phnom Penh |
| Pacific/Enderbury | Enderbury |
| Pacific/Kiritimati | Kiritimati |
| Pacific/Tarawa | Tarawa |
| Indian/Comoro | Comoro |
| America/St_Kitts | Saint Kitts |
| Asia/Pyongyang | Pyongyang |
| Asia/Seoul | Soul |
| Asia/Kuwait | Kuveit |
| America/Cayman | Cayman |
| Asia/Aqtau | Aktau |
| Asia/Oral | Oral |
| Asia/Atyrau | Atõrau |
| Asia/Aqtobe | Aktöbe |
| Asia/Qyzylorda | Kõzõlorda |
| Asia/Almaty | Almatõ |
| Asia/Vientiane | Vientiane |
| Asia/Beirut | Beirut |
| America/St_Lucia | Saint Lucia |
| Europe/Vaduz | Vaduz |
| Asia/Colombo | Colombo |
| Africa/Monrovia | Monrovia |
| Africa/Maseru | Maseru |
| Europe/Vilnius | Vilnius |
| Europe/Luxembourg | Luxembourg |
| Europe/Riga | Riia |
| Africa/Tripoli | Tripoli |
| Africa/Casablanca | Casablanca |
| Europe/Monaco | Monaco |
| Europe/Chisinau | Chișinău |
| Europe/Podgorica | Podgorica |
| America/Marigot | Marigot |
| Indian/Antananarivo | Antananarivo |
| Pacific/Kwajalein | Kwajalein |
| Pacific/Majuro | Majuro |
| Europe/Skopje | Skopje |
| Africa/Bamako | Bamako |
| Asia/Rangoon | Yangon |
| Asia/Hovd | Hovd |
| Asia/Ulaanbaatar | Ulaanbaatar |
| Asia/Choibalsan | Tšojbalsan |
| Asia/Macau | Macau |
| Pacific/Saipan | Saipan |
| America/Martinique | Martinique |
| Africa/Nouakchott | Nouakchott |
| America/Montserrat | Montserrat |
| Europe/Malta | Malta |
| Indian/Mauritius | Mauritius |
| Indian/Maldives | Maldiivid |
| Africa/Blantyre | Blantyre |
| America/Tijuana | Tijuana |
| America/Hermosillo | Hermosillo |
| America/Mazatlan | Mazatlán |
| America/Chihuahua | Chihuahua |
| America/Bahia_Banderas | Bahia Banderas |
| America/Ojinaga | Ojinaga |
| America/Monterrey | Monterrey |
| America/Mexico_City | México |
| America/Matamoros | Matamoros |
| America/Merida | Mérida |
| America/Cancun | Cancún |
| Asia/Kuala_Lumpur | Kuala Lumpur |
| Asia/Kuching | Kuching |
| Africa/Maputo | Maputo |
| Africa/Windhoek | Windhoek |
| Pacific/Noumea | Noumea |
| Africa/Niamey | Niamey |
| Pacific/Norfolk | Norfolk |
| Africa/Lagos | Lagos |
| America/Managua | Managua |
| Europe/Amsterdam | Amsterdam |
| Europe/Oslo | Oslo |
| Asia/Katmandu | Katmandu |
| Pacific/Nauru | Nauru |
| Pacific/Niue | Niue |
| Pacific/Chatham | Chatham |
| Pacific/Auckland | Auckland |
| Asia/Muscat | Masqaţ |
| America/Panama | Panama |
| America/Lima | Lima |
| Pacific/Tahiti | Tahiti |
| Pacific/Marquesas | Markiisaared |
| Pacific/Gambier | Gambier |
| Pacific/Port_Moresby | Port Moresby |
| Pacific/Bougainville | Bougainville |
| Asia/Manila | Manila |
| Asia/Karachi | Karachi |
| Europe/Warsaw | Varssavi |
| America/Miquelon | Miquelon |
| Pacific/Pitcairn | Pitcairn |
| America/Puerto_Rico | Puerto Rico |
| Asia/Gaza | Gaza |
| Asia/Hebron | Hebron |
| Atlantic/Azores | Assoorid |
| Atlantic/Madeira | Madeira |
| Europe/Lisbon | Lissabon |
| Pacific/Palau | Belau |
| America/Asuncion | Asunción |
| Asia/Qatar | Katar |
| Indian/Reunion | Réunion |
| Europe/Bucharest | Bukarest |
| Europe/Belgrade | Belgrad |
| Europe/Kaliningrad | Kaliningrad |
| Europe/Simferopol | Simferopol |
| Europe/Moscow | Moskva |
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
| Asia/Khandyga | Handõga |
| Asia/Sakhalin | Sahhalin |
| Asia/Ust-Nera | Ust-Nera |
| Asia/Magadan | Magadan |
| Asia/Srednekolymsk | Srednekolõmsk |
| Asia/Kamchatka | Kamtšatka |
| Asia/Anadyr | Anadõr |
| Africa/Kigali | Kigali |
| Asia/Riyadh | Ar-Riyāḑ |
| Pacific/Guadalcanal | Guadalcanal |
| Indian/Mahe | Mahe |
| Africa/Khartoum | Hartum |
| Europe/Stockholm | Stockholm |
| Asia/Singapore | Singapur |
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
| Asia/Damascus | Damaskus |
| Africa/Mbabane | Mbabane |
| America/Grand_Turk | Grand Turk |
| Africa/Ndjamena | N’Djamena |
| Indian/Kerguelen | Kerguelen |
| Africa/Lome | Lome |
| Asia/Bangkok | Bangkok |
| Asia/Dushanbe | Dušanbe |
| Pacific/Fakaofo | Fakaofo |
| Asia/Dili | Dili |
| Asia/Ashgabat | Aşgabat |
| Africa/Tunis | Tunis |
| Pacific/Tongatapu | Tongatapu |
| Europe/Istanbul | İstanbul |
| America/Port_of_Spain | Port of Spain |
| Pacific/Funafuti | Funafuti |
| Asia/Taipei | Taipei |
| Africa/Dar_es_Salaam | Dar es Salaam |
| Europe/Uzhgorod | Užgorod |
| Europe/Kiev | Kiiev |
| Europe/Zaporozhye | Zaporožje |
| Africa/Kampala | Kampala |
| Pacific/Midway | Midway |
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
| America/North_Dakota/Beulah | Beulah, Põhja-Dakota |
| America/North_Dakota/New_Salem | New Salem, Põhja-Dakota |
| America/North_Dakota/Center | Center, Põhja-Dakota |
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
| Europe/Vatican | Vatikan |
| America/St_Vincent | Saint Vincent |
| America/Caracas | Caracas |
| America/Tortola | Tortola |
| America/St_Thomas | Saint Thomas |
| Asia/Saigon | Ho Chi Minh |
| Pacific/Efate | Efate |
| Pacific/Wallis | Wallis |
| Pacific/Apia | Apia |
| Asia/Aden | Aden |
| Indian/Mayotte | Mayotte |
| Africa/Johannesburg | Johannesburg |
| Africa/Lusaka | Lusaka |
| Africa/Harare | Harare |
| Acre | Acre aegAcre standardaegAcre suveaeg |
| Afghanistan | Afganistani aeg |
| Africa_Central | Kesk-Aafrika aeg |
| Africa_Eastern | Ida-Aafrika aeg |
| Africa_Southern | Lõuna-Aafrika standardaeg |
| Africa_Western | Lääne-Aafrika aegLääne-Aafrika standardaegLääne-Aafrika suveaeg |
| Alaska | Alaska aegAlaska standardaegAlaska suveaeg |
| Almaty | Almatõ aegAlmatõ standardaegAlmatõ suveaeg |
| Amazon | Amazonase aegAmazonase standardaegAmazonase suveaeg |
| America_Central | Kesk-Ameerika aegKesk-Ameerika standardaegKesk-Ameerika suveaeg |
| America_Eastern | Idaranniku aegIdaranniku standardaegIdaranniku suveaeg |
| America_Mountain | Mäestikuvööndi aegMäestikuvööndi standardaegMäestikuvööndi suveaeg |
| America_Pacific | Vaikse ookeani aegVaikse ookeani standardaegVaikse ookeani suveaeg |
| Anadyr | Anadõri aegAnadõri standardaegAnadõri suveaeg |
| Apia | Apia aegApia standardaegApia suveaeg |
| Aqtau | Aktau aegAktau standardaegAktau suveaeg |
| Aqtobe | Aktöbe aegAktöbe standardaegAktöbe suveaeg |
| Arabian | Araabia aegAraabia standardaegAraabia suveaeg |
| Argentina | Argentina aegArgentina standardaegArgentina suveaeg |
| Argentina_Western | Lääne-Argentina aegLääne-Argentina standardaegLääne-Argentina suveaeg |
| Armenia | Armeenia aegArmeenia standardaegArmeenia suveaeg |
| Atlantic | Atlandi aegAtlandi standardaegAtlandi suveaeg |
| Australia_Central | Kesk-Austraalia aegKesk-Austraalia standardaegKesk-Austraalia suveaeg |
| Australia_CentralWestern | Austraalia Kesk-Lääne aegAustraalia Kesk-Lääne standardaegAustraalia Kesk-Lääne suveaeg |
| Australia_Eastern | Ida-Austraalia aegIda-Austraalia standardaegIda-Austraalia suveaeg |
| Australia_Western | Lääne-Austraalia aegLääne-Austraalia standardaegLääne-Austraalia suveaeg |
| Azerbaijan | Aserbaidžaani aegAserbaidžaani standardaegAserbaidžaani suveaeg |
| Azores | Assooride aegAssooride standardaegAssooride suveaeg |
| Bangladesh | Bangladeshi aegBangladeshi standardaegBangladeshi suveaeg |
| Bhutan | Bhutani aeg |
| Bolivia | Boliivia aeg |
| Brasilia | Brasiilia aegBrasiilia standardaegBrasiilia suveaeg |
| Brunei | Brunei aeg |
| Cape_Verde | Roheneemesaarte aegRoheneemesaarte standardaegRoheneemesaarte suveaeg |
| Casey | Casey aeg |
| Chamorro | Tšamorro standardaeg |
| Chatham | Chathami aegChathami standardaegChathami suveaeg |
| Chile | Tšiili aegTšiili standardaegTšiili suveaeg |
| China | Hiina aegHiina standardaegHiina suveaeg |
| Choibalsan | Tšojbalsani aegTšojbalsani standardaegTšojbalsani suveaeg |
| Christmas | Jõulusaare aeg |
| Cocos | Kookossaarte aeg |
| Colombia | Colombia aegColombia standardaegColombia suveaeg |
| Cook | Cooki saarte aegCooki saarte standardaegCooki saarte osaline suveaeg |
| Cuba | Kuuba aegKuuba standardaegKuuba suveaeg |
| Davis | Davise aeg |
| DumontDUrville | Dumont-d’Urville’i aeg |
| East_Timor | Ida-Timori aeg |
| Easter | Lihavõttesaare aegLihavõttesaare standardaegLihavõttesaare suveaeg |
| Ecuador | Ecuadori aeg |
| Europe_Central | Kesk-Euroopa aegKesk-Euroopa standardaegKesk-Euroopa suveaeg |
| Europe_Eastern | Ida-Euroopa aegIda-Euroopa standardaegIda-Euroopa suveaeg |
| Europe_Further_Eastern | Kaliningradi ja Valgevene aeg |
| Europe_Western | Lääne-Euroopa aegLääne-Euroopa standardaegLääne-Euroopa suveaeg |
| Falkland | Falklandi saarte aegFalklandi saarte standardaegFalklandi saarte suveaeg |
| Fiji | Fidži aegFidži standardaegFidži suveaeg |
| French_Guiana | Prantsuse Guajaana aeg |
| French_Southern | Prantsuse Antarktiliste ja Lõunaalade aeg |
| Galapagos | Galapagose aeg |
| Gambier | Gambier’ aeg |
| Georgia | Gruusia aegGruusia standardaegGruusia suveaeg |
| Gilbert_Islands | Gilberti saarte aeg |
| GMT | Greenwichi aeg |
| Greenland_Eastern | Ida-Gröönimaa aegIda-Gröönimaa standardaegIda-Gröönimaa suveaeg |
| Greenland_Western | Lääne-Gröönimaa aegLääne-Gröönimaa standardaegLääne-Gröönimaa suveaeg |
| Guam | Guami standardaeg |
| Gulf | Pärsia lahe standardaeg |
| Guyana | Guyana aeg |
| Hawaii_Aleutian | Hawaii-Aleuudi aegHawaii-Aleuudi standardaegHawaii-Aleuudi suveaeg |
| Hong_Kong | Hongkongi aegHongkongi standardaegHongkongi suveaeg |
| Hovd | Hovdi aegHovdi standardaegHovdi suveaeg |
| India | India aeg |
| Indian_Ocean | India ookeani aeg |
| Indochina | Indohiina aeg |
| Indonesia_Central | Kesk-Indoneesia aeg |
| Indonesia_Eastern | Ida-Indoneesia aeg |
| Indonesia_Western | Lääne-Indoneesia aeg |
| Iran | Iraani aegIraani standardaegIraani suveaeg |
| Irkutsk | Irkutski aegIrkutski standardaegIrkutski suveaeg |
| Israel | Iisraeli aegIisraeli standardaegIisraeli suveaeg |
| Japan | Jaapani aegJaapani standardaegJaapani suveaeg |
| Kamchatka | Petropavlovsk-Kamtšatski aegKamtšatka standardaegKamtšatka suveaeg |
| Kazakhstan_Eastern | Ida-Kasahstani aeg |
| Kazakhstan_Western | Lääne-Kasahstani aeg |
| Korea | Korea aegKorea standardaegKorea suveaeg |
| Kosrae | Kosrae aeg |
| Krasnoyarsk | Krasnojarski aegKrasnojarski standardaegKrasnojarski suveaeg |
| Kyrgystan | Kõrgõzstani aeg |
| Lanka | Sri Lanka aeg |
| Line_Islands | Line’i saarte aeg |
| Lord_Howe | Lord Howe’i aegLord Howe’i standardaegLord Howe’i suveaeg |
| Macau | Macau aegMacau standardaegMacau suveaeg |
| Macquarie | Macquarie saare aeg |
| Magadan | Magadani aegMagadani standardaegMagadani suveaeg |
| Malaysia | Malaisia ​​aeg |
| Maldives | Maldiivi aeg |
| Marquesas | Markiisaarte aeg |
| Marshall_Islands | Marshalli Saarte aeg |
| Mauritius | Mauritiuse aegMauritiuse standardaegMauritiuse suveaeg |
| Mawson | Mawsoni aeg |
| Mexico_Northwest | Loode-Mehhiko aegLoode-Mehhiko standardaegLoode-Mehhiko suveaeg |
| Mexico_Pacific | Mehhiko Vaikse ookeani aegMehhiko Vaikse ookeani standardaegMehhiko Vaikse ookeani suveaeg |
| Mongolia | Ulaanbaatari aegUlaanbaatari standardaegUlaanbaatari suveaeg |
| Moscow | Moskva aegMoskva standardaegMoskva suveaeg |
| Myanmar | Birma aeg |
| Nauru | Nauru aeg |
| Nepal | Nepali aeg |
| New_Caledonia | Uus-Kaledoonia aegUus-Kaledoonia standardaegUus-Kaledoonia suveaeg |
| New_Zealand | Uus-Meremaa aegUus-Meremaa standardaegUus-Meremaa suveaeg |
| Newfoundland | Newfoundlandi aegNewfoundlandi standardaegNewfoundlandi suveaeg |
| Niue | Niue aeg |
| Norfolk | Norfolki saarte aeg |
| Noronha | Fernando de Noronha aegFernando de Noronha standardaegFernando de Noronha suveaeg |
| North_Mariana | Põhja-Mariaani aeg |
| Novosibirsk | Novosibirski aegNovosibirski standardaegNovosibirski suveaeg |
| Omsk | Omski aegOmski standardaegOmski suveaeg |
| Pakistan | Pakistani aegPakistani standardaegPakistani suveaeg |
| Palau | Belau aeg |
| Papua_New_Guinea | Paapua Uus-Guinea aeg |
| Paraguay | Paraguay aegParaguay standardaegParaguay suveaeg |
| Peru | Peruu aegPeruu standardaegPeruu suveaeg |
| Philippines | Filipiini aegFilipiini standardaegFilipiini suveaeg |
| Phoenix_Islands | Fööniksisaarte aeg |
| Pierre_Miquelon | Saint-Pierre’i ja Miqueloni aegSaint-Pierre’i ja Miqueloni standardaegSaint-Pierre’i ja Miqueloni suveaeg |
| Pitcairn | Pitcairni aeg |
| Ponape | Pohnpei aeg |
| Pyongyang | Pyongyangi aeg |
| Qyzylorda | Kõzõlorda aegKõzõlorda standardaegKõzõlorda suveaeg |
| Reunion | Réunioni aeg |
| Rothera | Rothera aeg |
| Sakhalin | Sahhalini aegSahhalini standardaegSahhalini suveaeg |
| Samara | Samara aegSamara standardaegSamara suveaeg |
| Samoa | Samoa aegSamoa standardaegSamoa suveaeg |
| Seychelles | Seišelli aeg |
| Singapore | Singapuri standardaeg |
| Solomon | Saalomoni Saarte aeg |
| South_Georgia | Lõuna-Georgia aeg |
| Suriname | Suriname aeg |
| Syowa | Syowa aeg |
| Tahiti | Tahiti aeg |
| Taipei | Taipei aegTaipei standardaegTaipei suveaeg |
| Tajikistan | Tadžikistani aeg |
| Tokelau | Tokelau aeg |
| Tonga | Tonga aegTonga standardaegTonga suveaeg |
| Truk | Chuuki aeg |
| Turkmenistan | Türkmenistani aegTürkmenistani standardaegTürkmenistani suveaeg |
| Tuvalu | Tuvalu aeg |
| Uruguay | Uruguay aegUruguay standardaegUruguay suveaeg |
| Uzbekistan | Usbekistani aegUsbekistani standardaegUsbekistani suveaeg |
| Vanuatu | Vanuatu aegVanuatu standardaegVanuatu suveaeg |
| Venezuela | Venezuela aeg |
| Vladivostok | Vladivostoki aegVladivostoki standardaegVladivostoki suveaeg |
| Volgograd | Volgogradi aegVolgogradi standardaegVolgogradi suveaeg |
| Vostok | Vostoki aeg |
| Wake | Wake’i aeg |
| Wallis | Wallise ja Futuna aeg |
| Yakutsk | Jakutski aegJakutski standardaegJakutski suveaeg |
| Yekaterinburg | Jakaterinburgi aegJekaterinburgi standardaegJakaterinburgi suveaeg |
## Numbers stuff
latnlatn2
| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | ×10^ |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | NaN |
| Time separator (Hours:Minutes) | : |
#,##0.###0 tuhat0 tuhat00 tuhat00 tuhat000 tuhat000 tuhat0 miljon0 miljonit00 miljonit00 miljonit000 miljonit000 miljonit0 miljard0 miljardit00 miljardit00 miljardit000 miljardit000 miljardit0 triljon0 triljonit00 triljonit00 triljonit000 triljonit000 triljonit0 tuh0 tuh00 tuh00 tuh000 tuh000 tuh0 mln0 mln00 mln00 mln000 mln000 mln0 mld0 mld00 mld00 mld000 mld000 mld0 trl0 trl00 trl00 trl000 trl000 trl#E0#,##0%#,##0.00 ¤#,##0.00 ¤;(#,##0.00 ¤)0 tuh ¤0 tuh ¤00 tuh ¤00 tuh ¤000 tuh ¤000 tuh ¤0 mln ¤0 mln ¤00 mln ¤00 mln ¤000 mln ¤000 mln ¤0 mld ¤0 mld ¤00 mld ¤00 mld ¤000 mld ¤000 mld ¤0 trl ¤0 trl ¤00 trl ¤00 trl ¤000 trl ¤000 trl ¤
| one | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  | Andorra peseeta |
| one | Andorra peseeta |
| other | Andorra peseetat |
|  | Araabia Ühendemiraatide dirhem |
| one | Araabia Ühendemiraatide dirhem |
| other | Araabia Ühendemiraatide dirhemit |
|  symbol | AED |
|  | Afganistani afgaani (1927–2002) |
| one | Afganistani afgaani (1927–2002) |
| other | Afganistani afgaanit (1927–2002) |
|  | Afganistani afgaani |
| one | Afganistani afgaani |
| other | Afganistani afgaanit |
|  symbol | AFN |
|  | Albaania lekk (1946–1965) |
| one | Albaania lekk (1946–1965) |
| other | Albaania lekki (1946–1965) |
|  | Albaania lekk |
| one | Albaania lekk |
| other | Albaania lekki |
|  symbol | ALL |
|  | Armeenia dramm |
| one | Armeenia dramm |
| other | Armeenia drammi |
|  symbol | AMD |
|  | Hollandi Antillide kulden |
| one | Hollandi Antillide kulden |
| other | Hollandi Antillide kuldnat |
|  symbol | ANG |
|  | Angola kvanza |
| one | Angola kvanza |
| other | Angola kvanzat |
|  symbol | AOA |
|  | Angola kvanza (1977–1990) |
| one | Angola kvanza (1977–1990) |
| other | Angola kvanzat (1977–1990) |
|  | Angola kvanza (1990–2000) |
| one | Angola kvanza (1990–2000) |
| other | Angola kvanzat (1990–2000) |
|  | Angola reformitud kvanza, 1995–1999 |
|  | Argentina austral |
|  | Argentina peeso (1881–1970) |
| one | Argentina peeso (1881–1970) |
| other | Argentina peesot (1881–1970) |
|  | Argentina peeso (1983–1985) |
| one | Argentina peeso (1983–1985) |
| other | Argentina peesot (1983–1985) |
|  | Argentina peeso |
| one | Argentina peeso |
| other | Argentina peesot |
|  symbol | ARS |
| narrow symbol | $ |
|  | Austria šilling |
| one | Austria šilling |
| other | Austria šillingit |
|  | Austraalia dollar |
| one | Austraalia dollar |
| other | Austraalia dollarit |
|  symbol | AU$ |
| narrow symbol | $ |
|  | Aruba kulden |
| one | Aruba kulden |
| other | Aruba kuldnat |
|  symbol | AWG |
|  | Aserbaidžaani manat (1993–2006) |
| one | Aserbaidžaani manat (1993–2006) |
| other | Aserbaidžaani manatit (1993–2006) |
|  | Aserbaidžaani manat |
| one | Aserbaidžaani manat |
| other | Aserbaidžaani manatit |
|  symbol | AZN |
|  | Bosnia ja Hertsegoviina dinaar (1992–1994) |
| one | Bosnia ja Hertsegoviina dinaar (1992–1994) |
| other | Bosnia ja Hertsegoviina dinaari (1992–1994) |
|  | Bosnia ja Hertsegoviina konverteeritav mark |
| one | Bosnia ja Hertsegoviina konverteeritav mark |
| other | Bosnia ja Hertsegoviina konverteeritavat marka |
|  symbol | BAM |
|  | Bosnia ja Hertsegoviina uus dinaar (1994–1997) |
| one | Bosnia ja Hertsegoviina uus dinaar (1994–1997) |
| other | Bosnia ja Hertsegoviina uut dinaari (1994–1997) |
|  | Barbadose dollar |
| one | Barbadose dollar |
| other | Barbadose dollarit |
|  symbol | BBD |
| narrow symbol | $ |
|  | Bangladeshi taka |
| one | Bangladeshi taka |
| other | Bangladeshi takat |
|  symbol | BDT |
| narrow symbol | ৳ |
|  | Belgia konverteeritav frank |
| one | Belgia konverteeritav frank |
| other | Belgia konverteeritavat franki |
|  | Belgia frank |
| one | Belgia frank |
| other | Belgia franki |
|  | Belgia arveldusfrank |
|  | Bulgaaria püsiv leev |
|  | Bulgaaria leev |
| one | Bulgaaria leev |
| other | Bulgaaria leevi |
|  symbol | BGN |
|  | Bulgaaria leev (1879–1952) |
| one | Bulgaaria leev (1879–1952) |
| other | Bulgaaria leevi (1879–1952) |
|  | Bahreini dinaar |
| one | Bahreini dinaar |
| other | Bahreini dinaari |
|  symbol | BHD |
|  | Burundi frank |
| one | Burundi frank |
| other | Burundi franki |
|  symbol | BIF |
|  | Bermuda dollar |
| one | Bermuda dollar |
| other | Bermuda dollarit |
|  symbol | BMD |
| narrow symbol | $ |
|  | Brunei dollar |
| one | Brunei dollar |
| other | Brunei dollarit |
|  symbol | BND |
| narrow symbol | $ |
|  | Boliivia boliviaano |
| one | Boliivia boliviaano |
| other | Boliivia boliviaanot |
|  symbol | BOB |
|  | Boliivia boliviaano (1863–1963) |
| one | Boliivia boliviaano (1863–1963) |
| other | Boliivia boliviaanot (1863–1963) |
|  | Boliivia peeso |
| one | Boliivia peeso |
| other | Boliivia peesot |
|  | Brasiilia uus kruseiro (1967–1986) |
| one | Brasiilia uus kruseiro (1967–1986) |
| other | Brasiilia uut kruseirot (1967–1986) |
|  | Brasiilia krusado |
|  | Brasiilia kruseiro (1990–1993) |
| one | Brasiilia kruseiro (1990–1993) |
| other | Brasiilia kruseirot (1990–1993) |
|  | Brasiilia reaal |
| one | Brasiilia reaal |
| other | Brasiilia reaali |
|  symbol | R$ |
| narrow symbol | R$ |
|  | Brasiilia kruseiro (1993–1994) |
| one | Brasiilia kruseiro (1993–1994) |
| other | Brasiilia kruseirot (1993–1994) |
|  | Brasiilia kruseiro (1942–1967) |
| one | Brasiilia kruseiro (1942–1967) |
| other | Brasiilia kruseirot (1942–1967) |
|  | Bahama dollar |
| one | Bahama dollar |
| other | Bahama dollarit |
|  symbol | BSD |
| narrow symbol | $ |
|  | Bhutani ngultrum |
| one | Bhutani ngultrum |
| other | Bhutani ngultrumit |
|  symbol | BTN |
|  | Birma kjatt |
| one | Birma kjatt |
| other | Birma kjatti |
|  | Botswana pula |
| one | Botswana pula |
| other | Botswana pulat |
|  symbol | BWP |
|  | Valgevene uus rubla (1994–1999) |
| one | Valgevene uus rubla (1994–1999) |
| other | Valgevene uut rubla (1994–1999) |
|  | Valgevene rubla |
| one | Valgevene rubla |
| other | Valgevene rubla |
|  symbol | BYN |
| narrow symbol | р. |
|  | Valgevene rubla (2000–2016) |
| one | Valgevene rubla (2000–2016) |
| other | Valgevene rubla (2000–2016) |
|  symbol | BYR |
|  | Belize’i dollar |
| one | Belize’i dollar |
| other | Belize’i dollarit |
|  symbol | BZD |
| narrow symbol | $ |
|  | Kanada dollar |
| one | Kanada dollar |
| other | Kanada dollarit |
|  symbol | CA$ |
| narrow symbol | $ |
|  | Kongo frank |
| one | Kongo frank |
| other | Kongo franki |
|  symbol | CDF |
|  | Šveitsi frank |
| one | Šveitsi frank |
| other | Šveitsi franki |
|  symbol | CHF |
|  | Tšiili eskuudo |
| one | Tšiili eskuudo |
| other | Tšiili eskuudot |
|  | Tšiili peeso |
| one | Tšiili peeso |
| other | Tšiili peesot |
|  symbol | CLP |
| narrow symbol | $ |
|  | Hiina jüaan (välismaine turg) |
| one | Hiina jüaan (välismaine turg) |
| other | Hiina jüaani (välismaine turg) |
|  | Hiina jüaan |
| one | Hiina jüaan |
| other | Hiina jüaani |
|  symbol | CN¥ |
| narrow symbol | ¥ |
|  | Colombia peeso |
| one | Colombia peeso |
| other | Colombia peesot |
|  symbol | COP |
| narrow symbol | $ |
|  | Costa Rica koloon |
| one | Costa Rica koloon |
| other | Costa Rica kolooni |
|  symbol | CRC |
| narrow symbol | ₡ |
|  | Serbia dinaar (2002–2006) |
| one | Serbia dinaar (2002–2006) |
| other | Serbia dinaari (2002–2006) |
|  | Kuuba konverteeritav peeso |
| one | Kuuba konverteeritav peeso |
| other | Kuuba konverteeritavat peesot |
|  symbol | CUC |
|  | Kuuba peeso |
| one | Kuuba peeso |
| other | Kuuba peesot |
|  symbol | CUP |
| narrow symbol | $ |
|  | Cabo Verde eskuudo |
| one | Cabo Verde eskuudo |
| other | Cabo Verde eskuudot |
|  symbol | CVE |
|  | Küprose nael |
| one | Küprose nael |
| other | Küprose naela |
|  | Tšehhi kroon |
| one | Tšehhi kroon |
| other | Tšehhi krooni |
|  symbol | CZK |
|  | Ida-Saksa mark |
| one | Ida-Saksa mark |
| other | Ida-Saksa marka |
|  | Saksa mark |
| one | Saksa mark |
| other | Saksa marka |
|  | Djibouti frank |
| one | Djibouti frank |
| other | Djibouti franki |
|  symbol | DJF |
|  | Taani kroon |
| one | Taani kroon |
| other | Taani krooni |
|  symbol | DKK |
| narrow symbol | kr |
|  | Dominikaani peeso |
| one | Dominikaani peeso |
| other | Dominikaani peesot |
|  symbol | DOP |
| narrow symbol | $ |
|  | Alžeeria dinaar |
| one | Alžeeria dinaar |
| other | Alžeeria dinaari |
|  symbol | DZD |
|  | Ecuadori sukre |
| one | Ecuadori sukre |
| other | Ecuadori sukret |
|  | Eesti kroon |
| one | Eesti kroon |
| other | Eesti krooni |
|  symbol | kr |
| Decimal separator | . |
| "Thousands" separator |   |
|  | Egiptuse nael |
| one | Egiptuse nael |
| other | Egiptuse naela |
|  symbol | EGP |
|  | Eritrea nakfa |
| one | Eritrea nakfa |
| other | Eritrea nakfat |
|  symbol | ERN |
|  | Hispaania peseeta |
| one | Hispaania peseeta |
| other | Hispaania peseetat |
|  | Etioopia birr |
| one | Etioopia birr |
| other | Etioopia birri |
|  symbol | ETB |
|  | euro |
| one | euro |
| other | eurot |
|  symbol | € |
| narrow symbol | € |
|  | Soome mark |
| one | Soome mark |
| other | Soome marka |
|  | Fidži dollar |
| one | Fidži dollar |
| other | Fidži dollarit |
|  symbol | FJD |
| narrow symbol | $ |
|  | Falklandi saarte nael |
| one | Falklandi saarte nael |
| other | Falklandi saarte naela |
|  symbol | FKP |
|  | Prantsuse frank |
| one | Prantsuse frank |
| other | Prantsuse franki |
|  | Suurbritannia naelsterling |
| one | Suurbritannia naelsterling |
| other | Suurbritannia naelsterlingit |
|  symbol | £ |
| narrow symbol | £ |
|  | Gruusia lari |
| one | Gruusia lari |
| other | Gruusia lari |
|  symbol | GEL |
|  | Ghana sedi (1979–2007) |
| one | Ghana sedi (1979–2007) |
| other | Ghana sedit (1979–2007) |
|  | Ghana sedi |
| one | Ghana sedi |
| other | Ghana sedit |
|  symbol | GHS |
|  | Gibraltari nael |
| one | Gibraltari nael |
| other | Gibraltari naela |
|  symbol | GIP |
| narrow symbol | £ |
|  | Gambia dalasi |
| one | Gambia dalasi |
| other | Gambia dalasit |
|  symbol | GMD |
|  | Guinea frank |
| one | Guinea frank |
| other | Guinea franki |
|  symbol | GNF |
|  | Guinea syli |
|  | Kreeka drahm |
| one | Kreeka drahm |
| other | Kreeka drahmi |
|  | Guatemala ketsaal |
| one | Guatemala ketsaal |
| other | Guatemala ketsaali |
|  symbol | GTQ |
|  | Portugali Guinea eskuudo |
| one | Portugali Guinea eskuudo |
| other | Portugali Guinea eskuudot |
|  | Guinea-Bissau peeso |
| one | Guinea-Bissau peeso |
| other | Guinea-Bissau peesot |
|  | Guyana dollar |
| one | Guyana dollar |
| other | Guyana dollarit |
|  symbol | GYD |
| narrow symbol | $ |
|  | Hongkongi dollar |
| one | Hongkongi dollar |
| other | Hongkongi dollarit |
|  symbol | HK$ |
| narrow symbol | $ |
|  | Hondurase lempiira |
| one | Hondurase lempiira |
| other | Hondurase lempiirat |
|  symbol | HNL |
|  | Horvaatia dinaar |
| one | Horvaatia dinaar |
| other | Horvaatia dinaari |
|  | Horvaatia kuna |
| one | Horvaatia kuna |
| other | Horvaatia kuna |
|  symbol | HRK |
|  | Haiti gurd |
| one | Haiti gurd |
| other | Haiti gurdi |
|  symbol | HTG |
|  | Ungari forint |
| one | Ungari forint |
| other | Ungari forintit |
|  symbol | HUF |
|  | Indoneesia ruupia |
| one | Indoneesia ruupia |
| other | Indoneesia ruupiat |
|  symbol | IDR |
|  | Iiri nael |
| one | Iiri nael |
| other | Iiri naela |
|  | Iisraeli nael |
| one | Iisraeli nael |
| other | Iisraeli naela |
|  | Iisraeli seekel (1980–1985) |
| one | Iisraeli seekel (1980–1985) |
| other | Iisraeli seekelit (1980–1985) |
|  | Iisraeli uus seekel |
| one | Iisraeli uus seekel |
| other | Iisraeli uut seeklit |
|  symbol | ₪ |
| narrow symbol | ₪ |
|  | India ruupia |
| one | India ruupia |
| other | India ruupiat |
|  symbol | ₹ |
| narrow symbol | ₹ |
|  | Iraagi dinaar |
| one | Iraagi dinaar |
| other | Iraagi dinaari |
|  symbol | IQD |
|  | Iraani riaal |
| one | Iraani riaal |
| other | Iraani riaali |
|  symbol | IRR |
|  | Islandi kroon (1918–1981) |
| one | Islandi kroon (1918–1981) |
| other | Islandi krooni (1918–1981) |
|  | Islandi kroon |
| one | Islandi kroon |
| other | Islandi krooni |
|  symbol | ISK |
| narrow symbol | kr |
|  | Itaalia liir |
| one | Itaalia liir |
| other | Itaalia liiri |
|  | Jamaica dollar |
| one | Jamaica dollar |
| other | Jamaica dollarit |
|  symbol | JMD |
| narrow symbol | $ |
|  | Jordaania dinaar |
| one | Jordaania dinaar |
| other | Jordaania dinaari |
|  symbol | JOD |
|  | Jaapani jeen |
| one | Jaapani jeen |
| other | Jaapani jeeni |
|  symbol | ¥ |
| narrow symbol | ¥ |
|  | Keenia šilling |
| one | Keenia šilling |
| other | Keenia šillingit |
|  symbol | KES |
|  | Kõrgõzstani somm |
| one | Kõrgõzstani somm |
| other | Kõrgõzstani sommi |
|  symbol | KGS |
|  | Kambodža riaal |
| one | Kambodža riaal |
| other | Kambodža riaali |
|  symbol | KHR |
| narrow symbol | ៛ |
|  | Komoori frank |
| one | Komoori frank |
| other | Komoori franki |
|  symbol | KMF |
|  | Põhja-Korea vonn |
| one | Põhja-Korea vonn |
| other | Põhja-Korea vonni |
|  symbol | KPW |
|  | Lõuna-Korea vonn (1945–1953) |
| one | Lõuna-Korea vonn (1945–1953) |
| other | Lõuna-Korea vonni (1945–1953) |
|  | Lõuna-Korea vonn |
| one | Lõuna-Korea vonn |
| other | Lõuna-Korea vonni |
|  symbol | ₩ |
| narrow symbol | ₩ |
|  | Kuveidi dinaar |
| one | Kuveidi dinaar |
| other | Kuveidi dinaari |
|  symbol | KWD |
|  | Kaimanisaarte dollar |
| one | Kaimanisaarte dollar |
| other | Kaimanisaarte dollarit |
|  symbol | KYD |
| narrow symbol | $ |
|  | Kasahstani tenge |
| one | Kasahstani tenge |
| other | Kasahstani tenget |
|  symbol | KZT |
| narrow symbol | ₸ |
|  | Laose kiip |
| one | Laose kiip |
| other | Laose kiipi |
|  symbol | LAK |
| narrow symbol | ₭ |
|  | Liibanoni nael |
| one | Liibanoni nael |
| other | Liibanoni naela |
|  symbol | LBP |
|  | Sri Lanka ruupia |
| one | Sri Lanka ruupia |
| other | Sri Lanka ruupiat |
|  symbol | LKR |
|  | Libeeria dollar |
| one | Libeeria dollar |
| other | Libeeria dollarit |
|  symbol | LRD |
| narrow symbol | $ |
|  | Lesotho loti |
| one | Lesotho loti |
| other | Lesotho lotit |
|  | Leedu litt |
| one | Leedu litt |
| other | Leedu litti |
|  symbol | LTL |
|  | Luksemburgi konverteeritav frank |
| one | Luksemburgi konverteeritav frank |
| other | Luksemburgi konverteeritavat franki |
|  | Luksemburgi frank |
| one | Luksemburgi frank |
| other | Luksemburgi franki |
|  | Läti latt |
| one | Läti latt |
| other | Läti latti |
|  symbol | LVL |
|  | Läti rubla |
| one | Läti rubla |
| other | Läti rubla |
|  | Liibüa dinaar |
| one | Liibüa dinaar |
| other | Liibüa dinaari |
|  symbol | LYD |
|  | Maroko dirhem |
| one | Maroko dirhem |
| other | Maroko dirhemit |
|  symbol | MAD |
|  | Maroko frank |
| one | Maroko frank |
| other | Maroko franki |
|  | Monaco frank |
| one | Monaco frank |
| other | Monaco franki |
|  | Moldova leu |
| one | Moldova leu |
| other | Moldova leud |
|  symbol | MDL |
|  | Madagaskari ariari |
| one | Madagaskari ariari |
| other | Madagaskari ariarit |
|  symbol | MGA |
|  | Madagaskar frank |
| one | Madagaskar frank |
| other | Madagaskar franki |
|  | Makedoonia dinaar |
| one | Makedoonia dinaar |
| other | Makedoonia dinaari |
|  symbol | MKD |
|  | Makedoonia dinaar (1992–1993) |
| one | Makedoonia dinaar (1992–1993) |
| other | Makedoonia dinaari (1992–1993) |
|  | Mali frank |
| one | Mali frank |
| other | Mali franki |
|  | Myanmari kjatt |
| one | Myanmari kjatt |
| other | Myanmari kjatti |
|  symbol | MMK |
|  | Mongoolia tugrik |
| one | Mongoolia tugrik |
| other | Mongoolia tugrikut |
|  symbol | MNT |
| narrow symbol | ₮ |
|  | Macau pataaka |
| one | Macau pataaka |
| other | Macau pataakat |
|  symbol | MOP |
|  | Mauritaania ugia |
| one | Mauritaania ugia |
| other | Mauritaania ugiat |
|  symbol | MRO |
|  | Malta liir |
| one | Malta liir |
| other | Malta liiri |
|  | Malta nael |
| one | Malta nael |
| other | Malta naela |
|  | Mauritiuse ruupia |
| one | Mauritiuse ruupia |
| other | Mauritiuse ruupiat |
|  symbol | MUR |
|  | Maldiivi ruupia (1947–1981) |
| one | Maldiivi ruupia (1947–1981) |
| other | Maldiivi ruupiat (1947–1981) |
|  | Maldiivi ruupia |
| one | Maldiivi ruupia |
| other | Maldiivi ruupiat |
|  symbol | MVR |
|  | Malawi kvatša |
| one | Malawi kvatša |
| other | Malawi kvatšat |
|  symbol | MWK |
|  | Mehhiko peeso |
| one | Mehhiko peeso |
| other | Mehhiko peesot |
|  symbol | MX$ |
| narrow symbol | $ |
|  | Mehhiko peeso (1861–1992) |
| one | Mehhiko peeso (1861–1992) |
| other | Mehhiko peesot (1861–1992) |
|  | Malaisia ringgit |
| one | Malaisia ringgit |
| other | Malaisia ringgitit |
|  symbol | MYR |
|  | Mosambiigi eskuudo |
| one | Mosambiigi eskuudo |
| other | Mosambiigi eskuudot |
|  | Mosambiigi metikal (1980–2006) |
| one | Mosambiigi metikal (1980–2006) |
| other | Mosambiigi metikali (1980–2006) |
|  | Mosambiigi metikal |
| one | Mosambiigi metikal |
| other | Mosambiigi metikali |
|  symbol | MZN |
|  | Namiibia dollar |
| one | Namiibia dollar |
| other | Namiibia dollarit |
|  symbol | NAD |
| narrow symbol | $ |
|  | Nigeeria naira |
| one | Nigeeria naira |
| other | Nigeeria nairat |
|  symbol | NGN |
| narrow symbol | ₦ |
|  | Nicaragua kordoba (1988–1991) |
| one | Nicaragua kordoba (1988–1991) |
| other | Nicaragua kordobat (1988–1991) |
|  | Nicaragua kordoba |
| one | Nicaragua kordoba |
| other | Nicaragua kordobad |
|  symbol | NIO |
|  | Hollandi kulden |
| one | Hollandi kulden |
| other | Hollandi kuldnat |
|  | Norra kroon |
| one | Norra kroon |
| other | Norra krooni |
|  symbol | NOK |
|  | Nepali ruupia |
| one | Nepali ruupia |
| other | Nepali ruupiat |
|  symbol | NPR |
|  | Uus-Meremaa dollar |
| one | Uus-Meremaa dollar |
| other | Uus-Meremaa dollarit |
|  symbol | NZ$ |
| narrow symbol | $ |
|  | Omaani riaal |
| one | Omaani riaal |
| other | Omaani riaali |
|  symbol | OMR |
|  | Panama balboa |
| one | Panama balboa |
| other | Panama balboad |
|  symbol | PAB |
|  | Peruu inti |
|  | Peruu soll |
| one | Peruu soll |
| other | Peruu solli |
|  symbol | PEN |
|  | Peruu soll (1863–1965) |
| one | Peruu soll (1863–1965) |
| other | Peruu solli (1863–1965) |
|  | Paapua Uus-Guinea kina |
| one | Paapua Uus-Guinea kina |
| other | Paapua Uus-Guinea kinat |
|  symbol | PGK |
|  | Filipiini peeso |
| one | Filipiini peeso |
| other | Filipiini peesot |
|  symbol | PHP |
| narrow symbol | ₱ |
|  | Pakistani ruupia |
| one | Pakistani ruupia |
| other | Pakistani ruupiat |
|  symbol | PKR |
|  | Poola zlott |
| one | Poola zlott |
| other | Poola zlotti |
|  symbol | PLN |
|  | Poola zlott (1950–1995) |
| one | Poola zlott (1950–1995) |
| other | Poola zlotti (1950–1995) |
|  | Portugali eskuudo |
| one | Portugali eskuudo |
| other | Portugali eskuudot |
|  | Paraguay guaranii |
| one | Paraguay guaranii |
| other | Paraguay guaraniid |
|  symbol | PYG |
| narrow symbol | ₲ |
|  | Katari riaal |
| one | Katari riaal |
| other | Katari riaali |
|  symbol | QAR |
|  | Rodeesia dollar |
| one | Rodeesia dollar |
| other | Rodeesia dollarit |
|  | Rumeenia leu (1952–2006) |
| one | Rumeenia leu (1952–2006) |
| other | Rumeenia leud (1952–2006) |
|  | Rumeenia leu |
| one | Rumeenia leu |
| other | Rumeenia leud |
|  symbol | RON |
|  | Serbia dinaar |
| one | Serbia dinaar |
| other | Serbia dinaari |
|  symbol | RSD |
|  | Venemaa rubla |
| one | Venemaa rubla |
| other | Venemaa rubla |
|  symbol | RUB |
|  | Venemaa rubla (1991–1998) |
|  | Rwanda frank |
| one | Rwanda frank |
| other | Rwanda franki |
|  symbol | RWF |
|  | Saudi Araabia riaal |
| one | Saudi Araabia riaal |
| other | Saudi Araabia riaali |
|  symbol | SAR |
|  | Saalomoni Saarte dollar |
| one | Saalomoni Saarte dollar |
| other | Saalomoni Saarte dollarit |
|  symbol | SBD |
| narrow symbol | $ |
|  | Seišelli ruupia |
| one | Seišelli ruupia |
| other | Seišelli ruupiat |
|  symbol | SCR |
|  | Sudaani dinaar (1992–2007) |
| one | Sudaani dinaar (1992–2007) |
| other | Sudaani dinaari (1992–2007) |
|  | Sudaani nael |
| one | Sudaani nael |
| other | Sudaani naela |
|  symbol | SDG |
|  | Sudaani nael (1957–1998) |
| one | Sudaani nael (1957–1998) |
| other | Sudaani naela (1957–1998) |
|  | Rootsi kroon |
| one | Rootsi kroon |
| other | Rootsi krooni |
|  symbol | SEK |
|  | Singapuri dollar |
| one | Singapuri dollar |
| other | Singapuri dollarit |
|  symbol | SGD |
| narrow symbol | $ |
|  | Saint Helena nael |
| one | Saint Helena nael |
| other | Saint Helena naela |
|  symbol | SHP |
|  | Sloveenia tolar |
| one | Sloveenia tolar |
| other | Sloveenia tolarit |
|  | Slovaki kroon |
| one | Slovaki kroon |
| other | Slovaki krooni |
|  | Sierra Leone leoone |
| one | Sierra Leone leoone |
| other | Sierra Leone leoonet |
|  symbol | SLL |
|  | Somaalia šilling |
| one | Somaalia šilling |
| other | Somaalia šillingit |
|  symbol | SOS |
|  | Suriname dollar |
| one | Suriname dollar |
| other | Suriname dollarit |
|  symbol | SRD |
| narrow symbol | $ |
|  | Suriname kulden |
| one | Suriname kulden |
| other | Suriname kuldnat |
|  | Lõuna-Sudaani nael |
| one | Lõuna-Sudaani nael |
| other | Lõuna-Sudaani naela |
|  symbol | SSP |
| narrow symbol | £ |
|  | São Tomé ja Príncipe dobra (1977–2017) |
| one | São Tomé ja Príncipe dobra (1977–2017) |
| other | São Tomé ja Príncipe dobrat (1977–2017) |
|  symbol | STD |
|  | São Tomé ja Príncipe dobra |
| one | São Tomé ja Príncipe dobra |
| other | São Tomé ja Príncipe dobrat |
|  | NSVL-i rubla |
|  | El Salvadori koloon |
| one | El Salvadori koloon |
| other | El Salvadori kolooni |
|  | Süüria nael |
| one | Süüria nael |
| other | Süüria naela |
|  symbol | SYP |
|  | Svaasimaa lilangeni |
| one | Svaasimaa lilangeni |
| other | Svaasimaa lilangenit |
|  symbol | SZL |
|  | Tai baat |
| one | Tai baat |
| other | Tai baati |
|  symbol | ฿ |
| narrow symbol | ฿ |
|  | Tadžikistani rubla |
| one | Tadžikistani rubla |
| other | Tadžikistani rubla |
|  | Tadžikistani somoni |
| one | Tadžikistani somoni |
| other | Tadžikistani somonit |
|  symbol | TJS |
|  | Türkmenistani manat (1993–2009) |
| one | Türkmenistani manat (1993–2009) |
| other | Türkmenistani manatit (1993–2009) |
|  | Türkmenistani manat |
| one | Türkmenistani manat |
| other | Türkmenistani manatit |
|  symbol | TMT |
|  | Tuneesia dinaar |
| one | Tuneesia dinaar |
| other | Tuneesia dinaari |
|  symbol | TND |
|  | Tonga pa’anga |
| one | Tonga pa’anga |
| other | Tonga pa’angat |
|  symbol | TOP |
|  | Timori eskuudo |
| one | Timori eskuudo |
| other | Timori eskuudot |
|  | Türgi liir (1922–2005) |
| one | Türgi liir (1922–2005) |
| other | Türgi liiri (1922–2005) |
|  | Türgi liir |
| one | Türgi liir |
| other | Türgi liiri |
|  symbol | TRY |
| narrow symbol | ₺ |
|  | Trinidadi ja Tobago dollar |
| one | Trinidadi ja Tobago dollar |
| other | Trinidadi ja Tobago dollarit |
|  symbol | TTD |
| narrow symbol | $ |
|  | uus Taiwani dollar |
| one | uus Taiwani dollar |
| other | uut Taiwani dollarit |
|  symbol | NT$ |
| narrow symbol | NT$ |
|  | Tansaania šilling |
| one | Tansaania šilling |
| other | Tansaania šillingit |
|  symbol | TZS |
|  | Ukraina grivna |
| one | Ukraina grivna |
| other | Ukraina grivnat |
|  symbol | UAH |
| narrow symbol | ₴ |
|  | Ukraina karbovanets |
|  | Uganda šilling (1966–1987) |
| one | Uganda šilling (1966–1987) |
| other | Uganda šillingit (1966–1987) |
|  | Uganda šilling |
| one | Uganda šilling |
| other | Uganda šillingit |
|  symbol | UGX |
|  | USA dollar |
| one | USA dollar |
| other | USA dollarit |
|  symbol | $ |
| narrow symbol | $ |
|  | USA järgmise päeva dollar |
|  | USA sama päeva dollar |
|  | Uruguay peeso (1975–1993) |
| one | Uruguay peeso (1975–1993) |
| other | Uruguay peesot (1975–1993) |
|  | Uruguay peeso |
| one | Uruguay peeso |
| other | Uruguay peesot |
|  symbol | UYU |
| narrow symbol | $ |
|  | Usbekistani somm |
| one | Usbekistani somm |
| other | Usbekistani sommi |
|  symbol | UZS |
|  | Venezuela boliivar (1871–2008) |
| one | Venezuela boliivar (1871–2008) |
| other | Venezuela boliivarit (1871–2008) |
|  | Venezuela boliivar |
| one | Venezuela boliivar |
| other | Venezuela boliivarit |
|  symbol | VEF |
|  | Vietnami dong |
| one | Vietnami dong |
| other | Vietnami dongi |
|  symbol | ₫ |
| narrow symbol | ₫ |
|  | Vietnami dong (1978–1985) |
| one | Vietnami dong (1978–1985) |
| other | Vietnami dongi (1978–1985) |
|  | Vanuatu vatu |
| one | Vanuatu vatu |
| other | Vanuatu vatut |
|  symbol | VUV |
|  | Samoa taala |
| one | Samoa taala |
| other | Samoa taalat |
|  symbol | WST |
|  | Kesk-Aafrika CFA frank |
| one | Kesk-Aafrika CFA frank |
| other | Kesk-Aafrika CFA franki |
|  symbol | FCFA |
|  | hõbe |
| one | troiunts hõbedat |
| other | troiuntsi hõbedat |
|  | kuld |
| one | troiunts kulda |
| other | troiuntsi kulda |
|  | EURCO |
|  | Euroopa rahaühik |
|  | Euroopa rahaline arvestusühik (XBC) |
|  | Euroopa rahaline arvestusühik (XBD) |
|  | Ida-Kariibi dollar |
| one | Ida-Kariibi dollar |
| other | Ida-Kariibi dollarit |
|  symbol | EC$ |
|  | Rahvusvahelise Valuutafondi arvestusühik |
|  | eküü |
| one | eküü |
| other | eküüd |
|  | Prantsuse kuldfrank |
| one | Prantsuse kuldfrank |
| other | Prantsuse kuldfranki |
|  | Prantsuse UIC-frank |
|  | Lääne-Aafrika CFA frank |
| one | Lääne-Aafrika CFA frank |
| other | Lääne-Aafrika CFA franki |
|  symbol | CFA |
|  | pallaadium |
| one | troiunts pallaadiumit |
| other | troiuntsi pallaadiumit |
|  | CFP frank |
| one | CFP frank |
| other | CFP franki |
|  symbol | CFPF |
|  | plaatina |
| one | troiunts plaatinat |
| other | troiuntsi plaatinat |
|  | vääringute testkood |
|  | määramata rahaühik |
| one | (määramata rahaühik) |
| other | (määramata rahaühikut) |
|  | Jeemeni dinaar |
| one | Jeemeni dinaar |
| other | Jeemeni dinaari |
|  | Jeemeni riaal |
| one | Jeemeni riaal |
| other | Jeemeni riaali |
|  symbol | YER |
|  | Jugoslaavia uus dinaar (1994–2002) |
| one | Jugoslaavia uus dinaar (1994–2002) |
| other | Jugoslaavia uut dinaari (1994–2002) |
|  | Jugoslaavia konverteeritav dinaar (1990–1992) |
| one | Jugoslaavia konverteeritav dinaar (1990–1992) |
| other | Jugoslaavia konverteeritavat dinaari (1990–1992) |
|  | Lõuna-Aafrika rand |
| one | Lõuna-Aafrika rand |
| other | Lõuna-Aafrika randi |
|  symbol | ZAR |
|  | Sambia kvatša (1968–2012) |
| one | Sambia kvatša (1968–2012) |
| other | Sambia kvatšat (1968–2012) |
|  | Sambia kvatša |
| one | Sambia kvatša |
| other | Sambia kvatšat |
|  symbol | ZMW |
|  | Sairi zaire |
|  | Zimbabwe dollar (1980–2008) |
| one | Zimbabwe dollar (1980–2008) |
| other | Zimbabwe dollarit (1980–2008) |
|  | Zimbabwe dollar (2009) |
| one | Zimbabwe dollar (2009) |
| other | Zimbabwe dollarit (2009) |
|  | Zimbabwe dollar (2008) |
| one | Zimbabwe dollar (2008) |
| other | Zimbabwe dollarit (2008) |
Other stuff:
⩾{0}{0}‒{1}
Examples:
| one example | {0} ööpäev |
| other example | {0} ööpäeva |
Tehke {0}. parempööre.
## Units
| Code | Name |
| ---- | ---- |
| Compound pattern  | {0} {1} kohta |
| acceleration-g-force | ... |
|  | Maa raskuskiirendus |
| one | {0} Maa raskuskiirendus |
| other | {0} Maa raskuskiirendust |
| acceleration-meter-per-second-squared | ... |
|  | meetrid sekundi ruudu kohta |
| one | {0} meeter sekundi ruudu kohta |
| other | {0} meetrit sekundi ruudu kohta |
| angle-revolution | ... |
|  | täispööre |
| one | {0} täispööre |
| other | {0} täispööret |
| angle-radian | ... |
|  | radiaanid |
| one | {0} radiaan |
| other | {0} radiaani |
| angle-degree | ... |
|  | kraadid |
| one | {0} kraad |
| other | {0} kraadi |
| angle-arc-minute | ... |
|  | kaareminutid |
| one | {0} kaareminut |
| other | {0} kaareminutit |
| angle-arc-second | ... |
|  | kaaresekundid |
| one | {0} kaaresekund |
| other | {0} kaaresekundit |
| area-square-kilometer | ... |
|  | ruutkilomeetrid |
| one | {0} ruutkilomeeter |
| other | {0} ruutkilomeetrit |
{0} ruutkilomeetri kohta
| area-hectare | ... |
|  | hektarid |
| one | {0} hektar |
| other | {0} hektarit |
| area-square-meter | ... |
|  | ruutmeetrid |
| one | {0} ruutmeeter |
| other | {0} ruutmeetrit |
{0} ruutmeetri kohta
| area-square-centimeter | ... |
|  | ruutsentimeetrid |
| one | {0} ruutsentimeeter |
| other | {0} ruutsentimeetrit |
{0} ruutsentimeetri kohta
| area-square-mile | ... |
|  | ruutmiilid |
| one | {0} ruutmiil |
| other | {0} ruutmiili |
{0} ruutmiili kohta
| area-acre | ... |
|  | aakrid |
| one | {0} aaker |
| other | {0} aakrit |
| area-square-yard | ... |
|  | ruutjardid |
| one | {0} ruutjard |
| other | {0} ruutjardi |
| area-square-foot | ... |
|  | ruutjalad |
| one | {0} ruutjalg |
| other | {0} ruutjalga |
| area-square-inch | ... |
|  | ruuttollid |
| one | {0} ruuttoll |
| other | {0} ruuttolli |
{0} ruuttolli kohta
| concentr-karat | ... |
|  | karaadid |
| one | {0} karaat |
| other | {0} karaati |
| concentr-milligram-per-deciliter | ... |
|  | milligrammid detsiliitri kohta |
| one | {0} milligramm detsiliitri kohta |
| other | {0} milligrammi detsiliitri kohta |
| concentr-millimole-per-liter | ... |
|  | millimoolid liitri kohta |
| one | {0} millimool liitri kohta |
| other | {0} millimooli liitri kohta |
| concentr-part-per-million | ... |
|  | osa miljoni kohta |
| one | {0} osa miljoni kohta |
| other | {0} osa miljoni kohta |
| consumption-liter-per-kilometer | ... |
|  | liitrid kilomeetri kohta |
| one | {0} liiter kilomeetri kohta |
| other | {0} liitrit kilomeetri kohta |
| consumption-liter-per-100kilometers | ... |
|  | liitrid 100 kilomeetri kohta |
| one | liiter 100 kilomeetri kohta |
| other | {0} liitrit 100 kilomeetri kohta |
| consumption-mile-per-gallon | ... |
|  | miilid galloni kohta |
| one | {0} miil galloni kohta |
| other | {0} miili galloni kohta |
| consumption-mile-per-gallon-imperial | ... |
|  | miilid inglise galloni kohta |
| one | {0} miil inglise galloni kohta |
| other | {0} miili inglise galloni kohta |
| digital-terabyte | ... |
|  | terabaidid |
| one | {0} terabait |
| other | {0} terabaiti |
| digital-terabit | ... |
|  | terabitid |
| one | {0} terabitt |
| other | {0} terabitti |
| digital-gigabyte | ... |
|  | gigabaidid |
| one | {0} gigabait |
| other | {0} gigabaiti |
| digital-gigabit | ... |
|  | gigabitid |
| one | {0} gigabitt |
| other | {0} gigabitti |
| digital-megabyte | ... |
|  | megabaidid |
| one | {0} megabait |
| other | {0} megabaiti |
| digital-megabit | ... |
|  | megabitid |
| one | {0} megabitt |
| other | {0} megabitti |
| digital-kilobyte | ... |
|  | kilobaidid |
| one | {0} kilobait |
| other | {0} kilobaiti |
| digital-kilobit | ... |
|  | kilobitid |
| one | {0} kilobitt |
| other | {0} kilobitti |
| digital-byte | ... |
|  | baidid |
| one | {0} bait |
| other | {0} baiti |
| digital-bit | ... |
|  | bitid |
| one | {0} bitt |
| other | {0} bitti |
| duration-century | ... |
|  | sajandid |
| one | {0} sajand |
| other | {0} sajandit |
| duration-year | ... |
|  | aastad |
| one | {0} aasta |
| other | {0} aastat |
{0} aastas
| duration-month | ... |
|  | kuud |
| one | {0} kuu |
| other | {0} kuud |
{0} kuus
| duration-week | ... |
|  | nädalad |
| one | {0} nädal |
| other | {0} nädalat |
{0} nädalas
| duration-day | ... |
|  | ööpäevad |
| one | {0} ööpäev |
| other | {0} ööpäeva |
{0} ööpäevas
| duration-hour | ... |
|  | tunnid |
| one | {0} tund |
| other | {0} tundi |
{0} tunnis
| duration-minute | ... |
|  | minutid |
| one | {0} minut |
| other | {0} minutit |
{0} minutis
| duration-second | ... |
|  | sekundid |
| one | {0} sekund |
| other | {0} sekundit |
{0} sekundis
| duration-millisecond | ... |
|  | millisekundid |
| one | {0} millisekund |
| other | {0} millisekundit |
| duration-microsecond | ... |
|  | mikrosekundid |
| one | {0} mikrosekund |
| other | {0} mikrosekundit |
| duration-nanosecond | ... |
|  | nanosekundid |
| one | {0} nanosekund |
| other | {0} nanosekundit |
| electric-ampere | ... |
|  | amprid |
| one | {0} amper |
| other | {0} amprit |
| electric-milliampere | ... |
|  | milliamprid |
| one | {0} milliamper |
| other | {0} milliamprit |
| electric-ohm | ... |
|  | oomid |
| one | {0} oom |
| other | {0} oomi |
| electric-volt | ... |
|  | voldid |
| one | {0} volt |
| other | {0} volti |
| energy-kilocalorie | ... |
|  | kilokalorid |
| one | {0} kilokalor |
| other | {0} kilokalorit |
| energy-calorie | ... |
|  | kalorid |
| one | {0} kalor |
| other | {0} kalorit |
| energy-foodcalorie | ... |
|  | toidukalorid |
| one | {0} toidukalor |
| other | {0} toidukalorit |
| energy-kilojoule | ... |
|  | kilodžaulid |
| one | {0} kilodžaul |
| other | {0} kilodžauli |
| energy-joule | ... |
|  | džaulid |
| one | {0} džaul |
| other | {0} džauli |
| energy-kilowatt-hour | ... |
|  | kilovatt-tunnid |
| one | {0} kilovatt-tund |
| other | {0} kilovatt-tundi |
| frequency-gigahertz | ... |
|  | gigahertsid |
| one | {0} gigaherts |
| other | {0} gigahertsi |
| frequency-megahertz | ... |
|  | megahertsid |
| one | {0} megaherts |
| other | {0} megahertsi |
| frequency-kilohertz | ... |
|  | kilohertsid |
| one | {0} kiloherts |
| other | {0} kilohertsi |
| frequency-hertz | ... |
|  | hertsid |
| one | {0} herts |
| other | {0} hertsi |
| length-kilometer | ... |
|  | kilomeetrid |
| one | {0} kilomeeter |
| other | {0} kilomeetrit |
{0} kilomeetri kohta
| length-meter | ... |
|  | meetrid |
| one | {0} meeter |
| other | {0} meetrit |
{0} meetri kohta
| length-decimeter | ... |
|  | detsimeetrid |
| one | {0} detsimeeter |
| other | {0} detsimeetrit |
| length-centimeter | ... |
|  | sentimeetrid |
| one | {0} sentimeeter |
| other | {0} sentimeetrit |
{0} sentimeetri kohta
| length-millimeter | ... |
|  | millimeetrid |
| one | {0} millimeeter |
| other | {0} millimeetrit |
| length-micrometer | ... |
|  | mikromeetrid |
| one | {0} mikromeeter |
| other | {0} mikromeetrit |
| length-nanometer | ... |
|  | nanomeetrid |
| one | {0} nanomeeter |
| other | {0} nanomeetrit |
| length-picometer | ... |
|  | pikomeetrid |
| one | {0} pikomeeter |
| other | {0} pikomeetrit |
| length-mile | ... |
|  | miilid |
| one | {0} miil |
| other | {0} miili |
| length-yard | ... |
|  | jardid |
| one | {0} jard |
| other | {0} jardi |
| length-foot | ... |
|  | jalad |
| one | {0} jalg |
| other | {0} jalga |
{0} jala kohta
| length-inch | ... |
|  | tollid |
| one | {0} toll |
| other | {0} tolli |
{0} tolli kohta
| length-parsec | ... |
|  | parsekid |
| one | {0} parsek |
| other | {0} parsekit |
| length-light-year | ... |
|  | valgusaastad |
| one | {0} valgusaasta |
| other | {0} valgusaastat |
| length-astronomical-unit | ... |
|  | astronoomilised ühikud |
| one | {0} astronoomiline ühik |
| other | {0} astronoomilist ühikut |
| length-furlong | ... |
|  | furlongid |
| one | {0} furlong |
| other | {0} furlongi |
| length-fathom | ... |
|  | süllad |
| one | {0} süld |
| other | {0} sülda |
| length-nautical-mile | ... |
|  | meremiilid |
| one | {0} meremiil |
| other | {0} meremiili |
| length-mile-scandinavian | ... |
|  | Skandinaavia miilid |
| one | {0} Skandinaavia miil |
| other | {0} Skandinaavia miili |
| length-point | ... |
|  | punktid |
| one | {0} punkt |
| other | {0} punkti |
| light-lux | ... |
|  | luks |
| one | {0} luks |
| other | {0} luksi |
| mass-metric-ton | ... |
|  | tonnid |
| one | {0} tonn |
| other | {0} tonni |
| mass-kilogram | ... |
|  | kilogrammid |
| one | {0} kilogramm |
| other | {0} kilogrammi |
{0} kilogrammi kohta
| mass-gram | ... |
|  | grammid |
| one | {0} gramm |
| other | {0} grammi |
{0} grammi kohta
| mass-milligram | ... |
|  | milligrammid |
| one | {0} milligramm |
| other | {0} milligrammi |
| mass-microgram | ... |
|  | mikrogrammid |
| one | {0} mikrogramm |
| other | {0} mikrogrammi |
| mass-ton | ... |
|  | lühikesed tonnid |
| one | {0} lühike tonn |
| other | {0} lühikest tonni |
| mass-stone | ... |
|  | kivid |
| one | {0} kivi |
| other | {0} kivi |
| mass-pound | ... |
|  | naelad |
| one | {0} nael |
| other | {0} naela |
{0} naela kohta
| mass-ounce | ... |
|  | untsid |
| one | {0} unts |
| other | {0} untsi |
{0} untsi kohta
| mass-ounce-troy | ... |
|  | troiuntsid |
| one | {0} troiunts |
| other | {0} troiuntsi |
| mass-carat | ... |
|  | karaadid |
| one | {0} karaat |
| other | {0} karaati |
| power-gigawatt | ... |
|  | gigavatid |
| one | {0} gigavatt |
| other | {0} gigavatti |
| power-megawatt | ... |
|  | megavatid |
| one | {0} megavatt |
| other | {0} megavatti |
| power-kilowatt | ... |
|  | kilovatid |
| one | {0} kilovatt |
| other | {0} kilovatti |
| power-watt | ... |
|  | vatid |
| one | {0} vatt |
| other | {0} vatti |
| power-milliwatt | ... |
|  | millivatid |
| one | {0} millivatt |
| other | {0} millivatti |
| power-horsepower | ... |
|  | hobujõud |
| one | {0} hobujõud |
| other | {0} hobujõudu |
| pressure-hectopascal | ... |
|  | hektopaskalid |
| one | {0} hektopaskal |
| other | {0} hektopaskalit |
| pressure-millimeter-of-mercury | ... |
|  | millimeetrid elavhõbedasammast |
| one | {0} millimeeter elavhõbedasammast |
| other | {0} millimeetrit elavhõbedasammast |
| pressure-pound-per-square-inch | ... |
|  | naelad ruuttolli kohta |
| one | {0} nael ruuttolli kohta |
| other | {0} naela ruuttolli kohta |
| pressure-inch-hg | ... |
|  | tollid elavhõbedasammast |
| one | {0} toll elavhõbedasammast |
| other | {0} tolli elavhõbedasammast |
| pressure-millibar | ... |
|  | millibaarid |
| one | {0} millibaar |
| other | {0} millibaari |
| speed-kilometer-per-hour | ... |
|  | kilomeetrid tunnis |
| one | {0} kilomeeter tunnis |
| other | {0} kilomeetrit tunnis |
| speed-meter-per-second | ... |
|  | meetrid sekundis |
| one | {0} meeter sekundis |
| other | {0} meetrit sekundis |
| speed-mile-per-hour | ... |
|  | miilid tunnis |
| one | {0} miil tunnis |
| other | {0} miili tunnis |
| speed-knot | ... |
|  | sõlm |
| one | {0} sõlm |
| other | {0} sõlme |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | Celsiuse kraadid |
| one | {0} Celsiuse kraad |
| other | {0} Celsiuse kraadi |
| temperature-fahrenheit | ... |
|  | Fahrenheiti kraadid |
| one | {0} Fahrenheiti kraad |
| other | {0} Fahrenheiti kraadi |
| temperature-kelvin | ... |
|  | kelvinid |
| one | {0} kelvin |
| other | {0} kelvinit |
| volume-cubic-kilometer | ... |
|  | kuupkilomeetrid |
| one | {0} kuupkilomeeter |
| other | {0} kuupkilomeetrit |
| volume-cubic-meter | ... |
|  | kuupmeetrid |
| one | {0} kuupmeeter |
| other | {0} kuupmeetrit |
{0} kuupmeetri kohta
| volume-cubic-centimeter | ... |
|  | kuupsentimeetrid |
| one | {0} kuupsentimeeter |
| other | {0} kuupsentimeetrit |
{0} kuupsentimeetri kohta
| volume-cubic-mile | ... |
|  | kuupmiilid |
| one | {0} kuupmiil |
| other | {0} kuupmiili |
| volume-cubic-yard | ... |
|  | kuupjardid |
| one | {0} kuupjard |
| other | {0} kuupjardi |
| volume-cubic-foot | ... |
|  | kuupjalad |
| one | {0} kuupjalg |
| other | {0} kuupjalga |
| volume-cubic-inch | ... |
|  | kuuptollid |
| one | {0} kuuptoll |
| other | {0} kuuptolli |
| volume-megaliter | ... |
|  | megaliitrid |
| one | {0} megaliiter |
| other | {0} megaliitrit |
| volume-hectoliter | ... |
|  | hektoliitrid |
| one | {0} hektoliiter |
| other | {0} hektoliitrit |
| volume-liter | ... |
|  | liitrid |
| one | {0} liiter |
| other | {0} liitrit |
{0} liitri kohta
| volume-deciliter | ... |
|  | detsiliitrid |
| one | {0} detsiliiter |
| other | {0} detsiliitrit |
| volume-centiliter | ... |
|  | sentiliitrid |
| one | {0} sentiliiter |
| other | {0} sentiliitrit |
| volume-milliliter | ... |
|  | milliliitrid |
| one | {0} milliliiter |
| other | {0} milliliitrit |
| volume-pint-metric | ... |
|  | meetrilised pindid |
| one | {0} meetriline pint |
| other | {0} meetrilist pinti |
| volume-cup-metric | ... |
|  | meetrilised tassid |
| one | {0} meetriline tass |
| other | {0} meetrilist tassi |
| volume-acre-foot | ... |
|  | aakerjalad |
| one | {0} aakerjalg |
| other | {0} aakerjalga |
| volume-bushel | ... |
|  | buššelid |
| one | {0} buššel |
| other | {0} buššelit |
| volume-gallon | ... |
|  | gallonid |
| one | {0} gallon |
| other | {0} gallonit |
{0} galloni kohta
| volume-gallon-imperial | ... |
|  | inglise gallonid |
| one | {0} inglise gallon |
| other | {0} inglise gallonit |
{0} inglise galloni kohta
| volume-quart | ... |
|  | kvardid |
| one | {0} kvart |
| other | {0} kvarti |
| volume-pint | ... |
|  | pindid |
| one | {0} pint |
| other | {0} pinti |
| volume-cup | ... |
|  | tassid |
| one | {0} tass |
| other | {0} tassi |
| volume-fluid-ounce | ... |
|  | vedelikuuntsid |
| one | {0} vedelikuunts |
| other | {0} vedelikuuntsi |
| volume-tablespoon | ... |
|  | supilusikad |
| one | {0} supilusikas |
| other | {0} supilusikat |
| volume-teaspoon | ... |
|  | teelusikad |
| one | {0} teelusikas |
| other | {0} teelusikat |
{0} idapikkust{0} põhjalaiust{0} lõunalaiust{0} läänepikkust
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | Maa raskuskiirendus |
| one | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
|  | m/s² |
| one | {0} m/s² |
| other | {0} m/s² |
| angle-revolution | ... |
|  | pööre |
| one | {0} pööre |
| other | {0} pööret |
| angle-radian | ... |
|  | radiaanid |
| one | {0} rad |
| other | {0} rad |
| angle-degree | ... |
|  | kraadid |
| one | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | kaareminut |
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
|  | hektarid |
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
|  | aakrid |
| one | {0} ac |
| other | {0} ac |
| area-square-yard | ... |
|  | ruutjardid |
| one | {0} yd² |
| other | {0} yd² |
| area-square-foot | ... |
|  | ruutjalad |
| one | {0} ft² |
| other | {0} ft² |
| area-square-inch | ... |
|  | ruuttollid |
| one | {0} in² |
| other | {0} in² |
{0}/in²
| concentr-karat | ... |
|  | karaat |
| one | {0} ct |
| other | {0} ct |
| concentr-milligram-per-deciliter | ... |
|  | mg/dl |
| one | {0} mg/dl |
| other | {0} mg/dl |
| concentr-millimole-per-liter | ... |
|  | mmol/l |
| one | {0} mmol/l |
| other | {0} mmol/l |
| concentr-part-per-million | ... |
|  | osa/miljon |
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
|  | miil/gallon |
| one | {0} mpg |
| other | {0} mpg |
| consumption-mile-per-gallon-imperial | ... |
|  | miil/gal imp. |
| one | {0} mpg imp. |
| other | {0} mpg imp. |
| digital-terabyte | ... |
|  | TB |
| one | {0} TB |
| other | {0} TB |
| digital-terabit | ... |
|  | Tb |
| one | {0} Tb |
| other | {0} Tb |
| digital-gigabyte | ... |
|  | GB |
| one | {0} GB |
| other | {0} GB |
| digital-gigabit | ... |
|  | Gb |
| one | {0} Gb |
| other | {0} Gb |
| digital-megabyte | ... |
|  | MB |
| one | {0} MB |
| other | {0} MB |
| digital-megabit | ... |
|  | Mb |
| one | {0} Mb |
| other | {0} Mb |
| digital-kilobyte | ... |
|  | kB |
| one | {0} kB |
| other | {0} kB |
| digital-kilobit | ... |
|  | kb |
| one | {0} kb |
| other | {0} kb |
| digital-byte | ... |
|  | bait |
| one | {0} bait |
| other | {0} baiti |
| digital-bit | ... |
|  | bitt |
| one | {0} b |
| other | {0} b |
| duration-century | ... |
|  | saj |
| one | {0} saj |
| other | {0} saj |
| duration-year | ... |
|  | aastad |
| one | {0} a |
| other | {0} a |
{0}/a
| duration-month | ... |
|  | kuud |
| one | {0} kuu |
| other | {0} kuud |
{0}/k
| duration-week | ... |
|  | näd |
| one | {0} näd |
| other | {0} näd |
{0}/näd
| duration-day | ... |
|  | päevad |
| one | {0} päev |
| other | {0} päeva |
{0}/ööp
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
| one | {0} sek |
| other | {0} sek |
{0}/sek
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
|  | amprid |
| one | {0} A |
| other | {0} A |
| electric-milliampere | ... |
|  | milliamprid |
| one | {0} mA |
| other | {0} mA |
| electric-ohm | ... |
|  | oomid |
| one | {0} Ω |
| other | {0} Ω |
| electric-volt | ... |
|  | voldid |
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
|  | kJ |
| one | {0} kJ |
| other | {0} kJ |
| energy-joule | ... |
|  | džaulid |
| one | {0} J |
| other | {0} J |
| energy-kilowatt-hour | ... |
|  | kW-tund |
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
|  | jardid |
| one | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | ft |
| one | {0} ft |
| other | {0} ft |
{0}/ft
| length-inch | ... |
|  | tollid |
| one | {0} in |
| other | {0} in |
{0}/in
| length-parsec | ... |
|  | parsekid |
| one | {0} pc |
| other | {0} pc |
| length-light-year | ... |
|  | valgusaastad |
| one | {0} valgusa. |
| other | {0} valgusa. |
| length-astronomical-unit | ... |
|  | aü |
| one | {0} aü |
| other | {0} aü |
| length-furlong | ... |
|  | furlongid |
| one | {0} fur |
| other | {0} fur |
| length-fathom | ... |
|  | süllad |
| one | {0} fm |
| other | {0} fm |
| length-nautical-mile | ... |
|  | nmi |
| one | {0} nmi |
| other | {0} nmi |
| length-mile-scandinavian | ... |
|  | smi |
| one | {0} smi |
| other | {0} smi |
| length-point | ... |
|  | punktid |
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
|  | grammid |
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
|  | lüh t |
| one | {0} lüh t |
| other | {0} lüh t |
| mass-stone | ... |
|  | kivid |
| one | {0} st |
| other | {0} st |
| mass-pound | ... |
|  | naelad |
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
|  | ct |
| one | {0} ct |
| other | {0} ct |
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
|  | vatid |
| one | {0} W |
| other | {0} W |
| power-milliwatt | ... |
|  | mW |
| one | {0} mW |
| other | {0} mW |
| power-horsepower | ... |
|  | hj |
| one | {0} hj |
| other | {0} hj |
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
|  | in Hg |
| one | {0} in Hg |
| other | {0} in Hg |
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
|  | kuupmiilid |
| one | {0} mi³ |
| other | {0} mi³ |
| volume-cubic-yard | ... |
|  | kuupjardid |
| one | {0} yd³ |
| other | {0} yd³ |
| volume-cubic-foot | ... |
|  | ft³ |
| one | {0} ft³ |
| other | {0} ft³ |
| volume-cubic-inch | ... |
|  | kuuptollid |
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
|  | liitrid |
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
|  | mpt |
| one | {0} mpt |
| other | {0} mpt |
| volume-cup-metric | ... |
|  | mcup |
| one | {0} mc |
| other | {0} mc |
| volume-acre-foot | ... |
|  | aakerjalg |
| one | {0} ac ft |
| other | {0} ac ft |
| volume-bushel | ... |
|  | buššelid |
| volume-gallon | ... |
|  | gal |
| one | {0} gal |
| other | {0} gal |
{0}/gal
| volume-gallon-imperial | ... |
|  | Imp. gal |
| one | {0} gal Imp. |
| other | {0} gal Imp. |
{0}/gal Imp.
| volume-quart | ... |
|  | kvart |
| one | {0} qt |
| other | {0} qt |
| volume-pint | ... |
|  | pindid |
| one | {0} pt |
| other | {0} pt |
| volume-cup | ... |
|  | tass |
| one | {0} c |
| other | {0} c |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0} fl oz |
| other | {0} fl oz |
| volume-tablespoon | ... |
|  | spl |
| one | {0} spl |
| other | {0} spl |
| volume-teaspoon | ... |
|  | tl |
| one | {0} tl |
| other | {0} tl |
{0} ip{0} pl{0} ll{0} lp
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | Maa raskuskiirendus |
| one | {0}G |
| other | {0}G |
| acceleration-meter-per-second-squared | ... |
|  | m/s² |
| one | {0} m/s² |
| other | {0} m/s² |
| angle-degree | ... |
| one | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
| one | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
| one | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
| one | {0} km² |
| other | {0} km² |
| area-hectare | ... |
| one | {0} ha |
| other | {0} ha |
| area-square-meter | ... |
| one | {0} m² |
| other | {0} m² |
| area-square-mile | ... |
| one | {0} mi² |
| other | {0} mi² |
| area-acre | ... |
| one | {0} aaker |
| other | {0} aakrit |
| area-square-foot | ... |
| one | {0} ft² |
| other | {0} ft² |
| concentr-karat | ... |
| one | {0} kt |
| other | {0} kt |
| consumption-liter-per-100kilometers | ... |
|  | l/100 km |
| one | {0} l/100km |
| other | {0} l/100km |
| digital-byte | ... |
| one | {0} B |
| other | {0} B |
| duration-year | ... |
|  | a |
| one | {0} a |
| other | {0} a |
| duration-month | ... |
|  | kuud |
| one | {0} k |
| other | {0} k |
| duration-week | ... |
|  | n |
| one | {0} n |
| other | {0} n |
| duration-day | ... |
|  | päev |
| one | {0} p |
| other | {0} p |
| duration-hour | ... |
|  | t |
| one | {0} t |
| other | {0} t |
| duration-minute | ... |
|  | min |
| one | {0} min |
| other | {0} min |
{0}/min
| duration-second | ... |
|  | s |
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
| energy-kilowatt-hour | ... |
|  | kWh |
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
| one | {0} miil |
| other | {0} miili |
| length-yard | ... |
|  | jardid |
| one | {0} jard |
| other | {0} jardi |
| length-foot | ... |
|  | ft |
| one | {0} jalg |
| other | {0} jalga |
{0}/ft
| length-inch | ... |
|  | tollid |
| one | {0} toll |
| other | {0} tolli |
{0}/in
| length-parsec | ... |
|  | parsekid |
| one | {0} pc |
| other | {0} pc |
| length-light-year | ... |
|  | valgusaastad |
| one | {0} valgusa. |
| other | {0} valgusa. |
| length-astronomical-unit | ... |
|  | aü |
| one | {0} aü |
| other | {0} aü |
| length-furlong | ... |
|  | furlongid |
| one | {0} fur |
| other | {0} fur |
| length-fathom | ... |
|  | süllad |
| one | {0} fm |
| other | {0} fm |
| length-nautical-mile | ... |
|  | nmi |
| one | {0} nmi |
| other | {0} nmi |
| length-mile-scandinavian | ... |
|  | smi |
| one | {0} smi |
| other | {0} smi |
| length-point | ... |
|  | pt |
| one | {0} pt |
| other | {0} pt |
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
|  | gramm |
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
|  | lüh t |
| one | {0} lüh t |
| other | {0} lüh t |
| mass-stone | ... |
|  | kivid |
| one | {0} st |
| other | {0} st |
| mass-pound | ... |
|  | naelad |
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
|  | ct |
| one | {0} ct |
| other | {0} ct |
| power-kilowatt | ... |
| one | {0}kW |
| other | {0}kW |
| power-watt | ... |
| one | {0}W |
| other | {0}W |
| power-horsepower | ... |
| one | {0} hj |
| other | {0} hj |
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
|  | ″ Hg |
| one | {0} toll Hg |
| other | {0} tolli Hg |
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
| one | {0} km³ |
| other | {0} km³ |
| volume-cubic-mile | ... |
| one | {0} mi³ |
| other | {0} mi³ |
| volume-liter | ... |
|  | liiter |
| one | {0} l |
| other | {0} l |
{0} E{0} N{0} S{0} Wh:mmh:mm:ssm:ss
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
| end | {0} või {1} |
| 2 | {0} või {1} |
| standard-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} ja {1} |
| 2 | {0} ja {1} |
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
jah:jei:e
## Character sets
| Set | Name |
| --- | ---- |
| all | {0} – kõik |
| category-list | {0}: {1} |
| compatibility | {0} – ühilduvus |
| enclosed | {0} – suletud |
| extended | {0} – laiendatud |
| historic | {0} – ajalooline |
| miscellaneous | {0} – mitmesugust |
| other | {0} – muu |
| scripts | kirjad – {0} |
| onestrokes | {0} kriips |
| otherstrokes | {0} kriipsu |
| activities | tegevus |
| african_scripts | Aafrika kiri |
| american_scripts | Ameerika kiri |
| animal | loom |
| animals_nature | loom või loodus |
| arrows | nool |
| body | keha |
| box_drawing | kastjoonistus |
| braille | Braille |
| building | hoone |
| bullets_stars | täpp või täht |
| consonantal_jamo | konsonandi märk |
| currency_symbols | rahaühiku sümbol |
| dash_connector | kriips või liitja |
| digits | number |
| dingbats | piltmärk |
| divination_symbols | ennustussümbol |
| downwards_arrows | allapoole suunatud nool |
| downwards_upwards_arrows | alla- ja ülespoole suunatud nool |
| east_asian_scripts | Ida-Aasia kiri |
| emoji | emodži |
| european_scripts | Euroopa kiri |
| female | naine |
| flag | lipp |
| flags | lipud |
| food_drink | toit ja jook |
| format | vorming |
| format_whitespace | vorming ja tühimärgid |
| full_width_form_variant | täislaiuses variant |
| geometric_shapes | geomeetriline kujund |
| half_width_form_variant | poollaiuses variant |
| han_characters | hani kirjamärk |
| han_radicals | hani kirja võti |
| hanja | hanja |
| hanzi_simplified | hanzi (lihtsustatud) |
| hanzi_traditional | hanzi (traditsiooniline) |
| heart | süda |
| historic_scripts | ajalooline kiri |
| ideographic_desc_characters | ideograafiline kirjeldusmärk |
| japanese_kana | kana |
| kanbun | kanbun |
| kanji | kanji |
| keycap | klahv |
| leftwards_arrows | vasakule suunatud nool |
| leftwards_rightwards_arrows | vasakule ja paremale suunatud nool |
| letterlike_symbols | tähelaadne sümbol |
| limited_use | piiratud kasutusega |
| male | mees |
| math_symbols | matemaatiline sümbol |
| middle_eastern_scripts | Lähis-Ida kiri |
| miscellaneous | mitmesugust |
| modern_scripts | nüüdisaegne kiri |
| modifier | täiend |
| musical_symbols | muusikaline sümbol |
| nature | loodus |
| nonspacing | sammuta |
| numbers | arvud |
| objects | objekt |
| other | muu |
| paired | paaris |
| person | inimene |
| phonetic_alphabet | foneetiline tähestik |
| pictographs | piktogramm |
| place | koht |
| plant | taim |
| punctuation | kirjavahemärk |
| rightwards_arrows | paremale suunatud nool |
| sign_standard_symbols | märk või sümbol |
| small_form_variant | väikevariandid |
| smiley | smaili |
| smileys_people | smaili või inimene |
| south_asian_scripts | Lõuna-Aasia kiri |
| southeast_asian_scripts | Kagu-Aasia kiri |
| spacing | samm |
| sport | sport |
| symbols | sümbol |
| technical_symbols | tehniline sümbol |
| tone_marks | toonimärk |
| travel | reisimine |
| travel_places | reisimine või koht |
| upwards_arrows | ülespoole suunatud nooled |
| variant_forms | variant |
| vocalic_jamo | vokaali märk |
| weather | ilm |
| western_asian_scripts | Lääne-Aasia kiri |
| whitespace | tühimärk |
