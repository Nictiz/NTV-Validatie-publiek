**Let op:** T is de afgesproken referentiedatum. DocumentManifest is optioneel; stem bij ontbreken van ondersteuning de uitvoering van de relevante tests af op de NoManifest-variant.

### 1. Persoonsgegevens

| Veld | Waarde |
| --- | --- |
| Achternaam | XXX_Schulte |
| Voornaam | Eva |
| Voorletter(s) | E |
| Geslacht | Vrouw |
| Adresgegevens | Knolweg 1001, 9999XA, Stitswerd |
| Geboortedatum | 02-08-1964 |
| fBSN | 999910784 |

### 2. Zorgverleners

**Zorgverlener 1**

| Veld | Waarde |
| --- | --- |
| Achternaam | Snijder |
| Voorletter(s) | A.F. |

**Zorgverlener 2**

| Veld | Waarde |
| --- | --- |
| Achternaam | Kneder |
| Voorletter(s) | B. |

### 3. DocumentReferenties

**DocumentReferentie 4**

| Veld | Waarde |
| --- | --- |
| MasterIdentifier | Zelf te bepalen. |
| Status | Current |
| Type | Allergy and immunology Discharge summary, of type van eigen document. |
| Class | Discharge summary, of indien van toepassing class van eigen document. |
| Subject | XXX_Schulte |
| Indexed/Created | T - 320 |
| Author | Zorgverlener 1, zie tabel zorgverlener. |
| Title | Discharge summary, of van eigen document. |
| ContentType | Application/pdf |
| Language | Bij ondersteuning van dit concept een waarde invoeren. |
| Location PDF/A | Verwijzing naar een willekeurige PDF/A anders dan in een Binary-resource (indien dit niet wordt ondersteund, een verwijzing naar een willekeurige PDF/A in een Binary-resource). |
| Security label | Bij ondersteuning van dit concept een waarde invoeren. |

**DocumentReferentie 5**

| Veld | Waarde |
| --- | --- |
| MasterIdentifier | Zelf te bepalen. |
| Status | Indien entered-in-error of vergelijkbaar concept wordt ondersteund dit gebruiken. Indien dit niet wordt ondersteund, current gebruiken. |
| Type | Allergy and immunology Discharge summary, of type van eigen document. |
| Class | Discharge summary, of indien van toepassing class van eigen document. |
| Subject | XXX_Schulte |
| Indexed/Created | T - 320 |
| Author | Zorgverlener 1, zie tabel zorgverlener. |
| Title | Example PDF not in Binary, of van eigen document. |
| ContentType | Application/pdf |
| Language | Bij ondersteuning van dit concept een waarde invoeren. |
| Location PDF/A | Verwijzing naar een willekeurige PDF/A anders dan in een Binary-resource (indien dit niet wordt ondersteund, een verwijzing naar een willekeurige PDF/A in een Binary-resource). |
| Security label | Bij ondersteuning van dit concept een waarde invoeren. |

### 4. PDF/A-documenten

Document 4: **Document 4 - Discharge Summary.pdf**, of een eigen representatief document.

### 5. DocumentManifests

**DocumentManifest 1**

| Veld | Waarde |
| --- | --- |
| MasterIdentifier | Zelf te bepalen. |
| Identifier | Zelf te bepalen. |
| Status | Current |
| Type | Discharge summary, of type van eigen document. |
| Subject | XXX_Schulte |
| Created | T - 355 |
| Author | Zorgverlener 2, zie tabel zorgverlener. |
| Source | Eigen bronsysteem invoeren. |
| Content1 | Verwijzing naar DocumentReferentie 4 (zie hierboven), of DocumentReferentie van eigen document. |

**DocumentManifest 2**

| Veld | Waarde |
| --- | --- |
| MasterIdentifier | Zelf te bepalen. |
| Identifier | Zelf te bepalen. |
| Status | Indien superseded of vergelijkbaar concept wordt ondersteund dit gebruiken. Indien dit niet wordt ondersteund current gebruiken. |
| Type | Discharge summary, of type van eigen document. |
| Subject | XXX_Schulte |
| Created | T - 355 |
| Author | Zorgverlener 2, zie tabel zorgverlener. |
| Source | Eigen bronsysteem invoeren. |
| Content1 | Verwijzing naar DocumentReferentie 4 (zie hierboven), of DocumentReferentie van eigen document. |
| Content2 | Verwijzing naar DocumentReferentie 5 (zie hierboven), of DocumentReferentie van eigen document. |

*Opmerking: in werkelijkheid zou dit waarschijnlijk een historische versie zijn van DocumentManifest 1, met dezelfde identifiers en id. Voor testdoeleinden wordt deze als afzonderlijke resource-instantie ingevoerd.*

**DocumentManifest 3**

| Veld | Waarde |
| --- | --- |
| MasterIdentifier | Zelf te bepalen. |
| Identifier | Zelf te bepalen. |
| Status | Current |
| Type | Radiology Consult note, of type van eigen document. |
| Subject | XXX_Schulte |
| Created | T - 30 |
| Author | Zorgverlener 2, zie tabel zorgverlener. |
| Source | Eigen bronsysteem invoeren. |
| Content1 | Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |
| Content2 | Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |


