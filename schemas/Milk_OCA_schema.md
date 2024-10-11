---
layout: default  
title: Milk Aggregation  2
---

# Schema information

**Name**: Milk Aggregation  
**Description**: Aggregate data around milking events.  
**Classification**: RDF402  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| animal_id | Animal ID | Farm-level unique animal ID |
| begin_time | Begin time | Milking start time |
| date | Begin Date | Milking start date |
| dim | Days in milk | Days in Milk |
| duration | Duration | Milking Duration |
| end_date | End date | Milking end date |
| end_time | End time | Milking end time |
| lact_n | Lactation Number | The current lactation cycle the cow is in |
| milking_location | Milking Location | Location where animal was milked |
| session_n | Session Number | The current session (count) for the day (starting at midnight) that the cow has been milked in that day. |
| total_yield | Total Yield | Total Yield |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Milk Aggregation | Aggregate data around milking events. |

## Selection lists

### English

#### milking_location entry codes

| Entry code | Label |
| --- | --- |
| Rotary Parlour | Rotary Parlour |
| Tie Stall and Maternity | Tie Stall and Maternity |
| Voluntary Milking System | Voluntary Milking System |

## Schema details

### English

| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| animal_id | true |  | Numeric | Animal ID | Farm-level unique animal ID | Not a list | utf-8 | true | ^\-?\[0\-9\]\+$ |
| begin_time | false |  | DateTime | Begin time | Milking start time | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |
| date | false |  | DateTime | Begin Date | Milking start date | Not a list | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |
| dim | false | days | Numeric | Days in milk | Days in Milk | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| duration | false |  | DateTime | Duration | Milking Duration | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |
| end_date | false |  | DateTime | End date | Milking end date | Not a list | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |
| end_time | false |  | DateTime | End time | Milking end time | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |
| lact_n | false |  | Numeric | Lactation Number | The current lactation cycle the cow is in | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| milking_location | false |  | Text | Milking Location | Location where animal was milked | Rotary Parlour, Tie Stall and Maternity, Voluntary Milking System | utf-8 | false | ^\.\{0,50\}$ |
| session_n | false |  | Numeric | Session Number | The current session (count) for the day (starting at midnight) that the cow has been milked in that day. | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |
| total_yield | false | L | Numeric | Total Yield | Total Yield | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |

## Schema SAIDs

**Capture base**: ElQVB8ffr4TdvPvCgxmHjZxhUR_JcPkuLRpuHY1oU7HA

| Layer | SAID |
| --- | --- |
| character_encoding | EKwa4p3qiRjizl-bhiVy-sC5jd8FzNLyhL842vbEGpXM |
| conformance | ECj97Q3zZQYLyuyHli2x7rLvLaPKmpKkurPnnPMD9wbY |
| entry (en) | EIbRDpClXxWw202M3D5sTYPq5G4ZnLEta8FvK9lclunQ |
| entry_code | E6AuDvomYlHQ6k9HMRUCRYQnkESaGPZzh17CkVgsltPo |
| format | EDozfjgDRT3YzWoGo23E2VYt-Nh4iepYMc3kf02Uh1u4 |
| information (en) | EU-VGxKVUPBqBPqdQvi_pdLBduJvFIjrQJZHKHlBsAvM |
| label (en) | EgOwKdgjdcEP5y0l8Nx8RmpU74GKB-opBZj7LF-Y1hFc |
| meta (en) | EUmhlW5XLF7GtyZeToaaP0XNcaOKD61s_48bFCX6J-sw |
| unit | EaN1jMNQamXdPTRm-CB4Si5Oj6kt3xjmE2BjXkOzT664 |
