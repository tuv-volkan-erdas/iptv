# Türkische IPTV-Sender

114 Sender. Full HD wird bevorzugt; alternativ geprüfte Streams ab 720p. Die Auflösung steht beim Sendernamen.

## Playlist-URL

https://raw.githubusercontent.com/tuv-volkan-erdas/iptv/main/tuerkische-sender.m3u

## Prüfung am 30.10.2026

Für alle 100 Einträge wurde ein Videobild decodiert und dessen Auflösung gemessen. ATV wurde auf eine funktionierende 720p-Adresse umgestellt; NOW hat eine frisch abgerufene Streamadresse. Alle Einträge haben ein im Repository gespeichertes PNG-Logo.

Dies ist eine Momentaufnahme am Prüfstandort, keine Garantie für dauerhafte oder weltweite Erreichbarkeit. Manche Adressen enthalten zeitlich begrenzte Sitzungsparameter. Bei adaptiven Streams kann die Wiedergabequalität variieren. Details: pruefbericht.json.

## Quellen

Sender und Logodaten: https://github.com/iptv-org/iptv und https://github.com/iptv-org/database

Weitere Logos: offizielle Senderwebseiten sowie https://github.com/tv-logo/tv-logos (kostenlose persönliche Nutzung; Rechte an Logos verbleiben bei den jeweiligen Rechteinhabern).

## Aktualisierung am 01.11.2026

NOW wurde erneut mit 1280×720 geprüft und seine abgelaufene Streamadresse ersetzt. Beyaz TV wurde mit 1920×1080 geprüft und mit Logo ergänzt. Beide Prüfungen enthalten die Decodierung eines Videobildes. Die übrigen Sender wurden bei dieser Aktualisierung nicht erneut geprüft. NOW verwendet zeitlich begrenzte Streamadressen und kann erneute Aktualisierungen benötigen.

## Sendergruppen

- 01 | Große & überregionale Sender: 17 Sender
- 02 | Nachrichten & Wirtschaft: 14 Sender
- 03 | Musik: 15 Sender
- 04 | Kinder & Jugend: 6 Sender
- 05 | Sport: 5 Sender
- 06 | Regional & Lokal: 21 Sender
- 07 | Kultur & Bildung: 3 Sender
- 08 | Religion: 6 Sender
- 09 | Weitere Sender: 5 Sender
- 10 | Nicht durchgehend (Not 24/7): 22 Sender

Die Gruppe „Nicht durchgehend (Not 24/7)“ übernimmt die Kennzeichnung aus der iptv-org-Quellliste. Diese betrifft die Verfügbarkeit des gelisteten Streams und bedeutet nicht zwingend, dass der Fernsehsender selbst Sendepausen hat. Diese Zuordnung hat Vorrang vor Themen- und Regionalgruppen. Die übrigen Gruppen wurden anhand der Senderkategorien und redaktionell zugeordnet.

### Sport-Ergänzung und Gruppenkorrektur am 01.11.2026

Fenerbahçe TV wurde mit decodiertem Videobild in 1280×720 ergänzt. Habertürk TV steht auf Wunsch unter Nachrichten & Wirtschaft, Kanal 7 Avrupa unter Große & überregionale Sender; diese Ausnahmen haben Vorrang vor der Not-24/7-Kennzeichnung. TRT Spor konnte wegen HTTP-403-Antworten bei den Videosegmenten in keiner angebotenen Qualität bestätigt werden und wurde nicht ergänzt. Für NTV Spor wurde kein eigenständiger M3U-Livestream gefunden; der Betreiber führt NTVSPOR.NET als digitales Sportportal: https://www.dogusyayingrubu.com.tr/hakkimizda/markalarimiz/internet/ntvspor-net

### Weitere Ergänzungen am 01.11.2026

Neu mit decodiertem Videobild geprüft: teve2 (1080p), 24 TV (1080p), 360 (1080p), Dream Türk (720p), Euro D (720p), Number 1 TV (720p), TV4 (1080p), Kanal 7 (1080p), Ülke TV (720p), TV8,5 (1080p), Bloomberg HT (720p), Haber Global (720p). Alle zwölf Sender haben gespeicherte PNG-Logos. 360 und Haber Global stehen gemäß Kennzeichnung der Quellliste unter Nicht durchgehend.

Nicht ergänzt, weil in den geprüften Quellen kein funktionierender Stream ab 720p bestätigt wurde: CNN Türk, TRT Belgesel, TRT Spor, TRT Spor Yıldız, DMAX, TLC, TV100, Sözcü TV, Tele1, TVNET, Kral Pop TV und Show Türk. ATV Avrupa lieferte nur 576p. Die übrigen bestehenden Einträge wurden bei dieser Ergänzung nicht neu getestet.
