---
layout: default
title: "CLDR Russian (via LDML2markdown)"
---

## CLDR core data for Russian

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[{а\u0301} {е\u0301} {и\u0301} {о\u0301} {у\u0301} {ы\u0301} {э\u0301} {ю\u0301} {я\u0301}]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ы Э Ю Я]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ‚ " “ „ « » ( ) \[ \] \{ \} § @ * / \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | из {0} книги за {0} день |
| few example | из {0} книг за {0} дня |
| many example | из {0} книг за {0} дней |
| other example | из {0} книги за {0} дня |
| Country Data and Default Content | ru_RU |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Cyrl–Latn (make google table or so) |

### Casing

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName | titlecase |
| currencyName_count | lowercase |
| day_format_except_narrow | lowercase |
| day_standalone_except_narrow | lowercase |
| era_abbr | titlecase |
| era_name | titlecase |
| keyValue | lowercase |
| language | lowercase |
| metazone_long | titlecase |
| month_format_except_narrow | titlecase |
| month_standalone_except_narrow | titlecase |
| relative | lowercase |
| script | lowercase |
| territory | titlecase |
| variant | titlecase |
| zone_exemplarCity | titlecase |
| zone_long | titlecase |

### Collation

Alphabetical order,
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers

#### standard

```
				[reorder Cyrl]
				# The root collation already sorts й/Й as a base letter.

```

## CLDR minimal data for Russian

**Needed soon after submitting new locale**.

### Required date-time formats

(44+ needed?)
(Gregorian calendar)

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | янв. |
| month 2 | февр. |
| month 3 | мар. |
| month 4 | апр. |
| month 5 | мая |
| month 6 | июн. |
| month 7 | июл. |
| month 8 | авг. |
| month 9 | сент. |
| month 10 | окт. |
| month 11 | нояб. |
| month 12 | дек. |
| month 1 | Я |
| month 2 | Ф |
| month 3 | М |
| month 4 | А |
| month 5 | М |
| month 6 | И |
| month 7 | И |
| month 8 | А |
| month 9 | С |
| month 10 | О |
| month 11 | Н |
| month 12 | Д |
| month 1 | января |
| month 2 | февраля |
| month 3 | марта |
| month 4 | апреля |
| month 5 | мая |
| month 6 | июня |
| month 7 | июля |
| month 8 | августа |
| month 9 | сентября |
| month 10 | октября |
| month 11 | ноября |
| month 12 | декабря |
| month 1 | янв. |
| month 2 | февр. |
| month 3 | март |
| month 4 | апр. |
| month 5 | май |
| month 6 | июнь |
| month 7 | июль |
| month 8 | авг. |
| month 9 | сент. |
| month 10 | окт. |
| month 11 | нояб. |
| month 12 | дек. |
| month 1 | Я |
| month 2 | Ф |
| month 3 | М |
| month 4 | А |
| month 5 | М |
| month 6 | И |
| month 7 | И |
| month 8 | А |
| month 9 | С |
| month 10 | О |
| month 11 | Н |
| month 12 | Д |
| month 1 | январь |
| month 2 | февраль |
| month 3 | март |
| month 4 | апрель |
| month 5 | май |
| month 6 | июнь |
| month 7 | июль |
| month 8 | август |
| month 9 | сентябрь |
| month 10 | октябрь |
| month 11 | ноябрь |
| month 12 | декабрь |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | воскресенье |
| (week)day mon | понедельник |
| (week)day tue | вторник |
| (week)day wed | среда |
| (week)day thu | четверг |
| (week)day fri | пятница |
| (week)day sat | суббота |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | В |
| (week)day mon | П |
| (week)day tue | В |
| (week)day wed | С |
| (week)day thu | Ч |
| (week)day fri | П |
| (week)day sat | С |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | воскресенье |
| (week)day mon | понедельник |
| (week)day tue | вторник |
| (week)day wed | среда |
| (week)day thu | четверг |
| (week)day fri | пятница |
| (week)day sat | суббота |
| quarter 1 | 1-й кв. |
| quarter 2 | 2-й кв. |
| quarter 3 | 3-й кв. |
| quarter 4 | 4-й кв. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1-й квартал |
| quarter 2 | 2-й квартал |
| quarter 3 | 3-й квартал |
| quarter 4 | 4-й квартал |
| quarter 1 | 1-й кв. |
| quarter 2 | 2-й кв. |
| quarter 3 | 3-й кв. |
| quarter 4 | 4-й кв. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1-й квартал |
| quarter 2 | 2-й квартал |
| quarter 3 | 3-й квартал |
| quarter 4 | 4-й квартал |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | вечера |
| period of day night1 | ночи |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | веч. |
| period of day night1 | ночи |
| period of day midnight | полночь |
| period of day am | AM |
| period of day noon | полдень |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | вечера |
| period of day night1 | ночи |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | веч. |
| period of day night1 | ночь |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | веч. |
| period of day night1 | ночь |
| period of day midnight | полночь |
| period of day am | AM |
| period of day noon | полдень |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | вечер |
| period of day night1 | ночь |
| era | до Рождества Христова |
| era | до нашей эры |
| era | от Рождества Христова |
| era | нашей эры |
| era | до н. э. |
| era | н. э. |
| era | до н.э. |
| era | н.э. |
| date format | `EEEE, d MMMM y 'г'.` |
| date format | `d MMMM y 'г'.` |
| date format | `d MMM y 'г'.` |
| date format | `dd.MM.y` |
| time format | `H:mm:ss zzzz` |
| time format | `H:mm:ss z` |
| time format | `H:mm:ss` |
| time format | `H:mm` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `ccc, h:mm B` |
| date format `EBhms` | `ccc, h:mm:ss B` |
| date format `Ed` | `ccc, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y 'г'. G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d MMM y 'г'. G` |
| date format `GyMMMEd` | `E, d MMM y 'г'. G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `H:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `H:mm:ss` |
| date format `hmsv` | `h:mm:ss a v` |
| date format `Hmsv` | `H:mm:ss v` |
| date format `hmv` | `h:mm a v` |
| date format `Hmv` | `H:mm v` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMdd` | `dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `MM.y` |
| date format `yMd` | `dd.MM.y` |
| date format `yMEd` | `ccc, dd.MM.y 'г'.` |
| date format `yMM` | `MM.y` |
| date format `yMMM` | `LLL y 'г'.` |
| date format `yMMMd` | `d MMM y 'г'.` |
| date format `yMMMEd` | `E, d MMM y 'г'.` |
| date format `yMMMM` | `LLLL y 'г'.` |
| date format `yQQQ` | `QQQ y 'г'.` |
| date format `yQQQQ` | `QQQQ y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM – dd.MMdd.MM – dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `LLL – LLL` |
| interval format `MMMd` | `d–d MMMd MMM – d MMM` |
| interval format `MMMEd` | `E, d MMM – E, d MMME, d MMM – E, d MMM` |
| interval format `MMMM` | `LLLL – LLLL` |
| interval format `y` | `y–y` |
| interval format `yM` | `MM.y – MM.yMM.y – MM.y` |
| interval format `yMd` | `dd.MM.y – dd.MM.ydd.MM.y – dd.MM.ydd.MM.y – dd.MM.y` |
| interval format `yMEd` | `ccc, dd.MM.y – ccc, dd.MM.yccc, dd.MM.y – ccc, dd.MM.yccc, dd.MM.y – ccc, dd.MM.y` |
| interval format `yMMM` | `LLL – LLL y 'г'.LLL y 'г'. – LLL y 'г'.` |
| interval format `yMMMd` | `d–d MMM y 'г'.d MMM – d MMM y 'г'.d MMM y 'г'. – d MMM y 'г'.` |
| interval format `yMMMEd` | `ccc, d – ccc, d MMM y 'г'.ccc, d MMM – ccc, d MMM y 'г'.ccc, d MMM y 'г'. – ccc, d MMM y 'г'.` |
| interval format `yMMMM` | `LLLL – LLLL y 'г'.LLLL y 'г'. – LLLL y 'г'.` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, d MMMM y 'г'. G` |
| date format | `d MMMM y 'г'. G` |
| date format | `d MMM y 'г'. G` |
| date format | `dd.MM.y G` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `ccc, h:mm B` |
| date format `EBhms` | `ccc, h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `ccc, h:mm a` |
| date format `EHm` | `ccc HH:mm` |
| date format `Ehms` | `ccc, h:mm:ss a` |
| date format `EHms` | `ccc HH:mm:ss` |
| date format `Gy` | `y 'г'. G` |
| date format `GyMMM` | `LLL y 'г'. G` |
| date format `GyMMMd` | `d MMM y 'г'. G` |
| date format `GyMMMEd` | `E, d MMM y 'г'. G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y 'г'. G` |
| date format `yyyy` | `y 'г'. G` |
| date format `yyyyM` | `MM.y G` |
| date format `yyyyMd` | `dd.MM.y G` |
| date format `yyyyMEd` | `E, dd.MM.y G` |
| date format `yyyyMMM` | `LLL y 'г'. G` |
| date format `yyyyMMMd` | `d MMM y 'г'. G` |
| date format `yyyyMMMEd` | `E, d MMM y 'г'. G` |
| date format `yyyyMMMM` | `LLLL y 'г'. G` |
| date format `yyyyQQQ` | `QQQ y 'г'. G` |
| date format `yyyyQQQQ` | `QQQQ y 'г'. G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM – dd.MMdd.MM – dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `LLL – LLL` |
| interval format `MMMd` | `d–d MMMd MMM – d MMM` |
| interval format `MMMEd` | `ccc, d MMM – ccc, d MMMccc, d MMM – ccc, d MMM` |
| interval format `MMMM` | `LLLL – LLLL` |
| interval format `y` | `y–y 'гг'. G` |
| interval format `yM` | `MM.y – MM.y GMM.y – MM.y G` |
| interval format `yMd` | `dd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y G` |
| interval format `yMEd` | `ccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y G` |
| interval format `yMMM` | `LLL – LLL y 'г'. GLLL y 'г'. – LLL y 'г'. G` |
| interval format `yMMMd` | `d–d MMM y 'г'. Gd MMM – d MMM y 'г'. Gd MMM y 'г'. – d MMM y 'г'. G` |
| interval format `yMMMEd` | `ccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM y 'г'. – ccc, d MMM y 'г'. G` |
| interval format `yMMMM` | `LLLL – LLLL y 'г'. GLLLL y 'г'. – LLLL y 'г'. G` |

### Important names in language

Language:
| `ru` | русский |

Country or territory:

| `RU` | Россия |

Currency:

|  | российский рубль |
| one | российский рубль |
| few | российских рубля |
| many | российских рублей |
| other | российского рубля |
|  symbol | ₽ |
| narrow symbol | ₽ |

### Datetime patterns

| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `ccc, h:mm B` |
| date format `EBhms` | `ccc, h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `ccc, h:mm a` |
| date format `EHm` | `ccc HH:mm` |
| date format `Ehms` | `ccc, h:mm:ss a` |
| date format `EHms` | `ccc HH:mm:ss` |
| date format `Gy` | `y 'г'. G` |
| date format `GyMMM` | `LLL y 'г'. G` |
| date format `GyMMMd` | `d MMM y 'г'. G` |
| date format `GyMMMEd` | `E, d MMM y 'г'. G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y 'г'. G` |
| date format `yyyy` | `y 'г'. G` |
| date format `yyyyM` | `MM.y G` |
| date format `yyyyMd` | `dd.MM.y G` |
| date format `yyyyMEd` | `E, dd.MM.y G` |
| date format `yyyyMMM` | `LLL y 'г'. G` |
| date format `yyyyMMMd` | `d MMM y 'г'. G` |
| date format `yyyyMMMEd` | `E, d MMM y 'г'. G` |
| date format `yyyyMMMM` | `LLLL y 'г'. G` |
| date format `yyyyQQQ` | `QQQ y 'г'. G` |
| date format `yyyyQQQQ` | `QQQQ y 'г'. G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM – dd.MMdd.MM – dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `LLL – LLL` |
| interval format `MMMd` | `d–d MMMd MMM – d MMM` |
| interval format `MMMEd` | `ccc, d MMM – ccc, d MMMccc, d MMM – ccc, d MMM` |
| interval format `MMMM` | `LLLL – LLLL` |
| interval format `y` | `y–y 'гг'. G` |
| interval format `yM` | `MM.y – MM.y GMM.y – MM.y G` |
| interval format `yMd` | `dd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y G` |
| interval format `yMEd` | `ccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y G` |
| interval format `yMMM` | `LLL – LLL y 'г'. GLLL y 'г'. – LLL y 'г'. G` |
| interval format `yMMMd` | `d–d MMM y 'г'. Gd MMM – d MMM y 'г'. Gd MMM y 'г'. – d MMM y 'г'. G` |
| interval format `yMMMEd` | `ccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM y 'г'. – ccc, d MMM y 'г'. G` |
| interval format `yMMMM` | `LLLL – LLLL y 'г'. GLLLL y 'г'. – LLLL y 'г'. G` |

### Number formats

| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | не число |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| Time at Greenwich | GMT |
| regional | {0} |
| regional | {0}, летнее время |
| regional | {0}, стандартное время |
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
| `calendar` | календарь |
| `cf` | формат валюты |
| `colAlternate` | Игнорировать символы при сортировке |
| `colBackwards` | Обратная сортировка по акценту |
| `colCaseFirst` | Сортировка по верхнему или нижнему регистру |
| `colCaseLevel` | Сортировка с учетом регистра |
| `collation` | порядок сортировки |
| `colNormalization` | Нормализованная сортировка |
| `colNumeric` | Сортировка чисел |
| `colStrength` | Эффективность сортировки |
| `currency` | валюта |
| `hc` | формат времени (12 или 24) |
| `lb` | стиль перевода строки |
| `ms` | система мер |
| `numbers` | цифры |
| `timezone` | Часовой пояс |
| `va` | Вариант региональных настроек |
| `x` | Частное |

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13904 $ru
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
| `aa` | афарский |
| `ab` | абхазский |
| `ace` | ачехский |
| `ach` | ачоли |
| `ada` | адангме |
| `ady` | адыгейский |
| `ae` | авестийский |
| `af` | африкаанс |
| `afh` | африхили |
| `agq` | агем |
| `ain` | айнский |
| `ak` | акан |
| `akk` | аккадский |
| `ale` | алеутский |
| `alt` | южноалтайский |
| `am` | амхарский |
| `an` | арагонский |
| `ang` | староанглийский |
| `anp` | ангика |
| `ar` | арабский |
| `ar_001` | арабский литературный |
| `arc` | арамейский |
| `arn` | мапуче |
| `arp` | арапахо |
| `ars` | арабская — недждийская |
| `arw` | аравакский |
| `as` | ассамский |
| `asa` | асу |
| `ast` | астурийский |
| `av` | аварский |
| `awa` | авадхи |
| `ay` | аймара |
| `az` | азербайджанский |
| `az` | азербайджанский |
| `ba` | башкирский |
| `bal` | белуджский |
| `ban` | балийский |
| `bas` | баса |
| `bax` | бамум |
| `bbj` | гомала |
| `be` | белорусский |
| `bej` | беджа |
| `bem` | бемба |
| `bez` | бена |
| `bfd` | бафут |
| `bg` | болгарский |
| `bgn` | западный белуджский |
| `bho` | бходжпури |
| `bi` | бислама |
| `bik` | бикольский |
| `bin` | бини |
| `bkm` | ком |
| `bla` | сиксика |
| `bm` | бамбара |
| `bn` | бенгальский |
| `bo` | тибетский |
| `br` | бретонский |
| `bra` | брауи |
| `brx` | бодо |
| `bs` | боснийский |
| `bss` | акоосе |
| `bua` | бурятский |
| `bug` | бугийский |
| `bum` | булу |
| `byn` | билин |
| `byv` | медумба |
| `ca` | каталанский |
| `cad` | каддо |
| `car` | кариб |
| `cay` | кайюга |
| `cch` | атсам |
| `ce` | чеченский |
| `ceb` | себуано |
| `cgg` | кига |
| `ch` | чаморро |
| `chb` | чибча |
| `chg` | чагатайский |
| `chk` | чукотский |
| `chm` | марийский |
| `chn` | чинук жаргон |
| `cho` | чоктавский |
| `chp` | чипевьян |
| `chr` | чероки |
| `chy` | шайенский |
| `ckb` | сорани |
| `co` | корсиканский |
| `cop` | коптский |
| `cr` | кри |
| `crh` | крымско-татарский |
| `crs` | сейшельский креольский |
| `cs` | чешский |
| `csb` | кашубский |
| `cu` | церковнославянский |
| `cv` | чувашский |
| `cy` | валлийский |
| `da` | датский |
| `dak` | дакота |
| `dar` | даргинский |
| `dav` | таита |
| `de` | немецкий |
| `de_AT` | австрийский немецкий |
| `de_CH` | литературный швейцарский немецкий |
| `del` | делаварский |
| `den` | слейви |
| `dgr` | догриб |
| `din` | динка |
| `dje` | джерма |
| `doi` | догри |
| `dsb` | нижнелужицкий |
| `dua` | дуала |
| `dum` | средненидерландский |
| `dv` | мальдивский |
| `dyo` | диола-фоньи |
| `dyu` | диула |
| `dz` | дзонг-кэ |
| `dzg` | даза |
| `ebu` | эмбу |
| `ee` | эве |
| `efi` | эфик |
| `egy` | древнеегипетский |
| `eka` | экаджук |
| `el` | греческий |
| `elx` | эламский |
| `en` | английский |
| `en_AU` | австралийский английский |
| `en_CA` | канадский английский |
| `en_GB` | британский английский |
| `en_GB` | британский английский |
| `en_US` | американский английский |
| `en_US` | американский английский |
| `enm` | среднеанглийский |
| `eo` | эсперанто |
| `es` | испанский |
| `es_419` | латиноамериканский испанский |
| `es_ES` | европейский испанский |
| `es_MX` | мексиканский испанский |
| `et` | эстонский |
| `eu` | баскский |
| `ewo` | эвондо |
| `fa` | персидский |
| `fan` | фанг |
| `fat` | фанти |
| `ff` | фулах |
| `fi` | финский |
| `fil` | филиппинский |
| `fj` | фиджи |
| `fo` | фарерский |
| `fon` | фон |
| `fr` | французский |
| `fr_CA` | канадский французский |
| `fr_CH` | швейцарский французский |
| `frc` | каджунский французский |
| `frm` | среднефранцузский |
| `fro` | старофранцузский |
| `frr` | северный фризский |
| `frs` | восточный фризский |
| `fur` | фриульский |
| `fy` | западнофризский |
| `ga` | ирландский |
| `gaa` | га |
| `gag` | гагаузский |
| `gan` | гань |
| `gay` | гайо |
| `gba` | гбая |
| `gd` | гэльский |
| `gez` | геэз |
| `gil` | гильбертский |
| `gl` | галисийский |
| `gmh` | средневерхненемецкий |
| `gn` | гуарани |
| `goh` | древневерхненемецкий |
| `gon` | гонди |
| `gor` | горонтало |
| `got` | готский |
| `grb` | гребо |
| `grc` | древнегреческий |
| `gsw` | швейцарский немецкий |
| `gu` | гуджарати |
| `guz` | гусии |
| `gv` | мэнский |
| `gwi` | гвичин |
| `ha` | хауса |
| `hai` | хайда |
| `hak` | хакка |
| `haw` | гавайский |
| `he` | иврит |
| `hi` | хинди |
| `hil` | хилигайнон |
| `hit` | хеттский |
| `hmn` | хмонг |
| `ho` | хиримоту |
| `hr` | хорватский |
| `hsb` | верхнелужицкий |
| `hsn` | сян |
| `ht` | гаитянский |
| `hu` | венгерский |
| `hup` | хупа |
| `hy` | армянский |
| `hz` | гереро |
| `ia` | интерлингва |
| `iba` | ибанский |
| `ibb` | ибибио |
| `id` | индонезийский |
| `ie` | интерлингве |
| `ig` | игбо |
| `ii` | носу |
| `ik` | инупиак |
| `ilo` | илоко |
| `inh` | ингушский |
| `io` | идо |
| `is` | исландский |
| `it` | итальянский |
| `iu` | инуктитут |
| `ja` | японский |
| `jbo` | ложбан |
| `jgo` | нгомба |
| `jmc` | мачаме |
| `jpr` | еврейско-персидский |
| `jrb` | еврейско-арабский |
| `jv` | яванский |
| `ka` | грузинский |
| `kaa` | каракалпакский |
| `kab` | кабильский |
| `kac` | качинский |
| `kaj` | каджи |
| `kam` | камба |
| `kaw` | кави |
| `kbd` | кабардинский |
| `kbl` | канембу |
| `kcg` | тьяп |
| `kde` | маконде |
| `kea` | кабувердьяну |
| `kfo` | коро |
| `kg` | конго |
| `kha` | кхаси |
| `kho` | хотанский |
| `khq` | койра чиини |
| `ki` | кикуйю |
| `kj` | кунама |
| `kk` | казахский |
| `kkj` | како |
| `kl` | гренландский |
| `kln` | календжин |
| `km` | кхмерский |
| `kmb` | кимбунду |
| `kn` | каннада |
| `ko` | корейский |
| `koi` | коми-пермяцкий |
| `kok` | конкани |
| `kos` | косраенский |
| `kpe` | кпелле |
| `kr` | канури |
| `krc` | карачаево-балкарский |
| `krl` | карельский |
| `kru` | курух |
| `ks` | кашмири |
| `ksb` | шамбала |
| `ksf` | бафия |
| `ksh` | кёльнский |
| `ku` | курдский |
| `kum` | кумыкский |
| `kut` | кутенаи |
| `kv` | коми |
| `kw` | корнский |
| `ky` | киргизский |
| `la` | латинский |
| `lad` | ладино |
| `lag` | ланго |
| `lah` | лахнда |
| `lam` | ламба |
| `lb` | люксембургский |
| `lez` | лезгинский |
| `lg` | ганда |
| `li` | лимбургский |
| `lkt` | лакота |
| `ln` | лингала |
| `lo` | лаосский |
| `lol` | монго |
| `lou` | луизианский креольский |
| `loz` | лози |
| `lrc` | севернолурский |
| `lt` | литовский |
| `lu` | луба-катанга |
| `lua` | луба-лулуа |
| `lui` | луисеньо |
| `lun` | лунда |
| `luo` | луо |
| `lus` | лушей |
| `luy` | лухья |
| `lv` | латышский |
| `mad` | мадурский |
| `maf` | мафа |
| `mag` | магахи |
| `mai` | майтхили |
| `mak` | макассарский |
| `man` | мандинго |
| `mas` | масаи |
| `mde` | маба |
| `mdf` | мокшанский |
| `mdr` | мандарский |
| `men` | менде |
| `mer` | меру |
| `mfe` | маврикийский креольский |
| `mg` | малагасийский |
| `mga` | среднеирландский |
| `mgh` | макуа-меетто |
| `mgo` | мета |
| `mh` | маршалльский |
| `mi` | маори |
| `mic` | микмак |
| `min` | минангкабау |
| `mk` | македонский |
| `ml` | малаялам |
| `mn` | монгольский |
| `mnc` | маньчжурский |
| `mni` | манипурский |
| `moh` | мохаук |
| `mos` | моси |
| `mr` | маратхи |
| `ms` | малайский |
| `mt` | мальтийский |
| `mua` | мунданг |
| `mul` | языки разных семей |
| `mus` | крик |
| `mwl` | мирандский |
| `mwr` | марвари |
| `my` | бирманский |
| `mye` | миене |
| `myv` | эрзянский |
| `mzn` | мазендеранский |
| `na` | науру |
| `nan` | миньнань |
| `nap` | неаполитанский |
| `naq` | нама |
| `nb` | норвежский букмол |
| `nd` | северный ндебеле |
| `nds` | нижнегерманский |
| `nds_NL` | нижнесаксонский |
| `ne` | непальский |
| `new` | неварский |
| `ng` | ндонга |
| `nia` | ниас |
| `niu` | ниуэ |
| `nl` | нидерландский |
| `nl_BE` | фламандский |
| `nmg` | квасио |
| `nn` | нюнорск |
| `nnh` | нгиембунд |
| `no` | норвежский |
| `nog` | ногайский |
| `non` | старонорвежский |
| `nqo` | нко |
| `nr` | южный ндебеле |
| `nso` | северный сото |
| `nus` | нуэр |
| `nv` | навахо |
| `nwc` | классический невари |
| `ny` | ньянджа |
| `nym` | ньямвези |
| `nyn` | ньянколе |
| `nyo` | ньоро |
| `nzi` | нзима |
| `oc` | окситанский |
| `oj` | оджибва |
| `om` | оромо |
| `or` | ория |
| `os` | осетинский |
| `osa` | оседжи |
| `ota` | старотурецкий |
| `pa` | панджаби |
| `pag` | пангасинан |
| `pal` | пехлевийский |
| `pam` | пампанга |
| `pap` | папьяменто |
| `pau` | палау |
| `pcm` | нигерийско-креольский |
| `peo` | староперсидский |
| `phn` | финикийский |
| `pi` | пали |
| `pl` | польский |
| `pon` | понапе |
| `prg` | прусский |
| `pro` | старопровансальский |
| `ps` | пушту |
| `pt` | португальский |
| `pt_BR` | бразильский португальский |
| `pt_PT` | европейский португальский |
| `qu` | кечуа |
| `quc` | киче |
| `raj` | раджастхани |
| `rap` | рапануйский |
| `rar` | раротонга |
| `rm` | романшский |
| `rn` | рунди |
| `ro` | румынский |
| `ro_MD` | молдавский |
| `rof` | ромбо |
| `rom` | цыганский |
| `root` | корневой язык |
| `ru` | русский |
| `rup` | арумынский |
| `rw` | киньяруанда |
| `rwk` | руанда |
| `sa` | санскрит |
| `sad` | сандаве |
| `sah` | саха |
| `sam` | самаритянский арамейский |
| `saq` | самбуру |
| `sas` | сасакский |
| `sat` | сантали |
| `sba` | нгамбайский |
| `sbp` | сангу |
| `sc` | сардинский |
| `scn` | сицилийский |
| `sco` | шотландский |
| `sd` | синдхи |
| `sdh` | южнокурдский |
| `se` | северносаамский |
| `see` | сенека |
| `seh` | сена |
| `sel` | селькупский |
| `ses` | койраборо сенни |
| `sg` | санго |
| `sga` | староирландский |
| `sh` | сербскохорватский |
| `shi` | ташельхит |
| `shn` | шанский |
| `shu` | чадский арабский |
| `si` | сингальский |
| `sid` | сидама |
| `sk` | словацкий |
| `sl` | словенский |
| `sm` | самоанский |
| `sma` | южносаамский |
| `smj` | луле-саамский |
| `smn` | инари-саамский |
| `sms` | колтта-саамский |
| `sn` | шона |
| `snk` | сонинке |
| `so` | сомали |
| `sog` | согдийский |
| `sq` | албанский |
| `sr` | сербский |
| `srn` | сранан-тонго |
| `srr` | серер |
| `ss` | свази |
| `ssy` | сахо |
| `st` | южный сото |
| `su` | сунданский |
| `suk` | сукума |
| `sus` | сусу |
| `sux` | шумерский |
| `sv` | шведский |
| `sw` | суахили |
| `sw_CD` | конголезский суахили |
| `swb` | коморский |
| `syc` | классический сирийский |
| `syr` | сирийский |
| `ta` | тамильский |
| `te` | телугу |
| `tem` | темне |
| `teo` | тесо |
| `ter` | терено |
| `tet` | тетум |
| `tg` | таджикский |
| `th` | тайский |
| `ti` | тигринья |
| `tig` | тигре |
| `tiv` | тиви |
| `tk` | туркменский |
| `tkl` | токелайский |
| `tl` | тагалог |
| `tlh` | клингонский |
| `tli` | тлингит |
| `tmh` | тамашек |
| `tn` | тсвана |
| `to` | тонганский |
| `tog` | тонга |
| `tpi` | ток-писин |
| `tr` | турецкий |
| `tru` | туройо |
| `trv` | седекский |
| `ts` | тсонга |
| `tsi` | цимшиан |
| `tt` | татарский |
| `tum` | тумбука |
| `tvl` | тувалу |
| `tw` | тви |
| `twq` | тасавак |
| `ty` | таитянский |
| `tyv` | тувинский |
| `tzm` | среднеатласский тамазигхтский |
| `udm` | удмуртский |
| `ug` | уйгурский |
| `uga` | угаритский |
| `uk` | украинский |
| `umb` | умбунду |
| `und` | неизвестный язык |
| `ur` | урду |
| `uz` | узбекский |
| `vai` | ваи |
| `ve` | венда |
| `vi` | вьетнамский |
| `vo` | волапюк |
| `vot` | водский |
| `vun` | вунджо |
| `wa` | валлонский |
| `wae` | валлисский |
| `wal` | воламо |
| `war` | варай |
| `was` | вашо |
| `wbp` | вальбири |
| `wo` | волоф |
| `wuu` | ву |
| `xal` | калмыцкий |
| `xh` | коса |
| `xog` | сога |
| `yao` | яо |
| `yap` | яп |
| `yav` | янгбен |
| `ybb` | йемба |
| `yi` | идиш |
| `yo` | йоруба |
| `yue` | кантонский |
| `za` | чжуань |
| `zap` | сапотекский |
| `zbl` | блиссимволика |
| `zen` | зенагский |
| `zgh` | тамазигхтский |
| `zh` | китайский |
| `zh_Hans` | китайский, упрощенное письмо |
| `zh_Hant` | китайский, традиционное письмо |
| `zu` | зулу |
| `zun` | зуньи |
| `zxx` | нет языкового материала |
| `zza` | заза |
### Script names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `Afak` | афака |
| `Arab` | арабица |
| `Arab` | персидско-арабская |
| `Armi` | арамейская |
| `Armn` | армянская |
| `Avst` | авестийская |
| `Bali` | балийская |
| `Bamu` | бамум |
| `Bass` | басса (вах) |
| `Batk` | батакская |
| `Beng` | бенгальская |
| `Blis` | блиссимволика |
| `Bopo` | бопомофо |
| `Brah` | брахми |
| `Brai` | Брайля |
| `Bugi` | бугинизийская |
| `Buhd` | бухид |
| `Cakm` | чакмийская |
| `Cans` | канадское слоговое письмо |
| `Cari` | карийская |
| `Cham` | чамская |
| `Cher` | чероки |
| `Cirt` | кирт |
| `Copt` | коптская |
| `Cprt` | кипрская |
| `Cyrl` | кириллица |
| `Cyrs` | старославянская |
| `Deva` | деванагари |
| `Dsrt` | дезерет |
| `Dupl` | дуплоянская скоропись |
| `Egyd` | египетская демотическая |
| `Egyh` | египетская иератическая |
| `Egyp` | египетская иероглифическая |
| `Ethi` | эфиопская |
| `Geok` | грузинская хуцури |
| `Geor` | грузинская |
| `Glag` | глаголица |
| `Goth` | готская |
| `Gran` | грантха |
| `Grek` | греческая |
| `Gujr` | гуджарати |
| `Guru` | гурмукхи |
| `Hanb` | ханьб |
| `Hang` | хангыль |
| `Hani` | китайская |
| `Hano` | хануну |
| `Hans` | упрощенная китайская |
| `Hans` | упрощенная китайская |
| `Hant` | традиционная китайская |
| `Hant` | традиционная китайская |
| `Hebr` | еврейская |
| `Hira` | хирагана |
| `Hluw` | лувийские иероглифы |
| `Hmng` | пахау хмонг |
| `Hrkt` | катакана или хирагана |
| `Hung` | старовенгерская |
| `Inds` | хараппская (письменность долины Инда) |
| `Ital` | староитальянская |
| `Jamo` | джамо |
| `Java` | яванская |
| `Jpan` | японская |
| `Jurc` | чжурчжэньская |
| `Kali` | кайа |
| `Kana` | катакана |
| `Khar` | кхароштхи |
| `Khmr` | кхмерская |
| `Khoj` | ходжики |
| `Knda` | каннада |
| `Kore` | корейская |
| `Kpel` | кпелле |
| `Kthi` | кайтхи |
| `Lana` | ланна |
| `Laoo` | лаосская |
| `Latf` | латинская фрактура |
| `Latg` | гэльская латинская |
| `Latn` | латиница |
| `Lepc` | лепха |
| `Limb` | лимбу |
| `Lina` | линейное письмо А |
| `Linb` | линейное письмо Б |
| `Lisu` | лису |
| `Loma` | лома |
| `Lyci` | лициан |
| `Lydi` | лидийская |
| `Mand` | мандейская |
| `Mani` | манихейская |
| `Maya` | майя |
| `Mend` | менде |
| `Merc` | мероитская курсивная |
| `Mero` | мероитская |
| `Mlym` | малаялам |
| `Mong` | монгольская |
| `Moon` | азбука муна |
| `Mroo` | мро |
| `Mtei` | манипури |
| `Mymr` | мьянманская |
| `Narb` | северноаравийское |
| `Nbat` | набатейская |
| `Nkgb` | наси геба |
| `Nkoo` | нко |
| `Nshu` | нюй-шу |
| `Ogam` | огамическая |
| `Olck` | ол чики |
| `Orkh` | орхоно-енисейская |
| `Orya` | ория |
| `Osma` | османская |
| `Palm` | пальмиры |
| `Perm` | древнепермская |
| `Phag` | пагспа |
| `Phli` | пехлевийская |
| `Phlp` | пахлави псалтирная |
| `Phlv` | пахлави книжная |
| `Phnx` | финикийская |
| `Plrd` | поллардовская фонетика |
| `Prti` | парфянская |
| `Rjng` | реджангская |
| `Roro` | ронго-ронго |
| `Runr` | руническая |
| `Samr` | самаритянская |
| `Sara` | сарати |
| `Sarb` | староюжноарабская |
| `Saur` | саураштра |
| `Sgnw` | язык знаков |
| `Shaw` | алфавит Шоу |
| `Shrd` | шарада |
| `Sind` | кхудавади |
| `Sinh` | сингальская |
| `Sora` | сора-сонпенг |
| `Sund` | сунданская |
| `Sylo` | силоти нагри |
| `Syrc` | сирийская |
| `Syre` | сирийская эстрангело |
| `Syrj` | западносирийская |
| `Syrn` | восточно-сирийская |
| `Tagb` | тагбанва |
| `Takr` | такри |
| `Tale` | тайский ле |
| `Talu` | новый тайский ле |
| `Taml` | тамильская |
| `Tang` | тангутское меня |
| `Tavt` | тай-вьет |
| `Telu` | телугу |
| `Teng` | тенгварская |
| `Tfng` | древнеливийская |
| `Tglg` | тагалог |
| `Thaa` | тана |
| `Thai` | тайская |
| `Tibt` | тибетская |
| `Tirh` | тирхута |
| `Ugar` | угаритская |
| `Vaii` | вайская |
| `Visp` | видимая речь |
| `Wara` | варанг-кшити |
| `Wole` | волеаи |
| `Xpeo` | староперсидская |
| `Xsux` | шумеро-аккадская клинопись |
| `Yiii` | и |
| `Zinh` | унаследованная |
| `Zmth` | математические обозначения |
| `Zsye` | эмодзи |
| `Zsym` | символы |
| `Zxxx` | нет письменности |
| `Zyyy` | общепринятая |
| `Zzzz` | неизвестная письменность |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `001` | весь мир |
| `002` | Африка |
| `003` | Северная Америка |
| `005` | Южная Америка |
| `009` | Океания |
| `011` | Западная Африка |
| `013` | Центральная Америка |
| `014` | Восточная Африка |
| `015` | Северная Африка |
| `017` | Центральная Африка |
| `018` | Южная Африка |
| `019` | Америка |
| `021` | Североамериканский регион |
| `029` | Карибы |
| `030` | Восточная Азия |
| `034` | Южная Азия |
| `035` | Юго-Восточная Азия |
| `039` | Южная Европа |
| `053` | Австралазия |
| `054` | Меланезия |
| `057` | Микронезия |
| `061` | Полинезия |
| `142` | Азия |
| `143` | Центральная Азия |
| `145` | Западная Азия |
| `150` | Европа |
| `151` | Восточная Европа |
| `154` | Северная Европа |
| `155` | Западная Европа |
| `202` | Африка к югу от Сахары |
| `419` | Латинская Америка |
| `AC` | о-в Вознесения |
| `AD` | Андорра |
| `AE` | ОАЭ |
| `AF` | Афганистан |
| `AG` | Антигуа и Барбуда |
| `AI` | Ангилья |
| `AL` | Албания |
| `AM` | Армения |
| `AO` | Ангола |
| `AQ` | Антарктида |
| `AR` | Аргентина |
| `AS` | Американское Самоа |
| `AT` | Австрия |
| `AU` | Австралия |
| `AW` | Аруба |
| `AX` | Аландские о-ва |
| `AZ` | Азербайджан |
| `BA` | Босния и Герцеговина |
| `BB` | Барбадос |
| `BD` | Бангладеш |
| `BE` | Бельгия |
| `BF` | Буркина-Фасо |
| `BG` | Болгария |
| `BH` | Бахрейн |
| `BI` | Бурунди |
| `BJ` | Бенин |
| `BL` | Сен-Бартелеми |
| `BM` | Бермудские о-ва |
| `BN` | Бруней-Даруссалам |
| `BO` | Боливия |
| `BQ` | Бонэйр, Синт-Эстатиус и Саба |
| `BR` | Бразилия |
| `BS` | Багамы |
| `BT` | Бутан |
| `BV` | о-в Буве |
| `BW` | Ботсвана |
| `BY` | Беларусь |
| `BZ` | Белиз |
| `CA` | Канада |
| `CC` | Кокосовые о-ва |
| `CD` | Конго - Киншаса |
| `CD` | Конго (ДРК) |
| `CF` | Центрально-Африканская Республика |
| `CG` | Конго - Браззавиль |
| `CG` | Республика Конго |
| `CH` | Швейцария |
| `CI` | Кот-д’Ивуар |
| `CK` | Острова Кука |
| `CL` | Чили |
| `CM` | Камерун |
| `CN` | Китай |
| `CO` | Колумбия |
| `CP` | о-в Клиппертон |
| `CR` | Коста-Рика |
| `CU` | Куба |
| `CV` | Кабо-Верде |
| `CW` | Кюрасао |
| `CX` | о-в Рождества |
| `CY` | Кипр |
| `CZ` | Чехия |
| `DE` | Германия |
| `DG` | Диего-Гарсия |
| `DJ` | Джибути |
| `DK` | Дания |
| `DM` | Доминика |
| `DO` | Доминиканская Республика |
| `DZ` | Алжир |
| `EA` | Сеута и Мелилья |
| `EC` | Эквадор |
| `EE` | Эстония |
| `EG` | Египет |
| `EH` | Западная Сахара |
| `ER` | Эритрея |
| `ES` | Испания |
| `ET` | Эфиопия |
| `EU` | Европейский союз |
| `EZ` | еврозона |
| `FI` | Финляндия |
| `FJ` | Фиджи |
| `FK` | Фолклендские о-ва |
| `FK` | Фолклендские (Мальвинские) о-ва |
| `FM` | Федеративные Штаты Микронезии |
| `FO` | Фарерские о-ва |
| `FR` | Франция |
| `GA` | Габон |
| `GB` | Великобритания |
| `GB` | Британия |
| `GD` | Гренада |
| `GE` | Грузия |
| `GF` | Французская Гвиана |
| `GG` | Гернси |
| `GH` | Гана |
| `GI` | Гибралтар |
| `GL` | Гренландия |
| `GM` | Гамбия |
| `GN` | Гвинея |
| `GP` | Гваделупа |
| `GQ` | Экваториальная Гвинея |
| `GR` | Греция |
| `GS` | Южная Георгия и Южные Сандвичевы о-ва |
| `GT` | Гватемала |
| `GU` | Гуам |
| `GW` | Гвинея-Бисау |
| `GY` | Гайана |
| `HK` | Гонконг (САР) |
| `HK` | Гонконг |
| `HM` | о-ва Херд и Макдональд |
| `HN` | Гондурас |
| `HR` | Хорватия |
| `HT` | Гаити |
| `HU` | Венгрия |
| `IC` | Канарские о-ва |
| `ID` | Индонезия |
| `IE` | Ирландия |
| `IL` | Израиль |
| `IM` | о-в Мэн |
| `IN` | Индия |
| `IO` | Британская территория в Индийском океане |
| `IQ` | Ирак |
| `IR` | Иран |
| `IS` | Исландия |
| `IT` | Италия |
| `JE` | Джерси |
| `JM` | Ямайка |
| `JO` | Иордания |
| `JP` | Япония |
| `KE` | Кения |
| `KG` | Киргизия |
| `KH` | Камбоджа |
| `KI` | Кирибати |
| `KM` | Коморы |
| `KN` | Сент-Китс и Невис |
| `KP` | КНДР |
| `KR` | Республика Корея |
| `KW` | Кувейт |
| `KY` | Каймановы о-ва |
| `KZ` | Казахстан |
| `LA` | Лаос |
| `LB` | Ливан |
| `LC` | Сент-Люсия |
| `LI` | Лихтенштейн |
| `LK` | Шри-Ланка |
| `LR` | Либерия |
| `LS` | Лесото |
| `LT` | Литва |
| `LU` | Люксембург |
| `LV` | Латвия |
| `LY` | Ливия |
| `MA` | Марокко |
| `MC` | Монако |
| `MD` | Молдова |
| `ME` | Черногория |
| `MF` | Сен-Мартен |
| `MG` | Мадагаскар |
| `MH` | Маршалловы Острова |
| `MK` | Македония |
| `MK` | Македония (БЮРМ) |
| `ML` | Мали |
| `MM` | Мьянма (Бирма) |
| `MN` | Монголия |
| `MO` | Макао (САР) |
| `MO` | Макао |
| `MP` | Северные Марианские о-ва |
| `MQ` | Мартиника |
| `MR` | Мавритания |
| `MS` | Монтсеррат |
| `MT` | Мальта |
| `MU` | Маврикий |
| `MV` | Мальдивы |
| `MW` | Малави |
| `MX` | Мексика |
| `MY` | Малайзия |
| `MZ` | Мозамбик |
| `NA` | Намибия |
| `NC` | Новая Каледония |
| `NE` | Нигер |
| `NF` | о-в Норфолк |
| `NG` | Нигерия |
| `NI` | Никарагуа |
| `NL` | Нидерланды |
| `NO` | Норвегия |
| `NP` | Непал |
| `NR` | Науру |
| `NU` | Ниуэ |
| `NZ` | Новая Зеландия |
| `OM` | Оман |
| `PA` | Панама |
| `PE` | Перу |
| `PF` | Французская Полинезия |
| `PG` | Папуа — Новая Гвинея |
| `PH` | Филиппины |
| `PK` | Пакистан |
| `PL` | Польша |
| `PM` | Сен-Пьер и Микелон |
| `PN` | о-ва Питкэрн |
| `PR` | Пуэрто-Рико |
| `PS` | Палестинские территории |
| `PS` | Палестина |
| `PT` | Португалия |
| `PW` | Палау |
| `PY` | Парагвай |
| `QA` | Катар |
| `QO` | Внешняя Океания |
| `RE` | Реюньон |
| `RO` | Румыния |
| `RS` | Сербия |
| `RU` | Россия |
| `RW` | Руанда |
| `SA` | Саудовская Аравия |
| `SB` | Соломоновы Острова |
| `SC` | Сейшельские Острова |
| `SD` | Судан |
| `SE` | Швеция |
| `SG` | Сингапур |
| `SH` | о-в Св. Елены |
| `SI` | Словения |
| `SJ` | Шпицберген и Ян-Майен |
| `SK` | Словакия |
| `SL` | Сьерра-Леоне |
| `SM` | Сан-Марино |
| `SN` | Сенегал |
| `SO` | Сомали |
| `SR` | Суринам |
| `SS` | Южный Судан |
| `ST` | Сан-Томе и Принсипи |
| `SV` | Сальвадор |
| `SX` | Синт-Мартен |
| `SY` | Сирия |
| `SZ` | Свазиленд |
| `TA` | Тристан-да-Кунья |
| `TC` | о-ва Тёркс и Кайкос |
| `TD` | Чад |
| `TF` | Французские Южные территории |
| `TG` | Того |
| `TH` | Таиланд |
| `TJ` | Таджикистан |
| `TK` | Токелау |
| `TL` | Восточный Тимор |
| `TL` | Тимор-Лесте |
| `TM` | Туркменистан |
| `TN` | Тунис |
| `TO` | Тонга |
| `TR` | Турция |
| `TT` | Тринидад и Тобаго |
| `TV` | Тувалу |
| `TW` | Тайвань |
| `TZ` | Танзания |
| `UA` | Украина |
| `UG` | Уганда |
| `UM` | Внешние малые о-ва (США) |
| `UN` | Организация Объединенных Наций |
| `UN` | ООН |
| `US` | Соединенные Штаты |
| `US` | США |
| `UY` | Уругвай |
| `UZ` | Узбекистан |
| `VA` | Ватикан |
| `VC` | Сент-Винсент и Гренадины |
| `VE` | Венесуэла |
| `VG` | Виргинские о-ва (Британские) |
| `VI` | Виргинские о-ва (США) |
| `VN` | Вьетнам |
| `VU` | Вануату |
| `WF` | Уоллис и Футуна |
| `WS` | Самоа |
| `XK` | Косово |
| `YE` | Йемен |
| `YT` | Майотта |
| `ZA` | Южно-Африканская Республика |
| `ZM` | Замбия |
| `ZW` | Зимбабве |
| `ZZ` | неизвестный регион |
### Locale variant names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `1901` | Традиционная немецкая орфография |
| `1994` | Стандартизированная резьянская орфография |
| `1996` | Правила немецкой орфографии установленные с 1996 года |
| `1606NICT` | Поздне-средневековый французский до 1606 г. |
| `1694ACAD` | Французский раннего нового времени |
| `1959ACAD` | Академическая |
| `AREVELA` | Восточно-армянский |
| `AREVMDA` | Западно-армянский |
| `BAKU1926` | Унифицированный тюрско-латинский алфавит |
| `BISKE` | Диалект Сан-Гиоргио/Била |
| `BOONT` | Бунтлинг |
| `FONIPA` | Международный фонетический алфавит |
| `FONUPA` | Фонетический алфавит уральских языков |
| `KKCOR` | Общая офография |
| `LIPAW` | Липовецкий диалект резьянского языка |
| `MONOTON` | Монотонный |
| `NEDIS` | Надижский диалект |
| `NJIVA` | Гнива-нживский диалект |
| `OSOJS` | Осеакко-осоянский диалект |
| `PINYIN` | Пиньинь |
| `POLYTON` | Многотональный |
| `POSIX` | Компьютерный |
| `REVISED` | Пересмотренная орфография |
| `ROZAJ` | Резьянский |
| `SAAHO` | Сахо |
| `SCOTLAND` | Англо-шотландский |
| `SCOUSE` | Ливерпульский |
| `SOLBA` | Столвицко-солбицкий диалект |
| `TARASK` | Тарашкевица |
| `UCCOR` | Объединенная орфография |
| `UCRCOR` | Объединенная пересмотренная орфография |
| `VALENCIA` | Валенсийский |
| `WADEGILE` | Система Уэйда – Джайлза |
#### Keys (system names)
| key | Name |
| -------- | ---- |
| `calendar` | календарь |
| `cf` | формат валюты |
| `colAlternate` | Игнорировать символы при сортировке |
| `colBackwards` | Обратная сортировка по акценту |
| `colCaseFirst` | Сортировка по верхнему или нижнему регистру |
| `colCaseLevel` | Сортировка с учетом регистра |
| `collation` | порядок сортировки |
| `colNormalization` | Нормализованная сортировка |
| `colNumeric` | Сортировка чисел |
| `colStrength` | Эффективность сортировки |
| `currency` | валюта |
| `hc` | формат времени (12 или 24) |
| `lb` | стиль перевода строки |
| `ms` | система мер |
| `numbers` | цифры |
| `timezone` | Часовой пояс |
| `va` | Вариант региональных настроек |
| `x` | Частное |
### Types (of systems)
| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | буддийский календарь |
| `chinesecalendar` | китайский календарь |
| `copticcalendar` | Коптский календарь |
| `dangicalendar` | календарь данги |
| `ethiopiccalendar` | эфиопский календарь |
| `ethiopic-amete-alemcalendar` | Эфиопский календарь "Амете Алем" |
| `gregoriancalendar` | григорианский календарь |
| `hebrewcalendar` | еврейский календарь |
| `indiancalendar` | Национальный календарь Индии |
| `islamiccalendar` | исламский календарь |
| `islamic-civilcalendar` | Исламский гражданский календарь |
| `islamic-rgsacalendar` | исламский календарь (Саудовская Аравия) |
| `islamic-tblacalendar` | исламский календарь (табличный, астрономическая эпоха) |
| `islamic-umalquracalendar` | исламский календарь (Умм аль-Кура) |
| `iso8601calendar` | календарь ISO-8601 |
| `japanesecalendar` | японский календарь |
| `persiancalendar` | персидский календарь |
| `roccalendar` | календарь Миньго |
| `accountcf` | финансовый формат |
| `standardcf` | стандартный формат |
| `non-ignorablecolAlternate` | Сортировка символов |
| `shiftedcolAlternate` | Сортировка без учета символов |
| `nocolBackwards` | Сортировка по акцентам в обычном порядке |
| `yescolBackwards` | Сортировка по акцентам в обратном порядке |
| `lowercolCaseFirst` | Приоритетная сортировка слов в нижнем регистре |
| `nocolCaseFirst` | Сортировка по стандартным правилам |
| `uppercolCaseFirst` | Приоритетная сортировка слов в верхнем регистре |
| `nocolCaseLevel` | Сортировка вне зависимости от регистра |
| `yescolCaseLevel` | Сортировка с учетом регистра |
| `big5hancollation` | Сортировка традиционного китайского языка – Big5 |
| `compatcollation` | совместимый порядок сортировки |
| `dictionarycollation` | словарный порядок сортировки |
| `ducetcollation` | cтандартная сортировка Unicode |
| `emojicollation` | эмодзи |
| `eorcollation` | европейские правила сортировки |
| `gb2312hancollation` | упрощенный китайский - GB2312 |
| `phonebookcollation` | порядок телефонной книги |
| `phoneticcollation` | Фонетический порядок сортировки |
| `pinyincollation` | пиньинь |
| `reformedcollation` | реформированный порядок сортировки |
| `searchcollation` | поиск |
| `searchjlcollation` | Поиск по первой согласной хангыль |
| `standardcollation` | стандартная сортировка |
| `strokecollation` | по чертам |
| `traditionalcollation` | традиционный порядок |
| `unihancollation` | сортировка по ключам, затем по чертам |
| `zhuyincollation` | чжуинь |
| `nocolNormalization` | Сортировка без нормализации |
| `yescolNormalization` | Сортировка нормализованных символов Unicode |
| `nocolNumeric` | Отдельная сортировка числовых значений |
| `yescolNumeric` | Сортировка численных значений |
| `identicalcolStrength` | Полная сортировка |
| `primarycolStrength` | Сортировка только по символам, обозначающим разрядность |
| `quaternarycolStrength` | Сортировка по акцентам/регистрам/длине строки/кане |
| `secondarycolStrength` | Сортировка по акцентам |
| `tertiarycolStrength` | Сортировка по акцентам/регистру/длине строки |
| `fwidthd0` | полноширинные символы |
| `hwidthd0` | полуширинные символы |
| `npinyind0` | Числовая |
| `h11hc` | 12-часовой формат времени (0-11) |
| `h12hc` | 12-часовой формат времени (1-12) |
| `h23hc` | 24-часовой формат времени (0-23) |
| `h24hc` | 24-часовой формат времени (1-24) |
| `looselb` | мягкий перевод строки |
| `normallb` | обычный перевод строки |
| `strictlb` | жесткий перевод строки |
| `bgnm0` | система транслитерации BGN |
| `ungegnm0` | система транслитерации ООН |
| `metricms` | метрическая система |
| `uksystemms` | британская система мер |
| `ussystemms` | американская система мер |
| `arabnumbers` | арабско-индийские цифры |
| `arabextnumbers` | расширенная система арабско-индийских цифр |
| `armnnumbers` | армянские цифры |
| `armnlownumbers` | армянские цифры в нижнем регистре |
| `balinumbers` | балийские цифры |
| `bengnumbers` | бенгальские цифры |
| `brahnumbers` | цифры брахми |
| `cakmnumbers` | цифры чакма |
| `chamnumbers` | чамские цифры |
| `devanumbers` | цифры деванагари |
| `ethinumbers` | эфиопские цифры |
| `financenumbers` | Символы обозначения финансовых показателей |
| `fullwidenumbers` | полноширинные цифры |
| `geornumbers` | грузинские цифры |
| `greknumbers` | греческие цифры |
| `greklownumbers` | греческие цифры в нижнем регистре |
| `gujrnumbers` | цифры гуджарати |
| `gurunumbers` | цифры гурмукхи |
| `hanidecnumbers` | китайские десятичные цифры |
| `hansnumbers` | китайские упрощенные цифры |
| `hansfinnumbers` | китайские упрощенные цифры (финансы) |
| `hantnumbers` | китайские традиционные цифры |
| `hantfinnumbers` | китайские традиционные цифры (финансы) |
| `hebrnumbers` | цифры на иврите |
| `javanumbers` | яванские цифры |
| `jpannumbers` | японские цифры |
| `jpanfinnumbers` | японские цифры (финансы) |
| `kalinumbers` | цифры кайя ли |
| `khmrnumbers` | кхмерские цифры |
| `kndanumbers` | цифры каннада |
| `lananumbers` | цифры тай там хора |
| `lanathamnumbers` | цифры тай там там |
| `laoonumbers` | лаосские цифры |
| `latnnumbers` | современные арабские цифры |
| `lepcnumbers` | цифры лепча |
| `limbnumbers` | цифры лимбу |
| `mlymnumbers` | цифры малаялам |
| `mongnumbers` | Монгольские цифры |
| `mteinumbers` | цифры манипури |
| `mymrnumbers` | бирманские цифры |
| `mymrshannumbers` | бирманские шанские цифры |
| `nativenumbers` | Обозначения цифр коренного населения |
| `nkoonumbers` | цифры нко |
| `olcknumbers` | цифры ол-чики |
| `oryanumbers` | цифры ория |
| `osmanumbers` | цифры османья |
| `romannumbers` | римские цифры |
| `romanlownumbers` | римские цифры в нижнем регистре |
| `saurnumbers` | цифры саураштра |
| `shrdnumbers` | цифры шарада |
| `soranumbers` | цифры сора-сомпенг |
| `sundnumbers` | суданские цифры |
| `takrnumbers` | цифры такри |
| `talunumbers` | цифры новой тай-лю |
| `tamlnumbers` | тамильские традиционные цифры |
| `tamldecnumbers` | тамильские цифры |
| `telunumbers` | цифры телугу |
| `thainumbers` | тайские цифры |
| `tibtnumbers` | тибетские цифры |
| `traditionalnumbers` | Традиционная система нумерации |
| `vaiinumbers` | Цифры языка вай |
| `metric` | Метрическая |
| `UK` | Английская |
| `US` | Англо-американская |
### Code patterns
Язык: {0}Письменность: {0}Регион: {0}
### Context transforms
```
titlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstwordtitlecase-firstword
```
### Character processing for computer systems
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[{а\u0301} {е\u0301} {и\u0301} {о\u0301} {у\u0301} {ы\u0301} {э\u0301} {ю\u0301} {я\u0301}]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ы Э Ю Я]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ‚ " “ „ « » ( ) \[ \] \{ \} § @ * / \& #]` |
final ellipsis: `{0}…`
initial ellipsis: `…{0}`
medial ellipsis: `{0}…{1}`
word-final ellipsis: `{0} …`
word-initial ellipsis: `… {0}`
word-medial ellipsis: `{0} … {1}`
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
Quotation start character: «
Quotation end character: »
Secondary yquotation start character: „
Secondary quotation end character: “
## Calendar data
#### buddhist calendar
| ID-stuff | values |
| -------- | ------ |
| era | буддийская эра |
| era | BE |
| era | бэ |
#### chinese calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| date format | `EEEE, d MMMM U` |
| date format | `d MMMM U` |
| date format | `dd.MM U` |
| date format | `dd.MM.y` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E, d` |
| date format `Gy` | `U` |
| date format `GyMMM` | `LLL U` |
| date format `GyMMMd` | `d MMM U` |
| date format `GyMMMEd` | `E, d MMM U` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `H:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `H:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `U` |
| date format `yyyy` | `U` |
| date format `yyyyM` | `MM.y` |
| date format `yyyyMd` | `dd.MM.y` |
| date format `yyyyMEd` | `E, dd.MM.y` |
| date format `yyyyMMM` | `LLL U` |
| date format `yyyyMMMd` | `d MMM U` |
| date format `yyyyMMMEd` | `E, d MMM U` |
| date format `yyyyMMMM` | `LLLL U` |
| date format `yyyyQQQ` | `QQQ U` |
| date format `yyyyQQQQ` | `QQQQ U` |
#### coptic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | тот |
| month 2 | бабэ |
| month 3 | хатур |
| month 4 | кихак |
| month 5 | тубэ |
| month 6 | амшир |
| month 7 | барамхат |
| month 8 | бармуда |
| month 9 | башнас |
| month 10 | бауна |
| month 11 | абиб |
| month 12 | мисра |
| month 13 | наси |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | тот |
| month 2 | бабэ |
| month 3 | хатур |
| month 4 | кихак |
| month 5 | тубэ |
| month 6 | амшир |
| month 7 | барамхат |
| month 8 | бармуда |
| month 9 | башнас |
| month 10 | бауна |
| month 11 | абиб |
| month 12 | мисра |
| month 13 | наси |
| month 1 | тот |
| month 2 | бабэ |
| month 3 | хатур |
| month 4 | кихак |
| month 5 | тубэ |
| month 6 | амшир |
| month 7 | барамхат |
| month 8 | бармуда |
| month 9 | башнас |
| month 10 | бауна |
| month 11 | абиб |
| month 12 | мисра |
| month 13 | наси |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | тот |
| month 2 | бабэ |
| month 3 | хатур |
| month 4 | кихак |
| month 5 | тубэ |
| month 6 | амшир |
| month 7 | барамхат |
| month 8 | бармуда |
| month 9 | башнас |
| month 10 | бауна |
| month 11 | абиб |
| month 12 | мисра |
| month 13 | наси |
| era | до Диоклетиана |
| era | от Диоклетиана |
| era | до Диокл. |
| era | от Диокл. |
| era | до Диокл. |
| era | от Диокл. |
#### ethiopic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | мескерем |
| month 2 | текемт |
| month 3 | хедар |
| month 4 | тахсас |
| month 5 | тер |
| month 6 | якатит |
| month 7 | магабит |
| month 8 | миазия |
| month 9 | генбот |
| month 10 | сэнэ |
| month 11 | хамлэ |
| month 12 | нахасэ |
| month 13 | эпагомен |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | мескерем |
| month 2 | текемт |
| month 3 | хедар |
| month 4 | тахсас |
| month 5 | тер |
| month 6 | якатит |
| month 7 | магабит |
| month 8 | миазия |
| month 9 | генбот |
| month 10 | сэнэ |
| month 11 | хамлэ |
| month 12 | нахасэ |
| month 13 | эпагомен |
| month 1 | мескерем |
| month 2 | текемт |
| month 3 | хедар |
| month 4 | тахсас |
| month 5 | тер |
| month 6 | якатит |
| month 7 | магабит |
| month 8 | миазия |
| month 9 | генбот |
| month 10 | сэнэ |
| month 11 | хамлэ |
| month 12 | нахасэ |
| month 13 | эпагомен |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | мескерем |
| month 2 | текемт |
| month 3 | хедар |
| month 4 | тахсас |
| month 5 | тер |
| month 6 | якатит |
| month 7 | магабит |
| month 8 | миазия |
| month 9 | генбот |
| month 10 | сэнэ |
| month 11 | хамлэ |
| month 12 | нахасэ |
| month 13 | эпагомен |
| era | до воплощения Христа |
| era | от воплощения Христа |
| era | до Христа |
| era | от Христа |
| era | до Христа |
| era | от Христа |
#### generic calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `EEEE, d MMMM y 'г'. G` |
| date format | `d MMMM y 'г'. G` |
| date format | `d MMM y 'г'. G` |
| date format | `dd.MM.y G` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `ccc, h:mm B` |
| date format `EBhms` | `ccc, h:mm:ss B` |
| date format `Ed` | `E, d` |
| date format `Ehm` | `ccc, h:mm a` |
| date format `EHm` | `ccc HH:mm` |
| date format `Ehms` | `ccc, h:mm:ss a` |
| date format `EHms` | `ccc HH:mm:ss` |
| date format `Gy` | `y 'г'. G` |
| date format `GyMMM` | `LLL y 'г'. G` |
| date format `GyMMMd` | `d MMM y 'г'. G` |
| date format `GyMMMEd` | `E, d MMM y 'г'. G` |
| date format `h` | `h a` |
| date format `H` | `HH` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `HH:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `HH:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y 'г'. G` |
| date format `yyyy` | `y 'г'. G` |
| date format `yyyyM` | `MM.y G` |
| date format `yyyyMd` | `dd.MM.y G` |
| date format `yyyyMEd` | `E, dd.MM.y G` |
| date format `yyyyMMM` | `LLL y 'г'. G` |
| date format `yyyyMMMd` | `d MMM y 'г'. G` |
| date format `yyyyMMMEd` | `E, d MMM y 'г'. G` |
| date format `yyyyMMMM` | `LLLL y 'г'. G` |
| date format `yyyyQQQ` | `QQQ y 'г'. G` |
| date format `yyyyQQQQ` | `QQQQ y 'г'. G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM – dd.MMdd.MM – dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `LLL – LLL` |
| interval format `MMMd` | `d–d MMMd MMM – d MMM` |
| interval format `MMMEd` | `ccc, d MMM – ccc, d MMMccc, d MMM – ccc, d MMM` |
| interval format `MMMM` | `LLLL – LLLL` |
| interval format `y` | `y–y 'гг'. G` |
| interval format `yM` | `MM.y – MM.y GMM.y – MM.y G` |
| interval format `yMd` | `dd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y Gdd.MM.y – dd.MM.y G` |
| interval format `yMEd` | `ccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y Gccc, dd.MM.y – ccc, dd.MM.y G` |
| interval format `yMMM` | `LLL – LLL y 'г'. GLLL y 'г'. – LLL y 'г'. G` |
| interval format `yMMMd` | `d–d MMM y 'г'. Gd MMM – d MMM y 'г'. Gd MMM y 'г'. – d MMM y 'г'. G` |
| interval format `yMMMEd` | `ccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM – ccc, d MMM y 'г'. Gccc, d MMM y 'г'. – ccc, d MMM y 'г'. G` |
| interval format `yMMMM` | `LLLL – LLLL y 'г'. GLLLL y 'г'. – LLLL y 'г'. G` |
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | янв. |
| month 2 | февр. |
| month 3 | мар. |
| month 4 | апр. |
| month 5 | мая |
| month 6 | июн. |
| month 7 | июл. |
| month 8 | авг. |
| month 9 | сент. |
| month 10 | окт. |
| month 11 | нояб. |
| month 12 | дек. |
| month 1 | Я |
| month 2 | Ф |
| month 3 | М |
| month 4 | А |
| month 5 | М |
| month 6 | И |
| month 7 | И |
| month 8 | А |
| month 9 | С |
| month 10 | О |
| month 11 | Н |
| month 12 | Д |
| month 1 | января |
| month 2 | февраля |
| month 3 | марта |
| month 4 | апреля |
| month 5 | мая |
| month 6 | июня |
| month 7 | июля |
| month 8 | августа |
| month 9 | сентября |
| month 10 | октября |
| month 11 | ноября |
| month 12 | декабря |
| month 1 | янв. |
| month 2 | февр. |
| month 3 | март |
| month 4 | апр. |
| month 5 | май |
| month 6 | июнь |
| month 7 | июль |
| month 8 | авг. |
| month 9 | сент. |
| month 10 | окт. |
| month 11 | нояб. |
| month 12 | дек. |
| month 1 | Я |
| month 2 | Ф |
| month 3 | М |
| month 4 | А |
| month 5 | М |
| month 6 | И |
| month 7 | И |
| month 8 | А |
| month 9 | С |
| month 10 | О |
| month 11 | Н |
| month 12 | Д |
| month 1 | январь |
| month 2 | февраль |
| month 3 | март |
| month 4 | апрель |
| month 5 | май |
| month 6 | июнь |
| month 7 | июль |
| month 8 | август |
| month 9 | сентябрь |
| month 10 | октябрь |
| month 11 | ноябрь |
| month 12 | декабрь |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | воскресенье |
| (week)day mon | понедельник |
| (week)day tue | вторник |
| (week)day wed | среда |
| (week)day thu | четверг |
| (week)day fri | пятница |
| (week)day sat | суббота |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | В |
| (week)day mon | П |
| (week)day tue | В |
| (week)day wed | С |
| (week)day thu | Ч |
| (week)day fri | П |
| (week)day sat | С |
| (week)day sun | вс |
| (week)day mon | пн |
| (week)day tue | вт |
| (week)day wed | ср |
| (week)day thu | чт |
| (week)day fri | пт |
| (week)day sat | сб |
| (week)day sun | воскресенье |
| (week)day mon | понедельник |
| (week)day tue | вторник |
| (week)day wed | среда |
| (week)day thu | четверг |
| (week)day fri | пятница |
| (week)day sat | суббота |
| quarter 1 | 1-й кв. |
| quarter 2 | 2-й кв. |
| quarter 3 | 3-й кв. |
| quarter 4 | 4-й кв. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1-й квартал |
| quarter 2 | 2-й квартал |
| quarter 3 | 3-й квартал |
| quarter 4 | 4-й квартал |
| quarter 1 | 1-й кв. |
| quarter 2 | 2-й кв. |
| quarter 3 | 3-й кв. |
| quarter 4 | 4-й кв. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1-й квартал |
| quarter 2 | 2-й квартал |
| quarter 3 | 3-й квартал |
| quarter 4 | 4-й квартал |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | вечера |
| period of day night1 | ночи |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | веч. |
| period of day night1 | ночи |
| period of day midnight | полночь |
| period of day am | AM |
| period of day noon | полдень |
| period of day pm | PM |
| period of day morning1 | утра |
| period of day afternoon1 | дня |
| period of day evening1 | вечера |
| period of day night1 | ночи |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | веч. |
| period of day night1 | ночь |
| period of day midnight | полн. |
| period of day am | AM |
| period of day noon | полд. |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | веч. |
| period of day night1 | ночь |
| period of day midnight | полночь |
| period of day am | AM |
| period of day noon | полдень |
| period of day pm | PM |
| period of day morning1 | утро |
| period of day afternoon1 | день |
| period of day evening1 | вечер |
| period of day night1 | ночь |
| era | до Рождества Христова |
| era | до нашей эры |
| era | от Рождества Христова |
| era | нашей эры |
| era | до н. э. |
| era | н. э. |
| era | до н.э. |
| era | н.э. |
| date format | `EEEE, d MMMM y 'г'.` |
| date format | `d MMMM y 'г'.` |
| date format | `d MMM y 'г'.` |
| date format | `dd.MM.y` |
| time format | `H:mm:ss zzzz` |
| time format | `H:mm:ss z` |
| time format | `H:mm:ss` |
| time format | `H:mm` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| datetime format | `{1}, {0}` |
| date format `Bh` | `h B` |
| date format `Bhm` | `h:mm B` |
| date format `Bhms` | `h:mm:ss B` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `ccc, h:mm B` |
| date format `EBhms` | `ccc, h:mm:ss B` |
| date format `Ed` | `ccc, d` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `y 'г'. G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `d MMM y 'г'. G` |
| date format `GyMMMEd` | `E, d MMM y 'г'. G` |
| date format `h` | `h a` |
| date format `H` | `H` |
| date format `hm` | `h:mm a` |
| date format `Hm` | `H:mm` |
| date format `hms` | `h:mm:ss a` |
| date format `Hms` | `H:mm:ss` |
| date format `hmsv` | `h:mm:ss a v` |
| date format `Hmsv` | `H:mm:ss v` |
| date format `hmv` | `h:mm a v` |
| date format `Hmv` | `H:mm v` |
| date format `M` | `L` |
| date format `Md` | `dd.MM` |
| date format `MEd` | `E, dd.MM` |
| date format `MMdd` | `dd.MM` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `d MMM` |
| date format `MMMEd` | `ccc, d MMM` |
| date format `MMMMd` | `d MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `MMMMW` | `W-'я' 'неделя' MMMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `MM.y` |
| date format `yMd` | `dd.MM.y` |
| date format `yMEd` | `ccc, dd.MM.y 'г'.` |
| date format `yMM` | `MM.y` |
| date format `yMMM` | `LLL y 'г'.` |
| date format `yMMMd` | `d MMM y 'г'.` |
| date format `yMMMEd` | `E, d MMM y 'г'.` |
| date format `yMMMM` | `LLLL y 'г'.` |
| date format `yQQQ` | `QQQ y 'г'.` |
| date format `yQQQQ` | `QQQQ y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| date format `yw` | `w-'я' 'неделя' Y 'г'.` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d` |
| interval format `h` | `h a – h ah–h a` |
| interval format `H` | `H–H` |
| interval format `hm` | `h:mm a – h:mm ah:mm–h:mm ah:mm–h:mm a` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `h:mm a – h:mm a vh:mm–h:mm a vh:mm–h:mm a v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `h a – h a vh–h a v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M` |
| interval format `Md` | `dd.MM – dd.MMdd.MM – dd.MM` |
| interval format `MEd` | `E, dd.MM – E, dd.MME, dd.MM – E, dd.MM` |
| interval format `MMM` | `LLL – LLL` |
| interval format `MMMd` | `d–d MMMd MMM – d MMM` |
| interval format `MMMEd` | `E, d MMM – E, d MMME, d MMM – E, d MMM` |
| interval format `MMMM` | `LLLL – LLLL` |
| interval format `y` | `y–y` |
| interval format `yM` | `MM.y – MM.yMM.y – MM.y` |
| interval format `yMd` | `dd.MM.y – dd.MM.ydd.MM.y – dd.MM.ydd.MM.y – dd.MM.y` |
| interval format `yMEd` | `ccc, dd.MM.y – ccc, dd.MM.yccc, dd.MM.y – ccc, dd.MM.yccc, dd.MM.y – ccc, dd.MM.y` |
| interval format `yMMM` | `LLL – LLL y 'г'.LLL y 'г'. – LLL y 'г'.` |
| interval format `yMMMd` | `d–d MMM y 'г'.d MMM – d MMM y 'г'.d MMM y 'г'. – d MMM y 'г'.` |
| interval format `yMMMEd` | `ccc, d – ccc, d MMM y 'г'.ccc, d MMM – ccc, d MMM y 'г'.ccc, d MMM y 'г'. – ccc, d MMM y 'г'.` |
| interval format `yMMMM` | `LLLL – LLLL y 'г'.LLLL y 'г'. – LLLL y 'г'.` |
#### hebrew calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | тишрей |
| month 2 | хешван |
| month 3 | кислев |
| month 4 | тевет |
| month 5 | шеват |
| month 6 | адар I |
| month 7 | адар |
| month 7 | адар II |
| month 8 | нисан |
| month 9 | ияр |
| month 10 | сиван |
| month 11 | таммуз |
| month 12 | ав |
| month 13 | элул |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | тишрей |
| month 2 | хешван |
| month 3 | кислев |
| month 4 | тевет |
| month 5 | шеват |
| month 6 | адар I |
| month 7 | адар |
| month 7 | адар II |
| month 8 | нисан |
| month 9 | ияр |
| month 10 | сиван |
| month 11 | таммуз |
| month 12 | ав |
| month 13 | элул |
| month 1 | тишрей |
| month 2 | хешван |
| month 3 | кислев |
| month 4 | тевет |
| month 5 | шеват |
| month 6 | адар I |
| month 7 | адар |
| month 7 | адар II |
| month 8 | нисан |
| month 9 | ияр |
| month 10 | сиван |
| month 11 | таммуз |
| month 12 | ав |
| month 13 | элул |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 13 | 13 |
| month 1 | тишрей |
| month 2 | хешван |
| month 3 | кислев |
| month 4 | тевет |
| month 5 | шеват |
| month 6 | адар I |
| month 7 | адар |
| month 7 | адар II |
| month 8 | нисан |
| month 9 | ияр |
| month 10 | сиван |
| month 11 | таммуз |
| month 12 | ав |
| month 13 | элул |
| era | от сотворения мира |
| era | AM |
| era | AM |
#### indian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | чайтра |
| month 2 | ваисакха |
| month 3 | джанштха |
| month 4 | асадха |
| month 5 | сравана |
| month 6 | бхадра |
| month 7 | азвина |
| month 8 | картика |
| month 9 | аграхайана |
| month 10 | пауза |
| month 11 | магха |
| month 12 | пхалгуна |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | чайтра |
| month 2 | ваисакха |
| month 3 | джанштха |
| month 4 | асадха |
| month 5 | сравана |
| month 6 | бхадра |
| month 7 | азвина |
| month 8 | картика |
| month 9 | аграхайана |
| month 10 | пауза |
| month 11 | магха |
| month 12 | пхалгуна |
| month 1 | чайтра |
| month 2 | ваисакха |
| month 3 | джанштха |
| month 4 | асадха |
| month 5 | сравана |
| month 6 | бхадра |
| month 7 | азвина |
| month 8 | картика |
| month 9 | аграхайана |
| month 10 | пауза |
| month 11 | магха |
| month 12 | пхалгуна |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | чайтра |
| month 2 | ваисакха |
| month 3 | джанштха |
| month 4 | асадха |
| month 5 | сравана |
| month 6 | бхадра |
| month 7 | азвина |
| month 8 | картика |
| month 9 | аграхайана |
| month 10 | пауза |
| month 11 | магха |
| month 12 | пхалгуна |
| era | Сака |
| era | Сака |
| era | Сака |
#### islamic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | мух. |
| month 2 | саф. |
| month 3 | раб. I |
| month 4 | раб. II |
| month 5 | джум. I |
| month 6 | джум. II |
| month 7 | радж. |
| month 8 | шааб. |
| month 9 | рам. |
| month 10 | шав. |
| month 11 | зуль-к. |
| month 12 | зуль-х. |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | мухаррам |
| month 2 | сафар |
| month 3 | раби-уль-авваль |
| month 4 | раби-уль-ахир |
| month 5 | джумад-уль-авваль |
| month 6 | джумад-уль-ахир |
| month 7 | раджаб |
| month 8 | шаабан |
| month 9 | рамадан |
| month 10 | шавваль |
| month 11 | зуль-каада |
| month 12 | зуль-хиджжа |
| month 1 | мух. |
| month 2 | саф. |
| month 3 | раб. I |
| month 4 | раб. II |
| month 5 | джум. I |
| month 6 | джум. II |
| month 7 | радж. |
| month 8 | шааб. |
| month 9 | рам. |
| month 10 | шав. |
| month 11 | зуль-к. |
| month 12 | зуль-х. |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | мухаррам |
| month 2 | сафар |
| month 3 | раби-уль-авваль |
| month 4 | раби-уль-ахир |
| month 5 | джумад-уль-авваль |
| month 6 | джумад-уль-ахир |
| month 7 | раджаб |
| month 8 | шаабан |
| month 9 | рамадан |
| month 10 | шавваль |
| month 11 | зуль-каада |
| month 12 | зуль-хиджжа |
| era | после хиджры |
| era | AH |
| era | AH |
#### japanese calendar
| ID-stuff | values |
| -------- | ------ |
| era | Эпоха Тайка (645–650) |
| era | Эпоха Хакути (650–671) |
| era | Эпоха Хакухо (672–686) |
| era | Эпоха Сючё (686–701) |
| era | Эпоха Тайхо (701–704) |
| era | Эпоха Кёюн (704–708) |
| era | Эпоха Вадо (708–715) |
| era | Эпоха Рэйки (715–717) |
| era | Эпоха Ёро (717–724) |
| era | Эпоха Дзинки (724–729) |
| era | Эпоха Темпьё (729–749) |
| era | Эпоха Темпьё (749–749) |
| era | Эпоха Темпьё-Сьохо (749-757) |
| era | Эпоха Темпьё-Ходзи (757-765) |
| era | Эпоха Темпьё-Ходзи (765-767) |
| era | Эпоха Джинго-Кёюн (767-770) |
| era | Эпоха Хоки (770–780) |
| era | Эпоха Теньё (781–782) |
| era | Эпоха Енряку (782–806) |
| era | Эпоха Дайдо (806–810) |
| era | Эпоха Конин (810–824) |
| era | Эпоха Тентьо (824–834) |
| era | Эпоха Шова (834–848) |
| era | Эпоха Кайо (848–851) |
| era | Эпоха Ниндзю (851–854) |
| era | Эпоха Сайко (854–857) |
| era | Эпоха Теннан (857–859) |
| era | Эпоха Йоган (859–877) |
| era | Эпоха Генкей (877–885) |
| era | Эпоха Нинна (885–889) |
| era | Эпоха Кампьё (889–898) |
| era | Эпоха Сьотай (898–901) |
| era | Эпоха Энги (901–923) |
| era | Эпоха Ентьо (923–931) |
| era | Эпоха Сьёхэй (931–938) |
| era | Эпоха Тенгьо (938–947) |
| era | Эпоха Тенрияку (947–957) |
| era | Эпоха Тентоку (957–961) |
| era | Эпоха Ова (961–964) |
| era | Эпоха Кохо (964–968) |
| era | Эпоха Анна (968–970) |
| era | Эпоха Тенроку (970–973) |
| era | Эпоха Теньен (973–976) |
| era | Эпоха Дзьоген (976–978) |
| era | Эпоха Тенген (978–983) |
| era | Эпоха Ейкан (983–985) |
| era | Эпоха Канна (985–987) |
| era | Эпоха Ейен (987–989) |
| era | Эпоха Ейсо (989–990) |
| era | Эпоха Сёряку (990–995) |
| era | Эпоха Тётоку (995–999) |
| era | Эпоха Тёхо (999–1004) |
| era | Эпоха Канко (1004–1012) |
| era | Эпоха Тёва (1012–1017) |
| era | Эпоха Каннин (1017–1021) |
| era | Эпоха Дзиан (1021–1024) |
| era | Эпоха Мандзю (1024–1028) |
| era | Эпоха Тёгэн (1028–1037) |
| era | Эпоха Тёряку (1037–1040) |
| era | Эпоха Тёкю (1040–1044) |
| era | Эпоха Катоку (1044–1046) |
| era | Эпоха Эйсо (1046–1053) |
| era | Эпоха Тэнги (1053–1058) |
| era | Эпоха Кохэй (1058–1065) |
| era | Эпоха Дзиряку (1065–1069) |
| era | Эпоха Энкю (1069–1074) |
| era | Эпоха Сёхо (1074–1077) |
| era | Эпоха Сёряку (1077–1081) |
| era | Эпоха Эйхо (1081–1084) |
| era | Эпоха Отоку (1084–1087) |
| era | Эпоха Кандзи (1087–1094) |
| era | Эпоха Кахо (1094–1096) |
| era | Эпоха Эйтё (1096–1097) |
| era | Эпоха Сётоку (1097–1099) |
| era | Эпоха Кова (1099–1104) |
| era | Эпоха Тёдзи (1104–1106) |
| era | Эпоха Касё (1106–1108) |
| era | Эпоха Тэннин (1108–1110) |
| era | Эпоха Тэнъэй (1110–1113) |
| era | Эпоха Эйкю (1113–1118) |
| era | Эпоха Гэнъэй (1118–1120) |
| era | Эпоха Хоан (1120–1124) |
| era | Эпоха Тэндзи (1124–1126) |
| era | Эпоха Дайдзи (1126–1131) |
| era | Эпоха Тэнсё (1131–1132) |
| era | Эпоха Тёсё (1132–1135) |
| era | Эпоха Хоэн (1135–1141) |
| era | Эпоха Эйдзи (1141–1142) |
| era | Эпоха Кодзи (1142–1144) |
| era | Эпоха Тэнё (1144–1145) |
| era | Эпоха Кюан (1145–1151) |
| era | Эпоха Нимпэй (1151–1154) |
| era | Эпоха Кюдзю (1154–1156) |
| era | Эпоха Хогэн (1156–1159) |
| era | Эпоха Хэйдзи (1159–1160) |
| era | Эпоха Эйряку (1160–1161) |
| era | Эпоха Охо (1161–1163) |
| era | Эпоха Тёкан (1163–1165) |
| era | Эпоха Эйман (1165–1166) |
| era | Эпоха Нинъан (1166–1169) |
| era | Эпоха Као (1169–1171) |
| era | Эпоха Сёан (1171–1175) |
| era | Эпоха Ангэн (1175–1177) |
| era | Эпоха Дзисё (1177–1181) |
| era | Эпоха Ёва (1181–1182) |
| era | Эпоха Дзюэй (1182–1184) |
| era | Эпоха Гэнрюку (1184–1185) |
| era | Эпоха Бундзи (1185–1190) |
| era | Эпоха Кэнкю (1190–1199) |
| era | Эпоха Сёдзи (1199–1201) |
| era | Эпоха Кэннин (1201–1204) |
| era | Эпоха Гэнкю (1204–1206) |
| era | Эпоха Кэнъэй (1206–1207) |
| era | Эпоха Сёгэн (1207–1211) |
| era | Эпоха Кэнряку (1211–1213) |
| era | Эпоха Кэмпо (1213–1219) |
| era | Эпоха Сёкю (1219–1222) |
| era | Эпоха Дзёо (1222–1224) |
| era | Эпоха Гэннин (1224–1225) |
| era | Эпоха Кароку (1225–1227) |
| era | Эпоха Антэй (1227–1229) |
| era | Эпоха Канки (1229–1232) |
| era | Эпоха Дзёэй (1232–1233) |
| era | Эпоха Тэмпуку (1233–1234) |
| era | Эпоха Бунряку (1234–1235) |
| era | Эпоха Катэй (1235–1238) |
| era | Эпоха Рякунин (1238–1239) |
| era | Эпоха Энъо (1239–1240) |
| era | Эпоха Ниндзи (1240–1243) |
| era | Эпоха Кангэн (1243–1247) |
| era | Эпоха Ходзи (1247–1249) |
| era | Эпоха Кэнтё (1249–1256) |
| era | Эпоха Когэн (1256–1257) |
| era | Эпоха Сёка (1257–1259) |
| era | Эпоха Сёгэн (1259–1260) |
| era | Эпоха Бунъо (1260–1261) |
| era | Эпоха Котё (1261–1264) |
| era | Эпоха Бунъэй (1264–1275) |
| era | Эпоха Кэндзи (1275–1278) |
| era | Эпоха Коан (1278–1288) |
| era | Эпоха Сёо (1288–1293) |
| era | Эпоха Эйнин (1293–1299) |
| era | Эпоха Сёан (1299–1302) |
| era | Эпоха Кэнгэн (1302–1303) |
| era | Эпоха Кагэн (1303–1306) |
| era | Эпоха Токудзи (1306–1308) |
| era | Эпоха Энкэй (1308–1311) |
| era | Эпоха Отё (1311–1312) |
| era | Эпоха Сёва (1312–1317) |
| era | Эпоха Бумпо (1317–1319) |
| era | Эпоха Гэно (1319–1321) |
| era | Эпоха Гэнкё (1321–1324) |
| era | Эпоха Сётю (1324–1326) |
| era | Эпоха Карэки (1326–1329) |
| era | Эпоха Гэнтоку (1329–1331) |
| era | Эпоха Гэнко (1331–1334) |
| era | Эпоха Кэмму (1334–1336) |
| era | Эпоха Энгэн (1336–1340) |
| era | Эпоха Кококу (1340–1346) |
| era | Эпоха Сёхэй (1346–1370) |
| era | Эпоха Кэнтоку (1370–1372) |
| era | Эпоха Бунтю (1372–1375) |
| era | Эпоха Иэндзю (1375–1379) |
| era | Эпоха Коряку (1379–1381) |
| era | Эпоха Кова (1381–1384) |
| era | Эпоха Гэнтю (1384–1392) |
| era | Эпоха Мэйтоку (1384–1387) |
| era | Эпоха Какэй (1387–1389) |
| era | Эпоха Коо (1389–1390) |
| era | Эпоха Мэйтоку (1390–1394) |
| era | Эпоха Оэй (1394–1428) |
| era | Эпоха Сётё (1428–1429) |
| era | Эпоха Эйкё (1429–1441) |
| era | Эпоха Какицу (1441–1444) |
| era | Эпоха Банъан (1444–1449) |
| era | Эпоха Хотоку (1449–1452) |
| era | Эпоха Кётоку (1452–1455) |
| era | Эпоха Косё (1455–1457) |
| era | Эпоха Тёроку (1457–1460) |
| era | Эпоха Кансё (1460–1466) |
| era | Эпоха Бунсё (1466–1467) |
| era | Эпоха Онин (1467–1469) |
| era | Эпоха Буммэй (1469–1487) |
| era | Эпоха Тёкё (1487–1489) |
| era | Эпоха Энтоку (1489–1492) |
| era | Эпоха Мэйо (1492–1501) |
| era | Эпоха Бунки (1501–1504) |
| era | Эпоха Эйсё (1504–1521) |
| era | Эпоха Тайэй (1521–1528) |
| era | Эпоха Кёроку (1528–1532) |
| era | Эпоха Тэммон (1532–1555) |
| era | Эпоха Кодзи (1555–1558) |
| era | Эпоха Эйроку (1558–1570) |
| era | Эпоха Гэнки (1570–1573) |
| era | Эпоха Тэнсё (1573–1592) |
| era | Эпоха Бунроку (1592–1596) |
| era | Эпоха Кэйтё (1596–1615) |
| era | Эпоха Гэнва (1615–1624) |
| era | Эпоха Канъэй (1624–1644) |
| era | Эпоха Сёхо (1644–1648) |
| era | Эпоха Кэйан (1648–1652) |
| era | Эпоха Сё (1652–1655) |
| era | Эпоха Мэйряку (1655–1658) |
| era | Эпоха Мандзи (1658–1661) |
| era | Эпоха Камбун (1661–1673) |
| era | Эпоха Эмпо (1673–1681) |
| era | Эпоха Тэнва (1681–1684) |
| era | Эпоха Дзёкё (1684–1688) |
| era | Эпоха Гэнроку (1688–1704) |
| era | Эпоха Хоэй (1704–1711) |
| era | Эпоха Сётоку (1711–1716) |
| era | Эпоха Кёхо (1716–1736) |
| era | Эпоха Гэмбун (1736–1741) |
| era | Эпоха Кампо (1741–1744) |
| era | Эпоха Энкё (1744–1748) |
| era | Эпоха Канъэн (1748–1751) |
| era | Эпоха Хоряку (1751–1764) |
| era | Эпоха Мэйва (1764–1772) |
| era | Эпоха Анъэй (1772–1781) |
| era | Эпоха Тэммэй (1781–1789) |
| era | Эпоха Кансэй (1789–1801) |
| era | Эпоха Кёва (1801–1804) |
| era | Эпоха Бунка (1804–1818) |
| era | Эпоха Бунсэй (1818–1830) |
| era | Эпоха Тэмпо (1830–1844) |
| era | Эпоха Кока (1844–1848) |
| era | Эпоха Каэй (1848–1854) |
| era | Эпоха Ансэй (1854–1860) |
| era | Эпоха Манъэн (1860–1861) |
| era | Эпоха Бункю (1861–1864) |
| era | Эпоха Гендзи (1864–1865) |
| era | Эпоха Кейо (1865–1868) |
| era | Эпоха Мэйдзи |
| era | Эпоха Тайсьо |
| era | Сьова |
| era | Эпоха Хэйсэй |
#### persian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | фарвардин |
| month 2 | ордибехешт |
| month 3 | хордад |
| month 4 | тир |
| month 5 | мордад |
| month 6 | шахривер |
| month 7 | мехр |
| month 8 | абан |
| month 9 | азер |
| month 10 | дей |
| month 11 | бахман |
| month 12 | эсфанд |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | фарвардин |
| month 2 | ордибехешт |
| month 3 | хордад |
| month 4 | тир |
| month 5 | мордад |
| month 6 | шахривер |
| month 7 | мехр |
| month 8 | абан |
| month 9 | азер |
| month 10 | дей |
| month 11 | бахман |
| month 12 | эсфанд |
| month 1 | фарвардин |
| month 2 | ордибехешт |
| month 3 | хордад |
| month 4 | тир |
| month 5 | мордад |
| month 6 | шахривер |
| month 7 | мехр |
| month 8 | абан |
| month 9 | азер |
| month 10 | дей |
| month 11 | бахман |
| month 12 | эсфанд |
| month 1 | 1 |
| month 2 | 2 |
| month 3 | 3 |
| month 4 | 4 |
| month 5 | 5 |
| month 6 | 6 |
| month 7 | 7 |
| month 8 | 8 |
| month 9 | 9 |
| month 10 | 10 |
| month 11 | 11 |
| month 12 | 12 |
| month 1 | фарвардин |
| month 2 | ордибехешт |
| month 3 | хордад |
| month 4 | тир |
| month 5 | мордад |
| month 6 | шахривер |
| month 7 | мехр |
| month 8 | абан |
| month 9 | азер |
| month 10 | дей |
| month 11 | бахман |
| month 12 | эсфанд |
| era | персидский год |
| era | перс. год |
| era | перс. год |
#### roc calendar
| ID-stuff | values |
| -------- | ------ |
| era | до основания Китайской республики |
| era | Миньго |
| era | Before R.O.C. |
| era | Minguo |
| era | до респ. |
| era | Миньго |
### some more time stuff
|  | эра |
|  | эра |
|  | эра |
|  | год |
в прошлом годув этом годув следующем годучерез {0} годчерез {0} годачерез {0} летчерез {0} года{0} год назад{0} года назад{0} лет назад{0} года назад
|  | г. |
в прошлом г.в этом г.в след. г.через {0} г.через {0} г.через {0} л.через {0} г.{0} г. назад{0} г. назад{0} л. назад{0} г. назад
|  | г. |
в пр. г.в эт. г.в сл. г.+{0} г.+{0} г.+{0} л.+{0} г.-{0} г.-{0} г.-{0} л.-{0} г.
|  | квартал |
в прошлом кварталев текущем кварталев следующем кварталечерез {0} кварталчерез {0} кварталачерез {0} кварталовчерез {0} квартала{0} квартал назад{0} квартала назад{0} кварталов назад{0} квартала назад
|  | кв. |
последний кв.текущий кв.следующий кв.через {0} кв.через {0} кв.через {0} кв.через {0} кв.{0} кв. назад{0} кв. назад{0} кв. назад{0} кв. назад
|  | кв. |
посл. кв.тек. кв.след. кв.+{0} кв.+{0} кв.+{0} кв.+{0} кв.-{0} кв.-{0} кв.-{0} кв.-{0} кв.
|  | месяц |
в прошлом месяцев этом месяцев следующем месяцечерез {0} месяцчерез {0} месяцачерез {0} месяцевчерез {0} месяца{0} месяц назад{0} месяца назад{0} месяцев назад{0} месяца назад
|  | мес. |
в прошлом мес.в этом мес.в следующем мес.через {0} мес.через {0} мес.через {0} мес.через {0} мес.{0} мес. назад{0} мес. назад{0} мес. назад{0} мес. назад
|  | мес. |
в пр. мес.в эт. мес.в след. мес.+{0} мес.+{0} мес.+{0} мес.+{0} мес.-{0} мес.-{0} мес.-{0} мес.-{0} мес.
|  | неделя |
на прошлой неделена этой неделена следующей неделечерез {0} неделючерез {0} неделичерез {0} недельчерез {0} недели{0} неделю назад{0} недели назад{0} недель назад{0} недели назадна неделе {0}
|  | нед. |
на прошлой нед.на этой нед.на следующей нед.через {0} нед.через {0} нед.через {0} нед.через {0} нед.{0} нед. назад{0} нед. назад{0} нед. назад{0} нед. назадна нед. {0}
|  | нед. |
на пр. нед.на эт. нед.на след. неделе+{0} нед.+{0} нед.+{0} нед.+{0} нед.-{0} нед.-{0} нед.-{0} нед.-{0} нед.на нед. {0}
|  | неделя месяца |
|  | нед. месяца |
|  | нед. мес. |
|  | день |
позавчеравчерасегоднязавтрапослезавтрачерез {0} деньчерез {0} днячерез {0} днейчерез {0} дня{0} день назад{0} дня назад{0} дней назад{0} дня назад
|  | дн. |
позавчерапослезавтрачерез {0} дн.через {0} дн.через {0} дн.через {0} дн.{0} дн. назад{0} дн. назад{0} дн. назад{0} дн. назад
|  | дн. |
позавчерапослезавтра+{0} дн.+{0} дн.+{0} дн.+{0} дн.-{0} дн.-{0} дн.-{0} дн.-{0} дн.
|  | день года |
|  | дн. года |
|  | дн. года |
|  | день недели |
|  | дн. недели |
|  | дн. нед. |
|  | день недели в месяце |
|  | дн. нед. в месяце |
|  | дн. нед. в мес. |
в прошлое воскресеньев это воскресеньев следующее воскресеньечерез {0} воскресеньечерез {0} воскресеньячерез {0} воскресенийчерез {0} воскресенья{0} воскресенье назад{0} воскресенья назад{0} воскресений назад{0} воскресенья назадв прош. вс.в это вс.в след. вс.через {0} вс.через {0} вс.через {0} вс.через {0} вс.{0} вс. назад{0} вс. назад{0} вс. назад{0} вс. назадв прош. вс.в это вс.в след. вс.+{0} вс.+{0} вс.+{0} вс.+{0} вс.-{0} вс.-{0} вс.-{0} вс.-{0} вс.в прошлый понедельникв этот понедельникв следующий понедельникчерез {0} понедельникчерез {0} понедельникачерез {0} понедельниковчерез {0} понедельника{0} понедельник назад{0} понедельника назад{0} понедельников назад{0} понедельника назадв прош. пн.в этот пн.в след. пн.через {0} пн.через {0} пн.через {0} пн.через {0} пн.{0} пн. назад{0} пн. назад{0} пн. назад{0} пн. назадв прош. пн.в этот пн.в след. пн.+{0} пн.+{0} пн.+{0} пн.+{0} пн.-{0} пн.-{0} пн.-{0} пн.-{0} пн.в прошлый вторникв этот вторникв следующий вторникчерез {0} вторникчерез {0} вторникачерез {0} вторниковчерез {0} вторника{0} вторник назад{0} вторника назад{0} вторников назад{0} вторника назадв прош. вт.в этот вт.в след. вт.через {0} вт.через {0} вт.через {0} вт.через {0} вт.{0} вт. назад{0} вт. назад{0} вт. назад{0} вт. назадв прош. вт.в этот вт.в след. вт.+{0} вт.+{0} вт.+{0} вт.+{0} вт.-{0} вт.-{0} вт.-{0} вт.-{0} вт.в прошлую средув эту средув следующую средучерез {0} средучерез {0} средычерез {0} средчерез {0} среды{0} среду назад{0} среды назад{0} сред назад{0} среды назадв прош. ср.в эту ср.в след. ср.через {0} ср.через {0} ср.через {0} ср.через {0} ср.{0} ср. назад{0} ср. назад{0} ср. назад{0} ср. назадв прош. ср.в эту ср.в след. ср.+{0} ср.+{0} ср.+{0} ср.+{0} ср.-{0} ср.-{0} ср.-{0} ср.-{0} ср.в прошлый четвергв этот четвергв следующий четвергчерез {0} четвергчерез {0} четвергачерез {0} четверговчерез {0} четверга{0} четверг назад{0} четверга назад{0} четвергов назад{0} четверга назадв прош. чт.в этот чт.в след. чт.через {0} чт.через {0} чт.через {0} чт.через {0} чт.{0} чт. назад{0} чт. назад{0} чт. назад{0} чт. назадв прош. чт.в этот чт.в след. чт.+{0} чт.+{0} чт.+{0} чт.+{0} чт.-{0} чт.-{0} чт.-{0} чт.-{0} чт.в прошлую пятницув эту пятницув следующую пятницучерез {0} пятницучерез {0} пятницычерез {0} пятницчерез {0} пятницы{0} пятницу назад{0} пятницы назад{0} пятниц назад{0} пятницы назадв прош. пт.в эту пт.в след. пт.через {0} пт.через {0} пт.через {0} пт.через {0} пт.{0} пт. назад{0} пт. назад{0} пт. назад{0} пт. назадв прош. пт.в эту пт.в след. пт.+{0} пт.+{0} пт.+{0} пт.+{0} пт.-{0} пт.-{0} пт.-{0} пт.-{0} пт.в прошлую субботув эту субботув следующую субботучерез {0} субботучерез {0} субботычерез {0} субботчерез {0} субботы{0} субботу назад{0} субботы назад{0} суббот назад{0} субботы назадв прош. сб.в эту сб.в след. сб.через {0} сб.через {0} сб.через {0} сб.через {0} сб.{0} сб. назад{0} сб. назад{0} сб. назад{0} сб. назадв прош. сб.в эту сб.в след. сб.+{0} сб.+{0} сб.+{0} сб.+{0} сб.-{0} сб.-{0} сб.-{0} сб.-{0} сб.
|  | AM/PM |
|  | AM/PM |
|  | AM/PM |
|  | час |
в этот часчерез {0} часчерез {0} часачерез {0} часовчерез {0} часа{0} час назад{0} часа назад{0} часов назад{0} часа назад
|  | ч |
в этот часчерез {0} ч.через {0} ч.через {0} ч.через {0} ч.{0} ч. назад{0} ч. назад{0} ч. назад{0} ч. назад
|  | ч |
в этот час+{0} ч.+{0} ч.+{0} ч.+{0} ч.-{0} ч.-{0} ч.-{0} ч.-{0} ч.
|  | минута |
в эту минутучерез {0} минутучерез {0} минутычерез {0} минутчерез {0} минуты{0} минуту назад{0} минуты назад{0} минут назад{0} минуты назад
|  | мин. |
через {0} мин.через {0} мин.через {0} мин.через {0} мин.{0} мин. назад{0} мин. назад{0} мин. назад{0} мин. назад
|  | мин |
+{0} мин.+{0} мин.+{0} мин.+{0} мин.-{0} мин.-{0} мин.-{0} мин.-{0} мин.
|  | секунда |
сейчасчерез {0} секундучерез {0} секундычерез {0} секундчерез {0} секунды{0} секунду назад{0} секунды назад{0} секунд назад{0} секунды назад
|  | сек. |
через {0} сек.через {0} сек.через {0} сек.через {0} сек.{0} сек. назад{0} сек. назад{0} сек. назад{0} сек. назад
|  | с |
+{0} с+{0} с+{0} с+{0} с-{0} с-{0} с-{0} с-{0} с
|  | часовой пояс |
|  | час. пояс |
|  | час. пояс |
#### time zones
| Format name | Format |
| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| Time at Greenwich | GMT |
| regional | {0} |
| regional | {0}, летнее время |
| regional | {0}, стандартное время |
| fallback | {1} ({0}) |
| Zone | Name |
| ---- | ---- |
| America/Santa_Isabel | Санта-Изабел |
| Pacific/Honolulu | Гонолулу |
| Etc/UTC | Всемирное координированное время |
| Etc/Unknown | Неизвестный город |
| Europe/Andorra | Андорра |
| Asia/Dubai | Дубай |
| Asia/Kabul | Кабул |
| America/Antigua | Антигуа |
| America/Anguilla | Ангилья |
| Europe/Tirane | Тирана |
| Asia/Yerevan | Ереван |
| Africa/Luanda | Луанда |
| Antarctica/Rothera | Ротера |
| Antarctica/Palmer | Палмер |
| Antarctica/Troll | Тролль |
| Antarctica/Syowa | Сёва |
| Antarctica/Mawson | Моусон |
| Antarctica/Davis | Дейвис |
| Antarctica/Vostok | Восток |
| Antarctica/Casey | Кейси |
| Antarctica/DumontDUrville | Дюмон-д’Юрвиль |
| Antarctica/McMurdo | Мак-Мердо |
| America/Argentina/Rio_Gallegos | Рио-Гальегос |
| America/Mendoza | Мендоса |
| America/Argentina/San_Juan | Сан-Хуан |
| America/Argentina/Ushuaia | Ушуая |
| America/Argentina/La_Rioja | Ла-Риоха |
| America/Argentina/San_Luis | Сан-Луис |
| America/Catamarca | Катамарка |
| America/Argentina/Salta | Сальта |
| America/Jujuy | Жужуй |
| America/Argentina/Tucuman | Тукуман |
| America/Cordoba | Кордова |
| America/Buenos_Aires | Буэнос-Айрес |
| Pacific/Pago_Pago | Паго-Паго |
| Europe/Vienna | Вена |
| Australia/Perth | Перт |
| Australia/Eucla | Юкла |
| Australia/Darwin | Дарвин |
| Australia/Adelaide | Аделаида |
| Australia/Broken_Hill | Брокен-Хилл |
| Australia/Currie | Керри |
| Australia/Melbourne | Мельбурн |
| Australia/Hobart | Хобарт |
| Australia/Lindeman | Линдеман |
| Australia/Sydney | Сидней |
| Australia/Brisbane | Брисбен |
| Antarctica/Macquarie | Маккуори |
| Australia/Lord_Howe | Лорд-Хау |
| America/Aruba | Аруба |
| Europe/Mariehamn | Мариехамн |
| Asia/Baku | Баку |
| Europe/Sarajevo | Сараево |
| America/Barbados | Барбадос |
| Asia/Dhaka | Дакка |
| Europe/Brussels | Брюссель |
| Africa/Ouagadougou | Уагадугу |
| Europe/Sofia | София |
| Asia/Bahrain | Бахрейн |
| Africa/Bujumbura | Бужумбура |
| Africa/Porto-Novo | Порто-Ново |
| America/St_Barthelemy | Сен-Бартелеми |
| Atlantic/Bermuda | Бермудские о-ва |
| Asia/Brunei | Бруней |
| America/La_Paz | Ла-Пас |
| America/Kralendijk | Кралендейк |
| America/Eirunepe | Эйрунепе |
| America/Rio_Branco | Риу-Бранку |
| America/Porto_Velho | Порту-Велью |
| America/Boa_Vista | Боа-Виста |
| America/Manaus | Манаус |
| America/Cuiaba | Куяба |
| America/Santarem | Сантарен |
| America/Campo_Grande | Кампу-Гранди |
| America/Belem | Белен |
| America/Araguaina | Арагуаина |
| America/Sao_Paulo | Сан-Паулу |
| America/Bahia | Баия |
| America/Fortaleza | Форталеза |
| America/Maceio | Масейо |
| America/Recife | Ресифи |
| America/Noronha | Норонья |
| America/Nassau | Нассау |
| Asia/Thimphu | Тхимпху |
| Africa/Gaborone | Габороне |
| Europe/Minsk | Минск |
| America/Belize | Белиз |
| America/Dawson | Доусон |
| America/Whitehorse | Уайтхорс |
| America/Inuvik | Инувик |
| America/Vancouver | Ванкувер |
| America/Fort_Nelson | Форт Нельсон |
| America/Dawson_Creek | Доусон-Крик |
| America/Creston | Крестон |
| America/Yellowknife | Йеллоунайф |
| America/Edmonton | Эдмонтон |
| America/Swift_Current | Свифт-Керрент |
| America/Cambridge_Bay | Кеймбридж-Бей |
| America/Regina | Реджайна |
| America/Winnipeg | Виннипег |
| America/Resolute | Резольют |
| America/Rainy_River | Рейни-Ривер |
| America/Rankin_Inlet | Ранкин-Инлет |
| America/Coral_Harbour | Корал-Харбор |
| America/Thunder_Bay | Тандер-Бей |
| America/Nipigon | Нипигон |
| America/Toronto | Торонто |
| America/Iqaluit | Икалуит |
| America/Pangnirtung | Пангниртунг |
| America/Moncton | Монктон |
| America/Halifax | Галифакс |
| America/Goose_Bay | Гус-Бей |
| America/Glace_Bay | Глейс-Бей |
| America/Blanc-Sablon | Бланк-Саблон |
| America/St_Johns | Сент-Джонс |
| Indian/Cocos | Кокосовые о-ва |
| Africa/Kinshasa | Киншаса |
| Africa/Lubumbashi | Лубумбаши |
| Africa/Bangui | Банги |
| Africa/Brazzaville | Браззавиль |
| Europe/Zurich | Цюрих |
| Africa/Abidjan | Абиджан |
| Pacific/Rarotonga | Раротонга |
| Pacific/Easter | о-в Пасхи |
| America/Punta_Arenas | Пунта-Аренас |
| America/Santiago | Сантьяго |
| Africa/Douala | Дуала |
| Asia/Urumqi | Урумчи |
| Asia/Shanghai | Шанхай |
| America/Bogota | Богота |
| America/Costa_Rica | Коста-Рика |
| America/Havana | Гавана |
| Atlantic/Cape_Verde | Кабо-Верде |
| America/Curacao | Кюрасао |
| Indian/Christmas | о-в Рождества |
| Asia/Nicosia | Никосия |
| Asia/Famagusta | Фамагуста |
| Europe/Prague | Прага |
| Europe/Busingen | Бюзинген-на-Верхнем-Рейне |
| Europe/Berlin | Берлин |
| Africa/Djibouti | Джибути |
| Europe/Copenhagen | Копенгаген |
| America/Dominica | Доминика |
| America/Santo_Domingo | Санто-Доминго |
| Africa/Algiers | Алжир |
| Pacific/Galapagos | Галапагосские о-ва |
| America/Guayaquil | Гуаякиль |
| Europe/Tallinn | Таллин |
| Africa/Cairo | Каир |
| Africa/El_Aaiun | Эль-Аюн |
| Africa/Asmera | Асмэра |
| Atlantic/Canary | Канарские о-ва |
| Africa/Ceuta | Сеута |
| Europe/Madrid | Мадрид |
| Africa/Addis_Ababa | Аддис-Абеба |
| Europe/Helsinki | Хельсинки |
| Pacific/Fiji | Фиджи |
| Atlantic/Stanley | Стэнли |
| Pacific/Truk | Трук |
| Pacific/Ponape | Понпеи |
| Pacific/Kosrae | Косрае |
| Atlantic/Faeroe | Фарерские о-ва |
| Europe/Paris | Париж |
| Africa/Libreville | Либревиль |
| Europe/London | Великобритания, летнее времяЛондон |
| America/Grenada | Гренада |
| Asia/Tbilisi | Тбилиси |
| America/Cayenne | Кайенна |
| Europe/Guernsey | Гернси |
| Africa/Accra | Аккра |
| Europe/Gibraltar | Гибралтар |
| America/Thule | Туле |
| America/Godthab | Нуук |
| America/Scoresbysund | Скорсбисунн |
| America/Danmarkshavn | Денмарксхавн |
| Africa/Banjul | Банжул |
| Africa/Conakry | Конакри |
| America/Guadeloupe | Гваделупа |
| Africa/Malabo | Малабо |
| Europe/Athens | Афины |
| Atlantic/South_Georgia | Южная Георгия |
| America/Guatemala | Гватемала |
| Pacific/Guam | Гуам |
| Africa/Bissau | Бисау |
| America/Guyana | Гайана |
| Asia/Hong_Kong | Гонконг |
| America/Tegucigalpa | Тегусигальпа |
| Europe/Zagreb | Загреб |
| America/Port-au-Prince | Порт-о-Пренс |
| Europe/Budapest | Будапешт |
| Asia/Jakarta | Джакарта |
| Asia/Pontianak | Понтианак |
| Asia/Makassar | Макасар |
| Asia/Jayapura | Джаяпура |
| Europe/Dublin | Ирландия, стандартное времяДублин |
| Asia/Jerusalem | Иерусалим |
| Europe/Isle_of_Man | о-в Мэн |
| Asia/Calcutta | Калькутта |
| Indian/Chagos | Чагос |
| Asia/Baghdad | Багдад |
| Asia/Tehran | Тегеран |
| Atlantic/Reykjavik | Рейкьявик |
| Europe/Rome | Рим |
| Europe/Jersey | Джерси |
| America/Jamaica | Ямайка |
| Asia/Amman | Амман |
| Asia/Tokyo | Токио |
| Africa/Nairobi | Найроби |
| Asia/Bishkek | Бишкек |
| Asia/Phnom_Penh | Пномпень |
| Pacific/Enderbury | о-в Эндербери |
| Pacific/Kiritimati | Киритимати |
| Pacific/Tarawa | Тарава |
| Indian/Comoro | Коморы |
| America/St_Kitts | Сент-Китс |
| Asia/Pyongyang | Пхеньян |
| Asia/Seoul | Сеул |
| Asia/Kuwait | Кувейт |
| America/Cayman | Каймановы о-ва |
| Asia/Aqtau | Актау |
| Asia/Oral | Уральск |
| Asia/Atyrau | Атырау |
| Asia/Aqtobe | Актобе |
| Asia/Qyzylorda | Кызылорда |
| Asia/Almaty | Алматы |
| Asia/Vientiane | Вьентьян |
| Asia/Beirut | Бейрут |
| America/St_Lucia | Сент-Люсия |
| Europe/Vaduz | Вадуц |
| Asia/Colombo | Коломбо |
| Africa/Monrovia | Монровия |
| Africa/Maseru | Масеру |
| Europe/Vilnius | Вильнюс |
| Europe/Luxembourg | Люксембург |
| Europe/Riga | Рига |
| Africa/Tripoli | Триполи |
| Africa/Casablanca | Касабланка |
| Europe/Monaco | Монако |
| Europe/Chisinau | Кишинев |
| Europe/Podgorica | Подгорица |
| America/Marigot | Мариго |
| Indian/Antananarivo | Антананариву |
| Pacific/Kwajalein | Кваджалейн |
| Pacific/Majuro | Маджуро |
| Europe/Skopje | Скопье |
| Africa/Bamako | Бамако |
| Asia/Rangoon | Янгон |
| Asia/Hovd | Ховд |
| Asia/Ulaanbaatar | Улан-Батор |
| Asia/Choibalsan | Чойбалсан |
| Asia/Macau | Макао |
| Pacific/Saipan | Сайпан |
| America/Martinique | Мартиника |
| Africa/Nouakchott | Нуакшот |
| America/Montserrat | Монтсеррат |
| Europe/Malta | Мальта |
| Indian/Mauritius | Маврикий |
| Indian/Maldives | Мальдивы |
| Africa/Blantyre | Блантайр |
| America/Tijuana | Тихуана |
| America/Hermosillo | Эрмосильо |
| America/Mazatlan | Масатлан |
| America/Chihuahua | Чиуауа |
| America/Bahia_Banderas | Баия-де-Бандерас |
| America/Ojinaga | Охинага |
| America/Monterrey | Монтеррей |
| America/Mexico_City | Мехико |
| America/Matamoros | Матаморос |
| America/Merida | Мерида |
| America/Cancun | Канкун |
| Asia/Kuala_Lumpur | Куала-Лумпур |
| Asia/Kuching | Кучинг |
| Africa/Maputo | Мапуту |
| Africa/Windhoek | Виндхук |
| Pacific/Noumea | Нумеа |
| Africa/Niamey | Ниамей |
| Pacific/Norfolk | Норфолк |
| Africa/Lagos | Лагос |
| America/Managua | Манагуа |
| Europe/Amsterdam | Амстердам |
| Europe/Oslo | Осло |
| Asia/Katmandu | Катманду |
| Pacific/Nauru | Науру |
| Pacific/Niue | Ниуэ |
| Pacific/Chatham | Чатем |
| Pacific/Auckland | Окленд |
| Asia/Muscat | Маскат |
| America/Panama | Панама |
| America/Lima | Лима |
| Pacific/Tahiti | Таити |
| Pacific/Marquesas | Маркизские о-ва |
| Pacific/Gambier | о-ва Гамбье |
| Pacific/Port_Moresby | Порт-Морсби |
| Pacific/Bougainville | Бугенвиль |
| Asia/Manila | Манила |
| Asia/Karachi | Карачи |
| Europe/Warsaw | Варшава |
| America/Miquelon | Микелон |
| Pacific/Pitcairn | Питкэрн |
| America/Puerto_Rico | Пуэрто-Рико |
| Asia/Gaza | Газа |
| Asia/Hebron | Хеврон |
| Atlantic/Azores | Азорские о-ва |
| Atlantic/Madeira | Мадейра |
| Europe/Lisbon | Лиссабон |
| Pacific/Palau | Палау |
| America/Asuncion | Асунсьон |
| Asia/Qatar | Катар |
| Indian/Reunion | Реюньон |
| Europe/Bucharest | Бухарест |
| Europe/Belgrade | Белград |
| Europe/Kaliningrad | Калининград |
| Europe/Simferopol | Симферополь |
| Europe/Moscow | Москва |
| Europe/Volgograd | Волгоград |
| Europe/Saratov | Саратов |
| Europe/Astrakhan | Астрахань |
| Europe/Ulyanovsk | Ульяновск |
| Europe/Kirov | Киров |
| Europe/Samara | Самара |
| Asia/Yekaterinburg | Екатеринбург |
| Asia/Omsk | Омск |
| Asia/Novosibirsk | Новосибирск |
| Asia/Barnaul | Барнаул |
| Asia/Tomsk | Томск |
| Asia/Novokuznetsk | Новокузнецк |
| Asia/Krasnoyarsk | Красноярск |
| Asia/Irkutsk | Иркутск |
| Asia/Chita | Чита |
| Asia/Yakutsk | Якутск |
| Asia/Vladivostok | Владивосток |
| Asia/Khandyga | Хандыга |
| Asia/Sakhalin | о-в Сахалин |
| Asia/Ust-Nera | Усть-Нера |
| Asia/Magadan | Магадан |
| Asia/Srednekolymsk | Среднеколымск |
| Asia/Kamchatka | Петропавловск-Камчатский |
| Asia/Anadyr | Анадырь |
| Africa/Kigali | Кигали |
| Asia/Riyadh | Эр-Рияд |
| Pacific/Guadalcanal | Гуадалканал |
| Indian/Mahe | Маэ |
| Africa/Khartoum | Хартум |
| Europe/Stockholm | Стокгольм |
| Asia/Singapore | Сингапур |
| Atlantic/St_Helena | о-в Святой Елены |
| Europe/Ljubljana | Любляна |
| Arctic/Longyearbyen | Лонгйир |
| Europe/Bratislava | Братислава |
| Africa/Freetown | Фритаун |
| Europe/San_Marino | Сан-Марино |
| Africa/Dakar | Дакар |
| Africa/Mogadishu | Могадишо |
| America/Paramaribo | Парамарибо |
| Africa/Juba | Джуба |
| Africa/Sao_Tome | Сан-Томе |
| America/El_Salvador | Сальвадор |
| America/Lower_Princes | Лоуэр-Принсес-Куортер |
| Asia/Damascus | Дамаск |
| Africa/Mbabane | Мбабане |
| America/Grand_Turk | Гранд-Терк |
| Africa/Ndjamena | Нджамена |
| Indian/Kerguelen | Кергелен |
| Africa/Lome | Ломе |
| Asia/Bangkok | Бангкок |
| Asia/Dushanbe | Душанбе |
| Pacific/Fakaofo | Факаофо |
| Asia/Dili | Дили |
| Asia/Ashgabat | Ашхабад |
| Africa/Tunis | Тунис |
| Pacific/Tongatapu | Тонгатапу |
| Europe/Istanbul | Стамбул |
| America/Port_of_Spain | Порт-оф-Спейн |
| Pacific/Funafuti | Фунафути |
| Asia/Taipei | Тайбэй |
| Africa/Dar_es_Salaam | Дар-эс-Салам |
| Europe/Uzhgorod | Ужгород |
| Europe/Kiev | Киев |
| Europe/Zaporozhye | Запорожье |
| Africa/Kampala | Кампала |
| Pacific/Midway | о-ва Мидуэй |
| Pacific/Wake | Уэйк |
| America/Adak | Адак |
| America/Nome | Ном |
| Pacific/Johnston | Джонстон |
| America/Anchorage | Анкоридж |
| America/Yakutat | Якутат |
| America/Sitka | Ситка |
| America/Juneau | Джуно |
| America/Metlakatla | Метлакатла |
| America/Los_Angeles | Лос-Анджелес |
| America/Boise | Бойсе |
| America/Phoenix | Финикс |
| America/Denver | Денвер |
| America/North_Dakota/Beulah | Бойла, Северная Дакота |
| America/North_Dakota/New_Salem | Нью-Сейлем, Северная Дакота |
| America/North_Dakota/Center | Центр, Северная Дакота |
| America/Chicago | Чикаго |
| America/Menominee | Меномини |
| America/Indiana/Vincennes | Винсеннес |
| America/Indiana/Petersburg | Питерсберг, Индиана |
| America/Indiana/Tell_City | Телл-Сити |
| America/Indiana/Knox | Нокс, Индиана |
| America/Indiana/Winamac | Уинамак |
| America/Indiana/Marengo | Маренго, Индиана |
| America/Indianapolis | Индианаполис |
| America/Louisville | Луисвилл |
| America/Indiana/Vevay | Вевей, Индиана |
| America/Kentucky/Monticello | Монтиселло, Кентукки |
| America/Detroit | Детройт |
| America/New_York | Нью-Йорк |
| America/Montevideo | Монтевидео |
| Asia/Samarkand | Самарканд |
| Asia/Tashkent | Ташкент |
| Europe/Vatican | Ватикан |
| America/St_Vincent | Сент-Винсент |
| America/Caracas | Каракас |
| America/Tortola | Тортола |
| America/St_Thomas | Сент-Томас |
| Asia/Saigon | Хошимин |
| Pacific/Efate | Эфате |
| Pacific/Wallis | Уоллис |
| Pacific/Apia | Апиа |
| Asia/Aden | Аден |
| Indian/Mayotte | Майотта |
| Africa/Johannesburg | Йоханнесбург |
| Africa/Lusaka | Лусака |
| Africa/Harare | Хараре |
| Acre | Акри времяАкри стандартное времяАкри летнее время |
| Afghanistan | Афганистан |
| Africa_Central | Центральная Африка |
| Africa_Eastern | Восточная Африка |
| Africa_Southern | Южная Африка |
| Africa_Western | Западная АфрикаЗападная Африка, стандартное времяЗападная Африка, летнее время |
| Alaska | АляскаАляска, стандартное времяАляска, летнее время |
| Almaty | Алма-Ата времяАлма-Ата стандартное времяАлма-Ата летнее время |
| Amazon | АмазонкаАмазонка, стандартное времяАмазонка, летнее время |
| America_Central | Центральная АмерикаЦентральная Америка, стандартное времяЦентральная Америка, летнее время |
| America_Eastern | Восточная АмерикаВосточная Америка, стандартное времяВосточная Америка, летнее время |
| America_Mountain | Горное время (Северная Америка)Стандартное горное время (Северная Америка)Летнее горное время (Северная Америка) |
| America_Pacific | Тихоокеанское времяТихоокеанское стандартное времяТихоокеанское летнее время |
| Anadyr | Время по АнадырюАнадырь стандартное времяАнадырь летнее время |
| Apia | АпиаАпиа, стандартное времяАпиа, летнее время |
| Aqtau | Актау времяАктау, стандартное времяАктау летнее время |
| Aqtobe | Актобе времяАктобе стандартное времяАктобе летнее время |
| Arabian | Саудовская АравияСаудовская Аравия, стандартное времяСаудовская Аравия, летнее время |
| Argentina | АргентинаАргентина, стандартное времяАргентина, летнее время |
| Argentina_Western | Западная АргентинаЗападная Аргентина, стандартное времяЗападная Аргентина, летнее время |
| Armenia | АрменияАрмения, стандартное времяАрмения, летнее время |
| Atlantic | Атлантическое времяАтлантическое стандартное времяАтлантическое летнее время |
| Australia_Central | Центральная АвстралияЦентральная Австралия, стандартное времяЦентральная Австралия, летнее время |
| Australia_CentralWestern | Центральная Австралия, западное времяЦентральная Австралия, западное стандартное времяЦентральная Австралия, западное летнее время |
| Australia_Eastern | Восточная АвстралияВосточная Австралия, стандартное времяВосточная Австралия, летнее время |
| Australia_Western | Западная АвстралияЗападная Австралия, стандартное времяЗападная Австралия, летнее время |
| Azerbaijan | АзербайджанАзербайджан, стандартное времяАзербайджан, летнее время |
| Azores | Азорские о-ваАзорские о-ва, стандартное времяАзорские о-ва, летнее время |
| Bangladesh | БангладешБангладеш, стандартное времяБангладеш, летнее время |
| Bhutan | Бутан |
| Bolivia | Боливия |
| Brasilia | БразилияБразилия, стандартное времяБразилия, летнее время |
| Brunei | Бруней-Даруссалам |
| Cape_Verde | Кабо-ВердеКабо-Верде, стандартное времяКабо-Верде, летнее время |
| Casey | Кейси |
| Chamorro | Чаморро |
| Chatham | ЧатемЧатем, стандартное времяЧатем, летнее время |
| Chile | ЧилиЧили, стандартное времяЧили, летнее время |
| China | КитайКитай, стандартное времяКитай, летнее время |
| Choibalsan | ЧойбалсанЧойбалсан, стандартное времяЧойбалсан, летнее время |
| Christmas | о-в Рождества |
| Cocos | Кокосовые о-ва |
| Colombia | КолумбияКолумбия, стандартное времяКолумбия, летнее время |
| Cook | Острова КукаОстрова Кука, стандартное времяОстрова Кука, полулетнее время |
| Cuba | КубаКуба, стандартное времяКуба, летнее время |
| Davis | Дейвис |
| DumontDUrville | Дюмон-д’Юрвиль |
| East_Timor | Восточный Тимор |
| Easter | О-в ПасхиО-в Пасхи, стандартное времяО-в Пасхи, летнее время |
| Ecuador | Эквадор |
| Europe_Central | Центральная ЕвропаЦентральная Европа, стандартное времяЦентральная Европа, летнее время |
| Europe_Eastern | Восточная ЕвропаВосточная Европа, стандартное времяВосточная Европа, летнее время |
| Europe_Further_Eastern | Минское время |
| Europe_Western | Западная ЕвропаЗападная Европа, стандартное времяЗападная Европа, летнее время |
| Falkland | Фолклендские о-ваФолклендские о-ва, стандартное времяФолклендские о-ва, летнее время |
| Fiji | ФиджиФиджи, стандартное времяФиджи, летнее время |
| French_Guiana | Французская Гвиана |
| French_Southern | Французские Южные и Антарктические территории |
| Galapagos | Галапагосские о-ва |
| Gambier | Гамбье |
| Georgia | ГрузияГрузия, стандартное времяГрузия, летнее время |
| Gilbert_Islands | о-ва Гилберта |
| GMT | Среднее время по Гринвичу |
| Greenland_Eastern | Восточная ГренландияВосточная Гренландия, стандарное времяВосточная Гренландия, летнее время |
| Greenland_Western | Западная ГренландияЗападная Гренландия, стандартное времяЗападная Гренландия, летнее время |
| Guam | Гуам |
| Gulf | Персидский залив |
| Guyana | Гайана |
| Hawaii_Aleutian | Гавайско-алеутское времяГавайско-алеутское стандартное времяГавайско-алеутское летнее время |
| Hong_Kong | ГонконгГонконг, стандартное времяГонконг, летнее время |
| Hovd | ХовдХовд, стандартное времяХовд, летнее время |
| India | Индия |
| Indian_Ocean | Индийский океан |
| Indochina | Индокитай |
| Indonesia_Central | Центральная Индонезия |
| Indonesia_Eastern | Восточная Индонезия |
| Indonesia_Western | Западная Индонезия |
| Iran | ИранИран, стандартное времяИран, летнее время |
| Irkutsk | ИркутскИркутск, стандартное времяИркутск, летнее время |
| Israel | ИзраильИзраиль, стандартное времяИзраиль, летнее время |
| Japan | ЯпонияЯпония, стандартное времяЯпония, летнее время |
| Kamchatka | Петропавловск-КамчатскийПетропавловск-Камчатский, стандартное времяПетропавловск-Камчатский, летнее время |
| Kazakhstan_Eastern | Восточный Казахстан |
| Kazakhstan_Western | Западный Казахстан |
| Korea | КореяКорея, стандартное времяКорея, летнее время |
| Kosrae | Косрае |
| Krasnoyarsk | КрасноярскКрасноярск, стандартное времяКрасноярск, летнее время |
| Kyrgystan | Киргизия |
| Lanka | Шри-Ланка |
| Line_Islands | о-ва Лайн |
| Lord_Howe | Лорд-ХауЛорд-Хау, стандартное времяЛорд-Хау, летнее время |
| Macau | МакаоМакао, стандартное времяМакао, летнее время |
| Macquarie | Маккуори |
| Magadan | МагаданМагадан, стандартное времяМагадан, летнее время |
| Malaysia | Малайзия |
| Maldives | Мальдивы |
| Marquesas | Маркизские о-ва |
| Marshall_Islands | Маршалловы Острова |
| Mauritius | МаврикийМаврикий, стандартное времяМаврикий, летнее время |
| Mawson | Моусон |
| Mexico_Northwest | Северо-западное мексиканское времяСеверо-западное мексиканское стандартное времяСеверо-западное мексиканское летнее время |
| Mexico_Pacific | Тихоокеанское мексиканское времяТихоокеанское мексиканское стандартное времяТихоокеанское мексиканское летнее время |
| Mongolia | Улан-БаторУлан-Батор, стандартное времяУлан-Батор, летнее время |
| Moscow | МоскваМосква, стандартное времяМосква, летнее время |
| Myanmar | Мьянма |
| Nauru | Науру |
| Nepal | Непал |
| New_Caledonia | Новая КаледонияНовая Каледония, стандартное времяНовая Каледония, летнее время |
| New_Zealand | Новая ЗеландияНовая Зеландия, стандартное времяНовая Зеландия, летнее время |
| Newfoundland | НьюфаундлендНьюфаундленд, стандартное времяНьюфаундленд, летнее время |
| Niue | Ниуэ |
| Norfolk | Норфолк |
| Noronha | Фернанду-ди-НороньяФернанду-ди-Норонья, стандартное времяФернанду-ди-Норонья, летнее время |
| North_Mariana | Северные Марианские о-ва |
| Novosibirsk | НовосибирскНовосибирск, стандартное времяНовосибирск, летнее время |
| Omsk | ОмскОмск, стандартное времяОмск, летнее время |
| Pakistan | ПакистанПакистан, стандартное времяПакистан, летнее время |
| Palau | Палау |
| Papua_New_Guinea | Папуа – Новая Гвинея |
| Paraguay | ПарагвайПарагвай, стандартное времяПарагвай, летнее время |
| Peru | ПеруПеру, стандартное времяПеру, летнее время |
| Philippines | ФилиппиныФилиппины, стандартное времяФилиппины, летнее время |
| Phoenix_Islands | о-ва Феникс |
| Pierre_Miquelon | Сен-Пьер и МикелонСен-Пьер и Микелон, стандартное времяСен-Пьер и Микелон, летнее время |
| Pitcairn | Питкэрн |
| Ponape | Понпеи |
| Pyongyang | Пхеньян |
| Qyzylorda | Кызылорда*Кызылорда, стандартное время*Кызылорда, летнее время* |
| Reunion | Реюньон |
| Rothera | Ротера |
| Sakhalin | СахалинСахалин, стандартное времяСахалин, летнее время |
| Samara | Время в СамареСамарское стандартное времяСамарское летнее время |
| Samoa | СамоаСамоа, стандартное времяСамоа, летнее время |
| Seychelles | Сейшельские острова |
| Singapore | Сингапур |
| Solomon | Соломоновы острова |
| South_Georgia | Южная Георгия |
| Suriname | Суринам |
| Syowa | Сёва |
| Tahiti | Таити |
| Taipei | ТайваньТайвань, стандартное времяТайвань, летнее время |
| Tajikistan | Таджикистан |
| Tokelau | Токелау |
| Tonga | ТонгаТонга, стандартное времяТонга, летнее время |
| Truk | Трук |
| Turkmenistan | ТуркменияТуркмения, стандартное времяТуркмения, летнее время |
| Tuvalu | Тувалу |
| Uruguay | УругвайУругвай, стандартное времяУругвай, летнее время |
| Uzbekistan | УзбекистанУзбекистан, стандартное времяУзбекистан, летнее время |
| Vanuatu | ВануатуВануату, стандартное времяВануату, летнее время |
| Venezuela | Венесуэла |
| Vladivostok | ВладивостокВладивосток, стандартное времяВладивосток, летнее время |
| Volgograd | ВолгоградВолгоград, стандартное времяВолгоград, летнее время |
| Vostok | Восток |
| Wake | Уэйк |
| Wallis | Уоллис и Футуна |
| Yakutsk | ЯкутскЯкутск, стандартное времяЯкутск, летнее время |
| Yekaterinburg | ЕкатеринбургЕкатеринбург, стандартное времяЕкатеринбург, летнее время |
## Numbers stuff
latnlatn1
| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | не число |
| Time separator (Hours:Minutes) | : |
#,##0.###0 тысяча0 тысячи0 тысяч0 тысячи00 тысяча00 тысячи00 тысяч00 тысячи000 тысяча000 тысячи000 тысяч000 тысячи0 миллион0 миллиона0 миллионов0 миллиона00 миллион00 миллиона00 миллионов00 миллиона000 миллион000 миллиона000 миллионов000 миллиона0 миллиард0 миллиарда0 миллиардов0 миллиарда00 миллиард00 миллиарда00 миллиардов00 миллиарда000 миллиард000 миллиарда000 миллиардов000 миллиарда0 триллион0 триллиона0 триллионов0 триллиона00 триллион00 триллиона00 триллионов00 триллиона000 триллион000 триллиона000 триллионов000 триллиона0 тыс'.'0 тыс'.'0 тыс'.'0 тыс'.'00 тыс'.'00 тыс'.'00 тыс'.'00 тыс'.'000 тыс'.'000 тыс'.'000 тыс'.'000 тыс'.'0 млн0 млн0 млн0 млн00 млн00 млн00 млн00 млн000 млн000 млн000 млн000 млн0 млрд0 млрд0 млрд0 млрд00 млрд00 млрд00 млрд00 млрд000 млрд000 млрд000 млрд000 млрд0 трлн0 трлн0 трлн0 трлн00 трлн00 трлн00 трлн00 трлн000 трлн000 трлн000 трлн000 трлн#E0#,##0 %#,##0.00 ¤#,##0.00 ¤0 тыс'.' ¤0 тыс'.' ¤0 тыс'.' ¤0 тыс'.' ¤00 тыс'.' ¤00 тыс'.' ¤00 тыс'.' ¤00 тыс'.' ¤000 тыс'.' ¤000 тыс'.' ¤000 тыс'.' ¤000 тыс'.' ¤0 млн ¤0 млн ¤0 млн ¤0 млн ¤00 млн ¤00 млн ¤00 млн ¤00 млн ¤000 млн ¤000 млн ¤000 млн ¤000 млн ¤0 млрд ¤0 млрд ¤0 млрд ¤0 млрд ¤00 млрд ¤00 млрд ¤00 млрд ¤00 млрд ¤000 млрд ¤000 млрд ¤000 млрд ¤000 млрд ¤0 трлн ¤0 трлн ¤0 трлн ¤0 трлн ¤00 трлн ¤00 трлн ¤00 трлн ¤00 трлн ¤000 трлн ¤000 трлн ¤000 трлн ¤000 трлн ¤
| one | {0} {1} |
| few | {0} {1} |
| many | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  | Андоррская песета |
| one | андоррская песета |
| few | андоррские песеты |
| many | андоррских песет |
| other | андоррских песет |
|  | дирхам ОАЭ |
| one | дирхам ОАЭ |
| few | дирхама ОАЭ |
| many | дирхамов ОАЭ |
| other | дирхама ОАЭ |
|  symbol | AED |
|  | Афгани (1927–2002) |
|  | афгани |
| one | афгани |
| few | афгани |
| many | афгани |
| other | афгани |
|  symbol | AFN |
|  | албанский лек |
| one | албанский лек |
| few | албанских лека |
| many | албанских леков |
| other | албанского лека |
|  symbol | ALL |
|  | армянский драм |
| one | армянский драм |
| few | армянских драма |
| many | армянских драмов |
| other | армянского драма |
|  symbol | AMD |
|  | нидерландский антильский гульден |
| one | нидерландский антильский гульден |
| few | нидерландских антильских гульдена |
| many | нидерландских антильских гульденов |
| other | нидерландского антильского гульдена |
|  symbol | ANG |
|  | ангольская кванза |
| one | ангольская кванза |
| few | ангольские кванзы |
| many | ангольских кванз |
| other | ангольской кванзы |
|  symbol | AOA |
| narrow symbol | Kz |
|  | Ангольская кванза (1977–1990) |
| one | ангольских кванз (1977–1991) |
| few | ангольские кванзы (1977–1991) |
| many | ангольских кванз (1977–1991) |
| other | ангольских кванз (1977–1991) |
|  | Ангольская новая кванза (1990–2000) |
|  | Ангольская кванза реюстадо (1995–1999) |
| one | ангольских кванз реюстадо (1995–1999) |
| few | ангольские кванзы реюстадо (1995–1999) |
| many | ангольских кванз реюстадо (1995–1999) |
| other | ангольских кванз реюстадо (1995–1999) |
|  | Аргентинский аустрал |
|  | Аргентинское песо (1983–1985) |
|  | аргентинское песо |
| one | аргентинское песо |
| few | аргентинских песо |
| many | аргентинских песо |
| other | аргентинского песо |
|  symbol | ARS |
| narrow symbol | $ |
|  | Австрийский шиллинг |
|  | австралийский доллар |
| one | австралийский доллар |
| few | австралийских доллара |
| many | австралийских долларов |
| other | австралийского доллара |
|  symbol | A$ |
| narrow symbol | $ |
|  | арубанский флорин |
| one | арубанский флорин |
| few | арубанских флорина |
| many | арубанских флоринов |
| other | арубанского флорина |
|  symbol | AWG |
|  | Старый азербайджанский манат |
|  | азербайджанский манат |
| one | азербайджанский манат |
| few | азербайджанских маната |
| many | азербайджанских манатов |
| other | азербайджанского маната |
|  symbol | AZN |
|  | Динар Боснии и Герцеговины |
|  | конвертируемая марка Боснии и Герцеговины |
| one | конвертируемая марка Боснии и Герцеговины |
| few | конвертируемые марки Боснии и Герцеговины |
| many | конвертируемых марок Боснии и Герцеговины |
| other | конвертируемой марки Боснии и Герцеговины |
|  symbol | BAM |
| narrow symbol | KM |
|  | барбадосский доллар |
| one | барбадосский доллар |
| few | барбадосских доллара |
| many | барбадосских долларов |
| other | барбадосского доллара |
|  symbol | BBD |
| narrow symbol | $ |
|  | бангладешская така |
| one | бангладешская така |
| few | бангладешские таки |
| many | бангладешских так |
| other | бангладешской таки |
|  symbol | BDT |
| narrow symbol | ৳ |
|  | Бельгийский франк (конвертируемый) |
|  | Бельгийский франк |
|  | Бельгийский франк (финансовый) |
|  | Лев |
|  | болгарский лев |
| one | болгарский лев |
| few | болгарских лева |
| many | болгарских левов |
| other | болгарского лева |
|  symbol | BGN |
|  | бахрейнский динар |
| one | бахрейнский динар |
| few | бахрейнских динара |
| many | бахрейнских динаров |
| other | бахрейнского динара |
|  symbol | BHD |
|  | бурундийский франк |
| one | бурундийский франк |
| few | бурундийских франка |
| many | бурундийских франков |
| other | бурундийского франка |
|  symbol | BIF |
|  | бермудский доллар |
| one | бермудский доллар |
| few | бермудских доллара |
| many | бермудских долларов |
| other | бермудского доллара |
|  symbol | BMD |
| narrow symbol | $ |
|  | брунейский доллар |
| one | брунейский доллар |
| few | брунейских доллара |
| many | брунейских долларов |
| other | брунейского доллара |
|  symbol | BND |
| narrow symbol | $ |
|  | боливийский боливиано |
| one | боливийский боливиано |
| few | боливийских боливиано |
| many | боливийских боливиано |
| other | боливийского боливиано |
|  symbol | BOB |
| narrow symbol | Bs |
|  | Боливийское песо |
|  | Боливийский мвдол |
|  | Бразильский новый крузейро (1967–1986) |
|  | Бразильское крузадо |
|  | Бразильский крузейро (1990–1993) |
|  | бразильский реал |
| one | бразильский реал |
| few | бразильских реала |
| many | бразильских реалов |
| other | бразильского реала |
|  symbol | R$ |
| narrow symbol | R$ |
|  | Бразильское новое крузадо |
|  | Бразильский крузейро |
|  | багамский доллар |
| one | багамский доллар |
| few | багамских доллара |
| many | багамских долларов |
| other | багамского доллара |
|  symbol | BSD |
| narrow symbol | $ |
|  | бутанский нгултрум |
| one | бутанский нгултрум |
| few | бутанских нгултрума |
| many | бутанских нгултрумов |
| other | бутанского нгултрума |
|  symbol | BTN |
|  | Джа |
|  | ботсванская пула |
| one | ботсванская пула |
| few | ботсванские пулы |
| many | ботсванских пул |
| other | ботсванской пулы |
|  symbol | BWP |
| narrow symbol | P |
|  | Белорусский рубль (1994–1999) |
|  | белорусский рубль |
| one | белорусский рубль |
| few | белорусских рубля |
| many | белорусских рублей |
| other | белорусского рубля |
|  symbol | BYN |
| narrow symbol | р. |
|  | Белорусский рубль (2000–2016) |
| one | белорусский рубль (2000–2016) |
| few | белорусских рубля (2000–2016) |
| many | белорусских рублей (2000–2016) |
| other | белорусского рубля (2000–2016) |
|  symbol | BYR |
|  | белизский доллар |
| one | белизский доллар |
| few | белизских доллара |
| many | белизских долларов |
| other | белизского доллара |
|  symbol | BZD |
| narrow symbol | $ |
|  | канадский доллар |
| one | канадский доллар |
| few | канадских доллара |
| many | канадских долларов |
| other | канадского доллара |
|  symbol | CA$ |
| narrow symbol | $ |
|  | конголезский франк |
| one | конголезский франк |
| few | конголезских франка |
| many | конголезских франков |
| other | конголезского франка |
|  symbol | CDF |
|  | WIR евро |
|  | швейцарский франк |
| one | швейцарский франк |
| few | швейцарских франка |
| many | швейцарских франков |
| other | швейцарского франка |
|  symbol | CHF |
|  | WIR франк |
|  | Условная расчетная единица Чили |
|  | чилийское песо |
| one | чилийское песо |
| few | чилийских песо |
| many | чилийских песо |
| other | чилийского песо |
|  symbol | CLP |
| narrow symbol | $ |
|  | китайский офшорный юань |
| one | китайский офшорный юань |
| few | китайских офшорных юаня |
| many | китайских офшорных юаней |
| other | китайского офшорного юаня |
|  symbol | CNH |
|  | китайский юань |
| one | китайский юань |
| few | китайских юаня |
| many | китайских юаней |
| other | китайского юаня |
|  symbol | CN¥ |
| narrow symbol | ¥ |
|  | колумбийское песо |
| one | колумбийское песо |
| few | колумбийских песо |
| many | колумбийских песо |
| other | колумбийского песо |
|  symbol | COP |
| narrow symbol | $ |
|  | Единица реальной стоимости Колумбии |
|  | костариканский колон |
| one | костариканский колон |
| few | костариканских колона |
| many | костариканских колонов |
| other | костариканского колона |
|  symbol | CRC |
| narrow symbol | ₡ |
|  | Старый Сербский динар |
|  | Чехословацкая твердая крона |
|  | кубинское конвертируемое песо |
| one | кубинское конвертируемое песо |
| few | кубинских конвертируемых песо |
| many | кубинских конвертируемых песо |
| other | кубинского конвертируемого песо |
|  symbol | CUC |
| narrow symbol | $ |
|  | кубинское песо |
| one | кубинское песо |
| few | кубинских песо |
| many | кубинских песо |
| other | кубинского песо |
|  symbol | CUP |
| narrow symbol | $ |
|  | эскудо Кабо-Верде |
| one | эскудо Кабо-Верде |
| few | эскудо Кабо-Верде |
| many | эскудо Кабо-Верде |
| other | эскудо Кабо-Верде |
|  symbol | CVE |
|  | Кипрский фунт |
|  | чешская крона |
| one | чешская крона |
| few | чешские кроны |
| many | чешских крон |
| other | чешской кроны |
|  symbol | CZK |
| narrow symbol | Kč |
|  | Восточногерманская марка |
|  | Немецкая марка |
|  | франк Джибути |
| one | франк Джибути |
| few | франка Джибути |
| many | франков Джибути |
| other | франка Джибути |
|  symbol | DJF |
|  | датская крона |
| one | датская крона |
| few | датские кроны |
| many | датских крон |
| other | датской кроны |
|  symbol | DKK |
| narrow symbol | kr |
|  | доминиканское песо |
| one | доминиканское песо |
| few | доминиканских песо |
| many | доминиканских песо |
| other | доминиканского песо |
|  symbol | DOP |
| narrow symbol | $ |
|  | алжирский динар |
| one | алжирский динар |
| few | алжирских динара |
| many | алжирских динаров |
| other | алжирского динара |
|  symbol | DZD |
|  | Эквадорский сукре |
|  | Постоянная единица стоимости Эквадора |
|  | Эстонская крона |
|  | египетский фунт |
| one | египетский фунт |
| few | египетских фунта |
| many | египетских фунтов |
| other | египетского фунта |
|  symbol | EGP |
| narrow symbol | E£ |
|  | эритрейская накфа |
| one | эритрейская накфа |
| few | эритрейские накфы |
| many | эритрейских накф |
| other | эритрейской накфы |
|  symbol | ERN |
|  | Испанская песета (А) |
|  | Испанская песета (конвертируемая) |
|  | Испанская песета |
|  | эфиопский быр |
| one | эфиопский быр |
| few | эфиопских быра |
| many | эфиопских быров |
| other | эфиопского быра |
|  symbol | ETB |
|  | евро |
| one | евро |
| few | евро |
| many | евро |
| other | евро |
|  symbol | € |
| narrow symbol | € |
|  | Финская марка |
|  | доллар Фиджи |
| one | доллар Фиджи |
| few | доллара Фиджи |
| many | долларов Фиджи |
| other | доллара Фиджи |
|  symbol | FJD |
| narrow symbol | $ |
|  | фунт Фолклендских островов |
| one | фунт Фолклендских островов |
| few | фунта Фолклендских островов |
| many | фунтов Фолклендских островов |
| other | фунта Фолклендских островов |
|  symbol | FKP |
| narrow symbol | £ |
|  | Французский франк |
|  | британский фунт стерлингов |
| one | британский фунт стерлингов |
| few | британских фунта стерлингов |
| many | британских фунтов стерлингов |
| other | британского фунта стерлингов |
|  symbol | £ |
| narrow symbol | £ |
|  | Грузинский купон |
|  | грузинский лари |
| one | грузинский лари |
| few | грузинских лари |
| many | грузинских лари |
| other | грузинского лари |
|  symbol | GEL |
| narrow symbol | ლ |
| variant symbol | ₾ |
|  | Ганский седи (1979–2007) |
|  | ганский седи |
| one | ганский седи |
| few | ганских седи |
| many | ганских седи |
| other | ганского седи |
|  symbol | GHS |
|  | гибралтарский фунт |
| one | гибралтарский фунт |
| few | гибралтарских фунта |
| many | гибралтарских фунтов |
| other | гибралтарского фунта |
|  symbol | GIP |
| narrow symbol | £ |
|  | гамбийский даласи |
| one | гамбийский даласи |
| few | гамбийских даласи |
| many | гамбийских даласи |
| other | гамбийского даласи |
|  symbol | GMD |
|  | гвинейский франк |
| one | гвинейский франк |
| few | гвинейских франка |
| many | гвинейских франков |
| other | гвинейского франка |
|  symbol | GNF |
| narrow symbol | FG |
|  | Гвинейская сили |
|  | Эквеле экваториальной Гвинеи |
|  | Греческая драхма |
|  | гватемальский кетсаль |
| one | гватемальский кетсаль |
| few | гватемальских кетсаля |
| many | гватемальских кетсалей |
| other | гватемальского кетсаля |
|  symbol | GTQ |
| narrow symbol | Q |
|  | Эскудо Португальской Гвинеи |
|  | Песо Гвинеи-Бисау |
|  | гайанский доллар |
| one | гайанский доллар |
| few | гайанских доллара |
| many | гайанских долларов |
| other | гайанского доллара |
|  symbol | GYD |
| narrow symbol | $ |
|  | гонконгский доллар |
| one | гонконгский доллар |
| few | гонконгских доллара |
| many | гонконгских долларов |
| other | гонконгского доллара |
|  symbol | HK$ |
| narrow symbol | $ |
|  | гондурасская лемпира |
| one | гондурасская лемпира |
| few | гондурасские лемпиры |
| many | гондурасских лемпир |
| other | гондурасской лемпиры |
|  symbol | HNL |
| narrow symbol | L |
|  | Хорватский динар |
|  | хорватская куна |
| one | хорватская куна |
| few | хорватские куны |
| many | хорватских кун |
| other | хорватской куны |
|  symbol | HRK |
| narrow symbol | kn |
|  | гаитянский гурд |
| one | гаитянский гурд |
| few | гаитянских гурда |
| many | гаитянских гурдов |
| other | гаитянского гурда |
|  symbol | HTG |
|  | венгерский форинт |
| one | венгерский форинт |
| few | венгерских форинта |
| many | венгерских форинтов |
| other | венгерского форинта |
|  symbol | HUF |
| narrow symbol | Ft |
|  | индонезийская рупия |
| one | индонезийская рупия |
| few | индонезийские рупии |
| many | индонезийских рупий |
| other | индонезийской рупии |
|  symbol | IDR |
| narrow symbol | Rp |
|  | Ирландский фунт |
|  | Израильский фунт |
|  | новый израильский шекель |
| one | новый израильский шекель |
| few | новых израильских шекеля |
| many | новых израильских шекелей |
| other | нового израильского шекеля |
|  symbol | ₪ |
| narrow symbol | ₪ |
|  | индийская рупия |
| one | индийская рупия |
| few | индийские рупии |
| many | индийских рупий |
| other | индийской рупии |
|  symbol | ₹ |
| narrow symbol | ₹ |
|  | иракский динар |
| one | иракский динар |
| few | иракских динара |
| many | иракских динаров |
| other | иракского динара |
|  symbol | IQD |
|  | иранский риал |
| one | иранский риал |
| few | иранских риала |
| many | иранских риалов |
| other | иранского риала |
|  symbol | IRR |
|  | исландская крона |
| one | исландская крона |
| few | исландские кроны |
| many | исландских крон |
| other | исландской кроны |
|  symbol | ISK |
| narrow symbol | kr |
|  | Итальянская лира |
|  | ямайский доллар |
| one | ямайский доллар |
| few | ямайских доллара |
| many | ямайских долларов |
| other | ямайского доллара |
|  symbol | JMD |
| narrow symbol | $ |
|  | иорданский динар |
| one | иорданский динар |
| few | иорданских динара |
| many | иорданских динаров |
| other | иорданского динара |
|  symbol | JOD |
|  | японская иена |
| one | японская иена |
| few | японские иены |
| many | японских иен |
| other | японской иены |
|  symbol | ¥ |
| narrow symbol | ¥ |
|  | кенийский шиллинг |
| one | кенийский шиллинг |
| few | кенийских шиллинга |
| many | кенийских шиллингов |
| other | кенийского шиллинга |
|  symbol | KES |
|  | киргизский сом |
| one | киргизский сом |
| few | киргизских сома |
| many | киргизских сомов |
| other | киргизского сома |
|  symbol | KGS |
|  | камбоджийский риель |
| one | камбоджийский риель |
| few | камбоджийских риеля |
| many | камбоджийских риелей |
| other | камбоджийского риеля |
|  symbol | KHR |
| narrow symbol | ៛ |
|  | франк Коморских островов |
| one | франк Коморских островов |
| few | франка Коморских островов |
| many | франков Коморских островов |
| other | франка Коморских островов |
|  symbol | KMF |
| narrow symbol | CF |
|  | северокорейская вона |
| one | северокорейская вона |
| few | северокорейские воны |
| many | северокорейских вон |
| other | северокорейской воны |
|  symbol | KPW |
| narrow symbol | ₩ |
|  | южнокорейская вона |
| one | южнокорейская вона |
| few | южнокорейские воны |
| many | южнокорейских вон |
| other | южнокорейской воны |
|  symbol | ₩ |
| narrow symbol | ₩ |
|  | кувейтский динар |
| one | кувейтский динар |
| few | кувейтских динара |
| many | кувейтских динаров |
| other | кувейтского динара |
|  symbol | KWD |
|  | доллар Каймановых островов |
| one | доллар Каймановых островов |
| few | доллара Каймановых островов |
| many | долларов Каймановых островов |
| other | доллара Каймановых островов |
|  symbol | KYD |
| narrow symbol | $ |
|  | казахский тенге |
| one | казахский тенге |
| few | казахских тенге |
| many | казахских тенге |
| other | казахского тенге |
|  symbol | KZT |
| narrow symbol | ₸ |
|  | лаосский кип |
| one | лаосский кип |
| few | лаосских кипа |
| many | лаосских кипов |
| other | лаосского кипа |
|  symbol | LAK |
| narrow symbol | ₭ |
|  | ливанский фунт |
| one | ливанский фунт |
| few | ливанских фунта |
| many | ливанских фунтов |
| other | ливанского фунта |
|  symbol | LBP |
| narrow symbol | L£ |
|  | шри-ланкийская рупия |
| one | шри-ланкийская рупия |
| few | шри-ланкийские рупии |
| many | шри-ланкийских рупий |
| other | шри-ланкийской рупии |
|  symbol | LKR |
| narrow symbol | Rs |
|  | либерийский доллар |
| one | либерийский доллар |
| few | либерийских доллара |
| many | либерийских долларов |
| other | либерийского доллара |
|  symbol | LRD |
| narrow symbol | $ |
|  | Лоти |
|  | Литовский лит |
| one | литовский лит |
| few | литовских лита |
| many | литовских литов |
| other | литовского лита |
|  symbol | LTL |
|  | Литовский талон |
|  | Конвертируемый франк Люксембурга |
|  | Люксембургский франк |
|  | Финансовый франк Люксембурга |
|  | Латвийский лат |
| one | латвийский лат |
| few | латвийских лата |
| many | латвийских латов |
| other | латвийского лата |
|  symbol | LVL |
|  | Латвийский рубль |
|  | ливийский динар |
| one | ливийский динар |
| few | ливийских динара |
| many | ливийских динаров |
| other | ливийского динара |
|  symbol | LYD |
|  | марокканский дирхам |
| one | марокканский дирхам |
| few | марокканских дирхама |
| many | марокканских дирхамов |
| other | марокканского дирхама |
|  symbol | MAD |
|  | Марокканский франк |
|  | молдавский лей |
| one | молдавский лей |
| few | молдавских лея |
| many | молдавских леев |
| other | молдавского лея |
|  symbol | MDL |
|  | малагасийский ариари |
| one | малагасийский ариари |
| few | малагасийских ариари |
| many | малагасийских ариари |
| other | малагасийского ариари |
|  symbol | MGA |
| narrow symbol | Ar |
|  | Малагасийский франк |
|  | македонский денар |
| one | македонский денар |
| few | македонских денара |
| many | македонских денаров |
| other | македонского денара |
|  symbol | MKD |
|  | Малийский франк |
|  | мьянманский кьят |
| one | мьянманский кьят |
| few | мьянманских кьята |
| many | мьянманских кьятов |
| other | мьянманского кьята |
|  symbol | MMK |
| narrow symbol | K |
|  | монгольский тугрик |
| one | монгольский тугрик |
| few | монгольских тугрика |
| many | монгольских тугриков |
| other | монгольского тугрика |
|  symbol | MNT |
| narrow symbol | ₮ |
|  | патака Макао |
| one | патака Макао |
| few | патаки Макао |
| many | патак Макао |
| other | патаки Макао |
|  symbol | MOP |
|  | мавританская угия |
| one | мавританская угия |
| few | мавританские угии |
| many | мавританских угий |
| other | мавританской угии |
|  symbol | MRO |
|  | Мальтийская лира |
|  | Мальтийский фунт |
|  | маврикийская рупия |
| one | маврикийская рупия |
| few | маврикийские рупии |
| many | маврикийских рупий |
| other | маврикийской рупии |
|  symbol | MUR |
| narrow symbol | Rs |
|  | мальдивская руфия |
| one | мальдивская руфия |
| few | мальдивские руфии |
| many | мальдивских руфий |
| other | мальдивской руфии |
|  symbol | MVR |
|  | малавийская квача |
| one | малавийская квача |
| few | малавийские квачи |
| many | малавийских квач |
| other | малавийской квачи |
|  symbol | MWK |
|  | мексиканское песо |
| one | мексиканское песо |
| few | мексиканских песо |
| many | мексиканских песо |
| other | мексиканского песо |
|  symbol | MX$ |
| narrow symbol | $ |
|  | Мексиканское серебряное песо (1861–1992) |
|  | Мексиканская пересчетная единица (UDI) |
|  | малайзийский ринггит |
| one | малайзийский ринггит |
| few | малайзийских ринггита |
| many | малайзийских ринггитов |
| other | малайзийского ринггита |
|  symbol | MYR |
| narrow symbol | RM |
|  | Мозамбикское эскудо |
|  | Старый мозамбикский метикал |
|  | мозамбикский метикал |
| one | мозамбикский метикал |
| few | мозамбикских метикала |
| many | мозамбикских метикалов |
| other | мозамбикского метикала |
|  symbol | MZN |
|  | доллар Намибии |
| one | доллар Намибии |
| few | доллара Намибии |
| many | долларов Намибии |
| other | доллара Намибии |
|  symbol | NAD |
| narrow symbol | $ |
|  | нигерийская найра |
| one | нигерийская найра |
| few | нигерийские найры |
| many | нигерийских найр |
| other | нигерийской найры |
|  symbol | NGN |
| narrow symbol | ₦ |
|  | Никарагуанская кордоба (1988–1991) |
|  | никарагуанская кордоба |
| one | никарагуанская кордоба |
| few | никарагуанские кордобы |
| many | никарагуанских кордоб |
| other | никарагуанской кордобы |
|  symbol | NIO |
| narrow symbol | C$ |
|  | Нидерландский гульден |
|  | норвежская крона |
| one | норвежская крона |
| few | норвежские кроны |
| many | норвежских крон |
| other | норвежской кроны |
|  symbol | NOK |
| narrow symbol | kr |
|  | непальская рупия |
| one | непальская рупия |
| few | непальские рупии |
| many | непальских рупий |
| other | непальской рупии |
|  symbol | NPR |
| narrow symbol | Rs |
|  | новозеландский доллар |
| one | новозеландский доллар |
| few | новозеландских доллара |
| many | новозеландских долларов |
| other | новозеландского доллара |
|  symbol | NZ$ |
| narrow symbol | $ |
|  | оманский риал |
| one | оманский риал |
| few | оманских риала |
| many | оманских риалов |
| other | оманского риала |
|  symbol | OMR |
|  | панамский бальбоа |
| one | панамский бальбоа |
| few | панамских бальбоа |
| many | панамских бальбоа |
| other | панамского бальбоа |
|  symbol | PAB |
|  | Перуанское инти |
|  | перуанский соль |
| one | перуанский соль |
| few | перуанских соля |
| many | перуанских солей |
| other | перуанского соля |
|  symbol | PEN |
|  | Перуанский соль (1863–1965) |
| one | перуанский соль (1863–1965) |
| few | перуанских соля (1863–1965) |
| many | перуанских солей (1863–1965) |
| other | перуанского соля (1863–1965) |
|  symbol | PES |
|  | кина Папуа – Новой Гвинеи |
| one | кина Папуа – Новой Гвинеи |
| few | кины Папуа – Новой Гвинеи |
| many | кин Папуа – Новой Гвинеи |
| other | кины Папуа – Новой Гвинеи |
|  symbol | PGK |
|  | филиппинское песо |
| one | филиппинское песо |
| few | филиппинских песо |
| many | филиппинских песо |
| other | филиппинского песо |
|  symbol | PHP |
| narrow symbol | ₱ |
|  | пакистанская рупия |
| one | пакистанская рупия |
| few | пакистанские рупии |
| many | пакистанских рупий |
| other | пакистанской рупии |
|  symbol | PKR |
| narrow symbol | Rs |
|  | польский злотый |
| one | польский злотый |
| few | польских злотых |
| many | польских злотых |
| other | польского злотого |
|  symbol | PLN |
| narrow symbol | zł |
|  | Злотый |
|  | Португальское эскудо |
|  | парагвайский гуарани |
| one | парагвайский гуарани |
| few | парагвайских гуарани |
| many | парагвайских гуарани |
| other | парагвайского гуарани |
|  symbol | PYG |
| narrow symbol | ₲ |
|  | катарский риал |
| one | катарский риал |
| few | катарских риала |
| many | катарских риалов |
| other | катарского риала |
|  symbol | QAR |
|  | Родезийский доллар |
|  | Старый Румынский лей |
|  | румынский лей |
| one | румынский лей |
| few | румынских лея |
| many | румынских леев |
| other | румынского лея |
|  symbol | RON |
| narrow symbol | L |
|  | сербский динар |
| one | сербский динар |
| few | сербских динара |
| many | сербских динаров |
| other | сербского динара |
|  symbol | RSD |
|  | российский рубль |
| one | российский рубль |
| few | российских рубля |
| many | российских рублей |
| other | российского рубля |
|  symbol | ₽ |
| narrow symbol | ₽ |
|  | Российский рубль (1991–1998) |
|  symbol | р. |
|  | франк Руанды |
| one | франк Руанды |
| few | франка Руанды |
| many | франков Руанды |
| other | франка Руанды |
|  symbol | RWF |
| narrow symbol | RF |
|  | саудовский риял |
| one | саудовский риял |
| few | саудовских рияла |
| many | саудовских риялов |
| other | саудовского рияла |
|  symbol | SAR |
|  | доллар Соломоновых островов |
| one | доллар Соломоновых островов |
| few | доллара Соломоновых островов |
| many | долларов Соломоновых островов |
| other | доллара Соломоновых островов |
|  symbol | SBD |
| narrow symbol | $ |
|  | сейшельская рупия |
| one | сейшельская рупия |
| few | сейшельские рупии |
| many | сейшельских рупий |
| other | сейшельской рупии |
|  symbol | SCR |
|  | Суданский динар |
|  | суданский фунт |
| one | суданский фунт |
| few | суданских фунта |
| many | суданских фунтов |
| other | суданского фунта |
|  symbol | SDG |
|  | Старый суданский фунт |
|  | шведская крона |
| one | шведская крона |
| few | шведские кроны |
| many | шведских крон |
| other | шведской кроны |
|  symbol | SEK |
| narrow symbol | kr |
|  | сингапурский доллар |
| one | сингапурский доллар |
| few | сингапурских доллара |
| many | сингапурских долларов |
| other | сингапурского доллара |
|  symbol | SGD |
| narrow symbol | $ |
|  | фунт острова Святой Елены |
| one | фунт острова Святой Елены |
| few | фунта острова Святой Елены |
| many | фунтов острова Святой Елены |
| other | фунта острова Святой Елены |
|  symbol | SHP |
| narrow symbol | £ |
|  | Словенский толар |
|  | Словацкая крона |
|  | леоне |
| one | леоне |
| few | леоне |
| many | леоне |
| other | леоне |
|  symbol | SLL |
|  | сомалийский шиллинг |
| one | сомалийский шиллинг |
| few | сомалийских шиллинга |
| many | сомалийских шиллингов |
| other | сомалийского шиллинга |
|  symbol | SOS |
|  | суринамский доллар |
| one | суринамский доллар |
| few | суринамских доллара |
| many | суринамских долларов |
| other | суринамского доллара |
|  symbol | SRD |
| narrow symbol | $ |
|  | Суринамский гульден |
|  | южносуданский фунт |
| one | южносуданский фунт |
| few | южносуданских фунта |
| many | южносуданских фунтов |
| other | южносуданского фунта |
|  symbol | SSP |
| narrow symbol | £ |
|  | добра Сан-Томе и Принсипи (1977–2017) |
| one | добра Сан-Томе и Принсипи (1977–2017) |
| few | добры Сан-Томе и Принсипи (1977–2017) |
| many | добр Сан-Томе и Принсипи (1977–2017) |
| other | добры Сан-Томе и Принсипи (1977–2017) |
|  symbol | STD |
|  | добра Сан-Томе и Принсипи |
| one | добра Сан-Томе и Принсипи |
| few | добры Сан-Томе и Принсипи |
| many | добр Сан-Томе и Принсипи |
| other | добры Сан-Томе и Принсипи |
|  symbol | STN |
| narrow symbol | Db |
|  | Рубль СССР |
|  | Сальвадорский колон |
|  | сирийский фунт |
| one | сирийский фунт |
| few | сирийских фунта |
| many | сирийских фунтов |
| other | сирийского фунта |
|  symbol | SYP |
| narrow symbol | £ |
|  | свазилендский лилангени |
| one | свазилендский лилангени |
| few | свазилендских лилангени |
| many | свазилендских лилангени |
| other | свазилендского лилангени |
|  symbol | SZL |
|  | таиландский бат |
| one | таиландский бат |
| few | таиландских бата |
| many | таиландских батов |
| other | таиландского бата |
|  symbol | ฿ |
| narrow symbol | ฿ |
|  | Таджикский рубль |
|  | таджикский сомони |
| one | таджикский сомони |
| few | таджикских сомони |
| many | таджикских сомони |
| other | таджикского сомони |
|  symbol | TJS |
|  | Туркменский манат |
|  | новый туркменский манат |
| one | новый туркменский манат |
| few | новых туркменских маната |
| many | новых туркменских манатов |
| other | нового туркменского маната |
|  symbol | ТМТ |
|  | тунисский динар |
| one | тунисский динар |
| few | тунисских динара |
| many | тунисских динаров |
| other | тунисского динара |
|  symbol | TND |
|  | тонганская паанга |
| one | тонганская паанга |
| few | тонганские паанги |
| many | тонганских паанг |
| other | тонганской паанги |
|  symbol | TOP |
| narrow symbol | T$ |
|  | Тиморское эскудо |
|  | Турецкая лира (1922–2005) |
| one | турецкая лира (1922–2005) |
| few | турецкие лиры (1922–2005) |
| many | турецких лир (1922–2005) |
| other | турецкой лиры (1922–2005) |
|  | турецкая лира |
| one | турецкая лира |
| few | турецкие лиры |
| many | турецких лир |
| other | турецкой лиры |
|  symbol | TRY |
| narrow symbol | ₺ |
| variant symbol | TL |
|  | доллар Тринидада и Тобаго |
| one | доллар Тринидада и Тобаго |
| few | доллара Тринидада и Тобаго |
| many | долларов Тринидада и Тобаго |
| other | доллара Тринидада и Тобаго |
|  symbol | TTD |
| narrow symbol | $ |
|  | новый тайваньский доллар |
| one | новый тайваньский доллар |
| few | новых тайваньских доллара |
| many | новых тайваньских долларов |
| other | нового тайваньского доллара |
|  symbol | NT$ |
| narrow symbol | NT$ |
|  | танзанийский шиллинг |
| one | танзанийский шиллинг |
| few | танзанийских шиллинга |
| many | танзанийских шиллингов |
| other | танзанийского шиллинга |
|  symbol | TZS |
|  | украинская гривна |
| one | украинская гривна |
| few | украинские гривны |
| many | украинских гривен |
| other | украинской гривны |
|  symbol | ₴ |
| narrow symbol | ₴ |
| variant symbol | грн. |
|  | Карбованец (украинский) |
|  | Старый угандийский шиллинг |
|  | угандийский шиллинг |
| one | угандийский шиллинг |
| few | угандийских шиллинга |
| many | угандийских шиллингов |
| other | угандийского шиллинга |
|  symbol | UGX |
|  | доллар США |
| one | доллар США |
| few | доллара США |
| many | долларов США |
| other | доллара США |
|  symbol | $ |
| narrow symbol | $ |
|  | Доллар США следующего дня |
|  | Доллар США текущего дня |
|  | Уругвайский песо (индекс инфляции) |
|  | Уругвайское старое песо (1975–1993) |
|  | уругвайское песо |
| one | уругвайское песо |
| few | уругвайских песо |
| many | уругвайских песо |
| other | уругвайского песо |
|  symbol | UYU |
| narrow symbol | $ |
|  | узбекский сум |
| one | узбекский сум |
| few | узбекских сума |
| many | узбекских сумов |
| other | узбекского сума |
|  symbol | UZS |
|  | Венесуэльский боливар (1871–2008) |
|  | венесуэльский боливар |
| one | венесуэльский боливар |
| few | венесуэльских боливара |
| many | венесуэльских боливаров |
| other | венесуэльского боливара |
|  symbol | VEF |
| narrow symbol | Bs |
|  | вьетнамский донг |
| one | вьетнамский донг |
| few | вьетнамских донга |
| many | вьетнамских донгов |
| other | вьетнамского донга |
|  symbol | ₫ |
| narrow symbol | ₫ |
|  | вату Вануату |
| one | вату Вануату |
| few | вату Вануату |
| many | вату Вануату |
| other | вату Вануату |
|  symbol | VUV |
|  | самоанская тала |
| one | самоанская тала |
| few | самоанские талы |
| many | самоанских тал |
| other | самоанской талы |
|  symbol | WST |
|  | франк КФА BEAC |
| one | франк КФА ВЕАС |
| few | франка КФА ВЕАС |
| many | франков КФА ВЕАС |
| other | франка КФА ВЕАС |
|  symbol | FCFA |
|  | Серебро |
|  | Золото |
|  | Европейская составная единица |
|  | Европейская денежная единица |
|  | расчетная единица европейского валютного соглашения (XBC) |
|  | расчетная единица европейского валютного соглашения (XBD) |
|  | восточно-карибский доллар |
| one | восточно-карибский доллар |
| few | восточно-карибских доллара |
| many | восточно-карибских долларов |
| other | восточно-карибского доллара |
|  symbol | EC$ |
| narrow symbol | $ |
|  | СДР (специальные права заимствования) |
|  | ЭКЮ (единица европейской валюты) |
|  | Французский золотой франк |
|  | Французский UIC-франк |
|  | франк КФА ВСЕАО |
| one | франк КФА ВСЕАО |
| few | франка КФА ВСЕАО |
| many | франков КФА ВСЕАО |
| other | франка КФА ВСЕАО |
|  symbol | CFA |
|  | Палладий |
|  | французский тихоокеанский франк |
| one | французский тихоокеанский франк |
| few | французских тихоокеанских франка |
| many | французских тихоокеанских франков |
| other | французского тихоокеанского франка |
|  symbol | CFPF |
|  | Платина |
|  | единица RINET-фондов |
|  | тестовый валютный код |
|  | неизвестная валюта |
| one | единица неизвестной валюты |
| few | единицы неизвестной валюты |
| many | единиц неизвестной валюты |
| other | единицы неизвестной валюты |
|  symbol | XXXX |
|  | Йеменский динар |
|  | йеменский риал |
| one | йеменский риал |
| few | йеменских риала |
| many | йеменских риалов |
| other | йеменского риала |
|  symbol | YER |
|  | Югославский твердый динар |
|  | Югославский новый динар |
|  | Югославский динар |
|  | Южноафриканский рэнд (финансовый) |
|  | южноафриканский рэнд |
| one | южноафриканский рэнд |
| few | южноафриканских рэнда |
| many | южноафриканских рэндов |
| other | южноафриканского рэнда |
|  symbol | ZAR |
| narrow symbol | R |
|  | Квача (замбийская) (1968–2012) |
| one | замбийская квача (1968–2012) |
| few | замбийские квачи (1968–2012) |
| many | замбийских квач (1968–2012) |
| other | замбийской квачи (1968–2012) |
|  | замбийская квача |
| one | замбийская квача |
| few | замбийские квачи |
| many | замбийских квач |
| other | замбийской квачи |
|  symbol | ZMW |
| narrow symbol | ZK |
|  | Новый заир |
|  | Заир |
|  | Доллар Зимбабве |
|  | Доллар Зимбабве (2009) |
Other stuff:
⩾{0}{0}–{1}
Examples:
| one example | из {0} книги за {0} день |
| few example | из {0} книг за {0} дня |
| many example | из {0} книг за {0} дней |
| other example | из {0} книги за {0} дня |
Сверните направо на {0}-м перекрестке.
## Units
| Code | Name |
| ---- | ---- |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | ускорение свободного падения |
| one | {0} g |
| few | {0} g |
| many | {0} g |
| other | {0} g |
| acceleration-meter-per-second-squared | ... |
|  | метры в секунду в квадрате |
| one | {0} метр в секунду в квадрате |
| few | {0} метра в секунду в квадрате |
| many | {0} метров в секунду в квадрате |
| other | {0} метра в секунду в квадрате |
| angle-revolution | ... |
|  | оборот |
| one | {0} оборот |
| few | {0} оборота |
| many | {0} оборотов |
| other | {0} оборота |
| angle-radian | ... |
|  | радианы |
| one | {0} радиан |
| few | {0} радиана |
| many | {0} радиан |
| other | {0} радиана |
| angle-degree | ... |
|  | градусы |
| one | {0} градус |
| few | {0} градуса |
| many | {0} градусов |
| other | {0} градуса |
| angle-arc-minute | ... |
|  | минуты |
| one | {0} минута |
| few | {0} минуты |
| many | {0} минут |
| other | {0} минуты |
| angle-arc-second | ... |
|  | секунды |
| one | {0} секунда |
| few | {0} секунды |
| many | {0} секунд |
| other | {0} секунды |
| area-square-kilometer | ... |
|  | квадратные километры |
| one | {0} квадратный километр |
| few | {0} квадратных километра |
| many | {0} квадратных километров |
| other | {0} квадратного километра |
{0} на квадратный километр
| area-hectare | ... |
|  | гектары |
| one | {0} гектар |
| few | {0} гектара |
| many | {0} гектаров |
| other | {0} гектара |
| area-square-meter | ... |
|  | квадратные метры |
| one | {0} квадратный метр |
| few | {0} квадратных метра |
| many | {0} квадратных метров |
| other | {0} квадратного метра |
{0} на квадратный метр
| area-square-centimeter | ... |
|  | квадратные сантиметры |
| one | {0} квадратный сантиметр |
| few | {0} квадратных сантиметра |
| many | {0} квадратных сантиметров |
| other | {0} квадратного сантиметра |
{0} на квадратный сантиметр
| area-square-mile | ... |
|  | квадратные мили |
| one | {0} квадратная миля |
| few | {0} квадратные мили |
| many | {0} квадратных миль |
| other | {0} квадратной мили |
{0} на квадратную милю
| area-acre | ... |
|  | акры |
| one | {0} акр |
| few | {0} акра |
| many | {0} акров |
| other | {0} акра |
| area-square-yard | ... |
|  | квадратные ярды |
| one | {0} квадратный ярд |
| few | {0} квадратных ярда |
| many | {0} квадратных ярдов |
| other | {0} квадратного ярда |
| area-square-foot | ... |
|  | квадратные футы |
| one | {0} квадратный фут |
| few | {0} квадратных фута |
| many | {0} квадратных футов |
| other | {0} квадратного фута |
| area-square-inch | ... |
|  | квадратные дюймы |
| one | {0} квадратный дюйм |
| few | {0} квадратных дюйма |
| many | {0} квадратных дюймов |
| other | {0} квадратного дюйма |
{0} на квадратный дюйм
| concentr-karat | ... |
|  | караты |
| one | {0} карат |
| few | {0} карата |
| many | {0} карат |
| other | {0} карата |
| concentr-milligram-per-deciliter | ... |
|  | миллиграммы на децилитр |
| one | {0} миллиграмм на децилитр |
| few | {0} миллиграмма на децилитр |
| many | {0} миллиграммов на децилитр |
| other | {0} миллиграмма на децилитр |
| concentr-millimole-per-liter | ... |
|  | миллимоли на литр |
| one | {0} миллимоль на литр |
| few | {0} миллимоля на литр |
| many | {0} миллимолей на литр |
| other | {0} миллимоля на литр |
| concentr-part-per-million | ... |
|  | миллионные доли |
| one | {0} миллионная доля |
| few | {0} миллионные доли |
| many | {0} миллионных долей |
| other | {0} миллионной доли |
| consumption-liter-per-kilometer | ... |
|  | литры на километр |
| one | {0} литр на километр |
| few | {0} литра на километр |
| many | {0} литров на километр |
| other | {0} литра на километр |
| consumption-liter-per-100kilometers | ... |
|  | литры на 100 километров |
| one | {0} литр на 100 километров |
| few | {0} литра на 100 километров |
| many | {0} литров на 100 километров |
| other | {0} литра на 100 километров |
| consumption-mile-per-gallon | ... |
|  | мили на галлон |
| one | {0} миля на галлон |
| few | {0} мили на галлон |
| many | {0} миль на галлон |
| other | {0} мили на галлон |
| consumption-mile-per-gallon-imperial | ... |
|  | мили на имп. галлон |
| one | {0} миля на имп. галлон |
| few | {0} мили на имп. галлон |
| many | {0} миль на имп. галлон |
| other | {0} мили на имп. галлон |
| digital-terabyte | ... |
|  | терабайты |
| one | {0} терабайт |
| few | {0} терабайта |
| many | {0} терабайт |
| other | {0} терабайта |
| digital-terabit | ... |
|  | терабиты |
| one | {0} терабит |
| few | {0} терабита |
| many | {0} терабит |
| other | {0} терабита |
| digital-gigabyte | ... |
|  | гигабайты |
| one | {0} гигабайт |
| few | {0} гигабайта |
| many | {0} гигабайт |
| other | {0} гигабайта |
| digital-gigabit | ... |
|  | гигабиты |
| one | {0} гигабит |
| few | {0} гигабита |
| many | {0} гигабит |
| other | {0} гигабита |
| digital-megabyte | ... |
|  | мегабайты |
| one | {0} мегабайт |
| few | {0} мегабайта |
| many | {0} мегабайт |
| other | {0} мегабайта |
| digital-megabit | ... |
|  | мегабиты |
| one | {0} мегабит |
| few | {0} мегабита |
| many | {0} мегабит |
| other | {0} мегабита |
| digital-kilobyte | ... |
|  | килобайты |
| one | {0} килобайт |
| few | {0} килобайта |
| many | {0} килобайт |
| other | {0} килобайта |
| digital-kilobit | ... |
|  | килобиты |
| one | {0} килобит |
| few | {0} килобита |
| many | {0} килобит |
| other | {0} килобита |
| digital-byte | ... |
|  | байты |
| one | {0} байт |
| few | {0} байта |
| many | {0} байт |
| other | {0} байта |
| digital-bit | ... |
|  | биты |
| one | {0} бит |
| few | {0} бита |
| many | {0} бит |
| other | {0} бита |
| duration-century | ... |
|  | века |
| one | {0} век |
| few | {0} века |
| many | {0} веков |
| other | {0} века |
| duration-year | ... |
|  | годы |
| one | {0} год |
| few | {0} года |
| many | {0} лет |
| other | {0} года |
{0} в год
| duration-month | ... |
|  | месяцы |
| one | {0} месяц |
| few | {0} месяца |
| many | {0} месяцев |
| other | {0} месяца |
{0} в месяц
| duration-week | ... |
|  | недели |
| one | {0} неделя |
| few | {0} недели |
| many | {0} недель |
| other | {0} недели |
{0} в неделю
| duration-day | ... |
|  | дни |
| one | {0} день |
| few | {0} дня |
| many | {0} дней |
| other | {0} дня |
{0} в день
| duration-hour | ... |
|  | часы |
| one | {0} час |
| few | {0} часа |
| many | {0} часов |
| other | {0} часа |
{0} в час
| duration-minute | ... |
|  | минуты |
| one | {0} минута |
| few | {0} минуты |
| many | {0} минут |
| other | {0} минуты |
{0} в минуту
| duration-second | ... |
|  | секунды |
| one | {0} секунда |
| few | {0} секунды |
| many | {0} секунд |
| other | {0} секунды |
{0} в секунду
| duration-millisecond | ... |
|  | миллисекунды |
| one | {0} миллисекунда |
| few | {0} миллисекунды |
| many | {0} миллисекунд |
| other | {0} миллисекунды |
| duration-microsecond | ... |
|  | микросекунды |
| one | {0} микросекунда |
| few | {0} микросекунды |
| many | {0} микросекунд |
| other | {0} микросекунды |
| duration-nanosecond | ... |
|  | наносекунды |
| one | {0} наносекунда |
| few | {0} наносекунды |
| many | {0} наносекунд |
| other | {0} наносекунды |
| electric-ampere | ... |
|  | амперы |
| one | {0} ампер |
| few | {0} ампера |
| many | {0} ампер |
| other | {0} ампера |
| electric-milliampere | ... |
|  | миллиамперы |
| one | {0} миллиампер |
| few | {0} миллиампера |
| many | {0} миллиампер |
| other | {0} миллиампера |
| electric-ohm | ... |
|  | омы |
| one | {0} ом |
| few | {0} ома |
| many | {0} ом |
| other | {0} ома |
| electric-volt | ... |
|  | вольты |
| one | {0} вольт |
| few | {0} вольта |
| many | {0} вольт |
| other | {0} вольта |
| energy-kilocalorie | ... |
|  | килокалории |
| one | {0} килокалория |
| few | {0} килокалории |
| many | {0} килокалорий |
| other | {0} килокалории |
| energy-calorie | ... |
|  | калории |
| one | {0} калория |
| few | {0} калории |
| many | {0} калорий |
| other | {0} калории |
| energy-foodcalorie | ... |
|  | калории |
| one | {0} калория |
| few | {0} калории |
| many | {0} калорий |
| other | {0} калории |
| energy-kilojoule | ... |
|  | килоджоули |
| one | {0} килоджоуль |
| few | {0} килоджоуля |
| many | {0} килоджоулей |
| other | {0} килоджоуля |
| energy-joule | ... |
|  | джоули |
| one | {0} джоуль |
| few | {0} джоуля |
| many | {0} джоулей |
| other | {0} джоуля |
| energy-kilowatt-hour | ... |
|  | киловатт-часы |
| one | {0} киловатт-час |
| few | {0} киловатт-часа |
| many | {0} киловатт-часов |
| other | {0} киловатт-часа |
| frequency-gigahertz | ... |
|  | гигагерцы |
| one | {0} гигагерц |
| few | {0} гигагерца |
| many | {0} гигагерц |
| other | {0} гигагерца |
| frequency-megahertz | ... |
|  | мегагерцы |
| one | {0} мегагерц |
| few | {0} мегагерца |
| many | {0} мегагерц |
| other | {0} мегагерца |
| frequency-kilohertz | ... |
|  | килогерцы |
| one | {0} килогерц |
| few | {0} килогерца |
| many | {0} килогерц |
| other | {0} килогерца |
| frequency-hertz | ... |
|  | герцы |
| one | {0} герц |
| few | {0} герца |
| many | {0} герц |
| other | {0} герца |
| length-kilometer | ... |
|  | километры |
| one | {0} километр |
| few | {0} километра |
| many | {0} километров |
| other | {0} километра |
{0} на километр
| length-meter | ... |
|  | метры |
| one | {0} метр |
| few | {0} метра |
| many | {0} метров |
| other | {0} метра |
{0} на метр
| length-decimeter | ... |
|  | дециметры |
| one | {0} дециметр |
| few | {0} дециметра |
| many | {0} дециметров |
| other | {0} дециметра |
| length-centimeter | ... |
|  | сантиметры |
| one | {0} сантиметр |
| few | {0} сантиметра |
| many | {0} сантиметров |
| other | {0} сантиметра |
{0} на сантиметр
| length-millimeter | ... |
|  | миллиметры |
| one | {0} миллиметр |
| few | {0} миллиметра |
| many | {0} миллиметров |
| other | {0} миллиметра |
| length-micrometer | ... |
|  | микрометры |
| one | {0} микрометр |
| few | {0} микрометра |
| many | {0} микрометров |
| other | {0} микрометра |
| length-nanometer | ... |
|  | нанометры |
| one | {0} нанометр |
| few | {0} нанометра |
| many | {0} нанометров |
| other | {0} нанометра |
| length-picometer | ... |
|  | пикометры |
| one | {0} пикометр |
| few | {0} пикометра |
| many | {0} пикометров |
| other | {0} пикометра |
| length-mile | ... |
|  | мили |
| one | {0} миля |
| few | {0} мили |
| many | {0} миль |
| other | {0} мили |
| length-yard | ... |
|  | ярды |
| one | {0} ярд |
| few | {0} ярда |
| many | {0} ярдов |
| other | {0} ярда |
| length-foot | ... |
|  | футы |
| one | {0} фут |
| few | {0} фута |
| many | {0} футов |
| other | {0} фута |
{0} на фут
| length-inch | ... |
|  | дюймы |
| one | {0} дюйм |
| few | {0} дюйма |
| many | {0} дюймов |
| other | {0} дюйма |
{0} на дюйм
| length-parsec | ... |
|  | парсеки |
| one | {0} парсек |
| few | {0} парсека |
| many | {0} парсеков |
| other | {0} парсека |
| length-light-year | ... |
|  | световые годы |
| one | {0} световой год |
| few | {0} световых года |
| many | {0} световых лет |
| other | {0} светового года |
| length-astronomical-unit | ... |
|  | астрономические единицы |
| one | {0} астрономическая единица |
| few | {0} астрономические единицы |
| many | {0} астрономических единиц |
| other | {0} астрономической единицы |
| length-furlong | ... |
|  | фурлонги |
| one | {0} фурлонг |
| few | {0} фурлонга |
| many | {0} фурлонгов |
| other | {0} фурлонга |
| length-fathom | ... |
|  | морские сажени |
| one | {0} морская сажень |
| few | {0} морских сажени |
| many | {0} морских саженей |
| other | {0} морской сажени |
| length-nautical-mile | ... |
|  | морские мили |
| one | {0} морская миля |
| few | {0} морские мили |
| many | {0} морских миль |
| other | {0} морской мили |
| length-mile-scandinavian | ... |
|  | скандинавские мили |
| one | {0} скандинавская миля |
| few | {0} скандинавские мили |
| many | {0} скандинавских миль |
| other | {0} скандинавской мили |
| length-point | ... |
|  | пункты |
| one | {0} пункт |
| few | {0} пункта |
| many | {0} пунктов |
| other | {0} пункта |
| light-lux | ... |
|  | люксы |
| one | {0} люкс |
| few | {0} люкса |
| many | {0} люкс |
| other | {0} люкса |
| mass-metric-ton | ... |
|  | тонны |
| one | {0} тонна |
| few | {0} тонны |
| many | {0} тонн |
| other | {0} тонны |
| mass-kilogram | ... |
|  | килограммы |
| one | {0} килограмм |
| few | {0} килограмма |
| many | {0} килограмм |
| other | {0} килограмма |
{0} на килограмм
| mass-gram | ... |
|  | граммы |
| one | {0} грамм |
| few | {0} грамма |
| many | {0} грамм |
| other | {0} грамма |
{0} на грамм
| mass-milligram | ... |
|  | миллиграммы |
| one | {0} миллиграмм |
| few | {0} миллиграмма |
| many | {0} миллиграммов |
| other | {0} миллиграмма |
| mass-microgram | ... |
|  | микрограммы |
| one | {0} микрограмм |
| few | {0} микрограмма |
| many | {0} микрограммов |
| other | {0} микрограмма |
| mass-ton | ... |
|  | американские тонны |
| one | {0} американская тонна |
| few | {0} американские тонны |
| many | {0} американских тонн |
| other | {0} американской тонны |
| mass-stone | ... |
|  | стоуны |
| one | {0} стоун |
| few | {0} стоуна |
| many | {0} стоунов |
| other | {0} стоуна |
| mass-pound | ... |
|  | фунты |
| one | {0} фунт |
| few | {0} фунта |
| many | {0} фунтов |
| other | {0} фунта |
{0} на фунт
| mass-ounce | ... |
|  | унции |
| one | {0} унция |
| few | {0} унции |
| many | {0} унций |
| other | {0} унции |
{0} на унцию
| mass-ounce-troy | ... |
|  | тройские унции |
| one | {0} тройская унция |
| few | {0} тройские унции |
| many | {0} тройских унций |
| other | {0} тройской унции |
| mass-carat | ... |
|  | караты |
| one | {0} карат |
| few | {0} карата |
| many | {0} карат |
| other | {0} карата |
| power-gigawatt | ... |
|  | гигаватты |
| one | {0} гигаватт |
| few | {0} гигаватта |
| many | {0} гигаватт |
| other | {0} гигаватта |
| power-megawatt | ... |
|  | мегаватты |
| one | {0} мегаватт |
| few | {0} мегаватта |
| many | {0} мегаватт |
| other | {0} мегаватта |
| power-kilowatt | ... |
|  | киловатты |
| one | {0} киловатт |
| few | {0} киловатта |
| many | {0} киловатт |
| other | {0} киловатта |
| power-watt | ... |
|  | ватты |
| one | {0} ватт |
| few | {0} ватта |
| many | {0} ватт |
| other | {0} ватта |
| power-milliwatt | ... |
|  | милливатты |
| one | {0} милливатт |
| few | {0} милливатта |
| many | {0} милливатт |
| other | {0} милливатта |
| power-horsepower | ... |
|  | лошадиные силы |
| one | {0} лошадиная сила |
| few | {0} лошадиные силы |
| many | {0} лошадиных сил |
| other | {0} лошадиной силы |
| pressure-hectopascal | ... |
|  | гектопаскали |
| one | {0} гектопаскаль |
| few | {0} гектопаскаля |
| many | {0} гектопаскалей |
| other | {0} гектопаскаля |
| pressure-millimeter-of-mercury | ... |
|  | миллиметры ртутного столба |
| one | {0} миллиметр ртутного столба |
| few | {0} миллиметра ртутного столба |
| many | {0} миллиметров ртутного столба |
| other | {0} миллиметра ртутного столба |
| pressure-pound-per-square-inch | ... |
|  | фунты на квадратный дюйм |
| one | {0} фунт на квадратный дюйм |
| few | {0} фунта на квадратный дюйм |
| many | {0} фунтов на квадратный дюйм |
| other | {0} фунта на квадратный дюйм |
| pressure-inch-hg | ... |
|  | дюймы ртутного столба |
| one | {0} дюйм ртутного столба |
| few | {0} дюйма ртутного столба |
| many | {0} дюймов ртутного столба |
| other | {0} дюйма ртутного столба |
| pressure-millibar | ... |
|  | миллибары |
| one | {0} миллибар |
| few | {0} миллибара |
| many | {0} миллибар |
| other | {0} миллибара |
| speed-kilometer-per-hour | ... |
|  | километры в час |
| one | {0} километр в час |
| few | {0} километра в час |
| many | {0} километров в час |
| other | {0} километра в час |
| speed-meter-per-second | ... |
|  | метры в секунду |
| one | {0} метр в секунду |
| few | {0} метра в секундыу |
| many | {0} метров в секунду |
| other | {0} метра в секунду |
| speed-mile-per-hour | ... |
|  | мили в час |
| one | {0} миля в час |
| few | {0} мили в час |
| many | {0} миль в час |
| other | {0} мили в час |
| speed-knot | ... |
|  | узел |
| one | {0} узел |
| few | {0} узла |
| many | {0} узлов |
| other | {0} узла |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| few | {0}° |
| many | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | градусы Цельсия |
| one | {0} градус Цельсия |
| few | {0} градуса Цельсия |
| many | {0} градусов Цельсия |
| other | {0} градуса Цельсия |
| temperature-fahrenheit | ... |
|  | градусы по Фаренгейту |
| one | {0} градус по Фаренгейту |
| few | {0} градуса по Фаренгейту |
| many | {0} градусов по Фаренгейту |
| other | {0} градуса по Фаренгейту |
| temperature-kelvin | ... |
|  | градусы по Кельвину |
| one | {0} градус по Кельвину |
| few | {0} градуса по Кельвину |
| many | {0} градусов по Кельвину |
| other | {0} градуса по Кельвину |
| volume-cubic-kilometer | ... |
|  | кубические километры |
| one | {0} кубический километр |
| few | {0} кубических километра |
| many | {0} кубических километров |
| other | {0} кубического километра |
| volume-cubic-meter | ... |
|  | кубические метры |
| one | {0} кубический метр |
| few | {0} кубических метра |
| many | {0} кубических метров |
| other | {0} кубического метра |
{0} на кубический метр
| volume-cubic-centimeter | ... |
|  | кубические сантиметры |
| one | {0} кубический сантиметр |
| few | {0} кубических сантиметра |
| many | {0} кубических сантиметров |
| other | {0} кубического сантиметра |
{0} на кубический сантиметр
| volume-cubic-mile | ... |
|  | кубические мили |
| one | {0} кубическая миля |
| few | {0} кубические мили |
| many | {0} кубических миль |
| other | {0} кубической мили |
| volume-cubic-yard | ... |
|  | кубические ярды |
| one | {0} кубический ярд |
| few | {0} кубических ярда |
| many | {0} кубических ярдов |
| other | {0} кубического ярда |
| volume-cubic-foot | ... |
|  | кубические футы |
| one | {0} кубический фут |
| few | {0} кубических фута |
| many | {0} кубических футов |
| other | {0} кубического фута |
| volume-cubic-inch | ... |
|  | кубические дюймы |
| one | {0} кубический дюйм |
| few | {0} кубических дюйма |
| many | {0} кубических дюймов |
| other | {0} кубического дюйма |
| volume-megaliter | ... |
|  | мегалитры |
| one | {0} мегалитр |
| few | {0} мегалитра |
| many | {0} мегалитров |
| other | {0} мегалитра |
| volume-hectoliter | ... |
|  | гектолитры |
| one | {0} гектолитр |
| few | {0} гектолитра |
| many | {0} гектолитров |
| other | {0} гектолитра |
| volume-liter | ... |
|  | литры |
| one | {0} литр |
| few | {0} литра |
| many | {0} литров |
| other | {0} литра |
{0} на литр
| volume-deciliter | ... |
|  | децилитры |
| one | {0} децилитр |
| few | {0} децилитра |
| many | {0} децилитров |
| other | {0} децилитра |
| volume-centiliter | ... |
|  | сантилитры |
| one | {0} сантилитр |
| few | {0} сантилитра |
| many | {0} сантилитров |
| other | {0} сантилитра |
| volume-milliliter | ... |
|  | миллилитры |
| one | {0} миллилитр |
| few | {0} миллилитра |
| many | {0} миллилитров |
| other | {0} миллилитра |
| volume-pint-metric | ... |
|  | метрические пинты |
| one | {0} метрическая пинта |
| few | {0} метрические пинты |
| many | {0} метрических пинт |
| other | {0} метрической пинты |
| volume-cup-metric | ... |
|  | метрические чашки |
| one | {0} метрическая чашка |
| few | {0} метрические чашки |
| many | {0} метрических чашек |
| other | {0} метрической чашки |
| volume-acre-foot | ... |
|  | акрофуты |
| one | {0} акрофут |
| few | {0} акрофута |
| many | {0} акрофутов |
| other | {0} акрофута |
| volume-gallon | ... |
|  | галлоны |
| one | {0} галлон |
| few | {0} галлона |
| many | {0} галлонов |
| other | {0} галлона |
{0} на галлон
| volume-gallon-imperial | ... |
|  | имп. галлоны |
| one | {0} имп. галлон |
| few | {0} имп. галлона |
| many | {0} имп. галлонов |
| other | {0} имп. галлона |
{0} на имп. галлон
| volume-quart | ... |
|  | кварты |
| one | {0} кварта |
| few | {0} кварты |
| many | {0} кварт |
| other | {0} кварты |
| volume-pint | ... |
|  | пинты |
| one | {0} пинта |
| few | {0} пинты |
| many | {0} пинт |
| other | {0} пинты |
| volume-cup | ... |
|  | чашки |
| one | {0} чашка |
| few | {0} чашки |
| many | {0} чашек |
| other | {0} чашки |
| volume-fluid-ounce | ... |
|  | жидкие унции |
| one | {0} жидкая унция |
| few | {0} жидкие унции |
| many | {0} жидких унций |
| other | {0} жидкой унции |
| volume-tablespoon | ... |
|  | столовые ложки |
| one | {0} столовая ложка |
| few | {0} столовые ложки |
| many | {0} столовых ложек |
| other | {0} столовой ложки |
| volume-teaspoon | ... |
|  | чайные ложки |
| one | {0} чайная ложка |
| few | {0} чайные ложки |
| many | {0} чайных ложек |
| other | {0} чайной ложки |
{0} восточной долготы{0} северной широты{0} южной широты{0} западной долготы
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | g |
| one | {0} g |
| few | {0} g |
| many | {0} g |
| other | {0} g |
| acceleration-meter-per-second-squared | ... |
|  | м/с² |
| one | {0} м/с² |
| few | {0} м/с² |
| many | {0} м/с² |
| other | {0} м/с² |
| angle-revolution | ... |
|  | об. |
| one | {0} об. |
| few | {0} об. |
| many | {0} об. |
| other | {0} об. |
| angle-radian | ... |
|  | рад |
| one | {0} рад |
| few | {0} рад |
| many | {0} рад |
| other | {0} рад |
| angle-degree | ... |
|  | ° |
| one | {0}° |
| few | {0}° |
| many | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | ′ |
| one | {0}′ |
| few | {0}′ |
| many | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | ″ |
| one | {0}″ |
| few | {0}″ |
| many | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
|  | км² |
| one | {0} км² |
| few | {0} км² |
| many | {0} км² |
| other | {0} км² |
{0}/км²
| area-hectare | ... |
|  | га |
| one | {0} га |
| few | {0} га |
| many | {0} га |
| other | {0} га |
| area-square-meter | ... |
|  | м² |
| one | {0} м² |
| few | {0} м² |
| many | {0} м² |
| other | {0} м² |
{0}/м²
| area-square-centimeter | ... |
|  | см² |
| one | {0} см² |
| few | {0} см² |
| many | {0} см² |
| other | {0} см² |
{0}/см²
| area-square-mile | ... |
|  | миля² |
| one | {0} миля² |
| few | {0} миля² |
| many | {0} миля² |
| other | {0} миля² |
{0}/миля²
| area-acre | ... |
|  | акр. |
| one | {0} акр |
| few | {0} акр. |
| many | {0} акр. |
| other | {0} акр. |
| area-square-yard | ... |
|  | ярд² |
| one | {0} ярд² |
| few | {0} ярд² |
| many | {0} ярд² |
| other | {0} ярд² |
| area-square-foot | ... |
|  | фут² |
| one | {0} фут² |
| few | {0} фут² |
| many | {0} фут² |
| other | {0} фут² |
| area-square-inch | ... |
|  | дюйм² |
| one | {0} дюйм² |
| few | {0} дюйм² |
| many | {0} дюйм² |
| other | {0} дюйм² |
{0}/дюйм²
| concentr-karat | ... |
|  | кар |
| one | {0} кар |
| few | {0} кар |
| many | {0} кар |
| other | {0} кар |
| concentr-milligram-per-deciliter | ... |
|  | мг/дл |
| one | {0} мг/дл |
| few | {0} мг/дл |
| many | {0} мг/дл |
| other | {0} мг/дл |
| concentr-millimole-per-liter | ... |
|  | ммоль/л |
| one | {0} ммоль/л |
| few | {0} ммоль/л |
| many | {0} ммоль/л |
| other | {0} ммоль/л |
| concentr-part-per-million | ... |
|  | ppm |
| one | {0} ppm |
| few | {0} ppm |
| many | {0} ppm |
| other | {0} ppm |
| consumption-liter-per-kilometer | ... |
|  | л/км |
| one | {0} л/км |
| few | {0} л/км |
| many | {0} л/км |
| other | {0} л/км |
| consumption-liter-per-100kilometers | ... |
|  | л/100 км |
| one | {0} л/100 км |
| few | {0} л/100 км |
| many | {0} л/100 км |
| other | {0} л/100 км |
| consumption-mile-per-gallon | ... |
|  | миль/гал |
| one | {0} миля/галл. |
| few | {0} мили/галл. |
| many | {0} миль/галл. |
| other | {0} мили/галл. |
| consumption-mile-per-gallon-imperial | ... |
|  | мили/имп. гал |
| one | {0} миля/имп. гал |
| few | {0} мили/имп. гал |
| many | {0} миль/имп. гал |
| other | {0} мили/имп. галл. |
| digital-terabyte | ... |
|  | ТБ |
| one | {0} ТБ |
| few | {0} ТБ |
| many | {0} ТБ |
| other | {0} ТБ |
| digital-terabit | ... |
|  | Тбит |
| one | {0} Тбит |
| few | {0} Тбит |
| many | {0} Тбит |
| other | {0} Тбит |
| digital-gigabyte | ... |
|  | ГБ |
| one | {0} ГБ |
| few | {0} ГБ |
| many | {0} ГБ |
| other | {0} ГБ |
| digital-gigabit | ... |
|  | Гбит |
| one | {0} Гбит |
| few | {0} Гбит |
| many | {0} Гбит |
| other | {0} Гбит |
| digital-megabyte | ... |
|  | МБ |
| one | {0} МБ |
| few | {0} МБ |
| many | {0} МБ |
| other | {0} МБ |
| digital-megabit | ... |
|  | Мбит |
| one | {0} Мбит |
| few | {0} Мбит |
| many | {0} Мбит |
| other | {0} Мбит |
| digital-kilobyte | ... |
|  | кБ |
| one | {0} кБ |
| few | {0} кБ |
| many | {0} кБ |
| other | {0} кБ |
| digital-kilobit | ... |
|  | кбит |
| one | {0} кбит |
| few | {0} кбит |
| many | {0} кбит |
| other | {0} кбит |
| digital-byte | ... |
|  | Б |
| one | {0} Б |
| few | {0} Б |
| many | {0} Б |
| other | {0} Б |
| digital-bit | ... |
|  | бит |
| one | {0} бит |
| few | {0} бита |
| many | {0} бит |
| other | {0} бита |
| duration-century | ... |
|  | в. |
| one | {0} в. |
| few | {0} в. |
| many | {0} в. |
| other | {0} в. |
| duration-year | ... |
|  | г. |
| one | {0} г. |
| few | {0} г. |
| many | {0} л. |
| other | {0} г. |
{0}/г
| duration-month | ... |
|  | мес. |
| one | {0} мес. |
| few | {0} мес. |
| many | {0} мес. |
| other | {0} мес. |
{0}/мес
| duration-week | ... |
|  | нед. |
| one | {0} нед. |
| few | {0} нед. |
| many | {0} нед. |
| other | {0} нед. |
{0}/нед
| duration-day | ... |
|  | дн. |
| one | {0} дн. |
| few | {0} дн. |
| many | {0} дн. |
| other | {0} дн. |
{0}/д
| duration-hour | ... |
|  | ч |
| one | {0} ч. |
| few | {0} ч. |
| many | {0} ч. |
| other | {0} ч. |
{0}/ч
| duration-minute | ... |
|  | мин |
| one | {0} мин. |
| few | {0} мин. |
| many | {0} мин. |
| other | {0} мин. |
{0}/мин
| duration-second | ... |
|  | с |
| one | {0} с. |
| few | {0} с. |
| many | {0} с. |
| other | {0} с. |
{0}/c
| duration-millisecond | ... |
|  | мс |
| one | {0} мс |
| few | {0} мс |
| many | {0} мс |
| other | {0} мс |
| duration-microsecond | ... |
|  | мкс |
| one | {0} мкс |
| few | {0} мкс |
| many | {0} мкс |
| other | {0} мкс |
| duration-nanosecond | ... |
|  | нс |
| one | {0} нс |
| few | {0} нс |
| many | {0} нс |
| other | {0} нс |
| electric-ampere | ... |
|  | А |
| one | {0} А |
| few | {0} А |
| many | {0} А |
| other | {0} А |
| electric-milliampere | ... |
|  | мА |
| one | {0} мА |
| few | {0} мА |
| many | {0} мА |
| other | {0} мА |
| electric-ohm | ... |
|  | Ом |
| one | {0} Ом |
| few | {0} Ом |
| many | {0} Ом |
| other | {0} Ом |
| electric-volt | ... |
|  | В |
| one | {0} В |
| few | {0} В |
| many | {0} В |
| other | {0} В |
| energy-kilocalorie | ... |
|  | ккал |
| one | {0} ккал |
| few | {0} ккал |
| many | {0} ккал |
| other | {0} ккал |
| energy-calorie | ... |
|  | кал |
| one | {0} кал |
| few | {0} кал |
| many | {0} кал |
| other | {0} кал |
| energy-foodcalorie | ... |
|  | кал |
| one | {0} кал |
| few | {0} кал |
| many | {0} кал |
| other | {0} кал |
| energy-kilojoule | ... |
|  | кДж |
| one | {0} кДж |
| few | {0} кДж |
| many | {0} кДж |
| other | {0} кДж |
| energy-joule | ... |
|  | Дж |
| one | {0} Дж |
| few | {0} Дж |
| many | {0} Дж |
| other | {0} Дж |
| energy-kilowatt-hour | ... |
|  | кВт⋅ч |
| one | {0} кВт⋅ч |
| few | {0} кВт⋅ч |
| many | {0} кВт⋅ч |
| other | {0} кВт⋅ч |
| frequency-gigahertz | ... |
|  | ГГц |
| one | {0} ГГц |
| few | {0} ГГц |
| many | {0} ГГц |
| other | {0} ГГц |
| frequency-megahertz | ... |
|  | МГц |
| one | {0} МГц |
| few | {0} МГц |
| many | {0} МГц |
| other | {0} МГц |
| frequency-kilohertz | ... |
|  | кГц |
| one | {0} кГц |
| few | {0} кГц |
| many | {0} кГц |
| other | {0} кГц |
| frequency-hertz | ... |
|  | Гц |
| one | {0} Гц |
| few | {0} Гц |
| many | {0} Гц |
| other | {0} Гц |
| length-kilometer | ... |
|  | км |
| one | {0} км |
| few | {0} км |
| many | {0} км |
| other | {0} км |
{0}/км
| length-meter | ... |
|  | м |
| one | {0} м |
| few | {0} м |
| many | {0} м |
| other | {0} м |
{0}/м
| length-decimeter | ... |
|  | дм |
| one | {0} дм |
| few | {0} дм |
| many | {0} дм |
| other | {0} дм |
| length-centimeter | ... |
|  | см |
| one | {0} см |
| few | {0} см |
| many | {0} см |
| other | {0} см |
{0}/см
| length-millimeter | ... |
|  | мм |
| one | {0} мм |
| few | {0} мм |
| many | {0} мм |
| other | {0} мм |
| length-micrometer | ... |
|  | мкм |
| one | {0} мкм |
| few | {0} мкм |
| many | {0} мкм |
| other | {0} мкм |
| length-nanometer | ... |
|  | нм |
| one | {0} нм |
| few | {0} нм |
| many | {0} нм |
| other | {0} нм |
| length-picometer | ... |
|  | пм |
| one | {0} пм |
| few | {0} пм |
| many | {0} пм |
| other | {0} пм |
| length-mile | ... |
|  | мили |
| one | {0} миля |
| few | {0} мили |
| many | {0} миль |
| other | {0} мили |
| length-yard | ... |
|  | ярд. |
| one | {0} ярд |
| few | {0} ярд. |
| many | {0} ярд. |
| other | {0} ярд. |
| length-foot | ... |
|  | фт |
| one | {0} фт |
| few | {0} фт |
| many | {0} фт |
| other | {0} фт |
{0}/фт
| length-inch | ... |
|  | дюйм. |
| one | {0} дюйм |
| few | {0} дюйм. |
| many | {0} дюйм. |
| other | {0} дюйм. |
{0}/дюйм
| length-parsec | ... |
|  | пк |
| one | {0} пк |
| few | {0} пк |
| many | {0} пк |
| other | {0} пк |
| length-light-year | ... |
|  | св. г. |
| one | {0} св. г. |
| few | {0} св. г. |
| many | {0} св. л. |
| other | {0} св. г. |
| length-astronomical-unit | ... |
|  | а. е. |
| one | {0} а. е. |
| few | {0} а. е. |
| many | {0} а. е. |
| other | {0} а. е. |
| length-furlong | ... |
|  | фурлонги |
| one | {0} фурл. |
| few | {0} фурл. |
| many | {0} фурл. |
| other | {0} фурл. |
| length-fathom | ... |
|  | мор. сажени |
| one | {0} мор. сажень |
| few | {0} мор. сажени |
| many | {0} мор. саженей |
| other | {0} мор. сажени |
| length-nautical-mile | ... |
|  | мор. мили |
| one | {0} мор. миля |
| few | {0} мор. мили |
| many | {0} мор. миль |
| other | {0} мор. мили |
| length-mile-scandinavian | ... |
|  | ск. мил. |
| one | {0} ск. мил. |
| few | {0} ск. мил. |
| many | {0} ск. мил. |
| other | {0} ск. мил. |
| length-point | ... |
|  | пкт |
| one | {0} пкт |
| few | {0} пкт |
| many | {0} пкт |
| other | {0} пкт |
| light-lux | ... |
|  | лк |
| one | {0} лк |
| few | {0} лк |
| many | {0} лк |
| other | {0} лк |
| mass-metric-ton | ... |
|  | т |
| one | {0} т |
| few | {0} т |
| many | {0} т |
| other | {0} т |
| mass-kilogram | ... |
|  | кг |
| one | {0} кг |
| few | {0} кг |
| many | {0} кг |
| other | {0} кг |
{0}/кг
| mass-gram | ... |
|  | г |
| one | {0} г |
| few | {0} г |
| many | {0} г |
| other | {0} г |
{0}/г
| mass-milligram | ... |
|  | мг |
| one | {0} мг |
| few | {0} мг |
| many | {0} мг |
| other | {0} мг |
| mass-microgram | ... |
|  | мкг |
| one | {0} мкг |
| few | {0} мкг |
| many | {0} мкг |
| other | {0} мкг |
| mass-ton | ... |
|  | амер. т |
| one | {0} амер. т |
| few | {0} амер. т |
| many | {0} амер. т |
| other | {0} амер. т |
| mass-stone | ... |
|  | стоуны |
| one | {0} стоун |
| few | {0} стоуна |
| many | {0} стоунов |
| other | {0} стоуна |
| mass-pound | ... |
|  | фунт. |
| one | {0} фунт. |
| few | {0} фунт. |
| many | {0} фунт. |
| other | {0} фунт. |
{0}/фунт
| mass-ounce | ... |
|  | унц. |
| one | {0} унц. |
| few | {0} унц. |
| many | {0} унц. |
| other | {0} унц. |
{0}/унц
| mass-ounce-troy | ... |
|  | тр. унц. |
| one | {0} тр. унц. |
| few | {0} тр. унц. |
| many | {0} тр. унц. |
| other | {0} тр. унц. |
| mass-carat | ... |
|  | кар |
| one | {0} кар |
| few | {0} кар |
| many | {0} кар |
| other | {0} кар |
| power-gigawatt | ... |
|  | ГВт |
| one | {0} ГВт |
| few | {0} ГВт |
| many | {0} ГВт |
| other | {0} ГВт |
| power-megawatt | ... |
|  | МВт |
| one | {0} МВт |
| few | {0} МВт |
| many | {0} МВт |
| other | {0} МВт |
| power-kilowatt | ... |
|  | кВт |
| one | {0} кВт |
| few | {0} кВт |
| many | {0} кВт |
| other | {0} кВт |
| power-watt | ... |
|  | Вт |
| one | {0} Вт |
| few | {0} Вт |
| many | {0} Вт |
| other | {0} Вт |
| power-milliwatt | ... |
|  | мВт |
| one | {0} мВт |
| few | {0} мВт |
| many | {0} мВт |
| other | {0} мВт |
| power-horsepower | ... |
|  | л.с. |
| one | {0} л.с. |
| few | {0} л.с. |
| many | {0} л.с. |
| other | {0} л.с. |
| pressure-hectopascal | ... |
|  | гПа |
| one | {0} гПа |
| few | {0} гПа |
| many | {0} гПа |
| other | {0} гПа |
| pressure-millimeter-of-mercury | ... |
|  | мм рт. ст. |
| one | {0} мм рт. ст. |
| few | {0} мм рт. ст. |
| many | {0} мм рт. ст. |
| other | {0} мм рт. ст. |
| pressure-pound-per-square-inch | ... |
|  | ф. на дюйм² |
| one | {0} ф./дюйм² |
| few | {0} ф./дюйм² |
| many | {0} ф./дюйм² |
| other | {0} ф./дюйм² |
| pressure-inch-hg | ... |
|  | д. рт. ст. |
| one | {0} д. рт. ст. |
| few | {0} д. рт. ст. |
| many | {0} д. рт. ст. |
| other | {0} д. рт. ст. |
| pressure-millibar | ... |
|  | мбар |
| one | {0} мбар |
| few | {0} мбар |
| many | {0} мбар |
| other | {0} мбар |
| speed-kilometer-per-hour | ... |
|  | км/ч |
| one | {0} км/ч |
| few | {0} км/ч |
| many | {0} км/ч |
| other | {0} км/ч |
| speed-meter-per-second | ... |
|  | м/с |
| one | {0} м/с |
| few | {0} м/с |
| many | {0} м/с |
| other | {0} м/с |
| speed-mile-per-hour | ... |
|  | мили/час |
| one | {0} миля/час |
| few | {0} мили/час |
| many | {0} миль/час |
| other | {0} мили/час |
| speed-knot | ... |
|  | уз |
| one | {0} уз |
| few | {0} уз |
| many | {0} уз |
| other | {0} уз |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| few | {0}° |
| many | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | °C |
| one | {0} °C |
| few | {0} °C |
| many | {0} °C |
| other | {0} °C |
| temperature-fahrenheit | ... |
|  | °F |
| one | {0}°F |
| few | {0}°F |
| many | {0}°F |
| other | {0}°F |
| temperature-kelvin | ... |
|  | K |
| one | {0} K |
| few | {0} K |
| many | {0} K |
| other | {0} K |
| volume-cubic-kilometer | ... |
|  | км³ |
| one | {0} км³ |
| few | {0} км³ |
| many | {0} км³ |
| other | {0} км³ |
| volume-cubic-meter | ... |
|  | м³ |
| one | {0} м³ |
| few | {0} м³ |
| many | {0} м³ |
| other | {0} м³ |
{0}/м³
| volume-cubic-centimeter | ... |
|  | см³ |
| one | {0} см³ |
| few | {0} см³ |
| many | {0} см³ |
| other | {0} см³ |
{0}/см³
| volume-cubic-mile | ... |
|  | миля³ |
| one | {0} миля³ |
| few | {0} мили³ |
| many | {0} миль³ |
| other | {0} мили³ |
| volume-cubic-yard | ... |
|  | ярд³ |
| one | {0} ярд³ |
| few | {0} ярд³ |
| many | {0} ярд³ |
| other | {0} ярд³ |
| volume-cubic-foot | ... |
|  | фут³ |
| one | {0} фут³ |
| few | {0} фут³ |
| many | {0} фут³ |
| other | {0} фут³ |
| volume-cubic-inch | ... |
|  | дюйм³ |
| one | {0} дюйм³ |
| few | {0} дюйм³ |
| many | {0} дюйм³ |
| other | {0} дюйм³ |
| volume-megaliter | ... |
|  | Мл |
| one | {0} Мл |
| few | {0} Мл |
| many | {0} Мл |
| other | {0} Мл |
| volume-hectoliter | ... |
|  | гл |
| one | {0} гл |
| few | {0} гл |
| many | {0} гл |
| other | {0} гл |
| volume-liter | ... |
|  | л |
| one | {0} л |
| few | {0} л |
| many | {0} л |
| other | {0} л |
{0}/л
| volume-deciliter | ... |
|  | дл |
| one | {0} дл |
| few | {0} дл |
| many | {0} дл |
| other | {0} дл |
| volume-centiliter | ... |
|  | сл |
| one | {0} сл |
| few | {0} сл |
| many | {0} сл |
| other | {0} сл |
| volume-milliliter | ... |
|  | мл |
| one | {0} мл |
| few | {0} мл |
| many | {0} мл |
| other | {0} мл |
| volume-pint-metric | ... |
|  | мпт |
| one | {0} мпт |
| few | {0} мпт |
| many | {0} мпт |
| other | {0} мпт |
| volume-cup-metric | ... |
|  | м. чаш. |
| one | {0} м. чаш. |
| few | {0} м. чаш. |
| many | {0} м. чаш. |
| other | {0} м. чаш. |
| volume-acre-foot | ... |
|  | акрофут. |
| one | {0} акрофут |
| few | {0} акрофут. |
| many | {0} акрофут. |
| other | {0} акрофут. |
| volume-gallon | ... |
|  | гал. |
| one | {0} гал. |
| few | {0} гал. |
| many | {0} гал. |
| other | {0} гал. |
{0}/гал
| volume-gallon-imperial | ... |
|  | имп. гал. |
| one | {0} имп. гал. |
| few | {0} имп. гал. |
| many | {0} имп. гал. |
| other | {0} имп. гал. |
{0}/имп. гал
| volume-quart | ... |
|  | кварт. |
| one | {0} кварт. |
| few | {0} кварт. |
| many | {0} кварт. |
| other | {0} кварт. |
| volume-pint | ... |
|  | пинт. |
| one | {0} пинт. |
| few | {0} пинт. |
| many | {0} пинт. |
| other | {0} пинт. |
| volume-cup | ... |
|  | чаш. |
| one | {0} чаш. |
| few | {0} чаш. |
| many | {0} чаш. |
| other | {0} чаш. |
| volume-fluid-ounce | ... |
|  | жидк. унц. |
| one | {0} жидк. унц. |
| few | {0} жидк. унц. |
| many | {0} жидк. унц. |
| other | {0} жидк. унц. |
| volume-tablespoon | ... |
|  | ст. л. |
| one | {0} ст. л. |
| few | {0} ст. л. |
| many | {0} ст. л. |
| other | {0} ст. л. |
| volume-teaspoon | ... |
|  | ч. л. |
| one | {0} ч. л. |
| few | {0} ч. л. |
| many | {0} ч. л. |
| other | {0} ч. л. |
{0} в. д.{0} с. ш.{0} ю. ш.{0} з. д.
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | g |
| one | {0} G |
| few | {0} G |
| many | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
|  | м/с² |
| one | {0} м/с² |
| few | {0} м/с² |
| many | {0} м/с² |
| other | {0} м/с² |
| angle-degree | ... |
| one | {0}° |
| few | {0}° |
| many | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
| one | {0}′ |
| few | {0}′ |
| many | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
| one | {0}″ |
| few | {0}″ |
| many | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
| one | {0} км² |
| few | {0} км² |
| many | {0} км² |
| other | {0} км² |
| area-hectare | ... |
| one | {0} га |
| few | {0} га |
| many | {0} га |
| other | {0} га |
| area-square-meter | ... |
| one | {0} м² |
| few | {0} м² |
| many | {0} м² |
| other | {0} м² |
| area-square-mile | ... |
| one | {0} кв. миля |
| few | {0} кв. мили |
| many | {0} кв. миль |
| other | {0} кв. мили |
| area-acre | ... |
| one | {0} акр |
| few | {0} акра |
| many | {0} акров |
| other | {0} акра |
| area-square-foot | ... |
| one | {0} кв. фут |
| few | {0} кв. фута |
| many | {0} кв. футов |
| other | {0} кв. фута |
| consumption-liter-per-100kilometers | ... |
|  | л/100 км |
| one | {0} л/100 км |
| few | {0} л/100 км |
| many | {0} л/100 км |
| other | {0} л/100 км |
| duration-century | ... |
|  | в. |
| one | {0} в. |
| few | {0} в. |
| many | {0} в. |
| other | {0} в. |
| duration-year | ... |
|  | г. |
| one | {0} г. |
| few | {0} г. |
| many | {0} л. |
| other | {0} г. |
{0}/г.
| duration-month | ... |
|  | м. |
| one | {0} м. |
| few | {0} м. |
| many | {0} м. |
| other | {0} м. |
{0}/м.
| duration-week | ... |
|  | н. |
| one | {0} н. |
| few | {0} н. |
| many | {0} н. |
| other | {0} н. |
{0}/н.
| duration-day | ... |
|  | д. |
| one | {0} д. |
| few | {0} д. |
| many | {0} д. |
| other | {0} д. |
{0}/д.
| duration-hour | ... |
|  | ч |
| one | {0} ч |
| few | {0} ч |
| many | {0} ч |
| other | {0} ч |
{0}/ч.
| duration-minute | ... |
|  | мин |
| one | {0} мин |
| few | {0} мин |
| many | {0} мин |
| other | {0} мин |
{0}/мин.
| duration-second | ... |
|  | c |
| one | {0} с |
| few | {0} с |
| many | {0} с |
| other | {0} с |
{0}/c
| duration-millisecond | ... |
|  | мс |
| one | {0} мс |
| few | {0} мс |
| many | {0} мс |
| other | {0} мс |
| duration-microsecond | ... |
|  | мкс |
| one | {0} мкс |
| few | {0} мкс |
| many | {0} мкс |
| other | {0} мкс |
| duration-nanosecond | ... |
|  | нс |
| one | {0} нс |
| few | {0} нс |
| many | {0} нс |
| other | {0} нс |
| length-kilometer | ... |
|  | км |
| one | {0} км |
| few | {0} км |
| many | {0} км |
| other | {0} км |
{0}/км
| length-meter | ... |
|  | м |
| one | {0} м |
| few | {0} м |
| many | {0} м |
| other | {0} м |
{0}/м
| length-decimeter | ... |
|  | дм |
| one | {0} дм |
| few | {0} дм |
| many | {0} дм |
| other | {0} дм |
| length-centimeter | ... |
|  | см |
| one | {0} см |
| few | {0} см |
| many | {0} см |
| other | {0} см |
{0}/см
| length-millimeter | ... |
|  | мм |
| one | {0} мм |
| few | {0} мм |
| many | {0} мм |
| other | {0} мм |
| length-micrometer | ... |
|  | мкм |
| one | {0} мкм |
| few | {0} мкм |
| many | {0} мкм |
| other | {0} мкм |
| length-nanometer | ... |
|  | нм |
| one | {0} нм |
| few | {0} нм |
| many | {0} нм |
| other | {0} нм |
| length-picometer | ... |
|  | пм |
| one | {0} pm |
| few | {0} pm |
| many | {0} pm |
| other | {0} pm |
| length-mile | ... |
|  | мл. |
| one | {0} миля |
| few | {0} миль |
| many | {0} миль |
| other | {0} мили |
| length-yard | ... |
|  | ярд. |
| one | {0} ярд |
| few | {0} ярда |
| many | {0} ярдов |
| other | {0} ярда |
| length-foot | ... |
|  | фт |
| one | {0} фт |
| few | {0} фт |
| many | {0} фт |
| other | {0} фт |
{0}/фт
| length-inch | ... |
|  | дюйм. |
| one | {0} дюйм |
| few | {0} дюйма |
| many | {0} дюймов |
| other | {0} дюйма |
{0}/дюйм.
| length-parsec | ... |
|  | пк |
| one | {0} пк |
| few | {0} пк |
| many | {0} пк |
| other | {0} пк |
| length-light-year | ... |
|  | св. годы |
| one | {0} св. г. |
| few | {0} св. г. |
| many | {0} св. л. |
| other | {0} св. г. |
| length-astronomical-unit | ... |
|  | а. е. |
| one | {0} а. е. |
| few | {0} а. е. |
| many | {0} а. е. |
| other | {0} а. е. |
| length-furlong | ... |
|  | фрл |
| one | {0} фрл |
| few | {0} фрл |
| many | {0} фрл |
| other | {0} фрл |
| length-fathom | ... |
|  | м. саж. |
| one | {0} м. саж. |
| few | {0} м. саж. |
| many | {0} м. саж. |
| other | {0} м. саж. |
| length-nautical-mile | ... |
|  | мор. мили |
| one | {0} м. мл. |
| few | {0} м. мл. |
| many | {0} м. мл. |
| other | {0} м. мл. |
| length-mile-scandinavian | ... |
|  | ск. мл. |
| one | {0} ск. мл. |
| few | {0} ск. мл. |
| many | {0} ск. мл. |
| other | {0} ск. мл. |
| length-point | ... |
|  | пкт |
| one | {0} пкт |
| few | {0} пкт |
| many | {0} пкт |
| other | {0} пкт |
| mass-metric-ton | ... |
|  | т |
| one | {0} т |
| few | {0} т |
| many | {0} т |
| other | {0} т |
| mass-kilogram | ... |
|  | кг |
| one | {0} кг |
| few | {0} кг |
| many | {0} кг |
| other | {0} кг |
{0}/кг
| mass-gram | ... |
|  | г |
| one | {0} г |
| few | {0} г |
| many | {0} г |
| other | {0} г |
{0}/г
| mass-milligram | ... |
|  | мг |
| one | {0} мг |
| few | {0} мг |
| many | {0} мг |
| other | {0} мг |
| mass-microgram | ... |
|  | мкг |
| one | {0} мкг |
| few | {0} мкг |
| many | {0} мкг |
| other | {0} мкг |
| mass-ton | ... |
|  | ам. т |
| one | {0} ам. т |
| few | {0} ам. т |
| many | {0} ам. т |
| other | {0} ам. т |
| mass-stone | ... |
|  | стн |
| one | {0} стн |
| few | {0} стн |
| many | {0} стн |
| other | {0} стн |
| mass-pound | ... |
|  | фнт |
| one | {0} lb |
| few | {0} lb |
| many | {0} lb |
| other | {0} lb |
{0}/фнт
| mass-ounce | ... |
|  | унц. |
| one | {0} oz |
| few | {0} oz |
| many | {0} oz |
| other | {0} oz |
{0}/унц.
| mass-ounce-troy | ... |
|  | тр. унц. |
| one | {0} тр. унц. |
| few | {0} тр. унц. |
| many | {0} тр. унц. |
| other | {0} тр. унц. |
| mass-carat | ... |
|  | кар |
| one | {0} кар |
| few | {0} кар |
| many | {0} кар |
| other | {0} кар |
| power-kilowatt | ... |
| one | {0} кВт |
| few | {0} кВт |
| many | {0} кВт |
| other | {0} кВт |
| power-watt | ... |
| one | {0} Вт |
| few | {0} Вт |
| many | {0} Вт |
| other | {0} Вт |
| power-horsepower | ... |
| one | {0} л.с. |
| few | {0} л.с. |
| many | {0} л.с. |
| other | {0} л.с. |
| pressure-hectopascal | ... |
|  | гПа |
| one | {0} гПа |
| few | {0} гПа |
| many | {0} гПа |
| other | {0} гПа |
| pressure-millimeter-of-mercury | ... |
|  | мм рт. ст. |
| one | {0} мм рт. ст. |
| few | {0} мм рт. ст. |
| many | {0} мм рт. ст. |
| other | {0} мм рт. ст. |
| pressure-pound-per-square-inch | ... |
|  | ф. на дюйм² |
| one | {0} ф./дюйм² |
| few | {0} ф./дюйм² |
| many | {0} ф./дюйм² |
| other | {0} ф./дюйм² |
| pressure-inch-hg | ... |
|  | д. рт. ст. |
| one | {0} inHg |
| few | {0} inHg |
| many | {0} inHg |
| other | {0} inHg |
| pressure-millibar | ... |
|  | мбар |
| one | {0} мбар |
| few | {0} мбар |
| many | {0} мбар |
| other | {0} мбар |
| speed-kilometer-per-hour | ... |
|  | км/ч |
| one | {0} км/ч |
| few | {0} км/ч |
| many | {0} км/ч |
| other | {0} км/ч |
| speed-meter-per-second | ... |
|  | м/с |
| one | {0} м/с |
| few | {0} м/с |
| many | {0} м/с |
| other | {0} м/с |
| speed-mile-per-hour | ... |
|  | мили/час |
| one | {0} миль/ч |
| few | {0} миль/ч |
| many | {0} миль/ч |
| other | {0} миль/ч |
| speed-knot | ... |
|  | уз |
| one | {0} уз |
| few | {0} уз |
| many | {0} уз |
| other | {0} уз |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| few | {0}° |
| many | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | °C |
| one | {0} °C |
| few | {0} °C |
| many | {0} °C |
| other | {0} °C |
| temperature-fahrenheit | ... |
|  | °F |
| one | {0}°F |
| few | {0}°F |
| many | {0}°F |
| other | {0}°F |
| temperature-kelvin | ... |
|  | K |
| one | {0} K |
| few | {0} K |
| many | {0} K |
| other | {0} K |
| volume-cubic-kilometer | ... |
| one | {0} км³ |
| few | {0} км³ |
| many | {0} км³ |
| other | {0} км³ |
| volume-cubic-mile | ... |
| one | {0} куб. миля |
| few | {0} куб. мили |
| many | {0} куб. мили |
| other | {0} куб. мили |
| volume-liter | ... |
|  | л |
| one | {0} л |
| few | {0} л |
| many | {0} л |
| other | {0} л |
{0} в. д.{0} с. ш.{0} ю. ш.{0} з. д.h:mmh:mm:ssm:ss
## Lists
| List type | Patterns |
|  | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} и {1} |
| 2 | {0} и {1} |
| or | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} или {1} |
| 2 | {0} или {1} |
| standard-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} и {1} |
| 2 | {0} и {1} |
| unit | ... |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
| unit-narrow | ... |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
| unit-short | ... |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
## POSIX
да:днет:н
## Character sets
| Set | Name |
| --- | ---- |
| all | {0} — все |
| category-list | {0}: {1} |
| compatibility | {0} — совместимые |
| enclosed | {0} — вложенные |
| extended | {0} — расширенные |
| historic | {0} — исторические |
| miscellaneous | {0} — разное |
| other | {0} — другое |
| scripts | письменности — {0} |
| onestrokes | {0} черта |
| fewstrokes | {0} черты |
| manystrokes | {0} черт |
| otherstrokes | {0} черты |
| activities | занятия |
| african_scripts | письменности Африки |
| american_scripts | письменности Америки |
| animal | животные |
| animals_nature | животные и природа |
| arrows | стрелки |
| body | тело |
| box_drawing | псевдографика |
| braille | шрифт Брайля |
| building | здания |
| bullets_stars | маркеры списка/звезды |
| consonantal_jamo | согласные чамо |
| currency_symbols | символы валюты |
| dash_connector | тире/связка |
| digits | цифры |
| dingbats | дингбаты |
| divination_symbols | оккультные символы |
| downwards_arrows | стрелки вниз |
| downwards_upwards_arrows | стрелки вверх и вниз |
| east_asian_scripts | письменности Восточной Азии |
| emoji | эмодзи |
| european_scripts | письменности Европы |
| female | женщины |
| flag | флаги |
| flags | флаги |
| food_drink | еда и напитки |
| format | форматирование |
| format_whitespace | форматирование и пробелы |
| full_width_form_variant | варианты формы в полную ширину |
| geometric_shapes | геометрические фигуры |
| half_width_form_variant | варианты формы в половину ширины |
| han_characters | китайские символы |
| han_radicals | иероглифические ключи |
| hanja | ханча |
| hanzi_simplified | упрощенные китайские иероглифы |
| hanzi_traditional | традиционные китайские иероглифы |
| heart | сердца |
| historic_scripts | историческая письменность |
| ideographic_desc_characters | символы описания иероглифов |
| japanese_kana | кана |
| kanbun | камбун |
| kanji | кандзи |
| keycap | клавиши |
| leftwards_arrows | стрелки влево |
| leftwards_rightwards_arrows | стрелки влево и вправо |
| letterlike_symbols | буквенные символы |
| limited_use | ограниченное использование |
| male | мужчины |
| math_symbols | математические символы |
| middle_eastern_scripts | письменности Среднего Востока |
| miscellaneous | разное |
| modern_scripts | современная письменность |
| modifier | модификаторы |
| musical_symbols | музыкальные символы |
| nature | природа |
| nonspacing | непротяженные символы |
| numbers | числа |
| objects | объекты |
| other | другое |
| paired | парные символы |
| person | люди |
| phonetic_alphabet | фонетический алфавит |
| pictographs | пиктограммы |
| place | места |
| plant | растения |
| punctuation | пунктуационные знаки |
| rightwards_arrows | стрелки вправо |
| sign_standard_symbols | знаки/стандартные символы |
| small_form_variant | маленькие варианты формы |
| smiley | смайлики |
| smileys_people | смайлики и люди |
| south_asian_scripts | письменности Южной Азии |
| southeast_asian_scripts | письменности Юго-Восточной Азии |
| spacing | промежутки |
| sport | спорт |
| symbols | символы |
| technical_symbols | технические символы |
| tone_marks | метки тона |
| travel | путешествия |
| travel_places | путешествия и места |
| upwards_arrows | стрелки вверх |
| variant_forms | вариативные формы |
| vocalic_jamo | гласные чамо |
| weather | погода |
| western_asian_scripts | письменности Западной Азии |
| whitespace | пробелы |
## Font stuff
| Font feature | Name |
| "axis" ital | курсив |
| "axis" opsz | оптический размер |
| "axis" slnt | наклон |
| "axis" wdth | ширина |
| "axis" wght | толщина |
| "style" ital1 | рукописный |
| "style" opsz18 | титульный |
| "style" opsz72 | показать |
| "style" opsz144 | плакат |
| "style" slnt-12 | скошенный с наклоном |
| "style" slnt0 | прямой |
| "style" slnt12 | с наклоном |
| "style" slnt24 | сверхскошенный |
| "style" wdth50 | ультрасжатый |
| "style" wdth50 | ультраузкий |
| "style" wdth62.5 | сверхсжатый |
| "style" wdth62.5 | сверхузкий |
| "style" wdth62.5 | сверхсуженный |
| "style" wdth75 | сжатый |
| "style" wdth75 | суженный |
| "style" wdth87.5 | полусжатый |
| "style" wdth100 | нормальный |
| "style" wdth112.5 | полурасширенный |
| "style" wdth112.5 | полурастянутый |
| "style" wdth125 | расширенный |
| "style" wdth125 | широкий |
| "style" wdth150 | сверхрасширенный |
| "style" wdth150 | сверхрастянутый |
| "style" wdth150 | сверхширокий |
| "style" wdth200 | ультрасширенный |
| "style" wdth200 | ультрарастянутый |
| "style" wght100 | тонкий |
| "style" wght200 | сверхлегкий |
| "style" wght200 | ультралегкий |
| "style" wght300 | светлый |
| "style" wght350 | полулегкий |
| "style" wght380 | книжный |
| "style" wght400 | обычный |
| "style" wght500 | средний |
| "style" wght600 | полужирный |
| "style" wght700 | жирный |
| "style" wght800 | сверхжирный |
| "style" wght800 | ультражирный |
| "style" wght900 | черный |
| "style" wght900 | тяжелый |
| "style" wght950 | сверхчерный |
| "style" wght950 | ультратяжелый |
| "style" wght950 | ультрачерный |
| "feature" afrc | дроби с вертикальной чертой |
| "feature" cpsp | интервал между заглавными |
| "feature" dlig | необязательные лигатуры |
| "feature" frac | дроби с диагональной чертой |
| "feature" lnum | выравнивание цифр |
| "feature" onum | старые рисунки |
| "feature" ordn | порядковые числительные |
| "feature" pnum | пропорциональные цифры |
| "feature" smcp | малые прописные |
| "feature" tnum | табличные цифры |
| "feature" zero | нуль |
