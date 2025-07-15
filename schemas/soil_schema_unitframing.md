---
layout: default  
title: soil  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: soil  
**Description**: A schema describing soil samples together with water content measurements.  
**Classification**: RDF401  
**Author**: Carly  
**Author Email**: carly.huitema@gmail.com  
**Schema package SAID**: EFzJbnJlKWXYAyVukni-JzXPFwqALzTq2_MQr4IuAiFF  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| farm | Farm | The farm where the sample was collected |
| sample_type | Sample Type | The type of sample |
| collect_date | Collection Date | The date of sample collection |
| collect_time | Collection Time | The time of sample collection |
| latitude | Latitude | The latitude where the sample was taken |
| longitude | Longitude | The longitude where the sample was taken |
| duration | Duration | The duration of the sample collection |
| paddock_id | Paddock ID | The paddock ID where the sample was collected |
| samplers | Samplers | The people who collected the sample |
| sample_id | Sample ID | The unique identifier for the sample |
| date_in | Date In | The date the sample entered the lab |
| temperature | Temperature | The temperature at the time of sample collection |
| time_in | Time In | The time the sample entered the lab |
| initial_mass | Initial Mass | The initial mass of the sample |
| date_out | Date Out | The date the sample left the lab |
| final_mass | Final Mass | The final mass of the sample |
| time_out | Time Out | The time the sample left the lab |
| moisture | Moisture | The moisture content of the sample |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| French | sol | Un schéma décrivant des échantillons de sol avec des mesures de contenu en eau. |
| English | soil | A schema describing soil samples together with water content measurements. |

## Selection lists

### French

#### farm entry codes

| Entry code | Label |
| --- | --- |
| A | Ferme Hensall |
| B | Ferme Guelph nord |
| C | Ferme Guelph sud |
| D | Ferme Lakeridge |

#### samplers entry codes

| Entry code | Label |
| --- | --- |
| Aedan | Aedan |
| Isabella | Isabella |
| Lila | Lila |
| Makhi | Makhi |
| Nathan | Nathan |
| Zara | Zara |

### English

#### farm entry codes

| Entry code | Label |
| --- | --- |
| A | Hensall farm |
| B | Guelph farm north |
| C | Guelph farm south |
| D | Lakeridge farm |

#### samplers entry codes

| Entry code | Label |
| --- | --- |
| Aedan | Aedan |
| Isabella | Isabella |
| Lila | Lila |
| Makhi | Makhi |
| Nathan | Nathan |
| Zara | Zara |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Cardinality | Unit Framing |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| farm | false |  | Text |  | true | ^\[A\-Z\]\*$ |  |
| sample_type | false |  | Text |  | false | ^\.\{0,50\}$ |  |
| collect_date | false |  | DateTime |  | true | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| collect_time | false |  | DateTime |  | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |
| latitude | false |  | Text |  | false | ^\[NS\]\\s?\(?:\[0\-8\]?\\d\)°\\s?\(?:\[0\-5\]?\\d\)'?\\s?\(?:\[0\-5\]?\\d\(?:\\\.\\d\+\)?\)\\"?$ |  |
| longitude | false |  | Text |  | false | ^\[EW\]\\s?\(?:1\[0\-7\]\\d\|0?\\d\{1,2\}\)°\\s?\(?:\[0\-5\]?\\d\)'?\\s?\(?:\[0\-5\]?\\d\(?:\\\.\\d\+\)?\)\\"?$ |  |
| duration | false |  | DateTime |  | false | ^P\(?\!$\)\(\(\\d\+Y\)\|\(\\d\+\\\.\\d\+Y\)\)?\(\(\\d\+M\)\|\(\\d\+\\\.\\d\+M\)\)?\(\(\\d\+W\)\|\(\\d\+\\\.\\d\+W\)\)?\(\(\\d\+D\)\|\(\\d\+\\\.\\d\+D\)\)?\(T\(?=\\d\)\(\(\\d\+H\)\|\(\\d\+\\\.\\d\+H\)\)?\(\(\\d\+M\)\|\(\\d\+\\\.\\d\+M\)\)?\(\\d\+\(\\\.\\d\+\)?S\)?\)?$ |  |
| paddock_id | false |  | Numeric |  | false | ^\-?\[0\-9\]\+$ |  |
| samplers | false |  | Array[Text] |  | false |  | -6 |
| sample_id | false |  | Text |  | false | ^\.\{0,250\}$ |  |
| date_in | false |  | DateTime |  | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| temperature | false | C | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  | Cel |
| time_in | false |  | DateTime |  | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |
| initial_mass | false | g | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  | g |
| date_out | false |  | DateTime |  | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| final_mass | false | g | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  | g |
| time_out | false |  | DateTime |  | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |
| moisture | false | % | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  | % |

## Language-specific schema details

### French

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| farm | Ferme | La ferme où l\'échantillon a été prélevé | Ferme Hensall, Ferme Guelph nord, Ferme Guelph sud, Ferme Lakeridge |
| sample_type | Type d'échantillon | Le type d\'échantillon | Not a list |
| collect_date | Date de collecte | La date de prélèvement de l\'échantillon | Not a list |
| collect_time | Heure de collecte | L\'heure de prélèvement de l\'échantillon | Not a list |
| latitude | Latitude | La latitude où l\'échantillon a été prélevé | Not a list |
| longitude | Longitude | La longitude où l\'échantillon a été prélevé | Not a list |
| duration | Durée | La durée du prélèvement de l\'échantillon | Not a list |
| paddock_id | ID de paddock | L\'ID du paddock où l\'échantillon a été prélevé | Not a list |
| samplers | Préleveurs | Les personnes ayant prélevé l\'échantillon | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| sample_id | ID de l'échantillon | L\'identifiant unique de l\'échantillon | Not a list |
| date_in | Date d'entrée | La date d\'entrée de l\'échantillon au laboratoire | Not a list |
| temperature | Température | La température au moment du prélèvement de l\'échantillon | Not a list |
| time_in | Heure d'entrée | L\'heure d\'entrée de l\'échantillon au laboratoire | Not a list |
| initial_mass | Masse initiale | La masse initiale de l\'échantillon | Not a list |
| date_out | Date de sortie | La date de sortie de l\'échantillon du laboratoire | Not a list |
| final_mass | Masse finale | La masse finale de l\'échantillon | Not a list |
| time_out | Heure de sortie | L\'heure de sortie de l\'échantillon du laboratoire | Not a list |
| moisture | Humidité | Le contenu en eau de l\'échantillon | Not a list |

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| farm | Farm | The farm where the sample was collected | Hensall farm, Guelph farm north, Guelph farm south, Lakeridge farm |
| sample_type | Sample Type | The type of sample | Not a list |
| collect_date | Collection Date | The date of sample collection | Not a list |
| collect_time | Collection Time | The time of sample collection | Not a list |
| latitude | Latitude | The latitude where the sample was taken | Not a list |
| longitude | Longitude | The longitude where the sample was taken | Not a list |
| duration | Duration | The duration of the sample collection | Not a list |
| paddock_id | Paddock ID | The paddock ID where the sample was collected | Not a list |
| samplers | Samplers | The people who collected the sample | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| sample_id | Sample ID | The unique identifier for the sample | Not a list |
| date_in | Date In | The date the sample entered the lab | Not a list |
| temperature | Temperature | The temperature at the time of sample collection | Not a list |
| time_in | Time In | The time the sample entered the lab | Not a list |
| initial_mass | Initial Mass | The initial mass of the sample | Not a list |
| date_out | Date Out | The date the sample left the lab | Not a list |
| final_mass | Final Mass | The final mass of the sample | Not a list |
| time_out | Time Out | The time the sample left the lab | Not a list |
| moisture | Moisture | The moisture content of the sample | Not a list |

## Schema SAIDs

**Capture base**: EEs4WAywiDY8ScSrCWsw4fm75q9sdHeEnfP6S60cTsCt

**Bundle**: EFSiqVezLETLoYsFt1oEXI-udnL9agj9R2Nkd5N83f_w

**Package**: EFzJbnJlKWXYAyVukni-JzXPFwqALzTq2_MQr4IuAiFF

| Layer | SAID | Type |
| --- | --- | --- |
| cardinality | ELZEAN8WLZ_BoO0WTEyC3yyoXUfXFgs41WuK8p_gMz7B | spec/overlays/cardinality/1.1 |
| conformance | ED5KEcUrNHS7HkLQ45lqqH9vzsKrt38_Q3gxPjHyPXH8 | spec/overlays/conformance/1.1 |
| entry (eng) | ECUgIzLlZXBMhFbx-AdPxhBnfpN189yyup4yK4GoX3tU | spec/overlays/entry/1.1 |
| entry (fra) | EDnLflWG_tivtEnJiWHmQe4dI9l1c2IOoTTB0sBjPSZo | spec/overlays/entry/1.1 |
| entry_code | EDsl7KOkieN90UXtCedSIUsCtJIiqHTK8Ii-hwFw84Ls | spec/overlays/entry_code/1.1 |
| format | EE9m3B-pSvlfqJEOi2nyIOMsgBJjEfx3KSsSdoYNodeg | spec/overlays/format/1.1 |
| information (fra) | EB1kgm36RL2mcqcpMb8k__N2Usow9ipQquc-wHTcllDP | spec/overlays/information/1.1 |
| information (eng) | EM_eBnd5d7Td0hvEn1URDvQDVcyOgisRf-EaMakdpLv8 | spec/overlays/information/1.1 |
| label (fra) | EArvPW6E1RUpmeRvCo860ccC0uYuR8yeg9fEWBXhkvG9 | spec/overlays/label/1.1 |
| label (eng) | EM4mKhHhuYtz7Rycrw1K289IxxXwOHyqLy8A60FUZOg_ | spec/overlays/label/1.1 |
| meta (fra) | EBVzszq4ZBC9E_hL6vQagqvFMTX6QLL5i8LO2a7FmB1V | spec/overlays/meta/1.1 |
| meta (eng) | EMKwjHRm8hIF8GK0dOGioXgwZfqf_zcPszXj_6s_mMQ7 | spec/overlays/meta/1.1 |
| unit | ENZg3YRCFINxFNxAUXlQWTAXpFRok2MXQnXiMrbF285W | spec/overlays/unit/1.1 |
| ordering | EPOY9fKzN2jfV3xjCWW7XotenGgQsQryS5KfI6vJyedK | community/overlays/adc/ordering/1.1 |
| unit_framing | EM30Z6puh1ehTaHoKWb2G_xPhlZ6M9RqLXRAuZEXwYol | community/overlays/adc/unit_framing/1.1 |

**Date created**: 2025-07-15 13:42:01

