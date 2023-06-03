# Datenuebertragung
Es ist wichtig in der Medizin zu ermöglichen Daten effizient und sicher zu übertragen. Ich habe ein App programmiert, sie sich beim Einsatz von Rettungskräften gut machen lässt, um Daten schnell und sicher mit HL7 zu übertragen

## App Idee
Die Idee ist, den Prozess für die rettungskräfte zu optimieren, sodass die Lebensrettung auf alle fälle gelingt!
Es ist eine noch nicht ganz fertige Version, die Rettungskräfte folgendes ermöglicht: 
Notfall anzulegen  
![python 03 06 2023 03_11_00](https://github.com/maluka59/Datenuebertragung/assets/83926085/b4c2dde4-3133-47a0-b72d-ae62067e4462)
Weiterhin Patientendaten aufnehmen und Messungen dokumentieren 
![python 03 06 2023 03_11_23](https://github.com/maluka59/Datenuebertragung/assets/83926085/d99f506e-37a8-40c1-b50c-e27f93f1c2cb)
Und nachdem alles erfolgte wird per Spracherkennung die Einschätzung des Notarztes erfasst
![python 03 06 2023 03_12_06](https://github.com/maluka59/Datenuebertragung/assets/83926085/cbe316af-bb1b-4f18-a15f-dbdd3b3c75ac)
Abschießend werden alle diese Daten mit HL7-Protokoll (Health Level Seven) an das zuständige KH mit Sockets und TCP Verbindungen gesendet.
Dies erleichtet sowohl die Rettungskräfte als auch das Personal in den Khs, um besser kommunizieren zu können

https://github.com/maluka59/Datenuebertragung/assets/83926085/e9f7de95-8588-4eab-83e6-2ef1b7dda6c5

