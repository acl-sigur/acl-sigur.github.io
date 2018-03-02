
---
layout: default
title: "CLDR Russian (via LDML2markdown)"
---

## CLDR core data for Russian


**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ↴ |
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[{а\u0301} {е\u0301} {и\u0301} {о\u0301} {у\u0301} {ы\u0301} {э\u0301} {ю\u0301} {я\u0301}]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ы Э Ю Я]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ‚ " “ „ « » ( ) \[ \] \{ \} § @ * / \& #]` |
| Orientation | left-to-right |
| Orientation |  top-to-bottom |
| Plural rules | ↴ |
| plural one example | из {0} книги за {0} день |
| plural few example | из {0} книг за {0} дня |
| plural many example | из {0} книг за {0} дней |
| plural other example | из {0} книги за {0} дня |
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


#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | янв. |
| month, 2, abbreviated, format | февр. |
| month, 3, abbreviated, format | мар. |
| month, 4, abbreviated, format | апр. |
| month, 5, abbreviated, format | мая |
| month, 6, abbreviated, format | июн. |
| month, 7, abbreviated, format | июл. |
| month, 8, abbreviated, format | авг. |
| month, 9, abbreviated, format | сент. |
| month, 10, abbreviated, format | окт. |
| month, 11, abbreviated, format | нояб. |
| month, 12, abbreviated, format | дек. |
| month, 1, narrow, format | Я |
| month, 2, narrow, format | Ф |
| month, 3, narrow, format | М |
| month, 4, narrow, format | А |
| month, 5, narrow, format | М |
| month, 6, narrow, format | И |
| month, 7, narrow, format | И |
| month, 8, narrow, format | А |
| month, 9, narrow, format | С |
| month, 10, narrow, format | О |
| month, 11, narrow, format | Н |
| month, 12, narrow, format | Д |
| month, 1, wide, format | января |
| month, 2, wide, format | февраля |
| month, 3, wide, format | марта |
| month, 4, wide, format | апреля |
| month, 5, wide, format | мая |
| month, 6, wide, format | июня |
| month, 7, wide, format | июля |
| month, 8, wide, format | августа |
| month, 9, wide, format | сентября |
| month, 10, wide, format | октября |
| month, 11, wide, format | ноября |
| month, 12, wide, format | декабря |
| month, 1, abbreviated, stand-alone | янв. |
| month, 2, abbreviated, stand-alone | февр. |
| month, 3, abbreviated, stand-alone | март |
| month, 4, abbreviated, stand-alone | апр. |
| month, 5, abbreviated, stand-alone | май |
| month, 6, abbreviated, stand-alone | июнь |
| month, 7, abbreviated, stand-alone | июль |
| month, 8, abbreviated, stand-alone | авг. |
| month, 9, abbreviated, stand-alone | сент. |
| month, 10, abbreviated, stand-alone | окт. |
| month, 11, abbreviated, stand-alone | нояб. |
| month, 12, abbreviated, stand-alone | дек. |
| month, 1, narrow, stand-alone | Я |
| month, 2, narrow, stand-alone | Ф |
| month, 3, narrow, stand-alone | М |
| month, 4, narrow, stand-alone | А |
| month, 5, narrow, stand-alone | М |
| month, 6, narrow, stand-alone | И |
| month, 7, narrow, stand-alone | И |
| month, 8, narrow, stand-alone | А |
| month, 9, narrow, stand-alone | С |
| month, 10, narrow, stand-alone | О |
| month, 11, narrow, stand-alone | Н |
| month, 12, narrow, stand-alone | Д |
| month, 1, wide, stand-alone | январь |
| month, 2, wide, stand-alone | февраль |
| month, 3, wide, stand-alone | март |
| month, 4, wide, stand-alone | апрель |
| month, 5, wide, stand-alone | май |
| month, 6, wide, stand-alone | июнь |
| month, 7, wide, stand-alone | июль |
| month, 8, wide, stand-alone | август |
| month, 9, wide, stand-alone | сентябрь |
| month, 10, wide, stand-alone | октябрь |
| month, 11, wide, stand-alone | ноябрь |
| month, 12, wide, stand-alone | декабрь |
| (week)day, sun, abbreviated, format | вс |
| (week)day, mon, abbreviated, format | пн |
| (week)day, tue, abbreviated, format | вт |
| (week)day, wed, abbreviated, format | ср |
| (week)day, thu, abbreviated, format | чт |
| (week)day, fri, abbreviated, format | пт |
| (week)day, sat, abbreviated, format | сб |
| (week)day, sun, narrow, format | вс |
| (week)day, mon, narrow, format | пн |
| (week)day, tue, narrow, format | вт |
| (week)day, wed, narrow, format | ср |
| (week)day, thu, narrow, format | чт |
| (week)day, fri, narrow, format | пт |
| (week)day, sat, narrow, format | сб |
| (week)day, sun, short, format | вс |
| (week)day, mon, short, format | пн |
| (week)day, tue, short, format | вт |
| (week)day, wed, short, format | ср |
| (week)day, thu, short, format | чт |
| (week)day, fri, short, format | пт |
| (week)day, sat, short, format | сб |
| (week)day, sun, wide, format | воскресенье |
| (week)day, mon, wide, format | понедельник |
| (week)day, tue, wide, format | вторник |
| (week)day, wed, wide, format | среда |
| (week)day, thu, wide, format | четверг |
| (week)day, fri, wide, format | пятница |
| (week)day, sat, wide, format | суббота |
| (week)day, sun, abbreviated, stand-alone | вс |
| (week)day, mon, abbreviated, stand-alone | пн |
| (week)day, tue, abbreviated, stand-alone | вт |
| (week)day, wed, abbreviated, stand-alone | ср |
| (week)day, thu, abbreviated, stand-alone | чт |
| (week)day, fri, abbreviated, stand-alone | пт |
| (week)day, sat, abbreviated, stand-alone | сб |
| (week)day, sun, narrow, stand-alone | В |
| (week)day, mon, narrow, stand-alone | П |
| (week)day, tue, narrow, stand-alone | В |
| (week)day, wed, narrow, stand-alone | С |
| (week)day, thu, narrow, stand-alone | Ч |
| (week)day, fri, narrow, stand-alone | П |
| (week)day, sat, narrow, stand-alone | С |
| (week)day, sun, short, stand-alone | вс |
| (week)day, mon, short, stand-alone | пн |
| (week)day, tue, short, stand-alone | вт |
| (week)day, wed, short, stand-alone | ср |
| (week)day, thu, short, stand-alone | чт |
| (week)day, fri, short, stand-alone | пт |
| (week)day, sat, short, stand-alone | сб |
| (week)day, sun, wide, stand-alone | воскресенье |
| (week)day, mon, wide, stand-alone | понедельник |
| (week)day, tue, wide, stand-alone | вторник |
| (week)day, wed, wide, stand-alone | среда |
| (week)day, thu, wide, stand-alone | четверг |
| (week)day, fri, wide, stand-alone | пятница |
| (week)day, sat, wide, stand-alone | суббота |
| quarter, 1, abbreviated, format | 1-й кв. |
| quarter, 2, abbreviated, format | 2-й кв. |
| quarter, 3, abbreviated, format | 3-й кв. |
| quarter, 4, abbreviated, format | 4-й кв. |
| quarter, 1, narrow, format | 1 |
| quarter, 2, narrow, format | 2 |
| quarter, 3, narrow, format | 3 |
| quarter, 4, narrow, format | 4 |
| quarter, 1, wide, format | 1-й квартал |
| quarter, 2, wide, format | 2-й квартал |
| quarter, 3, wide, format | 3-й квартал |
| quarter, 4, wide, format | 4-й квартал |
| quarter, 1, abbreviated, stand-alone | 1-й кв. |
| quarter, 2, abbreviated, stand-alone | 2-й кв. |
| quarter, 3, abbreviated, stand-alone | 3-й кв. |
| quarter, 4, abbreviated, stand-alone | 4-й кв. |
| quarter, 1, narrow, stand-alone | 1 |
| quarter, 2, narrow, stand-alone | 2 |
| quarter, 3, narrow, stand-alone | 3 |
| quarter, 4, narrow, stand-alone | 4 |
| quarter, 1, wide, stand-alone | 1-й квартал |
| quarter, 2, wide, stand-alone | 2-й квартал |
| quarter, 3, wide, stand-alone | 3-й квартал |
| quarter, 4, wide, stand-alone | 4-й квартал |
| period of day, midnight, abbreviated, format | полн. |
| period of day, am, abbreviated, format | AM |
| period of day, noon, abbreviated, format | полд. |
| period of day, pm, abbreviated, format | PM |
| period of day, morning1, abbreviated, format | утра |
| period of day, afternoon1, abbreviated, format | дня |
| period of day, evening1, abbreviated, format | вечера |
| period of day, night1, abbreviated, format | ночи |
| period of day, midnight, narrow, format | полн. |
| period of day, am, narrow, format | AM |
| period of day, noon, narrow, format | полд. |
| period of day, pm, narrow, format | PM |
| period of day, morning1, narrow, format | утра |
| period of day, afternoon1, narrow, format | дня |
| period of day, evening1, narrow, format | веч. |
| period of day, night1, narrow, format | ночи |
| period of day, midnight, wide, format | полночь |
| period of day, am, wide, format | AM |
| period of day, noon, wide, format | полдень |
| period of day, pm, wide, format | PM |
| period of day, morning1, wide, format | утра |
| period of day, afternoon1, wide, format | дня |
| period of day, evening1, wide, format | вечера |
| period of day, night1, wide, format | ночи |
| period of day, midnight, abbreviated, stand-alone | полн. |
| period of day, am, abbreviated, stand-alone | AM |
| period of day, noon, abbreviated, stand-alone | полд. |
| period of day, pm, abbreviated, stand-alone | PM |
| period of day, morning1, abbreviated, stand-alone | утро |
| period of day, afternoon1, abbreviated, stand-alone | день |
| period of day, evening1, abbreviated, stand-alone | веч. |
| period of day, night1, abbreviated, stand-alone | ночь |
| period of day, midnight, narrow, stand-alone | полн. |
| period of day, am, narrow, stand-alone | AM |
| period of day, noon, narrow, stand-alone | полд. |
| period of day, pm, narrow, stand-alone | PM |
| period of day, morning1, narrow, stand-alone | утро |
| period of day, afternoon1, narrow, stand-alone | день |
| period of day, evening1, narrow, stand-alone | веч. |
| period of day, night1, narrow, stand-alone | ночь |
| period of day, midnight, wide, stand-alone | полночь |
| period of day, am, wide, stand-alone | AM |
| period of day, noon, wide, stand-alone | полдень |
| period of day, pm, wide, stand-alone | PM |
| period of day, morning1, wide, stand-alone | утро |
| period of day, afternoon1, wide, stand-alone | день |
| period of day, evening1, wide, stand-alone | вечер |
| period of day, night1, wide, stand-alone | ночь |
| era | до Рождества Христова |
| era | до нашей эры |
| era | от Рождества Христова |
| era | нашей эры |
| era | до н. э. |
| era | н. э. |
| era | до н.э. |
| era | н.э. |
| date format | ↴ |
| standard, full | `EEEE, d MMMM y 'г'.` |
| date format | ↴ |
| standard, long | `d MMMM y 'г'.` |
| date format | ↴ |
| standard, medium | `d MMM y 'г'.` |
| date format | ↴ |
| standard, short | `dd.MM.y` |
| time format | ↴ |
| standard, full | `H:mm:ss zzzz` |
| time format | ↴ |
| standard, long | `H:mm:ss z` |
| time format | ↴ |
| standard, medium | `H:mm:ss` |
| time format | ↴ |
| standard, short | `H:mm` |
| datetime format | ↴ |
| standard, full | `{1}, {0}` |
| datetime format | ↴ |
| standard, long | `{1}, {0}` |
| datetime format | ↴ |
| standard, medium | `{1}, {0}` |
| datetime format | ↴ |
| standard, short | `{1}, {0}` |
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
| date format | ↴ |
| standard, full | `EEEE, d MMMM y 'г'. G` |
| date format | ↴ |
| standard, long | `d MMMM y 'г'. G` |
| date format | ↴ |
| standard, medium | `d MMM y 'г'. G` |
| date format | ↴ |
| standard, short | `dd.MM.y G` |
| datetime format | ↴ |
| standard, full | `{1}, {0}` |
| datetime format | ↴ |
| standard, long | `{1}, {0}` |
| datetime format | ↴ |
| standard, medium | `{1}, {0}` |
| datetime format | ↴ |
| standard, short | `{1}, {0}` |
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

| , RUB | российский рубль |
| one, RUB | российский рубль |
| few, RUB | российских рубля |
| many, RUB | российских рублей |
| other, RUB | российского рубля |
| , RUB symbol | ₽ |
| narrow, RUB symbol | ₽ |

### Datetime patterns


(1 needed)

| datetime format | ↴ |
| standard, full | `{1}, {0}` |
| datetime format | ↴ |
| standard, long | `{1}, {0}` |
| datetime format | ↴ |
| standard, medium | `{1}, {0}` |
| datetime format | ↴ |
| standard, short | `{1}, {0}` |
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


#### Symbols

| Character name | Translated version |
| -------------- | ------------------ |
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

### Territories, cities  and timezone ID's in language area


Country or territory:

| `RU` | Россия |
| `FI` | Финляндия |
| `RU` | Россия |
| `HU` | Венгрия |
| `EE` | Эстония |

Timezone ID:

| Europe/Helsinki | Хельсинки |
| Europe/Moscow | Москва |
| Asia/Tomsk | Томск |
| Europe_Eastern | ↴ |
|  generic | Восточная Европа |
|  standard | Восточная Европа, стандартное время |
|  daylight savings | Восточная Европа, летнее время |
| Moscow | ↴ |
|  generic | Москва |
|  standard | Москва, стандартное время |
|  daylight savings | Москва, летнее время |
| Yekaterinburg | ↴ |
|  generic | Екатеринбург |
|  standard | Екатеринбург, стандартное время |
|  daylight savings | Екатеринбург, летнее время |

### Timezone patterns


(how timezones get displayed in calendars and clocks apps)

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

| Label | Formatting |
| ----- | ---------- |
| `language` | Язык: {0} |
| `script` | Письменность: {0} |
| `territory` | Регион: {0} |

### Context transforms

| Context | Transformation |
| ------- | -------------- |
| `stand-alone::currencyName` | `titlecase-firstword` |
| `uiListOrMenu::currencyName` | `titlecase-firstword` |
| `stand-alone::day-format-except-narrow` | `titlecase-firstword` |
| `uiListOrMenu::day-format-except-narrow` | `titlecase-firstword` |
| `stand-alone::day-standalone-except-narrow` | `titlecase-firstword` |
| `uiListOrMenu::day-standalone-except-narrow` | `titlecase-firstword` |
| `stand-alone::era-abbr` | `titlecase-firstword` |
| `uiListOrMenu::era-abbr` | `titlecase-firstword` |
| `stand-alone::era-name` | `titlecase-firstword` |
| `uiListOrMenu::era-name` | `titlecase-firstword` |
| `stand-alone::keyValue` | `titlecase-firstword` |
| `uiListOrMenu::keyValue` | `titlecase-firstword` |
| `stand-alone::languages` | `titlecase-firstword` |
| `uiListOrMenu::languages` | `titlecase-firstword` |
| `stand-alone::month-format-except-narrow` | `titlecase-firstword` |
| `uiListOrMenu::month-format-except-narrow` | `titlecase-firstword` |
| `stand-alone::month-standalone-except-narrow` | `titlecase-firstword` |
| `uiListOrMenu::month-standalone-except-narrow` | `titlecase-firstword` |
| `stand-alone::relative` | `titlecase-firstword` |
| `uiListOrMenu::relative` | `titlecase-firstword` |
| `stand-alone::script` | `titlecase-firstword` |
| `uiListOrMenu::script` | `titlecase-firstword` |

### Character processing for computer systems

| Character set | Pattern |
| ------------- | ------- |
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[{а\u0301} {е\u0301} {и\u0301} {о\u0301} {у\u0301} {ы\u0301} {э\u0301} {ю\u0301} {я\u0301}]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ы Э Ю Я]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – — , ; \: ! ? . … ' ‘ ‚ " “ „ « » ( ) \[ \] \{ \} § @ * / \& #]` |
| final ellipsis | `{0}…` |
| initial ellipsis | `…{0}` |
| medial ellipsis | `{0}…{1}` |
| word-final ellipsis | `{0} …` |
| word-initial ellipsis | `… {0}` |
| word-medial ellipsis | `{0} … {1}` |
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
| Quotation start character | « |
| Quotation end character | » |
| Secondary yquotation start character | „ |
| Secondary quotation end character | “ |

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
| month, 1, abbreviated, format | 1 |
| month, 2, abbreviated, format | 2 |
| month, 3, abbreviated, format | 3 |
| month, 4, abbreviated, format | 4 |
| month, 5, abbreviated, format | 5 |
| month, 6, abbreviated, format | 6 |
| month, 7, abbreviated, format | 7 |
| month, 8, abbreviated, format | 8 |
| month, 9, abbreviated, format | 9 |
| month, 10, abbreviated, format | 10 |
| month, 11, abbreviated, format | 11 |
| month, 12, abbreviated, format | 12 |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 1, abbreviated, stand-alone | 1 |
| month, 2, abbreviated, stand-alone | 2 |
| month, 3, abbreviated, stand-alone | 3 |
| month, 4, abbreviated, stand-alone | 4 |
| month, 5, abbreviated, stand-alone | 5 |
| month, 6, abbreviated, stand-alone | 6 |
| month, 7, abbreviated, stand-alone | 7 |
| month, 8, abbreviated, stand-alone | 8 |
| month, 9, abbreviated, stand-alone | 9 |
| month, 10, abbreviated, stand-alone | 10 |
| month, 11, abbreviated, stand-alone | 11 |
| month, 12, abbreviated, stand-alone | 12 |
| month, 1, wide, stand-alone | 1 |
| month, 2, wide, stand-alone | 2 |
| month, 3, wide, stand-alone | 3 |
| month, 4, wide, stand-alone | 4 |
| month, 5, wide, stand-alone | 5 |
| month, 6, wide, stand-alone | 6 |
| month, 7, wide, stand-alone | 7 |
| month, 8, wide, stand-alone | 8 |
| month, 9, wide, stand-alone | 9 |
| month, 10, wide, stand-alone | 10 |
| month, 11, wide, stand-alone | 11 |
| month, 12, wide, stand-alone | 12 |
| date format | ↴ |
| standard, full | `EEEE, d MMMM U` |
| date format | ↴ |
| standard, long | `d MMMM U` |
| date format | ↴ |
| standard, medium | `dd.MM U` |
| date format | ↴ |
| standard, short | `dd.MM.y` |
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
| month, 1, abbreviated, format | тот |
| month, 2, abbreviated, format | бабэ |
| month, 3, abbreviated, format | хатур |
| month, 4, abbreviated, format | кихак |
| month, 5, abbreviated, format | тубэ |
| month, 6, abbreviated, format | амшир |
| month, 7, abbreviated, format | барамхат |
| month, 8, abbreviated, format | бармуда |
| month, 9, abbreviated, format | башнас |
| month, 10, abbreviated, format | бауна |
| month, 11, abbreviated, format | абиб |
| month, 12, abbreviated, format | мисра |
| month, 13, abbreviated, format | наси |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 13, narrow, format | 13 |
| month, 1, wide, format | тот |
| month, 2, wide, format | бабэ |
| month, 3, wide, format | хатур |
| month, 4, wide, format | кихак |
| month, 5, wide, format | тубэ |
| month, 6, wide, format | амшир |
| month, 7, wide, format | барамхат |
| month, 8, wide, format | бармуда |
| month, 9, wide, format | башнас |
| month, 10, wide, format | бауна |
| month, 11, wide, format | абиб |
| month, 12, wide, format | мисра |
| month, 13, wide, format | наси |
| month, 1, abbreviated, stand-alone | тот |
| month, 2, abbreviated, stand-alone | бабэ |
| month, 3, abbreviated, stand-alone | хатур |
| month, 4, abbreviated, stand-alone | кихак |
| month, 5, abbreviated, stand-alone | тубэ |
| month, 6, abbreviated, stand-alone | амшир |
| month, 7, abbreviated, stand-alone | барамхат |
| month, 8, abbreviated, stand-alone | бармуда |
| month, 9, abbreviated, stand-alone | башнас |
| month, 10, abbreviated, stand-alone | бауна |
| month, 11, abbreviated, stand-alone | абиб |
| month, 12, abbreviated, stand-alone | мисра |
| month, 13, abbreviated, stand-alone | наси |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 13, narrow, stand-alone | 13 |
| month, 1, wide, stand-alone | тот |
| month, 2, wide, stand-alone | бабэ |
| month, 3, wide, stand-alone | хатур |
| month, 4, wide, stand-alone | кихак |
| month, 5, wide, stand-alone | тубэ |
| month, 6, wide, stand-alone | амшир |
| month, 7, wide, stand-alone | барамхат |
| month, 8, wide, stand-alone | бармуда |
| month, 9, wide, stand-alone | башнас |
| month, 10, wide, stand-alone | бауна |
| month, 11, wide, stand-alone | абиб |
| month, 12, wide, stand-alone | мисра |
| month, 13, wide, stand-alone | наси |
| era | до Диоклетиана |
| era | от Диоклетиана |
| era | до Диокл. |
| era | от Диокл. |
| era | до Диокл. |
| era | от Диокл. |

#### ethiopic calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | мескерем |
| month, 2, abbreviated, format | текемт |
| month, 3, abbreviated, format | хедар |
| month, 4, abbreviated, format | тахсас |
| month, 5, abbreviated, format | тер |
| month, 6, abbreviated, format | якатит |
| month, 7, abbreviated, format | магабит |
| month, 8, abbreviated, format | миазия |
| month, 9, abbreviated, format | генбот |
| month, 10, abbreviated, format | сэнэ |
| month, 11, abbreviated, format | хамлэ |
| month, 12, abbreviated, format | нахасэ |
| month, 13, abbreviated, format | эпагомен |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 13, narrow, format | 13 |
| month, 1, wide, format | мескерем |
| month, 2, wide, format | текемт |
| month, 3, wide, format | хедар |
| month, 4, wide, format | тахсас |
| month, 5, wide, format | тер |
| month, 6, wide, format | якатит |
| month, 7, wide, format | магабит |
| month, 8, wide, format | миазия |
| month, 9, wide, format | генбот |
| month, 10, wide, format | сэнэ |
| month, 11, wide, format | хамлэ |
| month, 12, wide, format | нахасэ |
| month, 13, wide, format | эпагомен |
| month, 1, abbreviated, stand-alone | мескерем |
| month, 2, abbreviated, stand-alone | текемт |
| month, 3, abbreviated, stand-alone | хедар |
| month, 4, abbreviated, stand-alone | тахсас |
| month, 5, abbreviated, stand-alone | тер |
| month, 6, abbreviated, stand-alone | якатит |
| month, 7, abbreviated, stand-alone | магабит |
| month, 8, abbreviated, stand-alone | миазия |
| month, 9, abbreviated, stand-alone | генбот |
| month, 10, abbreviated, stand-alone | сэнэ |
| month, 11, abbreviated, stand-alone | хамлэ |
| month, 12, abbreviated, stand-alone | нахасэ |
| month, 13, abbreviated, stand-alone | эпагомен |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 13, narrow, stand-alone | 13 |
| month, 1, wide, stand-alone | мескерем |
| month, 2, wide, stand-alone | текемт |
| month, 3, wide, stand-alone | хедар |
| month, 4, wide, stand-alone | тахсас |
| month, 5, wide, stand-alone | тер |
| month, 6, wide, stand-alone | якатит |
| month, 7, wide, stand-alone | магабит |
| month, 8, wide, stand-alone | миазия |
| month, 9, wide, stand-alone | генбот |
| month, 10, wide, stand-alone | сэнэ |
| month, 11, wide, stand-alone | хамлэ |
| month, 12, wide, stand-alone | нахасэ |
| month, 13, wide, stand-alone | эпагомен |
| era | до воплощения Христа |
| era | от воплощения Христа |
| era | до Христа |
| era | от Христа |
| era | до Христа |
| era | от Христа |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | ↴ |
| standard, full | `EEEE, d MMMM y 'г'. G` |
| date format | ↴ |
| standard, long | `d MMMM y 'г'. G` |
| date format | ↴ |
| standard, medium | `d MMM y 'г'. G` |
| date format | ↴ |
| standard, short | `dd.MM.y G` |
| datetime format | ↴ |
| standard, full | `{1}, {0}` |
| datetime format | ↴ |
| standard, long | `{1}, {0}` |
| datetime format | ↴ |
| standard, medium | `{1}, {0}` |
| datetime format | ↴ |
| standard, short | `{1}, {0}` |
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
| month, 1, abbreviated, format | янв. |
| month, 2, abbreviated, format | февр. |
| month, 3, abbreviated, format | мар. |
| month, 4, abbreviated, format | апр. |
| month, 5, abbreviated, format | мая |
| month, 6, abbreviated, format | июн. |
| month, 7, abbreviated, format | июл. |
| month, 8, abbreviated, format | авг. |
| month, 9, abbreviated, format | сент. |
| month, 10, abbreviated, format | окт. |
| month, 11, abbreviated, format | нояб. |
| month, 12, abbreviated, format | дек. |
| month, 1, narrow, format | Я |
| month, 2, narrow, format | Ф |
| month, 3, narrow, format | М |
| month, 4, narrow, format | А |
| month, 5, narrow, format | М |
| month, 6, narrow, format | И |
| month, 7, narrow, format | И |
| month, 8, narrow, format | А |
| month, 9, narrow, format | С |
| month, 10, narrow, format | О |
| month, 11, narrow, format | Н |
| month, 12, narrow, format | Д |
| month, 1, wide, format | января |
| month, 2, wide, format | февраля |
| month, 3, wide, format | марта |
| month, 4, wide, format | апреля |
| month, 5, wide, format | мая |
| month, 6, wide, format | июня |
| month, 7, wide, format | июля |
| month, 8, wide, format | августа |
| month, 9, wide, format | сентября |
| month, 10, wide, format | октября |
| month, 11, wide, format | ноября |
| month, 12, wide, format | декабря |
| month, 1, abbreviated, stand-alone | янв. |
| month, 2, abbreviated, stand-alone | февр. |
| month, 3, abbreviated, stand-alone | март |
| month, 4, abbreviated, stand-alone | апр. |
| month, 5, abbreviated, stand-alone | май |
| month, 6, abbreviated, stand-alone | июнь |
| month, 7, abbreviated, stand-alone | июль |
| month, 8, abbreviated, stand-alone | авг. |
| month, 9, abbreviated, stand-alone | сент. |
| month, 10, abbreviated, stand-alone | окт. |
| month, 11, abbreviated, stand-alone | нояб. |
| month, 12, abbreviated, stand-alone | дек. |
| month, 1, narrow, stand-alone | Я |
| month, 2, narrow, stand-alone | Ф |
| month, 3, narrow, stand-alone | М |
| month, 4, narrow, stand-alone | А |
| month, 5, narrow, stand-alone | М |
| month, 6, narrow, stand-alone | И |
| month, 7, narrow, stand-alone | И |
| month, 8, narrow, stand-alone | А |
| month, 9, narrow, stand-alone | С |
| month, 10, narrow, stand-alone | О |
| month, 11, narrow, stand-alone | Н |
| month, 12, narrow, stand-alone | Д |
| month, 1, wide, stand-alone | январь |
| month, 2, wide, stand-alone | февраль |
| month, 3, wide, stand-alone | март |
| month, 4, wide, stand-alone | апрель |
| month, 5, wide, stand-alone | май |
| month, 6, wide, stand-alone | июнь |
| month, 7, wide, stand-alone | июль |
| month, 8, wide, stand-alone | август |
| month, 9, wide, stand-alone | сентябрь |
| month, 10, wide, stand-alone | октябрь |
| month, 11, wide, stand-alone | ноябрь |
| month, 12, wide, stand-alone | декабрь |
| (week)day, sun, abbreviated, format | вс |
| (week)day, mon, abbreviated, format | пн |
| (week)day, tue, abbreviated, format | вт |
| (week)day, wed, abbreviated, format | ср |
| (week)day, thu, abbreviated, format | чт |
| (week)day, fri, abbreviated, format | пт |
| (week)day, sat, abbreviated, format | сб |
| (week)day, sun, narrow, format | вс |
| (week)day, mon, narrow, format | пн |
| (week)day, tue, narrow, format | вт |
| (week)day, wed, narrow, format | ср |
| (week)day, thu, narrow, format | чт |
| (week)day, fri, narrow, format | пт |
| (week)day, sat, narrow, format | сб |
| (week)day, sun, short, format | вс |
| (week)day, mon, short, format | пн |
| (week)day, tue, short, format | вт |
| (week)day, wed, short, format | ср |
| (week)day, thu, short, format | чт |
| (week)day, fri, short, format | пт |
| (week)day, sat, short, format | сб |
| (week)day, sun, wide, format | воскресенье |
| (week)day, mon, wide, format | понедельник |
| (week)day, tue, wide, format | вторник |
| (week)day, wed, wide, format | среда |
| (week)day, thu, wide, format | четверг |
| (week)day, fri, wide, format | пятница |
| (week)day, sat, wide, format | суббота |
| (week)day, sun, abbreviated, stand-alone | вс |
| (week)day, mon, abbreviated, stand-alone | пн |
| (week)day, tue, abbreviated, stand-alone | вт |
| (week)day, wed, abbreviated, stand-alone | ср |
| (week)day, thu, abbreviated, stand-alone | чт |
| (week)day, fri, abbreviated, stand-alone | пт |
| (week)day, sat, abbreviated, stand-alone | сб |
| (week)day, sun, narrow, stand-alone | В |
| (week)day, mon, narrow, stand-alone | П |
| (week)day, tue, narrow, stand-alone | В |
| (week)day, wed, narrow, stand-alone | С |
| (week)day, thu, narrow, stand-alone | Ч |
| (week)day, fri, narrow, stand-alone | П |
| (week)day, sat, narrow, stand-alone | С |
| (week)day, sun, short, stand-alone | вс |
| (week)day, mon, short, stand-alone | пн |
| (week)day, tue, short, stand-alone | вт |
| (week)day, wed, short, stand-alone | ср |
| (week)day, thu, short, stand-alone | чт |
| (week)day, fri, short, stand-alone | пт |
| (week)day, sat, short, stand-alone | сб |
| (week)day, sun, wide, stand-alone | воскресенье |
| (week)day, mon, wide, stand-alone | понедельник |
| (week)day, tue, wide, stand-alone | вторник |
| (week)day, wed, wide, stand-alone | среда |
| (week)day, thu, wide, stand-alone | четверг |
| (week)day, fri, wide, stand-alone | пятница |
| (week)day, sat, wide, stand-alone | суббота |
| quarter, 1, abbreviated, format | 1-й кв. |
| quarter, 2, abbreviated, format | 2-й кв. |
| quarter, 3, abbreviated, format | 3-й кв. |
| quarter, 4, abbreviated, format | 4-й кв. |
| quarter, 1, narrow, format | 1 |
| quarter, 2, narrow, format | 2 |
| quarter, 3, narrow, format | 3 |
| quarter, 4, narrow, format | 4 |
| quarter, 1, wide, format | 1-й квартал |
| quarter, 2, wide, format | 2-й квартал |
| quarter, 3, wide, format | 3-й квартал |
| quarter, 4, wide, format | 4-й квартал |
| quarter, 1, abbreviated, stand-alone | 1-й кв. |
| quarter, 2, abbreviated, stand-alone | 2-й кв. |
| quarter, 3, abbreviated, stand-alone | 3-й кв. |
| quarter, 4, abbreviated, stand-alone | 4-й кв. |
| quarter, 1, narrow, stand-alone | 1 |
| quarter, 2, narrow, stand-alone | 2 |
| quarter, 3, narrow, stand-alone | 3 |
| quarter, 4, narrow, stand-alone | 4 |
| quarter, 1, wide, stand-alone | 1-й квартал |
| quarter, 2, wide, stand-alone | 2-й квартал |
| quarter, 3, wide, stand-alone | 3-й квартал |
| quarter, 4, wide, stand-alone | 4-й квартал |
| period of day, midnight, abbreviated, format | полн. |
| period of day, am, abbreviated, format | AM |
| period of day, noon, abbreviated, format | полд. |
| period of day, pm, abbreviated, format | PM |
| period of day, morning1, abbreviated, format | утра |
| period of day, afternoon1, abbreviated, format | дня |
| period of day, evening1, abbreviated, format | вечера |
| period of day, night1, abbreviated, format | ночи |
| period of day, midnight, narrow, format | полн. |
| period of day, am, narrow, format | AM |
| period of day, noon, narrow, format | полд. |
| period of day, pm, narrow, format | PM |
| period of day, morning1, narrow, format | утра |
| period of day, afternoon1, narrow, format | дня |
| period of day, evening1, narrow, format | веч. |
| period of day, night1, narrow, format | ночи |
| period of day, midnight, wide, format | полночь |
| period of day, am, wide, format | AM |
| period of day, noon, wide, format | полдень |
| period of day, pm, wide, format | PM |
| period of day, morning1, wide, format | утра |
| period of day, afternoon1, wide, format | дня |
| period of day, evening1, wide, format | вечера |
| period of day, night1, wide, format | ночи |
| period of day, midnight, abbreviated, stand-alone | полн. |
| period of day, am, abbreviated, stand-alone | AM |
| period of day, noon, abbreviated, stand-alone | полд. |
| period of day, pm, abbreviated, stand-alone | PM |
| period of day, morning1, abbreviated, stand-alone | утро |
| period of day, afternoon1, abbreviated, stand-alone | день |
| period of day, evening1, abbreviated, stand-alone | веч. |
| period of day, night1, abbreviated, stand-alone | ночь |
| period of day, midnight, narrow, stand-alone | полн. |
| period of day, am, narrow, stand-alone | AM |
| period of day, noon, narrow, stand-alone | полд. |
| period of day, pm, narrow, stand-alone | PM |
| period of day, morning1, narrow, stand-alone | утро |
| period of day, afternoon1, narrow, stand-alone | день |
| period of day, evening1, narrow, stand-alone | веч. |
| period of day, night1, narrow, stand-alone | ночь |
| period of day, midnight, wide, stand-alone | полночь |
| period of day, am, wide, stand-alone | AM |
| period of day, noon, wide, stand-alone | полдень |
| period of day, pm, wide, stand-alone | PM |
| period of day, morning1, wide, stand-alone | утро |
| period of day, afternoon1, wide, stand-alone | день |
| period of day, evening1, wide, stand-alone | вечер |
| period of day, night1, wide, stand-alone | ночь |
| era | до Рождества Христова |
| era | до нашей эры |
| era | от Рождества Христова |
| era | нашей эры |
| era | до н. э. |
| era | н. э. |
| era | до н.э. |
| era | н.э. |
| date format | ↴ |
| standard, full | `EEEE, d MMMM y 'г'.` |
| date format | ↴ |
| standard, long | `d MMMM y 'г'.` |
| date format | ↴ |
| standard, medium | `d MMM y 'г'.` |
| date format | ↴ |
| standard, short | `dd.MM.y` |
| time format | ↴ |
| standard, full | `H:mm:ss zzzz` |
| time format | ↴ |
| standard, long | `H:mm:ss z` |
| time format | ↴ |
| standard, medium | `H:mm:ss` |
| time format | ↴ |
| standard, short | `H:mm` |
| datetime format | ↴ |
| standard, full | `{1}, {0}` |
| datetime format | ↴ |
| standard, long | `{1}, {0}` |
| datetime format | ↴ |
| standard, medium | `{1}, {0}` |
| datetime format | ↴ |
| standard, short | `{1}, {0}` |
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
| month, 1, abbreviated, format | тишрей |
| month, 2, abbreviated, format | хешван |
| month, 3, abbreviated, format | кислев |
| month, 4, abbreviated, format | тевет |
| month, 5, abbreviated, format | шеват |
| month, 6, abbreviated, format | адар I |
| month, 7, abbreviated, format | адар |
| month, 7, abbreviated, format | адар II |
| month, 8, abbreviated, format | нисан |
| month, 9, abbreviated, format | ияр |
| month, 10, abbreviated, format | сиван |
| month, 11, abbreviated, format | таммуз |
| month, 12, abbreviated, format | ав |
| month, 13, abbreviated, format | элул |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 13, narrow, format | 13 |
| month, 1, wide, format | тишрей |
| month, 2, wide, format | хешван |
| month, 3, wide, format | кислев |
| month, 4, wide, format | тевет |
| month, 5, wide, format | шеват |
| month, 6, wide, format | адар I |
| month, 7, wide, format | адар |
| month, 7, wide, format | адар II |
| month, 8, wide, format | нисан |
| month, 9, wide, format | ияр |
| month, 10, wide, format | сиван |
| month, 11, wide, format | таммуз |
| month, 12, wide, format | ав |
| month, 13, wide, format | элул |
| month, 1, abbreviated, stand-alone | тишрей |
| month, 2, abbreviated, stand-alone | хешван |
| month, 3, abbreviated, stand-alone | кислев |
| month, 4, abbreviated, stand-alone | тевет |
| month, 5, abbreviated, stand-alone | шеват |
| month, 6, abbreviated, stand-alone | адар I |
| month, 7, abbreviated, stand-alone | адар |
| month, 7, abbreviated, stand-alone | адар II |
| month, 8, abbreviated, stand-alone | нисан |
| month, 9, abbreviated, stand-alone | ияр |
| month, 10, abbreviated, stand-alone | сиван |
| month, 11, abbreviated, stand-alone | таммуз |
| month, 12, abbreviated, stand-alone | ав |
| month, 13, abbreviated, stand-alone | элул |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 13, narrow, stand-alone | 13 |
| month, 1, wide, stand-alone | тишрей |
| month, 2, wide, stand-alone | хешван |
| month, 3, wide, stand-alone | кислев |
| month, 4, wide, stand-alone | тевет |
| month, 5, wide, stand-alone | шеват |
| month, 6, wide, stand-alone | адар I |
| month, 7, wide, stand-alone | адар |
| month, 7, wide, stand-alone | адар II |
| month, 8, wide, stand-alone | нисан |
| month, 9, wide, stand-alone | ияр |
| month, 10, wide, stand-alone | сиван |
| month, 11, wide, stand-alone | таммуз |
| month, 12, wide, stand-alone | ав |
| month, 13, wide, stand-alone | элул |
| era | от сотворения мира |
| era | AM |
| era | AM |

#### indian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | чайтра |
| month, 2, abbreviated, format | ваисакха |
| month, 3, abbreviated, format | джанштха |
| month, 4, abbreviated, format | асадха |
| month, 5, abbreviated, format | сравана |
| month, 6, abbreviated, format | бхадра |
| month, 7, abbreviated, format | азвина |
| month, 8, abbreviated, format | картика |
| month, 9, abbreviated, format | аграхайана |
| month, 10, abbreviated, format | пауза |
| month, 11, abbreviated, format | магха |
| month, 12, abbreviated, format | пхалгуна |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 1, wide, format | чайтра |
| month, 2, wide, format | ваисакха |
| month, 3, wide, format | джанштха |
| month, 4, wide, format | асадха |
| month, 5, wide, format | сравана |
| month, 6, wide, format | бхадра |
| month, 7, wide, format | азвина |
| month, 8, wide, format | картика |
| month, 9, wide, format | аграхайана |
| month, 10, wide, format | пауза |
| month, 11, wide, format | магха |
| month, 12, wide, format | пхалгуна |
| month, 1, abbreviated, stand-alone | чайтра |
| month, 2, abbreviated, stand-alone | ваисакха |
| month, 3, abbreviated, stand-alone | джанштха |
| month, 4, abbreviated, stand-alone | асадха |
| month, 5, abbreviated, stand-alone | сравана |
| month, 6, abbreviated, stand-alone | бхадра |
| month, 7, abbreviated, stand-alone | азвина |
| month, 8, abbreviated, stand-alone | картика |
| month, 9, abbreviated, stand-alone | аграхайана |
| month, 10, abbreviated, stand-alone | пауза |
| month, 11, abbreviated, stand-alone | магха |
| month, 12, abbreviated, stand-alone | пхалгуна |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 1, wide, stand-alone | чайтра |
| month, 2, wide, stand-alone | ваисакха |
| month, 3, wide, stand-alone | джанштха |
| month, 4, wide, stand-alone | асадха |
| month, 5, wide, stand-alone | сравана |
| month, 6, wide, stand-alone | бхадра |
| month, 7, wide, stand-alone | азвина |
| month, 8, wide, stand-alone | картика |
| month, 9, wide, stand-alone | аграхайана |
| month, 10, wide, stand-alone | пауза |
| month, 11, wide, stand-alone | магха |
| month, 12, wide, stand-alone | пхалгуна |
| era | Сака |
| era | Сака |
| era | Сака |

#### islamic calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | мух. |
| month, 2, abbreviated, format | саф. |
| month, 3, abbreviated, format | раб. I |
| month, 4, abbreviated, format | раб. II |
| month, 5, abbreviated, format | джум. I |
| month, 6, abbreviated, format | джум. II |
| month, 7, abbreviated, format | радж. |
| month, 8, abbreviated, format | шааб. |
| month, 9, abbreviated, format | рам. |
| month, 10, abbreviated, format | шав. |
| month, 11, abbreviated, format | зуль-к. |
| month, 12, abbreviated, format | зуль-х. |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 1, wide, format | мухаррам |
| month, 2, wide, format | сафар |
| month, 3, wide, format | раби-уль-авваль |
| month, 4, wide, format | раби-уль-ахир |
| month, 5, wide, format | джумад-уль-авваль |
| month, 6, wide, format | джумад-уль-ахир |
| month, 7, wide, format | раджаб |
| month, 8, wide, format | шаабан |
| month, 9, wide, format | рамадан |
| month, 10, wide, format | шавваль |
| month, 11, wide, format | зуль-каада |
| month, 12, wide, format | зуль-хиджжа |
| month, 1, abbreviated, stand-alone | мух. |
| month, 2, abbreviated, stand-alone | саф. |
| month, 3, abbreviated, stand-alone | раб. I |
| month, 4, abbreviated, stand-alone | раб. II |
| month, 5, abbreviated, stand-alone | джум. I |
| month, 6, abbreviated, stand-alone | джум. II |
| month, 7, abbreviated, stand-alone | радж. |
| month, 8, abbreviated, stand-alone | шааб. |
| month, 9, abbreviated, stand-alone | рам. |
| month, 10, abbreviated, stand-alone | шав. |
| month, 11, abbreviated, stand-alone | зуль-к. |
| month, 12, abbreviated, stand-alone | зуль-х. |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 1, wide, stand-alone | мухаррам |
| month, 2, wide, stand-alone | сафар |
| month, 3, wide, stand-alone | раби-уль-авваль |
| month, 4, wide, stand-alone | раби-уль-ахир |
| month, 5, wide, stand-alone | джумад-уль-авваль |
| month, 6, wide, stand-alone | джумад-уль-ахир |
| month, 7, wide, stand-alone | раджаб |
| month, 8, wide, stand-alone | шаабан |
| month, 9, wide, stand-alone | рамадан |
| month, 10, wide, stand-alone | шавваль |
| month, 11, wide, stand-alone | зуль-каада |
| month, 12, wide, stand-alone | зуль-хиджжа |
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
| month, 1, abbreviated, format | фарвардин |
| month, 2, abbreviated, format | ордибехешт |
| month, 3, abbreviated, format | хордад |
| month, 4, abbreviated, format | тир |
| month, 5, abbreviated, format | мордад |
| month, 6, abbreviated, format | шахривер |
| month, 7, abbreviated, format | мехр |
| month, 8, abbreviated, format | абан |
| month, 9, abbreviated, format | азер |
| month, 10, abbreviated, format | дей |
| month, 11, abbreviated, format | бахман |
| month, 12, abbreviated, format | эсфанд |
| month, 1, narrow, format | 1 |
| month, 2, narrow, format | 2 |
| month, 3, narrow, format | 3 |
| month, 4, narrow, format | 4 |
| month, 5, narrow, format | 5 |
| month, 6, narrow, format | 6 |
| month, 7, narrow, format | 7 |
| month, 8, narrow, format | 8 |
| month, 9, narrow, format | 9 |
| month, 10, narrow, format | 10 |
| month, 11, narrow, format | 11 |
| month, 12, narrow, format | 12 |
| month, 1, wide, format | фарвардин |
| month, 2, wide, format | ордибехешт |
| month, 3, wide, format | хордад |
| month, 4, wide, format | тир |
| month, 5, wide, format | мордад |
| month, 6, wide, format | шахривер |
| month, 7, wide, format | мехр |
| month, 8, wide, format | абан |
| month, 9, wide, format | азер |
| month, 10, wide, format | дей |
| month, 11, wide, format | бахман |
| month, 12, wide, format | эсфанд |
| month, 1, abbreviated, stand-alone | фарвардин |
| month, 2, abbreviated, stand-alone | ордибехешт |
| month, 3, abbreviated, stand-alone | хордад |
| month, 4, abbreviated, stand-alone | тир |
| month, 5, abbreviated, stand-alone | мордад |
| month, 6, abbreviated, stand-alone | шахривер |
| month, 7, abbreviated, stand-alone | мехр |
| month, 8, abbreviated, stand-alone | абан |
| month, 9, abbreviated, stand-alone | азер |
| month, 10, abbreviated, stand-alone | дей |
| month, 11, abbreviated, stand-alone | бахман |
| month, 12, abbreviated, stand-alone | эсфанд |
| month, 1, narrow, stand-alone | 1 |
| month, 2, narrow, stand-alone | 2 |
| month, 3, narrow, stand-alone | 3 |
| month, 4, narrow, stand-alone | 4 |
| month, 5, narrow, stand-alone | 5 |
| month, 6, narrow, stand-alone | 6 |
| month, 7, narrow, stand-alone | 7 |
| month, 8, narrow, stand-alone | 8 |
| month, 9, narrow, stand-alone | 9 |
| month, 10, narrow, stand-alone | 10 |
| month, 11, narrow, stand-alone | 11 |
| month, 12, narrow, stand-alone | 12 |
| month, 1, wide, stand-alone | фарвардин |
| month, 2, wide, stand-alone | ордибехешт |
| month, 3, wide, stand-alone | хордад |
| month, 4, wide, stand-alone | тир |
| month, 5, wide, stand-alone | мордад |
| month, 6, wide, stand-alone | шахривер |
| month, 7, wide, stand-alone | мехр |
| month, 8, wide, stand-alone | абан |
| month, 9, wide, stand-alone | азер |
| month, 10, wide, stand-alone | дей |
| month, 11, wide, stand-alone | бахман |
| month, 12, wide, stand-alone | эсфанд |
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

| Stuff | Translation |
| ----- | ----------- |
| , era | эра |
| , era-short | эра |
| , era-narrow | эра |
| , year | год |
| -1year | в прошлом году |
| 0year | в этом году |
| 1year | в следующем году |
| oneyearfuture | через {0} год |
| fewyearfuture | через {0} года |
| manyyearfuture | через {0} лет |
| otheryearfuture | через {0} года |
| oneyearpast | {0} год назад |
| fewyearpast | {0} года назад |
| manyyearpast | {0} лет назад |
| otheryearpast | {0} года назад |
| , year-short | г. |
| -1year-short | в прошлом г. |
| 0year-short | в этом г. |
| 1year-short | в след. г. |
| oneyear-shortfuture | через {0} г. |
| fewyear-shortfuture | через {0} г. |
| manyyear-shortfuture | через {0} л. |
| otheryear-shortfuture | через {0} г. |
| oneyear-shortpast | {0} г. назад |
| fewyear-shortpast | {0} г. назад |
| manyyear-shortpast | {0} л. назад |
| otheryear-shortpast | {0} г. назад |
| , year-narrow | г. |
| -1year-narrow | в пр. г. |
| 0year-narrow | в эт. г. |
| 1year-narrow | в сл. г. |
| oneyear-narrowfuture | +{0} г. |
| fewyear-narrowfuture | +{0} г. |
| manyyear-narrowfuture | +{0} л. |
| otheryear-narrowfuture | +{0} г. |
| oneyear-narrowpast | -{0} г. |
| fewyear-narrowpast | -{0} г. |
| manyyear-narrowpast | -{0} л. |
| otheryear-narrowpast | -{0} г. |
| , quarter | квартал |
| -1quarter | в прошлом квартале |
| 0quarter | в текущем квартале |
| 1quarter | в следующем квартале |
| onequarterfuture | через {0} квартал |
| fewquarterfuture | через {0} квартала |
| manyquarterfuture | через {0} кварталов |
| otherquarterfuture | через {0} квартала |
| onequarterpast | {0} квартал назад |
| fewquarterpast | {0} квартала назад |
| manyquarterpast | {0} кварталов назад |
| otherquarterpast | {0} квартала назад |
| , quarter-short | кв. |
| -1quarter-short | последний кв. |
| 0quarter-short | текущий кв. |
| 1quarter-short | следующий кв. |
| onequarter-shortfuture | через {0} кв. |
| fewquarter-shortfuture | через {0} кв. |
| manyquarter-shortfuture | через {0} кв. |
| otherquarter-shortfuture | через {0} кв. |
| onequarter-shortpast | {0} кв. назад |
| fewquarter-shortpast | {0} кв. назад |
| manyquarter-shortpast | {0} кв. назад |
| otherquarter-shortpast | {0} кв. назад |
| , quarter-narrow | кв. |
| -1quarter-narrow | посл. кв. |
| 0quarter-narrow | тек. кв. |
| 1quarter-narrow | след. кв. |
| onequarter-narrowfuture | +{0} кв. |
| fewquarter-narrowfuture | +{0} кв. |
| manyquarter-narrowfuture | +{0} кв. |
| otherquarter-narrowfuture | +{0} кв. |
| onequarter-narrowpast | -{0} кв. |
| fewquarter-narrowpast | -{0} кв. |
| manyquarter-narrowpast | -{0} кв. |
| otherquarter-narrowpast | -{0} кв. |
| , month | месяц |
| -1month | в прошлом месяце |
| 0month | в этом месяце |
| 1month | в следующем месяце |
| onemonthfuture | через {0} месяц |
| fewmonthfuture | через {0} месяца |
| manymonthfuture | через {0} месяцев |
| othermonthfuture | через {0} месяца |
| onemonthpast | {0} месяц назад |
| fewmonthpast | {0} месяца назад |
| manymonthpast | {0} месяцев назад |
| othermonthpast | {0} месяца назад |
| , month-short | мес. |
| -1month-short | в прошлом мес. |
| 0month-short | в этом мес. |
| 1month-short | в следующем мес. |
| onemonth-shortfuture | через {0} мес. |
| fewmonth-shortfuture | через {0} мес. |
| manymonth-shortfuture | через {0} мес. |
| othermonth-shortfuture | через {0} мес. |
| onemonth-shortpast | {0} мес. назад |
| fewmonth-shortpast | {0} мес. назад |
| manymonth-shortpast | {0} мес. назад |
| othermonth-shortpast | {0} мес. назад |
| , month-narrow | мес. |
| -1month-narrow | в пр. мес. |
| 0month-narrow | в эт. мес. |
| 1month-narrow | в след. мес. |
| onemonth-narrowfuture | +{0} мес. |
| fewmonth-narrowfuture | +{0} мес. |
| manymonth-narrowfuture | +{0} мес. |
| othermonth-narrowfuture | +{0} мес. |
| onemonth-narrowpast | -{0} мес. |
| fewmonth-narrowpast | -{0} мес. |
| manymonth-narrowpast | -{0} мес. |
| othermonth-narrowpast | -{0} мес. |
| , week | неделя |
| -1week | на прошлой неделе |
| 0week | на этой неделе |
| 1week | на следующей неделе |
| oneweekfuture | через {0} неделю |
| fewweekfuture | через {0} недели |
| manyweekfuture | через {0} недель |
| otherweekfuture | через {0} недели |
| oneweekpast | {0} неделю назад |
| fewweekpast | {0} недели назад |
| manyweekpast | {0} недель назад |
| otherweekpast | {0} недели назад |
| week, relative period | на неделе {0} |
| , week-short | нед. |
| -1week-short | на прошлой нед. |
| 0week-short | на этой нед. |
| 1week-short | на следующей нед. |
| oneweek-shortfuture | через {0} нед. |
| fewweek-shortfuture | через {0} нед. |
| manyweek-shortfuture | через {0} нед. |
| otherweek-shortfuture | через {0} нед. |
| oneweek-shortpast | {0} нед. назад |
| fewweek-shortpast | {0} нед. назад |
| manyweek-shortpast | {0} нед. назад |
| otherweek-shortpast | {0} нед. назад |
| week-short, relative period | на нед. {0} |
| , week-narrow | нед. |
| -1week-narrow | на пр. нед. |
| 0week-narrow | на эт. нед. |
| 1week-narrow | на след. неделе |
| oneweek-narrowfuture | +{0} нед. |
| fewweek-narrowfuture | +{0} нед. |
| manyweek-narrowfuture | +{0} нед. |
| otherweek-narrowfuture | +{0} нед. |
| oneweek-narrowpast | -{0} нед. |
| fewweek-narrowpast | -{0} нед. |
| manyweek-narrowpast | -{0} нед. |
| otherweek-narrowpast | -{0} нед. |
| week-narrow, relative period | на нед. {0} |
| , weekOfMonth | неделя месяца |
| , weekOfMonth-short | нед. месяца |
| , weekOfMonth-narrow | нед. мес. |
| , day | день |
| -2day | позавчера |
| -1day | вчера |
| 0day | сегодня |
| 1day | завтра |
| 2day | послезавтра |
| onedayfuture | через {0} день |
| fewdayfuture | через {0} дня |
| manydayfuture | через {0} дней |
| otherdayfuture | через {0} дня |
| onedaypast | {0} день назад |
| fewdaypast | {0} дня назад |
| manydaypast | {0} дней назад |
| otherdaypast | {0} дня назад |
| , day-short | дн. |
| -2day-short | позавчера |
| 2day-short | послезавтра |
| oneday-shortfuture | через {0} дн. |
| fewday-shortfuture | через {0} дн. |
| manyday-shortfuture | через {0} дн. |
| otherday-shortfuture | через {0} дн. |
| oneday-shortpast | {0} дн. назад |
| fewday-shortpast | {0} дн. назад |
| manyday-shortpast | {0} дн. назад |
| otherday-shortpast | {0} дн. назад |
| , day-narrow | дн. |
| -2day-narrow | позавчера |
| 2day-narrow | послезавтра |
| oneday-narrowfuture | +{0} дн. |
| fewday-narrowfuture | +{0} дн. |
| manyday-narrowfuture | +{0} дн. |
| otherday-narrowfuture | +{0} дн. |
| oneday-narrowpast | -{0} дн. |
| fewday-narrowpast | -{0} дн. |
| manyday-narrowpast | -{0} дн. |
| otherday-narrowpast | -{0} дн. |
| , dayOfYear | день года |
| , dayOfYear-short | дн. года |
| , dayOfYear-narrow | дн. года |
| , weekday | день недели |
| , weekday-short | дн. недели |
| , weekday-narrow | дн. нед. |
| , weekdayOfMonth | день недели в месяце |
| , weekdayOfMonth-short | дн. нед. в месяце |
| , weekdayOfMonth-narrow | дн. нед. в мес. |
| -1sun | в прошлое воскресенье |
| 0sun | в это воскресенье |
| 1sun | в следующее воскресенье |
| onesunfuture | через {0} воскресенье |
| fewsunfuture | через {0} воскресенья |
| manysunfuture | через {0} воскресений |
| othersunfuture | через {0} воскресенья |
| onesunpast | {0} воскресенье назад |
| fewsunpast | {0} воскресенья назад |
| manysunpast | {0} воскресений назад |
| othersunpast | {0} воскресенья назад |
| -1sun-short | в прош. вс. |
| 0sun-short | в это вс. |
| 1sun-short | в след. вс. |
| onesun-shortfuture | через {0} вс. |
| fewsun-shortfuture | через {0} вс. |
| manysun-shortfuture | через {0} вс. |
| othersun-shortfuture | через {0} вс. |
| onesun-shortpast | {0} вс. назад |
| fewsun-shortpast | {0} вс. назад |
| manysun-shortpast | {0} вс. назад |
| othersun-shortpast | {0} вс. назад |
| -1sun-narrow | в прош. вс. |
| 0sun-narrow | в это вс. |
| 1sun-narrow | в след. вс. |
| onesun-narrowfuture | +{0} вс. |
| fewsun-narrowfuture | +{0} вс. |
| manysun-narrowfuture | +{0} вс. |
| othersun-narrowfuture | +{0} вс. |
| onesun-narrowpast | -{0} вс. |
| fewsun-narrowpast | -{0} вс. |
| manysun-narrowpast | -{0} вс. |
| othersun-narrowpast | -{0} вс. |
| -1mon | в прошлый понедельник |
| 0mon | в этот понедельник |
| 1mon | в следующий понедельник |
| onemonfuture | через {0} понедельник |
| fewmonfuture | через {0} понедельника |
| manymonfuture | через {0} понедельников |
| othermonfuture | через {0} понедельника |
| onemonpast | {0} понедельник назад |
| fewmonpast | {0} понедельника назад |
| manymonpast | {0} понедельников назад |
| othermonpast | {0} понедельника назад |
| -1mon-short | в прош. пн. |
| 0mon-short | в этот пн. |
| 1mon-short | в след. пн. |
| onemon-shortfuture | через {0} пн. |
| fewmon-shortfuture | через {0} пн. |
| manymon-shortfuture | через {0} пн. |
| othermon-shortfuture | через {0} пн. |
| onemon-shortpast | {0} пн. назад |
| fewmon-shortpast | {0} пн. назад |
| manymon-shortpast | {0} пн. назад |
| othermon-shortpast | {0} пн. назад |
| -1mon-narrow | в прош. пн. |
| 0mon-narrow | в этот пн. |
| 1mon-narrow | в след. пн. |
| onemon-narrowfuture | +{0} пн. |
| fewmon-narrowfuture | +{0} пн. |
| manymon-narrowfuture | +{0} пн. |
| othermon-narrowfuture | +{0} пн. |
| onemon-narrowpast | -{0} пн. |
| fewmon-narrowpast | -{0} пн. |
| manymon-narrowpast | -{0} пн. |
| othermon-narrowpast | -{0} пн. |
| -1tue | в прошлый вторник |
| 0tue | в этот вторник |
| 1tue | в следующий вторник |
| onetuefuture | через {0} вторник |
| fewtuefuture | через {0} вторника |
| manytuefuture | через {0} вторников |
| othertuefuture | через {0} вторника |
| onetuepast | {0} вторник назад |
| fewtuepast | {0} вторника назад |
| manytuepast | {0} вторников назад |
| othertuepast | {0} вторника назад |
| -1tue-short | в прош. вт. |
| 0tue-short | в этот вт. |
| 1tue-short | в след. вт. |
| onetue-shortfuture | через {0} вт. |
| fewtue-shortfuture | через {0} вт. |
| manytue-shortfuture | через {0} вт. |
| othertue-shortfuture | через {0} вт. |
| onetue-shortpast | {0} вт. назад |
| fewtue-shortpast | {0} вт. назад |
| manytue-shortpast | {0} вт. назад |
| othertue-shortpast | {0} вт. назад |
| -1tue-narrow | в прош. вт. |
| 0tue-narrow | в этот вт. |
| 1tue-narrow | в след. вт. |
| onetue-narrowfuture | +{0} вт. |
| fewtue-narrowfuture | +{0} вт. |
| manytue-narrowfuture | +{0} вт. |
| othertue-narrowfuture | +{0} вт. |
| onetue-narrowpast | -{0} вт. |
| fewtue-narrowpast | -{0} вт. |
| manytue-narrowpast | -{0} вт. |
| othertue-narrowpast | -{0} вт. |
| -1wed | в прошлую среду |
| 0wed | в эту среду |
| 1wed | в следующую среду |
| onewedfuture | через {0} среду |
| fewwedfuture | через {0} среды |
| manywedfuture | через {0} сред |
| otherwedfuture | через {0} среды |
| onewedpast | {0} среду назад |
| fewwedpast | {0} среды назад |
| manywedpast | {0} сред назад |
| otherwedpast | {0} среды назад |
| -1wed-short | в прош. ср. |
| 0wed-short | в эту ср. |
| 1wed-short | в след. ср. |
| onewed-shortfuture | через {0} ср. |
| fewwed-shortfuture | через {0} ср. |
| manywed-shortfuture | через {0} ср. |
| otherwed-shortfuture | через {0} ср. |
| onewed-shortpast | {0} ср. назад |
| fewwed-shortpast | {0} ср. назад |
| manywed-shortpast | {0} ср. назад |
| otherwed-shortpast | {0} ср. назад |
| -1wed-narrow | в прош. ср. |
| 0wed-narrow | в эту ср. |
| 1wed-narrow | в след. ср. |
| onewed-narrowfuture | +{0} ср. |
| fewwed-narrowfuture | +{0} ср. |
| manywed-narrowfuture | +{0} ср. |
| otherwed-narrowfuture | +{0} ср. |
| onewed-narrowpast | -{0} ср. |
| fewwed-narrowpast | -{0} ср. |
| manywed-narrowpast | -{0} ср. |
| otherwed-narrowpast | -{0} ср. |
| -1thu | в прошлый четверг |
| 0thu | в этот четверг |
| 1thu | в следующий четверг |
| onethufuture | через {0} четверг |
| fewthufuture | через {0} четверга |
| manythufuture | через {0} четвергов |
| otherthufuture | через {0} четверга |
| onethupast | {0} четверг назад |
| fewthupast | {0} четверга назад |
| manythupast | {0} четвергов назад |
| otherthupast | {0} четверга назад |
| -1thu-short | в прош. чт. |
| 0thu-short | в этот чт. |
| 1thu-short | в след. чт. |
| onethu-shortfuture | через {0} чт. |
| fewthu-shortfuture | через {0} чт. |
| manythu-shortfuture | через {0} чт. |
| otherthu-shortfuture | через {0} чт. |
| onethu-shortpast | {0} чт. назад |
| fewthu-shortpast | {0} чт. назад |
| manythu-shortpast | {0} чт. назад |
| otherthu-shortpast | {0} чт. назад |
| -1thu-narrow | в прош. чт. |
| 0thu-narrow | в этот чт. |
| 1thu-narrow | в след. чт. |
| onethu-narrowfuture | +{0} чт. |
| fewthu-narrowfuture | +{0} чт. |
| manythu-narrowfuture | +{0} чт. |
| otherthu-narrowfuture | +{0} чт. |
| onethu-narrowpast | -{0} чт. |
| fewthu-narrowpast | -{0} чт. |
| manythu-narrowpast | -{0} чт. |
| otherthu-narrowpast | -{0} чт. |
| -1fri | в прошлую пятницу |
| 0fri | в эту пятницу |
| 1fri | в следующую пятницу |
| onefrifuture | через {0} пятницу |
| fewfrifuture | через {0} пятницы |
| manyfrifuture | через {0} пятниц |
| otherfrifuture | через {0} пятницы |
| onefripast | {0} пятницу назад |
| fewfripast | {0} пятницы назад |
| manyfripast | {0} пятниц назад |
| otherfripast | {0} пятницы назад |
| -1fri-short | в прош. пт. |
| 0fri-short | в эту пт. |
| 1fri-short | в след. пт. |
| onefri-shortfuture | через {0} пт. |
| fewfri-shortfuture | через {0} пт. |
| manyfri-shortfuture | через {0} пт. |
| otherfri-shortfuture | через {0} пт. |
| onefri-shortpast | {0} пт. назад |
| fewfri-shortpast | {0} пт. назад |
| manyfri-shortpast | {0} пт. назад |
| otherfri-shortpast | {0} пт. назад |
| -1fri-narrow | в прош. пт. |
| 0fri-narrow | в эту пт. |
| 1fri-narrow | в след. пт. |
| onefri-narrowfuture | +{0} пт. |
| fewfri-narrowfuture | +{0} пт. |
| manyfri-narrowfuture | +{0} пт. |
| otherfri-narrowfuture | +{0} пт. |
| onefri-narrowpast | -{0} пт. |
| fewfri-narrowpast | -{0} пт. |
| manyfri-narrowpast | -{0} пт. |
| otherfri-narrowpast | -{0} пт. |
| -1sat | в прошлую субботу |
| 0sat | в эту субботу |
| 1sat | в следующую субботу |
| onesatfuture | через {0} субботу |
| fewsatfuture | через {0} субботы |
| manysatfuture | через {0} суббот |
| othersatfuture | через {0} субботы |
| onesatpast | {0} субботу назад |
| fewsatpast | {0} субботы назад |
| manysatpast | {0} суббот назад |
| othersatpast | {0} субботы назад |
| -1sat-short | в прош. сб. |
| 0sat-short | в эту сб. |
| 1sat-short | в след. сб. |
| onesat-shortfuture | через {0} сб. |
| fewsat-shortfuture | через {0} сб. |
| manysat-shortfuture | через {0} сб. |
| othersat-shortfuture | через {0} сб. |
| onesat-shortpast | {0} сб. назад |
| fewsat-shortpast | {0} сб. назад |
| manysat-shortpast | {0} сб. назад |
| othersat-shortpast | {0} сб. назад |
| -1sat-narrow | в прош. сб. |
| 0sat-narrow | в эту сб. |
| 1sat-narrow | в след. сб. |
| onesat-narrowfuture | +{0} сб. |
| fewsat-narrowfuture | +{0} сб. |
| manysat-narrowfuture | +{0} сб. |
| othersat-narrowfuture | +{0} сб. |
| onesat-narrowpast | -{0} сб. |
| fewsat-narrowpast | -{0} сб. |
| manysat-narrowpast | -{0} сб. |
| othersat-narrowpast | -{0} сб. |
| , dayperiod-short | AM/PM |
| , dayperiod | AM/PM |
| , dayperiod-narrow | AM/PM |
| , hour | час |
| 0hour | в этот час |
| onehourfuture | через {0} час |
| fewhourfuture | через {0} часа |
| manyhourfuture | через {0} часов |
| otherhourfuture | через {0} часа |
| onehourpast | {0} час назад |
| fewhourpast | {0} часа назад |
| manyhourpast | {0} часов назад |
| otherhourpast | {0} часа назад |
| , hour-short | ч |
| 0hour-short | в этот час |
| onehour-shortfuture | через {0} ч. |
| fewhour-shortfuture | через {0} ч. |
| manyhour-shortfuture | через {0} ч. |
| otherhour-shortfuture | через {0} ч. |
| onehour-shortpast | {0} ч. назад |
| fewhour-shortpast | {0} ч. назад |
| manyhour-shortpast | {0} ч. назад |
| otherhour-shortpast | {0} ч. назад |
| , hour-narrow | ч |
| 0hour-narrow | в этот час |
| onehour-narrowfuture | +{0} ч. |
| fewhour-narrowfuture | +{0} ч. |
| manyhour-narrowfuture | +{0} ч. |
| otherhour-narrowfuture | +{0} ч. |
| onehour-narrowpast | -{0} ч. |
| fewhour-narrowpast | -{0} ч. |
| manyhour-narrowpast | -{0} ч. |
| otherhour-narrowpast | -{0} ч. |
| , minute | минута |
| 0minute | в эту минуту |
| oneminutefuture | через {0} минуту |
| fewminutefuture | через {0} минуты |
| manyminutefuture | через {0} минут |
| otherminutefuture | через {0} минуты |
| oneminutepast | {0} минуту назад |
| fewminutepast | {0} минуты назад |
| manyminutepast | {0} минут назад |
| otherminutepast | {0} минуты назад |
| , minute-short | мин. |
| oneminute-shortfuture | через {0} мин. |
| fewminute-shortfuture | через {0} мин. |
| manyminute-shortfuture | через {0} мин. |
| otherminute-shortfuture | через {0} мин. |
| oneminute-shortpast | {0} мин. назад |
| fewminute-shortpast | {0} мин. назад |
| manyminute-shortpast | {0} мин. назад |
| otherminute-shortpast | {0} мин. назад |
| , minute-narrow | мин |
| oneminute-narrowfuture | +{0} мин. |
| fewminute-narrowfuture | +{0} мин. |
| manyminute-narrowfuture | +{0} мин. |
| otherminute-narrowfuture | +{0} мин. |
| oneminute-narrowpast | -{0} мин. |
| fewminute-narrowpast | -{0} мин. |
| manyminute-narrowpast | -{0} мин. |
| otherminute-narrowpast | -{0} мин. |
| , second | секунда |
| 0second | сейчас |
| onesecondfuture | через {0} секунду |
| fewsecondfuture | через {0} секунды |
| manysecondfuture | через {0} секунд |
| othersecondfuture | через {0} секунды |
| onesecondpast | {0} секунду назад |
| fewsecondpast | {0} секунды назад |
| manysecondpast | {0} секунд назад |
| othersecondpast | {0} секунды назад |
| , second-short | сек. |
| onesecond-shortfuture | через {0} сек. |
| fewsecond-shortfuture | через {0} сек. |
| manysecond-shortfuture | через {0} сек. |
| othersecond-shortfuture | через {0} сек. |
| onesecond-shortpast | {0} сек. назад |
| fewsecond-shortpast | {0} сек. назад |
| manysecond-shortpast | {0} сек. назад |
| othersecond-shortpast | {0} сек. назад |
| , second-narrow | с |
| onesecond-narrowfuture | +{0} с |
| fewsecond-narrowfuture | +{0} с |
| manysecond-narrowfuture | +{0} с |
| othersecond-narrowfuture | +{0} с |
| onesecond-narrowpast | -{0} с |
| fewsecond-narrowpast | -{0} с |
| manysecond-narrowpast | -{0} с |
| othersecond-narrowpast | -{0} с |
| , zone | часовой пояс |
| , zone-short | час. пояс |
| , zone-narrow | час. пояс |

#### time zones

| Format name | Format |
| ----------- | ------ |
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
| Etc/UTC | 
|  standard | Всемирное координированное время |
|
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
| Europe/London | 
|  daylight savings | Великобритания, летнее время |
Лондон |
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
| Europe/Dublin | 
|  daylight savings | Ирландия, стандартное время |
Дублин |
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
| Acre | ↴ |
|  generic | Акри время |
|  standard | Акри стандартное время |
|  daylight savings | Акри летнее время |
| Afghanistan | ↴ |
|  standard | Афганистан |
| Africa_Central | ↴ |
|  standard | Центральная Африка |
| Africa_Eastern | ↴ |
|  standard | Восточная Африка |
| Africa_Southern | ↴ |
|  standard | Южная Африка |
| Africa_Western | ↴ |
|  generic | Западная Африка |
|  standard | Западная Африка, стандартное время |
|  daylight savings | Западная Африка, летнее время |
| Alaska | ↴ |
|  generic | Аляска |
|  standard | Аляска, стандартное время |
|  daylight savings | Аляска, летнее время |
| Almaty | ↴ |
|  generic | Алма-Ата время |
|  standard | Алма-Ата стандартное время |
|  daylight savings | Алма-Ата летнее время |
| Amazon | ↴ |
|  generic | Амазонка |
|  standard | Амазонка, стандартное время |
|  daylight savings | Амазонка, летнее время |
| America_Central | ↴ |
|  generic | Центральная Америка |
|  standard | Центральная Америка, стандартное время |
|  daylight savings | Центральная Америка, летнее время |
| America_Eastern | ↴ |
|  generic | Восточная Америка |
|  standard | Восточная Америка, стандартное время |
|  daylight savings | Восточная Америка, летнее время |
| America_Mountain | ↴ |
|  generic | Горное время (Северная Америка) |
|  standard | Стандартное горное время (Северная Америка) |
|  daylight savings | Летнее горное время (Северная Америка) |
| America_Pacific | ↴ |
|  generic | Тихоокеанское время |
|  standard | Тихоокеанское стандартное время |
|  daylight savings | Тихоокеанское летнее время |
| Anadyr | ↴ |
|  generic | Время по Анадырю |
|  standard | Анадырь стандартное время |
|  daylight savings | Анадырь летнее время |
| Apia | ↴ |
|  generic | Апиа |
|  standard | Апиа, стандартное время |
|  daylight savings | Апиа, летнее время |
| Aqtau | ↴ |
|  generic | Актау время |
|  standard | Актау, стандартное время |
|  daylight savings | Актау летнее время |
| Aqtobe | ↴ |
|  generic | Актобе время |
|  standard | Актобе стандартное время |
|  daylight savings | Актобе летнее время |
| Arabian | ↴ |
|  generic | Саудовская Аравия |
|  standard | Саудовская Аравия, стандартное время |
|  daylight savings | Саудовская Аравия, летнее время |
| Argentina | ↴ |
|  generic | Аргентина |
|  standard | Аргентина, стандартное время |
|  daylight savings | Аргентина, летнее время |
| Argentina_Western | ↴ |
|  generic | Западная Аргентина |
|  standard | Западная Аргентина, стандартное время |
|  daylight savings | Западная Аргентина, летнее время |
| Armenia | ↴ |
|  generic | Армения |
|  standard | Армения, стандартное время |
|  daylight savings | Армения, летнее время |
| Atlantic | ↴ |
|  generic | Атлантическое время |
|  standard | Атлантическое стандартное время |
|  daylight savings | Атлантическое летнее время |
| Australia_Central | ↴ |
|  generic | Центральная Австралия |
|  standard | Центральная Австралия, стандартное время |
|  daylight savings | Центральная Австралия, летнее время |
| Australia_CentralWestern | ↴ |
|  generic | Центральная Австралия, западное время |
|  standard | Центральная Австралия, западное стандартное время |
|  daylight savings | Центральная Австралия, западное летнее время |
| Australia_Eastern | ↴ |
|  generic | Восточная Австралия |
|  standard | Восточная Австралия, стандартное время |
|  daylight savings | Восточная Австралия, летнее время |
| Australia_Western | ↴ |
|  generic | Западная Австралия |
|  standard | Западная Австралия, стандартное время |
|  daylight savings | Западная Австралия, летнее время |
| Azerbaijan | ↴ |
|  generic | Азербайджан |
|  standard | Азербайджан, стандартное время |
|  daylight savings | Азербайджан, летнее время |
| Azores | ↴ |
|  generic | Азорские о-ва |
|  standard | Азорские о-ва, стандартное время |
|  daylight savings | Азорские о-ва, летнее время |
| Bangladesh | ↴ |
|  generic | Бангладеш |
|  standard | Бангладеш, стандартное время |
|  daylight savings | Бангладеш, летнее время |
| Bhutan | ↴ |
|  standard | Бутан |
| Bolivia | ↴ |
|  standard | Боливия |
| Brasilia | ↴ |
|  generic | Бразилия |
|  standard | Бразилия, стандартное время |
|  daylight savings | Бразилия, летнее время |
| Brunei | ↴ |
|  standard | Бруней-Даруссалам |
| Cape_Verde | ↴ |
|  generic | Кабо-Верде |
|  standard | Кабо-Верде, стандартное время |
|  daylight savings | Кабо-Верде, летнее время |
| Casey | ↴ |
|  standard | Кейси |
| Chamorro | ↴ |
|  standard | Чаморро |
| Chatham | ↴ |
|  generic | Чатем |
|  standard | Чатем, стандартное время |
|  daylight savings | Чатем, летнее время |
| Chile | ↴ |
|  generic | Чили |
|  standard | Чили, стандартное время |
|  daylight savings | Чили, летнее время |
| China | ↴ |
|  generic | Китай |
|  standard | Китай, стандартное время |
|  daylight savings | Китай, летнее время |
| Choibalsan | ↴ |
|  generic | Чойбалсан |
|  standard | Чойбалсан, стандартное время |
|  daylight savings | Чойбалсан, летнее время |
| Christmas | ↴ |
|  standard | о-в Рождества |
| Cocos | ↴ |
|  standard | Кокосовые о-ва |
| Colombia | ↴ |
|  generic | Колумбия |
|  standard | Колумбия, стандартное время |
|  daylight savings | Колумбия, летнее время |
| Cook | ↴ |
|  generic | Острова Кука |
|  standard | Острова Кука, стандартное время |
|  daylight savings | Острова Кука, полулетнее время |
| Cuba | ↴ |
|  generic | Куба |
|  standard | Куба, стандартное время |
|  daylight savings | Куба, летнее время |
| Davis | ↴ |
|  standard | Дейвис |
| DumontDUrville | ↴ |
|  standard | Дюмон-д’Юрвиль |
| East_Timor | ↴ |
|  standard | Восточный Тимор |
| Easter | ↴ |
|  generic | О-в Пасхи |
|  standard | О-в Пасхи, стандартное время |
|  daylight savings | О-в Пасхи, летнее время |
| Ecuador | ↴ |
|  standard | Эквадор |
| Europe_Central | ↴ |
|  generic | Центральная Европа |
|  standard | Центральная Европа, стандартное время |
|  daylight savings | Центральная Европа, летнее время |
| Europe_Eastern | ↴ |
|  generic | Восточная Европа |
|  standard | Восточная Европа, стандартное время |
|  daylight savings | Восточная Европа, летнее время |
| Europe_Further_Eastern | ↴ |
|  standard | Минское время |
| Europe_Western | ↴ |
|  generic | Западная Европа |
|  standard | Западная Европа, стандартное время |
|  daylight savings | Западная Европа, летнее время |
| Falkland | ↴ |
|  generic | Фолклендские о-ва |
|  standard | Фолклендские о-ва, стандартное время |
|  daylight savings | Фолклендские о-ва, летнее время |
| Fiji | ↴ |
|  generic | Фиджи |
|  standard | Фиджи, стандартное время |
|  daylight savings | Фиджи, летнее время |
| French_Guiana | ↴ |
|  standard | Французская Гвиана |
| French_Southern | ↴ |
|  standard | Французские Южные и Антарктические территории |
| Galapagos | ↴ |
|  standard | Галапагосские о-ва |
| Gambier | ↴ |
|  standard | Гамбье |
| Georgia | ↴ |
|  generic | Грузия |
|  standard | Грузия, стандартное время |
|  daylight savings | Грузия, летнее время |
| Gilbert_Islands | ↴ |
|  standard | о-ва Гилберта |
| GMT | ↴ |
|  standard | Среднее время по Гринвичу |
| Greenland_Eastern | ↴ |
|  generic | Восточная Гренландия |
|  standard | Восточная Гренландия, стандарное время |
|  daylight savings | Восточная Гренландия, летнее время |
| Greenland_Western | ↴ |
|  generic | Западная Гренландия |
|  standard | Западная Гренландия, стандартное время |
|  daylight savings | Западная Гренландия, летнее время |
| Guam | ↴ |
|  standard | Гуам |
| Gulf | ↴ |
|  standard | Персидский залив |
| Guyana | ↴ |
|  standard | Гайана |
| Hawaii_Aleutian | ↴ |
|  generic | Гавайско-алеутское время |
|  standard | Гавайско-алеутское стандартное время |
|  daylight savings | Гавайско-алеутское летнее время |
| Hong_Kong | ↴ |
|  generic | Гонконг |
|  standard | Гонконг, стандартное время |
|  daylight savings | Гонконг, летнее время |
| Hovd | ↴ |
|  generic | Ховд |
|  standard | Ховд, стандартное время |
|  daylight savings | Ховд, летнее время |
| India | ↴ |
|  standard | Индия |
| Indian_Ocean | ↴ |
|  standard | Индийский океан |
| Indochina | ↴ |
|  standard | Индокитай |
| Indonesia_Central | ↴ |
|  standard | Центральная Индонезия |
| Indonesia_Eastern | ↴ |
|  standard | Восточная Индонезия |
| Indonesia_Western | ↴ |
|  standard | Западная Индонезия |
| Iran | ↴ |
|  generic | Иран |
|  standard | Иран, стандартное время |
|  daylight savings | Иран, летнее время |
| Irkutsk | ↴ |
|  generic | Иркутск |
|  standard | Иркутск, стандартное время |
|  daylight savings | Иркутск, летнее время |
| Israel | ↴ |
|  generic | Израиль |
|  standard | Израиль, стандартное время |
|  daylight savings | Израиль, летнее время |
| Japan | ↴ |
|  generic | Япония |
|  standard | Япония, стандартное время |
|  daylight savings | Япония, летнее время |
| Kamchatka | ↴ |
|  generic | Петропавловск-Камчатский |
|  standard | Петропавловск-Камчатский, стандартное время |
|  daylight savings | Петропавловск-Камчатский, летнее время |
| Kazakhstan_Eastern | ↴ |
|  standard | Восточный Казахстан |
| Kazakhstan_Western | ↴ |
|  standard | Западный Казахстан |
| Korea | ↴ |
|  generic | Корея |
|  standard | Корея, стандартное время |
|  daylight savings | Корея, летнее время |
| Kosrae | ↴ |
|  standard | Косрае |
| Krasnoyarsk | ↴ |
|  generic | Красноярск |
|  standard | Красноярск, стандартное время |
|  daylight savings | Красноярск, летнее время |
| Kyrgystan | ↴ |
|  standard | Киргизия |
| Lanka | ↴ |
|  standard | Шри-Ланка |
| Line_Islands | ↴ |
|  standard | о-ва Лайн |
| Lord_Howe | ↴ |
|  generic | Лорд-Хау |
|  standard | Лорд-Хау, стандартное время |
|  daylight savings | Лорд-Хау, летнее время |
| Macau | ↴ |
|  generic | Макао |
|  standard | Макао, стандартное время |
|  daylight savings | Макао, летнее время |
| Macquarie | ↴ |
|  standard | Маккуори |
| Magadan | ↴ |
|  generic | Магадан |
|  standard | Магадан, стандартное время |
|  daylight savings | Магадан, летнее время |
| Malaysia | ↴ |
|  standard | Малайзия |
| Maldives | ↴ |
|  standard | Мальдивы |
| Marquesas | ↴ |
|  standard | Маркизские о-ва |
| Marshall_Islands | ↴ |
|  standard | Маршалловы Острова |
| Mauritius | ↴ |
|  generic | Маврикий |
|  standard | Маврикий, стандартное время |
|  daylight savings | Маврикий, летнее время |
| Mawson | ↴ |
|  standard | Моусон |
| Mexico_Northwest | ↴ |
|  generic | Северо-западное мексиканское время |
|  standard | Северо-западное мексиканское стандартное время |
|  daylight savings | Северо-западное мексиканское летнее время |
| Mexico_Pacific | ↴ |
|  generic | Тихоокеанское мексиканское время |
|  standard | Тихоокеанское мексиканское стандартное время |
|  daylight savings | Тихоокеанское мексиканское летнее время |
| Mongolia | ↴ |
|  generic | Улан-Батор |
|  standard | Улан-Батор, стандартное время |
|  daylight savings | Улан-Батор, летнее время |
| Moscow | ↴ |
|  generic | Москва |
|  standard | Москва, стандартное время |
|  daylight savings | Москва, летнее время |
| Myanmar | ↴ |
|  standard | Мьянма |
| Nauru | ↴ |
|  standard | Науру |
| Nepal | ↴ |
|  standard | Непал |
| New_Caledonia | ↴ |
|  generic | Новая Каледония |
|  standard | Новая Каледония, стандартное время |
|  daylight savings | Новая Каледония, летнее время |
| New_Zealand | ↴ |
|  generic | Новая Зеландия |
|  standard | Новая Зеландия, стандартное время |
|  daylight savings | Новая Зеландия, летнее время |
| Newfoundland | ↴ |
|  generic | Ньюфаундленд |
|  standard | Ньюфаундленд, стандартное время |
|  daylight savings | Ньюфаундленд, летнее время |
| Niue | ↴ |
|  standard | Ниуэ |
| Norfolk | ↴ |
|  standard | Норфолк |
| Noronha | ↴ |
|  generic | Фернанду-ди-Норонья |
|  standard | Фернанду-ди-Норонья, стандартное время |
|  daylight savings | Фернанду-ди-Норонья, летнее время |
| North_Mariana | ↴ |
|  standard | Северные Марианские о-ва |
| Novosibirsk | ↴ |
|  generic | Новосибирск |
|  standard | Новосибирск, стандартное время |
|  daylight savings | Новосибирск, летнее время |
| Omsk | ↴ |
|  generic | Омск |
|  standard | Омск, стандартное время |
|  daylight savings | Омск, летнее время |
| Pakistan | ↴ |
|  generic | Пакистан |
|  standard | Пакистан, стандартное время |
|  daylight savings | Пакистан, летнее время |
| Palau | ↴ |
|  standard | Палау |
| Papua_New_Guinea | ↴ |
|  standard | Папуа – Новая Гвинея |
| Paraguay | ↴ |
|  generic | Парагвай |
|  standard | Парагвай, стандартное время |
|  daylight savings | Парагвай, летнее время |
| Peru | ↴ |
|  generic | Перу |
|  standard | Перу, стандартное время |
|  daylight savings | Перу, летнее время |
| Philippines | ↴ |
|  generic | Филиппины |
|  standard | Филиппины, стандартное время |
|  daylight savings | Филиппины, летнее время |
| Phoenix_Islands | ↴ |
|  standard | о-ва Феникс |
| Pierre_Miquelon | ↴ |
|  generic | Сен-Пьер и Микелон |
|  standard | Сен-Пьер и Микелон, стандартное время |
|  daylight savings | Сен-Пьер и Микелон, летнее время |
| Pitcairn | ↴ |
|  standard | Питкэрн |
| Ponape | ↴ |
|  standard | Понпеи |
| Pyongyang | ↴ |
|  standard | Пхеньян |
| Qyzylorda | ↴ |
|  generic | Кызылорда* |
|  standard | Кызылорда, стандартное время* |
|  daylight savings | Кызылорда, летнее время* |
| Reunion | ↴ |
|  standard | Реюньон |
| Rothera | ↴ |
|  standard | Ротера |
| Sakhalin | ↴ |
|  generic | Сахалин |
|  standard | Сахалин, стандартное время |
|  daylight savings | Сахалин, летнее время |
| Samara | ↴ |
|  generic | Время в Самаре |
|  standard | Самарское стандартное время |
|  daylight savings | Самарское летнее время |
| Samoa | ↴ |
|  generic | Самоа |
|  standard | Самоа, стандартное время |
|  daylight savings | Самоа, летнее время |
| Seychelles | ↴ |
|  standard | Сейшельские острова |
| Singapore | ↴ |
|  standard | Сингапур |
| Solomon | ↴ |
|  standard | Соломоновы острова |
| South_Georgia | ↴ |
|  standard | Южная Георгия |
| Suriname | ↴ |
|  standard | Суринам |
| Syowa | ↴ |
|  standard | Сёва |
| Tahiti | ↴ |
|  standard | Таити |
| Taipei | ↴ |
|  generic | Тайвань |
|  standard | Тайвань, стандартное время |
|  daylight savings | Тайвань, летнее время |
| Tajikistan | ↴ |
|  standard | Таджикистан |
| Tokelau | ↴ |
|  standard | Токелау |
| Tonga | ↴ |
|  generic | Тонга |
|  standard | Тонга, стандартное время |
|  daylight savings | Тонга, летнее время |
| Truk | ↴ |
|  standard | Трук |
| Turkmenistan | ↴ |
|  generic | Туркмения |
|  standard | Туркмения, стандартное время |
|  daylight savings | Туркмения, летнее время |
| Tuvalu | ↴ |
|  standard | Тувалу |
| Uruguay | ↴ |
|  generic | Уругвай |
|  standard | Уругвай, стандартное время |
|  daylight savings | Уругвай, летнее время |
| Uzbekistan | ↴ |
|  generic | Узбекистан |
|  standard | Узбекистан, стандартное время |
|  daylight savings | Узбекистан, летнее время |
| Vanuatu | ↴ |
|  generic | Вануату |
|  standard | Вануату, стандартное время |
|  daylight savings | Вануату, летнее время |
| Venezuela | ↴ |
|  standard | Венесуэла |
| Vladivostok | ↴ |
|  generic | Владивосток |
|  standard | Владивосток, стандартное время |
|  daylight savings | Владивосток, летнее время |
| Volgograd | ↴ |
|  generic | Волгоград |
|  standard | Волгоград, стандартное время |
|  daylight savings | Волгоград, летнее время |
| Vostok | ↴ |
|  standard | Восток |
| Wake | ↴ |
|  standard | Уэйк |
| Wallis | ↴ |
|  standard | Уоллис и Футуна |
| Yakutsk | ↴ |
|  generic | Якутск |
|  standard | Якутск, стандартное время |
|  daylight savings | Якутск, летнее время |
| Yekaterinburg | ↴ |
|  generic | Екатеринбург |
|  standard | Екатеринбург, стандартное время |
|  daylight savings | Екатеринбург, летнее время |

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
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | не число |
| Time separator (Hours:Minutes) | : |

#### Decimal formatting

| Format name | Pattern |
| ----------- | ------- |
| standard,  | `#,##0.###` |
| one1000, long | `0 тысяча` |
| few1000, long | `0 тысячи` |
| many1000, long | `0 тысяч` |
| other1000, long | `0 тысячи` |
| one10000, long | `00 тысяча` |
| few10000, long | `00 тысячи` |
| many10000, long | `00 тысяч` |
| other10000, long | `00 тысячи` |
| one100000, long | `000 тысяча` |
| few100000, long | `000 тысячи` |
| many100000, long | `000 тысяч` |
| other100000, long | `000 тысячи` |
| one1000000, long | `0 миллион` |
| few1000000, long | `0 миллиона` |
| many1000000, long | `0 миллионов` |
| other1000000, long | `0 миллиона` |
| one10000000, long | `00 миллион` |
| few10000000, long | `00 миллиона` |
| many10000000, long | `00 миллионов` |
| other10000000, long | `00 миллиона` |
| one100000000, long | `000 миллион` |
| few100000000, long | `000 миллиона` |
| many100000000, long | `000 миллионов` |
| other100000000, long | `000 миллиона` |
| one1000000000, long | `0 миллиард` |
| few1000000000, long | `0 миллиарда` |
| many1000000000, long | `0 миллиардов` |
| other1000000000, long | `0 миллиарда` |
| one10000000000, long | `00 миллиард` |
| few10000000000, long | `00 миллиарда` |
| many10000000000, long | `00 миллиардов` |
| other10000000000, long | `00 миллиарда` |
| one100000000000, long | `000 миллиард` |
| few100000000000, long | `000 миллиарда` |
| many100000000000, long | `000 миллиардов` |
| other100000000000, long | `000 миллиарда` |
| one1000000000000, long | `0 триллион` |
| few1000000000000, long | `0 триллиона` |
| many1000000000000, long | `0 триллионов` |
| other1000000000000, long | `0 триллиона` |
| one10000000000000, long | `00 триллион` |
| few10000000000000, long | `00 триллиона` |
| many10000000000000, long | `00 триллионов` |
| other10000000000000, long | `00 триллиона` |
| one100000000000000, long | `000 триллион` |
| few100000000000000, long | `000 триллиона` |
| many100000000000000, long | `000 триллионов` |
| other100000000000000, long | `000 триллиона` |
| one1000, short | `0 тыс'.'` |
| few1000, short | `0 тыс'.'` |
| many1000, short | `0 тыс'.'` |
| other1000, short | `0 тыс'.'` |
| one10000, short | `00 тыс'.'` |
| few10000, short | `00 тыс'.'` |
| many10000, short | `00 тыс'.'` |
| other10000, short | `00 тыс'.'` |
| one100000, short | `000 тыс'.'` |
| few100000, short | `000 тыс'.'` |
| many100000, short | `000 тыс'.'` |
| other100000, short | `000 тыс'.'` |
| one1000000, short | `0 млн` |
| few1000000, short | `0 млн` |
| many1000000, short | `0 млн` |
| other1000000, short | `0 млн` |
| one10000000, short | `00 млн` |
| few10000000, short | `00 млн` |
| many10000000, short | `00 млн` |
| other10000000, short | `00 млн` |
| one100000000, short | `000 млн` |
| few100000000, short | `000 млн` |
| many100000000, short | `000 млн` |
| other100000000, short | `000 млн` |
| one1000000000, short | `0 млрд` |
| few1000000000, short | `0 млрд` |
| many1000000000, short | `0 млрд` |
| other1000000000, short | `0 млрд` |
| one10000000000, short | `00 млрд` |
| few10000000000, short | `00 млрд` |
| many10000000000, short | `00 млрд` |
| other10000000000, short | `00 млрд` |
| one100000000000, short | `000 млрд` |
| few100000000000, short | `000 млрд` |
| many100000000000, short | `000 млрд` |
| other100000000000, short | `000 млрд` |
| one1000000000000, short | `0 трлн` |
| few1000000000000, short | `0 трлн` |
| many1000000000000, short | `0 трлн` |
| other1000000000000, short | `0 трлн` |
| one10000000000000, short | `00 трлн` |
| few10000000000000, short | `00 трлн` |
| many10000000000000, short | `00 трлн` |
| other10000000000000, short | `00 трлн` |
| one100000000000000, short | `000 трлн` |
| few100000000000000, short | `000 трлн` |
| many100000000000000, short | `000 трлн` |
| other100000000000000, short | `000 трлн` |
| standard,  | `#E0` |
| standard,  | `#,##0 %` |
| standard,  | `#,##0.00 ¤` |
| standard,  | `#,##0.00 ¤` |
| one1000, short | `0 тыс'.' ¤` |
| few1000, short | `0 тыс'.' ¤` |
| many1000, short | `0 тыс'.' ¤` |
| other1000, short | `0 тыс'.' ¤` |
| one10000, short | `00 тыс'.' ¤` |
| few10000, short | `00 тыс'.' ¤` |
| many10000, short | `00 тыс'.' ¤` |
| other10000, short | `00 тыс'.' ¤` |
| one100000, short | `000 тыс'.' ¤` |
| few100000, short | `000 тыс'.' ¤` |
| many100000, short | `000 тыс'.' ¤` |
| other100000, short | `000 тыс'.' ¤` |
| one1000000, short | `0 млн ¤` |
| few1000000, short | `0 млн ¤` |
| many1000000, short | `0 млн ¤` |
| other1000000, short | `0 млн ¤` |
| one10000000, short | `00 млн ¤` |
| few10000000, short | `00 млн ¤` |
| many10000000, short | `00 млн ¤` |
| other10000000, short | `00 млн ¤` |
| one100000000, short | `000 млн ¤` |
| few100000000, short | `000 млн ¤` |
| many100000000, short | `000 млн ¤` |
| other100000000, short | `000 млн ¤` |
| one1000000000, short | `0 млрд ¤` |
| few1000000000, short | `0 млрд ¤` |
| many1000000000, short | `0 млрд ¤` |
| other1000000000, short | `0 млрд ¤` |
| one10000000000, short | `00 млрд ¤` |
| few10000000000, short | `00 млрд ¤` |
| many10000000000, short | `00 млрд ¤` |
| other10000000000, short | `00 млрд ¤` |
| one100000000000, short | `000 млрд ¤` |
| few100000000000, short | `000 млрд ¤` |
| many100000000000, short | `000 млрд ¤` |
| other100000000000, short | `000 млрд ¤` |
| one1000000000000, short | `0 трлн ¤` |
| few1000000000000, short | `0 трлн ¤` |
| many1000000000000, short | `0 трлн ¤` |
| other1000000000000, short | `0 трлн ¤` |
| one10000000000000, short | `00 трлн ¤` |
| few10000000000000, short | `00 трлн ¤` |
| many10000000000000, short | `00 трлн ¤` |
| other10000000000000, short | `00 трлн ¤` |
| one100000000000000, short | `000 трлн ¤` |
| few100000000000000, short | `000 трлн ¤` |
| many100000000000000, short | `000 трлн ¤` |
| other100000000000000, short | `000 трлн ¤` |
| one,  | {0} {1} |
| few,  | {0} {1} |
| many,  | {0} {1} |
| other,  | {0} {1} |

## Currency names

| Code | Name |
| ---- | ---- |
| , ADP | Андоррская песета |
| one, ADP | андоррская песета |
| few, ADP | андоррские песеты |
| many, ADP | андоррских песет |
| other, ADP | андоррских песет |
| , AED | дирхам ОАЭ |
| one, AED | дирхам ОАЭ |
| few, AED | дирхама ОАЭ |
| many, AED | дирхамов ОАЭ |
| other, AED | дирхама ОАЭ |
| , AED symbol | AED |
| , AFA | Афгани (1927–2002) |
| , AFN | афгани |
| one, AFN | афгани |
| few, AFN | афгани |
| many, AFN | афгани |
| other, AFN | афгани |
| , AFN symbol | AFN |
| , ALL | албанский лек |
| one, ALL | албанский лек |
| few, ALL | албанских лека |
| many, ALL | албанских леков |
| other, ALL | албанского лека |
| , ALL symbol | ALL |
| , AMD | армянский драм |
| one, AMD | армянский драм |
| few, AMD | армянских драма |
| many, AMD | армянских драмов |
| other, AMD | армянского драма |
| , AMD symbol | AMD |
| , ANG | нидерландский антильский гульден |
| one, ANG | нидерландский антильский гульден |
| few, ANG | нидерландских антильских гульдена |
| many, ANG | нидерландских антильских гульденов |
| other, ANG | нидерландского антильского гульдена |
| , ANG symbol | ANG |
| , AOA | ангольская кванза |
| one, AOA | ангольская кванза |
| few, AOA | ангольские кванзы |
| many, AOA | ангольских кванз |
| other, AOA | ангольской кванзы |
| , AOA symbol | AOA |
| narrow, AOA symbol | Kz |
| , AOK | Ангольская кванза (1977–1990) |
| one, AOK | ангольских кванз (1977–1991) |
| few, AOK | ангольские кванзы (1977–1991) |
| many, AOK | ангольских кванз (1977–1991) |
| other, AOK | ангольских кванз (1977–1991) |
| , AON | Ангольская новая кванза (1990–2000) |
| , AOR | Ангольская кванза реюстадо (1995–1999) |
| one, AOR | ангольских кванз реюстадо (1995–1999) |
| few, AOR | ангольские кванзы реюстадо (1995–1999) |
| many, AOR | ангольских кванз реюстадо (1995–1999) |
| other, AOR | ангольских кванз реюстадо (1995–1999) |
| , ARA | Аргентинский аустрал |
| , ARP | Аргентинское песо (1983–1985) |
| , ARS | аргентинское песо |
| one, ARS | аргентинское песо |
| few, ARS | аргентинских песо |
| many, ARS | аргентинских песо |
| other, ARS | аргентинского песо |
| , ARS symbol | ARS |
| narrow, ARS symbol | $ |
| , ATS | Австрийский шиллинг |
| , AUD | австралийский доллар |
| one, AUD | австралийский доллар |
| few, AUD | австралийских доллара |
| many, AUD | австралийских долларов |
| other, AUD | австралийского доллара |
| , AUD symbol | A$ |
| narrow, AUD symbol | $ |
| , AWG | арубанский флорин |
| one, AWG | арубанский флорин |
| few, AWG | арубанских флорина |
| many, AWG | арубанских флоринов |
| other, AWG | арубанского флорина |
| , AWG symbol | AWG |
| , AZM | Старый азербайджанский манат |
| , AZN | азербайджанский манат |
| one, AZN | азербайджанский манат |
| few, AZN | азербайджанских маната |
| many, AZN | азербайджанских манатов |
| other, AZN | азербайджанского маната |
| , AZN symbol | AZN |
| , BAD | Динар Боснии и Герцеговины |
| , BAM | конвертируемая марка Боснии и Герцеговины |
| one, BAM | конвертируемая марка Боснии и Герцеговины |
| few, BAM | конвертируемые марки Боснии и Герцеговины |
| many, BAM | конвертируемых марок Боснии и Герцеговины |
| other, BAM | конвертируемой марки Боснии и Герцеговины |
| , BAM symbol | BAM |
| narrow, BAM symbol | KM |
| , BBD | барбадосский доллар |
| one, BBD | барбадосский доллар |
| few, BBD | барбадосских доллара |
| many, BBD | барбадосских долларов |
| other, BBD | барбадосского доллара |
| , BBD symbol | BBD |
| narrow, BBD symbol | $ |
| , BDT | бангладешская така |
| one, BDT | бангладешская така |
| few, BDT | бангладешские таки |
| many, BDT | бангладешских так |
| other, BDT | бангладешской таки |
| , BDT symbol | BDT |
| narrow, BDT symbol | ৳ |
| , BEC | Бельгийский франк (конвертируемый) |
| , BEF | Бельгийский франк |
| , BEL | Бельгийский франк (финансовый) |
| , BGL | Лев |
| , BGN | болгарский лев |
| one, BGN | болгарский лев |
| few, BGN | болгарских лева |
| many, BGN | болгарских левов |
| other, BGN | болгарского лева |
| , BGN symbol | BGN |
| , BHD | бахрейнский динар |
| one, BHD | бахрейнский динар |
| few, BHD | бахрейнских динара |
| many, BHD | бахрейнских динаров |
| other, BHD | бахрейнского динара |
| , BHD symbol | BHD |
| , BIF | бурундийский франк |
| one, BIF | бурундийский франк |
| few, BIF | бурундийских франка |
| many, BIF | бурундийских франков |
| other, BIF | бурундийского франка |
| , BIF symbol | BIF |
| , BMD | бермудский доллар |
| one, BMD | бермудский доллар |
| few, BMD | бермудских доллара |
| many, BMD | бермудских долларов |
| other, BMD | бермудского доллара |
| , BMD symbol | BMD |
| narrow, BMD symbol | $ |
| , BND | брунейский доллар |
| one, BND | брунейский доллар |
| few, BND | брунейских доллара |
| many, BND | брунейских долларов |
| other, BND | брунейского доллара |
| , BND symbol | BND |
| narrow, BND symbol | $ |
| , BOB | боливийский боливиано |
| one, BOB | боливийский боливиано |
| few, BOB | боливийских боливиано |
| many, BOB | боливийских боливиано |
| other, BOB | боливийского боливиано |
| , BOB symbol | BOB |
| narrow, BOB symbol | Bs |
| , BOP | Боливийское песо |
| , BOV | Боливийский мвдол |
| , BRB | Бразильский новый крузейро (1967–1986) |
| , BRC | Бразильское крузадо |
| , BRE | Бразильский крузейро (1990–1993) |
| , BRL | бразильский реал |
| one, BRL | бразильский реал |
| few, BRL | бразильских реала |
| many, BRL | бразильских реалов |
| other, BRL | бразильского реала |
| , BRL symbol | R$ |
| narrow, BRL symbol | R$ |
| , BRN | Бразильское новое крузадо |
| , BRR | Бразильский крузейро |
| , BSD | багамский доллар |
| one, BSD | багамский доллар |
| few, BSD | багамских доллара |
| many, BSD | багамских долларов |
| other, BSD | багамского доллара |
| , BSD symbol | BSD |
| narrow, BSD symbol | $ |
| , BTN | бутанский нгултрум |
| one, BTN | бутанский нгултрум |
| few, BTN | бутанских нгултрума |
| many, BTN | бутанских нгултрумов |
| other, BTN | бутанского нгултрума |
| , BTN symbol | BTN |
| , BUK | Джа |
| , BWP | ботсванская пула |
| one, BWP | ботсванская пула |
| few, BWP | ботсванские пулы |
| many, BWP | ботсванских пул |
| other, BWP | ботсванской пулы |
| , BWP symbol | BWP |
| narrow, BWP symbol | P |
| , BYB | Белорусский рубль (1994–1999) |
| , BYN | белорусский рубль |
| one, BYN | белорусский рубль |
| few, BYN | белорусских рубля |
| many, BYN | белорусских рублей |
| other, BYN | белорусского рубля |
| , BYN symbol | BYN |
| narrow, BYN symbol | р. |
| , BYR | Белорусский рубль (2000–2016) |
| one, BYR | белорусский рубль (2000–2016) |
| few, BYR | белорусских рубля (2000–2016) |
| many, BYR | белорусских рублей (2000–2016) |
| other, BYR | белорусского рубля (2000–2016) |
| , BYR symbol | BYR |
| , BZD | белизский доллар |
| one, BZD | белизский доллар |
| few, BZD | белизских доллара |
| many, BZD | белизских долларов |
| other, BZD | белизского доллара |
| , BZD symbol | BZD |
| narrow, BZD symbol | $ |
| , CAD | канадский доллар |
| one, CAD | канадский доллар |
| few, CAD | канадских доллара |
| many, CAD | канадских долларов |
| other, CAD | канадского доллара |
| , CAD symbol | CA$ |
| narrow, CAD symbol | $ |
| , CDF | конголезский франк |
| one, CDF | конголезский франк |
| few, CDF | конголезских франка |
| many, CDF | конголезских франков |
| other, CDF | конголезского франка |
| , CDF symbol | CDF |
| , CHE | WIR евро |
| , CHF | швейцарский франк |
| one, CHF | швейцарский франк |
| few, CHF | швейцарских франка |
| many, CHF | швейцарских франков |
| other, CHF | швейцарского франка |
| , CHF symbol | CHF |
| , CHW | WIR франк |
| , CLF | Условная расчетная единица Чили |
| , CLP | чилийское песо |
| one, CLP | чилийское песо |
| few, CLP | чилийских песо |
| many, CLP | чилийских песо |
| other, CLP | чилийского песо |
| , CLP symbol | CLP |
| narrow, CLP symbol | $ |
| , CNH | китайский офшорный юань |
| one, CNH | китайский офшорный юань |
| few, CNH | китайских офшорных юаня |
| many, CNH | китайских офшорных юаней |
| other, CNH | китайского офшорного юаня |
| , CNH symbol | CNH |
| , CNY | китайский юань |
| one, CNY | китайский юань |
| few, CNY | китайских юаня |
| many, CNY | китайских юаней |
| other, CNY | китайского юаня |
| , CNY symbol | CN¥ |
| narrow, CNY symbol | ¥ |
| , COP | колумбийское песо |
| one, COP | колумбийское песо |
| few, COP | колумбийских песо |
| many, COP | колумбийских песо |
| other, COP | колумбийского песо |
| , COP symbol | COP |
| narrow, COP symbol | $ |
| , COU | Единица реальной стоимости Колумбии |
| , CRC | костариканский колон |
| one, CRC | костариканский колон |
| few, CRC | костариканских колона |
| many, CRC | костариканских колонов |
| other, CRC | костариканского колона |
| , CRC symbol | CRC |
| narrow, CRC symbol | ₡ |
| , CSD | Старый Сербский динар |
| , CSK | Чехословацкая твердая крона |
| , CUC | кубинское конвертируемое песо |
| one, CUC | кубинское конвертируемое песо |
| few, CUC | кубинских конвертируемых песо |
| many, CUC | кубинских конвертируемых песо |
| other, CUC | кубинского конвертируемого песо |
| , CUC symbol | CUC |
| narrow, CUC symbol | $ |
| , CUP | кубинское песо |
| one, CUP | кубинское песо |
| few, CUP | кубинских песо |
| many, CUP | кубинских песо |
| other, CUP | кубинского песо |
| , CUP symbol | CUP |
| narrow, CUP symbol | $ |
| , CVE | эскудо Кабо-Верде |
| one, CVE | эскудо Кабо-Верде |
| few, CVE | эскудо Кабо-Верде |
| many, CVE | эскудо Кабо-Верде |
| other, CVE | эскудо Кабо-Верде |
| , CVE symbol | CVE |
| , CYP | Кипрский фунт |
| , CZK | чешская крона |
| one, CZK | чешская крона |
| few, CZK | чешские кроны |
| many, CZK | чешских крон |
| other, CZK | чешской кроны |
| , CZK symbol | CZK |
| narrow, CZK symbol | Kč |
| , DDM | Восточногерманская марка |
| , DEM | Немецкая марка |
| , DJF | франк Джибути |
| one, DJF | франк Джибути |
| few, DJF | франка Джибути |
| many, DJF | франков Джибути |
| other, DJF | франка Джибути |
| , DJF symbol | DJF |
| , DKK | датская крона |
| one, DKK | датская крона |
| few, DKK | датские кроны |
| many, DKK | датских крон |
| other, DKK | датской кроны |
| , DKK symbol | DKK |
| narrow, DKK symbol | kr |
| , DOP | доминиканское песо |
| one, DOP | доминиканское песо |
| few, DOP | доминиканских песо |
| many, DOP | доминиканских песо |
| other, DOP | доминиканского песо |
| , DOP symbol | DOP |
| narrow, DOP symbol | $ |
| , DZD | алжирский динар |
| one, DZD | алжирский динар |
| few, DZD | алжирских динара |
| many, DZD | алжирских динаров |
| other, DZD | алжирского динара |
| , DZD symbol | DZD |
| , ECS | Эквадорский сукре |
| , ECV | Постоянная единица стоимости Эквадора |
| , EEK | Эстонская крона |
| , EGP | египетский фунт |
| one, EGP | египетский фунт |
| few, EGP | египетских фунта |
| many, EGP | египетских фунтов |
| other, EGP | египетского фунта |
| , EGP symbol | EGP |
| narrow, EGP symbol | E£ |
| , ERN | эритрейская накфа |
| one, ERN | эритрейская накфа |
| few, ERN | эритрейские накфы |
| many, ERN | эритрейских накф |
| other, ERN | эритрейской накфы |
| , ERN symbol | ERN |
| , ESA | Испанская песета (А) |
| , ESB | Испанская песета (конвертируемая) |
| , ESP | Испанская песета |
| , ETB | эфиопский быр |
| one, ETB | эфиопский быр |
| few, ETB | эфиопских быра |
| many, ETB | эфиопских быров |
| other, ETB | эфиопского быра |
| , ETB symbol | ETB |
| , EUR | евро |
| one, EUR | евро |
| few, EUR | евро |
| many, EUR | евро |
| other, EUR | евро |
| , EUR symbol | € |
| narrow, EUR symbol | € |
| , FIM | Финская марка |
| , FJD | доллар Фиджи |
| one, FJD | доллар Фиджи |
| few, FJD | доллара Фиджи |
| many, FJD | долларов Фиджи |
| other, FJD | доллара Фиджи |
| , FJD symbol | FJD |
| narrow, FJD symbol | $ |
| , FKP | фунт Фолклендских островов |
| one, FKP | фунт Фолклендских островов |
| few, FKP | фунта Фолклендских островов |
| many, FKP | фунтов Фолклендских островов |
| other, FKP | фунта Фолклендских островов |
| , FKP symbol | FKP |
| narrow, FKP symbol | £ |
| , FRF | Французский франк |
| , GBP | британский фунт стерлингов |
| one, GBP | британский фунт стерлингов |
| few, GBP | британских фунта стерлингов |
| many, GBP | британских фунтов стерлингов |
| other, GBP | британского фунта стерлингов |
| , GBP symbol | £ |
| narrow, GBP symbol | £ |
| , GEK | Грузинский купон |
| , GEL | грузинский лари |
| one, GEL | грузинский лари |
| few, GEL | грузинских лари |
| many, GEL | грузинских лари |
| other, GEL | грузинского лари |
| , GEL symbol | GEL |
| narrow, GEL symbol | ლ |
| variant, GEL symbol | ₾ |
| , GHC | Ганский седи (1979–2007) |
| , GHS | ганский седи |
| one, GHS | ганский седи |
| few, GHS | ганских седи |
| many, GHS | ганских седи |
| other, GHS | ганского седи |
| , GHS symbol | GHS |
| , GIP | гибралтарский фунт |
| one, GIP | гибралтарский фунт |
| few, GIP | гибралтарских фунта |
| many, GIP | гибралтарских фунтов |
| other, GIP | гибралтарского фунта |
| , GIP symbol | GIP |
| narrow, GIP symbol | £ |
| , GMD | гамбийский даласи |
| one, GMD | гамбийский даласи |
| few, GMD | гамбийских даласи |
| many, GMD | гамбийских даласи |
| other, GMD | гамбийского даласи |
| , GMD symbol | GMD |
| , GNF | гвинейский франк |
| one, GNF | гвинейский франк |
| few, GNF | гвинейских франка |
| many, GNF | гвинейских франков |
| other, GNF | гвинейского франка |
| , GNF symbol | GNF |
| narrow, GNF symbol | FG |
| , GNS | Гвинейская сили |
| , GQE | Эквеле экваториальной Гвинеи |
| , GRD | Греческая драхма |
| , GTQ | гватемальский кетсаль |
| one, GTQ | гватемальский кетсаль |
| few, GTQ | гватемальских кетсаля |
| many, GTQ | гватемальских кетсалей |
| other, GTQ | гватемальского кетсаля |
| , GTQ symbol | GTQ |
| narrow, GTQ symbol | Q |
| , GWE | Эскудо Португальской Гвинеи |
| , GWP | Песо Гвинеи-Бисау |
| , GYD | гайанский доллар |
| one, GYD | гайанский доллар |
| few, GYD | гайанских доллара |
| many, GYD | гайанских долларов |
| other, GYD | гайанского доллара |
| , GYD symbol | GYD |
| narrow, GYD symbol | $ |
| , HKD | гонконгский доллар |
| one, HKD | гонконгский доллар |
| few, HKD | гонконгских доллара |
| many, HKD | гонконгских долларов |
| other, HKD | гонконгского доллара |
| , HKD symbol | HK$ |
| narrow, HKD symbol | $ |
| , HNL | гондурасская лемпира |
| one, HNL | гондурасская лемпира |
| few, HNL | гондурасские лемпиры |
| many, HNL | гондурасских лемпир |
| other, HNL | гондурасской лемпиры |
| , HNL symbol | HNL |
| narrow, HNL symbol | L |
| , HRD | Хорватский динар |
| , HRK | хорватская куна |
| one, HRK | хорватская куна |
| few, HRK | хорватские куны |
| many, HRK | хорватских кун |
| other, HRK | хорватской куны |
| , HRK symbol | HRK |
| narrow, HRK symbol | kn |
| , HTG | гаитянский гурд |
| one, HTG | гаитянский гурд |
| few, HTG | гаитянских гурда |
| many, HTG | гаитянских гурдов |
| other, HTG | гаитянского гурда |
| , HTG symbol | HTG |
| , HUF | венгерский форинт |
| one, HUF | венгерский форинт |
| few, HUF | венгерских форинта |
| many, HUF | венгерских форинтов |
| other, HUF | венгерского форинта |
| , HUF symbol | HUF |
| narrow, HUF symbol | Ft |
| , IDR | индонезийская рупия |
| one, IDR | индонезийская рупия |
| few, IDR | индонезийские рупии |
| many, IDR | индонезийских рупий |
| other, IDR | индонезийской рупии |
| , IDR symbol | IDR |
| narrow, IDR symbol | Rp |
| , IEP | Ирландский фунт |
| , ILP | Израильский фунт |
| , ILS | новый израильский шекель |
| one, ILS | новый израильский шекель |
| few, ILS | новых израильских шекеля |
| many, ILS | новых израильских шекелей |
| other, ILS | нового израильского шекеля |
| , ILS symbol | ₪ |
| narrow, ILS symbol | ₪ |
| , INR | индийская рупия |
| one, INR | индийская рупия |
| few, INR | индийские рупии |
| many, INR | индийских рупий |
| other, INR | индийской рупии |
| , INR symbol | ₹ |
| narrow, INR symbol | ₹ |
| , IQD | иракский динар |
| one, IQD | иракский динар |
| few, IQD | иракских динара |
| many, IQD | иракских динаров |
| other, IQD | иракского динара |
| , IQD symbol | IQD |
| , IRR | иранский риал |
| one, IRR | иранский риал |
| few, IRR | иранских риала |
| many, IRR | иранских риалов |
| other, IRR | иранского риала |
| , IRR symbol | IRR |
| , ISK | исландская крона |
| one, ISK | исландская крона |
| few, ISK | исландские кроны |
| many, ISK | исландских крон |
| other, ISK | исландской кроны |
| , ISK symbol | ISK |
| narrow, ISK symbol | kr |
| , ITL | Итальянская лира |
| , JMD | ямайский доллар |
| one, JMD | ямайский доллар |
| few, JMD | ямайских доллара |
| many, JMD | ямайских долларов |
| other, JMD | ямайского доллара |
| , JMD symbol | JMD |
| narrow, JMD symbol | $ |
| , JOD | иорданский динар |
| one, JOD | иорданский динар |
| few, JOD | иорданских динара |
| many, JOD | иорданских динаров |
| other, JOD | иорданского динара |
| , JOD symbol | JOD |
| , JPY | японская иена |
| one, JPY | японская иена |
| few, JPY | японские иены |
| many, JPY | японских иен |
| other, JPY | японской иены |
| , JPY symbol | ¥ |
| narrow, JPY symbol | ¥ |
| , KES | кенийский шиллинг |
| one, KES | кенийский шиллинг |
| few, KES | кенийских шиллинга |
| many, KES | кенийских шиллингов |
| other, KES | кенийского шиллинга |
| , KES symbol | KES |
| , KGS | киргизский сом |
| one, KGS | киргизский сом |
| few, KGS | киргизских сома |
| many, KGS | киргизских сомов |
| other, KGS | киргизского сома |
| , KGS symbol | KGS |
| , KHR | камбоджийский риель |
| one, KHR | камбоджийский риель |
| few, KHR | камбоджийских риеля |
| many, KHR | камбоджийских риелей |
| other, KHR | камбоджийского риеля |
| , KHR symbol | KHR |
| narrow, KHR symbol | ៛ |
| , KMF | франк Коморских островов |
| one, KMF | франк Коморских островов |
| few, KMF | франка Коморских островов |
| many, KMF | франков Коморских островов |
| other, KMF | франка Коморских островов |
| , KMF symbol | KMF |
| narrow, KMF symbol | CF |
| , KPW | северокорейская вона |
| one, KPW | северокорейская вона |
| few, KPW | северокорейские воны |
| many, KPW | северокорейских вон |
| other, KPW | северокорейской воны |
| , KPW symbol | KPW |
| narrow, KPW symbol | ₩ |
| , KRW | южнокорейская вона |
| one, KRW | южнокорейская вона |
| few, KRW | южнокорейские воны |
| many, KRW | южнокорейских вон |
| other, KRW | южнокорейской воны |
| , KRW symbol | ₩ |
| narrow, KRW symbol | ₩ |
| , KWD | кувейтский динар |
| one, KWD | кувейтский динар |
| few, KWD | кувейтских динара |
| many, KWD | кувейтских динаров |
| other, KWD | кувейтского динара |
| , KWD symbol | KWD |
| , KYD | доллар Каймановых островов |
| one, KYD | доллар Каймановых островов |
| few, KYD | доллара Каймановых островов |
| many, KYD | долларов Каймановых островов |
| other, KYD | доллара Каймановых островов |
| , KYD symbol | KYD |
| narrow, KYD symbol | $ |
| , KZT | казахский тенге |
| one, KZT | казахский тенге |
| few, KZT | казахских тенге |
| many, KZT | казахских тенге |
| other, KZT | казахского тенге |
| , KZT symbol | KZT |
| narrow, KZT symbol | ₸ |
| , LAK | лаосский кип |
| one, LAK | лаосский кип |
| few, LAK | лаосских кипа |
| many, LAK | лаосских кипов |
| other, LAK | лаосского кипа |
| , LAK symbol | LAK |
| narrow, LAK symbol | ₭ |
| , LBP | ливанский фунт |
| one, LBP | ливанский фунт |
| few, LBP | ливанских фунта |
| many, LBP | ливанских фунтов |
| other, LBP | ливанского фунта |
| , LBP symbol | LBP |
| narrow, LBP symbol | L£ |
| , LKR | шри-ланкийская рупия |
| one, LKR | шри-ланкийская рупия |
| few, LKR | шри-ланкийские рупии |
| many, LKR | шри-ланкийских рупий |
| other, LKR | шри-ланкийской рупии |
| , LKR symbol | LKR |
| narrow, LKR symbol | Rs |
| , LRD | либерийский доллар |
| one, LRD | либерийский доллар |
| few, LRD | либерийских доллара |
| many, LRD | либерийских долларов |
| other, LRD | либерийского доллара |
| , LRD symbol | LRD |
| narrow, LRD symbol | $ |
| , LSL | Лоти |
| , LTL | Литовский лит |
| one, LTL | литовский лит |
| few, LTL | литовских лита |
| many, LTL | литовских литов |
| other, LTL | литовского лита |
| , LTL symbol | LTL |
| , LTT | Литовский талон |
| , LUC | Конвертируемый франк Люксембурга |
| , LUF | Люксембургский франк |
| , LUL | Финансовый франк Люксембурга |
| , LVL | Латвийский лат |
| one, LVL | латвийский лат |
| few, LVL | латвийских лата |
| many, LVL | латвийских латов |
| other, LVL | латвийского лата |
| , LVL symbol | LVL |
| , LVR | Латвийский рубль |
| , LYD | ливийский динар |
| one, LYD | ливийский динар |
| few, LYD | ливийских динара |
| many, LYD | ливийских динаров |
| other, LYD | ливийского динара |
| , LYD symbol | LYD |
| , MAD | марокканский дирхам |
| one, MAD | марокканский дирхам |
| few, MAD | марокканских дирхама |
| many, MAD | марокканских дирхамов |
| other, MAD | марокканского дирхама |
| , MAD symbol | MAD |
| , MAF | Марокканский франк |
| , MDL | молдавский лей |
| one, MDL | молдавский лей |
| few, MDL | молдавских лея |
| many, MDL | молдавских леев |
| other, MDL | молдавского лея |
| , MDL symbol | MDL |
| , MGA | малагасийский ариари |
| one, MGA | малагасийский ариари |
| few, MGA | малагасийских ариари |
| many, MGA | малагасийских ариари |
| other, MGA | малагасийского ариари |
| , MGA symbol | MGA |
| narrow, MGA symbol | Ar |
| , MGF | Малагасийский франк |
| , MKD | македонский денар |
| one, MKD | македонский денар |
| few, MKD | македонских денара |
| many, MKD | македонских денаров |
| other, MKD | македонского денара |
| , MKD symbol | MKD |
| , MLF | Малийский франк |
| , MMK | мьянманский кьят |
| one, MMK | мьянманский кьят |
| few, MMK | мьянманских кьята |
| many, MMK | мьянманских кьятов |
| other, MMK | мьянманского кьята |
| , MMK symbol | MMK |
| narrow, MMK symbol | K |
| , MNT | монгольский тугрик |
| one, MNT | монгольский тугрик |
| few, MNT | монгольских тугрика |
| many, MNT | монгольских тугриков |
| other, MNT | монгольского тугрика |
| , MNT symbol | MNT |
| narrow, MNT symbol | ₮ |
| , MOP | патака Макао |
| one, MOP | патака Макао |
| few, MOP | патаки Макао |
| many, MOP | патак Макао |
| other, MOP | патаки Макао |
| , MOP symbol | MOP |
| , MRO | мавританская угия |
| one, MRO | мавританская угия |
| few, MRO | мавританские угии |
| many, MRO | мавританских угий |
| other, MRO | мавританской угии |
| , MRO symbol | MRO |
| , MTL | Мальтийская лира |
| , MTP | Мальтийский фунт |
| , MUR | маврикийская рупия |
| one, MUR | маврикийская рупия |
| few, MUR | маврикийские рупии |
| many, MUR | маврикийских рупий |
| other, MUR | маврикийской рупии |
| , MUR symbol | MUR |
| narrow, MUR symbol | Rs |
| , MVR | мальдивская руфия |
| one, MVR | мальдивская руфия |
| few, MVR | мальдивские руфии |
| many, MVR | мальдивских руфий |
| other, MVR | мальдивской руфии |
| , MVR symbol | MVR |
| , MWK | малавийская квача |
| one, MWK | малавийская квача |
| few, MWK | малавийские квачи |
| many, MWK | малавийских квач |
| other, MWK | малавийской квачи |
| , MWK symbol | MWK |
| , MXN | мексиканское песо |
| one, MXN | мексиканское песо |
| few, MXN | мексиканских песо |
| many, MXN | мексиканских песо |
| other, MXN | мексиканского песо |
| , MXN symbol | MX$ |
| narrow, MXN symbol | $ |
| , MXP | Мексиканское серебряное песо (1861–1992) |
| , MXV | Мексиканская пересчетная единица (UDI) |
| , MYR | малайзийский ринггит |
| one, MYR | малайзийский ринггит |
| few, MYR | малайзийских ринггита |
| many, MYR | малайзийских ринггитов |
| other, MYR | малайзийского ринггита |
| , MYR symbol | MYR |
| narrow, MYR symbol | RM |
| , MZE | Мозамбикское эскудо |
| , MZM | Старый мозамбикский метикал |
| , MZN | мозамбикский метикал |
| one, MZN | мозамбикский метикал |
| few, MZN | мозамбикских метикала |
| many, MZN | мозамбикских метикалов |
| other, MZN | мозамбикского метикала |
| , MZN symbol | MZN |
| , NAD | доллар Намибии |
| one, NAD | доллар Намибии |
| few, NAD | доллара Намибии |
| many, NAD | долларов Намибии |
| other, NAD | доллара Намибии |
| , NAD symbol | NAD |
| narrow, NAD symbol | $ |
| , NGN | нигерийская найра |
| one, NGN | нигерийская найра |
| few, NGN | нигерийские найры |
| many, NGN | нигерийских найр |
| other, NGN | нигерийской найры |
| , NGN symbol | NGN |
| narrow, NGN symbol | ₦ |
| , NIC | Никарагуанская кордоба (1988–1991) |
| , NIO | никарагуанская кордоба |
| one, NIO | никарагуанская кордоба |
| few, NIO | никарагуанские кордобы |
| many, NIO | никарагуанских кордоб |
| other, NIO | никарагуанской кордобы |
| , NIO symbol | NIO |
| narrow, NIO symbol | C$ |
| , NLG | Нидерландский гульден |
| , NOK | норвежская крона |
| one, NOK | норвежская крона |
| few, NOK | норвежские кроны |
| many, NOK | норвежских крон |
| other, NOK | норвежской кроны |
| , NOK symbol | NOK |
| narrow, NOK symbol | kr |
| , NPR | непальская рупия |
| one, NPR | непальская рупия |
| few, NPR | непальские рупии |
| many, NPR | непальских рупий |
| other, NPR | непальской рупии |
| , NPR symbol | NPR |
| narrow, NPR symbol | Rs |
| , NZD | новозеландский доллар |
| one, NZD | новозеландский доллар |
| few, NZD | новозеландских доллара |
| many, NZD | новозеландских долларов |
| other, NZD | новозеландского доллара |
| , NZD symbol | NZ$ |
| narrow, NZD symbol | $ |
| , OMR | оманский риал |
| one, OMR | оманский риал |
| few, OMR | оманских риала |
| many, OMR | оманских риалов |
| other, OMR | оманского риала |
| , OMR symbol | OMR |
| , PAB | панамский бальбоа |
| one, PAB | панамский бальбоа |
| few, PAB | панамских бальбоа |
| many, PAB | панамских бальбоа |
| other, PAB | панамского бальбоа |
| , PAB symbol | PAB |
| , PEI | Перуанское инти |
| , PEN | перуанский соль |
| one, PEN | перуанский соль |
| few, PEN | перуанских соля |
| many, PEN | перуанских солей |
| other, PEN | перуанского соля |
| , PEN symbol | PEN |
| , PES | Перуанский соль (1863–1965) |
| one, PES | перуанский соль (1863–1965) |
| few, PES | перуанских соля (1863–1965) |
| many, PES | перуанских солей (1863–1965) |
| other, PES | перуанского соля (1863–1965) |
| , PES symbol | PES |
| , PGK | кина Папуа – Новой Гвинеи |
| one, PGK | кина Папуа – Новой Гвинеи |
| few, PGK | кины Папуа – Новой Гвинеи |
| many, PGK | кин Папуа – Новой Гвинеи |
| other, PGK | кины Папуа – Новой Гвинеи |
| , PGK symbol | PGK |
| , PHP | филиппинское песо |
| one, PHP | филиппинское песо |
| few, PHP | филиппинских песо |
| many, PHP | филиппинских песо |
| other, PHP | филиппинского песо |
| , PHP symbol | PHP |
| narrow, PHP symbol | ₱ |
| , PKR | пакистанская рупия |
| one, PKR | пакистанская рупия |
| few, PKR | пакистанские рупии |
| many, PKR | пакистанских рупий |
| other, PKR | пакистанской рупии |
| , PKR symbol | PKR |
| narrow, PKR symbol | Rs |
| , PLN | польский злотый |
| one, PLN | польский злотый |
| few, PLN | польских злотых |
| many, PLN | польских злотых |
| other, PLN | польского злотого |
| , PLN symbol | PLN |
| narrow, PLN symbol | zł |
| , PLZ | Злотый |
| , PTE | Португальское эскудо |
| , PYG | парагвайский гуарани |
| one, PYG | парагвайский гуарани |
| few, PYG | парагвайских гуарани |
| many, PYG | парагвайских гуарани |
| other, PYG | парагвайского гуарани |
| , PYG symbol | PYG |
| narrow, PYG symbol | ₲ |
| , QAR | катарский риал |
| one, QAR | катарский риал |
| few, QAR | катарских риала |
| many, QAR | катарских риалов |
| other, QAR | катарского риала |
| , QAR symbol | QAR |
| , RHD | Родезийский доллар |
| , ROL | Старый Румынский лей |
| , RON | румынский лей |
| one, RON | румынский лей |
| few, RON | румынских лея |
| many, RON | румынских леев |
| other, RON | румынского лея |
| , RON symbol | RON |
| narrow, RON symbol | L |
| , RSD | сербский динар |
| one, RSD | сербский динар |
| few, RSD | сербских динара |
| many, RSD | сербских динаров |
| other, RSD | сербского динара |
| , RSD symbol | RSD |
| , RUB | российский рубль |
| one, RUB | российский рубль |
| few, RUB | российских рубля |
| many, RUB | российских рублей |
| other, RUB | российского рубля |
| , RUB symbol | ₽ |
| narrow, RUB symbol | ₽ |
| , RUR | Российский рубль (1991–1998) |
| , RUR symbol | р. |
| , RWF | франк Руанды |
| one, RWF | франк Руанды |
| few, RWF | франка Руанды |
| many, RWF | франков Руанды |
| other, RWF | франка Руанды |
| , RWF symbol | RWF |
| narrow, RWF symbol | RF |
| , SAR | саудовский риял |
| one, SAR | саудовский риял |
| few, SAR | саудовских рияла |
| many, SAR | саудовских риялов |
| other, SAR | саудовского рияла |
| , SAR symbol | SAR |
| , SBD | доллар Соломоновых островов |
| one, SBD | доллар Соломоновых островов |
| few, SBD | доллара Соломоновых островов |
| many, SBD | долларов Соломоновых островов |
| other, SBD | доллара Соломоновых островов |
| , SBD symbol | SBD |
| narrow, SBD symbol | $ |
| , SCR | сейшельская рупия |
| one, SCR | сейшельская рупия |
| few, SCR | сейшельские рупии |
| many, SCR | сейшельских рупий |
| other, SCR | сейшельской рупии |
| , SCR symbol | SCR |
| , SDD | Суданский динар |
| , SDG | суданский фунт |
| one, SDG | суданский фунт |
| few, SDG | суданских фунта |
| many, SDG | суданских фунтов |
| other, SDG | суданского фунта |
| , SDG symbol | SDG |
| , SDP | Старый суданский фунт |
| , SEK | шведская крона |
| one, SEK | шведская крона |
| few, SEK | шведские кроны |
| many, SEK | шведских крон |
| other, SEK | шведской кроны |
| , SEK symbol | SEK |
| narrow, SEK symbol | kr |
| , SGD | сингапурский доллар |
| one, SGD | сингапурский доллар |
| few, SGD | сингапурских доллара |
| many, SGD | сингапурских долларов |
| other, SGD | сингапурского доллара |
| , SGD symbol | SGD |
| narrow, SGD symbol | $ |
| , SHP | фунт острова Святой Елены |
| one, SHP | фунт острова Святой Елены |
| few, SHP | фунта острова Святой Елены |
| many, SHP | фунтов острова Святой Елены |
| other, SHP | фунта острова Святой Елены |
| , SHP symbol | SHP |
| narrow, SHP symbol | £ |
| , SIT | Словенский толар |
| , SKK | Словацкая крона |
| , SLL | леоне |
| one, SLL | леоне |
| few, SLL | леоне |
| many, SLL | леоне |
| other, SLL | леоне |
| , SLL symbol | SLL |
| , SOS | сомалийский шиллинг |
| one, SOS | сомалийский шиллинг |
| few, SOS | сомалийских шиллинга |
| many, SOS | сомалийских шиллингов |
| other, SOS | сомалийского шиллинга |
| , SOS symbol | SOS |
| , SRD | суринамский доллар |
| one, SRD | суринамский доллар |
| few, SRD | суринамских доллара |
| many, SRD | суринамских долларов |
| other, SRD | суринамского доллара |
| , SRD symbol | SRD |
| narrow, SRD symbol | $ |
| , SRG | Суринамский гульден |
| , SSP | южносуданский фунт |
| one, SSP | южносуданский фунт |
| few, SSP | южносуданских фунта |
| many, SSP | южносуданских фунтов |
| other, SSP | южносуданского фунта |
| , SSP symbol | SSP |
| narrow, SSP symbol | £ |
| , STD | добра Сан-Томе и Принсипи (1977–2017) |
| one, STD | добра Сан-Томе и Принсипи (1977–2017) |
| few, STD | добры Сан-Томе и Принсипи (1977–2017) |
| many, STD | добр Сан-Томе и Принсипи (1977–2017) |
| other, STD | добры Сан-Томе и Принсипи (1977–2017) |
| , STD symbol | STD |
| , STN | добра Сан-Томе и Принсипи |
| one, STN | добра Сан-Томе и Принсипи |
| few, STN | добры Сан-Томе и Принсипи |
| many, STN | добр Сан-Томе и Принсипи |
| other, STN | добры Сан-Томе и Принсипи |
| , STN symbol | STN |
| narrow, STN symbol | Db |
| , SUR | Рубль СССР |
| , SVC | Сальвадорский колон |
| , SYP | сирийский фунт |
| one, SYP | сирийский фунт |
| few, SYP | сирийских фунта |
| many, SYP | сирийских фунтов |
| other, SYP | сирийского фунта |
| , SYP symbol | SYP |
| narrow, SYP symbol | £ |
| , SZL | свазилендский лилангени |
| one, SZL | свазилендский лилангени |
| few, SZL | свазилендских лилангени |
| many, SZL | свазилендских лилангени |
| other, SZL | свазилендского лилангени |
| , SZL symbol | SZL |
| , THB | таиландский бат |
| one, THB | таиландский бат |
| few, THB | таиландских бата |
| many, THB | таиландских батов |
| other, THB | таиландского бата |
| , THB symbol | ฿ |
| narrow, THB symbol | ฿ |
| , TJR | Таджикский рубль |
| , TJS | таджикский сомони |
| one, TJS | таджикский сомони |
| few, TJS | таджикских сомони |
| many, TJS | таджикских сомони |
| other, TJS | таджикского сомони |
| , TJS symbol | TJS |
| , TMM | Туркменский манат |
| , TMT | новый туркменский манат |
| one, TMT | новый туркменский манат |
| few, TMT | новых туркменских маната |
| many, TMT | новых туркменских манатов |
| other, TMT | нового туркменского маната |
| , TMT symbol | ТМТ |
| , TND | тунисский динар |
| one, TND | тунисский динар |
| few, TND | тунисских динара |
| many, TND | тунисских динаров |
| other, TND | тунисского динара |
| , TND symbol | TND |
| , TOP | тонганская паанга |
| one, TOP | тонганская паанга |
| few, TOP | тонганские паанги |
| many, TOP | тонганских паанг |
| other, TOP | тонганской паанги |
| , TOP symbol | TOP |
| narrow, TOP symbol | T$ |
| , TPE | Тиморское эскудо |
| , TRL | Турецкая лира (1922–2005) |
| one, TRL | турецкая лира (1922–2005) |
| few, TRL | турецкие лиры (1922–2005) |
| many, TRL | турецких лир (1922–2005) |
| other, TRL | турецкой лиры (1922–2005) |
| , TRY | турецкая лира |
| one, TRY | турецкая лира |
| few, TRY | турецкие лиры |
| many, TRY | турецких лир |
| other, TRY | турецкой лиры |
| , TRY symbol | TRY |
| narrow, TRY symbol | ₺ |
| variant, TRY symbol | TL |
| , TTD | доллар Тринидада и Тобаго |
| one, TTD | доллар Тринидада и Тобаго |
| few, TTD | доллара Тринидада и Тобаго |
| many, TTD | долларов Тринидада и Тобаго |
| other, TTD | доллара Тринидада и Тобаго |
| , TTD symbol | TTD |
| narrow, TTD symbol | $ |
| , TWD | новый тайваньский доллар |
| one, TWD | новый тайваньский доллар |
| few, TWD | новых тайваньских доллара |
| many, TWD | новых тайваньских долларов |
| other, TWD | нового тайваньского доллара |
| , TWD symbol | NT$ |
| narrow, TWD symbol | NT$ |
| , TZS | танзанийский шиллинг |
| one, TZS | танзанийский шиллинг |
| few, TZS | танзанийских шиллинга |
| many, TZS | танзанийских шиллингов |
| other, TZS | танзанийского шиллинга |
| , TZS symbol | TZS |
| , UAH | украинская гривна |
| one, UAH | украинская гривна |
| few, UAH | украинские гривны |
| many, UAH | украинских гривен |
| other, UAH | украинской гривны |
| , UAH symbol | ₴ |
| narrow, UAH symbol | ₴ |
| variant, UAH symbol | грн. |
| , UAK | Карбованец (украинский) |
| , UGS | Старый угандийский шиллинг |
| , UGX | угандийский шиллинг |
| one, UGX | угандийский шиллинг |
| few, UGX | угандийских шиллинга |
| many, UGX | угандийских шиллингов |
| other, UGX | угандийского шиллинга |
| , UGX symbol | UGX |
| , USD | доллар США |
| one, USD | доллар США |
| few, USD | доллара США |
| many, USD | долларов США |
| other, USD | доллара США |
| , USD symbol | $ |
| narrow, USD symbol | $ |
| , USN | Доллар США следующего дня |
| , USS | Доллар США текущего дня |
| , UYI | Уругвайский песо (индекс инфляции) |
| , UYP | Уругвайское старое песо (1975–1993) |
| , UYU | уругвайское песо |
| one, UYU | уругвайское песо |
| few, UYU | уругвайских песо |
| many, UYU | уругвайских песо |
| other, UYU | уругвайского песо |
| , UYU symbol | UYU |
| narrow, UYU symbol | $ |
| , UZS | узбекский сум |
| one, UZS | узбекский сум |
| few, UZS | узбекских сума |
| many, UZS | узбекских сумов |
| other, UZS | узбекского сума |
| , UZS symbol | UZS |
| , VEB | Венесуэльский боливар (1871–2008) |
| , VEF | венесуэльский боливар |
| one, VEF | венесуэльский боливар |
| few, VEF | венесуэльских боливара |
| many, VEF | венесуэльских боливаров |
| other, VEF | венесуэльского боливара |
| , VEF symbol | VEF |
| narrow, VEF symbol | Bs |
| , VND | вьетнамский донг |
| one, VND | вьетнамский донг |
| few, VND | вьетнамских донга |
| many, VND | вьетнамских донгов |
| other, VND | вьетнамского донга |
| , VND symbol | ₫ |
| narrow, VND symbol | ₫ |
| , VUV | вату Вануату |
| one, VUV | вату Вануату |
| few, VUV | вату Вануату |
| many, VUV | вату Вануату |
| other, VUV | вату Вануату |
| , VUV symbol | VUV |
| , WST | самоанская тала |
| one, WST | самоанская тала |
| few, WST | самоанские талы |
| many, WST | самоанских тал |
| other, WST | самоанской талы |
| , WST symbol | WST |
| , XAF | франк КФА BEAC |
| one, XAF | франк КФА ВЕАС |
| few, XAF | франка КФА ВЕАС |
| many, XAF | франков КФА ВЕАС |
| other, XAF | франка КФА ВЕАС |
| , XAF symbol | FCFA |
| , XAG | Серебро |
| , XAU | Золото |
| , XBA | Европейская составная единица |
| , XBB | Европейская денежная единица |
| , XBC | расчетная единица европейского валютного соглашения (XBC) |
| , XBD | расчетная единица европейского валютного соглашения (XBD) |
| , XCD | восточно-карибский доллар |
| one, XCD | восточно-карибский доллар |
| few, XCD | восточно-карибских доллара |
| many, XCD | восточно-карибских долларов |
| other, XCD | восточно-карибского доллара |
| , XCD symbol | EC$ |
| narrow, XCD symbol | $ |
| , XDR | СДР (специальные права заимствования) |
| , XEU | ЭКЮ (единица европейской валюты) |
| , XFO | Французский золотой франк |
| , XFU | Французский UIC-франк |
| , XOF | франк КФА ВСЕАО |
| one, XOF | франк КФА ВСЕАО |
| few, XOF | франка КФА ВСЕАО |
| many, XOF | франков КФА ВСЕАО |
| other, XOF | франка КФА ВСЕАО |
| , XOF symbol | CFA |
| , XPD | Палладий |
| , XPF | французский тихоокеанский франк |
| one, XPF | французский тихоокеанский франк |
| few, XPF | французских тихоокеанских франка |
| many, XPF | французских тихоокеанских франков |
| other, XPF | французского тихоокеанского франка |
| , XPF symbol | CFPF |
| , XPT | Платина |
| , XRE | единица RINET-фондов |
| , XTS | тестовый валютный код |
| , XXX | неизвестная валюта |
| one, XXX | единица неизвестной валюты |
| few, XXX | единицы неизвестной валюты |
| many, XXX | единиц неизвестной валюты |
| other, XXX | единицы неизвестной валюты |
| , XXX symbol | XXXX |
| , YDD | Йеменский динар |
| , YER | йеменский риал |
| one, YER | йеменский риал |
| few, YER | йеменских риала |
| many, YER | йеменских риалов |
| other, YER | йеменского риала |
| , YER symbol | YER |
| , YUD | Югославский твердый динар |
| , YUM | Югославский новый динар |
| , YUN | Югославский динар |
| , ZAL | Южноафриканский рэнд (финансовый) |
| , ZAR | южноафриканский рэнд |
| one, ZAR | южноафриканский рэнд |
| few, ZAR | южноафриканских рэнда |
| many, ZAR | южноафриканских рэндов |
| other, ZAR | южноафриканского рэнда |
| , ZAR symbol | ZAR |
| narrow, ZAR symbol | R |
| , ZMK | Квача (замбийская) (1968–2012) |
| one, ZMK | замбийская квача (1968–2012) |
| few, ZMK | замбийские квачи (1968–2012) |
| many, ZMK | замбийских квач (1968–2012) |
| other, ZMK | замбийской квачи (1968–2012) |
| , ZMW | замбийская квача |
| one, ZMW | замбийская квача |
| few, ZMW | замбийские квачи |
| many, ZMW | замбийских квач |
| other, ZMW | замбийской квачи |
| , ZMW symbol | ZMW |
| narrow, ZMW symbol | ZK |
| , ZRN | Новый заир |
| , ZRZ | Заир |
| , ZWD | Доллар Зимбабве |
| , ZWL | Доллар Зимбабве (2009) |

Other stuff:

| atLeast,  | `⩾{0}` |
| range,  | `{0}–{1}` |

Examples:

| plural one example | из {0} книги за {0} день |
| plural few example | из {0} книг за {0} дня |
| plural many example | из {0} книг за {0} дней |
| plural other example | из {0} книги за {0} дня |
| ordinal  example | Сверните направо на {0}-м перекрестке. |

## Units

| Code | Name |
| ---- | ---- |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ↴ |
| , acceleration-g-force | ускорение свободного падения |
| one, acceleration-g-force | {0} g |
| few, acceleration-g-force | {0} g |
| many, acceleration-g-force | {0} g |
| other, acceleration-g-force | {0} g |
| acceleration-meter-per-second-squared | ↴ |
| , acceleration-meter-per-second-squared | метры в секунду в квадрате |
| one, acceleration-meter-per-second-squared | {0} метр в секунду в квадрате |
| few, acceleration-meter-per-second-squared | {0} метра в секунду в квадрате |
| many, acceleration-meter-per-second-squared | {0} метров в секунду в квадрате |
| other, acceleration-meter-per-second-squared | {0} метра в секунду в квадрате |
| angle-revolution | ↴ |
| , angle-revolution | оборот |
| one, angle-revolution | {0} оборот |
| few, angle-revolution | {0} оборота |
| many, angle-revolution | {0} оборотов |
| other, angle-revolution | {0} оборота |
| angle-radian | ↴ |
| , angle-radian | радианы |
| one, angle-radian | {0} радиан |
| few, angle-radian | {0} радиана |
| many, angle-radian | {0} радиан |
| other, angle-radian | {0} радиана |
| angle-degree | ↴ |
| , angle-degree | градусы |
| one, angle-degree | {0} градус |
| few, angle-degree | {0} градуса |
| many, angle-degree | {0} градусов |
| other, angle-degree | {0} градуса |
| angle-arc-minute | ↴ |
| , angle-arc-minute | минуты |
| one, angle-arc-minute | {0} минута |
| few, angle-arc-minute | {0} минуты |
| many, angle-arc-minute | {0} минут |
| other, angle-arc-minute | {0} минуты |
| angle-arc-second | ↴ |
| , angle-arc-second | секунды |
| one, angle-arc-second | {0} секунда |
| few, angle-arc-second | {0} секунды |
| many, angle-arc-second | {0} секунд |
| other, angle-arc-second | {0} секунды |
| area-square-kilometer | ↴ |
| , area-square-kilometer | квадратные километры |
| one, area-square-kilometer | {0} квадратный километр |
| few, area-square-kilometer | {0} квадратных километра |
| many, area-square-kilometer | {0} квадратных километров |
| other, area-square-kilometer | {0} квадратного километра |
| per units of area-square-kilometer | {0} на квадратный километр |
| area-hectare | ↴ |
| , area-hectare | гектары |
| one, area-hectare | {0} гектар |
| few, area-hectare | {0} гектара |
| many, area-hectare | {0} гектаров |
| other, area-hectare | {0} гектара |
| area-square-meter | ↴ |
| , area-square-meter | квадратные метры |
| one, area-square-meter | {0} квадратный метр |
| few, area-square-meter | {0} квадратных метра |
| many, area-square-meter | {0} квадратных метров |
| other, area-square-meter | {0} квадратного метра |
| per units of area-square-meter | {0} на квадратный метр |
| area-square-centimeter | ↴ |
| , area-square-centimeter | квадратные сантиметры |
| one, area-square-centimeter | {0} квадратный сантиметр |
| few, area-square-centimeter | {0} квадратных сантиметра |
| many, area-square-centimeter | {0} квадратных сантиметров |
| other, area-square-centimeter | {0} квадратного сантиметра |
| per units of area-square-centimeter | {0} на квадратный сантиметр |
| area-square-mile | ↴ |
| , area-square-mile | квадратные мили |
| one, area-square-mile | {0} квадратная миля |
| few, area-square-mile | {0} квадратные мили |
| many, area-square-mile | {0} квадратных миль |
| other, area-square-mile | {0} квадратной мили |
| per units of area-square-mile | {0} на квадратную милю |
| area-acre | ↴ |
| , area-acre | акры |
| one, area-acre | {0} акр |
| few, area-acre | {0} акра |
| many, area-acre | {0} акров |
| other, area-acre | {0} акра |
| area-square-yard | ↴ |
| , area-square-yard | квадратные ярды |
| one, area-square-yard | {0} квадратный ярд |
| few, area-square-yard | {0} квадратных ярда |
| many, area-square-yard | {0} квадратных ярдов |
| other, area-square-yard | {0} квадратного ярда |
| area-square-foot | ↴ |
| , area-square-foot | квадратные футы |
| one, area-square-foot | {0} квадратный фут |
| few, area-square-foot | {0} квадратных фута |
| many, area-square-foot | {0} квадратных футов |
| other, area-square-foot | {0} квадратного фута |
| area-square-inch | ↴ |
| , area-square-inch | квадратные дюймы |
| one, area-square-inch | {0} квадратный дюйм |
| few, area-square-inch | {0} квадратных дюйма |
| many, area-square-inch | {0} квадратных дюймов |
| other, area-square-inch | {0} квадратного дюйма |
| per units of area-square-inch | {0} на квадратный дюйм |
| concentr-karat | ↴ |
| , concentr-karat | караты |
| one, concentr-karat | {0} карат |
| few, concentr-karat | {0} карата |
| many, concentr-karat | {0} карат |
| other, concentr-karat | {0} карата |
| concentr-milligram-per-deciliter | ↴ |
| , concentr-milligram-per-deciliter | миллиграммы на децилитр |
| one, concentr-milligram-per-deciliter | {0} миллиграмм на децилитр |
| few, concentr-milligram-per-deciliter | {0} миллиграмма на децилитр |
| many, concentr-milligram-per-deciliter | {0} миллиграммов на децилитр |
| other, concentr-milligram-per-deciliter | {0} миллиграмма на децилитр |
| concentr-millimole-per-liter | ↴ |
| , concentr-millimole-per-liter | миллимоли на литр |
| one, concentr-millimole-per-liter | {0} миллимоль на литр |
| few, concentr-millimole-per-liter | {0} миллимоля на литр |
| many, concentr-millimole-per-liter | {0} миллимолей на литр |
| other, concentr-millimole-per-liter | {0} миллимоля на литр |
| concentr-part-per-million | ↴ |
| , concentr-part-per-million | миллионные доли |
| one, concentr-part-per-million | {0} миллионная доля |
| few, concentr-part-per-million | {0} миллионные доли |
| many, concentr-part-per-million | {0} миллионных долей |
| other, concentr-part-per-million | {0} миллионной доли |
| consumption-liter-per-kilometer | ↴ |
| , consumption-liter-per-kilometer | литры на километр |
| one, consumption-liter-per-kilometer | {0} литр на километр |
| few, consumption-liter-per-kilometer | {0} литра на километр |
| many, consumption-liter-per-kilometer | {0} литров на километр |
| other, consumption-liter-per-kilometer | {0} литра на километр |
| consumption-liter-per-100kilometers | ↴ |
| , consumption-liter-per-100kilometers | литры на 100 километров |
| one, consumption-liter-per-100kilometers | {0} литр на 100 километров |
| few, consumption-liter-per-100kilometers | {0} литра на 100 километров |
| many, consumption-liter-per-100kilometers | {0} литров на 100 километров |
| other, consumption-liter-per-100kilometers | {0} литра на 100 километров |
| consumption-mile-per-gallon | ↴ |
| , consumption-mile-per-gallon | мили на галлон |
| one, consumption-mile-per-gallon | {0} миля на галлон |
| few, consumption-mile-per-gallon | {0} мили на галлон |
| many, consumption-mile-per-gallon | {0} миль на галлон |
| other, consumption-mile-per-gallon | {0} мили на галлон |
| consumption-mile-per-gallon-imperial | ↴ |
| , consumption-mile-per-gallon-imperial | мили на имп. галлон |
| one, consumption-mile-per-gallon-imperial | {0} миля на имп. галлон |
| few, consumption-mile-per-gallon-imperial | {0} мили на имп. галлон |
| many, consumption-mile-per-gallon-imperial | {0} миль на имп. галлон |
| other, consumption-mile-per-gallon-imperial | {0} мили на имп. галлон |
| digital-terabyte | ↴ |
| , digital-terabyte | терабайты |
| one, digital-terabyte | {0} терабайт |
| few, digital-terabyte | {0} терабайта |
| many, digital-terabyte | {0} терабайт |
| other, digital-terabyte | {0} терабайта |
| digital-terabit | ↴ |
| , digital-terabit | терабиты |
| one, digital-terabit | {0} терабит |
| few, digital-terabit | {0} терабита |
| many, digital-terabit | {0} терабит |
| other, digital-terabit | {0} терабита |
| digital-gigabyte | ↴ |
| , digital-gigabyte | гигабайты |
| one, digital-gigabyte | {0} гигабайт |
| few, digital-gigabyte | {0} гигабайта |
| many, digital-gigabyte | {0} гигабайт |
| other, digital-gigabyte | {0} гигабайта |
| digital-gigabit | ↴ |
| , digital-gigabit | гигабиты |
| one, digital-gigabit | {0} гигабит |
| few, digital-gigabit | {0} гигабита |
| many, digital-gigabit | {0} гигабит |
| other, digital-gigabit | {0} гигабита |
| digital-megabyte | ↴ |
| , digital-megabyte | мегабайты |
| one, digital-megabyte | {0} мегабайт |
| few, digital-megabyte | {0} мегабайта |
| many, digital-megabyte | {0} мегабайт |
| other, digital-megabyte | {0} мегабайта |
| digital-megabit | ↴ |
| , digital-megabit | мегабиты |
| one, digital-megabit | {0} мегабит |
| few, digital-megabit | {0} мегабита |
| many, digital-megabit | {0} мегабит |
| other, digital-megabit | {0} мегабита |
| digital-kilobyte | ↴ |
| , digital-kilobyte | килобайты |
| one, digital-kilobyte | {0} килобайт |
| few, digital-kilobyte | {0} килобайта |
| many, digital-kilobyte | {0} килобайт |
| other, digital-kilobyte | {0} килобайта |
| digital-kilobit | ↴ |
| , digital-kilobit | килобиты |
| one, digital-kilobit | {0} килобит |
| few, digital-kilobit | {0} килобита |
| many, digital-kilobit | {0} килобит |
| other, digital-kilobit | {0} килобита |
| digital-byte | ↴ |
| , digital-byte | байты |
| one, digital-byte | {0} байт |
| few, digital-byte | {0} байта |
| many, digital-byte | {0} байт |
| other, digital-byte | {0} байта |
| digital-bit | ↴ |
| , digital-bit | биты |
| one, digital-bit | {0} бит |
| few, digital-bit | {0} бита |
| many, digital-bit | {0} бит |
| other, digital-bit | {0} бита |
| duration-century | ↴ |
| , duration-century | века |
| one, duration-century | {0} век |
| few, duration-century | {0} века |
| many, duration-century | {0} веков |
| other, duration-century | {0} века |
| duration-year | ↴ |
| , duration-year | годы |
| one, duration-year | {0} год |
| few, duration-year | {0} года |
| many, duration-year | {0} лет |
| other, duration-year | {0} года |
| per units of duration-year | {0} в год |
| duration-month | ↴ |
| , duration-month | месяцы |
| one, duration-month | {0} месяц |
| few, duration-month | {0} месяца |
| many, duration-month | {0} месяцев |
| other, duration-month | {0} месяца |
| per units of duration-month | {0} в месяц |
| duration-week | ↴ |
| , duration-week | недели |
| one, duration-week | {0} неделя |
| few, duration-week | {0} недели |
| many, duration-week | {0} недель |
| other, duration-week | {0} недели |
| per units of duration-week | {0} в неделю |
| duration-day | ↴ |
| , duration-day | дни |
| one, duration-day | {0} день |
| few, duration-day | {0} дня |
| many, duration-day | {0} дней |
| other, duration-day | {0} дня |
| per units of duration-day | {0} в день |
| duration-hour | ↴ |
| , duration-hour | часы |
| one, duration-hour | {0} час |
| few, duration-hour | {0} часа |
| many, duration-hour | {0} часов |
| other, duration-hour | {0} часа |
| per units of duration-hour | {0} в час |
| duration-minute | ↴ |
| , duration-minute | минуты |
| one, duration-minute | {0} минута |
| few, duration-minute | {0} минуты |
| many, duration-minute | {0} минут |
| other, duration-minute | {0} минуты |
| per units of duration-minute | {0} в минуту |
| duration-second | ↴ |
| , duration-second | секунды |
| one, duration-second | {0} секунда |
| few, duration-second | {0} секунды |
| many, duration-second | {0} секунд |
| other, duration-second | {0} секунды |
| per units of duration-second | {0} в секунду |
| duration-millisecond | ↴ |
| , duration-millisecond | миллисекунды |
| one, duration-millisecond | {0} миллисекунда |
| few, duration-millisecond | {0} миллисекунды |
| many, duration-millisecond | {0} миллисекунд |
| other, duration-millisecond | {0} миллисекунды |
| duration-microsecond | ↴ |
| , duration-microsecond | микросекунды |
| one, duration-microsecond | {0} микросекунда |
| few, duration-microsecond | {0} микросекунды |
| many, duration-microsecond | {0} микросекунд |
| other, duration-microsecond | {0} микросекунды |
| duration-nanosecond | ↴ |
| , duration-nanosecond | наносекунды |
| one, duration-nanosecond | {0} наносекунда |
| few, duration-nanosecond | {0} наносекунды |
| many, duration-nanosecond | {0} наносекунд |
| other, duration-nanosecond | {0} наносекунды |
| electric-ampere | ↴ |
| , electric-ampere | амперы |
| one, electric-ampere | {0} ампер |
| few, electric-ampere | {0} ампера |
| many, electric-ampere | {0} ампер |
| other, electric-ampere | {0} ампера |
| electric-milliampere | ↴ |
| , electric-milliampere | миллиамперы |
| one, electric-milliampere | {0} миллиампер |
| few, electric-milliampere | {0} миллиампера |
| many, electric-milliampere | {0} миллиампер |
| other, electric-milliampere | {0} миллиампера |
| electric-ohm | ↴ |
| , electric-ohm | омы |
| one, electric-ohm | {0} ом |
| few, electric-ohm | {0} ома |
| many, electric-ohm | {0} ом |
| other, electric-ohm | {0} ома |
| electric-volt | ↴ |
| , electric-volt | вольты |
| one, electric-volt | {0} вольт |
| few, electric-volt | {0} вольта |
| many, electric-volt | {0} вольт |
| other, electric-volt | {0} вольта |
| energy-kilocalorie | ↴ |
| , energy-kilocalorie | килокалории |
| one, energy-kilocalorie | {0} килокалория |
| few, energy-kilocalorie | {0} килокалории |
| many, energy-kilocalorie | {0} килокалорий |
| other, energy-kilocalorie | {0} килокалории |
| energy-calorie | ↴ |
| , energy-calorie | калории |
| one, energy-calorie | {0} калория |
| few, energy-calorie | {0} калории |
| many, energy-calorie | {0} калорий |
| other, energy-calorie | {0} калории |
| energy-foodcalorie | ↴ |
| , energy-foodcalorie | калории |
| one, energy-foodcalorie | {0} калория |
| few, energy-foodcalorie | {0} калории |
| many, energy-foodcalorie | {0} калорий |
| other, energy-foodcalorie | {0} калории |
| energy-kilojoule | ↴ |
| , energy-kilojoule | килоджоули |
| one, energy-kilojoule | {0} килоджоуль |
| few, energy-kilojoule | {0} килоджоуля |
| many, energy-kilojoule | {0} килоджоулей |
| other, energy-kilojoule | {0} килоджоуля |
| energy-joule | ↴ |
| , energy-joule | джоули |
| one, energy-joule | {0} джоуль |
| few, energy-joule | {0} джоуля |
| many, energy-joule | {0} джоулей |
| other, energy-joule | {0} джоуля |
| energy-kilowatt-hour | ↴ |
| , energy-kilowatt-hour | киловатт-часы |
| one, energy-kilowatt-hour | {0} киловатт-час |
| few, energy-kilowatt-hour | {0} киловатт-часа |
| many, energy-kilowatt-hour | {0} киловатт-часов |
| other, energy-kilowatt-hour | {0} киловатт-часа |
| frequency-gigahertz | ↴ |
| , frequency-gigahertz | гигагерцы |
| one, frequency-gigahertz | {0} гигагерц |
| few, frequency-gigahertz | {0} гигагерца |
| many, frequency-gigahertz | {0} гигагерц |
| other, frequency-gigahertz | {0} гигагерца |
| frequency-megahertz | ↴ |
| , frequency-megahertz | мегагерцы |
| one, frequency-megahertz | {0} мегагерц |
| few, frequency-megahertz | {0} мегагерца |
| many, frequency-megahertz | {0} мегагерц |
| other, frequency-megahertz | {0} мегагерца |
| frequency-kilohertz | ↴ |
| , frequency-kilohertz | килогерцы |
| one, frequency-kilohertz | {0} килогерц |
| few, frequency-kilohertz | {0} килогерца |
| many, frequency-kilohertz | {0} килогерц |
| other, frequency-kilohertz | {0} килогерца |
| frequency-hertz | ↴ |
| , frequency-hertz | герцы |
| one, frequency-hertz | {0} герц |
| few, frequency-hertz | {0} герца |
| many, frequency-hertz | {0} герц |
| other, frequency-hertz | {0} герца |
| length-kilometer | ↴ |
| , length-kilometer | километры |
| one, length-kilometer | {0} километр |
| few, length-kilometer | {0} километра |
| many, length-kilometer | {0} километров |
| other, length-kilometer | {0} километра |
| per units of length-kilometer | {0} на километр |
| length-meter | ↴ |
| , length-meter | метры |
| one, length-meter | {0} метр |
| few, length-meter | {0} метра |
| many, length-meter | {0} метров |
| other, length-meter | {0} метра |
| per units of length-meter | {0} на метр |
| length-decimeter | ↴ |
| , length-decimeter | дециметры |
| one, length-decimeter | {0} дециметр |
| few, length-decimeter | {0} дециметра |
| many, length-decimeter | {0} дециметров |
| other, length-decimeter | {0} дециметра |
| length-centimeter | ↴ |
| , length-centimeter | сантиметры |
| one, length-centimeter | {0} сантиметр |
| few, length-centimeter | {0} сантиметра |
| many, length-centimeter | {0} сантиметров |
| other, length-centimeter | {0} сантиметра |
| per units of length-centimeter | {0} на сантиметр |
| length-millimeter | ↴ |
| , length-millimeter | миллиметры |
| one, length-millimeter | {0} миллиметр |
| few, length-millimeter | {0} миллиметра |
| many, length-millimeter | {0} миллиметров |
| other, length-millimeter | {0} миллиметра |
| length-micrometer | ↴ |
| , length-micrometer | микрометры |
| one, length-micrometer | {0} микрометр |
| few, length-micrometer | {0} микрометра |
| many, length-micrometer | {0} микрометров |
| other, length-micrometer | {0} микрометра |
| length-nanometer | ↴ |
| , length-nanometer | нанометры |
| one, length-nanometer | {0} нанометр |
| few, length-nanometer | {0} нанометра |
| many, length-nanometer | {0} нанометров |
| other, length-nanometer | {0} нанометра |
| length-picometer | ↴ |
| , length-picometer | пикометры |
| one, length-picometer | {0} пикометр |
| few, length-picometer | {0} пикометра |
| many, length-picometer | {0} пикометров |
| other, length-picometer | {0} пикометра |
| length-mile | ↴ |
| , length-mile | мили |
| one, length-mile | {0} миля |
| few, length-mile | {0} мили |
| many, length-mile | {0} миль |
| other, length-mile | {0} мили |
| length-yard | ↴ |
| , length-yard | ярды |
| one, length-yard | {0} ярд |
| few, length-yard | {0} ярда |
| many, length-yard | {0} ярдов |
| other, length-yard | {0} ярда |
| length-foot | ↴ |
| , length-foot | футы |
| one, length-foot | {0} фут |
| few, length-foot | {0} фута |
| many, length-foot | {0} футов |
| other, length-foot | {0} фута |
| per units of length-foot | {0} на фут |
| length-inch | ↴ |
| , length-inch | дюймы |
| one, length-inch | {0} дюйм |
| few, length-inch | {0} дюйма |
| many, length-inch | {0} дюймов |
| other, length-inch | {0} дюйма |
| per units of length-inch | {0} на дюйм |
| length-parsec | ↴ |
| , length-parsec | парсеки |
| one, length-parsec | {0} парсек |
| few, length-parsec | {0} парсека |
| many, length-parsec | {0} парсеков |
| other, length-parsec | {0} парсека |
| length-light-year | ↴ |
| , length-light-year | световые годы |
| one, length-light-year | {0} световой год |
| few, length-light-year | {0} световых года |
| many, length-light-year | {0} световых лет |
| other, length-light-year | {0} светового года |
| length-astronomical-unit | ↴ |
| , length-astronomical-unit | астрономические единицы |
| one, length-astronomical-unit | {0} астрономическая единица |
| few, length-astronomical-unit | {0} астрономические единицы |
| many, length-astronomical-unit | {0} астрономических единиц |
| other, length-astronomical-unit | {0} астрономической единицы |
| length-furlong | ↴ |
| , length-furlong | фурлонги |
| one, length-furlong | {0} фурлонг |
| few, length-furlong | {0} фурлонга |
| many, length-furlong | {0} фурлонгов |
| other, length-furlong | {0} фурлонга |
| length-fathom | ↴ |
| , length-fathom | морские сажени |
| one, length-fathom | {0} морская сажень |
| few, length-fathom | {0} морских сажени |
| many, length-fathom | {0} морских саженей |
| other, length-fathom | {0} морской сажени |
| length-nautical-mile | ↴ |
| , length-nautical-mile | морские мили |
| one, length-nautical-mile | {0} морская миля |
| few, length-nautical-mile | {0} морские мили |
| many, length-nautical-mile | {0} морских миль |
| other, length-nautical-mile | {0} морской мили |
| length-mile-scandinavian | ↴ |
| , length-mile-scandinavian | скандинавские мили |
| one, length-mile-scandinavian | {0} скандинавская миля |
| few, length-mile-scandinavian | {0} скандинавские мили |
| many, length-mile-scandinavian | {0} скандинавских миль |
| other, length-mile-scandinavian | {0} скандинавской мили |
| length-point | ↴ |
| , length-point | пункты |
| one, length-point | {0} пункт |
| few, length-point | {0} пункта |
| many, length-point | {0} пунктов |
| other, length-point | {0} пункта |
| light-lux | ↴ |
| , light-lux | люксы |
| one, light-lux | {0} люкс |
| few, light-lux | {0} люкса |
| many, light-lux | {0} люкс |
| other, light-lux | {0} люкса |
| mass-metric-ton | ↴ |
| , mass-metric-ton | тонны |
| one, mass-metric-ton | {0} тонна |
| few, mass-metric-ton | {0} тонны |
| many, mass-metric-ton | {0} тонн |
| other, mass-metric-ton | {0} тонны |
| mass-kilogram | ↴ |
| , mass-kilogram | килограммы |
| one, mass-kilogram | {0} килограмм |
| few, mass-kilogram | {0} килограмма |
| many, mass-kilogram | {0} килограмм |
| other, mass-kilogram | {0} килограмма |
| per units of mass-kilogram | {0} на килограмм |
| mass-gram | ↴ |
| , mass-gram | граммы |
| one, mass-gram | {0} грамм |
| few, mass-gram | {0} грамма |
| many, mass-gram | {0} грамм |
| other, mass-gram | {0} грамма |
| per units of mass-gram | {0} на грамм |
| mass-milligram | ↴ |
| , mass-milligram | миллиграммы |
| one, mass-milligram | {0} миллиграмм |
| few, mass-milligram | {0} миллиграмма |
| many, mass-milligram | {0} миллиграммов |
| other, mass-milligram | {0} миллиграмма |
| mass-microgram | ↴ |
| , mass-microgram | микрограммы |
| one, mass-microgram | {0} микрограмм |
| few, mass-microgram | {0} микрограмма |
| many, mass-microgram | {0} микрограммов |
| other, mass-microgram | {0} микрограмма |
| mass-ton | ↴ |
| , mass-ton | американские тонны |
| one, mass-ton | {0} американская тонна |
| few, mass-ton | {0} американские тонны |
| many, mass-ton | {0} американских тонн |
| other, mass-ton | {0} американской тонны |
| mass-stone | ↴ |
| , mass-stone | стоуны |
| one, mass-stone | {0} стоун |
| few, mass-stone | {0} стоуна |
| many, mass-stone | {0} стоунов |
| other, mass-stone | {0} стоуна |
| mass-pound | ↴ |
| , mass-pound | фунты |
| one, mass-pound | {0} фунт |
| few, mass-pound | {0} фунта |
| many, mass-pound | {0} фунтов |
| other, mass-pound | {0} фунта |
| per units of mass-pound | {0} на фунт |
| mass-ounce | ↴ |
| , mass-ounce | унции |
| one, mass-ounce | {0} унция |
| few, mass-ounce | {0} унции |
| many, mass-ounce | {0} унций |
| other, mass-ounce | {0} унции |
| per units of mass-ounce | {0} на унцию |
| mass-ounce-troy | ↴ |
| , mass-ounce-troy | тройские унции |
| one, mass-ounce-troy | {0} тройская унция |
| few, mass-ounce-troy | {0} тройские унции |
| many, mass-ounce-troy | {0} тройских унций |
| other, mass-ounce-troy | {0} тройской унции |
| mass-carat | ↴ |
| , mass-carat | караты |
| one, mass-carat | {0} карат |
| few, mass-carat | {0} карата |
| many, mass-carat | {0} карат |
| other, mass-carat | {0} карата |
| power-gigawatt | ↴ |
| , power-gigawatt | гигаватты |
| one, power-gigawatt | {0} гигаватт |
| few, power-gigawatt | {0} гигаватта |
| many, power-gigawatt | {0} гигаватт |
| other, power-gigawatt | {0} гигаватта |
| power-megawatt | ↴ |
| , power-megawatt | мегаватты |
| one, power-megawatt | {0} мегаватт |
| few, power-megawatt | {0} мегаватта |
| many, power-megawatt | {0} мегаватт |
| other, power-megawatt | {0} мегаватта |
| power-kilowatt | ↴ |
| , power-kilowatt | киловатты |
| one, power-kilowatt | {0} киловатт |
| few, power-kilowatt | {0} киловатта |
| many, power-kilowatt | {0} киловатт |
| other, power-kilowatt | {0} киловатта |
| power-watt | ↴ |
| , power-watt | ватты |
| one, power-watt | {0} ватт |
| few, power-watt | {0} ватта |
| many, power-watt | {0} ватт |
| other, power-watt | {0} ватта |
| power-milliwatt | ↴ |
| , power-milliwatt | милливатты |
| one, power-milliwatt | {0} милливатт |
| few, power-milliwatt | {0} милливатта |
| many, power-milliwatt | {0} милливатт |
| other, power-milliwatt | {0} милливатта |
| power-horsepower | ↴ |
| , power-horsepower | лошадиные силы |
| one, power-horsepower | {0} лошадиная сила |
| few, power-horsepower | {0} лошадиные силы |
| many, power-horsepower | {0} лошадиных сил |
| other, power-horsepower | {0} лошадиной силы |
| pressure-hectopascal | ↴ |
| , pressure-hectopascal | гектопаскали |
| one, pressure-hectopascal | {0} гектопаскаль |
| few, pressure-hectopascal | {0} гектопаскаля |
| many, pressure-hectopascal | {0} гектопаскалей |
| other, pressure-hectopascal | {0} гектопаскаля |
| pressure-millimeter-of-mercury | ↴ |
| , pressure-millimeter-of-mercury | миллиметры ртутного столба |
| one, pressure-millimeter-of-mercury | {0} миллиметр ртутного столба |
| few, pressure-millimeter-of-mercury | {0} миллиметра ртутного столба |
| many, pressure-millimeter-of-mercury | {0} миллиметров ртутного столба |
| other, pressure-millimeter-of-mercury | {0} миллиметра ртутного столба |
| pressure-pound-per-square-inch | ↴ |
| , pressure-pound-per-square-inch | фунты на квадратный дюйм |
| one, pressure-pound-per-square-inch | {0} фунт на квадратный дюйм |
| few, pressure-pound-per-square-inch | {0} фунта на квадратный дюйм |
| many, pressure-pound-per-square-inch | {0} фунтов на квадратный дюйм |
| other, pressure-pound-per-square-inch | {0} фунта на квадратный дюйм |
| pressure-inch-hg | ↴ |
| , pressure-inch-hg | дюймы ртутного столба |
| one, pressure-inch-hg | {0} дюйм ртутного столба |
| few, pressure-inch-hg | {0} дюйма ртутного столба |
| many, pressure-inch-hg | {0} дюймов ртутного столба |
| other, pressure-inch-hg | {0} дюйма ртутного столба |
| pressure-millibar | ↴ |
| , pressure-millibar | миллибары |
| one, pressure-millibar | {0} миллибар |
| few, pressure-millibar | {0} миллибара |
| many, pressure-millibar | {0} миллибар |
| other, pressure-millibar | {0} миллибара |
| speed-kilometer-per-hour | ↴ |
| , speed-kilometer-per-hour | километры в час |
| one, speed-kilometer-per-hour | {0} километр в час |
| few, speed-kilometer-per-hour | {0} километра в час |
| many, speed-kilometer-per-hour | {0} километров в час |
| other, speed-kilometer-per-hour | {0} километра в час |
| speed-meter-per-second | ↴ |
| , speed-meter-per-second | метры в секунду |
| one, speed-meter-per-second | {0} метр в секунду |
| few, speed-meter-per-second | {0} метра в секундыу |
| many, speed-meter-per-second | {0} метров в секунду |
| other, speed-meter-per-second | {0} метра в секунду |
| speed-mile-per-hour | ↴ |
| , speed-mile-per-hour | мили в час |
| one, speed-mile-per-hour | {0} миля в час |
| few, speed-mile-per-hour | {0} мили в час |
| many, speed-mile-per-hour | {0} миль в час |
| other, speed-mile-per-hour | {0} мили в час |
| speed-knot | ↴ |
| , speed-knot | узел |
| one, speed-knot | {0} узел |
| few, speed-knot | {0} узла |
| many, speed-knot | {0} узлов |
| other, speed-knot | {0} узла |
| temperature-generic | ↴ |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| few, temperature-generic | {0}° |
| many, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ↴ |
| , temperature-celsius | градусы Цельсия |
| one, temperature-celsius | {0} градус Цельсия |
| few, temperature-celsius | {0} градуса Цельсия |
| many, temperature-celsius | {0} градусов Цельсия |
| other, temperature-celsius | {0} градуса Цельсия |
| temperature-fahrenheit | ↴ |
| , temperature-fahrenheit | градусы по Фаренгейту |
| one, temperature-fahrenheit | {0} градус по Фаренгейту |
| few, temperature-fahrenheit | {0} градуса по Фаренгейту |
| many, temperature-fahrenheit | {0} градусов по Фаренгейту |
| other, temperature-fahrenheit | {0} градуса по Фаренгейту |
| temperature-kelvin | ↴ |
| , temperature-kelvin | градусы по Кельвину |
| one, temperature-kelvin | {0} градус по Кельвину |
| few, temperature-kelvin | {0} градуса по Кельвину |
| many, temperature-kelvin | {0} градусов по Кельвину |
| other, temperature-kelvin | {0} градуса по Кельвину |
| volume-cubic-kilometer | ↴ |
| , volume-cubic-kilometer | кубические километры |
| one, volume-cubic-kilometer | {0} кубический километр |
| few, volume-cubic-kilometer | {0} кубических километра |
| many, volume-cubic-kilometer | {0} кубических километров |
| other, volume-cubic-kilometer | {0} кубического километра |
| volume-cubic-meter | ↴ |
| , volume-cubic-meter | кубические метры |
| one, volume-cubic-meter | {0} кубический метр |
| few, volume-cubic-meter | {0} кубических метра |
| many, volume-cubic-meter | {0} кубических метров |
| other, volume-cubic-meter | {0} кубического метра |
| per units of volume-cubic-meter | {0} на кубический метр |
| volume-cubic-centimeter | ↴ |
| , volume-cubic-centimeter | кубические сантиметры |
| one, volume-cubic-centimeter | {0} кубический сантиметр |
| few, volume-cubic-centimeter | {0} кубических сантиметра |
| many, volume-cubic-centimeter | {0} кубических сантиметров |
| other, volume-cubic-centimeter | {0} кубического сантиметра |
| per units of volume-cubic-centimeter | {0} на кубический сантиметр |
| volume-cubic-mile | ↴ |
| , volume-cubic-mile | кубические мили |
| one, volume-cubic-mile | {0} кубическая миля |
| few, volume-cubic-mile | {0} кубические мили |
| many, volume-cubic-mile | {0} кубических миль |
| other, volume-cubic-mile | {0} кубической мили |
| volume-cubic-yard | ↴ |
| , volume-cubic-yard | кубические ярды |
| one, volume-cubic-yard | {0} кубический ярд |
| few, volume-cubic-yard | {0} кубических ярда |
| many, volume-cubic-yard | {0} кубических ярдов |
| other, volume-cubic-yard | {0} кубического ярда |
| volume-cubic-foot | ↴ |
| , volume-cubic-foot | кубические футы |
| one, volume-cubic-foot | {0} кубический фут |
| few, volume-cubic-foot | {0} кубических фута |
| many, volume-cubic-foot | {0} кубических футов |
| other, volume-cubic-foot | {0} кубического фута |
| volume-cubic-inch | ↴ |
| , volume-cubic-inch | кубические дюймы |
| one, volume-cubic-inch | {0} кубический дюйм |
| few, volume-cubic-inch | {0} кубических дюйма |
| many, volume-cubic-inch | {0} кубических дюймов |
| other, volume-cubic-inch | {0} кубического дюйма |
| volume-megaliter | ↴ |
| , volume-megaliter | мегалитры |
| one, volume-megaliter | {0} мегалитр |
| few, volume-megaliter | {0} мегалитра |
| many, volume-megaliter | {0} мегалитров |
| other, volume-megaliter | {0} мегалитра |
| volume-hectoliter | ↴ |
| , volume-hectoliter | гектолитры |
| one, volume-hectoliter | {0} гектолитр |
| few, volume-hectoliter | {0} гектолитра |
| many, volume-hectoliter | {0} гектолитров |
| other, volume-hectoliter | {0} гектолитра |
| volume-liter | ↴ |
| , volume-liter | литры |
| one, volume-liter | {0} литр |
| few, volume-liter | {0} литра |
| many, volume-liter | {0} литров |
| other, volume-liter | {0} литра |
| per units of volume-liter | {0} на литр |
| volume-deciliter | ↴ |
| , volume-deciliter | децилитры |
| one, volume-deciliter | {0} децилитр |
| few, volume-deciliter | {0} децилитра |
| many, volume-deciliter | {0} децилитров |
| other, volume-deciliter | {0} децилитра |
| volume-centiliter | ↴ |
| , volume-centiliter | сантилитры |
| one, volume-centiliter | {0} сантилитр |
| few, volume-centiliter | {0} сантилитра |
| many, volume-centiliter | {0} сантилитров |
| other, volume-centiliter | {0} сантилитра |
| volume-milliliter | ↴ |
| , volume-milliliter | миллилитры |
| one, volume-milliliter | {0} миллилитр |
| few, volume-milliliter | {0} миллилитра |
| many, volume-milliliter | {0} миллилитров |
| other, volume-milliliter | {0} миллилитра |
| volume-pint-metric | ↴ |
| , volume-pint-metric | метрические пинты |
| one, volume-pint-metric | {0} метрическая пинта |
| few, volume-pint-metric | {0} метрические пинты |
| many, volume-pint-metric | {0} метрических пинт |
| other, volume-pint-metric | {0} метрической пинты |
| volume-cup-metric | ↴ |
| , volume-cup-metric | метрические чашки |
| one, volume-cup-metric | {0} метрическая чашка |
| few, volume-cup-metric | {0} метрические чашки |
| many, volume-cup-metric | {0} метрических чашек |
| other, volume-cup-metric | {0} метрической чашки |
| volume-acre-foot | ↴ |
| , volume-acre-foot | акрофуты |
| one, volume-acre-foot | {0} акрофут |
| few, volume-acre-foot | {0} акрофута |
| many, volume-acre-foot | {0} акрофутов |
| other, volume-acre-foot | {0} акрофута |
| volume-gallon | ↴ |
| , volume-gallon | галлоны |
| one, volume-gallon | {0} галлон |
| few, volume-gallon | {0} галлона |
| many, volume-gallon | {0} галлонов |
| other, volume-gallon | {0} галлона |
| per units of volume-gallon | {0} на галлон |
| volume-gallon-imperial | ↴ |
| , volume-gallon-imperial | имп. галлоны |
| one, volume-gallon-imperial | {0} имп. галлон |
| few, volume-gallon-imperial | {0} имп. галлона |
| many, volume-gallon-imperial | {0} имп. галлонов |
| other, volume-gallon-imperial | {0} имп. галлона |
| per units of volume-gallon-imperial | {0} на имп. галлон |
| volume-quart | ↴ |
| , volume-quart | кварты |
| one, volume-quart | {0} кварта |
| few, volume-quart | {0} кварты |
| many, volume-quart | {0} кварт |
| other, volume-quart | {0} кварты |
| volume-pint | ↴ |
| , volume-pint | пинты |
| one, volume-pint | {0} пинта |
| few, volume-pint | {0} пинты |
| many, volume-pint | {0} пинт |
| other, volume-pint | {0} пинты |
| volume-cup | ↴ |
| , volume-cup | чашки |
| one, volume-cup | {0} чашка |
| few, volume-cup | {0} чашки |
| many, volume-cup | {0} чашек |
| other, volume-cup | {0} чашки |
| volume-fluid-ounce | ↴ |
| , volume-fluid-ounce | жидкие унции |
| one, volume-fluid-ounce | {0} жидкая унция |
| few, volume-fluid-ounce | {0} жидкие унции |
| many, volume-fluid-ounce | {0} жидких унций |
| other, volume-fluid-ounce | {0} жидкой унции |
| volume-tablespoon | ↴ |
| , volume-tablespoon | столовые ложки |
| one, volume-tablespoon | {0} столовая ложка |
| few, volume-tablespoon | {0} столовые ложки |
| many, volume-tablespoon | {0} столовых ложек |
| other, volume-tablespoon | {0} столовой ложки |
| volume-teaspoon | ↴ |
| , volume-teaspoon | чайные ложки |
| one, volume-teaspoon | {0} чайная ложка |
| few, volume-teaspoon | {0} чайные ложки |
| many, volume-teaspoon | {0} чайных ложек |
| other, volume-teaspoon | {0} чайной ложки |
| coordinates, east | {0} восточной долготы |
| coordinates, north | {0} северной широты |
| coordinates, south | {0} южной широты |
| coordinates, west | {0} западной долготы |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ↴ |
| , acceleration-g-force | g |
| one, acceleration-g-force | {0} g |
| few, acceleration-g-force | {0} g |
| many, acceleration-g-force | {0} g |
| other, acceleration-g-force | {0} g |
| acceleration-meter-per-second-squared | ↴ |
| , acceleration-meter-per-second-squared | м/с² |
| one, acceleration-meter-per-second-squared | {0} м/с² |
| few, acceleration-meter-per-second-squared | {0} м/с² |
| many, acceleration-meter-per-second-squared | {0} м/с² |
| other, acceleration-meter-per-second-squared | {0} м/с² |
| angle-revolution | ↴ |
| , angle-revolution | об. |
| one, angle-revolution | {0} об. |
| few, angle-revolution | {0} об. |
| many, angle-revolution | {0} об. |
| other, angle-revolution | {0} об. |
| angle-radian | ↴ |
| , angle-radian | рад |
| one, angle-radian | {0} рад |
| few, angle-radian | {0} рад |
| many, angle-radian | {0} рад |
| other, angle-radian | {0} рад |
| angle-degree | ↴ |
| , angle-degree | ° |
| one, angle-degree | {0}° |
| few, angle-degree | {0}° |
| many, angle-degree | {0}° |
| other, angle-degree | {0}° |
| angle-arc-minute | ↴ |
| , angle-arc-minute | ′ |
| one, angle-arc-minute | {0}′ |
| few, angle-arc-minute | {0}′ |
| many, angle-arc-minute | {0}′ |
| other, angle-arc-minute | {0}′ |
| angle-arc-second | ↴ |
| , angle-arc-second | ″ |
| one, angle-arc-second | {0}″ |
| few, angle-arc-second | {0}″ |
| many, angle-arc-second | {0}″ |
| other, angle-arc-second | {0}″ |
| area-square-kilometer | ↴ |
| , area-square-kilometer | км² |
| one, area-square-kilometer | {0} км² |
| few, area-square-kilometer | {0} км² |
| many, area-square-kilometer | {0} км² |
| other, area-square-kilometer | {0} км² |
| per units of area-square-kilometer | {0}/км² |
| area-hectare | ↴ |
| , area-hectare | га |
| one, area-hectare | {0} га |
| few, area-hectare | {0} га |
| many, area-hectare | {0} га |
| other, area-hectare | {0} га |
| area-square-meter | ↴ |
| , area-square-meter | м² |
| one, area-square-meter | {0} м² |
| few, area-square-meter | {0} м² |
| many, area-square-meter | {0} м² |
| other, area-square-meter | {0} м² |
| per units of area-square-meter | {0}/м² |
| area-square-centimeter | ↴ |
| , area-square-centimeter | см² |
| one, area-square-centimeter | {0} см² |
| few, area-square-centimeter | {0} см² |
| many, area-square-centimeter | {0} см² |
| other, area-square-centimeter | {0} см² |
| per units of area-square-centimeter | {0}/см² |
| area-square-mile | ↴ |
| , area-square-mile | миля² |
| one, area-square-mile | {0} миля² |
| few, area-square-mile | {0} миля² |
| many, area-square-mile | {0} миля² |
| other, area-square-mile | {0} миля² |
| per units of area-square-mile | {0}/миля² |
| area-acre | ↴ |
| , area-acre | акр. |
| one, area-acre | {0} акр |
| few, area-acre | {0} акр. |
| many, area-acre | {0} акр. |
| other, area-acre | {0} акр. |
| area-square-yard | ↴ |
| , area-square-yard | ярд² |
| one, area-square-yard | {0} ярд² |
| few, area-square-yard | {0} ярд² |
| many, area-square-yard | {0} ярд² |
| other, area-square-yard | {0} ярд² |
| area-square-foot | ↴ |
| , area-square-foot | фут² |
| one, area-square-foot | {0} фут² |
| few, area-square-foot | {0} фут² |
| many, area-square-foot | {0} фут² |
| other, area-square-foot | {0} фут² |
| area-square-inch | ↴ |
| , area-square-inch | дюйм² |
| one, area-square-inch | {0} дюйм² |
| few, area-square-inch | {0} дюйм² |
| many, area-square-inch | {0} дюйм² |
| other, area-square-inch | {0} дюйм² |
| per units of area-square-inch | {0}/дюйм² |
| concentr-karat | ↴ |
| , concentr-karat | кар |
| one, concentr-karat | {0} кар |
| few, concentr-karat | {0} кар |
| many, concentr-karat | {0} кар |
| other, concentr-karat | {0} кар |
| concentr-milligram-per-deciliter | ↴ |
| , concentr-milligram-per-deciliter | мг/дл |
| one, concentr-milligram-per-deciliter | {0} мг/дл |
| few, concentr-milligram-per-deciliter | {0} мг/дл |
| many, concentr-milligram-per-deciliter | {0} мг/дл |
| other, concentr-milligram-per-deciliter | {0} мг/дл |
| concentr-millimole-per-liter | ↴ |
| , concentr-millimole-per-liter | ммоль/л |
| one, concentr-millimole-per-liter | {0} ммоль/л |
| few, concentr-millimole-per-liter | {0} ммоль/л |
| many, concentr-millimole-per-liter | {0} ммоль/л |
| other, concentr-millimole-per-liter | {0} ммоль/л |
| concentr-part-per-million | ↴ |
| , concentr-part-per-million | ppm |
| one, concentr-part-per-million | {0} ppm |
| few, concentr-part-per-million | {0} ppm |
| many, concentr-part-per-million | {0} ppm |
| other, concentr-part-per-million | {0} ppm |
| consumption-liter-per-kilometer | ↴ |
| , consumption-liter-per-kilometer | л/км |
| one, consumption-liter-per-kilometer | {0} л/км |
| few, consumption-liter-per-kilometer | {0} л/км |
| many, consumption-liter-per-kilometer | {0} л/км |
| other, consumption-liter-per-kilometer | {0} л/км |
| consumption-liter-per-100kilometers | ↴ |
| , consumption-liter-per-100kilometers | л/100 км |
| one, consumption-liter-per-100kilometers | {0} л/100 км |
| few, consumption-liter-per-100kilometers | {0} л/100 км |
| many, consumption-liter-per-100kilometers | {0} л/100 км |
| other, consumption-liter-per-100kilometers | {0} л/100 км |
| consumption-mile-per-gallon | ↴ |
| , consumption-mile-per-gallon | миль/гал |
| one, consumption-mile-per-gallon | {0} миля/галл. |
| few, consumption-mile-per-gallon | {0} мили/галл. |
| many, consumption-mile-per-gallon | {0} миль/галл. |
| other, consumption-mile-per-gallon | {0} мили/галл. |
| consumption-mile-per-gallon-imperial | ↴ |
| , consumption-mile-per-gallon-imperial | мили/имп. гал |
| one, consumption-mile-per-gallon-imperial | {0} миля/имп. гал |
| few, consumption-mile-per-gallon-imperial | {0} мили/имп. гал |
| many, consumption-mile-per-gallon-imperial | {0} миль/имп. гал |
| other, consumption-mile-per-gallon-imperial | {0} мили/имп. галл. |
| digital-terabyte | ↴ |
| , digital-terabyte | ТБ |
| one, digital-terabyte | {0} ТБ |
| few, digital-terabyte | {0} ТБ |
| many, digital-terabyte | {0} ТБ |
| other, digital-terabyte | {0} ТБ |
| digital-terabit | ↴ |
| , digital-terabit | Тбит |
| one, digital-terabit | {0} Тбит |
| few, digital-terabit | {0} Тбит |
| many, digital-terabit | {0} Тбит |
| other, digital-terabit | {0} Тбит |
| digital-gigabyte | ↴ |
| , digital-gigabyte | ГБ |
| one, digital-gigabyte | {0} ГБ |
| few, digital-gigabyte | {0} ГБ |
| many, digital-gigabyte | {0} ГБ |
| other, digital-gigabyte | {0} ГБ |
| digital-gigabit | ↴ |
| , digital-gigabit | Гбит |
| one, digital-gigabit | {0} Гбит |
| few, digital-gigabit | {0} Гбит |
| many, digital-gigabit | {0} Гбит |
| other, digital-gigabit | {0} Гбит |
| digital-megabyte | ↴ |
| , digital-megabyte | МБ |
| one, digital-megabyte | {0} МБ |
| few, digital-megabyte | {0} МБ |
| many, digital-megabyte | {0} МБ |
| other, digital-megabyte | {0} МБ |
| digital-megabit | ↴ |
| , digital-megabit | Мбит |
| one, digital-megabit | {0} Мбит |
| few, digital-megabit | {0} Мбит |
| many, digital-megabit | {0} Мбит |
| other, digital-megabit | {0} Мбит |
| digital-kilobyte | ↴ |
| , digital-kilobyte | кБ |
| one, digital-kilobyte | {0} кБ |
| few, digital-kilobyte | {0} кБ |
| many, digital-kilobyte | {0} кБ |
| other, digital-kilobyte | {0} кБ |
| digital-kilobit | ↴ |
| , digital-kilobit | кбит |
| one, digital-kilobit | {0} кбит |
| few, digital-kilobit | {0} кбит |
| many, digital-kilobit | {0} кбит |
| other, digital-kilobit | {0} кбит |
| digital-byte | ↴ |
| , digital-byte | Б |
| one, digital-byte | {0} Б |
| few, digital-byte | {0} Б |
| many, digital-byte | {0} Б |
| other, digital-byte | {0} Б |
| digital-bit | ↴ |
| , digital-bit | бит |
| one, digital-bit | {0} бит |
| few, digital-bit | {0} бита |
| many, digital-bit | {0} бит |
| other, digital-bit | {0} бита |
| duration-century | ↴ |
| , duration-century | в. |
| one, duration-century | {0} в. |
| few, duration-century | {0} в. |
| many, duration-century | {0} в. |
| other, duration-century | {0} в. |
| duration-year | ↴ |
| , duration-year | г. |
| one, duration-year | {0} г. |
| few, duration-year | {0} г. |
| many, duration-year | {0} л. |
| other, duration-year | {0} г. |
| per units of duration-year | {0}/г |
| duration-month | ↴ |
| , duration-month | мес. |
| one, duration-month | {0} мес. |
| few, duration-month | {0} мес. |
| many, duration-month | {0} мес. |
| other, duration-month | {0} мес. |
| per units of duration-month | {0}/мес |
| duration-week | ↴ |
| , duration-week | нед. |
| one, duration-week | {0} нед. |
| few, duration-week | {0} нед. |
| many, duration-week | {0} нед. |
| other, duration-week | {0} нед. |
| per units of duration-week | {0}/нед |
| duration-day | ↴ |
| , duration-day | дн. |
| one, duration-day | {0} дн. |
| few, duration-day | {0} дн. |
| many, duration-day | {0} дн. |
| other, duration-day | {0} дн. |
| per units of duration-day | {0}/д |
| duration-hour | ↴ |
| , duration-hour | ч |
| one, duration-hour | {0} ч. |
| few, duration-hour | {0} ч. |
| many, duration-hour | {0} ч. |
| other, duration-hour | {0} ч. |
| per units of duration-hour | {0}/ч |
| duration-minute | ↴ |
| , duration-minute | мин |
| one, duration-minute | {0} мин. |
| few, duration-minute | {0} мин. |
| many, duration-minute | {0} мин. |
| other, duration-minute | {0} мин. |
| per units of duration-minute | {0}/мин |
| duration-second | ↴ |
| , duration-second | с |
| one, duration-second | {0} с. |
| few, duration-second | {0} с. |
| many, duration-second | {0} с. |
| other, duration-second | {0} с. |
| per units of duration-second | {0}/c |
| duration-millisecond | ↴ |
| , duration-millisecond | мс |
| one, duration-millisecond | {0} мс |
| few, duration-millisecond | {0} мс |
| many, duration-millisecond | {0} мс |
| other, duration-millisecond | {0} мс |
| duration-microsecond | ↴ |
| , duration-microsecond | мкс |
| one, duration-microsecond | {0} мкс |
| few, duration-microsecond | {0} мкс |
| many, duration-microsecond | {0} мкс |
| other, duration-microsecond | {0} мкс |
| duration-nanosecond | ↴ |
| , duration-nanosecond | нс |
| one, duration-nanosecond | {0} нс |
| few, duration-nanosecond | {0} нс |
| many, duration-nanosecond | {0} нс |
| other, duration-nanosecond | {0} нс |
| electric-ampere | ↴ |
| , electric-ampere | А |
| one, electric-ampere | {0} А |
| few, electric-ampere | {0} А |
| many, electric-ampere | {0} А |
| other, electric-ampere | {0} А |
| electric-milliampere | ↴ |
| , electric-milliampere | мА |
| one, electric-milliampere | {0} мА |
| few, electric-milliampere | {0} мА |
| many, electric-milliampere | {0} мА |
| other, electric-milliampere | {0} мА |
| electric-ohm | ↴ |
| , electric-ohm | Ом |
| one, electric-ohm | {0} Ом |
| few, electric-ohm | {0} Ом |
| many, electric-ohm | {0} Ом |
| other, electric-ohm | {0} Ом |
| electric-volt | ↴ |
| , electric-volt | В |
| one, electric-volt | {0} В |
| few, electric-volt | {0} В |
| many, electric-volt | {0} В |
| other, electric-volt | {0} В |
| energy-kilocalorie | ↴ |
| , energy-kilocalorie | ккал |
| one, energy-kilocalorie | {0} ккал |
| few, energy-kilocalorie | {0} ккал |
| many, energy-kilocalorie | {0} ккал |
| other, energy-kilocalorie | {0} ккал |
| energy-calorie | ↴ |
| , energy-calorie | кал |
| one, energy-calorie | {0} кал |
| few, energy-calorie | {0} кал |
| many, energy-calorie | {0} кал |
| other, energy-calorie | {0} кал |
| energy-foodcalorie | ↴ |
| , energy-foodcalorie | кал |
| one, energy-foodcalorie | {0} кал |
| few, energy-foodcalorie | {0} кал |
| many, energy-foodcalorie | {0} кал |
| other, energy-foodcalorie | {0} кал |
| energy-kilojoule | ↴ |
| , energy-kilojoule | кДж |
| one, energy-kilojoule | {0} кДж |
| few, energy-kilojoule | {0} кДж |
| many, energy-kilojoule | {0} кДж |
| other, energy-kilojoule | {0} кДж |
| energy-joule | ↴ |
| , energy-joule | Дж |
| one, energy-joule | {0} Дж |
| few, energy-joule | {0} Дж |
| many, energy-joule | {0} Дж |
| other, energy-joule | {0} Дж |
| energy-kilowatt-hour | ↴ |
| , energy-kilowatt-hour | кВт⋅ч |
| one, energy-kilowatt-hour | {0} кВт⋅ч |
| few, energy-kilowatt-hour | {0} кВт⋅ч |
| many, energy-kilowatt-hour | {0} кВт⋅ч |
| other, energy-kilowatt-hour | {0} кВт⋅ч |
| frequency-gigahertz | ↴ |
| , frequency-gigahertz | ГГц |
| one, frequency-gigahertz | {0} ГГц |
| few, frequency-gigahertz | {0} ГГц |
| many, frequency-gigahertz | {0} ГГц |
| other, frequency-gigahertz | {0} ГГц |
| frequency-megahertz | ↴ |
| , frequency-megahertz | МГц |
| one, frequency-megahertz | {0} МГц |
| few, frequency-megahertz | {0} МГц |
| many, frequency-megahertz | {0} МГц |
| other, frequency-megahertz | {0} МГц |
| frequency-kilohertz | ↴ |
| , frequency-kilohertz | кГц |
| one, frequency-kilohertz | {0} кГц |
| few, frequency-kilohertz | {0} кГц |
| many, frequency-kilohertz | {0} кГц |
| other, frequency-kilohertz | {0} кГц |
| frequency-hertz | ↴ |
| , frequency-hertz | Гц |
| one, frequency-hertz | {0} Гц |
| few, frequency-hertz | {0} Гц |
| many, frequency-hertz | {0} Гц |
| other, frequency-hertz | {0} Гц |
| length-kilometer | ↴ |
| , length-kilometer | км |
| one, length-kilometer | {0} км |
| few, length-kilometer | {0} км |
| many, length-kilometer | {0} км |
| other, length-kilometer | {0} км |
| per units of length-kilometer | {0}/км |
| length-meter | ↴ |
| , length-meter | м |
| one, length-meter | {0} м |
| few, length-meter | {0} м |
| many, length-meter | {0} м |
| other, length-meter | {0} м |
| per units of length-meter | {0}/м |
| length-decimeter | ↴ |
| , length-decimeter | дм |
| one, length-decimeter | {0} дм |
| few, length-decimeter | {0} дм |
| many, length-decimeter | {0} дм |
| other, length-decimeter | {0} дм |
| length-centimeter | ↴ |
| , length-centimeter | см |
| one, length-centimeter | {0} см |
| few, length-centimeter | {0} см |
| many, length-centimeter | {0} см |
| other, length-centimeter | {0} см |
| per units of length-centimeter | {0}/см |
| length-millimeter | ↴ |
| , length-millimeter | мм |
| one, length-millimeter | {0} мм |
| few, length-millimeter | {0} мм |
| many, length-millimeter | {0} мм |
| other, length-millimeter | {0} мм |
| length-micrometer | ↴ |
| , length-micrometer | мкм |
| one, length-micrometer | {0} мкм |
| few, length-micrometer | {0} мкм |
| many, length-micrometer | {0} мкм |
| other, length-micrometer | {0} мкм |
| length-nanometer | ↴ |
| , length-nanometer | нм |
| one, length-nanometer | {0} нм |
| few, length-nanometer | {0} нм |
| many, length-nanometer | {0} нм |
| other, length-nanometer | {0} нм |
| length-picometer | ↴ |
| , length-picometer | пм |
| one, length-picometer | {0} пм |
| few, length-picometer | {0} пм |
| many, length-picometer | {0} пм |
| other, length-picometer | {0} пм |
| length-mile | ↴ |
| , length-mile | мили |
| one, length-mile | {0} миля |
| few, length-mile | {0} мили |
| many, length-mile | {0} миль |
| other, length-mile | {0} мили |
| length-yard | ↴ |
| , length-yard | ярд. |
| one, length-yard | {0} ярд |
| few, length-yard | {0} ярд. |
| many, length-yard | {0} ярд. |
| other, length-yard | {0} ярд. |
| length-foot | ↴ |
| , length-foot | фт |
| one, length-foot | {0} фт |
| few, length-foot | {0} фт |
| many, length-foot | {0} фт |
| other, length-foot | {0} фт |
| per units of length-foot | {0}/фт |
| length-inch | ↴ |
| , length-inch | дюйм. |
| one, length-inch | {0} дюйм |
| few, length-inch | {0} дюйм. |
| many, length-inch | {0} дюйм. |
| other, length-inch | {0} дюйм. |
| per units of length-inch | {0}/дюйм |
| length-parsec | ↴ |
| , length-parsec | пк |
| one, length-parsec | {0} пк |
| few, length-parsec | {0} пк |
| many, length-parsec | {0} пк |
| other, length-parsec | {0} пк |
| length-light-year | ↴ |
| , length-light-year | св. г. |
| one, length-light-year | {0} св. г. |
| few, length-light-year | {0} св. г. |
| many, length-light-year | {0} св. л. |
| other, length-light-year | {0} св. г. |
| length-astronomical-unit | ↴ |
| , length-astronomical-unit | а. е. |
| one, length-astronomical-unit | {0} а. е. |
| few, length-astronomical-unit | {0} а. е. |
| many, length-astronomical-unit | {0} а. е. |
| other, length-astronomical-unit | {0} а. е. |
| length-furlong | ↴ |
| , length-furlong | фурлонги |
| one, length-furlong | {0} фурл. |
| few, length-furlong | {0} фурл. |
| many, length-furlong | {0} фурл. |
| other, length-furlong | {0} фурл. |
| length-fathom | ↴ |
| , length-fathom | мор. сажени |
| one, length-fathom | {0} мор. сажень |
| few, length-fathom | {0} мор. сажени |
| many, length-fathom | {0} мор. саженей |
| other, length-fathom | {0} мор. сажени |
| length-nautical-mile | ↴ |
| , length-nautical-mile | мор. мили |
| one, length-nautical-mile | {0} мор. миля |
| few, length-nautical-mile | {0} мор. мили |
| many, length-nautical-mile | {0} мор. миль |
| other, length-nautical-mile | {0} мор. мили |
| length-mile-scandinavian | ↴ |
| , length-mile-scandinavian | ск. мил. |
| one, length-mile-scandinavian | {0} ск. мил. |
| few, length-mile-scandinavian | {0} ск. мил. |
| many, length-mile-scandinavian | {0} ск. мил. |
| other, length-mile-scandinavian | {0} ск. мил. |
| length-point | ↴ |
| , length-point | пкт |
| one, length-point | {0} пкт |
| few, length-point | {0} пкт |
| many, length-point | {0} пкт |
| other, length-point | {0} пкт |
| light-lux | ↴ |
| , light-lux | лк |
| one, light-lux | {0} лк |
| few, light-lux | {0} лк |
| many, light-lux | {0} лк |
| other, light-lux | {0} лк |
| mass-metric-ton | ↴ |
| , mass-metric-ton | т |
| one, mass-metric-ton | {0} т |
| few, mass-metric-ton | {0} т |
| many, mass-metric-ton | {0} т |
| other, mass-metric-ton | {0} т |
| mass-kilogram | ↴ |
| , mass-kilogram | кг |
| one, mass-kilogram | {0} кг |
| few, mass-kilogram | {0} кг |
| many, mass-kilogram | {0} кг |
| other, mass-kilogram | {0} кг |
| per units of mass-kilogram | {0}/кг |
| mass-gram | ↴ |
| , mass-gram | г |
| one, mass-gram | {0} г |
| few, mass-gram | {0} г |
| many, mass-gram | {0} г |
| other, mass-gram | {0} г |
| per units of mass-gram | {0}/г |
| mass-milligram | ↴ |
| , mass-milligram | мг |
| one, mass-milligram | {0} мг |
| few, mass-milligram | {0} мг |
| many, mass-milligram | {0} мг |
| other, mass-milligram | {0} мг |
| mass-microgram | ↴ |
| , mass-microgram | мкг |
| one, mass-microgram | {0} мкг |
| few, mass-microgram | {0} мкг |
| many, mass-microgram | {0} мкг |
| other, mass-microgram | {0} мкг |
| mass-ton | ↴ |
| , mass-ton | амер. т |
| one, mass-ton | {0} амер. т |
| few, mass-ton | {0} амер. т |
| many, mass-ton | {0} амер. т |
| other, mass-ton | {0} амер. т |
| mass-stone | ↴ |
| , mass-stone | стоуны |
| one, mass-stone | {0} стоун |
| few, mass-stone | {0} стоуна |
| many, mass-stone | {0} стоунов |
| other, mass-stone | {0} стоуна |
| mass-pound | ↴ |
| , mass-pound | фунт. |
| one, mass-pound | {0} фунт. |
| few, mass-pound | {0} фунт. |
| many, mass-pound | {0} фунт. |
| other, mass-pound | {0} фунт. |
| per units of mass-pound | {0}/фунт |
| mass-ounce | ↴ |
| , mass-ounce | унц. |
| one, mass-ounce | {0} унц. |
| few, mass-ounce | {0} унц. |
| many, mass-ounce | {0} унц. |
| other, mass-ounce | {0} унц. |
| per units of mass-ounce | {0}/унц |
| mass-ounce-troy | ↴ |
| , mass-ounce-troy | тр. унц. |
| one, mass-ounce-troy | {0} тр. унц. |
| few, mass-ounce-troy | {0} тр. унц. |
| many, mass-ounce-troy | {0} тр. унц. |
| other, mass-ounce-troy | {0} тр. унц. |
| mass-carat | ↴ |
| , mass-carat | кар |
| one, mass-carat | {0} кар |
| few, mass-carat | {0} кар |
| many, mass-carat | {0} кар |
| other, mass-carat | {0} кар |
| power-gigawatt | ↴ |
| , power-gigawatt | ГВт |
| one, power-gigawatt | {0} ГВт |
| few, power-gigawatt | {0} ГВт |
| many, power-gigawatt | {0} ГВт |
| other, power-gigawatt | {0} ГВт |
| power-megawatt | ↴ |
| , power-megawatt | МВт |
| one, power-megawatt | {0} МВт |
| few, power-megawatt | {0} МВт |
| many, power-megawatt | {0} МВт |
| other, power-megawatt | {0} МВт |
| power-kilowatt | ↴ |
| , power-kilowatt | кВт |
| one, power-kilowatt | {0} кВт |
| few, power-kilowatt | {0} кВт |
| many, power-kilowatt | {0} кВт |
| other, power-kilowatt | {0} кВт |
| power-watt | ↴ |
| , power-watt | Вт |
| one, power-watt | {0} Вт |
| few, power-watt | {0} Вт |
| many, power-watt | {0} Вт |
| other, power-watt | {0} Вт |
| power-milliwatt | ↴ |
| , power-milliwatt | мВт |
| one, power-milliwatt | {0} мВт |
| few, power-milliwatt | {0} мВт |
| many, power-milliwatt | {0} мВт |
| other, power-milliwatt | {0} мВт |
| power-horsepower | ↴ |
| , power-horsepower | л.с. |
| one, power-horsepower | {0} л.с. |
| few, power-horsepower | {0} л.с. |
| many, power-horsepower | {0} л.с. |
| other, power-horsepower | {0} л.с. |
| pressure-hectopascal | ↴ |
| , pressure-hectopascal | гПа |
| one, pressure-hectopascal | {0} гПа |
| few, pressure-hectopascal | {0} гПа |
| many, pressure-hectopascal | {0} гПа |
| other, pressure-hectopascal | {0} гПа |
| pressure-millimeter-of-mercury | ↴ |
| , pressure-millimeter-of-mercury | мм рт. ст. |
| one, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| few, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| many, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| other, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| pressure-pound-per-square-inch | ↴ |
| , pressure-pound-per-square-inch | ф. на дюйм² |
| one, pressure-pound-per-square-inch | {0} ф./дюйм² |
| few, pressure-pound-per-square-inch | {0} ф./дюйм² |
| many, pressure-pound-per-square-inch | {0} ф./дюйм² |
| other, pressure-pound-per-square-inch | {0} ф./дюйм² |
| pressure-inch-hg | ↴ |
| , pressure-inch-hg | д. рт. ст. |
| one, pressure-inch-hg | {0} д. рт. ст. |
| few, pressure-inch-hg | {0} д. рт. ст. |
| many, pressure-inch-hg | {0} д. рт. ст. |
| other, pressure-inch-hg | {0} д. рт. ст. |
| pressure-millibar | ↴ |
| , pressure-millibar | мбар |
| one, pressure-millibar | {0} мбар |
| few, pressure-millibar | {0} мбар |
| many, pressure-millibar | {0} мбар |
| other, pressure-millibar | {0} мбар |
| speed-kilometer-per-hour | ↴ |
| , speed-kilometer-per-hour | км/ч |
| one, speed-kilometer-per-hour | {0} км/ч |
| few, speed-kilometer-per-hour | {0} км/ч |
| many, speed-kilometer-per-hour | {0} км/ч |
| other, speed-kilometer-per-hour | {0} км/ч |
| speed-meter-per-second | ↴ |
| , speed-meter-per-second | м/с |
| one, speed-meter-per-second | {0} м/с |
| few, speed-meter-per-second | {0} м/с |
| many, speed-meter-per-second | {0} м/с |
| other, speed-meter-per-second | {0} м/с |
| speed-mile-per-hour | ↴ |
| , speed-mile-per-hour | мили/час |
| one, speed-mile-per-hour | {0} миля/час |
| few, speed-mile-per-hour | {0} мили/час |
| many, speed-mile-per-hour | {0} миль/час |
| other, speed-mile-per-hour | {0} мили/час |
| speed-knot | ↴ |
| , speed-knot | уз |
| one, speed-knot | {0} уз |
| few, speed-knot | {0} уз |
| many, speed-knot | {0} уз |
| other, speed-knot | {0} уз |
| temperature-generic | ↴ |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| few, temperature-generic | {0}° |
| many, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ↴ |
| , temperature-celsius | °C |
| one, temperature-celsius | {0} °C |
| few, temperature-celsius | {0} °C |
| many, temperature-celsius | {0} °C |
| other, temperature-celsius | {0} °C |
| temperature-fahrenheit | ↴ |
| , temperature-fahrenheit | °F |
| one, temperature-fahrenheit | {0}°F |
| few, temperature-fahrenheit | {0}°F |
| many, temperature-fahrenheit | {0}°F |
| other, temperature-fahrenheit | {0}°F |
| temperature-kelvin | ↴ |
| , temperature-kelvin | K |
| one, temperature-kelvin | {0} K |
| few, temperature-kelvin | {0} K |
| many, temperature-kelvin | {0} K |
| other, temperature-kelvin | {0} K |
| volume-cubic-kilometer | ↴ |
| , volume-cubic-kilometer | км³ |
| one, volume-cubic-kilometer | {0} км³ |
| few, volume-cubic-kilometer | {0} км³ |
| many, volume-cubic-kilometer | {0} км³ |
| other, volume-cubic-kilometer | {0} км³ |
| volume-cubic-meter | ↴ |
| , volume-cubic-meter | м³ |
| one, volume-cubic-meter | {0} м³ |
| few, volume-cubic-meter | {0} м³ |
| many, volume-cubic-meter | {0} м³ |
| other, volume-cubic-meter | {0} м³ |
| per units of volume-cubic-meter | {0}/м³ |
| volume-cubic-centimeter | ↴ |
| , volume-cubic-centimeter | см³ |
| one, volume-cubic-centimeter | {0} см³ |
| few, volume-cubic-centimeter | {0} см³ |
| many, volume-cubic-centimeter | {0} см³ |
| other, volume-cubic-centimeter | {0} см³ |
| per units of volume-cubic-centimeter | {0}/см³ |
| volume-cubic-mile | ↴ |
| , volume-cubic-mile | миля³ |
| one, volume-cubic-mile | {0} миля³ |
| few, volume-cubic-mile | {0} мили³ |
| many, volume-cubic-mile | {0} миль³ |
| other, volume-cubic-mile | {0} мили³ |
| volume-cubic-yard | ↴ |
| , volume-cubic-yard | ярд³ |
| one, volume-cubic-yard | {0} ярд³ |
| few, volume-cubic-yard | {0} ярд³ |
| many, volume-cubic-yard | {0} ярд³ |
| other, volume-cubic-yard | {0} ярд³ |
| volume-cubic-foot | ↴ |
| , volume-cubic-foot | фут³ |
| one, volume-cubic-foot | {0} фут³ |
| few, volume-cubic-foot | {0} фут³ |
| many, volume-cubic-foot | {0} фут³ |
| other, volume-cubic-foot | {0} фут³ |
| volume-cubic-inch | ↴ |
| , volume-cubic-inch | дюйм³ |
| one, volume-cubic-inch | {0} дюйм³ |
| few, volume-cubic-inch | {0} дюйм³ |
| many, volume-cubic-inch | {0} дюйм³ |
| other, volume-cubic-inch | {0} дюйм³ |
| volume-megaliter | ↴ |
| , volume-megaliter | Мл |
| one, volume-megaliter | {0} Мл |
| few, volume-megaliter | {0} Мл |
| many, volume-megaliter | {0} Мл |
| other, volume-megaliter | {0} Мл |
| volume-hectoliter | ↴ |
| , volume-hectoliter | гл |
| one, volume-hectoliter | {0} гл |
| few, volume-hectoliter | {0} гл |
| many, volume-hectoliter | {0} гл |
| other, volume-hectoliter | {0} гл |
| volume-liter | ↴ |
| , volume-liter | л |
| one, volume-liter | {0} л |
| few, volume-liter | {0} л |
| many, volume-liter | {0} л |
| other, volume-liter | {0} л |
| per units of volume-liter | {0}/л |
| volume-deciliter | ↴ |
| , volume-deciliter | дл |
| one, volume-deciliter | {0} дл |
| few, volume-deciliter | {0} дл |
| many, volume-deciliter | {0} дл |
| other, volume-deciliter | {0} дл |
| volume-centiliter | ↴ |
| , volume-centiliter | сл |
| one, volume-centiliter | {0} сл |
| few, volume-centiliter | {0} сл |
| many, volume-centiliter | {0} сл |
| other, volume-centiliter | {0} сл |
| volume-milliliter | ↴ |
| , volume-milliliter | мл |
| one, volume-milliliter | {0} мл |
| few, volume-milliliter | {0} мл |
| many, volume-milliliter | {0} мл |
| other, volume-milliliter | {0} мл |
| volume-pint-metric | ↴ |
| , volume-pint-metric | мпт |
| one, volume-pint-metric | {0} мпт |
| few, volume-pint-metric | {0} мпт |
| many, volume-pint-metric | {0} мпт |
| other, volume-pint-metric | {0} мпт |
| volume-cup-metric | ↴ |
| , volume-cup-metric | м. чаш. |
| one, volume-cup-metric | {0} м. чаш. |
| few, volume-cup-metric | {0} м. чаш. |
| many, volume-cup-metric | {0} м. чаш. |
| other, volume-cup-metric | {0} м. чаш. |
| volume-acre-foot | ↴ |
| , volume-acre-foot | акрофут. |
| one, volume-acre-foot | {0} акрофут |
| few, volume-acre-foot | {0} акрофут. |
| many, volume-acre-foot | {0} акрофут. |
| other, volume-acre-foot | {0} акрофут. |
| volume-gallon | ↴ |
| , volume-gallon | гал. |
| one, volume-gallon | {0} гал. |
| few, volume-gallon | {0} гал. |
| many, volume-gallon | {0} гал. |
| other, volume-gallon | {0} гал. |
| per units of volume-gallon | {0}/гал |
| volume-gallon-imperial | ↴ |
| , volume-gallon-imperial | имп. гал. |
| one, volume-gallon-imperial | {0} имп. гал. |
| few, volume-gallon-imperial | {0} имп. гал. |
| many, volume-gallon-imperial | {0} имп. гал. |
| other, volume-gallon-imperial | {0} имп. гал. |
| per units of volume-gallon-imperial | {0}/имп. гал |
| volume-quart | ↴ |
| , volume-quart | кварт. |
| one, volume-quart | {0} кварт. |
| few, volume-quart | {0} кварт. |
| many, volume-quart | {0} кварт. |
| other, volume-quart | {0} кварт. |
| volume-pint | ↴ |
| , volume-pint | пинт. |
| one, volume-pint | {0} пинт. |
| few, volume-pint | {0} пинт. |
| many, volume-pint | {0} пинт. |
| other, volume-pint | {0} пинт. |
| volume-cup | ↴ |
| , volume-cup | чаш. |
| one, volume-cup | {0} чаш. |
| few, volume-cup | {0} чаш. |
| many, volume-cup | {0} чаш. |
| other, volume-cup | {0} чаш. |
| volume-fluid-ounce | ↴ |
| , volume-fluid-ounce | жидк. унц. |
| one, volume-fluid-ounce | {0} жидк. унц. |
| few, volume-fluid-ounce | {0} жидк. унц. |
| many, volume-fluid-ounce | {0} жидк. унц. |
| other, volume-fluid-ounce | {0} жидк. унц. |
| volume-tablespoon | ↴ |
| , volume-tablespoon | ст. л. |
| one, volume-tablespoon | {0} ст. л. |
| few, volume-tablespoon | {0} ст. л. |
| many, volume-tablespoon | {0} ст. л. |
| other, volume-tablespoon | {0} ст. л. |
| volume-teaspoon | ↴ |
| , volume-teaspoon | ч. л. |
| one, volume-teaspoon | {0} ч. л. |
| few, volume-teaspoon | {0} ч. л. |
| many, volume-teaspoon | {0} ч. л. |
| other, volume-teaspoon | {0} ч. л. |
| coordinates, east | {0} в. д. |
| coordinates, north | {0} с. ш. |
| coordinates, south | {0} ю. ш. |
| coordinates, west | {0} з. д. |
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ↴ |
| , acceleration-g-force | g |
| one, acceleration-g-force | {0} G |
| few, acceleration-g-force | {0} G |
| many, acceleration-g-force | {0} G |
| other, acceleration-g-force | {0} G |
| acceleration-meter-per-second-squared | ↴ |
| , acceleration-meter-per-second-squared | м/с² |
| one, acceleration-meter-per-second-squared | {0} м/с² |
| few, acceleration-meter-per-second-squared | {0} м/с² |
| many, acceleration-meter-per-second-squared | {0} м/с² |
| other, acceleration-meter-per-second-squared | {0} м/с² |
| angle-degree | ↴ |
| one, angle-degree | {0}° |
| few, angle-degree | {0}° |
| many, angle-degree | {0}° |
| other, angle-degree | {0}° |
| angle-arc-minute | ↴ |
| one, angle-arc-minute | {0}′ |
| few, angle-arc-minute | {0}′ |
| many, angle-arc-minute | {0}′ |
| other, angle-arc-minute | {0}′ |
| angle-arc-second | ↴ |
| one, angle-arc-second | {0}″ |
| few, angle-arc-second | {0}″ |
| many, angle-arc-second | {0}″ |
| other, angle-arc-second | {0}″ |
| area-square-kilometer | ↴ |
| one, area-square-kilometer | {0} км² |
| few, area-square-kilometer | {0} км² |
| many, area-square-kilometer | {0} км² |
| other, area-square-kilometer | {0} км² |
| area-hectare | ↴ |
| one, area-hectare | {0} га |
| few, area-hectare | {0} га |
| many, area-hectare | {0} га |
| other, area-hectare | {0} га |
| area-square-meter | ↴ |
| one, area-square-meter | {0} м² |
| few, area-square-meter | {0} м² |
| many, area-square-meter | {0} м² |
| other, area-square-meter | {0} м² |
| area-square-mile | ↴ |
| one, area-square-mile | {0} кв. миля |
| few, area-square-mile | {0} кв. мили |
| many, area-square-mile | {0} кв. миль |
| other, area-square-mile | {0} кв. мили |
| area-acre | ↴ |
| one, area-acre | {0} акр |
| few, area-acre | {0} акра |
| many, area-acre | {0} акров |
| other, area-acre | {0} акра |
| area-square-foot | ↴ |
| one, area-square-foot | {0} кв. фут |
| few, area-square-foot | {0} кв. фута |
| many, area-square-foot | {0} кв. футов |
| other, area-square-foot | {0} кв. фута |
| consumption-liter-per-100kilometers | ↴ |
| , consumption-liter-per-100kilometers | л/100 км |
| one, consumption-liter-per-100kilometers | {0} л/100 км |
| few, consumption-liter-per-100kilometers | {0} л/100 км |
| many, consumption-liter-per-100kilometers | {0} л/100 км |
| other, consumption-liter-per-100kilometers | {0} л/100 км |
| duration-century | ↴ |
| , duration-century | в. |
| one, duration-century | {0} в. |
| few, duration-century | {0} в. |
| many, duration-century | {0} в. |
| other, duration-century | {0} в. |
| duration-year | ↴ |
| , duration-year | г. |
| one, duration-year | {0} г. |
| few, duration-year | {0} г. |
| many, duration-year | {0} л. |
| other, duration-year | {0} г. |
| per units of duration-year | {0}/г. |
| duration-month | ↴ |
| , duration-month | м. |
| one, duration-month | {0} м. |
| few, duration-month | {0} м. |
| many, duration-month | {0} м. |
| other, duration-month | {0} м. |
| per units of duration-month | {0}/м. |
| duration-week | ↴ |
| , duration-week | н. |
| one, duration-week | {0} н. |
| few, duration-week | {0} н. |
| many, duration-week | {0} н. |
| other, duration-week | {0} н. |
| per units of duration-week | {0}/н. |
| duration-day | ↴ |
| , duration-day | д. |
| one, duration-day | {0} д. |
| few, duration-day | {0} д. |
| many, duration-day | {0} д. |
| other, duration-day | {0} д. |
| per units of duration-day | {0}/д. |
| duration-hour | ↴ |
| , duration-hour | ч |
| one, duration-hour | {0} ч |
| few, duration-hour | {0} ч |
| many, duration-hour | {0} ч |
| other, duration-hour | {0} ч |
| per units of duration-hour | {0}/ч. |
| duration-minute | ↴ |
| , duration-minute | мин |
| one, duration-minute | {0} мин |
| few, duration-minute | {0} мин |
| many, duration-minute | {0} мин |
| other, duration-minute | {0} мин |
| per units of duration-minute | {0}/мин. |
| duration-second | ↴ |
| , duration-second | c |
| one, duration-second | {0} с |
| few, duration-second | {0} с |
| many, duration-second | {0} с |
| other, duration-second | {0} с |
| per units of duration-second | {0}/c |
| duration-millisecond | ↴ |
| , duration-millisecond | мс |
| one, duration-millisecond | {0} мс |
| few, duration-millisecond | {0} мс |
| many, duration-millisecond | {0} мс |
| other, duration-millisecond | {0} мс |
| duration-microsecond | ↴ |
| , duration-microsecond | мкс |
| one, duration-microsecond | {0} мкс |
| few, duration-microsecond | {0} мкс |
| many, duration-microsecond | {0} мкс |
| other, duration-microsecond | {0} мкс |
| duration-nanosecond | ↴ |
| , duration-nanosecond | нс |
| one, duration-nanosecond | {0} нс |
| few, duration-nanosecond | {0} нс |
| many, duration-nanosecond | {0} нс |
| other, duration-nanosecond | {0} нс |
| length-kilometer | ↴ |
| , length-kilometer | км |
| one, length-kilometer | {0} км |
| few, length-kilometer | {0} км |
| many, length-kilometer | {0} км |
| other, length-kilometer | {0} км |
| per units of length-kilometer | {0}/км |
| length-meter | ↴ |
| , length-meter | м |
| one, length-meter | {0} м |
| few, length-meter | {0} м |
| many, length-meter | {0} м |
| other, length-meter | {0} м |
| per units of length-meter | {0}/м |
| length-decimeter | ↴ |
| , length-decimeter | дм |
| one, length-decimeter | {0} дм |
| few, length-decimeter | {0} дм |
| many, length-decimeter | {0} дм |
| other, length-decimeter | {0} дм |
| length-centimeter | ↴ |
| , length-centimeter | см |
| one, length-centimeter | {0} см |
| few, length-centimeter | {0} см |
| many, length-centimeter | {0} см |
| other, length-centimeter | {0} см |
| per units of length-centimeter | {0}/см |
| length-millimeter | ↴ |
| , length-millimeter | мм |
| one, length-millimeter | {0} мм |
| few, length-millimeter | {0} мм |
| many, length-millimeter | {0} мм |
| other, length-millimeter | {0} мм |
| length-micrometer | ↴ |
| , length-micrometer | мкм |
| one, length-micrometer | {0} мкм |
| few, length-micrometer | {0} мкм |
| many, length-micrometer | {0} мкм |
| other, length-micrometer | {0} мкм |
| length-nanometer | ↴ |
| , length-nanometer | нм |
| one, length-nanometer | {0} нм |
| few, length-nanometer | {0} нм |
| many, length-nanometer | {0} нм |
| other, length-nanometer | {0} нм |
| length-picometer | ↴ |
| , length-picometer | пм |
| one, length-picometer | {0} pm |
| few, length-picometer | {0} pm |
| many, length-picometer | {0} pm |
| other, length-picometer | {0} pm |
| length-mile | ↴ |
| , length-mile | мл. |
| one, length-mile | {0} миля |
| few, length-mile | {0} миль |
| many, length-mile | {0} миль |
| other, length-mile | {0} мили |
| length-yard | ↴ |
| , length-yard | ярд. |
| one, length-yard | {0} ярд |
| few, length-yard | {0} ярда |
| many, length-yard | {0} ярдов |
| other, length-yard | {0} ярда |
| length-foot | ↴ |
| , length-foot | фт |
| one, length-foot | {0} фт |
| few, length-foot | {0} фт |
| many, length-foot | {0} фт |
| other, length-foot | {0} фт |
| per units of length-foot | {0}/фт |
| length-inch | ↴ |
| , length-inch | дюйм. |
| one, length-inch | {0} дюйм |
| few, length-inch | {0} дюйма |
| many, length-inch | {0} дюймов |
| other, length-inch | {0} дюйма |
| per units of length-inch | {0}/дюйм. |
| length-parsec | ↴ |
| , length-parsec | пк |
| one, length-parsec | {0} пк |
| few, length-parsec | {0} пк |
| many, length-parsec | {0} пк |
| other, length-parsec | {0} пк |
| length-light-year | ↴ |
| , length-light-year | св. годы |
| one, length-light-year | {0} св. г. |
| few, length-light-year | {0} св. г. |
| many, length-light-year | {0} св. л. |
| other, length-light-year | {0} св. г. |
| length-astronomical-unit | ↴ |
| , length-astronomical-unit | а. е. |
| one, length-astronomical-unit | {0} а. е. |
| few, length-astronomical-unit | {0} а. е. |
| many, length-astronomical-unit | {0} а. е. |
| other, length-astronomical-unit | {0} а. е. |
| length-furlong | ↴ |
| , length-furlong | фрл |
| one, length-furlong | {0} фрл |
| few, length-furlong | {0} фрл |
| many, length-furlong | {0} фрл |
| other, length-furlong | {0} фрл |
| length-fathom | ↴ |
| , length-fathom | м. саж. |
| one, length-fathom | {0} м. саж. |
| few, length-fathom | {0} м. саж. |
| many, length-fathom | {0} м. саж. |
| other, length-fathom | {0} м. саж. |
| length-nautical-mile | ↴ |
| , length-nautical-mile | мор. мили |
| one, length-nautical-mile | {0} м. мл. |
| few, length-nautical-mile | {0} м. мл. |
| many, length-nautical-mile | {0} м. мл. |
| other, length-nautical-mile | {0} м. мл. |
| length-mile-scandinavian | ↴ |
| , length-mile-scandinavian | ск. мл. |
| one, length-mile-scandinavian | {0} ск. мл. |
| few, length-mile-scandinavian | {0} ск. мл. |
| many, length-mile-scandinavian | {0} ск. мл. |
| other, length-mile-scandinavian | {0} ск. мл. |
| length-point | ↴ |
| , length-point | пкт |
| one, length-point | {0} пкт |
| few, length-point | {0} пкт |
| many, length-point | {0} пкт |
| other, length-point | {0} пкт |
| mass-metric-ton | ↴ |
| , mass-metric-ton | т |
| one, mass-metric-ton | {0} т |
| few, mass-metric-ton | {0} т |
| many, mass-metric-ton | {0} т |
| other, mass-metric-ton | {0} т |
| mass-kilogram | ↴ |
| , mass-kilogram | кг |
| one, mass-kilogram | {0} кг |
| few, mass-kilogram | {0} кг |
| many, mass-kilogram | {0} кг |
| other, mass-kilogram | {0} кг |
| per units of mass-kilogram | {0}/кг |
| mass-gram | ↴ |
| , mass-gram | г |
| one, mass-gram | {0} г |
| few, mass-gram | {0} г |
| many, mass-gram | {0} г |
| other, mass-gram | {0} г |
| per units of mass-gram | {0}/г |
| mass-milligram | ↴ |
| , mass-milligram | мг |
| one, mass-milligram | {0} мг |
| few, mass-milligram | {0} мг |
| many, mass-milligram | {0} мг |
| other, mass-milligram | {0} мг |
| mass-microgram | ↴ |
| , mass-microgram | мкг |
| one, mass-microgram | {0} мкг |
| few, mass-microgram | {0} мкг |
| many, mass-microgram | {0} мкг |
| other, mass-microgram | {0} мкг |
| mass-ton | ↴ |
| , mass-ton | ам. т |
| one, mass-ton | {0} ам. т |
| few, mass-ton | {0} ам. т |
| many, mass-ton | {0} ам. т |
| other, mass-ton | {0} ам. т |
| mass-stone | ↴ |
| , mass-stone | стн |
| one, mass-stone | {0} стн |
| few, mass-stone | {0} стн |
| many, mass-stone | {0} стн |
| other, mass-stone | {0} стн |
| mass-pound | ↴ |
| , mass-pound | фнт |
| one, mass-pound | {0} lb |
| few, mass-pound | {0} lb |
| many, mass-pound | {0} lb |
| other, mass-pound | {0} lb |
| per units of mass-pound | {0}/фнт |
| mass-ounce | ↴ |
| , mass-ounce | унц. |
| one, mass-ounce | {0} oz |
| few, mass-ounce | {0} oz |
| many, mass-ounce | {0} oz |
| other, mass-ounce | {0} oz |
| per units of mass-ounce | {0}/унц. |
| mass-ounce-troy | ↴ |
| , mass-ounce-troy | тр. унц. |
| one, mass-ounce-troy | {0} тр. унц. |
| few, mass-ounce-troy | {0} тр. унц. |
| many, mass-ounce-troy | {0} тр. унц. |
| other, mass-ounce-troy | {0} тр. унц. |
| mass-carat | ↴ |
| , mass-carat | кар |
| one, mass-carat | {0} кар |
| few, mass-carat | {0} кар |
| many, mass-carat | {0} кар |
| other, mass-carat | {0} кар |
| power-kilowatt | ↴ |
| one, power-kilowatt | {0} кВт |
| few, power-kilowatt | {0} кВт |
| many, power-kilowatt | {0} кВт |
| other, power-kilowatt | {0} кВт |
| power-watt | ↴ |
| one, power-watt | {0} Вт |
| few, power-watt | {0} Вт |
| many, power-watt | {0} Вт |
| other, power-watt | {0} Вт |
| power-horsepower | ↴ |
| one, power-horsepower | {0} л.с. |
| few, power-horsepower | {0} л.с. |
| many, power-horsepower | {0} л.с. |
| other, power-horsepower | {0} л.с. |
| pressure-hectopascal | ↴ |
| , pressure-hectopascal | гПа |
| one, pressure-hectopascal | {0} гПа |
| few, pressure-hectopascal | {0} гПа |
| many, pressure-hectopascal | {0} гПа |
| other, pressure-hectopascal | {0} гПа |
| pressure-millimeter-of-mercury | ↴ |
| , pressure-millimeter-of-mercury | мм рт. ст. |
| one, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| few, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| many, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| other, pressure-millimeter-of-mercury | {0} мм рт. ст. |
| pressure-pound-per-square-inch | ↴ |
| , pressure-pound-per-square-inch | ф. на дюйм² |
| one, pressure-pound-per-square-inch | {0} ф./дюйм² |
| few, pressure-pound-per-square-inch | {0} ф./дюйм² |
| many, pressure-pound-per-square-inch | {0} ф./дюйм² |
| other, pressure-pound-per-square-inch | {0} ф./дюйм² |
| pressure-inch-hg | ↴ |
| , pressure-inch-hg | д. рт. ст. |
| one, pressure-inch-hg | {0} inHg |
| few, pressure-inch-hg | {0} inHg |
| many, pressure-inch-hg | {0} inHg |
| other, pressure-inch-hg | {0} inHg |
| pressure-millibar | ↴ |
| , pressure-millibar | мбар |
| one, pressure-millibar | {0} мбар |
| few, pressure-millibar | {0} мбар |
| many, pressure-millibar | {0} мбар |
| other, pressure-millibar | {0} мбар |
| speed-kilometer-per-hour | ↴ |
| , speed-kilometer-per-hour | км/ч |
| one, speed-kilometer-per-hour | {0} км/ч |
| few, speed-kilometer-per-hour | {0} км/ч |
| many, speed-kilometer-per-hour | {0} км/ч |
| other, speed-kilometer-per-hour | {0} км/ч |
| speed-meter-per-second | ↴ |
| , speed-meter-per-second | м/с |
| one, speed-meter-per-second | {0} м/с |
| few, speed-meter-per-second | {0} м/с |
| many, speed-meter-per-second | {0} м/с |
| other, speed-meter-per-second | {0} м/с |
| speed-mile-per-hour | ↴ |
| , speed-mile-per-hour | мили/час |
| one, speed-mile-per-hour | {0} миль/ч |
| few, speed-mile-per-hour | {0} миль/ч |
| many, speed-mile-per-hour | {0} миль/ч |
| other, speed-mile-per-hour | {0} миль/ч |
| speed-knot | ↴ |
| , speed-knot | уз |
| one, speed-knot | {0} уз |
| few, speed-knot | {0} уз |
| many, speed-knot | {0} уз |
| other, speed-knot | {0} уз |
| temperature-generic | ↴ |
| , temperature-generic | ° |
| one, temperature-generic | {0}° |
| few, temperature-generic | {0}° |
| many, temperature-generic | {0}° |
| other, temperature-generic | {0}° |
| temperature-celsius | ↴ |
| , temperature-celsius | °C |
| one, temperature-celsius | {0} °C |
| few, temperature-celsius | {0} °C |
| many, temperature-celsius | {0} °C |
| other, temperature-celsius | {0} °C |
| temperature-fahrenheit | ↴ |
| , temperature-fahrenheit | °F |
| one, temperature-fahrenheit | {0}°F |
| few, temperature-fahrenheit | {0}°F |
| many, temperature-fahrenheit | {0}°F |
| other, temperature-fahrenheit | {0}°F |
| temperature-kelvin | ↴ |
| , temperature-kelvin | K |
| one, temperature-kelvin | {0} K |
| few, temperature-kelvin | {0} K |
| many, temperature-kelvin | {0} K |
| other, temperature-kelvin | {0} K |
| volume-cubic-kilometer | ↴ |
| one, volume-cubic-kilometer | {0} км³ |
| few, volume-cubic-kilometer | {0} км³ |
| many, volume-cubic-kilometer | {0} км³ |
| other, volume-cubic-kilometer | {0} км³ |
| volume-cubic-mile | ↴ |
| one, volume-cubic-mile | {0} куб. миля |
| few, volume-cubic-mile | {0} куб. мили |
| many, volume-cubic-mile | {0} куб. мили |
| other, volume-cubic-mile | {0} куб. мили |
| volume-liter | ↴ |
| , volume-liter | л |
| one, volume-liter | {0} л |
| few, volume-liter | {0} л |
| many, volume-liter | {0} л |
| other, volume-liter | {0} л |
| coordinates, east | {0} в. д. |
| coordinates, north | {0} с. ш. |
| coordinates, south | {0} ю. ш. |
| coordinates, west | {0} з. д. |
| , hm | h:mm |
| , hms | h:mm:ss |
| , ms | m:ss |

## Lists

| List type | Patterns |
| --------- | -------- |
|  | ↴ |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} и {1} |
| 2 | {0} и {1} |
| or | ↴ |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} или {1} |
| 2 | {0} или {1} |
| standard-short | ↴ |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} и {1} |
| 2 | {0} и {1} |
| unit | ↴ |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
| unit-narrow | ↴ |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |
| unit-short | ↴ |
| start | {0} {1} |
| middle | {0} {1} |
| end | {0} {1} |
| 2 | {0} {1} |

## POSIX

| Messages | Values |
| -------- | ------ |
| `yes` / affirmative | `да:д` |
| `no` / negative | `нет:н` |

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
| ------------ | ---- |
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
