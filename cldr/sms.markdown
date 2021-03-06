---
layout: default
title: "CLDR Skolt Saami"
---

## CLDR core data for Skolt Saami

Fill-in:

**Needed for requesting new locale**:


| Stuff | Values |
| --- | --- |
| Exemplar sets | ... |
| main characters | `[а â b c č ʒ ǯ d đ e f g ǧ ǥ h i j k ǩ l m n ŋ o õ p q r s š t u v w x y z ž å ä ö ʹ ʼ]` |
| auxiliary characters | `[ẹ ˈ á à ă ã ą ā ć ċ ç ď ð đ é è ê ě ë ė ę ē ģ ȟ ħ í î ï İ į ī ı ķ ĺ ľ ļ ł ń ň ñ ņ ó ò ô ő œ ŕ ř ś ŝ ş ș ß ť ţ ț ŧ ú ù û ů ű ų ū ý ÿ ü ź ż þ æ ø]` |
| index characters | `[А Â B C Č Ʒ Ǯ D Đ E Ẹ F G Ǧ Ǥ H I J K Ǩ L M N Ŋ O Õ P Q R S Š T U V W X Y Z Ž Å Ä Ö]` |
| numbers characters | `[  , % ‰ + − 0 1 2 3 4 5 6 7 8 9]` |
| punctuation characters | `[\- ‐ – , ; \: ! ? . … ’ ” » ( ) \[ \] § @ * / \\ \& #]` |
| Orientation | left-to-right |
| ... |  top-to-bottom |
| Plural rules | ... |
| one example | {0} peiʹvv  (inflect the word for day sg.)|
| other example | {0} peeiʹv |
| Country Data and Default Content | sms_FI |
| (Verify:) | https://www.unicode.org/cldr/charts/latest/supplemental/language_territory_information.html |
Skolt Sami sms Finland {OR} FI 610
| Romanization | Skolt Saami is already written in latin script |

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

Alphabetical order, (describe nearest language / Finnish, but 16 more glyphs: 
а â b c č ʒ ǯ d đ e ẹ f g ǧ ǥ h i j k ǩ l m n ŋ o õ p q r s š t u v w x y z ž å ä ö ʹ ʼ ˈ )

## CLDR minimal data for Uralic

**Needed soon after submitting new locale**.

### Required date-time formats

If the calendar used is not gregorian...

#### gregorian calendar

For most things, fill in full names and abbreviations (short and very short
i.e. 1–2 letters if one exists).

| ID-stuff | values |
| -------- | ------ |
| month 1 | ođđeeʹjjmään |
| month 2 | täʹlvvmään |
| month 3 | pâʹzzlâšttammään |
| month 4 | njuhččmään |
| month 5 | vueʹssmään |
| month 6 | ǩieʹssmään |
| month 7 | sueiʹnnmään |
| month 8 | påʹrǧǧmään|
| month 9 | čõhččmään |
| month 10 | rõõǥǥâdmään |
| month 11 | skamm-mään |
| month 12 | rosttovmään |
| (week)day sun | pâʹsspeiʹvv |
| (week)day mon | vuõssargg |
| (week)day tue | mââibargg |
| (week)day wed | seärad |
| (week)day thu | nelljdpeiʹvv |
| (week)day fri | piâtnâc |
| (week)day sat | sueʹvet |
| quarter 1 |  |
| quarter 2 |  |
| quarter 3 |  |
| quarter 4 |  |
| period of day midnight |  |
| period of day am |  |
| period of day noon |  |
| period of day pm |  |
| period of day morning1 | |
| period of day morning2 |  |
| period of day afternoon1 |  |
| period of day evening1 |  |
| period of day night1 |  |
| period of day midnight |  |
| period of day am |  |
| period of day noon |  |
| period of day pm |  |
| period of day morning1 |  |
| period of day morning2 |  |
| period of day afternoon1 |  |
| period of day evening1 |  |
| period of day night1 | |
| era BC |  |
| era BCE | |
| era AD |  |
| era ACE |  |

For formats examples are good: e.g. "on monday the 21. of June 1984",
"21.6.1984". "12:34"

| date format |  |
| time format |  |
| datetime format |  |
| Timezone | {0} {1} |
| interval format fallback | `{0}–{1}` |

### Important names in language

Language:

| `sms` | sääʹmǩiõll |

Country or territory:

| `FI` |  |
| `NO` |  |
| `RU` |  |

Currency:

| EUR | euro |
| one | euro |
| two | eurok |
| other | euroa |
|  symbol | € |
| narrow symbol | € |

### Datetime patterns

...

### Number formats

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
| Not a number |  |
| Time separator (Hours:Minutes) | : |

### Territories and cities in language area

E.g. timezones. Find correct examples from:

| Place code | Translation |
| ---------- | ----------- |
| 150 | Europe |
| FI | |
| RU | |
| Europe/Helsinki |  |
| Europe/Moscow |  |
| Europe_Eastern | |

### Timezone patterns

| Message | formatting |
| ------- | ---------- |
| Hours from UTC | +H:mm;-H:mm |
| GMT | UTC{0} |
| Time at Greenwich | UTC |
| regional |  |
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
| `calendar` |  |
| `cf` |  |
| `colAlternate` | |
| `colBackwards` | |
| `colCaseFirst` | |
| `colCaseLevel` | |
| `collation` | |
| `colNormalization` | |
| `colNumeric` | |
| `colStrength` | |
| `currency` | |
| `hc` | |
| `lb` | |
| `ms` | |
| `numbers` | |
| `timezone` | |
| `va` | |
| `x` | |

### Some time intervals

???

## More (all) CLDR data for $language

TODO
