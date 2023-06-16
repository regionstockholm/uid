# URI-based identifiers for Region Stockholm Gotland

## Introduction
Within Region Stockholm Gotland, different types of identifiers are used in existing IT systems, such as kombika-codes or unit identifiers within the electronic healthrecord (EHR) system TakeCare. When systems are to communicate with each other, it should be made clear to the systems what type of identifier is being transferred, so a way of identifying identifiers is needed. This can be done with so-called URIs (universal resource identifiers).

An identifier system is a managed collection of identifiers. Identifiers are used to identify a concepts, people etc. Identifiers belonging to a specific Identifier system can follow a certain format. Exampels of identifier systems within Sweden are Personnummer, Samordningsnummer eller Reservnummer.

See https://build.fhir.org/identifier-registry.html for international examples of Identifier systems

## Existing URIs
The following URIs are used within Region Stockholm Gotland:

|UniqueId.type|UniqueId.value|Name|Title|Status|Kind|Date|Description|
|---|---|---|---|---|---|---|---|
|uri|https://uid.regionstockholm.se/takecare/unitId|takeCareUnitId|TakeCare enhets-id|draft|identifier|2023-06-16|The URI identifies unit identifiers used within the EHR system TakeCare.|
|uri|https://uid.regionstockholm.se/kombika|kombikaCode|Kombikakod|draft|identifier|2023-06-16|The URI identifies kombika-codes.|
|uri|https://uid.regionstockholm.se/openehr/ehrid|||draft|identifier|2023-06-16|The URI identifies ....|

The table column headings are based on attributes in the FHIR NamingSystem-resource: https://hl7.org/fhir/namingsystem.html


## Governance
The URIs are managed by ...

If you have questions about the identifiers, please contact: ...
