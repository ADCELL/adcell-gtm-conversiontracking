# ADCELL - Conversion Tracking Tag Template

Dieses Template ermöglicht Advertisern die Einbindung des ADCELL Trackingcodes zum Transaktionstracking mittels Google Tag Manager.

### Inhalt: 
* [Installieren des Templates](#config)
* [Konfigurieren des Tags](#preparation)

## <a name="config"></a>Installieren des Templates
Es ist möglich diese Tag Vorlage direkt über die Community-Vorlagen im Google Tag Manager bei Anlage eines neuen Tags auszuwählen.
Eine manuelle Anlage ist aber auch möglich.

Manuelle Installation:

1. ZIP-Archiv downloaden und lokal entpacken
2. Im Google Tag Manager eine neue Vorlage anlegen
3. Über das erweiterte Menü "Importieren" auswählen 
4. Die Datei `template.tpl` aus dem ZIP-Archiv importieren
5. Die Vorlage speichern
6. Unter Tags einen neuen Tag anlegen und die Vorlage unter "benutzerdefiniert" auswählen 


## <a name="preparation"></a>Konfigurieren des Tags

Damit das Conversiontracking korrekt funktioniert. müssen die benutzerspezifischen Parameter bei der Konfigurations des Tags hinterlegt werden.

### Programm-ID
Hier muss die numerische ID der Kampagne bei ADCELL hinterlegt werden. Die ID der Kampagne findet sich im ADCELL Account in der Programmverwaltung. 

### Event-ID
Hier muss die numerische ID des Verkaufevents hinterlegt werden, das getrackt werden soll.
Die aktiven Events finden sich im ADCELL Account unter "Tracking".

### Referenz-Variable
Hier muss die Variable mit der eindeutigen Transaktionsreferenz hinterlegt werden.

### Betrags-Variable
Hier muss die Variable mit dem jeweiligen Betrag der zu trackenden Transaktion hinterlegt werden. Der Betrag muss mit Dezimalpunkt und zwei Nachkommastellen angegeben werden.
