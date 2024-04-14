# Home Assistant Support by SmartLiving.Rocks
## SmartLiving Support Service VPN Add-on
[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FSmartLiving-Rocks%2FHomeAssistantSupport)

Dieses Add-on ermöglicht es Ihnen zu unserem Support Netzwerk einer Verbinung aufzubauen, ohne das dafür extra Ports auf Ihrem Router aufgemacht werden müssen. Das ist zum einen eine sehr unsichere Methode vor allem für unerfahrene Nutzer. Zum anderen ist es manchmal nicht möglich eine sichere Verbindung aufzubauen z.B. wenn Sie auf Ihrem Boot, Camper, Tiny Haus oder anderen Orten mit mobilem Internet Zugang befinden. 

### OpenVPN
Diese Add-On basiert auf OpenVPN und baut eine gesicherte Verbindung über ein virtuelles privates Netzwerk zu unserem Support auf. 

### Installation
#### OpenVPN Zugangsdaten hinterlegen (*.ovpn Datei speichern)
Die ovpn Datei die wir Ihne zugeschickt haben müssen Sie in dem Ordner `/shares` abspeichern. Benutzen Sie hierzu eine von Ihnen bevorzugte Methode wie SMB oder fügen Sie die datei manuell hinzu mit `File` oder `Coder`. Ich empfehle Coder, das können Sie über diesen Link direkt zu Home Assistant hinzufügen: https://my.home-assistant.io/redirect/supervisor_addon/?addon=a0d7b954_vscode Hier Zeigen wir Ihnen wie es geht:

![OVPN via VS Code zu Home Assistant folder shares hinzufügen SmartLiving Support VPN](https://raw.githubusercontent.com/SmartLiving-Rocks/Anleitungen/main/ovpn.gif)

#### SmartLiving VPN: Repository hinzufügen
Kopieren Sie den folgenden Code in die Zwischenablage:
`https://github.com/SmartLiving-Rocks/HomeAssistantSupport`
Klicken Sie auf `Einstellungen` dann `Add-Ons` dannach unten rechts in der Ecke auf `Add-on Store` und abschließend auf die drei Punkte untereinander oben recht in der Ecke `Repositories`. Fügen Sie den kopierten Code ein und Klicken auf `Hinzufügen` und dann auf `Schließen`. Das Addon ist jetzt zu Home Assistant hinzugefügt und weiter unten in der Add-on Liste zu finden.

#### SmartLiving VPN: Add-on installieren
Klicken Sie nun auf den Eintrag und es öffnet sich ein Fenster mit weiteren Informationen. Klicken Sie jetzt auf installieren. Nach ein paar minuten ist das Add-on installiert und Sie können es jetzt starten. Sie haben sich erfolgreich mit unserem Netzwerk verbunden. Zur überprüfung können Sie auf den Reiter `Logs` klicken und ggf. fehler erkennen.

#### SmartLiving VPN: Add-on Konfigurieren
Ändern Sie unter dem Reiter `Konfiguration` den Namen des OVPN Files, falls nötig. Der Name muss der gleich sein, mit dem Namen der OPNV Datei, die unter `/shares` abgespeichert ist. 

<img width="1149" alt="Name des OVPN Files ändern" src="https://github.com/SmartLiving-Rocks/HomeAssistantSupport/assets/76279896/46b4271a-0a51-426a-a6cd-489985994376">


### Support Administrator einrichten
Damit wir uns mit Ihrere Home Assistant Instanz verbinden können müssen Sie noch einen Benutzer anlegen und diesem Adminstrationssrechte vergeben. 
Nutzername: `SmartLiving`
Passwort: `Rocks369!`
Wir werden dass Passwort direkt nach unserem ersten Login ändern.

