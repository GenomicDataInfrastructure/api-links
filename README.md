# api-links
Links to definitions and documentation for APIs used within GDI

GDI needs to support a diverse range of deployments, and different products from the starter kit maybe replaced. As such there is a need to move from a product defined to API defined infrastructure within GDI. This repo is therefore a place to link to the API specifications, and / or associated standard specifications.

## LifeScience AAI

- [OpenID Connect Core specification](https://openid.net/specs/openid-connect-core-1_0.html)
- [GA4GH AAI OpenID Connect Profile specification](https://ga4gh.github.io/data-security/aai-openid-connect-profile)
- [GA4GH Passport specification](https://ga4gh.github.io/data-security/ga4gh-passport)
- LifeScience AAI Identity Management API [openapi.yml](https://raw.githubusercontent.com/CESNET/perun/main/perun-openapi/openapi.yml) 

## Beacon & Beacon Network

- [GA4GH Beacon v2 specification](https://github.com/ga4gh-beacon/beacon-v2)
- [GA4GH Beacon v2 documentation](https://docs.genomebeacons.org/)

## 📦 FAIR Data Point (FDP) and metadata profiles

- Implementations of the FAIR Data Point principle must conform to FDP specification v1.2: https://specs.fairdatapoint.org/fdp-specs-v1.2.html
- Metadata, whether in a full FDP deployment or provided as a standalone RDF file, must align with the GDI harmonised metadata spreadsheet (leading), and then HealthDCAT-AP 5.0:
  - GDI harmonised metadata spreadsheet v1.1: https://docs.google.com/spreadsheets/d/1HpznG8yTcs7if0xqNSpZZIGpbEe7_3ZG6_nF1YeJmSA/edit?gid=225294581#gid=225294581
  - HealthDCAT-AP 5.0: https://healthdataeu.pages.code.europa.eu/healthdcat-ap/releases/release-5/
- SHACL shapes for validating FDP metadata: https://github.com/GenomicDataInfrastructure/gdi-metadata
