---
layout: default
title: Soil
---



## Schema information
**Name**: soil  
**Description**: A schema describing soil samples together with water content measurements.  
**Classification**: RDF401  
## Schema quick view
| Attribute | Label | Description |
| --- | --- | --- |
| collect_date |  |  |
| collect_time |  |  |
| date_in |  |  |
| date_out |  |  |
| duration |  |  |
| farm |  |  |
| final_mass |  |  |
| initial_mass |  |  |
| latitude |  |  |
| longitude |  |  |
| moisture |  |  |
| paddock_id |  |  |
| sample_id |  |  |
| sample_type |  |  |
| samplers |  |  |
| temperature |  |  |
| time_in |  |  |
| time_out |  |  |
## International schema information
| Language | Name | Description |
| --- | --- | --- |
| English | soil | A schema describing soil samples together with water content measurements. |
## Selection lists
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
## Schema details
### English
| Attribute | Sensitive | Unit | Type | Label | Description | List | Character encoding | Required entry | Format rule | Cardinality |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| collect_date | false |  | DateTime |  |  | Not a list | utf-8 | true | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| collect_time | false |  | DateTime |  |  | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |
| date_in | false |  | DateTime |  |  | Not a list | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| date_out | false |  | DateTime |  |  | Not a list | utf-8 | false | ^\(?:\(?:19\|20\)\\d\{2\}\)\-\(?:0\[1\-9\]\|1\[0\-2\]\)\-\(?:0\[1\-9\]\|\[1\-2\]\\d\|3\[0\-1\]\)$ |  |
| duration | false |  | DateTime |  |  | Not a list | utf-8 | false | ^P\(?\!$\)\(\(\\d\+Y\)\|\(\\d\+\.\\d\+Y$\)\)?\(\(\\d\+M\)\|\(\\d\+\.\\d\+M$\)\)?\(\(\\d\+W\)\|\(\\d\+\.\\d\+W$\)\)?\(\(\\d\+D\)\|\(\\d\+\.\\d\+D$\)\)?\(T\(?=\\d\)\(\(\\d\+H\)\|\(\\d\+\.\\d\+H$\)\)?\(\(\\d\+M\)\|\(\\d\+\.\\d\+M$\)\)?\(\\d\+\(\.\\d\+\)?S\)?\)??$/gm |  |
| farm | true |  | Text |  |  | Hensall farm, Guelph farm north, Guelph farm south, Lakeridge farm | utf-8 | true | ^\[A\-Z\]\*$ |  |
| final_mass | false | g | Numeric |  |  | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| initial_mass | false | g | Numeric |  |  | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| latitude | true |  | Text |  |  | Not a list | utf-8 | false |  |  |
| longitude | true |  | Text |  |  | Not a list | utf-8 | false |  |  |
| moisture | false | % | Numeric |  |  | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| paddock_id | false |  | Numeric |  |  | Not a list | utf-8 | false | ^\-?\[0\-9\]\+$ |  |
| sample_id | false |  | Text |  |  | Not a list | utf-8 | false | ^\.\{0,250\}$ |  |
| sample_type | false |  | Text |  |  | Not a list | utf-8 | false | ^\.\{0,50\}$ |  |
| samplers | true |  | Array[Text] |  |  | Aedan, Isabella, Lila, Makhi, Nathan, Zara | utf-8 | false | ^\.\{0,250\}$ | -6 |
| temperature | false | C | Numeric |  |  | Not a list | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |  |
| time_in | false |  | DateTime |  |  | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |
| time_out | false |  | DateTime |  |  | Not a list | utf-8 | false | ^\(\[01\]\[0\-9\]\|2\[0\-3\]\):\[0\-5\]\[0\-9\]:\[0\-5\]\[0\-9\]$/gm |  |
## Schema SAIDs
**Capture base**: EALZtciYP_Tn97BFilKL3C8ofMxF-xrswDmU9NC4CP9M
| Layer | SAID |
| --- | --- |
| cardinality | EHwYQEnhhxdIEcX2qOHKepHWs5UapeXoN5Xmpx1gy2e8 |
| character_encoding | EWbdH5fTs6PDkwjGN3JpW8kB1WGSu73VEe77hFoHq-JY |
| conformance | E0IURbDZk0bwQTtMTJVVuzk8ZW-0rQXv_yv1w6feRSGc |
| entry (en) | Ejs_hdLk8rmW4l0-RWZp7DR1j26k-UZfPfETko6x2agQ |
| entry_code | E01njgd7Lyp2UC83Wj5BK6cmBClg3jHIMFnPbB-4VCmg |
| format | EoQMU2ESg5hE2dMyp1VeajHpTH3FCrN0HmhRBahRBZ1o |
| information (en) | E6M8hstaDkOFApSRKqKwind2h56salwxkpesOMF5AnGI |
| label (en) | E5v2clKbavN57XXb7V-SvJD_tCAdUdMSc8MYom0ndTbM |
| meta (en) | EXVnFBxzM8qatUMOCJbg8dK89f3BhB7RCggHzjaHQt_s |
| unit | EuLp7LOvXjBcfwplInBR3aM2Oa-7VY3wVP2y7ReSbvok |
