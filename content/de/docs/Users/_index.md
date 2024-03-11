---
title: "Benutzer"
linkTitle: "Benutzer"
date: 2024-01-22        
weight: 250
---


Mit der Personen-App können Sie die Benutzerinformationen von Benutzern und Bibliotheksmitarbeitern verwalten. Sowohl die Benutzerdaten der Kunden als auch die des Bibliothekspersonals werden in der Benutzer-App gespeichert. Es gibt kein separates Verzeichnis oder eine App für Bibliotheksmitarbeiter. Der Unterschied zwischen einem Bibliotheksmitarbeiter und einem Kunden besteht darin, dass dem Benutzereintrag des Bibliotheksmitarbeiters FOLIO-Berechtigungen, ein Benutzername und ein Passwort zugewiesen sind.

Definition von Begriffen im Zusammenhang mit der Personen-App:

 -  **Benutzer.** Jede Person, die mit FOLIO interagiert oder Aufgaben darin ausführt. 

 -  **Personendatensatz.** Enthält Kontaktinformationen und Kennungen für einen einzelnen Benutzer. Es gibt Benutzerdatensätze sowohl für Benutzer als auch für Bibliothekspersonal. Eine Liste aller in einem Benutzerdatensatz enthaltenen Informationen finden Sie unter [Benutzerdatensatz anzeigen](#view-a-user-record). 

 -  **Berechtigung.** Ein einem Benutzer zugewiesener Wert, der ihm Zugriff auf FOLIO-Datensätze gewährt oder ihm die Ausführung bestimmter Aufgaben in FOLIO ermöglicht. 

 -  **Berechtigungsgruppe.** Eine Gruppe von Berechtigungen, die es einem Benutzer ermöglicht, eine bestimmte Aufgabengruppe auszuführen. Beispielsweise möchten Sie möglicherweise bestimmte Berechtigungen zusammenfassen, um job-spezifische Berechtigungsgruppen zu erstellen. Berechtigungsgruppen werden von Ihrer Bibliothek in [Einstellungen \> Personen \> Berechtigungsgruppen](../settings/settings\_users/settings\_users/#settings--users--permission-sets) definiert.

## Berechtigungen 

Mit den unten aufgeführten Berechtigungen können Sie mit der Benutzer-App interagieren und festlegen, was Sie in der App tun können und was nicht. Wenn einem Benutzer keine dieser Berechtigungen zugewiesen ist, kann er die Benutzer-App oder zugehörige Informationen nicht sehen. Weitere Informationen zu Berechtigungen finden Sie unter [Platform Essentials > Berechtigungen](../platform-essentials/permissions/). 

Nachfolgend sind alle Personenberechtigungen aufgeführt:

-  **Personenimport - Alle Berechtigungen.** Diese Berechtigung erlaubt es dem Benutzer, Personendatensätze zu importieren.  

-  **Person: Kann Exemplar-Sperren umgehen.** Diese Berechtigung ermöglicht es der Person, eine Exemplar-Sperre bei der Ausleihe zu umgehen. 

-  **Personen: Kann Kontosperren umgehen.** Diese Berechtigung ermöglicht es der Person, eine Kontosperre für die Ausleihe, Anfrage oder Verlängerung eines Exemplars in Ausleihe zu umgehen.

-  **Personen: Können Berechtigungen zuweisen und entziehen.** Diese Berechtigung ermöglicht es dem Benutzer, einem anderen Benutzer Berechtigungen zu- oder abzuerkennen. 

-  **Personen: Kann Servicestellen Personen zuweisen und die Zuweisung aufheben.** Diese Berechtigung ermöglicht es dem Benutzer, zugewiesene Servicestellen für Personen einzusehen und zu bearbeiten. Der Benutzer kann auch grundlegende Daten von Personen einsehen und bearbeiten.

-  **Personen: Können offene Transaktionen prüfen.** Diese Berechtigung ermöglicht es dem Benutzer, nach offenen Transaktionen in einem Benutzerdatensatz zu suchen. Wenn es keine offenen Transaktionen gibt, kann der Benutzerdatensatz gelöscht werden.

-  **Personen: Können einen neuen Benutzer erstellen.** Diese Berechtigung ermöglicht es dem Benutzer, einen neuen Datensatz für einen Benutzer zu erstellen und Benutzerinformationen, erweiterte Informationen und Kontaktinformationen zum Benutzerdatensatz hinzuzufügen. 

-  **Personen: Können Gebühren/Strafen erstellen, bearbeiten und entfernen.** Diese Berechtigung ermöglicht es dem Benutzer, Gebühren/Strafen zu erstellen, zu bearbeiten, zu entfernen und anzusehen.

-  **Personen: Können Kontosperren erstellen, bearbeiten und entfernen.** Diese Berechtigung ermöglicht es der Person, den Abschnitt Kontosperren im Datensatz des Benutzers zu sehen und Sperren zu bearbeiten und zu erstellen.

-  **Personen: Können Bevollmächtigte erstellen, bearbeiten und entfernen.** Diese Berechtigung ermöglicht es dem Benutzer, zugewiesene Bevollmächtigte eines Benutzers anzusehen und zu bearbeiten. Der Benutzer kann auch grundlegende Benutzerdatenelemente anzeigen und bearbeiten.

-  **Personen: Kann Benutzerprofil löschen, wenn der Benutzer keine offenen Transaktionen hat.** Mit dieser Berechtigung kann ein Benutzerprofil über die Benutzeroberfläche gelöscht werden, wenn der Benutzer keine offenen Transaktionen hat. Diese Berechtigung muss zusammen mit **Benutzer: Kann offene Transaktionen prüfen**.

-  **Personen: Kann Benutzerprofil bearbeiten.** Diese Berechtigung ermöglicht es dem Benutzer, die folgenden Abschnitte in einem Benutzerdatensatz zu bearbeiten und anzuzeigen: Benutzerinformationen, Erweiterte Informationen und Kontaktinformationen.

 -  **Personen: Können verlorene Gegenstände verarbeiten, für die tatsächliche Kosten erforderlich sind.** Mit dieser Berechtigung kann der Benutzer die Seite „Verlorene Gegenstände, für die eine Bearbeitung tatsächlicher Kosten erforderlich ist“ verwenden, um verlorene Gegenstände in Rechnung zu stellen. Die tatsächlichen Kosten werden in Nolana nicht vollständig umgesetzt. Es wird empfohlen, bis Orchid zu warten, um die Istkostenverarbeitung zu verwenden. 

-  **Personen: Können Gebühren/Strafen und Ausleihen einsehen.** Diese Berechtigung ermöglicht es Personen, Gebühren/Strafen und Ausleihen eines Benutzers einzusehen. 

-  **Personen: Können zugewiesene Berechtigungen für Personen einsehen.** Diese Berechtigung ermöglicht es dem Benutzer, die einem anderen Benutzer zugewiesenen Berechtigungen einzusehen. 

-  **Personen: Können zugewiesene Bevollmächtigte für Personen einsehen.** Diese Berechtigung ermöglicht es dem Benutzer, den Bereich Bevollmächtigte zu sehen, aber nicht die Bevollmächtigten, die einer Person zugewiesen sind, zu bearbeiten. Diese Berechtigung beinhaltet auch die Möglichkeit, zu suchen und Benutzerdatensätze (nur grundlegende Benutzerfelder) einzusehen.

-  **Personen: Können zugewiesene Servicestellen für Personen einsehen.** Diese Berechtigung ermöglicht es dem Benutzer, den Abschnitt Servicestellen zu sehen, aber keine Servicestellen zu bearbeiten, die einem Benutzer zugewiesen sind. Diese Berechtigung beinhaltet auch die Möglichkeit zu suchen und Benutzerdatensätze (nur grundlegende Benutzerfelder) einzusehen.

-  **Personen: Können das Konto anzeigen.** Diese Berechtigung ermöglicht es dem Benutzer, nach Datensätzen zu suchen und die folgenden Abschnitte in einem Datensatz anzuzeigen: Benutzerinformationen, erweiterte Informationen und Kontaktinformationen.

-  **Personen: Erstellen und Herunterladen des Kassenabgleichsberichts.** Diese Berechtigung ermöglicht es dem Benutzer, einen Kassenabgleichsbericht zu erstellen und herunterzuladen.

-  **Personen: Erstellen und herunterladen des Finanztransaktionsdetailberichts.** Diese Berechtigung ermöglicht es dem Benutzer, einen Finanztransaktionsdetailbericht zu erstellen und herunterzuladen. 

-  **Personen: erstellen und herunterladen Rückerstattungen zur manuellen Verarbeitung Bericht.** Diese Berechtigung ermöglicht es dem Benutzer, einen Bericht über Rückerstattungen zur manuellen Verarbeitung zu erstellen und herunterzuladen. 

-  **Personen: Passwort erstellen/zurücksetzen.** Diese Berechtigung ermöglicht es dem Benutzer, eine E-Mail zum Zurücksetzen des Passworts an einen Benutzer zu senden oder den Link zum Zurücksetzen des Passworts zu kopieren und mit einem Benutzer zu teilen, um die Funktion zum Zurücksetzen des Passworts zu nutzen.

-  **Personen: Benutzer-Ausleihen anonymisieren.** Diese Berechtigung ermöglicht es dem Benutzer, alle Benutzerdetails von einer Ausleihe zu entfernen. 

-   **Personen: Personen ändern das Fälligkeitsdatum der Ausleihe.** Diese Berechtigung ermöglicht es dem Benutzer, das Fälligkeitsdatum einer Ausleihe in einem anderen Benutzerdatensatz zu ändern. 

-   **Personen: Personen behaupten, sie hätten ausgeliehenes zurückgegeben.** Diese Berechtigung ermöglicht es dem Benutzer, den Status von ausgeliehenen Exemplaren auf "Angeblich zurückgegeben" zu ändern.

 -  **Personen: Benutzerleihen werden als verloren erklärt.** Mit dieser Berechtigung kann der Benutzer den Status ausgeliehener Exemplare in „Für verloren erklärt“ ändern. 

- **Personen: Zurückgeforderte Ausleihen verloren.** Diese Berechtigung erlaubt es dem Benutzer, den Status von ausgeliehenen, zurückgeforderten und zurückgegebenen Gegenständen auf "Vermisst" zu ändern.

-  **Personen: Verlängerungen von Medien.** Diese Berechtigung ermöglicht es der Personen, Ausleihen in dem Umfang zu verlängern der durch die Ausleihrichtlinie erlaubt ist.

-  **Personen: Personen erneuern Ausleihen durch Umgehen.** Diese Berechtigung erlaubt es dem Benutzer, fehlgeschlagene Verlängerungen zu umgehen.

-  **Personen: Ansicht der Ausleihen.** Diese Berechtigung ermöglicht es der Person, den Abschnitt Ausleihen in einem Personendatensatz einzusehen, die Ausleihseite und die Ausleihdetails zu betrachten. 

-  **Personen: Ansicht der Ausleihen von Personen, Änderung des Fälligkeitsdatums, Verlängerung.** Diese Berechtigung ermöglicht es einer Person, den Abschnitt Ausleihen in einem Personendatensatz einzusehen, das Fälligkeitsdatum einer Ausleihe zu ändern und Ausleihen zu verlängern.

-  **Personen: Bestandsanfragen anzeigen.** Diese Berechtigung ermöglicht es der Person, den Bereich Anfragen auf einem Personendatensatz einzusehen. Diese Berechtigung beinhaltet auch die Möglichkeit, Personendatensätze zu suchen und einzusehen (nur grundlegende Benutzerfelder).

## Tastenkürzel

Tastenkürzel ermöglichen es Ihnen, Aktionen in dieser App mit der Tastatur auszuführen. Siehe [Plattform Essentials > Tastenkürzel](..platform-essentials/keyboard-shortcuts/keyboardshortcuts/) für mehr Informationen.

## Erstellen eines Personendatensatzes manuell

1.  Klicken Sie im **Personen Suchergebnisse** Ausschnitt auf **Aktionen \> Neu**.

2.  Im Fenster **Benutzer erstellen**, füllen Sie die Abschnitte **Benutzerinformationen**, **Erweiterte Informationen** und **Kontaktinformationen** aus. Füllen Sie die Abschnitte **Benutzerdefinierte Felder** aus, wenn sie von Ihrer Institution konfiguriert wurden. Für mehr Informationen zu den Feldern und verfügbaren Aktionen in diesen Abschnitten, siehe die Abschnittsbeschreibungen unten.

3.  Sobald Sie alle Informationen über die Person eingegeben haben, klicken Sie auf **Speichern & Schließen**. Der Datensatz der Person wird gespeichert.

### Informationen über Personen

-   **Nachname (erforderlich).** Der Nachname der Person.

-   **Vorname.** Der Vorname der Person.

-   **Weitere Vornamen.** Die weiteren Vornamen der Person.

-  **Bevorzugter Vorname.** Der Name, mit dem die Person bevorzugt angesprochen wird. Wenn ein bevorzugter Vorname angegeben wird, wird dieser im Datensatz der Person anstelle des Vornamens angezeigt. 

-  **Benutzer-innengruppe (erforderlich).** Wählen Sie eine Benutzer-innengruppe aus, die der Person zugewiesen werden soll. Benutzer-innengruppen sind Klassen von Bibliotheksnutzenden, die in der Einstellungs-App Ihrer Bibliothek konfiguriert sind. Beispiele für Benutzer-innengruppen sind:

-   **Erwachsene.** Benutzende über 18 Jahre.

-   **Fakultät.** Personen mit dem Status eines Fakultätsmitglieds an Ihrer Einrichtung.

-   **Student.** Benutzende, die Studierende an Ihrer Institution sind.

Siehe [Einstellungen \> Personen \> Benutzer/-in Gruppen](../settings/settings\_users/settings\_users/#settings--users--patron-groups) für mehr Informationen.

-  **Status (erforderlich).** Wählen Sie einen Status für die Person: **Aktiv** oder **Inaktiv.** Der Status einer Person ist an das Ablaufdatum gekoppelt, das auf ihrem Datensatz festgelegt wurde. Aktiver Status zeigt eine laufende Zugehörigkeit, Beschäftigung oder Einschreibung innerhalb der Institution der Bibliothek an. Inaktiver Status zeigt an, dass das Ablaufdatum auf dem Datensatz der Person überschritten wurde und die Person nicht mehr zugehörig, beschäftigt oder eingeschrieben ist. Wenn eine **Benutzer-in Gruppe** ausgewählt wird, wird der **Status** automatisch auf **Aktiv** gesetzt.

-  **Ablaufdatum.** Die festgelegte Zeit, bevor der Datensatz einer Person abläuft und die Person keine aktiven Berechtigungen mehr hat oder die Möglichkeit, Exemplare auszuleihen. Das Ablaufdatum bestimmt, wann der Status einer Person von Aktiv zu Inaktiv wechselt. Das Ablaufdatum ist optional und dieses Feld kann leer gelassen werden. Informationen zur Bearbeitung eines Ablaufdatums finden Sie unter [Bearbeiten eines Ablaufdatums](#edit-an-expiration-date).

-  **Barcode.** Die Barcode-Nummer für die Bibliothekskarte der Person.

### Erweiterte Informationen

-  **Erfassungsdatum.** Das Datum, an dem eine Person an der Institution eingeschrieben ist. Dieses Feld wird automatisch ausgefüllt, wenn es in den von einem externen System bereitgestellten Quelldaten enthalten ist. 

-  **Externe System-ID.** Die externe System-ID für die Person. Dieses Feld wird automatisch ausgefüllt, wenn es in den von einem externen System bereitgestellten Quelldaten enthalten ist. 

-  **Geburtsdatum.** Das Geburtsdatum der Person im YYYY-MM-DD Format.

-  **Folio-Nummer.** Eine vom System generierte Nummer für den Datensatz des Benutzers.

-  **Anfragepräferenzen.** **Vormerkungsregal** ist standardmäßig für alle Personen ausgewählt. Wenn auch **Lieferung** ausgewählt ist, wählen Sie **Erfüllungspräferenz**. 

-  Wenn **Lieferung** als **Erfüllungspräferenz** ausgewählt ist, wählen Sie die **Standardlieferadresse** aus. Dieses Feld erscheint und ist nur erforderlich, wenn **Lieferung** als Anfragepräferenz ausgewählt ist. Adressen werden dem Benutzerdatensatz im Abschnitt **Kontaktinformationen** hinzugefügt. Siehe [Personen \> Kontaktinformationen] (#contact-information) für mehr Informationen.

-   Wenn **Vormerkungsregal** als **Erfüllungspräferenz** ausgewählt wird, wählen Sie die **Standardabhol-Servicestelle**. Alle Personendatensätze haben mindestens eine Servicestelle zugewiesen, um den Standort für die Ausleihe oder Abholung angeforderter Artikel anzugeben. Servicestellen werden von Ihrer Bibliothek in der Einstellungs-App konfiguriert. Siehe [Einstellungen \> Mandant \> Servicestellen](#../settings/settings\_tenant/settings\_tenant/#settings--tenant--service-points) für mehr Informationen.

-  **Name des Fachbereichs.** Name des Fachbereichs des Benutzers, falls zutreffend. Die Schaltfläche **Fachbereich hinzufügen** erscheint nur, wenn **Fachbereiche** in [Einstellungen \> Personen \> Fachbereiche](../settings/settings\_users/settings\_users/#settings--users--departments) konfiguriert sind.

-  Um die Person mit einem Fachbereich zu verknüpfen, klicken Sie auf **Fachbereich hinzufügen** und wählen Sie den Fachbereich aus der Dropdown-Liste aus. 

-  Löschen Sie den **Fachbereich** aus einem Persondatensatz, indem Sie auf das **Mülleimersymbol** klicken. 

-  **Kennung.** Der Name, den das Bibliothekspersonal verwendet, um sich bei FOLIO anzumelden. Anmerkung: Benutzende haben keine Kennung, da sie sich nicht bei FOLIO anmelden müssen.

-  **Passwort.** Personen können per E-Mail einen Link zum Zurücksetzen des Passworts erhalten. Dieser Link läuft nach 24 Stunden ab. Das Passwort muss die folgenden Standardvalidierungsregeln erfüllen:

  * Enthält mindestens 8 Zeichen.
  * Enthält sowohl Groß- als auch Kleinbuchstaben.
  * Enthält mindestens 1 numerisches Zeichen.
  * Enthält mindestens 1 Sonderzeichen.
  * Enthält nicht die Kennung.
  * Enthält keine Tastatursequenz.
  * Enthält nicht denselben Buchstaben.
  * Enthält kein(e) Leerzeichen.

Anmerkung: Die Institution kann unterschiedliche Regeln zur Passwortüberprüfung für ihre Personen festlegen. 

### Kontaktinformationen

-   **E-Mail (erforderlich).** Die E-Mail-Adresse der Person.

-   **Telefon.** Die Telefonnummer der Person.

-   **Mobiltelefon.** Die Mobiltelefonnummer der Person.

-   **Bevorzugter Kontakt (erforderlich).** Wählen Sie die bevorzugte Kontaktmethode des Benutzers aus: E-Mail, Post (Primäre Adresse) oder Textnachricht.

-   **Adresse.** Die Adresse der Person. Sie können mehrere Adressen hinzufügen. Um eine Adresse hinzuzufügen, klicken Sie auf **Adresse hinzufügen**. Wählen Sie **Als primäre Adresse verwenden** aus, wenn die Adresse als Hauptadresse der Person betrachtet wird. 

-   **Adresstyp.** Wählen Sie den passenden Adresstyp für die Adresse der Person aus. Adresstypen werden von Ihrer Bibliothek in der Einstellungs-App konfiguriert. Siehe [Einstellungen \> Personen \> Adresstypen](../settings/settings\_users/settings\_users/#settings--users--address-types) für mehr Informationen.

-  Füllen Sie die Adressinformationsfelder aus und klicken Sie auf **Adresse hinzufügen**, um die Adresse im Datensatz des Benutzers zu speichern. 

### Benutzerdefinierte Felder

Der Abschnitt **Benutzerdefinierte Felder** wird nur angezeigt, wenn er in der App **Einstellungen>Personen** konfiguriert ist. Informationen zur Konfiguration des Abschnitts **Benutzerdefinierte Felder** finden Sie unter [Einstellungen /> Personen /> Benutzerdefinierte Felder](../settings/settings\_users/settings\_users/#settings--users--custom-fields).

## Suchen Sie nach Personendatensätzen

Sie können nach Personendatensätzen in der **Personensuche** Ansicht suchen. Um nach Personen zu suchen, geben Sie Ihre Suchbegriffe in das Feld ein und klicken Sie auf **Suchen**. Das Suchfeld für Personen durchsucht diese Felder: Stichwort (Name, E-Mail, Identifikator), Barcode, Nachname oder Kennung. Vorname oder bevorzugter Vorname können als Name im Stichwortfeld verwendet werden. 

Sie können auch nach Personendatensätzen suchen, indem Sie einen der Filter in der **Personensuche** Ansicht auswählen. Zusätzlich können Sie die Filter nach einer Suche anwenden, um Ihre Ergebnisse zu begrenzen. Siehe die Abschnitte unten für mehr Informationen über die Filter.

### Status

Im **Personen Suchen** Ansicht, falls nötig, das **Status** Akkordeon erweitern und alle passenden Filter auswählen:

-   **Aktiv.** Personen mit dem Status Aktiv.

-   **Inaktiv.** Person mit dem Status Inaktiv.

### Benutzer-in Gruppe

Um Personen nach ihrer Benutzer/-innengruppe zu filtern, erweitern Sie in der **Suchen**-Ansicht bei Bedarf das Akkordeon **Benutzer-innengruppe** und wählen Sie eine der aufgelisteten Optionen aus. 

Benutzer-innengruppen werden in [Einstellungen \> Personen \> Benutzer-innengruppen](../settings/settings\_users/settings\_users/#settings--users--patron-groups) konfiguriert.

### Tags

Tags müssen in den [Einstellungen > Tags](../settings/settings\_tags/settings\_tags/) aktiviert sein, um als Filter zu erscheinen. Um nach Datensätzen von Personen zu suchen, die mit bestimmten Tags versehen sind, folgen Sie diesen Schritten:

1.  In der **Personen suchen** Ansicht, erweitern Sie das **Tags** Akkordeon, falls erforderlich. 

2.  Wählen Sie die Tag(s) aus der Dropdown-Liste aus. Die Suchergebnisse erscheinen in der Ansicht der Suchergebnisse für Personen. 

## Datensatz einer Person anzeigen

Sobald Sie einen Personendatensatz suchen, erscheint die folgende Information in der **Suchergebnisse für Personen** Ansicht:

-   **Name.** Name der Person. *Nachname, Vorname* oder *Nachname, bevorzugter Vorname (Vorname)*

-   **Aktiv.** Der Status der Person.

-   **Barcode.** Die Barcode-Nummer der Person.

-   **Benutzer-innengruppe.** Die Gruppe, der die Person angehört.

-   **Kennung.** Die Kennung der Person.

-   **E-Mail.** Die E-Mail-Adresse der Person.

In der **Personen Suchergebnisse** Ansicht, klicken Sie auf einen Datensatz, um ihn anzusehen. Die Personen Datensatz Ansicht zeigt zusätzliche Informationen über den Datensatz an. Siehe die Abschnitte unten für mehr Informationen über die Akkordeons, die im Datensatz erscheinen.

### Informationen für Personen

Für Informationen zu den im Abschnitt Personeninformationen angezeigten Feldern, siehe [Erstellen eines Personendatensatzes > Personeninformationen](#user-information). 

### Kontosperren

Im Bereich Kontosperren können Sie alle Sperren im Datensatz der Person einsehen und manuelle Sperren erstellen. Für mehr Informationen über manuelle Sperren, siehe [Eine manuelle Kontosperre erstellen](#creating-a-manual-patron-block).

Kontosperren werden in einem Tabellenformat angezeigt, wobei die neueste Sperre zuerst aufgeführt ist.

### Erweiterte Informationen

Für Informationen über die in dem Abschnitt Erweiterte Informationen angezeigten Felder, siehe [Erstellen Sie einen Personendatensatz \> Erweiterte Informationen](#extended-information). 

### Kontaktinformationen

Für Informationen zu den im Abschnitt Kontaktdaten angezeigten Feldern, siehe [Erstellen eines Datensatzes für eine Person \> Kontaktdaten](#contact-information).

### Benutzerdefinierte Felder

Benutzerdefinierte Felder werden von Ihrer Institution konfiguriert und ermöglichen zusätzliche Informationen im Benutzerdatensatz. Für mehr Informationen über benutzerdefinierte Felder siehe [Einstellungen \> Personen \> Benutzerdefinierte Felder](../settings/settings\_users/settings\_users/#settings--users--custom-fields). 

### Vollmachten

Der Vollmachten-Bereich zeigt alle Bevollmächtigten oder Sponsoren an, die mit dem Datensatz der Person verknüpft sind. Siehe [Einen Bevollmächtigten zu einem Personendatensatz hinzufügen](#adding-a-sponsor-to-a-user-record) oder [Einen Bevollmächtigten zu einem Personendatensatz hinzufügen](#add-a-proxy-to-a-user-record) für mehr Informationen. 

### Forderungen

Der Abschnitt **Gebühren/Strafen** zeigt die Anzahl der *offenen, geschlossenen, ausgesetzten angeblich zurückgegebenen* und *erstatteten Gebühren/Strafen* an. Für einen Überblick über **Gebühren/Strafen**, siehe [Zusätzliche Themen > Gebühren und Strafen](..access/additional-topics/feesfines/feesfines/).

Um zusätzliche Details über die Gebühren/Strafen der Person zu sehen, erweitern Sie das **Gebühren/Strafen** Akkordeon und klicken Sie auf **offene Gebühren/Strafen** oder **geschlossene Gebühren/Strafen**. 

Um alle Gebühren/Strafen zu sehen, klicken Sie auf **Alle Gebühren/Strafen anzeigen**. 

Sie können auch manuelle Gebühren/Strafen im Abschnitt **Gebühren/Strafen** erstellen. Für mehr Informationen über manuelle Gebühren/Strafen, siehe [Hinweise zu manuellen Gebühren/Strafen](#creating-a-manual-feefine). 

### Ausleihen

Der Abschnitt Ausleihen zeigt die Anzahl der *offenen Ausleihen* und *geschlossenen Ausleihen* auf einem Datensatz eines Benutzers an.

Eine Person hat eine offene Ausleihe, wenn sie ein Exemplar ausgeliehen hat und das Exemplar noch nicht zurückgegeben wurde. Eine Ausleihe gilt auch als offen, wenn die Person das Exemplar zurückgegeben hat, aber eine Gebühr/Strafe schuldet, oder wenn eine Person sagt, sie hätten ein Exemplar zurückgegeben und die Bibliothek markiert es als "angeblich zurück", während sie die Regale durchsuchen.

Sobald ein Exemplar an die Bibliothek zurückgegeben und die Rückgabe durchgeführt wurde und alle damit verbundenen Gebühren/Strafen geklärt sind, wird die Ausleihe abgeschlossen. Sobald eine Ausleihe abgeschlossen ist, kann sie anonymisiert werden. Um die Anonymisierung der Ausleihe einzurichten, siehe [Einstellungen > Ausleihe > Anonymisierung der Ausleihe](../settings/settings\_circulation/settings\_circulation/#settings--circulation--loan-anonymization). 

Um zusätzliche Details über die offenen Ausleihen oder abgeschlossenen Ausleihen der Person zu sehen, erweitern Sie das **Ausleihen** Akkordeon und klicken Sie auf **offene Ausleihen** oder **abgeschlossene Ausleihen**, jeweils.

### Bestandsanfragen

Der Abschnitt Bestandsanfragen zeigt die Anzahl der *offenen Bestandsanfragen* und *abgeschlossenen Bestandsanfragen* auf einem Datensatz einer Person an.

Eine Anfrage ist offen, wenn eine Person den angefragten Artikel noch nicht erhalten hat. Dies kann der Fall sein, wenn sie darauf warten, dass ein anderer Benutzer den Artikel zurückgibt, oder wenn der Artikel von einem Regal geholt wird (*Offen - Noch nicht erfüllt*, *Offen - Warten auf Lieferung* oder *Offen - in Transport*). Die Anfrage ist auch offen, wenn der Artikel zur angefragten Servicestelle gebracht wurde und der Benutzer zur Abholung benachrichtigt wurde (*Offen - Im Abholregal*).

Eine Anfrage wird geschlossen, wenn die Person das Exemplar abholt (*Geschlossen - erfüllt*). Sie wird auch geschlossen, wenn die Person oder das Bibliothekspersonal ihre Bestandsanfrage vor der Abholung abbricht (*Geschlossen - abgebrochen*), wenn die Person das Exemplar nicht vor Ablauf der Vormerkung abgeholt hat (Geschlossen - Abholung abgelaufen), oder wenn die Bibliothek die Anfrage nicht erfüllen konnte, bevor die Anfrage selbst abgelaufen ist (*Geschlossen - nicht erfüllt*).

Um zusätzliche Details zu den offenen oder geschlossenen Bestandsanfragen der Personen zu sehen, erweitern Sie das **Bestandsanfragen** Akkordeon und klicken Sie auf **offene Bestandsanfragen** oder **geschlossene Bestandsanfragen**.

Sie können Bestandsanfragen für die Person im Personendatensatz oder in der **Bestandsanfragen**-App erstellen. Klicken Sie auf die Schaltfläche **Bestandsanfragen** im Abschnitt **Bestandsanfragen** des Personendatensatzes oder gehen Sie zur **Bestandsanfragen**-App, indem Sie **Bestandsanfragen erstellen** im **Aktionen**-Menü auswählen. Für mehr Informationen über Anfragen, siehe [Anfragen](..access/requests/requests/).

### Systemberechtigungen

Der Abschnitt Systemberechtigungen zeigt alle dem Personendatensatz zugewiesenen Berechtigungen an. Für mehr Informationen siehe [Berechtigungen zuweisen](#assign-permissions) oder [Berechtigungen entfernen](#remove-permissions), je nach Bedarf.

### Servicestellen

Der Abschnitt Servicestellen zeigt alle der Person zugeordneten Servicestellen an, einschließlich der bevorzugten Servicestelle des Benutzers, falls zutreffend. Für mehr Informationen siehe [Eine Servicestelle hinzufügen](#add-a-service-point) oder [Eine Servicestelle entfernen](#remove-a-service-point), je nach Bedarf.

### Bemerkungen

Der Abschnitt Bemerkungen zeigt alle Anmerkungen über die Person an. Für mehr Informationen, siehe [Eine Anmerkung hinzufügen](#add-a-note).

## Bearbeiten Sie einen Personen Datensatz

Um die Abschnitte Benutzerinformationen, erweiterte Informationen oder Kontaktinformationen in einem Datensatz zu bearbeiten, folgen Sie diesen Schritten: 

1.  [Finden Sie den Datensatz der Person](#search-for-user-a-record), den Sie bearbeiten möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Aktionen \> Bearbeiten**.

3. Im **Bearbeiten** Fenster, bearbeiten Sie die entsprechenden Informationen in den Abschnitten [Personeninformationen](#user-information), [Erweiterte Informationen](#extended-information) oder [Kontaktinformationen](#contact-information).

4.  Klicken Sie auf **Speichern & Schließen**. Der Personendatensatz wird aktualisiert.

### Ein Ablaufdatum bearbeiten

Um ein **Ablaufdatum** in einem vorhandenen Personendatensatz zu bearbeiten (oder zurückzusetzen):

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), den Sie bearbeiten möchten und wählen Sie ihn aus.

2.  Wählen Sie den Personendatensatz aus der **Suchergebnisse für Personen** Liste aus. Klicken Sie auf **Aktionen \> Bearbeiten**.

- Passen Sie das Ablaufdatum an, indem Sie das neue Datum im Feld **Ablaufdatum** im Format JJJJ-MM-TT eingeben. Oder klicken Sie auf das Symbol **Kalender** im Feld **Ablaufdatum**, um ein Datum auszuwählen. 
- Setzen Sie das Datum auf das Standardablaufdatum für die zugewiesene Personengruppe zurück, indem Sie auf die **Re-Set** Schaltfläche im Feld **Ablaufdatum** klicken.
- Löschen Sie das Ablaufdatum, indem Sie auf das **x** im Feld **Ablaufdatum** klicken.

3.  Klicken Sie auf **Speichern & Schließen**.

### Ändern Sie den Status einer Person

Der Status einer Person kann zwischen Aktiv und Inaktiv geändert werden, abhängig von Änderungen in ihrem Beschäftigungsstatus oder Einschreibungsstatus. 

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), den Sie bearbeiten möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, im Abschnitt **Personeninformationen**, in der Dropdown-Liste **Status**, wählen Sie **Aktiv** oder **Inaktiv**.

4.  Klicken Sie auf **Speichern & Schließen**. 

### Eine E-Mail zum Zurücksetzen des Passworts senden

Sobald ein Personendatensatz erstellt wurde, kann ein Link zum Zurücksetzen des Passworts an den Benutzer gemailt werden. Um einen Link zum Zurücksetzen des Passworts zu senden:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), für die Sie eine E-Mail zum Zurücksetzen des Passworts senden möchten, und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, in den **Erweiterten Informationen**, klicken Sie auf den **Passwort-Reset-E-Mail senden** verknüpfen unter **Folio-Passwort**. Die Passwort-Reset-E-Mail wird an die in den **Kontaktinformationen** der Person angegebene E-Mail-Adresse gesendet.

4. Optional: Im Pop-up-Fenster **Passwort zurücksetzen E-Mail gesendet**, klicken Sie auf **Verknüpfung kopieren**, um den Link zum Zurücksetzen des Passworts zu kopieren und den Link manuell in einer anderen E-Mail-Anwendung an die Person zu senden.

5. Klicken Sie auf das **X**, um das Pop-up-Fenster zu schließen.

### Hinzufügen einer Vollmacht

Ein **Bevollmächtigte Person** ist eine Person, die eine andere Person autorisiert, in ihrem Namen Bibliotheksmaterialien auszuleihen. Wenn Sie beispielsweise einem Datensatz von Person Eins einen Sponsor hinzufügen, dann ist Person Eins der Bevollmächtigte und kann im Namen von Person Zwei (dem Sponsor) ausleihen.

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), zu dem Sie einen Bevollmächtigten hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3.  Im **Bearbeiten** Fenster, erweitern Sie das **Stellvertreter/Bevollmächtigte** Akkordeon und klicken Sie auf **Hinzufügen** im Abschnitt **Vollmachten**.

4.  Im **Personen-auswählen** Pop-up-Fenster suchen Sie nach der bevollmächtigten Person und wählen Sie sie aus. 

* Optional: Im Feld **Bevollmächtigte** wählen Sie den **Beziehungsstatus**: **Aktiv** oder **Inaktiv**.

* Optional: Geben Sie ein **Ablaufdatum** ein oder wählen Sie dieses aus. Das Ablaufdatum gibt das Ende der Bevollmächtigten-Beziehung an.

* Optional: Wählen Sie, ob der **Bevollmächtigte Bestandsanfragen für den Vertretenen stellen kann**. Wenn Sie **Ja** auswählen, dann kann der Bevollmächtigte Materialien im Namen des Sponsors anfordern.

* Optional: Wählen Sie aus, an wen Benachrichtigungen aus der Bibliothek in der Dropdown-Liste **Benachrichtigungen gesendet an** gesendet werden: **Bevollmächtigten** oder **Vertretenen**.

5.  Klicken Sie auf **Hinzufügen**.

6.  Klicken Sie auf **Speichern & Schließen**. Der **Bevollmächtigte** wird zum Personendatensatz hinzugefügt.

### Einen Bevollmächtigten hinzufügen

Ein **Bevollmächtigter** ist eine Person, die berechtigt ist, Bibliotheksmaterialien im Namen einer anderen Person auszuleihen. Wenn Sie beispielsweise einem Bevollmächtigten zum Datensatz von Person Eins hinzufügen, dann ist Person Zwei der Bevollmächtigte und kann im Namen von Person Eins (dem Vertretenen) ausleihen.

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), zu dem Sie einen Bevollmächtigten hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie das **Bevollmächtigten/Vertretende** Akkordeon und klicken Sie auf **Hinzufügen** im Bereich **Bevollmächtigte**.

4.  Im **Personensuche** Pop-up-Fenster, suchen Sie nach dem Bevollmächtigten und wählen Sie ihn aus. 

* Optional: In der **Bevollmächtigten**-Box, wählen Sie den **Beziehungsstatus**: **Aktiv** oder **Inaktiv**.

* Optional: Geben Sie ein **Ablaufdatum** ein oder wählen Sie dieses aus. Das Ablaufdatum gibt das Ende der Bevollmächtigten-/Vertretenden-Beziehung an.

* Optional: Wählen Sie, ob der **Bevollmächtigte Bestandsanfragen für den Vertretenen stellen kann**. Wenn Sie **Ja** auswählen, dann kann der Bevollmächtigte Materialien im Namen des Vertretenen anfordern.

* Optional: Wählen Sie in der Dropdown-Liste **Benachrichtigungen gesendet an** aus, an wen Benachrichtigungen aus der Bibliothek gesendet werden: Proxy oder Sponsor.

5.  Klicken Sie auf **Hinzufügen**. 

6.  Klicken Sie auf **Speichern & Schließen**. Der **Bevollmächtigten** wird zum Datensatz der Person hinzugefügt.

### Berechtigungen zuweisen

Das Bibliothekspersonal muss Berechtigungen zugewiesen bekommen, die in ihrem Personendatensatz hinterlegt sind, um mit dem FOLIO-Personal-Interface interagieren zu können. Benutzenden muss für Bibliotheksdienstleistungen wie das Ausleihen von Büchern, das Anfordern von Exemplaren usw. keine Berechtigungen zugewiesen werden. Eine Liste der Berechtigungen und ihrer Definitionen finden Sie im jeweiligen Berechtigungsabschnitt der App in der Dokumentation.

Um einem Personendatensatz Berechtigungen zuzuweisen:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), dem Sie Berechtigungen hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie bei Bedarf das **Systemberechtigungen** Akkordeon. 

4.  Klicken Sie auf **Berechtigung hinzufügen**.

5.  Im Pop-up-Fenster **Berechtigungen auswählen**, suchen Sie nach der Berechtigung oder Berechtigungsgruppe, die Sie der Person zuweisen möchten. 

Optional: Filtern Sie nach **Berechtigungstyp** oder **Berechtigungszuweisungsstatus** in der **Suchen & Filtern** Ansicht.

6.  Wählen Sie das/die Kontrollkästchen neben den Berechtigungen aus, die Sie der Person zuweisen möchten.

7.  Klicken Sie auf **Speichern & schließen**. Die Berechtigungen werden dem Personndatensatz zugewiesen.

8.  Klicken Sie auf **Speichern & schließen**. Der Datensatz der Person wird gespeichert.

### Entfernen Sie zugewiesene Berechtigung(en)

Berechtigungen können entweder einzeln oder alle auf einmal mit einem Klick aus einem Datensatz einer Person entfernt werden.

Zugewiesene Berechtigungen entfernen: 

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), für die Sie die Berechtigungen entfernen möchten und wählen Sie diesen aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie bei Bedarf das **Systemberechtigungen** Akkordeon. 

4. Klicken Sie auf das "x" neben der/den einzelnen Berechtigung(en), die Sie entfernen möchten. Die Berechtigung(en) werden aus dem Datensatz der Person entfernt.

5.  Klicken Sie auf **Speichern & schließen**. Der Datensatz der Person wird gespeichert.

Man kann Berechtigungen auch entfernen, indem man eine modifizierte Version des Vorgangs zum Hinzufügen von Berechtigungen befolgt:

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), von dem Sie die Berechtigungen entfernen möchten, und wählen Sie ihn aus.

2.  Im **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie bei Bedarf das **Systemberechtigungen** Akkordeon. 

4.  Klicken Sie auf **Berechtigung hinzufügen**.

5.  Im Pop-up-Fenster **Berechtigungen auswählen**, suchen Sie nach der Berechtigung oder den Berechtigungsgruppen, die Sie von der Person entfernen möchten. 

Optional: Filtern Sie nach **Berechtigungstyp** oder **Berechtigungszuweisungsstatus** in der **Suchen & Filtern** Ansicht.

6.  Deaktivieren Sie das **Kontrollkästchen** neben den Berechtigungen, die Sie der Person entziehen möchten.

7.  Klicken Sie auf **Speichern & schließen**. Die Berechtigung(en) werden aus dem Datensatz der Person entfernt.

8.  Klicken Sie auf **Speichern & schließen**. Der Datensatz der Person wird gespeichert.

Um alle zugewiesenen Berechtigungen mit einem Klick aus dem Datensatz der Person zu entfernen: 

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), von dem Sie die Berechtigungen entfernen möchten, und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie bei Bedarf das **Systemberechtigungen** Akkordeon. 

4.  Klicken Sie auf die Schaltfläche **Alle Berechtigungen aufheben**.

5.  Im Pop-up-Fenster **Alle Berechtigungen aufheben** klicken Sie auf **Ja**, um zu bestätigen, dass Sie alle Berechtigungen aufheben möchten. Alle zugewiesenen Berechtigungen werden aus dem Datensatz der Person entfernt. 

### Eine Servicestelle hinzufügen oder entfernen 

Eine Servicestelle in FOLIO ist eine Einstellung, die Bibliotheken konfigurieren, um Ausleihefunktionen zu unterstützen. Jedes FOLIO-Exemplar muss einen Standort haben und jeder Standort muss eine angehängte Servicestelle haben. Sie müssen mindestens eine Servicestelle einrichten, um Exemplare ein- und auschecken zu können; Benutzenden erlauben, Exemplare anzufordern; Gebühren erheben und einnehmen; und Exemplare zwischen den Standorten Ihrer Bibliothek in Transport bringen. 

Personal, das die Rückgabe-, Ausleihe-, Personen- oder Anfragen-Apps verwendet, muss mindestens eine Servicestelle in seinem Datensatz zugewiesen haben. Servicestellen werden für Ihre Bibliothek in der Einstellungs-App konfiguriert. Siehe [Einstellungen \> Mandant \> Servicestellen](../settings/settings\_tenant/settings\_tenant/#settings--tenant--service-points) für mehr Informationen. 

Um eine oder mehrere Servicestellen zu einem Personendatensatz hinzuzufügen:

1.  [Finden Sie den Personendatensatz](#search-for-user-records), zu dem Sie eine Servicestelle hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie bei Bedarf das **Servicestellen** Akkordeon. 

4.  Klicken Sie auf **Servicestellen hinzufügen**. 

5. Im Pop-up-Fenster **Servicestellen hinzufügen**, wählen Sie die **Kontrollkästchen** neben den Servicestellen aus, die Sie dem Personendatensatz zuweisen möchten.

*  Wenn mehr als eine Servicestelle demPersonendatensatz zugewiesen ist, wählen Sie eine Servicestelle aus dem Dropdown-Menü **Servicestellenpräferenz** aus. Dies ist optional, aber wenn es leer gelassen wird, muss der Benutzer jedes Mal, wenn er sich bei FOLIO anmeldet, die Servicestelle auswählen. 

6.  Klicken Sie auf **Speichern & schließen**. Die Servicestelle(n) werden dem Personendatensatz zugewiesen.

7.  Wählen Sie eine **Servicestelle Präferenz** aus der Dropdown-Liste aus. Wenn Sie **Keine** auswählen, wird die Person aufgefordert, jedes Mal eine Servicestelle auszuwählen, wenn sie sich bei FOLIO anmeldet.

8.  Klicken Sie auf **Speichern & Schließen**. Die Servicestelle(n) werden dem Personendatensatz hinzugefügt.

Um eine oder mehrere Servicestellen aus einem Personendatensatz zu entfernen:

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), von dem Sie eine Servicestelle entfernen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie das **Servicestellen** Akkordeon, falls erforderlich. 

4.  Klicken Sie auf das "x" neben der/den Servicestelle(n), die Sie entfernen möchten. Die Servicestelle(n) werden aus dem Datensatz der Person entfernt.

5. Klicken Sie auf **Speichern & schließen**. Der Persondatensatz wird gespeichert.

Es ist auch möglich, Servicestellen zu entfernen, indem man eine abgewandelte Version des Prozesses zur Hinzufügung verwendet:

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), von dem Sie eine Servicestelle entfernen möchten, und wählen Sie ihn aus.

2.  In der **Personendatensatz** Ansicht, klicken Sie auf **Bearbeiten**.

3. Im **Bearbeiten** Fenster, erweitern Sie das **Servicestellen** Akkordeon, falls erforderlich. 

4.  Klicken Sie auf **Servicestellen hinzufügen**. 

5. Im Pop-up-Fenster **Servicestellen hinzufügen**, deaktivieren Sie die **Kontrollkästchen** neben den Servicestellen, die Sie aus dem Datensatz der Person entfernen möchten.

6.  Klicken Sie auf **Speichern & Schließen**. Die Servicestelle(n) werden aus dem Datensatz der Person entfernt.

### Ein Tag hinzufügen oder entfernen

Beachten Sie, dass Tags für Ihre FOLIO-Instanz aktiviert sein müssen, um Tags in der Personen-App zu verwenden. Siehe [Einstellungen > Tags](../settings/settings\_tags/settings\_tags/) für mehr Informationen. 

Um einem Personendatensatz ein Tag hinzuzufügen:

1.  [Finden Sie den Personendatensatz](#search-for-a-user-record), zu dem Sie ein Tag hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf das **Tag-Symbol** neben der **Aktionen** Schaltfläche.

3. Wenn Sie ein vorhandenes Tag verwenden möchten, wählen Sie es aus der Dropdown-Liste aus. Wenn Sie ein neues Tag erstellen möchten, geben Sie das Tag in das Feld ein und wählen Sie **Tag hinzufügen für** den neuen Tag-Namen in der Dropdown-Liste aus.

4. Klicken Sie auf das **X** auf der **Tags**-Ansicht, um die Ansicht zu schließen und das Tag zu speichern. Die Feldkennung aktualisiert sich auf die Anzahl der auf den Datensatz der Person angewendeten Tags.

Um ein Tag von einem Personendatensatz zu entfernen:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), dem Sie ein Tag hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, klicken Sie auf das **Tag-Symbol** neben der **Aktionen** Schaltfläche.

3.  Klicken Sie auf das **X** neben dem zu entfernenden Tag.  

4.  Klicken Sie auf das **X** in der **Tags**-Ansicht, um die Ansicht zu schließen. Die Feldkennung wird auf die Anzahl der auf den Datensatz der Person angewendeten Tags aktualisiert.

### Eine manuelle Kontosperre erstellen

Kontosperren ermöglichen es Bibliotheken, einer Person manuell das Ausleihen, Verlängern und/oder Anfordern von Materialien zu verhindern, bis bestimmte Probleme gelöst sind. Personen mit entsprechenden Berechtigungen können manuelle Sperren in einem Datensatz einer Person aktualisieren, um Informationen zur Sperre, Aktionen oder die Sperre selbst zu entfernen. Die Sperre wird prominent im Datensatz der Person angezeigt, damit das Personal weiß, dass eine Person gesperrt ist und warum. Wenn ein Ablaufdatum für die Kontosperre angegeben ist, wird die Sperre an diesem Datum automatisch entfernt.

Eine Kontosperre kann zu einem Datensatz einer Person hinzugefügt werden, indem entweder eine Kontosperre-Vorlage ausgewählt oder eine Kontosperre erstellt wird. 

Um eine Kontosperre mit einer Vorlage für Kontosperren zu erstellen, folgen Sie diesen Schritten:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), den Sie sperren möchten, und wählen Sie ihn aus. 

2. In der **Datensatz** Ansicht, erweitern Sie das **Kontosperre** Akkordeon, falls nötig. 

3. Klicken Sie auf **Sperre erstellen**.  

4. Wählen Sie eine Kontosperre-Vorlage aus dem Menü **Vorlagenname** aus. Die Vorlagenwerte werden auf die Sperre angewendet.

5. Fügen Sie alle zusätzlichen Informationen zur Sperre hinzu und wählen Sie bei Bedarf ein Ablaufdatum aus.

6. Klicken Sie auf **Speichern & schließen.** Die Sperre wird gespeichert und zum Personendatensatz hinzugefügt.

Um eine Kontosperre zu erstellen und sie zu einem Datensatz einer Person hinzuzufügen, folgen Sie diesen Schritten:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record), den Sie sperren möchten, und wählen Sie ihn aus.

2. In der **Datensatz** Ansicht, erweitern Sie das **Kontosperren** Akkordeon.

3. Klicken Sie auf **Sperre erstellen**.  

4. Im Fenster **Neue Sperre** erweitern Sie das Akkordeon **Sperrinformationen** bei Bedarf. Geben Sie eine **Anzeige Beschreibung** ein. Dies ist die Beschreibung, die im Personendatensatz und in Pop-up-Fenstern angezeigt wird, die erscheinen, wenn das Personal versucht, Exemplare auszuleihen, zu verlängern oder im Namen der Person Bestandsanfragen zu stellen, abhängig von ihrer Sperre.

5. Optional: Geben Sie **Nur für Personal Informationen** ein.

6. Optional: Geben Sie eine **Nachricht an die Person** ein.

7. Optional: Geben Sie ein **Ablaufdatum** ein, an dem die Sperre abläuft.

8. Standardmäßig sind alle **Sperraktionen** ausgewählt. Dies sind die Aktionen, die der Benutzer aufgrund der Sperre nicht durchführen kann. Um einige der Aktionen zu erlauben, deaktivieren Sie das **Kontrollkästchen** neben **Ausleihen**, **Verlängerungen** oder **Bestandsanfragen**.

9.  Klicken Sie auf **Speichern & schließen**. Der Block wird gespeichert und zum Personendatensatz hinzugefügt.

### Eine Kontosperre bearbeiten

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record) mit der Sperre, den Sie bearbeiten möchten, und wählen Sie ihn aus.

2.  In der **Personendatensatz** Ansicht, erweitern Sie das **Kontosperre** Akkordeon.

3.  In der **Sperrentabelle**, wählen Sie die **Sperre** aus, die Sie bearbeiten möchten.

4.  Im **Persoensperre** Fenster, nehmen Sie Ihre Änderungen vor.

5.  Klicken Sie auf **Speichern & Schließen**. Die Kontosperre wird aktualisiert.

### Eine Kontosperre entfernen

Kontosperren mit Ablaufdaten werden an diesem Datum automatisch entfernt. 

Um eine Kontosperre ohne zugewiesenes Ablaufdatum zu entfernen, folgen Sie diesen Schritten:

1.  [Finden Sie den Datensatz der Person](#search-for-a-user-record) mit der Sperre, den Sie bearbeiten möchten, und wählen Sie ihn aus.

2.  In der **Datensatz** Ansicht, erweitern Sie das **Kontosperre** Akkordeon.

3.  Wählen Sie die Sperre aus, die Sie entfernen möchten

4.  Im Fenster des Personendatensatzes, klicken Sie auf **Löschen**.

5.  Im Pop-up-Fenster **Kontosperre löschen?** klicken Sie auf **Löschen**. Die Kontosperre wird entfernt.

### Eine Bestandsanfrage erstellen

Bestandsanfragen können auf drei Arten erstellt werden: In der Bestandsanfragen-App; im Personendatensatz in der Personen-App; oder vom Exemplardatensatz in der Katalog-App. Für Informationen zum Erstellen von Bestandsanfragen, siehe [Eine Bestandsanfrage erstellen](../access/requests/requests/#creating-a-request)

### Eine Bemerkung hinzufügen 

Um eine Bemerkung zu einem Personendatensatz hinzuzufügen: 

1.  [Finden Sie den Personendatensatz](#search-for-user-records), zu dem Sie eine Bemerkung hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personendatensatz** Ansicht, erweitern Sie das **Bemerkungen** Akkordeon, falls erforderlich. 

3.  Klicken Sie auf **Neu**.

4. Im Fenster **Neue Bemerkung**, wählen Sie den **Bemerkungstyp** aus der Dropdown-Liste aus. Bemerkungstypen werden in der Einstellungs-App erstellt. Für mehr Informationen über Bemerkungstypen, siehe [Einstellungen > Bemerkung > Allgemein](../settings/settings\_notes/settings\_notes/#settings--notes--general).

5. Geben Sie einen **Bemerkungstitel** in das Feld ein.

6. Optional: Geben Sie alle **Details** zur Bemerkung in das Feld ein.

7. Wenn diese Notiz als Pop-up angezeigt werden soll, wann immer der Personendatensatz in der Ausleihe und/oder Personen App geöffnet wird, markieren Sie das Kästchen **Ausleihe App** und/oder das Kästchen **Personen App** unter der Option **Bemerkung als Pop-up anzeigen**. 

8.  Klicken Sie auf **Speichern & schließen**. Die Bemerkung wird gespeichert.

## Löschen eines Personendatensatzes in der Personenoberfläche 

Ein Datensatz einer Person kann nur gelöscht werden, wenn die Person keine offenen Transaktionen hat. Um einen Datensatz einer Person zu löschen, prüfen Sie zuerst auf offene Transaktionen. Sobald bestätigt ist, dass die Person keine offenen Transaktionen hat, kann der Datensatz der Person gelöscht werden.

Befolgen Sie diese Schritte, um offene Transaktionen zu prüfen und einen Benutzerdatensatz in der Personenoberfläche zu löschen:

1. [Finden Sie den Datensatz der Person](#search-for-a-user-record), für die Sie offene Transaktionen prüfen möchten, und wählen Sie ihn aus.
2. Im **Aktionen**-Menü, wählen Sie **Nach offenen Transaktionen suchen/Person löschen** aus. 
3. Wenn für diese Person keine offenen Transaktionen vorhanden sind, erscheint die Meldung *Keine offenen Transaktionen für die Person (Nachname, Vorname). Sind Sie sicher, dass Sie diese Person löschen möchten?* im Fenster **Überprüfen auf offene Transaktionen/Person löschen**. 
4. Klicken Sie auf **Ja**, um den Datensatz der Person zu löschen. Eine *Person (Nachname, Vorname) erfolgreich gelöscht* Nachricht bestätigt die Löschung des Personendatensatzes. 
5. Oder klicken Sie auf **Nein**, um das Löschen abzubrechen und zum Personendatensatz zurückzukehren. 
6. Wenn eine oder mehrere offene Transaktionen für die Person vorliegen, wird die Nachricht *Person (Nachname, Vorname) hat die folgenden offenen Transaktionen. Bitte klären Sie die Transaktionen, um mit dem Löschen dieser Person fortzufahren.* Klicken Sie auf **OK**, um zum Datensatz der Person zurückzukehren. 

Wenn die gelöschte Person Berechtigungen zum Bearbeiten von Datensätzen hatte, wird die Quelle in der Metadatenhistorie als "Unbekannte Person" aufgeführt.

## Erstellen Sie einen Bericht

### Bericht überfällige Ausleihen

Der Bericht über überfällige Ausleihen ist eine durch Kommas getrennte Werte (CSV) Datei, die alle Personen mit überfälligen Medien anzeigt.

Einen Bericht über überfällige Ausleihen erstellen: 

1. In der **Personen Suchergebnisse** Ansicht, klicken Sie auf **Aktionen \> Überfällige Ausleihen Bericht (CSV)**. 
2. Je nach Ihrem Browser und dessen Konfigurationen erscheint eine Meldung *Export in Bearbeitung* und die Datei wird automatisch heruntergeladen oder Sie werden aufgefordert, sie zu speichern. Wenn es keine überfälligen Ausleihen zu melden gibt, erscheint eine Meldung *Keine Exemplare gefunden* und es wird keine Datei generiert. 

### Angeblich zurückgegeben Bericht

Der Bericht über angeblich zurückgegebene Materialien ist eine kommagetrennte Werte (CSV) Datei, die alle Personen mit angeblich zurückgegebenen Medien anzeigt.

So erstellen Sie einen Bericht über angeblich zurückgegebene Medien:

1. In der **Personen Suchergebnisse** Ansicht, klicken Sie auf **Aktionen \> Angeblich zurückgegeben Bericht (CSV)**.
2. Je nach Ihrem Browser und dessen Konfigurationen erscheint eine Meldung *Export in Bearbeitung* und die Datei wird automatisch heruntergeladen oder Sie werden aufgefordert, sie zu speichern. Wenn es keine angeblich zurückgegebenen Exemplare zu melden gibt, erscheint eine Meldung *Keine Exemplare gefunden* und es wird keine Datei generiert.

### Kassenabschlussbericht

Der Kassenabschlussbericht wird vom Bibliothekspersonal verwendet, um ihre Kasse am Ende einer Schicht auszugleichen. Der Kassenabschlussbericht zeigt die erhaltenen Zahlungsarten (Bargeld, Scheck, Kreditkarte und andere von der Bibliothekseinheit zugelassene Zahlungsarten) für Gebühren und Mahnungen und identifiziert den Forderungseigentümer/-in, damit die entsprechende Bibliothekseinheit die Zahlung erhält. Kassenabschlussbericht steht zum Download als Datei mit durch Kommas getrennten Werten (CSV) und/oder im druckbaren Dokumentenformat (PDF) zur Verfügung.

Einen Kassenabschlussbericht erstellen: 

1. In der **Personen Suchergebnisse** Ansicht, klicken Sie auf **Aktionen \>Kassenabschlussbericht (CSV, PDF)**. 
2. In dem Modal **Kassenabgleichsbericht**, geben Sie ein **Startdatum** (erforderlich) und ein **Enddatum** ein. Wählen Sie **Servicestelle** und **Quellen** (optional) aus. 
3. Wählen Sie das **Berichtsformat** aus. Sie können *CSV*, *PDF (nur Lesen)* oder *Beides* auswählen.
4. Klicken Sie auf **Speichern & Schließen**.
5. Je nach Ihrem Browser und dessen Konfigurationen erscheint eine Meldung *Export in Bearbeitung* und die Datei wird automatisch heruntergeladen oder Sie werden aufgefordert, sie zu speichern. Wenn keine Transaktionen zu berichten sind, erscheint eine Meldung *Keine Exemplare gefunden* und es wird keine Datei generiert.

### Detailbericht zu Finanztransaktionen

Der Detailbericht zu Finanztransaktionen ermöglicht es Bibliotheken, Transaktionen in einem bestimmten Zeitraum auf der Ebene des Forderungseigentümers/-in zu überprüfen. 

Einen Detailbericht zu Finanztransaktionen erstellen: 

1. In der **Personen Suchergebnisse** Ansicht, klicken Sie auf **Aktionen \>Finanztransaktionsdetail Bericht (CSV)**. 
2. Im Modal **Detailbericht zu Finanztransaktionen** geben Sie einen Datumsbereich an, indem Sie ein **Startdatum** und ein **Enddatum** eingeben. Wählen Sie den **Forderungseigentümer/-in** aus. Wählen Sie die **zugehörigen Servicestellen** aus (optional). 
3. Klicken Sie auf **Speichern & Schließen**.
4. Je nach Ihrem Browser und dessen Konfigurationen erscheint eine Meldung *Export in Bearbeitung* und die Datei wird automatisch heruntergeladen oder Sie werden aufgefordert, sie zu speichern. Wenn keine Transaktionen zu berichten sind, erscheint eine Meldung *Keine Exemplare gefunden* und es wird keine Datei generiert.

### Bericht über manuell zu bearbeitende Erstattungen (CSV)

Der Bericht über manuell zu bearbeitende Rückerstattungen ist ein Bericht, der der Bibliotheksverwaltung eine Liste der Benutzenden zur Verfügung stellt, die eine Rückerstattung benötigen. Er steht als kommagetrennte Werte (CSV) Datei zum Download zur Verfügung. 

Um einen Bericht über manuell zu bearbeitende Erstattungen zu erstellen: 

1. In der **Personen Suchergebnisse** Ansicht, klicken Sie auf **Aktionen \>Bericht über manuell zu bearbeitende Erstattungen (CSV)**. 
2. In dem Modal **Rückerstattungen zur manuellen Verarbeitung**, geben Sie einen Datumsbereich an, indem Sie ein **Startdatum** und ein **Enddatum** eingeben. Wählen Sie den **Forderungseigentümer/-in** aus.
3.  Klicken Sie auf **Speichern & Schließen**.
4. Je nach Ihrem Browser und dessen Konfigurationen erscheint eine Meldung *Export in Bearbeitung* und die Datei wird automatisch heruntergeladen oder Sie werden aufgefordert, sie zu speichern. Wenn keine Rückerstattungen manuell zu bearbeiten sind, erscheint eine Meldung *Keine Exemplare gefunden* und es wird keine Datei generiert. 

## Verwalten von Ausleihen und Gebühren/Strafen für Personen

Vom Ausleihe-Bereich in einem Datensatz einer Person kann ein FOLIO-Benutzer mit entsprechenden Berechtigungen eine Ausleihe für eine Person verlängern; das Fälligkeitsdatum ändern; das Exemplar als angeblich zurück markieren; oder das Exemplar als verloren erklären. Für mehr Informationen über Ausleihen, siehe [Zusätzliche Themen \> Ausleihen](../access/additional-topics/loans/loans/).

FOLIO Personen mit entsprechenden Berechtigungen können Gebühren/Strafen auf Personen Konten verwalten. Dies beinhaltet das Anzeigen von Gebühren-/Strafeninformationen, das Erstellen manueller Gebühren, das Akzeptieren von Zahlungen, das Erlassen einer Strafe, das Erstatten einer Strafe und die Stornierung einer Strafe. Für mehr Informationen über Gebühren/Strafen, siehe [Zusätzliche Themen \> Gebühren und Strafen](../access/additional-topics/feesfines/feesfines/). 

### Eine Ausleihe verlängern

Um eine oder mehrere Ausleihen für eine Person zu verlängern:

1. Erweitern Sie in der Personendatensatz-Ansicht das **Ausleihen** Akkordeon, falls erforderlich. 

2. Klicken Sie auf **Aktuelle Ausleihen**. 

3. Verwenden Sie die Kontrollkästchen links im **Ausleihe** Fenster, um die entsprechende(n) Ausleihe(n) auszuwählen.

4. Klicken Sie auf die Schaltfläche **Verlängern**, die sich in der oberen rechten Ecke des Fensters **Ausleihen** befindet.

Wenn die Verlängerung erfolgreich war, sehen Sie eine grüne Erfolgsmeldung in der unteren rechten Ecke. Das neue Fälligkeitsdatum kann früher sein als erwartet, wenn das normale Fälligkeitsdatum nach Ablauf des Kontos einer Person wäre.

Wenn die Verlängerung nicht erfolgreich war, erscheint eine Pop-up-Nachricht. Wenn Sie die richtigen Berechtigungen haben, können Sie auf **Umgehen** in dem Pop-up-Fenster klicken, um den Fehler zu umgehen und die Ausleihe zu verlängern.

Alternativ können Sie eine Ausleihe verlängern, indem Sie in der Spalte **Aktionen** auf **Verlängern** klicken. 

### Das Fälligkeitsdatum ändern

Um das Fälligkeitsdatum für eine oder mehrere Ausleihen für eine Person zu ändern:

1. Öffnen Sie in der Ansicht des Personendatensatzes bei Bedarf das Akkordeon **Ausleihen**. 

2. Klicken Sie auf **aktuelle Ausleihen**.

3. Wählen Sie die Kontrollkästchen links im **Ausleihe** Fenster aus, um die entsprechende(n) Ausleihe(n) auszuwählen.

4. Klicken Sie auf die Schaltfläche **Fälligkeitsdatum ändern**, die sich in der oberen rechten Ecke des Fensters **Ausleihen** befindet. 

5. In dem erscheinenden Pop-up-Fenster geben Sie ein neues Fälligkeitsdatum und eine Uhrzeit ein oder wählen Sie eines aus dem Kalender-Dropdown aus.

3.  Klicken Sie auf **Speichern & Schließen**.

Beachten Sie, dass Sie, wenn Sie die Berechtigung haben, das Fälligkeitsdatum einer Ausleihe zu ändern, das Fälligkeitsdatum/Zeitpunkt auf einen in der Vergangenheit liegenden Zeitpunkt ändern können; FOLIO wird Ihnen eine Warnmeldung geben, aber die Änderung zulassen.

### Markieren Sie ein Exemplar als angeblich zurück

Gelegentlich informieren Personen Bibliotheken darüber, dass sie Exemplare zurückgegeben haben, die noch als an sie ausgeliehen gelistet sind. Die Bibliothek hat die Möglichkeit, das Exemplar als "angeblich zurück" zu markieren. Dies setzt alle damit verbundenen Gebühren aus, während Bibliotheken Workflows durchführen können, um das Exemplar in ihren Regalen zu suchen.

Um ein Exemplar als angeblich zurück zu markieren:

1. Erweitern Sie in der Personendatensatzansicht bei Bedarf das **Ausleihen** Akkordeon.

2. Verwenden Sie die Kontrollkästchen links im **Ausleihe** Fenster, um die entsprechende(n) Ausleihe(n) auszuwählen.

3. Klicken Sie auf die Schaltfläche **Angeblich zurückgegeben**, die sich in der oberen rechten Ecke des Fensters **Ausleihen** befindet.

4. In dem aufpoppenden Fenster, geben Sie zusätzliche Informationen über die Behauptung der Person ein. 

5. Klicken Sie auf **Bestätigen**.

Die Ausleihe bleibt in der Liste der offenen Ausleihen der Person, aber der Exemplarstatus zeigt an, dass das Exemplar angeblich zurückgegeben wurde.

Wenn die Bibliothek das angeblich zurückgegebene Exemplar nicht finden kann, muss sie entscheiden, ob sie der Person das Exemplar in Rechnung stellt oder das Exemplar als vermisst markiert, ohne Gebühren zu erheben. In FOLIO wird diese Aktion als Klärung eines Anspruchs bezeichnet.

Forderung auflösen:

1. Klicken Sie auf die entsprechende Ausleihe, um das Fenster *Ausleihe Details* zu öffnen.

2. Klicken Sie auf die Schaltfläche, die mit **Anspruch klären** in der obersten Reihe gekennzeichnet ist.

3. Wenn Sie der Person für das Exemplar in Rechnung stellen möchten, wählen Sie **Für verloren erklärt**. Wenn Sie der Person das Exemplar nicht in Rechnung stellen möchten, wählen Sie **Als vermisst markieren**.

4. In dem aufpoppenden Fenster, das erscheint, zeigt FOLIO eine Nachricht an, um die Aktion zu bestätigen, die Sie durchführen möchten. Geben Sie zusätzliche Informationen über die Behauptung der Person ein (erforderlich).

5. Klicken Sie auf **Bestätigen**.

Wenn Sie sich entscheiden, das Exemplar als verloren zu melden, wird FOLIO die zugehörigen Gebührenrichtlinien für verlorene Exemplare für die Ausleihe prüfen und Gebühren/Strafen gemäß dieser Richtlinie berechnen.

### Markieren Sie ein Exemplar als für verloren erklärt

FOLIO bietet zwei Möglichkeiten an, um zu zeigen, dass ein Exemplar ausgeliehen und nicht zurückgegeben wurde - „Verloren erklärt“ und „Für verloren erklärt“. Verloren erklärt ist ein automatisierter Status, den FOLIO einem Exemplar gibt, wenn das Exemplar nicht bis zum in der Ausleihrichtlinie für verlorene Exemplare angegebenen Datum zurückgegeben wird. Für verloren erklärt ist ein manueller Status, den das Bibliothekspersonal verwenden kann, wenn eine Person der Bibliothek mitteilt, dass sie das Exemplar nicht zurückgeben können, weil sie es nicht mehr finden oder weil es versehentlich beschädigt wurde.

Das Bibliothekspersonal kann nur eine Ausleihe gleichzeitig für verloren erklären.

Um eine Ausleihe als für verloren erklärt zu markieren:

1. Klicken Sie auf die entsprechende Ausleihe, um das Fenster *Ausleihe Details* zu öffnen.

2. Klicken Sie oben im Fenster auf *Für verloren erklärt*.

3. In dem aufpoppenden Fenster, das erscheint, geben Sie zusätzliche Informationen über die Umstände der Ausleihe ein (erforderlich)

4. Klicken Sie auf **Bestätigen**.

Wenn ein Exemplar für verloren erklärt wird, prüft FOLIO die zugehörigen Gebührenrichtlinien für verlorene Exemplare für die Ausleihe und erhebt Gebühren/Strafen, wie in dieser Richtlinie konfiguriert.

### Eine manuelle Gebühr/Strafe erstellen

Beachten Sie, dass Ihre Bibliothek die Gebühren-/Straf-Einstellungen konfigurieren muss, bevor Gebühren/Strafen an Personen erhoben werden können. Siehe [Einstellungen > Personen > Eigentümer](../settings/settings\_users/settings\_users/#settings--users--owners) und [Einstellungen > Personen> Manuelle Gebühren](../settings/settings\_users/settings\_users/#settings--users--manual-charges) für mehr Informationen.

1.  [Finden Sie den Personendatensatz](#searching-for-user-records), zu dem Sie eine Gebühr/Strafe hinzufügen möchten und wählen Sie ihn aus.

2.  In der **Personendatensatz** Ansicht, erweitern Sie das **Gebühren/Strafen** Akkordeon, falls erforderlich.

3.  Klicken Sie auf **Forderung erstellen**.

4. Im Fenster **Neue Forderung**, wählen Sie den/die **Forderungseigentümer/-in** aus.

5.  Wählen Sie den **Forderungstyp**.

6.  In dem Feld **Gebühr/Strafbetrag** können Sie eine von drei Dingen tun:

Behalten Sie den Standardbetrag für Gebühren/Strafen bei, wenn einer für den Gebühren-/Strafentyp ausgefüllt ist.

Passen Sie den Standardgebühren-/Gebührenbetrag an, wenn er für die Gebühren-/Gebührenart eingetragen ist.

Geben Sie einen Gebühr-/Strafbetrag an, wenn keiner angezeigt wird.

7. Optional: Um die Gebühr/Strafe mit einem Exemplar zu verknüpfen, scannen Sie den Barcode des Exemplars in das Feld **Exemplarinformationen** ein und klicken Sie auf **Enter**.

8. Optional: Geben Sie in das Feld **Zusätzliche Informationen für das Personal** ein.

9. Klicken Sie auf **Nur Gebühr** um die Gebühr auf den Personendatensatz anzuwenden. Personen mit entsprechenden Berechtigungen können in FOLIO möglicherweise das Bußgeld erstellen und sofortige Zahlung akzeptieren, indem sie auf **Gebühr & jetzt bezahlen** klicken.

10. Klicken Sie entweder auf **Gebühr & jetzt bezahlen** um die Gebühr der Person zu berechnen und die Zahlung zu verarbeiten, oder auf **Nur Gebühr** um die Gebühr nur auf den Datensatz der Person anzuwenden.

### Zahlung einer Gebühr/Strafe akzeptieren

1.  [Finden Sie den Personendatensatz](#searching-for-user-records), für den Sie eine Zahlung für eine Gebühr/Strafe akzeptieren möchten und wählen Sie ihn aus.

2.  In der **Personen Datensatz** Ansicht, erweitern Sie das **Gebühren/Strafen** Akkordeon, falls erforderlich.

3. **(Anzahl der) offenen Gebühren/Strafen** auswählen, um die offenen Strafen der Person einzusehen.

4. Das Modal **Gebühren/Strafen** wird geöffnet. Klicken Sie auf die Gebühr/Strafe, für die Sie eine Zahlung annehmen möchten.

5. Das Modal **Gebühren-/Strafen-Details** öffnet sich. Klicken Sie auf **Aktionen \> Bezahlen**.

6. Das Modal **Gebühr/Strafe zahlen** öffnet sich. Geben Sie den Zahlungsbetrag ein (erforderlich). FOLIO kann vollständige und teilweise Zahlungen verarbeiten. Wenn Sie eine Teilzahlung akzeptieren, berechnet das Modal den verbleibenden Betrag.

7. **Zahlungsart** auswählen (erforderlich).

8. Geben Sie die **Transaktionsinformationen** und die **Zusätzlichen Informationen für das Personal** ein. Das Feld **Zusätzliche Informationen für das Personal** kann erforderlich sein, wenn Ihre Bibliothek diese Option konfiguriert hat.

9. Klicken Sie auf **Bezahlen**, dann auf **Bestätigen**.

Das Modal wird geschlossen und die **Gebühren-/Straf-Details** Seite wird mit der Zahlungsverbuchung aktualisiert. 

Forderungen erstatten

Personal mit entsprechenden Berechtigungen kann eine teilweise oder vollständige Erlassung einer Gebühr/Strafe vornehmen.

1.  [Finden Sie den Personendatensatz](#searching-for-user-records), für den Sie eine Zahlung für eine Gebühr/Strafe akzeptieren möchten, und wählen Sie ihn aus.

2.  In der **Personendatensatz** Ansicht, erweitern Sie das **Gebühren/Strafen** Akkordeon, falls erforderlich.

3. **(Anzahl der) offenen Gebühren/Strafen** auswählen, um die offenen Strafen der Person einzusehen.

4. Das Modal **Gebühren/Strafen** wird geöffnet. Klicken Sie auf die Gebühr/Strafe, die Sie erlassen möchten.

5. Das Modal **Gebühren-/Mahn-Details** öffnet sich. Klicken Sie auf **Aktionen \> Erlassen**.

6. Das Modal **Gebühr/Strafe erlassen** wird geöffnet. Geben Sie den Betrag ein, der erlassen werden soll (erforderlich). Sie können einen Teil oder die gesamte Strafe erlassen. Wenn Sie nur einen Teil der Strafe erlassen, berechnet FOLIO automatisch den verbleibenden Betrag. 

7. Wählen Sie den **Grund für den Verzicht** (erforderlich) aus und geben Sie **Zusätzliche Informationen für das Personal** ein. Das Feld **Zusätzliche Informationen für das Personal** kann erforderlich sein, wenn Ihre Bibliothek diese Option konfiguriert hat.

8. Klicken Sie auf **Verzichten**, dann auf **Bestätigen**.

Das Modal wird geschlossen und die **Gebühren-/Mahn-Details** Seite wird mit der Zahlungsverbuchung aktualisiert.

Forderungen erstatten

Personal mit entsprechenden Berechtigungen kann Forderungen teilweise oder vollständig erstatten. Die Zahlungsart muss Rückerstattungen zulassen. 

1.  [Finden Sie den Datensatz der Person](#searching-for-user-records), dem Sie eine Zahlung erstatten möchten, und klicken Sie darauf.

2.  In der **Personendatensatz** Ansicht, erweitern Sie das **Forderungen** Akkordeon, falls erforderlich.

3. **Alle Forderungen anzeigen** auswählen, um die Forderungen der Person zu sehen.

4. Das Modal **Forderungen** wird geöffnet. Klicken Sie auf die Forderung, für die Sie eine Zahlung erstatten möchten. Sie kann **Offen** oder **Geschlossen** sein.

5. Das Modal **Forderungen-Details** wird geöffnet. Klicken Sie auf **Aktionen \>Rückerstattung**.

6. Das Modal **Rückerstattungsgebühr/-strafe** wird geöffnet. Geben Sie den zu erstattenden Betrag ein (erforderlich). Sie können einen Teil oder den gesamten Strafbetrag erstatten. Wenn Sie nur einen Teil der Strafe erstatten, berechnet FOLIO automatisch den verbleibenden Betrag. 

7. Wählen Sie den **Erstattungsgrund** (erforderlich) aus und geben Sie **Zusätzliche Informationen für das Personal** ein. Das Feld **Zusätzliche Informationen für das Personal** kann erforderlich sein, wenn Ihre Bibliothek diese Option konfiguriert hat.

8. Klicken Sie auf **Rückerstattung**, dann auf **Bestätigen**.

Das Modal wird geschlossen und die **Gebühren-/Straf-Details** Seite wird mit der Zahlungsverbuchung aktualisiert.

### Eine Gebühr/Strafe als Fehler markieren (Gebühr/Strafe stornieren) 

Personal mit entsprechenden Berechtigungen kann eine Gebühr/Strafe als Fehler markieren; dies hat die Wirkung, die Gebühr/Strafe zu stornieren.

Beachten Sie, dass ein Fehler nur auf eine Gebühr in einem **ausstehenden** Zahlungsstatus angewendet werden kann. Die Kennzeichnung einer Gebühr als Fehler ist vorgesehen, wenn die Strafe aufgrund eines Personal- oder Systemfehlers erhoben wird und daher nichts davon bezahlt werden sollte.

1.  [Finden Sie den Datensatz der Person](#searching-for-user-records), bei dem Sie eine Zahlung erstatten möchten, und klicken Sie darauf.

2.  In der **Personen Datensatz** Ansicht, erweitern Sie das **Gebühren/Strafen** Akkordeon, falls erforderlich.

3. **Alle Gebühren/Strafen anzeigen** auswählen, um die Forderungen der Person zu sehen.

4. Das Modal **Gebühren/Strafen** wird geöffnet. Klicken Sie auf die Gebühr/Strafe, für die Sie eine Zahlung erstatten möchten. Sie kann **Offen** oder **Geschlossen** sein.

5. Das Modal **Forderungsdetails** wird geöffnet. Klicken Sie auf **Aktionen \> Fehler**.

6. Das Modal **Forderungen stornieren bestätigen** wird geöffnet. Geben Sie **Zusätzliche Informationen für das Personal** (erforderlich) ein.

7. Klicken Sie auf **Bestätigen**.

Das Modal wird geschlossen und die Seite **Forderungsdetails** wird mit der Stornierungstransaktion aktualisiert.


## Verarbeitung verlorener Exemplare, die tatsächliche Kosten erfordern

Bibliotheken können sich dafür entscheiden, für einige oder alle Gebühren, die sie Personen in Rechnung stellen, den **tatsächlichen Preis** zu verwenden. Bei dem Modell des tatsächlichen Preises überprüfen Bibliotheken jede Ausleihe, nachdem sie als verloren erklärt wurde, um der Person einen spezifischen Betrag für das Exemplar in Rechnung zu stellen, anstatt einen pauschalen Betrag basierend auf der zugehörigen Ausleihrichtlinie.

### Verlorene Exemplare anzeigen, für die tatsächliche Kosten erforderlich sind

In der Personen-App, wählen Sie **Aktionen \> Verlorene Exemplare, die tatsächliche Kosten erfordern.** Eine neue Vollbild-Ansicht wird geöffnet.

### Suchen & filtern nach verlorenen Exemplaren 

Sie können die Gebühren für verlorene Exemplare nach dem Namen der Person oder dem Titel der Instanz suchen.

Sie können Ihre Suchergebnisse filtern nach

-  **Verlusttyp**. Sie können filtern, um nur Ausleihen zu sehen, die als verloren eingestuft wurden, oder nur Ausleihen, die als verloren erklärt wurden.

-  **Datum des Verlustzeitraums**. Sie können ein Startdatum oder Enddatum angeben, wann das Exemplar verloren ging.

-  **Forderungseigentümer-in**. Sie können nach einem oder mehreren Forderungseigentümern filtern, um ihre spezifischen tatsächlichen Kostenpositionen zu sehen.

### Eine Rechnung für einen Artikel der tatsächlichen Kostenliste anwenden

Um einer Person die tatsächlichen Kosten für ein verlorenes Exemplar in Rechnung zu stellen, suchen Sie zunächst den Verlust-Datensatz. Sobald Sie den Datensatz gefunden haben, für den Sie die Rechnung stellen möchten:

1. Finden Sie den Verlust-Datensatz für das Exemplar, das Sie in Rechnung stellen möchten. Klicken Sie auf **Aktionen \> Tatsächliche Kosten in Rechnung stellen**.

2. Geben Sie im Modal **Tatsächliche Kosten zur Rechnungsstellung** den Betrag zur Rechnungsstellung ein. Fügen Sie bei Bedarf **Zusätzliche Informationen für das Personal** und **Zusätzliche Informationen für den Benutzer/die Benutzerin** hinzu. Klicken Sie auf **Fortfahren**.

3. Ein Bestätigungsmodal wird angezeigt. Wenn Sie etwas ändern möchten, klicken Sie auf **Weiter bearbeiten**, um zum vorherigen Modal zurückzukehren. Um fortzufahren und die Person zu belasten, klicken Sie auf **Bestätigen**.

Sobald Sie die Abrechnung der Person bestätigen, sehen Sie **Abgerechnet** in der Aktions-Spalte mit dem abgerechneten Betrag. Wenn Sie die Seite aktualisieren oder Ihren Browser-Tab schließen, wird beim nächsten Öffnen des Modals **Verlorene Exemplare bezüglich tatsächlicher Kosten** der verlorene Datensatz nicht mehr in der Liste der zu überprüfenden Exemplare angezeigt.

### Verarbeitung eines tatsächlichen Kostenexemplars ohne die Person zu belasten

Es wird Fälle geben, in denen Bibliotheken sich entscheiden, einer Person nichts für das verlorene Exemplar zu berechnen, aber dennoch die Gebühr bearbeiten und abschließen müssen.

Um einen verlorenen Datensatz als "Nicht in Rechnung stellen" zu markieren:

1. Finden Sie den Verlust-Datensatz für das Exemplar, das Sie als "Nicht berechnen" markieren möchten. Klicken Sie auf **Aktionen \> Nicht berechnen**.

2. Geben Sie im Modal **Nicht berechnen** bei Bedarf **Zusätzliche Informationen für das Personal** ein. Klicken Sie auf **Fortfahren**.

3. Ein Bestätigungsmodal wird angezeigt. Überprüfen Sie die Informationen. Wenn Sie etwas ändern möchten, klicken Sie auf **Weiter bearbeiten**, um zum vorherigen Modal zurückzukehren. Um fortzufahren, ohne die Person zu belasten, klicken Sie auf **Bestätigen**.

Wenn Sie fortfahren, die Person nicht zu belasten, sehen Sie **Nicht berechnet** in der Spalte Aktionen für diesen Datensatz erscheinen. Wenn Sie die Seite aktualisieren oder Ihren Browser-Tab schließen, wird die Gebühr, die Sie sich entschieden haben, nicht zu berechnen, das nächste Mal, wenn Sie das Modal **Verlorene Exemplare bezüglich tatsächlicher Kosten** öffnen, nicht mehr in der Personen-App sichtbar sein.

Beachten Sie, dass wenn Sie **Nicht in Rechnung stellen** auswählen und der Person auch keine Bearbeitungsgebühr für verlorene Exemplare hatte, das Markieren des Datensatzes des verlorenen Exemplars als **Nicht in Rechnung stellen** die Ausleihe abschließt und den Exemplarstatus auf **Verloren und bezahlt** ändert. FOLIO unterscheidet derzeit nicht zwischen Exemplarstatus, um anzuzeigen, ob ein Exemplar verloren ging und der Benutzer/-in dafür bezahlt hat, oder ob das Exemplar verloren ging und der Benutzer/-in dafür nicht bezahlt hat.
