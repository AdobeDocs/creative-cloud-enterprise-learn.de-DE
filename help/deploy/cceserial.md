---
title: Informationen zum Ablauf der Creative Cloud für Unternehmen und Acrobat-Seriennummern
description: Informationen zum Ablauf der Seriennummer auf Creative Cloud für Unternehmen und Acrobat
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '844'
ht-degree: 3%

---

# Informationen zum Ablauf der Creative Cloud für Unternehmen und Acrobat-Seriennummern

Früher hat Adobe Kunden mit Enterprise Term License Agreements (ETLA) Seriennummern für unsere Anwendungen (z. B. Creative Suite, Creative Cloud für Unternehmen, Acrobat XI, Acrobat DC) ausgestellt. Diese Seriennummern haben ein Ablaufdatum. Sobald das Ablaufdatum verstrichen ist, funktioniert das Produkt nicht mehr. Daher ist es wichtig, Ihre Migration zu planen, bevor Ihre Seriennummern ablaufen. Auf dieser Seite werden die Schritte beschrieben, die erforderlich sind, um sicherzustellen, dass Ihre Endbenutzer weiterhin auf ihre Adobe-Programme und -Services zugreifen können.

## Überprüfen Ihrer Seriennummern auf ihr Ablaufdatum

### Seriennummer(n) suchen

Die Seriennummernlizenzen, die mit Ihrem ETLA-Vertrag verknüpft sind, sind über die [Adobe Licensing Website](https://licensing.adobe.com/) (LWS). Befolgen Sie diese Anweisungen zum Anzeigen und Herunterladen:

1. Anmelden bei [Adobe Licensing Website](https://licensing.adobe.com/) (LWS) mit Ihrer Adobe ID und Ihrem Kennwort.
1. Auswählen **Lizenzen > Seriennummern abrufen**.
1. Geben Sie Ihr **Endbenutzer-ID** oder **Empfangsberechtigten-ID**.
1. (Optional) Wählen Sie eine **Produktname**, **Produktversion** oder **Plattform** , um Ergebnisse zu filtern.
1. Klicken Sie auf Suchen.
1. Der Produktname und die Seriennummern werden angezeigt.
1. (Optional) Wählen Sie &quot;IN CSV EXPORTIEREN&quot;, um die Liste der Seriennummern herunterzuladen.

![Seriennummern suchen](assets/retrieveserialnumbers.png)

### Ablaufdatum überprüfen

Die [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) ist ein Befehlszeilenprogramm für IT-Administratoren, mit dem Sie überprüfen können, ob Adobe-Produkte auf einem Computer abgelaufene oder demnächst ablaufende Seriennummern verwenden. Das Tool zeigt Informationen wie den Lizenzbezeichner (LEID), die verschlüsselte Seriennummer und das Ablaufdatum an. Dieses [Seite](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) enthält Anweisungen zum Herunterladen und Verwenden des Tools auf Mac- oder Windows-Computern.

## Verständnis der Endbenutzererfahrung vor und nach Ablauf der Seriennummer

Sowohl Acrobat als auch Creative Cloud für Unternehmensanwendungen zeigen ab 60 Tage vor Ablauf Meldungen (in den Anwendungen) an. Sobald die Seriennummer abgelaufen ist, funktionieren die Produkte nicht mehr und der Benutzer wird aufgefordert, Maßnahmen zu ergreifen.

### Creative Cloud für Unternehmen

Die folgenden Informationen geben einen Überblick über die Benutzererfahrung. Im Folgenden finden Sie ein kurzes Video, gefolgt von einer Überprüfung der Endbenutzerfunktionen.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Vor Ablauf**

Ab 60 Tagen vor Ablauf der Seriennummer wird für alle Creative Cloud-Anwendungen für Unternehmen ein Dialogfeld im Produktdialogfeld für den Endbenutzer angezeigt. Diese Nachricht wird wöchentlich angezeigt, bis 30 Tage vor Ablauf, sie wird dann täglich angezeigt, bis das Ablaufdatum *Ihre Lizenz läuft ab. Dieses Adobe-Produkt verwendet eine Lizenz, die am 29. November 2020 abläuft. Wenden Sie sich an Ihren Administrator, um den unterbrechungsfreien Zugriff zu gewährleisten.*.

![CCE vor Ablauf](assets/cceexpiring.png)

**Nach Ablauf**

Sobald die Seriennummer abgelaufen ist, haben die Benutzer keinen Zugriff mehr auf die Creative Cloud für Unternehmensanwendungen. Beim ersten Start nach Ablauf wird dem Benutzer ein Dialogfeld mit der Meldung *Die eingegebene Seriennummer ist abgelaufen. Dieses Produkt kann nicht lizenziert werden. Wenden Sie sich an den Support.*.

![CCE nach Ablaufmeldung](assets/cceafterexpire.png)

Bei allen folgenden Versuchen, die Applikationen zu starten, wird der Endbenutzer aufgefordert, **Jetzt anmelden** gefolgt von der Option, eine eigene Adobe ID zu erstellen und in den Testmodus zu wechseln. Jede neue Adobe ID, die vom Endbenutzer erstellt wird, wird jedoch nicht mit den Lizenzen Ihres Unternehmens verknüpft und führt zu zusätzlichen Verwirrungen für die Benutzer. Um Unterbrechungen des Geschäftsbetriebs und/oder unnötige Verwechslungen zu vermeiden, migrieren Sie Ihre Benutzer zu personengebundenen Lizenzen, bevor Ihre Seriennummer(n) ablaufen.

![CCE Sign in dialog 1](assets/ccesignin1.png)

![CCE Sign in Dialog 2](assets/ccesignin2.png)

### Acrobat

Die folgenden Informationen geben einen Überblick über die Benutzererfahrung. Im Folgenden finden Sie ein kurzes Video, gefolgt von einer Überprüfung der Endbenutzerfunktionen.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Vor Ablauf**

Ab 60 Tagen vor Ablauf der Seriennummer zeigt Acrobat dem Endbenutzer eine Popup-Meldung im Produkt an. Dieses erscheint einmal pro Woche bis 7 Tage vor Ablauf. Es wird dann beginnen, täglich zu erscheinen, *Ihre Adobe Acrobat-Lizenz läuft am 30.11.2020 ab. Wenden Sie sich an Ihren Administrator, um Acrobat ohne Unterbrechung weiterhin zu verwenden.*

![Acrobat Ablaufmeldung](assets/acrobatexpiring.png)

**Nach Ablauf**

Sobald die Seriennummer abgelaufen ist, haben die Benutzer keinen Zugriff mehr auf Acrobat. Beim ersten Start nach Ablauf wird dem Benutzer ein Dialogfeld mit der Meldung *Die eingegebene Seriennummer ist abgelaufen. Dieses Produkt kann nicht lizenziert werden. Wenden Sie sich an den Support.*

![Acrobat nach Ablaufmeldung](assets/acrobatafterexpire.png)

Bei allen folgenden Versuchen, Acrobat zu starten, wird der Endbenutzer aufgefordert, **Jetzt anmelden** gefolgt von der Option, eine eigene Adobe ID zu erstellen und in den Testmodus zu wechseln. Jede neue Adobe ID, die vom Endbenutzer erstellt wird, wird jedoch nicht mit den Lizenzen Ihres Unternehmens verknüpft und führt zu zusätzlichen Verwirrungen für die Benutzer.

![Acrobat Sign in Dialog 1](assets/acrobatsignin1.png)

![Acrobat Sign in Dialog 2](assets/acrobatsignin2.png)

## Kontaktieren Sie uns, wenn Sie Hilfe benötigen

Wenn Sie Fragen zur Verwendung der [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) -Tool verwendet werden oder Hilfe bei der Migration von der Bereitstellung der Seriennummer zu einem benannten Benutzer benötigen, haben Sie einige Optionen:
* Senden Sie eine E-Mail an das Adobe Enterprise Onboarding-Team - **entonb@adobe.com**
* Öffnen Sie ein Support-Ticket in [Admin Console](https://adminconsole.adobe.com/support)
* Wenden Sie sich an Ihr Adobe-Kontoteam.
