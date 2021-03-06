# windkraftanlagen-SH

ETL zur Transformation von Daten über Windkraftanlagen in Schleswig-Holstein. 

Grundlage der Daten: https://opendata.schleswig-holstein.de/dataset/windkraftanlagen-2021-02-25

Aufbau:
- Daten aus der CSV Datei werden eingelesen
- Daten werden nach aktiv/inaktiv kategorisiert
- Leistung, Leistungsenheit und UTM Zone werded extrahiert
- UTM Koordinaten werden nach Längengrad und Breitengrad konvertiert



Notiz: 2021-03-06 - die CSV Datei hat weniger Spalten als das Excel Sheet, ausserdem ist der Aufbau anders.


last-update: uwe geercken - 2021-03-06
