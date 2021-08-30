# Language Roadmap (v0.2)

All users get in touch with language during their usage of ILIAS. So do all people helping to write concepts and features, those writing the test cases and – of course – the maintainers and coders who provide the actual implementation.

The variety of actors leads to different flavours of language in ILIAS. The creation of a general style book has not yet gained enough traction.

Still, we would like to improve language in ILIAS. This is why we want to outline what we’re up to and provide pull requests based on our ideas presented in this document.

If you oppose (or support!) entries in this document, please comment and/or get on board.

**Unifying language variables**

Language variables are one of the many cross-cutting issues in ILIAS. Over time, the language increasingly diffuses apart. Continuous maintenance of the language variables should ensure and improve the uniformity of the system. This chapter describes the procedure and outlines the steps to unify the language variables. The priorities are discussed frequently with the maintainer.

## Tab Navigation

### Title of "Settings" tab and "General" Settings sub tab

The "Settings" tab is used in many ILIAS objects and services. The structure is very similar in all contexts of use – but the wording often differs. In order to simplify the handling and the learnability of the settings, wording should be adapted to each other.

**Suggested Pattern**
-The main tab for the settings of an object should always be called "Settings".
-There should be only one Settings tab per object or service.
-Since you are already in the Settings tab, the sub tabs should not get the addition "... Settings". Existing redundancies should be improved.
-If there is a sub tab that entails a variety of basic and general settings, it should be called "General". Other sub tabs should be named according to the settings groups contained.

**Currently used labels for the Basic/General Settings sub tab**

"Settings"
  -ILIAS Learning Module
  -Category
  -Study Programme
  -Glossary
  -Survey
  -Mediapool
  -Content Page
  -xAPI/cmi5
  -Bibliography
  -Administration > Personal Workspace > Who is online?-Tool
  -Administration > Personal Workspace > Tagging (Main tab here is called "Edit Settings", which should be corrected)

"General Settings"
  -Test&Assessment
  -Question Pool
  -Wiki
  -Exercise
  -Administration > Personal Workspace > Dashboard
  -Administration > Repository and Objects > Course
  -Administration > Repository and Objects > Group

"General"
  -Administration > Layout and Navigation > Editing
  -Administration > Communication > Mail
  -Administration > Search and Find > Metadata (Reiter heißt General Settings)

"Basic Settings"
  -Forum
  -Administration > System Settings and Maintenance > General Settings

"[Object name] Settings"
  -Course
  -Group
  -Administration > System Settings and Maintenance > Logging
  -Administration > User and Roles > Authentication and Registration (?eventuell Sonderfall? - mehrere Tabs mit Subeinstellungen)

"[Object] Properties"
  -Blog
  -Portfolio Template

"Settings for [Object name]"
  -SCORM Learning Module 1.2

"Edit"
  -Individual Assessment

"Object Settings [sic!]"
  -LTI Consumer

"Edit Settings"
  -Administration > Communication > News and Web Feeds (Reiter heißt Edit Settings) --> BUG REPORT

No Settings Tab
  -Administration > System Settings and Maintenance > System Check
  -Administration > System Settings and Maintenance > Repository Trash and Permissions (falschen Titel) --> BUG REPORT
  -Administration > Layout and Navigation > Main Menu
  -Administration > Layout and Navigation > Layout and Styles
  -Administration > User and Roles > terms of Service

Setting duplicates
  -Administration > Repository and Objects > Survey (Settings und Settings Templates)
  -Administration > Repository and Objects > Test (Settings und Settings Templates)

## Page Editor

###

unterschiedliche Editoren:
		- Seiteneditor / ILIAS-Seiteneditor / Editor / Standard-Seiteneditor / ILIAS-Editor -> ILIAS-Editor
		- TinyMCE / TinyMCE-Editor / Rich-Text-Editor (TinyMCE) / Rich-Text-Editor / Tiny MCE Editor -> TinyMCE-Editor
		- Zertifikat-Editor / certificate editor (EN) -> Zertifikatseinstellungen
            Administration > Achievements > Certificates
            Das hier angegebene Hintergrundbild wird bei allen Zertifikaten als Standard-Hintergrund verwendet, es sei denn, Sie geben im Zertifikat-Editor explizit ein anderes Hintergrundbild an.

            Das hier angegebene Hintergrundbild wird bei allen Zertifikaten als Standard-Hintergrund verwendet, es sei denn, Sie geben in den lokalen Zertifikatseinstellungen ein anderes Hintergrundbild an.

		- Styleeditor -> Content Style-Editor
            Administration > Layout > Editing
            Die Einstellung ersetzt die Buttons der semantischen Styleklassen für strong, emphatic und important durch die fest definierten Auszeichnungen B (bold), I (italic) und U (underline). Achtung: hierbei kann es zu Inkonsistenzen kommen, wenn über den Styleeditor den Styleklassen für strong, emphatic und important andere Auszeichnungen zugeordnet wurden.

            Die Einstellung ersetzt die Buttons der semantischen Styleklassen für strong, emphatic und important durch die fest definierten Auszeichnungen B (bold), I (italic) und U (underline). Achtung: hierbei kann es zu Inkonsistenzen kommen, wenn über den Content Style andere Auszeichnungen zugeordnet wurden.

		- Antwort-Editor
            Evtl. BUG: Eine Checkbox TinyMCE-Editor aktivieren. Byline: Der TinyMCE-Editor wird für die Antwort-Texte aktiviert. Damit können Sie mehrzeilige Antorten hinterlegen und den Antworttext gestalten.

		- Portfolio-Editor (exc) ->
            Im Übungsworkflow heißt auch das Beenden des Editors anders...Portfolio abschließen und abgeben.

            Möchten Sie die aktuelle Version Ihres Portfolios jetzt abgeben? Sie können dies auch jederzeit im Portfolio-Editor tun.

            Möchten Sie die aktuelle Version Ihres Portfolios jetzt abgeben? Sie können dies auch nach einer weiteren Bearbeitung tun.

		- Portfolio-Editor (exc) ->
            Möchten Sie die aktuelle Version Ihres Blogs jetzt abgeben? Sie können dies auch jederzeit im Blog-Editor tun.

            Möchten Sie die aktuelle Version Ihres Blogs jetzt abgeben? Sie können dies auch nach einer weiteren Bearbeitung tun.

### Customize Page

		- "Seite gestalten"
			- Magazin, Kategorie, Kurs
		- "Seite bearbeiten"
			- Lernmodul
			- Portfolio aus dem Reiter "Inhalt" über das Aktionen-Menü
		- "Bearbeiten"
			- Portfolio aus der Vorschau
				- Öffnen, dann sieht man die Voransicht mit Inhalten, Reitern usw.
				- Oben rechts dann Button "Bearbeiten" öffnet Editor
		- Loginseite gestalten / Loginscreen Editor (EN)

Editor beenden
		- "Bearbeitung beenden" ist immer da, oder?
    - Wird das nicht durch die Page Editor Revision geändert? Seitengestaltung beenden?
    - Wenn der Editor als Mode eingeführt wird, sollte das öffnen/starten des Editors präzise beschrieben werden....Editor öffnen/Editor beenden.


### Interne Links setzen

Block
    - Kein Link
    - WWW / Internet
        - Objekt » Ziel-Objekt wählen
    - Innerhalb von ILIAS

Medien
    - Link (extern)
    - Link (intern)
        - [Link auswählen]
    - Kein Link

Text (Seiteneditor unter ILIAS 7)
    - Interner Link
    - Externer Link
    - Benutzerprofil

## Weitere Anpassungen



## We want to find german Bezeichner for the following Words....



