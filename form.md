Proposal for the [IANA Application](https://www.iana.org/form/media-types) for an OpenTimeStamps Media Type.

| Field Name | Value | Note |
|--|--|--|
| Your Full Name | Emanuele Cisbani ||
|Your E-mail | ecisbani@intesigroup.com ||
| Type Name | application ||
| Subtype Name | vnd.opentimestamps.ots ||
| Required Parameters
| Optional Parameters
| Encoding Considerations | binary ||
| Security Considerations | OTS files contain URLs pointing to the server that provided it. Applications can ignore URLs if not trusted ||
| Interoperability Considerations
| Published specification
| Application Usage | OpenTimestamps calendar server and client for distributed ledgers (aka blockchain) timestamping. See opentimestamps.org for more details. ||
| Fragment Identifier Considerations
| Restrictions on Usage
| Provisional Registrations
| Additional Information - Deprecated alias names for this type
| Additional Information - Magic number(s) | 32 bytes 00 4f 70 65 6e 54 69 6d 65 73 74 61 6d 70 73 00 ... ||
| Additional Information - File extension(s)
| Additional Information - Macintosh File Type Code(s)
| Additional Information - Object Identifier(s) or OID(s)
| Intended Usage | common ||
| Other Information & Comments | The complete magic numbers list is: <br /> 00 4f 70 65 6e 54 69 6d 65 73 74 61 6d 70 73 00 <br /> 00 50 72 6f 6f 66 00 bf 89 e2 e8 84 e8 92 94 01 <br /> where the last byte of that header is the major <br /> version number, 1 in this case ||
| Contact Person - Contact Name | Emanuele Cisbani ||
| Contact Person - Contact Email Address | ecisbani@intesigroup.com ||
