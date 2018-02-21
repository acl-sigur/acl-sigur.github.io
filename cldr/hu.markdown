---
layout: default
title: "CLDR Hungarian (via LDML2markdown)"
---

## CLDR core data for Hungarian

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a á b c {cs} {ccs} d {dz} {ddz} {dzs} {ddzs} e é f g {gy} {ggy} h i í j k l {ly} {lly} m n {ny} {nny} o ó ö ő p r s {sz} {ssz} t {ty} {tty} u ú ü ű v z {zs} {zzs}]` |
| auxiliary characters | `[à ă â å ä ã ā æ ç è ĕ ê ë ē ì ĭ î ï ī ñ ò ŏ ô ø ō œ q ù ŭ û ū w x y ÿ]` |
| index characters | `[A Á B C {CS} D {DZ} {DZS} E É F G {GY} H I Í J K L {LY} M N {NY} O Ó Ö Ő P Q R S {SZ} T {TY} U Ú Ü Ű V W X Y Z {ZS}]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- – , ; \: ! ? . … ' ’ " ” „ « » ( ) \[ \] \{ \} ⟨ ⟩ § @ * / \& # ~ ⁒]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | A kosár tartalma: {0} X. Megveszi? |
| other example | A kosár tartalma: {0} X. Megveszi őket? |
| Country Data and Default Content | hu_HU |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Hungarian is already written in latin script |

### Casing

| Item | Case |
| ---  | ---  |
| calendar_field | lowercase |
| currencyName_count | lowercase |
| day_narrow | titlecase |
| key | titlecase |
| keyValue | titlecase |
| language | lowercase |
| metazone_long | lowercase |
| month_standalone_except_narrow | titlecase |
| quarter_abbreviated | titlecase |
| quarter_format_wide | titlecase |
| relative | lowercase |
| script | titlecase |
| territory | titlecase |
| variant | titlecase |
| zone_exemplarCity | titlecase |
| zone_long | lowercase |

### Collation

Alphabetical order,
I think we roughly need to know things like: sort V alongside W, etc., åäö
at end before numbers

#### standard
```
					&C<cs<<<Cs<<<CS
					&D<dz<<<Dz<<<DZ
					&DZ<dzs<<<Dzs<<<DZS
					&G<gy<<<Gy<<<GY
					&L<ly<<<Ly<<<LY
					&N<ny<<<Ny<<<NY
					&S<sz<<<Sz<<<SZ
					&T<ty<<<Ty<<<TY
					&Z<zs<<<Zs<<<ZS
					&O<ö<<<Ö<<ő<<<Ő
					&U<ü<<<Ü<<ű<<<Ű
					&cs<<<ccs/cs
					&Cs<<<Ccs/cs
					&CS<<<CCS/CS
					&dz<<<ddz/dz
					&Dz<<<Ddz/dz
					&DZ<<<DDZ/DZ
					&dzs<<<ddzs/dzs
					&Dzs<<<Ddzs/dzs
					&DZS<<<DDZS/DZS
					&gy<<<ggy/gy
					&Gy<<<Ggy/gy
					&GY<<<GGY/GY
					&ly<<<lly/ly
					&Ly<<<Lly/ly
					&LY<<<LLY/LY
					&ny<<<nny/ny
					&Ny<<<Nny/ny
					&NY<<<NNY/NY
					&sz<<<ssz/sz
					&Sz<<<Ssz/sz
					&SZ<<<SSZ/SZ
					&ty<<<tty/ty
					&Ty<<<Tty/ty
					&TY<<<TTY/TY
					&zs<<<zzs/zs
					&Zs<<<Zzs/zs
					&ZS<<<ZZS/ZS

```

#### standard

```
					&C<cs<<<cS<<<Cs<<<CS
					&D<dz<<<dZ<<<Dz<<<DZ
					&DZ<dzs<<<dzS<<<dZs<<<dZS<<<Dzs<<<DzS<<<DZs<<<DZS
					&G<gy<<<gY<<<Gy<<<GY
					&L<ly<<<lY<<<Ly<<<LY
					&N<ny<<<nY<<<Ny<<<NY
					&S<sz<<<sZ<<<Sz<<<SZ
					&T<ty<<<tY<<<Ty<<<TY
					&Z<zs<<<zS<<<Zs<<<ZS
					&O<ö<<<Ö<<ő<<<Ő
					&U<ü<<<Ü<<ű<<<Ű
					&cs<<<ccs/cs<<<ccS/cS<<<cCs/Cs<<<cCS/CS
					&Cs<<<Ccs/cs<<<CcS/cS<<<CCs/Cs
					&CS<<<CCS/CS
					&dz<<<ddz/dz<<<ddZ/dZ<<<dDz/Dz<<<dDZ/DZ
					&Dz<<<Ddz/dz<<<DdZ/dZ<<<DDz/Dz
					&DZ<<<DDZ/DZ
					&dzs<<<ddzs/dzs<<<ddzS/dzS<<<ddZs/dZs<<<ddZS/dZS<<<dDzs/Dzs<<<dDzS/DzS<<<dDZs/DZs
					<<<dDZS/DZS
					&Dzs<<<Ddzs/dzs<<<DdzS/dzS<<<DdZs/dZs<<<DdZS/dZS<<<DDzs/Dzs<<<DDzS/DzS<<<DDZs/DZs
					&DZS<<<DDZS/DZS
					&gy<<<ggy/gy<<<ggY/gY<<<gGy/Gy<<<gGY/GY
					&Gy<<<Ggy/gy<<<GgY/gY<<<GGy/Gy
					&GY<<<GGY/GY
					&ly<<<lly/ly<<<llY/lY<<<lLy/Ly<<<lLY/LY
					&Ly<<<Lly/ly<<<LlY/lY<<<LLy/Ly
					&LY<<<LLY/LY
					&ny<<<nny/ny<<<nnY/nY<<<nNy/Ny<<<nNY/NY
					&Ny<<<Nny/ny<<<NnY/nY<<<NNy/Ny
					&NY<<<NNY/NY
					&sz<<<ssz/sz<<<ssZ/sZ<<<sSz/Sz<<<sSZ/SZ
					&Sz<<<Ssz/sz<<<SsZ/sZ<<<SSz/Sz
					&SZ<<<SSZ/SZ
					&ty<<<tty/ty<<<ttY/tY<<<tTy/Ty<<<tTY/TY
					&Ty<<<Tty/ty<<<TtY/tY<<<TTy/Ty
					&TY<<<TTY/TY
					&zs<<<zzs/zs<<<zzS/zS<<<zZs/Zs<<<zZS/ZS
					&Zs<<<Zzs/zs<<<ZzS/zS<<<ZZs/Zs
					&ZS<<<ZZS/ZS

```

## CLDR minimal data for Hungarian

**Needed soon after submitting new locale**.

### Required date-time formats

(44+ needed?)
(Gregorian calendar)

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | jan. |
| month 2 | febr. |
| month 3 | márc. |
| month 4 | ápr. |
| month 5 | máj. |
| month 6 | jún. |
| month 7 | júl. |
| month 8 | aug. |
| month 9 | szept. |
| month 10 | okt. |
| month 11 | nov. |
| month 12 | dec. |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | Á |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | Sz |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| month 1 | január |
| month 2 | február |
| month 3 | március |
| month 4 | április |
| month 5 | május |
| month 6 | június |
| month 7 | július |
| month 8 | augusztus |
| month 9 | szeptember |
| month 10 | október |
| month 11 | november |
| month 12 | december |
| month 1 | jan. |
| month 2 | febr. |
| month 3 | márc. |
| month 4 | ápr. |
| month 5 | máj. |
| month 6 | jún. |
| month 7 | júl. |
| month 8 | aug. |
| month 9 | szept. |
| month 10 | okt. |
| month 11 | nov. |
| month 12 | dec. |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | Á |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | Sz |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| month 1 | január |
| month 2 | február |
| month 3 | március |
| month 4 | április |
| month 5 | május |
| month 6 | június |
| month 7 | július |
| month 8 | augusztus |
| month 9 | szeptember |
| month 10 | október |
| month 11 | november |
| month 12 | december |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sz |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Sz |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | vasárnap |
| (week)day mon | hétfő |
| (week)day tue | kedd |
| (week)day wed | szerda |
| (week)day thu | csütörtök |
| (week)day fri | péntek |
| (week)day sat | szombat |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sz |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Sz |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | vasárnap |
| (week)day mon | hétfő |
| (week)day tue | kedd |
| (week)day wed | szerda |
| (week)day thu | csütörtök |
| (week)day fri | péntek |
| (week)day sat | szombat |
| quarter 1 | I. n.év |
| quarter 2 | II. n.év |
| quarter 3 | III. n.év |
| quarter 4 | IV. n.év |
| quarter 1 | I. |
| quarter 2 | II. |
| quarter 3 | III. |
| quarter 4 | IV. |
| quarter 1 | I. negyedév |
| quarter 2 | II. negyedév |
| quarter 3 | III. negyedév |
| quarter 4 | IV. negyedév |
| quarter 1 | 1. n.év |
| quarter 2 | 2. n.év |
| quarter 3 | 3. n.év |
| quarter 4 | 4. n.év |
| quarter 1 | 1. |
| quarter 2 | 2. |
| quarter 3 | 3. |
| quarter 4 | 4. |
| quarter 1 | 1. negyedév |
| quarter 2 | 2. negyedév |
| quarter 3 | 3. negyedév |
| quarter 4 | 4. negyedév |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | délelőtt |
| period of day afternoon1 | délután |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | délelőtt |
| period of day afternoon1 | délután |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| era | Krisztus előtt |
| era | időszámításunk előtt |
| era | időszámításunk szerint |
| era | i. sz. |
| era | i. e. |
| era | i. sz. |
| era | ie. |
| era | isz. |
| date format | `y. MMMM d., EEEE` |
| date format | `y. MMMM d.` |
| date format | `y. MMM d.` |
| date format | `y. MM. dd.` |
| time format | `H:mm:ss zzzz` |
| time format | `H:mm:ss z` |
| time format | `H:mm:ss` |
| time format | `H:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `B h` |
| date format `Bhm` | `B h:mm` |
| date format `Bhms` | `B h:mm:ss` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E B h:mm` |
| date format `EBhms` | `E B h:mm:ss` |
| date format `Ed` | `d., E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y.` |
| date format `GyMMM` | `G y. MMM` |
| date format `GyMMMd` | `G y. MMM d.` |
| date format `GyMMMEd` | `G y. MMM d., E` |
| date format `h` | `a h` |
| date format `H` | `H` |
| date format `hm` | `a h:mm` |
| date format `Hm` | `H:mm` |
| date format `hms` | `a h:mm:ss` |
| date format `Hms` | `H:mm:ss` |
| date format `hmsv` | `a h:mm:ss v` |
| date format `Hmsv` | `HH:mm:ss v` |
| date format `hmv` | `a h:mm v` |
| date format `Hmv` | `HH:mm v` |
| date format `M` | `L` |
| date format `Md` | `M. d.` |
| date format `MEd` | `M. d., E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `MMM d., E` |
| date format `MMMMd` | `MMMM d.` |
| date format `MMMMW` | `MMM W. 'hete'` |
| date format `MMMMW` | `MMM W. 'hete'` |
| date format `mmss` | `mm:ss` |
| date format `ms` | `mm:ss` |
| date format `y` | `y.` |
| date format `yM` | `y. M.` |
| date format `yMd` | `y. MM. dd.` |
| date format `yMEd` | `y. MM. dd., E` |
| date format `yMMM` | `y. MMM` |
| date format `yMMMd` | `y. MMM d.` |
| date format `yMMMEd` | `y. MMM d., E` |
| date format `yMMMM` | `y. MMMM` |
| date format `yQQQ` | `y. QQQ` |
| date format `yQQQQ` | `y. QQQQ` |
| date format `yw` | `Y w. 'hete'` |
| date format `yw` | `Y w. 'hete'` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d.` |
| interval format `h` | `a h – a ha h–h` |
| interval format `H` | `H–H` |
| interval format `hm` | `a h:mm – a h:mma h:mm–h:mma h:mm–h:mm` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `a h:mm – a h:mm va h:mm–h:mm va h:mm–h:mm v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `a h – a h va h–h v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M.` |
| interval format `Md` | `M. d–d.M. d. – M. d.` |
| interval format `MEd` | `M. dd., E – M. d., EM. d., E – M. d., E` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `MMM d–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMM d., E – d., EMMM d., E – MMM d., E` |
| interval format `y` | `y–y` |
| interval format `yM` | `y. MM–MM.y. MM. – y. MM.` |
| interval format `yMd` | `y. MM. dd–dd.y. MM. dd. – MM. dd.y. MM. dd. – y. MM. dd.` |
| interval format `yMEd` | `y. MM. dd., E – dd., Ey. MM. dd., E – MM. dd., Ey. MM. dd., E – y. MM. dd., E` |
| interval format `yMMM` | `y. MMM–MMMy. MMM – y. MMM` |
| interval format `yMMMd` | `y. MMM d–d.y. MMM d. – MMM d.y. MMM d. – y. MMM d.` |
| interval format `yMMMEd` | `y. MMM d., E – d., Ey. MMM d., E – MMM d., Ey. MMM d., E – y. MMM d., E` |
| interval format `yMMMM` | `y. MMMM–MMMMy. MMMM – y. MMMM` |

#### generic calendar

| ID-stuff | values |
| -------- | ------ |
| date format | `G y. MMMM d., EEEE` |
| date format | `G y. MMMM d.` |
| date format | `G y. MMM d.` |
| date format | `GGGGG y. M. d.` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `B h` |
| date format `Bhm` | `B h:mm` |
| date format `Bhms` | `B h:mm:ss` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm` |
| date format `EBhms` | `E h:mm:ss` |
| date format `Ed` | `d., E` |
| date format `Ehm` | `E h:mm` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y.` |
| date format `GyMMM` | `G y. MMM` |
| date format `GyMMMd` | `G y. MMM d.` |
| date format `GyMMMEd` | `G y. MMM d., E` |
| date format `h` | `a h` |
| date format `H` | `H` |
| date format `hm` | `a h:mm` |
| date format `Hm` | `H:mm` |
| date format `hms` | `a h:mm:ss` |
| date format `Hms` | `H:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M. d.` |
| date format `MEd` | `M. d., E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `MMM d., E` |
| date format `MMMMd` | `MMMM d.` |
| date format `ms` | `mm:ss` |
| date format `y` | `G y.` |
| date format `yyyy` | `G y.` |
| date format `yyyyM` | `G y. MM.` |
| date format `yyyyMd` | `G y. MM. dd.` |
| date format `yyyyMEd` | `G y. MM. dd., E` |
| date format `yyyyMMM` | `G y. MMM` |
| date format `yyyyMMMd` | `G y. MMM d.` |
| date format `yyyyMMMEd` | `G y. MMM d., E` |
| date format `yyyyMMMM` | `G y. MMMM` |
| date format `yyyyQQQ` | `G y. QQQ` |
| date format `yyyyQQQQ` | `G y. QQQQ` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d.` |
| interval format `h` | `a h – a ha h–h` |
| interval format `H` | `H–H` |
| interval format `hm` | `a h:mm – a h:mma h:mm–h:mma h:mm–h:mm` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `a h:mm – a h:mm va h:mm–h:mm va h:mm–h:mm v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `a h – a h va h–h v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M.` |
| interval format `Md` | `MM. dd–dd.MM. dd. – MM. dd.` |
| interval format `MEd` | `MM. dd., E – MM. dd., EMM. dd., E – MM. dd., E` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `MMM d–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMM d., E – d., EMMM d., E – MMM d., E` |
| interval format `y` | `G y–y.` |
| interval format `yM` | `G y. MM–MM.G y. MM. – y. MM.` |
| interval format `yMd` | `G y. MM. dd–dd.G y. MM. dd. – MM. dd.G y. MM. dd. – y. MM. dd.` |
| interval format `yMEd` | `G y. MM. dd., E – dd., EG y. MM. dd., E – MM. dd., EG y. MM. dd., E – y. MM. dd., E` |
| interval format `yMMM` | `G y. MMM–MMMG y. MMM – y. MMM` |
| interval format `yMMMd` | `G y. MMM d–d.G y. MMM d. – MMM d.G y. MMM d. – y. MMM d.` |
| interval format `yMMMEd` | `G y. MMM d., E – MMM d., EG y. MMM d., E – MMM d., EG y. MMM d., E – y. MMM d., E` |
| interval format `yMMMM` | `G y. MMMM–MMMMG y. MMMM – y. MMMM` |

### Important names in language

Language:
| `hu` | magyar |

Country or territory:

| `HU` | Magyarország |

Currency:

|  | magyar forint |
| one | magyar forint |
| other | magyar forint |
|  symbol | Ft |
| narrow symbol | Ft |

### Datetime patterns

| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `B h` |
| date format `Bhm` | `B h:mm` |
| date format `Bhms` | `B h:mm:ss` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm` |
| date format `EBhms` | `E h:mm:ss` |
| date format `Ed` | `d., E` |
| date format `Ehm` | `E h:mm` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y.` |
| date format `GyMMM` | `G y. MMM` |
| date format `GyMMMd` | `G y. MMM d.` |
| date format `GyMMMEd` | `G y. MMM d., E` |
| date format `h` | `a h` |
| date format `H` | `H` |
| date format `hm` | `a h:mm` |
| date format `Hm` | `H:mm` |
| date format `hms` | `a h:mm:ss` |
| date format `Hms` | `H:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M. d.` |
| date format `MEd` | `M. d., E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `MMM d., E` |
| date format `MMMMd` | `MMMM d.` |
| date format `ms` | `mm:ss` |
| date format `y` | `G y.` |
| date format `yyyy` | `G y.` |
| date format `yyyyM` | `G y. MM.` |
| date format `yyyyMd` | `G y. MM. dd.` |
| date format `yyyyMEd` | `G y. MM. dd., E` |
| date format `yyyyMMM` | `G y. MMM` |
| date format `yyyyMMMd` | `G y. MMM d.` |
| date format `yyyyMMMEd` | `G y. MMM d., E` |
| date format `yyyyMMMM` | `G y. MMMM` |
| date format `yyyyQQQ` | `G y. QQQ` |
| date format `yyyyQQQQ` | `G y. QQQQ` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d.` |
| interval format `h` | `a h – a ha h–h` |
| interval format `H` | `H–H` |
| interval format `hm` | `a h:mm – a h:mma h:mm–h:mma h:mm–h:mm` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `a h:mm – a h:mm va h:mm–h:mm va h:mm–h:mm v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `a h – a h va h–h v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M.` |
| interval format `Md` | `MM. dd–dd.MM. dd. – MM. dd.` |
| interval format `MEd` | `MM. dd., E – MM. dd., EMM. dd., E – MM. dd., E` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `MMM d–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMM d., E – d., EMMM d., E – MMM d., E` |
| interval format `y` | `G y–y.` |
| interval format `yM` | `G y. MM–MM.G y. MM. – y. MM.` |
| interval format `yMd` | `G y. MM. dd–dd.G y. MM. dd. – MM. dd.G y. MM. dd. – y. MM. dd.` |
| interval format `yMEd` | `G y. MM. dd., E – dd., EG y. MM. dd., E – MM. dd., EG y. MM. dd., E – y. MM. dd., E` |
| interval format `yMMM` | `G y. MMM–MMMG y. MMM – y. MMM` |
| interval format `yMMMd` | `G y. MMM d–d.G y. MMM d. – MMM d.G y. MMM d. – y. MMM d.` |
| interval format `yMMMEd` | `G y. MMM d., E – MMM d., EG y. MMM d., E – MMM d., EG y. MMM d., E – y. MMM d., E` |
| interval format `yMMMM` | `G y. MMMM–MMMMG y. MMMM – y. MMMM` |


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
| Not a number | NaN |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| Time at Greenwich | GMT |
| regional | {0} idő |
| regional | {0} nyári idő |
| regional | {0} zónaidő |
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
| `calendar` | Naptár |
| `cf` | Pénznemformátum |
| `colAlternate` | Szimbólumokat figyelmen kívül hagyó rendezés |
| `colBackwards` | Ékezetek fordított rendezése |
| `colCaseFirst` | Rendezés nagy- vagy kisbetűk szerint |
| `colCaseLevel` | Kisbetű-nagybetű érzékeny rendezés |
| `collation` | Rendezési sorrend |
| `colNormalization` | Normalizált rendezés |
| `colNumeric` | Numerikus rendezés |
| `colStrength` | Rendezés erőssége |
| `currency` | Pénznem |
| `hc` | Óraformátum (12 – 24) |
| `lb` | Sortörés stílusa |
| `ms` | Mértékegységrendszer |
| `numbers` | Számok |
| `timezone` | Időzóna |
| `va` | Földrajzi helyvariáns |
| `x` | Privát használatra |

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13904 $hu
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
| `ab` | abház |
| `ace` | achinéz |
| `ach` | akoli |
| `ada` | adangme |
| `ady` | adyghe |
| `ae` | avesztán |
| `af` | afrikaans |
| `afh` | afrihili |
| `agq` | agem |
| `ain` | ainu |
| `ak` | akan |
| `akk` | akkád |
| `ale` | aleut |
| `alt` | dél-altaji |
| `am` | amhara |
| `an` | aragonéz |
| `ang` | óangol |
| `anp` | angika |
| `ar` | arab |
| `ar_001` | modern szabányos arab |
| `arc` | arámi |
| `arn` | mapucse |
| `arp` | arapaho |
| `ars` | nedzsdi arab |
| `arw` | aravak |
| `as` | asszámi |
| `asa` | asu |
| `ast` | asztúr |
| `av` | avar |
| `awa` | awádi |
| `ay` | ajmara |
| `az` | azerbajdzsáni |
| `az` | azeri |
| `ba` | baskír |
| `bal` | balucsi |
| `ban` | balinéz |
| `bas` | basza |
| `bax` | bamun |
| `bbj` | gomala |
| `be` | belarusz |
| `bej` | bedzsa |
| `bem` | bemba |
| `bez` | bena |
| `bfd` | bafut |
| `bg` | bolgár |
| `bgn` | nyugati beludzs |
| `bho` | bodzspuri |
| `bi` | bislama |
| `bik` | bikol |
| `bin` | bini |
| `bkm` | kom |
| `bla` | siksika |
| `bm` | bambara |
| `bn` | bangla |
| `bo` | tibeti |
| `br` | breton |
| `bra` | braj |
| `brx` | bodo |
| `bs` | bosnyák |
| `bss` | koszi |
| `bua` | burját |
| `bug` | buginéz |
| `bum` | bulu |
| `byn` | blin |
| `byv` | medumba |
| `ca` | katalán |
| `cad` | caddo |
| `car` | karib |
| `cay` | kajuga |
| `cch` | atszam |
| `ce` | csecsen |
| `ceb` | szebuano |
| `cgg` | kiga |
| `ch` | csamoró |
| `chb` | csibcsa |
| `chg` | csagatáj |
| `chk` | csukéz |
| `chm` | mari |
| `chn` | csinuk zsargon |
| `cho` | csoktó |
| `chp` | csipevé |
| `chr` | cseroki |
| `chy` | csejen |
| `ckb` | közép-ázsiai kurd |
| `co` | korzikai |
| `cop` | kopt |
| `cr` | krí |
| `crh` | krími tatár |
| `crs` | szeszelva kreol francia |
| `cs` | cseh |
| `csb` | kasub |
| `cu` | egyházi szláv |
| `cv` | csuvas |
| `cy` | walesi |
| `da` | dán |
| `dak` | dakota |
| `dar` | dargva |
| `dav` | taita |
| `de` | német |
| `de_AT` | osztrák német |
| `de_CH` | svájci felnémet |
| `del` | delavár |
| `den` | szlevi |
| `dgr` | dogrib |
| `din` | dinka |
| `dje` | zarma |
| `doi` | dogri |
| `dsb` | alsó-szorb |
| `dua` | duala |
| `dum` | közép holland |
| `dv` | divehi |
| `dyo` | jola-fonyi |
| `dyu` | diula |
| `dz` | dzsonga |
| `dzg` | dazaga |
| `ebu` | embu |
| `ee` | eve |
| `efi` | efik |
| `egy` | óegyiptomi |
| `eka` | ekadzsuk |
| `el` | görög |
| `elx` | elamit |
| `en` | angol |
| `en_AU` | ausztrál angol |
| `en_CA` | kanadai angol |
| `en_GB` | brit angol |
| `en_GB` | angol (UK) |
| `en_US` | amerikai angol |
| `en_US` | angol (USA) |
| `enm` | közép angol |
| `eo` | eszperantó |
| `es` | spanyol |
| `es_419` | latin-amerikai spanyol |
| `es_ES` | európai spanyol |
| `es_MX` | spanyol (mexikói) |
| `et` | észt |
| `eu` | baszk |
| `ewo` | evondo |
| `fa` | perzsa |
| `fan` | fang |
| `fat` | fanti |
| `ff` | fulani |
| `fi` | finn |
| `fil` | filippínó |
| `fj` | fidzsi |
| `fo` | feröeri |
| `fon` | fon |
| `fr` | francia |
| `fr_CA` | kanadai francia |
| `fr_CH` | svájci francia |
| `frc` | cajun francia |
| `frm` | közép francia |
| `fro` | ófrancia |
| `frr` | északi fríz |
| `frs` | keleti fríz |
| `fur` | friuli |
| `fy` | nyugati fríz |
| `ga` | ír |
| `gaa` | ga |
| `gag` | gagauz |
| `gan` | gan kínai |
| `gay` | gajo |
| `gba` | gbaja |
| `gd` | skóciai kelta |
| `gez` | geez |
| `gil` | ikiribati |
| `gl` | gallego |
| `gmh` | közép felső német |
| `gn` | guarani |
| `goh` | ófelső német |
| `gon` | gondi |
| `gor` | gorontalo |
| `got` | gót |
| `grb` | grebó |
| `grc` | ógörög |
| `gsw` | svájci német |
| `gu` | gudzsaráti |
| `guz` | guszii |
| `gv` | man-szigeti |
| `gwi` | gvicsin |
| `ha` | hausza |
| `hai` | haida |
| `hak` | hakka kínai |
| `haw` | hawaii |
| `he` | héber |
| `hi` | hindi |
| `hil` | ilokano |
| `hit` | hittite |
| `hmn` | hmong |
| `ho` | hiri motu |
| `hr` | horvát |
| `hsb` | felső-szorb |
| `hsn` | xiang kínai |
| `ht` | haiti kreol |
| `hu` | magyar |
| `hup` | hupa |
| `hy` | örmény |
| `hz` | herero |
| `ia` | interlingva |
| `iba` | iban |
| `ibb` | ibibio |
| `id` | indonéz |
| `ie` | interlingue |
| `ig` | igbó |
| `ii` | szecsuán ji |
| `ik` | inupiak |
| `ilo` | ilokó |
| `inh` | ingus |
| `io` | idó |
| `is` | izlandi |
| `it` | olasz |
| `iu` | inuktitut |
| `ja` | japán |
| `jbo` | lojban |
| `jgo` | ngomba |
| `jmc` | machame |
| `jpr` | zsidó-perzsa |
| `jrb` | zsidó-arab |
| `jv` | jávai |
| `ka` | grúz |
| `kaa` | kara-kalpak |
| `kab` | kabije |
| `kac` | kacsin |
| `kaj` | jju |
| `kam` | kamba |
| `kaw` | kawi |
| `kbd` | kabardi |
| `kbl` | kanembu |
| `kcg` | tyap |
| `kde` | makonde |
| `kea` | kabuverdianu |
| `kfo` | koro |
| `kg` | kongo |
| `kha` | kaszi |
| `kho` | kotanéz |
| `khq` | kojra-csíni |
| `ki` | kikuju |
| `kj` | kuanyama |
| `kk` | kazah |
| `kkj` | kakó |
| `kl` | grönlandi |
| `kln` | kalendzsin |
| `km` | khmer |
| `kmb` | kimbundu |
| `kn` | kannada |
| `ko` | koreai |
| `koi` | komi-permják |
| `kok` | konkani |
| `kos` | kosrei |
| `kpe` | kpelle |
| `kr` | kanuri |
| `krc` | karacsáj-balkár |
| `krl` | karelai |
| `kru` | kuruh |
| `ks` | kasmíri |
| `ksb` | sambala |
| `ksf` | bafia |
| `ksh` | kölsch |
| `ku` | kurd |
| `kum` | kumük |
| `kut` | kutenai |
| `kv` | komi |
| `kw` | korni |
| `ky` | kirgiz |
| `la` | latin |
| `lad` | ladino |
| `lag` | langi |
| `lah` | lahnda |
| `lam` | lamba |
| `lb` | luxemburgi |
| `lez` | lezg |
| `lg` | ganda |
| `li` | limburgi |
| `lkt` | lakota |
| `ln` | lingala |
| `lo` | lao |
| `lol` | mongó |
| `lou` | louisianai kreol |
| `loz` | lozi |
| `lrc` | északi luri |
| `lt` | litván |
| `lu` | luba-katanga |
| `lua` | luba-lulua |
| `lui` | luiseno |
| `lun` | lunda |
| `luo` | luo |
| `lus` | lushai |
| `luy` | lujia |
| `lv` | lett |
| `mad` | madurai |
| `maf` | mafa |
| `mag` | magahi |
| `mai` | maithili |
| `mak` | makaszar |
| `man` | mandingó |
| `mas` | masai |
| `mde` | maba |
| `mdf` | moksán |
| `mdr` | mandar |
| `men` | mende |
| `mer` | meru |
| `mfe` | mauritiusi kreol |
| `mg` | malgas |
| `mga` | közép ír |
| `mgh` | makua-metó |
| `mgo` | meta’ |
| `mh` | marshalli |
| `mi` | maori |
| `mic` | mikmak |
| `min` | minangkabau |
| `mk` | macedón |
| `ml` | malajálam |
| `mn` | mongol |
| `mnc` | mandzsu |
| `mni` | manipuri |
| `moh` | mohawk |
| `mos` | moszi |
| `mr` | maráthi |
| `ms` | maláj |
| `mt` | máltai |
| `mua` | mundang |
| `mul` | többszörös nyelvek |
| `mus` | krík |
| `mwl` | mirandéz |
| `mwr` | márvári |
| `my` | burmai |
| `mye` | myene |
| `myv` | erzjány |
| `mzn` | mázanderáni |
| `na` | naurui |
| `nan` | min nan kínai |
| `nap` | nápolyi |
| `naq` | nama |
| `nb` | norvég (bokmål) |
| `nd` | északi ndebele |
| `nds` | alsónémet |
| `nds_NL` | alsószász |
| `ne` | nepáli |
| `new` | nevari |
| `ng` | ndonga |
| `nia` | nias |
| `niu` | niuei |
| `nl` | holland |
| `nl_BE` | flamand |
| `nmg` | ngumba |
| `nn` | norvég (nynorsk) |
| `nnh` | ngiemboon |
| `no` | norvég |
| `nog` | nogaj |
| `non` | óskandináv |
| `nqo` | n’kó |
| `nr` | déli ndebele |
| `nso` | északi szeszotó |
| `nus` | nuer |
| `nv` | navahó |
| `nwc` | klasszikus newari |
| `ny` | nyandzsa |
| `nym` | nyamvézi |
| `nyn` | nyankole |
| `nyo` | nyoró |
| `nzi` | nzima |
| `oc` | okszitán |
| `oj` | ojibva |
| `om` | oromo |
| `or` | odia |
| `os` | oszét |
| `osa` | osage |
| `ota` | ottomán török |
| `pa` | pandzsábi |
| `pag` | pangaszinan |
| `pal` | pahlavi |
| `pam` | pampangan |
| `pap` | papiamento |
| `pau` | palaui |
| `pcm` | nigériai pidgin |
| `peo` | óperzsa |
| `phn` | főniciai |
| `pi` | pali |
| `pl` | lengyel |
| `pon` | pohnpei |
| `prg` | porosz |
| `pro` | óprovánszi |
| `ps` | pastu |
| `pt` | portugál |
| `pt_BR` | brazíliai portugál |
| `pt_PT` | európai portugál |
| `qu` | kecsua |
| `quc` | kicse |
| `raj` | radzsasztáni |
| `rap` | rapanui |
| `rar` | rarotongai |
| `rm` | rétoromán |
| `rn` | kirundi |
| `ro` | román |
| `ro_MD` | moldvai |
| `rof` | rombo |
| `rom` | roma |
| `root` | ősi |
| `ru` | orosz |
| `rup` | aromán |
| `rw` | kinyarvanda |
| `rwk` | rwo |
| `sa` | szanszkrit |
| `sad` | szandave |
| `sah` | szaha |
| `sam` | szamaritánus arámi |
| `saq` | szamburu |
| `sas` | sasak |
| `sat` | szantáli |
| `sba` | ngambay |
| `sbp` | szangu |
| `sc` | szardíniai |
| `scn` | szicíliai |
| `sco` | skót |
| `sd` | szindhi |
| `sdh` | dél-kurd |
| `se` | északi számi |
| `see` | szeneka |
| `seh` | szena |
| `sel` | szölkup |
| `ses` | kojra-szenni |
| `sg` | szangó |
| `sga` | óír |
| `sh` | szerbhorvát |
| `shi` | tachelhit |
| `shn` | san |
| `shu` | csádi arab |
| `si` | szingaléz |
| `sid` | szidamó |
| `sk` | szlovák |
| `sl` | szlovén |
| `sm` | szamoai |
| `sma` | déli számi |
| `smj` | lulei számi |
| `smn` | inari számi |
| `sms` | kolta számi |
| `sn` | sona |
| `snk` | szoninke |
| `so` | szomáli |
| `sog` | sogdien |
| `sq` | albán |
| `sr` | szerb |
| `srn` | szranai tongó |
| `srr` | szerer |
| `ss` | sziszuati |
| `ssy` | szahó |
| `st` | déli szeszotó |
| `su` | szundanéz |
| `suk` | szukuma |
| `sus` | szuszu |
| `sux` | sumér |
| `sv` | svéd |
| `sw` | szuahéli |
| `sw_CD` | kongói szuahéli |
| `swb` | comorei |
| `syc` | klasszikus szír |
| `syr` | szír |
| `ta` | tamil |
| `te` | telugu |
| `tem` | temne |
| `teo` | teszó |
| `ter` | terenó |
| `tet` | tetum |
| `tg` | tadzsik |
| `th` | thai |
| `ti` | tigrinya |
| `tig` | tigré |
| `tiv` | tiv |
| `tk` | türkmén |
| `tkl` | tokelaui |
| `tl` | tagalog |
| `tlh` | klingon |
| `tli` | tlingit |
| `tmh` | tamasek |
| `tn` | szecsuáni |
| `to` | tongai |
| `tog` | nyugati nyasza |
| `tpi` | tok pisin |
| `tr` | török |
| `trv` | tarokó |
| `ts` | conga |
| `tsi` | csimsiáni |
| `tt` | tatár |
| `tum` | tumbuka |
| `tvl` | tuvalu |
| `tw` | twi |
| `twq` | szavák |
| `ty` | tahiti |
| `tyv` | tuvai |
| `tzm` | közép-atlaszi tamazigt |
| `udm` | udmurt |
| `ug` | ujgur |
| `uga` | ugariti |
| `uk` | ukrán |
| `umb` | umbundu |
| `und` | ismeretlen nyelv |
| `ur` | urdu |
| `uz` | üzbég |
| `vai` | vai |
| `ve` | venda |
| `vi` | vietnami |
| `vo` | volapük |
| `vot` | votják |
| `vun` | vunjo |
| `wa` | vallon |
| `wae` | walser |
| `wal` | valamo |
| `war` | varaó |
| `was` | vasó |
| `wbp` | warlpiri |
| `wo` | volof |
| `wuu` | wu kínai |
| `xal` | kalmük |
| `xh` | xhosza |
| `xog` | szoga |
| `yao` | jaó |
| `yap` | japi |
| `yav` | jangben |
| `ybb` | jemba |
| `yi` | jiddis |
| `yo` | joruba |
| `yue` | kantoni |
| `za` | zsuang |
| `zap` | zapoték |
| `zbl` | Bliss jelképrendszer |
| `zen` | zenaga |
| `zgh` | marokkói tamazight |
| `zh` | kínai |
| `zh_Hans` | egyszerűsített kínai |
| `zh_Hant` | hagyományos kínai |
| `zu` | zulu |
| `zun` | zuni |
| `zxx` | nincs nyelvészeti tartalom |
| `zza` | zaza |
### Script names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `Arab` | Arab |
| `Arab` | Perzsa-arab |
| `Armi` | Birodalmi arámi |
| `Armn` | Örmény |
| `Avst` | Avesztán |
| `Bali` | Balinéz |
| `Batk` | Batak |
| `Beng` | Bengáli |
| `Blis` | Bliss jelképrendszer |
| `Bopo` | Bopomofo |
| `Brah` | Brámi |
| `Brai` | Vakírás |
| `Bugi` | Buginéz |
| `Buhd` | Buhid |
| `Cakm` | Csakma |
| `Cans` | Egyesített kanadai őslakos jelek |
| `Cari` | Kari |
| `Cham` | Csám |
| `Cher` | Cseroki |
| `Copt` | Kopt |
| `Cprt` | Ciprusi |
| `Cyrl` | Cirill |
| `Cyrs` | Óegyházi szláv cirill |
| `Deva` | Devanagári |
| `Dsrt` | Deseret |
| `Egyd` | Egyiptomi demotikus |
| `Egyh` | Egyiptomi hieratikus |
| `Egyp` | Egyiptomi hieroglifák |
| `Ethi` | Etióp |
| `Geok` | Grúz kucsuri |
| `Geor` | Grúz |
| `Glag` | Glagolitikus |
| `Goth` | Gót |
| `Grek` | Görög |
| `Gujr` | Gudzsaráti |
| `Guru` | Gurmuki |
| `Hanb` | Hanb |
| `Hang` | Hangul |
| `Hani` | Han |
| `Hano` | Hanunoo |
| `Hans` | Egyszerűsített |
| `Hans` | Egyszerűsített kínai |
| `Hant` | Hagyományos |
| `Hant` | Hagyományos kínai |
| `Hebr` | Héber |
| `Hira` | Hiragana |
| `Hmng` | Pahawh hmong |
| `Hrkt` | Katakana vagy hiragana |
| `Hung` | Ómagyar |
| `Inds` | Indus |
| `Ital` | Régi olasz |
| `Jamo` | Jamo |
| `Java` | Jávai |
| `Jpan` | Japán |
| `Kali` | Kajah li |
| `Kana` | Katakana |
| `Khar` | Kharoshthi |
| `Khmr` | Khmer |
| `Knda` | Kannada |
| `Kore` | Koreai |
| `Kthi` | Kaithi |
| `Lana` | Lanna |
| `Laoo` | Lao |
| `Latf` | Fraktur latin |
| `Latg` | Gael latin |
| `Latn` | Latin |
| `Lepc` | Lepcha |
| `Limb` | Limbu |
| `Lina` | Lineáris A |
| `Linb` | Lineáris B |
| `Lyci` | Líciai |
| `Lydi` | Lídiai |
| `Mand` | Mandai |
| `Mani` | Manicheus |
| `Maya` | Maja hieroglifák |
| `Mero` | Meroitikus |
| `Mlym` | Malajálam |
| `Mong` | Mongol |
| `Moon` | Moon |
| `Mtei` | Meitei mayek |
| `Mymr` | Burmai |
| `Nkoo` | N’ko |
| `Ogam` | Ogham |
| `Olck` | Ol chiki |
| `Orkh` | Orhon |
| `Orya` | Oriya |
| `Osma` | Oszmán |
| `Perm` | Ópermikus |
| `Phag` | Phags-pa |
| `Phli` | Felriatos pahlavi |
| `Phlp` | Psalter pahlavi |
| `Phlv` | Könyv pahlavi |
| `Phnx` | Főniciai |
| `Plrd` | Pollard fonetikus |
| `Prti` | Feliratos parthian |
| `Rjng` | Redzsang |
| `Roro` | Rongorongo |
| `Runr` | Runikus |
| `Samr` | Szamaritán |
| `Sara` | Szarati |
| `Saur` | Szaurastra |
| `Sgnw` | Jelírás |
| `Shaw` | Shaw ábécé |
| `Sinh` | Szingaléz |
| `Sund` | Szundanéz |
| `Sylo` | Sylheti nagári |
| `Syrc` | Szíriai |
| `Syre` | Estrangelo szíriai |
| `Syrj` | Nyugat-szíriai |
| `Syrn` | Kelet-szíriai |
| `Tagb` | Tagbanwa |
| `Tale` | Tai Le |
| `Talu` | Új tai lue |
| `Taml` | Tamil |
| `Tavt` | Tai viet |
| `Telu` | Telugu |
| `Teng` | Tengwar |
| `Tfng` | Berber |
| `Tglg` | Tagalog |
| `Thaa` | Thaana |
| `Thai` | Thai |
| `Tibt` | Tibeti |
| `Ugar` | Ugari |
| `Vaii` | Vai |
| `Visp` | Látható beszéd |
| `Xpeo` | Óperzsa |
| `Xsux` | Ékírásos suméro-akkád |
| `Yiii` | Ji |
| `Zinh` | Származtatott |
| `Zmth` | Matematikai jelrendszer |
| `Zsye` | Emoji |
| `Zsym` | Szimbólum |
| `Zxxx` | Íratlan nyelvek kódja |
| `Zyyy` | Meghatározatlan |
| `Zzzz` | Ismeretlen írásrendszer |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `001` | Világ |
| `002` | Afrika |
| `003` | Észak-Amerika |
| `005` | Dél-Amerika |
| `009` | Óceánia |
| `011` | Nyugat-Afrika |
| `013` | Közép-Amerika |
| `014` | Kelet-Afrika |
| `015` | Észak-Afrika |
| `017` | Közép-Afrika |
| `018` | Afrika déli része |
| `019` | Amerika |
| `021` | Amerika északi része |
| `029` | Karib-térség |
| `030` | Kelet-Ázsia |
| `034` | Dél-Ázsia |
| `035` | Délkelet-Ázsia |
| `039` | Dél-Európa |
| `053` | Ausztrálázsia |
| `054` | Melanézia |
| `057` | Mikronéziai régió |
| `061` | Polinézia |
| `142` | Ázsia |
| `143` | Közép-Ázsia |
| `145` | Nyugat-Ázsia |
| `150` | Európa |
| `151` | Kelet-Európa |
| `154` | Észak-Európa |
| `155` | Nyugat-Európa |
| `202` | Szubszaharai Afrika |
| `419` | Latin-Amerika |
| `AC` | Ascension-sziget |
| `AD` | Andorra |
| `AE` | Egyesült Arab Emírségek |
| `AF` | Afganisztán |
| `AG` | Antigua és Barbuda |
| `AI` | Anguilla |
| `AL` | Albánia |
| `AM` | Örményország |
| `AO` | Angola |
| `AQ` | Antarktisz |
| `AR` | Argentína |
| `AS` | Amerikai Szamoa |
| `AT` | Ausztria |
| `AU` | Ausztrália |
| `AW` | Aruba |
| `AX` | Åland-szigetek |
| `AZ` | Azerbajdzsán |
| `BA` | Bosznia-Hercegovina |
| `BB` | Barbados |
| `BD` | Banglades |
| `BE` | Belgium |
| `BF` | Burkina Faso |
| `BG` | Bulgária |
| `BH` | Bahrein |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | Saint-Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Bolívia |
| `BQ` | Holland Karib-térség |
| `BR` | Brazília |
| `BS` | Bahama-szigetek |
| `BT` | Bhután |
| `BV` | Bouvet-sziget |
| `BW` | Botswana |
| `BY` | Belarusz |
| `BZ` | Belize |
| `CA` | Kanada |
| `CC` | Kókusz (Keeling)-szigetek |
| `CD` | Kongó - Kinshasa |
| `CD` | Kongó (KDK) |
| `CF` | Közép-afrikai Köztársaság |
| `CG` | Kongó - Brazzaville |
| `CG` | Kongó (Köztársaság) |
| `CH` | Svájc |
| `CI` | Elefántcsontpart |
| `CI` | CI |
| `CK` | Cook-szigetek |
| `CL` | Chile |
| `CM` | Kamerun |
| `CN` | Kína |
| `CO` | Kolumbia |
| `CP` | Clipperton-sziget |
| `CR` | Costa Rica |
| `CU` | Kuba |
| `CV` | Zöld-foki Köztársaság |
| `CW` | Curaçao |
| `CX` | Karácsony-sziget |
| `CY` | Ciprus |
| `CZ` | Csehország |
| `CZ` | Cseh Köztársaság |
| `DE` | Németország |
| `DG` | Diego Garcia |
| `DJ` | Dzsibuti |
| `DK` | Dánia |
| `DM` | Dominika |
| `DO` | Dominikai Köztársaság |
| `DZ` | Algéria |
| `EA` | Ceuta és Melilla |
| `EC` | Ecuador |
| `EE` | Észtország |
| `EG` | Egyiptom |
| `EH` | Nyugat-Szahara |
| `ER` | Eritrea |
| `ES` | Spanyolország |
| `ET` | Etiópia |
| `EU` | Európai Unió |
| `EZ` | Eurózóna |
| `FI` | Finnország |
| `FJ` | Fidzsi |
| `FK` | Falkland-szigetek |
| `FK` | Falkland-szigetek (Malvin-szigetek) |
| `FM` | Mikronézia |
| `FO` | Feröer-szigetek |
| `FR` | Franciaország |
| `GA` | Gabon |
| `GB` | Egyesült Királyság |
| `GB` | UK |
| `GD` | Grenada |
| `GE` | Grúzia |
| `GF` | Francia Guyana |
| `GG` | Guernsey |
| `GH` | Ghána |
| `GI` | Gibraltár |
| `GL` | Grönland |
| `GM` | Gambia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Egyenlítői-Guinea |
| `GR` | Görögország |
| `GS` | Déli-Georgia és Déli-Sandwich-szigetek |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Bissau-Guinea |
| `GY` | Guyana |
| `HK` | Hongkong KKT |
| `HK` | Hongkong |
| `HM` | Heard-sziget és McDonald-szigetek |
| `HN` | Honduras |
| `HR` | Horvátország |
| `HT` | Haiti |
| `HU` | Magyarország |
| `IC` | Kanári-szigetek |
| `ID` | Indonézia |
| `IE` | Írország |
| `IL` | Izrael |
| `IM` | Man-sziget |
| `IN` | India |
| `IO` | Brit Indiai-óceáni Terület |
| `IQ` | Irak |
| `IR` | Irán |
| `IS` | Izland |
| `IT` | Olaszország |
| `JE` | Jersey |
| `JM` | Jamaica |
| `JO` | Jordánia |
| `JP` | Japán |
| `KE` | Kenya |
| `KG` | Kirgizisztán |
| `KH` | Kambodzsa |
| `KI` | Kiribati |
| `KM` | Comore-szigetek |
| `KN` | Saint Kitts és Nevis |
| `KP` | Észak-Korea |
| `KR` | Dél-Korea |
| `KW` | Kuvait |
| `KY` | Kajmán-szigetek |
| `KZ` | Kazahsztán |
| `LA` | Laosz |
| `LB` | Libanon |
| `LC` | Saint Lucia |
| `LI` | Liechtenstein |
| `LK` | Srí Lanka |
| `LR` | Libéria |
| `LS` | Lesotho |
| `LT` | Litvánia |
| `LU` | Luxemburg |
| `LV` | Lettország |
| `LY` | Líbia |
| `MA` | Marokkó |
| `MC` | Monaco |
| `MD` | Moldova |
| `ME` | Montenegró |
| `MF` | Saint Martin |
| `MG` | Madagaszkár |
| `MH` | Marshall-szigetek |
| `MK` | Macedónia |
| `MK` | Macedónia (MVJK) |
| `ML` | Mali |
| `MM` | Mianmar (Burma) |
| `MN` | Mongólia |
| `MO` | Makaó KKT |
| `MO` | Makaó |
| `MP` | Északi Mariana-szigetek |
| `MQ` | Martinique |
| `MR` | Mauritánia |
| `MS` | Montserrat |
| `MT` | Málta |
| `MU` | Mauritius |
| `MV` | Maldív-szigetek |
| `MW` | Malawi |
| `MX` | Mexikó |
| `MY` | Malajzia |
| `MZ` | Mozambik |
| `NA` | Namíbia |
| `NC` | Új-Kaledónia |
| `NE` | Niger |
| `NF` | Norfolk-sziget |
| `NG` | Nigéria |
| `NI` | Nicaragua |
| `NL` | Hollandia |
| `NO` | Norvégia |
| `NP` | Nepál |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | Új-Zéland |
| `OM` | Omán |
| `PA` | Panama |
| `PE` | Peru |
| `PF` | Francia Polinézia |
| `PG` | Pápua Új-Guinea |
| `PH` | Fülöp-szigetek |
| `PK` | Pakisztán |
| `PL` | Lengyelország |
| `PM` | Saint-Pierre és Miquelon |
| `PN` | Pitcairn-szigetek |
| `PR` | Puerto Rico |
| `PS` | Palesztin Terület |
| `PS` | Palesztina |
| `PT` | Portugália |
| `PW` | Palau |
| `PY` | Paraguay |
| `QA` | Katar |
| `QO` | Külső-Óceánia |
| `RE` | Réunion |
| `RO` | Románia |
| `RS` | Szerbia |
| `RU` | Oroszország |
| `RW` | Ruanda |
| `SA` | Szaúd-Arábia |
| `SB` | Salamon-szigetek |
| `SC` | Seychelle-szigetek |
| `SD` | Szudán |
| `SE` | Svédország |
| `SG` | Szingapúr |
| `SH` | Szent Ilona |
| `SI` | Szlovénia |
| `SJ` | Svalbard és Jan Mayen |
| `SK` | Szlovákia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Szenegál |
| `SO` | Szomália |
| `SR` | Suriname |
| `SS` | Dél-Szudán |
| `ST` | São Tomé és Príncipe |
| `SV` | Salvador |
| `SX` | Sint Maarten |
| `SY` | Szíria |
| `SZ` | Szváziföld |
| `TA` | Tristan da Cunha |
| `TC` | Turks- és Caicos-szigetek |
| `TD` | Csád |
| `TF` | Francia Déli Területek |
| `TG` | Togo |
| `TH` | Thaiföld |
| `TJ` | Tádzsikisztán |
| `TK` | Tokelau |
| `TL` | Kelet-Timor |
| `TL` | Timor-Leste |
| `TM` | Türkmenisztán |
| `TN` | Tunézia |
| `TO` | Tonga |
| `TR` | Törökország |
| `TT` | Trinidad és Tobago |
| `TV` | Tuvalu |
| `TW` | Tajvan |
| `TZ` | Tanzánia |
| `UA` | Ukrajna |
| `UG` | Uganda |
| `UM` | Az USA lakatlan külbirtokai |
| `UN` | Egyesült Nemzetek Szervezete |
| `UN` | ENSZ |
| `US` | Egyesült Államok |
| `US` | USA |
| `UY` | Uruguay |
| `UZ` | Üzbegisztán |
| `VA` | Vatikán |
| `VC` | Saint Vincent és a Grenadine-szigetek |
| `VE` | Venezuela |
| `VG` | Brit Virgin-szigetek |
| `VI` | Amerikai Virgin-szigetek |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis és Futuna |
| `WS` | Szamoa |
| `XK` | Koszovó |
| `YE` | Jemen |
| `YT` | Mayotte |
| `ZA` | Dél-afrikai Köztársaság |
| `ZM` | Zambia |
| `ZW` | Zimbabwe |
| `ZZ` | Ismeretlen körzet |
### Locale variant names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `1901` | Hagyományos német helyesírás |
| `1994` | Szabványosított reziján helyesírás |
| `1996` | 1996-os német helyesírás |
| `1606NICT` | Késői közép francia 1606-ig |
| `1694ACAD` | Korai modern francia |
| `1959ACAD` | Akadémiai |
| `ALALC97` | ALA-LC romanizáció, 1997-es kiadás |
| `ALUKU` | Aluku dialektus |
| `AREVELA` | Keleti örmény |
| `AREVMDA` | Nyugati örmény |
| `BAKU1926` | Egyesített türkic latin ábécé |
| `BAUDDHA` | Bauddha |
| `BISCAYAN` | Biszkajan |
| `BISKE` | San Giorgo/Bila tájszólás |
| `BOONT` | Boontling |
| `FONIPA` | IPA fonetika |
| `FONUPA` | UPA fonetika |
| `FONXSAMP` | Fonxsamp |
| `HEPBURN` | Hepburn romanizáció |
| `HOGNORSK` | Hongorszk |
| `ITIHASA` | Itihasa |
| `JAUER` | Jauer |
| `JYUTPING` | Jyutping |
| `KKCOR` | Meghatározatlan helyesírás |
| `LAUKIKA` | Laukika |
| `LIPAW` | Reziján lipovaz tájszólás |
| `LUNA1918` | Luna1918 |
| `MONOTON` | Monoton |
| `NDYUKA` | Ndyuka dialektus |
| `NEDIS` | Natisone dialektus |
| `NJIVA` | Gniva/Njiva tájszólás |
| `OSOJS` | Oseacco/Osojane tájszólás |
| `PAMAKA` | Pamaka dialektus |
| `PETR1708` | Petr1708 |
| `PINYIN` | pinjin átírás |
| `POLYTON` | Politonikus |
| `POSIX` | Számítógép |
| `PUTER` | Puter |
| `REVISED` | Átdolgozott helyesírás |
| `ROZAJ` | Reziján |
| `RUMGR` | Rumgr |
| `SAAHO` | Saho |
| `SCOTLAND` | Skót szabványos angol |
| `SCOUSE` | Scouse |
| `SOLBA` | Stolvizza/Solbica tájszólás |
| `SURMIRAN` | Surmiran |
| `SURSILV` | Sursilv |
| `SUTSILV` | Sutsilv |
| `TARASK` | Taraskijevica helyesírás |
| `UCCOR` | Egyesített helyesírás |
| `UCRCOR` | Egyesített átdolgozott helyesírás |
| `ULSTER` | Ulster |
| `VAIDIKA` | Vaidika |
| `VALENCIA` | Valencia |
| `VALLADER` | Vallader |
| `WADEGILE` | Wade-Giles átírás |
#### Keys (system names)
| key | Name |
| -------- | ---- |
| `calendar` | Naptár |
| `cf` | Pénznemformátum |
| `colAlternate` | Szimbólumokat figyelmen kívül hagyó rendezés |
| `colBackwards` | Ékezetek fordított rendezése |
| `colCaseFirst` | Rendezés nagy- vagy kisbetűk szerint |
| `colCaseLevel` | Kisbetű-nagybetű érzékeny rendezés |
| `collation` | Rendezési sorrend |
| `colNormalization` | Normalizált rendezés |
| `colNumeric` | Numerikus rendezés |
| `colStrength` | Rendezés erőssége |
| `currency` | Pénznem |
| `hc` | Óraformátum (12 – 24) |
| `lb` | Sortörés stílusa |
| `ms` | Mértékegységrendszer |
| `numbers` | Számok |
| `timezone` | Időzóna |
| `va` | Földrajzi helyvariáns |
| `x` | Privát használatra |
### Types (of systems)
| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | Buddhista naptár |
| `chinesecalendar` | Kínai naptár |
| `copticcalendar` | Kopt naptár |
| `dangicalendar` | Dangi naptár |
| `ethiopiccalendar` | Etióp naptár |
| `ethiopic-amete-alemcalendar` | Etióp amete alem naptár |
| `gregoriancalendar` | Gergely-naptár |
| `hebrewcalendar` | Héber naptár |
| `indiancalendar` | Indiai nemzeti naptár |
| `islamiccalendar` | Iszlám naptár |
| `islamic-civilcalendar` | Iszlám civil naptár |
| `islamic-umalquracalendar` | Iszlám Umm al-Qura naptár |
| `iso8601calendar` | ISO-8601 naptár |
| `japanesecalendar` | Japán naptár |
| `persiancalendar` | Perzsa naptár |
| `roccalendar` | Kínai köztársasági naptár |
| `accountcf` | Könyvelési pénznemformátum |
| `standardcf` | Normál pénznemformátum |
| `non-ignorablecolAlternate` | Szimbólumok rendezése |
| `shiftedcolAlternate` | Rendezés szimbólumok figyelmen kívül hagyásával |
| `nocolBackwards` | Ékezetek normál rendezése |
| `yescolBackwards` | Ékezetek szerinti fordított rendezés |
| `lowercolCaseFirst` | Kisbetűs szavak rendezése előre |
| `nocolCaseFirst` | Kisbetűs-nagybetűs szavak normál rendezése |
| `uppercolCaseFirst` | Nagybetűs szavak rendezése előre |
| `nocolCaseLevel` | Kis- és nagybetűket meg nem különböztető rendezés |
| `yescolCaseLevel` | Rendezés kisbetű-nagybetű szerint |
| `big5hancollation` | Hagyományos kínai sorrend - Big5 |
| `compatcollation` | Előző rendezési sorrend a kompatibilitás érdekében |
| `dictionarycollation` | Szótári rendezési sorrend |
| `ducetcollation` | Alapértelmezett Unicode rendezési sorrend |
| `eorcollation` | Európai rendezési szabályok |
| `gb2312hancollation` | Egyszerűsített kínai sorrend - GB2312 |
| `phonebookcollation` | Telefonkönyv sorrend |
| `phoneticcollation` | Fonetikus rendezési sorrend |
| `pinyincollation` | Pinyin sorrend |
| `reformedcollation` | Átalakított rendezési elv |
| `searchcollation` | Általános célú keresés |
| `searchjlcollation` | Keresés hangul kezdő mássalhangzó szerint |
| `standardcollation` | Normál rendezési sorrend |
| `strokecollation` | Vonássorrend |
| `traditionalcollation` | Hagyományos |
| `unihancollation` | Szótővonás rendezési sorrend |
| `nocolNormalization` | Rendezés normalizálás nélkül |
| `yescolNormalization` | Unicode szerinti normalizált rendezés |
| `nocolNumeric` | Számjegyek egyedi rendezése |
| `yescolNumeric` | Számjegyek numerikus rendezése |
| `identicalcolStrength` | Összes rendezése |
| `primarycolStrength` | Csak az alapbetűk rendezése |
| `quaternarycolStrength` | Ékezetek/kisbetű-nagybetű/szélesség/kanák rendezése |
| `secondarycolStrength` | Ékezetek rendezése |
| `tertiarycolStrength` | Ékezetek/kisbetű-nagybetű/szélesség rendezése |
| `fwidthd0` | Teljes szélesség |
| `hwidthd0` | Fél szélesség |
| `npinyind0` | Szám |
| `h11hc` | 12 órás rendszer (0–11) |
| `h12hc` | 12 órás rendszer (0–12) |
| `h23hc` | 24 órás rendszer (0–23) |
| `h24hc` | 24 órás rendszer (0–24) |
| `looselb` | Tág stílusú sortörés |
| `normallb` | Normál stílusú sortörés |
| `strictlb` | Szűk stílusú sortörés |
| `bgnm0` | BGN |
| `ungegnm0` | UNGEGN |
| `metricms` | Méterrendszer |
| `uksystemms` | Angolszász mértékegységrendszer |
| `ussystemms` | Amerikai mértékegységrendszer |
| `arabnumbers` | Arab-indiai számjegyek |
| `arabextnumbers` | Kibővített arab-indiai számjegyek |
| `armnnumbers` | Örmény számok |
| `armnlownumbers` | Örmény kisbetűs számok |
| `bengnumbers` | Bengáli számjegyek |
| `devanumbers` | Dévanágari számjegyek |
| `ethinumbers` | Etióp számok |
| `financenumbers` | Pénzügyi számok |
| `fullwidenumbers` | Teljes szélességű számjegyek |
| `geornumbers` | Grúz számok |
| `greknumbers` | Görög számok |
| `greklownumbers` | Görög kisbetűs számok |
| `gujrnumbers` | Gudzsaráti számjegyek |
| `gurunumbers` | Gurmuki számjegyek |
| `hanidecnumbers` | Kínai tizedes számok |
| `hansnumbers` | Egyszerűsített kínai számok |
| `hansfinnumbers` | Egyszerűsített kínai pénzügyi számok |
| `hantnumbers` | Hagyományos kínai számok |
| `hantfinnumbers` | Hagyományos kínai pénzügyi számok |
| `hebrnumbers` | Héber számok |
| `jpannumbers` | Japán számok |
| `jpanfinnumbers` | Japán pénzügyi számok |
| `khmrnumbers` | Khmer számjegyek |
| `kndanumbers` | Kannada számjegyek |
| `laoonumbers` | Lao számjegyek |
| `latnnumbers` | Nyugati számjegyek |
| `mlymnumbers` | Malajálam számjegyek |
| `mongnumbers` | Mongol számjegyek |
| `mymrnumbers` | Mianmari számjegyek |
| `nativenumbers` | Natív számjegyek |
| `oryanumbers` | Orija számjegyek |
| `romannumbers` | Római számok |
| `romanlownumbers` | Római kisbetűs számok |
| `tamlnumbers` | Tamil hagyományos számok |
| `tamldecnumbers` | Tamil számjegyek |
| `telunumbers` | Telugu számjegyek |
| `thainumbers` | Thai számjegyek |
| `tibtnumbers` | Tibeti számjegyek |
| `traditionalnumbers` | Hagyományos számok |
| `vaiinumbers` | Vai számjegyek |
| `metric` | metrikus |
| `UK` | angol |
| `US` | amerikai |
### Code patterns
Nyelv: {0}Írásrendszer: {0}Régió: {0}
### Character processing for computer systems
| main characters | `[a á b c {cs} {ccs} d {dz} {ddz} {dzs} {ddzs} e é f g {gy} {ggy} h i í j k l {ly} {lly} m n {ny} {nny} o ó ö ő p r s {sz} {ssz} t {ty} {tty} u ú ü ű v z {zs} {zzs}]` |
| auxiliary characters | `[à ă â å ä ã ā æ ç è ĕ ê ë ē ì ĭ î ï ī ñ ò ŏ ô ø ō œ q ù ŭ û ū w x y ÿ]` |
| index characters | `[A Á B C {CS} D {DZ} {DZS} E É F G {GY} H I Í J K L {LY} M N {NY} O Ó Ö Ő P Q R S {SZ} T {TY} U Ú Ü Ű V W X Y Z {ZS}]` |
| numbers characters | `[  \- , % ‰ + 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- – , ; \: ! ? . … ' ’ " ” „ « » ( ) \[ \] \{ \} ⟨ ⟩ § @ * / \& # ~ ⁒]` |
final ellipsis: `{0}…`
initial ellipsis: `…{0}`
medial ellipsis: `{0}…{1}`
word-final ellipsis: `{0}…`
word-initial ellipsis: `…{0}`
word-medial ellipsis: `{0} … {1}`
More information characters: `?`
Delimiters:
Quotation start character: „
Quotation end character: ”
Secondary yquotation start character: »
Secondary quotation end character: «
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
#### coptic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Thot |
| month 2 | Paophi |
| month 3 | Athür |
| month 4 | Koiak |
| month 5 | Tübi |
| month 6 | Mehir |
| month 7 | Phamenóth |
| month 8 | Pharmuthi |
| month 9 | Pakhónsz |
| month 10 | Pauni |
| month 11 | Epip |
| month 12 | Meszoré |
| month 13 | Pi Kogi Enavot |
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
| month 1 | Thot |
| month 2 | Paophi |
| month 3 | Athür |
| month 4 | Koiak |
| month 5 | Tübi |
| month 6 | Mehir |
| month 7 | Phamenóth |
| month 8 | Pharmuthi |
| month 9 | Pakhónsz |
| month 10 | Pauni |
| month 11 | Epip |
| month 12 | Meszoré |
| month 13 | Pi Kogi Enavot |
| month 1 | Thot |
| month 2 | Paophi |
| month 3 | Athür |
| month 4 | Koiak |
| month 5 | Tübi |
| month 6 | Mehir |
| month 7 | Phamenóth |
| month 8 | Pharmuthi |
| month 9 | Pakhónsz |
| month 10 | Pauni |
| month 11 | Epip |
| month 12 | Meszoré |
| month 13 | Pi Kogi Enavot |
| month 1 | Thot |
| month 2 | Paophi |
| month 3 | Athür |
| month 4 | Koiak |
| month 5 | Tübi |
| month 6 | Mehir |
| month 7 | Phamenóth |
| month 8 | Pharmuthi |
| month 9 | Pakhónsz |
| month 10 | Pauni |
| month 11 | Epip |
| month 12 | Meszoré |
| month 13 | Pi Kogi Enavot |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
#### ethiopic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Meskerem |
| month 2 | Tekemt |
| month 3 | Hedar |
| month 4 | Tahsas |
| month 5 | Ter |
| month 6 | Yekatit |
| month 7 | Megabit |
| month 8 | Miazia |
| month 9 | Genbot |
| month 10 | Sene |
| month 11 | Hamle |
| month 12 | Nehasse |
| month 13 | Pagumen |
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
| month 1 | Meskerem |
| month 2 | Tekemt |
| month 3 | Hedar |
| month 4 | Tahsas |
| month 5 | Ter |
| month 6 | Yekatit |
| month 7 | Megabit |
| month 8 | Miazia |
| month 9 | Genbot |
| month 10 | Sene |
| month 11 | Hamle |
| month 12 | Nehasse |
| month 13 | Pagumen |
| month 1 | Meskerem |
| month 2 | Tekemt |
| month 3 | Hedar |
| month 4 | Tahsas |
| month 5 | Ter |
| month 6 | Yekatit |
| month 7 | Megabit |
| month 8 | Miazia |
| month 9 | Genbot |
| month 10 | Sene |
| month 11 | Hamle |
| month 12 | Nehasse |
| month 13 | Pagumen |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
| era | ERA0 |
| era | ERA1 |
#### generic calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `G y. MMMM d., EEEE` |
| date format | `G y. MMMM d.` |
| date format | `G y. MMM d.` |
| date format | `GGGGG y. M. d.` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `B h` |
| date format `Bhm` | `B h:mm` |
| date format `Bhms` | `B h:mm:ss` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E h:mm` |
| date format `EBhms` | `E h:mm:ss` |
| date format `Ed` | `d., E` |
| date format `Ehm` | `E h:mm` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y.` |
| date format `GyMMM` | `G y. MMM` |
| date format `GyMMMd` | `G y. MMM d.` |
| date format `GyMMMEd` | `G y. MMM d., E` |
| date format `h` | `a h` |
| date format `H` | `H` |
| date format `hm` | `a h:mm` |
| date format `Hm` | `H:mm` |
| date format `hms` | `a h:mm:ss` |
| date format `Hms` | `H:mm:ss` |
| date format `M` | `L` |
| date format `Md` | `M. d.` |
| date format `MEd` | `M. d., E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `MMM d., E` |
| date format `MMMMd` | `MMMM d.` |
| date format `ms` | `mm:ss` |
| date format `y` | `G y.` |
| date format `yyyy` | `G y.` |
| date format `yyyyM` | `G y. MM.` |
| date format `yyyyMd` | `G y. MM. dd.` |
| date format `yyyyMEd` | `G y. MM. dd., E` |
| date format `yyyyMMM` | `G y. MMM` |
| date format `yyyyMMMd` | `G y. MMM d.` |
| date format `yyyyMMMEd` | `G y. MMM d., E` |
| date format `yyyyMMMM` | `G y. MMMM` |
| date format `yyyyQQQ` | `G y. QQQ` |
| date format `yyyyQQQQ` | `G y. QQQQ` |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d.` |
| interval format `h` | `a h – a ha h–h` |
| interval format `H` | `H–H` |
| interval format `hm` | `a h:mm – a h:mma h:mm–h:mma h:mm–h:mm` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `a h:mm – a h:mm va h:mm–h:mm va h:mm–h:mm v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `a h – a h va h–h v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M.` |
| interval format `Md` | `MM. dd–dd.MM. dd. – MM. dd.` |
| interval format `MEd` | `MM. dd., E – MM. dd., EMM. dd., E – MM. dd., E` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `MMM d–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMM d., E – d., EMMM d., E – MMM d., E` |
| interval format `y` | `G y–y.` |
| interval format `yM` | `G y. MM–MM.G y. MM. – y. MM.` |
| interval format `yMd` | `G y. MM. dd–dd.G y. MM. dd. – MM. dd.G y. MM. dd. – y. MM. dd.` |
| interval format `yMEd` | `G y. MM. dd., E – dd., EG y. MM. dd., E – MM. dd., EG y. MM. dd., E – y. MM. dd., E` |
| interval format `yMMM` | `G y. MMM–MMMG y. MMM – y. MMM` |
| interval format `yMMMd` | `G y. MMM d–d.G y. MMM d. – MMM d.G y. MMM d. – y. MMM d.` |
| interval format `yMMMEd` | `G y. MMM d., E – MMM d., EG y. MMM d., E – MMM d., EG y. MMM d., E – y. MMM d., E` |
| interval format `yMMMM` | `G y. MMMM–MMMMG y. MMMM – y. MMMM` |
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | jan. |
| month 2 | febr. |
| month 3 | márc. |
| month 4 | ápr. |
| month 5 | máj. |
| month 6 | jún. |
| month 7 | júl. |
| month 8 | aug. |
| month 9 | szept. |
| month 10 | okt. |
| month 11 | nov. |
| month 12 | dec. |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | Á |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | Sz |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| month 1 | január |
| month 2 | február |
| month 3 | március |
| month 4 | április |
| month 5 | május |
| month 6 | június |
| month 7 | július |
| month 8 | augusztus |
| month 9 | szeptember |
| month 10 | október |
| month 11 | november |
| month 12 | december |
| month 1 | jan. |
| month 2 | febr. |
| month 3 | márc. |
| month 4 | ápr. |
| month 5 | máj. |
| month 6 | jún. |
| month 7 | júl. |
| month 8 | aug. |
| month 9 | szept. |
| month 10 | okt. |
| month 11 | nov. |
| month 12 | dec. |
| month 1 | J |
| month 2 | F |
| month 3 | M |
| month 4 | Á |
| month 5 | M |
| month 6 | J |
| month 7 | J |
| month 8 | A |
| month 9 | Sz |
| month 10 | O |
| month 11 | N |
| month 12 | D |
| month 1 | január |
| month 2 | február |
| month 3 | március |
| month 4 | április |
| month 5 | május |
| month 6 | június |
| month 7 | július |
| month 8 | augusztus |
| month 9 | szeptember |
| month 10 | október |
| month 11 | november |
| month 12 | december |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sz |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Sz |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | vasárnap |
| (week)day mon | hétfő |
| (week)day tue | kedd |
| (week)day wed | szerda |
| (week)day thu | csütörtök |
| (week)day fri | péntek |
| (week)day sat | szombat |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sz |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Sz |
| (week)day sun | V |
| (week)day mon | H |
| (week)day tue | K |
| (week)day wed | Sze |
| (week)day thu | Cs |
| (week)day fri | P |
| (week)day sat | Szo |
| (week)day sun | vasárnap |
| (week)day mon | hétfő |
| (week)day tue | kedd |
| (week)day wed | szerda |
| (week)day thu | csütörtök |
| (week)day fri | péntek |
| (week)day sat | szombat |
| quarter 1 | I. n.év |
| quarter 2 | II. n.év |
| quarter 3 | III. n.év |
| quarter 4 | IV. n.év |
| quarter 1 | I. |
| quarter 2 | II. |
| quarter 3 | III. |
| quarter 4 | IV. |
| quarter 1 | I. negyedév |
| quarter 2 | II. negyedév |
| quarter 3 | III. negyedév |
| quarter 4 | IV. negyedév |
| quarter 1 | 1. n.év |
| quarter 2 | 2. n.év |
| quarter 3 | 3. n.év |
| quarter 4 | 4. n.év |
| quarter 1 | 1. |
| quarter 2 | 2. |
| quarter 3 | 3. |
| quarter 4 | 4. |
| quarter 1 | 1. negyedév |
| quarter 2 | 2. negyedév |
| quarter 3 | 3. negyedév |
| quarter 4 | 4. negyedév |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | délelőtt |
| period of day afternoon1 | délután |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | de. |
| period of day afternoon1 | du. |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| period of day midnight | éjfél |
| period of day am | de. |
| period of day noon | dél |
| period of day pm | du. |
| period of day morning1 | reggel |
| period of day morning2 | délelőtt |
| period of day afternoon1 | délután |
| period of day evening1 | este |
| period of day night1 | éjjel |
| period of day night2 | hajnal |
| era | Krisztus előtt |
| era | időszámításunk előtt |
| era | időszámításunk szerint |
| era | i. sz. |
| era | i. e. |
| era | i. sz. |
| era | ie. |
| era | isz. |
| date format | `y. MMMM d., EEEE` |
| date format | `y. MMMM d.` |
| date format | `y. MMM d.` |
| date format | `y. MM. dd.` |
| time format | `H:mm:ss zzzz` |
| time format | `H:mm:ss z` |
| time format | `H:mm:ss` |
| time format | `H:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `Bh` | `B h` |
| date format `Bhm` | `B h:mm` |
| date format `Bhms` | `B h:mm:ss` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `EBhm` | `E B h:mm` |
| date format `EBhms` | `E B h:mm:ss` |
| date format `Ed` | `d., E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y.` |
| date format `GyMMM` | `G y. MMM` |
| date format `GyMMMd` | `G y. MMM d.` |
| date format `GyMMMEd` | `G y. MMM d., E` |
| date format `h` | `a h` |
| date format `H` | `H` |
| date format `hm` | `a h:mm` |
| date format `Hm` | `H:mm` |
| date format `hms` | `a h:mm:ss` |
| date format `Hms` | `H:mm:ss` |
| date format `hmsv` | `a h:mm:ss v` |
| date format `Hmsv` | `HH:mm:ss v` |
| date format `hmv` | `a h:mm v` |
| date format `Hmv` | `HH:mm v` |
| date format `M` | `L` |
| date format `Md` | `M. d.` |
| date format `MEd` | `M. d., E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d.` |
| date format `MMMEd` | `MMM d., E` |
| date format `MMMMd` | `MMMM d.` |
| date format `MMMMW` | `MMM W. 'hete'` |
| date format `MMMMW` | `MMM W. 'hete'` |
| date format `mmss` | `mm:ss` |
| date format `ms` | `mm:ss` |
| date format `y` | `y.` |
| date format `yM` | `y. M.` |
| date format `yMd` | `y. MM. dd.` |
| date format `yMEd` | `y. MM. dd., E` |
| date format `yMMM` | `y. MMM` |
| date format `yMMMd` | `y. MMM d.` |
| date format `yMMMEd` | `y. MMM d., E` |
| date format `yMMMM` | `y. MMMM` |
| date format `yQQQ` | `y. QQQ` |
| date format `yQQQQ` | `y. QQQQ` |
| date format `yw` | `Y w. 'hete'` |
| date format `yw` | `Y w. 'hete'` |
| Timezone | {0} {1} |
| interval format fallback | `{0} – {1}` |
| interval format `d` | `d–d.` |
| interval format `h` | `a h – a ha h–h` |
| interval format `H` | `H–H` |
| interval format `hm` | `a h:mm – a h:mma h:mm–h:mma h:mm–h:mm` |
| interval format `Hm` | `H:mm–H:mmH:mm–H:mm` |
| interval format `hmv` | `a h:mm – a h:mm va h:mm–h:mm va h:mm–h:mm v` |
| interval format `Hmv` | `H:mm–H:mm vH:mm–H:mm v` |
| interval format `hv` | `a h – a h va h–h v` |
| interval format `Hv` | `H–H v` |
| interval format `M` | `M–M.` |
| interval format `Md` | `M. d–d.M. d. – M. d.` |
| interval format `MEd` | `M. dd., E – M. d., EM. d., E – M. d., E` |
| interval format `MMM` | `MMM–MMM` |
| interval format `MMMd` | `MMM d–d.MMM d. – MMM d.` |
| interval format `MMMEd` | `MMM d., E – d., EMMM d., E – MMM d., E` |
| interval format `y` | `y–y` |
| interval format `yM` | `y. MM–MM.y. MM. – y. MM.` |
| interval format `yMd` | `y. MM. dd–dd.y. MM. dd. – MM. dd.y. MM. dd. – y. MM. dd.` |
| interval format `yMEd` | `y. MM. dd., E – dd., Ey. MM. dd., E – MM. dd., Ey. MM. dd., E – y. MM. dd., E` |
| interval format `yMMM` | `y. MMM–MMMy. MMM – y. MMM` |
| interval format `yMMMd` | `y. MMM d–d.y. MMM d. – MMM d.y. MMM d. – y. MMM d.` |
| interval format `yMMMEd` | `y. MMM d., E – d., Ey. MMM d., E – MMM d., Ey. MMM d., E – y. MMM d., E` |
| interval format `yMMMM` | `y. MMMM–MMMMy. MMMM – y. MMMM` |
#### hebrew calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Tisri |
| month 2 | Hesván |
| month 3 | Kiszlév |
| month 4 | Tévész |
| month 5 | Svát |
| month 6 | Ádár I |
| month 7 | Ádár |
| month 7 | Ádár II |
| month 8 | Niszán |
| month 9 | Ijár |
| month 10 | Sziván |
| month 11 | Tamuz |
| month 12 | Áv |
| month 13 | Elul |
| month 1 | Tisri |
| month 2 | Hesván |
| month 3 | Kiszlév |
| month 4 | Tévész |
| month 5 | Svát |
| month 6 | Ádár I |
| month 7 | Ádár |
| month 7 | Ádár II |
| month 8 | Niszán |
| month 9 | Ijár |
| month 10 | Sziván |
| month 11 | Tamuz |
| month 12 | Áv |
| month 13 | Elul |
| month 1 | Tisri |
| month 2 | Hesván |
| month 3 | Kiszlév |
| month 4 | Tévész |
| month 5 | Svát |
| month 6 | Ádár I |
| month 7 | Ádár |
| month 7 | Ádár II |
| month 8 | Niszán |
| month 9 | Ijár |
| month 10 | Sziván |
| month 11 | Tamuz |
| month 12 | Áv |
| month 13 | Elul |
| month 1 | Tisri |
| month 2 | Hesván |
| month 3 | Kiszlév |
| month 4 | Tévész |
| month 5 | Svát |
| month 6 | Ádár I |
| month 7 | Ádár |
| month 7 | Ádár II |
| month 8 | Niszán |
| month 9 | Ijár |
| month 10 | Sziván |
| month 11 | Tamuz |
| month 12 | Áv |
| month 13 | Elul |
| era | TÉ |
| era | TÉ |
| era | TÉ |
#### indian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Chaitra |
| month 2 | Vaisakha |
| month 3 | Jyaistha |
| month 4 | Asadha |
| month 5 | Sravana |
| month 6 | Bhadra |
| month 7 | Asvina |
| month 8 | Kartika |
| month 9 | Agrahayana |
| month 10 | Pausa |
| month 11 | Magha |
| month 12 | Phalguna |
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
| month 1 | Chaitra |
| month 2 | Vaisakha |
| month 3 | Jyaistha |
| month 4 | Asadha |
| month 5 | Sravana |
| month 6 | Bhadra |
| month 7 | Asvina |
| month 8 | Kartika |
| month 9 | Agrahayana |
| month 10 | Pausa |
| month 11 | Magha |
| month 12 | Phalguna |
| month 1 | Chaitra |
| month 2 | Vaisakha |
| month 3 | Jyaistha |
| month 4 | Asadha |
| month 5 | Sravana |
| month 6 | Bhadra |
| month 7 | Asvina |
| month 8 | Kartika |
| month 9 | Agrahayana |
| month 10 | Pausa |
| month 11 | Magha |
| month 12 | Phalguna |
#### islamic calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | Moh. |
| month 2 | Saf. |
| month 3 | Réb. 1 |
| month 4 | Réb. 2 |
| month 5 | Dsem. I |
| month 6 | Dsem. II |
| month 7 | Red. |
| month 8 | Sab. |
| month 9 | Ram. |
| month 10 | Sev. |
| month 11 | Dsül k. |
| month 12 | Dsül h. |
| month 1 | Moharrem |
| month 2 | Safar |
| month 3 | Rébi el avvel |
| month 4 | Rébi el accher |
| month 5 | Dsemádi el avvel |
| month 6 | Dsemádi el accher |
| month 7 | Redseb |
| month 8 | Sabán |
| month 9 | Ramadán |
| month 10 | Sevvál |
| month 11 | Dsül kade |
| month 12 | Dsül hedse |
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
| month 1 | Moharrem |
| month 2 | Safar |
| month 3 | Rébi I |
| month 4 | Rébi II |
| month 5 | Dsemádi I |
| month 6 | Dsemádi II |
| month 7 | Redseb |
| month 8 | Sabán |
| month 9 | Ramadán |
| month 10 | Sevvál |
| month 11 | Dsül kade |
| month 12 | Dsül hedse |
| era | MF |
| era | MF |
| era | MF |
#### japanese calendar
| ID-stuff | values |
| -------- | ------ |
| date format | `G y. MMMM d., EEEE` |
| date format | `G y. MMMM d.` |
| date format | `G y.MM.dd.` |
| date format | `GGGGG y.MM.dd.` |
#### persian calendar
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
| month 1 | farvardin |
| month 2 | ordibehesht |
| month 3 | khordad |
| month 4 | tir |
| month 5 | mordad |
| month 6 | shahrivar |
| month 7 | mehr |
| month 8 | aban |
| month 9 | azar |
| month 10 | dey |
| month 11 | bahman |
| month 12 | esfand |
| month 1 | farvardin |
| month 2 | ordibehesht |
| month 3 | khordad |
| month 4 | tir |
| month 5 | mordad |
| month 6 | shahrivar |
| month 7 | mehr |
| month 8 | aban |
| month 9 | azar |
| month 10 | dey |
| month 11 | bahman |
| month 12 | esfand |
| month 1 | farvardin |
| month 2 | ordibehesht |
| month 3 | khordad |
| month 4 | tir |
| month 5 | mordad |
| month 6 | shahrivar |
| month 7 | mehr |
| month 8 | aban |
| month 9 | azar |
| month 10 | dey |
| month 11 | bahman |
| month 12 | esfand |
#### roc calendar
| ID-stuff | values |
| -------- | ------ |
| era | R.O.C. előtt |
| era | R.O.C. |
| era | R.O.C. előtt |
| era | R.O.C. |
| era | R.O.C. előtt |
| era | R.O.C. |
### some more time stuff
|  | éra |
|  | éra |
|  | éra |
|  | év |
előző évez az évkövetkező év{0} év múlva{0} év múlva{0} évvel ezelőtt{0} évvel ezelőtt
|  | év |
előző évez az évkövetkező év{0} év múlva{0} év múlva{0} évvel ezelőtt{0} évvel ezelőtt
|  | év |
előző évez az évkövetkező év{0} év múlva{0} év múlva{0} évvel ezelőtt{0} évvel ezelőtt
|  | negyedév |
előző negyedévez a negyedévkövetkező negyedév{0} negyedév múlva{0} negyedév múlva{0} negyedévvel ezelőtt{0} negyedévvel ezelőtt
|  | n.év |
előző negyedévez a negyedévkövetkező negyedév{0} negyedév múlva{0} negyedév múlva{0} negyedévvel ezelőtt{0} negyedévvel ezelőtt
|  | n.év |
előző negyedévez a negyedévkövetkező negyedév{0} n.év múlva{0} n.év múlva{0} negyedévvel ezelőtt{0} negyedévvel ezelőtt
|  | hónap |
előző hónapez a hónapkövetkező hónap{0} hónap múlva{0} hónap múlva{0} hónappal ezelőtt{0} hónappal ezelőtt
|  | hónap |
előző hónapez a hónapkövetkező hónap{0} hónap múlva{0} hónap múlva{0} hónappal ezelőtt{0} hónappal ezelőtt
|  | hónap |
előző hónapez a hónapkövetkező hónap{0} hónap múlva{0} hónap múlva{0} hónappal ezelőtt{0} hónappal ezelőtt
|  | hét |
előző hétez a hétkövetkező hét{0} hét múlva{0} hét múlva{0} héttel ezelőtt{0} héttel ezelőtt{0} hete
|  | hét |
előző hétez a hétkövetkező hét{0} hét múlva{0} hét múlva{0} héttel ezelőtt{0} héttel ezelőtt{0} hete
|  | hét |
előző hétez a hétkövetkező hét{0} hét múlva{0} hét múlva{0} héttel ezelőtt{0} héttel ezelőtt{0} hete
|  | hónap hete |
|  | hónap hete |
|  | hónap hete |
|  | nap |
tegnapelőtttegnapmaholnapholnapután{0} nap múlva{0} nap múlva{0} nappal ezelőtt{0} nappal ezelőtt
|  | nap |
tegnapelőtttegnapmaholnapholnapután{0} nap múlva{0} nap múlva{0} napja{0} napja
|  | nap |
tegnapelőtttegnapmaholnapholnapután{0} nap múlva{0} nap múlva{0} napja{0} napja
|  | év napja |
|  | év napja |
|  | év napja |
|  | hét napja |
|  | hét napja |
|  | hét napja |
|  | hónap hétköznapja |
|  | hónap hétköznapja |
|  | hónap hétköznapja |
előző vasárnapez a vasárnapkövetkező vasárnap{0} vasárnap múlva{0} vasárnap múlva{0} vasárnappal ezelőtt{0} vasárnappal ezelőttelőző vasárnapez a vasárnapkövetkező vasárnap{0} vasárnap múlva{0} vasárnap múlva{0} vasárnappal ezelőtt{0} vasárnappal ezelőttelőző vasárnapez a vasárnapkövetkező vasárnap{0} vasárnap múlva{0} vasárnap múlva{0} vasárnappal ezelőtt{0} vasárnappal ezelőttelőző hétfőez a hétfőkövetkező hétfő{0} hétfő múlva{0} hétfő múlva{0} hétfővel ezelőtt{0} hétfővel ezelőttelőző hétfőez a hétfőkövetkező hétfő{0} hétfő múlva{0} hétfő múlva{0} hétfővel ezelőtt{0} hétfővel ezelőttelőző hétfőez a hétfőkövetkező hétfő{0} hétfő múlva{0} hétfő múlva{0} hétfővel ezelőtt{0} hétfővel ezelőttelőző keddez a keddkövetkező kedd{0} kedd múlva{0} kedd múlva{0} keddel ezelőtt{0} keddel ezelőttelőző keddez a keddkövetkező kedd{0} kedd múlva{0} kedd múlva{0} keddel ezelőtt{0} keddel ezelőttelőző keddez a keddkövetkező kedd{0} kedd múlva{0} kedd múlva{0} keddel ezelőtt{0} keddel ezelőttelőző szerdaez a szerdakövetkező szerda{0} szerda múlva{0} szerda múlva{0} szerdával ezelőtt{0} szerdával ezelőttelőző szerdaez a szerdakövetkező szerda{0} szerda múlva{0} szerda múlva{0} szerdával ezelőtt{0} szerdával ezelőttelőző szerdaez a szerdakövetkező szerda{0} szerda múlva{0} szerda múlva{0} szerdával ezelőtt{0} szerdával ezelőttelőző csütörtökez a csütörtökkövetkező csütörtök{0} csütörtök múlva{0} csütörtök múlva{0} csütörtökkel ezelőtt{0} csütörtökkel ezelőttelőző csütörtökez a csütörtökkövetkező csütörtök{0} csütörtök múlva{0} csütörtök múlva{0} csütörtökkel ezelőtt{0} csütörtökkel ezelőttelőző csütörtökez a csütörtökkövetkező csütörtök{0} csütörtök múlva{0} csütörtök múlva{0} csütörtökkel ezelőtt{0} csütörtökkel ezelőttelőző péntekez a péntekkövetkező péntek{0} péntek múlva{0} péntek múlva{0} péntekkel ezelőtt{0} péntekkel ezelőttelőző péntekez a péntekkövetkező péntek{0} péntek múlva{0} péntek múlva{0} péntekkel ezelőtt{0} péntekkel ezelőttelőző péntekez a péntekkövetkező péntek{0} péntek múlva{0} péntek múlva{0} péntekkel ezelőtt{0} péntekkel ezelőttelőző szombatez a szombatkövetkező szombat{0} szombat múlva{0} szombat múlva{0} szombattal ezelőtt{0} szombattal ezelőttelőző szombatez a szombatkövetkező szombat{0} szombat múlva{0} szombat múlva{0} szombattal ezelőtt{0} szombattal ezelőttelőző szombatez a szombatkövetkező szombat{0} szombat múlva{0} szombat múlva{0} szombattal ezelőtt{0} szombattal ezelőtt
|  | napszak |
|  | napszak |
|  | napszak |
|  | óra |
ebben az órában{0} óra múlva{0} óra múlva{0} órával ezelőtt{0} órával ezelőtt
|  | óra |
{0} óra múlva{0} óra múlva{0} órával ezelőtt{0} órával ezelőtt
|  | óra |
{0} óra múlva{0} óra múlva{0} órával ezelőtt{0} órával ezelőtt
|  | perc |
ebben a percben{0} perc múlva{0} perc múlva{0} perccel ezelőtt{0} perccel ezelőtt
|  | perc |
{0} perc múlva{0} perc múlva{0} perccel ezelőtt{0} perccel ezelőtt
|  | perc |
{0} perc múlva{0} perc múlva{0} perccel ezelőtt{0} perccel ezelőtt
|  | másodperc |
most{0} másodperc múlva{0} másodperc múlva{0} másodperccel ezelőtt{0} másodperccel ezelőtt
|  | másodperc |
{0} másodperc múlva{0} másodperc múlva{0} másodperccel ezelőtt{0} másodperccel ezelőtt
|  | másodperc |
{0} másodperc múlva{0} másodperc múlva{0} másodperccel ezelőtt{0} másodperccel ezelőtt
|  | időzóna |
|  | időzóna |
|  | időzóna |
#### time zones
| Format name | Format |
| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| Time at Greenwich | GMT |
| regional | {0} idő |
| regional | {0} nyári idő |
| regional | {0} zónaidő |
| fallback | {1} ({0}) |
| Zone | Name |
| ---- | ---- |
| America/Santa_Isabel | Santa Isabel |
| Pacific/Honolulu | Honolulu |
| Etc/UTC | egyezményes koordinált világidő |
| Etc/Unknown | Ismeretlen város |
| Europe/Andorra | Andorra |
| Asia/Dubai | Dubai |
| Asia/Kabul | Kabul |
| America/Antigua | Antigua |
| America/Anguilla | Anguilla |
| Europe/Tirane | Tirana |
| Asia/Yerevan | Jereván |
| Africa/Luanda | Luanda |
| Antarctica/Rothera | Rothera |
| Antarctica/Palmer | Palmer |
| Antarctica/Troll | Troll |
| Antarctica/Syowa | Syowa |
| Antarctica/Mawson | Mawson |
| Antarctica/Davis | Davis |
| Antarctica/Vostok | Vosztok |
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
| Europe/Vienna | Bécs |
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
| Europe/Mariehamn | Mariehamn |
| Asia/Baku | Baku |
| Europe/Sarajevo | Szarajevó |
| America/Barbados | Barbados |
| Asia/Dhaka | Dakka |
| Europe/Brussels | Brüsszel |
| Africa/Ouagadougou | Ouagadougou |
| Europe/Sofia | Szófia |
| Asia/Bahrain | Bahrein |
| Africa/Bujumbura | Bujumbura |
| Africa/Porto-Novo | Porto-Novo |
| America/St_Barthelemy | Saint-Barthélemy |
| Atlantic/Bermuda | Bermuda |
| Asia/Brunei | Brunei |
| America/La_Paz | La Paz |
| America/Kralendijk | Kralendijk |
| America/Eirunepe | Eirunepé |
| America/Rio_Branco | Río Branco |
| America/Porto_Velho | Porto Velho |
| America/Boa_Vista | Boa Vista |
| America/Manaus | Manaus |
| America/Cuiaba | Cuiabá |
| America/Santarem | Santarem |
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
| Europe/Minsk | Minszk |
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
| Indian/Cocos | Kókusz-sziget |
| Africa/Kinshasa | Kinshasa |
| Africa/Lubumbashi | Lubumbashi |
| Africa/Bangui | Bangui |
| Africa/Brazzaville | Brazzaville |
| Europe/Zurich | Zürich |
| Africa/Abidjan | Abidjan |
| Pacific/Rarotonga | Rarotonga |
| Pacific/Easter | Húsvét-szigetek |
| America/Punta_Arenas | Punta Arenas |
| America/Santiago | Santiago |
| Africa/Douala | Douala |
| Asia/Urumqi | Ürümqi |
| Asia/Shanghai | Sanghaj |
| America/Bogota | Bogotá |
| America/Costa_Rica | Costa Rica |
| America/Havana | Havanna |
| Atlantic/Cape_Verde | Zöld-foki szigetek |
| America/Curacao | Curaçao |
| Indian/Christmas | Karácsony-sziget |
| Asia/Nicosia | Nicosia |
| Asia/Famagusta | Famagusta |
| Europe/Prague | Prága |
| Europe/Busingen | Büsingen |
| Europe/Berlin | Berlin |
| Africa/Djibouti | Dzsibuti |
| Europe/Copenhagen | Koppenhága |
| America/Dominica | Dominika |
| America/Santo_Domingo | Santo Domingo |
| Africa/Algiers | Algír |
| Pacific/Galapagos | Galapagos-szigetek |
| America/Guayaquil | Guayaquil |
| Europe/Tallinn | Tallin |
| Africa/Cairo | Kairó |
| Africa/El_Aaiun | El-Ajún |
| Africa/Asmera | Asmera |
| Atlantic/Canary | Kanári-szigetek |
| Africa/Ceuta | Ceuta |
| Europe/Madrid | Madrid |
| Africa/Addis_Ababa | Addisz-Abeba |
| Europe/Helsinki | Helsinki |
| Pacific/Fiji | Fidzsi |
| Atlantic/Stanley | Stanley |
| Pacific/Truk | Truk |
| Pacific/Ponape | Ponape-szigetek |
| Pacific/Kosrae | Kosrae-szigetek |
| Atlantic/Faeroe | Feröer |
| Europe/Paris | Párizs |
| Africa/Libreville | Libreville |
| Europe/London | brit nyári időLondon |
| America/Grenada | Grenada |
| Asia/Tbilisi | Tbiliszi |
| America/Cayenne | Cayenne |
| Europe/Guernsey | Guernsey |
| Africa/Accra | Accra |
| Europe/Gibraltar | Gibraltár |
| America/Thule | Thule |
| America/Godthab | Nuuk |
| America/Scoresbysund | Ittoqqortoormiit |
| America/Danmarkshavn | Danmarkshavn |
| Africa/Banjul | Banjul |
| Africa/Conakry | Conakry |
| America/Guadeloupe | Guadeloupe |
| Africa/Malabo | Malabó |
| Europe/Athens | Athén |
| Atlantic/South_Georgia | Déli-Georgia |
| America/Guatemala | Guatemala |
| Pacific/Guam | Guam |
| Africa/Bissau | Bissau |
| America/Guyana | Guyana |
| Asia/Hong_Kong | Hongkong |
| America/Tegucigalpa | Tegucigalpa |
| Europe/Zagreb | Zágráb |
| America/Port-au-Prince | Port-au-Prince |
| Europe/Budapest | Budapest |
| Asia/Jakarta | Jakarta |
| Asia/Pontianak | Pontianak |
| Asia/Makassar | Makasar |
| Asia/Jayapura | Jayapura |
| Europe/Dublin | ír nyári időDublin |
| Asia/Jerusalem | Jeruzsálem |
| Europe/Isle_of_Man | Man-sziget |
| Asia/Calcutta | Kalkutta |
| Indian/Chagos | Chagos |
| Asia/Baghdad | Bagdad |
| Asia/Tehran | Teherán |
| Atlantic/Reykjavik | Reykjavík |
| Europe/Rome | Róma |
| Europe/Jersey | Jersey |
| America/Jamaica | Jamaica |
| Asia/Amman | Ammán |
| Asia/Tokyo | Tokió |
| Africa/Nairobi | Nairobi |
| Asia/Bishkek | Biskek |
| Asia/Phnom_Penh | Phnom Penh |
| Pacific/Enderbury | Enderbury |
| Pacific/Kiritimati | Kiritimati-sziget |
| Pacific/Tarawa | Tarawa |
| Indian/Comoro | Komoró |
| America/St_Kitts | St. Kitts |
| Asia/Pyongyang | Phenjan |
| Asia/Seoul | Szöul |
| Asia/Kuwait | Kuvait |
| America/Cayman | Kajmán-szigetek |
| Asia/Aqtau | Aktau |
| Asia/Oral | Oral |
| Asia/Atyrau | Atyrau |
| Asia/Aqtobe | Aktöbe |
| Asia/Qyzylorda | Kizilorda |
| Asia/Almaty | Alma-Ata |
| Asia/Vientiane | Vientián |
| Asia/Beirut | Bejrút |
| America/St_Lucia | St. Lucia |
| Europe/Vaduz | Vaduz |
| Asia/Colombo | Colombo |
| Africa/Monrovia | Monrovia |
| Africa/Maseru | Maseru |
| Europe/Vilnius | Vilnius |
| Europe/Luxembourg | Luxemburg |
| Europe/Riga | Riga |
| Africa/Tripoli | Tripoli |
| Africa/Casablanca | Casablanca |
| Europe/Monaco | Monaco |
| Europe/Chisinau | Chisinau |
| Europe/Podgorica | Podgorica |
| America/Marigot | Marigot |
| Indian/Antananarivo | Antananarivo |
| Pacific/Kwajalein | Kwajalein-zátony |
| Pacific/Majuro | Majuro-zátony |
| Europe/Skopje | Skopje |
| Africa/Bamako | Bamako |
| Asia/Rangoon | Yangon |
| Asia/Hovd | Hovd |
| Asia/Ulaanbaatar | Ulánbátor |
| Asia/Choibalsan | Csojbalszan |
| Asia/Macau | Makaó |
| Pacific/Saipan | Saipan |
| America/Martinique | Martinique |
| Africa/Nouakchott | Nouakchott |
| America/Montserrat | Montserrat |
| Europe/Malta | Málta |
| Indian/Mauritius | Mauritius |
| Indian/Maldives | Maldív-szigetek |
| Africa/Blantyre | Blantyre |
| America/Tijuana | Tijuana |
| America/Hermosillo | Hermosillo |
| America/Mazatlan | Mazatlán |
| America/Chihuahua | Chihuahua |
| America/Bahia_Banderas | Bahia Banderas |
| America/Ojinaga | Ojinaga |
| America/Monterrey | Monterrey |
| America/Mexico_City | Mexikóváros |
| America/Matamoros | Matamoros |
| America/Merida | Mérida |
| America/Cancun | Cancún |
| Asia/Kuala_Lumpur | Kuala Lumpur |
| Asia/Kuching | Kucseng |
| Africa/Maputo | Maputo |
| Africa/Windhoek | Windhoek |
| Pacific/Noumea | Noumea |
| Africa/Niamey | Niamey |
| Pacific/Norfolk | Norfolk |
| Africa/Lagos | Lagos |
| America/Managua | Managua |
| Europe/Amsterdam | Amszterdam |
| Europe/Oslo | Oslo |
| Asia/Katmandu | Katmandu |
| Pacific/Nauru | Nauru |
| Pacific/Niue | Niue |
| Pacific/Chatham | Chatham-szigetek |
| Pacific/Auckland | Auckland |
| Asia/Muscat | Muscat |
| America/Panama | Panama |
| America/Lima | Lima |
| Pacific/Tahiti | Tahiti |
| Pacific/Marquesas | Marquesas-szigetek |
| Pacific/Gambier | Gambier-szigetek |
| Pacific/Port_Moresby | Port Moresby |
| Pacific/Bougainville | Bougainville |
| Asia/Manila | Manila |
| Asia/Karachi | Karacsi |
| Europe/Warsaw | Varsó |
| America/Miquelon | Miquelon |
| Pacific/Pitcairn | Pitcairn-szigetek |
| America/Puerto_Rico | Puerto Rico |
| Asia/Gaza | Gáza |
| Asia/Hebron | Hebron |
| Atlantic/Azores | Azori-szigetek |
| Atlantic/Madeira | Madeira |
| Europe/Lisbon | Lisszabon |
| Pacific/Palau | Palau |
| America/Asuncion | Asunción |
| Asia/Qatar | Katar |
| Indian/Reunion | Réunion |
| Europe/Bucharest | Bukarest |
| Europe/Belgrade | Belgrád |
| Europe/Kaliningrad | Kalinyingrád |
| Europe/Simferopol | Szimferopol |
| Europe/Moscow | Moszkva |
| Europe/Volgograd | Volgográd |
| Europe/Saratov | Szaratov |
| Europe/Astrakhan | Asztrahán |
| Europe/Ulyanovsk | Uljanovszk |
| Europe/Kirov | Kirov |
| Europe/Samara | Szamara |
| Asia/Yekaterinburg | Jekatyerinburg |
| Asia/Omsk | Omszk |
| Asia/Novosibirsk | Novoszibirszk |
| Asia/Barnaul | Barnaul |
| Asia/Tomsk | Tomszk |
| Asia/Novokuznetsk | Novokuznyeck |
| Asia/Krasnoyarsk | Krasznojarszk |
| Asia/Irkutsk | Irkutszk |
| Asia/Chita | Csita |
| Asia/Yakutsk | Jakutszk |
| Asia/Vladivostok | Vlagyivosztok |
| Asia/Khandyga | Handiga |
| Asia/Sakhalin | Szahalin |
| Asia/Ust-Nera | Uszty-Nyera |
| Asia/Magadan | Magadán |
| Asia/Srednekolymsk | Szrednekolimszk |
| Asia/Kamchatka | Kamcsatka |
| Asia/Anadyr | Anadir |
| Africa/Kigali | Kigali |
| Asia/Riyadh | Rijád |
| Pacific/Guadalcanal | Guadalcanal |
| Indian/Mahe | Mahe |
| Africa/Khartoum | Kartúm |
| Europe/Stockholm | Stockholm |
| Asia/Singapore | Szingapúr |
| Atlantic/St_Helena | Szent Ilona |
| Europe/Ljubljana | Ljubljana |
| Arctic/Longyearbyen | Longyearbyen |
| Europe/Bratislava | Pozsony |
| Africa/Freetown | Freetown |
| Europe/San_Marino | San Marino |
| Africa/Dakar | Dakar |
| Africa/Mogadishu | Mogadishu |
| America/Paramaribo | Paramaribo |
| Africa/Juba | Juba |
| Africa/Sao_Tome | São Tomé |
| America/El_Salvador | Salvador |
| America/Lower_Princes | Lower Prince’s Quarter |
| Asia/Damascus | Damaszkusz |
| Africa/Mbabane | Mbabane |
| America/Grand_Turk | Grand Turk |
| Africa/Ndjamena | Ndjamena |
| Indian/Kerguelen | Kerguelen |
| Africa/Lome | Lome |
| Asia/Bangkok | Bangkok |
| Asia/Dushanbe | Dushanbe |
| Pacific/Fakaofo | Fakaofo |
| Asia/Dili | Dili |
| Asia/Ashgabat | Asgabat |
| Africa/Tunis | Tunisz |
| Pacific/Tongatapu | Tongatapu |
| Europe/Istanbul | Isztanbul |
| America/Port_of_Spain | Port of Spain |
| Pacific/Funafuti | Funafuti |
| Asia/Taipei | Tajpej |
| Africa/Dar_es_Salaam | Dar es-Salaam |
| Europe/Uzhgorod | Ungvár |
| Europe/Kiev | Kijev |
| Europe/Zaporozhye | Zaporozsje |
| Africa/Kampala | Kampala |
| Pacific/Midway | Midway-szigetek |
| Pacific/Wake | Wake-sziget |
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
| America/North_Dakota/Beulah | Beulah, Észak-Dakota |
| America/North_Dakota/New_Salem | New Salem, Észak-Dakota |
| America/North_Dakota/Center | Center, Észak-Dakota |
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
| Asia/Samarkand | Szamarkand |
| Asia/Tashkent | Taskent |
| Europe/Vatican | Vatikán |
| America/St_Vincent | St. Vincent |
| America/Caracas | Caracas |
| America/Tortola | Tortola |
| America/St_Thomas | St. Thomas |
| Asia/Saigon | Ho Si Minh-város |
| Pacific/Efate | Efate |
| Pacific/Wallis | Wallis |
| Pacific/Apia | Apia |
| Asia/Aden | Áden |
| Indian/Mayotte | Mayotte |
| Africa/Johannesburg | Johannesburg |
| Africa/Lusaka | Lusaka |
| Africa/Harare | Harare |
| Acre | Acre időAcre zónaidőAcre nyári idő |
| Afghanistan | afganisztáni idő |
| Africa_Central | közép-afrikai téli idő |
| Africa_Eastern | kelet-afrikai téli idő |
| Africa_Southern | dél-afrikai téli idő |
| Africa_Western | nyugat-afrikai időzónanyugat-afrikai téli időnyugat-afrikai nyári idő |
| Alaska | alaszkai időalaszkai zónaidőalaszkai nyári idő |
| Almaty | Almati időAlmati zónaidőAlmati nyári idő |
| Amazon | amazóniai időamazóniai téli időamazóniai nyári idő |
| America_Central | középső államokbeli időközépső államokbeli zónaidőközépső államokbeli nyári idő |
| America_Eastern | keleti államokbeli időkeleti államokbeli zónaidőkeleti államokbeli nyári idő |
| America_Mountain | hegyvidéki időhegyvidéki zónaidőhegyvidéki nyári idő |
| America_Pacific | csendes-óceáni időcsendes-óceáni zónaidőcsendes-óceáni nyári idő |
| Anadyr | Anadiri időAnadíri zónaidőAnadíri nyári idő |
| Apia | apiai időapiai téli időapiai nyári idő |
| Aqtau | Aqtaui időAqtaui zónaidőAqtaui nyári idő |
| Aqtobe | Aqtobei időAqtobei zónaidőAqtobei nyári idő |
| Arabian | arab időarab téli időarab nyári idő |
| Argentina | argentínai időargentínai téli időargentínai nyári idő |
| Argentina_Western | nyugat-argentínai időzónanyugat-argentínai téli időnyugat-argentínai nyári idő |
| Armenia | örményországi időörményországi téli időörményországi nyári idő |
| Atlantic | atlanti-óceáni időatlanti-óceáni zónaidőatlanti-óceáni nyári idő |
| Australia_Central | közép-ausztráliai időközép-ausztráliai téli időközép-ausztráliai nyári idő |
| Australia_CentralWestern | közép-nyugat-ausztráliai időközép-nyugat-ausztráliai téli időközép-nyugat-ausztráliai nyári idő |
| Australia_Eastern | kelet-ausztráliai időkelet-ausztráliai téli időkelet-ausztráliai nyári idő |
| Australia_Western | nyugat-ausztráliai időnyugat-ausztráliai téli időnyugat-ausztráliai nyári idő |
| Azerbaijan | azerbajdzsáni időazerbajdzsáni téli időazerbajdzsáni nyári idő |
| Azores | azori időzónaazori téli időazori nyári idő |
| Bangladesh | bangladesi időbangladesi téli időbangladesi nyári idő |
| Bhutan | butáni idő |
| Bolivia | bolíviai téli idő |
| Brasilia | brazíliai időbrazíliai téli időbrazíliai nyári idő |
| Brunei | Brunei Darussalam-i idő |
| Cape_Verde | zöld-foki-szigeteki időzónazöld-foki-szigeteki téli időzöld-foki-szigeteki nyári idő |
| Chamorro | chamorrói téli idő |
| Chatham | chathami időchathami téli időchathami nyári idő |
| Chile | chilei időzónachilei téli időchilei nyári idő |
| China | kínai időkínai téli időkínai nyári idő |
| Choibalsan | csojbalszani időcsojbalszani téli időcsojbalszani nyári idő |
| Christmas | karácsony-szigeti téli idő |
| Cocos | kókusz-szigeteki téli idő |
| Colombia | kolumbiai időkolumbiai téli időkolumbiai nyári idő |
| Cook | cook-szigeteki időcook-szigeteki téli időcook-szigeteki fél nyári idő |
| Cuba | kubai időzónakubai téli időkubai nyári idő |
| Davis | davisi idő |
| DumontDUrville | dumont-d’Urville-i idő |
| East_Timor | kelet-timori téli idő |
| Easter | húsvét-szigeti időzónahúsvét-szigeti téli időhúsvét-szigeti nyári idő |
| Ecuador | ecuadori téli idő |
| Europe_Central | közép-európai időzónaközép-európai téli időközép-európai nyári időCETCETCEST |
| Europe_Eastern | kelet-európai időzónakelet-európai téli időkelet-európai nyári időEETEETEEST |
| Europe_Further_Eastern | minszki idő |
| Europe_Western | nyugat-európai időzónanyugat-európai téli időnyugat-európai nyári időWETWETWEST |
| Falkland | falkland-szigeteki időfalkland-szigeteki téli időfalkland-szigeteki nyári idő |
| Fiji | fidzsi időfidzsi téli időfidzsi nyári idő |
| French_Guiana | francia-guyanai idő |
| French_Southern | francia déli és antarktiszi idő |
| Galapagos | galápagosi téli idő |
| Gambier | gambieri idő |
| Georgia | grúziai időgrúziai téli időgrúziai nyári idő |
| Gilbert_Islands | gilbert-szigeteki idő |
| GMT | greenwichi középidő, téli időGMT |
| Greenland_Eastern | kelet-grönlandi időzónakelet-grönlandi téli időkelet-grönlandi nyári idő |
| Greenland_Western | nyugat-grönlandi időzónanyugat-grönlandi téli időnyugat-grönlandi nyári idő |
| Guam | Guami zónaidő |
| Gulf | öbölbeli téli idő |
| Guyana | guyanai téli idő |
| Hawaii_Aleutian | hawaii-aleuti időzónahawaii-aleuti téli időhawaii-aleuti nyári idő |
| Hong_Kong | hongkongi időzónahongkongi téli időhongkongi nyári idő |
| Hovd | hovdi időhovdi téli időhovdi nyári idő |
| India | indiai téli idő |
| Indian_Ocean | indiai-óceáni idő |
| Indochina | indokínai idő |
| Indonesia_Central | közép-indonéziai idő |
| Indonesia_Eastern | kelet-indonéziai idő |
| Indonesia_Western | nyugat-indonéziai téli idő |
| Iran | iráni időiráni téli időiráni nyári idő |
| Irkutsk | irkutszki időirkutszki téli időirkutszki nyári idő |
| Israel | izraeli időizraeli téli időizraeli nyári idő |
| Japan | japán időjapán téli időjapán nyári idő |
| Kamchatka | Petropavlovszk-kamcsatkai időPetropavlovszk-kamcsatkai zónaidőPetropavlovszk-kamcsatkai nyári idő |
| Kazakhstan_Eastern | kelet-kazahsztáni idő |
| Kazakhstan_Western | nyugat-kazahsztáni idő |
| Korea | koreai időkoreai téli időkoreai nyári idő |
| Kosrae | kosraei idő |
| Krasnoyarsk | krasznojarszki időkrasznojarszki téli időkrasznojarszki nyári idő |
| Kyrgystan | kirgizisztáni idő |
| Lanka | Lankai idő |
| Line_Islands | sor-szigeteki idő |
| Lord_Howe | Lord Howe-szigeti időLord Howe-szigeti téli időLord Howe-szigeti nyári idő |
| Macau | Macaui időMacaui zónaidőMacaui nyári idő |
| Macquarie | macquarie-szigeti téli idő |
| Magadan | magadáni időmagadani téli időmagadáni nyári idő |
| Malaysia | malajziai idő |
| Maldives | maldív-szigeteki idő |
| Marquesas | marquises-szigeteki idő |
| Marshall_Islands | marshall-szigeteki idő |
| Mauritius | mauritiusi időzónamauritiusi téli időmauritiusi nyári idő |
| Mawson | mawsoni idő |
| Mexico_Northwest | északnyugat-mexikói időészaknyugat-mexikói zónaidőészaknyugat-mexikói nyári idő |
| Mexico_Pacific | mexikói csendes-óceáni időmexikói csendes-óceáni zónaidőmexikói csendes-óceáni nyári idő |
| Mongolia | ulánbátori időulánbátori téli időulánbátori nyári idő |
| Moscow | moszkvai időmoszkvai téli időmoszkvai nyári idő |
| Myanmar | mianmari idő |
| Nauru | naurui idő |
| Nepal | nepáli idő |
| New_Caledonia | új-kaledóniai időúj-kaledóniai téli időúj-kaledóniai nyári idő |
| New_Zealand | új-zélandi időúj-zélandi téli időúj-zélandi nyári idő |
| Newfoundland | új-fundlandi időúj-fundlandi zónaidőúj-fundlandi nyári idő |
| Niue | niuei idő |
| Norfolk | norfolk-szigeteki idő |
| Noronha | Fernando de Noronha-i időFernando de Noronha-i téli időFernando de Noronha-i nyári idő |
| North_Mariana | Észak-mariana-szigeteki idő |
| Novosibirsk | novoszibirszki időnovoszibirszki téli időnovoszibirszki nyári idő |
| Omsk | omszki időomszki téli időomszki nyári idő |
| Pakistan | pakisztáni időpakisztáni téli időpakisztáni nyári idő |
| Palau | palaui idő |
| Papua_New_Guinea | pápua új-guineai idő |
| Paraguay | paraguayi időparaguayi téli időparaguayi nyári idő |
| Peru | perui időperui téli időperui nyári idő |
| Philippines | fülöp-szigeteki időfülöp-szigeteki téli időfülöp-szigeteki nyári idő |
| Phoenix_Islands | phoenix-szigeteki téli idő |
| Pierre_Miquelon | Saint-Pierre és Miquelon-i időSaint-Pierre és Miquelon-i zónaidőSaint-Pierre és Miquelon-i nyári idő |
| Pitcairn | pitcairn-szigeteki idő |
| Ponape | ponape-szigeti idő |
| Pyongyang | phenjani idő |
| Qyzylorda | Qyzylordai időQyzylordai zónaidőQyzylordai nyári idő |
| Reunion | réunioni idő |
| Rothera | rotherai idő |
| Sakhalin | szahalini időszahalini téli időszahalini nyári idő |
| Samara | Szamarai időSzamarai zónaidőSzamarai nyári idő |
| Samoa | szamoai időszamoai téli időszamoai nyári idő |
| Seychelles | seychelle-szigeteki idő |
| Singapore | szingapúri téli idő |
| Solomon | salamon-szigeteki idő |
| South_Georgia | déli-georgiai idő |
| Suriname | szurinámi idő |
| Syowa | syowai idő |
| Tahiti | tahiti idő |
| Taipei | taipei időtaipei téli időtaipei nyári idő |
| Tajikistan | tádzsikisztáni idő |
| Tokelau | tokelaui idő |
| Tonga | tongai időtongai téli időtongai nyári idő |
| Truk | truki idő |
| Turkmenistan | türkmenisztáni időtürkmenisztáni téli időtürkmenisztáni nyári idő |
| Tuvalu | tuvalui idő |
| Uruguay | uruguayi időuruguayi téli időuruguayi nyári idő |
| Uzbekistan | üzbegisztáni időüzbegisztáni téli időüzbegisztáni nyári idő |
| Vanuatu | vanuatui idővanuatui téli idővanuatui nyári idő |
| Venezuela | venezuelai idő |
| Vladivostok | vlagyivosztoki idővlagyivosztoki téli idővlagyivosztoki nyári idő |
| Volgograd | volgográdi idővolgográdi téli idővolgográdi nyári idő |
| Vostok | vosztoki idő |
| Wake | wake-szigeti idő |
| Wallis | Wallis és Futuna-i idő |
| Yakutsk | jakutszki időjakutszki téli időjakutszki nyári idő |
| Yekaterinburg | jekatyerinburgi időjekatyerinburgi téli időjekatyerinburgi nyári idő |
## Numbers stuff
latnlatn4
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
| Not a number | NaN |
| Time separator (Hours:Minutes) | : |
#,##0.###0 ezer0 ezer00 ezer00 ezer000 ezer000 ezer0 millió0 millió00 millió00 millió000 millió000 millió0 milliárd0 milliárd00 milliárd00 milliárd000 milliárd000 milliárd0 billió0 billió00 billió00 billió000 billió000 billió0 E0 E00 E00 E000 E000 E0 M0 M00 M00 M000 M000 M0 Mrd0 Mrd00 Mrd00 Mrd000 Mrd000 Mrd0 B0 B00 B00 B000 B000 B#E0#,##0%#,##0.00 ¤#,##0.00 ¤0 E ¤0 E ¤00 E ¤00 E ¤000 E ¤000 E ¤0 M ¤0 M ¤00 M ¤00 M ¤000 M ¤000 M ¤0 Mrd ¤0 Mrd ¤00 Mrd ¤00 Mrd ¤000 Mrd ¤000 Mrd ¤0 B ¤0 B ¤00 B ¤00 B ¤000 B ¤000 B ¤
| one | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  | Andorrai peseta |
| one | Andorrai peseta |
| other | Andorrai peseta |
|  | EAE-dirham |
| one | EAE-dirham |
| other | EAE-dirham |
|  symbol | AED |
|  | afgán afghani (1927–2002) |
| one | afgán afghani (1927–2002) |
| other | afgán afghani (1927–2002) |
|  | afgán afghani |
| one | afgán afghani |
| other | afgán afghani |
|  symbol | AFN |
|  | albán lek |
| one | albán lek |
| other | albán lek |
|  symbol | ALL |
|  | örmény dram |
| one | örmény dram |
| other | örmény dram |
|  symbol | AMD |
|  | holland antilláki forint |
| one | holland antilláki forint |
| other | holland antilláki forint |
|  symbol | ANG |
|  | angolai kwanza |
| one | angolai kwanza |
| other | angolai kwanza |
|  symbol | AOA |
| narrow symbol | Kz |
|  | Angolai kwanza (1977–1990) |
| one | Angolai kwanza (1977–1990) |
| other | Angolai kwanza (1977–1990) |
|  | Angolai új kwanza (1990–2000) |
| one | Angolai új kwanza (1990–2000) |
| other | Angolai új kwanza (1990–2000) |
|  | Angolai kwanza reajustado (1995–1999) |
| one | Angolai kwanza reajustado (1995–1999) |
| other | Angolai kwanza reajustado (1995–1999) |
|  | Argentín austral |
| one | Argentin austral |
| other | Argentin austral |
|  | Argentín peso (1983–1985) |
| one | Argentín peso (1983–1985) |
| other | Argentín peso (1983–1985) |
|  | argentin peso |
| one | argentin peso |
| other | argentin peso |
|  symbol | ARS |
| narrow symbol | $ |
|  | Osztrák schilling |
| one | Osztrák schilling |
| other | Osztrák schilling |
|  | ausztrál dollár |
| one | ausztrál dollár |
| other | ausztrál dollár |
|  symbol | AUD |
| narrow symbol | $ |
|  | arubai florin |
| one | arubai florin |
| other | arubai florin |
|  symbol | AWG |
|  | azerbajdzsáni manat (1993–2006) |
| one | azerbajdzsáni manat (1993–2006) |
| other | azerbajdzsáni manat (1993–2006) |
|  | azerbajdzsáni manat |
| one | azerbajdzsáni manat |
| other | azerbajdzsáni manat |
|  symbol | AZN |
|  | Bosznia-hercegovinai dínár (1992–1994) |
| one | Bosznia-hercegovinai dínár (1992–1994) |
| other | Bosznia-hercegovinai dínár (1992–1994) |
|  | bosznia-hercegovinai konvertibilis márka |
| one | bosznia-hercegovinai konvertibilis márka |
| other | bosznia-hercegovinai konvertibilis márka |
|  symbol | BAM |
| narrow symbol | KM |
|  | barbadosi dollár |
| one | barbadosi dollár |
| other | barbadosi dollár |
|  symbol | BBD |
| narrow symbol | $ |
|  | bangladesi taka |
| one | bangladesi taka |
| other | bangladesi taka |
|  symbol | BDT |
| narrow symbol | ৳ |
|  | Belga frank (konvertibilis) |
| one | Belga frank (konvertibilis) |
| other | Belga frank (konvertibilis) |
|  | Belga frank |
| one | Belga frank |
| other | Belga frank |
|  | Belga frank (pénzügyi) |
| one | Belga frank (pénzügyi) |
| other | Belga frank (pénzügyi) |
|  | Bolgár kemény leva |
| one | Bolgár kemény leva |
| other | Bolgár kemény leva |
|  | bolgár új leva |
| one | bolgár új leva |
| other | bolgár új leva |
|  symbol | BGN |
|  | bahreini dinár |
| one | bahreini dinár |
| other | bahreini dinár |
|  symbol | BHD |
|  | burundi frank |
| one | burundi frank |
| other | burundi frank |
|  symbol | BIF |
|  | bermudai dollár |
| one | bermudai dollár |
| other | bermudai dollár |
|  symbol | BMD |
| narrow symbol | $ |
|  | brunei dollár |
| one | brunei dollár |
| other | brunei dollár |
|  symbol | BND |
| narrow symbol | $ |
|  | bolíviai boliviano |
| one | bolíviai boliviano |
| other | bolíviai boliviano |
|  symbol | BOB |
| narrow symbol | Bs |
|  | Bolíviai peso |
| one | Bolíviai peso |
| other | Bolíviai peso |
|  | Bolíviai mvdol |
| one | Bolíviai mvdol |
| other | Bolíviai mvdol |
|  | Brazi cruzeiro novo (1967–1986) |
| one | Brazi cruzeiro novo (1967–1986) |
| other | Brazi cruzeiro novo (1967–1986) |
|  | Brazi cruzado (1986–1989) |
| one | Brazi cruzado (1986–1989) |
| other | Brazi cruzado (1986–1989) |
|  | Brazil cruzeiro (1990–1993) |
| one | Brazil cruzeiro (1990–1993) |
| other | Brazil cruzeiro (1990–1993) |
|  | brazil real |
| one | brazil real |
| other | brazil real |
|  symbol | BRL |
| narrow symbol | R$ |
|  | Brazil cruzado novo (1989–1990) |
| one | Brazil cruzado novo (1989–1990) |
| other | Brazil cruzado novo (1989–1990) |
|  | Brazil cruzeiro (1993–1994) |
| one | Brazil cruzeiro (1993–1994) |
| other | Brazil cruzeiro (1993–1994) |
|  | bahamai dollár |
| one | bahamai dollár |
| other | bahamai dollár |
|  symbol | BSD |
| narrow symbol | $ |
|  | bhutáni ngultrum |
| one | bhutáni ngultrum |
| other | bhutáni ngultrum |
|  symbol | BTN |
|  | Burmai kyat |
|  | botswanai pula |
| one | botswanai pula |
| other | botswanai pula |
|  symbol | BWP |
| narrow symbol | P |
|  | Fehérorosz új rubel (1994–1999) |
|  | fehérorosz rubel |
| one | fehérorosz rubel |
| other | fehérorosz rubel |
|  symbol | BYN |
| narrow symbol | р. |
|  | fehérorosz rubel (2000–2016) |
| one | fehérorosz rubel (2000–2016) |
| other | fehérorosz rubel (2000–2016) |
|  symbol | BYR |
|  | belize-i dollár |
| one | belize-i dollár |
| other | belize-i dollár |
|  symbol | BZD |
| narrow symbol | $ |
|  | kanadai dollár |
| one | kanadai dollár |
| other | kanadai dollár |
|  symbol | CAD |
| narrow symbol | $ |
|  | kongói frank |
| one | kongói frank |
| other | kongói frank |
|  symbol | CDF |
|  | WIR euro |
|  | svájci frank |
| one | svájci frank |
| other | svájci frank |
|  symbol | CHF |
|  | WIR frank |
|  | Chilei unidades de fomento |
|  | chilei peso |
| one | chilei peso |
| other | chilei peso |
|  symbol | CLP |
| narrow symbol | $ |
|  | kínai jüan (offshore) |
| one | kínai jüan (offshore) |
| other | kínai jüan (offshore) |
|  symbol | CNH |
|  | kínai jüan |
| one | kínai jüan |
| other | kínai jüan |
|  symbol | CNY |
| narrow symbol | ¥ |
|  | kolumbiai peso |
| one | kolumbiai peso |
| other | kolumbiai peso |
|  symbol | COP |
| narrow symbol | $ |
|  | Unidad de Valor Real |
|  | Costa Rica-i colon |
| one | Costa Rica-i colon |
| other | Costa Rica-i colon |
|  symbol | CRC |
| narrow symbol | ₡ |
|  | szerb dinár |
|  | Csehszlovák kemény korona |
|  | kubai konvertibilis peso |
| one | kubai konvertibilis peso |
| other | kubai konvertibilis peso |
|  symbol | CUC |
| narrow symbol | $ |
|  | kubai peso |
| one | kubai peso |
| other | kubai peso |
|  symbol | CUP |
| narrow symbol | $ |
|  | Cape Verde-i escudo |
| one | Cape Verde-i escudo |
| other | Cape Verde-i escudo |
|  symbol | CVE |
|  | Ciprusi font |
|  | cseh korona |
| one | cseh korona |
| other | cseh korona |
|  symbol | CZK |
| narrow symbol | Kč |
|  | Kelet-Német márka |
|  | Német márka |
|  | dzsibuti frank |
| one | dzsibuti frank |
| other | dzsibuti frank |
|  symbol | DJF |
|  | dán korona |
| one | dán korona |
| other | dán korona |
|  symbol | DKK |
| narrow symbol | kr |
|  | dominikai peso |
| one | dominikai peso |
| other | dominikai peso |
|  symbol | DOP |
| narrow symbol | $ |
|  | algériai dínár |
| one | algériai dínár |
| other | algériai dínár |
|  symbol | DZD |
|  | Ecuadori sucre |
|  | Ecuadori Unidad de Valor Constante (UVC) |
|  | Észt korona |
|  | egyiptomi font |
| one | egyiptomi font |
| other | egyiptomi font |
|  symbol | EGP |
| narrow symbol | E£ |
|  | eritreai nakfa |
| one | eritreai nakfa |
| other | eritreai nakfa |
|  symbol | ERN |
|  | spanyol peseta (A–kontó) |
|  | spanyol peseta (konvertibilis kontó) |
|  | Spanyol peseta |
|  | etiópiai birr |
| one | etiópiai birr |
| other | etiópiai birr |
|  symbol | ETB |
|  | euró |
| one | euró |
| other | euró |
|  symbol | EUR |
| narrow symbol | € |
|  | Finn markka |
|  | fidzsi dollár |
| one | fidzsi dollár |
| other | fidzsi dollár |
|  symbol | FJD |
| narrow symbol | $ |
|  | falkland-szigeteki font |
| one | falkland-szigeteki font |
| other | falkland-szigeteki font |
|  symbol | FKP |
| narrow symbol | £ |
|  | Francia frank |
|  | brit font |
| one | brit font |
| other | brit font |
|  symbol | GBP |
| narrow symbol | £ |
|  | Grúz kupon larit |
|  | grúz lari |
| one | grúz lari |
| other | grúz lari |
|  symbol | GEL |
| narrow symbol | ₾ |
| variant symbol | ₾ |
|  | Ghánai cedi (1979–2007) |
|  | ghánai cedi |
| one | ghánai cedi |
| other | ghánai cedi |
|  symbol | GHS |
|  | gibraltári font |
| one | gibraltári font |
| other | gibraltári font |
|  symbol | GIP |
| narrow symbol | £ |
|  | gambiai dalasi |
| one | gambiai dalasi |
| other | gambiai dalasi |
|  symbol | GMD |
|  | guineai frank |
| one | guineai frank |
| other | guineai frank |
|  symbol | GNF |
| narrow symbol | FG |
|  | Guineai syli |
|  | Egyenlítői-guineai ekwele guineana |
| one | Egyenlítői-guineai ekwele |
| other | Egyenlítői-guineai ekwele |
|  | Görög drachma |
|  | guatemalai quetzal |
| one | guatemalai quetzal |
| other | guatemalai quetzal |
|  symbol | GTQ |
| narrow symbol | Q |
|  | Portugál guinea escudo |
|  | Guinea-Bissaui peso |
|  | guyanai dollár |
| one | guyanai dollár |
| other | guyanai dollár |
|  symbol | GYD |
| narrow symbol | $ |
|  | hongkongi dollár |
| one | hongkongi dollár |
| other | hongkongi dollár |
|  symbol | HKD |
| narrow symbol | $ |
|  | hodurasi lempira |
| one | hodurasi lempira |
| other | hodurasi lempira |
|  symbol | HNL |
| narrow symbol | L |
|  | Horvát dínár |
|  | horvát kuna |
| one | horvát kuna |
| other | horvát kuna |
|  symbol | HRK |
| narrow symbol | kn |
|  | haiti gourde |
| one | haiti gourde |
| other | haiti gourde |
|  symbol | HTG |
|  | magyar forint |
| one | magyar forint |
| other | magyar forint |
|  symbol | Ft |
| narrow symbol | Ft |
|  | indonéz rúpia |
| one | indonéz rúpia |
| other | indonéz rúpia |
|  symbol | IDR |
| narrow symbol | Rp |
|  | Ír font |
|  | Izraeli font |
|  | izraeli új sékel |
| one | izraeli új sékel |
| other | izraeli új sékel |
|  symbol | ILS |
| narrow symbol | ₪ |
|  | indiai rúpia |
| one | indiai rúpia |
| other | indiai rúpia |
|  symbol | INR |
| narrow symbol | ₹ |
|  | iraki dínár |
| one | iraki dínár |
| other | iraki dínár |
|  symbol | IQD |
|  | iráni rial |
| one | iráni rial |
| other | iráni rial |
|  symbol | IRR |
|  | izlandi korona |
| one | izlandi korona |
| other | izlandi korona |
|  symbol | ISK |
| narrow symbol | kr |
|  | Olasz líra |
|  | jamaicai dollár |
| one | jamaicai dollár |
| other | jamaicai dollár |
|  symbol | JMD |
| narrow symbol | $ |
|  | jordániai dínár |
| one | jordániai dínár |
| other | jordániai dínár |
|  symbol | JOD |
|  | japán jen |
| one | japán jen |
| other | japán jen |
|  symbol | ¥ |
| narrow symbol | ¥ |
|  | kenyai shilling |
| one | kenyai shilling |
| other | kenyai shilling |
|  symbol | KES |
|  | kirgizisztáni szom |
| one | kirgizisztáni szom |
| other | kirgizisztáni szom |
|  symbol | KGS |
|  | kambodzsai riel |
| one | kambodzsai riel |
| other | kambodzsai riel |
|  symbol | KHR |
| narrow symbol | ៛ |
|  | comorei frank |
| one | comorei frank |
| other | comorei frank |
|  symbol | KMF |
| narrow symbol | CF |
|  | észak-koreai won |
| one | észak-koreai won |
| other | észak-koreai won |
|  symbol | KPW |
| narrow symbol | ₩ |
|  | dél-koreai won |
| one | dél-koreai won |
| other | dél-koreai won |
|  symbol | KRW |
| narrow symbol | ₩ |
|  | kuvaiti dínár |
| one | kuvaiti dínár |
| other | kuvaiti dínár |
|  symbol | KWD |
|  | kajmán-szigeteki dollár |
| one | kajmán-szigeteki dollár |
| other | kajmán-szigeteki dollár |
|  symbol | KYD |
| narrow symbol | $ |
|  | kazahsztáni tenge |
| one | kazahsztáni tenge |
| other | kazahsztáni tenge |
|  symbol | KZT |
| narrow symbol | ₸ |
|  | laoszi kip |
| one | laoszi kip |
| other | laoszi kip |
|  symbol | LAK |
| narrow symbol | ₭ |
|  | libanoni font |
| one | libanoni font |
| other | libanoni font |
|  symbol | LBP |
| narrow symbol | L£ |
|  | Srí Lanka-i rúpia |
| one | Srí Lanka-i rúpia |
| other | Srí Lanka-i rúpia |
|  symbol | LKR |
| narrow symbol | Rs |
|  | libériai dollár |
| one | libériai dollár |
| other | libériai dollár |
|  symbol | LRD |
| narrow symbol | $ |
|  | Lesothoi loti |
|  | litvániai litas |
| one | litvániai litas |
| other | litvániai litas |
|  symbol | LTL |
|  | Litvániai talonas |
|  | luxemburgi konvertibilis frank |
|  | Luxemburgi frank |
|  | luxemburgi pénzügyi frank |
|  | lett lats |
| one | lett lats |
| other | lett lats |
|  symbol | LVL |
|  | Lett rubel |
|  | líbiai dínár |
| one | líbiai dínár |
| other | líbiai dínár |
|  symbol | LYD |
|  | marokkói dirham |
| one | marokkói dirham |
| other | marokkói dirham |
|  symbol | MAD |
|  | Marokkói frank |
|  | moldován lei |
| one | moldován lei |
| other | moldován lei |
|  symbol | MDL |
|  | madagaszkári ariary |
| one | madagaszkári ariary |
| other | madagaszkári ariary |
|  symbol | MGA |
| narrow symbol | Ar |
|  | Madagaszkári frank |
|  | macedon dínár |
| one | macedon dínár |
| other | macedon dínár |
|  symbol | MKD |
|  | Mali frank |
|  | mianmari kyat |
| one | mianmari kyat |
| other | mianmari kyat |
|  symbol | MMK |
| narrow symbol | K |
|  | mongóliai tugrik |
| one | mongóliai tugrik |
| other | mongóliai tugrik |
|  symbol | MNT |
| narrow symbol | ₮ |
|  | makaói pataca |
| one | makaói pataca |
| other | makaói pataca |
|  symbol | MOP |
|  | mauritániai ouguiya |
| one | mauritániai ouguiya |
| other | mauritániai ouguiya |
|  symbol | MRO |
|  | Máltai líra |
|  | Máltai font |
|  | mauritiusi rúpia |
| one | mauritiusi rúpia |
| other | mauritiusi rúpia |
|  symbol | MUR |
| narrow symbol | Rs |
|  | maldív-szigeteki rufiyaa |
| one | maldív-szigeteki rufiyaa |
| other | maldív-szigeteki rufiyaa |
|  symbol | MVR |
|  | malawi kwacha |
| one | malawi kwacha |
| other | malawi kwacha |
|  symbol | MWK |
|  | mexikói peso |
| one | mexikói peso |
| other | mexikói peso |
|  symbol | MXN |
| narrow symbol | $ |
|  | Mexikói ezüst peso (1861–1992) |
|  | Mexikói Unidad de Inversion (UDI) |
|  | malajziai ringgit |
| one | malajziai ringgit |
| other | malajziai ringgit |
|  symbol | MYR |
| narrow symbol | RM |
|  | Mozambik escudo |
|  | Mozambik metical |
|  | mozambiki metikális |
| one | mozambiki metikális |
| other | mozambiki metikális |
|  symbol | MZN |
|  | namíbiai dollár |
| one | namíbiai dollár |
| other | namíbiai dollár |
|  symbol | NAD |
| narrow symbol | $ |
|  | nigériai naira |
| one | nigériai naira |
| other | nigériai naira |
|  symbol | NGN |
| narrow symbol | ₦ |
|  | Nikaraguai cordoba |
|  | nicaraguai córdoba |
| one | nicaraguai córdoba |
| other | nicaraguai córdoba |
|  symbol | NIO |
| narrow symbol | C$ |
|  | Holland forint |
|  | norvég korona |
| one | norvég korona |
| other | norvég korona |
|  symbol | NOK |
| narrow symbol | kr |
|  | nepáli rúpia |
| one | nepáli rúpia |
| other | nepáli rúpia |
|  symbol | NPR |
| narrow symbol | Rs |
|  | új-zélandi dollár |
| one | új-zélandi dollár |
| other | új-zélandi dollár |
|  symbol | NZD |
| narrow symbol | $ |
|  | ománi rial |
| one | ománi rial |
| other | ománi rial |
|  symbol | OMR |
|  | panamai balboa |
| one | panamai balboa |
| other | panamai balboa |
|  symbol | PAB |
|  | perui inti |
|  | perui sol |
| one | perui sol |
| other | perui sol |
|  symbol | PEN |
|  | perui sol (1863–1965) |
|  | pápua új-guineai kina |
| one | pápua új-guineai kina |
| other | pápua új-guineai kina |
|  symbol | PGK |
|  | fülöp-szigeteki peso |
| one | fülöp-szigeteki peso |
| other | fülöp-szigeteki peso |
|  symbol | PHP |
| narrow symbol | ₱ |
|  | pakisztáni rúpia |
| one | pakisztáni rúpia |
| other | pakisztáni rúpia |
|  symbol | PKR |
| narrow symbol | Rs |
|  | lengyel zloty |
| one | lengyel zloty |
| other | lengyel zloty |
|  symbol | PLN |
| narrow symbol | zł |
|  | Lengyel zloty (1950–1995) |
|  | Portugál escudo |
|  | paraguayi guarani |
| one | paraguayi guarani |
| other | paraguayi guarani |
|  symbol | PYG |
| narrow symbol | ₲ |
|  | katari rial |
| one | katari rial |
| other | katari rial |
|  symbol | QAR |
|  | rhodéziai dollár |
| one | Rhodéziai dollár |
| other | Rhodéziai dollár |
|  | román lej (1952–2006) |
| one | román lej (1952–2006) |
| other | román lej (1952–2006) |
|  | román lej |
| one | román lej |
| other | román lej |
|  symbol | RON |
| narrow symbol | lei |
|  | szerb dínár |
| one | szerb dínár |
| other | szerb dínár |
|  symbol | RSD |
|  | orosz rubel |
| one | orosz rubel |
| other | orosz rubel |
|  symbol | RUB |
| narrow symbol | ₽ |
|  | orosz rubel (1991–1998) |
| one | orosz rubel (1991–1998) |
| other | orosz rubel (1991–1998) |
|  | ruandai frank |
| one | ruandai frank |
| other | ruandai frank |
|  symbol | RWF |
| narrow symbol | RF |
|  | szaúdi riyal |
| one | szaúdi riyal |
| other | szaúdi riyal |
|  symbol | SAR |
|  | salamon-szigeteki dollár |
| one | salamon-szigeteki dollár |
| other | salamon-szigeteki dollár |
|  symbol | SBD |
| narrow symbol | $ |
|  | seychelle-szigeteki rúpia |
| one | seychelle-szigeteki rúpia |
| other | seychelle-szigeteki rúpia |
|  symbol | SCR |
|  | Szudáni dínár (1992–2007) |
| one | Szudáni dínár (1992–2007) |
| other | Szudáni dínár (1992–2007) |
|  | szudáni font |
| one | szudáni font |
| other | szudáni font |
|  symbol | SDG |
|  | Szudáni font (1957–1998) |
| one | Szudáni font (1957–1998) |
| other | Szudáni font (1957–1998) |
|  | svéd korona |
| one | svéd korona |
| other | svéd korona |
|  symbol | SEK |
| narrow symbol | kr |
|  | szingapúri dollár |
| one | szingapúri dollár |
| other | szingapúri dollár |
|  symbol | SGD |
| narrow symbol | $ |
|  | Szent Ilona-i font |
| one | Szent Ilona-i font |
| other | Szent Ilona-i font |
|  symbol | SHP |
| narrow symbol | £ |
|  | Szlovén tolar |
|  | Szlovák korona |
|  | Sierra Leone-i leone |
| one | Sierra Leone-i leone |
| other | Sierra Leone-i leone |
|  symbol | SLL |
|  | szomáli shilling |
| one | szomáli shilling |
| other | szomáli shilling |
|  symbol | SOS |
|  | suriname-i dollár |
| one | suriname-i dollár |
| other | suriname-i dollár |
|  symbol | SRD |
| narrow symbol | $ |
|  | Suriname-i gulden |
|  | dél-szudáni font |
| one | dél-szudáni font |
| other | dél-szudáni font |
|  symbol | SSP |
| narrow symbol | £ |
|  | São Tomé és Príncipe-i dobra (1977–2017) |
| one | São Tomé és Príncipe-i dobra (1977–2017) |
| other | São Tomé és Príncipe-i dobra (1977–2017) |
|  symbol | STD |
|  | São Tomé és Príncipe-i dobra |
| one | São Tomé és Príncipe-i dobra |
| other | São Tomé és Príncipe-i dobra |
| narrow symbol | Db |
|  | Szovjet rubel |
|  | Salvadori colón |
|  | szíriai font |
| one | szíriai font |
| other | szíriai font |
|  symbol | SYP |
| narrow symbol | £ |
|  | szváziföldi lilangeni |
| one | szváziföldi lilangeni |
| other | szváziföldi lilangeni |
|  symbol | SZL |
|  | thai baht |
| one | thai baht |
| other | thai baht |
|  symbol | THB |
| narrow symbol | ฿ |
|  | Tádzsikisztáni rubel |
|  | tádzsikisztáni somoni |
| one | tádzsikisztáni somoni |
| other | tádzsikisztáni somoni |
|  symbol | TJS |
|  | türkmenisztáni manat (1993–2009) |
| one | türkmenisztáni manat (1993–2009) |
| other | türkmenisztáni manat (1993–2009) |
|  | türkmenisztáni manat |
| one | türkmenisztáni manat |
| other | türkmenisztáni manat |
|  symbol | TMT |
|  | tunéziai dínár |
| one | tunéziai dínár |
| other | tunéziai dínár |
|  symbol | TND |
|  | tongai paanga |
| one | tongai paanga |
| other | tongai paanga |
|  symbol | TOP |
| narrow symbol | T$ |
|  | Timori escudo |
|  | török líra (1922–2005) |
| one | török líra (1922–2005) |
| other | török líra (1922–2005) |
|  | török líra |
| one | török líra |
| other | török líra |
|  symbol | TRY |
| narrow symbol | ₺ |
| variant symbol | TL |
|  | Trinidad és Tobago-i dollár |
| one | Trinidad és Tobago-i dollár |
| other | Trinidad és Tobago-i dollár |
|  symbol | TTD |
| narrow symbol | $ |
|  | tajvani új dollár |
| one | tajvani új dollár |
| other | tajvani új dollár |
|  symbol | TWD |
| narrow symbol | NT$ |
|  | tanzániai shilling |
| one | tanzániai shilling |
| other | tanzániai shilling |
|  symbol | TZS |
|  | ukrán hrivnya |
| one | ukrán hrivnya |
| other | ukrán hrivnya |
|  symbol | UAH |
| narrow symbol | ₴ |
|  | Ukrán karbovanec |
|  | Ugandai shilling (1966–1987) |
| one | Ugandai shilling (1966–1987) |
| other | Ugandai shilling (1966–1987) |
|  | ugandai shilling |
| one | ugandai shilling |
| other | ugandai shilling |
|  symbol | UGX |
|  | USA-dollár |
| one | USA-dollár |
| other | USA-dollár |
|  symbol | USD |
| narrow symbol | $ |
|  | USA dollár (következő napi) |
|  | USA dollár (aznapi) |
|  | Uruguayi peso en unidades indexadas |
| one | Uruguayi peso en unidades indexadas |
| other | Uruguayi peso en unidades indexadas |
|  | Uruguay-i peso (1975–1993) |
| one | Uruguayi peso (1975–1993) |
| other | Uruguayi peso (1975–1993) |
|  | uruguay-i peso |
| one | uruguayi peso |
| other | uruguayi peso |
|  symbol | UYU |
| narrow symbol | $ |
|  | üzbegisztáni szum |
| one | üzbegisztáni szum |
| other | üzbegisztáni szum |
|  symbol | UZS |
|  | Venezuelai bolivar (1871–2008) |
| one | Venezuelai bolivar (1871–2008) |
| other | Venezuelai bolivar (1871–2008) |
|  | venezuelai bolivar |
| one | venezuelai bolivar |
| other | venezuelai bolivar |
|  symbol | VEF |
| narrow symbol | Bs |
|  | vietnami dong |
| one | vietnami dong |
| other | vietnami dong |
|  symbol | VND |
| narrow symbol | ₫ |
|  | vanuatui vatu |
| one | vanuatui vatu |
| other | vanuatui vatu |
|  symbol | VUV |
|  | nyugat-szamoai tala |
| one | nyugat-szamoai tala |
| other | nyugat-szamoai tala |
|  symbol | WST |
|  | CFA frank BEAC |
| one | CFA frank BEAC |
| other | CFA frank BEAC |
|  symbol | FCFA |
|  | Ezüst |
|  | Arany |
|  | Európai kompozit egység |
| one | Európai kompozit egység |
| other | Európai kompozit egység |
|  | Európai monetáris egység |
| one | Európai monetáris egység |
| other | Európai monetáris egység |
|  | Európai kontó egység (XBC) |
| one | Európai kontó egység (XBC) |
| other | Európai kontó egység (XBC) |
|  | Európai kontó egység (XBD) |
| one | Európai kontó egység (XBD) |
| other | Európai kontó egység (XBD) |
|  | kelet-karibi dollár |
| one | kelet-karibi dollár |
| other | kelet-karibi dollár |
|  symbol | XCD |
| narrow symbol | $ |
|  | Special Drawing Rights |
|  | európai pénznemegység |
| one | Európai pénznemegység |
| other | Európai pénznemegység |
|  | Francia arany frank |
|  | Francia UIC-frank |
|  | CFA frank BCEAO |
| one | CFA frank BCEAO |
| other | CFA frank BCEAO |
|  symbol | CFA |
|  | palládium |
| one | Palládium |
| other | Palládium |
|  | csendes-óceáni valutaközösségi frank |
| one | csendes-óceáni valutaközösségi frank |
| other | csendes-óceáni valutaközösségi frank |
|  symbol | CFPF |
|  | platina |
| one | Platina |
| other | Platina |
|  | RINET tőke |
|  | Tesztelési pénznemkód |
|  | ismeretlen pénznem |
| one | (ismeretlen pénznem) |
| other | (ismeretlen pénznem) |
|  | Jemeni dínár |
|  | jemeni rial |
| one | jemeni rial |
| other | jemeni rial |
|  symbol | YER |
|  | Jugoszláv kemény dínár |
|  | Jugoszláv új dínár |
|  | Jugoszláv konvertibilis dínár |
|  | Dél-afrikai rand (pénzügyi) |
|  | dél-afrikai rand |
| one | dél-afrikai rand |
| other | dél-afrikai rand |
|  symbol | ZAR |
| narrow symbol | R |
|  | Zambiai kwacha (1968–2012) |
|  symbol | ZMK |
|  | zambiai kwacha |
| one | zambiai kwacha |
| other | zambiai kwacha |
|  symbol | ZMW |
| narrow symbol | ZK |
|  | Zairei új zaire |
|  | Zairei zaire |
|  | Zimbabwei dollár (1980–2008) |
| one | Zimbabwei dollár (1980–2008) |
| other | Zimbabwei dollár (1980–2008) |
|  | Zimbabwei dollár (2009) |
|  | Zimbabwei dollár (2008) |
| one | Zimbabwei dollár (2008) |
| other | Zimbabwei dollár (2008) |
Other stuff:
{0}+{0}–{1}
Examples:
| one example | A kosár tartalma: {0} X. Megveszi? |
| other example | A kosár tartalma: {0} X. Megveszi őket? |
Az {0}. lehetőségnél forduljon jobbra.A {0}. lehetőségnél forduljon jobbra.
## Units
| Code | Name |
| ---- | ---- |
| Compound pattern  | {0} per {1} |
| acceleration-g-force | ... |
|  | g gyorsulás |
| one | {0} g gyorsulás |
| other | {0} g gyorsulás |
| acceleration-meter-per-second-squared | ... |
|  | méter per másodpercnégyzet |
| one | {0} méter per másodpercnégyzet |
| other | {0} méter per másodpercnégyzet |
| angle-revolution | ... |
|  | fordulat |
| one | {0} fordulat |
| other | {0} fordulat |
| angle-radian | ... |
|  | radián |
| one | {0} radián |
| other | {0} radián |
| angle-degree | ... |
|  | fok |
| one | {0} fok |
| other | {0} fok |
| angle-arc-minute | ... |
|  | ívperc |
| one | {0} ívperc |
| other | {0} ívperc |
| angle-arc-second | ... |
|  | ívmásodperc |
| one | {0} ívmásodperc |
| other | {0} ívmásodperc |
| area-square-kilometer | ... |
|  | négyzetkilométer |
| one | {0} négyzetkilométer |
| other | {0} négyzetkilométer |
{0}/km²
| area-hectare | ... |
|  | hektár |
| one | {0} hektár |
| other | {0} hektár |
| area-square-meter | ... |
|  | négyzetméter |
| one | {0} négyzetméter |
| other | {0} négyzetméter |
{0}/négyzetméter
| area-square-centimeter | ... |
|  | négyzetcentiméter |
| one | {0} négyzetcentiméter |
| other | {0} négyzetcentiméter |
{0}/négyzetcentiméter
| area-square-mile | ... |
|  | négyzetmérföld |
| one | {0} négyzetmérföld |
| other | {0} négyzetmérföld |
{0}/négyzetmérföld
| area-acre | ... |
|  | hold |
| one | {0} hold |
| other | {0} hold |
| area-square-yard | ... |
|  | négyzetyard |
| one | {0} négyzetyard |
| other | {0} négyzetyard |
| area-square-foot | ... |
|  | négyzetláb |
| one | {0} négyzetláb |
| other | {0} négyzetláb |
| area-square-inch | ... |
|  | négyzethüvelyk |
| one | {0} négyzethüvelyk |
| other | {0} négyzethüvelyk |
{0}/négyzethüvelyk
| concentr-karat | ... |
|  | karát |
| one | {0} karát |
| other | {0} karát |
| concentr-milligram-per-deciliter | ... |
|  | milligramm/deciliter |
| one | {0} milligramm/deciliter |
| other | {0} milligramm/deciliter |
| concentr-millimole-per-liter | ... |
|  | millimól/liter |
| one | {0} millimól/liter |
| other | {0} millimól/liter |
| concentr-part-per-million | ... |
|  | részecske/millió |
| one | {0} részecske/millió |
| other | {0} részecske/millió |
| consumption-liter-per-kilometer | ... |
|  | liter per kilométer |
| one | {0} liter per kilométer |
| other | {0} liter per kilométer |
| consumption-liter-per-100kilometers | ... |
|  | liter/100 km |
| one | {0} liter/100 km |
| other | {0} liter/100 km |
| consumption-mile-per-gallon | ... |
|  | mérföld per gallon |
| one | {0} mérföld per gallon |
| other | {0} mérföld per gallon |
| consumption-mile-per-gallon-imperial | ... |
|  | mérföld/birodalmi gallon |
| one | {0} mérföld/birodalmi gallon |
| other | {0} mérföld/birodalmi gallon |
| digital-terabyte | ... |
|  | terabájt |
| one | {0} terabájt |
| other | {0} terabájt |
| digital-terabit | ... |
|  | terabit |
| one | {0} terabit |
| other | {0} terabit |
| digital-gigabyte | ... |
|  | gigabájt |
| one | {0} gigabájt |
| other | {0} gigabájt |
| digital-gigabit | ... |
|  | gigabit |
| one | {0} gigabit |
| other | {0} gigabit |
| digital-megabyte | ... |
|  | megabájt |
| one | {0} megabájt |
| other | {0} megabájt |
| digital-megabit | ... |
|  | megabit |
| one | {0} megabit |
| other | {0} megabit |
| digital-kilobyte | ... |
|  | kilobájt |
| one | {0} kilobájt |
| other | {0} kilobájt |
| digital-kilobit | ... |
|  | kilobit |
| one | {0} kilobit |
| other | {0} kilobit |
| digital-byte | ... |
|  | bájt |
| one | {0} bájt |
| other | {0} bájt |
| digital-bit | ... |
|  | bit |
| one | {0} bit |
| other | {0} bit |
| duration-century | ... |
|  | évszázad |
| one | {0} évszázad |
| other | {0} évszázad |
| duration-year | ... |
|  | év |
| one | {0} év |
| other | {0} év |
{0}/év
| duration-month | ... |
|  | hónap |
| one | {0} hónap |
| other | {0} hónap |
{0}/hónap
| duration-week | ... |
|  | hét |
| one | {0} hét |
| other | {0} hét |
{0}/hét
| duration-day | ... |
|  | nap |
| one | {0} nap |
| other | {0} nap |
{0}/nap
| duration-hour | ... |
|  | óra |
| one | {0} óra |
| other | {0} óra |
{0}/óra
| duration-minute | ... |
|  | perc |
| one | {0} perc |
| other | {0} perc |
{0}/perc
| duration-second | ... |
|  | másodperc |
| one | {0} másodperc |
| other | {0} másodperc |
{0}/másodperc
| duration-millisecond | ... |
|  | ezredmásodperc |
| one | {0} ezredmásodperc |
| other | {0} ezredmásodperc |
| duration-microsecond | ... |
|  | mikroszekundum |
| one | {0} mikroszekundum |
| other | {0} mikroszekundum |
| duration-nanosecond | ... |
|  | nanoszekundum |
| one | {0} nanoszekundum |
| other | {0} nanoszekundum |
| electric-ampere | ... |
|  | amper |
| one | {0} amper |
| other | {0} amper |
| electric-milliampere | ... |
|  | milliamper |
| one | {0} milliamper |
| other | {0} milliamper |
| electric-ohm | ... |
|  | ohm |
| one | {0} ohm |
| other | {0} ohm |
| electric-volt | ... |
|  | volt |
| one | {0} volt |
| other | {0} volt |
| energy-kilocalorie | ... |
|  | kilokalória |
| one | {0} kilokalória |
| other | {0} kilokalória |
| energy-calorie | ... |
|  | kalória |
| one | {0} kalória |
| other | {0} kalória |
| energy-foodcalorie | ... |
|  | kalória |
| one | {0} kalória |
| other | {0} kalória |
| energy-kilojoule | ... |
|  | kilojoule |
| one | {0} kilojoule |
| other | {0} kilojoule |
| energy-joule | ... |
|  | joule |
| one | {0} joule |
| other | {0} joule |
| energy-kilowatt-hour | ... |
|  | kilowattóra |
| one | {0} kilowattóra |
| other | {0} kilowattóra |
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
|  | kilométer |
| one | {0} kilométer |
| other | {0} kilométer |
{0}/kilométer
| length-meter | ... |
|  | méter |
| one | {0} méter |
| other | {0} méter |
{0}/méter
| length-decimeter | ... |
|  | deciméter |
| one | {0} deciméter |
| other | {0} deciméter |
| length-centimeter | ... |
|  | centiméter |
| one | {0} centiméter |
| other | {0} centiméter |
{0}/centimeter
| length-millimeter | ... |
|  | milliméter |
| one | {0} milliméter |
| other | {0} milliméter |
| length-micrometer | ... |
|  | mikrométer |
| one | {0} mikrométer |
| other | {0} mikrométer |
| length-nanometer | ... |
|  | nanométer |
| one | {0} nanométer |
| other | {0} nanométer |
| length-picometer | ... |
|  | pikométer |
| one | {0} pikométer |
| other | {0} pikométer |
| length-mile | ... |
|  | mérföld |
| one | {0} mérföld |
| other | {0} mérföld |
| length-yard | ... |
|  | yard |
| one | {0} yard |
| other | {0} yard |
| length-foot | ... |
|  | láb |
| one | {0} láb |
| other | {0} láb |
{0}/láb
| length-inch | ... |
|  | hüvelyk |
| one | {0} hüvelyk |
| other | {0} hüvelyk |
{0}/hüvelyk
| length-parsec | ... |
|  | parszek |
| one | {0} parszek |
| other | {0} parszek |
| length-light-year | ... |
|  | fényév |
| one | {0} fényév |
| other | {0} fényév |
| length-astronomical-unit | ... |
|  | csillagászati egység |
| one | {0} csillagászati egység |
| other | {0} csillagászati egység |
| length-nautical-mile | ... |
|  | tengeri mérföld |
| one | {0} tengeri mérföld |
| other | {0} tengeri mérföld |
| length-mile-scandinavian | ... |
|  | svéd mérföld |
| one | {0} svéd mérföld |
| other | {0} svéd mérföld |
| length-point | ... |
|  | pont |
| one | {0} pont |
| other | {0} pont |
| light-lux | ... |
|  | lux |
| one | {0} lux |
| other | {0} lux |
| mass-metric-ton | ... |
|  | metrikus tonna |
| one | {0} metrikus tonna |
| other | {0} metrikus tonna |
| mass-kilogram | ... |
|  | kilogramm |
| one | {0} kilogramm |
| other | {0} kilogramm |
{0}/kilogramm
| mass-gram | ... |
|  | gramm |
| one | {0} gramm |
| other | {0} gramm |
{0}/gramm
| mass-milligram | ... |
|  | milligramm |
| one | {0} milligramm |
| other | {0} milligramm |
| mass-microgram | ... |
|  | mikrogramm |
| one | {0} mikrogramm |
| other | {0} mikrogramm |
| mass-ton | ... |
|  | tonna |
| one | {0} tonna |
| other | {0} tonna |
| mass-pound | ... |
|  | font |
| one | {0} font |
| other | {0} font |
{0}/font
| mass-ounce | ... |
|  | uncia |
| one | {0} uncia |
| other | {0} uncia |
{0}/uncia
| mass-ounce-troy | ... |
|  | troy uncia |
| one | {0} troy uncia |
| other | {0} troy uncia |
| mass-carat | ... |
|  | karát |
| one | {0} karát |
| other | {0} karát |
| power-gigawatt | ... |
|  | gigawatt |
| one | {0} gigawatt |
| other | {0} gigawatt |
| power-megawatt | ... |
|  | megawatt |
| one | {0} megawatt |
| other | {0} megawatt |
| power-kilowatt | ... |
|  | kilowatt |
| one | {0} kilowatt |
| other | {0} kilowatt |
| power-watt | ... |
|  | watt |
| one | {0} watt |
| other | {0} watt |
| power-milliwatt | ... |
|  | milliwatt |
| one | {0} milliwatt |
| other | {0} milliwatt |
| power-horsepower | ... |
|  | lóerő |
| one | {0} lóerő |
| other | {0} lóerő |
| pressure-hectopascal | ... |
|  | hektopascal |
| one | {0} hektopascal |
| other | {0} hektopascal |
| pressure-millimeter-of-mercury | ... |
|  | mm Hg |
| one | {0} higanymilliméter |
| other | {0} higanymilliméter |
| pressure-pound-per-square-inch | ... |
|  | font per négyzethüvelyk |
| one | {0} font per négyzethüvelyk |
| other | {0} font per négyzethüvelyk |
| pressure-inch-hg | ... |
|  | higanyhüvelyk |
| one | {0} higanyhüvelyk |
| other | {0} higanyhüvelyk |
| pressure-millibar | ... |
|  | millibar |
| one | {0} millibar |
| other | {0} millibar |
| speed-kilometer-per-hour | ... |
|  | kilométer per óra |
| one | {0} kilométer per óra |
| other | {0} kilométer per óra |
| speed-meter-per-second | ... |
|  | méter per másodperc |
| one | {0} méter per másodperc |
| other | {0} méter per másodperc |
| speed-mile-per-hour | ... |
|  | mérföld per óra |
| one | {0} mérföld per óra |
| other | {0} mérföld per óra |
| speed-knot | ... |
|  | csomó |
| one | {0} csomó |
| other | {0} csomó |
| temperature-generic | ... |
|  | ° |
| one | {0}° |
| other | {0}° |
| temperature-celsius | ... |
|  | Celsius-fok |
| one | {0} Celsius-fok |
| other | {0} Celsius-fok |
| temperature-fahrenheit | ... |
|  | Fahrenheit-fok |
| one | {0} Fahrenheit-fok |
| other | {0} Fahrenheit-fok |
| temperature-kelvin | ... |
|  | kelvin |
| one | {0} kelvin |
| other | {0} kelvin |
| volume-cubic-kilometer | ... |
|  | köbkilométer |
| one | {0} köbkilométer |
| other | {0} köbkilométer |
| volume-cubic-meter | ... |
|  | köbméter |
| one | {0} köbméter |
| other | {0} köbméter |
{0}/köbméter
| volume-cubic-centimeter | ... |
|  | köbcentiméter |
| one | {0} köbcentiméter |
| other | {0} köbcentiméter |
{0}/köbcentiméter
| volume-cubic-mile | ... |
|  | köbmérföld |
| one | {0} köbmérföld |
| other | {0} köbmérföld |
| volume-cubic-yard | ... |
|  | köbyard |
| one | {0} köbyard |
| other | {0} köbyard |
| volume-cubic-foot | ... |
|  | köbláb |
| one | {0} köbláb |
| other | {0} köbláb |
| volume-cubic-inch | ... |
|  | köbhüvelyk |
| one | {0} köbhüvelyk |
| other | {0} köbhüvelyk |
| volume-megaliter | ... |
|  | megaliter |
| one | {0} megaliter |
| other | {0} megaliter |
| volume-hectoliter | ... |
|  | hektoliter |
| one | {0} hektoliter |
| other | {0} hektoliter |
| volume-liter | ... |
|  | liter |
| one | {0} liter |
| other | {0} liter |
{0}/liter
| volume-deciliter | ... |
|  | deciliter |
| one | {0} deciliter |
| other | {0} deciliter |
| volume-centiliter | ... |
|  | centiliter |
| one | {0} centiliter |
| other | {0} centiliter |
| volume-milliliter | ... |
|  | milliliter |
| one | {0} milliliter |
| other | {0} milliliter |
| volume-pint-metric | ... |
|  | metrikus pint |
| one | {0} metrikus pint |
| other | {0} metrikus pint |
| volume-cup-metric | ... |
|  | bögre |
| one | {0} bögre |
| other | {0} bögre |
| volume-acre-foot | ... |
|  | hold-láb |
| one | {0} hold-láb |
| other | {0} hold-láb |
| volume-gallon | ... |
|  | gallon |
| one | {0} gallon |
| other | {0} gallon |
{0}/gallon
| volume-gallon-imperial | ... |
|  | birodalmi gallon |
| one | {0} birodalmi gallon |
| other | {0} birodalmi gallon |
{0}/birodalmi gallon
| volume-quart | ... |
|  | quart |
| one | {0} quart |
| other | {0} quart |
| volume-pint | ... |
|  | pint |
| one | {0} pint |
| other | {0} pint |
| volume-cup | ... |
|  | csésze |
| one | {0} csésze |
| other | {0} csésze |
| volume-fluid-ounce | ... |
|  | folyadékuncia |
| one | {0} folyadékuncia |
| other | {0} folyadékuncia |
| volume-tablespoon | ... |
|  | evőkanál |
| one | {0} evőkanál |
| other | {0} evőkanál |
| volume-teaspoon | ... |
|  | kávéskanál |
| one | {0} kávéskanál |
| other | {0} kávéskanál |
{0} K{0} É{0} D{0} Ny
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | g gyorsulás |
| one | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
|  | m/s² |
| one | {0} m/s² |
| other | {0} m/s² |
| angle-revolution | ... |
|  | ford. |
| one | {0} ford. |
| other | {0} ford. |
| angle-radian | ... |
|  | rad |
| one | {0} rad |
| other | {0} rad |
| angle-degree | ... |
|  | fok |
| one | {0} fok |
| other | {0} fok |
| angle-arc-minute | ... |
|  | ívperc |
| one | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | ívmásodperc |
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
|  | kh |
| one | {0} kh |
| other | {0} kh |
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
|  | kt |
| one | {0} kt |
| other | {0} kt |
| concentr-milligram-per-deciliter | ... |
|  | mg/dl |
| one | {0} mg/dl |
| other | {0} mg/dl |
| concentr-millimole-per-liter | ... |
|  | millimól/liter |
| one | {0} mmol/l |
| other | {0} mmol/l |
| concentr-part-per-million | ... |
|  | részecske/millió |
| one | {0} ppm |
| other | {0} ppm |
| consumption-liter-per-kilometer | ... |
|  | l/km |
| one | {0} l/km |
| other | {0} l/km |
| consumption-liter-per-100kilometers | ... |
|  | l/100 km |
| one | {0} l/100 km |
| other | {0} l/100km |
| consumption-mile-per-gallon | ... |
|  | mpg |
| one | {0} mpg |
| other | {0} mpg |
| consumption-mile-per-gallon-imperial | ... |
|  | mérföld/bir. gallon |
| one | {0} mpg bir. |
| other | {0} mpg bir. |
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
|  | bájt |
| one | {0} bájt |
| other | {0} bájt |
| digital-bit | ... |
|  | bit |
| one | {0} bit |
| other | {0} bit |
| duration-century | ... |
|  | sz. |
| one | {0} sz. |
| other | {0} sz. |
| duration-year | ... |
|  | év |
| one | {0} év |
| other | {0} év |
{0}/év
| duration-month | ... |
|  | hónap |
| one | {0} hónap |
| other | {0} hónap |
{0}/hó
| duration-week | ... |
|  | hét |
| one | {0} hét |
| other | {0} hét |
{0}/hét
| duration-day | ... |
|  | nap |
| one | {0} nap |
| other | {0} nap |
{0}/nap
| duration-hour | ... |
|  | h |
| one | {0} h |
| other | {0} h |
{0}/h
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
|  | cal |
| one | {0} cal |
| other | {0} cal |
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
|  | mf |
| one | {0} mf |
| other | {0} mf |
| length-yard | ... |
|  | yd |
| one | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | láb |
| one | {0} láb |
| other | {0} láb |
{0}/láb
| length-inch | ... |
|  | hüvelyk |
| one | {0} hüvelyk |
| other | {0} hüvelyk |
{0}/in
| length-parsec | ... |
|  | pc |
| one | {0} pc |
| other | {0} pc |
| length-light-year | ... |
|  | fényév |
| one | {0} fényév |
| other | {0} fényév |
| length-astronomical-unit | ... |
|  | CsE |
| one | {0} CsE |
| other | {0} CsE |
| length-nautical-mile | ... |
|  | nmi |
| one | {0} nmi |
| other | {0} nmi |
| length-mile-scandinavian | ... |
|  | mil |
| one | {0} mil |
| other | {0} mil |
| length-point | ... |
|  | pont |
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
|  | gram |
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
|  | tn |
| one | {0} tn |
| other | {0} tn |
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
|  | Kt |
| one | {0} Kt |
| other | {0} Kt |
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
|  | LE |
| one | {0} LE |
| other | {0} LE |
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
| one | {0} mb |
| other | {0} mb |
| speed-kilometer-per-hour | ... |
|  | km/h |
| one | {0} km/h |
| other | {0} km/h |
| speed-meter-per-second | ... |
|  | m/s |
| one | {0} m/s |
| other | {0} m/s |
| speed-mile-per-hour | ... |
|  | mph |
| one | {0} mph |
| other | {0} mph |
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
|  | mpt |
| one | {0} mpt |
| other | {0} mpt |
| volume-cup-metric | ... |
|  | bg |
| one | {0} bg |
| other | {0} bg |
| volume-acre-foot | ... |
|  | ac ft |
| one | {0} ac ft |
| other | {0} ac ft |
| volume-gallon | ... |
|  | gal |
| one | {0} gal |
| other | {0} gal |
{0}/gal
| volume-gallon-imperial | ... |
|  | bir. gal |
| one | {0} bir. gal |
| other | {0} bir. gal |
{0}/bir. gal
| volume-quart | ... |
|  | qt |
| one | {0} qt |
| other | {0} qt |
| volume-pint | ... |
|  | pt |
| one | {0} pt |
| other | {0} pt |
| volume-cup | ... |
|  | cs. |
| one | {0} cs. |
| other | {0} cs. |
| volume-fluid-ounce | ... |
|  | fl oz |
| one | {0} fl oz |
| other | {0} fl oz |
| volume-tablespoon | ... |
|  | ek. |
| one | {0} ek. |
| other | {0} ek. |
| volume-teaspoon | ... |
|  | kk. |
| one | {0} kk. |
| other | {0} kk. |
{0} K{0} É{0} D{0} Ny
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
| one | {0} G |
| other | {0} G |
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
| one | {0} ac |
| other | {0} ac |
| area-square-foot | ... |
| one | {0} ft² |
| other | {0} ft² |
| consumption-liter-per-100kilometers | ... |
|  | l/100 km |
| one | {0} l/100 km |
| other | {0} l/100 km |
| duration-century | ... |
|  | sz. |
| one | {0} sz. |
| other | {0} sz. |
| duration-year | ... |
|  | év |
| one | {0} év |
| other | {0} év |
| duration-month | ... |
|  | hónap |
| one | {0} h. |
| other | {0} h. |
| duration-week | ... |
|  | hét |
| one | {0} hét |
| other | {0} hét |
| duration-day | ... |
|  | nap |
| one | {0} nap |
| other | {0} nap |
{0}/nap
| duration-hour | ... |
|  | h |
| one | {0} h |
| other | {0} h |
{0}/h
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
| length-picometer | ... |
| one | {0} pm |
| other | {0} pm |
| length-mile | ... |
|  | mf |
| one | {0} mf |
| other | {0} mf |
| length-yard | ... |
|  | yd |
| one | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | láb |
| one | {0} láb |
| other | {0} láb |
{0}/láb
| length-inch | ... |
|  | hüvelyk |
| one | {0} hüvelyk |
| other | {0} hüvelyk |
{0}/in
| length-light-year | ... |
| one | {0} fényév |
| other | {0} fényév |
| length-mile-scandinavian | ... |
|  | mil |
| one | {0} mil |
| other | {0} mil |
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
| mass-stone | ... |
|  | st |
| one | {0} st |
| other | {0} st |
| mass-pound | ... |
|  | lb |
| one | {0} font |
| other | {0} font |
{0}/lb
| mass-ounce | ... |
|  | oz |
| one | {0} uncia |
| other | {0} uncia |
{0}/oz
| power-kilowatt | ... |
| one | {0} kW |
| other | {0} kW |
| power-watt | ... |
| one | {0} W |
| other | {0} W |
| power-horsepower | ... |
| one | {0} LE |
| other | {0} LE |
| pressure-hectopascal | ... |
|  | hPa |
| one | {0} hPa |
| other | {0} hPa |
| pressure-millimeter-of-mercury | ... |
|  | Hgmm |
| one | {0} Hgmm |
| other | {0} Hgmm |
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
| one | {0} mb |
| other | {0} mb |
| speed-kilometer-per-hour | ... |
|  | km/h |
| one | {0} km/h |
| other | {0} km/h |
| speed-meter-per-second | ... |
|  | m/s |
| one | {0} m/s |
| other | {0} m/s |
| speed-mile-per-hour | ... |
|  | mph |
| one | {0} mph |
| other | {0} mph |
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
|  | l |
| one | {0} l |
| other | {0} l |
{0} K{0} É{0} D{0} Nyh:mmh:mm:ssm:ss
## Lists
| List type | Patterns |
|  | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} és {1} |
| 2 | {0} és {1} |
| or | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} vagy {1} |
| 2 | {0} vagy {1} |
| standard-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} és {1} |
| 2 | {0} és {1} |
| unit | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} és {1} |
| 2 | {0} és {1} |
| unit-narrow | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} és {1} |
| 2 | {0} és {1} |
| unit-short | ... |
| start | {0}, {1} |
| middle | {0}, {1} |
| end | {0} és {1} |
| 2 | {0} és {1} |
## POSIX
igen:inem:n
## Character sets
| Set | Name |
| --- | ---- |
| all | {0} – összes |
| category-list | {0}: {1} |
| compatibility | {0} – kompatibilitás |
| enclosed | {0} – zárt |
| extended | {0} – kibővített |
| historic | {0} – történelmi |
| miscellaneous | {0} – vegyes |
| other | {0} – egyéb |
| scripts | kézírások – {0} |
| onestrokes | {0} vonás |
| otherstrokes | {0} vonás |
| activities | tevékenység |
| african_scripts | afrikai írásrendszerek |
| american_scripts | amerikai írásrendszerek |
| animal | állat |
| animals_nature | állatok és természet |
| arrows | nyilak |
| body | test |
| box_drawing | grafikus karakterek |
| braille | braille |
| building | épület |
| bullets_stars | felsorolásjelek és csillagok |
| consonantal_jamo | mássalhangzói jamo |
| currency_symbols | pénznemek szimbólumai |
| dash_connector | gondolatjel/kötőjel |
| digits | számjegyek |
| dingbats | dingbatok |
| divination_symbols | jóslási jelek |
| downwards_arrows | lefelé mutató nyilak |
| downwards_upwards_arrows | felfelé-lefelé mutató nyilak |
| east_asian_scripts | kelet-ázsiai írásrendszerek |
| emoji | emodzsi |
| european_scripts | európai írásrendszerek |
| female | nő |
| flag | zászló |
| flags | zászlók |
| food_drink | étel-ital |
| format | formátum |
| format_whitespace | formátum és térköz |
| full_width_form_variant | teljes szélességű formavariációk |
| geometric_shapes | geometriai alakzatok |
| half_width_form_variant | félszélességű formavariációk |
| han_characters | han karakterek |
| han_radicals | han gyökök |
| hanja | handzsa |
| hanzi_simplified | hanzi (egyszerűsített) |
| hanzi_traditional | hanzi (hagyományos) |
| heart | szív |
| historic_scripts | történelmi írásrendszerek |
| ideographic_desc_characters | ideografikus leíró karakterek |
| japanese_kana | japán kana |
| kanbun | kanbun |
| kanji | kandzsi |
| keycap | gombfej |
| leftwards_arrows | balra mutató nyilak |
| leftwards_rightwards_arrows | jobbra-balra mutató nyilak |
| letterlike_symbols | betűszerű szimbólumok |
| limited_use | korlátozott használat |
| male | férfi |
| math_symbols | matematikai szimbólumok |
| middle_eastern_scripts | matematikai szimbólumok |
| miscellaneous | egyéb |
| modern_scripts | modern írásrendszerek |
| modifier | módosító |
| musical_symbols | zenei szimbólumok |
| nature | természet |
| nonspacing | szóközt nem alkalmazó |
| numbers | számok |
| objects | tárgyak |
| other | egyéb |
| paired | párosított |
| person | ember |
| phonetic_alphabet | fonetikus ábécé |
| pictographs | piktogramok |
| place | hely |
| plant | növény |
| punctuation | írásjel |
| rightwards_arrows | jobbra mutató nyilak |
| sign_standard_symbols | jelek/normál szimbólumok |
| small_form_variant | kis formavariánsok |
| smiley | hangulatjel |
| smileys_people | hangulatjelek és emberek |
| south_asian_scripts | dél-ázsiai írásrendszerek |
| southeast_asian_scripts | délkelet-ázsiai írásrendszerek |
| spacing | szóközt alkalmazó |
| sport | sport |
| symbols | szimbólumok |
| technical_symbols | műszaki szimbólumok |
| tone_marks | hangsúlyjelek |
| travel | utazás |
| travel_places | utazás és helyek |
| upwards_arrows | felfelé mutató nyilak |
| variant_forms | variánsformák |
| vocalic_jamo | magánhangzói jamo |
| weather | időjárás |
| western_asian_scripts | nyugat-ázsiai írásrendszerek |
| whitespace | térköz |
## Font stuff
| Font feature | Name |
| "axis" ital | dőlt |
| "axis" opsz | optikai méret |
| "axis" slnt | dőlés |
| "axis" wdth | szélesség |
| "axis" wght | súly |
| "style" ital1 | kurzív |
| "style" opsz18 | címstílus |
| "style" opsz72 | kijelző |
| "style" opsz144 | poszter |
| "style" slnt-12 | hátrafelé döntött |
| "style" slnt0 | függőleges |
| "style" slnt12 | dőlt |
| "style" slnt24 | extra döntött |
| "style" wdth50 | ultra sűrített |
| "style" wdth50 | ultra tömörített |
| "style" wdth62.5 | extra sűrített |
| "style" wdth62.5 | extra tömörített |
| "style" wdth62.5 | extra szűk |
| "style" wdth75 | sűrített |
| "style" wdth75 | tömörített |
| "style" wdth75 | szűk |
| "style" wdth87.5 | félig sűrített |
| "style" wdth100 | normál |
| "style" wdth112.5 | félig széthúzott |
| "style" wdth112.5 | félig kibővített |
| "style" wdth125 | széthúzva |
| "style" wdth125 | kiterjesztett |
| "style" wdth125 | széles |
| "style" wdth150 | extra széthúzott |
| "style" wdth150 | extra kibővített |
| "style" wdth150 | extra széles |
| "style" wdth200 | ultra széthúzott |
| "style" wdth200 | ultra kibővített |
| "style" wght100 | vékony |
| "style" wght200 | extra vékony |
| "style" wght200 | ultra vékony |
| "style" wght300 | vékony |
| "style" wght350 | félig vékony |
| "style" wght380 | könyv |
| "style" wght400 | szabályos |
| "style" wght500 | közepes |
| "style" wght600 | közepesen félkövér |
| "style" wght700 | félkövér |
| "style" wght800 | extra félkövér |
| "style" wght800 | ultra félkövér |
| "style" wght900 | fekete |
| "style" wght900 | nehéz |
| "style" wght950 | extra fekete |
| "style" wght950 | ultra vastag |
| "style" wght950 | ultra fekete |
| "feature" afrc | függőleges törtek |
| "feature" cpsp | nagybetűtérköz |
| "feature" dlig | kiegészítő ligatúrák |
| "feature" frac | átlós törtek |
| "feature" lnum | egyenletes számok |
| "feature" onum | régi stílusú ábrák |
| "feature" ordn | sorszámok |
| "feature" pnum | arányos számok |
| "feature" smcp | kiskapitálisok |
| "feature" tnum | rögzített szélességű számok |
| "feature" zero | áthúzott nulla |
