# NCT Device Catalogue

Checked device identities for Hanwha/Samsung and Hikvision. Public downloads require no GitHub account.

## Coverage

Catalogue version 2026103103 contains 674 records: 503 Hanwha/Samsung and 171 Hikvision. This is an initial checked subset, not an exhaustive manufacturer inventory. Regional editions and older product portfolios are retained as evidence; inclusion does not imply current availability or a successful discovery test.

Sources include Hanwha's 2024 global product portfolio and official product listings, and Hikvision's 2025 USA Product & Solution Quick Guide. Additional Hanwha/Samsung models are verified directly against exact official product-detail metadata, so newer products are not excluded merely because an older PDF omits them. Each record links to its official source, including the PDF page where relevant. Network cameras, NVRs, network-capable DVRs and encoders are included. Accessories, analogue-only cameras, ambiguous variants and incomplete extracted model strings are excluded from this checked release.

## Publication

Reviewed payloads are signed by the maintainer outside this repository. NCT checks the pinned public key, checksum, schema and increasing version before applying updates. Candidate collection never directly changes trusted catalogue entries. Source provenance identifies the model; it does not prove a particular discovery method passed.

Only public model/manufacturer/type/source information belongs here. Never add device observations, customer/site data, credentials, private signing keys or diagnostic sessions. Automatic contributions will use a private pending service; that service is not deployed yet.

Catalogue endpoint: https://raw.githubusercontent.com/anoraq1/nct-device-catalogue/main/index.json
Catalogue update indexes point to immutable versioned filenames so a newly fetched index cannot accidentally download a cached older catalogue.
