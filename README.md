[[DE]](README.md)/[[EN]](README_en.md)

# THW Pegel API

Das Technisches Hilfswerk (THW) setzt Messkoffer, sogenannte Mobile-Pegel, zur Messung von Pegel an verschiedenen Stellen ein. Die Daten werden auf der zugehörigen  Seite ([Pegelkarte](http://www.thw-pegel.de/pegelkarte.php)) zur Verfügung gestellt.


Die zugehörige API gibt die Daten des jeweiligen Pegels zurück. Dabei kann der Pegel allerdings nicht ausgewählt werden, sondern es werden Serverseitig die Daten für den im Frontend ausgewählten Pegel zurückgegeben. Die API verfügt zudem nicht über eine `Access-Control-Allow-Origin: *` - Header, daher ist das Abrufen aus einem anderen Frontend wie zum Beispiel die Swagger UI nicht ohne eine Proxyserver möglich. Ein kostenfreier Proxyserver ist in der Server-Auswahl zum Testen der API auswählbar. Dieser Server verfügt gegebenenfalls über eine geringe Übertragungsgeschwindigkeit.



Diese Spezifikation ist keine offizielle Spezifikation des THWs. Bei Fragen zum Mobilen-Pegel wenden Sie sich direkt an das THW.

