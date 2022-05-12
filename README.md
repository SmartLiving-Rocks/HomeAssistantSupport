# Home Assistant Support by SmartLiving.Rocks
## SmartLiving Support Service VPN Add-on
Dieses Add-on ermöglicht es Ihnen zu unserem Support Netzwerk einer Verbinung aufzubauen, ohne das dafür extra Ports auf Ihrem Router aufgemacht werden müssen. Das ist zum einen eine sehr unsichere Methode vor allem für unerfahrene Nutzer. Zum anderen ist es manchmal nicht möglich eine sichere Verbindung aufzubauen z.B. wenn Sie auf Ihrem Boot, Camper, Tiny Haus oder anderen Orten mit mobilem Internet Zugang befinden. 

### OpenVPN
Diese Add-On basiert auf OpenVPN und baut eine gesicherte Verbindung über ein virtuelles privates Netzwerk zu unserem Support auf. 

### Installation
#### OpenVPN Zugangsdaten hinterlegen (*.ovpn Datei speichern)
Die ovpn Datei die wir Ihne zugeschickt haben müssen Sie in dem Ordner `/shares` abspeichern. Benutzen Sie hierzu eine von Ihnen bevorzugte Methode wie SMB oder fügen Sie die datei manuell hinzu mit `File` oder `Coder`. Hier Zeigen wir Ihnen wie es geht:

<Gif - manuelles hinzufügen>

#### Repository hinzufügen
Kopieren Sie den folgenden Code in die Zwischenablage:
`https://github.com/SmartLiving-Rocks/HomeAssistantSupport`
Klicken Sie auf `Einstellungen` dann `Add-Ons` dannach unten rechts in der Ecke auf `Add-on Store` und abschließend auf die drei Punkte untereinander oben recht in der Ecke `Repositories`. Fügen Sie den kopierten Code ein und Klicken auf `Hinzufügen` und dann auf `Schließen`. Das Addon ist jetzt zu Home Assistant hinzugefügt und weiter unten in der Add-on Liste zu finden.

#### Add-on installieren 
Klicken Sie nun auf den Eintrag und es öffnet sich ein Fenster mit weiteren Informationen. Klicken Sie jetzt auf installieren. Nach ein paar minuten ist das Add-on installiert und Sie können es jetzt starten. Sie haben sich erfolgreich mit unserem Netzwerk verbunden. Zur überprüfung können Sie auf den Reiter `Logs` klicken und ggf. fehler erkennen. 

### Support Administrator einrichten
Damit wir uns mit Ihrere Home Assistant Instanz verbinden können müssen Sie noch einen Benutzer anlegen und diesem Adminstrationssrechte vergeben. 
Nutzername: `SmartLiving`
Passwort: `Rocks369!`
Wir werden dass Passwort direkt nach unserem ersten Login ändern.

