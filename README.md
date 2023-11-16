# Dynamische Spracherkennung

[Einleitung](#einleitung)
[Anforderungen](#anforderungen)
[Umsetzung](#umsetzung)
  - [PocketSphinx einfügen](#pocketSphinx_einfügen)
  - [Konfiguration](#konfiguration)
  - [Implementation](#implementation)
  - [Verwendung in Klassen](#verwendung_in_Klassen)
  - []()
[Probleme/Lessons learned](#probleme/Lessons_learned)
[Fazit](#fazit)

## Einleitung
Welche Erweiterung haben Sie vorgenommen? Inwiefern verbessert das die App?
	
## Anforderungen
Was genau soll Ihre Erweiterung leisten?
	
## Umsetzung
Wie funktioniert Ihre Erweiterung? Was mussten Sie programmieren, was konnten Sie konfigurieren? Welche anderen Artefakte wie XML, Bilder etc. wurden bearbeitet/erstellt, und warum?

1. PocketSphinx einfügen
   - Abhängigkeit in build.gradle einfügen:
     'implementation 'edu.cmu.pocketsphinx:pocketsphinx-android:5prealpha-SNAPSHOT''
   - Berechtigung hinzufügen:
     '<uses-permission android:name="android.permission.RECORD_AUDIO" />'

2. Konfiguration
   - Erstellung einer Konfigurationsdatei im Assets-Verzeichnis.
  
   - Vordefinierte Sprachmodelle herunterladen:
     'https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/'

4. Implementation

5. Verwendung in Klassen
	
## Probleme/Lessons learned
Gab es Features/Details, die Sie nicht umsetzen konnten? Welche Probleme hätten Sie vermeiden können? Was würden Sie anders machen, wenn Sie noch mal neu beginnen würden?
	
## Fazit
Konnten Sie alles wie geplant umsetzen? War der zeitliche Aufwand so wie erwartet? 
