Proposal for the [IANA Application](https://www.iana.org/form/media-types) for an OpenTimeStamps Media Type.

Request (Ticket) information [#1199397](https://tools.iana.org/public-view/viewticket/1199397) 

| Field Name | Value | Note |
|--|--|--|
| Your Full Name | Emanuele Cisbani ||
|Your E-mail | ecisbani@intesigroup.com ||
| Type Name | application ||
| Subtype Name | vnd.opentimestamps.ots ||
| Required Parameters | There are no Required Parameters ||
| Optional Parameters | There are no Optional Parameters ||
| Encoding Considerations | binary ||
| Security Considerations | OTS files contain URLs pointing to the server that provided it. Applications can ignore URLs if not trusted. This media type does not contain active or executable content. The information contained in the media type does not need integrity services. Considering the information is made by hashes, integrity can be verified only by having the original document that is not included in the media type. No personal data are directly exposed because the information is a timestamp that can only proof the original document existed at a defined date. Protecting this indirect information alone with standard encryption is an extremely rare use case. It's often the case that timestamps are provided bundled with the referring documents. Links are referenced in order to get additional information, they are not necessary to properly interpret the type. ||
| Interoperability Considerations | Bytes ordering is little-endian ||
| Published specification | Not currently available ||
| Application Usage | OpenTimestamps calendar server and client for distributed ledgers (aka blockchain) timestamping. See opentimestamps.org for more details. ||
| Fragment Identifier Considerations | N/A ||
| Restrictions on Usage | intended for common use ||
| Provisional Registrations | N/A ||
| Additional Information - Deprecated alias names for this type | not defined ||
| Additional Information - Magic number(s) | Proof files start with: 00 4f 70 65 6e 54 69 6d 65 73 74 61 ||
| Additional Information - File extension(s) | ots ||
| Additional Information - Macintosh File Type Code(s) | not defined ||
| Additional Information - Object Identifier(s) or OID(s) | not defined ||
| Intended Usage (combo)| Common ||
| Intended Usage (text)| Usage is aimed at opentimestamps clients or any software that wishes to view or verify the content of an opentimestamps proof ||
| Other Information & Comments | The complete magic numbers list is: <br /> 00 4f 70 65 6e 54 69 6d 65 73 74 61 6d 70 73 00 <br /> 00 50 72 6f 6f 66 00 bf 89 e2 e8 84 e8 92 94 01 <br /> where the last byte of that header is the major <br /> version number, 1 in this case ||
| Contact Person (Contact Name) | Peter Todd ||
| Contact Person (Contact Email Address) | pete@petertodd.org ||
| Contact Person (Author/Change Controller) | OpenTimestamps developer team <br /> https://github.com/orgs/opentimestamps/people ||
