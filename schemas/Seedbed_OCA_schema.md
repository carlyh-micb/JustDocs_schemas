---
layout: default  
title: Seedbed Quality Data - Residue Mass  
---

## Schema information

**Name**: Seedbed Quality Data - Residue Mass  
**Description**: I'd have to go back and obtain more information to fill this in appropriately - ME  
**Classification**: RDF401  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Field_ID | Field_ID |  |
| Method | Method |  |
| Plot | Plot |  |
| Project | Project |  |
| Quad_wet_wt | Quad_wet_wt | quadrat wet weight (g) in field |
| Timing | Timing |  |
| Tot_resid_plot_wt | Tot_resid_plot_wt | total residue plot weight (g) |
| Zone | Zone |  |
| date | date |  |
| dry_check1 | dry_check1 | dry check 1 (3 days) (g) |
| dry_check2 | dry_check2 | dry check 2 (4 days) (g) |
| dry_check3 | dry_check3 | dry check 3 |
| residue_dry_wt | residue_dry_wt | residue dry weight (g) |
| subsample_dry_wt | subsample_dry_wt | subsample dry weight difference (g) |
| subsample_mois | subsample_mois | subsample moisture (%) |
| subsample_wet_wt_field | subsample_wet_wt_field | subsample wet weight (g) in lab |
| subsample_wet_wt_lab | subsample_wet_wt_lab | subsample wet weight (g) in field |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Seedbed Quality Data - Residue Mass | I'd have to go back and obtain more information to fill this in appropriately - ME |

## Selection lists

### English

#### Method entry codes

| Entry code | Label |
| --- | --- |
| res_mass | Residual Mass |

#### Timing entry codes

| Entry code | Label |
| --- | --- |
| bp | before planting |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Field_ID | false |  | Numeric | Field_ID |  | Not a list | utf-8 | true |  |
| Method | false |  | Text | Method |  | Residual Mass | utf-8 | true |  |
| Plot | false |  | Numeric | Plot |  | Not a list | utf-8 | true |  |
| Project | false |  | Text | Project |  | Not a list | utf-8 | true |  |
| Quad_wet_wt | false | g | Numeric | Quad_wet_wt | quadrat wet weight (g) in field | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| Timing | false |  | Text | Timing |  | before planting | utf-8 | true |  |
| Tot_resid_plot_wt | false | g | Numeric | Tot_resid_plot_wt | total residue plot weight (g) | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| Zone | false |  | Numeric | Zone |  | Not a list | utf-8 | true |  |
| date | false |  | DateTime | date |  | Not a list | utf-8 | false |  |
| dry_check1 | false | g | Numeric | dry_check1 | dry check 1 (3 days) (g) | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| dry_check2 | false | g | Numeric | dry_check2 | dry check 2 (4 days) (g) | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| dry_check3 | false | g | Numeric | dry_check3 | dry check 3 | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| residue_dry_wt | false | g | Numeric | residue_dry_wt | residue dry weight (g) | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| subsample_dry_wt | false | g | Numeric | subsample_dry_wt | subsample dry weight difference (g) | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| subsample_mois | false | % | Numeric | subsample_mois | subsample moisture (%) | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| subsample_wet_wt_field | false | g | Numeric | subsample_wet_wt_field | subsample wet weight (g) in lab | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| subsample_wet_wt_lab | false | g | Numeric | subsample_wet_wt_lab | subsample wet weight (g) in field | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |

## Schema SAIDs

**Capture base**: EwJXNnC99ycJ_LTaIa9tnBV1SlcZj_cT-ypzbIBpHuJU

| Layer | SAID |
| --- | --- |
| character_encoding | E6RsnHPUM_aLgFpnfE8VflY2BolnzQp55S0KOVP_5uok |
| conformance | EZrxMgav_TE8w3A3qO3FVeHuouX2fPdPWk0iE0IGavys |
| entry (en) | EuOAvzVUZN2S3aektmA8rQmwzbqMmubolOmxk_eXPgTI |
| entry_code | EUDU9V7waF5CAbmMb9YyIWRUKCGkECggSmn3-qvJal_M |
| format | EcfmO-t6zC_KqTSCMJdaUUkK4SOBw_8ND0wPy0WWDzy4 |
| information (en) | EdjAfKOj1fKhLQ6b8LutfppiBbXX4UMNBy1ES8-5Za2s |
| label (en) | EGqqX4Nhy8PjmrGWrAnKN4ZzQM8MinOJuV_69A6PoDMQ |
| meta (en) | E8dpMnLdRKSUWSxcmp0fVNvI8YR9wcKY_fZdHHnnNqDw |
| unit | EXu8halVAVjfJeHlYzFF55H7tppnGNDM4mxds7bbpeoY |

**Date created**: 2024-11-15 11:49:06

