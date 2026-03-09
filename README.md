# APIs
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
- [GDI Beacon v2 guidelines](https://docs.google.com/document/d/1nytWC6QOvaLmoJd0OBOENc52gEXagXzI)

## 📦 FAIR Data Point (FDP) and GDI dataset profile

Implementations of a FAIR Data Point must conform to the FDP specification v1.2
https://specs.fairdatapoint.org/fdp-specs-v1.2.html
Metadata exposed through the FDP (or provided as standalone RDF) must comply with the GDI metadata profile, which builds on HealthDCAT-AP 6.0.
- GDI metadata documentation
  https://github.com/GenomicDataInfrastructure/gdi-metadata/tree/main/Documentation
- HealthDCAT-AP 6.0 specification
  https://healthdataeu.pages.code.europa.eu/healthdcat-ap/releases/release-6/
Metadata should be validated using the GDI SHACL shapes:
https://github.com/GenomicDataInfrastructure/gdi-metadata
