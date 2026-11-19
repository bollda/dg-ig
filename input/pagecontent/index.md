<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Ärztin oder ein Arzt erfasst eine Arzneimittelallergie in der Hausarztpraxis. Bei einem späteren Notfall kann das Behandlungsteam nachlesen, welches Arzneimittel betroffen ist, wie die Kritikalität eingeschätzt wurde und welche Reaktion dokumentiert ist.

### Scope

Dieser Implementation Guide beschreibt die strukturierte Dokumentation von Arzneimittelallergien mit FHIR. Er umfasst den klinischen Status, die Kritikalität, den Beginn der Allergie, die erfassende Person und bekannte Reaktionen. Lebensmittel- und Umweltallergien sowie Empfehlungen zur Behandlung liegen ausserhalb des Geltungsbereichs.

### Artefakte

TODO: Ergänzt pro Artefakt einen Satz, wofür es da ist.

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): beschreibt das FHIR-Profil für die Erfassung von Arzneimittelallergien.
- [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html) zeigt eine bestätigte Penicillinallergie mit dokumentierter Urtikaria.

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Daniel Bollinger

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
