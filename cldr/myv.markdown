---
layout: default
title: "CLDR Erzya"
---

## CLDR core data for Erzya

**Needed for requesting new locale**:

| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[а б в г д е ё ж з и й к л м н о п р с т у ф х ц ч ш щ ъ ы ь э ю я]` |
| auxiliary characters | `[ҥ є ѕ і ў џ ѣ ѡ ѳ ѵ ѷ җ ä ə]` |
| index characters | `[А Б В Г Д Е Ё Ж З И Й К Л М Н О П Р С Т У Ф Х Ц Ч Ш Щ Ъ Ы Ь Э Ю Я]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} зепе {0} зепесь |
| many example | {0} зепть {0} зептне |
| Country Data and Default Content | myv_RU |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
| Romanization | а:a б:b в:v г:g д:d е:je ё:jo ж:ž з:z и:i й:j к:k л:l м:m н:n о:o п:p р:r с:s т:t у:u ф:f х:h ц:c ч:č ш:š щ:šč ъ:ъ ы:y ь:ь э:e ю:ju я:ja |

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
Just like Russian, with "е" followed by "ё"

#### standard

```
				[reorder Cyrl]
				# The root collation already sorts й/Й as a base letter.

```

## CLDR minimal data for Erzya

**Needed soon after submitting new locale**.

### Required date-time formats

(44+ needed?)

#### gregorian calendar

| ID-stuff | values |
| -------- | ------ |
| month, 1, abbreviated, format | якшамк. |
| month, 2, abbreviated, format | даволк. |
| month, 3, abbreviated, format | эйзюрков|
| month, 4, abbreviated, format | чадык. |
| month, 5, abbreviated, format | панжик. |
| month, 6, abbreviated, format | аштемк. |
| month, 7, abbreviated, format | медьк. |
| month, 8, abbreviated, format | умарьк. |
| month, 9, abbreviated, format | таштамк. |
| month, 10, abbreviated, format | ожок. |
| month, 11, abbreviated, format | сундерьк. |
| month, 12, abbreviated, format | ацамк. |
| month, 1, narrow, format | Я |
| month, 2, narrow, format | Д |
| month, 3, narrow, format | Э |
| month, 4, narrow, format | Ч |
| month, 5, narrow, format | П |
| month, 6, narrow, format | А |
| month, 7, narrow, format | М |
| month, 8, narrow, format | У |
| month, 9, narrow, format | Т |
| month, 10, narrow, format | О |
| month, 11, narrow, format | С |
| month, 12, narrow, format | А |
# These are for month day ordering
| month, 1, wide, format | якшамковонь |
| month, 2, wide, format | даволковонь |
| month, 3, wide, format | эйзюрковонь|
| month, 4, wide, format | чадыковонь |
| month, 5, wide, format | панжиковонь |
| month, 6, wide, format | аштемковонь |
| month, 7, wide, format | медьковонь |
| month, 8, wide, format | умарьковонь |
| month, 9, wide, format | таштамковонь |
| month, 10, wide, format | ожоковонь |
| month, 11, wide, format | сундерьковонь |
| month, 12, wide, format | ацамковонь |
| month, 1, abbreviated, stand-alone | якшам |
| month, 2, abbreviated, stand-alone | давол |
| month, 3, abbreviated, stand-alone | эйзюр|
| month, 4, abbreviated, stand-alone | чады |
| month, 5, abbreviated, stand-alone | панжи |
| month, 6, abbreviated, stand-alone | аштем |
| month, 7, abbreviated, stand-alone | медь |
| month, 8, abbreviated, stand-alone | умарь |
| month, 9, abbreviated, stand-alone | таштам |
| month, 10, abbreviated, stand-alone | ожо |
| month, 11, abbreviated, stand-alone | сундерь |
| month, 12, abbreviated, stand-alone | ацам |
| month, 1, narrow, stand-alone | Я |
| month, 2, narrow, stand-alone | Д |
| month, 3, narrow, stand-alone | Э |
| month, 4, narrow, stand-alone | Ч |
| month, 5, narrow, stand-alone | П |
| month, 6, narrow, stand-alone | А |
| month, 7, narrow, stand-alone | М |
| month, 8, narrow, stand-alone | У |
| month, 9, narrow, stand-alone | Т |
| month, 10, narrow, stand-alone | О |
| month, 11, narrow, stand-alone | С |
| month, 12, narrow, stand-alone | А |


| month, 1, wide, stand-alone | якшамков |
| month, 2, wide, stand-alone | даволков |
| month, 3, wide, stand-alone | эйзюрков|
| month, 4, wide, stand-alone | чадыков |
| month, 5, wide, stand-alone | панжиков |
| month, 6, wide, stand-alone | аштемков |
| month, 7, wide, stand-alone | медьков |
| month, 8, wide, stand-alone | умарьков |
| month, 9, wide, stand-alone | таштамков |
| month, 10, wide, stand-alone | ожоков |
| month, 11, wide, stand-alone | сундерьков |
| month, 12, wide, stand-alone | ацамков |
| (week)day, sun, abbreviated, format | тар |
| (week)day, mon, abbreviated, format | атя |
| (week)day, tue, abbreviated, format | вас |
| (week)day, wed, abbreviated, format | кун |
| (week)day, thu, abbreviated, format | кал |
| (week)day, fri, abbreviated, format | сюк |
| (week)day, sat, abbreviated, format | шля |
| (week)day, sun, narrow, format | Т |
| (week)day, mon, narrow, format | А |
| (week)day, tue, narrow, format | В |
| (week)day, wed, narrow, format | К |
| (week)day, thu, narrow, format | К |
| (week)day, fri, narrow, format | С |
| (week)day, sat, narrow, format | Ш |
| (week)day, sun, short, format | та |
| (week)day, mon, short, format | ат |
| (week)day, tue, short, format | ва |
| (week)day, wed, short, format | ку |
| (week)day, thu, short, format | ка |
| (week)day, fri, short, format | сю |
| (week)day, sat, short, format | шл |
| (week)day, sun, wide, format | таргочистэ |
| (week)day, mon, wide, format | атяньчистэ |
| (week)day, tue, wide, format | вастаньчистэ |
| (week)day, wed, wide, format | куншкачистэ |
| (week)day, thu, wide, format | калчистэ |
| (week)day, fri, wide, format | сюконьчистэ |
| (week)day, sat, wide, format | шлямочистэ |
| (week)day, sun, abbreviated, stand-alone | тарго |
| (week)day, mon, abbreviated, stand-alone | атянь |
| (week)day, tue, abbreviated, stand-alone | вастань |
| (week)day, wed, abbreviated, stand-alone | куншка |
| (week)day, thu, abbreviated, stand-alone | кал |
| (week)day, fri, abbreviated, stand-alone | сюконь |
| (week)day, sat, abbreviated, stand-alone | шлямо |
| (week)day, sun, narrow, stand-alone | Т |
| (week)day, mon, narrow, stand-alone | А |
| (week)day, tue, narrow, stand-alone | В |
| (week)day, wed, narrow, stand-alone | К |
| (week)day, thu, narrow, stand-alone | К |
| (week)day, fri, narrow, stand-alone | С |
| (week)day, sat, narrow, stand-alone | Ш |
| (week)day, sun, short, stand-alone | та |
| (week)day, mon, short, stand-alone | ат |
| (week)day, tue, short, stand-alone | ва |
| (week)day, wed, short, stand-alone | ку |
| (week)day, thu, short, stand-alone | ка |
| (week)day, fri, short, stand-alone | сю |
| (week)day, sat, short, stand-alone | шл |
| (week)day, sun, wide, stand-alone | таргочи |
| (week)day, mon, wide, stand-alone | атяньчи |
| (week)day, tue, wide, stand-alone | вастаньчи |
| (week)day, wed, wide, stand-alone | куншкачи |
| (week)day, thu, wide, stand-alone | калчи |
| (week)day, fri, wide, stand-alone | сюконьчи |
| (week)day, sat, wide, stand-alone | шлямочи |
| quarter 1 | 1 |
| quarter 2 | 2 |
| quarter 3 | 3 |
| quarter 4 | 4 |
| period of day midnight | пелевене |
| period of day am | обедтэ икеле |
| period of day noon | чикуншкане |
| period of day pm | обедтэ мейле |
| period of day morning1 | валске марто|
| period of day morning2 |  |
| period of day afternoon1 | чить |
| period of day evening1 | чокшне ланга |
| period of day night1 | веть |
| period of day midnight |  |
| era BC | Христосонь чачомадо икеле |
| era BCE | Минек эрадо икеле |
| era AD | Христосонь чачомадо мейле |
| era ACE | Минек эрасто |
| date format | `EEEE, d MMMM y 'и'.` |
| date format | `d MMMM y 'и'.` |
| date format | `d MMM y 'и'.` |
| date format | `dd.MM.y` |
| time format | `H:mm:ss zzzz` |
| time format | `H:mm:ss z` |
| time format | `H:mm:ss` |
| time format | `H:mm` |
| datetime format | `{1}, {0}` |
| Timezone | {0} {1} |
| interval format fallback | `{0}–{1}` |


### Important names in language

Language:

| `myv` | эрзя |

Country or territory:

| `RU` | Рузонь мастор |

Currency:

|  | Россиянь целковой |
| one | Россиянь целковой |
| other | Россиянь целковойть |
|  symbol | ₽ |
| narrow symbol | ₽ |

### Datetime patterns

| datetime format | `{1}, {0}` |


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

Country or territory:

| `RU` | Рузонь мастор |

Timezone ID:

| Europe/Helsinki | Хельсинки |
| Europe/Moscow | Москов |
| Asia/Tomsk | Томск |

### Timezone patterns

| Hours from UTC | +HH:mm;-HH:mm |
| GMT | GMT{0} |
| Time at Greenwich | GMT |
| regional | {0} |
| regional | {0}, кизэнь шка |
| regional | {0}, свалонь шка |
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
| `calendar` | ковкерькс |
| `cf` | |
| `colAlternate` | |
| `colBackwards` | |
| `colCaseFirst` | |
| `colCaseLevel` | |
| `collation` | |
| `colNormalization` | |
| `colNumeric` | |
| `colStrength` | |
| `currency` | валюта |
| `hc` | |
| `lb` | |
| `ms` | онкстамонь система |
| `numbers` | |
| `timezone` | |
| `va` | |
| `x` | |

### Some time intervals

???
 
## More (all) CLDR data for Erzya

While not strictly needed is all used by software and stuff:
identity:

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
| `aa` | афаронь кель |
| `ab` | абхазонь кель |
| `ace` | ачехень кель |
| `ach` | ачолинь кель |
| `ada` | адангмень кель |
| `ady` | адыгеень кель |
| `ae` | авестиень кель |
| `af` | африкаансонь кель |
| `afh` | африхилинь кель |
| `agq` | агемень кель |
| `ain` | айнэнь кель |
| `ak` | аканонь кель |
| `akk` | аккадонь кель |
| `ale` | алеутонь кель |
| `alt` | пелечиёнксонь алтаень кель |
| `am` | амхаронь кель |
| `an` | арагононь кель |
| `ang` | ташто англань кель |
| `anp` | ангикань кель |
| `ar` | арабонь кель |
| `ar_001` | арабонь сёрмадонь кель |
| `arc` | арамеень кель |
| `arn` | мапучень кель |
| `arp` | арапахонь кель |
| `ars` | арабонь — недждиень кель |
| `arw` | араваконь кель |
| `as` | ассамонь кель |
| `asa` | асунь кель |
| `ast` | астуриень кель |
| `av` | аваронь кель |
| `awa` | авадхинь кель |
| `ay` | аймарань кель |
| `az` | азербайджанонь кель |
| `ba` | башкирэнь кель |
| `bal` | белуджонь кель |
| `ban` | балиень кель |
| `bas` | басань кель |
| `bax` | бамумонь кель |
| `bbj` | гомалань кель |
| `be` | белорузонь кель |
| `bej` | беджань кель |
| `bem` | бембань кель |
| `bez` | бенань кель |
| `bfd` | бафутонь кель |
| `bg` | болгаронь кель |
| `bgn` | чивалгомань белуджонь кель |
| `bho` | бходжпуринь кель |
| `bi` | бисламань кель |
| `bik` | биколень кель |
| `bin` | бининь кель |
| `bkm` | комонь кель |
| `bla` | сиксикань кель |
| `bm` | бамбарань кель |
| `bn` | бенгалень кель |
| `bo` | тибетэнь кель |
| `br` | бретононь кель |
| `bra` | брауинь кель |
| `brx` | бодонь кель |
| `bs` | босниень кель |
| `bss` | акоосень кель |
| `bua` | бурятонь кель |
| `bug` | бугиень кель |
| `bum` | булунь кель |
| `byn` | билинэнь кель |
| `byv` | медумбань кель |
| `ca` | каталанонь кель |
| `cad` | каддонь кель |
| `car` | карибень кель |
| `cay` | кайюгань кель |
| `cch` | атсамонь кель |
| `ce` | чеченэнь кель |
| `ceb` | себуанонь кель |
| `cgg` | кигань кель |
| `ch` | чаморронь кель |
| `chb` | чибчань кель |
| `chg` | чагатаень кель |
| `chk` | чукотонь кель |
| `chm` | мариень кель |
| `chn` | чинук жаргононь кель |
| `cho` | чоктавонь кель |
| `chp` | чипевьянонь кель |
| `chr` | черокинь кель |
| `chy` | шайенэнь кель |
| `ckb` | соранинь кель |
| `co` | корсиканонь кель |
| `cop` | коптонь кель |
| `cr` | кринь кель |
| `crh` | крымско-татаронь кель |
| `crs` | сейшельский креолень кель |
| `cs` | чешень кель |
| `csb` | кашубонь кель |
| `cu` | церковнославянонь кель |
| `cv` | ветькень кель |
| `cy` | валлиень кель |
| `da` | датонь кель |
| `dak` | дакотань кель |
| `dar` | даргинэнь кель |
| `dav` | таитань кель |
| `de` | немецень кель |
| `de_AT` | Австриянь немецень кель |
| `de_CH` | Швейцариянь сёрмадонь немецень кель |
| `del` | делаваронь кель |
| `den` | слейвинь кель |
| `dgr` | догрибень кель |
| `din` | динкань кель |
| `dje` | джермань кель |
| `doi` | догринь кель |
| `dsb` | алце лужицень кель |
| `dua` | дуалань кель |
| `dum` | куншканидерландонь кель |
| `dv` | мальдивень кель |
| `dyo` | диола-фоньинь кель |
| `dyu` | диулань кель |
| `dz` | дзонг-кэнь кель |
| `dzg` | дазань кель |
| `ebu` | эмбунь кель |
| `ee` | эвень кель |
| `efi` | эфикень кель |
| `egy` | кезэрь Египетэнь кель |
| `eka` | экаджуконь кель |
| `el` | грекень кель |
| `elx` | эламонь кель |
| `en` | англань кель |
| `en_AU` | Австралиянь англань кель |
| `en_CA` | Канадань англань кель |
| `en_GB` | Британиянь англань кель |
| `en_US` | Американонь англань кель |
| `enf` | вирень энецень кель |
| `enh` | тундрань энецень кель |
| `enm` | куншкаанглань кель |
| `eo` | эсперантонь кель |
| `es` | испанонь кель |
| `es_419` | латиноамериканонь испанонь кель |
| `es_ES` | Европань испанонь кель |
| `es_MX` | Мексикань испанонь кель |
| `et` | эстэнь кель |
| `eu` | басконь кель |
| `ewo` | эвондонь кель |
| `fa` | персидэнь кель |
| `fan` | фангонь кель |
| `fat` | фантинь кель |
| `ff` | фулахонь кель |
| `fi` | финнэнь кель |
| `fil` | филиппинэнь кель |
| `fj` | фиджинь кель |
| `fo` | фарерэнь кель |
| `fon` | фононь кель |
| `fr` | французонь кель |
| `fr_CA` | Канадань французонь кель |
| `fr_CH` | Швейцариянь французонь кель |
| `frc` | каджунонь французонь кель |
| `frm` | куншкафранцузонь кель |
| `fro` | ташто французонь кель |
| `frr` | пелевеёнксонь фризэнь кель |
| `frs` | чилисемаёнксонь фризэнь кель |
| `fur` | фриулень кель |
| `fy` | чивалгомаёнксонь фризэнь кель |
| `ga` | ирландонь кель |
| `gaa` | гань кель |
| `gag` | гагаузонь кель |
| `gan` | гань кель |
| `gay` | гайонь кель |
| `gba` | гбаянь кель |
| `gd` | гэлень кель |
| `gez` | геэзэнь кель |
| `gil` | гильбертэнь кель |
| `gl` | галисиень кель |
| `gmh` | куншка верце ненемецень кель |
| `gn` | гуаранинь кель |
| `goh` | кезэрень верце немецень кель |
| `gon` | гондинь кель |
| `gor` | горонталонь кель |
| `got` | готонь кель |
| `grb` | гребонь кель |
| `grc` | кезэрьгрекень кель |
| `gsw` | Швейцариянь немецень кель |
| `gu` | гуджаратинь кель |
| `guz` | гусиинь кель |
| `gv` | мэнэнь кель |
| `gwi` | гвичинэнь кель |
| `ha` | хаусань кель |
| `hai` | хайдань кель |
| `hak` | хаккань кель |
| `haw` | гаваень кель |
| `he` | ивритэнь кель |
| `hi` | хиндинь кель |
| `hil` | хилигайнононь кель |
| `hit` | хеттэнь кель |
| `hmn` | хмонгонь кель |
| `ho` | хиримотунь кель |
| `hr` | хорватонь кель |
| `hsb` | верце лужицень кель |
| `hsn` | сянонь кель |
| `ht` | гаитянонь кель |
| `hu` | венгрань кель |
| `hup` | хупань кель |
| `hy` | армянонь кель |
| `hz` | гереронь кель |
| `ia` | интерлингвань кель |
| `iba` | ибанонь кель |
| `ibb` | ибибионь кель |
| `id` | индонезиень кель |
| `ie` | интерлингвень кель |
| `ig` | игбонь кель |
| `ii` | носунь кель |
| `ik` | инупиаконь кель |
| `ilo` | илоконь кель |
| `inh` | ингушонь кель |
| `io` | идонь кель |
| `is` | исландонь кель |
| `it` | итальянонь кель |
| `iu` | инуктитутонь кель |
| `ja` | япононь кель |
| `jbo` | ложбанонь кель |
| `jgo` | нгомбань кель |
| `jmc` | мачамень кель |
| `jpr` | еврейско-персидэнь кель |
| `jrb` | еврейско-арабонь кель |
| `jv` | яванонь кель |
| `ka` | грузинэнь кель |
| `kaa` | каракалпаконь кель |
| `kab` | кабилень кель |
| `kac` | качинэнь кель |
| `kaj` | каджинь кель |
| `kam` | камбань кель |
| `kaw` | кавинь кель |
| `kbd` | кабардинэнь кель |
| `kbl` | канембунь кель |
| `kca` | хантынь кель |
| `kcg` | тьяпонь кель |
| `kde` | макондень кель |
| `kea` | кабувердьянунь кель |
| `kfo` | коронь кель |
| `kg` | конгонь кель |
| `kha` | кхасинь кель |
| `kho` | хотанонь кель |
| `khq` | койра чиининь кель |
| `ki` | кикуйюнь кель |
| `kj` | кунамань кель |
| `kk` | казахонь кель |
| `kkj` | каконь кель |
| `kl` | гренландонь кель |
| `kln` | календжинэнь кель |
| `km` | кхмерэнь кель |
| `kmb` | кимбундунь кель |
| `kn` | каннадань кель |
| `ko` | кореень кель |
| `koi` | коми-пермяконь кель |
| `kok` | конканинь кель |
| `kos` | косраенэнь кель |
| `kpe` | кпеллень кель |
| `kr` | кануринь кель |
| `krc` | карачаево-балкаронь кель |
| `krl` | карелень кель |
| `kru` | курухонь кель |
| `ks` | кашмиринь кель |
| `ksb` | шамбалань кель |
| `ksf` | бафиянь кель |
| `ksh` | кёльнень кель |
| `ku` | курдонь кель |
| `kum` | кумыкень кель |
| `kut` | кутенаинь кель |
| `kv` | коминь кель |
| `kw` | корнонь кель |
| `ky` | киргизэнь кель |
| `la` | латинэнь кель |
| `lad` | ладинонь кель |
| `lag` | лангонь кель |
| `lah` | лахндань кель |
| `lam` | ламбань кель |
| `lb` | люксембургонь кель |
| `lez` | лезгинэнь кель |
| `lg` | гандань кель |
| `li` | лимбургонь кель |
| `lkt` | лакотань кель |
| `ln` | лингалань кель |
| `lo` | лаосонь кель |
| `lol` | монгонь кель |
| `lou` | луизианский креолень кель |
| `loz` | лозинь кель |
| `lrc` | пелевеёнксонь луронь кель |
| `lt` | литовонь кель |
| `lu` | луба-катангань кель |
| `lua` | луба-лулуань кель |
| `lui` | луисеньонь кель |
| `lun` | лундань кель |
| `luo` | луонь кель |
| `lus` | лушеень кель |
| `luy` | лухьянь кель |
| `lv` | латышень кель |
| `mad` | мадуронь кель |
| `maf` | мафань кель |
| `mag` | магахинь кель |
| `mai` | майтхилинь кель |
| `mak` | макассаронь кель |
| `man` | мандингонь кель |
| `mas` | масаинь кель |
| `mde` | мабань кель |
| `mdf` | мокшонь кель |
| `mdr` | мандаронь кель |
| `men` | мендень кель |
| `mer` | мерунь кель |
| `mfe` | маврикийский креолень кель |
| `mg` | малагасиень кель |
| `mga` | куншкаирландонь кель |
| `mgh` | макуа-мееттонь кель |
| `mgo` | метань кель |
| `mh` | маршаллень кель |
| `mi` | маоринь кель |
| `mic` | микмаконь кель |
| `min` | минангкабаунь кель |
| `mk` | македононь кель |
| `ml` | малаяламонь кель |
| `mn` | монголень кель |
| `mnc` | маньчжуронь кель |
| `mni` | манипуронь кель |
| `mns` | мансинь кель |
| `moh` | мохауконь кель |
| `mos` | мосинь кель |
| `mr` | маратхинь кель |
| `ms` | малаень кель |
| `mt` | мальтиень кель |
| `mua` | мундангонь кель |
| `mul` | лия-лия канонь кельть |
| `mus` | крикень кель |
| `mwl` | мирандонь кель |
| `mwr` | марваринь кель |
| `my` | бирманонь кель |
| `mye` | миенень кель |
| `myv` | эрзянь кель |
| `mzn` | мазендеранонь кель |
| `na` | наурунь кель |
| `nan` | миньнань кель |
| `nap` | неаполитанонь кель |
| `naq` | намань кель |
| `nb` | норвежский букмолонь кель |
| `nd` | пелевеёнксонь ндебелень кель |
| `nds` | алце германонь кель |
| `nds_NL` | алце саксононь кель |
| `ne` | непалень кель |
| `new` | неваронь кель |
| `ng` | ндонгань кель |
| `nia` | ниасонь кель |
| `nio` | нганасанонь кель |
| `niu` | ниуэнь кель |
| `nl` | нидерландонь кель |
| `nl_BE` | фламандонь кель |
| `nmg` | квасионь кель |
| `nn` | нюнорсконь кель |
| `nnh` | нгиембундонь кель |
| `no` | норвежень кель |
| `nog` | ногаень кель |
| `non` | ташто норвегиянь кель |
| `nqo` | нконь кель |
| `nr` | пелечиёнксонь ндебелень кель |
| `nso` | пелевеёнксонь сотонь кель |
| `nus` | нуэрэнь кель |
| `nv` | навахонь кель |
| `nwc` | классический неваринь кель |
| `ny` | ньянджань кель |
| `nym` | ньямвезинь кель |
| `nyn` | ньянколень кель |
| `nyo` | ньоронь кель |
| `nzi` | нзимань кель |
| `oc` | окситанонь кель |
| `oj` | оджибвань кель |
| `om` | оромонь кель |
| `or` | ориянь кель |
| `os` | осетинэнь кель |
| `osa` | оседжинь кель |
| `ota` | ташто туркань кель |
| `pa` | панджабинь кель |
| `pag` | пангасинанонь кель |
| `pal` | пехлевиень кель |
| `pam` | пампангань кель |
| `pap` | папьяментонь кель |
| `pau` | палаунь кель |
| `pcm` | нигерийско-креолень кель |
| `peo` | ташто персидэнь кель |
| `phn` | финикиень кель |
| `pi` | палинь кель |
| `pl` | полень кель |
| `pon` | понапень кель |
| `prg` | пруссиянь кель |
| `pro` | ташто провансалень кель |
| `ps` | пуштунь кель |
| `pt` | португалень кель |
| `pt_BR` | Бразилиянь Португалиянь кель |
| `pt_PT` | Европань Португалиянь кель |
| `qu` | кечуань кель |
| `quc` | кичень кель |
| `raj` | раджастханинь кель |
| `rap` | рапануень кель |
| `rar` | раротонгань кель |
| `rm` | романшонь кель |
| `rn` | рундинь кель |
| `ro` | румынэнь кель |
| `ro_MD` | молдавонь кель |
| `rof` | ромбонь кель |
| `rom` | цыганонь кель |
| `root` | васень кель |
| `ru` | рузонь кель |
| `rup` | арумынэнь кель |
| `rw` | киньяруандань кель |
| `rwk` | руандань кель |
| `sa` | санскритэнь кель |
| `sad` | сандавень кель |
| `sah` | сахань кель |
| `sam` | Самариянь арамеень кель |
| `saq` | самбурунь кель |
| `sas` | сасаконь кель |
| `sat` | санталинь кель |
| `sba` | нгамбаень кель |
| `sbp` | сангунь кель |
| `sc` | сардинэнь кель |
| `scn` | сицилиень кель |
| `sco` | шотландонь кель |
| `sd` | синдхинь кель |
| `sdh` | пелечиёнксонь курдонь кель |
| `se` | пелевеёнксонь саамонь кель |
| `see` | сенекань кель |
| `seh` | сенань кель |
| `sel` | селькупонь кель |
| `ses` | койраборо сеннинь кель |
| `sg` | сангонь кель |
| `sga` | ташто ирландонь кель |
| `sh` | сербскохорватонь кель |
| `shi` | ташельхитэнь кель |
| `shn` | шанонь кель |
| `shu` | чадский арабонь кель |
| `si` | сингалень кель |
| `sid` | сидамань кель |
| `sk` | словаконь кель |
| `sl` | словенэнь кель |
| `sm` | самоань кель |
| `sma` | чикуншкань саамонь кель |
| `smj` | луле-саамонь кель |
| `smn` | инари-саамонь кель |
| `sms` | колтта-саамонь кель |
| `sn` | шонань кель |
| `snk` | сонинкень кель |
| `so` | сомалинь кель |
| `sog` | согдиень кель |
| `sq` | албанонь кель |
| `sr` | сербень кель |
| `srn` | сранан-тонгонь кель |
| `srr` | серерэнь кель |
| `ss` | свазинь кель |
| `ssy` | сахонь кель |
| `st` | пелечиёнксонь сотонь кель |
| `su` | сунданонь кель |
| `suk` | сукумань кель |
| `sus` | сусунь кель |
| `sux` | шумерэнь кель |
| `sv` | шведэнь кель |
| `sw` | суахилинь кель |
| `sw_CD` | конголезский суахилинь кель |
| `swb` | коморонь кель |
| `syc` | классический сириень кель |
| `syr` | сириень кель |
| `ta` | тамилень кель |
| `te` | телугунь кель |
| `tem` | темнень кель |
| `teo` | тесонь кель |
| `ter` | теренонь кель |
| `tet` | тетумонь кель |
| `tg` | таджикень кель |
| `th` | таень кель |
| `ti` | тигриньянь кель |
| `tig` | тигрень кель |
| `tiv` | тивинь кель |
| `tk` | туркменэнь кель |
| `tkl` | токелаень кель |
| `tl` | тагалогонь кель |
| `tlh` | клингононь кель |
| `tli` | тлингитэнь кель |
| `tmh` | тамашекень кель |
| `tn` | тсванань кель |
| `to` | тонганонь кель |
| `tog` | тонгань кель |
| `tpi` | ток-писинэнь кель |
| `tr` | Турциянь кель |
| `tru` | туройонь кель |
| `trv` | седекень кель |
| `ts` | тсонгань кель |
| `tsi` | цимшианонь кель |
| `tt` | татаронь кель |
| `tum` | тумбукань кель |
| `tvl` | тувалунь кель |
| `tw` | твинь кель |
| `twq` | тасаваконь кель |
| `ty` | таитянонь кель |
| `tyv` | тувинэнь кель |
| `tzm` | куншка атлассонь тамазигхтэнь кель |
| `udm` | удмуртонь кель |
| `ug` | уйгуронь кель |
| `uga` | угаритэнь кель |
| `uk` | украинэнь кель |
| `umb` | умбундунь кель |
| `und` | апак содань кель |
| `ur` | урдунь кель |
| `uz` | узбекень кель |
| `vai` | ваинь кель |
| `ve` | вендань кель |
| `vi` | вьетнамонь кель |
| `vo` | волапюконь кель |
| `vot` | водонь кель |
| `vun` | вунджонь кель |
| `wa` | валлононь кель |
| `wae` | валлисэнь кель |
| `wal` | воламонь кель |
| `war` | вараень кель |
| `was` | вашонь кель |
| `wbp` | вальбиринь кель |
| `wo` | волофонь кель |
| `wuu` | вунь кель |
| `xal` | калмыкень кель |
| `xh` | косань кель |
| `xog` | согань кель |
| `yao` | яонь кель |
| `yap` | японь кель |
| `yav` | янгбенэнь кель |
| `ybb` | йембань кель |
| `yi` | идишень кель |
| `yo` | йорубань кель |
| `yrk` | ненецень кель |
| `yue` | кантононь кель |
| `za` | чжуань кель |
| `zap` | сапотекень кель |
| `zbl` | блиссимволикань кель |
| `zen` | зенагонь кель |
| `zgh` | тамазигхтэнь кель |
| `zh` | китаень кель |
| `zh_Hans` | китаень кель, шождалгавтонь сёрма |
| `zh_Hant` | китаень кель, коень-кирдань сёрма |
| `zu` | зулунь кель |
| `zun` | зуньинь кель |
| `zxx` | аволь келень материал |
| `zza` | зазань кель |

### Script names

(Written in middle of sentence, selection list etc.)

### Territory names


(Written in middle of sentence, selection list etc.)

| ISO code | Name |
| -------- | ---- |
| `001` | мирмастор |
| `002` | Африка |
| `003` | Пелевеёнце Америка |
| `005` | Чипелеёнце Америка |
| `009` | Океания |
| `011` | Чивалгомань Африка |
| `013` | Куншка Америка |
| `014` | Чилисемань Африка |
| `015` | Пелевеёнце Африка |
| `017` | Куншка Африка |
| `018` | Африкань чипелеёнкс |
| `019` | Америка |
| `021` | Американь пелечеёнкс |
| `029` | Карибия |
| `030` | Чилисемань Азия |
| `034` | Чипелеёнце Азия |
| `035` | Чипеле-чилисемань Азия |
| `039` | Чипелеёнце Европа |
| `053` | Астралазия |
| `054` | Меланезия |
| `057` | Микронезия |
| `061` | Полинезия |
| `142` | Азия |
| `143` | Куншка Азия |
| `145` | Чивалгомань Азия |
| `150` | Европа |
| `151` | Чилисемань Европа |
| `154` | Пелевеёнце Европа |
| `155` | Чивалгомань Европа |
| `202` | Сахарадо чипелеёнце Африка |
| `419` | Латынэнь Америка |
