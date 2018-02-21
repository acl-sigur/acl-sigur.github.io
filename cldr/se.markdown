---
layout: default
title: "CLDR Northern Saami (via LDML2markdown)"
---

## CLDR core data for Northern Saami

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[a á b c č d đ e f g h i j k l m n ŋ o p r s š t ŧ u v z ž]` |
| auxiliary characters | `[à ç é è í ń ñ ó ò q ú w x y ü ø æ å ä ã ö]` |
| index characters | `[A Á B C Č D Đ E É F G H I J K L M N Ŋ O P Q R S Š T Ŧ U V W X Y Z Ž Ø Æ Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| Country Data and Default Content | se_NO |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | Northern Saami is already written in latin script |

### Casing

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
				[import se-u-co-standard]

```

#### standard

```
&[before 1]b<á<<<Á
&[before 1]d<č # fallback: ch
<<<Č<ʒ # Skolt Sami, not "index" for other Sami languages
<<<Ʒ<ǯ # Skolt Sami, not "index" for other Sami languages
<<<Ǯ
&[before 1]e<đ # fallback: dh
<<<Đ<<ð # Icelandic uses a "eth"...
<<<Ð
&[before 1]h<ǧ # Skolt Sami, not "index" for other Sami languages
<<<Ǧ<ǥ # Skolt Sami, not "index" for other Sami languages
<<<Ǥ
&[before 1]l<ǩ # Skolt Sami, not "index" for other Sami languages
<<<Ǩ
&[before 1]o<ŋ # fallback: ng
<<<Ŋ<<ń # Lule Sami (alternative "eng")
<<<Ń<<ñ # Lule Sami (alternative "eng")
<<<Ñ
&[before 1]t<š # fallback: sh
<<<Š
&[before 1]u<ŧ # fallback: th
<<<Ŧ<<þ # Icelandic uses thorn...
<<<Þ
&y<<ü # compat. for Norwegian/Swedish
<<<Ü<<ű # considered a variant of ü
<<<Ű
&[before 1]ǀ # LATIN LETTER DENTAL CLICK
<ž # fallback: zh
<<<Ž<ø # compat. for Norwegian
<<<Ø<<œ # considered a variant of ø (and ö...)
<<<Œ<æ # compat. for Norwegian
<<<Æ<å # compat. for Norwegian/Swedish
<<<Å<<ȧ # considered a variant of å
<<<Ȧ<ä # compat. for Swedish
<<<Ä<<ã # considered a variant of ä
<<<Ã<ö # compat. for Swedish
<<<Ö<<ő # considered a variant of ö
<<<Ő<<õ # considered a variant of ö
<<<Õ<<ô # while pronounced as å in French, it is used for some Swedish dialects for "thick ö"
<<<Ô<<ǫ # variant from old Icelandic/old Norse of a vowel now pronounced like ö
<<<Ǫ
```

## CLDR minimal data for Northern Saami

**Needed soon after submitting new locale**.

### Required date-time formats

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month 1 | ođđj |
| month 2 | guov |
| month 3 | njuk |
| month 4 | cuo |
| month 5 | mies |
| month 6 | geas |
| month 7 | suoi |
| month 8 | borg |
| month 9 | čakč |
| month 10 | golg |
| month 11 | skáb |
| month 12 | juov |
| month 1 | O |
| month 2 | G |
| month 3 | N |
| month 4 | C |
| month 5 | M |
| month 6 | G |
| month 7 | S |
| month 8 | B |
| month 9 | Č |
| month 10 | G |
| month 11 | S |
| month 12 | J |
| month 1 | ođđajagemánnu |
| month 2 | guovvamánnu |
| month 3 | njukčamánnu |
| month 4 | cuoŋománnu |
| month 5 | miessemánnu |
| month 6 | geassemánnu |
| month 7 | suoidnemánnu |
| month 8 | borgemánnu |
| month 9 | čakčamánnu |
| month 10 | golggotmánnu |
| month 11 | skábmamánnu |
| month 12 | juovlamánnu |
| month 1 | ođđj |
| month 2 | guov |
| month 3 | njuk |
| month 4 | cuo |
| month 5 | mies |
| month 6 | geas |
| month 7 | suoi |
| month 8 | borg |
| month 9 | čakč |
| month 10 | golg |
| month 11 | skáb |
| month 12 | juov |
| month 1 | O |
| month 2 | G |
| month 3 | N |
| month 4 | C |
| month 5 | M |
| month 6 | G |
| month 7 | S |
| month 8 | B |
| month 9 | Č |
| month 10 | G |
| month 11 | S |
| month 12 | J |
| month 1 | ođđajagemánnu |
| month 2 | guovvamánnu |
| month 3 | njukčamánnu |
| month 4 | cuoŋománnu |
| month 5 | miessemánnu |
| month 6 | geassemánnu |
| month 7 | suoidnemánnu |
| month 8 | borgemánnu |
| month 9 | čakčamánnu |
| month 10 | golggotmánnu |
| month 11 | skábmamánnu |
| month 12 | juovlamánnu |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
https://github.com/acl-sigur/acl-sigur.github.io/blob/master/cldr/myv.markdown| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | G |
| (week)day thu | D |
| (week)day fri | B |
| (week)day sat | L |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | sotnabeaivi |
| (week)day mon | vuossárga |
| (week)day tue | maŋŋebárga |
| (week)day wed | gaskavahkku |
| (week)day thu | duorasdat |
| (week)day fri | bearjadat |
| (week)day sat | lávvardat |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | G |
| (week)day thu | D |
| (week)day fri | B |
| (week)day sat | L |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | sotnabeaivi |
| (week)day mon | vuossárga |
| (week)day tue | maŋŋebárga |
| (week)day wed | gaskavahkku |
| (week)day thu | duorasdat |
| (week)day fri | bearjadat |
| (week)day sat | lávvardat |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | iđitbeaivet |
| period of day pm | eahketbeaivet |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | iđitbeaivi |
| period of day pm | eahketbeaivi |
| era | ovdal Kristtusa |
| era | BCE |
| era | maŋŋel Kristtusa |
| era | CE |
| era | o.Kr. |
| era | BCE |
| era | m.Kr. |
| era | CE |
| era | ooá |
| era | oá |
| date format | `y MMMM d, EEEE` |
| date format | `y MMMM d` |
| date format | `y MMM d` |
| date format | `y-MM-dd` |
| time format | `HH:mm:ss zzzz` |
| time format | `HH:mm:ss z` |
| time format | `HH:mm:ss` |
| time format | `HH:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `d, E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y` |
| date format `GyMMM` | `G y MMM` |
| date format `GyMMMd` | `G y MMM d` |
| date format `GyMMMEd` | `G y MMM d, E` |
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
| date format `Md` | `MM-dd` |
| date format `MEd` | `MM-dd, E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `MMM d, E` |
| date format `MMMMd` | `MMMM d` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `y-MM` |
| date format `yMd` | `y-MM-dd` |
| date format `yMEd` | `y-MM-dd, E` |
| date format `yMMM` | `y MMM` |
| date format `yMMMd` | `y MMM d` |
| date format `yMMMEd` | `y MMM d, E` |
| date format `yMMMM` | `y MMMM` |
| date format `yQQQ` | `y QQQ` |
| date format `yQQQQ` | `y QQQQ` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
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
| interval format `Md` | `MM-dd – MM-ddMM-dd – MM-dd` |
| interval format `MEd` | `MM-dd, E – MM-dd, EMM-dd, E – MM-dd, E` |
| interval format `MMM` | `LLL–LLL` |
| interval format `MMMd` | `MMM d–dMMM d – MMM d` |
| interval format `MMMEd` | `MMM d, E – MMM d, EMMM d, E – MMM d, E` |
| interval format `y` | `y–y` |
| interval format `yM` | `y-MM – y-MMy-MM – y-MM` |
| interval format `yMd` | `y-MM-dd – y-MM-ddy-MM-dd – y-MM-ddy-MM-dd – y-MM-dd` |
| interval format `yMEd` | `y-MM-dd, E – y-MM-dd, Ey-MM-dd, E – y-MM-dd, Ey-MM-dd, E – y-MM-dd, E` |
| interval format `yMMM` | `y MMM–MMMy MMM – y MMM` |
| interval format `yMMMd` | `y MMM d–dy MMM d – MMM dy MMM d – y MMM d` |
| interval format `yMMMEd` | `y MMM d, E – MMM d, Ey MMM d, E – MMM d, Ey MMM d, E – y MMM d, E` |
| interval format `yMMMM` | `y MMMM–MMMMy MMMM – y MMMM` |

### Important names in language

Language:

| `se` | davvisámegiella |

Country or territory:

| `NO` | Norga |

Currency:

|  | euro |
| one | euro |
| two | euro |
| other | euro |
|  symbol | € |
| narrow symbol | € |

### Datetime patterns

### Number formats

| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | ·10^ |
| Superscripting Exponent | · |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | ¤¤¤ |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

The place names to translate must be in the lists here:

### Timezone patterns

| Hours from UTC | +HH:mm;−HH:mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional | {0} áigi |
| regional | {0} geassiáigi |
| regional | {0} dábálašáigi |
| fallback | {0} ({1}) |

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
| `calendar` | kaleandar |
| `collation` | ortnet |
| `currency` | valuhtta |
| `numbers` | numerála |

### Some time intervals

???

## More (all) CLDR data for $language

While not strictly needed is all used by software and stuff:
identity:
```
$Revision: 13869 $se
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
| `ace` | acehgiella |
| `af` | afrikánsagiella |
| `an` | aragoniagiella |
| `ang` | boares eaŋgalasgiella |
| `ar` | arábagiella |
| `ast` | asturiagiella |
| `be` | vilges-ruoššagiella |
| `bg` | bulgáriagiella |
| `bn` | bengalgiella |
| `bo` | tibetagiella |
| `br` | bretonagiella |
| `bs` | bosniagiella |
| `ca` | katalánagiella |
| `chm` | marigiella |
| `co` | corsicagiella |
| `cs` | čeahkagiella |
| `cy` | kymragiella |
| `da` | dánskkagiella |
| `de` | duiskkagiella |
| `dv` | divehigiella |
| `dz` | dzongkhagiella |
| `el` | greikkagiella |
| `en` | eaŋgalsgiella |
| `es` | spánskkagiella |
| `et` | esttegiella |
| `fa` | persijagiella |
| `fi` | suomagiella |
| `fil` | filippiinnagiella |
| `fj` | fidjigiella |
| `fo` | fearagiella |
| `fr` | fránskkagiella |
| `fy` | oarjifriisagiella |
| `ga` | iirragiella |
| `gu` | gujaratagiella |
| `gv` | manksgiella |
| `ha` | haussagiella |
| `haw` | hawaiigiella |
| `hi` | hindigiella |
| `hr` | kroátiagiella |
| `ht` | haitigiella |
| `hu` | ungárgiella |
| `hy` | armeenagiella |
| `id` | indonesiagiella |
| `is` | islánddagiella |
| `it` | itáliagiella |
| `ja` | japánagiella |
| `jv` | javagiella |
| `ka` | georgiagiella |
| `kk` | kazakgiella |
| `km` | kambodiagiella |
| `ko` | koreagiella |
| `krl` | gárjilgiella |
| `ku` | kurdigiella |
| `kv` | komigiella |
| `kw` | kornagiella |
| `la` | láhtengiella |
| `lb` | luxemburggagiella |
| `lo` | laogiella |
| `lt` | liettuvagiella |
| `lv` | látviagiella |
| `mdf` | mokšagiella |
| `mi` | maorigiella |
| `mk` | makedoniagiella |
| `mn` | mongoliagiella |
| `mt` | maltagiella |
| `my` | burmagiella |
| `myv` | ersagiella |
| `nb` | girjedárogiella |
| `ne` | nepaligiella |
| `nl` | hollánddagiella |
| `nn` | ođđadárogiella |
| `no` | dárogiella |
| `oc` | oksitánagiella |
| `pa` | panjabigiella |
| `pl` | polskkagiella |
| `pt` | portugálagiella |
| `rm` | romanšgiella |
| `ro` | romániagiella |
| `ru` | ruoššagiella |
| `sc` | sardigiella |
| `scn` | sisiliagiella |
| `se` | davvisámegiella |
| `sel` | selkupagiella |
| `sh` | serbokroatiagiella |
| `sk` | slovákiagiella |
| `sl` | slovenagiella |
| `sm` | samoagiella |
| `sma` | lullisámegiella |
| `smj` | julevsámegiella |
| `smn` | anárašgiella |
| `sms` | nuortalašgiella |
| `sq` | albánagiella |
| `sr` | serbiagiella |
| `sv` | ruoŧagiella |
| `swb` | shimaorigiella |
| `th` | ŧaigiella |
| `tr` | durkagiella |
| `ty` | tahitigiella |
| `udm` | udmurtagiella |
| `uk` | ukrainagiella |
| `und` | dovdameahttun giella |
| `ur` | urdugiella |
| `vi` | vietnamgiella |
| `wa` | vallonagiella |
| `yue` | kantongiella |
| `zh` | kiinnágiella |
| `zh_Hans` | álki kiinágiella |
| `zh_Hant` | árbevirolaš kiinnágiella |
### Script names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `Arab` | arába |
| `Cyrl` | kyrillalaš |
| `Grek` | greikkalaš |
| `Hang` | hangul |
| `Hani` | kiinnaš |
| `Hans` | álki |
| `Hant` | árbevirolaš |
| `Hira` | hiragana |
| `Kana` | katakana |
| `Latn` | láhtenaš |
| `Zxxx` | orrut chállojuvvot |
| `Zzzz` | dovdameahttun chállin |
### Territory names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `001` | máilbmi |
| `002` | Afrihkká |
| `003` | dávvi-Amerihkká ja gaska-Amerihkká |
| `005` | mátta-Amerihkká |
| `009` | Oseania |
| `011` | oarji-Afrihkká |
| `013` | gaska-Amerihkká |
| `014` | nuorta-Afrihkká |
| `015` | davvi-Afrihkká |
| `017` | gaska-Afrihkká |
| `018` | mátta-Afrihkká |
| `019` | Amerihkká |
| `021` | dávvi-Amerihkká |
| `029` | Karibia |
| `030` | nuorta-Ásia |
| `034` | mátta-Ásia |
| `035` | mátta-nuorta-Ásia |
| `039` | mátta-Eurohpá |
| `053` | Austrália ja Ođđa-Selánda |
| `054` | Melanesia |
| `057` | Mikronesia guovllus |
| `061` | Polynesia |
| `142` | Ásia |
| `143` | gaska-Ásia |
| `145` | oarji-Ásia |
| `150` | Eurohpá |
| `151` | nuorta-Eurohpá |
| `154` | davvi-Eurohpá |
| `155` | oarji-Eurohpá |
| `419` | lulli-Amerihkká |
| `AC` | Ascension |
| `AD` | Andorra |
| `AE` | Ovttastuvvan Arábaemiráhtat |
| `AF` | Afghanistan |
| `AG` | Antigua ja Barbuda |
| `AI` | Anguilla |
| `AL` | Albánia |
| `AM` | Armenia |
| `AO` | Angola |
| `AQ` | Antárktis |
| `AR` | Argentina |
| `AS` | Amerihká Samoa |
| `AT` | Nuortariika |
| `AU` | Austrália |
| `AW` | Aruba |
| `AX` | Ålánda |
| `AZ` | Aserbaižan |
| `BA` | Bosnia-Hercegovina |
| `BB` | Barbados |
| `BD` | Bangladesh |
| `BE` | Belgia |
| `BF` | Burkina Faso |
| `BG` | Bulgária |
| `BH` | Bahrain |
| `BI` | Burundi |
| `BJ` | Benin |
| `BL` | Saint Barthélemy |
| `BM` | Bermuda |
| `BN` | Brunei |
| `BO` | Bolivia |
| `BQ` | Vuolleeatnamat Karibe |
| `BR` | Brasil |
| `BS` | Bahamas |
| `BT` | Bhutan |
| `BV` | Bouvet-sullot |
| `BW` | Botswana |
| `BY` | Vilges-Ruošša |
| `BZ` | Belize |
| `CA` | Kanáda |
| `CC` | Cocos-sullot |
| `CD` | Kongo-Kinshasa |
| `CF` | Gaska-Afrihká dásseváldi |
| `CG` | Kongo-Brazzaville |
| `CH` | Šveica |
| `CI` | Elfenbenariddu |
| `CK` | Cook-sullot |
| `CL` | Čiile |
| `CM` | Kamerun |
| `CN` | Kiinná |
| `CO` | Kolombia |
| `CP` | Clipperton-sullot |
| `CR` | Costa Rica |
| `CU` | Kuba |
| `CV` | Kap Verde |
| `CW` | Curaçao |
| `CX` | Juovllat-sullot |
| `CY` | Kypros |
| `CZ` | Čeahkka |
| `DE` | Duiska |
| `DG` | Diego Garcia |
| `DJ` | Djibouti |
| `DK` | Dánmárku |
| `DM` | Dominica |
| `DO` | Dominikána dásseváldi |
| `DZ` | Algeria |
| `EA` | Ceuta ja Melilla |
| `EC` | Ecuador |
| `EE` | Estlánda |
| `EG` | Egypta |
| `EH` | Oarje-Sahára |
| `ER` | Eritrea |
| `ES` | Spánia |
| `ET` | Etiopia |
| `EU` | Eurohpa Uniovdna |
| `FI` | Suopma |
| `FJ` | Fijisullot |
| `FK` | Falklandsullot |
| `FM` | Mikronesia |
| `FO` | Fearsullot |
| `FR` | Frankriika |
| `GA` | Gabon |
| `GB` | Stuorra-Británnia |
| `GB` | Stuorra-Británnia |
| `GD` | Grenada |
| `GE` | Georgia |
| `GF` | Frankriikka Guayana |
| `GG` | Guernsey |
| `GH` | Ghana |
| `GI` | Gibraltar |
| `GL` | Kalaallit Nunaat |
| `GM` | Gámbia |
| `GN` | Guinea |
| `GP` | Guadeloupe |
| `GQ` | Ekvatoriála Guinea |
| `GR` | Greika |
| `GS` | Lulli Georgia ja Lulli Sandwich-sullot |
| `GT` | Guatemala |
| `GU` | Guam |
| `GW` | Guinea-Bissau |
| `GY` | Guyana |
| `HK` | Hongkong |
| `HK` | Hongkong |
| `HM` | Heard- ja McDonald-sullot |
| `HN` | Honduras |
| `HR` | Kroátia |
| `HT` | Haiti |
| `HU` | Ungár |
| `IC` | Kanáriasullot |
| `ID` | Indonesia |
| `IE` | Irlánda |
| `IL` | Israel |
| `IM` | Mann-sullot |
| `IN` | India |
| `IQ` | Irak |
| `IR` | Iran |
| `IS` | Islánda |
| `IT` | Itália |
| `JE` | Jersey |
| `JM` | Jamaica |
| `JO` | Jordánia |
| `JP` | Japána |
| `KE` | Kenia |
| `KG` | Kirgisistan |
| `KH` | Kambodža |
| `KI` | Kiribati |
| `KM` | Komoros |
| `KN` | Saint Kitts ja Nevis |
| `KP` | Davvi-Korea |
| `KR` | Mátta-Korea |
| `KW` | Kuwait |
| `KY` | Cayman-sullot |
| `KZ` | Kasakstan |
| `LA` | Laos |
| `LB` | Libanon |
| `LC` | Saint Lucia |
| `LI` | Liechtenstein |
| `LK` | Sri Lanka |
| `LR` | Liberia |
| `LS` | Lesotho |
| `LT` | Lietuva |
| `LU` | Luxembourg |
| `LV` | Látvia |
| `LY` | Libya |
| `MA` | Marokko |
| `MC` | Monaco |
| `MD` | Moldávia |
| `ME` | Montenegro |
| `MF` | Frankriikka Saint Martin |
| `MG` | Madagaskar |
| `MH` | Marshallsullot |
| `MK` | Makedonia |
| `ML` | Mali |
| `MM` | Burma |
| `MN` | Mongolia |
| `MO` | Makáo |
| `MO` | Makáo |
| `MP` | Davvi-Mariánat |
| `MQ` | Martinique |
| `MR` | Mauretánia |
| `MS` | Montserrat |
| `MT` | Málta |
| `MU` | Mauritius |
| `MV` | Malediivvat |
| `MW` | Malawi |
| `MX` | Meksiko |
| `MY` | Malesia |
| `MZ` | Mosambik |
| `NA` | Namibia |
| `NC` | Ođđa-Kaledonia |
| `NE` | Niger |
| `NF` | Norfolksullot |
| `NG` | Nigeria |
| `NI` | Nicaragua |
| `NL` | Vuolleeatnamat |
| `NO` | Norga |
| `NP` | Nepal |
| `NR` | Nauru |
| `NU` | Niue |
| `NZ` | Ođđa-Selánda |
| `OM` | Oman |
| `PA` | Panama |
| `PE` | Peru |
| `PF` | Frankriikka Polynesia |
| `PG` | Papua-Ođđa-Guinea |
| `PH` | Filippiinnat |
| `PK` | Pakistan |
| `PL` | Polen |
| `PM` | Saint Pierre ja Miquelon |
| `PN` | Pitcairn |
| `PR` | Puerto Rico |
| `PS` | Palestina |
| `PS` | Palestina |
| `PT` | Portugála |
| `PW` | Palau |
| `PY` | Paraguay |
| `QA` | Qatar |
| `RE` | Réunion |
| `RO` | Románia |
| `RS` | Serbia |
| `RU` | Ruošša |
| `RW` | Rwanda |
| `SA` | Saudi-Arábia |
| `SB` | Salomon-sullot |
| `SC` | Seychellsullot |
| `SD` | Davvisudan |
| `SE` | Ruoŧŧa |
| `SG` | Singapore |
| `SH` | Saint Helena |
| `SI` | Slovenia |
| `SJ` | Svalbárda ja Jan Mayen |
| `SK` | Slovákia |
| `SL` | Sierra Leone |
| `SM` | San Marino |
| `SN` | Senegal |
| `SO` | Somália |
| `SR` | Surinam |
| `SS` | Máttasudan |
| `ST` | São Tomé ja Príncipe |
| `SV` | El Salvador |
| `SX` | Vuolleeatnamat Saint Martin |
| `SY` | Syria |
| `SZ` | Svazieana |
| `TA` | Tristan da Cunha |
| `TC` | Turks ja Caicos-sullot |
| `TD` | Tčad |
| `TG` | Togo |
| `TH` | Thaieana |
| `TJ` | Tažikistan |
| `TK` | Tokelau |
| `TL` | Nuorta-Timor |
| `TM` | Turkmenistan |
| `TN` | Tunisia |
| `TO` | Tonga |
| `TR` | Durka |
| `TT` | Trinidad ja Tobago |
| `TV` | Tuvalu |
| `TW` | Taiwan |
| `TZ` | Tanzánia |
| `UA` | Ukraina |
| `UG` | Uganda |
| `US` | Amerihká ovttastuvvan stáhtat |
| `US` | USA |
| `UY` | Uruguay |
| `UZ` | Usbekistan |
| `VA` | Vatikána |
| `VC` | Saint Vincent ja Grenadine |
| `VE` | Venezuela |
| `VG` | Brittania Virgin-sullot |
| `VI` | AOS Virgin-sullot |
| `VN` | Vietnam |
| `VU` | Vanuatu |
| `WF` | Wallis ja Futuna |
| `WS` | Samoa |
| `XK` | Kosovo |
| `YE` | Jemen |
| `YT` | Mayotte |
| `ZA` | Mátta-Afrihká |
| `ZM` | Zambia |
| `ZW` | Zimbabwe |
| `ZZ` | dovdameahttun guovlu |
### Locale variant names
(Written in middle of sentence, selection list etc.)
| ISO code | Name |
| -------- | ---- |
| `FONIPA` | IPA |
| `FONUPA` | UPA |
| `FONXSAMP` | X-SAMPA |
| `HEPBURN` | Hepburn |
| `PINYIN` | pinyin |
| `WADEGILE` | Wade-Giles |
#### Keys (system names)
| key | Name |
| -------- | ---- |
| `calendar` | kaleandar |
| `collation` | ortnet |
| `currency` | valuhtta |
| `numbers` | numerála |
### Types (of systems)
| key, System   | Name |
| -------- | ---- |
| `buddhistcalendar` | buddhista kaleander |
| `chinesecalendar` | kiinna |
| `gregoriancalendar` | gregoria kaleander |
| `pinyincollation` | pinyin ortnet |
| `traditionalcollation` | árbevirolaš ortnet |
| `fullwidenumbers` | viddis oarjelohkosátni |
| `latnnumbers` | oarjelohkosátni |
| `metric` | SI állan |
| `UK` | SB állan |
| `US` | AOS állan |
### Code patterns
giella: {0}chállin: {0}guovlu: {0}
### Character processing for computer systems
| main characters | `[a á b c č d đ e f g h i j k l m n ŋ o p r s š t ŧ u v z ž]` |
| auxiliary characters | `[à ç é è í ń ñ ó ò q ú w x y ü ø æ å ä ã ö]` |
| index characters | `[A Á B C Č D Đ E É F G H I J K L M N Ŋ O P Q R S Š T Ŧ U V W X Y Z Ž Ø Æ Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
final ellipsis: `{0}…`
initial ellipsis: `…{0}`
medial ellipsis: `{0}…{1}`
word-final ellipsis: `{0} …`
word-initial ellipsis: `… {0}`
word-medial ellipsis: `{0} … {1}`
More information characters: `?`
Delimiters:
Quotation start character: ”
Quotation end character: ”
Secondary yquotation start character: ’
Secondary quotation end character: ’
## Calendar data
#### gregorian calendar
| ID-stuff | values |
| -------- | ------ |
| month 1 | ođđj |
| month 2 | guov |
| month 3 | njuk |
| month 4 | cuo |
| month 5 | mies |
| month 6 | geas |
| month 7 | suoi |
| month 8 | borg |
| month 9 | čakč |
| month 10 | golg |
| month 11 | skáb |
| month 12 | juov |
| month 1 | O |
| month 2 | G |
| month 3 | N |
| month 4 | C |
| month 5 | M |
| month 6 | G |
| month 7 | S |
| month 8 | B |
| month 9 | Č |
| month 10 | G |
| month 11 | S |
| month 12 | J |
| month 1 | ođđajagemánnu |
| month 2 | guovvamánnu |
| month 3 | njukčamánnu |
| month 4 | cuoŋománnu |
| month 5 | miessemánnu |
| month 6 | geassemánnu |
| month 7 | suoidnemánnu |
| month 8 | borgemánnu |
| month 9 | čakčamánnu |
| month 10 | golggotmánnu |
| month 11 | skábmamánnu |
| month 12 | juovlamánnu |
| month 1 | ođđj |
| month 2 | guov |
| month 3 | njuk |
| month 4 | cuo |
| month 5 | mies |
| month 6 | geas |
| month 7 | suoi |
| month 8 | borg |
| month 9 | čakč |
| month 10 | golg |
| month 11 | skáb |
| month 12 | juov |
| month 1 | O |
| month 2 | G |
| month 3 | N |
| month 4 | C |
| month 5 | M |
| month 6 | G |
| month 7 | S |
| month 8 | B |
| month 9 | Č |
| month 10 | G |
| month 11 | S |
| month 12 | J |
| month 1 | ođđajagemánnu |
| month 2 | guovvamánnu |
| month 3 | njukčamánnu |
| month 4 | cuoŋománnu |
| month 5 | miessemánnu |
| month 6 | geassemánnu |
| month 7 | suoidnemánnu |
| month 8 | borgemánnu |
| month 9 | čakčamánnu |
| month 10 | golggotmánnu |
| month 11 | skábmamánnu |
| month 12 | juovlamánnu |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | G |
| (week)day thu | D |
| (week)day fri | B |
| (week)day sat | L |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | sotnabeaivi |
| (week)day mon | vuossárga |
| (week)day tue | maŋŋebárga |
| (week)day wed | gaskavahkku |
| (week)day thu | duorasdat |
| (week)day fri | bearjadat |
| (week)day sat | lávvardat |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | S |
| (week)day mon | V |
| (week)day tue | M |
| (week)day wed | G |
| (week)day thu | D |
| (week)day fri | B |
| (week)day sat | L |
| (week)day sun | sotn |
| (week)day mon | vuos |
| (week)day tue | maŋ |
| (week)day wed | gask |
| (week)day thu | duor |
| (week)day fri | bear |
| (week)day sat | láv |
| (week)day sun | sotnabeaivi |
| (week)day mon | vuossárga |
| (week)day tue | maŋŋebárga |
| (week)day wed | gaskavahkku |
| (week)day thu | duorasdat |
| (week)day fri | bearjadat |
| (week)day sat | lávvardat |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| quarter 1 | Q1 |
| quarter 2 | Q2 |
| quarter 3 | Q3 |
| quarter 4 | Q4 |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | iđitbeaivet |
| period of day pm | eahketbeaivet |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | i.b. |
| period of day pm | e.b. |
| period of day am | iđitbeaivi |
| period of day pm | eahketbeaivi |
| era | ovdal Kristtusa |
| era | BCE |
| era | maŋŋel Kristtusa |
| era | CE |
| era | o.Kr. |
| era | BCE |
| era | m.Kr. |
| era | CE |
| era | ooá |
| era | oá |
| date format | `y MMMM d, EEEE` |
| date format | `y MMMM d` |
| date format | `y MMM d` |
| date format | `y-MM-dd` |
| time format | `HH:mm:ss zzzz` |
| time format | `HH:mm:ss z` |
| time format | `HH:mm:ss` |
| time format | `HH:mm` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| datetime format | `{1} {0}` |
| date format `d` | `d` |
| date format `E` | `ccc` |
| date format `Ed` | `d, E` |
| date format `Ehm` | `E h:mm a` |
| date format `EHm` | `E HH:mm` |
| date format `Ehms` | `E h:mm:ss a` |
| date format `EHms` | `E HH:mm:ss` |
| date format `Gy` | `G y` |
| date format `GyMMM` | `G y MMM` |
| date format `GyMMMd` | `G y MMM d` |
| date format `GyMMMEd` | `G y MMM d, E` |
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
| date format `Md` | `MM-dd` |
| date format `MEd` | `MM-dd, E` |
| date format `MMM` | `LLL` |
| date format `MMMd` | `MMM d` |
| date format `MMMEd` | `MMM d, E` |
| date format `MMMMd` | `MMMM d` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `MMMMW` | `'week' W 'of' MMM` |
| date format `ms` | `mm:ss` |
| date format `y` | `y` |
| date format `yM` | `y-MM` |
| date format `yMd` | `y-MM-dd` |
| date format `yMEd` | `y-MM-dd, E` |
| date format `yMMM` | `y MMM` |
| date format `yMMMd` | `y MMM d` |
| date format `yMMMEd` | `y MMM d, E` |
| date format `yMMMM` | `y MMMM` |
| date format `yQQQ` | `y QQQ` |
| date format `yQQQQ` | `y QQQQ` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
| date format `yw` | `'week' w 'of' Y` |
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
| interval format `Md` | `MM-dd – MM-ddMM-dd – MM-dd` |
| interval format `MEd` | `MM-dd, E – MM-dd, EMM-dd, E – MM-dd, E` |
| interval format `MMM` | `LLL–LLL` |
| interval format `MMMd` | `MMM d–dMMM d – MMM d` |
| interval format `MMMEd` | `MMM d, E – MMM d, EMMM d, E – MMM d, E` |
| interval format `y` | `y–y` |
| interval format `yM` | `y-MM – y-MMy-MM – y-MM` |
| interval format `yMd` | `y-MM-dd – y-MM-ddy-MM-dd – y-MM-ddy-MM-dd – y-MM-dd` |
| interval format `yMEd` | `y-MM-dd, E – y-MM-dd, Ey-MM-dd, E – y-MM-dd, Ey-MM-dd, E – y-MM-dd, E` |
| interval format `yMMM` | `y MMM–MMMy MMM – y MMM` |
| interval format `yMMMd` | `y MMM d–dy MMM d – MMM dy MMM d – y MMM d` |
| interval format `yMMMEd` | `y MMM d, E – MMM d, Ey MMM d, E – MMM d, Ey MMM d, E – y MMM d, E` |
| interval format `yMMMM` | `y MMMM–MMMMy MMMM – y MMMM` |
### some more time stuff
|  | éra |
|  | jáhki |
{0} jahki maŋŋilit{0} jahkki maŋŋilit{0} jahkki maŋŋilit{0} jahki árat{0} jahkki árat{0} jahkki árat
|  | mánnu |
{0} mánotbadji maŋŋilit{0} mánotbadji maŋŋilit{0} mánotbadji maŋŋilit{0} mánotbadji árat{0} mánotbadji árat{0} mánotbadji árat
|  | váhkku |
{0} vahku maŋŋilit{0} vahkku maŋŋilit{0} vahkku maŋŋilit{0} vahku árat{0} vahkku árat{0} vahkku árat
|  | beaivi |
oovdebpeivviikteodneihttinpaijeelittáá{0} jándor maŋŋilit{0} jándor amaŋŋilit{0} jándora maŋŋilit{0} jándor árat{0} jándora árat{0} jándora árat
|  | váhkkubeaivi |
|  | beaivi ráidodássi |
|  | diibmu |
{0} diibmu maŋŋilit{0} diibmur maŋŋilit{0} diibmur maŋŋilit{0} diibmu árat{0} diibmur árat{0} diibmur árat
|  | minuhtta |
{0} minuhta maŋŋilit{0} minuhtta maŋŋilit{0} minuhtta maŋŋilit{0} minuhta árat{0} minuhtta árat{0} minuhtta árat
|  | sekunda |
na{0} sekunda maŋŋilit{0} sekundda maŋŋilit{0} sekundda maŋŋilit{0} sekunda árat{0} sekundda árat{0} sekundda árat
|  | áigeavádat |
#### time zones
| Format name | Format |
| Hours from UTC | +HH:mm;−HH:mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional | {0} áigi |
| regional | {0} geassiáigi |
| regional | {0} dábálašáigi |
| fallback | {0} ({1}) |
| Zone | Name |
| ---- | ---- |
| Etc/Unknown | dovdameahttun áigeavádat |
| Antarctica/DumontDUrville | Dumont d’Urville |
| America/St_Barthelemy | Saint Barthélemy |
| America/Sao_Paulo | São Paulo |
| America/Curacao | Curaçao |
| America/Merida | Mérida |
| Europe_Central | gaska-Eurohpá áigigaska-Eurohpá dábálašáigigaska-Eurohpá geassiáigiCETCETCEST |
| Europe_Eastern | nuorti-Eurohpá áiginuorti-Eurohpá dábálašáiginuorti-Eurohpá geassiáigiEETEETEEST |
| Europe_Western | oarje-Eurohpá áigioarje-Eurohpá dábálašáigioarje-Eurohpá geassiáigiWETWETWEST |
| GMT | Greenwich gaskka áigiGMT |
| Moscow | Moskva-áigiMoskva-dábálašáigiMoskva-geassiáigi |
## Numbers stuff
latnlatn1
| Character name | Translated version |
| Decimal separator | , |
| "Thousands" separator |   |
| Numbers separator | ; |
| Percents | % |
| Plus | + |
| Minus | − |
| Exponential | ·10^ |
| Superscripting Exponent | · |
| Permilles | ‰ |
| Infinity | ∞ |
| Not a number | ¤¤¤ |
| Time separator (Hours:Minutes) | : |
#,##0.###0 duhát0 duháhat0 duháhat00 duhát00 duháhat00 duháhat000 duhát000 duháhat000 duháhat0 miljona0 miljonat0 miljonat00 miljona00 miljonat00 miljonat000 miljona000 miljonat000 miljonat0 miljardi0 miljardit0 miljardit00 miljardi00 miljardit00 miljardit000 miljardi000 miljardit000 miljardit0 biljona0 biljonat0 biljonat00 biljona00 biljonat00 biljonat000 biljona000 biljonat000 biljonat0 dt0 dt0 dt00 dt00 dt00 dt000 dt000 dt000 dt0 mn0 mn0 mn00 mn00 mn00 mn000 mn000 mn000 mn0 md0 md0 md00 md00 md00 md000 md000 md000 md0 bn0 bn0 bn00 bn00 bn00 bn000 bn000 bn000 bn#E0#,##0 %#,##0.00 ¤#,##0.00 ¤0 dt ¤0 dt ¤0 dt ¤00 dt ¤00 dt ¤00 dt ¤000 dt ¤000 dt ¤000 dt ¤0 mn ¤0 mn ¤0 mn ¤00 mn ¤00 mn ¤00 mn ¤000 mn ¤000 mn ¤000 mn ¤0 md ¤0 md ¤0 md ¤00 md ¤00 md ¤00 md ¤000 md ¤000 md ¤000 md ¤0 bn ¤0 bn ¤0 bn ¤00 bn ¤00 bn ¤00 bn ¤000 bn ¤000 bn ¤000 bn ¤
| one | {0} {1} |
| two | {0} {1} |
| other | {0} {1} |
## Currency names
| Code | Name |
| ---- | ---- |
|  symbol | Dkr |
| narrow symbol | kr |
|  | euro |
| one | euro |
| two | euro |
| other | euro |
|  symbol | € |
| narrow symbol | € |
|  | suoma márkki |
|  symbol | GB£ |
| narrow symbol | £ |
|  symbol | HK$ |
|  symbol | ₹ |
|  symbol | Ikr |
| narrow symbol | kr |
|  symbol | JP¥ |
|  symbol | MX$ |
|  | norgga kruvdno |
| one | norgga kruvdno |
| two | norgga kruvdno |
| other | norgga kruvdno |
|  symbol | kr |
| narrow symbol | kr |
|  | ruoŧŧa kruvdno |
| one | ruoŧŧa kruvdno |
| two | ruoŧŧa kruvdno |
| other | ruoŧŧa kruvdno |
|  symbol | Skr |
| narrow symbol | kr |
|  symbol | ฿ |
|  | uns silba |
|  | uns golli |
Other stuff:
⩾{0}{0}–{1}
## Units
| Code | Name |
| ---- | ---- |
| Compound pattern  | {0} juohke {1} |
| acceleration-g-force | ... |
|  | Maapallo gravitaatiovoimat |
| one | {0} Maapallo gravitaatiovoima |
| two | {0} Maapallo gravitaatiovoimat |
| other | {0} Maapallo gravitaatiovoimat |
| angle-degree | ... |
|  | grádat |
| one | {0} grádat |
| two | {0} grádat |
| other | {0} grádat |
| angle-arc-minute | ... |
|  | jorbbas minuhtta |
| one | {0} jorbbas minuhta |
| two | {0} jorbbas minuhtta |
| other | {0} jorbbas minuhtta |
| angle-arc-second | ... |
|  | jorbbas sekundda |
| one | {0} jorbbas sekunda |
| two | {0} jorbbas sekundda |
| other | {0} jorbbas sekundda |
| area-square-kilometer | ... |
|  | neliökilomehtera |
| one | {0} neliökilomehter |
| two | {0} neliökilomehtera |
| other | {0} neliökilomehtera |
| area-hectare | ... |
|  | hehtaaria |
| one | {0} hehtaari |
| two | {0} hehtaaria |
| other | {0} hehtaaria |
| area-square-meter | ... |
|  | neliömehtera |
| one | {0} neliömehter |
| two | {0} neliömehtera |
| other | {0} neliömehtera |
| area-square-mile | ... |
|  | eangas neliömiila |
| one | {0} eangas neliömiil |
| two | {0} eangas neliömiila |
| other | {0} eangas neliömiila |
| area-acre | ... |
|  | Amerihká tynnyrinala |
| one | {0} Amerihká tynnyrinala |
| two | {0} Amerihká tynnyrinala |
| other | {0} Amerihká tynnyrinala |
| area-square-foot | ... |
|  | neliöjuolgi |
| one | {0} neliöjuolgi |
| two | {0} neliöjuolgi |
| other | {0} neliöjuolgi |
| duration-year | ... |
|  | jahkki |
| one | {0} jahki |
| two | {0} jahkki |
| other | {0} jahkki |
{0} juohke jahki
| duration-month | ... |
|  | mánotbadji |
| one | {0} mánotbadji |
| two | {0} mánotbaji |
| other | {0} mánotbadji |
{0} juohke mánotbadji
| duration-week | ... |
|  | váhkku |
| one | {0} váhku |
| two | {0} váhkku |
| other | {0} váhkku |
{0} juohke váhku
| duration-day | ... |
|  | jándora |
| one | {0} jándor |
| two | {0} jándora |
| other | {0} jándora |
{0} juohke jándor
| duration-hour | ... |
|  | diibmur |
| one | {0} diibmu |
| two | {0} diimmur |
| other | {0} diibmur |
{0} juohke diibmu
| duration-minute | ... |
|  | minuhtta |
| one | {0} minuhta |
| two | {0} minuhtta |
| other | {0} minuhtta |
{0} juohke minuhta
| duration-second | ... |
|  | sekundda |
| one | {0} sekunda |
| two | {0} sekundda |
| other | {0} sekundda |
{0} juohke sekunda
| duration-millisecond | ... |
|  | millisekundda |
| one | {0} millisekunda |
| two | {0} millisekundda |
| other | {0} millisekundda |
| duration-microsecond | ... |
|  | mikrosekundda |
| one | {0} mikrosekunda |
| two | {0} mikrosekundda |
| other | {0} mikrosekundda |
| duration-nanosecond | ... |
|  | nanosekundda |
| one | {0} nanosekunda |
| two | {0} nanosekundda |
| other | {0} nanosekundda |
| length-kilometer | ... |
|  | kilomehtera |
| one | {0} kilomehter |
| two | {0} kilomehtera |
| other | {0} kilomehtera |
{0} juohke kilomehter
| length-meter | ... |
|  | mehtera |
| one | {0} mehter |
| two | {0} mehtera |
| other | {0} mehtera |
{0} juohke mehter
| length-decimeter | ... |
|  | desimehtera |
| one | {0} desimehter |
| two | {0} desimehtera |
| other | {0} desimehtera |
| length-centimeter | ... |
|  | sentimehtera |
| one | {0} sentimehter |
| two | {0} sentimehtera |
| other | {0} sentimehtera |
{0} juohke sentimehter
| length-millimeter | ... |
|  | millimehtera |
| one | {0} millimehter |
| two | {0} millimehtera |
| other | {0} millimehtera |
| length-micrometer | ... |
|  | mikromehtera |
| one | {0} mikromehter |
| two | {0} mikromehtera |
| other | {0} mikromehtera |
| length-nanometer | ... |
|  | nanomehtera |
| one | {0} nanomehter |
| two | {0} nanomehtera |
| other | {0} nanomehtera |
| length-picometer | ... |
|  | pikomehtera |
| one | {0} pikomehter |
| two | {0} pikomehtera |
| other | {0} pikomehtera |
| length-mile | ... |
|  | eangas miila |
| one | {0} eangas miil |
| two | {0} eangas miila |
| other | {0} eangas miila |
| length-yard | ... |
|  | eangas yard |
| one | {0} eangas yard |
| two | {0} eangas yard |
| other | {0} eangas yard |
| length-foot | ... |
|  | juolgi |
| one | {0} juolgi |
| two | {0} juolgi |
| other | {0} juolgi |
{0} juohke juolgi
| length-inch | ... |
|  | bealgi |
| one | {0} bealgi |
| two | {0} bealgi |
| other | {0} bealgi |
{0} juohke bealgi
| length-light-year | ... |
|  | chuovgat jagi |
| one | {0} chuovgat jagi |
| two | {0} chuovgat jagi |
| other | {0} chuovgat jagi |
| length-mile-scandinavian | ... |
|  | miila |
| one | {0} miil |
| two | {0} miila |
| other | {0} miila |
| mass-metric-ton | ... |
|  | tonna |
| one | {0} tonna |
| two | {0} tonna |
| other | {0} tonna |
| mass-kilogram | ... |
|  | kilogram |
| one | {0} kilogram |
| two | {0} kilogram |
| other | {0} kilogram |
{0} juohke kilogram
| mass-gram | ... |
|  | gram |
| one | {0} gram |
| two | {0} gram |
| other | {0} gram |
{0} juohke gram
| mass-ton | ... |
|  | eangas tonna à 907kg |
| one | {0} eangas tonna à 907kg |
| two | {0} eangas tonna à 907kg |
| other | {0} eangas tonna à 907kg |
| mass-pound | ... |
|  | pauna |
| one | {0} pauna |
| two | {0} pauna |
| other | {0} pauna |
| mass-ounce | ... |
|  | unssi |
| one | {0} unssi |
| two | {0} unssi |
| other | {0} unssi |
| power-kilowatt | ... |
|  | kilowatt |
| one | {0} kilowatt |
| two | {0} kilowatt |
| other | {0} kilowatt |
| power-watt | ... |
|  | watt |
| one | {0} watt |
| two | {0} watt |
| other | {0} watt |
| power-horsepower | ... |
|  | hevosvoima |
| one | {0} hevosvoima |
| two | {0} hevosvoima |
| other | {0} hevosvoima |
| pressure-hectopascal | ... |
|  | hehtopascal |
| one | {0} hehtopascal |
| two | {0} hehtopascal |
| other | {0} hehtopascal |
| pressure-inch-hg | ... |
|  | bealgi kvikksølv |
| one | {0} bealgi kvikksølv |
| two | {0} bealgi kvikksølv |
| other | {0} bealgi kvikksølv |
| pressure-millibar | ... |
|  | millibar |
| one | {0} millibar |
| two | {0} millibar |
| other | {0} millibar |
| speed-kilometer-per-hour | ... |
|  | kilomehtera kohti diibmu |
| one | {0} kilomehter kohti diibmu |
| two | {0} kilomehtera kohti diibmu |
| other | {0} kilomehtera kohti diibmu |
| speed-meter-per-second | ... |
|  | mehtera kohti sekunti |
| one | {0} mehter kohti sekunti |
| two | {0} mehtera kohti sekunti |
| other | {0} mehtera kohti sekunti |
| speed-mile-per-hour | ... |
|  | eangas miila kohti diibmu |
| one | {0} eangas miil kohti diibmu |
| two | {0} eangas miila kohti diibmu |
| other | {0} eangas miila kohti diibmu |
| temperature-celsius | ... |
|  | grádat Celsius |
| one | {0} grádat Celsius |
| two | {0} grádat Celsius |
| other | {0} grádat Celsius |
| temperature-fahrenheit | ... |
|  | grádat Fahrenheit |
| one | {0} grádat Fahrenheit |
| two | {0} grádat Fahrenheit |
| other | {0} grádat Fahrenheit |
| volume-cubic-kilometer | ... |
|  | kubikkilomehtera |
| one | {0} kubikkilomehter |
| two | {0} kubikkilomehtera |
| other | {0} kubikkilomehtera |
| volume-cubic-mile | ... |
|  | eangas kubikkmiila |
| one | {0} eangas kubikkmiil |
| two | {0} eangas kubikkmiila |
| other | {0} eangas kubikkmiila |
| volume-liter | ... |
|  | lihtara |
| one | {0} lihtar |
| two | {0} lihtara |
| other | {0} lihtara |
{0} juohke lithar{0} nuorti{0} davvi{0} lulli{0} oarji
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
|  | Maapallo gravitaatiovoimat |
| one | {0} G |
| two | {0} G |
| other | {0} G |
| acceleration-meter-per-second-squared | ... |
| one | {0} m/s² |
| two | {0} m/s² |
| other | {0} m/s² |
| angle-degree | ... |
|  | grádat |
| one | {0}° |
| two | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
|  | jorbbas minuhtta |
| one | {0}′ |
| two | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
|  | jorbbas sekundda |
| one | {0}″ |
| two | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
|  | neliökilomehtera |
| one | {0} km² |
| two | {0} km² |
| other | {0} km² |
{0}/km²
| area-hectare | ... |
|  | hehtaaria |
| one | {0} ha |
| two | {0} ha |
| other | {0} ha |
| area-square-meter | ... |
|  | neliömehtera |
| one | {0} m² |
| two | {0} m² |
| other | {0} m² |
{0}/m²
| area-square-centimeter | ... |
|  | cm² |
| one | {0} cm² |
| two | {0} cm² |
| other | {0} cm² |
{0}/cm²
| area-square-mile | ... |
|  | eangas neliömiila |
| one | {0} mi² |
| two | {0} mi² |
| other | {0} mi² |
| area-acre | ... |
|  | Amerihká tynnyrinala |
| one | {0} ac |
| two | {0} ac |
| other | {0} ac |
| area-square-foot | ... |
|  | neliöjuolgi |
| one | {0} ft² |
| two | {0} ft² |
| other | {0} ft² |
| duration-year | ... |
|  | jahkki |
| one | {0} jah |
| two | {0} jah |
| other | {0} jah |
{0}/jah
| duration-month | ... |
|  | mánotbadji |
| one | {0} mán |
| two | {0} mán |
| other | {0} mán |
{0}/mán
| duration-week | ... |
|  | váhkku |
| one | {0} v |
| two | {0} v |
| other | {0} v |
{0}/v
| duration-day | ... |
|  | jándora |
| one | {0} d |
| two | {0} d |
| other | {0} d |
{0}/d
| duration-hour | ... |
|  | diibmur |
| one | {0} h |
| two | {0} h |
| other | {0} h |
{0}/h
| duration-minute | ... |
|  | minuhtta |
| one | {0} min |
| two | {0} min |
| other | {0} min |
{0}/min
| duration-second | ... |
|  | sekundda |
| one | {0} s |
| two | {0} s |
| other | {0} s |
{0}/s
| duration-millisecond | ... |
|  | millisekundda |
| one | {0} ms |
| two | {0} ms |
| other | {0} ms |
| duration-microsecond | ... |
|  | μs |
| one | {0} μs |
| two | {0} μs |
| other | {0} μs |
| duration-nanosecond | ... |
|  | ns |
| one | {0} ns |
| two | {0} ns |
| other | {0} ns |
| length-kilometer | ... |
|  | kilomehtera |
| one | {0} km |
| two | {0} km |
| other | {0} km |
{0}/km
| length-meter | ... |
|  | mehtera |
| one | {0} m |
| two | {0} m |
| other | {0} m |
{0}/m
| length-decimeter | ... |
|  | dm |
| one | {0} dm |
| two | {0} dm |
| other | {0} dm |
| length-centimeter | ... |
|  | sentimehtera |
| one | {0} cm |
| two | {0} cm |
| other | {0} cm |
{0}/cm
| length-millimeter | ... |
|  | millimehtera |
| one | {0} mm |
| two | {0} mm |
| other | {0} mm |
| length-micrometer | ... |
|  | µm |
| one | {0} µm |
| two | {0} µm |
| other | {0} µm |
| length-nanometer | ... |
|  | nm |
| one | {0} nm |
| two | {0} nm |
| other | {0} nm |
| length-picometer | ... |
|  | pikomehtera |
| one | {0} pm |
| two | {0} pm |
| other | {0} pm |
| length-mile | ... |
|  | eangas miila |
| one | {0} mi |
| two | {0} mi |
| other | {0} mi |
| length-yard | ... |
|  | eangas yard |
| one | {0} yd |
| two | {0} yd |
| other | {0} yd |
| length-foot | ... |
|  | juolgi |
| one | {0} juolgi |
| two | {0} juolgi |
| other | {0} juolgi |
{0}/juolgi
| length-inch | ... |
|  | bealgi |
| one | {0} bealgi |
| two | {0} bealgi |
| other | {0} bealgi |
{0}/bealgi
| length-light-year | ... |
|  | chuovgat jagi |
| one | {0} ly |
| two | {0} ly |
| other | {0} ly |
| length-mile-scandinavian | ... |
|  | miila |
| one | {0} miil |
| two | {0} miila |
| other | {0} miila |
| mass-metric-ton | ... |
|  | tonna |
| one | {0} t |
| two | {0} t |
| other | {0} t |
| mass-kilogram | ... |
|  | kilogram |
| one | {0} kg |
| two | {0} kg |
| other | {0} kg |
{0}/kg
| mass-gram | ... |
|  | gram |
| one | {0} g |
| two | {0} g |
| other | {0} g |
{0}/g
| mass-milligram | ... |
| one | {0} mg |
| two | {0} mg |
| other | {0} mg |
| mass-microgram | ... |
| one | {0} µg |
| two | {0} µg |
| other | {0} µg |
| mass-ton | ... |
|  | eangas tonna à 907kg |
| one | {0} eang.ton. à 907kg |
| two | {0} eang.ton. à 907kg |
| other | {0} eang.ton. à 907kg |
| mass-pound | ... |
|  | pauna |
| one | {0} pauna |
| two | {0} pauna |
| other | {0} pauna |
| mass-ounce | ... |
|  | unssi |
| one | {0} unssi |
| two | {0} unssi |
| other | {0} unssi |
| power-kilowatt | ... |
|  | kilowatt |
| one | {0} kW |
| two | {0} kW |
| other | {0} kW |
| power-watt | ... |
|  | watt |
| one | {0} W |
| two | {0} W |
| other | {0} W |
| power-horsepower | ... |
|  | hevosvoima |
| one | {0} hv |
| two | {0} hv |
| other | {0} hv |
| pressure-hectopascal | ... |
|  | hehtopascal |
| one | {0} hPa |
| two | {0} hPa |
| other | {0} hPa |
| pressure-inch-hg | ... |
|  | bealgi kvikksølv |
| one | {0} bealgi Hg |
| two | {0} bealgi Hg |
| other | {0} bealgi Hg |
| pressure-millibar | ... |
|  | millibar |
| one | {0} mbar |
| two | {0} mbar |
| other | {0} mbar |
| speed-kilometer-per-hour | ... |
|  | kilomehtera kohti diibmu |
| one | {0} km/h |
| two | {0} km/h |
| other | {0} km/h |
| speed-meter-per-second | ... |
|  | mehtera kohti sekunti |
| one | {0} m/s |
| two | {0} m/s |
| other | {0} m/s |
| speed-mile-per-hour | ... |
|  | eangas miila kohti diibmu |
| one | {0} mi/h |
| two | {0} mi/h |
| other | {0} mi/h |
| temperature-celsius | ... |
|  | grádat Celsius |
| one | {0}°C |
| two | {0}°C |
| other | {0}°C |
| temperature-fahrenheit | ... |
|  | grádat Fahrenheit |
| one | {0}°F |
| two | {0}°F |
| other | {0}°F |
| volume-cubic-kilometer | ... |
|  | kubikkilomehtera |
| one | {0} km³ |
| two | {0} km³ |
| other | {0} km³ |
| volume-cubic-meter | ... |
| one | {0} m³ |
| two | {0} m³ |
| other | {0} m³ |
{0}/m³
| volume-cubic-centimeter | ... |
|  | cm³ |
| one | {0} cm³ |
| two | {0} cm³ |
| other | {0} cm³ |
{0}/cm³
| volume-cubic-mile | ... |
|  | eangas kubikkmiila |
| one | {0} mi³ |
| two | {0} mi³ |
| other | {0} mi³ |
| volume-megaliter | ... |
|  | ML |
| one | {0} ML |
| two | {0} ML |
| other | {0} ML |
| volume-hectoliter | ... |
|  | hL |
| one | {0} hL |
| two | {0} hL |
| other | {0} hL |
| volume-liter | ... |
|  | lihtara |
| one | {0} l |
| two | {0} l |
| other | {0} l |
{0}/L
| volume-deciliter | ... |
|  | dL |
| one | {0} dL |
| two | {0} dL |
| other | {0} dL |
| volume-centiliter | ... |
|  | cL |
| one | {0} cL |
| two | {0} cL |
| other | {0} cL |
| volume-milliliter | ... |
|  | mL |
| one | {0} mL |
| two | {0} mL |
| other | {0} mL |
{0} N{0} D{0} L{0} O
| Compound pattern  | {0}/{1} |
| acceleration-g-force | ... |
| one | {0}G |
| two | {0}G |
| other | {0}G |
| acceleration-meter-per-second-squared | ... |
| one | {0}m/s² |
| two | {0}m/s² |
| other | {0}m/s² |
| angle-degree | ... |
| one | {0}° |
| two | {0}° |
| other | {0}° |
| angle-arc-minute | ... |
| one | {0}′ |
| two | {0}′ |
| other | {0}′ |
| angle-arc-second | ... |
| one | {0}″ |
| two | {0}″ |
| other | {0}″ |
| area-square-kilometer | ... |
| one | {0}km² |
| two | {0}km² |
| other | {0}km² |
{0}/km²
| area-hectare | ... |
| one | {0}ha |
| two | {0}ha |
| other | {0}ha |
| area-square-meter | ... |
| one | {0}m² |
| two | {0}m² |
| other | {0}m² |
{0}/m²
| area-square-centimeter | ... |
|  | cm² |
| one | {0}cm² |
| two | {0}cm² |
| other | {0}cm² |
{0}/cm²
| area-square-mile | ... |
| one | {0} mi² |
| two | {0} mi² |
| other | {0} mi² |
| area-acre | ... |
| one | {0} ac |
| two | {0} ac |
| other | {0} ac |
| area-square-foot | ... |
| one | {0} ft² |
| two | {0} ft² |
| other | {0} ft² |
| duration-year | ... |
| one | {0}j |
| two | {0}j |
| other | {0}j |
{0}/jah
| duration-month | ... |
| one | {0}m |
| two | {0}m |
| other | {0}m |
{0}/mán
| duration-week | ... |
| one | {0}v |
| two | {0}v |
| other | {0}v |
{0}/v
| duration-day | ... |
| one | {0}d |
| two | {0}d |
| other | {0}d |
{0}/d
| duration-hour | ... |
| one | {0}h |
| two | {0}h |
| other | {0}h |
{0}/h
| duration-minute | ... |
| one | {0}m |
| two | {0}m |
| other | {0}m |
{0}/min
| duration-second | ... |
| one | {0}s |
| two | {0}s |
| other | {0}s |
{0}/s
| duration-millisecond | ... |
| one | {0}ms |
| two | {0}ms |
| other | {0}ms |
| duration-microsecond | ... |
|  | μs |
| one | {0}μs |
| two | {0}μs |
| other | {0}μs |
| duration-nanosecond | ... |
|  | ns |
| one | {0}ns |
| two | {0}ns |
| other | {0}ns |
| length-kilometer | ... |
| one | {0}km |
| two | {0}km |
| other | {0}km |
{0}/km
| length-meter | ... |
| one | {0}m |
| two | {0}m |
| other | {0}m |
{0}/m
| length-decimeter | ... |
|  | dm |
| one | {0}dm |
| two | {0}dm |
| other | {0}dm |
| length-centimeter | ... |
| one | {0}cm |
| two | {0}cm |
| other | {0}cm |
{0}/cm
| length-millimeter | ... |
| one | {0}mm |
| two | {0}mm |
| other | {0}mm |
| length-micrometer | ... |
|  | µm |
| one | {0}µm |
| two | {0}µm |
| other | {0}µm |
| length-nanometer | ... |
|  | nm |
| one | {0}nm |
| two | {0} nm |
| other | {0}nm |
| length-picometer | ... |
| one | {0}pm |
| two | {0}pm |
| other | {0}pm |
| length-mile | ... |
| one | {0} mi |
| two | {0} mi |
| other | {0} mi |
| length-yard | ... |
| one | {0} yd |
| two | {0} yd |
| other | {0} yd |
| length-foot | ... |
| one | {0} juolgi |
| two | {0} juolgi |
| other | {0} juolgi |
| length-inch | ... |
| one | {0} bealgi |
| two | {0} bealgi |
| other | {0} bealgi |
| length-light-year | ... |
| one | {0} ly |
| two | {0} ly |
| other | {0} ly |
| mass-metric-ton | ... |
|  | tonna |
| one | {0}t |
| two | {0}t |
| other | {0}t |
| mass-kilogram | ... |
| one | {0}kg |
| two | {0}kg |
| other | {0}kg |
{0}/kg
| mass-gram | ... |
| one | {0}g |
| two | {0}g |
| other | {0}g |
{0}/g
| mass-milligram | ... |
| one | {0}mg |
| two | {0}mg |
| other | {0}mg |
| mass-microgram | ... |
| one | {0}µg |
| two | {0}µg |
| other | {0}µg |
| mass-ton | ... |
|  | eangas tonna |
| one | {0} e.ton. |
| two | {0} e.ton. |
| other | {0} e.ton. |
| mass-pound | ... |
| one | {0} pauna |
| two | {0} pauna |
| other | {0} pauna |
| mass-ounce | ... |
| one | {0} unssi |
| two | {0} unssi |
| other | {0} unssi |
| power-kilowatt | ... |
| one | {0}kW |
| two | {0}kW |
| other | {0}kW |
| power-watt | ... |
| one | {0}W |
| two | {0}W |
| other | {0}W |
| power-horsepower | ... |
| one | {0}hv |
| two | {0}hv |
| other | {0}hv |
| pressure-hectopascal | ... |
| one | {0}hPa |
| two | {0}hPa |
| other | {0}hPa |
| pressure-inch-hg | ... |
| one | {0} bealgi Hg |
| two | {0} bealgi Hg |
| other | {0} bealgi Hg |
| pressure-millibar | ... |
| one | {0}mbar |
| two | {0}mbar |
| other | {0}mbar |
| speed-kilometer-per-hour | ... |
| one | {0}km/h |
| two | {0}km/h |
| other | {0}km/h |
| speed-meter-per-second | ... |
| one | {0}m/s |
| two | {0}m/s |
| other | {0}m/s |
| speed-mile-per-hour | ... |
| one | {0} mi/h |
| two | {0} mi/h |
| other | {0} mi/h |
| temperature-celsius | ... |
| one | {0}° |
| two | {0}° |
| other | {0}° |
| temperature-fahrenheit | ... |
| one | {0}°F |
| two | {0}°F |
| other | {0}°F |
| volume-cubic-kilometer | ... |
| one | {0}km³ |
| two | {0}km³ |
| other | {0}km³ |
| volume-cubic-centimeter | ... |
|  | cm³ |
| one | {0}cm³ |
| two | {0}cm³ |
| other | {0}cm³ |
{0}/cm³
| volume-cubic-mile | ... |
| one | {0} mi³ |
| two | {0} mi³ |
| other | {0} mi³ |
| volume-megaliter | ... |
|  | ML |
| one | {0}ML |
| two | {0}ML |
| other | {0}ML |
| volume-hectoliter | ... |
|  | hL |
| one | {0}hL |
| two | {0}hL |
| other | {0}hL |
| volume-liter | ... |
| one | {0}L |
| two | {0}L |
| other | {0}L |
{0}/L
| volume-deciliter | ... |
|  | dL |
| one | {0}dL |
| two | {0}dL |
| other | {0}dL |
| volume-centiliter | ... |
|  | cL |
| one | {0}cL |
| two | {0}cL |
| other | {0}cL |
| volume-milliliter | ... |
|  | mL |
| one | {0}mL |
| two | {0}mL |
| other | {0}mL |
{0}N{0}D{0}L{0}Oh:mmh:mm:ssm:ss
## Lists
| List type | Patterns |
|  | ... |
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
joii
