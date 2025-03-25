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
**Schema package SAID**: EDdOZC4DApIvNmA3ESv5bpbl5GnaiwjU3h7t8ypg6WtA  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| collect_date | Collection Date | The date of sample collection |
| collect_time | Collection Time | The time of sample collection |
| date_in | Date In | The date the sample entered the lab |
| date_out | Date Out | The date the sample left the lab |
| duration | Duration | The duration of the sample collection |
| farm | Farm | The farm where the sample was collected |
| final_mass | Final Mass | The final mass of the sample |
| initial_mass | Initial Mass | The initial mass of the sample |
| latitude | Latitude | The latitude where the sample was taken |
| longitude | Longitude | The longitude where the sample was taken |
| moisture | Moisture | The moisture content of the sample |
| paddock_id | Paddock ID | The paddock ID where the sample was collected |
| sample_id | Sample ID | The unique identifier for the sample |
| sample_type | Sample Type | The type of sample |
| samplers | Samplers | The people who collected the sample |
| temperature | Temperature | The temperature at the time of sample collection |
| time_in | Time In | The time the sample entered the lab |
| time_out | Time Out | The time the sample left the lab |

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

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Cardinality |
| --- | --- | --- | --- | --- | --- | --- | --- |
| collect_date | false |  | DateTime | utf-8 | true | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| collect_time | false |  | DateTime | utf-8 | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |
| date_in | false |  | DateTime | utf-8 | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| date_out | false |  | DateTime | utf-8 | false | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |  |
| duration | false |  | DateTime | utf-8 | false | ^P\(?\!$\)\(\(\\d\+Y\)\|\(\\d\+\\\.\\d\+Y\)\)?\(\(\\d\+M\)\|\(\\d\+\\\.\\d\+M\)\)?\(\(\\d\+W\)\|\(\\d\+\\\.\\d\+W\)\)?\(\(\\d\+D\)\|\(\\d\+\\\.\\d\+D\)\)?\(T\(?=\\d\)\(\(\\d\+H\)\|\(\\d\+\\\.\\d\+H\)\)?\(\(\\d\+M\)\|\(\\d\+\\\.\\d\+M\)\)?\(\\d\+\(\\\.\\d\+\)?S\)?\)?$ |  |
| farm | false |  | Text | utf-8 | true | ^\[A\-Z\]\*$ |  |
| final_mass | false | g | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| initial_mass | false | g | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| latitude | false |  | Text | utf-8 | false | ^\[NS\]\\s?\(?:\[0\-8\]?\\d\)°\\s?\(?:\[0\-5\]?\\d\)'?\\s?\(?:\[0\-5\]?\\d\(?:\\\.\\d\+\)?\)\\"?$ |  |
| longitude | false |  | Text | utf-8 | false | ^\[EW\]\\s?\(?:\[0\-1\]?\[0\-7\]?\\d\)°\\s?\(?:\[0\-5\]?\\d\)'?\\s?\(?:\[0\-5\]?\\d\(?:\\\.\\d\+\)?\)\\"?$ |  |
| moisture | false | % | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| paddock_id | false |  | Numeric | utf-8 | false | ^\-?\[0\-9\]\+$ |  |
| sample_id | false |  | Text | utf-8 | false | ^\.\{0,250\}$ |  |
| sample_type | false |  | Text | utf-8 | false | ^\.\{0,50\}$ |  |
| samplers | false |  | Text | utf-8 | false | ^\.\{0,250\}$ | -6 |
| temperature | false | C | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| time_in | false |  | DateTime | utf-8 | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |
| time_out | false |  | DateTime | utf-8 | false | ^\(\[01\]\\d\|2\[0\-3\]\):\(\[0\-5\]\\d\):\(\[0\-5\]\\d\)$ |  |

## Language-specific schema details

### French

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| collect_date | Date de collecte | La date de prélèvement de l'échantillon | Not a list |
| collect_time | Heure de collecte | L'heure de prélèvement de l'échantillon | Not a list |
| date_in | Date d'entrée | La date d'entrée de l'échantillon au laboratoire | Not a list |
| date_out | Date de sortie | La date de sortie de l'échantillon du laboratoire | Not a list |
| duration | Durée | La durée du prélèvement de l'échantillon | Not a list |
| farm | Ferme | La ferme où l'échantillon a été prélevé | Ferme Hensall, Ferme Guelph nord, Ferme Guelph sud, Ferme Lakeridge |
| final_mass | Masse finale | La masse finale de l'échantillon | Not a list |
| initial_mass | Masse initiale | La masse initiale de l'échantillon | Not a list |
| latitude | Latitude | La latitude où l'échantillon a été prélevé | Not a list |
| longitude | Longitude | La longitude où l'échantillon a été prélevé | Not a list |
| moisture | Humidité | Le contenu en eau de l'échantillon | Not a list |
| paddock_id | ID de paddock | L'ID du paddock où l'échantillon a été prélevé | Not a list |
| sample_id | ID de l'échantillon | L'identifiant unique de l'échantillon | Not a list |
| sample_type | Type d'échantillon | Le type d'échantillon | Not a list |
| samplers | Préleveurs | Les personnes ayant prélevé l'échantillon | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| temperature | Température | La température au moment du prélèvement de l'échantillon | Not a list |
| time_in | Heure d'entrée | L'heure d'entrée de l'échantillon au laboratoire | Not a list |
| time_out | Heure de sortie | L'heure de sortie de l'échantillon du laboratoire | Not a list |

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| collect_date | Collection Date | The date of sample collection | Not a list |
| collect_time | Collection Time | The time of sample collection | Not a list |
| date_in | Date In | The date the sample entered the lab | Not a list |
| date_out | Date Out | The date the sample left the lab | Not a list |
| duration | Duration | The duration of the sample collection | Not a list |
| farm | Farm | The farm where the sample was collected | Hensall farm, Guelph farm north, Guelph farm south, Lakeridge farm |
| final_mass | Final Mass | The final mass of the sample | Not a list |
| initial_mass | Initial Mass | The initial mass of the sample | Not a list |
| latitude | Latitude | The latitude where the sample was taken | Not a list |
| longitude | Longitude | The longitude where the sample was taken | Not a list |
| moisture | Moisture | The moisture content of the sample | Not a list |
| paddock_id | Paddock ID | The paddock ID where the sample was collected | Not a list |
| sample_id | Sample ID | The unique identifier for the sample | Not a list |
| sample_type | Sample Type | The type of sample | Not a list |
| samplers | Samplers | The people who collected the sample | Aedan, Isabella, Lila, Makhi, Nathan, Zara |
| temperature | Temperature | The temperature at the time of sample collection | Not a list |
| time_in | Time In | The time the sample entered the lab | Not a list |
| time_out | Time Out | The time the sample left the lab | Not a list |

## Schema SAIDs

**Capture base**: EBPlcLe2LNJD4aayAYB1Ey80tS7hnDYzh3jHhiaEmchY
**Bundle**: EH6-Olk7O3iOsdK1lU098EgKQS4cfg3Cf2WL4Sa-8koc
**Package**: EDdOZC4DApIvNmA3ESv5bpbl5GnaiwjU3h7t8ypg6WtA

| Layer | SAID | Type |
| --- | --- | --- |
| cardinality | ECZA169W_6xQmjlJ7KvVPETd7Xhy_vqPGbwHAMTwiRnF | spec/overlays/cardinality/1.1 |
| character_encoding | ELSAsYcdDpV8F6u6-ag503eEyclMtG1cjZXXXgHOVP93 | spec/overlays/character_encoding/1.1 |
| conformance | EFoQ9efABS4VQsvxvCf71GR95LocFDJe8f6ivYT6a9mK | spec/overlays/conformance/1.1 |
| entry (fra) | ECtylXA5bL-NPfBqLayEu3FXkYiOmeZRY_qRT4-bicKH | spec/overlays/entry/1.1 |
| entry (eng) | EDcn3YVKU4aFrAsZZJKSQbTU6Exw4r0hWyuE6O9TtbuK | spec/overlays/entry/1.1 |
| entry_code | EAgcq-7X4R7ULwg5AptR2jTfFxtEqM_3m3reQ6GX_wm3 | spec/overlays/entry_code/1.1 |
| format | EH8xq5laiAtM_0SurbAInrh_Aqrn8SSr3kfzvDlx2_XC | spec/overlays/format/1.1 |
| information (fra) | EAtR5RsYv5elebY4wvjjXg5LFGjOeZfwbNu0t1_EtPJe | spec/overlays/information/1.1 |
| information (eng) | EED84KC81T10cHQEZBok7RkI2h4cjV7-1Qhhc0NejC0X | spec/overlays/information/1.1 |
| label (fra) | EDtwB8TY_dyHgiZL6ISu9zvUT4PN6i3pg_W103RC1EEu | spec/overlays/label/1.1 |
| label (eng) | EMG8Qg5N69fhT8FklO_pCcgu8W5tXHgotG9AvJV5nETn | spec/overlays/label/1.1 |
| meta (fra) | EFtGbT7om7e-J1BoR91U2u0FFrDKdQiaYp9SklxH6G8E | spec/overlays/meta/1.1 |
| meta (eng) | EHNtZrZX2XN-yAAKvZ8POW0WMHLXuuUTKpJqVb2GNoM3 | spec/overlays/meta/1.1 |
| unit | EPE7f5bSFxb3WQykN5J7P5sbfoJnNFW5pIIW4FqdCG9_ | spec/overlays/unit/1.1 |
| ordering | EDoV6xer3KrlsjXBidJdn-zR59G2sEr7G9EPhcr5Ci33 | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-03-25 08:53:31

