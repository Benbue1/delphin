1. Ziele des Projekts

  A. Zentrale Datenverwaltung
       Alle Mitgliederdaten sollen an einem Ort gepflegt werden können.
       Verschiedene Rollen (z. B. Trainer, Vorstand, Kassierer) erhalten Zugriff auf die für sie relevanten Informationen.

  B. Automatisierte Beitragsverwaltung & SEPA
      Mitglieder- und Bankdaten erfassen.
      Einfache Erstellung von SEPA-XML-Lastschriftdateien für den Beitragseinzug.

  C. Integration mit Microsoft 365
      Single-Sign-On über Azure Active Directory (M365) für die Benutzer, damit keine doppelten Logins gepflegt werden müssen.
      Optional: Nutzung von Microsoft Graph für Kalender-/E-Mail-Funktionen (z. B. automatisierte Termin-Einladungen, Mails an Mitglieder).





2. Funktionsumfang
  
  A. Mitgliederverwaltung
      Anlegen, Bearbeiten, Löschen von Personen (Name, Geburtsdatum, Adresse, Erreichbarkeiten, Mitgliedsnummer etc.).
      Bereiche für Schwimmer, Taucher, Aqua-Fitness, Trainer, Kampfrichter, Vorstandsfunktionen, Bank & Beitrag.
      Übersicht über alle Personen mit Filter- und Suchmöglichkeiten.

   B. Beitragsabrechnung
      Erfassen verschiedener Beitragsarten (z. B. Jahresbeitrag, Jugendbeitrag, Trainerbeitrag).
      Verknüpfen der Person mit der jeweiligen Beitragsart.
      Regelmäßige / einmalige Beiträge (Zahlungsintervalle).
      Erstellen von SEPA-XML-Dateien für Lastschrifteinzüge.

   C. Rollen- und Rechtemanagement
      Mindestanforderung: Rollen wie „Admin“ (Vollzugriff), „Kassierer“ (Zugriff auf Zahlungsdaten), „Trainer“ (eingeschränkter Zugriff, nur auf Gruppen).
      Authentifizierung über Microsoft 365-Konten (Azure AD).
      Autorisierungslogik festlegen (z. B. welche Daten darf eine Trainer-Rolle sehen, was darf ein Kassierer bearbeiten?).

  D. Anbindung von Kalenderfunktionen (z. B. Trainingstermine automatisch in den M365-Kalender eintragen).
      E-Mail-Benachrichtigungen über Outlook/Exchange (z. B. automatische Mails an Mitglieder).
      Dokumentenablage oder Downloadbereich (Upload von Lizenzen, Attesten, etc.).
