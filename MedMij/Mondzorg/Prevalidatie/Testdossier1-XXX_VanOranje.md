# Testdossier1-XXX_VanOranje

Bron: [MedMij R4 DentalCare IG — versie 1.0.0-rc.2](https://simplifier.net/guide/medmij-r4-dentalcare-ig/Home/Test-Material/Test-material-scenario-1?version=1.0.0-rc.2)

[1. MedMij Core: ASA-score 1.0.0-rc3](#1-medmij-core-asa-score-100-rc3)
[2. MedMij Core: Contact 1.0.0-rc3](#2-medmij-core-contact-100-rc3)
[2.1 Encounter: 20-05-2026](#21-encounter-20-05-2026)
[2.2 Encounter: 20-05-2025](#22-encounter-20-05-2025)
[3. MedMij Core: Patient 1.0.0-rc.3](#3-medmij-core-patient-100-rc3)
[3.1 Patient: Erik van Oranje](#31-patient-erik-van-oranje)
[3.2 Contact Person: Leo Jansen](#32-contact-person-leo-jansen)
[4. MedMij Core: Betaler 1.0.0-rc3](#4-medmij-core-betaler-100-rc3)
[4.1 Payer: Erik van Oranje](#41-payer-erik-van-oranje)
[4.2 Payer: Zorgkantoor Noorderlicht](#42-payer-zorgkantoor-noorderlicht)
[5. MedMij Core: Behandeldoel 1.0.0-rc3](#5-medmij-core-behandeldoel-100-rc3)
[5.1 Treatment Objective: Gingivitis/tandvleesontsteking behandelen](#51-treatment-objective-gingivitistandvleesontsteking-behandelen)
[5.2 Treatment Objective: Cariës rechterbovenkies restaureren](#52-treatment-objective-cariës-rechterbovenkies-restaureren)
[6. MedMij Core: Health Professional data 1.0.0-rc.3 (referentiedata)](#6-medmij-core-health-professional-data-100-rc3-referentiedata)
[6.1 Health Professional: A.B.D.O. de Koning](#61-health-professional-abdo-de-koning)
[6.2 Health Professional: S. Vermeer](#62-health-professional-s-vermeer)
[7 MedMij Core: Healthcare Provider 1.0.0-rc.3 (referentiedata)](#7-medmij-core-healthcare-provider-100-rc3-referentiedata)
[7.1 Healthcare Provider: Mondzorgcentrum Lindenhof](#71-healthcare-provider-mondzorgcentrum-lindenhof)
[7.2 Healthcare Provider: Praktijklocatie Lindenhof](#72-healthcare-provider-praktijklocatie-lindenhof)
[8. Verzamelen Mondzorg: Cariësrisico 1.0.0-rc2](#8-verzamelen-mondzorg-cariësrisico-100-rc2)
[9. Verzamelen Mondzorg: Dental Fitness 1.0.0-rc2](#9-verzamelen-mondzorg-dental-fitness-100-rc2)
[10. Verzamelen Mondzorg: Mondhygiëne 1.0.0-rc2](#10-verzamelen-mondzorg-mondhygiëne-100-rc2)
[11. Verzamelen Mondzorg: Parafunctionele activiteit 1.0.0-rc2](#11-verzamelen-mondzorg-parafunctionele-activiteit-100-rc2)
[12. Verzamelen Mondzorg - Periodieke Parodontale Screening-score 1.0.0-rc2](#12-verzamelen-mondzorg---periodieke-parodontale-screening-score-100-rc2)
[13. Verzamelen Mondzorg - Verrichting 1.0.0-rc2](#13-verzamelen-mondzorg---verrichting-100-rc2)

## 1. MedMij Core: ASA-score 1.0.0-rc3

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|bdabb6dc-a6be-4124-85c5-49bd385a9868 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|03-06-2025 09:05|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ASAScoreValue|ASA-score 1 (code '413495001' from code system 'SNOMED CT')|
|Performer|A.B.D.O. de Koning, Tandarts|
|Comment|Geen relevante gezondheidsveranderingen sinds vorige keuring; patiënt is inzetbaar, geen medicatie of allergieën.|

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 2. MedMij Core: Contact 1.0.0-rc3

### 2.1 Encounter: 20-05-2026

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|3fd0d3e1-960d-4a05-8ab5-76adbc1ecdce (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ContactType|Anders (code 'OTH' from code system 'NullFlavor'): Tandarts Periodiek Preventief Onderzoek|
|ContactWith|A.B.D.O. de Koning, Tandarts|
|Location|Praktijklocatie Lindenhof|
|StartDateTime|20-05-2026 10:00|
|EndDateTime|20-05-2026 11:00|
|ContactReason - Problem||
|ContactReason - Procedure||
|ContactReason - DeviatingResult|Vorige orthopantomogram (röntgenfoto) was in 2025|
|ContactReason - CommentContactReason|Jaarlijkse periodiek preventief onderzoek|
|Origin||
|Destination||

### 2.2 Encounter: 20-05-2025

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|2ffbc4f2-95e8-4b98-a803-34386f4595e9 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ContactType|Anders (code 'OTH' from code system 'NullFlavor'): Tandarts Periodiek Preventief Onderzoek|
|ContactWith|A.B.D.O. de Koning, Tandarts|
|Location|Praktijklocatie Lindenhof|
|StartDateTime|20-05-2025 10:00|
|EndDateTime|20-05-2025 11:00|
|ContactReason - Problem|Cariës rechterbovenkies|
|ContactReason - Procedure||
|ContactReason - DeviatingResult||
|ContactReason - CommentContactReason|Periodiek preventief onderzoek: cariës rechterbovenkies vastgesteld; restauratie gepland. Tevens gingivitis bij slechte mondhygiëne.|
|Origin|Eigen woonomgeving (code '264362003' from code system 'SNOMED CT')|
|Destination||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 3. MedMij Core: Patient 1.0.0-rc.3

### 3.1 Patient: Erik van Oranje

|Veld|Waarde|
|:--|:--|
|Name Information - FirstNames|Erik|
|Name Information - Initials||
|Name Information - GivenName|Erik|
|Name Information - NameUsage|Eigen geslachtsnaam (code 'NL1' from code system 'NaamGebruik')|
|Name Information - LastName - Prefix|van|
|Name Information - LastName - LastName|Oranje|
|Name Information - LastNamePartner - PartnerPrefix||
|Name Information - LastNamePartner - PartnerLastName||
|Name Information - Titles||
|Address Information - Street|De Doerak|
|Address Information - HouseNumber|57|
|Address Information - HouseNumberLetter|A|
|Address Information - HouseNumberAddition||
|Address Information - HouseNumberIndication||
|Address Information - Postcode|6123 PP|
|Address Information - PlaceOfResidence|Montferland|
|Address Information - Municipality||
|Address Information - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|Address Information - AdditionalInformation||
|Address Information - AddressType|Officieel adres (code 'HP' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - TelephoneNumber|+31612345600|
|Contact Information - TelephoneNumbers - TelecomType|Mobiel telefoonnummer (code 'MC' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - NumberType|Telefoonnummer thuis (code 'HP' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - Comment||
|Contact Information - EmailAddresses - EmailAddress|<erikvanoranje@test.com>|
|Contact Information - EmailAddresses - EmailAddressType|Privé e-mailadres (code 'HP' from code system 'AddressUse')|
|PatientIdentificationNumber|999998286 (in identifier system 'Burgerservicenummer')|
|DateOfBirth|02-08-1991|
|Gender|Man (code 'M' from code system 'AdministrativeGender')|
|MultipleBirthIndicator||
|DeathIndicator|Nee|
|DateOfDeath||

### 3.2 Contact Person: Leo Jansen

|Veld|Waarde|
|:--|:--|
|Name Information - FirstNames|Leo|
|Name Information - Initials||
|Name Information - GivenName||
|Name Information - NameUsage|Eigen geslachtsnaam gevolgd door geslachtsnaam partner (code 'NL4' from code system 'NaamGebruik')|
|Name Information - LastName - Prefix||
|Name Information - LastName - LastName|Jansen|
|Name Information - LastNamePartner - PartnerPrefix|van der|
|Name Information - LastNamePartner - PartnerLastName|Heide|
|Name Information - Titles|MSc|
|Address Information - Street|Kerkstraat|
|Address Information - HouseNumber|12|
|Address Information - HouseNumberLetter|B|
|Address Information - HouseNumberAddition||
|Address Information - HouseNumberIndication|Bij (code 'by' from code system 'AanduidingBijHuisnummer')|
|Address Information - Postcode|6942 AB|
|Address Information - PlaceOfResidence|Didam|
|Address Information - Municipality|Montferland|
|Address Information - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|Address Information - AdditionalInformation|boven de bakkerij|
|Address Information - AddressType|Officieel adres (code 'HP' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - TelephoneNumber|+31612345611|
|Contact Information - TelephoneNumbers - TelecomType|Mobiel telefoonnummer (code 'MC' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - NumberType|Telefoonnummer thuis (code 'HP' from code system 'AddressUse')|
|Contact Information - TelephoneNumbers - Comment|Bereikbaar op werkdagen tussen 9.00 en 17.00 uur|
|Contact Information - EmailAddresses - EmailAddress|<leojansen@test.com>|
|Contact Information - EmailAddresses - EmailAddressType|Privé e-mailadres (code 'HP' from code system 'AddressUse')|
|Role|Eerste relatie/contactpersoon (code '01' from code system 'COD472-VEKT')|
|Role|Mantelzorger (code '100001' from code system 'ExtraRolcodes')|
|Relationship||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 4. MedMij Core: Betaler 1.0.0-rc3

### 4.1 Payer: Erik van Oranje

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|95f5850e-1bfd-4aad-b6dc-45beee67f185 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|PayerPerson - PayerName|Erik van Oranje|
|PayerPerson - BankInformation - BankName|ING|
|PayerPerson - BankInformation - BankCode|INGBNL2A|
|PayerPerson - BankInformation - AccountNumber|NL85INGB0001234567|
|InsuranceCompany - Insurance - StartDateTime||
|InsuranceCompany - Insurance - EndDateTime||
|InsuranceCompany - Insurance - InsuranceType||
|InsuranceCompany - IdentificationNumber||
|InsuranceCompany - OrganizationName||
|InsuranceCompany - InsurantNumber||
|AddressInformation - Street|De Doerak|
|AddressInformation - HouseNumber|57|
|AddressInformation - HouseNumberLetter|A|
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|6123 PP|
|AddressInformation - PlaceOfResidence|Montferland|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Officieel adres (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31612345600|
|ContactInformation - TelephoneNumbers - TelecomType|Mobiel telefoonnummer (code 'MC' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - NumberType|Telefoonnummer thuis (code 'HP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<erikvanoranje@test.com>|
|ContactInformation - EmailAddresses - EmailAddressType|Privé e-mailadres (code 'HP' from code system 'AddressUse')|

### 4.2 Payer: Zorgkantoor Noorderlicht

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|b60e42e2-e133-4528-873c-292f0bb29093 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|PayerPerson - PayerName||
|PayerPerson - BankInformation - BankName||
|PayerPerson - BankInformation - BankCode||
|PayerPerson - BankInformation - AccountNumber||
|InsuranceCompany - Insurance - StartDateTime|01-01-2025|
|InsuranceCompany - Insurance - EndDateTime|01-01-2026|
|InsuranceCompany - Insurance - InsuranceType|Basis (code 'B' from code system 'Verzekeringssoort')|
|InsuranceCompany - IdentificationNumber|9901 (in identifier system 'UZOVI')|
|InsuranceCompany - OrganizationName|Zorgkantoor Noorderlicht|
|InsuranceCompany - InsurantNumber|12345678|
|AddressInformation - Street|Kadeweg|
|AddressInformation - HouseNumber|22|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|9994 XX|
|AddressInformation - PlaceOfResidence|Harlingen|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|0501234567|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress||
|ContactInformation - EmailAddresses - EmailAddressType||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 5. MedMij Core: Behandeldoel 1.0.0-rc3

### 5.1 Treatment Objective: Gingivitis/tandvleesontsteking behandelen

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|b9239217-7b5b-465b-a550-c3cabceb7983 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen'), Mondhygiënisten (code '8700' from code system 'Vektis AGB-medische specialismen')|
|DesiredHealthcareResult|Gingivitis/tandvleesontsteking behandelen|
|DesiredHealthCondition - StatusName||
|DesiredHealthCondition - StatusValue||
|DesiredHealthCondition - StatusDate||
|DesiredHealthCondition - Comment||
|DesiredHealthCondition - MedicalDevice||
|Problem||
|Priority|Hoge prioriteit (code 'high-priority' from code system 'GoalPriority')|

### 5.2 Treatment Objective: Cariës rechterbovenkies restaureren

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|ff0bf74b-fb91-4054-acdc-4359df96036f (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|DesiredHealthcareResult|Cariës rechterbovenkies restaureren|
|DesiredHealthCondition - StatusName||
|DesiredHealthCondition - StatusValue||
|DesiredHealthCondition - StatusDate||
|DesiredHealthCondition - Comment||
|DesiredHealthCondition - MedicalDevice||
|Problem||
|Priority|Hoge prioriteit (code 'high-priority' from code system 'GoalPriority')|

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 6. MedMij Core: Health Professional data 1.0.0-rc.3 (referentiedata)

### 6.1 Health Professional: A.B.D.O. de Koning

|Veld|Waarde|
|:--|:--|
|HealthProfessionalIdentificationNumber|12070100 (in identifier system 'BIG register inschrijvingsnummer')|
|NameInformation - FirstNames||
|NameInformation - Initials|A.B.D.O.|
|NameInformation - GivenName||
|NameInformation - NameUsage||
|NameInformation - LastName - Prefix|de|
|NameInformation - LastName - LastName|Koning|
|NameInformation - LastNamePartner - PartnerPrefix||
|NameInformation - LastNamePartner - PartnerLastName||
|NameInformation - Titles||
|Speciality|Tandartsen, algemeen practicus (code '1200' from code system 'Vektis AGB-medische specialismen')|
|Gender||
|AddressInformation - Street|Simon Smitweg|
|AddressInformation - HouseNumber|1|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|2353 GA|
|AddressInformation - PlaceOfResidence|Leiderdorp|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31612345601|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<dekoning@tandarts.nl>|
|ContactInformation - EmailAddresses - EmailAddressType|Zakelijk e-mailadres (code 'WP' from code system 'AddressUse')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|HealthProfessionalRole||

### 6.2 Health Professional: S. Vermeer

|Veld|Waarde|
|:--|:--|
|HealthProfessionalIdentificationNumber|87001201 (in identifier system 'BIG register inschrijvingsnummer')|
|NameInformation - FirstNames||
|NameInformation - Initials|S.|
|NameInformation - GivenName||
|NameInformation - NameUsage||
|NameInformation - LastName - Prefix||
|NameInformation - LastName - LastName|Vermeer|
|NameInformation - LastNamePartner - PartnerPrefix||
|NameInformation - LastNamePartner - PartnerLastName||
|NameInformation - Titles||
|Speciality|Mondhygiënisten (code '8700' from code system 'Vektis AGB-medische specialismen')|
|Gender|Vrouw (code 'F' from code system 'AdministrativeGender')|
|AddressInformation - Street|Simon Smitweg|
|AddressInformation - HouseNumber|1|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|2353 GA|
|AddressInformation - PlaceOfResidence|Leiderdorp|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31612345603|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<vermeer@mondhygienist.nl>|
|ContactInformation - EmailAddresses - EmailAddressType|Zakelijk e-mailadres (code 'WP' from code system 'AddressUse')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|HealthProfessionalRole||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 7 MedMij Core: Healthcare Provider 1.0.0-rc.3 (referentiedata)

### 7.1 Healthcare Provider: Mondzorgcentrum Lindenhof

|Veld|Waarde|
|:--|:--|
|HealthcareProviderIdentificationNumber|12999001 (in identifier system 'Vektis AGB-zorgverlener tabel')|
|OrganizationName|Mondzorgcentrum Lindenhof|
|DepartmentSpeciality|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ContactInformation - TelephoneNumbers - TelephoneNumber|+31612345602|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress|<info@lindenhof-mondzorg.nl>|
|ContactInformation - EmailAddresses - EmailAddressType|Zakelijk e-mailadres (code 'WP' from code system 'AddressUse')|
|AddressInformation - Street|Meidoornlaan|
|AddressInformation - HouseNumber|15|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|9991 XX|
|AddressInformation - PlaceOfResidence|Leiderdorp|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|OrganizationType||
|OrganizationLocation - LocationName||
|OrganizationLocation - LocationNumber||

### 7.2 Healthcare Provider: Praktijklocatie Lindenhof

|Veld|Waarde|
|:--|:--|
|HealthcareProviderIdentificationNumber||
|OrganizationName|Praktijklocatie Lindenhof|
|DepartmentSpeciality||
|ContactInformation - TelephoneNumbers - TelephoneNumber|0881234567|
|ContactInformation - TelephoneNumbers - TelecomType||
|ContactInformation - TelephoneNumbers - NumberType|Zakelijk telefoonnummer (code 'WP' from code system 'AddressUse')|
|ContactInformation - TelephoneNumbers - Comment||
|ContactInformation - EmailAddresses - EmailAddress||
|ContactInformation - EmailAddresses - EmailAddressType||
|AddressInformation - Street|Heideweg|
|AddressInformation - HouseNumber|3|
|AddressInformation - HouseNumberLetter||
|AddressInformation - HouseNumberAddition||
|AddressInformation - HouseNumberIndication||
|AddressInformation - Postcode|9992 XX|
|AddressInformation - PlaceOfResidence|Leiderdorp|
|AddressInformation - Municipality||
|AddressInformation - Country|Nederland (code 'NL' from code system 'ISO 3166-1 (alpha-2)')|
|AddressInformation - AdditionalInformation||
|AddressInformation - AddressType|Werkadres (code 'WP' from code system 'AddressUse')|
|OrganizationType||
|OrganizationLocation - LocationName||
|OrganizationLocation - LocationNumber||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 8. Verzamelen Mondzorg: Cariësrisico 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|96a93ed3-7a65-4bf8-a656-ec975732f73e (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025 10:30|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|CariesRiskValue|verhoogd (code '35105006' from code system 'SNOMED CT')|
|Performer|A.B.D.O. de Koning, Tandarts|
|Comment|Advies: frequentie van suikerhoudende tussendoortjes beperken.|

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 9. Verzamelen Mondzorg: Dental Fitness 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|3fd0d3e1-960d-4a05-8ab5-76adbc1ecdce (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025 10:15|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|DentalFitnessValue|klasse 2 (code '258393007' from code system 'SNOMED CT')|
|Performer|A.B.D.O. de Koning, Tandarts|
|Comment|Actieve cariës en gingivitis; restauratieve behandeling gepland.|

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 10. Verzamelen Mondzorg: Mondhygiëne 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|cc98117d-988c-4d3a-990a-a831fe580d8a (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025 10:45|
|CareType|Mondhygiënisten (code '8700' from code system 'Vektis AGB-medische specialismen')|
|OralHygieneValue|slecht (code '556001' from code system 'SNOMED CT')|
|Performer|S. Vermeer, Mondhygiënist|
|Comment||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 11. Verzamelen Mondzorg: Parafunctionele activiteit 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|525c56a1-d0b7-4ee2-8825-32db8f8148e4 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025 10:10|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ParafunctionalActivityValue|Overmatig knarsen bij stress|
|Performer|A.B.D.O. de Koning, Tandarts|
|Comment||

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 12. Verzamelen Mondzorg - Periodieke Parodontale Screening-score 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|8fed8eb5-5353-4ae6-88dc-ab283ad0afb3 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|EffectiveDateTime|20-05-2025 10:05|
|CareType|Mondhygiënisten (code '8700' from code system 'Vektis AGB-medische specialismen')|
|PeriodicPeriodontalScreeningScoreValue|Pockets 0-3 millimeter = in orde (code 'ppsscore1' from code system 'PeriodicPeriodontalScreeningScore')|
|Performer|S. Vermeer, Mondhygiënist|
|Comment|Geen parodontale vervolgbehandeling; wel gingivitis bij slechte mondhygiëne|

[Terug naar boven](#testdossier1-xxx_vanoranje)

## 13. Verzamelen Mondzorg - Verrichting 1.0.0-rc2

|Veld|Waarde|
|:--|:--|
|IdentificationNumber|1c2c7df9-8a1f-4ef9-9bfd-3640f8e39ec1 (in identifier system '<https://mondzorgcentrum-lindenhof.nl/fhir/NamingSystem/resource-business-identifier>')|
|HealthcareProvider|Mondzorgcentrum Lindenhof|
|StartDateTime|03-06-2025 09:00|
|EndDateTime|03-06-2025 09:45|
|CareType|Tandartsen (code '1200' from code system 'Vektis AGB-medische specialismen')|
|ProcedureType|Eénvlaksvulling composiet (code 'V91' from code system 'Vektis Prestatiecodelijst Mondzorg')|
|ProcedureMethod|inbrengen (code '257867005' from code system 'SNOMED CT')|
|ProcedureAnatomicalLocation - Location|tand en/of kies (code '38199008' from code system 'SNOMED CT')|
|ProcedureAnatomicalLocation - Laterality|Rechts (code '24028007' from code system 'SNOMED CT')|
|Indication - ProblemType|Diagnose (code '282291009' from code system 'SNOMED CT')|
|Indication - ProblemName|gaatje in je tand of kies (code '80967001' from code system 'SNOMED CT')|
|Indication - FurtherSpecificationProblemName|Cariës rechterbovenkies|
|Indication - ProblemAnatomicalLocation - Location|tand en/of kies (code '38199008' from code system 'SNOMED CT')|
|Indication - ProblemAnatomicalLocation - Laterality|Rechts (code '24028007' from code system 'SNOMED CT')|
|Indication - ProblemStartDate|20-05-2025 10:00|
|Indication - ProblemEndDate||
|Indication - ProblemStatus|Actueel (code '55561003' from code system 'SNOMED CT')|
|Indication - VerificationStatus|Bevestigd (code '410605003' from code system 'SNOMED CT')|
|Indication - Comment|Actieve cariës vastgesteld tijdens periodiek preventief onderzoek. Restauratieve behandeling (éénvlaksvulling) en preventief advies besproken.|
|Location|Praktijklocatie Lindenhof|
|Performer|A.B.D.O. de Koning, Tandarts|

[Terug naar boven](#testdossier1-xxx_vanoranje)
