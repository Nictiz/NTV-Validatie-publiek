**Let op:** T is de afgesproken referentiedatum.

### 1. Persoonsgegevens

| Veld | Waarde |
|---|---|
| Achternaam | XXX_Meijer |
| Voornaam | Laura |
| Voorletter(s) | L |
| Geslacht | Vrouw |
| Adresgegevens | Esdoornlaan 42, 3812BK, Amersfoort |
| Geboortedatum | 14-03-1967 |
| fBSN | 999910711 |

### 2. Zorgverleners

**Zorgverlener 1**

| Veld | Waarde |
|---|---|
| Achternaam | Snijder|
| Voorletter(s) | A.F. |

**Zorgverlener 2**

| Veld | Waarde |
|---|---|
| Achternaam | Herbst |
| Voorletter(s) | A. |

### 3. DocumentReferenties

**DocumentReferentie 4**

| Veld | Waarde |
|---|---|
| MasterIdentifier | Zelf te bepalen. |
| Status | Current |
| Type | Allergy and Immunology Discharge Summary (LOINC 68626-1). |
| Class | Discharge Summary (LOINC 18842-5). |
| Subject | Laura XXX_Meijer |
| Indexed/Created | T – 320 |
| Author | Zorgverlener 1, zie tabel zorgverleners. |
| Title |Discharge Summary. |
| Description | Allergologie en immunologie - Ontslagbrief |
| ContentType | application/pdf |
| Language | Bij ondersteuning van dit concept een waarde invoeren. |
| Location PDF/A | Verwijzing naar een willekeurige PDF/A anders dan in een Binary-resource (indien dit niet wordt ondersteund, een verwijzing naar een willekeurige PDF/A in een Binary-resource, bijvoorbeeld Document 3). |
| Security label | Bij ondersteuning van dit concept een waarde invoeren. |

**DocumentReferentie 5**

| Veld | Waarde |
|---|---|
| MasterIdentifier | Zelf te bepalen. |
| Status | Indien entered-in-error of vergelijkbaar concept wordt ondersteund dit gebruiken. Indien dit niet wordt ondersteund, current gebruiken.|
| Type | Plan of Care Note (LOINC 18776-5). |
| Subject | Laura XXX_Meijer |
| Indexed/Created | T – 320 |
| Author | Zorgverlener 2, zie tabel zorgverleners. |
| Title | Discharge Summary. |
| Description | Vervallen registratie - Ontslagbrief allergologie |
| ContentType | application/pdf |
| Language | Bij ondersteuning van dit concept een waarde invoeren. |
| Location PDF/A | Verwijzing naar daadwerkelijke PDF/A in een Binary-resource (PDF/A-document 4). |
| Security label | Bij ondersteuning van dit concept een waarde invoeren. |

### 6. Documenten

Document 3: **Zorgplan hypertensie - Laura Meijer.pdf**
Document 4: **Verwijsbrief fysiotherapie - Laura Meijer.pdf**

### 5. DocumentManifests

Registreer de onderstaande documentverzamelingen. Iedere DocumentManifest verwijst naar één of meerdere DocumentReferences.

**DocumentManifest 1**

| Veld | Waarde |
|---|---|
| MasterIdentifier | Zelf te bepalen. |
| Status | Current |
| Type | Discharge Summary (LOINC 18842-5) |
| Subject | Laura XXX_Meijer |
| Created | T – 355 |
| Author | Zorgverlener 2, zie tabel zorgverleners. |
| Source | URL van het bronsysteem. In de testdata: `http://xis.org/example`. |
| Content | DocumentReferentie 4, zie hierboven. |

**DocumentManifest 2**

| Veld | Waarde |
|---|---|
| MasterIdentifier | Zelf te bepalen. |
| Status | Superseded |
| Type | Summary of Episode Note (LOINC 34133-9) |
| Subject | Laura XXX_Meijer |
| Created | T – 355 |
| Author | Zorgverlener 2, zie tabel zorgverleners. |
| Source | URL van het bronsysteem. In de testdata: `http://xis.org/example`. |
| Content 1| Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |
| Content 2| Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |

**DocumentManifest 3**

| Veld | Waarde |
|---|---|
| MasterIdentifier | Zelf te bepalen, uniek voor DocumentManifest 3. |
| Status | Current |
| Type | Plan of Care Note (LOINC 18776-5) |
| Subject | Laura XXX_Meijer |
| Created | T – 30 |
| Author | Zorgverlener 2, zie tabel zorgverleners. |
| Source | URL van het bronsysteem. In de testdata: `http://xis.org/example`. |
| Content 1| Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |
| Content 2| Verwijzing naar een willekeurige DocumentReferentie. Geen voorbeeld beschikbaar. |
