
BEGIN_REFERENCE_MATERIAL
******************************************************************
OCA_READ_ME/1.0
This is a human-readable schema, based on the OCA schema standard.

Reference for Overlays Capture Architecture (OCA):
https://doi.org/10.5281/zenodo.7707467

Reference for OCA_READ_ME/1.0:
https://github.com/agrifooddatacanada/OCA_README

A schema describes details about a dataset.
In OCA, a schema consists of a capture_base which documents the attributes and their most basic features.
A schema may also contain overlays which add details to the capture_base.
For each overlay and capture_base, a hash of their original contents has been calculated and is reported here as the SAID value.

This README format documents the capture_base and overlays that were associated together in a single OCA Bundle.
OCA_MANIFEST lists all components of the OCA Bundle.
For the OCA_BUNDLE, each section between rows of ****'s contains the details of one "layer type/version" of the OCA Bundle.
******************************************************************
END_REFERENCE_MATERIAL

BEGIN_OCA_MANIFEST
******************************************************************
Package SAID/digest: EFzJbnJlKWXYAyVukni-JzXPFwqALzTq2_MQr4IuAiFF
Bundle SAID/digest: EFSiqVezLETLoYsFt1oEXI-udnL9agj9R2Nkd5N83f_w

spec/capture_base/1.1 SAID/digest: "EEs4WAywiDY8ScSrCWsw4fm75q9sdHeEnfP6S60cTsCt"
spec/overlays/meta/1.1 (fra) SAID/digest: "EBVzszq4ZBC9E_hL6vQagqvFMTX6QLL5i8LO2a7FmB1V"
spec/overlays/meta/1.1 (eng) SAID/digest: "EMKwjHRm8hIF8GK0dOGioXgwZfqf_zcPszXj_6s_mMQ7"
spec/overlays/label/1.1 (fra) SAID/digest: "EArvPW6E1RUpmeRvCo860ccC0uYuR8yeg9fEWBXhkvG9"
spec/overlays/label/1.1 (eng) SAID/digest: "EM4mKhHhuYtz7Rycrw1K289IxxXwOHyqLy8A60FUZOg_"
spec/overlays/information/1.1 (fra) SAID/digest: "EB1kgm36RL2mcqcpMb8k__N2Usow9ipQquc-wHTcllDP"
spec/overlays/information/1.1 (eng) SAID/digest: "EM_eBnd5d7Td0hvEn1URDvQDVcyOgisRf-EaMakdpLv8"
spec/overlays/unit/1.1 SAID/digest: "ENZg3YRCFINxFNxAUXlQWTAXpFRok2MXQnXiMrbF285W"
spec/overlays/conformance/1.1 SAID/digest: "ED5KEcUrNHS7HkLQ45lqqH9vzsKrt38_Q3gxPjHyPXH8"
spec/overlays/format/1.1 SAID/digest: "EE9m3B-pSvlfqJEOi2nyIOMsgBJjEfx3KSsSdoYNodeg"
spec/overlays/entry_code/1.1 SAID/digest: "EDsl7KOkieN90UXtCedSIUsCtJIiqHTK8Ii-hwFw84Ls"
spec/overlays/entry/1.1 (eng) SAID/digest: "ECUgIzLlZXBMhFbx-AdPxhBnfpN189yyup4yK4GoX3tU"
spec/overlays/entry/1.1 (fra) SAID/digest: "EDnLflWG_tivtEnJiWHmQe4dI9l1c2IOoTTB0sBjPSZo"

community/overlays/adc/ordering/1.1 SAID/digest: "EPOY9fKzN2jfV3xjCWW7XotenGgQsQryS5KfI6vJyedK"
community/overlays/adc/unit_framing/1.1 SAID/digest: "EM30Z6puh1ehTaHoKWb2G_xPhlZ6M9RqLXRAuZEXwYol"
******************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
******************************************************************
Layer name: spec/capture_base/1.1
SAID/digest: EEs4WAywiDY8ScSrCWsw4fm75q9sdHeEnfP6S60cTsCt
Classification: RDF401

Schema attributes: data type
    farm: Text
    sample_type: Text
    collect_date: DateTime
    collect_time: DateTime
    latitude: Text
    longitude: Text
    duration: DateTime
    paddock_id: Numeric
    samplers: Array[Text]
    sample_id: Text
    date_in: DateTime
    temperature: Numeric
    time_in: DateTime
    initial_mass: Numeric
    date_out: DateTime
    final_mass: Numeric
    time_out: DateTime
    moisture: Numeric

******************************************************************
Layer name: spec/overlays/meta/1.1
SAID/digest: EBVzszq4ZBC9E_hL6vQagqvFMTX6QLL5i8LO2a7FmB1V
Language: fra
Description: Un schéma décrivant des échantillons de sol avec des mesures de contenu en eau.

Layer name: spec/overlays/meta/1.1
SAID/digest: EMKwjHRm8hIF8GK0dOGioXgwZfqf_zcPszXj_6s_mMQ7
Language: eng
Description: A schema describing soil samples together with water content measurements.

******************************************************************
Layer name: spec/overlays/label/1.1
SAID/digest: EArvPW6E1RUpmeRvCo860ccC0uYuR8yeg9fEWBXhkvG9
Language: fra
Schema attributes: spec/overlays/label/1.1
    farm: Ferme
    sample_type: Type d'échantillon
    collect_date: Date de collecte
    collect_time: Heure de collecte
    latitude: Latitude
    longitude: Longitude
    duration: Durée
    paddock_id: ID de paddock
    samplers: Préleveurs
    sample_id: ID de l'échantillon
    date_in: Date d'entrée
    temperature: Température
    time_in: Heure d'entrée
    initial_mass: Masse initiale
    date_out: Date de sortie
    final_mass: Masse finale
    time_out: Heure de sortie
    moisture: Humidité

Layer name: spec/overlays/label/1.1
SAID/digest: EM4mKhHhuYtz7Rycrw1K289IxxXwOHyqLy8A60FUZOg_
Language: eng
Schema attributes: spec/overlays/label/1.1
    farm: Farm
    sample_type: Sample Type
    collect_date: Collection Date
    collect_time: Collection Time
    latitude: Latitude
    longitude: Longitude
    duration: Duration
    paddock_id: Paddock ID
    samplers: Samplers
    sample_id: Sample ID
    date_in: Date In
    temperature: Temperature
    time_in: Time In
    initial_mass: Initial Mass
    date_out: Date Out
    final_mass: Final Mass
    time_out: Time Out
    moisture: Moisture

******************************************************************
Layer name: spec/overlays/information/1.1
SAID/digest: EB1kgm36RL2mcqcpMb8k__N2Usow9ipQquc-wHTcllDP
Language: fra
Schema attributes: spec/overlays/information/1.1
    farm: La ferme où l'échantillon a été prélevé
    sample_type: Le type d'échantillon
    collect_date: La date de prélèvement de l'échantillon
    collect_time: L'heure de prélèvement de l'échantillon
    latitude: La latitude où l'échantillon a été prélevé
    longitude: La longitude où l'échantillon a été prélevé
    duration: La durée du prélèvement de l'échantillon
    paddock_id: L'ID du paddock où l'échantillon a été prélevé
    samplers: Les personnes ayant prélevé l'échantillon
    sample_id: L'identifiant unique de l'échantillon
    date_in: La date d'entrée de l'échantillon au laboratoire
    temperature: La température au moment du prélèvement de l'échantillon
    time_in: L'heure d'entrée de l'échantillon au laboratoire
    initial_mass: La masse initiale de l'échantillon
    date_out: La date de sortie de l'échantillon du laboratoire
    final_mass: La masse finale de l'échantillon
    time_out: L'heure de sortie de l'échantillon du laboratoire
    moisture: Le contenu en eau de l'échantillon

Layer name: spec/overlays/information/1.1
SAID/digest: EM_eBnd5d7Td0hvEn1URDvQDVcyOgisRf-EaMakdpLv8
Language: eng
Schema attributes: spec/overlays/information/1.1
    farm: The farm where the sample was collected
    sample_type: The type of sample
    collect_date: The date of sample collection
    collect_time: The time of sample collection
    latitude: The latitude where the sample was taken
    longitude: The longitude where the sample was taken
    duration: The duration of the sample collection
    paddock_id: The paddock ID where the sample was collected
    samplers: The people who collected the sample
    sample_id: The unique identifier for the sample
    date_in: The date the sample entered the lab
    temperature: The temperature at the time of sample collection
    time_in: The time the sample entered the lab
    initial_mass: The initial mass of the sample
    date_out: The date the sample left the lab
    final_mass: The final mass of the sample
    time_out: The time the sample left the lab
    moisture: The moisture content of the sample

******************************************************************
Layer name: spec/overlays/unit/1.1
SAID/digest: ENZg3YRCFINxFNxAUXlQWTAXpFRok2MXQnXiMrbF285W
Measurement system: undefined

Schema attributes: spec/overlays/unit/1.1
    temperature: C
    initial_mass: g
    final_mass: g
    moisture: %

******************************************************************
Layer name: spec/overlays/conformance/1.1
SAID/digest: ED5KEcUrNHS7HkLQ45lqqH9vzsKrt38_Q3gxPjHyPXH8

Schema attributes: spec/overlays/conformance/1.1
    farm: M
    sample_type: O
    collect_date: M
    collect_time: O
    latitude: O
    longitude: O
    duration: O
    paddock_id: O
    samplers: O
    sample_id: O
    date_in: O
    temperature: O
    time_in: O
    initial_mass: O
    date_out: O
    final_mass: O
    time_out: O
    moisture: O

******************************************************************
Layer name: spec/overlays/format/1.1
SAID/digest: EE9m3B-pSvlfqJEOi2nyIOMsgBJjEfx3KSsSdoYNodeg

Schema attributes: spec/overlays/format/1.1
    farm: ^[A-Z]*$
    sample_type: ^.{0,50}$
    collect_date: ^(\d{4})-(0[1-9]|1[0-2])-(0[1-9]|[12]\d|3[01])$
    collect_time: ^([01]\d|2[0-3]):([0-5]\d):([0-5]\d)$
    latitude: ^[NS]\s?(?:[0-8]?\d)°\s?(?:[0-5]?\d)'?\s?(?:[0-5]?\d(?:\.\d+)?)\"?$
    longitude: ^[EW]\s?(?:1[0-7]\d|0?\d{1,2})°\s?(?:[0-5]?\d)'?\s?(?:[0-5]?\d(?:\.\d+)?)\"?$
    duration: ^P(?!$)((\d+Y)|(\d+\.\d+Y))?((\d+M)|(\d+\.\d+M))?((\d+W)|(\d+\.\d+W))?((\d+D)|(\d+\.\d+D))?(T(?=\d)((\d+H)|(\d+\.\d+H))?((\d+M)|(\d+\.\d+M))?(\d+(\.\d+)?S)?)?$
    paddock_id: ^-?[0-9]+$
    sample_id: ^.{0,250}$
    date_in: ^(\d{4})-(0[1-9]|1[0-2])-(0[1-9]|[12]\d|3[01])$
    temperature: ^[-+]?\d*\.?\d+$
    time_in: ^([01]\d|2[0-3]):([0-5]\d):([0-5]\d)$
    initial_mass: ^[-+]?\d*\.?\d+$
    date_out: ^(\d{4})-(0[1-9]|1[0-2])-(0[1-9]|[12]\d|3[01])$
    final_mass: ^[-+]?\d*\.?\d+$
    time_out: ^([01]\d|2[0-3]):([0-5]\d):([0-5]\d)$
    moisture: ^[-+]?\d*\.?\d+$

******************************************************************
Layer name: spec/overlays/entry_code/1.1
SAID/digest: EDsl7KOkieN90UXtCedSIUsCtJIiqHTK8Ii-hwFw84Ls

Schema attributes: spec/overlays/entry_code/1.1
    farm: [A,B,C,D]
    samplers: [Aedan,Isabella,Lila,Makhi,Nathan,Zara]

******************************************************************
Layer name: spec/overlays/entry/1.1
SAID/digest: ECUgIzLlZXBMhFbx-AdPxhBnfpN189yyup4yK4GoX3tU
Schema attributes: spec/overlays/entry/1.1
    farm: Hensall farm, Guelph farm north, Guelph farm south, Lakeridge farm
    samplers: Aedan, Isabella, Lila, Makhi, Nathan, Zara

Layer name: spec/overlays/entry/1.1
SAID/digest: EDnLflWG_tivtEnJiWHmQe4dI9l1c2IOoTTB0sBjPSZo
Schema attributes: spec/overlays/entry/1.1
    farm: Ferme Hensall, Ferme Guelph nord, Ferme Guelph sud, Ferme Lakeridge
    samplers: Aedan, Isabella, Lila, Makhi, Nathan, Zara

******************************************************************
END_OCA_BUNDLE

BEGIN_OCA_PACKAGE_EXTENSIONS
******************************************************************
Layer name: community/overlays/adc/ordering/1.1
SAID/digest: EPOY9fKzN2jfV3xjCWW7XotenGgQsQryS5KfI6vJyedK
Attribute ordering: farm, sample_type, collect_date, collect_time, latitude, longitude, duration, paddock_id, samplers, sample_id, date_in, temperature, time_in, initial_mass, date_out, final_mass, time_out, moisture
Entry code ordering:
    farm: A, B, C, D
    samplers: Aedan, Isabella, Lila, Makhi, Nathan, Zara

******************************************************************
Layer name: community/overlays/adc/unit_framing/1.1
SAID/digest: EM30Z6puh1ehTaHoKWb2G_xPhlZ6M9RqLXRAuZEXwYol

Schema attributes: community/overlays/adc/unit_framing/1.1
   final_mass: unit: g, UCUM code: g
   initial_mass: unit: g, UCUM code: g
   moisture: unit: %, UCUM code: %
   temperature: unit: C, UCUM code: Cel

******************************************************************
END_OCA_PACKAGE_EXTENSIONS
