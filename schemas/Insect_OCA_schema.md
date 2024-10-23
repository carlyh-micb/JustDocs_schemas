---
layout: default  
title: Insect Counting  
parent: PEACE
---

# Schema information

**Name**: Insect Counting  
**Description**: A schema for insect counts developed at the University of Guelph as an ADC test schema  
**Classification**: CRDC:RDF40  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| analysisDate | Date of Analysis | Data of analysis of samples (all in a single day) |
| collectionDate | Date of Collection | Date of sample collection |
| insectCount | Insect Count | number of specified honeybees |
| insectType | Insect Type | species of honeybee counted and weighed |
| insectWeight | Insect Weight(s) | weights of honebees that were weighed: note not every collected bee was weighed |
| location | Campus location | Campus location where the samples were collected on the date of sample collection |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Insect Counting | A schema for insect counts developed at the University of Guelph as an ADC test schema |

## Selection lists

### English

#### insectType entry codes

| Entry code | Label |
| --- | --- |
| 501 | Carniolan honey bee |
| 527 | Russian honey bee |

#### location entry codes

| Entry code | Label |
| --- | --- |
| BAFF | Bedrock Aquifer Field Facility |
| TH | Townsend House |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding | Format rule |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| analysisDate | false |  | DateTime | Date of Analysis | Data of analysis of samples (all in a single day) | Not a list | utf-8 | YYYY\-MM\-DD |
| collectionDate | false |  | DateTime | Date of Collection | Date of sample collection | Not a list | utf-8 | YYYY\-MM\-DD |
| insectCount | false |  | Numeric | Insect Count | number of specified honeybees | Not a list | utf-8 | ^\[\+\-\]?\\d\+$ |
| insectType | false |  | Numeric | Insect Type | species of honeybee counted and weighed | Carniolan honey bee, Russian honey bee | utf-8 | ^\[\+\-\]?\\d\+$ |
| insectWeight | false | mg | Array[Numeric] | Insect Weight(s) | weights of honebees that were weighed: note not every collected bee was weighed | Not a list | utf-8 | ^\[\+\-\]?\\d\+$ |
| location | false |  | Text | Campus location | Campus location where the samples were collected on the date of sample collection | Bedrock Aquifer Field Facility, Townsend House | utf-8 | \[A\-Z\]\* |

## Schema SAIDs

**Capture base**: EVnvZJj9NrgJcyjB9Hltx6r1w1fi20mVG23vv7eI2sC8

| Layer | SAID |
| --- | --- |
| character_encoding | ETCBOek8JY83XCtZTOUyXlcnTczEdytLp-xpC7eDGRGY |
| entry (en) | EJUu256bPq40VO1IpbAyKDlErOZFbix141GerLcOfgh4 |
| entry_code | E3PGUpSlSQDrmDabXs4_neknGV-5eLYD-5VstMOBimRM |
| format | EufpjVNcqLKf1WjdaWEOeRNr8tO--B9XQrDgYMtgPbNE |
| information (en) | E0P9nrVxglX0G0nQxqUUT2M_-gUUAO-Il3zVBDfD-W4E |
| label (en) | EEx61pSoWiYrfcqavqh3xQl-WVGB9MAgOFRVCqXbUKjY |
| meta (en) | EKBw_KVlzdxI6tvopUHwdUc2DhmMrGWaZ3h7q1pWi-nA |
| unit | E_XuB6gNgVuOjy2pHQvD6wz1KZy8SPUsVTjxYiH0b250 |
