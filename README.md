# sessionplan

sessionplan ist dafür da, Sessionpläne für Barcamps digital zu verwalten 
und auf beliebigen Devices anzuzeigen.

sessionplan wird in PHP programmiert. Die Anzeige auf den jeweiligen Devices
wird mit CSS und JavaScript umgesetzt. Ein eigener, individueller Sessionplan, 
wird local im LocalStorage des Browsers in dem Device gespeichert.

Die Sessionpläne sollen als JSON-Dateien auf dem Server abgelegt werden.

## Barcamps verwalten
Für Barcamps können Templates mit Räumen und Zeitslots angelegt werden. 
Auf deren Basis können dann für einzelne Tage Sessionpläne erstellt werden. 

## Sessionpläne anzeigen
Der Sessionplan für einen Tag eines Barcamps wird als OnePager im Browser auf 
beliebigen Devices, Laptops, Tablets und Smartphones angemessen angezeigt. 
Es ist möglich, einzelne Sessions als interessant zu markieren. 
In jedem Zeitslot kann eine Session in den persönlichen Sessionplan eingetragen 
werden. Die Einstellungen werden auf dem Device im LocalStorage des Browsers 
gespeichert.

## Sessionplan-API zum Abrufen des Sessionplanes für beliebige Anwendungen
Die Infos zu einem Sessionplan sollen in einer WEB-API zur Verfügung gestellt 
werden. Der API-Zugang ist unter anderem für IOT-Barcamp-Uhren auf Basis 
von ESP32-Boards mit integriertem TFT-Display gedacht. Die Barcamp-Uhren sollen 
beim AGILE.RUHR Camp im April 2025 in den Räumen anzeigen, welche Session in 
dem Raum stattfindet.