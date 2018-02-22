---
layout: default
title: "CLDR Inari Sámi (via LDML2markdown)"
---

## CLDR core data for Inari Sámi

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a â b c č d đ e f g h i j k l m n ŋ o p r s š t u v y z ž ä á]` |
| auxiliary characters | `[à ç é è í ñ ń ó ò q ú ü w x æ ø å ã ö]` |
| index characters | `[A Â B C Č D Đ E F G H I J K L M N Ŋ O P R S Š T U V Y Z Ž Ä Á]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| Country Data and Default Content | smn_FI |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Inari Sámi is already written in latin script |

### Casing

**This was taken from casing/se.xml**

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName | lowercase |
| currencyName_count | lowercase |
| day_format_except_narrow | lowercase |
| day_narrow | titlecase |
| day_standalone_except_narrow | lowercase |
| era_abbr | lowercase |
| era_name | lowercase |
| era_narrow | lowercase |
| key | lowercase |
| keyValue | lowercase |
| language | lowercase |
| month_format_except_narrow | lowercase |
| month_narrow | titlecase |
| month_standalone_except_narrow | lowercase |
| script | lowercase |
| symbol | titlecase |
| territory | titlecase |
| variant | titlecase |
| zone_exemplarCity | titlecase |

### Collation

Alphabetical order,
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers
#### search
```
				[import und-u-co-search]
				[import smn-u-co-standard]

```
#### standard
```
				&A<â<<<Â<<à<<<À
				&C<č<<<Č
				&D<đ<<<Đ
				&Ŋ<<ñ<<<Ñ<<ń<<<Ń  # root already sorts n<ŋ<<<Ŋ
				&S<š<<<Š
				&Z<ž<<<Ž<æ<<<Æ<ø<<<Ø<å<<<Å<ã<<<Ã<ä<<<Ä<á<<<Á<ö<<<Ö

```

## CLDR minimal data for Inari Sámi

**Needed soon after submitting new locale**.

### Required date-time formats


#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | uđiv |
| month 2 | kuovâ |
| month 3 | njuhčâ |
| month 4 | cuáŋui |
| month 5 | vyesi |
| month 6 | kesi |
| month 7 | syeini |
| month 8 | porge |
| month 9 | čohčâ |
| month 10 | roovvâd |
| month 11 | skammâ |
| month 12 | juovlâ |
| month 1 | U |
| month 2 | K |
| month 3 | NJ |
| month 4 | C |
| month 5 | V |
| month 6 | K |
| month 7 | S |
| month 8 | P |
| month 9 | Č |
| month 10 | R |
| month 11 | S |
| month 12 | J |
| month 1 | uđđâivemáánu |
| month 2 | kuovâmáánu |
| month 3 | njuhčâmáánu |
| month 4 | cuáŋuimáánu |
| month 5 | vyesimáánu |
| month 6 | kesimáánu |
| month 7 | syeinimáánu |
| month 8 | porgemáánu |
| month 9 | čohčâmáánu |
| month 10 | roovvâdmáánu |
| month 11 | skammâmáánu |
| month 12 | juovlâmáánu |
| month 1 | uđiv |
| month 2 | kuovâ |
| month 3 | njuhčâ |
| month 4 | cuáŋui |
| month 5 | vyesi |
| month 6 | kesi |
| month 7 | syeini |
| month 8 | porge |
| month 9 | čohčâ |
| month 10 | roovvâd |
| month 11 | skammâ |
| month 12 | juovlâ |
| month 1 | U |
| month 2 | K |
| month 3 | NJ |
| month 4 | C |
| month 5 | V |
| month 6 | K |
| month 7 | S |
| month 8 | P |
| month 9 | Č |
| month 10 | R |
| month 11 | S |
| month 12 | J |
| month 1 | uđđâivemáánu |
| month 2 | kuovâmáánu |
| month 3 | njuhčâmáánu |
| month 4 | cuáŋuimáánu |
| month 5 | vyesimáánu |
| month 6 | kesimáánu |
| month 7 | syeinimáánu |
| month 8 | porgemáánu |
| month 9 | čohčâmáánu |
| month 10 | roovvâdmáánu |
| month 11 | skammâmáánu |
| month 12 | juovlâmáánu |
| (week)day sun | pas |
| (week)day mon | vuo |
| (week)day tue | maj |
| (week)day wed | kos |
| (week)day thu | tuo |
| (week)day fri | vás |
| (week)day sat | láv |
| (week)day sun | p |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | V |
| (week)day sat | L |
| (week)day sun | pa |
| (week)day mon | vu |
| (week)day tue | ma |
| (week)day wed | ko |
| (week)day thu | tu |
| (week)day fri | vá |
| (week)day sat | lá |
| (week)day sun | pasepeeivi |
| (week)day mon | vuossaargâ |
| (week)day tue | majebaargâ |
| (week)day wed | koskoho |
| (week)day thu | tuorâstuv |
| (week)day fri | vástuppeeivi |
| (week)day sat | lávurduv |
| (week)day sun | pas |
| (week)day mon | vuo |
| (week)day tue | maj |
| (week)day wed | kos |
| (week)day thu | tuo |
| (week)day fri | vás |
| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | W |
| (week)day thu | T |
| (week)day fri | F |
| (week)day sat | S |
| (week)day sun | pa |
| (week)day mon | vu |
| (week)day tue | ma |
| (week)day wed | ko |
| (week)day thu | tu |
| (week)day fri | vá |
| (week)day sat | lá |
| (week)day sun | pasepeivi |
| (week)day mon | vuossargâ |
| (week)day tue | majebargâ |
| (week)day wed | koskokko |
| (week)day thu | tuorâstâh |
| (week)day fri | vástuppeivi |
| (week)day sat | lávurdâh |
| quarter 1 | 1. niälj. |
| quarter 2 | 2. niälj. |
| quarter 3 | 3. niälj. |
| quarter 4 | 4. niälj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. niäljádâs |
| quarter 2 | 2. niäljádâs |
| quarter 3 | 3. niäljádâs |
| quarter 4 | 4. niäljádâs |
| quarter 1 | 1. niälj. |
| quarter 2 | 2. niälj. |
| quarter 3 | 3. niälj. |
| quarter 4 | 4. niälj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. niäljádâs |
| quarter 2 | 2. niäljádâs |
| quarter 3 | 3. niäljádâs |
| quarter 4 | 4. niäljádâs |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| era | Ovdil Kristus šoddâm |
| era | Ovdil ääigirekinistem älgim |
| era | maŋa Kristus šoddâm |
| era | maŋa ääigirekinistem älgim |
| era | oKr. |
| era | oää. |
| era | mKr. |
| era | mää. |
| date format | `cccc, MMMM d. y` |
| date format | `MMMM d. y` |
| date format | `MMM d. y` |
| date format | `d.M.y` |
| time format | `H.mm.ss zzzz` |
| time format | `H.mm.ss z` |
| time format | `H.mm.ss` |
| time format | `H.mm` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E H.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E H.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `MMM d. y G` |
| date format `GyMMMEd` | `E, MMM d. y G` |
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
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `E, MMM d.` |
| date format `MMMMd` | `MMMM d.` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `ms` | `m.ss.` |
| date format `y` | `y` |
| date format `yM` | `L.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E d.M.y` |
| date format `yMMM` | `LLL y` |
| date format `yMMMd` | `MMM d. y` |
| date format `yMMMEd` | `ccc, MMM d. y` |
| date format `yMMMM` | `LLLL y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'okko' w, Y` |
| date format `yw` | `'okko' w, Y` |
| date format `yw` | `'okko' w, Y` |
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
| interval format `MMMd` | `MMM d.–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMMM E d. – E d.MMMM E d. – MMMM E d.` |
| interval format `y` | `y–y` |
| interval format `yM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMd` | `d. – d.M.yd.M.–d.M.yd.M.y–d.M.y` |
| interval format `yMEd` | `E d.M.y – E d.M.yE d.M.y – E d.M.yE d.M.y – E d.M.y` |
| interval format `yMMM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMMMd` | `MMMM d.–d. yMMMM d. – MMMM d. yMMMM d. y – MMMM d. y` |
| interval format `yMMMEd` | `MMMM E d. – E d. yMMMM E d. – MMMM E d. yMMMM E d. y – MMMM E d. y` |
| interval format `yMMMM` | `LLL–LLLL yLLLL y – LLLL y` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `cccc MMMM d. y G` |
| date format | `MMMM d. y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E d.` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `MMM d. y G` |
| date format `GyMMMEd` | `E MMM d. y G` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `ccc MMM d.` |
| date format `MMMMd` | `d. MMMM` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `MMM d. y G` |
| date format `yyyyMMMEd` | `E MMM d. y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d.–d.` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `MMMM d.–d.MMMM d. – MMMM d.` |
| interval format `MMMEd` | `MMMM E d. – E d.MMMM E d. – MMMM E d.` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `MMMM d.–d. y GMMMM d. – MMMM d. y GMMMM d. y – MMMM d. y G` |
| interval format `yMMMEd` | `MMMM E d. – E d. y GMMMM E d. – MMMM E d. y GMMMM E d. y – MMMM E d. y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |

### Important names in language

Language:

| `smn` | anarâškielâ |

Country or territory:

| `FI` | Suomâ |

Currency:

|  | euro |

### Datetime patterns

| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E d.` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `MMM d. y G` |
| date format `GyMMMEd` | `E MMM d. y G` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `ccc MMM d.` |
| date format `MMMMd` | `d. MMMM` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `MMM d. y G` |
| date format `yyyyMMMEd` | `E MMM d. y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d.–d.` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `MMMM d.–d.MMMM d. – MMMM d.` |
| interval format `MMMEd` | `MMMM E d. – E d.MMMM E d. – MMMM E d.` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `MMMM d.–d. y GMMMM d. – MMMM d. y GMMMM d. y – MMMM d. y G` |
| interval format `yMMMEd` | `MMMM E d. – E d. y GMMMM E d. – MMMM E d. y GMMMM E d. y – MMMM E d. y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |

### Number formats

| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | epiloho |
| Time separator (Hours:Minutes) | . |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

### Locale pattern

(how software should display languages)

#### Locale display patterns

| Things | Patterns |
| ------ | -------- |
| language, country | `{0} ({1})` |
| locale, another locale | `{0}, {1}` |
| label: locale | `{0}: {1}` |

### some important words to translate

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13869 $smn
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
| `ab` | abhasiakielâ |
| `ace` | atšehkielâ |
| `ada` | adangme |
| `ady` | adyge |
| `af` | afrikaans |
| `agq` | aghem |
| `ain` | ainukielâ |
| `ak` | akankielâ |
| `ale` | aleutkielâ |
| `alt` | maadâaltaikielâ |
| `am` | amharakielâ |
| `an` | aragoniakielâ |
| `anp` | angika |
| `ar` | arabiakielâ |
| `ar_001` | standard arabiakielâ |
| `arn` | mapudungun |
| `arp` | arapahokielâ |
| `as` | assamkielâ |
| `asa` | asukielâ |
| `ast` | asturiakielâ |
| `av` | avarkielâ |
| `awa` | awadhikielâ |
| `ay` | aymarakielâ |
| `az` | azerbaidžankielâ |
| `ba` | baškirkielâ |
| `ban` | balikielâ |
| `bas` | basaakielâ |
| `be` | vielgisruošâkielâ |
| `bem` | bembakielâ |
| `bez` | benakielâ |
| `bg` | bulgariakielâ |
| `bho` | bhožpurikielâ |
| `bi` | bislama |
| `bin` | binikielâ |
| `bla` | siksikakielâ |
| `bm` | bambarakielâ |
| `bn` | banglakielâ |
| `bo` | tiibetkielâ |
| `br` | bretonkielâ |
| `brx` | bodokielâ |
| `bs` | bosniakielâ |
| `bug` | bugikielâ |
| `byn` | blinkielâ |
| `ca` | katalankielâ |
| `ce` | tšetšenkielâ |
| `ceb` | cebuanokielâ |
| `cgg` | kigakielâ |
| `ch` | chamorrokielâ |
| `chk` | chuukkielâ |
| `chm` | marikielâ |
| `cho` | choctawkielâ |
| `chr` | cherokeekielâ |
| `chy` | cheyennekielâ |
| `ckb` | sorani kurdikielâ |
| `co` | korsikakielâ |
| `crs` | Seychellij kreoliranska |
| `cs` | tšeekikielâ |
| `cu` | kirkkoslaavi |
| `cv` | tšuvaskielâ |
| `cy` | kymrikielâ |
| `da` | tanskakielâ |
| `dak` | dakotakielâ |
| `dar` | dargikielâ |
| `dav` | taitakielâ |
| `de` | saksakielâ |
| `de_AT` | Nuorttâriijkâ saksakielâ |
| `de_CH` | Sveitsi pajesaksakielâ |
| `dgr` | dogribkielâ |
| `dje` | zarmakielâ |
| `dsb` | vyelisorbi |
| `dua` | dualakielâ |
| `dv` | divehikielâ |
| `dyo` | jola-fonyi |
| `dz` | Dzongkha |
| `dzg` | dazakielâ |
| `ebu` | embukielâ |
| `ee` | ewekielâ |
| `efi` | efikkielâ |
| `eka` | ekajuk |
| `el` | kreikakielâ |
| `en` | eŋgâlâskielâ |
| `en_AU` | Australia eŋgâlâskielâ |
| `en_CA` | Kanada eŋgâlâskielâ |
| `en_GB` | Britannia eŋgâlâskielâ |
| `en_GB` | eŋgâlâskielâ (OK) |
| `en_US` | Amerika eŋgâlâskielâ |
| `en_US` | eŋgâlâskielâ (USA) |
| `eo` | esperantokielâ |
| `es` | espanjakielâ |
| `es_419` | Läättin-Amerika espanjakielâ |
| `es_ES` | Espanja espanjakielâ |
| `es_MX` | Meksiko espanjakielâ |
| `et` | eestikielâ |
| `eu` | baskikielâ |
| `ewo` | ewondokielâ |
| `fa` | persiakielâ |
| `ff` | fulakielâ |
| `fi` | suomâkielâ |
| `fil` | filipinokielâ |
| `fj` | fidžikielâ |
| `fo` | fäärikielâ |
| `fon` | fonkielâ |
| `fr` | ranskakielâ |
| `fr_CA` | Kanada ranskakielâ |
| `fr_CH` | Sveitsi ranskakielâ |
| `fur` | friulikielâ |
| `fy` | viestârfriisi |
| `ga` | iirikielâ |
| `gaa` | gakielâ |
| `gd` | skottilâš gaelikielâ |
| `gez` | ge’ez |
| `gil` | kiribatikielâ |
| `gl` | galiciakielâ |
| `gn` | guaranikielâ |
| `gor` | gorontalokielâ |
| `grc` | toovláš kreikakielâ |
| `gsw` | Sveitsi saksakielâ |
| `gu` | gudžaratikielâ |
| `guz` | gusiikielâ |
| `gv` | manks |
| `gwi` | gwich’inkielâ |
| `ha` | hausakielâ |
| `haw` | hawaijikielâ |
| `he` | hepreakielâ |
| `hi` | hindikielâ |
| `hil` | hiligainokielâ |
| `hmn` | hmongkielâ |
| `hr` | kroatiakielâ |
| `hsb` | pajesorbi |
| `ht` | Haiti kreoli |
| `hu` | uŋgarkielâ |
| `hup` | hupakielâ |
| `hy` | armeniakielâ |
| `hz` | hererokielâ |
| `ia` | interlingua |
| `iba` | ibankielâ |
| `ibb` | ibibiokielâ |
| `id` | indonesiakielâ |
| `ig` | igbokielâ |
| `ilo` | ilocano |
| `inh` | inguškielâ |
| `io` | ido |
| `is` | islandkielâ |
| `it` | italiakielâ |
| `iu` | inuktitut |
| `ja` | jaapaankielâ |
| `jbo` | lojban |
| `jgo` | ngomba |
| `jmc` | machame |
| `jv` | jaavakielâ |
| `ka` | georgiakielâ |
| `kab` | kabylkielâ |
| `kac` | kachin |
| `kaj` | jju |
| `kam` | kambakielâ |
| `kbd` | kabardikielâ |
| `kcg` | tyap |
| `kde` | makonde |
| `kea` | Kap Verde kreoli |
| `kfo` | koro |
| `kha` | khasi |
| `khq` | koyra chiini |
| `ki` | kikujukielâ |
| `kj` | kuanjama |
| `kk` | kazakkielâ |
| `kkj` | kako |
| `kl` | kalaallisut |
| `kln` | kalenjikielâ |
| `km` | khmerkielâ |
| `kmb` | kimbundu |
| `kn` | kannada |
| `ko` | koreakielâ |
| `kok` | konkani |
| `kpe` | kpellekielâ |
| `kr` | kanurikielâ |
| `krc` | karachai-balkarkielâ |
| `krl` | kärjilkielâ |
| `kru` | kurukhkielâ |
| `ks` | kashmirkielâ |
| `ksb` | shambala |
| `ksf` | bafia |
| `ksh` | kölnkielâ |
| `ku` | kurdikielâ |
| `kum` | kumykkielâ |
| `kv` | komikielâ |
| `kw` | kornikielâ |
| `ky` | kirgiskielâ |
| `la` | läättinkielâ |
| `lad` | ladinokielâ |
| `lag` | langokielâ |
| `lb` | luxemburgkielâ |
| `lez` | lezgikielâ |
| `lg` | luganda |
| `li` | limburgkielâ |
| `lkt` | lakotakielâ |
| `ln` | lingala |
| `lo` | laokielâ |
| `loz` | lozi |
| `lrc` | taveluri |
| `lt` | liettuakielâ |
| `lu` | katangaluba |
| `lua` | lulualuba |
| `lun` | lunda |
| `luo` | luo |
| `lus` | lusai |
| `luy` | luhya |
| `lv` | latviakielâ |
| `mad` | madurakielâ |
| `mag` | magahi |
| `mai` | maithili |
| `mak` | makasar |
| `mas` | masaikielâ |
| `mdf` | mokšakielâ |
| `men` | mendekielâ |
| `mer` | merukielâ |
| `mfe` | morisyen |
| `mg` | malagaskielâ |
| `mgh` | makua-meetto |
| `mgo` | meta’ |
| `mh` | marshallkielâ |
| `mi` | maorikielâ |
| `mic` | micmac |
| `min` | minangkabau |
| `mk` | makedoniakielâ |
| `ml` | malajam |
| `mn` | mongoliakielâ |
| `mni` | manipuri |
| `moh` | mohawkkielâ |
| `mos` | moore |
| `mr` | marathikielâ |
| `mrj` | viestârmari |
| `ms` | malaiji |
| `mt` | maltakielâ |
| `mua` | mundang |
| `mul` | maŋgâ kielâ |
| `mus` | muskogeekielâ |
| `mwl` | mirandeskielâ |
| `my` | burmakielâ |
| `myv` | ersäkielâ |
| `mzn` | mazandarani |
| `na` | naurukielâ |
| `nap` | napolikielâ |
| `naq` | nama |
| `nb` | tárukielâ bokmål |
| `nd` | tave-nbedele |
| `nds_NL` | Vuáládâhenâmij saksakielâ |
| `ne` | nepalkielâ |
| `new` | newari |
| `ng` | ndonga |
| `nia` | niaskielâ |
| `niu` | niuekielâ |
| `nl` | hollandkielâ |
| `nl_BE` | hollandkielâ (flaami) |
| `nmg` | kwasio |
| `nn` | tárukielâ nynorsk |
| `nnh` | ngiemboon |
| `no` | tárukielâ |
| `nog` | nogaikielâ |
| `non` | toovláš tárukielâ |
| `nqo` | n’ko |
| `nr` | maadâ-nbedele |
| `nso` | tavesotho |
| `nus` | nuer |
| `nv` | navajokielâ |
| `ny` | njanža |
| `nyn` | nyankolekielâ |
| `oc` | oksitan |
| `om` | oromokielâ |
| `or` | orija |
| `os` | ossetkielâ |
| `pa` | pandžabi |
| `pag` | pangasinankielâ |
| `pam` | pampangakielâ |
| `pap` | papiamentu |
| `pau` | palaukielâ |
| `pcm` | Nigeria pidgin |
| `pl` | puolakielâ |
| `prg` | toovláš preussikielâ |
| `ps` | paštu |
| `pt` | portugalkielâ |
| `pt_BR` | Brasilia portugalkielâ |
| `pt_PT` | Portugal portugalkielâ |
| `qu` | quechua |
| `quc` | ki’che’ |
| `rap` | rapanui |
| `rar` | rarotonga |
| `rm` | retoroomaankielâ |
| `rn` | rundi |
| `ro` | romaniakielâ |
| `rof` | rombo |
| `rom` | roomaankielâ |
| `root` | ruotâs |
| `ru` | ruošâkielâ |
| `rup` | aromaniakielâ |
| `rw` | ruandakielâ |
| `rwk` | rwa |
| `sa` | sanskrit |
| `sad` | sandawe |
| `sah` | jakutkielâ |
| `saq` | samburukielâ |
| `sat` | santalikielâ |
| `sba` | ngambay |
| `sbp` | sangu |
| `sc` | sardiniakielâ |
| `scn` | sisiliakielâ |
| `sco` | skootikielâ |
| `sd` | sindhi |
| `se` | tavekielâ |
| `seh` | sena |
| `ses` | koyraboro senni |
| `sg` | sango |
| `shi` | tašelhit |
| `shn` | shankielâ |
| `si` | sinhala |
| `sk` | slovakiakielâ |
| `sl` | sloveniakielâ |
| `sm` | samoakielâ |
| `sma` | maadâsämikielâ |
| `smj` | juulevsämikielâ |
| `smn` | anarâškielâ |
| `sms` | nuorttâlâškielâ |
| `sn` | shona |
| `snk` | soninke |
| `so` | somalikielâ |
| `sq` | albaniakielâ |
| `sr` | serbiakielâ |
| `srn` | sranantongo |
| `ss` | swazikielâ |
| `ssy` | saho |
| `st` | maadâsotho |
| `su` | sundakielâ |
| `suk` | sukumakielâ |
| `sv` | ruotâkielâ |
| `sw` | swahilikielâ |
| `sw_CD` | Kongo swahilikielâ |
| `swb` | komorikielâ |
| `syr` | syyriakielâ |
| `ta` | tamilkielâ |
| `te` | telugu |
| `tem` | temnekielâ |
| `teo` | ateso |
| `tet` | tetum |
| `tg` | tadžikkielâ |
| `th` | thaikielâ |
| `ti` | tigrinyakielâ |
| `tig` | tigrekielâ |
| `tk` | turkmenkielâ |
| `tlh` | klingonkielâ |
| `tn` | tswanakielâ |
| `to` | tongakielâ |
| `tpi` | tok pisin |
| `tr` | tuurkikielâ |
| `trv` | taroko |
| `ts` | tsongakielâ |
| `tt` | tatarkielâ |
| `tum` | tumbukakielâ |
| `tvl` | tuvalukielâ |
| `twq` | tasawaq |
| `ty` | tahitikielâ |
| `tyv` | tuvakielâ |
| `tzm` | Koskâatlas tamazight |
| `udm` | udmurtkielâ |
| `ug` | uigurkielâ |
| `uk` | ukrainakielâ |
| `umb` | umbundu |
| `und` | tubdâmettumis kielâ |
| `ur` | urdu |
| `uz` | uzbekkielâ |
| `vai` | vaikielâ |
| `ve` | vendakielâ |
| `vep` | vepsäkielâ |
| `vi` | vietnamkielâ |
| `vo` | volapük |
| `vun` | vunjo |
| `wa` | walloonkielâ |
| `wae` | walliskielâ |
| `wal` | wolaitakielâ |
| `war` | waraykielâ |
| `wo` | wolofkielâ |
| `xal` | kalmukkielâ |
| `xh` | xhosakielâ |
| `xog` | soga |
| `yav` | yangben |
| `ybb` | yemba |
| `yi` | jiddish |
| `yo` | yorubakielâ |
| `yue` | kantonkielâ |
| `zgh` | standard tamazight |
| `zh` | mandarinkiinakielâ |
| `zh_Hans` | oovtâkiärdánis kiinakielâ |
| `zh_Hant` | ärbivuáválâš kiinakielâ |
| `zu` | zulukielâ |
| `zun` | zunikielâ |
| `zxx` | ij kielâlâš siskáldâs |
| `zza` | zazakielâ |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `AC` | Ascension-suálui |
| `AD` | Andorra |
| `AE` | Arabiemirkodeh |
| `AF` | Afganistan |
| `AG` | Antigua já Barbuda |
| `AI` | Anguilla |
| `AL` | Albania |
| `AM` | Armenia |
| `AO` | Angola |
| `AQ` | Antarktis |
| `AR` | Argentina |
| `AS` | Amerika Samoa |
| `AT` | Nuorttâriijkâ |
| `AU` | Australia |
| `AW` | Aruba |
| `AX` | Vuáskueennâm |
| `AZ` | Azerbaidžan |
| `BA` | Bosnia já Herzegovina |
| `BB` | Barbados |
| `BD` | Bangladesh |
| `BE` | Belgia |
| `BF` | Burkina Faso |
| `BG` | Bulgaria |
| `BH` | Bahrain |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | St. Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Bolivia |
| `BR` | Brasilia |
| `BS` | Bahama |
| `BT` | Bhutan |
| `BV` | Bouvetsuálui |
| `BW` | Botswana |
| `BY` | Vielgis-Ruoššâ |
| `BZ` | Belize |
| `CA` | Kanada |
| `CC` | Kookossuolluuh (Keelingsuolluuh) |
| `CD` | Kongo demokraattisâš täsiväldi |
| `CF` | Koskâ-Afrika täsiväldi |
| `CG` | Kongo täsiväldi |
| `CH` | Sveitsi |
| `CI` | Côte d’Ivoire |
| `CK` | Cooksuolluuh |
| `CL` | Chile |
| `CM` | Kamerun |
| `CN` | Kiina |
| `CO` | Kolumbia |
| `CP` | Clippertonsuálui |
| `CR` | Costa Rica |
| `CU` | Kuuba |
| `CV` | Cape Verde |
| `CW` | Curaçao |
| `CX` | Juovlâsuálui |
| `CY` | Kypros |
| `CZ` | Tšekki |
| `DE` | Saksa |
| `DG` | Diego Garcia |
| `DJ` | Djibouti |
| `DK` | Tanska |
| `DM` | Dominica |
| `DO` | Dominikaanisâš täsiväldi |
| `DZ` | Algeria |
| `EA` | Ceuta já Melilla |
| `EC` | Ecuador |
| `EE` | Eestieennâm |
| `EG` | Egypti |
| `ER` | Eritrea |
| `ES` | Espanja |
| `ET` | Etiopia |
| `FI` | Suomâ |
| `FJ` | Fidži |
| `FK` | Falklandsuolluuh |
| `FK` | Falklandsuolluuh (Malvinassuolluuh) |
| `FM` | Mikronesia littoväldi |
| `FO` | Färsuolluuh |
| `FR` | Ranska |
| `GA` | Gabon |
| `GB` | Ovtâstum Kunâgâskodde |
| `GB` | OK |
| `GD` | Grenada |
| `GE` | Georgia |
| `GF` | Ranska Guyana |
| `GG` | Guernsey |
| `GH` | Ghana |
| `GI` | Gibraltar |
| `GL` | Grönland |
| `GM` | Gambia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Peeivitäsideijee Guinea |
| `GR` | Kreikka |
| `GS` | Maadâ-Georgia já Máddááh Sandwichsuolluuh |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Guinea-Bissau |
| `GY` | Guyana |
| `HK` | Hongkong – Kiina e.h.k. |
| `HK` | Hong Kong |
| `HM` | Heard já McDonaldsuolluuh |
| `HN` | Honduras |
| `HR` | Kroatia |
| `HT` | Haiti |
| `HU` | Uŋgar |
| `IC` | Kanariasuolluuh |
| `ID` | Indonesia |
| `IE` | Irland |
| `IL` | Israel |
| `IM` | Mansuálui |
| `IN` | India |
| `IO` | Brittilâš India väldimeerâ kuávlu |
| `IQ` | Irak |
| `IR` | Iran |
| `IS` | Island |
| `IT` | Italia |
| `JE` | Jersey |
| `JM` | Jamaika |
| `JO` | Jordan |
| `JP` | Jaapaan |
| `KE` | Kenia |
| `KG` | Kirgisia |
| `KH` | Kambodža |
| `KI` | Kiribati |
| `KM` | Komoreh |
| `KN` | St. Kitts já Nevis |
| `KP` | Tave-Korea |
| `KR` | Maadâ-Korea |
| `KW` | Kuwait |
| `KY` | Caymansuolluuh |
| `KZ` | Kazakstan |
| `LA` | Laos |
| `LB` | Libanon |
| `LC` | St. Lucia |
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
| `MF` | St. Martin |
| `MG` | Madagaskar |
| `MH` | Marshallsuolluuh |
| `MK` | OJT Makedonia |
| `ML` | Mali |
| `MM` | Myanmar (Burma) |
| `MN` | Mongolia |
| `MO` | Macao - – Kiina e.h.k. |
| `MO` | Macao |
| `MP` | Tave-Marianeh |
| `MQ` | Martinique |
| `MR` | Mauritania |
| `MS` | Montserrat |
| `MT` | Malta |
| `MU` | Mauritius |
| `MV` | Malediveh |
| `MW` | Malawi |
| `MX` | Meksiko |
| `MY` | Malaysia |
| `MZ` | Mosambik |
| `NA` | Namibia |
| `NC` | Uđđâ-Kaledonia |
| `NE` | Niger |
| `NF` | Norfolksuálui |
| `NG` | Nigeria |
| `NI` | Nicaragua |
| `NL` | Vuáládâhenâmeh |
| `NO` | Taažâ |
| `NP` | Nepal |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | Uđđâ-Seeland |
| `OM` | Oman |
| `PA` | Panama |
| `PE` | Peru |
| `PF` | Ranska Polynesia |
| `PG` | Papua-Uđđâ-Guinea |
| `PH` | Filipineh |
| `PK` | Pakistan |
| `PL` | Puola |
| `PM` | St. Pierre já Miquelon |
| `PN` | Pitcairn |
| `PR` | Puerto Rico |
| `PT` | Portugal |
| `PW` | Palau |
| `PY` | Paraguay |
| `QA` | Qatar |
| `RE` | Réunion |
| `RO` | Romania |
| `RS` | Serbia |
| `RU` | Ruoššâ |
| `RW` | Ruanda |
| `SA` | Saudi Arabia |
| `SB` | Salomosuolluuh |
| `SC` | Seychelleh |
| `SD` | Sudan |
| `SE` | Ruotâ |
| `SG` | Singapore |
| `SH` | Saint Helena |
| `SI` | Slovenia |
| `SJ` | Čokkeväärih já Jan Mayen |
| `SK` | Slovakia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Senegal |
| `SO` | Somalia |
| `SR` | Surinam |
| `SS` | Maadâ-Sudan |
| `ST` | São Tomé já Príncipe |
| `SV` | El Salvador |
| `SX` | Sint Maarten |
| `SY` | Syria |
| `SZ` | Swazieennâm |
| `TA` | Tristan da Cunha |
| `TC` | Turks- já Caicossuolluuh |
| `TD` | Tšad |
| `TF` | Ranska máddááh kuávluh |
| `TG` | Togo |
| `TH` | Thaieennâm |
| `TJ` | Tadžikistan |
| `TK` | Tokelau |
| `TL` | Timor-Leste |
| `TM` | Turkmenistan |
| `TN` | Tunisia |
| `TO` | Tonga |
| `TR` | Turkki |
| `TT` | Trinidad já Tobago |
| `TV` | Tuvalu |
| `TW` | Taiwan |
| `TZ` | Tansania |
| `UA` | Ukraina |
| `UG` | Uganda |
| `UM` | Ovtâstum Staatâi sierânâssuolluuh |
| `US` | Ovtâstum Staatah |
| `US` | USA |
| `UY` | Uruguay |
| `UZ` | Uzbekistan |
| `VA` | Vatikan |
| `VC` | St. Vincent já Grenadines |
| `VE` | Venezuela |
| `VG` | Brittiliih Nieidâsuolluuh |
| `VI` | Ovtâstum Staatâi Nieidâsuolluuh |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis já Futuna |
| `WS` | Samoa |
| `XK` | Kosovo |
| `YE` | Jemen |
| `YT` | Mayotte |
| `ZA` | Maadâ-Afrikka |
| `ZM` | Sambia |
| `ZW` | Zimbabwe |
| `metric` | metrisâš |
| `UK` | brittilâš |
| `US` | ameriklâš |
### Code patterns
kielâ: {0}čäällimvuáhádâh: {0}kuávlu: {0}left-to-righttop-to-bottom
### Character processing for computer systems
| main characters | `[a â b c č d đ e f g h i j k l m n ŋ o p r s š t u v y z ž ä á]` |
| auxiliary characters | `[à ç é è í ñ ń ó ò q ú ü w x æ ø å ã ö]` |
| index characters | `[A Â B C Č D Đ E F G H I J K L M N Ŋ O P R S Š T U V Y Z Ž Ä Á]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
## Calendar data
#### generic calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `cccc MMMM d. y G` |
| date format | `MMMM d. y G` |
| date format | `d.M.y G` |
| date format | `d.M.y GGGGG` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E d.` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `MMM d. y G` |
| date format `GyMMMEd` | `E MMM d. y G` |
| date format `M` | `L` |
| date format `Md` | `d.M.` |
| date format `MEd` | `E d.M.` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `ccc MMM d.` |
| date format `MMMMd` | `d. MMMM` |
| date format `y` | `y G` |
| date format `yyyy` | `y G` |
| date format `yyyyM` | `L.y G` |
| date format `yyyyMd` | `d.M.y G` |
| date format `yyyyMEd` | `E d.M.y G` |
| date format `yyyyMMM` | `LLL y G` |
| date format `yyyyMMMd` | `MMM d. y G` |
| date format `yyyyMMMEd` | `E MMM d. y G` |
| date format `yyyyMMMM` | `LLLL y G` |
| date format `yyyyQQQ` | `QQQ y G` |
| date format `yyyyQQQQ` | `QQQQ y G` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d.–d.` |
| interval format `M` | `L.–L.` |
| interval format `Md` | `d.–d.M.d.M.–d.M.` |
| interval format `MEd` | `E d. – E d.M.E d.M. – E d.M.` |
| interval format `MMM` | `LLL–LLLL` |
| interval format `MMMd` | `MMMM d.–d.MMMM d. – MMMM d.` |
| interval format `MMMEd` | `MMMM E d. – E d.MMMM E d. – MMMM E d.` |
| interval format `y` | `y–y G` |
| interval format `yM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMd` | `d.–d.M.y Gd.M.–d.M.y Gd.M.y–d.M.y G` |
| interval format `yMEd` | `E d.M.y – E d.M.y GE d.M.y – E d.M.y GE d.M.y – E d.M.y G` |
| interval format `yMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
| interval format `yMMMd` | `MMMM d.–d. y GMMMM d. – MMMM d. y GMMMM d. y – MMMM d. y G` |
| interval format `yMMMEd` | `MMMM E d. – E d. y GMMMM E d. – MMMM E d. y GMMMM E d. y – MMMM E d. y G` |
| interval format `yMMMM` | `LLL–LLLL y GLLLL y – LLLL y G` |
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | uđiv |
| month 2 | kuovâ |
| month 3 | njuhčâ |
| month 4 | cuáŋui |
| month 5 | vyesi |
| month 6 | kesi |
| month 7 | syeini |
| month 8 | porge |
| month 9 | čohčâ |
| month 10 | roovvâd |
| month 11 | skammâ |
| month 12 | juovlâ |
| month 1 | U |
| month 2 | K |
| month 3 | NJ |
| month 4 | C |
| month 5 | V |
| month 6 | K |
| month 7 | S |
| month 8 | P |
| month 9 | Č |
| month 10 | R |
| month 11 | S |
| month 12 | J |
| month 1 | uđđâivemáánu |
| month 2 | kuovâmáánu |
| month 3 | njuhčâmáánu |
| month 4 | cuáŋuimáánu |
| month 5 | vyesimáánu |
| month 6 | kesimáánu |
| month 7 | syeinimáánu |
| month 8 | porgemáánu |
| month 9 | čohčâmáánu |
| month 10 | roovvâdmáánu |
| month 11 | skammâmáánu |
| month 12 | juovlâmáánu |
| month 1 | uđiv |
| month 2 | kuovâ |
| month 3 | njuhčâ |
| month 4 | cuáŋui |
| month 5 | vyesi |
| month 6 | kesi |
| month 7 | syeini |
| month 8 | porge |
| month 9 | čohčâ |
| month 10 | roovvâd |
| month 11 | skammâ |
| month 12 | juovlâ |
| month 1 | U |
| month 2 | K |
| month 3 | NJ |
| month 4 | C |
| month 5 | V |
| month 6 | K |
| month 7 | S |
| month 8 | P |
| month 9 | Č |
| month 10 | R |
| month 11 | S |
| month 12 | J |
| month 1 | uđđâivemáánu |
| month 2 | kuovâmáánu |
| month 3 | njuhčâmáánu |
| month 4 | cuáŋuimáánu |
| month 5 | vyesimáánu |
| month 6 | kesimáánu |
| month 7 | syeinimáánu |
| month 8 | porgemáánu |
| month 9 | čohčâmáánu |
| month 10 | roovvâdmáánu |
| month 11 | skammâmáánu |
| month 12 | juovlâmáánu |
| (week)day sun | pas |
| (week)day mon | vuo |
| (week)day tue | maj |
| (week)day wed | kos |
| (week)day thu | tuo |
| (week)day fri | vás |
| (week)day sat | láv |
| (week)day sun | p |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | K |
| (week)day thu | T |
| (week)day fri | V |
| (week)day sat | L |
| (week)day sun | pa |
| (week)day mon | vu |
| (week)day tue | ma |
| (week)day wed | ko |
| (week)day thu | tu |
| (week)day fri | vá |
| (week)day sat | lá |
| (week)day sun | pasepeeivi |
| (week)day mon | vuossaargâ |
| (week)day tue | majebaargâ |
| (week)day wed | koskoho |
| (week)day thu | tuorâstuv |
| (week)day fri | vástuppeeivi |
| (week)day sat | lávurduv |
| (week)day sun | pas |
| (week)day mon | vuo |
| (week)day tue | maj |
| (week)day wed | kos |
| (week)day thu | tuo |
| (week)day fri | vás |
| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | M |
| (week)day tue | T |
| (week)day wed | W |
| (week)day thu | T |
| (week)day fri | F |
| (week)day sat | S |
| (week)day sun | pa |
| (week)day mon | vu |
| (week)day tue | ma |
| (week)day wed | ko |
| (week)day thu | tu |
| (week)day fri | vá |
| (week)day sat | lá |
| (week)day sun | pasepeivi |
| (week)day mon | vuossargâ |
| (week)day tue | majebargâ |
| (week)day wed | koskokko |
| (week)day thu | tuorâstâh |
| (week)day fri | vástuppeivi |
| (week)day sat | lávurdâh |
| quarter 1 | 1. niälj. |
| quarter 2 | 2. niälj. |
| quarter 3 | 3. niälj. |
| quarter 4 | 4. niälj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. niäljádâs |
| quarter 2 | 2. niäljádâs |
| quarter 3 | 3. niäljádâs |
| quarter 4 | 4. niäljádâs |
| quarter 1 | 1. niälj. |
| quarter 2 | 2. niälj. |
| quarter 3 | 3. niälj. |
| quarter 4 | 4. niälj. |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | 1. niäljádâs |
| quarter 2 | 2. niäljádâs |
| quarter 3 | 3. niäljádâs |
| quarter 4 | 4. niäljádâs |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| period of day am | ip. |
| period of day pm | ep. |
| era | Ovdil Kristus šoddâm |
| era | Ovdil ääigirekinistem älgim |
| era | maŋa Kristus šoddâm |
| era | maŋa ääigirekinistem älgim |
| era | oKr. |
| era | oää. |
| era | mKr. |
| era | mää. |
| date format | `cccc, MMMM d. y` |
| date format | `MMMM d. y` |
| date format | `MMM d. y` |
| date format | `d.M.y` |
| time format | `H.mm.ss zzzz` |
| time format | `H.mm.ss z` |
| time format | `H.mm.ss` |
| time format | `H.mm` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} 'tme' {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `E d.` |
| date format `Ehm` | `E h.mm a` |
| date format `EHm` | `E H.mm` |
| date format `Ehms` | `E h.mm.ss a` |
| date format `EHms` | `E H.mm.ss` |
| date format `Gy` | `y G` |
| date format `GyMMM` | `LLL y G` |
| date format `GyMMMd` | `MMM d. y G` |
| date format `GyMMMEd` | `E, MMM d. y G` |
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
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `E, MMM d.` |
| date format `MMMMd` | `MMMM d.` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `MMMMW` | `'okko' W, MMM` |
| date format `ms` | `m.ss.` |
| date format `y` | `y` |
| date format `yM` | `L.y` |
| date format `yMd` | `d.M.y` |
| date format `yMEd` | `E d.M.y` |
| date format `yMMM` | `LLL y` |
| date format `yMMMd` | `MMM d. y` |
| date format `yMMMEd` | `ccc, MMM d. y` |
| date format `yMMMM` | `LLLL y` |
| date format `yQQQ` | `QQQ y` |
| date format `yQQQQ` | `QQQQ y` |
| date format `yw` | `'okko' w, Y` |
| date format `yw` | `'okko' w, Y` |
| date format `yw` | `'okko' w, Y` |
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
| interval format `MMMd` | `MMM d.–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMMM E d. – E d.MMMM E d. – MMMM E d.` |
| interval format `y` | `y–y` |
| interval format `yM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMd` | `d. – d.M.yd.M.–d.M.yd.M.y–d.M.y` |
| interval format `yMEd` | `E d.M.y – E d.M.yE d.M.y – E d.M.yE d.M.y – E d.M.y` |
| interval format `yMMM` | `LLL–LLLL yLLLL y – LLLL y` |
| interval format `yMMMd` | `MMMM d.–d. yMMMM d. – MMMM d. yMMMM d. y – MMMM d. y` |
| interval format `yMMMEd` | `MMMM E d. – E d. yMMMM E d. – MMMM E d. yMMMM E d. y – MMMM E d. y` |
| interval format `yMMMM` | `LLL–LLLL yLLLL y – LLLL y` |
## Numbers stuff
1
| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Percents | % |
| Plus | + |
| Minus | - |
| Exponential | E |
| Superscripting Exponent | × |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | epiloho |
| Time separator (Hours:Minutes) | . |
#,##0.###0 tuhháát0 tuhháát0 tuhháát00 tuhháát00 tuhháát00 tuhháát000 tuhháát000 tuhháát000 tuhháát0 miljovn0 miljovn0 miljovn00 miljovn00 miljovn00 miljovn000 miljovn000 miljovn000 miljovn0 miljard0 miljard0 miljard00 miljard00 miljard00 miljard000 miljard000 miljard000 miljard0 biljovn0 biljovn0 biljovn00 biljovn00 biljovn00 biljovn000 biljovn000 biljovn000 biljovn#E0#,##0 %#,##0.00 ¤#,##0.00 ¤¤ 0K¤ 0K¤ 0K¤ 00K¤ 00K¤ 00K¤ 000K¤ 000K¤ 000K¤ 0M¤ 0M¤ 0M¤ 00M¤ 00M¤ 00M¤ 000M¤ 000M¤ 000M¤ 0G¤ 0G¤ 0G¤ 00G¤ 00G¤ 00G¤ 000G¤ 000G¤ 000G¤ 0T¤ 0T¤ 0T¤ 00T¤ 00T¤ 00T¤ 000T¤ 000T¤ 000T
| one | {0} {1} |
| two | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  | Tanska ruvnâ |
|  | Eesti ruvnâ |
|  | euro |
|  | Suomâ märkki |
|  | Island ruvnâ |
|  | Latvia ruble |
|  | Taažâ ruvnâ |
|  | Ruotâ ruvnâ |
Other stuff:
ucemustáá {0}{0}–{1}
## Units
| Code | Name |
| ---- | ---- |
| duration-year | ... |
|  | iveh |
| duration-month | ... |
|  | mánuppajeh |
| duration-week | ... |
|  | ohoh |
| duration-day | ... |
|  | peeivih |
| duration-hour | ... |
|  | tiijmeh |
| duration-minute | ... |
|  | minutteh |
| duration-second | ... |
|  | sekunteh |
| duration-millisecond | ... |
|  | millisekunteh |
| duration-microsecond | ... |
|  | mikrosekunteh |
| one | {0} μs |
| two | {0} μs |
| other | {0} μs |
| duration-nanosecond | ... |
|  | nanosekunteh |
