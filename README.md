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

1. GUI anpassung
   - Sprachauswahl in der root_preference.xml mit dropdown eingefügt
  
   <PreferenceCategory app:title="SPRACHE">

        <DropDownPreference
            android:key="languageSelection"
            android:title="Sprachauswahl"
            android:summary="Wähle eine Sprache aus:"
            android:entries="@array/language_entries"
            android:entryValues="@array/language_values"/>
    </PreferenceCategory>
  
    <string-array name="language_entries">
        <item>Deutsch</item>
        <item>English</item>
        <item>French</item>
        <item>Spanish</item>
    </string-array>

    <string-array name="language_values">
        <item>de</item>
        <item>en</item>
        <item>fr</item>
        <item>es</item>
    </string-array>

2. PocketSphinx einfügen

3. Implementation

4. Verwendung in Klassen
	
## Probleme/Lessons learned
Gab es Features/Details, die Sie nicht umsetzen konnten? Welche Probleme hätten Sie vermeiden können? Was würden Sie anders machen, wenn Sie noch mal neu beginnen würden?
	
## Fazit
Konnten Sie alles wie geplant umsetzen? War der zeitliche Aufwand so wie erwartet? 
