# Testdossier3-XXX_vandeStok

Bron: [MedMij R4 DentalCare IG — versie 1.0.0-rc.2](https://simplifier.net/guide/medmij-r4-dentalcare-ig/Home/Test-Material/Test-material-scenario-3?version=1.0.0-rc.2)

[1. MedMij Core: ASA-score 1.0.0-rc3](#1-medmij-core-asa-score-100-rc3)
[2. MedMij Core: Contact 1.0.0-rc3](#2-medmij-core-contact-100-rc3)
[3. MedMij Core: Patiënt 1.0.0-rc.3](#3-medmij-core-patiënt-100-rc3)
[3.1 Patiënt: Berend van de stok](#31-patiënt-berend-van-de-stok)
[3.2 Contactpersoon: Piet Klaas](#32-contactpersoon-piet-klaas)
[4. MedMij Core: Betaler 1.0.0-rc3](#4-medmij-core-betaler-100-rc3)
[4.1 Payer: Berend van de Stok](#41-payer-berend-van-de-stok)
[4.2 Payer: Verzekeraar Helderzicht](#42-payer-verzekeraar-helderzicht)
[5. MedMij Core: Behandeldoel 1.0.0-rc3](#5-medmij-core-behandeldoel-100-rc3)
[5.1 Treatment Objective: Trekken snijtand linksboven](#51-treatment-objective-trekken-snijtand-linksboven)
[5.2 Treatment Objective: Wortelpuntoperatie (apexresectie)](#52-treatment-objective-wortelpuntoperatie-apexresectie)
[5.3 Treatment Objective: Gewenste gezondheidstoestand: kan kauwen, specifiek doel: geen probleem met kauwen](#53-treatment-objective-gewenste-gezondheidstoestand-kan-kauwen-specifiek-doel-geen-probleem-met-kauwen)
[6. MedMij Core: Health Professional data 1.0.0-rc.3 (referentiedata)](#6-medmij-core-health-professional-data-100-rc3-referentiedata)
[7. MedMij Core: Healthcare Provider 1.0.0-rc.3 (referentiedata)](#7-medmij-core-healthcare-provider-100-rc3-referentiedata)
[8. Verzamelen Mondzorg: Cariësrisico 1.0.0-rc2](#8-verzamelen-mondzorg-cariësrisico-100-rc2)
[9. Verzamelen Mondzorg: Dental Fitness 1.0.0-rc2 - niet aanwezig](#9-verzamelen-mondzorg-dental-fitness-100-rc2---niet-aanwezig)
[10. Verzamelen Mondzorg: Mondhygiëne 1.0.0-rc2](#10-verzamelen-mondzorg-mondhygiëne-100-rc2)
[11. Verzamelen Mondzorg: Parafunctionele activiteit 1.0.0-rc2](#11-verzamelen-mondzorg-parafunctionele-activiteit-100-rc2)
[12. Verzamelen Mondzorg: Periodieke Parodontale Screening-score 1.0.0-rc2](#12-verzamelen-mondzorg-periodieke-parodontale-screening-score-100-rc2)
[13. Verzamelen Mondzorg: Verrichting 1.0.0-rc2](#13-verzamelen-mondzorg-verrichting-100-rc2)

## 1. MedMij Core: ASA-score 1.0.0-rc3

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|0892c80d-df37-438a-ae24-20243feec745 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|EffectiveDateTime|01-01-2024 10:43|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|ASAScoreValue|ASA-score 3 (code '413497009' from code system 'SNOMED CT')|
|Performer|B. Dijkstra, Orthodontist|
|Comment|Allergisch voor gluten, heeft nierziekte en bloedarmoede|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 2. MedMij Core: Contact 1.0.0-rc3

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|bb9c5cf0-25e5-47e4-a9a9-350ec964fc6d (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider||
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|ContactType|Poliklinisch (code 'AMB' from code system 'ActCode')|
|ContactWith|B. Dijkstra, Orthodontist|
|Location|Orthodontiepraktijk Dijkstra|
|StartDateTime|01-08-2025 09:00|
|EndDateTime|01-08-2025 09:30|
|ContactReason - Problem||
|ContactReason - Procedure||
|ContactReason - DeviatingResult||
|ContactReason - CommentContactReason||
|Origin||
|Destination||

[Terug naar boven](#testdossier3-xxx_vandestok)

## 3. MedMij Core: Patiënt 1.0.0-rc.3

### 3.1 Patiënt: Berend van de stok

|Veld|Waarde|
|:--|:--|
|NameInformation - FirstNames|Berend|
|NameInformation - Initials||
|NameInformation - GivenName|Beer|
|NameInformation - NameUsage||
|NameInformation - LastName - Prefix|van de|
|NameInformation - LastName - LastName|Stok|
|NameInformation - LastNamePartner - PartnerPrefix||
|NameInformation - LastNamePartner - PartnerLastName||
|NameInformation - Titles||
|AddressInformation - Street|Bloemstraat|
|AddressInformation - HouseNumber|25|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|5678 BB|
|AddressInformation - PlaceOfResidence|Bergen op Zoom|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Officieel adres (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31687654321|
|ContactInformation - TelephoneNumbers - TelecomType|Mobiel telefoonnummer (code 'MC' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - NumberType|Telefoonnummer thuis (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<berendvandestok@gmail.com>|
|ContactInformation - EmailAddresses - EmailAddressType|Privé e-mailadres (code 'HP' from code system 'AddressUse')|
|PatientIdentificationNumber|999998304 (in identifier system 'Burgerservicenummer')|
|DateOfBirth|04-05-1980|
|Gender|Man (code 'M' from code system 'AdministrativeGender')|
|MultipleBirthIndicator||
|DeathIndicator|Nee|
|DateOfDeath||

### 3.2 Contactpersoon: Piet Klaas

|Veld|Waarde|
|:--|:--|
|NameInformation - FirstNames|Piet|
|NameInformation - Initials||
|NameInformation - GivenName||
|NameInformation - NameUsage||
|NameInformation - LastName - Prefix||
|NameInformation - LastName - LastName|Klaas|
|NameInformation - LastNamePartner - PartnerPrefix||
|NameInformation - LastNamePartner - PartnerLastName||
|NameInformation - Titles||
|ContactInformation - TelephoneNumbers - TelephoneNumber||
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType||
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress||
|ContactInformation - EmailAddresses - EmailAddressType||
|AddressInformation - Street||
|AddressInformation - HouseNumber||
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode||
|AddressInformation - PlaceOfResidence||
|AddressInformation - Municipality||
|AddressInformation - Country||
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType||
|Role|Eerste relatie/contactpersoon (code '01' from code system 'COD472-VEKT')|
|Relationship|Vader (code 'FTH' from code system 'RoleCode')|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 4. MedMij Core: Betaler 1.0.0-rc3

### 4.1 Payer: Berend van de Stok

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|d2987f88-2494-4bf5-aca4-7838c0d84d54 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|PayerPerson - PayerName|Berend van de Stok|
|PayerPerson - BankInformation - BankName|ABNA|
|PayerPerson - BankInformation - BankCode|ABNA00NL|
|PayerPerson - BankInformation - AccountNumber|NL00ABNA0001234567|
|InsuranceCompany - Insurance - StartDateTime||
|InsuranceCompany - Insurance - EndDateTime||
|InsuranceCompany - Insurance - InsuranceType||
|InsuranceCompany - IdentificationNumber||
|InsuranceCompany - OrganizationName||
|InsuranceCompany - InsurantNumber||
|AddressInformation - Street|Bloemstraat|
|AddressInformation - HouseNumber|25|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|5678 BB|
|AddressInformation - PlaceOfResidence|Bergen op Zoom|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Officieel adres (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31687654321|
|ContactInformation - TelephoneNumbers - TelecomType|Mobiel telefoonnummer (code 'MC' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - NumberType|Telefoonnummer thuis (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<berendvandestok@gmail.com>|
|ContactInformation - EmailAddresses - EmailAddressType|Privé e-mailadres (code 'HP' from code system 'AddressUse')|

### 4.2 Payer: Verzekeraar Helderzicht

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|27c25ab9-9ec7-4f2e-b125-adad8694ca1f (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|PayerPerson - PayerName||
|PayerPerson - BankInformation - BankName||
|PayerPerson - BankInformation - BankCode||
|PayerPerson - BankInformation - AccountNumber||
|InsuranceCompany - Insurance - StartDateTime|01-01-2024|
|InsuranceCompany - Insurance - EndDateTime|01-01-2026|
|InsuranceCompany - Insurance - InsuranceType|Tandverzekering (los) (code 'T' from code system 'Verzekeringssoort')|
|InsuranceCompany - IdentificationNumber||
|InsuranceCompany - OrganizationName|Verzekeraar Helderzicht|
|InsuranceCompany - InsurantNumber|12345679|
|AddressInformation - Street|Parksingel|
|AddressInformation - HouseNumber|8|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|9995 XX|
|AddressInformation - PlaceOfResidence|Den Helder|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber||
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType||
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress||
|ContactInformation - EmailAddresses - EmailAddressType||

[Terug naar boven](#testdossier3-xxx_vandestok)

## 5. MedMij Core: Behandeldoel 1.0.0-rc3

### 5.1 Treatment Objective: Trekken snijtand linksboven

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|fa406aee-3588-4c45-b282-c4a3fb5464de (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider||
|EffectiveDateTime||
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|DesiredHealthcareResult|Trekken snijtand linksboven|
|DesiredHealthCondition - StatusName||
|DesiredHealthCondition - StatusValue||
|DesiredHealthCondition - StatusDate||
|DesiredHealthCondition - Comment||
|DesiredHealthCondition - MedicalDevice||
|Problem|Malocclusie met scheefstand van de snijtand linksboven|
|Priority|Hoge prioriteit (code 'high-priority' from code system 'GoalPriority')|

#### 5.1.1. Problem: Malocclusie met scheefstand van de snijtand linksboven (referentiedata)

|Veld|Waarde|
|:--|:--|
|ProblemType|Diagnose (code '282291009' from code system 'SNOMED CT')|
|ProblemName|malocclusie van tanden en/of kiezen (code '47944004' from code system 'SNOMED CT')|
|FurtherSpecificationProblemName|Malocclusie met scheefstand van de snijtand linksboven|
|ProblemAnatomicalLocation - Location|bovenste tandboog (code '39481002' from code system 'SNOMED CT')|
|ProblemAnatomicalLocation - Laterality||
|ProblemStartDate|15-11-2023|
|ProblemEndDate||
|ProblemStatus|Actueel (code '55561003' from code system 'SNOMED CT')|
|VerificationStatus|Bevestigd (code '410605003' from code system 'SNOMED CT')|
|Comment|Malocclusie met scheefstand van de snijtand linksboven; orthodontische behandeling met vaste beugel gepland na paro-stabilisatie en extractie.|

### 5.2 Treatment Objective: Wortelpuntoperatie (apexresectie)

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|594f942b-f84f-43db-85e8-f473b7187428 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider||
|EffectiveDateTime||
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|DesiredHealthcareResult|Wortelpuntoperatie (apexresectie)|
|DesiredHealthCondition - StatusName||
|DesiredHealthCondition - StatusValue||
|DesiredHealthCondition - StatusDate||
|DesiredHealthCondition - Comment||
|DesiredHealthCondition - MedicalDevice||
|Problem||
|Priority|Lage prioriteit (code 'low-priority' from code system 'GoalPriority')|

### 5.3 Treatment Objective: Gewenste gezondheidstoestand: kan kauwen, specifiek doel: geen probleem met kauwen

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|9fe343ae-b170-4a5f-9491-9fb9eaebca23 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider||
|EffectiveDateTime||
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|DesiredHealthcareResult||
|DesiredHealthCondition - StatusName|kan kauwen (code '288919008' from code system 'SNOMED CT')|
|DesiredHealthCondition - StatusValue|geen probleem met kauwen (code '162019007' from code system 'SNOMED CT')|
|DesiredHealthCondition - StatusDate|01-08-2025|
|DesiredHealthCondition - Comment|Na extractie snijtand linksboven en orthodontische behandeling met vaste beugel moet het kauwen weer klachtenvrij zijn.|
|DesiredHealthCondition - MedicalDevice|Vaste multibracket-beugel bovenboog|
|Problem|Malocclusie met scheefstand van de snijtand linksboven|
|Priority|Hoge prioriteit (code 'high-priority' from code system 'GoalPriority')|

#### 5.3.1 Medical Device: Vaste multibracket-beugel bovenboog (referentiedata)

|Veld|Waarde|
|:--|:--|
|Product - ProductID|(01)08712345678906(11)240115(17)290115(10)ORTHO24A(21)BVDS0001|
|Product - ProductType|orthodontische apparatuur (code '25742001' from code system 'SNOMED CT')|
|ProductDescription|Vaste multibracket-beugel voor de bovenboog|
|AnatomicalLocation - Location|bovenste tandboog (code '39481002' from code system 'SNOMED CT')|
|AnatomicalLocation - Laterality||
|Indication|Malocclusie met scheefstand van de snijtand linksboven|
|StartDate|01-02-2024|
|EndDate|01-08-2025|
|Comment|Vaste multibracket-beugel in de bovenboog geplaatst na paro-stabilisatie en extractie; controle elke zes weken.|
|Location|Orthodontiepraktijk Dijkstra|
|HealthProfessional|B. Dijkstra, Orthodontist|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 6. MedMij Core: Health Professional data 1.0.0-rc.3 (referentiedata)

|Veld|Waarde|
|:--|:--|
|HealthProfessionalIdentificationNumber|12000003 (in identifier system 'BIG register inschrijvingsnummer')|
|NameInformation - FirstNames||
|NameInformation - Initials|B.|
|NameInformation - GivenName||
|NameInformation - NameUsage||
|NameInformation - LastName - Prefix||
|NameInformation - LastName - LastName|Dijkstra|
|NameInformation - LastNamePartner - PartnerPrefix||
|NameInformation - LastNamePartner - PartnerLastName||
|NameInformation - Titles||
|Speciality|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|Gender||
|AddressInformation - Street|Stationsstraat|
|AddressInformation - HouseNumber|18|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|4611 XX|
|AddressInformation - PlaceOfResidence|Bergen op Zoom|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31612345604|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<dijkstra@orthodontiedijkstra.nl>|
|ContactInformation - EmailAddresses - EmailAddressType|Zakelijk e-mailadres (code 'WP' from code system 'AddressUse')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|HealthProfessionalRole||

[Terug naar boven](#testdossier3-xxx_vandestok)

## 7. MedMij Core: Healthcare Provider 1.0.0-rc.3 (referentiedata)

|Veld|Waarde|
|:--|:--|
|HealthcareProviderIdentificationNumber|13004567 (in identifier system 'Vektis AGB-zorgverlener tabel')|
|OrganizationName|Orthodontiepraktijk Dijkstra|
|DepartmentSpeciality|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|0164123456|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<info@orthodontiedijkstra.nl>|
|ContactInformation - EmailAddresses - EmailAddressType|Zakelijk e-mailadres (code 'WP' from code system 'AddressUse')|
|AddressInformation - Street|Stationsstraat|
|AddressInformation - HouseNumber|18|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|4611 XX|
|AddressInformation - PlaceOfResidence|Bergen op Zoom|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|OrganizationType||
|OrganizationLocation - LocationName||
|OrganizationLocation - LocationNumber||

[Terug naar boven](#testdossier3-xxx_vandestok)

## 8. Verzamelen Mondzorg: Cariësrisico 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|7d351e57-3ee3-4a7c-8e93-2c3789d0314a (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|EffectiveDateTime|01-01-2024 10:43|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|CariesRiskValue|verhoogd (code '35105006' from code system 'SNOMED CT')|
|Performer|B. Dijkstra, Orthodontist|
|Comment|Verhoogd risico mede i.v.m. comorbiditeit (nierziekte, bloedarmoede).|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 9. Verzamelen Mondzorg: Dental Fitness 1.0.0-rc2 - niet aanwezig

[Terug naar boven](#testdossier3-xxx_vandestok)

## 10. Verzamelen Mondzorg: Mondhygiëne 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|f8d64a19-1350-4c20-9567-9395b8ba0978 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|EffectiveDateTime|01-01-2024 10:43|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen'), Mondhygiënisten (code '8700' from code system 'Vektis AGB-medische specialismen')|
|OralHygieneValue|goed (code '20572008' from code system 'SNOMED CT')|
|Performer|B. Dijkstra, Orthodontist|
|Comment|Goede mondhygiëne; eerdere parodontitis met stabiele restpockets.|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 11. Verzamelen Mondzorg: Parafunctionele activiteit 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|87ecdf20-f2b0-4024-aaf7-67548be399a4 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|EffectiveDateTime|01-01-2024 10:43|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|ParafunctionalActivityValue|Tanden knarsen tijdens slaap|
|Performer|B. Dijkstra, Orthodontist|
|Comment||

[Terug naar boven](#testdossier3-xxx_vandestok)

## 12. Verzamelen Mondzorg: Periodieke Parodontale Screening-score 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|04f2e128-5ce8-491f-b518-b6afe4c69447 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|EffectiveDateTime|01-01-2024 10:43|
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|PeriodicPeriodontalScreeningScoreValue|Pockets groter dan of gelijk aan 6 millimeter = wellicht niet in orde (code 'ppsscore3' from code system 'PeriodicPeriodontalScreeningScore')|
|Performer|B. Dijkstra, Orthodontist|
|Comment|Verwezen naar paro; orthodontische behandeling pas na paro-stabilisatie (jan–feb 2024).|

[Terug naar boven](#testdossier3-xxx_vandestok)

## 13. Verzamelen Mondzorg: Verrichting 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|1b48b2b6-2a04-41b6-a86b-06652937a253 (in identifier system '<https://orthodontiepraktijk-dijkstra.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Orthodontiepraktijk Dijkstra|
|StartDateTime|01-01-2024|
|EndDateTime||
|CareType|Tandartsspecialisten dentomaxillaire orthopaedie (code '1300' from code system 'Vektis AGB-medische specialismen')|
|ProcedureType|Eerste consult (code 'F121A' from code system 'Vektis Prestatiecodelijst Mondzorg')|
|ProcedureMethod||
|ProcedureAnatomicalLocation - Location||
|ProcedureAnatomicalLocation - Laterality||
|Indication - ProblemType||
|Indication - ProblemName||
|Indication - FurtherSpecificationProblemName||
|Indication - ProblemAnatomicalLocation - Location||
|Indication - ProblemAnatomicalLocation - Laterality||
|Indication - ProblemStartDate||
|Indication - ProblemEndDate||
|Indication - ProblemStatus||
|Indication - VerificationStatus||
|Indication - Comment||
|Location|Orthodontiepraktijk Dijkstra|
|Performer|B. Dijkstra, Orthodontist|

[Terug naar boven](#testdossier3-xxx_vandestok)
