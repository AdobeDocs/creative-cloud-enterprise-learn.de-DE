---
title: Ablauf des Creative Cloud für die Enterprise- und Acrobat-Seriennummer
description: Ablauf der Seriennummer für Creative Cloud für Unternehmen und Acrobat
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Ablauf des Creative Cloud für die Enterprise- und Acrobat-Seriennummer

Historisch gesehen hat Adobe Seriennummern mit unseren Applikationen (z. B. Creative Suite, Creative Cloud für Unternehmen, Acrobat XI, Acrobat DC) an Kunden mit Enterprise Term License Agreements (ETLA) vergeben. Diese Seriennummern haben ein Ablaufdatum. Sobald das Ablaufdatum abgelaufen ist, funktioniert das Produkt nicht mehr. Daher ist es wichtig, die Migration zu planen, bevor Ihre Seriennummern ablaufen. Auf dieser Seite werden die erforderlichen Schritte beschrieben, um sicherzustellen, dass Ihre Endbenutzer weiterhin auf ihre Adobe-Applikationen und -Dienste zugreifen können.

## Überprüfen der Seriennummern auf Ablaufdatum

### Seriennummer(n) suchen

Die mit Ihrem ETLA-Vertrag verknüpften Seriennummernlizenzen sind über die [Adobe Licensing Website](https://licensing.adobe.com/) (LWS) verfügbar. Befolgen Sie diese Anweisungen zum Anzeigen und Herunterladen:

1. Melden Sie sich mit Ihrem Adobe ID und Kennwort bei der [Adobe Licensing Website](https://licensing.adobe.com/) (LWS) an.
1. Wählen Sie **Lizenzen > Seriennummern abrufen**.
1. Geben Sie Ihre **Endbenutzer-ID** oder **Endbenutzer-ID** ein.
1. (Optional) Wählen Sie einen **Produktnamen**, **Produktversion** oder **Plattform** aus, um die Ergebnisse zu filtern.
1. Klicken Sie auf Suchen.
1. Der Produktname und die Seriennummern werden angezeigt.
1. (Optional) Wählen Sie &quot;IN CSV EXPORTIEREN&quot;, um die Liste der Seriennummern herunterzuladen.

![Seriennummern suchen](assets/retrieveserialnumbers.png)

### Ablaufdatum überprüfen

Das [AdobeExpirationCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) ist ein Befehlszeilenprogramm für IT-Administratoren, mit dem Sie überprüfen können, ob Adoben auf einem Computer Seriennummern verwenden, die abgelaufen sind oder ablaufen. Das Tool zeigt Informationen wie den Produktlizenzbezeichner (LEID), die verschlüsselte Seriennummer und das Ablaufdatum an. Diese [Seite](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) enthält Anweisungen zum Herunterladen und Verwenden des Tools auf Mac- oder Windows-Computern.

## Erfahren Sie mehr über das Benutzererlebnis vor und nach Ablauf der Seriennummer

Sowohl Acrobat als auch Creative Cloud for Enterprise-Apps werden ab 60 Tagen vor Ablauf Nachrichten (in den Applikationen) angezeigt. Sobald die Seriennummer abgelaufen ist, funktionieren die Produkte nicht mehr und der Benutzer wird aufgefordert, Maßnahmen zu ergreifen.

### Creative Cloud für Unternehmenserfahrung

In den folgenden Informationen wird die Endbenutzererfahrung beschrieben. Im Folgenden finden Sie ein kurzes Video, gefolgt von einem Überblick über die Endbenutzererfahrung.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Vor Ablauf**

Ab 60 Tagen vor Ablauf der Seriennummer wird für alle Creative Cloud für Unternehmensanwendungen ein Dialogfeld im Produkt für den Endbenutzer angezeigt. Diese Meldung wird wöchentlich angezeigt, bis 30 Tage vor Ablauf, wird sie dann täglich bis zum Ablaufdatum angezeigt, das *Ihre Lizenz läuft ab. Dieses Adobe-Produkt verwendet eine Lizenz, die am 29. November 2020 ablaufen soll. Wenden Sie sich an Ihren Administrator, um einen kontinuierlichen Zugriff zu gewährleisten.*

![Meldung &quot;CCE vor Ablauf&quot;](assets/cceexpiring.png)

**Nach Ablauf**

Sobald die Seriennummer abgelaufen ist, haben die Benutzer keinen Zugriff mehr auf das Creative Cloud für Unternehmensanwendungen. Beim ersten Start nach Ablauf wird der Benutzer mit einem Dialogfeld aufgefordert, in dem *Die eingegebene Seriennummer ist abgelaufen. Dieses Produkt kann nicht lizenziert werden. Wenden Sie sich an den Support.*

![CCE nach Ablauf](assets/cceafterexpire.png)

Bei allen nachfolgenden Versuchen, die Applikationen zu starten, wird der Endbenutzer aufgefordert, **Jetzt anmelden** und anschließend die Option, ein eigenes Adobe ID zu erstellen und in den Testmodus zu wechseln. Ein vom Endbenutzer erstelltes neues Adobe ID wird jedoch nicht mit den Lizenzen Ihres Unternehmens verknüpft und führt zu zusätzlichen Verwirrungen bei den Benutzern. Um Geschäftsstörungen und/oder unnötige Verwirrung zu vermeiden, migrieren Sie Ihre Benutzer zur personengebundenen Lizenzierung, bevor Ihre Seriennummer(n) abläuft.

![CCE Sign in dialog 1](assets/ccesignin1.png)

![CCE Sign in dialog 2](assets/ccesignin2.png)

### Acrobat-Erfahrung

In den folgenden Informationen wird die Endbenutzererfahrung beschrieben. Im Folgenden finden Sie ein kurzes Video, gefolgt von einem Überblick über die Endbenutzererfahrung.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Vor Ablauf**

Ab 60 Tagen vor Ablauf der Seriennummer zeigt Acrobat eine In-Produkt-Popup-Meldung an den Endbenutzer an. Diese wird einmal wöchentlich bis 7 Tage vor Ablauf angezeigt. Sie wird dann täglich mit *Ihre Adobe Acrobat-Lizenz läuft am 11.30.2020 ab. Wenden Sie sich an Ihren Administrator, um Acrobat ohne Unterbrechung weiter zu verwenden.*

![Acrobat-Meldung für abgelaufenes Abonnement](assets/acrobatexpiring.png)

**Nach Ablauf**

Sobald die Seriennummer abgelaufen ist, haben die Benutzer keinen Zugriff mehr auf Acrobat. Beim ersten Start nach Ablauf wird der Benutzer mit einem Dialogfeld aufgefordert, in dem *Die eingegebene Seriennummer ist abgelaufen. Dieses Produkt kann nicht lizenziert werden. Wenden Sie sich an den Support.*

![Acrobat nach Ablauf](assets/acrobatafterexpire.png)

Bei allen nachfolgenden Versuchen, Acrobat zu starten, wird der Endbenutzer aufgefordert, **Jetzt anmelden** und anschließend die Option, ein eigenes Adobe ID zu erstellen und in den Testmodus zu wechseln. Ein vom Endbenutzer erstelltes neues Adobe ID wird jedoch nicht mit den Lizenzen Ihres Unternehmens verknüpft und führt zu zusätzlichen Verwirrungen bei den Benutzern.

![Acrobat Sign in dialog 1](assets/acrobatsignin1.png)

![Acrobat Sign in dialog 2](assets/acrobatsignin2.png)

## Wenden Sie sich an uns, wenn Sie Hilfe benötigen

Wenn Sie Fragen zur Verwendung des [AdobeExpirationCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html)-Tools haben oder Hilfe beim Migrieren von der Seriennummernbereitstellung zu einem benannten Benutzer benötigen, haben Sie einige Optionen:
* Senden Sie eine E-Mail an das Adobe Enterprise Onboarding Team - **entonb@adobe.com**
* Support-Ticket in [Admin Console](https://adminconsole.adobe.com/support) öffnen
* Wenden Sie sich an Ihren Adobe Account Manager oder Customer Success Manager.
